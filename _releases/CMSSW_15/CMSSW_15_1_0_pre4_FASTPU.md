---
layout: post
rel_link:  "15_1_0_pre4_FASTPU"
title:  "CMSSW_15_1_0_pre4_FASTPU"
date:   2025-07-09 18:46:21
categories: cmssw
relmajor: 15
relminor: 1
relsubminor: 0
relpre: _pre4
---

# CMSSW_15_1_0_pre4_FASTPU
#### Changes since CMSSW_15_1_0_pre3_FASTPU:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_15_1_0_pre3_FASTPU...CMSSW_15_1_0_pre4_FASTPU)



1. [48509](http://github.com/cms-sw/cmssw/pull/48509){:target="_blank"}  from **@mmusich**: fix HLT TICL reconstruction sequences when `ticl_barrel` is invoked in presence of the `alpaka` modifier `hlt` created: 2025-07-09 07:13:48 merged: 2025-07-09 13:00:12

2. [48488](http://github.com/cms-sw/cmssw/pull/48488){:target="_blank"}  from **@civanch**: [SIM] Clean up custom physics sub-library `simulation` created: 2025-07-06 12:11:56 merged: 2025-07-08 07:54:38

3. [48487](http://github.com/cms-sw/cmssw/pull/48487){:target="_blank"}  from **@michael-pitt**: add DQM plots for new CMS-FSC detector `dqm` created: 2025-07-06 02:15:39 merged: 2025-07-07 08:42:19

4. [48483](http://github.com/cms-sw/cmssw/pull/48483){:target="_blank"}  from **@hjbossi**: Change of HF threshold of OO era `l1` created: 2025-07-04 18:15:22 merged: 2025-07-04 21:55:00

5. [48482](http://github.com/cms-sw/cmssw/pull/48482){:target="_blank"}  from **@Pmeiring**: [L1T] Update CALO-L2 Tau Isolation LUT for 2025 post-TS1 `l1` created: 2025-07-04 16:12:31 merged: 2025-07-06 17:40:30

6. [48480](http://github.com/cms-sw/cmssw/pull/48480){:target="_blank"}  from **@ashleyahram**: update a vertex smearing parameters for 2025 pO MC `operations` `simulation` created: 2025-07-04 11:30:13 merged: 2025-07-06 15:29:03

7. [48478](http://github.com/cms-sw/cmssw/pull/48478){:target="_blank"}  from **@pallabidas**: [Phase-2 L1T] fixing out of bound indices in Phase2L1CaloPFClusterEmulator `l1` `upgrade` created: 2025-07-03 18:57:10 merged: 2025-07-08 07:56:02

8. [48477](http://github.com/cms-sw/cmssw/pull/48477){:target="_blank"}  from **@AdrianoDee**: Fix for `n_layers` Check in `CAHitNtupletAlpaka::globalBeginRun` `reconstruction` `tracking` created: 2025-07-03 14:54:40 merged: 2025-07-04 22:01:10

9. [48475](http://github.com/cms-sw/cmssw/pull/48475){:target="_blank"}  from **@CeliaFernandez**: Change fromVertex parameter from False to True for DGL reconstruction `reconstruction` created: 2025-07-03 13:45:14 merged: 2025-07-05 09:23:49

10. [48474](http://github.com/cms-sw/cmssw/pull/48474){:target="_blank"}  from **@mmusich**: Improved Event Content for the `TkAlHLT*` ALCARECO  `alca` created: 2025-07-03 12:29:32 merged: 2025-07-05 13:19:49

11. [48470](http://github.com/cms-sw/cmssw/pull/48470){:target="_blank"}  from **@mmusich**: remove warnings about `UnusedProductsForCanDeleteEarly` in the phase-2 HLT menu `hlt` created: 2025-07-03 07:43:05 merged: 2025-07-04 07:38:16

12. [48467](http://github.com/cms-sw/cmssw/pull/48467){:target="_blank"}  from **@fwyzard**: Update getCudaCoresPerSM for Blackwell GPUs `heterogeneous` created: 2025-07-03 05:02:18 merged: 2025-07-04 07:39:41

13. [48466](http://github.com/cms-sw/cmssw/pull/48466){:target="_blank"}  from **@fabiocos**: MTD DetId: add static methods to MTDDetId to test whether it is BTL or ETL `simulation` `upgrade` created: 2025-07-02 15:40:07 merged: 2025-07-04 22:01:47

14. [48464](http://github.com/cms-sw/cmssw/pull/48464){:target="_blank"}  from **@fabiocos**: MTD Validation: update vertex multiplicity plots `dqm` created: 2025-07-02 14:22:16 merged: 2025-07-04 22:00:49

15. [48463](http://github.com/cms-sw/cmssw/pull/48463){:target="_blank"}  from **@AdrianoDee**: HLT Phase2 Alpaka menu in `relval_gpu` `pdmv` `upgrade` created: 2025-07-02 13:55:57 merged: 2025-07-08 07:55:22

16. [48462](http://github.com/cms-sw/cmssw/pull/48462){:target="_blank"}  from **@elenavernazza**: [NGT] Fix filling of ValueMap for DeepJet scores for NanoAOD Phase2 HLT `hlt` `reconstruction` created: 2025-07-02 13:02:31 merged: 2025-07-04 07:38:52

17. [48461](http://github.com/cms-sw/cmssw/pull/48461){:target="_blank"}  from **@akritkbehera**: [TrackingTools/KalmanUpdators] Add using declaration to prevent funct `reconstruction` `tracking` created: 2025-07-02 10:20:32 merged: 2025-07-04 07:37:11

18. [48459](http://github.com/cms-sw/cmssw/pull/48459){:target="_blank"}  from **@ftorrresd**: Increase Nano relval WF counter buffer size `pdmv` `upgrade` `xpog` created: 2025-07-01 23:30:20 merged: 2025-07-05 09:23:36

19. [48454](http://github.com/cms-sw/cmssw/pull/48454){:target="_blank"}  from **@trackreco**: fix the loop range in mkFit MkFinder hit checks `reconstruction` `tracking` created: 2025-07-01 12:35:02 merged: 2025-07-01 16:40:57

20. [48453](http://github.com/cms-sw/cmssw/pull/48453){:target="_blank"}  from **@cms-ngt-hlt**: `ScoutingCollectionMonitor` add muon "Vtx" collections `dqm` `hlt` created: 2025-07-01 12:21:33 merged: 2025-07-04 22:00:28

21. [48451](http://github.com/cms-sw/cmssw/pull/48451){:target="_blank"}  from **@mmusich**: Introduce a stub of `LHCInfoPer*` Payload Inspector `db` created: 2025-06-30 18:55:03 merged: 2025-07-01 16:41:57

22. [48449](http://github.com/cms-sw/cmssw/pull/48449){:target="_blank"}  from **@hqucms**: [HGCAL] Update HGCal unpacker to handle flexible fedId assignment `reconstruction` `upgrade` created: 2025-06-30 14:52:07 merged: 2025-07-01 16:41:37

23. [48448](http://github.com/cms-sw/cmssw/pull/48448){:target="_blank"}  from **@bsunanda**: Run3-Sim164X Separate HcalTestNumbering flag for signal and PU which enables signal from FullSim and PU from FastSim `simulation` created: 2025-06-30 14:20:27 merged: 2025-07-04 07:40:02

24. [48446](http://github.com/cms-sw/cmssw/pull/48446){:target="_blank"}  from **@JHiltbrand**: Avoid FSC Channels when Making HCAL LUT XML Payloads `db` created: 2025-06-30 10:20:59 merged: 2025-07-01 16:41:12

25. [48444](http://github.com/cms-sw/cmssw/pull/48444){:target="_blank"}  from **@hjbossi**: Add protection to skip addition FSC channels. `l1` created: 2025-06-30 09:31:46 merged: 2025-06-30 14:18:48

26. [48442](http://github.com/cms-sw/cmssw/pull/48442){:target="_blank"}  from **@SegmentLinking**: LST notebooks for neural network training: make training reproducible `reconstruction` `tracking` created: 2025-06-30 00:15:53 merged: 2025-07-02 13:39:15

27. [48440](http://github.com/cms-sw/cmssw/pull/48440){:target="_blank"}  from **@mmusich**: apply `stage2` L1T customizations to `TrackToTrackComparisonHists` `dqm` `tracking` created: 2025-06-29 17:37:06 merged: 2025-07-01 16:40:42

28. [48437](http://github.com/cms-sw/cmssw/pull/48437){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `15_0_X` (8/N)  [`15_1_X`]  `hlt` created: 2025-06-28 10:19:40 merged: 2025-06-28 13:02:38

29. [48436](http://github.com/cms-sw/cmssw/pull/48436){:target="_blank"}  from **@bsunanda**: Run3-alca254 Add the new ways to introduce PF cuts from a file derived from DB `alca` created: 2025-06-28 09:56:47 merged: 2025-06-28 20:22:05

30. [48435](http://github.com/cms-sw/cmssw/pull/48435){:target="_blank"}  from **@smorovic**: [DAQ] add back RawEventOutputModule support for FEDRawDataCollection `daq` created: 2025-06-28 08:13:22 merged: 2025-06-28 12:44:35

31. [48433](http://github.com/cms-sw/cmssw/pull/48433){:target="_blank"}  from **@guitargeek**: Don't use facade functions in MnMigrad to modify parameter state `alca` `reconstruction` `tracking` created: 2025-06-27 15:15:28 merged: 2025-06-28 12:38:13

32. [48431](http://github.com/cms-sw/cmssw/pull/48431){:target="_blank"}  from **@li-chenyan**: [L1T] Changed the CENT012 Threshold for OO run `l1` created: 2025-06-27 14:08:53 merged: 2025-06-27 20:09:44

33. [48430](http://github.com/cms-sw/cmssw/pull/48430){:target="_blank"}  from **@flodamas**: Fix workflows 4.17 and 4.29 `pdmv` `upgrade` created: 2025-06-27 11:22:06 merged: 2025-06-27 20:13:22

34. [48428](http://github.com/cms-sw/cmssw/pull/48428){:target="_blank"}  from **@bsunanda**: Phase2-hgx364S Modify some parameters for the no cell option for the V19 scenario `geometry` `simulation` `upgrade` created: 2025-06-27 06:36:52 merged: 2025-07-03 06:41:49

35. [48425](http://github.com/cms-sw/cmssw/pull/48425){:target="_blank"}  from **@cms-ngt-hlt**: Extend NanoAOD for NGT Phase 2 Scouting with Tau and Gen information `hlt` `simulation` `pdmv` `upgrade` `xpog` created: 2025-06-26 15:27:53 merged: 2025-07-02 13:37:07

36. [48423](http://github.com/cms-sw/cmssw/pull/48423){:target="_blank"}  from **@eyigitba**: [L1T] Implementing sector based mode 7 promotion in EMTF for Run 3 2025 `l1` created: 2025-06-26 11:34:17 merged: 2025-06-26 18:28:19

37. [48421](http://github.com/cms-sw/cmssw/pull/48421){:target="_blank"}  from **@smorovic**: [DAQ] Phase-2 raw data product `daq` created: 2025-06-26 11:01:24 merged: 2025-06-27 20:55:10

38. [48417](http://github.com/cms-sw/cmssw/pull/48417){:target="_blank"}  from **@stahlleiton**: Reduce size of dEdx information in UPC and oxygen eras `reconstruction` `xpog` `tracking` created: 2025-06-26 03:43:19 merged: 2025-06-26 08:37:41

39. [48416](http://github.com/cms-sw/cmssw/pull/48416){:target="_blank"}  from **@Dr15Jones**: Refactored how begin/end/Job/Stream are implemented `core` `simulation` created: 2025-06-25 20:51:30 merged: 2025-06-28 12:37:23

40. [48414](http://github.com/cms-sw/cmssw/pull/48414){:target="_blank"}  from **@michael-pitt**: adds Heavy Ion initialization to Pythia `generators` created: 2025-06-25 18:49:55 merged: 2025-07-04 07:39:11

41. [48410](http://github.com/cms-sw/cmssw/pull/48410){:target="_blank"}  from **@cms-ngt-hlt**: Fix Jacobian for linefit in Brokenline. `reconstruction` `tracking` created: 2025-06-25 15:56:06 merged: 2025-06-26 12:17:17

42. [48406](http://github.com/cms-sw/cmssw/pull/48406){:target="_blank"}  from **@saswatinandan**: in run3_oxygen eras use triggerResultsFilterFromDB instead of HLTHigh `alca` `trk` created: 2025-06-25 13:02:38 merged: 2025-06-26 06:30:34

43. [48403](http://github.com/cms-sw/cmssw/pull/48403){:target="_blank"}  from **@mmasciov**: Strip overlap check for different product ID `reconstruction` `tracking` created: 2025-06-25 11:57:37 merged: 2025-06-26 08:39:56

44. [48398](http://github.com/cms-sw/cmssw/pull/48398){:target="_blank"}  from **@jprendi**: New HLT Scouting DQM Online Client `dqm` `hlt` created: 2025-06-24 19:21:12 merged: 2025-07-01 20:09:22

45. [48396](http://github.com/cms-sw/cmssw/pull/48396){:target="_blank"}  from **@ctdax**: Fixed G4LorentzVector usage, momentum updating, and energy deposit model in FullModelHadronicProcess.cc `simulation` created: 2025-06-24 13:37:04 merged: 2025-07-04 07:36:57

46. [48394](http://github.com/cms-sw/cmssw/pull/48394){:target="_blank"}  from **@rovere**: Extend NanoAOD for NGT Phase 2 Scouting and Association Handling `hlt` `simulation` `xpog` created: 2025-06-24 10:15:12 merged: 2025-06-25 05:48:12

47. [48393](http://github.com/cms-sw/cmssw/pull/48393){:target="_blank"}  from **@akritkbehera**: Updated to use __getitem__ `dqm` created: 2025-06-24 09:43:19 merged: 2025-06-30 15:28:19

48. [48391](http://github.com/cms-sw/cmssw/pull/48391){:target="_blank"}  from **@tvami**: Remove deprecated genParticleCandidates `analysis` `generators` `reconstruction` created: 2025-06-24 03:55:08 merged: 2025-07-03 08:37:02

49. [48386](http://github.com/cms-sw/cmssw/pull/48386){:target="_blank"}  from **@flodamas**: Muon skims for the 2025 light-ion runs `operations` `pdmv` `upgrade` created: 2025-06-23 14:15:28 merged: 2025-06-26 12:15:43

50. [48385](http://github.com/cms-sw/cmssw/pull/48385){:target="_blank"}  from **@gmelachr**: Update for BPHNano to solve issues with different compilers  `xpog` created: 2025-06-23 11:53:39 merged: 2025-06-30 17:52:57

51. [48379](http://github.com/cms-sw/cmssw/pull/48379){:target="_blank"}  from @mmusich: replace HLT menu to `**@fake2**` for wf 281.0 `pdmv` `upgrade` created: 2025-06-21 09:50:08 merged: 2025-06-22 16:00:07

52. [48375](http://github.com/cms-sw/cmssw/pull/48375){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `15_0_X` (7/N)  [`15_1_X`]  `hlt` created: 2025-06-20 08:48:24 merged: 2025-06-20 13:48:35

53. [48374](http://github.com/cms-sw/cmssw/pull/48374){:target="_blank"}  from **@civanch**: [SIM] Improved digi printouts `simulation` created: 2025-06-20 05:33:54 merged: 2025-06-21 07:28:50

54. [48365](http://github.com/cms-sw/cmssw/pull/48365){:target="_blank"}  from **@perrotta**:  Updated 2025 geometry in the 2025 MC GT for 151X `alca` created: 2025-06-18 17:43:03 merged: 2025-06-19 14:32:10

55. [48363](http://github.com/cms-sw/cmssw/pull/48363){:target="_blank"}  from **@mmasciov**: Fix CA cell hardCurvCut, to apply absolute value `reconstruction` `heterogeneous` `tracking` created: 2025-06-18 16:49:47 merged: 2025-06-19 11:48:39

56. [48361](http://github.com/cms-sw/cmssw/pull/48361){:target="_blank"}  from **@mmasciov**: Update HLT MultiTrackValidator `dqm` `tracking` created: 2025-06-18 14:19:38 merged: 2025-07-01 05:38:42

57. [48359](http://github.com/cms-sw/cmssw/pull/48359){:target="_blank"}  from **@CMS-LUMI-POG**: pileup profiles for RunIIIpp5p36Winter24 MC compaign `operations` `simulation` created: 2025-06-18 13:38:18 merged: 2025-06-20 05:27:24

58. [48358](http://github.com/cms-sw/cmssw/pull/48358){:target="_blank"}  from **@Dr15Jones**: Refactor Worker/Module system `core` `simulation` created: 2025-06-18 12:56:37 merged: 2025-06-19 18:08:38

59. [48356](http://github.com/cms-sw/cmssw/pull/48356){:target="_blank"}  from **@CMSTrackerDPG**: Adapt template pixel cpe algo to better handle shortened or broken clusters `operations` `reconstruction` `pdmv` `db` `upgrade` `trk` created: 2025-06-18 08:59:58 merged: 2025-06-24 15:23:41

60. [48354](http://github.com/cms-sw/cmssw/pull/48354){:target="_blank"}  from **@kyungminparkdrums**: [15_1_X] Update in ECAL DQM some ECAL TP Et monitoring plot displays from GeV to ADC `dqm` `ecal` created: 2025-06-18 08:22:54 merged: 2025-06-19 18:10:18

61. [48353](http://github.com/cms-sw/cmssw/pull/48353){:target="_blank"}  from **@mmusich**: remove obsolete parameter `transactionId` from `CondDBESSource` `alca` `db` created: 2025-06-18 08:03:19 merged: 2025-06-18 18:22:20

62. [48352](http://github.com/cms-sw/cmssw/pull/48352){:target="_blank"}  from **@llunerti**: Protect SoftMuonMvaRun3Estimator from returning nan `reconstruction` `xpog` created: 2025-06-18 07:57:06 merged: 2025-06-18 18:21:40

63. [48349](http://github.com/cms-sw/cmssw/pull/48349){:target="_blank"}  from **@hqucms**: Fix JMEnano workflow 11634.15 `xpog` created: 2025-06-17 15:26:27 merged: 2025-06-18 07:15:23

64. [48348](http://github.com/cms-sw/cmssw/pull/48348){:target="_blank"}  from **@iarspider**: Do not access itr->second if itr is invalid `geometry` `upgrade` created: 2025-06-17 14:49:04 merged: 2025-06-18 18:21:05

65. [48344](http://github.com/cms-sw/cmssw/pull/48344){:target="_blank"}  from **@smuzaffar**: [GCC14]Included header algorithm for std::max_element `core` created: 2025-06-17 12:35:58 merged: 2025-06-18 07:22:53

66. [48341](http://github.com/cms-sw/cmssw/pull/48341){:target="_blank"}  from **@bsunanda**: Run3-alca253 Provide run range in the IsoTrackAnalyzer code and provide cfg's for ACaReco and AlCaRaw o/p's `alca` created: 2025-06-17 11:40:42 merged: 2025-06-18 07:25:15

67. [48340](http://github.com/cms-sw/cmssw/pull/48340){:target="_blank"}  from **@BenjaminRS**: [L1T] Add Displaced Vertices into the default running of the P2 L1T Emulator (Phase 2) `l1` created: 2025-06-17 10:39:40 merged: 2025-06-18 07:53:40

68. [48338](http://github.com/cms-sw/cmssw/pull/48338){:target="_blank"}  from **@iarspider**: [DBG_X] Fix trackerMaterialAnalysisPlots unit test failure `simulation` created: 2025-06-17 08:55:16 merged: 2025-06-18 07:23:54

69. [48337](http://github.com/cms-sw/cmssw/pull/48337){:target="_blank"}  from **@civanch**: [SIM] Update handling of G4Regions, improved printouts, added Phase2 stacking action  `simulation` created: 2025-06-17 06:51:49 merged: 2025-06-18 07:25:54

70. [48336](http://github.com/cms-sw/cmssw/pull/48336){:target="_blank"}  from **@ftorrresd**: Fix Zero Division for Nano Size comparison `xpog` created: 2025-06-16 23:18:43 merged: 2025-06-17 08:21:56

71. [48335](http://github.com/cms-sw/cmssw/pull/48335){:target="_blank"}  from **@SegmentLinking**: Vectorize data pre-processing when training track embeddings in LST `reconstruction` `tracking` created: 2025-06-16 23:14:34 merged: 2025-06-18 07:17:37

72. [48334](http://github.com/cms-sw/cmssw/pull/48334){:target="_blank"}  from **@bsunanda**: Phase2-hgx364R Cure the failure of Relval 32034.0 as reported by Ivan in the issue #48331 `geometry` created: 2025-06-16 13:06:27 merged: 2025-06-17 07:03:26

73. [48333](http://github.com/cms-sw/cmssw/pull/48333){:target="_blank"}  from **@fabiocos**: MTD geometry: update defaults test scenario for MTD to D121 `geometry` `upgrade` created: 2025-06-16 12:15:00 merged: 2025-06-18 07:16:38

74. [48330](http://github.com/cms-sw/cmssw/pull/48330){:target="_blank"}  from **@Annnnya**: Changed openmpi to mpi in HeterogeneousCore packages `heterogeneous` created: 2025-06-16 03:36:15 merged: 2025-06-23 05:15:35

75. [48329](http://github.com/cms-sw/cmssw/pull/48329){:target="_blank"}  from **@denizsun**: [HCAL-DQM] Resolve fatal error introduced in PR #48211 (see issue #48243) `dqm` created: 2025-06-15 19:36:55 merged: 2025-06-19 18:09:38

76. [48327](http://github.com/cms-sw/cmssw/pull/48327){:target="_blank"}  from **@mmusich**: Add GEN-level HLT validation to standard validation sequences `dqm` created: 2025-06-14 16:59:50 merged: 2025-06-24 16:58:23

77. [48326](http://github.com/cms-sw/cmssw/pull/48326){:target="_blank"}  from **@BenjaminRS**: [L1T] Adding displaced vertices into L1Nano (Phase 2) `l1` `xpog` created: 2025-06-14 14:14:54 merged: 2025-06-18 07:17:13

78. [48325](http://github.com/cms-sw/cmssw/pull/48325){:target="_blank"}  from **@bsunanda**: Phase2-hgx364Q Correct the list of XML files for the option C27 that is used to create the scenario Run4D122 `geometry` `upgrade` created: 2025-06-14 13:12:18 merged: 2025-06-16 06:29:06

79. [48324](http://github.com/cms-sw/cmssw/pull/48324){:target="_blank"}  from **@mmusich**: update input file of `testPhase2PixelNtuple` `geometry` `upgrade` created: 2025-06-14 12:35:51 merged: 2025-06-15 20:49:53

80. [48323](http://github.com/cms-sw/cmssw/pull/48323){:target="_blank"}  from **@mmusich**: improve / fix Phase2 OT rechits validation for HLT `dqm` `trk` created: 2025-06-14 10:47:01 merged: 2025-06-19 12:58:22

81. [48321](http://github.com/cms-sw/cmssw/pull/48321){:target="_blank"}  from **@tvami**: Fix memory leak in GenHFHadronMatcher `analysis` created: 2025-06-14 04:38:26 merged: 2025-06-17 07:03:51

82. [48318](http://github.com/cms-sw/cmssw/pull/48318){:target="_blank"}  from **@BlancoFS**: Filter infinite loops in muon trajectory reconstruction [CMSHLT-3557] `reconstruction` `tracking` created: 2025-06-13 14:47:41 merged: 2025-06-18 07:14:05

83. [48316](http://github.com/cms-sw/cmssw/pull/48316){:target="_blank"}  from **@mmasciov**: Customization for HLT doublet-recovery tracking iteration with mkFit `reconstruction` `pdmv` `upgrade` `tracking` created: 2025-06-13 13:51:05 merged: 2025-06-17 07:05:17

84. [48314](http://github.com/cms-sw/cmssw/pull/48314){:target="_blank"}  from **@leobeltra**: Added std::span support to make_device_view and make_host_view `heterogeneous` created: 2025-06-13 12:22:48 merged: 2025-06-14 06:59:59

85. [48312](http://github.com/cms-sw/cmssw/pull/48312){:target="_blank"}  from **@kyungminparkdrums**: [15_1_X] Remove trailing blanks in the ECAL DQM histogram naming that cause error in ROOT636 and ROOT6 IBs `dqm` `ecal` created: 2025-06-13 08:17:39 merged: 2025-06-16 06:57:20

86. [48309](http://github.com/cms-sw/cmssw/pull/48309){:target="_blank"}  from **@perrotta**: Update 150X GTs as of 13/06/2025 in autoCond `alca` created: 2025-06-13 07:02:25 merged: 2025-06-16 06:28:35

87. [48306](http://github.com/cms-sw/cmssw/pull/48306){:target="_blank"}  from **@Dr15Jones**: Refactor how ED modules are constructed `core` `reconstruction` created: 2025-06-12 20:59:18 merged: 2025-06-16 06:58:58

88. [48304](http://github.com/cms-sw/cmssw/pull/48304){:target="_blank"}  from **@wddgit**: Remove remnants of SubProcess from Service System `core` `reconstruction` `heterogeneous` created: 2025-06-12 14:31:22 merged: 2025-06-16 06:31:02

89. [48301](http://github.com/cms-sw/cmssw/pull/48301){:target="_blank"}  from **@bsunanda**: Phase2-hgx364P0 Update the list of Eras in Configuration/StandardSequences `operations` created: 2025-06-12 01:54:07 merged: 2025-06-15 07:33:40

90. [48300](http://github.com/cms-sw/cmssw/pull/48300){:target="_blank"}  from **@fabiocos**: MTD geometry: set manually the unit test geometry scenario to avoid conflicts with tests of other scenarios `geometry` `reconstruction` `simulation` `upgrade` created: 2025-06-11 21:37:58 merged: 2025-06-12 08:46:14

91. [48299](http://github.com/cms-sw/cmssw/pull/48299){:target="_blank"}  from **@Dr15Jones**: Convert many tests to use catch2 in DataFormat/Common `core` created: 2025-06-11 21:14:54 merged: 2025-06-16 06:30:13

92. [48298](http://github.com/cms-sw/cmssw/pull/48298){:target="_blank"}  from **@cms-ngt-hlt**: HLT Nano: fix typo in DeepFlavour variables `hlt` created: 2025-06-11 16:06:09 merged: 2025-06-12 08:45:14

93. [48297](http://github.com/cms-sw/cmssw/pull/48297){:target="_blank"}  from **@bsunanda**: Phase2-hgx364P2 Change the default Phase2 scenario to Run4D121 til V19 is fully active `geometry` `upgrade` created: 2025-06-11 14:08:05 merged: 2025-06-13 15:19:00

94. [48296](http://github.com/cms-sw/cmssw/pull/48296){:target="_blank"}  from **@fabiocos**: MTD reconstruction: TrackExtender code cleanup `reconstruction` `upgrade` created: 2025-06-11 10:13:27 merged: 2025-06-16 06:28:10

95. [48295](http://github.com/cms-sw/cmssw/pull/48295){:target="_blank"}  from **@artlbv**: [Phase-2 HLT] Add hltHpsPFTau table to HLT Nano `hlt` created: 2025-06-11 09:47:37 merged: 2025-06-19 18:08:25

96. [48292](http://github.com/cms-sw/cmssw/pull/48292){:target="_blank"}  from **@bsunanda**: Phase2-hgx364P1 Update the workflow for V19 version of HGCal scenarios `pdmv` `upgrade` created: 2025-06-11 03:00:05 merged: 2025-06-12 08:47:59

97. [48291](http://github.com/cms-sw/cmssw/pull/48291){:target="_blank"}  from **@Dr15Jones**: Make BeamSpotOnlineProducer return consistent results `alca` `reconstruction` `tracking` created: 2025-06-10 22:25:53 merged: 2025-06-12 21:47:13

98. [48290](http://github.com/cms-sw/cmssw/pull/48290){:target="_blank"}  from **@AdrianoDee**: Add `L1P2GT` for Default Inputs `operations` created: 2025-06-10 20:55:28 merged: 2025-06-16 06:58:17

99. [48288](http://github.com/cms-sw/cmssw/pull/48288){:target="_blank"}  from **@akritkbehera**: Updated ROOT geometry version compatibility `visualization` created: 2025-06-10 16:45:50 merged: 2025-06-12 08:47:54

100. [48286](http://github.com/cms-sw/cmssw/pull/48286){:target="_blank"}  from **@Dr15Jones**: Add module types to ModuleAllocMonitor output `core` created: 2025-06-10 15:37:11 merged: 2025-06-11 08:15:24

101. [48285](http://github.com/cms-sw/cmssw/pull/48285){:target="_blank"}  from **@slava77**: LST replace uint4 by uint[4] array Params_pLS::ArrayUxHits `reconstruction` `heterogeneous` `tracking` created: 2025-06-10 14:51:31 merged: 2025-06-12 08:48:27

102. [48284](http://github.com/cms-sw/cmssw/pull/48284){:target="_blank"}  from **@bsunanda**: Phs2-hgx364P Update the definition of placement index so that the guard ring implementation in partial wafer can work fine `geometry` `upgrade` created: 2025-06-10 14:23:17 merged: 2025-06-11 08:14:23

103. [48283](http://github.com/cms-sw/cmssw/pull/48283){:target="_blank"}  from **@SegmentLinking**: Finalize refactoring of LST standalone to remove script-generated code `reconstruction` `tracking` created: 2025-06-10 14:05:39 merged: 2025-06-11 08:14:10

104. [48282](http://github.com/cms-sw/cmssw/pull/48282){:target="_blank"}  from **@bsunanda**: Phase2-hgx364O Update some of the scenarios so that the no-gap solution for V18 and beyond scenarios have no overlap issues `geometry` `upgrade` created: 2025-06-10 14:02:36 merged: 2025-06-11 08:16:49

105. [48281](http://github.com/cms-sw/cmssw/pull/48281){:target="_blank"}  from **@AdrianoDee**: Adding 2025 Data Wfs `pdmv` `upgrade` created: 2025-06-10 12:47:02 merged: 2025-06-19 05:11:48

106. [48279](http://github.com/cms-sw/cmssw/pull/48279){:target="_blank"}  from **@Dr15Jones**: Use constexpr in CondDB query building `db` created: 2025-06-09 20:19:36 merged: 2025-06-16 06:27:40

107. [48278](http://github.com/cms-sw/cmssw/pull/48278){:target="_blank"}  from **@kyungminparkdrums**: Add spike killer monitoring plots for ECAL DQM `dqm` `ecal` created: 2025-06-09 20:04:46 merged: 2025-06-12 08:46:39

108. [48276](http://github.com/cms-sw/cmssw/pull/48276){:target="_blank"}  from **@mmusich**: Improve shortened track monitoring  `alca` `dqm` `tracking` `trk` created: 2025-06-09 16:38:19 merged: 2025-06-11 15:54:00

109. [48274](http://github.com/cms-sw/cmssw/pull/48274){:target="_blank"}  from **@bsunanda**: Phase2-hgx364N Remove overlaps in the no gap solution of the V19 version of the HGCal scenario `geometry` `upgrade` created: 2025-06-09 12:52:42 merged: 2025-06-10 08:42:39

110. [48273](http://github.com/cms-sw/cmssw/pull/48273){:target="_blank"}  from **@bsunanda**: Phase2-hgx364M Remove overlaps from the V18ng scenario by making special treatments to HD2 and HD3 partial wafers `geometry` `upgrade` created: 2025-06-09 11:55:50 merged: 2025-06-10 08:41:47

111. [48271](http://github.com/cms-sw/cmssw/pull/48271){:target="_blank"}  from **@AdrianoDee**: Fix to `T35` Phase2 Tracker Geometry Module Counts in `SimplePixelTopology.h` `geometry` created: 2025-06-08 13:02:45 merged: 2025-06-17 07:04:23

112. [48270](http://github.com/cms-sw/cmssw/pull/48270){:target="_blank"}  from **@Dr15Jones**: Properly lock source for Run/Lumi transition `core` created: 2025-06-07 15:14:42 merged: 2025-06-10 13:30:29

113. [48268](http://github.com/cms-sw/cmssw/pull/48268){:target="_blank"}  from **@bsunanda**: Phase2-hgx364L Provide 2 methods in RechitTool to distinguish fine vs coarse tile sizes `geometry` `upgrade` created: 2025-06-07 03:30:28 merged: 2025-06-09 07:41:11

114. [48266](http://github.com/cms-sw/cmssw/pull/48266){:target="_blank"}  from **@fwyzard**: Improve sorting of `DetSetVector<CTPPSPixelRecHit>` `alca` `core` `reconstruction` created: 2025-06-06 16:40:11 merged: 2025-06-11 15:52:45

115. [48264](http://github.com/cms-sw/cmssw/pull/48264){:target="_blank"}  from **@Dr15Jones**: Remove const_cast from DaqProvenanceHelper `core` created: 2025-06-06 14:49:00 merged: 2025-06-07 08:29:23

116. [48262](http://github.com/cms-sw/cmssw/pull/48262){:target="_blank"}  from **@mmusich**: add phase-2 NANO HLT workflows to `ph2_hlt` short matrix `pdmv` `upgrade` created: 2025-06-06 10:45:20 merged: 2025-06-11 08:15:43

117. [48261](http://github.com/cms-sw/cmssw/pull/48261){:target="_blank"}  from **@perrotta**: Further 2025 MC GT update towards Spring25MC in autoCond `alca` created: 2025-06-06 10:33:12 merged: 2025-06-07 08:29:01

118. [48259](http://github.com/cms-sw/cmssw/pull/48259){:target="_blank"}  from **@Dr15Jones**: Use steady_clock directly in some services `core` created: 2025-06-05 20:01:46 merged: 2025-06-06 08:07:25

119. [48257](http://github.com/cms-sw/cmssw/pull/48257){:target="_blank"}  from **@Dr15Jones**: Keep proper file extension for ALCAReAlCaHLTHGComb workflow `pdmv` `upgrade` created: 2025-06-05 18:55:24 merged: 2025-06-12 08:46:59

120. [48256](http://github.com/cms-sw/cmssw/pull/48256){:target="_blank"}  from **@uttiyasarkar**: fix:Duplicate DeepCSV path removal, onnx model update `hlt` created: 2025-06-05 18:18:17 merged: 2025-06-10 13:32:15

121. [48253](http://github.com/cms-sw/cmssw/pull/48253){:target="_blank"}  from **@cms-ngt-hlt**: update sample for phase-2 HLT timing tests `hlt` created: 2025-06-05 07:02:26 merged: 2025-06-05 12:03:17

122. [48252](http://github.com/cms-sw/cmssw/pull/48252){:target="_blank"}  from **@Dr15Jones**: Removed mutable member from ProcInfoFetcher `core` created: 2025-06-04 22:27:38 merged: 2025-06-05 18:19:19

123. [48250](http://github.com/cms-sw/cmssw/pull/48250){:target="_blank"}  from **@jsamudio**: Add switch for scalar sum to LHEPtFilter `generators` created: 2025-06-04 22:04:46 merged: 2025-07-03 08:37:17

124. [48249](http://github.com/cms-sw/cmssw/pull/48249){:target="_blank"}  from **@SegmentLinking**: Track Embeddings for Improved Duplicate Removal in LST `reconstruction` `heterogeneous` `tracking` created: 2025-06-04 18:26:16 merged: 2025-06-05 17:22:12

125. [48247](http://github.com/cms-sw/cmssw/pull/48247){:target="_blank"}  from **@tschuh**: Fix for PR #47067 `l1` `upgrade` `trk` created: 2025-06-04 16:07:25 merged: 2025-06-09 21:22:21

126. [48246](http://github.com/cms-sw/cmssw/pull/48246){:target="_blank"}  from **@Parsifal-2045**: [NGT] Update default Phase 2 HLT Muon sequence  to use new Standalone seeding module and streamlined Tracker Muon reconstruction `dqm` `hlt` `operations` `pdmv` `upgrade` `xpog` created: 2025-06-04 15:51:05 merged: 2025-06-19 18:09:18

127. [48245](http://github.com/cms-sw/cmssw/pull/48245){:target="_blank"}  from **@Dr15Jones**: More asserts on geometry for HGCal `simulation` `upgrade` created: 2025-06-04 15:42:14 merged: 2025-06-10 13:28:59

128. [48244](http://github.com/cms-sw/cmssw/pull/48244){:target="_blank"}  from **@stahlleiton**: Use standard PV reco in Run3_2025_UPC_OXY `reconstruction` `tracking` created: 2025-06-04 15:35:33 merged: 2025-06-05 12:01:05

129. [48241](http://github.com/cms-sw/cmssw/pull/48241){:target="_blank"}  from **@bsunanda**: Phase2-hgx364K Add a sensitive detector creation file for HGCal which will work for no cell creation for the silicon part `geometry` `upgrade` created: 2025-06-04 04:18:41 merged: 2025-06-04 07:39:05

130. [48240](http://github.com/cms-sw/cmssw/pull/48240){:target="_blank"}  from **@bsunanda**: Phase2-hgx364J Make modifier for V19 version of HGCal and include this in 2 ERAs for this new version of HGCal `operations` created: 2025-06-04 04:05:56 merged: 2025-06-05 12:04:06

131. [48239](http://github.com/cms-sw/cmssw/pull/48239){:target="_blank"}  from **@bsunanda**: Phase2-hgx364I Update the test scripts in SimG4Core/PrintGeomInfo/test/python to accommodate new scenarios of HGCal geometry `simulation` created: 2025-06-04 01:45:45 merged: 2025-06-05 09:01:33

132. [48238](http://github.com/cms-sw/cmssw/pull/48238){:target="_blank"}  from **@bsunanda**: Phase2-hgx364H Add two new scenario for HGCal V19n and V19ng without cell declaration at G4 geometry level and removing the gaps `geometry` `operations` `upgrade` created: 2025-06-04 01:35:52 merged: 2025-06-10 08:40:58

133. [48237](http://github.com/cms-sw/cmssw/pull/48237){:target="_blank"}  from **@hjbossi**: HCAL DQM - Recover HF TPs `dqm` created: 2025-06-03 21:01:28 merged: 2025-06-05 12:02:27

134. [48236](http://github.com/cms-sw/cmssw/pull/48236){:target="_blank"}  from **@SegmentLinking**: Fix ROCm compilation of standalone LST `reconstruction` `tracking` created: 2025-06-03 18:44:59 merged: 2025-06-04 14:28:21

135. [48232](http://github.com/cms-sw/cmssw/pull/48232){:target="_blank"}  from **@mmusich**: add back HLT e/gamma GSF Tracking validation in Phase-2 `dqm` created: 2025-06-02 16:55:21 merged: 2025-06-04 07:40:44

136. [48231](http://github.com/cms-sw/cmssw/pull/48231){:target="_blank"}  from **@mmusich**: Improve TkAl Offline DQM `dqm` created: 2025-06-02 16:53:06 merged: 2025-06-04 07:40:05

137. [48230](http://github.com/cms-sw/cmssw/pull/48230){:target="_blank"}  from **@waredjeb**: Add score plots back in HGCAL Validation `dqm` created: 2025-06-02 15:49:31 merged: 2025-06-04 07:42:44

138. [48228](http://github.com/cms-sw/cmssw/pull/48228){:target="_blank"}  from **@smuzaffar**: typo: use correct variable name c27_ `geometry` `upgrade` created: 2025-06-02 05:33:33 merged: 2025-06-02 07:36:25

139. [48227](http://github.com/cms-sw/cmssw/pull/48227){:target="_blank"}  from **@mmusich**: Alignment Payload Inspector: add per layer, disk, Pixel Alignment Tracker Maps `db` created: 2025-06-01 16:27:45 merged: 2025-06-02 20:19:20

140. [48226](http://github.com/cms-sw/cmssw/pull/48226){:target="_blank"}  from **@mmusich**: add protection to `HLTPPSJetComparisonFilter` against faulty `LHCInfo` payloads (Energy=0) `hlt` created: 2025-06-01 16:26:47 merged: 2025-06-04 07:41:53

141. [48224](http://github.com/cms-sw/cmssw/pull/48224){:target="_blank"}  from **@mmusich**: add support for `ALCARECOTkAlHLTTracks` and `ALCARECOTkAlHLTTracksZMuMu` in `trackselectionRefitting` `alca` created: 2025-06-01 12:00:23 merged: 2025-06-02 07:26:14

142. [48222](http://github.com/cms-sw/cmssw/pull/48222){:target="_blank"}  from **@bsunanda**: Phase2-hgx364G Make coherent definitions of Wafer Size and Nominal Wafer Size for several scenarios using HGCal `geometry` `upgrade` created: 2025-05-31 08:44:09 merged: 2025-06-03 09:04:12

143. [48220](http://github.com/cms-sw/cmssw/pull/48220){:target="_blank"}  from **@makortel**: Add IOTrace debug-level messages to `edm::RootTree` `core` created: 2025-05-30 17:47:11 merged: 2025-06-05 19:38:45

144. [48219](http://github.com/cms-sw/cmssw/pull/48219){:target="_blank"}  from **@makortel**: Make empty and `'*'` `debugModules` to result in all debug messages to be printed `core` created: 2025-05-30 17:18:41 merged: 2025-06-05 18:19:33

145. [48218](http://github.com/cms-sw/cmssw/pull/48218){:target="_blank"}  from **@wddgit**: Remove SubProcess related code from FastTimerService `hlt` created: 2025-05-30 16:10:36 merged: 2025-06-04 07:41:20

146. [48217](http://github.com/cms-sw/cmssw/pull/48217){:target="_blank"}  from **@fwyzard**: Add missing includes to HGCalUnpacker `reconstruction` `upgrade` created: 2025-05-30 13:42:20 merged: 2025-06-04 07:40:34

147. [48216](http://github.com/cms-sw/cmssw/pull/48216){:target="_blank"}  from **@leobeltra**: Merged SoAView into SoALayout and added heterogeneous deepCopy for PortableCollections `alca` `reconstruction` `simulation` `db` `upgrade` `heterogeneous` created: 2025-05-30 10:13:34 merged: 2025-06-26 18:28:07

148. [48212](http://github.com/cms-sw/cmssw/pull/48212){:target="_blank"}  from **@mmusich**: do not apply long-distance interactions on `hltHgcalMergeLayerClusters` `hlt` created: 2025-05-30 08:49:46 merged: 2025-05-31 11:01:55

149. [48211](http://github.com/cms-sw/cmssw/pull/48211){:target="_blank"}  from **@denizsun**: [HCAL-DQM] Add Certification-Related DQM Plots and Fix FED 1118/1121 Yellow Status in DigiTask  `dqm` created: 2025-05-29 19:46:25 merged: 2025-06-04 07:42:29

150. [48209](http://github.com/cms-sw/cmssw/pull/48209){:target="_blank"}  from **@gmelachr**: BPH NanoAODs: increase precision and add decay modes `xpog` created: 2025-05-29 19:13:06 merged: 2025-05-31 11:02:02

151. [48208](http://github.com/cms-sw/cmssw/pull/48208){:target="_blank"}  from **@bsunanda**: Phase2-hgx364F Move HGCGuardRing.h(cc) from SimG4CMS/Calo to Geometry/HGCalCommonData `geometry` `simulation` `upgrade` created: 2025-05-29 16:03:25 merged: 2025-06-01 10:40:14

152. [48207](http://github.com/cms-sw/cmssw/pull/48207){:target="_blank"}  from **@Dr15Jones**: Added asserts to HGCal RecHit production code `reconstruction` `upgrade` created: 2025-05-29 13:38:30 merged: 2025-06-04 07:38:45

153. [48206](http://github.com/cms-sw/cmssw/pull/48206){:target="_blank"}  from **@bsunanda**: Phs2-hgx364E Make some bug fixes for the V18 and V19 versions of HGCal `geometry` `simulation` `upgrade` created: 2025-05-29 12:19:25 merged: 2025-05-31 11:01:00

154. [48204](http://github.com/cms-sw/cmssw/pull/48204){:target="_blank"}  from **@mmusich**: SiStrip Payload Inspector: fix swapped IoV list in comparison plots using `SiStripCondObjectRepresent` `db` `trk` created: 2025-05-29 07:17:17 merged: 2025-05-30 06:20:21

155. [48203](http://github.com/cms-sw/cmssw/pull/48203){:target="_blank"}  from **@makortel**: Allow temporary std::string messages for IntrusiveMonitorBase `core` created: 2025-05-28 19:42:54 merged: 2025-05-30 06:20:07

156. [48202](http://github.com/cms-sw/cmssw/pull/48202){:target="_blank"}  from **@makortel**: Extend edmStorageTrace.py to print read offset ranges and map those to the TFile contents `core` created: 2025-05-28 19:30:04 merged: 2025-05-30 06:23:11

157. [48201](http://github.com/cms-sw/cmssw/pull/48201){:target="_blank"}  from **@CTPPS**: PPS Diamond DQM Local Coordinate System Enhancement `dqm` created: 2025-05-28 19:26:14 merged: 2025-06-04 07:37:50

158. [48200](http://github.com/cms-sw/cmssw/pull/48200){:target="_blank"}  from **@makortel**: Add an option to edmFileUtil to print detailed basket information for a given branch `core` created: 2025-05-28 19:23:45 merged: 2025-05-31 11:00:26

159. [48199](http://github.com/cms-sw/cmssw/pull/48199){:target="_blank"}  from **@Dr15Jones**: Issue UnusedProductsForCanDeleteEarly message only once `core` created: 2025-05-28 19:16:58 merged: 2025-05-30 06:20:02

160. [48198](http://github.com/cms-sw/cmssw/pull/48198){:target="_blank"}  from **@mmusich**: Allow running `trackingMonitorHLT` DQM sequence in the same step as HLT `dqm` created: 2025-05-28 16:48:05 merged: 2025-05-31 11:00:35

161. [48196](http://github.com/cms-sw/cmssw/pull/48196){:target="_blank"}  from **@thesps**: Add the jet mass to the SC8 L1Nano table `l1` `xpog` created: 2025-05-28 15:19:48 merged: 2025-06-04 07:38:05

162. [48191](http://github.com/cms-sw/cmssw/pull/48191){:target="_blank"}  from **@makortel**: Remove `cms::cuda::ScopedContextTask` as unused `heterogeneous` created: 2025-05-28 13:32:58 merged: 2025-05-29 06:27:05

163. [48188](http://github.com/cms-sw/cmssw/pull/48188){:target="_blank"}  from **@bsunanda**: Phase2-hgx364D Make cog the default position for v19 while retrieving position from DetId `geometry` `upgrade` created: 2025-05-28 02:56:24 merged: 2025-05-28 14:08:29

164. [48185](http://github.com/cms-sw/cmssw/pull/48185){:target="_blank"}  from **@felicepantaleo**: [TICL] Reco to Sim score redefinition `simulation` `upgrade` created: 2025-05-27 15:11:58 merged: 2025-05-28 05:37:55

165. [48181](http://github.com/cms-sw/cmssw/pull/48181){:target="_blank"}  from **@smuzaffar**: [xSAN]Explicitly link against libresolv for Sanitizer IB `core` created: 2025-05-27 08:08:53 merged: 2025-05-30 09:34:37

166. [48180](http://github.com/cms-sw/cmssw/pull/48180){:target="_blank"}  from **@bsunanda**: Phase2-hgx364C Update the scripts in SimG4CMS/Calo/test/python for Run3 and Run4 scenarios `simulation` created: 2025-05-27 03:22:51 merged: 2025-05-28 05:36:45

167. [48179](http://github.com/cms-sw/cmssw/pull/48179){:target="_blank"}  from **@BenjaminRS**: [L1T] E2E NNVtx Track to Vertex Association in Puppi (Phase 2) `l1` `upgrade` created: 2025-05-26 21:24:30 merged: 2025-06-10 13:33:55

168. [48177](http://github.com/cms-sw/cmssw/pull/48177){:target="_blank"}  from **@bsunanda**: Phase2-hgx364B Make some corrections relevant for the V19 version of the HGCal code `geometry` `simulation` `upgrade` created: 2025-05-26 14:53:26 merged: 2025-05-27 05:13:11

169. [48175](http://github.com/cms-sw/cmssw/pull/48175){:target="_blank"}  from **@ftorrresd**: Add new line before Nano Comparison header `xpog` created: 2025-05-26 11:00:20 merged: 2025-05-26 17:30:57

170. [48173](http://github.com/cms-sw/cmssw/pull/48173){:target="_blank"}  from **@rdelliga**: BTL occupancy studies `dqm` created: 2025-05-26 09:11:49 merged: 2025-05-31 11:00:05

171. [48172](http://github.com/cms-sw/cmssw/pull/48172){:target="_blank"}  from **@leobeltra**: Fixed SOA(_CONST)_ELEMENT_METHODS sintax in the README `heterogeneous` created: 2025-05-26 08:31:45 merged: 2025-05-26 13:34:28

172. [48166](http://github.com/cms-sw/cmssw/pull/48166){:target="_blank"}  from **@bsunanda**: Phase2-hgx364A Update some of the tests in Geometry/HGCalGeometry/test to estimate the errors correctly `geometry` `simulation` `upgrade` created: 2025-05-24 03:20:05 merged: 2025-05-25 17:49:11

173. [48165](http://github.com/cms-sw/cmssw/pull/48165){:target="_blank"}  from **@bsunanda**: Phase2-hgx364 Make a new scenario Run4D121 using D116 + corrected RPC with the corresponding workflow 34434.0 `geometry` `operations` `pdmv` `upgrade` created: 2025-05-24 03:08:09 merged: 2025-05-27 05:08:40

174. [48160](http://github.com/cms-sw/cmssw/pull/48160){:target="_blank"}  from **@mbluj**: Fix initialisation / deactivation of XercesC in OMTF emulator code `l1` created: 2025-05-23 16:07:43 merged: 2025-05-24 08:18:38

175. [48159](http://github.com/cms-sw/cmssw/pull/48159){:target="_blank"}  from **@Dr15Jones**: Get ServiceToken in TStorageFactoryFile `core` created: 2025-05-23 14:53:35 merged: 2025-05-28 05:36:20

176. [48155](http://github.com/cms-sw/cmssw/pull/48155){:target="_blank"}  from **@CMS-HGCAL**: [HGCAL] Fix cell types in indexer `alca` `geometry` `reconstruction` `db` `upgrade` created: 2025-05-23 09:50:56 merged: 2025-05-31 10:59:51

177. [48154](http://github.com/cms-sw/cmssw/pull/48154){:target="_blank"}  from **@bsunanda**: Phase2-hgx363AN Update all the testscripts in Geometry/HGCalGeometry/test/python for the V19 HGCal Geometry `geometry` `upgrade` created: 2025-05-23 03:26:46 merged: 2025-05-23 12:55:00

178. [48153](http://github.com/cms-sw/cmssw/pull/48153){:target="_blank"}  from **@kpedro88**: Update FastSim 2024 Era, add 2025 workflow `operations` `pdmv` `upgrade` created: 2025-05-22 21:18:09 merged: 2025-05-28 05:36:50

179. [48152](http://github.com/cms-sw/cmssw/pull/48152){:target="_blank"}  from **@hqucms**: Update NANO relval workflows `dqm` `operations` `pdmv` `upgrade` `xpog` created: 2025-05-22 20:38:59 merged: 2025-06-02 20:19:02

180. [48151](http://github.com/cms-sw/cmssw/pull/48151){:target="_blank"}  from **@smuzaffar**: [UBSAN] Avoid large constructor for HDShower class `fastsim` created: 2025-05-22 17:34:15 merged: 2025-05-23 12:55:31

181. [48149](http://github.com/cms-sw/cmssw/pull/48149){:target="_blank"}  from **@andreypz**: Update DT calibration workflows to work with newest CMSSW releases `alca` created: 2025-05-22 13:57:10 merged: 2025-05-28 05:37:06

182. [48148](http://github.com/cms-sw/cmssw/pull/48148){:target="_blank"}  from **@tcuisset**: TICL: change Trackster SimToReco score, to fix overlapping CaloParticle issues `simulation` `upgrade` created: 2025-05-22 13:23:02 merged: 2025-05-25 17:48:31

183. [48147](http://github.com/cms-sw/cmssw/pull/48147){:target="_blank"}  from **@tcuisset**: Fix SimTracksterSC pdgId in TICLDumper `reconstruction` `upgrade` created: 2025-05-22 11:38:33 merged: 2025-05-23 12:55:13

184. [48145](http://github.com/cms-sw/cmssw/pull/48145){:target="_blank"}  from **@eigen1907**: Revert RPC Endcap Disk4 rotation - for Run 4 Scenario with 2030/v6/rpcf.xml  `geometry` created: 2025-05-22 04:32:44 merged: 2025-05-23 12:55:53

185. [48144](http://github.com/cms-sw/cmssw/pull/48144){:target="_blank"}  from **@bsunanda**: Phase2-hgx363AM Update several test scripts in Geometry/HGCalCommonData/test/python `geometry` `upgrade` created: 2025-05-22 03:54:22 merged: 2025-05-22 07:11:26

186. [48143](http://github.com/cms-sw/cmssw/pull/48143){:target="_blank"}  from **@Dr15Jones**: Static analysis fixes for FWCore `core` created: 2025-05-21 21:40:05 merged: 2025-05-23 12:54:28

187. [48142](http://github.com/cms-sw/cmssw/pull/48142){:target="_blank"}  from **@missirol**: use BX info in L1-uGT emulation of CICADA conditions `l1` created: 2025-05-21 19:24:52 merged: 2025-05-24 08:18:05

188. [48140](http://github.com/cms-sw/cmssw/pull/48140){:target="_blank"}  from **@Dr15Jones**: Removed const_cast in DataKey `core` created: 2025-05-21 18:26:37 merged: 2025-05-22 07:14:40

189. [48139](http://github.com/cms-sw/cmssw/pull/48139){:target="_blank"}  from **@Dr15Jones**: Fix static assert warning in TimingServiceBase `core` created: 2025-05-21 18:00:33 merged: 2025-05-22 07:13:55

190. [48138](http://github.com/cms-sw/cmssw/pull/48138){:target="_blank"}  from **@Dr15Jones**: Simplified helpers for edmNew::DetSetVector `core` created: 2025-05-21 16:01:27 merged: 2025-05-22 07:13:02

191. [48137](http://github.com/cms-sw/cmssw/pull/48137){:target="_blank"}  from **@CMS-HGCAL**: [HGCAL] Clean HGCal configuration & calibration `alca` `reconstruction` `db` `upgrade` `heterogeneous` created: 2025-05-21 15:06:07 merged: 2025-05-25 17:47:28

192. [48133](http://github.com/cms-sw/cmssw/pull/48133){:target="_blank"}  from **@fwyzard**: Improve SoA out-of-bounds error message `heterogeneous` created: 2025-05-21 07:50:11 merged: 2025-05-28 14:08:54

193. [48132](http://github.com/cms-sw/cmssw/pull/48132){:target="_blank"}  from **@bsunanda**: Phase2-hgx363AL Make a v19 version where the cell structure is made only in the SIM step while making hits `geometry` `upgrade` created: 2025-05-21 03:48:50 merged: 2025-05-21 08:09:50

194. [48129](http://github.com/cms-sw/cmssw/pull/48129){:target="_blank"}  from **@fwyzard**: conddb2hdf5: add option to restrict IOVs to a single run `db` created: 2025-05-20 17:07:08 merged: 2025-05-31 10:59:35

195. [48127](http://github.com/cms-sw/cmssw/pull/48127){:target="_blank"}  from **@smuzaffar**: [UBSAN][GCC14]move large constructor code in to private member function `alca` created: 2025-05-20 14:39:08 merged: 2025-05-22 07:12:11

196. [48125](http://github.com/cms-sw/cmssw/pull/48125){:target="_blank"}  from **@Dr15Jones**: Release principals in TestSourceProcessor `core` created: 2025-05-20 14:04:49 merged: 2025-05-21 08:10:12

197. [48123](http://github.com/cms-sw/cmssw/pull/48123){:target="_blank"}  from **@mmusich**: Geometry/TrackerGeometryBuilder/README.md: fix `subDetId` typo `geometry` `trk` created: 2025-05-20 13:28:17 merged: 2025-05-22 08:22:39

198. [48122](http://github.com/cms-sw/cmssw/pull/48122){:target="_blank"}  from **@JHiltbrand**: Fix AlCaHcalIsoTrk_Run3 Scenario Impl `operations` created: 2025-05-20 12:20:52 merged: 2025-05-27 15:10:33

199. [48121](http://github.com/cms-sw/cmssw/pull/48121){:target="_blank"}  from **@asavincms**: [L1T] Calo trigger Zero Suppression at Layer1 included in Online producer `l1` created: 2025-05-20 10:12:57 merged: 2025-05-20 15:07:58

200. [48120](http://github.com/cms-sw/cmssw/pull/48120){:target="_blank"}  from **@rseidita**: Updating Online DQM Info client to correctly display beam energy status `dqm` created: 2025-05-20 09:06:09 merged: 2025-05-23 12:56:41

201. [48118](http://github.com/cms-sw/cmssw/pull/48118){:target="_blank"}  from **@bsunanda**: Phase2-hgx363AK Remove the overlaps in the Phase2 scenarios D111, D112, D113 due to tracker subscenarios T16, T37 and T38 `geometry` `upgrade` `trk` created: 2025-05-19 09:15:20 merged: 2025-05-21 03:38:05

202. [48115](http://github.com/cms-sw/cmssw/pull/48115){:target="_blank"}  from **@gpetruc**: Fix SoftMuonMvaRun3Estimator for NaN chi2 (PromptReco issue) `reconstruction` `xpog` created: 2025-05-18 16:14:09 merged: 2025-05-20 17:57:35

203. [48114](http://github.com/cms-sw/cmssw/pull/48114){:target="_blank"}  from **@cms-ngt-hlt**: Fixes for HGCal validation at HLT `dqm` `operations` `simulation` `pdmv` `upgrade` created: 2025-05-18 15:34:56 merged: 2025-05-28 05:35:35

204. [48113](http://github.com/cms-sw/cmssw/pull/48113){:target="_blank"}  from **@bsunanda**: Phase2-hgx363AJ Correct the *SensorSeparation* to 2mm and modify the list of tiles with modified IR to avoid overlaps `geometry` `upgrade` created: 2025-05-18 13:12:43 merged: 2025-05-20 05:32:40

205. [48112](http://github.com/cms-sw/cmssw/pull/48112){:target="_blank"}  from **@stahlleiton**: Fix missing towerMaker collection in AOD in Run3_2025_OXY eras `reconstruction` created: 2025-05-17 15:14:53 merged: 2025-05-20 05:32:45

206. [48111](http://github.com/cms-sw/cmssw/pull/48111){:target="_blank"}  from **@mmusich**: Improve `BeamSpotCompatibilityChecker` and its usage in `Alignment/OfflineValidation` `alca` `dqm` `reconstruction` `db` `tracking` `trk` created: 2025-05-17 11:48:29 merged: 2025-05-23 12:54:53

207. [48108](http://github.com/cms-sw/cmssw/pull/48108){:target="_blank"}  from **@bsunanda**: Phase2-hgx363AI Remove some of the overlaps in the ETL versions in v9 and v10 `geometry` `upgrade` created: 2025-05-16 16:31:40 merged: 2025-05-17 17:33:47

208. [48104](http://github.com/cms-sw/cmssw/pull/48104){:target="_blank"}  from **@hqucms**: NanoAODv15-Lite setup for Run2UL and 2022/2023 `operations` `reconstruction` `xpog` created: 2025-05-16 10:04:25 merged: 2025-06-05 07:33:12

209. [48103](http://github.com/cms-sw/cmssw/pull/48103){:target="_blank"}  from **@fwyzard**: Mark SoA element constructor `constexpr` `heterogeneous` created: 2025-05-16 08:51:29 merged: 2025-05-17 17:31:19

210. [48102](http://github.com/cms-sw/cmssw/pull/48102){:target="_blank"}  from **@fabferro**: PPS 2025 Reconstruction geometry BUG FIX `geometry` created: 2025-05-16 07:59:09 merged: 2025-05-17 17:32:54

211. [48101](http://github.com/cms-sw/cmssw/pull/48101){:target="_blank"}  from **@ashleyahram**: update an estimate vertex smearing parameters for 2025 OO MC `operations` `simulation` created: 2025-05-16 07:33:28 merged: 2025-05-17 17:33:21

212. [48099](http://github.com/cms-sw/cmssw/pull/48099){:target="_blank"}  from **@bsunanda**: Phase2-hgx363AH Allow overlap checks for HGCal scenarios from V16 till V19 with the dd4hep definition `geometry` `upgrade` created: 2025-05-16 04:32:48 merged: 2025-05-17 17:31:07

213. [48098](http://github.com/cms-sw/cmssw/pull/48098){:target="_blank"}  from **@kpedro88**: add hybrid pileup workflows `pdmv` `upgrade` created: 2025-05-15 23:58:17 merged: 2025-06-02 20:18:41

214. [48097](http://github.com/cms-sw/cmssw/pull/48097){:target="_blank"}  from **@Dr15Jones**: fix code-checks in ProductProvenanceLookup `core` created: 2025-05-15 20:48:54 merged: 2025-05-17 17:32:42

215. [48096](http://github.com/cms-sw/cmssw/pull/48096){:target="_blank"}  from **@Dr15Jones**: fix axes in edmStreamStallGrapher `core` created: 2025-05-15 18:07:46 merged: 2025-05-17 17:33:02

216. [48095](http://github.com/cms-sw/cmssw/pull/48095){:target="_blank"}  from **@bsunanda**: Phse2-hgx363AAG Update the directory names of several scenarios defined in Geometry/MuoncommonDta `geometry` created: 2025-05-15 17:04:39 merged: 2025-05-17 17:34:52

217. [48094](http://github.com/cms-sw/cmssw/pull/48094){:target="_blank"}  from **@bsunanda**: Phase2-hgx363AAF Update the directory names of several scenarios defined in Geometry/HcalAlgo and Geometry/HcalcommonData `geometry` created: 2025-05-15 16:51:52 merged: 2025-05-17 17:34:27

218. [48092](http://github.com/cms-sw/cmssw/pull/48092){:target="_blank"}  from **@bsunanda**: Phase2-hgx363AAE Update the directory names of several scenarios defined in Geometry/CMSCommonData and Geometry/HGCalCommonData `geometry` `upgrade` created: 2025-05-15 16:29:18 merged: 2025-05-17 17:32:31

219. [48091](http://github.com/cms-sw/cmssw/pull/48091){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Introduce NanoAOD flavour for Phase 2 HLT `hlt` `reconstruction` `pdmv` `upgrade` `xpog` created: 2025-05-15 16:23:22 merged: 2025-06-04 07:39:45

220. [48088](http://github.com/cms-sw/cmssw/pull/48088){:target="_blank"}  from **@Dr15Jones**: Allow use of TTree::GetEntry in PoolSource `core` created: 2025-05-15 13:46:20 merged: 2025-05-22 07:15:04

221. [48087](http://github.com/cms-sw/cmssw/pull/48087){:target="_blank"}  from **@cms-ngt-hlt**: Updates to the NGT DQM Scouting instance and introducing new NGT DQM scouting online client `dqm` `hlt` created: 2025-05-15 13:05:32 merged: 2025-05-23 12:56:30

222. [48086](http://github.com/cms-sw/cmssw/pull/48086){:target="_blank"}  from **@mmusich**: add monitoring for `TkAlHLTTracks` and `TkAlHLTTracksZMuMu` track collections `alca` `dqm` `operations` created: 2025-05-15 07:25:46 merged: 2025-05-20 05:34:06

223. [48076](http://github.com/cms-sw/cmssw/pull/48076){:target="_blank"}  from **@mmusich**: Introduce `ph2_hlt` predefined workflow list `pdmv` `upgrade` created: 2025-05-14 08:44:03 merged: 2025-05-17 17:32:02

224. [48074](http://github.com/cms-sw/cmssw/pull/48074){:target="_blank"}  from **@mmusich**: Alignment Validation: fix `GeneralPurposeVertexAnalyzer` configuration `alca` `dqm` `tracking` `trk` created: 2025-05-14 07:15:41 merged: 2025-05-20 05:33:35

225. [48073](http://github.com/cms-sw/cmssw/pull/48073){:target="_blank"}  from **@makortel**: Add storage tracer `core` created: 2025-05-13 20:31:35 merged: 2025-05-17 17:30:34

226. [48055](http://github.com/cms-sw/cmssw/pull/48055){:target="_blank"}  from **@missirol**: use unpacked HCAL TPs for L1T-ZDC sums in `L1TReEmulFromRAW` `l1` created: 2025-05-11 21:55:39 merged: 2025-05-19 07:38:11

227. [48045](http://github.com/cms-sw/cmssw/pull/48045){:target="_blank"}  from **@missirol**: use unpacked track-finder inputs for kBMTF in `L1REPACK:Full` `l1` `operations` created: 2025-05-08 22:31:01 merged: 2025-05-19 07:36:39

228. [48041](http://github.com/cms-sw/cmssw/pull/48041){:target="_blank"}  from **@iarspider**: Silence Wdangling-reference in RecoLocalCalo/EcalRecProducers alpaka plugin `reconstruction` created: 2025-05-08 16:21:00 merged: 2025-05-21 08:10:05

229. [48037](http://github.com/cms-sw/cmssw/pull/48037){:target="_blank"}  from **@aloeliger**: Take uGT DQM emulation CICADA from unpacked `dqm` created: 2025-05-08 14:57:19 merged: 2025-05-20 05:33:05

230. [48002](http://github.com/cms-sw/cmssw/pull/48002){:target="_blank"}  from **@cerminar**: [L1T] Restructure handling of Calorimeter input to Correlator Layer-1 + new TkElectrons in barrel (Phase-2) `l1` `upgrade` created: 2025-05-02 16:05:20 merged: 2025-06-18 07:46:29

231. [47994](http://github.com/cms-sw/cmssw/pull/47994){:target="_blank"}  from **@fwyzard**: Remove the use of deprecated MPI C++ bindings `generators` `heterogeneous` created: 2025-04-30 18:15:47 merged: 2025-05-17 17:29:57

232. [47993](http://github.com/cms-sw/cmssw/pull/47993){:target="_blank"}  from **@Dongwoon77**: Update for Masked VFAT plots on GEM onlineDQM `dqm` created: 2025-04-30 15:52:49 merged: 2025-05-31 10:59:20

233. [47859](http://github.com/cms-sw/cmssw/pull/47859){:target="_blank"}  from **@brusale**: TICL-barrel: run CLUE in the barrel calorimeters and first workflows `generators` `dqm` `hlt` `operations` `reconstruction` `simulation` `pdmv` `upgrade` created: 2025-04-13 14:40:59 merged: 2025-07-08 15:17:45

234. [47829](http://github.com/cms-sw/cmssw/pull/47829){:target="_blank"}  from **@RSalvatico**: Add treatment of HGCAL calibration and surrounding cells `alca` `geometry` `reconstruction` `db` `upgrade` `heterogeneous` created: 2025-04-09 14:31:53 merged: 2025-05-17 17:29:12

235. [47728](http://github.com/cms-sw/cmssw/pull/47728){:target="_blank"}  from **@dan131riley**: fixes for vector size handling and spurious wakeups in TimeStudyModules `core` created: 2025-03-28 17:21:06 merged: 2025-06-05 07:32:54

236. [47611](http://github.com/cms-sw/cmssw/pull/47611){:target="_blank"}  from **@AdrianoDee**: A More Flexible And Lightweight CA `dqm` `geometry` `hlt` `reconstruction` `heterogeneous` `tracking` `trk` created: 2025-03-17 12:32:30 merged: 2025-07-01 16:40:31

237. [47067](http://github.com/cms-sw/cmssw/pull/47067){:target="_blank"}  from **@cms-L1TK**: L1 tracking update `core` `l1` `operations` `simulation` `upgrade` `trk` created: 2025-01-09 14:59:59 merged: 2025-06-01 10:40:44

#### CMSDIST Changes between Tags REL/CMSSW_15_1_0_pre3_FASTPU/el8_amd64_gcc12 and REL/CMSSW_15_1_0_pre4_FASTPU/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_15_1_0_pre3_FASTPU/el8_amd64_gcc12...REL/CMSSW_15_1_0_pre4_FASTPU/el8_amd64_gcc12)



1. [9964](http://github.com/cms-sw/cmsdist/pull/9964){:target="_blank"}  from **@cms-sw**: cms-common: Added cmsTraceFunction created: 2025-07-07 14:21:28 merged: 2025-07-07 14:52:58

2. [9961](http://github.com/cms-sw/cmsdist/pull/9961){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1TCalorimeter to V01-06-00 created: 2025-07-06 17:40:11 merged: 2025-07-06 17:40:13

3. [9958](http://github.com/cms-sw/cmsdist/pull/9958){:target="_blank"}  from **@cms-sw**: Update tag for DQM-Integration to V00-10-00 created: 2025-07-01 09:00:57 merged: 2025-07-01 09:00:59

4. [9948](http://github.com/cms-sw/cmsdist/pull/9948){:target="_blank"}  from **@clelange**: Update cms-cat.spec target commit created: 2025-06-27 09:20:40 merged: 2025-06-27 12:27:38

5. [9946](http://github.com/cms-sw/cmsdist/pull/9946){:target="_blank"}  from **@cms-sw**: Update tag for GeneratorInterface-EvtGenInterface to V02-12-00 created: 2025-06-27 07:38:58 merged: 2025-06-27 07:39:00

6. [9942](http://github.com/cms-sw/cmsdist/pull/9942){:target="_blank"}  from **@cms-sw**: update urllib3 to version 2.5.0 which contains security fixes created: 2025-06-24 13:22:05 merged: 2025-06-24 20:06:28

7. [9941](http://github.com/cms-sw/cmsdist/pull/9941){:target="_blank"}  from **@Annnnya**: changed dependency of hdf5 and sherpa to more general mpi.xml created: 2025-06-23 13:06:54 merged: 2025-06-24 07:09:55

8. [9936](http://github.com/cms-sw/cmsdist/pull/9936){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-Phase2L1ParticleFlow to V00-08-00 created: 2025-06-18 07:46:34 merged: 2025-06-18 07:46:36

9. [9935](http://github.com/cms-sw/cmsdist/pull/9935){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-18-00 created: 2025-06-18 07:16:55 merged: 2025-06-18 07:16:57

10. [9934](http://github.com/cms-sw/cmsdist/pull/9934){:target="_blank"}  from **@cms-sw**: make sure to download unique wheel for each arch created: 2025-06-18 07:06:59 merged: 2025-06-18 08:13:35

11. [9929](http://github.com/cms-sw/cmsdist/pull/9929){:target="_blank"}  from **@cms-sw**: Update of python packages created: 2025-06-15 13:19:57 merged: 2025-06-17 07:59:27

12. [9927](http://github.com/cms-sw/cmsdist/pull/9927){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-MkFit to V00-17-00 created: 2025-06-13 06:59:25 merged: 2025-06-13 06:59:27

13. [9921](http://github.com/cms-sw/cmsdist/pull/9921){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1TTrackMatch to V00-03-00 created: 2025-06-10 13:46:27 merged: 2025-06-10 13:46:28

14. [9919](http://github.com/cms-sw/cmsdist/pull/9919){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-VertexFinder to V00-02-00 created: 2025-06-10 13:34:05 merged: 2025-06-10 13:34:07

15. [9918](http://github.com/cms-sw/cmsdist/pull/9918){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-31-00 created: 2025-06-10 13:32:41 merged: 2025-06-10 13:32:43

16. [9916](http://github.com/cms-sw/cmsdist/pull/9916){:target="_blank"}  from **@sinonkt**: Update crab client to v3.250522 in prod IB created: 2025-06-06 12:21:42 merged: 2025-06-09 07:58:48

17. [9904](http://github.com/cms-sw/cmsdist/pull/9904){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-HGCalMapping to V00-02-00 created: 2025-06-02 08:28:23 merged: 2025-06-02 08:28:25

18. [9900](http://github.com/cms-sw/cmsdist/pull/9900){:target="_blank"}  from **@cms-sw**: BuildRules: Explicitly add gcc-toolchain in compile_commands.json created: 2025-05-30 10:28:26 merged: 2025-05-30 11:12:43

19. [9898](http://github.com/cms-sw/cmsdist/pull/9898){:target="_blank"}  from **@thesps**: Bump conifer to 1.7 created: 2025-05-28 16:02:25 merged: 2025-05-29 10:21:51

20. [9896](http://github.com/cms-sw/cmsdist/pull/9896){:target="_blank"}  from **@cms-sw**: created clang++.cfg and clang.cfg files and dropped --gcc-toolchain from toolfile created: 2025-05-28 12:57:23 merged: 2025-05-29 10:17:00

21. [9895](http://github.com/cms-sw/cmsdist/pull/9895){:target="_blank"}  from **@cms-sw**: ROCM: do not set --gcc-toolchain/--target via toolfile created: 2025-05-28 09:04:44 merged: 2025-05-28 15:19:05

22. [9894](http://github.com/cms-sw/cmsdist/pull/9894){:target="_blank"}  from **@cms-sw**: BuildRules: add libresolv in LD_PRELOAD for unit tests created: 2025-05-28 08:04:25 merged: 2025-05-28 21:58:37

23. [9893](http://github.com/cms-sw/cmsdist/pull/9893){:target="_blank"}  from **@cms-sw**: ROCM: set HIP_PATH and created clang++.cfg to provide gcc-toolchain and target created: 2025-05-27 13:23:55 merged: 2025-05-27 22:01:26

24. [9892](http://github.com/cms-sw/cmsdist/pull/9892){:target="_blank"}  from **@cms-sw**: Update python packages created: 2025-05-26 15:32:28 merged: 2025-05-27 08:11:18

25. [9891](http://github.com/cms-sw/cmsdist/pull/9891){:target="_blank"}  from **@cms-sw**: Added tool to link resolv system lib created: 2025-05-26 13:19:55 merged: 2025-05-26 14:38:12

26. [9889](http://github.com/cms-sw/cmsdist/pull/9889){:target="_blank"}  from **@smuzaffar**: Updated root to tip of branch v6-32-00-patches created: 2025-05-26 08:57:37 merged: 2025-05-27 08:13:44

27. [9886](http://github.com/cms-sw/cmsdist/pull/9886){:target="_blank"}  from **@belforte**: Update crab-dev.spec to latest tag created: 2025-05-22 14:58:38 merged: 2025-05-22 17:43:30

28. [9884](http://github.com/cms-sw/cmsdist/pull/9884){:target="_blank"}  from **@cms-sw**: cms-common: Update scram project hook to look for system cuda too created: 2025-05-22 09:48:23 merged: 2025-05-22 17:40:44

29. [9883](http://github.com/cms-sw/cmsdist/pull/9883){:target="_blank"}  from **@cms-sw**: Disabled alpaka-cuda backend if nvcc is not accessible created: 2025-05-21 14:22:00 merged: 2025-05-22 06:02:50

30. [9877](http://github.com/cms-sw/cmsdist/pull/9877){:target="_blank"}  from **@smuzaffar**: Updated root to tip of branch v6-32-00-patches for 15.1.X default IBs created: 2025-05-20 17:25:16 merged: 2025-05-21 06:50:48

31. [9876](http://github.com/cms-sw/cmsdist/pull/9876){:target="_blank"}  from **@cms-sw**: Rivet: disable ONNX dependency created: 2025-05-20 16:26:02 merged: 2025-05-22 16:38:29

32. [9856](http://github.com/cms-sw/cmsdist/pull/9856){:target="_blank"}  from **@fwyzard**: Update CUDA to version 12.9.0 and cuDNN to version 9.9.0 created: 2025-05-13 09:53:32 merged: 2025-05-17 07:24:00

33. [9845](http://github.com/cms-sw/cmsdist/pull/9845){:target="_blank"}  from **@fwyzard**: Add MPICH v4.3 and a generic MPI tool created: 2025-05-10 13:20:57 merged: 2025-05-26 15:22:32
