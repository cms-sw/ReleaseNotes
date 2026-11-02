---
layout: post
rel_link:  "20_1_0_pre5"
title:  "CMSSW_20_1_0_pre5"
date:   2026-10-30 10:10:12
categories: cmssw
relmajor: 20
relminor: 1
relsubminor: 0
relpre: _pre5
---

# CMSSW_20_1_0_pre5
#### Changes since CMSSW_20_1_0_pre4:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_20_1_0_pre4...CMSSW_20_1_0_pre5)



1. [52298](http://github.com/cms-sw/cmssw/pull/52298){:target="_blank"}  from **@bsunanda**: Run3-gex235 Update the scripts in Validation/Geometry/test to make them run without crashing, except the issue in histogram booking `dqm` `geometry` created: 2026-10-27 10:25:48 merged: 2026-10-27 18:16:58

2. [52296](http://github.com/cms-sw/cmssw/pull/52296){:target="_blank"}  from **@Dr15Jones**: Removed HRRealTime.h `core` `reconstruction` `tracking` created: 2026-10-26 20:20:59 merged: 2026-10-27 18:17:13

3. [52292](http://github.com/cms-sw/cmssw/pull/52292){:target="_blank"}  from **@makortel**: Add rntuple option to Merge jobs, add rudimentary unit test `operations` created: 2026-10-26 15:59:31 merged: 2026-10-26 17:51:46

4. [52291](http://github.com/cms-sw/cmssw/pull/52291){:target="_blank"}  from **@sbaldu**: Fix search box comparison in BarrelCLUEAlgo `reconstruction` created: 2026-10-26 15:55:56 merged: 2026-10-27 18:17:40

5. [52287](http://github.com/cms-sw/cmssw/pull/52287){:target="_blank"}  from **@fwyzard**: FastTimerService: add printLumiSummary, gate the transition reports `hlt` created: 2026-10-26 06:04:35 merged: 2026-10-26 16:34:48

6. [52286](http://github.com/cms-sw/cmssw/pull/52286){:target="_blank"}  from **@fwyzard**: FastTimerService: optimise filling per-path resources `hlt` created: 2026-10-25 19:15:58 merged: 2026-10-26 16:34:15

7. [52279](http://github.com/cms-sw/cmssw/pull/52279){:target="_blank"}  from **@fwyzard**: `FastTimerService`: handle unknown threads `hlt` created: 2026-10-24 07:52:52 merged: 2026-10-26 07:35:11

8. [52273](http://github.com/cms-sw/cmssw/pull/52273){:target="_blank"}  from **@teteumac**: [DQM] Consolidate inclusive jet DQM pT histograms `dqm` created: 2026-10-23 11:48:29 merged: 2026-10-26 16:33:58

9. [52267](http://github.com/cms-sw/cmssw/pull/52267){:target="_blank"}  from **@mmusich**: add 1D comparison plots of ECAL laser corrections `db` created: 2026-10-23 07:46:35 merged: 2026-10-24 08:43:13

10. [52265](http://github.com/cms-sw/cmssw/pull/52265){:target="_blank"}  from **@Electricks94**: Improve EIGEN support in the SoA backend `heterogeneous` `reconstruction` `simulation` `tracking` created: 2026-10-22 15:35:22 merged: 2026-10-26 16:25:49

11. [52264](http://github.com/cms-sw/cmssw/pull/52264){:target="_blank"}  from **@mmusich**: Fix `HLTJetFlavourTagParticleTransformerSequencePF` to not contain filters `hlt` created: 2026-10-22 15:31:24 merged: 2026-10-24 08:42:47

12. [52261](http://github.com/cms-sw/cmssw/pull/52261){:target="_blank"}  from **@bsunanda**: Phase2-hgxgex234 Remove refernce to subdetector types for HGCal in Validation code which were used in the pst for 6-inch wafers `dqm` created: 2026-10-22 06:43:22 merged: 2026-10-22 08:54:19

13. [52260](http://github.com/cms-sw/cmssw/pull/52260){:target="_blank"}  from **@bsunanda**: Phase2-gex233 Remove refernce to subdetector types for HGCal in some RecoEgamma code which were used in the pst for 6-inch wafers `reconstruction` created: 2026-10-22 06:41:31 merged: 2026-10-22 13:16:09

14. [52256](http://github.com/cms-sw/cmssw/pull/52256){:target="_blank"}  from **@stahlleiton**: [20_1_X] Add option to keep dEdx hit information using track multiplicity `reconstruction` `tracking` created: 2026-10-21 14:00:07 merged: 2026-10-22 08:54:30

15. [52251](http://github.com/cms-sw/cmssw/pull/52251){:target="_blank"}  from **@smuzaffar**: [DQM] Apply code-format changes suggested by LLVM23 `dqm` created: 2026-10-20 19:30:26 merged: 2026-10-21 07:59:11

16. [52249](http://github.com/cms-sw/cmssw/pull/52249){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] Apply code-format changes suggested by LLVM23 `reconstruction` `trk` created: 2026-10-20 19:29:51 merged: 2026-10-21 07:59:04

17. [52248](http://github.com/cms-sw/cmssw/pull/52248){:target="_blank"}  from **@smuzaffar**: [SIMULATION] Apply code-format changes suggested by LLVM23 `simulation` created: 2026-10-20 19:29:40 merged: 2026-10-21 20:59:43

18. [52247](http://github.com/cms-sw/cmssw/pull/52247){:target="_blank"}  from **@smuzaffar**: [ALCA-DB] Apply code-format changes suggested by LLVM23 `db` created: 2026-10-20 19:29:09 merged: 2026-10-21 20:59:53

19. [52244](http://github.com/cms-sw/cmssw/pull/52244){:target="_blank"}  from **@forthommel**: Add missing dictionaries for CaloAnalysis `simulation` created: 2026-10-20 11:07:44 merged: 2026-10-21 07:58:06

20. [52243](http://github.com/cms-sw/cmssw/pull/52243){:target="_blank"}  from **@pallabidas**: Fix phi inefficiency in GCT object `l1` created: 2026-10-20 09:49:06 merged: 2026-10-24 08:44:05

21. [52241](http://github.com/cms-sw/cmssw/pull/52241){:target="_blank"}  from **@AuroraPerego**: Add missing dictionaries for TICL  `core` `reconstruction` created: 2026-10-19 20:41:23 merged: 2026-10-20 15:26:42

22. [52240](http://github.com/cms-sw/cmssw/pull/52240){:target="_blank"}  from **@Parsifal-2045**: Add missing data dictionaries for HLT inputs `l1` `simulation` created: 2026-10-19 15:26:34 merged: 2026-10-20 15:21:29

23. [52236](http://github.com/cms-sw/cmssw/pull/52236){:target="_blank"}  from **@forthommel**: Revert "LSTCore: -Ofast for the CPU backend and --use_fast_math for CUDA" `reconstruction` `tracking` created: 2026-10-19 11:10:25 merged: 2026-10-19 20:22:35

24. [52225](http://github.com/cms-sw/cmssw/pull/52225){:target="_blank"}  from **@bsunanda**: Run3-gex231 Include FBCM as test code in 2026 special scenario for ForwardCommonData `geometry` created: 2026-10-18 11:24:18 merged: 2026-10-19 08:57:33

25. [52219](http://github.com/cms-sw/cmssw/pull/52219){:target="_blank"}  from **@CMS-HGCAL**: HGCAL : CondFormats for aging `alca` `db` `geometry` `simulation` created: 2026-10-17 08:43:53 merged: 2026-10-22 13:15:55

26. [52213](http://github.com/cms-sw/cmssw/pull/52213){:target="_blank"}  from **@bfonta**: PFBlockAlgo improvements. `reconstruction` created: 2026-10-16 16:30:52 merged: 2026-10-20 15:20:47

27. [52211](http://github.com/cms-sw/cmssw/pull/52211){:target="_blank"}  from **@bsunanda**: Phase2-hgx369C Update the test scripts for evaluating the performance of neighbour finder of HGCal silicon cells `geometry` created: 2026-10-16 11:08:07 merged: 2026-10-16 15:41:53

28. [52209](http://github.com/cms-sw/cmssw/pull/52209){:target="_blank"}  from **@perrotta**: Add 2025 EG regression tags as placeholders for the 2026 HI MC GT in autoCond [20_1_X] `alca` created: 2026-10-16 10:07:09 merged: 2026-10-16 15:42:29

29. [52208](http://github.com/cms-sw/cmssw/pull/52208){:target="_blank"}  from **@AuroraPerego**: fix a bug in `TICLAssociationMap` and add a test `simulation` created: 2026-10-16 09:34:00 merged: 2026-10-20 15:29:57

30. [52206](http://github.com/cms-sw/cmssw/pull/52206){:target="_blank"}  from **@forthommel**: FlatOccupancy cleanup in MuonAlignmentAlgorithms `alca` created: 2026-10-16 07:42:34 merged: 2026-10-16 15:42:58

31. [52202](http://github.com/cms-sw/cmssw/pull/52202){:target="_blank"}  from **@Dr15Jones**: Moved to using google benchmark for precision timing `reconstruction` `simulation` `tracking` created: 2026-10-15 21:55:33 merged: 2026-10-24 08:42:23

32. [52198](http://github.com/cms-sw/cmssw/pull/52198){:target="_blank"}  from **@smuzaffar**: [HLT] [CLANG] Fix build warnings reported in clang IBs `hlt` created: 2026-10-15 14:28:53 merged: 2026-10-15 20:44:44

33. [52197](http://github.com/cms-sw/cmssw/pull/52197){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION][CLANG] Fix build warnings reported in clang IBs `reconstruction` created: 2026-10-15 14:23:33 merged: 2026-10-15 20:45:17

34. [52196](http://github.com/cms-sw/cmssw/pull/52196){:target="_blank"}  from **@smuzaffar**: [DQM] [CLANG] Fix build warnings reported in clang IBs `dqm` created: 2026-10-15 14:20:15 merged: 2026-10-19 20:22:25

35. [52195](http://github.com/cms-sw/cmssw/pull/52195){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION-XPOG] [CLANG] Fix build warnings reported in clang IBs `reconstruction` `xpog` created: 2026-10-15 14:11:44 merged: 2026-10-27 07:44:52

36. [52194](http://github.com/cms-sw/cmssw/pull/52194){:target="_blank"}  from **@smuzaffar**: [ANALYSIS] [CLANG] Fix build warnings reported in clang IBs `analysis` created: 2026-10-15 14:11:29 merged: 2026-10-15 20:54:12

37. [52193](http://github.com/cms-sw/cmssw/pull/52193){:target="_blank"}  from **@smuzaffar**: [FASTSIM] [CLANG] Fix build warnings reported in clang IBs `fastsim` created: 2026-10-15 14:09:21 merged: 2026-10-16 16:30:12

38. [52192](http://github.com/cms-sw/cmssw/pull/52192){:target="_blank"}  from **@smuzaffar**: [GEOMETRY] [CLANG] Fix build warnings reported in clang IBs `geometry` created: 2026-10-15 14:09:05 merged: 2026-10-16 16:32:22

39. [52191](http://github.com/cms-sw/cmssw/pull/52191){:target="_blank"}  from **@bsunanda**: Phase2-gex229X Remove reference to subdetector types of three different HGCal types in some local reconstruction code `reconstruction` created: 2026-10-15 12:07:04 merged: 2026-10-20 15:21:39

40. [52190](http://github.com/cms-sw/cmssw/pull/52190){:target="_blank"}  from **@smuzaffar**: fireworks: Explicitly link against rootgeomchecker to avoid UBSAN link error `visualization` created: 2026-10-15 10:09:11 merged: 2026-10-17 09:53:23

41. [52189](http://github.com/cms-sw/cmssw/pull/52189){:target="_blank"}  from **@fwyzard**: Do not start an OpenMP thread pool when loading XGBoost models `ml` created: 2026-10-15 06:42:43 merged: 2026-10-17 13:47:05

42. [52186](http://github.com/cms-sw/cmssw/pull/52186){:target="_blank"}  from **@mmusich**: do not use hardcoded GEM and RPC rechit collections at the HLT `hlt` `reconstruction` created: 2026-10-14 15:09:32 merged: 2026-10-15 10:37:33

43. [52185](http://github.com/cms-sw/cmssw/pull/52185){:target="_blank"}  from **@Dr15Jones**: Use sleep_for in timing unit test `core` created: 2026-10-14 14:09:21 merged: 2026-10-14 20:59:40

44. [52179](http://github.com/cms-sw/cmssw/pull/52179){:target="_blank"}  from **@bsunanda**: Phase2-gex299 Update the scripts in SimG4Core/PrintGeomInfo to make them useful for  more recent geometry scenarios `simulation` created: 2026-10-14 06:37:14 merged: 2026-10-16 15:43:40

45. [52178](http://github.com/cms-sw/cmssw/pull/52178){:target="_blank"}  from **@kpedro88**: Introduce MTD for Phase 2 FastSim `fastsim` `operations` `simulation` `tracking` created: 2026-10-13 15:43:55 merged: 2026-10-14 08:05:03

46. [52177](http://github.com/cms-sw/cmssw/pull/52177){:target="_blank"}  from **@akritkbehera**: Integrate llvm23 changes from DEVEL to master branch `alca` `analysis` `core` `trk` created: 2026-10-13 13:20:42 merged: 2026-10-20 07:43:54

47. [52175](http://github.com/cms-sw/cmssw/pull/52175){:target="_blank"}  from **@AuroraPerego**: Fix TICLv5 superclustering config `dqm` `operations` `pdmv` `reconstruction` `simulation` created: 2026-10-13 12:00:27 merged: 2026-10-21 07:57:08

48. [52174](http://github.com/cms-sw/cmssw/pull/52174){:target="_blank"}  from **@Parsifal-2045**: Take Phase-2 hit errors from genError in the Alpaka Pixel CPE `geometry` `hlt` `reconstruction` `trk` created: 2026-10-13 08:21:51 merged: 2026-10-16 15:43:58

49. [52173](http://github.com/cms-sw/cmssw/pull/52173){:target="_blank"}  from **@igv4321**: Resetting memoized pulse shapes in MahiFit for every run `hcal` `reconstruction` created: 2026-10-13 08:14:44 merged: 2026-10-14 20:59:02

50. [52172](http://github.com/cms-sw/cmssw/pull/52172){:target="_blank"}  from **@abdoulline**: HCAL : cleaning hard-coded conditions `alca` `hcal` created: 2026-10-13 08:12:48 merged: 2026-10-14 08:04:38

51. [52170](http://github.com/cms-sw/cmssw/pull/52170){:target="_blank"}  from **@smuzaffar**: testEigenJacobian: Fix build warning by removing unused variables and commented out code `reconstruction` `tracking` created: 2026-10-13 07:52:54 merged: 2026-10-15 08:56:36

52. [52167](http://github.com/cms-sw/cmssw/pull/52167){:target="_blank"}  from **@thomreis**: ECAL - Fix bin overflow issue for some validation histograms `dqm` `ecal` `l1` created: 2026-10-12 21:51:36 merged: 2026-10-17 13:46:00

53. [52166](http://github.com/cms-sw/cmssw/pull/52166){:target="_blank"}  from **@GNiendorf**: LST Memory Compaction `dqm` `heterogeneous` `hlt` `reconstruction` `tracking` created: 2026-10-12 20:25:46 merged: 2026-10-27 18:20:33

54. [52165](http://github.com/cms-sw/cmssw/pull/52165){:target="_blank"}  from **@fwyzard**: Restore the previous product getter in `RefCoreStreamerGuard` `core` created: 2026-10-12 19:04:14 merged: 2026-10-15 06:53:12

55. [52161](http://github.com/cms-sw/cmssw/pull/52161){:target="_blank"}  from **@bsunanda**: Phase2-hgcal369B4 Add a test for getArea code of HGCalGeometry `geometry` created: 2026-10-12 15:01:29 merged: 2026-10-12 18:35:49

56. [52158](http://github.com/cms-sw/cmssw/pull/52158){:target="_blank"}  from **@fwyzard**: Rework the Services ownership to improve scaling to large number of cores `core` `db` `generators` `geometry` `heterogeneous` `hlt` `l1` `ml` `simulation` `tracking` `trk` created: 2026-10-12 10:29:19 merged: 2026-10-29 17:30:23

57. [52145](http://github.com/cms-sw/cmssw/pull/52145){:target="_blank"}  from **@fwyzard**: Fix recent MPI test issues `heterogeneous` created: 2026-10-11 16:08:52 merged: 2026-10-12 14:36:06

58. [52144](http://github.com/cms-sw/cmssw/pull/52144){:target="_blank"}  from **@fwyzard**: Improve adler32 api and use zlib implementation `core` `daq` `dqm` `hlt` created: 2026-10-11 11:43:35 merged: 2026-10-14 20:59:28

59. [52143](http://github.com/cms-sw/cmssw/pull/52143){:target="_blank"}  from **@felicepantaleo**: HLTrigger/Tools: testHltDiff assertions read the text from a here-string `hlt` created: 2026-10-11 07:01:09 merged: 2026-10-12 14:33:23

60. [52141](http://github.com/cms-sw/cmssw/pull/52141){:target="_blank"}  from **@fwyzard**: Fix HLT `JSONMonitoring` for hostnames over 32 characters `hlt` created: 2026-10-10 20:08:11 merged: 2026-10-12 18:35:29

61. [52139](http://github.com/cms-sw/cmssw/pull/52139){:target="_blank"}  from **@fwyzard**: Fix `EvFDaqDirector` for hostnames over 32 characters `daq` created: 2026-10-10 20:02:40 merged: 2026-10-12 14:29:36

62. [52136](http://github.com/cms-sw/cmssw/pull/52136){:target="_blank"}  from **@fwyzard**: Fix DQM fillJson for hostnames over 32 characters `dqm` created: 2026-10-09 21:23:36 merged: 2026-10-12 14:29:51

63. [52134](http://github.com/cms-sw/cmssw/pull/52134){:target="_blank"}  from **@CMS-HGCAL**: Fix: [HGCAL] Adding upstream protection for saturated TOT charge `simulation` created: 2026-10-09 14:29:33 merged: 2026-10-22 13:15:37

64. [52133](http://github.com/cms-sw/cmssw/pull/52133){:target="_blank"}  from **@Dr15Jones**: Specialize workers for each transition type `core` `simulation` created: 2026-10-09 13:34:48 merged: 2026-10-15 20:10:33

65. [52132](http://github.com/cms-sw/cmssw/pull/52132){:target="_blank"}  from **@Parsifal-2045**: Fix wrong `--slot` configuration in the Phase-2 HLT timing test `hlt` created: 2026-10-09 13:08:43 merged: 2026-10-14 08:05:58

66. [52131](http://github.com/cms-sw/cmssw/pull/52131){:target="_blank"}  from **@Dominic-Stafford**: Fix incorrect references to ShowerHandler in Herwig7MGMergingSetting `generators` created: 2026-10-09 11:50:24 merged: 2026-10-12 14:34:42

67. [52129](http://github.com/cms-sw/cmssw/pull/52129){:target="_blank"}  from **@SegmentLinking**: LST: restore the -z TEDD disk 2 pixel-map connections `reconstruction` `tracking` created: 2026-10-09 09:40:48 merged: 2026-10-16 15:44:11

68. [52128](http://github.com/cms-sw/cmssw/pull/52128){:target="_blank"}  from **@perrotta**: Update beamspot tags for 2026 HI MC GT in autoCond `alca` created: 2026-10-09 06:27:45 merged: 2026-10-12 14:31:40

69. [52127](http://github.com/cms-sw/cmssw/pull/52127){:target="_blank"}  from **@GNiendorf**: LSTCore: -Ofast for the CPU backend and --use_fast_math for CUDA `reconstruction` `tracking` created: 2026-10-08 22:39:20 merged: 2026-10-15 20:11:22

70. [52117](http://github.com/cms-sw/cmssw/pull/52117){:target="_blank"}  from **@jprendi**: Adding `ScoutingMuonPropertiesMonitor` to `hltDqmOnlyScouting` sequence `dqm` created: 2026-10-08 09:48:51 merged: 2026-10-12 14:32:37

71. [52112](http://github.com/cms-sw/cmssw/pull/52112){:target="_blank"}  from **@mmarriot**: Fix Trackster sigmas and sigmaPCA in TrackstersPCA `reconstruction` created: 2026-10-07 18:18:03 merged: 2026-10-17 13:46:15

72. [52111](http://github.com/cms-sw/cmssw/pull/52111){:target="_blank"}  from **@Parsifal-2045**: Enable NVIDIA MPS in Phase-2 HLT timing tests `hlt` created: 2026-10-07 15:20:42 merged: 2026-10-15 06:52:52

73. [52110](http://github.com/cms-sw/cmssw/pull/52110){:target="_blank"}  from **@Parsifal-2045**: Remove `EIGEN_NO_DEBUG` flag `reconstruction` `tracking` created: 2026-10-07 15:02:49 merged: 2026-10-14 08:04:26

74. [52108](http://github.com/cms-sw/cmssw/pull/52108){:target="_blank"}  from **@SegmentLinking**: Add offline LST+mkFit (all iterations) Phase-2 RECO workflows `pdmv` created: 2026-10-07 13:51:30 merged: 2026-10-14 20:58:31

75. [52103](http://github.com/cms-sw/cmssw/pull/52103){:target="_blank"}  from **@alexandertuna**: Add sim parentage of hits to LST ntuple `reconstruction` `tracking` created: 2026-10-07 05:13:32 merged: 2026-10-15 20:11:05

76. [52102](http://github.com/cms-sw/cmssw/pull/52102){:target="_blank"}  from **@felicepantaleo**: fix candidates time for tracks without mtd `reconstruction` created: 2026-10-07 04:16:40 merged: 2026-10-12 20:56:46

77. [52098](http://github.com/cms-sw/cmssw/pull/52098){:target="_blank"}  from **@mmusich**: Swap `DeepTau` based reconstruction for `ParT` one in NGT Scouting menu `hlt` `reconstruction` created: 2026-10-06 13:53:37 merged: 2026-10-12 14:32:20

78. [52090](http://github.com/cms-sw/cmssw/pull/52090){:target="_blank"}  from **@makortel**: Use `edm::FileInPath::findFile()` only with relative paths in `jetHtPlotter.cc` `alca` `trk` created: 2026-10-05 19:04:25 merged: 2026-10-14 08:04:00

79. [52077](http://github.com/cms-sw/cmssw/pull/52077){:target="_blank"}  from **@tvami**: Add GenHDF5 reader `generators` `pdmv` created: 2026-10-03 14:38:30 merged: 2026-10-14 08:06:10

80. [52068](http://github.com/cms-sw/cmssw/pull/52068){:target="_blank"}  from **@akritkbehera**: [xpog] Apply clang23-code-formating `xpog` created: 2026-10-02 13:23:49 merged: 2026-10-12 20:55:56

81. [52057](http://github.com/cms-sw/cmssw/pull/52057){:target="_blank"}  from **@teteumac**: [DQM] Remove MET filter histograms and dependent efficiencies - Round 1 `dqm` created: 2026-10-01 17:01:02 merged: 2026-10-16 15:44:26

82. [52056](http://github.com/cms-sw/cmssw/pull/52056){:target="_blank"}  from **@teteumac**: [DQM] Remove selected offline jet DQM histograms and dependent ratios - Round 1 `dqm` created: 2026-10-01 16:50:33 merged: 2026-10-16 15:44:31

83. [52049](http://github.com/cms-sw/cmssw/pull/52049){:target="_blank"}  from **@eyigitba**: [L1T] Adding an option to modify FEVTDEBUGHLTEventContent for L1 Scouting `l1` `operations` created: 2026-10-01 11:54:00 merged: 2026-10-17 13:47:25

84. [52046](http://github.com/cms-sw/cmssw/pull/52046){:target="_blank"}  from **@gabrielmscampos**: [UBSAN][DQM] bound VFAT mask shift to the 24-bit OH mask width `dqm` created: 2026-10-01 08:30:27 merged: 2026-10-14 08:48:03

85. [52039](http://github.com/cms-sw/cmssw/pull/52039){:target="_blank"}  from **@kpedro88**: remove outdated default datasets from upgrade matrix `pdmv` created: 2026-09-30 19:07:06 merged: 2026-10-13 15:17:22

86. [52015](http://github.com/cms-sw/cmssw/pull/52015){:target="_blank"}  from **@GNiendorf**: mkFit and HLT LST-step fixes: high-pT tracks in jets and displaced-track recovery `hlt` `reconstruction` `tracking` created: 2026-09-29 13:12:26 merged: 2026-10-13 07:20:38

87. [52011](http://github.com/cms-sw/cmssw/pull/52011){:target="_blank"}  from **@GNiendorf**: LST T5 & T4 DNN Retrain `reconstruction` `tracking` created: 2026-09-29 12:32:54 merged: 2026-10-12 14:30:13

88. [52000](http://github.com/cms-sw/cmssw/pull/52000){:target="_blank"}  from **@smeriano**: Adding Decay Modes and Fake Sources for the Tau Phase 2 Validation tool `dqm` created: 2026-09-28 11:42:40 merged: 2026-10-15 10:38:12

89. [51968](http://github.com/cms-sw/cmssw/pull/51968){:target="_blank"}  from **@fwyzard**: Run ORT on GPU using CUDA and MIGraphX execution providers `ml` created: 2026-09-24 17:16:45 merged: 2026-10-12 20:57:31

90. [51959](http://github.com/cms-sw/cmssw/pull/51959){:target="_blank"}  from **@hatakeyamak**: MLPF barrel and HF for Phase 2 `dqm` `pdmv` `pf` `reconstruction` created: 2026-09-24 05:10:31 merged: 2026-10-13 15:20:46

91. [51942](http://github.com/cms-sw/cmssw/pull/51942){:target="_blank"}  from **@mardsouza**: GeneratorInterface/Core: Fix cross section consistency in GenXSecAnalyzer `generators` created: 2026-09-22 23:56:39 merged: 2026-10-14 08:04:05

92. [51928](http://github.com/cms-sw/cmssw/pull/51928){:target="_blank"}  from **@parbol**: MTD Alignment package 20 1 x `alca` `db` created: 2026-09-21 11:20:22 merged: 2026-10-12 13:44:58

93. [51867](http://github.com/cms-sw/cmssw/pull/51867){:target="_blank"}  from **@makortel**: Add tests for `edm::FileInPath` and fix number of corner cases `core` created: 2026-09-11 21:24:29 merged: 2026-10-17 13:47:11

94. [51856](http://github.com/cms-sw/cmssw/pull/51856){:target="_blank"}  from **@silviodonato**: Addition of a HGCal-only reco, validation, harvesting sequence and workflow `dqm` `operations` `pdmv` `simulation` created: 2026-09-10 17:15:55 merged: 2026-10-14 08:06:31

95. [51855](http://github.com/cms-sw/cmssw/pull/51855){:target="_blank"}  from **@jonathon-langford**: Add STXS 1.3 binning `generators` `xpog` created: 2026-09-10 16:01:37 merged: 2026-10-27 18:20:03

96. [51829](http://github.com/cms-sw/cmssw/pull/51829){:target="_blank"}  from **@felicepantaleo**: Truth Graph: branch association library and reco-to-truth associators `dqm` `generators` `pdmv` `simulation` created: 2026-09-04 12:33:42 merged: 2026-10-27 18:19:44

97. [51736](http://github.com/cms-sw/cmssw/pull/51736){:target="_blank"}  from **@ljuckett**: Tracker DQM: Add histogram booking at multiple levels `dqm` `trk` created: 2026-08-19 16:28:30 merged: 2026-10-27 18:18:29

98. [51654](http://github.com/cms-sw/cmssw/pull/51654){:target="_blank"}  from **@felicepantaleo**: Speed up runTheMatrix.py by up to 7x `pdmv` created: 2026-08-08 09:32:43 merged: 2026-10-13 15:20:03

99. [50617](http://github.com/cms-sw/cmssw/pull/50617){:target="_blank"}  from **@Dr15Jones**: Use RNTupleReader::RActiveEntryToken `core` created: 2026-04-01 13:34:31 merged: 2026-10-21 21:00:22

#### CMSDIST Changes between Tags REL/CMSSW_20_1_0_pre4/el9_amd64_gcc14 and REL/CMSSW_20_1_0_pre5/el9_amd64_gcc14:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_20_1_0_pre4/el9_amd64_gcc14...REL/CMSSW_20_1_0_pre5/el9_amd64_gcc14)



1. [10965](http://github.com/cms-sw/cmsdist/pull/10965){:target="_blank"}  from **@cms-sw**: cms-common: replace egrep with grep -E created: 2026-10-29 18:50:36 merged: 2026-10-29 21:27:13

2. [10964](http://github.com/cms-sw/cmsdist/pull/10964){:target="_blank"}  from **@cms-sw**: Fix Sherpa3 to pick up our python created: 2026-10-29 10:42:15 merged: 2026-10-29 11:32:15

3. [10962](http://github.com/cms-sw/cmsdist/pull/10962){:target="_blank"}  from **@cms-sw**: Update SCRAM/BuildRules for supporting edmplugin_from deps created: 2026-10-27 14:37:55 merged: 2026-10-27 21:46:18

4. [10959](http://github.com/cms-sw/cmsdist/pull/10959){:target="_blank"}  from **@akritkbehera**: Updated root to tip of branch v6-40-00-patches created: 2026-10-26 08:20:35 merged: 2026-10-26 20:48:42

5. [10956](http://github.com/cms-sw/cmsdist/pull/10956){:target="_blank"}  from **@cms-sw**: Update tag for IOMC-Input to V00-00-02 created: 2026-10-24 08:46:50 merged: 2026-10-24 08:46:53

6. [10955](http://github.com/cms-sw/cmsdist/pull/10955){:target="_blank"}  from **@cms-sw**: Update tag for Configuration-Generator to V01-14-02 created: 2026-10-24 08:46:38 merged: 2026-10-24 08:46:41

7. [10954](http://github.com/cms-sw/cmsdist/pull/10954){:target="_blank"}  from **@akritkbehera**: Reduce parallel compilations and set CMAKE_BUILD_PARALLEL_LEVEL created: 2026-10-23 13:39:30 merged: 2026-10-24 03:47:04

8. [10953](http://github.com/cms-sw/cmsdist/pull/10953){:target="_blank"}  from **@cms-sw**: Look for generated sources in S3 too created: 2026-10-22 21:21:41 merged: 2026-10-27 08:14:46

9. [10952](http://github.com/cms-sw/cmsdist/pull/10952){:target="_blank"}  from **@cms-sw**: Bump Python packages to their newer versions created: 2026-10-21 14:04:31 merged: 2026-10-22 16:42:42

10. [10951](http://github.com/cms-sw/cmsdist/pull/10951){:target="_blank"}  from **@akritkbehera**: Updates pip due to security issues. created: 2026-10-21 13:53:50 merged: 2026-10-22 16:43:30

11. [10949](http://github.com/cms-sw/cmsdist/pull/10949){:target="_blank"}  from **@cms-sw**: Update PyTorch to version 2.14.1 created: 2026-10-20 20:18:04 merged: 2026-10-22 16:44:07

12. [10947](http://github.com/cms-sw/cmsdist/pull/10947){:target="_blank"}  from **@akritkbehera**: Bump LLVM version from 23.1.1 to 23.1.3 created: 2026-10-20 14:03:21 merged: 2026-10-20 20:40:19

13. [10946](http://github.com/cms-sw/cmsdist/pull/10946){:target="_blank"}  from **@akritkbehera**: Updated root to tip of branch v6-40-00-patches created: 2026-10-20 14:00:47 merged: 2026-10-20 21:00:51

14. [10945](http://github.com/cms-sw/cmsdist/pull/10945){:target="_blank"}  from **@fwyzard**: Update jemalloc version 5.4.0 created: 2026-10-19 21:48:45 merged: 2026-10-20 19:00:17

15. [10944](http://github.com/cms-sw/cmsdist/pull/10944){:target="_blank"}  from **@cms-sw**: TF: check if externals sources as same as previously cached created: 2026-10-19 21:20:14 merged: 2026-10-20 15:09:24

16. [10942](http://github.com/cms-sw/cmsdist/pull/10942){:target="_blank"}  from **@cms-sw**: Update scram to use CMS_PATH/arch/cms to find install arch created: 2026-10-19 11:00:39 merged: 2026-10-19 13:09:38

17. [10941](http://github.com/cms-sw/cmsdist/pull/10941){:target="_blank"}  from **@cms-sw**: Force cache tf ext src created: 2026-10-19 10:34:35 merged: 2026-10-19 11:02:21

18. [10938](http://github.com/cms-sw/cmsdist/pull/10938){:target="_blank"}  from **@fwyzard**: Update root dependencies found by CMake created: 2026-10-18 21:18:45 merged: 2026-10-19 13:10:34

19. [10937](http://github.com/cms-sw/cmsdist/pull/10937){:target="_blank"}  from **@cms-sw**: Build tensile for all gpu arch via hipblaslt created: 2026-10-18 16:23:49 merged: 2026-10-19 20:29:19

20. [10936](http://github.com/cms-sw/cmsdist/pull/10936){:target="_blank"}  from **@fwyzard**: Update LZ4 to v1.10.0 created: 2026-10-17 20:53:09 merged: 2026-10-19 13:09:54

21. [10932](http://github.com/cms-sw/cmsdist/pull/10932){:target="_blank"}  from **@cms-sw**: Update tag for MagneticField-Interpolation to V01-02-01 created: 2026-10-16 07:08:31 merged: 2026-10-16 07:08:34

22. [10931](http://github.com/cms-sw/cmsdist/pull/10931){:target="_blank"}  from **@cms-sw**: Revert Torch to version 2.13.0 created: 2026-10-15 20:57:05 merged: 2026-10-16 05:25:00

23. [10929](http://github.com/cms-sw/cmsdist/pull/10929){:target="_blank"}  from **@cms-sw**: pyg-lib: fix the symlink for lib/libpyg.so created: 2026-10-15 12:49:11 merged: 2026-10-15 17:35:41

24. [10928](http://github.com/cms-sw/cmsdist/pull/10928){:target="_blank"}  from **@cms-sw**: [sherpa3] Relocation Exmaples python and cmake files created: 2026-10-15 12:15:00 merged: 2026-10-15 17:35:04

25. [10927](http://github.com/cms-sw/cmsdist/pull/10927){:target="_blank"}  from **@cms-sw**: Added hipfile toolfile created: 2026-10-15 10:52:33 merged: 2026-10-16 08:13:45

26. [10926](http://github.com/cms-sw/cmsdist/pull/10926){:target="_blank"}  from **@cms-sw**: Added toolfile for Root GeomChecker library created: 2026-10-15 10:04:25 merged: 2026-10-15 17:34:16

27. [10925](http://github.com/cms-sw/cmsdist/pull/10925){:target="_blank"}  from **@fwyzard**: Add GCC OpenMP tools created: 2026-10-15 09:32:16 merged: 2026-10-15 17:32:53

28. [10924](http://github.com/cms-sw/cmsdist/pull/10924){:target="_blank"}  from **@cms-sw**: Update TBB version from 2022.3.0 to 2023.1.0 created: 2026-10-14 08:33:37 merged: 2026-10-15 07:47:33

29. [10923](http://github.com/cms-sw/cmsdist/pull/10923){:target="_blank"}  from **@cms-sw**: Update ROOT to version 6.40.05 for 20.1.X release cycle created: 2026-10-14 07:30:54 merged: 2026-10-14 20:37:11

30. [10922](http://github.com/cms-sw/cmsdist/pull/10922){:target="_blank"}  from **@cms-sw**: Pytorch 2.14.1 and massive update of python packages created: 2026-10-13 14:00:55 merged: 2026-10-15 07:35:51

31. [10920](http://github.com/cms-sw/cmsdist/pull/10920){:target="_blank"}  from **@akritkbehera**: Update llvm23 in default IBs created: 2026-10-13 13:27:03 merged: 2026-10-20 07:43:47

32. [10918](http://github.com/cms-sw/cmsdist/pull/10918){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-MkFit to V00-20-01 created: 2026-10-13 07:20:51 merged: 2026-10-13 07:20:55

33. [10914](http://github.com/cms-sw/cmsdist/pull/10914){:target="_blank"}  from **@fwyzard**: Update Intel ISA-L to v2.32.1 created: 2026-10-11 09:22:59 merged: 2026-10-12 20:54:50

34. [10909](http://github.com/cms-sw/cmsdist/pull/10909){:target="_blank"}  from **@EmanueleCoradin**: Add some PyTorch-ROCm dependencies created: 2026-10-08 13:33:04 merged: 2026-10-12 20:57:28

35. [10907](http://github.com/cms-sw/cmsdist/pull/10907){:target="_blank"}  from **@Parsifal-2045**: Add `EIGEN_NO_DEBUG` flag to `CMS_EIGEN_CXX_FLAGS` created: 2026-10-07 17:42:23 merged: 2026-10-12 15:54:59

36. [10873](http://github.com/cms-sw/cmsdist/pull/10873){:target="_blank"}  from **@fwyzard**: ONNXRuntime: update to version 1.30.0 created: 2026-09-24 06:19:13 merged: 2026-10-12 20:57:26
