---
layout: post
rel_link:  "14_1_0_pre0"
title:  "CMSSW_14_1_0_pre0"
date:   2024-02-15 13:19:54
categories: cmssw
relmajor: 14
relminor: 1
relsubminor: 0
relpre: _pre0
---

# CMSSW_14_1_0_pre0
#### Changes since CMSSW_14_0_0_pre3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_0_0_pre3...CMSSW_14_1_0_pre0)



1. [43951](http://github.com/cms-sw/cmssw/pull/43951){:target="_blank"}  from **@CTPPS**: CTPPS update HLTPPSJetComparisonFilter to use LHCInfoCombined `hlt` `ctpps` created: 2024-02-13 16:04:08 merged: 2024-02-14 11:46:42

2. [43935](http://github.com/cms-sw/cmssw/pull/43935){:target="_blank"}  from **@mmusich**: Miscellaneous improvements to `Alignment/MillePedeAlignmentAlgorithm` unit tests `alca` `trk` created: 2024-02-11 17:45:46 merged: 2024-02-12 18:09:07

3. [43934](http://github.com/cms-sw/cmssw/pull/43934){:target="_blank"}  from **@bsunanda**: Phase2-hgx353D Modify some of the cfg's in Validation/HGCalValidation to work for V16, V17, V18 scenarios of HGCal Geometry `dqm` created: 2024-02-11 06:12:29 merged: 2024-02-12 18:07:14

4. [43933](http://github.com/cms-sw/cmssw/pull/43933){:target="_blank"}  from **@bsunanda**: Phase2-hgx153C Modify some of the test scripts in Validation/HGCalValidation for each of calorimeter scenarios `dqm` created: 2024-02-10 09:54:10 merged: 2024-02-12 18:06:04

5. [43931](http://github.com/cms-sw/cmssw/pull/43931){:target="_blank"}  from **@wddgit**: Removed unused code related to OwnVector `fastsim` `reconstruction` `tracking` created: 2024-02-09 22:13:35 merged: 2024-02-13 13:55:51

6. [43920](http://github.com/cms-sw/cmssw/pull/43920){:target="_blank"}  from **@Dr15Jones**: Throw exception if TFile::Open returns nullptr `core` created: 2024-02-08 16:30:55 merged: 2024-02-09 14:45:31

7. [43917](http://github.com/cms-sw/cmssw/pull/43917){:target="_blank"}  from **@mbluj**: Configuration arguments for version and packing schema of covariance in DeepJetTag producer `reconstruction` `btv` created: 2024-02-08 14:59:16 merged: 2024-02-14 11:54:05

8. [43916](http://github.com/cms-sw/cmssw/pull/43916){:target="_blank"}  from **@vlimant**: Nano branches from ValueMap of elaborated types `xpog` created: 2024-02-08 14:33:29 merged: 2024-02-13 13:59:34

9. [43915](http://github.com/cms-sw/cmssw/pull/43915){:target="_blank"}  from **@dan131riley**: MkFitCore: move simd pragmas to inner loops to address clang warnings `reconstruction` `tracking` created: 2024-02-08 13:41:28 merged: 2024-02-12 17:59:26

10. [43910](http://github.com/cms-sw/cmssw/pull/43910){:target="_blank"}  from **@bsunanda**: Phase2-hgx353A Update various cfg files to do the tests for V18 versions of HGCal `geometry` `upgrade` created: 2024-02-08 09:59:58 merged: 2024-02-09 14:45:43

11. [43906](http://github.com/cms-sw/cmssw/pull/43906){:target="_blank"}  from **@cms-tsg-storm**: Migration to ConfDb 14_0_0_pre3 template and addOnTests bug fix [14_1_X] `hlt` created: 2024-02-08 08:28:40 merged: 2024-02-09 12:14:36

12. [43903](http://github.com/cms-sw/cmssw/pull/43903){:target="_blank"}  from **@bsunanda**: Phase2-hgx353 add a new scenario 2026D109 utilizing V18 version of HGCAL after removing some of the gaps `geometry` `operations` `pdmv` `upgrade` created: 2024-02-08 05:11:21 merged: 2024-02-12 17:22:16

13. [43900](http://github.com/cms-sw/cmssw/pull/43900){:target="_blank"}  from **@saumyaphor4252**: Update Run3 CSC conditions in 2022, 2023, 2024 realistic MC GTs and offline data GT `alca` created: 2024-02-07 17:33:50 merged: 2024-02-14 11:59:51

14. [43894](http://github.com/cms-sw/cmssw/pull/43894){:target="_blank"}  from **@Dr15Jones**: Issue exception for ROOT file forward incompatiblity problem `core` created: 2024-02-07 16:13:31 merged: 2024-02-09 14:45:58

15. [43890](http://github.com/cms-sw/cmssw/pull/43890){:target="_blank"}  from **@mbluj**: Implementation of TauWPThreshold without need to catch exceptions `reconstruction` `tau` created: 2024-02-07 15:42:27 merged: 2024-02-09 14:56:35

16. [43885](http://github.com/cms-sw/cmssw/pull/43885){:target="_blank"}  from **@swagata87**: Produce sMajor, sMinor in EgammaHLTClusterShapeProducer `hlt` `egamma` created: 2024-02-07 07:59:12 merged: 2024-02-12 17:43:43

17. [43878](http://github.com/cms-sw/cmssw/pull/43878){:target="_blank"}  from **@perrotta**: Do not redefine twice in CMSSW the TkAl muon selectors `alca` `trk` created: 2024-02-06 13:13:31 merged: 2024-02-09 14:56:59

18. [43876](http://github.com/cms-sw/cmssw/pull/43876){:target="_blank"}  from **@bsunanda**: Run3-gex175 Try to have the 2024 version of GE21 `geometry` created: 2024-02-06 11:28:05 merged: 2024-02-07 15:39:05

19. [43874](http://github.com/cms-sw/cmssw/pull/43874){:target="_blank"}  from **@mmusich**: fix `DAClusterizerInZ_vect` for ASAN_X build `reconstruction` `tracking` created: 2024-02-06 06:43:56 merged: 2024-02-07 15:18:23

20. [43873](http://github.com/cms-sw/cmssw/pull/43873){:target="_blank"}  from **@arsahasransu**: Implement the GSF Track fBrem Variable Filling for Scouting Electrons: 14_1 `hlt` created: 2024-02-05 19:35:18 merged: 2024-02-07 15:38:46

21. [43870](http://github.com/cms-sw/cmssw/pull/43870){:target="_blank"}  from **@mmusich**: miscellaneous updates to improve validation of phase-2 Tracker Alignment samples `alca` `trk` created: 2024-02-05 15:54:44 merged: 2024-02-07 15:38:04

22. [43869](http://github.com/cms-sw/cmssw/pull/43869){:target="_blank"}  from **@aloeliger**: Add low pt muon fix objects into phase 2 L1 event content. `l1` created: 2024-02-05 14:47:42 merged: 2024-02-07 15:40:17

23. [43867](http://github.com/cms-sw/cmssw/pull/43867){:target="_blank"}  from **@cms-tsg-storm**:  HLT menu development for `13_3_X` (3/N) [`14_1_X`]  `hlt` created: 2024-02-05 14:16:52 merged: 2024-02-06 17:03:09

24. [43865](http://github.com/cms-sw/cmssw/pull/43865){:target="_blank"}  from **@mmusich**: HLT development: add unit test for online vs dev tables consistency `hlt` created: 2024-02-05 10:38:20 merged: 2024-02-07 15:37:41

25. [43862](http://github.com/cms-sw/cmssw/pull/43862){:target="_blank"}  from **@bsunanda**: Phase2-hgx352C Fix the unit test in Configuration/Geometry `geometry` `upgrade` created: 2024-02-04 06:34:34 merged: 2024-02-05 11:32:26

26. [43860](http://github.com/cms-sw/cmssw/pull/43860){:target="_blank"}  from **@michael-pitt**: extend histograms to the Run3 range in CTPPSLHCInfoPlotter `dqm` created: 2024-02-03 18:07:38 merged: 2024-02-05 11:59:36

27. [43859](http://github.com/cms-sw/cmssw/pull/43859){:target="_blank"}  from **@mmusich**: add phase2 customizations to `TkAlMuonSelectors` to increase selection efficiency `alca` created: 2024-02-03 17:59:39 merged: 2024-02-07 15:36:56

28. [43857](http://github.com/cms-sw/cmssw/pull/43857){:target="_blank"}  from **@sroychow**: Migrate dqm & validation  plugins from Sioutertracker to Sitrackerphase2 `dqm` `simulation` `trk` created: 2024-02-03 17:42:29 merged: 2024-02-12 17:37:49

29. [43856](http://github.com/cms-sw/cmssw/pull/43856){:target="_blank"}  from **@mmusich**: Update `TestRun3ScoutingFormats.sh` for CMSSW_14_0_0_pre3 Scouting DataFormat updates `core` created: 2024-02-03 15:01:26 merged: 2024-02-07 15:36:10

30. [43855](http://github.com/cms-sw/cmssw/pull/43855){:target="_blank"}  from **@hsert**: Fix Phase2 ditau HLT path (with DeepTau Isolation) `hlt` `reconstruction` `tau` created: 2024-02-03 10:03:11 merged: 2024-02-07 15:41:03

31. [43854](http://github.com/cms-sw/cmssw/pull/43854){:target="_blank"}  from **@michael-pitt**: update XangleBetaStarFilter with NewLHCInfo `db` created: 2024-02-03 05:57:06 merged: 2024-02-09 12:18:27

32. [43853](http://github.com/cms-sw/cmssw/pull/43853){:target="_blank"}  from **@fwyzard**: Follow up to the Alpaka integration in CMSSW `alca` `geometry` `reconstruction` `pdmv` `db` `upgrade` `heterogeneous` `tracking` `trk` created: 2024-02-03 00:29:15 merged: 2024-02-12 20:22:05

33. [43852](http://github.com/cms-sw/cmssw/pull/43852){:target="_blank"}  from **@ccahoughton**: Implement quick fix for eta going out of scope `l1` `upgrade` created: 2024-02-02 18:48:29 merged: 2024-02-09 14:57:24

34. [43850](http://github.com/cms-sw/cmssw/pull/43850){:target="_blank"}  from **@smorovic**: [14_0_X][DAQ] DaqDirector fixes and cleanup, and removal of EvFOutputModule `daq` created: 2024-02-02 15:29:45 merged: 2024-02-03 14:36:11

35. [43844](http://github.com/cms-sw/cmssw/pull/43844){:target="_blank"}  from **@bsunanda**: Run3-Sim154 Try to avoid memory leak issues in SimG4Core/PrintGeomeInfo and Geometry/TrackerCommonData `geometry` `simulation` `trk` created: 2024-02-02 09:48:06 merged: 2024-02-05 11:58:07

36. [43842](http://github.com/cms-sw/cmssw/pull/43842){:target="_blank"}  from **@cms-tsg-storm**: HLT development for 13_3 2/N [14_0_X] `hlt` created: 2024-02-02 08:45:28 merged: 2024-02-02 14:11:48

37. [43841](http://github.com/cms-sw/cmssw/pull/43841){:target="_blank"}  from **@bsunanda**: Phase2-hgx352B Add an example of CMS scenario with only HGCal detector `geometry` `operations` `simulation` `upgrade` created: 2024-02-02 06:28:21 merged: 2024-02-07 19:09:46

38. [43835](http://github.com/cms-sw/cmssw/pull/43835){:target="_blank"}  from **@wddgit**: Remove edmConvertToStreamModule.py, it's no longer needed `core` created: 2024-02-01 15:18:50 merged: 2024-02-02 14:26:12

39. [43834](http://github.com/cms-sw/cmssw/pull/43834){:target="_blank"}  from **@smuzaffar**: ROOT6 changes needed for RNTupleModel `xpog` created: 2024-02-01 13:44:52 merged: 2024-02-07 15:42:13

40. [43833](http://github.com/cms-sw/cmssw/pull/43833){:target="_blank"}  from **@wddgit**: Delete last analysis legacy type modules `analysis` created: 2024-01-31 23:14:13 merged: 2024-02-02 14:26:05

41. [43832](http://github.com/cms-sw/cmssw/pull/43832){:target="_blank"}  from **@wddgit**: Delete last L1 legacy type module `l1` created: 2024-01-31 21:20:00 merged: 2024-02-02 14:24:54

42. [43829](http://github.com/cms-sw/cmssw/pull/43829){:target="_blank"}  from **@wddgit**: Migrate last geometry legacy type module `geometry` created: 2024-01-31 17:47:26 merged: 2024-02-02 14:24:37

43. [43828](http://github.com/cms-sw/cmssw/pull/43828){:target="_blank"}  from **@makortel**: Fix NanoAOD workflow reading 12_4_X file `core` `pdmv` `upgrade` created: 2024-01-31 16:59:41 merged: 2024-02-05 11:44:39

44. [43827](http://github.com/cms-sw/cmssw/pull/43827){:target="_blank"}  from **@mmusich**: update input file for `testG4Refitter` to avoid backward compatibility issue due to not storing `TStreamerInfo` `simulation` `tracking` created: 2024-01-31 16:55:03 merged: 2024-02-02 14:24:23

45. [43826](http://github.com/cms-sw/cmssw/pull/43826){:target="_blank"}  from **@makortel**: Remove unnecessary import of L1GTScales `l1` `upgrade` created: 2024-01-31 15:50:01 merged: 2024-02-07 19:13:19

46. [43825](http://github.com/cms-sw/cmssw/pull/43825){:target="_blank"}  from **@makortel**: Declare InvariantMassError as transient data product `l1` `upgrade` created: 2024-01-31 15:42:20 merged: 2024-02-07 19:14:40

47. [43822](http://github.com/cms-sw/cmssw/pull/43822){:target="_blank"}  from **@RSalvatico**: Make default Phase2 HLT thresholds from config file the same as in Run3 `hlt` `egamma` created: 2024-01-31 11:24:43 merged: 2024-02-05 12:02:52

48. [43821](http://github.com/cms-sw/cmssw/pull/43821){:target="_blank"}  from **@gpetruc**:     Phase-2 L1T Correlator: Rewrite linpuppi emulator with ap_fixed `l1` `upgrade` created: 2024-01-31 08:58:03 merged: 2024-02-07 15:34:04

49. [43818](http://github.com/cms-sw/cmssw/pull/43818){:target="_blank"}  from **@wddgit**: Delete last daq legacy type module `daq` `l1` `reconstruction` created: 2024-01-30 22:54:14 merged: 2024-02-07 15:41:13

50. [43814](http://github.com/cms-sw/cmssw/pull/43814){:target="_blank"}  from **@kpedro88**: cmsTriton bug fixes and improvements `pdmv` `upgrade` `heterogeneous` created: 2024-01-30 16:05:46 merged: 2024-02-11 16:23:32

51. [43813](http://github.com/cms-sw/cmssw/pull/43813){:target="_blank"}  from **@denizsun**: SkipEvent is removed [issue#43793] `dqm` created: 2024-01-30 15:54:44 merged: 2024-02-02 14:23:38

52. [43809](http://github.com/cms-sw/cmssw/pull/43809){:target="_blank"}  from **@SohamBhattacharya**: [14_1_X] [Phase-2] Change Phase-2 HLT Egamma paths to use the GT emulator `hlt` `reconstruction` `upgrade` `egamma` created: 2024-01-30 06:35:28 merged: 2024-02-12 17:24:54

53. [43805](http://github.com/cms-sw/cmssw/pull/43805){:target="_blank"}  from **@fabiocos**: Geometry: add Phase2 scenarios D107 = T32+C17+M11+I17+O9+F8 and D108 = T35+C19+M11+I17+O9+F8 `geometry` `operations` `pdmv` `upgrade` created: 2024-01-29 10:53:47 merged: 2024-02-07 19:08:33

54. [43799](http://github.com/cms-sw/cmssw/pull/43799){:target="_blank"}  from **@aloeliger**: Update CICADA emulator templates and update model version to pattern testing model `l1` created: 2024-01-26 15:45:57 merged: 2024-02-07 19:16:57

55. [43798](http://github.com/cms-sw/cmssw/pull/43798){:target="_blank"}  from **@brusale**: Fix purity and duplicate calculation in HGCal validation `dqm` created: 2024-01-26 14:09:07 merged: 2024-02-07 15:41:24

56. [43795](http://github.com/cms-sw/cmssw/pull/43795){:target="_blank"}  from **@thomreis**: ECAL - Set correct CC tag labels for ECAL RecHit producer `dqm` `reconstruction` `ecal` created: 2024-01-26 12:31:20 merged: 2024-02-02 14:23:18

57. [43791](http://github.com/cms-sw/cmssw/pull/43791){:target="_blank"}  from **@quinnanm**: AXOL1TL change to v3 of model  `l1` created: 2024-01-26 02:41:43 merged: 2024-02-02 14:22:58

58. [43772](http://github.com/cms-sw/cmssw/pull/43772){:target="_blank"}  from **@fwyzard**: Update Alpaka to version 1.1.0 `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-01-23 13:25:05 merged: 2024-02-13 13:06:50

59. [43769](http://github.com/cms-sw/cmssw/pull/43769){:target="_blank"}  from **@bsunanda**: Phase2 hgx352A: Add possibilities of more scenarios in some of the checks of G4 Components `geometry` `simulation` `upgrade` `trk` created: 2024-01-23 04:17:18 merged: 2024-02-03 14:37:02

60. [43762](http://github.com/cms-sw/cmssw/pull/43762){:target="_blank"}  from **@parbol**: A new digitization model for the ETL detector `reconstruction` `simulation` `upgrade` `mtd` created: 2024-01-21 23:16:11 merged: 2024-02-09 14:59:21

61. [43706](http://github.com/cms-sw/cmssw/pull/43706){:target="_blank"}  from **@hgc-tpg**: [HGCAL trigger] Configurations fixes and updates `l1` `upgrade` created: 2024-01-12 13:53:20 merged: 2024-02-08 21:52:18

62. [43701](http://github.com/cms-sw/cmssw/pull/43701){:target="_blank"}  from **@jsamudio**: Introduce matrix workflows for Alpaka-based Particle Flow `dqm` `operations` `reconstruction` `pdmv` `upgrade` `pf` created: 2024-01-11 16:47:39 merged: 2024-02-14 20:46:50

63. [43569](http://github.com/cms-sw/cmssw/pull/43569){:target="_blank"}  from **@jfernan2**: [DQM DT] Changes to put back DT Noise plot in Online DQM `dqm` created: 2023-12-14 16:51:36 merged: 2024-02-09 14:59:50

64. [43468](http://github.com/cms-sw/cmssw/pull/43468){:target="_blank"}  from **@agrubercms**: SimTauCPLink - Adding a link between GenTaus and CaloParticles `dqm` `reconstruction` `simulation` `upgrade` created: 2023-12-01 10:25:53 merged: 2024-02-09 15:02:01

65. [43334](http://github.com/cms-sw/cmssw/pull/43334){:target="_blank"}  from **@iarspider**: Replace classlib's Regex with std::regex `dqm` created: 2023-11-20 14:23:58 merged: 2024-02-09 15:02:30

66. [41928](http://github.com/cms-sw/cmssw/pull/41928){:target="_blank"}  from **@ericcano**: SoA range checking: adds inter operability between range checked and non range checked `heterogeneous` created: 2023-06-12 15:32:38 merged: 2024-02-07 15:33:44

67. [40285](http://github.com/cms-sw/cmssw/pull/40285){:target="_blank"}  from **@ericcano**: Add support to multi layout portable collections (any number) `heterogeneous` created: 2022-12-12 09:36:42 merged: 2024-02-13 14:03:51

#### CMSDIST Changes between Tags REL/CMSSW_14_0_0_pre3/el8_amd64_gcc12 and REL/CMSSW_14_1_0_pre0/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_0_0_pre3/el8_amd64_gcc12...REL/CMSSW_14_1_0_pre0/el8_amd64_gcc12)



1. [9022](http://github.com/cms-sw/cmsdist/pull/9022){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-Phase2L1ParticleFlow to V00-07-00 created: 2024-02-15 11:11:29 merged: 2024-02-15 11:11:31

2. [9016](http://github.com/cms-sw/cmsdist/pull/9016){:target="_blank"}  from **@cms-sw**: cmssw-elN: Drop -i option to not run in interactive mode created: 2024-02-13 22:35:31 merged: 2024-02-14 09:12:26

3. [9015](http://github.com/cms-sw/cmsdist/pull/9015){:target="_blank"}  from **@cms-sw**: grpcio: Changes backported from TF 2.15 branch created: 2024-02-13 22:31:20 merged: 2024-02-15 07:53:42

4. [9011](http://github.com/cms-sw/cmsdist/pull/9011){:target="_blank"}  from **@cms-sw**: [PPC64LE] Use system openssl for py3-grpcio created: 2024-02-13 09:11:56 merged: 2024-02-13 22:14:02

5. [9004](http://github.com/cms-sw/cmsdist/pull/9004){:target="_blank"}  from **@cms-sw**: [dependabot] Update grpcio and grpcio-tools to 1.60.1 created: 2024-02-12 10:59:07 merged: 2024-02-12 21:23:19

6. [9003](http://github.com/cms-sw/cmsdist/pull/9003){:target="_blank"}  from **@cms-sw**: [master] Updated root to tip of branch v6-30-00-patches created: 2024-02-12 10:55:31 merged: 2024-02-12 21:24:24

7. [8998](http://github.com/cms-sw/cmsdist/pull/8998){:target="_blank"}  from **@cms-sw**: Update tag for GeneratorInterface-EvtGenInterface to V02-09-00 created: 2024-02-10 07:49:33 merged: 2024-02-10 07:49:34

8. [8996](http://github.com/cms-sw/cmsdist/pull/8996){:target="_blank"}  from **@cms-sw**: BuildRules: Fixes for multi-arch and PGO created: 2024-02-09 08:04:15 merged: 2024-02-09 13:52:55

9. [8994](http://github.com/cms-sw/cmsdist/pull/8994){:target="_blank"}  from **@cms-sw**: Update tag for DataFormats-Scouting to V00-03-00 created: 2024-02-07 19:46:27 merged: 2024-02-07 19:47:09

10. [8990](http://github.com/cms-sw/cmsdist/pull/8990){:target="_blank"}  from **@cms-sw**: BuildRule: Fix emdplugin cache for multiarch builds created: 2024-02-07 08:26:25 merged: 2024-02-07 15:18:57

11. [8989](http://github.com/cms-sw/cmsdist/pull/8989){:target="_blank"}  from **@cms-sw**: Fix GBL compilation for non-x64 architectures created: 2024-02-07 08:11:55 merged: 2024-02-07 09:39:09

12. [8988](http://github.com/cms-sw/cmsdist/pull/8988){:target="_blank"}  from **@cms-sw**: pypi: Update cryptography 42.0.2 created: 2024-02-06 15:23:26 merged: 2024-02-06 19:20:59

13. [8987](http://github.com/cms-sw/cmsdist/pull/8987){:target="_blank"}  from **@cms-sw**: Update aiohttp to version 3.9.3 created: 2024-02-05 22:17:22 merged: 2024-02-06 14:33:33

14. [8986](http://github.com/cms-sw/cmsdist/pull/8986){:target="_blank"}  from **@cms-sw**: cmsdist_packages.py: Updated to contains information for cmssw-vectorize created: 2024-02-05 21:37:30 merged: 2024-02-05 21:37:52

15. [8985](http://github.com/cms-sw/cmsdist/pull/8985){:target="_blank"}  from **@cms-sw**: remove unused type="path" for environment tag created: 2024-02-05 21:28:51 merged: 2024-02-05 22:07:05

16. [8984](http://github.com/cms-sw/cmsdist/pull/8984){:target="_blank"}  from **@cms-sw**: ROOT: Use rootcling instead of genreflex for root dict generation created: 2024-02-05 14:45:55 merged: 2024-02-06 15:14:03

17. [8982](http://github.com/cms-sw/cmsdist/pull/8982){:target="_blank"}  from **@cms-sw**: Update tag for RecoTauTag-TrainingFiles to V00-09-00 created: 2024-02-03 17:42:22 merged: 2024-02-03 17:43:40

18. [8980](http://github.com/cms-sw/cmsdist/pull/8980){:target="_blank"}  from **@aandvalenzuela**: Update ROOT to use tagged version 6.30.04+cms patch in master IBs created: 2024-02-01 12:40:42 merged: 2024-02-06 16:20:31

19. [8979](http://github.com/cms-sw/cmsdist/pull/8979){:target="_blank"}  from **@cms-sw**: Build gbl for multivectorization release due to its eigen dependency created: 2024-01-31 06:21:01 merged: 2024-02-05 21:04:06

20. [8957](http://github.com/cms-sw/cmsdist/pull/8957){:target="_blank"}  from **@fwyzard**: Update Alpaka to version 1.1.0 created: 2024-01-23 10:10:01 merged: 2024-02-13 13:06:39
