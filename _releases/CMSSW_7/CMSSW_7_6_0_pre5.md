---
layout: post
rel_link:  "7_6_0_pre5"
title:  "CMSSW_7_6_0_pre5"
date:   2015-09-11 12:53:17
categories: cmssw
relmajor: 7
relminor: 6
relsubminor: 0
relpre: _pre5
---

# CMSSW_7_6_0_pre5
#### Changes since CMSSW_7_6_0_pre4:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_6_0_pre4...CMSSW_7_6_0_pre5)



1. [11132](http://github.com/cms-sw/cmssw/pull/11132){:target="_blank"}  from **@davidsheffield**: Add scouting electron, photon, and muon classes and producers `hlt`  created: 2015-09-04 14:55:13 merged: 2015-09-11 09:31:46

2. [11135](http://github.com/cms-sw/cmssw/pull/11135){:target="_blank"}  from **@Dr15Jones**: Made MaterialAccountingTrack const correct `simulation`  created: 2015-09-04 15:55:33 merged: 2015-09-11 09:30:24

3. [11043](http://github.com/cms-sw/cmssw/pull/11043){:target="_blank"}  from **@cms-tsg-storm**: 76X 25ns HLT round three `hlt`  created: 2015-08-31 13:32:57 merged: 2015-09-11 07:56:32

4. [11183](http://github.com/cms-sw/cmssw/pull/11183){:target="_blank"}  from **@makortel**: Fix MeasurementTrackerEvent configuration of some TrackingRegionProducers `fastsim`  `hlt`  `reconstruction`  created: 2015-09-08 07:32:48 merged: 2015-09-11 07:51:10

5. [11140](http://github.com/cms-sw/cmssw/pull/11140){:target="_blank"}  from **@cvuosalo**: Convert remaining legacy modules in RECO to support multi-threading `analysis`  `reconstruction`  created: 2015-09-04 17:14:42 merged: 2015-09-11 07:05:08

6. [11146](http://github.com/cms-sw/cmssw/pull/11146){:target="_blank"}  from **@Dr15Jones**: Use iorule to remove mutables from CandKinResolution `analysis`  created: 2015-09-04 21:03:14 merged: 2015-09-11 07:03:53

7. [11158](http://github.com/cms-sw/cmssw/pull/11158){:target="_blank"}  from **@smorovic**: Fix premature end of run in DAQ (76X) `daq`  `reconstruction`  created: 2015-09-05 21:38:25 merged: 2015-09-11 07:02:35

8. [11219](http://github.com/cms-sw/cmssw/pull/11219){:target="_blank"}  from **@ndaci**:  Updated paths (DiPhoton, HighPtPhoton). `dqm`  created: 2015-09-10 10:39:37 merged: 2015-09-11 06:59:47

9. [11145](http://github.com/cms-sw/cmssw/pull/11145){:target="_blank"}  from **@Dr15Jones**: Made PFTau const thread-safe `reconstruction`  created: 2015-09-04 19:50:16 merged: 2015-09-10 09:01:26

10. [11173](http://github.com/cms-sw/cmssw/pull/11173){:target="_blank"}  from **@slava77**: cleanup of uninitialized reads reported by valgrind `analysis`  `dqm`  `reconstruction`  created: 2015-09-07 19:30:16 merged: 2015-09-10 08:57:19

11. [11201](http://github.com/cms-sw/cmssw/pull/11201){:target="_blank"}  from **@lveldere**: FastSim, use cms::Exception rather than logError + exit `fastsim`  created: 2015-09-09 12:57:42 merged: 2015-09-10 08:31:14

12. [11202](http://github.com/cms-sw/cmssw/pull/11202){:target="_blank"}  from **@smuzaffar**: fixed typo: RecoEGamma/Examples -> RecoEgamma/Examples `core`  created: 2015-09-09 13:17:28 merged: 2015-09-09 13:23:02

13. [11139](http://github.com/cms-sw/cmssw/pull/11139){:target="_blank"}  from **@matteosan1**: Roll-back to old configuration to fix issue in VID `reconstruction`  created: 2015-09-04 16:19:24 merged: 2015-09-09 12:21:21

14. [11121](http://github.com/cms-sw/cmssw/pull/11121){:target="_blank"}  from **@lveldere**: Fastsim newrechits rebase sep4 `analysis`  `fastsim`  `geometry`  `reconstruction`  `simulation`  created: 2015-09-04 09:44:33 merged: 2015-09-09 10:20:17

15. [11063](http://github.com/cms-sw/cmssw/pull/11063){:target="_blank"}  from **@ndaci**: Added a new path in DiPhoton category. `dqm`  created: 2015-09-01 15:24:51 merged: 2015-09-09 05:25:38

16. [11192](http://github.com/cms-sw/cmssw/pull/11192){:target="_blank"}  from **@Dr15Jones**: Marked DataProxy as thread safe `core`  created: 2015-09-08 19:53:07 merged: 2015-09-09 05:23:31

17. [11089](http://github.com/cms-sw/cmssw/pull/11089){:target="_blank"}  from **@VinInn**: fix inner outer for OutIn `reconstruction`  created: 2015-09-02 16:01:35 merged: 2015-09-09 05:23:12

18. [11079](http://github.com/cms-sw/cmssw/pull/11079){:target="_blank"}  from **@pietverwilligen**: Update test gem rec hit analyzer `reconstruction`  created: 2015-09-02 10:37:23 merged: 2015-09-08 12:35:47

19. [11035](http://github.com/cms-sw/cmssw/pull/11035){:target="_blank"}  from **@ebouvier**: Top trigger names for 25 ns 76X `dqm`  created: 2015-08-31 08:20:02 merged: 2015-09-08 12:35:14

20. [11083](http://github.com/cms-sw/cmssw/pull/11083){:target="_blank"}  from **@wulsin**: Add customize configuration file to produce/keep a collection of part `simulation`  created: 2015-09-02 13:05:42 merged: 2015-09-08 05:31:09

21. [11161](http://github.com/cms-sw/cmssw/pull/11161){:target="_blank"}  from **@Sam-Harper**: DiEle25 dqm update `dqm`  created: 2015-09-06 15:42:43 merged: 2015-09-08 05:26:09

22. [11115](http://github.com/cms-sw/cmssw/pull/11115){:target="_blank"}  from **@smorovic**: Streamer output modules ported to one::OutputModule (76X) `core`  `daq`  `dqm`  `reconstruction`  created: 2015-09-03 21:05:11 merged: 2015-09-08 05:21:29

23. [11142](http://github.com/cms-sw/cmssw/pull/11142){:target="_blank"}  from **@Dr15Jones**: Made BeamCurrentInfo thread-safe via use of iorules `reconstruction`  created: 2015-09-04 18:14:35 merged: 2015-09-08 05:21:25

24. [11170](http://github.com/cms-sw/cmssw/pull/11170){:target="_blank"}  from **@dmitrijus**: Fix a 'kNoTypesStored' bug in DQMRootSource (76x) `dqm`  created: 2015-09-07 09:02:06 merged: 2015-09-08 05:21:09

25. [11167](http://github.com/cms-sw/cmssw/pull/11167){:target="_blank"}  from **@alja**: 75x Fireworks: auto-detect configuration after opening first file -- git reattempt 2 `visualization`  created: 2015-09-06 21:51:56 merged: 2015-09-07 10:01:22

26. [11144](http://github.com/cms-sw/cmssw/pull/11144){:target="_blank"}  from **@Dr15Jones**: Release shared resources when use mayConsumes `core`  `simulation`  created: 2015-09-04 19:35:23 merged: 2015-09-07 05:54:27

27. [11112](http://github.com/cms-sw/cmssw/pull/11112){:target="_blank"}  from **@makortel**: Forward originalAlgo and algoMask in TrackRefitter `reconstruction`  created: 2015-09-03 14:31:03 merged: 2015-09-05 06:56:14

28. [11143](http://github.com/cms-sw/cmssw/pull/11143){:target="_blank"}  from **@wmtan**: Maintainability cleanup for EventSelector `core`  created: 2015-09-04 18:24:31 merged: 2015-09-05 06:56:09

29. [11147](http://github.com/cms-sw/cmssw/pull/11147){:target="_blank"}  from **@gartung**: Only check const cast away in CStyle casts and const_cast<> expresssions `core`  created: 2015-09-04 21:44:46 merged: 2015-09-05 06:51:10

30. [10904](http://github.com/cms-sw/cmssw/pull/10904){:target="_blank"}  from **@ggovi**: Prototype of payload inspector modules for V2 `alca`  `db`  created: 2015-08-21 14:32:37 merged: 2015-09-04 15:51:45

31. [10821](http://github.com/cms-sw/cmssw/pull/10821){:target="_blank"}  from **@slehti**: Hlt tau validation update76X `dqm`  created: 2015-08-17 15:11:43 merged: 2015-09-04 15:46:43

32. [11125](http://github.com/cms-sw/cmssw/pull/11125){:target="_blank"}  from **@vasile-ghete**: Cmssw 7 6 x L1 gt utils update `l1`  created: 2015-09-04 12:46:03 merged: 2015-09-04 15:43:59

33. [11097](http://github.com/cms-sw/cmssw/pull/11097){:target="_blank"}  from **@civanch**: Fixed static analyzer warnings `simulation`  created: 2015-09-03 08:54:18 merged: 2015-09-04 13:31:36

34. [11106](http://github.com/cms-sw/cmssw/pull/11106){:target="_blank"}  from **@istaslis**: Added dummy parameters to HIMultiTrackSelector `reconstruction`  created: 2015-09-03 11:52:46 merged: 2015-09-04 09:51:29

35. [10972](http://github.com/cms-sw/cmssw/pull/10972){:target="_blank"}  from **@degano**: Fix EvtGenInterface report instruction to comply with evtgen 1.4. `generators`  created: 2015-08-27 08:08:57 merged: 2015-09-04 09:01:37

36. [10911](http://github.com/cms-sw/cmssw/pull/10911){:target="_blank"}  from **@makortel**: Transform RecoTrackRefSelector to stream::EDProducer `hlt`  `reconstruction`  created: 2015-08-24 07:15:34 merged: 2015-09-04 07:21:37

37. [11099](http://github.com/cms-sw/cmssw/pull/11099){:target="_blank"}  from **@heppye**: Create Create Bd_JpsiKPi.dec `generators`  created: 2015-09-03 09:01:21 merged: 2015-09-03 14:01:51

38. [10242](http://github.com/cms-sw/cmssw/pull/10242){:target="_blank"}  from **@hdelanno**: Addition of histograms for SiStrip : Cluster widths vs amplitudes `dqm`  created: 2015-07-16 12:21:05 merged: 2015-09-03 10:52:09

39. [11050](http://github.com/cms-sw/cmssw/pull/11050){:target="_blank"}  from **@fwyzard**: DQMStore::removeElement: do not remove non-existing MEs `dqm`  created: 2015-08-31 20:51:58 merged: 2015-09-03 10:51:45

40. [10907](http://github.com/cms-sw/cmssw/pull/10907){:target="_blank"}  from **@ndaci**: Fixed path names. Removed pt2 and pt3 in unnecessary cases. Added deb `dqm`  created: 2015-08-22 13:11:33 merged: 2015-09-03 07:56:30

41. [11072](http://github.com/cms-sw/cmssw/pull/11072){:target="_blank"}  from **@fwyzard**: migrate modules used by the HLT menu to multithreading (L1) (76x) `l1`  created: 2015-09-02 07:18:28 merged: 2015-09-03 07:53:41

42. [10974](http://github.com/cms-sw/cmssw/pull/10974){:target="_blank"}  from **@ndaci**: Update paths. `dqm`  created: 2015-08-27 08:44:46 merged: 2015-09-03 07:51:45

43. [10989](http://github.com/cms-sw/cmssw/pull/10989){:target="_blank"}  from **@ianna**: Update Validation to Use Default GT `db`  `dqm`  `geometry`  created: 2015-08-27 14:56:27 merged: 2015-09-03 07:51:39

44. [11001](http://github.com/cms-sw/cmssw/pull/11001){:target="_blank"}  from **@lveldere**: Introduce slim track validation sequences  `dqm`  created: 2015-08-28 10:03:49 merged: 2015-09-03 07:51:33

45. [11040](http://github.com/cms-sw/cmssw/pull/11040){:target="_blank"}  from **@danduggan**: Patching to better handle LS based histos during LS transitions in 76x `dqm`  created: 2015-08-31 11:34:59 merged: 2015-09-03 07:51:23

46. [11090](http://github.com/cms-sw/cmssw/pull/11090){:target="_blank"}  from **@gartung**: add edm::serviceregistry::ServicesManager::MakerHolder::add() to skip `core`  created: 2015-09-02 17:27:29 merged: 2015-09-03 07:51:18

47. [11029](http://github.com/cms-sw/cmssw/pull/11029){:target="_blank"}  from **@davidsheffield**: Add index to primary vertex in scouting particle collection `hlt`  created: 2015-08-31 00:04:45 merged: 2015-09-03 07:48:11

48. [11073](http://github.com/cms-sw/cmssw/pull/11073){:target="_blank"}  from **@cms-sw**: Revert "adding David Lange's comments built on rebase of ValidationDo `dqm`  `generators`  created: 2015-09-02 07:32:31 merged: 2015-09-02 07:41:14

49. [10695](http://github.com/cms-sw/cmssw/pull/10695){:target="_blank"}  from **@cms-l1t-offline**: Add HF Minimum Bias algorithm to Stage1 Emulator `l1`  created: 2015-08-11 18:02:24 merged: 2015-09-02 06:31:29

50. [10963](http://github.com/cms-sw/cmssw/pull/10963){:target="_blank"}  from **@ngrenz**: ngrenz: testing of stereo optimization `reconstruction`  `simulation`  created: 2015-08-27 04:44:22 merged: 2015-09-02 06:26:48

51. [10984](http://github.com/cms-sw/cmssw/pull/10984){:target="_blank"}  from **@davidlt**: runTheMatrix.py: misc cleanups; make --showMatrix consistent `pdmv`  created: 2015-08-27 13:21:49 merged: 2015-09-02 06:26:30

52. [11028](http://github.com/cms-sw/cmssw/pull/11028){:target="_blank"}  from **@ahinzmann**: Add energy correlation functions to jet tools `reconstruction`  created: 2015-08-29 21:44:28 merged: 2015-09-02 06:26:25

53. [10917](http://github.com/cms-sw/cmssw/pull/10917){:target="_blank"}  from **@gpetruc**: Add L1 prescales to the miniAOD (76X port of #10895) `analysis`  created: 2015-08-24 09:47:36 merged: 2015-09-02 06:26:17

54. [11045](http://github.com/cms-sw/cmssw/pull/11045){:target="_blank"}  from **@kkiesel**: Fastsim ECAL response correction (2) `fastsim`  created: 2015-08-31 14:54:02 merged: 2015-09-02 06:26:11

55. [11066](http://github.com/cms-sw/cmssw/pull/11066){:target="_blank"}  from **@wmtan**: Use anonymous namespaces to avoid duplicate symbols `reconstruction`  created: 2015-09-01 18:37:52 merged: 2015-09-02 06:21:10

56. [11053](http://github.com/cms-sw/cmssw/pull/11053){:target="_blank"}  from **@fwyzard**: migrate L1 and HLT summary modules to one::EDAnalyzer `hlt`  `l1`  created: 2015-08-31 20:58:25 merged: 2015-09-01 16:16:42

57. [10958](http://github.com/cms-sw/cmssw/pull/10958){:target="_blank"}  from **@fwyzard**: migrate modules used by the HLT menu to multithreading (various) `analysis`  `db`  `dqm`  `hlt`  `l1`  created: 2015-08-26 15:43:19 merged: 2015-09-01 16:12:49

58. [10842](http://github.com/cms-sw/cmssw/pull/10842){:target="_blank"}  from **@apfeiffer1**: update of the XML conversion in C++  `db`  created: 2015-08-18 14:48:32 merged: 2015-09-01 16:12:39

59. [10971](http://github.com/cms-sw/cmssw/pull/10971){:target="_blank"}  from **@cerminar**: First integration of Pixel Alignment of large structures in PCL - updated (76X)  `alca`  `db`  `operations`  `pdmv`  created: 2015-08-27 07:35:07 merged: 2015-09-01 05:21:43

60. [10977](http://github.com/cms-sw/cmssw/pull/10977){:target="_blank"}  from **@kodolova**: Fix bug in JetPlusTrackCorrections_cff.py: add JetVertexExtender `reconstruction`  created: 2015-08-27 09:37:37 merged: 2015-09-01 05:21:35

61. [11051](http://github.com/cms-sw/cmssw/pull/11051){:target="_blank"}  from **@fwyzard**: ThroughputServiceClient: add more throughput plots `hlt`  created: 2015-08-31 20:54:47 merged: 2015-09-01 05:21:10

62. [10836](http://github.com/cms-sw/cmssw/pull/10836){:target="_blank"}  from **@cms-tsg-storm**: Round Two 25ns HLT updates (76X) `hlt`  created: 2015-08-18 08:06:32 merged: 2015-08-31 09:51:54

63. [10979](http://github.com/cms-sw/cmssw/pull/10979){:target="_blank"}  from **@lveldere**: FastSim: remove import of non-existing cfg from START geometry `fastsim`  created: 2015-08-27 12:09:58 merged: 2015-08-31 09:46:47

64. [10988](http://github.com/cms-sw/cmssw/pull/10988){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `alca`  created: 2015-08-27 14:52:47 merged: 2015-08-30 14:18:36

65. [11018](http://github.com/cms-sw/cmssw/pull/11018){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `l1`  created: 2015-08-28 17:45:01 merged: 2015-08-30 14:17:17

66. [11017](http://github.com/cms-sw/cmssw/pull/11017){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `l1`  created: 2015-08-28 17:25:34 merged: 2015-08-30 14:17:00

67. [11016](http://github.com/cms-sw/cmssw/pull/11016){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `dqm`  created: 2015-08-28 16:55:10 merged: 2015-08-30 14:16:40

68. [11015](http://github.com/cms-sw/cmssw/pull/11015){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `dqm`  created: 2015-08-28 15:55:31 merged: 2015-08-30 14:16:22

69. [11014](http://github.com/cms-sw/cmssw/pull/11014){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `generators`  created: 2015-08-28 15:29:42 merged: 2015-08-30 14:16:04

70. [11006](http://github.com/cms-sw/cmssw/pull/11006){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `analysis`  created: 2015-08-28 14:16:57 merged: 2015-08-30 14:15:46

71. [11005](http://github.com/cms-sw/cmssw/pull/11005){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `dqm`  `l1`  created: 2015-08-28 14:10:30 merged: 2015-08-30 14:15:28

72. [11003](http://github.com/cms-sw/cmssw/pull/11003){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `dqm`  created: 2015-08-28 14:04:23 merged: 2015-08-30 14:15:07

73. [10997](http://github.com/cms-sw/cmssw/pull/10997){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `dqm`  created: 2015-08-28 02:42:46 merged: 2015-08-30 14:14:49

74. [10990](http://github.com/cms-sw/cmssw/pull/10990){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `alca`  `l1`  created: 2015-08-27 15:30:29 merged: 2015-08-30 14:14:30

75. [10653](http://github.com/cms-sw/cmssw/pull/10653){:target="_blank"}  from **@echapon**: New track algorithm names for HI muon RegIt `reconstruction`  created: 2015-08-10 15:15:48 merged: 2015-08-30 07:16:17

76. [10947](http://github.com/cms-sw/cmssw/pull/10947){:target="_blank"}  from **@ssanders50**: boundary check `reconstruction`  created: 2015-08-26 09:26:12 merged: 2015-08-30 07:16:09

77. [10873](http://github.com/cms-sw/cmssw/pull/10873){:target="_blank"}  from **@lgray**: Important-> EDM IDs update, Fixed typo in effective areas. `analysis`  `reconstruction`  created: 2015-08-20 10:29:32 merged: 2015-08-30 07:11:29

78. [10923](http://github.com/cms-sw/cmssw/pull/10923){:target="_blank"}  from **@ahinzmann**: Switch to latest pileup jet id in DQM `dqm`  created: 2015-08-24 15:02:38 merged: 2015-08-30 07:11:22

79. [10951](http://github.com/cms-sw/cmssw/pull/10951){:target="_blank"}  from **@wmtan**: Thread Safety: Remove unneeded state from TriggerResultsBasedEventSelector `core`  created: 2015-08-26 14:57:04 merged: 2015-08-30 07:11:10

80. [10995](http://github.com/cms-sw/cmssw/pull/10995){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `dqm`  created: 2015-08-28 02:09:42 merged: 2015-08-30 07:07:36

81. [10996](http://github.com/cms-sw/cmssw/pull/10996){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `dqm`  created: 2015-08-28 02:28:31 merged: 2015-08-30 07:07:13

82. [11000](http://github.com/cms-sw/cmssw/pull/11000){:target="_blank"}  from **@fwyzard**: more cleanup of RecoLocalMuon/RPCRecHit `reconstruction`  created: 2015-08-28 08:39:18 merged: 2015-08-30 07:06:55

83. [11011](http://github.com/cms-sw/cmssw/pull/11011){:target="_blank"}  from **@Dr15Jones**: Fix bug preventing the use of a local cache `core`  created: 2015-08-28 14:41:22 merged: 2015-08-30 07:06:49

84. [11020](http://github.com/cms-sw/cmssw/pull/11020){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `reconstruction`  created: 2015-08-28 18:41:02 merged: 2015-08-30 07:06:44

85. [11021](http://github.com/cms-sw/cmssw/pull/11021){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `simulation`  created: 2015-08-28 18:41:52 merged: 2015-08-30 07:06:38

86. [10998](http://github.com/cms-sw/cmssw/pull/10998){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `dqm`  created: 2015-08-28 02:52:59 merged: 2015-08-30 07:06:06

87. [11008](http://github.com/cms-sw/cmssw/pull/11008){:target="_blank"}  from **@gartung**: Event filter utilities fix clang warning `daq`  `hlt`  `reconstruction`  created: 2015-08-28 14:36:34 merged: 2015-08-30 07:05:10

88. [11019](http://github.com/cms-sw/cmssw/pull/11019){:target="_blank"}  from **@gartung**: fix clang static analyzer warning using namespace in header `analysis`  created: 2015-08-28 18:16:06 merged: 2015-08-30 07:04:05

#### CMSDIST Changes between Tags REL/CMSSW_7_6_0_pre4/slc6_amd64_gcc493 and REL/CMSSW_7_6_0_pre5/slc6_amd64_gcc493:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_6_0_pre4/slc6_amd64_gcc493...REL/CMSSW_7_6_0_pre5/slc6_amd64_gcc493)



1. [1803](http://github.com/cms-sw/cmsdist/pull/1803){:target="_blank"}  from **@degano**: Update geant4 to version 10.01.p02. created: 2015-09-09 14:41:24 merged: 2015-09-09 14:42:00

2. [1802](http://github.com/cms-sw/cmsdist/pull/1802){:target="_blank"}  from **@smuzaffar**: move to latest config tag V05-05-03 created: 2015-09-09 07:28:32 merged: 2015-09-09 07:28:44

3. [1800](http://github.com/cms-sw/cmsdist/pull/1800){:target="_blank"}  from **@degano**: Update data for Configuration/Generator. created: 2015-09-08 14:17:46 merged: 2015-09-08 14:17:49

4. [1777](http://github.com/cms-sw/cmsdist/pull/1777){:target="_blank"}  from **@cms-sw**: Revert "Revert "upgrade to evtgen 1.4.0p1"" created: 2015-08-27 08:08:10 merged: 2015-09-04 09:01:31

5. [1795](http://github.com/cms-sw/cmsdist/pull/1795){:target="_blank"}  from **@degano**: Create new data for RecoBTag/CTagging from repository. created: 2015-09-04 08:59:55 merged: 2015-09-04 08:59:59

6. [1791](http://github.com/cms-sw/cmsdist/pull/1791){:target="_blank"}  from **@degano**: Update Root to the tip of the branch 6.02.00-patches. created: 2015-09-03 11:59:30 merged: 2015-09-03 14:21:29

7. [1775](http://github.com/cms-sw/cmsdist/pull/1775){:target="_blank"}  from **@davidlt**: GDB, SQLite, CMake, CGAL, libxslt updates created: 2015-08-26 16:23:10 merged: 2015-09-01 12:37:53

8. [1786](http://github.com/cms-sw/cmsdist/pull/1786){:target="_blank"}  from **@degano**: Add python modules: PyYAML, docopt, prettytable, schema. created: 2015-09-01 09:51:11 merged: 2015-09-01 10:08:53

9. [1781](http://github.com/cms-sw/cmsdist/pull/1781){:target="_blank"}  from **@degano**: Update to latest CondFormats/JetMETObjects created: 2015-08-31 09:37:51 merged: 2015-08-31 09:37:57
