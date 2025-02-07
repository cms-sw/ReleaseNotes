---
layout: post
rel_link:  "15_0_0_pre3"
title:  "CMSSW_15_0_0_pre3"
date:   2025-02-06 09:55:42
categories: cmssw
relmajor: 15
relminor: 0
relsubminor: 0
relpre: _pre3
---

# CMSSW_15_0_0_pre3
#### Changes since CMSSW_15_0_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_15_0_0_pre2...CMSSW_15_0_0_pre3)



1. [47269](http://github.com/cms-sw/cmssw/pull/47269){:target="_blank"}  from **@hqucms**: [HGCAL] Fix the implementation of scaling test in HGCalRecHitProducers `reconstruction` `upgrade` created: 2025-02-05 14:21:35 merged: 2025-02-05 18:50:31

2. [47266](http://github.com/cms-sw/cmssw/pull/47266){:target="_blank"}  from **@iarspider**: [GCC14] Avoid std::clamp in device code `reconstruction` `tracking` `trk` created: 2025-02-05 10:07:13 merged: 2025-02-05 18:47:41

3. [47265](http://github.com/cms-sw/cmssw/pull/47265){:target="_blank"}  from **@iarspider**: [GCC14] template-id not allowed for constructor in C++20 `reconstruction` `heterogeneous` `tracking` created: 2025-02-05 08:40:34 merged: 2025-02-05 13:36:36

4. [47264](http://github.com/cms-sw/cmssw/pull/47264){:target="_blank"}  from **@mmusich**: move `HGCalHitCalibrationHLT` DQM plots from top folder to inside `HLT` folder `dqm` created: 2025-02-05 07:52:02 merged: 2025-02-05 18:47:11

5. [47263](http://github.com/cms-sw/cmssw/pull/47263){:target="_blank"}  from **@jsamudio**: Change PFRecHitSoAProducer to directly consume HCAL rechit SoA in matrix WFs `reconstruction` created: 2025-02-04 21:16:11 merged: 2025-02-05 15:40:36

6. [47256](http://github.com/cms-sw/cmssw/pull/47256){:target="_blank"}  from **@makortel**: Copy also chi2 for HCAL RecHits in HCALRecHitSoAProducer `reconstruction` `heterogeneous` created: 2025-02-04 11:09:06 merged: 2025-02-04 18:53:51

7. [47253](http://github.com/cms-sw/cmssw/pull/47253){:target="_blank"}  from **@hqucms**: [NANO] Fix PS weight parsing `xpog` created: 2025-02-04 00:43:42 merged: 2025-02-04 15:05:50

8. [47243](http://github.com/cms-sw/cmssw/pull/47243){:target="_blank"}  from **@bsunanda**: Run3-gex187X Add a test script to test all scenarios of 2021 `simulation` created: 2025-02-03 10:14:21 merged: 2025-02-04 08:06:02

9. [47241](http://github.com/cms-sw/cmssw/pull/47241){:target="_blank"}  from **@fwyzard**: Fix the number for the last lumisection of the run `db` created: 2025-02-02 15:46:59 merged: 2025-02-05 10:20:43

10. [47240](http://github.com/cms-sw/cmssw/pull/47240){:target="_blank"}  from **@fwyzard**: Add missing `#include` in `CondFormats/Common` `alca` `db` created: 2025-02-02 15:38:11 merged: 2025-02-03 17:31:03

11. [47235](http://github.com/cms-sw/cmssw/pull/47235){:target="_blank"}  from **@elfontan**: Scouting Offline DQM for 2025 data-taking (EGM+MUO+autoDQM) `dqm` created: 2025-01-31 23:26:59 merged: 2025-02-05 18:49:41

12. [47234](http://github.com/cms-sw/cmssw/pull/47234){:target="_blank"}  from **@Dr15Jones**: Renamed BranchChildren to ProductDependencies `core` created: 2025-01-31 21:15:21 merged: 2025-02-05 13:37:02

13. [47232](http://github.com/cms-sw/cmssw/pull/47232){:target="_blank"}  from **@SegmentLinking**: Dynamic Memory Allocation for LST Objects `reconstruction` `tracking` created: 2025-01-31 18:47:00 merged: 2025-02-03 10:49:32

14. [47231](http://github.com/cms-sw/cmssw/pull/47231){:target="_blank"}  from **@hqucms**: Add matrix tests for reMINI + NANOv15 `pdmv` `upgrade` created: 2025-01-31 18:26:20 merged: 2025-02-04 15:03:20

15. [47230](http://github.com/cms-sw/cmssw/pull/47230){:target="_blank"}  from **@eigen1907**: Temporarily deactivate selfTest during integrate RPC geometry and isFront function modifications `reconstruction` created: 2025-01-31 15:41:46 merged: 2025-01-31 19:55:01

16. [47229](http://github.com/cms-sw/cmssw/pull/47229){:target="_blank"}  from **@Dr15Jones**: Fix NoParentDictionary test `core` created: 2025-01-31 15:03:54 merged: 2025-02-05 12:22:03

17. [47228](http://github.com/cms-sw/cmssw/pull/47228){:target="_blank"}  from **@nurfikri89**: [NanoAOD, BTV] Finalize UParT branches for NanoV15 `xpog` created: 2025-01-31 15:03:17 merged: 2025-01-31 19:53:30

18. [47227](http://github.com/cms-sw/cmssw/pull/47227){:target="_blank"}  from **@makortel**: Remove default constructor from Alpaka EDProducer base classes `heterogeneous` created: 2025-01-31 15:01:46 merged: 2025-02-04 15:03:44

19. [47224](http://github.com/cms-sw/cmssw/pull/47224){:target="_blank"}  from **@mmusich**: add `fillDescriptions` to several plugins used at HLT (5/N) `alca` `analysis` `dqm` `hlt` `reconstruction` `simulation` `pdmv` `xpog` `tracking` `trk` created: 2025-01-31 14:00:00 merged: 2025-02-05 06:53:49

20. [47216](http://github.com/cms-sw/cmssw/pull/47216){:target="_blank"}  from **@makortel**: Migrate Alpaka EDProducers to pass the edm::ParameterSet to base class constructor `alca` `reconstruction` `upgrade` `heterogeneous` `tracking` `trk` created: 2025-01-30 23:06:59 merged: 2025-02-04 09:34:11

21. [47214](http://github.com/cms-sw/cmssw/pull/47214){:target="_blank"}  from **@makortel**: Remove unused source member from an iorule in DataFormats/TauReco/src/classes_def_2.xml `reconstruction` created: 2025-01-30 19:04:20 merged: 2025-01-31 19:55:15

22. [47213](http://github.com/cms-sw/cmssw/pull/47213){:target="_blank"}  from **@Dr15Jones**: Sources now have independent ProductRegistry `core` created: 2025-01-30 18:51:06 merged: 2025-01-31 19:52:55

23. [47210](http://github.com/cms-sw/cmssw/pull/47210){:target="_blank"}  from **@mandrenguyen**: Exclude neutrinos from heavy-ion genJets in miniAOD `reconstruction` `xpog` created: 2025-01-30 14:06:35 merged: 2025-01-30 17:36:32

24. [47209](http://github.com/cms-sw/cmssw/pull/47209){:target="_blank"}  from **@hahnjo**: Work around ROOT bug in HitPattern IO read rule `reconstruction` `tracking` created: 2025-01-30 12:18:53 merged: 2025-01-30 15:53:29

25. [47208](http://github.com/cms-sw/cmssw/pull/47208){:target="_blank"}  from **@SegmentLinking**: Use central phi functions instead LST ones `reconstruction` `heterogeneous` `tracking` created: 2025-01-30 11:03:18 merged: 2025-01-31 07:25:34

26. [47206](http://github.com/cms-sw/cmssw/pull/47206){:target="_blank"}  from **@nurfikri89**: [JME,Nano] Refactor constituents table,  add GloParT WvsQCD score `reconstruction` `xpog` created: 2025-01-29 22:48:40 merged: 2025-02-04 15:46:21

27. [47205](http://github.com/cms-sw/cmssw/pull/47205){:target="_blank"}  from **@mmusich**: add more limited matrix options, separately for Run1&2, Run3, Phase2 and HeavyIons `pdmv` `upgrade` created: 2025-01-29 21:27:49 merged: 2025-02-04 09:33:40

28. [47204](http://github.com/cms-sw/cmssw/pull/47204){:target="_blank"}  from **@artlbv**: L1 P2GT region cut checks and fixing menu config `l1` `upgrade` created: 2025-01-29 20:06:31 merged: 2025-02-05 16:34:03

29. [47203](http://github.com/cms-sw/cmssw/pull/47203){:target="_blank"}  from **@smuzaffar**: Update clang-tidy test to make sure it process header file too `core` created: 2025-01-29 19:45:48 merged: 2025-02-05 14:17:37

30. [47202](http://github.com/cms-sw/cmssw/pull/47202){:target="_blank"}  from **@iarspider**: Add missing methods to Style class `dqm` created: 2025-01-29 15:53:19 merged: 2025-01-30 15:50:55

31. [47201](http://github.com/cms-sw/cmssw/pull/47201){:target="_blank"}  from **@Dr15Jones**: Remove use of OpenMP threading `reconstruction` created: 2025-01-29 15:23:40 merged: 2025-01-30 15:48:45

32. [47200](http://github.com/cms-sw/cmssw/pull/47200){:target="_blank"}  from **@iarspider**: Remove unused variable in TrackingManagerHelper.icc `simulation` created: 2025-01-29 08:43:20 merged: 2025-01-31 09:41:03

33. [47199](http://github.com/cms-sw/cmssw/pull/47199){:target="_blank"}  from **@iarspider**: Remove unused variable in TestAssociator.cc `simulation` `trk` created: 2025-01-29 08:38:08 merged: 2025-02-03 07:25:26

34. [47197](http://github.com/cms-sw/cmssw/pull/47197){:target="_blank"}  from **@24LopezR**: Process modifier for displaced SUSY simulation fix `operations` `simulation` created: 2025-01-28 16:09:58 merged: 2025-02-03 17:29:40

35. [47195](http://github.com/cms-sw/cmssw/pull/47195){:target="_blank"}  from **@iarspider**: Avoid inf average values in SimpleMemoryCheck `core` created: 2025-01-28 15:10:56 merged: 2025-01-28 21:26:41

36. [47191](http://github.com/cms-sw/cmssw/pull/47191){:target="_blank"}  from **@mmusich**: add `fillDescriptions` to several `ESproducer`s used at HLT (2/N) `alca` `analysis` `hlt` `reconstruction` `tracking` created: 2025-01-27 21:11:34 merged: 2025-01-30 10:12:29

37. [47190](http://github.com/cms-sw/cmssw/pull/47190){:target="_blank"}  from **@Dr15Jones**: Rename BranchDescription to ProductDescription `alca` `core` `daq` `dqm` `generators` `hlt` `l1` `reconstruction` `visualization` `simulation` `xpog` `trk` created: 2025-01-27 14:24:09 merged: 2025-01-30 15:50:20

38. [47189](http://github.com/cms-sw/cmssw/pull/47189){:target="_blank"}  from **@mmusich**: throw in presence of mismatched `SimBeamSpot` types in `BetafuncEvtVtxGenerator` and `GaussEvtVtxGenerator` `alca` `simulation` `db` `tracking` created: 2025-01-27 09:39:32 merged: 2025-01-28 14:04:29

39. [47188](http://github.com/cms-sw/cmssw/pull/47188){:target="_blank"}  from **@francescobrivio**: Update beamspot option in ConfigBuilder `hlt` `operations` `pdmv` `upgrade` created: 2025-01-26 17:14:37 merged: 2025-01-31 07:27:02

40. [47186](http://github.com/cms-sw/cmssw/pull/47186){:target="_blank"}  from **@civanch**: [SIM/MTD] Fixed ECAL GFlash for Phase2 `simulation` created: 2025-01-26 09:22:01 merged: 2025-01-26 16:43:26

41. [47185](http://github.com/cms-sw/cmssw/pull/47185){:target="_blank"}  from **@slava77**: speedup SiStripRecHitConverterAlgorithm by reserving the output size `reconstruction` `trk` created: 2025-01-25 13:06:07 merged: 2025-01-27 16:04:37

42. [47184](http://github.com/cms-sw/cmssw/pull/47184){:target="_blank"}  from **@Dr15Jones**: Fix edmDumpClassVersion call for CondFormats/L1TObjects `alca` `l1` `db` created: 2025-01-24 16:47:26 merged: 2025-01-30 15:49:32

43. [47181](http://github.com/cms-sw/cmssw/pull/47181){:target="_blank"}  from **@makortel**: Remove unnecessary dummy object definitions from CondFormats/L1TObjects/src/classes.h `alca` `l1` `db` created: 2025-01-24 14:28:38 merged: 2025-01-30 15:49:05

44. [47180](http://github.com/cms-sw/cmssw/pull/47180){:target="_blank"}  from **@carlocms**: MTD Validation: removed duplicated statement in BtlLocalRecoValidation `dqm` created: 2025-01-24 13:10:54 merged: 2025-01-24 16:29:42

45. [47179](http://github.com/cms-sw/cmssw/pull/47179){:target="_blank"}  from **@iarspider**: Fix compilation of HGCalRecHitProducers.cc `reconstruction` `upgrade` created: 2025-01-24 10:07:55 merged: 2025-01-27 11:13:10

46. [47175](http://github.com/cms-sw/cmssw/pull/47175){:target="_blank"}  from **@makortel**: Add HardwareResourcesDescription class `core` created: 2025-01-24 01:24:46 merged: 2025-01-30 15:52:39

47. [47174](http://github.com/cms-sw/cmssw/pull/47174){:target="_blank"}  from **@slava77**: use faster variant of OmniClusterRef and RefCoreWithIndex initialization `core` `reconstruction` `tracking` `trk` created: 2025-01-23 23:33:00 merged: 2025-01-25 07:48:50

48. [47173](http://github.com/cms-sw/cmssw/pull/47173){:target="_blank"}  from **@AlexDeMoor**: Introduce Unified Particle Transformer v2 `reconstruction` `xpog` created: 2025-01-23 21:41:17 merged: 2025-02-04 15:05:45

49. [47172](http://github.com/cms-sw/cmssw/pull/47172){:target="_blank"}  from **@24LopezR**: ETL simulation: update of TWC parameters `reconstruction` `upgrade` created: 2025-01-23 19:23:42 merged: 2025-01-25 07:51:46

50. [47169](http://github.com/cms-sw/cmssw/pull/47169){:target="_blank"}  from **@makortel**: Add necessary target members to HitPattern IO read rule `reconstruction` `tracking` created: 2025-01-23 14:38:26 merged: 2025-01-24 15:25:02

51. [47168](http://github.com/cms-sw/cmssw/pull/47168){:target="_blank"}  from **@sihyunjeon**: Phase2 inner tracker class def xml fix `reconstruction` `upgrade` `trk` created: 2025-01-23 07:12:54 merged: 2025-01-24 14:38:41

52. [47167](http://github.com/cms-sw/cmssw/pull/47167){:target="_blank"}  from **@nurfikri89**: [BTV,DQM] Add tagger inputs plots for DQM and Validation `dqm` `tracking` created: 2025-01-22 22:31:29 merged: 2025-01-28 15:18:53

53. [47166](http://github.com/cms-sw/cmssw/pull/47166){:target="_blank"}  from **@Dr15Jones**: Remove uses of ConstProductRegistry from framework `core` `simulation` created: 2025-01-22 19:31:03 merged: 2025-01-24 15:13:35

54. [47165](http://github.com/cms-sw/cmssw/pull/47165){:target="_blank"}  from **@24LopezR**: Fix in HepMC - G4 interface for displaced SUSY simulation `simulation` created: 2025-01-22 15:56:14 merged: 2025-01-24 14:38:46

55. [47163](http://github.com/cms-sw/cmssw/pull/47163){:target="_blank"}  from **@perrotta**: Update online GTs for 150X and GT for 2025 MC conditions in autoCond  `alca` created: 2025-01-22 14:24:01 merged: 2025-01-23 10:45:20

56. [47162](http://github.com/cms-sw/cmssw/pull/47162){:target="_blank"}  from **@smuzaffar**: Remove unused iorules of missing reco::LeafParticle class `reconstruction` created: 2025-01-22 13:27:41 merged: 2025-01-23 08:11:30

57. [47161](http://github.com/cms-sw/cmssw/pull/47161){:target="_blank"}  from **@AdrianoDee**: 2025 PU and Wfs for PR Testing and GPU `pdmv` `upgrade` created: 2025-01-22 08:54:55 merged: 2025-01-27 09:12:43

58. [47160](http://github.com/cms-sw/cmssw/pull/47160){:target="_blank"}  from **@bsunanda**: Phase2-gex186C Modify all Run4 scenarios to include the modified RPC geometry `geometry` `upgrade` created: 2025-01-22 08:50:19 merged: 2025-02-03 07:24:44

59. [47159](http://github.com/cms-sw/cmssw/pull/47159){:target="_blank"}  from **@bsunanda**: Run3-gex186B Modify all Run3 scenarios to include the modified RPC geometry `geometry` `upgrade` created: 2025-01-22 06:48:55 merged: 2025-01-23 08:58:57

60. [47158](http://github.com/cms-sw/cmssw/pull/47158){:target="_blank"}  from **@bsunanda**: Run3-gex186A Modify all Run2 scenarios to include the modified RPC geometry `geometry` `upgrade` created: 2025-01-22 06:13:45 merged: 2025-01-24 15:26:04

61. [47157](http://github.com/cms-sw/cmssw/pull/47157){:target="_blank"}  from **@nurfikri89**: [Nano, JMENano] Updates for V15 `xpog` created: 2025-01-21 18:19:10 merged: 2025-01-25 07:50:18

62. [47156](http://github.com/cms-sw/cmssw/pull/47156){:target="_blank"}  from **@mmusich**: Fix `cfi` creation for conf db parsing `reconstruction` created: 2025-01-21 16:31:38 merged: 2025-01-21 21:22:04

63. [47154](http://github.com/cms-sw/cmssw/pull/47154){:target="_blank"}  from **@SegmentLinking**: Rename reduceRange to reducePhiRange `dqm` `hlt` `l1` `reconstruction` `simulation` `upgrade` `heterogeneous` `tracking` created: 2025-01-21 10:47:21 merged: 2025-01-25 07:51:20

64. [47153](http://github.com/cms-sw/cmssw/pull/47153){:target="_blank"}  from **@iarspider**: Fix generation of cmsDriver command if accelerators contain asterisk symbol `pdmv` `upgrade` created: 2025-01-21 10:14:29 merged: 2025-01-27 11:12:20

65. [47151](http://github.com/cms-sw/cmssw/pull/47151){:target="_blank"}  from **@mmusich**: fix `EventSetupConflict` for producer 'SteppingHelixPropagator' `reconstruction` `tracking` created: 2025-01-21 08:51:56 merged: 2025-01-21 21:28:45

66. [47149](http://github.com/cms-sw/cmssw/pull/47149){:target="_blank"}  from **@ats2008**: Calo Layer-2 EG conditions update for 2024 `l1` created: 2025-01-21 06:25:15 merged: 2025-01-23 08:07:35

67. [47148](http://github.com/cms-sw/cmssw/pull/47148){:target="_blank"}  from **@Pruthvi-ch**: Corrections to HGCal Cell offsets for v19  `geometry` `upgrade` created: 2025-01-21 03:16:39 merged: 2025-01-23 08:07:23

68. [47147](http://github.com/cms-sw/cmssw/pull/47147){:target="_blank"}  from **@civanch**: [TRK DIGI] Fix sampling of tracker noise  `simulation` `trk` created: 2025-01-20 23:42:01 merged: 2025-01-21 16:23:10

69. [47146](http://github.com/cms-sw/cmssw/pull/47146){:target="_blank"}  from **@missirol**: update `TestGlobalObjectMapRecordFormat` unit test with `CMSSW_15_0_0_pre2` inputs `l1` created: 2025-01-20 19:41:07 merged: 2025-01-29 07:51:08

70. [47144](http://github.com/cms-sw/cmssw/pull/47144){:target="_blank"}  from **@mmusich**: Clean-up Phase-2 HLT menu of duplicates `hlt` created: 2025-01-20 16:14:12 merged: 2025-01-21 21:28:59

71. [47143](http://github.com/cms-sw/cmssw/pull/47143){:target="_blank"}  from **@fabiocos**: MTD geometry: address static CLANG analyzer error in Geometry/MTDNumberingBuilder `geometry` `upgrade` created: 2025-01-20 10:54:27 merged: 2025-01-20 17:28:16

72. [47142](http://github.com/cms-sw/cmssw/pull/47142){:target="_blank"}  from **@mmusich**: run more testing in `CalibTracker/SiStripCommon` unit tests `alca` `trk` created: 2025-01-20 10:43:04 merged: 2025-01-21 16:34:09

73. [47141](http://github.com/cms-sw/cmssw/pull/47141){:target="_blank"}  from **@smuzaffar**: [GCC13]Workaround to avoid false-positive partly outside array bounds `reconstruction` `tracking` created: 2025-01-20 09:49:12 merged: 2025-01-21 16:21:25

74. [47139](http://github.com/cms-sw/cmssw/pull/47139){:target="_blank"}  from @BlancoFS: Fix trigger table for MUO**@POG** flavored nanoAOD  `xpog` created: 2025-01-20 09:21:37 merged: 2025-01-25 07:49:51

75. [47136](http://github.com/cms-sw/cmssw/pull/47136){:target="_blank"}  from **@mmusich**: add `fillDescriptions` to several `ESproducer`s used at HLT (1/N) `alca` `reconstruction` `upgrade` `tracking` `trk` created: 2025-01-19 19:25:19 merged: 2025-01-20 17:29:35

76. [47134](http://github.com/cms-sw/cmssw/pull/47134){:target="_blank"}  from **@bsunanda**: Run3-gex186 Submit the modified RPC geometries for Run, Run3 and Run4 `geometry` created: 2025-01-19 05:13:13 merged: 2025-01-20 17:33:45

77. [47133](http://github.com/cms-sw/cmssw/pull/47133){:target="_blank"}  from **@missirol**: remove warning on value of `pcrhFracSize` `reconstruction` created: 2025-01-18 12:28:43 merged: 2025-01-20 17:35:09

78. [47132](http://github.com/cms-sw/cmssw/pull/47132){:target="_blank"}  from **@missirol**: enable a `printf` call in `fitVertices` only in `verbose` mode `reconstruction` `tracking` created: 2025-01-18 09:45:59 merged: 2025-01-20 17:31:05

79. [47131](http://github.com/cms-sw/cmssw/pull/47131){:target="_blank"}  from **@bsunanda**: Phase2-hgx361F Update the remaining scripts in Geometry/HGCalGeometry/test/python using the tool that finds ERA and Global Tag for a given scenario `geometry` `upgrade` created: 2025-01-18 06:32:39 merged: 2025-01-20 17:33:56

80. [47130](http://github.com/cms-sw/cmssw/pull/47130){:target="_blank"}  from **@bsunanda**: Phase2-hgx361E Update several scripts in Geometry/HGCalGeometry/test/python using the new tool that finds the right ERA and Global Tag `geometry` `upgrade` created: 2025-01-18 04:04:49 merged: 2025-01-20 17:34:46

81. [47128](http://github.com/cms-sw/cmssw/pull/47128){:target="_blank"}  from **@missirol**: fixing one include-guard and use of tabs post-#47030 `l1` created: 2025-01-17 18:03:55 merged: 2025-01-28 06:29:16

82. [47126](http://github.com/cms-sw/cmssw/pull/47126){:target="_blank"}  from **@Dr15Jones**: Removed use of ConstProductRegistry outside of the framework `alca` `core` `simulation` `trk` created: 2025-01-17 16:42:17 merged: 2025-01-20 17:33:21

83. [47120](http://github.com/cms-sw/cmssw/pull/47120){:target="_blank"}  from **@fwyzard**: Replace `ALPAKA_STATIC_ACC_MEM_GLOBAL` with `HOST_DEVICE_CONSTANT` `reconstruction` created: 2025-01-17 08:07:25 merged: 2025-01-20 17:32:36

84. [47119](http://github.com/cms-sw/cmssw/pull/47119){:target="_blank"}  from **@fwyzard**: Update the signature of `allocMappedBuf` `heterogeneous` created: 2025-01-17 07:31:38 merged: 2025-01-21 16:25:50

85. [47118](http://github.com/cms-sw/cmssw/pull/47118){:target="_blank"}  from **@Dr15Jones**: Reduced what data held in BranchDescription `alca` `core` `generators` created: 2025-01-16 21:48:40 merged: 2025-01-23 08:06:46

86. [47117](http://github.com/cms-sw/cmssw/pull/47117){:target="_blank"}  from **@Dr15Jones**: Created DroppedDataProductResolver `core` created: 2025-01-16 15:51:49 merged: 2025-01-20 17:29:56

87. [47109](http://github.com/cms-sw/cmssw/pull/47109){:target="_blank"}  from **@bsunanda**: Phase2-hgx361 Enable a scenario with only HGCal for the V17 version `geometry` `simulation` `upgrade` created: 2025-01-15 14:56:12 merged: 2025-01-20 17:30:21

88. [47102](http://github.com/cms-sw/cmssw/pull/47102){:target="_blank"}  from **@jhakala**: HcalNano for MC `pdmv` `upgrade` `xpog` `hcal` created: 2025-01-14 20:26:00 merged: 2025-01-29 07:50:18

89. [47101](http://github.com/cms-sw/cmssw/pull/47101){:target="_blank"}  from **@mkirsano**: Enable running ExternalDecays (photospp only for the moment) in the HepMC3 mode `generators` created: 2025-01-14 20:06:14 merged: 2025-01-20 17:29:12

90. [47094](http://github.com/cms-sw/cmssw/pull/47094){:target="_blank"}  from **@slava77**: fill charge_ and barycenter_ for all SiStripClusters `reconstruction` `trk` created: 2025-01-13 23:28:33 merged: 2025-01-20 17:28:05

91. [47084](http://github.com/cms-sw/cmssw/pull/47084){:target="_blank"}  from **@SegmentLinking**: LST followups: better work divisions, concrete kernel dimension, some cleanup and fixes `reconstruction` `heterogeneous` `tracking` created: 2025-01-10 19:17:40 merged: 2025-01-29 07:48:33

92. [47033](http://github.com/cms-sw/cmssw/pull/47033){:target="_blank"}  from **@SegmentLinking**: Port generic alpaka phi functions to `DataFormats/Math` `heterogeneous` created: 2025-01-02 12:10:36 merged: 2025-01-20 17:27:31

93. [47014](http://github.com/cms-sw/cmssw/pull/47014){:target="_blank"}  from **@iarspider**: Fix UnnecessaryMutableChecker `core` created: 2024-12-19 15:49:54 merged: 2025-01-21 21:28:18

94. [47007](http://github.com/cms-sw/cmssw/pull/47007){:target="_blank"}  from **@yeckang**: [GEM] Allow storing 2025 geometry in GEMGeometryParsFromDD `geometry` `upgrade` created: 2024-12-18 08:29:31 merged: 2025-01-21 21:27:28

95. [47002](http://github.com/cms-sw/cmssw/pull/47002){:target="_blank"}  from **@smuzaffar**: [DQM] Apply code checks/format `dqm` `trk` created: 2024-12-18 07:41:35 merged: 2025-01-21 16:20:36

96. [46959](http://github.com/cms-sw/cmssw/pull/46959){:target="_blank"}  from **@JunseokLee3609**: update seed for l1tObjectsTiming `dqm` created: 2024-12-16 10:32:37 merged: 2025-01-31 19:52:43

97. [46916](http://github.com/cms-sw/cmssw/pull/46916){:target="_blank"}  from **@fwyzard**: Replace `TAcc` with explicit accelerator type `reconstruction` `upgrade` `heterogeneous` `tracking` `trk` created: 2024-12-11 17:24:33 merged: 2025-01-21 21:26:29

98. [46884](http://github.com/cms-sw/cmssw/pull/46884){:target="_blank"}  from **@CMSTrackerDPG**: Run-dependent pixel simulation using additionally compressed SimHit info `operations` `simulation` `pdmv` `upgrade` `trk` created: 2024-12-05 17:58:37 merged: 2025-02-05 10:20:59

99. [46489](http://github.com/cms-sw/cmssw/pull/46489){:target="_blank"}  from **@artlbv**: [Phase-2 L1] Incorporate object threshold scalings, ID and isolation via dictionaries into the P2GT menu `l1` `operations` `upgrade` created: 2024-10-23 11:39:40 merged: 2025-01-27 16:03:07

100. [46198](http://github.com/cms-sw/cmssw/pull/46198){:target="_blank"}  from **@aloeliger**: Synchronize L1T L1TReEmulFromRAW and Repack_Full configurations `operations` created: 2024-10-02 11:30:16 merged: 2025-02-04 15:02:45

101. [40610](http://github.com/cms-sw/cmssw/pull/40610){:target="_blank"}  from **@mmusich**: `RecoLocalTracker/SubCollectionProducers`: replacing `existsAs` with `fillDescription` for default parameter values `reconstruction` `trk` created: 2023-01-25 11:22:12 merged: 2025-01-21 21:26:13

#### CMSDIST Changes between Tags REL/CMSSW_15_0_0_pre2/el8_amd64_gcc12 and REL/CMSSW_15_0_0_pre3/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_15_0_0_pre2/el8_amd64_gcc12...REL/CMSSW_15_0_0_pre3/el8_amd64_gcc12)



1. [9676](http://github.com/cms-sw/cmsdist/pull/9676){:target="_blank"}  from **@cms-sw**: cms-common: Fix for GREP_OPTION env created: 2025-02-04 21:39:47 merged: 2025-02-05 06:54:46

2. [9674](http://github.com/cms-sw/cmsdist/pull/9674){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-26-00 created: 2025-02-04 15:05:57 merged: 2025-02-04 15:06:00

3. [9670](http://github.com/cms-sw/cmsdist/pull/9670){:target="_blank"}  from **@fwyzard**: Update ROCm to version 6.3.2 created: 2025-02-04 08:49:30 merged: 2025-02-06 07:13:03

4. [9669](http://github.com/cms-sw/cmsdist/pull/9669){:target="_blank"}  from **@hahnjo**: Update G4HepEm to latest tag created: 2025-02-03 12:23:32 merged: 2025-02-03 21:04:20

5. [9666](http://github.com/cms-sw/cmsdist/pull/9666){:target="_blank"}  from **@cms-sw**: Added isal deps in to xrootd toolfile created: 2025-02-02 11:35:54 merged: 2025-02-02 14:09:04

6. [9654](http://github.com/cms-sw/cmsdist/pull/9654){:target="_blank"}  from **@cms-sw**: Update pybind11 and apply array out of bound patch created: 2025-01-30 08:26:21 merged: 2025-01-31 05:37:36

7. [9653](http://github.com/cms-sw/cmsdist/pull/9653){:target="_blank"}  from **@cms-sw**: onnxruntime: Use single thread to compile with nvcc created: 2025-01-29 22:57:37 merged: 2025-01-30 05:21:52

8. [9652](http://github.com/cms-sw/cmsdist/pull/9652){:target="_blank"}  from **@cms-sw**: build rule: fixes clang-tidy, use relative path for cmssw headers created: 2025-01-29 19:44:06 merged: 2025-01-30 08:42:36

9. [9651](http://github.com/cms-sw/cmsdist/pull/9651){:target="_blank"}  from **@cms-sw**: TF: apply upstream patch to fix gcc13/aarch64 build errors created: 2025-01-29 16:23:31 merged: 2025-01-29 22:02:17

10. [9644](http://github.com/cms-sw/cmsdist/pull/9644){:target="_blank"}  from **@cms-sw**: Update tag for GeneratorInterface-EvtGenInterface to V02-11-00 created: 2025-01-29 09:19:45 merged: 2025-01-29 09:19:47

11. [9642](http://github.com/cms-sw/cmsdist/pull/9642){:target="_blank"}  from **@cms-sw**: Update tag for DataFormats-L1TGlobal to V00-03-00 created: 2025-01-29 07:51:14 merged: 2025-01-29 07:51:15

12. [9640](http://github.com/cms-sw/cmsdist/pull/9640){:target="_blank"}  from **@cms-sw**: backport changes from gcc13 branch to master created: 2025-01-29 06:40:54 merged: 2025-01-29 18:37:13

13. [9639](http://github.com/cms-sw/cmsdist/pull/9639){:target="_blank"}  from **@gartung**: libunwind master with fix for uninitialized access created: 2025-01-28 15:55:01 merged: 2025-02-04 22:23:13

14. [9638](http://github.com/cms-sw/cmsdist/pull/9638){:target="_blank"}  from **@cms-sw**: Update virtualenv  20.29.1 created: 2025-01-27 21:11:45 merged: 2025-01-28 07:44:22

15. [9637](http://github.com/cms-sw/cmsdist/pull/9637){:target="_blank"}  from **@cms-sw**: Build rules: set default micro arch for all builds created: 2025-01-27 15:23:42 merged: 2025-01-27 20:44:32

16. [9636](http://github.com/cms-sw/cmsdist/pull/9636){:target="_blank"}  from **@fwyzard**: Update CUDA to 12.8.0 created: 2025-01-26 18:29:38 merged: 2025-01-29 18:36:47

17. [9635](http://github.com/cms-sw/cmsdist/pull/9635){:target="_blank"}  from **@gartung**: Update libunwind version disable per thread cache created: 2025-01-26 15:30:48 merged: 2025-01-26 18:25:11

18. [9633](http://github.com/cms-sw/cmsdist/pull/9633){:target="_blank"}  from **@valsdav**: Added FORCE_LINK to pytorch custom ops libraries created: 2025-01-23 18:24:03 merged: 2025-01-27 20:41:40

19. [9632](http://github.com/cms-sw/cmsdist/pull/9632){:target="_blank"}  from **@fwyzard**: Build ROCm rocprofiler-register from sources created: 2025-01-22 09:13:29 merged: 2025-01-22 20:35:28

20. [9630](http://github.com/cms-sw/cmsdist/pull/9630){:target="_blank"}  from **@fwyzard**: Update ROCm to 6.2.4 and GPU targets created: 2025-01-20 17:42:56 merged: 2025-01-21 08:05:12

21. [9629](http://github.com/cms-sw/cmsdist/pull/9629){:target="_blank"}  from **@cms-sw**: buildrulles: fix for linking cuda libs created: 2025-01-20 13:16:23 merged: 2025-01-21 08:16:07

22. [9620](http://github.com/cms-sw/cmsdist/pull/9620){:target="_blank"}  from **@fwyzard**: Update CUDA to 12.6.3 and cuDNN to 9.6.0 created: 2025-01-16 23:34:16 merged: 2025-01-21 16:27:06

23. [9619](http://github.com/cms-sw/cmsdist/pull/9619){:target="_blank"}  from **@fwyzard**: Update alpaka to 1.2.0 created: 2025-01-16 23:03:21 merged: 2025-01-21 16:25:55

24. [9581](http://github.com/cms-sw/cmsdist/pull/9581){:target="_blank"}  from **@fwyzard**: Update NVIDIA gdrcopy to v2.4.4 created: 2024-12-16 18:24:19 merged: 2025-01-24 15:14:00
