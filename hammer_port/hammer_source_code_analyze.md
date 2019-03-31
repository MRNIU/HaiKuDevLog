hammer.h



[-] buf.h (1)
	[-] buf.h (1)
		hammer.h Includes buf.h at hammer.h:61
[-] conf.h (1)
	[-] conf.h (1)
		hammer.h Includes conf.h at hammer.h:48
[-] dirent.h (1)
	[-] dirent.h (1)
		hammer.h Includes dirent.h at hammer.h:55
[-] event.h (1)
	[-] event.h (1)
		hammer.h Includes event.h at hammer.h:60
[-] fcntl.h (1)
	[-] fcntl.h (1)
		hammer.h Includes fcntl.h at hammer.h:57
[-] file.h (1)
	[-] file.h (1)
		hammer.h Includes file.h at hammer.h:59
[-] ktr.h (1)
	[-] ktr.h (1)
		hammer.h Includes ktr.h at hammer.h:63
[-] limits.h (1)
	[-] limits.h (1)
		hammer.h Includes limits.h at hammer.h:64
[-] lockf.h (1)
	[-] lockf.h (1)
		hammer.h Includes lockf.h at hammer.h:58
[-] malloc.h (1)
	[-] malloc.h (1)
		hammer.h Includes malloc.h at hammer.h:50
[-] mount.h (1)
	[-] mount.h (1)
		hammer.h Includes mount.h at hammer.h:51
[-] param.h (1)
	[-] param.h (1)
		hammer.h Includes param.h at hammer.h:43
[-] priv.h (1)
	[-] priv.h (1)
		hammer.h Includes priv.h at hammer.h:54
[-] proc.h (1)
	[-] proc.h (1)
		hammer.h Includes proc.h at hammer.h:53
[-] queue.h (1)
	[-] queue.h (1)
		hammer.h Includes queue.h at hammer.h:62
[-] stat.h (1)
	[-] stat.h (1)
		hammer.h Includes stat.h at hammer.h:56
[-] swap_pager.h (1)
	[-] swap_pager.h (1)
		hammer.h Includes swap_pager.h at hammer.h:66
[-] sysctl.h (1)
	[-] sysctl.h (1)
		hammer.h Includes sysctl.h at hammer.h:65
[-] tree.h (1)
	[-] tree.h (1)
		hammer.h Includes tree.h at hammer.h:49
[-] vm_extern.h (1)
	[-] vm_extern.h (1)
		hammer.h Includes vm_extern.h at hammer.h:67
[-] vnode.h (1)
	[-] vnode.h (1)
		hammer.h Includes vnode.h at hammer.h:52



---

hammer_blockmap.c



[-] _null.h (21)
	[-] Macro: NULL (21)
		hammer_blockmap_alloc Uses NULL at hammer_blockmap.c:80
		hammer_blockmap_alloc Uses NULL at hammer_blockmap.c:81
		hammer_blockmap_alloc Uses NULL at hammer_blockmap.c:82
		hammer_blockmap_alloc Uses NULL at hammer_blockmap.c:376
		hammer_blockmap_reserve Uses NULL at hammer_blockmap.c:415
		hammer_blockmap_reserve Uses NULL at hammer_blockmap.c:416
		hammer_blockmap_reserve Uses NULL at hammer_blockmap.c:417
		hammer_blockmap_reserve Uses NULL at hammer_blockmap.c:424
		hammer_blockmap_reserve Uses NULL at hammer_blockmap.c:434
		hammer_blockmap_reserve Uses NULL at hammer_blockmap.c:450
		hammer_blockmap_reserve Uses NULL at hammer_blockmap.c:591
		hammer_reserve_setdelay_offset Uses NULL at hammer_blockmap.c:704
		hammer_blockmap_free Uses NULL at hammer_blockmap.c:775
		hammer_blockmap_free Uses NULL at hammer_blockmap.c:776
		hammer_blockmap_dedup Uses NULL at hammer_blockmap.c:909
		hammer_blockmap_dedup Uses NULL at hammer_blockmap.c:910
		hammer_blockmap_finalize Uses NULL at hammer_blockmap.c:1019
		hammer_blockmap_finalize Uses NULL at hammer_blockmap.c:1020
		hammer_blockmap_getfree Uses NULL at hammer_blockmap.c:1151
		hammer_blockmap_lookup_verify Uses NULL at hammer_blockmap.c:1239
		hammer_check_volume Uses NULL at hammer_blockmap.c:1352
[-] kern_slaballoc.c (4)
	[-] Function: kfree (2)
		hammer_blockmap_reserve_complete Calls kfree at hammer_blockmap.c:675
		hammer_reserve_setdelay_offset Calls kfree at hammer_blockmap.c:715
	[-] Function: kmalloc (2)
		hammer_blockmap_reserve Calls kmalloc at hammer_blockmap.c:583
		hammer_reserve_setdelay_offset Calls kmalloc at hammer_blockmap.c:705
[-] malloc.h (6)
	[-] Macro: M_USE_RESERVE (2)
		hammer_blockmap_reserve Uses M_USE_RESERVE at hammer_blockmap.c:584
		hammer_reserve_setdelay_offset Uses M_USE_RESERVE at hammer_blockmap.c:706
	[-] Macro: M_WAITOK (2)
		hammer_blockmap_reserve Uses M_WAITOK at hammer_blockmap.c:584
		hammer_reserve_setdelay_offset Uses M_WAITOK at hammer_blockmap.c:706
	[-] Macro: M_ZERO (2)
		hammer_blockmap_reserve Uses M_ZERO at hammer_blockmap.c:584
		hammer_reserve_setdelay_offset Uses M_ZERO at hammer_blockmap.c:706
[-] queue.h (4)
	[-] Macro: TAILQ_INSERT_TAIL (2)
		hammer_reserve_setdelay Uses TAILQ_INSERT_TAIL at hammer_blockmap.c:736
		hammer_reserve_setdelay Uses TAILQ_INSERT_TAIL at hammer_blockmap.c:742
	[-] Macro: TAILQ_REMOVE (2)
		hammer_reserve_setdelay Uses TAILQ_REMOVE at hammer_blockmap.c:734
		hammer_reserve_clrdelay Uses TAILQ_REMOVE at hammer_blockmap.c:756
[-] tree.h (8)
	[-] Macro: RB_GENERATE2 (1)
		hammer_blockmap.c Uses RB_GENERATE2 at hammer_blockmap.c:53
	[-] Macro: RB_INSERT (2)
		hammer_blockmap_reserve Uses RB_INSERT at hammer_blockmap.c:590
		hammer_reserve_setdelay_offset Uses RB_INSERT at hammer_blockmap.c:714
	[-] Macro: RB_LOOKUP (4)
		hammer_blockmap_alloc Uses RB_LOOKUP at hammer_blockmap.c:291
		hammer_blockmap_reserve Uses RB_LOOKUP at hammer_blockmap.c:569
		hammer_reserve_setdelay_offset Uses RB_LOOKUP at hammer_blockmap.c:703
		hammer_blockmap_lookup_verify Uses RB_LOOKUP at hammer_blockmap.c:1290
	[-] Macro: RB_REMOVE (1)
		hammer_blockmap_reserve_complete Uses RB_REMOVE at hammer_blockmap.c:674
[-] vm_page2.h (1)
	[-] vm_page2.h (1)
		hammer_blockmap.c Includes vm_page2.h at hammer_blockmap.c:38



---

hammer_btree.c



[-] _null.h (28)
	[-] Macro: NULL (28)
		hammer_btree_iterate Uses NULL at hammer_btree.c:138
		hammer_btree_iterate Uses NULL at hammer_btree.c:183
		hammer_btree_iterate_reverse Uses NULL at hammer_btree.c:414
		hammer_btree_extract Uses NULL at hammer_btree.c:693
		hammer_btree_extract Uses NULL at hammer_btree.c:705
		hammer_btree_delete Uses NULL at hammer_btree.c:917
		hammer_btree_delete Uses NULL at hammer_btree.c:939
		btree_search Uses NULL at hammer_btree.c:1033
		btree_split_internal Uses NULL at hammer_btree.c:1455
		btree_split_internal Uses NULL at hammer_btree.c:1496
		btree_split_internal Uses NULL at hammer_btree.c:1532
		btree_split_internal Uses NULL at hammer_btree.c:1669
		btree_split_leaf Uses NULL at hammer_btree.c:1749
		btree_split_leaf Uses NULL at hammer_btree.c:1785
		btree_remove Uses NULL at hammer_btree.c:2182
		btree_remove Uses NULL at hammer_btree.c:2230
		hammer_btree_get_parent Uses NULL at hammer_btree.c:2477
		hammer_btree_get_parent Uses NULL at hammer_btree.c:2478
		hammer_btree_get_parent Uses NULL at hammer_btree.c:2489
		hammer_node_lock_init Uses NULL at hammer_btree.c:2557
		hammer_node_lock_init Uses NULL at hammer_btree.c:2561
		hammer_btree_lcache_free Uses NULL at hammer_btree.c:2603
		hammer_btree_lcache_free Uses NULL at hammer_btree.c:2610
		hammer_btree_lock_children Uses NULL at hammer_btree.c:2677
		hammer_btree_lock_children Uses NULL at hammer_btree.c:2686
		hammer_btree_lock_copy Uses NULL at hammer_btree.c:2730
		hammer_btree_unlock_children Uses NULL at hammer_btree.c:2782
		hammer_btree_unlock_children Uses NULL at hammer_btree.c:2809
[-] kern_slaballoc.c (8)
	[-] Function: kfree (4)
		hammer_btree_lcache_free Calls kfree at hammer_btree.c:2607
		hammer_btree_lcache_free Calls kfree at hammer_btree.c:2608
		hammer_btree_unlock_children Calls kfree at hammer_btree.c:2804
		hammer_btree_unlock_children Calls kfree at hammer_btree.c:2808
	[-] Function: kmalloc (4)
		hammer_btree_lcache_init Calls kmalloc at hammer_btree.c:2589
		hammer_btree_lcache_init Calls kmalloc at hammer_btree.c:2590
		hammer_btree_lock_children Calls kmalloc at hammer_btree.c:2690
		hammer_btree_lock_copy Calls kmalloc at hammer_btree.c:2732
[-] lwkt_thread.c (2)
	[-] Function: lwkt_user_yield (2)
		hammer_btree_iterate Calls lwkt_user_yield at hammer_btree.c:150
		hammer_btree_iterate_reverse Calls lwkt_user_yield at hammer_btree.c:429
[-] malloc.h (6)
	[-] Macro: M_WAITOK (4)
		hammer_btree_lcache_init Uses M_WAITOK at hammer_btree.c:2589
		hammer_btree_lcache_init Uses M_WAITOK at hammer_btree.c:2591
		hammer_btree_lock_children Uses M_WAITOK at hammer_btree.c:2692
		hammer_btree_lock_copy Uses M_WAITOK at hammer_btree.c:2733
	[-] Macro: M_ZERO (2)
		hammer_btree_lcache_init Uses M_ZERO at hammer_btree.c:2589
		hammer_btree_lock_children Uses M_ZERO at hammer_btree.c:2692
[-] memset.c (4)
	[-] Function: bzero (4)
		hammer_btree_lcache_init Calls bzero at hammer_btree.c:2586
		hammer_btree_unlock_children Calls bzero at hammer_btree.c:2797
		hammer_btree_unlock_children Calls bzero at hammer_btree.c:2801
		hammer_make_separator Calls bzero at hammer_btree.c:2906
[-] mman.h (1)
	[-] Typedef: size_t (1)
		esize Types size_t at hammer_btree.c:1693
[-] os.c (7)
	[-] Function: bcopy (7)
		hammer_btree_insert Calls bcopy at hammer_btree.c:820
		hammer_btree_delete Calls bcopy at hammer_btree.c:904
		btree_split_internal Calls bcopy at hammer_btree.c:1552
		btree_split_internal Calls bcopy at hammer_btree.c:1581
		btree_split_leaf Calls bcopy at hammer_btree.c:1803
		btree_split_leaf Calls bcopy at hammer_btree.c:1833
		btree_remove Calls bcopy at hammer_btree.c:2311
[-] queue.h (18)
	[-] Macro: TAILQ_EMPTY (2)
		hammer_btree_lcache_free Uses TAILQ_EMPTY at hammer_btree.c:2606
		hammer_btree_unlock_children Uses TAILQ_EMPTY at hammer_btree.c:2795
	[-] Macro: TAILQ_FIRST (3)
		hammer_btree_lcache_free Uses TAILQ_FIRST at hammer_btree.c:2603
		hammer_btree_lock_children Uses TAILQ_FIRST at hammer_btree.c:2685
		hammer_btree_unlock_children Uses TAILQ_FIRST at hammer_btree.c:2782
	[-] Macro: TAILQ_FOREACH (2)
		hammer_btree_lock_copy Uses TAILQ_FOREACH at hammer_btree.c:2737
		hammer_btree_sync_copy Uses TAILQ_FOREACH at hammer_btree.c:2761
	[-] Macro: TAILQ_INIT (5)
		hammer_node_lock_init Uses TAILQ_INIT at hammer_btree.c:2556
		hammer_btree_lcache_init Uses TAILQ_INIT at hammer_btree.c:2587
		hammer_btree_lcache_init Uses TAILQ_INIT at hammer_btree.c:2592
		hammer_btree_lock_children Uses TAILQ_INIT at hammer_btree.c:2693
		hammer_btree_unlock_children Uses TAILQ_INIT at hammer_btree.c:2798
	[-] Macro: TAILQ_INSERT_TAIL (3)
		hammer_btree_lcache_init Uses TAILQ_INSERT_TAIL at hammer_btree.c:2593
		hammer_btree_lock_children Uses TAILQ_INSERT_TAIL at hammer_btree.c:2696
		hammer_btree_unlock_children Uses TAILQ_INSERT_TAIL at hammer_btree.c:2802
	[-] Macro: TAILQ_REMOVE (3)
		hammer_btree_lcache_free Uses TAILQ_REMOVE at hammer_btree.c:2604
		hammer_btree_lock_children Uses TAILQ_REMOVE at hammer_btree.c:2688
		hammer_btree_unlock_children Uses TAILQ_REMOVE at hammer_btree.c:2783
[-] subr_prf.c (14)
	[-] Function: kprintf (14)
		hammer_print_btree_node Calls kprintf at hammer_btree.c:2958
		hammer_print_btree_node Calls kprintf at hammer_btree.c:2977
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:2985
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:2986
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:2987
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:2988
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:2989
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:2990
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:2991
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:2993
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:2996
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:2999
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:3001
		hammer_print_btree_elm Calls kprintf at hammer_btree.c:3002

---



hammer_crc.h



[-] crc32.c (13)
	[-] Function: crc32 (12)
		hammer_datacrc Macros crc32 at hammer_crc.h:73
		hammer_crc_get_blockmap Calls crc32 at hammer_crc.h:85
		hammer_crc_get_layer1 Calls crc32 at hammer_crc.h:113
		hammer_crc_get_layer2 Calls crc32 at hammer_crc.h:141
		hammer_crc_get_volume Calls crc32 at hammer_crc.h:169
		hammer_crc_get_volume Calls crc32 at hammer_crc.h:170
		hammer_crc_get_fifo_head Calls crc32 at hammer_crc.h:198
		hammer_crc_get_fifo_head Calls crc32 at hammer_crc.h:199
		hammer_crc_get_btree Calls crc32 at hammer_crc.h:227
		hammer_crc_get_leaf Calls crc32 at hammer_crc.h:271
		hammer_crc_get_leaf Calls crc32 at hammer_crc.h:274
		hammer_crc_get_mrec_head Calls crc32 at hammer_crc.h:311
	[-] Function: crc32_ext (1)
		hammer_datacrc_ext Macros crc32_ext at hammer_crc.h:77
[-] icrc32.c (12)
	[-] Function: iscsi_crc32 (11)
		hammer_datacrc Macros iscsi_crc32 at hammer_crc.h:73
		hammer_crc_get_blockmap Calls iscsi_crc32 at hammer_crc.h:85
		hammer_crc_get_layer1 Calls iscsi_crc32 at hammer_crc.h:113
		hammer_crc_get_layer2 Calls iscsi_crc32 at hammer_crc.h:141
		hammer_crc_get_volume Calls iscsi_crc32 at hammer_crc.h:169
		hammer_crc_get_volume Calls iscsi_crc32 at hammer_crc.h:170
		hammer_crc_get_fifo_head Calls iscsi_crc32 at hammer_crc.h:198
		hammer_crc_get_fifo_head Calls iscsi_crc32 at hammer_crc.h:199
		hammer_crc_get_btree Calls iscsi_crc32 at hammer_crc.h:227
		hammer_crc_get_leaf Calls iscsi_crc32 at hammer_crc.h:271
		hammer_crc_get_leaf Calls iscsi_crc32 at hammer_crc.h:274
	[-] Function: iscsi_crc32_ext (1)
		hammer_datacrc_ext Macros iscsi_crc32_ext at hammer_crc.h:77
[-] mman.h (4)
	[-] Typedef: size_t (4)
		crc32 Uses size_t at hammer_crc.h:46
		crc32_ext Uses size_t at hammer_crc.h:47
		iscsi_crc32 Uses size_t at hammer_crc.h:48
		iscsi_crc32_ext Uses size_t at hammer_crc.h:49



---



hammer_cursor.c (82)



[-] _null.h (48)
	[-] Macro: NULL (48)
		hammer_init_cursor Uses NULL at hammer_cursor.c:117
		hammer_init_cursor Uses NULL at hammer_cursor.c:142
		hammer_init_cursor Uses NULL at hammer_cursor.c:145
		hammer_init_cursor Uses NULL at hammer_cursor.c:148
		hammer_init_cursor Uses NULL at hammer_cursor.c:156
		hammer_init_cursor Uses NULL at hammer_cursor.c:185
		hammer_init_cursor Uses NULL at hammer_cursor.c:191
		hammer_normalize_cursor Uses NULL at hammer_cursor.c:214
		hammer_normalize_cursor Uses NULL at hammer_cursor.c:215
		hammer_done_cursor Uses NULL at hammer_cursor.c:234
		hammer_done_cursor Uses NULL at hammer_cursor.c:239
		hammer_done_cursor Uses NULL at hammer_cursor.c:243
		hammer_done_cursor Uses NULL at hammer_cursor.c:245
		hammer_done_cursor Uses NULL at hammer_cursor.c:249
		hammer_done_cursor Uses NULL at hammer_cursor.c:253
		hammer_done_cursor Uses NULL at hammer_cursor.c:282
		hammer_done_cursor Uses NULL at hammer_cursor.c:287
		hammer_done_cursor Uses NULL at hammer_cursor.c:290
		hammer_done_cursor Uses NULL at hammer_cursor.c:291
		hammer_done_cursor Uses NULL at hammer_cursor.c:292
		hammer_done_cursor Uses NULL at hammer_cursor.c:293
		hammer_done_cursor Uses NULL at hammer_cursor.c:294
		hammer_cursor_upgrade Uses NULL at hammer_cursor.c:318
		hammer_cursor_upgrade Uses NULL at hammer_cursor.c:327
		hammer_cursor_upgrade_node Uses NULL at hammer_cursor.c:354
		hammer_cursor_seek Uses NULL at hammer_cursor.c:476
		hammer_load_cursor_parent Uses NULL at hammer_cursor.c:514
		hammer_cursor_up Uses NULL at hammer_cursor.c:538
		hammer_cursor_up Uses NULL at hammer_cursor.c:548
		hammer_cursor_up_locked Uses NULL at hammer_cursor.c:575
		hammer_cursor_up_locked Uses NULL at hammer_cursor.c:586
		hammer_cursor_down Uses NULL at hammer_cursor.c:633
		hammer_unlock_cursor Uses NULL at hammer_cursor.c:724
		hammer_recover_cursor Uses NULL at hammer_cursor.c:834
		hammer_recover_cursor Uses NULL at hammer_cursor.c:839
		hammer_push_cursor Uses NULL at hammer_cursor.c:872
		hammer_push_cursor Uses NULL at hammer_cursor.c:873
		hammer_push_cursor Uses NULL at hammer_cursor.c:874
		hammer_push_cursor Uses NULL at hammer_cursor.c:875
		hammer_push_cursor Uses NULL at hammer_cursor.c:878
		hammer_pop_cursor Uses NULL at hammer_cursor.c:901
		hammer_cursor_replaced_node Uses NULL at hammer_cursor.c:923
		hammer_cursor_removed_node Uses NULL at hammer_cursor.c:954
		hammer_cursor_removed_node Uses NULL at hammer_cursor.c:957
		hammer_cursor_removed_node Uses NULL at hammer_cursor.c:963
		hammer_cursor_deleted_element Uses NULL at hammer_cursor.c:1125
		hammer_cursor_invalidate_cache Uses NULL at hammer_cursor.c:1169
		hammer_cursor_invalidate_cache Uses NULL at hammer_cursor.c:1170
[-] cdefs.h (1)
	[-] Macro: __noinline (1)
		hammer_cursor.c Uses __noinline at hammer_cursor.c:382
[-] defines.h (5)
	[-] Typedef: u_int (5)
		tticks Types u_int at hammer_cursor.c:53
		rticks Types u_int at hammer_cursor.c:80
		xticks Types u_int at hammer_cursor.c:81
		dummy Types u_int at hammer_cursor.c:82
		hammer_init_cursor Casts u_int at hammer_cursor.c:94
[-] kern_slaballoc.c (2)
	[-] Function: kfree (1)
		hammer_pop_cursor Calls kfree at hammer_cursor.c:905
	[-] Function: kmalloc (1)
		hammer_push_cursor Calls kmalloc at hammer_cursor.c:862
[-] malloc.h (2)
	[-] Macro: M_WAITOK (1)
		hammer_push_cursor Uses M_WAITOK at hammer_cursor.c:862
	[-] Macro: M_ZERO (1)
		hammer_push_cursor Uses M_ZERO at hammer_cursor.c:862
[-] memset.c (1)
	[-] Function: bzero (1)
		hammer_init_cursor Calls bzero at hammer_cursor.c:56
[-] os.c (1)
	[-] Function: bcopy (1)
		hammer_push_cursor Calls bcopy at hammer_cursor.c:863
[-] queue.h (22)
	[-] Macro: TAILQ_FIRST (2)
		hammer_cursor_replaced_node Uses TAILQ_FIRST at hammer_cursor.c:923
		hammer_cursor_removed_node Uses TAILQ_FIRST at hammer_cursor.c:957
	[-] Macro: TAILQ_FOREACH (6)
		hammer_cursor_split_node Uses TAILQ_FOREACH at hammer_cursor.c:987
		hammer_cursor_moved_element Uses TAILQ_FOREACH at hammer_cursor.c:1028
		hammer_cursor_moved_element Uses TAILQ_FOREACH at hammer_cursor.c:1058
		hammer_cursor_parent_changed Uses TAILQ_FOREACH at hammer_cursor.c:1095
		hammer_cursor_deleted_element Uses TAILQ_FOREACH at hammer_cursor.c:1120
		hammer_cursor_inserted_element Uses TAILQ_FOREACH at hammer_cursor.c:1147
	[-] Macro: TAILQ_INSERT_TAIL (8)
		hammer_unlock_cursor Uses TAILQ_INSERT_TAIL at hammer_cursor.c:728
		hammer_push_cursor Uses TAILQ_INSERT_TAIL at hammer_cursor.c:869
		hammer_push_cursor Uses TAILQ_INSERT_TAIL at hammer_cursor.c:877
		hammer_cursor_replaced_node Uses TAILQ_INSERT_TAIL at hammer_cursor.c:925
		hammer_cursor_removed_node Uses TAILQ_INSERT_TAIL at hammer_cursor.c:961
		hammer_cursor_split_node Uses TAILQ_INSERT_TAIL at hammer_cursor.c:992
		hammer_cursor_moved_element Uses TAILQ_INSERT_TAIL at hammer_cursor.c:1033
		hammer_cursor_moved_element Uses TAILQ_INSERT_TAIL at hammer_cursor.c:1068
	[-] Macro: TAILQ_REMOVE (6)
		hammer_lock_cursor Uses TAILQ_REMOVE at hammer_cursor.c:766
		hammer_cursor_replaced_node Uses TAILQ_REMOVE at hammer_cursor.c:924
		hammer_cursor_removed_node Uses TAILQ_REMOVE at hammer_cursor.c:960
		hammer_cursor_split_node Uses TAILQ_REMOVE at hammer_cursor.c:991
		hammer_cursor_moved_element Uses TAILQ_REMOVE at hammer_cursor.c:1032
		hammer_cursor_moved_element Uses TAILQ_REMOVE at hammer_cursor.c:1067



---



hammer_dedup.c (4)



[-] _null.h (4)
	[-] Macro: NULL (4)
		hammer_ioc_dedup Uses NULL at hammer_dedup.c:57
		hammer_ioc_dedup Uses NULL at hammer_dedup.c:57
		hammer_ioc_dedup Uses NULL at hammer_dedup.c:73
		hammer_ioc_dedup Uses NULL at hammer_dedup.c:73



---



hammer_disk.h (13)



[-] cdefs.h (1)
	[-] Macro: __packed (1)
		hammer_disk.h Uses __packed at hammer_disk.h:1018
[-] endian.h (1)
	[-] endian.h (1)
		hammer_disk.h Includes endian.h at hammer_disk.h:40
[-] route6d.c (9)
	[-] Macro: offsetof (9)
		HAMMER_BLOCKMAP_CRCSIZE Macros offsetof at hammer_disk.h:396
		HAMMER_LAYER1_CRCSIZE Macros offsetof at hammer_disk.h:430
		HAMMER_LAYER2_CRCSIZE Macros offsetof at hammer_disk.h:452
		HAMMER_FIFO_HEAD_CRCOFF Macros offsetof at hammer_disk.h:585
		HAMMER_VOL_CRCSIZE1 Macros offsetof at hammer_disk.h:798
		HAMMER_INODE_CRCSIZE Macros offsetof at hammer_disk.h:916
		HAMMER_ENTRY_NAME_OFF Macros offsetof at hammer_disk.h:964
		HAMMER_ENTRY_SIZE Macros offsetof at hammer_disk.h:965
		HAMMER_SYMLINK_NAME_OFF Macros offsetof at hammer_disk.h:975
[-] uuid.h (2)
	[-] Typedef: uuid_t (1)
		hammer_uuid_t Types uuid_t at hammer_disk.h:122
	[-] uuid.h (1)
		hammer_disk.h Includes uuid.h at hammer_disk.h:43



---



hammer_flusher.c (79)



[-] _null.h (23)
	[-] Macro: NULL (23)
		hammer_flusher_sync Uses NULL at hammer_flusher.c:76
		hammer_flusher_async Uses NULL at hammer_flusher.c:106
		hammer_flusher_create Uses NULL at hammer_flusher.c:207
		hammer_flusher_create Uses NULL at hammer_flusher.c:213
		hammer_flusher_destroy Uses NULL at hammer_flusher.c:235
		hammer_flusher_master_thread Uses NULL at hammer_flusher.c:294
		hammer_flusher_flush Uses NULL at hammer_flusher.c:320
		hammer_flusher_flush Uses NULL at hammer_flusher.c:333
		hammer_flusher_flush Uses NULL at hammer_flusher.c:357
		hammer_flusher_flush Uses NULL at hammer_flusher.c:395
		hammer_flusher_flush Uses NULL at hammer_flusher.c:407
		hammer_flusher_flush Uses NULL at hammer_flusher.c:447
		hammer_flusher_slave_thread Uses NULL at hammer_flusher.c:478
		hammer_flusher_slave_thread Uses NULL at hammer_flusher.c:482
		hammer_flusher_slave_thread Uses NULL at hammer_flusher.c:487
		hammer_flusher_clean_loose_ios Uses NULL at hammer_flusher.c:506
		hammer_flusher_clean_loose_ios Uses NULL at hammer_flusher.c:508
		hammer_flusher_clean_loose_ios Uses NULL at hammer_flusher.c:511
		hammer_flusher_finalize Uses NULL at hammer_flusher.c:657
		hammer_flusher_finalize Uses NULL at hammer_flusher.c:743
		hammer_flusher_finalize Uses NULL at hammer_flusher.c:763
		hammer_flusher_finalize Uses NULL at hammer_flusher.c:803
		hammer_flusher_flush_undos Uses NULL at hammer_flusher.c:895
[-] kern_slaballoc.c (3)
	[-] Function: kfree (2)
		hammer_flusher_destroy Calls kfree at hammer_flusher.c:242
		hammer_flusher_flush Calls kfree at hammer_flusher.c:425
	[-] Function: kmalloc (1)
		hammer_flusher_create Calls kmalloc at hammer_flusher.c:209
[-] lwkt_thread.c (4)
	[-] Function: lwkt_create (2)
		hammer_flusher_create Calls lwkt_create at hammer_flusher.c:206
		hammer_flusher_create Calls lwkt_create at hammer_flusher.c:212
	[-] Function: lwkt_exit (2)
		hammer_flusher_master_thread Calls lwkt_exit at hammer_flusher.c:297
		hammer_flusher_slave_thread Calls lwkt_exit at hammer_flusher.c:490
[-] lwkt_token.c (6)
	[-] Function: lwkt_gettoken (3)
		hammer_flusher_master_thread Calls lwkt_gettoken at hammer_flusher.c:259
		hammer_flusher_slave_thread Calls lwkt_gettoken at hammer_flusher.c:469
		hammer_flusher_clean_loose_ios Calls lwkt_gettoken at hammer_flusher.c:507
	[-] Function: lwkt_reltoken (3)
		hammer_flusher_master_thread Calls lwkt_reltoken at hammer_flusher.c:296
		hammer_flusher_slave_thread Calls lwkt_reltoken at hammer_flusher.c:489
		hammer_flusher_clean_loose_ios Calls lwkt_reltoken at hammer_flusher.c:516
[-] malloc.h (2)
	[-] Macro: M_WAITOK (1)
		hammer_flusher_create Uses M_WAITOK at hammer_flusher.c:209
	[-] Macro: M_ZERO (1)
		hammer_flusher_create Uses M_ZERO at hammer_flusher.c:209
[-] os.c (1)
	[-] Function: bcopy (1)
		hammer_flusher_finalize Calls bcopy at hammer_flusher.c:691
[-] queue.h (22)
	[-] Macro: TAILQ_EMPTY (1)
		hammer_flusher_master_thread Uses TAILQ_EMPTY at hammer_flusher.c:284
	[-] Macro: TAILQ_ENTRY (1)
		hammer_flusher_info Uses TAILQ_ENTRY at hammer_flusher.c:57
	[-] Macro: TAILQ_FIRST (9)
		hammer_flusher_async_one Uses TAILQ_FIRST at hammer_flusher.c:150
		hammer_flusher_destroy Uses TAILQ_FIRST at hammer_flusher.c:235
		hammer_flusher_flush Uses TAILQ_FIRST at hammer_flusher.c:320
		hammer_flusher_flush Uses TAILQ_FIRST at hammer_flusher.c:332
		hammer_flusher_flush Uses TAILQ_FIRST at hammer_flusher.c:395
		hammer_flusher_flush Uses TAILQ_FIRST at hammer_flusher.c:407
		hammer_flusher_flush Uses TAILQ_FIRST at hammer_flusher.c:428
		hammer_flusher_flush Uses TAILQ_FIRST at hammer_flusher.c:447
		hammer_flusher_haswork Uses TAILQ_FIRST at hammer_flusher.c:958
	[-] Macro: TAILQ_INIT (2)
		hammer_flusher_create Uses TAILQ_INIT at hammer_flusher.c:203
		hammer_flusher_create Uses TAILQ_INIT at hammer_flusher.c:204
	[-] Macro: TAILQ_INSERT_TAIL (3)
		hammer_flusher_create Uses TAILQ_INSERT_TAIL at hammer_flusher.c:211
		hammer_flusher_flush Uses TAILQ_INSERT_TAIL at hammer_flusher.c:400
		hammer_flusher_slave_thread Uses TAILQ_INSERT_TAIL at hammer_flusher.c:484
	[-] Macro: TAILQ_NEXT (2)
		hammer_flusher_async Uses TAILQ_NEXT at hammer_flusher.c:109
		hammer_flusher_flush Uses TAILQ_NEXT at hammer_flusher.c:344
	[-] Macro: TAILQ_REMOVE (4)
		hammer_flusher_destroy Uses TAILQ_REMOVE at hammer_flusher.c:237
		hammer_flusher_flush Uses TAILQ_REMOVE at hammer_flusher.c:396
		hammer_flusher_flush Uses TAILQ_REMOVE at hammer_flusher.c:424
		hammer_flusher_slave_thread Uses TAILQ_REMOVE at hammer_flusher.c:483
