---
layout: post
rel_link:  "13_1_0_pre2"
title:  "CMSSW_13_1_0_pre2"
date:   2023-03-22 17:59:19
categories: cmssw
relmajor: 13
relminor: 1
relsubminor: 0
relpre: _pre2
---

# CMSSW_13_1_0_pre2
#### Changes since CMSSW_13_1_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_13_1_0_pre1...CMSSW_13_1_0_pre2)



1. [41121](http://github.com/cms-sw/cmssw/pull/41121){:target="_blank"}  from **@mmusich**: Remove the const_cast from SiStripFedCablingFakeESSource `alca` `trk` created: 2023-03-21 16:43:28 merged: 2023-03-22 07:28:25

2. [41119](http://github.com/cms-sw/cmssw/pull/41119){:target="_blank"}  from **@saumyaphor4252**: Include Phase2 TkAl Rcds in Phase2 MC GT with T21 tags `alca` created: 2023-03-21 15:09:05 merged: 2023-03-22 09:11:00

3. [41116](http://github.com/cms-sw/cmssw/pull/41116){:target="_blank"}  from **@mmusich**: Fix several unit test post-merge of #41075 `alca` `reconstruction` `simulation` `db` `tracking` `trk` created: 2023-03-21 09:44:33 merged: 2023-03-22 09:29:22

4. [41113](http://github.com/cms-sw/cmssw/pull/41113){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_0_X` (5/N) [`13_1_X`] `hlt` created: 2023-03-21 08:45:46 merged: 2023-03-21 15:48:08

5. [41110](http://github.com/cms-sw/cmssw/pull/41110){:target="_blank"}  from **@hahnjo**: Add CMSHepEmTrackingManager `simulation` created: 2023-03-20 16:37:24 merged: 2023-03-21 09:06:46

6. [41109](http://github.com/cms-sw/cmssw/pull/41109){:target="_blank"}  from **@wddgit**: HcalDigiDump.cc Migrate consumesMany to GetterOfProducts `simulation` created: 2023-03-20 16:18:48 merged: 2023-03-21 09:08:39

7. [41103](http://github.com/cms-sw/cmssw/pull/41103){:target="_blank"}  from **@smuzaffar**: [Geom] Avoid unit tests failures in DBG IBs `geometry` created: 2023-03-20 11:22:45 merged: 2023-03-20 15:35:13

8. [41102](http://github.com/cms-sw/cmssw/pull/41102){:target="_blank"}  from **@smuzaffar**: [Core] Fix unit tests for DBG IBs `core` created: 2023-03-20 10:11:00 merged: 2023-03-20 15:36:43

9. [41100](http://github.com/cms-sw/cmssw/pull/41100){:target="_blank"}  from **@perrotta**: Reduce non necessary sqrt computations in RecoTauTag/HLTProducers `hlt` created: 2023-03-19 17:05:28 merged: 2023-03-21 14:39:25

10. [41099](http://github.com/cms-sw/cmssw/pull/41099){:target="_blank"}  from **@swagata87**: Remove unnecessary open e/gamma paths from Phase2 HLT menu `hlt` `egamma` created: 2023-03-19 12:45:53 merged: 2023-03-20 22:17:08

11. [41098](http://github.com/cms-sw/cmssw/pull/41098){:target="_blank"}  from **@bsunanda**: Run3-gex155B Modify the mode of several script files in CondTools/Geometry/test/writehelpers so that the execution of creating geometry payload script can run smoothly `db` created: 2023-03-19 11:19:44 merged: 2023-03-19 21:49:47

12. [41096](http://github.com/cms-sw/cmssw/pull/41096){:target="_blank"}  from **@smorovic**: DAQ: fix file descriptor close in DAQSource (13_1_X) `daq` created: 2023-03-18 12:38:16 merged: 2023-03-19 15:16:33

13. [41095](http://github.com/cms-sw/cmssw/pull/41095){:target="_blank"}  from **@mandrenguyen**: HI 2023 relval wfs + realistic 2022 vtx smearing `alca` `generators` `pdmv` `upgrade` created: 2023-03-18 09:18:11 merged: 2023-03-22 08:46:08

14. [41094](http://github.com/cms-sw/cmssw/pull/41094){:target="_blank"}  from **@tvami**: Move leftover PoolDBOutputService modules to use kSharedResource `alca` `db` `trk` created: 2023-03-18 03:02:50 merged: 2023-03-20 07:43:31

15. [41092](http://github.com/cms-sw/cmssw/pull/41092){:target="_blank"}  from **@mbluj**: Add tau decay-mode to genTauJets as status `analysis` created: 2023-03-17 17:49:56 merged: 2023-03-19 15:29:04

16. [41090](http://github.com/cms-sw/cmssw/pull/41090){:target="_blank"}  from **@smuzaffar**: Unit test: Do not generate files in top level directory `generators` created: 2023-03-17 16:13:19 merged: 2023-03-20 12:27:13

17. [41083](http://github.com/cms-sw/cmssw/pull/41083){:target="_blank"}  from **@ctarricone**: MTD Validation: Update Btl Local Reco Monitoring `dqm` created: 2023-03-17 11:05:21 merged: 2023-03-20 09:05:29

18. [41082](http://github.com/cms-sw/cmssw/pull/41082){:target="_blank"}  from **@smuzaffar**: [unit test] make sure copied directory has write permissions `alca` `trk` created: 2023-03-17 10:21:07 merged: 2023-03-18 07:20:18

19. [41081](http://github.com/cms-sw/cmssw/pull/41081){:target="_blank"}  from **@bsunanda**: Phase2-gex156 Provide a dump geometry of GEM detectors to enable testing the missing components `geometry` created: 2023-03-17 09:57:43 merged: 2023-03-18 06:55:46

20. [41080](http://github.com/cms-sw/cmssw/pull/41080){:target="_blank"}  from **@mmusich**: fix ASAN Segmentation failure & heap-buffer-overflow in unit test `Alignment/OfflineValidation/GCPall` `alca` `trk` created: 2023-03-17 08:46:36 merged: 2023-03-18 07:19:29

21. [41076](http://github.com/cms-sw/cmssw/pull/41076){:target="_blank"}  from **@tvami**: Remove bTagging tags from Run3 data GTs `alca` created: 2023-03-16 19:21:06 merged: 2023-03-17 09:03:25

22. [41075](http://github.com/cms-sw/cmssw/pull/41075){:target="_blank"}  from **@mmusich**: Apply Tracker Alignment to phase2 geometries `alca` `geometry` `upgrade` created: 2023-03-16 19:02:08 merged: 2023-03-20 17:10:17

23. [41074](http://github.com/cms-sw/cmssw/pull/41074){:target="_blank"}  from **@Dr15Jones**: Added new cms::errors::ExternalFailure exception `core` created: 2023-03-16 17:45:10 merged: 2023-03-17 07:25:07

24. [41073](http://github.com/cms-sw/cmssw/pull/41073){:target="_blank"}  from **@Dr15Jones**: Have ExternalGeneratorFilter throw an generator specific exception `generators` created: 2023-03-16 16:29:50 merged: 2023-03-20 11:35:07

25. [41072](http://github.com/cms-sw/cmssw/pull/41072){:target="_blank"}  from **@saumyaphor4252**: Include EcalSimComponentShapeRcd in all MC GTs and remove TkAl Rcds from Phase2 MC GT `alca` created: 2023-03-16 16:00:37 merged: 2023-03-17 07:17:06

26. [41070](http://github.com/cms-sw/cmssw/pull/41070){:target="_blank"}  from **@smuzaffar**: [CORE] Cleanup USE_UNITTEST_DIR which is now enabled at project level `core` created: 2023-03-16 11:03:57 merged: 2023-03-16 20:58:42

27. [41069](http://github.com/cms-sw/cmssw/pull/41069){:target="_blank"}  from **@smuzaffar**: [DQM-GEOMETRY] Cleanup USE_UNITTEST_DIR which is now enabled at project level `dqm` `geometry` created: 2023-03-16 11:03:42 merged: 2023-03-17 07:12:16

28. [41068](http://github.com/cms-sw/cmssw/pull/41068){:target="_blank"}  from **@smuzaffar**: [ALCA] Cleanup USE_UNITTEST_DIR which is now enabled at project level `alca` `trk` created: 2023-03-16 11:03:05 merged: 2023-03-16 13:49:18

29. [41067](http://github.com/cms-sw/cmssw/pull/41067){:target="_blank"}  from **@smuzaffar**: [PDMV-UPGRADE] Cleanup USE_UNITTEST_DIR which is now enabled at project level `pdmv` `upgrade` created: 2023-03-16 11:02:45 merged: 2023-03-20 15:49:30

30. [41066](http://github.com/cms-sw/cmssw/pull/41066){:target="_blank"}  from **@smuzaffar**: [DB] Cleanup USE_UNITTEST_DIR which is now enabled at project level `db` created: 2023-03-16 11:02:16 merged: 2023-03-16 13:41:52

31. [41065](http://github.com/cms-sw/cmssw/pull/41065){:target="_blank"}  from **@mmusich**: More refined error treatment in trend of efficiency vs lumi, PU and BX in `SiStripHitEfficiencyHarvester` `alca` `trk` created: 2023-03-15 20:27:11 merged: 2023-03-16 21:02:11

32. [41064](http://github.com/cms-sw/cmssw/pull/41064){:target="_blank"}  from **@Dr15Jones**: Make jets in TauGenJetProducer from taus which are not decayed `analysis` created: 2023-03-15 19:52:51 merged: 2023-03-17 14:15:53

33. [41063](http://github.com/cms-sw/cmssw/pull/41063){:target="_blank"}  from **@civanch**: Added CMS SIM event manager `simulation` created: 2023-03-15 17:33:12 merged: 2023-03-18 06:53:23

34. [41061](http://github.com/cms-sw/cmssw/pull/41061){:target="_blank"}  from **@jalimena**: [HLT validation and DQM] update for new EXO displaced photon + HT path for 2023 (13_1_X) `dqm` created: 2023-03-15 16:00:38 merged: 2023-03-21 07:56:39

35. [41056](http://github.com/cms-sw/cmssw/pull/41056){:target="_blank"}  from **@bsunanda**: Run3-alca141  Correct and extend the macros for HCAL isoTrac calibration and these are now used in geeting response correction factors for 2023 data `alca` created: 2023-03-15 06:51:26 merged: 2023-03-15 13:12:17

36. [41054](http://github.com/cms-sw/cmssw/pull/41054){:target="_blank"}  from **@Dr15Jones**: Added TypeMatch to be used with GetterOfProducts `core` created: 2023-03-14 17:16:00 merged: 2023-03-17 07:44:14

37. [41052](http://github.com/cms-sw/cmssw/pull/41052){:target="_blank"}  from **@Dr15Jones**: Added EventSetup module timing to Timing Service `core` created: 2023-03-14 14:44:53 merged: 2023-03-15 09:41:35

38. [41051](http://github.com/cms-sw/cmssw/pull/41051){:target="_blank"}  from **@swagata87**: Adapt latest PF settings in Phase2 Egamma HLT `hlt` created: 2023-03-14 12:58:08 merged: 2023-03-17 07:30:41

39. [41050](http://github.com/cms-sw/cmssw/pull/41050){:target="_blank"}  from **@mmusich**: Clean-up in `CalibTracker/SiStripHitEfficiency` and add trend of efficiency vs lumi, PU and BX in `SiStripHitEfficiencyHarvester` `alca` `trk` created: 2023-03-14 12:44:07 merged: 2023-03-15 13:13:44

40. [41047](http://github.com/cms-sw/cmssw/pull/41047){:target="_blank"}  from **@fwyzard**: Make the beam spot configuration of the Phase-2 HLT menu more consistent `hlt` created: 2023-03-13 21:32:22 merged: 2023-03-14 19:10:22

41. [41044](http://github.com/cms-sw/cmssw/pull/41044){:target="_blank"}  from **@smuzaffar**: fix unit test: avoid creating data files in src tree `db` created: 2023-03-13 17:15:12 merged: 2023-03-14 13:23:35

42. [41042](http://github.com/cms-sw/cmssw/pull/41042){:target="_blank"}  from **@dinyar**: Add logic to produce "two loose showers in different sectors" in the MuonShowerProducer `l1` created: 2023-03-13 16:08:56 merged: 2023-03-15 13:14:31

43. [41041](http://github.com/cms-sw/cmssw/pull/41041){:target="_blank"}  from **@dmeuser**: Update of HG PCL tracker alignment max movement thresholds `alca` `db` created: 2023-03-13 15:48:55 merged: 2023-03-14 13:26:35

44. [41039](http://github.com/cms-sw/cmssw/pull/41039){:target="_blank"}  from **@swertz**: [Nano] Fix JetTable genJetIdx matching `xpog` created: 2023-03-13 10:28:12 merged: 2023-03-20 15:39:34

45. [41037](http://github.com/cms-sw/cmssw/pull/41037){:target="_blank"}  from **@missirol**: remove duplicates from `PhysicsTools/TensorFlow/test/BuildFile.xml` `reconstruction` created: 2023-03-12 19:42:34 merged: 2023-03-16 21:45:24

46. [41033](http://github.com/cms-sw/cmssw/pull/41033){:target="_blank"}  from **@smuzaffar**: [DQM] Various fixes/improvements for unit test `dqm` created: 2023-03-10 18:16:40 merged: 2023-03-13 07:56:42

47. [41032](http://github.com/cms-sw/cmssw/pull/41032){:target="_blank"}  from **@smuzaffar**: [CORE] Various fixes/improvements for unit test `core` created: 2023-03-10 18:16:13 merged: 2023-03-13 14:42:55

48. [41031](http://github.com/cms-sw/cmssw/pull/41031){:target="_blank"}  from **@smuzaffar**: [GEOMETRY-UPGRADE] Various fixes/improvements for unit test `geometry` `upgrade` created: 2023-03-10 18:14:55 merged: 2023-03-11 13:11:47

49. [41030](http://github.com/cms-sw/cmssw/pull/41030){:target="_blank"}  from **@smuzaffar**: [HLT] Various fixes/improvements for unit test `hlt` created: 2023-03-10 18:14:38 merged: 2023-03-11 08:05:08

50. [41029](http://github.com/cms-sw/cmssw/pull/41029){:target="_blank"}  from **@smuzaffar**: [ALCA] Various fixes/improvements for unit test `alca` `trk` created: 2023-03-10 18:14:04 merged: 2023-03-11 08:01:19

51. [41028](http://github.com/cms-sw/cmssw/pull/41028){:target="_blank"}  from **@hftsoi**: Layer1 unpacker and DQM modified for HCALFB `dqm` `l1` `hcal` `l1t` created: 2023-03-10 18:07:50 merged: 2023-03-16 22:12:58

52. [41027](http://github.com/cms-sw/cmssw/pull/41027){:target="_blank"}  from **@fabiocos**: MTD digitization: add position dependence to BTL amplitudes `dqm` `simulation` `upgrade` created: 2023-03-10 17:46:22 merged: 2023-03-20 09:33:22

53. [41026](http://github.com/cms-sw/cmssw/pull/41026){:target="_blank"}  from **@fabiocos**: MTD geometry: update tests to scenario D95 `dqm` `geometry` `reconstruction` `upgrade` created: 2023-03-10 17:25:38 merged: 2023-03-13 15:02:02

54. [41025](http://github.com/cms-sw/cmssw/pull/41025){:target="_blank"}  from **@arsahasransu**: Add additional track variables to the Run 3 scouting electron collection for low pT electrons. `core` `hlt` created: 2023-03-10 17:03:17 merged: 2023-03-17 09:42:48

55. [41024](http://github.com/cms-sw/cmssw/pull/41024){:target="_blank"}  from **@smuzaffar**: [CORE] Various fixes/improvements for unit test `core` created: 2023-03-10 16:23:47 merged: 2023-03-13 08:01:49

56. [41023](http://github.com/cms-sw/cmssw/pull/41023){:target="_blank"}  from **@Dr15Jones**: Removed deprecated EventSetup signals from ActivityRegistry `core` created: 2023-03-10 15:42:38 merged: 2023-03-11 08:02:37

57. [41022](http://github.com/cms-sw/cmssw/pull/41022){:target="_blank"}  from **@civanch**: Cleanup and preparation for sim extentions `simulation` created: 2023-03-10 14:49:45 merged: 2023-03-13 16:10:08

58. [41021](http://github.com/cms-sw/cmssw/pull/41021){:target="_blank"}  from **@cerminar**: Add Correlator Layer-2 e/g objects to the Phase-2 event content `l1` created: 2023-03-10 13:38:11 merged: 2023-03-11 08:09:13

59. [41019](http://github.com/cms-sw/cmssw/pull/41019){:target="_blank"}  from **@makortel**: Fix implicit host-to-device copy for ES data products with labels in Alpaka ESProducers `heterogeneous` created: 2023-03-09 21:40:31 merged: 2023-03-13 15:59:09

60. [41016](http://github.com/cms-sw/cmssw/pull/41016){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_0_X` (4/N) [`13_1_X`] `hlt` `pdmv` `upgrade` created: 2023-03-09 18:16:04 merged: 2023-03-10 14:24:21

61. [41015](http://github.com/cms-sw/cmssw/pull/41015){:target="_blank"}  from **@smuzaffar**: [HETEROGENEOUS] Various fixes/improvements for unit test `heterogeneous` created: 2023-03-09 16:32:57 merged: 2023-03-09 19:53:22

62. [41014](http://github.com/cms-sw/cmssw/pull/41014){:target="_blank"}  from **@smuzaffar**: [ALCA] Various fixes/improvements for unit test `alca` `trk` created: 2023-03-09 16:32:04 merged: 2023-03-09 19:53:34

63. [41013](http://github.com/cms-sw/cmssw/pull/41013){:target="_blank"}  from **@smuzaffar**: [SIMULATION] Various fixes/improvements for unit test `simulation` created: 2023-03-09 16:31:03 merged: 2023-03-10 06:19:14

64. [41012](http://github.com/cms-sw/cmssw/pull/41012){:target="_blank"}  from **@smuzaffar**: [CORE] Various fixes/improvements for unit test `core` created: 2023-03-09 16:29:19 merged: 2023-03-10 09:02:53

65. [41010](http://github.com/cms-sw/cmssw/pull/41010){:target="_blank"}  from **@suchandradutta**: Phase2 Tracker Digitizer updated to have the possibility to used planer pixel algorithm in 3D pixel `simulation` `upgrade` `trk` created: 2023-03-09 15:27:38 merged: 2023-03-13 16:08:01

66. [41009](http://github.com/cms-sw/cmssw/pull/41009){:target="_blank"}  from **@civanch**: Improved initialisation of Geant4e propagator `simulation` `tracking` created: 2023-03-09 11:36:39 merged: 2023-03-09 19:54:07

67. [41008](http://github.com/cms-sw/cmssw/pull/41008){:target="_blank"}  from **@yuanchao**: Payload Inspector plugin for Jet Resolution and SF `db` created: 2023-03-09 10:55:40 merged: 2023-03-14 19:13:06

68. [41005](http://github.com/cms-sw/cmssw/pull/41005){:target="_blank"}  from **@saumyaphor4252**: Update L1 menu tag for data RelVals and 2023/2024, Phase2 MC GTs `alca` created: 2023-03-09 09:10:52 merged: 2023-03-10 14:24:07

69. [41004](http://github.com/cms-sw/cmssw/pull/41004){:target="_blank"}  from **@portalesHEP**: L1 matching module for VBF+dijet HLT `hlt` created: 2023-03-09 08:46:22 merged: 2023-03-18 07:03:12

70. [40999](http://github.com/cms-sw/cmssw/pull/40999){:target="_blank"}  from **@smuzaffar**: [GEOMETRY-UPGRADE] Various fixes/improvements for unit test `geometry` `upgrade` created: 2023-03-08 16:59:03 merged: 2023-03-09 10:31:04

71. [40998](http://github.com/cms-sw/cmssw/pull/40998){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION-UPGRADE] Various fixes/improvements for unit test `reconstruction` `upgrade` created: 2023-03-08 16:57:54 merged: 2023-03-09 08:00:24

72. [40997](http://github.com/cms-sw/cmssw/pull/40997){:target="_blank"}  from **@smuzaffar**: [CORE] Various fixes/improvements for unit test `core` created: 2023-03-08 16:57:10 merged: 2023-03-09 08:04:36

73. [40994](http://github.com/cms-sw/cmssw/pull/40994){:target="_blank"}  from **@brallmond**: Add plugin to use existing HLTDoubleSinglet module with two PFJets and one RecoEcalCandidate `hlt` created: 2023-03-08 14:12:50 merged: 2023-03-08 17:09:46

74. [40993](http://github.com/cms-sw/cmssw/pull/40993){:target="_blank"}  from **@brallmond**: extended existing HLT tau-jet correlation module `hlt` created: 2023-03-08 12:17:28 merged: 2023-03-09 21:08:05

75. [40989](http://github.com/cms-sw/cmssw/pull/40989){:target="_blank"}  from **@mmusich**: Fix Phase-1 Barrel Pixel Inner / Outer ladders numbering in several monitoring tools `alca` `db` `trk` created: 2023-03-08 10:25:06 merged: 2023-03-16 15:30:36

76. [40988](http://github.com/cms-sw/cmssw/pull/40988){:target="_blank"}  from **@smuzaffar**: [Core] Unit tests fixes/improvements `core` created: 2023-03-08 09:21:33 merged: 2023-03-08 14:59:27

77. [40987](http://github.com/cms-sw/cmssw/pull/40987){:target="_blank"}  from **@bsunanda**: Phase2-hgx336B Make the first step to provide an option for guard ring in HGCal simulation `geometry` `upgrade` created: 2023-03-08 09:14:21 merged: 2023-03-09 12:46:15

78. [40986](http://github.com/cms-sw/cmssw/pull/40986){:target="_blank"}  from **@bmarzocc**: Customize to produce & save ECAL-only caloparticles `dqm` `ecal` created: 2023-03-07 19:28:12 merged: 2023-03-14 13:27:24

79. [40985](http://github.com/cms-sw/cmssw/pull/40985){:target="_blank"}  from **@trackreco**: mkFit: technical fixes for standalone build only `reconstruction` `tracking` created: 2023-03-07 18:11:00 merged: 2023-03-09 11:22:50

80. [40984](http://github.com/cms-sw/cmssw/pull/40984){:target="_blank"}  from **@Dr15Jones**: Use anonymous namespace in CandIsolatorFromDeposits `reconstruction` created: 2023-03-07 17:37:43 merged: 2023-03-08 11:05:03

81. [40983](http://github.com/cms-sw/cmssw/pull/40983){:target="_blank"}  from **@AdrianoDee**: Allow to Skim Unused Input Prototracks `reconstruction` `tracking` created: 2023-03-07 17:21:48 merged: 2023-03-09 10:40:29

82. [40981](http://github.com/cms-sw/cmssw/pull/40981){:target="_blank"}  from **@mmusich**: `SiPixelDynamicInefficiency_PayloadInspector` fix issue with PU parametrization plot polynomial representation `db` `trk` created: 2023-03-07 09:59:54 merged: 2023-03-07 13:46:47

83. [40978](http://github.com/cms-sw/cmssw/pull/40978){:target="_blank"}  from **@smuzaffar**: [ALCA-DB] Various fixes/improvements for unit test `alca` `db` created: 2023-03-07 08:16:38 merged: 2023-03-07 13:48:13

84. [40977](http://github.com/cms-sw/cmssw/pull/40977){:target="_blank"}  from **@smuzaffar**: [CORE] Various fixes/improvements for unit test `core` created: 2023-03-07 07:32:59 merged: 2023-03-08 07:31:46

85. [40976](http://github.com/cms-sw/cmssw/pull/40976){:target="_blank"}  from **@smuzaffar**: [DQM-GEOMETRY] Various fixes/improvements for unit test `dqm` `geometry` created: 2023-03-07 07:32:35 merged: 2023-03-09 10:29:28

86. [40975](http://github.com/cms-sw/cmssw/pull/40975){:target="_blank"}  from **@smuzaffar**: [DB] Various fixes/improvements for unit test `db` created: 2023-03-07 07:32:01 merged: 2023-03-07 13:49:16

87. [40974](http://github.com/cms-sw/cmssw/pull/40974){:target="_blank"}  from **@smuzaffar**: [SIMULATION] Various fixes/improvements for unit test `simulation` `trk` created: 2023-03-07 07:31:39 merged: 2023-03-07 13:50:13

88. [40973](http://github.com/cms-sw/cmssw/pull/40973){:target="_blank"}  from **@smuzaffar**: [DQM] Various fixes/improvements for unit test `dqm` `tracking` created: 2023-03-07 07:30:12 merged: 2023-03-09 10:26:31

89. [40972](http://github.com/cms-sw/cmssw/pull/40972){:target="_blank"}  from **@smuzaffar**: [ALCA] Various fixes/improvements for unit test `alca` `trk` created: 2023-03-07 07:29:46 merged: 2023-03-07 13:52:50

90. [40970](http://github.com/cms-sw/cmssw/pull/40970){:target="_blank"}  from **@bsunanda**: Run3-alca240 Add one more isolated bunch AlCaReco to the AlCa matrix `alca` created: 2023-03-07 04:57:43 merged: 2023-03-13 09:55:15

91. [40969](http://github.com/cms-sw/cmssw/pull/40969){:target="_blank"}  from **@bsunanda**: Run3-alca239 Add a file which is used for phi-symmetry calibration using local runs of HCAL `alca` created: 2023-03-07 04:55:55 merged: 2023-03-16 07:38:39

92. [40968](http://github.com/cms-sw/cmssw/pull/40968){:target="_blank"}  from **@bsunanda**: Run3-alca237X Add the possibility of providing depth-dependent correction factors from muon studies to IsoTrack analysis in HCAL calibration `alca` created: 2023-03-07 03:50:54 merged: 2023-03-07 14:04:26

93. [40965](http://github.com/cms-sw/cmssw/pull/40965){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_0_X` (3/N) [`13_1_X`] `hlt` created: 2023-03-06 22:16:13 merged: 2023-03-07 10:11:10

94. [40964](http://github.com/cms-sw/cmssw/pull/40964){:target="_blank"}  from **@Dr15Jones**: Add vertex of problem tau in HepMCValidationHelper `generators` `dqm` created: 2023-03-06 19:45:37 merged: 2023-03-10 15:15:46

95. [40963](http://github.com/cms-sw/cmssw/pull/40963){:target="_blank"}  from **@mmusich**: fix segmentation violation in `SiStripHitEffFromCalibTree` and `SiStripHitResolFromCalibTree` in ASAN_X `alca` `trk` created: 2023-03-06 16:51:02 merged: 2023-03-06 21:40:01

96. [40962](http://github.com/cms-sw/cmssw/pull/40962){:target="_blank"}  from **@Dr15Jones**: Make sure variables are preserved in ReggeGribovPartonMCInterface `generators` created: 2023-03-06 16:33:33 merged: 2023-03-16 21:00:34

97. [40961](http://github.com/cms-sw/cmssw/pull/40961){:target="_blank"}  from **@nhduongvn**: Handle invalid entries in <data-access> of site-local-config.xml `core` created: 2023-03-06 14:21:44 merged: 2023-03-16 06:35:34

98. [40960](http://github.com/cms-sw/cmssw/pull/40960){:target="_blank"}  from **@smorovic**: DAQ: New input source (13_1_X) `core` `daq` created: 2023-03-06 14:12:29 merged: 2023-03-15 16:22:19

99. [40959](http://github.com/cms-sw/cmssw/pull/40959){:target="_blank"}  from **@bsunanda**: Phase2-hgx336A Correct the nonzzero cassette shift scenario for HGCal `geometry` `upgrade` created: 2023-03-06 09:46:12 merged: 2023-03-07 10:23:07

100. [40958](http://github.com/cms-sw/cmssw/pull/40958){:target="_blank"}  from **@jeongeun**: Migrate consumesMany to GetterOfProducts in DQMServices `dqm` created: 2023-03-06 08:33:57 merged: 2023-03-09 10:25:46

101. [40954](http://github.com/cms-sw/cmssw/pull/40954){:target="_blank"}  from **@srimanob**: 13_1: 2023 FastSim Workflow `pdmv` `upgrade` created: 2023-03-03 16:07:04 merged: 2023-03-04 17:00:06

102. [40953](http://github.com/cms-sw/cmssw/pull/40953){:target="_blank"}  from **@smorovic**: DAQ: fix noninitialized pointer in input source `daq` created: 2023-03-03 15:47:20 merged: 2023-03-06 11:29:03

103. [40952](http://github.com/cms-sw/cmssw/pull/40952){:target="_blank"}  from **@bsunanda**: Run3-alca238 Modify the output content for 2 isolated bunch AlCaReco modules of HCAL `alca` created: 2023-03-03 15:36:06 merged: 2023-03-13 09:55:27

104. [40950](http://github.com/cms-sw/cmssw/pull/40950){:target="_blank"}  from **@mmusich**: `SiPixelPayloadInspectorHelper`: fix warning: '<anonymous>' may be used uninitialized `db` `trk` created: 2023-03-03 14:11:03 merged: 2023-03-04 08:01:33

105. [40944](http://github.com/cms-sw/cmssw/pull/40944){:target="_blank"}  from **@mmusich**: prevent `heap-buffer-overflow` in `SiPixelDynamicInefficiencyPUParametrization` `db` `trk` created: 2023-03-03 09:18:03 merged: 2023-03-03 15:21:30

106. [40933](http://github.com/cms-sw/cmssw/pull/40933){:target="_blank"}  from **@abdoulline**: Activating v7 of HF ShowerLibrary  `geometry` created: 2023-03-02 15:06:32 merged: 2023-03-03 13:47:32

107. [40931](http://github.com/cms-sw/cmssw/pull/40931){:target="_blank"}  from **@eyigitba**: Modify EMTF unpacker to support new reduced DAQ window for 2023 data taking `l1` created: 2023-03-02 13:02:02 merged: 2023-03-03 10:24:02

108. [40928](http://github.com/cms-sw/cmssw/pull/40928){:target="_blank"}  from **@missirol**: use unique names for outputs of HLT-DQM unit tests `dqm` `hlt` created: 2023-03-02 09:55:06 merged: 2023-03-03 09:58:51

109. [40926](http://github.com/cms-sw/cmssw/pull/40926){:target="_blank"}  from **@bsunanda**: Run3-sim139 Replace cout with G4cout in SimG4CMS/Muon `simulation` created: 2023-03-02 09:26:32 merged: 2023-03-03 10:25:41

110. [40923](http://github.com/cms-sw/cmssw/pull/40923){:target="_blank"}  from **@jeongeun**: Migrate consumesMany() to edm::GetterOfProducts() in GlobalRecHitsAnalyzer `dqm` created: 2023-03-02 07:33:03 merged: 2023-03-20 08:56:55

111. [40918](http://github.com/cms-sw/cmssw/pull/40918){:target="_blank"}  from **@missirol**: avoid duplicates in `HLTPMMassFilter` plugin `hlt` created: 2023-03-01 17:34:34 merged: 2023-03-02 16:07:32

112. [40916](http://github.com/cms-sw/cmssw/pull/40916){:target="_blank"}  from **@lwang046**: HcalDQM: Fix HFRaddam event type `dqm` `hcal` created: 2023-03-01 17:13:45 merged: 2023-03-06 11:20:54

113. [40914](http://github.com/cms-sw/cmssw/pull/40914){:target="_blank"}  from **@iarspider**: Disable clang's bitwise-instead-of-logical warnings for some parts of code `reconstruction` `tracking` created: 2023-03-01 13:24:15 merged: 2023-03-02 17:30:05

114. [40913](http://github.com/cms-sw/cmssw/pull/40913){:target="_blank"}  from **@fabiocos**: MTD validation: ETL digi per LGAD multiplicity monitoring `dqm` created: 2023-03-01 11:45:11 merged: 2023-03-03 10:28:01

115. [40912](http://github.com/cms-sw/cmssw/pull/40912){:target="_blank"}  from **@beaucero**: HLT Phase2 Removing Duplicate Modules `hlt` created: 2023-03-01 11:31:19 merged: 2023-03-14 13:29:44

116. [40909](http://github.com/cms-sw/cmssw/pull/40909){:target="_blank"}  from **@Soumyatifr**: eg hlt filter threshold reduction to 15 \GeV from 20\GeV `xpog` created: 2023-03-01 10:58:09 merged: 2023-03-06 15:15:26

117. [40906](http://github.com/cms-sw/cmssw/pull/40906){:target="_blank"}  from **@guitargeek**: Clean unused dependencies from BuildFiles `analysis` `alca` `core` `dqm` `geometry` `l1` `reconstruction` `simulation` `upgrade` `heterogeneous` `tracking` `trk` created: 2023-03-01 10:16:06 merged: 2023-03-04 08:38:36

118. [40903](http://github.com/cms-sw/cmssw/pull/40903){:target="_blank"}  from **@bsunanda**: Run3-alca237 Modify most of the scripts needed to get IsoTrack calibration of HCAL `alca` created: 2023-03-01 07:19:55 merged: 2023-03-06 21:46:36

119. [40900](http://github.com/cms-sw/cmssw/pull/40900){:target="_blank"}  from **@carriganm95**: updated tau HLT paths for disappearing tracks skim `pdmv` created: 2023-02-28 19:30:53 merged: 2023-03-10 14:25:40

120. [40890](http://github.com/cms-sw/cmssw/pull/40890){:target="_blank"}  from **@dinyar**: Update muon shower data formats for 2023 running `l1` created: 2023-02-27 17:22:39 merged: 2023-03-13 14:53:44

121. [40886](http://github.com/cms-sw/cmssw/pull/40886){:target="_blank"}  from **@bsunanda**: Run3-gex155A Additional files to make payloads for 2023 Geometry `db` created: 2023-02-27 01:56:53 merged: 2023-03-09 21:08:59

122. [40879](http://github.com/cms-sw/cmssw/pull/40879){:target="_blank"}  from **@makortel**: Fix propagation of an earlier exception in Transformer `core` created: 2023-02-24 19:29:37 merged: 2023-03-16 07:49:40

123. [40849](http://github.com/cms-sw/cmssw/pull/40849){:target="_blank"}  from **@makortel**: Allow access to const edm::{Event,EventSetup} from device::{Event,EventSetup} `heterogeneous` created: 2023-02-22 17:03:39 merged: 2023-03-02 20:34:00

124. [40819](http://github.com/cms-sw/cmssw/pull/40819){:target="_blank"}  from **@civanch**: Fixed low energy GFLASH `simulation` created: 2023-02-20 10:14:53 merged: 2023-03-08 07:38:41

125. [40814](http://github.com/cms-sw/cmssw/pull/40814){:target="_blank"}  from **@kpedro88**: Ragged batching interface for SonicTriton `heterogeneous` created: 2023-02-17 19:31:58 merged: 2023-03-02 16:05:24

126. [40666](http://github.com/cms-sw/cmssw/pull/40666){:target="_blank"}  from **@revering**: Added skimming filter for disappearing muons `pdmv` created: 2023-02-01 18:08:31 merged: 2023-03-19 15:11:39

127. [40096](http://github.com/cms-sw/cmssw/pull/40096){:target="_blank"}  from **@cecilecaillol**: [L1T] Phase-2, Update Track Selection Emulation to Match Firmware `l1` `upgrade` created: 2022-11-17 09:54:35 merged: 2023-03-03 16:09:16

#### CMSDIST Changes between Tags REL/CMSSW_13_1_0_pre1/el8_amd64_gcc11 and REL/CMSSW_13_1_0_pre2/el8_amd64_gcc11:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_13_1_0_pre1/el8_amd64_gcc11...REL/CMSSW_13_1_0_pre2/el8_amd64_gcc11)



1. [8403](http://github.com/cms-sw/cmsdist/pull/8403){:target="_blank"}  from **@cms-sw**: [SCRAM] disply BuildFile name in case of parsing errors created: 2023-03-22 15:21:10 merged: 2023-03-22 16:45:49

2. [8399](http://github.com/cms-sw/cmsdist/pull/8399){:target="_blank"}  from **@cms-sw**: [BuildRules] Re-revert to tag V07-09-00 created: 2023-03-21 16:13:14 merged: 2023-03-22 14:27:42

3. [8398](http://github.com/cms-sw/cmsdist/pull/8398){:target="_blank"}  from **@cms-sw**: Revert config tag to V07-08-00 created: 2023-03-21 06:42:30 merged: 2023-03-21 06:42:44

4. [8393](http://github.com/cms-sw/cmsdist/pull/8393){:target="_blank"}  from **@cms-sw**: [jemalloc] move common sections in to jemalloc-common created: 2023-03-19 19:14:00 merged: 2023-03-20 09:02:38

5. [8392](http://github.com/cms-sw/cmsdist/pull/8392){:target="_blank"}  from **@cms-sw**: [BuildRules] More updates for unit tests created: 2023-03-18 12:14:58 merged: 2023-03-20 21:26:07

6. [8390](http://github.com/cms-sw/cmsdist/pull/8390){:target="_blank"}  from **@cms-sw**: [Geant4] Fix LTO warnings about uninitialized variables created: 2023-03-16 19:01:27 merged: 2023-03-17 07:28:56

7. [8389](http://github.com/cms-sw/cmsdist/pull/8389){:target="_blank"}  from **@gartung**: Rename jemalloc libraries with debug and profiling options enabled. created: 2023-03-16 13:55:48 merged: 2023-03-19 09:48:44

8. [8387](http://github.com/cms-sw/cmsdist/pull/8387){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-EgammaPhotonProducers to V00-03-00 created: 2023-03-15 13:58:04 merged: 2023-03-15 14:02:14

9. [8386](http://github.com/cms-sw/cmsdist/pull/8386){:target="_blank"}  from **@aloeliger**: Update utm to v0.11.2 created: 2023-03-15 10:54:26 merged: 2023-03-16 17:40:12

10. [8385](http://github.com/cms-sw/cmsdist/pull/8385){:target="_blank"}  from **@cms-sw**: [BuildRules] Enable usage of separate unit tests directory at project level created: 2023-03-15 06:58:30 merged: 2023-03-16 06:23:33

11. [8384](http://github.com/cms-sw/cmsdist/pull/8384){:target="_blank"}  from **@jmduarte**: update AXOL1TL to 1.0.0 created: 2023-03-15 04:21:20 merged: 2023-03-16 17:40:41

12. [8383](http://github.com/cms-sw/cmsdist/pull/8383){:target="_blank"}  from **@fwyzard**: Update UCX to version 1.14.0 created: 2023-03-14 15:41:38 merged: 2023-03-15 07:37:04

13. [8382](http://github.com/cms-sw/cmsdist/pull/8382){:target="_blank"}  from **@fwyzard**: Explicitly use the GNU binutils ld.bfd linker created: 2023-03-14 10:37:48 merged: 2023-03-16 19:03:40

14. [8379](http://github.com/cms-sw/cmsdist/pull/8379){:target="_blank"}  from **@jmduarte**: Add AXOL1TL extras spec created: 2023-03-14 02:50:06 merged: 2023-03-14 16:42:22

15. [8377](http://github.com/cms-sw/cmsdist/pull/8377){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-11-00 created: 2023-03-13 15:01:53 merged: 2023-03-13 15:02:18

16. [8376](http://github.com/cms-sw/cmsdist/pull/8376){:target="_blank"}  from **@cms-sw**: Create RPM macro to generate CMAKE_PREFIX_PATH created: 2023-03-13 13:42:46 merged: 2023-03-14 14:14:20

17. [8375](http://github.com/cms-sw/cmsdist/pull/8375){:target="_blank"}  from **@epalencia**: Update UTM to 0.11.1 created: 2023-03-13 11:21:59 merged: 2023-03-14 08:28:35

18. [8372](http://github.com/cms-sw/cmsdist/pull/8372){:target="_blank"}  from **@cms-sw**: Build ONNXRuntime for same cuda archs as the rest of cms externals created: 2023-03-12 11:19:31 merged: 2023-03-12 19:29:09

19. [8370](http://github.com/cms-sw/cmsdist/pull/8370){:target="_blank"}  from **@fwyzard**: Package the HIP/ROCm and ROCrand libraries created: 2023-03-09 23:41:44 merged: 2023-03-21 17:11:13

20. [8369](http://github.com/cms-sw/cmsdist/pull/8369){:target="_blank"}  from **@cms-sw**: [BuildRules] Add CMSSW_BASE/tmp to CMSSW_SEARCH_PATH for unit tests created: 2023-03-09 16:27:53 merged: 2023-03-09 22:40:28

21. [8368](http://github.com/cms-sw/cmsdist/pull/8368){:target="_blank"}  from **@hahnjo**: Update G4HepEm to new pre-release created: 2023-03-09 14:33:14 merged: 2023-03-17 11:52:48

22. [8366](http://github.com/cms-sw/cmsdist/pull/8366){:target="_blank"}  from **@cms-sw**: [BuildRules] More fixes for running tests in individual dirs created: 2023-03-08 16:47:13 merged: 2023-03-09 05:16:13

23. [8365](http://github.com/cms-sw/cmsdist/pull/8365){:target="_blank"}  from **@cms-sw**: [BuildRules] [unit test] Fix for full release test directory created: 2023-03-08 11:07:23 merged: 2023-03-08 11:08:56

24. [8364](http://github.com/cms-sw/cmsdist/pull/8364){:target="_blank"}  from **@fwyzard**: Update to cuDNN 8.8.0, pyCUDA 2022.2.2 created: 2023-03-07 21:28:27 merged: 2023-03-09 09:30:57

25. [8361](http://github.com/cms-sw/cmsdist/pull/8361){:target="_blank"}  from **@cms-sw**: [BuildRules] Changes for running unit tests from separate test dirs created: 2023-03-06 14:13:25 merged: 2023-03-06 20:20:48

26. [8356](http://github.com/cms-sw/cmsdist/pull/8356){:target="_blank"}  from **@fwyzard**: Replace c++1z with c++17 created: 2023-03-04 18:00:22 merged: 2023-03-05 15:01:48

27. [8351](http://github.com/cms-sw/cmsdist/pull/8351){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-EgammaPhotonProducers to V00-02-00 created: 2023-03-02 18:35:48 merged: 2023-03-02 18:36:11

28. [8350](http://github.com/cms-sw/cmsdist/pull/8350){:target="_blank"}  from **@cms-sw**: Update tag for RecoEcal-EgammaClusterProducers to V00-03-00 created: 2023-03-02 18:32:52 merged: 2023-03-02 18:35:32

29. [8348](http://github.com/cms-sw/cmsdist/pull/8348){:target="_blank"}  from **@cms-sw**: Update tag for HeterogeneousCore-SonicTriton to V00-02-00 created: 2023-03-02 17:09:40 merged: 2023-03-02 17:19:06

30. [8346](http://github.com/cms-sw/cmsdist/pull/8346){:target="_blank"}  from **@fwyzard**: [BuildRules] Enable alpaka ROCm backend created: 2023-03-02 11:08:01 merged: 2023-03-03 07:22:15

31. [8345](http://github.com/cms-sw/cmsdist/pull/8345){:target="_blank"}  from **@cms-sw**: Update ROOT 6.26 in CMSSW master created: 2023-03-02 10:13:16 merged: 2023-03-03 15:21:52

32. [8324](http://github.com/cms-sw/cmsdist/pull/8324){:target="_blank"}  from **@kpedro88**: Update Triton client to version 2.25 created: 2023-02-17 19:32:00 merged: 2023-03-02 18:32:34

33. [8292](http://github.com/cms-sw/cmsdist/pull/8292){:target="_blank"}  from **@cms-sw**: [SimG4CMS-Calo] Update HFShowerLibrary_run3_v7 created: 2023-02-06 11:57:10 merged: 2023-03-02 13:03:30
