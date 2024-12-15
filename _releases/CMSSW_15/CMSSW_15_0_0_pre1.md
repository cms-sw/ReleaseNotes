---
layout: post
rel_link:  "15_0_0_pre1"
title:  "CMSSW_15_0_0_pre1"
date:   2024-12-14 20:31:03
categories: cmssw
relmajor: 15
relminor: 0
relsubminor: 0
relpre: _pre1
---

# CMSSW_15_0_0_pre1
#### Changes since CMSSW_14_2_0_pre4:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_2_0_pre4...CMSSW_15_0_0_pre1)



1. [46919](http://github.com/cms-sw/cmssw/pull/46919){:target="_blank"}  from **@smuzaffar**: Fix for importing ClassesDefXmlUtils `core` created: 2024-12-12 08:38:28 merged: 2024-12-12 15:52:50

2. [46913](http://github.com/cms-sw/cmssw/pull/46913){:target="_blank"}  from **@mmusich**: Follow-up to HLT HG Combined PCL workflow `alca` `db` `trk` created: 2024-12-11 15:56:42 merged: 2024-12-12 15:53:51

3. [46911](http://github.com/cms-sw/cmssw/pull/46911){:target="_blank"}  from **@fabiocos**: MTD geometry: add BTL topology to MTDTopology, reorganize dependencies `dqm` `geometry` `reconstruction` `simulation` `upgrade` `tracking` `mtd` created: 2024-12-11 10:55:55 merged: 2024-12-12 15:54:33

4. [46909](http://github.com/cms-sw/cmssw/pull/46909){:target="_blank"}  from **@AdrianoDee**: Restoring 2023 RelVal Inputs `pdmv` `upgrade` created: 2024-12-11 10:14:05 merged: 2024-12-11 16:54:04

5. [46906](http://github.com/cms-sw/cmssw/pull/46906){:target="_blank"}  from **@leonardogiannini**: [mkFit] small fix in propToPlane `reconstruction` `tracking` created: 2024-12-10 04:23:37 merged: 2024-12-11 09:32:05

6. [46905](http://github.com/cms-sw/cmssw/pull/46905){:target="_blank"}  from **@mbluj**: Sort hybrid taus with descending pt [fix] `reconstruction` `xpog` created: 2024-12-09 23:33:52 merged: 2024-12-11 13:15:28

7. [46902](http://github.com/cms-sw/cmssw/pull/46902){:target="_blank"}  from **@mmusich**: fix clang linking issue in `SimMuon/MCTruth` `simulation` created: 2024-12-09 16:52:04 merged: 2024-12-10 08:52:31

8. [46896](http://github.com/cms-sw/cmssw/pull/46896){:target="_blank"}  from **@iarspider**: SeedToTrackProducer: return early if L2 seed collection is not found `simulation` created: 2024-12-09 10:33:08 merged: 2024-12-10 08:52:19

9. [46893](http://github.com/cms-sw/cmssw/pull/46893){:target="_blank"}  from **@mmusich**: Improve messages due `VertexException` in `SequentialPrimaryVertexFitterAdapter` and clean-up of `BeamSpotOnlineProducer` `alca` `reconstruction` `tracking` created: 2024-12-07 10:46:10 merged: 2024-12-09 17:46:04

10. [46892](http://github.com/cms-sw/cmssw/pull/46892){:target="_blank"}  from **@mmusich**: fix replacing of split pixel clusters in DQM online clients after #46694 `dqm` created: 2024-12-07 10:45:35 merged: 2024-12-09 15:01:24

11. [46891](http://github.com/cms-sw/cmssw/pull/46891){:target="_blank"}  from **@mkirsano**: Change Vtx generators to allow HepMC3Product smearing `simulation` created: 2024-12-06 17:30:50 merged: 2024-12-09 17:45:31

12. [46890](http://github.com/cms-sw/cmssw/pull/46890){:target="_blank"}  from **@bsunanda**: Phase2-gex184 Change directory name 2026 to 2030 to enable future Run3 runs during 2026 `geometry` `upgrade` `tracking` `trk` created: 2024-12-06 15:42:58 merged: 2024-12-12 15:53:36

13. [46888](http://github.com/cms-sw/cmssw/pull/46888){:target="_blank"}  from **@cms-trackeralign**: Introduce High Granularity Tracker Alignment Prompt Calibration Loop for HLT alignment conditions `alca` `operations` created: 2024-12-06 11:07:22 merged: 2024-12-10 16:59:22

14. [46887](http://github.com/cms-sw/cmssw/pull/46887){:target="_blank"}  from **@fwyzard**: Fix PFClusterSoAProducer to read a device collection `reconstruction` created: 2024-12-06 09:43:19 merged: 2024-12-11 13:31:39

15. [46886](http://github.com/cms-sw/cmssw/pull/46886){:target="_blank"}  from **@bsunanda**: Phase2-hgx360T Make a test code to find the area of HGCal cells through the method "cellArea" of HGCalDDConst `geometry` `upgrade` created: 2024-12-06 09:27:38 merged: 2024-12-07 06:19:52

16. [46883](http://github.com/cms-sw/cmssw/pull/46883){:target="_blank"}  from **@makortel**: Add `customiseWithTimeMemoryInfo()` function to `TimeMemoryInfo.py` `core` created: 2024-12-05 17:09:49 merged: 2024-12-07 06:19:13

17. [46878](http://github.com/cms-sw/cmssw/pull/46878){:target="_blank"}  from **@stahlleiton**: Implement eras for Run3 2025 PbPb UPC and oxygen runs `operations` `pdmv` `upgrade` created: 2024-12-05 12:14:41 merged: 2024-12-11 09:32:29

18. [46877](http://github.com/cms-sw/cmssw/pull/46877){:target="_blank"}  from **@fwyzard**: Let `edm::Wrapper<T>` use the constructor `T{kUninitialized}` `core` `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-12-05 11:34:16 merged: 2024-12-11 13:31:46

19. [46876](http://github.com/cms-sw/cmssw/pull/46876){:target="_blank"}  from **@fwyzard**: Do not use default-constructed PortableCollections `reconstruction` `heterogeneous` `trk` created: 2024-12-05 08:43:13 merged: 2024-12-05 21:07:47

20. [46875](http://github.com/cms-sw/cmssw/pull/46875){:target="_blank"}  from **@fwyzard**: Constrain the TriggerObject template constructors `hlt` created: 2024-12-05 08:37:20 merged: 2024-12-05 12:27:33

21. [46874](http://github.com/cms-sw/cmssw/pull/46874){:target="_blank"}  from **@fwyzard**: Use #include <...> for external headers `core` `reconstruction` created: 2024-12-05 07:56:10 merged: 2024-12-05 21:06:41

22. [46871](http://github.com/cms-sw/cmssw/pull/46871){:target="_blank"}  from **@wddgit**: SubProcess bug fix, updateLookup called too early `core` created: 2024-12-04 23:21:34 merged: 2024-12-10 08:53:26

23. [46870](http://github.com/cms-sw/cmssw/pull/46870){:target="_blank"}  from **@smuzaffar**: Class version update unit test fix `core` created: 2024-12-04 18:40:45 merged: 2024-12-05 07:30:05

24. [46861](http://github.com/cms-sw/cmssw/pull/46861){:target="_blank"}  from **@Parsifal-2045**: Optimise muon seed MVA classifier `reconstruction` created: 2024-12-04 09:14:36 merged: 2024-12-04 18:40:38

25. [46860](http://github.com/cms-sw/cmssw/pull/46860){:target="_blank"}  from **@Parsifal-2045**: Implement Phase 2 Muon HLT validation `dqm` `operations` `simulation` created: 2024-12-04 09:07:55 merged: 2024-12-06 12:55:28

26. [46857](http://github.com/cms-sw/cmssw/pull/46857){:target="_blank"}  from **@SegmentLinking**: LST algorithm developments accumulated during integration PR `reconstruction` `tracking` created: 2024-12-03 21:23:53 merged: 2024-12-04 09:15:51

27. [46854](http://github.com/cms-sw/cmssw/pull/46854){:target="_blank"}  from **@nothingface0**: [DQM] Update `compareDQMOutput.py` `dqm` created: 2024-12-03 14:10:29 merged: 2024-12-05 12:24:05

28. [46851](http://github.com/cms-sw/cmssw/pull/46851){:target="_blank"}  from **@mmusich**: fix `CaloParticle` class version after #46678 `simulation` created: 2024-12-03 10:28:12 merged: 2024-12-03 16:26:30

29. [46844](http://github.com/cms-sw/cmssw/pull/46844){:target="_blank"}  from **@SegmentLinking**: Fix to LST code due to uninitialization of the shiftedRt2 variable `reconstruction` `tracking` created: 2024-12-02 18:22:32 merged: 2024-12-03 16:26:55

30. [46843](http://github.com/cms-sw/cmssw/pull/46843){:target="_blank"}  from **@AdrianoDee**: Disable 2022/2023 MC Tests `pdmv` `upgrade` created: 2024-12-02 13:00:52 merged: 2024-12-06 12:54:16

31. [46841](http://github.com/cms-sw/cmssw/pull/46841){:target="_blank"}  from **@AdrianoDee**: Use `Run4` for Phase2 PU inputs `pdmv` `upgrade` created: 2024-12-02 12:01:42 merged: 2024-12-02 19:48:18

32. [46840](http://github.com/cms-sw/cmssw/pull/46840){:target="_blank"}  from **@enibigir**: Update HSCParticle object to be compatible with MiniAOD `analysis` created: 2024-12-02 11:02:35 merged: 2024-12-04 14:43:48

33. [46833](http://github.com/cms-sw/cmssw/pull/46833){:target="_blank"}  from **@mmusich**: `TriggerResultsFilterFromDB`: accept all triggers paths in presence of an empty list of expressions `hlt` created: 2024-11-30 14:38:13 merged: 2024-12-02 15:43:49

34. [46829](http://github.com/cms-sw/cmssw/pull/46829){:target="_blank"}  from **@fwyzard**: Remove the explicit dependency on non-alpaka main library `reconstruction` `heterogeneous` `tracking` created: 2024-11-29 15:26:19 merged: 2024-12-05 09:44:51

35. [46828](http://github.com/cms-sw/cmssw/pull/46828){:target="_blank"}  from **@SegmentLinking**: Addition of single iteration Patatrack and LST HLT configurations and workflows `hlt` `operations` `reconstruction` `pdmv` `upgrade` `tracking` created: 2024-11-29 14:56:54 merged: 2024-12-04 09:18:16

36. [46827](http://github.com/cms-sw/cmssw/pull/46827){:target="_blank"}  from **@mmusich**: Add Phase1 pixel tracker maps to `TrackerAlignmentErrorExtended_PayloadInspector` `db` created: 2024-11-29 08:47:08 merged: 2024-11-29 20:54:02

37. [46826](http://github.com/cms-sw/cmssw/pull/46826){:target="_blank"}  from **@mmusich**: `DeDxCalibration` as `SiStrip` gains and fixes to the APV gain payload inspector `db` `trk` created: 2024-11-29 07:58:42 merged: 2024-11-29 20:56:22

38. [46825](http://github.com/cms-sw/cmssw/pull/46825){:target="_blank"}  from **@fwyzard**: Fix `EmptySourceFromEventIDs` test configuration `core` created: 2024-11-28 15:00:15 merged: 2024-11-29 09:07:10

39. [46824](http://github.com/cms-sw/cmssw/pull/46824){:target="_blank"}  from **@perrotta**: Update 141X data GTs in autoCond `alca` `dqm` created: 2024-11-28 14:55:27 merged: 2024-12-05 09:50:31

40. [46823](http://github.com/cms-sw/cmssw/pull/46823){:target="_blank"}  from **@mmusich**: add DQM / Validation monitoring for `hltInitialStep` and  `hltHighPtTriplet` tracks in the Phase2 HLT menu `dqm` `operations` `tracking` created: 2024-11-28 14:05:42 merged: 2024-12-04 14:38:38

41. [46820](http://github.com/cms-sw/cmssw/pull/46820){:target="_blank"}  from **@bsunanda**: Phase2-hgx360Y Update some of the parameters for V19 version of HGCal geometry `geometry` `upgrade` created: 2024-11-28 07:57:56 merged: 2024-11-28 12:12:28

42. [46818](http://github.com/cms-sw/cmssw/pull/46818){:target="_blank"}  from **@bsunanda**: Run3-gex183 Define the additional scenarios for 2025: required to prepare the payloads for 2025 `geometry` `operations` `upgrade` created: 2024-11-28 07:31:26 merged: 2024-11-29 09:06:25

43. [46813](http://github.com/cms-sw/cmssw/pull/46813){:target="_blank"}  from **@CMSTrackerDPG**: Allow using fake pixels from the digi morphing algorithm as cluster seeds but drop them from final clusters `reconstruction` `trk` created: 2024-11-27 17:36:34 merged: 2024-11-29 09:08:44

44. [46812](http://github.com/cms-sw/cmssw/pull/46812){:target="_blank"}  from **@bsunanda**: Run3-alca251 Modify the HCAL calibration macros in view of current and 2025 IsoTrack calibrations `alca` created: 2024-11-27 16:12:27 merged: 2024-11-29 09:09:25

45. [46804](http://github.com/cms-sw/cmssw/pull/46804){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_1_X` (4/N)  [`15_0_X`] `alca` `hlt` created: 2024-11-26 17:53:35 merged: 2024-11-27 13:56:03

46. [46802](http://github.com/cms-sw/cmssw/pull/46802){:target="_blank"}  from **@SegmentLinking**: Removal of LST *ByLayer( functions to fix build errors `reconstruction` `tracking` created: 2024-11-26 16:45:56 merged: 2024-11-26 19:52:30

47. [46801](http://github.com/cms-sw/cmssw/pull/46801){:target="_blank"}  from **@Cvico**: Update on genDressedLepton pT threshold for nanoAOD `xpog` created: 2024-11-26 15:29:08 merged: 2024-11-27 05:47:14

48. [46800](http://github.com/cms-sw/cmssw/pull/46800){:target="_blank"}  from **@AlessandroTarabini**: Increase precision of two shower shape observables for Hgg analysis `xpog` created: 2024-11-26 15:17:37 merged: 2024-11-27 05:47:10

49. [46799](http://github.com/cms-sw/cmssw/pull/46799){:target="_blank"}  from **@bsunanda**: Phase2-gex182 Complete the Run4D116 scenario which mimicj Run4D110 but with much reduced overlaps `geometry` `upgrade` created: 2024-11-26 08:46:08 merged: 2024-11-26 19:53:15

50. [46798](http://github.com/cms-sw/cmssw/pull/46798){:target="_blank"}  from **@bsunanda**: Run3-gex181 Getting ready for preparing payload of 2025 Geometry `db` created: 2024-11-26 08:33:25 merged: 2024-11-26 19:55:27

51. [46797](http://github.com/cms-sw/cmssw/pull/46797){:target="_blank"}  from **@mkirsano**: Hepmc3tog4, addind the codes that provide a possibility to transfer HepMC3Product from the GEN step to the SIM step  `analysis` `generators` `simulation` created: 2024-11-25 18:33:24 merged: 2024-11-29 20:55:29

52. [46795](http://github.com/cms-sw/cmssw/pull/46795){:target="_blank"}  from **@smuzaffar**: [ROOT6]Drop extra space from the key name `dqm` created: 2024-11-25 16:16:15 merged: 2024-11-26 19:52:14

53. [46794](http://github.com/cms-sw/cmssw/pull/46794){:target="_blank"}  from **@smuzaffar**: [UBSAN]Check for finite tracklet seeding or d0 cut `l1` created: 2024-11-25 15:21:53 merged: 2024-11-26 13:53:58

54. [46793](http://github.com/cms-sw/cmssw/pull/46793){:target="_blank"}  from **@AdrianoDee**: Update Default Datasets for 2022 (was 2021) `pdmv` `upgrade` created: 2024-11-25 11:43:56 merged: 2024-12-09 17:45:06

55. [46791](http://github.com/cms-sw/cmssw/pull/46791){:target="_blank"}  from **@smuzaffar**: Fix DQM config test: Increase number of sequences to process `dqm` created: 2024-11-25 07:16:03 merged: 2024-11-25 18:03:45

56. [46790](http://github.com/cms-sw/cmssw/pull/46790){:target="_blank"}  from **@fwyzard**: Implement framework modules for EventID-related tests `core` created: 2024-11-24 22:36:01 merged: 2024-11-28 07:44:28

57. [46789](http://github.com/cms-sw/cmssw/pull/46789){:target="_blank"}  from **@Dr15Jones**: Reduced allocations in  ShiftedJetProducerT `reconstruction` `db` `xpog` created: 2024-11-24 14:41:15 merged: 2024-11-26 19:54:30

58. [46787](http://github.com/cms-sw/cmssw/pull/46787){:target="_blank"}  from **@Dr15Jones**: Fix off by 1 error in Multi5x5ClusterAlgo `reconstruction` created: 2024-11-23 21:04:30 merged: 2024-11-25 18:04:10

59. [46784](http://github.com/cms-sw/cmssw/pull/46784){:target="_blank"}  from **@bsunanda**: Run3-hcx380 Correct the scenario for 2025 by including the DT shield `geometry` `upgrade` created: 2024-11-23 08:43:25 merged: 2024-11-25 08:20:18

60. [46782](http://github.com/cms-sw/cmssw/pull/46782){:target="_blank"}  from **@smuzaffar**: [L1-UPGRADE] py2/3 compatibility:drop use of __future__ `l1` `upgrade` created: 2024-11-22 17:19:31 merged: 2024-12-01 07:37:10

61. [46781](http://github.com/cms-sw/cmssw/pull/46781){:target="_blank"}  from **@smuzaffar**: [OPERATIONS] py2/3 compatibility:drop use of __future__ `operations` created: 2024-11-22 17:19:26 merged: 2024-11-28 08:58:56

62. [46780](http://github.com/cms-sw/cmssw/pull/46780){:target="_blank"}  from **@smuzaffar**: [MISC3] py2/3 compatibility:drop use of __future__ `dqm` `generators` `xpog` created: 2024-11-22 17:19:10 merged: 2024-11-27 19:05:56

63. [46779](http://github.com/cms-sw/cmssw/pull/46779){:target="_blank"}  from **@smuzaffar**: [MISC2] py2/3 compatibility:drop use of __future__ `fastsim` `generators` `geometry` `visualization` `heterogeneous` `trk` created: 2024-11-22 17:19:02 merged: 2024-11-30 11:46:41

64. [46778](http://github.com/cms-sw/cmssw/pull/46778){:target="_blank"}  from **@smuzaffar**: [MISC1] py2/3 compatibility:drop use of __future__ `alca` `dqm` `geometry` `hlt` `l1` `pdmv` `db` `upgrade` `tracking` created: 2024-11-22 17:18:56 merged: 2024-12-01 14:58:35

65. [46777](http://github.com/cms-sw/cmssw/pull/46777){:target="_blank"}  from **@smuzaffar**: [DQM-GEOMETRY] py2/3 compatibility:drop use of __future__ `dqm` `geometry` created: 2024-11-22 17:18:39 merged: 2024-11-28 07:50:31

66. [46776](http://github.com/cms-sw/cmssw/pull/46776){:target="_blank"}  from **@smuzaffar**: [SIMULATION-UPGRADE] py2/3 compatibility:drop use of __future__ `simulation` `upgrade` created: 2024-11-22 17:18:34 merged: 2024-12-01 14:58:05

67. [46775](http://github.com/cms-sw/cmssw/pull/46775){:target="_blank"}  from **@smuzaffar**: [ALCA-RECONSTRUCTION] py2/3 compatibility:drop use of __future__ `alca` `reconstruction` `tracking` created: 2024-11-22 17:18:28 merged: 2024-11-26 14:32:00

68. [46774](http://github.com/cms-sw/cmssw/pull/46774){:target="_blank"}  from **@smuzaffar**: [SIMULATION] py2/3 compatibility:drop use of __future__ `simulation` `trk` created: 2024-11-22 17:18:11 merged: 2024-11-26 14:24:04

69. [46773](http://github.com/cms-sw/cmssw/pull/46773){:target="_blank"}  from **@smuzaffar**: [HLT] py2/3 compatibility:drop use of __future__ `hlt` created: 2024-11-22 17:18:05 merged: 2024-11-25 08:20:04

70. [46772](http://github.com/cms-sw/cmssw/pull/46772){:target="_blank"}  from **@smuzaffar**: [DAQ] py2/3 compatibility:drop use of __future__ `daq` created: 2024-11-22 17:17:59 merged: 2024-11-24 09:40:13

71. [46771](http://github.com/cms-sw/cmssw/pull/46771){:target="_blank"}  from **@smuzaffar**: [L1] py2/3 compatibility:drop use of __future__ `l1` created: 2024-11-22 17:17:41 merged: 2024-11-26 14:15:16

72. [46770](http://github.com/cms-sw/cmssw/pull/46770){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION-XPOG] py2/3 compatibility:drop use of __future__ `reconstruction` `xpog` created: 2024-11-22 17:17:35 merged: 2024-11-26 14:34:23

73. [46769](http://github.com/cms-sw/cmssw/pull/46769){:target="_blank"}  from **@smuzaffar**: [CORE] py2/3 compatibility:drop use of __future__ `core` created: 2024-11-22 17:17:30 merged: 2024-11-29 09:10:38

74. [46768](http://github.com/cms-sw/cmssw/pull/46768){:target="_blank"}  from **@smuzaffar**: [ANALYSIS] py2/3 compatibility:drop use of __future__ `analysis` `trk` created: 2024-11-22 17:17:15 merged: 2024-11-23 15:22:49

75. [46767](http://github.com/cms-sw/cmssw/pull/46767){:target="_blank"}  from **@smuzaffar**: [DQM] py2/3 compatibility:drop use of __future__ `dqm` `tracking` `trk` created: 2024-11-22 17:17:09 merged: 2024-11-25 18:03:21

76. [46766](http://github.com/cms-sw/cmssw/pull/46766){:target="_blank"}  from **@smuzaffar**: [PDMV-UPGRADE] py2/3 compatibility:drop use of __future__ `pdmv` `upgrade` created: 2024-11-22 17:17:02 merged: 2024-12-01 07:36:38

77. [46765](http://github.com/cms-sw/cmssw/pull/46765){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] py2/3 compatibility:drop use of __future__ `reconstruction` `tracking` `trk` created: 2024-11-22 17:16:46 merged: 2024-11-24 09:33:11

78. [46764](http://github.com/cms-sw/cmssw/pull/46764){:target="_blank"}  from **@smuzaffar**: [ALCA-DB] py2/3 compatibility:drop use of __future__ `alca` `db` `trk` created: 2024-11-22 17:16:35 merged: 2024-11-24 09:44:28

79. [46763](http://github.com/cms-sw/cmssw/pull/46763){:target="_blank"}  from **@jking79**: Update ecalMultiFitUncalibRecHit_cfi.py  parameters for CC `alca` `reconstruction` `ecal` created: 2024-11-22 16:01:28 merged: 2024-12-04 14:37:37

80. [46761](http://github.com/cms-sw/cmssw/pull/46761){:target="_blank"}  from **@fabiocos**: MTD geometry: Fix MTDGeometryBuilder text to avoid rounding issues with alternative architectures `geometry` `upgrade` `mtd` created: 2024-11-22 14:51:31 merged: 2024-11-26 19:53:40

81. [46760](http://github.com/cms-sw/cmssw/pull/46760){:target="_blank"}  from **@smorovic**: (HLT) fix service discovery in HLTriggerJSONMonitoring `hlt` created: 2024-11-22 09:07:13 merged: 2024-11-27 05:45:24

82. [46758](http://github.com/cms-sw/cmssw/pull/46758){:target="_blank"}  from **@smuzaffar**: [UBSAN][LST]Fix runtime error by keep the region object alive `reconstruction` `tracking` created: 2024-11-21 22:27:23 merged: 2024-11-22 12:36:20

83. [46756](http://github.com/cms-sw/cmssw/pull/46756){:target="_blank"}  from **@Dr15Jones**: avoid holding memory between events in Multi5x5ClusterProducer  `reconstruction` created: 2024-11-21 18:49:23 merged: 2024-11-22 12:35:44

84. [46755](http://github.com/cms-sw/cmssw/pull/46755){:target="_blank"}  from **@bsunanda**: Phase2-hgx360FX Attempt to make a Phase2 scenario with 0 overlaps with zero tolerance in lieu of #46565 and #46610 `geometry` `operations` `pdmv` `upgrade` created: 2024-11-21 16:35:41 merged: 2024-11-25 16:19:55

85. [46754](http://github.com/cms-sw/cmssw/pull/46754){:target="_blank"}  from **@smuzaffar**: Avoid using past module for python2/3 compatibility `core` created: 2024-11-21 15:58:08 merged: 2024-11-22 08:25:33

86. [46753](http://github.com/cms-sw/cmssw/pull/46753){:target="_blank"}  from **@bsunanda**: Phase2-hgx360W Provide a method in HGCALDDDConst to access the area of a cell `geometry` `upgrade` created: 2024-11-21 14:37:43 merged: 2024-11-24 09:34:24

87. [46752](http://github.com/cms-sw/cmssw/pull/46752){:target="_blank"}  from **@martinamalberti**: MTD reconstruction: save correct outermost hit position also for tracks w/o last hit in mtd `reconstruction` `upgrade` created: 2024-11-21 14:02:21 merged: 2024-12-02 15:42:24

88. [46751](http://github.com/cms-sw/cmssw/pull/46751){:target="_blank"}  from **@kdeleo**: RecoMTD: new class for storing variables for BTD and GNN training `reconstruction` `upgrade` `mtd` created: 2024-11-21 13:22:12 merged: 2024-11-24 09:39:09

89. [46749](http://github.com/cms-sw/cmssw/pull/46749){:target="_blank"}  from **@dsidirop1**: Updated Input tags and code additions for TOP Production DQM GEN-SIM-RECO `dqm` created: 2024-11-20 15:31:58 merged: 2024-11-27 19:05:26

90. [46744](http://github.com/cms-sw/cmssw/pull/46744){:target="_blank"}  from **@bsunanda**: Run3-hcx379X Creating the possibility to add the additional MB4 shield in Phase2 scenarios `geometry` `upgrade` created: 2024-11-20 12:44:16 merged: 2024-11-21 08:37:46

91. [46743](http://github.com/cms-sw/cmssw/pull/46743){:target="_blank"}  from **@bsunanda**: Phase2-hgx360V Use the keyword Run4 instead of 2026 for naming a scenario in SimG4Core/PrintGeomInfo/test/python `simulation` created: 2024-11-20 12:26:24 merged: 2024-11-21 08:36:59

92. [46742](http://github.com/cms-sw/cmssw/pull/46742){:target="_blank"}  from **@mmusich**:  Use `TriggerResultsFilterFromDB` instead of `HLTHighLevel`,  in order to allow prescaled HLT paths in `EcalESAlign` and `HcalCalIterativePhiSym`  `alca` created: 2024-11-20 11:12:18 merged: 2024-12-02 19:47:58

93. [46738](http://github.com/cms-sw/cmssw/pull/46738){:target="_blank"}  from **@JHiltbrand**: Improvements for HCAL LUT XML Diffing `alca` `l1` `db` created: 2024-11-19 15:58:12 merged: 2024-11-26 14:21:03

94. [46737](http://github.com/cms-sw/cmssw/pull/46737){:target="_blank"}  from **@francescobrivio**: Temporary Rollback for DIP BeamSpot client `dqm` created: 2024-11-19 15:52:16 merged: 2024-11-20 19:21:10

95. [46734](http://github.com/cms-sw/cmssw/pull/46734){:target="_blank"}  from **@bsunanda**: Phase2-hgx360U Update the code for guard ring and mouse bite usage in full and partial wafers in HGCal geometry definition `simulation` created: 2024-11-19 13:38:24 merged: 2024-11-21 08:37:35

96. [46733](http://github.com/cms-sw/cmssw/pull/46733){:target="_blank"}  from **@bsunanda**: Phase2-hgx360S Update a few constants in v19 hgcal.xml file `geometry` `upgrade` created: 2024-11-19 13:33:39 merged: 2024-11-20 19:21:23

97. [46732](http://github.com/cms-sw/cmssw/pull/46732){:target="_blank"}  from **@battibass**: [Simulation] Allow DT ageing toy model to run at the DIGI-L1T step `simulation` created: 2024-11-19 11:16:29 merged: 2024-11-25 11:56:49

98. [46729](http://github.com/cms-sw/cmssw/pull/46729){:target="_blank"}  from **@Dr15Jones**: Avoid allocations in ParentageID `core` created: 2024-11-18 21:33:45 merged: 2024-11-24 09:33:52

99. [46728](http://github.com/cms-sw/cmssw/pull/46728){:target="_blank"}  from **@ctdax**: Fixed energy of R-Hadron cloud in energy deposit model `simulation` created: 2024-11-18 18:53:54 merged: 2024-11-21 08:38:38

100. [46720](http://github.com/cms-sw/cmssw/pull/46720){:target="_blank"}  from **@bsunanda**: Phase2-hgx360R Inhibit ZDC digitization in Phase2 scenario `simulation` created: 2024-11-18 08:10:32 merged: 2024-11-21 08:38:04

101. [46707](http://github.com/cms-sw/cmssw/pull/46707){:target="_blank"}  from **@smuzaffar**: [Py312] Move away from using imp python module `core` created: 2024-11-15 10:41:38 merged: 2024-11-23 15:24:04

102. [46705](http://github.com/cms-sw/cmssw/pull/46705){:target="_blank"}  from **@bsunanda**: Run3-hcx379 First version of 2025 scenario - still needed the correct PPS geometry with the needed rotation `geometry` `operations` `upgrade` created: 2024-11-15 06:39:35 merged: 2024-11-22 16:06:06

103. [46703](http://github.com/cms-sw/cmssw/pull/46703){:target="_blank"}  from **@cjh1**: fix retry logic for triton client `heterogeneous` created: 2024-11-14 19:49:43 merged: 2024-11-21 08:36:30

104. [46700](http://github.com/cms-sw/cmssw/pull/46700){:target="_blank"}  from **@felicepantaleo**: Improve TICL Association Map and update TICL event content `dqm` `reconstruction` `simulation` `upgrade` `hgcal` created: 2024-11-14 14:32:11 merged: 2024-12-07 06:18:14

105. [46694](http://github.com/cms-sw/cmssw/pull/46694){:target="_blank"}  from **@AdrianoDee**: Allowing Cluster Splitting with HLT Vertices `dqm` `operations` `reconstruction` `pdmv` `upgrade` `tracking` created: 2024-11-13 16:00:06 merged: 2024-12-06 12:54:51

106. [46683](http://github.com/cms-sw/cmssw/pull/46683){:target="_blank"}  from **@fabiocos**: MTD geometry: update MTDGeometry test, use only DD4hep backend, add ETL pixel position test `geometry` `upgrade` created: 2024-11-12 17:17:32 merged: 2024-11-21 08:36:18

107. [46678](http://github.com/cms-sw/cmssw/pull/46678){:target="_blank"}  from **@AuroraPerego**: Add time to HGCAL CaloParticles `reconstruction` `simulation` `upgrade` created: 2024-11-12 13:14:38 merged: 2024-12-02 10:24:54

108. [46655](http://github.com/cms-sw/cmssw/pull/46655){:target="_blank"}  from **@valsdav**: Moved Egamma TensorFlow sessions to global cache `reconstruction` `ml` created: 2024-11-11 12:05:09 merged: 2024-11-24 09:37:48

109. [46649](http://github.com/cms-sw/cmssw/pull/46649){:target="_blank"}  from **@AdrianoDee**: Rename 2021 Wfs with 2022 `pdmv` `upgrade` created: 2024-11-11 09:28:43 merged: 2024-11-24 09:32:22

110. [46617](http://github.com/cms-sw/cmssw/pull/46617){:target="_blank"}  from **@rohitcms**: Add caloParams v0_1 for 2024 HI run `l1` created: 2024-11-06 17:36:47 merged: 2024-11-26 14:31:19

111. [46593](http://github.com/cms-sw/cmssw/pull/46593){:target="_blank"}  from **@rohitcms**: Add caloParams v0_0 for 2024 HI run `l1` created: 2024-11-03 18:45:19 merged: 2024-11-22 12:32:14

112. [46539](http://github.com/cms-sw/cmssw/pull/46539){:target="_blank"}  from **@waredjeb**: TICLv5a : Improve skeleton linking and parameters tuning `hlt` `reconstruction` `upgrade` created: 2024-10-29 11:43:20 merged: 2024-11-23 15:22:05

113. [46402](http://github.com/cms-sw/cmssw/pull/46402){:target="_blank"}  from **@iarspider**: [LLVM Analyzer][Generators] Cleanup LLVM analyzer warnings `generators` created: 2024-10-16 11:17:15 merged: 2024-11-27 19:06:35

114. [46260](http://github.com/cms-sw/cmssw/pull/46260){:target="_blank"}  from **@iarspider**: [LLVM Analyzer][Gen] Cleanup dead assignments reported by llvm analyzer `generators` created: 2024-10-04 13:02:24 merged: 2024-11-27 19:07:21

115. [45640](http://github.com/cms-sw/cmssw/pull/45640){:target="_blank"}  from **@IzaakWN**: VarParsing: prevent TypeError for default of int/float/bool list `core` created: 2024-08-05 16:05:31 merged: 2024-12-03 10:16:42

116. [45483](http://github.com/cms-sw/cmssw/pull/45483){:target="_blank"}  from **@richardkasongo2003**: Choose data to display for the Tracer Log Viewer `core` created: 2024-07-17 15:04:16 merged: 2024-11-23 15:20:54

#### CMSDIST Changes between Tags REL/CMSSW_14_2_0_pre4/el8_amd64_gcc12 and REL/CMSSW_15_0_0_pre1/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_2_0_pre4/el8_amd64_gcc12...REL/CMSSW_15_0_0_pre1/el8_amd64_gcc12)



1. [9577](http://github.com/cms-sw/cmsdist/pull/9577){:target="_blank"}  from **@cms-sw**: Revert build rules: python import fix, prefer generated cfipython files created: 2024-12-13 12:53:27 merged: 2024-12-13 13:03:11

2. [9574](http://github.com/cms-sw/cmsdist/pull/9574){:target="_blank"}  from **@cms-sw**: patch release build fix: use realpath for import python module created: 2024-12-12 09:47:45 merged: 2024-12-12 15:41:44

3. [9571](http://github.com/cms-sw/cmsdist/pull/9571){:target="_blank"}  from **@cms-sw**: Generate compile rules for addtional microarch for alpaka serial backend created: 2024-12-12 07:43:22 merged: 2024-12-12 09:03:43

4. [9570](http://github.com/cms-sw/cmsdist/pull/9570){:target="_blank"}  from **@belforte**: bump crab-dev to v3.241211 created: 2024-12-11 17:33:57 merged: 2024-12-12 08:47:06

5. [9568](http://github.com/cms-sw/cmsdist/pull/9568){:target="_blank"}  from **@cms-sw**: [BuildRule] Copy rootmap to lib product store created: 2024-12-11 14:58:41 merged: 2024-12-11 21:58:51

6. [9566](http://github.com/cms-sw/cmsdist/pull/9566){:target="_blank"}  from **@cms-sw**: BuildRule: Use correct dev.cc.o for alpaka/serial backend created: 2024-12-11 08:11:34 merged: 2024-12-11 09:58:17

7. [9564](http://github.com/cms-sw/cmsdist/pull/9564){:target="_blank"}  from **@cms-sw**: Move to x86-64-v3 microarch created: 2024-12-10 18:47:47 merged: 2024-12-11 07:04:39

8. [9563](http://github.com/cms-sw/cmsdist/pull/9563){:target="_blank"}  from **@fwyzard**: Update NVIDIA gdrcopy to v2.4.3 created: 2024-12-10 08:38:00 merged: 2024-12-11 09:58:51

9. [9561](http://github.com/cms-sw/cmsdist/pull/9561){:target="_blank"}  from **@gartung**: Add GPROFNF_SYSCONFDIR to gcc-cxxcompiler toolfile on AL9 and above created: 2024-12-09 15:47:39 merged: 2024-12-10 10:06:31

10. [9554](http://github.com/cms-sw/cmsdist/pull/9554){:target="_blank"}  from **@cms-sw**: cms-common: Deploy scram site hook for setting LC_ALL env created: 2024-12-05 13:07:07 merged: 2024-12-06 12:57:19

11. [9550](http://github.com/cms-sw/cmsdist/pull/9550){:target="_blank"}  from **@cms-sw**: XRootd: version 5.7.2 created: 2024-12-04 19:03:58 merged: 2024-12-05 07:02:47

12. [9549](http://github.com/cms-sw/cmsdist/pull/9549){:target="_blank"}  from **@cms-sw**: backport of edm class version changes created: 2024-12-04 18:14:50 merged: 2024-12-04 20:01:01

13. [9540](http://github.com/cms-sw/cmsdist/pull/9540){:target="_blank"}  from **@cms-sw**: update cms-tfaot: added revision in toolfiles created: 2024-11-27 16:35:30 merged: 2024-11-27 20:57:07

14. [9539](http://github.com/cms-sw/cmsdist/pull/9539){:target="_blank"}  from **@cms-sw**: security fixes: update aiohttp and tornado created: 2024-11-27 15:49:27 merged: 2024-11-27 20:58:33

15. [9538](http://github.com/cms-sw/cmsdist/pull/9538){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-16-00 created: 2024-11-27 15:41:06 merged: 2024-11-27 15:41:08

16. [9537](http://github.com/cms-sw/cmsdist/pull/9537){:target="_blank"}  from **@cms-sw**: [BuildRules]Make each per-Alpaka-backend library to depend on the main library created: 2024-11-27 07:19:41 merged: 2024-11-27 16:56:16

17. [9536](http://github.com/cms-sw/cmsdist/pull/9536){:target="_blank"}  from **@cms-sw**: SCRAM: Update scram tool info to show tool revision created: 2024-11-26 15:05:58 merged: 2024-11-26 22:09:04

18. [9535](http://github.com/cms-sw/cmsdist/pull/9535){:target="_blank"}  from **@belforte**: bump client v3.241125 to prod created: 2024-11-26 14:26:40 merged: 2024-11-26 22:08:50

19. [9534](http://github.com/cms-sw/cmsdist/pull/9534){:target="_blank"}  from **@cms-sw**: Added revision number for toolfiles created: 2024-11-25 22:36:48 merged: 2024-11-26 08:10:12

20. [9533](http://github.com/cms-sw/cmsdist/pull/9533){:target="_blank"}  from **@cms-sw**: Enable as needed flag created: 2024-11-25 22:19:18 merged: 2024-11-26 07:38:11

21. [9531](http://github.com/cms-sw/cmsdist/pull/9531){:target="_blank"}  from **@belforte**: bump CRAB client and server version to v3.241125 created: 2024-11-25 16:21:30 merged: 2024-11-25 20:59:43

22. [9528](http://github.com/cms-sw/cmsdist/pull/9528){:target="_blank"}  from **@cms-sw**: Update tag for Configuration-Generator to V01-10-00 created: 2024-11-22 16:04:23 merged: 2024-11-22 16:04:25

23. [9527](http://github.com/cms-sw/cmsdist/pull/9527){:target="_blank"}  from **@clelange**: Update hepdata-lib to v0.17.0 created: 2024-11-22 10:34:35 merged: 2024-11-25 09:32:53

24. [9526](http://github.com/cms-sw/cmsdist/pull/9526){:target="_blank"}  from **@cms-sw**: [Buildrules] Avoid duplicate compilation messages for BUILD_LOG=yes created: 2024-11-21 17:05:34 merged: 2024-11-22 07:14:51

25. [9525](http://github.com/cms-sw/cmsdist/pull/9525){:target="_blank"}  from **@belforte**: crab-dev -> prod, bump crab-dev to 241121 (py3.12) created: 2024-11-21 16:25:49 merged: 2024-11-21 20:38:14

26. [9524](http://github.com/cms-sw/cmsdist/pull/9524){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-15-00 created: 2024-11-21 08:35:57 merged: 2024-11-21 08:35:58
