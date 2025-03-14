---
layout: post
rel_link:  "15_1_0_pre1"
title:  "CMSSW_15_1_0_pre1"
date:   2025-03-13 08:50:49
categories: cmssw
relmajor: 15
relminor: 1
relsubminor: 0
relpre: _pre1
---

# CMSSW_15_1_0_pre1
#### Changes since CMSSW_15_0_1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_15_0_1...CMSSW_15_1_0_pre1)



1. [47569](http://github.com/cms-sw/cmssw/pull/47569){:target="_blank"}  from **@mmusich**: remove `hltOnlineBeamSpotESProducer_cfi` from NGT scouting menu `hlt` created: 2025-03-12 08:18:57 merged: 2025-03-12 15:32:41

2. [47562](http://github.com/cms-sw/cmssw/pull/47562){:target="_blank"}  from **@Dr15Jones**: Removed unneeded code in StreamerInputSource `core` created: 2025-03-11 15:44:02 merged: 2025-03-12 06:02:41

3. [47558](http://github.com/cms-sw/cmssw/pull/47558){:target="_blank"}  from **@jlidrych**: add fillDescriptions to several Strip modules used at HLT `alca` `reconstruction` `trk` created: 2025-03-11 13:35:18 merged: 2025-03-12 15:32:16

4. [47553](http://github.com/cms-sw/cmssw/pull/47553){:target="_blank"}  from **@bsunanda**: Run3-187O Create an XML file for gem11 without chambers 6, 7, 8 on -z side for 2025 `geometry` created: 2025-03-11 05:23:05 merged: 2025-03-12 06:07:10

5. [47551](http://github.com/cms-sw/cmssw/pull/47551){:target="_blank"}  from **@bsunanda**: Run3-gex187N Update all Run3 scenarios to accommodate the changes for RPC correction for phi staggering and z-position `geometry` `upgrade` created: 2025-03-11 02:57:41 merged: 2025-03-12 06:08:12

6. [47549](http://github.com/cms-sw/cmssw/pull/47549){:target="_blank"}  from **@civanch**: [FULLSIM] Extended SIM exception  `simulation` created: 2025-03-10 18:03:13 merged: 2025-03-12 15:20:25

7. [47546](http://github.com/cms-sw/cmssw/pull/47546){:target="_blank"}  from **@makortel**: Remove FinalPath from the framework `core` `hlt` created: 2025-03-10 15:10:32 merged: 2025-03-12 15:19:36

8. [47544](http://github.com/cms-sw/cmssw/pull/47544){:target="_blank"}  from **@24LopezR**: Fix typo in g4SimHits cfg `simulation` created: 2025-03-10 11:00:29 merged: 2025-03-12 06:07:41

9. [47543](http://github.com/cms-sw/cmssw/pull/47543){:target="_blank"}  from **@smuzaffar**: Added algorithm header needed for std::transform `reconstruction` `upgrade` created: 2025-03-10 07:23:34 merged: 2025-03-12 15:31:13

10. [47542](http://github.com/cms-sw/cmssw/pull/47542){:target="_blank"}  from **@mmusich**: Add HLT tracking monitoring in cosmics  `alca` `dqm` `operations` `pdmv` `upgrade` created: 2025-03-09 17:00:03 merged: 2025-03-12 15:17:12

11. [47539](http://github.com/cms-sw/cmssw/pull/47539){:target="_blank"}  from **@francescobrivio**: Update OnlineBeamMonitor for DIP publication `dqm` `db` `tracking` created: 2025-03-09 14:44:46 merged: 2025-03-12 06:06:46

12. [47537](http://github.com/cms-sw/cmssw/pull/47537){:target="_blank"}  from **@smuzaffar**: [UBSAN] added deps on TrackerRecHit2D for BaseTrackerRecHit `simulation` created: 2025-03-09 09:14:14 merged: 2025-03-12 15:30:41

13. [47536](http://github.com/cms-sw/cmssw/pull/47536){:target="_blank"}  from **@srimanob**: 2025 Scenario `operations` created: 2025-03-08 23:27:57 merged: 2025-03-12 15:16:22

14. [47534](http://github.com/cms-sw/cmssw/pull/47534){:target="_blank"}  from **@bsunanda**: Phase2-hgx362B Add the modified title files for HGCal using the flat file parameters of modmapv16.6_cmssw_flatfile.txt `geometry` `upgrade` created: 2025-03-08 08:56:17 merged: 2025-03-09 18:23:19

15. [47533](http://github.com/cms-sw/cmssw/pull/47533){:target="_blank"}  from **@Dr15Jones**: Compartmentalize how ProductRegistry is filled `core` `dqm` `simulation` `trk` created: 2025-03-07 19:34:59 merged: 2025-03-12 15:35:40

16. [47531](http://github.com/cms-sw/cmssw/pull/47531){:target="_blank"}  from **@bsunanda**: Run3-gex187M Update the documentation of different Run4 scenarios `geometry` `upgrade` created: 2025-03-07 15:14:16 merged: 2025-03-09 18:28:23

17. [47529](http://github.com/cms-sw/cmssw/pull/47529){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `15_0_X` (2/N)  [`15_1_X`]  `hlt` created: 2025-03-07 12:54:26 merged: 2025-03-07 19:59:35

18. [47528](http://github.com/cms-sw/cmssw/pull/47528){:target="_blank"}  from **@kdeleo**: MtdValidation: add plots on track multiplicity  `dqm` created: 2025-03-07 11:26:48 merged: 2025-03-12 06:03:32

19. [47526](http://github.com/cms-sw/cmssw/pull/47526){:target="_blank"}  from **@bsunanda**: Phase2-hgx362A Provide the possibility of running without a Sensitive Detector by setting OnlySD = ['NONE'] `geometry` `simulation` `upgrade` created: 2025-03-07 07:31:17 merged: 2025-03-09 18:27:44

20. [47522](http://github.com/cms-sw/cmssw/pull/47522){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] add validation (w.r.t. SIM) step for Phase-2 HLT timing and NGT workflows `pdmv` `upgrade` created: 2025-03-06 10:57:52 merged: 2025-03-12 06:01:56

21. [47521](http://github.com/cms-sw/cmssw/pull/47521){:target="_blank"}  from **@bsunanda**: Ryn3-gex187L Cure the overlaps in 2021, 2023, 2024 by adopting Sergio's version for 2023/v2/mfshield.xml `geometry` created: 2025-03-06 06:14:44 merged: 2025-03-07 09:55:15

22. [47520](http://github.com/cms-sw/cmssw/pull/47520){:target="_blank"}  from **@fwyzard**: Remove unnecessary headers from HGCalRecProducers `reconstruction` `upgrade` created: 2025-03-06 06:05:42 merged: 2025-03-07 07:32:59

23. [47519](http://github.com/cms-sw/cmssw/pull/47519){:target="_blank"}  from **@bsunanda**: Phase2-hgx362 First attempt to make V19 version of HGCal Geometry `geometry` `visualization` `upgrade` created: 2025-03-06 04:46:21 merged: 2025-03-07 09:52:59

24. [47518](http://github.com/cms-sw/cmssw/pull/47518){:target="_blank"}  from **@woohyeonHeo**: Remove L1Trigger dependency from DataFormats package "ME0Stub" `l1` `simulation` `upgrade` created: 2025-03-06 04:16:22 merged: 2025-03-07 19:57:44

25. [47514](http://github.com/cms-sw/cmssw/pull/47514){:target="_blank"}  from **@alexandertuna**: Add LST_STANDALONE option for printf vs edm::LogWarning `reconstruction` `tracking` created: 2025-03-05 17:59:34 merged: 2025-03-07 09:52:20

26. [47513](http://github.com/cms-sw/cmssw/pull/47513){:target="_blank"}  from **@SWuchterl**: add fillDescriptions to several BTV plugins used at HLT `reconstruction` created: 2025-03-05 17:06:12 merged: 2025-03-07 09:52:08

27. [47512](http://github.com/cms-sw/cmssw/pull/47512){:target="_blank"}  from **@bsunanda**: Run3-gex187K Add overlap check test for the files produced by Sergio in PR #47511 `geometry` created: 2025-03-05 13:18:25 merged: 2025-03-06 08:29:33

28. [47511](http://github.com/cms-sw/cmssw/pull/47511){:target="_blank"}  from **@slomeo**: Overlaps fixed for Muon System - 2025 Scenario with 2025/v3/rpcf.xml `geometry` created: 2025-03-05 12:16:43 merged: 2025-03-06 08:29:18

29. [47508](http://github.com/cms-sw/cmssw/pull/47508){:target="_blank"}  from **@mmusich**: remove L1T legacy dependencies from pixel and strip online DQM clients `dqm` created: 2025-03-05 11:38:28 merged: 2025-03-07 20:00:09

30. [47501](http://github.com/cms-sw/cmssw/pull/47501){:target="_blank"}  from **@vlimant**: McM/production bound options to cmsDriver `operations` created: 2025-03-04 10:52:23 merged: 2025-03-06 08:38:24

31. [47496](http://github.com/cms-sw/cmssw/pull/47496){:target="_blank"}  from **@BlancoFS**: Enable corrections for HCAL effective areas `hlt` created: 2025-03-04 08:41:47 merged: 2025-03-05 06:35:26

32. [47495](http://github.com/cms-sw/cmssw/pull/47495){:target="_blank"}  from **@bsunanda**: Run3-gex187J Sergio's correction for overlap removals for the 2025 version of rpcf v2 `geometry` created: 2025-03-04 08:17:51 merged: 2025-03-05 06:36:04

33. [47493](http://github.com/cms-sw/cmssw/pull/47493){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `15_0_X` (1/N) [`15_1_X`] `hlt` created: 2025-03-04 07:56:15 merged: 2025-03-04 13:48:33

34. [47486](http://github.com/cms-sw/cmssw/pull/47486){:target="_blank"}  from **@Dr15Jones**: Removed Principal::adjustToNewProductRegistry `core` created: 2025-03-03 16:02:12 merged: 2025-03-06 08:29:13

35. [47483](http://github.com/cms-sw/cmssw/pull/47483){:target="_blank"}  from **@AdrianoDee**: Reading `TriggerResults` from an `InputTag` for B2G HLT Analyzers `dqm` created: 2025-03-03 10:21:49 merged: 2025-03-05 06:34:58

36. [47481](http://github.com/cms-sw/cmssw/pull/47481){:target="_blank"}  from **@Dr15Jones**: Added csv output option to edmModuleEventAllocMonitorAnalyze.py `core` created: 2025-02-28 20:35:14 merged: 2025-03-02 12:14:28

37. [47479](http://github.com/cms-sw/cmssw/pull/47479){:target="_blank"}  from **@bsunanda**: Run3-gex187I Add a new XML file from Jongwon for RPC to add the new chamber in RE4/1 `geometry` created: 2025-02-28 08:48:57 merged: 2025-03-02 12:14:18

38. [47478](http://github.com/cms-sw/cmssw/pull/47478){:target="_blank"}  from **@ywkao**: Implement TH2Poly in DQM Services and add GetArray support `core` `dqm` created: 2025-02-28 05:26:01 merged: 2025-03-10 07:19:03

39. [47477](http://github.com/cms-sw/cmssw/pull/47477){:target="_blank"}  from **@makortel**: Add optional HardwareResourcesInformation printout to edmProvDump `core` created: 2025-02-27 20:50:55 merged: 2025-02-28 09:11:45

40. [47476](http://github.com/cms-sw/cmssw/pull/47476){:target="_blank"}  from **@trackreco**: mkFit: technical fix, remove unused function from standalone build `reconstruction` `tracking` created: 2025-02-27 18:42:44 merged: 2025-03-02 10:17:04

41. [47473](http://github.com/cms-sw/cmssw/pull/47473){:target="_blank"}  from **@makortel**: Revert "Add HardwareResourcesInformation printout to edmProvDump" `core` created: 2025-02-27 14:21:46 merged: 2025-02-27 17:50:43

42. [47471](http://github.com/cms-sw/cmssw/pull/47471){:target="_blank"}  from **@mmusich**: miscellaneous improvements to `HLTriggerOffline/Scouting` plugins `dqm` created: 2025-02-27 13:16:46 merged: 2025-03-02 12:13:54

43. [47466](http://github.com/cms-sw/cmssw/pull/47466){:target="_blank"}  from **@makortel**: Move `CPUServiceBase`, `RootHandlers`, and `TimingServiceBase` to `FWCore/AbstractServices` `core` created: 2025-02-26 17:24:40 merged: 2025-03-06 08:30:22

44. [47465](http://github.com/cms-sw/cmssw/pull/47465){:target="_blank"}  from **@bsunanda**: Phase2-gex187H Enlarge verification of overlaps for phase2 scenarios due to change of RPC geometry `geometry` created: 2025-02-26 17:08:03 merged: 2025-02-27 12:51:56

45. [47464](http://github.com/cms-sw/cmssw/pull/47464){:target="_blank"}  from **@civanch**: [FULLSIM] Updated configuration of  G4HepEm physics  `simulation` created: 2025-02-26 16:33:03 merged: 2025-02-27 12:52:12

46. [47462](http://github.com/cms-sw/cmssw/pull/47462){:target="_blank"}  from **@makortel**: XrdAdaptor: improve exception messages `core` created: 2025-02-26 15:10:16 merged: 2025-03-02 12:13:38

47. [47461](http://github.com/cms-sw/cmssw/pull/47461){:target="_blank"}  from **@SegmentLinking**: Minor fixes to LST standalone code `reconstruction` `heterogeneous` `tracking` created: 2025-02-26 14:54:08 merged: 2025-03-04 09:02:36

48. [47460](http://github.com/cms-sw/cmssw/pull/47460){:target="_blank"}  from **@p2l1-gtEmulator**: Quality score sum cut + L1GTAcceptFilter + internal fixes `l1` `upgrade` created: 2025-02-26 12:49:01 merged: 2025-03-04 09:45:41

49. [47457](http://github.com/cms-sw/cmssw/pull/47457){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_2_X` (2/N)  [`15_1_X`]  `alca` `hlt` created: 2025-02-26 11:25:48 merged: 2025-02-27 16:14:51

50. [47456](http://github.com/cms-sw/cmssw/pull/47456){:target="_blank"}  from **@smuzaffar**: fix logical error when level>dim-1 `analysis` created: 2025-02-26 10:11:52 merged: 2025-02-26 18:40:35

51. [47455](http://github.com/cms-sw/cmssw/pull/47455){:target="_blank"}  from **@smuzaffar**: fix gcc 14 warnings: use atomic_ref instead of casting `heterogeneous` created: 2025-02-26 09:39:00 merged: 2025-02-26 12:15:41

52. [47454](http://github.com/cms-sw/cmssw/pull/47454){:target="_blank"}  from **@kerstinlovisa**: Function to set tracker bounds in KalmanVertexFitter `reconstruction` `tracking` created: 2025-02-26 08:47:56 merged: 2025-03-12 06:06:24

53. [47453](http://github.com/cms-sw/cmssw/pull/47453){:target="_blank"}  from **@bsunanda**: Run3-gex187H Modify some of the overlap scripts to test overlaps in the new muon scenarios `geometry` created: 2025-02-26 04:51:51 merged: 2025-02-26 18:40:45

54. [47451](http://github.com/cms-sw/cmssw/pull/47451){:target="_blank"}  from **@CMS-HGCAL**: Monitor quality of unpacked FED data with a dedicated SoA `reconstruction` `simulation` `upgrade` `heterogeneous` created: 2025-02-25 15:05:02 merged: 2025-03-09 18:25:54

55. [47444](http://github.com/cms-sw/cmssw/pull/47444){:target="_blank"}  from **@fwyzard**: Implement `edm::ProductNamePattern` `core` created: 2025-02-25 12:46:07 merged: 2025-02-26 14:53:33

56. [47442](http://github.com/cms-sw/cmssw/pull/47442){:target="_blank"}  from **@fwyzard**: Modernise the interface of `ObjectWithDict` `core` created: 2025-02-25 11:27:55 merged: 2025-02-26 09:52:34

57. [47441](http://github.com/cms-sw/cmssw/pull/47441){:target="_blank"}  from **@JanGerritSchulz**: [NGT] Adding `SimDoublets` class for Pixel Tracking Validation including corresponding EDProducers and EDAnalyzers `dqm` `generators` `reconstruction` `simulation` `pdmv` `upgrade` `tracking` `trk` created: 2025-02-25 11:22:07 merged: 2025-03-07 19:57:29

58. [47440](http://github.com/cms-sw/cmssw/pull/47440){:target="_blank"}  from **@iarspider**: DuplicateTrackMerger: fix relvals 29634.703,29834.703 failing in DBG_X IBs `reconstruction` `tracking` created: 2025-02-25 11:18:56 merged: 2025-02-27 17:50:13

59. [47439](http://github.com/cms-sw/cmssw/pull/47439){:target="_blank"}  from **@perrotta**: Update 2023 and 2024 HI MC GTs in autoCond `alca` created: 2025-02-25 11:12:36 merged: 2025-02-27 13:00:52

60. [47437](http://github.com/cms-sw/cmssw/pull/47437){:target="_blank"}  from **@SegmentLinking**: Monitor intermediate LST track collections at HLT `dqm` `operations` `tracking` created: 2025-02-24 23:33:31 merged: 2025-02-25 20:53:30

61. [47436](http://github.com/cms-sw/cmssw/pull/47436){:target="_blank"}  from **@fwyzard**: Remove false positve in `scram b check-headers` `core` created: 2025-02-24 20:26:28 merged: 2025-02-25 16:32:10

62. [47435](http://github.com/cms-sw/cmssw/pull/47435){:target="_blank"}  from **@smuzaffar**: Included cstdint for uint64_t; fixes gcc14 header check `simulation` `upgrade` created: 2025-02-24 17:02:05 merged: 2025-02-25 13:45:10

63. [47434](http://github.com/cms-sw/cmssw/pull/47434){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Add a novel `NGTScouting` Phase-2 HLT menu that runs a single "scouting"-like path on the whole L1Accept `hlt` `pdmv` `upgrade` created: 2025-02-24 16:51:08 merged: 2025-03-06 08:29:58

64. [47432](http://github.com/cms-sw/cmssw/pull/47432){:target="_blank"}  from **@makortel**: XrdAdaptor: Do not add empty exclude strings `core` created: 2025-02-24 15:42:16 merged: 2025-02-25 20:52:40

65. [47431](http://github.com/cms-sw/cmssw/pull/47431){:target="_blank"}  from **@iarspider**: TrackFindingTracklet: remove #pragma message `l1` created: 2025-02-24 11:07:29 merged: 2025-03-02 12:11:43

66. [47430](http://github.com/cms-sw/cmssw/pull/47430){:target="_blank"}  from **@mmusich**: `DQMStreamerReader`: re-throw all exceptions when run in unit test mode `dqm` created: 2025-02-24 09:38:26 merged: 2025-02-25 10:32:24

67. [47429](http://github.com/cms-sw/cmssw/pull/47429){:target="_blank"}  from **@mmusich**: Improvements to `HLTObjectMonitor` `dqm` `hlt` created: 2025-02-24 09:24:55 merged: 2025-02-24 17:33:16

68. [47428](http://github.com/cms-sw/cmssw/pull/47428){:target="_blank"}  from **@tomasra**: Port recent changes from Pythia8Hadronizer to Pythia8HepMC3Hadronizer `generators` created: 2025-02-24 04:42:58 merged: 2025-03-12 06:02:55

69. [47426](http://github.com/cms-sw/cmssw/pull/47426){:target="_blank"}  from **@smuzaffar**: Fix needed for boost 1.87.0 `core` `daq` `reconstruction` `upgrade` created: 2025-02-22 15:38:59 merged: 2025-02-24 17:33:53

70. [47425](http://github.com/cms-sw/cmssw/pull/47425){:target="_blank"}  from **@fwyzard**: Implement additional framework integration tests `core` created: 2025-02-21 19:28:06 merged: 2025-02-25 20:50:36

71. [47423](http://github.com/cms-sw/cmssw/pull/47423){:target="_blank"}  from **@aloeliger**: Include CICADA v2.2.0 configuration as modification to 2025 L1T Era `l1` `operations` created: 2025-02-21 17:31:42 merged: 2025-03-12 15:23:42

72. [47419](http://github.com/cms-sw/cmssw/pull/47419){:target="_blank"}  from **@fwyzard**: Fix `HcalUpgradeDataFrame` dummy type `simulation` created: 2025-02-21 00:38:05 merged: 2025-02-21 15:55:03

73. [47418](http://github.com/cms-sw/cmssw/pull/47418){:target="_blank"}  from **@mmusich**: move unit test for `onlinebeammonitor_dqm_sourceclient-live` to use streamer files `dqm` created: 2025-02-20 21:19:53 merged: 2025-02-24 17:35:01

74. [47417](http://github.com/cms-sw/cmssw/pull/47417){:target="_blank"}  from **@ReyerBand**: Fix for EcalRecHits in dead channels with wrong bits set `reconstruction` `ecal` created: 2025-02-20 18:16:56 merged: 2025-02-21 15:59:53

75. [47414](http://github.com/cms-sw/cmssw/pull/47414){:target="_blank"}  from **@iarspider**: Remove unused variable `reconstruction` created: 2025-02-20 13:16:04 merged: 2025-02-21 16:03:28

76. [47411](http://github.com/cms-sw/cmssw/pull/47411){:target="_blank"}  from **@smuzaffar**: [GCC14]Fix type conversion not using user defined operator warning `core` `db` created: 2025-02-20 11:57:21 merged: 2025-02-25 16:33:55

77. [47410](http://github.com/cms-sw/cmssw/pull/47410){:target="_blank"}  from **@smorovic**: [DAQ] improvements for DTH readout, new file discovery mode `daq` created: 2025-02-20 10:28:22 merged: 2025-02-25 13:44:31

78. [47409](http://github.com/cms-sw/cmssw/pull/47409){:target="_blank"}  from **@perrotta**: Restore run2_data_HEfail in autoCond `alca` created: 2025-02-20 09:46:19 merged: 2025-02-20 16:20:31

79. [47408](http://github.com/cms-sw/cmssw/pull/47408){:target="_blank"}  from **@iarspider**: Fix TestRunnerDataFormatsFWLite unit test `core` created: 2025-02-20 07:57:37 merged: 2025-02-20 16:17:21

80. [47407](http://github.com/cms-sw/cmssw/pull/47407){:target="_blank"}  from **@stahlleiton**: Change fastjet RangeDefinition to Selector to fix warnings `reconstruction` created: 2025-02-20 00:44:44 merged: 2025-02-20 16:19:09

81. [47405](http://github.com/cms-sw/cmssw/pull/47405){:target="_blank"}  from **@SegmentLinking**: Follow up on using cms::alpakatools deltaPhi functions `reconstruction` `heterogeneous` `tracking` created: 2025-02-19 22:46:06 merged: 2025-02-20 16:22:56

82. [47401](http://github.com/cms-sw/cmssw/pull/47401){:target="_blank"}  from @mmusich: introduce `@phase2FakeHLT` and `**@phase2ValidationFakeHLT**` DQM / Validation sequences `dqm` `operations` `simulation` `pdmv` `upgrade` created: 2025-02-19 11:11:38 merged: 2025-02-25 20:52:05

83. [47399](http://github.com/cms-sw/cmssw/pull/47399){:target="_blank"}  from **@rovere**: Fix FEVDEBUGHLT event content to include all Tracksters. `reconstruction` `upgrade` created: 2025-02-19 08:23:22 merged: 2025-02-24 17:34:04

84. [47398](http://github.com/cms-sw/cmssw/pull/47398){:target="_blank"}  from **@mmusich**: protect `Phase2IT{OT}ValidateCluster` against missing input collections `dqm` `trk` created: 2025-02-19 08:06:21 merged: 2025-02-19 13:34:06

85. [47396](http://github.com/cms-sw/cmssw/pull/47396){:target="_blank"}  from **@guitargeek**: Modernize code of TagProbeFitter `analysis` created: 2025-02-18 23:32:49 merged: 2025-02-19 12:33:14

86. [47394](http://github.com/cms-sw/cmssw/pull/47394){:target="_blank"}  from **@smuzaffar**: Do not fail unit test due to undefined behavior `ml` created: 2025-02-18 22:57:46 merged: 2025-02-26 18:41:43

87. [47393](http://github.com/cms-sw/cmssw/pull/47393){:target="_blank"}  from **@cms-tsg-storm**: fix `customizeHLTfor47047` to work also on menus already customized `hlt` created: 2025-02-18 22:57:32 merged: 2025-02-19 12:31:54

88. [47392](http://github.com/cms-sw/cmssw/pull/47392){:target="_blank"}  from **@Dr15Jones**: Added and_then function to Service class `core` created: 2025-02-18 22:15:52 merged: 2025-02-20 16:18:01

89. [47390](http://github.com/cms-sw/cmssw/pull/47390){:target="_blank"}  from **@guitargeek**: Fix compilation of TagProbeFitter with ROOT master `analysis` created: 2025-02-18 16:52:33 merged: 2025-02-19 12:31:05

90. [47385](http://github.com/cms-sw/cmssw/pull/47385){:target="_blank"}  from **@perrotta**: Update a few GTs in autoCond `alca` created: 2025-02-18 14:41:25 merged: 2025-02-19 16:00:19

91. [47383](http://github.com/cms-sw/cmssw/pull/47383){:target="_blank"}  from **@trackreco**: Enable mkFit initialStep for track building in phase-2 era, and introduce noMkFit phase-2 era(s) `operations` `reconstruction` `tracking` created: 2025-02-18 12:23:22 merged: 2025-02-21 17:38:46

92. [47382](http://github.com/cms-sw/cmssw/pull/47382){:target="_blank"}  from **@AdrianoDee**: Fixing `RelMon` Pages Stylesheets Locations `dqm` created: 2025-02-18 11:23:46 merged: 2025-02-18 17:53:48

93. [47381](http://github.com/cms-sw/cmssw/pull/47381){:target="_blank"}  from **@bsunanda**: Run3-gex187G Modify the scripts to prepare the DDD payloads for the Run2 scenarios `db` created: 2025-02-18 04:40:25 merged: 2025-02-18 17:52:58

94. [47380](http://github.com/cms-sw/cmssw/pull/47380){:target="_blank"}  from **@bsunanda**: Run3-gex187F Update the remaining scriptts in Configuration/Geometry for Calorimeter and Muon systems `geometry` `upgrade` created: 2025-02-18 02:10:03 merged: 2025-02-18 07:13:05

95. [47379](http://github.com/cms-sw/cmssw/pull/47379){:target="_blank"}  from **@rovere**: Remove unused L1T paths from the past from HLT Upgrade Menu. `hlt` created: 2025-02-17 21:00:09 merged: 2025-02-18 17:52:20

96. [47378](http://github.com/cms-sw/cmssw/pull/47378){:target="_blank"}  from **@lguzzi**: move online beam spot arbitration to the edproducer `alca` `dqm` `hlt` `operations` `reconstruction` `db` `tracking` created: 2025-02-17 17:37:27 merged: 2025-03-07 19:58:20

97. [47375](http://github.com/cms-sw/cmssw/pull/47375){:target="_blank"}  from **@bsunanda**: Run3-gex187E Update several geometry scripts for misc. Extended scenarios `geometry` `upgrade` created: 2025-02-17 15:53:14 merged: 2025-02-18 07:11:40

98. [47374](http://github.com/cms-sw/cmssw/pull/47374){:target="_blank"}  from **@Dr15Jones**: Have fillDescriptions generate a template for VPSet in cfi files `core` created: 2025-02-17 15:51:21 merged: 2025-02-18 07:12:48

99. [47373](http://github.com/cms-sw/cmssw/pull/47373){:target="_blank"}  from **@woohyeonHeo**: ME0 L1Trigger Object and producer for CMSSW `l1` `simulation` `upgrade` created: 2025-02-17 14:42:06 merged: 2025-03-04 09:45:11

100. [47371](http://github.com/cms-sw/cmssw/pull/47371){:target="_blank"}  from **@bsunanda**: Run3-gex187D Update some of the geometry cff's of Run2 period `geometry` `upgrade` created: 2025-02-17 14:16:26 merged: 2025-02-18 07:11:53

101. [47370](http://github.com/cms-sw/cmssw/pull/47370){:target="_blank"}  from **@AdrianoDee**: Adding `SimpleTrackValidation` Analyzer `dqm` `tracking` created: 2025-02-17 14:10:20 merged: 2025-02-18 17:51:02

102. [47369](http://github.com/cms-sw/cmssw/pull/47369){:target="_blank"}  from **@mmusich**: make `edmConfigFromDB` exit with an error message `daq` created: 2025-02-17 13:33:36 merged: 2025-02-18 07:12:21

103. [47366](http://github.com/cms-sw/cmssw/pull/47366){:target="_blank"}  from **@bsunanda**: Run3-gex187C Update the scripts for the years 2021, 2023, 2024, 2026 which are used to prepare the payloads from DDD versions `db` created: 2025-02-17 12:45:53 merged: 2025-02-18 07:12:07

104. [47365](http://github.com/cms-sw/cmssw/pull/47365){:target="_blank"}  from **@bsunanda**: Run3-gex187B Correct the payload creation scripts for the years 2024 and 2025 `db` created: 2025-02-17 12:12:55 merged: 2025-02-18 07:11:00

105. [47359](http://github.com/cms-sw/cmssw/pull/47359){:target="_blank"}  from **@mmusich**: fix `throwOnMissing` logic in `ObjectSelectorBase` `reconstruction` created: 2025-02-17 09:02:05 merged: 2025-02-18 07:10:41

106. [47357](http://github.com/cms-sw/cmssw/pull/47357){:target="_blank"}  from **@fwyzard**: Modernise Handle and OrphanHandle interface `analysis` `core` `l1` `reconstruction` `upgrade` `xpog` `tracking` created: 2025-02-15 14:11:49 merged: 2025-03-04 09:44:58

107. [47356](http://github.com/cms-sw/cmssw/pull/47356){:target="_blank"}  from **@fwyzard**: Fix warning about implicitly-declared copy constructor `reconstruction` created: 2025-02-15 13:18:14 merged: 2025-02-18 07:09:57

108. [47355](http://github.com/cms-sw/cmssw/pull/47355){:target="_blank"}  from **@makortel**: Use HardwareResourcesDescription in ProcessConfiguration `core` `dqm` `generators` `simulation` `trk` created: 2025-02-14 20:50:13 merged: 2025-02-26 09:53:18

109. [47354](http://github.com/cms-sw/cmssw/pull/47354){:target="_blank"}  from **@Dr15Jones**: Added VPSetTemplate to configuration `core` created: 2025-02-14 15:33:49 merged: 2025-02-15 08:32:26

110. [47353](http://github.com/cms-sw/cmssw/pull/47353){:target="_blank"}  from **@cquarant**: MTD Geometry - BTL numbering scheme update with correction for backward compatibility `geometry` `operations` `reconstruction` `simulation` `pdmv` `upgrade` `tracking` created: 2025-02-14 14:41:13 merged: 2025-03-07 07:33:30

111. [47352](http://github.com/cms-sw/cmssw/pull/47352){:target="_blank"}  from **@mmusich**: add IT and OT cluster, rechit and tracking rechits validation at HLT for Phase-2 `dqm` `trk` created: 2025-02-14 14:01:04 merged: 2025-02-18 07:13:38

112. [47351](http://github.com/cms-sw/cmssw/pull/47351){:target="_blank"}  from **@fabiocos**: MTD reconstruction and validation: update TkFilterParameters in MTD use with Phase2 settings `dqm` `reconstruction` `simulation` `upgrade` `mtd` created: 2025-02-14 13:40:03 merged: 2025-02-18 07:09:33

113. [47346](http://github.com/cms-sw/cmssw/pull/47346){:target="_blank"}  from **@missirol**: add dictionary for `std::pair<short,int>` `core` created: 2025-02-13 21:44:46 merged: 2025-02-14 17:05:38

114. [47344](http://github.com/cms-sw/cmssw/pull/47344){:target="_blank"}  from **@brunolopesbr2**: Updated HLT BTV validation paths from DeepCSV to PNet `dqm` `btv` created: 2025-02-13 19:19:42 merged: 2025-02-18 07:09:04

115. [47341](http://github.com/cms-sw/cmssw/pull/47341){:target="_blank"}  from **@asavincms**: ZS added to L1TCaloLayer1 `l1` created: 2025-02-13 12:49:37 merged: 2025-02-18 23:18:17

116. [47340](http://github.com/cms-sw/cmssw/pull/47340){:target="_blank"}  from **@jyoti299**: MtdValidation : Add monitoring of unassociated tracks  `dqm` created: 2025-02-13 10:46:54 merged: 2025-02-13 20:15:18

117. [47335](http://github.com/cms-sw/cmssw/pull/47335){:target="_blank"}  from **@vlimant**: add a filter sequence if it is present in the fragment `operations` created: 2025-02-12 11:57:16 merged: 2025-02-18 16:47:27

118. [47332](http://github.com/cms-sw/cmssw/pull/47332){:target="_blank"}  from **@hahnjo**: Remove EMMT physics list, make EMH an alias for EMM + G4HepEm `simulation` created: 2025-02-12 09:05:17 merged: 2025-02-13 20:13:23

119. [47330](http://github.com/cms-sw/cmssw/pull/47330){:target="_blank"}  from **@iarspider**: [GCC14] Fix compilation errors `l1` `reconstruction` `tracking` created: 2025-02-12 08:05:28 merged: 2025-02-18 17:49:18

120. [47328](http://github.com/cms-sw/cmssw/pull/47328){:target="_blank"}  from **@etzovara**:  Developing offline JetMET DQM for Scouting jets - complementary to PR #47212 `dqm` created: 2025-02-11 22:50:03 merged: 2025-02-20 16:12:10

121. [47327](http://github.com/cms-sw/cmssw/pull/47327){:target="_blank"}  from @mmusich: add a test workflow for testing the new `**@hltScouting**` DQM sequence in `ScoutingPFMonitor` dataset `pdmv` `upgrade` created: 2025-02-11 20:43:30 merged: 2025-02-13 20:12:58

122. [47325](http://github.com/cms-sw/cmssw/pull/47325){:target="_blank"}  from **@fwyzard**: Fix `SiPixelClusterizer` alpaka code when `GPU_DEBUG` is defined `core` `reconstruction` `trk` created: 2025-02-11 19:35:05 merged: 2025-02-13 07:14:24

123. [47321](http://github.com/cms-sw/cmssw/pull/47321){:target="_blank"}  from **@iarspider**: Fix Wunused-result warnings in TRGScalers2DB.cc `reconstruction` created: 2025-02-11 16:39:51 merged: 2025-02-13 07:14:59

124. [47320](http://github.com/cms-sw/cmssw/pull/47320){:target="_blank"}  from **@iarspider**: Fix improper use of std::unique and std::remove `dqm` `hlt` `reconstruction` `xpog` `tracking` `trk` created: 2025-02-11 16:23:57 merged: 2025-02-18 07:08:53

125. [47314](http://github.com/cms-sw/cmssw/pull/47314){:target="_blank"}  from **@bsunanda**: Run3-gex187A Add overlap check for 2016 `geometry` `simulation` `upgrade` created: 2025-02-11 05:36:10 merged: 2025-02-12 09:46:03

126. [47313](http://github.com/cms-sw/cmssw/pull/47313){:target="_blank"}  from **@makortel**: Fix compilation of EdmEventSize on clang `core` created: 2025-02-10 21:42:09 merged: 2025-02-12 09:44:35

127. [47308](http://github.com/cms-sw/cmssw/pull/47308){:target="_blank"}  from **@Dr15Jones**: Added template argument to VPSet `core` created: 2025-02-10 14:57:46 merged: 2025-02-12 09:27:31

128. [47305](http://github.com/cms-sw/cmssw/pull/47305){:target="_blank"}  from **@smuzaffar**: Fix gcc14 array-bound error `db` created: 2025-02-10 09:03:21 merged: 2025-02-10 20:02:45

129. [47300](http://github.com/cms-sw/cmssw/pull/47300){:target="_blank"}  from **@fwyzard**: Implement a compile-time warp size constant `reconstruction` `heterogeneous` `tracking` `trk` created: 2025-02-07 21:32:15 merged: 2025-02-13 07:15:44

130. [47299](http://github.com/cms-sw/cmssw/pull/47299){:target="_blank"}  from **@KIT-CMS**: Embedding update for run3 `simulation` created: 2025-02-07 19:10:55 merged: 2025-02-18 07:08:39

131. [47297](http://github.com/cms-sw/cmssw/pull/47297){:target="_blank"}  from **@Dr15Jones**: Can specify TBranch aliases in PoolOutputModule `core` created: 2025-02-07 17:07:22 merged: 2025-02-13 07:14:48

132. [47295](http://github.com/cms-sw/cmssw/pull/47295){:target="_blank"}  from **@thomreis**: Fix event number overflow in ECAL packer `daq` `ecal` created: 2025-02-07 16:02:07 merged: 2025-02-08 11:22:04

133. [47290](http://github.com/cms-sw/cmssw/pull/47290){:target="_blank"}  from **@thomreis**: Fix event number overflow in ES packer `daq` `ecal` created: 2025-02-07 10:01:21 merged: 2025-02-09 06:59:04

134. [47289](http://github.com/cms-sw/cmssw/pull/47289){:target="_blank"}  from **@namapane**: Add protection for type change when updating branches `xpog` created: 2025-02-07 08:58:14 merged: 2025-02-07 15:19:57

135. [47286](http://github.com/cms-sw/cmssw/pull/47286){:target="_blank"}  from **@mmusich**: Remove duplication of configuration of `EGammaSuperclusterProducer` in the Phase-2 HLT menu `hlt` created: 2025-02-06 17:24:15 merged: 2025-02-07 15:18:33

136. [47285](http://github.com/cms-sw/cmssw/pull/47285){:target="_blank"}  from **@bsunanda**: Run3-gex187Z Add the XML files for RPC which provide the right z-positions for the endcap chmbers `geometry` `upgrade` created: 2025-02-06 16:06:43 merged: 2025-02-12 09:29:17

137. [47284](http://github.com/cms-sw/cmssw/pull/47284){:target="_blank"}  from **@makortel**: Fix read rules for CTPPSLocalTrackLite `reconstruction` created: 2025-02-06 14:56:53 merged: 2025-02-08 11:22:46

138. [47283](http://github.com/cms-sw/cmssw/pull/47283){:target="_blank"}  from **@hazeltet845**: Restriction of reemul fg0 in ieta16 `l1` created: 2025-02-06 14:38:42 merged: 2025-02-18 23:16:46

139. [47282](http://github.com/cms-sw/cmssw/pull/47282){:target="_blank"}  from **@artlbv**: [Phase-2 L1]: update readme for P2GT menu configs `l1` `upgrade` created: 2025-02-06 14:06:19 merged: 2025-02-18 17:47:39

140. [47281](http://github.com/cms-sw/cmssw/pull/47281){:target="_blank"}  from **@makortel**: Remove size scalar from HcalRecHitSoALayout as unused `reconstruction` `heterogeneous` created: 2025-02-06 12:57:01 merged: 2025-02-08 11:21:59

141. [47280](http://github.com/cms-sw/cmssw/pull/47280){:target="_blank"}  from **@makortel**: Move `ResourceInformation` abstract base class to FWCore/AbstractServices, and few additional improvements `core` `heterogeneous` `ml` created: 2025-02-06 12:13:15 merged: 2025-02-11 07:28:06

142. [47277](http://github.com/cms-sw/cmssw/pull/47277){:target="_blank"}  from **@gartung**: Update cmsRunGP executable to link with gperftools libprofiler.so after toolfile change `core` created: 2025-02-06 01:21:00 merged: 2025-02-24 17:43:37

143. [47276](http://github.com/cms-sw/cmssw/pull/47276){:target="_blank"}  from **@cramonal**: HGCAL: ECON D CRC (trailer) computation in the Unpacker  `reconstruction` `simulation` `upgrade` created: 2025-02-05 18:46:08 merged: 2025-02-10 20:04:40

144. [47273](http://github.com/cms-sw/cmssw/pull/47273){:target="_blank"}  from **@tore1311**: Fixes to the ChiSquared Test in RelMon `dqm` created: 2025-02-05 15:39:36 merged: 2025-02-08 11:21:48

145. [47271](http://github.com/cms-sw/cmssw/pull/47271){:target="_blank"}  from **@bdanzi**: Reduce minYsizeB1 and minYsizeB2 CA cuts for Phase1 `geometry` `reconstruction` `tracking` created: 2025-02-05 15:21:14 merged: 2025-02-08 11:20:28

146. [47268](http://github.com/cms-sw/cmssw/pull/47268){:target="_blank"}  from **@makortel**: Use `std::span` instead of `edm::Span` `core` `daq` `l1` `xpog` `heterogeneous` created: 2025-02-05 12:17:32 merged: 2025-02-12 08:59:49

147. [47262](http://github.com/cms-sw/cmssw/pull/47262){:target="_blank"}  from **@stahlleiton**: [HGCAL] Implement time corrections in HGCAL TOA kernel `alca` `reconstruction` `db` `upgrade` created: 2025-02-04 17:20:38 merged: 2025-02-25 13:43:55

148. [47261](http://github.com/cms-sw/cmssw/pull/47261){:target="_blank"}  from **@gartung**: Geometry/HGCalCommonData: fix array bounds error `geometry` `upgrade` created: 2025-02-04 16:13:07 merged: 2025-02-10 20:03:35

149. [47257](http://github.com/cms-sw/cmssw/pull/47257){:target="_blank"}  from **@yeckang**: [GEM] Turning on the applyMasking flag for Run 3 GEM data taking `alca` `operations` `reconstruction` `upgrade` created: 2025-02-04 14:04:31 merged: 2025-02-20 16:09:55

150. [47255](http://github.com/cms-sw/cmssw/pull/47255){:target="_blank"}  from **@rsreds**: [NGT] Update FastTimerService to new resource format in circles `hlt` created: 2025-02-04 10:35:24 merged: 2025-02-07 15:19:32

151. [47254](http://github.com/cms-sw/cmssw/pull/47254){:target="_blank"}  from **@smuzaffar**: Remove mkFit based workflow 12834.7 from short matrix `pdmv` `upgrade` `tracking` created: 2025-02-04 09:47:44 merged: 2025-02-12 09:48:35

152. [47252](http://github.com/cms-sw/cmssw/pull/47252){:target="_blank"}  from **@Sam-Harper**: HLT Gen Validation `dqm` created: 2025-02-03 19:32:03 merged: 2025-02-12 09:45:18

153. [47248](http://github.com/cms-sw/cmssw/pull/47248){:target="_blank"}  from **@rsreds**: [NGT] Extend edmEventSize to measure leaf sizes `core` created: 2025-02-03 10:31:48 merged: 2025-02-07 15:19:20

154. [47247](http://github.com/cms-sw/cmssw/pull/47247){:target="_blank"}  from **@bsunanda**: Run3-gex187Y Update some of the scripts for 2021 and 2023 to make the payloads `db` created: 2025-02-03 10:31:14 merged: 2025-02-12 09:48:58

155. [47236](http://github.com/cms-sw/cmssw/pull/47236){:target="_blank"}  from **@bsunanda**: Run3-gex187 Update CondTools/Geometry/ to be ready for preparing the payloads with modified versions of the scenarios `db` created: 2025-02-02 03:26:31 merged: 2025-02-12 09:01:07

156. [47226](http://github.com/cms-sw/cmssw/pull/47226){:target="_blank"}  from **@makortel**: Migrate BeamSpotDeviceProducer and HcalDigisSoAProducer to rely on implicit host-to-device copy `alca` `reconstruction` `heterogeneous` `tracking` created: 2025-01-31 14:56:33 merged: 2025-03-05 06:34:18

157. [47212](http://github.com/cms-sw/cmssw/pull/47212){:target="_blank"}  from **@etzovara**: Developing offline JetMET DQM for Scouting jets `dqm` created: 2025-01-30 15:06:19 merged: 2025-02-08 11:21:33

158. [47198](http://github.com/cms-sw/cmssw/pull/47198){:target="_blank"}  from **@rovere**: Add searchInCommands to runTheMatrix, interactive. `pdmv` `upgrade` created: 2025-01-28 19:51:07 merged: 2025-02-24 11:50:34

159. [47069](http://github.com/cms-sw/cmssw/pull/47069){:target="_blank"}  from **@Parsifal-2045**: [NGT] Implement `NanoAOD` ntuples production for HLT Muon objects `operations` `pdmv` `upgrade` `xpog` created: 2025-01-09 15:42:23 merged: 2025-02-10 20:04:07

160. [46929](http://github.com/cms-sw/cmssw/pull/46929){:target="_blank"}  from **@wddgit**: Print ES module dependences from Tracer `core` `hlt` `heterogeneous` created: 2024-12-12 22:16:17 merged: 2025-02-13 20:15:36

161. [46247](http://github.com/cms-sw/cmssw/pull/46247){:target="_blank"}  from **@iarspider**: [LLVM Analyzer][DQM] Fix some static analyzer warnings `dqm` `db` `tracking` `trk` created: 2024-10-04 07:28:09 merged: 2025-03-12 15:36:47

162. [45475](http://github.com/cms-sw/cmssw/pull/45475){:target="_blank"}  from **@brandiskip**: Outer Tracker Phase2 DQM: additional stub validation plots `dqm` `trk` created: 2024-07-16 21:58:56 merged: 2025-02-19 16:17:31

163. [43596](http://github.com/cms-sw/cmssw/pull/43596){:target="_blank"}  from **@smuzaffar**: Added unit test for checking import ROOT openat calls `core` created: 2023-12-19 10:21:52 merged: 2025-02-26 18:38:47

#### CMSDIST Changes between Tags REL/CMSSW_15_0_1/el8_amd64_gcc12 and REL/CMSSW_15_1_0_pre1/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_15_0_1/el8_amd64_gcc12...REL/CMSSW_15_1_0_pre1/el8_amd64_gcc12)



1. [9734](http://github.com/cms-sw/cmsdist/pull/9734){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-17-00 created: 2025-03-07 07:35:14 merged: 2025-03-07 07:35:16

2. [9732](http://github.com/cms-sw/cmsdist/pull/9732){:target="_blank"}  from **@belforte**: set crab-pre to what is prod ATM created: 2025-03-06 12:11:23 merged: 2025-03-07 11:29:58

3. [9727](http://github.com/cms-sw/cmsdist/pull/9727){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-27-00 created: 2025-03-04 17:52:56 merged: 2025-03-04 17:52:57

4. [9726](http://github.com/cms-sw/cmsdist/pull/9726){:target="_blank"}  from **@sinonkt**: Update CRAB client to v3.250217 in prod. created: 2025-03-04 16:53:11 merged: 2025-03-05 16:26:35

5. [9723](http://github.com/cms-sw/cmsdist/pull/9723){:target="_blank"}  from **@cms-sw**: eigen: Fix enum arithmetic: changes from upstream created: 2025-02-26 21:49:14 merged: 2025-02-26 21:56:21

6. [9722](http://github.com/cms-sw/cmsdist/pull/9722){:target="_blank"}  from **@cms-sw**: cms-common: updated runtime hook to set LC_ALL for all env created: 2025-02-26 18:38:16 merged: 2025-02-26 21:45:52

7. [9719](http://github.com/cms-sw/cmsdist/pull/9719){:target="_blank"}  from **@cms-sw**: vecgeom:  Do not read destructed memory created: 2025-02-25 11:21:28 merged: 2025-02-25 15:37:45

8. [9718](http://github.com/cms-sw/cmsdist/pull/9718){:target="_blank"}  from **@cms-sw**: Update tag for DQM-Integration to V00-09-00 created: 2025-02-25 11:01:26 merged: 2025-02-25 11:01:29

9. [9717](http://github.com/cms-sw/cmsdist/pull/9717){:target="_blank"}  from **@cms-sw**: ThePeg: fix warning for arithmetic between enumeration and float type created: 2025-02-25 10:59:01 merged: 2025-02-25 13:52:36

10. [9716](http://github.com/cms-sw/cmsdist/pull/9716){:target="_blank"}  from **@cms-sw**: [protobuf]Patched to avoid non-virtual-dtor warning created: 2025-02-25 10:30:30 merged: 2025-02-25 21:03:09

11. [9715](http://github.com/cms-sw/cmsdist/pull/9715){:target="_blank"}  from **@cms-sw**: Update tag for DQM-Integration to V00-08-00 created: 2025-02-24 17:35:34 merged: 2025-02-24 17:35:36

12. [9713](http://github.com/cms-sw/cmsdist/pull/9713){:target="_blank"}  from **@cms-sw**: boost:1.80: patch to avoid gcc14 usage of conversion operator warning created: 2025-02-23 10:32:41 merged: 2025-02-24 17:30:44

13. [9712](http://github.com/cms-sw/cmsdist/pull/9712){:target="_blank"}  from **@cms-sw**: SCRAM: typo created: 2025-02-22 13:46:49 merged: 2025-02-22 15:20:39

14. [9711](http://github.com/cms-sw/cmsdist/pull/9711){:target="_blank"}  from **@cms-sw**: Coral: replace deprecated boost::filesystem::path::is_complete with is_absolute created: 2025-02-22 11:54:00 merged: 2025-02-22 15:20:55

15. [9710](http://github.com/cms-sw/cmsdist/pull/9710){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-MkFit to V00-16-00 created: 2025-02-21 17:39:01 merged: 2025-02-21 17:39:03

16. [9709](http://github.com/cms-sw/cmsdist/pull/9709){:target="_blank"}  from **@aloeliger**: Update CICADA.spec to 1.4.0 created: 2025-02-21 16:46:46 merged: 2025-02-24 17:09:06

17. [9706](http://github.com/cms-sw/cmsdist/pull/9706){:target="_blank"}  from **@cms-sw**: TBB version v2022.0.0 created: 2025-02-20 14:48:39 merged: 2025-02-21 21:37:51

18. [9705](http://github.com/cms-sw/cmsdist/pull/9705){:target="_blank"}  from **@cms-sw**: Updated cryptography  to 44.0.1 created: 2025-02-20 14:16:29 merged: 2025-02-20 22:00:58

19. [9704](http://github.com/cms-sw/cmsdist/pull/9704){:target="_blank"}  from **@hahnjo**: Integrate latest fixes for G4HepEm created: 2025-02-20 13:06:51 merged: 2025-02-21 07:14:21

20. [9703](http://github.com/cms-sw/cmsdist/pull/9703){:target="_blank"}  from **@cms-sw**: Update zstd to version 1.5.7 created: 2025-02-20 09:22:30 merged: 2025-02-20 22:01:17

21. [9699](http://github.com/cms-sw/cmsdist/pull/9699){:target="_blank"}  from **@smuzaffar**: Updated root to tip of branch v6-32-00-patches created: 2025-02-19 14:41:05 merged: 2025-02-19 20:11:09

22. [9696](http://github.com/cms-sw/cmsdist/pull/9696){:target="_blank"}  from **@cms-sw**: CPPUnit: Updated to latest 1.15.1 + changes created: 2025-02-18 14:33:12 merged: 2025-02-18 21:13:41

23. [9695](http://github.com/cms-sw/cmsdist/pull/9695){:target="_blank"}  from **@thesps**: Bump conifer to 1.6 created: 2025-02-17 13:37:59 merged: 2025-02-18 09:25:51

24. [9693](http://github.com/cms-sw/cmsdist/pull/9693){:target="_blank"}  from **@belforte**: Update crab-dev.spec created: 2025-02-17 10:29:38 merged: 2025-02-17 13:04:21

25. [9692](http://github.com/cms-sw/cmsdist/pull/9692){:target="_blank"}  from **@belforte**: bump crab-dev to prod created: 2025-02-16 17:48:21 merged: 2025-02-17 11:01:09

26. [9690](http://github.com/cms-sw/cmsdist/pull/9690){:target="_blank"}  from **@cms-sw**: fwlite: add FWCore/AbstractServices created: 2025-02-12 21:40:47 merged: 2025-02-12 21:41:08

27. [9689](http://github.com/cms-sw/cmsdist/pull/9689){:target="_blank"}  from **@gartung**: Gperftools: compile without libunwind created: 2025-02-12 17:15:25 merged: 2025-02-12 21:29:52

28. [9687](http://github.com/cms-sw/cmsdist/pull/9687){:target="_blank"}  from **@cms-sw**: Update Pytorch to 2.6.0; add support for cuda_arch 90 to cuda_flags created: 2025-02-12 09:39:47 merged: 2025-02-18 09:24:56

29. [9683](http://github.com/cms-sw/cmsdist/pull/9683){:target="_blank"}  from **@fwyzard**: Update hwloc to version 2.12.0 created: 2025-02-11 06:54:32 merged: 2025-02-18 21:10:34

30. [9682](http://github.com/cms-sw/cmsdist/pull/9682){:target="_blank"}  from **@cms-sw**: Buildrules: alpaka: Do not add self dependency if package/src generates edm plugin created: 2025-02-11 06:19:56 merged: 2025-02-11 16:57:34

31. [9675](http://github.com/cms-sw/cmsdist/pull/9675){:target="_blank"}  from **@cms-sw**: Update Vecgeom to v1.2.10 created: 2025-02-04 16:13:08 merged: 2025-02-10 15:47:01
