---
layout: post
rel_link:  "9_1_0_pre1"
title:  "CMSSW_9_1_0_pre1"
date:   2017-03-22 16:05:59
categories: cmssw
relmajor: 9
relminor: 1
relsubminor: 0
relpre: _pre1
---

# CMSSW_9_1_0_pre1
#### Changes since CMSSW_9_0_0:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_9_0_0...CMSSW_9_1_0_pre1)



1. [18036](http://github.com/cms-sw/cmssw/pull/18036){:target="_blank"}  from **@cms-sw**: Revert "Bin lookup in the JetCorrectorParameters class" `analysis`  `comparison`  `db`  created: 2017-03-22 15:59:04 merged: 2017-03-22 15:59:30

2. [18034](http://github.com/cms-sw/cmssw/pull/18034){:target="_blank"}  from **@cerminar**: Fix the handling of ALCARECO output for steps which don't require the creation of a combined stream (i.e. all cases but the Tier0 one) `operations`  created: 2017-03-22 13:03:01 merged: 2017-03-22 16:03:34

3. [18029](http://github.com/cms-sw/cmssw/pull/18029){:target="_blank"}  from @cms-sw: Revert "add PV monitoring **@HLT**" `comparison`  `dqm`  `hlt`  `operations`  `pdmv`  `reconstruction`  `simulation`  `upgrade`  created: 2017-03-22 08:26:26 merged: 2017-03-22 08:37:41

4. [18027](http://github.com/cms-sw/cmssw/pull/18027){:target="_blank"}  from **@fioriNTU**: Phase1 Geometry in Online `dqm`  created: 2017-03-22 06:58:15 merged: 2017-03-22 12:51:30

5. [18022](http://github.com/cms-sw/cmssw/pull/18022){:target="_blank"}  from **@wddgit**: Fix problem introduced by recent PR #17950 related to dropOnInput `core`  created: 2017-03-21 20:31:00 merged: 2017-03-22 06:51:07

6. [18008](http://github.com/cms-sw/cmssw/pull/18008){:target="_blank"}  from **@ianna**: Zero Material 2017 Plan1 Scenario `geometry`  `upgrade`  created: 2017-03-21 11:37:26 merged: 2017-03-22 09:02:05

7. [18003](http://github.com/cms-sw/cmssw/pull/18003){:target="_blank"}  from **@rovere**: Material in color `simulation`  created: 2017-03-20 20:51:04 merged: 2017-03-21 16:48:21

8. [18000](http://github.com/cms-sw/cmssw/pull/18000){:target="_blank"}  from **@civanch**: Removed time cut in calorimeters for neutron background simulation `core`  `simulation`  created: 2017-03-20 18:54:07 merged: 2017-03-21 17:04:13

9. [17999](http://github.com/cms-sw/cmssw/pull/17999){:target="_blank"}  from **@gartung**: Enable ROOT ImplicitMT through config `comparison`  `core`  created: 2017-03-20 18:49:12 merged: 2017-03-21 16:49:00

10. [17998](http://github.com/cms-sw/cmssw/pull/17998){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-gem25 Correct the gap between eta section of GE21 `geometry`  created: 2017-03-20 16:54:05 merged: 2017-03-21 08:28:32

11. [17997](http://github.com/cms-sw/cmssw/pull/17997){:target="_blank"}  from **@gartung**: Fix gcc6 misleading-indentation warning `reconstruction`  created: 2017-03-20 16:40:56 merged: 2017-03-22 16:02:27

12. [17996](http://github.com/cms-sw/cmssw/pull/17996){:target="_blank"}  from @mtosi: add PV monitoring **@HLT** `dqm`  `hlt`  `operations`  `pdmv`  `reconstruction`  `simulation`  `upgrade`  created: 2017-03-20 16:28:02 merged: 2017-03-21 16:51:52

13. [17994](http://github.com/cms-sw/cmssw/pull/17994){:target="_blank"}  from **@imKuehlschrank**: add plot params to individual histograms created in the geometry hierarchy `dqm`  created: 2017-03-20 14:41:19 merged: 2017-03-22 06:53:53

14. [17993](http://github.com/cms-sw/cmssw/pull/17993){:target="_blank"}  from **@suchandradutta**: TrackerMap creation script updated  `dqm`  created: 2017-03-20 12:01:18 merged: 2017-03-21 08:29:05

15. [17991](http://github.com/cms-sw/cmssw/pull/17991){:target="_blank"}  from **@silviodonato**: Minor bug fix in hltGetConfiguration (91X) `hlt`  created: 2017-03-20 10:51:39 merged: 2017-03-20 20:31:51

16. [17989](http://github.com/cms-sw/cmssw/pull/17989){:target="_blank"}  from **@anorkus**: Removed CouchURL param from injection dict in 91X `pdmv`  `upgrade`  created: 2017-03-20 09:51:41 merged: 2017-03-20 20:31:59

17. [17985](http://github.com/cms-sw/cmssw/pull/17985){:target="_blank"}  from **@civanch**: Fixed new cavern description `geometry`  `upgrade`  created: 2017-03-19 21:48:03 merged: 2017-03-20 09:21:57

18. [17983](http://github.com/cms-sw/cmssw/pull/17983){:target="_blank"}  from **@mariadalfonso**: HBHE M3 = fix M3  `alca`  `reconstruction`  created: 2017-03-19 09:39:02 merged: 2017-03-21 19:49:04

19. [17982](http://github.com/cms-sw/cmssw/pull/17982){:target="_blank"}  from **@Dr15Jones**: Task based stream begin transitions `core`  created: 2017-03-18 19:53:37 merged: 2017-03-20 09:23:23

20. [17981](http://github.com/cms-sw/cmssw/pull/17981){:target="_blank"}  from **@mmusich**: [91X] fix ShallowEventDataProducer to allow running SiStripGain PCL producers from 2016 ALCARECO   `alca`  created: 2017-03-18 10:20:54 merged: 2017-03-21 16:50:05

protects SiStripGains PCL algorithm when analyzing ALCARECO data produced with versions not containing #17419



21. [17980](http://github.com/cms-sw/cmssw/pull/17980){:target="_blank"}  from **@mmusich**: [91X] Modernize configuration of SiStripDetVOffReader and add SiStripApvGainReader `db`  created: 2017-03-18 10:09:12 merged: 2017-03-22 06:54:17

22. [17976](http://github.com/cms-sw/cmssw/pull/17976){:target="_blank"}  from **@deguio**: removed HCAL DQM from the offline sequences `dqm`  created: 2017-03-17 20:33:22 merged: 2017-03-18 19:27:22

23. [17975](http://github.com/cms-sw/cmssw/pull/17975){:target="_blank"}  from **@arunhep**: 2017 and 2018 GTs updated with HCAL LUTs Bug fix and Resp Corr Update for Plan1 `alca`  created: 2017-03-17 20:03:42 merged: 2017-03-20 09:23:08

24. [17972](http://github.com/cms-sw/cmssw/pull/17972){:target="_blank"}  from **@gartung**: SimCalorimetry/EcalEBTrigPrimAlgos : Comment out unused variables to remove gcc warning. `l1`  `upgrade`  created: 2017-03-17 16:22:28 merged: 2017-03-22 09:08:15

25. [17966](http://github.com/cms-sw/cmssw/pull/17966){:target="_blank"}  from **@pietverwilligen**: from 768 to 512 strips for ME0 geometry `geometry`  `upgrade`  created: 2017-03-17 14:13:00 merged: 2017-03-20 20:32:12

26. [17962](http://github.com/cms-sw/cmssw/pull/17962){:target="_blank"}  from **@gartung**: IOMC/RandomEngine/test fix bug in initialization of sleep timer. `core`  created: 2017-03-16 19:55:07 merged: 2017-03-18 19:28:08

27. [17961](http://github.com/cms-sw/cmssw/pull/17961){:target="_blank"}  from **@gartung**: CalibCalorimetry/HcalPlugins fix bug found from clang warning `alca`  created: 2017-03-16 19:29:31 merged: 2017-03-21 17:22:44

28. [17960](http://github.com/cms-sw/cmssw/pull/17960){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-TB24 Fix the crash with TB170 geometry `geometry`  `upgrade`  created: 2017-03-16 15:49:21 merged: 2017-03-17 17:16:04

29. [17955](http://github.com/cms-sw/cmssw/pull/17955){:target="_blank"}  from **@shervin86**: removed assert `alca`  created: 2017-03-16 10:56:28 merged: 2017-03-20 20:32:27

30. [17953](http://github.com/cms-sw/cmssw/pull/17953){:target="_blank"}  from **@matz-e**: Fix HCAL trigger mode in 2018 geometry `geometry`  created: 2017-03-16 08:38:48 merged: 2017-03-16 18:19:06

31. [17951](http://github.com/cms-sw/cmssw/pull/17951){:target="_blank"}  from **@cms-tsg-storm**: Bugfix and clean-up of frozen HLT menus (91X) `hlt`  created: 2017-03-16 08:11:05 merged: 2017-03-16 17:20:11

32. [17950](http://github.com/cms-sw/cmssw/pull/17950){:target="_blank"}  from **@wddgit**: Fix BranchChildren/Parentage problems that occur with SubProcess and EDAlias `core`  created: 2017-03-15 22:04:14 merged: 2017-03-20 20:32:42

33. [17948](http://github.com/cms-sw/cmssw/pull/17948){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx117 Make right treatment of neutral filter `geometry`  `simulation`  created: 2017-03-15 21:54:45 merged: 2017-03-18 19:28:54

34. [17946](http://github.com/cms-sw/cmssw/pull/17946){:target="_blank"}  from **@Dr15Jones**: Use tbb::spawn instead of tbb::enqueue for stream 0 begin transitions `core`  created: 2017-03-15 19:05:22 merged: 2017-03-16 07:25:55

35. [17945](http://github.com/cms-sw/cmssw/pull/17945){:target="_blank"}  from **@Dr15Jones**: Do not reset info for the stack trace helper `core`  created: 2017-03-15 16:36:38 merged: 2017-03-16 07:25:45

36. [17944](http://github.com/cms-sw/cmssw/pull/17944){:target="_blank"}  from **@ianna**: 2023 Scenario and Workflow with Detailed Cavern `geometry`  `operations`  `pdmv`  `simulation`  `upgrade`  created: 2017-03-15 14:09:37 merged: 2017-03-17 17:07:09

37. [17939](http://github.com/cms-sw/cmssw/pull/17939){:target="_blank"}  from **@fioriNTU**: OnlineClients `dqm`  created: 2017-03-15 08:04:54 merged: 2017-03-16 11:54:07

38. [17937](http://github.com/cms-sw/cmssw/pull/17937){:target="_blank"}  from **@Dr15Jones**: Fix comparisons used for unit tests `core`  created: 2017-03-14 19:23:36 merged: 2017-03-15 08:26:40

39. [17936](http://github.com/cms-sw/cmssw/pull/17936){:target="_blank"}  from **@franzoni**: fix for ECAL selective readout `alca`  created: 2017-03-14 18:22:21 merged: 2017-03-16 07:25:36

40. [17935](http://github.com/cms-sw/cmssw/pull/17935){:target="_blank"}  from **@ianna**: Remove Beam-pipe from CTPPS Configuration `geometry`  created: 2017-03-14 18:19:08 merged: 2017-03-15 08:27:55

41. [17932](http://github.com/cms-sw/cmssw/pull/17932){:target="_blank"}  from **@ndaci**: Fix the access to PU info in HLT Ntuples (91X, master branch) `hlt`  created: 2017-03-14 17:33:32 merged: 2017-03-15 08:25:38

42. [17925](http://github.com/cms-sw/cmssw/pull/17925){:target="_blank"}  from **@folguera**: Muon HLT for IterL3: porting to new seeding  `hlt`  `reconstruction`  created: 2017-03-14 15:45:16 merged: 2017-03-16 17:21:49

43. [17918](http://github.com/cms-sw/cmssw/pull/17918){:target="_blank"}  from **@makortel**: Add CA hit ntuplets for early deletion `reconstruction`  created: 2017-03-14 13:28:50 merged: 2017-03-16 17:22:04

44. [17917](http://github.com/cms-sw/cmssw/pull/17917){:target="_blank"}  from **@folguera**: Muon HLT - fix in TSGForOI `reconstruction`  created: 2017-03-14 12:29:05 merged: 2017-03-17 17:24:14

45. [17916](http://github.com/cms-sw/cmssw/pull/17916){:target="_blank"}  from **@fioriNTU**: removing double call to the RAW data plugin `dqm`  created: 2017-03-14 11:11:38 merged: 2017-03-15 15:13:30

46. [17915](http://github.com/cms-sw/cmssw/pull/17915){:target="_blank"}  from **@cms-sw**: Revert "Revert "Update 2017 Beam-pipe Middle Section"" `geometry`  `upgrade`  created: 2017-03-14 11:06:30 merged: 2017-03-14 14:17:48

47. [17914](http://github.com/cms-sw/cmssw/pull/17914){:target="_blank"}  from **@ianna**: Update All Locations of Phase 1 Beampipe `geometry`  `upgrade`  created: 2017-03-14 10:52:36 merged: 2017-03-14 14:17:15

48. [17913](http://github.com/cms-sw/cmssw/pull/17913){:target="_blank"}  from **@cms-sw**: Revert "Update 2017 Beam-pipe Middle Section" `comparison`  `geometry`  `upgrade`  created: 2017-03-14 09:57:37 merged: 2017-03-14 09:57:43

49. [17912](http://github.com/cms-sw/cmssw/pull/17912){:target="_blank"}  from **@Dr15Jones**: Report # events per Lumi for output files in framework job report `core`  created: 2017-03-13 20:21:41 merged: 2017-03-14 08:29:10

50. [17906](http://github.com/cms-sw/cmssw/pull/17906){:target="_blank"}  from **@cms-tsg-storm**: Cleanup of HLT customization files moved into ConfDB menus (91X) `hlt`  created: 2017-03-13 15:19:56 merged: 2017-03-14 12:29:30

51. [17905](http://github.com/cms-sw/cmssw/pull/17905){:target="_blank"}  from **@franzoni**: fix GEM geometry - HCAL emap - HCAL resoCorr HEP17 - SiStrip bad channels [91x version] `alca`  created: 2017-03-13 14:29:25 merged: 2017-03-14 14:18:47

52. [17903](http://github.com/cms-sw/cmssw/pull/17903){:target="_blank"}  from **@makortel**: Add README for adding/reordering iterations `reconstruction`  created: 2017-03-13 12:43:05 merged: 2017-03-14 08:29:21

53. [17901](http://github.com/cms-sw/cmssw/pull/17901){:target="_blank"}  from **@fabozzi**: Migration of workflow injection to Unified `pdmv`  `upgrade`  created: 2017-03-13 11:46:55 merged: 2017-03-14 12:28:53

54. [17895](http://github.com/cms-sw/cmssw/pull/17895){:target="_blank"}  from **@christopheralanwest**: Fix eta range for HCAL LUT metadata `alca`  created: 2017-03-12 15:46:26 merged: 2017-03-15 08:23:02

55. [17891](http://github.com/cms-sw/cmssw/pull/17891){:target="_blank"}  from **@VinInn**: New cluster shape filter for phase2 + adding PixelPair `reconstruction`  `upgrade`  created: 2017-03-11 13:33:59 merged: 2017-03-16 19:46:46

56. [17889](http://github.com/cms-sw/cmssw/pull/17889){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-gem24 Fix the issue of GE21 with staggered gap `geometry`  `upgrade`  created: 2017-03-10 23:03:24 merged: 2017-03-18 19:29:15

57. [17888](http://github.com/cms-sw/cmssw/pull/17888){:target="_blank"}  from **@pmillet**: Bugfix for MakeSherpaLibs and update of example cards `generators`  created: 2017-03-10 16:31:47 merged: 2017-03-12 18:42:10

58. [17880](http://github.com/cms-sw/cmssw/pull/17880){:target="_blank"}  from **@leggat**: Pixel Phase 1 summary maps `dqm`  created: 2017-03-10 14:55:22 merged: 2017-03-16 17:53:36

59. [17879](http://github.com/cms-sw/cmssw/pull/17879){:target="_blank"}  from **@ggovi**: Added RunInfo quick access in Condition DB `alca`  `db`  created: 2017-03-10 14:54:06 merged: 2017-03-21 16:53:36

60. [17877](http://github.com/cms-sw/cmssw/pull/17877){:target="_blank"}  from **@bendavid**: Minor improvements to Multifit handling of max sample fallback (91x) `reconstruction`  created: 2017-03-10 13:52:47 merged: 2017-03-18 19:29:44

61. [17874](http://github.com/cms-sw/cmssw/pull/17874){:target="_blank"}  from **@smuzaffar**: updated/bug fix duplicateReflexLibrarySearch.py  `core`  created: 2017-03-10 10:06:34 merged: 2017-03-10 18:20:11

62. [17873](http://github.com/cms-sw/cmssw/pull/17873){:target="_blank"}  from **@fabozzi**: update 2017 wf in IB: replace TenMuE with ZMM (91X) `pdmv`  `upgrade`  created: 2017-03-10 09:36:20 merged: 2017-03-10 12:05:59

63. [17872](http://github.com/cms-sw/cmssw/pull/17872){:target="_blank"}  from **@fwyzard**: Set HCAL method 3 respons to 1.0 for data and MC. `hlt`  `reconstruction`  created: 2017-03-09 22:31:47 merged: 2017-03-14 08:29:35

64. [17870](http://github.com/cms-sw/cmssw/pull/17870){:target="_blank"}  from **@Dr15Jones**: Fixed a clang warning in View.cc `core`  created: 2017-03-09 21:42:30 merged: 2017-03-10 07:52:06

65. [17869](http://github.com/cms-sw/cmssw/pull/17869){:target="_blank"}  from **@grasph**: MatacqProduce: added support for multiple matacq files per run `alca`  `reconstruction`  created: 2017-03-09 21:16:12 merged: 2017-03-21 08:37:07

66. [17865](http://github.com/cms-sw/cmssw/pull/17865){:target="_blank"}  from **@enochnotsocool**: Sistrip cluster gain/raw cluster charge update - 91X `dqm`  created: 2017-03-09 20:40:02 merged: 2017-03-15 08:16:48

67. [17864](http://github.com/cms-sw/cmssw/pull/17864){:target="_blank"}  from **@Dr15Jones**: Fix memory leaks associated with Muon Digi histogramming `dqm`  `simulation`  created: 2017-03-09 20:37:15 merged: 2017-03-11 07:06:18

68. [17863](http://github.com/cms-sw/cmssw/pull/17863){:target="_blank"}  from **@Dr15Jones**: Use std::unique_ptr to manage memory in PileupJetIdProducer `reconstruction`  created: 2017-03-09 19:26:12 merged: 2017-03-16 07:19:36

69. [17861](http://github.com/cms-sw/cmssw/pull/17861){:target="_blank"}  from **@Dr15Jones**: Fix memory leak in BasicHepMCValidation `dqm`  `generators`  created: 2017-03-09 17:19:32 merged: 2017-03-14 14:21:58

70. [17855](http://github.com/cms-sw/cmssw/pull/17855){:target="_blank"}  from **@boudoul**: Cleaning  pixel certification to prevent crash at Tier0 `dqm`  created: 2017-03-09 14:57:24 merged: 2017-03-10 07:52:31

71. [17854](http://github.com/cms-sw/cmssw/pull/17854){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca75 Changes in view of Plan1 and 2017 running `alca`  created: 2017-03-09 14:48:41 merged: 2017-03-21 16:51:06

72. [17852](http://github.com/cms-sw/cmssw/pull/17852){:target="_blank"}  from **@cms-tsg-storm**: Update HLT STORM validation to Phase1 (91X) `core`  `hlt`  `pdmv`  `upgrade`  created: 2017-03-09 12:49:29 merged: 2017-03-11 07:06:46

73. [17851](http://github.com/cms-sw/cmssw/pull/17851){:target="_blank"}  from **@ggovi**: Various fixes: conddb core, conddb tools, runinfo o2o `db`  created: 2017-03-09 11:32:35 merged: 2017-03-09 19:45:35

74. [17844](http://github.com/cms-sw/cmssw/pull/17844){:target="_blank"}  from **@ianna**: Restructure XML Data Directories by Year and Version Step 2 `geometry`  `upgrade`  created: 2017-03-09 10:14:40 merged: 2017-03-13 09:05:18

75. [17837](http://github.com/cms-sw/cmssw/pull/17837){:target="_blank"}  from **@Dr15Jones**: Added ModuloEventIDFilter and ModuloStreamIDFilter `core`  created: 2017-03-08 21:58:53 merged: 2017-03-09 08:43:00

76. [17833](http://github.com/cms-sw/cmssw/pull/17833){:target="_blank"}  from **@civanch**: Extention of neutron background simulation `simulation`  created: 2017-03-08 17:41:53 merged: 2017-03-10 08:10:38

77. [17831](http://github.com/cms-sw/cmssw/pull/17831){:target="_blank"}  from **@ianna**: Restructure XML Data Directories by Year and Version `geometry`  `upgrade`  created: 2017-03-08 17:08:54 merged: 2017-03-10 12:10:54

78. [17828](http://github.com/cms-sw/cmssw/pull/17828){:target="_blank"}  from **@boudoul**: Setting up properly peak and deco (strip tracker config) 2017 cosmic WFs  `pdmv`  `upgrade`  created: 2017-03-08 16:47:21 merged: 2017-03-17 17:41:41

79. [17825](http://github.com/cms-sw/cmssw/pull/17825){:target="_blank"}  from **@rekovic**: pr91x Configure TTStubAlgorithm from L1TrackTrigger sequence for TiltedTracker  `geometry`  `operations`  created: 2017-03-08 13:50:39 merged: 2017-03-09 08:46:16

80. [17823](http://github.com/cms-sw/cmssw/pull/17823){:target="_blank"}  from **@davidlange6**: revert change to CaloCluster in warning cleanup `comparison`  `reconstruction`  created: 2017-03-08 09:41:52 merged: 2017-03-08 09:42:20

81. [17821](http://github.com/cms-sw/cmssw/pull/17821){:target="_blank"}  from **@mariadalfonso**: HBHE M2 = fix Memory Leak `reconstruction`  created: 2017-03-08 09:02:48 merged: 2017-03-10 14:33:07

82. [17820](http://github.com/cms-sw/cmssw/pull/17820){:target="_blank"}  from **@fcouderc**: Update tag&probe package for egm [91X PR] `analysis`  `reconstruction`  created: 2017-03-08 08:40:59 merged: 2017-03-11 06:52:30

83. [17818](http://github.com/cms-sw/cmssw/pull/17818){:target="_blank"}  from **@EsmaeelEskandari**: L1T legacy app is turned off and L1T2016 is renamed to L1T `dqm`  created: 2017-03-08 08:26:54 merged: 2017-03-16 19:46:22

84. [17813](http://github.com/cms-sw/cmssw/pull/17813){:target="_blank"}  from **@Dr15Jones**: Converted BaseEvtVtxGenerator to stream module `generators`  `simulation`  created: 2017-03-07 22:04:39 merged: 2017-03-14 17:38:29

85. [17812](http://github.com/cms-sw/cmssw/pull/17812){:target="_blank"}  from **@aperloff**: Bin lookup in the JetCorrectorParameters class `analysis`  `db`  created: 2017-03-07 20:57:00 merged: 2017-03-22 06:59:40

86. [17808](http://github.com/cms-sw/cmssw/pull/17808){:target="_blank"}  from **@Dr15Jones**: Make GenParticleProducer a global module `analysis`  created: 2017-03-07 16:53:19 merged: 2017-03-17 08:21:09

87. [17807](http://github.com/cms-sw/cmssw/pull/17807){:target="_blank"}  from **@gpetruc**: customizeHitRecoveryInGluedDetTkSeedsOnly `reconstruction`  created: 2017-03-07 16:44:56 merged: 2017-03-16 07:23:51

88. [17806](http://github.com/cms-sw/cmssw/pull/17806){:target="_blank"}  from **@ianna**: Update 2017 Beam-pipe Middle Section `geometry`  `upgrade`  created: 2017-03-07 15:00:52 merged: 2017-03-13 14:28:06

89. [17804](http://github.com/cms-sw/cmssw/pull/17804){:target="_blank"}  from **@kandrosov**: Code for ClusterShapeHitFilter calibration `reconstruction`  created: 2017-03-07 07:28:04 merged: 2017-03-18 19:31:06

90. [17803](http://github.com/cms-sw/cmssw/pull/17803){:target="_blank"}  from **@igv4321**: Proper memory cleanup `reconstruction`  created: 2017-03-07 00:53:53 merged: 2017-03-14 08:29:55

91. [17801](http://github.com/cms-sw/cmssw/pull/17801){:target="_blank"}  from **@wddgit**: Initial Implementation of Tasks in CMS Configurations  `analysis`  `core`  `dqm`  `hlt`  `operations`  `reconstruction`  created: 2017-03-06 18:55:39 merged: 2017-03-21 19:44:29

92. [17800](http://github.com/cms-sw/cmssw/pull/17800){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-sim04 Adding a dumping analyzer to diagnose if o/p is created using TestNumbering or not for HCAL `simulation`  created: 2017-03-06 17:45:57 merged: 2017-03-09 08:44:16

93. [17798](http://github.com/cms-sw/cmssw/pull/17798){:target="_blank"}  from **@smuzaffar**: Regenerate DQMServices/Core/src/ROOTFilePB.pb files for ptotocol buffer 3.2.0 `dqm`  created: 2017-03-06 16:27:50 merged: 2017-03-06 20:31:00

94. [17796](http://github.com/cms-sw/cmssw/pull/17796){:target="_blank"}  from **@cms-tsg-storm**: Bug fixes and adding a Fake2 HLT menu (91X) `hlt`  created: 2017-03-06 15:22:06 merged: 2017-03-07 15:56:58

95. [17792](http://github.com/cms-sw/cmssw/pull/17792){:target="_blank"}  from **@makortel**: Improve TrackingNtuple, add optional SeedStopReason to CkfTrackCandidateMaker `alca`  `dqm`  `hlt`  `reconstruction`  created: 2017-03-06 14:09:06 merged: 2017-03-20 20:33:24

96. [17789](http://github.com/cms-sw/cmssw/pull/17789){:target="_blank"}  from **@matz-e**: Fix HCAL TP compression LUTs by populating plan 1 TP list first `alca`  `l1`  created: 2017-03-06 12:51:40 merged: 2017-03-13 09:05:55

97. [17788](http://github.com/cms-sw/cmssw/pull/17788){:target="_blank"}  from **@makortel**: Fix MultiTrackValidator sim dxy/dz wrt. PV histograms `dqm`  `reconstruction`  `simulation`  created: 2017-03-06 10:46:06 merged: 2017-03-07 20:49:41

98. [17787](http://github.com/cms-sw/cmssw/pull/17787){:target="_blank"}  from **@makortel**: Add differential pulls, and resolutions+pulls for PV to vertex validation `dqm`  created: 2017-03-06 09:54:54 merged: 2017-03-07 15:57:17

99. [17782](http://github.com/cms-sw/cmssw/pull/17782){:target="_blank"}  from **@kpedro88**: include hcalRecAlgos ES producer in cosmic workflow `reconstruction`  created: 2017-03-05 22:48:32 merged: 2017-03-06 19:49:37

100. [17778](http://github.com/cms-sw/cmssw/pull/17778){:target="_blank"}  from **@Dr15Jones**: Speed up the use of DDFilteredViews `alca`  `dqm`  `geometry`  `simulation`  `upgrade`  created: 2017-03-05 19:25:28 merged: 2017-03-10 07:52:52

101. [17777](http://github.com/cms-sw/cmssw/pull/17777){:target="_blank"}  from **@igv4321**: Ignoring calibration channels in the dataframes `reconstruction`  created: 2017-03-05 17:01:06 merged: 2017-03-07 21:21:32

102. [17773](http://github.com/cms-sw/cmssw/pull/17773){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx115 Correct the issue of ieta=29 for higher depths in the Phase1 mode `geometry`  created: 2017-03-03 22:09:07 merged: 2017-03-07 08:34:22

103. [17772](http://github.com/cms-sw/cmssw/pull/17772){:target="_blank"}  from **@slava77**: Revert "narrower anode time window switched to True" (91X fwd port of #17741) `reconstruction`  created: 2017-03-03 19:02:19 merged: 2017-03-05 16:19:23

104. [17771](http://github.com/cms-sw/cmssw/pull/17771){:target="_blank"}  from **@makortel**: Make track algo priority order dynamic `dqm`  `fastsim`  `hlt`  `reconstruction`  created: 2017-03-03 17:56:54 merged: 2017-03-11 06:46:30

105. [17767](http://github.com/cms-sw/cmssw/pull/17767){:target="_blank"}  from **@cms-tau-pog**: Switching off reconstruction of so called "NullTaus" `reconstruction`  created: 2017-03-03 14:06:28 merged: 2017-03-13 09:06:30

106. [17766](http://github.com/cms-sw/cmssw/pull/17766){:target="_blank"}  from **@makortel**: Switch phase1 tracking to use CA seeding by default `operations`  `pdmv`  `reconstruction`  `upgrade`  created: 2017-03-03 13:33:44 merged: 2017-03-14 08:30:21

107. [17765](http://github.com/cms-sw/cmssw/pull/17765){:target="_blank"}  from **@mmusich**: [91X] fix spurious tickmark gain change warnings in SiStripChannelGain calibration `alca`  created: 2017-03-03 12:55:52 merged: 2017-03-07 15:57:53

108. [17761](http://github.com/cms-sw/cmssw/pull/17761){:target="_blank"}  from **@enochnotsocool**: SiPixelPhase1 - Filter update `dqm`  created: 2017-03-03 10:39:35 merged: 2017-03-07 16:01:07

109. [17758](http://github.com/cms-sw/cmssw/pull/17758){:target="_blank"}  from **@slava77**: increase cosmics MC step1 nevents `pdmv`  `upgrade`  created: 2017-03-02 22:15:21 merged: 2017-03-07 08:13:36

110. [17755](http://github.com/cms-sw/cmssw/pull/17755){:target="_blank"}  from **@jshlee**: fix rotation in me0geometry `geometry`  `upgrade`  created: 2017-03-02 16:31:49 merged: 2017-03-07 21:00:12

111. [17752](http://github.com/cms-sw/cmssw/pull/17752){:target="_blank"}  from **@wddgit**: Fix parentage provenance in corner case `core`  created: 2017-03-02 15:26:53 merged: 2017-03-07 08:12:20

112. [17751](http://github.com/cms-sw/cmssw/pull/17751){:target="_blank"}  from **@kpedro88**: fix sequences for HE plan1 `operations`  `reconstruction`  created: 2017-03-02 15:25:09 merged: 2017-03-03 20:20:33

113. [17749](http://github.com/cms-sw/cmssw/pull/17749){:target="_blank"}  from **@Dr15Jones**: Begin stream transitions use multiple tbb tasks `core`  `fastsim`  created: 2017-03-02 14:45:17 merged: 2017-03-07 16:01:29

114. [17748](http://github.com/cms-sw/cmssw/pull/17748){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca74 Make IsoTrack AlCaReco as well as tree makers to be equally useful for all possible isolation strategy `alca`  created: 2017-03-02 14:43:49 merged: 2017-03-02 14:57:45

115. [17747](http://github.com/cms-sw/cmssw/pull/17747){:target="_blank"}  from **@fwyzard**: implement "plan 1" and sum SiPM rechits over all depths `comparison`  `hlt`  created: 2017-03-02 14:43:31 merged: 2017-03-02 14:58:02

116. [17746](http://github.com/cms-sw/cmssw/pull/17746){:target="_blank"}  from **@usarica**: Cumulative updates to HipPy scripting, TwoBodyDecay, Alignment/OfflineValidation and MuonAnalysis/MuscleFit macros created: 2017-03-02 14:43:14 merged: 2017-03-02 14:59:49

117. [17745](http://github.com/cms-sw/cmssw/pull/17745){:target="_blank"}  from **@makortel**: Add IfLogDebug and IfLogTrace to MessageLogger.h `core`  `reconstruction`  created: 2017-03-02 14:06:45 merged: 2017-03-05 16:21:13

118. [17744](http://github.com/cms-sw/cmssw/pull/17744){:target="_blank"}  from **@makortel**: Remove TrackerSeedValidator as obsolete `dqm`  `fastsim`  created: 2017-03-02 13:53:31 merged: 2017-03-05 16:26:10

119. [17743](http://github.com/cms-sw/cmssw/pull/17743){:target="_blank"}  from **@civanch**: Some cleanup for SIM `comparison`  `simulation`  created: 2017-03-02 13:52:43 merged: 2017-03-02 14:58:23

120. [17740](http://github.com/cms-sw/cmssw/pull/17740){:target="_blank"}  from **@sviret**: Porting the TTTrack classes in 81X `l1`  `simulation`  `upgrade`  created: 2017-03-02 12:39:24 merged: 2017-03-08 11:02:49

121. [17734](http://github.com/cms-sw/cmssw/pull/17734){:target="_blank"}  from **@kreczko**: [90X] Offline DQM modules for L1Trigger (stage2 calo layer2) `dqm`  `l1`  created: 2017-03-02 12:37:43 merged: 2017-03-15 09:57:13

122. [17724](http://github.com/cms-sw/cmssw/pull/17724){:target="_blank"}  from **@ghellwig**: [90X] Allow multi-IOV input for Millepede alignment framework `alca`  created: 2017-03-02 12:34:56 merged: 2017-03-08 10:45:22

123. [17723](http://github.com/cms-sw/cmssw/pull/17723){:target="_blank"}  from **@abbiendi**: Improved muon track validation (new code + customization) `dqm`  `simulation`  created: 2017-03-02 12:34:40 merged: 2017-03-16 07:32:07

124. [17718](http://github.com/cms-sw/cmssw/pull/17718){:target="_blank"}  from **@dmitrijus**: Make MonitorElement to emit LogWarning instead of writing to std::cout `dqm`  created: 2017-03-02 12:33:18 merged: 2017-03-07 16:01:48

125. [17717](http://github.com/cms-sw/cmssw/pull/17717){:target="_blank"}  from **@davidlt**: Resolve segfault in MuonGEMHitsHarvestor::dqmEndJob `dqm`  created: 2017-03-02 12:33:07 merged: 2017-03-03 12:44:21

126. [17716](http://github.com/cms-sw/cmssw/pull/17716){:target="_blank"}  from **@ianna**: Extended 2017 Plan1 Scenario Scripts `db`  created: 2017-03-02 12:33:01 merged: 2017-03-11 06:54:40

127. [17715](http://github.com/cms-sw/cmssw/pull/17715){:target="_blank"}  from **@knoepfel**: Convert ObjectViewCleaner from legacy producer to stream producer `dqm`  created: 2017-03-02 12:32:45 merged: 2017-03-07 16:01:58

128. [17713](http://github.com/cms-sw/cmssw/pull/17713){:target="_blank"}  from **@lgray**: Fix numerical precision issue in 2D vertexing and wrong normalization. `reconstruction`  `upgrade`  created: 2017-03-02 12:32:10 merged: 2017-03-08 23:22:16

129. [17710](http://github.com/cms-sw/cmssw/pull/17710){:target="_blank"}  from **@cms-btv-pog**: Reject 0 pt Puppi candidates in jet-track association `reconstruction`  created: 2017-03-02 12:31:21 merged: 2017-03-05 16:21:21

130. [17709](http://github.com/cms-sw/cmssw/pull/17709){:target="_blank"}  from **@rekovic**: pr90x Add stage2L1Trigger to Era_Phase2C2. `l1`  `operations`  `pdmv`  `upgrade`  created: 2017-03-02 12:31:04 merged: 2017-03-11 06:45:53

131. [17708](http://github.com/cms-sw/cmssw/pull/17708){:target="_blank"}  from **@davidlange6**: Fix some of the gcc620 warnings including possibly important changes to CondTools/Ecal and RecoJets/JetAlgorithms `alca`  `analysis`  `db`  `dqm`  `l1`  `reconstruction`  created: 2017-03-02 12:30:48 merged: 2017-03-07 21:25:11

132. [17705](http://github.com/cms-sw/cmssw/pull/17705){:target="_blank"}  from **@aspiezia**: residual plots for DQM `dqm`  created: 2017-03-02 12:29:57 merged: 2017-03-17 08:20:27

133. [17704](http://github.com/cms-sw/cmssw/pull/17704){:target="_blank"}  from **@nfilipov**: Pcc 90 x `reconstruction`  created: 2017-03-02 12:29:40 merged: 2017-03-05 16:22:23

134. [17703](http://github.com/cms-sw/cmssw/pull/17703){:target="_blank"}  from **@jshlee**: Pfmuon fix 90x `reconstruction`  `upgrade`  created: 2017-03-02 12:29:24 merged: 2017-03-22 06:57:33

recover PF muon efficiency in workflows with HGCAL



135. [17702](http://github.com/cms-sw/cmssw/pull/17702){:target="_blank"}  from **@arunhep**: GT updates for 900pre5 with Summer16 JECs, GEM reco geometry and ESEE Intercalib `alca`  created: 2017-03-02 12:29:07 merged: 2017-03-07 16:26:16

136. [17701](http://github.com/cms-sw/cmssw/pull/17701){:target="_blank"}  from **@CTPPS**: CTPPS: miniAOD (second resubmission) `analysis`  `dqm`  `reconstruction`  created: 2017-03-02 12:28:51 merged: 2017-03-05 16:25:09

137. [17700](http://github.com/cms-sw/cmssw/pull/17700){:target="_blank"}  from **@cms-btv-pog**: Update to input collection tokens in PATJetProducer `analysis`  `reconstruction`  created: 2017-03-02 12:28:34 merged: 2017-03-09 08:51:52

138. [17699](http://github.com/cms-sw/cmssw/pull/17699){:target="_blank"}  from **@knoepfel**: Convert Validation/RecoTau modules from legacy to global producers `dqm`  created: 2017-03-02 12:28:18 merged: 2017-03-08 22:50:32

139. [17697](http://github.com/cms-sw/cmssw/pull/17697){:target="_blank"}  from **@kpedro88**: remove photoelectronsToAnalog python parameter (now taken from DB) `comparison`  `simulation`  created: 2017-03-02 12:27:45 merged: 2017-03-02 15:11:06

140. [17696](http://github.com/cms-sw/cmssw/pull/17696){:target="_blank"}  from **@dmitrijus**: Online DQM changes for MWGR#2 `dqm`  created: 2017-03-02 12:27:29 merged: 2017-03-18 19:32:10

141. [17692](http://github.com/cms-sw/cmssw/pull/17692){:target="_blank"}  from **@nancymarinelli**: Update the dataformat for the TP per crystal. It now follows what pre `l1`  `simulation`  `upgrade`  created: 2017-03-02 12:26:23 merged: 2017-03-13 09:08:03

142. [17691](http://github.com/cms-sw/cmssw/pull/17691){:target="_blank"}  from **@PFCal-dev**: HGCAL trigger sim clustering `l1`  `upgrade`  created: 2017-03-02 12:26:07 merged: 2017-03-09 13:45:49

143. [17690](http://github.com/cms-sw/cmssw/pull/17690){:target="_blank"}  from **@archiron**: nbOfDaughters_electrons_correction_Histos_90X_V2 `dqm`  created: 2017-03-02 12:25:50 merged: 2017-03-18 19:34:05

144. [17688](http://github.com/cms-sw/cmssw/pull/17688){:target="_blank"}  from **@kpedro88**: use HBHE Phase1 reco for Run2/legacy, unify M0 parameters `dqm`  `reconstruction`  `simulation`  created: 2017-03-02 12:25:16 merged: 2017-03-20 09:24:41

145. [17687](http://github.com/cms-sw/cmssw/pull/17687){:target="_blank"}  from **@nickmccoll**: CSC RU segment algorithm tuned for ME0 `reconstruction`  `upgrade`  created: 2017-03-02 12:25:00 merged: 2017-03-18 19:34:21

146. [17686](http://github.com/cms-sw/cmssw/pull/17686){:target="_blank"}  from **@davidlt**: Initialize theModMEs.ClusterGain `dqm`  created: 2017-03-02 11:34:36 merged: 2017-03-02 13:45:13

147. [17685](http://github.com/cms-sw/cmssw/pull/17685){:target="_blank"}  from **@fabozzi**: Relval updates `comparison`  `pdmv`  `upgrade`  created: 2017-03-02 11:31:54 merged: 2017-03-02 15:09:27

148. [17684](http://github.com/cms-sw/cmssw/pull/17684){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-TB23 Add the new AHCal for 2017 HGCal TB `geometry`  `simulation`  `upgrade`  created: 2017-03-02 11:27:33 merged: 2017-03-05 16:24:43

149. [17680](http://github.com/cms-sw/cmssw/pull/17680){:target="_blank"}  from **@mariadalfonso**: HBHE M2 = HPD old code cleanup `reconstruction`  created: 2017-03-02 10:55:21 merged: 2017-03-21 16:51:22

#### CMSDIST Changes between Tags REL/CMSSW_9_0_0/slc6_amd64_gcc530 and REL/CMSSW_9_1_0_pre1/slc6_amd64_gcc530:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_9_0_0/slc6_amd64_gcc530...REL/CMSSW_9_1_0_pre1/slc6_amd64_gcc530)



1. [2907](http://github.com/cms-sw/cmsdist/pull/2907){:target="_blank"}  from **@smuzaffar**: Fix scipy numpy created: 2017-03-21 11:48:17 merged: 2017-03-21 19:56:52

2. [2906](http://github.com/cms-sw/cmsdist/pull/2906){:target="_blank"}  from **@davidlange6**: remove /bin/perl from memprobe in root created: 2017-03-21 11:32:44 merged: 2017-03-21 21:16:21

3. [2900](http://github.com/cms-sw/cmsdist/pull/2900){:target="_blank"}  from **@smuzaffar**: Updated root to tip of branch v6-08-00-patches n 91X created: 2017-03-15 08:30:21 merged: 2017-03-16 10:10:02

4. [2898](http://github.com/cms-sw/cmsdist/pull/2898){:target="_blank"}  from **@vkuznet**: To avoid latency disable uniq sorting by default and made it optional created: 2017-03-14 15:15:02 merged: 2017-03-21 21:17:26

5. [2897](http://github.com/cms-sw/cmsdist/pull/2897){:target="_blank"}  from **@vkuznet**: New version of dasgoclient: fixed expired proxy and nevents in DBS output created: 2017-03-10 15:11:07 merged: 2017-03-13 14:02:31

6. [2895](http://github.com/cms-sw/cmsdist/pull/2895){:target="_blank"}  from **@cms-sw**: move to root 6.08.06 in 91X created: 2017-03-09 07:12:23 merged: 2017-03-09 21:42:41

7. [2894](http://github.com/cms-sw/cmsdist/pull/2894){:target="_blank"}  from **@cms-sw**: Update py2-tensorflow.spec created: 2017-03-08 15:00:51 merged: 2017-03-09 14:16:28

8. [2891](http://github.com/cms-sw/cmsdist/pull/2891){:target="_blank"}  from **@mkirsano**: Add professor2 created: 2017-03-07 20:13:45 merged: 2017-03-13 21:44:49

9. [2888](http://github.com/cms-sw/cmsdist/pull/2888){:target="_blank"}  from **@smuzaffar**: New standalone dasgoclient  created: 2017-03-07 14:24:03 merged: 2017-03-07 20:43:51

10. [2887](http://github.com/cms-sw/cmsdist/pull/2887){:target="_blank"}  from **@cms-sw**: Update protobuf.spec created: 2017-03-07 08:09:52 merged: 2017-03-07 15:46:09

11. [2882](http://github.com/cms-sw/cmsdist/pull/2882){:target="_blank"}  from **@davidlange6**: protobuf update created: 2017-03-06 09:17:27 merged: 2017-03-06 20:31:15

12. [2881](http://github.com/cms-sw/cmsdist/pull/2881){:target="_blank"}  from **@davidlange6**: Tqdm python package created: 2017-03-06 08:30:28 merged: 2017-03-06 10:09:57
