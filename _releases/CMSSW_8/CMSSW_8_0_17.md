---
layout: post
rel_link:  "8_0_17"
title:  "CMSSW_8_0_17"
date:   2016-08-10 08:35:30
categories: cmssw
relmajor: 8
relminor: 0
relsubminor: 17
---

# CMSSW_8_0_17
#### Changes since CMSSW_8_0_16:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_0_16...CMSSW_8_0_17)



1. [15398](http://github.com/cms-sw/cmssw/pull/15398){:target="_blank"}  from **@degano**: change das_client.py to das_client in cmsDriver `comparison`  `operations`  `pdmv`  created: 2016-08-09 14:19:12 merged: 2016-08-09 16:46:34

2. [15396](http://github.com/cms-sw/cmssw/pull/15396){:target="_blank"}  from **@mmusich**: 80x: fix SiPixelAli PCL update logic `alca`  `comparison`  created: 2016-08-09 11:20:00 merged: 2016-08-09 16:00:08

3. [15394](http://github.com/cms-sw/cmssw/pull/15394){:target="_blank"}  from **@cms-btv-pog**: Subjet TagInfo updates (80X) `analysis`  `comparison`  `reconstruction`  created: 2016-08-08 21:27:24 merged: 2016-08-10 08:00:50

4. [15391](http://github.com/cms-sw/cmssw/pull/15391){:target="_blank"}  from **@dan131riley**: protect RawTask::_process from processing bad HcalHTRData, backport to 80x `comparison`  `dqm`  created: 2016-08-08 14:00:09 merged: 2016-08-09 15:55:11

5. [15373](http://github.com/cms-sw/cmssw/pull/15373){:target="_blank"}  from **@mmusich**: Fix failure due to AlCaEcalTrg missing triggerbit in 80X MC relvals `alca`  `comparison`  created: 2016-08-05 11:09:20 merged: 2016-08-10 07:49:58

6. [15365](http://github.com/cms-sw/cmssw/pull/15365){:target="_blank"}  from **@cms-sw**: Revert "Updating Trigger Path and Fixing for Empty Histograms for single lept" `comparison`  `dqm`  created: 2016-08-04 06:58:55 merged: 2016-08-04 06:59:35

7. [15349](http://github.com/cms-sw/cmssw/pull/15349){:target="_blank"}  from **@jalimena**: Update muon timing analyzer 80x `comparison`  `reconstruction`  created: 2016-08-02 12:07:09 merged: 2016-08-09 15:58:40

8. [15344](http://github.com/cms-sw/cmssw/pull/15344){:target="_blank"}  from **@fioriNTU**: IsolatedBunchesTrackingMonitor `comparison`  `dqm`  created: 2016-08-01 15:58:23 merged: 2016-08-10 07:50:48

9. [15342](http://github.com/cms-sw/cmssw/pull/15342){:target="_blank"}  from **@boudoul**: update of Strip hit efficiency code - 80X version `alca`  `comparison`  created: 2016-08-01 15:31:40 merged: 2016-08-09 16:01:36

10. [15329](http://github.com/cms-sw/cmssw/pull/15329){:target="_blank"}  from **@barvic**: 80X - Added CSC Unpacker check for FED/DDU<->chamber mapping inconsistencies `reconstruction`  created: 2016-07-30 21:56:39 merged: 2016-08-08 20:30:03

11. [15323](http://github.com/cms-sw/cmssw/pull/15323){:target="_blank"}  from **@fabozzi**: New memory option in runTheMatrix (backport from #15149) `pdmv`  created: 2016-07-28 17:12:01 merged: 2016-08-08 20:29:14

12. [15317](http://github.com/cms-sw/cmssw/pull/15317){:target="_blank"}  from **@CTPPS**: CTPPS: directory rename Totem -> CTPPS (back-port of #15311) `dqm`  `geometry`  `operations`  `reconstruction`  created: 2016-07-28 13:28:24 merged: 2016-08-09 15:56:32

13. [15308](http://github.com/cms-sw/cmssw/pull/15308){:target="_blank"}  from **@jasperlauwers**: 80X Adding Mu12_Ele23 path `comparison`  `dqm`  created: 2016-07-27 16:33:03 merged: 2016-08-08 20:29:27

14. [15299](http://github.com/cms-sw/cmssw/pull/15299){:target="_blank"}  from **@jaylawhorn**: fix SUSY Razor HLT DQM module `dqm`  created: 2016-07-27 09:54:15 merged: 2016-08-10 07:51:29

15. [15298](http://github.com/cms-sw/cmssw/pull/15298){:target="_blank"}  from **@diguida**: Use the latest Express GT as a fallback, and fix http proxy setting in curl for Tier0 DataService query for Event Display applications. `comparison`  `dqm`  created: 2016-07-27 09:48:52 merged: 2016-08-10 07:51:44

16. [15292](http://github.com/cms-sw/cmssw/pull/15292){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca54 Backport HcalIsolatedBunch from 8_1_X `alca`  `dqm`  `operations`  created: 2016-07-26 16:37:50 merged: 2016-07-29 14:13:45

17. [15282](http://github.com/cms-sw/cmssw/pull/15282){:target="_blank"}  from **@HeinerTholen**: fix: eval_auto_bounds returns good value for pt==pt_low `db`  created: 2016-07-26 11:27:41 merged: 2016-08-10 07:51:59

18. [15236](http://github.com/cms-sw/cmssw/pull/15236){:target="_blank"}  from **@gouskos**: dqm plot, pixel endcap roc occupancy in 80x `comparison`  `dqm`  created: 2016-07-19 20:05:22 merged: 2016-08-09 15:56:12

#### CMSDIST Changes between Tags REL/CMSSW_8_0_16/slc6_amd64_gcc530 and REL/CMSSW_8_0_17/slc6_amd64_gcc530:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_0_16/slc6_amd64_gcc530...REL/CMSSW_8_0_17/slc6_amd64_gcc530)



1. [2432](http://github.com/cms-sw/cmsdist/pull/2432){:target="_blank"}  from **@iahmad-khan**: updates das client to 2.17.04 created: 2016-08-02 15:33:32 merged: 2016-08-09 09:42:00
