---
layout: post
rel_link:  "7_6_0"
title:  "CMSSW_7_6_0"
date:   2015-10-30 15:13:18
categories: cmssw
relmajor: 7
relminor: 6
relsubminor: 0
---

# CMSSW_7_6_0
#### Changes since CMSSW_7_6_0_pre7:

<span class="glyphicon glyphicon-arrow-right"></span> Merge due to automatic forward port
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_6_0_pre7...CMSSW_7_6_0)



1. [12198](http://github.com/cms-sw/cmssw/pull/12198){:target="_blank"}  from **@davidlange6**: update to gensim recycling that matches beamspot in GT `comparison`  `pdmv`  created: 2015-10-30 08:09:20 merged: 2015-10-30 10:23:36

2. [12178](http://github.com/cms-sw/cmssw/pull/12178){:target="_blank"}  from **@muell149**: minor updates to path names and axis ranges `comparison`  `dqm`  created: 2015-10-29 17:32:42 merged: 2015-10-30 13:06:43

3. [12168](http://github.com/cms-sw/cmssw/pull/12168){:target="_blank"}  from **@diguida**: Revision of snapshotTime handling in HLT and new Run2 MC GT with ES fixes `alca`  `comparison`  `hlt`  created: 2015-10-29 13:58:22 merged: 2015-10-30 13:06:29

4. [12159](http://github.com/cms-sw/cmssw/pull/12159){:target="_blank"}  from **@pohsun**: ADC region reduced to 100 for strip ClusterStoNCorr summaries. `dqm`  created: 2015-10-29 00:25:18 merged: 2015-10-30 10:46:47

5. [12145](http://github.com/cms-sw/cmssw/pull/12145){:target="_blank"}  from **@fwyzard**: Revert the HCAL method 3 response correction `comparison`  `hlt`  created: 2015-10-28 15:59:44 merged: 2015-10-28 20:27:09

6. [12142](http://github.com/cms-sw/cmssw/pull/12142){:target="_blank"}  from **@fojensen**: add vertex covariance for V0Producer 76x `reconstruction`  created: 2015-10-28 15:00:35 merged: 2015-10-29 11:01:22

7. [12137](http://github.com/cms-sw/cmssw/pull/12137){:target="_blank"}  from **@smorovic**: Monitoring JSON changes in DAQ (76X) `daq`  `dqm`  `hlt`  `reconstruction`  created: 2015-10-28 11:45:13 merged: 2015-10-30 10:46:58

8. [12132](http://github.com/cms-sw/cmssw/pull/12132){:target="_blank"}  from **@gpetruc**: Add hcal fraction to packed candidates (76X) `analysis`  `comparison`  created: 2015-10-27 22:06:48 merged: 2015-10-30 10:26:17

9. [12122](http://github.com/cms-sw/cmssw/pull/12122){:target="_blank"}  from **@gpetruc**: MiniAOD event content updates for 76X `analysis`  created: 2015-10-27 13:51:04 merged: 2015-10-28 08:14:18

10. [12121](http://github.com/cms-sw/cmssw/pull/12121){:target="_blank"}  from **@davidlt**: CalibCalorimetry/EcalLaserAnalyzer: disable object I/O (ClassDef) `alca`  `comparison`  created: 2015-10-27 13:48:59 merged: 2015-10-28 14:46:27

11. [12118](http://github.com/cms-sw/cmssw/pull/12118){:target="_blank"}  from **@mark-grimes**: Take out the era customisations now that L1 comes from GT (76X) `l1`  created: 2015-10-27 12:28:44 merged: 2015-10-27 17:36:17

12. [12117](http://github.com/cms-sw/cmssw/pull/12117){:target="_blank"}  from **@mark-grimes**: Add eras for 2016 and Run 1 (76X) `operations`  created: 2015-10-27 12:20:26 merged: 2015-10-28 08:16:28

13. [12111](http://github.com/cms-sw/cmssw/pull/12111){:target="_blank"}  from **@lgray**: Fix VID python behavior and ignored cuts (76X) `analysis`  created: 2015-10-27 09:56:52 merged: 2015-10-28 13:16:12

14. [12106](http://github.com/cms-sw/cmssw/pull/12106){:target="_blank"}  from **@vkhristenko**: Fixing Offline DQM Bug `dqm`  created: 2015-10-26 20:29:46 merged: 2015-10-29 12:21:45

15. [12100](http://github.com/cms-sw/cmssw/pull/12100){:target="_blank"}  from **@fwyzard**: use dedicated calibrations at HLT `alca`  `hlt`  `reconstruction`  created: 2015-10-26 16:02:41 merged: 2015-10-28 20:26:08

16. [12096](http://github.com/cms-sw/cmssw/pull/12096){:target="_blank"}  from **@cms-l1t-offline**: deprecate caloparams by local config for all but HI work flows `dqm`  `l1`  created: 2015-10-26 13:45:31 merged: 2015-10-27 17:41:30

17. [12080](http://github.com/cms-sw/cmssw/pull/12080){:target="_blank"}  from **@ferencek**: Reverting the src parameter value for PAT jet partons `analysis`  created: 2015-10-23 20:32:56 merged: 2015-10-28 14:45:06

18. [12079](http://github.com/cms-sw/cmssw/pull/12079){:target="_blank"}  from **@mmusich**: New GTs for 76X: Updates for MC DR Production and other fixes `alca`  `hlt`  `operations`  `pdmv`  created: 2015-10-23 19:37:48 merged: 2015-10-25 21:14:29

19. [12078](http://github.com/cms-sw/cmssw/pull/12078){:target="_blank"}  from **@hengne**: relval scripts update after 760pre7 validation `pdmv`  created: 2015-10-23 18:18:55 merged: 2015-10-26 10:26:24

20. [12076](http://github.com/cms-sw/cmssw/pull/12076){:target="_blank"}  from **@slava77**: raise exception if MINIAOD is requested in HeavyIonsRun2 (same as #12075) `operations`  created: 2015-10-23 13:22:31 merged: 2015-10-24 07:35:06

21. [12074](http://github.com/cms-sw/cmssw/pull/12074){:target="_blank"}  from **@gennai**: Alca beam spot harvester fix v2 cmssw 7 6 x `alca`  created: 2015-10-23 11:43:20 merged: 2015-10-25 14:31:14

22. [12072](http://github.com/cms-sw/cmssw/pull/12072){:target="_blank"}  from **@vdutta**: Updates for tracker DQM plots, 76X `dqm`  created: 2015-10-23 10:31:57 merged: 2015-10-29 12:22:00

23. [12068](http://github.com/cms-sw/cmssw/pull/12068){:target="_blank"}  from **@davidlange6**: 76x version of removing invalid detids fix for fastsim pileup `simulation`  created: 2015-10-23 09:11:19 merged: 2015-10-27 17:41:39

24. [12064](http://github.com/cms-sw/cmssw/pull/12064){:target="_blank"}  from **@hengne**: fix era typo `pdmv`  created: 2015-10-23 08:36:48 merged: 2015-10-24 07:24:40

25. [12061](http://github.com/cms-sw/cmssw/pull/12061){:target="_blank"}  from **@ferencek**: Update RelVal input to CMSSW_7_6_0_pre7 `analysis`  `comparison`  created: 2015-10-23 02:05:31 merged: 2015-10-28 14:44:47

26. [12057](http://github.com/cms-sw/cmssw/pull/12057){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx44 Add protection to HcalTopology `geometry`  created: 2015-10-22 20:18:56 merged: 2015-10-27 06:55:46

27. [12053](http://github.com/cms-sw/cmssw/pull/12053){:target="_blank"}  from **@jbrands**: fixing bug for cut-based jet pu ID `reconstruction`  created: 2015-10-22 15:27:21 merged: 2015-10-28 08:21:25

28. [12044](http://github.com/cms-sw/cmssw/pull/12044){:target="_blank"}  from **@fwyzard**: add a label to indentify the PFProducer calibrations `hlt`  `reconstruction`  created: 2015-10-22 09:30:44 merged: 2015-10-23 08:21:13

29. [12041](http://github.com/cms-sw/cmssw/pull/12041){:target="_blank"}  from **@hardenbr**: EcalRechitsDigis fix save behavior to check for end of list 76X `hlt`  created: 2015-10-22 09:16:34 merged: 2015-10-23 08:26:13

30. [12040](http://github.com/cms-sw/cmssw/pull/12040){:target="_blank"}  from **@mandrenguyen**: Adding a vertex smearing configution for pp at 5 TeV, based on latest info from the LHC `comparison`  `operations`  `simulation`  created: 2015-10-22 08:29:55 merged: 2015-10-28 14:44:30

31. [12034](http://github.com/cms-sw/cmssw/pull/12034){:target="_blank"}  from **@mariadalfonso**: METfilters: fix forth bad EE supercluster `analysis`  created: 2015-10-21 21:11:12 merged: 2015-10-27 14:17:33

32. [12031](http://github.com/cms-sw/cmssw/pull/12031){:target="_blank"}  from **@Dr15Jones**: Set ROOT histogram fitting to be thread-safe `reconstruction`  created: 2015-10-21 19:43:07 merged: 2015-10-24 08:24:36

33. [12028](http://github.com/cms-sw/cmssw/pull/12028){:target="_blank"}  from **@lgray**: Fix failing relval missing new ECAL digi params (76X) `simulation`  created: 2015-10-21 17:32:07 merged: 2015-10-22 12:49:36

34. [12024](http://github.com/cms-sw/cmssw/pull/12024){:target="_blank"}  from **@nickmccoll**: Make ClusterMultiplicityFilter multithread safe `reconstruction`  created: 2015-10-21 12:00:28 merged: 2015-10-22 07:26:16

35. [12021](http://github.com/cms-sw/cmssw/pull/12021){:target="_blank"}  from **@threus**: fixed avgfedDigiOccvsLumi ME `dqm`  created: 2015-10-21 11:20:29 merged: 2015-10-29 12:22:11

36. [12020](http://github.com/cms-sw/cmssw/pull/12020){:target="_blank"}  from **@dmitrijus**: Remove unused package DQM/PhysicsHWW `dqm`  created: 2015-10-21 10:56:18 merged: 2015-10-24 07:33:18

37. [12002](http://github.com/cms-sw/cmssw/pull/12002){:target="_blank"}  from **@smdogra**: Reco changes for centralityBin in DQM `dqm`  `reconstruction`  created: 2015-10-20 20:19:54 merged: 2015-10-29 12:31:28

38. [12000](http://github.com/cms-sw/cmssw/pull/12000){:target="_blank"}  from **@wmtan**: Fix packed gen particle copy and move ctors `analysis`  created: 2015-10-20 19:10:40 merged: 2015-10-21 13:43:57

39. [11995](http://github.com/cms-sw/cmssw/pull/11995){:target="_blank"}  from **@fioriNTU**: ready to use cfg for shifters `analysis`  `comparison`  created: 2015-10-20 15:48:06 merged: 2015-10-27 14:17:55

40. [11991](http://github.com/cms-sw/cmssw/pull/11991){:target="_blank"}  from **@nickmccoll**: Removed static analyzer errors from RecoLocalTracker `reconstruction`  created: 2015-10-20 15:22:46 merged: 2015-10-22 07:26:41

41. [11987](http://github.com/cms-sw/cmssw/pull/11987){:target="_blank"}  from **@davidlt**: Double buffer size for 'name1' and 'name2' `dqm`  created: 2015-10-20 13:43:19 merged: 2015-10-28 10:22:07

42. [11981](http://github.com/cms-sw/cmssw/pull/11981){:target="_blank"}  from **@Martin-Grunewald**: Eras for TSG tests `hlt`  created: 2015-10-20 11:37:14 merged: 2015-10-20 17:21:22

43. [11980](http://github.com/cms-sw/cmssw/pull/11980){:target="_blank"}  from **@ggovi**: Introduced new synchronization types in conddb tools `db`  created: 2015-10-20 10:48:51 merged: 2015-10-26 10:26:38

44. [11976](http://github.com/cms-sw/cmssw/pull/11976){:target="_blank"}  from **@smuzaffar**: drop Alignment/CocoaAnalysis package which is sub-set of Alignment/CocoaFit `alca`  created: 2015-10-20 07:46:26 merged: 2015-10-20 17:24:23

45. [11973](http://github.com/cms-sw/cmssw/pull/11973){:target="_blank"}  from **@smuzaffar**: fix duplicateReflexLibrarySearch: look for function name too in classes_def.xml files `core`  created: 2015-10-19 22:32:59 merged: 2015-10-20 07:08:33

46. [11972](http://github.com/cms-sw/cmssw/pull/11972){:target="_blank"}  from **@rovere**: Prevent V0 sim2reco candidate to share the same TrackRef `dqm`  created: 2015-10-19 22:28:13 merged: 2015-10-20 11:56:26

47. [11969](http://github.com/cms-sw/cmssw/pull/11969){:target="_blank"}  from **@pablodecm**: Change cMVAv2 range in DQM to [-1,1] `dqm`  created: 2015-10-19 17:52:51 merged: 2015-10-22 07:26:52

48. [11967](http://github.com/cms-sw/cmssw/pull/11967){:target="_blank"}  from **@lathomas**: Typo in CSCTightHalo2015Filter `analysis`  `reconstruction`  created: 2015-10-19 17:30:06 merged: 2015-10-30 10:25:52

49. [11965](http://github.com/cms-sw/cmssw/pull/11965){:target="_blank"}  from **@Dr15Jones**: Remove last usage of edm::LazyGetter and edm::RefGetter `alca`  `core`  created: 2015-10-19 15:17:54 merged: 2015-10-21 12:58:04

50. [11963](http://github.com/cms-sw/cmssw/pull/11963){:target="_blank"}  from **@davidlange6**: Quieting 76x step2 and step3 `analysis`  `core`  `dqm`  `l1`  `pdmv`  `reconstruction`  `simulation`  created: 2015-10-19 15:17:09 merged: 2015-10-25 21:16:07

51. [11959](http://github.com/cms-sw/cmssw/pull/11959){:target="_blank"}  from **@ggovi**: Replaced synchronization types according to the new policy.  `alca`  `db`  created: 2015-10-19 13:48:45 merged: 2015-10-26 10:26:43

52. [11957](http://github.com/cms-sw/cmssw/pull/11957){:target="_blank"}  from **@davidlt**: Fireworks/Core: remove intrusive macros breaking libstdc++ `comparison`  `visualization`  created: 2015-10-19 12:51:02 merged: 2015-10-24 08:33:17

53. [11956](http://github.com/cms-sw/cmssw/pull/11956){:target="_blank"}  from **@davidlt**: MuonAnalysis/MomentumScaleCalibration: remove intrusive macros breaking libstdc++ `analysis`  created: 2015-10-19 12:28:18 merged: 2015-10-23 09:28:55

54. [11955](http://github.com/cms-sw/cmssw/pull/11955){:target="_blank"}  from **@davidlt**: PerfTools/Callgrind: remove intrusive macros breaking libstdc++ `comparison`  `core`  created: 2015-10-19 12:14:08 merged: 2015-10-19 15:37:04

55. [11954](http://github.com/cms-sw/cmssw/pull/11954){:target="_blank"}  from **@davidlt**: Remove intrusive macros breaking libstdc++ `reconstruction`  created: 2015-10-19 11:54:11 merged: 2015-10-21 10:01:55

56. [11953](http://github.com/cms-sw/cmssw/pull/11953){:target="_blank"}  from **@davidlt**: Remove intrusive macros breaking libstdc++ `reconstruction`  created: 2015-10-19 11:33:14 merged: 2015-10-21 10:02:01

57. [11951](http://github.com/cms-sw/cmssw/pull/11951){:target="_blank"}  from **@davidlt**: DataFormats/EcalDigi: remove intrusive macros breaking libstdc++ `comparison`  `core`  `simulation`  created: 2015-10-19 09:34:20 merged: 2015-10-19 15:37:22

58. [11863](http://github.com/cms-sw/cmssw/pull/11863){:target="_blank"}  from **@davidlange6**: revert back the 75x automerge for HLT config v4 `comparison`  `hlt`  created: 2015-10-18 07:59:41 merged: 2015-10-18 08:37:17

59. [11862](http://github.com/cms-sw/cmssw/pull/11862){:target="_blank"}  from **@davidlange6**: guard against era being none `comparison`  `operations`  created: 2015-10-17 10:30:16 merged: 2015-10-17 10:42:53

60. [11860](http://github.com/cms-sw/cmssw/pull/11860){:target="_blank"}  from **@davidlange6**: fix up recently introduced problems  in IB tests `comparison`  `pdmv`  `reconstruction`  created: 2015-10-17 08:13:53 merged: 2015-10-17 18:40:49

61. [11855](http://github.com/cms-sw/cmssw/pull/11855){:target="_blank"}  from **@rappoccio**: Adding no-HF grid-based rho (76x forward-port #11773), and fixing existing bugged central rho values `reconstruction`  created: 2015-10-16 17:16:01 merged: 2015-10-23 08:21:46

62. [11854](http://github.com/cms-sw/cmssw/pull/11854){:target="_blank"}  from **@makortel**: Fix TrackingVertex->TrackingParticle links in premixing `simulation`  created: 2015-10-16 14:32:03 merged: 2015-10-21 09:57:14

63. [11848](http://github.com/cms-sw/cmssw/pull/11848){:target="_blank"}  from **@davidlt**: Remove constexpr from ringOrder `reconstruction`  created: 2015-10-16 10:04:38 merged: 2015-10-19 09:56:43

64. [11847](http://github.com/cms-sw/cmssw/pull/11847){:target="_blank"}  from **@Dr15Jones**: Removed unnecessary include and forward declaration of RefGetter `hlt`  `reconstruction`  created: 2015-10-16 10:00:50 merged: 2015-10-17 18:41:19

65. [11846](http://github.com/cms-sw/cmssw/pull/11846){:target="_blank"}  from **@Dr15Jones**: Removed edm::LazyGetter<> related dictionaries `reconstruction`  created: 2015-10-16 10:00:00 merged: 2015-10-19 10:01:42

66. [11843](http://github.com/cms-sw/cmssw/pull/11843){:target="_blank"}  from **@davidlt**: DataFormats/Common: change from std::swap to edm::swap `core`  created: 2015-10-16 08:40:00 merged: 2015-10-16 19:56:15

67. [11838](http://github.com/cms-sw/cmssw/pull/11838){:target="_blank"}  from **@jhgoh**: bugfix: assign muon PDG id using PFMuon charge `reconstruction`  created: 2015-10-15 23:33:07 merged: 2015-10-19 10:01:47

68. [11835](http://github.com/cms-sw/cmssw/pull/11835){:target="_blank"}  from **@BetterWang**: EP code bug fix `reconstruction`  created: 2015-10-15 20:22:15 merged: 2015-10-19 09:57:00

69. [11833](http://github.com/cms-sw/cmssw/pull/11833){:target="_blank"}  from @bendavid: add additional shower setting (formally) needed for consistent aMC**@NL** `comparison`  `generators`  created: 2015-10-15 18:05:36 merged: 2015-10-16 05:23:21

70. [11832](http://github.com/cms-sw/cmssw/pull/11832){:target="_blank"}  from **@capalmer85**: PCC ntupler 76x - October2015 `reconstruction`  created: 2015-10-15 17:26:59 merged: 2015-10-23 08:21:52

71. [11831](http://github.com/cms-sw/cmssw/pull/11831){:target="_blank"}  from **@rovere**: Flag the globalEfficiencies plot in the DQMGenericClient `dqm`  created: 2015-10-15 16:42:05 merged: 2015-10-19 10:06:35

72. [11828](http://github.com/cms-sw/cmssw/pull/11828){:target="_blank"}  from **@hroskes**: No more cmsStage etc. scripts `alca`  `analysis`  created: 2015-10-15 16:39:32 merged: 2015-10-20 11:51:40

73. [11827](http://github.com/cms-sw/cmssw/pull/11827){:target="_blank"}  from **@Dr15Jones**: Made RefCore and RefCoreWithIndex icc compatible `core`  created: 2015-10-15 15:37:00 merged: 2015-10-16 19:56:37

74. [11825](http://github.com/cms-sw/cmssw/pull/11825){:target="_blank"}  from **@barvic**: 76X - Fix for handling of rare case of CFEB data corruption `reconstruction`  created: 2015-10-15 15:32:37 merged: 2015-10-16 13:06:36

75. [11823](http://github.com/cms-sw/cmssw/pull/11823){:target="_blank"}  from **@mark-grimes**: Fix --dump_python option in cmsDriver `comparison`  `operations`  created: 2015-10-15 15:18:10 merged: 2015-10-16 20:05:15

76. [11820](http://github.com/cms-sw/cmssw/pull/11820){:target="_blank"}  from **@sethzenz**: Prevent VirtualJetProducer from wasting time on setup if input empty `reconstruction`  created: 2015-10-15 14:48:14 merged: 2015-10-19 10:02:03

77. [11819](http://github.com/cms-sw/cmssw/pull/11819){:target="_blank"}  from **@govoni**: Update TTbar_13TeV_TuneCUETP8M1_cfi.py `comparison`  `generators`  created: 2015-10-15 14:00:59 merged: 2015-10-16 05:50:26

78. [11817](http://github.com/cms-sw/cmssw/pull/11817){:target="_blank"}  from **@mark-grimes**: Make the L1REPACK step work with the Run 2 eras `fastsim`  `l1`  `operations`  created: 2015-10-15 13:14:45 merged: 2015-10-16 06:00:29

79. [11814](http://github.com/cms-sw/cmssw/pull/11814){:target="_blank"}  from **@Dr15Jones**: removed unused SiStripMonitorMuonHLT `dqm`  created: 2015-10-15 12:52:33 merged: 2015-10-16 05:23:42

80. [11813](http://github.com/cms-sw/cmssw/pull/11813){:target="_blank"}  from **@dmitrijus**: Fix statics in CastorDigiMonitor. `dqm`  created: 2015-10-15 12:09:54 merged: 2015-10-24 07:32:05

81. [11812](http://github.com/cms-sw/cmssw/pull/11812){:target="_blank"}  from **@Dr15Jones**: Removed unused HITSiStripRawToClustersRoI `alca`  created: 2015-10-15 09:30:21 merged: 2015-10-15 12:41:15

82. [11811](http://github.com/cms-sw/cmssw/pull/11811){:target="_blank"}  from **@fabozzi**: added FEVTDEBUGHLT as output of step2 data relvals `pdmv`  created: 2015-10-15 09:20:45 merged: 2015-10-21 10:02:16

83. [11810](http://github.com/cms-sw/cmssw/pull/11810){:target="_blank"}  from **@Dr15Jones**: Removed old LazyGetter calls from HLTDummyCollections `hlt`  created: 2015-10-15 08:44:10 merged: 2015-10-15 12:51:15

84. <span class="glyphicon glyphicon-arrow-right"></span>[11807](http://github.com/cms-sw/cmssw/pull/11807){:target="_blank"}  from **@alja**: 75x Fireworks: fix MuonDigi accessor type `comparison`  `visualization`  created: 2015-10-14 22:46:54 merged: 2015-10-15 07:36:12

85. [11804](http://github.com/cms-sw/cmssw/pull/11804){:target="_blank"}  from **@mbandrews**: Fix TestPulse RMS binning and output `dqm`  created: 2015-10-14 22:25:36 merged: 2015-10-16 05:24:51

86. [11801](http://github.com/cms-sw/cmssw/pull/11801){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx42 Bug fix for HcalTopology `geometry`  created: 2015-10-14 20:03:15 merged: 2015-10-15 08:00:49

87. [11800](http://github.com/cms-sw/cmssw/pull/11800){:target="_blank"}  from **@diguida**: New Global Tags with cleanup and fixes for all scenarios. `alca`  created: 2015-10-14 19:30:23 merged: 2015-10-15 12:41:30

88. [11798](http://github.com/cms-sw/cmssw/pull/11798){:target="_blank"}  from **@vandreev11**: Fix a typo in MaterialNames, new material in HGCEE `geometry`  created: 2015-10-14 17:19:14 merged: 2015-10-19 10:02:08

89. [11790](http://github.com/cms-sw/cmssw/pull/11790){:target="_blank"}  from **@lveldere**: FastSim : muon validation : use fastsim era to define fastsim customs `dqm`  `fastsim`  `simulation`  created: 2015-10-14 14:11:33 merged: 2015-10-29 07:21:01

90. [11789](http://github.com/cms-sw/cmssw/pull/11789){:target="_blank"}  from **@dertexaner**: Switch default HBHENoiseFilter settings to Run2-25ns configuration V2 - 76X `reconstruction`  `simulation`  created: 2015-10-14 14:10:52 merged: 2015-10-23 08:21:58

91. [11788](http://github.com/cms-sw/cmssw/pull/11788){:target="_blank"}  from **@Dr15Jones**: Removed API for RefGetter and LazyGetter from EcalRegionCabling `reconstruction`  created: 2015-10-14 13:26:42 merged: 2015-10-19 10:02:14

92. [11785](http://github.com/cms-sw/cmssw/pull/11785){:target="_blank"}  from **@smuzaffar**: remove duplicate run2 2015C workflows which were auto-forward ported from 75X `comparison`  `pdmv`  created: 2015-10-14 11:25:11 merged: 2015-10-14 13:41:50

93. [11784](http://github.com/cms-sw/cmssw/pull/11784){:target="_blank"}  from **@lgray**: Add possibility for partial ECAL digitization (towards working HGCAL) `simulation`  created: 2015-10-14 10:29:42 merged: 2015-10-19 10:06:46

94. [11783](http://github.com/cms-sw/cmssw/pull/11783){:target="_blank"}  from **@lveldere**: Fastsim: HF: use shower library also for run1 `fastsim`  `simulation`  created: 2015-10-14 08:06:38 merged: 2015-10-22 13:01:54

95. [11779](http://github.com/cms-sw/cmssw/pull/11779){:target="_blank"}  from **@fwyzard**: make the behaviour of cmsRun and edmConfigDump more consistent `core`  created: 2015-10-13 23:50:04 merged: 2015-10-16 13:06:57

96. [11772](http://github.com/cms-sw/cmssw/pull/11772){:target="_blank"}  from **@wmtan**: get rid of const_cast `core`  created: 2015-10-13 17:15:12 merged: 2015-10-14 08:51:26

97. [11769](http://github.com/cms-sw/cmssw/pull/11769){:target="_blank"}  from **@igv4321**: Hcal simple reconstructor with method3 `reconstruction`  created: 2015-10-13 16:44:55 merged: 2015-10-23 08:26:49

98. [11768](http://github.com/cms-sw/cmssw/pull/11768){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-gem10 Changes due to absent short chambers in GE21 `geometry`  created: 2015-10-13 16:36:11 merged: 2015-10-19 10:02:20

99. [11766](http://github.com/cms-sw/cmssw/pull/11766){:target="_blank"}  from **@cms-tau-pog**: 3prong1pi0 new dms `reconstruction`  created: 2015-10-13 16:08:46 merged: 2015-10-23 08:27:00

100. [11761](http://github.com/cms-sw/cmssw/pull/11761){:target="_blank"}  from **@slava77**: pick ecal fraction of 0 for a candidate with trackMomentum 0 (same as #11302 and  #11760) `comparison`  `reconstruction`  created: 2015-10-13 14:20:24 merged: 2015-10-14 08:47:35

101. <span class="glyphicon glyphicon-arrow-right"></span>[11760](http://github.com/cms-sw/cmssw/pull/11760){:target="_blank"}  from **@slava77**: pick ecal fraction of 0 for a candidate with trackMomentum 0 (same as #11302) `reconstruction`  created: 2015-10-13 14:12:59 merged: 2015-10-15 07:36:30

102. [11759](http://github.com/cms-sw/cmssw/pull/11759){:target="_blank"}  from **@Dr15Jones**: Remove use of non-const static in pat::UserData<> `analysis`  created: 2015-10-13 13:27:47 merged: 2015-10-15 12:48:59

103. [11758](http://github.com/cms-sw/cmssw/pull/11758){:target="_blank"}  from **@Dr15Jones**: Made static const in LimiDetails `reconstruction`  created: 2015-10-13 12:53:05 merged: 2015-10-16 05:26:20

104. [11757](http://github.com/cms-sw/cmssw/pull/11757){:target="_blank"}  from **@Dr15Jones**: Changed static to const in ClusterFP420 `reconstruction`  created: 2015-10-13 12:24:07 merged: 2015-10-15 05:17:39

105. [11751](http://github.com/cms-sw/cmssw/pull/11751){:target="_blank"}  from **@dertexaner**: Adding HBHENegativeNoise bit to HcalRecHitFlagsToBeExcluded - 76X `reconstruction`  created: 2015-10-13 11:22:40 merged: 2015-10-23 09:30:13

106. [11749](http://github.com/cms-sw/cmssw/pull/11749){:target="_blank"}  from **@Dr15Jones**: Made static const in MuonSelectors `reconstruction`  created: 2015-10-13 10:48:58 merged: 2015-10-15 05:17:23

107. [11748](http://github.com/cms-sw/cmssw/pull/11748){:target="_blank"}  from **@Dr15Jones**: Fix thread safety problem in ParametrizationHelper::fromString `analysis`  created: 2015-10-13 10:36:49 merged: 2015-10-15 05:17:07

108. [11746](http://github.com/cms-sw/cmssw/pull/11746){:target="_blank"}  from **@Dr15Jones**: Removed unnecessary const_cast in DataFormats/L1GlobalTrigger `l1`  created: 2015-10-13 09:52:06 merged: 2015-10-15 05:16:51

109. [11745](http://github.com/cms-sw/cmssw/pull/11745){:target="_blank"}  from **@Dr15Jones**: Remove unnecessary const cast away in LTCDigi `l1`  created: 2015-10-13 09:21:53 merged: 2015-10-15 05:16:36

110. [11744](http://github.com/cms-sw/cmssw/pull/11744){:target="_blank"}  from **@davidlt**: [UB] Initialize 'WasDecodingOk_' in 'EcalDCCHeaderRuntypeDecoder' `reconstruction`  created: 2015-10-13 09:13:40 merged: 2015-10-15 05:16:22

111. [11743](http://github.com/cms-sw/cmssw/pull/11743){:target="_blank"}  from **@Dr15Jones**: Fix problems found by static analyzer in DataFormats/Scalers `daq`  `l1`  `reconstruction`  created: 2015-10-13 09:05:24 merged: 2015-10-20 11:52:01

112. [11742](http://github.com/cms-sw/cmssw/pull/11742){:target="_blank"}  from **@slava77**: fix wrong auto-forward-port of RecoTLR of  #11741  `operations`  created: 2015-10-13 08:14:35 merged: 2015-10-15 05:16:03

113. <span class="glyphicon glyphicon-arrow-right"></span>[11741](http://github.com/cms-sw/cmssw/pull/11741){:target="_blank"}  from **@slava77**: heavyIonsRun2 scenario for data processing `dqm`  `operations`  created: 2015-10-12 23:38:58 merged: 2015-10-13 07:29:23

114. [11738](http://github.com/cms-sw/cmssw/pull/11738){:target="_blank"}  from **@lgray**: EGM ID Updates from recipes (76X) `analysis`  `reconstruction`  created: 2015-10-12 22:01:02 merged: 2015-10-20 17:17:38

115. [11737](http://github.com/cms-sw/cmssw/pull/11737){:target="_blank"}  from **@lathomas**: Tuning the CSC Halo filter parameters `reconstruction`  created: 2015-10-12 21:22:52 merged: 2015-10-15 12:42:19

116. [11734](http://github.com/cms-sw/cmssw/pull/11734){:target="_blank"}  from **@davidlt**: Fix UB by settting firstStep in AnnealingGhostTrackFitter `reconstruction`  created: 2015-10-12 15:20:03 merged: 2015-10-15 05:22:56

117. [11728](http://github.com/cms-sw/cmssw/pull/11728){:target="_blank"}  from **@davidlt**: Add _UBSAN_ to CMSSW `comparison`  `core`  created: 2015-10-12 07:58:21 merged: 2015-10-19 15:33:31

118. [11727](http://github.com/cms-sw/cmssw/pull/11727){:target="_blank"}  from **@serval2412**: cppcheck: Prefer prefix ++/-- operators for non-primitive types `alca`  created: 2015-10-11 21:12:41 merged: 2015-10-15 12:46:26

119. [11726](http://github.com/cms-sw/cmssw/pull/11726){:target="_blank"}  from **@dertexaner**: HBHE isolated noise reflagger retuning for Run2 `reconstruction`  created: 2015-10-11 20:52:08 merged: 2015-10-23 08:27:10

120. <span class="glyphicon glyphicon-arrow-right"></span>[11724](http://github.com/cms-sw/cmssw/pull/11724){:target="_blank"}  from **@Dr15Jones**: Fix python2.6 SyntaxError. `comparison`  `core`  created: 2015-10-11 13:10:14 merged: 2015-10-11 14:27:48

121. [11721](http://github.com/cms-sw/cmssw/pull/11721){:target="_blank"}  from **@davidlt**: DQM/PixelLumi: definite static const int members `dqm`  created: 2015-10-10 13:09:05 merged: 2015-10-15 05:21:02

122. [11720](http://github.com/cms-sw/cmssw/pull/11720){:target="_blank"}  from **@fwyzard**: cmsCheckMultithreading replaced by edmCheckmultithreading `hlt`  created: 2015-10-10 11:37:22 merged: 2015-10-11 14:31:10

123. <span class="glyphicon glyphicon-arrow-right"></span>[11719](http://github.com/cms-sw/cmssw/pull/11719){:target="_blank"}  from **@fwyzard**: cmsCheckMultithreading replaced by edmCheckmultithreading `hlt`  created: 2015-10-10 11:37:16 merged: 2015-10-12 12:36:19

124. [11716](http://github.com/cms-sw/cmssw/pull/11716){:target="_blank"}  from **@vandreev11**: Hgcal v7geometry xml files `geometry`  created: 2015-10-09 18:01:39 merged: 2015-10-12 20:26:12

125. [11715](http://github.com/cms-sw/cmssw/pull/11715){:target="_blank"}  from **@silviodonato**: HLT BTV DQM offline - safe for missing collections `dqm`  created: 2015-10-09 15:37:52 merged: 2015-10-15 05:20:45

126. [11714](http://github.com/cms-sw/cmssw/pull/11714){:target="_blank"}  from **@Dr15Jones**: Removed unused typedef from HLTTrackHaloFilter `hlt`  created: 2015-10-09 15:20:11 merged: 2015-10-11 14:36:24

127. [11713](http://github.com/cms-sw/cmssw/pull/11713){:target="_blank"}  from **@Dr15Jones**: Removed unused DetSetLazyVector class `core`  created: 2015-10-09 14:50:02 merged: 2015-10-11 14:36:29

128. [11711](http://github.com/cms-sw/cmssw/pull/11711){:target="_blank"}  from **@bsunanda**: bsunanda: Run2-hcx40 Update the hit validation package to match Phase2 simulation  `dqm`  created: 2015-10-09 07:10:34 merged: 2015-10-16 13:12:09

129. [11710](http://github.com/cms-sw/cmssw/pull/11710){:target="_blank"}  from **@slehti**: HLTTauDQM: Bugfix `dqm`  created: 2015-10-09 06:13:08 merged: 2015-10-15 05:19:52

130. [11708](http://github.com/cms-sw/cmssw/pull/11708){:target="_blank"}  from **@hengne**: Relval update after 7_6_0_pre6 `generators`  `pdmv`  created: 2015-10-09 06:07:35 merged: 2015-10-13 07:26:44

131. [11706](http://github.com/cms-sw/cmssw/pull/11706){:target="_blank"}  from **@Dr15Jones**: const thread-safe packed classes `analysis`  created: 2015-10-09 03:49:01 merged: 2015-10-15 05:19:19

132. <span class="glyphicon glyphicon-arrow-right"></span>[11705](http://github.com/cms-sw/cmssw/pull/11705){:target="_blank"}  from **@lihux25**: Fix the duplicated HF channels `reconstruction`  created: 2015-10-08 22:30:07 merged: 2015-10-12 12:41:23

133. [11704](http://github.com/cms-sw/cmssw/pull/11704){:target="_blank"}  from **@lihux25**: Fix the duplicated HF channels `reconstruction`  created: 2015-10-08 22:17:40 merged: 2015-10-11 14:31:26

134. [11694](http://github.com/cms-sw/cmssw/pull/11694){:target="_blank"}  from **@ndaci**: Added new categories (DSTJets,DSTMuons) for scouting triggers. `dqm`  created: 2015-10-08 15:39:04 merged: 2015-10-15 12:51:25

135. [11690](http://github.com/cms-sw/cmssw/pull/11690){:target="_blank"}  from **@mark-grimes**: Switch AddOn tests to use Run 2 eras `comparison`  `core`  created: 2015-10-08 13:30:33 merged: 2015-10-26 13:36:54

136. <span class="glyphicon glyphicon-arrow-right"></span>[11688](http://github.com/cms-sw/cmssw/pull/11688){:target="_blank"}  from **@cms-btv-pog**: Switch on hadronFlavourHasPriority for b-tag Validation module. `dqm`  created: 2015-10-08 09:53:10 merged: 2015-10-15 07:36:50

137. [11685](http://github.com/cms-sw/cmssw/pull/11685){:target="_blank"}  from **@cms-btv-pog**: b-tag GBRForest payloads from GT `analysis`  `reconstruction`  created: 2015-10-08 05:53:08 merged: 2015-10-16 06:03:04

138. [11683](http://github.com/cms-sw/cmssw/pull/11683){:target="_blank"}  from **@mrcarver**: Removed JetIdCleaning from SUSY path names (CMSHLT-601 for 76X) `dqm`  created: 2015-10-07 20:33:24 merged: 2015-10-15 12:51:31

139. [11680](http://github.com/cms-sw/cmssw/pull/11680){:target="_blank"}  from **@wmtan**: Replace LinkDef file witl XML selection file in PhysicsTools/TagAndProbe `analysis`  created: 2015-10-07 20:15:05 merged: 2015-10-26 14:56:30

140. [11676](http://github.com/cms-sw/cmssw/pull/11676){:target="_blank"}  from **@richard-cms**: L1 MHT and forward Jet fixes `l1`  created: 2015-10-07 18:57:24 merged: 2015-10-11 14:31:31

141. [11673](http://github.com/cms-sw/cmssw/pull/11673){:target="_blank"}  from **@wmtan**: Replace LinkDef files with XML selextion files.in CalibCalorimetry/EcalLaserAnalyzer `alca`  created: 2015-10-07 18:40:06 merged: 2015-10-12 12:31:15

142. [11671](http://github.com/cms-sw/cmssw/pull/11671){:target="_blank"}  from **@nhanvtran**: update to PUPPI;speedup, low PU corr `analysis`  `reconstruction`  created: 2015-10-07 16:12:03 merged: 2015-10-23 08:23:21

143. [11670](http://github.com/cms-sw/cmssw/pull/11670){:target="_blank"}  from **@ianna**: Thread-safe DB Geometry Builders `db`  created: 2015-10-07 15:54:12 merged: 2015-10-27 06:56:32

144. [11666](http://github.com/cms-sw/cmssw/pull/11666){:target="_blank"}  from **@makortel**: Fix the definition of pileup tracks in MultiTrackValidator `dqm`  created: 2015-10-07 09:38:31 merged: 2015-10-15 06:01:15

145. [11661](http://github.com/cms-sw/cmssw/pull/11661){:target="_blank"}  from **@wmtan**: replace most LinkDef.h files with XML selection files `alca`  `analysis`  `db`  `dqm`  `reconstruction`  `simulation`  created: 2015-10-06 20:12:39 merged: 2015-10-17 09:10:13

146. <span class="glyphicon glyphicon-arrow-right"></span>[11657](http://github.com/cms-sw/cmssw/pull/11657){:target="_blank"}  from **@gsafronov**: 75X: fix pT selection in HLTrigger/special/src/HLTPixlMBFilt.cc `comparison`  `hlt`  created: 2015-10-06 16:07:37 merged: 2015-10-15 07:35:18

147. [11653](http://github.com/cms-sw/cmssw/pull/11653){:target="_blank"}  from **@rovere**: Restore v0 validation   `dqm`  `reconstruction`  `simulation`  created: 2015-10-06 14:38:42 merged: 2015-10-15 05:22:06

148. [11652](http://github.com/cms-sw/cmssw/pull/11652){:target="_blank"}  from **@ianna**: Extended 2019 Scenario Scripts `db`  created: 2015-10-06 13:12:00 merged: 2015-10-12 12:31:46

149. [11651](http://github.com/cms-sw/cmssw/pull/11651){:target="_blank"}  from **@lgray**: Forward port HGCalRecAlgos/Producers from CMSSW_6_2_0_SLHC26_patch3 (76X) `reconstruction`  created: 2015-10-06 13:04:14 merged: 2015-10-11 14:36:37

150. [11644](http://github.com/cms-sw/cmssw/pull/11644){:target="_blank"}  from **@jmduarte**: RazorHbb HLT DQM for 76X `dqm`  created: 2015-10-06 05:48:59 merged: 2015-10-15 06:06:19

151. <span class="glyphicon glyphicon-arrow-right"></span>[11638](http://github.com/cms-sw/cmssw/pull/11638){:target="_blank"}  from **@alja**: 75x Fireworks: fix problem with muon global track propagation `comparison`  `visualization`  created: 2015-10-05 16:30:42 merged: 2015-10-12 12:36:37

152. [11636](http://github.com/cms-sw/cmssw/pull/11636){:target="_blank"}  from **@jasperlauwers**: Adding VBF H to Invisible paths + associated code fix `dqm`  created: 2015-10-05 14:09:05 merged: 2015-10-15 06:01:26

153. [11624](http://github.com/cms-sw/cmssw/pull/11624){:target="_blank"}  from **@makortel**: Migrate away from explicit comparisons of GeomDetEnumerators::PixelBarrel/PixelEndcap `alca`  `fastsim`  `geometry`  `reconstruction`  created: 2015-10-02 15:02:58 merged: 2015-10-16 13:12:43

154. <span class="glyphicon glyphicon-arrow-right"></span>[11615](http://github.com/cms-sw/cmssw/pull/11615){:target="_blank"}  from **@cmkuo**: fix ES unpacker when the 2nd OptoRX is diabled, but the 1t and 3rd Op `reconstruction`  created: 2015-10-02 03:33:05 merged: 2015-10-12 12:41:39

155. <span class="glyphicon glyphicon-arrow-right"></span>[11604](http://github.com/cms-sw/cmssw/pull/11604){:target="_blank"}  from **@kkrajczar**: For HI HLT: migration of 5 HI tracking modules to stream modules (75X backport) `reconstruction`  created: 2015-10-01 16:06:26 merged: 2015-10-12 12:41:45

156. <span class="glyphicon glyphicon-arrow-right"></span>[11594](http://github.com/cms-sw/cmssw/pull/11594){:target="_blank"}  from **@ggovi**: Back-port of several fixes and improvements for the conddb tools `db`  created: 2015-10-01 13:12:15 merged: 2015-10-12 12:36:43

157. <span class="glyphicon glyphicon-arrow-right"></span>[11586](http://github.com/cms-sw/cmssw/pull/11586){:target="_blank"}  from **@Martin-Grunewald**: Addition of PFMET to Trigger Data Formats (75X) `hlt`  created: 2015-10-01 07:25:12 merged: 2015-10-13 07:31:56

158. <span class="glyphicon glyphicon-arrow-right"></span>[11551](http://github.com/cms-sw/cmssw/pull/11551){:target="_blank"}  from **@dmitrijus**: A fix for the DQMStreamerReader (75x) `dqm`  created: 2015-09-29 14:27:12 merged: 2015-10-12 12:36:50

159. [11548](http://github.com/cms-sw/cmssw/pull/11548){:target="_blank"}  from **@cms-tsg-storm**: 76X hlt25ns round six `fastsim`  `hlt`  created: 2015-09-29 12:22:41 merged: 2015-10-16 13:12:51

160. <span class="glyphicon glyphicon-arrow-right"></span>[11545](http://github.com/cms-sw/cmssw/pull/11545){:target="_blank"}  from **@sushilchauhan**: fix for LS range of fit if there are no event processed in a LS `dqm`  created: 2015-09-29 12:11:46 merged: 2015-10-12 12:36:57

161. <span class="glyphicon glyphicon-arrow-right"></span>[11541](http://github.com/cms-sw/cmssw/pull/11541){:target="_blank"}  from **@hengne**: relval scripts update, 2015c data workflows, a couple of fixes. `alca`  `hlt`  `pdmv`  `simulation`  created: 2015-09-29 10:27:35 merged: 2015-10-13 07:32:08

162. <span class="glyphicon glyphicon-arrow-right"></span>[11536](http://github.com/cms-sw/cmssw/pull/11536){:target="_blank"}  from **@smorovic**: Checksum parameter cfi export (75X) `daq`  `reconstruction`  created: 2015-09-28 16:53:47 merged: 2015-10-12 12:37:03

163. <span class="glyphicon glyphicon-arrow-right"></span>[11531](http://github.com/cms-sw/cmssw/pull/11531){:target="_blank"}  from **@taroni**: fixing emulator fenix bug `l1`  created: 2015-09-28 14:18:10 merged: 2015-10-12 12:51:19

164. <span class="glyphicon glyphicon-arrow-right"></span>[11523](http://github.com/cms-sw/cmssw/pull/11523){:target="_blank"}  from **@arcidiac**: Fix for the Streams' names to be monitored `dqm`  created: 2015-09-28 11:04:20 merged: 2015-10-15 09:27:08

165. <span class="glyphicon glyphicon-arrow-right"></span>[11521](http://github.com/cms-sw/cmssw/pull/11521){:target="_blank"}  from **@slehti**: Bugfix in HLTTauDQMPath affecting L2 plots `dqm`  created: 2015-09-28 10:18:05 merged: 2015-10-12 12:41:51

166. <span class="glyphicon glyphicon-arrow-right"></span>[11509](http://github.com/cms-sw/cmssw/pull/11509){:target="_blank"}  from **@fwyzard**: hltDiff: compare TriggerResults event by event (75x) `comparison`  `hlt`  created: 2015-09-26 10:38:39 merged: 2015-10-12 15:16:43

167. [11497](http://github.com/cms-sw/cmssw/pull/11497){:target="_blank"}  from **@kpedro88**: merge SLHC updates for CaloTowers `alca`  `db`  `geometry`  `hlt`  `reconstruction`  `simulation`  created: 2015-09-25 18:33:14 merged: 2015-10-20 11:52:31

168. <span class="glyphicon glyphicon-arrow-right"></span>[11484](http://github.com/cms-sw/cmssw/pull/11484){:target="_blank"}  from **@cms-tsg-storm**: 75X hlt25ns round5 plus updated frozenv4 `hlt`  created: 2015-09-25 08:15:21 merged: 2015-10-15 07:51:39

169. <span class="glyphicon glyphicon-arrow-right"></span>[11474](http://github.com/cms-sw/cmssw/pull/11474){:target="_blank"}  from **@davidlange6**: Fix mistakes in hcal customise function created: 2015-09-24 20:02:55 merged: 2015-09-24 20:03:31

170. <span class="glyphicon glyphicon-arrow-right"></span>[11464](http://github.com/cms-sw/cmssw/pull/11464){:target="_blank"}  from **@threus**: updated x-axes for several SiStripDQM MEs (75x) `dqm`  created: 2015-09-24 16:04:58 merged: 2015-10-12 12:37:22

171. <span class="glyphicon glyphicon-arrow-right"></span>[11457](http://github.com/cms-sw/cmssw/pull/11457){:target="_blank"}  from **@smorovic**: Freeing INI file buffer after writing the file is finished (75X) `core`  created: 2015-09-24 13:45:05 merged: 2015-10-12 12:42:14

172. <span class="glyphicon glyphicon-arrow-right"></span>[11444](http://github.com/cms-sw/cmssw/pull/11444){:target="_blank"}  from **@dinardo**: Now the code is able to handle non consecutive LS `dqm`  created: 2015-09-23 22:43:36 merged: 2015-10-15 07:56:40

173. <span class="glyphicon glyphicon-arrow-right"></span>[11417](http://github.com/cms-sw/cmssw/pull/11417){:target="_blank"}  from **@argiro**: PositionCalc Fix `reconstruction`  created: 2015-09-22 09:55:43 merged: 2015-10-12 12:46:26

174. <span class="glyphicon glyphicon-arrow-right"></span>[11406](http://github.com/cms-sw/cmssw/pull/11406){:target="_blank"}  from **@lgray**: Fix sigmaIetaIphi for photon regression (75X) `reconstruction`  created: 2015-09-21 22:21:53 merged: 2015-10-12 12:51:31

175. <span class="glyphicon glyphicon-arrow-right"></span>[11400](http://github.com/cms-sw/cmssw/pull/11400){:target="_blank"}  from **@Dr15Jones**: Change mayConsume to conditional consumes in PATJetProducer `analysis`  created: 2015-09-21 15:57:24 merged: 2015-09-28 13:32:30

176. <span class="glyphicon glyphicon-arrow-right"></span>[11391](http://github.com/cms-sw/cmssw/pull/11391){:target="_blank"}  from **@Martin-Grunewald**: 75X: New GT with L1T v5 and thus new HLT selection `alca`  `hlt`  created: 2015-09-21 10:44:06 merged: 2015-10-15 09:27:14

177. <span class="glyphicon glyphicon-arrow-right"></span>[11362](http://github.com/cms-sw/cmssw/pull/11362){:target="_blank"}  from **@cms-met**: Change the type1 jet pt threshold from 10 to 15 GeV `analysis`  created: 2015-09-18 15:59:36 merged: 2015-10-12 12:51:36

178. [11251](http://github.com/cms-sw/cmssw/pull/11251){:target="_blank"}  from **@dmitrijus**:   Replace mark-and-delete at next merge algorithm in DQMStore (76x) `dqm`  created: 2015-09-15 11:07:21 merged: 2015-10-27 17:39:14

179. [11131](http://github.com/cms-sw/cmssw/pull/11131){:target="_blank"}  from **@wouf**: Update Hydjet2 and Hydjet1 `generators`  created: 2015-09-04 14:37:46 merged: 2015-10-29 16:32:10

180. <span class="glyphicon glyphicon-arrow-right"></span>[11096](http://github.com/cms-sw/cmssw/pull/11096){:target="_blank"}  from **@VinInn**: fix inner outer for OutIn in 75X `reconstruction`  created: 2015-09-03 08:49:50 merged: 2015-10-12 12:42:21

181. [11060](http://github.com/cms-sw/cmssw/pull/11060){:target="_blank"}  from **@duanders**: Use new primary vertex filter in hotline and high MET skim `alca`  `pdmv`  created: 2015-09-01 09:48:37 merged: 2015-10-29 12:26:43

182. <span class="glyphicon glyphicon-arrow-right"></span>[10839](http://github.com/cms-sw/cmssw/pull/10839){:target="_blank"}  from **@yetkinyilmaz**: Option for DAS query in ConfigBuilder 75X `comparison`  `operations`  created: 2015-08-18 11:57:25 merged: 2015-10-13 07:37:30

183. [10517](http://github.com/cms-sw/cmssw/pull/10517){:target="_blank"}  from **@alberto-sanchez**: Adding Onia states to pruned gen particles `analysis`  created: 2015-08-02 14:00:18 merged: 2015-10-16 06:01:52

184. [10494](http://github.com/cms-sw/cmssw/pull/10494){:target="_blank"}  from **@ianna**: Use Hcal Trigger Tower Geometry from Event Setup `alca`  `db`  `l1`  created: 2015-07-31 08:54:51 merged: 2015-10-27 06:56:39

185. [10320](http://github.com/cms-sw/cmssw/pull/10320){:target="_blank"}  from **@jhgoh**: RivetAnalyzer consumes migration 76X `generators`  created: 2015-07-23 13:38:38 merged: 2015-10-19 11:28:28

186. [10176](http://github.com/cms-sw/cmssw/pull/10176){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca18 Restore Olgas code and modify the others to do both NZS and iterative analysis `alca`  created: 2015-07-13 17:57:58 merged: 2015-10-23 09:32:24

#### CMSDIST Changes between Tags REL/CMSSW_7_6_0_pre7/slc6_amd64_gcc493 and REL/CMSSW_7_6_0/slc6_amd64_gcc493:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_6_0_pre7/slc6_amd64_gcc493...REL/CMSSW_7_6_0/slc6_amd64_gcc493)



1. [1925](http://github.com/cms-sw/cmsdist/pull/1925){:target="_blank"}  from **@degano**: Update data for RecoJets/JetProducers. created: 2015-10-23 12:06:10 merged: 2015-10-23 12:06:14

2. [1915](http://github.com/cms-sw/cmsdist/pull/1915){:target="_blank"}  from **@smuzaffar**: update root to use cms/c1ca998 i.e current tip of root 6-02 branches created: 2015-10-21 14:57:51 merged: 2015-10-21 15:18:56

3. [1908](http://github.com/cms-sw/cmsdist/pull/1908){:target="_blank"}  from **@davidlt**: gmp-static: set --host and --build to for a generic build created: 2015-10-19 06:53:02 merged: 2015-10-19 06:53:27

4. [1905](http://github.com/cms-sw/cmsdist/pull/1905){:target="_blank"}  from **@davidlt**: Remmove unsupported command by icpc and ifort created: 2015-10-16 11:07:24 merged: 2015-10-16 11:07:41

5. [1904](http://github.com/cms-sw/cmsdist/pull/1904){:target="_blank"}  from **@degano**: Update root to the tip of the branch. created: 2015-10-16 10:34:09 merged: 2015-10-16 10:35:31

6. [1902](http://github.com/cms-sw/cmsdist/pull/1902){:target="_blank"}  from **@degano**: Advance RecoJets/JetProducers data to latest update. created: 2015-10-15 13:49:13 merged: 2015-10-15 13:49:17

7. [1900](http://github.com/cms-sw/cmsdist/pull/1900){:target="_blank"}  from **@degano**: Upgrade Frontier client to version 2.8.14 and pacparser to 1.3.5. created: 2015-10-14 13:56:06 merged: 2015-10-14 13:56:55

8. [1897](http://github.com/cms-sw/cmsdist/pull/1897){:target="_blank"}  from **@cms-sw**: Revert "Update frontier client to 2.8.13 and pacparser to 1.3.5." created: 2015-10-14 11:39:43 merged: 2015-10-14 11:39:53

9. [1895](http://github.com/cms-sw/cmsdist/pull/1895){:target="_blank"}  from **@cms-sw**: Revert "Advance fastjet-contrib to version cms/v1.020." created: 2015-10-13 21:08:51 merged: 2015-10-13 21:08:56

10. [1891](http://github.com/cms-sw/cmsdist/pull/1891){:target="_blank"}  from **@degano**: Advance fastjet-contrib to version cms/v1.020. created: 2015-10-13 07:53:44 merged: 2015-10-13 07:53:47

11. [1888](http://github.com/cms-sw/cmsdist/pull/1888){:target="_blank"}  from **@degano**: Advance release for RecoEgamma/ElectronIdentification data. created: 2015-10-13 07:31:12 merged: 2015-10-13 07:31:15

12. [1882](http://github.com/cms-sw/cmsdist/pull/1882){:target="_blank"}  from **@degano**: Update frontier client to 2.8.13 and pacparser to 1.3.5. created: 2015-10-12 10:18:05 merged: 2015-10-12 10:18:11

13. [1881](http://github.com/cms-sw/cmsdist/pull/1881){:target="_blank"}  from **@degano**: Update py2-dxr to use pysqlite 2.8 to load extension in sqlite 3.8. created: 2015-10-12 08:21:25 merged: 2015-10-12 08:23:21