[-] subr_prf.c (3)
	[-] Function: kprintf (3)
		hammer_flush_dirty Calls kprintf at hammer_flusher.c:982
		hammer_flush_dirty Calls kprintf at hammer_flusher.c:986
		hammer_flush_dirty Calls kprintf at hammer_flusher.c:991
[-] thread.h (1)
	[-] Typedef: thread_t (1)
		td Types thread_t at hammer_flusher.c:59
[-] tree.h (13)
	[-] Macro: RB_EMPTY (1)
		hammer_flusher_flush Uses RB_EMPTY at hammer_flusher.c:422
	[-] Macro: RB_FIRST (3)
		hammer_flusher_finalize Uses RB_FIRST at hammer_flusher.c:657
		hammer_flusher_finalize Uses RB_FIRST at hammer_flusher.c:803
		hammer_flusher_flush_undos Uses RB_FIRST at hammer_flusher.c:895
	[-] Macro: RB_GENERATE (1)
		hammer_flusher.c Uses RB_GENERATE at hammer_flusher.c:50
	[-] Macro: RB_REMOVE (1)
		hammer_flusher_clean_loose_ios Uses RB_REMOVE at hammer_flusher.c:510
	[-] Macro: RB_ROOT (6)
		hammer_flusher_clean_loose_ios Uses RB_ROOT at hammer_flusher.c:506
		hammer_flusher_clean_loose_ios Uses RB_ROOT at hammer_flusher.c:508
		hammer_flusher_haswork Uses RB_ROOT at hammer_flusher.c:959
		hammer_flusher_haswork Uses RB_ROOT at hammer_flusher.c:960
		hammer_flusher_haswork Uses RB_ROOT at hammer_flusher.c:961
		hammer_flusher_haswork Uses RB_ROOT at hammer_flusher.c:962
	[-] Macro: RB_SCAN (1)
		hammer_flusher_slave_thread Uses RB_SCAN at hammer_flusher.c:478
[-] vm_page.c (1)
	[-] Function: vm_wait_nominal (1)
		hammer_flusher_flush_inode Calls vm_wait_nominal at hammer_flusher.c:550



---



hammer_inode.c (214)



[-] _null.h (56)
	[-] Macro: NULL (56)
		hammer_vop_inactive Uses NULL at hammer_inode.c:185
		hammer_vop_reclaim Uses NULL at hammer_inode.c:232
		hammer_vop_reclaim Uses NULL at hammer_inode.c:236
		hammer_vop_reclaim Uses NULL at hammer_inode.c:237
		hammer_inode_dirty Uses NULL at hammer_inode.c:267
		hammer_get_vnode Uses NULL at hammer_inode.c:291
		hammer_get_vnode Uses NULL at hammer_inode.c:296
		hammer_get_vnode Uses NULL at hammer_inode.c:369
		hammer_get_inode Uses NULL at hammer_inode.c:451
		hammer_get_inode Uses NULL at hammer_inode.c:491
		hammer_get_inode Uses NULL at hammer_inode.c:498
		hammer_get_inode Uses NULL at hammer_inode.c:590
		hammer_get_dummy_inode Uses NULL at hammer_inode.c:634
		hammer_get_dummy_inode Uses NULL at hammer_inode.c:703
		hammer_find_inode Uses NULL at hammer_inode.c:722
		hammer_create_inode Uses NULL at hammer_inode.c:778
		hammer_create_inode Uses NULL at hammer_inode.c:795
		hammer_create_inode Uses NULL at hammer_inode.c:928
		hammer_free_inode Uses NULL at hammer_inode.c:959
		hammer_load_pseudofs Uses NULL at hammer_inode.c:995
		hammer_load_pseudofs Uses NULL at hammer_inode.c:999
		hammer_load_pseudofs Uses NULL at hammer_inode.c:1007
		hammer_save_pseudofs Uses NULL at hammer_inode.c:1065
		hammer_save_pseudofs Uses NULL at hammer_inode.c:1088
		hammer_mkroot_pseudofs Uses NULL at hammer_inode.c:1137
		hammer_mkroot_pseudofs Uses NULL at hammer_inode.c:1139
		hammer_mkroot_pseudofs Uses NULL at hammer_inode.c:1150
		hammer_mkroot_pseudofs Uses NULL at hammer_inode.c:1150
		hammer_unload_pseudofs_callback Uses NULL at hammer_inode.c:1185
		hammer_rel_inode Uses NULL at hammer_inode.c:1493
		hammer_unload_inode Uses NULL at hammer_inode.c:1531
		hammer_destroy_inode_callback Uses NULL at hammer_inode.c:1566
		hammer_destroy_inode_callback Uses NULL at hammer_inode.c:1568
		hammer_destroy_inode_callback Uses NULL at hammer_inode.c:1572
		hammer_destroy_inode_callback Uses NULL at hammer_inode.c:1579
		hammer_destroy_inode_callback Uses NULL at hammer_inode.c:1587
		hammer_destroy_inode_callback Uses NULL at hammer_inode.c:1597
		hammer_destroy_inode_callback Uses NULL at hammer_inode.c:1614
		hammer_destroy_inode_callback Uses NULL at hammer_inode.c:1615
		hammer_flush_inode Uses NULL at hammer_inode.c:1756
		hammer_flush_inode Uses NULL at hammer_inode.c:1765
		hammer_flush_inode Uses NULL at hammer_inode.c:1768
		hammer_flush_inode Uses NULL at hammer_inode.c:1770
		hammer_flush_inode_core Uses NULL at hammer_inode.c:2155
		hammer_flush_inode_core Uses NULL at hammer_inode.c:2172
		hammer_setup_child_callback Uses NULL at hammer_inode.c:2306
		hammer_setup_child_callback Uses NULL at hammer_inode.c:2323
		hammer_flush_inode_done Uses NULL at hammer_inode.c:2588
		hammer_flush_inode_done Uses NULL at hammer_inode.c:2629
		hammer_sync_record_callback Uses NULL at hammer_inode.c:2858
		hammer_sync_inode Uses NULL at hammer_inode.c:2931
		hammer_sync_inode Uses NULL at hammer_inode.c:2951
		hammer_sync_inode Uses NULL at hammer_inode.c:3038
		hammer_sync_inode Uses NULL at hammer_inode.c:3065
		hammer_inode_unloadable_check Uses NULL at hammer_inode.c:3268
		hammer_inode_wakereclaims Uses NULL at hammer_inode.c:3327
[-] bsd-misc.h (3)
	[-] Struct: timeval (3)
		[-] Object: tv_sec (1)
			hammer_update_atime_quick Uses tv_sec at hammer_inode.c:1720
		[-] Object: tv_usec (1)
			hammer_update_atime_quick Uses tv_usec at hammer_inode.c:1720
		[-] Struct: timeval (1)
			tv Types timeval at hammer_inode.c:1701
[-] buf.h (8)
	[-] Struct: vnode (8)
		[-] Object: v_data (3)
			hammer_vop_reclaim Uses v_data at hammer_inode.c:232
			hammer_vop_reclaim Sets v_data at hammer_inode.c:236
			hammer_get_vnode Sets v_data at hammer_inode.c:350
		[-] Struct: vnode (5)
			vp Types vnode at hammer_inode.c:228
			vp Types vnode at hammer_inode.c:264
			vpp Types vnode at hammer_inode.c:281
			vp Types vnode at hammer_inode.c:284
			vp Types vnode at hammer_inode.c:3246
[-] cdefs.h (2)
	[-] Macro: __unused (2)
		hammer_destroy_inode_callback Uses __unused at hammer_inode.c:1558
		hammer_reload_inode Uses __unused at hammer_inode.c:1630
[-] dirfs_vnops.c (2)
	[-] Macro: VNOVAL (2)
		hammer_create_inode Uses VNOVAL at hammer_inode.c:897
		hammer_create_inode Uses VNOVAL at hammer_inode.c:904
[-] kern_clock.c (1)
	[-] Function: getmicrotime (1)
		hammer_update_atime_quick Calls getmicrotime at hammer_inode.c:1716
[-] kern_slaballoc.c (8)
	[-] Function: kfree (3)
		hammer_free_inode Calls kfree at hammer_inode.c:961
		hammer_load_pseudofs Calls kfree at hammer_inode.c:1043
		hammer_rel_pseudofs Calls kfree at hammer_inode.c:1224
	[-] Function: kmalloc (5)
		hammer_get_inode Calls kmalloc at hammer_inode.c:460
		hammer_get_dummy_inode Calls kmalloc at hammer_inode.c:643
		hammer_create_inode Calls kmalloc at hammer_inode.c:785
		hammer_load_pseudofs Calls kmalloc at hammer_inode.c:1002
		hammer_flush_inode Calls kmalloc at hammer_inode.c:1766
[-] lock.h (1)
	[-] Macro: LK_EXCLUSIVE (1)
		hammer_get_vnode Uses LK_EXCLUSIVE at hammer_inode.c:380
[-] lwkt_token.c (4)
	[-] Function: lwkt_gettoken (2)
		hammer_vop_inactive Calls lwkt_gettoken at hammer_inode.c:204
		hammer_vop_reclaim Calls lwkt_gettoken at hammer_inode.c:234
	[-] Function: lwkt_reltoken (2)
		hammer_vop_inactive Calls lwkt_reltoken at hammer_inode.c:208
		hammer_vop_reclaim Calls lwkt_reltoken at hammer_inode.c:247
[-] malloc.h (10)
	[-] Macro: M_WAITOK (5)
		hammer_get_inode Uses M_WAITOK at hammer_inode.c:460
		hammer_get_dummy_inode Uses M_WAITOK at hammer_inode.c:643
		hammer_create_inode Uses M_WAITOK at hammer_inode.c:785
		hammer_load_pseudofs Uses M_WAITOK at hammer_inode.c:1002
		hammer_flush_inode Uses M_WAITOK at hammer_inode.c:1766
	[-] Macro: M_ZERO (5)
		hammer_get_inode Uses M_ZERO at hammer_inode.c:460
		hammer_get_dummy_inode Uses M_ZERO at hammer_inode.c:643
		hammer_create_inode Uses M_ZERO at hammer_inode.c:785
		hammer_load_pseudofs Uses M_ZERO at hammer_inode.c:1002
		hammer_flush_inode Uses M_ZERO at hammer_inode.c:1766
[-] mman.h (2)
	[-] Typedef: off_t (2)
		trunc_off Types off_t at hammer_inode.c:2996
		aligned_trunc_off Types off_t at hammer_inode.c:2997
[-] mount.h (1)
	[-] Macro: MNT_NOATIME (1)
		hammer_update_atime_quick Uses MNT_NOATIME at hammer_inode.c:1705
[-] os.c (2)
	[-] Function: bcopy (2)
		hammer_load_pseudofs Calls bcopy at hammer_inode.c:1032
		hammer_save_pseudofs Calls bcopy at hammer_inode.c:1111
[-] queue.h (21)
	[-] Macro: TAILQ_EMPTY (4)
		hammer_unload_inode Uses TAILQ_EMPTY at hammer_inode.c:1538
		hammer_flush_inode Uses TAILQ_EMPTY at hammer_inode.c:1786
		hammer_flush_inode_done Uses TAILQ_EMPTY at hammer_inode.c:2646
		hammer_flush_inode_done Uses TAILQ_EMPTY at hammer_inode.c:2683
	[-] Macro: TAILQ_FIRST (4)
		hammer_destroy_inode_callback Uses TAILQ_FIRST at hammer_inode.c:1566
		hammer_setup_parent_inodes Uses TAILQ_FIRST at hammer_inode.c:1883
		hammer_sync_inode Uses TAILQ_FIRST at hammer_inode.c:2930
		hammer_inode_wakereclaims Uses TAILQ_FIRST at hammer_inode.c:3327
	[-] Macro: TAILQ_FOREACH (1)
		hammer_setup_parent_inodes Uses TAILQ_FOREACH at hammer_inode.c:1896
	[-] Macro: TAILQ_INIT (3)
		hammer_get_inode Uses TAILQ_INIT at hammer_inode.c:477
		hammer_get_dummy_inode Uses TAILQ_INIT at hammer_inode.c:658
		hammer_create_inode Uses TAILQ_INIT at hammer_inode.c:815
	[-] Macro: TAILQ_INSERT_TAIL (2)
		hammer_flush_inode Uses TAILQ_INSERT_TAIL at hammer_inode.c:1773
		hammer_inode_waitreclaims Uses TAILQ_INSERT_TAIL at hammer_inode.c:3378
	[-] Macro: TAILQ_NEXT (3)
		hammer_flush_inode Uses TAILQ_NEXT at hammer_inode.c:1762
		hammer_flush_inode_core Uses TAILQ_NEXT at hammer_inode.c:2245
		hammer_sync_inode Uses TAILQ_NEXT at hammer_inode.c:2932
	[-] Macro: TAILQ_REMOVE (4)
		hammer_destroy_inode_callback Uses TAILQ_REMOVE at hammer_inode.c:1567
		hammer_sync_inode Uses TAILQ_REMOVE at hammer_inode.c:2949
		hammer_inode_wakereclaims Uses TAILQ_REMOVE at hammer_inode.c:3330
		hammer_inode_waitreclaims Uses TAILQ_REMOVE at hammer_inode.c:3381
[-] resourcevar.h (1)
	[-] Struct: krate (1)
		[-] Struct: krate (1)
			hammer_gen_krate Types krate at hammer_inode.c:58
[-] spawn.h (2)
	[-] Typedef: pid_t (2)
		hammer_inode_inostats Uses pid_t at hammer_inode.c:53
		pid Types pid_t at hammer_inode.c:3397
[-] stat.h (3)
	[-] Macro: SF_NOHISTORY (1)
		hammer_create_inode Uses SF_NOHISTORY at hammer_inode.c:829
	[-] Macro: UF_NODUMP (1)
		hammer_create_inode Uses UF_NODUMP at hammer_inode.c:829
	[-] Macro: UF_NOHISTORY (1)
		hammer_create_inode Uses UF_NOHISTORY at hammer_inode.c:829
[-] tree.h (30)
	[-] Macro: RB_EMPTY (6)
		hammer_unload_inode Uses RB_EMPTY at hammer_inode.c:1537
		hammer_flush_inode_done Uses RB_EMPTY at hammer_inode.c:2574
		hammer_flush_inode_done Uses RB_EMPTY at hammer_inode.c:2576
		hammer_flush_inode_done Uses RB_EMPTY at hammer_inode.c:2646
		hammer_sync_inode Uses RB_EMPTY at hammer_inode.c:3100
		hammer_sync_inode Uses RB_EMPTY at hammer_inode.c:3110
	[-] Macro: RB_GENERATE (1)
		hammer_inode.c Uses RB_GENERATE at hammer_inode.c:162
	[-] Macro: RB_GENERATE2 (1)
		hammer_inode.c Uses RB_GENERATE2 at hammer_inode.c:165
	[-] Macro: RB_GENERATE_XLOOKUP (1)
		hammer_inode.c Uses RB_GENERATE_XLOOKUP at hammer_inode.c:163
	[-] Macro: RB_INIT (4)
		hammer_get_inode Uses RB_INIT at hammer_inode.c:476
		hammer_get_dummy_inode Uses RB_INIT at hammer_inode.c:657
		hammer_create_inode Uses RB_INIT at hammer_inode.c:814
		hammer_flush_inode Uses RB_INIT at hammer_inode.c:1772
	[-] Macro: RB_INSERT (5)
		hammer_get_inode Uses RB_INSERT at hammer_inode.c:577
		hammer_get_dummy_inode Uses RB_INSERT at hammer_inode.c:693
		hammer_create_inode Uses RB_INSERT at hammer_inode.c:929
		hammer_load_pseudofs Uses RB_INSERT at hammer_inode.c:1042
		hammer_flush_inode_core Uses RB_INSERT at hammer_inode.c:2234
	[-] Macro: RB_LOOKUP (1)
		hammer_load_pseudofs Uses RB_LOOKUP at hammer_inode.c:982
	[-] Macro: RB_REMOVE (5)
		hammer_rel_pseudofs Uses RB_REMOVE at hammer_inode.c:1223
		hammer_unload_inode Uses RB_REMOVE at hammer_inode.c:1541
		hammer_unload_inode Uses RB_REMOVE at hammer_inode.c:1544
		hammer_destroy_inode_callback Uses RB_REMOVE at hammer_inode.c:1595
		hammer_flush_inode_done Uses RB_REMOVE at hammer_inode.c:2628
	[-] Macro: RB_ROOT (4)
		hammer_destroy_inode_callback Uses RB_ROOT at hammer_inode.c:1572
		hammer_flush_inode_done Uses RB_ROOT at hammer_inode.c:2565
		hammer_sync_inode Uses RB_ROOT at hammer_inode.c:3175
		hammer_sync_inode Uses RB_ROOT at hammer_inode.c:3176
	[-] Macro: RB_SCAN (2)
		hammer_flush_inode_core Uses RB_SCAN at hammer_inode.c:2155
		hammer_sync_inode Uses RB_SCAN at hammer_inode.c:3065
[-] types.h (3)
	[-] Typedef: gid_t (1)
		hammer_create_inode Casts gid_t at hammer_inode.c:904
	[-] Typedef: uid_t (2)
		xuid Types uid_t at hammer_inode.c:765
		hammer_create_inode Casts uid_t at hammer_inode.c:897
[-] ucred.h (2)
	[-] Struct: ucred (2)
		[-] Struct: ucred (2)
			cred Types ucred at hammer_inode.c:759
			cred Types ucred at hammer_inode.c:1130
[-] vfs_helper.c (1)
	[-] Function: vop_helper_create_uid (1)
		hammer_create_inode Calls vop_helper_create_uid at hammer_inode.c:888
[-] vfs_lock.c (10)
	[-] Function: vdrop (2)
		hammer_get_vnode Calls vdrop at hammer_inode.c:382
		hammer_get_vnode Calls vdrop at hammer_inode.c:387
	[-] Function: vget (1)
		hammer_get_vnode Calls vget at hammer_inode.c:380
	[-] Function: vhold (1)
		hammer_get_vnode Calls vhold at hammer_inode.c:373
	[-] Function: vput (2)
		hammer_get_vnode Calls vput at hammer_inode.c:385
		hammer_inode_unloadable_check Calls vput at hammer_inode.c:3282
	[-] Function: vsetflags (3)
		hammer_get_vnode Calls vsetflags at hammer_inode.c:342
		hammer_get_vnode Calls vsetflags at hammer_inode.c:344
		hammer_get_vnode Calls vsetflags at hammer_inode.c:346
	[-] Function: vx_put (1)
		hammer_get_vnode Calls vx_put at hammer_inode.c:300
[-] vfs_mount.c (1)
	[-] Function: getnewvnode (1)
		hammer_get_vnode Calls getnewvnode at hammer_inode.c:292
[-] vfs_subr.c (12)
	[-] Function: addaliasu (1)
		hammer_get_vnode Calls addaliasu at hammer_inode.c:316
	[-] Function: vattr_null (1)
		hammer_mkroot_pseudofs Calls vattr_null at hammer_inode.c:1146
	[-] Function: vclean_unlocked (1)
		hammer_unload_pseudofs_callback Calls vclean_unlocked at hammer_inode.c:1184
	[-] Function: vinitvmio (1)
		hammer_get_vnode Calls vinitvmio at hammer_inode.c:355
	[-] Function: vrecycle (2)
		hammer_vop_inactive Calls vrecycle at hammer_inode.c:186
		hammer_vop_inactive Calls vrecycle at hammer_inode.c:209
	[-] Macro: VISDIRTY (1)
		hammer_inode_dirty Addr Uses VISDIRTY at hammer_inode.c:268
	[-] Macro: VPFSROOT (3)
		hammer_get_vnode Uses VPFSROOT at hammer_inode.c:344
		hammer_get_vnode Uses VPFSROOT at hammer_inode.c:346
		hammer_unload_pseudofs_callback Addr Uses VPFSROOT at hammer_inode.c:1173
	[-] Macro: VRECLAIMED (1)
		hammer_inode_dirty Addr Uses VRECLAIMED at hammer_inode.c:268
	[-] Macro: VROOT (1)
		hammer_get_vnode Uses VROOT at hammer_inode.c:342
[-] vfs_sync.c (2)
	[-] Function: vclrisdirty (1)
		hammer_vop_reclaim Calls vclrisdirty at hammer_inode.c:245
	[-] Function: vsetisdirty (1)
		hammer_inode_dirty Calls vsetisdirty at hammer_inode.c:269
[-] vfs_vm.c (1)
	[-] Function: nvtruncbuf (1)
		hammer_inode_unloadable_check Calls nvtruncbuf at hammer_inode.c:3278
[-] vfscache.h (18)
	[-] Struct: vattr (18)
		[-] Object: va_gid (2)
			hammer_create_inode Uses va_gid at hammer_inode.c:904
			hammer_create_inode Uses va_gid at hammer_inode.c:905
		[-] Object: va_gid_uuid (1)
			hammer_create_inode Uses va_gid_uuid at hammer_inode.c:903
		[-] Object: va_mode (4)
			hammer_create_inode Uses va_mode at hammer_inode.c:844
			hammer_create_inode Addr Uses va_mode at hammer_inode.c:889
			hammer_create_inode Uses va_mode at hammer_inode.c:893
			hammer_mkroot_pseudofs Sets va_mode at hammer_inode.c:1147
		[-] Object: va_rmajor (1)
			hammer_create_inode Uses va_rmajor at hammer_inode.c:875
		[-] Object: va_rminor (1)
			hammer_create_inode Uses va_rminor at hammer_inode.c:876
		[-] Object: va_type (2)
			hammer_create_inode Uses va_type at hammer_inode.c:840
			hammer_mkroot_pseudofs Sets va_type at hammer_inode.c:1148
		[-] Object: va_uid (2)
			hammer_create_inode Uses va_uid at hammer_inode.c:897
			hammer_create_inode Uses va_uid at hammer_inode.c:898
		[-] Object: va_uid_uuid (1)
			hammer_create_inode Uses va_uid_uuid at hammer_inode.c:896
		[-] Object: va_vaflags (2)
			hammer_create_inode Uses va_vaflags at hammer_inode.c:895
			hammer_create_inode Uses va_vaflags at hammer_inode.c:902
		[-] Struct: vattr (2)
			vap Types vattr at hammer_inode.c:758
			vap Types vattr at hammer_inode.c:1134
[-] vfsops.h (6)
	[-] Struct: vop_inactive_args (4)
		[-] Object: a_vp (3)
			hammer_vop_inactive Uses a_vp at hammer_inode.c:179
			hammer_vop_inactive Uses a_vp at hammer_inode.c:186
			hammer_vop_inactive Uses a_vp at hammer_inode.c:209
		[-] Struct: vop_inactive_args (1)
			ap Types vop_inactive_args at hammer_inode.c:177
	[-] Struct: vop_reclaim_args (2)
		[-] Object: a_vp (1)
			hammer_vop_reclaim Uses a_vp at hammer_inode.c:230
		[-] Struct: vop_reclaim_args (1)
			ap Types vop_reclaim_args at hammer_inode.c:224
[-] vm_page2.h (1)
	[-] vm_page2.h (1)
		hammer_inode.c Includes vm_page2.h at hammer_inode.c:35



---



hammer_io.c (248)



[-] _null.h (30)
	[-] Macro: NULL (30)
		hammer_io_to_iostring Uses NULL at hammer_io.c:131
		hammer_io_disassociate Uses NULL at hammer_io.c:207
		hammer_io_disassociate Uses NULL at hammer_io.c:223
		hammer_io_disassociate Uses NULL at hammer_io.c:228
		hammer_io_read Uses NULL at hammer_io.c:382
		hammer_io_new Uses NULL at hammer_io.c:441
		hammer_io_inval Uses NULL at hammer_io.c:506
		hammer_io_inval Uses NULL at hammer_io.c:511
		hammer_io_release Uses NULL at hammer_io.c:562
		hammer_io_release Uses NULL at hammer_io.c:563
		hammer_io_release Uses NULL at hammer_io.c:638
		hammer_io_release Uses NULL at hammer_io.c:691
		hammer_io_modify Uses NULL at hammer_io.c:824
		hammer_modify_volume Uses NULL at hammer_io.c:904
		hammer_modify_buffer Uses NULL at hammer_io.c:926
		hammer_io_clear_modify Uses NULL at hammer_io.c:983
		hammer_io_clear_modify Uses NULL at hammer_io.c:990
		hammer_io_clear_modlist Uses NULL at hammer_io.c:1045
		hammer_io_set_modlist Uses NULL at hammer_io.c:1057
		hammer_io_complete Uses NULL at hammer_io.c:1145
		hammer_io_deallocate Uses NULL at hammer_io.c:1257
		hammer_io_deallocate Uses NULL at hammer_io.c:1258
		hammer_io_direct_write Uses NULL at hammer_io.c:1768
		hammer_io_direct_write_complete Uses NULL at hammer_io.c:1821
		hammer_io_direct_uncache_callback Uses NULL at hammer_io.c:1946
		hammer_io_direct_uncache_callback Uses NULL at hammer_io.c:1958
		hammer_io_flush_sync Uses NULL at hammer_io.c:1988
		hammer_io_flush_sync Uses NULL at hammer_io.c:1995
		hammer_io_flush_sync Uses NULL at hammer_io.c:2007
		hammer_io_flush_sync Uses NULL at hammer_io.c:2010
[-] bio.h (39)
	[-] Struct: bio (39)
		[-] Object: bio_buf (9)
			hammer_io_direct_read Uses bio_buf at hammer_io.c:1469
			hammer_io_indirect_read Uses bio_buf at hammer_io.c:1543
			hammer_indirect_callback Uses bio_buf at hammer_io.c:1624
			hammer_indirect_callback Uses bio_buf at hammer_io.c:1649
			hammer_io_direct_write Uses bio_buf at hammer_io.c:1710
			hammer_io_direct_write Uses bio_buf at hammer_io.c:1731
			hammer_io_direct_write Uses bio_buf at hammer_io.c:1771
			hammer_io_direct_write Uses bio_buf at hammer_io.c:1789
			hammer_io_direct_write_complete Uses bio_buf at hammer_io.c:1826
		[-] Object: bio_caller_info1 (6)
			hammer_io_indirect_read Sets bio_caller_info1 at hammer_io.c:1576
			hammer_indirect_callback Uses bio_caller_info1 at hammer_io.c:1648
			hammer_indirect_callback Uses bio_caller_info1 at hammer_io.c:1659
			hammer_indirect_callback Uses bio_caller_info1 at hammer_io.c:1662
			hammer_io_direct_write Sets bio_caller_info1 at hammer_io.c:1743
			hammer_io_direct_write_complete Uses bio_caller_info1 at hammer_io.c:1820
		[-] Object: bio_caller_info2 (3)
			hammer_io_indirect_read Sets bio_caller_info2 at hammer_io.c:1577
			hammer_io_indirect_read Sets bio_caller_info2 at hammer_io.c:1579
			hammer_indirect_callback Uses bio_caller_info2 at hammer_io.c:1658
		[-] Object: bio_caller_info3 (2)
			hammer_io_indirect_read Sets bio_caller_info3 at hammer_io.c:1581
			hammer_indirect_callback Uses bio_caller_info3 at hammer_io.c:1650
		[-] Object: bio_done (1)
			hammer_io_direct_write Sets bio_done at hammer_io.c:1742
		[-] Object: bio_flags (2)
			hammer_indirect_callback Uses bio_flags at hammer_io.c:1644
			hammer_indirect_callback Modifys bio_flags at hammer_io.c:1646
		[-] Object: bio_offset (5)
			hammer_io_direct_read Uses bio_offset at hammer_io.c:1461
			hammer_io_direct_read Sets bio_offset at hammer_io.c:1496
			hammer_io_indirect_read Uses bio_offset at hammer_io.c:1535
			hammer_io_direct_write Sets bio_offset at hammer_io.c:1741
			hammer_io_direct_write Sets bio_offset at hammer_io.c:1753
		[-] Struct: bio (11)
			hammer_indirect_callback Uses bio at hammer_io.c:57
			hammer_io_direct_write_complete Uses bio at hammer_io.c:58
			bio Types bio at hammer_io.c:1450
			nbio Types bio at hammer_io.c:1457
			bio Types bio at hammer_io.c:1525
			bio Types bio at hammer_io.c:1622
			obio Types bio at hammer_io.c:1626
			bio Types bio at hammer_io.c:1693
			nbio Types bio at hammer_io.c:1702
			nbio Types bio at hammer_io.c:1813
			obio Types bio at hammer_io.c:1815
[-] buf.h (52)
	[-] Struct: buf (48)
		[-] Object: b_bcount (1)
			hammer_io_flush_sync Sets b_bcount at hammer_io.c:1998
		[-] Object: b_bufsize (15)
			hammer_io_direct_read Uses b_bufsize at hammer_io.c:1470
			hammer_io_direct_read Uses b_bufsize at hammer_io.c:1498
			hammer_io_indirect_read Uses b_bufsize at hammer_io.c:1544
			hammer_io_indirect_read Uses b_bufsize at hammer_io.c:1588
			hammer_io_indirect_read Uses b_bufsize at hammer_io.c:1595
			hammer_indirect_callback Uses b_bufsize at hammer_io.c:1660
			hammer_indirect_callback Uses b_bufsize at hammer_io.c:1660
			hammer_indirect_callback Uses b_bufsize at hammer_io.c:1663
			hammer_indirect_callback Uses b_bufsize at hammer_io.c:1663
			hammer_indirect_callback Uses b_bufsize at hammer_io.c:1676
			hammer_indirect_callback Uses b_bufsize at hammer_io.c:1676
			hammer_indirect_callback Uses b_bufsize at hammer_io.c:1677
			hammer_io_direct_write Uses b_bufsize at hammer_io.c:1732
			hammer_io_direct_write Uses b_bufsize at hammer_io.c:1755
			hammer_io_flush_sync Sets b_bufsize at hammer_io.c:1997
		[-] Object: b_data (7)
			hammer_indirect_callback Uses b_data at hammer_io.c:1660
			hammer_indirect_callback Uses b_data at hammer_io.c:1660
			hammer_indirect_callback Uses b_data at hammer_io.c:1663
			hammer_indirect_callback Uses b_data at hammer_io.c:1663
			hammer_indirect_callback Uses b_data at hammer_io.c:1677
			hammer_indirect_callback Uses b_data at hammer_io.c:1677
			hammer_io_direct_write Uses b_data at hammer_io.c:1774
		[-] Struct: buf (25)
			hammer_io_deallocate Uses buf at hammer_io.c:56
			bp Types buf at hammer_io.c:201
			bp Types buf at hammer_io.c:379
			bp Types buf at hammer_io.c:439
			bp Types buf at hammer_io.c:494
			hammer_io_release Types buf at hammer_io.c:557
			bp Types buf at hammer_io.c:560
			bp Types buf at hammer_io.c:709
			bp Types buf at hammer_io.c:1100
			bp Types buf at hammer_io.c:1116
			bp Types buf at hammer_io.c:1223
			bp1 Types buf at hammer_io.c:1298
			bp2 Types buf at hammer_io.c:1298
			bp Types buf at hammer_io.c:1320
			bp Types buf at hammer_io.c:1332
			bp Types buf at hammer_io.c:1413
			bp Types buf at hammer_io.c:1456
			bp Types buf at hammer_io.c:1531
			bp Types buf at hammer_io.c:1624
			obp Types buf at hammer_io.c:1625
			bp Types buf at hammer_io.c:1701
			bp Types buf at hammer_io.c:1816
			bp Types buf at hammer_io.c:1943
			bp_base Types buf at hammer_io.c:1988
			bp Types buf at hammer_io.c:1989
	[-] Struct: vnode (4)
		[-] Struct: vnode (4)
			devvp Types vnode at hammer_io.c:377
			devvp Types vnode at hammer_io.c:437
			vp Types vnode at hammer_io.c:1275
			vp Types vnode at hammer_io.c:1942
