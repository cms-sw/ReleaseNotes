---
layout: post
rel_link:  "12_3_0_pre6"
title:  "CMSSW_12_3_0_pre6"
date:   2022-03-10 15:38:09
categories: cmssw
relmajor: 12
relminor: 3
relsubminor: 0
relpre: _pre6
---

# CMSSW_12_3_0_pre6
#### Changes since CMSSW_12_3_0_pre5:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_3_0_pre5...CMSSW_12_3_0_pre6)



1. [37185](http://github.com/cms-sw/cmssw/pull/37185){:target="_blank"}  from **@perrotta**: Tighten check for the number of weights in GenWeightValidation `dqm` `generators` created: 2022-03-09 14:44:37 merged: 2022-03-10 01:45:59

2. [37183](http://github.com/cms-sw/cmssw/pull/37183){:target="_blank"}  from **@bsunanda**: Run3-hcx331 Cleanup some of the codes in Validation/HcalRecHits `dqm` created: 2022-03-09 09:49:26 merged: 2022-03-10 08:53:39

3. [37182](http://github.com/cms-sw/cmssw/pull/37182){:target="_blank"}  from **@dan131riley**: fix thinnedAssociationsHelperPtr scope error `core` created: 2022-03-09 00:50:14 merged: 2022-03-09 14:16:33

4. [37181](http://github.com/cms-sw/cmssw/pull/37181){:target="_blank"}  from **@missirol**: handle inverted filters in `TriggerObjectStandAlone` `reconstruction` created: 2022-03-08 21:42:29 merged: 2022-03-09 17:30:57

5. [37177](http://github.com/cms-sw/cmssw/pull/37177){:target="_blank"}  from **@mmasciov**: Update DQM (offline + HLTEvF) HLT track monitoring for Run3 era `dqm` `hlt` created: 2022-03-08 16:54:11 merged: 2022-03-09 14:08:06

6. [37176](http://github.com/cms-sw/cmssw/pull/37176){:target="_blank"}  from **@mmasciov**: Add std::move to std::vector member of Run3ScoutingMuon `core` created: 2022-03-08 15:19:45 merged: 2022-03-09 00:33:59

7. [37173](http://github.com/cms-sw/cmssw/pull/37173){:target="_blank"}  from **@cms-tsg-storm**: Use of new AlCa GTs for run3 relval in TSG tests `hlt` created: 2022-03-08 13:34:55 merged: 2022-03-08 18:00:06

8. [37171](http://github.com/cms-sw/cmssw/pull/37171){:target="_blank"}  from **@malbouis**: Update autoCond.py to include GTs with fixed L1 Menu for Run3 `alca` created: 2022-03-08 12:22:18 merged: 2022-03-08 17:58:11

9. [37170](http://github.com/cms-sw/cmssw/pull/37170){:target="_blank"}  from **@suchandradutta**: Adding MacroPixel inefficiency in Tracker Phase2Digitizer `simulation` `upgrade` created: 2022-03-08 11:31:08 merged: 2022-03-10 09:11:21

10. [37166](http://github.com/cms-sw/cmssw/pull/37166){:target="_blank"}  from **@bsunanda**: run3-alca222 Make use of ESGetToken in CondTools/Hcal/test/stubs/HcalCalibrationsAnalyzer.cc `db` created: 2022-03-08 07:21:51 merged: 2022-03-08 14:30:21

11. [37165](http://github.com/cms-sw/cmssw/pull/37165){:target="_blank"}  from **@bsunanda**: Run3-hcx330 Cleanup some of the codes in Validation/HcalHits `dqm` created: 2022-03-08 07:14:04 merged: 2022-03-10 08:54:17

12. [37164](http://github.com/cms-sw/cmssw/pull/37164){:target="_blank"}  from **@yuanchao**: Migrate deprecated EDModule for CondFormats/DTObjects `alca` `db` created: 2022-03-08 02:39:02 merged: 2022-03-08 12:56:12

13. [37160](http://github.com/cms-sw/cmssw/pull/37160){:target="_blank"}  from **@Dr15Jones**: Use ZSTD and default compression for PoolOutputModule `core` created: 2022-03-07 15:13:00 merged: 2022-03-07 20:19:24

14. [37159](http://github.com/cms-sw/cmssw/pull/37159){:target="_blank"}  from **@fwyzard**: Define HOST_DEVICE_CONSTANT to implement constexpr aggregate host/device constants `core` created: 2022-03-07 13:46:34 merged: 2022-03-08 15:25:55

15. [37158](http://github.com/cms-sw/cmssw/pull/37158){:target="_blank"}  from **@trtomei**: Adding optionality for MTD timing in PFTICLProducer `reconstruction` `upgrade` created: 2022-03-07 13:17:51 merged: 2022-03-09 11:26:17

16. [37156](http://github.com/cms-sw/cmssw/pull/37156){:target="_blank"}  from **@jainshilpi**: Fix for the access of haloMVATaggerVal in the Run 1+2 files `reconstruction` created: 2022-03-07 08:15:07 merged: 2022-03-08 09:09:43

17. [37154](http://github.com/cms-sw/cmssw/pull/37154){:target="_blank"}  from **@mmusich**: Use externally produced trajectory in ExtenderWithMTD, customise needed TrajectoryInEvent also for PixelLess iteration `reconstruction` created: 2022-03-07 07:51:43 merged: 2022-03-08 12:53:12

18. [37153](http://github.com/cms-sw/cmssw/pull/37153){:target="_blank"}  from **@perrotta**: Remove dead assignments from BTagSF.cc `analysis` created: 2022-03-06 18:26:09 merged: 2022-03-07 06:38:23

19. [37152](http://github.com/cms-sw/cmssw/pull/37152){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_3_X` `hlt` created: 2022-03-06 06:35:42 merged: 2022-03-07 09:22:12

20. [37149](http://github.com/cms-sw/cmssw/pull/37149){:target="_blank"}  from **@mmasciov**: Revisit usage of HitPattern in DataFormats/Scouting `core` `hlt` `reconstruction` created: 2022-03-05 19:30:52 merged: 2022-03-08 15:09:03

21. [37148](http://github.com/cms-sw/cmssw/pull/37148){:target="_blank"}  from **@srimanob**: Add warning to add DD4hep in GeometryConf `geometry` `upgrade` created: 2022-03-05 17:42:42 merged: 2022-03-06 04:28:21

22. [37147](http://github.com/cms-sw/cmssw/pull/37147){:target="_blank"}  from **@CTPPS**: XML and FedId configuration update for PPS `alca` `reconstruction` created: 2022-03-04 19:33:12 merged: 2022-03-09 14:19:01

23. [37145](http://github.com/cms-sw/cmssw/pull/37145){:target="_blank"}  from **@smuzaffar**: Added unit test to run pede from millepede `alca` created: 2022-03-04 18:25:24 merged: 2022-03-05 01:19:05

24. [37144](http://github.com/cms-sw/cmssw/pull/37144){:target="_blank"}  from **@malbouis**: Include HLT JEC and L1T Menu tags in data, mcRun3 and mcRun4 GTs `alca` created: 2022-03-04 16:58:20 merged: 2022-03-05 06:38:07

25. [37143](http://github.com/cms-sw/cmssw/pull/37143){:target="_blank"}  from **@mmusich**: `BeamSpot` Payload Inspector: introduce payload parameters comparator `db` created: 2022-03-04 15:24:38 merged: 2022-03-07 00:38:39

26. [37142](http://github.com/cms-sw/cmssw/pull/37142){:target="_blank"}  from **@srimanob**: Fix dtSpecFilter of M9 and add DD4hep wf for D77 `geometry` `pdmv` `upgrade` created: 2022-03-04 12:46:58 merged: 2022-03-08 00:47:10

27. [37141](http://github.com/cms-sw/cmssw/pull/37141){:target="_blank"}  from **@AliinCern**: Cuda time measurements `heterogeneous` created: 2022-03-04 11:18:15 merged: 2022-03-07 16:43:06

28. [37139](http://github.com/cms-sw/cmssw/pull/37139){:target="_blank"}  from **@slava77**: add quality selections in MkFitOutputConverter `reconstruction` created: 2022-03-04 03:38:44 merged: 2022-03-07 17:59:59

29. [37133](http://github.com/cms-sw/cmssw/pull/37133){:target="_blank"}  from **@NiharSaha**: Drop type specs for Trigger `dqm` created: 2022-03-03 17:07:19 merged: 2022-03-04 15:28:12

30. [37132](http://github.com/cms-sw/cmssw/pull/37132){:target="_blank"}  from **@cms-tsg-storm**: Update of L1T menu in TSG GTs to L1Menu_Collisions2022_v0_1_6_xml `hlt` created: 2022-03-03 16:13:24 merged: 2022-03-04 13:41:49

31. [37130](http://github.com/cms-sw/cmssw/pull/37130){:target="_blank"}  from **@tvami**: Add `AlcaPCCIntegrator` modules to the AlCa no ConcurrentLumis list `alca` created: 2022-03-03 14:32:39 merged: 2022-03-05 16:46:40

32. [37128](http://github.com/cms-sw/cmssw/pull/37128){:target="_blank"}  from **@fwyzard**: Add an option to cmsDriver for selecting the accelerators to use `operations` `heterogeneous` created: 2022-03-03 10:32:31 merged: 2022-03-04 13:57:38

33. [37127](http://github.com/cms-sw/cmssw/pull/37127){:target="_blank"}  from **@mmusich**: modernize `TriggerHelper` and migrate to usage of `DCSRecord` `dqm` created: 2022-03-03 10:10:01 merged: 2022-03-04 14:39:31

34. [37124](http://github.com/cms-sw/cmssw/pull/37124){:target="_blank"}  from **@yuanchao**: Migrate deprecated EDAnalyzers in CondTools/DT to the One version. `db` created: 2022-03-02 22:56:42 merged: 2022-03-04 15:48:49

35. [37123](http://github.com/cms-sw/cmssw/pull/37123){:target="_blank"}  from **@thomreis**: ECAL DQM - Add WF .513 for ECAL GPU vs. CPU validation `dqm` `pdmv` `upgrade` `heterogeneous` created: 2022-03-02 22:44:52 merged: 2022-03-09 17:35:37

36. [37122](http://github.com/cms-sw/cmssw/pull/37122){:target="_blank"}  from **@leonardogiannini**: Speed-up seed/dup. cleaning mkFit `reconstruction` created: 2022-03-02 20:55:04 merged: 2022-03-09 00:32:06

37. [37121](http://github.com/cms-sw/cmssw/pull/37121){:target="_blank"}  from **@wweiphy**: Merged central modules at L3&L4 in SiPixelLorentzAngle PCL workflow `alca` created: 2022-03-02 18:34:10 merged: 2022-03-03 16:58:06

38. [37120](http://github.com/cms-sw/cmssw/pull/37120){:target="_blank"}  from **@mmusich**: consolidate `CalibTracker/SiStripQuality` `alca` `db` created: 2022-03-02 18:02:07 merged: 2022-03-04 00:56:40

39. [37118](http://github.com/cms-sw/cmssw/pull/37118){:target="_blank"}  from **@Dr15Jones**: Removed excess printing in FWCore/ParameterSet tests `core` created: 2022-03-02 16:27:51 merged: 2022-03-03 00:56:22

40. [37117](http://github.com/cms-sw/cmssw/pull/37117){:target="_blank"}  from **@andrea21z**: DQM HLT Muon cleaning `dqm` created: 2022-03-02 15:05:25 merged: 2022-03-08 13:01:43

41. [37116](http://github.com/cms-sw/cmssw/pull/37116){:target="_blank"}  from **@cms-tau-pog**: Add PFDiJetCorrCheckerWithDiTau producer for DoubleTau+VBF-jets HLT paths `hlt` created: 2022-03-02 10:45:50 merged: 2022-03-04 00:54:53

42. [37114](http://github.com/cms-sw/cmssw/pull/37114){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_3_X` `hlt` created: 2022-03-02 05:29:17 merged: 2022-03-02 12:12:16

43. [37112](http://github.com/cms-sw/cmssw/pull/37112){:target="_blank"}  from **@cvuosalo**: [DD4hep] Add error message for undefined solid `geometry` created: 2022-03-01 23:45:31 merged: 2022-03-02 17:06:58

44. [37111](http://github.com/cms-sw/cmssw/pull/37111){:target="_blank"}  from **@trackreco**: [MkFit] round up size arguments to aligned_alloc upwards to align value. `reconstruction` created: 2022-03-01 19:34:32 merged: 2022-03-02 12:23:28

45. [37110](http://github.com/cms-sw/cmssw/pull/37110){:target="_blank"}  from **@JanFSchulte**: fix L1 candidate matching in HLTMuonL1TFilter `hlt` created: 2022-03-01 18:37:34 merged: 2022-03-02 20:36:38

46. [37109](http://github.com/cms-sw/cmssw/pull/37109){:target="_blank"}  from **@smuzaffar**: [ALCA] Update all the scripts to use python3 `alca` created: 2022-03-01 18:32:34 merged: 2022-03-02 01:30:07

47. [37108](http://github.com/cms-sw/cmssw/pull/37108){:target="_blank"}  from **@smuzaffar**: [ANALYSIS] Update all the scripts to use python3 `analysis` created: 2022-03-01 18:32:15 merged: 2022-03-02 12:16:52

48. [37107](http://github.com/cms-sw/cmssw/pull/37107){:target="_blank"}  from **@smuzaffar**: [CORE] Update all the scripts to use python3 `core` created: 2022-03-01 18:32:09 merged: 2022-03-02 07:33:02

49. [37106](http://github.com/cms-sw/cmssw/pull/37106){:target="_blank"}  from **@smuzaffar**: [DB] Update all the scripts to use python3 `db` created: 2022-03-01 18:32:01 merged: 2022-03-02 01:30:41

50. [37105](http://github.com/cms-sw/cmssw/pull/37105){:target="_blank"}  from **@smuzaffar**: [GENERATORS] Update all the scripts to use python3 `generators` created: 2022-03-01 18:31:35 merged: 2022-03-04 14:28:09

51. [37104](http://github.com/cms-sw/cmssw/pull/37104){:target="_blank"}  from **@smuzaffar**: [HETEROGENEOUS] Update all the scripts to use python3 `heterogeneous` created: 2022-03-01 18:31:24 merged: 2022-03-02 00:30:13

52. [37103](http://github.com/cms-sw/cmssw/pull/37103){:target="_blank"}  from **@smuzaffar**: [PDMV-UPGRADE] Update all the scripts to use python3 `pdmv` `upgrade` created: 2022-03-01 18:31:12 merged: 2022-03-02 14:53:04

53. [37102](http://github.com/cms-sw/cmssw/pull/37102){:target="_blank"}  from **@tvami**: Add saturated EGM regression tags to Run-3 MC GTs `alca` created: 2022-03-01 18:07:56 merged: 2022-03-03 14:19:55

54. [37101](http://github.com/cms-sw/cmssw/pull/37101){:target="_blank"}  from **@francescobrivio**: [123X] Migrate DQM clients to Run3 era `dqm` created: 2022-03-01 15:42:18 merged: 2022-03-07 16:31:16

55. [37100](http://github.com/cms-sw/cmssw/pull/37100){:target="_blank"}  from **@swagata87**: Adapt to new range for BDT output for Run3 Saturated regression `operations` `reconstruction` created: 2022-03-01 14:29:27 merged: 2022-03-03 14:19:50

56. [37098](http://github.com/cms-sw/cmssw/pull/37098){:target="_blank"}  from **@ggovi**: LHCInfo workflow for Run3: Implemented PPS feedback `alca` `db` created: 2022-03-01 13:08:04 merged: 2022-03-02 00:44:36

57. [37095](http://github.com/cms-sw/cmssw/pull/37095){:target="_blank"}  from **@cvuosalo**: Fix AllStepsToTree option to runP_Tracker.py script `dqm` `geometry` created: 2022-02-28 23:40:48 merged: 2022-03-02 00:35:58

58. [37094](http://github.com/cms-sw/cmssw/pull/37094){:target="_blank"}  from **@smuzaffar**: When open fails with XrdCl::errRedirectLimit, delay next active source check. `core` created: 2022-02-28 21:50:14 merged: 2022-03-07 16:35:29

59. [37093](http://github.com/cms-sw/cmssw/pull/37093){:target="_blank"}  from **@cms-sw**: Revert "Revert "Add D88 DD4hep wf to relval_2026"" `pdmv` `upgrade` created: 2022-02-28 21:37:10 merged: 2022-03-05 16:50:06

60. [37092](http://github.com/cms-sw/cmssw/pull/37092){:target="_blank"}  from **@cms-sw**: Revert "Add D88 DD4hep wf to relval_2026" `pdmv` `upgrade` created: 2022-02-28 21:25:27 merged: 2022-02-28 21:34:06

61. [37091](http://github.com/cms-sw/cmssw/pull/37091){:target="_blank"}  from **@cms-tau-pog**: Removal of depreciated tauIDs `dqm` `reconstruction` `xpog` created: 2022-02-28 20:50:57 merged: 2022-03-08 12:51:47

62. [37090](http://github.com/cms-sw/cmssw/pull/37090){:target="_blank"}  from **@mmasciov**: Update selection for HLT tracking validation `dqm` created: 2022-02-28 18:13:23 merged: 2022-03-02 00:41:59

63. [37089](http://github.com/cms-sw/cmssw/pull/37089){:target="_blank"}  from **@tvami**: Add new L1T menu for Run-3 MC GTs `alca` created: 2022-02-28 17:28:54 merged: 2022-03-01 09:34:49

64. [37088](http://github.com/cms-sw/cmssw/pull/37088){:target="_blank"}  from **@slava77**: properly treat averaging with self in GhostTrackVertexFinder::vtxMean `reconstruction` created: 2022-02-28 15:28:47 merged: 2022-03-04 13:01:35

65. [37085](http://github.com/cms-sw/cmssw/pull/37085){:target="_blank"}  from **@mmusich**: Fix `BeamSpotAnalyzer::fillDescriptions` `alca` `reconstruction` created: 2022-02-28 09:43:43 merged: 2022-03-01 13:37:37

66. [37084](http://github.com/cms-sw/cmssw/pull/37084){:target="_blank"}  from **@mmusich**: migration to `DCSRecord` of `GenericTriggerEventFlag` `dqm` `hlt` `l1` created: 2022-02-28 08:25:17 merged: 2022-03-03 00:57:49

67. [37083](http://github.com/cms-sw/cmssw/pull/37083){:target="_blank"}  from **@mmusich**: introduce `GenericTriggerEventFlag::fillPSetDescription` and use it in several clients `dqm` `hlt` `l1` created: 2022-02-28 08:25:09 merged: 2022-03-02 00:38:48

68. [37082](http://github.com/cms-sw/cmssw/pull/37082){:target="_blank"}  from **@zhokin2**: HCAL: update(psm) of DPGAnalysis/HcalTools  for Run3  `dqm` created: 2022-02-28 07:58:18 merged: 2022-03-07 17:22:29

69. [37080](http://github.com/cms-sw/cmssw/pull/37080){:target="_blank"}  from **@bsunanda**: Run3-alca221 Cleanup the class in Calibration/HcalConnectivity `alca` created: 2022-02-27 17:45:58 merged: 2022-02-28 21:15:43

70. [37079](http://github.com/cms-sw/cmssw/pull/37079){:target="_blank"}  from **@srimanob**: Add D88 DD4hep wf to relval_2026 `pdmv` `upgrade` created: 2022-02-27 11:59:24 merged: 2022-02-28 21:19:19

71. [37078](http://github.com/cms-sw/cmssw/pull/37078){:target="_blank"}  from **@srimanob**: Fix dtSpecsFilter XML used by Phase-2 wf for DD4hep `geometry` `upgrade` created: 2022-02-27 09:45:55 merged: 2022-03-02 17:28:19

72. [37077](http://github.com/cms-sw/cmssw/pull/37077){:target="_blank"}  from **@bsunanda**: Run3-alca220 Cleanup some of the classes in Calibration/HcalIsolatedTrackReco `alca` created: 2022-02-26 20:42:37 merged: 2022-02-27 15:30:51

73. [37072](http://github.com/cms-sw/cmssw/pull/37072){:target="_blank"}  from **@smuzaffar**: added unit test for das-selected-lumis.py `pdmv` `upgrade` created: 2022-02-25 21:50:49 merged: 2022-02-27 20:44:05

74. [37070](http://github.com/cms-sw/cmssw/pull/37070){:target="_blank"}  from **@bsunanda**: Run3-alca219 Cleanup some of the classes in Calibration/HcalCalibAlgos `alca` created: 2022-02-25 14:08:10 merged: 2022-02-26 01:51:23

75. [37069](http://github.com/cms-sw/cmssw/pull/37069){:target="_blank"}  from **@mmusich**: get rid of `CMSDEPRECATED_X` warnings in `SimTracker` `simulation` `upgrade` created: 2022-02-25 12:45:08 merged: 2022-02-27 20:48:36

76. [37068](http://github.com/cms-sw/cmssw/pull/37068){:target="_blank"}  from **@missirol**: add `mantissaPrecision` parameter to `HLTScoutingPrimaryVertexProducer` `hlt` created: 2022-02-25 10:52:35 merged: 2022-02-27 04:41:51

77. [37066](http://github.com/cms-sw/cmssw/pull/37066){:target="_blank"}  from **@mmusich**: introduce `SiStripApvGainFromFileBuilder` (reprise) `db` created: 2022-02-25 07:28:14 merged: 2022-03-01 21:09:50

78. [37064](http://github.com/cms-sw/cmssw/pull/37064){:target="_blank"}  from **@makortel**: Small simplification in ensureAvailableAccelerators() `core` created: 2022-02-24 22:34:18 merged: 2022-02-25 15:07:48

79. [37063](http://github.com/cms-sw/cmssw/pull/37063){:target="_blank"}  from **@makortel**: Load Accelerators_cff unconditionally in customizeHLTforPatatrack.py, and clean up GPU/CPU forcing functions `hlt` created: 2022-02-24 22:22:39 merged: 2022-02-27 04:40:55

80. [37062](http://github.com/cms-sw/cmssw/pull/37062){:target="_blank"}  from **@makortel**: Add 'CUDAService' category also when CUDA is disabled, but only if it does not exist yet `heterogeneous` created: 2022-02-24 22:18:50 merged: 2022-02-25 13:08:45

81. [37061](http://github.com/cms-sw/cmssw/pull/37061){:target="_blank"}  from **@makortel**: Fix mkedlpr and mkesprod scripts for python3 `core` created: 2022-02-24 20:56:05 merged: 2022-02-25 04:40:57

82. [37060](http://github.com/cms-sw/cmssw/pull/37060){:target="_blank"}  from **@robervalwalsh**: Fixes for SiStripCalCosmicsNano `operations` `pdmv` `upgrade` created: 2022-02-24 20:40:08 merged: 2022-03-04 13:54:47

83. [37059](http://github.com/cms-sw/cmssw/pull/37059){:target="_blank"}  from **@tvami**: Remove unused CASTOR tags and change Castor DQM to Run-3 era `alca` `dqm` created: 2022-02-24 20:16:43 merged: 2022-02-28 14:36:58

84. [37058](http://github.com/cms-sw/cmssw/pull/37058){:target="_blank"}  from **@abdoulline**: HCAL HcalTBSource: adding skipEvents parameter `alca` created: 2022-02-24 17:29:56 merged: 2022-02-25 04:41:42

85. [37057](http://github.com/cms-sw/cmssw/pull/37057){:target="_blank"}  from **@missirol**: modernise and template HLT plugin for matching of two Jet collections `hlt` created: 2022-02-24 15:44:38 merged: 2022-02-27 04:46:07

86. [37056](http://github.com/cms-sw/cmssw/pull/37056){:target="_blank"}  from **@fabiocos**: MTD validation: update cluster histograms `dqm` created: 2022-02-24 14:00:00 merged: 2022-02-27 06:14:30

87. [37054](http://github.com/cms-sw/cmssw/pull/37054){:target="_blank"}  from **@smorovic**: DAQ - fixing streamer count of HLT paths with the GlobalEvFOutputModule (12_3_X) `core` `daq` created: 2022-02-24 09:56:45 merged: 2022-02-25 00:34:51

88. [37053](http://github.com/cms-sw/cmssw/pull/37053){:target="_blank"}  from **@wouf**: memory leak fixes for Hydjets `generators` created: 2022-02-24 09:42:36 merged: 2022-03-01 00:39:48

89. [37051](http://github.com/cms-sw/cmssw/pull/37051){:target="_blank"}  from **@jmejiagu**: update patZpeak to python3. add Jpsi example `core` created: 2022-02-23 16:43:59 merged: 2022-02-24 02:46:01

90. [37050](http://github.com/cms-sw/cmssw/pull/37050){:target="_blank"}  from **@CTPPS**: Updated the PPS PCL workers to support the new AlCaRecoProducer `alca` created: 2022-02-23 16:22:49 merged: 2022-02-24 13:28:01

91. [37048](http://github.com/cms-sw/cmssw/pull/37048){:target="_blank"}  from **@CTPPS**: PPSAlCaRecoProducer - minor fixes requested in #36273 `alca` created: 2022-02-23 14:26:14 merged: 2022-02-23 20:18:21

92. [37047](http://github.com/cms-sw/cmssw/pull/37047){:target="_blank"}  from **@bsunanda**: Phase2-gem67 Small cleanup of a test analyzer in Geometry/GEMGeometry `geometry` `upgrade` created: 2022-02-23 14:19:25 merged: 2022-02-26 01:52:43

93. [37046](http://github.com/cms-sw/cmssw/pull/37046){:target="_blank"}  from **@lathomas**: Update to L1 prescale code following move to fractional prescales `hlt` `l1` created: 2022-02-23 13:32:21 merged: 2022-02-25 00:47:15

94. [37045](http://github.com/cms-sw/cmssw/pull/37045){:target="_blank"}  from **@mmusich**: migrate away from deprecated APIs in the DQM subsystem `dqm` created: 2022-02-23 12:56:12 merged: 2022-02-25 00:37:20

95. [37044](http://github.com/cms-sw/cmssw/pull/37044){:target="_blank"}  from **@mmusich**: migrate `RawDataConverter` away from deprecated `EDAnalyzer` API `alca` created: 2022-02-23 08:47:56 merged: 2022-02-23 20:35:38

96. [37042](http://github.com/cms-sw/cmssw/pull/37042){:target="_blank"}  from **@elfontan**: Fix of the L1MenuWriter needed for the X2O procedure + update of the L1UpgradeTfMuonShowerTreeProducer `l1` created: 2022-02-22 23:26:39 merged: 2022-02-25 00:49:27

97. [37041](http://github.com/cms-sw/cmssw/pull/37041){:target="_blank"}  from **@kpedro88**: Sonic interface simplifications `reconstruction` `heterogeneous` created: 2022-02-22 22:51:05 merged: 2022-02-24 13:31:46

98. [37039](http://github.com/cms-sw/cmssw/pull/37039){:target="_blank"}  from **@missirol**: create `cfi` files for `JetConstituentSelector<>` plugins `hlt` `reconstruction` created: 2022-02-22 22:07:02 merged: 2022-02-25 15:10:19

99. [37038](http://github.com/cms-sw/cmssw/pull/37038){:target="_blank"}  from **@osschar**: [MkFit] Fix uninitialized MkFinder::m_prop_config in backward-fit. `reconstruction` created: 2022-02-22 21:37:33 merged: 2022-02-23 17:04:06

100. [37037](http://github.com/cms-sw/cmssw/pull/37037){:target="_blank"}  from **@cvuosalo**: Add energy units to CMSUnits.h `reconstruction` created: 2022-02-22 21:33:37 merged: 2022-02-27 15:26:31

101. [37036](http://github.com/cms-sw/cmssw/pull/37036){:target="_blank"}  from **@kpedro88**: Miscellaneous fixes and improvements for SonicTriton `heterogeneous` created: 2022-02-22 20:08:24 merged: 2022-02-24 13:33:26

102. [37035](http://github.com/cms-sw/cmssw/pull/37035){:target="_blank"}  from **@CMSTrackerDPG**: Avoid storing empty DetSet containers in the pixel digi collection `reconstruction` created: 2022-02-22 19:50:19 merged: 2022-03-02 13:02:16

103. [37034](http://github.com/cms-sw/cmssw/pull/37034){:target="_blank"}  from **@malbouis**: Include PPS timing-hptdc tag, HCal trigger primitive tag and update HI GT `alca` `reconstruction` created: 2022-02-22 18:20:53 merged: 2022-02-25 13:05:44

104. [37033](http://github.com/cms-sw/cmssw/pull/37033){:target="_blank"}  from **@tvami**: Change DQM modules to use stage-2 L1T `dqm` created: 2022-02-22 16:42:19 merged: 2022-02-24 18:13:50

105. [37032](http://github.com/cms-sw/cmssw/pull/37032){:target="_blank"}  from **@smuzaffar**: Add missing init in default constructor `reconstruction` created: 2022-02-22 16:41:42 merged: 2022-03-02 00:34:06

106. [37031](http://github.com/cms-sw/cmssw/pull/37031){:target="_blank"}  from **@cms-tsg-storm**: Update of L1T menu in TSG GTs `hlt` created: 2022-02-22 14:29:29 merged: 2022-02-22 19:57:13

107. [37028](http://github.com/cms-sw/cmssw/pull/37028){:target="_blank"}  from **@emiglior**: add process modifier to enable x-talk in Phase-2 InnerTracker pixels `operations` `simulation` `upgrade` created: 2022-02-22 13:00:35 merged: 2022-02-27 15:46:45

108. [37023](http://github.com/cms-sw/cmssw/pull/37023){:target="_blank"}  from **@mmusich**: use auto-generated configuration fragments in a few `RecoTracker` classes `reconstruction` created: 2022-02-22 09:59:42 merged: 2022-02-23 13:40:51

109. [37022](http://github.com/cms-sw/cmssw/pull/37022){:target="_blank"}  from **@missirol**: fixing removal of modules from `FinalPath` `core` created: 2022-02-22 08:57:03 merged: 2022-02-24 01:39:23

110. [37015](http://github.com/cms-sw/cmssw/pull/37015){:target="_blank"}  from **@bsunanda**: Run3-sim109E Clean analyzers in SimG4CMS/EcalTestBeam/plugins `simulation` created: 2022-02-21 17:23:51 merged: 2022-02-27 06:20:20

111. [37014](http://github.com/cms-sw/cmssw/pull/37014){:target="_blank"}  from **@trackreco**: patch-around immintrin.h for non-x86 case in MkFit `reconstruction` created: 2022-02-21 16:01:55 merged: 2022-02-22 12:58:43

112. [37011](http://github.com/cms-sw/cmssw/pull/37011){:target="_blank"}  from **@tlampen**: Fix printed text in Payload Inspector plots for DropBoxMetaData `db` created: 2022-02-21 14:04:29 merged: 2022-02-22 19:52:58

113. [37008](http://github.com/cms-sw/cmssw/pull/37008){:target="_blank"}  from **@iarspider**: MillePedeAlignmentAlgorithm: update for new GBL version `alca` created: 2022-02-21 13:37:59 merged: 2022-02-23 00:40:05

114. [37007](http://github.com/cms-sw/cmssw/pull/37007){:target="_blank"}  from **@bsunanda**: Run3-sim109D Clean analyzers in SimG4CMS/Muon and SimG4CMS/Tracker `simulation` created: 2022-02-21 13:37:22 merged: 2022-02-24 01:41:00

115. [37006](http://github.com/cms-sw/cmssw/pull/37006){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_3_X` `hlt` created: 2022-02-21 11:49:08 merged: 2022-02-22 10:51:10

116. [37005](http://github.com/cms-sw/cmssw/pull/37005){:target="_blank"}  from **@srimanob**: Update L1TrackTrigger step to DD4hep `l1` `upgrade` created: 2022-02-21 07:12:43 merged: 2022-03-03 14:03:33

117. [37003](http://github.com/cms-sw/cmssw/pull/37003){:target="_blank"}  from **@bsunanda**: Run3-sim109C Clean the analyzers in SimG4CMS/CherenkovAnalysis/plugins `simulation` created: 2022-02-20 14:59:43 merged: 2022-02-22 10:49:06

118. [37002](http://github.com/cms-sw/cmssw/pull/37002){:target="_blank"}  from **@bsunanda**: Run3-TB68 Clean up the analyzers of HCAL TB applications in SimG4CMS/HcalTestBeam/plugins `simulation` created: 2022-02-19 14:34:07 merged: 2022-02-22 10:46:01

119. [37001](http://github.com/cms-sw/cmssw/pull/37001){:target="_blank"}  from **@bsunanda**: Phase2-TB67 Clean up the analyzers of HGCal TB applications in SimG4CMS/HGCalTestBeam/plugins `simulation` `upgrade` created: 2022-02-19 00:53:07 merged: 2022-02-28 00:35:55

120. [36999](http://github.com/cms-sw/cmssw/pull/36999){:target="_blank"}  from **@cms-tsg-storm**: HLT menu migration to CMSSW_12_3_0_pre5 template `hlt` created: 2022-02-18 14:44:29 merged: 2022-02-19 13:11:26

121. [36998](http://github.com/cms-sw/cmssw/pull/36998){:target="_blank"}  from **@lwang046**: HcalDQM: GPU MonitoringTask `dqm` `operations` `heterogeneous` created: 2022-02-18 09:46:07 merged: 2022-02-28 16:06:46

122. [36997](http://github.com/cms-sw/cmssw/pull/36997){:target="_blank"}  from **@slomeo**: Fixed all the overlaps inside the Muon Yoke (2021/v6/muonYoke.xml) `geometry` created: 2022-02-18 08:02:44 merged: 2022-02-23 13:35:00

123. [36995](http://github.com/cms-sw/cmssw/pull/36995){:target="_blank"}  from **@bsunanda**: Run3-sim109B Cleanup the remaining parts of SimG4CMS/Calo/plugins code `simulation` created: 2022-02-17 20:22:11 merged: 2022-02-19 13:10:15

124. [36994](http://github.com/cms-sw/cmssw/pull/36994){:target="_blank"}  from **@SanghyunKo**: Add GEN/LHE weight validation subdirectories for GEN Relval `dqm` `generators` created: 2022-02-17 17:03:30 merged: 2022-03-07 20:25:39

125. [36992](http://github.com/cms-sw/cmssw/pull/36992){:target="_blank"}  from **@yuanchao**: remove unused legacy headers in RPC `alca` `db` created: 2022-02-17 14:19:25 merged: 2022-02-17 18:56:14

126. [36990](http://github.com/cms-sw/cmssw/pull/36990){:target="_blank"}  from **@arsahasransu**: Add the detector ids to the scouting electron and photon collection for Run 3 `core` `hlt` created: 2022-02-17 13:12:47 merged: 2022-02-21 14:54:02

127. [36989](http://github.com/cms-sw/cmssw/pull/36989){:target="_blank"}  from **@jeongeun**: Clean up redundant edm ParameterSet existAs or exist in RecoTracker/{TkSeedGenerator} `reconstruction` created: 2022-02-17 12:21:27 merged: 2022-02-22 10:11:03

128. [36987](http://github.com/cms-sw/cmssw/pull/36987){:target="_blank"}  from **@bsunanda**: Run3-alca218D Clean some of the remaining Hcal calibration codes in Calibration/HcalCalibAlgos `alca` created: 2022-02-16 19:36:50 merged: 2022-02-17 20:35:06

129. [36986](http://github.com/cms-sw/cmssw/pull/36986){:target="_blank"}  from **@missirol**: update of HLT-E/Gamma modules to avoid accessing `L1CaloGeometry` unnecessarily `hlt` created: 2022-02-16 17:29:49 merged: 2022-02-17 21:17:06

130. [36985](http://github.com/cms-sw/cmssw/pull/36985){:target="_blank"}  from **@perrotta**: A few possible bug fixes in the L1T code `l1` created: 2022-02-16 17:10:01 merged: 2022-03-08 00:42:23

131. [36984](http://github.com/cms-sw/cmssw/pull/36984){:target="_blank"}  from **@bsunanda**: Run3-sim109A Cleanup some of the SimG4CMS/Calo code `simulation` created: 2022-02-16 17:08:58 merged: 2022-02-17 15:57:45

132. [36983](http://github.com/cms-sw/cmssw/pull/36983){:target="_blank"}  from **@mmusich**: Remove Phase-0 SiStrip records dependency from Phase-2 workflows `alca` `daq` `operations` `reconstruction` `simulation` created: 2022-02-16 15:01:14 merged: 2022-02-19 13:56:30

133. [36981](http://github.com/cms-sw/cmssw/pull/36981){:target="_blank"}  from **@missirol**: small improvements to `HLTSumJetTag` `hlt` created: 2022-02-16 14:29:47 merged: 2022-02-17 20:41:29

134. [36980](http://github.com/cms-sw/cmssw/pull/36980){:target="_blank"}  from **@mmusich**: remove more `CMSDEPRECATED_X` warnings from `RecoTracker` `reconstruction` created: 2022-02-16 14:27:04 merged: 2022-02-23 08:58:51

135. [36979](http://github.com/cms-sw/cmssw/pull/36979){:target="_blank"}  from **@bsunanda**: Run3-alca218C Clean some of the HCAL calibration code in Calibration/HcalCalibAlgos/plugins `alca` created: 2022-02-15 22:05:25 merged: 2022-02-17 21:23:24

136. [36970](http://github.com/cms-sw/cmssw/pull/36970){:target="_blank"}  from **@fabiocos**: MTD geometry: update tests to scenario D88, update DDFilteredView::parameters() accordingly `geometry` `reconstruction` `upgrade` created: 2022-02-15 11:43:42 merged: 2022-02-18 17:01:16

137. [36968](http://github.com/cms-sw/cmssw/pull/36968){:target="_blank"}  from **@mmusich**: SiPixelClusterizer: No digis to clusterize warning into error `reconstruction` created: 2022-02-15 08:37:14 merged: 2022-03-02 17:09:50

138. [36961](http://github.com/cms-sw/cmssw/pull/36961){:target="_blank"}  from **@mandrenguyen**: Add HiGenEvent object to heavy-ion miniAOD event content `reconstruction` `xpog` created: 2022-02-14 15:50:54 merged: 2022-03-04 00:59:49

139. [36956](http://github.com/cms-sw/cmssw/pull/36956){:target="_blank"}  from **@ggovi**: Changing LHCInfo O2O Implementation to access source data from OMS `alca` `db` created: 2022-02-14 13:07:52 merged: 2022-02-18 16:12:44

140. [36954](http://github.com/cms-sw/cmssw/pull/36954){:target="_blank"}  from **@rgoldouz**: Electron and photon masses are set to zero `reconstruction` created: 2022-02-14 11:00:06 merged: 2022-03-08 00:38:22

141. [36952](http://github.com/cms-sw/cmssw/pull/36952){:target="_blank"}  from **@benitezj**: AlCaLumiPixelsCountsExpress and AlCaLumiPixelsCountsPrompt  PCL and PromptReco  `alca` `pdmv` `upgrade` created: 2022-02-14 01:11:31 merged: 2022-03-02 15:14:51

142. [36921](http://github.com/cms-sw/cmssw/pull/36921){:target="_blank"}  from **@bsunanda**: Phase2-hgx299 Add the dd4hep version of the algorithm to make rotated full wafers as in #36898 `geometry` `upgrade` created: 2022-02-09 21:26:03 merged: 2022-02-17 15:52:51

143. [36919](http://github.com/cms-sw/cmssw/pull/36919){:target="_blank"}  from **@gk199**: L1 emulator for LLP displaced jet trigger (L1 6:1 LUT, L2 jet algo), L1TNtuples addition of jet hwQual `l1` created: 2022-02-09 15:31:43 merged: 2022-02-17 15:58:25

144. [36901](http://github.com/cms-sw/cmssw/pull/36901){:target="_blank"}  from **@jainshilpi**: Implementation of beam halo tagger algorithm for the endcap photons `reconstruction` created: 2022-02-07 00:38:09 merged: 2022-03-03 14:44:27

145. [36890](http://github.com/cms-sw/cmssw/pull/36890){:target="_blank"}  from **@nurfikri89**: [MiniAOD] Lower AK4 Puppi jets pT cut for Run 3 `reconstruction` `xpog` created: 2022-02-04 18:50:45 merged: 2022-03-08 11:23:14

146. [36850](http://github.com/cms-sw/cmssw/pull/36850){:target="_blank"}  from **@kirschen**: fix bug in NANOAOD Pileup_nTrueInt variable (int instead of float) `xpog` created: 2022-02-01 13:46:03 merged: 2022-02-18 09:51:20

147. [36846](http://github.com/cms-sw/cmssw/pull/36846){:target="_blank"}  from **@carriganm95**: Skim for EXO Disappearing Tracks `pdmv` created: 2022-01-31 20:58:35 merged: 2022-02-25 17:31:11

148. [36793](http://github.com/cms-sw/cmssw/pull/36793){:target="_blank"}  from **@fabiocos**: MTD reconstruction: speed up TrackExtenderWithMTD `operations` `reconstruction` `upgrade` created: 2022-01-25 09:38:39 merged: 2022-02-21 08:20:15

149. [36742](http://github.com/cms-sw/cmssw/pull/36742){:target="_blank"}  from **@alejands**: Create new ECAL DQM GpuTask to monitor and compare CPU and GPU generated ECAL RECO objects `dqm` `operations` created: 2022-01-18 21:01:23 merged: 2022-02-22 10:11:46

150. [36699](http://github.com/cms-sw/cmssw/pull/36699){:target="_blank"}  from **@makortel**: Add a generic mechanism to specify compute accelerators to use in the configuration `core` `dqm` `hlt` `operations` `reconstruction` `upgrade` `heterogeneous` created: 2022-01-12 21:36:30 merged: 2022-02-23 13:56:35

151. [36546](http://github.com/cms-sw/cmssw/pull/36546){:target="_blank"}  from **@trackreco**: mkFit external integration `reconstruction` created: 2021-12-17 22:48:08 merged: 2022-02-21 00:50:56

152. [36526](http://github.com/cms-sw/cmssw/pull/36526){:target="_blank"}  from **@maxgalli**: Hgg photons variables in nanoAODs `xpog` created: 2021-12-16 17:24:30 merged: 2022-03-08 01:13:03

153. [36337](http://github.com/cms-sw/cmssw/pull/36337){:target="_blank"}  from **@hgc-tpg**: [HGCAL trigger] Migration to new code structure - First pass `l1` `upgrade` created: 2021-12-02 14:43:05 merged: 2022-02-17 19:18:00

154. [36080](http://github.com/cms-sw/cmssw/pull/36080){:target="_blank"}  from **@forthommel**: [PPS][NanoAOD] Generator-level proton information `xpog` created: 2021-11-10 19:10:25 merged: 2022-02-17 21:07:42

#### CMSDIST Changes between Tags REL/CMSSW_12_3_0_pre5/slc7_amd64_gcc10 and REL/CMSSW_12_3_0_pre6/slc7_amd64_gcc10:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_3_0_pre5/slc7_amd64_gcc10...REL/CMSSW_12_3_0_pre6/slc7_amd64_gcc10)



1. [7680](http://github.com/cms-sw/cmsdist/pull/7680){:target="_blank"}  from **@cms-sw**: [CS9] Update py3-debugpy to version 1.5.1 created: 2022-03-10 10:04:35 merged: 2022-03-10 14:57:10

2. [7668](http://github.com/cms-sw/cmsdist/pull/7668){:target="_blank"}  from **@cms-sw**: Update sigcpp to 3.2.0 created: 2022-03-04 16:16:01 merged: 2022-03-07 21:28:19

3. [7667](http://github.com/cms-sw/cmsdist/pull/7667){:target="_blank"}  from **@cms-sw**: [SCRAM] Allow to prefix user defined PATH, LD_LIBRARY_PATH created: 2022-03-04 16:04:15 merged: 2022-03-04 19:01:44

4. [7666](http://github.com/cms-sw/cmsdist/pull/7666){:target="_blank"}  from **@cms-sw**: Update tag for CondTools-SiStrip to V00-02-00 created: 2022-03-04 00:57:24 merged: 2022-03-04 00:58:02

5. [7665](http://github.com/cms-sw/cmsdist/pull/7665){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-PhotonIdentification to V01-04-00 created: 2022-03-04 00:39:39 merged: 2022-03-04 00:40:25

6. [7663](http://github.com/cms-sw/cmsdist/pull/7663){:target="_blank"}  from **@cms-sw**: Update pacparser to 1.3.7 created: 2022-03-03 16:35:44 merged: 2022-03-07 21:27:38

7. [7660](http://github.com/cms-sw/cmsdist/pull/7660){:target="_blank"}  from **@cms-sw**: Update Millepede to V04-11-01 and switch to git created: 2022-03-02 14:40:40 merged: 2022-03-05 09:43:20

8. [7659](http://github.com/cms-sw/cmsdist/pull/7659){:target="_blank"}  from **@cms-sw**: typo fixed for fakesystem created: 2022-03-02 07:14:28 merged: 2022-03-02 07:14:40

9. [7658](http://github.com/cms-sw/cmsdist/pull/7658){:target="_blank"}  from **@cms-sw**: added github perl deps in fakesystem created: 2022-03-02 07:06:15 merged: 2022-03-02 07:06:31

10. [7657](http://github.com/cms-sw/cmsdist/pull/7657){:target="_blank"}  from **@cms-sw**: Update tag for CondTools-SiStrip to V00-01-00 created: 2022-03-01 21:17:59 merged: 2022-03-01 21:18:32

11. [7656](http://github.com/cms-sw/cmsdist/pull/7656){:target="_blank"}  from **@cms-sw**: perl package clean from bootstrap; drop python2 deps created: 2022-03-01 19:05:24 merged: 2022-03-02 06:28:26

12. [7655](http://github.com/cms-sw/cmsdist/pull/7655){:target="_blank"}  from **@mkirsano**: Addhepmc3 created: 2022-03-01 16:24:47 merged: 2022-03-02 20:55:08

13. [7653](http://github.com/cms-sw/cmsdist/pull/7653){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2022-03-01 12:53:55 merged: 2022-03-01 18:57:34

14. [7652](http://github.com/cms-sw/cmsdist/pull/7652){:target="_blank"}  from **@cms-sw**: XRootD: Update to version 5.4.1 and build with scitokens-cpp created: 2022-02-26 14:59:57 merged: 2022-02-27 20:31:21

15. [7650](http://github.com/cms-sw/cmsdist/pull/7650){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2022-02-25 19:28:25 merged: 2022-02-26 09:50:00

16. [7649](http://github.com/cms-sw/cmsdist/pull/7649){:target="_blank"}  from **@fwyzard**: Update Eigen with a fix for AMD GPUs created: 2022-02-24 22:30:47 merged: 2022-02-26 09:52:40

17. [7646](http://github.com/cms-sw/cmsdist/pull/7646){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2022-02-24 13:53:44 merged: 2022-02-24 19:24:58

18. [7645](http://github.com/cms-sw/cmsdist/pull/7645){:target="_blank"}  from **@cms-sw**: Update tag for Alignment-OfflineValidation to V00-02-00 created: 2022-02-23 20:42:55 merged: 2022-02-23 20:47:04

19. [7641](http://github.com/cms-sw/cmsdist/pull/7641){:target="_blank"}  from **@fwyzard**: Update to CUDA 11.4.4 created: 2022-02-22 13:58:17 merged: 2022-02-24 09:32:11

20. [7640](http://github.com/cms-sw/cmsdist/pull/7640){:target="_blank"}  from **@cms-sw**: Update glimpse to 4.18.7-6; fix source URL (the old one is dead) created: 2022-02-22 09:43:39 merged: 2022-02-22 14:47:03

21. [7638](http://github.com/cms-sw/cmsdist/pull/7638){:target="_blank"}  from **@cms-sw**: Update GBL (and move to git instead of svn) created: 2022-02-21 11:28:28 merged: 2022-02-23 00:39:38

22. [7635](http://github.com/cms-sw/cmsdist/pull/7635){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-09-00 created: 2022-02-18 17:01:12 merged: 2022-02-18 17:07:09

23. [7632](http://github.com/cms-sw/cmsdist/pull/7632){:target="_blank"}  from **@cms-sw**: [scipy] disable rpm find_provide and explicitly set the needed Provdies created: 2022-02-18 09:07:09 merged: 2022-02-18 17:51:43

24. [7631](http://github.com/cms-sw/cmsdist/pull/7631){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1THGCal to V01-07-00 created: 2022-02-17 19:19:00 merged: 2022-02-17 20:20:50

25. [7630](http://github.com/cms-sw/cmsdist/pull/7630){:target="_blank"}  from **@cms-sw**: [build rules] fix for edm class check rules created: 2022-02-16 15:15:41 merged: 2022-02-17 15:37:32

26. [7617](http://github.com/cms-sw/cmsdist/pull/7617){:target="_blank"}  from **@cms-sw**: [TF] Added build with GPU support but default is to build without GPU created: 2022-02-10 19:10:33 merged: 2022-02-23 07:11:12

27. [7528](http://github.com/cms-sw/cmsdist/pull/7528){:target="_blank"}  from **@slava77**: remove mkFit external created: 2021-12-23 04:09:30 merged: 2022-02-21 00:51:23
