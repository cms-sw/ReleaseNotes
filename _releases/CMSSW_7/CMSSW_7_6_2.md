---
layout: post
rel_link:  "7_6_2"
title:  "CMSSW_7_6_2"
date:   2015-12-04 13:50:53
categories: cmssw
relmajor: 7
relminor: 6
relsubminor: 2
---

# CMSSW_7_6_2
#### Changes since CMSSW_7_6_1:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_6_1...CMSSW_7_6_2)



1. [12662](http://github.com/cms-sw/cmssw/pull/12662){:target="_blank"}  from **@Dr15Jones**: Do not call TTree cache after an exception happens `comparison`  `core`  created: 2015-12-03 21:03:11 merged: 2015-12-04 07:42:25

2. [12631](http://github.com/cms-sw/cmssw/pull/12631){:target="_blank"}  from **@cvuosalo**: Restore CSCHaloData to AOD, which was inadvertently deleted by PR 11068 `reconstruction`  created: 2015-12-02 05:32:34 merged: 2015-12-03 09:21:40

3. [12630](http://github.com/cms-sw/cmssw/pull/12630){:target="_blank"}  from **@deguio**: make miniAODDQM and miniAODValidation able to run together when starting from AODSIM `analysis`  `dqm`  `operations`  created: 2015-12-01 22:19:40 merged: 2015-12-03 09:05:18

4. [12612](http://github.com/cms-sw/cmssw/pull/12612){:target="_blank"}  from **@slava77**: PackedCandidates.. comment out parts of unit test that are not expected to work given that data are packed upon creation with precision loss (same as #12430) `analysis`  `reconstruction`  created: 2015-11-30 19:35:34 merged: 2015-12-01 00:33:48

5. [12593](http://github.com/cms-sw/cmssw/pull/12593){:target="_blank"}  from **@slava77**: Fail read calls after exception. (same as #12590) `core`  created: 2015-11-30 03:55:54 merged: 2015-11-30 16:23:09

6. [12588](http://github.com/cms-sw/cmssw/pull/12588){:target="_blank"}  from **@makortel**: Fix PackedCandidate vertex to post-packed value (76X) `analysis`  `reconstruction`  created: 2015-11-28 20:18:20 merged: 2015-12-04 08:45:38

7. [12586](http://github.com/cms-sw/cmssw/pull/12586){:target="_blank"}  from **@cms-tau-pog**: 76x re mini aod `analysis`  `reconstruction`  created: 2015-11-27 14:29:44 merged: 2015-12-03 09:07:55

8. [12583](http://github.com/cms-sw/cmssw/pull/12583){:target="_blank"}  from **@makortel**: Fixes to PackedCandidate (76X) `analysis`  `reconstruction`  created: 2015-11-27 08:45:04 merged: 2015-12-03 09:08:13

9. [12578](http://github.com/cms-sw/cmssw/pull/12578){:target="_blank"}  from **@fioriNTU**: adding file needed for HI Qtest on Tracking `dqm`  created: 2015-11-26 13:33:50 merged: 2015-11-30 02:09:52

10. [12557](http://github.com/cms-sw/cmssw/pull/12557){:target="_blank"}  from **@kencall**: Changes the energy threshold on the EcalDeadCellTriggerPrimitiveFilter `analysis`  `reconstruction`  created: 2015-11-24 23:23:05 merged: 2015-12-03 09:08:54

11. [12515](http://github.com/cms-sw/cmssw/pull/12515){:target="_blank"}  from **@clelange**: filters for charged hadrons and muons that have bad track quality cau `analysis`  `reconstruction`  created: 2015-11-20 12:23:01 merged: 2015-12-03 09:14:08

12. [12445](http://github.com/cms-sw/cmssw/pull/12445){:target="_blank"}  from **@cms-btv-pog**: Updated version of the boosted double SV tagger (76X) `analysis`  `reconstruction`  created: 2015-11-17 00:01:32 merged: 2015-12-03 09:06:05

13. [12288](http://github.com/cms-sw/cmssw/pull/12288){:target="_blank"}  from **@mverzett**: add ctagging discriminators in the default PAT content, small improvement to test script `analysis`  `reconstruction`  created: 2015-11-06 15:52:11 merged: 2015-12-03 09:07:14

14. [12249](http://github.com/cms-sw/cmssw/pull/12249){:target="_blank"}  from **@vmariani**: Adding Dstar filter for enriched MC production request `generators`  created: 2015-11-03 15:49:27 merged: 2015-12-03 09:05:56

15. [12224](http://github.com/cms-sw/cmssw/pull/12224){:target="_blank"}  from **@heppye**: add BPH fragmentation file for trigger study `generators`  created: 2015-11-01 19:06:37 merged: 2015-12-03 09:06:09

#### CMSDIST Changes between Tags REL/CMSSW_7_6_1/slc6_amd64_gcc493 and REL/CMSSW_7_6_2/slc6_amd64_gcc493:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_6_1/slc6_amd64_gcc493...REL/CMSSW_7_6_2/slc6_amd64_gcc493)



1. [1979](http://github.com/cms-sw/cmsdist/pull/1979){:target="_blank"}  from **@cms-sw**: Revert "Upgrade Frontier client to version 2.8.14 and pacparser to 1.3.5." created: 2015-11-22 08:57:53 merged: 2015-11-22 08:57:59

2. [1961](http://github.com/cms-sw/cmsdist/pull/1961){:target="_blank"}  from **@iahmad-khan**: update branch and tag in  root.spec created: 2015-11-13 12:33:20 merged: 2015-11-14 13:08:37