[-] buf2.h (5)
	[-] Macro: B_NOTMETA (4)
		hammer_io_notmeta Addr Uses B_NOTMETA at hammer_io.c:352
		hammer_io_notmeta Uses B_NOTMETA at hammer_io.c:356
		hammer_io_indirect_read Uses B_NOTMETA at hammer_io.c:1589
		hammer_io_indirect_read Uses B_NOTMETA at hammer_io.c:1596
	[-] buf2.h (1)
		hammer_io.c Includes buf2.h at hammer_io.c:51
[-] dirfs_vnops.c (9)
	[-] Macro: B_ERROR (9)
		hammer_io_complete Addr Uses B_ERROR at hammer_io.c:1143
		hammer_io_complete Uses B_ERROR at hammer_io.c:1159
		hammer_io_direct_read Uses B_ERROR at hammer_io.c:1506
		hammer_io_indirect_read Uses B_ERROR at hammer_io.c:1605
		hammer_indirect_callback Addr Uses B_ERROR at hammer_io.c:1652
		hammer_indirect_callback Uses B_ERROR at hammer_io.c:1656
		hammer_indirect_callback Uses B_ERROR at hammer_io.c:1670
		hammer_io_direct_write Uses B_ERROR at hammer_io.c:1792
		hammer_io_direct_write_complete Addr Uses B_ERROR at hammer_io.c:1828
[-] kern_synch.c (1)
	[-] Function: tsleep_interlock (1)
		hammer_io_wait Calls tsleep_interlock at hammer_io.c:251
[-] lwkt_token.c (40)
	[-] Function: lwkt_gettoken (18)
		hammer_io_wait Calls lwkt_gettoken at hammer_io.c:248
		hammer_io_wait_all Calls lwkt_gettoken at hammer_io.c:274
		hammer_io_clear_error Calls lwkt_gettoken at hammer_io.c:315
		hammer_io_clear_error_noassert Calls lwkt_gettoken at hammer_io.c:329
		hammer_io_notmeta Calls lwkt_gettoken at hammer_io.c:355
		hammer_io_inval Calls lwkt_gettoken at hammer_io.c:498
		hammer_io_flush Calls lwkt_gettoken at hammer_io.c:783
		hammer_io_write_interlock Calls lwkt_gettoken at hammer_io.c:874
		hammer_io_clear_modify Calls lwkt_gettoken at hammer_io.c:974
		hammer_io_clear_modlist Calls lwkt_gettoken at hammer_io.c:1041
		hammer_io_set_modlist Calls lwkt_gettoken at hammer_io.c:1056
		hammer_io_complete Calls lwkt_gettoken at hammer_io.c:1122
		hammer_io_complete Calls lwkt_gettoken at hammer_io.c:1144
		hammer_io_deallocate Calls lwkt_gettoken at hammer_io.c:1230
		hammer_io_checkwrite Calls lwkt_gettoken at hammer_io.c:1340
		hammer_io_direct_write_complete Calls lwkt_gettoken at hammer_io.c:1824
		hammer_io_direct_write_complete Calls lwkt_gettoken at hammer_io.c:1829
		hammer_io_direct_wait Calls lwkt_gettoken at hammer_io.c:1872
	[-] Function: lwkt_reltoken (22)
		hammer_io_wait Calls lwkt_reltoken at hammer_io.c:255
		hammer_io_wait_all Calls lwkt_reltoken at hammer_io.c:276
		hammer_io_wait_all Calls lwkt_reltoken at hammer_io.c:300
		hammer_io_clear_error Calls lwkt_reltoken at hammer_io.c:321
		hammer_io_clear_error_noassert Calls lwkt_reltoken at hammer_io.c:334
		hammer_io_notmeta Calls lwkt_reltoken at hammer_io.c:357
		hammer_io_inval Calls lwkt_reltoken at hammer_io.c:533
		hammer_io_flush Calls lwkt_reltoken at hammer_io.c:785
		hammer_io_write_interlock Calls lwkt_reltoken at hammer_io.c:880
		hammer_io_clear_modify Calls lwkt_reltoken at hammer_io.c:976
		hammer_io_clear_modify Calls lwkt_reltoken at hammer_io.c:993
		hammer_io_clear_modlist Calls lwkt_reltoken at hammer_io.c:1047
		hammer_io_set_modlist Calls lwkt_reltoken at hammer_io.c:1085
		hammer_io_complete Calls lwkt_reltoken at hammer_io.c:1147
		hammer_io_complete Calls lwkt_reltoken at hammer_io.c:1202
		hammer_io_deallocate Calls lwkt_reltoken at hammer_io.c:1268
		hammer_io_checkwrite Calls lwkt_reltoken at hammer_io.c:1349
		hammer_io_checkwrite Calls lwkt_reltoken at hammer_io.c:1364
		hammer_io_checkwrite Calls lwkt_reltoken at hammer_io.c:1401
		hammer_io_direct_write_complete Calls lwkt_reltoken at hammer_io.c:1832
		hammer_io_direct_write_complete Calls lwkt_reltoken at hammer_io.c:1847
		hammer_io_direct_wait Calls lwkt_reltoken at hammer_io.c:1877
[-] memset.c (1)
	[-] Function: bzero (1)
		hammer_io_wait_all Calls bzero at hammer_io.c:281
[-] nfs_serv.c (1)
	[-] Macro: FINDBLK_TEST (1)
		hammer_io_direct_uncache_callback Uses FINDBLK_TEST at hammer_io.c:1958
[-] os.c (2)
	[-] Function: bcopy (2)
		hammer_indirect_callback Calls bcopy at hammer_io.c:1677
		hammer_io_direct_write Calls bcopy at hammer_io.c:1774
[-] param.h (1)
	[-] Macro: PINTERLOCKED (1)
		hammer_io_wait Uses PINTERLOCKED at hammer_io.c:253
[-] queue.h (11)
	[-] Macro: TAILQ_EMPTY (1)
		hammer_io_wait_all Uses TAILQ_EMPTY at hammer_io.c:275
	[-] Macro: TAILQ_FIRST (3)
		hammer_io_wait_all Uses TAILQ_FIRST at hammer_io.c:289
		hammer_io_wait_all Uses TAILQ_FIRST at hammer_io.c:297
		hammer_io_complete Uses TAILQ_FIRST at hammer_io.c:1175
	[-] Macro: TAILQ_FOREACH (1)
		hammer_io_clear_modify Uses TAILQ_FOREACH at hammer_io.c:1012
	[-] Macro: TAILQ_INSERT_TAIL (3)
		hammer_io_wait_all Uses TAILQ_INSERT_TAIL at hammer_io.c:288
		hammer_io_flush Uses TAILQ_INSERT_TAIL at hammer_io.c:784
		hammer_io_checkwrite Uses TAILQ_INSERT_TAIL at hammer_io.c:1398
	[-] Macro: TAILQ_NEXT (1)
		hammer_io_complete Uses TAILQ_NEXT at hammer_io.c:1176
	[-] Macro: TAILQ_REMOVE (2)
		hammer_io_wait_all Uses TAILQ_REMOVE at hammer_io.c:296
		hammer_io_complete Uses TAILQ_REMOVE at hammer_io.c:1180
[-] quotacheck.c (1)
	[-] Function: bread (1)
		hammer_io_read Calls bread at hammer_io.c:393
[-] subr_diskgpt.c (3)
	[-] Macro: B_AGE (2)
		hammer_indirect_callback Uses B_AGE at hammer_io.c:1679
		hammer_io_direct_write Uses B_AGE at hammer_io.c:1772
	[-] Macro: B_INVAL (1)
		hammer_io_direct_write_complete Uses B_INVAL at hammer_io.c:1833
[-] tree.h (6)
	[-] Macro: RB_FOREACH (1)
		hammer_io_flush_sync Uses RB_FOREACH at hammer_io.c:1991
	[-] Macro: RB_GENERATE (1)
		hammer_io.c Uses RB_GENERATE at hammer_io.c:84
	[-] Macro: RB_INSERT (2)
		hammer_io_set_modlist Uses RB_INSERT at hammer_io.c:1080
		hammer_io_deallocate Uses RB_INSERT at hammer_io.c:1260
	[-] Macro: RB_REMOVE (2)
		hammer_io_clear_modify Uses RB_REMOVE at hammer_io.c:989
		hammer_io_clear_modlist Uses RB_REMOVE at hammer_io.c:1044
[-] ufs_readwrite.c (1)
	[-] Macro: B_CLUSTEROK (1)
		hammer_io_release Uses B_CLUSTEROK at hammer_io.c:631
[-] utilities.c (3)
	[-] Function: getblk (3)
		hammer_io_new Calls getblk at hammer_io.c:442
		hammer_io_inval Calls getblk at hammer_io.c:509
		hammer_io_direct_uncache_callback Calls getblk at hammer_io.c:1960
[-] vfs_bio.c (31)
	[-] Function: bdwrite (1)
		hammer_io_release Calls bdwrite at hammer_io.c:632
	[-] Function: biodone (6)
		hammer_io_direct_read Calls biodone at hammer_io.c:1507
		hammer_io_indirect_read Calls biodone at hammer_io.c:1606
		hammer_indirect_callback Calls biodone at hammer_io.c:1681
		hammer_io_direct_write Calls biodone at hammer_io.c:1779
		hammer_io_direct_write Calls biodone at hammer_io.c:1793
		hammer_io_direct_write_complete Calls biodone at hammer_io.c:1849
	[-] Function: biowait (1)
		hammer_io_flush_sync Calls biowait at hammer_io.c:2009
	[-] Function: bpdone (1)
		hammer_indirect_callback Calls bpdone at hammer_io.c:1645
	[-] Function: bqrelse (2)
		hammer_io_inval Calls bqrelse at hammer_io.c:524
		hammer_indirect_callback Calls bqrelse at hammer_io.c:1682
	[-] Function: breadcb (1)
		hammer_io_indirect_read Calls breadcb at hammer_io.c:1595
	[-] Function: bremfree (1)
		hammer_io_inval Calls bremfree at hammer_io.c:507
	[-] Function: bundirty (2)
		hammer_io_inval Calls bundirty at hammer_io.c:528
		hammer_io_complete Calls bundirty at hammer_io.c:1160
	[-] Function: findblk (2)
		hammer_io_inval Calls findblk at hammer_io.c:506
		hammer_io_direct_uncache_callback Calls findblk at hammer_io.c:1958
	[-] Function: pop_bio (1)
		hammer_io_direct_write_complete Calls pop_bio at hammer_io.c:1827
	[-] Function: push_bio (3)
		hammer_io_direct_read Calls push_bio at hammer_io.c:1495
		hammer_io_direct_write Calls push_bio at hammer_io.c:1740
		hammer_io_direct_write Calls push_bio at hammer_io.c:1752
	[-] Function: regetblk (5)
		hammer_io_new Calls regetblk at hammer_io.c:453
		hammer_io_release Calls regetblk at hammer_io.c:611
		hammer_io_release Calls regetblk at hammer_io.c:677
		hammer_io_flush Calls regetblk at hammer_io.c:734
		hammer_io_modify Calls regetblk at hammer_io.c:836
	[-] Function: vfs_bio_clrbuf (1)
		hammer_io_new Calls vfs_bio_clrbuf at hammer_io.c:459
	[-] Function: vn_strategy (3)
		hammer_io_direct_read Calls vn_strategy at hammer_io.c:1499
		hammer_io_direct_write Calls vn_strategy at hammer_io.c:1757
		hammer_io_flush_sync Calls vn_strategy at hammer_io.c:2004
	[-] Function: waitrunningbufspace (1)
		hammer_io_limit_backlog Calls waitrunningbufspace at hammer_io.c:2020
[-] vfs_cluster.c (2)
	[-] Function: cluster_awrite (1)
		hammer_io_flush Calls cluster_awrite at hammer_io.c:786
	[-] Function: cluster_readcb (1)
		hammer_io_indirect_read Calls cluster_readcb at hammer_io.c:1587
[-] vfs_lock.c (1)
	[-] Function: vput (1)
		hammer_io_direct_uncache_callback Calls vput at hammer_io.c:1964
[-] vfs_vm.c (6)
	[-] Macro: B_NOCACHE (2)
		hammer_io_disassociate Uses B_NOCACHE at hammer_io.c:217
		hammer_io_inval Uses B_NOCACHE at hammer_io.c:529
	[-] Macro: B_RELBUF (2)
		hammer_io_disassociate Uses B_RELBUF at hammer_io.c:217
		hammer_io_inval Uses B_RELBUF at hammer_io.c:529
	[-] Macro: NOOFFSET (2)
		hammer_io_direct_uncache_callback Uses NOOFFSET at hammer_io.c:1959
		hammer_io_direct_uncache_callback Uses NOOFFSET at hammer_io.c:1961
[-] vm_pager.c (2)
	[-] Function: getpbuf (1)
		hammer_io_flush_sync Calls getpbuf at hammer_io.c:1995
	[-] Function: relpbuf (1)
		hammer_io_flush_sync Calls relpbuf at hammer_io.c:2010



---



hammer_ioctl.c (35)



[-] _null.h (13)
	[-] Macro: NULL (13)
		hammer_ioc_gethistory Uses NULL at hammer_ioctl.c:318
		hammer_ioc_synctid Uses NULL at hammer_ioctl.c:521
		hammer_ioc_set_version Uses NULL at hammer_ioctl.c:635
		hammer_ioc_set_version Uses NULL at hammer_ioctl.c:635
		hammer_ioc_add_snapshot Uses NULL at hammer_ioctl.c:733
		hammer_ioc_del_snapshot Uses NULL at hammer_ioctl.c:810
		hammer_ioc_del_snapshot Uses NULL at hammer_ioctl.c:834
		hammer_ioc_get_snapshot Uses NULL at hammer_ioctl.c:879
		hammer_ioc_get_config Uses NULL at hammer_ioctl.c:959
		hammer_ioc_set_config Uses NULL at hammer_ioctl.c:1005
		hammer_ioc_set_config Uses NULL at hammer_ioctl.c:1029
		hammer_ioc_get_data Uses NULL at hammer_ioctl.c:1068
		hammer_ioc_get_data Uses NULL at hammer_ioctl.c:1068
[-] kern_prot.c (3)
	[-] Function: priv_check_cred (3)
		hammer_ioctl Calls priv_check_cred at hammer_ioctl.c:72
		hammer_ioctl Calls priv_check_cred at hammer_ioctl.c:197
		hammer_ioctl Calls priv_check_cred at hammer_ioctl.c:207
[-] memset.c (2)
	[-] Function: bzero (2)
		hammer_ioc_add_snapshot Calls bzero at hammer_ioctl.c:742
		hammer_ioc_set_config Calls bzero at hammer_ioctl.c:1011
[-] mount.h (3)
	[-] Macro: MNT_NOWAIT (1)
		hammer_ioc_synctid Uses MNT_NOWAIT at hammer_ioctl.c:520
	[-] Macro: MNT_WAIT (2)
		hammer_ioc_synctid Uses MNT_WAIT at hammer_ioctl.c:525
		hammer_ioc_synctid Uses MNT_WAIT at hammer_ioctl.c:530
[-] priv.h (3)
	[-] Macro: PRIV_HAMMER_IOCTL (1)
		hammer_ioctl Uses PRIV_HAMMER_IOCTL at hammer_ioctl.c:72
	[-] Macro: PRIV_HAMMER_VOLUME (2)
		hammer_ioctl Uses PRIV_HAMMER_VOLUME at hammer_ioctl.c:197
		hammer_ioctl Uses PRIV_HAMMER_VOLUME at hammer_ioctl.c:207
[-] subr_prf.c (8)
	[-] Function: ksnprintf (8)
		hammer_ioc_get_version Calls ksnprintf at hammer_ioctl.c:566
		hammer_ioc_get_version Calls ksnprintf at hammer_ioctl.c:570
		hammer_ioc_get_version Calls ksnprintf at hammer_ioctl.c:574
		hammer_ioc_get_version Calls ksnprintf at hammer_ioctl.c:578
		hammer_ioc_get_version Calls ksnprintf at hammer_ioctl.c:582
		hammer_ioc_get_version Calls ksnprintf at hammer_ioctl.c:586
		hammer_ioc_get_version Calls ksnprintf at hammer_ioctl.c:590
		hammer_ioc_get_version Calls ksnprintf at hammer_ioctl.c:594
[-] types.h (2)
	[-] Typedef: caddr_t (1)
		data Types caddr_t at hammer_ioctl.c:65
	[-] Typedef: u_long (1)
		com Types u_long at hammer_ioctl.c:65
[-] ucred.h (1)
	[-] Struct: ucred (1)
		[-] Struct: ucred (1)
			cred Types ucred at hammer_ioctl.c:66



---



hammer_ioctl.h (31)



[-] ioccom.h (28)
	[-] Macro: _IOR (1)
		HAMMERIOC_GET_INFO Macros _IOR at hammer_ioctl.h:482
	[-] Macro: _IOWR (26)
		HAMMERIOC_PRUNE Macros _IOWR at hammer_ioctl.h:467
		HAMMERIOC_GETHISTORY Macros _IOWR at hammer_ioctl.h:468
		HAMMERIOC_REBLOCK Macros _IOWR at hammer_ioctl.h:469
		HAMMERIOC_SYNCTID Macros _IOWR at hammer_ioctl.h:470
		HAMMERIOC_SET_PSEUDOFS Macros _IOWR at hammer_ioctl.h:471
		HAMMERIOC_GET_PSEUDOFS Macros _IOWR at hammer_ioctl.h:472
		HAMMERIOC_MIRROR_READ Macros _IOWR at hammer_ioctl.h:473
		HAMMERIOC_MIRROR_WRITE Macros _IOWR at hammer_ioctl.h:474
		HAMMERIOC_UPG_PSEUDOFS Macros _IOWR at hammer_ioctl.h:475
		HAMMERIOC_DGD_PSEUDOFS Macros _IOWR at hammer_ioctl.h:476
		HAMMERIOC_RMR_PSEUDOFS Macros _IOWR at hammer_ioctl.h:477
		HAMMERIOC_WAI_PSEUDOFS Macros _IOWR at hammer_ioctl.h:478
		HAMMERIOC_GET_VERSION Macros _IOWR at hammer_ioctl.h:479
		HAMMERIOC_SET_VERSION Macros _IOWR at hammer_ioctl.h:480
		HAMMERIOC_REBALANCE Macros _IOWR at hammer_ioctl.h:481
		HAMMERIOC_ADD_VOLUME Macros _IOWR at hammer_ioctl.h:483
		HAMMERIOC_ADD_SNAPSHOT Macros _IOWR at hammer_ioctl.h:484
		HAMMERIOC_DEL_SNAPSHOT Macros _IOWR at hammer_ioctl.h:485
		HAMMERIOC_GET_SNAPSHOT Macros _IOWR at hammer_ioctl.h:486
		HAMMERIOC_GET_CONFIG Macros _IOWR at hammer_ioctl.h:487
		HAMMERIOC_SET_CONFIG Macros _IOWR at hammer_ioctl.h:488
		HAMMERIOC_DEL_VOLUME Macros _IOWR at hammer_ioctl.h:489
		HAMMERIOC_DEDUP Macros _IOWR at hammer_ioctl.h:490
		HAMMERIOC_GET_DATA Macros _IOWR at hammer_ioctl.h:491
		HAMMERIOC_LIST_VOLUMES Macros _IOWR at hammer_ioctl.h:492
		HAMMERIOC_SCAN_PSEUDOFS Macros _IOWR at hammer_ioctl.h:493
	[-] ioccom.h (1)
		hammer_ioctl.h Includes ioccom.h at hammer_ioctl.h:44
[-] param.h (2)
	[-] Macro: MAXPATHLEN (1)
		hammer_ioc_volume Uses MAXPATHLEN at hammer_ioctl.h:334
	[-] param.h (1)
		hammer_ioctl.h Includes param.h at hammer_ioctl.h:43
[-] route6d.c (1)
	[-] Macro: offsetof (1)
		HAMMER_MREC_CRCOFF Macros offsetof at hammer_ioctl.h:390



---



hammer_mirror.c (11)



[-] _null.h (7)
	[-] Macro: NULL (7)
		hammer_ioc_mirror_read Uses NULL at hammer_mirror.c:111
		hammer_ioc_mirror_read Uses NULL at hammer_mirror.c:111
		hammer_ioc_mirror_write Uses NULL at hammer_mirror.c:362
		hammer_ioc_mirror_write Uses NULL at hammer_mirror.c:362
		hammer_ioc_mirror_write Uses NULL at hammer_mirror.c:405
		hammer_mirror_delete_to Uses NULL at hammer_mirror.c:758
		hammer_mirror_update Uses NULL at hammer_mirror.c:831
[-] crc32.c (1)
	[-] Function: crc32_ext (1)
		hammer_ioc_mirror_read Calls crc32_ext at hammer_mirror.c:280
[-] memset.c (2)
	[-] Function: bzero (2)
		hammer_ioc_mirror_read Calls bzero at hammer_mirror.c:101
		hammer_ioc_mirror_read Calls bzero at hammer_mirror.c:102
[-] uwrapper.c (1)
	[-] Function: copyin (1)
		hammer_ioc_mirror_write Calls copyin at hammer_mirror.c:415



---



hammer_mount.h (2)



[-] mount.h (1)
	[-] mount.h (1)
		hammer_mount.h Includes mount.h at hammer_mount.h:44
[-] types.h (1)
	[-] Macro: _SYS_TYPES_H_ (1)
		hammer_mount.h Uses _SYS_TYPES_H_ at hammer_mount.h:40



---



hammer_object.c (59)



[-] _null.h (31)
	[-] Macro: NULL (31)
		hammer_flush_record_done Uses NULL at hammer_object.c:323
		hammer_flush_record_done Uses NULL at hammer_object.c:330
		hammer_flush_record_done Uses NULL at hammer_object.c:333
		hammer_rel_mem_record Uses NULL at hammer_object.c:402
		hammer_rel_mem_record Uses NULL at hammer_object.c:405
		hammer_rel_mem_record Uses NULL at hammer_object.c:478
		hammer_rel_mem_record Uses NULL at hammer_object.c:481
		hammer_rel_mem_record Uses NULL at hammer_object.c:483
		hammer_rec_scan_callback Uses NULL at hammer_object.c:545
		hammer_mem_lookup Uses NULL at hammer_object.c:601
		hammer_mem_lookup Uses NULL at hammer_object.c:604
		hammer_mem_first Uses NULL at hammer_object.c:623
		hammer_mem_first Uses NULL at hammer_object.c:626
		hammer_ip_del_direntry Uses NULL at hammer_object.c:784
		hammer_ip_del_direntry Uses NULL at hammer_object.c:862
		hammer_ip_get_bulk Uses NULL at hammer_object.c:913
		hammer_ip_add_bulk Uses NULL at hammer_object.c:973
		hammer_ip_add_bulk Uses NULL at hammer_object.c:976
		hammer_ip_replace_bulk Uses NULL at hammer_object.c:1012
		hammer_ip_sync_record_cursor Uses NULL at hammer_object.c:1205
		hammer_ip_sync_record_cursor Uses NULL at hammer_object.c:1268
		hammer_mem_add Uses NULL at hammer_object.c:1378
		hammer_ip_first Uses NULL at hammer_object.c:1542
		hammer_ip_next Uses NULL at hammer_object.c:1670
		hammer_ip_next Uses NULL at hammer_object.c:1678
		hammer_ip_next Uses NULL at hammer_object.c:1835
		hammer_ip_resolve_data Uses NULL at hammer_object.c:1872
		hammer_ip_delete_record Uses NULL at hammer_object.c:2238
		hammer_create_at_cursor Uses NULL at hammer_object.c:2287
		hammer_create_at_cursor Uses NULL at hammer_object.c:2302
		hammer_create_at_cursor Uses NULL at hammer_object.c:2337
[-] cdefs.h (2)
	[-] Macro: __unused (2)
		hammer_object.c Uses __unused at hammer_object.c:40
		hammer_frontend_trunc_callback Uses __unused at hammer_object.c:1070
[-] ip.h (1)
	[-] Struct: ip (1)
		[-] Struct: ip (1)
			__debugvar Types ip at hammer_object.c:1539
[-] kern_slaballoc.c (4)
	[-] Function: kfree (2)
		hammer_rel_mem_record Calls kfree at hammer_object.c:465
		hammer_rel_mem_record Calls kfree at hammer_object.c:485
	[-] Function: kmalloc (2)
		hammer_alloc_mem_record Calls kmalloc at hammer_object.c:271
		hammer_alloc_mem_record Calls kmalloc at hammer_object.c:280
[-] malloc.h (5)
	[-] Macro: M_USE_RESERVE (1)
		hammer_alloc_mem_record Uses M_USE_RESERVE at hammer_object.c:272
	[-] Macro: M_WAITOK (2)
		hammer_alloc_mem_record Uses M_WAITOK at hammer_object.c:272
		hammer_alloc_mem_record Uses M_WAITOK at hammer_object.c:280
	[-] Macro: M_ZERO (2)
		hammer_alloc_mem_record Uses M_ZERO at hammer_object.c:272
		hammer_alloc_mem_record Uses M_ZERO at hammer_object.c:280
[-] mman.h (2)
	[-] Typedef: off_t (2)
		file_offset Types off_t at hammer_object.c:951
		file_size Types off_t at hammer_object.c:1037
[-] os.c (3)
	[-] Function: bcopy (3)
		hammer_ip_add_direntry Calls bcopy at hammer_object.c:682
		hammer_ip_sync_record_cursor Calls bcopy at hammer_object.c:1272
		hammer_create_at_cursor Calls bcopy at hammer_object.c:2325
[-] queue.h (4)
	[-] Macro: TAILQ_INSERT_TAIL (2)
		hammer_ip_add_direntry Uses TAILQ_INSERT_TAIL at hammer_object.c:724
		hammer_ip_del_direntry Uses TAILQ_INSERT_TAIL at hammer_object.c:814
	[-] Macro: TAILQ_REMOVE (2)
		hammer_flush_record_done Uses TAILQ_REMOVE at hammer_object.c:331
		hammer_rel_mem_record Uses TAILQ_REMOVE at hammer_object.c:403
[-] tree.h (5)
	[-] Macro: RB_EMPTY (2)
		hammer_rel_mem_record Uses RB_EMPTY at hammer_object.c:418
		hammer_rel_mem_record Uses RB_EMPTY at hammer_object.c:446
	[-] Macro: RB_GENERATE (1)
		hammer_object.c Uses RB_GENERATE at hammer_object.c:255
	[-] Macro: RB_INSERT (1)
		hammer_mem_add Uses RB_INSERT at hammer_object.c:1369
	[-] Macro: RB_REMOVE (1)
		hammer_rel_mem_record Uses RB_REMOVE at hammer_object.c:413
[-] uwrapper.c (1)
	[-] Function: copyin (1)
		hammer_create_at_cursor Calls copyin at hammer_object.c:2311
[-] vfs_subr.c (1)
	[-] Macro: VINACTIVE (1)
		hammer_ip_del_direntry Addr Uses VINACTIVE at hammer_object.c:862





---



hammer_ondisk.c (235)



[-] _null.h (72)
	[-] Macro: NULL (72)
		hammer_install_volume Uses NULL at hammer_ondisk.c:117
		hammer_install_volume Uses NULL at hammer_ondisk.c:140
		hammer_install_volume Uses NULL at hammer_ondisk.c:165
		hammer_install_volume Uses NULL at hammer_ondisk.c:252
		hammer_install_volume Uses NULL at hammer_ondisk.c:265
		hammer_install_volume Uses NULL at hammer_ondisk.c:267
		hammer_adjust_volume_mode Uses NULL at hammer_ondisk.c:285
		hammer_adjust_volume_mode Uses NULL at hammer_ondisk.c:286
		hammer_adjust_volume_mode Uses NULL at hammer_ondisk.c:289
		hammer_adjust_volume_mode Uses NULL at hammer_ondisk.c:290
		hammer_unload_volume Uses NULL at hammer_ondisk.c:305
		hammer_unload_volume Uses NULL at hammer_ondisk.c:332
		hammer_unload_volume Uses NULL at hammer_ondisk.c:354
		hammer_unload_volume Uses NULL at hammer_ondisk.c:361
		hammer_unload_volume Uses NULL at hammer_ondisk.c:365
		hammer_unload_volume Uses NULL at hammer_ondisk.c:376
		hammer_unload_volume Uses NULL at hammer_ondisk.c:385
		hammer_free_volume Uses NULL at hammer_ondisk.c:407
		hammer_free_volume Uses NULL at hammer_ondisk.c:411
		hammer_get_volume Uses NULL at hammer_ondisk.c:429
		hammer_get_volume Uses NULL at hammer_ondisk.c:431
		hammer_get_volume Uses NULL at hammer_ondisk.c:442
		hammer_get_root_volume Uses NULL at hammer_ondisk.c:477
		hammer_get_root_volume Uses NULL at hammer_ondisk.c:488
		hammer_load_volume Uses NULL at hammer_ondisk.c:506
		hammer_rel_volume Uses NULL at hammer_ondisk.c:535
		hammer_mountcheck_volumes Uses NULL at hammer_ondisk.c:552
		hammer_get_buffer Uses NULL at hammer_ondisk.c:654
		hammer_get_buffer Uses NULL at hammer_ondisk.c:697
		hammer_get_buffer Uses NULL at hammer_ondisk.c:706
		hammer_get_buffer Uses NULL at hammer_ondisk.c:707
		hammer_get_buffer Uses NULL at hammer_ondisk.c:731
		hammer_get_buffer Uses NULL at hammer_ondisk.c:746
		hammer_get_buffer Uses NULL at hammer_ondisk.c:749
		hammer_load_buffer Uses NULL at hammer_ondisk.c:898
		hammer_unload_buffer Uses NULL at hammer_ondisk.c:954
		hammer_ref_buffer Uses NULL at hammer_ondisk.c:1013
		hammer_rel_buffer Uses NULL at hammer_ondisk.c:1043
		hammer_rel_buffer Uses NULL at hammer_ondisk.c:1077
		hammer_rel_buffer Uses NULL at hammer_ondisk.c:1082
		_hammer_bread Uses NULL at hammer_ondisk.c:1126
		_hammer_bread Uses NULL at hammer_ondisk.c:1139
		_hammer_bread Uses NULL at hammer_ondisk.c:1140
		hammer_get_node Uses NULL at hammer_ondisk.c:1221
		hammer_get_node Uses NULL at hammer_ondisk.c:1240
		hammer_ref_node Uses NULL at hammer_ondisk.c:1256
		hammer_load_node Uses NULL at hammer_ondisk.c:1277
		hammer_load_node Uses NULL at hammer_ondisk.c:1288
		hammer_load_node Uses NULL at hammer_ondisk.c:1290
		hammer_ref_node_safe Uses NULL at hammer_ondisk.c:1353
		hammer_ref_node_safe Uses NULL at hammer_ondisk.c:1358
		hammer_ref_node_safe Uses NULL at hammer_ondisk.c:1367
		_hammer_rel_node Uses NULL at hammer_ondisk.c:1415
		_hammer_rel_node Uses NULL at hammer_ondisk.c:1435
		hammer_cache_node Uses NULL at hammer_ondisk.c:1482
		hammer_uncache_node Uses NULL at hammer_ondisk.c:1499
		hammer_uncache_node Uses NULL at hammer_ondisk.c:1501
		hammer_flush_node Uses NULL at hammer_ondisk.c:1526
		hammer_flush_node Uses NULL at hammer_ondisk.c:1528
		hammer_flush_node Uses NULL at hammer_ondisk.c:1536
		hammer_flush_node Uses NULL at hammer_ondisk.c:1539
		hammer_flush_node Uses NULL at hammer_ondisk.c:1540
		hammer_flush_buffer_nodes Uses NULL at hammer_ondisk.c:1576
		hammer_flush_buffer_nodes Uses NULL at hammer_ondisk.c:1577
		hammer_flush_buffer_nodes Uses NULL at hammer_ondisk.c:1585
		hammer_flush_buffer_nodes Uses NULL at hammer_ondisk.c:1587
		hammer_alloc_btree Uses NULL at hammer_ondisk.c:1605
		hammer_alloc_btree Uses NULL at hammer_ondisk.c:1606
		hammer_alloc_data Uses NULL at hammer_ondisk.c:1679
		hammer_sync_hmp Uses NULL at hammer_ondisk.c:1743
		hammer_sync_hmp Uses NULL at hammer_ondisk.c:1744
		hammer_sync_scan2 Uses NULL at hammer_ondisk.c:1757
