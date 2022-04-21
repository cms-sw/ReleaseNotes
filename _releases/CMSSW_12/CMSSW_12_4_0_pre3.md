---
layout: post
rel_link:  "12_4_0_pre3"
title:  "CMSSW_12_4_0_pre3"
date:   2022-04-21 06:54:09
categories: cmssw
relmajor: 12
relminor: 4
relsubminor: 0
relpre: _pre3
---

# CMSSW_12_4_0_pre3
#### Changes since CMSSW_12_4_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_4_0_pre2...CMSSW_12_4_0_pre3)



1. [37634](http://github.com/cms-sw/cmssw/pull/37634){:target="_blank"}  from **@zuoxunwu**: small fix to enable CSC unpacker in L1T DQM sequence `dqm` created: 2022-04-20 14:22:43 merged: 2022-04-21 06:16:50

2. [37631](http://github.com/cms-sw/cmssw/pull/37631){:target="_blank"}  from **@mmusich**: get rid of more deprecation warnings in `OnlineDB` `db` created: 2022-04-20 12:14:23 merged: 2022-04-20 20:01:09

3. [37627](http://github.com/cms-sw/cmssw/pull/37627){:target="_blank"}  from **@tvami**: Add new scenario for ECAL ALCANANO and update the unit test `operations` created: 2022-04-19 20:44:45 merged: 2022-04-20 19:56:58

4. [37613](http://github.com/cms-sw/cmssw/pull/37613){:target="_blank"}  from **@mmusich**: fix the cms EDModule type of `GenParticleMatchMerger` `simulation` created: 2022-04-19 09:05:49 merged: 2022-04-21 00:45:35

5. [37609](http://github.com/cms-sw/cmssw/pull/37609){:target="_blank"}  from **@Dr15Jones**: Move framework test modules away from legacy types `core` created: 2022-04-18 21:13:01 merged: 2022-04-20 00:39:31

6. [37607](http://github.com/cms-sw/cmssw/pull/37607){:target="_blank"}  from **@Dr15Jones**: Disable fork handler in XrootD `core` created: 2022-04-18 15:57:16 merged: 2022-04-18 23:23:52

7. [37606](http://github.com/cms-sw/cmssw/pull/37606){:target="_blank"}  from **@missirol**: add HLT-EGM customisation for 2018 Data `hlt` created: 2022-04-18 15:31:29 merged: 2022-04-19 09:16:04

8. [37605](http://github.com/cms-sw/cmssw/pull/37605){:target="_blank"}  from **@fwyzard**: Updates to the MPIService `heterogeneous` created: 2022-04-18 14:11:58 merged: 2022-04-19 01:03:11

9. [37604](http://github.com/cms-sw/cmssw/pull/37604){:target="_blank"}  from **@bsunanda**: Phase2-hgx309 Add possibility of adding shift due to cassette positioning `geometry` `upgrade` created: 2022-04-18 08:04:38 merged: 2022-04-19 07:30:02

10. [37594](http://github.com/cms-sw/cmssw/pull/37594){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_3_X` [`12_4_X`] `hlt` created: 2022-04-16 06:57:58 merged: 2022-04-16 15:25:26

11. [37591](http://github.com/cms-sw/cmssw/pull/37591){:target="_blank"}  from **@Dr15Jones**: Better exception messages from ROOT delayed reading `core` created: 2022-04-16 00:20:23 merged: 2022-04-18 19:52:15

12. [37589](http://github.com/cms-sw/cmssw/pull/37589){:target="_blank"}  from **@Dr15Jones**: Better Tau failure messages `analysis` created: 2022-04-15 21:12:55 merged: 2022-04-18 01:06:26

13. [37588](http://github.com/cms-sw/cmssw/pull/37588){:target="_blank"}  from **@tvami**: Updating EGM HLT supercluster regression tags for Run 3 in MC `alca` `hlt` `reconstruction` created: 2022-04-15 19:34:29 merged: 2022-04-19 09:16:39

14. [37587](http://github.com/cms-sw/cmssw/pull/37587){:target="_blank"}  from **@mmusich**: modernize `SiStripPayloadMapTableCreator` `db` created: 2022-04-15 19:33:53 merged: 2022-04-16 01:51:30

15. [37582](http://github.com/cms-sw/cmssw/pull/37582){:target="_blank"}  from **@francescobrivio**: Fix typo in L1T prescales files `l1` created: 2022-04-15 14:16:43 merged: 2022-04-18 13:15:40

16. [37578](http://github.com/cms-sw/cmssw/pull/37578){:target="_blank"}  from **@mmusich**: [OT inefficiency] add 0% bad strip scenario to customization function and generate new RelVal workflows `simulation` `pdmv` `upgrade` created: 2022-04-15 11:37:46 merged: 2022-04-18 19:41:38

17. [37577](http://github.com/cms-sw/cmssw/pull/37577){:target="_blank"}  from **@bsunanda**: Run2-gex125C Make the 2017 version to work till end of step3 for both dd4hep and ddd variants `geometry` created: 2022-04-15 07:43:45 merged: 2022-04-17 01:35:29

18. [37576](http://github.com/cms-sw/cmssw/pull/37576){:target="_blank"}  from **@suchandradutta**: Phase2 digitizer updated to exclude  badchannel in Strip like detectors `simulation` `upgrade` created: 2022-04-15 07:33:12 merged: 2022-04-18 18:59:20

19. [37575](http://github.com/cms-sw/cmssw/pull/37575){:target="_blank"}  from **@smuzaffar**: Fix CS8/EL8/CS9 openssl build error `core` created: 2022-04-15 03:34:02 merged: 2022-04-15 12:37:24

20. [37574](http://github.com/cms-sw/cmssw/pull/37574){:target="_blank"}  from **@AnnikaStein**: feat: update TopMuEG skim to latest HLT paths in BTV `pdmv` created: 2022-04-14 18:42:54 merged: 2022-04-18 15:38:23

21. [37573](http://github.com/cms-sw/cmssw/pull/37573){:target="_blank"}  from **@mdelcourt**: Fixed dead assign in CalibTracker/SiStripHitEfficiency and CalibFormats/SiStripObjects `alca` created: 2022-04-14 17:51:55 merged: 2022-04-15 21:20:12

22. [37570](http://github.com/cms-sw/cmssw/pull/37570){:target="_blank"}  from **@finnlabe**: B2G HLT DQM cleanup `dqm` created: 2022-04-14 13:14:18 merged: 2022-04-15 21:23:27

23. [37568](http://github.com/cms-sw/cmssw/pull/37568){:target="_blank"}  from **@davidlange6**: Fixing missing Buildfile dependencies on hepmc `dqm` `fastsim` `generators` `visualization` `simulation` created: 2022-04-14 11:36:13 merged: 2022-04-18 06:28:06

24. [37566](http://github.com/cms-sw/cmssw/pull/37566){:target="_blank"}  from **@bsunanda**: Phase2-hgx308X Avoid compilation warnings in L1Trigger/L1THGCal `dqm` `l1` `upgrade` created: 2022-04-14 04:41:47 merged: 2022-04-19 07:27:56

25. [37565](http://github.com/cms-sw/cmssw/pull/37565){:target="_blank"}  from **@arsahasransu**: Change tracks to optional requirement in HLTDisplacedEgammaFilter `hlt` created: 2022-04-14 02:06:13 merged: 2022-04-14 23:25:47

26. [37563](http://github.com/cms-sw/cmssw/pull/37563){:target="_blank"}  from **@makortel**: Make SwitchProducer work with ConditionalTask `core` created: 2022-04-14 00:21:03 merged: 2022-04-20 15:53:28

27. [37562](http://github.com/cms-sw/cmssw/pull/37562){:target="_blank"}  from **@makortel**: Move pixelTracksCPU module definition inside SwitchProducerCUDA `hlt` `reconstruction` `heterogeneous` created: 2022-04-13 22:47:10 merged: 2022-04-15 00:46:48

28. [37561](http://github.com/cms-sw/cmssw/pull/37561){:target="_blank"}  from **@trackreco**: mkFit update to standalone build/test scripts `reconstruction` created: 2022-04-13 22:30:27 merged: 2022-04-14 23:24:57

29. [37557](http://github.com/cms-sw/cmssw/pull/37557){:target="_blank"}  from **@malbouis**: Add PPS and EGM tags to dataRun3 GTs `alca` created: 2022-04-13 19:40:13 merged: 2022-04-15 21:37:08

30. [37555](http://github.com/cms-sw/cmssw/pull/37555){:target="_blank"}  from **@rovere**: Eta phi search in tile `reconstruction` `upgrade` created: 2022-04-13 15:49:56 merged: 2022-04-16 21:28:07

31. [37551](http://github.com/cms-sw/cmssw/pull/37551){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development `hlt` created: 2022-04-13 14:43:58 merged: 2022-04-14 11:53:54

32. [37547](http://github.com/cms-sw/cmssw/pull/37547){:target="_blank"}  from **@bsunanda**: Phase2-hgx308 Add the new conversion code of Flat file to XML `dqm` `geometry` `upgrade` created: 2022-04-13 09:33:22 merged: 2022-04-19 07:16:28

33. [37546](http://github.com/cms-sw/cmssw/pull/37546){:target="_blank"}  from **@perrotta**: Simplify usage of constants in HGCalCellUV `geometry` `upgrade` created: 2022-04-13 08:56:45 merged: 2022-04-13 17:32:53

34. [37545](http://github.com/cms-sw/cmssw/pull/37545){:target="_blank"}  from **@Dr15Jones**: Added exception to HepMCValidationHelper `dqm` `generators` created: 2022-04-12 21:01:55 merged: 2022-04-14 00:34:33

35. [37544](http://github.com/cms-sw/cmssw/pull/37544){:target="_blank"}  from **@zuoxunwu**: Enable EMTF regional showers with unpacked info `dqm` created: 2022-04-12 19:26:54 merged: 2022-04-15 00:38:08

36. [37541](http://github.com/cms-sw/cmssw/pull/37541){:target="_blank"}  from **@gartung**: Link cmsRunGP with libtcmalloc.so so that heap profiling can be run. `core` created: 2022-04-12 17:34:16 merged: 2022-04-13 00:34:03

37. [37540](http://github.com/cms-sw/cmssw/pull/37540){:target="_blank"}  from **@perrotta**: Remove some dead assignments in L1Trigger/DTTriggerPhase2/src/HoughGrouping.cc `l1` `upgrade` created: 2022-04-12 16:23:58 merged: 2022-04-13 20:35:37

38. [37539](http://github.com/cms-sw/cmssw/pull/37539){:target="_blank"}  from **@alpakpinar**: Add HFJetCleaner module for HLT `hlt` created: 2022-04-12 16:08:36 merged: 2022-04-18 00:57:04

39. [37537](http://github.com/cms-sw/cmssw/pull/37537){:target="_blank"}  from **@lwang046**: HCalDQM: Fix for issue #37486 collection tag correction `dqm` created: 2022-04-12 10:17:05 merged: 2022-04-20 00:43:43

40. [37535](http://github.com/cms-sw/cmssw/pull/37535){:target="_blank"}  from **@iarspider**: Add import test for professor2 `analysis` created: 2022-04-12 07:21:02 merged: 2022-04-14 11:59:31

41. [37533](http://github.com/cms-sw/cmssw/pull/37533){:target="_blank"}  from **@tvami**: Simplify `VVIObjF` object so it takes `kappa` only in the constructor `reconstruction` created: 2022-04-11 21:20:48 merged: 2022-04-20 07:47:39

42. [37531](http://github.com/cms-sw/cmssw/pull/37531){:target="_blank"}  from **@smuzaffar**: added new Utilities/OpenSSL and move unit tests to it `core` `db` created: 2022-04-11 16:38:26 merged: 2022-04-14 13:34:17

43. [37524](http://github.com/cms-sw/cmssw/pull/37524){:target="_blank"}  from **@cms-tsg-storm**: HLT menu migration to 12_3_0 `hlt` created: 2022-04-11 10:26:10 merged: 2022-04-11 15:49:38

44. [37522](http://github.com/cms-sw/cmssw/pull/37522){:target="_blank"}  from **@cecilecaillol**: L1T: Switch from cout to MessageLogger `l1` created: 2022-04-11 10:03:43 merged: 2022-04-11 15:47:58

45. [37520](http://github.com/cms-sw/cmssw/pull/37520){:target="_blank"}  from **@mbluj**: Extend eta range for jets seeding tau reco&ID `reconstruction` created: 2022-04-11 09:06:25 merged: 2022-04-20 14:12:54

46. [37519](http://github.com/cms-sw/cmssw/pull/37519){:target="_blank"}  from **@missirol**: removed deprecated HLT plugin `PFJetsMatchedToFilteredCaloJetsProducer` `hlt` created: 2022-04-10 08:12:21 merged: 2022-04-10 21:54:40

47. [37518](http://github.com/cms-sw/cmssw/pull/37518){:target="_blank"}  from **@missirol**: add HLT customisation for Run-2 CTPPS `hlt` created: 2022-04-10 07:55:59 merged: 2022-04-11 09:06:57

48. [37517](http://github.com/cms-sw/cmssw/pull/37517){:target="_blank"}  from **@bsunanda**: Phase2-gex127M Make some protection in accessing inpu collections for MTD so that some FasTsim tests can proceed `reconstruction` `simulation` `upgrade` created: 2022-04-10 07:00:42 merged: 2022-04-12 12:27:19

49. [37516](http://github.com/cms-sw/cmssw/pull/37516){:target="_blank"}  from **@bsunanda**: Run3-alca222X Utilize MessageLogger rather than cout in Calibration/IsolatedParticles `alca` created: 2022-04-10 01:36:38 merged: 2022-04-12 15:54:57

50. [37515](http://github.com/cms-sw/cmssw/pull/37515){:target="_blank"}  from **@alja**: Add typedefs for association quality and tag template argument types. `core` created: 2022-04-09 22:07:44 merged: 2022-04-11 19:33:25

51. [37514](http://github.com/cms-sw/cmssw/pull/37514){:target="_blank"}  from **@smuzaffar**: Update cmsLHEtoEOSManager.py to use python used by cmsRun `generators` created: 2022-04-09 11:41:49 merged: 2022-04-11 09:09:58

52. [37511](http://github.com/cms-sw/cmssw/pull/37511){:target="_blank"}  from **@bsunanda**: Phase2-hgx307X Change xml file in view of changed algorithms in PR's #37505 and #37510 `geometry` created: 2022-04-09 05:42:21 merged: 2022-04-12 00:58:00

53. [37510](http://github.com/cms-sw/cmssw/pull/37510){:target="_blank"}  from **@bsunanda**: Phase2-hgx307 Update HGCal cell defintion using PR #37505 `geometry` `upgrade` created: 2022-04-09 01:41:44 merged: 2022-04-13 17:35:43

54. [37509](http://github.com/cms-sw/cmssw/pull/37509){:target="_blank"}  from **@rtschmitz**: Skim for Delayed Jets and DTClusters `pdmv` created: 2022-04-09 01:11:36 merged: 2022-04-16 01:49:15

55. [37508](http://github.com/cms-sw/cmssw/pull/37508){:target="_blank"}  from **@shimashimarin**: Change the way to match "mg_reweighting" in production of NanoAOD MC samples `xpog` created: 2022-04-08 18:03:25 merged: 2022-04-10 12:12:33

56. [37505](http://github.com/cms-sw/cmssw/pull/37505){:target="_blank"}  from **@Pruthvi-ch**: Cell correction `geometry` `upgrade` created: 2022-04-08 14:08:39 merged: 2022-04-12 12:22:54

57. [37504](http://github.com/cms-sw/cmssw/pull/37504){:target="_blank"}  from **@bsunanda**: Run3-alca222 Update some of the macros usedin calibrating HCAL with isotrack or muon `alca` created: 2022-04-08 10:34:50 merged: 2022-04-10 01:58:19

58. [37502](http://github.com/cms-sw/cmssw/pull/37502){:target="_blank"}  from **@cms-tsg-storm**: Fix L1T MuonShowers for HLT `hlt` `operations` created: 2022-04-08 07:27:01 merged: 2022-04-08 12:40:53

59. [37500](http://github.com/cms-sw/cmssw/pull/37500){:target="_blank"}  from **@mmusich**: Introduce `PtMaxTrackCountFilter` `reconstruction` created: 2022-04-07 19:01:35 merged: 2022-04-15 14:31:54

60. [37498](http://github.com/cms-sw/cmssw/pull/37498){:target="_blank"}  from **@CTPPS**: bugfix XML for PPS strips mapping `alca` created: 2022-04-07 16:45:50 merged: 2022-04-08 00:39:38

61. [37495](http://github.com/cms-sw/cmssw/pull/37495){:target="_blank"}  from **@cecilecaillol**: rename duplicated class TrackQuality `l1` `upgrade` created: 2022-04-07 15:48:25 merged: 2022-04-11 09:52:32

62. [37492](http://github.com/cms-sw/cmssw/pull/37492){:target="_blank"}  from **@mmusich**: SiStrip Payload Inspector: refinements to `SiStripCondObjectRepresent` `db` created: 2022-04-07 15:11:15 merged: 2022-04-11 09:27:08

63. [37491](http://github.com/cms-sw/cmssw/pull/37491){:target="_blank"}  from **@ram1123**: Added the switch for the inclusion of PS energy `hlt` `reconstruction` created: 2022-04-07 14:29:06 merged: 2022-04-08 11:01:35

64. [37490](http://github.com/cms-sw/cmssw/pull/37490){:target="_blank"}  from **@smuzaffar**: [CS9] Remove usage of deprecated SHA1 functions, use EVP_Digest instead `core` `db` created: 2022-04-07 14:22:42 merged: 2022-04-08 15:35:43

65. [37489](http://github.com/cms-sw/cmssw/pull/37489){:target="_blank"}  from **@cecilecaillol**: fix edm module warnings `l1` created: 2022-04-07 14:15:21 merged: 2022-04-08 07:03:00

66. [37485](http://github.com/cms-sw/cmssw/pull/37485){:target="_blank"}  from **@smuzaffar**: Properly close file using fclose; fixes CS9 compilation warning `alca` created: 2022-04-07 09:52:45 merged: 2022-04-08 14:50:58

67. [37480](http://github.com/cms-sw/cmssw/pull/37480){:target="_blank"}  from **@gartung**: Utilities/StaticAnaylzers: Add check to postprocess-scan-build.py for empty cells to avoid index out of range error. `core` created: 2022-04-06 14:23:07 merged: 2022-04-06 23:28:45

68. [37478](http://github.com/cms-sw/cmssw/pull/37478){:target="_blank"}  from **@davidlange6**: remove circular dependency in DataFormats/L1Trigger `l1` created: 2022-04-06 08:29:36 merged: 2022-04-06 12:50:29

69. [37474](http://github.com/cms-sw/cmssw/pull/37474){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_3_X` [`12_4_X`] `hlt` created: 2022-04-06 06:45:08 merged: 2022-04-06 14:57:22

70. [37473](http://github.com/cms-sw/cmssw/pull/37473){:target="_blank"}  from **@bsunanda**: Run3-sim116X Clean up the codes in SimG4Core/GFlash/TB as suggested by Andrea `simulation` created: 2022-04-06 02:12:18 merged: 2022-04-07 13:00:35

71. [37471](http://github.com/cms-sw/cmssw/pull/37471){:target="_blank"}  from **@TaeunKwon**: HCAL: fix on HCAL TP saturation algorithm to synchronize s/w TP algorithm with f/w `l1` created: 2022-04-05 23:04:10 merged: 2022-04-07 00:38:29

72. [37470](http://github.com/cms-sw/cmssw/pull/37470){:target="_blank"}  from **@srimanob**: Add LHCTransport to Run3 GEN content `generators` created: 2022-04-05 16:09:28 merged: 2022-04-12 00:52:40

73. [37464](http://github.com/cms-sw/cmssw/pull/37464){:target="_blank"}  from **@mmusich**: get rid of CMSDEPRECATED_X warnings in `HeavyFlavorAnalysis/SpecificDecay` `analysis` created: 2022-04-05 12:23:19 merged: 2022-04-05 21:34:42

74. [37463](http://github.com/cms-sw/cmssw/pull/37463){:target="_blank"}  from **@mmusich**: Customize for OT inefficiency `alca` `simulation` `upgrade` created: 2022-04-05 09:51:23 merged: 2022-04-08 00:53:39

75. [37460](http://github.com/cms-sw/cmssw/pull/37460){:target="_blank"}  from **@bsunanda**: Phase2-hgx306 Make a trivial change to reduce number of methods in Geometry/HGcalGeometry `geometry` `upgrade` created: 2022-04-05 08:36:45 merged: 2022-04-07 10:53:11

76. [37456](http://github.com/cms-sw/cmssw/pull/37456){:target="_blank"}  from **@mbluj**: Fixes to the tauID configuration tool `reconstruction` `xpog` created: 2022-04-04 14:28:50 merged: 2022-04-13 00:33:12

77. [37455](http://github.com/cms-sw/cmssw/pull/37455){:target="_blank"}  from **@mmusich**: minor changes to SiPixelLorentzAnglePCL modules `alca` created: 2022-04-04 14:04:12 merged: 2022-04-05 08:09:14

78. [37453](http://github.com/cms-sw/cmssw/pull/37453){:target="_blank"}  from **@elfontan**: New set of files coherent with the new v1_0_0 L1Menu `l1` created: 2022-04-04 12:26:18 merged: 2022-04-07 14:30:22

79. [37449](http://github.com/cms-sw/cmssw/pull/37449){:target="_blank"}  from **@CTPPS**: bugfix - xml tag in PPS strips mapping `alca` created: 2022-04-03 17:14:28 merged: 2022-04-04 08:00:49

80. [37448](http://github.com/cms-sw/cmssw/pull/37448){:target="_blank"}  from **@bsunanda**: Phase2-hgx305 Update the hgcalcell xml files in view of foressen corrections `geometry` `upgrade` created: 2022-04-03 09:14:02 merged: 2022-04-07 15:02:12

81. [37447](http://github.com/cms-sw/cmssw/pull/37447){:target="_blank"}  from **@bsunanda**: Run3-sim116 Make use of printing and creating root tree compatible with multithreaded jobs in a number of packages of SimG4Core `simulation` created: 2022-04-03 03:20:15 merged: 2022-04-05 01:01:58

82. [37442](http://github.com/cms-sw/cmssw/pull/37442){:target="_blank"}  from **@francescobrivio**: Update final L1T menu tag for Run 3 start up `alca` created: 2022-04-02 09:27:58 merged: 2022-04-03 01:18:46

83. [37440](http://github.com/cms-sw/cmssw/pull/37440){:target="_blank"}  from **@cms-tsg-storm**: Update of L1T menu in TSG GTs to `L1Menu_Collisions2022_v1_0_0_xml` `hlt` created: 2022-04-02 09:01:02 merged: 2022-04-03 01:15:06

84. [37438](http://github.com/cms-sw/cmssw/pull/37438){:target="_blank"}  from **@gk199**: HCAL finegrain bit fix to account for TDC packing, and SOI alignment `l1` created: 2022-04-02 02:33:24 merged: 2022-04-05 01:07:44

85. [37437](http://github.com/cms-sw/cmssw/pull/37437){:target="_blank"}  from **@kondratyevd**: Update to DNN-based strategy for outside-in seed generation in Muon HLT `hlt` `reconstruction` created: 2022-04-01 20:18:44 merged: 2022-04-06 08:16:40

86. [37434](http://github.com/cms-sw/cmssw/pull/37434){:target="_blank"}  from **@tvami**: Add AlCaLumiPixels_Run3 scenario `operations` created: 2022-04-01 13:57:07 merged: 2022-04-05 05:52:57

87. [37431](http://github.com/cms-sw/cmssw/pull/37431){:target="_blank"}  from **@slomeo**: Fixed overlaps in M10 Phase2 Scenario (D86, D88, D91) `geometry` `upgrade` created: 2022-04-01 09:54:02 merged: 2022-04-02 05:55:38

88. [37430](http://github.com/cms-sw/cmssw/pull/37430){:target="_blank"}  from **@thomreis**: ECAL GPU unpacker - Add detection of corrupted DCC tower headers and recovery `reconstruction` created: 2022-04-01 09:22:16 merged: 2022-04-03 07:42:51

89. [37428](http://github.com/cms-sw/cmssw/pull/37428){:target="_blank"}  from **@bsunanda**: Run3-gex126X Utilize messagelogger instead of cout in SimG4CMS/Muon and SimG4CMS/ShowerLibraryProducer `simulation` created: 2022-04-01 01:51:13 merged: 2022-04-04 08:43:52

90. [37427](http://github.com/cms-sw/cmssw/pull/37427){:target="_blank"}  from **@hyunyong**: MuonAlignment GEM phase2 geometry `alca` created: 2022-03-31 20:05:00 merged: 2022-04-07 00:44:50

91. [37424](http://github.com/cms-sw/cmssw/pull/37424){:target="_blank"}  from **@jaimeleonh**: Added new muon-tau-jet OvRm filter `hlt` created: 2022-03-31 14:57:54 merged: 2022-04-01 07:19:48

92. [37420](http://github.com/cms-sw/cmssw/pull/37420){:target="_blank"}  from **@mmusich**: add DB ntuplizer and SiStripCondVisualizer, introduce analysis macros and add unit tests `db` created: 2022-03-31 06:00:26 merged: 2022-04-01 00:41:17

93. [37419](http://github.com/cms-sw/cmssw/pull/37419){:target="_blank"}  from **@makortel**: Enable concurrent IOVs by default in ConfigBuilder `operations` created: 2022-03-30 23:55:30 merged: 2022-04-01 06:37:40

94. [37418](http://github.com/cms-sw/cmssw/pull/37418){:target="_blank"}  from **@trackreco**: [MkFit] Tracker geometry extraction from Reco geom modules `reconstruction` created: 2022-03-30 23:06:54 merged: 2022-04-06 10:47:01

95. [37417](http://github.com/cms-sw/cmssw/pull/37417){:target="_blank"}  from **@makortel**: Set concurrent lumis/IOVs in ConfigBuilder if their value is different from default regardless of the number of threads `operations` created: 2022-03-30 21:09:23 merged: 2022-04-02 11:37:58

96. [37415](http://github.com/cms-sw/cmssw/pull/37415){:target="_blank"}  from **@battibass**: [12_4_X] Fix writing of int8_t flat table columns in nanoAOD flat ntuples `xpog` created: 2022-03-30 14:42:06 merged: 2022-04-01 14:30:20

97. [37411](http://github.com/cms-sw/cmssw/pull/37411){:target="_blank"}  from **@fwyzard**: Update all GPU workflows `pdmv` `upgrade` created: 2022-03-30 12:38:42 merged: 2022-04-05 07:42:22

98. [37408](http://github.com/cms-sw/cmssw/pull/37408){:target="_blank"}  from **@iarspider**: Fix warning: 'mzbtemp' may be used uninitialized `l1` `upgrade` created: 2022-03-30 07:13:26 merged: 2022-03-30 19:50:47

99. [37406](http://github.com/cms-sw/cmssw/pull/37406){:target="_blank"}  from **@bsunanda**: Run3-hgx304 Replace cout with messagelogger statements in man classes of Geometry/CaloTopology `geometry` created: 2022-03-30 03:53:11 merged: 2022-03-30 20:05:56

100. [37405](http://github.com/cms-sw/cmssw/pull/37405){:target="_blank"}  from **@dan131riley**: Avoid DQMIO file GUID collisions `dqm` created: 2022-03-29 23:39:47 merged: 2022-03-30 19:48:12

101. [37402](http://github.com/cms-sw/cmssw/pull/37402){:target="_blank"}  from **@Sam-Harper**: Fixing FastTimerClient Hist Remaking Issue : 12_4_X `hlt` created: 2022-03-29 17:14:03 merged: 2022-03-31 16:02:13

102. [37401](http://github.com/cms-sw/cmssw/pull/37401){:target="_blank"}  from **@cecilecaillol**: L1 phase-2 calo developments `l1` `upgrade` created: 2022-03-29 14:52:21 merged: 2022-04-13 17:38:07

103. [37398](http://github.com/cms-sw/cmssw/pull/37398){:target="_blank"}  from **@VinInn**: Stabilize Fishbone `reconstruction` created: 2022-03-29 13:05:13 merged: 2022-04-03 01:17:36

104. [37397](http://github.com/cms-sw/cmssw/pull/37397){:target="_blank"}  from **@mmusich**: introduce SiPhase2BadStrip format for phase-2 simulation `alca` `geometry` `reconstruction` `db` `upgrade` created: 2022-03-29 10:17:23 merged: 2022-04-05 07:41:07

105. [37395](http://github.com/cms-sw/cmssw/pull/37395){:target="_blank"}  from **@Sam-Harper**: Adding option to disable resetting L1 PS counters on ls change `l1` created: 2022-03-29 06:11:01 merged: 2022-04-05 08:39:51

106. [37394](http://github.com/cms-sw/cmssw/pull/37394){:target="_blank"}  from **@bsunanda**: Run2-gex125 Attempt to make 2017 scenario compatible with dd4hep `geometry` `upgrade` created: 2022-03-29 04:18:11 merged: 2022-04-11 10:12:24

107. [37387](http://github.com/cms-sw/cmssw/pull/37387){:target="_blank"}  from **@tvami**: Change prescaled dedx calculation to exclude pixels for Run3 `reconstruction` created: 2022-03-28 20:10:38 merged: 2022-04-11 00:51:24

108. [37386](http://github.com/cms-sw/cmssw/pull/37386){:target="_blank"}  from **@lecriste**: [HGCal] Bug fix in Validation `dqm` created: 2022-03-28 18:51:52 merged: 2022-03-30 19:56:51

109. [37383](http://github.com/cms-sw/cmssw/pull/37383){:target="_blank"}  from **@cecilecaillol**: L1T phase-2: modify HPS taus `l1` `upgrade` created: 2022-03-28 13:25:18 merged: 2022-04-01 13:38:17

110. [37382](http://github.com/cms-sw/cmssw/pull/37382){:target="_blank"}  from **@cecilecaillol**: L1T vertex finder phase2 developments `l1` created: 2022-03-28 12:59:48 merged: 2022-04-01 13:13:49

111. [37378](http://github.com/cms-sw/cmssw/pull/37378){:target="_blank"}  from **@abhih1**: Change quality criteria for some supercrystals in the Ecal Endcaps for LED Quality plots [Master] `dqm` created: 2022-03-28 12:16:43 merged: 2022-03-30 19:53:17

112. [37374](http://github.com/cms-sw/cmssw/pull/37374){:target="_blank"}  from **@bsunanda**: Phase2-hgx303 Rearrange some of the parameters in the proper class in view of V17 geometry `geometry` `upgrade` created: 2022-03-28 10:08:37 merged: 2022-03-30 23:51:35

113. [37369](http://github.com/cms-sw/cmssw/pull/37369){:target="_blank"}  from **@bsunanda**: Run3-gex124E Try to remove compilation warnings in RecoParticleFlow/PFTracking `reconstruction` created: 2022-03-28 05:00:27 merged: 2022-03-30 23:44:59

114. [37367](http://github.com/cms-sw/cmssw/pull/37367){:target="_blank"}  from **@missirol**: remove duplicate of `PropagateToMuon` class `analysis` `dqm` created: 2022-03-27 12:33:51 merged: 2022-04-01 17:49:42

115. [37361](http://github.com/cms-sw/cmssw/pull/37361){:target="_blank"}  from **@Pruthvi-ch**: Cell XY to UV conversion fo HGCal wafers `geometry` `upgrade` created: 2022-03-26 15:03:51 merged: 2022-04-12 11:36:12

116. [37360](http://github.com/cms-sw/cmssw/pull/37360){:target="_blank"}  from **@francescobrivio**: Improve autoAlca dictionaries layout `alca` created: 2022-03-26 11:28:52 merged: 2022-04-07 00:41:45

117. [37358](http://github.com/cms-sw/cmssw/pull/37358){:target="_blank"}  from **@cecilecaillol**: Phase 2 L1: add code for Phase 2 L1 GMT `l1` created: 2022-03-26 09:09:00 merged: 2022-04-01 17:21:26

118. [37355](http://github.com/cms-sw/cmssw/pull/37355){:target="_blank"}  from **@cecilecaillol**: Phase-2 L1: code for L1 demonstrators `l1` created: 2022-03-26 08:25:07 merged: 2022-04-01 17:08:51

119. [37353](http://github.com/cms-sw/cmssw/pull/37353){:target="_blank"}  from **@bsunanda**: Run3-gex124C Try to avoid compilation warnings in L1Trigger/L1CaloTrigger `l1` `upgrade` created: 2022-03-26 01:31:19 merged: 2022-03-30 23:43:10

120. [37347](http://github.com/cms-sw/cmssw/pull/37347){:target="_blank"}  from **@srimanob**: Run-3 FastSim modifier and workflows in runTheMatrix `operations` `simulation` `pdmv` `upgrade` created: 2022-03-25 16:09:00 merged: 2022-04-05 01:23:08

121. [37343](http://github.com/cms-sw/cmssw/pull/37343){:target="_blank"}  from **@rovere**: Add TICL from Reco customise `reconstruction` `upgrade` created: 2022-03-25 08:03:39 merged: 2022-03-30 23:53:10

122. [37342](http://github.com/cms-sw/cmssw/pull/37342){:target="_blank"}  from **@jalimena**: Offline DQM for new EXO-LLP Run 3 HLT paths `dqm` created: 2022-03-25 08:02:43 merged: 2022-03-31 15:25:57

123. [37340](http://github.com/cms-sw/cmssw/pull/37340){:target="_blank"}  from **@jshlee**: [GEM] bugfix - BC and OrbitCounter in AMC13 `simulation` `upgrade` created: 2022-03-24 17:15:07 merged: 2022-03-30 20:00:17

124. [37330](http://github.com/cms-sw/cmssw/pull/37330){:target="_blank"}  from **@bsunanda**: Phase2-hg302 Bug fix for the corners and replacing cout with message logger services `geometry` `upgrade` created: 2022-03-24 06:16:04 merged: 2022-04-03 07:31:38

125. [37324](http://github.com/cms-sw/cmssw/pull/37324){:target="_blank"}  from **@srimanob**: Add HLT75e33 step to Phase-2 workflows `pdmv` `upgrade` created: 2022-03-23 15:41:26 merged: 2022-04-20 00:34:24

126. [37309](http://github.com/cms-sw/cmssw/pull/37309){:target="_blank"}  from **@AliinCern**: mpiCudaGeneric is a program transfer data from a machine to another with GPU using MPI and CUDA. `heterogeneous` created: 2022-03-22 18:11:23 merged: 2022-04-18 15:40:12

127. [37305](http://github.com/cms-sw/cmssw/pull/37305){:target="_blank"}  from **@Dr15Jones**: Added ConditionalTask `core` `hlt` created: 2022-03-22 14:22:45 merged: 2022-04-07 13:59:16

128. [37298](http://github.com/cms-sw/cmssw/pull/37298){:target="_blank"}  from **@jalimena**: HLT release validation for new EXO-LLP Run 3 paths `dqm` created: 2022-03-22 12:50:44 merged: 2022-03-31 15:19:22

129. [37286](http://github.com/cms-sw/cmssw/pull/37286){:target="_blank"}  from **@khaosmos93**: pT dependent ROI producers for Muon HLT `reconstruction` created: 2022-03-21 11:03:26 merged: 2022-04-05 01:09:13

130. [37279](http://github.com/cms-sw/cmssw/pull/37279){:target="_blank"}  from **@barvic**: CSC Run3 data format unpacking/packing update (12_4_X) `reconstruction` created: 2022-03-19 01:49:39 merged: 2022-04-06 07:52:42

131. [37266](http://github.com/cms-sw/cmssw/pull/37266){:target="_blank"}  from **@kakwok**: Update CLCT thresholds for hadronic showers in CSC `l1` created: 2022-03-18 05:14:35 merged: 2022-04-08 07:41:13

132. [37250](http://github.com/cms-sw/cmssw/pull/37250){:target="_blank"}  from **@andrea21z**: Updating the WP of the Muon MVA ID `reconstruction` created: 2022-03-15 12:30:19 merged: 2022-03-31 15:39:08

133. [37219](http://github.com/cms-sw/cmssw/pull/37219){:target="_blank"}  from **@marksan87**: Bug fix for multiple detectors in PFRecHitQTestHCALThresholdVsDepth test  `reconstruction` created: 2022-03-11 21:12:38 merged: 2022-04-05 21:31:33

134. [37187](http://github.com/cms-sw/cmssw/pull/37187){:target="_blank"}  from **@mkirsano**: Add generator hepmc3 products `generators` created: 2022-03-09 19:29:02 merged: 2022-04-20 00:36:12

135. [37178](http://github.com/cms-sw/cmssw/pull/37178){:target="_blank"}  from **@seungjin-yang**: Add GE1/1 detection efficiency monitor using GEMCSCSegment `dqm` created: 2022-03-08 17:46:17 merged: 2022-04-08 07:33:04

136. [37162](http://github.com/cms-sw/cmssw/pull/37162){:target="_blank"}  from **@trtomei**: Porting HLT Phase 2 simplified menu to 12_4_X `hlt` created: 2022-03-07 19:19:14 merged: 2022-04-20 00:35:13

#### CMSDIST Changes between Tags REL/CMSSW_12_4_0_pre2/slc7_amd64_gcc10 and REL/CMSSW_12_4_0_pre3/slc7_amd64_gcc10:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_4_0_pre2/slc7_amd64_gcc10...REL/CMSSW_12_4_0_pre3/slc7_amd64_gcc10)



1. [7801](http://github.com/cms-sw/cmsdist/pull/7801){:target="_blank"}  from **@cms-sw**: [FWLite] added hepmc3 deps needed due to cms-sw/cmssw#37187 created: 2022-04-20 11:51:18 merged: 2022-04-20 11:51:29

2. [7797](http://github.com/cms-sw/cmsdist/pull/7797){:target="_blank"}  from **@cms-sw**: [SCRAM] treat rhel and its colnes as same created: 2022-04-19 12:49:11 merged: 2022-04-20 07:19:13

3. [7796](http://github.com/cms-sw/cmsdist/pull/7796){:target="_blank"}  from **@cms-sw**: Added cmssw-rocky/alma/ubi/el* scripts created: 2022-04-19 11:48:30 merged: 2022-04-20 07:19:24

4. [7791](http://github.com/cms-sw/cmsdist/pull/7791){:target="_blank"}  from **@cms-sw**: [GIT] update to version 2.35.3 which has fix for CVE-2022-24765 created: 2022-04-14 21:18:41 merged: 2022-04-15 08:30:55

5. [7790](http://github.com/cms-sw/cmsdist/pull/7790){:target="_blank"}  from **@cms-sw**: Dropped yaml-cpp; it is not any more required by rivet created: 2022-04-14 08:51:10 merged: 2022-04-14 19:48:07

6. [7789](http://github.com/cms-sw/cmsdist/pull/7789){:target="_blank"}  from **@cms-sw**: G4: cleanup build and toolfile to properly set deps and flags created: 2022-04-14 08:38:52 merged: 2022-04-14 14:02:52

7. [7787](http://github.com/cms-sw/cmsdist/pull/7787){:target="_blank"}  from **@cms-sw**: Revert "Update yaml-cpp to 0.7.0" created: 2022-04-14 04:08:34 merged: 2022-04-14 04:08:41

8. [7783](http://github.com/cms-sw/cmsdist/pull/7783){:target="_blank"}  from **@cms-sw**: [professor2] Remove easy-install pth and rename professor python dir created: 2022-04-13 05:45:00 merged: 2022-04-13 09:31:11

9. [7781](http://github.com/cms-sw/cmsdist/pull/7781){:target="_blank"}  from **@aandvalenzuela**: Add cpu_features library created: 2022-04-12 14:35:59 merged: 2022-04-14 06:46:28

10. [7780](http://github.com/cms-sw/cmsdist/pull/7780){:target="_blank"}  from **@cms-sw**: Update yaml-cpp to 0.7.0 created: 2022-04-12 14:02:05 merged: 2022-04-13 15:49:38

11. [7779](http://github.com/cms-sw/cmsdist/pull/7779){:target="_blank"}  from **@cms-sw**: Update xtensor to 0.24.1, xtl to 0.7.4 created: 2022-04-12 12:05:49 merged: 2022-04-13 05:53:33

12. [7777](http://github.com/cms-sw/cmsdist/pull/7777){:target="_blank"}  from **@cms-sw**: fix professor2 python packageing created: 2022-04-11 16:30:10 merged: 2022-04-12 05:15:50

13. [7776](http://github.com/cms-sw/cmsdist/pull/7776){:target="_blank"}  from **@mkirsano**: update lhapdf sets to 6.4.0e created: 2022-04-11 10:03:04 merged: 2022-04-12 05:16:17

14. [7774](http://github.com/cms-sw/cmsdist/pull/7774){:target="_blank"}  from **@cms-sw**: Fix py-tables issue for aarch64/ppc64le created: 2022-04-10 05:03:22 merged: 2022-04-10 14:48:41

15. [7773](http://github.com/cms-sw/cmsdist/pull/7773){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2022-04-08 16:35:38 merged: 2022-04-08 20:19:21

16. [7769](http://github.com/cms-sw/cmsdist/pull/7769){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-L1TGlobal to V00-02-00 created: 2022-04-07 14:32:44 merged: 2022-04-07 14:45:59

17. [7768](http://github.com/cms-sw/cmsdist/pull/7768){:target="_blank"}  from **@cms-sw**: Eigen: Convert diag pragmas to nv_diag created: 2022-04-07 13:20:34 merged: 2022-04-08 03:30:32

18. [7767](http://github.com/cms-sw/cmsdist/pull/7767){:target="_blank"}  from **@aandvalenzuela**: [Spack] Update py-packages to the latest version created: 2022-04-07 12:55:19 merged: 2022-04-11 11:40:43

19. [7764](http://github.com/cms-sw/cmsdist/pull/7764){:target="_blank"}  from **@cms-sw**: Update mctester to 1.25.1 created: 2022-04-07 09:36:42 merged: 2022-04-08 03:24:13

20. [7762](http://github.com/cms-sw/cmsdist/pull/7762){:target="_blank"}  from **@smuzaffar**: Updated root to tip of branch v6-24-00-patches created: 2022-04-06 20:02:08 merged: 2022-04-08 03:24:40

21. [7761](http://github.com/cms-sw/cmsdist/pull/7761){:target="_blank"}  from **@cms-sw**: Update rdma-core to 39.1 created: 2022-04-06 14:59:59 merged: 2022-04-08 03:31:13

22. [7759](http://github.com/cms-sw/cmsdist/pull/7759){:target="_blank"}  from **@cms-sw**: xrootd: enable readline and did some cleanup created: 2022-04-06 13:58:31 merged: 2022-04-07 21:57:46

23. [7758](http://github.com/cms-sw/cmsdist/pull/7758){:target="_blank"}  from **@cms-sw**: Update OpenCV to 4.5.5 created: 2022-04-06 13:17:01 merged: 2022-04-08 18:53:10

24. [7756](http://github.com/cms-sw/cmsdist/pull/7756){:target="_blank"}  from **@cms-sw**: Update opencl-cpp to 2.0.6 and change URL created: 2022-04-06 13:01:48 merged: 2022-04-08 18:53:50

25. [7754](http://github.com/cms-sw/cmsdist/pull/7754){:target="_blank"}  from **@cms-sw**: Update tag for RecoMuon-TrackerSeedGenerator to V00-04-00 created: 2022-04-06 12:17:35 merged: 2022-04-06 12:21:48

26. [7749](http://github.com/cms-sw/cmsdist/pull/7749){:target="_blank"}  from **@cms-sw**: Update cuDNN to v8.3.3.40 for CUDA 11.5 created: 2022-04-05 13:48:57 merged: 2022-04-09 16:14:16

27. [7746](http://github.com/cms-sw/cmsdist/pull/7746){:target="_blank"}  from **@cms-sw**: Keep soversion in HepMC3 recipe created: 2022-04-04 14:06:35 merged: 2022-04-05 13:13:16

28. [7745](http://github.com/cms-sw/cmsdist/pull/7745){:target="_blank"}  from **@cms-sw**: disable scipy auto provides as it sometimes hangs the rpm build process created: 2022-04-04 09:29:55 merged: 2022-04-05 10:08:10

29. [7743](http://github.com/cms-sw/cmsdist/pull/7743){:target="_blank"}  from **@cms-sw**: Update highfive to 2.3.1 created: 2022-04-01 14:41:45 merged: 2022-04-04 09:32:07

30. [7741](http://github.com/cms-sw/cmsdist/pull/7741){:target="_blank"}  from **@cms-sw**: Update dwz to 0.14 created: 2022-04-01 09:04:01 merged: 2022-04-01 14:37:02

31. [7738](http://github.com/cms-sw/cmsdist/pull/7738){:target="_blank"}  from **@fwyzard**: Update OpenMPI to version 4.1.3 created: 2022-03-31 21:11:53 merged: 2022-04-04 09:32:39

32. [7737](http://github.com/cms-sw/cmsdist/pull/7737){:target="_blank"}  from **@cms-sw**: Update tag for RecoMuon-MuonIdentification to V01-14-00 created: 2022-03-31 15:43:29 merged: 2022-03-31 15:46:10

33. [7733](http://github.com/cms-sw/cmsdist/pull/7733){:target="_blank"}  from **@cms-sw**: Update tag for DQM-EcalMonitorClient to V00-02-00 created: 2022-03-30 20:12:50 merged: 2022-03-30 20:20:30

34. [7728](http://github.com/cms-sw/cmsdist/pull/7728){:target="_blank"}  from **@gartung**: Update to latest Intel compiler: icpx  created: 2022-03-28 16:02:05 merged: 2022-04-01 06:19:36

35. [7712](http://github.com/cms-sw/cmsdist/pull/7712){:target="_blank"}  from **@cms-sw**: Update professor2 to 2.3.3 created: 2022-03-23 14:36:46 merged: 2022-04-06 11:38:44
