---
layout: post
rel_link:  "7_6_0_pre4"
title:  "CMSSW_7_6_0_pre4"
date:   2015-08-28 07:08:17
categories: cmssw
relmajor: 7
relminor: 6
relsubminor: 0
relpre: _pre4
---

# CMSSW_7_6_0_pre4
#### Changes since CMSSW_7_6_0_pre3:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_6_0_pre3...CMSSW_7_6_0_pre4)



1. [10936](http://github.com/cms-sw/cmssw/pull/10936){:target="_blank"}  from **@fwyzard**: migrate RPCPointProducer to a global::EDProducer (76x) `dqm`  `hlt`  `reconstruction`  created: 2015-08-25 01:16:02 merged: 2015-08-28 06:56:42

2. [10941](http://github.com/cms-sw/cmssw/pull/10941){:target="_blank"}  from **@dmitrijus**: Fix DQM/PhysicsHWW by just ignoring jets with invalid parameters (76x) `dqm`  created: 2015-08-25 17:10:30 merged: 2015-08-28 06:55:41

3. [10922](http://github.com/cms-sw/cmssw/pull/10922){:target="_blank"}  from **@lveldere**: use fastSim era to apply FastSim mods on TrackValidation_cff `dqm`  `fastsim`  `operations`  `simulation`  created: 2015-08-24 12:43:50 merged: 2015-08-27 09:22:41

4. [10945](http://github.com/cms-sw/cmssw/pull/10945){:target="_blank"}  from **@ianna**: Roll Back Changes to Production Geometry `geometry`  created: 2015-08-26 06:40:38 merged: 2015-08-27 09:17:56

5. [10957](http://github.com/cms-sw/cmssw/pull/10957){:target="_blank"}  from **@fwyzard**: migrate to modules used by the HLT menu multithreading (AlCa) `alca`  created: 2015-08-26 15:37:14 merged: 2015-08-27 09:16:07

6. [10950](http://github.com/cms-sw/cmssw/pull/10950){:target="_blank"}  from **@Dr15Jones**: Fixed include guard in ESUnpacker.h `reconstruction`  created: 2015-08-26 14:30:28 merged: 2015-08-27 09:15:45

7. [10949](http://github.com/cms-sw/cmssw/pull/10949){:target="_blank"}  from **@Dr15Jones**: Missed a needed T*::Fit change for thread safety `dqm`  created: 2015-08-26 13:58:55 merged: 2015-08-27 06:44:06

8. [10952](http://github.com/cms-sw/cmssw/pull/10952){:target="_blank"}  from **@echapon**: New steps for HI muon RegIt `reconstruction`  created: 2015-08-26 15:10:39 merged: 2015-08-27 06:43:02

9. [10954](http://github.com/cms-sw/cmssw/pull/10954){:target="_blank"}  from **@fwyzard**: migrate to modules used by the HLT menu multithreading (Reco) `reconstruction`  created: 2015-08-26 15:35:27 merged: 2015-08-27 06:42:34

10. [10648](http://github.com/cms-sw/cmssw/pull/10648){:target="_blank"}  from **@bbockelm**: Fix python2.6 SyntaxError. `core`  created: 2015-08-09 16:07:21 merged: 2015-08-27 06:41:12

11. [10890](http://github.com/cms-sw/cmssw/pull/10890){:target="_blank"}  from **@ANSH0712**: FastSim Tracking without sim info `fastsim`  created: 2015-08-20 18:11:04 merged: 2015-08-27 06:41:00

12. [10955](http://github.com/cms-sw/cmssw/pull/10955){:target="_blank"}  from **@fwyzard**: migrate to modules used by the HLT menu multithreading (HLT) `hlt`  created: 2015-08-26 15:36:26 merged: 2015-08-27 06:37:58

13. [10959](http://github.com/cms-sw/cmssw/pull/10959){:target="_blank"}  from **@gartung**: Fix for warning from clang static analyzer. `reconstruction`  created: 2015-08-26 18:31:22 merged: 2015-08-27 06:37:46

14. [10938](http://github.com/cms-sw/cmssw/pull/10938){:target="_blank"}  from **@duanders**: Update hotline skim sequences and cuts `alca`  created: 2015-08-25 10:35:58 merged: 2015-08-26 20:44:47

15. [10877](http://github.com/cms-sw/cmssw/pull/10877){:target="_blank"}  from **@MarkBaber**: CMSSW_7_6_X DQM updates for AlphaT HLT paths (v2) `dqm`  created: 2015-08-20 11:06:18 merged: 2015-08-26 06:08:48

16. [10914](http://github.com/cms-sw/cmssw/pull/10914){:target="_blank"}  from **@Martin-Grunewald**: Fix DQM py files for ConfDB parsing (76X) `dqm`  created: 2015-08-24 08:43:38 merged: 2015-08-26 06:01:53

17. [10485](http://github.com/cms-sw/cmssw/pull/10485){:target="_blank"}  from **@pietverwilligen**: Gem segment 76 `reconstruction`  `simulation`  created: 2015-07-30 17:08:07 merged: 2015-08-26 05:57:54

18. [10775](http://github.com/cms-sw/cmssw/pull/10775){:target="_blank"}  from **@dgulhan**: Pixel cluster splitting and jet core iteration for HI Tracking `operations`  `reconstruction`  created: 2015-08-14 11:46:33 merged: 2015-08-26 05:56:55

19. [10874](http://github.com/cms-sw/cmssw/pull/10874){:target="_blank"}  from **@hengne**: Add back a workflow removed by accident in commit 14bf693 `pdmv`  created: 2015-08-20 10:41:37 merged: 2015-08-26 05:56:18

20. [10905](http://github.com/cms-sw/cmssw/pull/10905){:target="_blank"}  from **@mbandrews**: forcing EE qT to be always true `dqm`  created: 2015-08-21 14:36:32 merged: 2015-08-25 06:31:12

21. [10805](http://github.com/cms-sw/cmssw/pull/10805){:target="_blank"}  from **@cms-tau-pog**: Dynamic strip reco v4 `analysis`  `reconstruction`  created: 2015-08-16 13:29:50 merged: 2015-08-25 06:26:50

22. [10871](http://github.com/cms-sw/cmssw/pull/10871){:target="_blank"}  from **@archiron**: Electron Validation : modification of scl_EoEtrueVsrecOfflineVertices histo `dqm`  created: 2015-08-20 07:29:01 merged: 2015-08-25 06:26:39

23. [10921](http://github.com/cms-sw/cmssw/pull/10921){:target="_blank"}  from **@lgray**: Change photon & electron regressions back to fractionized shower shapes  `reconstruction`  created: 2015-08-24 11:39:45 merged: 2015-08-25 06:26:13

24. [10930](http://github.com/cms-sw/cmssw/pull/10930){:target="_blank"}  from **@cmkuo**: fix a bug for the number of good ES rechits `dqm`  created: 2015-08-24 19:45:23 merged: 2015-08-25 06:21:09

25. [10811](http://github.com/cms-sw/cmssw/pull/10811){:target="_blank"}  from **@KiSooLee**: HLT BPTX path for HI added `dqm`  created: 2015-08-17 08:24:30 merged: 2015-08-24 17:31:50

26. [10837](http://github.com/cms-sw/cmssw/pull/10837){:target="_blank"}  from **@davidlt**: condformats_serialization_generate.py: fix include paths and fail on serious issues `db`  created: 2015-08-18 11:26:09 merged: 2015-08-24 17:26:49

27. [10838](http://github.com/cms-sw/cmssw/pull/10838){:target="_blank"}  from **@yetkinyilmaz**: Option for DAS query in ConfigBuilder 76X `operations`  created: 2015-08-18 11:56:25 merged: 2015-08-24 06:12:38

28. [10689](http://github.com/cms-sw/cmssw/pull/10689){:target="_blank"}  from **@lgray**: Modifier to apply energy corrections to photons and electrons (miniAOD) for 76X `analysis`  `reconstruction`  created: 2015-08-11 14:38:35 merged: 2015-08-24 06:06:05

29. [10850](http://github.com/cms-sw/cmssw/pull/10850){:target="_blank"}  from **@kkotov**: Adding CaloParams and CaloConfig types to CondDB `db`  created: 2015-08-19 09:54:25 merged: 2015-08-24 06:04:02

30. [10908](http://github.com/cms-sw/cmssw/pull/10908){:target="_blank"}  from **@davidlange6**: physicstools unit test removed `analysis`  created: 2015-08-23 05:56:49 merged: 2015-08-23 06:02:48

31. [10860](http://github.com/cms-sw/cmssw/pull/10860){:target="_blank"}  from **@davidlt**: SiStripRecHitMatcher.h: remove non-POD VLA `reconstruction`  created: 2015-08-19 19:19:35 merged: 2015-08-23 05:53:31

32. [10900](http://github.com/cms-sw/cmssw/pull/10900){:target="_blank"}  from **@mojoe137**: fix trigger feeding the pixel lumi dqm to match the VdM menu `dqm`  created: 2015-08-21 12:54:19 merged: 2015-08-23 05:53:15

33. [10897](http://github.com/cms-sw/cmssw/pull/10897){:target="_blank"}  from **@gpetruc**: FWLite MultiChainEvent: avoid crash on empty files (76X) `core`  created: 2015-08-21 10:30:18 merged: 2015-08-22 06:08:02

34. [10708](http://github.com/cms-sw/cmssw/pull/10708){:target="_blank"}  from **@makortel**: Migrate bunch of tracking related modules to one/stream/global `dqm`  `reconstruction`  `simulation`  created: 2015-08-12 07:28:16 merged: 2015-08-21 08:32:16

35. [10859](http://github.com/cms-sw/cmssw/pull/10859){:target="_blank"}  from **@davidlt**: DQM/PixelLumi: definite static const int members `dqm`  created: 2015-08-19 19:06:42 merged: 2015-08-21 08:31:55

36. [10187](http://github.com/cms-sw/cmssw/pull/10187){:target="_blank"}  from **@mark-grimes**: Updates the Run2 era to match recent changes in the customisations `fastsim`  `l1`  created: 2015-07-14 09:19:07 merged: 2015-08-21 08:31:13

37. [10172](http://github.com/cms-sw/cmssw/pull/10172){:target="_blank"}  from **@mark-grimes**: Update Run 2 eras to match customisation functions `operations`  created: 2015-07-13 16:00:52 merged: 2015-08-21 08:30:35

38. [10197](http://github.com/cms-sw/cmssw/pull/10197){:target="_blank"}  from **@jpata**: Combined MVA computer based on TMVA (CombinedMVAV2) `analysis`  `reconstruction`  created: 2015-07-14 14:52:16 merged: 2015-08-21 08:30:12

39. [10889](http://github.com/cms-sw/cmssw/pull/10889){:target="_blank"}  from **@wmtan**: Move parentage code out of the OutputModule base class `core`  created: 2015-08-20 16:52:54 merged: 2015-08-21 08:27:29

40. [10840](http://github.com/cms-sw/cmssw/pull/10840){:target="_blank"}  from **@boudoul**: From760pre3relval `pdmv`  created: 2015-08-18 12:48:23 merged: 2015-08-20 09:01:32

41. [10625](http://github.com/cms-sw/cmssw/pull/10625){:target="_blank"}  from **@ahinzmann**: Cleanup duplicate pileup jet ID configurations `analysis`  `dqm`  `reconstruction`  created: 2015-08-07 12:30:54 merged: 2015-08-20 08:58:18

42. [10767](http://github.com/cms-sw/cmssw/pull/10767){:target="_blank"}  from **@apfeiffer1**: First version of a "unit-test" like regression test for conditions `db`  created: 2015-08-14 08:32:24 merged: 2015-08-20 08:57:19

43. [10783](http://github.com/cms-sw/cmssw/pull/10783){:target="_blank"}  from **@ahinzmann**: Adjust ak8 jet threshold in MiniAOD `analysis`  created: 2015-08-14 16:36:19 merged: 2015-08-20 08:56:57

44. [10848](http://github.com/cms-sw/cmssw/pull/10848){:target="_blank"}  from **@dmitrijus**: Update Scal (Online DQM) configuration to work with our new setup (76x) `dqm`  created: 2015-08-19 08:29:05 merged: 2015-08-20 05:51:12

45. [10601](http://github.com/cms-sw/cmssw/pull/10601){:target="_blank"}  from **@cschomak**: APE tool implemented `alca`  created: 2015-08-06 07:35:21 merged: 2015-08-20 05:48:13

46. [10818](http://github.com/cms-sw/cmssw/pull/10818){:target="_blank"}  from **@mmarionncern**: Fix of the 76X recoMET tests `reconstruction`  created: 2015-08-17 10:45:47 merged: 2015-08-20 05:47:01

47. [10825](http://github.com/cms-sw/cmssw/pull/10825){:target="_blank"}  from **@capalmer85**: Pcc ntupler 76x update v1 `reconstruction`  created: 2015-08-17 20:30:44 merged: 2015-08-20 05:46:55

48. [10843](http://github.com/cms-sw/cmssw/pull/10843){:target="_blank"}  from **@ggovi**: Improved handling of customized GT via toGet `alca`  `db`  created: 2015-08-18 15:02:48 merged: 2015-08-20 05:46:43

49. [10846](http://github.com/cms-sw/cmssw/pull/10846){:target="_blank"}  from **@ianna**: Replace Legacy EDAnalyzer with Thread-friendly in Geometry `geometry`  created: 2015-08-19 08:15:59 merged: 2015-08-20 05:46:37

50. [10856](http://github.com/cms-sw/cmssw/pull/10856){:target="_blank"}  from **@Dr15Jones**: Fix thread-safety issue with StreamerInputSource `core`  created: 2015-08-19 16:36:29 merged: 2015-08-20 05:46:22

51. [10869](http://github.com/cms-sw/cmssw/pull/10869){:target="_blank"}  from **@jhgoh**: Fix crash due to invalid track status 76X  `reconstruction`  created: 2015-08-20 03:37:26 merged: 2015-08-20 05:43:47

52. [10471](http://github.com/cms-sw/cmssw/pull/10471){:target="_blank"}  from **@apfeiffer1**: Update conddb tool to make a copy of a full GT `db`  created: 2015-07-30 08:38:34 merged: 2015-08-18 13:24:27

53. [10829](http://github.com/cms-sw/cmssw/pull/10829){:target="_blank"}  from **@slava77**: add dqmSeq option to the recoinator `operations`  created: 2015-08-17 23:51:48 merged: 2015-08-18 13:19:32

54. [10816](http://github.com/cms-sw/cmssw/pull/10816){:target="_blank"}  from **@covarell**: add lhe generic filter `generators`  created: 2015-08-17 09:38:17 merged: 2015-08-18 13:02:09

55. [10258](http://github.com/cms-sw/cmssw/pull/10258){:target="_blank"}  from **@duanders**: Data scouting classes and producers (76X) `hlt`  created: 2015-07-17 12:42:31 merged: 2015-08-18 08:41:29

56. [10819](http://github.com/cms-sw/cmssw/pull/10819){:target="_blank"}  from **@apfeiffer1**: Example of a payload-to-XML C++ plugin  `db`  created: 2015-08-17 12:44:22 merged: 2015-08-18 08:26:32

57. [10822](http://github.com/cms-sw/cmssw/pull/10822){:target="_blank"}  from **@ginnocen**: new methods for D filters `hlt`  created: 2015-08-17 18:51:44 merged: 2015-08-18 08:21:31

58. [10609](http://github.com/cms-sw/cmssw/pull/10609){:target="_blank"}  from **@schoef**: MET Filter update (port of #10604) `alca`  `analysis`  `reconstruction`  created: 2015-08-06 20:21:37 merged: 2015-08-18 08:18:35

59. [10706](http://github.com/cms-sw/cmssw/pull/10706){:target="_blank"}  from **@alberto-sanchez**: Fixing horrible typo. Also add a Log message for force decay and clea `generators`  created: 2015-08-12 00:13:39 merged: 2015-08-18 08:17:06

60. [10808](http://github.com/cms-sw/cmssw/pull/10808){:target="_blank"}  from **@smorovic**: metadata JSON files produced for empty lumisections in DAQ (76X) `daq`  `dqm`  `hlt`  `reconstruction`  created: 2015-08-16 17:16:21 merged: 2015-08-18 08:17:00

61. [10828](http://github.com/cms-sw/cmssw/pull/10828){:target="_blank"}  from **@fwyzard**: hltGetConfiguration: switch run:NNNNNN to use ConfDB v2 `hlt`  created: 2015-08-17 21:28:54 merged: 2015-08-18 08:16:32

62. [10296](http://github.com/cms-sw/cmssw/pull/10296){:target="_blank"}  from **@kfjack**: Update MuTauSkim_cff with new Tau POG Isolation from Ram `pdmv`  created: 2015-07-21 15:54:43 merged: 2015-08-17 17:32:12

63. [10531](http://github.com/cms-sw/cmssw/pull/10531){:target="_blank"}  from **@cms-tsg-storm**: HLT update for 25ns (76X) `alca`  `hlt`  created: 2015-08-03 16:04:18 merged: 2015-08-17 17:32:05

64. [10694](http://github.com/cms-sw/cmssw/pull/10694){:target="_blank"}  from **@mark-grimes**: Fix phase1TkCustoms for recent changes to defaults `simulation`  created: 2015-08-11 16:48:26 merged: 2015-08-17 17:24:25

65. [10791](http://github.com/cms-sw/cmssw/pull/10791){:target="_blank"}  from **@threus**: tiny update of occupancy script `dqm`  created: 2015-08-14 17:27:07 merged: 2015-08-17 08:04:10

66. [10626](http://github.com/cms-sw/cmssw/pull/10626){:target="_blank"}  from **@jgomez2**: HITRDQMupdate `dqm`  created: 2015-08-07 13:08:30 merged: 2015-08-16 19:31:47

67. [10718](http://github.com/cms-sw/cmssw/pull/10718){:target="_blank"}  from **@makortel**: MultiTrackValidator cleanup `dqm`  created: 2015-08-12 13:19:22 merged: 2015-08-16 19:31:41

68. [10688](http://github.com/cms-sw/cmssw/pull/10688){:target="_blank"}  from **@makortel**: Tracking HLT validation cleanup `dqm`  created: 2015-08-11 14:31:55 merged: 2015-08-16 19:27:06

69. [10766](http://github.com/cms-sw/cmssw/pull/10766){:target="_blank"}  from **@mmarionncern**: Update the default relval for the recoMET tests `reconstruction`  created: 2015-08-14 08:18:32 merged: 2015-08-16 19:26:54

70. [10801](http://github.com/cms-sw/cmssw/pull/10801){:target="_blank"}  from **@gouskos**: enable beam spot validation - emails notifications suppressed 76x `dqm`  created: 2015-08-15 16:02:30 merged: 2015-08-16 19:26:32

71. [10731](http://github.com/cms-sw/cmssw/pull/10731){:target="_blank"}  from **@Dr15Jones**: Fixed clang compiler warnings `analysis`  `reconstruction`  created: 2015-08-12 18:18:50 merged: 2015-08-16 19:25:11

72. [10529](http://github.com/cms-sw/cmssw/pull/10529){:target="_blank"}  from **@pablodecm**: Add combMVA to bTag DQM `dqm`  created: 2015-08-03 15:07:45 merged: 2015-08-15 08:37:05

73. [10542](http://github.com/cms-sw/cmssw/pull/10542){:target="_blank"}  from **@rappoccio**: Adjusting trigger paths for B2G DQM : 76x `dqm`  created: 2015-08-03 20:29:16 merged: 2015-08-15 08:37:00

74. [10700](http://github.com/cms-sw/cmssw/pull/10700){:target="_blank"}  from **@richard-cms**: Put GED photons into HI event content and DQM pathways `dqm`  `reconstruction`  created: 2015-08-11 19:26:35 merged: 2015-08-15 08:36:44

75. [10734](http://github.com/cms-sw/cmssw/pull/10734){:target="_blank"}  from **@ndaci**: Update paths. `dqm`  created: 2015-08-12 21:57:05 merged: 2015-08-15 08:36:25

76. [10773](http://github.com/cms-sw/cmssw/pull/10773){:target="_blank"}  from **@deguio**: add legacy module support for run and lumi based histograms `dqm`  created: 2015-08-14 11:43:34 merged: 2015-08-15 08:36:18

77. [10780](http://github.com/cms-sw/cmssw/pull/10780){:target="_blank"}  from **@MilanoBicocca-pix**: [BeamSpot] fit 1D projections of PV distribution to get initial values for 3D fit parameters `alca`  `reconstruction`  created: 2015-08-14 16:09:46 merged: 2015-08-15 08:36:13

78. [10794](http://github.com/cms-sw/cmssw/pull/10794){:target="_blank"}  from **@Dr15Jones**: Modernize GoodVetexFilter `pdmv`  created: 2015-08-14 19:17:30 merged: 2015-08-15 08:34:10

79. [10633](http://github.com/cms-sw/cmssw/pull/10633){:target="_blank"}  from **@fioriNTU**: PixelBarrelEfficiency76 `dqm`  created: 2015-08-07 16:55:07 merged: 2015-08-15 08:32:29

80. [10654](http://github.com/cms-sw/cmssw/pull/10654){:target="_blank"}  from **@echapon**: Run "high level muon reconstruction" for heavy ions `reconstruction`  created: 2015-08-10 15:22:08 merged: 2015-08-15 08:32:23

81. [10665](http://github.com/cms-sw/cmssw/pull/10665){:target="_blank"}  from **@cmkuo**: add low pt photons (10-14 GeV) to miniAOD for 76x `reconstruction`  created: 2015-08-10 21:38:27 merged: 2015-08-15 08:32:17

82. [10619](http://github.com/cms-sw/cmssw/pull/10619){:target="_blank"}  from **@lgray**: EGM IDs for MiniAOD Reprocessing (76X) `analysis`  `reconstruction`  created: 2015-08-07 00:59:02 merged: 2015-08-15 08:32:04

83. [10719](http://github.com/cms-sw/cmssw/pull/10719){:target="_blank"}  from **@prbbing**: Added new displacedJets paths `dqm`  created: 2015-08-12 14:47:01 merged: 2015-08-15 08:31:46

84. [10748](http://github.com/cms-sw/cmssw/pull/10748){:target="_blank"}  from **@lgray**: Move slimmedAddPileupInfo to miniAOD_customizeMC (76X) `analysis`  created: 2015-08-13 16:27:15 merged: 2015-08-15 08:31:40

85. [10769](http://github.com/cms-sw/cmssw/pull/10769){:target="_blank"}  from **@MilanoBicocca-pix**: [DQM/BeamMonitor] fix y-axis range to properly display d0-phi plot `dqm`  created: 2015-08-14 09:40:27 merged: 2015-08-15 08:31:34

86. [10793](http://github.com/cms-sw/cmssw/pull/10793){:target="_blank"}  from **@dmitrijus**: Fix online DQM configuration for visualization (76x) `dqm`  created: 2015-08-14 17:35:43 merged: 2015-08-15 08:31:16

87. [10795](http://github.com/cms-sw/cmssw/pull/10795){:target="_blank"}  from **@Dr15Jones**: Prefetch mayConsumes to avoid deadlocks `core`  created: 2015-08-14 20:46:07 merged: 2015-08-15 08:26:11

88. [10746](http://github.com/cms-sw/cmssw/pull/10746){:target="_blank"}  from **@alja**: 76x Fireworks: Fix clang error `visualization`  created: 2015-08-13 15:58:17 merged: 2015-08-14 08:26:35

89. [10334](http://github.com/cms-sw/cmssw/pull/10334){:target="_blank"}  from **@cvernier**: Hlt mvapuid recojet `reconstruction`  created: 2015-07-23 21:19:18 merged: 2015-08-14 07:21:45

90. [10707](http://github.com/cms-sw/cmssw/pull/10707){:target="_blank"}  from **@ANSH0712**: seed state back propagated to first rechit and then instead of sim in `fastsim`  created: 2015-08-12 06:27:54 merged: 2015-08-14 07:16:21

91. [10716](http://github.com/cms-sw/cmssw/pull/10716){:target="_blank"}  from **@dmitrijus**: Customisations and few fixes for online DQM (76x) `dqm`  `reconstruction`  created: 2015-08-12 10:09:00 merged: 2015-08-14 07:11:19

92. [10677](http://github.com/cms-sw/cmssw/pull/10677){:target="_blank"}  from **@davidlt**: CondFormats/MFObjects: use correct path for headers.h `alca`  created: 2015-08-11 11:32:53 merged: 2015-08-14 07:08:51

93. [10709](http://github.com/cms-sw/cmssw/pull/10709){:target="_blank"}  from **@fcavallo**: bug fix in OccupancyNoise `dqm`  created: 2015-08-12 08:48:33 merged: 2015-08-14 07:06:54

94. [10717](http://github.com/cms-sw/cmssw/pull/10717){:target="_blank"}  from **@ianna**: DD Core Cleanup `geometry`  created: 2015-08-12 12:58:46 merged: 2015-08-14 07:06:31

95. [10726](http://github.com/cms-sw/cmssw/pull/10726){:target="_blank"}  from **@dertexaner**: Fix r45Fraction_ calculation `reconstruction`  created: 2015-08-12 16:19:39 merged: 2015-08-14 07:01:26

96. [10742](http://github.com/cms-sw/cmssw/pull/10742){:target="_blank"}  from **@fwyzard**: fix location of ConfDB v2 .jar files `hlt`  created: 2015-08-13 12:46:35 merged: 2015-08-14 07:00:16

97. [10730](http://github.com/cms-sw/cmssw/pull/10730){:target="_blank"}  from **@ahinzmann**: Fix eta-dependent pileup jet ID `dqm`  `reconstruction`  created: 2015-08-12 16:58:25 merged: 2015-08-13 17:09:38

98. [10679](http://github.com/cms-sw/cmssw/pull/10679){:target="_blank"}  from **@makortel**: Fix MultiTrackValidator "doPlotsOnlyForTruePV" mode `dqm`  created: 2015-08-11 12:01:04 merged: 2015-08-13 08:51:18

99. [10543](http://github.com/cms-sw/cmssw/pull/10543){:target="_blank"}  from **@cms-btv-pog**: GBRForest in TMVAEvaluator + SoftLepton taggers using GBRForest `analysis`  `reconstruction`  created: 2015-08-04 04:29:34 merged: 2015-08-13 07:22:26

100. [10681](http://github.com/cms-sw/cmssw/pull/10681){:target="_blank"}  from **@prbbing**: Added HT Parking Paths `dqm`  created: 2015-08-11 13:15:12 merged: 2015-08-13 07:21:25

101. [10686](http://github.com/cms-sw/cmssw/pull/10686){:target="_blank"}  from **@muell149**: adding HLT object monitoring to HLT online DQM `dqm`  created: 2015-08-11 14:05:55 merged: 2015-08-13 07:21:17

102. [10661](http://github.com/cms-sw/cmssw/pull/10661){:target="_blank"}  from **@wddgit**: Make missing consumes calls an exception `alca`  `core`  `dqm`  created: 2015-08-10 20:16:28 merged: 2015-08-13 07:18:55

103. [10727](http://github.com/cms-sw/cmssw/pull/10727){:target="_blank"}  from **@slava77**: SimGeneralAOD doesn't belong in AODEventContent `operations`  created: 2015-08-12 16:32:28 merged: 2015-08-13 07:15:44

104. [10647](http://github.com/cms-sw/cmssw/pull/10647){:target="_blank"}  from **@bbockelm**: Send storage statistics to HTCondor. `core`  created: 2015-08-09 15:29:02 merged: 2015-08-12 07:06:42

105. [10655](http://github.com/cms-sw/cmssw/pull/10655){:target="_blank"}  from **@lathomas**: CSCHaloData kept in AOD `reconstruction`  created: 2015-08-10 16:27:26 merged: 2015-08-12 07:06:35

106. [10672](http://github.com/cms-sw/cmssw/pull/10672){:target="_blank"}  from **@lihux25**: Fix a crash "withTopo" issue  `alca`  created: 2015-08-11 04:45:39 merged: 2015-08-12 07:06:29

107. [10675](http://github.com/cms-sw/cmssw/pull/10675){:target="_blank"}  from **@ianna**: DD Cleanup `geometry`  created: 2015-08-11 09:59:02 merged: 2015-08-12 07:06:23

108. [10630](http://github.com/cms-sw/cmssw/pull/10630){:target="_blank"}  from **@dmitrijus**: Re-organize python configurations for the online DQM applications `dqm`  created: 2015-08-07 14:07:18 merged: 2015-08-12 07:03:12

109. [10699](http://github.com/cms-sw/cmssw/pull/10699){:target="_blank"}  from **@Dr15Jones**: Removed unused member data `visualization`  created: 2015-08-11 19:20:52 merged: 2015-08-12 07:01:09

110. [10472](http://github.com/cms-sw/cmssw/pull/10472){:target="_blank"}  from **@makortel**: Add efficiency and fake rate vs. dxy/dz wrt PV to MultiTrackValidator, and make normalization+cumulative histograms before efficiency in DQMGenericClient `dqm`  created: 2015-07-30 09:16:34 merged: 2015-08-10 20:07:08

111. [10332](http://github.com/cms-sw/cmssw/pull/10332){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hgx30 Try to add the reconstruction geometry and topology for HGCal `geometry`  created: 2015-07-23 20:11:10 merged: 2015-08-10 20:01:58

112. [10169](http://github.com/cms-sw/cmssw/pull/10169){:target="_blank"}  from **@cerminar**: RelVals for PCL (75X) `alca`  `pdmv`  created: 2015-07-13 14:34:10 merged: 2015-08-10 12:37:21

113. [10461](http://github.com/cms-sw/cmssw/pull/10461){:target="_blank"}  from **@mkirsano**: Use pythia8 EvtGen plugin in Pythia8Interface `generators`  created: 2015-07-29 21:24:59 merged: 2015-08-10 10:54:40

114. [10575](http://github.com/cms-sw/cmssw/pull/10575){:target="_blank"}  from **@ferencek**: Moving GBRForestWriter to CommonTools/Utils `analysis`  `reconstruction`  created: 2015-08-04 21:57:29 merged: 2015-08-10 10:53:46

115. [10641](http://github.com/cms-sw/cmssw/pull/10641){:target="_blank"}  from **@diguida**: Hotfix for Run2015A+B 0T luminous region centroid positions (76X) `simulation`  created: 2015-08-08 17:31:04 merged: 2015-08-10 06:01:11

116. [10642](http://github.com/cms-sw/cmssw/pull/10642){:target="_blank"}  from **@lathomas**: Beam Halo filter bug fix `reconstruction`  created: 2015-08-09 07:58:37 merged: 2015-08-10 05:56:13

#### CMSDIST Changes between Tags REL/CMSSW_7_6_0_pre3/slc6_amd64_gcc493 and REL/CMSSW_7_6_0_pre4/slc6_amd64_gcc493:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_6_0_pre3/slc6_amd64_gcc493...REL/CMSSW_7_6_0_pre4/slc6_amd64_gcc493)



1. [1776](http://github.com/cms-sw/cmsdist/pull/1776){:target="_blank"}  from **@cms-sw**: Revert "upgrade to evtgen 1.4.0p1" created: 2015-08-27 07:45:56 merged: 2015-08-27 07:46:00

2. [1771](http://github.com/cms-sw/cmsdist/pull/1771){:target="_blank"}  from **@mkirsano**: upgrade to evtgen 1.4.0p1 created: 2015-08-25 14:44:28 merged: 2015-08-26 13:44:05

3. [1745](http://github.com/cms-sw/cmsdist/pull/1745){:target="_blank"}  from **@degano**: Advance fastjet-contrib to thread-friendly patch. created: 2015-08-19 08:16:42 merged: 2015-08-19 08:16:44

4. [1744](http://github.com/cms-sw/cmsdist/pull/1744){:target="_blank"}  from **@degano**: Advance RecoEgamma/PhotonIdentification data to V01-00-03 created: 2015-08-18 12:16:35 merged: 2015-08-18 12:16:39

5. [1734](http://github.com/cms-sw/cmsdist/pull/1734){:target="_blank"}  from **@smuzaffar**: added back the -fPIC created: 2015-08-10 19:43:44 merged: 2015-08-10 19:43:49

6. [1733](http://github.com/cms-sw/cmsdist/pull/1733){:target="_blank"}  from **@smuzaffar**: added -DG4USE_STD11 for geant4static tool; not needed as this tool is only used for linking created: 2015-08-10 14:31:22 merged: 2015-08-10 14:31:33

7. [1732](http://github.com/cms-sw/cmsdist/pull/1732){:target="_blank"}  from **@smuzaffar**: Geant4 std11 fix created: 2015-08-10 13:51:10 merged: 2015-08-10 13:53:11
