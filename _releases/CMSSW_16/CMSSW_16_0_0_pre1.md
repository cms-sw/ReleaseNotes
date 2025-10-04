---
layout: post
rel_link:  "16_0_0_pre1"
title:  "CMSSW_16_0_0_pre1"
date:   2025-10-04 07:46:13
categories: cmssw
relmajor: 16
relminor: 0
relsubminor: 0
relpre: _pre1
---

# CMSSW_16_0_0_pre1
#### Changes since CMSSW_15_1_0_pre5:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_15_1_0_pre5...CMSSW_16_0_0_pre1)



1. [49051](http://github.com/cms-sw/cmssw/pull/49051){:target="_blank"}  from **@AdrianoDee**: Reading Certification JSON from `cvmfs` in `das-up-to-nevents.py` `pdmv` `upgrade` created: 2025-10-02 19:59:55 merged: 2025-10-03 08:21:03

2. [49047](http://github.com/cms-sw/cmssw/pull/49047){:target="_blank"}  from **@bsunanda**: Run3-alca262 Update the calibration macro which is used for IsoTrack calibration of HCAL `alca` created: 2025-10-02 05:06:50 merged: 2025-10-03 08:40:05

3. [49041](http://github.com/cms-sw/cmssw/pull/49041){:target="_blank"}  from **@bsunanda**: Run3-gex191 Update the ZDC geometry and the material in the transport region `geometry` `upgrade` created: 2025-10-01 15:22:24 merged: 2025-10-02 07:56:07

4. [49040](http://github.com/cms-sw/cmssw/pull/49040){:target="_blank"}  from **@saswatinandan**: Implementing suggestions received in PR 49015 `reconstruction` `trk` created: 2025-10-01 15:05:54 merged: 2025-10-02 08:53:39

5. [49033](http://github.com/cms-sw/cmssw/pull/49033){:target="_blank"}  from **@civanch**: [SIM] Update Geant4 user actions for phase2 simulation `simulation` `upgrade` created: 2025-09-30 16:35:58 merged: 2025-10-02 12:26:57

6. [49032](http://github.com/cms-sw/cmssw/pull/49032){:target="_blank"}  from **@Dr15Jones**: initialized variables before use in framework code `core` created: 2025-09-30 14:57:44 merged: 2025-10-02 19:27:06

7. [49024](http://github.com/cms-sw/cmssw/pull/49024){:target="_blank"}  from **@AdrianoDee**: Properly Clamping the Clusters in Module with `maxNumClustersPerModules` `reconstruction` `heterogeneous` `trk` created: 2025-09-29 12:54:08 merged: 2025-09-30 19:23:48

8. [49023](http://github.com/cms-sw/cmssw/pull/49023){:target="_blank"}  from **@waredjeb**: Filter LayerClusters  for TICL Recovery PR by AlgoID and Size  `hlt` `reconstruction` `upgrade` created: 2025-09-29 12:11:26 merged: 2025-10-02 08:53:28

9. [49021](http://github.com/cms-sw/cmssw/pull/49021){:target="_blank"}  from **@AdrianoDee**: Fixes for Digi Morphing: Limiting Histogram Size and Decoupling for `TrackerTraits` `geometry` `reconstruction` `heterogeneous` `trk` created: 2025-09-29 10:55:46 merged: 2025-10-03 16:16:14

10. [49019](http://github.com/cms-sw/cmssw/pull/49019){:target="_blank"}  from **@israr100**: Provide fillDescriptions to CSC ESproducers for HLT `alca` created: 2025-09-29 08:41:07 merged: 2025-09-30 08:45:56

11. [49016](http://github.com/cms-sw/cmssw/pull/49016){:target="_blank"}  from **@fwyzard**: Use the GPU family macros for the ROCm warp size `heterogeneous` created: 2025-09-29 06:13:24 merged: 2025-09-30 15:35:13

12. [49015](http://github.com/cms-sw/cmssw/pull/49015){:target="_blank"}  from **@saswatinandan**: Modification of existing rawprime version of SiStripApproxCluster `reconstruction` `trk` created: 2025-09-28 20:08:32 merged: 2025-09-30 18:44:27

13. [49014](http://github.com/cms-sw/cmssw/pull/49014){:target="_blank"}  from **@mmusich**: `PrimaryVertexResolution`: add protection against missing track references in input vertex `dqm` `tracking` created: 2025-09-28 19:04:55 merged: 2025-09-29 11:50:30

14. [49012](http://github.com/cms-sw/cmssw/pull/49012){:target="_blank"}  from **@konpas17**: HCAL: Move HF fine-grain thresholds to conditions `alca` `l1` created: 2025-09-27 18:17:35 merged: 2025-10-02 19:26:27

15. [49001](http://github.com/cms-sw/cmssw/pull/49001){:target="_blank"}  from **@Dr15Jones**: Gather more timing information about Framework startup `core` created: 2025-09-26 14:18:35 merged: 2025-09-28 08:36:12

16. [49000](http://github.com/cms-sw/cmssw/pull/49000){:target="_blank"}  from **@fabiocos**: Reconstruction: remove RecoTracker dependency on MTD `reconstruction` `tracking` created: 2025-09-26 13:51:19 merged: 2025-09-30 07:39:06

17. [48999](http://github.com/cms-sw/cmssw/pull/48999){:target="_blank"}  from **@mkirsano**: align HepMC3 plugin with HepMC2 plugin and add test configs `generators` created: 2025-09-26 13:47:40 merged: 2025-10-02 19:29:48

18. [48997](http://github.com/cms-sw/cmssw/pull/48997){:target="_blank"}  from **@bsunanda**: Phase2-hgx364E Accommodate new V19 options in some of the tests `dqm` `geometry` created: 2025-09-26 05:25:14 merged: 2025-09-30 18:15:35

19. [48996](http://github.com/cms-sw/cmssw/pull/48996){:target="_blank"}  from **@Dr15Jones**: Add test for reading files with different ProductRegistries `core` created: 2025-09-25 19:27:38 merged: 2025-09-30 07:35:22

20. [48990](http://github.com/cms-sw/cmssw/pull/48990){:target="_blank"}  from **@bsunanda**: Run3-gex190 Update the ZDC description using a new zdc.xml file from Hanna `geometry` `upgrade` created: 2025-09-25 08:07:53 merged: 2025-09-26 05:13:52

21. [48989](http://github.com/cms-sw/cmssw/pull/48989){:target="_blank"}  from **@sihyunjeon**: add hepmc writer `generators` created: 2025-09-25 00:44:17 merged: 2025-09-26 08:44:34

22. [48987](http://github.com/cms-sw/cmssw/pull/48987){:target="_blank"}  from **@Dr15Jones**: Fix lifetime issue found in edmWriteConfigs `core` created: 2025-09-24 20:05:42 merged: 2025-09-25 13:27:57

23. [48986](http://github.com/cms-sw/cmssw/pull/48986){:target="_blank"}  from **@AuroraPerego**: Fix `idLastStoredAncestor` to point to a track parent when the full graph is not saved `simulation` created: 2025-09-24 17:25:01 merged: 2025-09-28 08:35:22

24. [48983](http://github.com/cms-sw/cmssw/pull/48983){:target="_blank"}  from **@lukaszmichalskii**: Make TupleOrPointerType use const pointer in SoAConstParametersImpl `heterogeneous` created: 2025-09-24 14:52:24 merged: 2025-09-25 06:57:05

25. [48981](http://github.com/cms-sw/cmssw/pull/48981){:target="_blank"}  from **@bsunanda**: Run3-alca261 Update the macros used to calibrate Hcal IsoTrack studies `alca` created: 2025-09-24 12:56:59 merged: 2025-09-26 08:52:14

26. [48980](http://github.com/cms-sw/cmssw/pull/48980){:target="_blank"}  from **@mmusich**: add HLT vertexing resolution monitoring (by split vertex method) `dqm` `tracking` created: 2025-09-24 12:29:49 merged: 2025-09-26 16:00:29

27. [48979](http://github.com/cms-sw/cmssw/pull/48979){:target="_blank"}  from **@kmorrison314**: [L1T] EMTF DQM Errors Plot and GEM Plot Minor Fixes `dqm` created: 2025-09-24 11:15:12 merged: 2025-09-30 18:14:45

28. [48978](http://github.com/cms-sw/cmssw/pull/48978){:target="_blank"}  from **@hjbossi**: [DQM]: Improvements to ZDC DQM `dqm` created: 2025-09-24 01:36:46 merged: 2025-09-30 18:13:42

29. [48975](http://github.com/cms-sw/cmssw/pull/48975){:target="_blank"}  from **@ReyerBand**: Added fillDescriptions method for EcalSeverityLevel `reconstruction` `ecal` created: 2025-09-23 16:53:01 merged: 2025-09-25 06:58:38

30. [48971](http://github.com/cms-sw/cmssw/pull/48971){:target="_blank"}  from **@waredjeb**: Add PF GPU-CPU difference plots in DQM `dqm` created: 2025-09-23 09:26:16 merged: 2025-09-26 07:31:52

31. [48970](http://github.com/cms-sw/cmssw/pull/48970){:target="_blank"}  from **@leonardogiannini**: [mkFit] propagation to plane in backward fit phase2 and bug fix `reconstruction` `tracking` created: 2025-09-22 22:17:24 merged: 2025-09-25 11:03:48

32. [48968](http://github.com/cms-sw/cmssw/pull/48968){:target="_blank"}  from **@mmusich**: deal with `Fake` HLT menus in `ScoutingMuonTriggerAnalyzer` `dqm` created: 2025-09-22 13:53:32 merged: 2025-09-23 20:02:48

33. [48967](http://github.com/cms-sw/cmssw/pull/48967){:target="_blank"}  from **@mkirsano**: Fix memory in case of hepmc3 `simulation` created: 2025-09-22 13:42:39 merged: 2025-09-24 14:15:17

34. [48963](http://github.com/cms-sw/cmssw/pull/48963){:target="_blank"}  from **@missirol**: fix emulation of L1T ZDC EtSums `dqm` `l1` created: 2025-09-20 19:01:06 merged: 2025-09-28 08:34:52

35. [48962](http://github.com/cms-sw/cmssw/pull/48962){:target="_blank"}  from **@CMS-HGCAL**: Update FED Raw Data Dumper tester `daq` created: 2025-09-20 16:10:57 merged: 2025-09-22 08:24:17

36. [48961](http://github.com/cms-sw/cmssw/pull/48961){:target="_blank"}  from **@gartung**: Make Circles plots for resources reported by Module Alloc Monitor service. `core` `operations` created: 2025-09-19 19:23:45 merged: 2025-09-26 15:57:29

37. [48957](http://github.com/cms-sw/cmssw/pull/48957){:target="_blank"}  from **@cms-tsg-storm**: add support for multiple input FEDs in `HLTL1NumberFilter` `hlt` created: 2025-09-19 10:21:31 merged: 2025-09-22 08:26:36

38. [48955](http://github.com/cms-sw/cmssw/pull/48955){:target="_blank"}  from **@bsunanda**: Phase2-hgx364D Correct the material content of the steel cover in the CE-H section `geometry` `upgrade` created: 2025-09-19 10:14:21 merged: 2025-09-21 13:34:25

39. [48951](http://github.com/cms-sw/cmssw/pull/48951){:target="_blank"}  from **@iarspider**: SoftMuonMvaRun3Estimator: use std::abs `reconstruction` `xpog` created: 2025-09-18 08:54:56 merged: 2025-09-19 07:09:25

40. [48950](http://github.com/cms-sw/cmssw/pull/48950){:target="_blank"}  from **@iarspider**: PFAnalyzer.cc: use std::abs `dqm` created: 2025-09-18 07:54:08 merged: 2025-09-23 10:57:55

41. [48949](http://github.com/cms-sw/cmssw/pull/48949){:target="_blank"}  from **@iarspider**: SequentialVertexFitter: use std::abs instead of integer abs `reconstruction` `tracking` created: 2025-09-18 07:47:36 merged: 2025-09-18 20:07:09

42. [48947](http://github.com/cms-sw/cmssw/pull/48947){:target="_blank"}  from **@fwyzard**: Update the compile-time warp size constant for ROCm 7.0 `heterogeneous` created: 2025-09-18 04:55:35 merged: 2025-09-19 07:12:00

43. [48944](http://github.com/cms-sw/cmssw/pull/48944){:target="_blank"}  from **@smorovic**: [DAQ] skip directory creation in read-only discovery mode `daq` created: 2025-09-17 10:44:39 merged: 2025-09-18 12:19:06

44. [48941](http://github.com/cms-sw/cmssw/pull/48941){:target="_blank"}  from **@hqucms**: Update HGCal testbeam relval workflow `reconstruction` created: 2025-09-16 17:24:04 merged: 2025-09-25 11:05:03

45. [48935](http://github.com/cms-sw/cmssw/pull/48935){:target="_blank"}  from @cms-ngt-hlt: [NGT] Add extra NGT scouting track table producer, when using `NANO:**@NGTScoutingVal**` `hlt` created: 2025-09-16 11:58:45 merged: 2025-09-25 11:02:33

46. [48932](http://github.com/cms-sw/cmssw/pull/48932){:target="_blank"}  from **@slava77**: mkfit standalone bin file writer updates: track hit order and phase-2 OT cluster size `reconstruction` `tracking` created: 2025-09-15 18:07:16 merged: 2025-09-16 08:54:51

47. [48931](http://github.com/cms-sw/cmssw/pull/48931){:target="_blank"}  from **@arunhep**: Renaming the GTs for Mini to Mini MC Campaigns (Run2+Run3) `alca` created: 2025-09-15 16:03:37 merged: 2025-09-16 08:54:36

48. [48927](http://github.com/cms-sw/cmssw/pull/48927){:target="_blank"}  from **@cms-ngt-hlt**: CaloCluster forward declaration `hlt` `l1` `reconstruction` `visualization` `simulation` `upgrade` created: 2025-09-15 10:54:24 merged: 2025-09-20 07:39:02

49. [48926](http://github.com/cms-sw/cmssw/pull/48926){:target="_blank"}  from **@Parsifal-2045**: Change job/threads split for Phase-2 HLT timing tests `hlt` created: 2025-09-15 10:41:25 merged: 2025-09-16 08:59:21

50. [48925](http://github.com/cms-sw/cmssw/pull/48925){:target="_blank"}  from **@mmusich**: remove wf 24834.911 `pdmv` `upgrade` created: 2025-09-15 09:46:54 merged: 2025-09-16 08:55:21

51. [48924](http://github.com/cms-sw/cmssw/pull/48924){:target="_blank"}  from **@mmusich**: Trim down `ALCAPROMPT` step in the Prompt Calibration Loop `alca` `trk` created: 2025-09-14 15:46:21 merged: 2025-09-16 08:57:01

52. [48909](http://github.com/cms-sw/cmssw/pull/48909){:target="_blank"}  from **@SegmentLinking**: Reshape LST T3 and T5 building kernels in LST to increase the active threads per warp `reconstruction` `heterogeneous` `tracking` created: 2025-09-12 16:45:14 merged: 2025-09-24 14:15:09

53. [48908](http://github.com/cms-sw/cmssw/pull/48908){:target="_blank"}  from **@Dr15Jones**: Moved Pool based tests from FWCore to IOPool `core` created: 2025-09-12 15:08:23 merged: 2025-09-17 11:12:34

54. [48907](http://github.com/cms-sw/cmssw/pull/48907){:target="_blank"}  from **@archiron**: New Validation/RecoEgamma PF differential Isolation Electrons plots V1 `dqm` created: 2025-09-12 13:29:36 merged: 2025-10-02 19:26:52

55. [48906](http://github.com/cms-sw/cmssw/pull/48906){:target="_blank"}  from **@wouf**: HI GENs fix for rnd seed issue #48814 `generators` created: 2025-09-12 07:59:35 merged: 2025-09-25 11:11:47

56. [48903](http://github.com/cms-sw/cmssw/pull/48903){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `15_0_X` (10/N)  [`16_0_X`]  `hlt` created: 2025-09-12 07:52:57 merged: 2025-09-12 14:04:45

57. [48902](http://github.com/cms-sw/cmssw/pull/48902){:target="_blank"}  from **@Dr15Jones**: Remove unused DetSetVector test in FWCore/Integration `core` created: 2025-09-11 19:01:41 merged: 2025-09-12 20:25:46

58. [48895](http://github.com/cms-sw/cmssw/pull/48895){:target="_blank"}  from **@CMS-HGCAL**: Fix to HGCAL unpacker: Move from FEDRawDataCollection to RawDataBuffer  `reconstruction` `upgrade` created: 2025-09-11 08:29:05 merged: 2025-09-24 05:59:14

59. [48894](http://github.com/cms-sw/cmssw/pull/48894){:target="_blank"}  from **@mmusich**: TkAlignment all-in-one validation: use `DiMuonMassProfiles` for Z   merge step `alca` `trk` created: 2025-09-10 14:47:39 merged: 2025-09-11 08:30:04

60. [48893](http://github.com/cms-sw/cmssw/pull/48893){:target="_blank"}  from **@Dr15Jones**: Remove vebose output in concurrency test `core` created: 2025-09-10 14:36:48 merged: 2025-09-11 18:01:12

61. [48890](http://github.com/cms-sw/cmssw/pull/48890){:target="_blank"}  from **@mmusich**: silence `SiPixelRawToCluster` verbose ROC and FED error printouts (again) `reconstruction` `trk` created: 2025-09-10 13:36:03 merged: 2025-09-10 21:23:53

62. [48886](http://github.com/cms-sw/cmssw/pull/48886){:target="_blank"}  from **@mmusich**: Adjust `trackingIters01` process modifier usage to be functional in Run3 scenarios `reconstruction` `tracking` created: 2025-09-10 09:22:19 merged: 2025-09-14 11:23:18

63. [48884](http://github.com/cms-sw/cmssw/pull/48884){:target="_blank"}  from **@stahlleiton**: Add fill description for PFCandidateFwdPtrProducer `reconstruction` created: 2025-09-10 04:49:09 merged: 2025-09-11 18:02:34

64. [48881](http://github.com/cms-sw/cmssw/pull/48881){:target="_blank"}  from **@slava77**: revive support for HLT in the tracking ntuple `dqm` `reconstruction` `tracking` created: 2025-09-09 15:56:55 merged: 2025-09-18 20:08:28

65. [48874](http://github.com/cms-sw/cmssw/pull/48874){:target="_blank"}  from **@gartung**: PerfTools/AllocMonitor: add c++ types for EDModules and ESModules to json output of scripts/edmModuleAllocMonitorAnalyze.py `core` created: 2025-09-08 16:10:17 merged: 2025-09-12 16:19:56

66. [48862](http://github.com/cms-sw/cmssw/pull/48862){:target="_blank"}  from **@AuroraPerego**: Add vector of tracks to TICL tracksters and candidates and add other validation plots `dqm` `reconstruction` `upgrade` created: 2025-09-08 13:45:18 merged: 2025-09-30 18:10:53

67. [48860](http://github.com/cms-sw/cmssw/pull/48860){:target="_blank"}  from **@mseidel42**: btvNano: fix link between GenCands and decayed hadrons `xpog` created: 2025-09-08 12:08:46 merged: 2025-09-09 07:45:50

68. [48859](http://github.com/cms-sw/cmssw/pull/48859){:target="_blank"}  from **@smorovic**: [DAQ] HLT test-stand conversion job patches `daq` created: 2025-09-08 08:44:17 merged: 2025-09-08 17:33:45

69. [48858](http://github.com/cms-sw/cmssw/pull/48858){:target="_blank"}  from **@mmusich**: add `fillDescriptions` to several plugins used at HLT (6/N) `alca` `geometry` `reconstruction` `tracking` `trk` created: 2025-09-08 08:15:20 merged: 2025-09-08 17:32:07

70. [48857](http://github.com/cms-sw/cmssw/pull/48857){:target="_blank"}  from **@Electricks94**: Move MultiVectorManager to DataFormats/Common and address discussion from #48826 and rename it to MultiSpan `core` `dqm` `reconstruction` `simulation` `upgrade` created: 2025-09-05 22:32:29 merged: 2025-09-30 07:34:56

71. [48856](http://github.com/cms-sw/cmssw/pull/48856){:target="_blank"}  from **@Dr15Jones**: Fix assertion failure in ProductRegistry merging `core` created: 2025-09-05 20:36:28 merged: 2025-09-06 08:53:46

72. [48852](http://github.com/cms-sw/cmssw/pull/48852){:target="_blank"}  from **@nancymarinelli**: Bug fixing in the RecoEgamma/plugins/PhotonValidator.cc `dqm` created: 2025-09-05 15:33:17 merged: 2025-09-11 07:23:54

73. [48851](http://github.com/cms-sw/cmssw/pull/48851){:target="_blank"}  from **@waredjeb**: TICLv5 Adjust Linking step `hlt` `reconstruction` `pdmv` `upgrade` created: 2025-09-05 11:37:05 merged: 2025-09-10 12:27:44

74. [48850](http://github.com/cms-sw/cmssw/pull/48850){:target="_blank"}  from **@tihsu99**: Include scouting EGM in Online DQM stream `dqm` `hlt` created: 2025-09-05 11:35:30 merged: 2025-09-09 15:35:43

75. [48846](http://github.com/cms-sw/cmssw/pull/48846){:target="_blank"}  from **@ctdax**: Fixed outgoing R-hadron check for stop R-hadrons `simulation` created: 2025-09-04 19:13:42 merged: 2025-09-06 08:53:01

76. [48841](http://github.com/cms-sw/cmssw/pull/48841){:target="_blank"}  from **@jo100sun**: GEM TnP efficiency bugfix in the OfflineDQM `dqm` created: 2025-09-04 05:28:59 merged: 2025-09-08 17:35:00

77. [48840](http://github.com/cms-sw/cmssw/pull/48840){:target="_blank"}  from **@Dr15Jones**: Remove file static regex from FriendlyName.cc `core` created: 2025-09-03 20:46:35 merged: 2025-09-05 08:20:39

78. [48839](http://github.com/cms-sw/cmssw/pull/48839){:target="_blank"}  from **@Dr15Jones**: Removed FWCore/Utilities dependency on PerfTools/AllocMonitor `core` created: 2025-09-03 19:37:39 merged: 2025-09-06 14:13:37

79. [48835](http://github.com/cms-sw/cmssw/pull/48835){:target="_blank"}  from **@SegmentLinking**: LST: introduce code to write object data in standalone and fix memory leak `reconstruction` `heterogeneous` `tracking` created: 2025-09-03 13:29:48 merged: 2025-09-16 08:59:07

80. [48833](http://github.com/cms-sw/cmssw/pull/48833){:target="_blank"}  from **@ram1123**: Fix documentation for SoftActivityJetNjets parameters `xpog` created: 2025-09-02 23:49:01 merged: 2025-09-09 07:44:20

81. [48830](http://github.com/cms-sw/cmssw/pull/48830){:target="_blank"}  from **@cericeci**: Fixed bug on longitudinal momentum computation for SUEP constituents `generators` created: 2025-09-02 12:52:42 merged: 2025-09-11 18:04:06

82. [48828](http://github.com/cms-sw/cmssw/pull/48828){:target="_blank"}  from **@akritkbehera**: [PhysicsTools/TensorFlowAOT/testAOTTools] Fix unknown-pc-linux on EL10 by replacing platform.processor() with platform.machine() `ml` created: 2025-09-02 08:47:54 merged: 2025-09-05 08:17:17

83. [48827](http://github.com/cms-sw/cmssw/pull/48827){:target="_blank"}  from **@mmusich**: add a unit tests for running `GRun`, `HIon`, `Special` in FULL output mode `hlt` created: 2025-09-01 15:09:20 merged: 2025-09-03 08:13:21

84. [48826](http://github.com/cms-sw/cmssw/pull/48826){:target="_blank"}  from **@waredjeb**: Moving MultiVectorManager.h under DataFormats/HGCalReco `dqm` `reconstruction` `simulation` `upgrade` created: 2025-09-01 12:09:22 merged: 2025-09-03 11:23:12

85. [48820](http://github.com/cms-sw/cmssw/pull/48820){:target="_blank"}  from **@mmusich**: fix `GeneralPurposeTrackAnalyzer` for `StreamHLTMonitor` events `alca` `trk` created: 2025-08-29 12:20:39 merged: 2025-08-30 08:14:12

86. [48816](http://github.com/cms-sw/cmssw/pull/48816){:target="_blank"}  from **@makortel**: Remove SwitchProducer and ConditionalTask from the framework `core` `dqm` `hlt` created: 2025-08-28 14:39:25 merged: 2025-09-17 11:10:44

87. [48813](http://github.com/cms-sw/cmssw/pull/48813){:target="_blank"}  from **@RobertJWard**: [L1T] Update P2GT Emulator with latest IDs and Scalings from Annual Review 2025 (Phase 2) `l1` created: 2025-08-27 13:39:28 merged: 2025-09-28 08:37:22

88. [48812](http://github.com/cms-sw/cmssw/pull/48812){:target="_blank"}  from **@CMS-HGCAL**: Fix to unpacker / module locator for HGCAL `alca` `daq` `geometry` `reconstruction` `simulation` `db` `upgrade` created: 2025-08-27 12:55:31 merged: 2025-08-29 06:18:16

89. [48809](http://github.com/cms-sw/cmssw/pull/48809){:target="_blank"}  from **@mmusich**: add 2025 to the allowed 0T pp collisions workflows (.24 modifier) `pdmv` `upgrade` created: 2025-08-27 08:53:48 merged: 2025-08-27 18:15:14

90. [48808](http://github.com/cms-sw/cmssw/pull/48808){:target="_blank"}  from **@iarspider**: Disable testTables and import-tables tests for ASAN IBs `analysis` created: 2025-08-27 07:54:10 merged: 2025-08-30 08:13:52

91. [48807](http://github.com/cms-sw/cmssw/pull/48807){:target="_blank"}  from **@Dr15Jones**: Determine non-process name lookups at begin job `analysis` `core` `generators` `simulation` created: 2025-08-26 18:52:28 merged: 2025-09-16 08:56:13

92. [48806](http://github.com/cms-sw/cmssw/pull/48806){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Rename HLT DQM jet validation folder `dqm` created: 2025-08-26 15:59:24 merged: 2025-08-27 18:14:50

93. [48805](http://github.com/cms-sw/cmssw/pull/48805){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Bug fix for JetTester::etaInfo `dqm` created: 2025-08-26 15:20:20 merged: 2025-08-27 18:14:34

94. [48804](http://github.com/cms-sw/cmssw/pull/48804){:target="_blank"}  from **@Alejandro1400**: LHCInfoAnalyzer Tests `db` created: 2025-08-26 14:50:09 merged: 2025-09-08 17:31:35

95. [48801](http://github.com/cms-sw/cmssw/pull/48801){:target="_blank"}  from **@waredjeb**: Add ZEE_14 workflows to TICLv5 procModifier `pdmv` `upgrade` created: 2025-08-26 13:04:07 merged: 2025-08-27 08:08:42

96. [48800](http://github.com/cms-sw/cmssw/pull/48800){:target="_blank"}  from **@bsunanda**: Phase2-hgx364A Changes made to resolve an issue in making tests for overlap checks `simulation` created: 2025-08-26 10:48:33 merged: 2025-08-29 13:07:19

97. [48796](http://github.com/cms-sw/cmssw/pull/48796){:target="_blank"}  from **@CMSTrackerDPG**: Enabling SiPixel good edge algorithm from 2025 onward `operations` created: 2025-08-25 20:40:15 merged: 2025-08-26 15:16:18

98. [48794](http://github.com/cms-sw/cmssw/pull/48794){:target="_blank"}  from **@wddgit**: Add comments to ProcessBlock test file `core` created: 2025-08-25 20:01:06 merged: 2025-08-27 05:22:33

99. [48793](http://github.com/cms-sw/cmssw/pull/48793){:target="_blank"}  from **@asavincms**: L1T ZS L1Calo and hiZDC, update of CaloParamsHelperO2O.h `l1` created: 2025-08-25 15:14:17 merged: 2025-08-27 05:22:45

100. [48792](http://github.com/cms-sw/cmssw/pull/48792){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Bug fix for fakerate_vertcount_fwdneg `dqm` `tracking` created: 2025-08-25 15:03:01 merged: 2025-08-27 18:15:27

101. [48791](http://github.com/cms-sw/cmssw/pull/48791){:target="_blank"}  from **@stahlleiton**: Increase electron PF maxHcalE in PbPb eras `reconstruction` created: 2025-08-25 14:07:45 merged: 2025-08-27 16:01:57

102. [48789](http://github.com/cms-sw/cmssw/pull/48789){:target="_blank"}  from **@jprendi**: Fixing minor error in Scouting DQM module `dqm` `hlt` created: 2025-08-25 12:28:42 merged: 2025-08-27 18:16:34

103. [48788](http://github.com/cms-sw/cmssw/pull/48788){:target="_blank"}  from **@cms-tsg-storm**: update menu used in `test_hltMenuContentToCSVs` `hlt` created: 2025-08-23 13:44:43 merged: 2025-08-24 08:34:29

104. [48787](http://github.com/cms-sw/cmssw/pull/48787){:target="_blank"}  from **@wddgit**: Fix corner case in processingOrderMerge `core` created: 2025-08-22 20:27:35 merged: 2025-08-26 06:58:22

105. [48786](http://github.com/cms-sw/cmssw/pull/48786){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Jet Validation for Phase-2 HLT: Part 2 `dqm` created: 2025-08-22 16:45:23 merged: 2025-08-27 18:13:56

106. [48784](http://github.com/cms-sw/cmssw/pull/48784){:target="_blank"}  from **@mmusich**: Switch `addOnTests.py` script from `getopt` to `argparse` `core` created: 2025-08-22 14:05:48 merged: 2025-08-26 06:57:42

107. [48783](http://github.com/cms-sw/cmssw/pull/48783){:target="_blank"}  from **@makortel**: Extend schema evolution test to cover splitLevel 0 and 99 `core` created: 2025-08-22 13:54:10 merged: 2025-08-28 08:19:09

108. [48779](http://github.com/cms-sw/cmssw/pull/48779){:target="_blank"}  from **@Dr15Jones**: Add algorithm include to fix gcc14 build `core` created: 2025-08-21 15:26:07 merged: 2025-08-21 21:41:12

109. [48778](http://github.com/cms-sw/cmssw/pull/48778){:target="_blank"}  from **@makortel**: Extend `cmsTraceFunction` test to `putenv()` and `--abort` `core` created: 2025-08-21 14:08:00 merged: 2025-09-20 07:38:41

110. [48775](http://github.com/cms-sw/cmssw/pull/48775){:target="_blank"}  from **@patinkaew**: ScoutingNano: Update skipEventsWithoutScouting to include new ScoutingPF0,ScoutingPF1 datasets `xpog` created: 2025-08-21 09:03:43 merged: 2025-08-25 11:25:30

111. [48774](http://github.com/cms-sw/cmssw/pull/48774){:target="_blank"}  from **@Parsifal-2045**: Add support for `{pre,post}ModuleEventDelayedGet` signals to the `FastTimerService` `hlt` created: 2025-08-21 09:02:37 merged: 2025-08-29 06:18:05

112. [48773](http://github.com/cms-sw/cmssw/pull/48773){:target="_blank"}  from **@dan131riley**: Phase2TrackerMonitorDigi: initialize MonitorElement pointers `dqm` `trk` created: 2025-08-20 20:32:24 merged: 2025-08-23 07:00:43

113. [48771](http://github.com/cms-sw/cmssw/pull/48771){:target="_blank"}  from **@linacre**: DemonstratorTools: make TMUX slice staggering optional, and disable it in GTTFileWriter `l1` created: 2025-08-20 17:18:21 merged: 2025-09-18 12:18:46

114. [48770](http://github.com/cms-sw/cmssw/pull/48770){:target="_blank"}  from **@stahlleiton**: Update low pT egamma regression in 2025 UPC era `reconstruction` `pdmv` `upgrade` created: 2025-08-20 16:24:03 merged: 2025-08-26 06:57:31

115. [48769](http://github.com/cms-sw/cmssw/pull/48769){:target="_blank"}  from **@stahlleiton**: Increase electron H/E threshold in PbPb eras `reconstruction` `egamma` created: 2025-08-20 15:22:01 merged: 2025-08-20 19:03:06

116. [48768](http://github.com/cms-sw/cmssw/pull/48768){:target="_blank"}  from **@makortel**: Remove SwitchProducerCUDA `heterogeneous` created: 2025-08-20 13:50:44 merged: 2025-08-23 07:01:39

117. [48767](http://github.com/cms-sw/cmssw/pull/48767){:target="_blank"}  from **@Dr15Jones**: Require that process order be consistent when merging files `core` created: 2025-08-19 18:28:12 merged: 2025-08-20 19:02:28

118. [48764](http://github.com/cms-sw/cmssw/pull/48764){:target="_blank"}  from **@dgaytanv**: [SIM] added doFineCalo_ variable definition to Phase2SteppingAction `simulation` created: 2025-08-19 11:51:28 merged: 2025-08-20 19:01:55

119. [48763](http://github.com/cms-sw/cmssw/pull/48763){:target="_blank"}  from **@cms-tsg-storm**: Improve HLT Scouting DataFormat event content handling in derived datasets `hlt` `operations` created: 2025-08-19 09:51:43 merged: 2025-08-19 16:40:42

120. [48762](http://github.com/cms-sw/cmssw/pull/48762){:target="_blank"}  from **@iarspider**: [DQM/SiPixelMonitorRawData] Fix 'Called C++ object pointer is null' `dqm` `trk` created: 2025-08-19 08:48:38 merged: 2025-08-19 16:41:26

121. [48761](http://github.com/cms-sw/cmssw/pull/48761){:target="_blank"}  from **@iarspider**: [CondTools/RunInfo] Use edm::isNotFinite instead of std::isnan `db` created: 2025-08-19 08:32:55 merged: 2025-08-19 16:41:08

122. [48760](http://github.com/cms-sw/cmssw/pull/48760){:target="_blank"}  from **@iarspider**: [CommonTools/TrackerMap] Use edm::isNotFinite instead of std::isnan `dqm` `reconstruction` `trk` created: 2025-08-19 08:28:24 merged: 2025-08-20 19:02:40

123. [48759](http://github.com/cms-sw/cmssw/pull/48759){:target="_blank"}  from **@bsunanda**: Run3-alca260 modify some of the features for comparision plots between  sources of  AlCaRaw files `alca` created: 2025-08-19 04:08:48 merged: 2025-08-19 16:39:36

124. [48758](http://github.com/cms-sw/cmssw/pull/48758){:target="_blank"}  from **@bsunanda**: Phase2-hgx364 Add 2 more workflows for HGCal v19 (with no creation of geometry tree beyond the wafers; one with no gaps among the silicon modules) `pdmv` `upgrade` created: 2025-08-19 03:41:39 merged: 2025-08-26 06:56:06

125. [48756](http://github.com/cms-sw/cmssw/pull/48756){:target="_blank"}  from **@mmusich**: fix ticl barrel in ph-2 HLT configuration `hlt` created: 2025-08-18 10:59:14 merged: 2025-08-20 19:03:31

126. [48754](http://github.com/cms-sw/cmssw/pull/48754){:target="_blank"}  from **@iarspider**: [EventFilter/Utilities] Fix clang static analyzer warning `daq` created: 2025-08-18 08:49:09 merged: 2025-08-18 13:06:17

127. [48753](http://github.com/cms-sw/cmssw/pull/48753){:target="_blank"}  from **@asavincms**: Revert "L1Calo , fix Zero Suppression  producer position to get it consistent with o2o definition" `l1` created: 2025-08-16 15:58:00 merged: 2025-08-18 13:06:58

128. [48750](http://github.com/cms-sw/cmssw/pull/48750){:target="_blank"}  from **@alexandertuna**: Update Mixing.py to include 100_BX_25ns_m3p3 `operations` created: 2025-08-15 23:02:43 merged: 2025-08-21 21:42:46

129. [48747](http://github.com/cms-sw/cmssw/pull/48747){:target="_blank"}  from **@kyungminparkdrums**: Deprecate PU trend plot in offline DQM for ECAL `dqm` created: 2025-08-15 16:05:20 merged: 2025-08-23 07:00:28

130. [48746](http://github.com/cms-sw/cmssw/pull/48746){:target="_blank"}  from **@TomasKello**: Fix PVmerge to store results in EOS `alca` `trk` created: 2025-08-15 16:02:50 merged: 2025-08-19 07:12:30

131. [48745](http://github.com/cms-sw/cmssw/pull/48745){:target="_blank"}  from **@cms-ngt-hlt**: Met Validation for Phase-2 HLT `dqm` created: 2025-08-15 15:23:10 merged: 2025-10-03 12:44:53

132. [48744](http://github.com/cms-sw/cmssw/pull/48744){:target="_blank"}  from **@slava77**: LST: clone SerialSync using makeSerialClone in track-to-track setup `reconstruction` `heterogeneous` `tracking` created: 2025-08-15 14:42:55 merged: 2025-08-16 08:53:14

133. [48742](http://github.com/cms-sw/cmssw/pull/48742){:target="_blank"}  from **@denizsun**: [HCAL-DQM] Fix missing FED 1136 (ZDC) in Hcal/RawTask/SummaryvsLS plot `dqm` created: 2025-08-15 10:05:19 merged: 2025-08-21 14:55:03

134. [48740](http://github.com/cms-sw/cmssw/pull/48740){:target="_blank"}  from **@Dr15Jones**: Optimize 'no process' data product lookup `core` created: 2025-08-14 18:27:12 merged: 2025-08-18 18:06:13

135. [48739](http://github.com/cms-sw/cmssw/pull/48739){:target="_blank"}  from **@civanch**: [SIM] added test of geometry and improved run time info `simulation` created: 2025-08-14 14:05:35 merged: 2025-08-15 08:51:01

136. [48738](http://github.com/cms-sw/cmssw/pull/48738){:target="_blank"}  from **@agrubercms**: New HLTFilter to read out L1P2GT tau candidates at Phase-2 HLT `hlt` created: 2025-08-14 13:29:54 merged: 2025-08-20 18:53:16

137. [48735](http://github.com/cms-sw/cmssw/pull/48735){:target="_blank"}  from **@jo100sun**: GEM Eta-partition id check in Muon-Rechit matching `reconstruction` created: 2025-08-14 05:06:18 merged: 2025-08-15 08:47:56

138. [48734](http://github.com/cms-sw/cmssw/pull/48734){:target="_blank"}  from **@CMSTrackerDPG**: Digi Morphing for HLT `reconstruction` `heterogeneous` `trk` created: 2025-08-14 04:23:03 merged: 2025-09-05 15:24:24

139. [48731](http://github.com/cms-sw/cmssw/pull/48731){:target="_blank"}  from **@mmusich**: Technical follow ups to #48701 `simulation` `trk` created: 2025-08-13 08:07:53 merged: 2025-08-13 15:59:59

140. [48730](http://github.com/cms-sw/cmssw/pull/48730){:target="_blank"}  from **@kpedro88**: add and use isUninitialized() accessor for InputTag `alca` `core` `dqm` `hlt` `l1` `reconstruction` `simulation` `tracking` `trk` created: 2025-08-12 21:08:53 merged: 2025-08-18 16:39:41

141. [48728](http://github.com/cms-sw/cmssw/pull/48728){:target="_blank"}  from **@stahlleiton**: Add tracker-driven electrons in PbPb eras `reconstruction` `tracking` `egamma` created: 2025-08-12 18:59:09 merged: 2025-08-14 07:31:12

142. [48726](http://github.com/cms-sw/cmssw/pull/48726){:target="_blank"}  from **@Dr15Jones**: Additional debugging for testFWCoreConcurrency `core` created: 2025-08-12 14:10:13 merged: 2025-08-13 06:21:57

143. [48725](http://github.com/cms-sw/cmssw/pull/48725){:target="_blank"}  from **@Moanwar**: Update batch size in ONNX interface `ml` created: 2025-08-12 10:57:53 merged: 2025-09-05 08:16:48

144. [48722](http://github.com/cms-sw/cmssw/pull/48722){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Jet Validation for Phase-2 HLT `dqm` created: 2025-08-12 08:36:02 merged: 2025-08-23 06:59:49

145. [48721](http://github.com/cms-sw/cmssw/pull/48721){:target="_blank"}  from **@mmusich**: miscellaneous updates to `hltPhase2UpgradeIntegrationTests` `hlt` created: 2025-08-11 20:14:12 merged: 2025-08-12 14:40:57

146. [48720](http://github.com/cms-sw/cmssw/pull/48720){:target="_blank"}  from **@makortel**: Replace deprecated constants for compression level in `OrbitNanoAODOutputModule` `daq` created: 2025-08-11 19:17:13 merged: 2025-08-12 14:41:20

147. [48718](http://github.com/cms-sw/cmssw/pull/48718){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `15_0_X` (9/N)  [`15_1_X`]  `hlt` `operations` created: 2025-08-11 17:47:36 merged: 2025-08-12 14:40:08

148. [48716](http://github.com/cms-sw/cmssw/pull/48716){:target="_blank"}  from **@akritkbehera**: Replacing"TMath.h" usage in favor of CMath `alca` `dqm` `l1` `visualization` `simulation` `upgrade` `trk` created: 2025-08-11 11:29:37 merged: 2025-08-15 08:50:41

149. [48714](http://github.com/cms-sw/cmssw/pull/48714){:target="_blank"}  from **@smuzaffar**: [GDB] Added unit tests for gdb and running cmsTraceFunction `core` created: 2025-08-11 10:20:42 merged: 2025-08-13 16:01:28

150. [48712](http://github.com/cms-sw/cmssw/pull/48712){:target="_blank"}  from **@Dr15Jones**: prefetch data for RandomNumberGenerator `core` created: 2025-08-10 21:10:30 merged: 2025-08-12 14:40:45

151. [48711](http://github.com/cms-sw/cmssw/pull/48711){:target="_blank"}  from **@leobeltra**: Updated README `heterogeneous` created: 2025-08-10 17:17:50 merged: 2025-08-13 06:21:05

152. [48707](http://github.com/cms-sw/cmssw/pull/48707){:target="_blank"}  from **@cms-ngt-hlt**: Update `ScoutingCollectionMonitor` to allow monitoring of ECal and HCal PF rechits `dqm` `hlt` created: 2025-08-08 19:07:08 merged: 2025-08-12 15:40:11

153. [48706](http://github.com/cms-sw/cmssw/pull/48706){:target="_blank"}  from **@slava77**: HLT:75e33_trackingOnly and a related reference workflow `hlt` `pdmv` `upgrade` created: 2025-08-08 16:15:10 merged: 2025-08-19 07:11:51

154. [48705](http://github.com/cms-sw/cmssw/pull/48705){:target="_blank"}  from **@mmusich**: protect online DQM clients when running in `inputFiles` mode against meaningless customizations `dqm` created: 2025-08-08 15:22:45 merged: 2025-08-21 15:47:44

155. [48704](http://github.com/cms-sw/cmssw/pull/48704){:target="_blank"}  from **@smorovic**: [DAQ] DAQSource read-only mode and processing specific lumis in file discovery mode (Phase-2) `daq` created: 2025-08-08 15:16:32 merged: 2025-08-09 11:46:59

156. [48703](http://github.com/cms-sw/cmssw/pull/48703){:target="_blank"}  from **@makortel**: Remove the use of `SwitchProducerCUDA` outside HeterogeneousCore `alca` `dqm` `l1` `operations` `reconstruction` `simulation` `heterogeneous` `trk` created: 2025-08-08 14:36:13 merged: 2025-08-19 16:42:38

157. [48701](http://github.com/cms-sw/cmssw/pull/48701){:target="_blank"}  from **@mmasciov**: Adapt ClusterTPAssociationProducer to deal with two strip cluster product IDs `simulation` `dqm` `tracking` `trk` created: 2025-08-08 14:04:58 merged: 2025-08-12 19:38:56

158. [48699](http://github.com/cms-sw/cmssw/pull/48699){:target="_blank"}  from **@bsunanda**: Phase2-hgx364 Take into account that the flat file information refers to z=-1 wafers `geometry` `upgrade` created: 2025-08-08 01:59:47 merged: 2025-08-18 06:49:21

159. [48698](http://github.com/cms-sw/cmssw/pull/48698){:target="_blank"}  from **@SegmentLinking**: Dynamic Memory Caps for LS, T3, T5 Objects in LST `reconstruction` `heterogeneous` `tracking` created: 2025-08-07 22:07:38 merged: 2025-08-27 18:13:20

160. [48697](http://github.com/cms-sw/cmssw/pull/48697){:target="_blank"}  from **@stahlleiton**: Fix relvals 138.1 and 138.2 `pdmv` `upgrade` created: 2025-08-07 21:14:11 merged: 2025-08-13 06:20:54

161. [48696](http://github.com/cms-sw/cmssw/pull/48696){:target="_blank"}  from **@Dr15Jones**: RandomNumberGeneratorService properly does consumes `core` `simulation` created: 2025-08-07 19:45:09 merged: 2025-08-09 11:46:35

162. [48695](http://github.com/cms-sw/cmssw/pull/48695){:target="_blank"}  from **@mmusich**: add ageing customization to `ph2_hlt` workflows `simulation` `pdmv` `upgrade` created: 2025-08-07 17:06:18 merged: 2025-08-12 15:37:51

163. [48694](http://github.com/cms-sw/cmssw/pull/48694){:target="_blank"}  from **@makortel**: Add missing dictionary to `SimDataFormats/Associations` `core` `reconstruction` `simulation` `upgrade` created: 2025-08-07 16:46:41 merged: 2025-08-09 11:46:15

164. [48691](http://github.com/cms-sw/cmssw/pull/48691){:target="_blank"}  from **@makortel**: Fix tests following `edmProvDump` changes `core` created: 2025-08-07 13:36:00 merged: 2025-08-08 10:16:24

165. [48690](http://github.com/cms-sw/cmssw/pull/48690){:target="_blank"}  from **@stahlleiton**: Add dEdx lfit to PbPb eras `operations` `reconstruction` `xpog` created: 2025-08-07 08:35:28 merged: 2025-08-11 11:23:32

166. [48689](http://github.com/cms-sw/cmssw/pull/48689){:target="_blank"}  from **@makortel**: Pass type information only via `edm::TypeID` in `ProductDescription` constructor `generators` `core` `daq` created: 2025-08-06 22:31:36 merged: 2025-08-27 05:25:22

167. [48688](http://github.com/cms-sw/cmssw/pull/48688){:target="_blank"}  from **@Dr15Jones**: Added firstIf to chaining task system `core` created: 2025-08-06 17:01:09 merged: 2025-08-07 16:17:00

168. [48687](http://github.com/cms-sw/cmssw/pull/48687){:target="_blank"}  from **@bfonta**: Add a relval test for the NGT scouting menu with multiple process modifiers `pdmv` `upgrade` created: 2025-08-06 16:11:12 merged: 2025-08-26 06:59:06

169. [48686](http://github.com/cms-sw/cmssw/pull/48686){:target="_blank"}  from **@hqucms**: Remove Run2 procModifier from Run3 ReMINI relval workflows and fix BTV MINIAOD DQM `dqm` `pdmv` `upgrade` `tracking` created: 2025-08-06 15:31:24 merged: 2025-08-20 18:53:00

170. [48684](http://github.com/cms-sw/cmssw/pull/48684){:target="_blank"}  from **@mmasciov**: Update of strip overlap check for different product ID `reconstruction` `tracking` created: 2025-08-06 15:19:38 merged: 2025-08-08 10:18:47

171. [48682](http://github.com/cms-sw/cmssw/pull/48682){:target="_blank"}  from **@Dr15Jones**: Cache EDGetToken in InputTag `alca` `core` `dqm` `trk` created: 2025-08-06 14:30:24 merged: 2025-08-13 16:00:38

172. [48681](http://github.com/cms-sw/cmssw/pull/48681){:target="_blank"}  from **@stahlleiton**: Fix use of UPC era modifiers `l1` `operations` `reconstruction` created: 2025-08-06 13:42:47 merged: 2025-08-09 11:46:00

173. [48679](http://github.com/cms-sw/cmssw/pull/48679){:target="_blank"}  from **@lwang046**: HCALDQM: Revise of calibration tasks `dqm` created: 2025-08-06 12:29:34 merged: 2025-08-21 14:53:30

174. [48678](http://github.com/cms-sw/cmssw/pull/48678){:target="_blank"}  from **@cms-AlCaDB**: LHCInfo* printing utilities  `db` created: 2025-08-06 10:34:10 merged: 2025-08-19 16:38:02

175. [48674](http://github.com/cms-sw/cmssw/pull/48674){:target="_blank"}  from **@kk428**: LST: Modifying LST to create efficiency plots for jets `reconstruction` `tracking` created: 2025-08-05 17:03:39 merged: 2025-08-07 16:17:21

176. [48673](http://github.com/cms-sw/cmssw/pull/48673){:target="_blank"}  from **@bfonta**: Include the HLT menu in the name of the output directory. `hlt` created: 2025-08-05 16:56:27 merged: 2025-08-06 17:32:05

177. [48671](http://github.com/cms-sw/cmssw/pull/48671){:target="_blank"}  from **@bsunanda**: Phase2-hgx363Y Add validation for he V19 version of HGCal `dqm` created: 2025-08-05 09:08:27 merged: 2025-08-18 06:48:52

178. [48669](http://github.com/cms-sw/cmssw/pull/48669){:target="_blank"}  from **@makortel**: Add missing dictionaries to `DataFormats/L1TrackTrigger` `l1` `upgrade` created: 2025-08-04 22:05:37 merged: 2025-08-12 14:41:55

179. [48668](http://github.com/cms-sw/cmssw/pull/48668){:target="_blank"}  from **@makortel**: Always initialize `PortableHostObject::product_` `heterogeneous` created: 2025-08-04 19:40:27 merged: 2025-08-13 06:21:36

180. [48665](http://github.com/cms-sw/cmssw/pull/48665){:target="_blank"}  from **@civanch**: [SIM] Added Geant4 mag field stepper type `simulation` created: 2025-08-04 12:08:27 merged: 2025-08-05 18:11:32

181. [48664](http://github.com/cms-sw/cmssw/pull/48664){:target="_blank"}  from **@mmusich**: allow the possibility to run different flavours of HLT menu in `hltPhase2UpgradeIntegrationTests` `hlt` created: 2025-08-04 09:50:59 merged: 2025-08-04 19:47:19

182. [48663](http://github.com/cms-sw/cmssw/pull/48663){:target="_blank"}  from **@stahlleiton**: Raise ECAL thresholds for beam splashes `operations` `reconstruction` `pdmv` `upgrade` created: 2025-08-03 19:58:21 merged: 2025-09-02 14:39:54

183. [48662](http://github.com/cms-sw/cmssw/pull/48662){:target="_blank"}  from **@mmusich**: Update `TestRun3ScoutingFormats.sh` for `CMSSW_15_1_0_pre5` updates `core` created: 2025-08-03 14:54:51 merged: 2025-08-04 18:11:49

184. [48660](http://github.com/cms-sw/cmssw/pull/48660){:target="_blank"}  from **@battibass**: Muon DPG custom-NANO updates enabling additional studies `pdmv` `upgrade` `xpog` created: 2025-08-01 12:58:07 merged: 2025-08-13 20:52:23

185. [48659](http://github.com/cms-sw/cmssw/pull/48659){:target="_blank"}  from **@slava77**: LST: allow OT tracker hits on the input seeds `reconstruction` `tracking` created: 2025-08-01 12:48:15 merged: 2025-08-04 18:12:53

186. [48658](http://github.com/cms-sw/cmssw/pull/48658){:target="_blank"}  from **@asavincms**: L1Calo , fix Zero Suppression  producer position to get it consistent with o2o definition `l1` created: 2025-08-01 12:16:18 merged: 2025-08-08 10:16:40

187. [48657](http://github.com/cms-sw/cmssw/pull/48657){:target="_blank"}  from **@bsunanda**: Run3-alca259 Add a new macro which can do a double-sided Crystal Ball fit using RooFit facility `alca` created: 2025-08-01 10:17:00 merged: 2025-08-18 06:48:37

188. [48656](http://github.com/cms-sw/cmssw/pull/48656){:target="_blank"}  from **@makortel**: Avoid relying on header parsing in ProductRegistry unit test `core` created: 2025-07-31 22:15:41 merged: 2025-08-04 19:46:12

189. [48654](http://github.com/cms-sw/cmssw/pull/48654){:target="_blank"}  from **@stahlleiton**: Enable secondary vertices in PbPb eras `reconstruction` `tracking` created: 2025-07-31 12:53:50 merged: 2025-08-12 14:18:49

190. [48648](http://github.com/cms-sw/cmssw/pull/48648){:target="_blank"}  from **@CMS-HGCAL**: [HGCAL] Add ECON-T indexer for reading out TPG data `alca` `geometry` `reconstruction` `simulation` `db` `upgrade` `heterogeneous` created: 2025-07-29 14:05:01 merged: 2025-09-25 11:16:47

191. [48645](http://github.com/cms-sw/cmssw/pull/48645){:target="_blank"}  from **@alja**: [fireworks] Add edm::TypeWithDict validity check in hasMemberTVirtualCollectionProxy `visualization` created: 2025-07-29 02:44:58 merged: 2025-08-04 18:21:53

192. [48638](http://github.com/cms-sw/cmssw/pull/48638){:target="_blank"}  from **@felix-phy**: added new miniAODDQMBtagOnly sequence to OfflineDQM `dqm` created: 2025-07-28 14:49:18 merged: 2025-08-21 14:53:43

193. [48635](http://github.com/cms-sw/cmssw/pull/48635){:target="_blank"}  from **@stahlleiton**: Add access to dEdx error `fastsim` `operations` `reconstruction` `pdmv` `upgrade` `xpog` `tracking` created: 2025-07-27 15:33:18 merged: 2025-08-05 11:49:48

194. [48634](http://github.com/cms-sw/cmssw/pull/48634){:target="_blank"}  from **@stahlleiton**: Add 2025 HI relval workflows `alca` `pdmv` `upgrade` created: 2025-07-27 14:31:40 merged: 2025-08-15 08:47:30

195. [48624](http://github.com/cms-sw/cmssw/pull/48624){:target="_blank"}  from **@iarspider**: Fix stack-use-after-scope in HLTGenResHistColl::fillHists `dqm` created: 2025-07-24 08:58:21 merged: 2025-08-04 18:14:37

196. [48615](http://github.com/cms-sw/cmssw/pull/48615){:target="_blank"}  from **@iarspider**: Fix heap-buffer-overflow in RecHitProcessor::processLook `l1` created: 2025-07-23 12:56:42 merged: 2025-08-15 08:49:26

197. [48608](http://github.com/cms-sw/cmssw/pull/48608){:target="_blank"}  from **@nancymarinelli**: Phase 2 EB trig primitive: needed fix to PR 42633  `l1` `simulation` `upgrade` created: 2025-07-22 17:44:04 merged: 2025-09-16 08:55:51

198. [48607](http://github.com/cms-sw/cmssw/pull/48607){:target="_blank"}  from **@sbaldu**: Implement template helper functions to reduce macro depencencies in SoA backend `heterogeneous` created: 2025-07-22 15:36:10 merged: 2025-08-27 05:23:45

199. [48606](http://github.com/cms-sw/cmssw/pull/48606){:target="_blank"}  from **@stahlleiton**: Adapt HGCal rechit producer for HGCal testbeam data `alca` `geometry` `reconstruction` `pdmv` `db` `upgrade` `heterogeneous` created: 2025-07-22 15:11:57 merged: 2025-08-19 15:19:36

200. [48597](http://github.com/cms-sw/cmssw/pull/48597){:target="_blank"}  from **@hjbossi**: Add NeNe era modifier for the HF FG bit thresholds. `l1` `operations` created: 2025-07-21 21:11:10 merged: 2025-08-07 13:39:46

201. [48571](http://github.com/cms-sw/cmssw/pull/48571){:target="_blank"}  from **@CMS-HGCAL**: Updates for new HGCal SiPM channel mapping `geometry` `upgrade` created: 2025-07-18 10:29:12 merged: 2025-08-25 07:18:53

202. [48562](http://github.com/cms-sw/cmssw/pull/48562){:target="_blank"}  from **@makortel**: Enhance process information in `edmProvDump` output and include hardware information there `core` `hlt` created: 2025-07-16 21:16:51 merged: 2025-08-06 15:13:16

203. [48559](http://github.com/cms-sw/cmssw/pull/48559){:target="_blank"}  from **@CMS-HGCAL**: Read BX, L1A, and Orbit numbers from ECON-D, Capture Block, and S-Link headers `reconstruction` `simulation` `upgrade` created: 2025-07-16 13:40:10 merged: 2025-08-26 06:45:06

204. [48541](http://github.com/cms-sw/cmssw/pull/48541){:target="_blank"}  from **@CMSTrackerDPG**: Disabling irradiation bias correction from 2025 onward `reconstruction` `trk` created: 2025-07-14 17:14:44 merged: 2025-08-27 05:21:17

205. [48539](http://github.com/cms-sw/cmssw/pull/48539){:target="_blank"}  from **@see-saw28**: Remove EGM Scale and Smearing for Run2 reprocessing and update old EPcombination parameters `reconstruction` `xpog` `egamma` created: 2025-07-14 09:26:18 merged: 2025-08-07 16:18:21

206. [48508](http://github.com/cms-sw/cmssw/pull/48508){:target="_blank"}  from **@slava77**: LST: add trackToTrack comparisons for GPU vs CPU tracking `dqm` `reconstruction` `pdmv` `upgrade` `tracking` created: 2025-07-08 23:13:59 merged: 2025-08-13 06:24:38

207. [48490](http://github.com/cms-sw/cmssw/pull/48490){:target="_blank"}  from **@AdrianoDee**: Fixed Number of Events Data Wfs for Testing `pdmv` `upgrade` created: 2025-07-07 10:26:03 merged: 2025-09-20 07:38:16

208. [48422](http://github.com/cms-sw/cmssw/pull/48422){:target="_blank"}  from **@mseidel42**: Modifications for Pythia 8.315 `generators` created: 2025-06-26 11:10:16 merged: 2025-10-03 11:25:01

209. [48408](http://github.com/cms-sw/cmssw/pull/48408){:target="_blank"}  from **@KIT-CMS**: Restructure and comment the tau embedding method `operations` `reconstruction` `simulation` `pdmv` `upgrade` `xpog` `tracking` `trk` created: 2025-06-25 14:35:18 merged: 2025-09-23 09:01:31

210. [48378](http://github.com/cms-sw/cmssw/pull/48378){:target="_blank"}  from **@alexstrel**: Replace standard library functions with their Alpaka equivalents  `reconstruction` `heterogeneous` `tracking` created: 2025-06-20 19:48:16 merged: 2025-08-04 18:11:17

211. [48377](http://github.com/cms-sw/cmssw/pull/48377){:target="_blank"}  from **@leobeltra**: Updated SoA View accessors from raw pointers to span `dqm` `hlt` `reconstruction` `simulation` `upgrade` `heterogeneous` `tracking` `trk` created: 2025-06-20 10:13:35 merged: 2025-10-01 15:29:19

212. [48311](http://github.com/cms-sw/cmssw/pull/48311){:target="_blank"}  from **@JHiltbrand**: Remove Redundant Condition Check in HCAL TP Algorithm Setup Code `l1` created: 2025-06-13 08:13:55 merged: 2025-08-27 18:12:36

213. [48308](http://github.com/cms-sw/cmssw/pull/48308){:target="_blank"}  from **@JunwonTomOh**: [L1T] Update L1T MET and Add JUMP algorithm (Phase 2) `l1` `upgrade` created: 2025-06-13 06:33:37 merged: 2025-09-10 19:27:06

214. [48303](http://github.com/cms-sw/cmssw/pull/48303){:target="_blank"}  from **@waredjeb**: Fix crashes in HGCAL HLT/RECO with v19 geometry `hlt` `l1` `reconstruction` `simulation` `upgrade` `hgcal` created: 2025-06-12 12:22:18 merged: 2025-08-18 13:06:10

215. [48275](http://github.com/cms-sw/cmssw/pull/48275){:target="_blank"}  from **@brandiskip**: L1 Track Extended Collection for Phase2OT added to Validation Package `dqm` `trk` created: 2025-06-09 15:32:39 merged: 2025-10-02 08:29:27

216. [48221](http://github.com/cms-sw/cmssw/pull/48221){:target="_blank"}  from **@mmusich**: Further fixes for HGCal validation at HLT `dqm` `reconstruction` `upgrade` created: 2025-05-31 08:01:53 merged: 2025-09-17 12:29:39

217. [48184](http://github.com/cms-sw/cmssw/pull/48184){:target="_blank"}  from **@felicepantaleo**: TICL trackster raw pT from position `reconstruction` `upgrade` created: 2025-05-27 14:39:42 merged: 2025-08-27 18:12:50

218. [48163](http://github.com/cms-sw/cmssw/pull/48163){:target="_blank"}  from **@patinkaew**: Introduce L1ScoutingNanoAOD for Run3 `daq` `pdmv` `upgrade` `xpog` created: 2025-05-23 21:20:27 merged: 2025-08-11 11:50:15

#### CMSDIST Changes between Tags REL/CMSSW_15_1_0_pre5/el8_amd64_gcc13 and REL/CMSSW_16_0_0_pre1/el8_amd64_gcc13:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_15_1_0_pre5/el8_amd64_gcc13...REL/CMSSW_16_0_0_pre1/el8_amd64_gcc13)



1. [9998](http://github.com/cms-sw/cmsdist/pull/9998){:target="_blank"}  from **@cms-sw**: SCRAMV1: unset PYTHONHOME via scram wrapper script created: 2025-08-07 13:28:03 merged: 2025-08-07 15:41:05

2. [9996](http://github.com/cms-sw/cmsdist/pull/9996){:target="_blank"}  from **@cms-sw**: cms-git-tools: Added subpackage-aware cherry-pick created: 2025-08-07 09:07:25 merged: 2025-08-07 13:21:21

3. [9995](http://github.com/cms-sw/cmsdist/pull/9995){:target="_blank"}  from **@sinonkt**: update crab-dev to v3.250806 created: 2025-08-06 15:40:13 merged: 2025-08-07 06:21:05

4. [9994](http://github.com/cms-sw/cmsdist/pull/9994){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-HGCalMapping to V00-05-00 created: 2025-08-05 15:08:53 merged: 2025-08-05 15:08:55

5. [9992](http://github.com/cms-sw/cmsdist/pull/9992){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-HGCalMapping to V00-04-00 created: 2025-08-05 14:41:08 merged: 2025-08-05 14:41:10

6. [9990](http://github.com/cms-sw/cmsdist/pull/9990){:target="_blank"}  from **@cms-sw**: Update tag for DataFormats-Scouting to V00-05-00 created: 2025-08-04 14:11:55 merged: 2025-08-04 14:11:57

7. [9944](http://github.com/cms-sw/cmsdist/pull/9944){:target="_blank"}  from **@fwyzard**: Update alpaka to 1.3.0 created: 2025-06-26 12:12:58 merged: 2025-09-11 12:26:53

8. [9943](http://github.com/cms-sw/cmsdist/pull/9943){:target="_blank"}  from **@mseidel42**: Pythia 8.315 created: 2025-06-26 11:08:12 merged: 2025-10-03 11:23:59

9. [10102](http://github.com/cms-sw/cmsdist/pull/10102){:target="_blank"}  from **@cms-sw**: Move master IBs to gcc13 created: 2025-09-30 18:17:35 merged: 2025-09-30 20:02:57

10. [10101](http://github.com/cms-sw/cmsdist/pull/10101){:target="_blank"}  from **@fwyzard**: Update UCX to version 1.19.0 created: 2025-09-30 16:55:49 merged: 2025-10-03 09:01:38

11. [10098](http://github.com/cms-sw/cmsdist/pull/10098){:target="_blank"}  from **@belforte**: Update crab-dev.spec created: 2025-09-30 09:59:14 merged: 2025-10-03 09:02:03

12. [10094](http://github.com/cms-sw/cmsdist/pull/10094){:target="_blank"}  from **@cms-sw**: cms-common: Print stack trace and exit with non-zero code if the traced application crashes created: 2025-09-27 05:32:46 merged: 2025-09-27 20:28:32

13. [10090](http://github.com/cms-sw/cmsdist/pull/10090){:target="_blank"}  from **@cms-sw**: Update tag for RecoLocalCalo-HGCalRecProducers to V00-02-00 created: 2025-09-25 11:05:03 merged: 2025-09-25 11:05:05

14. [10089](http://github.com/cms-sw/cmsdist/pull/10089){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-HGCalMapping to V00-07-00 created: 2025-09-25 11:04:39 merged: 2025-09-25 11:04:41

15. [10088](http://github.com/cms-sw/cmsdist/pull/10088){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-MkFit to V00-18-00 created: 2025-09-25 11:04:00 merged: 2025-09-25 11:04:02

16. [10083](http://github.com/cms-sw/cmsdist/pull/10083){:target="_blank"}  from **@cms-sw**: clhep: replace stdlib.h with cstdlib created: 2025-09-17 07:10:27 merged: 2025-09-17 11:14:01

17. [10082](http://github.com/cms-sw/cmsdist/pull/10082){:target="_blank"}  from **@cms-sw**: [hls] Cleanup of C headers e.g. stdlib.h, stdio.h, assert.h created: 2025-09-16 15:49:18 merged: 2025-09-16 20:59:33

18. [10081](http://github.com/cms-sw/cmsdist/pull/10081){:target="_blank"}  from **@cms-sw**: Fix for various relocation issues created: 2025-09-16 08:45:15 merged: 2025-09-16 21:07:19

19. [10080](http://github.com/cms-sw/cmsdist/pull/10080){:target="_blank"}  from **@cms-sw**: [RFC] Add tool to automatically update most of ROCm subpackages' versions created: 2025-09-15 15:17:20 merged: 2025-09-16 21:08:24

20. [10073](http://github.com/cms-sw/cmsdist/pull/10073){:target="_blank"}  from **@cms-sw**: [Sherpa]Apply the upstream patch to avoid setting env created: 2025-09-14 10:42:04 merged: 2025-09-27 05:43:01

21. [10069](http://github.com/cms-sw/cmsdist/pull/10069){:target="_blank"}  from **@kpedro88**: expose additional libraries needed for celeritas geant4 interface compilation created: 2025-09-11 20:12:31 merged: 2025-09-14 18:56:09

22. [10065](http://github.com/cms-sw/cmsdist/pull/10065){:target="_blank"}  from **@mmusich**: Update tag for L1Trigger-Phase2L1ParticleFlow to V00-09-00 created: 2025-09-11 08:55:38 merged: 2025-09-11 09:40:11

23. [10063](http://github.com/cms-sw/cmsdist/pull/10063){:target="_blank"}  from **@belforte**: Update crab-dev.spec created: 2025-09-08 08:10:45 merged: 2025-09-08 11:19:36

24. [10058](http://github.com/cms-sw/cmsdist/pull/10058){:target="_blank"}  from **@cms-sw**: openmpi: Set needed env to avoid openmpi calling setenv at runtime created: 2025-09-04 09:57:02 merged: 2025-09-12 09:47:42

25. [10055](http://github.com/cms-sw/cmsdist/pull/10055){:target="_blank"}  from **@cms-sw**: xrootd: update to version 5.8.4 created: 2025-09-02 14:42:34 merged: 2025-09-03 08:13:39

26. [10054](http://github.com/cms-sw/cmsdist/pull/10054){:target="_blank"}  from **@fwyzard**: Update ROCm to version 6.4.3 created: 2025-09-02 10:05:56 merged: 2025-09-11 12:27:35

27. [10051](http://github.com/cms-sw/cmsdist/pull/10051){:target="_blank"}  from **@cms-sw**: cms-common: Fix for 00-no-biglib hook and cmsTraceFunction with abort option created: 2025-09-01 08:39:04 merged: 2025-09-01 11:53:58

28. [10047](http://github.com/cms-sw/cmsdist/pull/10047){:target="_blank"}  from **@belforte**: bump crab-dev to prod. Save prod as pre(vious) created: 2025-08-28 11:42:00 merged: 2025-08-28 14:40:37

29. [10045](http://github.com/cms-sw/cmsdist/pull/10045){:target="_blank"}  from **@cms-sw**: Update tag for IOPool-Input to V00-04-00 created: 2025-08-28 07:11:54 merged: 2025-08-28 07:11:56

30. [10043](http://github.com/cms-sw/cmsdist/pull/10043){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-HGCalMapping to V00-06-00 created: 2025-08-27 07:28:36 merged: 2025-08-27 07:28:37

31. [10042](http://github.com/cms-sw/cmsdist/pull/10042){:target="_blank"}  from **@fwyzard**: Update hwloc to v2.12.2 created: 2025-08-26 21:07:29 merged: 2025-08-27 08:42:19

32. [10040](http://github.com/cms-sw/cmsdist/pull/10040){:target="_blank"}  from **@ghyls**: Upgrade OpenMPI version from 4.1.9 to 5.0.8 created: 2025-08-26 12:42:33 merged: 2025-09-03 08:24:02

33. [10039](http://github.com/cms-sw/cmsdist/pull/10039){:target="_blank"}  from **@Annnnya**: Fix mpich configuration and update to 4.3.1 created: 2025-08-25 10:04:26 merged: 2025-09-01 10:23:35

34. [10035](http://github.com/cms-sw/cmsdist/pull/10035){:target="_blank"}  from **@belforte**: Update crab-dev.spec to latest created: 2025-08-20 10:30:57 merged: 2025-08-22 13:37:28

35. [10034](http://github.com/cms-sw/cmsdist/pull/10034){:target="_blank"}  from **@fwyzard**: Update NVIDIA gdrcopy to v2.5.1 created: 2025-08-20 05:29:47 merged: 2025-09-01 14:29:35

36. [10033](http://github.com/cms-sw/cmsdist/pull/10033){:target="_blank"}  from **@cms-sw**: Update tag for RecoLocalCalo-HGCalRecProducers to V00-01-00 created: 2025-08-19 15:19:52 merged: 2025-08-19 15:19:53

37. [10031](http://github.com/cms-sw/cmsdist/pull/10031){:target="_blank"}  from **@fwyzard**: Update CUDA to version 12.9.1 created: 2025-08-19 06:44:54 merged: 2025-09-02 07:32:16

38. [10018](http://github.com/cms-sw/cmsdist/pull/10018){:target="_blank"}  from **@cms-sw**: auto generate/repalce tool name and base variables created: 2025-08-15 11:11:41 merged: 2025-08-15 16:33:21

39. [10017](http://github.com/cms-sw/cmsdist/pull/10017){:target="_blank"}  from **@cms-sw**: cleanup for py3 blosc/blosc2 and tables packages created: 2025-08-15 09:23:35 merged: 2025-08-15 16:21:25

40. [10014](http://github.com/cms-sw/cmsdist/pull/10014){:target="_blank"}  from **@cms-sw**: Update tag for DQM-Integration to V00-11-00 created: 2025-08-13 08:54:59 merged: 2025-08-13 08:55:00

41. [10009](http://github.com/cms-sw/cmsdist/pull/10009){:target="_blank"}  from **@cms-sw**: [gdb] build with relocatable python libdir created: 2025-08-11 09:24:04 merged: 2025-08-11 20:34:14

42. [10001](http://github.com/cms-sw/cmsdist/pull/10001){:target="_blank"}  from **@cms-sw**: revert SCRAM to not unset PYTHONHOME created: 2025-08-08 09:10:33 merged: 2025-08-08 09:20:16
