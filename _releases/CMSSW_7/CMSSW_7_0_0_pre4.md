---
layout: post
rel_link:  "7_0_0_pre4"
title:  "CMSSW_7_0_0_pre4"
date:   2013-09-14 22:42:28
categories: cmssw
relmajor: 7
relminor: 0
relsubminor: 0
relpre: _pre4
---

# CMSSW_7_0_0_pre4
#### Changes since CMSSW_7_0_0_pre3:

1. [834](http://github.com/cms-sw/cmssw/pull/834){:target="_blank"}  from **@ktf**: Use struct flock rather than flock to keep mac happy. `daq`  created: 2013-09-14 22:41:22 merged: 2013-09-14 22:41:35

2. [833](http://github.com/cms-sw/cmssw/pull/833){:target="_blank"}  from **@wmtan**: Add std:: qualifiers or directives `alca`  created: 2013-09-14 15:37:03 merged: 2013-09-14 19:25:52

3. [831](http://github.com/cms-sw/cmssw/pull/831){:target="_blank"}  from **@ktf**: More XDAQ removal cleanups. `daq`  created: 2013-09-14 09:27:54 merged: 2013-09-14 09:35:57

4. [764](http://github.com/cms-sw/cmssw/pull/764){:target="_blank"}  from **@inugent**: Wlhe2 hep mc converter70x `generators`  created: 2013-09-10 15:48:43 merged: 2013-09-14 08:03:50

5. [775](http://github.com/cms-sw/cmssw/pull/775){:target="_blank"}  from **@mkirsano**: Generators Fixes -- Fix decay pi0 after Tauola++ migration. `generators`  created: 2013-09-11 07:19:47 merged: 2013-09-14 08:02:50

6. [802](http://github.com/cms-sw/cmssw/pull/802){:target="_blank"}  from **@ptcox**: Consumes to CSCSharesInput `reconstruction`  created: 2013-09-12 09:57:01 merged: 2013-09-14 08:02:21

7. [727](http://github.com/cms-sw/cmssw/pull/727){:target="_blank"}  from **@makortel**: Performance improvement in PAT helpers.py (70X) `analysis`  created: 2013-09-06 06:47:32 merged: 2013-09-14 07:56:00

8. [829](http://github.com/cms-sw/cmssw/pull/829){:target="_blank"}  from **@wmtan**: Add missing std:: qualifiers and missing includes of iostream. `alca`  `analysis`  `core`  `daq`  `db`  `dqm`  `fastsim`  `generators`  `geometry`  `hlt`  `l1`  `operations`  `reconstruction`  `simulation`  `visualization`  created: 2013-09-13 22:19:52 merged: 2013-09-13 22:36:51

9. [828](http://github.com/cms-sw/cmssw/pull/828){:target="_blank"}  from **@ktf**: Drop Commissioning helpers DaqSource based. `alca`  created: 2013-09-13 20:22:21 merged: 2013-09-13 20:30:39

10. [824](http://github.com/cms-sw/cmssw/pull/824){:target="_blank"}  from **@ktf**: Remove friendship relations to removed DaqSource. `core`  created: 2013-09-13 12:42:23 merged: 2013-09-13 15:17:25

11. [815](http://github.com/cms-sw/cmssw/pull/815){:target="_blank"}  from **@Dr15Jones**: Thread safe callbacks from Service system will not give access to Run, LuminosityBlock or Event `core`  created: 2013-09-12 17:04:21 merged: 2013-09-13 11:59:31

12. [819](http://github.com/cms-sw/cmssw/pull/819){:target="_blank"}  from **@danduggan**: adding back hlt functionality for this pkg `dqm`  created: 2013-09-13 09:00:53 merged: 2013-09-13 11:58:40

13. [822](http://github.com/cms-sw/cmssw/pull/822){:target="_blank"}  from **@Martin-Grunewald**: HLTXDAQ fixup `hlt`  created: 2013-09-13 10:41:02 merged: 2013-09-13 11:51:31

14. [821](http://github.com/cms-sw/cmssw/pull/821){:target="_blank"}  from **@ktf**: Macosx uses a different layout for struct flock. `daq`  created: 2013-09-13 09:08:26 merged: 2013-09-13 11:49:02

15. [813](http://github.com/cms-sw/cmssw/pull/813){:target="_blank"}  from **@avartak**: Fix resolution/pull plots `dqm`  created: 2013-09-12 15:26:51 merged: 2013-09-13 10:01:10

16. [706](http://github.com/cms-sw/cmssw/pull/706){:target="_blank"}  from **@lgray**: Integration of the E\gamma Cluster Position Calculator into the PFClusterProducer `reconstruction`  created: 2013-09-03 18:28:13 merged: 2013-09-13 07:23:01

17. [816](http://github.com/cms-sw/cmssw/pull/816){:target="_blank"}  from **@wmtan**: add missing namespaces or includes `alca`  `dqm`  `fastsim`  `l1`  `reconstruction`  created: 2013-09-12 22:02:39 merged: 2013-09-12 22:39:32

18. [803](http://github.com/cms-sw/cmssw/pull/803){:target="_blank"}  from **@giamman**: new syntax for track seeding configuration `fastsim`  created: 2013-09-12 10:29:30 merged: 2013-09-12 19:35:29

19. [782](http://github.com/cms-sw/cmssw/pull/782){:target="_blank"}  from **@ptcox**: Consumes to CSCDigitizer `simulation`  created: 2013-09-11 11:50:14 merged: 2013-09-12 19:34:43

20. [627](http://github.com/cms-sw/cmssw/pull/627){:target="_blank"}  from **@gartung**: Other packages -- changes for large object passed by value  `alca`  `analysis`  `fastsim`  `generators`  `operations`  `reconstruction`  `simulation`  created: 2013-08-27 02:39:23 merged: 2013-09-12 19:24:51

21. [814](http://github.com/cms-sw/cmssw/pull/814){:target="_blank"}  from **@ktf**: Remove xdaq mergiable `daq`  created: 2013-09-12 16:44:32 merged: 2013-09-12 19:11:45

22. [781](http://github.com/cms-sw/cmssw/pull/781){:target="_blank"}  from **@lgray**: PFEGamma fix to prevent refined SCs with both EB and EE clusters `reconstruction`  created: 2013-09-11 10:45:10 merged: 2013-09-12 16:51:24

23. [810](http://github.com/cms-sw/cmssw/pull/810){:target="_blank"}  from **@danduggan**: removed xdaq deps from all dqm packages `dqm`  created: 2013-09-12 14:39:05 merged: 2013-09-12 15:49:41

24. [811](http://github.com/cms-sw/cmssw/pull/811){:target="_blank"}  from **@nclopezo**: Remove CVS Keywords from Reco\* `reconstruction`  created: 2013-09-12 15:01:42 merged: 2013-09-12 15:21:56

25. [806](http://github.com/cms-sw/cmssw/pull/806){:target="_blank"}  from **@giamman**: Preparation for new mixing (part 2) `fastsim`  created: 2013-09-12 13:08:21 merged: 2013-09-12 14:18:50

26. [804](http://github.com/cms-sw/cmssw/pull/804){:target="_blank"}  from **@ktf**: Remove dependency on XDAQ from HcalOnlineDb `db`  created: 2013-09-12 11:55:10 merged: 2013-09-12 13:08:20

27. [212](http://github.com/cms-sw/cmssw/pull/212){:target="_blank"}  from **@SusieMurphy**: Updated cfg-viewer, unscheduled added `core`  created: 2013-08-01 15:37:21 merged: 2013-09-12 12:34:08

28. [786](http://github.com/cms-sw/cmssw/pull/786){:target="_blank"}  from **@ianna**: Gem geometry payload `db`  created: 2013-09-11 13:01:16 merged: 2013-09-12 12:08:48

29. [801](http://github.com/cms-sw/cmssw/pull/801){:target="_blank"}  from **@Martin-Grunewald**: fillDescriptions for HLTrigger/Timer `hlt`  created: 2013-09-12 07:52:58 merged: 2013-09-12 12:04:16

30. [785](http://github.com/cms-sw/cmssw/pull/785){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from Online DB `db`  created: 2013-09-11 12:56:33 merged: 2013-09-12 12:01:53

31. [787](http://github.com/cms-sw/cmssw/pull/787){:target="_blank"}  from **@ptcox**: Consumes to CSCEfficiency `reconstruction`  created: 2013-09-11 13:06:02 merged: 2013-09-12 07:50:03

32. [789](http://github.com/cms-sw/cmssw/pull/789){:target="_blank"}  from **@ktf**: Remove all templated documentation which was never populated. `alca`  `analysis`  `core`  `daq`  `db`  `docs`  `dqm`  `fastsim`  `generators`  `geometry`  `hlt`  `l1`  `operations`  `reconstruction`  `simulation`  created: 2013-09-11 13:20:39 merged: 2013-09-11 20:32:45

33. [731](http://github.com/cms-sw/cmssw/pull/731){:target="_blank"}  from **@wddgit**: Multithreaded TFileService `alca`  `analysis`  `core`  `dqm`  `reconstruction`  `simulation`  created: 2013-09-06 15:20:53 merged: 2013-09-11 19:15:25

34. [735](http://github.com/cms-sw/cmssw/pull/735){:target="_blank"}  from **@wmtan**: Use correct stream for Delayed Reading `core`  `dqm`  `simulation`  created: 2013-09-07 04:32:39 merged: 2013-09-11 17:25:07

35. [769](http://github.com/cms-sw/cmssw/pull/769){:target="_blank"}  from **@jhgoh**: Validation/RPCRecHits getByToken update `dqm`  created: 2013-09-10 20:09:04 merged: 2013-09-11 15:02:31

36. [779](http://github.com/cms-sw/cmssw/pull/779){:target="_blank"}  from **@blinkseb**: Fix wrong import in metFilters_cff `analysis`  created: 2013-09-11 09:10:48 merged: 2013-09-11 14:20:53

37. [790](http://github.com/cms-sw/cmssw/pull/790){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from PhysicsTools `analysis`  created: 2013-09-11 13:31:42 merged: 2013-09-11 13:47:18

38. [756](http://github.com/cms-sw/cmssw/pull/756){:target="_blank"}  from **@nclopezo**: Remove CVS Keywords from IO\* `alca`  `core`  `daq`  `simulation`  created: 2013-09-10 09:36:44 merged: 2013-09-11 13:42:12

39. [788](http://github.com/cms-sw/cmssw/pull/788){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from PerfTools `core`  created: 2013-09-11 13:10:43 merged: 2013-09-11 13:15:55

40. [771](http://github.com/cms-sw/cmssw/pull/771){:target="_blank"}  from **@wmtan**: add missing std:: namespace qualifiers `core`  created: 2013-09-10 22:13:25 merged: 2013-09-11 12:27:12

41. [777](http://github.com/cms-sw/cmssw/pull/777){:target="_blank"}  from **@Martin-Grunewald**: New ConfDb location 7_0_0 `hlt`  created: 2013-09-11 07:43:29 merged: 2013-09-11 10:11:21

42. [759](http://github.com/cms-sw/cmssw/pull/759){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from MagneticField `reconstruction`  created: 2013-09-10 12:51:41 merged: 2013-09-11 10:10:59

43. [680](http://github.com/cms-sw/cmssw/pull/680){:target="_blank"}  from **@rappoccio**: EITopPAG updates, merging with E/Gamma features `analysis`  `dqm`  `reconstruction`  created: 2013-08-30 19:55:04 merged: 2013-09-11 09:19:48

44. [752](http://github.com/cms-sw/cmssw/pull/752){:target="_blank"}  from **@TaiSakuma**: add configurations for several corrected METs `analysis`  created: 2013-09-09 23:19:26 merged: 2013-09-11 02:32:30

45. [761](http://github.com/cms-sw/cmssw/pull/761){:target="_blank"}  from **@nclopezo**: Removed CVS keywords from MuonAnalysis `analysis`  created: 2013-09-10 13:09:26 merged: 2013-09-11 02:29:38

46. [758](http://github.com/cms-sw/cmssw/pull/758){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from Jet\* `analysis`  created: 2013-09-10 12:30:58 merged: 2013-09-11 02:28:38

47. [175](http://github.com/cms-sw/cmssw/pull/175){:target="_blank"}  from **@mandrenguyen**: Switch from triplet only tracks to all tracks, to avoid problems with tr... `reconstruction`  created: 2013-07-24 11:44:23 merged: 2013-09-10 13:04:53

48. [743](http://github.com/cms-sw/cmssw/pull/743){:target="_blank"}  from **@ptcox**: Consumes to CSCSegment `reconstruction`  created: 2013-09-09 12:59:51 merged: 2013-09-10 11:48:49

49. [754](http://github.com/cms-sw/cmssw/pull/754){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from Heavy\* `analysis`  created: 2013-09-10 08:43:43 merged: 2013-09-10 09:54:25

50. [755](http://github.com/cms-sw/cmssw/pull/755){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from HiggsAnalysis `analysis`  created: 2013-09-10 09:06:19 merged: 2013-09-10 09:14:12

51. [624](http://github.com/cms-sw/cmssw/pull/624){:target="_blank"}  from **@gartung**: Sim\* Packages -- changes for large object passed by value `l1`  `simulation`  created: 2013-08-26 20:20:30 merged: 2013-09-10 08:17:17

52. [582](http://github.com/cms-sw/cmssw/pull/582){:target="_blank"}  from **@anorkus**: RelMon updates and fixes `reconstruction`  created: 2013-08-21 11:05:18 merged: 2013-09-10 08:09:13

53. [745](http://github.com/cms-sw/cmssw/pull/745){:target="_blank"}  from **@nclopezo**: Remove CVS Keywords from HLT\* `dqm`  `hlt`  created: 2013-09-09 14:53:09 merged: 2013-09-10 08:07:52

54. [741](http://github.com/cms-sw/cmssw/pull/741){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from GeneratorInterface `generators`  created: 2013-09-09 12:35:48 merged: 2013-09-10 08:01:23

55. [744](http://github.com/cms-sw/cmssw/pull/744){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from Geometry\* `geometry`  created: 2013-09-09 14:00:38 merged: 2013-09-10 07:41:47

56. [740](http://github.com/cms-sw/cmssw/pull/740){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from Fireworks `visualization`  created: 2013-09-09 11:44:43 merged: 2013-09-09 13:17:18

57. [739](http://github.com/cms-sw/cmssw/pull/739){:target="_blank"}  from **@TaiSakuma**: copy xy correction constants from CVS Revision 1.7 `analysis`  created: 2013-09-09 00:02:30 merged: 2013-09-09 12:16:10

58. [738](http://github.com/cms-sw/cmssw/pull/738){:target="_blank"}  from **@Dr15Jones**: Added preallocate signal for Services `core`  created: 2013-09-08 17:28:57 merged: 2013-09-09 07:55:16

59. [691](http://github.com/cms-sw/cmssw/pull/691){:target="_blank"}  from **@acimmino**: Second clean up cout `dqm`  created: 2013-09-02 14:59:00 merged: 2013-09-09 07:44:02

60. [690](http://github.com/cms-sw/cmssw/pull/690){:target="_blank"}  from **@nancymarinelli**: 700 updates in validation reco egamma test `dqm`  created: 2013-09-02 14:33:35 merged: 2013-09-08 19:35:55

61. [671](http://github.com/cms-sw/cmssw/pull/671){:target="_blank"}  from **@deguio**: declare consumes for DQM core packages `dqm`  created: 2013-08-30 09:13:35 merged: 2013-09-08 19:35:29

62. [732](http://github.com/cms-sw/cmssw/pull/732){:target="_blank"}  from **@perrotta**: Consumes egamma `hlt`  created: 2013-09-06 15:22:38 merged: 2013-09-08 13:58:04

63. [678](http://github.com/cms-sw/cmssw/pull/678){:target="_blank"}  from **@rappoccio**: Adding b-tagging only to the EITopPAG `analysis`  `reconstruction`  created: 2013-08-30 16:39:26 merged: 2013-09-06 15:02:15

64. [717](http://github.com/cms-sw/cmssw/pull/717){:target="_blank"}  from **@nclopezo**: Removed CVS Keywords from EventFilter `daq`  `l1`  `reconstruction`  created: 2013-09-04 14:49:12 merged: 2013-09-06 11:29:30

65. [716](http://github.com/cms-sw/cmssw/pull/716){:target="_blank"}  from **@argiro**: fixed uninitialized variables `reconstruction`  created: 2013-09-04 14:33:07 merged: 2013-09-06 11:00:14

66. [711](http://github.com/cms-sw/cmssw/pull/711){:target="_blank"}  from **@yiiyama**: consume & getByToken `dqm`  created: 2013-09-04 11:05:43 merged: 2013-09-06 08:17:15

67. [724](http://github.com/cms-sw/cmssw/pull/724){:target="_blank"}  from **@davidlt**: Revert multisource xrootd `core`  created: 2013-09-05 22:40:52 merged: 2013-09-05 23:04:11

68. [718](http://github.com/cms-sw/cmssw/pull/718){:target="_blank"}  from **@nclopezo**: Removed CVS keywords from ElectroWeakAnalysis `analysis`  created: 2013-09-04 14:52:01 merged: 2013-09-05 08:30:58

69. [558](http://github.com/cms-sw/cmssw/pull/558){:target="_blank"}  from **@bbockelm**: Multisource xrootd `core`  created: 2013-08-16 15:43:51 merged: 2013-09-04 15:32:20

70. [715](http://github.com/cms-sw/cmssw/pull/715){:target="_blank"}  from **@Dr15Jones**: Signal handlers use atomics `core`  created: 2013-09-04 13:58:19 merged: 2013-09-04 14:41:10

71. [677](http://github.com/cms-sw/cmssw/pull/677){:target="_blank"}  from **@ianna**: CaloTowers and Hcal geometry test `geometry`  created: 2013-08-30 16:35:04 merged: 2013-09-04 13:55:21

72. [710](http://github.com/cms-sw/cmssw/pull/710){:target="_blank"}  from **@perrotta**: Consumes special `hlt`  created: 2013-09-04 10:26:33 merged: 2013-09-04 13:30:24

73. [702](http://github.com/cms-sw/cmssw/pull/702){:target="_blank"}  from **@ghellwig**: Update all in one tool to current 70X version `alca`  created: 2013-09-03 15:40:16 merged: 2013-09-04 13:20:36

74. [707](http://github.com/cms-sw/cmssw/pull/707){:target="_blank"}  from **@Dr15Jones**: Removed all code related to running EventProcessor asynchronously `core`  created: 2013-09-04 01:54:36 merged: 2013-09-04 11:51:31

75. [709](http://github.com/cms-sw/cmssw/pull/709){:target="_blank"}  from **@nclopezo**: Revomed CVS keywords from EgammaAnalysis `analysis`  created: 2013-09-04 09:51:08 merged: 2013-09-04 11:38:10

76. [704](http://github.com/cms-sw/cmssw/pull/704){:target="_blank"}  from **@wmtan**: Remove obsolete comment `core`  created: 2013-09-03 16:44:53 merged: 2013-09-04 07:49:57

77. [645](http://github.com/cms-sw/cmssw/pull/645){:target="_blank"}  from **@lgray**: Fix valgrind warning in PFEGammaProducer `reconstruction`  created: 2013-08-28 09:34:18 merged: 2013-09-03 14:52:53

78. [667](http://github.com/cms-sw/cmssw/pull/667){:target="_blank"}  from **@inugent**: My multi thread patch val `generators`  created: 2013-08-30 00:03:36 merged: 2013-09-03 12:44:52

79. [697](http://github.com/cms-sw/cmssw/pull/697){:target="_blank"}  from **@Martin-Grunewald**: Fix for HeavyIon L1REPACKing `operations`  created: 2013-09-03 10:57:13 merged: 2013-09-03 12:26:10

80. [687](http://github.com/cms-sw/cmssw/pull/687){:target="_blank"}  from **@nclopezo**: Remove CVS Keywords from Dataformats `alca`  `analysis`  `core`  `daq`  `dqm`  `generators`  `geometry`  `hlt`  `l1`  `reconstruction`  `simulation`  created: 2013-09-02 10:24:22 merged: 2013-09-03 09:05:15

81. [689](http://github.com/cms-sw/cmssw/pull/689){:target="_blank"}  from **@nclopezo**: Remove CVS keywords from DetectorDescription `geometry`  created: 2013-09-02 13:15:44 merged: 2013-09-03 09:02:48

82. [688](http://github.com/cms-sw/cmssw/pull/688){:target="_blank"}  from **@suchandradutta**: Adding CheckVariance Quality Test `dqm`  created: 2013-09-02 11:00:01 merged: 2013-09-03 07:54:50

83. [644](http://github.com/cms-sw/cmssw/pull/644){:target="_blank"}  from **@ferencek**: 70X additional b-taggers `reconstruction`  created: 2013-08-28 04:08:23 merged: 2013-09-02 15:26:32

84. [685](http://github.com/cms-sw/cmssw/pull/685){:target="_blank"}  from **@Dr15Jones**: Multiple streams in cmsRun `core`  `simulation`  created: 2013-09-01 20:01:02 merged: 2013-09-02 09:48:00

85. [661](http://github.com/cms-sw/cmssw/pull/661){:target="_blank"}  from **@nclopezo**: Remove CVS keywords from L1\* `l1`  created: 2013-08-29 14:57:00 merged: 2013-09-02 07:41:36

86. [674](http://github.com/cms-sw/cmssw/pull/674){:target="_blank"}  from **@nclopezo**: Remove CVS Keywords from CaloOnlineTools `alca`  `db`  created: 2013-08-30 12:40:30 merged: 2013-09-02 07:39:37

87. [648](http://github.com/cms-sw/cmssw/pull/648){:target="_blank"}  from **@fwyzard**: build a vector applying a transformation to each element of an input vector `core`  created: 2013-08-28 10:04:40 merged: 2013-09-02 07:28:11

88. [669](http://github.com/cms-sw/cmssw/pull/669){:target="_blank"}  from **@Martin-Grunewald**: Consumes api3 for HLTrigger/HLTcore and HLTrigger/HLTfilters `hlt`  created: 2013-08-30 08:22:51 merged: 2013-09-02 07:27:45

89. [673](http://github.com/cms-sw/cmssw/pull/673){:target="_blank"}  from **@nclopezo**: Remove CVS keywords from Analysis\* `analysis`  created: 2013-08-30 09:48:55 merged: 2013-09-01 19:57:15

90. [665](http://github.com/cms-sw/cmssw/pull/665){:target="_blank"}  from **@Dr15Jones**: stream::EDAnalyzer never updated to pass ModuleCallingContext. `core`  created: 2013-08-29 22:29:04 merged: 2013-09-01 19:56:14

91. [681](http://github.com/cms-sw/cmssw/pull/681){:target="_blank"}  from **@wmtan**: Make history registry non-singleton and also fix read calls to not use p... `core`  `daq`  `dqm`  `generators`  `visualization`  created: 2013-08-30 22:37:30 merged: 2013-09-01 14:33:36

92. [668](http://github.com/cms-sw/cmssw/pull/668){:target="_blank"}  from **@inugent**: Use consumes API in TauSpinner `generators`  created: 2013-08-30 00:06:04 merged: 2013-08-30 09:44:01

93. [670](http://github.com/cms-sw/cmssw/pull/670){:target="_blank"}  from **@ktf**: Fix typos. `alca`  created: 2013-08-30 08:39:00 merged: 2013-08-30 08:39:21

94. [664](http://github.com/cms-sw/cmssw/pull/664){:target="_blank"}  from **@ktf**: Remove obsolete package. `analysis`  created: 2013-08-29 15:44:02 merged: 2013-08-29 19:33:56

95. [654](http://github.com/cms-sw/cmssw/pull/654){:target="_blank"}  from **@ktf**: Remove CVS keywords `alca`  `l1`  created: 2013-08-29 09:40:13 merged: 2013-08-29 17:50:44

96. [657](http://github.com/cms-sw/cmssw/pull/657){:target="_blank"}  from **@inugent**: Patch for name space bug  `generators`  created: 2013-08-29 12:51:23 merged: 2013-08-29 14:54:40

97. [659](http://github.com/cms-sw/cmssw/pull/659){:target="_blank"}  from **@nclopezo**: Remove CVS keywords from DQM\* `dqm`  `l1`  created: 2013-08-29 14:08:48 merged: 2013-08-29 14:24:37

98. [655](http://github.com/cms-sw/cmssw/pull/655){:target="_blank"}  from **@perrotta**: Check and fix HLTFilters for compliance `hlt`  created: 2013-08-29 12:16:07 merged: 2013-08-29 14:16:20

99. [658](http://github.com/cms-sw/cmssw/pull/658){:target="_blank"}  from **@ktf**: Remove packages which depend on XDAQ. `daq`  created: 2013-08-29 12:55:32 merged: 2013-08-29 14:01:25

100. [656](http://github.com/cms-sw/cmssw/pull/656){:target="_blank"}  from **@nclopezo**: Removing CVS Keywords from Sim `l1`  `simulation`  created: 2013-08-29 12:24:41 merged: 2013-08-29 12:31:53

101. [651](http://github.com/cms-sw/cmssw/pull/651){:target="_blank"}  from **@Dr15Jones**: Have TriggerResults see all transitions `core`  created: 2013-08-28 14:24:53 merged: 2013-08-29 08:06:32

102. [649](http://github.com/cms-sw/cmssw/pull/649){:target="_blank"}  from **@gpetruc**: MuonAnalysis/MuonAssociators gen particle migration `analysis`  created: 2013-08-28 10:49:02 merged: 2013-08-28 17:59:14

103. [232](http://github.com/cms-sw/cmssw/pull/232){:target="_blank"}  from **@davidlange6**: stuff from 612slh6 that is ahead of 70x and 620 `alca`  `geometry`  `reconstruction`  `simulation`  created: 2013-08-04 22:11:50 merged: 2013-08-28 16:54:35

104. [618](http://github.com/cms-sw/cmssw/pull/618){:target="_blank"}  from **@gartung**: changes for large object passed by value found by clang static analyzer cms.ArgSizeChecker `dqm`  `hlt`  created: 2013-08-26 16:00:20 merged: 2013-08-28 15:00:25

105. [601](http://github.com/cms-sw/cmssw/pull/601){:target="_blank"}  from **@gartung**: Cond\* -- changes for large object passed by value found by clang static ... `alca`  `db`  `dqm`  created: 2013-08-23 19:32:45 merged: 2013-08-28 14:10:54

106. [630](http://github.com/cms-sw/cmssw/pull/630){:target="_blank"}  from **@ktf**: Misc memory related fixes. `dqm`  created: 2013-08-27 12:01:01 merged: 2013-08-28 14:09:20

107. [636](http://github.com/cms-sw/cmssw/pull/636){:target="_blank"}  from **@Dr15Jones**: Have Workers for the same module use the same ModuleDescription `core`  created: 2013-08-27 16:25:35 merged: 2013-08-28 11:52:58

108. [621](http://github.com/cms-sw/cmssw/pull/621){:target="_blank"}  from **@Dr15Jones**: Sources can tell the framework they need to synchronize `core`  created: 2013-08-26 18:37:54 merged: 2013-08-28 09:50:16

109. [640](http://github.com/cms-sw/cmssw/pull/640){:target="_blank"}  from **@ktf**: Add process history map entry immediately on registration `core`  `dqm`  `generators`  created: 2013-08-27 21:39:20 merged: 2013-08-28 05:54:39

110. [590](http://github.com/cms-sw/cmssw/pull/590){:target="_blank"}  from **@ktf**: Remove mentioning of CVS. `core`  created: 2013-08-22 13:36:47 merged: 2013-08-27 20:43:32

111. [628](http://github.com/cms-sw/cmssw/pull/628){:target="_blank"}  from **@jhgoh**: Bugfix for the GenParticles2HepMCConverter `generators`  created: 2013-08-27 10:05:55 merged: 2013-08-27 20:40:25

112. [623](http://github.com/cms-sw/cmssw/pull/623){:target="_blank"}  from **@gartung**: Reco Packages -- changes for large object passed by value `analysis`  `hlt`  `reconstruction`  created: 2013-08-26 19:43:28 merged: 2013-08-27 20:39:23

113. [622](http://github.com/cms-sw/cmssw/pull/622){:target="_blank"}  from **@gartung**: PhysicsTools packages -- changes for large object passed by value  `analysis`  created: 2013-08-26 18:56:01 merged: 2013-08-27 20:38:48

114. [614](http://github.com/cms-sw/cmssw/pull/614){:target="_blank"}  from **@gartung**: Geometry -- changes for large object passed by value found by clang stat... `geometry`  created: 2013-08-26 15:12:52 merged: 2013-08-27 20:37:28

115. [599](http://github.com/cms-sw/cmssw/pull/599){:target="_blank"}  from **@gartung**: Alignment Packages  -- changes for large object passed by value `alca`  created: 2013-08-23 18:50:04 merged: 2013-08-27 20:35:40

116. [616](http://github.com/cms-sw/cmssw/pull/616){:target="_blank"}  from **@Martin-Grunewald**: Update of subtable creation tools; new subtables for string-to-InputTag migration `hlt`  created: 2013-08-26 15:17:51 merged: 2013-08-27 20:33:50

117. [608](http://github.com/cms-sw/cmssw/pull/608){:target="_blank"}  from **@Dr15Jones**: Remove makeModule from worker `core`  created: 2013-08-26 00:13:24 merged: 2013-08-27 20:29:37

118. [607](http://github.com/cms-sw/cmssw/pull/607){:target="_blank"}  from **@Dr15Jones**: Renamed edm::Selections to edm::SelectedProducts `alca`  `core`  created: 2013-08-25 18:21:57 merged: 2013-08-27 20:28:42
