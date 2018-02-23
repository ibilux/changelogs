Lineage eXTenDed Kernel los-15.1 source Changelog:
============================================================

02-14-2018
====================

* [776da8e Up version R5](https://github.com/ppajda/kernel_g3/commit/776da8e69862dcd6d50d1c155557360604823c5f)
* [794e14d kgsl: fix derp](https://github.com/ppajda/kernel_g3/commit/794e14da2a9b72929a20cfd57fec12e39ce74d0d)
* [884ec74 proc: modify cmdline to export correct charger mode](https://github.com/ppajda/kernel_g3/commit/884ec74931fd671afcaffa130b6893ddfbbc86ab)
* [43d582c ANDROID: xattr: Pass EOPNOTSUPP to permission2](https://github.com/ppajda/kernel_g3/commit/43d582c92b582425c3a8844ada195437b3633886)
* [7dd1b79 Enable setting security contexts on rootfs inodes.](https://github.com/ppajda/kernel_g3/commit/7dd1b796c7d544927c1052a617d95be613a93dcf)
* [87253b3 selinux: enable genfscon labeling for sysfs and pstore files](https://github.com/ppajda/kernel_g3/commit/87253b3e0f0da3bac258e8f0e9359fae06f5323e)
* [6ae202b selinux: enable per-file labeling for debugfs files.](https://github.com/ppajda/kernel_g3/commit/6ae202b0910bdec88f9ecef69b9e9d8dff248aff)
* [47a196d defconfigs: cleanup](https://github.com/ppajda/kernel_g3/commit/47a196df5dce798102b6ab8f75162969a30ab1df)
* [95bbfd1 usb: gadget: fix build](https://github.com/ppajda/kernel_g3/commit/95bbfd1af182ce5e0283830ce6f7c8b6abcfed82)
* [bc0e549 Revert "usb: gadget: f_hid: fix build error"](https://github.com/ppajda/kernel_g3/commit/bc0e549fa20af39ff671b2f98dc7d2e75925d289)
* [a6ae7e0 defconfig: Disable CONFIG_MSM_SMP2P_TEST](https://github.com/ppajda/kernel_g3/commit/a6ae7e0ffa839164ac8004cd265fc7ffe6fc20d2)
* [6ab8067 defconfig: Disable perf events](https://github.com/ppajda/kernel_g3/commit/6ab8067d97804af02550670318b06f71102280ed)

***

01-30-2018
====================

* [85facad kgsl: fix derp](https://github.com/ppajda/kernel_g3/commit/85facad937e4574f4eeddf7eac7b2401f0ca6453)
* [6beca95 include: Include dummy MSM Audio Calibration header * This needs to be included in apq8084/msm8974 kernel's exported headers to build the msm audio hal as of oreo-mr1. * Demon000 deserves credit for the initial idea behind this commit, as he pointed out which structs were used.](https://github.com/ppajda/kernel_g3/commit/6beca95b8678b4b0cc2ac0ee8267d9c130312a9a)
* [58745d7 ANDROID: binder: fix OOB write in __binder_update_page_range](https://github.com/ppajda/kernel_g3/commit/58745d7ad18d094eb0e317ce8d585af1a3d1b222)
* [3fd68eb UPSTREAM: include/linux/mm.h: add PAGE_ALIGNED() helper](https://github.com/ppajda/kernel_g3/commit/3fd68eb48e23fd829b5f602e3f479536d3e7b1c7)
* [14e1de8 android: binder: Move buffer out of area shared with user space](https://github.com/ppajda/kernel_g3/commit/14e1de8f4ee067ff44c0fd183a3e163864dbff77)
* [b279afe android: binder: Refactor prev and next buffer into a helper function](https://github.com/ppajda/kernel_g3/commit/b279afe1949061ff42592ca4e230b5d401fe7efd)
* [e1871b2 BACKPORT: staging: android: fix missing a blank line after declarations](https://github.com/ppajda/kernel_g3/commit/e1871b2d45aa9551c4dd581a894269889db840b4)
* [1397539 UPSTREAM: Staging: Android: removed an unnecessary else statement](https://github.com/ppajda/kernel_g3/commit/13975395c64734206cd955ecbc6613177fbe6f29)
* [782c903 binder: always allocate/map first BINDER_MIN_ALLOC pages](https://github.com/ppajda/kernel_g3/commit/782c903dd14fa3e640ca12a2ae278be88b954f76)
* [b50ea73 ANDROID: sdcardfs: Move default_normal to superblock](https://github.com/ppajda/kernel_g3/commit/b50ea738be6deb88a8a794afb844366f5e614eca)
* [53a309d kgsl: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/53a309d7483cf61e5f3d7340b9b5d7c43ccc28cf)
* [52d5fb8 uio: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/52d5fb809ea34dc43ffb23ccbf01c95741ee1009)
* [e7a36f4 spmi: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/e7a36f477d520ea51dc7aab9a22043c782763d5c)
* [fa893fd slimbus: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/fa893fdbbffd6abe7f6a2c3f9c8036c64a527c58)

***

01-24-2018
====================


***

01-23-2018
====================

* [193422b BACKPORT: ARM: dts: msm: Mount the system partition during early init](https://github.com/ppajda/kernel_g3/commit/193422b5cacef6d9ac16ddcb64bac8100b60737d)

***

01-15-2018
====================

* [b5b5132 mm: change max readahead size to 512KB](https://github.com/ppajda/kernel_g3/commit/b5b5132f659b8b7a6129b925846c763364227adc)
* [85b6b84 BACKPORT: ARM: dts: msm: Mount the system partition during early init](https://github.com/ppajda/kernel_g3/commit/85b6b849b2daa313434c668987ac6add1e0776e8)
* [20d534a ANDROID: sdcardfs: Fix missing break on default_normal](https://github.com/ppajda/kernel_g3/commit/20d534a9b20ed10b48c8c2c887f50afb8b491fca)
* [70f0115 msm: cpp: Fix for integer overflow in cpp](https://github.com/ppajda/kernel_g3/commit/70f0115cf19766c61149bd795dcab75bb636e17d)
* [5a6b96a msm: vidc: Check video buffer handle for Null pointer access.](https://github.com/ppajda/kernel_g3/commit/5a6b96a5f100c2c0843d506709581da0f3efa981)
* [2b00a2f msm:vidc: Fix klockwork errors in video driver.](https://github.com/ppajda/kernel_g3/commit/2b00a2fe658f766a130debacfb9d061bab6198f2)
* [17b2257 msm:vidc: Add null check for handle in smem buffer comparision.](https://github.com/ppajda/kernel_g3/commit/17b22573f2b0f043577dd1ff9048bc4e4bd68639)
* [926e835 msm: vidc: add ion_handle checking before mapping buffers.](https://github.com/ppajda/kernel_g3/commit/926e83574db47dfae3c04c20c3f28e91f6a91316)
* [6b2f57e msm: camera: cpp: Add validation for v4l2 ioctl arguments](https://github.com/ppajda/kernel_g3/commit/6b2f57e8d20b1f301dc3fae07c5629f7dd5c97d1)
* [690f1ff staging: android: ashmem: fix a race condition in ASHMEM_SET_SIZE ioctl](https://github.com/ppajda/kernel_g3/commit/690f1ff7aed686279d5c777b70594cbcd2e74bea)
* [08b8bd5 ANDROID: mnt: Fix freeing of mount data](https://github.com/ppajda/kernel_g3/commit/08b8bd5b17fd10f8284a39d5f38597696519cd91)
* [7b8325d ANDROID: sdcardfs: Add default_normal option](https://github.com/ppajda/kernel_g3/commit/7b8325df55be2a51bd1ff8bcc6c63c6ae7029c27)
* [8d6ca6e ANDROID: sdcardfs: notify lower file of opens](https://github.com/ppajda/kernel_g3/commit/8d6ca6e9f424e4281aa5fa1f01af48a06bc5bb27)
* [bcecfa1 changes kernel headers](https://github.com/ppajda/kernel_g3/commit/bcecfa189815506812b67da997219ea8594ab0c9)
* [526e094 Fastcharge: Increase ac charge to 1800mA](https://github.com/ppajda/kernel_g3/commit/526e0943aae833a494708887ead9955d5752b338)
* [f91178b Add binder devices](https://github.com/ppajda/kernel_g3/commit/f91178b539bdb048b1dec68be3dd7117f151c290)
* [653eb55 msm: camera: move firmware to vendor](https://github.com/ppajda/kernel_g3/commit/653eb551765d54437ba1a31a0b1c1d17eb9fd784)
* [c0c1084 g3: update config to point bcmdhd firmware to vendor](https://github.com/ppajda/kernel_g3/commit/c0c108400102d76977a686b720941dfe9dc6b8f3)
* [5d5bc12 bcmdhd_g3: Update driver from LG's Android N](https://github.com/ppajda/kernel_g3/commit/5d5bc12ce71336e668033bdc2c377e4ed7dc3c07)

***

01-01-2018
====================

* [2c346c6 defconfigs: cleanup](https://github.com/ppajda/kernel_g3/commit/2c346c606159805e84267ef4f14564c06c574920)
* [e57aa0d mmc: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/e57aa0d739309e33276885cb4121dee164a5fd23)
* [4ffc8c2 inotify: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/4ffc8c2ee6461e2e951bc8e53d7b7e7e2dd6ba50)
* [7e1fafe6 ocmem_sched: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/7e1fafe608ec0075bd30340e11f5d9b5c5e36b68)
* [2479ad1 dm: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/2479ad1eb6decf0cc326c4ae3004d8aaca298b67)
* [4c70160 iommu: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/4c7016096bcd8fe7e5ad0e2365787b593734c3f4)
* [00e4018 iommu: moving initialization earlier](https://github.com/ppajda/kernel_g3/commit/00e40181af145de23a40b8a76a54d6a8b9493fb2)
* [68f0d21 cgroup: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/68f0d21b1e919822c403245beb01ecbed539b4ef)
* [fb7e41e tune again thermal](https://github.com/ppajda/kernel_g3/commit/fb7e41eccf8309576b437b3074dffab8fd0c138e)
* [0e445db fs: dynamic fsync: remove powersuspend](https://github.com/ppajda/kernel_g3/commit/0e445dbf98d8b9df8988815dc3fbe8cc761162a2)
* [3e60f40 Fix code errors detected using Linaro GCC 6.1.1-rc1](https://github.com/ppajda/kernel_g3/commit/3e60f40da5ce668ce2ed38351236fd0c0728a4f4)

***

12-27-2017
====================


***

12-26-2017
====================

* [ef98253 mdss: kcal: make colors more vivid](https://github.com/ppajda/kernel_g3/commit/ef982536aaf60c4801093caf067695f73c70acc0)
* [e69659c usb: gadget: f_hid: fix build error](https://github.com/ppajda/kernel_g3/commit/e69659cc6a229771cbead6f1abd24d26cc7b10af)
* [9de43a9 usb: gadget: u_serial: fix typo which cause build warning](https://github.com/ppajda/kernel_g3/commit/9de43a90661291dfcdd50c3efcc073541f94359e)
* [793aa91 usb: gadget: add multiple definition guards](https://github.com/ppajda/kernel_g3/commit/793aa91fe3a0f0385af5078f58edac811b95a206)
* [261d851 Revert "usb: gadget: Enable HID function for charging mode"](https://github.com/ppajda/kernel_g3/commit/261d85123c706f93d4d50617c626f746b66c65a4)
* [06e809a USB: android: Fix a NULL pointer dereference](https://github.com/ppajda/kernel_g3/commit/06e809a32235fa47d854cdcbd25df0670472699a)
* [aff775b usb: dwc3: Do not call WARN_ON_ONCE from interrupt context](https://github.com/ppajda/kernel_g3/commit/aff775b04bfc73ecb6c7d2bea2cc4d13e03b77fe)
* [324da95 usb: gadget: FunctionFS and SuperSpeed updates](https://github.com/ppajda/kernel_g3/commit/324da95f45d70e7578308cbd20b8f96fe86d5f06)
* [003b1f6 f_fs: ffs_func_free: cleanup requests allocated by autoconfig](https://github.com/ppajda/kernel_g3/commit/003b1f6adde6e0d7aad4ddc5ed044eb4561ded23)
* [7d58701 usb: gadget: f_fs: Fix enumeration in fullspeed mode](https://github.com/ppajda/kernel_g3/commit/7d58701cf31e01615270f3a790adae46a246578e)

***

12-24-2017
====================


***

12-22-2017
====================

* [fd25c11 workqueue: fix derp](https://github.com/ppajda/kernel_g3/commit/fd25c11e6d6a5ac162814a7c05224257b232ac73)
* [5dd933f workqueue: Fix flag collision](https://github.com/ppajda/kernel_g3/commit/5dd933f3fbdbf2fcd4233dc4a91f49419d5f3fa9)
* [898645c workqueue: implicit ordered attribute should be overridable](https://github.com/ppajda/kernel_g3/commit/898645cf75c09b848d459cedbc7d3f7352b0b3cb)
* [551e948 workqueue: restore WQ_UNBOUND/max_active==1 to be ordered](https://github.com/ppajda/kernel_g3/commit/551e94813b642488ad0aceedd72cb75cc5579382)
* [6e98810 workqueue.c: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/6e98810641677ea26867e46ad5f2397534ac51dd)
* [7b1a944 workqueue: Add system wide power_efficient workqueues](https://github.com/ppajda/kernel_g3/commit/7b1a944515f16e6b893186d4ab5b8abeeeab4d9f)
* [bf4ceb3 Workqueue: fix permissions](https://github.com/ppajda/kernel_g3/commit/bf4ceb3eaeb25eab4b94ae32ed4a3665b10ed2ac)
* [042d76e workqueue: fix ghost PENDING flag while doing MQ IO](https://github.com/ppajda/kernel_g3/commit/042d76ef836701acc40ceffb6148c5ccd6a4c982)
* [fc088f7 Revert "workqueue: make sure delayed work run in local cpu"](https://github.com/ppajda/kernel_g3/commit/fc088f70c382c129790134857c569363a0675bf6)
* [c97856b workqueue: make sure delayed work run in local cpu](https://github.com/ppajda/kernel_g3/commit/c97856bc0533b22f26010be50488d43b5e58a899)
* [1acec2d workqueue: fix hang involving racing cancel[_delayed]_work_sync()'s for PREEMPT_NONE](https://github.com/ppajda/kernel_g3/commit/1acec2d57ef18769ff5f2bbe815599e9836de050)
* [6161d9c workqueue: fix subtle pool management issue which can stall whole worker_pool](https://github.com/ppajda/kernel_g3/commit/6161d9c12108f39e587a70b10d55c52f1d7b64fc)
* [8655731 workqueue: zero cpumask of wq_numa_possible_cpumask on init](https://github.com/ppajda/kernel_g3/commit/865573147f6c586c35ee40ed81e895bbf6bf8a78)
* [7597d46 workqueue: fix dev_set_uevent_suppress() imbalance](https://github.com/ppajda/kernel_g3/commit/7597d46de0c4cd3ae1744e8b32b97a27471140fa)
* [da283b7 workqueue: make rescuer_thread() empty wq->maydays list before exiting](https://github.com/ppajda/kernel_g3/commit/da283b7aab7924d3cad5c352a3706472db8a56dd)
* [adff70b workqueue: fix a possible race condition between rescuer and pwq-release](https://github.com/ppajda/kernel_g3/commit/adff70ba106e1266a66180fa1fffb4f1aab9330e)
* [0ddc867c workqueue: fix bugs in wq_update_unbound_numa() failure path](https://github.com/ppajda/kernel_g3/commit/0ddc867c192e7fe2201abcbb5b5a61ce33866eed)
* [51ffeb0 workqueue: fix ordered workqueues in NUMA setups](https://github.com/ppajda/kernel_g3/commit/51ffeb059bcc3acb49d1dac4c693d5784b74637c)
* [cd86df2 workqueue: copy workqueue_attrs with all fields](https://github.com/ppajda/kernel_g3/commit/cd86df2d9d784b72305b45eb54eb92265aaa5729)
* [cb1ec72 workqueue: don't perform NUMA-aware allocations on offline nodes in wq_numa_init()](https://github.com/ppajda/kernel_g3/commit/cb1ec72ed9292ee9054e15b4631a06ad9913a590)
* [48dff1f workqueue: Make schedule_work() available again to non GPL modules](https://github.com/ppajda/kernel_g3/commit/48dff1f9e7d7c0ed61af87a82a181d2775a5d479)
* [3bf4b51 workqueue: correct handling of the pool spin_lock](https://github.com/ppajda/kernel_g3/commit/3bf4b51b2a5c7952eca1e41c7d5eaea8efe8cac7)
* [d191caf workqueue: workqueue_congested() shouldn't translate WORK_CPU_UNBOUND into node number](https://github.com/ppajda/kernel_g3/commit/d191caf3b1f65750318f4786581f2e8bf38ee390)
* [0ed6753 kthread: implement probe_kthread_data()](https://github.com/ppajda/kernel_g3/commit/0ed6753d2df1e6e1c71c55e465337af5d47ad924)
* [cbe1387 workqueue: include workqueue info when printing debug dump of a worker task](https://github.com/ppajda/kernel_g3/commit/cbe13878b345db015e837c89c1df85325c800098)
* [08af438 workqueue: use kmem_cache_free() instead of kfree()](https://github.com/ppajda/kernel_g3/commit/08af438702094fbd927df6a63ff9077d3ee545e0)
* [291b8cf workqueue: avoid false negative WARN_ON() in destroy_workqueue()](https://github.com/ppajda/kernel_g3/commit/291b8cf08d2fa5be2a8eefdabd965bc759dda25f)
* [635d4be workqueue: update sysfs interface to reflect NUMA awareness and a kernel param to disable NUMA affinity](https://github.com/ppajda/kernel_g3/commit/635d4be416bacee8a0894530464419d3d985e733)
* [2ea7d3d workqueue: implement NUMA affinity for unbound workqueues](https://github.com/ppajda/kernel_g3/commit/2ea7d3d773851c371108ab2f8f1c197b86560d41)
* [be6b346 workqueue: introduce put_pwq_unlocked()](https://github.com/ppajda/kernel_g3/commit/be6b34632827bd5f0c47611d165b9f739f24d48b)
* [b115048 workqueue: introduce numa_pwq_tbl_install()](https://github.com/ppajda/kernel_g3/commit/b115048a007798e73832c07e7541a8dde68a026d)
* [deae916 workqueue: use NUMA-aware allocation for pool_workqueues](https://github.com/ppajda/kernel_g3/commit/deae9166154460f2bc60b3423b4a7029dd4a1b33)
* [b0833ae3 workqueue: break init_and_link_pwq() into two functions and introduce alloc_unbound_pwq()](https://github.com/ppajda/kernel_g3/commit/b0833ae3d46a8922cb4a363dfad0041d391feaf9)
* [0228392 workqueue: map an unbound workqueues to multiple per-node pool_workqueues](https://github.com/ppajda/kernel_g3/commit/0228392e93afe3aacef4f753b8da61d95e69aa1e)
* [9073595 workqueue: move hot fields of workqueue_struct to the end](https://github.com/ppajda/kernel_g3/commit/90735958521d411a9d667fa9bf14484696fbc2d1)
* [8442de5 workqueue: make workqueue->name[] fixed len](https://github.com/ppajda/kernel_g3/commit/8442de58363b4a78d6e1011de86c60f77bc14c94)
* [b546d2c workqueue: add workqueue->unbound_attrs](https://github.com/ppajda/kernel_g3/commit/b546d2cc9e34f92b960a233958a7ea328687d52c)
* [873fe90 workqueue: determine NUMA node of workers accourding to the allowed cpumask](https://github.com/ppajda/kernel_g3/commit/873fe9084370ae547478de08ef39512bc0fbd05b)
* [82c45c4 workqueue: drop 'H' from kworker names of unbound worker pools](https://github.com/ppajda/kernel_g3/commit/82c45c46b1f2e85413f841e9d6b477daf3115417)
* [d2449de workqueue: add wq_numa_tbl_len and wq_numa_possible_cpumask[]](https://github.com/ppajda/kernel_g3/commit/d2449de9ed3cdcb4beddc341529a675bfc43a9cc)
* [72efe53 workqueue: move pwq_pool_locking outside of get/put_unbound_pool()](https://github.com/ppajda/kernel_g3/commit/72efe537512af5ccfbcbc2cd27adc7023c240942)
* [4240902 workqueue: fix memory leak in apply_workqueue_attrs()](https://github.com/ppajda/kernel_g3/commit/42409022959dbbfe19f4e85d9a4634dcf0a85759)
* [2b8832e workqueue: fix unbound workqueue attrs hashing / comparison](https://github.com/ppajda/kernel_g3/commit/2b8832e6c940c40516d6798a62ab5ecb29f5840b)
* [35c235c workqueue: fix race condition in unbound workqueue free path](https://github.com/ppajda/kernel_g3/commit/35c235c4f54e592c321272cc921dcb3e26b6e108)
* [6ab9841 workqueue: remove pwq_lock which is no longer used](https://github.com/ppajda/kernel_g3/commit/6ab98410e13083e5eae709858aa37bded0452ec8)
* [3be2c3a workqueue: protect wq->saved_max_active with wq->mutex](https://github.com/ppajda/kernel_g3/commit/3be2c3a35d968c316c4a9626670020fd17cfdfb1)
* [13efe5b workqueue: protect wq->pwqs and iteration with wq->mutex](https://github.com/ppajda/kernel_g3/commit/13efe5bd76cb90700428ca363ea0dae25da5087d)
* [7c85085 workqueue: protect wq->nr_drainers and ->flags with wq->mutex](https://github.com/ppajda/kernel_g3/commit/7c85085dd020e15ac274fbbe9e1ce97cacca355b)
* [285e714 workqueue: rename wq->flush_mutex to wq->mutex](https://github.com/ppajda/kernel_g3/commit/285e71468ea46659d537709bb36829dfbee280b6)
* [cfa38f2 workqueue: rename wq_mutex to wq_pool_mutex](https://github.com/ppajda/kernel_g3/commit/cfa38f2ccc5290b15c181f7c11d2e4e162d25873)
* [c9f8d01 workqueue: avoid false negative in assert_manager_or_pool_lock()](https://github.com/ppajda/kernel_g3/commit/c9f8d01d3b54f0c1cddf63bdd4d6ba29664d30a1)
* [16600ff workqueue: use rcu_read_lock_sched() instead for accessing pwq in RCU](https://github.com/ppajda/kernel_g3/commit/16600ff03551d97a0f7524889389fac795c760f2)
* [15f0743 workqueue: kick a worker in pwq_adjust_max_active()](https://github.com/ppajda/kernel_g3/commit/15f07436ba1f45bd858ece4beb202a19cb84c611)
* [a3fd9e8 workqueue: simplify current_is_workqueue_rescuer()](https://github.com/ppajda/kernel_g3/commit/a3fd9e884354bc4bdd41ccd3e9a15ebab02b47d4)
* [27f505c workqueue: add missing POOL_FREEZING](https://github.com/ppajda/kernel_g3/commit/27f505c2c882d8f6978bfd0abe84e6e22535c697)
* [d7fcab7 workqueue: restore CPU affinity of unbound workers on CPU_ONLINE](https://github.com/ppajda/kernel_g3/commit/d7fcab7cc2fb20b635379d515117fbdef9f743cb)
* [a6f8028 workqueue: directly restore CPU affinity of workers from CPU_ONLINE](https://github.com/ppajda/kernel_g3/commit/a6f8028f6c8da1ade89590bc176d7eb55d8e2c7b)
* [e3fe434 workqueue: relocate rebind_workers()](https://github.com/ppajda/kernel_g3/commit/e3fe4341086d76315d9c04357a2d069d60f05267)

***

12-21-2017
====================

* [52d51cc kgsl: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/52d51ccc0f7deb60d08017e4a72fbfc849dc5a5c)
* [e9e1d5e ion: remove deprecated idr_](https://github.com/ppajda/kernel_g3/commit/e9e1d5e1c84ddc2a9ffe63bc86994b6bf534b334)
* [f8ccb29 gpio: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/f8ccb29ce2e7b2b1a5b04190ed0472bd61275a41)
* [950322f events: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/950322fd1c84bf7dc00c9e780678684975b462ea)
* [18cc979 block: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/18cc979be12226ebe28ca9a6ef15c74866391c57)
* [b4370a4 scsi: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/b4370a48f4bdb74ee1db1a923be76d043fa39865)
* [b9a23d3 [SCSI] st: remove st_mutex](https://github.com/ppajda/kernel_g3/commit/b9a23d3d6bbcb21b15985d7bb34d444bf11b54e8)
* [fe857f5 [SCSI] st: clean up device file creation and removal](https://github.com/ppajda/kernel_g3/commit/fe857f5df923a3becd6d262307057609b3163922)
* [bfda29b [SCSI] st: get rid of scsi_tapes array](https://github.com/ppajda/kernel_g3/commit/bfda29b9d932d17629f053fc78560157889ab83b)
* [9eb4e8d [SCSI] st: clean up dev cleanup in st_probe](https://github.com/ppajda/kernel_g3/commit/9eb4e8de8d2c0ebb84fe07bc9bb0d977aabf17fa)
* [e991e2b [SCSI] st: Use static class attributes](https://github.com/ppajda/kernel_g3/commit/e991e2b821747c1b11b8d90f96714a8377b911bc)
* [e347043 block/loop: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/e347043db4f3f4ddd49c15884f99c18b5373d945)
* [380efba posix-timers: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/380efbad95329ee9736656d2d792c818477b889c)
* [820ce5a idr: document exit conditions on idr_for_each_entry better](https://github.com/ppajda/kernel_g3/commit/820ce5aec3962d5e666e969686ecf8a45bc96ac6)
* [d5c853d idr: make idr_layer larger](https://github.com/ppajda/kernel_g3/commit/d5c853df2af61db624be530d97d25765b2a9a061)
* [40f29ea idr: fix overflow bug during maximum ID calculation at maximum height](https://github.com/ppajda/kernel_g3/commit/40f29ead4a4e02100ece6a27840c6607be4832af)
* [451f88a idr: introduce idr_alloc_cyclic()](https://github.com/ppajda/kernel_g3/commit/451f88a4dc7a90668a1baf9ff4822d3488453a34)
* [f3a1f08 idr: idr_alloc() shouldn't trigger lowmem warning when preloaded](https://github.com/ppajda/kernel_g3/commit/f3a1f08cd409f3c92dbcaff0553f42180e2b1ba7)
* [ff69791e idr: deprecate idr_pre_get() and idr_get_new[_above]()](https://github.com/ppajda/kernel_g3/commit/ff69791e33707621159752bd9579f56f2d734b01)
* [dae4b42 idr: fix new kernel-doc warnings](https://github.com/ppajda/kernel_g3/commit/dae4b42ffb0b8cab846a5ea2a59b35085ce7aa74)
* [e27210f idr: remove WARN_ON_ONCE() on negative IDs](https://github.com/ppajda/kernel_g3/commit/e27210f1c3ec9443a451db3df2c85fcef90e5905)
* [23dcfaf idr: explain WARN_ON_ONCE() on negative IDs out-of-range ID](https://github.com/ppajda/kernel_g3/commit/23dcfafe73b54652d1f298448b2f8bd9bb217ee3)
* [9c3576b idr: implement lookup hint](https://github.com/ppajda/kernel_g3/commit/9c3576bf55132a3f0141eb75ebed59b6ed1aba95)
* [6a6c589 idr: add idr_layer->prefix](https://github.com/ppajda/kernel_g3/commit/6a6c58909118b9d10743a6c0e94ae8d629d55faf)
* [914be51 idr: remove length restriction from idr_layer->bitmap](https://github.com/ppajda/kernel_g3/commit/914be51013d96c86607873a4e04a9b9e933d0329)
* [d42e47a idr: remove MAX_IDR_MASK and move left MAX_IDR_* into idr.c](https://github.com/ppajda/kernel_g3/commit/d42e47a38517e6072908889ddf738685feab19da)
* [60df39e Remove deprecated idr_remove_all and fix derps](https://github.com/ppajda/kernel_g3/commit/60df39eff04aaa91360dcaaf37394243dc8cdae8)
* [d446e5a idr: rename MAX_LEVEL to MAX_IDR_LEVEL](https://github.com/ppajda/kernel_g3/commit/d446e5abee41fcf677f8748d1832c1d83fdea9df)
* [302b8f1 idr: fix top layer handling](https://github.com/ppajda/kernel_g3/commit/302b8f139dfbece91c6c2b95c8320d15c144d13b)
* [f61903b idr: implement idr_preload[_end]() and idr_alloc()](https://github.com/ppajda/kernel_g3/commit/f61903bd5d1d399262a8d087003455ac7ba27b08)
* [0e617e8 idr: refactor idr_get_new_above()](https://github.com/ppajda/kernel_g3/commit/0e617e8efbca99b47a45b16d1d6ab40ddc4c6c96)
* [63a4f2f idr: remove _idr_rc_to_errno() hack](https://github.com/ppajda/kernel_g3/commit/63a4f2fff84f5c480fee6ff3d3aca6d11b971ae5)
* [8e0ae37 idr: relocate idr_for_each_entry() and reorganize id[r|a]_get_new()](https://github.com/ppajda/kernel_g3/commit/8e0ae376a0386268af4ca13d9b0d3f5db354163a)
* [1c00508 idr: deprecate idr_remove_all()](https://github.com/ppajda/kernel_g3/commit/1c00508587dc7752489f43b2b9339d90c43cfeb0)
* [42142ff idr: make idr_destroy() imply idr_remove_all()](https://github.com/ppajda/kernel_g3/commit/42142ff1245c0eff576cf84183d539385b431688)
* [35e0f94 locking: Various static lock initializer fixes](https://github.com/ppajda/kernel_g3/commit/35e0f9448504b3f169560ee91b0f2aae357684d6)
* [94296c9 sched: replace PF_THREAD_BOUND with PF_NO_SETAFFINITY](https://github.com/ppajda/kernel_g3/commit/94296c9d559e0173388d90fa63b540c44eb85ce2)
* [bf685a8 Pull workqueue fix from Tejun Heo](https://github.com/ppajda/kernel_g3/commit/bf685a82e0610fa63fe622b3954e11263e4601f4)
* [0a71da3 workqueue: rename workqueue_lock to wq_mayday_lock](https://github.com/ppajda/kernel_g3/commit/0a71da3e9bc5229f00a26c36352680c9c6fc88a3)
* [79532ec workqueue: separate out pool_workqueue locking into pwq_lock](https://github.com/ppajda/kernel_g3/commit/79532ecfff43bab0183833574da68821fa295d60)
* [95dea85 workqueue: separate out pool and workqueue locking into wq_mutex](https://github.com/ppajda/kernel_g3/commit/95dea85118b47a90da3e7aa9c277a7f63d941aee)
* [9b75d63 workqueue: relocate global variable defs and function decls in workqueue.c](https://github.com/ppajda/kernel_g3/commit/9b75d63d14197dded40a2b4b215f91a213051c8d)
* [cc7766b workqueue: better define locking rules around worker creation / destruction](https://github.com/ppajda/kernel_g3/commit/cc7766b77de857691661a4c6cdb1b9874e7ab9b5)
* [a0aa136 workqueue: factor out initial worker creation into create_and_start_worker()](https://github.com/ppajda/kernel_g3/commit/a0aa136528eb556a5cfc5d7aae8d22318c34bcc1)
* [0a15bd7 workqueue: rename worker_pool->assoc_mutex to ->manager_mutex](https://github.com/ppajda/kernel_g3/commit/0a15bd75c70e0ccc8c3c387455a9985e78e906df)
* [03f44f0 workqueue: inline trivial wrappers](https://github.com/ppajda/kernel_g3/commit/03f44f0f931b7da3c2512355addf112b8e73ad80)
* [473f231 workqueue: rename @id to @pi in for_each_each_pool()](https://github.com/ppajda/kernel_g3/commit/473f231f36b58687875f6814fd80bec1b14f1716)
* [ffb2b69 workqueue: update comments and a warning message](https://github.com/ppajda/kernel_g3/commit/ffb2b69e7b2c838a526e7b59f5d8ab72393a8099)
* [0f2214a workqueue: fix max_active handling in init_and_link_pwq()](https://github.com/ppajda/kernel_g3/commit/0f2214a41eadffd9db1727c02d51e8579e13cfaa)
* [4f6f86b workqueue: implement and use pwq_adjust_max_active()](https://github.com/ppajda/kernel_g3/commit/4f6f86b100090091deaf652a9d94a3721dd63a31)
* [87e64e6 workqueue: relocate pwq_set_max_active()](https://github.com/ppajda/kernel_g3/commit/87e64e6be63d55e663084457f9a96cb3af1c69a4)
* [19420d1 workqueue: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/19420d10eaebeac2130b9e633eadf23958fdd23b)
* [7a5d28f workqueue: implement current_is_workqueue_rescuer()](https://github.com/ppajda/kernel_g3/commit/7a5d28f131ff63b249eba837c3994f3762c51326)
* [e4b4ba3 workqueue: implement sysfs interface for workqueues](https://github.com/ppajda/kernel_g3/commit/e4b4ba3ef6e1e1d5b8c621701c8bcdaa3d4aff06)
* [8dd9323 driver/base: implement subsys_virtual_register()](https://github.com/ppajda/kernel_g3/commit/8dd9323b17ae069496bcdab2998cf71151c768e6)
* [527a1c9 cpumask: implement cpumask_parse()](https://github.com/ppajda/kernel_g3/commit/527a1c9a919343d9d3ab9a6cd56b255f8f9b78a6)
* [092874b workqueue: reject adjusting max_active or applying attrs to ordered workqueues](https://github.com/ppajda/kernel_g3/commit/092874ba2a631d8f6db30179cfde64b7a627d1bd)
* [29b98d0 workqueue: make it clear that WQ_DRAINING is an internal flag](https://github.com/ppajda/kernel_g3/commit/29b98d06994e13720804133b77cf79c5a0073263)
* [88097ca workqueue: implement apply_workqueue_attrs()](https://github.com/ppajda/kernel_g3/commit/88097caabbaeed150918ac9b31f8d8e6bb3be29a)
* [f36ddb5 workqueue: perform non-reentrancy test when queueing to unbound workqueues too](https://github.com/ppajda/kernel_g3/commit/f36ddb585f0f61839200105907a9a58ee5e1e517)
* [22ff0df workqueue: prepare flush_workqueue() for dynamic creation and destrucion of unbound pool_workqueues](https://github.com/ppajda/kernel_g3/commit/22ff0dfa952feadf119ea4b6f4a104eb78ee7a95)
* [b988a3a workqueue: implement get/put_pwq()](https://github.com/ppajda/kernel_g3/commit/b988a3a6038f578ecee8c3475e5e8227726744c7)
* [05d3d3a workqueue: restructure __alloc_workqueue_key()](https://github.com/ppajda/kernel_g3/commit/05d3d3a7f10637c27b7b5fe6e67b4b252633c399)
* [2efff0e workqueue: drop WQ_RESCUER and test workqueue->rescuer for NULL instead](https://github.com/ppajda/kernel_g3/commit/2efff0ea12d898bfaea28c2ccae68134d7357639)
* [2268289 workqueue: add pool ID to the names of unbound kworkers](https://github.com/ppajda/kernel_g3/commit/22682898f5207886c6bef247db00b5f595d1254d)
* [aa35084 workqueue: drop "std" from cpu_std_worker_pools and for_each_std_worker_pool()](https://github.com/ppajda/kernel_g3/commit/aa3508489a36f1284a941dc87fafb2fc80155c5c)
* [68571ce workqueue: remove unbound_std_worker_pools[] and related helpers](https://github.com/ppajda/kernel_g3/commit/68571ceb51c940449cd231432be561ba3b84f688)
* [143be00 workqueue: implement attribute-based unbound worker_pool management](https://github.com/ppajda/kernel_g3/commit/143be00904a1c2d13544694ec0cda7a7a5a2ea97)
* [89458f8 workqueue: introduce workqueue_attrs](https://github.com/ppajda/kernel_g3/commit/89458f8d8ceb621861dbd6b7fbfe9fc50d998ec9)
* [ef0bc74 workqueue: separate out init_worker_pool() from init_workqueues()](https://github.com/ppajda/kernel_g3/commit/ef0bc7474c3ffa9551d21175cc5e5546c462fcf6)
* [fa5c8fa workqueue: replace POOL_MANAGING_WORKERS flag with worker_pool->manager_arb](https://github.com/ppajda/kernel_g3/commit/fa5c8fa98ad26db6f7f147b394cef62c9d13f792)
* [c4756af workqueue: update synchronization rules on worker_pool_idr](https://github.com/ppajda/kernel_g3/commit/c4756af350f3f9ca283a86857681ed72a28200db)
* [a7e404c workqueue: update synchronization rules on workqueue->pwqs](https://github.com/ppajda/kernel_g3/commit/a7e404c25d02b2b26e84b5684daf71703eba3328)
* [386a9f9 workqueue: replace get_pwq() with explicit per_cpu_ptr() accesses and first_pwq()](https://github.com/ppajda/kernel_g3/commit/386a9f9d98f45a0b814935fed857fffc27a9613f)
* [bfc17f3 workqueue: remove workqueue_struct->pool_wq.single](https://github.com/ppajda/kernel_g3/commit/bfc17f3a00a6c113d44638fe2aabbd981a9eaac5)
* [c4a7a1a workqueue: consistently use int for @cpu variables](https://github.com/ppajda/kernel_g3/commit/c4a7a1a289b7fd5807c9764134cf2ac3085a455d)
* [a9b44e8 workqueue: add wokrqueue_struct->maydays list to replace mayday cpu iterators](https://github.com/ppajda/kernel_g3/commit/a9b44e8279a216fbbc2d1b8610c35371545ac023)
* [a369f98 workqueue: restructure pool / pool_workqueue iterations in freeze/thaw functions](https://github.com/ppajda/kernel_g3/commit/a369f98a09fc2c86d86a580383fadeec74523a30)
* [f6ad795 workqueue: introduce for_each_pool()](https://github.com/ppajda/kernel_g3/commit/f6ad7953c807b263e482edec562f90993beac23d)
* [820c0ca7 workqueue: replace for_each_pwq_cpu() with for_each_pwq()](https://github.com/ppajda/kernel_g3/commit/820c0ca7a8dabe8795ce497e1605482aef69d9dc)
* [1f2b3c1 workqueue: add workqueue_struct->pwqs list](https://github.com/ppajda/kernel_g3/commit/1f2b3c13900e686cd55d673cd865ea7b58d5b105)
* [e59d640 workqueue: introduce kmem_cache for pool_workqueues](https://github.com/ppajda/kernel_g3/commit/e59d64057c3f63bbdf406069b2f69ffc35dc7793)
* [2d338bf workqueue: make workqueue_lock irq-safe](https://github.com/ppajda/kernel_g3/commit/2d338bfae4ba8325ff0aa3e44fdcbd140beaa9a4)
* [eadc291 workqueue: make sanity checks less punshing using WARN_ON[_ONCE]()s](https://github.com/ppajda/kernel_g3/commit/eadc29122f9521968d3438c9b0b36c58b2236bab)
* [89e3ca8 workqueue: fix possible pool stall bug in wq_unbind_fn()](https://github.com/ppajda/kernel_g3/commit/89e3ca8b2774c8d757ce12637059e3a50d7713c7)
* [71de30a0 workqueue: better define synchronization rule around rescuer->pool updates](https://github.com/ppajda/kernel_g3/commit/71de30a07b39c85c332b322f825534dffede68e3)
* [14e4a11 workqueue: change argument of worker_maybe_bind_and_lock() to @pool](https://github.com/ppajda/kernel_g3/commit/14e4a11626c499b70780d0ddd5cc0889b71bcfb6)

***

12-20-2017
====================

* [3ea36d0 workqueue: un-GPL function delayed_work_timer_fn()](https://github.com/ppajda/kernel_g3/commit/3ea36d065f9f4395a87d8b501d2cf6774da3a5f4)
* [8c106af workqueue: implement current_is_async()](https://github.com/ppajda/kernel_g3/commit/8c106af70faf6f13429cc7a230434818d77878ec)
* [ea9fd1f workqueue: rename cpu_workqueue to pool_workqueue](https://github.com/ppajda/kernel_g3/commit/ea9fd1f3725606a4bb9f6f9ace00841c17b565bb)
* [783c2b6 workqueue: reimplement is_chained_work() using current_wq_worker()](https://github.com/ppajda/kernel_g3/commit/783c2b64630a273236a42374b2eb6f969497a5cf)
* [c30d21d workqueue: fix is_chained_work() regression](https://github.com/ppajda/kernel_g3/commit/c30d21dc457bba0f01327e0346e23878f33c40ce)
* [3712e23 workqueue: pick cwq instead of pool in __queue_work()](https://github.com/ppajda/kernel_g3/commit/3712e2378b3901e85f8fccb765459233f7a7ff4d)
* [91694d3 workqueue: make get_work_pool_id() cheaper](https://github.com/ppajda/kernel_g3/commit/91694d3c96bcf1341d0765ee674a0a6a98fa8e71)
* [3dc5b08 workqueue: move nr_running into worker_pool](https://github.com/ppajda/kernel_g3/commit/3dc5b084f1ed985cb240aae0fbb2192a96c494ff)
* [826fa65 workqueue: cosmetic update in try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/826fa65ca3179d6c5d83c60dac7418210b7e8767)
* [82be383 workqueue: simplify is-work-item-queued-here test](https://github.com/ppajda/kernel_g3/commit/82be3830ffb6b61a88a51fca8d618e528bfe74a9)
* [a6fd817 workqueue: make work->data point to pool after try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/a6fd8171695cd6ab8525818ef0b84a5cb2817174)
* [caa3268 workqueue: add delayed_work->wq to simplify reentrancy handling](https://github.com/ppajda/kernel_g3/commit/caa32684f4fc1964d12e813ebc6c9fdb767287d0)
* [5e298f1 workqueue: make work_busy() test WORK_STRUCT_PENDING first](https://github.com/ppajda/kernel_g3/commit/5e298f194d7c20ba25898759524e6c9ca8c81d61)
* [8ad97c5 workqueue: replace WORK_CPU_NONE/LAST with WORK_CPU_END](https://github.com/ppajda/kernel_g3/commit/8ad97c594963eead5da1f4db777a76d65696372b)
* [db9eb4a workqueue: post global_cwq removal cleanups](https://github.com/ppajda/kernel_g3/commit/db9eb4a54e5493ee582244755bfc5b28f928039a)
* [baae911b1 workqueue: rename nr_running variables](https://github.com/ppajda/kernel_g3/commit/baae911b1640c8f1cc8c9dcce063bc8b62fed86d)
* [38efa63 workqueue: remove global_cwq](https://github.com/ppajda/kernel_g3/commit/38efa63aff6ae4b7364d8de7783baa7c5aab4dfe)
* [e5de008f workqueue: remove worker_pool->gcwq](https://github.com/ppajda/kernel_g3/commit/e5de008f270deae605124e47f001294b36e114af)
* [5aa2a38 workqueue: replace for_each_worker_pool() with for_each_std_worker_pool()](https://github.com/ppajda/kernel_g3/commit/5aa2a380f91da1cf70c0015c543a3f3311a6340d)
* [82c10b5 workqueue: make freezing/thawing per-pool](https://github.com/ppajda/kernel_g3/commit/82c10b53fcd6737a87f1e1178f3c6551a1966d41)
* [146766a workqueue: make hotplug processing per-pool](https://github.com/ppajda/kernel_g3/commit/146766a91feefe8e800f4142fdcb64da9843e701)
* [8c8db74 workqueue: move global_cwq->lock to worker_pool](https://github.com/ppajda/kernel_g3/commit/8c8db74b2c4274590058b49b7e727ce773e9d504)
* [4d2c579 workqueue: move global_cwq->cpu to worker_pool](https://github.com/ppajda/kernel_g3/commit/4d2c5799ba7b4756d6ef1596d320937fea723ec6)
* [0731b86 workqueue: move busy_hash from global_cwq to worker_pool](https://github.com/ppajda/kernel_g3/commit/0731b8608d90f65c33edff1356c9f7786e148ada)
* [84577c1 workqueue: record pool ID instead of CPU in work->data when off-queue](https://github.com/ppajda/kernel_g3/commit/84577c1c0dddb3ab05772fadd220842ad4936dac)
* [4146658 workqueue: add worker_pool->id](https://github.com/ppajda/kernel_g3/commit/4146658366653f2e4a8d6d2d1b3ebf4294827f71)
* [b5aaa98e workqueue: make GCWQ_FREEZING a pool flag](https://github.com/ppajda/kernel_g3/commit/b5aaa98ec57f24efce2193a07bee0e0489e9e856)
* [27d7894 workqueue: make GCWQ_DISASSOCIATED a pool flag](https://github.com/ppajda/kernel_g3/commit/27d789435dafc8cef5e5f60cbcc3fc1602e10a5a)
* [4a12e9b workqueue: use std_ prefix for the standard per-cpu pools](https://github.com/ppajda/kernel_g3/commit/4a12e9bf54e78743b19bc076e73041e047bf2ba6)
* [1296d96 workqueue: move struct worker definition to workqueue_internal.h](https://github.com/ppajda/kernel_g3/commit/1296d96c2280d4f79ff9de90ee18b365f51d5fe7)
* [b10b273 workqueue: rename kernel/workqueue_sched.h to kernel/workqueue_internal.h](https://github.com/ppajda/kernel_g3/commit/b10b27359c614eeb2e16e179c6d3f960d8879e2b)
* [d46278a workqueue: set PF_WQ_WORKER on rescuers](https://github.com/ppajda/kernel_g3/commit/d46278a955d45c6b9008f8e69eaf187b45b9fd7a)
* [ed862ff workqueue: fix find_worker_executing_work() brekage from hashtable conversion](https://github.com/ppajda/kernel_g3/commit/ed862ff6d364e7720f03f80e46d4a252a3284b8c)
* [c001268 workqueue: consider work function when searching for busy work items](https://github.com/ppajda/kernel_g3/commit/c001268f55117fb1bc19022a3de3caa5567fd7b4)
* [520db4d workqueue: use new hashtable implementation](https://github.com/ppajda/kernel_g3/commit/520db4d718fc85795ac8388a72f6bd38c74af7f3)
* [75c7eb9 workqueue: convert BUG_ON()s in __queue_delayed_work() to WARN_ON_ONCE()s](https://github.com/ppajda/kernel_g3/commit/75c7eb9014ef6e06f773f2b9b77078d167d7165d)
* [591ea99 workqueue: add WARN_ON_ONCE() on CPU number to wq_worker_waking_up()](https://github.com/ppajda/kernel_g3/commit/591ea9917c0c8d734cd554b3b81e808013f792bf)
* [f80bdb8 workqueue: trivial fix for return statement in work_busy()](https://github.com/ppajda/kernel_g3/commit/f80bdb86f7c14f6c913c30407304ee8a5805380e)
* [06441cd workqueue: mod_delayed_work_on() shouldn't queue timer on 0 delay](https://github.com/ppajda/kernel_g3/commit/06441cddedb4b7952314c3e853bb727399d779ff)
* [348e70e workqueue: cancel_delayed_work() should return %false if work item is idle](https://github.com/ppajda/kernel_g3/commit/348e70eb2fb09c872d1ec92b92ce5ed34df7fdbf)
* [045c4c6 workqueue: remove spurious WARN_ON_ONCE(in_irq()) from try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/045c4c637b20667b11136d20b034b1e9b90f4c4e)
* [b3c72db workqueue: use cwq_set_max_active() helper for workqueue_set_max_active()](https://github.com/ppajda/kernel_g3/commit/b3c72db80394d0b9e2bcc0aa248d62eba3bc028a)
* [41d81dc workqueue: introduce cwq_set_max_active() helper for thaw_workqueues()](https://github.com/ppajda/kernel_g3/commit/41d81dcfa1fa62c17dbc1cf0568293b3bf4bec75)
* [1cff548 workqueue: remove @delayed from cwq_dec_nr_in_flight()](https://github.com/ppajda/kernel_g3/commit/1cff548f4b4544f14f8ac3361f032b4c42ef4923)
* [fa7f86b workqueue: fix possible stall on try_to_grab_pending() of a delayed work item](https://github.com/ppajda/kernel_g3/commit/fa7f86bc983093d433227442646ea37abdac46e6)
* [9f93e41 workqueue: use hotcpu_notifier() for workqueue_cpu_down_callback()](https://github.com/ppajda/kernel_g3/commit/9f93e41676005e706c6fb53eb307fa3749b394f3)
* [bef4e27 workqueue: use __cpuinit instead of __devinit for cpu callbacks](https://github.com/ppajda/kernel_g3/commit/bef4e276be98386ce04361bf848f1ab35d9c862c)
* [e84fd7d workqueue: rename manager_mutex to assoc_mutex](https://github.com/ppajda/kernel_g3/commit/e84fd7dfd082c16467eb9f60c0de814127483395)
* [7c58ae0 workqueue: WORKER_REBIND is no longer necessary for idle rebinding](https://github.com/ppajda/kernel_g3/commit/7c58ae0075cc0cb86f577d7ee141b91b1a09ed7c)
* [b2bd40f workqueue: WORKER_REBIND is no longer necessary for busy rebinding](https://github.com/ppajda/kernel_g3/commit/b2bd40f38c99fbe02e49b8cee595b7e145895698)
* [09d52b0 workqueue: reimplement idle worker rebinding](https://github.com/ppajda/kernel_g3/commit/09d52b0a5f160933d5b2d2734d3746f40a7acd07)
* [f819056 Merge branch 'for-3.6-fixes' of git://git.kernel.org/pub/scm/linux/kernel/git/tj/wq into for-3.7](https://github.com/ppajda/kernel_g3/commit/f819056024a31f4f581d3fbceabb640969d87b90)
* [c42cab9 workqueue: always clear WORKER_REBIND in busy_worker_rebind_fn()](https://github.com/ppajda/kernel_g3/commit/c42cab9d6a427b838e79f562aa3d4d9eee514f26)
* [ad077d0 workqueue: fix possible idle worker depletion across CPU hotplug](https://github.com/ppajda/kernel_g3/commit/ad077d038fae9071c0f502fc6da58b0f2cc17015)
* [b696ea4 workqueue: restore POOL_MANAGING_WORKERS](https://github.com/ppajda/kernel_g3/commit/b696ea45c53329a3b8162f7e0c1fd13b47d12dc3)
* [1d01a57 workqueue: fix possible deadlock in idle worker rebinding](https://github.com/ppajda/kernel_g3/commit/1d01a57c0491fb3313eab4b755aad5883fc75116)
* [0d928ab workqueue: move WORKER_REBIND clearing in rebind_workers() to the end of the function](https://github.com/ppajda/kernel_g3/commit/0d928ab0b41f3405ebbc7bf9f806178370b54b79)

***

12-19-2017
====================

* [b365f61 rename deprecated __cancel_delayed_work to cancel_delayed_work](https://github.com/ppajda/kernel_g3/commit/b365f613ef45b6e3952b8ac0b3893a113dab5f6f)
* [c521e6c workqueue: introduce WORK_OFFQ_CPU_NONE](https://github.com/ppajda/kernel_g3/commit/c521e6c47e3408d4f3b287a4cdd02e09472d7044)
* [acde4f1 workqueue: unexport work_cpu()](https://github.com/ppajda/kernel_g3/commit/acde4f1c4a0f020ce3c08ed270acbc8965a16bec)
* [f4d76a7 workqueue: deprecate __cancel_delayed_work()](https://github.com/ppajda/kernel_g3/commit/f4d76a72e588e3354c0c4d1d71e542fe74b4b09b)
* [aa7f28c workqueue: reimplement cancel_delayed_work() using try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/aa7f28c2d3307933eebae9f2553ebbeb358331d0)
* [859fcbb workqueue: use irqsafe timer for delayed_work](https://github.com/ppajda/kernel_g3/commit/859fcbb12e3ae4b3282f06e2a5d576e8e11b30b1)
* [570894d timer: Implement TIMER_IRQSAFE](https://github.com/ppajda/kernel_g3/commit/570894d0cd2d706193b652143348d9cd51c8893d)
* [50bf96c timer: Clean up timer initializers](https://github.com/ppajda/kernel_g3/commit/50bf96c88ec48b04f249a194149261c49fc88b6d)
* [eb24f29 timer: Relocate declarations of init_timer_on_stack_key()](https://github.com/ppajda/kernel_g3/commit/eb24f292026c5c96705163b27fe99196503ce2f1)
* [5ce71ce timer: Generalize timer->base flags handling](https://github.com/ppajda/kernel_g3/commit/5ce71ce2c01fd83ae43eb7c48ac9ac2928718e60)
* [0b77895 timers: Improve get_next_timer_interrupt()](https://github.com/ppajda/kernel_g3/commit/0b77895992db230049c50425d67c386009276541)
* [1454c40 timers: Add accounting of non deferrable timers](https://github.com/ppajda/kernel_g3/commit/1454c40d5061514f94cec541f187f09db2c48023)
* [a5e4196 timers: Consolidate base->next_timer update](https://github.com/ppajda/kernel_g3/commit/a5e419675f2d474ecac49615dffb2b9e346b11f7)
* [ec64c88 timers: Create detach_if_pending() and use it](https://github.com/ppajda/kernel_g3/commit/ec64c88c78b5ccc360732939c86cd8756eb9240e)
* [e390ab5 lockdep: fix oops in processing workqueue](https://github.com/ppajda/kernel_g3/commit/e390ab545af029b79999bc733345598c8af21a32)
* [b2eb2b6 workqueue: clean up delayed_work initializers and add missing one](https://github.com/ppajda/kernel_g3/commit/b2eb2b62d2ac4a0d1b9159f01bcabe25b58be0e7)
* [5ed4473 workqueue: make deferrable delayed_work initializer names consistent](https://github.com/ppajda/kernel_g3/commit/5ed44735cfc5d83f20a692d144c5a33be2d60a06)
* [1521342 workqueue: deprecate system_nrt[_freezable]_wq](https://github.com/ppajda/kernel_g3/commit/1521342b03cd6f7459cc92aecfa38de87d5d259d)
* [2f9b2ee workqueue: deprecate flush[_delayed]_work_sync()](https://github.com/ppajda/kernel_g3/commit/2f9b2ee55aeeb0a09558f0340c0f303e0f14ee30)
* [3383324 sched/core: Fix a race between try_to_wake_up() and a woken up task](https://github.com/ppajda/kernel_g3/commit/33833243edc778302926e24fdc42d8c9fac4cb48)
* [bf01498 Revert "msm8974pro.dtsi: change initial power level"](https://github.com/ppajda/kernel_g3/commit/bf0149803b82291fd9e7ca030d612548b15833d9)

***

12-17-2017
====================

* [b19af4c PM / Sleep: Require CAP_BLOCK_SUSPEND to use wake_lock/wake_unlock](https://github.com/ppajda/kernel_g3/commit/b19af4cdaa9946823ba06e17f4c0547b7dac5007)
* [3d0626b SELinux: include definition of new capabilities](https://github.com/ppajda/kernel_g3/commit/3d0626b7af935693b51fbafb6d26e5915ed5abd7)
* [0fcaa8c PM: Rename CAP_EPOLLWAKEUP to CAP_BLOCK_SUSPEND](https://github.com/ppajda/kernel_g3/commit/0fcaa8c28b28e3f4730885bce1330a5dd4b2b3f6)
* [37c077d epoll: Fix user space breakage related to EPOLLWAKEUP](https://github.com/ppajda/kernel_g3/commit/37c077d02b46744033db48b1168aedbce6e845cf)
* [7323231 epoll: Add a flag, EPOLLWAKEUP, to prevent suspend while epoll events are ready](https://github.com/ppajda/kernel_g3/commit/7323231b551d5932ea15a38a753b3dc775ffbdd3)

***

12-16-2017
====================


***

12-15-2017
====================

* [49eea1f ANDROID: binder: fix compilation warnings.](https://github.com/ppajda/kernel_g3/commit/49eea1f78b51ac3e8218504dc717a56b2a5d8c8f)
* [967637c UPSTREAM: drivers: android: correct the size of struct binder_uintptr_t for BC_DEAD_BINDER_DONE](https://github.com/ppajda/kernel_g3/commit/967637c3cb1be568809c03169aa23d620e86fee3)
* [b59ab5e staging: binder: Improve Kconfig entry for ANDROID_BINDER_IPC_32BIT](https://github.com/ppajda/kernel_g3/commit/b59ab5e83a192c3802ad6b60cf48706027c40816)
* [8471234 BACKPORT: ARM: 8091/2: add get_user() support for 8 byte types](https://github.com/ppajda/kernel_g3/commit/8471234f4203b16f7d907c16d6d4d771c02e8a06)

***

12-14-2017
====================

* [711f9b8 dts: msm8974.dtsi: tune thermal](https://github.com/ppajda/kernel_g3/commit/711f9b88bdd889b56de4d535a93e36d51de2f4da)

***

12-13-2017
====================

* [3fb3048 msm: kgsl: Remove io_fraction as it is no longer used](https://github.com/ppajda/kernel_g3/commit/3fb30482c14e3389e89b80a901e5b27be89137e8)
* [6133243 msm8974pro.dtsi: change initial power level](https://github.com/ppajda/kernel_g3/commit/61332436353e6cef34729a73c1418370d71ce7d7)
* [1859328 msm8974pro: regulator: adjust GFX regulator parameters](https://github.com/ppajda/kernel_g3/commit/1859328e7e861db5ba6540057837574edf12fb4a)
* [0a1d984 ALSA: seq: Fix use-after-free at creating a port](https://github.com/ppajda/kernel_g3/commit/0a1d984e525870bb75e80d3d9edb955d7b4fa352)
* [669f969 nl80211: check for the required netlink attributes presence](https://github.com/ppajda/kernel_g3/commit/669f96987d5098d6df54dd2797eecbb596df03da)
* [d5857280 SoC: msm: audio-effects: return directly to avoid integer overflow](https://github.com/ppajda/kernel_g3/commit/d585728036e4a51531836021370c173c5af758e6)
* [5273ef7 crypto: msm: Fix several race condition issues in crypto drivers](https://github.com/ppajda/kernel_g3/commit/5273ef7b655a4c983315dc53a65b31b3da6b3d5e)
* [d3c5382 net: usb: Make sure list_head operate atomically](https://github.com/ppajda/kernel_g3/commit/d3c5382db78e0fc4e3f0ff36bb280bf6446d4f8f)
* [f1fefe4 msm: camera: fix off-by-one overflow in msm_isp_get_bufq](https://github.com/ppajda/kernel_g3/commit/f1fefe4111e5ae9a4226a58ce403bd25afd25975)
* [24c1768 ASoC: msm: qdsp6v2: extend validation of virtual address](https://github.com/ppajda/kernel_g3/commit/24c176873161bdddbbebea87df678711c8b88d29)
* [0663704 mm: Fix incorrect type conversion for size during dma allocation](https://github.com/ppajda/kernel_g3/commit/066370409a4359d0b69ca9a8ae9ba678ed0c236d)
* [b0d6f83 msm: mdss: Buffer overflow while processing gamut table data](https://github.com/ppajda/kernel_g3/commit/b0d6f83bad8d8fb923a42f07551fb546491b5b61)
* [7b7dc7a msm: sps: Fix race condition in SPS debugfs APIs](https://github.com/ppajda/kernel_g3/commit/7b7dc7a3bd1cfd0ecd222638e298a16a45c71060)
* [83a2bab ASoC: msm: remove unused msm-compr-q6-v2](https://github.com/ppajda/kernel_g3/commit/83a2bab61c93323627b5e43cb8eddd854162ba30)
* [08cca0f IKHSS7-18791 msm:fix the list usage in msm_bus_dbg](https://github.com/ppajda/kernel_g3/commit/08cca0f199534b3fbd8a7d6e090ed9d4e72aece5)
* [5e18434 diag: dci: Add protection while querying event status](https://github.com/ppajda/kernel_g3/commit/5e18434e70b2db0ec27b6b3865587cb33f764fec)
* [9d17439 wcnss: fix the potential memory leak and heap overflow](https://github.com/ppajda/kernel_g3/commit/9d1743964dee4d6677d164317957754b48ce6bfd)
* [1b7bc1f msm: camera: isp: fix for out of bound access array](https://github.com/ppajda/kernel_g3/commit/1b7bc1f538ad65c2518d28c1b35c1f51ee952c77)
* [18722bc msm: camera: Allow driver file to be opend only once.](https://github.com/ppajda/kernel_g3/commit/18722bc2d48c97e5ceb0ffcba6f8aa2d0295124f)
* [60abc8c ipx: call ipxitf_put() in ioctl error path](https://github.com/ppajda/kernel_g3/commit/60abc8c72d6bbc813fc28964cc4d4a4f18974d19)
* [0085fca ASoC: msm: acquire lock in ioctl](https://github.com/ppajda/kernel_g3/commit/0085fca01d583dc96a18c35e0ba78d7f8d46d0da)
* [4ef147d ANDROID: input: keychord: fix race condition bug](https://github.com/ppajda/kernel_g3/commit/4ef147dc2d51bc7c252ca91cf0a4905be2293960)
* [0f18d35 ALSA: pcm: prevent UAF in snd_pcm_info](https://github.com/ppajda/kernel_g3/commit/0f18d35a308556fa9013f7844fca2f9ca078d018)
* [e0a9187 Prevent potential double frees in sg driver](https://github.com/ppajda/kernel_g3/commit/e0a9187c276103c403fe40632a422c06bddd847d)
* [3e2479e tracing: do not leak kernel addresses](https://github.com/ppajda/kernel_g3/commit/3e2479ecb0bec1f17a8008e81cc41ca4181ab377)
* [f7010b3 UPSTREAM: tracing: Fix trace_printk() to print when not using bprintk()](https://github.com/ppajda/kernel_g3/commit/f7010b343f40685a51b9175908b104123e07a6a3)
* [dd4f587 Prevent heap overflow in uvc driver](https://github.com/ppajda/kernel_g3/commit/dd4f58757519dc6224eecddbe165a7d1055bf452)
* [c268ee9 input: synaptics: put offset checks under mutex.](https://github.com/ppajda/kernel_g3/commit/c268ee9ac9890278a9fea02aeb167fc16e4b2c58)
* [4920539 msm: ADSPRPC: Buffer length truncated while validation](https://github.com/ppajda/kernel_g3/commit/492053936631619e13c9890c0faa3d4ec9fb6106)
* [df56998 input: synaptics_dsx: remove some sysfs nodes.](https://github.com/ppajda/kernel_g3/commit/df56998fa83f40d54d29e3b39639a42879a461ad)
* [7e2de43 Input: synaptics: check input, prevent sysfs races](https://github.com/ppajda/kernel_g3/commit/7e2de43dff985c67b3f086cfc39deaca316ef4dc)
* [50ea0f3 input: synaptics: defer sysfs creation during init](https://github.com/ppajda/kernel_g3/commit/50ea0f3a490a94d08554c774de1362a745cb99a6)
* [3a82c14 input: synaptics: allocate heap memory for buffer](https://github.com/ppajda/kernel_g3/commit/3a82c14c532b5008bca85198f0f3bffea0240627)
* [f6ab6a0 input: synaptics: allocate heap memory for temp buf](https://github.com/ppajda/kernel_g3/commit/f6ab6a05023b5daab714d3ce300efc1fe62e19b6)
* [0945946 msm: ispif: Remove handling of SD_SHUTDOWN](https://github.com/ppajda/kernel_g3/commit/094594641aaef305bf7dd9e41863346689b10586)
* [ca7cc13 net: socket: fix recvmmsg not returning error from sock_error](https://github.com/ppajda/kernel_g3/commit/ca7cc1358c2322cd56ba5a394df3cb39042fac35)
* [e5f1a97 ipv6: add complete rcu protection around np->opt](https://github.com/ppajda/kernel_g3/commit/e5f1a97bd85d1f7567f4c9610134566d33d2d7a4)
* [35dc6ea UPSTREAM: x86/mm/32: Enable full randomization on i386 and X86_32](https://github.com/ppajda/kernel_g3/commit/35dc6ea5b2c71f8b758db9ed843cc64645de810a)
* [76ce27b sdcardfs: fix space leak](https://github.com/ppajda/kernel_g3/commit/76ce27b44d23e65073105d8bb90775bef14b86c8)
* [ac5e199 sdcardfs: minor fixes](https://github.com/ppajda/kernel_g3/commit/ac5e199ffd33aca8a6de9085ba0d2cb799fbe2b5)
* [1a30bc8 sdcardfs: Backport and use some 3.10 hlist/hash macros](https://github.com/ppajda/kernel_g3/commit/1a30bc8e64d9cc77866e24741edb8c106c05e6f8)
* [157e022 ANDROID: sdcardfs: Add missing break](https://github.com/ppajda/kernel_g3/commit/157e022754286bff2ee86aa8752f03af6a920b68)
* [a01fcef ANDROID: Sdcardfs: Move gid derivation under flag](https://github.com/ppajda/kernel_g3/commit/a01fcef146a9810113f9b64d92aea1bf8f056f74)
* [9d2bc8e ANDROID: sdcardfs: override credential for ioctl to lower fs](https://github.com/ppajda/kernel_g3/commit/9d2bc8e9e2b5eab16d2d282ede92b6c521223b45)
* [f65bc63 sdcardfs: limit stacking depth](https://github.com/ppajda/kernel_g3/commit/f65bc63c7dcbe7f155c14e8f037227b562f5bfc3)
* [75bcc81 ANDROID: sdcardfs: Remove unnecessary lock](https://github.com/ppajda/kernel_g3/commit/75bcc81d058f5c0a61a5687702964557d43d5e1f)
* [d807d9a ANDROID: sdcardfs: use mount_nodev and fix a issue in sdcardfs_kill_sb](https://github.com/ppajda/kernel_g3/commit/d807d9aafc32096f3551f8af59d89aaf9f2a5d6e)
* [1b0b17a ANDROID: sdcardfs: remove dead function open_flags_to_access_mode()](https://github.com/ppajda/kernel_g3/commit/1b0b17aab2bec6050d77a0cb99538fe51fb10f78)
* [7d6d24c ANDROID: sdcardfs: d_splice_alias can return error values](https://github.com/ppajda/kernel_g3/commit/7d6d24ccaceda4fd6cb11c0414875635533e96a6)
* [49de287 ANDROID: mnt: Fix next_descendent](https://github.com/ppajda/kernel_g3/commit/49de287bcb54a3ed24a2e8fd2f4b83d1c8863242)
* [a792523 ANDROID: sdcardfs: Check for NULL in revalidate](https://github.com/ppajda/kernel_g3/commit/a79252396902c6e5286a609748a7e02c3d56e2fc)
* [873a359 ANDROID: sdcardfs: Add linux/kref.h include](https://github.com/ppajda/kernel_g3/commit/873a359105a5ff53a676d00d61d57196a3ed7cfc)
* [1a26885 ANDROID: sdcardfs: Move top to its own struct](https://github.com/ppajda/kernel_g3/commit/1a2688533ded9dce393e36efc3be07bf18b1eeac)
* [f11b9de ANDROID: sdcardfs: fix sdcardfs_destroy_inode for the inode RCU approach](https://github.com/ppajda/kernel_g3/commit/f11b9ded23f66f14d7f5548c966748cd6f2f853f)
* [fb0aab4 ANDROID: sdcardfs: Don't iput if we didn't igrab](https://github.com/ppajda/kernel_g3/commit/fb0aab4657a61653f428688038417fdd369035c0)
* [5e9ca17 ANDROID: sdcardfs: Call lower fs's revalidate](https://github.com/ppajda/kernel_g3/commit/5e9ca17cdac6a72c281a64c4c19587cb0768dcdc)
* [e232ff9 ANDROID: sdcardfs: Avoid setting GIDs outside of valid ranges](https://github.com/ppajda/kernel_g3/commit/e232ff933f562aa91f15c6e47e0aeafd6ea88fa6)
* [fba396b Revert "Revert "Android: sdcardfs: Don't do d_add for lower fs""](https://github.com/ppajda/kernel_g3/commit/fba396ba67737f21e13232142694ee318c7a300c)
* [1588b49 ANDROID: sdcardfs: Use filesystem specific hash](https://github.com/ppajda/kernel_g3/commit/1588b4931108ec89926e0be0b85dc7a25645b4a2)
* [b60b4c7 Revert "Android: sdcardfs: Don't do d_add for lower fs"](https://github.com/ppajda/kernel_g3/commit/b60b4c72977409fa3e5b5d922a3653644fb13adb)
* [6a09577 Android: sdcardfs: Don't complain in fixup_lower_ownership](https://github.com/ppajda/kernel_g3/commit/6a095774d4aa7acee8e3af35e43c27e97311e163)
* [f4c2092 Android: sdcardfs: Don't do d_add for lower fs](https://github.com/ppajda/kernel_g3/commit/f4c2092fa6501e30df3f3272febe9ada04bd0a02)
* [510a57a ANDROID: sdcardfs: ->iget fixes](https://github.com/ppajda/kernel_g3/commit/510a57acfb1a9b78a018c7cc86c9a68b551144c0)
* [21e2f68 Android: sdcardfs: Change cache GID value](https://github.com/ppajda/kernel_g3/commit/21e2f686b748f8f531939ae2d10c75182b80b641)
* [5f05a6a ANDROID: sdcardfs: Directly pass lower file for mmap](https://github.com/ppajda/kernel_g3/commit/5f05a6acc424fabae6107d31b92267f30a9995c7)
* [94f37c9 ANDROID: sdcardfs: update module info](https://github.com/ppajda/kernel_g3/commit/94f37c9ea04af37c953f03c36cdd77a2caacddc2)
* [43703ac ANDROID: sdcardfs: use d_splice_alias](https://github.com/ppajda/kernel_g3/commit/43703acf3ae4ac1c120deb30f660c7b4675ce4ba)
* [17d4af5 ANDROID: sdcardfs: fix ->llseek to update upper and lower offset](https://github.com/ppajda/kernel_g3/commit/17d4af5138fadc52c2b7966b7d65d37e528e3d07)
* [e684026 ANDROID: sdcardfs: copy lower inode attributes in ->ioctl](https://github.com/ppajda/kernel_g3/commit/e6840260e1f3fa1f2710f7d1d93788442eebf8f2)
* [e92d8a5 ANDROID: sdcardfs: remove unnecessary call to do_munmap](https://github.com/ppajda/kernel_g3/commit/e92d8a58149db25957eacdc876996ba172bde64e)
* [be25f4f ANDROID: sdcardfs: Fix style issues in macros](https://github.com/ppajda/kernel_g3/commit/be25f4fda955874855e6c4dc1dd611105e8363ce)
* [d2f9b19 ANDROID: sdcardfs: Use seq_puts over seq_printf](https://github.com/ppajda/kernel_g3/commit/d2f9b197a9a999f94aded8aeae6ae896fc582ee9)
* [28b3c43 ANDROID: sdcardfs: Use to kstrout](https://github.com/ppajda/kernel_g3/commit/28b3c43fbf9e8ff963609239d537afdeb675a0b0)
* [efcd009 ANDROID: sdcardfs: Use pr_[...] instead of printk](https://github.com/ppajda/kernel_g3/commit/efcd009d8b2e372f67b72f33d1439bef2ba6d50b)
* [2c00431 ANDROID: sdcardfs: remove unneeded null check](https://github.com/ppajda/kernel_g3/commit/2c0043166b2d25cbad2898e8dc42ab3fb11cb888)
* [6810fd1 ANDROID: sdcardfs: Fix style issues with comments](https://github.com/ppajda/kernel_g3/commit/6810fd1921df0e2122f0398cec60d4a38a869fd9)
* [a21a42e ANDROID: sdcardfs: Fix formatting](https://github.com/ppajda/kernel_g3/commit/a21a42ef7b37662b2393eef28de44937642842d1)
* [b24c32d ANDROID: sdcardfs: correct order of descriptors](https://github.com/ppajda/kernel_g3/commit/b24c32d41262ac0a36ceaea5b7a6388d1ea68642)
* [3148cc5 ANDROID: sdcardfs: Fix gid issue](https://github.com/ppajda/kernel_g3/commit/3148cc5c3e04b121a1b20f74a0c739842cc1b1ad)
* [eba3472 ANDROID: sdcardfs: Use tabs instead of spaces in multiuser.h](https://github.com/ppajda/kernel_g3/commit/eba3472201274b3a6fbebdbdcba8494d25e2e23e)
* [51e218e ANDROID: sdcardfs: Remove uninformative prints](https://github.com/ppajda/kernel_g3/commit/51e218ec4a773a27ceeab93969c8a80b49718921)
* [10353fd ANDROID: sdcardfs: move path_put outside of spinlock](https://github.com/ppajda/kernel_g3/commit/10353fdee38f453501716046c7a72daa69e2fcec)
* [4877590 ANDROID: sdcardfs: Use case insensitive hash function](https://github.com/ppajda/kernel_g3/commit/4877590b53fa1300b27b5c23c6860638da30f1e0)
* [5d17d74 ANDROID: sdcardfs: declare MODULE_ALIAS_FS](https://github.com/ppajda/kernel_g3/commit/5d17d743981e4bfbd8c23cd1f4513640b33e18e4)
* [ff5e526 fs: Limit sys_mount to only request filesystem modules.](https://github.com/ppajda/kernel_g3/commit/ff5e5262f9ebbf4be47c92e9a10153436c5515a0)
* [82d3b06 ANDROID: sdcardfs: Get the blocksize from the lower fs](https://github.com/ppajda/kernel_g3/commit/82d3b06fabeff4396cf820689d7581e15cc30422)
* [aa882e9 ANDROID: sdcardfs: Use d_invalidate instead of drop_recurisve](https://github.com/ppajda/kernel_g3/commit/aa882e9f80ccde83329789f5a08fdbc145405fbb)
* [279dc26 ANDROID: sdcardfs: Switch to internal case insensitive compare](https://github.com/ppajda/kernel_g3/commit/279dc26814682a4b19bddbb4f6ae84410f2b9451)
* [4795ddf ANDROID: sdcardfs: Use spin_lock_nested](https://github.com/ppajda/kernel_g3/commit/4795ddf28637e11466c963e8136420a5850d292d)
* [721d3f7 ANDROID: sdcardfs: Replace get/put with d_lock](https://github.com/ppajda/kernel_g3/commit/721d3f7114fd390a420661c285b1ea388a00f123)
* [ff8500c ANDROID: sdcardfs: rate limit warning print](https://github.com/ppajda/kernel_g3/commit/ff8500c032f9863f34306eee943f6644283e8a11)
* [ce09a56 ANDROID: sdcardfs: support direct-IO (DIO) operations](https://github.com/ppajda/kernel_g3/commit/ce09a56a89a797e01375f7ce662a586ff0601a61)
* [36f344c ANDROID: sdcardfs: implement vm_ops->page_mkwrite](https://github.com/ppajda/kernel_g3/commit/36f344c50bfb3ccc96b4a30375c1ebbbe87c03e1)
* [ca9e7ef ANDROID: sdcardfs: Don't bother deleting freelist](https://github.com/ppajda/kernel_g3/commit/ca9e7efb312c39df13793a6938b7430c596bee56)
* [32d7fb9 ANDROID: sdcardfs: Add missing path_put](https://github.com/ppajda/kernel_g3/commit/32d7fb9d1c31c567913f54a5f03ff81d592308ba)
* [b6fdf4e ANDROID: sdcardfs: Fix incorrect hash](https://github.com/ppajda/kernel_g3/commit/b6fdf4e0675e4ecd62fc0d0edbdee333556e5898)
* [f7e1c31 ANDROID: sdcardfs: Switch strcasecmp for internal call](https://github.com/ppajda/kernel_g3/commit/f7e1c31c9b1b8a03f05d0969878fd39195154799)
* [618189c constify d_lookup() arguments](https://github.com/ppajda/kernel_g3/commit/618189c4e1459a9df20ade30fae102f3a333ab2b)
* [1163ed0 constify __d_lookup() arguments](https://github.com/ppajda/kernel_g3/commit/1163ed0d38bb736ce239a5e86ef56e72236f6a04)
* [308781a ANDROID: sdcardfs: switch to full_name_hash and qstr](https://github.com/ppajda/kernel_g3/commit/308781ad643b7dbb467cd94b879b2d8016b3178e)
* [73b825a ANDROID: sdcardfs: Add GID Derivation to sdcardfs](https://github.com/ppajda/kernel_g3/commit/73b825ab636d55e40da9d5b4bc4c83b3a66d0ca4)
* [83ceeb7 ANDROID: sdcardfs: Remove redundant operation](https://github.com/ppajda/kernel_g3/commit/83ceeb71ad98f3cc4e08ff77740671e5cb8f4bf7)
* [a87e915 ANDROID: sdcardfs: add support for user permission isolation](https://github.com/ppajda/kernel_g3/commit/a87e9158ffcaee5b19ecfe734e1cee81ba828df3)
* [f34d44b ANDROID: sdcardfs: Refactor configfs interface](https://github.com/ppajda/kernel_g3/commit/f34d44b57e3db20d890002f0015cc5b840909d1f)
* [2252878 ANDROID: sdcardfs: Allow non-owners to touch](https://github.com/ppajda/kernel_g3/commit/225287875976f33cbc14b0962a6e38a0cc2be572)
* [ea4d2c5 ANDROID: mnt: remount should propagate to slaves of slaves](https://github.com/ppajda/kernel_g3/commit/ea4d2c56c5559f3dd9a53518025421c5e6e48cd1)
* [092a82f ANDROID: sdcardfs: Fix locking issue with permision fix up](https://github.com/ppajda/kernel_g3/commit/092a82f52f98072c258b85c702187ef93407fc6f)
* [a82d5e6 ANDROID: vfs: Missed updating truncate to truncate2](https://github.com/ppajda/kernel_g3/commit/a82d5e67623f4415329d264296aaa27965d87a57)
* [9031ebf BACKPORT: smarter propagate_mnt()](https://github.com/ppajda/kernel_g3/commit/9031ebff26f5eebe93b9623d8461ba3a8b2c8bd3)
* [ca9629b BACKPORT: don't bother with propagate_mnt() unless the target is shared](https://github.com/ppajda/kernel_g3/commit/ca9629ba927c3a4373bd903f7ce30f1b943cb563)
* [d9aee3d sdcardfs: Change magic value](https://github.com/ppajda/kernel_g3/commit/d9aee3d53fd04532a244f08b1d6502f2c41688f6)
* [13a1887 sdcardfs: Use per mount permissions](https://github.com/ppajda/kernel_g3/commit/13a18878a46a6f005233d9ca8b232cd71b4b11ed)
* [59a1738 sdcardfs: Add gid and mask to private mount data](https://github.com/ppajda/kernel_g3/commit/59a17382bb03ca08e99a4366dac40b935d4c50ab)
* [2dc07db sdcardfs: User new permission2 functions](https://github.com/ppajda/kernel_g3/commit/2dc07db34d6deae0f8a0c7eebe873254878f2aef)
* [04cb875 vfs: Add setattr2 for filesystems with per mount permissions](https://github.com/ppajda/kernel_g3/commit/04cb87520f110a098f80d7ed57e8fda545e5fd53)
* [5c8035d vfs: Add permission2 for filesystems with per mount permissions](https://github.com/ppajda/kernel_g3/commit/5c8035d3607c9dbb3d5c39a00f61f1a60e8a8e2c)
* [e55b29a vfs: Allow filesystems to access their private mount data](https://github.com/ppajda/kernel_g3/commit/e55b29a1cce54eecc49d47d67fa0370cbeaf995d)
* [b577c60 mnt: Add filesystem private data to mount points](https://github.com/ppajda/kernel_g3/commit/b577c6046e78b68476ba2253bc9d8cd55f874634)
* [4215162 ANDROID: sdcardfs: Fix backport issue for 3.10](https://github.com/ppajda/kernel_g3/commit/421516276773e47f4058b034f4f8967c8264493e)
* [e698366 sdcardfs: Move directory unlock before touch](https://github.com/ppajda/kernel_g3/commit/e6983667cfaceb8e0f5dad1873a3486b32d62e44)
* [8bdb159 sdcardfs: fix external storage exporting incorrect uid](https://github.com/ppajda/kernel_g3/commit/8bdb159c8f9cfed030d22c91c6445ac9b66b8a6c)
* [9bcccfe sdcardfs: Added top to sdcardfs_inode_info](https://github.com/ppajda/kernel_g3/commit/9bcccfe60513ed01b4edec8638a0f5dd8d37cd04)
* [c3e57f5 sdcardfs: Switch package list to RCU](https://github.com/ppajda/kernel_g3/commit/c3e57f5ed0dfeb5ed246e0ee1b63c1873f3ab96d)
* [1d49a24 sdcardfs: Fix locking for permission fix up](https://github.com/ppajda/kernel_g3/commit/1d49a24414b417541f7448c032af94ff5d73c41c)
* [175eb0b sdcardfs: Check for other cases on path lookup](https://github.com/ppajda/kernel_g3/commit/175eb0bf0affa163ebb02afaa9fc7383c468130f)
* [b2d2499 sdcardfs: override umask on mkdir and create](https://github.com/ppajda/kernel_g3/commit/b2d2499f08f0b091f68164f743f4ce9e5dd9dac2)
* [5bc4f2f ANDROID: sdcardfs: fix itnull.cocci warnings](https://github.com/ppajda/kernel_g3/commit/5bc4f2f0db4ab8076768d47274ff113ca1973be9)
* [6a81757 sdcardfs: Truncate packages_gid.list on overflow](https://github.com/ppajda/kernel_g3/commit/6a817576efeb40ca29043ab61917232f32dc7a43)
* [95b3544 vfs: change d_canonical_path to take two paths](https://github.com/ppajda/kernel_g3/commit/95b354488638e84cefb5e59a3fad5ebacfa3aa05)
* [dd05aaf sdcardfs: remove unneeded __init and __exit](https://github.com/ppajda/kernel_g3/commit/dd05aaf520a150da7292a1f5196dedfedbac19aa)
* [de879b0 sdcardfs: Remove unused code](https://github.com/ppajda/kernel_g3/commit/de879b0d6631d837db368a6012e74571fd96d174)
* [0063ca1 sdcardfs: remove effectless config option](https://github.com/ppajda/kernel_g3/commit/0063ca129ebcf6ec7f9d804e1fde7fea6d9fb61e)
* [2673e66 sdcardfs: Add support for d_canonicalize](https://github.com/ppajda/kernel_g3/commit/2673e66fe99cdb008c2174ee6a84e8f7fae55726)
* [339ceb1 sdcardfs: Bring up to date with Android M permissions:](https://github.com/ppajda/kernel_g3/commit/339ceb109ef8a008642bd4999ea8eb86658f0a78)
* [27456af sdcardfs: Changed type-cast in packagelist management](https://github.com/ppajda/kernel_g3/commit/27456af7f606215f311579d85a6f6f2e39ac2cd2)
* [ef63e9a sdcardfs: Port to 3.4](https://github.com/ppajda/kernel_g3/commit/ef63e9a75d635eccb54d474e3810a34b047b2068)
* [306df0e Included sdcardfs source code for kernel 3.0](https://github.com/ppajda/kernel_g3/commit/306df0ee701fbb7eb5a791b213fbbb102da52a4e)
* [131b190 consitify do_mount() arguments](https://github.com/ppajda/kernel_g3/commit/131b19009287f830ae0f41161dfdb6097902c72b)
* [6f5d6c0 do_add_mount()/umount -l races](https://github.com/ppajda/kernel_g3/commit/6f5d6c07a25ef9826aa27e2ee5c7e0fa10b01f93)
* [c09f57d fs: introduce inode operation ->update_time](https://github.com/ppajda/kernel_g3/commit/c09f57dabe0900f0488d22c4f0ed971f4168e7ba)
* [30a2041 VFS: Comment mount following code](https://github.com/ppajda/kernel_g3/commit/30a204154b32325b21d92cc047a8dcf93e90877d)
* [6e8b7bf VFS: Make clone_mnt()/copy_tree()/collect_mounts() return errors](https://github.com/ppajda/kernel_g3/commit/6e8b7bf2f4d7001df92ef3da8f3f348431c6a351)
* [8b573af get rid of magic in proc_namespace.c](https://github.com/ppajda/kernel_g3/commit/8b573afb03ef4713a53acbb20dd77c648283708f)
* [b112722 get rid of ->mnt_longterm](https://github.com/ppajda/kernel_g3/commit/b1127221dadc8c2fb4b386d7c002a21476a7b4fe)
* [3a73ab2 brlocks/lglocks: API cleanups](https://github.com/ppajda/kernel_g3/commit/3a73ab2036de5173a918bfa3bb81a9a4e92d0c48)
* [e2ea03d brlocks/lglocks: turn into functions](https://github.com/ppajda/kernel_g3/commit/e2ea03dd798a619e1ed1b3807fafac66853fd4c2)
* [cf8ce3f lglock: remove online variants of lock](https://github.com/ppajda/kernel_g3/commit/cf8ce3f6810197ec08f8b8b26465fa0ae5127744)
* [b6e88b3 Revert "get rid of s_files and files_lock"](https://github.com/ppajda/kernel_g3/commit/b6e88b379bdbd40b518c8a7ca6db92b4bb4e6590)

***

12-12-2017
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
