---
layout: post
rel_link:  "7_4_3"
title:  "CMSSW_7_4_3"
date:   2015-05-23 19:41:14
categories: cmssw
relmajor: 7
relminor: 4
relsubminor: 3
---

# CMSSW_7_4_3
#### Changes since CMSSW_7_4_2_patch1:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_4_2_patch1...CMSSW_7_4_3)



1. [9247](http://github.com/cms-sw/cmssw/pull/9247){:target="_blank"}  from **@davidlange6**: protect against a missing L1 GT `dqm`  created: 2015-05-23 12:30:18 merged: 2015-05-23 15:50:16

2. [9240](http://github.com/cms-sw/cmssw/pull/9240){:target="_blank"}  from **@slava77**:  Put some order in old MF configs; asymptotic default will be MagneticField_cff.py (same as #9239 ) `operations`  created: 2015-05-22 16:13:15 merged: 2015-05-23 15:50:01

3. [9212](http://github.com/cms-sw/cmssw/pull/9212){:target="_blank"}  from **@dmitrijus**: Minor improvement for DQM/PhysicsHWW. `dqm`  created: 2015-05-21 18:05:20 merged: 2015-05-22 14:17:44

4. [9176](http://github.com/cms-sw/cmssw/pull/9176){:target="_blank"}  from **@cms-tsg-storm**: HLT updates on top of what is in CMSSW742 `hlt`  created: 2015-05-20 14:52:25 merged: 2015-05-22 14:13:07

5. [9220](http://github.com/cms-sw/cmssw/pull/9220){:target="_blank"}  from **@lveldere**: Bug fix: undo fix of ConversionTracks in case of gen-mixing (74X) `fastsim`  created: 2015-05-22 07:58:35 merged: 2015-05-22 14:12:22

6. [9229](http://github.com/cms-sw/cmssw/pull/9229){:target="_blank"}  from **@davidlange6**: Option to remove hwwdqm `dqm`  `operations`  created: 2015-05-22 10:15:54 merged: 2015-05-22 14:11:53

7. [8953](http://github.com/cms-sw/cmssw/pull/8953){:target="_blank"}  from **@cms-tsg-storm**: HLT updates on top of 741 with FastSim for 74X `fastsim`  `hlt`  `operations`  created: 2015-05-04 17:53:29 merged: 2015-05-22 06:35:38

8. [9181](http://github.com/cms-sw/cmssw/pull/9181){:target="_blank"}  from **@wmtan**: Backport secondary input source improvements from 7_5_X `core`  created: 2015-05-20 19:20:36 merged: 2015-05-22 06:34:37

9. [8653](http://github.com/cms-sw/cmssw/pull/8653){:target="_blank"}  from **@lveldere**: Fastsim 74X: fix truth matching for recoTracks from PU events `reconstruction`  `simulation`  created: 2015-04-03 12:44:57 merged: 2015-05-22 06:33:32

10. [9090](http://github.com/cms-sw/cmssw/pull/9090){:target="_blank"}  from **@cfmcginn**: Moved *_cff.py to *_cfi.py for inclusion into HLT and confdb (backport from 75 pr) `reconstruction`  created: 2015-05-14 16:22:19 merged: 2015-05-21 20:22:04

11. [9211](http://github.com/cms-sw/cmssw/pull/9211){:target="_blank"}  from **@lveldere**: FastSim 74X: remove FastSim specific collections from AODSIM  `fastsim`  created: 2015-05-21 17:54:41 merged: 2015-05-21 20:18:57

12. [9108](http://github.com/cms-sw/cmssw/pull/9108){:target="_blank"}  from **@fcavallo**: fix FEDIDmin/max initialization `dqm`  created: 2015-05-15 14:33:56 merged: 2015-05-21 14:43:30

13. [9187](http://github.com/cms-sw/cmssw/pull/9187){:target="_blank"}  from **@cms-btv-pog**: Protection for pt=0 ghost candidates in jet flavor clustering (74X) `analysis`  created: 2015-05-21 00:09:42 merged: 2015-05-21 14:38:49

14. [9205](http://github.com/cms-sw/cmssw/pull/9205){:target="_blank"}  from **@Dr15Jones**: Make 10MB the default stack size for additional threads `core`  created: 2015-05-21 14:25:08 merged: 2015-05-21 14:38:37

15. [9151](http://github.com/cms-sw/cmssw/pull/9151){:target="_blank"}  from **@HuguesBrun**: fix muon HLT DQM for tk muon (backport in 74X) `dqm`  created: 2015-05-19 12:14:52 merged: 2015-05-20 18:37:18

16. [9164](http://github.com/cms-sw/cmssw/pull/9164){:target="_blank"}  from **@mengleisun**: fix the calibration DQM configuration `dqm`  created: 2015-05-19 21:22:22 merged: 2015-05-20 18:36:57

17. [9006](http://github.com/cms-sw/cmssw/pull/9006){:target="_blank"}  from **@emanueledimarco**: Use of full5x5 cluster shapes to compute the MVA, read gzipped xml files `analysis`  created: 2015-05-08 13:19:39 merged: 2015-05-20 15:12:49

18. [8677](http://github.com/cms-sw/cmssw/pull/8677){:target="_blank"}  from **@bmarzocc**: 7_4_X_alcarecostream_nophisym `alca`  `operations`  `pdmv`  created: 2015-04-08 06:53:57 merged: 2015-05-20 15:05:38

19. [8056](http://github.com/cms-sw/cmssw/pull/8056){:target="_blank"}  from **@cms-btv-pog**: Switch by default to new flavour tool based on Hadrons. Update of exampl... `dqm`  created: 2015-03-04 08:58:52 merged: 2015-05-20 15:03:20

20. [8124](http://github.com/cms-sw/cmssw/pull/8124){:target="_blank"}  from **@rjwang**: add plots of wire group and strip numbers for all chambers `dqm`  created: 2015-03-06 18:12:05 merged: 2015-05-20 15:03:06

21. [8152](http://github.com/cms-sw/cmssw/pull/8152){:target="_blank"}  from **@fruboes**: DQM plots for jet triggers in lowPU runs `dqm`  created: 2015-03-09 12:25:38 merged: 2015-05-20 15:02:53

22. [8210](http://github.com/cms-sw/cmssw/pull/8210){:target="_blank"}  from **@ndaci**:   Added Dxy plots (only for electron/muon at this moment) (Backport from 75X) `dqm`  created: 2015-03-11 19:45:08 merged: 2015-05-20 15:02:42

23. [8573](http://github.com/cms-sw/cmssw/pull/8573){:target="_blank"}  from **@jingyucms**: Histograms for L1T Stage1 `dqm`  created: 2015-03-27 17:29:13 merged: 2015-05-20 15:02:32

24. [8730](http://github.com/cms-sw/cmssw/pull/8730){:target="_blank"}  from **@acimmino**: RPC DQM Fix for summary plots and DCS bit in 74X `dqm`  created: 2015-04-14 15:19:03 merged: 2015-05-20 15:01:58

25. [8904](http://github.com/cms-sw/cmssw/pull/8904){:target="_blank"}  from **@lveldere**: Fastsim: 74X premixing `fastsim`  `operations`  `pdmv`  `simulation`  created: 2015-04-28 19:39:35 merged: 2015-05-20 15:01:42

26. [8937](http://github.com/cms-sw/cmssw/pull/8937){:target="_blank"}  from **@aelwood**: Updated the alphaT paths for the DQM modules `dqm`  created: 2015-05-01 21:15:48 merged: 2015-05-20 15:01:26

27. [8972](http://github.com/cms-sw/cmssw/pull/8972){:target="_blank"}  from **@hdelanno**: Cleaned unused config parameters in Strip DQM for 7_4_X `dqm`  created: 2015-05-06 14:45:39 merged: 2015-05-20 15:01:15

28. [9021](http://github.com/cms-sw/cmssw/pull/9021){:target="_blank"}  from **@jmduarte**: updating razor HLT paths for SUSY DQM in 74X `dqm`  created: 2015-05-08 23:11:12 merged: 2015-05-20 15:00:57

29. [9029](http://github.com/cms-sw/cmssw/pull/9029){:target="_blank"}  from **@cbernet**: Heppy 74X integration `analysis`  created: 2015-05-11 07:49:26 merged: 2015-05-20 15:00:46

#### CMSDIST Changes between Tags REL/CMSSW_7_4_2_patch1/slc6_amd64_gcc491 and REL/CMSSW_7_4_3/slc6_amd64_gcc491:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_4_2_patch1/slc6_amd64_gcc491...REL/CMSSW_7_4_3/slc6_amd64_gcc491)



1. [1570](http://github.com/cms-sw/cmsdist/pull/1570){:target="_blank"}  from **@smuzaffar**: updated root commit to include the LorentzVector fix 09b7416ea111be6651790d346294572b82c59a24 created: 2015-05-21 09:32:25 merged: 2015-05-21 09:32:29

2. [1568](http://github.com/cms-sw/cmsdist/pull/1568){:target="_blank"}  from @cms-sw: Update root to commit cms-sw/root**@8fdd98** 7_4_X created: 2015-05-21 09:17:41 merged: 2015-05-21 09:17:52