[-] buf.h (10)
	[-] Struct: buf (7)
		[-] Object: b_bcount (1)
			hammer_unload_volume Uses b_bcount at hammer_ondisk.c:316
		[-] Object: b_data (2)
			hammer_install_volume Uses b_data at hammer_ondisk.c:183
			hammer_unload_volume Uses b_data at hammer_ondisk.c:320
		[-] Struct: buf (4)
			bp Types buf at hammer_ondisk.c:117
			bp Types buf at hammer_ondisk.c:305
			bp Types buf at hammer_ondisk.c:531
			bp Types buf at hammer_ondisk.c:1043
	[-] Struct: vnode (3)
		[-] Struct: vnode (3)
			devvp Types vnode at hammer_ondisk.c:110
			hammer_sync_scan2 Uses vnode at hammer_ondisk.c:1692
			vp Types vnode at hammer_ondisk.c:1750
[-] buf2.h (1)
	[-] buf2.h (1)
		hammer_ondisk.c Includes buf2.h at hammer_ondisk.c:43
[-] cdefs.h (1)
	[-] Macro: __unused (1)
		hammer_adjust_volume_mode Uses __unused at hammer_ondisk.c:279
[-] fcntl.h (15)
	[-] Macro: FREAD (10)
		hammer_install_volume Uses FREAD at hammer_ondisk.c:164
		hammer_install_volume Uses FREAD at hammer_ondisk.c:164
		hammer_install_volume Uses FREAD at hammer_ondisk.c:267
		hammer_install_volume Uses FREAD at hammer_ondisk.c:267
		hammer_adjust_volume_mode Uses FREAD at hammer_ondisk.c:285
		hammer_adjust_volume_mode Uses FREAD at hammer_ondisk.c:286
		hammer_adjust_volume_mode Uses FREAD at hammer_ondisk.c:289
		hammer_adjust_volume_mode Uses FREAD at hammer_ondisk.c:290
		hammer_unload_volume Uses FREAD at hammer_ondisk.c:376
		hammer_unload_volume Uses FREAD at hammer_ondisk.c:385
	[-] Macro: FWRITE (5)
		hammer_install_volume Uses FWRITE at hammer_ondisk.c:164
		hammer_install_volume Uses FWRITE at hammer_ondisk.c:267
		hammer_adjust_volume_mode Uses FWRITE at hammer_ondisk.c:286
		hammer_adjust_volume_mode Uses FWRITE at hammer_ondisk.c:289
		hammer_unload_volume Uses FWRITE at hammer_ondisk.c:385
[-] kern_slaballoc.c (10)
	[-] Function: kfree (6)
		hammer_free_volume Calls kfree at hammer_ondisk.c:406
		hammer_free_volume Calls kfree at hammer_ondisk.c:414
		hammer_get_buffer Calls kfree at hammer_ondisk.c:735
		hammer_rel_buffer Calls kfree at hammer_ondisk.c:1098
		hammer_get_node Calls kfree at hammer_ondisk.c:1230
		hammer_flush_node Calls kfree at hammer_ondisk.c:1560
	[-] Function: kmalloc (3)
		hammer_install_volume Calls kmalloc at hammer_ondisk.c:130
		hammer_get_buffer Calls kmalloc at hammer_ondisk.c:715
		hammer_get_node Calls kmalloc at hammer_ondisk.c:1223
	[-] Function: kstrdup (1)
		hammer_install_volume Calls kstrdup at hammer_ondisk.c:131
[-] kern_uuid.c (1)
	[-] Function: kuuid_compare (1)
		hammer_install_volume Calls kuuid_compare at hammer_ondisk.c:217
[-] lock.h (10)
	[-] Macro: LK_EXCLUSIVE (5)
		hammer_install_volume Uses LK_EXCLUSIVE at hammer_ondisk.c:160
		hammer_install_volume Uses LK_EXCLUSIVE at hammer_ondisk.c:266
		hammer_adjust_volume_mode Uses LK_EXCLUSIVE at hammer_ondisk.c:282
		hammer_unload_volume Uses LK_EXCLUSIVE at hammer_ondisk.c:374
		hammer_unload_volume Uses LK_EXCLUSIVE at hammer_ondisk.c:383
	[-] Macro: LK_RETRY (5)
		hammer_install_volume Uses LK_RETRY at hammer_ondisk.c:160
		hammer_install_volume Uses LK_RETRY at hammer_ondisk.c:266
		hammer_adjust_volume_mode Uses LK_RETRY at hammer_ondisk.c:282
		hammer_unload_volume Uses LK_RETRY at hammer_ondisk.c:374
		hammer_unload_volume Uses LK_RETRY at hammer_ondisk.c:383
[-] lwkt_token.c (8)
	[-] Function: lwkt_gettoken (4)
		hammer_get_root_volume Calls lwkt_gettoken at hammer_ondisk.c:484
		hammer_rel_volume Calls lwkt_gettoken at hammer_ondisk.c:534
		hammer_get_buffer Calls lwkt_gettoken at hammer_ondisk.c:650
		hammer_ref_buffer Calls lwkt_gettoken at hammer_ondisk.c:1009
	[-] Function: lwkt_reltoken (4)
		hammer_get_root_volume Calls lwkt_reltoken at hammer_ondisk.c:486
		hammer_rel_volume Calls lwkt_reltoken at hammer_ondisk.c:537
		hammer_get_buffer Calls lwkt_reltoken at hammer_ondisk.c:657
		hammer_ref_buffer Calls lwkt_reltoken at hammer_ondisk.c:1015
[-] malloc.h (8)
	[-] Macro: M_USE_RESERVE (2)
		hammer_get_buffer Uses M_USE_RESERVE at hammer_ondisk.c:716
		hammer_get_node Uses M_USE_RESERVE at hammer_ondisk.c:1223
	[-] Macro: M_WAITOK (3)
		hammer_install_volume Uses M_WAITOK at hammer_ondisk.c:130
		hammer_get_buffer Uses M_WAITOK at hammer_ondisk.c:716
		hammer_get_node Uses M_WAITOK at hammer_ondisk.c:1223
	[-] Macro: M_ZERO (3)
		hammer_install_volume Uses M_ZERO at hammer_ondisk.c:130
		hammer_get_buffer Uses M_ZERO at hammer_ondisk.c:716
		hammer_get_node Uses M_ZERO at hammer_ondisk.c:1223
[-] memset.c (1)
	[-] Function: bzero (1)
		hammer_alloc_btree Calls bzero at hammer_ondisk.c:1615
[-] mount.h (7)
	[-] Macro: MNT_LAZY (1)
		hammer_sync_hmp Uses MNT_LAZY at hammer_ondisk.c:1730
	[-] Macro: MNT_NOWAIT (1)
		hammer_sync_scan2 Uses MNT_NOWAIT at hammer_ondisk.c:1768
	[-] Macro: MNT_RDONLY (2)
		hammer_install_volume Uses MNT_RDONLY at hammer_ondisk.c:124
		hammer_unload_volume Uses MNT_RDONLY at hammer_ondisk.c:307
	[-] Macro: MNT_WAIT (3)
		hammer_queue_inodes_flusher Uses MNT_WAIT at hammer_ondisk.c:1704
		hammer_sync_hmp Uses MNT_WAIT at hammer_ondisk.c:1736
		hammer_sync_hmp Uses MNT_WAIT at hammer_ondisk.c:1739
[-] nlookup.h (5)
	[-] Struct: nlookupdata (3)
		[-] Object: nl_cred (1)
			hammer_install_volume Uses nl_cred at hammer_ondisk.c:145
		[-] Object: nl_nch (1)
			hammer_install_volume Addr Uses nl_nch at hammer_ondisk.c:145
		[-] Struct: nlookupdata (1)
			nd Types nlookupdata at hammer_ondisk.c:116
	[-] Macro: NLC_FOLLOW (1)
		hammer_install_volume Uses NLC_FOLLOW at hammer_ondisk.c:141
	[-] nlookup.h (1)
		hammer_ondisk.c Includes nlookup.h at hammer_ondisk.c:42
[-] os.c (2)
	[-] Function: bcopy (2)
		hammer_install_volume Calls bcopy at hammer_ondisk.c:196
		hammer_unload_volume Calls bcopy at hammer_ondisk.c:320
[-] queue.h (14)
	[-] Macro: TAILQ_EMPTY (2)
		hammer_rel_buffer Uses TAILQ_EMPTY at hammer_ondisk.c:1086
		hammer_uncache_node Uses TAILQ_EMPTY at hammer_ondisk.c:1502
	[-] Macro: TAILQ_FIRST (2)
		hammer_flush_node Uses TAILQ_FIRST at hammer_ondisk.c:1526
		hammer_flush_buffer_nodes Uses TAILQ_FIRST at hammer_ondisk.c:1576
	[-] Macro: TAILQ_INIT (3)
		hammer_get_buffer Uses TAILQ_INIT at hammer_ondisk.c:723
		hammer_get_node Uses TAILQ_INIT at hammer_ondisk.c:1226
		hammer_get_node Uses TAILQ_INIT at hammer_ondisk.c:1227
	[-] Macro: TAILQ_INSERT_TAIL (3)
		hammer_load_node Uses TAILQ_INSERT_TAIL at hammer_ondisk.c:1291
		hammer_load_node Uses TAILQ_INSERT_TAIL at hammer_ondisk.c:1300
		hammer_cache_node Uses TAILQ_INSERT_TAIL at hammer_ondisk.c:1491
	[-] Macro: TAILQ_REMOVE (4)
		hammer_uncache_node Uses TAILQ_REMOVE at hammer_ondisk.c:1500
		hammer_flush_node Uses TAILQ_REMOVE at hammer_ondisk.c:1527
		hammer_flush_node Uses TAILQ_REMOVE at hammer_ondisk.c:1541
		hammer_flush_buffer_nodes Uses TAILQ_REMOVE at hammer_ondisk.c:1588
[-] quotacheck.c (2)
	[-] Function: bread (2)
		hammer_install_volume Calls bread at hammer_ondisk.c:180
		hammer_unload_volume Calls bread at hammer_ondisk.c:315
[-] subr_prf.c (4)
	[-] Function: kprintf (3)
		hammer_install_volume Calls kprintf at hammer_ondisk.c:202
		hammer_install_volume Calls kprintf at hammer_ondisk.c:204
		hammer_install_volume Calls kprintf at hammer_ondisk.c:206
	[-] Function: krateprintf (1)
		hammer_del_buffers Calls krateprintf at hammer_ondisk.c:856
[-] tree.h (20)
	[-] Macro: RB_EMPTY (2)
		hammer_install_volume Uses RB_EMPTY at hammer_ondisk.c:215
		hammer_sync_scan2 Uses RB_EMPTY at hammer_ondisk.c:1764
	[-] Macro: RB_GENERATE2 (3)
		hammer_ondisk.c Uses RB_GENERATE2 at hammer_ondisk.c:88
		hammer_ondisk.c Uses RB_GENERATE2 at hammer_ondisk.c:90
		hammer_ondisk.c Uses RB_GENERATE2 at hammer_ondisk.c:92
	[-] Macro: RB_INSERT (3)
		hammer_install_volume Uses RB_INSERT at hammer_ondisk.c:227
		hammer_get_buffer Uses RB_INSERT at hammer_ondisk.c:729
		hammer_get_node Uses RB_INSERT at hammer_ondisk.c:1228
	[-] Macro: RB_LOOKUP (7)
		hammer_get_volume Uses RB_LOOKUP at hammer_ondisk.c:428
		hammer_mountcheck_volumes Uses RB_LOOKUP at hammer_ondisk.c:551
		hammer_get_buffer Uses RB_LOOKUP at hammer_ondisk.c:612
		hammer_get_buffer Uses RB_LOOKUP at hammer_ondisk.c:670
		hammer_sync_buffers Uses RB_LOOKUP at hammer_ondisk.c:779
		hammer_del_buffers Uses RB_LOOKUP at hammer_ondisk.c:827
		hammer_get_node Uses RB_LOOKUP at hammer_ondisk.c:1220
	[-] Macro: RB_REMOVE (5)
		hammer_unload_volume Uses RB_REMOVE at hammer_ondisk.c:393
		hammer_get_buffer Uses RB_REMOVE at hammer_ondisk.c:652
		hammer_ref_buffer Uses RB_REMOVE at hammer_ondisk.c:1011
		hammer_rel_buffer Uses RB_REMOVE at hammer_ondisk.c:1078
		hammer_flush_node Uses RB_REMOVE at hammer_ondisk.c:1538
[-] ucred.h (6)
	[-] Struct: ucred (3)
		[-] Struct: ucred (3)
			hammer_install_volume Casts ucred at hammer_ondisk.c:165
			hammer_adjust_volume_mode Casts ucred at hammer_ondisk.c:285
			hammer_adjust_volume_mode Casts ucred at hammer_ondisk.c:289
	[-] Macro: FSCRED (3)
		hammer_install_volume Uses FSCRED at hammer_ondisk.c:165
		hammer_adjust_volume_mode Uses FSCRED at hammer_ondisk.c:285
		hammer_adjust_volume_mode Uses FSCRED at hammer_ondisk.c:289
[-] utilities.c (1)
	[-] Function: bwrite (1)
		hammer_unload_volume Calls bwrite at hammer_ondisk.c:321
[-] vfs_cache.c (1)
	[-] Function: cache_vref (1)
		hammer_install_volume Calls cache_vref at hammer_ondisk.c:145
[-] vfs_lock.c (1)
	[-] Function: vrele (1)
		hammer_free_volume Calls vrele at hammer_ondisk.c:410
[-] vfs_mount.c (3)
	[-] Macro: VMSC_ONEPASS (3)
		hammer_queue_inodes_flusher Uses VMSC_ONEPASS at hammer_ondisk.c:1705
		hammer_queue_inodes_flusher Uses VMSC_ONEPASS at hammer_ondisk.c:1708
		hammer_sync_hmp Uses VMSC_ONEPASS at hammer_ondisk.c:1731
[-] vfs_nlookup.c (3)
	[-] Function: nlookup (1)
		hammer_install_volume Calls nlookup at hammer_ondisk.c:143
	[-] Function: nlookup_done (1)
		hammer_install_volume Calls nlookup_done at hammer_ondisk.c:146
	[-] Function: nlookup_init (1)
		hammer_install_volume Calls nlookup_init at hammer_ondisk.c:141
[-] vfs_subr.c (13)
	[-] Function: vcount (1)
		hammer_install_volume Calls vcount at hammer_ondisk.c:157
	[-] Function: vfs_mountedon (1)
		hammer_install_volume Calls vfs_mountedon at hammer_ondisk.c:154
	[-] Function: vinvalbuf (3)
		hammer_install_volume Calls vinvalbuf at hammer_ondisk.c:161
		hammer_unload_volume Calls vinvalbuf at hammer_ondisk.c:375
		hammer_unload_volume Calls vinvalbuf at hammer_ondisk.c:384
	[-] Function: vn_isdisk (1)
		hammer_install_volume Calls vn_isdisk at hammer_ondisk.c:153
	[-] Macro: V_SAVE (2)
		hammer_install_volume Uses V_SAVE at hammer_ondisk.c:161
		hammer_unload_volume Uses V_SAVE at hammer_ondisk.c:384
	[-] Macro: VMSC_GETVP (3)
		hammer_queue_inodes_flusher Uses VMSC_GETVP at hammer_ondisk.c:1705
		hammer_queue_inodes_flusher Uses VMSC_GETVP at hammer_ondisk.c:1708
		hammer_sync_hmp Uses VMSC_GETVP at hammer_ondisk.c:1729
	[-] Macro: VMSC_NOWAIT (2)
		hammer_queue_inodes_flusher Uses VMSC_NOWAIT at hammer_ondisk.c:1708
		hammer_sync_hmp Uses VMSC_NOWAIT at hammer_ondisk.c:1734
[-] vfs_sync.c (6)
	[-] Function: vclrisdirty (2)
		hammer_sync_scan2 Calls vclrisdirty at hammer_ondisk.c:1760
		hammer_sync_scan2 Calls vclrisdirty at hammer_ondisk.c:1765
	[-] Function: vsyncscan (4)
		hammer_queue_inodes_flusher Calls vsyncscan at hammer_ondisk.c:1705
		hammer_queue_inodes_flusher Calls vsyncscan at hammer_ondisk.c:1708
		hammer_sync_hmp Calls vsyncscan at hammer_ondisk.c:1734
		hammer_sync_hmp Calls vsyncscan at hammer_ondisk.c:1737
[-] vfs_vnops.c (10)
	[-] Function: vn_lock (5)
		hammer_install_volume Calls vn_lock at hammer_ondisk.c:160
		hammer_install_volume Calls vn_lock at hammer_ondisk.c:266
		hammer_adjust_volume_mode Calls vn_lock at hammer_ondisk.c:282
		hammer_unload_volume Calls vn_lock at hammer_ondisk.c:374
		hammer_unload_volume Calls vn_lock at hammer_ondisk.c:383
	[-] Function: vn_unlock (5)
		hammer_install_volume Calls vn_unlock at hammer_ondisk.c:167
		hammer_install_volume Calls vn_unlock at hammer_ondisk.c:268
		hammer_adjust_volume_mode Calls vn_unlock at hammer_ondisk.c:292
		hammer_unload_volume Calls vn_unlock at hammer_ondisk.c:377
		hammer_unload_volume Calls vn_unlock at hammer_ondisk.c:386



---



hammer_pfs.c (12)



[-] _null.h (6)
	[-] Macro: NULL (6)
		hammer_ioc_scan_pseudofs Uses NULL at hammer_pfs.c:339
		hammer_ioc_scan_pseudofs Uses NULL at hammer_pfs.c:343
		hammer_pfs_rollback Uses NULL at hammer_pfs.c:430
		hammer_pfs_rollback Uses NULL at hammer_pfs.c:430
		hammer_pfs_delete_at_cursor Uses NULL at hammer_pfs.c:523
		hammer_pfs_delete_at_cursor Uses NULL at hammer_pfs.c:528
[-] memset.c (2)
	[-] Function: bzero (2)
		hammer_pfs_rollback Calls bzero at hammer_pfs.c:419
		hammer_pfs_rollback Calls bzero at hammer_pfs.c:420
[-] param.h (1)
	[-] Macro: PCATCH (1)
		hammer_ioc_wait_pseudofs Uses PCATCH at hammer_pfs.c:301
[-] ucred.h (1)
	[-] Struct: ucred (1)
		[-] Struct: ucred (1)
			cred Types ucred at hammer_pfs.c:100
[-] uwrapper.c (2)
	[-] Function: copyin (2)
		hammer_ioc_set_pseudofs Calls copyin at hammer_pfs.c:118
		hammer_ioc_wait_pseudofs Calls copyin at hammer_pfs.c:288



---



hammer_prune.c (7)



[-] _null.h (3)
	[-] Macro: NULL (3)
		hammer_ioc_prune Uses NULL at hammer_prune.c:114
		hammer_ioc_prune Uses NULL at hammer_prune.c:114
		prune_check_nlinks Uses NULL at hammer_prune.c:335
[-] kern_slaballoc.c (2)
	[-] Function: kfree (1)
		hammer_ioc_prune Calls kfree at hammer_prune.c:263
	[-] Function: kmalloc (1)
		hammer_ioc_prune Calls kmalloc at hammer_prune.c:103
[-] malloc.h (1)
	[-] Macro: M_WAITOK (1)
		hammer_ioc_prune Uses M_WAITOK at hammer_prune.c:103
[-] uwrapper.c (1)
	[-] Function: copyin (1)
		hammer_ioc_prune Calls copyin at hammer_prune.c:104



---



hammer_rebalance.c (21)



[-] _null.h (4)
	[-] Macro: NULL (4)
		hammer_ioc_rebalance Uses NULL at hammer_rebalance.c:104
		hammer_ioc_rebalance Uses NULL at hammer_rebalance.c:104
		rebalance_node Uses NULL at hammer_rebalance.c:310
		rebalance_node Uses NULL at hammer_rebalance.c:494
[-] queue.h (10)
	[-] Macro: TAILQ_FIRST (4)
		rebalance_node Uses TAILQ_FIRST at hammer_rebalance.c:310
		rebalance_node Uses TAILQ_FIRST at hammer_rebalance.c:312
		rebalance_node Uses TAILQ_FIRST at hammer_rebalance.c:363
		rebalance_node Uses TAILQ_FIRST at hammer_rebalance.c:370
	[-] Macro: TAILQ_FOREACH (2)
		rebalance_node Uses TAILQ_FOREACH at hammer_rebalance.c:327
		rebalance_node Uses TAILQ_FOREACH at hammer_rebalance.c:367
	[-] Macro: TAILQ_NEXT (4)
		rebalance_node Uses TAILQ_NEXT at hammer_rebalance.c:384
		rebalance_node Uses TAILQ_NEXT at hammer_rebalance.c:399
		rebalance_node Uses TAILQ_NEXT at hammer_rebalance.c:456
		rebalance_node Uses TAILQ_NEXT at hammer_rebalance.c:494
[-] subr_prf.c (5)
	[-] Function: kprintf (5)
		rebalance_closeout Calls kprintf at hammer_rebalance.c:545
		rebalance_closeout Calls kprintf at hammer_rebalance.c:576
		rebalance_closeout Calls kprintf at hammer_rebalance.c:579
		rebalance_closeout Calls kprintf at hammer_rebalance.c:596
		rebalance_closeout Calls kprintf at hammer_rebalance.c:601
[-] vm_page.c (2)
	[-] Function: vm_test_nominal (1)
		hammer_ioc_rebalance Calls vm_test_nominal at hammer_rebalance.c:134
	[-] Function: vm_wait_nominal (1)
		hammer_ioc_rebalance Calls vm_wait_nominal at hammer_rebalance.c:136



---



hammer_reblock.c (14)



[-] _null.h (9)
	[-] Macro: NULL (9)
		hammer_ioc_reblock Uses NULL at hammer_reblock.c:108
		hammer_ioc_reblock Uses NULL at hammer_reblock.c:108
		hammer_ioc_reblock Uses NULL at hammer_reblock.c:184
		hammer_reblock_helper Uses NULL at hammer_reblock.c:424
		hammer_reblock_data Uses NULL at hammer_reblock.c:457
		hammer_reblock_leaf_node Uses NULL at hammer_reblock.c:536
		hammer_reblock_int_node Uses NULL at hammer_reblock.c:585
		hammer_reblock_int_node Uses NULL at hammer_reblock.c:596
		hammer_reblock_int_node Uses NULL at hammer_reblock.c:626
[-] kern_iosched.c (1)
	[-] Function: bwillwrite (1)
		hammer_ioc_reblock Calls bwillwrite at hammer_reblock.c:225
[-] os.c (2)
	[-] Function: bcopy (2)
		hammer_reblock_data Calls bcopy at hammer_reblock.c:487
		hammer_move_node Calls bcopy at hammer_reblock.c:641
[-] vfs_bio.c (1)
	[-] Function: bd_heatup (1)
		hammer_ioc_reblock Calls bd_heatup at hammer_reblock.c:223
[-] vm_page.c (1)
	[-] Function: vm_wait_nominal (1)
		hammer_ioc_reblock Calls vm_wait_nominal at hammer_reblock.c:228



---



hammer_recover.c (71)



[-] _null.h (29)
	[-] Macro: NULL (29)
		hammer_recover_stage1 Uses NULL at hammer_recover.c:227
		hammer_recover_stage1 Uses NULL at hammer_recover.c:444
		hammer_recover_stage1 Uses NULL at hammer_recover.c:464
		hammer_recover_stage1 Uses NULL at hammer_recover.c:482
		hammer_recover_stage2 Uses NULL at hammer_recover.c:566
		hammer_recover_stage2 Uses NULL at hammer_recover.c:721
		hammer_recover_stage2 Uses NULL at hammer_recover.c:731
		hammer_recover_stage2 Uses NULL at hammer_recover.c:733
		hammer_recover_scan_rev Uses NULL at hammer_recover.c:796
		hammer_recover_scan_rev Uses NULL at hammer_recover.c:804
		hammer_recover_scan_rev Uses NULL at hammer_recover.c:812
		hammer_recover_scan_fwd Uses NULL at hammer_recover.c:849
		hammer_recover_scan_fwd Uses NULL at hammer_recover.c:857
		hammer_recover_undo Uses NULL at hammer_recover.c:1082
		hammer_recover_undo Uses NULL at hammer_recover.c:1087
		hammer_recover_undo Uses NULL at hammer_recover.c:1110
		hammer_recover_undo Uses NULL at hammer_recover.c:1115
		hammer_recover_redo_run Uses NULL at hammer_recover.c:1285
		hammer_recover_redo_exec Uses NULL at hammer_recover.c:1302
		hammer_recover_redo_exec Uses NULL at hammer_recover.c:1307
		hammer_recover_redo_exec Uses NULL at hammer_recover.c:1310
		hammer_recover_redo_exec Uses NULL at hammer_recover.c:1324
		hammer_recover_redo_exec Uses NULL at hammer_recover.c:1335
		hammer_recover_redo_exec Uses NULL at hammer_recover.c:1342
		hammer_recover_flush_buffers Uses NULL at hammer_recover.c:1436
		hammer_recover_flush_buffers Uses NULL at hammer_recover.c:1439
		hammer_recover_flush_buffers Uses NULL at hammer_recover.c:1447
		hammer_recover_flush_buffers Uses NULL at hammer_recover.c:1450
		hammer_recover_flush_volume_callback Uses NULL at hammer_recover.c:1487
[-] buf.h (1)
	[-] Struct: vnode (1)
		[-] Struct: vnode (1)
			vp Types vnode at hammer_recover.c:1302
[-] fcntl.h (4)
	[-] Macro: FREAD (2)
		hammer_recover_redo_exec Uses FREAD at hammer_recover.c:1324
		hammer_recover_redo_exec Uses FREAD at hammer_recover.c:1342
	[-] Macro: FWRITE (2)
		hammer_recover_redo_exec Uses FWRITE at hammer_recover.c:1324
		hammer_recover_redo_exec Uses FWRITE at hammer_recover.c:1342
[-] kern_slaballoc.c (6)
	[-] Function: kfree (4)
		hammer_recover_stage2 Calls kfree at hammer_recover.c:735
		hammer_recover_stage2 Calls kfree at hammer_recover.c:737
		hammer_recover_redo_rec Calls kfree at hammer_recover.c:1185
		hammer_recover_redo_run Calls kfree at hammer_recover.c:1288
	[-] Function: kmalloc (2)
		hammer_recover_redo_rec Calls kmalloc at hammer_recover.c:1177
		hammer_recover_redo_rec Calls kmalloc at hammer_recover.c:1202
[-] lock.h (2)
	[-] Macro: LK_EXCLUSIVE (1)
		hammer_recover_redo_exec Uses LK_EXCLUSIVE at hammer_recover.c:1336
	[-] Macro: LK_RETRY (1)
		hammer_recover_redo_exec Uses LK_RETRY at hammer_recover.c:1336
[-] malloc.h (4)
	[-] Macro: M_WAITOK (2)
		hammer_recover_redo_rec Uses M_WAITOK at hammer_recover.c:1177
		hammer_recover_redo_rec Uses M_WAITOK at hammer_recover.c:1202
	[-] Macro: M_ZERO (2)
		hammer_recover_redo_rec Uses M_ZERO at hammer_recover.c:1177
		hammer_recover_redo_rec Uses M_ZERO at hammer_recover.c:1202
[-] memset.c (2)
	[-] Function: bzero (2)
		hammer_recover_redo_run Calls bzero at hammer_recover.c:1235
		hammer_recover_redo_run Calls bzero at hammer_recover.c:1277
[-] mman.h (1)
	[-] Typedef: size_t (1)
		_hammer_check_signature Casts size_t at hammer_recover.c:902
[-] os.c (1)
	[-] Function: bcopy (1)
		hammer_recover_copy_undo Calls bcopy at hammer_recover.c:1154
[-] spinlock.h (1)
	[-] Struct: spinlock (1)
		[-] Struct: spinlock (1)
			rbh_spin Types spinlock at hammer_recover.c:157
[-] tree.h (14)
	[-] Macro: RB_ENTRY (1)
		hammer_rterm Uses RB_ENTRY at hammer_recover.c:147
	[-] Macro: RB_FIND (2)
		hammer_recover_redo_run Uses RB_FIND at hammer_recover.c:1243
		hammer_recover_redo_run Uses RB_FIND at hammer_recover.c:1283
	[-] Macro: RB_GENERATE (1)
		hammer_recover.c Uses RB_GENERATE at hammer_recover.c:188
	[-] Macro: RB_HEAD (1)
		hammer_recover.c Uses RB_HEAD at hammer_recover.c:157
	[-] Macro: RB_INIT (1)
		hammer_recover_stage2 Uses RB_INIT at hammer_recover.c:539
	[-] Macro: RB_INSERT (1)
		hammer_recover_redo_rec Uses RB_INSERT at hammer_recover.c:1183
	[-] Macro: RB_PROTOTYPE (1)
		hammer_recover.c Uses RB_PROTOTYPE at hammer_recover.c:158
	[-] Macro: RB_REMOVE (1)
		hammer_recover_stage2 Uses RB_REMOVE at hammer_recover.c:732
	[-] Macro: RB_ROOT (1)
		hammer_recover_stage2 Uses RB_ROOT at hammer_recover.c:731
	[-] Macro: RB_SCAN (4)
		hammer_recover_flush_buffers Uses RB_SCAN at hammer_recover.c:1436
		hammer_recover_flush_buffers Uses RB_SCAN at hammer_recover.c:1439
		hammer_recover_flush_buffers Uses RB_SCAN at hammer_recover.c:1447
		hammer_recover_flush_buffers Uses RB_SCAN at hammer_recover.c:1450
[-] vfs_lock.c (1)
	[-] Function: vput (1)
		hammer_recover_redo_exec Calls vput at hammer_recover.c:1354
