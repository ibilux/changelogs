Lineage eXTenDed Kernel los-15.0 source Changelog:
============================================================

02-14-2018
====================

* [2454a62 Up version R5](https://github.com/ppajda/kernel_g3/commit/2454a62d5da4eb96955133950b099f391193b56d)
* [8c6634f kgsl: fix derp](https://github.com/ppajda/kernel_g3/commit/8c6634faa4c455ef4db11ddea6459fb560673ff8)
* [aa006fc ANDROID: xattr: Pass EOPNOTSUPP to permission2](https://github.com/ppajda/kernel_g3/commit/aa006fcfd9d5fd2832af968948e3babdb6187c9f)
* [d22b5f0 Enable setting security contexts on rootfs inodes.](https://github.com/ppajda/kernel_g3/commit/d22b5f0ec7d6d4ac8a1aa85b7dafe3e9084f5a9a)
* [ff0af9c selinux: enable genfscon labeling for sysfs and pstore files](https://github.com/ppajda/kernel_g3/commit/ff0af9cf0c80793325b6c86b661c91d6428e9b9a)
* [501c2e9 selinux: enable per-file labeling for debugfs files.](https://github.com/ppajda/kernel_g3/commit/501c2e9254902bc6ce40dcd39092c5e132d9298e)
* [cab3ea9 defconfigs: cleanup](https://github.com/ppajda/kernel_g3/commit/cab3ea9ba58b93fbb5cf0266f14de0ed4b3ed288)
* [0a1c6e8 usb: gadget: fix build](https://github.com/ppajda/kernel_g3/commit/0a1c6e886accee87517bf707e53fec4d8c7f9e63)
* [e183854 Revert "usb: gadget: f_hid: fix build error"](https://github.com/ppajda/kernel_g3/commit/e183854ca0765e4a9e70433be0218c0e0307e85c)
* [7a2e1da defconfig: Disable CONFIG_MSM_SMP2P_TEST](https://github.com/ppajda/kernel_g3/commit/7a2e1dacdfc5e5a36b26f5ddb99f6a8de0accb29)
* [e3e300f defconfig: Disable perf events](https://github.com/ppajda/kernel_g3/commit/e3e300f9a71ea0f91f3097d7e2ca9c800904792a)

***

01-30-2018
====================

* [0bd6452 kgsl: fix derp](https://github.com/ppajda/kernel_g3/commit/0bd6452aed0c8d0671b49facbe71c1ed2bbc9165)
* [d6e8d6e include: Include dummy MSM Audio Calibration header * This needs to be included in apq8084/msm8974 kernel's exported headers to build the msm audio hal as of oreo-mr1. * Demon000 deserves credit for the initial idea behind this commit, as he pointed out which structs were used.](https://github.com/ppajda/kernel_g3/commit/d6e8d6e7459aaef49a56724c20e9a18b2899b859)
* [395f795 ANDROID: binder: fix OOB write in __binder_update_page_range](https://github.com/ppajda/kernel_g3/commit/395f795670c6ba30f852b7226df25cc44cc0ba35)
* [5a6b6ae UPSTREAM: include/linux/mm.h: add PAGE_ALIGNED() helper](https://github.com/ppajda/kernel_g3/commit/5a6b6aeff47f49260dde6ccaa7ebc5d1ee0d8e87)
* [3d397d2 android: binder: Move buffer out of area shared with user space](https://github.com/ppajda/kernel_g3/commit/3d397d20a406030a96f9f04385894d6c2171ccfb)
* [5dd228d android: binder: Refactor prev and next buffer into a helper function](https://github.com/ppajda/kernel_g3/commit/5dd228d970811274f8696c5c0537a4a154e5cc9b)
* [0fc08a5 BACKPORT: staging: android: fix missing a blank line after declarations](https://github.com/ppajda/kernel_g3/commit/0fc08a5534718e39aceda584c9e21426fffa93ff)
* [4156a72 UPSTREAM: Staging: Android: removed an unnecessary else statement](https://github.com/ppajda/kernel_g3/commit/4156a72c47a4104d60936b6717a4d3ff03eb44c8)
* [5321299 binder: always allocate/map first BINDER_MIN_ALLOC pages](https://github.com/ppajda/kernel_g3/commit/53212992d9dd92cd2d2f8873027fa64bda4fd052)
* [eed509a ANDROID: sdcardfs: Move default_normal to superblock](https://github.com/ppajda/kernel_g3/commit/eed509a5f3100100ec902122b1ab4a1fe01f1131)
* [e4c50fe kgsl: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/e4c50fe5b8ec30e0c6674fcb55bfd812816b6ab3)
* [f0ba994 uio: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/f0ba99498478be4ad49f5979355ff27a67764e6d)
* [19849f2 spmi: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/19849f23d2ab2185b43e6595ffd4021abe9555db)
* [78f0931 slimbus: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/78f0931e062962bce039029a1aeaf9fe030bdf56)
* [d18b59c ppp: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/d18b59cb136997fa9717b1828a835e9065343ef7)

***

01-23-2018
====================


***

01-16-2018
====================

* [cbbf0fb Revert "msm: camera: move firmware to vendor"](https://github.com/ppajda/kernel_g3/commit/cbbf0fbb6d3cd07c35ae592bd5c5b7fe8b5aac14)

***

01-15-2018
====================

* [0129a5e mm: change max readahead size to 512KB](https://github.com/ppajda/kernel_g3/commit/0129a5e23c1041778657e14d7e6bbc34146b4d7e)
* [3a2af4e BACKPORT: ARM: dts: msm: Mount the system partition during early init](https://github.com/ppajda/kernel_g3/commit/3a2af4ed49da19b592bb3895b97eda22dd69597f)
* [5b6dfcd ANDROID: sdcardfs: Fix missing break on default_normal](https://github.com/ppajda/kernel_g3/commit/5b6dfcd97714c065271c76a2f5851eec4bbe987f)
* [e37d7d3 msm: cpp: Fix for integer overflow in cpp](https://github.com/ppajda/kernel_g3/commit/e37d7d3ce263980cf5e4c8e441f0737e9a00470d)
* [609a9eb msm: vidc: Check video buffer handle for Null pointer access.](https://github.com/ppajda/kernel_g3/commit/609a9ebf53f06b3c569bbdd33edeb4f3f3318291)
* [2f07aa0 msm:vidc: Fix klockwork errors in video driver.](https://github.com/ppajda/kernel_g3/commit/2f07aa094ae77dc9afcd63bb8b0c52b5e04bdfff)
* [ce53892 msm:vidc: Add null check for handle in smem buffer comparision.](https://github.com/ppajda/kernel_g3/commit/ce538925cb479233f21fd3616e56e8cfc596af2f)
* [99339ec msm: vidc: add ion_handle checking before mapping buffers.](https://github.com/ppajda/kernel_g3/commit/99339ec818e8c6be27531feb10ceab64e0c932b5)
* [e14e3a8 msm: camera: cpp: Add validation for v4l2 ioctl arguments](https://github.com/ppajda/kernel_g3/commit/e14e3a8fd142c1ff851a2a782644390b2bc4e124)
* [e5a781a staging: android: ashmem: fix a race condition in ASHMEM_SET_SIZE ioctl](https://github.com/ppajda/kernel_g3/commit/e5a781a883dbe8858c0549a500957829cfca91bf)
* [62db3f4 ANDROID: mnt: Fix freeing of mount data](https://github.com/ppajda/kernel_g3/commit/62db3f419f5b549defbb096bb632d7902e1f599b)
* [2fc4595 ANDROID: sdcardfs: Add default_normal option](https://github.com/ppajda/kernel_g3/commit/2fc4595f1ff1362fc7f6cdcd2421afd2af53392a)
* [2a4f425 ANDROID: sdcardfs: notify lower file of opens](https://github.com/ppajda/kernel_g3/commit/2a4f425cf4e2c59940aaa0691a33e0c2ab9bccd5)
* [66acc4b changes kernel headers](https://github.com/ppajda/kernel_g3/commit/66acc4b1201d6dff3865e202bb5726e8b03d3c94)
* [25c5831 Fastcharge: Increase ac charge to 1800mA](https://github.com/ppajda/kernel_g3/commit/25c58310ae81c54994fb1755261df17d6d0b0e0b)
* [3426c0c msm: camera: move firmware to vendor](https://github.com/ppajda/kernel_g3/commit/3426c0c1e3d7a2ed710c36b9745a9e3c3703877e)
* [f0d225f g3: update config to point bcmdhd firmware to vendor](https://github.com/ppajda/kernel_g3/commit/f0d225f8ece94740c07c19bbd49f8aaad0026409)
* [8f74746 bcmdhd_g3: Update driver from LG's Android N](https://github.com/ppajda/kernel_g3/commit/8f7474655e5059aae12e469c630a0f18ae70e483)

***

01-01-2018
====================

* [bfc6d3f defconfigs: cleanup](https://github.com/ppajda/kernel_g3/commit/bfc6d3f591c23e1d455d0f8e55ed9a8ea8a1d87d)
* [6f56d18 mmc: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/6f56d183410741bd515c12c7ba664726dd2a7bf3)
* [d6b4c17 inotify: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/d6b4c17d95853b667f31214e55eb7bd6f96c1ca4)
* [1eb01a7 ocmem_sched: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/1eb01a73f08a33ad5c19b7f728cea609ad2f6b9f)
* [195e0e1 dm: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/195e0e159f27201978b64edbdf4d03e8bbe4e54f)
* [a5e3dbc iommu: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/a5e3dbc4f072b0e6e960b7eaae6ef75077e2bb1a)
* [f1cdd81 iommu: moving initialization earlier](https://github.com/ppajda/kernel_g3/commit/f1cdd81e42cadcd9448f2199a8c13dc7e8fbb37a)
* [31dc443 cgroup: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/31dc4436bccfdf47624d4d4c126a468a4ce0d76f)
* [b16d5ff tune again thermal](https://github.com/ppajda/kernel_g3/commit/b16d5ff17cfd8bbeea8c58b4562c081fa13a9a77)
* [deed607 fs: dynamic fsync: remove powersuspend](https://github.com/ppajda/kernel_g3/commit/deed607636058e0c78ad894550af394e533e9dd9)
* [a77705b Fix code errors detected using Linaro GCC 6.1.1-rc1](https://github.com/ppajda/kernel_g3/commit/a77705bedd104776089578a026567baffb5f7526)

***

12-27-2017
====================


***

12-26-2017
====================

* [d9a6ab9 mdss: kcal: make colors more vivid](https://github.com/ppajda/kernel_g3/commit/d9a6ab93da05aae235b4aa63c8651a7bf554b211)
* [7a5e509 usb: gadget: f_hid: fix build error](https://github.com/ppajda/kernel_g3/commit/7a5e50900ad8061f31f27573b931a5290cbb46ea)
* [362bbc4 usb: gadget: u_serial: fix typo which cause build warning](https://github.com/ppajda/kernel_g3/commit/362bbc4d4843a81af50a2815ab4f687a13be7c95)
* [d1ed0d6 usb: gadget: add multiple definition guards](https://github.com/ppajda/kernel_g3/commit/d1ed0d60cf88c4f72efa3e7ab1cb08e5060de9d5)
* [ec93c85 Revert "usb: gadget: Enable HID function for charging mode"](https://github.com/ppajda/kernel_g3/commit/ec93c857ef1d5e2b11411492aea2450352df831f)
* [1a828a5 USB: android: Fix a NULL pointer dereference](https://github.com/ppajda/kernel_g3/commit/1a828a5e845813b30d8bb13f26f1c35c707d84b6)
* [671e8ef usb: dwc3: Do not call WARN_ON_ONCE from interrupt context](https://github.com/ppajda/kernel_g3/commit/671e8ef1bbaf26483bd71edc82c93e1b442a04de)
* [b57455e usb: gadget: FunctionFS and SuperSpeed updates](https://github.com/ppajda/kernel_g3/commit/b57455e3b550b5bc0a4128d97192925bb5988780)
* [71c2693 f_fs: ffs_func_free: cleanup requests allocated by autoconfig](https://github.com/ppajda/kernel_g3/commit/71c26937276990f5c1d776c8d20320b85e543739)
* [69ca9ec usb: gadget: f_fs: Fix enumeration in fullspeed mode](https://github.com/ppajda/kernel_g3/commit/69ca9eca291345abc1df12858a603601fc44aa0f)

***

12-24-2017
====================


***

12-22-2017
====================

* [f673899 workqueue: fix derp](https://github.com/ppajda/kernel_g3/commit/f673899de18595391124d4ad06f5d4749c1e3305)
* [8ff8697 workqueue: Fix flag collision](https://github.com/ppajda/kernel_g3/commit/8ff86974dcedb2471e862a198bdd86515e5c13ea)
* [a48fbbf workqueue: implicit ordered attribute should be overridable](https://github.com/ppajda/kernel_g3/commit/a48fbbf1a03ca77d6d902882dc4f678f9d9fc2bf)
* [50554a7 workqueue: restore WQ_UNBOUND/max_active==1 to be ordered](https://github.com/ppajda/kernel_g3/commit/50554a70b01c01ecaff692b5516d9a6e19516069)
* [fae4b41 workqueue.c: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/fae4b411704e4107a2e656289c7645b1e492d0f6)
* [8e13913 workqueue: Add system wide power_efficient workqueues](https://github.com/ppajda/kernel_g3/commit/8e1391302ca2b4acc31034bc8c4fe78628d294f1)
* [1822cb4 Workqueue: fix permissions](https://github.com/ppajda/kernel_g3/commit/1822cb46ba90c9e6909fcc4f49c17449d6e3a8d7)
* [5a53ac1 workqueue: fix ghost PENDING flag while doing MQ IO](https://github.com/ppajda/kernel_g3/commit/5a53ac1cb04897553aca123b47c31fc3d13f4e16)
* [14a5b4e Revert "workqueue: make sure delayed work run in local cpu"](https://github.com/ppajda/kernel_g3/commit/14a5b4ede9dc40d6c71004b0ca45b7710f5379b0)
* [090f130 workqueue: make sure delayed work run in local cpu](https://github.com/ppajda/kernel_g3/commit/090f1301177d369ca26ffbcada3178fd0844e2c9)
* [97fc7a1 workqueue: fix hang involving racing cancel[_delayed]_work_sync()'s for PREEMPT_NONE](https://github.com/ppajda/kernel_g3/commit/97fc7a1975ac558fb40889ab993c2c286b645876)
* [4575999 workqueue: fix subtle pool management issue which can stall whole worker_pool](https://github.com/ppajda/kernel_g3/commit/4575999750157b7ba94ced16dc2d018ba1d7b576)
* [9e90f6c workqueue: zero cpumask of wq_numa_possible_cpumask on init](https://github.com/ppajda/kernel_g3/commit/9e90f6c1bd5e94958b692f1252d21265c165a3fb)
* [b4acd93 workqueue: fix dev_set_uevent_suppress() imbalance](https://github.com/ppajda/kernel_g3/commit/b4acd933fc54439c696f8b4ec3a3b5fd7f2820e1)
* [e4e2b2b workqueue: make rescuer_thread() empty wq->maydays list before exiting](https://github.com/ppajda/kernel_g3/commit/e4e2b2b537c21259ba5f3a488a5b317347533c75)
* [0b36063 workqueue: fix a possible race condition between rescuer and pwq-release](https://github.com/ppajda/kernel_g3/commit/0b3606301531747aff77a40c6a2012480e9efacd)
* [8799466 workqueue: fix bugs in wq_update_unbound_numa() failure path](https://github.com/ppajda/kernel_g3/commit/87994662f3e99731ebc704b9fe6c271f9b3ba133)
* [58f6c36 workqueue: fix ordered workqueues in NUMA setups](https://github.com/ppajda/kernel_g3/commit/58f6c362d522a9c056f6f68ba37292f5611ccf6b)
* [722bd06 workqueue: copy workqueue_attrs with all fields](https://github.com/ppajda/kernel_g3/commit/722bd06f91af9f29ddf8ec5eb10c5ffc13633c11)
* [7d4c436 workqueue: don't perform NUMA-aware allocations on offline nodes in wq_numa_init()](https://github.com/ppajda/kernel_g3/commit/7d4c436f4e3d47cc42ba2b1df22e1fe874f09561)
* [c697189 workqueue: Make schedule_work() available again to non GPL modules](https://github.com/ppajda/kernel_g3/commit/c697189fa0461a62e0f3ca9b33c0161189bdccbb)
* [2b1c100 workqueue: correct handling of the pool spin_lock](https://github.com/ppajda/kernel_g3/commit/2b1c10004776fa9674e89a15ff9632e3381d42c1)
* [fe920c8 workqueue: workqueue_congested() shouldn't translate WORK_CPU_UNBOUND into node number](https://github.com/ppajda/kernel_g3/commit/fe920c8d2a541491dbcfb7f99898b1ff99f0650b)
* [a7c817f kthread: implement probe_kthread_data()](https://github.com/ppajda/kernel_g3/commit/a7c817f2fb27ee741117e4b43d029aa87b3a141d)
* [446e7c0 workqueue: include workqueue info when printing debug dump of a worker task](https://github.com/ppajda/kernel_g3/commit/446e7c051b8dd28db1c99f35fceb9930948f73ae)
* [03db82f workqueue: use kmem_cache_free() instead of kfree()](https://github.com/ppajda/kernel_g3/commit/03db82fe5b7b9ba54931c22877a51dcf0cdef9ff)
* [e58a332 workqueue: avoid false negative WARN_ON() in destroy_workqueue()](https://github.com/ppajda/kernel_g3/commit/e58a332ef6de35a81f7d67ec3389ef67f743b3b7)
* [ea24e88 workqueue: update sysfs interface to reflect NUMA awareness and a kernel param to disable NUMA affinity](https://github.com/ppajda/kernel_g3/commit/ea24e886850bbd1c630a5e8230dfaca1810aa69c)
* [2e3eef4 workqueue: implement NUMA affinity for unbound workqueues](https://github.com/ppajda/kernel_g3/commit/2e3eef47f8941f7643341d7042b8c385d8daaeea)
* [aa187bd workqueue: introduce put_pwq_unlocked()](https://github.com/ppajda/kernel_g3/commit/aa187bda71187adf463ca2e5e559cedfdbe8e916)
* [6b5c2da workqueue: introduce numa_pwq_tbl_install()](https://github.com/ppajda/kernel_g3/commit/6b5c2dafa076e73868863f46fd7716e0fd72e933)
* [185e894 workqueue: use NUMA-aware allocation for pool_workqueues](https://github.com/ppajda/kernel_g3/commit/185e89451beb7f027699a73433d5b470657e31df)
* [194f737 workqueue: break init_and_link_pwq() into two functions and introduce alloc_unbound_pwq()](https://github.com/ppajda/kernel_g3/commit/194f73784b71026287b75b006efd78bf610b968c)
* [78fc2f6 workqueue: map an unbound workqueues to multiple per-node pool_workqueues](https://github.com/ppajda/kernel_g3/commit/78fc2f6a469a810640657eb27482b1bdbcf52199)
* [601e72d workqueue: move hot fields of workqueue_struct to the end](https://github.com/ppajda/kernel_g3/commit/601e72dc009376c833e1cede17280ff0e7e1557b)
* [05cef547 workqueue: make workqueue->name[] fixed len](https://github.com/ppajda/kernel_g3/commit/05cef547fe209a187fadd538e59ab5a3da141cea)
* [8670457 workqueue: add workqueue->unbound_attrs](https://github.com/ppajda/kernel_g3/commit/8670457f5454d4e80a2e613651f6f335e2ced4b6)
* [7197a13 workqueue: determine NUMA node of workers accourding to the allowed cpumask](https://github.com/ppajda/kernel_g3/commit/7197a13954f42f5aec485611977b1469d7010c67)
* [7ba14ab workqueue: drop 'H' from kworker names of unbound worker pools](https://github.com/ppajda/kernel_g3/commit/7ba14ab213bbe83da60c82cb33315e514d0edc0f)
* [17b6652 workqueue: add wq_numa_tbl_len and wq_numa_possible_cpumask[]](https://github.com/ppajda/kernel_g3/commit/17b6652ae308ac0ccbaa2cfd11fd7c20ada304c6)
* [09ab430 workqueue: move pwq_pool_locking outside of get/put_unbound_pool()](https://github.com/ppajda/kernel_g3/commit/09ab4300a099ca3f18bdb47206e9d32975629b97)
* [428e454 workqueue: fix memory leak in apply_workqueue_attrs()](https://github.com/ppajda/kernel_g3/commit/428e4545766435ee72aecc8122aa5f5c3314adee)
* [f62c42e workqueue: fix unbound workqueue attrs hashing / comparison](https://github.com/ppajda/kernel_g3/commit/f62c42e379edae8973403f72c4135af1f6d3fa1b)
* [59f2b7e workqueue: fix race condition in unbound workqueue free path](https://github.com/ppajda/kernel_g3/commit/59f2b7e5c3e0d78a8e9fa03ec95798eb70c628d4)
* [baa08ba workqueue: remove pwq_lock which is no longer used](https://github.com/ppajda/kernel_g3/commit/baa08bac76b27f69f9e1f3d9bf7faa9ed0384eca)
* [1d9436c workqueue: protect wq->saved_max_active with wq->mutex](https://github.com/ppajda/kernel_g3/commit/1d9436c9574977a526794fa0ca6a9fa53d42f93d)
* [f8bde4f workqueue: protect wq->pwqs and iteration with wq->mutex](https://github.com/ppajda/kernel_g3/commit/f8bde4f84d45c8af562cf90d4a8d7bc5dd322ea2)
* [67ebaa7 workqueue: protect wq->nr_drainers and ->flags with wq->mutex](https://github.com/ppajda/kernel_g3/commit/67ebaa78cba58a5d6396880cb107c29a9acab4fb)
* [9aa2f38 workqueue: rename wq->flush_mutex to wq->mutex](https://github.com/ppajda/kernel_g3/commit/9aa2f38f7ced70550d32145096f7c6c2a7b61ed2)
* [11e0c59 workqueue: rename wq_mutex to wq_pool_mutex](https://github.com/ppajda/kernel_g3/commit/11e0c594ee1632bb611a1cbb498910791d0e5955)
* [cffcb6d workqueue: avoid false negative in assert_manager_or_pool_lock()](https://github.com/ppajda/kernel_g3/commit/cffcb6d241ac8cdad83807e580f4c1f1e29f9be4)
* [0f57ef5 workqueue: use rcu_read_lock_sched() instead for accessing pwq in RCU](https://github.com/ppajda/kernel_g3/commit/0f57ef559bba7394decf435a384a4fe3bece5da1)
* [f2093fc workqueue: kick a worker in pwq_adjust_max_active()](https://github.com/ppajda/kernel_g3/commit/f2093fcd3b79d2a5ee48b6f271e5164d1dfb6ad7)
* [f42ac47 workqueue: simplify current_is_workqueue_rescuer()](https://github.com/ppajda/kernel_g3/commit/f42ac47ac4abd023dd95369233c6e86031be7abc)
* [875b599 workqueue: add missing POOL_FREEZING](https://github.com/ppajda/kernel_g3/commit/875b59997f504493ed3d86b9e05636940ec17eab)
* [06f33d6 workqueue: restore CPU affinity of unbound workers on CPU_ONLINE](https://github.com/ppajda/kernel_g3/commit/06f33d67f10f72f381e0dfa8a546fd4ee0eb3681)
* [3c7fe4b workqueue: directly restore CPU affinity of workers from CPU_ONLINE](https://github.com/ppajda/kernel_g3/commit/3c7fe4b2b6479d9ac7561ed3c08894458db65d65)
* [0384d70 workqueue: relocate rebind_workers()](https://github.com/ppajda/kernel_g3/commit/0384d70619d596cdbdfa3e8a0a63d8d40c2595fc)
* [464e034 workqueue: convert worker_pool->worker_ida to idr and implement for_each_pool_worker()](https://github.com/ppajda/kernel_g3/commit/464e0341dece48fc50d2d36c38bcf25e16b891e1)
* [4f1c6d9 kgsl: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/4f1c6d924719f1a31936d0f9915dd9323d7318d8)
* [d4f2ee2 ion: remove deprecated idr_](https://github.com/ppajda/kernel_g3/commit/d4f2ee2980dfbe34513922332b12f89737ee0216)
* [d3d9495 gpio: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/d3d9495d44a459f3cfedeb37165b7f98f5f41a59)
* [8a4f7aa events: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/8a4f7aa23239f9a4793db65229849e0c39a6b089)
* [7f6ac0f block: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/7f6ac0f863e0ae1cf9fd1bbdae4dacab6ff3e63a)
* [6e73754 scsi: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/6e7375499536bd7e342c4aacaf708f2a8d65fa7a)
* [da6ef53 [SCSI] st: remove st_mutex](https://github.com/ppajda/kernel_g3/commit/da6ef53d3f9fa1e317f2d314a3f95b69f8668a52)
* [ced1c59e [SCSI] st: clean up device file creation and removal](https://github.com/ppajda/kernel_g3/commit/ced1c59e4b5bf2e7f6c0bd10a799bd3cfcce9d34)
* [84829a05 [SCSI] st: get rid of scsi_tapes array](https://github.com/ppajda/kernel_g3/commit/84829a0585efdd87b652b4e64d5b45184b65d089)
* [ffcebeb [SCSI] st: clean up dev cleanup in st_probe](https://github.com/ppajda/kernel_g3/commit/ffcebebf00dabf871756c853ff0ae8a1fea8a005)
* [b82af75 [SCSI] st: Use static class attributes](https://github.com/ppajda/kernel_g3/commit/b82af75b50b585393eb6d9ef12304c6a7249badf)
* [2b341c3 block/loop: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/2b341c3137ee0a3c728aab97649fa392a75ef0d5)
* [74617ff posix-timers: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/74617ff82c20f3c895b99bfbc9ddcc758e982d67)
* [95d0e0f idr: document exit conditions on idr_for_each_entry better](https://github.com/ppajda/kernel_g3/commit/95d0e0f59b8d564f9864d773627c731f155b4df8)
* [100ef7b idr: make idr_layer larger](https://github.com/ppajda/kernel_g3/commit/100ef7b81e2c2cc4fe6e8b08cc02a5bbd33157f6)
* [0926240 idr: fix overflow bug during maximum ID calculation at maximum height](https://github.com/ppajda/kernel_g3/commit/092624044f63fbb4f867dcf2df3b97d375da7419)
* [e524e4b idr: introduce idr_alloc_cyclic()](https://github.com/ppajda/kernel_g3/commit/e524e4b05d03cdaf658e7446b11d0ea3345c080c)
* [2170a53 idr: idr_alloc() shouldn't trigger lowmem warning when preloaded](https://github.com/ppajda/kernel_g3/commit/2170a5324b985ffdaa9718dd3f251cb81bd1dcb9)
* [c962380 idr: deprecate idr_pre_get() and idr_get_new[_above]()](https://github.com/ppajda/kernel_g3/commit/c9623802f17e01e1727f98ebf16ed49521b41526)
* [bb2603b idr: fix new kernel-doc warnings](https://github.com/ppajda/kernel_g3/commit/bb2603bd26d51a67274121584dc7078db3f4cdd8)
* [7ed3b81 idr: remove WARN_ON_ONCE() on negative IDs](https://github.com/ppajda/kernel_g3/commit/7ed3b81fa9b3fec803159ee7858c2c672ddccaa1)
* [f75d786 idr: explain WARN_ON_ONCE() on negative IDs out-of-range ID](https://github.com/ppajda/kernel_g3/commit/f75d78618ef4cecc98ba47c716bbb13bb599709d)
* [a3dd55c idr: implement lookup hint](https://github.com/ppajda/kernel_g3/commit/a3dd55c7947a5e8b0bb6c6ad67cc85d2db157016)
* [632186c idr: add idr_layer->prefix](https://github.com/ppajda/kernel_g3/commit/632186c3a08e7bcae080d3f31c0ce5b48c6eeaa6)
* [d032220 idr: remove length restriction from idr_layer->bitmap](https://github.com/ppajda/kernel_g3/commit/d032220296d86b0420930d3c7700e0f5a3920537)
* [4bec27f idr: remove MAX_IDR_MASK and move left MAX_IDR_* into idr.c](https://github.com/ppajda/kernel_g3/commit/4bec27ff8497da27ffdb850d77f67d150438555b)
* [e3c4507 Remove deprecated idr_remove_all and fix derps](https://github.com/ppajda/kernel_g3/commit/e3c450740d689108ff1d20aeb8bd286cd601f2c0)
* [748df9c idr: rename MAX_LEVEL to MAX_IDR_LEVEL](https://github.com/ppajda/kernel_g3/commit/748df9c5ae9af9e868d6dc15c7418b1a116d1c10)
* [e63b230 idr: fix top layer handling](https://github.com/ppajda/kernel_g3/commit/e63b230afbced021a2caea8025085d0150e529bc)
* [4a35aa9 idr: implement idr_preload[_end]() and idr_alloc()](https://github.com/ppajda/kernel_g3/commit/4a35aa963b9da3a34a881403b3c148a81d1ce8c9)
* [77d3410 idr: refactor idr_get_new_above()](https://github.com/ppajda/kernel_g3/commit/77d3410f877a14fd65cc07e437de92255f788edb)
* [325abb2 idr: remove _idr_rc_to_errno() hack](https://github.com/ppajda/kernel_g3/commit/325abb2c4d7dde70f06253f65a0597a3054d8b19)
* [0f09017 idr: relocate idr_for_each_entry() and reorganize id[r|a]_get_new()](https://github.com/ppajda/kernel_g3/commit/0f090174e12f8e491ce6f5fd618084182afc7cc0)
* [8e6dc4f idr: deprecate idr_remove_all()](https://github.com/ppajda/kernel_g3/commit/8e6dc4fea5f5a3b8efdee445ce1609b9fdd7c995)
* [c06dcb8 idr: make idr_destroy() imply idr_remove_all()](https://github.com/ppajda/kernel_g3/commit/c06dcb8530d017b8980164060bbbdcdb07d5e4fe)
* [837ba4d locking: Various static lock initializer fixes](https://github.com/ppajda/kernel_g3/commit/837ba4dff1685c75b8105f49ff5d25cd164ecdb4)
* [4e9e930 sched: replace PF_THREAD_BOUND with PF_NO_SETAFFINITY](https://github.com/ppajda/kernel_g3/commit/4e9e930b3d964f6f95282de2f38d5616927742ca)
* [8baceca Pull workqueue fix from Tejun Heo](https://github.com/ppajda/kernel_g3/commit/8bacecabfaa4b312fe703cadb0639cc4135e6b65)
* [c882af6 workqueue: rename workqueue_lock to wq_mayday_lock](https://github.com/ppajda/kernel_g3/commit/c882af60947d75bd67e67f9ac48250af9b032773)
* [3c8b677 workqueue: separate out pool_workqueue locking into pwq_lock](https://github.com/ppajda/kernel_g3/commit/3c8b67795a90da8cc816d1640125c938911c8293)
* [b1faa82 workqueue: separate out pool and workqueue locking into wq_mutex](https://github.com/ppajda/kernel_g3/commit/b1faa82d81f4d255204aa57fb48593e9c3223f8d)
* [fcd8089 workqueue: relocate global variable defs and function decls in workqueue.c](https://github.com/ppajda/kernel_g3/commit/fcd80898f52346c2b0e2a47c5658735109b48eae)
* [7e37ad9 workqueue: better define locking rules around worker creation / destruction](https://github.com/ppajda/kernel_g3/commit/7e37ad975b74524841246be6daed9c02e9a6145d)
* [6ee16ed workqueue: factor out initial worker creation into create_and_start_worker()](https://github.com/ppajda/kernel_g3/commit/6ee16edcda8327d1699c628a3968520f4e9822d2)
* [f3471f0 workqueue: rename worker_pool->assoc_mutex to ->manager_mutex](https://github.com/ppajda/kernel_g3/commit/f3471f04380b4ff129f0da27224ddb7c3d48e3d7)
* [c262705 workqueue: inline trivial wrappers](https://github.com/ppajda/kernel_g3/commit/c262705a76d94ecbd2cdc04ec581ffbb7f8a7c0a)
* [007d881 workqueue: rename @id to @pi in for_each_each_pool()](https://github.com/ppajda/kernel_g3/commit/007d881e594d030b216c2d5adc9b83d99c31e728)
* [b34acc2 workqueue: update comments and a warning message](https://github.com/ppajda/kernel_g3/commit/b34acc233e4ca666e59e11c6748393e25fe92607)
* [d394cd0 workqueue: fix max_active handling in init_and_link_pwq()](https://github.com/ppajda/kernel_g3/commit/d394cd0a4a60718a2a6fa84e1c436f90866eedb2)
* [3103466 workqueue: implement and use pwq_adjust_max_active()](https://github.com/ppajda/kernel_g3/commit/310346631c39de3126e52c38e11d563430d74b81)
* [c6d2140 workqueue: relocate pwq_set_max_active()](https://github.com/ppajda/kernel_g3/commit/c6d21400dc22ab59b1872dc6bca8b780eeb14003)
* [a64d8ce workqueue: convert to idr_alloc()](https://github.com/ppajda/kernel_g3/commit/a64d8ce062f9c74478bc3e96b73063bf7f3f1c06)
* [fe7b5c9 workqueue: implement current_is_workqueue_rescuer()](https://github.com/ppajda/kernel_g3/commit/fe7b5c99ee2eca9d72c885ad443c063db27cd37c)
* [558c502 workqueue: implement sysfs interface for workqueues](https://github.com/ppajda/kernel_g3/commit/558c50258960c4fbb68826dc7d9f0e5874970be5)
* [6baeb7a driver/base: implement subsys_virtual_register()](https://github.com/ppajda/kernel_g3/commit/6baeb7a51b03599d34dc29a0bc421d4d0bbcb815)
* [8b40859 cpumask: implement cpumask_parse()](https://github.com/ppajda/kernel_g3/commit/8b4085926e5c7046f260b6bd5109873be76892fc)
* [7139acf workqueue: reject adjusting max_active or applying attrs to ordered workqueues](https://github.com/ppajda/kernel_g3/commit/7139acf8db6f4a747d8038773f5cc1e78059dcaa)
* [48cd8f9 workqueue: make it clear that WQ_DRAINING is an internal flag](https://github.com/ppajda/kernel_g3/commit/48cd8f96abd5db04e3e78c4a3bc2312ce70b60ee)
* [a546549 workqueue: implement apply_workqueue_attrs()](https://github.com/ppajda/kernel_g3/commit/a5465494055a7fdede9ddd71ac9df3ec1b3a6b8f)
* [e0d25e3 workqueue: perform non-reentrancy test when queueing to unbound workqueues too](https://github.com/ppajda/kernel_g3/commit/e0d25e3271ce74d8957e58e8fe4d03cdb2a58e9e)
* [2d1c726 workqueue: prepare flush_workqueue() for dynamic creation and destrucion of unbound pool_workqueues](https://github.com/ppajda/kernel_g3/commit/2d1c726e457ced87106d102b35a8c0ff0f5e9992)
* [113e740 workqueue: implement get/put_pwq()](https://github.com/ppajda/kernel_g3/commit/113e740c37ed87189a3c5da2a3ec87b118a5a8cb)
* [af40b5c workqueue: restructure __alloc_workqueue_key()](https://github.com/ppajda/kernel_g3/commit/af40b5c2d46947efe944f788bad2d1798f52e8af)
* [f58ba0e workqueue: drop WQ_RESCUER and test workqueue->rescuer for NULL instead](https://github.com/ppajda/kernel_g3/commit/f58ba0e397da4502a3eb8f953e52a44adc5cfec0)
* [d5962d9 workqueue: add pool ID to the names of unbound kworkers](https://github.com/ppajda/kernel_g3/commit/d5962d920d16d69ca51ae157ae47f1eecd5c3428)
* [c05126a workqueue: drop "std" from cpu_std_worker_pools and for_each_std_worker_pool()](https://github.com/ppajda/kernel_g3/commit/c05126a52b5094c54c0f2cf66f37b2dbc68b7447)
* [a639ea7 workqueue: remove unbound_std_worker_pools[] and related helpers](https://github.com/ppajda/kernel_g3/commit/a639ea7ec4a9ae7506e6f3b652d79e1538da94d4)
* [c66dd1a workqueue: implement attribute-based unbound worker_pool management](https://github.com/ppajda/kernel_g3/commit/c66dd1a632d6d9f4485db821444155bd86c1fbea)
* [d5647aa workqueue: introduce workqueue_attrs](https://github.com/ppajda/kernel_g3/commit/d5647aab801775f3bd8894201e9878943bc2c619)
* [98d843a workqueue: separate out init_worker_pool() from init_workqueues()](https://github.com/ppajda/kernel_g3/commit/98d843aa22da8028246347ca8a2522d8d8f3c979)
* [6278bf4 workqueue: replace POOL_MANAGING_WORKERS flag with worker_pool->manager_arb](https://github.com/ppajda/kernel_g3/commit/6278bf410339ed2c61e406bf2a676d9b41a01250)
* [69a42dd workqueue: update synchronization rules on worker_pool_idr](https://github.com/ppajda/kernel_g3/commit/69a42ddcff4bedb910f3b937d9439ebf36a4fb88)
* [9a1ee00 workqueue: update synchronization rules on workqueue->pwqs](https://github.com/ppajda/kernel_g3/commit/9a1ee004e2cf435cad79d1ad81dc0038f667f171)
* [3a82383 workqueue: replace get_pwq() with explicit per_cpu_ptr() accesses and first_pwq()](https://github.com/ppajda/kernel_g3/commit/3a823837a45376e999ec56412d89b15df4cf8599)
* [848f3fa workqueue: remove workqueue_struct->pool_wq.single](https://github.com/ppajda/kernel_g3/commit/848f3fa8cc28db7bf59ad4d0619cb64ba9a73547)
* [907c16c workqueue: consistently use int for @cpu variables](https://github.com/ppajda/kernel_g3/commit/907c16c0271b2aedfe062caa05a75d9528d641e4)
* [e0b7272 workqueue: add wokrqueue_struct->maydays list to replace mayday cpu iterators](https://github.com/ppajda/kernel_g3/commit/e0b727225849d760083ef85ee45618078c7fc3b7)
* [b181f17 workqueue: restructure pool / pool_workqueue iterations in freeze/thaw functions](https://github.com/ppajda/kernel_g3/commit/b181f17b754c4e965cd621f754fee5b716962a5d)
* [2877c9a workqueue: introduce for_each_pool()](https://github.com/ppajda/kernel_g3/commit/2877c9a7865c8433a3e3b6cc96c1d1fa1c931ce8)
* [73525d1 workqueue: replace for_each_pwq_cpu() with for_each_pwq()](https://github.com/ppajda/kernel_g3/commit/73525d10c7cf2b8e0754e6d4b442286686378a0d)
* [d4e610a workqueue: add workqueue_struct->pwqs list](https://github.com/ppajda/kernel_g3/commit/d4e610a157a1f4ab6ef34a44923770df9eeaf721)
* [82ad563 workqueue: introduce kmem_cache for pool_workqueues](https://github.com/ppajda/kernel_g3/commit/82ad5638ea777e3f01b3a022f732f3dea9bd4bf6)
* [b28c5b6 workqueue: make workqueue_lock irq-safe](https://github.com/ppajda/kernel_g3/commit/b28c5b6fc8f703095877482eacab779e4a7286e4)
* [3bb5dd8 workqueue: make sanity checks less punshing using WARN_ON[_ONCE]()s](https://github.com/ppajda/kernel_g3/commit/3bb5dd8a95eee1639f8b63eb94400faf989452a0)
* [02ef40d workqueue: fix possible pool stall bug in wq_unbind_fn()](https://github.com/ppajda/kernel_g3/commit/02ef40d005f0b7b24d2bc25070cbcdc7c3d14929)
* [601c2da workqueue: better define synchronization rule around rescuer->pool updates](https://github.com/ppajda/kernel_g3/commit/601c2da9477c0be92ff705c704e8541e4b03f013)
* [51aae3b workqueue: change argument of worker_maybe_bind_and_lock() to @pool](https://github.com/ppajda/kernel_g3/commit/51aae3b853da2c11be59789fb7f9ac2fa9e0a897)
* [d156d29 workqueue: use %current instead of worker->task in worker_maybe_bind_and_lock()](https://github.com/ppajda/kernel_g3/commit/d156d2982732bdb3fcf53fcef13d0ee8ddba02b8)
* [f132392 workqueue: un-GPL function delayed_work_timer_fn()](https://github.com/ppajda/kernel_g3/commit/f132392cb1c0ffd607367b2847efb7d0b9a83d20)
* [0ab5430 workqueue: implement current_is_async()](https://github.com/ppajda/kernel_g3/commit/0ab5430568d08a41ff1a7308a0b0012a9fc8ada0)
* [85703a0 workqueue: rename cpu_workqueue to pool_workqueue](https://github.com/ppajda/kernel_g3/commit/85703a09e0c74d48a24a038ab8e49de92b9be057)
* [2e1a601 workqueue: reimplement is_chained_work() using current_wq_worker()](https://github.com/ppajda/kernel_g3/commit/2e1a60120c0168be43084937d55e30cd0c78c203)
* [4d5b7fe workqueue: fix is_chained_work() regression](https://github.com/ppajda/kernel_g3/commit/4d5b7fe870ea5ece8ae8859f2d771a35ad938905)
* [448a05a workqueue: pick cwq instead of pool in __queue_work()](https://github.com/ppajda/kernel_g3/commit/448a05a4ea21a4eef36af01e1ad96e8ea6411685)
* [b817b3b workqueue: make get_work_pool_id() cheaper](https://github.com/ppajda/kernel_g3/commit/b817b3bfd46d493a3e56eb169d9d62cbe3f328ec)
* [c201125 workqueue: move nr_running into worker_pool](https://github.com/ppajda/kernel_g3/commit/c2011251ae5b7d717f70cbd8bb45b8a1ca1bfdde)
* [d93472e workqueue: cosmetic update in try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/d93472e6bd2f4f1d91ac9026d57be4d789575a9a)
* [a975ff1 workqueue: simplify is-work-item-queued-here test](https://github.com/ppajda/kernel_g3/commit/a975ff1a9640ab6ea92eb0ce057538036656698e)
* [18ee76c workqueue: make work->data point to pool after try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/18ee76cac0c331e9222abd20a37324d819bd54b7)
* [b2f8d56 workqueue: add delayed_work->wq to simplify reentrancy handling](https://github.com/ppajda/kernel_g3/commit/b2f8d560395a6055cfed3437c7d101e32a499a68)
* [97a47fd workqueue: make work_busy() test WORK_STRUCT_PENDING first](https://github.com/ppajda/kernel_g3/commit/97a47fdc5230563fcec2d6f8e2f61184e48df122)
* [3d8217a workqueue: replace WORK_CPU_NONE/LAST with WORK_CPU_END](https://github.com/ppajda/kernel_g3/commit/3d8217a5ff779d6e5acb93f3ea2ef18b0f95af65)
* [bca565b workqueue: post global_cwq removal cleanups](https://github.com/ppajda/kernel_g3/commit/bca565b4bbfa3f422758d1bb5224a085978f9801)
* [f553376 workqueue: rename nr_running variables](https://github.com/ppajda/kernel_g3/commit/f5533766d05cbea323dbab6e9b030c71ab0961dc)
* [94572cbf workqueue: remove global_cwq](https://github.com/ppajda/kernel_g3/commit/94572cbffb1ab7eaf34bf48468897d384ceb83ab)
* [5f1d1b6 workqueue: remove worker_pool->gcwq](https://github.com/ppajda/kernel_g3/commit/5f1d1b69d1b68ea02a2cf89baf074ba36c765acb)
* [b1bbf1c workqueue: replace for_each_worker_pool() with for_each_std_worker_pool()](https://github.com/ppajda/kernel_g3/commit/b1bbf1c41a84fb5c1439a95f2ebffc8c81fdefb5)
* [258708b workqueue: make freezing/thawing per-pool](https://github.com/ppajda/kernel_g3/commit/258708bf75a6ac016c1c3d7c2a81e66eb312d579)
* [561e7d7 workqueue: make hotplug processing per-pool](https://github.com/ppajda/kernel_g3/commit/561e7d7aca9ae01820094c2d83765d5e8c77e21d)
* [2cea6c3 workqueue: move global_cwq->lock to worker_pool](https://github.com/ppajda/kernel_g3/commit/2cea6c340aced58541acb34ad0ec059a2ea086c3)
* [591d576 workqueue: move global_cwq->cpu to worker_pool](https://github.com/ppajda/kernel_g3/commit/591d576e0b67dd54a4385d45a6eddc8833145e2c)
* [9fe6323 workqueue: move busy_hash from global_cwq to worker_pool](https://github.com/ppajda/kernel_g3/commit/9fe63236d1cc78d05717db9f3181d12c29ebca6a)
* [a798d8a workqueue: record pool ID instead of CPU in work->data when off-queue](https://github.com/ppajda/kernel_g3/commit/a798d8a72314ebd1d649632920609487ad0fdbe0)
* [61e1207 workqueue: add worker_pool->id](https://github.com/ppajda/kernel_g3/commit/61e120725b79efe085d555a542f8809faeb9e30a)
* [101f0fd workqueue: make GCWQ_FREEZING a pool flag](https://github.com/ppajda/kernel_g3/commit/101f0fd2da99c88ae2faf11deb24c780add9ea3c)
* [c0ff875 workqueue: make GCWQ_DISASSOCIATED a pool flag](https://github.com/ppajda/kernel_g3/commit/c0ff875f40eaad73924b9acdef9b4b9f96b1b717)
* [0223687 workqueue: use std_ prefix for the standard per-cpu pools](https://github.com/ppajda/kernel_g3/commit/02236870ee742b4d7b3e4fc7a2c01dfb233d0c96)
* [e107aa4 workqueue: move struct worker definition to workqueue_internal.h](https://github.com/ppajda/kernel_g3/commit/e107aa46614398807c2a9d7be8c7b5bd0724471b)
* [0eed48a workqueue: rename kernel/workqueue_sched.h to kernel/workqueue_internal.h](https://github.com/ppajda/kernel_g3/commit/0eed48aab112768c1ebb9c18c03e506f4fb56c76)
* [aae2420 workqueue: set PF_WQ_WORKER on rescuers](https://github.com/ppajda/kernel_g3/commit/aae2420fc9a21075beb780c542ee29214dff2568)
* [bd83622 workqueue: fix find_worker_executing_work() brekage from hashtable conversion](https://github.com/ppajda/kernel_g3/commit/bd83622851d9e0cef838c25d7ceae0d9932680ec)
* [6d00890 workqueue: consider work function when searching for busy work items](https://github.com/ppajda/kernel_g3/commit/6d00890cc050972bd331e231ee68b7d1836ebe8c)
* [7d56580 workqueue: use new hashtable implementation](https://github.com/ppajda/kernel_g3/commit/7d56580b4f10809ce0279c4c79e287a417f8c123)
* [f04e26e workqueue: convert BUG_ON()s in __queue_delayed_work() to WARN_ON_ONCE()s](https://github.com/ppajda/kernel_g3/commit/f04e26ee550271b2e462d20f318c7d7f10413cc7)
* [a31d30b workqueue: add WARN_ON_ONCE() on CPU number to wq_worker_waking_up()](https://github.com/ppajda/kernel_g3/commit/a31d30bd14775db5a46588a715f2b5664332598b)
* [2176753 workqueue: trivial fix for return statement in work_busy()](https://github.com/ppajda/kernel_g3/commit/21767539a36428692d4486eab4726c9c7739eb24)
* [d0421a7 workqueue: mod_delayed_work_on() shouldn't queue timer on 0 delay](https://github.com/ppajda/kernel_g3/commit/d0421a7d034412ba10c8bbbf7a0974755c6a5935)
* [39af2ed workqueue: cancel_delayed_work() should return %false if work item is idle](https://github.com/ppajda/kernel_g3/commit/39af2ed4032a582265cd6f8d3f367a15e79359a7)
* [dae6fa8 workqueue: remove spurious WARN_ON_ONCE(in_irq()) from try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/dae6fa85689688e48bf4464615605de06549c5eb)
* [fec7ecc workqueue: use cwq_set_max_active() helper for workqueue_set_max_active()](https://github.com/ppajda/kernel_g3/commit/fec7ecc5caf2485e505df8ae08eaf5786a6a3f12)
* [8475ec1 workqueue: introduce cwq_set_max_active() helper for thaw_workqueues()](https://github.com/ppajda/kernel_g3/commit/8475ec18cda37dc19152a434f993ab1f26978a94)
* [21e403d workqueue: remove @delayed from cwq_dec_nr_in_flight()](https://github.com/ppajda/kernel_g3/commit/21e403df5f5c685c335373b99da7f4d5f1026455)
* [3e85cef workqueue: fix possible stall on try_to_grab_pending() of a delayed work item](https://github.com/ppajda/kernel_g3/commit/3e85cef341a643e9410e78adbc448c2cfe1d7912)
* [ad07a5e workqueue: use hotcpu_notifier() for workqueue_cpu_down_callback()](https://github.com/ppajda/kernel_g3/commit/ad07a5edb3ede3ce7f32dd152feb2c3525d7d67c)
* [000aa05 workqueue: use __cpuinit instead of __devinit for cpu callbacks](https://github.com/ppajda/kernel_g3/commit/000aa050d8d745b7e81a37525a9fa24226cd2675)
* [82652f8 workqueue: rename manager_mutex to assoc_mutex](https://github.com/ppajda/kernel_g3/commit/82652f86e23577549f9cd54d170c0be12071a3b7)
* [9760dd5 workqueue: WORKER_REBIND is no longer necessary for idle rebinding](https://github.com/ppajda/kernel_g3/commit/9760dd56f7ecab818df247f3b3c38cc38781b149)
* [32ad293 workqueue: WORKER_REBIND is no longer necessary for busy rebinding](https://github.com/ppajda/kernel_g3/commit/32ad293f9714fac0fdd8df4ba2dfb516a9139b31)
* [19b219c workqueue: reimplement idle worker rebinding](https://github.com/ppajda/kernel_g3/commit/19b219c270c4311567199afbabe64bc476f22985)
* [e1190e5 Merge branch 'for-3.6-fixes' of git://git.kernel.org/pub/scm/linux/kernel/git/tj/wq into for-3.7](https://github.com/ppajda/kernel_g3/commit/e1190e563e5d8ee341009db95855747bd8ef7501)
* [6902cc5 workqueue: always clear WORKER_REBIND in busy_worker_rebind_fn()](https://github.com/ppajda/kernel_g3/commit/6902cc53457cb625623c5705a24b0fbeeb2713ac)
* [9d9bfdb workqueue: fix possible idle worker depletion across CPU hotplug](https://github.com/ppajda/kernel_g3/commit/9d9bfdbf177deb19d15ee37e7e23fb0f63eabb99)
* [9a624e7 workqueue: restore POOL_MANAGING_WORKERS](https://github.com/ppajda/kernel_g3/commit/9a624e7f2a5f9bb166d1271ad22585c5223fcc0d)
* [cd9088b workqueue: fix possible deadlock in idle worker rebinding](https://github.com/ppajda/kernel_g3/commit/cd9088b17e0859abf2279fd228d0ff2f2c17516a)
* [faf7017 workqueue: move WORKER_REBIND clearing in rebind_workers() to the end of the function](https://github.com/ppajda/kernel_g3/commit/faf7017ef8627c9a584b64d8a8678ca44a3eab7c)
* [47fd043 workqueue: UNBOUND -> REBIND morphing in rebind_workers() should be atomic](https://github.com/ppajda/kernel_g3/commit/47fd0433e8509bb73e4235b4c4718b5cb62dfc40)
* [96aadf4 rename deprecated __cancel_delayed_work to cancel_delayed_work](https://github.com/ppajda/kernel_g3/commit/96aadf44cfd3808ed7edf87e478d133113584559)
* [20894d6 workqueue: introduce WORK_OFFQ_CPU_NONE](https://github.com/ppajda/kernel_g3/commit/20894d679c223311e7d37650bc871fab5142d333)
* [41c7b25 workqueue: unexport work_cpu()](https://github.com/ppajda/kernel_g3/commit/41c7b2588be2fc82bee336d06280ac5b50c10bd4)
* [1f0c530 workqueue: deprecate __cancel_delayed_work()](https://github.com/ppajda/kernel_g3/commit/1f0c530483b9453f1ca76abb649ef9a94fec98d2)
* [7307f7e workqueue: reimplement cancel_delayed_work() using try_to_grab_pending()](https://github.com/ppajda/kernel_g3/commit/7307f7e8e31655cdeea2b75ebfab5598cb4ceb7a)
* [da9b1b2 workqueue: use irqsafe timer for delayed_work](https://github.com/ppajda/kernel_g3/commit/da9b1b2ff977ee28a2d85cbf204038018b16db57)
* [8163899 timer: Implement TIMER_IRQSAFE](https://github.com/ppajda/kernel_g3/commit/816389994250c416bf7ea3580a0b88b20919aa23)
* [5a516d6 timer: Clean up timer initializers](https://github.com/ppajda/kernel_g3/commit/5a516d651777a6bb882f542ecd1639022f14775a)
* [3df95b0 timer: Relocate declarations of init_timer_on_stack_key()](https://github.com/ppajda/kernel_g3/commit/3df95b0a2af371269db6e7c4874a5c49f05015d3)
* [62890bc timer: Generalize timer->base flags handling](https://github.com/ppajda/kernel_g3/commit/62890bc50ca08b13de857bf61a4b2617c67f105b)
* [b78bd38 timers: Improve get_next_timer_interrupt()](https://github.com/ppajda/kernel_g3/commit/b78bd38b0f621eb8ba718ff44def8f0cabc3bbf4)
* [e20c64a timers: Add accounting of non deferrable timers](https://github.com/ppajda/kernel_g3/commit/e20c64aea6d839dc4460fe3fc6d9c63a27cf6a2e)
* [92f26b9 timers: Consolidate base->next_timer update](https://github.com/ppajda/kernel_g3/commit/92f26b9fb18fbcbf21f0c8850ce5d9c2a0e9abc7)
* [72a85c5 timers: Create detach_if_pending() and use it](https://github.com/ppajda/kernel_g3/commit/72a85c5fa1c1eb9d29866942a920d9676a3ff716)
* [f859472 lockdep: fix oops in processing workqueue](https://github.com/ppajda/kernel_g3/commit/f859472979b1165f2e1f9f03d8d82fe26c3a9062)
* [a6c0349 workqueue: clean up delayed_work initializers and add missing one](https://github.com/ppajda/kernel_g3/commit/a6c034977662d7c7b4608f7397016d667ebcb4d8)
* [015d757 workqueue: make deferrable delayed_work initializer names consistent](https://github.com/ppajda/kernel_g3/commit/015d757ea6ec12d78ef13a5c523c9ea63c376fc9)
* [f39fe3f workqueue: deprecate system_nrt[_freezable]_wq](https://github.com/ppajda/kernel_g3/commit/f39fe3f25b1e34d0768adfdc027c741c21d75802)
* [0a83131 workqueue: deprecate flush[_delayed]_work_sync()](https://github.com/ppajda/kernel_g3/commit/0a831314daa0eee8feddaae872262e1a75691288)
* [6ab773a sched/core: Fix a race between try_to_wake_up() and a woken up task](https://github.com/ppajda/kernel_g3/commit/6ab773a959334bb94cdab76d68d20f525739a607)

***

12-16-2017
====================

* [7a9af14 defconfigs: fix derp](https://github.com/ppajda/kernel_g3/commit/7a9af14df5b7289cc76fad404fcf3582ab37c957)
* [de7dccc fixes some errors](https://github.com/ppajda/kernel_g3/commit/de7dccc7b2585ce4ceb8cebbdf22989789b98613)
* [6a8373f dts: msm8974.dtsi: tune thermal](https://github.com/ppajda/kernel_g3/commit/6a8373f0418581009c893e9f47172286ddfba199)
* [6a44e9f replace deprecated create_singlethread_workqueue with schedule_work](https://github.com/ppajda/kernel_g3/commit/6a44e9fc41e316b0689f78ea77ddc5ae65f0cfbc)
* [6662a71 msm: kgsl: Remove io_fraction as it is no longer used](https://github.com/ppajda/kernel_g3/commit/6662a71f92c9b750e4bb33e5c3612a76f8135985)
* [1e25792 msm8974pro.dtsi: change initial power level](https://github.com/ppajda/kernel_g3/commit/1e25792768c25a3d90d8dbdaa0c7e0ffbf03c369)

***

12-13-2017
====================

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
