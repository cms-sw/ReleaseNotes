---
layout: post
rel_link:  "10_0_0_pre2"
title:  "CMSSW_10_0_0_pre2"
date:   2017-12-07 21:58:31
categories: cmssw
relmajor: 10
relminor: 0
relsubminor: 0
relpre: _pre2
---

# CMSSW_10_0_0_pre2
#### Changes since CMSSW_10_0_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_10_0_0_pre1...CMSSW_10_0_0_pre2)



1. [21654](http://github.com/cms-sw/cmssw/pull/21654){:target="_blank"}  from **@davidlange6**: avoid PI.h `generators`  created: 2017-12-06 16:18:59 merged: 2017-12-07 12:40:56

2. [21648](http://github.com/cms-sw/cmssw/pull/21648){:target="_blank"}  from **@makortel**: Fix cmsDriver exception message when --conditions is not given `operations`  created: 2017-12-05 16:14:04 merged: 2017-12-06 10:43:29

3. [21647](http://github.com/cms-sw/cmssw/pull/21647){:target="_blank"}  from **@arunhep**: [10.0.X] GT Updates : PhaseII GT updated with the new Jet Energy Corrections `alca`  created: 2017-12-05 11:39:38 merged: 2017-12-05 19:55:49

4. [21642](http://github.com/cms-sw/cmssw/pull/21642){:target="_blank"}  from **@alja**: Fireworks: increase span of energy scale in lego view `visualization`  created: 2017-12-04 20:10:54 merged: 2017-12-05 09:45:50

5. [21641](http://github.com/cms-sw/cmssw/pull/21641){:target="_blank"}  from **@Dr15Jones**: Changed a static to be atomic to fix a thread-safety issue `generators`  created: 2017-12-04 18:30:20 merged: 2017-12-07 12:41:17

6. [21638](http://github.com/cms-sw/cmssw/pull/21638){:target="_blank"}  from **@kreczko**: [10X] added exception (on failed write) to reco::details::loadTMVAWeights `analysis`  `reconstruction`  created: 2017-12-04 14:38:47 merged: 2017-12-06 10:43:10

7. [21636](http://github.com/cms-sw/cmssw/pull/21636){:target="_blank"}  from **@igv4321**: Adding special treatment for QIE10/QIE11 TDC values 50 to 57 `reconstruction`  created: 2017-12-03 09:27:06 merged: 2017-12-07 12:54:49

8. [21635](http://github.com/cms-sw/cmssw/pull/21635){:target="_blank"}  from **@Dr15Jones**: Removed calls to TH1::SetBit since they are not intended for users `dqm`  created: 2017-12-02 14:55:59 merged: 2017-12-03 13:14:38

9. [21634](http://github.com/cms-sw/cmssw/pull/21634){:target="_blank"}  from **@Dr15Jones**: Fix order of destructor calls `core`  created: 2017-12-02 14:09:03 merged: 2017-12-03 13:14:58

10. [21633](http://github.com/cms-sw/cmssw/pull/21633){:target="_blank"}  from **@Dr15Jones**: Make using ROOT's ImplicitMT the default `core`  created: 2017-12-01 20:06:25 merged: 2017-12-02 07:55:10

11. [21631](http://github.com/cms-sw/cmssw/pull/21631){:target="_blank"}  from **@cms-tau-pog**: Code cleanup in TauPOG repositories + a fix that falls back to gsfTracks for leading charged candidates for which kftTracks are not available `reconstruction`  created: 2017-12-01 17:31:49 merged: 2017-12-06 10:42:35

12. [21629](http://github.com/cms-sw/cmssw/pull/21629){:target="_blank"}  from **@VinInn**: remove TrajectoryCleanerBySharedSeeds `reconstruction`  created: 2017-12-01 15:47:04 merged: 2017-12-03 13:14:21

13. [21626](http://github.com/cms-sw/cmssw/pull/21626){:target="_blank"}  from **@fabozzi**: Updates to NANOAOD workflows in the matrix `operations`  `pdmv`  `upgrade`  created: 2017-12-01 14:38:43 merged: 2017-12-04 08:50:42

14. [21623](http://github.com/cms-sw/cmssw/pull/21623){:target="_blank"}  from **@Dr15Jones**: Added framework transition test `core`  created: 2017-11-30 22:12:54 merged: 2017-12-01 12:21:22

15. [21619](http://github.com/cms-sw/cmssw/pull/21619){:target="_blank"}  from **@Teemperor**: Make DQM headers compile with C++ modules. `dqm`  created: 2017-11-30 14:21:09 merged: 2017-12-01 07:40:54

16. [21614](http://github.com/cms-sw/cmssw/pull/21614){:target="_blank"}  from **@Teemperor**: Added include for cmath to GammaZInterference.h `analysis`  created: 2017-11-30 10:43:24 merged: 2017-12-01 07:46:04

17. [21613](http://github.com/cms-sw/cmssw/pull/21613){:target="_blank"}  from **@Teemperor**: Added include to FSimTrack.h to FSimTrackEqual.h `fastsim`  created: 2017-11-30 10:43:15 merged: 2017-12-01 15:51:51

18. [21612](http://github.com/cms-sw/cmssw/pull/21612){:target="_blank"}  from **@Teemperor**: Also fwd declare TGLViewerBase in CmsAnnotation.h `visualization`  created: 2017-11-30 10:43:09 merged: 2017-12-01 07:47:42

19. [21610](http://github.com/cms-sw/cmssw/pull/21610){:target="_blank"}  from **@Teemperor**: Also fwd declare TGLCheckButton in CmsShowModelPopuph `visualization`  created: 2017-11-30 10:42:58 merged: 2017-12-01 07:40:32

20. [21609](http://github.com/cms-sw/cmssw/pull/21609){:target="_blank"}  from **@Teemperor**: Fixed typo in FWMuonBuilder.h `visualization`  created: 2017-11-30 10:42:52 merged: 2017-12-01 07:25:51

21. [21608](http://github.com/cms-sw/cmssw/pull/21608){:target="_blank"}  from **@Teemperor**: Also fwd declare TEveCaloDat in FWECALCaloDataDetailViewBuilder.h `visualization`  created: 2017-11-30 10:42:45 merged: 2017-12-01 07:25:59

22. [21607](http://github.com/cms-sw/cmssw/pull/21607){:target="_blank"}  from **@Teemperor**: Added header guards to FWECALDetailViewBuilder.h `visualization`  created: 2017-11-30 10:42:37 merged: 2017-12-01 07:47:57

23. [21606](http://github.com/cms-sw/cmssw/pull/21606){:target="_blank"}  from **@Teemperor**: Also fwd declare TEveJetCone in makeEveJetCone.h `visualization`  created: 2017-11-30 10:41:35 merged: 2017-12-01 07:26:08

24. [21605](http://github.com/cms-sw/cmssw/pull/21605){:target="_blank"}  from **@Teemperor**: Include TEveVector.h in FWPFMaths.h `visualization`  created: 2017-11-30 10:41:28 merged: 2017-12-01 07:48:14

25. [21604](http://github.com/cms-sw/cmssw/pull/21604){:target="_blank"}  from **@Teemperor**: Include set in TrackUtils.h `visualization`  created: 2017-11-30 10:41:23 merged: 2017-12-01 07:26:16

26. [21603](http://github.com/cms-sw/cmssw/pull/21603){:target="_blank"}  from **@Teemperor**: Include string in Pythia6Declarations.h `generators`  created: 2017-11-30 10:41:17 merged: 2017-12-07 12:57:20

27. [21601](http://github.com/cms-sw/cmssw/pull/21601){:target="_blank"}  from **@Teemperor**: Added include for cmath to TopQuarkAnalysis/TopObjectResolutions `analysis`  created: 2017-11-30 10:41:01 merged: 2017-12-01 07:29:56

28. [21600](http://github.com/cms-sw/cmssw/pull/21600){:target="_blank"}  from **@Teemperor**: Added missing includes to HLTL1TSeed.h `hlt`  created: 2017-11-30 10:40:55 merged: 2017-12-01 12:18:56

29. [21599](http://github.com/cms-sw/cmssw/pull/21599){:target="_blank"}  from **@Teemperor**: Added include for Event.h to HLTMuonL2ToL1Map.h `hlt`  created: 2017-11-30 10:40:50 merged: 2017-12-01 12:19:26

30. [21598](http://github.com/cms-sw/cmssw/pull/21598){:target="_blank"}  from **@Teemperor**: Added missing includes to HLTMuonL2ToL1TMap.h `hlt`  created: 2017-11-30 10:40:44 merged: 2017-12-01 12:19:38

31. [21597](http://github.com/cms-sw/cmssw/pull/21597){:target="_blank"}  from **@Teemperor**: Added include for ParameterSet to SimpleCutsIsolator.h `reconstruction`  created: 2017-11-30 10:40:38 merged: 2017-12-01 12:19:47

32. [21596](http://github.com/cms-sw/cmssw/pull/21596){:target="_blank"}  from **@Teemperor**: Added include for MuonFwd.h to HLTrigger/Muon `hlt`  created: 2017-11-30 10:40:33 merged: 2017-12-01 12:19:57

33. [21595](http://github.com/cms-sw/cmssw/pull/21595){:target="_blank"}  from **@Teemperor**: Actually include TBuffer.h in CustomStreamer.h `core`  created: 2017-11-30 10:40:27 merged: 2017-12-01 07:29:34

34. [21594](http://github.com/cms-sw/cmssw/pull/21594){:target="_blank"}  from **@Teemperor**: Added missing includes to vmac.h `l1`  created: 2017-11-30 10:40:22 merged: 2017-12-06 10:47:00

35. [21593](http://github.com/cms-sw/cmssw/pull/21593){:target="_blank"}  from **@Teemperor**: Don't include inside a namespace in Common.h `l1`  created: 2017-11-30 10:40:16 merged: 2017-12-01 15:52:20

36. [21592](http://github.com/cms-sw/cmssw/pull/21592){:target="_blank"}  from **@Teemperor**: Added include for EvtComplex to EvtSLBaryonAmp.hh `generators`  created: 2017-11-30 10:40:10 merged: 2017-12-07 12:41:28

37. [21590](http://github.com/cms-sw/cmssw/pull/21590){:target="_blank"}  from **@Teemperor**: Add header guards to PhysicsTools/FWLite headers `analysis`  created: 2017-11-30 10:39:53 merged: 2017-12-01 10:31:06

38. [21589](http://github.com/cms-sw/cmssw/pull/21589){:target="_blank"}  from **@Teemperor**: Add include for string to JetSelection.h `analysis`  `reconstruction`  created: 2017-11-30 10:39:48 merged: 2017-12-03 13:12:45

39. [21588](http://github.com/cms-sw/cmssw/pull/21588){:target="_blank"}  from **@Teemperor**: Added include for IsolationProducer.h to CalIsolationExtrapolate.h `analysis`  created: 2017-11-30 10:39:43 merged: 2017-12-01 15:52:33

40. [21587](http://github.com/cms-sw/cmssw/pull/21587){:target="_blank"}  from **@Teemperor**: Added missing includes to BinomialProbHelper.h `analysis`  created: 2017-11-30 10:39:37 merged: 2017-12-01 12:26:33

41. [21586](http://github.com/cms-sw/cmssw/pull/21586){:target="_blank"}  from **@Teemperor**: Added include for SuperClusterFwd.h to ConversionTrackCandidateProduc `reconstruction`  created: 2017-11-30 10:39:31 merged: 2017-12-03 15:04:04

42. [21585](http://github.com/cms-sw/cmssw/pull/21585){:target="_blank"}  from **@Teemperor**: Added include for CaloTowerDefs.h to EgammaHLTCaloTowerProducer.h `hlt`  created: 2017-11-30 10:39:24 merged: 2017-12-01 12:20:12

43. [21584](http://github.com/cms-sw/cmssw/pull/21584){:target="_blank"}  from **@Teemperor**: Added missing includes to EgammaHLTPixelMatchParamObjects.h `hlt`  created: 2017-11-30 10:39:19 merged: 2017-12-01 12:20:22

44. [21583](http://github.com/cms-sw/cmssw/pull/21583){:target="_blank"}  from **@Teemperor**: Added include for SuperClusterFwd.h to EgammaHLTRecoEcalCandidateProd `hlt`  created: 2017-11-30 10:39:13 merged: 2017-12-01 12:20:33

45. [21582](http://github.com/cms-sw/cmssw/pull/21582){:target="_blank"}  from **@Teemperor**: Added missing include to EgammaHLTTimeCleanedRechitProducer.h `hlt`  created: 2017-11-30 10:39:07 merged: 2017-12-01 12:21:12

46. [21581](http://github.com/cms-sw/cmssw/pull/21581){:target="_blank"}  from **@Teemperor**: Added missing includes to HLTRechitInRegionsProducer.h `hlt`  created: 2017-11-30 10:39:00 merged: 2017-12-01 12:26:15

47. [21580](http://github.com/cms-sw/cmssw/pull/21580){:target="_blank"}  from **@Teemperor**: Added missing fftjet includes to ScaleCalculators.h `reconstruction`  created: 2017-11-30 10:38:55 merged: 2017-12-02 07:54:49

48. [21579](http://github.com/cms-sw/cmssw/pull/21579){:target="_blank"}  from **@Teemperor**: Added include for vector to MyCluster.h `reconstruction`  created: 2017-11-30 10:38:49 merged: 2017-12-02 09:11:47

49. [21578](http://github.com/cms-sw/cmssw/pull/21578){:target="_blank"}  from **@Teemperor**: Added include for cmath to CaloRecHitResolutionProvider.h `reconstruction`  created: 2017-11-30 10:38:44 merged: 2017-12-02 07:54:33

50. [21577](http://github.com/cms-sw/cmssw/pull/21577){:target="_blank"}  from **@Teemperor**: Added include for cmath to Cluster1DCleaner.h `reconstruction`  created: 2017-11-30 10:38:37 merged: 2017-12-02 07:54:22

51. [21576](http://github.com/cms-sw/cmssw/pull/21576){:target="_blank"}  from **@Teemperor**: Added include for Point3D.h to Cluster1DMerger.h `reconstruction`  created: 2017-11-30 10:38:32 merged: 2017-12-02 07:54:16

52. [21575](http://github.com/cms-sw/cmssw/pull/21575){:target="_blank"}  from **@Teemperor**: Added include for vector to FindPeakFastPV.h `reconstruction`  created: 2017-11-30 10:38:26 merged: 2017-12-02 07:54:03

53. [21574](http://github.com/cms-sw/cmssw/pull/21574){:target="_blank"}  from **@Teemperor**: Added missing include to CaloTowerCreatorForTauHLT.h `hlt`  created: 2017-11-30 10:38:20 merged: 2017-12-01 12:25:53

54. [21573](http://github.com/cms-sw/cmssw/pull/21573){:target="_blank"}  from **@Teemperor**: Added missing include to CaloTowerFromL1TCreatorForTauHLT.h `hlt`  created: 2017-11-30 10:38:14 merged: 2017-12-01 12:25:37

55. [21572](http://github.com/cms-sw/cmssw/pull/21572){:target="_blank"}  from **@Teemperor**: Added missing include to TTHelpers.h `reconstruction`  created: 2017-11-30 10:38:08 merged: 2017-12-03 13:12:36

56. [21571](http://github.com/cms-sw/cmssw/pull/21571){:target="_blank"}  from **@Teemperor**: Added missing include to EcalTrigPrimFunctionalAlgo.h `l1`  created: 2017-11-30 10:38:01 merged: 2017-12-06 10:48:15

57. [21570](http://github.com/cms-sw/cmssw/pull/21570){:target="_blank"}  from **@Teemperor**: Added include to ostream to IOIsWritable.hh `alca`  created: 2017-11-30 10:36:00 merged: 2017-12-01 08:00:23

58. [21569](http://github.com/cms-sw/cmssw/pull/21569){:target="_blank"}  from **@Teemperor**: Added header guards to FillInfo.h `alca`  `db`  created: 2017-11-30 10:35:53 merged: 2017-12-07 13:02:50

59. [21568](http://github.com/cms-sw/cmssw/pull/21568){:target="_blank"}  from **@Teemperor**: Added include to Eigen to ReferenceTrajectoryBase.h `alca`  created: 2017-11-30 10:34:39 merged: 2017-12-01 08:04:25

60. [21567](http://github.com/cms-sw/cmssw/pull/21567){:target="_blank"}  from **@Teemperor**: Added missing includes PixelAliasList.H `alca`  created: 2017-11-30 10:34:33 merged: 2017-12-01 08:01:16

61. [21566](http://github.com/cms-sw/cmssw/pull/21566){:target="_blank"}  from **@Teemperor**: Added include to unistd to PixelConfigFile `alca`  created: 2017-11-30 10:34:27 merged: 2017-12-01 16:34:58

62. [21565](http://github.com/cms-sw/cmssw/pull/21565){:target="_blank"}  from **@Teemperor**: Added missing includes to PixelConfigList.h `alca`  created: 2017-11-30 10:34:20 merged: 2017-12-01 12:25:29

63. [21564](http://github.com/cms-sw/cmssw/pull/21564){:target="_blank"}  from **@Teemperor**: Added include for string to PixelVersionAlias.h `alca`  created: 2017-11-30 10:34:15 merged: 2017-12-01 15:53:28

64. [21563](http://github.com/cms-sw/cmssw/pull/21563){:target="_blank"}  from **@Teemperor**: Added missing includes to PixelConfig.h `alca`  created: 2017-11-30 10:34:09 merged: 2017-12-01 15:53:39

65. [21562](http://github.com/cms-sw/cmssw/pull/21562){:target="_blank"}  from **@Teemperor**: Include cstdint in ConstantsForCondObjects.h `reconstruction`  created: 2017-11-30 10:34:02 merged: 2017-12-02 07:53:50

66. [21561](http://github.com/cms-sw/cmssw/pull/21561){:target="_blank"}  from **@Teemperor**: Added include for PixelMaskOverrideBase to PixelMaskOverride `alca`  created: 2017-11-30 10:33:52 merged: 2017-12-01 15:53:52

67. [21560](http://github.com/cms-sw/cmssw/pull/21560){:target="_blank"}  from **@Teemperor**: Added missing includes to SurveyPxbImageReader `alca`  created: 2017-11-30 10:33:47 merged: 2017-12-01 12:31:02

68. [21559](http://github.com/cms-sw/cmssw/pull/21559){:target="_blank"}  from **@Teemperor**: Added missing includes to TrackerDetectorStruct.h `alca`  created: 2017-11-30 10:33:41 merged: 2017-12-01 12:31:39

69. [21558](http://github.com/cms-sw/cmssw/pull/21558){:target="_blank"}  from **@Teemperor**: Added missing include to BoundaryPlane.h `reconstruction`  created: 2017-11-30 10:33:36 merged: 2017-12-04 08:58:51

70. [21557](http://github.com/cms-sw/cmssw/pull/21557){:target="_blank"}  from **@Teemperor**: Make BoundarySurface.h compile `reconstruction`  created: 2017-11-30 10:33:28 merged: 2017-12-02 07:52:24

71. [21556](http://github.com/cms-sw/cmssw/pull/21556){:target="_blank"}  from **@Teemperor**: Removed commented out dependency in DataFormats/EgammaCandidates `reconstruction`  created: 2017-11-30 10:33:18 merged: 2017-12-02 07:51:41

72. [21553](http://github.com/cms-sw/cmssw/pull/21553){:target="_blank"}  from **@Teemperor**: Qualified numeric_limits in PFCombinedTauTagInfo.h `reconstruction`  created: 2017-11-30 10:31:13 merged: 2017-12-01 07:48:29

73. [21551](http://github.com/cms-sw/cmssw/pull/21551){:target="_blank"}  from **@Teemperor**: Added missing includes to EventHypothesisLooper.h `analysis`  `reconstruction`  created: 2017-11-30 10:30:59 merged: 2017-12-04 08:51:21

74. [21550](http://github.com/cms-sw/cmssw/pull/21550){:target="_blank"}  from **@Teemperor**: Added include for cstdint to liblogintpack.h `analysis`  `reconstruction`  created: 2017-11-30 10:30:54 merged: 2017-12-02 07:57:50

75. [21549](http://github.com/cms-sw/cmssw/pull/21549){:target="_blank"}  from **@Teemperor**: Added include for cmath to BionamialProbability.h `analysis`  `reconstruction`  created: 2017-11-30 10:30:47 merged: 2017-12-02 07:58:00

76. [21548](http://github.com/cms-sw/cmssw/pull/21548){:target="_blank"}  from **@Teemperor**: Added missing include to trackHitsToClusterRefs.h `simulation`  created: 2017-11-30 10:30:39 merged: 2017-12-01 15:54:18

77. [21547](http://github.com/cms-sw/cmssw/pull/21547){:target="_blank"}  from **@Teemperor**: Fixed forward decls in AlignmentGlobalTrackSelector.h `alca`  created: 2017-11-30 10:30:33 merged: 2017-12-01 12:28:51

78. [21546](http://github.com/cms-sw/cmssw/pull/21546){:target="_blank"}  from **@Teemperor**: Added missing forward decls to AlignmentTwoBodyDecayTrackSelector.h `alca`  created: 2017-11-30 10:30:28 merged: 2017-12-01 12:29:01

79. [21545](http://github.com/cms-sw/cmssw/pull/21545){:target="_blank"}  from **@Teemperor**: Added missing includes to CandMapTrait.h `analysis`  `reconstruction`  created: 2017-11-30 10:30:22 merged: 2017-12-04 08:53:53

80. [21544](http://github.com/cms-sw/cmssw/pull/21544){:target="_blank"}  from **@Teemperor**: Added include for string to HcalRawGain.h `alca`  `db`  created: 2017-11-30 10:30:16 merged: 2017-12-02 07:50:32

81. [21542](http://github.com/cms-sw/cmssw/pull/21542){:target="_blank"}  from **@Teemperor**: Added include for boost access to ScalingExponential.h `alca`  `db`  created: 2017-11-30 10:30:04 merged: 2017-12-06 10:46:06

82. [21541](http://github.com/cms-sw/cmssw/pull/21541){:target="_blank"}  from **@Teemperor**: Added missing includes to APDSimParameters.h `simulation`  created: 2017-11-30 10:29:59 merged: 2017-12-01 15:54:28

83. [21540](http://github.com/cms-sw/cmssw/pull/21540){:target="_blank"}  from **@Teemperor**: Added missing include to EcalUncalibRecHitRecAbsAlgo.h `reconstruction`  created: 2017-11-30 10:29:52 merged: 2017-12-02 07:50:20

84. [21539](http://github.com/cms-sw/cmssw/pull/21539){:target="_blank"}  from **@Teemperor**: Added missing include to EcalCondHandler.h `db`  created: 2017-11-30 10:29:46 merged: 2017-12-06 10:45:21

85. [21538](http://github.com/cms-sw/cmssw/pull/21538){:target="_blank"}  from **@Teemperor**: Corrected include in EcalWeightSetXMLTranslator.h `db`  created: 2017-11-30 10:29:39 merged: 2017-12-06 10:45:40

86. [21537](http://github.com/cms-sw/cmssw/pull/21537){:target="_blank"}  from **@Teemperor**: Added missing include to CastorRawGain.h `alca`  `db`  created: 2017-11-30 10:29:24 merged: 2017-12-05 09:46:30

87. [21536](http://github.com/cms-sw/cmssw/pull/21536){:target="_blank"}  from **@Teemperor**: Added include for cstdint to ESCrcKchipFast.h `reconstruction`  created: 2017-11-30 10:29:18 merged: 2017-12-02 07:50:11

88. [21535](http://github.com/cms-sw/cmssw/pull/21535){:target="_blank"}  from **@Teemperor**: Added include for memory to Table.h `core`  created: 2017-11-30 10:29:11 merged: 2017-12-01 07:36:07

89. [21534](http://github.com/cms-sw/cmssw/pull/21534){:target="_blank"}  from **@Teemperor**: Added missing include to SeedCreatorFromRegionHitsEDProducerT.h `reconstruction`  created: 2017-11-30 10:29:04 merged: 2017-12-02 10:31:25

90. [21533](http://github.com/cms-sw/cmssw/pull/21533){:target="_blank"}  from **@Teemperor**: Added header guards to DetIDAssociator.h `alca`  created: 2017-11-30 10:28:19 merged: 2017-12-02 07:49:59

91. [21532](http://github.com/cms-sw/cmssw/pull/21532){:target="_blank"}  from **@Teemperor**: Include Sourcevariable.h in SourceVariableSet.h `analysis`  created: 2017-11-30 10:28:12 merged: 2017-12-01 07:49:21

92. [21531](http://github.com/cms-sw/cmssw/pull/21531){:target="_blank"}  from **@Teemperor**: Included CaloGeometry.h in eCone.h `alca`  `comparison`  created: 2017-11-30 10:28:06 merged: 2017-12-01 07:30:17

93. [21529](http://github.com/cms-sw/cmssw/pull/21529){:target="_blank"}  from **@Teemperor**: Forward declared Wrapperbase in InternalDataKey.h `core`  created: 2017-11-30 10:27:53 merged: 2017-12-01 07:49:43

94. [21528](http://github.com/cms-sw/cmssw/pull/21528){:target="_blank"}  from **@Teemperor**: Added missing includes to JetAlgoHelper.h `reconstruction`  created: 2017-11-30 10:27:46 merged: 2017-12-01 07:49:57

95. [21527](http://github.com/cms-sw/cmssw/pull/21527){:target="_blank"}  from **@Teemperor**: Added missing includes to PrintoutHelper.h `reconstruction`  created: 2017-11-30 10:27:40 merged: 2017-12-01 07:30:38

96. [21526](http://github.com/cms-sw/cmssw/pull/21526){:target="_blank"}  from **@Teemperor**: Added include for Exception.h to InputSource.h/OutputFiles.h `core`  created: 2017-11-30 10:27:35 merged: 2017-12-01 07:33:12

97. [21525](http://github.com/cms-sw/cmssw/pull/21525){:target="_blank"}  from **@Teemperor**: Added include for SiStripApvGain to SiStripGainsPCLHarvester.h `alca`  created: 2017-11-30 10:27:27 merged: 2017-12-04 08:56:06

98. [21524](http://github.com/cms-sw/cmssw/pull/21524){:target="_blank"}  from **@Teemperor**: Added include for Event/Parameter set ot CommonTools/ParticleFlow `analysis`  `reconstruction`  created: 2017-11-30 10:27:20 merged: 2017-12-01 07:50:15

99. [21522](http://github.com/cms-sw/cmssw/pull/21522){:target="_blank"}  from **@Teemperor**: Added missing include to SiStripPayloadInspectorHelper.h `comparison`  `db`  created: 2017-11-30 10:27:05 merged: 2017-12-07 12:55:12

100. [21518](http://github.com/cms-sw/cmssw/pull/21518){:target="_blank"}  from **@Teemperor**: Added missing vector includes EMTF `l1`  created: 2017-11-30 10:26:40 merged: 2017-12-07 12:41:39

101. [21515](http://github.com/cms-sw/cmssw/pull/21515){:target="_blank"}  from **@Teemperor**: Added header guards to ThrParameters.h `reconstruction`  created: 2017-11-30 10:26:20 merged: 2017-12-07 13:03:32

102. [21507](http://github.com/cms-sw/cmssw/pull/21507){:target="_blank"}  from **@Teemperor**: Actually cindelu CSCDMBHeader.h in CSCDMBTrailer2005/2013.h `reconstruction`  created: 2017-11-30 10:25:27 merged: 2017-12-01 07:50:58

103. [21505](http://github.com/cms-sw/cmssw/pull/21505){:target="_blank"}  from **@Teemperor**: Added include for vector to MuonArbitrationMethods.h `reconstruction`  created: 2017-11-30 10:25:15 merged: 2017-12-01 07:46:34

104. [21504](http://github.com/cms-sw/cmssw/pull/21504){:target="_blank"}  from **@Teemperor**: Added include for vector to TimeMeasurementSequence.h `reconstruction`  created: 2017-11-30 10:25:10 merged: 2017-12-01 12:29:12

105. [21503](http://github.com/cms-sw/cmssw/pull/21503){:target="_blank"}  from **@Teemperor**: Added missing include to MuonArbitrationMethods.h `reconstruction`  created: 2017-11-30 10:25:04 merged: 2017-12-01 07:51:18

106. [21502](http://github.com/cms-sw/cmssw/pull/21502){:target="_blank"}  from **@Teemperor**: Added missing includes to UECalibration.h `reconstruction`  created: 2017-11-30 10:24:57 merged: 2017-12-01 07:36:33

107. [21496](http://github.com/cms-sw/cmssw/pull/21496){:target="_blank"}  from **@Teemperor**: Added cstdint include to DataFormats/CTPPSReco headers `reconstruction`  created: 2017-11-30 10:24:19 merged: 2017-12-01 12:29:35

108. [21495](http://github.com/cms-sw/cmssw/pull/21495){:target="_blank"}  from **@Teemperor**: Include cstdint in TotemFEDInfo.H `reconstruction`  `simulation`  created: 2017-11-30 10:24:12 merged: 2017-12-01 07:33:23

109. [21493](http://github.com/cms-sw/cmssw/pull/21493){:target="_blank"}  from **@Teemperor**: Added include to FTLRecHit.h to FTLRecHitComparison.h `reconstruction`  created: 2017-11-30 10:23:58 merged: 2017-12-02 07:49:51

110. [21489](http://github.com/cms-sw/cmssw/pull/21489){:target="_blank"}  from **@civanch**: Geant4 sensitive detectors cleanup 1 `simulation`  `upgrade`  created: 2017-11-29 20:59:34 merged: 2017-12-07 12:50:26

111. [21488](http://github.com/cms-sw/cmssw/pull/21488){:target="_blank"}  from **@Dr15Jones**: EventProcessor refactoring `core`  created: 2017-11-29 20:47:16 merged: 2017-11-30 14:48:38

112. [21486](http://github.com/cms-sw/cmssw/pull/21486){:target="_blank"}  from **@nsmith-**: Bugfix new CaloLayer1 unpacker `l1`  created: 2017-11-29 17:34:25 merged: 2017-11-30 14:50:29

113. [21484](http://github.com/cms-sw/cmssw/pull/21484){:target="_blank"}  from **@davidlt**: Fix undefined references `reconstruction`  `upgrade`  created: 2017-11-29 14:19:55 merged: 2017-12-01 07:38:09

114. [21483](http://github.com/cms-sw/cmssw/pull/21483){:target="_blank"}  from **@mmusich**: [10.0.x] fix tk map scale in SiStrip PI, in case there is a sigle value to be displayed `db`  created: 2017-11-29 11:41:36 merged: 2017-12-07 12:43:38

115. [21481](http://github.com/cms-sw/cmssw/pull/21481){:target="_blank"}  from **@mrodozov**: Fix wrong bit shifting in TestPhiMemoryImage.cpp `l1`  created: 2017-11-28 22:29:25 merged: 2017-11-29 01:35:29

116. [21480](http://github.com/cms-sw/cmssw/pull/21480){:target="_blank"}  from **@fwyzard**: Use the CMS_THREAD_SAFE macro instead of [[cms::thread_safe]] `alca`  `analysis`  `core`  `fastsim`  `reconstruction`  created: 2017-11-28 20:46:53 merged: 2017-12-04 08:52:06

117. [21473](http://github.com/cms-sw/cmssw/pull/21473){:target="_blank"}  from **@mrodozov**: Fix build fail in SimG4Core/CustomPhysics `simulation`  created: 2017-11-28 09:08:05 merged: 2017-11-28 11:22:23

118. [21471](http://github.com/cms-sw/cmssw/pull/21471){:target="_blank"}  from **@ghellwig**: [10.0.X] HTCondor migration, fixes, improvements and preparation for AFS migration in MillePede workflow `alca`  created: 2017-11-28 08:47:13 merged: 2017-12-07 12:44:42

119. [21469](http://github.com/cms-sw/cmssw/pull/21469){:target="_blank"}  from **@Dr15Jones**: Fix edmProvDump handling of processing history `core`  created: 2017-11-27 20:56:13 merged: 2017-11-28 11:30:17

120. [21468](http://github.com/cms-sw/cmssw/pull/21468){:target="_blank"}  from **@Dr15Jones**: move *egmGsfElectronIDsForDQM module to a cms.Task `dqm`  created: 2017-11-27 16:01:15 merged: 2017-11-28 17:08:49

121. [21466](http://github.com/cms-sw/cmssw/pull/21466){:target="_blank"}  from **@arunhep**: [GT Updates] for mcRunI and mcRunII for HCAL effective Pedestals to fix PR 21438 `alca`  created: 2017-11-27 13:29:25 merged: 2017-11-28 11:29:52

122. [21463](http://github.com/cms-sw/cmssw/pull/21463){:target="_blank"}  from **@VinInn**: Clean SeedClusterRemover `reconstruction`  created: 2017-11-25 14:50:38 merged: 2017-11-28 11:29:06

123. [21462](http://github.com/cms-sw/cmssw/pull/21462){:target="_blank"}  from **@civanch**: General clean-up of the SimG4Core/CustomPhysics library `simulation`  created: 2017-11-24 19:55:43 merged: 2017-11-27 13:20:55

124. [21460](http://github.com/cms-sw/cmssw/pull/21460){:target="_blank"}  from **@kpedro88**: activate 2018 PU workflows `pdmv`  `upgrade`  created: 2017-11-24 19:19:31 merged: 2017-11-25 10:29:00

125. [21456](http://github.com/cms-sw/cmssw/pull/21456){:target="_blank"}  from **@VinInn**: Cleanup of Tracking code `alca`  `analysis`  `core`  `dqm`  `reconstruction`  created: 2017-11-24 14:23:35 merged: 2017-11-30 01:03:55

126. [21453](http://github.com/cms-sw/cmssw/pull/21453){:target="_blank"}  from **@davidlt**: Fix two bugs (out-of-bounds access) in MuonAlignment* `alca`  created: 2017-11-23 18:40:31 merged: 2017-11-24 09:06:09

127. [21450](http://github.com/cms-sw/cmssw/pull/21450){:target="_blank"}  from **@argiro**: bug fix for g6 and g1 handling `alca`  created: 2017-11-23 15:15:04 merged: 2017-11-25 08:49:59

128. [21446](http://github.com/cms-sw/cmssw/pull/21446){:target="_blank"}  from **@fwyzard**: FastTimerService: add measurement of framework overhead (100x) `hlt`  created: 2017-11-23 12:48:43 merged: 2017-11-24 17:49:09

129. [21444](http://github.com/cms-sw/cmssw/pull/21444){:target="_blank"}  from **@cms-tsg-storm**: Add L1 ETMHF as HLT objects `hlt`  created: 2017-11-23 11:36:57 merged: 2017-11-24 17:45:36

130. [21442](http://github.com/cms-sw/cmssw/pull/21442){:target="_blank"}  from **@arunhep**: Adding postLS2 (2019) design key and 2019 workflow updates `alca`  `pdmv`  `upgrade`  created: 2017-11-23 08:49:17 merged: 2017-11-28 12:01:56

131. [21439](http://github.com/cms-sw/cmssw/pull/21439){:target="_blank"}  from **@kpedro88**: Fix mismatched calo signals warning and make accessors consistent `alca`  `simulation`  created: 2017-11-22 19:03:05 merged: 2017-11-27 13:17:57

132. [21438](http://github.com/cms-sw/cmssw/pull/21438){:target="_blank"}  from **@kpedro88**: Use of effective pedestals for HCAL Phase1/Phase2 reco `alca`  `db`  `hlt`  `reconstruction`  `simulation`  created: 2017-11-22 18:40:38 merged: 2017-12-07 13:00:58

133. [21437](http://github.com/cms-sw/cmssw/pull/21437){:target="_blank"}  from **@cms-tsg-storm**: Cleaning of TrajectoryCleanerESProducer in HLT directory `hlt`  created: 2017-11-22 17:43:20 merged: 2017-11-24 09:06:30

134. [21435](http://github.com/cms-sw/cmssw/pull/21435){:target="_blank"}  from **@CTPPS**: Silencing CTPPSIncludeAlignments print out `geometry`  created: 2017-11-22 15:30:18 merged: 2017-11-23 07:35:33

135. [21434](http://github.com/cms-sw/cmssw/pull/21434){:target="_blank"}  from **@abaty**: Moving off obsolete trajectory cleaner in 1st step of HI tracking `reconstruction`  created: 2017-11-22 14:59:40 merged: 2017-11-24 17:49:31

136. [21431](http://github.com/cms-sw/cmssw/pull/21431){:target="_blank"}  from **@prebello**: added 2017E/D/F data relvals `pdmv`  `upgrade`  created: 2017-11-22 13:35:40 merged: 2017-11-28 11:50:51

137. [21428](http://github.com/cms-sw/cmssw/pull/21428){:target="_blank"}  from **@mmusich**: [10.0.x] remove memory leak in PVValidation and fix ini file `alca`  created: 2017-11-22 12:48:41 merged: 2017-11-28 11:27:59

138. [21426](http://github.com/cms-sw/cmssw/pull/21426){:target="_blank"}  from **@CTPPS**: CTPPS: Improved Diamond data formats `reconstruction`  created: 2017-11-22 11:51:00 merged: 2017-12-05 09:52:16

139. [21422](http://github.com/cms-sw/cmssw/pull/21422){:target="_blank"}  from **@fwyzard**: remove unnecessary #include `alca`  `hlt`  `reconstruction`  created: 2017-11-21 21:19:56 merged: 2017-11-22 09:19:52

140. [21421](http://github.com/cms-sw/cmssw/pull/21421){:target="_blank"}  from **@pieterdavid**: Migrate SiStripSubStructure (and TkDetMap, TkHistoMap) from tracker-sub-DetId to TrackerTopology `alca`  `analysis`  `dqm`  `hlt`  `reconstruction`  `simulation`  created: 2017-11-21 16:18:42 merged: 2017-11-29 12:52:31

141. [21419](http://github.com/cms-sw/cmssw/pull/21419){:target="_blank"}  from **@perrozzi**: set TMPDIR variable to soft link pointing to PWD `generators`  created: 2017-11-21 16:05:09 merged: 2017-11-24 18:03:01

142. [21417](http://github.com/cms-sw/cmssw/pull/21417){:target="_blank"}  from **@mmusich**: [10.0.x] Add dump plot of AlignPCLThreshold in the payload inspector `db`  created: 2017-11-21 15:47:34 merged: 2017-12-01 07:52:28

143. [21416](http://github.com/cms-sw/cmssw/pull/21416){:target="_blank"}  from **@mmusich**: [10.0.x] add plot of BS parameters in beamspot payload inspector `db`  created: 2017-11-21 15:47:30 merged: 2017-11-29 12:46:03

144. [21415](http://github.com/cms-sw/cmssw/pull/21415){:target="_blank"}  from **@Teemperor**: Refactored HcalRecHitFwd.h to HcalRecHitDefs.h `reconstruction`  created: 2017-11-21 14:26:21 merged: 2017-11-23 07:33:46

145. [21414](http://github.com/cms-sw/cmssw/pull/21414){:target="_blank"}  from **@Teemperor**: Added include for PFTau3ProngSummaryFwd.h `reconstruction`  created: 2017-11-21 14:26:10 merged: 2017-11-23 07:33:33

146. [21413](http://github.com/cms-sw/cmssw/pull/21413){:target="_blank"}  from **@Teemperor**: Added include for algorithm to get std::min `analysis`  created: 2017-11-21 14:26:01 merged: 2017-11-22 07:59:31

147. [21412](http://github.com/cms-sw/cmssw/pull/21412){:target="_blank"}  from **@Teemperor**: Made simple_stat.h standalone `reconstruction`  created: 2017-11-21 14:25:52 merged: 2017-11-30 01:06:39

148. [21411](http://github.com/cms-sw/cmssw/pull/21411){:target="_blank"}  from **@Teemperor**: Make AlignableDataIO.h/AlignableDataIOROOT.h standalone `alca`  created: 2017-11-21 14:25:44 merged: 2017-12-01 12:32:27

149. [21410](http://github.com/cms-sw/cmssw/pull/21410){:target="_blank"}  from **@Teemperor**: Added missing forward decls to DDNodeSelector.h `geometry`  created: 2017-11-21 14:25:34 merged: 2017-11-22 07:59:43

150. [21409](http://github.com/cms-sw/cmssw/pull/21409){:target="_blank"}  from **@Teemperor**: Added include for vector to SelectionUserVariables.h `alca`  created: 2017-11-21 14:25:26 merged: 2017-12-06 10:41:52

151. [21408](http://github.com/cms-sw/cmssw/pull/21408){:target="_blank"}  from **@Teemperor**: Include TrackCandidateCollection in TrackCandidateSeedAssociation.h `reconstruction`  created: 2017-11-21 14:25:17 merged: 2017-11-23 07:33:21

152. [21407](http://github.com/cms-sw/cmssw/pull/21407){:target="_blank"}  from **@Teemperor**: Added missing include to AssociatedVariableCollectionSelector.h `analysis`  `reconstruction`  created: 2017-11-21 14:25:08 merged: 2017-11-23 07:39:17

153. [21406](http://github.com/cms-sw/cmssw/pull/21406){:target="_blank"}  from **@Teemperor**: Added missing include to DummySelector.h `analysis`  `reconstruction`  created: 2017-11-21 14:25:00 merged: 2017-11-23 07:33:08

154. [21405](http://github.com/cms-sw/cmssw/pull/21405){:target="_blank"}  from **@Teemperor**: Added missing includes to FwdPtrConversionFactory.h `analysis`  `reconstruction`  created: 2017-11-21 14:24:48 merged: 2017-11-23 07:32:57

155. [21404](http://github.com/cms-sw/cmssw/pull/21404){:target="_blank"}  from **@Teemperor**: Added missing includes to NullPostProcessor `analysis`  `reconstruction`  created: 2017-11-21 14:22:26 merged: 2017-11-23 07:35:04

156. [21403](http://github.com/cms-sw/cmssw/pull/21403){:target="_blank"}  from **@Teemperor**: Added missing include to TrajAnnealing `reconstruction`  created: 2017-11-21 14:22:18 merged: 2017-11-23 07:32:34

157. [21402](http://github.com/cms-sw/cmssw/pull/21402){:target="_blank"}  from **@Teemperor**: Added missing include to BarrelUtil.h `reconstruction`  created: 2017-11-21 14:22:09 merged: 2017-11-23 07:32:21

158. [21401](http://github.com/cms-sw/cmssw/pull/21401){:target="_blank"}  from **@Teemperor**: Include DetRod.h in PhiBorderFinder.h `reconstruction`  created: 2017-11-21 14:22:02 merged: 2017-11-23 07:32:08

159. [21400](http://github.com/cms-sw/cmssw/pull/21400){:target="_blank"}  from **@Teemperor**: Include ForwardDetRod.h in RBorderFinder.h `reconstruction`  created: 2017-11-21 14:21:53 merged: 2017-11-23 07:31:55

160. [21396](http://github.com/cms-sw/cmssw/pull/21396){:target="_blank"}  from **@davidlt**: Fix undefined references in UBSAN IBs `alca`  `analysis`  `dqm`  `fastsim`  `generators`  `geometry`  `reconstruction`  `simulation`  created: 2017-11-21 09:00:26 merged: 2017-11-23 07:34:00

161. [21395](http://github.com/cms-sw/cmssw/pull/21395){:target="_blank"}  from **@arunhep**: GTUpdates : All GTs updated with HCAL Pedestals with effective label `alca`  created: 2017-11-21 04:36:11 merged: 2017-11-21 12:27:26

162. [21391](http://github.com/cms-sw/cmssw/pull/21391){:target="_blank"}  from **@Dr15Jones**: Make sure task object is owned by the lambda for prePrefetchSelectionAsync call `core`  created: 2017-11-20 16:12:50 merged: 2017-11-21 07:18:59

163. [21390](http://github.com/cms-sw/cmssw/pull/21390){:target="_blank"}  from **@mrodozov**: Fix relval 145.0  fail `pdmv`  `upgrade`  created: 2017-11-20 16:03:51 merged: 2017-11-21 07:18:46

164. [21389](http://github.com/cms-sw/cmssw/pull/21389){:target="_blank"}  from **@makortel**: Replace fastSim.isChosen() with toModify/toReplaceWith/makeProcessModifier `dqm`  `fastsim`  `operations`  `reconstruction`  `simulation`  created: 2017-11-20 16:02:47 merged: 2017-12-01 15:56:33

165. [21387](http://github.com/cms-sw/cmssw/pull/21387){:target="_blank"}  from **@DryRun**: Fix for large number of efficiency_strings in HLT harvesting `dqm`  created: 2017-11-20 15:43:39 merged: 2017-12-07 13:01:47

166. [21386](http://github.com/cms-sw/cmssw/pull/21386){:target="_blank"}  from **@Teemperor**: Added include for SelectorStack.h to ExpressionCondition.h `analysis`  `reconstruction`  created: 2017-11-20 14:46:46 merged: 2017-11-23 07:35:15

167. [21385](http://github.com/cms-sw/cmssw/pull/21385){:target="_blank"}  from **@Teemperor**: Remove CombinerSetter.h `analysis`  `reconstruction`  created: 2017-11-20 14:24:54 merged: 2017-11-22 07:59:56

168. [21384](http://github.com/cms-sw/cmssw/pull/21384){:target="_blank"}  from **@Teemperor**: Added include for vector to MuonShower.h `reconstruction`  created: 2017-11-20 14:18:19 merged: 2017-11-21 17:20:33

169. [21383](http://github.com/cms-sw/cmssw/pull/21383){:target="_blank"}  from **@Teemperor**: Added include for cmath to MuenMETCorrectionData `reconstruction`  created: 2017-11-20 14:18:14 merged: 2017-11-21 17:20:45

170. [21382](http://github.com/cms-sw/cmssw/pull/21382){:target="_blank"}  from **@Teemperor**: Added include to EcalRecHit.h to EcalRecHitComparison.h `reconstruction`  created: 2017-11-20 14:18:08 merged: 2017-11-21 17:20:58

171. [21381](http://github.com/cms-sw/cmssw/pull/21381){:target="_blank"}  from **@Teemperor**: Added include to AbsArchive.hh to RPFooterReference.hh `alca`  created: 2017-11-20 13:59:43 merged: 2017-11-23 07:31:32

172. [21380](http://github.com/cms-sw/cmssw/pull/21380){:target="_blank"}  from **@Teemperor**: Added include to CharBuffer.hh to RPBufferReference.hh `alca`  created: 2017-11-20 13:52:25 merged: 2017-11-21 07:18:33

173. [21379](http://github.com/cms-sw/cmssw/pull/21379){:target="_blank"}  from **@Teemperor**: Added include to functional to AlignmentSorter.h `alca`  `db`  created: 2017-11-20 13:39:59 merged: 2017-11-21 07:18:19

174. [21378](http://github.com/cms-sw/cmssw/pull/21378){:target="_blank"}  from **@Teemperor**: Added include to cstddef to InsertContainerItem.hh `alca`  created: 2017-11-20 13:39:58 merged: 2017-11-21 07:18:06

175. [21377](http://github.com/cms-sw/cmssw/pull/21377){:target="_blank"}  from **@Teemperor**: Added include to AbsArchive.hh to CPFooterReference.hh `alca`  created: 2017-11-20 13:39:56 merged: 2017-11-21 07:17:53

176. [21376](http://github.com/cms-sw/cmssw/pull/21376){:target="_blank"}  from **@arizzi**: Second NanoAOD update `analysis`  `reconstruction`  created: 2017-11-20 12:54:23 merged: 2017-11-22 08:02:33

177. [21375](http://github.com/cms-sw/cmssw/pull/21375){:target="_blank"}  from **@Teemperor**: Added missing includes to IDbSchema.h `db`  created: 2017-11-20 12:49:02 merged: 2017-11-21 17:21:10

178. [21374](http://github.com/cms-sw/cmssw/pull/21374){:target="_blank"}  from **@Teemperor**: Added missing vector include to WrapperDetail.h `core`  created: 2017-11-20 12:48:57 merged: 2017-11-21 07:17:40

179. [21373](http://github.com/cms-sw/cmssw/pull/21373){:target="_blank"}  from **@Teemperor**: Added include for size_t to ContainerMaskTraits.h `core`  created: 2017-11-20 12:48:41 merged: 2017-11-21 07:17:26

180. [21372](http://github.com/cms-sw/cmssw/pull/21372){:target="_blank"}  from **@Teemperor**: Added include for size_t to ContainerMask.h `core`  created: 2017-11-20 12:48:40 merged: 2017-11-24 17:49:58

181. [21371](http://github.com/cms-sw/cmssw/pull/21371){:target="_blank"}  from **@Teemperor**: Added ProductID include to AssociationMapHelpers.h `core`  created: 2017-11-20 12:48:34 merged: 2017-11-21 07:17:14

182. [21363](http://github.com/cms-sw/cmssw/pull/21363){:target="_blank"}  from **@civanch**: Fixed initialisation of Geant4 run managers `simulation`  created: 2017-11-19 17:34:55 merged: 2017-11-20 08:38:57

183. [21361](http://github.com/cms-sw/cmssw/pull/21361){:target="_blank"}  from **@bsunanda**: Run2-alca106 Update calibration code using IsoTracks and MIPs in HB/HE `alca`  created: 2017-11-17 19:37:33 merged: 2017-11-28 11:31:05

184. [21360](http://github.com/cms-sw/cmssw/pull/21360){:target="_blank"}  from **@civanch**: Updated Geant4 physics lists `simulation`  created: 2017-11-17 19:21:35 merged: 2017-11-21 07:17:02

185. [21357](http://github.com/cms-sw/cmssw/pull/21357){:target="_blank"}  from **@VinInn**: few improvements to tracking DQM `dqm`  created: 2017-11-17 18:18:34 merged: 2017-11-30 01:07:29

186. [21354](http://github.com/cms-sw/cmssw/pull/21354){:target="_blank"}  from **@kpedro88**: use deterministic seed for time smearing producers `reconstruction`  `simulation`  `upgrade`  created: 2017-11-17 15:58:10 merged: 2017-11-25 08:50:36

187. [21353](http://github.com/cms-sw/cmssw/pull/21353){:target="_blank"}  from **@rekovic**: Pr100x RPCTwinMux in L1TRawToDigi Sequence  `l1`  created: 2017-11-17 15:11:12 merged: 2017-11-18 16:43:51

188. [21350](http://github.com/cms-sw/cmssw/pull/21350){:target="_blank"}  from **@vukasinmilosevic**: Small corrections to the calo to uGT comparison plots `dqm`  created: 2017-11-17 13:28:48 merged: 2017-11-30 14:51:12

189. [21349](http://github.com/cms-sw/cmssw/pull/21349){:target="_blank"}  from **@jhgoh**: Fix GenParticles2HepMCConverter to run on herwig samples `generators`  created: 2017-11-17 13:22:23 merged: 2017-11-30 14:53:55

190. [21348](http://github.com/cms-sw/cmssw/pull/21348){:target="_blank"}  from **@cms-tau-pog**: Reduce LogWarning for non-existing tau discriminators during pat::Tau candidate creation `analysis`  `reconstruction`  created: 2017-11-17 11:20:53 merged: 2017-11-27 13:54:55

191. [21347](http://github.com/cms-sw/cmssw/pull/21347){:target="_blank"}  from **@mschrode**: Update Phase-I mis-alignment scenario (MC2017 V1) `alca`  created: 2017-11-17 10:59:00 merged: 2017-11-18 16:47:47

192. [21345](http://github.com/cms-sw/cmssw/pull/21345){:target="_blank"}  from **@davidlt**: Fix indexes related to {s,l,c}_suffix `comparison`  `dqm`  created: 2017-11-17 08:09:45 merged: 2017-11-18 17:05:19

193. [21342](http://github.com/cms-sw/cmssw/pull/21342){:target="_blank"}  from **@civanch**: Updated TB2006 `simulation`  created: 2017-11-16 17:54:22 merged: 2017-11-17 12:14:12

194. [21339](http://github.com/cms-sw/cmssw/pull/21339){:target="_blank"}  from **@civanch**: Added MixMax random number generator `core`  created: 2017-11-16 17:20:23 merged: 2017-11-17 12:13:46

195. [21334](http://github.com/cms-sw/cmssw/pull/21334){:target="_blank"}  from **@thomreis**: L1T online and offline DQM configuration upgrades `dqm`  `l1`  created: 2017-11-16 15:43:14 merged: 2017-11-29 12:43:58

196. [21331](http://github.com/cms-sw/cmssw/pull/21331){:target="_blank"}  from **@cms-bph-trigger**: Make the HLT vertex filters robust to L3Muon duplicates `hlt`  created: 2017-11-16 15:15:50 merged: 2017-11-18 16:41:30

197. [21328](http://github.com/cms-sw/cmssw/pull/21328){:target="_blank"}  from **@perrozzi**: add EventGenerationFailure exit code  `core`  `generators`  created: 2017-11-16 13:39:50 merged: 2017-11-17 10:07:21

198. [21325](http://github.com/cms-sw/cmssw/pull/21325){:target="_blank"}  from **@fwyzard**: Move all EDM plugins to the plugins/ directory `hlt`  created: 2017-11-15 17:43:41 merged: 2017-11-21 07:16:21

199. [21323](http://github.com/cms-sw/cmssw/pull/21323){:target="_blank"}  from **@ly615**: [10X] L1T Validation Module with with GeneratorParticle Information: put denom/nominator hists into a sub-dir `dqm`  created: 2017-11-15 15:09:19 merged: 2017-12-01 07:39:17

200. [21320](http://github.com/cms-sw/cmssw/pull/21320){:target="_blank"}  from **@Dr15Jones**: Post event transition cache must be atomic `core`  created: 2017-11-15 14:32:16 merged: 2017-11-15 17:51:22

201. [21318](http://github.com/cms-sw/cmssw/pull/21318){:target="_blank"}  from **@davignon**: Revised binning for L1T Tau DQM efficiency turn-ons `dqm`  `l1`  created: 2017-11-15 13:14:46 merged: 2017-11-30 01:08:08

202. [21317](http://github.com/cms-sw/cmssw/pull/21317){:target="_blank"}  from **@threus**: updated express GT for EventDisplay `dqm`  created: 2017-11-15 13:05:30 merged: 2017-11-20 10:37:42

203. [21310](http://github.com/cms-sw/cmssw/pull/21310){:target="_blank"}  from **@ttrk**: keep islandPhoton related collections via HI eras `reconstruction`  created: 2017-11-15 00:48:46 merged: 2017-11-17 10:06:01

204. [21307](http://github.com/cms-sw/cmssw/pull/21307){:target="_blank"}  from **@jshlee**: gem geometry to DB writer `db`  `geometry`  `upgrade`  created: 2017-11-14 18:46:24 merged: 2017-11-25 08:51:16

205. [21306](http://github.com/cms-sw/cmssw/pull/21306){:target="_blank"}  from **@jshlee**: gem CondFormats `alca`  `db`  `upgrade`  created: 2017-11-14 18:33:10 merged: 2017-12-07 21:56:42

206. [21305](http://github.com/cms-sw/cmssw/pull/21305){:target="_blank"}  from **@jshlee**: gem DataFormats for digi errors `daq`  `simulation`  `upgrade`  created: 2017-11-14 18:24:16 merged: 2017-11-27 13:18:08

207. [21304](http://github.com/cms-sw/cmssw/pull/21304){:target="_blank"}  from **@ghellwig**: [10.0.X] Update of MC misalignment scaler tool `alca`  created: 2017-11-14 17:51:17 merged: 2017-12-01 17:07:20

208. [21302](http://github.com/cms-sw/cmssw/pull/21302){:target="_blank"}  from **@pieterdavid**: Revert accidentally committed changes in CalibTracker/SiStripDCS `alca`  created: 2017-11-14 17:23:04 merged: 2017-11-21 07:14:59

209. [21299](http://github.com/cms-sw/cmssw/pull/21299){:target="_blank"}  from **@perrotta**: Cure (innocuous) dead assignments in reco met filters and producers `analysis`  `reconstruction`  created: 2017-11-14 14:39:17 merged: 2017-11-15 08:11:16

210. [21291](http://github.com/cms-sw/cmssw/pull/21291){:target="_blank"}  from **@capalmer85**: add PU=0 at the start of vectors (master) `simulation`  created: 2017-11-13 14:19:55 merged: 2017-11-20 08:43:09

211. [21289](http://github.com/cms-sw/cmssw/pull/21289){:target="_blank"}  from **@mariadalfonso**: HBHE: obsolete code cleanup `alca`  `reconstruction`  `simulation`  `upgrade`  created: 2017-11-13 13:17:53 merged: 2017-12-05 09:54:15

212. [21278](http://github.com/cms-sw/cmssw/pull/21278){:target="_blank"}  from **@davidlt**: Fix various string related errors `alca`  `analysis`  `dqm`  `reconstruction`  created: 2017-11-11 13:23:27 merged: 2017-11-19 14:45:44

213. [21266](http://github.com/cms-sw/cmssw/pull/21266){:target="_blank"}  from **@mmusich**: [10.0.X] Add Payload Inspector for AlCaRecoTriggerBits `db`  `hlt`  created: 2017-11-10 16:10:10 merged: 2017-11-22 08:11:17

214. [21265](http://github.com/cms-sw/cmssw/pull/21265){:target="_blank"}  from **@mmusich**: [10.0.x] Update of SiStrip PI classes `db`  created: 2017-11-10 16:10:03 merged: 2017-11-20 11:07:22

215. [21262](http://github.com/cms-sw/cmssw/pull/21262){:target="_blank"}  from **@FHead**: Offline trigger DQM for HighPT for pp reference run `dqm`  created: 2017-11-10 15:02:52 merged: 2017-11-15 17:50:56

216. [21252](http://github.com/cms-sw/cmssw/pull/21252){:target="_blank"}  from **@perrotta**: Solve a possible bug found in RecoMuon/MuonIdentification/src/MuonShowerInformationFiller.cc `reconstruction`  created: 2017-11-10 09:23:25 merged: 2017-12-06 10:41:32

217. [21244](http://github.com/cms-sw/cmssw/pull/21244){:target="_blank"}  from **@mrodozov**: Removing ambiguous assertion from unit test TestCondFormatsJetMETObjectsJetCorrectorParameters `analysis`  `db`  created: 2017-11-09 16:43:48 merged: 2017-11-16 09:56:27

218. [21221](http://github.com/cms-sw/cmssw/pull/21221){:target="_blank"}  from **@mrodozov**: Remove unused vars in multiple pkgs `analysis`  `dqm`  `geometry`  `l1`  created: 2017-11-08 16:15:06 merged: 2017-11-24 09:17:05

219. [21204](http://github.com/cms-sw/cmssw/pull/21204){:target="_blank"}  from **@christopheralanwest**: Implement HCAL SiPM nonlinearity in LUTs `alca`  `l1`  created: 2017-11-07 18:29:06 merged: 2017-11-30 14:58:34

220. [21203](http://github.com/cms-sw/cmssw/pull/21203){:target="_blank"}  from **@jiafulow**: Fix L1TMuonEndCap warning regarding Phase 2 iRPC hits `l1`  `upgrade`  created: 2017-11-07 17:41:02 merged: 2017-11-15 17:54:21

221. [21186](http://github.com/cms-sw/cmssw/pull/21186){:target="_blank"}  from **@cms-tau-pog**: Temporary fix of TQAF unit tests after TauID update  `analysis`  created: 2017-11-06 15:59:53 merged: 2017-11-23 17:19:58

222. [21182](http://github.com/cms-sw/cmssw/pull/21182){:target="_blank"}  from **@vukasinmilosevic**: Change locations of DQM modules as requested in CMSLITDPG-318 `dqm`  created: 2017-11-06 13:27:43 merged: 2017-11-16 10:14:18

223. [21168](http://github.com/cms-sw/cmssw/pull/21168){:target="_blank"}  from **@cmadrid1**: HBHE: Adding new scintillator+Y11, 206, and 207 shapes for simulation and 2018 Data `alca`  `reconstruction`  `simulation`  `upgrade`  created: 2017-11-04 15:37:16 merged: 2017-12-07 13:05:26

224. [21164](http://github.com/cms-sw/cmssw/pull/21164){:target="_blank"}  from **@efeyazgan**: Create Pythia8CUEP8M2T4Settings_cfi.py `generators`  created: 2017-11-03 21:25:16 merged: 2017-11-18 16:48:12

225. [21152](http://github.com/cms-sw/cmssw/pull/21152){:target="_blank"}  from **@jkunkle**: add HCAL laser monitoring charge `analysis`  `reconstruction`  created: 2017-11-03 16:39:53 merged: 2017-12-04 08:56:46

226. [21147](http://github.com/cms-sw/cmssw/pull/21147){:target="_blank"}  from **@VinInn**: Add method to return the significance of a track inside a Det `reconstruction`  `simulation`  created: 2017-11-03 09:32:49 merged: 2017-11-15 15:23:29

227. [21144](http://github.com/cms-sw/cmssw/pull/21144){:target="_blank"}  from **@bcmcms**: Hcal relval update 9_X_Y digi amplitude `dqm`  created: 2017-11-02 22:19:51 merged: 2017-11-15 08:14:28

228. [21139](http://github.com/cms-sw/cmssw/pull/21139){:target="_blank"}  from **@AndreasAlbert**: ZCounting: Add electron channel. `dqm`  created: 2017-11-02 16:37:37 merged: 2017-12-04 08:57:02

229. [21137](http://github.com/cms-sw/cmssw/pull/21137){:target="_blank"}  from **@lpernie**: [10.0.X] Update GT: Update all L1T tags `alca`  `dqm`  `l1`  created: 2017-11-02 15:45:39 merged: 2017-11-20 17:35:31

230. [21134](http://github.com/cms-sw/cmssw/pull/21134){:target="_blank"}  from **@slehti**: HLTTauValidation: changed DQMBaseFolder from HLT/TauRelVal to HLT/TAU `dqm`  created: 2017-11-02 13:43:48 merged: 2017-11-20 08:45:15

231. [21037](http://github.com/cms-sw/cmssw/pull/21037){:target="_blank"}  from **@nsmith-**: HGCal EGamma ID helpers and Phase-II MiniAOD `analysis`  `reconstruction`  `upgrade`  created: 2017-10-26 23:42:37 merged: 2017-11-30 14:59:33

232. [21021](http://github.com/cms-sw/cmssw/pull/21021){:target="_blank"}  from **@gsfs**: New beam spots `operations`  `simulation`  created: 2017-10-25 18:12:44 merged: 2017-11-17 14:13:13

233. [21017](http://github.com/cms-sw/cmssw/pull/21017){:target="_blank"}  from **@boundino**: Add a fast version of existing 2-prong D trigger filter and a new 3-prong trigger filter in 10_0_X `hlt`  created: 2017-10-25 15:15:22 merged: 2017-11-24 17:58:16

234. [20969](http://github.com/cms-sw/cmssw/pull/20969){:target="_blank"}  from **@dtsitson**: Dedicated timing plots for L1T objects - Online DQM & L1T - CMSSW_9_4_X `dqm`  created: 2017-10-19 08:25:46 merged: 2017-11-18 16:52:18

235. [20879](http://github.com/cms-sw/cmssw/pull/20879){:target="_blank"}  from **@gartung**: cms.Sequence->cms.Task conversion for reconstruction `fastsim`  `reconstruction`  created: 2017-10-10 14:52:50 merged: 2017-11-27 20:23:12

236. [20683](http://github.com/cms-sw/cmssw/pull/20683){:target="_blank"}  from **@perrozzi**: fwd-port HTXS to master `generators`  created: 2017-09-28 02:43:22 merged: 2017-12-01 16:02:09

237. [20640](http://github.com/cms-sw/cmssw/pull/20640){:target="_blank"}  from **@lgray**: Add possibility to cut on timing to IVF `analysis`  `reconstruction`  `upgrade`  created: 2017-09-24 15:21:56 merged: 2017-11-16 10:04:46

238. [20509](http://github.com/cms-sw/cmssw/pull/20509){:target="_blank"}  from **@dildick**: GEM-CSC local trigger: make ME11 and ME21 TMBs inherit from same base class `l1`  `simulation`  `upgrade`  created: 2017-09-14 03:53:36 merged: 2017-12-05 09:55:06

239. [20249](http://github.com/cms-sw/cmssw/pull/20249){:target="_blank"}  from **@dildick**: Modifier for high-lumi CSC L1 local trigger algorithms `operations`  created: 2017-08-23 20:48:05 merged: 2017-12-07 12:45:56

240. [20166](http://github.com/cms-sw/cmssw/pull/20166){:target="_blank"}  from **@rappoccio**: B2G DQM for dilepton paths `dqm`  created: 2017-08-14 20:34:56 merged: 2017-11-16 09:58:48

#### CMSDIST Changes between Tags REL/CMSSW_10_0_0_pre1/slc6_amd64_gcc630 and REL/CMSSW_10_0_0_pre2/slc6_amd64_gcc630:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_10_0_0_pre1/slc6_amd64_gcc630...REL/CMSSW_10_0_0_pre2/slc6_amd64_gcc630)



1. [3611](http://github.com/cms-sw/cmsdist/pull/3611){:target="_blank"}  from **@mrodozov**: Updated root to tip of branch v6-10-00-patches created: 2017-11-29 15:10:08 merged: 2017-11-30 07:38:24

2. [3610](http://github.com/cms-sw/cmsdist/pull/3610){:target="_blank"}  from **@fwyzard**: update Intel tools for CMSSW 10.0.x created: 2017-11-28 22:27:27 merged: 2017-11-29 16:29:44

3. [3603](http://github.com/cms-sw/cmsdist/pull/3603){:target="_blank"}  from **@cms-sw**: backport boost and eigen changes for cuda created: 2017-11-27 10:17:31 merged: 2017-11-30 07:39:12

4. [3599](http://github.com/cms-sw/cmsdist/pull/3599){:target="_blank"}  from **@cms-sw**: updated build rules to fix the generation of python init files for deleted packages created: 2017-11-24 15:53:23 merged: 2017-11-25 08:14:00

5. [3595](http://github.com/cms-sw/cmsdist/pull/3595){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2017-11-22 21:43:16 merged: 2017-11-23 08:46:32

6. [3592](http://github.com/cms-sw/cmsdist/pull/3592){:target="_blank"}  from **@cms-sw**: Updating GeneratorInterface-EvtGenInterface to to new tag V02-00-09 created: 2017-11-22 14:48:14 merged: 2017-11-27 18:39:23

7. [3590](http://github.com/cms-sw/cmsdist/pull/3590){:target="_blank"}  from **@cms-sw**: Update cms-git-tools.spec created: 2017-11-20 11:13:07 merged: 2017-11-20 11:13:15

8. [3578](http://github.com/cms-sw/cmsdist/pull/3578){:target="_blank"}  from **@cms-sw**: Revert tensorflow changes for thread management created: 2017-11-15 15:52:11 merged: 2017-11-15 18:23:25