[-] vfs_vnops.c (3)
	[-] Function: vn_lock (1)
		hammer_recover_redo_exec Calls vn_lock at hammer_recover.c:1336
	[-] Function: vn_rdwr (1)
		hammer_recover_redo_exec Calls vn_rdwr at hammer_recover.c:1332
	[-] Function: vn_unlock (1)
		hammer_recover_redo_exec Calls vn_unlock at hammer_recover.c:1331
[-] vfscache.h (2)
	[-] Struct: vattr (2)
		[-] Object: va_size (1)
			hammer_recover_redo_exec Sets va_size at hammer_recover.c:1346
		[-] Struct: vattr (1)
			va Types vattr at hammer_recover.c:1300



---



hammer_redo.c (13)



[-] _null.h (7)
	[-] Macro: NULL (7)
		hammer_generate_redo Uses NULL at hammer_redo.c:67
		hammer_generate_redo Uses NULL at hammer_redo.c:86
		hammer_generate_redo Uses NULL at hammer_redo.c:119
		hammer_generate_redo Uses NULL at hammer_redo.c:199
		hammer_generate_redo_sync Uses NULL at hammer_redo.c:317
		hammer_generate_redo_sync Uses NULL at hammer_redo.c:331
		hammer_generate_redo_sync Uses NULL at hammer_redo.c:332
[-] os.c (1)
	[-] Function: bcopy (1)
		hammer_generate_redo Calls bcopy at hammer_redo.c:226
[-] tree.h (5)
	[-] Macro: RB_FIRST (1)
		hammer_generate_redo_sync Uses RB_FIRST at hammer_redo.c:320
	[-] Macro: RB_GENERATE2 (1)
		hammer_redo.c Uses RB_GENERATE2 at hammer_redo.c:43
	[-] Macro: RB_INSERT (2)
		hammer_generate_redo Uses RB_INSERT at hammer_redo.c:180
		hammer_redo_fifo_end_flush Uses RB_INSERT at hammer_redo.c:366
	[-] Macro: RB_REMOVE (1)
		hammer_redo_fifo_end_flush Uses RB_REMOVE at hammer_redo.c:359



---



hammer_signal.c (4)



[-] lwkt_thread.c (1)
	[-] Function: lwkt_user_yield (1)
		hammer_signal_check Calls lwkt_user_yield at hammer_signal.c:54
[-] signal2.h (3)
	[-] Function: __cursig (1)
		hammer_signal_check Calls __cursig at hammer_signal.c:59
	[-] Macro: CURSIG_NOBLOCK (1)
		hammer_signal_check Uses CURSIG_NOBLOCK at hammer_signal.c:59
	[-] signal2.h (1)
		hammer_signal.c Includes signal2.h at hammer_signal.c:40



---



hammer_subs.c (80)



[-] _null.h (2)
	[-] Macro: NULL (2)
		hammer_lock_downgrade Uses NULL at hammer_subs.c:257
		hammer_unlock Uses NULL at hammer_subs.c:292
[-] _timespec.h (6)
	[-] Struct: timespec (6)
		[-] Object: tv_nsec (2)
			hammer_time_to_timespec Sets tv_nsec at hammer_subs.c:798
			hammer_timespec_to_time Uses tv_nsec at hammer_subs.c:806
		[-] Object: tv_sec (2)
			hammer_time_to_timespec Sets tv_sec at hammer_subs.c:797
			hammer_timespec_to_time Uses tv_sec at hammer_subs.c:807
		[-] Struct: timespec (2)
			ts Types timespec at hammer_subs.c:795
			ts Types timespec at hammer_subs.c:802
[-] cdefs.h (1)
	[-] Macro: __unused (1)
		hammer_rel_interlock_done Uses __unused at hammer_subs.c:619
[-] defines.h (35)
	[-] Typedef: u_int (35)
		lv Types u_int at hammer_subs.c:44
		nlv Types u_int at hammer_subs.c:45
		lv Types u_int at hammer_subs.c:86
		nlv Types u_int at hammer_subs.c:87
		lv Types u_int at hammer_subs.c:125
		nlv Types u_int at hammer_subs.c:126
		lv Types u_int at hammer_subs.c:162
		nlv Types u_int at hammer_subs.c:163
		lv Types u_int at hammer_subs.c:208
		nlv Types u_int at hammer_subs.c:209
		lv Types u_int at hammer_subs.c:247
		nlv Types u_int at hammer_subs.c:248
		lv Types u_int at hammer_subs.c:274
		nlv Types u_int at hammer_subs.c:275
		lv Types u_int at hammer_subs.c:311
		lv Types u_int at hammer_subs.c:333
		nlv Types u_int at hammer_subs.c:334
		lv Types u_int at hammer_subs.c:364
		nlv Types u_int at hammer_subs.c:365
		lv Types u_int at hammer_subs.c:410
		nlv Types u_int at hammer_subs.c:411
		lv Types u_int at hammer_subs.c:496
		nlv Types u_int at hammer_subs.c:497
		lv Types u_int at hammer_subs.c:522
		nlv Types u_int at hammer_subs.c:523
		lv Types u_int at hammer_subs.c:557
		nlv Types u_int at hammer_subs.c:558
		lv Types u_int at hammer_subs.c:621
		nlv Types u_int at hammer_subs.c:622
		lv Types u_int at hammer_subs.c:651
		nlv Types u_int at hammer_subs.c:652
		lv Types u_int at hammer_subs.c:684
		nlv Types u_int at hammer_subs.c:685
		lv Types u_int at hammer_subs.c:712
		nlv Types u_int at hammer_subs.c:713
[-] dirent.h (9)
	[-] Macro: DT_BLK (1)
		hammer_get_dtype Uses DT_BLK at hammer_subs.c:858
	[-] Macro: DT_CHR (1)
		hammer_get_dtype Uses DT_CHR at hammer_subs.c:856
	[-] Macro: DT_DBF (1)
		hammer_get_dtype Uses DT_DBF at hammer_subs.c:850
	[-] Macro: DT_DIR (1)
		hammer_get_dtype Uses DT_DIR at hammer_subs.c:846
	[-] Macro: DT_FIFO (1)
		hammer_get_dtype Uses DT_FIFO at hammer_subs.c:852
	[-] Macro: DT_LNK (1)
		hammer_get_dtype Uses DT_LNK at hammer_subs.c:860
	[-] Macro: DT_REG (1)
		hammer_get_dtype Uses DT_REG at hammer_subs.c:848
	[-] Macro: DT_SOCK (1)
		hammer_get_dtype Uses DT_SOCK at hammer_subs.c:854
	[-] Macro: DT_UNKNOWN (1)
		hammer_get_dtype Uses DT_UNKNOWN at hammer_subs.c:862
[-] kern_synch.c (5)
	[-] Function: tsleep_interlock (5)
		hammer_lock_ex_ident Calls tsleep_interlock at hammer_subs.c:68
		hammer_lock_sh Calls tsleep_interlock at hammer_subs.c:151
		hammer_ref_interlock Calls tsleep_interlock at hammer_subs.c:465
		hammer_rel_interlock Calls tsleep_interlock at hammer_subs.c:591
		hammer_get_interlock Calls tsleep_interlock at hammer_subs.c:658
[-] memset.c (1)
	[-] Function: bzero (1)
		hammer_guid_to_uuid Calls bzero at hammer_subs.c:790
[-] param.h (5)
	[-] Macro: PINTERLOCKED (5)
		hammer_lock_ex_ident Uses PINTERLOCKED at hammer_subs.c:70
		hammer_lock_sh Uses PINTERLOCKED at hammer_subs.c:153
		hammer_ref_interlock Uses PINTERLOCKED at hammer_subs.c:468
		hammer_rel_interlock Uses PINTERLOCKED at hammer_subs.c:593
		hammer_get_interlock Uses PINTERLOCKED at hammer_subs.c:660
[-] stat.h (2)
	[-] Macro: SF_NOHISTORY (1)
		hammer_nohistory Uses SF_NOHISTORY at hammer_subs.c:901
	[-] Macro: UF_NOHISTORY (1)
		hammer_nohistory Uses UF_NOHISTORY at hammer_subs.c:901
[-] strtoul.c (1)
	[-] Function: strtoul (1)
		hammer_str_to_tid Calls strtoul at hammer_subs.c:1073
[-] thread.h (7)
	[-] Typedef: thread_t (7)
		td Types thread_t at hammer_subs.c:43
		td Types thread_t at hammer_subs.c:84
		td Types thread_t at hammer_subs.c:124
		td Types thread_t at hammer_subs.c:161
		td Types thread_t at hammer_subs.c:207
		__debugvar Types thread_t at hammer_subs.c:246
		__debugvar Types thread_t at hammer_subs.c:273
[-] types.h (4)
	[-] Macro: udev_t (2)
		hammer_subs.c Uses udev_t at hammer_subs.c:1131
		hammer_fsid_to_udev Uses udev_t at hammer_subs.c:1137
	[-] Typedef: dev_t (2)
		hammer_fsid_to_udev Types dev_t at hammer_subs.c:1131
		hammer_fsid_to_udev Casts dev_t at hammer_subs.c:1137
[-] uuid.h (2)
	[-] Struct: uuid (2)
		[-] Object: node (2)
			hammer_to_unix_xid Returns node at hammer_subs.c:784
			hammer_guid_to_uuid Deref Sets node at hammer_subs.c:791



---



hammer_transaction.c (45)



[-] _null.h (11)
	[-] Macro: NULL (11)
		hammer_done_transaction Uses NULL at hammer_transaction.c:126
		hammer_alloc_objid Uses NULL at hammer_transaction.c:192
		hammer_alloc_objid Uses NULL at hammer_transaction.c:201
		hammer_alloc_objid Uses NULL at hammer_transaction.c:219
		hammer_alloc_objid Uses NULL at hammer_transaction.c:249
		hammer_alloc_objid Uses NULL at hammer_transaction.c:251
		hammer_clear_objid Uses NULL at hammer_transaction.c:294
		hammer_clear_objid Uses NULL at hammer_transaction.c:295
		hammer_clear_objid Uses NULL at hammer_transaction.c:296
		hammer_destroy_objid_cache Uses NULL at hammer_transaction.c:307
		hammer_destroy_objid_cache Uses NULL at hammer_transaction.c:310
[-] bsd-misc.h (12)
	[-] Struct: timeval (12)
		[-] Object: tv_sec (6)
			hammer_start_transaction Uses tv_sec at hammer_transaction.c:60
			hammer_start_transaction Uses tv_sec at hammer_transaction.c:61
			hammer_simple_transaction Uses tv_sec at hammer_transaction.c:84
			hammer_simple_transaction Uses tv_sec at hammer_transaction.c:85
			hammer_start_transaction_fls Uses tv_sec at hammer_transaction.c:113
			hammer_start_transaction_fls Uses tv_sec at hammer_transaction.c:114
		[-] Object: tv_usec (3)
			hammer_start_transaction Uses tv_usec at hammer_transaction.c:60
			hammer_simple_transaction Uses tv_usec at hammer_transaction.c:84
			hammer_start_transaction_fls Uses tv_usec at hammer_transaction.c:113
		[-] Struct: timeval (3)
			tv Types timeval at hammer_transaction.c:48
			tv Types timeval at hammer_transaction.c:72
			tv Types timeval at hammer_transaction.c:99
[-] kern_clock.c (3)
	[-] Function: getmicrotime (3)
		hammer_start_transaction Calls getmicrotime at hammer_transaction.c:59
		hammer_simple_transaction Calls getmicrotime at hammer_transaction.c:83
		hammer_start_transaction_fls Calls getmicrotime at hammer_transaction.c:112
[-] kern_slaballoc.c (5)
	[-] Function: kfree (4)
		hammer_alloc_objid Calls kfree at hammer_transaction.c:208
		hammer_alloc_objid Calls kfree at hammer_transaction.c:224
		hammer_alloc_objid Calls kfree at hammer_transaction.c:252
		hammer_destroy_objid_cache Calls kfree at hammer_transaction.c:311
	[-] Function: kmalloc (1)
		hammer_alloc_objid Calls kmalloc at hammer_transaction.c:194
[-] lwkt_token.c (2)
	[-] Function: lwkt_gettoken (1)
		hammer_done_transaction Calls lwkt_gettoken at hammer_transaction.c:132
	[-] Function: lwkt_reltoken (1)
		hammer_done_transaction Calls lwkt_reltoken at hammer_transaction.c:134
[-] malloc.h (2)
	[-] Macro: M_WAITOK (1)
		hammer_alloc_objid Uses M_WAITOK at hammer_transaction.c:195
	[-] Macro: M_ZERO (1)
		hammer_alloc_objid Uses M_ZERO at hammer_transaction.c:195
[-] memset.c (1)
	[-] Function: bzero (1)
		hammer_start_transaction_fls Calls bzero at hammer_transaction.c:102
[-] queue.h (9)
	[-] Macro: TAILQ_FIRST (2)
		hammer_alloc_objid Uses TAILQ_FIRST at hammer_transaction.c:217
		hammer_destroy_objid_cache Uses TAILQ_FIRST at hammer_transaction.c:307
	[-] Macro: TAILQ_INSERT_HEAD (1)
		hammer_clear_objid Uses TAILQ_INSERT_HEAD at hammer_transaction.c:298
	[-] Macro: TAILQ_INSERT_TAIL (2)
		hammer_alloc_objid Uses TAILQ_INSERT_TAIL at hammer_transaction.c:202
		hammer_alloc_objid Uses TAILQ_INSERT_TAIL at hammer_transaction.c:254
	[-] Macro: TAILQ_REMOVE (4)
		hammer_alloc_objid Uses TAILQ_REMOVE at hammer_transaction.c:221
		hammer_alloc_objid Uses TAILQ_REMOVE at hammer_transaction.c:231
		hammer_clear_objid Uses TAILQ_REMOVE at hammer_transaction.c:297
		hammer_destroy_objid_cache Uses TAILQ_REMOVE at hammer_transaction.c:308



---



hammer_undo.c (20)



[-] _null.h (7)
	[-] Macro: NULL (7)
		hammer_generate_undo Uses NULL at hammer_undo.c:100
		hammer_generate_undo Uses NULL at hammer_undo.c:132
		hammer_generate_undo Uses NULL at hammer_undo.c:165
		hammer_upgrade_undo_4 Uses NULL at hammer_undo.c:346
		hammer_upgrade_undo_4 Uses NULL at hammer_undo.c:360
		hammer_upgrade_undo_4 Uses NULL at hammer_undo.c:385
		hammer_enter_undo_history Uses NULL at hammer_undo.c:458
[-] memset.c (1)
	[-] Function: bzero (1)
		hammer_format_undo Calls bzero at hammer_undo.c:312
[-] os.c (1)
	[-] Function: bcopy (1)
		hammer_generate_undo Calls bcopy at hammer_undo.c:234
[-] queue.h (6)
	[-] Macro: TAILQ_FIRST (1)
		hammer_enter_undo_history Uses TAILQ_FIRST at hammer_undo.c:450
	[-] Macro: TAILQ_INIT (1)
		hammer_clear_undo_history Uses TAILQ_INIT at hammer_undo.c:466
	[-] Macro: TAILQ_INSERT_TAIL (2)
		hammer_enter_undo_history Uses TAILQ_INSERT_TAIL at hammer_undo.c:441
		hammer_enter_undo_history Uses TAILQ_INSERT_TAIL at hammer_undo.c:456
	[-] Macro: TAILQ_REMOVE (2)
		hammer_enter_undo_history Uses TAILQ_REMOVE at hammer_undo.c:440
		hammer_enter_undo_history Uses TAILQ_REMOVE at hammer_undo.c:451
[-] tree.h (5)
	[-] Macro: RB_GENERATE2 (1)
		hammer_undo.c Uses RB_GENERATE2 at hammer_undo.c:51
	[-] Macro: RB_INIT (1)
		hammer_clear_undo_history Uses RB_INIT at hammer_undo.c:465
	[-] Macro: RB_INSERT (1)
		hammer_enter_undo_history Uses RB_INSERT at hammer_undo.c:457
	[-] Macro: RB_LOOKUP (1)
		hammer_enter_undo_history Uses RB_LOOKUP at hammer_undo.c:438
	[-] Macro: RB_REMOVE (1)
		hammer_enter_undo_history Uses RB_REMOVE at hammer_undo.c:452



---



hammer_vfsops.c (317)



[-] _null.h (30)
	[-] Macro: NULL (30)
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:329
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:336
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:346
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:372
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:376
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:401
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:480
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:491
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:497
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:504
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:540
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:544
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:575
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:578
		hammer_vfs_mount Uses NULL at hammer_vfsops.c:587
		hammer_free_hmp Uses NULL at hammer_vfsops.c:839
		hammer_free_hmp Uses NULL at hammer_vfsops.c:848
		hammer_free_hmp Uses NULL at hammer_vfsops.c:868
		hammer_free_hmp Uses NULL at hammer_vfsops.c:873
		hammer_free_hmp Uses NULL at hammer_vfsops.c:875
		hammer_free_hmp Uses NULL at hammer_vfsops.c:878
		hammer_free_hmp Uses NULL at hammer_vfsops.c:880
		hammer_critical_error Uses NULL at hammer_vfsops.c:905
		hammer_vfs_vget Uses NULL at hammer_vfsops.c:949
		hammer_vfs_vget Uses NULL at hammer_vfsops.c:952
		hammer_vfs_vget Uses NULL at hammer_vfsops.c:953
		hammer_vfs_root Uses NULL at hammer_vfsops.c:974
		hammer_vfs_sync Uses NULL at hammer_vfsops.c:1068
		hammer_vfs_fhtovp Uses NULL at hammer_vfsops.c:1130
		hammer_vfs_fhtovp Uses NULL at hammer_vfsops.c:1136
[-] buf.h (14)
	[-] Struct: vnode (14)
		[-] Struct: vnode (14)
			hammer_vfs_root Uses vnode at hammer_vfsops.c:238
			hammer_vfs_vget Uses vnode at hammer_vfsops.c:244
			hammer_vfs_vget Uses vnode at hammer_vfsops.c:245
			hammer_vfs_fhtovp Uses vnode at hammer_vfsops.c:247
			hammer_vfs_fhtovp Uses vnode at hammer_vfsops.c:248
			hammer_vfs_vptofh Uses vnode at hammer_vfsops.c:249
			rootvp Types vnode at hammer_vfsops.c:328
			devvp Types vnode at hammer_vfsops.c:329
			dvp Types vnode at hammer_vfsops.c:920
			vpp Types vnode at hammer_vfsops.c:921
			vpp Types vnode at hammer_vfsops.c:970
			vp Types vnode at hammer_vfsops.c:1084
			rootvp Types vnode at hammer_vfsops.c:1105
			vpp Types vnode at hammer_vfsops.c:1106
[-] kern_objcache.c (2)
	[-] Function: objcache_get (1)
		hammer_vfs_mount Calls objcache_get at hammer_vfsops.c:537
	[-] Function: objcache_put (1)
		hammer_vfs_mount Calls objcache_put at hammer_vfsops.c:582
[-] kern_slaballoc.c (10)
	[-] Function: kfree (2)
		hammer_free_hmp Calls kfree at hammer_vfsops.c:855
		hammer_free_hmp Calls kfree at hammer_vfsops.c:885
	[-] Function: kmalloc (1)
		hammer_vfs_mount Calls kmalloc at hammer_vfsops.c:402
	[-] Function: kmalloc_create (2)
		hammer_vfs_mount Calls kmalloc_create at hammer_vfsops.c:412
		hammer_vfs_mount Calls kmalloc_create at hammer_vfsops.c:413
	[-] Function: kmalloc_destroy (2)
		hammer_free_hmp Calls kmalloc_destroy at hammer_vfsops.c:882
		hammer_free_hmp Calls kmalloc_destroy at hammer_vfsops.c:883
	[-] Function: kmalloc_limit (2)
		hammer_vfs_init Calls kmalloc_limit at hammer_vfsops.c:293
		hammer_vfs_init Calls kmalloc_limit at hammer_vfsops.c:294
	[-] Function: kmalloc_raise_limit (1)
		hammer_vfs_mount Calls kmalloc_raise_limit at hammer_vfsops.c:415
[-] lwkt_token.c (25)
	[-] Function: lwkt_gettoken (10)
		hammer_vfs_mount Calls lwkt_gettoken at hammer_vfsops.c:475
		hammer_vfs_mount Calls lwkt_gettoken at hammer_vfsops.c:532
		hammer_vfs_unmount Calls lwkt_gettoken at hammer_vfsops.c:797
		hammer_vfs_vget Calls lwkt_gettoken at hammer_vfsops.c:929
		hammer_vfs_statfs Calls lwkt_gettoken at hammer_vfsops.c:988
		hammer_vfs_statvfs Calls lwkt_gettoken at hammer_vfsops.c:1026
		hammer_vfs_sync Calls lwkt_gettoken at hammer_vfsops.c:1067
		hammer_vfs_fhtovp Calls lwkt_gettoken at hammer_vfsops.c:1122
		hammer_vfs_checkexp Calls lwkt_gettoken at hammer_vfsops.c:1151
		hammer_vfs_export Calls lwkt_gettoken at hammer_vfsops.c:1171
	[-] Function: lwkt_reltoken (13)
		hammer_vfs_mount Calls lwkt_reltoken at hammer_vfsops.c:507
		hammer_vfs_mount Calls lwkt_reltoken at hammer_vfsops.c:782
		hammer_vfs_unmount Calls lwkt_reltoken at hammer_vfsops.c:811
		hammer_free_hmp Calls lwkt_reltoken at hammer_vfsops.c:884
		hammer_vfs_vget Calls lwkt_reltoken at hammer_vfsops.c:959
		hammer_vfs_statfs Calls lwkt_reltoken at hammer_vfsops.c:991
		hammer_vfs_statfs Calls lwkt_reltoken at hammer_vfsops.c:1012
		hammer_vfs_statvfs Calls lwkt_reltoken at hammer_vfsops.c:1029
		hammer_vfs_statvfs Calls lwkt_reltoken at hammer_vfsops.c:1049
		hammer_vfs_sync Calls lwkt_reltoken at hammer_vfsops.c:1073
		hammer_vfs_fhtovp Calls lwkt_reltoken at hammer_vfsops.c:1139
		hammer_vfs_checkexp Calls lwkt_reltoken at hammer_vfsops.c:1160
		hammer_vfs_export Calls lwkt_reltoken at hammer_vfsops.c:1181
	[-] Function: lwkt_token_init (2)
		hammer_vfs_mount Calls lwkt_token_init at hammer_vfsops.c:529
		hammer_vfs_mount Calls lwkt_token_init at hammer_vfsops.c:530
[-] malloc.h (5)
	[-] Struct: malloc_type (1)
		[-] Struct: malloc_type (1)
			M_HAMMER Types malloc_type at hammer_vfsops.c:268
	[-] Macro: M_WAITOK (2)
		hammer_vfs_mount Uses M_WAITOK at hammer_vfsops.c:402
		hammer_vfs_mount Uses M_WAITOK at hammer_vfsops.c:537
	[-] Macro: M_ZERO (1)
		hammer_vfs_mount Uses M_ZERO at hammer_vfsops.c:402
	[-] Macro: MALLOC_DEFINE (1)
		hammer_vfsops.c Uses MALLOC_DEFINE at hammer_vfsops.c:268
[-] memset.c (2)
	[-] Function: bzero (2)
		hammer_vfs_mount Calls bzero at hammer_vfsops.c:347
		hammer_vfs_mount Calls bzero at hammer_vfsops.c:763
[-] mman.h (1)
	[-] Typedef: size_t (1)
		size Types size_t at hammer_vfsops.c:764
[-] mount.h (37)
	[-] Struct: export_args (1)
		[-] Struct: export_args (1)
			export Types export_args at hammer_vfsops.c:1166
	[-] Struct: fid (12)
		[-] Object: fid_data (4)
			hammer_vfs_vptofh Uses fid_data at hammer_vfsops.c:1092
			hammer_vfs_vptofh Uses fid_data at hammer_vfsops.c:1093
			hammer_vfs_fhtovp Uses fid_data at hammer_vfsops.c:1115
			hammer_vfs_fhtovp Uses fid_data at hammer_vfsops.c:1116
		[-] Object: fid_ext (2)
			hammer_vfs_vptofh Sets fid_ext at hammer_vfsops.c:1091
			hammer_vfs_fhtovp Uses fid_ext at hammer_vfsops.c:1120
		[-] Object: fid_len (1)
			hammer_vfs_vptofh Sets fid_len at hammer_vfsops.c:1090
		[-] Struct: fid (5)
			hammer_vfs_fhtovp Uses fid at hammer_vfsops.c:248
			hammer_vfs_vptofh Uses fid at hammer_vfsops.c:249
			fhp Types fid at hammer_vfsops.c:1084
			hammer_vfs_vptofh Uses fid at hammer_vfsops.c:1090
			fhp Types fid at hammer_vfsops.c:1106
	[-] Struct: statfs (2)
		[-] Struct: statfs (2)
			hammer_vfs_statfs Uses statfs at hammer_vfsops.c:239
			sbp Types statfs at hammer_vfsops.c:979
	[-] Struct: vfsconf (2)
		[-] Struct: vfsconf (2)
			hammer_vfs_init Uses vfsconf at hammer_vfsops.c:246
			conf Types vfsconf at hammer_vfsops.c:274
	[-] Macro: MAXFIDSZ (1)
		hammer_vfs_vptofh Uses MAXFIDSZ at hammer_vfsops.c:1088
	[-] Macro: MNAMELEN (2)
		hammer_vfs_mount Uses MNAMELEN at hammer_vfsops.c:763
		hammer_vfs_mount Uses MNAMELEN at hammer_vfsops.c:767
	[-] Macro: MNT_FORCE (1)
		hammer_vfs_unmount Uses MNT_FORCE at hammer_vfsops.c:799
	[-] Macro: MNT_LOCAL (2)
		hammer_vfs_mount Uses MNT_LOCAL at hammer_vfsops.c:648
		hammer_free_hmp Uses MNT_LOCAL at hammer_vfsops.c:879
	[-] Macro: MNT_NOATIME (1)
		hammer_vfs_mount Uses MNT_NOATIME at hammer_vfsops.c:340
	[-] Macro: MNT_RDONLY (5)
		hammer_vfs_mount Uses MNT_RDONLY at hammer_vfsops.c:361
		hammer_vfs_mount Uses MNT_RDONLY at hammer_vfsops.c:460
		hammer_vfs_mount Uses MNT_RDONLY at hammer_vfsops.c:494
		hammer_vfs_mount Uses MNT_RDONLY at hammer_vfsops.c:520
		hammer_critical_error Uses MNT_RDONLY at hammer_vfsops.c:904
	[-] Macro: MNT_UPDATE (3)
		hammer_vfs_mount Uses MNT_UPDATE at hammer_vfsops.c:370
		hammer_vfs_mount Uses MNT_UPDATE at hammer_vfsops.c:474
		hammer_vfs_mount Uses MNT_UPDATE at hammer_vfsops.c:759
	[-] Macro: MNTK_ALL_MPSAFE (1)
		hammer_vfs_mount Uses MNTK_ALL_MPSAFE at hammer_vfsops.c:635
	[-] Macro: MNTK_FSMID (1)
		hammer_vfs_mount Uses MNTK_FSMID at hammer_vfsops.c:627
	[-] Macro: MNTK_THR_SYNC (1)
		hammer_vfs_mount Uses MNTK_THR_SYNC at hammer_vfsops.c:628
	[-] Macro: MNTK_WANTRDWR (1)
		hammer_vfs_mount Uses MNTK_WANTRDWR at hammer_vfsops.c:477
	[-] Macro: VFCF_MPSAFE (1)
		hammer_vfsops.c Uses VFCF_MPSAFE at hammer_vfsops.c:270
[-] mountctl.h (2)
	[-] Macro: MOUNTCTL_SET_EXPORT (1)
		hammer_vfs_export Uses MOUNTCTL_SET_EXPORT at hammer_vfsops.c:1174
	[-] mountctl.h (1)
		hammer_vfsops.c Includes mountctl.h at hammer_vfsops.c:35
[-] msdosfs_vfsops.c (1)
	[-] Macro: FORCECLOSE (1)
		hammer_vfs_unmount Uses FORCECLOSE at hammer_vfsops.c:800
[-] os.c (7)
	[-] Function: bcopy (7)
		hammer_vfs_mount Calls bcopy at hammer_vfsops.c:486
		hammer_vfs_mount Calls bcopy at hammer_vfsops.c:671
		hammer_vfs_mount Calls bcopy at hammer_vfsops.c:734
		hammer_vfs_vptofh Calls bcopy at hammer_vfsops.c:1092
		hammer_vfs_vptofh Calls bcopy at hammer_vfsops.c:1093
		hammer_vfs_fhtovp Calls bcopy at hammer_vfsops.c:1115
		hammer_vfs_fhtovp Calls bcopy at hammer_vfsops.c:1116
[-] param.h (2)
	[-] Macro: MAXPATHLEN (2)
		hammer_vfs_mount Uses MAXPATHLEN at hammer_vfsops.c:551
		hammer_vfs_mount Uses MAXPATHLEN at hammer_vfsops.c:575
[-] queue.h (8)
	[-] Macro: TAILQ_FIRST (1)
		hammer_free_hmp Uses TAILQ_FIRST at hammer_vfsops.c:848
	[-] Macro: TAILQ_INIT (6)
		hammer_vfs_mount Uses TAILQ_INIT at hammer_vfsops.c:448
		hammer_vfs_mount Uses TAILQ_INIT at hammer_vfsops.c:449
		hammer_vfs_mount Uses TAILQ_INIT at hammer_vfsops.c:450
		hammer_vfs_mount Uses TAILQ_INIT at hammer_vfsops.c:451
		hammer_vfs_mount Uses TAILQ_INIT at hammer_vfsops.c:452
		hammer_vfs_mount Uses TAILQ_INIT at hammer_vfsops.c:527
	[-] Macro: TAILQ_REMOVE (1)
		hammer_free_hmp Uses TAILQ_REMOVE at hammer_vfsops.c:849
[-] socket.h (2)
	[-] Struct: sockaddr (2)
		[-] Struct: sockaddr (2)
			hammer_vfs_checkexp Uses sockaddr at hammer_vfsops.c:250
			nam Types sockaddr at hammer_vfsops.c:1144
[-] statvfs.h (2)
	[-] Struct: statvfs (2)
		[-] Struct: statvfs (2)
			hammer_vfs_statvfs Uses statvfs at hammer_vfsops.c:241
			sbp Types statvfs at hammer_vfsops.c:1017
[-] strlen.c (1)
	[-] Function: strlen (1)
		hammer_vfs_mount Calls strlen at hammer_vfsops.c:551
[-] subr_prf.c (2)
	[-] Function: kprintf (1)
		hammer_vfs_mount Calls kprintf at hammer_vfsops.c:701
	[-] Function: ksnprintf (1)
		hammer_vfs_mount Calls ksnprintf at hammer_vfsops.c:708
