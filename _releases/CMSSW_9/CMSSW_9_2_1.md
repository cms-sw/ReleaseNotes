---
layout: post
rel_link:  "9_2_1"
title:  "CMSSW_9_2_1"
date:   2017-06-01 18:29:44
categories: cmssw
relmajor: 9
relminor: 2
relsubminor: 1
---

# CMSSW_9_2_1
#### Changes since CMSSW_9_2_0_patch5:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_9_2_0_patch5...CMSSW_9_2_1)



1. [19067](http://github.com/cms-sw/cmssw/pull/19067){:target="_blank"}  from **@rekovic**: pr92 L1T parser compatible utm-0.6.0 and later `l1`  created: 2017-06-01 15:24:21 merged: 2017-06-01 17:46:47

2. [19059](http://github.com/cms-sw/cmssw/pull/19059){:target="_blank"}  from **@mtosi**: fix pixel DQM `dqm`  created: 2017-06-01 11:57:28 merged: 2017-06-01 18:27:44

3. [19047](http://github.com/cms-sw/cmssw/pull/19047){:target="_blank"}  from **@kpedro88**: Fix HCAL premixing with QIE8 and uHTR `operations`  `reconstruction`  created: 2017-05-31 18:27:03 merged: 2017-06-01 18:20:16

4. [19045](http://github.com/cms-sw/cmssw/pull/19045){:target="_blank"}  from **@fwyzard**: recover original behaviour: do not write .jsndata files for empty lumisections `hlt`  created: 2017-05-31 15:49:38 merged: 2017-06-01 06:51:45

5. [19037](http://github.com/cms-sw/cmssw/pull/19037){:target="_blank"}  from **@BenjaminRS**: Fixing a bug to not try to take a L2 track when no L2 is available `hlt`  created: 2017-05-31 13:58:19 merged: 2017-06-01 13:54:31

6. [19035](http://github.com/cms-sw/cmssw/pull/19035){:target="_blank"}  from **@dmitrijus**: Online DQM fix for ML applications. `dqm`  created: 2017-05-31 13:47:21 merged: 2017-06-01 10:15:13

7. [19022](http://github.com/cms-sw/cmssw/pull/19022){:target="_blank"}  from **@davidlange6**: quieter harvesting step `dqm`  `operations`  created: 2017-05-30 16:44:31 merged: 2017-06-01 07:50:29

8. [19021](http://github.com/cms-sw/cmssw/pull/19021){:target="_blank"}  from **@gartung**: Geometry : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `geometry`  created: 2017-05-30 15:42:17 merged: 2017-06-01 06:57:49

9. [19016](http://github.com/cms-sw/cmssw/pull/19016){:target="_blank"}  from **@Dr15Jones**: Avoid making three copies of a large PSet in TrackingMonitor `dqm`  created: 2017-05-30 14:35:41 merged: 2017-06-01 06:57:37

10. [19015](http://github.com/cms-sw/cmssw/pull/19015){:target="_blank"}  from **@cerminar**: [92X] RelVal tests for new alca workflows `pdmv`  `upgrade`  created: 2017-05-30 14:18:05 merged: 2017-06-01 17:51:49

11. [19006](http://github.com/cms-sw/cmssw/pull/19006){:target="_blank"}  from **@boudoul**: Use non-deprecated phase2 scenario in detector description unit tests `geometry`  created: 2017-05-30 08:07:17 merged: 2017-05-30 10:58:22

12. [18998](http://github.com/cms-sw/cmssw/pull/18998){:target="_blank"}  from **@Dr15Jones**: Avoid TClass::GetClass calls when data product missing `core`  created: 2017-05-29 20:38:05 merged: 2017-05-30 07:42:56

13. [18996](http://github.com/cms-sw/cmssw/pull/18996){:target="_blank"}  from **@igv4321**: Adding anode DB suppression status to the rechits `reconstruction`  created: 2017-05-29 16:47:13 merged: 2017-06-01 18:22:58

14. [18993](http://github.com/cms-sw/cmssw/pull/18993){:target="_blank"}  from **@leggat**: Updates to pixel phase 1 summary class `dqm`  created: 2017-05-29 10:23:08 merged: 2017-06-01 07:53:38

15. [18991](http://github.com/cms-sw/cmssw/pull/18991){:target="_blank"}  from **@Dr15Jones**: Fix memory leaks in DQMOffline/Trigger `dqm`  created: 2017-05-29 02:54:59 merged: 2017-05-30 20:22:41

16. [18990](http://github.com/cms-sw/cmssw/pull/18990){:target="_blank"}  from **@Dr15Jones**: Fix memory leak in ConversionLikelihoodCalculator `reconstruction`  created: 2017-05-28 22:45:50 merged: 2017-06-01 06:57:27

17. [18989](http://github.com/cms-sw/cmssw/pull/18989){:target="_blank"}  from **@Dr15Jones**: Fixed memory leak in L1TMuonEndCapForestESProducer `l1`  created: 2017-05-28 22:17:56 merged: 2017-06-01 07:54:15

18. [18988](http://github.com/cms-sw/cmssw/pull/18988){:target="_blank"}  from **@Dr15Jones**: Fix thread local memory leak in EgammaTowerIsolation `reconstruction`  created: 2017-05-28 21:17:36 merged: 2017-06-01 06:57:15

19. [18987](http://github.com/cms-sw/cmssw/pull/18987){:target="_blank"}  from **@smuzaffar**: added missing header numeric to fix gcc6/7 compilation errors about std::iota `comparison`  `reconstruction`  `upgrade`  created: 2017-05-28 16:46:00 merged: 2017-05-28 16:46:12

20. [18985](http://github.com/cms-sw/cmssw/pull/18985){:target="_blank"}  from **@Dr15Jones**: Fixed memory leak in MultipleScatteringX0Data `reconstruction`  created: 2017-05-28 14:02:31 merged: 2017-06-01 14:50:28

21. [18982](http://github.com/cms-sw/cmssw/pull/18982){:target="_blank"}  from **@smuzaffar**: Fix geners cdump test `alca`  created: 2017-05-27 08:55:11 merged: 2017-05-27 10:33:08

22. [18980](http://github.com/cms-sw/cmssw/pull/18980){:target="_blank"}  from **@fwyzard**: fix HLT rate monitoring for CMSSW 9.2.x `hlt`  created: 2017-05-27 08:29:38 merged: 2017-05-28 08:02:47

23. [18973](http://github.com/cms-sw/cmssw/pull/18973){:target="_blank"}  from **@gartung**: DataFormats/PatCandidates : missing #include <array> found compiling on macos with clang `analysis`  `reconstruction`  created: 2017-05-26 18:31:19 merged: 2017-05-27 07:33:52

24. [18972](http://github.com/cms-sw/cmssw/pull/18972){:target="_blank"}  from **@gartung**: FWCore/Framework : missing #include <array> found compiling on macOS with clang `core`  created: 2017-05-26 18:30:21 merged: 2017-05-27 07:34:26

25. [18966](http://github.com/cms-sw/cmssw/pull/18966){:target="_blank"}  from **@forthommel**: CTPPS: small corrections in the diamond DQM `dqm`  created: 2017-05-26 15:10:45 merged: 2017-05-30 20:26:25

26. [18962](http://github.com/cms-sw/cmssw/pull/18962){:target="_blank"}  from **@thomreis**: L1 muon online DQM uprades `dqm`  created: 2017-05-26 14:15:34 merged: 2017-06-01 11:02:54

27. [18959](http://github.com/cms-sw/cmssw/pull/18959){:target="_blank"}  from **@jalimena**: update EXO NoBPTX trigger paths validation for 2017 pp collisions `dqm`  created: 2017-05-26 12:14:32 merged: 2017-06-01 08:16:44

28. [18957](http://github.com/cms-sw/cmssw/pull/18957){:target="_blank"}  from **@folguera**: MuonHLT IterL3 reconstruction:  bug fix to avoid running twice on the same L1  `hlt`  created: 2017-05-26 08:44:54 merged: 2017-05-27 07:37:56

29. [18955](http://github.com/cms-sw/cmssw/pull/18955){:target="_blank"}  from **@jhgoh**: RPCRecHits nan protection `reconstruction`  created: 2017-05-26 01:26:20 merged: 2017-05-31 11:08:25

30. [18952](http://github.com/cms-sw/cmssw/pull/18952){:target="_blank"}  from **@cms-sw**: fix fwlite build by removing dependency on TrackingTools/PatternTools/interface/Trajectory.h `comparison`  `reconstruction`  created: 2017-05-25 19:39:39 merged: 2017-05-25 19:39:52

31. [18947](http://github.com/cms-sw/cmssw/pull/18947){:target="_blank"}  from **@gartung**: RecoTracker: fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `reconstruction`  created: 2017-05-25 15:30:22 merged: 2017-05-27 07:41:20

32. [18946](http://github.com/cms-sw/cmssw/pull/18946){:target="_blank"}  from **@gartung**: RecoParticleFlow : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `reconstruction`  created: 2017-05-25 15:26:15 merged: 2017-05-27 07:41:35

33. [18945](http://github.com/cms-sw/cmssw/pull/18945){:target="_blank"}  from **@gartung**: RecoMuon : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `reconstruction`  created: 2017-05-25 15:24:09 merged: 2017-05-27 07:41:47

34. [18944](http://github.com/cms-sw/cmssw/pull/18944){:target="_blank"}  from **@gartung**: RecoLocalCalo : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `reconstruction`  created: 2017-05-25 15:22:06 merged: 2017-05-27 07:41:59

35. [18943](http://github.com/cms-sw/cmssw/pull/18943){:target="_blank"}  from **@gartung**: RecoBTag : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `reconstruction`  created: 2017-05-25 15:19:33 merged: 2017-05-27 07:42:10

36. [18942](http://github.com/cms-sw/cmssw/pull/18942){:target="_blank"}  from **@gartung**: PhysicsTools : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `analysis`  `reconstruction`  created: 2017-05-25 15:17:34 merged: 2017-05-27 07:42:18

37. [18941](http://github.com/cms-sw/cmssw/pull/18941){:target="_blank"}  from **@gartung**: L1Trigger : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `l1`  created: 2017-05-25 15:14:45 merged: 2017-05-30 20:27:06

38. [18940](http://github.com/cms-sw/cmssw/pull/18940){:target="_blank"}  from **@gartung**: HLTrigger : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `hlt`  created: 2017-05-25 15:11:07 merged: 2017-05-27 07:42:45

39. [18939](http://github.com/cms-sw/cmssw/pull/18939){:target="_blank"}  from **@gartung**: GeneratorInterface : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `generators`  created: 2017-05-25 15:09:02 merged: 2017-05-30 14:12:12

40. [18938](http://github.com/cms-sw/cmssw/pull/18938){:target="_blank"}  from **@gartung**: EventFilter : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `l1`  created: 2017-05-25 15:06:56 merged: 2017-05-30 20:27:16

41. [18937](http://github.com/cms-sw/cmssw/pull/18937){:target="_blank"}  from **@gartung**: DQMServices : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `dqm`  created: 2017-05-25 15:04:49 merged: 2017-05-27 07:42:56

42. [18936](http://github.com/cms-sw/cmssw/pull/18936){:target="_blank"}  from **@gartung**: DQM + DQMOffline : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `dqm`  created: 2017-05-25 15:03:25 merged: 2017-05-27 07:43:07

43. [18935](http://github.com/cms-sw/cmssw/pull/18935){:target="_blank"}  from **@gartung**: CondCore : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `db`  created: 2017-05-25 15:00:40 merged: 2017-05-30 14:12:23

44. [18934](http://github.com/cms-sw/cmssw/pull/18934){:target="_blank"}  from **@gartung**: CalibCalorimetry + CaloOnlineTools : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `alca`  `db`  created: 2017-05-25 14:39:09 merged: 2017-05-30 08:42:28

45. [18933](http://github.com/cms-sw/cmssw/pull/18933){:target="_blank"}  from **@gartung**: Alignment : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `alca`  created: 2017-05-25 14:36:05 merged: 2017-05-30 07:43:13

46. [18931](http://github.com/cms-sw/cmssw/pull/18931){:target="_blank"}  from **@Dr15Jones**: Removed class ELdestControl `core`  created: 2017-05-25 13:43:33 merged: 2017-05-27 07:43:28

47. [18930](http://github.com/cms-sw/cmssw/pull/18930){:target="_blank"}  from **@VinInn**: VertexDQM: recenter y_vtx, increase range for nvtx `dqm`  created: 2017-05-25 11:27:33 merged: 2017-05-27 07:43:52

48. [18928](http://github.com/cms-sw/cmssw/pull/18928){:target="_blank"}  from **@gartung**: CalibFormats : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `alca`  created: 2017-05-25 01:40:32 merged: 2017-05-30 08:21:35

49. [18927](http://github.com/cms-sw/cmssw/pull/18927){:target="_blank"}  from **@gartung**: DataFormats/TrackerRecHit2D: Fix warning warning: 'class TkCloner' has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `reconstruction`  created: 2017-05-25 01:32:37 merged: 2017-05-27 07:44:02

50. [18926](http://github.com/cms-sw/cmssw/pull/18926){:target="_blank"}  from **@gartung**: SimCalorimetry : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `simulation`  `upgrade`  created: 2017-05-24 23:45:33 merged: 2017-05-27 07:44:22

51. [18924](http://github.com/cms-sw/cmssw/pull/18924){:target="_blank"}  from **@gartung**: SimG4 : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `simulation`  created: 2017-05-24 22:19:38 merged: 2017-05-27 07:44:31

52. [18923](http://github.com/cms-sw/cmssw/pull/18923){:target="_blank"}  from **@gartung**: SimTracker : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `simulation`  `upgrade`  created: 2017-05-24 22:16:39 merged: 2017-05-27 07:44:43

53. [18922](http://github.com/cms-sw/cmssw/pull/18922){:target="_blank"}  from **@gartung**: fix Utilities/XrdAdapter : gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `core`  created: 2017-05-24 22:12:33 merged: 2017-05-27 07:44:52

54. [18921](http://github.com/cms-sw/cmssw/pull/18921){:target="_blank"}  from **@gartung**: TrackingTools : fix gcc700 warning: class  has virtual functions and accessible non-virtual destructor [-Wnon-virtual-dtor] `reconstruction`  created: 2017-05-24 22:08:08 merged: 2017-05-27 07:45:11

55. [18916](http://github.com/cms-sw/cmssw/pull/18916){:target="_blank"}  from **@hroskes**: fix mistake in all in one tool configuration `alca`  created: 2017-05-24 16:17:45 merged: 2017-05-25 08:11:01

56. [18910](http://github.com/cms-sw/cmssw/pull/18910){:target="_blank"}  from **@smuzaffar**: Fixing rootcling warning about missing dependencies `reconstruction`  created: 2017-05-24 09:53:10 merged: 2017-05-25 08:10:50

57. [18909](http://github.com/cms-sw/cmssw/pull/18909){:target="_blank"}  from **@cms-sw**: run condTestRegression test only on slc/amd64 archs. `db`  created: 2017-05-24 05:38:50 merged: 2017-05-25 08:10:23

58. [18908](http://github.com/cms-sw/cmssw/pull/18908){:target="_blank"}  from **@cfmcginn**: Added offline dqm for HI triggers to be used in LowPU datataking in 2017 `dqm`  created: 2017-05-24 05:30:13 merged: 2017-05-25 08:10:32

59. [18905](http://github.com/cms-sw/cmssw/pull/18905){:target="_blank"}  from **@franzoni**: [9_2_X] fix name of input collection in pathALCARECOHcalCalMinBias `alca`  created: 2017-05-23 20:06:09 merged: 2017-05-27 07:48:11

60. [18900](http://github.com/cms-sw/cmssw/pull/18900){:target="_blank"}  from **@hroskes**: convenient interface for HipPy and MP alignments `alca`  created: 2017-05-23 15:13:42 merged: 2017-05-24 07:26:36

61. [18898](http://github.com/cms-sw/cmssw/pull/18898){:target="_blank"}  from **@davidlt**: Implement HRRealTime for AArch64 `core`  created: 2017-05-23 14:39:00 merged: 2017-05-24 07:26:14

62. [18897](http://github.com/cms-sw/cmssw/pull/18897){:target="_blank"}  from **@ianna**: DD Agorithm Cleanup `geometry`  created: 2017-05-23 14:29:20 merged: 2017-05-24 14:02:26

63. [18896](http://github.com/cms-sw/cmssw/pull/18896){:target="_blank"}  from **@VinInn**: fix bug about lambda error + small cleanup `reconstruction`  created: 2017-05-23 12:57:56 merged: 2017-05-27 07:48:28

64. [18894](http://github.com/cms-sw/cmssw/pull/18894){:target="_blank"}  from **@threus**: update GT in online DQM and EventDisplay `dqm`  created: 2017-05-23 08:59:01 merged: 2017-05-23 16:04:27

65. [18893](http://github.com/cms-sw/cmssw/pull/18893){:target="_blank"}  from **@Teemperor**: Comment out commentary behind #endif in Constants.h `alca`  `comparison`  `db`  created: 2017-05-23 07:01:27 merged: 2017-05-23 07:10:32

66. [18891](http://github.com/cms-sw/cmssw/pull/18891){:target="_blank"}  from **@ianna**: DDQuery Remove Unused Class `geometry`  created: 2017-05-22 17:18:26 merged: 2017-05-23 05:59:09

67. [18890](http://github.com/cms-sw/cmssw/pull/18890){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx126 Correct the name of collection in 3 cfi files of HCAL AlCaReco's `alca`  created: 2017-05-22 17:12:18 merged: 2017-05-24 07:27:04

68. [18889](http://github.com/cms-sw/cmssw/pull/18889){:target="_blank"}  from **@Dr15Jones**: Added edmScanValgrind.py to discard false positives `core`  created: 2017-05-22 16:32:41 merged: 2017-05-23 07:12:23

69. [18888](http://github.com/cms-sw/cmssw/pull/18888){:target="_blank"}  from **@jfernan2**: Small fix to DT DQM configuration `dqm`  created: 2017-05-22 15:21:12 merged: 2017-05-25 08:09:57

70. [18887](http://github.com/cms-sw/cmssw/pull/18887){:target="_blank"}  from **@Teemperor**: Remove the dead headers ColumnPacker.hh/ColumnPackerHelper.hh `alca`  created: 2017-05-22 15:00:54 merged: 2017-05-23 09:48:25

71. [18886](http://github.com/cms-sw/cmssw/pull/18886){:target="_blank"}  from **@Teemperor**: Added missing include for <utility> to collectTupleNames.hh `alca`  created: 2017-05-22 15:00:46 merged: 2017-05-23 05:59:21

72. [18885](http://github.com/cms-sw/cmssw/pull/18885){:target="_blank"}  from **@Teemperor**: Add missing includes to BoundaryInformation.h `reconstruction`  created: 2017-05-22 15:00:39 merged: 2017-05-25 08:09:38

73. [18884](http://github.com/cms-sw/cmssw/pull/18884){:target="_blank"}  from **@Teemperor**: Added missing <vector> include to PattRecoTree.h `reconstruction`  created: 2017-05-22 15:00:33 merged: 2017-05-25 08:09:27

74. [18882](http://github.com/cms-sw/cmssw/pull/18882){:target="_blank"}  from **@smuzaffar**: Fixed unit test to use TAxis `core`  `dqm`  created: 2017-05-22 13:36:02 merged: 2017-05-23 09:48:40

75. [18881](http://github.com/cms-sw/cmssw/pull/18881){:target="_blank"}  from **@smuzaffar**: fixed unit test to work in IB env `alca`  created: 2017-05-22 13:21:45 merged: 2017-05-23 05:59:33

76. [18876](http://github.com/cms-sw/cmssw/pull/18876){:target="_blank"}  from **@cms-sw**: Fix unittest: avoid using shared /tmp/PixelBaryCentreTool directory `alca`  created: 2017-05-22 07:47:10 merged: 2017-05-22 10:25:10

77. [18874](http://github.com/cms-sw/cmssw/pull/18874){:target="_blank"}  from **@Dr15Jones**: Removed unused variable `core`  created: 2017-05-21 15:28:23 merged: 2017-05-22 06:15:40

78. [18870](http://github.com/cms-sw/cmssw/pull/18870){:target="_blank"}  from **@Dr15Jones**: Fix code indention in CTPPSPixelDQMSource `dqm`  created: 2017-05-20 15:45:37 merged: 2017-05-22 09:11:48

79. [18869](http://github.com/cms-sw/cmssw/pull/18869){:target="_blank"}  from **@fwyzard**: update L1REPACK configuration to use unpacked digis also for HCAL upgrades `l1`  `operations`  created: 2017-05-20 08:55:29 merged: 2017-05-21 08:14:17

80. [18867](http://github.com/cms-sw/cmssw/pull/18867){:target="_blank"}  from **@Dr15Jones**: Moved functions from anonymous namespace in CondCore/CondDB `db`  created: 2017-05-20 02:28:06 merged: 2017-05-24 07:42:49

81. [18865](http://github.com/cms-sw/cmssw/pull/18865){:target="_blank"}  from **@franzoni**: Drop-box metadata management: updates and introduce AAG, BSHP, EcalPed `alca`  `db`  created: 2017-05-19 18:31:12 merged: 2017-05-23 09:49:31

82. [18864](http://github.com/cms-sw/cmssw/pull/18864){:target="_blank"}  from **@bsunanda**: Phase2-hgx83 Bug fixes to two codes `dqm`  created: 2017-05-19 18:02:26 merged: 2017-05-24 14:03:22

83. [18862](http://github.com/cms-sw/cmssw/pull/18862){:target="_blank"}  from **@fioriNTU**: Disabling a plot making the GUI unstable  `dqm`  created: 2017-05-19 15:44:55 merged: 2017-05-25 08:06:44

84. [18861](http://github.com/cms-sw/cmssw/pull/18861){:target="_blank"}  from **@PFCal-dev**: HGCAL trigger fixes, optimizations and cleaning `l1`  `upgrade`  created: 2017-05-19 15:29:50 merged: 2017-05-23 07:19:26

85. [18860](http://github.com/cms-sw/cmssw/pull/18860){:target="_blank"}  from **@thomreis**: Add zero suppression mask for L1T uGMT capId3. `dqm`  created: 2017-05-19 14:58:49 merged: 2017-05-25 08:06:28

86. [18858](http://github.com/cms-sw/cmssw/pull/18858){:target="_blank"}  from **@mrodozov**: Importing missing piece of das_client `core`  created: 2017-05-19 14:25:26 merged: 2017-05-20 07:24:19

87. [18853](http://github.com/cms-sw/cmssw/pull/18853){:target="_blank"}  from **@kpedro88**: temporarily disable setNoiseFlagsQIE11 for AlCa `alca`  created: 2017-05-19 13:34:36 merged: 2017-05-23 06:00:29

88. [18852](http://github.com/cms-sw/cmssw/pull/18852){:target="_blank"}  from **@boudoul**: Deprecating Phase2 Tracker T3 and corresp. scenarios + Adding D18 (= D8 but with the non deprec. Tracker)  `geometry`  `operations`  `pdmv`  `upgrade`  created: 2017-05-19 13:30:33 merged: 2017-05-29 12:26:11

89. [18851](http://github.com/cms-sw/cmssw/pull/18851){:target="_blank"}  from **@mrodozov**: Fixing rootcling warning about missing dependencies  `analysis`  `reconstruction`  `upgrade`  created: 2017-05-19 10:36:30 merged: 2017-05-23 09:13:46

90. [18849](http://github.com/cms-sw/cmssw/pull/18849){:target="_blank"}  from **@mrodozov**: Fixing rootcling warning about missing dependencies `fastsim`  created: 2017-05-19 10:17:59 merged: 2017-05-21 08:14:42

91. [18848](http://github.com/cms-sw/cmssw/pull/18848){:target="_blank"}  from **@mrodozov**: Fixing rootcling warning about missing dependencies  `simulation`  created: 2017-05-19 10:17:16 merged: 2017-05-21 08:14:52

92. [18847](http://github.com/cms-sw/cmssw/pull/18847){:target="_blank"}  from **@mrodozov**: Fixing rootcling warning about missing dependencies `l1`  `upgrade`  created: 2017-05-19 10:16:36 merged: 2017-05-22 09:09:02

93. [18846](http://github.com/cms-sw/cmssw/pull/18846){:target="_blank"}  from **@perrozzi**: fix LHERunInfoProduct duplication `generators`  created: 2017-05-19 06:11:53 merged: 2017-05-28 08:03:02

94. [18842](http://github.com/cms-sw/cmssw/pull/18842){:target="_blank"}  from **@Dr15Jones**: Set a maximum number of waiting messages `core`  created: 2017-05-19 01:11:25 merged: 2017-05-20 12:04:59

95. [18840](http://github.com/cms-sw/cmssw/pull/18840){:target="_blank"}  from **@slava77**: optimize ECAL uncalibRecHit multifit (follow up to #18600) `reconstruction`  created: 2017-05-18 22:17:46 merged: 2017-05-20 12:05:20

96. [18837](http://github.com/cms-sw/cmssw/pull/18837){:target="_blank"}  from **@ianna**: Remove Legacy Code `geometry`  created: 2017-05-18 15:25:44 merged: 2017-05-19 07:24:25

97. [18833](http://github.com/cms-sw/cmssw/pull/18833){:target="_blank"}  from **@Dr15Jones**: Consolidate stream and thread printout `core`  created: 2017-05-18 14:09:40 merged: 2017-05-19 07:14:54

98. [18830](http://github.com/cms-sw/cmssw/pull/18830){:target="_blank"}  from **@folguera**: HLTL1MuonNoL2Selector fix to avoid the need of duplicating the class `hlt`  created: 2017-05-18 10:11:36 merged: 2017-05-19 07:16:10

99. [18829](http://github.com/cms-sw/cmssw/pull/18829){:target="_blank"}  from **@calabria**: Fix for the GEM validation: fix histogram folder `dqm`  created: 2017-05-18 10:01:09 merged: 2017-05-25 08:06:07

100. [18826](http://github.com/cms-sw/cmssw/pull/18826){:target="_blank"}  from **@ggovi**: Fix for PopCon BTransition module  `db`  created: 2017-05-18 07:46:04 merged: 2017-05-19 07:16:31

101. [18824](http://github.com/cms-sw/cmssw/pull/18824){:target="_blank"}  from **@rovere**: Full reco-material tuninig after PR 18651 `geometry`  created: 2017-05-18 07:06:00 merged: 2017-05-19 10:50:38

102. [18819](http://github.com/cms-sw/cmssw/pull/18819){:target="_blank"}  from **@Sam-Harper**: fillDescriptions fix for E/gamma Pixel Matching Modules `hlt`  `reconstruction`  created: 2017-05-17 22:40:22 merged: 2017-05-18 09:25:10

103. [18817](http://github.com/cms-sw/cmssw/pull/18817){:target="_blank"}  from **@JanFSchulte**: Update of PointSeededTrackingRegionsProducer to work in CMSSW 9 `reconstruction`  created: 2017-05-17 21:53:00 merged: 2017-05-24 08:05:40

104. [18816](http://github.com/cms-sw/cmssw/pull/18816){:target="_blank"}  from **@JanFSchulte**: Add fake trajectory to PixelTracks `reconstruction`  created: 2017-05-17 21:50:13 merged: 2017-05-25 08:05:52

105. [18815](http://github.com/cms-sw/cmssw/pull/18815){:target="_blank"}  from **@forthommel**: CTPPS: Small memory footprint reduction for the channels mapping handler `alca`  `db`  created: 2017-05-17 21:10:17 merged: 2017-05-29 20:29:56

106. [18813](http://github.com/cms-sw/cmssw/pull/18813){:target="_blank"}  from **@capalmer85**: Pcc producer phase1 rebase 92 x `alca`  `operations`  `reconstruction`  created: 2017-05-17 18:33:34 merged: 2017-05-18 09:46:51

107. [18808](http://github.com/cms-sw/cmssw/pull/18808){:target="_blank"}  from **@davidlange6**: speed up earlyDeleteSettings_cff.py by avoiding function calls `operations`  created: 2017-05-17 14:57:24 merged: 2017-05-31 09:16:29

108. [18807](http://github.com/cms-sw/cmssw/pull/18807){:target="_blank"}  from **@mandrenguyen**: Also store crossing frame in heavy-ion event overlay workflow `simulation`  created: 2017-05-17 14:44:39 merged: 2017-05-19 07:14:15

109. [18806](http://github.com/cms-sw/cmssw/pull/18806){:target="_blank"}  from **@Teemperor**: Remove dead header TrackingDataPrint.h `simulation`  created: 2017-05-17 14:42:11 merged: 2017-05-24 14:03:52

110. [18804](http://github.com/cms-sw/cmssw/pull/18804){:target="_blank"}  from **@Teemperor**: Remove compability header normalizedPhi.h `analysis`  `reconstruction`  created: 2017-05-17 14:07:49 merged: 2017-05-19 07:16:50

111. [18803](http://github.com/cms-sw/cmssw/pull/18803){:target="_blank"}  from **@Teemperor**: Added missing includes to Instantiate.h. `db`  created: 2017-05-17 13:56:16 merged: 2017-05-31 11:25:06

112. [18799](http://github.com/cms-sw/cmssw/pull/18799){:target="_blank"}  from **@Teemperor**: Add missing #include to DeDxHitInfo.h `reconstruction`  created: 2017-05-17 09:58:31 merged: 2017-05-18 07:54:36

113. [18796](http://github.com/cms-sw/cmssw/pull/18796){:target="_blank"}  from **@Teemperor**: Add missing includes to HGCRecHitComparison.h. `reconstruction`  `upgrade`  created: 2017-05-17 09:58:04 merged: 2017-05-18 09:25:20

114. [18795](http://github.com/cms-sw/cmssw/pull/18795){:target="_blank"}  from **@Teemperor**: Add missing include to LocalErrorBaseExtended.h `simulation`  created: 2017-05-17 09:57:53 merged: 2017-05-18 07:54:23

115. [18788](http://github.com/cms-sw/cmssw/pull/18788){:target="_blank"}  from **@Teemperor**: Make PythiaDecays.h a standalone header. `fastsim`  created: 2017-05-17 09:56:41 merged: 2017-05-18 07:54:09

116. [18787](http://github.com/cms-sw/cmssw/pull/18787){:target="_blank"}  from **@Teemperor**: Add missing includes to Phase2TrackerCOmmisioningDigi.h `reconstruction`  `upgrade`  created: 2017-05-17 09:56:30 merged: 2017-05-18 09:24:58

117. [18786](http://github.com/cms-sw/cmssw/pull/18786){:target="_blank"}  from **@Teemperor**: Fix clashes between translator function in PythonModule.h/.cc `core`  created: 2017-05-17 09:56:18 merged: 2017-05-18 09:30:29

118. [18785](http://github.com/cms-sw/cmssw/pull/18785){:target="_blank"}  from **@Teemperor**: Add missing includes to TrajectoryStopReasons.h `reconstruction`  created: 2017-05-17 09:56:05 merged: 2017-05-18 07:53:06

119. [18784](http://github.com/cms-sw/cmssw/pull/18784){:target="_blank"}  from **@Teemperor**: Add missing includes to SerializationManual.h `alca`  `db`  created: 2017-05-17 09:55:50 merged: 2017-05-18 09:25:41

120. [18779](http://github.com/cms-sw/cmssw/pull/18779){:target="_blank"}  from **@slava77**: recover multi-thread reproducibility in CTPPS diamond local track y position `reconstruction`  created: 2017-05-17 00:54:46 merged: 2017-05-18 07:52:54

121. [18778](http://github.com/cms-sw/cmssw/pull/18778){:target="_blank"}  from **@igv4321**: Turning on channel quality fetching from db `reconstruction`  created: 2017-05-16 22:46:19 merged: 2017-05-19 12:26:09

122. [18773](http://github.com/cms-sw/cmssw/pull/18773){:target="_blank"}  from **@slava77**:  lower pt cut on dedxhitinfo to 10 GeV and add dedx harmonic2 for pixel hits `reconstruction`  created: 2017-05-16 15:51:55 merged: 2017-05-21 08:15:00

123. [18768](http://github.com/cms-sw/cmssw/pull/18768){:target="_blank"}  from **@bsunanda**: Phase2-hgx81 Add ROOT scripts to study harvested plots `dqm`  created: 2017-05-16 13:23:31 merged: 2017-05-24 07:29:10

124. [18766](http://github.com/cms-sw/cmssw/pull/18766){:target="_blank"}  from **@mrodozov**: There is a missing dependency that is causing a build error `reconstruction`  created: 2017-05-16 13:04:42 merged: 2017-05-18 07:52:23

125. [18765](http://github.com/cms-sw/cmssw/pull/18765){:target="_blank"}  from **@civanch**: Added CPU benchmark `simulation`  created: 2017-05-16 12:24:15 merged: 2017-05-18 14:05:19

126. [18764](http://github.com/cms-sw/cmssw/pull/18764){:target="_blank"}  from **@Teemperor**: Add missing #include to DeDxHit.h. `reconstruction`  created: 2017-05-16 11:46:54 merged: 2017-05-18 09:36:20

127. [18763](http://github.com/cms-sw/cmssw/pull/18763){:target="_blank"}  from **@Teemperor**: Add missing Candidate.h/LeafCandidate.h includes to CandidateWithRef.h. `analysis`  `reconstruction`  created: 2017-05-16 11:46:30 merged: 2017-05-18 07:57:32

128. [18755](http://github.com/cms-sw/cmssw/pull/18755){:target="_blank"}  from **@MilanoBicocca-pix**: CMSSW 92X - Adding the possibility to select the PVs before the BeamSpot fit `alca`  `dqm`  `reconstruction`  created: 2017-05-15 23:04:34 merged: 2017-05-24 15:17:52

129. [18751](http://github.com/cms-sw/cmssw/pull/18751){:target="_blank"}  from **@gartung**: DQMServices/Core: Change DQMEDHarvester to an edm::one::EDProducer and add alias to EDProducer from DQMEDHarvester `alca`  `dqm`  `fastsim`  `generators`  `geometry`  `l1`  `upgrade`  created: 2017-05-15 18:25:20 merged: 2017-05-27 07:54:11

130. [18743](http://github.com/cms-sw/cmssw/pull/18743){:target="_blank"}  from **@dildick**: CSC TP bugfixes for high PU running `dqm`  `l1`  `upgrade`  created: 2017-05-15 16:21:24 merged: 2017-05-18 14:46:26

131. [18739](http://github.com/cms-sw/cmssw/pull/18739){:target="_blank"}  from **@arizzi**: Pack triggerobject standalone and photons/muon updated packing for miniaod `analysis`  `operations`  `reconstruction`  created: 2017-05-15 14:50:08 merged: 2017-06-01 10:09:38

132. [18728](http://github.com/cms-sw/cmssw/pull/18728){:target="_blank"}  from **@VinInn**: CA for Phase2 tracking + few more smaller-impact optimizations `reconstruction`  `upgrade`  created: 2017-05-14 16:48:09 merged: 2017-05-23 06:03:51

133. [18724](http://github.com/cms-sw/cmssw/pull/18724){:target="_blank"}  from **@VinInn**: make const correct muon seeding in tracking `reconstruction`  created: 2017-05-13 10:12:27 merged: 2017-05-22 11:57:29

134. [18718](http://github.com/cms-sw/cmssw/pull/18718){:target="_blank"}  from **@CTPPS**: CTPPS: DQM configuration fix `dqm`  created: 2017-05-12 18:57:18 merged: 2017-05-28 08:03:38

135. [18711](http://github.com/cms-sw/cmssw/pull/18711){:target="_blank"}  from **@akhukhun**: adjust HF TP emulator and compression LUTs `l1`  created: 2017-05-12 13:15:13 merged: 2017-05-31 06:42:46

136. [18696](http://github.com/cms-sw/cmssw/pull/18696){:target="_blank"}  from **@jhgoh**: MuonCaloCompatibility fix to reduce number of file handle `reconstruction`  created: 2017-05-11 14:27:39 merged: 2017-05-22 10:24:54

137. [18689](http://github.com/cms-sw/cmssw/pull/18689){:target="_blank"}  from **@archiron**: miniAODIsolation_91X_V2 `dqm`  created: 2017-05-11 12:15:18 merged: 2017-05-27 07:53:56

138. [18684](http://github.com/cms-sw/cmssw/pull/18684){:target="_blank"}  from **@mandrenguyen**: Remove HF/Voronoi subtraction for jets in heavy ions and disable centrality bin producer `dqm`  `reconstruction`  created: 2017-05-10 22:30:43 merged: 2017-05-20 12:05:48

139. [18646](http://github.com/cms-sw/cmssw/pull/18646){:target="_blank"}  from **@abaty**: First Round of Phase 1 Tracking changes for Heavy Ions `reconstruction`  created: 2017-05-09 18:54:04 merged: 2017-05-30 20:40:36

140. [18638](http://github.com/cms-sw/cmssw/pull/18638){:target="_blank"}  from **@mtosi**: add NumberOfEventsPerLS EDFilter `analysis`  created: 2017-05-09 15:26:19 merged: 2017-05-30 10:36:19

141. [18634](http://github.com/cms-sw/cmssw/pull/18634){:target="_blank"}  from **@smuzaffar**: preparing for dasgoclient: implement get_value in cmssw_das_client `core`  created: 2017-05-09 14:28:40 merged: 2017-05-18 09:37:50

142. [18548](http://github.com/cms-sw/cmssw/pull/18548){:target="_blank"}  from **@bjmarsh**: Add mini-isolation for leptons and a new collection of Isolated Tracks in MiniAOD `analysis`  `reconstruction`  created: 2017-05-02 20:17:14 merged: 2017-05-23 09:44:46

143. [18540](http://github.com/cms-sw/cmssw/pull/18540){:target="_blank"}  from **@enochnotsocool**: Raw ADC value computation efficiency fix `dqm`  created: 2017-05-02 13:19:37 merged: 2017-05-24 14:25:20

144. [18531](http://github.com/cms-sw/cmssw/pull/18531){:target="_blank"}  from **@dimattia**: DQM quality monitor for SiStrip Gain (G2) from Multi Run Harvesting  `alca`  created: 2017-05-01 14:20:02 merged: 2017-06-01 12:43:22

145. [18517](http://github.com/cms-sw/cmssw/pull/18517){:target="_blank"}  from **@kkotov**: Moving the Prescale ES producer to the new parser and deleting old XML parser `l1`  created: 2017-04-28 14:28:46 merged: 2017-05-31 08:15:10

146. [18447](http://github.com/cms-sw/cmssw/pull/18447){:target="_blank"}  from **@enochnotsocool**: Digi occupancy plot rotated + FED range adjusted (91X) `dqm`  created: 2017-04-24 09:51:29 merged: 2017-05-31 10:50:22

147. [18364](http://github.com/cms-sw/cmssw/pull/18364){:target="_blank"}  from **@mtosi**: add HLT HCAL DQM/Validation `dqm`  `hlt`  created: 2017-04-14 14:37:24 merged: 2017-05-31 10:52:20

148. [18236](http://github.com/cms-sw/cmssw/pull/18236){:target="_blank"}  from **@CMS-HGCAL**: Collected HGCal reconstruction changes `reconstruction`  `upgrade`  created: 2017-04-06 07:54:26 merged: 2017-05-28 08:05:01

#### CMSDIST Changes between Tags REL/CMSSW_9_2_0_patch5/slc6_amd64_gcc530 and REL/CMSSW_9_2_1/slc6_amd64_gcc530:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_9_2_0_patch5/slc6_amd64_gcc530...REL/CMSSW_9_2_1/slc6_amd64_gcc530)



1. [3081](http://github.com/cms-sw/cmsdist/pull/3081){:target="_blank"}  from **@cms-sw**: Use new build rule tag V05-05-24 created: 2017-06-01 14:00:10 merged: 2017-06-01 14:00:18

2. [3077](http://github.com/cms-sw/cmsdist/pull/3077){:target="_blank"}  from **@davidlange6**: Adding hep_ml, rep, uncertainties tools - fixing python path for xrootd created: 2017-05-31 14:54:56 merged: 2017-06-01 07:45:34

3. [3072](http://github.com/cms-sw/cmsdist/pull/3072){:target="_blank"}  from **@mrodozov**: Updating utm.spec for new tag usage created: 2017-05-29 08:33:09 merged: 2017-06-01 17:47:30

4. [3068](http://github.com/cms-sw/cmsdist/pull/3068){:target="_blank"}  from **@TaiSakuma**: update pandas version to 0.20.1 for 9_2_X created: 2017-05-24 10:37:21 merged: 2017-05-26 10:34:38

5. [3064](http://github.com/cms-sw/cmsdist/pull/3064){:target="_blank"}  from **@smuzaffar**: updated cms-git-tools which contains new git-cms-checkout-topic created: 2017-05-23 09:32:38 merged: 2017-05-26 10:34:52

6. [3055](http://github.com/cms-sw/cmsdist/pull/3055){:target="_blank"}  from **@cms-sw**: Update data-L1Trigger-L1TCalorimeter.spec created: 2017-05-19 07:48:13 merged: 2017-05-19 08:55:39

7. [3040](http://github.com/cms-sw/cmsdist/pull/3040){:target="_blank"}  from **@davidlange6**: add prwlock tool created: 2017-05-15 13:27:59 merged: 2017-05-19 10:41:33

8. [3013](http://github.com/cms-sw/cmsdist/pull/3013){:target="_blank"}  from **@mkirsano**: Upgrade pythia8 to 226 created: 2017-05-08 09:54:52 merged: 2017-05-19 10:40:29
