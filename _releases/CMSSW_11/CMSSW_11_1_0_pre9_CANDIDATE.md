---
layout: post
rel_link:  "11_1_0_pre9_CANDIDATE"
title:  "CMSSW_11_1_0_pre9_CANDIDATE"
date:   2020-06-03 19:10:22
categories: cmssw
relmajor: 11
relminor: 1
relsubminor: 0
relpre: _pre9
---

# CMSSW_11_1_0_pre9_CANDIDATE
#### Changes since CMSSW_11_1_0_pre8:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_11_1_0_pre8...CMSSW_11_1_0_pre9_CANDIDATE)



1. [30078](http://github.com/cms-sw/cmssw/pull/30078){:target="_blank"}  from **@mmusich**: 11.1.X  [Tracker Alignment] All-in-one tool support of multiple tags in user-inputed sqlite file `alca`  created: 2020-06-02 14:01:53 merged: 2020-06-03 19:07:49



2. [30065](http://github.com/cms-sw/cmssw/pull/30065){:target="_blank"}  from **@mbluj**: Fix bug affecting boosted tau isolation (11_1_X) `reconstruction`  created: 2020-06-01 11:26:32 merged: 2020-06-03 19:02:06



3. [30062](http://github.com/cms-sw/cmssw/pull/30062){:target="_blank"}  from **@cms-sw**: Davix unit test fix: use google instead of cern.ch `core`  created: 2020-05-31 08:25:45 merged: 2020-06-01 07:06:43



4. [30056](http://github.com/cms-sw/cmssw/pull/30056){:target="_blank"}  from **@cms-tsg-storm**: Migration of HLT menus to 11_1_0_pre8 template plus updates (11_1_X) `hlt`  created: 2020-05-30 05:46:57 merged: 2020-05-31 18:21:45



5. [30040](http://github.com/cms-sw/cmssw/pull/30040){:target="_blank"}  from **@cms-L1TK**: Backport of PR #29527 (L1 tracking) `l1`  created: 2020-05-29 10:00:45 merged: 2020-06-02 09:14:41



6. [30028](http://github.com/cms-sw/cmssw/pull/30028){:target="_blank"}  from **@cvuosalo**: Fix DetectorDescription Parser unit test -- backport of #29947 `geometry`  created: 2020-05-28 17:19:25 merged: 2020-05-29 08:05:45



7. [30014](http://github.com/cms-sw/cmssw/pull/30014){:target="_blank"}  from **@mmusich**: [11.1.X] Add CDC Tracks to TkAlCosmics0T ALCARECO `alca`  `dqm`  `operations`  created: 2020-05-28 13:23:23 merged: 2020-06-01 13:53:24



8. [30009](http://github.com/cms-sw/cmssw/pull/30009){:target="_blank"}  from **@cms-tau-pog**: Restructured code of againstElectronDeadECAL tauID (11_1_X) `analysis`  `reconstruction`  created: 2020-05-28 09:43:49 merged: 2020-05-29 14:50:45



9. [30002](http://github.com/cms-sw/cmssw/pull/30002){:target="_blank"}  from **@cms-patatrack**: Do not apply the "const" modifier to the return type (11.1.x) `alca`  `db`  created: 2020-05-27 14:40:09 merged: 2020-06-01 13:42:32



10. [29999](http://github.com/cms-sw/cmssw/pull/29999){:target="_blank"}  from **@cms-tsg-storm**: Fixes in PSetBlobProducer functionality for use in HLT (11_1_X) `core`  `daq`  `reconstruction`  created: 2020-05-27 11:17:22 merged: 2020-05-28 17:10:27



11. [29986](http://github.com/cms-sw/cmssw/pull/29986){:target="_blank"}  from **@cms-tsg-storm**: HLT customisation update (111X) `hlt`  created: 2020-05-26 15:17:37 merged: 2020-05-27 08:21:37



12. [29980](http://github.com/cms-sw/cmssw/pull/29980){:target="_blank"}  from **@mmusich**: [11.1.X]  Fix several bugs introduced in the Pixel PI `db`  created: 2020-05-25 17:04:38 merged: 2020-05-28 08:45:25



13. [29978](http://github.com/cms-sw/cmssw/pull/29978){:target="_blank"}  from **@cms-tau-pog**: bug fix to runTauIdMVA.py tool (11_1_X) `analysis`  `reconstruction`  `xpog`  created: 2020-05-25 14:36:32 merged: 2020-06-03 18:58:07



14. [29963](http://github.com/cms-sw/cmssw/pull/29963){:target="_blank"}  from **@bsunanda**: Run3-ft25 Fix overlap for run3 geometry - backport #29953 `geometry`  `upgrade`  created: 2020-05-23 14:25:33 merged: 2020-05-26 16:49:15



15. [29959](http://github.com/cms-sw/cmssw/pull/29959){:target="_blank"}  from **@mmusich**: [11.1.X] Applied gain calibration scheme update at HLT as well `hlt`  created: 2020-05-22 19:10:06 merged: 2020-05-25 07:26:17



#### CMSDIST Changes between Tags REL/CMSSW_11_1_0_pre8/slc7_amd64_gcc820 and REL/CMSSW_11_1_0_pre9_CANDIDATE/slc7_amd64_gcc820:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_11_1_0_pre8/slc7_amd64_gcc820...REL/CMSSW_11_1_0_pre9_CANDIDATE/slc7_amd64_gcc820)



1. [5860](http://github.com/cms-sw/cmsdist/pull/5860){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2020-05-25 21:32:03 merged: 2020-05-26 11:43:43

2. [5853](http://github.com/cms-sw/cmsdist/pull/5853){:target="_blank"}  from **@fwyzard**: Extend jmalloc to monitor the peak memory usage of each thread (11.1.x) created: 2020-05-24 08:27:38 merged: 2020-06-01 08:08:25

3. [5850](http://github.com/cms-sw/cmsdist/pull/5850){:target="_blank"}  from **@fwyzard**: Fix CUDA compilation flags (11.1.x) created: 2020-05-22 21:35:45 merged: 2020-05-25 07:40:37

4. [5847](http://github.com/cms-sw/cmsdist/pull/5847){:target="_blank"}  from **@cms-sw**: [crab] fix finding latest crab version logic created: 2020-05-22 12:35:57 merged: 2020-05-22 14:17:41

5. [5747](http://github.com/cms-sw/cmsdist/pull/5747){:target="_blank"}  from **@mrodozov**: [Sonic] Add OpenCV external created: 2020-04-15 15:47:44 merged: 2020-05-22 18:46:24

6. [5744](http://github.com/cms-sw/cmsdist/pull/5744){:target="_blank"}  from **@cms-sw**: [Sonic] Add grpc recipe created: 2020-04-14 16:13:37 merged: 2020-05-22 18:42:07
