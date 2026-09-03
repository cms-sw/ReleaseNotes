---
layout: post
rel_link:  "20_1_0_pre3"
title:  "CMSSW_20_1_0_pre3"
date:   2026-09-02 20:45:14
categories: cmssw
relmajor: 20
relminor: 1
relsubminor: 0
relpre: _pre3
---

# CMSSW_20_1_0_pre3
#### Changes since CMSSW_20_1_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_20_1_0_pre2...CMSSW_20_1_0_pre3)



1. [51792](http://github.com/cms-sw/cmssw/pull/51792){:target="_blank"}  from **@fwyzard**: Remove unused `EDM_MPI_MessageType` array `heterogeneous` created: 2026-09-01 09:37:49 merged: 2026-09-01 14:38:06

2. [51764](http://github.com/cms-sw/cmssw/pull/51764){:target="_blank"}  from **@JHiltbrand**: Cleanup HCAL LUT XML Production Code `core` `db` created: 2026-08-27 08:07:55 merged: 2026-09-01 14:37:47

3. [51754](http://github.com/cms-sw/cmssw/pull/51754){:target="_blank"}  from **@AuroraPerego**: Modify CLUE3D in the barrel for EGM linking `reconstruction` created: 2026-08-25 10:14:02 merged: 2026-08-27 22:09:15

4. [51750](http://github.com/cms-sw/cmssw/pull/51750){:target="_blank"}  from **@makortel**: Remove testSkipEvent_cfg.py as obsolete `core` created: 2026-08-24 19:16:41 merged: 2026-08-25 16:47:34

5. [51749](http://github.com/cms-sw/cmssw/pull/51749){:target="_blank"}  from **@Annnnya**: configure MPISender via type and input tag instead of pattern `heterogeneous` created: 2026-08-24 15:41:55 merged: 2026-08-25 17:53:38

6. [51747](http://github.com/cms-sw/cmssw/pull/51747){:target="_blank"}  from **@Dr15Jones**: Fix handling of an exception thrown from a source `core` created: 2026-08-22 23:16:17 merged: 2026-08-26 11:47:54

7. [51746](http://github.com/cms-sw/cmssw/pull/51746){:target="_blank"}  from **@Dr15Jones**: Added additional tests of merged Run and LuminosityBlock products `core` created: 2026-08-21 16:27:53 merged: 2026-08-25 12:56:23

8. [51744](http://github.com/cms-sw/cmssw/pull/51744){:target="_blank"}  from **@suchandradutta**: Update of Phase2 Tracker Digitizer code for CPU Optimization `simulation` `trk` created: 2026-08-21 13:14:24 merged: 2026-08-27 09:33:40

9. [51741](http://github.com/cms-sw/cmssw/pull/51741){:target="_blank"}  from **@fwyzard**: Update the requested memory size in reused blocks `heterogeneous` created: 2026-08-21 05:47:55 merged: 2026-08-24 19:22:05

10. [51740](http://github.com/cms-sw/cmssw/pull/51740){:target="_blank"}  from **@fwyzard**: Make Open MPI 5 use the same accelerator as CMSSW `core` `heterogeneous` `operations` created: 2026-08-20 05:59:32 merged: 2026-08-26 18:41:38

11. [51739](http://github.com/cms-sw/cmssw/pull/51739){:target="_blank"}  from **@alexstrel**: Added  ROOT dictionaries in DataFormats `l1` `reconstruction` created: 2026-08-19 20:04:54 merged: 2026-08-22 05:51:53

12. [51734](http://github.com/cms-sw/cmssw/pull/51734){:target="_blank"}  from **@AdrianoDee**: Fix `defaultDatasets` for `Run4D127` `pdmv` created: 2026-08-19 07:58:55 merged: 2026-08-24 14:39:38

13. [51733](http://github.com/cms-sw/cmssw/pull/51733){:target="_blank"}  from **@mmusich**: [NGT] Introduce `GenericObjectDQMSource` `dqm` created: 2026-08-19 07:35:08 merged: 2026-08-27 09:34:36

14. [51727](http://github.com/cms-sw/cmssw/pull/51727){:target="_blank"}  from **@Dr15Jones**: Do not have debug level MessageLogger in TauValidator `dqm` created: 2026-08-18 15:13:08 merged: 2026-08-19 20:34:37

15. [51725](http://github.com/cms-sw/cmssw/pull/51725){:target="_blank"}  from **@Moanwar**: Updating the TICL offline NanoAOD `reconstruction` `xpog` created: 2026-08-18 14:26:48 merged: 2026-08-31 19:58:28

16. [51724](http://github.com/cms-sw/cmssw/pull/51724){:target="_blank"}  from **@makortel**: Move contents of `FWCore/Services/src` to `FWCore/Services/plugins` `core` created: 2026-08-18 14:21:02 merged: 2026-08-19 20:34:52

17. [51723](http://github.com/cms-sw/cmssw/pull/51723){:target="_blank"}  from **@makortel**: Consolidate `AR_WATCH_USING_METHOD` macros in `ActivityRegistry.h` `core` created: 2026-08-18 13:50:32 merged: 2026-08-19 20:35:22

18. [51721](http://github.com/cms-sw/cmssw/pull/51721){:target="_blank"}  from **@mmusich**: `ScoutingTrackMonitor`: fix for the axes' labels according to the pT cut `dqm` created: 2026-08-17 17:59:01 merged: 2026-08-19 05:26:59

19. [51720](http://github.com/cms-sw/cmssw/pull/51720){:target="_blank"}  from **@mmusich**: replace `HLTP2GTTauFilter` with an instace of `HLTP2GTSingleObjectFilter` `hlt` created: 2026-08-17 16:33:02 merged: 2026-08-19 20:35:35

20. [51719](http://github.com/cms-sw/cmssw/pull/51719){:target="_blank"}  from **@JanGerritSchulz**: Remove no-op if-statement and corresponding TODO from calculateVertexSharedTracks.cc `simulation` `trk` created: 2026-08-17 10:30:24 merged: 2026-08-21 09:32:02

21. [51718](http://github.com/cms-sw/cmssw/pull/51718){:target="_blank"}  from **@Chihwan-An**: Rename HLT_LooseDeepTauPFTauHPS150_L2NN_eta2p1 to L1NN `dqm` `hlt` created: 2026-08-17 09:41:16 merged: 2026-08-18 08:43:26

22. [51717](http://github.com/cms-sw/cmssw/pull/51717){:target="_blank"}  from **@AdrianoDee**: Fixed D127 Inputs `pdmv` created: 2026-08-16 20:44:51 merged: 2026-08-17 06:45:16

23. [51715](http://github.com/cms-sw/cmssw/pull/51715){:target="_blank"}  from **@aterigun**: DQMGenericClient: optionally compute relative resolution (sigma/mean) `dqm` created: 2026-08-16 00:44:06 merged: 2026-08-25 12:59:41

24. [51714](http://github.com/cms-sw/cmssw/pull/51714){:target="_blank"}  from **@fwyzard**: Remove unnecessary dependency on CUDA `dqm` created: 2026-08-15 15:51:18 merged: 2026-08-18 08:15:22

25. [51713](http://github.com/cms-sw/cmssw/pull/51713){:target="_blank"}  from **@smuzaffar**: Changes needed for updatign TF to version 2.21 `dqm` `ml` `reconstruction` `tracking` created: 2026-08-15 06:39:56 merged: 2026-08-31 20:00:26

26. [51711](http://github.com/cms-sw/cmssw/pull/51711){:target="_blank"}  from **@makortel**: Fix edmProvDump test for FileInPath local vs. release behavior `core` created: 2026-08-14 17:57:44 merged: 2026-08-17 11:39:58

27. [51708](http://github.com/cms-sw/cmssw/pull/51708){:target="_blank"}  from **@makortel**: Fix ActivityRegistry README.md `core` created: 2026-08-14 14:29:27 merged: 2026-08-17 12:09:44

28. [51707](http://github.com/cms-sw/cmssw/pull/51707){:target="_blank"}  from **@aterigun**: JetTester: add jpt jet type reading reco::JPTJetCollection `dqm` created: 2026-08-14 13:07:49 merged: 2026-08-14 17:44:27

29. [51706](http://github.com/cms-sw/cmssw/pull/51706){:target="_blank"}  from **@mmusich**: remove unused instances of `L1TTkEleFilter` and `L1TTkEmFilter` from the Phase-2 HLT menu `hlt` created: 2026-08-14 11:57:34 merged: 2026-08-14 17:44:13

30. [51702](http://github.com/cms-sw/cmssw/pull/51702){:target="_blank"}  from **@bsunanda**: [17_0_X] Phase2-hgx368P Debug the code of newighbour finder for HGCal cells `geometry` created: 2026-08-14 06:49:03 merged: 2026-08-14 17:42:58

31. [51700](http://github.com/cms-sw/cmssw/pull/51700){:target="_blank"}  from **@makortel**: Update dictionary package assignment for TrackingVertex-reco::Vertex associations `core` created: 2026-08-13 13:38:54 merged: 2026-08-14 06:56:14

32. [51699](http://github.com/cms-sw/cmssw/pull/51699){:target="_blank"}  from **@Dr15Jones**: TriggerReport summary now handled by a service `core` created: 2026-08-13 13:32:35 merged: 2026-08-17 11:39:04

33. [51696](http://github.com/cms-sw/cmssw/pull/51696){:target="_blank"}  from **@JanGerritSchulz**: [NGT] Set minHits for secondary vertexing with pixel tracks to 5 `hlt` created: 2026-08-13 08:02:30 merged: 2026-08-13 13:26:41

34. [51693](http://github.com/cms-sw/cmssw/pull/51693){:target="_blank"}  from **@bsunanda**: Phase2-gex221 Create a new scenario Run4D128 similar to Run4D127 but with the  older version of GE0 geometry description `geometry` `operations` `pdmv` created: 2026-08-13 04:49:43 merged: 2026-08-17 11:38:18

35. [51687](http://github.com/cms-sw/cmssw/pull/51687){:target="_blank"}  from **@bsunanda**: Phase2-hgx368O Improve the testing code for finding the nearest neighbour of HGCal silicon cells `geometry` created: 2026-08-12 06:06:20 merged: 2026-08-13 06:54:18

36. [51686](http://github.com/cms-sw/cmssw/pull/51686){:target="_blank"}  from **@slava77**: LST: add earlier skips to speedup Create* kernels using connected*Max counters  `reconstruction` `tracking` created: 2026-08-11 22:38:38 merged: 2026-08-19 20:34:23

37. [51684](http://github.com/cms-sw/cmssw/pull/51684){:target="_blank"}  from **@AdrianoDee**: New D127 Inputs `pdmv` created: 2026-08-11 22:15:14 merged: 2026-08-13 18:58:45

38. [51675](http://github.com/cms-sw/cmssw/pull/51675){:target="_blank"}  from **@JanGerritSchulz**: [NGT] Add production vertex of GenParticles to NGT Scouting NanoAOD `hlt` created: 2026-08-11 15:52:54 merged: 2026-08-12 05:23:03

39. [51673](http://github.com/cms-sw/cmssw/pull/51673){:target="_blank"}  from **@smuzaffar**: PY314: drop dxr unit test which uses deprecated cgi module `analysis` created: 2026-08-11 13:19:10 merged: 2026-08-12 05:23:17

40. [51672](http://github.com/cms-sw/cmssw/pull/51672){:target="_blank"}  from **@smuzaffar**: py3.14: explicitly pass the args.source instead of use of global args `dqm` created: 2026-08-11 13:14:45 merged: 2026-08-12 15:10:30

41. [51671](http://github.com/cms-sw/cmssw/pull/51671){:target="_blank"}  from **@smuzaffar**: py3.14: use function instead of lambda `alca` created: 2026-08-11 13:12:15 merged: 2026-08-12 06:13:04

42. [51670](http://github.com/cms-sw/cmssw/pull/51670){:target="_blank"}  from **@Electricks94**: Introspection for SoABlocks `heterogeneous` created: 2026-08-11 12:33:43 merged: 2026-08-27 22:09:45

43. [51669](http://github.com/cms-sw/cmssw/pull/51669){:target="_blank"}  from **@cms-ngt-hlt**: Generalised Phase-2 GT filters, modelled after `HLTL1TSeed` `hlt` created: 2026-08-11 11:32:27 merged: 2026-08-17 11:37:58

44. [51664](http://github.com/cms-sw/cmssw/pull/51664){:target="_blank"}  from **@Parsifal-2045**: Make `testHeterogeneousMenu` catch hidden consumes `hlt` created: 2026-08-10 17:08:38 merged: 2026-08-12 05:23:35

45. [51662](http://github.com/cms-sw/cmssw/pull/51662){:target="_blank"}  from **@mmusich**: make `bunchSpacingProducer` InputTag trackable  `hlt` `reconstruction` created: 2026-08-10 15:19:24 merged: 2026-08-12 05:23:49

46. [51661](http://github.com/cms-sw/cmssw/pull/51661){:target="_blank"}  from **@Dr15Jones**: Have InputProcessBlock transition have its own Workers `core` created: 2026-08-10 13:58:19 merged: 2026-08-13 18:27:07

47. [51653](http://github.com/cms-sw/cmssw/pull/51653){:target="_blank"}  from **@felicepantaleo**: TICL: initialise all TICLCandidate members and wrap phi in the track to trackster window `reconstruction` created: 2026-08-07 18:34:43 merged: 2026-08-12 05:25:38

48. [51652](http://github.com/cms-sw/cmssw/pull/51652){:target="_blank"}  from **@Dr15Jones**: zero initialize the vertex colllection in vertexFinder `reconstruction` `tracking` created: 2026-08-07 16:52:23 merged: 2026-08-25 13:01:31

49. [51651](http://github.com/cms-sw/cmssw/pull/51651){:target="_blank"}  from **@Dr15Jones**: Minor improvements to SiPixelRawDataError `simulation` `trk` created: 2026-08-07 16:07:36 merged: 2026-08-12 05:28:58

50. [51650](http://github.com/cms-sw/cmssw/pull/51650){:target="_blank"}  from **@Dr15Jones**: Removed unused member variable from EcalUncalibratedRecHit `reconstruction` created: 2026-08-07 15:04:23 merged: 2026-08-18 05:17:04

51. [51649](http://github.com/cms-sw/cmssw/pull/51649){:target="_blank"}  from **@sbaldu**: Rename SimDataformats TICL associator as `TICLAssociationMap` `dqm` `generators` `reconstruction` `simulation` `xpog` created: 2026-08-07 13:50:15 merged: 2026-08-21 09:33:48

52. [51648](http://github.com/cms-sw/cmssw/pull/51648){:target="_blank"}  from **@Dr15Jones**: Zero initialize TrackCollection `reconstruction` `tracking` created: 2026-08-07 13:42:19 merged: 2026-08-12 05:24:28

53. [51645](http://github.com/cms-sw/cmssw/pull/51645){:target="_blank"}  from **@thomreis**: Update EcalSimPulseShape payload inspector for empty EE pulses `db` `ecal` created: 2026-08-07 08:43:46 merged: 2026-08-12 05:25:03

54. [51642](http://github.com/cms-sw/cmssw/pull/51642){:target="_blank"}  from **@makortel**: Extend testing of corner cases of floating point parameter `core` created: 2026-08-06 21:04:25 merged: 2026-08-12 05:22:52

55. [51641](http://github.com/cms-sw/cmssw/pull/51641){:target="_blank"}  from **@Dr15Jones**: Only make Worker for global transition if needed `core` created: 2026-08-06 20:53:10 merged: 2026-08-13 06:54:04

56. [51639](http://github.com/cms-sw/cmssw/pull/51639){:target="_blank"}  from **@fabiocos**: MTD geometry: fast geographicalld rawId determination for BTLDetId `geometry` `simulation` created: 2026-08-06 16:16:52 merged: 2026-08-12 05:24:52

57. [51637](http://github.com/cms-sw/cmssw/pull/51637){:target="_blank"}  from **@EmanueleCoradin**: Fix PyTorchAlpaka Policy `heterogeneous` `ml` created: 2026-08-06 15:21:09 merged: 2026-08-27 22:10:40

58. [51631](http://github.com/cms-sw/cmssw/pull/51631){:target="_blank"}  from **@igv4321**: A bug fix for the use of Hcal pulse shapes from CMS database `reconstruction` created: 2026-08-05 12:52:56 merged: 2026-08-12 05:22:38

59. [51626](http://github.com/cms-sw/cmssw/pull/51626){:target="_blank"}  from **@makortel**: Remove JobFailure and PostESModuleRegistration signals as obsolete `core` `daq` created: 2026-08-04 20:09:40 merged: 2026-08-17 11:38:33

60. [51625](http://github.com/cms-sw/cmssw/pull/51625){:target="_blank"}  from **@makortel**: Improve how some ActivityRegistry signals are emitted `core` `db` created: 2026-08-04 20:06:41 merged: 2026-08-13 06:53:20

61. [51622](http://github.com/cms-sw/cmssw/pull/51622){:target="_blank"}  from **@kpedro88**: fix typo in cmsTritonConfigTool `heterogeneous` created: 2026-08-04 14:34:42 merged: 2026-08-27 09:07:05

62. [51615](http://github.com/cms-sw/cmssw/pull/51615){:target="_blank"}  from **@Electricks94**: Improve SoATemplate README `heterogeneous` created: 2026-08-03 14:29:42 merged: 2026-08-12 05:22:07

63. [51613](http://github.com/cms-sw/cmssw/pull/51613){:target="_blank"}  from **@mroguljic**: stabilize template multiply into adjacent add `db` `reconstruction` `trk` created: 2026-08-03 09:27:05 merged: 2026-08-25 12:59:01

64. [51608](http://github.com/cms-sw/cmssw/pull/51608){:target="_blank"}  from **@gartung**: PerfTools/Allocmon add circles plots for ExternalWork and Transform modules `core` created: 2026-07-31 23:24:33 merged: 2026-08-14 06:55:50

65. [51593](http://github.com/cms-sw/cmssw/pull/51593){:target="_blank"}  from **@fnenna**: New arbitration definition to optimize ME0 tracker muon reconstruction `reconstruction` created: 2026-07-29 12:10:26 merged: 2026-08-22 05:55:23

66. [51577](http://github.com/cms-sw/cmssw/pull/51577){:target="_blank"}  from **@JanGerritSchulz**: [NGT] Introduce general DQM Validation for Secondary Vertexing `dqm` `reconstruction` `simulation` `tracking` `trk` created: 2026-07-28 16:47:16 merged: 2026-08-12 05:22:24

67. [51555](http://github.com/cms-sw/cmssw/pull/51555){:target="_blank"}  from **@thomreis**: Add LD spike tagger algorithm to ECAL Phase 2 TP emulation `alca` `db` `ecal` `l1` `simulation` created: 2026-07-24 14:25:45 merged: 2026-08-17 11:37:08

68. [51528](http://github.com/cms-sw/cmssw/pull/51528){:target="_blank"}  from **@sbaldu**: Remove explicit implementation of `SoAConstParametersImpl` `heterogeneous` created: 2026-07-20 11:49:51 merged: 2026-08-13 06:52:19

69. [51526](http://github.com/cms-sw/cmssw/pull/51526){:target="_blank"}  from **@namapane**: Updates and maintenance of the MagneticField subsystem `db` `operations` `reconstruction` created: 2026-07-19 13:22:16 merged: 2026-08-18 05:15:30

70. [51413](http://github.com/cms-sw/cmssw/pull/51413){:target="_blank"}  from **@felicepantaleo**: move HGCAL configuration parameters from double to float  `hlt` `reconstruction` created: 2026-07-05 15:27:06 merged: 2026-08-25 16:48:37

71. [51378](http://github.com/cms-sw/cmssw/pull/51378){:target="_blank"}  from **@raoatifshad**: [WarningFix]: Remove mutable global state from makeArroPlots `alca` `trk` created: 2026-06-30 13:38:29 merged: 2026-08-12 05:54:39

72. [51111](http://github.com/cms-sw/cmssw/pull/51111){:target="_blank"}  from **@zhenbinwu**: [Phase2 L1T] GMT Upgrade of Kalman Filter for Barrel Muon KMTF `l1` created: 2026-06-01 21:44:09 merged: 2026-08-13 19:31:34

73. [50896](http://github.com/cms-sw/cmssw/pull/50896){:target="_blank"}  from **@DanielEstrada971102**: [L1T] DT Trigger Phase-2  Shower Tagging v1.2 `l1` created: 2026-05-06 19:51:53 merged: 2026-08-12 05:21:44

74. [50691](http://github.com/cms-sw/cmssw/pull/50691){:target="_blank"}  from **@Electricks94**: SoA Schema evolution `heterogeneous` created: 2026-04-08 14:14:34 merged: 2026-08-14 06:55:21

75. [50503](http://github.com/cms-sw/cmssw/pull/50503){:target="_blank"}  from **@ghyls**: Add an `MPISenderPortable` and `MPIReceiverPortable` modules to send/receive arbitrary device collections `core` `heterogeneous` `reconstruction` `simulation` `tracking` `trk` created: 2026-03-24 01:44:46 merged: 2026-08-31 19:57:59

76. [49995](http://github.com/cms-sw/cmssw/pull/49995){:target="_blank"}  from **@sbaldu**: Implement heterogeneous Association Map based on SoA blocks `heterogeneous` `reconstruction` created: 2026-02-01 14:30:48 merged: 2026-08-25 12:58:16

#### CMSDIST Changes between Tags REL/CMSSW_20_1_0_pre2/el9_amd64_gcc14 and REL/CMSSW_20_1_0_pre3/el9_amd64_gcc14:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_20_1_0_pre2/el9_amd64_gcc14...REL/CMSSW_20_1_0_pre3/el9_amd64_gcc14)



1. [10822](http://github.com/cms-sw/cmsdist/pull/10822){:target="_blank"}  from **@cms-sw**: cleanup fwlite deps created: 2026-09-02 20:35:24 merged: 2026-09-02 20:36:02

2. [10820](http://github.com/cms-sw/cmsdist/pull/10820){:target="_blank"}  from **@cms-sw**: fwlite: delete Heterogeneous*/*/plugins created: 2026-09-02 08:08:35 merged: 2026-09-02 08:08:50

3. [10816](http://github.com/cms-sw/cmsdist/pull/10816){:target="_blank"}  from **@cms-sw**: Match the root version 6.36.15 created: 2026-09-01 14:38:02 merged: 2026-09-02 06:51:51

4. [10800](http://github.com/cms-sw/cmsdist/pull/10800){:target="_blank"}  from **@fwyzard**: Prevent a deadlock in ROCm created: 2026-08-21 14:41:35 merged: 2026-08-23 08:47:26

5. [10797](http://github.com/cms-sw/cmsdist/pull/10797){:target="_blank"}  from **@todor-ivanov**: Update dasgoclient version to v02.04.54 created: 2026-08-20 08:56:36 merged: 2026-08-20 17:37:55

6. [10793](http://github.com/cms-sw/cmsdist/pull/10793){:target="_blank"}  from **@cms-sw**: [AOTriton] Avoid hard-coded aotriton version for aotriton-images created: 2026-08-18 14:50:53 merged: 2026-08-21 20:46:31

7. [10789](http://github.com/cms-sw/cmsdist/pull/10789){:target="_blank"}  from **@cms-sw**: Tensorflow 2.21 and related changes created: 2026-08-15 06:29:58 merged: 2026-08-31 20:00:27

8. [10787](http://github.com/cms-sw/cmsdist/pull/10787){:target="_blank"}  from **@felicepantaleo**: Update clue to 1.1.3 created: 2026-08-14 18:13:59 merged: 2026-08-27 06:42:11

9. [10786](http://github.com/cms-sw/cmsdist/pull/10786){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-Phase2L1GMT to V00-01-01 created: 2026-08-13 19:31:33 merged: 2026-08-13 19:31:35

10. [10785](http://github.com/cms-sw/cmsdist/pull/10785){:target="_blank"}  from **@cms-sw**: Improved rocm source extraction created: 2026-08-13 15:11:28 merged: 2026-08-15 05:21:32

11. [10780](http://github.com/cms-sw/cmsdist/pull/10780){:target="_blank"}  from **@cms-sw**: Move to GCC14 as default for 20.1.X created: 2026-08-11 06:25:29 merged: 2026-08-13 06:56:53

12. [10764](http://github.com/cms-sw/cmsdist/pull/10764){:target="_blank"}  from **@fwyzard**: Build LLVM only for the current CPU architecture created: 2026-08-06 06:49:58 merged: 2026-08-25 15:00:28