[-] sysctl.h (116)
	[-] Macro: CTLFLAG_RD (33)
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:107
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:144
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:146
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:148
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:150
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:152
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:154
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:156
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:158
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:160
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:163
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:165
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:167
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:169
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:171
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:173
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:175
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:177
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:179
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:182
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:184
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:186
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:188
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:190
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:192
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:194
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:196
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:199
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:201
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:203
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:205
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:207
		hammer_vfsops.c Uses CTLFLAG_RD at hammer_vfsops.c:209
	[-] Macro: CTLFLAG_RW (25)
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:106
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:109
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:111
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:113
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:115
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:117
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:119
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:121
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:123
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:125
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:127
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:130
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:132
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:134
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:136
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:138
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:141
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:211
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:213
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:215
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:217
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:219
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:221
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:223
		hammer_vfsops.c Uses CTLFLAG_RW at hammer_vfsops.c:225
	[-] Macro: OID_AUTO (58)
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:106
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:107
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:109
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:111
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:113
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:115
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:117
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:119
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:121
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:123
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:125
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:127
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:130
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:132
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:134
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:136
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:138
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:141
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:144
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:146
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:148
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:150
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:152
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:154
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:156
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:158
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:160
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:163
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:165
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:167
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:169
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:171
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:173
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:175
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:177
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:179
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:182
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:184
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:186
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:188
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:190
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:192
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:194
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:196
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:199
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:201
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:203
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:205
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:207
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:209
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:211
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:213
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:215
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:217
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:219
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:221
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:223
		hammer_vfsops.c Uses OID_AUTO at hammer_vfsops.c:225
[-] tree.h (23)
	[-] Macro: RB_EMPTY (2)
		hammer_free_hmp Uses RB_EMPTY at hammer_vfsops.c:847
		hammer_free_hmp Uses RB_EMPTY at hammer_vfsops.c:850
	[-] Macro: RB_INIT (13)
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:511
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:512
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:513
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:514
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:515
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:516
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:517
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:518
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:522
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:523
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:524
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:525
		hammer_vfs_mount Uses RB_INIT at hammer_vfsops.c:526
	[-] Macro: RB_SCAN (8)
		hammer_vfs_mount Uses RB_SCAN at hammer_vfsops.c:480
		hammer_vfs_mount Uses RB_SCAN at hammer_vfsops.c:491
		hammer_vfs_mount Uses RB_SCAN at hammer_vfsops.c:497
		hammer_vfs_mount Uses RB_SCAN at hammer_vfsops.c:504
		hammer_free_hmp Uses RB_SCAN at hammer_vfsops.c:839
		hammer_free_hmp Uses RB_SCAN at hammer_vfsops.c:873
		hammer_free_hmp Uses RB_SCAN at hammer_vfsops.c:875
		hammer_critical_error Uses RB_SCAN at hammer_vfsops.c:905
[-] types.h (5)
	[-] Typedef: caddr_t (2)
		hammer_vfs_mount Uses caddr_t at hammer_vfsops.c:235
		data Types caddr_t at hammer_vfsops.c:322
	[-] Typedef: ino_t (2)
		hammer_vfs_vget Uses ino_t at hammer_vfsops.c:245
		ino Types ino_t at hammer_vfsops.c:921
	[-] Typedef: qaddr_t (1)
		hammer_vfs_mount Casts qaddr_t at hammer_vfsops.c:403
[-] ucred.h (8)
	[-] Struct: ucred (8)
		[-] Struct: ucred (8)
			hammer_vfs_mount Uses ucred at hammer_vfsops.c:236
			hammer_vfs_statfs Uses ucred at hammer_vfsops.c:240
			hammer_vfs_statvfs Uses ucred at hammer_vfsops.c:242
			hammer_vfs_checkexp Uses ucred at hammer_vfsops.c:251
			cred Types ucred at hammer_vfsops.c:323
			cred Types ucred at hammer_vfsops.c:979
			cred Types ucred at hammer_vfsops.c:1017
			credanonp Types ucred at hammer_vfsops.c:1145
[-] uwrapper.c (2)
	[-] Function: copyin (2)
		hammer_vfs_mount Calls copyin at hammer_vfsops.c:363
		hammer_vfs_mount Calls copyin at hammer_vfsops.c:571
[-] vfs_conf.c (1)
	[-] Function: kgetdiskbyname (1)
		hammer_vfs_mount Calls kgetdiskbyname at hammer_vfsops.c:565
[-] vfs_init.c (3)
	[-] Function: vfs_add_vnodeops (3)
		hammer_vfs_mount Calls vfs_add_vnodeops at hammer_vfsops.c:650
		hammer_vfs_mount Calls vfs_add_vnodeops at hammer_vfsops.c:651
		hammer_vfs_mount Calls vfs_add_vnodeops at hammer_vfsops.c:652
[-] vfs_lock.c (1)
	[-] Function: vput (1)
		hammer_vfs_mount Calls vput at hammer_vfsops.c:746
[-] vfs_mount.c (2)
	[-] Function: vflush (2)
		hammer_vfs_mount Calls vflush at hammer_vfsops.c:756
		hammer_vfs_unmount Calls vflush at hammer_vfsops.c:801
[-] vfs_subr.c (3)
	[-] Function: bdevvp (1)
		hammer_vfs_mount Calls bdevvp at hammer_vfsops.c:566
	[-] Function: vfs_export (1)
		hammer_vfs_export Calls vfs_export at hammer_vfsops.c:1175
	[-] Function: vfs_export_lookup (1)
		hammer_vfs_checkexp Calls vfs_export_lookup at hammer_vfsops.c:1152



---



hammer_vnops.c (910)



[-] _null.h (35)
	[-] Macro: NULL (35)
		hammer_vop_fsync Uses NULL at hammer_vnops.c:275
		hammer_vop_fsync Uses NULL at hammer_vnops.c:275
		hammer_vop_read Uses NULL at hammer_vnops.c:422
		hammer_vop_read Uses NULL at hammer_vnops.c:422
		hammer_vop_write Uses NULL at hammer_vnops.c:567
		hammer_vop_ncreate Uses NULL at hammer_vnops.c:954
		hammer_vop_ncreate Uses NULL at hammer_vnops.c:958
		hammer_vop_ncreate Uses NULL at hammer_vnops.c:979
		hammer_vop_nresolve Uses NULL at hammer_vnops.c:1173
		hammer_vop_nresolve Uses NULL at hammer_vnops.c:1201
		hammer_vop_nresolve Uses NULL at hammer_vnops.c:1286
		hammer_vop_nresolve Uses NULL at hammer_vnops.c:1294
		hammer_vop_nlookupdotdot Uses NULL at hammer_vnops.c:1356
		hammer_vop_nlookupdotdot Uses NULL at hammer_vnops.c:1371
		hammer_vop_nmkdir Uses NULL at hammer_vnops.c:1477
		hammer_vop_nmkdir Uses NULL at hammer_vnops.c:1480
		hammer_vop_nmkdir Uses NULL at hammer_vnops.c:1499
		hammer_vop_nmknod Uses NULL at hammer_vnops.c:1555
		hammer_vop_nmknod Uses NULL at hammer_vnops.c:1558
		hammer_vop_nmknod Uses NULL at hammer_vnops.c:1576
		hammer_vop_readdir Uses NULL at hammer_vnops.c:1654
		hammer_vop_readdir Uses NULL at hammer_vnops.c:1761
		hammer_vop_readlink Uses NULL at hammer_vnops.c:1820
		hammer_vop_nrename Uses NULL at hammer_vnops.c:1946
		hammer_vop_setattr Uses NULL at hammer_vnops.c:2257
		hammer_vop_nsymlink Uses NULL at hammer_vnops.c:2417
		hammer_vop_nsymlink Uses NULL at hammer_vnops.c:2420
		hammer_vop_nsymlink Uses NULL at hammer_vnops.c:2465
		hammer_vop_mountctl Uses NULL at hammer_vnops.c:2536
		hammer_vop_mountctl Uses NULL at hammer_vnops.c:2547
		hammer_vop_strategy_read Uses NULL at hammer_vnops.c:2676
		hammer_vop_strategy_read Uses NULL at hammer_vnops.c:2689
		hammer_vnops.c Uses NULL at hammer_vnops.c:3532
		hammer_vnops.c Uses NULL at hammer_vnops.c:3535
		hammer_vnops.c Uses NULL at hammer_vnops.c:3538
[-] bio.h (16)
	[-] Struct: bio (16)
		[-] Object: bio_buf (2)
			hammer_vop_strategy_read Uses bio_buf at hammer_vnops.c:2658
			hammer_vop_strategy_write Uses bio_buf at hammer_vnops.c:3183
		[-] Object: bio_offset (11)
			hammer_vop_strategy_read Uses bio_offset at hammer_vnops.c:2673
			hammer_vop_strategy_read Uses bio_offset at hammer_vnops.c:2714
			hammer_vop_strategy_read Uses bio_offset at hammer_vnops.c:2728
			hammer_vop_strategy_read Uses bio_offset at hammer_vnops.c:2767
			hammer_vop_strategy_read Sets bio_offset at hammer_vnops.c:2851
			hammer_vop_strategy_read Sets bio_offset at hammer_vnops.c:2860
			hammer_vop_strategy_write Uses bio_offset at hammer_vnops.c:3187
			hammer_vop_strategy_write Uses bio_offset at hammer_vnops.c:3242
			hammer_vop_strategy_write Uses bio_offset at hammer_vnops.c:3243
			hammer_vop_strategy_write Uses bio_offset at hammer_vnops.c:3244
			hammer_vop_strategy_write Uses bio_offset at hammer_vnops.c:3249
		[-] Struct: bio (3)
			bio Types bio at hammer_vnops.c:2645
			nbio Types bio at hammer_vnops.c:2646
			bio Types bio at hammer_vnops.c:3176
[-] buf.h (34)
	[-] Struct: buf (24)
		[-] Object: b_bufsize (12)
			hammer_vop_strategy_read Uses b_bufsize at hammer_vnops.c:2728
			hammer_vop_strategy_read Uses b_bufsize at hammer_vnops.c:2769
			hammer_vop_strategy_read Uses b_bufsize at hammer_vnops.c:2770
			hammer_vop_strategy_read Uses b_bufsize at hammer_vnops.c:2790
			hammer_vop_strategy_read Uses b_bufsize at hammer_vnops.c:2791
			hammer_vop_strategy_read Uses b_bufsize at hammer_vnops.c:2842
			hammer_vop_strategy_read Uses b_bufsize at hammer_vnops.c:2877
			hammer_vop_strategy_read Uses b_bufsize at hammer_vnops.c:2887
			hammer_vop_strategy_read Uses b_bufsize at hammer_vnops.c:2888
			hammer_vop_strategy_read Uses b_bufsize at hammer_vnops.c:2889
			hammer_vop_strategy_write Uses b_bufsize at hammer_vnops.c:3188
			hammer_vop_strategy_write Uses b_bufsize at hammer_vnops.c:3245
		[-] Object: b_data (7)
			hammer_vop_read Uses b_data at hammer_vnops.c:453
			hammer_vop_write Uses b_data at hammer_vnops.c:722
			hammer_vop_write Uses b_data at hammer_vnops.c:747
			hammer_vop_strategy_read Uses b_data at hammer_vnops.c:2771
			hammer_vop_strategy_read Uses b_data at hammer_vnops.c:2867
			hammer_vop_strategy_read Uses b_data at hammer_vnops.c:2889
			hammer_vop_strategy_write Uses b_data at hammer_vnops.c:3249
		[-] Struct: buf (5)
			bp Types buf at hammer_vnops.c:309
			bp Types buf at hammer_vnops.c:504
			bp Types buf at hammer_vnops.c:2602
			bp Types buf at hammer_vnops.c:2647
			bp Types buf at hammer_vnops.c:3177
	[-] Struct: vnode (10)
		[-] Struct: vnode (10)
			vp Types vnode at hammer_vnops.c:149
			hammer_dounlink Uses vnode at hammer_vnops.c:156
			vp Types vnode at hammer_vnops.c:499
			vp Types vnode at hammer_vnops.c:1119
			vp Types vnode at hammer_vnops.c:2069
			dvp Types vnode at hammer_vnops.c:3282
			vp Types vnode at hammer_vnops.c:3445
			vp Types vnode at hammer_vnops.c:3544
			vp Types vnode at hammer_vnops.c:3571
			vp Types vnode at hammer_vnops.c:3579
[-] buf.h (7)
	[-] Macro: B_RAM (1)
		hammer_vop_read Addr Uses B_RAM at hammer_vnops.c:380
	[-] Macro: B_VFSFLAG1 (3)
		hammer_vop_write Uses B_VFSFLAG1 at hammer_vnops.c:743
		hammer_vop_strategy_write Addr Uses B_VFSFLAG1 at hammer_vnops.c:3258
		hammer_vop_strategy_write Uses B_VFSFLAG1 at hammer_vnops.c:3260
	[-] Macro: GETBLK_BHEAVY (3)
		hammer_vop_write Uses GETBLK_BHEAVY at hammer_vnops.c:689
		hammer_vop_write Uses GETBLK_BHEAVY at hammer_vnops.c:701
		hammer_vop_write Uses GETBLK_BHEAVY at hammer_vnops.c:710
[-] buf2.h (5)
	[-] Macro: B_NOTMETA (4)
		hammer_vop_read Uses B_NOTMETA at hammer_vnops.c:415
		hammer_vop_read Uses B_NOTMETA at hammer_vnops.c:421
		hammer_vop_strategy_read Uses B_NOTMETA at hammer_vnops.c:2899
		hammer_vop_strategy_write Uses B_NOTMETA at hammer_vnops.c:3205
	[-] buf2.h (1)
		hammer_vnops.c Includes buf2.h at hammer_vnops.c:37
[-] dirent.h (3)
	[-] Macro: DT_DIR (3)
		hammer_vop_readdir Uses DT_DIR at hammer_vnops.c:1670
		hammer_vop_readdir Uses DT_DIR at hammer_vnops.c:1684
		hammer_vop_readdir Uses DT_DIR at hammer_vnops.c:1687
[-] dirfs_vnops.c (13)
	[-] Macro: B_ERROR (4)
		hammer_vop_strategy Uses B_ERROR at hammer_vnops.c:2616
		hammer_vop_strategy_read Uses B_ERROR at hammer_vnops.c:2907
		hammer_vop_strategy_write Uses B_ERROR at hammer_vnops.c:3192
		hammer_vop_strategy_write Uses B_ERROR at hammer_vnops.c:3268
	[-] Macro: IO_APPEND (1)
		hammer_vop_write Addr Uses IO_APPEND at hammer_vnops.c:548
	[-] Macro: IO_SYNC (1)
		hammer_vop_write Addr Uses IO_SYNC at hammer_vnops.c:826
	[-] Macro: VNOVAL (7)
		hammer_vop_setattr Uses VNOVAL at hammer_vnops.c:2188
		hammer_vop_setattr Uses VNOVAL at hammer_vnops.c:2211
		hammer_vop_setattr Uses VNOVAL at hammer_vnops.c:2211
		hammer_vop_setattr Uses VNOVAL at hammer_vnops.c:2236
		hammer_vop_setattr Uses VNOVAL at hammer_vnops.c:2343
		hammer_vop_setattr Uses VNOVAL at hammer_vnops.c:2348
		hammer_vop_setattr Uses VNOVAL at hammer_vnops.c:2354
[-] event.h (40)
	[-] Macro: EV_EOF (3)
		filt_hammerread Uses EV_EOF at hammer_vnops.c:3585
		filt_hammerwrite Uses EV_EOF at hammer_vnops.c:3601
		filt_hammervnode Uses EV_EOF at hammer_vnops.c:3612
	[-] Macro: EV_NODATA (3)
		filt_hammerread Uses EV_NODATA at hammer_vnops.c:3585
		filt_hammerwrite Uses EV_NODATA at hammer_vnops.c:3601
		filt_hammervnode Uses EV_NODATA at hammer_vnops.c:3612
	[-] Macro: EV_ONESHOT (2)
		filt_hammerread Uses EV_ONESHOT at hammer_vnops.c:3585
		filt_hammerwrite Uses EV_ONESHOT at hammer_vnops.c:3601
	[-] Macro: EVFILT_READ (1)
		hammer_vop_kqfilter Uses EVFILT_READ at hammer_vnops.c:3548
	[-] Macro: EVFILT_VNODE (1)
		hammer_vop_kqfilter Uses EVFILT_VNODE at hammer_vnops.c:3554
	[-] Macro: EVFILT_WRITE (1)
		hammer_vop_kqfilter Uses EVFILT_WRITE at hammer_vnops.c:3551
	[-] Macro: NOTE_ATTRIB (7)
		hammer_vop_markatime Uses NOTE_ATTRIB at hammer_vnops.c:2143
		hammer_vop_setattr Uses NOTE_ATTRIB at hammer_vnops.c:2198
		hammer_vop_setattr Uses NOTE_ATTRIB at hammer_vnops.c:2233
		hammer_vop_setattr Uses NOTE_ATTRIB at hammer_vnops.c:2335
		hammer_vop_setattr Uses NOTE_ATTRIB at hammer_vnops.c:2346
		hammer_vop_setattr Uses NOTE_ATTRIB at hammer_vnops.c:2351
		hammer_vop_setattr Uses NOTE_ATTRIB at hammer_vnops.c:2365
	[-] Macro: NOTE_DELETE (1)
		hammer_dounlink Uses NOTE_DELETE at hammer_vnops.c:3450
	[-] Macro: NOTE_EXTEND (2)
		hammer_vop_write Uses NOTE_EXTEND at hammer_vnops.c:677
		hammer_vop_setattr Uses NOTE_EXTEND at hammer_vnops.c:2283
	[-] Macro: NOTE_LINK (3)
		hammer_vop_nlink Uses NOTE_LINK at hammer_vnops.c:1433
		hammer_vop_nmkdir Uses NOTE_LINK at hammer_vnops.c:1510
		hammer_vop_nrmdir Uses NOTE_LINK at hammer_vnops.c:2113
	[-] Macro: NOTE_RENAME (1)
		hammer_vop_nrename Uses NOTE_RENAME at hammer_vnops.c:2074
	[-] Macro: NOTE_REVOKE (3)
		filt_hammerread Uses NOTE_REVOKE at hammer_vnops.c:3584
		filt_hammerwrite Uses NOTE_REVOKE at hammer_vnops.c:3600
		filt_hammervnode Uses NOTE_REVOKE at hammer_vnops.c:3611
	[-] Macro: NOTE_WRITE (12)
		hammer_vop_write Uses NOTE_WRITE at hammer_vnops.c:769
		hammer_vop_ncreate Uses NOTE_WRITE at hammer_vnops.c:988
		hammer_vop_nlink Uses NOTE_WRITE at hammer_vnops.c:1434
		hammer_vop_nmkdir Uses NOTE_WRITE at hammer_vnops.c:1510
		hammer_vop_nmknod Uses NOTE_WRITE at hammer_vnops.c:1587
		hammer_vop_nremove Uses NOTE_WRITE at hammer_vnops.c:1912
		hammer_vop_nrename Uses NOTE_WRITE at hammer_vnops.c:2066
		hammer_vop_nrename Uses NOTE_WRITE at hammer_vnops.c:2067
		hammer_vop_nrmdir Uses NOTE_WRITE at hammer_vnops.c:2113
		hammer_vop_setattr Uses NOTE_WRITE at hammer_vnops.c:2272
		hammer_vop_setattr Uses NOTE_WRITE at hammer_vnops.c:2283
		hammer_vop_nsymlink Uses NOTE_WRITE at hammer_vnops.c:2472
[-] ext2_inode.c (4)
	[-] Macro: B_CACHE (4)
		hammer_vop_read Addr Uses B_CACHE at hammer_vnops.c:380
		hammer_vop_read Uses B_CACHE at hammer_vnops.c:380
		hammer_vop_write Addr Uses B_CACHE at hammer_vnops.c:690
		hammer_vop_write Addr Uses B_CACHE at hammer_vnops.c:702
[-] fcntl.h (1)
	[-] Macro: FWRITE (1)
		hammer_vop_open Uses FWRITE at hammer_vnops.c:1605
[-] fifo.h (1)
	[-] fifo.h (1)
		hammer_vnops.c Includes fifo.h at hammer_vnops.c:38
[-] fifo_vnops.c (5)
	[-] Function: fifo_vnoperate (1)
		hammer_vnops.c Pointers fifo_vnoperate at hammer_vnops.c:133
	[-] Object: fifo_vnode_vops (4)
		hammer_vop_fifoclose Addr Uses fifo_vnode_vops at hammer_vnops.c:3485
		hammer_vop_fiforead Addr Uses fifo_vnode_vops at hammer_vnops.c:3493
		hammer_vop_fifowrite Addr Uses fifo_vnode_vops at hammer_vnops.c:3503
		hammer_vop_fifokqfilter Addr Uses fifo_vnode_vops at hammer_vnops.c:3514
[-] hammer2_vnops.c (1)
	[-] Macro: NOTE_OLDAPI (1)
		filt_hammerread Addr Uses NOTE_OLDAPI at hammer_vnops.c:3592
[-] kern_event.c (2)
	[-] Function: knote_insert (1)
		hammer_vop_kqfilter Calls knote_insert at hammer_vnops.c:3563
	[-] Function: knote_remove (1)
		filt_hammerdetach Calls knote_remove at hammer_vnops.c:3573
[-] kern_iosched.c (1)
	[-] Function: bwillwrite (1)
		hammer_vop_write Calls bwillwrite at hammer_vnops.c:646
[-] kern_lockf.c (1)
	[-] Function: lf_advlock (1)
		hammer_vop_advlock Calls lf_advlock at hammer_vnops.c:883
[-] kern_sig.c (1)
	[-] Function: lwpsignal (1)
		hammer_vop_write Calls lwpsignal at hammer_vnops.c:570
[-] kern_slaballoc.c (3)
	[-] Function: kfree (1)
		hammer_vop_readdir Calls kfree at hammer_vnops.c:1759
	[-] Function: kmalloc (2)
		hammer_vop_nlookupdotdot Calls kmalloc at hammer_vnops.c:1352
		hammer_vop_readdir Calls kmalloc at hammer_vnops.c:1650
[-] kern_subr.c (4)
	[-] Function: uiomove (2)
		hammer_vop_readlink Calls uiomove at hammer_vnops.c:1843
		hammer_vop_readlink Calls uiomove at hammer_vnops.c:1875
	[-] Function: uiomovebp (2)
		hammer_vop_read Calls uiomovebp at hammer_vnops.c:453
		hammer_vop_write Calls uiomovebp at hammer_vnops.c:722
[-] kern_uuid.c (2)
	[-] Function: kuuid_compare (2)
		hammer_vop_setattr Calls kuuid_compare at hammer_vnops.c:2224
		hammer_vop_setattr Calls kuuid_compare at hammer_vnops.c:2225
[-] lwkt_token.c (64)
	[-] Function: lwkt_gettoken (27)
		hammer_vop_fsync Calls lwkt_gettoken at hammer_vnops.c:186
		hammer_vop_read Calls lwkt_gettoken at hammer_vnops.c:476
		hammer_vop_write Calls lwkt_gettoken at hammer_vnops.c:620
		hammer_vop_write Calls lwkt_gettoken at hammer_vnops.c:724
		hammer_vop_ncreate Calls lwkt_gettoken at hammer_vnops.c:944
		hammer_vop_nresolve Calls lwkt_gettoken at hammer_vnops.c:1144
		hammer_vop_nlookupdotdot Calls lwkt_gettoken at hammer_vnops.c:1337
		hammer_vop_nlink Calls lwkt_gettoken at hammer_vnops.c:1413
		hammer_vop_nmkdir Calls lwkt_gettoken at hammer_vnops.c:1468
		hammer_vop_nmknod Calls lwkt_gettoken at hammer_vnops.c:1544
		hammer_vop_readdir Calls lwkt_gettoken at hammer_vnops.c:1658
		hammer_vop_readlink Calls lwkt_gettoken at hammer_vnops.c:1794
		hammer_vop_nremove Calls lwkt_gettoken at hammer_vnops.c:1907
		hammer_vop_nrename Calls lwkt_gettoken at hammer_vnops.c:1964
		hammer_vop_nrmdir Calls lwkt_gettoken at hammer_vnops.c:2108
		hammer_vop_markatime Calls lwkt_gettoken at hammer_vnops.c:2137
		hammer_vop_setattr Calls lwkt_gettoken at hammer_vnops.c:2184
		hammer_vop_nsymlink Calls lwkt_gettoken at hammer_vnops.c:2407
		hammer_vop_nwhiteout Calls lwkt_gettoken at hammer_vnops.c:2500
		hammer_vop_ioctl Calls lwkt_gettoken at hammer_vnops.c:2521
		hammer_vop_mountctl Calls lwkt_gettoken at hammer_vnops.c:2550
		hammer_vop_strategy_read Calls lwkt_gettoken at hammer_vnops.c:2675
		hammer_vop_strategy_read Calls lwkt_gettoken at hammer_vnops.c:2688
		hammer_vop_strategy_read Calls lwkt_gettoken at hammer_vnops.c:2699
		hammer_vop_bmap Calls lwkt_gettoken at hammer_vnops.c:2995
		hammer_vop_strategy_write Calls lwkt_gettoken at hammer_vnops.c:3197
		filt_hammerread Calls lwkt_gettoken at hammer_vnops.c:3588
	[-] Function: lwkt_reltoken (37)
		hammer_vop_fsync Calls lwkt_reltoken at hammer_vnops.c:220
		hammer_vop_fsync Calls lwkt_reltoken at hammer_vnops.c:242
		hammer_vop_fsync Calls lwkt_reltoken at hammer_vnops.c:292
		hammer_vop_read Calls lwkt_reltoken at hammer_vnops.c:480
		hammer_vop_write Calls lwkt_reltoken at hammer_vnops.c:627
		hammer_vop_write Calls lwkt_reltoken at hammer_vnops.c:766
		hammer_vop_write Calls lwkt_reltoken at hammer_vnops.c:791
		hammer_vop_ncreate Calls lwkt_reltoken at hammer_vnops.c:959
		hammer_vop_ncreate Calls lwkt_reltoken at hammer_vnops.c:990
		hammer_vop_nresolve Calls lwkt_reltoken at hammer_vnops.c:1298
		hammer_vop_nlookupdotdot Calls lwkt_reltoken at hammer_vnops.c:1357
		hammer_vop_nlookupdotdot Calls lwkt_reltoken at hammer_vnops.c:1374
		hammer_vop_nlink Calls lwkt_reltoken at hammer_vnops.c:1435
		hammer_vop_nmkdir Calls lwkt_reltoken at hammer_vnops.c:1481
		hammer_vop_nmkdir Calls lwkt_reltoken at hammer_vnops.c:1511
		hammer_vop_nmknod Calls lwkt_reltoken at hammer_vnops.c:1559
		hammer_vop_nmknod Calls lwkt_reltoken at hammer_vnops.c:1588
		hammer_vop_readdir Calls lwkt_reltoken at hammer_vnops.c:1771
		hammer_vop_readlink Calls lwkt_reltoken at hammer_vnops.c:1844
		hammer_vop_readlink Calls lwkt_reltoken at hammer_vnops.c:1883
		hammer_vop_nremove Calls lwkt_reltoken at hammer_vnops.c:1913
		hammer_vop_nrename Calls lwkt_reltoken at hammer_vnops.c:2084
		hammer_vop_nrmdir Calls lwkt_reltoken at hammer_vnops.c:2114
		hammer_vop_markatime Calls lwkt_reltoken at hammer_vnops.c:2144
		hammer_vop_setattr Calls lwkt_reltoken at hammer_vnops.c:2373
		hammer_vop_nsymlink Calls lwkt_reltoken at hammer_vnops.c:2421
		hammer_vop_nsymlink Calls lwkt_reltoken at hammer_vnops.c:2476
		hammer_vop_nwhiteout Calls lwkt_reltoken at hammer_vnops.c:2505
		hammer_vop_ioctl Calls lwkt_reltoken at hammer_vnops.c:2524
		hammer_vop_mountctl Calls lwkt_reltoken at hammer_vnops.c:2584
		hammer_vop_strategy_read Calls lwkt_reltoken at hammer_vnops.c:2677
		hammer_vop_strategy_read Calls lwkt_reltoken at hammer_vnops.c:2690
		hammer_vop_strategy_read Calls lwkt_reltoken at hammer_vnops.c:2934
		hammer_vop_bmap Calls lwkt_reltoken at hammer_vnops.c:3104
		hammer_vop_strategy_write Calls lwkt_reltoken at hammer_vnops.c:3221
		hammer_vop_strategy_write Calls lwkt_reltoken at hammer_vnops.c:3271
		filt_hammerread Calls lwkt_reltoken at hammer_vnops.c:3591
[-] malloc.h (2)
	[-] Macro: M_WAITOK (2)
		hammer_vop_nlookupdotdot Uses M_WAITOK at hammer_vnops.c:1352
		hammer_vop_readdir Uses M_WAITOK at hammer_vnops.c:1650
[-] memset.c (2)
	[-] Function: bzero (2)
		hammer_vop_strategy_read Calls bzero at hammer_vnops.c:2771
		hammer_vop_strategy_read Calls bzero at hammer_vnops.c:2889
[-] mman.h (12)
	[-] Typedef: mode_t (3)
		cur_mode Types mode_t at hammer_vnops.c:2212
		hammer_vop_setattr Casts mode_t at hammer_vnops.c:2354
		cur_mode Types mode_t at hammer_vnops.c:2355
	[-] Typedef: off_t (7)
		offset Types off_t at hammer_vnops.c:308
		base_offset Types off_t at hammer_vnops.c:502
		nsize Types off_t at hammer_vnops.c:601
		cookies Types off_t at hammer_vnops.c:1636
		saveoff Types off_t at hammer_vnops.c:1637
		hammer_vop_readdir Uses off_t at hammer_vnops.c:1650
		off Types off_t at hammer_vnops.c:3582
	[-] Typedef: size_t (2)
		resid Types size_t at hammer_vnops.c:318
		hammer_vop_write Casts size_t at hammer_vnops.c:748
[-] mount.h (15)
	[-] Struct: export_args (2)
		[-] Struct: export_args (2)
			hammer_vop_mountctl Uses export_args at hammer_vnops.c:2554
			hammer_vop_mountctl Casts export_args at hammer_vnops.c:2558
	[-] Macro: MNT_NOATIME (2)
		hammer_vop_read Uses MNT_NOATIME at hammer_vnops.c:475
		hammer_vop_markatime Uses MNT_NOATIME at hammer_vnops.c:2135
	[-] Macro: MNT_NOCLUSTERW (1)
		hammer_vop_write Uses MNT_NOCLUSTERW at hammer_vnops.c:833
	[-] Macro: MNT_NOWAIT (3)
		hammer_vop_fsync Uses MNT_NOWAIT at hammer_vnops.c:202
		hammer_vop_fsync Uses MNT_NOWAIT at hammer_vnops.c:216
		hammer_vop_fsync Uses MNT_NOWAIT at hammer_vnops.c:226
	[-] Macro: MNT_RDONLY (2)
		hammer_vop_markatime Uses MNT_RDONLY at hammer_vnops.c:2130
		hammer_vop_setattr Uses MNT_RDONLY at hammer_vnops.c:2175
	[-] Macro: MNT_WAIT (4)
		hammer_vop_fsync Uses MNT_WAIT at hammer_vnops.c:201
		hammer_vop_fsync Uses MNT_WAIT at hammer_vnops.c:215
		hammer_vop_fsync Uses MNT_WAIT at hammer_vnops.c:225
		hammer_vop_fsync Uses MNT_WAIT at hammer_vnops.c:277
	[-] Macro: VOP_FSYNC_SYSCALL (1)
		hammer_vop_fsync Uses VOP_FSYNC_SYSCALL at hammer_vnops.c:192
[-] mountctl.h (3)
	[-] Macro: MOUNTCTL_MOUNTFLAGS (1)
		hammer_vop_mountctl Uses MOUNTCTL_MOUNTFLAGS at hammer_vnops.c:2560
	[-] Macro: MOUNTCTL_SET_EXPORT (1)
		hammer_vop_mountctl Uses MOUNTCTL_SET_EXPORT at hammer_vnops.c:2553
	[-] mountctl.h (1)
		hammer_vnops.c Includes mountctl.h at hammer_vnops.c:35
