HAMMER interfaces with the operating system through two major subsystems.
On the front-end Hammer implements the DragonFly VNOPS API. On the back-
end (though also the front-end due to the direct-read/direct-write bypass feature)
Hammer uses the kernel's buffer cache for both v-node-related operations and
for block device operations.

HAMMER’s front-end operations are completely decoupled from back-end operations, including for rename and truncation, and front-end bulk writes are able to reserve space on the media without modifying the storage allocation layer and thus issue bulk writes directly to the media from the front-end. The back-end then deals with updating the B-Tree after the fact.[^hammer.pdf: Section 1 – Overview]

Kernels which do not deal with atomicy and name-space guarantees will
need to implement a layer TO guarantee them before dropping into
Hammer's VNOPS code.[^hammer.pdf: Section 13 - Porting]

