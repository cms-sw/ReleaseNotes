---
layout: post
rel_link:  "8_3_0"
title:  "CMSSW_8_3_0"
date:   2017-02-23 08:32:09
categories: cmssw
relmajor: 8
relminor: 3
relsubminor: 0
---

# CMSSW_8_3_0
#### Changes since CMSSW_8_2_0_patch1:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_2_0_patch1...CMSSW_8_3_0)



1. [17614](http://github.com/cms-sw/cmssw/pull/17614){:target="_blank"}  from **@davidlange6**: repair check on release number `comparison`  `hlt`  created: 2017-02-23 08:28:57 merged: 2017-02-23 08:29:13

2. [17585](http://github.com/cms-sw/cmssw/pull/17585){:target="_blank"}  from **@davidlange6**: 8_3_0 bug fixes `alca`  `comparison`  `dqm`  `hlt`  `l1`  `pdmv`  `reconstruction`  `upgrade`  created: 2017-02-21 12:31:42 merged: 2017-02-21 12:32:05

3. [17392](http://github.com/cms-sw/cmssw/pull/17392){:target="_blank"}  from **@cms-sw**: Revert "Pr90x L1T Stage2 for Phase2" `alca`  `comparison`  `l1`  `simulation`  created: 2017-02-02 15:52:19 merged: 2017-02-02 15:52:41

4. [17391](http://github.com/cms-sw/cmssw/pull/17391){:target="_blank"}  from **@kpedro88**: temp fix 2017 WF nums by skipping ranges `pdmv`  `upgrade`  created: 2017-02-02 15:43:55 merged: 2017-02-02 17:44:11

5. [17390](http://github.com/cms-sw/cmssw/pull/17390){:target="_blank"}  from **@boudoul**: Removing 'cout' comments  from code used in prod (phase2 Track Trigger)  `comparison`  `l1`  created: 2017-02-02 14:43:14 merged: 2017-02-02 20:24:33

6. [17382](http://github.com/cms-sw/cmssw/pull/17382){:target="_blank"}  from **@makortel**: Fix calculation of TrackingParticle::numberOfHits() `simulation`  created: 2017-02-02 08:48:52 merged: 2017-02-02 20:25:37

7. [17380](http://github.com/cms-sw/cmssw/pull/17380){:target="_blank"}  from **@gartung**: DataFormats/CaloTowers : changes needed to compile on macOS sierra with system clang and libc++ `reconstruction`  created: 2017-02-01 23:12:26 merged: 2017-02-02 20:26:27

8. [17377](http://github.com/cms-sw/cmssw/pull/17377){:target="_blank"}  from **@knoepfel**: Convert edm::LogErrorHarvester from legacy to global EDProducer. `core`  created: 2017-02-01 18:35:59 merged: 2017-02-02 08:43:05

9. [17374](http://github.com/cms-sw/cmssw/pull/17374){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-gem22 Update the gap value in GE21 design for TDR_Dev version `geometry`  created: 2017-02-01 16:05:45 merged: 2017-02-02 08:42:42

10. [17371](http://github.com/cms-sw/cmssw/pull/17371){:target="_blank"}  from **@Dr15Jones**: The new gcc ABI for C++11 uses different namespace `core`  created: 2017-02-01 15:17:25 merged: 2017-02-02 10:26:20

11. [17367](http://github.com/cms-sw/cmssw/pull/17367){:target="_blank"}  from **@VinInn**: make TrackExtra fully persistent because of FastSimPU `reconstruction`  created: 2017-02-01 10:07:03 merged: 2017-02-01 10:31:25

12. [17366](http://github.com/cms-sw/cmssw/pull/17366){:target="_blank"}  from **@ggovi**: Remove CondCore/ORA package `db`  created: 2017-02-01 09:32:33 merged: 2017-02-01 15:24:44

13. [17364](http://github.com/cms-sw/cmssw/pull/17364){:target="_blank"}  from **@davidlange6**: remove comparisons of nonnull objects against 0 `reconstruction`  created: 2017-02-01 09:03:19 merged: 2017-02-02 20:26:37

14. [17363](http://github.com/cms-sw/cmssw/pull/17363){:target="_blank"}  from **@VinInn**: Fix 17098 `dqm`  created: 2017-02-01 08:56:57 merged: 2017-02-01 09:16:43

15. [17359](http://github.com/cms-sw/cmssw/pull/17359){:target="_blank"}  from **@gartung**: SimDataFormats/RandomEngineState : Changes needed to compile with macOS clang and libc++ `simulation`  created: 2017-01-31 20:17:36 merged: 2017-02-01 15:50:33

16. [17355](http://github.com/cms-sw/cmssw/pull/17355){:target="_blank"}  from **@gartung**: Geometry/CaloGeometry : Changes needed to compile with macOS clang and libc++ `geometry`  created: 2017-01-31 20:08:09 merged: 2017-02-01 15:21:56

17. [17354](http://github.com/cms-sw/cmssw/pull/17354){:target="_blank"}  from **@gartung**: Fireworks/Core : Changes needed to compile with macOS clang and libc++ `visualization`  created: 2017-01-31 20:04:41 merged: 2017-02-01 15:20:35

18. [17342](http://github.com/cms-sw/cmssw/pull/17342){:target="_blank"}  from **@gartung**: FWCore/Framework : Changes needed to compile with macOS clang and libc++ `core`  created: 2017-01-31 19:24:45 merged: 2017-02-02 08:43:27

19. [17341](http://github.com/cms-sw/cmssw/pull/17341){:target="_blank"}  from **@davidlange6**: more workflows that can not use recycled gensim at this point `pdmv`  created: 2017-01-31 18:17:27 merged: 2017-01-31 19:27:24

20. [17338](http://github.com/cms-sw/cmssw/pull/17338){:target="_blank"}  from **@makortel**: Remove check on TrackingParticle::numberOfHits()==0 from QuickTrackAssociatorByHits `dqm`  `simulation`  created: 2017-01-31 16:08:03 merged: 2017-02-01 15:19:04

21. [17337](http://github.com/cms-sw/cmssw/pull/17337){:target="_blank"}  from **@franzoni**: alignment (asy and real) Consistent with Fpix updated Thickness (290 instead of 300 mum) `alca`  created: 2017-01-31 15:21:54 merged: 2017-01-31 19:22:41

22. [17336](http://github.com/cms-sw/cmssw/pull/17336){:target="_blank"}  from **@lorusso7**: Madgraph 2.4.2 cards `generators`  created: 2017-01-31 14:28:19 merged: 2017-02-01 15:18:33

23. [17335](http://github.com/cms-sw/cmssw/pull/17335){:target="_blank"}  from **@kpedro88**: Fix or suppress warnings related to Phase0 HE in 2017 `dqm`  created: 2017-01-31 13:58:19 merged: 2017-01-31 21:48:24

24. [17334](http://github.com/cms-sw/cmssw/pull/17334){:target="_blank"}  from **@VinInn**: use edm::View in TrackRefitter `reconstruction`  created: 2017-01-31 11:07:10 merged: 2017-02-02 20:28:32

25. [17332](http://github.com/cms-sw/cmssw/pull/17332){:target="_blank"}  from **@davidlange6**: turn off 2017 gen sim recycle for now `pdmv`  created: 2017-01-31 07:28:29 merged: 2017-01-31 08:51:29

26. [17329](http://github.com/cms-sw/cmssw/pull/17329){:target="_blank"}  from **@Dr15Jones**: Fix pickling of SortedKeysDict `core`  created: 2017-01-30 21:03:06 merged: 2017-01-31 08:55:00

27. [17328](http://github.com/cms-sw/cmssw/pull/17328){:target="_blank"}  from **@Dr15Jones**: Add missing initializations needed by python CmsRun `core`  created: 2017-01-30 20:51:49 merged: 2017-01-31 08:54:43

28. [17324](http://github.com/cms-sw/cmssw/pull/17324){:target="_blank"}  from **@ianna**: GEM Reco Geometry from DB in 2017 Era `geometry`  `operations`  created: 2017-01-30 16:12:47 merged: 2017-01-31 09:58:01

29. [17320](http://github.com/cms-sw/cmssw/pull/17320){:target="_blank"}  from **@syuvivida**: Fix of GenFilterInfo in 90X release `generators`  created: 2017-01-30 14:37:30 merged: 2017-01-31 15:03:09

30. [17319](http://github.com/cms-sw/cmssw/pull/17319){:target="_blank"}  from **@franzoni**: geometry updates: Tracker and Gem affecting 2017 and 2018 scenarios `alca`  created: 2017-01-30 12:33:31 merged: 2017-01-31 09:57:21

31. [17316](http://github.com/cms-sw/cmssw/pull/17316){:target="_blank"}  from **@bbockelm**: Fix string quoting for condor_chirp CLI. `core`  created: 2017-01-30 02:33:15 merged: 2017-01-31 08:53:47

32. [17314](http://github.com/cms-sw/cmssw/pull/17314){:target="_blank"}  from **@boudoul**: Adding Stubs within Track Trigger Sequence (Phase2 Tracker)  `operations`  `pdmv`  created: 2017-01-29 20:32:50 merged: 2017-01-30 17:34:17

33. [17312](http://github.com/cms-sw/cmssw/pull/17312){:target="_blank"}  from **@slava77**: put unscheduled customs in order: external methods done applied after all internal (miniAOD) are done `operations`  created: 2017-01-29 14:58:27 merged: 2017-01-30 08:55:45

34. [17310](http://github.com/cms-sw/cmssw/pull/17310){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx100 Add a few test to verify Plan-1 geometry `geometry`  created: 2017-01-27 22:49:55 merged: 2017-01-29 09:01:31

35. [17309](http://github.com/cms-sw/cmssw/pull/17309){:target="_blank"}  from **@rekovic**: 90x L1T FEVTDEBUG fix missing Stage2 products `l1`  created: 2017-01-27 17:41:33 merged: 2017-01-31 08:53:37

36. [17304](http://github.com/cms-sw/cmssw/pull/17304){:target="_blank"}  from **@manoni**: Modification/Addition in SiStripMonitorDigi and SiStripMonitorCluster packages `dqm`  created: 2017-01-27 11:05:08 merged: 2017-02-01 15:17:50

37. [17301](http://github.com/cms-sw/cmssw/pull/17301){:target="_blank"}  from **@yiiyama**: Bugfix EcalSimProducer for APD simulation `simulation`  created: 2017-01-26 23:03:38 merged: 2017-01-30 17:21:11

38. [17299](http://github.com/cms-sw/cmssw/pull/17299){:target="_blank"}  from **@capalmer85**: add selecting bunch feature to estimate PU script - 90X `db`  created: 2017-01-26 19:33:14 merged: 2017-01-27 21:17:31

39. [17297](http://github.com/cms-sw/cmssw/pull/17297){:target="_blank"}  from **@kpedro88**: Fix config for Phase2 EB trig prim digis `l1`  `simulation`  created: 2017-01-26 16:36:54 merged: 2017-01-29 09:00:53

40. [17294](http://github.com/cms-sw/cmssw/pull/17294){:target="_blank"}  from **@cms-btv-pog**: Switching BoostedDoubleSV tagger to v4 training for AK8 jets `reconstruction`  created: 2017-01-26 15:26:32 merged: 2017-01-30 12:42:39

41. [17291](http://github.com/cms-sw/cmssw/pull/17291){:target="_blank"}  from **@ianna**: Extended 2018 Geometry Scenario Update `db`  `geometry`  created: 2017-01-26 10:12:01 merged: 2017-02-01 15:37:55

42. [17290](http://github.com/cms-sw/cmssw/pull/17290){:target="_blank"}  from **@rovere**: Silent warning due to missing templates in PhaseII `dqm`  created: 2017-01-26 10:05:37 merged: 2017-02-01 15:21:32

43. [17289](http://github.com/cms-sw/cmssw/pull/17289){:target="_blank"}  from **@jhgoh**: RPCRecHit local x position correction `reconstruction`  created: 2017-01-26 07:49:50 merged: 2017-02-02 20:29:42

44. [17287](http://github.com/cms-sw/cmssw/pull/17287){:target="_blank"}  from **@mdhildreth**: add base configuration to allow arbitrary pileup functions on a stabl `simulation`  created: 2017-01-25 22:25:59 merged: 2017-01-27 14:50:38

45. [17284](http://github.com/cms-sw/cmssw/pull/17284){:target="_blank"}  from **@fwyzard**: move migration to HBHEPhase1Reconstructor to the common run2_HCAL_2017 era `hlt`  created: 2017-01-25 17:55:59 merged: 2017-01-25 20:12:55

46. [17283](http://github.com/cms-sw/cmssw/pull/17283){:target="_blank"}  from **@civanch**: Fix for exotica simulation `simulation`  created: 2017-01-25 16:17:01 merged: 2017-01-26 19:48:32

47. [17281](http://github.com/cms-sw/cmssw/pull/17281){:target="_blank"}  from **@walterjr**: 2015LowPUMixProfile90X `operations`  `simulation`  created: 2017-01-25 12:14:23 merged: 2017-01-25 16:38:24

48. [17280](http://github.com/cms-sw/cmssw/pull/17280){:target="_blank"}  from **@rovere**: Update RecoMaterial `geometry`  created: 2017-01-25 11:01:28 merged: 2017-01-30 13:55:13

49. [17279](http://github.com/cms-sw/cmssw/pull/17279){:target="_blank"}  from **@emanueledimarco**: Optional use of Max-Sample algorithm for gain-switch cases `reconstruction`  created: 2017-01-25 10:58:56 merged: 2017-01-30 12:51:37

50. [17278](http://github.com/cms-sw/cmssw/pull/17278){:target="_blank"}  from **@ggovi**: conddb tools improvements `db`  created: 2017-01-25 10:18:55 merged: 2017-01-31 17:14:17

51. [17275](http://github.com/cms-sw/cmssw/pull/17275){:target="_blank"}  from **@davidlt**: Replace deprecated throw with noexcept `reconstruction`  created: 2017-01-25 05:56:07 merged: 2017-01-27 22:00:15

52. [17274](http://github.com/cms-sw/cmssw/pull/17274){:target="_blank"}  from **@davidlt**: Replace forward decl for PFTrackTransformer with full header incl `reconstruction`  created: 2017-01-25 05:21:44 merged: 2017-01-27 22:22:13

53. [17273](http://github.com/cms-sw/cmssw/pull/17273){:target="_blank"}  from **@davidlt**: Cleanup throw specifier and boost stuff `simulation`  created: 2017-01-25 05:09:13 merged: 2017-01-25 16:22:19

54. [17272](http://github.com/cms-sw/cmssw/pull/17272){:target="_blank"}  from **@davidlt**: Resolve -Werror=format-truncation= issues `analysis`  created: 2017-01-25 04:49:43 merged: 2017-01-25 16:47:20

55. [17271](http://github.com/cms-sw/cmssw/pull/17271){:target="_blank"}  from **@davidlt**: Replace bool with unsigned int `analysis`  created: 2017-01-25 01:00:50 merged: 2017-01-25 16:22:38

56. [17270](http://github.com/cms-sw/cmssw/pull/17270){:target="_blank"}  from **@davidlt**: Remove char buffer and sprintf with std::string/std::to_string `dqm`  `geometry`  created: 2017-01-25 00:10:55 merged: 2017-01-25 16:23:26

57. [17269](http://github.com/cms-sw/cmssw/pull/17269){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx99 Interface change in view of handling special RBX `geometry`  created: 2017-01-24 23:23:56 merged: 2017-01-25 16:31:26

58. [17268](http://github.com/cms-sw/cmssw/pull/17268){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx98 Enable possibility of running GEN-SIM for some 2017 geometry and choosing Plan0/1/36 at DIGI-RECO level `geometry`  `simulation`  created: 2017-01-24 22:28:21 merged: 2017-01-27 15:22:20

59. [17267](http://github.com/cms-sw/cmssw/pull/17267){:target="_blank"}  from **@davidlt**: Replace TString with std::string to avoid C++17 issues `dqm`  created: 2017-01-24 22:16:08 merged: 2017-01-25 17:09:22

60. [17265](http://github.com/cms-sw/cmssw/pull/17265){:target="_blank"}  from **@cms-sw**: Revert "CTPPS: miniAOD" `analysis`  `comparison`  `dqm`  `reconstruction`  created: 2017-01-24 19:19:38 merged: 2017-01-24 19:20:23

61. [17261](http://github.com/cms-sw/cmssw/pull/17261){:target="_blank"}  from **@ianna**: TIB Rail Bottom Overlap Bugfix `geometry`  created: 2017-01-24 16:42:10 merged: 2017-01-30 14:34:47

62. [17255](http://github.com/cms-sw/cmssw/pull/17255){:target="_blank"}  from **@davidlt**: Replace buf/sprintf to std::to_string `geometry`  created: 2017-01-23 17:28:59 merged: 2017-01-24 14:05:26

63. [17253](http://github.com/cms-sw/cmssw/pull/17253){:target="_blank"}  from **@aperloff**: Thread Safe Jet Correctors `analysis`  `reconstruction`  created: 2017-01-23 15:57:44 merged: 2017-01-27 14:52:08

64. [17252](http://github.com/cms-sw/cmssw/pull/17252){:target="_blank"}  from **@bapavlov**: iRPC_2D `simulation`  created: 2017-01-23 15:39:49 merged: 2017-01-25 16:51:58

65. [17250](http://github.com/cms-sw/cmssw/pull/17250){:target="_blank"}  from **@pietverwilligen**: ME0ReDigitizer not using roll==0 to distinguish between M1 and M2 geometry `simulation`  created: 2017-01-23 13:37:26 merged: 2017-01-30 14:04:27

66. [17249](http://github.com/cms-sw/cmssw/pull/17249){:target="_blank"}  from **@depasse**: Reading TPG parameters from file `db`  created: 2017-01-23 11:01:21 merged: 2017-02-01 15:16:46

67. [17248](http://github.com/cms-sw/cmssw/pull/17248){:target="_blank"}  from **@cms-l1t-offline**: Pr90x L1T Stage2 for Phase2 `alca`  `l1`  `simulation`  created: 2017-01-23 10:52:42 merged: 2017-01-31 17:14:49

68. [17246](http://github.com/cms-sw/cmssw/pull/17246){:target="_blank"}  from **@intrepid42**: Read compressed LHE weights `generators`  created: 2017-01-23 10:28:09 merged: 2017-01-24 17:44:22

69. [17245](http://github.com/cms-sw/cmssw/pull/17245){:target="_blank"}  from **@schneiml**: Pixel Material Budget Changes (updated) `dqm`  `geometry`  created: 2017-01-22 17:44:47 merged: 2017-01-30 13:56:17

70. [17243](http://github.com/cms-sw/cmssw/pull/17243){:target="_blank"}  from **@davidlt**: Clean Clang warnings regarding hiding overloaded virtual functions `alca`  created: 2017-01-21 15:34:46 merged: 2017-01-24 14:10:41

71. [17241](http://github.com/cms-sw/cmssw/pull/17241){:target="_blank"}  from **@slava77**: reduce memory used by iso deposits `analysis`  `operations`  `reconstruction`  created: 2017-01-21 03:17:38 merged: 2017-01-22 20:39:25

72. [17239](http://github.com/cms-sw/cmssw/pull/17239){:target="_blank"}  from **@davidlt**: HLT GCC 7 Cleanup `hlt`  created: 2017-01-20 22:04:12 merged: 2017-01-22 09:06:49

73. [17237](http://github.com/cms-sw/cmssw/pull/17237){:target="_blank"}  from **@davidlt**: Add dtors with noexcept(false) to match C++ requirements `core`  created: 2017-01-20 21:21:56 merged: 2017-01-25 16:25:40

74. [17236](http://github.com/cms-sw/cmssw/pull/17236){:target="_blank"}  from **@Dr15Jones**: Added ability to import framework into python `core`  created: 2017-01-20 21:07:54 merged: 2017-01-22 09:07:22

75. [17235](http://github.com/cms-sw/cmssw/pull/17235){:target="_blank"}  from **@fwyzard**: HLT customisations for the Phase I HCAL upgrades `hlt`  created: 2017-01-20 19:28:16 merged: 2017-01-25 17:15:06

76. [17232](http://github.com/cms-sw/cmssw/pull/17232){:target="_blank"}  from **@davidlt**: Replace throw dynamic exception specifiers with noexcept `db`  created: 2017-01-20 16:51:20 merged: 2017-01-23 16:45:57

77. [17230](http://github.com/cms-sw/cmssw/pull/17230){:target="_blank"}  from **@davidlt**: Use static_cast to call explicitly conversion operator on TString `visualization`  created: 2017-01-20 16:41:08 merged: 2017-01-21 09:04:46

78. [17227](http://github.com/cms-sw/cmssw/pull/17227){:target="_blank"}  from **@davidlt**: Use static_cast to call explicitly conversion operator on TString `analysis`  created: 2017-01-20 13:38:27 merged: 2017-01-20 17:44:52

79. [17226](http://github.com/cms-sw/cmssw/pull/17226){:target="_blank"}  from **@matz-e**: HCAL TP: Address outstanding comment from #17171 `l1`  created: 2017-01-20 13:22:48 merged: 2017-01-23 17:24:16

80. [17221](http://github.com/cms-sw/cmssw/pull/17221){:target="_blank"}  from **@mtosi**: edm::Viewreco::Track instead of reco::TrackCollection in DQM/TrackingMonitor `dqm`  created: 2017-01-20 10:22:45 merged: 2017-01-24 17:57:43

81. [17220](http://github.com/cms-sw/cmssw/pull/17220){:target="_blank"}  from **@smuzaffar**: update root numpy unit test `analysis`  created: 2017-01-20 09:13:58 merged: 2017-01-20 09:42:09

82. [17217](http://github.com/cms-sw/cmssw/pull/17217){:target="_blank"}  from **@bbockelm**: Pass thread count to gridpack run scripts. `core`  `generators`  created: 2017-01-20 03:19:54 merged: 2017-01-21 09:05:13

83. [17216](http://github.com/cms-sw/cmssw/pull/17216){:target="_blank"}  from **@Dr15Jones**: Fixed python module name for C++ callable code `core`  created: 2017-01-19 22:32:59 merged: 2017-01-20 13:04:14

84. [17215](http://github.com/cms-sw/cmssw/pull/17215){:target="_blank"}  from **@knoepfel**: Convert JetConstituentSelector template from legacy to stream filter `reconstruction`  created: 2017-01-19 19:34:16 merged: 2017-01-27 21:18:39

85. [17214](http://github.com/cms-sw/cmssw/pull/17214){:target="_blank"}  from **@ahinzmann**: Sync AOD and MiniAOD PU ID `reconstruction`  created: 2017-01-19 18:40:13 merged: 2017-01-22 09:07:59

86. [17213](http://github.com/cms-sw/cmssw/pull/17213){:target="_blank"}  from **@davidlt**: Replace throw specifier (deprecated) with noexcept (C++11) `db`  created: 2017-01-19 15:10:28 merged: 2017-01-23 16:50:55

87. [17212](http://github.com/cms-sw/cmssw/pull/17212){:target="_blank"}  from **@argiro**: fix missing assignment of gainswitch flag `reconstruction`  created: 2017-01-19 15:00:52 merged: 2017-01-22 09:08:16

88. [17210](http://github.com/cms-sw/cmssw/pull/17210){:target="_blank"}  from **@schneiml**: Material Budget Tool Fixes `dqm`  `geometry`  created: 2017-01-19 14:13:07 merged: 2017-01-25 17:03:16

89. [17208](http://github.com/cms-sw/cmssw/pull/17208){:target="_blank"}  from **@schneiml**: Phase1 Pixel DQM PixelMaps, new TrackEfficiencies, removed Harvesting, new Plots and various Bugfixes `dqm`  created: 2017-01-19 12:55:09 merged: 2017-01-29 09:00:45

90. [17207](http://github.com/cms-sw/cmssw/pull/17207){:target="_blank"}  from **@ggovi**: Improvements for o2o tools `db`  created: 2017-01-19 10:10:18 merged: 2017-01-23 16:49:15

91. [17205](http://github.com/cms-sw/cmssw/pull/17205){:target="_blank"}  from **@bendavid**: Extended Multifit functionality `reconstruction`  created: 2017-01-18 23:26:40 merged: 2017-01-23 19:38:32

92. [17203](http://github.com/cms-sw/cmssw/pull/17203){:target="_blank"}  from **@dmitrijus**: Implement handling of edm::shutdown_flag in online DQM sources `dqm`  created: 2017-01-18 15:02:03 merged: 2017-01-19 07:42:08

93. [17199](http://github.com/cms-sw/cmssw/pull/17199){:target="_blank"}  from **@ianna**: TOB Connectors Overlap Bugfix `geometry`  created: 2017-01-18 09:27:01 merged: 2017-01-30 13:54:19

94. [17198](http://github.com/cms-sw/cmssw/pull/17198){:target="_blank"}  from **@kpedro88**: Phase0 HE in 2017, Phase1 HE in 2018 `alca`  `db`  `dqm`  `geometry`  `operations`  `pdmv`  `reconstruction`  `simulation`  created: 2017-01-18 00:52:37 merged: 2017-01-29 09:00:02

95. [17197](http://github.com/cms-sw/cmssw/pull/17197){:target="_blank"}  from **@wddgit**: Clean up import statements to only import what is necessary. `analysis`  `reconstruction`  created: 2017-01-17 20:32:13 merged: 2017-01-18 09:41:20

96. [17195](http://github.com/cms-sw/cmssw/pull/17195){:target="_blank"}  from **@pietverwilligen**: change ME0Geometry from 10 to 8 eta partitions for TDRDev `geometry`  created: 2017-01-17 12:11:33 merged: 2017-01-18 09:41:35

97. [17188](http://github.com/cms-sw/cmssw/pull/17188){:target="_blank"}  from **@smorovic**: DAQ test module updates (90X) `daq`  `reconstruction`  created: 2017-01-16 15:30:11 merged: 2017-01-18 09:46:39

98. [17185](http://github.com/cms-sw/cmssw/pull/17185){:target="_blank"}  from **@cms-sw**: Replace TMVA::Factory->SetInputTrees with TMVA::DataLoader `analysis`  created: 2017-01-16 15:11:25 merged: 2017-01-17 06:35:18

99. [17184](http://github.com/cms-sw/cmssw/pull/17184){:target="_blank"}  from **@davidlt**: Value initialize MapType to avoid -Werror=maybe-uninitialized `reconstruction`  created: 2017-01-16 14:40:58 merged: 2017-01-17 09:56:14

100. [17182](http://github.com/cms-sw/cmssw/pull/17182){:target="_blank"}  from **@cms-tsg-storm**: Update of HLT to /dev/CMSSW_9_0_0/HLT/V5 (90X) `hlt`  created: 2017-01-16 13:39:33 merged: 2017-01-18 09:47:15

101. [17181](http://github.com/cms-sw/cmssw/pull/17181){:target="_blank"}  from **@mtosi**: add pixel and strip clusters vs good pv and lumi `dqm`  `hlt`  created: 2017-01-16 11:51:48 merged: 2017-01-19 07:42:48

102. [17179](http://github.com/cms-sw/cmssw/pull/17179){:target="_blank"}  from **@civanch**: Smart G4 magnetic field manager `simulation`  created: 2017-01-16 09:52:01 merged: 2017-01-19 15:43:24

103. [17177](http://github.com/cms-sw/cmssw/pull/17177){:target="_blank"}  from **@suchandradutta**: Tracker Phase2Digitizer updated  memory leak `simulation`  created: 2017-01-14 19:25:30 merged: 2017-01-17 02:16:58

104. [17176](http://github.com/cms-sw/cmssw/pull/17176){:target="_blank"}  from **@lgray**: Add timing detectors to GeomDetEnumerators `geometry`  created: 2017-01-13 23:19:23 merged: 2017-01-16 08:12:28

105. [17175](http://github.com/cms-sw/cmssw/pull/17175){:target="_blank"}  from **@pietverwilligen**: New ME0GeometryBuilder for baseline ME0 geometry `geometry`  created: 2017-01-13 17:12:34 merged: 2017-01-16 08:14:29

106. [17174](http://github.com/cms-sw/cmssw/pull/17174){:target="_blank"}  from **@Dr15Jones**: Replaced tab with space to avoid gcc 6.3 warning in L1Trigger/L1TCommon `l1`  created: 2017-01-13 16:52:56 merged: 2017-01-14 00:21:30

107. [17173](http://github.com/cms-sw/cmssw/pull/17173){:target="_blank"}  from **@Dr15Jones**: Use dynamic_cast instead of reinterpret_cast in HeavyFlavorAnalysis `analysis`  created: 2017-01-13 16:00:27 merged: 2017-01-14 00:21:52

108. [17172](http://github.com/cms-sw/cmssw/pull/17172){:target="_blank"}  from **@Dr15Jones**: Hide debugging code in TrackingTrughAccumulator `simulation`  created: 2017-01-13 15:20:48 merged: 2017-01-14 00:22:29

109. [17171](http://github.com/cms-sw/cmssw/pull/17171){:target="_blank"}  from **@matz-e**: Make HCAL TP generation more robust. `l1`  created: 2017-01-13 12:04:48 merged: 2017-01-20 13:10:24

110. [17170](http://github.com/cms-sw/cmssw/pull/17170){:target="_blank"}  from **@makortel**: Migrate PixelTrackProducer and HLT to new seeding framework `alca`  `dqm`  `fastsim`  `hlt`  `reconstruction`  created: 2017-01-13 10:32:04 merged: 2017-01-26 23:40:34

111. [17168](http://github.com/cms-sw/cmssw/pull/17168){:target="_blank"}  from **@gartung**: Fixes for changes in location of apple clang's libc++ header locations `core`  `reconstruction`  created: 2017-01-12 21:20:11 merged: 2017-01-14 00:23:09

112. [17167](http://github.com/cms-sw/cmssw/pull/17167){:target="_blank"}  from **@smuzaffar**: use cmssw_das_client wrapper instead of duplicated das_client code `analysis`  created: 2017-01-12 16:19:30 merged: 2017-01-13 00:23:35

113. [17166](http://github.com/cms-sw/cmssw/pull/17166){:target="_blank"}  from **@davidlt**: Fix FORTRAN warnings in ME2pythia.f `generators`  created: 2017-01-12 12:38:19 merged: 2017-01-13 00:23:44

114. [17165](http://github.com/cms-sw/cmssw/pull/17165){:target="_blank"}  from **@slehti**: Changed hltCaloStage2Digis -> caloStage2Digis `dqm`  created: 2017-01-12 12:13:15 merged: 2017-01-14 00:23:44

115. [17164](http://github.com/cms-sw/cmssw/pull/17164){:target="_blank"}  from **@davidlt**: Fix warning (non-null compare) in MatrixMeschach `alca`  created: 2017-01-12 12:08:33 merged: 2017-01-13 00:24:20

116. [17163](http://github.com/cms-sw/cmssw/pull/17163){:target="_blank"}  from **@cms-tau-pog**: Increasing eta range for tau reconstruction for phase 2 geometries `reconstruction`  created: 2017-01-12 11:55:56 merged: 2017-01-18 09:48:46

117. [17162](http://github.com/cms-sw/cmssw/pull/17162){:target="_blank"}  from **@CTPPS**: CTPPS: miniAOD `analysis`  `dqm`  `reconstruction`  created: 2017-01-12 11:01:27 merged: 2017-01-20 13:13:08

118. [17161](http://github.com/cms-sw/cmssw/pull/17161){:target="_blank"}  from **@wmtford**: Hit assoc for phase2 `simulation`  created: 2017-01-12 04:45:02 merged: 2017-01-16 08:16:03

119. [17158](http://github.com/cms-sw/cmssw/pull/17158){:target="_blank"}  from **@wddgit**: Remove import \* for cloned modules `analysis`  `reconstruction`  created: 2017-01-11 20:41:17 merged: 2017-01-13 00:24:41

120. [17156](http://github.com/cms-sw/cmssw/pull/17156){:target="_blank"}  from **@ianna**: Remove Overlaps in FPix `geometry`  created: 2017-01-11 17:24:17 merged: 2017-01-30 13:53:44

121. [17155](http://github.com/cms-sw/cmssw/pull/17155){:target="_blank"}  from **@gartung**: Fix error from apple-clang-8.0 because of missing #include <functional> `core`  created: 2017-01-11 17:05:28 merged: 2017-01-12 00:34:54

122. [17153](http://github.com/cms-sw/cmssw/pull/17153){:target="_blank"}  from **@wddgit**: Replace import \* when modules are imported only to be cloned `analysis`  `reconstruction`  created: 2017-01-11 15:32:44 merged: 2017-01-13 10:26:05

123. [17152](http://github.com/cms-sw/cmssw/pull/17152){:target="_blank"}  from **@Dr15Jones**: Fix operator!= for pat::strbitset `analysis`  created: 2017-01-11 15:17:08 merged: 2017-01-12 10:42:38

124. [17151](http://github.com/cms-sw/cmssw/pull/17151){:target="_blank"}  from **@davidlt**: Fix self-comparison in L1MuGMTExtendedCand `l1`  created: 2017-01-11 15:12:11 merged: 2017-01-13 00:25:29

125. [17150](http://github.com/cms-sw/cmssw/pull/17150){:target="_blank"}  from **@Dr15Jones**: Fix L1TCaloParamsCompare operator== `l1`  created: 2017-01-11 15:02:58 merged: 2017-01-13 00:25:50

126. [17147](http://github.com/cms-sw/cmssw/pull/17147){:target="_blank"}  from **@davidlt**: Avoid Oracle OCCI APIs which work with std::string in C++11 ABI mode `db`  created: 2017-01-11 14:27:33 merged: 2017-01-23 16:49:25

127. [17146](http://github.com/cms-sw/cmssw/pull/17146){:target="_blank"}  from **@archiron**: Provenance histos rescaling updated 90X v1 `dqm`  created: 2017-01-11 13:58:37 merged: 2017-01-12 00:35:44

128. [17145](http://github.com/cms-sw/cmssw/pull/17145){:target="_blank"}  from **@amartelli**: dead ES regions with corrected energy for each plane. Fixes inconsistency in regression training `reconstruction`  created: 2017-01-11 13:34:17 merged: 2017-01-18 09:49:15

129. [17144](http://github.com/cms-sw/cmssw/pull/17144){:target="_blank"}  from **@ebrondol**: Fix geometry ordering for Phase2 Pixel `geometry`  `reconstruction`  created: 2017-01-11 11:22:51 merged: 2017-01-17 10:05:22

130. [17142](http://github.com/cms-sw/cmssw/pull/17142){:target="_blank"}  from **@cms-sw**: For runTheMatrix: fix lumi section selection logic to avoid duplicate file names `comparison`  `pdmv`  created: 2017-01-11 06:56:01 merged: 2017-01-11 06:56:58

131. [17140](http://github.com/cms-sw/cmssw/pull/17140){:target="_blank"}  from **@cms-sw**: filter das_client results match the needed lumi sections if requested `pdmv`  created: 2017-01-10 15:32:53 merged: 2017-01-10 22:21:45

132. [17139](http://github.com/cms-sw/cmssw/pull/17139){:target="_blank"}  from **@davidlt**: FriendlyName: add "String" options for C++11 ABI `core`  created: 2017-01-10 13:42:23 merged: 2017-01-10 22:22:10

133. [17138](http://github.com/cms-sw/cmssw/pull/17138){:target="_blank"}  from **@Sam-Harper**: New E/gamma pat::Electron and pat::Photon modifiers `reconstruction`  created: 2017-01-10 12:23:50 merged: 2017-01-13 10:25:42

134. [17137](http://github.com/cms-sw/cmssw/pull/17137){:target="_blank"}  from **@Dr15Jones**: Force untracked parameters for modules into Registry `core`  created: 2017-01-09 22:14:11 merged: 2017-01-10 11:37:57

135. [17135](http://github.com/cms-sw/cmssw/pull/17135){:target="_blank"}  from **@lgray**: Remove use of tmpnam in generators `generators`  created: 2017-01-09 18:59:33 merged: 2017-01-10 11:38:06

136. [17134](http://github.com/cms-sw/cmssw/pull/17134){:target="_blank"}  from **@rovere**: Add reco material to dqm `dqm`  `geometry`  `simulation`  created: 2017-01-09 16:37:17 merged: 2017-01-16 13:02:14

137. [17131](http://github.com/cms-sw/cmssw/pull/17131){:target="_blank"}  from **@ianna**: GEM Reco Geometry Payload Writer Added to 2017 Scripts `db`  created: 2017-01-09 10:47:03 merged: 2017-02-01 15:36:56

138. [17129](http://github.com/cms-sw/cmssw/pull/17129){:target="_blank"}  from **@mariadalfonso**: HBHE M2: noise definition cleanup `reconstruction`  created: 2017-01-07 20:07:33 merged: 2017-01-17 10:15:22

139. [17127](http://github.com/cms-sw/cmssw/pull/17127){:target="_blank"}  from **@knoepfel**: Improvements to stall-monitoring service and script. `core`  created: 2017-01-06 19:45:15 merged: 2017-01-14 00:24:09

140. [17126](http://github.com/cms-sw/cmssw/pull/17126){:target="_blank"}  from **@davidlt**: Add missing HcalDeterministicFit::rCorrSiPM `reconstruction`  created: 2017-01-06 14:47:05 merged: 2017-01-07 08:19:49

141. [17124](http://github.com/cms-sw/cmssw/pull/17124){:target="_blank"}  from **@srimanob**: Fix empty list of LHE files (90X) `operations`  created: 2017-01-06 13:34:26 merged: 2017-01-07 08:20:43

142. [17121](http://github.com/cms-sw/cmssw/pull/17121){:target="_blank"}  from **@wddgit**: Prevent module used for cloning from being loaded into process and se `analysis`  `reconstruction`  created: 2017-01-05 19:57:04 merged: 2017-01-08 01:33:01

143. [17120](http://github.com/cms-sw/cmssw/pull/17120){:target="_blank"}  from **@Dr15Jones**: Fixed consumes in EcalDetailedTimeRecHitProducer `reconstruction`  created: 2017-01-05 19:46:13 merged: 2017-01-08 01:34:03

144. [17119](http://github.com/cms-sw/cmssw/pull/17119){:target="_blank"}  from **@Dr15Jones**: Fix randomly failing framework unit test `core`  created: 2017-01-05 16:35:12 merged: 2017-01-06 07:36:37

145. [17118](http://github.com/cms-sw/cmssw/pull/17118){:target="_blank"}  from **@Sam-Harper**: bug fix for GsfEleEcalDrivenCut  `reconstruction`  created: 2017-01-05 16:32:16 merged: 2017-01-07 09:21:10

146. [17117](http://github.com/cms-sw/cmssw/pull/17117){:target="_blank"}  from **@hroskes**: inequality operators for cms types `alca`  `analysis`  `core`  `db`  `dqm`  `reconstruction`  created: 2017-01-05 15:28:27 merged: 2017-01-12 10:37:58

147. [17116](http://github.com/cms-sw/cmssw/pull/17116){:target="_blank"}  from **@calabria**: New ME0 validation `dqm`  `reconstruction`  `simulation`  created: 2017-01-05 11:33:50 merged: 2017-02-01 15:15:42

148. [17115](http://github.com/cms-sw/cmssw/pull/17115){:target="_blank"}  from **@ianna**: GEM Slice Test in 2017 Scenario `geometry`  created: 2017-01-05 08:28:18 merged: 2017-01-30 13:53:18

149. [17114](http://github.com/cms-sw/cmssw/pull/17114){:target="_blank"}  from **@abdoulline**: Bringing Phase2 ZS in sync with Phase1 one `simulation`  created: 2017-01-05 07:16:04 merged: 2017-01-10 11:39:08

150. [17113](http://github.com/cms-sw/cmssw/pull/17113){:target="_blank"}  from **@Dr15Jones**: Fix exception message context information `core`  created: 2017-01-04 20:35:30 merged: 2017-01-07 08:22:01

151. [17112](http://github.com/cms-sw/cmssw/pull/17112){:target="_blank"}  from **@lgray**: Initialize timeError properly in FTLUncalibratedRecHit `reconstruction`  created: 2017-01-04 18:02:14 merged: 2017-01-06 07:36:57

152. [17111](http://github.com/cms-sw/cmssw/pull/17111){:target="_blank"}  from **@ronchese**: Bph reco update, jan 01 2017 `analysis`  `comparison`  created: 2017-01-04 15:52:40 merged: 2017-01-12 00:36:49

153. [17110](http://github.com/cms-sw/cmssw/pull/17110){:target="_blank"}  from **@ebrondol**: Second tuning of Pixel cluster shape cut for Phase 2 `reconstruction`  created: 2017-01-04 10:36:02 merged: 2017-01-14 00:24:24

154. [17109](http://github.com/cms-sw/cmssw/pull/17109){:target="_blank"}  from **@wmtford**: Update stripClusterMCanalysis config to 9_0_0_pr2 `dqm`  created: 2017-01-03 22:29:37 merged: 2017-01-10 22:25:00

155. [17108](http://github.com/cms-sw/cmssw/pull/17108){:target="_blank"}  from **@lgray**: Remove compiler warning in boosted taus `reconstruction`  created: 2017-01-03 18:37:32 merged: 2017-01-04 07:32:19

156. [17107](http://github.com/cms-sw/cmssw/pull/17107){:target="_blank"}  from **@lgray**: Remove compiler warnings in E/gamma packages `reconstruction`  created: 2017-01-03 18:21:06 merged: 2017-01-04 07:32:34

157. [17106](http://github.com/cms-sw/cmssw/pull/17106){:target="_blank"}  from **@ebrondol**: Updating Phase2 tracker documentation `geometry`  created: 2017-01-03 12:49:22 merged: 2017-01-05 07:41:43

158. [17104](http://github.com/cms-sw/cmssw/pull/17104){:target="_blank"}  from **@cms-AlCaDB**: [90X] Add new style of e/gamma regressions labels in Run1 MC Global Tags `alca`  created: 2016-12-30 08:59:04 merged: 2017-01-09 00:35:18

159. [17103](http://github.com/cms-sw/cmssw/pull/17103){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx72 Correct the validation sequence for HGCal `dqm`  `reconstruction`  `simulation`  created: 2016-12-29 20:26:05 merged: 2017-01-10 11:39:52

160. [17102](http://github.com/cms-sw/cmssw/pull/17102){:target="_blank"}  from **@Dr15Jones**: Better detection of unrunnable scheduled `core`  `operations`  created: 2016-12-29 03:16:20 merged: 2016-12-29 07:53:34

161. [17099](http://github.com/cms-sw/cmssw/pull/17099){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx97 Bug fixes for Hcal geometry routines `geometry`  created: 2016-12-27 14:46:32 merged: 2017-01-24 16:26:45

162. [17098](http://github.com/cms-sw/cmssw/pull/17098){:target="_blank"}  from **@VinInn**: Remove Trajectory from event `alca`  `dqm`  `fastsim`  `hlt`  `pdmv`  `reconstruction`  `visualization`  created: 2016-12-23 18:33:10 merged: 2017-01-31 20:48:11

163. [17097](http://github.com/cms-sw/cmssw/pull/17097){:target="_blank"}  from **@suchandradutta**: Update of the Phase2 Tracker Digitizer Validation suite `simulation`  created: 2016-12-23 17:02:20 merged: 2017-01-27 21:29:42

164. [17096](http://github.com/cms-sw/cmssw/pull/17096){:target="_blank"}  from **@cms-tsg-storm**: Migration of HLT to 900pre2 template & cleanup `hlt`  created: 2016-12-23 06:34:23 merged: 2017-01-05 07:43:20

165. [17094](http://github.com/cms-sw/cmssw/pull/17094){:target="_blank"}  from **@mariadalfonso**: HBHE: M3 scale fixes + online/offline M2 parameter adjustements `alca`  `hlt`  `reconstruction`  created: 2016-12-22 23:43:24 merged: 2017-01-05 07:46:04

166. [17092](http://github.com/cms-sw/cmssw/pull/17092){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca73 Correct the script and also the IsoTrackFilter cutoffs `alca`  created: 2016-12-21 21:19:49 merged: 2016-12-22 11:56:33

167. [17091](http://github.com/cms-sw/cmssw/pull/17091){:target="_blank"}  from **@makortel**: Fix crash in tracking MC validation plot scripts `dqm`  created: 2016-12-21 16:00:59 merged: 2017-01-10 11:40:09

168. [17087](http://github.com/cms-sw/cmssw/pull/17087){:target="_blank"}  from **@lgray**: Further performance improvement in BoostedTauSeeds `reconstruction`  created: 2016-12-21 02:37:25 merged: 2016-12-22 01:52:30

169. [17083](http://github.com/cms-sw/cmssw/pull/17083){:target="_blank"}  from **@felicepantaleo**: CA - Last hit quadruplet chi2 filter `reconstruction`  created: 2016-12-20 15:39:12 merged: 2016-12-21 10:39:17

170. [17082](http://github.com/cms-sw/cmssw/pull/17082){:target="_blank"}  from **@cms-l1t-offline**: Fix l1 fat event filters 90x bis - now use TCDS unpacked data for L1T `daq`  `hlt`  `l1`  `reconstruction`  created: 2016-12-20 15:14:37 merged: 2016-12-23 12:13:29

171. [17081](http://github.com/cms-sw/cmssw/pull/17081){:target="_blank"}  from **@ianna**: Add 2023 Geometry Scenario Version `visualization`  created: 2016-12-20 10:30:14 merged: 2017-01-08 01:36:14

172. [17080](http://github.com/cms-sw/cmssw/pull/17080){:target="_blank"}  from **@gartung**: EventFilter-EcalRawToDigi: fix clang warning hides overloaded virtual function `reconstruction`  created: 2016-12-19 18:25:29 merged: 2016-12-20 03:31:28

173. [17078](http://github.com/cms-sw/cmssw/pull/17078){:target="_blank"}  from **@calabria**: Fix ME0 neutron background normalization `simulation`  created: 2016-12-19 18:16:45 merged: 2016-12-21 01:16:50

174. [17076](http://github.com/cms-sw/cmssw/pull/17076){:target="_blank"}  from **@mtosi**: add Throughput client `dqm`  created: 2016-12-19 14:58:33 merged: 2017-01-10 11:40:47

175. [17075](http://github.com/cms-sw/cmssw/pull/17075){:target="_blank"}  from **@CTPPS**: CTPPS 3d pixel detid `simulation`  created: 2016-12-19 14:54:51 merged: 2017-01-18 10:12:23

176. [17074](http://github.com/cms-sw/cmssw/pull/17074){:target="_blank"}  from **@mtosi**: tracking DQM improvements `dqm`  `reconstruction`  created: 2016-12-19 13:34:58 merged: 2017-01-17 10:44:19

177. [17072](http://github.com/cms-sw/cmssw/pull/17072){:target="_blank"}  from **@ahinzmann**: Fix PUPPI MET tails `analysis`  `reconstruction`  created: 2016-12-19 12:34:56 merged: 2017-01-12 10:40:40

178. [17067](http://github.com/cms-sw/cmssw/pull/17067){:target="_blank"}  from **@ahinzmann**: Fix PUPPI lowPUCorr config 90X `analysis`  `reconstruction`  created: 2016-12-19 08:46:19 merged: 2016-12-30 08:07:31

179. [17066](http://github.com/cms-sw/cmssw/pull/17066){:target="_blank"}  from **@cms-AlCaDB**: [90X] update 2023 upgrade simulation Global Tag with SIM and RECO geometries tags `alca`  created: 2016-12-18 18:35:23 merged: 2017-01-10 23:48:42

180. [17065](http://github.com/cms-sw/cmssw/pull/17065){:target="_blank"}  from **@civanch**: Fixed warnings and printouts in SIM `simulation`  created: 2016-12-18 16:13:51 merged: 2016-12-19 08:18:20

181. [17064](http://github.com/cms-sw/cmssw/pull/17064){:target="_blank"}  from **@Dr15Jones**: Fix using unscheduled execution with a SubProcess `core`  created: 2016-12-17 03:11:50 merged: 2016-12-17 15:02:19

182. [17063](http://github.com/cms-sw/cmssw/pull/17063){:target="_blank"}  from **@slava77**: write a collection in JetTracksAssociatorAtCaloFace::produce before premature return `reconstruction`  created: 2016-12-17 01:15:32 merged: 2016-12-18 10:10:13

183. [17062](http://github.com/cms-sw/cmssw/pull/17062){:target="_blank"}  from **@ericvaandering**: Modernize python code in 9_0 `alca`  `core`  `db`  `dqm`  `hlt`  created: 2016-12-16 21:43:50 merged: 2016-12-18 10:10:11

184. [17060](http://github.com/cms-sw/cmssw/pull/17060){:target="_blank"}  from **@Dr15Jones**: Make TimeReport work properly with SubProcesses `core`  created: 2016-12-16 19:13:45 merged: 2016-12-16 21:03:51

185. [17057](http://github.com/cms-sw/cmssw/pull/17057){:target="_blank"}  from **@makortel**: Fix lostmidfrac in track MVA selection `reconstruction`  created: 2016-12-16 13:48:30 merged: 2016-12-23 12:13:58

186. [17056](http://github.com/cms-sw/cmssw/pull/17056){:target="_blank"}  from **@VinInn**: remove nonsense error along trajectory `reconstruction`  created: 2016-12-16 13:08:22 merged: 2016-12-20 03:31:47

187. [17054](http://github.com/cms-sw/cmssw/pull/17054){:target="_blank"}  from **@kpedro88**: SiPM pulse code cleanup `alca`  `simulation`  created: 2016-12-15 21:11:54 merged: 2016-12-21 10:43:17

188. [17053](http://github.com/cms-sw/cmssw/pull/17053){:target="_blank"}  from **@cms-l1t-offline**: Pr90x l1t integration (v89.20) Mu isolation perf, EG new vars, Gen in L1TNtuple  `l1`  `operations`  created: 2016-12-15 19:56:55 merged: 2016-12-18 10:10:59

189. [17051](http://github.com/cms-sw/cmssw/pull/17051){:target="_blank"}  from **@gartung**: CondFormat/EcalObjects/test: fix clang warning in test class `alca`  `db`  created: 2016-12-15 14:54:13 merged: 2016-12-21 11:26:06

190. [17050](http://github.com/cms-sw/cmssw/pull/17050){:target="_blank"}  from **@gartung**: Calibration/IsolatedPatricles: fix clang warning hides overloaded virtual function `alca`  created: 2016-12-15 14:42:06 merged: 2016-12-16 07:50:13

191. [17048](http://github.com/cms-sw/cmssw/pull/17048){:target="_blank"}  from **@cms-AlCaDB**: [90X] update MC Global Tags including latest ingredients as in Moriond17 campaign for run2, add new labels for e/gamma regressions and make pA queue more realistic `alca`  created: 2016-12-15 11:02:06 merged: 2016-12-16 09:38:43

192. [17042](http://github.com/cms-sw/cmssw/pull/17042){:target="_blank"}  from **@fwyzard**:  implement Eras for HLT (90x) (alternative approach) `hlt`  created: 2016-12-14 22:09:29 merged: 2016-12-28 09:15:03

193. [17040](http://github.com/cms-sw/cmssw/pull/17040){:target="_blank"}  from **@lgray**: Speed improvements for TauJetRegionProducer `reconstruction`  created: 2016-12-14 19:00:24 merged: 2016-12-21 01:17:12

194. [17039](http://github.com/cms-sw/cmssw/pull/17039){:target="_blank"}  from **@gartung**: RecoLocalTracker/SiPixelClusterizer/test: fix clang warnings in test classes `reconstruction`  created: 2016-12-14 16:37:46 merged: 2016-12-16 07:50:22

195. [17038](http://github.com/cms-sw/cmssw/pull/17038){:target="_blank"}  from **@gartung**: SLHCUpgradeSimulations/Geometry/test fix clang warning hides overloaded virtual `geometry`  created: 2016-12-14 15:00:17 merged: 2016-12-15 16:06:40

196. [17037](http://github.com/cms-sw/cmssw/pull/17037){:target="_blank"}  from **@mariadalfonso**: HBHE: use proper quantization noise in the M2 `reconstruction`  created: 2016-12-14 14:24:03 merged: 2016-12-23 12:14:57

197. [17031](http://github.com/cms-sw/cmssw/pull/17031){:target="_blank"}  from **@gartung**: RecoParticleFlow/PFTracking/test: fix clang warnings in test classes `reconstruction`  created: 2016-12-14 04:24:54 merged: 2016-12-16 07:50:30

198. [17028](http://github.com/cms-sw/cmssw/pull/17028){:target="_blank"}  from **@gartung**: DQMOffline/L1Trigger: fix clang warning hides overloaded virtual `dqm`  `l1`  created: 2016-12-14 04:11:11 merged: 2016-12-16 07:50:38

199. [17027](http://github.com/cms-sw/cmssw/pull/17027){:target="_blank"}  from **@gartung**: HLTriggerOffline/Exotica: fix clang warnings `dqm`  created: 2016-12-14 03:58:34 merged: 2016-12-21 11:20:50

200. [17026](http://github.com/cms-sw/cmssw/pull/17026){:target="_blank"}  from **@gartung**: EventFilter/CastorRawToDigi: fix clang warning by moving `reconstruction`  created: 2016-12-14 03:53:21 merged: 2016-12-16 07:50:48

201. [17025](http://github.com/cms-sw/cmssw/pull/17025){:target="_blank"}  from **@gartung**: HLTrigger/HLTanalyzers: fix clang warning by `hlt`  created: 2016-12-14 03:50:00 merged: 2016-12-14 11:20:06

202. [17023](http://github.com/cms-sw/cmssw/pull/17023){:target="_blank"}  from **@gartung**: Validation/CaloTowers: fix clang warning hides overloaded virtual `dqm`  created: 2016-12-14 03:36:55 merged: 2016-12-15 18:36:38

203. [17022](http://github.com/cms-sw/cmssw/pull/17022){:target="_blank"}  from **@gartung**: DQMOffline/Hcal: fix clang warning hides overloaded virtual `dqm`  created: 2016-12-14 03:32:43 merged: 2016-12-15 18:36:13

204. [17021](http://github.com/cms-sw/cmssw/pull/17021){:target="_blank"}  from **@gartung**: RecoJets/JetProducers: fix clang warning hides overloaded virtual `reconstruction`  created: 2016-12-14 03:32:24 merged: 2016-12-16 07:51:03

205. [17020](http://github.com/cms-sw/cmssw/pull/17020){:target="_blank"}  from **@gartung**: PhysicsTools/JetMCAlgos: fix clang warning hides overloaded virtual `analysis`  created: 2016-12-14 03:23:51 merged: 2016-12-20 03:34:28

206. [17019](http://github.com/cms-sw/cmssw/pull/17019){:target="_blank"}  from **@gartung**: DPGAnalysis/Skims: fix clang warning hides overloaded virtual `pdmv`  created: 2016-12-14 03:15:00 merged: 2016-12-14 14:55:29

207. [17018](http://github.com/cms-sw/cmssw/pull/17018){:target="_blank"}  from **@gartung**: DPGAnalysis/SiStripTool: fix clang warnings hides overloaded virtual `analysis`  created: 2016-12-14 03:14:42 merged: 2016-12-20 03:33:57

208. [17017](http://github.com/cms-sw/cmssw/pull/17017){:target="_blank"}  from **@gartung**: PhysicsTools/IsolationUtils: fix clang warning hides overloaded virtual function `analysis`  created: 2016-12-14 03:14:26 merged: 2016-12-21 10:43:42

209. [17016](http://github.com/cms-sw/cmssw/pull/17016){:target="_blank"}  from **@cms-l1t-offline**: 90x L1T - remove an external data file `l1`  created: 2016-12-14 02:11:35 merged: 2016-12-14 07:14:53

210. [17015](http://github.com/cms-sw/cmssw/pull/17015){:target="_blank"}  from **@gartung**: DQM-HcalCommon+HcalTasks: fix clang warnings hides overloaded virtual function `dqm`  created: 2016-12-13 21:38:50 merged: 2017-01-27 21:18:53

211. [17014](http://github.com/cms-sw/cmssw/pull/17014){:target="_blank"}  from **@gartung**: EgammaAnalysis/ElectronTools: potential bug fix, add parens to set implied order of + and ? `analysis`  created: 2016-12-13 19:39:42 merged: 2017-01-05 07:47:09

212. [17011](http://github.com/cms-sw/cmssw/pull/17011){:target="_blank"}  from **@gartung**: DQM/EcalCommon: fix clang warnings about hides overloaded virtual `dqm`  created: 2016-12-13 19:05:45 merged: 2016-12-16 21:04:07

213. [17010](http://github.com/cms-sw/cmssw/pull/17010){:target="_blank"}  from **@lgray**: Remove unit tests for HGCalRecProducers (covered by matrix now) `reconstruction`  created: 2016-12-13 18:19:26 merged: 2016-12-14 15:10:44

214. [17009](http://github.com/cms-sw/cmssw/pull/17009){:target="_blank"}  from **@gartung**: RecoParticleFlow/Benchmark: fix clang warning about hides overloaded virtual `reconstruction`  created: 2016-12-13 18:09:15 merged: 2016-12-16 07:52:23

215. [17008](http://github.com/cms-sw/cmssw/pull/17008){:target="_blank"}  from **@gartung**: EventFilter/EcalTBRawToDigi: fix clang warnings about hides overloaded virtual function `reconstruction`  created: 2016-12-13 17:33:49 merged: 2016-12-16 07:52:08

216. [17007](http://github.com/cms-sw/cmssw/pull/17007){:target="_blank"}  from **@dan131riley**: reduce input tag memory churn by passing correct type constant to tokenize `core`  created: 2016-12-13 16:52:54 merged: 2016-12-14 11:20:29

217. [17006](http://github.com/cms-sw/cmssw/pull/17006){:target="_blank"}  from **@dan131riley**: Re-raise signals received after InitRootHandlers has been unloaded `core`  created: 2016-12-13 16:18:37 merged: 2016-12-14 11:20:52

218. [16999](http://github.com/cms-sw/cmssw/pull/16999){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx71 Update all validation code in view of BH changes `dqm`  created: 2016-12-13 02:28:40 merged: 2017-01-12 00:40:13

219. [16997](http://github.com/cms-sw/cmssw/pull/16997){:target="_blank"}  from **@lgray**: Speedups to HGCal clustering `reconstruction`  created: 2016-12-13 00:16:12 merged: 2016-12-22 11:55:48

220. [16996](http://github.com/cms-sw/cmssw/pull/16996){:target="_blank"}  from **@gartung**: RecoLocalCalo/CastorReco fix clang warnings `reconstruction`  created: 2016-12-12 22:57:05 merged: 2016-12-14 07:15:45

221. [16995](http://github.com/cms-sw/cmssw/pull/16995){:target="_blank"}  from **@gartung**: HcalTBObjectUnpacker fix clang warning `reconstruction`  created: 2016-12-12 22:50:07 merged: 2016-12-14 07:16:03

222. [16994](http://github.com/cms-sw/cmssw/pull/16994){:target="_blank"}  from **@gartung**: RecoTauTag/ImpactParameter/test fix clang warning `reconstruction`  created: 2016-12-12 22:45:54 merged: 2016-12-16 07:51:46

223. [16993](http://github.com/cms-sw/cmssw/pull/16993){:target="_blank"}  from **@gartung**: RecoTracker test classes: fix clang warnings `reconstruction`  created: 2016-12-12 22:39:15 merged: 2016-12-16 19:15:33

224. [16991](http://github.com/cms-sw/cmssw/pull/16991){:target="_blank"}  from **@gartung**: SUSYBSMAnalysis/HSCP: potential bug beginJob can be called; addition of parens `analysis`  created: 2016-12-12 22:30:12 merged: 2016-12-14 07:16:58

225. [16990](http://github.com/cms-sw/cmssw/pull/16990){:target="_blank"}  from **@gartung**: Validation/GlobalRecHits: fix clang warning about using std `dqm`  created: 2016-12-12 22:21:08 merged: 2016-12-15 11:12:59

226. [16989](http://github.com/cms-sw/cmssw/pull/16989){:target="_blank"}  from **@gartung**: Validation/Mixing: fix clang warning vexing parse `dqm`  created: 2016-12-12 22:16:57 merged: 2016-12-16 07:51:38

227. [16988](http://github.com/cms-sw/cmssw/pull/16988){:target="_blank"}  from **@gartung**: Validation/MuonRPCGeometry: potential bug beginJob might be called `geometry`  created: 2016-12-12 22:16:27 merged: 2016-12-14 07:17:28

228. [16987](http://github.com/cms-sw/cmssw/pull/16987){:target="_blank"}  from **@gartung**: Validation/RecoEgamma: potential bug endRun can be called `dqm`  created: 2016-12-12 22:09:03 merged: 2016-12-15 18:33:23

229. [16983](http://github.com/cms-sw/cmssw/pull/16983){:target="_blank"}  from **@gartung**: CalibCalorimetry/HcalAlgos/test fix clang warning hides overloaded virtual function `alca`  created: 2016-12-12 21:01:59 merged: 2017-01-08 20:00:34

230. [16982](http://github.com/cms-sw/cmssw/pull/16982){:target="_blank"}  from **@gartung**: Validation/RecoMuon: potential bug endRun now called after changing parameters `dqm`  created: 2016-12-12 20:42:22 merged: 2016-12-15 18:32:53

231. [16981](http://github.com/cms-sw/cmssw/pull/16981){:target="_blank"}  from **@civanch**: Cosmetic cleanup SIM interface to field `simulation`  created: 2016-12-12 20:11:52 merged: 2016-12-19 08:18:50

232. [16980](http://github.com/cms-sw/cmssw/pull/16980){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca71 Correct the IsoTrackkanalyzer and associated macros `alca`  created: 2016-12-12 19:16:15 merged: 2016-12-14 15:02:29

233. [16979](http://github.com/cms-sw/cmssw/pull/16979){:target="_blank"}  from **@ikrav**: EGM-certified electron IDs for 2016 data: cut-based and MVA `reconstruction`  created: 2016-12-12 19:13:26 merged: 2016-12-29 08:04:18

234. [16976](http://github.com/cms-sw/cmssw/pull/16976){:target="_blank"}  from **@gartung**: RecoTracker/DebugTools: bug fix beginRun not called because of incorrect parameters `reconstruction`  created: 2016-12-12 17:48:46 merged: 2016-12-21 11:32:23

235. [16973](http://github.com/cms-sw/cmssw/pull/16973){:target="_blank"}  from **@schneiml**: Make the online DQM fileinputsource more intelligent `dqm`  created: 2016-12-12 09:58:15 merged: 2017-01-10 11:42:21

236. [16971](http://github.com/cms-sw/cmssw/pull/16971){:target="_blank"}  from **@boudoul**: Making Phase2 T2 (and 2023D2) more realistic [using Pixel phase2 rather than a la Phase1] - Renamed as T4 and 2023D10 Resp. `geometry`  `l1`  `operations`  `pdmv`  `reconstruction`  `visualization`  created: 2016-12-11 21:14:48 merged: 2016-12-18 17:37:48

237. [16944](http://github.com/cms-sw/cmssw/pull/16944){:target="_blank"}  from **@anorkus**: Change to use pythia8 gen_fragment as pythia6 one was deleted `dqm`  created: 2016-12-09 13:19:39 merged: 2016-12-13 20:55:06

238. [16938](http://github.com/cms-sw/cmssw/pull/16938){:target="_blank"}  from **@gartung**: Reco*: fix bug because of misplaced parens; fix clang warnings about abs `analysis`  `hlt`  `reconstruction`  created: 2016-12-08 23:33:53 merged: 2016-12-14 15:07:04

239. [16934](http://github.com/cms-sw/cmssw/pull/16934){:target="_blank"}  from **@gartung**: L1Trigger: fix clang warnings about abs `l1`  created: 2016-12-08 23:24:27 merged: 2016-12-14 07:32:13

240. [16921](http://github.com/cms-sw/cmssw/pull/16921){:target="_blank"}  from **@gartung**: CondFormats-SiPixelObjects fix clang warnings about abs and mismatched tags `alca`  `db`  created: 2016-12-08 22:30:00 merged: 2017-01-06 07:39:27

241. [16916](http://github.com/cms-sw/cmssw/pull/16916){:target="_blank"}  from **@gartung**: CondTool/DT fix clang warning  -Wabsolute-value `db`  created: 2016-12-08 20:46:16 merged: 2016-12-21 11:32:52

242. [16913](http://github.com/cms-sw/cmssw/pull/16913){:target="_blank"}  from **@Sam-Harper**: HEEP V7.0 in 90X `analysis`  `reconstruction`  created: 2016-12-08 17:24:00 merged: 2017-01-06 07:38:04

243. [16911](http://github.com/cms-sw/cmssw/pull/16911){:target="_blank"}  from **@makortel**: Replace trackingPhase1PU70 workflows with CA seeding `dqm`  `operations`  `pdmv`  `reconstruction`  created: 2016-12-08 14:30:26 merged: 2016-12-16 14:52:18

244. [16901](http://github.com/cms-sw/cmssw/pull/16901){:target="_blank"}  from **@lgray**: Fast timing layer RecHits and event display `geometry`  `operations`  `reconstruction`  `visualization`  created: 2016-12-07 16:42:24 merged: 2016-12-30 08:19:21

245. [16898](http://github.com/cms-sw/cmssw/pull/16898){:target="_blank"}  from **@mmusich**: [90X] PV-Validation for phase-I `alca`  created: 2016-12-07 15:52:54 merged: 2017-01-17 10:11:23

246. [16875](http://github.com/cms-sw/cmssw/pull/16875){:target="_blank"}  from **@schneiml**: Phase1 Pixel DQM Histogram Reorganisation `dqm`  created: 2016-12-05 17:24:32 merged: 2016-12-14 07:50:51

247. [16849](http://github.com/cms-sw/cmssw/pull/16849){:target="_blank"}  from **@kskovpen**: Muon SIM filter `simulation`  created: 2016-12-04 12:08:51 merged: 2016-12-29 07:56:31

248. [16845](http://github.com/cms-sw/cmssw/pull/16845){:target="_blank"}  from **@Dr15Jones**: Phase 2 of the multi-threaded framework `core`  `simulation`  created: 2016-12-02 19:52:04 merged: 2016-12-16 14:59:29

249. [16828](http://github.com/cms-sw/cmssw/pull/16828){:target="_blank"}  from **@dildick**: Consumes interface for MCMultiParticleFilter `generators`  created: 2016-12-01 00:43:19 merged: 2017-01-17 10:10:22

250. [16794](http://github.com/cms-sw/cmssw/pull/16794){:target="_blank"}  from **@cms-l1t-offline**: pr90x L1T GT packer of ExternalConditions `l1`  `operations`  created: 2016-11-29 15:31:17 merged: 2016-12-14 15:08:44

251. [16792](http://github.com/cms-sw/cmssw/pull/16792){:target="_blank"}  from **@makortel**: Transform pixel track fitter, filter, and cleaner to ED or ES products `alca`  `dqm`  `fastsim`  `hlt`  `reconstruction`  created: 2016-11-29 14:01:51 merged: 2016-12-15 08:45:27

252. [16749](http://github.com/cms-sw/cmssw/pull/16749){:target="_blank"}  from **@ghellwig**: [90X] Geometry independent SiPixelAli PCL `alca`  created: 2016-11-24 11:27:10 merged: 2017-01-10 23:40:58

253. [16739](http://github.com/cms-sw/cmssw/pull/16739){:target="_blank"}  from **@jfernan2**: Changes to disable DDU trigger plots in DT DQM Online Trigger checks  `dqm`  `reconstruction`  created: 2016-11-23 08:58:42 merged: 2017-02-01 15:45:38

254. [16664](http://github.com/cms-sw/cmssw/pull/16664){:target="_blank"}  from **@kkotov**: Adding L1T O2O parsing for the EMTF + taking CaloParams prototype from the CondDB `db`  `l1`  created: 2016-11-16 18:39:04 merged: 2017-01-20 18:00:07

255. [16638](http://github.com/cms-sw/cmssw/pull/16638){:target="_blank"}  from **@fthyssen**: RPC TwinMux and OMTF/CPPF unpacker conditions `alca`  `db`  created: 2016-11-16 09:49:50 merged: 2017-02-01 16:23:52

256. [16621](http://github.com/cms-sw/cmssw/pull/16621){:target="_blank"}  from **@echapon**: Allow a boost on particles in MCParticlePairFilter `generators`  created: 2016-11-16 09:45:10 merged: 2017-01-17 10:33:32

257. [16598](http://github.com/cms-sw/cmssw/pull/16598){:target="_blank"}  from **@nancymarinelli**: Tp phase ii v0 `l1`  `simulation`  created: 2016-11-16 09:38:55 merged: 2017-01-25 16:32:01

#### CMSDIST Changes between Tags REL/CMSSW_8_2_0_patch1/slc6_amd64_gcc530 and REL/CMSSW_8_3_0/slc6_amd64_gcc530:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_2_0_patch1/slc6_amd64_gcc530...REL/CMSSW_8_3_0/slc6_amd64_gcc530)



1. [2789](http://github.com/cms-sw/cmsdist/pull/2789){:target="_blank"}  from **@iahmad-khan**: updates to version V02-00-03 created: 2017-01-25 20:46:44 merged: 2017-01-26 12:13:16

2. [2787](http://github.com/cms-sw/cmsdist/pull/2787){:target="_blank"}  from **@cms-sw**: Update data-L1Trigger-L1THGCal tag V01-00-02 created: 2017-01-24 08:36:15 merged: 2017-01-26 12:15:16

3. [2783](http://github.com/cms-sw/cmsdist/pull/2783){:target="_blank"}  from **@iahmad-khan**: updates data-RecoBTag-Combined to version v01-00-03 created: 2017-01-20 14:02:05 merged: 2017-01-23 14:24:15

4. [2780](http://github.com/cms-sw/cmsdist/pull/2780){:target="_blank"}  from **@cms-sw**: backport compile_commands.json changes to gcc620 branch created: 2017-01-19 16:43:41 merged: 2017-01-19 21:24:11

5. [2774](http://github.com/cms-sw/cmsdist/pull/2774){:target="_blank"}  from **@smuzaffar**: added psutils for 90X gcc530 IBs created: 2017-01-17 09:23:44 merged: 2017-01-17 09:57:57

6. [2773](http://github.com/cms-sw/cmsdist/pull/2773){:target="_blank"}  from **@smuzaffar**: New lightweight classes to apply a trained neural net (lwtnn) created: 2017-01-17 09:12:01 merged: 2017-01-17 21:38:55

7. [2768](http://github.com/cms-sw/cmsdist/pull/2768){:target="_blank"}  from **@cms-sw**: Update root to 6.08.02 in 90X created: 2017-01-16 15:06:27 merged: 2017-01-17 06:35:28

8. [2767](http://github.com/cms-sw/cmsdist/pull/2767){:target="_blank"}  from **@cms-sw**: update py2-sqlalchemy to 1.1.4 created: 2017-01-16 14:48:13 merged: 2017-01-17 20:49:55

9. [2765](http://github.com/cms-sw/cmsdist/pull/2765){:target="_blank"}  from **@cms-sw**: Fix workflow 534.0 crash for gcc >= 6 created: 2017-01-12 21:58:01 merged: 2017-01-12 21:59:26

10. [2748](http://github.com/cms-sw/cmsdist/pull/2748){:target="_blank"}  from **@mharrend**: Herwig7: Changed include directive in toolfile created: 2016-12-20 16:57:55 merged: 2017-01-12 22:09:59

11. [2745](http://github.com/cms-sw/cmsdist/pull/2745){:target="_blank"}  from **@TaiSakuma**: update pandas version to 0.19.1 for 9_0_X created: 2016-12-16 16:15:56 merged: 2016-12-21 11:01:59

12. [2732](http://github.com/cms-sw/cmsdist/pull/2732){:target="_blank"}  from **@iahmad-khan**: updates SLHCUpgradeSimulations-Geometry to use new tag V01-00-04 created: 2016-12-12 09:19:21 merged: 2016-12-21 11:03:29