[-] namecache.h (70)
	[-] Struct: namecache (43)
		[-] Object: nc_name (23)
			hammer_vop_ncreate Uses nc_name at hammer_vnops.c:953
			hammer_vop_ncreate Uses nc_name at hammer_vnops.c:968
			hammer_vop_nresolve Deref Uses nc_name at hammer_vnops.c:1148
			hammer_vop_nresolve Deref Uses nc_name at hammer_vnops.c:1148
			hammer_vop_nresolve Uses nc_name at hammer_vnops.c:1149
			hammer_vop_nresolve Deref Uses nc_name at hammer_vnops.c:1193
			hammer_vop_nresolve Uses nc_name at hammer_vnops.c:1218
			hammer_vop_nresolve Uses nc_name at hammer_vnops.c:1253
			hammer_vop_nresolve Uses nc_name at hammer_vnops.c:1274
			hammer_vop_nlink Uses nc_name at hammer_vnops.c:1422
			hammer_vop_nmkdir Uses nc_name at hammer_vnops.c:1476
			hammer_vop_nmkdir Uses nc_name at hammer_vnops.c:1489
			hammer_vop_nmknod Uses nc_name at hammer_vnops.c:1554
			hammer_vop_nmknod Uses nc_name at hammer_vnops.c:1568
			hammer_vop_nrename Uses nc_name at hammer_vnops.c:1978
			hammer_vop_nrename Uses nc_name at hammer_vnops.c:1998
			hammer_vop_nrename Uses nc_name at hammer_vnops.c:2030
			hammer_vop_nsymlink Uses nc_name at hammer_vnops.c:2416
			hammer_vop_nsymlink Uses nc_name at hammer_vnops.c:2457
			hammer_dounlink Uses nc_name at hammer_vnops.c:3308
			hammer_dounlink Uses nc_name at hammer_vnops.c:3344
			hammer_dounlink Uses nc_name at hammer_vnops.c:3368
			hammer_dounlink Uses nc_name at hammer_vnops.c:3410
		[-] Object: nc_nlen (15)
			hammer_vop_ncreate Uses nc_nlen at hammer_vnops.c:953
			hammer_vop_ncreate Uses nc_nlen at hammer_vnops.c:968
			hammer_vop_nresolve Uses nc_nlen at hammer_vnops.c:1139
			hammer_vop_nlink Uses nc_nlen at hammer_vnops.c:1422
			hammer_vop_nmkdir Uses nc_nlen at hammer_vnops.c:1476
			hammer_vop_nmkdir Uses nc_nlen at hammer_vnops.c:1489
			hammer_vop_nmknod Uses nc_nlen at hammer_vnops.c:1554
			hammer_vop_nmknod Uses nc_nlen at hammer_vnops.c:1568
			hammer_vop_nrename Uses nc_nlen at hammer_vnops.c:1978
			hammer_vop_nrename Uses nc_nlen at hammer_vnops.c:1998
			hammer_vop_nrename Uses nc_nlen at hammer_vnops.c:2029
			hammer_vop_nsymlink Uses nc_nlen at hammer_vnops.c:2416
			hammer_vop_nsymlink Uses nc_nlen at hammer_vnops.c:2458
			hammer_dounlink Uses nc_nlen at hammer_vnops.c:3308
			hammer_dounlink Uses nc_nlen at hammer_vnops.c:3343
		[-] Object: nc_vp (1)
			hammer_vop_nrename Uses nc_vp at hammer_vnops.c:1945
		[-] Struct: namecache (4)
			ncp Types namecache at hammer_vnops.c:1113
			fncp Types namecache at hammer_vnops.c:1925
			tncp Types namecache at hammer_vnops.c:1926
			ncp Types namecache at hammer_vnops.c:3285
	[-] Struct: nchandle (26)
		[-] Object: ncp (19)
			hammer_vop_ncreate Deref Uses ncp at hammer_vnops.c:953
			hammer_vop_ncreate Deref Uses ncp at hammer_vnops.c:953
			hammer_vop_ncreate Deref Uses ncp at hammer_vnops.c:968
			hammer_vop_ncreate Deref Uses ncp at hammer_vnops.c:968
			hammer_vop_nlink Deref Uses ncp at hammer_vnops.c:1422
			hammer_vop_nlink Deref Uses ncp at hammer_vnops.c:1422
			hammer_vop_nmkdir Deref Uses ncp at hammer_vnops.c:1476
			hammer_vop_nmkdir Deref Uses ncp at hammer_vnops.c:1476
			hammer_vop_nmkdir Deref Uses ncp at hammer_vnops.c:1489
			hammer_vop_nmkdir Deref Uses ncp at hammer_vnops.c:1489
			hammer_vop_nmknod Deref Uses ncp at hammer_vnops.c:1554
			hammer_vop_nmknod Deref Uses ncp at hammer_vnops.c:1554
			hammer_vop_nmknod Deref Uses ncp at hammer_vnops.c:1568
			hammer_vop_nmknod Deref Uses ncp at hammer_vnops.c:1568
			hammer_vop_nsymlink Deref Uses ncp at hammer_vnops.c:2416
			hammer_vop_nsymlink Deref Uses ncp at hammer_vnops.c:2416
			hammer_vop_nsymlink Deref Uses ncp at hammer_vnops.c:2457
			hammer_vop_nsymlink Deref Uses ncp at hammer_vnops.c:2458
			hammer_dounlink Uses ncp at hammer_vnops.c:3302
		[-] Struct: nchandle (7)
			hammer_dounlink Uses nchandle at hammer_vnops.c:155
			nch Types nchandle at hammer_vnops.c:928
			nch Types nchandle at hammer_vnops.c:1388
			nch Types nchandle at hammer_vnops.c:1452
			nch Types nchandle at hammer_vnops.c:1528
			nch Types nchandle at hammer_vnops.c:2388
			nch Types nchandle at hammer_vnops.c:3281
	[-] namecache.h (1)
		hammer_vnops.c Includes namecache.h at hammer_vnops.c:36
[-] os.c (4)
	[-] Function: bcopy (4)
		hammer_vop_readlink Calls bcopy at hammer_vnops.c:1818
		hammer_vop_nsymlink Calls bcopy at hammer_vnops.c:2433
		hammer_vop_nsymlink Calls bcopy at hammer_vnops.c:2444
		hammer_vop_strategy_read Calls bcopy at hammer_vnops.c:2866
[-] param.h (3)
	[-] Macro: MAXBSIZE (3)
		hammer_vop_read Uses MAXBSIZE at hammer_vnops.c:344
		hammer_vop_read Uses MAXBSIZE at hammer_vnops.c:344
		hammer_vop_read Uses MAXBSIZE at hammer_vnops.c:417
[-] proc.h (2)
	[-] Struct: proc (1)
		[-] Object: p_limit (1)
			hammer_vop_write Deref Uses p_limit at hammer_vnops.c:568
	[-] Macro: p_rlimit (1)
		hammer_vop_write Uses p_rlimit at hammer_vnops.c:568
[-] quotacheck.c (2)
	[-] Function: bread (2)
		hammer_vop_write Calls bread at hammer_vnops.c:692
		hammer_vop_write Calls bread at hammer_vnops.c:717
[-] resource.h (1)
	[-] Struct: rlimit (1)
		[-] Object: rlim_cur (1)
			hammer_vop_write Uses rlim_cur at hammer_vnops.c:568
[-] resourcevar.h (1)
	[-] Struct: plimit (1)
		[-] Object: pl_rlimit (1)
			hammer_vop_write Deref Uses pl_rlimit at hammer_vnops.c:568
[-] signal.h (1)
	[-] Macro: SIGXFSZ (1)
		hammer_vop_write Uses SIGXFSZ at hammer_vnops.c:570
[-] strlen.c (2)
	[-] Function: strlen (2)
		hammer_vop_readlink Calls strlen at hammer_vnops.c:1837
		hammer_vop_nsymlink Calls strlen at hammer_vnops.c:2430
[-] strncmp.c (2)
	[-] Function: strncmp (2)
		hammer_vop_getattr Calls strncmp at hammer_vnops.c:1051
		hammer_vop_readlink Calls strncmp at hammer_vnops.c:1816
[-] strtoul.c (1)
	[-] Function: strtoul (1)
		hammer_vop_readlink Calls strtoul at hammer_vnops.c:1820
[-] subr_diskgpt.c (4)
	[-] Macro: B_AGE (3)
		hammer_vop_read Uses B_AGE at hammer_vnops.c:381
		hammer_vop_read Uses B_AGE at hammer_vnops.c:452
		hammer_vop_write Uses B_AGE at hammer_vnops.c:822
	[-] Macro: B_INVAL (1)
		hammer_vop_read Addr Uses B_INVAL at hammer_vnops.c:380
[-] subr_prf.c (3)
	[-] Function: ksnprintf (3)
		hammer_vop_nlookupdotdot Calls ksnprintf at hammer_vnops.c:1353
		hammer_vop_readlink Calls ksnprintf at hammer_vnops.c:1826
		hammer_vop_readlink Calls ksnprintf at hammer_vnops.c:1832
[-] thread.h (5)
	[-] Struct: thread (4)
		[-] Object: td_lwp (1)
			hammer_vop_write Uses td_lwp at hammer_vnops.c:570
		[-] Object: td_proc (3)
			hammer_vop_write Uses td_proc at hammer_vnops.c:567
			hammer_vop_write Deref Uses td_proc at hammer_vnops.c:568
			hammer_vop_write Uses td_proc at hammer_vnops.c:570
	[-] Typedef: thread_t (1)
		td Types thread_t at hammer_vnops.c:498
[-] types.h (9)
	[-] Typedef: caddr_t (1)
		hammer_vop_kqfilter Casts caddr_t at hammer_vnops.c:3561
	[-] Typedef: gid_t (4)
		gid Types gid_t at hammer_vnops.c:861
		hammer_vop_setattr Casts gid_t at hammer_vnops.c:2211
		cur_gid Types gid_t at hammer_vnops.c:2214
		cur_gid Types gid_t at hammer_vnops.c:2357
	[-] Typedef: uid_t (4)
		uid Types uid_t at hammer_vnops.c:860
		hammer_vop_setattr Casts uid_t at hammer_vnops.c:2211
		cur_uid Types uid_t at hammer_vnops.c:2213
		cur_uid Types uid_t at hammer_vnops.c:2356
[-] ucred.h (2)
	[-] Struct: ucred (2)
		[-] Struct: ucred (2)
			hammer_dounlink Uses ucred at hammer_vnops.c:156
			cred Types ucred at hammer_vnops.c:3282
[-] ufs_readwrite.c (12)
	[-] Macro: APPEND (2)
		hammer_vop_setattr Addr Uses APPEND at hammer_vnops.c:2200
		hammer_vop_setattr Addr Uses APPEND at hammer_vnops.c:2207
	[-] Macro: B_CLUSTEROK (3)
		hammer_vop_read Uses B_CLUSTEROK at hammer_vnops.c:437
		hammer_vop_write Uses B_CLUSTEROK at hammer_vnops.c:772
		hammer_vop_write Uses B_CLUSTEROK at hammer_vnops.c:824
	[-] Macro: IO_ASYNC (1)
		hammer_vop_write Addr Uses IO_ASYNC at hammer_vnops.c:830
	[-] Macro: IO_DIRECT (1)
		hammer_vop_write Addr Uses IO_DIRECT at hammer_vnops.c:828
	[-] Macro: VLASTWRITETS (5)
		hammer_vop_write Addr Uses VLASTWRITETS at hammer_vnops.c:535
		hammer_vop_write Uses VLASTWRITETS at hammer_vnops.c:542
		hammer_vop_setattr Uses VLASTWRITETS at hammer_vnops.c:2289
		hammer_vop_setattr Uses VLASTWRITETS at hammer_vnops.c:2334
		hammer_vop_setattr Uses VLASTWRITETS at hammer_vnops.c:2352
[-] usb_dev.c (6)
	[-] Macro: FILTEROP_ISFD (3)
		hammer_vnops.c Uses FILTEROP_ISFD at hammer_vnops.c:3531
		hammer_vnops.c Uses FILTEROP_ISFD at hammer_vnops.c:3534
		hammer_vnops.c Uses FILTEROP_ISFD at hammer_vnops.c:3537
	[-] Macro: FILTEROP_MPSAFE (3)
		hammer_vnops.c Uses FILTEROP_MPSAFE at hammer_vnops.c:3531
		hammer_vnops.c Uses FILTEROP_MPSAFE at hammer_vnops.c:3534
		hammer_vnops.c Uses FILTEROP_MPSAFE at hammer_vnops.c:3537
[-] utilities.c (5)
	[-] Function: bwrite (1)
		hammer_vop_write Calls bwrite at hammer_vnops.c:827
	[-] Function: getblk (4)
		hammer_vop_read Calls getblk at hammer_vnops.c:379
		hammer_vop_write Calls getblk at hammer_vnops.c:688
		hammer_vop_write Calls getblk at hammer_vnops.c:701
		hammer_vop_write Calls getblk at hammer_vnops.c:709
[-] vfs_bio.c (16)
	[-] Function: bawrite (2)
		hammer_vop_write Calls bawrite at hammer_vnops.c:829
		hammer_vop_write Calls bawrite at hammer_vnops.c:831
	[-] Function: bdwrite (1)
		hammer_vop_write Calls bdwrite at hammer_vnops.c:841
	[-] Function: bheavy (1)
		hammer_vop_write Calls bheavy at hammer_vnops.c:719
	[-] Function: biodone (5)
		hammer_vop_strategy Calls biodone at hammer_vnops.c:2617
		hammer_vop_strategy_read Calls biodone at hammer_vnops.c:2908
		hammer_vop_strategy_write Calls biodone at hammer_vnops.c:3193
		hammer_vop_strategy_write Calls biodone at hammer_vnops.c:3220
		hammer_vop_strategy_write Calls biodone at hammer_vnops.c:3269
	[-] Function: bqrelse (3)
		hammer_vop_read Calls bqrelse at hammer_vnops.c:386
		hammer_vop_read Calls bqrelse at hammer_vnops.c:454
		hammer_vop_write Calls bqrelse at hammer_vnops.c:691
	[-] Function: breadnx (1)
		hammer_vop_read Calls breadnx at hammer_vnops.c:420
	[-] Function: push_bio (1)
		hammer_vop_strategy_read Calls push_bio at hammer_vnops.c:2672
	[-] Function: vfs_bio_clrbuf (2)
		hammer_vop_write Calls vfs_bio_clrbuf at hammer_vnops.c:703
		hammer_vop_write Calls vfs_bio_clrbuf at hammer_vnops.c:711
[-] vfs_cache.c (16)
	[-] Function: cache_rename (1)
		hammer_vop_nrename Calls cache_rename at hammer_vnops.c:2065
	[-] Function: cache_setunresolved (5)
		hammer_vop_ncreate Calls cache_setunresolved at hammer_vnops.c:985
		hammer_vop_nlink Calls cache_setunresolved at hammer_vnops.c:1429
		hammer_vop_nmkdir Calls cache_setunresolved at hammer_vnops.c:1504
		hammer_vop_nmknod Calls cache_setunresolved at hammer_vnops.c:1581
		hammer_vop_nsymlink Calls cache_setunresolved at hammer_vnops.c:2470
	[-] Function: cache_setvp (9)
		hammer_vop_ncreate Calls cache_setvp at hammer_vnops.c:986
		hammer_vop_nresolve Calls cache_setvp at hammer_vnops.c:1177
		hammer_vop_nresolve Calls cache_setvp at hammer_vnops.c:1205
		hammer_vop_nresolve Calls cache_setvp at hammer_vnops.c:1290
		hammer_vop_nresolve Calls cache_setvp at hammer_vnops.c:1294
		hammer_vop_nlink Calls cache_setvp at hammer_vnops.c:1430
		hammer_vop_nmkdir Calls cache_setvp at hammer_vnops.c:1505
		hammer_vop_nmknod Calls cache_setvp at hammer_vnops.c:1582
		hammer_vop_nsymlink Calls cache_setvp at hammer_vnops.c:2471
	[-] Function: cache_unlink (1)
		hammer_dounlink Calls cache_unlink at hammer_vnops.c:3431
[-] vfs_cluster.c (2)
	[-] Function: cluster_readx (1)
		hammer_vop_read Calls cluster_readx at hammer_vnops.c:413
	[-] Function: cluster_write (1)
		hammer_vop_write Calls cluster_write at hammer_vnops.c:839
[-] vfs_default.c (4)
	[-] Function: vop_stdclose (1)
		hammer_vop_close Calls vop_stdclose at hammer_vnops.c:912
	[-] Function: vop_stdmountctl (2)
		hammer_vop_mountctl Calls vop_stdmountctl at hammer_vnops.c:2565
		hammer_vop_mountctl Calls vop_stdmountctl at hammer_vnops.c:2581
	[-] Function: vop_stdopen (1)
		hammer_vop_open Calls vop_stdopen at hammer_vnops.c:1607
[-] vfs_helper.c (7)
	[-] Function: vop_helper_access (1)
		hammer_vop_access Calls vop_helper_access at hammer_vnops.c:867
	[-] Function: vop_helper_chmod (1)
		hammer_vop_setattr Calls vop_helper_chmod at hammer_vnops.c:2359
	[-] Function: vop_helper_chown (1)
		hammer_vop_setattr Calls vop_helper_chown at hammer_vnops.c:2218
	[-] Function: vop_helper_read_shortcut (1)
		hammer_vop_read Calls vop_helper_read_shortcut at hammer_vnops.c:333
	[-] Function: vop_helper_setattr_flags (1)
		hammer_vop_setattr Calls vop_helper_setattr_flags at hammer_vnops.c:2190
	[-] Macro: IMMUTABLE (2)
		hammer_vop_setattr Addr Uses IMMUTABLE at hammer_vnops.c:2200
		hammer_vop_setattr Addr Uses IMMUTABLE at hammer_vnops.c:2207
[-] vfs_lock.c (11)
	[-] Function: vclrflags (4)
		hammer_vop_write Calls vclrflags at hammer_vnops.c:542
		hammer_vop_setattr Calls vclrflags at hammer_vnops.c:2289
		hammer_vop_setattr Calls vclrflags at hammer_vnops.c:2334
		hammer_vop_setattr Calls vclrflags at hammer_vnops.c:2352
	[-] Function: vrele (5)
		hammer_vop_nresolve Calls vrele at hammer_vnops.c:1178
		hammer_vop_nresolve Calls vrele at hammer_vnops.c:1206
		hammer_vop_nresolve Calls vrele at hammer_vnops.c:1291
		hammer_vop_nrename Calls vrele at hammer_vnops.c:2075
		hammer_dounlink Calls vrele at hammer_vnops.c:3459
	[-] Function: vx_lock (1)
		hammer_vop_fsync Calls vx_lock at hammer_vnops.c:288
	[-] Function: vx_unlock (1)
		hammer_vop_fsync Calls vx_unlock at hammer_vnops.c:281
[-] vfs_subr.c (8)
	[-] Function: vfs_flagstostr (1)
		hammer_vop_mountctl Calls vfs_flagstostr at hammer_vnops.c:2572
	[-] Function: vfsync (1)
		hammer_vop_fsync Calls vfsync at hammer_vnops.c:275
	[-] Function: vop_write_dirent (4)
		hammer_vop_readdir Calls vop_write_dirent at hammer_vnops.c:1670
		hammer_vop_readdir Calls vop_write_dirent at hammer_vnops.c:1682
		hammer_vop_readdir Calls vop_write_dirent at hammer_vnops.c:1686
		hammer_vop_readdir Calls vop_write_dirent at hammer_vnops.c:1732
	[-] Macro: B_PAGING (1)
		hammer_vop_strategy_read Addr Uses B_PAGING at hammer_vnops.c:2687
	[-] Macro: VRECLAIMED (1)
		hammer_vop_fsync Addr Uses VRECLAIMED at hammer_vnops.c:280
[-] vfs_sync.c (2)
	[-] Function: vclrisdirty (2)
		hammer_vop_fsync Calls vclrisdirty at hammer_vnops.c:241
		hammer_vop_fsync Calls vclrisdirty at hammer_vnops.c:291
[-] vfs_vm.c (6)
	[-] Function: nvextendbuf (2)
		hammer_vop_write Calls nvextendbuf at hammer_vnops.c:668
		hammer_vop_setattr Calls nvextendbuf at hammer_vnops.c:2274
	[-] Function: nvtruncbuf (2)
		hammer_vop_write Calls nvtruncbuf at hammer_vnops.c:761
		hammer_vop_setattr Calls nvtruncbuf at hammer_vnops.c:2267
	[-] Macro: NOOFFSET (2)
		hammer_vop_write Uses NOOFFSET at hammer_vnops.c:789
		hammer_vop_strategy_write Uses NOOFFSET at hammer_vnops.c:3266
[-] vfs_vnops.c (7)
	[-] Function: vn_unlock (5)
		hammer_vop_nresolve Calls vn_unlock at hammer_vnops.c:1176
		hammer_vop_nresolve Calls vn_unlock at hammer_vnops.c:1204
		hammer_vop_nresolve Calls vn_unlock at hammer_vnops.c:1289
		hammer_vop_nrename Calls vn_unlock at hammer_vnops.c:2073
		hammer_dounlink Calls vn_unlock at hammer_vnops.c:3449
	[-] Macro: IO_RECURSE (1)
		hammer_vop_write Addr Uses IO_RECURSE at hammer_vnops.c:645
	[-] Macro: VSWAPCACHE (1)
		hammer_vop_strategy_read Addr Uses VSWAPCACHE at hammer_vnops.c:2745
[-] vfscache.h (65)
	[-] Struct: vattr (65)
		[-] Object: va_atime (4)
			hammer_vop_getattr Addr Uses va_atime at hammer_vnops.c:1064
			hammer_vop_getattr Addr Uses va_atime at hammer_vnops.c:1067
			hammer_vop_setattr Uses va_atime at hammer_vnops.c:2343
			hammer_vop_setattr Addr Uses va_atime at hammer_vnops.c:2344
		[-] Object: va_blocksize (1)
			hammer_vop_getattr Sets va_blocksize at hammer_vnops.c:1073
		[-] Object: va_bytes (3)
			hammer_vop_getattr Sets va_bytes at hammer_vnops.c:1075
			hammer_vop_getattr Sets va_bytes at hammer_vnops.c:1077
			hammer_vop_getattr Sets va_bytes at hammer_vnops.c:1079
		[-] Object: va_ctime (1)
			hammer_vop_getattr Addr Uses va_ctime at hammer_vnops.c:1070
		[-] Object: va_fileid (1)
			hammer_vop_getattr Sets va_fileid at hammer_vnops.c:1029
		[-] Object: va_filerev (1)
			hammer_vop_getattr Sets va_filerev at hammer_vnops.c:1083
		[-] Object: va_flags (3)
			hammer_vop_getattr Sets va_flags at hammer_vnops.c:1071
			hammer_vop_setattr Uses va_flags at hammer_vnops.c:2188
			hammer_vop_setattr Uses va_flags at hammer_vnops.c:2190
		[-] Object: va_fsid (1)
			hammer_vop_getattr Sets va_fsid at hammer_vnops.c:1026
		[-] Object: va_fsid_uuid (1)
			hammer_vop_getattr Sets va_fsid_uuid at hammer_vnops.c:1086
		[-] Object: va_gen (1)
			hammer_vop_getattr Sets va_gen at hammer_vnops.c:1072
		[-] Object: va_gid (3)
			hammer_vop_getattr Sets va_gid at hammer_vnops.c:1033
			hammer_vop_setattr Uses va_gid at hammer_vnops.c:2211
			hammer_vop_setattr Uses va_gid at hammer_vnops.c:2218
		[-] Object: va_gid_uuid (1)
			hammer_vop_getattr Sets va_gid_uuid at hammer_vnops.c:1085
		[-] Object: va_mode (3)
			hammer_vop_getattr Sets va_mode at hammer_vnops.c:1030
			hammer_vop_setattr Uses va_mode at hammer_vnops.c:2354
			hammer_vop_setattr Uses va_mode at hammer_vnops.c:2359
		[-] Object: va_mtime (4)
			hammer_vop_getattr Addr Uses va_mtime at hammer_vnops.c:1065
			hammer_vop_getattr Addr Uses va_mtime at hammer_vnops.c:1068
			hammer_vop_setattr Uses va_mtime at hammer_vnops.c:2348
			hammer_vop_setattr Addr Uses va_mtime at hammer_vnops.c:2349
		[-] Object: va_nlink (1)
			hammer_vop_getattr Sets va_nlink at hammer_vnops.c:1031
		[-] Object: va_rmajor (2)
			hammer_vop_getattr Sets va_rmajor at hammer_vnops.c:1034
			hammer_vop_getattr Sets va_rmajor at hammer_vnops.c:1093
		[-] Object: va_rminor (2)
			hammer_vop_getattr Sets va_rminor at hammer_vnops.c:1035
			hammer_vop_getattr Sets va_rminor at hammer_vnops.c:1094
		[-] Object: va_size (24)
			hammer_vop_getattr Sets va_size at hammer_vnops.c:1036
			hammer_vop_getattr Sets va_size at hammer_vnops.c:1053
			hammer_vop_getattr Sets va_size at hammer_vnops.c:1055
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2236
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2236
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2239
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2255
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2259
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2266
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2267
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2269
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2276
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2278
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2280
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2285
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2297
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2300
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2302
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2303
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2325
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2327
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2328
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2330
			hammer_vop_setattr Uses va_size at hammer_vnops.c:2331
		[-] Object: va_type (1)
			hammer_vop_getattr Sets va_type at hammer_vnops.c:1082
		[-] Object: va_uid (3)
			hammer_vop_getattr Sets va_uid at hammer_vnops.c:1032
			hammer_vop_setattr Uses va_uid at hammer_vnops.c:2211
			hammer_vop_setattr Uses va_uid at hammer_vnops.c:2218
		[-] Object: va_uid_uuid (1)
			hammer_vop_getattr Sets va_uid_uuid at hammer_vnops.c:1084
		[-] Object: va_vaflags (1)
			hammer_vop_getattr Sets va_vaflags at hammer_vnops.c:1087
		[-] Struct: vattr (2)
			vap Types vattr at hammer_vnops.c:1009
			vap Types vattr at hammer_vnops.c:2157
