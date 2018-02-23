Lineage eXTenDed Kernel los-15.1-slim source Changelog:
============================================================

02-14-2018
====================

* [83d41b0 Up version R5](https://github.com/ppajda/kernel_g3/commit/83d41b00d8581aa96340d2f84d8130ee00181de9)
* [8880d2b kgsl: fix derp](https://github.com/ppajda/kernel_g3/commit/8880d2b4fb57ec90a742424970cea802de5dfdf3)
* [1464bbd proc: modify cmdline to export correct charger mode](https://github.com/ppajda/kernel_g3/commit/1464bbd864f6678c7b99d858c71a2e532308743f)
* [1a2d497 ANDROID: xattr: Pass EOPNOTSUPP to permission2](https://github.com/ppajda/kernel_g3/commit/1a2d49767fffdca534609b88b3c45e8f70a584f9)
* [d597759 Enable setting security contexts on rootfs inodes.](https://github.com/ppajda/kernel_g3/commit/d59775920cdb822304924585a7d04df053e6ae17)
* [75bb63a selinux: enable genfscon labeling for sysfs and pstore files](https://github.com/ppajda/kernel_g3/commit/75bb63a0fc13397aaa9a25889dcdaf5105a12e4f)
* [d132630 selinux: enable per-file labeling for debugfs files.](https://github.com/ppajda/kernel_g3/commit/d132630bb927ec27100f5372a061b93324150b4b)
* [81d2f0a defconfigs: cleanup](https://github.com/ppajda/kernel_g3/commit/81d2f0ae923f1051b0a6fc00326021879a92f0bb)
* [4754e24 usb: gadget: fix build](https://github.com/ppajda/kernel_g3/commit/4754e24dc96c05165c7d183de99502c85f5c5437)
* [88782a1 Revert "usb: gadget: f_hid: fix build error"](https://github.com/ppajda/kernel_g3/commit/88782a1a01be05220d323a8d882e88158d64464e)
* [4831619 defconfig: Disable CONFIG_MSM_SMP2P_TEST](https://github.com/ppajda/kernel_g3/commit/4831619d45552a52bf5a48fc59b44459156e6076)
* [05c79374 defconfig: Disable perf events](https://github.com/ppajda/kernel_g3/commit/05c79374c6a0884e921b21b2a71af19e2d0c12d9)

***

01-29-2018
====================


***

01-27-2018
====================

* [0ce9a99 include: Include dummy MSM Audio Calibration header * This needs to be included in apq8084/msm8974 kernel's exported headers to build the msm audio hal as of oreo-mr1. * Demon000 deserves credit for the initial idea behind this commit, as he pointed out which structs were used.](https://github.com/ppajda/kernel_g3/commit/0ce9a99f2683001a13409cad5bb026faf4d33380)
* [ab353a4 ANDROID: binder: fix OOB write in __binder_update_page_range](https://github.com/ppajda/kernel_g3/commit/ab353a4586b605c5d2719aaabb2702bdf7b2f96d)
* [df16898 UPSTREAM: include/linux/mm.h: add PAGE_ALIGNED() helper](https://github.com/ppajda/kernel_g3/commit/df168987ba891371ebb93698d45f44de5284ee20)
* [fcb8a0f android: binder: Move buffer out of area shared with user space](https://github.com/ppajda/kernel_g3/commit/fcb8a0fd00a78e070ea7da898de8883894fe853b)
* [dd38d65 android: binder: Refactor prev and next buffer into a helper function](https://github.com/ppajda/kernel_g3/commit/dd38d652a052346b6d0428a8adabce1adc04ac72)
* [15427c5 BACKPORT: staging: android: fix missing a blank line after declarations](https://github.com/ppajda/kernel_g3/commit/15427c522d2b90e8ffc4b5b966ade3117790cd25)
* [b1849eb UPSTREAM: Staging: Android: removed an unnecessary else statement](https://github.com/ppajda/kernel_g3/commit/b1849eb857bacd72d764a82f1cd42b720e0d870d)
* [fd4e0c3 binder: always allocate/map first BINDER_MIN_ALLOC pages](https://github.com/ppajda/kernel_g3/commit/fd4e0c3c767a0705a5e7999c89f95e0bd301836e)
* [8f99ca6 ANDROID: sdcardfs: Move default_normal to superblock](https://github.com/ppajda/kernel_g3/commit/8f99ca6545ea3a37ad60ef1601ff33649703db99)
* [cf26b4b kgsl: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/cf26b4b0ef68e551016bd0f8d77f156e982a9e09)
* [47af35a uio: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/47af35a10340de1f63c0649c994ab7b8444296ef)
* [4a7c323 spmi: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/4a7c323446813f3e05d0a25244c94671836f3a29)
* [b9fcd4f slimbus: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/b9fcd4f932d3bb29058bb763e733e3c49fa7b28f)

***

01-26-2018
====================


***

01-23-2018
====================

* [720e00f BACKPORT: ARM: dts: msm: Mount the system partition during early init](https://github.com/ppajda/kernel_g3/commit/720e00fcd9928db0d4b5122bb93f31034f5e9761)

***

01-14-2018
====================

* [c95d974 mm: change max readahead size to 512KB](https://github.com/ppajda/kernel_g3/commit/c95d9745b2692b9d55cb419b37e6c99693d5c710)

***

01-12-2018
====================

* [ef88684 ANDROID: sdcardfs: Fix missing break on default_normal](https://github.com/ppajda/kernel_g3/commit/ef88684ed52a178a939257e8ecfecf750210a4ed)
* [f4d786f msm: cpp: Fix for integer overflow in cpp](https://github.com/ppajda/kernel_g3/commit/f4d786fd45b003541106e812ebe8ef6bdcab993c)
* [90c15e9 msm: vidc: Check video buffer handle for Null pointer access.](https://github.com/ppajda/kernel_g3/commit/90c15e91a8bc5a260bf43b185199bc9b8f31f84b)
* [56ad8c8 msm:vidc: Fix klockwork errors in video driver.](https://github.com/ppajda/kernel_g3/commit/56ad8c828553a15a74fb29764084af2e8d484549)
* [a1bfd45 msm:vidc: Add null check for handle in smem buffer comparision.](https://github.com/ppajda/kernel_g3/commit/a1bfd45297d145196d441cebbc56685762bda41d)
* [6c968cc msm: vidc: add ion_handle checking before mapping buffers.](https://github.com/ppajda/kernel_g3/commit/6c968cc785de5d06812e4ef605a9424bb54138fb)
* [7c9d64d msm: camera: cpp: Add validation for v4l2 ioctl arguments](https://github.com/ppajda/kernel_g3/commit/7c9d64d95a8f910d254b683304db5338f33e7cb0)
* [f2207f4 staging: android: ashmem: fix a race condition in ASHMEM_SET_SIZE ioctl](https://github.com/ppajda/kernel_g3/commit/f2207f41b23f4d9d29ab1e1018053dc08c425027)
* [a32ee66 ANDROID: mnt: Fix freeing of mount data](https://github.com/ppajda/kernel_g3/commit/a32ee6663807b6d52be7518c4232e035124f8e43)
* [3e83da2 ANDROID: sdcardfs: Add default_normal option](https://github.com/ppajda/kernel_g3/commit/3e83da213c87317e85e76574bc8721cc402ea523)

***

01-11-2018
====================


***

01-10-2018
====================

* [9a1bd89 Fastcharge: Increase ac charge to 1800mA](https://github.com/ppajda/kernel_g3/commit/9a1bd8914d3db509090036a13cf8243d4088722a)

***

01-06-2018
====================

* [6ff4314 msm: camera: move firmware to vendor](https://github.com/ppajda/kernel_g3/commit/6ff431482f672de447d61b9a9f6df72e1ae902fb)
* [31c49ea g3: update config to point bcmdhd firmware to vendor](https://github.com/ppajda/kernel_g3/commit/31c49ead3ceda3a4d3a8572ad3991c4e7e9c1bf5)

***

01-02-2018
====================


***

12-31-2017
====================


***

12-30-2017
====================

* [9fe5658 mmc: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/9fe5658e90176517641606fd044b377b0a5a33fc)
* [edd763d inotify: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/edd763d7e1fd41af574ab8037feb188e85f185e7)
* [2676f39 ocmem_sched: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/2676f39b909497ffa0405ba037db941a74722dca)
* [779262e dm: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/779262e9e59b6443b1324be44892c95ec6a5b682)
* [29c0767 iommu: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/29c0767a354029d32499c3e3f70722d0b3d199b1)
* [44bbd2f iommu: moving initialization earlier](https://github.com/ppajda/kernel_g3/commit/44bbd2f88001c4a5ee8388772f16a8711adf2a18)
* [3be7d89 cgroup: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/3be7d89bff8c67f1a1801181e49332e93dd6ac44)
* [fc4ae4d Fix code errors detected using Linaro GCC 6.1.1-rc1](https://github.com/ppajda/kernel_g3/commit/fc4ae4d13ae61c84f6ebe81a2820b4f6267f6211)
* [7be968b defconfigs: Reduce scheduler tick rate to 100 Hz](https://github.com/ppajda/kernel_g3/commit/7be968b566128c84dfbabbf7c5b6f04ad3597dbe)
* [741a656 fs: dynamic fsync: remove powersuspend](https://github.com/ppajda/kernel_g3/commit/741a65638c8ad8d72cfc74a4c9ee8b474b531a91)

***

12-26-2017
====================

* [719d67a mdss: kcal: make colors more vivid](https://github.com/ppajda/kernel_g3/commit/719d67a07730cccc38d415ee35778f827d63ecb2)
* [1a3db58 usb: gadget: f_hid: fix build error](https://github.com/ppajda/kernel_g3/commit/1a3db582d435117ef1585b50bfd3e50663ac123a)
* [bb5dff6 usb: gadget: u_serial: fix typo which cause build warning](https://github.com/ppajda/kernel_g3/commit/bb5dff66cb025730d3ed9ea90aa4763184748cb2)
* [b6d5c97 usb: gadget: add multiple definition guards](https://github.com/ppajda/kernel_g3/commit/b6d5c97964d8d05b772f1cf1f892b39c9805b8c8)
* [5848544 Revert "usb: gadget: Enable HID function for charging mode"](https://github.com/ppajda/kernel_g3/commit/5848544bd3c40ce74f62bb5c5ca10c87533dfad5)
* [66e63dc USB: android: Fix a NULL pointer dereference](https://github.com/ppajda/kernel_g3/commit/66e63dc431236bbb4435694fc507cd22fc5e452c)
* [e1391e1 usb: dwc3: Do not call WARN_ON_ONCE from interrupt context](https://github.com/ppajda/kernel_g3/commit/e1391e1c966ea6a2ef929f36d96ca83df7109311)
* [3291ccaa usb: gadget: FunctionFS and SuperSpeed updates](https://github.com/ppajda/kernel_g3/commit/3291ccaa630b9eb334d7dc3735b6d2d507a59890)
* [58c76fc f_fs: ffs_func_free: cleanup requests allocated by autoconfig](https://github.com/ppajda/kernel_g3/commit/58c76fce02ee327838470492fa7af94a5f3aef58)
* [70b3016 usb: gadget: f_fs: Fix enumeration in fullspeed mode](https://github.com/ppajda/kernel_g3/commit/70b30168b405578c1c6311da3c0aef400a3c59c5)

***

12-24-2017
====================


***

12-23-2017
====================

* [b580467 ANDROID: binder: fix compilation warnings.](https://github.com/ppajda/kernel_g3/commit/b5804673ed003006554f77957e72e2b13b6de7e8)
* [cb40126 UPSTREAM: drivers: android: correct the size of struct binder_uintptr_t for BC_DEAD_BINDER_DONE](https://github.com/ppajda/kernel_g3/commit/cb40126605e1a4658efeea0483addc226b3bd233)
* [70a3271 staging: binder: Improve Kconfig entry for ANDROID_BINDER_IPC_32BIT](https://github.com/ppajda/kernel_g3/commit/70a3271cdf6ef1228583630b75efe8385282a38a)
* [20ba299 BACKPORT: ARM: 8091/2: add get_user() support for 8 byte types](https://github.com/ppajda/kernel_g3/commit/20ba29916ad903e27ef79ffd2fce16697619dd80)

***

12-22-2017
====================

* [cdf1672 workqueue: fix derp](https://github.com/ppajda/kernel_g3/commit/cdf1672ee8ce329914138528b78f6134829ec8f9)
* [aadb34e workqueue: Fix flag collision](https://github.com/ppajda/kernel_g3/commit/aadb34e76ce831d7463f79737186f5dee8685388)
* [1ce4e1a workqueue: implicit ordered attribute should be overridable](https://github.com/ppajda/kernel_g3/commit/1ce4e1a2d14ee4365fd8933b41649bdf230e0bf2)
* [84bb450 workqueue: restore WQ_UNBOUND/max_active==1 to be ordered](https://github.com/ppajda/kernel_g3/commit/84bb450d818b49a9ff52a5a555d2f8664738754c)
* [9b26c44 workqueue.c: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/9b26c44a538feb17999320ba73cfda7025a1affa)
* [caf060a workqueue: Add system wide power_efficient workqueues](https://github.com/ppajda/kernel_g3/commit/caf060aedcaacf8d425471d47d9d1bcd39a7f63d)
* [220fafa Workqueue: fix permissions](https://github.com/ppajda/kernel_g3/commit/220fafab74ac364c09e96fc1609ec5929b53a1e0)
* [57c871e workqueue: fix ghost PENDING flag while doing MQ IO](https://github.com/ppajda/kernel_g3/commit/57c871ee28fb3fa63843fcf1d451de25183a79e7)
* [bc87ceb Revert "workqueue: make sure delayed work run in local cpu"](https://github.com/ppajda/kernel_g3/commit/bc87ceb042e1c8219a5861a90536e0ed80bf02aa)
* [a8dd69b workqueue: make sure delayed work run in local cpu](https://github.com/ppajda/kernel_g3/commit/a8dd69b79b8d7a9703e146634572674ddac0973a)
* [b353253 workqueue: fix hang involving racing cancel[_delayed]_work_sync()'s for PREEMPT_NONE](https://github.com/ppajda/kernel_g3/commit/b35325363ccf5d06773f0742a29b6b4f2aa67b0b)
* [4e59443 workqueue: fix subtle pool management issue which can stall whole worker_pool](https://github.com/ppajda/kernel_g3/commit/4e59443b36e5c910e4862f8df79178b329f3247f)
* [2f57d67 workqueue: zero cpumask of wq_numa_possible_cpumask on init](https://github.com/ppajda/kernel_g3/commit/2f57d67f36ad5f1f403a7630728fd2f017ab70bb)
* [08b83b4 workqueue: fix dev_set_uevent_suppress() imbalance](https://github.com/ppajda/kernel_g3/commit/08b83b4af68a4294a4641e5ddc79d31665844e49)
* [867b954 workqueue: make rescuer_thread() empty wq->maydays list before exiting](https://github.com/ppajda/kernel_g3/commit/867b954e05b3bed8f98583816e76dbc34fb75bb7)
* [ee333ce workqueue: fix a possible race condition between rescuer and pwq-release](https://github.com/ppajda/kernel_g3/commit/ee333ce23279147000d4d45f9a7ead7145091d65)
* [646b438 workqueue: fix bugs in wq_update_unbound_numa() failure path](https://github.com/ppajda/kernel_g3/commit/646b438e052cebe1b6f6e47baa3ef6888158ffc7)
* [5c6bf10 workqueue: fix ordered workqueues in NUMA setups](https://github.com/ppajda/kernel_g3/commit/5c6bf1018f8a02d5a5a318e224c738b3cbad79a5)
* [a63ab97 workqueue: copy workqueue_attrs with all fields](https://github.com/ppajda/kernel_g3/commit/a63ab97b922a9b05b842c68d27e81022ec78a1f7)
* [bf4e2d7 workqueue: don't perform NUMA-aware allocations on offline nodes in wq_numa_init()](https://github.com/ppajda/kernel_g3/commit/bf4e2d75aedee656f7f7c2867bcd089a0563ef7b)
* [70fb0d4 workqueue: Make schedule_work() available again to non GPL modules](https://github.com/ppajda/kernel_g3/commit/70fb0d415bb150da356782af4429c7480863d355)
* [3e2f814 workqueue: correct handling of the pool spin_lock](https://github.com/ppajda/kernel_g3/commit/3e2f814db86877124e18e5f76930d9ba643cf49d)
* [802779c workqueue: workqueue_congested() shouldn't translate WORK_CPU_UNBOUND into node number](https://github.com/ppajda/kernel_g3/commit/802779ca3c0d22a582f648eaef81fa038548b5c5)
* [256ec59 kthread: implement probe_kthread_data()](https://github.com/ppajda/kernel_g3/commit/256ec598e9fe1a1338af6c029d986e905c7f9fd7)
* [6a49c95 workqueue: include workqueue info when printing debug dump of a worker task](https://github.com/ppajda/kernel_g3/commit/6a49c952d9775b79fe68a94136d6f5ad2efb6bf2)
* [d4abe4f workqueue: use kmem_cache_free() instead of kfree()](https://github.com/ppajda/kernel_g3/commit/d4abe4f5ab17447ddc2e71b8361638b124a129f6)
* [8dd7ee5 workqueue: avoid false negative WARN_ON() in destroy_workqueue()](https://github.com/ppajda/kernel_g3/commit/8dd7ee531d2cdfec8658ea69177e52bc2058f9d4)
* [80d5f87 workqueue: update sysfs interface to reflect NUMA awareness and a kernel param to disable NUMA affinity](https://github.com/ppajda/kernel_g3/commit/80d5f87c676e6a24567e1d4086ffc95da9c08b39)
* [5fec282 workqueue: implement NUMA affinity for unbound workqueues](https://github.com/ppajda/kernel_g3/commit/5fec28253b8580cd7ccfe5f4b57f644904ce0e64)
* [e2ba3f5 workqueue: introduce put_pwq_unlocked()](https://github.com/ppajda/kernel_g3/commit/e2ba3f58c5c401b979f04c84ef55bde4950a72a5)
* [8d1f5af workqueue: introduce numa_pwq_tbl_install()](https://github.com/ppajda/kernel_g3/commit/8d1f5afa1482641854eba432d36daaa7c33a9975)
* [56b2a67 workqueue: use NUMA-aware allocation for pool_workqueues](https://github.com/ppajda/kernel_g3/commit/56b2a671b099ae7f3903d2eb0a3b865e2043c9f7)
* [9122685 workqueue: break init_and_link_pwq() into two functions and introduce alloc_unbound_pwq()](https://github.com/ppajda/kernel_g3/commit/9122685484f49a370632b5f0e261b8af7977dea6)
* [562bb6c workqueue: map an unbound workqueues to multiple per-node pool_workqueues](https://github.com/ppajda/kernel_g3/commit/562bb6c550a2ff09cb07d9060e2bac062505905d)
* [9690ec6 workqueue: move hot fields of workqueue_struct to the end](https://github.com/ppajda/kernel_g3/commit/9690ec678286a8f4ed32d19b7024d9c6aa85220b)
* [0987de6 workqueue: make workqueue->name[] fixed len](https://github.com/ppajda/kernel_g3/commit/0987de6274efc3aea1f117238a74008a578f3d0b)
* [84cbcb5 workqueue: add workqueue->unbound_attrs](https://github.com/ppajda/kernel_g3/commit/84cbcb55b7de69bf0a3bc3c0b4a41b185bdd5a41)
* [b9629a1 workqueue: determine NUMA node of workers accourding to the allowed cpumask](https://github.com/ppajda/kernel_g3/commit/b9629a1a98ed15674cada36367507cafb87b9eae)
* [daf1806 workqueue: drop 'H' from kworker names of unbound worker pools](https://github.com/ppajda/kernel_g3/commit/daf1806635a03148cb2af7c858faea9058e9254b)
* [dc3ef92 workqueue: add wq_numa_tbl_len and wq_numa_possible_cpumask[]](https://github.com/ppajda/kernel_g3/commit/dc3ef920d8e423fa49a742edbb41314065304618)
* [018d35e workqueue: move pwq_pool_locking outside of get/put_unbound_pool()](https://github.com/ppajda/kernel_g3/commit/018d35e466b366d63203de48124fcb552d6e7719)
* [a52574f workqueue: fix memory leak in apply_workqueue_attrs()](https://github.com/ppajda/kernel_g3/commit/a52574f71b54a2ad2ca5dbf9ea5b3bd142c28814)
* [c9778d4 workqueue: fix unbound workqueue attrs hashing / comparison](https://github.com/ppajda/kernel_g3/commit/c9778d4a43bfc069feef5ee2ca94b3e0f3d2830d)
* [d72d54e workqueue: fix race condition in unbound workqueue free path](https://github.com/ppajda/kernel_g3/commit/d72d54e12fb419b821c282357ba418bebf91c4b1)
* [98a05b4 workqueue: remove pwq_lock which is no longer used](https://github.com/ppajda/kernel_g3/commit/98a05b43492ab15f9da8744afa5243f72e9cc9e5)
* [2eef900 workqueue: protect wq->saved_max_active with wq->mutex](https://github.com/ppajda/kernel_g3/commit/2eef90067d638df2a723dc3dc27325f5fa286659)
* [fbd05e1 workqueue: protect wq->pwqs and iteration with wq->mutex](https://github.com/ppajda/kernel_g3/commit/fbd05e1f2cf101ced42ad50451898adbd8f9e259)
* [bd236b0 workqueue: protect wq->nr_drainers and ->flags with wq->mutex](https://github.com/ppajda/kernel_g3/commit/bd236b0e6aa555a8b443d22384e0451dd528bf4a)
* [489a7d0 workqueue: rename wq->flush_mutex to wq->mutex](https://github.com/ppajda/kernel_g3/commit/489a7d0c99b633b72c4039f134ebada150226dd6)
* [7b463fc workqueue: rename wq_mutex to wq_pool_mutex](https://github.com/ppajda/kernel_g3/commit/7b463fc1b5f0251806ceee394fc9bc2e5ff38ffb)
* [5dd9fca workqueue: avoid false negative in assert_manager_or_pool_lock()](https://github.com/ppajda/kernel_g3/commit/5dd9fcadc856a987d50448c7e4257cd4220948ac)
* [318e3ca workqueue: use rcu_read_lock_sched() instead for accessing pwq in RCU](https://github.com/ppajda/kernel_g3/commit/318e3caa50d22b83adae7b6e4ea213e31ecdca17)
* [bdbf7ce workqueue: kick a worker in pwq_adjust_max_active()](https://github.com/ppajda/kernel_g3/commit/bdbf7ce200fc4526340da906e34b996fb4678247)
* [45761c8 workqueue: simplify current_is_workqueue_rescuer()](https://github.com/ppajda/kernel_g3/commit/45761c8d7d0a7b7d06f1b9b0fb71f8d28c0f2e83)
* [667ec5b workqueue: add missing POOL_FREEZING](https://github.com/ppajda/kernel_g3/commit/667ec5bfb888009175af8a4a34804d4f93910273)
* [1a8d19e workqueue: restore CPU affinity of unbound workers on CPU_ONLINE](https://github.com/ppajda/kernel_g3/commit/1a8d19eb0cffc3cc5ba801bc6c9ab4973f5df95b)
* [4234bbc workqueue: directly restore CPU affinity of workers from CPU_ONLINE](https://github.com/ppajda/kernel_g3/commit/4234bbcfa5c494b554840689175adff7dd2171c9)
* [4d956d8 workqueue: relocate rebind_workers()](https://github.com/ppajda/kernel_g3/commit/4d956d89121bdeb7d587f702a92b59666da8aaab)
* [408aaab workqueue: convert worker_pool->worker_ida to idr and implement for_each_pool_worker()](https://github.com/ppajda/kernel_g3/commit/408aaabae4397f1675cedd97fddb0af94592f50b)
* [c5b7415 kgsl: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/c5b74154948f7a72d24172e6b6fa1dabc7499391)
* [94e6bd9 ion: remove deprecated idr_](https://github.com/ppajda/kernel_g3/commit/94e6bd98d673b140437e6a2a409d580fc3eec771)
* [b2e9591 gpio: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/b2e9591019edbb00fd542012ad2ef07d175b56e4)
* [dbab8a4 events: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/dbab8a48de703bfaac5fda0b5550e14261ad5f0b)
* [5f6d2842 block: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/5f6d28421291c9acb935991f9aaad5bde682c09d)
* [2e209e1 scsi: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/2e209e12f981f46c90ff4d984efc7ab0cba11499)
* [15c4ab5 [SCSI] st: remove st_mutex](https://github.com/ppajda/kernel_g3/commit/15c4ab59748cc450d524de82e3877c2394cd69bb)
* [fc0af8f [SCSI] st: clean up device file creation and removal](https://github.com/ppajda/kernel_g3/commit/fc0af8f9b358bdad261178a8ae832ba1bf106804)
* [49d6fb5 [SCSI] st: get rid of scsi_tapes array](https://github.com/ppajda/kernel_g3/commit/49d6fb5c46bc4fbe754b84b98c858abb34814edf)
* [3e3a356 [SCSI] st: clean up dev cleanup in st_probe](https://github.com/ppajda/kernel_g3/commit/3e3a3568f4de2fde4ae4d72a5f5d94ded7570cd6)
* [47ee6a0 [SCSI] st: Use static class attributes](https://github.com/ppajda/kernel_g3/commit/47ee6a0499e653663d45662010a764b16569480b)
* [5e2f8c1 block/loop: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/5e2f8c15f3eb3b66436610ba517b8528fcd672a7)
* [dc329f9 posix-timers: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/dc329f99bdadd05763fc05f99430af647e4dc6b0)
* [590e214 idr: document exit conditions on idr_for_each_entry better](https://github.com/ppajda/kernel_g3/commit/590e2144a3343fe9132e1d7c1ce8db422f2b3ab6)
* [603926a idr: make idr_layer larger](https://github.com/ppajda/kernel_g3/commit/603926addd73a66f2ef95eb528eadc209fcf1cf8)
* [05d2965 idr: fix overflow bug during maximum ID calculation at maximum height](https://github.com/ppajda/kernel_g3/commit/05d2965cc14ff96807062d3e4eaeedfee91bea11)
* [2233ac0 idr: introduce idr_alloc_cyclic()](https://github.com/ppajda/kernel_g3/commit/2233ac0ac8cab6227ed62db7306b5db311d44a8c)
* [5197d22 idr: idr_alloc() shouldn't trigger lowmem warning when preloaded](https://github.com/ppajda/kernel_g3/commit/5197d22def477804c8c6fbdfd54ee37928d37944)
* [2529a77 idr: deprecate idr_pre_get() and idr_get_new[_above]()](https://github.com/ppajda/kernel_g3/commit/2529a77427ac71bbaf191e33253d3c7b28c7fbd2)
* [29befed idr: fix new kernel-doc warnings](https://github.com/ppajda/kernel_g3/commit/29befeda380d4ba2aae5135b0d1cf8e7dd6eb14d)
* [6d25346 idr: remove WARN_ON_ONCE() on negative IDs](https://github.com/ppajda/kernel_g3/commit/6d25346558a325b9962828b6da9af2ad10119b41)
* [13596b4 idr: explain WARN_ON_ONCE() on negative IDs out-of-range ID](https://github.com/ppajda/kernel_g3/commit/13596b47b580d8e5c56c83e5d5e93db4fdcb82c0)
* [6fd287d idr: implement lookup hint](https://github.com/ppajda/kernel_g3/commit/6fd287d6451a856b73914db605f8ea95fe8e92f5)
* [8b030e4 idr: add idr_layer->prefix](https://github.com/ppajda/kernel_g3/commit/8b030e4bc4cc6199b37bed1d205ed720b5250134)
* [7698258 idr: remove length restriction from idr_layer->bitmap](https://github.com/ppajda/kernel_g3/commit/76982589fbd7b00424e7730eac9231557f9c91fd)
* [55d5b88 idr: remove MAX_IDR_MASK and move left MAX_IDR_* into idr.c](https://github.com/ppajda/kernel_g3/commit/55d5b880cfcd0649df94e59a9fa531612e77080a)
* [0b48868 Remove deprecated idr_remove_all and fix derps](https://github.com/ppajda/kernel_g3/commit/0b48868e5d53daf85afd0f595dee89f05f5d1b77)
* [d9c0c1c idr: rename MAX_LEVEL to MAX_IDR_LEVEL](https://github.com/ppajda/kernel_g3/commit/d9c0c1c7c3d93e7801038ad4619830b397d0a6ad)
* [18f7269 idr: fix top layer handling](https://github.com/ppajda/kernel_g3/commit/18f726940becf8c72d0dd89c4695f263d344cf4f)
* [dcc19e8 idr: implement idr_preload[_end]() and idr_alloc()](https://github.com/ppajda/kernel_g3/commit/dcc19e81364fb0026b9d1b7a4361202b19991aba)
* [343efa0 idr: refactor idr_get_new_above()](https://github.com/ppajda/kernel_g3/commit/343efa020f750f03bb2463109e82c959af98a1f0)
* [158dc52 idr: remove _idr_rc_to_errno() hack](https://github.com/ppajda/kernel_g3/commit/158dc5268dfc1e3dce12f5b4d4c9e4765b13a260)
* [a5b6c4e idr: relocate idr_for_each_entry() and reorganize id[r|a]_get_new()](https://github.com/ppajda/kernel_g3/commit/a5b6c4e340eb86ebe4be0a0f766309ed165211fd)
* [d1e4a9b idr: deprecate idr_remove_all()](https://github.com/ppajda/kernel_g3/commit/d1e4a9bede39ea1ef8c5c090392c34453ee4a883)
* [86b15b5 idr: make idr_destroy() imply idr_remove_all()](https://github.com/ppajda/kernel_g3/commit/86b15b51620206b8e5a707a78f76b1d03340b771)
* [1f4d9cb locking: Various static lock initializer fixes](https://github.com/ppajda/kernel_g3/commit/1f4d9cbf3ae80139bc6317c58899605c03ad3a23)
* [7e0e51f sched: replace PF_THREAD_BOUND with PF_NO_SETAFFINITY](https://github.com/ppajda/kernel_g3/commit/7e0e51f767849c78ce3353ef31a371ed9fddef50)
* [bbc2f73 Pull workqueue fix from Tejun Heo](https://github.com/ppajda/kernel_g3/commit/bbc2f730604b0ee146e4be2b8897d13aff804fc7)
* [8143655 workqueue: rename workqueue_lock to wq_mayday_lock](https://github.com/ppajda/kernel_g3/commit/814365581a7a0f8843f59e9046d210fc488fcb72)
* [de49d98 workqueue: separate out pool_workqueue locking into pwq_lock](https://github.com/ppajda/kernel_g3/commit/de49d9808fd046af2b8953f9f3556b1423ae816f)
* [b3cfb9f workqueue: separate out pool and workqueue locking into wq_mutex](https://github.com/ppajda/kernel_g3/commit/b3cfb9f5d1a2fcc429557f2fdb82b838a925eaf3)
* [5d589c7 workqueue: relocate global variable defs and function decls in workqueue.c](https://github.com/ppajda/kernel_g3/commit/5d589c75084c539d617d6ec0ad89d561b77f19c0)
* [e3c39f4 workqueue: better define locking rules around worker creation / destruction](https://github.com/ppajda/kernel_g3/commit/e3c39f42fba55c75ee5be38d451631e76ab8a960)
* [392d40e workqueue: factor out initial worker creation into create_and_start_worker()](https://github.com/ppajda/kernel_g3/commit/392d40e0eb091ccf9908547979a64df73d630875)
* [e1211d3 workqueue: rename worker_pool->assoc_mutex to ->manager_mutex](https://github.com/ppajda/kernel_g3/commit/e1211d3700793923360c4f47ac812acaf52de7d5)
* [0634c3b workqueue: inline trivial wrappers](https://github.com/ppajda/kernel_g3/commit/0634c3b32615f794de86a717b164ec1386b975e0)
* [7ed3e95 workqueue: rename @id to @pi in for_each_each_pool()](https://github.com/ppajda/kernel_g3/commit/7ed3e9577f8d587405de8b1a843ade2e4394b7bd)
* [90d8e17 workqueue: update comments and a warning message](https://github.com/ppajda/kernel_g3/commit/90d8e17d0d43018e6ae65e64f848800ce6d08523)
* [b4af43b workqueue: fix max_active handling in init_and_link_pwq()](https://github.com/ppajda/kernel_g3/commit/b4af43bc1d69a986439215079e819ba44354d295)
* [da26616 workqueue: implement and use pwq_adjust_max_active()](https://github.com/ppajda/kernel_g3/commit/da266163d23657e3a1bd50d6030ddad03817bc10)
* [5b49332 workqueue: relocate pwq_set_max_active()](https://github.com/ppajda/kernel_g3/commit/5b49332caaa62e437c58000436134682e95727a8)
* [c5c18ca workqueue: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/c5c18cab3e6aab9037845c055ddb4ae29cc43fda)
* [5d140d9 workqueue: implement current_is_workqueue_rescuer()](https://github.com/ppajda/kernel_g3/commit/5d140d99e032492e2f54a2dbd90b8baae245a2ef)
* [1368b61 workqueue: implement sysfs interface for workqueues](https://github.com/ppajda/kernel_g3/commit/1368b612a76fd4b0f02b818ad221f4974efbc882)
* [9dbc58b driver/base: implement subsys_virtual_register()](https://github.com/ppajda/kernel_g3/commit/9dbc58bb1280cf564ab11abfc4925758cfef9524)
* [b0c4e9a cpumask: implement cpumask_parse()](https://github.com/ppajda/kernel_g3/commit/b0c4e9a90f35c0856cfe89b6ab0a077827d9cd5d)
* [3cd17ca workqueue: reject adjusting max_active or applying attrs to ordered workqueues](https://github.com/ppajda/kernel_g3/commit/3cd17caebc2f63360e638574a2aa1723a82e5aad)
* [1a162c2 workqueue: make it clear that WQ_DRAINING is an internal flag](https://github.com/ppajda/kernel_g3/commit/1a162c25b9e0a66d3fe0bd33b757adac56fce5c2)
* [285788f workqueue: implement apply_workqueue_attrs()](https://github.com/ppajda/kernel_g3/commit/285788f92acd4b98ad25f297a63712bbc28f7eac)
* [1357d8a workqueue: perform non-reentrancy test when queueing to unbound workqueues too](https://github.com/ppajda/kernel_g3/commit/1357d8abb62809993458088fc26e0e78eb9824a7)
* [1ee4cfd workqueue: prepare flush_workqueue() for dynamic creation and destrucion of unbound pool_workqueues](https://github.com/ppajda/kernel_g3/commit/1ee4cfd90369dc11ad87a273d1454238077bc1ce)
* [7bbb4de workqueue: implement get/put_pwq()](https://github.com/ppajda/kernel_g3/commit/7bbb4debcf19c7e5cfceba9f023a4862c23d2c42)
* [0ebba4e workqueue: restructure __alloc_workqueue_key()](https://github.com/ppajda/kernel_g3/commit/0ebba4e330edf2f1967dc08ae318706202c58f7a)
* [67adf62 workqueue: drop WQ_RESCUER and test workqueue->rescuer for NULL instead](https://github.com/ppajda/kernel_g3/commit/67adf62eecfe59d80267bac38112e9772ee21987)
* [e18c48c7 workqueue: add pool ID to the names of unbound kworkers](https://github.com/ppajda/kernel_g3/commit/e18c48c7e004249187e024d55eb9127d317e8ddc)
* [940baf3 workqueue: drop "std" from cpu_std_worker_pools and for_each_std_worker_pool()](https://github.com/ppajda/kernel_g3/commit/940baf3fff4e892730bb0d50c5f5cf5a012afd39)
* [a3918d8 workqueue: remove unbound_std_worker_pools[] and related helpers](https://github.com/ppajda/kernel_g3/commit/a3918d8494bd364be9f8c727c723da466d1021a8)
* [be09636 workqueue: implement attribute-based unbound worker_pool management](https://github.com/ppajda/kernel_g3/commit/be0963674091fc6b62fff823d38238f7a6810e8a)
* [9ce36b7 workqueue: introduce workqueue_attrs](https://github.com/ppajda/kernel_g3/commit/9ce36b724a2691da970e08a83e0ab6de7a85f19e)
* [27f3282 workqueue: separate out init_worker_pool() from init_workqueues()](https://github.com/ppajda/kernel_g3/commit/27f3282f465bfe6b7440aed17a86a463e52fbe92)
* [d1ec74e workqueue: replace POOL_MANAGING_WORKERS flag with worker_pool->manager_arb](https://github.com/ppajda/kernel_g3/commit/d1ec74eef304bd82dadf955ae99a7f4317a1f169)
* [c49bdd6 workqueue: update synchronization rules on worker_pool_idr](https://github.com/ppajda/kernel_g3/commit/c49bdd658867ae247f86a5f865ff23945bcf2965)
* [364e875 workqueue: update synchronization rules on workqueue->pwqs](https://github.com/ppajda/kernel_g3/commit/364e87576643c958e1546e33472c3cace94ca20c)
* [7e044d3 workqueue: replace get_pwq() with explicit per_cpu_ptr() accesses and first_pwq()](https://github.com/ppajda/kernel_g3/commit/7e044d36e9781178422f83a2cd4b07944f40b9f3)
* [f6eed19 workqueue: remove workqueue_struct->pool_wq.single](https://github.com/ppajda/kernel_g3/commit/f6eed19e89b801ab71dd3ed102e3161a5d0137c7)
* [f3be0ea workqueue: consistently use int for @cpu variables](https://github.com/ppajda/kernel_g3/commit/f3be0eac0efbf47a993c5db2f2e6cb73f4664c7e)
* [85c9a9e workqueue: add wokrqueue_struct->maydays list to replace mayday cpu iterators](https://github.com/ppajda/kernel_g3/commit/85c9a9eb57d0cf0cbe903c013114b9767d62c87b)
* [7de8402 workqueue: restructure pool / pool_workqueue iterations in freeze/thaw functions](https://github.com/ppajda/kernel_g3/commit/7de8402798276d7b514cb9c28df47cc6c00caf3d)
* [456108c workqueue: introduce for_each_pool()](https://github.com/ppajda/kernel_g3/commit/456108ca5c7bc723af460b883320fd473139001e)
* [c32009d workqueue: replace for_each_pwq_cpu() with for_each_pwq()](https://github.com/ppajda/kernel_g3/commit/c32009d0fef378fc9b4094d23b3f528f9af9b5b9)
* [4231f41 workqueue: add workqueue_struct->pwqs list](https://github.com/ppajda/kernel_g3/commit/4231f414ddbf66f41a273fcdc9503ee85aed434e)
* [fff8cea workqueue: introduce kmem_cache for pool_workqueues](https://github.com/ppajda/kernel_g3/commit/fff8ceaf929e9c0b4ff23c9660a480e962aec438)
* [ce4e978 workqueue: make workqueue_lock irq-safe](https://github.com/ppajda/kernel_g3/commit/ce4e978235e2773714701b3c1c10d8a88098c050)
* [2ebbec6 workqueue: make sanity checks less punshing using WARN_ON[_ONCE]()s](https://github.com/ppajda/kernel_g3/commit/2ebbec63b7da3847053b72bc105cca4266396d40)
* [6f9ddb3 workqueue: fix possible pool stall bug in wq_unbind_fn()](https://github.com/ppajda/kernel_g3/commit/6f9ddb3923c1eddfac3dfd3380847816d3f350e9)
* [f032cc3 workqueue: better define synchronization rule around rescuer->pool updates](https://github.com/ppajda/kernel_g3/commit/f032cc306b44ac9fa8a2d3c604c0ef438097a73f)
* [e4720ce workqueue: change argument of worker_maybe_bind_and_lock() to @pool](https://github.com/ppajda/kernel_g3/commit/e4720cedc7f2a00bcac6eb619e879c052c56ba57)
* [3055b9b workqueue: use %current instead of worker->task in worker_maybe_bind_and_lock()](https://github.com/ppajda/kernel_g3/commit/3055b9b923fb5ddc21ccd2d5064924cd828b1603)
* [81bf5a1 workqueue: un-GPL function delayed_work_timer_fn()](https://github.com/ppajda/kernel_g3/commit/81bf5a1268cb19b553d7701a87242e0793e497ba)
* [f635c04 workqueue: implement current_is_async()](https://github.com/ppajda/kernel_g3/commit/f635c04fa912de0af60f0096e524e215f0972493)
* [f645d65 workqueue: rename cpu_workqueue to pool_workqueue](https://github.com/ppajda/kernel_g3/commit/f645d6567eb9e62771598cb71f45f24a5d75f3f2)
* [460057a workqueue: reimplement is_chained_work() using current_wq_worker()](https://github.com/ppajda/kernel_g3/commit/460057a731926ca6c75a2530d818666b9aafe56a)
* [906a331 workqueue: fix is_chained_work() regression](https://github.com/ppajda/kernel_g3/commit/906a3314bd392f8d62a8342c4868931ac324c107)
* [69cf119 workqueue: pick cwq instead of pool in __queue_work()](https://github.com/ppajda/kernel_g3/commit/69cf119308c6ef217c35958b787282c03d927f58)
* [138aa89 workqueue: make get_work_pool_id() cheaper](https://github.com/ppajda/kernel_g3/commit/138aa89e426dc4a748944d4b13afd5902f88a521)
* [fb668ac workqueue: move nr_running into worker_pool](https://github.com/ppajda/kernel_g3/commit/fb668ac0cfc2043fde01e2274d4719c6f4e1553a)
* [101b7b3 workqueue: cosmetic update in try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/101b7b3b95203db6e70acaaafbdcb27e27e79cbd)
* [6e9b1ba workqueue: simplify is-work-item-queued-here test](https://github.com/ppajda/kernel_g3/commit/6e9b1ba7566395136f67554f3184c1138c8c8993)
* [6f7ec5d workqueue: make work->data point to pool after try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/6f7ec5df7196df4878d7c5aae610552b2141e5ef)
* [e0909ae workqueue: add delayed_work->wq to simplify reentrancy handling](https://github.com/ppajda/kernel_g3/commit/e0909ae887a73993c7d739857d82b2fc7a56e5e3)
* [2332700 workqueue: make work_busy() test WORK_STRUCT_PENDING first](https://github.com/ppajda/kernel_g3/commit/2332700e30809af50c34260bbc71182d55e3e6e4)
* [91152cf workqueue: replace WORK_CPU_NONE/LAST with WORK_CPU_END](https://github.com/ppajda/kernel_g3/commit/91152cfbee16a5a18b328fc7291a0577badb96d3)
* [7e38043 workqueue: post global_cwq removal cleanups](https://github.com/ppajda/kernel_g3/commit/7e3804382005f9a95f6c2e8779df55f4545a0d6b)
* [35eeca7 workqueue: rename nr_running variables](https://github.com/ppajda/kernel_g3/commit/35eeca70cd40c62ca24c0619adef2d5464cc26a2)
* [a6103de workqueue: remove global_cwq](https://github.com/ppajda/kernel_g3/commit/a6103de23f8b915e4eb6cf1bd8b848e758648e3b)
* [e3df90f workqueue: remove worker_pool->gcwq](https://github.com/ppajda/kernel_g3/commit/e3df90fe4ac1d3b68d8eda4525a2ad7b5f1852b1)
* [c860d7b workqueue: replace for_each_worker_pool() with for_each_std_worker_pool()](https://github.com/ppajda/kernel_g3/commit/c860d7b79f9e6c4ce071788da9f12674db8a1e37)
* [1b58496 workqueue: make freezing/thawing per-pool](https://github.com/ppajda/kernel_g3/commit/1b58496131bf3a2abbead7b875e61f5c485da332)
* [7381209 workqueue: make hotplug processing per-pool](https://github.com/ppajda/kernel_g3/commit/7381209a19011d437c52822ad6616f172ff88c32)
* [c9bed9b workqueue: move global_cwq->lock to worker_pool](https://github.com/ppajda/kernel_g3/commit/c9bed9b2bfdefcb35f6bc6c5081626de97c91264)
* [dcfc578 workqueue: move global_cwq->cpu to worker_pool](https://github.com/ppajda/kernel_g3/commit/dcfc5784e52ba798097652ea840d5d45fe670f12)
* [7f52286 workqueue: move busy_hash from global_cwq to worker_pool](https://github.com/ppajda/kernel_g3/commit/7f5228682ea5a406dfad28868a2aba684a1d1481)
* [39b1097 workqueue: record pool ID instead of CPU in work->data when off-queue](https://github.com/ppajda/kernel_g3/commit/39b1097c985ec7b38fb382857587f475bb19440f)
* [f84a804 workqueue: add worker_pool->id](https://github.com/ppajda/kernel_g3/commit/f84a80405856548bdc567ce5496f8934ebd24f2b)
* [2a686a7 workqueue: make GCWQ_FREEZING a pool flag](https://github.com/ppajda/kernel_g3/commit/2a686a7adeabc86fa39ffa36e41d2dd61f2a83be)
* [305cb0f workqueue: make GCWQ_DISASSOCIATED a pool flag](https://github.com/ppajda/kernel_g3/commit/305cb0f5f8cbd1163a6cdd9fa839e67621af0dbf)
* [79025a5 workqueue: use std_ prefix for the standard per-cpu pools](https://github.com/ppajda/kernel_g3/commit/79025a5540e5ce0aa0347231e900bee7b11ed343)
* [e4fdda7 workqueue: move struct worker definition to workqueue_internal.h](https://github.com/ppajda/kernel_g3/commit/e4fdda7b947d68c80d41df01b2b421a1346a2f96)
* [8caedc9 workqueue: rename kernel/workqueue_sched.h to kernel/workqueue_internal.h](https://github.com/ppajda/kernel_g3/commit/8caedc959abdb758ceb2ed6a532e12fea964aa54)
* [85bec27 workqueue: set PF_WQ_WORKER on rescuers](https://github.com/ppajda/kernel_g3/commit/85bec2781e4e78409cbfce1a3ee76ac2fc16ba6b)
* [e145c8d workqueue: fix find_worker_executing_work() brekage from hashtable conversion](https://github.com/ppajda/kernel_g3/commit/e145c8dc481891905ec11d9f88f1b6b94b33d17c)
* [5823172 workqueue: consider work function when searching for busy work items](https://github.com/ppajda/kernel_g3/commit/58231723d5a21ecc07b44bb86fd3b9d91888ece1)
* [0720702 workqueue: use new hashtable implementation](https://github.com/ppajda/kernel_g3/commit/07207029d72769d085a6914396760bf8a6e84652)
* [ab100ce workqueue: convert BUG_ON()s in __queue_delayed_work() to WARN_ON_ONCE()s](https://github.com/ppajda/kernel_g3/commit/ab100ceec1f4bd26b2cb6fd7f04ad4dfd391496d)
* [1ee1f97 workqueue: add WARN_ON_ONCE() on CPU number to wq_worker_waking_up()](https://github.com/ppajda/kernel_g3/commit/1ee1f97eac60e3778bcc6ae7a3a45766c9d84345)
* [aa6b033 workqueue: trivial fix for return statement in work_busy()](https://github.com/ppajda/kernel_g3/commit/aa6b033e88e70f157f7adc9f345d4b6d8207dc22)
* [ba9508d workqueue: mod_delayed_work_on() shouldn't queue timer on 0 delay](https://github.com/ppajda/kernel_g3/commit/ba9508d076994111c9fb5cf25119497a6babe922)
* [c7028b6 workqueue: cancel_delayed_work() should return %false if work item is idle](https://github.com/ppajda/kernel_g3/commit/c7028b670a9517f163f780463e625e6b34f0f07b)
* [6021591 workqueue: remove spurious WARN_ON_ONCE(in_irq()) from try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/60215917fe018bb6b78366f4535e4493cc391f24)
* [688eb44 workqueue: use cwq_set_max_active() helper for workqueue_set_max_active()](https://github.com/ppajda/kernel_g3/commit/688eb44834beabe6f2bfdc9e0287cc7379c99b9f)
* [103ce64 workqueue: introduce cwq_set_max_active() helper for thaw_workqueues()](https://github.com/ppajda/kernel_g3/commit/103ce6469a3bbac7625df9b8fd8bc5b81e936936)
* [6dec31c workqueue: remove @delayed from cwq_dec_nr_in_flight()](https://github.com/ppajda/kernel_g3/commit/6dec31cda216f5000c7f51641a82f43ddb252429)
* [26033d9 workqueue: fix possible stall on try_to_grab_pending() of a delayed work item](https://github.com/ppajda/kernel_g3/commit/26033d9a045e3f1398979a309474580610f62aed)
* [ac75895 workqueue: use hotcpu_notifier() for workqueue_cpu_down_callback()](https://github.com/ppajda/kernel_g3/commit/ac75895ae6427598685d4f8c059bcabf1e7de2eb)
* [e92db22 workqueue: use __cpuinit instead of __devinit for cpu callbacks](https://github.com/ppajda/kernel_g3/commit/e92db226d92649f8b01ffc2f515d2f121153d1c8)
* [4af5963 workqueue: rename manager_mutex to assoc_mutex](https://github.com/ppajda/kernel_g3/commit/4af5963f7c098e2780c0da93a67b266d384397a5)
* [989d841 workqueue: WORKER_REBIND is no longer necessary for idle rebinding](https://github.com/ppajda/kernel_g3/commit/989d841251ab3606c28ff2a129f4891063808f3d)
* [5a23c84 workqueue: WORKER_REBIND is no longer necessary for busy rebinding](https://github.com/ppajda/kernel_g3/commit/5a23c84ae5b4dbae3d69cd6296a1c8b13cc3c3ca)
* [afb1703 workqueue: reimplement idle worker rebinding](https://github.com/ppajda/kernel_g3/commit/afb17035dc0a801518e1f05251ea11804d84771a)
* [38530e9 Merge branch 'for-3.6-fixes' of git://git.kernel.org/pub/scm/linux/kernel/git/tj/wq into for-3.7](https://github.com/ppajda/kernel_g3/commit/38530e96f89bf2e65ae9cc7f35744c68e1c87d64)
* [01a07b1 workqueue: always clear WORKER_REBIND in busy_worker_rebind_fn()](https://github.com/ppajda/kernel_g3/commit/01a07b1d5426f5ee4960fb8dc91cc4f0c22a20bc)
* [7a6df86 workqueue: fix possible idle worker depletion across CPU hotplug](https://github.com/ppajda/kernel_g3/commit/7a6df86e2d6420c30857a3c73a1fad507b941b44)
* [4c89c51 workqueue: restore POOL_MANAGING_WORKERS](https://github.com/ppajda/kernel_g3/commit/4c89c51576e89078adb5a25b79d1b70357b57ec9)
* [8672645 workqueue: fix possible deadlock in idle worker rebinding](https://github.com/ppajda/kernel_g3/commit/8672645462938edd7fc5d167f2621634f819102c)
* [ac54c5f workqueue: move WORKER_REBIND clearing in rebind_workers() to the end of the function](https://github.com/ppajda/kernel_g3/commit/ac54c5fde837cec830eead4f2622cc5cd6189b5b)
* [6e1f80f workqueue: UNBOUND -> REBIND morphing in rebind_workers() should be atomic](https://github.com/ppajda/kernel_g3/commit/6e1f80f2362a9d48f8eee3d20695efa915671e95)
* [4fd1c95 rename deprecated __cancel_delayed_work to cancel_delayed_work](https://github.com/ppajda/kernel_g3/commit/4fd1c95e009c0d19267de99665ab31b21075fd77)
* [207f9d7 workqueue: introduce WORK_OFFQ_CPU_NONE](https://github.com/ppajda/kernel_g3/commit/207f9d7600b03a3e0e94609ad599cb3abf1a3fb1)
* [70f70ed workqueue: unexport work_cpu()](https://github.com/ppajda/kernel_g3/commit/70f70ede383acd248c26c251c7347da421744176)
* [b97ec45 workqueue: deprecate __cancel_delayed_work()](https://github.com/ppajda/kernel_g3/commit/b97ec45139e04f8376672134c6d9e5859e79d9ba)
* [9e0f5af workqueue: reimplement cancel_delayed_work() using try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/9e0f5af174433bed01178f816d0e32a0016eda55)
* [f86dd89 workqueue: use irqsafe timer for delayed_work](https://github.com/ppajda/kernel_g3/commit/f86dd89b29e311b5d4cab6a17b8b4152e5100d1f)
* [e2e65a1 timer: Implement TIMER_IRQSAFE](https://github.com/ppajda/kernel_g3/commit/e2e65a17b286d882123206fe6086e913e20b5bba)
* [987a962 timer: Clean up timer initializers](https://github.com/ppajda/kernel_g3/commit/987a9622f77f163d820ea690ee5fac27babad86f)
* [922bcd8 timer: Relocate declarations of init_timer_on_stack_key()](https://github.com/ppajda/kernel_g3/commit/922bcd847981d7e1a08fefa65ad44de130d7321a)
* [275d443 timer: Generalize timer->base flags handling](https://github.com/ppajda/kernel_g3/commit/275d4435536613821f8a43ce0529a726fae68eb3)
* [bd61734 timers: Improve get_next_timer_interrupt()](https://github.com/ppajda/kernel_g3/commit/bd617346f31465a6a8e40ef71bb6a46617e7132b)
* [db3365a timers: Add accounting of non deferrable timers](https://github.com/ppajda/kernel_g3/commit/db3365a5ae3c1925b9cdea986c90ede87bec6089)
* [be9cd0f timers: Consolidate base->next_timer update](https://github.com/ppajda/kernel_g3/commit/be9cd0ffda60bfc1d83dfcbf5a6fb09c20565ca4)
* [47b71a3 timers: Create detach_if_pending() and use it](https://github.com/ppajda/kernel_g3/commit/47b71a393848c2ed4ad498283a01a3c5a9d1b801)
* [0089d0e lockdep: fix oops in processing workqueue](https://github.com/ppajda/kernel_g3/commit/0089d0e9f866069ebdf72ffc05dff1e3da239664)
* [0bcaa81 workqueue: clean up delayed_work initializers and add missing one](https://github.com/ppajda/kernel_g3/commit/0bcaa81f515398678025de0bc531e39c4e4608f0)
* [5d6a489 workqueue: make deferrable delayed_work initializer names consistent](https://github.com/ppajda/kernel_g3/commit/5d6a489438732dba5ef53a75c80f6c1848ebb73d)
* [119fad8 workqueue: deprecate system_nrt[_freezable]_wq](https://github.com/ppajda/kernel_g3/commit/119fad808917b06c3c2c99166042b08b5a1243db)
* [5e56a10 workqueue: deprecate flush[_delayed]_work_sync()](https://github.com/ppajda/kernel_g3/commit/5e56a10bf64eb867e5ecd677a03113180ebd6a5d)
* [e6030a8 sched/core: Fix a race between try_to_wake_up() and a woken up task](https://github.com/ppajda/kernel_g3/commit/e6030a80cc5c3b3bfcf0208f103de198dba96587)

***

12-16-2017
====================

* [9f892f2 defconfigs: fix derp](https://github.com/ppajda/kernel_g3/commit/9f892f2b592460fec38cc0f685100a5570cbef67)
* [5ef39a8 fixes some errors](https://github.com/ppajda/kernel_g3/commit/5ef39a880c233f9cc4229e24680f963a867e95a1)
* [8ec448f dts: msm8974.dtsi: tune thermal](https://github.com/ppajda/kernel_g3/commit/8ec448f80dc9bee2ef0db0bec207d555a1ae20f4)
* [2696e79 replace deprecated create_singlethread_workqueue with schedule_work](https://github.com/ppajda/kernel_g3/commit/2696e791594e4193d7fc02ca7ac8919268c6e0df)
* [9914a39 msm: kgsl: Remove io_fraction as it is no longer used](https://github.com/ppajda/kernel_g3/commit/9914a3968eac82f61e74b7359e9a4e4240729a1f)
* [aa764ab msm8974pro.dtsi: change initial power level](https://github.com/ppajda/kernel_g3/commit/aa764ab580aba802d72a7db97878b003f62c8e1c)

***

12-13-2017
====================

* [d48a5ac ALSA: seq: Fix use-after-free at creating a port](https://github.com/ppajda/kernel_g3/commit/d48a5ac4c387a997cfede68c7e481ad414db2de2)
* [fbeeb86 nl80211: check for the required netlink attributes presence](https://github.com/ppajda/kernel_g3/commit/fbeeb86d2d3adf3e0926983f7f980e78b22645ce)
* [a7be5af SoC: msm: audio-effects: return directly to avoid integer overflow](https://github.com/ppajda/kernel_g3/commit/a7be5aff3c56639373365e838e6f72a526382a76)
* [e92d74d crypto: msm: Fix several race condition issues in crypto drivers](https://github.com/ppajda/kernel_g3/commit/e92d74d03c8c1253b782da8e8aed73ee8c503b10)
* [d18d387 net: usb: Make sure list_head operate atomically](https://github.com/ppajda/kernel_g3/commit/d18d3878376cdcf63d4377417eb880897236e822)
* [7bb5958 msm: camera: fix off-by-one overflow in msm_isp_get_bufq](https://github.com/ppajda/kernel_g3/commit/7bb59581315b0a57b478fcbb9b3185b3681cfcff)
* [c1e015f ASoC: msm: qdsp6v2: extend validation of virtual address](https://github.com/ppajda/kernel_g3/commit/c1e015fbf3d93d8576393c35018e1ed4768d3cbf)
* [d57fc24 mm: Fix incorrect type conversion for size during dma allocation](https://github.com/ppajda/kernel_g3/commit/d57fc2454fc4d0a6d7cf8e2c3e0e17d7e649eef4)
* [016f266 msm: mdss: Buffer overflow while processing gamut table data](https://github.com/ppajda/kernel_g3/commit/016f2668301f40419d23c8ac80c37164d553ed23)
* [8f9b84d msm: sps: Fix race condition in SPS debugfs APIs](https://github.com/ppajda/kernel_g3/commit/8f9b84d404778062df33870f544186a8538919e9)
* [5fe8b27 ASoC: msm: remove unused msm-compr-q6-v2](https://github.com/ppajda/kernel_g3/commit/5fe8b27f73d2c7e4fa9ddbb00c58e218aca750ed)
* [ec4921d IKHSS7-18791 msm:fix the list usage in msm_bus_dbg](https://github.com/ppajda/kernel_g3/commit/ec4921d77d45d15ec7b7f26506c72d09d9c2f948)
* [4b8c7b0 diag: dci: Add protection while querying event status](https://github.com/ppajda/kernel_g3/commit/4b8c7b00d3630884e62522d3dcd2767a71bd4b44)
* [6d1a6e5 wcnss: fix the potential memory leak and heap overflow](https://github.com/ppajda/kernel_g3/commit/6d1a6e546c6a42096364165fe129f5c794087c2d)
* [52dc989 msm: camera: isp: fix for out of bound access array](https://github.com/ppajda/kernel_g3/commit/52dc98996fe137579d7e3c5b515c2bf6b7cd486d)
* [554194c msm: camera: Allow driver file to be opend only once.](https://github.com/ppajda/kernel_g3/commit/554194c65f8db4a520ddab83a553dad3b9067774)
* [e6510ad ipx: call ipxitf_put() in ioctl error path](https://github.com/ppajda/kernel_g3/commit/e6510ad6f982af57f0147866f8b5362a269618b0)
* [c96500a ASoC: msm: acquire lock in ioctl](https://github.com/ppajda/kernel_g3/commit/c96500aa56579483d8d1eec903b0024747627f54)
* [c2a19d1 ANDROID: input: keychord: fix race condition bug](https://github.com/ppajda/kernel_g3/commit/c2a19d1faab3847a009067fea032bf6be16b3968)
* [cb239bd ALSA: pcm: prevent UAF in snd_pcm_info](https://github.com/ppajda/kernel_g3/commit/cb239bd180387c1f1c60d3b538f5ef048a3d9b26)
* [9dbfc40 Prevent potential double frees in sg driver](https://github.com/ppajda/kernel_g3/commit/9dbfc40c709d372a844c02d6a835dc2962578b71)
* [794c981 tracing: do not leak kernel addresses](https://github.com/ppajda/kernel_g3/commit/794c9814fba543f1d040d226f8d6e3172d7dcd76)
* [6a405f1 UPSTREAM: tracing: Fix trace_printk() to print when not using bprintk()](https://github.com/ppajda/kernel_g3/commit/6a405f13d3c8e52d8dc4bd76fee6a5dc33ea6e32)
* [9b39667 Prevent heap overflow in uvc driver](https://github.com/ppajda/kernel_g3/commit/9b396672c0abba04f487340b33a2a1bdba935b5c)
* [71a20b1 input: synaptics: put offset checks under mutex.](https://github.com/ppajda/kernel_g3/commit/71a20b1729cd5b1ab92b749b072721f2bc48b85b)
* [7a7a803 msm: ADSPRPC: Buffer length truncated while validation](https://github.com/ppajda/kernel_g3/commit/7a7a80326da900628a06b38d44c0530ead22e2b9)
* [5461c95 input: synaptics_dsx: remove some sysfs nodes.](https://github.com/ppajda/kernel_g3/commit/5461c95fc482a7911c84d58349066b1d1f616341)
* [add909b Input: synaptics: check input, prevent sysfs races](https://github.com/ppajda/kernel_g3/commit/add909b5b84e98cae3bc814a44e96051fb15db48)
* [6c4ea7a input: synaptics: defer sysfs creation during init](https://github.com/ppajda/kernel_g3/commit/6c4ea7a3c2ea32b521a12298181e4f2a27dc6f7e)
* [7d1a6b9 input: synaptics: allocate heap memory for buffer](https://github.com/ppajda/kernel_g3/commit/7d1a6b98c89ec953490cf77d5d730622267cea14)
* [3b75011 input: synaptics: allocate heap memory for temp buf](https://github.com/ppajda/kernel_g3/commit/3b7501151723edcab6496acb1f9ac09a581552b9)
* [fd4b2b6 msm: ispif: Remove handling of SD_SHUTDOWN](https://github.com/ppajda/kernel_g3/commit/fd4b2b6c78207be878435d188a8459c8d9c9e8cf)
* [48dbbe6 net: socket: fix recvmmsg not returning error from sock_error](https://github.com/ppajda/kernel_g3/commit/48dbbe6dedb78793b5cd65f4bdf3e6e9461b3ceb)
* [d24a0b2 ipv6: add complete rcu protection around np->opt](https://github.com/ppajda/kernel_g3/commit/d24a0b2b1d89826861f9c3949874ab241745e879)
* [97c8dbd UPSTREAM: x86/mm/32: Enable full randomization on i386 and X86_32](https://github.com/ppajda/kernel_g3/commit/97c8dbda950b3a3f12085fe4756db376fab35ca3)
* [9f52735 sdcardfs: fix space leak](https://github.com/ppajda/kernel_g3/commit/9f52735e7dab5a65cfb9f6901180f4a3d5b4f3ef)
* [61ce94c sdcardfs: minor fixes](https://github.com/ppajda/kernel_g3/commit/61ce94c7925461f65ecdf8cc4d3205c6fb9ba660)
* [1c513e1 sdcardfs: Backport and use some 3.10 hlist/hash macros](https://github.com/ppajda/kernel_g3/commit/1c513e1e136a51a62e3c7f3024fc4a1274f89aee)
* [cf22c7c ANDROID: sdcardfs: Add missing break](https://github.com/ppajda/kernel_g3/commit/cf22c7c1a590d2b472830eccf67c1b32158d1ba0)
* [0c3d819 ANDROID: Sdcardfs: Move gid derivation under flag](https://github.com/ppajda/kernel_g3/commit/0c3d81972dce1bb06e516a82d8c108cf0702021b)
* [a68ba47 ANDROID: sdcardfs: override credential for ioctl to lower fs](https://github.com/ppajda/kernel_g3/commit/a68ba47414d787833385c2aa7e289e3f2bfc201b)
* [536773a sdcardfs: limit stacking depth](https://github.com/ppajda/kernel_g3/commit/536773af0561af9d0d4da75cde9d95f1d5dcdfe0)
* [e1faea4 ANDROID: sdcardfs: Remove unnecessary lock](https://github.com/ppajda/kernel_g3/commit/e1faea47200b431a628c275f4ae8bd22d23731d5)
* [d0b550c ANDROID: sdcardfs: use mount_nodev and fix a issue in sdcardfs_kill_sb](https://github.com/ppajda/kernel_g3/commit/d0b550cc4ee5aff4ebc99d9bba50df61b4dccd40)
* [10a53a3 ANDROID: sdcardfs: remove dead function open_flags_to_access_mode()](https://github.com/ppajda/kernel_g3/commit/10a53a3cf8082f947c899b67c9ca7e30a5d1b776)
* [cd87ed3 ANDROID: sdcardfs: d_splice_alias can return error values](https://github.com/ppajda/kernel_g3/commit/cd87ed3eae1f1608e509305aa9cc3d02c6d43a22)
* [74bdfce ANDROID: mnt: Fix next_descendent](https://github.com/ppajda/kernel_g3/commit/74bdfcec898538f05dd472630c12c345baedd897)
* [16ce09d ANDROID: sdcardfs: Check for NULL in revalidate](https://github.com/ppajda/kernel_g3/commit/16ce09d158cf07b3c08c779ccd0875bd14266f73)
* [feefb06 ANDROID: sdcardfs: Add linux/kref.h include](https://github.com/ppajda/kernel_g3/commit/feefb063b4a9390402509b12f52c758f87c06d16)
* [65c2a8c ANDROID: sdcardfs: Move top to its own struct](https://github.com/ppajda/kernel_g3/commit/65c2a8c8412b17d9ec79d996b8ef05d7c31873e6)
* [684cb5a ANDROID: sdcardfs: fix sdcardfs_destroy_inode for the inode RCU approach](https://github.com/ppajda/kernel_g3/commit/684cb5a322ba8a8e3ee16f6e6a464f94e4b5febb)
* [0e9534d ANDROID: sdcardfs: Don't iput if we didn't igrab](https://github.com/ppajda/kernel_g3/commit/0e9534dbf89f31cb090342968fc98401065572f7)
* [df39563 ANDROID: sdcardfs: Call lower fs's revalidate](https://github.com/ppajda/kernel_g3/commit/df395632909c2ec9d2d92762444333f747315ef4)
* [d73beeb ANDROID: sdcardfs: Avoid setting GIDs outside of valid ranges](https://github.com/ppajda/kernel_g3/commit/d73beeb5231d70ade1badd9753ef495b6434a3ec)
* [ea31319 Revert "Revert "Android: sdcardfs: Don't do d_add for lower fs""](https://github.com/ppajda/kernel_g3/commit/ea31319ee54df21b377e671abb0df2ad15187dc3)
* [6746b45 ANDROID: sdcardfs: Use filesystem specific hash](https://github.com/ppajda/kernel_g3/commit/6746b4508713219d7f0717a2456e3e0a5e36c9cd)
* [91b3464 Revert "Android: sdcardfs: Don't do d_add for lower fs"](https://github.com/ppajda/kernel_g3/commit/91b34644a6b3223cd4f6bfc8f7ef0b8cf4a92c45)
* [1db1d66 Android: sdcardfs: Don't complain in fixup_lower_ownership](https://github.com/ppajda/kernel_g3/commit/1db1d66668b9d838503591ba8fab76c131c4fd1c)
* [b358e54 Android: sdcardfs: Don't do d_add for lower fs](https://github.com/ppajda/kernel_g3/commit/b358e548772f91db71a5d6a86f3cc6ecc59866fc)
* [9e8f498 ANDROID: sdcardfs: ->iget fixes](https://github.com/ppajda/kernel_g3/commit/9e8f498ef97b9f8bac2b6be3fb0847d8349a9bfd)
* [fbf7d92 Android: sdcardfs: Change cache GID value](https://github.com/ppajda/kernel_g3/commit/fbf7d9212642e66ecc6d12650435ab4aa012bdef)
* [22bc2b7 ANDROID: sdcardfs: Directly pass lower file for mmap](https://github.com/ppajda/kernel_g3/commit/22bc2b7fc7a8daa50e72ef261cd7757f3310d197)
* [577e943 ANDROID: sdcardfs: update module info](https://github.com/ppajda/kernel_g3/commit/577e94361a24cbe4dce7dee677c8bd699f4a71f1)
* [e71a136 ANDROID: sdcardfs: use d_splice_alias](https://github.com/ppajda/kernel_g3/commit/e71a136e6f06044bb78b0f3acc264e7823710cc9)
* [c7ea5a4 ANDROID: sdcardfs: fix ->llseek to update upper and lower offset](https://github.com/ppajda/kernel_g3/commit/c7ea5a4378ee57e1d9b2f46247dd0a78ccecf2e3)
* [11c63a6 ANDROID: sdcardfs: copy lower inode attributes in ->ioctl](https://github.com/ppajda/kernel_g3/commit/11c63a6f2bad3527715bd10d3066a2c4df6d93ae)
* [1add727 ANDROID: sdcardfs: remove unnecessary call to do_munmap](https://github.com/ppajda/kernel_g3/commit/1add72719416bb802848ffc23a1a0fcbc0ed0d01)
* [5ca6f9c ANDROID: sdcardfs: Fix style issues in macros](https://github.com/ppajda/kernel_g3/commit/5ca6f9c01df1bddb5cda63f04f49bf054f7c8d10)
* [29a44c0 ANDROID: sdcardfs: Use seq_puts over seq_printf](https://github.com/ppajda/kernel_g3/commit/29a44c05e2caa4fe9df44a29e68eec982129abac)
* [2e8e374 ANDROID: sdcardfs: Use to kstrout](https://github.com/ppajda/kernel_g3/commit/2e8e374231f9f1f5203cc16ad6f7ed05694fbd91)
* [ebcb3d4 ANDROID: sdcardfs: Use pr_[...] instead of printk](https://github.com/ppajda/kernel_g3/commit/ebcb3d453f740a49cd61cc479e5fb46537ccdabc)
* [906949e ANDROID: sdcardfs: remove unneeded null check](https://github.com/ppajda/kernel_g3/commit/906949ef0f97157d0f4656bbc7ba981b56ccefbd)
* [abfc58f ANDROID: sdcardfs: Fix style issues with comments](https://github.com/ppajda/kernel_g3/commit/abfc58f82a66e3888300d568295b77fc297e318a)
* [8c07e7e ANDROID: sdcardfs: Fix formatting](https://github.com/ppajda/kernel_g3/commit/8c07e7ecf2b51479d7ac42fdb714bf8b6e5052c5)
* [4d6cb8ab ANDROID: sdcardfs: correct order of descriptors](https://github.com/ppajda/kernel_g3/commit/4d6cb8abad2549217fc3855e0a6ebdd79963b40f)
* [877c95f ANDROID: sdcardfs: Fix gid issue](https://github.com/ppajda/kernel_g3/commit/877c95f8e7136c17e6954e3459bbb3e15b4d5105)
* [b6a59c1 ANDROID: sdcardfs: Use tabs instead of spaces in multiuser.h](https://github.com/ppajda/kernel_g3/commit/b6a59c16a35d78b395b6566c52f2c807ad63f6e3)
* [a3e940f ANDROID: sdcardfs: Remove uninformative prints](https://github.com/ppajda/kernel_g3/commit/a3e940f7d5a24e5d1673b999caa51b2033e20487)
* [5c8c24d ANDROID: sdcardfs: move path_put outside of spinlock](https://github.com/ppajda/kernel_g3/commit/5c8c24dbf14801c485cccf53253b8a4007073778)
* [7efe8d1 ANDROID: sdcardfs: Use case insensitive hash function](https://github.com/ppajda/kernel_g3/commit/7efe8d1b536f45e6f32621db1c2e9c142a933aef)
* [a8b1867 ANDROID: sdcardfs: declare MODULE_ALIAS_FS](https://github.com/ppajda/kernel_g3/commit/a8b18670540da59ca39864edc3a7107abf644e9c)
* [cb0dc32 fs: Limit sys_mount to only request filesystem modules.](https://github.com/ppajda/kernel_g3/commit/cb0dc320042d5ef2f294fce157b64fc41d536a85)
* [c49004b ANDROID: sdcardfs: Get the blocksize from the lower fs](https://github.com/ppajda/kernel_g3/commit/c49004b20575c28d984c0812acf337a4cd07f06c)
* [c6f3491 ANDROID: sdcardfs: Use d_invalidate instead of drop_recurisve](https://github.com/ppajda/kernel_g3/commit/c6f34914efcc3341997f73d6101490a2b41986bd)
* [b9fca4d ANDROID: sdcardfs: Switch to internal case insensitive compare](https://github.com/ppajda/kernel_g3/commit/b9fca4d5524b1c28145d906c66c70b13d9234f50)
* [0a6989e ANDROID: sdcardfs: Use spin_lock_nested](https://github.com/ppajda/kernel_g3/commit/0a6989e2174d30bf213e256b131ae7c470bbce0c)
* [e0f58fd ANDROID: sdcardfs: Replace get/put with d_lock](https://github.com/ppajda/kernel_g3/commit/e0f58fd64978fd704c068cdf93ca7d7b8cec5457)
* [561678c ANDROID: sdcardfs: rate limit warning print](https://github.com/ppajda/kernel_g3/commit/561678c609194dc0181efa18c8ba1ef57d9bf94d)
* [9348fc1b ANDROID: sdcardfs: support direct-IO (DIO) operations](https://github.com/ppajda/kernel_g3/commit/9348fc1b5d05a77d555b430c0a9563b5745f61e3)
* [350f1fe ANDROID: sdcardfs: implement vm_ops->page_mkwrite](https://github.com/ppajda/kernel_g3/commit/350f1fe52577ae3fe9dcc3fa74c648cc38a9f583)
* [0bf289a ANDROID: sdcardfs: Don't bother deleting freelist](https://github.com/ppajda/kernel_g3/commit/0bf289a6dba8a5120b1d8a5447d67b9aa9b07836)
* [769dad9 ANDROID: sdcardfs: Add missing path_put](https://github.com/ppajda/kernel_g3/commit/769dad928e4c3d80c42acc678fbdf0ef13d1fb31)
* [93990ea ANDROID: sdcardfs: Fix incorrect hash](https://github.com/ppajda/kernel_g3/commit/93990eaad5731738f0f83a5271f1faf8cab67e30)
* [8ec6a43 ANDROID: sdcardfs: Switch strcasecmp for internal call](https://github.com/ppajda/kernel_g3/commit/8ec6a4379a708a7d688b64a057e60e9ed85fe30e)
* [cf2bcf6 constify d_lookup() arguments](https://github.com/ppajda/kernel_g3/commit/cf2bcf6509544e989cc660931f3d55f3a93a3d99)
* [c432ffe constify __d_lookup() arguments](https://github.com/ppajda/kernel_g3/commit/c432ffe712c1a92324f339458d8b2442c63a1127)
* [61a232f ANDROID: sdcardfs: switch to full_name_hash and qstr](https://github.com/ppajda/kernel_g3/commit/61a232f953d3c3d675e619706baff06807cf8c06)
* [c5ec15d ANDROID: sdcardfs: Add GID Derivation to sdcardfs](https://github.com/ppajda/kernel_g3/commit/c5ec15dd4344b6d85a54cce6807365751e3f3141)
* [919bc71 ANDROID: sdcardfs: Remove redundant operation](https://github.com/ppajda/kernel_g3/commit/919bc71950b4494f092a1cef0a6990e0f992488e)
* [36b1bd3 ANDROID: sdcardfs: add support for user permission isolation](https://github.com/ppajda/kernel_g3/commit/36b1bd3b4beadc2bf1747eb05ffbabb1d178fc2d)
* [f3955e6 ANDROID: sdcardfs: Refactor configfs interface](https://github.com/ppajda/kernel_g3/commit/f3955e607351a3f5f07865d4e0d8e0929e517c39)
* [45cfa9d ANDROID: sdcardfs: Allow non-owners to touch](https://github.com/ppajda/kernel_g3/commit/45cfa9d54cc28a0b8d8086c614321e33ec11058e)
* [4848f26 ANDROID: mnt: remount should propagate to slaves of slaves](https://github.com/ppajda/kernel_g3/commit/4848f26a9ba4486cf22397b916d19d94dd607a86)
* [02b1c7e ANDROID: sdcardfs: Fix locking issue with permision fix up](https://github.com/ppajda/kernel_g3/commit/02b1c7e9463e2018f1d360f0f86dbe122c94c4df)
* [30c9b8f ANDROID: vfs: Missed updating truncate to truncate2](https://github.com/ppajda/kernel_g3/commit/30c9b8fc95f5041255cd2a85e7341825fc521244)
* [d9ea396 BACKPORT: smarter propagate_mnt()](https://github.com/ppajda/kernel_g3/commit/d9ea396e6efe141e9246592a86dc02cb4f99fd91)
* [89a9a56 BACKPORT: don't bother with propagate_mnt() unless the target is shared](https://github.com/ppajda/kernel_g3/commit/89a9a56ba6d321ec83b6933788f774902e2c5f10)
* [ae25e75 sdcardfs: Change magic value](https://github.com/ppajda/kernel_g3/commit/ae25e7516b5f8d33a56daeb689ca1399d8e7fcde)
* [9ca4d4e sdcardfs: Use per mount permissions](https://github.com/ppajda/kernel_g3/commit/9ca4d4e1f1e57b6019d0e777cd8af305babd2850)
* [b3373e7 sdcardfs: Add gid and mask to private mount data](https://github.com/ppajda/kernel_g3/commit/b3373e7e9cb566d8f0826eb1705e30743e5e7b10)
* [d3b3fc8 sdcardfs: User new permission2 functions](https://github.com/ppajda/kernel_g3/commit/d3b3fc848b0ddc3741a74ab3e2a931693c383bd4)
* [daf1538 vfs: Add setattr2 for filesystems with per mount permissions](https://github.com/ppajda/kernel_g3/commit/daf1538434c597f86e865f97335f5f5574899a0b)
* [7fba639 vfs: Add permission2 for filesystems with per mount permissions](https://github.com/ppajda/kernel_g3/commit/7fba6399dc5c440e6babf0dab14401909938e288)
* [866282b vfs: Allow filesystems to access their private mount data](https://github.com/ppajda/kernel_g3/commit/866282bd8d354445d66175ddc7eead261ba210ca)
* [0df5aba mnt: Add filesystem private data to mount points](https://github.com/ppajda/kernel_g3/commit/0df5aba8e0ee27e53264ee8a1e8b90876b67e0fd)
* [ceef290 ANDROID: sdcardfs: Fix backport issue for 3.10](https://github.com/ppajda/kernel_g3/commit/ceef290f5fed38cd53811f8226c66bbe0cfcd7de)
* [c95354a sdcardfs: Move directory unlock before touch](https://github.com/ppajda/kernel_g3/commit/c95354aed11ed7828b0b32e29cbbf8f7f78a1008)
* [3fac9b7 sdcardfs: fix external storage exporting incorrect uid](https://github.com/ppajda/kernel_g3/commit/3fac9b74d033b10fc4b222786bf6400269db6261)
* [87ca162 sdcardfs: Added top to sdcardfs_inode_info](https://github.com/ppajda/kernel_g3/commit/87ca16221066cd7fbeefc34b549ed9fde58b4149)
* [acfc675 sdcardfs: Switch package list to RCU](https://github.com/ppajda/kernel_g3/commit/acfc6758fab4f036fa8a4e1e234c7e831ff07d95)
* [bc51a6f sdcardfs: Fix locking for permission fix up](https://github.com/ppajda/kernel_g3/commit/bc51a6f5b1c7162b55a22a41786bf29f6b24ec47)
* [3b852e7 sdcardfs: Check for other cases on path lookup](https://github.com/ppajda/kernel_g3/commit/3b852e778fc14097c786fc3f3efdd5b00b42da84)
* [5410795 sdcardfs: override umask on mkdir and create](https://github.com/ppajda/kernel_g3/commit/541079543a16b3660734b400d20241feabcce48a)
* [4160133 ANDROID: sdcardfs: fix itnull.cocci warnings](https://github.com/ppajda/kernel_g3/commit/41601330534c495fbcbee0b46d8c2f2bbba0aed2)
* [d89e0b5c sdcardfs: Truncate packages_gid.list on overflow](https://github.com/ppajda/kernel_g3/commit/d89e0b5cb84cc0ac988d92645dc6c7b0e69d63cf)
* [e22ffaf vfs: change d_canonical_path to take two paths](https://github.com/ppajda/kernel_g3/commit/e22ffaf4fcc0539fd80d86927206f67711296238)
* [6bcb597 sdcardfs: remove unneeded __init and __exit](https://github.com/ppajda/kernel_g3/commit/6bcb597b3412575a0e141dd1ce14ec4d5c61dfc7)
* [f003660 sdcardfs: Remove unused code](https://github.com/ppajda/kernel_g3/commit/f003660b452e8943c2c062fb1de1631702b46f94)
* [27d3a0c sdcardfs: remove effectless config option](https://github.com/ppajda/kernel_g3/commit/27d3a0cadd5f0be44c4683543f74a9f8ff7ffe3e)
* [1e14473 sdcardfs: Add support for d_canonicalize](https://github.com/ppajda/kernel_g3/commit/1e1447383866f5270a817b2e7b3ca8349a10695e)
* [7211728 sdcardfs: Bring up to date with Android M permissions:](https://github.com/ppajda/kernel_g3/commit/72117281832e4e5f07504a37a7ea6e7993dc5039)
* [3892259 sdcardfs: Changed type-cast in packagelist management](https://github.com/ppajda/kernel_g3/commit/3892259c38239c3676daeec51b162dccf980759b)
* [0e08304 sdcardfs: Port to 3.4](https://github.com/ppajda/kernel_g3/commit/0e0830499dd3903f8703171f55a4e6a6141657ac)
* [b59779e Included sdcardfs source code for kernel 3.0](https://github.com/ppajda/kernel_g3/commit/b59779ed63fff444065bb8412dc42d6d095aaefe)
* [b55a6b3 consitify do_mount() arguments](https://github.com/ppajda/kernel_g3/commit/b55a6b3e4d9a68ebf07e11adfe5c5dea67cdc607)
* [10fc3b7 do_add_mount()/umount -l races](https://github.com/ppajda/kernel_g3/commit/10fc3b74424b9f8b81758e6f43fe0674e8eea1a5)
* [459d6a5 fs: introduce inode operation ->update_time](https://github.com/ppajda/kernel_g3/commit/459d6a56e4511b3620531ae224369b41eda69ad9)
* [0c3fe72 VFS: Comment mount following code](https://github.com/ppajda/kernel_g3/commit/0c3fe7209555f896fc99abb8a21d3724592f627d)
* [6d1799f3 VFS: Make clone_mnt()/copy_tree()/collect_mounts() return errors](https://github.com/ppajda/kernel_g3/commit/6d1799f39bd0482f6bc4d881d9c44c269ea47bd9)
* [c3e82f7 get rid of magic in proc_namespace.c](https://github.com/ppajda/kernel_g3/commit/c3e82f7cbfc33a482c7a7455ea508dace6671149)
* [be576c1 get rid of ->mnt_longterm](https://github.com/ppajda/kernel_g3/commit/be576c15f8f9c304d693ae675d030e61a64c42dd)
* [18ba2fc brlocks/lglocks: API cleanups](https://github.com/ppajda/kernel_g3/commit/18ba2fceea06e6d2a08cd808c383b0874c479123)
* [2fc5d7a brlocks/lglocks: turn into functions](https://github.com/ppajda/kernel_g3/commit/2fc5d7aebf45865ba950318060bd3469956a1e64)
* [22dd229 lglock: remove online variants of lock](https://github.com/ppajda/kernel_g3/commit/22dd2291b23f6df0dbe555b998d52caaf4f8333a)
* [7fb8cb5 Revert "get rid of s_files and files_lock"](https://github.com/ppajda/kernel_g3/commit/7fb8cb580c8ab3e6c5a55d39186e7f8af8c0d4c3)
* [c8b66f1 g3: remove support for sdcardfs](https://github.com/ppajda/kernel_g3/commit/c8b66f173c48142958ff63fd426bced862bb2974)

***

12-05-2017
====================

* [0368d32 Merge branch 'los-15.0-slim' of https://github.com/ppajda/kernel_g3 into los-15.0-slim](https://github.com/ppajda/kernel_g3/commit/0368d32c4098c651ad74c12ea3a16f96990530db)

***

12-03-2017
====================


***

11-29-2017
====================


***

11-27-2017
====================

* [6ae2436 dts: msm8974.dtsi: tweaks](https://github.com/ppajda/kernel_g3/commit/6ae24360cc97bbd24e08b5cc69531f68027543f6)

***

11-25-2017
====================

* [e01f8d7 bq5102x: remove __dev macro](https://github.com/ppajda/kernel_g3/commit/e01f8d79731428630552c926159cd207fdfdd3d6)
* [8e40bd6 Regen defconfigs](https://github.com/ppajda/kernel_g3/commit/8e40bd63b90fc2cac91a83b62f5958c48262ec0c)
* [8bc39df Remove cache dumping and the L1/L2 cache error reporting driver](https://github.com/ppajda/kernel_g3/commit/8bc39dfa289608e554c8a2408f399fb39d3e5eba)
* [7f5644b Cleanup](https://github.com/ppajda/kernel_g3/commit/7f5644bf74e07b6dba114963045853763701e60e)

***

11-24-2017
====================


***

11-23-2017
====================

* [7b78072 Fix compile with gcc 7.x](https://github.com/ppajda/kernel_g3/commit/7b78072c2c8911cf84ac979a40e8076e6542fc05)
* [c32a157 Updates to cpu-boost, msm-limiter, bricked and msm hotplugs](https://github.com/ppajda/kernel_g3/commit/c32a157c342539d1ffbe52a890f33b74ffee577a)
* [4f26526 msm_rq_stats: update for bricked hotplug add get_rq_info Signed-off-by: DerRomtester <dieb.stefan.96@gmail.com>](https://github.com/ppajda/kernel_g3/commit/4f2652676ee53908f6a1eb37ed5823a312f7ec65)
* [c49989b msm: rq_stats: Register for Cpufreq policy notification](https://github.com/ppajda/kernel_g3/commit/c49989b0a556f356660554ace00982d85e7dbccc)
* [66dbe30 msm: rq_stats: Add hotplug enable toggle](https://github.com/ppajda/kernel_g3/commit/66dbe30c4a64129fb225e77c09cdd65a988531b0)
* [3f7ab6b soc: qcom: rq_stats: remove the redundant iowait check](https://github.com/ppajda/kernel_g3/commit/3f7ab6b146cf6d47f9cda45d346aba22df7205aa)
* [2cd87f5 rq_stats: Fix usage of cpufreq APIs](https://github.com/ppajda/kernel_g3/commit/2cd87f517e692f399a9fb9ef74d83d1d6a3efde6)
* [31a3ee4 soc: qcom: rq_stats: Always show idle time left](https://github.com/ppajda/kernel_g3/commit/31a3ee45a334c4a1e95c6a5cc20a27f925dac492)
* [038da76 msm: rq_stats: Calculate load based on current freq limit](https://github.com/ppajda/kernel_g3/commit/038da76a5553d947e3e9df7e1b107845bbc93559)

***

11-22-2017
====================

* [545bbae msm: msm_mpdecision: disable by default at boot](https://github.com/ppajda/kernel_g3/commit/545bbaeab29129336279d4dc70f17fd985affad7)
* [83d3cc7 msm: Fix high load average from uninterruptible waits](https://github.com/ppajda/kernel_g3/commit/83d3cc7a7a55e1c2bcf0f7092c057ad8be037674)
* [89153ba msm: pm: Increase cpu collapse timeout](https://github.com/ppajda/kernel_g3/commit/89153ba43e08af52d97604fb769d4400aaa1c5a3)

***

11-21-2017
====================

* [7484a4b Remove a whole set of __dev... macros](https://github.com/ppajda/kernel_g3/commit/7484a4bf95c8d23b455ba6ae8450e3a291cb00b9)
* [7f0b1b3 Update msm-limiter](https://github.com/ppajda/kernel_g3/commit/7f0b1b3eab642602b634c31997a6f216b662d013)

***

11-17-2017
====================

* [226104e Fix derp](https://github.com/ppajda/kernel_g3/commit/226104e88d3e23e5cd4ca3b626d88682c3534eb9)
* [65fd207 math64: Add mul_u64_u32_shr()](https://github.com/ppajda/kernel_g3/commit/65fd2073c80f3bfd515cd40b5c7793afb4a7242e)
* [0cce04d sched/fair: Move load idx selection in find_idlest_group](https://github.com/ppajda/kernel_g3/commit/0cce04d42881d86fb2fdfb0ba6fc4a7a532dcc52)
* [18febaf sched: Remove unnecessary iteration over sched domains to update nr_busy_cpus](https://github.com/ppajda/kernel_g3/commit/18febafc372ad858689e95e84267974a024953de)
* [6945e1b sched/fair: Rework sched_fair time accounting](https://github.com/ppajda/kernel_g3/commit/6945e1b2d95cb6bd5651b3360b53fc49b176730c)
* [184d117 sched: Fix asymmetric scheduling for POWER7](https://github.com/ppajda/kernel_g3/commit/184d117454e4ed6eac13884561b4623203e02018)
* [eceda8e sched: Remove one division operation in find_busiest_queue()](https://github.com/ppajda/kernel_g3/commit/eceda8e2b1e4440d7846e3b39668cab836058328)
* [645b4e4 sched: Remove the useless declaration in kernel/sched/fair.c](https://github.com/ppajda/kernel_g3/commit/645b4e4eeadd47e7d124b277057a069a2ce98971)
* [b8452c4 sched: Refine the code in unthrottle_cfs_rq()](https://github.com/ppajda/kernel_g3/commit/b8452c414d90c53bddfddf773053b5f34d8df91b)
* [392a699 sched: Update rq clock earlier in unthrottle_cfs_rq](https://github.com/ppajda/kernel_g3/commit/392a69959a566f5d4d8c256ec6dce0f9875d73e0)
* [52dfd9d sched: Update rq clock before setting fair group shares](https://github.com/ppajda/kernel_g3/commit/52dfd9dfbb4caf9a2763f63f2a164a4d0bfb6e43)
* [1f0dca6 sched: Use this_rq() helper](https://github.com/ppajda/kernel_g3/commit/1f0dca6195d146550e3066df08e31b457d706e14)
* [ca5eafe sched: Fix init NOHZ_IDLE flag](https://github.com/ppajda/kernel_g3/commit/ca5eafea69a7898777966e4960df9bd18c6e4201)
* [ec851c8 sched: Move update_load_*() methods from sched.h to fair.c](https://github.com/ppajda/kernel_g3/commit/ec851c86bddf58175250159a8f94c478a94b3186)
* [b92935a sched: Rename load_balance_tmpmask to load_balance_mask](https://github.com/ppajda/kernel_g3/commit/b92935a8d9d6dca2ec845ea2c7a979f240a04f10)
* [329197e sched: Move up affinity check to mitigate useless redoing overhead](https://github.com/ppajda/kernel_g3/commit/329197e54a5e0d1e89625b28dfb77d8f4f125efe)
* [4838348 sched: Explicitly cpu_idle_type checking in rebalance_domains()](https://github.com/ppajda/kernel_g3/commit/48383486c8febdb4f2201575576097a31a149efa)
* [37b14d2 sched: Change position of resched_cpu() in load_balance()](https://github.com/ppajda/kernel_g3/commit/37b14d2499b82241b1de2c3f764016c3aea3639e)
* [6035291 sched: Fix variable name misnomer, add comments](https://github.com/ppajda/kernel_g3/commit/6035291c16b51b63406b9fc933be754ce9a11166)
* [9743ad6 sched: Make default_scale_freq_power() static](https://github.com/ppajda/kernel_g3/commit/9743ad6306a5fb6d78ef0def39ee98b5a24f046a)
* [00cadd2 sched: Fix warning in kernel/sched/fair.c](https://github.com/ppajda/kernel_g3/commit/00cadd22c623fc686e71b47f8974fce23a9c05a6)
* [3ce7af7 sched: Fix wrong rq's runnable_avg update with rt tasks](https://github.com/ppajda/kernel_g3/commit/3ce7af7c01d645529cc60eea633431f6351d7879)
* [c4d0e60 sched: add missing headers and cleanup duplicate functions](https://github.com/ppajda/kernel_g3/commit/c4d0e6076facf998e2cf282ca4f067e08a8ad1f3)
* [de82c1c sched: Simplify can_migrate_task()](https://github.com/ppajda/kernel_g3/commit/de82c1ca1562c21a6996908ebbdc31c6bbc3670c)
* [29ebd11 sched: Fix select_idle_sibling() bouncing cow syndrome](https://github.com/ppajda/kernel_g3/commit/29ebd1101ce88dbaa9ed8a97cbe7616d4d231c1e)
* [abd76ff sched: Micro-optimize the smart wake-affine logic](https://github.com/ppajda/kernel_g3/commit/abd76ffe84d591abeeccafdb8e6e2d99e65a82e6)
* [a9120b6 sched: Implement smarter wake-affine logic](https://github.com/ppajda/kernel_g3/commit/a9120b694149eea7fa2950418ebb9b85539468e2)
* [f33ac28 sched/nohz: Clean up select_nohz_load_balancer()](https://github.com/ppajda/kernel_g3/commit/f33ac28ee1e92bd1775d0703075aabbcdedd7f0e)
* [2d02f74 sched: packing task to per cpu horse power in periodic balance](https://github.com/ppajda/kernel_g3/commit/2d02f747b4233620461d77275ff50492547d10db)
* [c17b6e1 sched: packing task per cpu power in fork/exec/wakeup balance](https://github.com/ppajda/kernel_g3/commit/c17b6e109b7166c2e73640fa08184a5193fb4c0d)
* [4df47aa sched: only use instant utilization in burst wakeup balance](https://github.com/ppajda/kernel_g3/commit/4df47aac20fc921fcde6ae13cc1784c1774efcbf)
* [167a858 sched: make sure select_tas_rq_fair get a cpu](https://github.com/ppajda/kernel_g3/commit/167a858d2de0fbeb83d66857f8efe3cbc1304ca2)
* [7292e6e sched: don't do power balance on share cpu power domain](https://github.com/ppajda/kernel_g3/commit/7292e6e7bb5275bc9e278e427c15f6761dd8512b)
* [60de632 sched: lazy power balance](https://github.com/ppajda/kernel_g3/commit/60de632f64d6d708f35ce64fe5c50adeebed7f57)
* [f7a621d sched: power aware load balance](https://github.com/ppajda/kernel_g3/commit/f7a621d158b8619bfdd0229fbd9869cd62585646)
* [512cafc sched: add new members of sd_lb_stats](https://github.com/ppajda/kernel_g3/commit/512cafc87211166d81eda18e9cf99b5e7733b0d0)
* [dae2441 sched: no balance for prefer_sibling in power scheduling](https://github.com/ppajda/kernel_g3/commit/dae2441c265e089a7c0550a8fbc7cac52486f253)
* [dda51ac Remove duplicate variables in kernel/sched/fair.c](https://github.com/ppajda/kernel_g3/commit/dda51ac9fcba079bc8c94a1114e242a2b8c802cf)
* [9df71c6 sched: pull all tasks from source group](https://github.com/ppajda/kernel_g3/commit/9df71c6d7acc538dad361ff48c96a17de8faee13)
* [0ba9047 sched: add power/performance balance allow flag](https://github.com/ppajda/kernel_g3/commit/0ba9047f09e0853db11669e11aa8032fb55c1d41)
* [dd1eaa9 sched: packing transitory tasks in wakeup power balancing](https://github.com/ppajda/kernel_g3/commit/dd1eaa948025c0cc6b04b49428a7cc151e0ae717)
* [7ecddbc sched: using avg_idle to detect bursty wakeup](https://github.com/ppajda/kernel_g3/commit/7ecddbc19cc3372fee762cdfe78d03db5e81b622)
* [c27c122 sched: add sched_burst_threshold_ns as wakeup burst indicator](https://github.com/ppajda/kernel_g3/commit/c27c122301f10f966989269e010fc63e21788267)
* [d0b89a8 sched: add power aware scheduling in fork/exec/wake](https://github.com/ppajda/kernel_g3/commit/d0b89a81735158dfbc9c17f19a687590c7c65ef6)
* [b57b547 sched: get rq potential maximum utilization](https://github.com/ppajda/kernel_g3/commit/b57b5477b7982f3adc00e872eca0418749909890)
* [ab3e09f9 sched: scale_rt_power rename and meaning change](https://github.com/ppajda/kernel_g3/commit/ab3e09f9e51561c659f2ef01f43f952f2bc1c878)
* [23bafeb sched: move sg/sd_lb_stats struct ahead](https://github.com/ppajda/kernel_g3/commit/23bafeb22e8920e32d782e2f1bbf627e89556833)
* [ccd661e sched: add new sg/sd_lb_stats fields for incoming fork/exec/wake balancing](https://github.com/ppajda/kernel_g3/commit/ccd661eaa10dd15bdfe448fb30d5e658417797fa)
* [aaefd93 sched: log the cpu utilization at rq](https://github.com/ppajda/kernel_g3/commit/aaefd93443969af02bf34089b523001defe31343)
* [1480b53 sched: add sysfs interface for sched_balance_policy selection](https://github.com/ppajda/kernel_g3/commit/1480b536ddb1d2aa31ad9a0a5f403396c7b3a622)
* [dbccb63 sched: add sched balance policies in kernel](https://github.com/ppajda/kernel_g3/commit/dbccb63ca92e89f2987a26d9fe2b488b88a9dbd1)
* [40c8e35 sched: set initial value of runnable avg for new forked task](https://github.com/ppajda/kernel_g3/commit/40c8e357257cde60eb5056fa2f32e0dc69c9aac7)
* [f9f6079 tune asmp hotplug](https://github.com/ppajda/kernel_g3/commit/f9f60794a7c2f448efca1f3b3376e370c1a22f3d)
* [24ff5fd lm3697: Add state notifier](https://github.com/ppajda/kernel_g3/commit/24ff5fdf7ad2ee8ee445b3372065fd2219a9c116)
* [94394d4 powersuspend: add backlight driver hook](https://github.com/ppajda/kernel_g3/commit/94394d46d7ca33198d83e3254ed02a1cebacc618)
* [c5764fb LM3697: add sleep_state hook sysfs](https://github.com/ppajda/kernel_g3/commit/c5764fb9f119d744de2e6b1f4793d6dfda53bc69)
* [7804f3f video: backlight: lm3697: Introduce backlight control](https://github.com/ppajda/kernel_g3/commit/7804f3f8e424819a558a2b9f868e241a927de0cd)

***

11-16-2017
====================

* [05ee3b6 Fix build](https://github.com/ppajda/kernel_g3/commit/05ee3b62f2e0179deeda53bf061991f5d5dff321)
* [ed5b1c2 Update msm_hotplug, cpu-boost, impulse gov](https://github.com/ppajda/kernel_g3/commit/ed5b1c24e3d5f9adcc2afda67dbf441eec3f605b)
* [f297f92 Add umbrella_core gov](https://github.com/ppajda/kernel_g3/commit/f297f92a254c0e4c8f5ad5f19ce4263a3791203c)
* [52cc8a7 Fix makefile](https://github.com/ppajda/kernel_g3/commit/52cc8a775e4db576ef9c97a5b57106da59b0d97d)
* [c707156 cpufreq: Introduce new relation for freq selection](https://github.com/ppajda/kernel_g3/commit/c707156b02d3579d211ea3fa5e38c71b6cbfe066)
* [5c6a064 Add nightmare, smartmax, smartmax_eps governons](https://github.com/ppajda/kernel_g3/commit/5c6a064d2967e460519582970d6320d2db1778bb)
* [d6bb688 cpufreq_stats: sync to complete update](https://github.com/ppajda/kernel_g3/commit/d6bb68831aea27cd19d7fdd13ddf449f35dceea7)
* [c7b106f cpufreq / stats: Get rid of CPUFREQ_STATDEVICE_ATTR](https://github.com/ppajda/kernel_g3/commit/c7b106f1b9224d7a4b4237cfe206955ba0a307c3)
* [28d2635 Fix cpufreq_stats.c Use u64 instead cputime64_t](https://github.com/ppajda/kernel_g3/commit/28d26355f4d95c72e02424565ad45a7e7c382781)
* [a07de8e [upstream]:cpufreq: add cpufreq_governor (only needs for my tree to add more cpu governor from 3.10.y branch)](https://github.com/ppajda/kernel_g3/commit/a07de8e2e7024f20c3571b86a17e07a2a02c703f)
* [a6afbf8 cpufreq: add upstream 3.10.y driver needs](https://github.com/ppajda/kernel_g3/commit/a6afbf8142b35eedfb31a3cd761acbc4913e064d)
* [c2e2c2f arm: boot: compressed: Optimize for cortex a15](https://github.com/ppajda/kernel_g3/commit/c2e2c2f88a2509d3d389650480f576798854e2ac)
* [a8a6496 page-writeback: Increase these numbers to help save some battery](https://github.com/ppajda/kernel_g3/commit/a8a64966991ccfd6e70dde3bd608bbf9c563365c)
* [91ca8c7 fs/sync: Make sync() satisfy many requests with one invocation.](https://github.com/ppajda/kernel_g3/commit/91ca8c72ab620f7c2014631c8dd573e6a344c066)
* [0bf9687 drivers/power/wakeup: add custom wakelock path](https://github.com/ppajda/kernel_g3/commit/0bf9687a8af8b1ffef36f4e58866cc71fe8ae7c8)

***


### [This Changelog was generated automatically Click here to see how](https://github.com/bhb27/BHB27Kernel/tree/N_c/build/changelog.sh)
