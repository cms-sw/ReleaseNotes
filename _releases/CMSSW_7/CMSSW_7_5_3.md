---
layout: post
rel_link:  "7_5_3"
title:  "CMSSW_7_5_3"
date:   2015-09-18 12:58:20
categories: cmssw
relmajor: 7
relminor: 5
relsubminor: 3
---

# CMSSW_7_5_3
#### Changes since CMSSW_7_5_2:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_5_2...CMSSW_7_5_3)



1. [11283](http://github.com/cms-sw/cmssw/pull/11283){:target="_blank"}  from **@bachtis**: Fix in PF reconstruction for the  spike at MET=0.0 - 75X version of #11280 `reconstruction`  created: 2015-09-16 14:44:32 merged: 2015-09-18 12:51:29

2. [11275](http://github.com/cms-sw/cmssw/pull/11275){:target="_blank"}  from **@mbandrews**: Migrate to ecalMultifit. Remove timing qT patch `dqm`  created: 2015-09-16 13:30:25 merged: 2015-09-18 07:41:32

3. [11281](http://github.com/cms-sw/cmssw/pull/11281){:target="_blank"}  from **@fcouderc**: add sigmaietaiphi for photon regression inputs (75X) `reconstruction`  created: 2015-09-16 14:11:08 merged: 2015-09-18 07:36:40

4. [11294](http://github.com/cms-sw/cmssw/pull/11294){:target="_blank"}  from **@cms-tsg-storm**: 75X 25ns HLT - round four `hlt`  created: 2015-09-16 16:28:48 merged: 2015-09-17 15:04:17

5. [11255](http://github.com/cms-sw/cmssw/pull/11255){:target="_blank"}  from **@cerminar**: Fix in PCL for SiPixel alignment (75X) `alca`  created: 2015-09-15 15:54:50 merged: 2015-09-17 09:31:52

6. [11269](http://github.com/cms-sw/cmssw/pull/11269){:target="_blank"}  from **@slava77**: don't pass puppi NaNs to pseudojet methods (port of #11267 to 75X) `analysis`  `reconstruction`  created: 2015-09-16 05:12:53 merged: 2015-09-17 09:26:58

7. [11299](http://github.com/cms-sw/cmssw/pull/11299){:target="_blank"}  from **@wmtan**: Make ROOT5 checksums known in ROOT6 (7_5_X) `reconstruction`  created: 2015-09-16 19:16:48 merged: 2015-09-17 09:26:42

8. [10240](http://github.com/cms-sw/cmssw/pull/10240){:target="_blank"}  from **@cms-met**: Various improvements and small fixes of the MET uncertainty tools `analysis`  `dqm`  created: 2015-07-16 11:16:17 merged: 2015-09-16 20:17:08

9. [11034](http://github.com/cms-sw/cmssw/pull/11034){:target="_blank"}  from **@ebouvier**: Top trigger names for 25 ns 75X `dqm`  created: 2015-08-31 08:19:40 merged: 2015-09-16 20:16:58

10. [11141](http://github.com/cms-sw/cmssw/pull/11141){:target="_blank"}  from **@mandrenguyen**: Update HI vtx smearing according to new beta*.  `operations`  `simulation`  created: 2015-09-04 17:30:41 merged: 2015-09-16 20:15:58

11. [11259](http://github.com/cms-sw/cmssw/pull/11259){:target="_blank"}  from **@deguio**: update GT for online processing `dqm`  created: 2015-09-15 16:53:13 merged: 2015-09-16 20:11:46

12. [11274](http://github.com/cms-sw/cmssw/pull/11274){:target="_blank"}  from **@davidlange6**: Method3 with hcal time slew update, backwards compatible `alca`  `hlt`  `reconstruction`  `simulation`  created: 2015-09-16 12:56:46 merged: 2015-09-16 20:07:56

13. [11261](http://github.com/cms-sw/cmssw/pull/11261){:target="_blank"}  from **@lgray**: Update two variables of electron MVA to match the training definition (75X) `reconstruction`  created: 2015-09-15 17:44:42 merged: 2015-09-16 20:01:41

14. [11263](http://github.com/cms-sw/cmssw/pull/11263){:target="_blank"}  from **@wmtan**: Use anonymous namespace to avoid duplicate symbols `reconstruction`  created: 2015-09-15 19:27:41 merged: 2015-09-16 19:56:40

15. [11094](http://github.com/cms-sw/cmssw/pull/11094){:target="_blank"}  from **@fwyzard**: make EcalRingCalibrationTools thread safe (75x) `alca`  `hlt`  created: 2015-09-02 23:58:23 merged: 2015-09-16 13:06:29

16. [10569](http://github.com/cms-sw/cmssw/pull/10569){:target="_blank"}  from **@mdhildreth**: 750 tracking particles PreMixing fixes `dqm`  `operations`  `pdmv`  `simulation`  created: 2015-08-04 17:52:44 merged: 2015-09-16 12:17:41

17. [11242](http://github.com/cms-sw/cmssw/pull/11242){:target="_blank"}  from **@fwyzard**: edmCheckMultithreading: check for non multithreading-compliant modules `core`  created: 2015-09-14 08:46:28 merged: 2015-09-16 09:16:26

18. [11134](http://github.com/cms-sw/cmssw/pull/11134){:target="_blank"}  from **@davidsheffield**: Add scouting electron, photon, and muon classes and producers `hlt`  created: 2015-09-04 14:56:23 merged: 2015-09-16 09:13:26

19. [11157](http://github.com/cms-sw/cmssw/pull/11157){:target="_blank"}  from **@smorovic**: Fix premature end of run in DAQ (75X) `daq`  `reconstruction`  created: 2015-09-05 21:36:58 merged: 2015-09-15 16:16:46

20. [10968](http://github.com/cms-sw/cmssw/pull/10968){:target="_blank"}  from **@fwyzard**: migrate modules used by the HLT menu to multithreading (L1) (75x) `l1`  created: 2015-08-27 06:15:41 merged: 2015-09-15 16:07:36

21. [11042](http://github.com/cms-sw/cmssw/pull/11042){:target="_blank"}  from **@cms-tsg-storm**: 75X 25ns HLT round three `hlt`  created: 2015-08-31 13:32:20 merged: 2015-09-15 16:07:30

22. [11116](http://github.com/cms-sw/cmssw/pull/11116){:target="_blank"}  from **@smorovic**: Streamer output modules ported to one::OutputModule (75X) `core`  `daq`  `dqm`  `reconstruction`  created: 2015-09-03 21:06:39 merged: 2015-09-15 16:07:06

23. [11207](http://github.com/cms-sw/cmssw/pull/11207){:target="_blank"}  from **@bendavid**: add protection for rare infinite loop in ecal multifit (75X) `reconstruction`  created: 2015-09-09 16:08:56 merged: 2015-09-15 16:06:49

24. [11217](http://github.com/cms-sw/cmssw/pull/11217){:target="_blank"}  from **@alja**: 75x Fireworks: Adjust camera position when open 3D region `visualization`  created: 2015-09-09 20:45:30 merged: 2015-09-11 07:36:10

25. [10265](http://github.com/cms-sw/cmssw/pull/10265){:target="_blank"}  from **@slehti**: Hlt tau validation update75x `dqm`  created: 2015-07-17 14:30:19 merged: 2015-09-11 07:01:26

26. [10967](http://github.com/cms-sw/cmssw/pull/10967){:target="_blank"}  from **@fwyzard**: migrate modules used by the HLT menu to multithreading (HLT) (75x) `hlt`  created: 2015-08-27 06:15:36 merged: 2015-09-11 07:01:20

27. [11160](http://github.com/cms-sw/cmssw/pull/11160){:target="_blank"}  from **@matteosan1**: Electron object modifier 75X  `analysis`  `reconstruction`  created: 2015-09-06 07:11:19 merged: 2015-09-11 06:55:07

28. [11175](http://github.com/cms-sw/cmssw/pull/11175){:target="_blank"}  from **@slava77**: cleanup of uninitialized reads reported by valgrind (backport of #11173 ) `analysis`  `dqm`  `reconstruction`  created: 2015-09-07 19:34:38 merged: 2015-09-11 06:54:52

29. [11064](http://github.com/cms-sw/cmssw/pull/11064){:target="_blank"}  from **@ndaci**: Added a new path in DiPhoton category. (Backport from #11063) `dqm`  created: 2015-09-01 15:45:19 merged: 2015-09-10 09:01:32

30. [11002](http://github.com/cms-sw/cmssw/pull/11002){:target="_blank"}  from **@ahinzmann**: Backport of new pileup jet ID for MiniAOD re-processing `analysis`  `dqm`  `reconstruction`  created: 2015-08-28 13:15:55 merged: 2015-09-09 14:07:15

31. [11074](http://github.com/cms-sw/cmssw/pull/11074){:target="_blank"}  from **@ahinzmann**: Add energy correlation functions to jet tools 75 `reconstruction`  created: 2015-09-02 07:45:34 merged: 2015-09-09 14:06:46

32. [10970](http://github.com/cms-sw/cmssw/pull/10970){:target="_blank"}  from **@fwyzard**: migrate modules used by the HLT menu to multithreading (various) (75x) `analysis`  `db`  `dqm`  `hlt`  `l1`  created: 2015-08-27 06:16:30 merged: 2015-09-09 13:44:12

33. [11124](http://github.com/cms-sw/cmssw/pull/11124){:target="_blank"}  from **@vasile-ghete**: Cmssw 7 5 x l1 gt utils `l1`  created: 2015-09-04 10:50:54 merged: 2015-09-09 13:43:38

34. [11165](http://github.com/cms-sw/cmssw/pull/11165){:target="_blank"}  from **@Sam-Harper**: DiEle25 dqm update 75X `dqm`  created: 2015-09-06 16:44:13 merged: 2015-09-09 13:43:03

35. [11076](http://github.com/cms-sw/cmssw/pull/11076){:target="_blank"}  from **@ahinzmann**: Followup on flavor definition in MiniAOD `analysis`  created: 2015-09-02 09:12:47 merged: 2015-09-09 13:41:34

36. [11169](http://github.com/cms-sw/cmssw/pull/11169){:target="_blank"}  from **@dmitrijus**: Fix a 'kNoTypesStored' bug in DQMRootSource `dqm`  created: 2015-09-07 08:57:37 merged: 2015-09-09 13:40:43

37. [11184](http://github.com/cms-sw/cmssw/pull/11184){:target="_blank"}  from **@davidlange6**: Hcal backwards compatible version of hcal scale and digitizer changes `simulation`  created: 2015-09-08 13:09:54 merged: 2015-09-09 13:31:24

38. [11049](http://github.com/cms-sw/cmssw/pull/11049){:target="_blank"}  from **@fwyzard**: DQMStore::removeElement: do not remove non-existing MEs (75x) `dqm`  created: 2015-08-31 20:51:45 merged: 2015-09-06 06:21:33

39. [11054](http://github.com/cms-sw/cmssw/pull/11054){:target="_blank"}  from **@fwyzard**: migrate L1 and HLT summary modules to one::EDAnalyzer (75x) `hlt`  `l1`  created: 2015-08-31 20:58:34 merged: 2015-09-06 06:21:17

40. [11105](http://github.com/cms-sw/cmssw/pull/11105){:target="_blank"}  from **@istaslis**: Added dummy parameters to HIMultiTrackSelector `reconstruction`  created: 2015-09-03 11:38:17 merged: 2015-09-06 06:20:33

41. [10925](http://github.com/cms-sw/cmssw/pull/10925){:target="_blank"}  from **@cms-tau-pog**: Dynamic strip reco 75 x `analysis`  `reconstruction`  created: 2015-08-24 17:29:30 merged: 2015-09-04 07:26:55

42. [10935](http://github.com/cms-sw/cmssw/pull/10935){:target="_blank"}  from **@fwyzard**:   migrate RPCPointProducer to a global::EDProducer (75x) `dqm`  `hlt`  `reconstruction`  created: 2015-08-25 01:09:39 merged: 2015-09-04 07:26:49

43. [11013](http://github.com/cms-sw/cmssw/pull/11013){:target="_blank"}  from **@sachikot**: adding more scal monitoring for online DQM in 75X `dqm`  created: 2015-08-28 14:54:08 merged: 2015-09-04 07:26:42

44. [10451](http://github.com/cms-sw/cmssw/pull/10451){:target="_blank"}  from **@cerminar**: First integration of Pixel Alignment of large structures in PCL (75X) `alca`  `db`  `operations`  `pdmv`  created: 2015-07-29 11:46:46 merged: 2015-09-04 07:22:56

45. [11069](http://github.com/cms-sw/cmssw/pull/11069){:target="_blank"}  from **@wmtan**: Use anonymous namespace to avoid duplicate symbols `reconstruction`  created: 2015-09-02 04:17:27 merged: 2015-09-04 07:21:22

46. [11032](http://github.com/cms-sw/cmssw/pull/11032){:target="_blank"}  from **@davidsheffield**: Add index to primary vertex in scouting particle collection `hlt`  created: 2015-08-31 05:35:35 merged: 2015-09-04 07:21:09

47. [11092](http://github.com/cms-sw/cmssw/pull/11092){:target="_blank"}  from **@Dr15Jones**: Appy event filter before data prefetching for OutputModules `core`  created: 2015-09-02 22:02:39 merged: 2015-09-04 07:19:56

48. [10751](http://github.com/cms-sw/cmssw/pull/10751){:target="_blank"}  from **@ahinzmann**: Switch parton flavour in MiniAOD from algorithmic to physics definition 75 `analysis`  created: 2015-08-13 16:40:35 merged: 2015-09-02 06:31:23

49. [10966](http://github.com/cms-sw/cmssw/pull/10966){:target="_blank"}  from **@fwyzard**: migrate modules used by the HLT menu to multithreading (Reco) (75x) `reconstruction`  created: 2015-08-27 06:14:11 merged: 2015-09-02 06:26:42

50. [10969](http://github.com/cms-sw/cmssw/pull/10969){:target="_blank"}  from **@fwyzard**: migrate modules used by the HLT menu to multithreading (AlCa) (75x) `alca`  created: 2015-08-27 06:15:45 merged: 2015-09-02 06:26:36

51. [10916](http://github.com/cms-sw/cmssw/pull/10916){:target="_blank"}  from **@gpetruc**: Add L1 prescales to the miniAOD (75X port of #10895) `analysis`  created: 2015-08-24 09:47:30 merged: 2015-09-02 06:26:27

52. [10549](http://github.com/cms-sw/cmssw/pull/10549){:target="_blank"}  from **@heppye**: add DQM Validation plots for MSSM Hbb Trigger Paths.  `dqm`  created: 2015-08-04 08:09:36 merged: 2015-09-01 16:13:28

53. [10584](http://github.com/cms-sw/cmssw/pull/10584){:target="_blank"}  from **@rovere**: Factorise PreSplitting configuration from InitialStep `reconstruction`  created: 2015-08-05 11:39:09 merged: 2015-09-01 16:13:20

54. [10659](http://github.com/cms-sw/cmssw/pull/10659){:target="_blank"}  from **@echapon**: New track algorithm names for HI muon RegIt `reconstruction`  created: 2015-08-10 19:36:08 merged: 2015-09-01 16:13:14

55. [10812](http://github.com/cms-sw/cmssw/pull/10812){:target="_blank"}  from **@KiSooLee**: BPTX path for HI added `dqm`  created: 2015-08-17 08:34:11 merged: 2015-09-01 16:12:54

56. [10835](http://github.com/cms-sw/cmssw/pull/10835){:target="_blank"}  from **@cms-tsg-storm**: Round Two 25ns HLT updates (75X) `hlt`  created: 2015-08-18 08:05:54 merged: 2015-09-01 16:12:46

57. [10878](http://github.com/cms-sw/cmssw/pull/10878){:target="_blank"}  from **@MarkBaber**: CMSSW_7_5_X DQM updates for AlphaT HLT paths (v2) `dqm`  created: 2015-08-20 11:06:21 merged: 2015-09-01 16:12:32

58. [10912](http://github.com/cms-sw/cmssw/pull/10912){:target="_blank"}  from **@makortel**: Transform RecoTrackRefSelector to stream (75X) `reconstruction`  created: 2015-08-24 08:04:55 merged: 2015-09-01 16:12:20

59. [10978](http://github.com/cms-sw/cmssw/pull/10978){:target="_blank"}  from **@ggovi**: Fix for PoolDBESSource_cfi - properly moved to V2 `alca`  `db`  created: 2015-08-27 10:29:00 merged: 2015-09-01 16:12:02

60. [11052](http://github.com/cms-sw/cmssw/pull/11052){:target="_blank"}  from **@fwyzard**: ThroughputServiceClient: add more throughput plots (75x) `hlt`  created: 2015-08-31 20:55:05 merged: 2015-09-01 16:11:46

61. [10983](http://github.com/cms-sw/cmssw/pull/10983){:target="_blank"}  from **@duanders**: Update hotline skim sequences and cuts (75X) `alca`  created: 2015-08-27 13:18:30 merged: 2015-09-01 16:06:57

62. [11039](http://github.com/cms-sw/cmssw/pull/11039){:target="_blank"}  from **@danduggan**: Patching to better handle LS based histos during LS transitions in 75x `dqm`  created: 2015-08-31 11:33:43 merged: 2015-09-01 05:21:21

63. [10903](http://github.com/cms-sw/cmssw/pull/10903){:target="_blank"}  from **@mbandrews**: forcing EE qT to be always true `dqm`  created: 2015-08-21 14:31:32 merged: 2015-08-31 10:16:48

64. [10942](http://github.com/cms-sw/cmssw/pull/10942){:target="_blank"}  from **@dmitrijus**: Fix DQM/PhysicsHWW by just ignoring jets with invalid parameters (75x) `dqm`  created: 2015-08-25 17:20:43 merged: 2015-08-31 09:41:42

65. [10931](http://github.com/cms-sw/cmssw/pull/10931){:target="_blank"}  from **@wmtan**: Make ROOT5 checksum known to ROOT6 `analysis`  created: 2015-08-24 20:14:53 merged: 2015-08-31 09:38:36

66. [10961](http://github.com/cms-sw/cmssw/pull/10961){:target="_blank"}  from **@duanders**: Workaround for gluino decay bug (75X) `generators`  created: 2015-08-26 22:30:29 merged: 2015-08-31 09:37:38

67. [10608](http://github.com/cms-sw/cmssw/pull/10608){:target="_blank"}  from **@schoef**:  MET Filter update (port of #10604) `alca`  `analysis`  `reconstruction`  created: 2015-08-06 20:20:24 merged: 2015-08-31 09:37:06

68. [10690](http://github.com/cms-sw/cmssw/pull/10690){:target="_blank"}  from **@lgray**: Modifier to apply energy corrections to photons and electrons (miniAOD) for 75X `alca`  `analysis`  `reconstruction`  created: 2015-08-11 15:23:44 merged: 2015-08-31 09:33:11

69. [10735](http://github.com/cms-sw/cmssw/pull/10735){:target="_blank"}  from **@ndaci**: Update paths. `dqm`  created: 2015-08-12 22:40:47 merged: 2015-08-31 09:33:02

70. [10756](http://github.com/cms-sw/cmssw/pull/10756){:target="_blank"}  from **@cms-btv-pog**: GBRForest in TMVAEvaluator + SoftLepton taggers using GBRForest: 75X `analysis`  `reconstruction`  created: 2015-08-13 21:01:12 merged: 2015-08-31 09:32:55

71. [10884](http://github.com/cms-sw/cmssw/pull/10884){:target="_blank"}  from **@archiron**: Electron Validation : modification of scl_EoEtrueVsrecOfflineVertices histo (75x) `dqm`  created: 2015-08-20 14:12:40 merged: 2015-08-31 09:32:33

72. [10913](http://github.com/cms-sw/cmssw/pull/10913){:target="_blank"}  from **@Martin-Grunewald**: Fix DQM py files for ConfDB parsing (75X) `dqm`  created: 2015-08-24 08:42:48 merged: 2015-08-31 09:32:28

73. [10929](http://github.com/cms-sw/cmssw/pull/10929){:target="_blank"}  from **@cmkuo**: fix a bug for the number of good ES rechits `dqm`  created: 2015-08-24 19:42:36 merged: 2015-08-31 09:32:22

74. [10948](http://github.com/cms-sw/cmssw/pull/10948){:target="_blank"}  from **@ssanders50**: boundary check `reconstruction`  created: 2015-08-26 09:29:47 merged: 2015-08-31 09:32:16

75. [10982](http://github.com/cms-sw/cmssw/pull/10982){:target="_blank"}  from **@lveldere**: FastSim bugfix 75X: remove import of non-existing cfg from START geometry `fastsim`  created: 2015-08-27 12:20:03 merged: 2015-08-31 09:32:01

76. [11010](http://github.com/cms-sw/cmssw/pull/11010){:target="_blank"}  from **@Dr15Jones**: Fix bug preventing the use of a local cache `core`  created: 2015-08-28 14:38:21 merged: 2015-08-31 09:31:50

77. [10786](http://github.com/cms-sw/cmssw/pull/10786){:target="_blank"}  from **@ahinzmann**: Adjust ak8 jet threshold in MiniAOD `analysis`  created: 2015-08-14 16:55:15 merged: 2015-08-31 09:28:58

78. [10953](http://github.com/cms-sw/cmssw/pull/10953){:target="_blank"}  from **@echapon**: New steps for HI muon RegIt `reconstruction`  created: 2015-08-26 15:13:26 merged: 2015-08-27 09:16:44

79. [10896](http://github.com/cms-sw/cmssw/pull/10896){:target="_blank"}  from **@gpetruc**: FWLite MultiChainEvent: avoid crash on empty files (75X) `core`  created: 2015-08-21 10:30:14 merged: 2015-08-24 06:09:41

#### CMSDIST Changes between Tags REL/CMSSW_7_5_2/slc6_amd64_gcc491 and REL/CMSSW_7_5_3/slc6_amd64_gcc491:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_5_2/slc6_amd64_gcc491...REL/CMSSW_7_5_3/slc6_amd64_gcc491)



1. [1796](http://github.com/cms-sw/cmsdist/pull/1796){:target="_blank"}  from **@degano**: Add python modules: PyYAML, docopt, prettytable, schema. created: 2015-09-04 10:03:00 merged: 2015-09-04 10:03:04

2. [1782](http://github.com/cms-sw/cmsdist/pull/1782){:target="_blank"}  from **@degano**: Update to latest CondFormats/JetMETObjects created: 2015-08-31 09:38:36 merged: 2015-08-31 09:38:38
