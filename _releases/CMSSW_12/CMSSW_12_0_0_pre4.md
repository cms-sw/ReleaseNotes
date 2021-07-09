---
layout: post
rel_link:  "12_0_0_pre4"
title:  "CMSSW_12_0_0_pre4"
date:   2021-07-08 19:35:39
categories: cmssw
relmajor: 12
relminor: 0
relsubminor: 0
relpre: _pre4
---

# CMSSW_12_0_0_pre4
#### Changes since CMSSW_12_0_0_pre3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_0_0_pre3...CMSSW_12_0_0_pre4)



1. [34398](http://github.com/cms-sw/cmssw/pull/34398){:target="_blank"}  from **@smuzaffar**: python2 clean: fixed unit test to use python3 `core` created: 2021-07-08 11:19:17 merged: 2021-07-08 15:36:46

2. [34397](http://github.com/cms-sw/cmssw/pull/34397){:target="_blank"}  from **@smuzaffar**: python2 cleanup: Updated unit test to use python3 `dqm` created: 2021-07-08 11:11:09 merged: 2021-07-08 15:36:18

3. [34396](http://github.com/cms-sw/cmssw/pull/34396){:target="_blank"}  from **@smuzaffar**: Use python3 to correct pick sqlalchemy and ROOT `alca` created: 2021-07-08 11:00:48 merged: 2021-07-08 15:04:43

4. [34390](http://github.com/cms-sw/cmssw/pull/34390){:target="_blank"}  from **@OzAmram**: Remove 2D pixel template B field warning for 0T `alca` created: 2021-07-07 19:58:21 merged: 2021-07-08 12:24:51

5. [34386](http://github.com/cms-sw/cmssw/pull/34386){:target="_blank"}  from **@VinInn**: enforce memory order to avoid crash on Ampere `reconstruction` created: 2021-07-07 15:39:41 merged: 2021-07-08 14:05:59

6. [34376](http://github.com/cms-sw/cmssw/pull/34376){:target="_blank"}  from **@jfernan2**: [DQM] Subsystem packages to use python3 `dqm` created: 2021-07-07 10:58:46 merged: 2021-07-07 15:47:04

7. [34374](http://github.com/cms-sw/cmssw/pull/34374){:target="_blank"}  from **@jfernan2**: [DQM] Move to python3 all scripts in DQMServices `dqm` created: 2021-07-07 10:17:46 merged: 2021-07-07 13:15:56

8. [34373](http://github.com/cms-sw/cmssw/pull/34373){:target="_blank"}  from **@ggovi**: Moving uploadCondition.py to python3 `db` created: 2021-07-07 09:29:43 merged: 2021-07-07 14:08:28

9. [34372](http://github.com/cms-sw/cmssw/pull/34372){:target="_blank"}  from **@smuzaffar**: use python for FW edm utilities run by scram `core` created: 2021-07-07 09:09:52 merged: 2021-07-07 13:16:45

10. [34371](http://github.com/cms-sw/cmssw/pull/34371){:target="_blank"}  from **@jeongeun**: Migrate module configuration in RecoEgamma{EgammaIsolationAlgos} to use default cfipython `reconstruction` created: 2021-07-07 05:43:04 merged: 2021-07-07 15:46:07

11. [34369](http://github.com/cms-sw/cmssw/pull/34369){:target="_blank"}  from **@Dr15Jones**: Prefetch for EDLoopers `alca` `core` created: 2021-07-06 18:23:15 merged: 2021-07-07 16:30:00

12. [34366](http://github.com/cms-sw/cmssw/pull/34366){:target="_blank"}  from **@jfernan2**: [DQM] Set assertLegacySafe to False `dqm` created: 2021-07-06 17:03:23 merged: 2021-07-07 09:07:43

13. [34365](http://github.com/cms-sw/cmssw/pull/34365){:target="_blank"}  from **@calderona**: Migrate ED modules to use esConsumes in Validation/RecoMuon `dqm` created: 2021-07-06 16:59:10 merged: 2021-07-07 15:46:54

14. [34364](http://github.com/cms-sw/cmssw/pull/34364){:target="_blank"}  from **@davidlange6**: move scripts in Utilties and Validation to py3 `core` `dqm` created: 2021-07-06 16:46:02 merged: 2021-07-07 13:17:12

15. [34352](http://github.com/cms-sw/cmssw/pull/34352){:target="_blank"}  from **@davidlange6**: Move FWCore and Configuration python scripts to python3 `core` `operations` `pdmv` `upgrade` created: 2021-07-06 14:29:00 merged: 2021-07-07 15:51:36

16. [34351](http://github.com/cms-sw/cmssw/pull/34351){:target="_blank"}  from **@bsunanda**: Run3-trk06 Add a script for dumping Geometry defined using dd4hep `geometry` created: 2021-07-06 13:29:54 merged: 2021-07-07 13:17:41

17. [34348](http://github.com/cms-sw/cmssw/pull/34348){:target="_blank"}  from **@francescobrivio**: Update BeamSpotOnline tags for CRUZET `alca` `dqm` created: 2021-07-06 08:10:07 merged: 2021-07-07 09:14:28

18. [34344](http://github.com/cms-sw/cmssw/pull/34344){:target="_blank"}  from **@cvuosalo**: [DD4hep] Add support for Assembly tags in XML and for creating DB payload `geometry` created: 2021-07-06 05:15:51 merged: 2021-07-08 17:38:49

19. [34343](http://github.com/cms-sw/cmssw/pull/34343){:target="_blank"}  from **@cvuosalo**: [DD4hep] Add DD4hep Run 3 workflow that reads geometry from DB `pdmv` `upgrade` created: 2021-07-06 04:01:19 merged: 2021-07-08 17:40:46

20. [34342](http://github.com/cms-sw/cmssw/pull/34342){:target="_blank"}  from **@abhih1**: Add new plots to ECAL Offline DQM with Pedestal and Laser transparency correction from the Database `dqm` created: 2021-07-06 00:36:54 merged: 2021-07-07 13:48:19

21. [34340](http://github.com/cms-sw/cmssw/pull/34340){:target="_blank"}  from **@bsunanda**: Phase2-hgx288 Read all parameters needed for V16 geometry of HGCal `geometry` `upgrade` created: 2021-07-05 21:35:47 merged: 2021-07-07 13:48:50

22. [34339](http://github.com/cms-sw/cmssw/pull/34339){:target="_blank"}  from **@hatakeyamak**: Drop type specs in modifiers under Validation/RecoParticleFlow and some cleanup `dqm` created: 2021-07-05 19:43:12 merged: 2021-07-06 15:49:19

23. [34334](http://github.com/cms-sw/cmssw/pull/34334){:target="_blank"}  from **@eyigitba**: EMTF Emulator Update to Add Run 3 CSC TP variables `l1` created: 2021-07-05 15:12:20 merged: 2021-07-06 16:06:28

24. [34332](http://github.com/cms-sw/cmssw/pull/34332){:target="_blank"}  from **@mmusich**: fix definition override in RecoTrackerP5_cff.py `reconstruction` created: 2021-07-05 14:05:01 merged: 2021-07-06 09:11:15

25. [34328](http://github.com/cms-sw/cmssw/pull/34328){:target="_blank"}  from **@Purva-Chaudhari**: Use std::bind in place of boost:bind `core` `db` `generators` `geometry` `reconstruction` `simulation` `visualization` created: 2021-07-04 17:32:13 merged: 2021-07-08 09:33:28

26. [34326](http://github.com/cms-sw/cmssw/pull/34326){:target="_blank"}  from **@mmusich**: Fix issues with SiPixelQualityMapComparisonBase `db` `dqm` created: 2021-07-04 15:01:29 merged: 2021-07-07 09:41:40

27. [34325](http://github.com/cms-sw/cmssw/pull/34325){:target="_blank"}  from **@guitargeek**: Use std:: functions instead of TMath:: functions in RecoEgamma `reconstruction` created: 2021-07-04 00:07:23 merged: 2021-07-07 15:46:22

28. [34324](http://github.com/cms-sw/cmssw/pull/34324){:target="_blank"}  from **@bsunanda**: Phase2-gem63 Include the right version of MuonNumbering file for many scenarios `geometry` `upgrade` created: 2021-07-03 15:03:32 merged: 2021-07-06 02:43:27

29. [34323](http://github.com/cms-sw/cmssw/pull/34323){:target="_blank"}  from **@smuzaffar**: Update condformat serialization script to use python3 `db` created: 2021-07-02 23:10:26 merged: 2021-07-05 00:10:40

30. [34321](http://github.com/cms-sw/cmssw/pull/34321){:target="_blank"}  from **@wddgit**: Fix Framework unit test script bugs `core` created: 2021-07-02 21:27:08 merged: 2021-07-06 15:50:00

31. [34320](http://github.com/cms-sw/cmssw/pull/34320){:target="_blank"}  from **@bsunanda**: Run4-gem63B Add 2 useful scripts to test dd4hep for Phase2 `simulation` created: 2021-07-02 19:38:26 merged: 2021-07-04 01:51:03

32. [34319](http://github.com/cms-sw/cmssw/pull/34319){:target="_blank"}  from **@bsunanda**: Run3-gem63A Modify debug statements to resolve the issue of failures for phase2 dd4hep `geometry` `simulation` created: 2021-07-02 19:24:21 merged: 2021-07-04 01:53:13

33. [34317](http://github.com/cms-sw/cmssw/pull/34317){:target="_blank"}  from **@dan131riley**: Fix SiPixelDigisClustersFromSoA EDM_ML_DEBUG compilation error `reconstruction` created: 2021-07-02 16:15:48 merged: 2021-07-04 01:51:57

34. [34315](http://github.com/cms-sw/cmssw/pull/34315){:target="_blank"}  from **@PFCal-dev**: [HGCal Trigger] Fix bug in auto-encoder trigger cell normalization `l1` `upgrade` created: 2021-07-02 09:32:16 merged: 2021-07-06 15:47:29

35. [34312](http://github.com/cms-sw/cmssw/pull/34312){:target="_blank"}  from **@dmeuser**: Barycenter histograms for TkDQM `dqm` created: 2021-07-02 08:21:55 merged: 2021-07-02 13:50:38

36. [34311](http://github.com/cms-sw/cmssw/pull/34311){:target="_blank"}  from **@felicepantaleo**: [HGCAL] Validation - Purity and efficiency `dqm` created: 2021-07-02 08:06:53 merged: 2021-07-02 13:52:28

37. [34308](http://github.com/cms-sw/cmssw/pull/34308){:target="_blank"}  from **@dildick**: Update TMB matching parameters for CSC trigger primitives `l1` created: 2021-07-02 03:33:41 merged: 2021-07-07 01:05:19

38. [34307](http://github.com/cms-sw/cmssw/pull/34307){:target="_blank"}  from **@guitargeek**: Merge .h and .cc files of PhysicsTools/PatAlgos plugins `reconstruction` created: 2021-07-01 22:05:17 merged: 2021-07-05 00:09:50

39. [34306](http://github.com/cms-sw/cmssw/pull/34306){:target="_blank"}  from **@smuzaffar**: Split dqm configuration tests in smaller parts to avoid timeouts `dqm` created: 2021-07-01 21:13:54 merged: 2021-07-02 09:33:37

40. [34305](http://github.com/cms-sw/cmssw/pull/34305){:target="_blank"}  from **@bsunanda**: Run3-ft33 Use of ESGetToken in analyzer code of HFNose `geometry` created: 2021-07-01 20:29:14 merged: 2021-07-07 13:17:55

41. [34304](http://github.com/cms-sw/cmssw/pull/34304){:target="_blank"}  from **@bapavlov**: ES consumes fixed  `simulation` created: 2021-07-01 19:30:50 merged: 2021-07-04 01:56:48

42. [34300](http://github.com/cms-sw/cmssw/pull/34300){:target="_blank"}  from **@davidlange6**: change default cmsRun to use python3.  `core` created: 2021-07-01 15:17:52 merged: 2021-07-07 00:55:40

43. [34299](http://github.com/cms-sw/cmssw/pull/34299){:target="_blank"}  from **@mmusich**: improve realism of Run3 cosmics workflows `pdmv` `upgrade` created: 2021-07-01 15:14:28 merged: 2021-07-02 13:53:19

44. [34298](http://github.com/cms-sw/cmssw/pull/34298){:target="_blank"}  from **@davidlange6**: update getPayloadData.py to python3 in sync with changing boost_python to python3 `db` created: 2021-07-01 15:00:24 merged: 2021-07-06 00:05:59

45. [34297](http://github.com/cms-sw/cmssw/pull/34297){:target="_blank"}  from **@mmusich**: Migrate to es Consumes `Alignment/CocoaApplication` and `Alignment/LaserDQM` `alca` created: 2021-07-01 11:44:19 merged: 2021-07-05 09:36:53

46. [34295](http://github.com/cms-sw/cmssw/pull/34295){:target="_blank"}  from **@MilanoBicocca-pix**: modified the various (ES)producers for express stream and HLT `alca` `reconstruction` created: 2021-07-01 09:05:28 merged: 2021-07-05 14:31:06

47. [34292](http://github.com/cms-sw/cmssw/pull/34292){:target="_blank"}  from **@thomreis**: Fix crash in ECAL local reco on GPU if ECAL is not in the run `reconstruction` created: 2021-06-30 15:42:53 merged: 2021-07-01 00:49:17

48. [34291](http://github.com/cms-sw/cmssw/pull/34291){:target="_blank"}  from **@srimanob**: Add D76 prod-like to relval_2026 `pdmv` `upgrade` created: 2021-06-30 14:37:37 merged: 2021-07-05 04:20:43

49. [34288](http://github.com/cms-sw/cmssw/pull/34288){:target="_blank"}  from **@davidlange6**: add gil acquire when modifying python object `core` created: 2021-06-30 13:45:58 merged: 2021-07-01 11:49:47

50. [34286](http://github.com/cms-sw/cmssw/pull/34286){:target="_blank"}  from **@CMSTrackerDPG**: make CPEFast to better reproduce Generic (w/o track angle) `heterogeneous` `reconstruction` created: 2021-06-30 13:15:21 merged: 2021-07-08 14:05:46

51. [34285](http://github.com/cms-sw/cmssw/pull/34285){:target="_blank"}  from **@pieterdavid**: SiStripDetInfoFileReader refactoring and cleanup `alca` `db` `dqm` `reconstruction` created: 2021-06-30 09:49:30 merged: 2021-07-04 01:55:01

52. [34284](http://github.com/cms-sw/cmssw/pull/34284){:target="_blank"}  from **@bsunanda**: Phase2-gex81 Modify the Phase2 scenarios to work for dd4hep `geometry` `upgrade` created: 2021-06-29 19:43:33 merged: 2021-07-02 15:04:43

53. [34283](http://github.com/cms-sw/cmssw/pull/34283){:target="_blank"}  from **@Dr15Jones**: Removed global namespace using from XercesStrUtils.h `alca` `core` created: 2021-06-29 17:52:49 merged: 2021-07-05 09:35:54

54. [34282](http://github.com/cms-sw/cmssw/pull/34282){:target="_blank"}  from **@abdoulline**: HCAL: move data-specific SeverityLevel customization(s) to Reconstruction_Data_cff.py `operations` `reconstruction` created: 2021-06-29 17:34:22 merged: 2021-07-04 04:44:43

55. [34281](http://github.com/cms-sw/cmssw/pull/34281){:target="_blank"}  from **@slava77**: CPU optimization in muonisolation::TrackSelector: postpone eta/phi computation until needed `reconstruction` created: 2021-06-29 15:46:21 merged: 2021-07-01 00:52:32

56. [34280](http://github.com/cms-sw/cmssw/pull/34280){:target="_blank"}  from **@Dr15Jones**: Moved using namespace within PyBind11 function `core` created: 2021-06-29 14:19:42 merged: 2021-06-30 00:18:41

57. [34279](http://github.com/cms-sw/cmssw/pull/34279){:target="_blank"}  from **@perrotta**: Initialize file size for MatacqProducer::msize `reconstruction` created: 2021-06-29 12:25:00 merged: 2021-07-01 07:47:34

58. [34278](http://github.com/cms-sw/cmssw/pull/34278){:target="_blank"}  from **@lwang046**: HcalDQM - Drop type specs for python files `dqm` created: 2021-06-29 12:13:01 merged: 2021-06-30 14:01:19

59. [34277](http://github.com/cms-sw/cmssw/pull/34277){:target="_blank"}  from **@bsunanda**: Run4-hgx287Y Geometry definition for the mixed layers of HGCal V16 `geometry` `upgrade` created: 2021-06-29 12:00:39 merged: 2021-07-02 15:03:28

60. [34276](http://github.com/cms-sw/cmssw/pull/34276){:target="_blank"}  from **@felicepantaleo**: [HGCAL] Fill regressed energy for SimTracksters `reconstruction` `upgrade` created: 2021-06-29 08:53:26 merged: 2021-06-30 00:16:19

61. [34275](http://github.com/cms-sw/cmssw/pull/34275){:target="_blank"}  from **@missirol**: update track-weight map of 4D primary vertices w/o BS constraint `reconstruction` created: 2021-06-29 05:11:16 merged: 2021-07-02 00:26:23

62. [34274](http://github.com/cms-sw/cmssw/pull/34274){:target="_blank"}  from **@Dr15Jones**: Mark ParentageRegistry as thread safe `core` created: 2021-06-28 18:41:00 merged: 2021-06-29 06:07:34

63. [34273](http://github.com/cms-sw/cmssw/pull/34273){:target="_blank"}  from **@thomreis**: ECAL esConsumes migrations in EventFilter and RecoLocalCalo `reconstruction` created: 2021-06-28 17:45:25 merged: 2021-07-01 15:04:43

64. [34270](http://github.com/cms-sw/cmssw/pull/34270){:target="_blank"}  from **@mmusich**: Migrate to esConsumes `Alignment/CommonAlignmentMonitor` `alca` created: 2021-06-28 12:17:17 merged: 2021-07-02 15:02:42

65. [34269](http://github.com/cms-sw/cmssw/pull/34269){:target="_blank"}  from **@missirol**: fix for ndof of 4D primary vertices `reconstruction` created: 2021-06-28 07:09:46 merged: 2021-06-29 00:36:29

66. [34268](http://github.com/cms-sw/cmssw/pull/34268){:target="_blank"}  from **@mmasciov**: Fixing missing comma in trackingPlots `dqm` created: 2021-06-28 01:47:41 merged: 2021-06-28 14:00:49

67. [34267](http://github.com/cms-sw/cmssw/pull/34267){:target="_blank"}  from **@bsunanda**: Run3-hcx298 Correct the scripts for Geometry related to DB for HCAL `geometry` created: 2021-06-27 22:07:14 merged: 2021-06-30 00:08:51

68. [34266](http://github.com/cms-sw/cmssw/pull/34266){:target="_blank"}  from **@sroychow**: DQM : migrate modules for esConumes part 2 `dqm` created: 2021-06-27 10:39:14 merged: 2021-06-29 00:40:29

69. [34264](http://github.com/cms-sw/cmssw/pull/34264){:target="_blank"}  from **@smuzaffar**: Fixes needed for UBSAN IBs: null destination pointer `alca` created: 2021-06-27 07:35:15 merged: 2021-06-28 14:01:14

70. [34262](http://github.com/cms-sw/cmssw/pull/34262){:target="_blank"}  from **@bsunanda**: Run3-gem62G Use of ESGetToken for CSCGeometry `geometry` created: 2021-06-26 19:16:15 merged: 2021-06-27 09:01:41

71. [34261](http://github.com/cms-sw/cmssw/pull/34261){:target="_blank"}  from **@smuzaffar**: [ASAN] Fix for ODR violation `generators` created: 2021-06-26 18:15:27 merged: 2021-06-28 13:00:14

72. [34260](http://github.com/cms-sw/cmssw/pull/34260){:target="_blank"}  from **@smuzaffar**: BuildFile cleanup: remove deps on itself `dqm` created: 2021-06-26 18:09:34 merged: 2021-06-26 21:34:37

73. [34259](http://github.com/cms-sw/cmssw/pull/34259){:target="_blank"}  from **@VinInn**: Make PixelDigi conversion to legacy optional `core` `reconstruction` created: 2021-06-26 15:56:48 merged: 2021-06-30 14:20:06

74. [34258](http://github.com/cms-sw/cmssw/pull/34258){:target="_blank"}  from **@smuzaffar**: [ASAN] Fix one definition rules violations `generators` created: 2021-06-26 14:44:03 merged: 2021-06-28 13:00:22

75. [34257](http://github.com/cms-sw/cmssw/pull/34257){:target="_blank"}  from **@mmusich**: getPayloadData unit test, if no plugins are found, look in the `CMSSW_RELEASE_BASE` `db` created: 2021-06-26 09:59:00 merged: 2021-06-26 21:36:14

76. [34256](http://github.com/cms-sw/cmssw/pull/34256){:target="_blank"}  from **@slava77**: trackingNtuple updates from mkFit/LST developments `dqm` `reconstruction` created: 2021-06-26 03:53:41 merged: 2021-06-30 15:00:52

77. [34253](http://github.com/cms-sw/cmssw/pull/34253){:target="_blank"}  from **@slava77**: "is not" -> "!=" in PatAlgos trigTools.py  `reconstruction` created: 2021-06-25 18:43:28 merged: 2021-06-27 07:52:55

78. [34252](http://github.com/cms-sw/cmssw/pull/34252){:target="_blank"}  from **@TaeunKwon**: Updates of the TP reconstruction algorithm to fix the TP energy saturation effect `l1` created: 2021-06-25 17:48:19 merged: 2021-06-29 13:18:07

79. [34251](http://github.com/cms-sw/cmssw/pull/34251){:target="_blank"}  from **@bsunanda**: Phase2-hgx287Y Update the algorithms for mixed layers to be ready for the V16 mixed layer `geometry` `upgrade` created: 2021-06-25 15:23:58 merged: 2021-06-27 07:53:25

80. [34250](http://github.com/cms-sw/cmssw/pull/34250){:target="_blank"}  from **@VinInn**: Speed up Patatrack CA `heterogeneous` `reconstruction` created: 2021-06-25 13:48:15 merged: 2021-06-30 00:24:53

81. [34249](http://github.com/cms-sw/cmssw/pull/34249){:target="_blank"}  from **@bsunanda**: Run3-gex80B Use of alternative ESGetToken initialization for DDD/DD4Hep in Tracker `geometry` created: 2021-06-25 13:09:48 merged: 2021-06-26 01:05:51

82. [34248](http://github.com/cms-sw/cmssw/pull/34248){:target="_blank"}  from **@mmusich**: Finalize migration to esConsumes of `Alignment/TrackerAlignment` and `Alignment/SurveyAnalysis` `alca` created: 2021-06-25 12:37:16 merged: 2021-07-05 09:37:09

83. [34246](http://github.com/cms-sw/cmssw/pull/34246){:target="_blank"}  from **@bsunanda**: Run3-gem62F Use of alternative ESGetToken initialization for DDD/DD4Hep in Muon/HGCal `geometry` `upgrade` created: 2021-06-25 02:03:07 merged: 2021-06-27 09:04:56

84. [34245](http://github.com/cms-sw/cmssw/pull/34245){:target="_blank"}  from **@dildick**: Updates for Run-3 CSC trigger primitives `dqm` `l1` `simulation` created: 2021-06-25 01:28:10 merged: 2021-06-30 00:20:58

85. [34244](http://github.com/cms-sw/cmssw/pull/34244){:target="_blank"}  from **@bsunanda**: Run3-hcx297 Take care of DDD or DD4Hep in esGetToken for Hcal code `geometry` created: 2021-06-25 01:27:35 merged: 2021-06-26 01:07:15

86. [34242](http://github.com/cms-sw/cmssw/pull/34242){:target="_blank"}  from **@bsunanda**: Run3-gex80A Use ESGetToken in codes of Geometry/Calo... analyzers `geometry` created: 2021-06-24 15:42:33 merged: 2021-06-25 07:34:51

87. [34241](http://github.com/cms-sw/cmssw/pull/34241){:target="_blank"}  from **@bsunanda**: Run4-hgx287X Extend the work for V16 Geometry of HGCal `geometry` `upgrade` created: 2021-06-24 15:32:59 merged: 2021-06-27 07:54:06

88. [34240](http://github.com/cms-sw/cmssw/pull/34240){:target="_blank"}  from **@mmusich**: [Tracker Alignment] Add di-electron vertex validation `alca` created: 2021-06-24 14:18:49 merged: 2021-06-26 07:16:07

89. [34238](http://github.com/cms-sw/cmssw/pull/34238){:target="_blank"}  from **@cecilecaillol**: L1T Phase-2: add tracking jets `l1` `upgrade` created: 2021-06-24 09:13:03 merged: 2021-07-01 07:35:29

90. [34237](http://github.com/cms-sw/cmssw/pull/34237){:target="_blank"}  from **@smuzaffar**: [ASAN] Fix duplicate definition of hjRandomEngine `generators` created: 2021-06-24 08:51:21 merged: 2021-06-24 14:11:21

91. [34236](http://github.com/cms-sw/cmssw/pull/34236){:target="_blank"}  from **@cecilecaillol**: L1T Phase-1: update MET pileup mitigation `l1` created: 2021-06-24 08:48:29 merged: 2021-06-24 15:21:48

92. [34235](http://github.com/cms-sw/cmssw/pull/34235){:target="_blank"}  from **@cecilecaillol**: L1T Phase-1: Adding L1boosted objects `l1` created: 2021-06-24 08:29:22 merged: 2021-07-02 13:56:56

93. [34234](http://github.com/cms-sw/cmssw/pull/34234){:target="_blank"}  from **@smuzaffar**: fix allocation/deallocation mismatch issue in ASAN `analysis` created: 2021-06-24 08:05:13 merged: 2021-06-25 00:06:29

94. [34233](http://github.com/cms-sw/cmssw/pull/34233){:target="_blank"}  from **@ggovi**: Moving condition DB tools to python3 `db` created: 2021-06-24 07:21:05 merged: 2021-07-05 00:11:29

95. [34232](http://github.com/cms-sw/cmssw/pull/34232){:target="_blank"}  from **@guitargeek**: Avoid illegal import from PhysicsTools/PatAlgos/plugins in MuonAnalysis `analysis` `reconstruction` created: 2021-06-23 22:23:49 merged: 2021-06-25 00:09:59

96. [34231](http://github.com/cms-sw/cmssw/pull/34231){:target="_blank"}  from **@wddgit**: Enable concurrent lumis and IOVs by default when number of streams is at least 2 `core` created: 2021-06-23 21:43:38 merged: 2021-07-03 02:03:23

97. [34230](http://github.com/cms-sw/cmssw/pull/34230){:target="_blank"}  from **@smuzaffar**: Fix needed due to catch2 update `dqm` created: 2021-06-23 21:40:58 merged: 2021-06-24 00:07:01

98. [34229](http://github.com/cms-sw/cmssw/pull/34229){:target="_blank"}  from **@slava77**: remove 2017 tests from dataProcessing runCfgTest `operations` created: 2021-06-23 17:36:21 merged: 2021-06-24 00:30:25

99. [34225](http://github.com/cms-sw/cmssw/pull/34225){:target="_blank"}  from **@bsunanda**: Run3-gem62E Correct use of ESGetToken for GEMGeometry using suggestion from Matti `geometry` `upgrade` created: 2021-06-23 15:50:35 merged: 2021-06-28 14:32:13

100. [34222](http://github.com/cms-sw/cmssw/pull/34222){:target="_blank"}  from **@bsunanda**: Run3-gem62D Use of ESGetToken for DTGeometry `geometry` created: 2021-06-23 14:11:09 merged: 2021-06-26 01:07:41

101. [34221](http://github.com/cms-sw/cmssw/pull/34221){:target="_blank"}  from **@mmusich**: add protection against missing cast to Phase2TrackerRecHit1D in Phase2OTValidateTrackingRecHit `dqm` created: 2021-06-23 13:19:04 merged: 2021-06-24 00:21:33

102. [34220](http://github.com/cms-sw/cmssw/pull/34220){:target="_blank"}  from **@jfernan2**: RFC: [DQM] First prototype of nanoDQMIO with single LS granularity `dqm` created: 2021-06-23 08:35:15 merged: 2021-06-30 08:52:56

103. [34219](http://github.com/cms-sw/cmssw/pull/34219){:target="_blank"}  from **@cvuosalo**: [DD4hep] Enable Run 3 DD4hep workflows to read geometry from DB `geometry` `operations` `upgrade` created: 2021-06-23 03:42:19 merged: 2021-07-04 04:48:14

104. [34218](http://github.com/cms-sw/cmssw/pull/34218){:target="_blank"}  from **@malbouis**: Include new PPS geometry tag and Hcal MC tag in GTs `alca` created: 2021-06-23 00:35:15 merged: 2021-06-24 07:25:06

105. [34217](http://github.com/cms-sw/cmssw/pull/34217){:target="_blank"}  from **@davidlange6**: convert to unit test in FWCore/PythonFramework to pybind11 `core` created: 2021-06-22 20:38:44 merged: 2021-06-23 14:43:07

106. [34216](http://github.com/cms-sw/cmssw/pull/34216){:target="_blank"}  from **@bsunanda**: Run3-gem62C Use ESGetToken in RPC geometry packages `geometry` created: 2021-06-22 20:11:31 merged: 2021-06-26 01:13:27

107. [34215](http://github.com/cms-sw/cmssw/pull/34215){:target="_blank"}  from **@cms-L1TK**: Update L1 tracking for HL-LHC (replacement of #34028) `l1` `upgrade` created: 2021-06-22 19:00:14 merged: 2021-07-07 09:12:41

108. [34214](http://github.com/cms-sw/cmssw/pull/34214){:target="_blank"}  from **@bsunanda**: Run3-gem62B Use of ESGetToken in GEM geometry packages `geometry` `upgrade` created: 2021-06-22 17:56:22 merged: 2021-06-23 00:28:49

109. [34210](http://github.com/cms-sw/cmssw/pull/34210){:target="_blank"}  from **@VinInn**: shift legend's position in MTV tuning plots `dqm` created: 2021-06-22 15:09:40 merged: 2021-06-23 08:27:48

110. [34209](http://github.com/cms-sw/cmssw/pull/34209){:target="_blank"}  from **@bsunanda**: Run3-gem62A Take care of ESGetToken in Geometry/MuonNumbering `geometry` created: 2021-06-22 14:35:42 merged: 2021-06-23 00:15:03

111. [34208](http://github.com/cms-sw/cmssw/pull/34208){:target="_blank"}  from **@sroychow**: DQM: migrate modules to esConsumes `dqm` `l1` created: 2021-06-22 13:39:17 merged: 2021-06-24 15:28:36

112. [34207](http://github.com/cms-sw/cmssw/pull/34207){:target="_blank"}  from **@casarsa**: MTD Validation: SIM clusters `dqm` created: 2021-06-22 13:03:25 merged: 2021-06-25 00:11:20

113. [34205](http://github.com/cms-sw/cmssw/pull/34205){:target="_blank"}  from **@mrodozov**: Cast indexFor to unsigned for size comparison `alca` `core` `db` created: 2021-06-22 09:43:16 merged: 2021-06-23 13:30:08

114. [34204](http://github.com/cms-sw/cmssw/pull/34204){:target="_blank"}  from **@sviret**: Fix in the MPA stub building code `l1` `upgrade` created: 2021-06-22 08:45:08 merged: 2021-06-25 15:37:44

115. [34201](http://github.com/cms-sw/cmssw/pull/34201){:target="_blank"}  from **@bsunanda**: Phase2-hgx287X Next step for V16 Geometry for HGCAL `geometry` `upgrade` created: 2021-06-21 22:15:59 merged: 2021-06-25 15:38:43

116. [34200](http://github.com/cms-sw/cmssw/pull/34200){:target="_blank"}  from **@smuzaffar**: fix unit test: download file in tmp area and add the path in PYTHONPATH `generators` created: 2021-06-21 20:17:16 merged: 2021-06-22 09:13:57

117. [34199](http://github.com/cms-sw/cmssw/pull/34199){:target="_blank"}  from **@mmusich**: add unit tests for getPayloadData.py `db` created: 2021-06-21 17:33:53 merged: 2021-06-25 15:36:36

118. [34198](http://github.com/cms-sw/cmssw/pull/34198){:target="_blank"}  from **@trackreco**: Enable mkFit for initialStepPreSplitting with trackingMkFit modifier `dqm` `operations` `reconstruction` created: 2021-06-21 14:27:22 merged: 2021-06-26 07:43:07

119. [34195](http://github.com/cms-sw/cmssw/pull/34195){:target="_blank"}  from **@fabiocos**: MTD reconstruction: revision of the AODSIM event content `dqm` `reconstruction` `upgrade` created: 2021-06-21 10:35:54 merged: 2021-06-25 15:34:54

120. [34192](http://github.com/cms-sw/cmssw/pull/34192){:target="_blank"}  from **@ggovi**: Fix for conddb command line tool `db` created: 2021-06-21 09:36:17 merged: 2021-06-25 09:51:59

121. [34191](http://github.com/cms-sw/cmssw/pull/34191){:target="_blank"}  from **@guitargeek**: BuildFiles cleaning `alca` `db` `dqm` `l1` `reconstruction` `simulation` created: 2021-06-20 22:09:09 merged: 2021-06-23 00:40:40

122. [34190](http://github.com/cms-sw/cmssw/pull/34190){:target="_blank"}  from **@guitargeek**: Replace deprecated ext/hash_map with std::unordered_map `alca` `db` `l1` created: 2021-06-20 16:59:20 merged: 2021-06-25 07:35:06

123. [34188](http://github.com/cms-sw/cmssw/pull/34188){:target="_blank"}  from **@smuzaffar**: remove a unit test which was added by mistake `dqm` created: 2021-06-20 09:16:58 merged: 2021-06-20 09:18:07

124. [34187](http://github.com/cms-sw/cmssw/pull/34187){:target="_blank"}  from **@bsunanda**: Run3-TB61 Modify the cfg's for HCAL Test Beam `geometry` `operations` `simulation` created: 2021-06-19 16:40:28 merged: 2021-06-22 01:00:34

125. [34186](http://github.com/cms-sw/cmssw/pull/34186){:target="_blank"}  from **@smuzaffar**: Split DQM configuration tests in smaller set to make then run fast `dqm` created: 2021-06-19 08:37:50 merged: 2021-06-20 08:57:49

126. [34185](http://github.com/cms-sw/cmssw/pull/34185){:target="_blank"}  from **@smuzaffar**: Fix unit tests to avoid bot rebuild every thing `generators` created: 2021-06-19 08:32:12 merged: 2021-06-21 08:53:53

127. [34183](http://github.com/cms-sw/cmssw/pull/34183){:target="_blank"}  from **@slava77**: Validation/RecoMuon HTrack: make a copy instead of a reference to a temporary `dqm` created: 2021-06-18 14:56:24 merged: 2021-06-20 08:58:39

128. [34182](http://github.com/cms-sw/cmssw/pull/34182){:target="_blank"}  from **@smuzaffar**: Initialize data members to avoid compiler warnings `reconstruction` created: 2021-06-18 13:06:51 merged: 2021-06-24 00:22:23

129. [34181](http://github.com/cms-sw/cmssw/pull/34181){:target="_blank"}  from **@carolinecollard**: Change of strategy in Pixel Charge Reweighting `simulation` created: 2021-06-18 12:56:03 merged: 2021-06-24 09:15:27

130. [34180](http://github.com/cms-sw/cmssw/pull/34180){:target="_blank"}  from **@smuzaffar**: fix DBG IBs warnings about EDM_ML_DEBUG redefined `alca` `core` `dqm` `geometry` `simulation` created: 2021-06-18 12:53:01 merged: 2021-06-21 06:07:33

131. [34179](http://github.com/cms-sw/cmssw/pull/34179){:target="_blank"}  from **@slava77**: remove unused KFFittingSmootherESProducer.h `reconstruction` created: 2021-06-18 12:44:06 merged: 2021-06-19 01:38:48

132. [34178](http://github.com/cms-sw/cmssw/pull/34178){:target="_blank"}  from **@dildick**: Fix mistake in muon shower valid flag. Enable showers in L1T (HadronicShowerTrigger-6) `l1` created: 2021-06-18 12:34:25 merged: 2021-06-22 14:06:22

133. [34175](http://github.com/cms-sw/cmssw/pull/34175){:target="_blank"}  from **@sroychow**: TkDQM: remove OT validation module for vector hits workflow `dqm` `pdmv` `upgrade` created: 2021-06-18 06:58:37 merged: 2021-06-21 08:45:08

134. [34174](http://github.com/cms-sw/cmssw/pull/34174){:target="_blank"}  from **@bsunanda**: Run3-gex79 Take P4 as the default PPS for Run3 scenario `geometry` `upgrade` created: 2021-06-18 01:11:54 merged: 2021-06-23 08:24:46

135. [34173](http://github.com/cms-sw/cmssw/pull/34173){:target="_blank"}  from **@colizz**: Specify separate directories to run external instances in ExternalGeneratorFilter `generators` created: 2021-06-17 19:07:54 merged: 2021-06-21 13:51:48

136. [34172](http://github.com/cms-sw/cmssw/pull/34172){:target="_blank"}  from **@bsunanda**: Run3-hcx296 Update some of the cfg's in view of testing SD's to be used `simulation` created: 2021-06-17 18:09:15 merged: 2021-06-18 11:59:43

137. [34171](http://github.com/cms-sw/cmssw/pull/34171){:target="_blank"}  from **@bsunanda**: Run4-hgx287 Next step for V16 Geometry of HGCal (EE algorithm) `geometry` `upgrade` created: 2021-06-17 18:06:45 merged: 2021-06-22 00:20:38

138. [34170](http://github.com/cms-sw/cmssw/pull/34170){:target="_blank"}  from **@jfernan2**: Drop type specs for DQM/Integration python files `dqm` created: 2021-06-17 17:31:31 merged: 2021-06-22 00:17:04

139. [34167](http://github.com/cms-sw/cmssw/pull/34167){:target="_blank"}  from **@ianna**: [DD4hep] DDDetector ES producer from DB  `geometry` created: 2021-06-17 15:30:34 merged: 2021-06-23 00:03:09

140. [34165](http://github.com/cms-sw/cmssw/pull/34165){:target="_blank"}  from **@francescobrivio**: Update GEMRECO geometry in online GTs `alca` created: 2021-06-17 08:42:51 merged: 2021-06-18 12:01:48

141. [34162](http://github.com/cms-sw/cmssw/pull/34162){:target="_blank"}  from **@bsunanda**: Run2-TB61 Modify the cfg's for testbeam simulation of the combined calorimeter ECAL+HCAL `geometry` `simulation` created: 2021-06-16 23:18:39 merged: 2021-06-18 00:38:51

142. [34160](http://github.com/cms-sw/cmssw/pull/34160){:target="_blank"}  from **@ianna**: implement assembly in dd core `geometry` created: 2021-06-16 15:35:45 merged: 2021-06-18 00:43:59

143. [34159](http://github.com/cms-sw/cmssw/pull/34159){:target="_blank"}  from **@mmusich**: [DQM/TrackerRemapper] add unit tests `alca` `db` `dqm` created: 2021-06-16 15:09:58 merged: 2021-06-22 09:14:34

144. [34158](http://github.com/cms-sw/cmssw/pull/34158){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-TB61 Modify the cfg's for HGCal TB in view of changes in initialuizing SD's `simulation` `upgrade` created: 2021-06-16 14:46:51 merged: 2021-06-19 06:28:22

145. [34156](http://github.com/cms-sw/cmssw/pull/34156){:target="_blank"}  from **@marco-link**: Cleanup of BTV OfflineDQM `dqm` created: 2021-06-16 13:07:28 merged: 2021-06-18 00:36:01

146. [34155](http://github.com/cms-sw/cmssw/pull/34155){:target="_blank"}  from **@jeongeun**: Migrate module config in RecoEgamma{EgammaTools} to use default cfipython `reconstruction` created: 2021-06-16 11:28:38 merged: 2021-06-18 00:43:09

147. [34154](http://github.com/cms-sw/cmssw/pull/34154){:target="_blank"}  from **@civanch**: Fixed warnigs of static analizer in Physics Lists `simulation` created: 2021-06-16 11:24:54 merged: 2021-06-18 00:34:16

148. [34152](http://github.com/cms-sw/cmssw/pull/34152){:target="_blank"}  from **@davidlange6**: adapt python fwk unit tests  `core` `dqm` `geometry` created: 2021-06-16 08:43:46 merged: 2021-06-22 18:42:43

149. [34148](http://github.com/cms-sw/cmssw/pull/34148){:target="_blank"}  from **@smuzaffar**: [DB] Apply code-checks/format `db` created: 2021-06-15 21:28:43 merged: 2021-06-18 05:44:23

150. [34146](http://github.com/cms-sw/cmssw/pull/34146){:target="_blank"}  from **@Dr15Jones**: Allow specification of ES modules in ExternalGeneratorFilter `generators` created: 2021-06-15 18:52:49 merged: 2021-06-21 13:49:44

151. [34142](http://github.com/cms-sw/cmssw/pull/34142){:target="_blank"}  from **@smuzaffar**: [SIMULATION_UPGRADE] Apply code-checks/format `simulation` `upgrade` created: 2021-06-15 14:26:55 merged: 2021-06-18 07:40:42

152. [34140](http://github.com/cms-sw/cmssw/pull/34140){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] code-checks/format; clean code to remove global functions `reconstruction` created: 2021-06-15 14:26:42 merged: 2021-06-23 15:55:56

153. [34139](http://github.com/cms-sw/cmssw/pull/34139){:target="_blank"}  from **@smuzaffar**: [L1_UPGRADE] Apply code-checks/format `l1` `upgrade` created: 2021-06-15 14:26:35 merged: 2021-06-18 07:40:33

154. [34137](http://github.com/cms-sw/cmssw/pull/34137){:target="_blank"}  from **@smuzaffar**: [HLT] Apply code-checks/format `hlt` created: 2021-06-15 14:26:17 merged: 2021-06-22 00:19:13

155. [34135](http://github.com/cms-sw/cmssw/pull/34135){:target="_blank"}  from **@bsunanda**: Phase2-hgx287V New Validation tool for HGCal Geometry from Imran Yusuff `dqm` created: 2021-06-15 13:49:27 merged: 2021-06-18 00:35:01

156. [34134](http://github.com/cms-sw/cmssw/pull/34134){:target="_blank"}  from **@hatakeyamak**: skipPS option for CorrectedECALPFClusterProducer `reconstruction` created: 2021-06-15 11:22:06 merged: 2021-06-18 12:00:33

157. [34128](http://github.com/cms-sw/cmssw/pull/34128){:target="_blank"}  from **@smuzaffar**: [ALCA_RECONSTRUCTION] Apply code-checks/format `alca` `reconstruction` created: 2021-06-15 10:35:27 merged: 2021-06-18 12:55:27

158. [34127](http://github.com/cms-sw/cmssw/pull/34127){:target="_blank"}  from **@smuzaffar**: [ALCA] Apply code-checks/format `alca` created: 2021-06-15 10:35:19 merged: 2021-06-18 12:55:35

159. [34123](http://github.com/cms-sw/cmssw/pull/34123){:target="_blank"}  from **@watson-ij**: Fix sign error in expression in GEM digitizer `simulation` `upgrade` created: 2021-06-15 08:56:24 merged: 2021-06-19 07:31:35

160. [34116](http://github.com/cms-sw/cmssw/pull/34116){:target="_blank"}  from **@bsunanda**: Run3-alca187 Update calibration macros in view of discrepancy in the procedure `alca` created: 2021-06-14 15:23:55 merged: 2021-06-18 13:25:15

161. [34098](http://github.com/cms-sw/cmssw/pull/34098){:target="_blank"}  from **@mmusich**: add customization function to swap offlinePrimaryVertices to offlinePrimaryVerticesWithBS `reconstruction` created: 2021-06-11 14:01:53 merged: 2021-06-18 00:39:47

162. [34093](http://github.com/cms-sw/cmssw/pull/34093){:target="_blank"}  from **@PFCal-dev**: [HGCal trigger] Updates in Module sums and Towers `l1` `upgrade` created: 2021-06-11 09:53:42 merged: 2021-06-22 09:16:14

163. [34082](http://github.com/cms-sw/cmssw/pull/34082){:target="_blank"}  from **@pieterdavid**: Fix SiStripQuality merging with FED errors from a DQM file `alca` `db` `dqm` created: 2021-06-10 13:03:48 merged: 2021-06-29 07:54:08

164. [34070](http://github.com/cms-sw/cmssw/pull/34070){:target="_blank"}  from **@guitargeek**: Remove PhysicsTools/ParallelAnalysis package `analysis` `core` created: 2021-06-09 21:38:18 merged: 2021-06-22 14:13:35

165. [34060](http://github.com/cms-sw/cmssw/pull/34060){:target="_blank"}  from **@mrodozov**: Fix clang warning in OnlineDB/SiStripO2O `db` created: 2021-06-09 13:24:32 merged: 2021-06-29 09:16:00

166. [34025](http://github.com/cms-sw/cmssw/pull/34025){:target="_blank"}  from **@NTrevisani**: Dt extended data format `l1` `upgrade` created: 2021-06-08 13:54:04 merged: 2021-06-21 00:15:33

167. [33983](http://github.com/cms-sw/cmssw/pull/33983){:target="_blank"}  from **@wonpoint4**: MuonHLTSeed MVA Classifier 120X `hlt` `reconstruction` created: 2021-06-04 19:08:52 merged: 2021-06-23 14:54:09

168. [33944](http://github.com/cms-sw/cmssw/pull/33944){:target="_blank"}  from **@Dres90**: Improve parameters handling and output from conditions upload_script_v2 `db` created: 2021-06-02 11:53:24 merged: 2021-06-18 00:38:06

169. [33928](http://github.com/cms-sw/cmssw/pull/33928){:target="_blank"}  from **@mandrenguyen**: Recluster AK4 jets in HI reMiniAOD to avoid rare crash `reconstruction` created: 2021-06-01 11:21:31 merged: 2021-06-29 00:38:34

170. [33889](http://github.com/cms-sw/cmssw/pull/33889){:target="_blank"}  from **@VinInn**: Introduce Quality for PixelTracks. Improve Patatrack duplicate & ambiguity resolution `dqm` `heterogeneous` `reconstruction` created: 2021-05-29 08:31:55 merged: 2021-06-18 12:02:45

171. [33801](http://github.com/cms-sw/cmssw/pull/33801){:target="_blank"}  from **@kpedro88**: shared memory support for SonicTriton `heterogeneous` created: 2021-05-20 22:56:20 merged: 2021-06-18 00:42:09

172. [33583](http://github.com/cms-sw/cmssw/pull/33583){:target="_blank"}  from **@mmusich**: Migrate to esConsumes HIP and MillePede Alignment Algorithms `alca` created: 2021-04-30 07:33:07 merged: 2021-06-22 09:16:32

173. [33365](http://github.com/cms-sw/cmssw/pull/33365){:target="_blank"}  from **@makortel**: Enable misc-definitions-in-headers clang-tidy check `core` created: 2021-04-07 23:49:27 merged: 2021-06-24 06:37:55

#### CMSDIST Changes between Tags REL/CMSSW_12_0_0_pre3/slc7_amd64_gcc900 and REL/CMSSW_12_0_0_pre4/slc7_amd64_gcc900:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_0_0_pre3/slc7_amd64_gcc900...REL/CMSSW_12_0_0_pre4/slc7_amd64_gcc900)



1. [7115](http://github.com/cms-sw/cmsdist/pull/7115){:target="_blank"}  from **@cms-sw**: avoid using hard-coded python version created: 2021-07-08 08:49:19 merged: 2021-07-08 08:49:39

2. [7114](http://github.com/cms-sw/cmsdist/pull/7114){:target="_blank"}  from **@cms-sw**: Remove python deps from cmssw/fwlite created: 2021-07-08 08:25:48 merged: 2021-07-08 08:26:25

3. [7109](http://github.com/cms-sw/cmsdist/pull/7109){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-TrackFindingTracklet to V00-02-00 created: 2021-07-07 09:13:16 merged: 2021-07-07 09:13:52

4. [7108](http://github.com/cms-sw/cmsdist/pull/7108){:target="_blank"}  from **@belforte**: more changes for py3 in CRABClient created: 2021-07-06 09:57:07 merged: 2021-07-07 08:25:57

5. [7107](http://github.com/cms-sw/cmsdist/pull/7107){:target="_blank"}  from **@davidlange6**: move gdb to python3 created: 2021-07-06 06:48:35 merged: 2021-07-07 07:57:10

6. [7105](http://github.com/cms-sw/cmsdist/pull/7105){:target="_blank"}  from **@cms-sw**: remove root_numpy/pandas created: 2021-07-05 20:09:22 merged: 2021-07-05 20:17:08

7. [7101](http://github.com/cms-sw/cmsdist/pull/7101){:target="_blank"}  from **@cms-sw**: [FWLite] added python3 toolfile created: 2021-07-05 10:28:57 merged: 2021-07-05 10:31:16

8. [7099](http://github.com/cms-sw/cmsdist/pull/7099){:target="_blank"}  from **@cms-sw**: More py2/py3 cleanup created: 2021-07-05 07:27:36 merged: 2021-07-05 19:59:30

9. [7095](http://github.com/cms-sw/cmsdist/pull/7095){:target="_blank"}  from **@cms-sw**: remove python2 bindings from opencv and llvm created: 2021-07-02 19:27:35 merged: 2021-07-04 20:06:12

10. [7094](http://github.com/cms-sw/cmsdist/pull/7094){:target="_blank"}  from **@cms-sw**: Revert "remove python2 bindings from opencv and llvm " created: 2021-07-02 19:27:05 merged: 2021-07-02 19:27:12

11. [7093](http://github.com/cms-sw/cmsdist/pull/7093){:target="_blank"}  from **@davidlange6**: remove python2 bindings from opencv and llvm  created: 2021-07-02 08:30:53 merged: 2021-07-02 14:30:21

12. [7092](http://github.com/cms-sw/cmsdist/pull/7092){:target="_blank"}  from **@cms-sw**: Python3 migration: drop py2-cython and only built it for py3 created: 2021-07-02 06:08:17 merged: 2021-07-03 11:48:23

13. [7090](http://github.com/cms-sw/cmsdist/pull/7090){:target="_blank"}  from **@cms-sw**: python3 migration: drop py2-backports created: 2021-07-01 16:54:30 merged: 2021-07-02 05:01:51

14. [7089](http://github.com/cms-sw/cmsdist/pull/7089){:target="_blank"}  from **@cms-sw**: [GOSAM] updated gosam to 2.1.0 created: 2021-07-01 16:34:46 merged: 2021-07-02 05:02:44

15. [7087](http://github.com/cms-sw/cmsdist/pull/7087){:target="_blank"}  from **@cms-sw**: py2 cleanup: fastjet and mxnet-predict build with py3 created: 2021-07-01 10:34:29 merged: 2021-07-02 05:03:40

16. [7086](http://github.com/cms-sw/cmsdist/pull/7086){:target="_blank"}  from **@cms-sw**: py2 cleanup: doxygen lhapdf and libxslt created: 2021-07-01 09:28:43 merged: 2021-07-02 05:04:14

17. [7085](http://github.com/cms-sw/cmsdist/pull/7085){:target="_blank"}  from **@davidlange6**: Move boost to python3 created: 2021-06-30 19:06:07 merged: 2021-07-06 00:05:51

18. [7084](http://github.com/cms-sw/cmsdist/pull/7084){:target="_blank"}  from **@cms-sw**: Py3 drop used pkgs created: 2021-06-30 16:52:04 merged: 2021-06-30 19:10:35

19. [7083](http://github.com/cms-sw/cmsdist/pull/7083){:target="_blank"}  from **@cms-sw**: use python to build ninja created: 2021-06-30 16:40:30 merged: 2021-07-01 07:25:34

20. [7082](http://github.com/cms-sw/cmsdist/pull/7082){:target="_blank"}  from **@cms-sw**: updated xrootd and blackhat to use py3 only; drop distcc/ccache created: 2021-06-30 16:16:42 merged: 2021-07-01 07:25:07

21. [7081](http://github.com/cms-sw/cmsdist/pull/7081){:target="_blank"}  from **@davidlange6**: remove pyminuit and its dependencies created: 2021-06-30 15:25:16 merged: 2021-07-01 11:25:36

22. [7078](http://github.com/cms-sw/cmsdist/pull/7078){:target="_blank"}  from **@cms-sw**: build sherpa using python3 created: 2021-06-30 12:01:14 merged: 2021-06-30 19:00:19

23. [7077](http://github.com/cms-sw/cmsdist/pull/7077){:target="_blank"}  from **@cms-sw**: [SCRAM] Extra checks of tags and attributes, deploy docs created: 2021-06-30 07:36:16 merged: 2021-06-30 19:06:32

24. [7075](http://github.com/cms-sw/cmsdist/pull/7075){:target="_blank"}  from **@cms-sw**: added rootntuple tool definition created: 2021-06-29 17:41:10 merged: 2021-06-30 05:42:02

25. [7071](http://github.com/cms-sw/cmsdist/pull/7071){:target="_blank"}  from **@belforte**: update crabclient DEV created: 2021-06-28 16:18:33 merged: 2021-06-28 16:57:34

26. [7070](http://github.com/cms-sw/cmsdist/pull/7070){:target="_blank"}  from **@davidlange6**: Moving externals towards python3 created: 2021-06-28 15:41:16 merged: 2021-06-30 05:41:31

27. [7066](http://github.com/cms-sw/cmsdist/pull/7066){:target="_blank"}  from **@cms-sw**: [OpenLoops 2.1.2] Generate process_src.tgz to be uploaded as source created: 2021-06-28 12:48:41 merged: 2021-06-29 16:12:33

28. [7063](http://github.com/cms-sw/cmsdist/pull/7063){:target="_blank"}  from **@cms-sw**: Added detect_odr_violation=0 to asan option created: 2021-06-26 09:09:28 merged: 2021-06-26 09:10:06

29. [7062](http://github.com/cms-sw/cmsdist/pull/7062){:target="_blank"}  from **@cms-sw**: Removal of various python2 based packages, backported fromDEVEL created: 2021-06-25 15:05:54 merged: 2021-06-25 21:09:54

30. [7061](http://github.com/cms-sw/cmsdist/pull/7061){:target="_blank"}  from **@cms-sw**: [SCRAM] Added for and foreach attributes for unit tests created: 2021-06-25 09:57:22 merged: 2021-06-25 20:28:11

31. [7060](http://github.com/cms-sw/cmsdist/pull/7060){:target="_blank"}  from **@cms-sw**: [CC8] Fix trivy sources: expand after changing to directory created: 2021-06-24 22:50:17 merged: 2021-06-25 05:14:18

32. [7057](http://github.com/cms-sw/cmsdist/pull/7057){:target="_blank"}  from **@vkuznet**: Update versions for different tools; replace local builds with binary downloads; add trivy tool created: 2021-06-23 18:33:51 merged: 2021-06-23 21:44:19

33. [7056](http://github.com/cms-sw/cmsdist/pull/7056){:target="_blank"}  from **@cms-sw**: [SCRAM] Update to support generating multiple tests using single command created: 2021-06-23 09:38:13 merged: 2021-06-24 09:43:18

34. [7055](http://github.com/cms-sw/cmsdist/pull/7055){:target="_blank"}  from **@cms-sw**: [BuildRules] Fix the EDM_PLUGIN="0" flag in plugisn/BuildFile created: 2021-06-22 16:07:18 merged: 2021-06-22 21:02:22

35. [7054](http://github.com/cms-sw/cmsdist/pull/7054){:target="_blank"}  from **@davidlange6**: restore pyyaml on python2 as needed by conddb  created: 2021-06-22 06:49:58 merged: 2021-06-22 15:33:57

36. [7053](http://github.com/cms-sw/cmsdist/pull/7053){:target="_blank"}  from **@cms-sw**: Get catch2 2.13.6 created: 2021-06-21 20:38:40 merged: 2021-06-23 13:30:00

37. [7051](http://github.com/cms-sw/cmsdist/pull/7051){:target="_blank"}  from **@cms-sw**: [TBB] Use another repo/branch/tag for PPC created: 2021-06-21 12:42:53 merged: 2021-06-22 21:01:58

38. [7046](http://github.com/cms-sw/cmsdist/pull/7046){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-CSCTriggerPrimitives to V00-09-00 created: 2021-06-21 07:03:34 merged: 2021-06-21 08:43:03

39. [7045](http://github.com/cms-sw/cmsdist/pull/7045){:target="_blank"}  from **@cms-sw**: [BuildRules] Add unit test time in the test logs created: 2021-06-20 09:42:21 merged: 2021-06-20 23:36:48

40. [7043](http://github.com/cms-sw/cmsdist/pull/7043){:target="_blank"}  from **@cms-sw**: [cmssw-osenv] fix handling of multiple commands created: 2021-06-17 20:14:57 merged: 2021-06-17 20:15:07
