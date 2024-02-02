---
layout: post
rel_link:  "14_0_0_pre3"
title:  "CMSSW_14_0_0_pre3"
date:   2024-02-01 16:06:31
categories: cmssw
relmajor: 14
relminor: 0
relsubminor: 0
relpre: _pre3
---

# CMSSW_14_0_0_pre3
#### Changes since CMSSW_14_0_0_pre2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_0_0_pre2...CMSSW_14_0_0_pre3)



1. [43820](http://github.com/cms-sw/cmssw/pull/43820){:target="_blank"}  from **@fwyzard**: Fix loop in vertexFinder::splitVertices(acc, ...) `reconstruction` `tracking` created: 2024-01-31 07:36:57 merged: 2024-01-31 14:27:53

2. [43819](http://github.com/cms-sw/cmssw/pull/43819){:target="_blank"}  from **@mmusich**: `EgammaHLTHcalVarProducerFromRecHit`: fix `HcalPFCuts` consumes pattern `hlt` `egamma` created: 2024-01-31 04:33:22 merged: 2024-01-31 14:27:47

3. [43817](http://github.com/cms-sw/cmssw/pull/43817){:target="_blank"}  from **@wddgit**: Delete last simulation legacy type module `simulation` created: 2024-01-30 22:27:19 merged: 2024-01-31 14:28:42

4. [43811](http://github.com/cms-sw/cmssw/pull/43811){:target="_blank"}  from **@ericcano**: Ensures that warp level primitives are called from full warps in prefixScan. `heterogeneous` created: 2024-01-30 11:10:48 merged: 2024-01-30 15:37:51

5. [43808](http://github.com/cms-sw/cmssw/pull/43808){:target="_blank"}  from **@youyingli**: Update skim configs for full ReReco 2022/2023 `pdmv` created: 2024-01-29 18:03:08 merged: 2024-01-30 15:38:30

6. [43804](http://github.com/cms-sw/cmssw/pull/43804){:target="_blank"}  from **@iarspider**: Remove uses of deprecated std::random_shuffle `core` `simulation` `heterogeneous` created: 2024-01-29 09:28:46 merged: 2024-01-30 15:38:43

7. [43794](http://github.com/cms-sw/cmssw/pull/43794){:target="_blank"}  from **@mmusich**: add necessary changes to run the uploads of the Combined High Granularity SiPixel alignment in the PCL `alca` `db` `trk` created: 2024-01-26 10:36:40 merged: 2024-01-30 14:49:48

8. [43792](http://github.com/cms-sw/cmssw/pull/43792){:target="_blank"}  from **@mmusich**: silence CPP20 warnings about `maybe-uninitialized` variables in `momentumBiasValidation.C` `alca` `trk` created: 2024-01-26 08:31:56 merged: 2024-01-30 15:49:11

9. [43788](http://github.com/cms-sw/cmssw/pull/43788){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_3_X` (1/N) [`14_0_X`] `hlt` created: 2024-01-25 18:34:31 merged: 2024-01-30 14:47:00

10. [43785](http://github.com/cms-sw/cmssw/pull/43785){:target="_blank"}  from **@hgc-tpg**: [HGCAL trigger] Update validation histograms `dqm` created: 2024-01-25 11:25:11 merged: 2024-01-30 15:40:56

11. [43782](http://github.com/cms-sw/cmssw/pull/43782){:target="_blank"}  from **@smuzaffar**: Revert back to chi-square fit instead of likelihood fit `dqm` created: 2024-01-24 21:48:53 merged: 2024-01-25 15:14:39

12. [43781](http://github.com/cms-sw/cmssw/pull/43781){:target="_blank"}  from **@cms-sw**: Revert "Use likelihood fit instead of chi-square fit in PVValidation" `alca` `trk` created: 2024-01-24 21:43:05 merged: 2024-01-25 15:14:54

13. [43779](http://github.com/cms-sw/cmssw/pull/43779){:target="_blank"}  from **@wddgit**: Disable the getFedsFromOmds configuration option in L1RCTProducer `l1` created: 2024-01-24 17:16:00 merged: 2024-01-30 15:41:08

14. [43778](http://github.com/cms-sw/cmssw/pull/43778){:target="_blank"}  from **@iarspider**: Replace C-style arrays with std::arrays (follow-up on #43771) `l1` `upgrade` created: 2024-01-24 13:08:13 merged: 2024-01-30 15:41:30

15. [43776](http://github.com/cms-sw/cmssw/pull/43776){:target="_blank"}  from **@iarspider**: Split testConfigDP into smaller parts `operations` created: 2024-01-23 15:29:03 merged: 2024-01-25 15:19:37

16. [43774](http://github.com/cms-sw/cmssw/pull/43774){:target="_blank"}  from **@Sam-Harper**: Added signed GSF track variable collections to the HLT producer: 14_0 `hlt` created: 2024-01-23 13:55:00 merged: 2024-01-25 15:15:46

17. [43773](http://github.com/cms-sw/cmssw/pull/43773){:target="_blank"}  from **@iarspider**: Fix compilation errro in Alignment/OfflineValidation/test/testTrackAnalyzers.cc `alca` `trk` created: 2024-01-23 13:46:56 merged: 2024-01-25 15:16:04

18. [43771](http://github.com/cms-sw/cmssw/pull/43771){:target="_blank"}  from **@iarspider**: Fix deprecated-copy warnings in L1CaloTrigger `l1` `upgrade` created: 2024-01-23 09:04:47 merged: 2024-01-23 15:21:17

19. [43770](http://github.com/cms-sw/cmssw/pull/43770){:target="_blank"}  from **@iarspider**: Fix usage of deprecated RooDataSet constructors `analysis` created: 2024-01-23 08:37:52 merged: 2024-01-25 15:16:54

20. [43763](http://github.com/cms-sw/cmssw/pull/43763){:target="_blank"}  from **@saumyaphor4252**: Update 140X Run3 data and MC GTs `alca` created: 2024-01-22 10:15:51 merged: 2024-01-23 15:21:02

21. [43760](http://github.com/cms-sw/cmssw/pull/43760){:target="_blank"}  from **@bsunanda**: Phase2-hgx352 Modify the scenarios D104, D105 to accommodate modified T35 and I17 (also go back to C17 for D105). Add a new scenario D106 with C23 (same as C22 but without cell definition in Geant4) `geometry` `operations` `pdmv` `upgrade` created: 2024-01-20 04:58:47 merged: 2024-01-30 14:55:21

22. [43759](http://github.com/cms-sw/cmssw/pull/43759){:target="_blank"}  from **@Dr15Jones**: Changed to constexpr in reco::Vertex `reconstruction` `tracking` created: 2024-01-19 18:50:35 merged: 2024-01-22 15:43:52

23. [43758](http://github.com/cms-sw/cmssw/pull/43758){:target="_blank"}  from **@mmasciov**: Add non-diagonal errors to scouting vertices `core` `hlt` created: 2024-01-19 17:45:30 merged: 2024-01-30 14:47:58

24. [43757](http://github.com/cms-sw/cmssw/pull/43757){:target="_blank"}  from **@mmusich**: Introduce `AlignmentTracksFromVertexCompositeCandidate` and new alca flavour `TkAlV0s` `alca` `dqm` `operations` `trk` created: 2024-01-19 16:36:28 merged: 2024-01-25 15:19:50

25. [43754](http://github.com/cms-sw/cmssw/pull/43754){:target="_blank"}  from **@mmusich**: fix `test_payload_sanity` unit test script `alca` `trk` created: 2024-01-19 13:59:28 merged: 2024-01-22 15:43:25

26. [43753](http://github.com/cms-sw/cmssw/pull/43753){:target="_blank"}  from **@vlimant**: simplify MU-DPG custom nano configuration `operations` `xpog` created: 2024-01-19 11:46:35 merged: 2024-01-25 15:19:55

27. [43752](http://github.com/cms-sw/cmssw/pull/43752){:target="_blank"}  from **@smuzaffar**: Fix warnings which are ignored by bot `alca` `dqm` `trk` created: 2024-01-19 10:51:06 merged: 2024-01-23 15:20:36

28. [43750](http://github.com/cms-sw/cmssw/pull/43750){:target="_blank"}  from **@Dr15Jones**: Fixed UBSAN warning in FieldHandler `l1` created: 2024-01-18 22:22:53 merged: 2024-01-22 15:43:02

29. [43749](http://github.com/cms-sw/cmssw/pull/43749){:target="_blank"}  from **@Dr15Jones**: Properly setup meta data in LHESource `generators` created: 2024-01-18 20:23:21 merged: 2024-01-23 15:17:52

30. [43747](http://github.com/cms-sw/cmssw/pull/43747){:target="_blank"}  from **@Dr15Jones**: Handle empty branch index lists from input `core` created: 2024-01-18 15:42:27 merged: 2024-01-19 16:45:44

31. [43746](http://github.com/cms-sw/cmssw/pull/43746){:target="_blank"}  from **@pallabidas**: [Phase-2 L1T] calibrated GCT calo jets and taus `l1` `upgrade` created: 2024-01-18 15:29:12 merged: 2024-01-22 15:42:56

32. [43745](http://github.com/cms-sw/cmssw/pull/43745){:target="_blank"}  from **@cms-trackeralign**: `ReferenceTrajectory`: decrease the value of the minumum precision to allow along-strip alignment of Phase2 2S modules  `alca` `trk` created: 2024-01-18 15:05:05 merged: 2024-01-19 16:45:32

33. [43744](http://github.com/cms-sw/cmssw/pull/43744){:target="_blank"}  from **@arsahasransu**: Electron and Photon Scouting Data Format Update for 2024 pp Collisions `core` `hlt` created: 2024-01-18 14:02:10 merged: 2024-01-19 16:44:22

34. [43741](http://github.com/cms-sw/cmssw/pull/43741){:target="_blank"}  from **@rdelliga**: MTD Validation: addition of plots for the impact of MTD on Pt resolution  `dqm` created: 2024-01-18 11:02:51 merged: 2024-01-25 15:17:37

35. [43738](http://github.com/cms-sw/cmssw/pull/43738){:target="_blank"}  from **@SohamBhattacharya**: [14_0_X] [Phase-2] Change Phase-2 HLT muon paths to use the L1 GT emulator `hlt` created: 2024-01-17 19:33:33 merged: 2024-01-23 15:17:23

36. [43737](http://github.com/cms-sw/cmssw/pull/43737){:target="_blank"}  from **@cgsavard**: Update displaced track jet cuts in GTT `l1` `upgrade` created: 2024-01-17 19:32:00 merged: 2024-01-25 15:18:07

37. [43736](http://github.com/cms-sw/cmssw/pull/43736){:target="_blank"}  from **@srimanob**: Update Patatrack wf in relval_2026 `pdmv` `upgrade` created: 2024-01-17 17:46:06 merged: 2024-01-22 15:41:50

38. [43734](http://github.com/cms-sw/cmssw/pull/43734){:target="_blank"}  from **@vlimant**: remove support for int8 branches in NANO `xpog` created: 2024-01-17 17:12:08 merged: 2024-01-25 15:18:35

39. [43732](http://github.com/cms-sw/cmssw/pull/43732){:target="_blank"}  from **@fabiocos**: MTD reconstruction: fix BTL time for missing correction in BTL geometry v3 (scenario I17) `reconstruction` `upgrade` `mtd` created: 2024-01-17 13:55:49 merged: 2024-01-22 15:41:36

40. [43731](http://github.com/cms-sw/cmssw/pull/43731){:target="_blank"}  from **@silviodonato**: Add fillDescription to CommonTools/UtilAlgos/interface/Merger.h - 140X `reconstruction` created: 2024-01-17 13:24:13 merged: 2024-01-19 16:41:40

41. [43729](http://github.com/cms-sw/cmssw/pull/43729){:target="_blank"}  from **@mmusich**: Adapt shortened tracks resolution method to work with AlCaReco event content `alca` `dqm` `reconstruction` `tracking` `trk` created: 2024-01-17 11:24:12 merged: 2024-01-19 16:39:43

42. [43727](http://github.com/cms-sw/cmssw/pull/43727){:target="_blank"}  from **@bsunanda**: hgx-TB77A Commit changes made by Ashim for 2023 August/Septemeber Test Beam `geometry` `simulation` `upgrade` created: 2024-01-17 04:30:54 merged: 2024-01-22 15:40:47

43. [43726](http://github.com/cms-sw/cmssw/pull/43726){:target="_blank"}  from **@makortel**: Make Minuit2 error on non-posdef initial matrix an error message instead of an exception `core` `reconstruction` `pdmv` created: 2024-01-16 23:09:12 merged: 2024-01-22 15:39:55

44. [43725](http://github.com/cms-sw/cmssw/pull/43725){:target="_blank"}  from **@dan131riley**: Fix some MkFit valgrind warnings, improve loop vectorization `reconstruction` `tracking` created: 2024-01-16 22:01:11 merged: 2024-01-17 14:28:16

45. [43724](http://github.com/cms-sw/cmssw/pull/43724){:target="_blank"}  from **@Dr15Jones**: DQMStore avoids using 0 as invalid module ID `dqm` created: 2024-01-16 21:21:58 merged: 2024-01-19 16:35:45

46. [43721](http://github.com/cms-sw/cmssw/pull/43721){:target="_blank"}  from **@cms-trackeralign**: Introduce High Granularity Tracker Alignment Prompt Calibration Loop with Z   data `alca` `operations` `pdmv` `upgrade` `trk` created: 2024-01-16 17:15:45 merged: 2024-01-25 15:20:12

47. [43720](http://github.com/cms-sw/cmssw/pull/43720){:target="_blank"}  from **@slava77**: add OT tracker cluster masks in TrackingNtuple `dqm` `tracking` created: 2024-01-16 15:13:48 merged: 2024-01-19 16:31:50

48. [43719](http://github.com/cms-sw/cmssw/pull/43719){:target="_blank"}  from **@smuzaffar**: Unit tests to check SCRAM test command works `core` created: 2024-01-16 15:05:50 merged: 2024-01-19 16:31:38

49. [43718](http://github.com/cms-sw/cmssw/pull/43718){:target="_blank"}  from **@bsunanda**: Phase2-hgx350C Steps to create a scenario of B18 Geometry of HGCal where no innecr cell straucture of full wafers are not created atin Geant4 geometry `geometry` `upgrade` created: 2024-01-16 12:58:15 merged: 2024-01-19 16:30:55

50. [43717](http://github.com/cms-sw/cmssw/pull/43717){:target="_blank"}  from **@bsunanda**: Phase2-hgx351 Modify to analyze flat files contatining only full silisonlayers of EE and HE (usefule for HFNose) `geometry` `upgrade` created: 2024-01-16 09:43:20 merged: 2024-01-19 16:30:30

51. [43716](http://github.com/cms-sw/cmssw/pull/43716){:target="_blank"}  from **@mmusich**: Update `testTrackAnalyzers`  `alca` `trk` created: 2024-01-15 17:49:23 merged: 2024-01-19 16:30:05

52. [43715](http://github.com/cms-sw/cmssw/pull/43715){:target="_blank"}  from **@vlimant**: remove nano specific setting for IMT `operations` created: 2024-01-15 11:16:47 merged: 2024-01-25 15:20:21

53. [43714](http://github.com/cms-sw/cmssw/pull/43714){:target="_blank"}  from **@swagata87**: Remove unused code to alleviate maintenance burden `reconstruction` `egamma` `pf` created: 2024-01-15 11:14:20 merged: 2024-01-16 14:39:04

54. [43709](http://github.com/cms-sw/cmssw/pull/43709){:target="_blank"}  from **@mmusich**: `ALCARECOTkAlDQM`: improve `DiMuonVertexMonitor` titles `dqm` created: 2024-01-12 19:43:52 merged: 2024-01-15 16:02:14

55. [43708](http://github.com/cms-sw/cmssw/pull/43708){:target="_blank"}  from **@cms-trackeralign**: Implementation of the Muon Track Splitting (MTS) Validation in the new TkAl all-in-one tool `alca` `trk` created: 2024-01-12 19:37:38 merged: 2024-01-15 16:02:00

56. [43707](http://github.com/cms-sw/cmssw/pull/43707){:target="_blank"}  from **@SohamBhattacharya**: [14_0_X] [Phase-2] Enable support for P2GTCandidates in HLT `hlt` created: 2024-01-12 14:47:06 merged: 2024-01-16 14:44:07

57. [43705](http://github.com/cms-sw/cmssw/pull/43705){:target="_blank"}  from **@gpetruc**: L1T Correlator support for TMUX 18 in the barrel `l1` `upgrade` created: 2024-01-12 13:50:40 merged: 2024-01-22 15:39:11

58. [43704](http://github.com/cms-sw/cmssw/pull/43704){:target="_blank"}  from **@hgc-tpg**: [HGCAL trigger] Update in geometry tester class `l1` `upgrade` created: 2024-01-12 12:32:51 merged: 2024-01-22 15:26:48

59. [43702](http://github.com/cms-sw/cmssw/pull/43702){:target="_blank"}  from **@Dr15Jones**: Better dependency checking on Paths `core` created: 2024-01-11 19:16:24 merged: 2024-01-12 16:38:23

60. [43700](http://github.com/cms-sw/cmssw/pull/43700){:target="_blank"}  from **@hgc-tpg**: [HGCAL trigger] Fix hgcalTrigPrimValidation config name `dqm` created: 2024-01-11 14:27:52 merged: 2024-01-15 15:59:06

61. [43698](http://github.com/cms-sw/cmssw/pull/43698){:target="_blank"}  from **@bsunanda**: Phas2-HGX350B Attempt to make a flat silicon file for HGNose descriptiopn - first step to make the next version of HFNose `geometry` `upgrade` created: 2024-01-11 04:49:55 merged: 2024-01-15 15:58:45

62. [43696](http://github.com/cms-sw/cmssw/pull/43696){:target="_blank"}  from **@kpedro88**: Triton model versioning `heterogeneous` created: 2024-01-10 22:32:45 merged: 2024-01-30 15:42:46

63. [43694](http://github.com/cms-sw/cmssw/pull/43694){:target="_blank"}  from **@Dr15Jones**: Use std types for SFINAE usage in cms::Exception `core` created: 2024-01-10 19:41:14 merged: 2024-01-12 16:34:18

64. [43693](http://github.com/cms-sw/cmssw/pull/43693){:target="_blank"}  from **@Dr15Jones**: Avoid making voxels in TGeoManager `geometry` created: 2024-01-10 15:51:08 merged: 2024-01-12 16:33:52

65. [43689](http://github.com/cms-sw/cmssw/pull/43689){:target="_blank"}  from **@mmusich**: Introduce wf 7.5 (phase-2 cosmics D98) and necessary mods to make it run `dqm` `operations` `reconstruction` `simulation` `pdmv` `upgrade` `tracking` `trk` created: 2024-01-10 11:53:50 merged: 2024-01-25 15:20:47

66. [43686](http://github.com/cms-sw/cmssw/pull/43686){:target="_blank"}  from **@aloeliger**: Remove hackConditions as was done in L1T Offline fork `l1` created: 2024-01-09 21:30:55 merged: 2024-01-22 15:25:10

67. [43685](http://github.com/cms-sw/cmssw/pull/43685){:target="_blank"}  from **@Dr15Jones**: Explicit default methods for SDSRawDataCollection `daq` created: 2024-01-09 19:40:42 merged: 2024-01-12 16:32:52

68. [43684](http://github.com/cms-sw/cmssw/pull/43684){:target="_blank"}  from **@Dr15Jones**: Fixed copy constructor name in bqueue_itr `reconstruction` `tracking` created: 2024-01-09 19:21:54 merged: 2024-01-12 16:32:37

69. [43683](http://github.com/cms-sw/cmssw/pull/43683){:target="_blank"}  from **@Dr15Jones**: Exclude EndPathStatus when only 1 EndPath exists `core` created: 2024-01-09 17:58:22 merged: 2024-01-12 16:32:17

70. [43682](http://github.com/cms-sw/cmssw/pull/43682){:target="_blank"}  from **@makortel**: Example of Alpaka-based EventSetup data product that uses PortableCollection member variables `heterogeneous` created: 2024-01-09 17:23:58 merged: 2024-01-19 16:28:40

71. [43681](http://github.com/cms-sw/cmssw/pull/43681){:target="_blank"}  from **@swagata87**: Use HCAL noise cuts from DB only for Run3 and Phase2 `hlt` `reconstruction` `pf` created: 2024-01-09 17:18:06 merged: 2024-01-10 15:35:07

72. [43680](http://github.com/cms-sw/cmssw/pull/43680){:target="_blank"}  from **@CMSTrackerDPG**: Add more table producers to SiStrip AlCaNano `alca` `trk` created: 2024-01-09 13:23:01 merged: 2024-01-12 16:27:22

73. [43679](http://github.com/cms-sw/cmssw/pull/43679){:target="_blank"}  from **@missirol**: silence static-analyzer warnings in `HLTConfig{Data,Provider}` `hlt` created: 2024-01-08 23:01:15 merged: 2024-01-12 16:26:49

74. [43678](http://github.com/cms-sw/cmssw/pull/43678){:target="_blank"}  from **@gartung**: Utilities/StaticAnalyzer: Honor use of CMS_SA_ALLOW for ParameterSet::existsAs checker `core` created: 2024-01-08 17:19:40 merged: 2024-01-12 16:25:48

75. [43675](http://github.com/cms-sw/cmssw/pull/43675){:target="_blank"}  from **@iarspider-cmssw**: Always define stack variable in edm-global-class.py `core` created: 2024-01-08 09:05:52 merged: 2024-01-12 16:25:32

76. [43672](http://github.com/cms-sw/cmssw/pull/43672){:target="_blank"}  from **@civanch**: [14_0_X: SIM] Fixed compilation in debug mode `simulation` created: 2024-01-05 18:02:26 merged: 2024-01-12 16:25:17

77. [43671](http://github.com/cms-sw/cmssw/pull/43671){:target="_blank"}  from **@Dr15Jones**: Removed beginRun/endRun methods in TrackTriggerAssociation modules `l1` `simulation` `trk` created: 2024-01-05 16:15:52 merged: 2024-01-12 16:24:12

78. [43670](http://github.com/cms-sw/cmssw/pull/43670){:target="_blank"}  from **@Dr15Jones**: Removed empty beginRun from PFCandidateChecker `reconstruction` created: 2024-01-05 16:05:47 merged: 2024-01-12 16:24:06

79. [43669](http://github.com/cms-sw/cmssw/pull/43669){:target="_blank"}  from **@Dr15Jones**: Removed beginRun methods in  RecoLocalCalo `reconstruction` `upgrade` created: 2024-01-05 15:50:57 merged: 2024-01-12 16:15:24

80. [43668](http://github.com/cms-sw/cmssw/pull/43668){:target="_blank"}  from **@Dr15Jones**: Removed beginRun from FixedGridRhoProducerFastjetFromRecHit `reconstruction` created: 2024-01-05 15:24:06 merged: 2024-01-12 16:13:45

81. [43667](http://github.com/cms-sw/cmssw/pull/43667){:target="_blank"}  from **@Dr15Jones**: Removed beginRun use in EgammaPhotonProducers modules `reconstruction` created: 2024-01-05 15:14:34 merged: 2024-01-12 16:13:22

82. [43665](http://github.com/cms-sw/cmssw/pull/43665){:target="_blank"}  from **@Dr15Jones**: Remove beginRun/beginLuminosityBlock methods in EGammaElectronProducers `l1` `reconstruction` `upgrade` created: 2024-01-05 14:55:20 merged: 2024-01-19 16:26:25

83. [43663](http://github.com/cms-sw/cmssw/pull/43663){:target="_blank"}  from **@mmusich**: SiStrip Condition tools: add more APV gain inspection tools `db` `trk` created: 2024-01-05 12:28:36 merged: 2024-01-12 16:13:06

84. [43662](http://github.com/cms-sw/cmssw/pull/43662){:target="_blank"}  from **@mmusich**: Improve `SiPixelQualityProbabilities_PayloadInspector` `db` `trk` created: 2024-01-05 12:19:56 merged: 2024-01-12 16:12:24

85. [43661](http://github.com/cms-sw/cmssw/pull/43661){:target="_blank"}  from **@bsunanda**: Phase2-HGX350A Resolve the scenario for V18 version of HGCal Geometry `geometry` `operations` `simulation` `pdmv` `upgrade` created: 2024-01-05 04:55:22 merged: 2024-01-16 14:57:03

86. [43659](http://github.com/cms-sw/cmssw/pull/43659){:target="_blank"}  from **@Dr15Jones**: Removed empty beginRun from FastTSGFromL2Muon `fastsim` created: 2024-01-04 21:44:29 merged: 2024-01-12 16:12:03

87. [43658](http://github.com/cms-sw/cmssw/pull/43658){:target="_blank"}  from **@Dr15Jones**: Cleanup Run/LuminosityBlock methods in EventFilter `l1` `reconstruction` `trk` created: 2024-01-04 21:30:30 merged: 2024-01-12 16:09:07

88. [43657](http://github.com/cms-sw/cmssw/pull/43657){:target="_blank"}  from **@Dr15Jones**: Removed empty beginRun in DPGAnalysis/HcalNanoAOD modules `xpog` `hcal` created: 2024-01-04 21:10:45 merged: 2024-01-12 16:00:20

89. [43656](http://github.com/cms-sw/cmssw/pull/43656){:target="_blank"}  from **@Dr15Jones**: Removed begin/endRun method from AlCaHBHEMuonProducer `alca` created: 2024-01-04 21:02:24 merged: 2024-01-12 16:00:05

90. [43655](http://github.com/cms-sw/cmssw/pull/43655){:target="_blank"}  from **@Dr15Jones**: Changed StubAssociator to a global module `l1` `simulation` `trk` created: 2024-01-04 17:16:25 merged: 2024-01-12 15:59:31

91. [43653](http://github.com/cms-sw/cmssw/pull/43653){:target="_blank"}  from **@Dr15Jones**: Moved to global modules in SimMuon `simulation` `upgrade` created: 2024-01-04 16:26:45 merged: 2024-01-22 15:24:53

92. [43651](http://github.com/cms-sw/cmssw/pull/43651){:target="_blank"}  from **@Dr15Jones**: Made modules global in RecoEcal/EgammaClusterProducers `reconstruction` created: 2024-01-03 19:48:08 merged: 2024-01-12 15:59:07

93. [43650](http://github.com/cms-sw/cmssw/pull/43650){:target="_blank"}  from **@mmusich**: Fix `TkAlStyle` includes and add unit tests `alca` `trk` created: 2024-01-03 14:42:13 merged: 2024-01-12 15:58:55

94. [43649](http://github.com/cms-sw/cmssw/pull/43649){:target="_blank"}  from **@Dr15Jones**: Change to global module in L1Trigger/L1TGEM `l1` created: 2024-01-03 13:56:28 merged: 2024-01-12 15:48:04

95. [43648](http://github.com/cms-sw/cmssw/pull/43648){:target="_blank"}  from **@makortel**: Clean up some unnecessary {begin,end}{Run,LuminosityBlock} transition functions `alca` `analysis` `daq` `dqm` `hlt` `l1` `reconstruction` `simulation` `xpog` `trk` created: 2024-01-02 21:41:55 merged: 2024-01-15 15:58:24

96. [43647](http://github.com/cms-sw/cmssw/pull/43647){:target="_blank"}  from **@Dr15Jones**: Modernize Phase2TrackerDigiProducer `daq` `reconstruction` `trk` created: 2024-01-02 16:26:01 merged: 2024-01-12 15:37:07

97. [43645](http://github.com/cms-sw/cmssw/pull/43645){:target="_blank"}  from **@missirol**: use `HIDQM*` streams in online-DQM clients if `runType==hi_run` `dqm` created: 2024-01-02 11:37:40 merged: 2024-01-30 15:43:00

98. [43644](http://github.com/cms-sw/cmssw/pull/43644){:target="_blank"}  from **@missirol**: make `hltFindDuplicates` work again `hlt` created: 2024-01-02 11:26:32 merged: 2024-01-12 15:36:33

99. [43643](http://github.com/cms-sw/cmssw/pull/43643){:target="_blank"}  from **@missirol**: use `reco::deltaR2` in `HLTrigger/*/` packages `hlt` created: 2024-01-02 11:16:54 merged: 2024-01-12 15:35:26

100. [43641](http://github.com/cms-sw/cmssw/pull/43641){:target="_blank"}  from **@CTPPS**: CTPPS create Reconstruction workflow test `reconstruction` created: 2023-12-28 13:23:13 merged: 2024-01-12 15:31:07

101. [43640](http://github.com/cms-sw/cmssw/pull/43640){:target="_blank"}  from **@civanch**: [14_0_X SIM] Updated low-energy GFlash method in ECAL `simulation` created: 2023-12-27 08:51:11 merged: 2024-01-12 15:27:29

102. [43639](http://github.com/cms-sw/cmssw/pull/43639){:target="_blank"}  from **@Duchstf**: Add update for Tau NN with pT calibration `l1` `upgrade` created: 2023-12-23 04:57:44 merged: 2024-01-22 15:23:39

103. [43637](http://github.com/cms-sw/cmssw/pull/43637){:target="_blank"}  from **@Dr15Jones**: Start work for stream modules to explicitly request Run/Lumis `core` created: 2023-12-22 19:25:28 merged: 2024-01-12 15:26:53

104. [43635](http://github.com/cms-sw/cmssw/pull/43635){:target="_blank"}  from **@srimanob**: Add Phase-2 workflow with Phase-2 ECal TP, also with ECal component  `pdmv` `upgrade` created: 2023-12-22 17:39:06 merged: 2024-01-17 14:28:40

105. [43632](http://github.com/cms-sw/cmssw/pull/43632){:target="_blank"}  from **@fwyzard**: Improve uniform_groups-related functions `heterogeneous` created: 2023-12-21 23:19:53 merged: 2024-01-12 15:19:46

106. [43631](http://github.com/cms-sw/cmssw/pull/43631){:target="_blank"}  from **@brallmond**: Added new filter type HLT2MuonPFJet to plugins for ETau Pnet HLT path `hlt` created: 2023-12-21 18:10:27 merged: 2024-01-12 15:18:23

107. [43629](http://github.com/cms-sw/cmssw/pull/43629){:target="_blank"}  from **@Dr15Jones**: Check that lumiSectionInterval_ is valid in StreamerOutputModuleCommon `core` created: 2023-12-21 15:50:08 merged: 2024-01-12 15:18:47

108. [43627](http://github.com/cms-sw/cmssw/pull/43627){:target="_blank"}  from **@jaimeleonh**: Added new Triple Jet and Muon + Double Jet Ov.Rm. filters to be used in the TauPOG PNet transition `hlt` created: 2023-12-21 12:57:09 merged: 2024-01-08 18:38:12

109. [43626](http://github.com/cms-sw/cmssw/pull/43626){:target="_blank"}  from **@llunerti**: Fix invariant mass plot range in Muons DQM `dqm` created: 2023-12-21 10:53:37 merged: 2024-01-08 18:46:50

110. [43625](http://github.com/cms-sw/cmssw/pull/43625){:target="_blank"}  from **@fabiocos**: MTD digitization: test code to print and display BTL pulse shape `simulation` `upgrade` created: 2023-12-21 10:09:39 merged: 2024-01-08 19:02:21

111. [43622](http://github.com/cms-sw/cmssw/pull/43622){:target="_blank"}  from **@drkovalskyi**: Soft muon MVA id for run3 `reconstruction` `xpog` created: 2023-12-20 18:01:47 merged: 2024-01-23 15:15:37

112. [43616](http://github.com/cms-sw/cmssw/pull/43616){:target="_blank"}  from **@bsunanda**: Run3-Sim153H Cleanup in SimG4CMS/Tracker against using codes directly from DD4hep `simulation` created: 2023-12-20 12:23:23 merged: 2024-01-08 19:18:48

113. [43615](http://github.com/cms-sw/cmssw/pull/43615){:target="_blank"}  from **@aandvalenzuela**: [RECONSTRUCTION] Define missing copy constructir to fix warnings reported in DEVEL IBs `reconstruction` `tracking` created: 2023-12-20 11:01:19 merged: 2024-01-08 19:19:23

114. [43614](http://github.com/cms-sw/cmssw/pull/43614){:target="_blank"}  from **@aandvalenzuela**: [HETEROGENEOUS] Fix deprecated call to `hipMallocHost` in DEVEL IBs `heterogeneous` created: 2023-12-20 10:55:37 merged: 2024-01-08 19:25:43

115. [43613](http://github.com/cms-sw/cmssw/pull/43613){:target="_blank"}  from **@borzari**: Including short tracks resolution method in DQM `dqm` `reconstruction` `tracking` created: 2023-12-20 01:56:01 merged: 2024-01-12 14:59:20

116. [43612](http://github.com/cms-sw/cmssw/pull/43612){:target="_blank"}  from **@swagata87**: Calotower phase-out from PF code `hlt` `reconstruction` `pf` created: 2023-12-19 18:54:40 merged: 2024-01-08 19:27:26

117. [43611](http://github.com/cms-sw/cmssw/pull/43611){:target="_blank"}  from **@Dr15Jones**: Explicit default methods for MESet iterators `dqm` created: 2023-12-19 18:17:02 merged: 2024-01-08 19:29:04

118. [43610](http://github.com/cms-sw/cmssw/pull/43610){:target="_blank"}  from **@cgsavard**: Update L1 track jet cuts `l1` `upgrade` created: 2023-12-19 17:59:30 merged: 2024-01-19 16:24:31

119. [43609](http://github.com/cms-sw/cmssw/pull/43609){:target="_blank"}  from **@Dr15Jones**: Removed std::unexpected from DTGeometryParserFromDDD `alca` created: 2023-12-19 17:34:46 merged: 2024-01-08 19:29:28

120. [43606](http://github.com/cms-sw/cmssw/pull/43606){:target="_blank"}  from **@Dr15Jones**: Removed get_temporary_buffer from L1Trigger/L1TMuonEndCap `l1` created: 2023-12-19 17:10:33 merged: 2024-01-08 19:29:53

121. [43605](http://github.com/cms-sw/cmssw/pull/43605){:target="_blank"}  from **@Dr15Jones**: Removed operator= from Phase2L1CaloJetEmulator helpers `l1` `upgrade` created: 2023-12-19 16:41:19 merged: 2024-01-08 19:30:55

122. [43604](http://github.com/cms-sw/cmssw/pull/43604){:target="_blank"}  from **@Dr15Jones**: Removed std::unary_function from l1t::KeyGetter `l1` `upgrade` created: 2023-12-19 15:59:47 merged: 2024-01-08 19:31:08

123. [43601](http://github.com/cms-sw/cmssw/pull/43601){:target="_blank"}  from **@Dr15Jones**: Fixed std::accumulate use in L1Trigger/TrackFindingTracklet `l1` created: 2023-12-19 15:33:14 merged: 2024-01-08 19:31:23

124. [43592](http://github.com/cms-sw/cmssw/pull/43592){:target="_blank"}  from **@kdeleo**: Vertex reconstruction: code re-organization + vertex time computation `alca` `dqm` `operations` `reconstruction` `simulation` `upgrade` `tracking` `trk` created: 2023-12-18 16:30:18 merged: 2024-01-30 15:44:41

125. [43581](http://github.com/cms-sw/cmssw/pull/43581){:target="_blank"}  from **@lathomas**: TeV jet RAW-RECO skim `pdmv` created: 2023-12-15 22:46:44 merged: 2024-01-19 16:01:40

126. [43567](http://github.com/cms-sw/cmssw/pull/43567){:target="_blank"}  from **@bsunanda**: Phase2-hgx350Z Investigation of the failure in finding the correct UV from a position in space for V18 geometry of HGCal `geometry` `simulation` `upgrade` created: 2023-12-14 15:30:32 merged: 2024-01-08 19:31:48

127. [43565](http://github.com/cms-sw/cmssw/pull/43565){:target="_blank"}  from **@slava77**: followup fixes after enabling seedingDeepCore displacedRegionalTracking in #43472 `dqm` `operations` `tracking` created: 2023-12-14 03:14:46 merged: 2024-01-16 14:50:47

128. [43547](http://github.com/cms-sw/cmssw/pull/43547){:target="_blank"}  from **@Pruthvi-ch**: Corrections to HD partial wafer cell pattern of HGCal `geometry` `simulation` `upgrade` created: 2023-12-12 12:01:24 merged: 2024-01-08 19:34:32

129. [43544](http://github.com/cms-sw/cmssw/pull/43544){:target="_blank"}  from **@jfernan2**: Fix static warnings on DT L1T `l1` `upgrade` created: 2023-12-11 16:16:41 merged: 2024-01-08 19:36:19

130. [43543](http://github.com/cms-sw/cmssw/pull/43543){:target="_blank"}  from **@CTPPS**: Refactoring PI plugin for PPSTiming -- added input parameters `db` created: 2023-12-11 08:27:38 merged: 2024-01-12 14:56:30

131. [43541](http://github.com/cms-sw/cmssw/pull/43541){:target="_blank"}  from **@CTPPS**: new PI plugin added for TotemDAQMapping class `db` created: 2023-12-10 23:18:01 merged: 2024-01-08 19:37:29

132. [43535](http://github.com/cms-sw/cmssw/pull/43535){:target="_blank"}  from **@swagata87**: Making ECAL detector based isolation more robust against noise `dqm` `reconstruction` `egamma` created: 2023-12-09 18:52:01 merged: 2024-01-08 19:48:07

133. [43533](http://github.com/cms-sw/cmssw/pull/43533){:target="_blank"}  from **@namapane**: Fix haddnano.py to handle zero-events nanoAOD files properly `xpog` created: 2023-12-09 09:57:11 merged: 2024-01-17 19:05:59

134. [43524](http://github.com/cms-sw/cmssw/pull/43524){:target="_blank"}  from **@p2l1-gtEmulator**: Add integer hw accessor function to P2GTCandidate `l1` created: 2023-12-08 11:47:51 merged: 2024-01-08 19:48:22

135. [43502](http://github.com/cms-sw/cmssw/pull/43502){:target="_blank"}  from **@cfmcginn**: Removal of ZDC LUT file in caloParamsHelper and L1T workflow `l1` created: 2023-12-05 15:29:26 merged: 2024-01-12 14:48:46

136. [43487](http://github.com/cms-sw/cmssw/pull/43487){:target="_blank"}  from **@JunquanTao**: Add PV sumPT2 of pf charged particles associated to PV in NanoAOD  `xpog` created: 2023-12-04 13:31:37 merged: 2024-01-12 14:48:26

137. [43478](http://github.com/cms-sw/cmssw/pull/43478){:target="_blank"}  from **@jfernan2**: Change output from RECO to AOD in Run3 Data RelVal wfs `pdmv` `upgrade` created: 2023-12-01 19:15:49 merged: 2024-01-12 14:55:51

138. [43440](http://github.com/cms-sw/cmssw/pull/43440){:target="_blank"}  from **@aloeliger**: Cicada pattern testing `l1` created: 2023-11-29 17:00:46 merged: 2024-01-08 20:41:42

139. [43430](http://github.com/cms-sw/cmssw/pull/43430){:target="_blank"}  from **@apetkovi1**: Add HZZ electron ID for Run3 `reconstruction` `xpog` `egamma` created: 2023-11-29 12:39:24 merged: 2024-01-15 15:57:54

140. [43374](http://github.com/cms-sw/cmssw/pull/43374){:target="_blank"}  from **@PonIlya**: CondDBESSource.cc added dump method to JSON file `alca` `db` created: 2023-11-23 13:51:36 merged: 2024-01-12 14:47:16

141. [43310](http://github.com/cms-sw/cmssw/pull/43310){:target="_blank"}  from **@makortel**: Allow Portable{Collection,Object}<T, TDev> to be used also independently of ALPAKA_ACCELERATOR_NAMESPACE `heterogeneous` created: 2023-11-16 22:47:24 merged: 2024-01-08 20:42:21

142. [43294](http://github.com/cms-sw/cmssw/pull/43294){:target="_blank"}  from **@PixelTracksAlpaka**: Pixel Alpaka Migration: Configs and Fixes [VII] `dqm` `hlt` `operations` `reconstruction` `pdmv` `upgrade` `heterogeneous` `tracking` `trk` created: 2023-11-15 17:27:15 merged: 2024-01-30 20:15:59

143. [43257](http://github.com/cms-sw/cmssw/pull/43257){:target="_blank"}  from **@thomreis**: ECAL unpacker and ECAL multifit algorithm migration to alpaka `dqm` `alca` `hlt` `operations` `reconstruction` `simulation` `pdmv` `upgrade` `heterogeneous` `ecal` created: 2023-11-13 14:59:05 merged: 2024-01-26 14:36:00

144. [43233](http://github.com/cms-sw/cmssw/pull/43233){:target="_blank"}  from **@thesps**: L1T Seeded Cone jets update `l1` `upgrade` created: 2023-11-09 13:08:35 merged: 2024-01-19 16:01:04

145. [43195](http://github.com/cms-sw/cmssw/pull/43195){:target="_blank"}  from **@etzia**: Add Run3 promptData JetID `reconstruction` `xpog` created: 2023-11-06 09:46:50 merged: 2024-01-19 16:00:43

146. [43064](http://github.com/cms-sw/cmssw/pull/43064){:target="_blank"}  from **@ericcano**: Ports prefixScan, OneToManyAssoc and HistoContainer from CUDAUtilities. `heterogeneous` created: 2023-10-19 10:11:17 merged: 2024-01-23 14:37:47

147. [43046](http://github.com/cms-sw/cmssw/pull/43046){:target="_blank"}  from **@mitaylor**: Add caloParams v0_4_2 and v0_4_3 `l1` created: 2023-10-17 22:30:43 merged: 2024-01-19 15:59:53

148. [41288](http://github.com/cms-sw/cmssw/pull/41288){:target="_blank"}  from **@PixelTracksAlpaka**: Pixel Alpaka Migration: DQM [VI] `alca` `dqm` `reconstruction` `heterogeneous` `tracking` `trk` created: 2023-04-05 15:50:50 merged: 2024-01-29 17:06:59

149. [41287](http://github.com/cms-sw/cmssw/pull/41287){:target="_blank"}  from **@PixelTracksAlpaka**: Pixel Alpaka Migration: Vertexing [V] `alca` `reconstruction` `heterogeneous` `tracking` `trk` created: 2023-04-05 15:50:42 merged: 2024-01-29 14:17:59

150. [41286](http://github.com/cms-sw/cmssw/pull/41286){:target="_blank"}  from **@PixelTracksAlpaka**: Pixel Alpaka Migration: Tracking [IV] `reconstruction` `heterogeneous` `tracking` `trk` created: 2023-04-05 15:50:40 merged: 2024-01-29 14:17:00

151. [41285](http://github.com/cms-sw/cmssw/pull/41285){:target="_blank"}  from **@PixelTracksAlpaka**: Pixel Alpaka Migration: Local Reconstruction [III] `simulation` `alca` `reconstruction` `db` `heterogeneous` `tracking` `trk` created: 2023-04-05 15:50:36 merged: 2024-01-26 14:33:15

152. [41255](http://github.com/cms-sw/cmssw/pull/41255){:target="_blank"}  from **@AdrianoDee**: Guard for No Digis for Phase2 and Patatrack `NuGun` `reconstruction` `pdmv` `upgrade` `trk` created: 2023-04-03 09:50:11 merged: 2024-01-22 15:21:04

153. [41162](http://github.com/cms-sw/cmssw/pull/41162){:target="_blank"}  from **@iarspider-cmssw**: Add test for (py3-)torch `analysis` created: 2023-03-23 15:49:06 merged: 2024-01-08 20:42:59

154. [40921](http://github.com/cms-sw/cmssw/pull/40921){:target="_blank"}  from **@lk11235**: HipPy update to python3 `alca` `trk` created: 2023-03-01 23:40:27 merged: 2024-01-08 20:44:22

#### CMSDIST Changes between Tags REL/CMSSW_14_0_0_pre2/el8_amd64_gcc12 and REL/CMSSW_14_0_0_pre3/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_0_0_pre2/el8_amd64_gcc12...REL/CMSSW_14_0_0_pre3/el8_amd64_gcc12)



1. [8974](http://github.com/cms-sw/cmsdist/pull/8974){:target="_blank"}  from **@cms-sw**: [CRAB] Remove deployment of crab/examples created: 2024-01-29 15:43:20 merged: 2024-01-30 16:19:36

2. [8972](http://github.com/cms-sw/cmsdist/pull/8972){:target="_blank"}  from **@cms-sw**: TF: make tensorflow_mkldnn_contraction_kernel configurable created: 2024-01-29 07:31:54 merged: 2024-01-29 09:15:10

3. [8971](http://github.com/cms-sw/cmsdist/pull/8971){:target="_blank"}  from **@cms-sw**: cms-git-tools: Fix for squashed commits with Co-authored created: 2024-01-26 19:06:42 merged: 2024-01-26 21:42:28

4. [8969](http://github.com/cms-sw/cmsdist/pull/8969){:target="_blank"}  from **@cms-sw**: SCRAMV2: back ported ignoreing site hooks support to SCRAMV2 created: 2024-01-25 08:37:38 merged: 2024-01-25 09:49:28

5. [8968](http://github.com/cms-sw/cmsdist/pull/8968){:target="_blank"}  from **@cms-sw**: SCRAMV1 update to latest commit created: 2024-01-24 21:37:30 merged: 2024-01-24 21:37:39

6. [8967](http://github.com/cms-sw/cmsdist/pull/8967){:target="_blank"}  from **@cms-sw**: Update tag for RecoMET-METPUSubtraction to V01-03-00 created: 2024-01-24 15:21:46 merged: 2024-01-24 19:19:55

7. [8966](http://github.com/cms-sw/cmsdist/pull/8966){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-EgammaPhotonProducers to V00-05-00 created: 2024-01-24 15:21:34 merged: 2024-01-24 19:21:14

8. [8965](http://github.com/cms-sw/cmsdist/pull/8965){:target="_blank"}  from **@cms-sw**: Update tag for RecoEcal-EgammaClusterProducers to V00-04-00 created: 2024-01-24 15:21:27 merged: 2024-01-24 19:16:29

9. [8964](http://github.com/cms-sw/cmsdist/pull/8964){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-20-00 created: 2024-01-24 15:21:20 merged: 2024-01-24 19:15:06

10. [8963](http://github.com/cms-sw/cmsdist/pull/8963){:target="_blank"}  from **@cms-sw**: Update tag for HeterogeneousCore-SonicTriton to V00-03-00 created: 2024-01-24 15:21:07 merged: 2024-01-24 19:14:31

11. [8962](http://github.com/cms-sw/cmsdist/pull/8962){:target="_blank"}  from **@cms-sw**: cms-common: support for ignoring site specific hooks created: 2024-01-24 10:43:20 merged: 2024-01-24 19:13:04

12. [8961](http://github.com/cms-sw/cmsdist/pull/8961){:target="_blank"}  from **@cms-sw**: Update py-pillow to 10.2.0 created: 2024-01-24 07:22:58 merged: 2024-01-24 19:21:37

13. [8960](http://github.com/cms-sw/cmsdist/pull/8960){:target="_blank"}  from **@cms-sw**: cms-common: Fix for gsl-config created: 2024-01-23 17:03:10 merged: 2024-01-23 21:35:02

14. [8959](http://github.com/cms-sw/cmsdist/pull/8959){:target="_blank"}  from **@cms-sw**: cms-common: fixed gsl runtime hook to include openblas libs created: 2024-01-23 14:29:52 merged: 2024-01-23 16:31:12

15. [8958](http://github.com/cms-sw/cmsdist/pull/8958){:target="_blank"}  from **@cms-sw**: Fix gsl-config so that by default it uses openblas lib created: 2024-01-23 11:31:03 merged: 2024-01-23 21:48:09

16. [8956](http://github.com/cms-sw/cmsdist/pull/8956){:target="_blank"}  from **@cms-sw**: Update tag for RecoMuon-MuonIdentification to V01-16-00 created: 2024-01-22 15:22:10 merged: 2024-01-23 10:22:51

17. [8955](http://github.com/cms-sw/cmsdist/pull/8955){:target="_blank"}  from **@cms-sw**: Update tag for DataFormats-L1Scouting to V00-01-00 created: 2024-01-19 16:19:25 merged: 2024-01-19 16:19:55

18. [8954](http://github.com/cms-sw/cmsdist/pull/8954){:target="_blank"}  from **@cms-sw**: Update tag for DataFormats-L1ScoutingRawData to V00-01-00 created: 2024-01-19 16:17:20 merged: 2024-01-19 16:17:51

19. [8953](http://github.com/cms-sw/cmsdist/pull/8953){:target="_blank"}  from **@consuegs**: Update Millepede to V04-14-00 created: 2024-01-18 13:32:03 merged: 2024-01-23 10:20:15

20. [8951](http://github.com/cms-sw/cmsdist/pull/8951){:target="_blank"}  from **@cms-sw**: Support for psABI micro architectures created: 2024-01-18 06:33:43 merged: 2024-01-18 21:05:22

21. [8949](http://github.com/cms-sw/cmsdist/pull/8949){:target="_blank"}  from **@smuzaffar**: Updated root to tip of branch v6-30-00-patches created: 2024-01-17 16:39:54 merged: 2024-01-18 20:51:31

22. [8947](http://github.com/cms-sw/cmsdist/pull/8947){:target="_blank"}  from **@kpedro88**: Improve protobuf text_format output created: 2024-01-16 21:43:44 merged: 2024-01-18 21:05:48

23. [8946](http://github.com/cms-sw/cmsdist/pull/8946){:target="_blank"}  from **@cms-sw**: Update tag for GeneratorInterface-EvtGenInterface to V02-08-00 created: 2024-01-16 15:16:52 merged: 2024-01-16 15:25:48

24. [8945](http://github.com/cms-sw/cmsdist/pull/8945){:target="_blank"}  from **@cms-sw**: Python tools versions with security fixes updates created: 2024-01-16 13:29:38 merged: 2024-01-16 17:34:26

25. [8944](http://github.com/cms-sw/cmsdist/pull/8944){:target="_blank"}  from @cms-sw: scram-tools: Fix for replacing `**@VAR**@` in toolfile; remove PGO-Profiles subdir created: 2024-01-16 13:20:39 merged: 2024-01-16 15:41:47

26. [8943](http://github.com/cms-sw/cmsdist/pull/8943){:target="_blank"}  from **@cms-sw**: Enable triton-client python interface created: 2024-01-16 13:05:39 merged: 2024-01-16 21:36:16

27. [8942](http://github.com/cms-sw/cmsdist/pull/8942){:target="_blank"}  from **@cms-sw**: Update dd4hep v01-27-02: Adapt to ROOT 6.31 created: 2024-01-16 10:41:54 merged: 2024-01-16 15:30:27

28. [8941](http://github.com/cms-sw/cmsdist/pull/8941){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-ElectronIdentification to V01-14-00 created: 2024-01-16 08:33:24 merged: 2024-01-16 08:33:44

29. [8940](http://github.com/cms-sw/cmsdist/pull/8940){:target="_blank"}  from **@belforte**: move CRABClient v3.240110 to crab-prod created: 2024-01-15 21:55:26 merged: 2024-01-16 08:56:30

30. [8939](http://github.com/cms-sw/cmsdist/pull/8939){:target="_blank"}  from **@cms-sw**: PGO: Use env variables with fprofile-use instead of %q{VAR} created: 2024-01-15 15:57:14 merged: 2024-01-16 10:23:11

31. [8933](http://github.com/cms-sw/cmsdist/pull/8933){:target="_blank"}  from **@belforte**: Update crab-dev.spec created: 2024-01-10 17:26:38 merged: 2024-01-10 21:57:07

32. [8932](http://github.com/cms-sw/cmsdist/pull/8932){:target="_blank"}  from **@cms-sw**: xrootd: Update to version 5.6.4 created: 2024-01-10 15:57:36 merged: 2024-01-11 07:08:42

33. [8931](http://github.com/cms-sw/cmsdist/pull/8931){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2024-01-10 15:31:42 merged: 2024-01-10 19:27:40

34. [8925](http://github.com/cms-sw/cmsdist/pull/8925){:target="_blank"}  from **@cms-sw**: cmssw-elX: source cmsset_default.sh in the new shell created: 2024-01-10 07:09:21 merged: 2024-01-10 08:05:56

35. [8923](http://github.com/cms-sw/cmsdist/pull/8923){:target="_blank"}  from **@cms-sw**: opencv: Update to version 4.9.0 which contains C++20 fixes created: 2024-01-08 15:31:30 merged: 2024-01-08 18:59:55

36. [8922](http://github.com/cms-sw/cmsdist/pull/8922){:target="_blank"}  from **@cms-sw**: Backport cpp20 changes to master branch created: 2024-01-08 15:00:33 merged: 2024-01-09 08:28:11

37. [8920](http://github.com/cms-sw/cmsdist/pull/8920){:target="_blank"}  from **@cms-sw**: celeritas: Disable OpenMP and fix the lib link order created: 2024-01-08 10:55:09 merged: 2024-01-08 13:41:59

38. [8919](http://github.com/cms-sw/cmsdist/pull/8919){:target="_blank"}  from **@cms-sw**: cmssw-osenv: Fix multi-command handling created: 2024-01-08 09:58:09 merged: 2024-01-08 13:29:11

39. [8918](http://github.com/cms-sw/cmsdist/pull/8918){:target="_blank"}  from **@cms-sw**: move common flags in separate file created: 2024-01-01 16:45:25 merged: 2024-01-01 22:37:58

40. [8916](http://github.com/cms-sw/cmsdist/pull/8916){:target="_blank"}  from **@cms-sw**: celeritas: support for geant4 11.2 created: 2023-12-31 13:34:06 merged: 2023-12-31 15:06:16

41. [8914](http://github.com/cms-sw/cmsdist/pull/8914){:target="_blank"}  from **@cms-sw**: [celeritas] build with -DCMAKE_POSITION_INDEPENDENT_CODE=ON created: 2023-12-29 12:09:37 merged: 2023-12-30 14:12:20

42. [8913](http://github.com/cms-sw/cmsdist/pull/8913){:target="_blank"}  from **@cms-sw**: [json] Explicitly added cmake and gmake deps created: 2023-12-24 09:47:19 merged: 2023-12-24 10:51:23

43. [8912](http://github.com/cms-sw/cmsdist/pull/8912){:target="_blank"}  from **@cms-sw**: Added celeritas version 0.4.1 created: 2023-12-23 11:28:40 merged: 2023-12-27 08:31:41

44. [8911](http://github.com/cms-sw/cmsdist/pull/8911){:target="_blank"}  from **@cms-sw**: [json] Version 3.11.3; build with cmake created: 2023-12-23 11:23:39 merged: 2023-12-23 21:51:09

45. [8910](http://github.com/cms-sw/cmsdist/pull/8910){:target="_blank"}  from **@cms-sw**: [geant4] Cleanup spec created: 2023-12-23 08:54:34 merged: 2023-12-23 21:50:39

46. [8908](http://github.com/cms-sw/cmsdist/pull/8908){:target="_blank"}  from **@cms-sw**: [BuildRule] Unit test colored output created: 2023-12-22 09:46:42 merged: 2023-12-23 08:47:29

47. [8907](http://github.com/cms-sw/cmsdist/pull/8907){:target="_blank"}  from **@cms-sw**: added build options which can be controlled via cmsBuild created: 2023-12-21 17:02:54 merged: 2023-12-30 14:53:44

48. [8906](http://github.com/cms-sw/cmsdist/pull/8906){:target="_blank"}  from **@jmduarte**: Add TOoLLiP extra created: 2023-12-21 05:24:45 merged: 2023-12-23 21:52:57

49. [8864](http://github.com/cms-sw/cmsdist/pull/8864){:target="_blank"}  from **@cms-sw**: VecGeom: Update to version 1.2.7 created: 2023-12-08 06:29:11 merged: 2023-12-23 08:46:57
