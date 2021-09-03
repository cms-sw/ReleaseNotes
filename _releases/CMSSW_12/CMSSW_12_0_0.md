---
layout: post
rel_link:  "12_0_0"
title:  "CMSSW_12_0_0"
date:   2021-09-02 08:58:28
categories: cmssw
relmajor: 12
relminor: 0
relsubminor: 0
---

# CMSSW_12_0_0
#### Changes since CMSSW_12_0_0_pre6:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_0_0_pre6...CMSSW_12_0_0)



1. [35087](http://github.com/cms-sw/cmssw/pull/35087){:target="_blank"}  from **@Sam-Harper**: Adding protections to PATTriggerProducer when the path has zero filters: 12_0 `reconstruction` created: 2021-08-31 09:15:45 merged: 2021-09-01 19:20:55

2. [35076](http://github.com/cms-sw/cmssw/pull/35076){:target="_blank"}  from **@colizz**: [12_0_X] Better handling of timeout in FWCore/SharedMemory `core` created: 2021-08-30 16:36:30 merged: 2021-08-31 00:23:31

3. [35075](http://github.com/cms-sw/cmssw/pull/35075){:target="_blank"}  from **@colizz**: [12_0_X] Backport concurrent GEN utilities `generators` `pdmv` `upgrade` created: 2021-08-30 16:19:12 merged: 2021-09-01 08:24:37

4. [35025](http://github.com/cms-sw/cmssw/pull/35025){:target="_blank"}  from **@TomasKello**: [12_0_X]Fix on compilation issues with DMR, GC and MTS validation scripts.  `alca` created: 2021-08-26 09:06:07 merged: 2021-08-29 01:40:13

5. [35009](http://github.com/cms-sw/cmssw/pull/35009){:target="_blank"}  from **@missirol**: [12_0_X] Fixing some edge cases in HLT-Patatrack customisations `hlt` created: 2021-08-25 13:16:38 merged: 2021-08-26 08:20:12

6. [35007](http://github.com/cms-sw/cmssw/pull/35007){:target="_blank"}  from **@mteroerd**: Validation plots for APE and bug fixes: Backport of #34828 `alca` created: 2021-08-25 09:01:43 merged: 2021-08-26 03:23:14

7. [34993](http://github.com/cms-sw/cmssw/pull/34993){:target="_blank"}  from **@CMSTrackerDPG**: [12_0_X] TkDQM: Fix tracker maps for run3 `dqm` created: 2021-08-24 13:18:27 merged: 2021-08-31 00:22:36

8. [34987](http://github.com/cms-sw/cmssw/pull/34987){:target="_blank"}  from **@cvuosalo**: [DD4hep] Revise order of materials, partial backport of #34974 `geometry` created: 2021-08-23 19:53:20 merged: 2021-08-27 15:44:19

9. [34970](http://github.com/cms-sw/cmssw/pull/34970){:target="_blank"}  from **@aperloff**: Updates to the TTTrack/TTTrack_TrackWord DataFormats `l1` `upgrade` created: 2021-08-20 22:54:55 merged: 2021-09-02 02:37:32

10. [34957](http://github.com/cms-sw/cmssw/pull/34957){:target="_blank"}  from **@fwyzard**: HLT customisation for Patatrack pixel tracks and GPU offload [12.0.x] `hlt` created: 2021-08-19 15:44:39 merged: 2021-08-21 07:07:58

11. [34949](http://github.com/cms-sw/cmssw/pull/34949){:target="_blank"}  from **@fwyzard**: Fix uploading the EventSetup conditions to multiple CUDA devices [12.0.x] `heterogeneous` created: 2021-08-19 10:22:28 merged: 2021-08-23 13:09:25

12. [34947](http://github.com/cms-sw/cmssw/pull/34947){:target="_blank"}  from **@mmusich**: [12.0.X] migrate `AlignmentProducer` to event consumes `alca` created: 2021-08-19 07:09:48 merged: 2021-08-20 01:51:11

13. [34936](http://github.com/cms-sw/cmssw/pull/34936){:target="_blank"}  from **@mmusich**: [12.0.X] do not produce NaNs in SiPixelActionExecutor `dqm` created: 2021-08-18 16:57:34 merged: 2021-08-19 12:26:15

14. [34930](http://github.com/cms-sw/cmssw/pull/34930){:target="_blank"}  from **@fwyzard**: Fix radix sort test (12.0.x) `heterogeneous` created: 2021-08-18 07:40:16 merged: 2021-08-19 01:05:36

15. [34923](http://github.com/cms-sw/cmssw/pull/34923){:target="_blank"}  from **@tvami**: [12_0_X] Add HCAL tag `HcalRespCorrs_2021_v3.0_mc` to Run-3 MC GTs `alca` created: 2021-08-17 18:57:22 merged: 2021-08-25 03:13:43

16. [34888](http://github.com/cms-sw/cmssw/pull/34888){:target="_blank"}  from **@mmusich**: [12_0_X] Fix rare crash in pixel template interpolation `reconstruction` `db` created: 2021-08-16 13:34:05 merged: 2021-08-17 15:49:07

17. [34877](http://github.com/cms-sw/cmssw/pull/34877){:target="_blank"}  from **@mmusich**: [12.0.X] Miscellaneous fixes to  `Alignment/OflineValidation` all-in-one tool  `alca` created: 2021-08-13 19:16:52 merged: 2021-08-16 07:53:21

18. [34861](http://github.com/cms-sw/cmssw/pull/34861){:target="_blank"}  from **@colizz**: [12_0_X] Backport the fix on the workflow 537 and the mergeLHE.py script `generators` `pdmv` `upgrade` created: 2021-08-13 07:25:39 merged: 2021-08-26 06:56:08

19. [34854](http://github.com/cms-sw/cmssw/pull/34854){:target="_blank"}  from **@ggovi**: o2o tools fixes and improvements for python3 `db` created: 2021-08-12 14:42:05 merged: 2021-08-19 13:16:49

20. [34851](http://github.com/cms-sw/cmssw/pull/34851){:target="_blank"}  from **@veszpv**: Pixel cluster repair by morphing backport to 12_0_X `operations` `reconstruction` created: 2021-08-12 09:57:22 merged: 2021-08-13 07:06:07

21. [34845](http://github.com/cms-sw/cmssw/pull/34845){:target="_blank"}  from **@CTPPS**: PPS Alignment - bug fix (backport) `alca` `db` created: 2021-08-11 14:43:11 merged: 2021-08-16 14:32:56

22. [34799](http://github.com/cms-sw/cmssw/pull/34799){:target="_blank"}  from **@abdoulline**: [12_0_X] backport : HF SimHits timing fix `geometry` `simulation` created: 2021-08-05 17:01:30 merged: 2021-08-07 02:29:01

#### CMSDIST Changes between Tags REL/CMSSW_12_0_0_pre6/slc7_amd64_gcc900 and REL/CMSSW_12_0_0/slc7_amd64_gcc900:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_0_0_pre6/slc7_amd64_gcc900...REL/CMSSW_12_0_0/slc7_amd64_gcc900)



1. [7210](http://github.com/cms-sw/cmsdist/pull/7210){:target="_blank"}  from **@cms-sw**: [12.0.X] back ported cmssw patch release fixes created: 2021-08-11 14:28:24 merged: 2021-08-12 07:48:57

2. [7202](http://github.com/cms-sw/cmsdist/pull/7202){:target="_blank"}  from **@cms-sw**: [12.0.X] fix EvtGen data path created: 2021-08-04 17:11:35 merged: 2021-08-06 07:08:18
