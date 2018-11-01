---
layout: post
rel_link:  "10_3_1"
title:  "CMSSW_10_3_1"
date:   2018-11-01 09:39:25
categories: cmssw
relmajor: 10
relminor: 3
relsubminor: 1
---

# CMSSW_10_3_1
#### Changes since CMSSW_10_3_0_patch1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_10_3_0_patch1...CMSSW_10_3_1)



1. [25065](http://github.com/cms-sw/cmssw/pull/25065){:target="_blank"}  from **@apana**: Update HLT and GT packer for new HI L1 objects (Backport to 10_3_X) `hlt`  `l1`  created: 2018-10-30 23:49:12 merged: 2018-11-01 08:53:50



2. [25010](http://github.com/cms-sw/cmssw/pull/25010){:target="_blank"}  from **@bundocka**: L1T CaloL2 O2O Fixes for HI **10_3_X BACKPORT** `l1`  created: 2018-10-26 01:21:08 merged: 2018-10-31 08:53:13



3. [25006](http://github.com/cms-sw/cmssw/pull/25006){:target="_blank"}  from **@zhenhu**: Backport to 10.3.X: add 2 production-like workflows for HI 2018 `pdmv`  `upgrade`  created: 2018-10-25 21:15:22 merged: 2018-10-29 14:36:28



4. [24987](http://github.com/cms-sw/cmssw/pull/24987){:target="_blank"}  from **@apana**: Update uGT unpacker to pick up new HI centrality values (Backport) `l1`  created: 2018-10-24 17:45:01 merged: 2018-10-30 17:18:52



5. [24979](http://github.com/cms-sw/cmssw/pull/24979){:target="_blank"}  from **@mdhildreth**: fix memory leak `l1`  `simulation`  created: 2018-10-23 15:59:48 merged: 2018-10-28 20:55:21



6. [24976](http://github.com/cms-sw/cmssw/pull/24976){:target="_blank"}  from **@mmusich**: [10.3.X] add missing eventSetupPathsKey swap for HI 2018 `alca`  created: 2018-10-23 11:48:09 merged: 2018-10-30 17:18:17



7. [24970](http://github.com/cms-sw/cmssw/pull/24970){:target="_blank"}  from **@mmusich**: [10.3.X] Tracker Alignment: parallelize PV Validation `alca`  created: 2018-10-23 07:33:11 merged: 2018-10-28 20:54:52



8. [24962](http://github.com/cms-sw/cmssw/pull/24962){:target="_blank"}  from **@pieterdavid**: [10_3_X] Fix APV shot cleaner for 10bit `reconstruction`  created: 2018-10-22 16:01:36 merged: 2018-10-26 19:17:20



9. [24950](http://github.com/cms-sw/cmssw/pull/24950){:target="_blank"}  from **@muhammadansariqbal**: Tracker Alignment - Fix to conddb function in validation and migration to common EOS storage `alca`  created: 2018-10-19 18:22:39 merged: 2018-10-28 20:54:34



10. [24939](http://github.com/cms-sw/cmssw/pull/24939){:target="_blank"}  from **@fwyzard**: Skip tests if no CUDA devices are present (10.3.x) `reconstruction`  created: 2018-10-19 11:51:03 merged: 2018-10-28 20:51:47



11. [24928](http://github.com/cms-sw/cmssw/pull/24928){:target="_blank"}  from **@mandrenguyen**: Central skims for PbPb 2018 (103X backport) `operations`  `pdmv`  created: 2018-10-18 14:21:09 merged: 2018-10-30 21:28:37



12. [24926](http://github.com/cms-sw/cmssw/pull/24926){:target="_blank"}  from **@mmusich**: [10.3.X] Fix testProduceSystematicMisalignment and add unit tests `alca`  created: 2018-10-18 12:03:11 merged: 2018-10-26 19:16:17



13. [24915](http://github.com/cms-sw/cmssw/pull/24915){:target="_blank"}  from **@lpernie**: [10.3.X][Change GT] Update HI MC ECAL GT + 2019 GT Geom. fix `alca`  created: 2018-10-17 17:04:49 merged: 2018-10-28 20:50:57



14. [24912](http://github.com/cms-sw/cmssw/pull/24912){:target="_blank"}  from **@nwickram**: Backport to 103X: add fastSim2017 PU and pmx wfs `pdmv`  `upgrade`  created: 2018-10-17 15:15:55 merged: 2018-10-29 16:26:55



15. [24907](http://github.com/cms-sw/cmssw/pull/24907){:target="_blank"}  from **@slezki**: Backport of the PR #24613 and #24902: RPC digi merger and test new readouts `dqm`  `l1`  `operations`  `reconstruction`  created: 2018-10-17 13:56:03 merged: 2018-10-29 12:48:20



16. [24890](http://github.com/cms-sw/cmssw/pull/24890){:target="_blank"}  from **@guitargeek**: [10_3_X] Fixed copy-paste typo in Spring15 photon MVA weight file names `reconstruction`  created: 2018-10-16 13:22:27 merged: 2018-10-26 19:15:21



17. [24889](http://github.com/cms-sw/cmssw/pull/24889){:target="_blank"}  from **@YeonjuGo**: Centrality reco modification for 2018 heavy ion run  `operations`  `reconstruction`  created: 2018-10-16 11:32:24 merged: 2018-10-29 16:17:51



18. [24888](http://github.com/cms-sw/cmssw/pull/24888){:target="_blank"}  from **@sikler**: Fixes for online beamspot, heavy-ion run in 2018 (10_3_X) `dqm`  created: 2018-10-16 11:26:39 merged: 2018-11-01 09:32:41



#### CMSDIST Changes between Tags REL/CMSSW_10_3_0_patch1/slc6_amd64_gcc700 and REL/CMSSW_10_3_1/slc6_amd64_gcc700:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_10_3_0_patch1/slc6_amd64_gcc700...REL/CMSSW_10_3_1/slc6_amd64_gcc700)


