---
layout: post
rel_link:  "13_3_0_pre1"
title:  "CMSSW_13_3_0_pre1"
date:   2023-08-03 20:26:41
categories: cmssw
relmajor: 13
relminor: 3
relsubminor: 0
relpre: _pre1
---

# CMSSW_13_3_0_pre1
#### Changes since CMSSW_13_2_0_pre3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_13_2_0_pre3...CMSSW_13_3_0_pre1)



1. [42449](http://github.com/cms-sw/cmssw/pull/42449){:target="_blank"}  from **@mmusich**: TrackerAlignment PI: Support pixel only comparisons `db` created: 2023-08-02 15:31:39 merged: 2023-08-02 20:06:47

2. [42440](http://github.com/cms-sw/cmssw/pull/42440){:target="_blank"}  from **@smuzaffar**: Use TCMalloc instead of JeMalloc for cmsRun `core` created: 2023-08-01 17:50:21 merged: 2023-08-02 16:14:29

3. [42438](http://github.com/cms-sw/cmssw/pull/42438){:target="_blank"}  from **@bsunanda**: Phase2-hgx342C Modify the tester to check correctly the  wafer ID from position for HGCal `geometry` `upgrade` created: 2023-08-01 14:37:32 merged: 2023-08-02 16:15:54

4. [42437](http://github.com/cms-sw/cmssw/pull/42437){:target="_blank"}  from **@caruta**: Removal of StringCutObjectSelector from Muon trigger DQM `dqm` created: 2023-08-01 12:33:39 merged: 2023-08-01 16:25:31

5. [42432](http://github.com/cms-sw/cmssw/pull/42432){:target="_blank"}  from **@fabiocos**: MTD validation: downgrade warning in BTL local reco validation `dqm` created: 2023-08-01 09:47:15 merged: 2023-08-03 06:44:05

6. [42429](http://github.com/cms-sw/cmssw/pull/42429){:target="_blank"}  from **@bsunanda**: Phase2-TB71 Add a new scenario to evaluate the August 2023 HGCal Test Beam `geometry` `upgrade` created: 2023-07-31 14:40:43 merged: 2023-08-02 07:02:41

7. [42428](http://github.com/cms-sw/cmssw/pull/42428){:target="_blank"}  from **@silviodonato**: sort by pt only good-quality tracks `reconstruction` `tracking` created: 2023-07-31 13:03:06 merged: 2023-08-02 16:23:37

8. [42425](http://github.com/cms-sw/cmssw/pull/42425){:target="_blank"}  from **@fwyzard**: Replace the SFINAE check with static_assert `heterogeneous` created: 2023-07-31 12:21:01 merged: 2023-08-01 05:13:14

9. [42420](http://github.com/cms-sw/cmssw/pull/42420){:target="_blank"}  from **@bsunanda**: Phase2-sim145 Study the difference in SD's between DDD and DD4hep for Phase2 scenarios `simulation` created: 2023-07-30 09:26:27 merged: 2023-08-01 07:52:38

10. [42419](http://github.com/cms-sw/cmssw/pull/42419){:target="_blank"}  from **@bsunanda**: Phase2-sim145X Modify some of the SIM codes to understand the difference between DDD and DD4hep for HGCal `simulation` created: 2023-07-30 01:59:16 merged: 2023-07-30 12:02:11

11. [42415](http://github.com/cms-sw/cmssw/pull/42415){:target="_blank"}  from **@missirol**: update `testTriggerEventAnalyzers` unit test (new input, more events) `hlt` created: 2023-07-29 06:12:28 merged: 2023-07-30 07:13:14

12. [42413](http://github.com/cms-sw/cmssw/pull/42413){:target="_blank"}  from **@sunilUIET**: Add WFs for 2023D `pdmv` `upgrade` created: 2023-07-29 05:54:45 merged: 2023-07-30 07:26:16

13. [42410](http://github.com/cms-sw/cmssw/pull/42410){:target="_blank"}  from **@missirol**: fix configuration of GPU Pixel unpacker in Run-3 HLT menus post-#41632 `hlt` `reconstruction` `trk` created: 2023-07-28 22:03:45 merged: 2023-07-31 16:37:56

14. [42405](http://github.com/cms-sw/cmssw/pull/42405){:target="_blank"}  from **@smuzaffar**: [DBG] Fix comparison of integer expressions of different signedness `reconstruction` `trk` created: 2023-07-28 08:54:11 merged: 2023-08-01 16:13:52

15. [42393](http://github.com/cms-sw/cmssw/pull/42393){:target="_blank"}  from **@perrotta**: fix SetEntries in MESet `dqm` created: 2023-07-27 15:41:03 merged: 2023-07-29 05:42:42

16. [42392](http://github.com/cms-sw/cmssw/pull/42392){:target="_blank"}  from **@iarspider**: [GCC13] Add include of cstdint in more places `alca` `reconstruction` `simulation` created: 2023-07-27 14:48:16 merged: 2023-07-31 17:22:06

17. [42391](http://github.com/cms-sw/cmssw/pull/42391){:target="_blank"}  from **@iarspider**: Fix maybe-uninitialized warnings in L1GTDeltaCut.h `l1` `upgrade` created: 2023-07-27 12:59:09 merged: 2023-07-28 10:53:49

18. [42378](http://github.com/cms-sw/cmssw/pull/42378){:target="_blank"}  from **@mmusich**: clear `badPixelDetsBarrel_` and `badPixelDetsEndcap_` in `PixelInactiveAreaFinder` `reconstruction` `tracking` created: 2023-07-26 14:18:54 merged: 2023-07-28 09:45:14

19. [42377](http://github.com/cms-sw/cmssw/pull/42377){:target="_blank"}  from **@iarspider**: Fix ambiguous comparision in HcalDcsMap `alca` `db` created: 2023-07-26 13:21:02 merged: 2023-07-27 05:40:11

20. [42376](http://github.com/cms-sw/cmssw/pull/42376){:target="_blank"}  from **@aloeliger**: Add initial null value for model result in calo summary `l1` created: 2023-07-26 12:41:46 merged: 2023-07-29 05:45:50

21. [42373](http://github.com/cms-sw/cmssw/pull/42373){:target="_blank"}  from **@perrotta**: Maybe remove build warning in TrackerMap, but at least clean it up `dqm` `reconstruction` `trk` created: 2023-07-25 20:48:34 merged: 2023-08-01 10:04:14

22. [42360](http://github.com/cms-sw/cmssw/pull/42360){:target="_blank"}  from **@CTPPS**: fixed comparePayloads in LHCInfo* PopCons `db` created: 2023-07-25 15:05:11 merged: 2023-07-28 12:24:01

23. [42359](http://github.com/cms-sw/cmssw/pull/42359){:target="_blank"}  from **@mmusich**: Update `PrimaryVertexMonitor` `dqm` created: 2023-07-25 15:02:23 merged: 2023-07-27 08:34:30

24. [42358](http://github.com/cms-sw/cmssw/pull/42358){:target="_blank"}  from **@saumyaphor4252**: Update 2023 MC GTs with the fixed L1T tag and re-snapshot the data GTs `alca` created: 2023-07-25 14:47:44 merged: 2023-07-30 07:18:14

25. [42357](http://github.com/cms-sw/cmssw/pull/42357){:target="_blank"}  from **@francescobrivio**: Improve discover method in cond2xml for read-only and patch releases `db` created: 2023-07-25 14:46:59 merged: 2023-07-26 17:14:04

26. [42354](http://github.com/cms-sw/cmssw/pull/42354){:target="_blank"}  from **@fabiocos**: MTD geometry: remove code for obsolete ETL ring-based scenario `dqm` `geometry` `reconstruction` `upgrade` created: 2023-07-25 12:55:19 merged: 2023-07-28 07:42:38

27. [42352](http://github.com/cms-sw/cmssw/pull/42352){:target="_blank"}  from **@theochatzis**: [HLT_Phase2] Removal of Preshower modules `hlt` created: 2023-07-25 09:39:46 merged: 2023-07-26 17:18:05

28. [42351](http://github.com/cms-sw/cmssw/pull/42351){:target="_blank"}  from @theochatzis: [JME**@Phase2HLT**] Removal of unnecessary modules `hlt` created: 2023-07-25 09:33:30 merged: 2023-07-26 17:21:09

29. [42350](http://github.com/cms-sw/cmssw/pull/42350){:target="_blank"}  from **@bsunanda**: Phase2-hgx342B Investigating the difference between DDD and DD4hep geometries for HGCal partial wafers `geometry` `simulation` `upgrade` created: 2023-07-25 09:05:49 merged: 2023-07-26 13:53:33

30. [42349](http://github.com/cms-sw/cmssw/pull/42349){:target="_blank"}  from **@iarspider**: DDAlgoArguments.cc: remove redundant move in return statement `geometry` created: 2023-07-25 08:36:41 merged: 2023-07-26 13:54:15

31. [42347](http://github.com/cms-sw/cmssw/pull/42347){:target="_blank"}  from **@NJManganelli**: Phase 2 GTT MET cos LUT update `l1` `upgrade` created: 2023-07-25 07:10:21 merged: 2023-07-27 16:53:57

32. [42346](http://github.com/cms-sw/cmssw/pull/42346){:target="_blank"}  from **@srimanob**: Add 2023 FastSim Era `operations` `pdmv` `upgrade` created: 2023-07-24 21:17:22 merged: 2023-07-27 12:48:55

33. [42341](http://github.com/cms-sw/cmssw/pull/42341){:target="_blank"}  from **@iarspider**: [CPP20] Add missing include `geometry` `upgrade` `trk` created: 2023-07-24 13:37:45 merged: 2023-07-25 17:18:38

34. [42336](http://github.com/cms-sw/cmssw/pull/42336){:target="_blank"}  from **@guitargeek**: Clean unused dependencies from BuildFiles `alca` `daq` `dqm` `operations` `reconstruction` `simulation` `db` `upgrade` `xpog` `hcal` `trk` created: 2023-07-23 12:29:02 merged: 2023-07-25 17:15:23

35. [42335](http://github.com/cms-sw/cmssw/pull/42335){:target="_blank"}  from **@smuzaffar**: [GCC13] Added missing cstdint include `reconstruction` `daq` `geometry` `simulation` `trk` created: 2023-07-22 15:03:20 merged: 2023-07-25 07:05:34

36. [42334](http://github.com/cms-sw/cmssw/pull/42334){:target="_blank"}  from **@Dr15Jones**: The cut parser is now const-thread-safe `analysis` `dqm` `reconstruction` `visualization` created: 2023-07-21 18:58:58 merged: 2023-07-27 13:01:00

37. [42333](http://github.com/cms-sw/cmssw/pull/42333){:target="_blank"}  from **@slava77**: tracking MTV: improve ability to select region in eta-phi for sim particles `dqm` `tracking` created: 2023-07-21 16:56:22 merged: 2023-07-23 19:35:29

38. [42328](http://github.com/cms-sw/cmssw/pull/42328){:target="_blank"}  from **@bsunanda**: Run3-sim145X Add a missing end of line in a printout statement in SimG4CMS/Calo `simulation` created: 2023-07-21 07:42:04 merged: 2023-07-21 16:51:36

39. [42327](http://github.com/cms-sw/cmssw/pull/42327){:target="_blank"}  from **@srimanob**: Update 2023 FastSim beamspot `pdmv` `upgrade` created: 2023-07-21 06:30:38 merged: 2023-07-25 07:02:27

40. [42326](http://github.com/cms-sw/cmssw/pull/42326){:target="_blank"}  from **@bsunanda**: Run3-sim145 Add a procedure to dump all touchables from a G4 geometry setup `simulation` created: 2023-07-21 05:23:23 merged: 2023-07-21 15:31:12

41. [42325](http://github.com/cms-sw/cmssw/pull/42325){:target="_blank"}  from **@NJManganelli**: Phase 2 GTT inversion LUT harmonization `l1` created: 2023-07-20 22:00:00 merged: 2023-07-25 13:30:48

42. [42324](http://github.com/cms-sw/cmssw/pull/42324){:target="_blank"}  from **@mmusich**: support `conddb` for patch releases in read-only mode `db` created: 2023-07-20 17:03:56 merged: 2023-07-25 07:09:33

43. [42320](http://github.com/cms-sw/cmssw/pull/42320){:target="_blank"}  from **@missirol**: add layer-TSOS compatibility check in `LayerMeasurements` `reconstruction` `tracking` created: 2023-07-20 11:49:55 merged: 2023-07-27 14:28:36

44. [42318](http://github.com/cms-sw/cmssw/pull/42318){:target="_blank"}  from **@missirol**: fix `ldir.z==0` edge case in `fastProp` method of `RecHitPropagator.h` `reconstruction` `tracking` created: 2023-07-20 11:45:58 merged: 2023-07-27 20:29:55

45. [42316](http://github.com/cms-sw/cmssw/pull/42316){:target="_blank"}  from **@yuanchao**: Clean up work around in JER Payload Inspector plugin `db` created: 2023-07-20 10:40:51 merged: 2023-07-21 14:00:27

46. [42315](http://github.com/cms-sw/cmssw/pull/42315){:target="_blank"}  from **@depasse**: ECAL : DB PayloadInspector correction `db` created: 2023-07-20 10:29:54 merged: 2023-07-21 14:00:50

47. [42314](http://github.com/cms-sw/cmssw/pull/42314){:target="_blank"}  from **@smuzaffar**: moved PixelThresholdClusterizer::clusterizeDetUnitT template function in separate header `reconstruction` `trk` created: 2023-07-20 09:42:17 merged: 2023-07-24 13:55:12

48. [42313](http://github.com/cms-sw/cmssw/pull/42313){:target="_blank"}  from **@iarspider**: TopRecoilHook: fix warning about empty if `generators` created: 2023-07-20 07:17:51 merged: 2023-07-27 09:13:34

49. [42312](http://github.com/cms-sw/cmssw/pull/42312){:target="_blank"}  from **@bsunanda**: Run3-sim144 Investigate the solids produced through ddd and dd4hep for HGCal versions D98 and D99 `simulation` created: 2023-07-20 01:16:38 merged: 2023-07-20 14:29:35

50. [42311](http://github.com/cms-sw/cmssw/pull/42311){:target="_blank"}  from **@wddgit**: Remove getManyByType from the Framework `core` created: 2023-07-19 16:58:30 merged: 2023-07-24 15:31:06

51. [42310](http://github.com/cms-sw/cmssw/pull/42310){:target="_blank"}  from **@wddgit**: Remove CaloTowersDump and STAnalyzer `reconstruction` created: 2023-07-19 15:25:35 merged: 2023-07-24 13:55:28

52. [42309](http://github.com/cms-sw/cmssw/pull/42309){:target="_blank"}  from **@nancymarinelli**: Split the dR plot for neutral hadrons in two eta ranges in the EB `dqm` `egamma` created: 2023-07-19 14:55:35 merged: 2023-07-21 14:01:02

53. [42308](http://github.com/cms-sw/cmssw/pull/42308){:target="_blank"}  from **@smuzaffar**: [GCC12] Split RiemannFitOnGPU.cu in multiple files to avoid build errors `reconstruction` `tracking` created: 2023-07-19 14:51:42 merged: 2023-07-25 07:13:05

54. [42304](http://github.com/cms-sw/cmssw/pull/42304){:target="_blank"}  from **@AdrianoDee**: Clean Up for Pixel Tracks - Follow-up to #41632 `dqm` `reconstruction` `pdmv` `upgrade` `tracking` `trk` created: 2023-07-19 14:27:31 merged: 2023-07-27 19:51:01

55. [42303](http://github.com/cms-sw/cmssw/pull/42303){:target="_blank"}  from **@fabferro**: PPS suppress LogErrors in Pixel unpacker `reconstruction` created: 2023-07-19 14:11:39 merged: 2023-07-26 13:57:38

56. [42302](http://github.com/cms-sw/cmssw/pull/42302){:target="_blank"}  from **@mmusich**: Support HLT tracks in alignment validation `alca` `reconstruction` `tracking` created: 2023-07-19 09:12:05 merged: 2023-07-24 13:56:12

57. [42301](http://github.com/cms-sw/cmssw/pull/42301){:target="_blank"}  from **@thomreis**: ECAL skip GPU unpacking of the rest of the block if a bad block is detected `reconstruction` `heterogeneous` `ecal` created: 2023-07-18 21:58:24 merged: 2023-07-27 20:34:50

58. [42300](http://github.com/cms-sw/cmssw/pull/42300){:target="_blank"}  from **@dan131riley**: declare the storage type of the L1GtObject to workaround a ROOT problem `l1` created: 2023-07-18 21:52:36 merged: 2023-07-20 14:27:49

59. [42295](http://github.com/cms-sw/cmssw/pull/42295){:target="_blank"}  from **@sunilUIET**: Fixing PU  for 2023 WFs with more reasonable profile `pdmv` `upgrade` created: 2023-07-18 12:12:51 merged: 2023-07-20 14:26:44

60. [42294](http://github.com/cms-sw/cmssw/pull/42294){:target="_blank"}  from **@RSalvatico**: Update electron IDs in OfflineDQM `dqm` `egamma` created: 2023-07-18 12:04:52 merged: 2023-07-19 13:30:08

61. [42293](http://github.com/cms-sw/cmssw/pull/42293){:target="_blank"}  from **@iarspider**: Make RecoLocalCalo/EcalRecProducers compile with C++20 `reconstruction` created: 2023-07-18 11:58:54 merged: 2023-07-24 13:56:37

62. [42290](http://github.com/cms-sw/cmssw/pull/42290){:target="_blank"}  from **@NJManganelli**: Phase 2 match GTTFileWriter cfi and source parameter name `l1` created: 2023-07-18 06:55:26 merged: 2023-07-20 14:26:21

63. [42288](http://github.com/cms-sw/cmssw/pull/42288){:target="_blank"}  from **@cgsavard**: Add track MVA1 to DQM tools for future studies `dqm` `trk` created: 2023-07-17 23:11:28 merged: 2023-07-19 13:29:44

64. [42287](http://github.com/cms-sw/cmssw/pull/42287){:target="_blank"}  from **@Dr15Jones**: Removed unnecessary lazy object selection in TopMonitor `dqm` created: 2023-07-17 20:40:43 merged: 2023-07-19 13:29:19

65. [42284](http://github.com/cms-sw/cmssw/pull/42284){:target="_blank"}  from **@francescobrivio**: Revert BeamSpot fallback logic `alca` `dqm` `reconstruction` `db` `tracking` created: 2023-07-17 20:22:12 merged: 2023-07-19 13:29:09

66. [42283](http://github.com/cms-sw/cmssw/pull/42283){:target="_blank"}  from **@srimanob**: Add 2023 ProdLike workflow `pdmv` `upgrade` created: 2023-07-17 18:17:14 merged: 2023-07-20 14:25:59

67. [42282](http://github.com/cms-sw/cmssw/pull/42282){:target="_blank"}  from **@sunilUIET**: Fix ZeroBias DQM module name in Reco Step `pdmv` `upgrade` created: 2023-07-17 14:12:43 merged: 2023-07-18 13:20:30

68. [42277](http://github.com/cms-sw/cmssw/pull/42277){:target="_blank"}  from **@youyingli**: Add HARVEST step to SKIM WF for Run3 `pdmv` `upgrade` created: 2023-07-16 13:15:03 merged: 2023-07-23 19:48:05

69. [42276](http://github.com/cms-sw/cmssw/pull/42276){:target="_blank"}  from **@bsunanda**: Run3-sim143 Test code to investigate the discrepancy between DDD and DD4hep for HGCal `simulation` created: 2023-07-16 09:59:11 merged: 2023-07-17 20:55:31

70. [42271](http://github.com/cms-sw/cmssw/pull/42271){:target="_blank"}  from **@wddgit**: Remove calls to getManyByType in DQM modules `dqm` created: 2023-07-14 20:58:18 merged: 2023-07-18 13:20:16

71. [42264](http://github.com/cms-sw/cmssw/pull/42264){:target="_blank"}  from **@lauridsj**: Fix EmissionVetoHook for BB4L `generators` created: 2023-07-14 11:03:52 merged: 2023-07-30 07:09:58

72. [42263](http://github.com/cms-sw/cmssw/pull/42263){:target="_blank"}  from **@bsunanda**: Phase2-hgx341I Modify the correct conversion code in some of the debug statements of the dd4hep version of HGCal geometry involving cassettes `geometry` `upgrade` created: 2023-07-14 03:53:22 merged: 2023-07-20 14:25:44

73. [42257](http://github.com/cms-sw/cmssw/pull/42257){:target="_blank"}  from **@fabiocos**: MTD reconstruction and validation: validation and debugging information for track - MTD matching studies `dqm` `reconstruction` `upgrade` created: 2023-07-13 14:27:58 merged: 2023-07-24 13:58:32

74. [42256](http://github.com/cms-sw/cmssw/pull/42256){:target="_blank"}  from **@pallabidas**: Adding photons to L1Ntuples `l1` created: 2023-07-13 12:56:30 merged: 2023-07-20 14:25:10

75. [42249](http://github.com/cms-sw/cmssw/pull/42249){:target="_blank"}  from **@wddgit**: Fix error code returned by cmsRun on a FallbackFileOpenError `core` created: 2023-07-12 16:57:02 merged: 2023-07-24 15:39:08

76. [42228](http://github.com/cms-sw/cmssw/pull/42228){:target="_blank"}  from **@iarspider**: Code changes for Protobuf 3.21.9 and TensorFlow 2.12 `dqm` `reconstruction` created: 2023-07-11 06:16:24 merged: 2023-08-01 19:51:51

77. [42212](http://github.com/cms-sw/cmssw/pull/42212){:target="_blank"}  from **@lwang046**: HCALDQM - Add occupancy-per-LS based ML monitoring plots `dqm` `hcal` created: 2023-07-07 06:39:01 merged: 2023-07-27 08:19:24

78. [42180](http://github.com/cms-sw/cmssw/pull/42180){:target="_blank"}  from **@vslokenb**: Top recoil hook cleaned `generators` created: 2023-07-03 20:44:28 merged: 2023-07-19 13:28:33

79. [42177](http://github.com/cms-sw/cmssw/pull/42177){:target="_blank"}  from **@eyigitba**: EMTF NNv16 Implementation `l1` created: 2023-07-03 16:08:17 merged: 2023-07-27 09:09:24

80. [42158](http://github.com/cms-sw/cmssw/pull/42158){:target="_blank"}  from **@srimanob**: Re-enable nb*AK8PuppiSoftDrop in PAT step `reconstruction` `xpog` created: 2023-06-29 23:40:24 merged: 2023-07-27 14:27:21

81. [42129](http://github.com/cms-sw/cmssw/pull/42129){:target="_blank"}  from **@NJManganelli**: Phase 2 forwardport FastHisto PR1130 `dqm` `l1` `upgrade` created: 2023-06-29 03:25:04 merged: 2023-07-17 20:58:32

82. [41995](http://github.com/cms-sw/cmssw/pull/41995){:target="_blank"}  from **@gsaha009**: Tau DQM miniAOD validation for MC `dqm` `simulation` created: 2023-06-17 12:55:46 merged: 2023-07-20 14:24:41

83. [41915](http://github.com/cms-sw/cmssw/pull/41915){:target="_blank"}  from **@quark2**: Change of GE21 layouts and plots, and VFAT status with VFAT mask and missing VFATs `dqm` `gem` created: 2023-06-10 04:18:09 merged: 2023-07-19 13:26:59

84. [41808](http://github.com/cms-sw/cmssw/pull/41808){:target="_blank"}  from **@p2l1-gtEmulator**: Phase-2 Global Trigger Emulator `l1` `upgrade` created: 2023-05-30 12:21:31 merged: 2023-07-25 13:31:55

#### CMSDIST Changes between Tags REL/CMSSW_13_2_0_pre3/el8_amd64_gcc11 and REL/CMSSW_13_3_0_pre1/el8_amd64_gcc11:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_13_2_0_pre3/el8_amd64_gcc11...REL/CMSSW_13_3_0_pre1/el8_amd64_gcc11)



1. [8622](http://github.com/cms-sw/cmsdist/pull/8622){:target="_blank"}  from **@cms-sw**: SCRAMV2: Do not create CMS_PAtH/etc/scramrc files which are taken care by SCRAmv1 created: 2023-07-31 09:11:29 merged: 2023-07-31 13:07:20

2. [8620](http://github.com/cms-sw/cmsdist/pull/8620){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-12-00 created: 2023-07-28 07:41:42 merged: 2023-07-28 07:42:20

3. [8618](http://github.com/cms-sw/cmsdist/pull/8618){:target="_blank"}  from **@fwyzard**: Update Intel oneAPI compiler to version 2023.2.0 created: 2023-07-27 15:06:10 merged: 2023-07-28 07:37:13

4. [8616](http://github.com/cms-sw/cmsdist/pull/8616){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1TMuon to V01-09-00 created: 2023-07-27 09:08:34 merged: 2023-07-27 09:09:04

5. [8615](http://github.com/cms-sw/cmsdist/pull/8615){:target="_blank"}  from **@cms-sw**: Update tag for DQM-HcalTasks to V00-01-00 created: 2023-07-27 07:29:50 merged: 2023-07-27 08:20:21

6. [8611](http://github.com/cms-sw/cmsdist/pull/8611){:target="_blank"}  from **@cms-sw**: cms-common: Added scram runtime site hook for xrootd created: 2023-07-24 13:19:58 merged: 2023-07-24 14:43:06

7. [8607](http://github.com/cms-sw/cmsdist/pull/8607){:target="_blank"}  from **@cms-sw**: SCRAMV2: Allow to query TOOLVERSION created: 2023-07-21 11:02:45 merged: 2023-07-22 09:21:48

8. [8606](http://github.com/cms-sw/cmsdist/pull/8606){:target="_blank"}  from **@belforte**: bump CRABClient v3.230612 to prod, save curren prod as pre created: 2023-07-20 13:41:21 merged: 2023-07-20 20:23:15

9. [8604](http://github.com/cms-sw/cmsdist/pull/8604){:target="_blank"}  from **@aandvalenzuela**: Update TBB to version 2021.9.0 created: 2023-07-20 07:27:58 merged: 2023-07-22 09:22:00

10. [8603](http://github.com/cms-sw/cmsdist/pull/8603){:target="_blank"}  from **@cms-sw**: [HDF5] disable cxx and enable threadsafe created: 2023-07-19 14:03:12 merged: 2023-07-22 09:22:42

11. [8602](http://github.com/cms-sw/cmsdist/pull/8602){:target="_blank"}  from **@cms-sw**: Added support to enable debug mode for root/llvm created: 2023-07-19 09:01:31 merged: 2023-07-19 12:48:36

12. [8601](http://github.com/cms-sw/cmsdist/pull/8601){:target="_blank"}  from **@aandvalenzuela**: Enable debug mode option for root, geant4, dd4hep and vecgeom created: 2023-07-18 08:55:05 merged: 2023-07-19 07:27:41

13. [8565](http://github.com/cms-sw/cmsdist/pull/8565){:target="_blank"}  from **@cms-sw**: Update TF to 2.12 (backport from IB/CMSSW_13_2_X/g13 branch) created: 2023-06-23 08:36:47 merged: 2023-08-01 19:51:56
