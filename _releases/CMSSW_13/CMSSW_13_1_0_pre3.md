---
layout: post
rel_link:  "13_1_0_pre3"
title:  "CMSSW_13_1_0_pre3"
date:   2023-04-12 05:41:20
categories: cmssw
relmajor: 13
relminor: 1
relsubminor: 0
relpre: _pre3
---

# CMSSW_13_1_0_pre3
#### Changes since CMSSW_13_1_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_13_1_0_pre2...CMSSW_13_1_0_pre3)



1. [41306](http://github.com/cms-sw/cmssw/pull/41306){:target="_blank"}  from **@gartung**: Utilities/StaticAnalyzers: skip pybind11 types in non-const global statics check `core` created: 2023-04-07 17:23:18 merged: 2023-04-10 13:35:07

2. [41304](http://github.com/cms-sw/cmssw/pull/41304){:target="_blank"}  from **@bsunanda**: Run3-gex158D Replace std::cout with edm::LogVerbatim in Geometry/MuonNumbering `geometry` created: 2023-04-07 09:40:58 merged: 2023-04-10 13:35:22

3. [41303](http://github.com/cms-sw/cmssw/pull/41303){:target="_blank"}  from **@smuzaffar**: [DBG] Fix compilation warnings `geometry` created: 2023-04-07 07:44:04 merged: 2023-04-08 16:02:45

4. [41302](http://github.com/cms-sw/cmssw/pull/41302){:target="_blank"}  from **@smuzaffar**: [DBG] fix compilation error for dbg IBs `simulation` created: 2023-04-07 07:36:07 merged: 2023-04-07 12:12:55

5. [41300](http://github.com/cms-sw/cmssw/pull/41300){:target="_blank"}  from **@mmusich**: get rid of `gROOT->Reset()` in GeometryComparisonPlotter.cc `alca` `trk` created: 2023-04-06 14:11:42 merged: 2023-04-06 19:33:19

6. [41299](http://github.com/cms-sw/cmssw/pull/41299){:target="_blank"}  from **@mmusich**: TkAl Payload Inspector: fix bug in computation of barycenters per partition and improve graphical display `db` created: 2023-04-06 12:50:36 merged: 2023-04-06 19:35:35

7. [41298](http://github.com/cms-sw/cmssw/pull/41298){:target="_blank"}  from **@francescobrivio**: Fix OMS url link for BeamSpot DQM clients `dqm` created: 2023-04-06 11:42:45 merged: 2023-04-07 08:33:30

8. [41294](http://github.com/cms-sw/cmssw/pull/41294){:target="_blank"}  from **@bsunanda**: Phase2-hgx336F Fix a bug in HGCalWaferMask to avoid overlaps of partial wafers in the V17 geometry of HGCal `geometry` `upgrade` created: 2023-04-06 05:44:54 merged: 2023-04-07 08:20:07

9. [41293](http://github.com/cms-sw/cmssw/pull/41293){:target="_blank"}  from **@aloeliger**: Add back data version removed in #41277 `l1` created: 2023-04-06 05:16:38 merged: 2023-04-06 08:26:48

10. [41291](http://github.com/cms-sw/cmssw/pull/41291){:target="_blank"}  from **@Dr15Jones**: Switch to std::chrono::steady_clock `core` created: 2023-04-05 17:53:16 merged: 2023-04-07 07:04:49

11. [41289](http://github.com/cms-sw/cmssw/pull/41289){:target="_blank"}  from **@dan131riley**: remove erroneous call to global ROOT reset `reconstruction` `dqm` `trk` created: 2023-04-05 16:07:40 merged: 2023-04-11 10:03:19

12. [41281](http://github.com/cms-sw/cmssw/pull/41281){:target="_blank"}  from **@mmusich**: improve unit test `testCreateRandomMisalignment` `alca` `trk` created: 2023-04-05 10:46:09 merged: 2023-04-05 16:44:52

13. [41278](http://github.com/cms-sw/cmssw/pull/41278){:target="_blank"}  from **@bsunanda**: Phase2-hgx337 The first entry of the V18 version of HGCal geometry `dqm` `geometry` `upgrade` created: 2023-04-05 04:11:25 merged: 2023-04-10 13:35:58

14. [41277](http://github.com/cms-sw/cmssw/pull/41277){:target="_blank"}  from **@zhenbinwu**: Add ap_data type to Phase 2 GMT output for GT interface `l1` created: 2023-04-04 21:25:39 merged: 2023-04-05 16:52:09

15. [41274](http://github.com/cms-sw/cmssw/pull/41274){:target="_blank"}  from **@smuzaffar**: Remove FWCore TestHelper utility `core` created: 2023-04-04 16:57:07 merged: 2023-04-05 05:45:49

16. [41273](http://github.com/cms-sw/cmssw/pull/41273){:target="_blank"}  from **@emiglior**: redefine IT digitizer ToF window + add customize fcn for activating IT signal shape with RelVals `simulation` `pdmv` `upgrade` `trk` created: 2023-04-04 16:12:53 merged: 2023-04-11 16:18:22

17. [41272](http://github.com/cms-sw/cmssw/pull/41272){:target="_blank"}  from **@bsunanda**: Run3-gex158C Replace std::cout with edm::LogVerbatim in Geometry/HcalEventSetup and Geometry/HcalTestBeamData. Also, add some missing files needed for testing `geometry` created: 2023-04-04 13:48:15 merged: 2023-04-06 04:58:50

18. [41269](http://github.com/cms-sw/cmssw/pull/41269){:target="_blank"}  from **@smuzaffar**: Unit tests improvement and addition of edmFileInPath `core` `db` created: 2023-04-04 11:04:09 merged: 2023-04-05 05:40:39

19. [41268](http://github.com/cms-sw/cmssw/pull/41268){:target="_blank"}  from **@bsunanda**: Run3-gex158B Replace std::cout with edm::LogVerbatim in Geometry/HGCalGeometry and Geometry/HcalCommonData `geometry` `upgrade` created: 2023-04-04 10:35:45 merged: 2023-04-07 07:47:41

20. [41263](http://github.com/cms-sw/cmssw/pull/41263){:target="_blank"}  from **@bsunanda**: Phase2-TB70 Add a simulation setup for radiation hardness studies of HGCal wafers `geometry` `upgrade` created: 2023-04-04 04:33:28 merged: 2023-04-10 13:53:24

21. [41262](http://github.com/cms-sw/cmssw/pull/41262){:target="_blank"}  from **@Dr15Jones**: Timing Service now measures time not running a Module `core` created: 2023-04-03 20:18:49 merged: 2023-04-07 15:16:48

22. [41254](http://github.com/cms-sw/cmssw/pull/41254){:target="_blank"}  from **@missirol**: remove duplicate plugin `HLTPFDiJetCorrCheckerWithDiTau` `hlt` created: 2023-04-02 12:29:44 merged: 2023-04-02 20:11:04

23. [41253](http://github.com/cms-sw/cmssw/pull/41253){:target="_blank"}  from **@srimanob**: Add DD4hep Phase2 wf in short,IB matrix `pdmv` `upgrade` created: 2023-04-02 02:23:18 merged: 2023-04-05 16:52:23

24. [41252](http://github.com/cms-sw/cmssw/pull/41252){:target="_blank"}  from **@bsunanda**: Phase2-gex158A Replace cout with edm::Logverbatim in Geometry/GlobalTrackingGeometryBuilder `geometry` `tracking` created: 2023-04-01 09:25:46 merged: 2023-04-06 04:56:29

25. [41248](http://github.com/cms-sw/cmssw/pull/41248){:target="_blank"}  from **@smuzaffar**: Re-enable unit tests for ASAN build `reconstruction` `core` `dqm` `heterogeneous` created: 2023-03-31 14:27:11 merged: 2023-04-06 05:44:23

26. [41247](http://github.com/cms-sw/cmssw/pull/41247){:target="_blank"}  from **@tvami**: Update Run-3 HI GTs to include ECAL spike-killers `alca` created: 2023-03-31 14:07:20 merged: 2023-03-31 17:37:12

27. [41244](http://github.com/cms-sw/cmssw/pull/41244){:target="_blank"}  from **@bsunanda**: Run3-gex158 Remove TimeMe in Geometry/DTGeometryBuilder to allow building the geometry routines in debug mode `geometry` created: 2023-03-31 09:18:58 merged: 2023-03-31 19:08:27

28. [41242](http://github.com/cms-sw/cmssw/pull/41242){:target="_blank"}  from **@radla118**: Update for the LumiPCC module veto list and afterglow factors `alca` created: 2023-03-31 07:40:09 merged: 2023-03-31 17:44:46

29. [41241](http://github.com/cms-sw/cmssw/pull/41241){:target="_blank"}  from **@bsunanda**: Phase2-gex157D Add new scripts to study material budgets for Phase2 geometries `dqm` `geometry` created: 2023-03-31 05:42:12 merged: 2023-04-04 09:26:41

30. [41240](http://github.com/cms-sw/cmssw/pull/41240){:target="_blank"}  from **@yuanchao**: add pt dependent SF and add legends on summary plots `db` created: 2023-03-31 03:29:57 merged: 2023-04-07 15:16:06

31. [41239](http://github.com/cms-sw/cmssw/pull/41239){:target="_blank"}  from **@stahlleiton**: Update FG HF thresholds to 2022 PbPb `alca` `l1` created: 2023-03-31 00:02:40 merged: 2023-04-04 12:05:27

32. [41238](http://github.com/cms-sw/cmssw/pull/41238){:target="_blank"}  from **@aloeliger**: Add default parameter description to L1TCaloLayer1 producer `l1` created: 2023-03-30 21:42:41 merged: 2023-03-31 07:28:29

33. [41237](http://github.com/cms-sw/cmssw/pull/41237){:target="_blank"}  from **@cms-sw**: Revert "Herwig lhe matching fix" `generators` created: 2023-03-30 16:31:15 merged: 2023-03-31 07:16:00

34. [41236](http://github.com/cms-sw/cmssw/pull/41236){:target="_blank"}  from **@AdrianoDee**: Add Wf `*.81` for BPH DQM `pdmv` `upgrade` created: 2023-03-30 15:07:18 merged: 2023-04-05 16:53:08

35. [41233](http://github.com/cms-sw/cmssw/pull/41233){:target="_blank"}  from **@dinyar**: Add "one loose" showers from EMTF and "two loose showers in different sectors" from uGMT to L1Tntuples `l1` created: 2023-03-30 12:59:13 merged: 2023-03-31 09:30:15

36. [41231](http://github.com/cms-sw/cmssw/pull/41231){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_0_X` (6/N): GRun menu V1.0 of 2023 [`13_1_X`] `hlt` created: 2023-03-30 12:52:43 merged: 2023-03-30 16:39:35

37. [41226](http://github.com/cms-sw/cmssw/pull/41226){:target="_blank"}  from **@kennedykiley**: Add HCAL LLP Jet Skim config `pdmv` created: 2023-03-29 17:37:39 merged: 2023-04-05 16:54:23

38. [41225](http://github.com/cms-sw/cmssw/pull/41225){:target="_blank"}  from **@mmusich**: Modernize / optimize `DisappearingMuonsSkimming` `pdmv` created: 2023-03-29 16:58:45 merged: 2023-04-11 09:54:26

39. [41221](http://github.com/cms-sw/cmssw/pull/41221){:target="_blank"}  from **@vshang**: Adding HCAL FB LUT to caloParams for uploading to DB `l1` `db` created: 2023-03-29 13:05:16 merged: 2023-04-10 19:57:03

40. [41219](http://github.com/cms-sw/cmssw/pull/41219){:target="_blank"}  from **@iarspider**: Fix DataFormats/Scouting tests on PowerPC `core` created: 2023-03-29 11:47:54 merged: 2023-03-30 06:27:16

41. [41218](http://github.com/cms-sw/cmssw/pull/41218){:target="_blank"}  from **@bsunanda**: Run3-gex157D Use edm::Log... instead of cout in Geometry/ForwardGeometry `geometry` created: 2023-03-29 09:35:28 merged: 2023-03-31 09:11:58

42. [41217](http://github.com/cms-sw/cmssw/pull/41217){:target="_blank"}  from **@swagata87**: [EGM] Remove obsolete Phase2 configs `hlt` created: 2023-03-29 09:01:07 merged: 2023-03-29 15:03:55

43. [41215](http://github.com/cms-sw/cmssw/pull/41215){:target="_blank"}  from **@bsunanda**: Run3-sim140 Small fix to SimG4CMS/Calo to enable builiding debug library `simulation` created: 2023-03-29 01:48:01 merged: 2023-03-29 11:58:45

44. [41213](http://github.com/cms-sw/cmssw/pull/41213){:target="_blank"}  from **@civanch**: Fixed memory grow at SIM step `simulation` created: 2023-03-28 17:59:48 merged: 2023-03-28 21:16:06

45. [41212](http://github.com/cms-sw/cmssw/pull/41212){:target="_blank"}  from **@ChuyuanLiu**: Fix axis title in tracking validation plots `dqm` `tracking` created: 2023-03-28 17:43:55 merged: 2023-03-29 05:14:01

46. [41211](http://github.com/cms-sw/cmssw/pull/41211){:target="_blank"}  from **@elfontan**: Adding 2Loose HMT showers in the GT emulator `l1` created: 2023-03-28 17:30:56 merged: 2023-04-01 10:32:19

47. [41208](http://github.com/cms-sw/cmssw/pull/41208){:target="_blank"}  from **@bsunanda**: Phase2-hgx336E Try to fix an error in the code for HGCal V16 Geometry and take care of the #define statement in Geometry/HGCalCommonData/src `geometry` `upgrade` created: 2023-03-28 09:12:55 merged: 2023-03-30 07:20:43

48. [41205](http://github.com/cms-sw/cmssw/pull/41205){:target="_blank"}  from **@mmusich**: Graphical improvements for TrackerAlignment_PayloadInspector `db` created: 2023-03-28 07:54:16 merged: 2023-03-28 14:18:50

49. [41204](http://github.com/cms-sw/cmssw/pull/41204){:target="_blank"}  from **@perrotta**: Remove unneeded header includes from DQM/CTPPS plugins `dqm` created: 2023-03-28 06:36:55 merged: 2023-03-29 05:12:43

50. [41202](http://github.com/cms-sw/cmssw/pull/41202){:target="_blank"}  from **@saumyaphor4252**: Update GEM geometry in 2023 MC GTs and L1 HI menu tag in 2022/2023 MC GTs `alca` created: 2023-03-27 21:16:40 merged: 2023-03-28 16:04:49

51. [41201](http://github.com/cms-sw/cmssw/pull/41201){:target="_blank"}  from **@Dr15Jones**: Added ShutdownSignal entry to JobReport `core` created: 2023-03-27 20:30:49 merged: 2023-03-31 07:42:54

52. [41193](http://github.com/cms-sw/cmssw/pull/41193){:target="_blank"}  from **@mmusich**: Re-introduce `BeamSpotOnlineProducer` for Phase-2 HLT menu `alca` `hlt` `reconstruction` `tracking` created: 2023-03-27 11:24:47 merged: 2023-04-03 16:13:54

53. [41192](http://github.com/cms-sw/cmssw/pull/41192){:target="_blank"}  from **@fmanteca**: Update HMT shower thresholds for Loose HMT emulation in CSC `l1` created: 2023-03-26 16:47:08 merged: 2023-03-27 15:38:56

54. [41191](http://github.com/cms-sw/cmssw/pull/41191){:target="_blank"}  from **@bsunanda**: Run3-gex157C Use edm::Log... instead of cout in Geometry/EcalMapping and Geometry/EcalTestBeam `geometry` created: 2023-03-26 16:18:36 merged: 2023-03-27 11:55:57

55. [41190](http://github.com/cms-sw/cmssw/pull/41190){:target="_blank"}  from **@bsunanda**: Phase2-hgx336D Improve testing of cassette shift computation for HGCal geometries `geometry` `upgrade` created: 2023-03-26 13:17:36 merged: 2023-03-28 10:52:52

56. [41187](http://github.com/cms-sw/cmssw/pull/41187){:target="_blank"}  from **@CTPPS**: PPS diamond mapping fix for 2023 run `alca` `dqm` `ctpps` created: 2023-03-25 20:19:07 merged: 2023-03-28 16:16:29

57. [41185](http://github.com/cms-sw/cmssw/pull/41185){:target="_blank"}  from **@eyigitba**: Added option to trigger on loose HMT showers in EMTF `l1` created: 2023-03-25 15:09:18 merged: 2023-03-27 21:31:43

58. [41183](http://github.com/cms-sw/cmssw/pull/41183){:target="_blank"}  from **@slava77**: add track algo and originalAlgo to PackedCandidates `reconstruction` `xpog` `tracking` created: 2023-03-25 00:23:50 merged: 2023-03-29 19:49:58

59. [41182](http://github.com/cms-sw/cmssw/pull/41182){:target="_blank"}  from **@dinyar**: Add loose bits to uGMT muon shower DQM plots `dqm` `l1t` created: 2023-03-24 17:12:36 merged: 2023-03-29 05:12:14

60. [41181](http://github.com/cms-sw/cmssw/pull/41181){:target="_blank"}  from **@civanch**: Geant4 user actions and CMS mctruth handling clean-up `simulation` created: 2023-03-24 17:07:29 merged: 2023-03-26 20:42:31

61. [41177](http://github.com/cms-sw/cmssw/pull/41177){:target="_blank"}  from **@missirol**: Add upper cut on jet time to `HLTJetTimingFilter` `hlt` created: 2023-03-24 15:02:37 merged: 2023-03-26 20:49:45

62. [41174](http://github.com/cms-sw/cmssw/pull/41174){:target="_blank"}  from **@bsunanda**: Run3-gex157B Replace use of cout's with LogVerbatim in Geometry/DTGeo metry and Geometry/DTGeometryBuilder `geometry` created: 2023-03-24 12:39:59 merged: 2023-03-28 07:21:52

63. [41173](http://github.com/cms-sw/cmssw/pull/41173){:target="_blank"}  from **@bsunanda**: Run3-gex157A Replace use of cout's with LogVerbatim in Geometry/CaloTopology and Geometry/CommonTopologies `geometry` created: 2023-03-24 11:39:45 merged: 2023-03-29 12:02:17

64. [41172](http://github.com/cms-sw/cmssw/pull/41172){:target="_blank"}  from **@dinyar**: Update muon shower (un)packers for 2023 running `l1` created: 2023-03-24 11:33:13 merged: 2023-03-27 12:12:38

65. [41170](http://github.com/cms-sw/cmssw/pull/41170){:target="_blank"}  from **@vukasinmilosevic**: Fixing the missing Tau plots within the L1T offline DQM `dqm` `l1` created: 2023-03-24 10:05:22 merged: 2023-03-27 13:23:20

66. [41169](http://github.com/cms-sw/cmssw/pull/41169){:target="_blank"}  from **@iarspider**: Fix build failure in DBG_X `geometry` `upgrade` created: 2023-03-24 08:14:46 merged: 2023-03-24 20:15:02

67. [41165](http://github.com/cms-sw/cmssw/pull/41165){:target="_blank"}  from **@Dr15Jones**: Use start time of cmsRun in CondorStatusService `core` created: 2023-03-23 21:04:05 merged: 2023-03-27 21:36:22

68. [41163](http://github.com/cms-sw/cmssw/pull/41163){:target="_blank"}  from **@Cvico**: Fix for nanoGEN jets `xpog` created: 2023-03-23 17:26:45 merged: 2023-03-24 13:48:07

69. [41161](http://github.com/cms-sw/cmssw/pull/41161){:target="_blank"}  from **@smuzaffar**: [ALCA-DB] Various fixes/improvements for unit test `alca` `db` `tracking` created: 2023-03-23 12:04:31 merged: 2023-03-23 16:21:36

70. [41160](http://github.com/cms-sw/cmssw/pull/41160){:target="_blank"}  from **@smuzaffar**: [ALCA-RECONSTRUCTION] Various fixes/improvements for unit test `reconstruction` `alca` `tracking` created: 2023-03-23 12:04:23 merged: 2023-03-24 11:00:06

71. [41159](http://github.com/cms-sw/cmssw/pull/41159){:target="_blank"}  from **@smuzaffar**: [GEOMETRY] Various fixes/improvements for unit test `geometry` `trk` created: 2023-03-23 12:04:02 merged: 2023-03-23 16:22:32

72. [41158](http://github.com/cms-sw/cmssw/pull/41158){:target="_blank"}  from **@smuzaffar**: [DB] Various fixes/improvements for unit test `db` `trk` created: 2023-03-23 12:03:56 merged: 2023-03-23 16:23:07

73. [41157](http://github.com/cms-sw/cmssw/pull/41157){:target="_blank"}  from **@smuzaffar**: [DB-DQM] Various fixes/improvements for unit test `dqm` `db` `tracking` created: 2023-03-23 12:03:47 merged: 2023-03-24 07:17:12

74. [41156](http://github.com/cms-sw/cmssw/pull/41156){:target="_blank"}  from **@smuzaffar**: [ALCA] Various fixes/improvements for unit test `alca` `trk` created: 2023-03-23 12:03:32 merged: 2023-03-23 16:23:49

75. [41155](http://github.com/cms-sw/cmssw/pull/41155){:target="_blank"}  from **@smuzaffar**: [DAQ] Various fixes/improvements for unit test `daq` created: 2023-03-23 12:03:25 merged: 2023-03-23 16:25:00

76. [41154](http://github.com/cms-sw/cmssw/pull/41154){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] Various fixes/improvements for unit test `reconstruction` `tracking` created: 2023-03-23 12:03:16 merged: 2023-03-24 11:00:15

77. [41153](http://github.com/cms-sw/cmssw/pull/41153){:target="_blank"}  from **@smuzaffar**: [GEOMETRY-UPGRADE] Various fixes/improvements for unit test `geometry` `upgrade` created: 2023-03-23 12:02:51 merged: 2023-03-24 10:53:14

78. [41152](http://github.com/cms-sw/cmssw/pull/41152){:target="_blank"}  from **@smuzaffar**: [DQM] Various fixes/improvements for unit test `dqm` `trk` created: 2023-03-23 12:02:44 merged: 2023-03-24 07:18:08

79. [41151](http://github.com/cms-sw/cmssw/pull/41151){:target="_blank"}  from **@smuzaffar**: [SIMULATION] Various fixes/improvements for unit test `simulation` created: 2023-03-23 12:02:15 merged: 2023-03-23 16:25:07

80. [41149](http://github.com/cms-sw/cmssw/pull/41149){:target="_blank"}  from **@eyigitba**: Add L1 Stage2 Digis to Cosmics AOD event content `l1` `operations` created: 2023-03-23 09:25:32 merged: 2023-04-11 10:08:15

81. [41148](http://github.com/cms-sw/cmssw/pull/41148){:target="_blank"}  from **@mmusich**: range-based loops in `SiStripFedCablingFakeESSource` `alca` `trk` created: 2023-03-23 09:06:45 merged: 2023-03-23 16:25:45

82. [41145](http://github.com/cms-sw/cmssw/pull/41145){:target="_blank"}  from **@youyingli**: Update autoSkim for 2023 data taking [13_1_X] `operations` `pdmv` `upgrade` created: 2023-03-23 04:25:11 merged: 2023-04-11 16:40:47

83. [41143](http://github.com/cms-sw/cmssw/pull/41143){:target="_blank"}  from **@smuzaffar**: [OPERATIONS] Various fixes/improvements for unit test `operations` created: 2023-03-22 17:18:43 merged: 2023-03-23 06:22:26

84. [41142](http://github.com/cms-sw/cmssw/pull/41142){:target="_blank"}  from **@smuzaffar**: [CORE] Various fixes/improvements for unit test `core` created: 2023-03-22 17:18:36 merged: 2023-03-23 05:55:45

85. [41141](http://github.com/cms-sw/cmssw/pull/41141){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION-XPOG] Various fixes/improvements for unit test `reconstruction` `xpog` created: 2023-03-22 17:18:29 merged: 2023-03-24 11:00:24

86. [41140](http://github.com/cms-sw/cmssw/pull/41140){:target="_blank"}  from **@smuzaffar**: [ALCA-DB] Various fixes/improvements for unit test `alca` `db` created: 2023-03-22 17:18:04 merged: 2023-03-23 05:57:31

87. [41139](http://github.com/cms-sw/cmssw/pull/41139){:target="_blank"}  from **@smuzaffar**: [GEOMETRY] Various fixes/improvements for unit test `geometry` created: 2023-03-22 17:17:57 merged: 2023-03-23 06:00:08

88. [41138](http://github.com/cms-sw/cmssw/pull/41138){:target="_blank"}  from **@smuzaffar**: [DB-DQM] Various fixes/improvements for unit test `dqm` `db` created: 2023-03-22 17:17:49 merged: 2023-03-23 08:23:42

89. [41137](http://github.com/cms-sw/cmssw/pull/41137){:target="_blank"}  from **@smuzaffar**: [ANALYSIS] Various fixes/improvements for unit test `analysis` created: 2023-03-22 17:17:32 merged: 2023-03-23 06:24:08

90. [41136](http://github.com/cms-sw/cmssw/pull/41136){:target="_blank"}  from **@smuzaffar**: [ALCA] Various fixes/improvements for unit test `alca` `trk` created: 2023-03-22 17:17:22 merged: 2023-03-23 06:19:45

91. [41135](http://github.com/cms-sw/cmssw/pull/41135){:target="_blank"}  from **@smuzaffar**: [GENERATORS] Various fixes/improvements for unit test `generators` created: 2023-03-22 17:17:15 merged: 2023-03-24 11:00:31

92. [41134](http://github.com/cms-sw/cmssw/pull/41134){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] Various fixes/improvements for unit test `reconstruction` created: 2023-03-22 17:16:54 merged: 2023-03-24 11:00:38

93. [41133](http://github.com/cms-sw/cmssw/pull/41133){:target="_blank"}  from **@smuzaffar**: [DQM] Various fixes/improvements for unit test `dqm` created: 2023-03-22 17:16:42 merged: 2023-03-23 09:08:24

94. [41132](http://github.com/cms-sw/cmssw/pull/41132){:target="_blank"}  from **@smuzaffar**: [SIMULATION] Various fixes/improvements for unit test `simulation` created: 2023-03-22 17:16:25 merged: 2023-03-23 06:20:28

95. [41131](http://github.com/cms-sw/cmssw/pull/41131){:target="_blank"}  from **@fabiocos**: MTD digitization: Add calculation of per SiPM time resolution to BtlElectronicsSim `simulation` `upgrade` created: 2023-03-22 16:48:53 merged: 2023-03-23 09:13:09

96. [41130](http://github.com/cms-sw/cmssw/pull/41130){:target="_blank"}  from **@mmusich**: adapt Tracker Alignment Payload Inspector for phase-2 `db` created: 2023-03-22 15:55:04 merged: 2023-03-23 06:30:18

97. [41129](http://github.com/cms-sw/cmssw/pull/41129){:target="_blank"}  from **@mmusich**: Update `AlignableTracker` for phase-2 Outer Tracker `alca` `trk` created: 2023-03-22 15:50:34 merged: 2023-03-30 20:27:07

98. [41128](http://github.com/cms-sw/cmssw/pull/41128){:target="_blank"}  from **@igv4321**: HcalPFCuts database table and relevant infrastructure `alca` `db` created: 2023-03-22 15:24:12 merged: 2023-03-30 21:00:14

99. [41127](http://github.com/cms-sw/cmssw/pull/41127){:target="_blank"}  from **@mmusich**: introduce `SiStripNoisesAndBadCompsChecker` `db` `trk` created: 2023-03-22 14:02:37 merged: 2023-03-23 10:08:45

100. [41125](http://github.com/cms-sw/cmssw/pull/41125){:target="_blank"}  from **@smorovic**: (13_1_X) streamer format padding `alca` `core` `dqm` created: 2023-03-21 21:44:39 merged: 2023-03-27 14:01:18

101. [41124](http://github.com/cms-sw/cmssw/pull/41124){:target="_blank"}  from **@Dr15Jones**: Add temporary failure element to Framework Job Report `core` created: 2023-03-21 19:05:05 merged: 2023-03-26 20:54:47

102. [41123](http://github.com/cms-sw/cmssw/pull/41123){:target="_blank"}  from **@francescobrivio**: Update BeamSpot for 2022 EOY MC `alca` `pdmv` `upgrade` created: 2023-03-21 17:22:06 merged: 2023-04-03 16:12:49

103. [41120](http://github.com/cms-sw/cmssw/pull/41120){:target="_blank"}  from **@mmusich**: fix peak mode SiStrip noise payload in 2018 cosmics simulation `alca` created: 2023-03-21 15:54:05 merged: 2023-03-23 18:14:45

104. [41118](http://github.com/cms-sw/cmssw/pull/41118){:target="_blank"}  from **@iarspider**: Update to new ONNXRuntime api `dqm` `reconstruction` created: 2023-03-21 13:07:46 merged: 2023-04-10 19:55:35

105. [41093](http://github.com/cms-sw/cmssw/pull/41093){:target="_blank"}  from **@missirol**: a first unit test for backward compatibility of Scouting data formats `core` created: 2023-03-17 22:42:29 merged: 2023-03-24 07:50:50

106. [41077](http://github.com/cms-sw/cmssw/pull/41077){:target="_blank"}  from **@sunilUIET**: reverting back to run3_data_relval for making rereco GT default in relval [13_1_X] `alca` `pdmv` `upgrade` created: 2023-03-17 03:59:42 merged: 2023-03-23 08:29:35

107. [41058](http://github.com/cms-sw/cmssw/pull/41058){:target="_blank"}  from **@mmusich**: Move `RecoPixelVertexing` subsystems to `RecoTracker` `alca` `dqm` `fastsim` `hlt` `operations` `reconstruction` `pdmv` `upgrade` `tracking` `trk` created: 2023-03-15 08:07:59 merged: 2023-03-31 07:50:19

108. [41057](http://github.com/cms-sw/cmssw/pull/41057){:target="_blank"}  from **@qyguo**: Muon efficiency measurement for GEM `dqm` `gem` created: 2023-03-15 07:27:30 merged: 2023-03-23 10:32:13

109. [41048](http://github.com/cms-sw/cmssw/pull/41048){:target="_blank"}  from **@bsunanda**: Phase2-hgx336C Try to introduce the guard rings for both full and partial wafers of HGCal (will be a part of V18) `geometry` `simulation` `upgrade` created: 2023-03-14 07:46:27 merged: 2023-03-23 09:26:50

110. [41036](http://github.com/cms-sw/cmssw/pull/41036){:target="_blank"}  from **@aloeliger**: Modify L1TGlobal menu code and CondFormats to remove reinterpret_cast to and from utm firmware "es" types `alca` `dqm` `l1` `db` `l1t` created: 2023-03-11 01:12:26 merged: 2023-03-23 12:46:06

111. [41003](http://github.com/cms-sw/cmssw/pull/41003){:target="_blank"}  from **@srimanob**: Update short matrix to use Phase-2 D95 geometry `pdmv` `upgrade` created: 2023-03-09 08:23:05 merged: 2023-03-31 19:05:22

112. [41001](http://github.com/cms-sw/cmssw/pull/41001){:target="_blank"}  from **@wddgit**: Implement ExternalWork for ESProducers `core` created: 2023-03-08 22:05:23 merged: 2023-03-24 08:01:08

113. [40939](http://github.com/cms-sw/cmssw/pull/40939){:target="_blank"}  from **@Dominic-Stafford**: Herwig lhe matching fix `generators` created: 2023-03-02 18:47:45 merged: 2023-03-29 04:44:37

114. [40899](http://github.com/cms-sw/cmssw/pull/40899){:target="_blank"}  from **@gartung**: PerfTools/JeProf: Make a library that allows a call to jemalloc profile heap dump function. `core` created: 2023-02-28 18:23:58 merged: 2023-03-24 20:18:26

115. [40895](http://github.com/cms-sw/cmssw/pull/40895){:target="_blank"}  from **@CTPPS**: Added DQM module for PPS dedicated random stream `dqm` `ctpps` created: 2023-02-28 15:22:17 merged: 2023-03-27 14:13:58

116. [40876](http://github.com/cms-sw/cmssw/pull/40876){:target="_blank"}  from **@andrea21z**: Removing not used muon MVAs from miniAOD `reconstruction` `xpog` `muon` created: 2023-02-24 14:25:03 merged: 2023-03-27 13:17:51

117. [40855](http://github.com/cms-sw/cmssw/pull/40855){:target="_blank"}  from **@jhakala**: Improved method for EB digi simulation `simulation` `alca` `operations` `pdmv` `db` `upgrade` `ecal` created: 2023-02-23 00:40:50 merged: 2023-04-01 09:00:30

118. [40803](http://github.com/cms-sw/cmssw/pull/40803){:target="_blank"}  from **@nurfikri89**: [BTV] PUPPI ValueMap-compatible Deep taggers info producers `reconstruction` `xpog` `btv` created: 2023-02-17 08:34:54 merged: 2023-03-27 21:53:37

119. [40745](http://github.com/cms-sw/cmssw/pull/40745){:target="_blank"}  from **@scooperstein**: Integration of extended ParticleNet trainings for simultaneous jet flavor tagging, pT regression, and tau ID + reconstruction `reconstruction` `xpog` `btv` `tau` `jetmet` created: 2023-02-10 13:56:53 merged: 2023-04-03 16:11:43

120. [40663](http://github.com/cms-sw/cmssw/pull/40663){:target="_blank"}  from **@Sam-Harper**: L1Nano addition `l1` `pdmv` `upgrade` `xpog` created: 2023-02-01 16:09:39 merged: 2023-04-01 09:26:22

121. [34618](http://github.com/cms-sw/cmssw/pull/34618){:target="_blank"}  from **@dan131riley**: CUDA implementation of RecoLocalTracker/SiStripCluster  ClustersFromRawProducer `alca` `reconstruction` `heterogeneous` `trk` created: 2021-07-25 21:17:23 merged: 2023-03-27 13:52:42

#### CMSDIST Changes between Tags REL/CMSSW_13_1_0_pre2/el8_amd64_gcc11 and REL/CMSSW_13_1_0_pre3/el8_amd64_gcc11:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_13_1_0_pre2/el8_amd64_gcc11...REL/CMSSW_13_1_0_pre3/el8_amd64_gcc11)



1. [8432](http://github.com/cms-sw/cmsdist/pull/8432){:target="_blank"}  from **@belforte**: bump crab-prod to v3.230404 created: 2023-04-06 12:28:53 merged: 2023-04-06 19:49:11

2. [8430](http://github.com/cms-sw/cmsdist/pull/8430){:target="_blank"}  from **@cms-sw**: PGO: CMSSW_PGO_DIRECTORY only for pgo generation created: 2023-04-05 13:30:01 merged: 2023-04-05 13:58:14

3. [8427](http://github.com/cms-sw/cmsdist/pull/8427){:target="_blank"}  from **@belforte**: bump crab-dev to latest tag created: 2023-04-04 09:33:04 merged: 2023-04-04 16:47:46

4. [8426](http://github.com/cms-sw/cmsdist/pull/8426){:target="_blank"}  from **@iarspider**: Updated root to tip of branch v6-26-00-patches created: 2023-04-04 08:36:47 merged: 2023-04-04 16:49:49

5. [8422](http://github.com/cms-sw/cmsdist/pull/8422){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-15-00 created: 2023-04-04 03:30:37 merged: 2023-04-04 03:31:46

6. [8420](http://github.com/cms-sw/cmsdist/pull/8420){:target="_blank"}  from **@cms-sw**: [PGO] Initial changes to support PGO builds created: 2023-04-03 10:15:31 merged: 2023-04-04 13:16:23

7. [8419](http://github.com/cms-sw/cmsdist/pull/8419){:target="_blank"}  from **@fwyzard**: Update hwloc to version 2.9.1 created: 2023-04-03 09:58:28 merged: 2023-04-05 19:19:21

8. [8417](http://github.com/cms-sw/cmsdist/pull/8417){:target="_blank"}  from **@cms-sw**: Revert "Add patches to propagate lhe numbering through herwig" created: 2023-03-30 16:31:34 merged: 2023-03-31 07:15:52

9. [8416](http://github.com/cms-sw/cmsdist/pull/8416){:target="_blank"}  from **@novicecpp**: bump crab-prod to v3.230227 created: 2023-03-30 11:08:40 merged: 2023-04-03 09:08:48

10. [8415](http://github.com/cms-sw/cmsdist/pull/8415){:target="_blank"}  from **@cms-sw**: Update G4 11.1.1, vecgeom 1.2.1, clhep 2.4.6 and G4-data created: 2023-03-29 12:17:11 merged: 2023-04-10 11:33:45

11. [8411](http://github.com/cms-sw/cmsdist/pull/8411){:target="_blank"}  from **@cms-sw**: yaml-cpp: fix relocation created: 2023-03-28 21:03:30 merged: 2023-03-29 08:07:30

12. [8410](http://github.com/cms-sw/cmsdist/pull/8410){:target="_blank"}  from **@forthommel**: Imported yaml-cpp 0.7.0 created: 2023-03-28 13:27:43 merged: 2023-03-28 20:59:42

13. [8409](http://github.com/cms-sw/cmsdist/pull/8409){:target="_blank"}  from **@cms-sw**: Update tag for CondTools-Hcal to V00-01-00 created: 2023-03-28 13:21:17 merged: 2023-03-28 15:06:46

14. [8407](http://github.com/cms-sw/cmsdist/pull/8407){:target="_blank"}  from **@cms-sw**: [FWLite] Added utm dependency created: 2023-03-24 08:44:41 merged: 2023-03-24 08:47:14

15. [8406](http://github.com/cms-sw/cmsdist/pull/8406){:target="_blank"}  from **@cms-sw**: improved unit test message created: 2023-03-23 14:43:50 merged: 2023-03-23 20:00:10

16. [8405](http://github.com/cms-sw/cmsdist/pull/8405){:target="_blank"}  from **@cms-sw**: drop G4GEOM_USE_USOLIDS flag to fix G4 compilation warnings in cmssw created: 2023-03-23 06:51:31 merged: 2023-03-23 19:54:23

17. [8404](http://github.com/cms-sw/cmsdist/pull/8404){:target="_blank"}  from **@cms-sw**: Update cms-common: map rhel/rocky/alma distros to el created: 2023-03-22 16:22:37 merged: 2023-03-22 20:24:21

18. [8397](http://github.com/cms-sw/cmsdist/pull/8397){:target="_blank"}  from **@cms-sw**: Update onnxruntime to 1.14.1 created: 2023-03-20 13:48:55 merged: 2023-04-10 20:42:36

19. [8396](http://github.com/cms-sw/cmsdist/pull/8396){:target="_blank"}  from **@aandvalenzuela**: Update ROOT in master created: 2023-03-20 12:58:30 merged: 2023-03-23 06:27:07

20. [8349](http://github.com/cms-sw/cmsdist/pull/8349){:target="_blank"}  from **@Dominic-Stafford**: Add patches to propagate lhe numbering through herwig created: 2023-03-02 18:29:50 merged: 2023-03-29 19:33:05
