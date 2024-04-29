---
layout: post
rel_link:  "14_1_0_pre3"
title:  "CMSSW_14_1_0_pre3"
date:   2024-04-26 20:14:51
categories: cmssw
relmajor: 14
relminor: 1
relsubminor: 0
relpre: _pre3
---

# CMSSW_14_1_0_pre3
#### Changes since CMSSW_14_1_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_1_0_pre2...CMSSW_14_1_0_pre3)



1. [44850](http://github.com/cms-sw/cmssw/pull/44850){:target="_blank"}  from **@hqucms**: Fix metMCTable in NanoGEN `xpog` created: 2024-04-25 13:54:38 merged: 2024-04-25 21:06:21

2. [44839](http://github.com/cms-sw/cmssw/pull/44839){:target="_blank"}  from **@trackreco**: Add description of .702 workflow offset, introduced in PR #44708 `pdmv` `upgrade` created: 2024-04-24 14:24:16 merged: 2024-04-24 17:58:35

3. [44836](http://github.com/cms-sw/cmssw/pull/44836){:target="_blank"}  from **@fwyzard**: Add script to merge the JSON files produced by the FastTimerService `hlt` created: 2024-04-24 13:08:24 merged: 2024-04-24 19:16:37

4. [44829](http://github.com/cms-sw/cmssw/pull/44829){:target="_blank"}  from **@davidlange6**: optimize and protect DisplacedRegionSeedingVertexProducer against busy events `reconstruction` `tracking` created: 2024-04-24 08:19:47 merged: 2024-04-24 19:42:20

5. [44824](http://github.com/cms-sw/cmssw/pull/44824){:target="_blank"}  from **@cms-sw**: Update rocm_version.h include so that it works for ROCm 5.6 and above `heterogeneous` created: 2024-04-24 05:05:11 merged: 2024-04-24 18:49:49

6. [44823](http://github.com/cms-sw/cmssw/pull/44823){:target="_blank"}  from **@Dr15Jones**: Added exception if all caches are empty in PluginManager `core` created: 2024-04-23 17:55:49 merged: 2024-04-24 18:46:44

7. [44819](http://github.com/cms-sw/cmssw/pull/44819){:target="_blank"}  from **@mmusich**: miscellaneaous improvements to `PixelBaryCentreAnalyzer` `alca` `trk` created: 2024-04-23 14:22:28 merged: 2024-04-24 18:56:01

8. [44813](http://github.com/cms-sw/cmssw/pull/44813){:target="_blank"}  from **@mroguljic**: fix skipping qBin when reading template info `reconstruction` `trk` created: 2024-04-23 10:22:53 merged: 2024-04-24 19:15:31

9. [44810](http://github.com/cms-sw/cmssw/pull/44810){:target="_blank"}  from **@mmusich**: miscellaneous improvements to `LSNumberFilter` `alca` created: 2024-04-23 08:48:54 merged: 2024-04-24 18:55:21

10. [44809](http://github.com/cms-sw/cmssw/pull/44809){:target="_blank"}  from **@RSalvatico**: Correct one filterBit name in EGMNano and add one more `xpog` `egamma` created: 2024-04-23 08:27:26 merged: 2024-04-24 19:12:29

11. [44803](http://github.com/cms-sw/cmssw/pull/44803){:target="_blank"}  from **@smuzaffar**: [UBSAN] Fix shift exponent 64 is too large for 32-bit `l1` created: 2024-04-22 19:21:25 merged: 2024-04-24 18:45:43

12. [44802](http://github.com/cms-sw/cmssw/pull/44802){:target="_blank"}  from **@fwyzard**: Migrate `assert` to to `ALPAKA_ASSERT_ACC` `alca` `reconstruction` `db` `heterogeneous` `tracking` `trk` created: 2024-04-22 17:32:41 merged: 2024-04-23 11:34:27

13. [44801](http://github.com/cms-sw/cmssw/pull/44801){:target="_blank"}  from **@mmusich**: `BrokenLineFit` and `RiemannFit`: mask asserts behind `DEBUG` flags `reconstruction` `tracking` created: 2024-04-22 15:58:41 merged: 2024-04-23 15:17:12

14. [44798](http://github.com/cms-sw/cmssw/pull/44798){:target="_blank"}  from **@dinyar**: Fix position of unconstrained pT coming from OMTF `l1` created: 2024-04-22 11:00:36 merged: 2024-04-24 19:10:36

15. [44797](http://github.com/cms-sw/cmssw/pull/44797){:target="_blank"}  from **@24LopezR**: RecHit based Ecal/Hcal muon isolation `reconstruction` `xpog` `muon` created: 2024-04-22 10:57:11 merged: 2024-04-24 19:08:36

16. [44796](http://github.com/cms-sw/cmssw/pull/44796){:target="_blank"}  from **@smuzaffar**: [UBSAN] Initialize missing PixelBarrelValues members for phase1 `reconstruction` `tracking` created: 2024-04-22 06:29:36 merged: 2024-04-24 18:43:49

17. [44794](http://github.com/cms-sw/cmssw/pull/44794){:target="_blank"}  from **@depasse**: ECAL : Tool to create sqlite files for DB `db` `ecal` created: 2024-04-21 16:02:16 merged: 2024-04-26 11:59:51

18. [44790](http://github.com/cms-sw/cmssw/pull/44790){:target="_blank"}  from **@fwyzard**: Skip invalid HCAL PF rechits in PFRecHitTopologyESProducer `reconstruction` `heterogeneous` `pf` created: 2024-04-21 10:18:31 merged: 2024-04-22 15:33:38

19. [44788](http://github.com/cms-sw/cmssw/pull/44788){:target="_blank"}  from **@fwyzard**: Revert "CalorimeterDefinitions: don't return -1 as uint32_t" `reconstruction` `heterogeneous` created: 2024-04-21 09:56:40 merged: 2024-04-22 15:30:07

20. [44783](http://github.com/cms-sw/cmssw/pull/44783){:target="_blank"}  from **@phnattla**: HLT Menu check for the PCL Tracker Alignment `alca` created: 2024-04-19 12:43:07 merged: 2024-04-22 17:35:59

21. [44782](http://github.com/cms-sw/cmssw/pull/44782){:target="_blank"}  from **@hqucms**: Using explicit lazy parsing & concrete data types in SimpleFlatTableProducer `alca` `reconstruction` `xpog` `trk` created: 2024-04-19 00:45:43 merged: 2024-04-24 11:07:36

22. [44777](http://github.com/cms-sw/cmssw/pull/44777){:target="_blank"}  from **@fwyzard**: Update the #include files for ROCm v6.x `heterogeneous` created: 2024-04-18 17:09:09 merged: 2024-04-22 17:39:45

23. [44776](http://github.com/cms-sw/cmssw/pull/44776){:target="_blank"}  from **@SohamBhattacharya**: [Phase-2] [14_1_X] Configuration for Phase-2 HLT path validation `hlt` created: 2024-04-18 15:50:51 merged: 2024-04-22 17:40:08

24. [44775](http://github.com/cms-sw/cmssw/pull/44775){:target="_blank"}  from **@namapane**: Fix --docmd option in inspectNanoFile.py `xpog` created: 2024-04-18 15:13:21 merged: 2024-04-19 17:51:41

25. [44773](http://github.com/cms-sw/cmssw/pull/44773){:target="_blank"}  from **@AdrianoDee**: Allow Runtime Number of Hits for Alpaka Pixel Reconstruction `geometry` `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-04-18 14:56:18 merged: 2024-04-18 19:18:03

26. [44772](http://github.com/cms-sw/cmssw/pull/44772){:target="_blank"}  from **@rovere**: Add HLT Timing scripts. `hlt` created: 2024-04-18 11:38:57 merged: 2024-04-19 17:51:56

27. [44771](http://github.com/cms-sw/cmssw/pull/44771){:target="_blank"}  from **@mmusich**: add a unit test for `convertToRaw` `daq` `hlt` created: 2024-04-18 09:31:19 merged: 2024-04-22 17:40:43

28. [44765](http://github.com/cms-sw/cmssw/pull/44765){:target="_blank"}  from **@Raffaella07**: Adding Phase2 tracker T36, T37 and T38 (for IT studies) `alca` `geometry` `operations` `pdmv` `upgrade` `trk` created: 2024-04-17 16:22:38 merged: 2024-04-23 15:16:44

29. [44764](http://github.com/cms-sw/cmssw/pull/44764){:target="_blank"}  from **@mmusich**: fixup eta lookup in `absEtaLowEdges_` in miscellaneous `RecoEgamma/EgammaHLTProducers` plugins `hlt` `egamma` created: 2024-04-17 14:00:26 merged: 2024-04-18 15:17:05

30. [44753](http://github.com/cms-sw/cmssw/pull/44753){:target="_blank"}  from **@makortel**: Add tests for ProductID metadata consistency for ROOT and streamer formats `core` created: 2024-04-16 16:21:26 merged: 2024-04-18 15:17:25

31. [44748](http://github.com/cms-sw/cmssw/pull/44748){:target="_blank"}  from **@ykumar05**: High pT Tracks resolved: Fitting each track as a Helix! Dropping the  `fastsim` created: 2024-04-16 09:03:47 merged: 2024-04-19 17:52:20

32. [44742](http://github.com/cms-sw/cmssw/pull/44742){:target="_blank"}  from **@AdrianoDee**: Fix for `EndPath`s in `DependecyGraph` `core` created: 2024-04-15 14:55:57 merged: 2024-04-16 12:19:29

33. [44735](http://github.com/cms-sw/cmssw/pull/44735){:target="_blank"}  from **@missirol**: fix PSet of `EvFDaqDirector` in `convertToRaw.py` `hlt` created: 2024-04-15 08:35:47 merged: 2024-04-15 16:44:06

34. [44733](http://github.com/cms-sw/cmssw/pull/44733){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_0_X` (6/N) [`14_1_X`] `hlt` created: 2024-04-14 09:04:35 merged: 2024-04-14 22:02:13

35. [44730](http://github.com/cms-sw/cmssw/pull/44730){:target="_blank"}  from **@makortel**: Ignore errors from `alpaka::enqueue()` in `CachingAllocator::free()` `heterogeneous` created: 2024-04-12 18:06:36 merged: 2024-04-18 15:20:56

36. [44728](http://github.com/cms-sw/cmssw/pull/44728){:target="_blank"}  from **@TizianoBevilacqua**: adding HoE Tower based for photons `xpog` created: 2024-04-12 16:26:34 merged: 2024-04-14 22:44:05

37. [44727](http://github.com/cms-sw/cmssw/pull/44727){:target="_blank"}  from **@Dr15Jones**: Fix memory use when writing ParameterSets to files `core` created: 2024-04-12 16:00:05 merged: 2024-04-14 22:41:50

38. [44726](http://github.com/cms-sw/cmssw/pull/44726){:target="_blank"}  from **@hqucms**: Fix ParticleNetLegacy when running Nano on Run2UL samples `xpog` created: 2024-04-12 15:58:30 merged: 2024-04-12 20:56:12

39. [44719](http://github.com/cms-sw/cmssw/pull/44719){:target="_blank"}  from **@smorovic**: updated parameters and model for photon XGboost MVA (HLT) [14_1_X] `hlt` `reconstruction` `egamma` created: 2024-04-11 21:53:50 merged: 2024-04-12 20:27:59

40. [44717](http://github.com/cms-sw/cmssw/pull/44717){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_0_X` (5/N) [`14_1_X`] `hlt` created: 2024-04-11 21:46:58 merged: 2024-04-12 20:28:07

41. [44712](http://github.com/cms-sw/cmssw/pull/44712){:target="_blank"}  from **@fwyzard**: Reorganise alpaka kernel loop functions `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-04-11 15:24:44 merged: 2024-04-19 17:53:07

42. [44709](http://github.com/cms-sw/cmssw/pull/44709){:target="_blank"}  from **@namapane**: Prevent geniso to be run in nanogen `xpog` created: 2024-04-11 14:25:46 merged: 2024-04-14 22:39:33

43. [44708](http://github.com/cms-sw/cmssw/pull/44708){:target="_blank"}  from **@trackreco**: Support for Phase-2 mkFit initialStep track building `reconstruction` `pdmv` `upgrade` `tracking` created: 2024-04-11 13:03:21 merged: 2024-04-24 17:57:38

44. [44704](http://github.com/cms-sw/cmssw/pull/44704){:target="_blank"}  from **@mmusich**: Updates in Alignment/OfflineValidation used in Run3 re-reco validations `alca` `trk` created: 2024-04-11 08:19:25 merged: 2024-04-12 20:29:13

45. [44698](http://github.com/cms-sw/cmssw/pull/44698){:target="_blank"}  from **@makortel**: Workaround to produce exactly same data products in Serial and CUDA backends in Alpaka modules possibly used at HLT `alca` `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-04-10 20:22:32 merged: 2024-04-11 16:19:12

46. [44696](http://github.com/cms-sw/cmssw/pull/44696){:target="_blank"}  from **@NJManganelli**: Phase 2 GTT Add Extended Jets to buffers for GlobalTrigger `l1` created: 2024-04-10 17:44:35 merged: 2024-04-22 17:43:41

47. [44693](http://github.com/cms-sw/cmssw/pull/44693){:target="_blank"}  from **@jsamudio**: Fix crash in PF Clustering due to empty HCAL RecHits collection `reconstruction` `heterogeneous` `pf` created: 2024-04-10 15:09:26 merged: 2024-04-11 16:13:26

48. [44692](http://github.com/cms-sw/cmssw/pull/44692){:target="_blank"}  from **@fmanteca**: Removed pixelLayers requirement in MuonSelectors.cc `reconstruction` `muon` created: 2024-04-10 14:07:13 merged: 2024-04-11 17:48:12

49. [44691](http://github.com/cms-sw/cmssw/pull/44691){:target="_blank"}  from **@lucasrussell01**: Add Unified ParT to tau NanoAOD `reconstruction` `xpog` `tau` created: 2024-04-10 13:21:16 merged: 2024-04-19 12:48:54

50. [44688](http://github.com/cms-sw/cmssw/pull/44688){:target="_blank"}  from **@brallmond**: Updated Tau Filterbits for 2024 Data Taking `xpog` `tau` created: 2024-04-10 10:14:46 merged: 2024-04-11 17:41:52

51. [44685](http://github.com/cms-sw/cmssw/pull/44685){:target="_blank"}  from **@mbluj**: Modify tau sequences to not pull payloads from outside GT `reconstruction` `xpog` `tau` created: 2024-04-10 09:14:10 merged: 2024-04-14 22:36:45

52. [44681](http://github.com/cms-sw/cmssw/pull/44681){:target="_blank"}  from **@jonamotta**: Calo Layer-2 EG/TAU conditions for 2024 `l1` created: 2024-04-10 07:01:29 merged: 2024-04-22 17:44:21

53. [44678](http://github.com/cms-sw/cmssw/pull/44678){:target="_blank"}  from **@NJManganelli**: Phase 2 GTT fix miscellaneous bugs and add Displaced TrackJet HT `l1` `upgrade` created: 2024-04-09 22:38:29 merged: 2024-04-12 20:34:14

54. [44676](http://github.com/cms-sw/cmssw/pull/44676){:target="_blank"}  from **@fwyzard**: Use explicit acelerator types in alpaka tests `heterogeneous` created: 2024-04-09 16:13:40 merged: 2024-04-11 17:39:05

55. [44674](http://github.com/cms-sw/cmssw/pull/44674){:target="_blank"}  from **@kyungminparkdrums**: Update ECAL DQM GPU input tag module names for alpaka `dqm` created: 2024-04-09 14:41:54 merged: 2024-04-15 15:13:59

56. [44672](http://github.com/cms-sw/cmssw/pull/44672){:target="_blank"}  from **@hqucms**: Fix import path for nanoL1TrigObjCustomizeFull `l1` `xpog` created: 2024-04-09 14:12:53 merged: 2024-04-09 17:30:27

57. [44671](http://github.com/cms-sw/cmssw/pull/44671){:target="_blank"}  from **@stahlleiton**: Update UPC relval workflows `generators` `pdmv` `upgrade` created: 2024-04-09 14:04:25 merged: 2024-04-24 18:58:25

58. [44667](http://github.com/cms-sw/cmssw/pull/44667){:target="_blank"}  from **@hqucms**: Add orbitNumber to NanoAOD `xpog` created: 2024-04-09 09:46:04 merged: 2024-04-11 17:36:57

59. [44662](http://github.com/cms-sw/cmssw/pull/44662){:target="_blank"}  from **@bsunanda**: Phase2-sim156 Update the scripts to enable run on new scenarios of Phase2 geometry `dqm` `geometry` created: 2024-04-09 05:42:07 merged: 2024-04-22 17:44:45

60. [44661](http://github.com/cms-sw/cmssw/pull/44661){:target="_blank"}  from **@bsunanda**: phase2-sim155 Update the scripts to enable run on new scenarios of Phase2 geometry `simulation` created: 2024-04-09 05:39:48 merged: 2024-04-12 20:34:52

61. [44656](http://github.com/cms-sw/cmssw/pull/44656){:target="_blank"}  from **@fwyzard**: Move EventSetup record dependency to non-device source file `reconstruction` `pf` created: 2024-04-08 12:47:59 merged: 2024-04-11 17:35:57

62. [44653](http://github.com/cms-sw/cmssw/pull/44653){:target="_blank"}  from **@iarspider**: [CPP20] Fix deprecated enum arithmetics in SiPixelAliPCLThresholdsPayloadInspectorHelper `db` created: 2024-04-08 08:16:17 merged: 2024-04-11 17:34:36

63. [44651](http://github.com/cms-sw/cmssw/pull/44651){:target="_blank"}  from **@iarspider**: [CPP20] Remove references to deprecated std::is_pod `alca` created: 2024-04-08 07:12:49 merged: 2024-04-11 17:33:00

64. [44647](http://github.com/cms-sw/cmssw/pull/44647){:target="_blank"}  from **@forthommel**: CepGenInterface: Added missing include `generators` created: 2024-04-06 14:53:15 merged: 2024-04-19 17:54:46

65. [44646](http://github.com/cms-sw/cmssw/pull/44646){:target="_blank"}  from **@iarspider**: [GCC13] Temporary convert array-bounds errors into warnings `analysis` `dqm` `l1` `reconstruction` `simulation` `upgrade` `tracking` `trk` created: 2024-04-06 11:40:45 merged: 2024-04-18 15:21:28

66. [44642](http://github.com/cms-sw/cmssw/pull/44642){:target="_blank"}  from **@artlbv**: Add L1 objects into Run3Scouting Nano `xpog` created: 2024-04-06 09:14:05 merged: 2024-04-08 12:41:42

67. [44641](http://github.com/cms-sw/cmssw/pull/44641){:target="_blank"}  from **@AlexDeMoor**: Introduce Unified Particle Transformer AK4 jet tagger `reconstruction` `xpog` `btv` `tau` `jetmet` created: 2024-04-06 08:50:58 merged: 2024-04-16 12:04:48

68. [44640](http://github.com/cms-sw/cmssw/pull/44640){:target="_blank"}  from **@fwyzard**: Fixes for low-level alpaka based utilities `heterogeneous` created: 2024-04-05 23:28:51 merged: 2024-04-08 11:57:41

69. [44637](http://github.com/cms-sw/cmssw/pull/44637){:target="_blank"}  from **@mbluj**: Add reduced lepton time-life info to NanoAOD `pdmv` `upgrade` `xpog` `tau` created: 2024-04-05 17:04:50 merged: 2024-04-12 20:36:04

70. [44633](http://github.com/cms-sw/cmssw/pull/44633){:target="_blank"}  from **@iarspider**: Phase2L1CaloJetEmulator: fix maybe-uninitialized warning `l1` `upgrade` created: 2024-04-05 13:00:23 merged: 2024-04-11 17:32:05

71. [44624](http://github.com/cms-sw/cmssw/pull/44624){:target="_blank"}  from **@wddgit**: Improve behavior after exception in begin/end stream lumi `core` created: 2024-04-04 19:39:17 merged: 2024-04-19 17:56:17

72. [44623](http://github.com/cms-sw/cmssw/pull/44623){:target="_blank"}  from **@bonanomi**: [GenPartIsoProducer.cc] New plugin for gen-part isolation. `xpog` created: 2024-04-04 19:34:15 merged: 2024-04-08 12:40:27

73. [44622](http://github.com/cms-sw/cmssw/pull/44622){:target="_blank"}  from **@fwyzard**: Add a test for Alpaka libraries and build rules `heterogeneous` created: 2024-04-04 17:13:21 merged: 2024-04-08 12:43:37

74. [44620](http://github.com/cms-sw/cmssw/pull/44620){:target="_blank"}  from **@Dr15Jones**: Revert "Temporary: abort if cutParser fails to find methods" `reconstruction` created: 2024-04-04 14:18:57 merged: 2024-04-19 17:56:31

75. [44618](http://github.com/cms-sw/cmssw/pull/44618){:target="_blank"}  from **@iarspider**: PFTau.cc: remove pessimizing move `reconstruction` `tau` created: 2024-04-04 14:09:43 merged: 2024-04-08 12:37:57

76. [44614](http://github.com/cms-sw/cmssw/pull/44614){:target="_blank"}  from **@marinakolosova**: Updated AK8 path names for 2024 data-taking `dqm` created: 2024-04-04 12:28:53 merged: 2024-04-08 12:02:29

77. [44613](http://github.com/cms-sw/cmssw/pull/44613){:target="_blank"}  from **@slehti**: HLT Tau DQM for PNet taus `dqm` created: 2024-04-04 10:53:49 merged: 2024-04-09 17:23:42

78. [44611](http://github.com/cms-sw/cmssw/pull/44611){:target="_blank"}  from **@civanch**: [14_1_X Phase2 SIM] Fixed Birks saturation constants for HGCal scintillators `simulation` `upgrade` created: 2024-04-04 10:10:47 merged: 2024-04-08 12:36:39

79. [44610](http://github.com/cms-sw/cmssw/pull/44610){:target="_blank"}  from **@rseidita**: Adding CSC MEs to per-LS scope in Offline DQM `dqm` created: 2024-04-04 10:04:06 merged: 2024-04-12 20:36:10

80. [44608](http://github.com/cms-sw/cmssw/pull/44608){:target="_blank"}  from **@iarspider**: CalorimeterDefinitions: don't return -1 as uint32_t `reconstruction` `pf` created: 2024-04-04 09:10:05 merged: 2024-04-08 12:31:57

81. [44604](http://github.com/cms-sw/cmssw/pull/44604){:target="_blank"}  from **@rovere**: Move Muon Paths to use sequences in HLT Phase2 Menu. `hlt` created: 2024-04-03 19:23:38 merged: 2024-04-05 14:08:27

82. [44602](http://github.com/cms-sw/cmssw/pull/44602){:target="_blank"}  from **@iarspider**: Remove explicit SimHitCollection copy-constructor `simulation` `upgrade` created: 2024-04-03 13:38:12 merged: 2024-04-08 12:30:59

83. [44601](http://github.com/cms-sw/cmssw/pull/44601){:target="_blank"}  from **@BenjaminRS**: L1T P2: L1TrackVertexAssociationProducer bug fix to stop accessing data after move `l1` `upgrade` created: 2024-04-03 13:23:15 merged: 2024-04-08 19:01:29

84. [44600](http://github.com/cms-sw/cmssw/pull/44600){:target="_blank"}  from **@zhokin2**: Monitoring of Hcal adc sticking in neighbouring TS `dqm` created: 2024-04-03 08:38:59 merged: 2024-04-12 20:21:27

85. [44595](http://github.com/cms-sw/cmssw/pull/44595){:target="_blank"}  from **@dan131riley**: move DataRecord includes to HBHERecHitProducerGPU `reconstruction` created: 2024-04-02 21:20:31 merged: 2024-04-03 11:00:55

86. [44594](http://github.com/cms-sw/cmssw/pull/44594){:target="_blank"}  from **@saumyaphor4252**: Update L1TUtmTriggerMenu tag in 2024 MC GTs and for Run3 data RelVals `alca` created: 2024-04-02 18:59:23 merged: 2024-04-04 16:00:55

87. [44593](http://github.com/cms-sw/cmssw/pull/44593){:target="_blank"}  from **@civanch**: [14_1_X SIM] Clean-up MC truth infrastructure `simulation` created: 2024-04-02 17:58:19 merged: 2024-04-03 10:58:06

88. [44592](http://github.com/cms-sw/cmssw/pull/44592){:target="_blank"}  from **@swagata87**: Fix ordering of egamma HLT modules `hlt` `egamma` created: 2024-04-02 17:48:09 merged: 2024-04-04 15:56:11

89. [44591](http://github.com/cms-sw/cmssw/pull/44591){:target="_blank"}  from **@stahlleiton**: Change unsubjet_map in btag info producers to tracked `hlt` `reconstruction` `btv` created: 2024-04-02 15:52:43 merged: 2024-04-03 21:22:46

90. [44590](http://github.com/cms-sw/cmssw/pull/44590){:target="_blank"}  from **@Dr15Jones**: Temporary: abort if cutParser fails to find methods `core` `reconstruction` created: 2024-04-02 15:05:05 merged: 2024-04-03 22:48:19

91. [44589](http://github.com/cms-sw/cmssw/pull/44589){:target="_blank"}  from **@mmusich**: `TrackerAlignment_PayloadInspector`: add tag comparator in cylindrical coordinates `db` created: 2024-04-02 13:31:10 merged: 2024-04-04 15:52:35

92. [44588](http://github.com/cms-sw/cmssw/pull/44588){:target="_blank"}  from **@mmusich**: TkAl: protect unit tests against empty queries and drop unused tests `alca` `trk` created: 2024-04-02 13:04:16 merged: 2024-04-03 22:46:26

93. [44586](http://github.com/cms-sw/cmssw/pull/44586){:target="_blank"}  from **@riga**: Slight update to TensorFlowAOT interface. `ml` created: 2024-04-02 09:34:52 merged: 2024-04-03 10:22:56

94. [44574](http://github.com/cms-sw/cmssw/pull/44574){:target="_blank"}  from **@cms-L1TK**: Fix bug in L1 track duplicate removal for displaced tracking `l1` created: 2024-03-28 19:50:39 merged: 2024-04-18 15:24:31

95. [44573](http://github.com/cms-sw/cmssw/pull/44573){:target="_blank"}  from **@Dr15Jones**: Initialize cut parser earlier in NanoAODDQM module `xpog` created: 2024-03-28 19:14:09 merged: 2024-03-31 22:55:58

96. [44570](http://github.com/cms-sw/cmssw/pull/44570){:target="_blank"}  from **@mmusich**: add a unit test for conversion of `millepede.res` files into DB payloads `alca` `trk` created: 2024-03-28 16:16:39 merged: 2024-04-03 22:44:59

97. [44568](http://github.com/cms-sw/cmssw/pull/44568){:target="_blank"}  from **@radla118**: Update of the LumiPCC module veto list and afterglow factors for 2024 `alca` created: 2024-03-28 02:32:07 merged: 2024-04-03 22:53:27

98. [44564](http://github.com/cms-sw/cmssw/pull/44564){:target="_blank"}  from **@makortel**: If `TClass::GetClass()` fails in `TypeWithDict::byName()`, include the argument class name in the exception message `core` created: 2024-03-27 21:14:58 merged: 2024-03-28 23:58:42

99. [44562](http://github.com/cms-sw/cmssw/pull/44562){:target="_blank"}  from **@noepalm**: MTD reconstruction: propagation of track time of flight uncertainty to vertex reconstruction `reconstruction` `upgrade` `tracking` `mtd` created: 2024-03-27 17:59:01 merged: 2024-04-12 20:20:43

100. [44558](http://github.com/cms-sw/cmssw/pull/44558){:target="_blank"}  from **@rovere**: Add HGCAL Hit calibration to Phase2 HLT. `dqm` created: 2024-03-27 16:02:51 merged: 2024-04-03 22:51:27

101. [44552](http://github.com/cms-sw/cmssw/pull/44552){:target="_blank"}  from **@felicepantaleo**: HLT phase-2: fix HGCAL Layercluster and create common constants configuration for HGCAL `hlt` `hgcal` created: 2024-03-27 10:28:08 merged: 2024-03-31 22:52:59

102. [44549](http://github.com/cms-sw/cmssw/pull/44549){:target="_blank"}  from **@hjbossi**: Make PYTHIA 8 photon flux more configurable. `generators` created: 2024-03-26 17:57:05 merged: 2024-04-15 15:04:24

103. [44548](http://github.com/cms-sw/cmssw/pull/44548){:target="_blank"}  from **@martinamalberti**: [MTD] Addition of mtd association maps to the event content `simulation` `upgrade` created: 2024-03-26 17:52:34 merged: 2024-03-31 22:51:27

104. [44546](http://github.com/cms-sw/cmssw/pull/44546){:target="_blank"}  from **@brunolopesbr2**: Add QuadJet with 3 b-tag PNet trigger to the DQM offline `dqm` created: 2024-03-26 16:25:27 merged: 2024-04-04 23:43:12

105. [44545](http://github.com/cms-sw/cmssw/pull/44545){:target="_blank"}  from **@syuvivida**: Protection of hcalcalib DQM client when hltHcalCalibrationRaw is not found `dqm` created: 2024-03-26 16:21:15 merged: 2024-03-27 19:43:38

106. [44543](http://github.com/cms-sw/cmssw/pull/44543){:target="_blank"}  from **@dinyar**: Unpack displaced pT from OMTF at the uGMT inputs `l1` created: 2024-03-26 15:49:49 merged: 2024-04-02 15:47:23

107. [44537](http://github.com/cms-sw/cmssw/pull/44537){:target="_blank"}  from **@mmusich**: Improvements for `TrackerAlignment_PayloadInspector`: support OT-only comparisons and re-ordered TF{E}PX detid schemas `db` created: 2024-03-25 15:11:07 merged: 2024-03-27 20:01:48

108. [44535](http://github.com/cms-sw/cmssw/pull/44535){:target="_blank"}  from **@iarspider**: [CPP20][SIMULATION] Replace some enums with constexpr int `simulation` created: 2024-03-25 13:35:44 merged: 2024-03-28 23:56:07

109. [44534](http://github.com/cms-sw/cmssw/pull/44534){:target="_blank"}  from **@iarspider**: [CPP20][L1,UPGRADE] Replace some enums with constexpr ints `l1` `simulation` `upgrade` created: 2024-03-25 13:10:33 merged: 2024-03-28 23:55:28

110. [44531](http://github.com/cms-sw/cmssw/pull/44531){:target="_blank"}  from **@smorovic**: XGBoost producer bugfix and unit test fix for non-x86_64 (14_1_X) `reconstruction` `egamma` created: 2024-03-25 10:52:54 merged: 2024-03-31 22:50:20

111. [44530](http://github.com/cms-sw/cmssw/pull/44530){:target="_blank"}  from **@iarspider**: [CLANG_X] Use generated ctor in VertexProperty `simulation` created: 2024-03-25 09:53:53 merged: 2024-03-31 22:49:32

112. [44529](http://github.com/cms-sw/cmssw/pull/44529){:target="_blank"}  from **@iarspider**: [CLANG_X] Use generated copy ctor in WeightsInfo `generators` created: 2024-03-25 09:51:15 merged: 2024-03-28 12:31:48

113. [44528](http://github.com/cms-sw/cmssw/pull/44528){:target="_blank"}  from **@iarspider**: [CLANG_X] Use generated copy ctor in FTLDataFrameT `simulation` `upgrade` created: 2024-03-25 09:48:55 merged: 2024-03-31 22:48:16

114. [44519](http://github.com/cms-sw/cmssw/pull/44519){:target="_blank"}  from **@riga**: Enable TensorFlowAOT unit tests, remove dev workflow. `ml` created: 2024-03-22 17:18:29 merged: 2024-03-31 22:47:32

115. [44518](http://github.com/cms-sw/cmssw/pull/44518){:target="_blank"}  from **@stahlleiton**: Add PF HF sum energy to reco::Centrality `dqm` `reconstruction` created: 2024-03-22 16:24:36 merged: 2024-04-03 22:43:30

116. [44515](http://github.com/cms-sw/cmssw/pull/44515){:target="_blank"}  from **@iarspider**: [CPP20][DQM] Replace some enums with constexpr ints `dqm` `reconstruction` `simulation` created: 2024-03-22 14:17:12 merged: 2024-04-02 14:13:31

117. [44514](http://github.com/cms-sw/cmssw/pull/44514){:target="_blank"}  from **@iarspider**: [CPP20][GEOMETRY] Replace some enums with constexpr ints `geometry` `simulation` created: 2024-03-22 13:16:17 merged: 2024-03-28 23:52:01

118. [44513](http://github.com/cms-sw/cmssw/pull/44513){:target="_blank"}  from **@felicepantaleo**: ticlv5: Optimize CLUE2D `reconstruction` `upgrade` created: 2024-03-22 13:05:29 merged: 2024-04-01 17:30:18

119. [44510](http://github.com/cms-sw/cmssw/pull/44510){:target="_blank"}  from **@artlbv**: AXOL1TL emulator update for L1 Menu parsing with UTMv12 `hlt` `l1` created: 2024-03-22 10:35:54 merged: 2024-03-27 15:34:44

120. [44509](http://github.com/cms-sw/cmssw/pull/44509){:target="_blank"}  from **@iarspider**: [CPP20][ALCA] Replace some enums with constexpr ints `alca` `trk` created: 2024-03-22 09:47:40 merged: 2024-03-28 12:31:01

121. [44507](http://github.com/cms-sw/cmssw/pull/44507){:target="_blank"}  from **@cmantill**: Add ParticleNet legacy discriminator scores and mass regression to MINIAOD `reconstruction` `xpog` created: 2024-03-22 04:29:58 merged: 2024-03-27 20:11:24

122. [44503](http://github.com/cms-sw/cmssw/pull/44503){:target="_blank"}  from **@vlimant**: new Prompt Lepton ID MVA (and renaming) `operations` `reconstruction` `xpog` `muon` `egamma` created: 2024-03-21 16:05:22 merged: 2024-03-31 23:05:04

123. [44492](http://github.com/cms-sw/cmssw/pull/44492){:target="_blank"}  from **@vlimant**: Hcalnano autonano `operations` `pdmv` `upgrade` `xpog` `hcal` created: 2024-03-20 12:02:35 merged: 2024-03-28 12:39:50

124. [44484](http://github.com/cms-sw/cmssw/pull/44484){:target="_blank"}  from **@Dr15Jones**: Use default ctr in HGCal data formats `simulation` `upgrade` created: 2024-03-20 11:02:28 merged: 2024-03-28 12:32:30

125. [44479](http://github.com/cms-sw/cmssw/pull/44479){:target="_blank"}  from **@nurfikri89**: [NanoAOD] Add number of B & C hadrons for GenJetAK8 and GenJet `xpog` created: 2024-03-20 08:40:09 merged: 2024-03-28 12:34:34

126. [44471](http://github.com/cms-sw/cmssw/pull/44471){:target="_blank"}  from **@aehart**: Numerical stability fix for Phase 2 L1 tracking `l1` created: 2024-03-19 17:35:17 merged: 2024-03-27 19:55:09

127. [44453](http://github.com/cms-sw/cmssw/pull/44453){:target="_blank"}  from **@Dr15Jones**: Added python type annotation to some configuration classes `core` created: 2024-03-18 16:38:38 merged: 2024-03-31 22:41:03

128. [44451](http://github.com/cms-sw/cmssw/pull/44451){:target="_blank"}  from **@iarspider**: [CPP20] Remove deprecated implicit capture of this `core` `reconstruction` `upgrade` `heterogeneous` created: 2024-03-18 14:37:24 merged: 2024-03-28 12:27:29

129. [44411](http://github.com/cms-sw/cmssw/pull/44411){:target="_blank"}  from **@esiam**: JME DQM implementation of Z/Gamma plus Jet monitoring for Run3  (14_1_X) `dqm` created: 2024-03-15 09:05:16 merged: 2024-04-03 22:41:14

130. [44391](http://github.com/cms-sw/cmssw/pull/44391){:target="_blank"}  from **@vlimant**: l1nano import location `operations` `pdmv` `upgrade` `xpog` created: 2024-03-13 13:02:32 merged: 2024-04-02 14:10:13

131. [44373](http://github.com/cms-sw/cmssw/pull/44373){:target="_blank"}  from **@JHiltbrand**: Add Veto Threshold to HCAL TP Emulator `alca` `l1` `db` created: 2024-03-11 22:44:46 merged: 2024-03-27 16:59:56

132. [44353](http://github.com/cms-sw/cmssw/pull/44353){:target="_blank"}  from **@24LopezR**: Add reco::Muon displacedMuons to offline validation sequences `dqm` created: 2024-03-08 09:10:06 merged: 2024-04-02 14:15:52

133. [44349](http://github.com/cms-sw/cmssw/pull/44349){:target="_blank"}  from **@Duchstf**: Tau spring24 update `l1` `upgrade` created: 2024-03-07 20:08:55 merged: 2024-04-11 17:30:42

134. [44346](http://github.com/cms-sw/cmssw/pull/44346){:target="_blank"}  from **@cerminar**: Phase2 L1T, Correlator Layer-2 : support emulation of with TMUX18 input + GT interface tweaks `l1` `upgrade` created: 2024-03-07 17:08:50 merged: 2024-03-31 22:40:12

135. [44336](http://github.com/cms-sw/cmssw/pull/44336){:target="_blank"}  from **@rseidita**: Adding PUPPI jets and METs to offline DQM `dqm` created: 2024-03-07 09:04:27 merged: 2024-04-24 11:12:40

136. [44335](http://github.com/cms-sw/cmssw/pull/44335){:target="_blank"}  from **@wajidalikhan**: slimmedMETsNoHF and possible cleanup `dqm` `reconstruction` `xpog` created: 2024-03-07 06:38:40 merged: 2024-03-27 19:52:19

137. [44050](http://github.com/cms-sw/cmssw/pull/44050){:target="_blank"}  from **@nurfikri89**: [Puppi] Hadronic tau recovery with protection for fromPV==2 charged particles `reconstruction` `xpog` `tau` `jetmet` created: 2024-02-21 19:42:29 merged: 2024-04-01 17:28:57

138. [43957](http://github.com/cms-sw/cmssw/pull/43957){:target="_blank"}  from **@lathomas**: Customized L1T NanoAOD `l1` `pdmv` `upgrade` `xpog` created: 2024-02-13 22:16:36 merged: 2024-04-08 12:15:49

139. [43925](http://github.com/cms-sw/cmssw/pull/43925){:target="_blank"}  from **@bhattlokesh2027**: Cell offset and Cell area calculation of partial wafer cells for HGCAL V18 `geometry` `upgrade` created: 2024-02-09 07:04:09 merged: 2024-04-11 17:27:57

140. [43815](http://github.com/cms-sw/cmssw/pull/43815){:target="_blank"}  from **@slava77**: enable mkFit for pixelLess iteration `operations` `tracking` created: 2024-01-30 16:11:12 merged: 2024-04-09 15:17:14

141. [43485](http://github.com/cms-sw/cmssw/pull/43485){:target="_blank"}  from **@Ming-Yan**: [NanoAOD,BTVNano] Btvnano integration as customized module `reconstruction` `pdmv` `upgrade` `xpog` `pf` `jetmet` created: 2023-12-04 09:28:40 merged: 2024-04-08 12:07:58

#### CMSDIST Changes between Tags REL/CMSSW_14_1_0_pre2/el8_amd64_gcc12 and REL/CMSSW_14_1_0_pre3/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_1_0_pre2/el8_amd64_gcc12...REL/CMSSW_14_1_0_pre3/el8_amd64_gcc12)



1. [9161](http://github.com/cms-sw/cmsdist/pull/9161){:target="_blank"}  from **@cms-sw**: scram-project-build: simple formating of config/Self.xml created: 2024-04-25 09:24:00 merged: 2024-04-25 14:14:22

2. [9159](http://github.com/cms-sw/cmsdist/pull/9159){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-MkFit to V00-14-00 created: 2024-04-24 17:56:28 merged: 2024-04-24 17:56:29

3. [9157](http://github.com/cms-sw/cmsdist/pull/9157){:target="_blank"}  from **@cms-sw**: deploy new site based os mismatch check hook created: 2024-04-24 11:32:50 merged: 2024-04-24 14:03:13

4. [9154](http://github.com/cms-sw/cmsdist/pull/9154){:target="_blank"}  from **@cms-sw**: for multi-arch set SCRAM_TARGET to auto MULTIARCH/SKYLAKE otherwise to default created: 2024-04-24 05:25:10 merged: 2024-04-24 11:27:52

5. [9153](http://github.com/cms-sw/cmsdist/pull/9153){:target="_blank"}  from **@cms-sw**: Revert "Update ROCm to version 6.1.0" created: 2024-04-24 05:04:08 merged: 2024-04-24 19:00:00

6. [9149](http://github.com/cms-sw/cmsdist/pull/9149){:target="_blank"}  from **@cms-sw**: cmssw-env: add --show-command option created: 2024-04-19 16:34:19 merged: 2024-04-20 04:20:27

7. [9147](http://github.com/cms-sw/cmsdist/pull/9147){:target="_blank"}  from **@belforte**: Bump crab-prod to v3.240416 after validation in crab-dev created: 2024-04-18 13:10:23 merged: 2024-04-18 22:44:17

8. [9146](http://github.com/cms-sw/cmsdist/pull/9146){:target="_blank"}  from **@cms-sw**: Add cmssw/external/lib to RIVET_ANALYSIS_PATH created: 2024-04-17 21:56:28 merged: 2024-04-18 12:45:46

9. [9143](http://github.com/cms-sw/cmsdist/pull/9143){:target="_blank"}  from **@fwyzard**: Update ROCm to version 6.1.0 created: 2024-04-17 15:20:19 merged: 2024-04-22 17:39:39

10. [9141](http://github.com/cms-sw/cmsdist/pull/9141){:target="_blank"}  from **@cms-sw**: Rivet: use eigen flags; update rivet analysis path for multi-arch created: 2024-04-17 10:11:08 merged: 2024-04-17 13:01:01

11. [9139](http://github.com/cms-sw/cmsdist/pull/9139){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-22-00 created: 2024-04-17 00:53:33 merged: 2024-04-17 00:53:34

12. [9138](http://github.com/cms-sw/cmsdist/pull/9138){:target="_blank"}  from **@belforte**: Update crab-dev to latest tag created: 2024-04-16 20:31:12 merged: 2024-04-17 10:27:01

13. [9137](http://github.com/cms-sw/cmsdist/pull/9137){:target="_blank"}  from **@cms-sw**: Enable multi-arch build for unit tests created: 2024-04-15 10:14:17 merged: 2024-04-16 07:01:33

14. [9135](http://github.com/cms-sw/cmsdist/pull/9135){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-PhotonIdentification to V01-08-00 created: 2024-04-13 18:40:03 merged: 2024-04-13 18:40:04

15. [9134](http://github.com/cms-sw/cmsdist/pull/9134){:target="_blank"}  from **@fwyzard**: Add NVML python bindings created: 2024-04-13 07:11:30 merged: 2024-04-18 10:55:30

16. [9126](http://github.com/cms-sw/cmsdist/pull/9126){:target="_blank"}  from **@fwyzard**: Update to CUDA 12.4.1 created: 2024-04-08 11:51:25 merged: 2024-04-11 06:14:35

17. [9122](http://github.com/cms-sw/cmsdist/pull/9122){:target="_blank"}  from **@forthommel**: [14_1_X] Bumped CepGen version to 1.2.3 created: 2024-04-06 10:25:23 merged: 2024-04-19 17:54:01

18. [9121](http://github.com/cms-sw/cmsdist/pull/9121){:target="_blank"}  from **@fwyzard**: Build alpaka code in GPU-only mode created: 2024-04-05 15:53:11 merged: 2024-04-08 21:25:40

19. [9120](http://github.com/cms-sw/cmsdist/pull/9120){:target="_blank"}  from **@belforte**: bump crabclient to v3.240404 created: 2024-04-05 15:22:02 merged: 2024-04-06 11:09:21

20. [9115](http://github.com/cms-sw/cmsdist/pull/9115){:target="_blank"}  from **@cms-sw**: [BuildRules] Export cuda/rocm static libs from the base release created: 2024-04-05 10:45:29 merged: 2024-04-05 14:38:34

21. [9114](http://github.com/cms-sw/cmsdist/pull/9114){:target="_blank"}  from **@belforte**: Update crab-dev to v4.230404 (fix for external/objs-) created: 2024-04-04 10:10:25 merged: 2024-04-04 21:31:45

22. [9112](http://github.com/cms-sw/cmsdist/pull/9112){:target="_blank"}  from **@smuzaffar**: [ROOT]Updated root version to 6.30.06 created: 2024-04-03 21:33:43 merged: 2024-04-08 14:53:41

23. [9108](http://github.com/cms-sw/cmsdist/pull/9108){:target="_blank"}  from **@riga**: Update cms-tfaot and test models. created: 2024-04-02 09:34:42 merged: 2024-04-03 10:22:06

24. [9107](http://github.com/cms-sw/cmsdist/pull/9107){:target="_blank"}  from **@cms-sw**: tensorflow-xla-runtime: fix for TF 2.15 created: 2024-04-02 08:40:37 merged: 2024-04-02 09:51:41

25. [9105](http://github.com/cms-sw/cmsdist/pull/9105){:target="_blank"}  from **@cms-sw**: Update tag for PhysicsTools-NanoAOD to V01-04-00 created: 2024-03-31 23:04:08 merged: 2024-03-31 23:04:09

26. [9104](http://github.com/cms-sw/cmsdist/pull/9104){:target="_blank"}  from **@belforte**: Update crab-dev.spec (client v3.240216) created: 2024-03-29 11:05:36 merged: 2024-03-30 05:15:10

27. [9102](http://github.com/cms-sw/cmsdist/pull/9102){:target="_blank"}  from **@cms-sw**: [BuildRules] fix alpaka/rocm rules created: 2024-03-28 12:50:40 merged: 2024-03-29 09:17:29

28. [9093](http://github.com/cms-sw/cmsdist/pull/9093){:target="_blank"}  from **@riga**: Add tools to build TF AOT models created: 2024-03-22 17:16:24 merged: 2024-03-31 22:46:29
