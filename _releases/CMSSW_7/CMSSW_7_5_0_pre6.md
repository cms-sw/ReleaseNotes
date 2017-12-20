---
layout: post
rel_link:  "7_5_0_pre6"
title:  "CMSSW_7_5_0_pre6"
date:   2015-06-22 19:58:20
categories: cmssw
relmajor: 7
relminor: 5
relsubminor: 0
relpre: _pre6
---

# CMSSW_7_5_0_pre6
#### Changes since CMSSW_7_5_0_pre5:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_5_0_pre5...CMSSW_7_5_0_pre6)



1. [9679](http://github.com/cms-sw/cmssw/pull/9679){:target="_blank"}  from **@diguida**: Remove PoolDBESSource for QGL from cfi file and update Global Tags for RelVals `alca`  `reconstruction`  created: 2015-06-19 08:57:18 merged: 2015-06-22 19:54:34

2. [9649](http://github.com/cms-sw/cmssw/pull/9649){:target="_blank"}  from **@mark-grimes**: Fix edmPythonSearch to also look in modules from process.load(...)  `core`  created: 2015-06-16 23:36:01 merged: 2015-06-20 16:36:39

3. [9691](http://github.com/cms-sw/cmssw/pull/9691){:target="_blank"}  from **@gartung**: Clang SA fix partial match of ESD class name `core`  created: 2015-06-19 19:29:45 merged: 2015-06-20 16:34:20

4. [9683](http://github.com/cms-sw/cmssw/pull/9683){:target="_blank"}  from **@wddgit**: Bug fix. Fix moduleDescription function `core`  created: 2015-06-19 14:27:24 merged: 2015-06-20 09:04:32

5. [9645](http://github.com/cms-sw/cmssw/pull/9645){:target="_blank"}  from **@MilanoBicocca-pix**: Add vtx smearing parameters from run 247324 `operations`  `simulation`  created: 2015-06-16 16:59:39 merged: 2015-06-19 17:53:17

6. [9682](http://github.com/cms-sw/cmssw/pull/9682){:target="_blank"}  from **@jiafulow**: Update TrackingParticleFactory::vectorIsInsideVolume(...) function in TrackingTruthAccumulator `simulation`  created: 2015-06-19 13:27:41 merged: 2015-06-19 17:42:04

7. [9688](http://github.com/cms-sw/cmssw/pull/9688){:target="_blank"}  from **@ianna**: Hcal Parameters ES Producer `geometry`  created: 2015-06-19 15:26:03 merged: 2015-06-19 17:41:53

8. [9459](http://github.com/cms-sw/cmssw/pull/9459){:target="_blank"}  from **@jhgoh**: Muon Common Isolation Framework and Versionned ID `analysis`  `reconstruction`  created: 2015-06-04 18:58:02 merged: 2015-06-19 15:48:15

9. [9672](http://github.com/cms-sw/cmssw/pull/9672){:target="_blank"}  from **@mdhildreth**: 75Xx pixel db ineff premix update `simulation`  created: 2015-06-18 21:06:39 merged: 2015-06-19 07:42:47

10. [9640](http://github.com/cms-sw/cmssw/pull/9640){:target="_blank"}  from **@ahinzmann**: Fix ConfigEditor to handle VPSet which have no label `core`  created: 2015-06-16 13:13:09 merged: 2015-06-19 07:36:16

11. [9671](http://github.com/cms-sw/cmssw/pull/9671){:target="_blank"}  from **@wddgit**: Make skeletons generate stream or one types `core`  created: 2015-06-18 16:12:29 merged: 2015-06-19 07:34:01

12. [9663](http://github.com/cms-sw/cmssw/pull/9663){:target="_blank"}  from **@CmsHI**: make sure that the SuperClusters are available in AOD for Heavy Ions `reconstruction`  created: 2015-06-18 05:54:54 merged: 2015-06-18 18:37:06

13. [9502](http://github.com/cms-sw/cmssw/pull/9502){:target="_blank"}  from **@jingyucms**: add cfg for l1tstage1 dqm running on live `dqm`  created: 2015-06-08 13:28:03 merged: 2015-06-18 18:35:26

14. [9563](http://github.com/cms-sw/cmssw/pull/9563){:target="_blank"}  from **@rjwang**: update CSCTF LUTs configuration for ME- `dqm`  created: 2015-06-11 13:04:27 merged: 2015-06-18 18:35:04

15. [9631](http://github.com/cms-sw/cmssw/pull/9631){:target="_blank"}  from **@HuguesBrun**: update the same sign directory in the Higgs HLT DQM  `dqm`  created: 2015-06-16 08:02:15 merged: 2015-06-18 18:27:32

16. [9654](http://github.com/cms-sw/cmssw/pull/9654){:target="_blank"}  from **@arizzi**: Fix bug spoling PV sorting on W' and Z'. Override default ptMax cut `reconstruction`  created: 2015-06-17 10:26:53 merged: 2015-06-18 18:22:19

17. [9436](http://github.com/cms-sw/cmssw/pull/9436){:target="_blank"}  from **@mharrend**: HerwigPP: Added two processes `generators`  created: 2015-06-03 16:03:28 merged: 2015-06-18 14:47:46

18. [9605](http://github.com/cms-sw/cmssw/pull/9605){:target="_blank"}  from **@vanbesien**: Deleted many files that seem obsolete to me `dqm`  created: 2015-06-13 13:22:14 merged: 2015-06-18 14:47:25

19. [8890](http://github.com/cms-sw/cmssw/pull/8890){:target="_blank"}  from **@dildick**: GEM-CSC integrated local trigger (part I) `l1`  `simulation`  created: 2015-04-28 05:37:59 merged: 2015-06-18 06:16:55

20. [9661](http://github.com/cms-sw/cmssw/pull/9661){:target="_blank"}  from **@ggovi**: fix for the iov sequence iterators as delivered by the caching in pages `db`  created: 2015-06-17 19:51:41 merged: 2015-06-18 06:16:17

21. [9441](http://github.com/cms-sw/cmssw/pull/9441){:target="_blank"}  from **@avetisya**: Adding prescale index and L1 tables with per-type data to 75X `hlt`  created: 2015-06-04 09:11:58 merged: 2015-06-18 06:14:40

22. [9662](http://github.com/cms-sw/cmssw/pull/9662){:target="_blank"}  from **@wddgit**: Bug fix. Add function to get top level PSet `core`  created: 2015-06-17 20:58:30 merged: 2015-06-18 06:14:05

23. [9652](http://github.com/cms-sw/cmssw/pull/9652){:target="_blank"}  from **@ianna**: Hcal DB Parameters test `geometry`  created: 2015-06-17 08:26:17 merged: 2015-06-17 19:36:22

24. [9567](http://github.com/cms-sw/cmssw/pull/9567){:target="_blank"}  from **@alkaloge**: Ddt skims 75x `pdmv`  created: 2015-06-11 15:29:13 merged: 2015-06-17 18:27:29

25. [9647](http://github.com/cms-sw/cmssw/pull/9647){:target="_blank"}  from **@wmtan**: Add informative exception for hash collision `core`  created: 2015-06-16 20:53:29 merged: 2015-06-17 18:27:10

26. [9648](http://github.com/cms-sw/cmssw/pull/9648){:target="_blank"}  from **@Dr15Jones**: Fix a race condition in edm::Ref `core`  created: 2015-06-16 21:23:50 merged: 2015-06-17 18:27:00

27. [9657](http://github.com/cms-sw/cmssw/pull/9657){:target="_blank"}  from **@fwyzard**: hltConfigFromDB: increase the thread stack size `hlt`  created: 2015-06-17 13:43:23 merged: 2015-06-17 18:26:37

28. [9571](http://github.com/cms-sw/cmssw/pull/9571){:target="_blank"}  from **@alberto-sanchez**: Onia2mumu `analysis`  created: 2015-06-11 17:05:29 merged: 2015-06-17 18:23:42

29. [9595](http://github.com/cms-sw/cmssw/pull/9595){:target="_blank"}  from **@lveldere**: thorough clean-up of TrackCandidate producer `fastsim`  created: 2015-06-12 13:28:07 merged: 2015-06-17 07:52:51

30. [9636](http://github.com/cms-sw/cmssw/pull/9636){:target="_blank"}  from **@cschomak**: Switched to GeometryRecoDB in geometryCompatisonTemplates.py `alca`  created: 2015-06-16 11:50:13 merged: 2015-06-17 07:52:29

31. [9437](http://github.com/cms-sw/cmssw/pull/9437){:target="_blank"}  from **@nsmith-**: Bugfix in L1 GCT ET sums hardware emulator `l1`  created: 2015-06-03 17:40:32 merged: 2015-06-17 07:47:35

32. [9498](http://github.com/cms-sw/cmssw/pull/9498){:target="_blank"}  from **@smuzaffar**: move AdaptorConfig EDM Plugin out of Capabilities `core`  created: 2015-06-08 13:03:37 merged: 2015-06-17 07:47:25

33. [9637](http://github.com/cms-sw/cmssw/pull/9637){:target="_blank"}  from **@heilman**: Check for valid pointers in GetJetConstituentsQuick (Port of PR#752 from 72X) `reconstruction`  created: 2015-06-16 12:18:16 merged: 2015-06-17 07:46:29

34. [9599](http://github.com/cms-sw/cmssw/pull/9599){:target="_blank"}  from **@davidlt**: Add missing references `reconstruction`  created: 2015-06-12 16:54:50 merged: 2015-06-16 16:27:32

35. [9274](http://github.com/cms-sw/cmssw/pull/9274){:target="_blank"}  from **@thuer**: Relval samples for Sherpa+Blackhat and Sherpa+OpenLoops `generators`  `pdmv`  created: 2015-05-26 12:45:05 merged: 2015-06-16 13:37:24

36. [9570](http://github.com/cms-sw/cmssw/pull/9570){:target="_blank"}  from **@felicepantaleo**: Unique TFormula name `alca`  `db`  created: 2015-06-11 16:37:49 merged: 2015-06-16 13:06:57

37. [9596](http://github.com/cms-sw/cmssw/pull/9596){:target="_blank"}  from **@dmcinerney**: integrated 3D geometry comparison visualization into all-in-one tool `alca`  created: 2015-06-12 15:34:11 merged: 2015-06-16 13:06:46

38. [9548](http://github.com/cms-sw/cmssw/pull/9548){:target="_blank"}  from **@emanueledimarco**: Updated Z->ee skim for Run2 `pdmv`  created: 2015-06-10 16:52:40 merged: 2015-06-16 13:05:57

39. [9624](http://github.com/cms-sw/cmssw/pull/9624){:target="_blank"}  from **@jmduarte**: bug fix for ECAL HLT validation workflow 75X `dqm`  created: 2015-06-15 14:27:13 merged: 2015-06-16 13:04:26

40. [9586](http://github.com/cms-sw/cmssw/pull/9586){:target="_blank"}  from **@MilanoBicocca-pix**: Fix inconsistency in BeamSpot IOV creation in PCL `alca`  created: 2015-06-12 08:57:57 merged: 2015-06-16 07:47:06

41. [9600](http://github.com/cms-sw/cmssw/pull/9600){:target="_blank"}  from **@hroskes**: Fixes for parallel offline and track splitting validations `alca`  created: 2015-06-12 18:32:02 merged: 2015-06-16 07:41:47

42. [9487](http://github.com/cms-sw/cmssw/pull/9487){:target="_blank"}  from **@kkrajczar**: Fix for crash in 140.0: remove PostLS1_HI customization from legacy HI workflow `pdmv`  created: 2015-06-07 11:02:16 merged: 2015-06-16 06:17:18

43. [9522](http://github.com/cms-sw/cmssw/pull/9522){:target="_blank"}  from **@JetMETdqmval**: apply fix in filling of PFCandidate METPhi histograms `dqm`  created: 2015-06-09 11:50:34 merged: 2015-06-16 06:17:11

44. [9415](http://github.com/cms-sw/cmssw/pull/9415){:target="_blank"}  from **@ndaci**: Add DisplacedMuJet, add a new path in METplusTrack, comment out unnec `dqm`  created: 2015-06-02 16:11:18 merged: 2015-06-16 06:11:59

45. [9591](http://github.com/cms-sw/cmssw/pull/9591){:target="_blank"}  from **@mandrenguyen**: Reduced pTmin of pixel pairs from 4 to 1 GeV in HI reco `reconstruction`  created: 2015-06-12 11:56:36 merged: 2015-06-16 06:11:31

46. [9614](http://github.com/cms-sw/cmssw/pull/9614){:target="_blank"}  from **@smorovic**: Fixes to JSONMonotoring (75X) `hlt`  created: 2015-06-14 11:07:47 merged: 2015-06-16 06:06:26

47. [9537](http://github.com/cms-sw/cmssw/pull/9537){:target="_blank"}  from **@lveldere**: FastSim : HF : Shower Library: safe handling of pointers `fastsim`  created: 2015-06-10 08:39:11 merged: 2015-06-15 12:22:17

48. [9593](http://github.com/cms-sw/cmssw/pull/9593){:target="_blank"}  from **@diguida**: Updated GT for online DQM (75X version) `dqm`  created: 2015-06-12 12:57:51 merged: 2015-06-15 12:17:23

49. [9565](http://github.com/cms-sw/cmssw/pull/9565){:target="_blank"}  from **@rappoccio**: Updating DQM to latest HLT path name `dqm`  created: 2015-06-11 13:55:49 merged: 2015-06-14 12:26:55

50. [9583](http://github.com/cms-sw/cmssw/pull/9583){:target="_blank"}  from **@cms-tsg-storm**: Further HLT updates on top of 744 (75X) `hlt`  created: 2015-06-12 06:33:24 merged: 2015-06-14 11:36:37

51. [9590](http://github.com/cms-sw/cmssw/pull/9590){:target="_blank"}  from **@ianna**: DD Offline DB Loader Cleanup `geometry`  created: 2015-06-12 11:44:34 merged: 2015-06-14 11:36:29

52. [9594](http://github.com/cms-sw/cmssw/pull/9594){:target="_blank"}  from **@battibass**: Adding matrix worflows for PR#9469 `pdmv`  created: 2015-06-12 13:12:33 merged: 2015-06-14 11:36:22

53. [9330](http://github.com/cms-sw/cmssw/pull/9330){:target="_blank"}  from **@mandrenguyen**: Update default vtx smearing for PbPb to 2015 expectation `operations`  `pdmv`  `simulation`  created: 2015-05-29 11:01:48 merged: 2015-06-14 11:35:28

54. [9481](http://github.com/cms-sw/cmssw/pull/9481){:target="_blank"}  from **@kfiekas**: HCAL 25ns reco update `reconstruction`  created: 2015-06-05 20:09:12 merged: 2015-06-14 11:35:16

55. [9573](http://github.com/cms-sw/cmssw/pull/9573){:target="_blank"}  from **@parbol**: Updates names for paths with BTAGs. `dqm`  created: 2015-06-11 18:25:49 merged: 2015-06-14 11:35:06

56. [9602](http://github.com/cms-sw/cmssw/pull/9602){:target="_blank"}  from **@slava77**: add checks if trajectory has hits before accessing them `reconstruction`  created: 2015-06-12 20:16:07 merged: 2015-06-14 11:34:25

57. [9589](http://github.com/cms-sw/cmssw/pull/9589){:target="_blank"}  from **@fwyzard**: hltDumpStream update (75x) `hlt`  created: 2015-06-12 10:41:38 merged: 2015-06-12 13:41:31

58. [9333](http://github.com/cms-sw/cmssw/pull/9333){:target="_blank"}  from **@cms-met**: Update of the MVAMET algorithm plus use of new training files `reconstruction`  created: 2015-05-29 13:02:32 merged: 2015-06-12 10:38:30

59. [9394](http://github.com/cms-sw/cmssw/pull/9394){:target="_blank"}  from **@capalmer85**: Add luminibble unpacker `daq`  `operations`  created: 2015-06-01 22:14:22 merged: 2015-06-12 09:20:40

60. [9463](http://github.com/cms-sw/cmssw/pull/9463){:target="_blank"}  from **@fioriNTU**: FPix Occupancy `dqm`  created: 2015-06-04 20:41:49 merged: 2015-06-12 06:33:55

61. [9512](http://github.com/cms-sw/cmssw/pull/9512){:target="_blank"}  from **@gpetruc**: Fixes for Tag&Probe in 7.5.X (fix of #8801) `analysis`  `reconstruction`  created: 2015-06-08 16:37:23 merged: 2015-06-12 06:33:40

62. [9559](http://github.com/cms-sw/cmssw/pull/9559){:target="_blank"}  from **@mandrenguyen**: Turn off calo muons in HI reco sequence `reconstruction`  created: 2015-06-11 11:17:12 merged: 2015-06-12 06:33:29

63. [9531](http://github.com/cms-sw/cmssw/pull/9531){:target="_blank"}  from **@igv4321**: Forward port of changes in PR #9395 `analysis`  `reconstruction`  `simulation`  created: 2015-06-09 22:07:36 merged: 2015-06-12 06:31:29

64. [9560](http://github.com/cms-sw/cmssw/pull/9560){:target="_blank"}  from **@MilanoBicocca-pix**: [BeamSpot] update cfg to rerun track and PV fitting before BS determination `alca`  `reconstruction`  created: 2015-06-11 12:15:24 merged: 2015-06-12 06:30:32

65. [9527](http://github.com/cms-sw/cmssw/pull/9527){:target="_blank"}  from **@dmitrijus**: Fixed array overflow by ignoring the out-of-bounds value ... `dqm`  created: 2015-06-09 15:34:09 merged: 2015-06-11 14:12:11

66. [9449](http://github.com/cms-sw/cmssw/pull/9449){:target="_blank"}  from **@makortel**: Merge TrackerLayerIdAccessor to TrackerTopology `geometry`  `reconstruction`  created: 2015-06-04 12:36:53 merged: 2015-06-11 14:10:50

67. [9552](http://github.com/cms-sw/cmssw/pull/9552){:target="_blank"}  from **@hroskes**: Offline validation ROOT6 `alca`  created: 2015-06-10 18:42:59 merged: 2015-06-11 12:41:35

68. [9469](http://github.com/cms-sw/cmssw/pull/9469){:target="_blank"}  from **@battibass**: Cosmic GEN configuration with tighter pointing cuts `generators`  created: 2015-06-05 11:22:59 merged: 2015-06-11 12:37:17

69. [9543](http://github.com/cms-sw/cmssw/pull/9543){:target="_blank"}  from **@threus**: strip online DQM config (75X): activated HLT selection for cosmics and pp collisions `dqm`  created: 2015-06-10 13:29:13 merged: 2015-06-11 12:37:06

70. [9547](http://github.com/cms-sw/cmssw/pull/9547){:target="_blank"}  from **@davidlt**: DQM/L1TMonitor: definite static const int members `dqm`  created: 2015-06-10 15:27:52 merged: 2015-06-11 12:36:51

71. [9557](http://github.com/cms-sw/cmssw/pull/9557){:target="_blank"}  from **@ggovi**: Fix for import tool - ensured correct return value for empty IOV ranges `db`  created: 2015-06-11 07:38:15 merged: 2015-06-11 12:36:31

72. [9525](http://github.com/cms-sw/cmssw/pull/9525){:target="_blank"}  from **@kropiv**: change primaryVertexCut for fast displaced Vertex reconstruction from `reconstruction`  created: 2015-06-09 13:59:14 merged: 2015-06-11 07:36:27

73. [9530](http://github.com/cms-sw/cmssw/pull/9530){:target="_blank"}  from **@ahinzmann**: fix ECAL cluster input for PFCaloJets `reconstruction`  created: 2015-06-09 21:56:08 merged: 2015-06-11 07:31:42

74. [9389](http://github.com/cms-sw/cmssw/pull/9389){:target="_blank"}  from **@thomreis**: Fix for Egamma HLT RelVal `dqm`  created: 2015-06-01 17:27:15 merged: 2015-06-10 19:35:01

75. [9541](http://github.com/cms-sw/cmssw/pull/9541){:target="_blank"}  from **@davidlt**: Resolve null-dereference and enable Linux containers `core`  created: 2015-06-10 12:58:36 merged: 2015-06-10 19:34:24

76. [9083](http://github.com/cms-sw/cmssw/pull/9083){:target="_blank"}  from **@pietverwilligen**: Gemcsc segment 75X `reconstruction`  `simulation`  created: 2015-05-14 10:45:33 merged: 2015-06-10 11:42:32

77. [9514](http://github.com/cms-sw/cmssw/pull/9514){:target="_blank"}  from **@fwyzard**: add support for ConfDB v2 to hltConfigFromDB `hlt`  created: 2015-06-08 17:12:38 merged: 2015-06-10 11:36:34

78. [9279](http://github.com/cms-sw/cmssw/pull/9279){:target="_blank"}  from **@abbiendi**: complete the recoMuon validation workflow for cosmic muons `dqm`  `operations`  `reconstruction`  `simulation`  created: 2015-05-26 16:47:23 merged: 2015-06-10 11:36:13

79. [9519](http://github.com/cms-sw/cmssw/pull/9519){:target="_blank"}  from **@makortel**: Fixes to vertex validation `dqm`  created: 2015-06-09 09:35:53 merged: 2015-06-10 11:34:23

80. [9406](http://github.com/cms-sw/cmssw/pull/9406){:target="_blank"}  from **@cms-tsg-storm**: HLT updates on top of the menu in CMSSW_744 - 75X `hlt`  `l1`  created: 2015-06-02 13:36:31 merged: 2015-06-10 11:29:47

81. [9526](http://github.com/cms-sw/cmssw/pull/9526){:target="_blank"}  from **@clacaputo**: BUGFIX to ME0 SimHit `geometry`  `reconstruction`  `simulation`  created: 2015-06-09 13:59:51 merged: 2015-06-10 11:26:41

82. [9529](http://github.com/cms-sw/cmssw/pull/9529){:target="_blank"}  from **@eavdeeva**: add script PlotFromMillepedeRes `alca`  created: 2015-06-09 20:18:56 merged: 2015-06-10 11:21:37

83. [9409](http://github.com/cms-sw/cmssw/pull/9409){:target="_blank"}  from **@zc11**: Add HLT_FullTrack DQM for low PU `dqm`  created: 2015-06-02 14:21:18 merged: 2015-06-09 19:42:03

84. [9524](http://github.com/cms-sw/cmssw/pull/9524){:target="_blank"}  from **@makortel**: Reduce MultiTrackValidator memory use `dqm`  created: 2015-06-09 12:39:57 merged: 2015-06-09 19:41:41

85. [9499](http://github.com/cms-sw/cmssw/pull/9499){:target="_blank"}  from **@smuzaffar**: move TrackTSelectorAnalyzer EDM Plugin out of Capabilities `analysis`  created: 2015-06-08 13:04:12 merged: 2015-06-09 19:38:15

86. [9518](http://github.com/cms-sw/cmssw/pull/9518){:target="_blank"}  from **@davidlt**: DataFormats/Candidate: remove duplicate selection rule `analysis`  `reconstruction`  created: 2015-06-09 07:45:38 merged: 2015-06-09 19:36:16

87. [8771](http://github.com/cms-sw/cmssw/pull/8771){:target="_blank"}  from **@serdweg**: Updates to the DT calibration package `alca`  created: 2015-04-17 11:14:59 merged: 2015-06-09 14:28:46

88. [9443](http://github.com/cms-sw/cmssw/pull/9443){:target="_blank"}  from **@davidlange6**: Reduce fastsim memory profile a bit `fastsim`  created: 2015-06-04 09:57:23 merged: 2015-06-09 14:27:43

89. [9465](http://github.com/cms-sw/cmssw/pull/9465){:target="_blank"}  from **@ianna**: DD Core Cleanup `alca`  `dqm`  `geometry`  `simulation`  created: 2015-06-05 08:23:51 merged: 2015-06-09 14:27:27

90. [9440](http://github.com/cms-sw/cmssw/pull/9440){:target="_blank"}  from **@BetterWang**: HI EP and DQM update `dqm`  `hlt`  `reconstruction`  created: 2015-06-04 08:42:19 merged: 2015-06-09 14:23:15

91. [9457](http://github.com/cms-sw/cmssw/pull/9457){:target="_blank"}  from **@threus**: Remove module-level plots from online Strip DQM  `dqm`  created: 2015-06-04 16:13:29 merged: 2015-06-09 14:22:56

92. [9496](http://github.com/cms-sw/cmssw/pull/9496){:target="_blank"}  from **@dmitrijus**: Fix array underflow issue in DQM/HcalMonitorTasks. `dqm`  created: 2015-06-08 12:42:21 merged: 2015-06-09 14:22:25

93. [9509](http://github.com/cms-sw/cmssw/pull/9509){:target="_blank"}  from **@deguio**: merge instead of adding in case the CanExtendAllAxis is set `dqm`  created: 2015-06-08 15:15:12 merged: 2015-06-09 11:06:38

94. [9511](http://github.com/cms-sw/cmssw/pull/9511){:target="_blank"}  from **@mmusich**: Fixing AlCaRecoTriggerBits reading/writing for condDBv2  `db`  `hlt`  created: 2015-06-08 16:24:22 merged: 2015-06-09 11:04:38

95. [9467](http://github.com/cms-sw/cmssw/pull/9467){:target="_blank"}  from **@apfeiffer1**: update conddb tool to improve handling/showing of time-types/time-stamps `db`  created: 2015-06-05 10:15:14 merged: 2015-06-08 20:52:38

96. [9503](http://github.com/cms-sw/cmssw/pull/9503){:target="_blank"}  from **@dgonzal**: fixed parameters for fastsime tune `fastsim`  created: 2015-06-08 13:36:09 merged: 2015-06-08 20:52:32

97. [9506](http://github.com/cms-sw/cmssw/pull/9506){:target="_blank"}  from **@dmitrijus**: Properly zero terminate a string in DQMEventInfo. `dqm`  created: 2015-06-08 14:26:21 merged: 2015-06-08 20:46:27

98. [9507](http://github.com/cms-sw/cmssw/pull/9507){:target="_blank"}  from **@davidlt**: CondFormats/Alignment: remove unused selection rules `alca`  `db`  created: 2015-06-08 14:42:19 merged: 2015-06-08 20:44:16

99. [9505](http://github.com/cms-sw/cmssw/pull/9505){:target="_blank"}  from **@davidlt**: DataFormats/Math: remove unused selection rules `reconstruction`  created: 2015-06-08 14:24:01 merged: 2015-06-08 20:44:06

100. [9501](http://github.com/cms-sw/cmssw/pull/9501){:target="_blank"}  from **@davidlt**: TrackingTools/TrajectoryState: clean up selection rules `reconstruction`  created: 2015-06-08 13:27:13 merged: 2015-06-08 20:43:52

101. [9497](http://github.com/cms-sw/cmssw/pull/9497){:target="_blank"}  from **@davidlt**: SimDataFormats/Vertex: clean unused pattern-based selection rules `simulation`  created: 2015-06-08 13:02:08 merged: 2015-06-08 20:43:27

102. [9492](http://github.com/cms-sw/cmssw/pull/9492){:target="_blank"}  from **@davidlt**: Clean unsused selection rules (ROOT 6.04.00) `analysis`  `reconstruction`  created: 2015-06-08 10:31:38 merged: 2015-06-08 20:43:14

103. [9495](http://github.com/cms-sw/cmssw/pull/9495){:target="_blank"}  from **@davidlt**: SimDataFormats/TrackingAnalysis: unused selection rules cleanup `simulation`  created: 2015-06-08 12:17:07 merged: 2015-06-08 20:42:47

104. [9256](http://github.com/cms-sw/cmssw/pull/9256){:target="_blank"}  from **@shervin86**: Electron stream plugin fix `alca`  created: 2015-05-25 06:51:37 merged: 2015-06-08 15:43:31

105. [9313](http://github.com/cms-sw/cmssw/pull/9313){:target="_blank"}  from **@cfmcginn**: Added basicjet template for JetCorrectionProducer (heavy ions hlt use) `analysis`  created: 2015-05-28 13:13:19 merged: 2015-06-08 15:28:03

106. [9340](http://github.com/cms-sw/cmssw/pull/9340){:target="_blank"}  from **@jruizvar**: New dqm modules for PFHT paths (rebase of #9028) `dqm`  created: 2015-05-29 16:56:40 merged: 2015-06-08 15:08:21

107. [9355](http://github.com/cms-sw/cmssw/pull/9355){:target="_blank"}  from **@davidlt**: Fix -Wpotentially-evaluated-expression warnings `analysis`  created: 2015-05-30 14:44:46 merged: 2015-06-08 15:08:11

108. [9432](http://github.com/cms-sw/cmssw/pull/9432){:target="_blank"}  from **@cschomak**: Simplified commands to copy geometry comparison plots into subfolders, changed units in rotation plots `alca`  created: 2015-06-03 10:08:55 merged: 2015-06-08 15:07:41

109. [9450](http://github.com/cms-sw/cmssw/pull/9450){:target="_blank"}  from **@dmitrijus**: Remove PileupJetIdAlgo from DQM/PhysicsHWW (forward port to 75x) `dqm`  created: 2015-06-04 13:11:37 merged: 2015-06-08 15:07:31

110. [9360](http://github.com/cms-sw/cmssw/pull/9360){:target="_blank"}  from **@jingyucms**: minor fix for dttf dqm and rct dqm `dqm`  `l1`  created: 2015-05-31 04:59:11 merged: 2015-06-08 15:04:56

111. [9489](http://github.com/cms-sw/cmssw/pull/9489){:target="_blank"}  from **@bendavid**: Protect against infinite loops in gen status flag code `analysis`  created: 2015-06-07 16:49:10 merged: 2015-06-08 15:03:00

112. [9491](http://github.com/cms-sw/cmssw/pull/9491){:target="_blank"}  from **@lveldere**: fix indentation of TrajectoryManager and CalorimetryManager `fastsim`  created: 2015-06-08 09:55:29 merged: 2015-06-08 15:02:54

113. [9494](http://github.com/cms-sw/cmssw/pull/9494){:target="_blank"}  from **@mkirsano**: Use pythia8 internal code to append event in residualDecays `generators`  created: 2015-06-08 12:10:01 merged: 2015-06-08 15:00:01

114. [9391](http://github.com/cms-sw/cmssw/pull/9391){:target="_blank"}  from **@istaslis**: Turn on track selection MVA in Heavy Ions `reconstruction`  created: 2015-06-01 19:42:07 merged: 2015-06-08 11:22:53

115. [9477](http://github.com/cms-sw/cmssw/pull/9477){:target="_blank"}  from **@veelken**: fixed CaloTaus (memory issue of ECALBounds) for CMSSW 7_4_x `reconstruction`  created: 2015-06-05 16:17:51 merged: 2015-06-08 11:22:16

116. [9446](http://github.com/cms-sw/cmssw/pull/9446){:target="_blank"}  from **@smuzaffar**: limit the proofsrv slaves to be only two for these unit tests `core`  created: 2015-06-04 12:18:42 merged: 2015-06-07 19:59:41

117. [9460](http://github.com/cms-sw/cmssw/pull/9460){:target="_blank"}  from **@hengne**: Updates RelVal scripts `pdmv`  created: 2015-06-04 19:05:30 merged: 2015-06-07 19:41:58

118. [9445](http://github.com/cms-sw/cmssw/pull/9445){:target="_blank"}  from **@threus**: updated sistrip configuration for online dqm in 75x `dqm`  created: 2015-06-04 12:06:16 merged: 2015-06-07 19:40:04

119. [9470](http://github.com/cms-sw/cmssw/pull/9470){:target="_blank"}  from **@dkotlins**: enable generic CPE to run without GenErrors `reconstruction`  created: 2015-06-05 11:43:55 merged: 2015-06-07 08:51:44

120. [9486](http://github.com/cms-sw/cmssw/pull/9486){:target="_blank"}  from **@wmtan**: Make ROOT5 checksum known in ROOT6 release `reconstruction`  created: 2015-06-07 04:39:17 merged: 2015-06-07 08:47:47

121. [9454](http://github.com/cms-sw/cmssw/pull/9454){:target="_blank"}  from **@kropiv**: change primaryVertexCut for displaced Vertex reconstruction from 2.5  `reconstruction`  created: 2015-06-04 14:59:58 merged: 2015-06-06 16:22:31

122. [9285](http://github.com/cms-sw/cmssw/pull/9285){:target="_blank"}  from **@capalmer85**: PCC NTupler updates 75X `reconstruction`  created: 2015-05-27 00:08:26 merged: 2015-06-06 16:19:26

123. [9442](http://github.com/cms-sw/cmssw/pull/9442){:target="_blank"}  from **@davidlt**: PhysicsTools/IsolationAlgos: add missing dependecy on DataFormats/PatCandidates `analysis`  created: 2015-06-04 09:25:38 merged: 2015-06-06 16:17:43

124. [9380](http://github.com/cms-sw/cmssw/pull/9380){:target="_blank"}  from **@davidlt**: DataFormats/CaloTowers: add missing class `analysis`  `reconstruction`  created: 2015-06-01 11:10:29 merged: 2015-06-06 16:17:17

125. [9242](http://github.com/cms-sw/cmssw/pull/9242){:target="_blank"}  from **@rrabadan**: Mod highest values `dqm`  created: 2015-05-23 01:16:41 merged: 2015-06-06 16:12:00

126. [9358](http://github.com/cms-sw/cmssw/pull/9358){:target="_blank"}  from **@davidlt**: CondFormats/ESObjects: dictionary cleanup `alca`  `db`  created: 2015-05-30 20:57:34 merged: 2015-06-06 16:11:49

127. [9077](http://github.com/cms-sw/cmssw/pull/9077){:target="_blank"}  from **@venturia**: Removed histograms from an EDProducer, new EDAnalyzer, some configuration adjustments and update of the documentation `analysis`  `dqm`  created: 2015-05-13 16:21:24 merged: 2015-06-06 16:11:13

128. [9338](http://github.com/cms-sw/cmssw/pull/9338){:target="_blank"}  from **@nhanvtran**: puppi bug fix for low PU case `analysis`  `reconstruction`  created: 2015-05-29 16:45:09 merged: 2015-06-06 16:08:09

129. [9404](http://github.com/cms-sw/cmssw/pull/9404){:target="_blank"}  from **@smuzaffar**: resolve the conflicts for 74X to 75X forward ports `analysis`  `dqm`  `operations`  `simulation`  created: 2015-06-02 13:11:59 merged: 2015-06-06 16:06:59

130. [9410](http://github.com/cms-sw/cmssw/pull/9410){:target="_blank"}  from **@fioriNTU**: fix of Report Histos `dqm`  created: 2015-06-02 15:12:02 merged: 2015-06-06 16:05:12

131. [9480](http://github.com/cms-sw/cmssw/pull/9480){:target="_blank"}  from **@wmtan**: Fix uninitialized parameter causing relval failures in mixing workflows `simulation`  created: 2015-06-05 19:39:25 merged: 2015-06-06 13:26:38

132. [9201](http://github.com/cms-sw/cmssw/pull/9201){:target="_blank"}  from **@makortel**: Add more histograms and track selections to MultiTrackValidator, remove standalone mode `analysis`  `dqm`  `fastsim`  `geometry`  `reconstruction`  `simulation`  created: 2015-05-21 10:17:39 merged: 2015-06-05 15:58:02

133. [9372](http://github.com/cms-sw/cmssw/pull/9372){:target="_blank"}  from **@davidlt**: CondFormats/EcalObjects: clean dictionary of duplicate selection rules `alca`  `db`  created: 2015-05-31 08:40:53 merged: 2015-06-05 15:52:08

134. [9466](http://github.com/cms-sw/cmssw/pull/9466){:target="_blank"}  from **@davidlt**: RecoJets/JetAnalyzers: fix -Werror=maybe-uninitialized `reconstruction`  created: 2015-06-05 09:07:47 merged: 2015-06-05 15:49:56

135. [9318](http://github.com/cms-sw/cmssw/pull/9318){:target="_blank"}  from **@makortel**: Separate vertex truth matching from vertex validation EDAnalyzer `dqm`  `simulation`  created: 2015-05-28 14:21:40 merged: 2015-06-05 11:53:36

136. [9458](http://github.com/cms-sw/cmssw/pull/9458){:target="_blank"}  from **@pietverwilligen**: avoid dereferencing of null pointer `simulation`  created: 2015-06-04 16:51:00 merged: 2015-06-05 11:22:17

137. [9464](http://github.com/cms-sw/cmssw/pull/9464){:target="_blank"}  from **@wmtan**: Make ROOT5 checksums known in ROOT6 `reconstruction`  created: 2015-06-04 21:16:27 merged: 2015-06-05 11:20:06

138. [7795](http://github.com/cms-sw/cmssw/pull/7795){:target="_blank"}  from **@matz-e**: Allow for more than 3 skipped LHE files. `generators`  created: 2015-02-17 12:40:03 merged: 2015-06-04 18:52:17

139. [9276](http://github.com/cms-sw/cmssw/pull/9276){:target="_blank"}  from **@archiron**: Energy correction `dqm`  created: 2015-05-26 15:11:29 merged: 2015-06-04 18:27:53

140. [9384](http://github.com/cms-sw/cmssw/pull/9384){:target="_blank"}  from **@igv4321**: Turning on the HBHE negative energy filter `reconstruction`  created: 2015-06-01 14:48:13 merged: 2015-06-04 18:15:53

141. [9451](http://github.com/cms-sw/cmssw/pull/9451){:target="_blank"}  from **@sushilchauhan**: replaced kCanRebin with SetCanExtend for beamspot code for online DQM as done in PR #9416 `dqm`  created: 2015-06-04 13:39:56 merged: 2015-06-04 18:14:34

142. [9393](http://github.com/cms-sw/cmssw/pull/9393){:target="_blank"}  from **@dinardo**: Test white background `dqm`  created: 2015-06-01 22:01:51 merged: 2015-06-04 18:12:34

143. [9397](http://github.com/cms-sw/cmssw/pull/9397){:target="_blank"}  from **@wmtan**: Refactoring of PoolSource `core`  `dqm`  `geometry`  `simulation`  created: 2015-06-02 01:33:34 merged: 2015-06-04 18:11:31

144. [9002](http://github.com/cms-sw/cmssw/pull/9002){:target="_blank"}  from **@lgray**: EGM VID IDs for 75X - PHYS14 tunings `analysis`  `reconstruction`  created: 2015-05-08 11:28:54 merged: 2015-06-04 11:11:14

145. [9120](http://github.com/cms-sw/cmssw/pull/9120){:target="_blank"}  from **@cms-btv-pog**: Boosted double SV tagger `analysis`  `reconstruction`  created: 2015-05-17 16:08:22 merged: 2015-06-04 11:10:50

146. [9431](http://github.com/cms-sw/cmssw/pull/9431){:target="_blank"}  from **@ggovi**: enabling code for timestamp selection after frontier bug fix `alca`  `db`  created: 2015-06-03 08:53:57 merged: 2015-06-04 11:10:08

147. [9433](http://github.com/cms-sw/cmssw/pull/9433){:target="_blank"}  from **@milosdjordjevic**: RecoParticleFlow/PFTracking/interface/LightPFTrackProducer.h `reconstruction`  created: 2015-06-03 10:25:51 merged: 2015-06-04 11:03:15

148. [9373](http://github.com/cms-sw/cmssw/pull/9373){:target="_blank"}  from **@davidlt**: Fix dependencies between DataFormats `fastsim`  `reconstruction`  created: 2015-05-31 13:52:12 merged: 2015-06-04 09:04:11

149. [9362](http://github.com/cms-sw/cmssw/pull/9362){:target="_blank"}  from **@davidlt**: DataFormats/TauReco: clean dictionary of duplicate selection rules `reconstruction`  created: 2015-05-31 06:55:59 merged: 2015-06-04 08:58:56

150. [9399](http://github.com/cms-sw/cmssw/pull/9399){:target="_blank"}  from **@Martin-Grunewald**: Add L1T lowPU v3 menu (75X) `hlt`  `l1`  created: 2015-06-02 06:58:48 merged: 2015-06-04 08:58:29

151. [9426](http://github.com/cms-sw/cmssw/pull/9426){:target="_blank"}  from **@Dr15Jones**: Customize HLT for new jet correctors `hlt`  created: 2015-06-02 21:45:03 merged: 2015-06-04 08:57:53

152. [9411](http://github.com/cms-sw/cmssw/pull/9411){:target="_blank"}  from **@rovere**: CCC off everywhere, not only iterative tracking, in RunI-like customisation snippet. `reconstruction`  created: 2015-06-02 15:19:13 merged: 2015-06-04 08:57:14

153. [9388](http://github.com/cms-sw/cmssw/pull/9388){:target="_blank"}  from **@akhukhun**: Separate tp emulator parameters for HF. `l1`  created: 2015-06-01 16:31:24 merged: 2015-06-04 08:56:40

154. [9434](http://github.com/cms-sw/cmssw/pull/9434){:target="_blank"}  from **@smuzaffar**: update duplicate dictionary checking script fr new types `core`  created: 2015-06-03 10:48:53 merged: 2015-06-03 13:49:35

155. [9420](http://github.com/cms-sw/cmssw/pull/9420){:target="_blank"}  from **@batinkov**: runtype is removed `dqm`  created: 2015-06-02 19:59:49 merged: 2015-06-03 10:48:00

156. [9367](http://github.com/cms-sw/cmssw/pull/9367){:target="_blank"}  from **@davidlt**: DataFormats/HGCRecHit: clean dictionary of duplicate selection rules created: 2015-05-31 07:29:06 merged: 2015-06-03 10:43:42

157. [9368](http://github.com/cms-sw/cmssw/pull/9368){:target="_blank"}  from **@davidlt**: DataFormats/HGCDigi: clean dictionary of duplicate selection rules created: 2015-05-31 07:37:30 merged: 2015-06-03 10:43:32

158. [9403](http://github.com/cms-sw/cmssw/pull/9403){:target="_blank"}  from **@davidlt**: Remove leading whitespace from types in classes_*def.xml selection files `analysis`  `core`  `fastsim`  `l1`  `reconstruction`  `simulation`  created: 2015-06-02 13:02:35 merged: 2015-06-03 10:42:56

159. [9402](http://github.com/cms-sw/cmssw/pull/9402){:target="_blank"}  from **@ianna**: DD Core Cleanup `geometry`  created: 2015-06-02 12:42:21 merged: 2015-06-03 08:34:12

160. [9401](http://github.com/cms-sw/cmssw/pull/9401){:target="_blank"}  from **@vdutta**: Fix to allow histogram rebinning to work again for Tracker DQM trend plots in ROOT6 (75X) `dqm`  created: 2015-06-02 09:02:36 merged: 2015-06-03 08:33:38

161. [9324](http://github.com/cms-sw/cmssw/pull/9324){:target="_blank"}  from **@jmduarte**: adding Hbb invariant mass HLT filter 75X `hlt`  created: 2015-05-29 02:30:23 merged: 2015-06-02 16:17:54

162. [9316](http://github.com/cms-sw/cmssw/pull/9316){:target="_blank"}  from **@apfeiffer1**: Conddb: move to upper-case table names, ignore non-existing GT table in sqlite `db`  created: 2015-05-28 13:47:50 merged: 2015-06-02 16:13:21

163. [9335](http://github.com/cms-sw/cmssw/pull/9335){:target="_blank"}  from **@franzoni**: 2400 MB changed to 3000 `pdmv`  created: 2015-05-29 14:08:34 merged: 2015-06-02 16:12:49

164. [9385](http://github.com/cms-sw/cmssw/pull/9385){:target="_blank"}  from **@smorovic**: Online file-locking improvements (75X) `daq`  created: 2015-06-01 16:04:43 merged: 2015-06-02 16:12:10

165. [9121](http://github.com/cms-sw/cmssw/pull/9121){:target="_blank"}  from **@ahinzmann**: Fix switch to ak8GenJetsNoNu in miniaod `analysis`  created: 2015-05-18 04:55:36 merged: 2015-06-02 14:05:56

166. [9377](http://github.com/cms-sw/cmssw/pull/9377){:target="_blank"}  from **@boudoul**: Loading the Magnetic Field by default from DB `operations`  `pdmv`  created: 2015-05-31 17:04:18 merged: 2015-06-02 09:49:19

167. [9357](http://github.com/cms-sw/cmssw/pull/9357){:target="_blank"}  from **@civanch**: Cleanup Geant4 Physics Lists for exotics `simulation`  created: 2015-05-30 19:07:31 merged: 2015-06-02 07:36:30

168. [9312](http://github.com/cms-sw/cmssw/pull/9312){:target="_blank"}  from **@apfeiffer1**: add check to ignore non-existing GT table when reading sqlite files `db`  created: 2015-05-28 13:00:08 merged: 2015-06-02 07:34:40

169. [9361](http://github.com/cms-sw/cmssw/pull/9361){:target="_blank"}  from **@davidlt**: Fireworks/Core: dictionary cleanup `visualization`  created: 2015-05-31 06:33:13 merged: 2015-06-02 07:34:16

170. [9370](http://github.com/cms-sw/cmssw/pull/9370){:target="_blank"}  from **@davidlt**: DataFormats/DetId: clean dictionary of duplicate selection rules `simulation`  created: 2015-05-31 07:58:17 merged: 2015-06-01 07:46:20

171. [9317](http://github.com/cms-sw/cmssw/pull/9317){:target="_blank"}  from **@ianna**: DD Offline DB Loader Cleanup `geometry`  `simulation`  created: 2015-05-28 14:13:00 merged: 2015-05-31 15:13:47

172. [9305](http://github.com/cms-sw/cmssw/pull/9305){:target="_blank"}  from **@wmtan**: Rename AutoLibraryLoader (FWLite), which is misnamed `alca`  `analysis`  `core`  `db`  `dqm`  `fastsim`  `generators`  `hlt`  `l1`  `operations`  `reconstruction`  `simulation`  `visualization`  created: 2015-05-27 23:14:23 merged: 2015-05-31 12:27:07

173. [9329](http://github.com/cms-sw/cmssw/pull/9329){:target="_blank"}  from **@civanch**: fixed mu-nuclear `simulation`  created: 2015-05-29 10:12:26 merged: 2015-05-31 12:26:44

174. [9353](http://github.com/cms-sw/cmssw/pull/9353){:target="_blank"}  from **@davidlt**: Add missing GCC11_OVERRIDE / override `core`  `reconstruction`  created: 2015-05-30 12:21:04 merged: 2015-05-31 12:24:58

175. [9363](http://github.com/cms-sw/cmssw/pull/9363){:target="_blank"}  from **@davidlt**: DataFormats/RecoCandidate: clean dictionary of duplicate selection rules `reconstruction`  created: 2015-05-31 07:05:22 merged: 2015-05-31 12:24:40

176. [9366](http://github.com/cms-sw/cmssw/pull/9366){:target="_blank"}  from **@davidlt**: DataFormats/HepMCCandidate: clean dictionary of duplicate selection rules `generators`  created: 2015-05-31 07:20:27 merged: 2015-05-31 12:24:06

177. [9371](http://github.com/cms-sw/cmssw/pull/9371){:target="_blank"}  from **@davidlt**: CondFormats/SiStripObjects: clean dictionary of duplicate selection rules `alca`  `db`  created: 2015-05-31 08:08:05 merged: 2015-05-31 12:23:52

178. [9369](http://github.com/cms-sw/cmssw/pull/9369){:target="_blank"}  from **@davidlt**: DataFormats/EcalRecHit: clean dictionary of duplicate selection rules `reconstruction`  created: 2015-05-31 07:49:37 merged: 2015-05-31 12:22:54

179. [9352](http://github.com/cms-sw/cmssw/pull/9352){:target="_blank"}  from **@davidlt**: Validation/EventGenerator: remove duplicate in BuildFile.xml `dqm`  `generators`  created: 2015-05-30 12:12:43 merged: 2015-05-31 07:55:46

#### CMSDIST Changes between Tags REL/CMSSW_7_5_0_pre5/slc6_amd64_gcc491 and REL/CMSSW_7_5_0_pre6/slc6_amd64_gcc491:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_5_0_pre5/slc6_amd64_gcc491...REL/CMSSW_7_5_0_pre6/slc6_amd64_gcc491)



1. [1625](http://github.com/cms-sw/cmsdist/pull/1625){:target="_blank"}  from **@degano**: Remove FastSimulation/PileUpProducer data. created: 2015-06-19 09:53:00 merged: 2015-06-19 09:53:04

2. [1624](http://github.com/cms-sw/cmsdist/pull/1624){:target="_blank"}  from **@degano**: Advance root to pick up latest 2 commits created: 2015-06-19 09:33:00 merged: 2015-06-19 09:33:03

3. [1621](http://github.com/cms-sw/cmsdist/pull/1621){:target="_blank"}  from **@degano**: Advance root to pickup latest patch. created: 2015-06-16 08:37:36 merged: 2015-06-16 08:37:39

4. [1618](http://github.com/cms-sw/cmsdist/pull/1618){:target="_blank"}  from **@degano**: Update RecoMET/METPUSubtraction data to latest update. created: 2015-06-12 09:52:04 merged: 2015-06-12 09:52:10

5. [1616](http://github.com/cms-sw/cmsdist/pull/1616){:target="_blank"}  from **@degano**: Patchelf requrires autotools at build time. created: 2015-06-10 08:59:20 merged: 2015-06-10 08:59:26

6. [1612](http://github.com/cms-sw/cmsdist/pull/1612){:target="_blank"}  from **@smuzaffar**: updated Intel ICC compiler to test 16.0 beta release created: 2015-06-05 15:30:17 merged: 2015-06-05 15:31:12

7. [1606](http://github.com/cms-sw/cmsdist/pull/1606){:target="_blank"}  from **@degano**: Remove patch for symlink and force them through makefile options instead created: 2015-06-05 08:53:18 merged: 2015-06-05 08:57:46

8. [1598](http://github.com/cms-sw/cmsdist/pull/1598){:target="_blank"}  from **@degano**: Update root to version 6.02.10 with CMS patches on top of it. created: 2015-06-03 10:25:36 merged: 2015-06-03 10:26:38

9. [1594](http://github.com/cms-sw/cmsdist/pull/1594){:target="_blank"}  from **@ggovi**: cleaned up patches for timestamp handling in coral created: 2015-05-31 08:37:07 merged: 2015-06-02 14:32:16
