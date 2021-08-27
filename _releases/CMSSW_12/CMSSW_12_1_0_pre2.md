---
layout: post
rel_link:  "12_1_0_pre2"
title:  "CMSSW_12_1_0_pre2"
date:   2021-08-26 00:45:00
categories: cmssw
relmajor: 12
relminor: 1
relsubminor: 0
relpre: _pre2
---

# CMSSW_12_1_0_pre2
#### Changes since CMSSW_12_1_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_1_0_pre1...CMSSW_12_1_0_pre2)



1. [35001](http://github.com/cms-sw/cmssw/pull/35001){:target="_blank"}  from **@gartung**: Utilities/StaticAnalyzers: Update function dumper to not add virtual at the end of function calls `core` created: 2021-08-24 20:23:43 merged: 2021-08-25 03:07:07

2. [34999](http://github.com/cms-sw/cmssw/pull/34999){:target="_blank"}  from **@Dr15Jones**: Use sufficient digits when converting a double `core` created: 2021-08-24 18:12:20 merged: 2021-08-25 13:02:52

3. [34998](http://github.com/cms-sw/cmssw/pull/34998){:target="_blank"}  from **@bsunanda**: Run3-hcx313 Rearrange the .h files in SimCalorimetry/HcalZeroSuppressionProducers `simulation` created: 2021-08-24 17:50:10 merged: 2021-08-25 07:03:54

4. [34996](http://github.com/cms-sw/cmssw/pull/34996){:target="_blank"}  from **@makortel**: Migrate classes deriving from IsoDepositExtractor to esConsumes() `reconstruction` created: 2021-08-24 14:51:11 merged: 2021-08-25 03:06:46

5. [34992](http://github.com/cms-sw/cmssw/pull/34992){:target="_blank"}  from **@missirol**: Fixing some edge cases in HLT-Patatrack customisations `hlt` created: 2021-08-24 09:36:08 merged: 2021-08-25 09:18:25

6. [34984](http://github.com/cms-sw/cmssw/pull/34984){:target="_blank"}  from **@Dr15Jones**: Fix infrequent deadlock in edm::ThreadHandoff `simulation` created: 2021-08-23 15:42:16 merged: 2021-08-24 01:05:58

7. [34983](http://github.com/cms-sw/cmssw/pull/34983){:target="_blank"}  from **@bsunanda**: Run3-gex90 Make unique material names as default for all Run3 scenarios `geometry` `upgrade` created: 2021-08-23 15:01:08 merged: 2021-08-25 13:37:20

8. [34982](http://github.com/cms-sw/cmssw/pull/34982){:target="_blank"}  from **@Dr15Jones**: Avoid memory overwrites in Ecal PayloadInspectors `db` created: 2021-08-23 14:37:04 merged: 2021-08-23 20:17:58

9. [34980](http://github.com/cms-sw/cmssw/pull/34980){:target="_blank"}  from **@bsunanda**: Run3-alca198 Modify the analyzers to record muons not on event basis but on single muon basis `alca` created: 2021-08-23 13:09:30 merged: 2021-08-25 10:32:34

10. [34977](http://github.com/cms-sw/cmssw/pull/34977){:target="_blank"}  from **@smuzaffar**: [Framework] Move publically used private headers in to interface dir `core` created: 2021-08-23 10:42:44 merged: 2021-08-24 13:17:03

11. [34976](http://github.com/cms-sw/cmssw/pull/34976){:target="_blank"}  from **@Purva-Chaudhari**: Remove boost lexical_cast dependency in FWCore `core` created: 2021-08-23 09:50:11 merged: 2021-08-24 01:09:03

12. [34974](http://github.com/cms-sw/cmssw/pull/34974){:target="_blank"}  from **@cvuosalo**: [DD4hep] Revise order of materials to prevent delayed resolution of references `geometry` created: 2021-08-23 03:11:52 merged: 2021-08-24 08:43:06

13. [34973](http://github.com/cms-sw/cmssw/pull/34973){:target="_blank"}  from **@jeongeun**: Migrate module configuration in PhysicsTools to use default cfipython `reconstruction` created: 2021-08-21 18:17:24 merged: 2021-08-24 14:25:20

14. [34972](http://github.com/cms-sw/cmssw/pull/34972){:target="_blank"}  from **@bsunanda**: Run3-hcx310 Put back HcalDigiProducer.cc in SimCalorimetry/HcalSimProducers/src `simulation` created: 2021-08-21 14:39:37 merged: 2021-08-22 08:46:34

15. [34969](http://github.com/cms-sw/cmssw/pull/34969){:target="_blank"}  from **@makortel**: Migrate TrackingParticleNumberOfLayersProducer to esConsumes() `simulation` created: 2021-08-20 20:11:20 merged: 2021-08-21 09:44:15

16. [34968](http://github.com/cms-sw/cmssw/pull/34968){:target="_blank"}  from **@makortel**: Restore cms::cuda::ESProduct construction without GPU `heterogeneous` created: 2021-08-20 19:55:28 merged: 2021-08-21 13:35:05

17. [34967](http://github.com/cms-sw/cmssw/pull/34967){:target="_blank"}  from **@makortel**: Migrate some modules in SimTracker to esConsumes() `simulation` created: 2021-08-20 19:23:14 merged: 2021-08-21 09:41:00

18. [34965](http://github.com/cms-sw/cmssw/pull/34965){:target="_blank"}  from **@bsunanda**: Run3-alca197 Add a possible AlCa stream for IsoTrackFilter useful for MC productions `alca` `operations` created: 2021-08-20 17:44:37 merged: 2021-08-24 09:01:22

19. [34964](http://github.com/cms-sw/cmssw/pull/34964){:target="_blank"}  from **@bsunanda**: Run3-sim103 Add tools to study big xml file which goes in the DB `dqm` `geometry` `simulation` created: 2021-08-20 15:09:03 merged: 2021-08-23 07:41:07

20. [34963](http://github.com/cms-sw/cmssw/pull/34963){:target="_blank"}  from **@abhih1**: Migrate leftover ECAL DQM codes to ESConsumes `dqm` created: 2021-08-20 14:05:15 merged: 2021-08-23 16:01:01

21. [34962](http://github.com/cms-sw/cmssw/pull/34962){:target="_blank"}  from **@slava77**: initialize TrackstersProducer::iterIndex_ to 0 `reconstruction` `upgrade` created: 2021-08-20 13:02:41 merged: 2021-08-21 07:06:39

22. [34961](http://github.com/cms-sw/cmssw/pull/34961){:target="_blank"}  from **@makortel**: Migrate some modules in RecoHI to esConsumes() `reconstruction` created: 2021-08-20 01:10:46 merged: 2021-08-21 01:26:32

23. [34960](http://github.com/cms-sw/cmssw/pull/34960){:target="_blank"}  from **@osschar**: [Fireworks/Geometry] Strip topolgy for sub-classes of StripTopology was not exported to RECO geometry. `visualization` created: 2021-08-19 22:21:47 merged: 2021-08-20 21:18:49

24. [34959](http://github.com/cms-sw/cmssw/pull/34959){:target="_blank"}  from **@makortel**: Migrate some modules in RecoJets to esConsumes() `reconstruction` created: 2021-08-19 20:00:23 merged: 2021-08-21 01:25:54

25. [34958](http://github.com/cms-sw/cmssw/pull/34958){:target="_blank"}  from **@makortel**: Add public interface for constructing and freeing caching allocators `heterogeneous` created: 2021-08-19 17:32:59 merged: 2021-08-20 16:41:32

26. [34956](http://github.com/cms-sw/cmssw/pull/34956){:target="_blank"}  from **@fwyzard**: HLT customisation for Patatrack pixel tracks and GPU offload `hlt` created: 2021-08-19 15:35:54 merged: 2021-08-20 13:22:56

27. [34954](http://github.com/cms-sw/cmssw/pull/34954){:target="_blank"}  from **@lecriste**: [HGCAL] Improve validation scripts `dqm` created: 2021-08-19 13:06:47 merged: 2021-08-19 21:38:15

28. [34953](http://github.com/cms-sw/cmssw/pull/34953){:target="_blank"}  from **@abhih1**: Correct labels for a Trigger plot in ECAL DQM `dqm` created: 2021-08-19 12:56:44 merged: 2021-08-19 21:20:29

29. [34951](http://github.com/cms-sw/cmssw/pull/34951){:target="_blank"}  from **@mtosi**: fix typo in the gen fragment file name `generators` created: 2021-08-19 12:15:26 merged: 2021-08-19 17:12:07

30. [34948](http://github.com/cms-sw/cmssw/pull/34948){:target="_blank"}  from **@fwyzard**: Fix uploading the EventSetup conditions to multiple CUDA devices `heterogeneous` created: 2021-08-19 09:30:23 merged: 2021-08-19 21:24:11

31. [34945](http://github.com/cms-sw/cmssw/pull/34945){:target="_blank"}  from **@makortel**: Migrate RPCRecHitProducer to esConsumes() `reconstruction` created: 2021-08-19 01:56:04 merged: 2021-08-23 13:14:25

32. [34944](http://github.com/cms-sw/cmssw/pull/34944){:target="_blank"}  from **@makortel**: Remove MuonToSimAssociatorBase, MuonToSimAssociatorByHits, and TrackAssociatorRecord as obsolete `analysis` `alca` `dqm` `reconstruction` `simulation` created: 2021-08-19 01:14:30 merged: 2021-08-21 06:28:24

33. [34943](http://github.com/cms-sw/cmssw/pull/34943){:target="_blank"}  from **@makortel**: Migrate some modules in RecoMET to esConsumes() `reconstruction` created: 2021-08-19 00:20:00 merged: 2021-08-21 01:28:51

34. [34941](http://github.com/cms-sw/cmssw/pull/34941){:target="_blank"}  from **@Dr15Jones**: Better reporting of CPU timing `core` created: 2021-08-18 19:53:48 merged: 2021-08-19 13:14:05

35. [34940](http://github.com/cms-sw/cmssw/pull/34940){:target="_blank"}  from **@bsunanda**: Run3-hcx309 Rearrange the files to remove .h files from SimCalorimetry/HcalSimProducers/src `simulation` created: 2021-08-18 19:53:25 merged: 2021-08-20 21:14:47

36. [34939](http://github.com/cms-sw/cmssw/pull/34939){:target="_blank"}  from **@bsunanda**: Run3-hcx308 Rearrange the files to remove .h files from SimCalorimetry/CastorSim/src `simulation` created: 2021-08-18 19:27:50 merged: 2021-08-20 21:14:03

37. [34938](http://github.com/cms-sw/cmssw/pull/34938){:target="_blank"}  from **@makortel**: Migrate PFSimParticleProducer to esConsumes() `reconstruction` created: 2021-08-18 18:52:55 merged: 2021-08-21 01:24:40

38. [34935](http://github.com/cms-sw/cmssw/pull/34935){:target="_blank"}  from **@makortel**: Migrate PFTauPrimaryVertexProducerBase to esConsumes() `reconstruction` created: 2021-08-18 16:53:01 merged: 2021-08-21 01:23:40

39. [34934](http://github.com/cms-sw/cmssw/pull/34934){:target="_blank"}  from **@makortel**: Migrate some modules in RecoTracker to esConsumes() `reconstruction` created: 2021-08-18 16:34:37 merged: 2021-08-21 01:29:26

40. [34931](http://github.com/cms-sw/cmssw/pull/34931){:target="_blank"}  from **@pieterdavid**: Update pileupCal.py using numpy `db` created: 2021-08-18 12:39:38 merged: 2021-08-24 01:06:52

41. [34929](http://github.com/cms-sw/cmssw/pull/34929){:target="_blank"}  from **@fwyzard**: Fix radix sort test `heterogeneous` created: 2021-08-18 07:37:41 merged: 2021-08-18 11:49:05

42. [34928](http://github.com/cms-sw/cmssw/pull/34928){:target="_blank"}  from **@bsunanda**: Run3-sim102 Correct the cfg's so that they can work `simulation` created: 2021-08-17 23:49:50 merged: 2021-08-18 08:51:07

43. [34927](http://github.com/cms-sw/cmssw/pull/34927){:target="_blank"}  from **@bsunanda**: Run3-gex89 Attempt to define unqiue names of materials everywhere `geometry` `upgrade` created: 2021-08-17 22:44:46 merged: 2021-08-23 06:31:48

44. [34926](http://github.com/cms-sw/cmssw/pull/34926){:target="_blank"}  from **@Dr15Jones**: Simplify setting EDPutTokenT via call to produces `core` created: 2021-08-17 21:33:44 merged: 2021-08-21 01:28:06

45. [34924](http://github.com/cms-sw/cmssw/pull/34924){:target="_blank"}  from **@makortel**: Migrate (Cosmic)ParametersDefinerForTP to esConsumes() `dqm` `simulation` created: 2021-08-17 20:49:39 merged: 2021-08-18 19:50:34

46. [34922](http://github.com/cms-sw/cmssw/pull/34922){:target="_blank"}  from **@tvami**: Add HCAL tag `HcalRespCorrs_2021_v3.0_mc` to Run-3 MC GTs `alca` created: 2021-08-17 18:32:58 merged: 2021-08-23 20:08:37

47. [34921](http://github.com/cms-sw/cmssw/pull/34921){:target="_blank"}  from **@trackreco**: Update of mkFit for 12_1_0_pre2 `operations` `reconstruction` created: 2021-08-17 17:33:54 merged: 2021-08-25 06:35:32

48. [34919](http://github.com/cms-sw/cmssw/pull/34919){:target="_blank"}  from **@smuzaffar**: [Reco] Fixes needed to avoid exposing private headers via interface dir `reconstruction` created: 2021-08-17 16:24:53 merged: 2021-08-20 14:03:01

49. [34916](http://github.com/cms-sw/cmssw/pull/34916){:target="_blank"}  from **@Dr15Jones**: Move Guid.h to interface `core` created: 2021-08-17 15:17:27 merged: 2021-08-17 21:13:36

50. [34915](http://github.com/cms-sw/cmssw/pull/34915){:target="_blank"}  from **@Dr15Jones**: Created setupSiteLocalConfig `core` created: 2021-08-17 14:23:04 merged: 2021-08-17 21:01:40

51. [34914](http://github.com/cms-sw/cmssw/pull/34914){:target="_blank"}  from **@Dr15Jones**: Consolidated GLBMuonAnalyzer into one file `reconstruction` created: 2021-08-17 14:20:47 merged: 2021-08-19 14:48:25

52. [34913](http://github.com/cms-sw/cmssw/pull/34913){:target="_blank"}  from **@smuzaffar**: [PhysicsTools] Move icc file used by public interface in to interface `analysis` created: 2021-08-17 13:56:30 merged: 2021-08-18 01:45:07

53. [34912](http://github.com/cms-sw/cmssw/pull/34912){:target="_blank"}  from **@smorovic**: (DAQ) input source - minimum starting lumisection `daq` `reconstruction` created: 2021-08-17 13:55:58 merged: 2021-08-17 21:21:03

54. [34911](http://github.com/cms-sw/cmssw/pull/34911){:target="_blank"}  from **@smuzaffar**: [HLTriggerOffline] Move Higgs sources in to plugins dir `dqm` created: 2021-08-17 13:47:22 merged: 2021-08-17 21:11:51

55. [34910](http://github.com/cms-sw/cmssw/pull/34910){:target="_blank"}  from **@makortel**: Complete migration of TrackClassifier to esConsumes() `simulation` created: 2021-08-17 13:32:41 merged: 2021-08-18 08:54:28

56. [34909](http://github.com/cms-sw/cmssw/pull/34909){:target="_blank"}  from **@apsallid**: [HGCAL] make makeHGCalValidationPlots.py executable again `dqm` created: 2021-08-17 13:30:14 merged: 2021-08-17 14:10:12

57. [34908](http://github.com/cms-sw/cmssw/pull/34908){:target="_blank"}  from **@bainbrid**: LowPtElectrons: convert Seed BDTs from XML to ROOT file format `reconstruction` created: 2021-08-17 13:23:41 merged: 2021-08-19 15:24:22

58. [34907](http://github.com/cms-sw/cmssw/pull/34907){:target="_blank"}  from **@smuzaffar**: [Geometry] Move public headers in to interface dir `geometry` created: 2021-08-17 12:51:48 merged: 2021-08-18 08:53:04

59. [34905](http://github.com/cms-sw/cmssw/pull/34905){:target="_blank"}  from **@smuzaffar**: [Validation] Use correct header for ParametersDefinerForTP `dqm` created: 2021-08-17 12:21:18 merged: 2021-08-17 21:10:31

60. [34904](http://github.com/cms-sw/cmssw/pull/34904){:target="_blank"}  from **@smuzaffar**: [Validation] Move EcalDigis sources in to plugins dir `dqm` created: 2021-08-17 12:08:45 merged: 2021-08-19 06:00:38

61. [34903](http://github.com/cms-sw/cmssw/pull/34903){:target="_blank"}  from **@smuzaffar**: [GCC10] Use constexpr which fixes gcc10/ASAN build error `alca` created: 2021-08-17 06:09:55 merged: 2021-08-17 12:19:14

62. [34900](http://github.com/cms-sw/cmssw/pull/34900){:target="_blank"}  from **@mmusich**: Do not produce NaNs in `SiPixelActionExecutor` `dqm` created: 2021-08-16 20:17:23 merged: 2021-08-17 08:46:12

63. [34899](http://github.com/cms-sw/cmssw/pull/34899){:target="_blank"}  from **@Dr15Jones**: Run G4 workers on their own dedicated threads `simulation` created: 2021-08-16 19:48:01 merged: 2021-08-19 05:57:44

64. [34897](http://github.com/cms-sw/cmssw/pull/34897){:target="_blank"}  from **@smuzaffar**: [Calib] Move private header in to src directory `alca` created: 2021-08-16 17:00:17 merged: 2021-08-16 20:25:58

65. [34896](http://github.com/cms-sw/cmssw/pull/34896){:target="_blank"}  from **@smuzaffar**: [Fireworks] Move public headers in to interface directory `visualization` created: 2021-08-16 16:49:12 merged: 2021-08-17 01:27:12

66. [34894](http://github.com/cms-sw/cmssw/pull/34894){:target="_blank"}  from **@smuzaffar**: [Generator] Move public headers in to interface directory `generators` created: 2021-08-16 16:01:44 merged: 2021-08-17 15:12:44

67. [34893](http://github.com/cms-sw/cmssw/pull/34893){:target="_blank"}  from **@smuzaffar**: [CommonTools] Move public headers in to interface directory `dqm` `reconstruction` created: 2021-08-16 15:26:56 merged: 2021-08-17 17:43:02

68. [34892](http://github.com/cms-sw/cmssw/pull/34892){:target="_blank"}  from **@tvami**: Fix typo in the RelMon category  `dqm` created: 2021-08-16 14:43:12 merged: 2021-08-16 20:17:04

69. [34891](http://github.com/cms-sw/cmssw/pull/34891){:target="_blank"}  from **@Dr15Jones**: Moved headers from src to interface in FWCore/Framework `core` created: 2021-08-16 13:49:40 merged: 2021-08-17 21:02:11

70. [34887](http://github.com/cms-sw/cmssw/pull/34887){:target="_blank"}  from **@yuanchao**: Remove unused headers for CommonTools packages `reconstruction` created: 2021-08-16 11:32:15 merged: 2021-08-25 06:59:06

71. [34886](http://github.com/cms-sw/cmssw/pull/34886){:target="_blank"}  from **@smuzaffar**: BuildFile: use py3-sqlalchemy `db` created: 2021-08-16 11:11:01 merged: 2021-08-16 15:29:30

72. [34885](http://github.com/cms-sw/cmssw/pull/34885){:target="_blank"}  from **@mmusich**: migrate `AlignmentProducer` to event consumes `alca` created: 2021-08-16 10:59:40 merged: 2021-08-19 05:49:32

73. [34883](http://github.com/cms-sw/cmssw/pull/34883){:target="_blank"}  from **@smuzaffar**: Buildfile cleanup: remove non-existing module.cc file `simulation` created: 2021-08-16 08:58:16 merged: 2021-08-16 20:18:41

74. [34881](http://github.com/cms-sw/cmssw/pull/34881){:target="_blank"}  from **@mmusich**: [Alignment/HIPAlignmentAlgorithm] modernize `LhcTrackAnalyzer` `alca` created: 2021-08-14 16:48:41 merged: 2021-08-16 01:52:07

75. [34879](http://github.com/cms-sw/cmssw/pull/34879){:target="_blank"}  from **@bsunanda**: Run3-gex88 Make P5 as the default for 2021 scenarios `geometry` `upgrade` created: 2021-08-13 21:00:36 merged: 2021-08-16 10:10:45

76. [34876](http://github.com/cms-sw/cmssw/pull/34876){:target="_blank"}  from **@mmusich**: [Tracker Alignment] Miscellaneous fixes in `Alignment/OfflineValidation` all-in-one tool `alca` created: 2021-08-13 19:06:33 merged: 2021-08-15 02:19:43

77. [34875](http://github.com/cms-sw/cmssw/pull/34875){:target="_blank"}  from **@kpedro88**: more Python3 fixes for geometry script `geometry` `upgrade` created: 2021-08-13 17:29:59 merged: 2021-08-16 07:54:47

78. [34874](http://github.com/cms-sw/cmssw/pull/34874){:target="_blank"}  from **@smuzaffar**: [DBG] Fixes needed for 08-12-2300 DBG IB `alca` `simulation` created: 2021-08-13 16:00:36 merged: 2021-08-16 12:51:29

79. [34872](http://github.com/cms-sw/cmssw/pull/34872){:target="_blank"}  from **@smuzaffar**: [IOMC] Move public headers to interface directory `core` `daq` `fastsim` `simulation` created: 2021-08-13 14:10:53 merged: 2021-08-19 06:02:31

80. [34871](http://github.com/cms-sw/cmssw/pull/34871){:target="_blank"}  from **@smuzaffar**: [Validation] Removed unnecessary include statements `dqm` created: 2021-08-13 13:40:35 merged: 2021-08-14 01:14:49

81. [34870](http://github.com/cms-sw/cmssw/pull/34870){:target="_blank"}  from **@smuzaffar**: [TkTrackingRegions] Move public headers to interface directory `reconstruction` created: 2021-08-13 13:10:03 merged: 2021-08-14 01:15:19

82. [34869](http://github.com/cms-sw/cmssw/pull/34869){:target="_blank"}  from **@iarspider**: Add missing include in CondDBTools.cc `db` created: 2021-08-13 13:06:57 merged: 2021-08-13 14:45:43

83. [34868](http://github.com/cms-sw/cmssw/pull/34868){:target="_blank"}  from **@smuzaffar**: [RecoTracker] Move public headers to interface directory `dqm` `reconstruction` created: 2021-08-13 10:51:23 merged: 2021-08-14 01:15:32

84. [34867](http://github.com/cms-sw/cmssw/pull/34867){:target="_blank"}  from **@smuzaffar**: [RecoPixelVertexing] Move public headers to interface directory `reconstruction` created: 2021-08-13 10:40:22 merged: 2021-08-14 01:15:56

85. [34866](http://github.com/cms-sw/cmssw/pull/34866){:target="_blank"}  from **@smuzaffar**: [Reco] Removed unnecessary include statements `alca` `reconstruction` `db` `upgrade` created: 2021-08-13 10:22:59 merged: 2021-08-17 21:36:23

86. [34865](http://github.com/cms-sw/cmssw/pull/34865){:target="_blank"}  from **@smuzaffar**: [Reco] Removed unnecessary include statements `hlt` `reconstruction` created: 2021-08-13 10:11:09 merged: 2021-08-18 12:24:28

87. [34864](http://github.com/cms-sw/cmssw/pull/34864){:target="_blank"}  from **@smuzaffar**: [RecoMuon] Remove unnecessary include statements to avoid private hdr deps `reconstruction` created: 2021-08-13 09:15:09 merged: 2021-08-14 01:16:15

88. [34863](http://github.com/cms-sw/cmssw/pull/34863){:target="_blank"}  from **@smuzaffar**: [L1TTrackMatch] Remove unnecessary include statements to avoid private hdr dep `l1` `upgrade` created: 2021-08-13 08:27:32 merged: 2021-08-18 01:49:26

89. [34862](http://github.com/cms-sw/cmssw/pull/34862){:target="_blank"}  from **@smuzaffar**: [DQM] Remove unnecessary include statements to avoid private header dep `dqm` created: 2021-08-13 08:22:08 merged: 2021-08-13 14:28:20

90. [34858](http://github.com/cms-sw/cmssw/pull/34858){:target="_blank"}  from **@slava77**: initialize Trackster::iterationIndex_ `reconstruction` `upgrade` created: 2021-08-12 17:51:55 merged: 2021-08-17 21:34:08

91. [34857](http://github.com/cms-sw/cmssw/pull/34857){:target="_blank"}  from **@bsunanda**: Run3-sim101 Modified the examination of geometry in XML and DB `simulation` created: 2021-08-12 15:50:46 merged: 2021-08-13 10:40:35

92. [34856](http://github.com/cms-sw/cmssw/pull/34856){:target="_blank"}  from **@bsunanda**: Run3-gex87 Modify material budget code relevant to study XML vs DB `dqm` `geometry` created: 2021-08-12 15:46:22 merged: 2021-08-13 06:07:13

93. [34855](http://github.com/cms-sw/cmssw/pull/34855){:target="_blank"}  from **@smuzaffar**: Coderule script: fixes needed for python3 `core` created: 2021-08-12 15:01:24 merged: 2021-08-13 01:59:36

94. [34853](http://github.com/cms-sw/cmssw/pull/34853){:target="_blank"}  from **@smuzaffar**: [CalibMuon] Move and merge .h and .cc files used by plugin `alca` `reconstruction` created: 2021-08-12 13:53:08 merged: 2021-08-15 02:20:19

95. [34852](http://github.com/cms-sw/cmssw/pull/34852){:target="_blank"}  from **@iarspider**: [GCC11] Fix warning: loop variable binds to a temporary `reconstruction` created: 2021-08-12 11:21:27 merged: 2021-08-13 02:03:17

96. [34849](http://github.com/cms-sw/cmssw/pull/34849){:target="_blank"}  from **@smuzaffar**: [SimCalorimetry] Avoid using private CondFormats/EcalObjects/src/classes.h `simulation` created: 2021-08-12 08:13:06 merged: 2021-08-13 02:00:21

97. [34848](http://github.com/cms-sw/cmssw/pull/34848){:target="_blank"}  from **@ggovi**: o2o tools fixes and improvements for python3 `db` created: 2021-08-12 07:09:04 merged: 2021-08-12 13:22:46

98. [34847](http://github.com/cms-sw/cmssw/pull/34847){:target="_blank"}  from **@ggovi**: CondCore/Utilities: cleaned up dependencies from CondCore/CondDB details `db` created: 2021-08-11 19:20:01 merged: 2021-08-12 08:28:39

99. [34846](http://github.com/cms-sw/cmssw/pull/34846){:target="_blank"}  from **@OzAmram**: Fix rare crash in pixel template interpolation `reconstruction` `db` created: 2021-08-11 18:48:26 merged: 2021-08-16 13:31:52

100. [34844](http://github.com/cms-sw/cmssw/pull/34844){:target="_blank"}  from **@CTPPS**: PPS Alignment - bug fix `alca` `db` created: 2021-08-11 14:28:35 merged: 2021-08-13 14:42:36

101. [34843](http://github.com/cms-sw/cmssw/pull/34843){:target="_blank"}  from **@jshlee**: GEM unpacker cleanup `reconstruction` `simulation` `upgrade` created: 2021-08-11 13:20:58 merged: 2021-08-19 01:03:41

102. [34842](http://github.com/cms-sw/cmssw/pull/34842){:target="_blank"}  from **@bsunanda**: Run3-sim100 Take Vladimir's comments for include statements of CLHEP headers `simulation` `upgrade` created: 2021-08-11 12:11:18 merged: 2021-08-13 02:01:07

103. [34837](http://github.com/cms-sw/cmssw/pull/34837){:target="_blank"}  from **@Dr15Jones**: Performance improvements for DQM startup `core` `dqm` created: 2021-08-11 01:02:30 merged: 2021-08-13 02:15:45

104. [34836](http://github.com/cms-sw/cmssw/pull/34836){:target="_blank"}  from **@bsunanda**: Run3-sim99 Collapse .h and .cc files in SimG4CMS/EcalTestBeam `simulation` created: 2021-08-10 20:05:43 merged: 2021-08-12 08:29:20

105. [34834](http://github.com/cms-sw/cmssw/pull/34834){:target="_blank"}  from **@jeongeun**: Migrate module configuration in RecoTauTag to use default cfipython `reconstruction` created: 2021-08-10 18:20:36 merged: 2021-08-17 10:42:15

106. [34833](http://github.com/cms-sw/cmssw/pull/34833){:target="_blank"}  from **@perrotta**: Remove dead assignments for ZToMuMuGammaAnalyzer and HGCalSimHitValidation `dqm` created: 2021-08-10 17:41:30 merged: 2021-08-13 14:26:01

107. [34832](http://github.com/cms-sw/cmssw/pull/34832){:target="_blank"}  from **@mmusich**: [RFC] add `commissioning_run` as DQM runType and use it in SiStrip online DQM client `dqm` created: 2021-08-10 17:10:08 merged: 2021-08-13 02:13:48

108. [34830](http://github.com/cms-sw/cmssw/pull/34830){:target="_blank"}  from **@bsunanda**: Run3-sim98 Collapse .h and .cc files in SimG4CMS/FP420 `simulation` created: 2021-08-10 16:45:15 merged: 2021-08-12 08:29:39

109. [34829](http://github.com/cms-sw/cmssw/pull/34829){:target="_blank"}  from **@bsunanda**: Run3-alca196 Collapse .h and .cc files in DQMOffline/CalibCalo and reorganize the files `dqm` created: 2021-08-10 16:34:35 merged: 2021-08-13 14:25:40

110. [34828](http://github.com/cms-sw/cmssw/pull/34828){:target="_blank"}  from **@mteroerd**: Validation plots for APE and bug fixes `alca` created: 2021-08-10 15:25:47 merged: 2021-08-14 01:33:47

111. [34827](http://github.com/cms-sw/cmssw/pull/34827){:target="_blank"}  from **@maaraujo94**: Adding an HLT filter based on PPS local track multiplicity conditions for selection of events for PPS PCL `hlt` created: 2021-08-10 14:29:03 merged: 2021-08-25 07:48:12

112. [34826](http://github.com/cms-sw/cmssw/pull/34826){:target="_blank"}  from **@smuzaffar**: Replace boost::regex with std::regex `db` created: 2021-08-10 13:53:41 merged: 2021-08-13 02:01:59

113. [34825](http://github.com/cms-sw/cmssw/pull/34825){:target="_blank"}  from **@iarspider**: [GCC11] Add missing #include for std::size_t definition `heterogeneous` created: 2021-08-10 08:01:51 merged: 2021-08-12 12:47:24

114. [34824](http://github.com/cms-sw/cmssw/pull/34824){:target="_blank"}  from **@iarspider**: [GCC11] Fix "this pointer is null" in class FWRecoGeometryESProducer of Fireworks/Geometry `visualization` created: 2021-08-10 07:49:07 merged: 2021-08-12 09:11:19

115. [34823](http://github.com/cms-sw/cmssw/pull/34823){:target="_blank"}  from **@bsunanda**: Run3-alca192B Change std::cout to edm::LogVerbatim in a number of classes in Calibration/IsolatedParticles `alca` created: 2021-08-09 16:08:08 merged: 2021-08-11 08:53:44

116. [34821](http://github.com/cms-sw/cmssw/pull/34821){:target="_blank"}  from **@yeckang**: GEM Validation update `dqm` `simulation` created: 2021-08-09 12:36:27 merged: 2021-08-15 02:21:48

117. [34820](http://github.com/cms-sw/cmssw/pull/34820){:target="_blank"}  from **@civanch**: OscarMTProducer clean-up `simulation` created: 2021-08-09 12:12:28 merged: 2021-08-10 01:45:17

118. [34819](http://github.com/cms-sw/cmssw/pull/34819){:target="_blank"}  from **@bsunanda**: Run3-sim97 Rearrange the files in SimG4CMS/ShowerLibraryProducer and collapse .h  and .cc files `simulation` created: 2021-08-08 15:12:37 merged: 2021-08-09 13:49:40

119. [34818](http://github.com/cms-sw/cmssw/pull/34818){:target="_blank"}  from **@jeongeun**: Migrate module configuration in RecoVertex to use default cfipython `reconstruction` created: 2021-08-08 12:12:36 merged: 2021-08-12 12:45:14

120. [34817](http://github.com/cms-sw/cmssw/pull/34817){:target="_blank"}  from **@jeongeun**: Migrate module configuration in RecoPixelVertexing to use default cfipython `reconstruction` created: 2021-08-08 05:41:21 merged: 2021-08-12 12:44:58

121. [34816](http://github.com/cms-sw/cmssw/pull/34816){:target="_blank"}  from **@bsunanda**: Run3-sim96 Rearrange the files in SimG4CMS/Forward and collaspse some of the .h and .cc files `simulation` created: 2021-08-07 19:53:39 merged: 2021-08-10 10:17:09

122. [34815](http://github.com/cms-sw/cmssw/pull/34815){:target="_blank"}  from **@Dr15Jones**: Better handling of timeout in FWCore/SharedMemory `core` created: 2021-08-06 21:12:41 merged: 2021-08-09 04:48:13

123. [34814](http://github.com/cms-sw/cmssw/pull/34814){:target="_blank"}  from **@bsunanda**: Run3-Sim95 Collapse .h and .cc files if possible in SimG4CMS/Calo `simulation` created: 2021-08-06 17:23:21 merged: 2021-08-07 02:15:28

124. [34813](http://github.com/cms-sw/cmssw/pull/34813){:target="_blank"}  from **@bsunanda**: Run3-alca192A Utilize edm::LogVerbatim instead of cout in a number of classes of Calibration/IsolatedParticles `alca` created: 2021-08-06 15:57:20 merged: 2021-08-09 13:49:24

125. [34809](http://github.com/cms-sw/cmssw/pull/34809){:target="_blank"}  from **@guitargeek**: Clean unused dependencies from BuildFiles `l1` `analysis` `alca` `dqm` `reconstruction` `simulation` `pdmv` `upgrade` created: 2021-08-05 22:21:47 merged: 2021-08-16 01:49:07

126. [34808](http://github.com/cms-sw/cmssw/pull/34808){:target="_blank"}  from **@hyunyong**: [BUGFIX] CocoaModel/src/Model.cc gcc11 compile error fix (issues #34756) `alca` created: 2021-08-05 22:17:00 merged: 2021-08-06 13:41:41

127. [34804](http://github.com/cms-sw/cmssw/pull/34804){:target="_blank"}  from **@colizz**: Fix the mergeLHE.py script `generators` created: 2021-08-05 19:02:47 merged: 2021-08-10 12:36:20

128. [34802](http://github.com/cms-sw/cmssw/pull/34802){:target="_blank"}  from **@Dr15Jones**: Create abstract XrdStatistics class `core` created: 2021-08-05 18:38:59 merged: 2021-08-06 06:36:48

129. [34800](http://github.com/cms-sw/cmssw/pull/34800){:target="_blank"}  from **@lecriste**: [HGCAL] From CaloParticle to SimTrackster in the Validation linking section `dqm` `reconstruction` `upgrade` created: 2021-08-05 17:01:55 merged: 2021-08-15 09:32:30

130. [34798](http://github.com/cms-sw/cmssw/pull/34798){:target="_blank"}  from **@Dr15Jones**: Fix loop in PFJetIDSelectionFunctor `reconstruction` created: 2021-08-05 16:19:14 merged: 2021-08-06 06:39:12

131. [34796](http://github.com/cms-sw/cmssw/pull/34796){:target="_blank"}  from **@bsunanda**: Run3-sim94 Rearranging the files in SimG4CMS/Forward `simulation` created: 2021-08-05 15:04:27 merged: 2021-08-06 11:51:18

132. [34794](http://github.com/cms-sw/cmssw/pull/34794){:target="_blank"}  from **@perrotta**: Remove dead code and apply one fix in DQM/L1TMonitor `dqm` created: 2021-08-05 14:30:09 merged: 2021-08-10 07:51:21

133. [34793](http://github.com/cms-sw/cmssw/pull/34793){:target="_blank"}  from **@Dr15Jones**: Add additional paths to customizeHLTIter0ToMkFit `reconstruction` created: 2021-08-05 14:18:08 merged: 2021-08-07 02:23:56

134. [34792](http://github.com/cms-sw/cmssw/pull/34792){:target="_blank"}  from **@theofil**: Herwig6 header files from non-interace, related to #34718 `generators` created: 2021-08-05 13:51:28 merged: 2021-08-05 19:12:53

135. [34791](http://github.com/cms-sw/cmssw/pull/34791){:target="_blank"}  from **@bsunanda**: Phase2-TB63Z Rearrange the header file and make first example for dd4hep (replacing #34752) `simulation` `upgrade` created: 2021-08-05 13:49:33 merged: 2021-08-09 13:33:28

136. [34786](http://github.com/cms-sw/cmssw/pull/34786){:target="_blank"}  from **@abdoulline**: HCAL:  HF SimHits timing fix `geometry` `simulation` created: 2021-08-05 06:18:21 merged: 2021-08-06 06:40:35

137. [34784](http://github.com/cms-sw/cmssw/pull/34784){:target="_blank"}  from **@bsunanda**: Run3-alca193 Add DQM for HcalIterativePhiSymAlCaReco `dqm` `operations` created: 2021-08-05 00:17:52 merged: 2021-08-10 08:39:16

138. [34783](http://github.com/cms-sw/cmssw/pull/34783){:target="_blank"}  from **@dildick**: New option in CSC DigiToRaw to pack strip digis by CFEB in each chamber.  `reconstruction` `simulation` created: 2021-08-04 21:47:06 merged: 2021-08-25 09:12:14

139. [34776](http://github.com/cms-sw/cmssw/pull/34776){:target="_blank"}  from **@bsunanda**: Run3-alca192 Add a few methods in Calibration/IsolatedParticles `alca` created: 2021-08-04 15:25:29 merged: 2021-08-10 05:54:25

140. [34773](http://github.com/cms-sw/cmssw/pull/34773){:target="_blank"}  from **@smuzaffar**: [DQM] Cleanup for private header usage `dqm` created: 2021-08-04 14:48:52 merged: 2021-08-10 07:39:45

141. [34772](http://github.com/cms-sw/cmssw/pull/34772){:target="_blank"}  from **@iarspider**: [GCC 11] Fix "this pointer is null" in RecoJets/JetProducers PileupJetIdAlgo `reconstruction` created: 2021-08-04 14:38:26 merged: 2021-08-05 05:48:17

142. [34771](http://github.com/cms-sw/cmssw/pull/34771){:target="_blank"}  from **@Dr15Jones**: Make header files in FWCore/Framework/interface consistent `core` `dqm` `simulation` created: 2021-08-04 14:23:06 merged: 2021-08-13 02:14:40

143. [34770](http://github.com/cms-sw/cmssw/pull/34770){:target="_blank"}  from **@bsunanda**: Run3-TB63 Rearrange the files in SimG4CMS/HcalTestBeam `simulation` created: 2021-08-04 14:00:44 merged: 2021-08-05 12:56:01

144. [34769](http://github.com/cms-sw/cmssw/pull/34769){:target="_blank"}  from **@iarspider**: [GCC 11] Fix error "this pointer is null" in PhysicsTools/FWLite `analysis` created: 2021-08-04 14:00:15 merged: 2021-08-05 19:21:19

145. [34767](http://github.com/cms-sw/cmssw/pull/34767){:target="_blank"}  from **@iarspider**: [GCC 11] Fix error "this pointer is null" in L1Trigger/DTTrigger `l1` created: 2021-08-04 13:25:52 merged: 2021-08-18 15:27:20

146. [34765](http://github.com/cms-sw/cmssw/pull/34765){:target="_blank"}  from **@thomreis**: Fix crash of ECAL GPU reco when ECAL is out of the run. `reconstruction` created: 2021-08-04 13:18:49 merged: 2021-08-04 20:05:13

147. [34764](http://github.com/cms-sw/cmssw/pull/34764){:target="_blank"}  from **@iarspider**: [GCC 11] Fix error: 'this' pointer is null in Fireworks/Geometry `visualization` created: 2021-08-04 12:56:06 merged: 2021-08-04 20:27:34

148. [34763](http://github.com/cms-sw/cmssw/pull/34763){:target="_blank"}  from **@smuzaffar**: [MagneticField] Move public headers to interface directory `pdmv` `reconstruction` created: 2021-08-04 11:07:24 merged: 2021-08-05 12:23:14

149. [34762](http://github.com/cms-sw/cmssw/pull/34762){:target="_blank"}  from **@smuzaffar**: [DataFormat] Cleanup unnecessary includes of DF private headers `alca` `daq` `db` `reconstruction` created: 2021-08-04 10:19:37 merged: 2021-08-05 08:49:39

150. [34761](http://github.com/cms-sw/cmssw/pull/34761){:target="_blank"}  from **@smuzaffar**: [Calib] Move public headers to interface directory `l1` `alca` `reconstruction` `db` created: 2021-08-04 10:06:49 merged: 2021-08-12 08:42:24

151. [34759](http://github.com/cms-sw/cmssw/pull/34759){:target="_blank"}  from **@ChrisMisan**: Diamond Sampic reco `reconstruction` created: 2021-08-04 09:11:48 merged: 2021-08-14 01:36:41

152. [34758](http://github.com/cms-sw/cmssw/pull/34758){:target="_blank"}  from **@iarspider**: [GCC 11] Fix error "this pointer is null" in DQM/SiStripCommissioningDbClients `dqm` created: 2021-08-04 09:08:41 merged: 2021-08-10 08:27:13

153. [34757](http://github.com/cms-sw/cmssw/pull/34757){:target="_blank"}  from **@iarspider**: [GCC 11] Fix error "array subscript outside array bounds" `db` created: 2021-08-04 08:56:24 merged: 2021-08-10 14:13:29

154. [34755](http://github.com/cms-sw/cmssw/pull/34755){:target="_blank"}  from **@smuzaffar**: [Geometry] Move public headers to interface directory `db` `geometry` `simulation` `upgrade` created: 2021-08-04 08:35:34 merged: 2021-08-04 20:42:34

155. [34754](http://github.com/cms-sw/cmssw/pull/34754){:target="_blank"}  from **@fabiocos**: Modernization of several simulation standalone test EDAnalyzers `analysis` `simulation` created: 2021-08-04 08:32:40 merged: 2021-08-05 08:59:10

156. [34748](http://github.com/cms-sw/cmssw/pull/34748){:target="_blank"}  from **@fwyzard**: Protect HCAL GPU-related modules against empty events `reconstruction` created: 2021-08-03 16:20:03 merged: 2021-08-05 05:23:24

157. [34746](http://github.com/cms-sw/cmssw/pull/34746){:target="_blank"}  from **@smuzaffar**: [L1] Move public headers to interface directory `dqm` `l1` created: 2021-08-03 14:36:15 merged: 2021-08-06 07:22:05

158. [34745](http://github.com/cms-sw/cmssw/pull/34745){:target="_blank"}  from **@smuzaffar**: [RecoParticleFlow] Cleanup for unused/private header `reconstruction` created: 2021-08-03 13:39:10 merged: 2021-08-05 05:42:06

159. [34744](http://github.com/cms-sw/cmssw/pull/34744){:target="_blank"}  from **@smuzaffar**: [TrackingTools] Move public headers to interface directory `reconstruction` created: 2021-08-03 13:17:48 merged: 2021-08-05 05:27:41

160. [34740](http://github.com/cms-sw/cmssw/pull/34740){:target="_blank"}  from **@cms-tsg-storm**: HLT menu migration to CMSSW 12_0_0_pre5 template [12_1_X] `hlt` created: 2021-08-03 12:18:42 merged: 2021-08-04 10:26:32

161. [34739](http://github.com/cms-sw/cmssw/pull/34739){:target="_blank"}  from **@smuzaffar**: [EventFilter] header cleanup to avoid private header usage `dqm` `hlt` created: 2021-08-03 11:40:25 merged: 2021-08-04 08:56:49

162. [34738](http://github.com/cms-sw/cmssw/pull/34738){:target="_blank"}  from **@bsunanda**: Run3-hcx306 Bug fix to get back the same hit energy distribution for HCAL `simulation` created: 2021-08-03 02:21:03 merged: 2021-08-03 12:28:06

163. [34737](http://github.com/cms-sw/cmssw/pull/34737){:target="_blank"}  from **@bsunanda**: Run3-alca191 Stop using cout in the codes of Calibration/HcalCalibAlgos `alca` created: 2021-08-02 21:01:53 merged: 2021-08-07 02:21:50

164. [34735](http://github.com/cms-sw/cmssw/pull/34735){:target="_blank"}  from **@Dr15Jones**: Rewrote checkForModuleDependencyCorrectness `core` created: 2021-08-02 19:00:03 merged: 2021-08-10 08:40:43

165. [34734](http://github.com/cms-sw/cmssw/pull/34734){:target="_blank"}  from **@smuzaffar**: [Sim] Move public headers on to interface directory `dqm` `generators` `simulation` `upgrade` created: 2021-08-02 17:16:37 merged: 2021-08-03 17:37:27

166. [34733](http://github.com/cms-sw/cmssw/pull/34733){:target="_blank"}  from **@smuzaffar**: [DD] Move public headers in to interface directory `geometry` `simulation` created: 2021-08-02 16:34:06 merged: 2021-08-03 07:45:32

167. [34729](http://github.com/cms-sw/cmssw/pull/34729){:target="_blank"}  from **@smuzaffar**: [CommonTools] move public header to interface directory `analysis` `dqm` `reconstruction` `visualization` created: 2021-08-02 15:35:36 merged: 2021-08-05 05:52:02

168. [34728](http://github.com/cms-sw/cmssw/pull/34728){:target="_blank"}  from **@Dres90**: Fix params for Payload Inspector `db` created: 2021-08-02 15:32:58 merged: 2021-08-11 08:52:54

169. [34727](http://github.com/cms-sw/cmssw/pull/34727){:target="_blank"}  from **@smuzaffar**: [Firework] Cleanup for public headers `visualization` created: 2021-08-02 14:48:50 merged: 2021-08-05 19:18:06

170. [34725](http://github.com/cms-sw/cmssw/pull/34725){:target="_blank"}  from **@fwyzard**: Fix uploading EventSetup conditions from multiple CUDA streams `heterogeneous` created: 2021-08-02 14:20:32 merged: 2021-08-03 06:57:13

171. [34723](http://github.com/cms-sw/cmssw/pull/34723){:target="_blank"}  from **@yuanchao**: Remove unused headers of Calib- packages `alca` created: 2021-08-02 12:55:44 merged: 2021-08-03 17:41:46

172. [34722](http://github.com/cms-sw/cmssw/pull/34722){:target="_blank"}  from **@srimanob**: Allow multiple "--command" in runTheMatrix `pdmv` `upgrade` created: 2021-08-02 12:37:56 merged: 2021-08-05 13:00:27

173. [34720](http://github.com/cms-sw/cmssw/pull/34720){:target="_blank"}  from **@dmeuser**: TkDQM: Fill barycenter plots at EndRun `dqm` created: 2021-08-02 11:50:55 merged: 2021-08-03 07:59:34

174. [34719](http://github.com/cms-sw/cmssw/pull/34719){:target="_blank"}  from **@francescobrivio**: Update DQM onlinebeammonitor `dqm` created: 2021-08-02 11:47:13 merged: 2021-08-03 15:47:15

175. [34715](http://github.com/cms-sw/cmssw/pull/34715){:target="_blank"}  from **@yuanchao**: Remove unused header for Alignment/LaserAlignment and Alignment/MuonAlignmentAlgorithms `alca` created: 2021-08-01 21:07:59 merged: 2021-08-02 05:27:45

176. [34713](http://github.com/cms-sw/cmssw/pull/34713){:target="_blank"}  from **@jshlee**: GEM dataformat - fix classversion `reconstruction` `simulation` `upgrade` created: 2021-07-31 14:20:56 merged: 2021-08-03 16:18:09

177. [34710](http://github.com/cms-sw/cmssw/pull/34710){:target="_blank"}  from **@colizz**: Enable concurrent GEN in Configuration/Generator/python `generators` `pdmv` `upgrade` created: 2021-07-31 07:23:34 merged: 2021-08-17 21:26:04

178. [34709](http://github.com/cms-sw/cmssw/pull/34709){:target="_blank"}  from **@bsunanda**: Run3-alca190 Modify the AlCaRecoProducer for HBHEMuon `alca` created: 2021-07-30 16:51:46 merged: 2021-08-02 15:14:24

179. [34708](http://github.com/cms-sw/cmssw/pull/34708){:target="_blank"}  from **@dan131riley**: minimal Validation/RecoTrack/python/plotting/plotting.py fix for division changes in py3 `dqm` created: 2021-07-30 16:30:52 merged: 2021-07-31 09:33:21

180. [34706](http://github.com/cms-sw/cmssw/pull/34706){:target="_blank"}  from **@zuoxunwu**: Online DQM: Add EMTF DQM plots on GEM information and their comparison to CSC inputs `dqm` created: 2021-07-30 13:01:28 merged: 2021-08-04 10:25:48

181. [34703](http://github.com/cms-sw/cmssw/pull/34703){:target="_blank"}  from **@smuzaffar**: [tidy] Performance-unnecessary-copy-initialization fix `reconstruction` created: 2021-07-30 09:18:38 merged: 2021-07-31 01:23:43

182. [34702](http://github.com/cms-sw/cmssw/pull/34702){:target="_blank"}  from **@apsallid**: [HGCAL] Updates on the RelVal campaign scripts due to python3 and other PRs `dqm` created: 2021-07-30 09:16:08 merged: 2021-07-31 09:29:06

183. [34699](http://github.com/cms-sw/cmssw/pull/34699){:target="_blank"}  from **@mmusich**: [Payload Inspector] Miscellaneous improvements for `RunInfo` and `SiStripLatency` `db` created: 2021-07-29 19:26:50 merged: 2021-07-31 01:31:20

184. [34697](http://github.com/cms-sw/cmssw/pull/34697){:target="_blank"}  from **@Dr15Jones**: Apply task chains to more code in FWCore/Framework `core` created: 2021-07-29 18:10:51 merged: 2021-08-17 01:27:47

185. [34695](http://github.com/cms-sw/cmssw/pull/34695){:target="_blank"}  from **@mariadalfonso**: NANO: rework for Prompt (part2) `xpog` created: 2021-07-29 15:21:39 merged: 2021-07-31 09:28:02

186. [34691](http://github.com/cms-sw/cmssw/pull/34691){:target="_blank"}  from **@smuzaffar**: [Misc2][clang-tidy] make deleted function public `alca` `core` `db` `dqm` `generators` `geometry` `l1` `reconstruction` `simulation` created: 2021-07-29 10:56:18 merged: 2021-08-03 07:23:17

187. [34690](http://github.com/cms-sw/cmssw/pull/34690){:target="_blank"}  from **@mmusich**: make `TrackerSystematicMisalignments` a one module `alca` created: 2021-07-29 10:33:28 merged: 2021-07-31 01:35:32

188. [34688](http://github.com/cms-sw/cmssw/pull/34688){:target="_blank"}  from **@smuzaffar**: [L1][clang-tidy] make deleted function public `l1` created: 2021-07-29 09:47:34 merged: 2021-08-03 07:23:27

189. [34683](http://github.com/cms-sw/cmssw/pull/34683){:target="_blank"}  from **@smuzaffar**: [Sim][clang-tidy] make deleted function public `generators` `simulation` `upgrade` created: 2021-07-29 08:37:56 merged: 2021-08-03 07:20:08

190. [34682](http://github.com/cms-sw/cmssw/pull/34682){:target="_blank"}  from **@smuzaffar**: [Cond][clang-tidy] make deleted function public  `alca` `db` `l1` created: 2021-07-29 08:12:23 merged: 2021-08-03 07:15:42

191. [34681](http://github.com/cms-sw/cmssw/pull/34681){:target="_blank"}  from **@dr-stringfellow**: Disable vertex smearing for workflows using CloseByParticleGun `operations` `pdmv` `simulation` `upgrade` created: 2021-07-29 07:59:47 merged: 2021-08-03 08:00:07

192. [34676](http://github.com/cms-sw/cmssw/pull/34676){:target="_blank"}  from **@ptcox**: Update test configs for CSCDigitizer to 12_0_X `simulation` created: 2021-07-28 16:48:24 merged: 2021-07-31 01:33:51

193. [34674](http://github.com/cms-sw/cmssw/pull/34674){:target="_blank"}  from **@bsunanda**: Run3-hcx305 Update some of the cfg's in Validation/HcalHits in view of changes to SD classes `dqm` created: 2021-07-28 15:13:14 merged: 2021-08-01 09:19:15

194. [34672](http://github.com/cms-sw/cmssw/pull/34672){:target="_blank"}  from **@ggovi**: Payload inspector framework moved to pybind11 `db` created: 2021-07-28 14:10:36 merged: 2021-08-24 01:04:12

195. [34670](http://github.com/cms-sw/cmssw/pull/34670){:target="_blank"}  from **@smuzaffar**: [OnlineDB][clang-tidy] make deleted function public `db` created: 2021-07-28 13:20:21 merged: 2021-07-31 01:22:28

196. [34668](http://github.com/cms-sw/cmssw/pull/34668){:target="_blank"}  from **@smuzaffar**: [DataFormats][clang-tidy] make deleted function public `core` `reconstruction` `simulation` `upgrade` created: 2021-07-28 12:44:14 merged: 2021-08-01 09:18:07

197. [34665](http://github.com/cms-sw/cmssw/pull/34665){:target="_blank"}  from **@smuzaffar**: [Fireworks][Clang-tidy] make deleted function public `visualization` created: 2021-07-28 09:39:33 merged: 2021-08-02 09:25:17

198. [34664](http://github.com/cms-sw/cmssw/pull/34664){:target="_blank"}  from **@stahlleiton**: Adapted EcalRawToDigi and SiPixelRawToCluster GPU code for HIon `heterogeneous` `reconstruction` created: 2021-07-28 06:48:34 merged: 2021-08-03 12:49:57

199. [34657](http://github.com/cms-sw/cmssw/pull/34657){:target="_blank"}  from **@smuzaffar**: [CondFormat][clang-tidy] Fix readability-container-size-empty warnings `alca` `db` created: 2021-07-27 21:07:40 merged: 2021-07-31 01:21:43

200. [34643](http://github.com/cms-sw/cmssw/pull/34643){:target="_blank"}  from **@bbilin**: Changing Commissioning 2020 to Commissioning 2021 with new run # and dataset.  `pdmv` `upgrade` created: 2021-07-27 15:34:34 merged: 2021-08-02 07:42:46

201. [34631](http://github.com/cms-sw/cmssw/pull/34631){:target="_blank"}  from **@ptcox**: fix incomplete esconsumes migration `simulation` created: 2021-07-26 19:06:55 merged: 2021-08-05 12:33:10

202. [34612](http://github.com/cms-sw/cmssw/pull/34612){:target="_blank"}  from **@namapane**: Update DT DQM, calibration scripts, and local reco code to allow using "new" DB format `alca` `dqm` `hlt` `reconstruction` `db` created: 2021-07-24 11:31:51 merged: 2021-08-12 06:10:40

203. [34608](http://github.com/cms-sw/cmssw/pull/34608){:target="_blank"}  from **@PFCal-dev**: [HGCal trigger] Remove deprecated v8 geometry code + Add new trigger geometry class `l1` `simulation` `upgrade` created: 2021-07-23 14:40:18 merged: 2021-08-08 08:52:51

204. [34606](http://github.com/cms-sw/cmssw/pull/34606){:target="_blank"}  from **@veszpv**: Pixel cluster repair by morphing `operations` `reconstruction` created: 2021-07-23 14:07:39 merged: 2021-08-10 02:13:51

205. [34605](http://github.com/cms-sw/cmssw/pull/34605){:target="_blank"}  from **@kyoon-mit**: Configure HFNose TICL Trackster Parameters `reconstruction` `upgrade` created: 2021-07-23 12:15:14 merged: 2021-07-31 01:26:45

206. [34599](http://github.com/cms-sw/cmssw/pull/34599){:target="_blank"}  from **@tklijnsma**: finecalo: No longer count reentries into the calorimeter as boundary crossings `simulation` `upgrade` created: 2021-07-22 19:04:07 merged: 2021-08-02 12:47:27

207. [34597](http://github.com/cms-sw/cmssw/pull/34597){:target="_blank"}  from **@tklijnsma**: Fixed finecalo performance `simulation` `upgrade` created: 2021-07-22 17:38:14 merged: 2021-08-07 11:59:43

208. [34576](http://github.com/cms-sw/cmssw/pull/34576){:target="_blank"}  from **@cms-tau-pog**: Enable boosted tau reco to run at miniAOD `reconstruction` created: 2021-07-21 16:24:07 merged: 2021-08-12 09:08:13

209. [34572](http://github.com/cms-sw/cmssw/pull/34572){:target="_blank"}  from **@mseidel42**: Allow HcalPulseContainment timePhase definition as in SIM `alca` `l1` `reconstruction` created: 2021-07-21 07:18:11 merged: 2021-08-04 13:16:54

210. [34571](http://github.com/cms-sw/cmssw/pull/34571){:target="_blank"}  from **@jeongeun**: Migrate module configuration in RecoMET to use default cfipython `reconstruction` created: 2021-07-21 06:10:34 merged: 2021-08-11 08:57:07

211. [34505](http://github.com/cms-sw/cmssw/pull/34505){:target="_blank"}  from **@UniMiBAnalyses**: Adding the codes for ECAL Phase2 amplitude local reconstruction `reconstruction` created: 2021-07-15 17:27:11 merged: 2021-08-15 02:24:13

212. [34452](http://github.com/cms-sw/cmssw/pull/34452){:target="_blank"}  from **@srimanob**: Fix when neither "data" nor "MC" is specified in the cmsDriver. `dqm` `operations` `xpog` created: 2021-07-13 07:07:56 merged: 2021-08-09 11:46:29

213. [34446](http://github.com/cms-sw/cmssw/pull/34446){:target="_blank"}  from **@AdrianoDee**: Adding LUT approach for PackedCandidates `reconstruction` created: 2021-07-12 16:27:02 merged: 2021-08-12 09:00:10

214. [34439](http://github.com/cms-sw/cmssw/pull/34439){:target="_blank"}  from **@SohamBhattacharya**: Clean/rename FromMultiCl HGCal egamma collections `dqm` `reconstruction` `upgrade` created: 2021-07-10 16:20:33 merged: 2021-08-10 17:20:39

215. [34427](http://github.com/cms-sw/cmssw/pull/34427){:target="_blank"}  from **@jfernan2**: python2 cleanup: Validation packages `core` `dqm` `geometry` created: 2021-07-09 11:22:22 merged: 2021-08-10 13:55:03

#### CMSDIST Changes between Tags REL/CMSSW_12_1_0_pre1/slc7_amd64_gcc900 and REL/CMSSW_12_1_0_pre2/slc7_amd64_gcc900:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_1_0_pre1/slc7_amd64_gcc900...REL/CMSSW_12_1_0_pre2/slc7_amd64_gcc900)



1. [7240](http://github.com/cms-sw/cmsdist/pull/7240){:target="_blank"}  from **@cms-sw**: [WIP] Remove py3-google-common package created: 2021-08-25 14:16:09 merged: 2021-08-25 22:23:21

2. [7239](http://github.com/cms-sw/cmsdist/pull/7239){:target="_blank"}  from **@cms-sw**: Revert "[Tensorflow] Update to version 2.6.0" created: 2021-08-25 13:00:32 merged: 2021-08-25 16:23:40

3. [7237](http://github.com/cms-sw/cmsdist/pull/7237){:target="_blank"}  from **@ddaina**: update crab-dev to v3.210825 created: 2021-08-25 08:21:09 merged: 2021-08-25 12:23:22

4. [7234](http://github.com/cms-sw/cmsdist/pull/7234){:target="_blank"}  from **@cms-sw**: treat private header usage as warning for devel IBs created: 2021-08-25 07:14:49 merged: 2021-08-25 07:14:55

5. [7232](http://github.com/cms-sw/cmsdist/pull/7232){:target="_blank"}  from **@cms-sw**: Update py3-notebook to 6.4.3 created: 2021-08-23 21:54:46 merged: 2021-08-24 07:02:40

6. [7231](http://github.com/cms-sw/cmsdist/pull/7231){:target="_blank"}  from **@cms-sw**: added suport to build indiviual toolfiles created: 2021-08-23 18:00:00 merged: 2021-08-23 21:43:52

7. [7230](http://github.com/cms-sw/cmsdist/pull/7230){:target="_blank"}  from **@cms-sw**: [BuildRules] Check for private headers usage created: 2021-08-23 15:59:54 merged: 2021-08-24 07:03:34

8. [7229](http://github.com/cms-sw/cmsdist/pull/7229){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-MkFit to V00-03-00 created: 2021-08-23 15:00:13 merged: 2021-08-25 06:36:06

9. [7228](http://github.com/cms-sw/cmsdist/pull/7228){:target="_blank"}  from **@mrodozov**: Updated root to tip of branch v6-22-00-patches created: 2021-08-23 06:18:57 merged: 2021-08-23 21:44:15

10. [7225](http://github.com/cms-sw/cmsdist/pull/7225){:target="_blank"}  from **@cms-sw**: [Tensorflow] Update to version 2.6.0 created: 2021-08-21 14:27:13 merged: 2021-08-24 07:03:18

11. [7223](http://github.com/cms-sw/cmsdist/pull/7223){:target="_blank"}  from **@cms-sw**: [Eigen] More Eigen GPU work, with fix for CUDA 11.4 created: 2021-08-20 08:15:36 merged: 2021-08-20 15:43:55

12. [7222](http://github.com/cms-sw/cmsdist/pull/7222){:target="_blank"}  from **@cms-sw**: [SCRAM] use system python3 when project env is not set created: 2021-08-20 07:24:18 merged: 2021-08-20 08:59:56

13. [7220](http://github.com/cms-sw/cmsdist/pull/7220){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-ElectronIdentification to V01-07-00 created: 2021-08-19 15:26:02 merged: 2021-08-19 16:31:50

14. [7217](http://github.com/cms-sw/cmsdist/pull/7217){:target="_blank"}  from **@mmasciov**: Update mkfit to V3.1.1 created: 2021-08-17 17:32:37 merged: 2021-08-25 06:35:54

15. [7209](http://github.com/cms-sw/cmsdist/pull/7209){:target="_blank"}  from **@cms-sw**: keep cmssw tools to drop in a common file created: 2021-08-11 14:27:37 merged: 2021-08-11 17:20:19

16. [7208](http://github.com/cms-sw/cmsdist/pull/7208){:target="_blank"}  from **@cms-sw**: [cx-ORacle] enable it for non-x86_64 archs created: 2021-08-10 09:54:43 merged: 2021-08-11 06:51:57

17. [7207](http://github.com/cms-sw/cmsdist/pull/7207){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1THGCal to V01-06-00 created: 2021-08-08 08:50:10 merged: 2021-08-08 08:51:38

18. [7204](http://github.com/cms-sw/cmsdist/pull/7204){:target="_blank"}  from **@fwyzard**: Update Alpaka to v0.7.0 and Cupla to v0.3.0 created: 2021-08-05 15:33:13 merged: 2021-08-06 16:47:18

19. [7203](http://github.com/cms-sw/cmsdist/pull/7203){:target="_blank"}  from **@cms-sw**: Update tag for DataFormats-PatCandidates to V01-01-00 created: 2021-08-05 13:50:54 merged: 2021-08-05 22:33:29

20. [7201](http://github.com/cms-sw/cmsdist/pull/7201){:target="_blank"}  from **@mkirsano**: fix EvtGen data path created: 2021-08-04 09:13:21 merged: 2021-08-04 17:09:16

21. [7199](http://github.com/cms-sw/cmsdist/pull/7199){:target="_blank"}  from **@cms-sw**: [Eigen] Fixed CUDA warning and restored Matrix5d inversion on GPU created: 2021-08-03 21:58:20 merged: 2021-08-04 08:43:22

22. [7198](http://github.com/cms-sw/cmsdist/pull/7198){:target="_blank"}  from **@cms-sw**: fix pcm_util toolfile for CXXMODULE IBs created: 2021-08-03 21:26:57 merged: 2021-08-03 21:27:10

23. [7196](http://github.com/cms-sw/cmsdist/pull/7196){:target="_blank"}  from **@cms-sw**: Update cmssw-wm-tools.spec created: 2021-08-03 12:24:31 merged: 2021-08-03 17:07:35

24. [7195](http://github.com/cms-sw/cmsdist/pull/7195){:target="_blank"}  from **@fwyzard**: Update Alpaka to version 0.6.1 created: 2021-08-03 07:47:24 merged: 2021-08-03 21:19:13

25. [7190](http://github.com/cms-sw/cmsdist/pull/7190){:target="_blank"}  from **@cms-sw**: Update py3-wheel, py3-numpy and py3-wrapt created: 2021-07-30 23:03:19 merged: 2021-08-01 12:12:37

26. [7188](http://github.com/cms-sw/cmsdist/pull/7188){:target="_blank"}  from **@cms-sw**: [GCC11] Use newer ruy for TF 2.5 created: 2021-07-30 22:47:34 merged: 2021-07-30 22:47:47

27. [7187](http://github.com/cms-sw/cmsdist/pull/7187){:target="_blank"}  from **@cms-sw**: updated pcm_util.xml created: 2021-07-30 14:55:32 merged: 2021-07-30 14:55:37

28. [7186](http://github.com/cms-sw/cmsdist/pull/7186){:target="_blank"}  from **@cms-sw**: GCC 11 Fix for onnxruntime created: 2021-07-30 14:19:55 merged: 2021-07-30 22:09:13

29. [7170](http://github.com/cms-sw/cmsdist/pull/7170){:target="_blank"}  from **@fwyzard**: Update UCX libraries to v1.10.1, and link to the RDMA core libraries  created: 2021-07-26 21:20:46 merged: 2021-08-02 14:06:14
