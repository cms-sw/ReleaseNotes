---
layout: post
rel_link:  "7_2_0_pre1"
title:  "CMSSW_7_2_0_pre1"
date:   2014-06-24 14:31:28
categories: cmssw
relmajor: 7
relminor: 2
relsubminor: 0
relpre: _pre1
---

# CMSSW_7_2_0_pre1
#### Changes since CMSSW_7_1_0:

1. [4366](http://github.com/cms-sw/cmssw/pull/4366){:target="_blank"}  from **@ahinzmann**: Adapt edmConfigEditor for unscheduled mode. `core`  created: 2014-06-24 09:20:13 merged: 2014-06-24 11:40:06

2. [4347](http://github.com/cms-sw/cmssw/pull/4347){:target="_blank"}  from **@jpavel**: Adding offset parameter to the tau isolation. `reconstruction`  created: 2014-06-23 09:52:42 merged: 2014-06-24 11:39:09

3. [4368](http://github.com/cms-sw/cmssw/pull/4368){:target="_blank"}  from **@cms-sw**: Forward port CMSSW_7_1_X into CMSSW_7_2_X `operations`  `simulation`  created: 2014-06-24 09:53:45 merged: 2014-06-24 10:52:11

4. [4356](http://github.com/cms-sw/cmssw/pull/4356){:target="_blank"}  from **@ktf**: Fix forward port 72x `alca`  `analysis`  `daq`  `db`  `dqm`  `fastsim`  `hlt`  `l1`  `operations`  `reconstruction`  `simulation`  `visualization`  created: 2014-06-23 15:02:11 merged: 2014-06-24 08:37:55

5. [4343](http://github.com/cms-sw/cmssw/pull/4343){:target="_blank"}  from **@Martin-Grunewald**: CMSSW 710 template in ConfDb for HLT menues in 72X. `hlt`  created: 2014-06-23 08:35:13 merged: 2014-06-24 04:55:23

6. [4360](http://github.com/cms-sw/cmssw/pull/4360){:target="_blank"}  from **@civanch**: cleanup generator interface as in 4306 `simulation`  created: 2014-06-23 16:50:52 merged: 2014-06-24 04:52:39

7. [4232](http://github.com/cms-sw/cmssw/pull/4232){:target="_blank"}  from **@ktf**: Fix forward port from CMSSW_7_1_X to CMSSW_7_2_X `core`  `geometry`  `hlt`  `l1`  created: 2014-06-13 11:46:24 merged: 2014-06-23 12:51:44

8. [4322](http://github.com/cms-sw/cmssw/pull/4322){:target="_blank"}  from **@wmtan**: Remove line breaks. They cause problems `reconstruction`  created: 2014-06-19 22:26:58 merged: 2014-06-23 07:31:29

9. [4317](http://github.com/cms-sw/cmssw/pull/4317){:target="_blank"}  from **@cerati**: MultiTrackValidator remove vectors and remove unused plots. `dqm`  created: 2014-06-19 15:53:58 merged: 2014-06-22 22:04:10

10. [4174](http://github.com/cms-sw/cmssw/pull/4174){:target="_blank"}  from **@Dr15Jones**: Removed unnecessary mutable from GlobalTriggerMenu `alca`  `db`  `l1`  created: 2014-06-09 22:13:14 merged: 2014-06-22 15:28:10

11. [4320](http://github.com/cms-sw/cmssw/pull/4320){:target="_blank"}  from **@srimanob**: fix postLS1Customs.py `simulation`  created: 2014-06-19 21:01:26 merged: 2014-06-22 15:26:35

12. [4329](http://github.com/cms-sw/cmssw/pull/4329){:target="_blank"}  from **@rcastello**: Updated GTs for 7_2_0_pre1 `alca`  created: 2014-06-20 11:18:17 merged: 2014-06-20 18:59:38

13. [4259](http://github.com/cms-sw/cmssw/pull/4259){:target="_blank"}  from **@TaiSakuma**: code-cleaning in RecoMET/METProducers/python `reconstruction`  created: 2014-06-16 00:45:47 merged: 2014-06-20 17:03:26

14. [4282](http://github.com/cms-sw/cmssw/pull/4282){:target="_blank"}  from **@TaiSakuma**: delete "calotoweroptmaker" `dqm`  `operations`  `reconstruction`  `simulation`  created: 2014-06-16 23:50:20 merged: 2014-06-20 14:20:10

15. [4324](http://github.com/cms-sw/cmssw/pull/4324){:target="_blank"}  from **@mdhildreth**: Change DataMixer to merge CSC Strip Digis instead of adding duplicates `simulation`  created: 2014-06-20 04:15:26 merged: 2014-06-20 12:08:52

16. [4308](http://github.com/cms-sw/cmssw/pull/4308){:target="_blank"}  from **@deguio**: Update the configuration of the FastTimerService used for Offline DQM: same as #4307 `dqm`  created: 2014-06-18 18:06:39 merged: 2014-06-20 09:01:28

17. [4314](http://github.com/cms-sw/cmssw/pull/4314){:target="_blank"}  from **@gartung**: Remove unused declaration `core`  created: 2014-06-19 14:20:30 merged: 2014-06-19 14:24:16

18. [4293](http://github.com/cms-sw/cmssw/pull/4293){:target="_blank"}  from **@VinInn**: TLS cleanup `alca`  `db`  `reconstruction`  created: 2014-06-17 13:34:13 merged: 2014-06-19 14:08:31

19. [4285](http://github.com/cms-sw/cmssw/pull/4285){:target="_blank"}  from **@apfeiffer1**: explicitly convert Time_t to RunNumber to avoid compiler warning `alca`  created: 2014-06-17 08:20:02 merged: 2014-06-19 09:19:43

20. [4299](http://github.com/cms-sw/cmssw/pull/4299){:target="_blank"}  from **@HuguesBrun**: Fix in Higgs HLT validation DQM for multithreading `dqm`  created: 2014-06-18 07:54:53 merged: 2014-06-19 06:55:05

21. [4303](http://github.com/cms-sw/cmssw/pull/4303){:target="_blank"}  from **@deguio**: Handle correctly the ME which are not TH1 [int,string,float] `dqm`  created: 2014-06-18 12:45:55 merged: 2014-06-18 16:38:03

22. [4291](http://github.com/cms-sw/cmssw/pull/4291){:target="_blank"}  from **@thuer**: Sherpa 2.1.1 API changes. `generators`  created: 2014-06-17 12:53:10 merged: 2014-06-18 08:07:15

23. [4298](http://github.com/cms-sw/cmssw/pull/4298){:target="_blank"}  from **@threus**: Thread safety fixes for DQM/SiStripMonitorHardware `dqm`  created: 2014-06-17 17:38:16 merged: 2014-06-18 08:05:34

24. [4260](http://github.com/cms-sw/cmssw/pull/4260){:target="_blank"}  from **@barvic**: CSC DDU IDs fix for post-LS1 configuration `dqm`  `reconstruction`  created: 2014-06-16 01:32:15 merged: 2014-06-18 06:42:04

25. [4297](http://github.com/cms-sw/cmssw/pull/4297){:target="_blank"}  from **@deguio**: move L1TFED to DQMEDAnalyzer interface `dqm`  created: 2014-06-17 17:10:10 merged: 2014-06-18 06:41:17

26. [4239](http://github.com/cms-sw/cmssw/pull/4239){:target="_blank"}  from **@cerati**: MultiTrackValidator: add efficiency and fakerate vs deltaR `dqm`  created: 2014-06-13 14:41:42 merged: 2014-06-17 19:22:09

27. [4269](http://github.com/cms-sw/cmssw/pull/4269){:target="_blank"}  from **@perrotta**: HLT run2 updates `hlt`  created: 2014-06-16 12:09:40 merged: 2014-06-17 13:49:25

28. [4253](http://github.com/cms-sw/cmssw/pull/4253){:target="_blank"}  from **@davidlange6**: clear map before each event is processed in PhotonMCTruthFinder `dqm`  `reconstruction`  created: 2014-06-15 17:12:22 merged: 2014-06-17 05:44:59

29. [4248](http://github.com/cms-sw/cmssw/pull/4248){:target="_blank"}  from **@gartung**: Virtual function calls of the for Foo::bar() are not linked to their override `core`  created: 2014-06-14 16:15:37 merged: 2014-06-16 21:18:23

30. [4182](http://github.com/cms-sw/cmssw/pull/4182){:target="_blank"}  from **@perrotta**: HLT run2 menu `alca`  `fastsim`  `hlt`  created: 2014-06-10 12:51:44 merged: 2014-06-16 09:09:36

31. [4236](http://github.com/cms-sw/cmssw/pull/4236){:target="_blank"}  from **@deguio**: Fix a static variable which was removed by mistake in DQM/BeamMonitor `dqm`  created: 2014-06-13 14:15:19 merged: 2014-06-16 07:35:54

32. [4045](http://github.com/cms-sw/cmssw/pull/4045){:target="_blank"}  from **@TaiSakuma**: Use new implementation of MET corrections in PAT jetTools and start refactoring the MET uncertainty tool `analysis`  created: 2014-05-28 23:11:11 merged: 2014-06-16 06:14:07

33. [4043](http://github.com/cms-sw/cmssw/pull/4043){:target="_blank"}  from **@Dr15Jones**: Fixed incorrect virtual function overload in TSelectorAnalyzer `analysis`  created: 2014-05-28 19:53:40 merged: 2014-06-16 06:13:30

34. [4090](http://github.com/cms-sw/cmssw/pull/4090){:target="_blank"}  from **@sethcooper**: Update to sourcing data format and unpacker `reconstruction`  created: 2014-06-02 17:13:25 merged: 2014-06-16 06:13:11

35. [4091](http://github.com/cms-sw/cmssw/pull/4091){:target="_blank"}  from **@Dr15Jones**: Changed TrackWithVertexRefSelector to a stream module. `analysis`  `reconstruction`  created: 2014-06-02 17:36:43 merged: 2014-06-15 19:57:58

36. [4252](http://github.com/cms-sw/cmssw/pull/4252){:target="_blank"}  from **@davidlange6**: fix memory leak Validation/EventGenerator created: 2014-06-15 17:06:19 merged: 2014-06-15 17:06:32

37. [4250](http://github.com/cms-sw/cmssw/pull/4250){:target="_blank"}  from **@Dr15Jones**: Removed old Timing plugin declaration `core`  created: 2014-06-15 00:55:42 merged: 2014-06-15 06:47:26

38. [4064](http://github.com/cms-sw/cmssw/pull/4064){:target="_blank"}  from **@ericvaandering**: Improve LumiList `core`  created: 2014-05-30 19:03:03 merged: 2014-06-14 05:55:49

39. [4096](http://github.com/cms-sw/cmssw/pull/4096){:target="_blank"}  from **@ktf**: Final clang fix. `analysis`  `core`  created: 2014-06-03 09:34:11 merged: 2014-06-13 20:17:31

40. [4227](http://github.com/cms-sw/cmssw/pull/4227){:target="_blank"}  from **@wmtan**: Use std::shared_ptr, not boost::shared_ptr `analysis`  `core`  `daq`  `dqm`  `generators`  `geometry`  `reconstruction`  `simulation`  `visualization`  created: 2014-06-12 21:07:30 merged: 2014-06-13 11:58:43

41. [4230](http://github.com/cms-sw/cmssw/pull/4230){:target="_blank"}  from **@ktf**: Drop unused variable. `core`  created: 2014-06-13 10:02:15 merged: 2014-06-13 10:30:13

42. [4213](http://github.com/cms-sw/cmssw/pull/4213){:target="_blank"}  from **@Dr15Jones**: Add ability to account for additional CPU time per event. `core`  created: 2014-06-11 19:49:36 merged: 2014-06-13 09:10:28

43. [4173](http://github.com/cms-sw/cmssw/pull/4173){:target="_blank"}  from **@Dr15Jones**: Removed unneeded const_cast from TrackAssociatorByHits `simulation`  created: 2014-06-09 21:52:17 merged: 2014-06-13 08:58:15

44. [4162](http://github.com/cms-sw/cmssw/pull/4162){:target="_blank"}  from **@cerati**: Jet core step from710pre8 fixed `dqm`  `reconstruction`  created: 2014-06-09 15:17:10 merged: 2014-06-13 07:21:09

45. [4220](http://github.com/cms-sw/cmssw/pull/4220){:target="_blank"}  from **@jpavel**: Removed duplicated definitions of EDProducers. `reconstruction`  created: 2014-06-12 12:36:23 merged: 2014-06-13 07:19:24

46. [4034](http://github.com/cms-sw/cmssw/pull/4034){:target="_blank"}  from **@barvic**: Post-LS1 CSC integration - updated to new data format CSC packer / unpacker `analysis`  `dqm`  `reconstruction`  created: 2014-05-28 13:33:23 merged: 2014-06-13 07:18:52

47. [4106](http://github.com/cms-sw/cmssw/pull/4106){:target="_blank"}  from **@deguio**: Move the Vx3DHLTAnalyzer class to the DQMEDAnalyzer interface `dqm`  created: 2014-06-04 11:47:08 merged: 2014-06-12 18:42:02

48. [4114](http://github.com/cms-sw/cmssw/pull/4114){:target="_blank"}  from **@TaiSakuma**: Change the naming convention of CaloMETs `reconstruction`  created: 2014-06-05 02:25:46 merged: 2014-06-12 17:50:25

49. [4112](http://github.com/cms-sw/cmssw/pull/4112){:target="_blank"}  from **@ptcox**: Multithreading for CSCOfflineMonitor `dqm`  created: 2014-06-04 17:42:12 merged: 2014-06-12 17:49:41

50. [4196](http://github.com/cms-sw/cmssw/pull/4196){:target="_blank"}  from **@leggat**: Multithread pixel update - raw data error fix. `dqm`  created: 2014-06-10 18:36:41 merged: 2014-06-12 12:15:04

51. [4193](http://github.com/cms-sw/cmssw/pull/4193){:target="_blank"}  from **@wmtan**: Add missing includes. `core`  `daq`  `reconstruction`  created: 2014-06-10 17:12:56 merged: 2014-06-12 07:28:54

52. [4007](http://github.com/cms-sw/cmssw/pull/4007){:target="_blank"}  from **@TaiSakuma**: Remove unused files in RecoMET. `reconstruction`  created: 2014-05-26 04:28:06 merged: 2014-06-12 07:27:12

53. [4129](http://github.com/cms-sw/cmssw/pull/4129){:target="_blank"}  from **@Dr15Jones**: Removed unused variable to avoid valgrind error in SoftElectronMVAEstimator `reconstruction`  created: 2014-06-05 18:57:26 merged: 2014-06-12 07:25:48

54. [4104](http://github.com/cms-sw/cmssw/pull/4104){:target="_blank"}  from **@gartung**: Check the bodies of FunctionDecl's too. `core`  created: 2014-06-03 18:46:29 merged: 2014-06-11 09:20:43

55. [4158](http://github.com/cms-sw/cmssw/pull/4158){:target="_blank"}  from **@ktf**: Forward port CMSSW_7_1_X into CMSSW_7_2_X (corrected by hand) `alca`  `dqm`  created: 2014-06-07 13:30:03 merged: 2014-06-11 08:07:35

56. [4016](http://github.com/cms-sw/cmssw/pull/4016){:target="_blank"}  from **@gpetruc**: miniAOD part4 (7.2.X, only PatAlgos and cmsDriver) `analysis`  `operations`  created: 2014-05-27 11:37:11 merged: 2014-06-10 16:00:59

57. [4018](http://github.com/cms-sw/cmssw/pull/4018){:target="_blank"}  from **@ptraczyk**: RecoLocalMuon/DTSegment -- DT meantimer tune `reconstruction`  created: 2014-05-27 13:07:03 merged: 2014-06-10 14:46:49

58. [4166](http://github.com/cms-sw/cmssw/pull/4166){:target="_blank"}  from **@Dr15Jones**: Mark as thread safe classes from Geometry/EcalAlgo created: 2014-06-09 20:47:43 merged: 2014-06-09 20:50:42

59. [4156](http://github.com/cms-sw/cmssw/pull/4156){:target="_blank"}  from **@ktf**: Fix a bunch of clang warnings. `analysis`  `reconstruction`  created: 2014-06-07 13:08:18 merged: 2014-06-07 13:10:12

60. [4130](http://github.com/cms-sw/cmssw/pull/4130){:target="_blank"}  from **@civanch**: Multithreading fixes in simulation `simulation`  created: 2014-06-05 19:14:09 merged: 2014-06-06 19:21:28

61. [4128](http://github.com/cms-sw/cmssw/pull/4128){:target="_blank"}  from **@Dr15Jones**: Fixed a read of uninitialized memory in CastorMonitorModule `dqm`  created: 2014-06-05 18:56:56 merged: 2014-06-05 20:27:15

62. [4120](http://github.com/cms-sw/cmssw/pull/4120){:target="_blank"}  from **@degano**: Update RivetInterface to use Rivet 2.0.0 `generators`  created: 2014-06-05 09:33:20 merged: 2014-06-05 09:44:14

63. [4035](http://github.com/cms-sw/cmssw/pull/4035){:target="_blank"}  from **@wddgit**: Event setup exceptions. `analysis`  `core`  `geometry`  `reconstruction`  created: 2014-05-28 14:08:07 merged: 2014-06-03 23:15:59

64. [4075](http://github.com/cms-sw/cmssw/pull/4075){:target="_blank"}  from **@ktf**: Make sure files are at CERN also when specifying multiple runs. `operations`  created: 2014-06-02 11:59:26 merged: 2014-06-03 08:47:49

65. [4040](http://github.com/cms-sw/cmssw/pull/4040){:target="_blank"}  from **@ktf**: Drop tertiary vertex `reconstruction`  created: 2014-05-28 15:35:37 merged: 2014-06-03 06:11:09

66. [4071](http://github.com/cms-sw/cmssw/pull/4071){:target="_blank"}  from **@nclopezo**: Removed duplicate line in DataFormats/TauReco/BuildFile.xml `reconstruction`  created: 2014-06-02 08:18:14 merged: 2014-06-03 06:10:38

67. [4053](http://github.com/cms-sw/cmssw/pull/4053){:target="_blank"}  from **@davidlt**: Good seed producer dtor segfault. `reconstruction`  created: 2014-05-30 09:48:05 merged: 2014-06-03 06:10:01

68. [4006](http://github.com/cms-sw/cmssw/pull/4006){:target="_blank"}  from **@TaiSakuma**: Make "alias" optional in *METProducer. `reconstruction`  created: 2014-05-25 23:16:06 merged: 2014-06-03 06:09:23

69. [4005](http://github.com/cms-sw/cmssw/pull/4005){:target="_blank"}  from **@TaiSakuma**: Remove unused cfi file in RecoMET. `reconstruction`  created: 2014-05-25 21:30:19 merged: 2014-06-03 06:04:07

70. [4044](http://github.com/cms-sw/cmssw/pull/4044){:target="_blank"}  from **@Dr15Jones**: Clang fixes for RecoMuon/MuonSeedGenerator `reconstruction`  created: 2014-05-28 20:13:14 merged: 2014-06-03 05:46:27

71. [4068](http://github.com/cms-sw/cmssw/pull/4068){:target="_blank"}  from **@apfeiffer1**: Update serialisation generator script. `db`  created: 2014-05-31 14:14:10 merged: 2014-06-02 09:31:19

72. [4057](http://github.com/cms-sw/cmssw/pull/4057){:target="_blank"}  from **@nclopezo**: Static Analyser -- Changed the configuration for the static analyser `core`  created: 2014-05-30 14:52:14 merged: 2014-06-02 08:03:59

73. [3971](http://github.com/cms-sw/cmssw/pull/3971){:target="_blank"}  from **@cms-tau-pog**: Tau quality cuts update. `reconstruction`  created: 2014-05-22 16:40:12 merged: 2014-06-02 06:25:46

74. [3993](http://github.com/cms-sw/cmssw/pull/3993){:target="_blank"}  from **@jpavel**: Saving tau decay mode inside PFTau and patTau. `analysis`  `reconstruction`  created: 2014-05-23 17:00:56 merged: 2014-05-30 18:50:40

75. [4019](http://github.com/cms-sw/cmssw/pull/4019){:target="_blank"}  from **@deguio**: Enhancing the igetter functionalities: addint DQMStore::IGetter::removeElement `dqm`  created: 2014-05-27 14:02:23 merged: 2014-05-30 18:49:04

76. [4046](http://github.com/cms-sw/cmssw/pull/4046){:target="_blank"}  from **@ktf**: Fix clang bug `analysis`  created: 2014-05-29 09:06:55 merged: 2014-05-30 11:23:42

77. [4042](http://github.com/cms-sw/cmssw/pull/4042){:target="_blank"}  from **@Dr15Jones**: Added tryToGet method to EventSetup and EventSetupRecord. `core`  created: 2014-05-28 18:20:00 merged: 2014-05-29 16:29:59

78. [3966](http://github.com/cms-sw/cmssw/pull/3966){:target="_blank"}  from **@VinInn**: SingleObjectSelector as stream module. `analysis`  `dqm`  `reconstruction`  created: 2014-05-22 14:43:15 merged: 2014-05-29 12:09:28

79. [4020](http://github.com/cms-sw/cmssw/pull/4020){:target="_blank"}  from **@VinInn**: Tau discrimination producers (not yet) stream `reconstruction`  created: 2014-05-27 16:29:05 merged: 2014-05-28 14:32:04

80. [4015](http://github.com/cms-sw/cmssw/pull/4015){:target="_blank"}  from **@ktf**: More clang fixes. `alca`  `analysis`  `db`  `dqm`  `generators`  `geometry`  `l1`  `reconstruction`  `simulation`  created: 2014-05-27 06:57:16 merged: 2014-05-28 13:43:37

81. [4033](http://github.com/cms-sw/cmssw/pull/4033){:target="_blank"}  from **@smuzaffar**: Fix duplicate reflex library search for patch releases created: 2014-05-28 12:59:46 merged: 2014-05-28 12:59:52

82. [4023](http://github.com/cms-sw/cmssw/pull/4023){:target="_blank"}  from **@Dr15Jones**: Have the command line arg -n override numberOfThreads in config `core`  created: 2014-05-27 21:46:03 merged: 2014-05-28 01:09:15

83. [4014](http://github.com/cms-sw/cmssw/pull/4014){:target="_blank"}  from **@TaiSakuma**: Prepare to delete old definitions of corrected CaloMETs `analysis`  created: 2014-05-26 23:30:51 merged: 2014-05-27 19:11:01

84. [3965](http://github.com/cms-sw/cmssw/pull/3965){:target="_blank"}  from **@vadler**: Update test input RelVal RecoMET/METProducers `reconstruction`  created: 2014-05-22 14:32:43 merged: 2014-05-27 13:50:26

85. [3989](http://github.com/cms-sw/cmssw/pull/3989){:target="_blank"}  from **@lveldere**: FastSim -- Switch to Pythia 8 for FastSim decays  `fastsim`  created: 2014-05-23 13:14:46 merged: 2014-05-26 07:48:51

86. [3988](http://github.com/cms-sw/cmssw/pull/3988){:target="_blank"}  from **@apfeiffer1**: Fix missing qg likelihood 72x `db`  created: 2014-05-23 13:14:35 merged: 2014-05-23 13:27:33

87. [3948](http://github.com/cms-sw/cmssw/pull/3948){:target="_blank"}  from **@davidlt**: ARM64 -- condformats_serialization_generate.py: support for aarch64 `db`  created: 2014-05-21 14:08:50 merged: 2014-05-22 15:09:00

88. [3951](http://github.com/cms-sw/cmssw/pull/3951){:target="_blank"}  from **@davidlt**: ARM64 -- DataFormats/Math: rdtscp.h disable on aarch64 `reconstruction`  created: 2014-05-21 15:33:33 merged: 2014-05-22 13:12:14

89. [3942](http://github.com/cms-sw/cmssw/pull/3942){:target="_blank"}  from **@TaiSakuma**: Reco -- Change the naming convention of CaloMETs `analysis`  `dqm`  `reconstruction`  created: 2014-05-20 18:17:10 merged: 2014-05-22 07:49:24

90. [3946](http://github.com/cms-sw/cmssw/pull/3946){:target="_blank"}  from **@gpetruc**: MiniAOD part 3 (7.2.X clone of the 7.1.X PR) `analysis`  `core`  `operations`  `reconstruction`  created: 2014-05-21 11:54:26 merged: 2014-05-21 19:34:05