[-] vfsops.h (353)
	[-] Struct: vop_access_args (3)
		[-] Object: a_vp (1)
			hammer_vop_access Uses a_vp at hammer_vnops.c:859
		[-] Struct: vop_access_args (2)
			hammer_vop_access Uses vop_access_args at hammer_vnops.c:48
			ap Types vop_access_args at hammer_vnops.c:857
	[-] Struct: vop_advlock_args (3)
		[-] Object: a_vp (1)
			hammer_vop_advlock Uses a_vp at hammer_vnops.c:881
		[-] Struct: vop_advlock_args (2)
			hammer_vop_advlock Uses vop_advlock_args at hammer_vnops.c:49
			ap Types vop_advlock_args at hammer_vnops.c:879
	[-] Struct: vop_bmap_args (25)
		[-] Object: a_cmd (1)
			hammer_vop_bmap Uses a_cmd at hammer_vnops.c:2988
		[-] Object: a_doffsetp (1)
			hammer_vop_bmap Uses a_doffsetp at hammer_vnops.c:3151
		[-] Object: a_loffset (13)
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3012
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3014
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3023
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3088
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3111
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3119
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3121
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3123
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3125
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3133
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3141
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3153
			hammer_vop_bmap Uses a_loffset at hammer_vnops.c:3157
		[-] Object: a_runb (4)
			hammer_vop_bmap Uses a_runb at hammer_vnops.c:3011
			hammer_vop_bmap Uses a_runb at hammer_vnops.c:3152
			hammer_vop_bmap Uses a_runb at hammer_vnops.c:3153
			hammer_vop_bmap Uses a_runb at hammer_vnops.c:3154
		[-] Object: a_runp (3)
			hammer_vop_bmap Uses a_runp at hammer_vnops.c:3156
			hammer_vop_bmap Uses a_runp at hammer_vnops.c:3157
			hammer_vop_bmap Uses a_runp at hammer_vnops.c:3158
		[-] Object: a_vp (1)
			hammer_vop_bmap Uses a_vp at hammer_vnops.c:2974
		[-] Struct: vop_bmap_args (2)
			hammer_vop_bmap Uses vop_bmap_args at hammer_vnops.c:68
			ap Types vop_bmap_args at hammer_vnops.c:2955
	[-] Struct: vop_close_args (5)
		[-] Object: a_head (1)
			hammer_vop_fifoclose Addr Uses a_head at hammer_vnops.c:3485
		[-] Struct: vop_close_args (4)
			hammer_vop_close Uses vop_close_args at hammer_vnops.c:50
			hammer_vop_fifoclose Uses vop_close_args at hammer_vnops.c:75
			ap Types vop_close_args at hammer_vnops.c:893
			ap Types vop_close_args at hammer_vnops.c:3482
	[-] Struct: vop_fsync_args (9)
		[-] Object: a_flags (1)
			hammer_vop_fsync Uses a_flags at hammer_vnops.c:192
		[-] Object: a_vp (5)
			hammer_vop_fsync Uses a_vp at hammer_vnops.c:181
			hammer_vop_fsync Uses a_vp at hammer_vnops.c:275
			hammer_vop_fsync Uses a_vp at hammer_vnops.c:280
			hammer_vop_fsync Uses a_vp at hammer_vnops.c:281
			hammer_vop_fsync Uses a_vp at hammer_vnops.c:288
		[-] Object: a_waitfor (1)
			hammer_vop_fsync Uses a_waitfor at hammer_vnops.c:183
		[-] Struct: vop_fsync_args (2)
			hammer_vop_fsync Uses vop_fsync_args at hammer_vnops.c:45
			ap Types vop_fsync_args at hammer_vnops.c:179
	[-] Struct: vop_getattr_args (4)
		[-] Object: a_vap (1)
			hammer_vop_getattr Uses a_vap at hammer_vnops.c:1009
		[-] Object: a_vp (1)
			hammer_vop_getattr Uses a_vp at hammer_vnops.c:1008
		[-] Struct: vop_getattr_args (2)
			hammer_vop_getattr Uses vop_getattr_args at hammer_vnops.c:52
			ap Types vop_getattr_args at hammer_vnops.c:1006
	[-] Struct: vop_ioctl_args (7)
		[-] Object: a_command (1)
			hammer_vop_ioctl Uses a_command at hammer_vnops.c:2522
		[-] Object: a_cred (1)
			hammer_vop_ioctl Uses a_cred at hammer_vnops.c:2523
		[-] Object: a_data (1)
			hammer_vop_ioctl Uses a_data at hammer_vnops.c:2522
		[-] Object: a_fflag (1)
			hammer_vop_ioctl Uses a_fflag at hammer_vnops.c:2523
		[-] Object: a_vp (1)
			hammer_vop_ioctl Uses a_vp at hammer_vnops.c:2517
		[-] Struct: vop_ioctl_args (2)
			hammer_vop_ioctl Uses vop_ioctl_args at hammer_vnops.c:71
			ap Types vop_ioctl_args at hammer_vnops.c:2515
	[-] Struct: vop_kqfilter_args (7)
		[-] Object: a_head (1)
			hammer_vop_fifokqfilter Addr Uses a_head at hammer_vnops.c:3514
		[-] Object: a_kn (1)
			hammer_vop_kqfilter Uses a_kn at hammer_vnops.c:3545
		[-] Object: a_vp (1)
			hammer_vop_kqfilter Uses a_vp at hammer_vnops.c:3544
		[-] Struct: vop_kqfilter_args (4)
			hammer_vop_kqfilter Uses vop_kqfilter_args at hammer_vnops.c:73
			hammer_vop_fifokqfilter Uses vop_kqfilter_args at hammer_vnops.c:78
			ap Types vop_kqfilter_args at hammer_vnops.c:3510
			ap Types vop_kqfilter_args at hammer_vnops.c:3542
	[-] Struct: vop_markatime_args (5)
		[-] Object: a_vp (3)
			hammer_vop_markatime Uses a_vp at hammer_vnops.c:2129
			hammer_vop_markatime Uses a_vp at hammer_vnops.c:2130
			hammer_vop_markatime Uses a_vp at hammer_vnops.c:2143
		[-] Struct: vop_markatime_args (2)
			hammer_vop_markatime Uses vop_markatime_args at hammer_vnops.c:65
			ap Types vop_markatime_args at hammer_vnops.c:2123
	[-] Struct: vop_mountctl_args (12)
		[-] Object: a_buf (1)
			hammer_vop_mountctl Uses a_buf at hammer_vnops.c:2573
		[-] Object: a_buflen (2)
			hammer_vop_mountctl Uses a_buflen at hammer_vnops.c:2571
			hammer_vop_mountctl Uses a_buflen at hammer_vnops.c:2574
		[-] Object: a_ctl (1)
			hammer_vop_mountctl Uses a_ctl at hammer_vnops.c:2558
		[-] Object: a_ctllen (1)
			hammer_vop_mountctl Uses a_ctllen at hammer_vnops.c:2554
		[-] Object: a_head (1)
			hammer_vop_mountctl Uses a_head at hammer_vnops.c:2546
		[-] Object: a_op (2)
			hammer_vop_mountctl Uses a_op at hammer_vnops.c:2552
			hammer_vop_mountctl Uses a_op at hammer_vnops.c:2557
		[-] Object: a_res (2)
			hammer_vop_mountctl Uses a_res at hammer_vnops.c:2569
			hammer_vop_mountctl Uses a_res at hammer_vnops.c:2578
		[-] Struct: vop_mountctl_args (2)
			hammer_vop_mountctl Uses vop_mountctl_args at hammer_vnops.c:72
			ap Types vop_mountctl_args at hammer_vnops.c:2530
	[-] Struct: vop_ncreate_args (13)
		[-] Object: a_cred (1)
			hammer_vop_ncreate Uses a_cred at hammer_vnops.c:952
		[-] Object: a_dvp (2)
			hammer_vop_ncreate Uses a_dvp at hammer_vnops.c:933
			hammer_vop_ncreate Uses a_dvp at hammer_vnops.c:988
		[-] Object: a_nch (3)
			hammer_vop_ncreate Uses a_nch at hammer_vnops.c:932
			hammer_vop_ncreate Uses a_nch at hammer_vnops.c:985
			hammer_vop_ncreate Uses a_nch at hammer_vnops.c:986
		[-] Object: a_vap (1)
			hammer_vop_ncreate Uses a_vap at hammer_vnops.c:952
		[-] Object: a_vpp (4)
			hammer_vop_ncreate Uses a_vpp at hammer_vnops.c:958
			hammer_vop_ncreate Uses a_vpp at hammer_vnops.c:979
			hammer_vop_ncreate Uses a_vpp at hammer_vnops.c:981
			hammer_vop_ncreate Uses a_vpp at hammer_vnops.c:986
		[-] Struct: vop_ncreate_args (2)
			hammer_vop_ncreate Uses vop_ncreate_args at hammer_vnops.c:51
			ap Types vop_ncreate_args at hammer_vnops.c:923
	[-] Struct: vop_nlink_args (10)
		[-] Object: a_dvp (3)
			hammer_vop_nlink Uses a_dvp at hammer_vnops.c:1392
			hammer_vop_nlink Uses a_dvp at hammer_vnops.c:1396
			hammer_vop_nlink Uses a_dvp at hammer_vnops.c:1434
		[-] Object: a_nch (1)
			hammer_vop_nlink Uses a_nch at hammer_vnops.c:1395
		[-] Object: a_vp (4)
			hammer_vop_nlink Uses a_vp at hammer_vnops.c:1392
			hammer_vop_nlink Uses a_vp at hammer_vnops.c:1397
			hammer_vop_nlink Uses a_vp at hammer_vnops.c:1430
			hammer_vop_nlink Uses a_vp at hammer_vnops.c:1433
		[-] Struct: vop_nlink_args (2)
			hammer_vop_nlink Uses vop_nlink_args at hammer_vnops.c:55
			ap Types vop_nlink_args at hammer_vnops.c:1383
	[-] Struct: vop_nlookupdotdot_args (8)
		[-] Object: a_dvp (1)
			hammer_vop_nlookupdotdot Uses a_dvp at hammer_vnops.c:1329
		[-] Object: a_fakename (2)
			hammer_vop_nlookupdotdot Uses a_fakename at hammer_vnops.c:1352
			hammer_vop_nlookupdotdot Uses a_fakename at hammer_vnops.c:1353
		[-] Object: a_vpp (3)
			hammer_vop_nlookupdotdot Uses a_vpp at hammer_vnops.c:1356
			hammer_vop_nlookupdotdot Uses a_vpp at hammer_vnops.c:1368
			hammer_vop_nlookupdotdot Uses a_vpp at hammer_vnops.c:1371
		[-] Struct: vop_nlookupdotdot_args (2)
			hammer_vop_nlookupdotdot Uses vop_nlookupdotdot_args at hammer_vnops.c:54
			ap Types vop_nlookupdotdot_args at hammer_vnops.c:1318
	[-] Struct: vop_nmkdir_args (13)
		[-] Object: a_cred (1)
			hammer_vop_nmkdir Uses a_cred at hammer_vnops.c:1475
		[-] Object: a_dvp (2)
			hammer_vop_nmkdir Uses a_dvp at hammer_vnops.c:1457
			hammer_vop_nmkdir Uses a_dvp at hammer_vnops.c:1510
		[-] Object: a_nch (3)
			hammer_vop_nmkdir Uses a_nch at hammer_vnops.c:1456
			hammer_vop_nmkdir Uses a_nch at hammer_vnops.c:1504
			hammer_vop_nmkdir Uses a_nch at hammer_vnops.c:1505
		[-] Object: a_vap (1)
			hammer_vop_nmkdir Uses a_vap at hammer_vnops.c:1475
		[-] Object: a_vpp (4)
			hammer_vop_nmkdir Uses a_vpp at hammer_vnops.c:1480
			hammer_vop_nmkdir Uses a_vpp at hammer_vnops.c:1499
			hammer_vop_nmkdir Uses a_vpp at hammer_vnops.c:1501
			hammer_vop_nmkdir Uses a_vpp at hammer_vnops.c:1505
		[-] Struct: vop_nmkdir_args (2)
			hammer_vop_nmkdir Uses vop_nmkdir_args at hammer_vnops.c:56
			ap Types vop_nmkdir_args at hammer_vnops.c:1447
	[-] Struct: vop_nmknod_args (13)
		[-] Object: a_cred (1)
			hammer_vop_nmknod Uses a_cred at hammer_vnops.c:1553
		[-] Object: a_dvp (2)
			hammer_vop_nmknod Uses a_dvp at hammer_vnops.c:1533
			hammer_vop_nmknod Uses a_dvp at hammer_vnops.c:1587
		[-] Object: a_nch (3)
			hammer_vop_nmknod Uses a_nch at hammer_vnops.c:1532
			hammer_vop_nmknod Uses a_nch at hammer_vnops.c:1581
			hammer_vop_nmknod Uses a_nch at hammer_vnops.c:1582
		[-] Object: a_vap (1)
			hammer_vop_nmknod Uses a_vap at hammer_vnops.c:1553
		[-] Object: a_vpp (4)
			hammer_vop_nmknod Uses a_vpp at hammer_vnops.c:1558
			hammer_vop_nmknod Uses a_vpp at hammer_vnops.c:1576
			hammer_vop_nmknod Uses a_vpp at hammer_vnops.c:1578
			hammer_vop_nmknod Uses a_vpp at hammer_vnops.c:1582
		[-] Struct: vop_nmknod_args (2)
			hammer_vop_nmknod Uses vop_nmknod_args at hammer_vnops.c:57
			ap Types vop_nmknod_args at hammer_vnops.c:1523
	[-] Struct: vop_nremove_args (7)
		[-] Object: a_cred (1)
			hammer_vop_nremove Uses a_cred at hammer_vnops.c:1909
		[-] Object: a_dvp (3)
			hammer_vop_nremove Uses a_dvp at hammer_vnops.c:1899
			hammer_vop_nremove Uses a_dvp at hammer_vnops.c:1909
			hammer_vop_nremove Uses a_dvp at hammer_vnops.c:1912
		[-] Object: a_nch (1)
			hammer_vop_nremove Uses a_nch at hammer_vnops.c:1909
		[-] Struct: vop_nremove_args (2)
			hammer_vop_nremove Uses vop_nremove_args at hammer_vnops.c:62
			ap Types vop_nremove_args at hammer_vnops.c:1892
	[-] Struct: vop_nrename_args (17)
		[-] Object: a_cred (1)
			hammer_vop_nrename Uses a_cred at hammer_vnops.c:1975
		[-] Object: a_fdvp (4)
			hammer_vop_nrename Uses a_fdvp at hammer_vnops.c:1936
			hammer_vop_nrename Uses a_fdvp at hammer_vnops.c:1938
			hammer_vop_nrename Uses a_fdvp at hammer_vnops.c:1941
			hammer_vop_nrename Uses a_fdvp at hammer_vnops.c:2066
		[-] Object: a_fnch (3)
			hammer_vop_nrename Uses a_fnch at hammer_vnops.c:1938
			hammer_vop_nrename Uses a_fnch at hammer_vnops.c:1943
			hammer_vop_nrename Uses a_fnch at hammer_vnops.c:2065
		[-] Object: a_tdvp (4)
			hammer_vop_nrename Uses a_tdvp at hammer_vnops.c:1936
			hammer_vop_nrename Uses a_tdvp at hammer_vnops.c:1942
			hammer_vop_nrename Uses a_tdvp at hammer_vnops.c:1974
			hammer_vop_nrename Uses a_tdvp at hammer_vnops.c:2067
		[-] Object: a_tnch (3)
			hammer_vop_nrename Uses a_tnch at hammer_vnops.c:1944
			hammer_vop_nrename Uses a_tnch at hammer_vnops.c:1974
			hammer_vop_nrename Uses a_tnch at hammer_vnops.c:2065
		[-] Struct: vop_nrename_args (2)
			hammer_vop_nrename Uses vop_nrename_args at hammer_vnops.c:63
			ap Types vop_nrename_args at hammer_vnops.c:1922
	[-] Struct: vop_nresolve_args (8)
		[-] Object: a_dvp (1)
			hammer_vop_nresolve Uses a_dvp at hammer_vnops.c:1135
		[-] Object: a_nch (5)
			hammer_vop_nresolve Uses a_nch at hammer_vnops.c:1136
			hammer_vop_nresolve Uses a_nch at hammer_vnops.c:1177
			hammer_vop_nresolve Uses a_nch at hammer_vnops.c:1205
			hammer_vop_nresolve Uses a_nch at hammer_vnops.c:1290
			hammer_vop_nresolve Uses a_nch at hammer_vnops.c:1294
		[-] Struct: vop_nresolve_args (2)
			hammer_vop_nresolve Uses vop_nresolve_args at hammer_vnops.c:53
			ap Types vop_nresolve_args at hammer_vnops.c:1110
	[-] Struct: vop_nrmdir_args (7)
		[-] Object: a_cred (1)
			hammer_vop_nrmdir Uses a_cred at hammer_vnops.c:2110
		[-] Object: a_dvp (3)
			hammer_vop_nrmdir Uses a_dvp at hammer_vnops.c:2100
			hammer_vop_nrmdir Uses a_dvp at hammer_vnops.c:2110
			hammer_vop_nrmdir Uses a_dvp at hammer_vnops.c:2113
		[-] Object: a_nch (1)
			hammer_vop_nrmdir Uses a_nch at hammer_vnops.c:2110
		[-] Struct: vop_nrmdir_args (2)
			hammer_vop_nrmdir Uses vop_nrmdir_args at hammer_vnops.c:64
			ap Types vop_nrmdir_args at hammer_vnops.c:2093
	[-] Struct: vop_nsymlink_args (17)
		[-] Object: a_cred (1)
			hammer_vop_nsymlink Uses a_cred at hammer_vnops.c:2415
		[-] Object: a_dvp (2)
			hammer_vop_nsymlink Uses a_dvp at hammer_vnops.c:2396
			hammer_vop_nsymlink Uses a_dvp at hammer_vnops.c:2472
		[-] Object: a_nch (3)
			hammer_vop_nsymlink Uses a_nch at hammer_vnops.c:2395
			hammer_vop_nsymlink Uses a_nch at hammer_vnops.c:2470
			hammer_vop_nsymlink Uses a_nch at hammer_vnops.c:2471
		[-] Object: a_target (3)
			hammer_vop_nsymlink Uses a_target at hammer_vnops.c:2430
			hammer_vop_nsymlink Uses a_target at hammer_vnops.c:2433
			hammer_vop_nsymlink Uses a_target at hammer_vnops.c:2444
		[-] Object: a_vap (2)
			hammer_vop_nsymlink Uses a_vap at hammer_vnops.c:2393
			hammer_vop_nsymlink Uses a_vap at hammer_vnops.c:2415
		[-] Object: a_vpp (4)
			hammer_vop_nsymlink Uses a_vpp at hammer_vnops.c:2420
			hammer_vop_nsymlink Uses a_vpp at hammer_vnops.c:2465
			hammer_vop_nsymlink Uses a_vpp at hammer_vnops.c:2467
			hammer_vop_nsymlink Uses a_vpp at hammer_vnops.c:2471
		[-] Struct: vop_nsymlink_args (2)
			hammer_vop_nsymlink Uses vop_nsymlink_args at hammer_vnops.c:69
			ap Types vop_nsymlink_args at hammer_vnops.c:2382
	[-] Struct: vop_nwhiteout_args (7)
		[-] Object: a_cred (1)
			hammer_vop_nwhiteout Uses a_cred at hammer_vnops.c:2503
		[-] Object: a_dvp (2)
			hammer_vop_nwhiteout Uses a_dvp at hammer_vnops.c:2492
			hammer_vop_nwhiteout Uses a_dvp at hammer_vnops.c:2502
		[-] Object: a_flags (1)
			hammer_vop_nwhiteout Uses a_flags at hammer_vnops.c:2503
		[-] Object: a_nch (1)
			hammer_vop_nwhiteout Uses a_nch at hammer_vnops.c:2502
		[-] Struct: vop_nwhiteout_args (2)
			hammer_vop_nwhiteout Uses vop_nwhiteout_args at hammer_vnops.c:70
			ap Types vop_nwhiteout_args at hammer_vnops.c:2485
	[-] Struct: vop_open_args (4)
		[-] Object: a_mode (1)
			hammer_vop_open Uses a_mode at hammer_vnops.c:1605
		[-] Object: a_vp (1)
			hammer_vop_open Uses a_vp at hammer_vnops.c:1603
		[-] Struct: vop_open_args (2)
			hammer_vop_open Uses vop_open_args at hammer_vnops.c:58
			ap Types vop_open_args at hammer_vnops.c:1599
	[-] Struct: vop_ops (61)
		[-] Object: vop_access (3)
			hammer_vnops.c Inits vop_access at hammer_vnops.c:87
			hammer_vnops.c Inits vop_access at hammer_vnops.c:123
			hammer_vnops.c Inits vop_access at hammer_vnops.c:137
		[-] Object: vop_advlock (1)
			hammer_vnops.c Inits vop_advlock at hammer_vnops.c:88
		[-] Object: vop_bmap (1)
			hammer_vnops.c Inits vop_bmap at hammer_vnops.c:109
		[-] Object: vop_close (3)
			hammer_vnops.c Inits vop_close at hammer_vnops.c:89
			hammer_vnops.c Inits vop_close at hammer_vnops.c:124
			hammer_vnops.c Inits vop_close at hammer_vnops.c:138
		[-] Object: vop_default (3)
			hammer_vnops.c Inits vop_default at hammer_vnops.c:81
			hammer_vnops.c Inits vop_default at hammer_vnops.c:119
			hammer_vnops.c Inits vop_default at hammer_vnops.c:133
		[-] Object: vop_fsync (3)
			hammer_vnops.c Inits vop_fsync at hammer_vnops.c:82
			hammer_vnops.c Inits vop_fsync at hammer_vnops.c:120
			hammer_vnops.c Inits vop_fsync at hammer_vnops.c:134
		[-] Object: vop_getattr (3)
			hammer_vnops.c Inits vop_getattr at hammer_vnops.c:91
			hammer_vnops.c Inits vop_getattr at hammer_vnops.c:126
			hammer_vnops.c Inits vop_getattr at hammer_vnops.c:140
		[-] Object: vop_getpages (1)
			hammer_vnops.c Inits vop_getpages at hammer_vnops.c:83
		[-] Object: vop_inactive (3)
			hammer_vnops.c Inits vop_inactive at hammer_vnops.c:92
			hammer_vnops.c Inits vop_inactive at hammer_vnops.c:127
			hammer_vnops.c Inits vop_inactive at hammer_vnops.c:141
		[-] Object: vop_ioctl (1)
			hammer_vnops.c Inits vop_ioctl at hammer_vnops.c:113
		[-] Object: vop_kqfilter (2)
			hammer_vnops.c Inits vop_kqfilter at hammer_vnops.c:115
			hammer_vnops.c Inits vop_kqfilter at hammer_vnops.c:144
		[-] Object: vop_markatime (3)
			hammer_vnops.c Inits vop_markatime at hammer_vnops.c:107
			hammer_vnops.c Inits vop_markatime at hammer_vnops.c:125
			hammer_vnops.c Inits vop_markatime at hammer_vnops.c:139
		[-] Object: vop_mountctl (1)
			hammer_vnops.c Inits vop_mountctl at hammer_vnops.c:114
		[-] Object: vop_ncreate (1)
			hammer_vnops.c Inits vop_ncreate at hammer_vnops.c:90
		[-] Object: vop_nlink (1)
			hammer_vnops.c Inits vop_nlink at hammer_vnops.c:96
		[-] Object: vop_nlookupdotdot (1)
			hammer_vnops.c Inits vop_nlookupdotdot at hammer_vnops.c:95
		[-] Object: vop_nmkdir (1)
			hammer_vnops.c Inits vop_nmkdir at hammer_vnops.c:97
		[-] Object: vop_nmknod (1)
			hammer_vnops.c Inits vop_nmknod at hammer_vnops.c:98
		[-] Object: vop_nremove (1)
			hammer_vnops.c Inits vop_nremove at hammer_vnops.c:104
		[-] Object: vop_nrename (1)
			hammer_vnops.c Inits vop_nrename at hammer_vnops.c:105
		[-] Object: vop_nresolve (1)
			hammer_vnops.c Inits vop_nresolve at hammer_vnops.c:94
		[-] Object: vop_nrmdir (1)
			hammer_vnops.c Inits vop_nrmdir at hammer_vnops.c:106
		[-] Object: vop_nsymlink (1)
			hammer_vnops.c Inits vop_nsymlink at hammer_vnops.c:111
		[-] Object: vop_nwhiteout (1)
			hammer_vnops.c Inits vop_nwhiteout at hammer_vnops.c:112
		[-] Object: vop_open (1)
			hammer_vnops.c Inits vop_open at hammer_vnops.c:99
		[-] Object: vop_pathconf (1)
			hammer_vnops.c Inits vop_pathconf at hammer_vnops.c:100
		[-] Object: vop_print (1)
			hammer_vnops.c Inits vop_print at hammer_vnops.c:101
		[-] Object: vop_putpages (1)
			hammer_vnops.c Inits vop_putpages at hammer_vnops.c:84
		[-] Object: vop_read (3)
			hammer_vnops.c Inits vop_read at hammer_vnops.c:85
			hammer_vnops.c Inits vop_read at hammer_vnops.c:121
			hammer_vnops.c Inits vop_read at hammer_vnops.c:135
		[-] Object: vop_readdir (1)
			hammer_vnops.c Inits vop_readdir at hammer_vnops.c:102
		[-] Object: vop_readlink (1)
			hammer_vnops.c Inits vop_readlink at hammer_vnops.c:103
		[-] Object: vop_reclaim (3)
			hammer_vnops.c Inits vop_reclaim at hammer_vnops.c:93
			hammer_vnops.c Inits vop_reclaim at hammer_vnops.c:128
			hammer_vnops.c Inits vop_reclaim at hammer_vnops.c:142
		[-] Object: vop_setattr (3)
			hammer_vnops.c Inits vop_setattr at hammer_vnops.c:108
			hammer_vnops.c Inits vop_setattr at hammer_vnops.c:129
			hammer_vnops.c Inits vop_setattr at hammer_vnops.c:143
		[-] Object: vop_strategy (1)
			hammer_vnops.c Inits vop_strategy at hammer_vnops.c:110
		[-] Object: vop_write (3)
			hammer_vnops.c Inits vop_write at hammer_vnops.c:86
			hammer_vnops.c Inits vop_write at hammer_vnops.c:122
			hammer_vnops.c Inits vop_write at hammer_vnops.c:136
		[-] Struct: vop_ops (3)
			hammer_vnode_vops Types vop_ops at hammer_vnops.c:80
			hammer_spec_vops Types vop_ops at hammer_vnops.c:118
			hammer_fifo_vops Types vop_ops at hammer_vnops.c:132
	[-] Struct: vop_print_args (2)
		[-] Struct: vop_print_args (2)
			hammer_vop_print Uses vop_print_args at hammer_vnops.c:59
			ap Types vop_print_args at hammer_vnops.c:1615
	[-] Struct: vop_read_args (13)
		[-] Object: a_head (1)
			hammer_vop_fiforead Addr Uses a_head at hammer_vnops.c:3493
		[-] Object: a_ioflag (2)
			hammer_vop_read Uses a_ioflag at hammer_vnops.c:345
			hammer_vop_read Uses a_ioflag at hammer_vnops.c:385
		[-] Object: a_uio (1)
			hammer_vop_read Uses a_uio at hammer_vnops.c:326
		[-] Object: a_vp (5)
			hammer_vop_read Uses a_vp at hammer_vnops.c:320
			hammer_vop_read Uses a_vp at hammer_vnops.c:322
			hammer_vop_read Uses a_vp at hammer_vnops.c:379
			hammer_vop_read Uses a_vp at hammer_vnops.c:413
			hammer_vop_read Uses a_vp at hammer_vnops.c:420
		[-] Struct: vop_read_args (4)
			hammer_vop_read Uses vop_read_args at hammer_vnops.c:46
			hammer_vop_fiforead Uses vop_read_args at hammer_vnops.c:76
			ap Types vop_read_args at hammer_vnops.c:303
			ap Types vop_read_args at hammer_vnops.c:3489
	[-] Struct: vop_readdir_args (11)
		[-] Object: a_cookies (2)
			hammer_vop_readdir Uses a_cookies at hammer_vnops.c:1761
			hammer_vop_readdir Uses a_cookies at hammer_vnops.c:1768
		[-] Object: a_eofflag (2)
			hammer_vop_readdir Uses a_eofflag at hammer_vnops.c:1752
			hammer_vop_readdir Uses a_eofflag at hammer_vnops.c:1753
		[-] Object: a_ncookies (3)
			hammer_vop_readdir Uses a_ncookies at hammer_vnops.c:1646
			hammer_vop_readdir Uses a_ncookies at hammer_vnops.c:1760
			hammer_vop_readdir Uses a_ncookies at hammer_vnops.c:1767
		[-] Object: a_uio (1)
			hammer_vop_readdir Uses a_uio at hammer_vnops.c:1642
		[-] Object: a_vp (1)
			hammer_vop_readdir Uses a_vp at hammer_vnops.c:1641
		[-] Struct: vop_readdir_args (2)
			hammer_vop_readdir Uses vop_readdir_args at hammer_vnops.c:60
			ap Types vop_readdir_args at hammer_vnops.c:1625
	[-] Struct: vop_readlink_args (5)
		[-] Object: a_uio (2)
			hammer_vop_readlink Uses a_uio at hammer_vnops.c:1843
			hammer_vop_readlink Uses a_uio at hammer_vnops.c:1878
		[-] Object: a_vp (1)
			hammer_vop_readlink Uses a_vp at hammer_vnops.c:1791
		[-] Struct: vop_readlink_args (2)
			hammer_vop_readlink Uses vop_readlink_args at hammer_vnops.c:61
			ap Types vop_readlink_args at hammer_vnops.c:1780
	[-] Struct: vop_setattr_args (17)
		[-] Object: a_cred (3)
			hammer_vop_setattr Uses a_cred at hammer_vnops.c:2192
			hammer_vop_setattr Uses a_cred at hammer_vnops.c:2219
			hammer_vop_setattr Uses a_cred at hammer_vnops.c:2359
		[-] Object: a_vap (1)
			hammer_vop_setattr Uses a_vap at hammer_vnops.c:2169
		[-] Object: a_vp (11)
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2170
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2175
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2218
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2237
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2267
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2274
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2289
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2334
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2352
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2359
			hammer_vop_setattr Uses a_vp at hammer_vnops.c:2372
		[-] Struct: vop_setattr_args (2)
			hammer_vop_setattr Uses vop_setattr_args at hammer_vnops.c:66
			ap Types vop_setattr_args at hammer_vnops.c:2153
	[-] Struct: vop_strategy_args (17)
		[-] Object: a_bio (8)
			hammer_vop_strategy Uses a_bio at hammer_vnops.c:2605
			hammer_vop_strategy Uses a_bio at hammer_vnops.c:2617
			hammer_vop_strategy_read Uses a_bio at hammer_vnops.c:2657
			hammer_vop_strategy_read Uses a_bio at hammer_vnops.c:2908
			hammer_vop_strategy_write Uses a_bio at hammer_vnops.c:3182
			hammer_vop_strategy_write Uses a_bio at hammer_vnops.c:3193
			hammer_vop_strategy_write Uses a_bio at hammer_vnops.c:3220
			hammer_vop_strategy_write Uses a_bio at hammer_vnops.c:3269
		[-] Object: a_vp (3)
			hammer_vop_strategy_read Uses a_vp at hammer_vnops.c:2659
			hammer_vop_strategy_read Uses a_vp at hammer_vnops.c:2745
			hammer_vop_strategy_write Uses a_vp at hammer_vnops.c:3184
		[-] Struct: vop_strategy_args (6)
			hammer_vop_strategy Uses vop_strategy_args at hammer_vnops.c:67
			hammer_vop_strategy_read Uses vop_strategy_args at hammer_vnops.c:158
			hammer_vop_strategy_write Uses vop_strategy_args at hammer_vnops.c:159
			ap Types vop_strategy_args at hammer_vnops.c:2600
			ap Types vop_strategy_args at hammer_vnops.c:2636
			ap Types vop_strategy_args at hammer_vnops.c:3171
	[-] Struct: vop_write_args (23)
		[-] Object: a_head (1)
			hammer_vop_fifowrite Addr Uses a_head at hammer_vnops.c:3503
		[-] Object: a_ioflag (6)
			hammer_vop_write Uses a_ioflag at hammer_vnops.c:519
			hammer_vop_write Uses a_ioflag at hammer_vnops.c:548
			hammer_vop_write Uses a_ioflag at hammer_vnops.c:645
			hammer_vop_write Uses a_ioflag at hammer_vnops.c:826
			hammer_vop_write Uses a_ioflag at hammer_vnops.c:828
			hammer_vop_write Uses a_ioflag at hammer_vnops.c:830
		[-] Object: a_uio (1)
			hammer_vop_write Uses a_uio at hammer_vnops.c:528
		[-] Object: a_vp (11)
			hammer_vop_write Uses a_vp at hammer_vnops.c:512
			hammer_vop_write Uses a_vp at hammer_vnops.c:515
			hammer_vop_write Uses a_vp at hammer_vnops.c:668
			hammer_vop_write Uses a_vp at hammer_vnops.c:688
			hammer_vop_write Uses a_vp at hammer_vnops.c:692
			hammer_vop_write Uses a_vp at hammer_vnops.c:701
			hammer_vop_write Uses a_vp at hammer_vnops.c:709
			hammer_vop_write Uses a_vp at hammer_vnops.c:717
			hammer_vop_write Uses a_vp at hammer_vnops.c:761
			hammer_vop_write Uses a_vp at hammer_vnops.c:833
			hammer_vop_write Uses a_vp at hammer_vnops.c:845
		[-] Struct: vop_write_args (4)
			hammer_vop_write Uses vop_write_args at hammer_vnops.c:47
			hammer_vop_fifowrite Uses vop_write_args at hammer_vnops.c:77
			ap Types vop_write_args at hammer_vnops.c:493
			ap Types vop_write_args at hammer_vnops.c:3499
[-] vnode.h (1)
	[-] Macro: IO_NRDELAY (1)
		hammer_vop_read Addr Uses IO_NRDELAY at hammer_vnops.c:385



---



hammer_volume.c (30)



[-] _null.h (15)
	[-] Macro: NULL (15)
		hammer_ioc_volume_add Uses NULL at hammer_volume.c:107
		hammer_ioc_volume_add Uses NULL at hammer_volume.c:115
		hammer_ioc_volume_del Uses NULL at hammer_volume.c:178
		hammer_ioc_volume_del Uses NULL at hammer_volume.c:181
		hammer_ioc_volume_del Uses NULL at hammer_volume.c:186
		hammer_ioc_volume_del Uses NULL at hammer_volume.c:189
		hammer_ioc_volume_del Uses NULL at hammer_volume.c:262
		hammer_ioc_volume_list Uses NULL at hammer_volume.c:308
		hammer_format_freemap Uses NULL at hammer_volume.c:393
		hammer_format_freemap Uses NULL at hammer_volume.c:394
		hammer_free_freemap Uses NULL at hammer_volume.c:511
		hammer_free_freemap Uses NULL at hammer_volume.c:512
		hammer_update_volumes_header Uses NULL at hammer_volume.c:684
		hammer_count_bigblocks Uses NULL at hammer_volume.c:759
		hammer_count_bigblocks Uses NULL at hammer_volume.c:760
[-] memset.c (7)
	[-] Function: bzero (7)
		hammer_ioc_volume_del Calls bzero at hammer_volume.c:265
		hammer_do_reblock Calls bzero at hammer_volume.c:337
		hammer_format_freemap Calls bzero at hammer_volume.c:423
		hammer_format_freemap Calls bzero at hammer_volume.c:453
		hammer_free_freemap Calls bzero at hammer_volume.c:590
		hammer_free_freemap Calls bzero at hammer_volume.c:597
		hammer_format_volume_header Calls bzero at hammer_volume.c:627
[-] mount.h (2)
	[-] Macro: MNT_RDONLY (2)
		hammer_ioc_volume_add Uses MNT_RDONLY at hammer_volume.c:74
		hammer_ioc_volume_del Uses MNT_RDONLY at hammer_volume.c:159
[-] param.h (1)
	[-] Macro: MAXPATHLEN (1)
		hammer_ioc_volume_list Uses MAXPATHLEN at hammer_volume.c:311
[-] strlen.c (1)
	[-] Function: strlen (1)
		hammer_ioc_volume_list Calls strlen at hammer_volume.c:310
[-] subr_prf.c (3)
	[-] Function: kprintf (2)
		hammer_ioc_volume_del Calls kprintf at hammer_volume.c:238
		hammer_ioc_volume_del Calls kprintf at hammer_volume.c:240
	[-] Function: ksnprintf (1)
		hammer_format_volume_header Calls ksnprintf at hammer_volume.c:630
[-] tree.h (1)
	[-] Macro: RB_SCAN (1)
		hammer_ioc_volume_del Uses RB_SCAN at hammer_volume.c:262

