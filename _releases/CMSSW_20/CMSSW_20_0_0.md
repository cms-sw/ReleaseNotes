---
layout: post
rel_link:  "20_0_0"
title:  "CMSSW_20_0_0"
date:   2026-08-10 16:58:31
categories: cmssw
relmajor: 20
relminor: 0
relsubminor: 0
---

# CMSSW_20_0_0
#### Changes since CMSSW_20_0_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_20_0_0_pre1...CMSSW_20_0_0)



1. [51658](http://github.com/cms-sw/cmssw/pull/51658){:target="_blank"}  from **@kpedro88**: Move Run 4 default to D127 [20_0_X] `db` `geometry` `operations` `pdmv` created: 2026-08-09 16:21:01 merged: 2026-08-10 15:21:24

2. [51646](http://github.com/cms-sw/cmssw/pull/51646){:target="_blank"}  from **@felicepantaleo**: backport 20_0_X - enable ReconnectDroppedAncestors by default `ppd` `simulation` created: 2026-08-07 10:20:01 merged: 2026-08-10 16:54:30

3. [51620](http://github.com/cms-sw/cmssw/pull/51620){:target="_blank"}  from **@bsunanda**: Phase2 gex219  Create a new workflow for Run4D127 with the Tracker geometry as in T35 and also with updated documentation in Configuration/Geometry/README.md `geometry` `operations` `pdmv` created: 2026-08-04 03:42:25 merged: 2026-08-05 15:58:56

4. [51597](http://github.com/cms-sw/cmssw/pull/51597){:target="_blank"}  from **@cms-tsg-storm**: [20.0.X] Add an `addOnTest` for the Phase 2 HLT menu `core` `hlt` created: 2026-07-29 19:45:48 merged: 2026-08-10 15:22:29

5. [51591](http://github.com/cms-sw/cmssw/pull/51591){:target="_blank"}  from **@mmusich**: [20.0.X] Update `GeneralPurposeVertexAnalyzer` and `PrimaryVertexMonitor` axes labels accordingly to track pT cut `alca` `dqm` `tracking` `trk` created: 2026-07-29 10:47:21 merged: 2026-07-31 08:10:48

6. [51590](http://github.com/cms-sw/cmssw/pull/51590){:target="_blank"}  from **@bsunanda**: Phase2-gex216 Add a new scenario Run4D126 with the latest versions of Tracker, HGCal, MTD, Shield and GE0 -- backport of 51589 `geometry` `operations` `pdmv` created: 2026-07-29 09:58:10 merged: 2026-08-03 13:03:43

7. [51585](http://github.com/cms-sw/cmssw/pull/51585){:target="_blank"}  from **@waredjeb**: [Backport 20_0_X] Accurate MIP Scaling V19 `simulation` created: 2026-07-29 08:27:49 merged: 2026-08-05 07:21:45

8. [51568](http://github.com/cms-sw/cmssw/pull/51568){:target="_blank"}  from **@mmusich**: [20.0.X] Implement MIP Timing Detector reconstruction sequence for Phase-2 HLT  `dqm` `hlt` `operations` `pdmv` `reconstruction` `simulation` created: 2026-07-27 14:51:44 merged: 2026-07-31 05:49:59

9. [51544](http://github.com/cms-sw/cmssw/pull/51544){:target="_blank"}  from **@felicepantaleo**: backport 20_0_X - Fix v19 HGCal ToA jitter constant and per-type time offset generation `hlt` `simulation` created: 2026-07-22 19:46:14 merged: 2026-07-25 23:55:09

10. [51534](http://github.com/cms-sw/cmssw/pull/51534){:target="_blank"}  from **@thomreis**: Fix ECAL DQM warnings about missing endcap collections in Phase 2 - 200X `dqm` `ecal` `simulation` created: 2026-07-21 10:44:42 merged: 2026-07-29 17:09:00

11. [51525](http://github.com/cms-sw/cmssw/pull/51525){:target="_blank"}  from **@felicepantaleo**: backport 20_0_X - Fix HGCal HD 200um (type 3) handling in legacy digitizer ZS and v19 local reco constants `hgcal` `reconstruction` `simulation` created: 2026-07-18 15:23:22 merged: 2026-07-21 14:37:05

12. [51520](http://github.com/cms-sw/cmssw/pull/51520){:target="_blank"}  from **@thomreis**: Update ECAL Phase 2 sample noise correlations - 200X `ecal` `simulation` created: 2026-07-17 11:28:33 merged: 2026-07-30 14:34:34

13. [51487](http://github.com/cms-sw/cmssw/pull/51487){:target="_blank"}  from **@felicepantaleo**: backport 20_0_X - TruthInfo: pileup-aware truth graph during mixing `generators` created: 2026-07-14 20:23:37 merged: 2026-07-15 08:44:07

14. [51474](http://github.com/cms-sw/cmssw/pull/51474){:target="_blank"}  from **@mbluj**: Updates L1T OMTF for Phase 2 [20_0_X] `l1` created: 2026-07-13 13:21:29 merged: 2026-08-04 15:37:58

15. [51469](http://github.com/cms-sw/cmssw/pull/51469){:target="_blank"}  from **@felicepantaleo**: 20_0_X backport - MC-truth graph prototype `dqm` `generators` `operations` `pdmv` `simulation` created: 2026-07-12 16:43:32 merged: 2026-07-14 03:54:09

16. [51464](http://github.com/cms-sw/cmssw/pull/51464){:target="_blank"}  from **@bsunanda**: Phase2-hgx368H Modify the testing scripts for neighbour finder and implement debug in the original code - backport of #51463 `geometry` created: 2026-07-11 06:24:16 merged: 2026-07-12 20:59:05

17. [51462](http://github.com/cms-sw/cmssw/pull/51462){:target="_blank"}  from **@AdrianoDee**: [20_X] New Inputs for Run4 D121  `pdmv` created: 2026-07-10 08:49:01 merged: 2026-07-12 20:58:52

18. [51440](http://github.com/cms-sw/cmssw/pull/51440){:target="_blank"}  from **@bsunanda**: Phase2-hgx368D Bug fix in Geometry/HGCalGeometry as pointed out by Daria Selivanova and Andreas Hinzman `geometry` created: 2026-07-08 07:34:24 merged: 2026-07-09 10:35:15

19. [51437](http://github.com/cms-sw/cmssw/pull/51437){:target="_blank"}  from **@mmusich**: [20.0.X] first implementation of `TrigObjP4FlatTableProducer` `hlt` `pdmv` created: 2026-07-07 17:39:58 merged: 2026-07-09 10:37:32

20. [51436](http://github.com/cms-sw/cmssw/pull/51436){:target="_blank"}  from **@thomreis**: Add premixing to development ECAL Phase 2 simulation - 200X `ecal` `l1` `pdmv` `reconstruction` `simulation` created: 2026-07-07 17:11:02 merged: 2026-07-10 20:07:11

21. [51411](http://github.com/cms-sw/cmssw/pull/51411){:target="_blank"}  from **@cms-ngt-hlt**: [20.0.X] fix bug in `hltMkFitEventOfHits`, do not use the offline beamspot at HLT `hlt` created: 2026-07-04 10:01:33 merged: 2026-07-07 18:14:37

22. [51403](http://github.com/cms-sw/cmssw/pull/51403){:target="_blank"}  from **@thomreis**: Add ECAL Phase 2 digis and TP digis validation - 200X `dqm` `ecal` `l1` `simulation` created: 2026-07-03 12:44:59 merged: 2026-07-09 10:31:25

23. [51401](http://github.com/cms-sw/cmssw/pull/51401){:target="_blank"}  from **@thomreis**: Add additional processes to ECAL development matrix workflows - 200X `ecal` `pdmv` created: 2026-07-03 12:41:08 merged: 2026-07-12 20:58:21

24. [51386](http://github.com/cms-sw/cmssw/pull/51386){:target="_blank"}  from **@bsunanda**: Phase2-hgx368B: Modify the debug statements in HGCSiliconDtId and HGCScintillatorDetId to make them simpler and user friendly (backport of #51382 and #51385 `simulation` created: 2026-07-01 09:19:07 merged: 2026-07-03 07:59:01

25. [51347](http://github.com/cms-sw/cmssw/pull/51347){:target="_blank"}  from **@mmusich**: [20.0.X] `compareMemoryProfiles`: support just one file in input `hlt` created: 2026-06-28 08:53:02 merged: 2026-06-30 15:19:41

26. [51334](http://github.com/cms-sw/cmssw/pull/51334){:target="_blank"}  from **@slava77**: LST: set T5 occupancy threshold at 100K (backport of #51333) `hlt` `reconstruction` `tracking` created: 2026-06-26 17:17:14 merged: 2026-07-08 20:29:04

27. [51327](http://github.com/cms-sw/cmssw/pull/51327){:target="_blank"}  from **@bsunanda**: Phase2-hgx367lm Correct a bug in HGCalGeomParameters.cc to make it work correctly for the ColdBox mode of HGCal and the testing code for neighbour finder of HGCal silicon cells -- backport of #51323 and #51324 `geometry` created: 2026-06-26 05:28:53 merged: 2026-06-28 08:45:14

28. [51315](http://github.com/cms-sw/cmssw/pull/51315){:target="_blank"}  from **@Electricks94**: [Backport to 20_0_X (#50691)] SoA Schema evolution `heterogeneous` created: 2026-06-25 07:31:40 merged: 2026-06-30 15:24:40

29. [51313](http://github.com/cms-sw/cmssw/pull/51313){:target="_blank"}  from **@kpedro88**: Fix incorrect loop and memory leak in Phase 2 SIM code [20_0_X] `simulation` created: 2026-06-24 22:34:25 merged: 2026-06-26 06:36:29

30. [51243](http://github.com/cms-sw/cmssw/pull/51243){:target="_blank"}  from **@makortel**: [20_0_X] Remove Run 3 PU GPU workflows `pdmv` created: 2026-06-17 12:12:58 merged: 2026-06-18 08:45:15

31. [51234](http://github.com/cms-sw/cmssw/pull/51234){:target="_blank"}  from **@makortel**: [20_0_X] Fix SciTag values `core` created: 2026-06-17 06:30:02 merged: 2026-06-17 18:02:24

32. [51223](http://github.com/cms-sw/cmssw/pull/51223){:target="_blank"}  from **@cms-tsg-storm**: [20.0.X] re-activate Phase2 HLT timing script, using samples produced in `CMSSW_20_0_0_pre1` `hlt` created: 2026-06-16 07:36:27 merged: 2026-06-17 08:59:07

33. [51194](http://github.com/cms-sw/cmssw/pull/51194){:target="_blank"}  from **@bsunanda**: Phase2-hgxhgx367C Backport all modifications related to HGCal ColdBox simulation to CMSSW_20_0_X (from CMSSW_17_0_X version) `geometry` `simulation` created: 2026-06-11 05:24:36 merged: 2026-06-14 06:06:20

34. [51185](http://github.com/cms-sw/cmssw/pull/51185){:target="_blank"}  from **@bsunanda**: Phase2-hgx367B2 Equip RecHitTools to work for a single HGCal detector as in ColdBox setup (backport of #51184) `reconstruction` created: 2026-06-10 15:09:38 merged: 2026-06-13 05:57:21

35. [51157](http://github.com/cms-sw/cmssw/pull/51157){:target="_blank"}  from **@Dr15Jones**: [backport 20_0] Must use streamer when writing CSCSegment to RNTuple `reconstruction` created: 2026-06-09 15:06:52 merged: 2026-06-11 06:18:02

36. [51151](http://github.com/cms-sw/cmssw/pull/51151){:target="_blank"}  from **@cms-tsg-storm**: Disable MC-based TSG tests in 20_0_X `hlt` created: 2026-06-09 07:31:13 merged: 2026-06-10 20:38:21

#### CMSDIST Changes between Tags REL/CMSSW_20_0_0_pre1/el8_amd64_gcc13 and REL/CMSSW_20_0_0/el8_amd64_gcc13:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_20_0_0_pre1/el8_amd64_gcc13...REL/CMSSW_20_0_0/el8_amd64_gcc13)



1. [10771](http://github.com/cms-sw/cmsdist/pull/10771){:target="_blank"}  from **@quinnanm**: [20_0_X] Update hls4mlEmulatorExtras to v1.1.7 (backport) created: 2026-08-07 14:33:25 merged: 2026-08-09 20:55:07

2. [10759](http://github.com/cms-sw/cmsdist/pull/10759){:target="_blank"}  from **@cms-sw**: [20.0.X] Update L1Trigger-L1TMuon version to V01-13-00 created: 2026-08-05 07:46:43 merged: 2026-08-05 07:47:14

3. [10652](http://github.com/cms-sw/cmsdist/pull/10652){:target="_blank"}  from **@fwyzard**: [20.0] Set `ROCM_PATH` to the CMSSW ROCm installation created: 2026-06-17 05:22:14 merged: 2026-06-17 17:41:01

4. [10609](http://github.com/cms-sw/cmsdist/pull/10609){:target="_blank"}  from **@fwyzard**: [20.0] Update CUDA to version 12.9.2 created: 2026-06-08 23:08:15 merged: 2026-06-16 13:09:01
