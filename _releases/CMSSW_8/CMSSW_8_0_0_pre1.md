---
layout: post
rel_link:  "8_0_0_pre1"
title:  "CMSSW_8_0_0_pre1"
date:   2015-11-07 10:58:18
categories: cmssw
relmajor: 8
relminor: 0
relsubminor: 0
relpre: _pre1
---

# CMSSW_8_0_0_pre1
#### Changes since CMSSW_7_6_0:

:arrow_right: Merge due to automatic forward port
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_6_0...CMSSW_8_0_0_pre1)



1. [12285](http://github.com/cms-sw/cmssw/pull/12285){:target="_blank"}  from **@Martin-Grunewald**: Check HLT menu for MT `hlt`  created: 2015-11-06 11:12:49 merged: 2015-11-07 09:07:39

2. [12280](http://github.com/cms-sw/cmssw/pull/12280){:target="_blank"}  from **@ghellwig**: Fix bug in caching of surface deformations. `alca`  `comparison`  created: 2015-11-06 10:35:33 merged: 2015-11-06 12:56:30

3. [12278](http://github.com/cms-sw/cmssw/pull/12278){:target="_blank"}  from **@davidlt**: Clean up duplicate selection rules (ROOT 6.06) `reconstruction`  `visualization`  created: 2015-11-05 22:58:22 merged: 2015-11-07 09:04:39

4. [12274](http://github.com/cms-sw/cmssw/pull/12274){:target="_blank"}  from **@osschar**: Clenup define private public in Fireworks `comparison`  `visualization`  created: 2015-11-05 16:34:17 merged: 2015-11-06 11:06:31

5. [12268](http://github.com/cms-sw/cmssw/pull/12268){:target="_blank"}  from **@cerminar**: Fix PCL workflows for HI scenario (80X) `alca`  `operations`  `pdmv`  created: 2015-11-05 13:00:51 merged: 2015-11-06 11:04:40
- :arrow_right: #12265 from **@matz-e**: Add a consume to fix DumpFedRawDataProduct from crashing. `daq` 

6. [12260](http://github.com/cms-sw/cmssw/pull/12260){:target="_blank"}  from **@ianna**: Fix Merger Issues `geometry`  created: 2015-11-04 16:52:24 merged: 2015-11-05 14:51:29

7. [12258](http://github.com/cms-sw/cmssw/pull/12258){:target="_blank"}  from **@bbockelm**: Provide a utility for efficiently copying multiple files to the local `core`  created: 2015-11-04 16:04:47 merged: 2015-11-05 14:51:34

8. [12254](http://github.com/cms-sw/cmssw/pull/12254){:target="_blank"}  from **@mark-grimes**: Add Phase1 pixel and Phase2 (2023) eras `operations`  created: 2015-11-04 11:28:49 merged: 2015-11-05 15:03:54

9. [12253](http://github.com/cms-sw/cmssw/pull/12253){:target="_blank"}  from **@smuzaffar**: fix for unit test: do not call unit test with full path `core`  created: 2015-11-04 08:21:26 merged: 2015-11-04 14:22:20

10. [12248](http://github.com/cms-sw/cmssw/pull/12248){:target="_blank"}  from **@makortel**: Switch TrackWithVertexRefSelector to ObjectSelectorStreamProducer, and remove its obsolete configuration files `analysis`  `reconstruction`  created: 2015-11-03 15:49:26 merged: 2015-11-06 11:04:58

11. [12245](http://github.com/cms-sw/cmssw/pull/12245){:target="_blank"}  from **@smorovic**: Monitoring service changes for DAQ: rebase (80X) `daq`  `reconstruction`  created: 2015-11-03 13:16:46 merged: 2015-11-05 14:51:40
- :arrow_right: #12241 from **@anorkus**: Fix in DQMIO to histogram converter script `dqm` 
- :arrow_right: #12239 from **@mverwe**: Bug fix for compatible mode in UETableProducer. (Same as #12227) `reconstruction` 

12. [12234](http://github.com/cms-sw/cmssw/pull/12234){:target="_blank"}  from **@wmtan**: Add option to print module dependencies on data `core`  created: 2015-11-02 20:57:44 merged: 2015-11-04 14:20:14

13. [12231](http://github.com/cms-sw/cmssw/pull/12231){:target="_blank"}  from **@istaslis**: Set tight mva value of HI initial step to be equal to highPurity mva value (80X version of #12223) `reconstruction`  created: 2015-11-02 15:54:09 merged: 2015-11-05 14:46:32

14. [12229](http://github.com/cms-sw/cmssw/pull/12229){:target="_blank"}  from **@smuzaffar**: missing dependency added which was dropped due to DQM/HLTEvF cleanup `dqm`  created: 2015-11-02 15:44:06 merged: 2015-11-02 19:10:31
- :arrow_right: #12228 from **@mmusich**: Minimal Change: reading tags from CondDBv2 `reconstruction` 

15. [12226](http://github.com/cms-sw/cmssw/pull/12226){:target="_blank"}  from **@makortel**: Add enum to PackedCandidate and functions to MiniFloatConverter to aid validation `analysis`  `comparison`  created: 2015-11-02 10:59:43 merged: 2015-11-07 10:49:21
- :arrow_right: #12222 from **@ginnocen**: PR for adding the cfi of HITrackClusterRemover.cc for ConfDB use in 76 (same as #12220) `reconstruction` 

16. [12217](http://github.com/cms-sw/cmssw/pull/12217){:target="_blank"}  from **@gartung**: script that determines what other libraries a library depends on  `core`  created: 2015-10-30 21:07:39 merged: 2015-11-01 05:14:51

17. [12211](http://github.com/cms-sw/cmssw/pull/12211){:target="_blank"}  from **@dmitrijus**: Static beam 80x `dqm`  created: 2015-10-30 14:27:37 merged: 2015-10-31 08:06:10

18. [12209](http://github.com/cms-sw/cmssw/pull/12209){:target="_blank"}  from **@dmitrijus**: Ramdisk 80x `dqm`  created: 2015-10-30 14:23:22 merged: 2015-11-02 10:51:56

19. [12204](http://github.com/cms-sw/cmssw/pull/12204){:target="_blank"}  from **@ericvaandering**: Do modern exceptions after conflicts resolved `alca`  `analysis`  `core`  `daq`  `db`  `docs`  `dqm`  `geometry`  `hlt`  `operations`  `pdmv`  `reconstruction`  `simulation`  created: 2015-10-30 11:20:34 merged: 2015-11-05 14:51:52

20. [12199](http://github.com/cms-sw/cmssw/pull/12199){:target="_blank"}  from **@thuer**: Initialize Sherpa only once for multiple lumi sections `generators`  created: 2015-10-30 09:32:51 merged: 2015-11-02 21:26:21

21. [12196](http://github.com/cms-sw/cmssw/pull/12196){:target="_blank"}  from **@smuzaffar**: make a fresh PR for bsunanda:Run2-hcx41 (11767 for 7_6_X) HcalTopology depends only on HcalDDDRecContants `alca`  `geometry`  `hlt`  `l1`  `simulation`  created: 2015-10-30 05:13:47 merged: 2015-11-03 17:21:58

22. [12190](http://github.com/cms-sw/cmssw/pull/12190){:target="_blank"}  from **@barvic**: 80X - Fix for handling of rare cases of CSC CFEB data corruptions with incorrect 16 samples flag reporting `reconstruction`  created: 2015-10-29 20:56:37 merged: 2015-10-31 08:11:10
- :arrow_right: #12188 from **@barvic**: 76X - Fix for handling of rare cases of CSC CFEB data corruptions with incorrect 16 samples flag reporting `reconstruction` 

23. [12181](http://github.com/cms-sw/cmssw/pull/12181){:target="_blank"}  from **@Dr15Jones**: Removed SimpleProfiler helper files `core`  created: 2015-10-29 18:52:33 merged: 2015-10-30 08:06:16

24. [12174](http://github.com/cms-sw/cmssw/pull/12174){:target="_blank"}  from **@rrabadan**: add NApv shots in text file: module with highest values `dqm`  created: 2015-10-29 16:52:03 merged: 2015-10-30 08:11:19
- :arrow_right: #12172 from **@hdelanno**: Fixing missing histograms in online for sistrip (version 76X) `dqm` 

25. [12171](http://github.com/cms-sw/cmssw/pull/12171){:target="_blank"}  from **@hdelanno**: Fixing missing histograms in online for sistrip `dqm`  created: 2015-10-29 16:32:27 merged: 2015-11-01 05:14:37

26. [12170](http://github.com/cms-sw/cmssw/pull/12170){:target="_blank"}  from **@ianna**: HGCal Reco Geometry `geometry`  created: 2015-10-29 16:21:31 merged: 2015-11-03 17:22:45

27. [12164](http://github.com/cms-sw/cmssw/pull/12164){:target="_blank"}  from **@fwyzard**: TriggerBxMonitor: monitor the BX accept of L1 and HLT triggers `dqm`  created: 2015-10-29 10:24:44 merged: 2015-11-01 05:14:21

28. [12162](http://github.com/cms-sw/cmssw/pull/12162){:target="_blank"}  from **@davidlt**: DataFormats/TrackerRecHit2D: clean Clang override warnings `reconstruction`  created: 2015-10-29 06:46:24 merged: 2015-10-30 08:11:25

29. [12160](http://github.com/cms-sw/cmssw/pull/12160){:target="_blank"}  from **@pohsun**: ADC region reduced to 100 for strip ClusterStoNCorr summaries. `dqm`  created: 2015-10-29 00:30:50 merged: 2015-10-30 08:11:31

30. [12156](http://github.com/cms-sw/cmssw/pull/12156){:target="_blank"}  from **@fwyzard**: Re-introduce the new HCAL method 3 response correction `hlt`  created: 2015-10-28 21:42:52 merged: 2015-10-29 12:41:16

31. [12149](http://github.com/cms-sw/cmssw/pull/12149){:target="_blank"}  from **@vdutta**: Correct config for pixel summary report map QTests; update tracking Q `dqm`  created: 2015-10-28 17:21:29 merged: 2015-10-29 12:41:27

32. [12148](http://github.com/cms-sw/cmssw/pull/12148){:target="_blank"}  from **@smorovic**: fillDescriptions migration and parameter cleanup in DAQ modules (80X) `daq`  `reconstruction`  created: 2015-10-28 16:26:54 merged: 2015-11-05 14:46:46

33. [12141](http://github.com/cms-sw/cmssw/pull/12141){:target="_blank"}  from **@ggovi**: Fix required by the L1T O2O. `alca`  `db`  created: 2015-10-28 14:37:43 merged: 2015-11-05 14:46:52

34. [12140](http://github.com/cms-sw/cmssw/pull/12140){:target="_blank"}  from **@jsalfeld**: new version of pileUp calculation script `db`  created: 2015-10-28 14:26:46 merged: 2015-11-07 09:06:20

35. [12134](http://github.com/cms-sw/cmssw/pull/12134){:target="_blank"}  from **@fojensen**: add vertex covariance `reconstruction`  created: 2015-10-28 05:03:09 merged: 2015-10-29 12:41:32

36. [12128](http://github.com/cms-sw/cmssw/pull/12128){:target="_blank"}  from **@Dr15Jones**: Set class version number to 2 for CastorShowerLibraryInfo `simulation`  created: 2015-10-27 18:49:36 merged: 2015-10-28 08:11:18

37. [12115](http://github.com/cms-sw/cmssw/pull/12115){:target="_blank"}  from **@davidlt**: CalibCalorimetry/EcalLaserAnalyzer: disable object I/O (ClassDef) `alca`  `comparison`  created: 2015-10-27 12:04:22 merged: 2015-10-27 14:21:24

38. [12109](http://github.com/cms-sw/cmssw/pull/12109){:target="_blank"}  from **@mmusich**: Adding label HLT for PFCalibrationRcd `alca`  created: 2015-10-27 09:53:52 merged: 2015-10-27 14:12:05

39. [12105](http://github.com/cms-sw/cmssw/pull/12105){:target="_blank"}  from **@vkhristenko**: Fixing Offline DQM Bug `dqm`  created: 2015-10-26 20:26:55 merged: 2015-10-29 12:41:42

40. [12102](http://github.com/cms-sw/cmssw/pull/12102){:target="_blank"}  from **@smuzaffar**: LXR url updated to point to cmslxr.fnal.gov `core`  created: 2015-10-26 16:44:31 merged: 2015-10-27 06:51:30

41. [12094](http://github.com/cms-sw/cmssw/pull/12094){:target="_blank"}  from **@mmusich**: Minimal Change: reading tags from CondDBv2 `reconstruction`  created: 2015-10-26 11:37:35 merged: 2015-10-30 08:16:17

42. [12092](http://github.com/cms-sw/cmssw/pull/12092){:target="_blank"}  from **@davidlt**: FWCore/Utilities: remove intrusive macros breaking libstdc++ `core`  created: 2015-10-26 07:20:14 merged: 2015-10-27 06:51:40

43. [12091](http://github.com/cms-sw/cmssw/pull/12091){:target="_blank"}  from **@davidlt**: CondFormats/Common: remove intrusive macros breaking libstdc++ `alca`  `db`  created: 2015-10-26 07:19:09 merged: 2015-11-05 20:11:31

44. [12088](http://github.com/cms-sw/cmssw/pull/12088){:target="_blank"}  from **@davidlt**: Use std::fmin instead of std::min in HcalTimeSlew::delay `alca`  created: 2015-10-25 09:38:46 merged: 2015-10-30 10:30:51

45. [12085](http://github.com/cms-sw/cmssw/pull/12085){:target="_blank"}  from **@richard-cms**: Add full5x5 shower shape block to non-GED photons producer `reconstruction`  created: 2015-10-24 20:41:06 merged: 2015-11-05 14:46:59

46. [12077](http://github.com/cms-sw/cmssw/pull/12077){:target="_blank"}  from **@gennai**: Tk alca reco producers fixes v2 cmssw 8 0 x `alca`  created: 2015-10-23 14:03:09 merged: 2015-10-25 14:16:16

47. [12066](http://github.com/cms-sw/cmssw/pull/12066){:target="_blank"}  from **@davidlange6**: Hcal det id protect again invalid IDs in digitizer `simulation`  created: 2015-10-23 09:06:07 merged: 2015-10-23 12:36:31

48. [12065](http://github.com/cms-sw/cmssw/pull/12065){:target="_blank"}  from **@hengne**: fix a typo in --era specification `pdmv`  created: 2015-10-23 08:41:41 merged: 2015-10-24 07:35:28

49. [12058](http://github.com/cms-sw/cmssw/pull/12058){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx45 Add protection to HcalTopology `geometry`  created: 2015-10-22 20:21:05 merged: 2015-10-28 08:11:28

50. [12055](http://github.com/cms-sw/cmssw/pull/12055){:target="_blank"}  from **@vandreev11**: Hgcal v7 geometry eefh corrections `geometry`  created: 2015-10-22 17:37:18 merged: 2015-10-28 08:11:33

51. [12054](http://github.com/cms-sw/cmssw/pull/12054){:target="_blank"}  from **@jbrands**: fixing bug for cut-based jet pu ID `reconstruction`  created: 2015-10-22 15:35:05 merged: 2015-10-28 08:11:39

52. [12049](http://github.com/cms-sw/cmssw/pull/12049){:target="_blank"}  from **@mandrenguyen**: Adding a vertex smearing configution for pp at 5 TeV `operations`  `simulation`  created: 2015-10-22 13:50:12 merged: 2015-10-30 08:07:29

53. [12046](http://github.com/cms-sw/cmssw/pull/12046){:target="_blank"}  from **@dinardo**: Implemented new cumulative histograms and made independent from any  `dqm`  created: 2015-10-22 10:00:17 merged: 2015-10-29 12:41:56

54. [12035](http://github.com/cms-sw/cmssw/pull/12035){:target="_blank"}  from **@Dr15Jones**: Removed LazyGetter from SiPixelClusterShapeCache `reconstruction`  created: 2015-10-21 21:14:31 merged: 2015-10-22 07:21:13

55. [12032](http://github.com/cms-sw/cmssw/pull/12032){:target="_blank"}  from **@Dr15Jones**: Set ROOT histogram fitting to be thread-safe `reconstruction`  created: 2015-10-21 19:48:27 merged: 2015-10-25 14:21:13

56. [12027](http://github.com/cms-sw/cmssw/pull/12027){:target="_blank"}  from **@lgray**: Fix failing relval missing new ECAL digi params (80X) `simulation`  created: 2015-10-21 17:29:22 merged: 2015-10-22 12:49:25

57. [12026](http://github.com/cms-sw/cmssw/pull/12026){:target="_blank"}  from **@nickmccoll**: Removed static analyzer errors from RecoLocalTracker `reconstruction`  created: 2015-10-21 16:47:26 merged: 2015-10-22 07:26:10

58. [12025](http://github.com/cms-sw/cmssw/pull/12025){:target="_blank"}  from **@mharrend**: Herwig: Add config for LO NNPDF30 `generators`  created: 2015-10-21 12:27:30 merged: 2015-11-02 21:31:28

59. [12023](http://github.com/cms-sw/cmssw/pull/12023){:target="_blank"}  from **@mark-grimes**: Add eras for 2016 and Run 1 `operations`  created: 2015-10-21 11:30:58 merged: 2015-10-26 13:25:02

60. [12017](http://github.com/cms-sw/cmssw/pull/12017){:target="_blank"}  from **@ericvaandering**: Use next() built-in `alca`  `core`  `db`  `docs`  `dqm`  `reconstruction`  created: 2015-10-21 10:07:24 merged: 2015-10-23 12:38:51

61. [12016](http://github.com/cms-sw/cmssw/pull/12016){:target="_blank"}  from **@ericvaandering**: Get rid of relative imports. `alca`  `analysis`  `core`  `reconstruction`  created: 2015-10-21 09:54:36 merged: 2015-10-29 12:40:41

62. [12012](http://github.com/cms-sw/cmssw/pull/12012){:target="_blank"}  from **@ericvaandering**: Make sure output of zip is a list (is a generator in python 3 `alca`  `analysis`  `core`  `db`  `dqm`  `pdmv`  `reconstruction`  created: 2015-10-21 09:40:02 merged: 2015-10-26 10:21:34

63. [12011](http://github.com/cms-sw/cmssw/pull/12011){:target="_blank"}  from **@ericvaandering**: types module is deprecated `core`  created: 2015-10-21 09:28:52 merged: 2015-10-22 07:26:25

64. [12009](http://github.com/cms-sw/cmssw/pull/12009){:target="_blank"}  from **@ericvaandering**: implicit tuple parameter unpacking is removed in python 3 `alca`  `core`  `db`  `docs`  created: 2015-10-21 08:57:24 merged: 2015-10-30 10:32:28

65. [12008](http://github.com/cms-sw/cmssw/pull/12008){:target="_blank"}  from **@ericvaandering**: backticks are deprecated, use repr() instead `hlt`  `l1`  created: 2015-10-21 08:42:12 merged: 2015-10-26 14:17:54

66. [12007](http://github.com/cms-sw/cmssw/pull/12007){:target="_blank"}  from **@ericvaandering**: reduce() is not a builtin in python 3 `alca`  `core`  `db`  `docs`  `dqm`  `operations`  `reconstruction`  created: 2015-10-21 08:21:15 merged: 2015-10-26 13:24:42

67. [12006](http://github.com/cms-sw/cmssw/pull/12006){:target="_blank"}  from **@ericvaandering**: apply() is deprecated since python 2.3 `alca`  `docs`  created: 2015-10-21 07:26:19 merged: 2015-10-30 10:33:17

68. [12005](http://github.com/cms-sw/cmssw/pull/12005){:target="_blank"}  from **@ericvaandering**: xreadlines is obsolete `alca`  `core`  created: 2015-10-21 05:54:52 merged: 2015-10-22 07:26:30

69. [12004](http://github.com/cms-sw/cmssw/pull/12004){:target="_blank"}  from **@ericvaandering**: Replace has_key with in for dictionaries `alca`  `analysis`  `core`  `db`  `docs`  `dqm`  `fastsim`  `hlt`  `operations`  `reconstruction`  created: 2015-10-21 05:36:30 merged: 2015-10-23 08:29:07

70. [12001](http://github.com/cms-sw/cmssw/pull/12001){:target="_blank"}  from **@wmtan**: Support multiple subprocesses `core`  created: 2015-10-20 19:38:44 merged: 2015-10-28 08:12:48

71. [11997](http://github.com/cms-sw/cmssw/pull/11997){:target="_blank"}  from **@ericvaandering**: StandardError is now Exception `alca`  `analysis`  `geometry`  `reconstruction`  created: 2015-10-20 16:14:55 merged: 2015-10-22 07:21:59

72. [11996](http://github.com/cms-sw/cmssw/pull/11996){:target="_blank"}  from **@ericvaandering**: Use new way of referring to python code `alca`  `db`  `dqm`  created: 2015-10-20 16:00:45 merged: 2015-10-26 14:14:34

73. [11994](http://github.com/cms-sw/cmssw/pull/11994){:target="_blank"}  from **@ericvaandering**: Use explicit (preferred) form for numeric literals `alca`  `core`  `db`  `dqm`  created: 2015-10-20 15:40:05 merged: 2015-10-30 10:34:15

74. [11983](http://github.com/cms-sw/cmssw/pull/11983){:target="_blank"}  from **@lgray**: Fix clang warnings in geometry classes. `geometry`  `simulation`  created: 2015-10-20 12:36:58 merged: 2015-10-21 06:11:27

75. [11971](http://github.com/cms-sw/cmssw/pull/11971){:target="_blank"}  from **@gartung**: Edm global class report `core`  created: 2015-10-19 21:10:17 merged: 2015-11-03 17:27:27

76. [11961](http://github.com/cms-sw/cmssw/pull/11961){:target="_blank"}  from **@ericvaandering**: Python3 and recent python 2 use sys.maxsize and no sys.maxint `core`  created: 2015-10-19 14:57:47 merged: 2015-10-20 11:56:32

77. [11960](http://github.com/cms-sw/cmssw/pull/11960){:target="_blank"}  from **@ericvaandering**: Use preferred form of not-equal since python 3 eliminates <> `core`  `dqm`  `reconstruction`  created: 2015-10-19 14:37:29 merged: 2015-10-23 08:30:43

78. [11944](http://github.com/cms-sw/cmssw/pull/11944){:target="_blank"}  from **@dmitrijus**:   Replace mark-and-delete at next merge algorithm in DQMStore (76x) `comparison`  `dqm`  created: 2015-10-19 08:19:19 merged: 2015-10-27 14:25:24

79. [11943](http://github.com/cms-sw/cmssw/pull/11943){:target="_blank"}  from **@heppye**: Rename Create Bd_JpsiKPi.dec to Bd_JpsiKPi.dec `generators`  created: 2015-10-19 08:19:03 merged: 2015-10-20 11:53:53

80. [11935](http://github.com/cms-sw/cmssw/pull/11935){:target="_blank"}  from **@ianna**: ME0 DB Record `db`  `geometry`  created: 2015-10-19 08:16:49 merged: 2015-10-26 13:31:33

81. [11934](http://github.com/cms-sw/cmssw/pull/11934){:target="_blank"}  from **@jrcastle**: Heavy ion common alignment producer 76 x `alca`  `dqm`  `operations`  `pdmv`  created: 2015-10-19 08:16:32 merged: 2015-11-03 20:29:19

82. [11932](http://github.com/cms-sw/cmssw/pull/11932){:target="_blank"}  from **@kurtejung**: upgrade AMPT to v2.25t5 `generators`  created: 2015-10-19 08:15:59 merged: 2015-11-02 21:36:32

83. [11931](http://github.com/cms-sw/cmssw/pull/11931){:target="_blank"}  from **@VinInn**: Tracking Reco: tuning of outlier rejection, duplicate merging, pairSeeding `alca`  `comparison`  `core`  `dqm`  `fastsim`  `reconstruction`  created: 2015-10-19 08:15:43 merged: 2015-10-19 11:24:56

84. [11930](http://github.com/cms-sw/cmssw/pull/11930){:target="_blank"}  from **@dertexaner**: HBHE isolated noise reflagger retuning for Run2 `comparison`  `reconstruction`  created: 2015-10-19 08:15:26 merged: 2015-10-19 11:25:25

85. [11924](http://github.com/cms-sw/cmssw/pull/11924){:target="_blank"}  from **@dertexaner**: Adding HBHENegativeNoise bit to HcalRecHitFlagsToBeExcluded - 76X `reconstruction`  created: 2015-10-19 08:13:47 merged: 2015-10-22 07:26:57

86. [11921](http://github.com/cms-sw/cmssw/pull/11921){:target="_blank"}  from **@cms-tau-pog**: 3prong1pi0 new dms `comparison`  `reconstruction`  created: 2015-10-19 08:12:57 merged: 2015-10-19 11:29:23

87. [11918](http://github.com/cms-sw/cmssw/pull/11918){:target="_blank"}  from **@igv4321**: Hcal simple reconstructor with method3 `reconstruction`  created: 2015-10-19 08:12:07 merged: 2015-10-21 06:11:38

88. [11916](http://github.com/cms-sw/cmssw/pull/11916){:target="_blank"}  from **@lveldere**: Fastsim: HF: use shower library also for run1 `fastsim`  `simulation`  created: 2015-10-19 08:11:34 merged: 2015-10-22 13:01:48

89. [11912](http://github.com/cms-sw/cmssw/pull/11912){:target="_blank"}  from **@dertexaner**: Switch default HBHENoiseFilter settings to Run2-25ns configuration V2 - 76X `reconstruction`  `simulation`  created: 2015-10-19 08:10:28 merged: 2015-10-20 12:01:16

90. [11899](http://github.com/cms-sw/cmssw/pull/11899){:target="_blank"}  from **@capalmer85**: PCC ntupler 76x - October2015 `reconstruction`  created: 2015-10-19 08:04:02 merged: 2015-10-22 07:27:04

91. [11896](http://github.com/cms-sw/cmssw/pull/11896){:target="_blank"}  from **@davidlt**: Fix ICC issue with 'decltype(..) a, decltype(a) b' in lambda `db`  created: 2015-10-19 08:03:57 merged: 2015-11-03 17:27:33

92. [11893](http://github.com/cms-sw/cmssw/pull/11893){:target="_blank"}  from **@davidlt**: Use rand(0) instead of ran(0) for compatibility with Intel Fortran (i `generators`  created: 2015-10-19 08:03:53 merged: 2015-10-29 12:46:08

93. [11891](http://github.com/cms-sw/cmssw/pull/11891){:target="_blank"}  from **@geonmo**: Gem sim validation porting 76 x only occupy plots `dqm`  created: 2015-10-19 07:24:36 merged: 2015-11-07 09:02:49

94. [11890](http://github.com/cms-sw/cmssw/pull/11890){:target="_blank"}  from **@cms-btv-pog**: Updated flavor parton selection for Pythia8 `analysis`  created: 2015-10-19 07:24:34 merged: 2015-11-07 09:11:28

95. [11886](http://github.com/cms-sw/cmssw/pull/11886){:target="_blank"}  from **@wmtan**: Replace LinkDef file in IORawData/HcalTBInputService `alca`  created: 2015-10-19 07:24:27 merged: 2015-11-07 09:29:33

96. [11884](http://github.com/cms-sw/cmssw/pull/11884){:target="_blank"}  from **@nhanvtran**: update to PUPPI;speedup, low PU corr `analysis`  `reconstruction`  created: 2015-10-19 07:24:24 merged: 2015-10-23 08:15:39

97. [11883](http://github.com/cms-sw/cmssw/pull/11883){:target="_blank"}  from **@wmtan**: Replace LinkDef file witl XML selection file in Calibration/HcalCalibAlgos `alca`  created: 2015-10-19 07:24:22 merged: 2015-10-31 07:01:24

98. [11882](http://github.com/cms-sw/cmssw/pull/11882){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx39 Add a scenario with PhaseI tracker, PhaseII muon for HGCAL `geometry`  created: 2015-10-19 07:24:20 merged: 2015-10-28 08:16:43

99. [11880](http://github.com/cms-sw/cmssw/pull/11880){:target="_blank"}  from **@lgray**: HGC ToT Digitization Implementation (and corresponding RECO updates) `geometry`  `reconstruction`  `simulation`  created: 2015-10-19 07:23:17 merged: 2015-11-06 11:17:06

100. [11878](http://github.com/cms-sw/cmssw/pull/11878){:target="_blank"}  from **@mengleisun**: new plots for ECAL DQM `dqm`  created: 2015-10-19 07:23:14 merged: 2015-10-29 12:46:27

101. [11875](http://github.com/cms-sw/cmssw/pull/11875){:target="_blank"}  from **@rappoccio**: Adding no-HF grid-based rho : 76x forward-port #11773 `reconstruction`  created: 2015-10-19 07:23:09 merged: 2015-10-23 08:16:39

102. [11874](http://github.com/cms-sw/cmssw/pull/11874){:target="_blank"}  from **@serval2412**: cppcheck: some fixes for 4 modules `alca`  `analysis`  `l1`  created: 2015-10-19 07:23:07 merged: 2015-10-26 14:15:42

#### CMSDIST Changes between Tags REL/CMSSW_7_6_0/slc6_amd64_gcc493 and REL/CMSSW_8_0_0_pre1/slc6_amd64_gcc493:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_6_0/slc6_amd64_gcc493...REL/CMSSW_8_0_0_pre1/slc6_amd64_gcc493)



1. [1942](http://github.com/cms-sw/cmsdist/pull/1942){:target="_blank"}  from **@degano**: Update cms-git-tools to tip of branch. created: 2015-11-05 14:06:32 merged: 2015-11-06 10:57:07

2. [1939](http://github.com/cms-sw/cmsdist/pull/1939){:target="_blank"}  from **@smuzaffar**: Updated root to tip of v6-02-00-patches created: 2015-11-05 08:54:01 merged: 2015-11-05 08:57:02

3. [1933](http://github.com/cms-sw/cmsdist/pull/1933){:target="_blank"}  from **@degano**: Update rivet and yoda 8_0_X created: 2015-10-29 15:52:04 merged: 2015-11-04 14:43:35

4. [1932](http://github.com/cms-sw/cmsdist/pull/1932){:target="_blank"}  from **@iahmad-khan**: update root.spec to use latest 6-02 branch created: 2015-10-29 15:14:35 merged: 2015-10-29 19:40:11

5. [1924](http://github.com/cms-sw/cmsdist/pull/1924){:target="_blank"}  from **@degano**: Update data for RecoBTag/SecondaryVertex. created: 2015-10-23 09:30:04 merged: 2015-10-23 09:30:11

6. [1914](http://github.com/cms-sw/cmsdist/pull/1914){:target="_blank"}  from **@davidlt**: gdb: bump version to 7.10 created: 2015-10-21 14:15:20 merged: 2015-10-21 15:09:58

7. [1907](http://github.com/cms-sw/cmsdist/pull/1907){:target="_blank"}  from **@davidlt**: gmp-static: set --host and --build to for a generic build created: 2015-10-19 06:51:23 merged: 2015-10-19 06:51:42
