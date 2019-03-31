[haiku gsoc 2019 ideas](https://www.haiku-os.org/community/gsoc/2019/ideas#kernel)

[haiku gsoc 2019 student](https://www.haiku-os.org/community/gsoc/2019/students)



# File Systems: general improvements and new filesystems.

Haiku has great support for its own file system, but is completely missing support for some other fielsystems. It is way better for interoperability with other systems to be able to read and write to these disks.

The goal of this project is to port one of the following filesystems to Haiku:

1. HAMMER FS: [homepage](http://www.dragonflybsd.org/hammer/), [sourcecode](http://fxr.watson.org/fxr/source/vfs/hammer/?v=DFBSD) (3-clause BSD, a port of the existing code is ok)

It's okay to port over the code from other systems, although we prefer code that can be distributed under the MIT license.

- Skill set: kernel, and driver development
- Possible mentors/knowledgeable people: PulkoMandy, waddlesplash



# TODO

要修改的目录

- haiku/src/build/libroot
- haiku/src/add-ons/kernel/file_systems



# Analysis of the HAMMER FS

```
├── Makefile
├── hammer.h
├── hammer_blockmap.c
├── hammer_btree.c
├── hammer_btree.h
├── hammer_crc.h
├── hammer_cursor.c
├── hammer_cursor.h
├── hammer_dedup.c
├── hammer_disk.h
├── hammer_flusher.c
├── hammer_inode.c
├── hammer_io.c
├── hammer_ioctl.c
├── hammer_ioctl.h
├── hammer_mirror.c
├── hammer_mount.h
├── hammer_object.c
├── hammer_ondisk.c
├── hammer_pfs.c
├── hammer_prune.c
├── hammer_rebalance.c
├── hammer_reblock.c
├── hammer_recover.c
├── hammer_redo.c
├── hammer_signal.c
├── hammer_subs.c
├── hammer_transaction.c
├── hammer_undo.c
├── hammer_vfsops.c
├── hammer_vnops.c
└── hammer_volume.c
```

The following entry need to change:

1. type, such int64_t and so on
2. `vm_page_count_min` at blackcap.c, at vm_page2.h
3. `vm_page_count_severe()` at inode.c, at vm_page2.h
4.



### Macro: NULL in _null.h
(All the C file)
hammer_subs.c
hammer_transaction.c
hammer_undo.c
hammer_vfsops.c
hammer_vnops.c
hammer_volume.c
hammer_object.c
hammer_ondisk.c
hammer_pfs.c
hammer_prune.c
hammer_rebalance.c
hammer_reblock.c
hammer_recover.c
hammer_redo.c
hammer_mirror.c
hammer_flusher.c
hammer_inode.c
hammer_io.c
hammer_ioctl.c
hammer_cursor.c
hammer_dedup.c
hammer_blockmap.c
hammer_btree.c

### Function: kfree in kern_slaballoc.c
hammer_blockmap.c
hammer_btree.c
hammer_cursor.c
hammer_flusher.c
hammer_inode.c
hammer_object.c
hammer_ondisk.c
hammer_prune.c
hammer_recover.c
hammer_transaction.c
hammer_vfsops.c
hammer_vnops.c

### Function: kmalloc in kern_slaballoc.c
hammer_blockmap.c
hammer_btree.c
hammer_cursor.c
hammer_flusher.c
hammer_inode.c
hammer_object.c
hammer_ondisk.c
hammer_prune.c
hammer_recover.c
hammer_transaction.c
hammer_vfsops.c
hammer_vnops.c

### Macro: M_USE_RESERVE in malloc.h
hammer_blockmap.c
hammer_object.c
hammer_ondisk.c

### Macro: M_WAITOK in malloc.h
hammer_blockmap.c
hammer_btree.c
hammer_cursor.c
hammer_flusher.c
hammer_inode.c
hammer_object.c
hammer_ondisk.c
hammer_prune.c
hammer_recover.c
hammer_transaction.c
hammer_vfsops.c
hammer_vnops.c

### Macro: M_ZERO in malloc.h
hammer_blockmap.c
hammer_btree.c
hammer_cursor.c
hammer_flusher.c
hammer_inode.c
hammer_object.c
hammer_ondisk.c
hammer_recover.c
hammer_transaction.c
hammer_vfsops.c

### Macro: TAILQ_INSERT_HEAD in queue.h
hammer_transaction.c

### Macro: TAILQ_INSERT_TAIL in queue.h
hammer_blockmap.c
hammer_btree.c
hammer_cursor.c
hammer_inode.c
hammer_io.c
hammer_object.c
hammer_ondisk.c
hammer_transaction.c
hammer_undo.c

### Macro: TAILQ_REMOVE in queue.h
hammer_blockmap.c
hammer_btree.c
hammer_cursor.c
hammer_inode.c
hammer_io.c
hammer_object.c
hammer_ondisk.c
hammer_transaction.c
hammer_undo.c
hammer_vfsops.c

### Macro: TAILQ_EMPTY in queue.h
hammer_btree.c
hammer_inode.c
hammer_io.c
hammer_ondisk.c

### Macro: TAILQ_FIRST in queue.h
hammer_btree.c
hammer_cursor.c
hammer_inode.c
hammer_io.c
hammer_ondisk.c
hammer_rebalance.c
hammer_transaction.c
hammer_undo.c
hammer_vfsops.c

### Macro: TAILQ_FOREACH in queue.h
hammer_btree.c
hammer_cursor.c
hammer_inode.c
hammer_io.c
hammer_rebalance.c

### Macro: TAILQ_INIT in queue.h
hammer_btree.c
hammer_inode.c
hammer_ondisk.c
hammer_undo.c
hammer_vfsops.c

### Macro: TAILQ_ENTRY in queue.h
hammer_flusher.c

### Macro: TAILQ_NEXT in queue.h
hammer_flusher.c
hammer_inode.c
hammer_io.c
hammer_rebalance.c

### Macro: RB_GENERATE2 in tree.h
hammer_blockmap.c
hammer_ondisk.c
hammer_redo.c
hammer_undo.c

### Macro: RB_INSERT in tree.h
hammer_blockmap.c
hammer_io.c
hammer_object.c
hammer_ondisk.c
hammer_recover.c
hammer_redo.c
hammer_undo.c

### Macro: RB_LOOKUP in tree.h
hammer_blockmap.c
hammer_ondisk.c
hammer_undo.c

### Macro: RB_REMOVE in tree.h
hammer_blockmap.c
hammer_io.c
hammer_object.c
hammer_ondisk.c
hammer_recover.c
hammer_redo.c
hammer_undo.c

### Macro: RB_EMPTY in tree.h
hammer_flusher.c
hammer_object.c
hammer_ondisk.c
hammer_vfsops.c

### Macro: RB_FIRST in tree.h
hammer_flusher.c
hammer_redo.c

### Macro: RB_GENERATE in tree.h
hammer_flusher.c
hammer_io.c
hammer_object.c
hammer_recover.c

### Macro: RB_ROOT in tree.h
hammer_flusher.c
hammer_recover.c

### Macro: RB_SCAN in tree.h
hammer_flusher.c
hammer_recover.c
hammer_vfsops.c
hammer_volume.c

### Macro: RB_GENERATE_XLOOKUP in tree.h
hammer_inode.c

### Macro: RB_INIT in tree.h
hammer_inode.c
hammer_recover.c
hammer_undo.c
hammer_vfsops.c

### Macro: RB_FOREACH in tree.h
hammer_io.c

### Macro: RB_ENTRY in tree.h
hammer_recover.c

### Macro: RB_FIND in tree.h
hammer_recover.c

### Macro: RB_HEAD in tree.h
hammer_recover.c

### Macro: RB_PROTOTYPE in tree.h
hammer_recover.c

### vm_page2.h
hammer_blockmap.c
hammer_inode.c

### Function: lwkt_user_yield in lwkt_thread.c
hammer_btree.c
hammer_signal.c

### Function: lwkt_create in lwkt_thread.c
hammer_flusher.c

### Function: lwkt_exit in lwkt_thread.c
hammer_flusher.c

### Function: lwkt_gettoken in lwkt_token.c
hammer_flusher.c
hammer_inode.c
hammer_io.c
hammer_ondisk.c
hammer_transaction.c
hammer_vfsops.c
hammer_vnops.c

### Function: lwkt_reltoken in lwkt_token.c
hammer_flusher.c
hammer_inode.c
hammer_io.c
hammer_ondisk.c
hammer_transaction.c
hammer_vfsops.c
hammer_vnops.c

### Function: bzero in memset.c
hammer_btree.c
hammer_cursor.c
hammer_io.c
hammer_ioctl.c
hammer_mirror.c
hammer_ondisk.c
hammer_pfs.c
hammer_recover.c
hammer_subs.c
hammer_transaction.c
hammer_undo.c
hammer_vfsops.c
hammer_volume.c
hammer_vnops.c

### Typedef: size_t in mman.h
hammer_btree.c
hammer_crc.h
hammer_recover.c
hammer_vfsops.c
hammer_vnops.c

### Function: bcopy in os.c
hammer_btree.c
hammer_cursor.c
hammer_flusher.c
hammer_inode.c
hammer_io.c
hammer_object.c
hammer_ondisk.c
hammer_reblock.c
hammer_recover.c
hammer_redo.c
hammer_undo.c
hammer_vfsops.c
hammer_vnops.c

### Function: kprintf in subr_prf.c
hammer_btree.c
hammer_flusher.c
hammer_ondisk.c
hammer_rebalance.c
hammer_vfsops.c
hammer_volume.c

### Function: iscsi_crc32 in icrc32.c
hammer_crc.h

### Function: iscsi_crc32_ext in icrc32.c
hammer_crc.h

### Function: crc32 in crc32.c
hammer_crc.h

### Function: crc32_ext in crc32.c
hammer_crc.h
hammer_mirror.c

### Typedef: u_int in defines.h
hammer_cursor.c
hammer_subs.c

### Macro: __noinline in cdefs.h
hammer_cursor.c

### uuid.h
hammer_disk.h (13)

### Typedef: uuid_t in uuid.h
hammer_disk.h (13)

### Macro: offsetof in route6d.c
hammer_disk.h (13)
hammer_ioctl.h

### endian.h
hammer_disk.h (13)

### Macro: __packed in cdefs.h
hammer_disk.h (13)

### Function: vm_wait_nominal in vm_page.c
hammer_flusher.c
hammer_reblock.c

### Typedef: thread_t in thread.h
hammer_flusher.c
hammer_subs.c
hammer_vnops.c

### Struct: vop_inactive_args in vfsops.h
hammer_inode.c

### Struct: vop_reclaim_args in vfsops.h
hammer_inode.c

### Struct: vattr in vfscache.h
hammer_inode.c
hammer_recover.c
hammer_vnops.c

### Function: nvtruncbuf in vfs_vm.c
hammer_inode.c
hammer_vnops.c

### Function: vclrisdirty in vfs_sync.c
hammer_inode.c
hammer_ondisk.c
hammer_vnops.c

### Function: vsetisdirty in vfs_sync.c
hammer_inode.c

### Function: addaliasu in vfs_subr.c
hammer_inode.c

### Function: vattr_null in vfs_subr.c
hammer_inode.c

### Function: vclean_unlocked in vfs_subr.c
hammer_inode.c

### Function: vinitvmio in vfs_subr.c
hammer_inode.c

### Function: vrecycle in vfs_subr.c
hammer_inode.c

### Macro: VISDIRTY in vfs_subr.c
hammer_inode.c

### Macro: VPFSROOT in vfs_subr.c
hammer_inode.c

### Macro: VRECLAIMED in vfs_subr.c
hammer_inode.c
hammer_vnops.c

### Macro: VROOT in vfs_subr.c
hammer_inode.c

### Function: getnewvnode in vfs_mount.c
hammer_inode.c

### Function: vdrop in vfs_lock.c
hammer_inode.c

### Function: vget in vfs_lock.c
hammer_inode.c

### Function: vhold in vfs_lock.c
hammer_inode.c

### Function: vput in vfs_lock.c
hammer_inode.c
hammer_io.c
hammer_recover.c
hammer_vfsops.c

### Function: vsetflags in vfs_lock.c
hammer_inode.c

### Function: vx_put in vfs_lock.c
hammer_inode.c

### Function: vop_helper_create_uid in vfs_helper.c
hammer_inode.c

### Struct: ucred in ucred.h
hammer_inode.c
hammer_ioctl.c
hammer_ondisk.c
hammer_pfs.c
hammer_vfsops.c
hammer_vnops.c

### Typedef: gid_t in types.h
hammer_inode.c
hammer_vnops.c

### Typedef: uid_t in types.h
hammer_inode.c
hammer_vnops.c

### Macro: SF_NOHISTORY in stat.h
hammer_inode.c
hammer_subs.c

### Macro: UF_NODUMP in stat.h
hammer_inode.c

### Macro: UF_NOHISTORY in stat.h
hammer_inode.c
hammer_subs.c

### Typedef: pid_t in spawn.h
hammer_inode.c

### Struct: krate in resourcevar.h
hammer_inode.c

### Macro: MNT_NOATIME in moumt.h
hammer_inode.c
hammer_vfsops.c
hammer_vnops.c

### Typedef: off_t in mman.h
hammer_inode.c
hammer_object.c
hammer_vnops.c

### Macro: LK_EXCLUSIVE in lock.h
hammer_inode.c
hammer_recover.c

### Function: getmicrotime in kern_clock.c
hammer_inode.c
hammer_transaction.c

### Macro: VNOVAL in dirfs_vnops.c
hammer_inode.c
hammer_vnops.c

### Macro: __unused in cdefs.h
hammer_inode.c
hammer_object.c
hammer_ondisk.c
hammer_subs.c

### Struct: vnode in buf.h
hammer_inode.c
hammer_io.c
hammer_ondisk.c
hammer_recover.c
hammer_vfsops.c
hammer_vnops.c

### Struct: timeval in bsd-misc.h (3)
hammer_inode.c
hammer_transaction.c

### Function: getpbuf in vm_pager.c
hammer_io.c

###  Function: relpbuf in vm_pager.c
hammer_io.c

### Macro: B_NOCACHE in vfs_vm.c
hammer_io.c

### Macro: B_RELBUF in vfs_vm.c
hammer_io.c

### Macro: NOOFFSET in vfs_vm.c
hammer_io.c
hammer_vnops.c

### Function: cluster_awrite in vfs_cluster.c
hammer_io.c

### Function: cluster_readcb in vfs_cluster.c
hammer_io.c

### Function: bdwrite in vfs_bio.c
hammer_io.c
hammer_vnops.c

### Function: biodone in vfs_bio.c
hammer_io.c
hammer_vnops.c

### Function: biowait in vfs_bio.c
hammer_io.c

### Function: bpdone in vfs_bio.c
hammer_io.c

### Function: bqrelse in vfs_bio.c
hammer_io.c
hammer_vnops.c

### Function: breadcb in vfs_bio.c
hammer_io.c

### Function: bremfree in vfs_bio.c
hammer_io.c

### Function: bundirty in vfs_bio.c
hammer_io.c

### Function: findblk in vfs_bio.c
hammer_io.c

### Function: pop_bio in vfs_bio.c
hammer_io.c

### Function: push_bio in vfs_bio.c
hammer_io.c
hammer_vnops.c

### Function: regetblk in vfs_bio.c
hammer_io.c

### Function: vfs_bio_clrbuf in vfs_bio.c
hammer_io.c
hammer_vnops.c

### Function: vn_strategy in vfs_bio.c
hammer_io.c

### Function: waitrunningbufspace in vfs_bio.c
hammer_io.c

### Function: getblk in utilities.c
hammer_io.c
hammer_vnops.c

### Macro: B_CLUSTEROK in ufs_readwrite.c
hammer_io.c
hammer_vnops.c

### Macro: B_AGE in subr_diskgpt.c
hammer_io.c
hammer_vnops.c

### Macro: B_INVAL in subr_diskgpt.c
hammer_io.c
hammer_vnops.c

### Function: bread in quotacheck.c
hammer_io.c
hammer_ondisk.c
hammer_vnops.c

### Macro: PINTERLOCKED in param.h
hammer_io.c
hammer_ioctl.h
hammer_subs.c

### Macro: FINDBLK_TEST in nfs_serv.c
hammer_io.c

### Function: tsleep_interlock in kern_synch.c
hammer_io.c
hammer_subs.c

### Macro: B_ERROR in dirfs_vnops.c
hammer_io.c
hammer_vnops.c

### Macro: B_NOTMETA in buf2.h
hammer_io.c
hammer_vnops.c

### buf2.h in buf2.h
hammer_io.c
hammer_ondisk.c
hammer_vnops.c

### Struct: buf in buf.h
hammer_io.c
hammer_ondisk.c
hammer_vnops.c

### Struct: bio in bio.h
hammer_io.c
hammer_vnops.c

### Typedef: caddr_t in types.h
hammer_ioctl.c
hammer_vfsops.c
hammer_vnops.c

### Typedef: u_long in types.h
hammer_ioctl.c

### Function: ksnprintf in subr_prf.c
hammer_ioctl.c
hammer_vfsops.c
hammer_volume.c
hammer_vnops.c

### Macro: PRIV_HAMMER_IOCTL in priv.h
hammer_ioctl.c

### Macro: PRIV_HAMMER_VOLUME in priv.h
hammer_ioctl.c

### Macro: MNT_NOWAIT in mount.h
hammer_ioctl.c
hammer_mount.h
hammer_ondisk.c
hammer_vnops.c

### Macro: MNT_WAIT in mount.h
hammer_ioctl.c
hammer_ondisk.c
hammer_vnops.c

### Macro: MNT_FORCE in mount.h
hammer_vfsops.c

### Macro: MNT_LOCAL in mount.h
hammer_vfsops.c

### Macro: MNT_UPDATE in mount.h
hammer_vfsops.c

### Function: priv_check_cred in kern_prot.c
hammer_ioctl.c

### Macro: MAXPATHLEN in param.h
hammer_ioctl.h
hammer_vfsops.c
hammer_volume.c

### Macro: _IOR in ioccom.h
hammer_ioctl.h

### Macro: _IOWR in ioccom.h
hammer_ioctl.h

### ioccom.h in ioccom.h
hammer_ioctl.h

### Function: copyin in uwrapper.c
hammer_mirror.c
hammer_object.c
hammer_pfs.c
hammer_prune.c
hammer_vfsops.c

### Macro: _SYS_TYPES_H_ in types.h
hammer_mount.h

### Macro: VINACTIVE in vfs_subr.c
hammer_object.c

### Struct: ip in ip.h
hammer_object.c

### Function: vn_lock in vfs_vnops.c
hammer_ondisk.c
hammer_recover.c

### Function: vn_unlock in vfs_vnops.c
hammer_ondisk.c
hammer_recover.c
hammer_vnops.c

### Function: vsyncscan in vfs_sync.c
hammer_ondisk.c

### Function: vcount in vfs_subr.c
hammer_ondisk.c

###  Function: vfs_mountedon in vfs_subr.c
hammer_ondisk.c

### Function: vinvalbuf in vfs_subr.c
hammer_ondisk.c

### Function: vn_isdisk in vfs_subr.c
hammer_ondisk.c

### Macro: V_SAVE in vfs_subr.c
hammer_ondisk.c

### Macro: VMSC_GETVP in vfs_subr.c
hammer_ondisk.c

### Macro: VMSC_NOWAIT in vfs_subr.c
hammer_ondisk.c

### Function: nlookup in vfs_nlookup.c
hammer_ondisk.c

### Function: nlookup_done in vfs_nlookup.c
hammer_ondisk.c

### Function: nlookup_init in vfs_nlookup.c
hammer_ondisk.c

### Macro: FREAD in fcntl.h
hammer_ondisk.c
hammer_recover.c

### Macro: FWRITE in fcntl.h
hammer_ondisk.c
hammer_recover.c
hammer_vnops.c

### Function: kstrdup in kern_slaballoc.c
hammer_ondisk.c

### Function: kuuid_compare in kern_uuid.c
hammer_ondisk.c
hammer_vnops.c

### Macro: LK_RETRY in lock.h
hammer_ondisk.c
hammer_recover.c

### Macro: MNT_LAZY in mount.h
hammer_ondisk.c

### Macro: MNT_RDONLY in mount.h
hammer_ondisk.c
hammer_vfsops.c
hammer_volume.c
hammer_vnops.c

### Struct: nlookupdata in nlookup.h
hammer_ondisk.c

### Macro: NLC_FOLLOW in nlookup.h
hammer_ondisk.c

### nlookup.h in nlookup.h
hammer_ondisk.c

### Function: krateprintf in subr_prf.c
hammer_ondisk.c

### Macro: FSCRED in ucred.h
hammer_ondisk.c

### Function: bwrite in utilities.c
hammer_ondisk.c
hammer_vnops.c

### Function: cache_vref in vfs_cache.c
hammer_ondisk.c

### Function: vrele in vfs_lock.c
hammer_ondisk.c
hammer_vnops.c

### Macro: VMSC_ONEPASS in vfs_mount.c
hammer_ondisk.c


### Macro: PCATCH in param.h
hammer_pfs.c

### Function: vm_test_nominal in vm_page.c
hammer_rebalance.c

### Function: vm_wait_nominal in vm_page.c
hammer_rebalance.c

### Function: bd_heatup in vfs_bio.c
hammer_reblock.c

### Function: bwillwrite in kern_iosched.c
hammer_reblock.c
hammer_vnops.c

### Struct: spinlock in spinlock.h
hammer_recover.c

### Function: vn_unlock in vfs_vnops.c
hammer_recover.c

### Function: __cursig in signal2.h
hammer_signal.c

### Macro: CURSIG_NOBLOCK in signal2.h
hammer_signal.c

### signal2.h in signal2.h
hammer_signal.c

###  Struct: timespec in _timespec.h
hammer_subs.c

### Macro: DT_BLK in dirent.h
hammer_subs.c

### Macro: DT_CHR in dirent.h
hammer_subs.c

### Macro: DT_DBF in dirent.h
hammer_subs.c

### Macro: DT_DIR in dirent.h
hammer_subs.c
hammer_vnops.c

### Macro: DT_FIFO in dirent.h
hammer_subs.c

### Macro: DT_LNK in dirent.h
hammer_subs.c

### Macro: DT_REG in dirent.h
hammer_subs.c

### Macro: DT_SOCK in dirent.h
hammer_subs.c

### Macro: DT_UNKNOWN in dirent.h
hammer_subs.c

### Function: strtoul in strtoul.c
hammer_subs.c
hammer_vnops.c

### Macro: udev_t in types.h
hammer_subs.c

### Typedef: dev_t in types.h
hammer_subs.c

### Struct: uuid in uuid.h
hammer_subs.c

### Function: objcache_get in kern_objcache.c
hammer_vfsops.c
### Function: objcache_put in kern_objcache.c
hammer_vfsops.c

### Function: kmalloc_create in kern_slaballoc.c
hammer_vfsops.c

### Function: kmalloc_destroy in kern_slaballoc.c
hammer_vfsops.c

### Function: kmalloc_limit in kern_slaballoc.c
hammer_vfsops.c

### Function: kmalloc_raise_limit in kern_slaballoc.c
hammer_vfsops.c

### Function: lwkt_token_init in lwkt_token.c
hammer_vfsops.c

### Struct: malloc_type in malloc.h
hammer_vfsops.c

### Macro: MALLOC_DEFINE in malloc.h
hammer_vfsops.c

### Struct: export_args in mount.h
hammer_vfsops.c
hammer_vnops.c

### Struct: fid in mount.h
hammer_vfsops.c

### Struct: statfs in mount.h
hammer_vfsops.c

### Struct: vfsconf in mount.h
hammer_vfsops.c

### Macro: MAXFIDSZ in mount.h
hammer_vfsops.c

### Macro: MNAMELEN in mount.h
hammer_vfsops.c

### Macro: MNTK_ALL_MPSAFE in mount.h
hammer_vfsops.c

### Macro: MNTK_FSMID in mount.h
hammer_vfsops.c

### Macro: MNTK_THR_SYNC in mount.h
hammer_vfsops.c

### Macro: MNTK_WANTRDWR in mount.h
hammer_vfsops.c

### Macro: VFCF_MPSAFEin mount.h
hammer_vfsops.c

### Macro: MOUNTCTL_SET_EXPORT in mountctl.h
hammer_vfsops.c
hammer_vnops.c

### mountctl.h in mountctl.h
hammer_vfsops.c
hammer_vnops.c

### Macro: FORCECLOSE in msdosfs_vfsops.c
hammer_vfsops.c

### Struct: sockaddr in socket.h
hammer_vfsops.c

### Struct: statvfs in statvfs.h
hammer_vfsops.c

### Function: strlen in strlen.c
hammer_vfsops.c
hammer_volume.c
hammer_vnops.c

### Macro: CTLFLAG_RD in sysctl.h
hammer_vfsops.c

### Macro: CTLFLAG_RW in sysctl.h
hammer_vfsops.c

### Macro: OID_AUTO
hammer_vfsops.c

### Typedef: ino_t in types.h
hammer_vfsops.c

### Typedef: qaddr_t in types.h
hammer_vfsops.c

### Function: kgetdiskbyname in vfs_conf.c
hammer_vfsops.c

### Function: vfs_add_vnodeops in vfs_init.c
hammer_vfsops.c

### Function: vflush in vfs_mount.c
hammer_vfsops.c

### Function: bdevvp in vfs_subr.c
hammer_vfsops.c

### Function: vfs_export in vfs_subr.c
hammer_vfsops.c

### Function: vfs_export_lookup in vfs_subr.c
hammer_vfsops.c

### Macro: B_RAM in buf.h
hammer_vnops.c

### Macro: B_VFSFLAG1 in buf.h
hammer_vnops.c

### Macro: GETBLK_BHEAVY in buf.h
hammer_vnops.c

### Macro: IO_APPEND in dirfs_vnops.c
hammer_vnops.c

### Macro: IO_SYNC in dirfs_vnops.c
hammer_vnops.c

### Macro: EV_EOF in event.h
hammer_vnops.c

### Macro: EV_NODATA in event.h
hammer_vnops.c

### Macro: EV_ONESHOT in event.h
hammer_vnops.c

### Macro: EVFILT_READ in event.h
hammer_vnops.c

### Macro: EVFILT_VNODE in event.h
hammer_vnops.c

### Macro: EVFILT_WRITE in event.h
hammer_vnops.c

### Macro: NOTE_ATTRIB in event.h
hammer_vnops.c

### Macro: NOTE_DELETE in event.h
hammer_vnops.c

### Macro: NOTE_EXTEND in event.h
hammer_vnops.c

### Macro: NOTE_LINK in event.h
hammer_vnops.c

### Macro: NOTE_RENAME in event.h
hammer_vnops.c

### Macro: NOTE_REVOKE in event.h
hammer_vnops.c

### Macro: NOTE_WRITE in event.h
hammer_vnops.c

### Macro: B_CACHE in ext2_inode.c
hammer_vnops.c

### fifo.h in fifo.h
hammer_vnops.c

### Function: fifo_vnoperate in fifo_vnops.c
hammer_vnops.c

### Object: fifo_vnode_vops in fifo_vnops.c
hammer_vnops.c

### Macro: NOTE_OLDAPI in hammer2_vnops.c
hammer_vnops.c

### Function: knote_insert in kern_event.c
hammer_vnops.c

###  Function: knote_remove in kern_event.c
hammer_vnops.c

### Function: lf_advlock in kern_lockf.c
hammer_vnops.c

### Function: lwpsignal in kern_sig.c
hammer_vnops.c

### Function: uiomove in kern_subr.c
hammer_vnops.c

### Function: uiomovebp in kern_subr.c
hammer_vnops.c'

### Typedef: mode_t in mman.h
hammer_vnops.c

### Macro: MNT_NOCLUSTERW in mount.h
hammer_vnops.c

### Macro: VOP_FSYNC_SYSCALL in mount.h
hammer_vnops.c

### Macro: MOUNTCTL_MOUNTFLAGS in mountctl.h
hammer_vnops.c

### Struct: namecache in namecache.h
hammer_vnops.c

### Struct: nchandle in namecache.h
hammer_vnops.c

### namecache.h in namecache.h
hammer_vnops.c

### Macro: MAXBSIZE in param.h
hammer_vnops.c

### Struct: proc in proc.h
hammer_vnops.c

### Macro: p_rlimit in proc.h
hammer_vnops.c

### Struct: rlimit in resource.h
hammer_vnops.c

### Struct: plimit in resourcevar.h
hammer_vnops.c

### Macro: SIGXFSZ in signal.h
hammer_vnops.c

### Function: strncmp in strncmp.c
hammer_vnops.c

### Struct: thread in thread.h
hammer_vnops.c

### Macro: APPEND in ufs_readwrite.c
hammer_vnops.c

### Macro: B_CLUSTEROK in ufs_readwrite.c
hammer_vnops.c

### Macro: IO_ASYNC in ufs_readwrite.c
hammer_vnops.c

### Macro: IO_DIRECT in ufs_readwrite.c
hammer_vnops.c

### Macro: VLASTWRITETS in ufs_readwrite.c
hammer_vnops.c

### Macro: FILTEROP_ISFD in usb_dev.c
hammer_vnops.c

### Macro: FILTEROP_MPSAFE in usb_dev.c
hammer_vnops.c

### Function: bawrite in vfs_bio.c
hammer_vnops.c

### Function: bheavy in vfs_bio.c
hammer_vnops.c

### Function: breadnx in vfs_bio.c
hammer_vnops.c

### Function: cache_rename in vfs_cache.c
hammer_vnops.c

### Function: cache_setunresolved in vfs_cache.c
hammer_vnops.c

### Function: cache_setvp in vfs_cache.c
hammer_vnops.c

### Function: cache_unlink in vfs_cache.c
hammer_vnops.c

### Function: cluster_readx in vfs_cluster.c
hammer_vnops.c

### Function: cluster_write in vfs_cluster.c
hammer_vnops.c

### Function: vop_stdclose in vfs_default.c
hammer_vnops.c

### Function: vop_stdmountctl in vfs_default.c
hammer_vnops.c

### Function: vop_stdopen in vfs_default.c
hammer_vnops.c

### Function: vop_helper_access in vfs_helper.c
hammer_vnops.c

### Function: vop_helper_chmod in vfs_helper.c
hammer_vnops.c

### Function: vop_helper_chown in vfs_helper.c
hammer_vnops.c

### Function: vop_helper_read_shortcut in vfs_helper.c
hammer_vnops.c

### Function: vop_helper_setattr_flags in vfs_helper.c
hammer_vnops.c

### Macro: IMMUTABLE in vfs_helper.c
hammer_vnops.c

### Function: vclrflags in vfs_lock.c
hammer_vnops.c

### Function: vx_lock in vfs_lock.c
hammer_vnops.c

### Function: vx_unlock in vfs_lock.c
hammer_vnops.c

### Function: vfs_flagstostr in vfs_subr.c
hammer_vnops.c

### Function: vfsync in vfs_subr.c
hammer_vnops.c

### Function: vop_write_dirent in vfs_subr.c
hammer_vnops.c

### Macro: B_PAGING in vfs_subr.c
hammer_vnops.c

### Function: nvextendbuf in vfs_vm.c
hammer_vnops.c

### Macro: IO_RECURSE in vfs_vnops.c
hammer_vnops.c

### Macro: VSWAPCACHE in vfs_vnops.c
hammer_vnops.c

### Struct: vop_access_args in vfsops.h
hammer_vnops.c

### Struct: vop_advlock_args in vfsops.h
hammer_vnops.c

### Struct: vop_bmap_args in vfsops.h
hammer_vnops.c

### Struct: vop_close_args in vfsops.h
hammer_vnops.c

### Struct: vop_fsync_args in vfsops.h
hammer_vnops.c

### Struct: vop_getattr_args in vfsops.h
hammer_vnops.c

### Struct: vop_ioctl_args in vfsops.h
hammer_vnops.c

### Struct: vop_kqfilter_args in vfsops.h
hammer_vnops.c

### Struct: vop_markatime_args in vfsops.h
hammer_vnops.c

### Struct: vop_mountctl_args in vfsops.h
hammer_vnops.c

### Struct: vop_ncreate_args in vfsops.h
hammer_vnops.c

### Struct: vop_nlink_args in vfsops.h
hammer_vnops.c

### Struct: vop_nlookupdotdot_args in vfsops.h
hammer_vnops.c

### Struct: vop_nmkdir_args in vfsops.h
hammer_vnops.c

### Struct: vop_nmknod_args in vfsops.h
hammer_vnops.c

### Struct: vop_nremove_args in vfsops.h
hammer_vnops.c

### Struct: vop_nrename_args in vfsops.h
hammer_vnops.c

### Struct: vop_nresolve_args in vfsops.h
hammer_vnops.c

### Struct: vop_nrmdir_args in vfsops.h
hammer_vnops.c

### Struct: vop_nsymlink_args in vfsops.h
hammer_vnops.c

### Struct: vop_nwhiteout_args in vfsops.h
hammer_vnops.c

### Struct: vop_open_args in vfsops.h
hammer_vnops.c

### Struct: vop_ops in vfsops.h
hammer_vnops.c

### Struct: vop_print_args in vfsops.h
hammer_vnops.c

### Struct: vop_read_args in vfsops.h
hammer_vnops.c

### Struct: vop_readdir_args in vfsops.h
hammer_vnops.c

### Struct: vop_readlink_args in vfsops.h
hammer_vnops.c

### Struct: vop_setattr_args in vfsops.h
hammer_vnops.c

### Struct: vop_strategy_args in vfsops.h
hammer_vnops.c

### Struct: vop_write_args in vfsops.h
hammer_vnops.c

### Macro: IO_NRDELAY in vnode.h
hammer_vnops.c
