---
layout: post
rel_link:  "13_3_0_pre5"
title:  "CMSSW_13_3_0_pre5"
date:   2023-11-02 13:24:45
categories: cmssw
relmajor: 13
relminor: 3
relsubminor: 0
relpre: _pre5
---

# CMSSW_13_3_0_pre5
#### Changes since CMSSW_13_3_0_pre4:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_13_3_0_pre4...CMSSW_13_3_0_pre5)



1. [43153](http://github.com/cms-sw/cmssw/pull/43153){:target="_blank"}  from **@iarspider**: Remove defaulted constructors and operators of StdArray  `core` created: 2023-10-31 08:36:45 merged: 2023-11-01 14:34:46

2. [43152](http://github.com/cms-sw/cmssw/pull/43152){:target="_blank"}  from **@jking79**: Update ecalMultiFitUncalibRecHit_cfi.py `reconstruction` `ecal` created: 2023-10-30 17:39:40 merged: 2023-11-01 14:30:04

3. [43148](http://github.com/cms-sw/cmssw/pull/43148){:target="_blank"}  from **@bsunanda**: Phase2-hgx348 Make provision for the new positions of the guard rings and sizes of partial wafers (V17 to V18 transition) `geometry` `simulation` `upgrade` created: 2023-10-30 09:59:59 merged: 2023-11-01 14:24:38

4. [43147](http://github.com/cms-sw/cmssw/pull/43147){:target="_blank"}  from **@smuzaffar**: Fix unittest by making a local copy of test configuration `alca` `db` created: 2023-10-30 08:48:10 merged: 2023-10-30 17:20:05

5. [43142](http://github.com/cms-sw/cmssw/pull/43142){:target="_blank"}  from **@fabiocos**: Simulation: adapt Phase2SteppingAction to the Tracker-CALO direct boundary for back-scattering detection `simulation` created: 2023-10-28 14:08:13 merged: 2023-10-29 23:28:34

6. [43139](http://github.com/cms-sw/cmssw/pull/43139){:target="_blank"}  from **@abdoulline**: HCAL: setting hardcoded PFCuts conditions for Phase2 `alca` created: 2023-10-28 11:02:25 merged: 2023-11-01 20:45:52

7. [43136](http://github.com/cms-sw/cmssw/pull/43136){:target="_blank"}  from **@smuzaffar**: [DB]Clang format change needed by LLVM17 `db` `tracking` created: 2023-10-27 14:37:52 merged: 2023-10-29 19:09:05

8. [43134](http://github.com/cms-sw/cmssw/pull/43134){:target="_blank"}  from **@smuzaffar**: [FW][LLVM17] Clang tidy warnings performance-copy/move fixed `core` created: 2023-10-27 09:18:37 merged: 2023-10-30 17:20:41

9. [43133](http://github.com/cms-sw/cmssw/pull/43133){:target="_blank"}  from **@bsunanda**: Phase2-gex173 Make 2 changes: eta sizes for GE21; Size of Tracker volume to touch CALO and BeamPipe volumes on either side `geometry` `operations` `simulation` `pdmv` `upgrade` `trk` created: 2023-10-27 08:50:35 merged: 2023-11-01 16:53:10

10. [43132](http://github.com/cms-sw/cmssw/pull/43132){:target="_blank"}  from **@fmanteca**: Add minETA selection to HLT filter RecoTracker/DeDx/plugins/HLTDeDxFilter `reconstruction` `tracking` created: 2023-10-27 07:38:40 merged: 2023-11-01 20:29:29

11. [43129](http://github.com/cms-sw/cmssw/pull/43129){:target="_blank"}  from **@saumyaphor4252**: Update Run3 MC GTs with corrected GEM geometry for GE21 demonstration chamber `alca` created: 2023-10-27 04:29:00 merged: 2023-11-01 14:17:39

12. [43128](http://github.com/cms-sw/cmssw/pull/43128){:target="_blank"}  from **@mmusich**: SiStrip Paylod Inspector: add `SiStripFedCablingComparisonTrackerMapBase` template and concrete implementations `db` `trk` created: 2023-10-26 22:14:24 merged: 2023-10-30 17:21:04

13. [43127](http://github.com/cms-sw/cmssw/pull/43127){:target="_blank"}  from **@thomreis**: Use ratio timing for CPU algorithm in ECAL CPU vs. GPU validation `reconstruction` `ecal` created: 2023-10-26 22:09:15 merged: 2023-10-30 17:21:25

14. [43126](http://github.com/cms-sw/cmssw/pull/43126){:target="_blank"}  from **@wddgit**: edmPluginHelp bug fix, crash would occur if helper plugin contains itself recursively `core` created: 2023-10-26 16:28:49 merged: 2023-11-01 14:15:08

15. [43120](http://github.com/cms-sw/cmssw/pull/43120){:target="_blank"}  from **@syuvivida**: Online DQM fed client: use rawDataRepacker for HCAL FEDIntegrity Task in HI runs `dqm` created: 2023-10-26 11:43:26 merged: 2023-10-30 17:22:35

16. [43118](http://github.com/cms-sw/cmssw/pull/43118){:target="_blank"}  from **@iarspider**: Replace deprecated hash_set with unordered_set `dqm` created: 2023-10-26 09:41:13 merged: 2023-11-01 14:10:13

17. [43116](http://github.com/cms-sw/cmssw/pull/43116){:target="_blank"}  from **@kpedro88**: fix cmsDriver arguments in testTauEmbeddingProducers `simulation` created: 2023-10-25 21:37:20 merged: 2023-10-27 12:19:31

18. [43115](http://github.com/cms-sw/cmssw/pull/43115){:target="_blank"}  from **@bsunanda**: Phase2-hgx347 Make hits for Calibration cells in the coming HGCal version `geometry` `operations` `simulation` `upgrade` created: 2023-10-25 16:35:43 merged: 2023-11-01 16:57:00

19. [43114](http://github.com/cms-sw/cmssw/pull/43114){:target="_blank"}  from **@aloeliger**: Addition of CaloSummary (CICADA) to L1 Emulation Sequences and Ntuples `l1` created: 2023-10-25 15:34:12 merged: 2023-10-29 19:20:34

20. [43110](http://github.com/cms-sw/cmssw/pull/43110){:target="_blank"}  from **@francescobrivio**: Update beamhlt client unitTests `dqm` created: 2023-10-25 12:23:26 merged: 2023-11-01 20:38:13

21. [43109](http://github.com/cms-sw/cmssw/pull/43109){:target="_blank"}  from **@artlbv**: Update the Phase-2 L1 vertex tag in the P2GT producer `l1` `upgrade` created: 2023-10-25 09:01:42 merged: 2023-11-01 20:26:48

22. [43106](http://github.com/cms-sw/cmssw/pull/43106){:target="_blank"}  from **@guitargeek**: Use likelihood fit instead of chi-square fit in DQMServices slice fits `dqm` created: 2023-10-24 22:20:16 merged: 2023-11-01 14:06:37

23. [43104](http://github.com/cms-sw/cmssw/pull/43104){:target="_blank"}  from **@iarspider**: Add missing namespace to isnan calls `dqm` `reconstruction` created: 2023-10-24 19:13:25 merged: 2023-10-27 13:33:20

24. [43102](http://github.com/cms-sw/cmssw/pull/43102){:target="_blank"}  from **@kpedro88**: argparse migration for PhysicsTools and FWLite `analysis` `core` `xpog` created: 2023-10-24 14:40:47 merged: 2023-10-27 13:29:30

25. [43100](http://github.com/cms-sw/cmssw/pull/43100){:target="_blank"}  from **@cms-tau-pog**: Enable HLT tau filtering based on jet-tags (ParticleNet) `hlt` `reconstruction` `tau` created: 2023-10-24 14:20:36 merged: 2023-10-27 13:27:50

26. [43099](http://github.com/cms-sw/cmssw/pull/43099){:target="_blank"}  from **@iarspider**: Fix Wdeprecated-copy warnings in DataFormats/Common (2nd attempt) `core` created: 2023-10-24 13:33:55 merged: 2023-11-01 14:02:36

27. [43098](http://github.com/cms-sw/cmssw/pull/43098){:target="_blank"}  from **@waredjeb**: Fix GlobalTag for dumping Fireworks Geometry `visualization` created: 2023-10-24 10:44:48 merged: 2023-10-25 02:46:44

28. [43096](http://github.com/cms-sw/cmssw/pull/43096){:target="_blank"}  from **@smuzaffar**: Control maximum number of process to run for generating validation plots `dqm` `tracking` created: 2023-10-24 08:23:40 merged: 2023-11-01 13:51:02

29. [43095](http://github.com/cms-sw/cmssw/pull/43095){:target="_blank"}  from **@saumyaphor4252**: Include HcalPFCuts Rcd in Run2,3 offline data GTs `alca` created: 2023-10-24 07:59:29 merged: 2023-10-26 15:59:19

30. [43094](http://github.com/cms-sw/cmssw/pull/43094){:target="_blank"}  from **@mmusich**: Introduce tracking and vertexing HLT validation (w.r.t TPs) for Phase 2 `dqm` `tracking` created: 2023-10-24 07:15:15 merged: 2023-10-27 13:22:59

31. [43093](http://github.com/cms-sw/cmssw/pull/43093){:target="_blank"}  from **@perrotta**: Correct url of the GEN fragment in a Pythia8Interface test and of the RelMon main page, after SSO migration `dqm` `generators` `pdmv` created: 2023-10-24 06:18:20 merged: 2023-11-01 13:48:06

32. [43092](http://github.com/cms-sw/cmssw/pull/43092){:target="_blank"}  from **@makortel**: Make empty std::optionals to work as ESProducer return value `core` created: 2023-10-23 21:51:08 merged: 2023-10-29 19:06:39

33. [43091](http://github.com/cms-sw/cmssw/pull/43091){:target="_blank"}  from **@aloeliger**: Cleanup CICADA/CaloSummary emulation and make CICADA versions available as templated plugins `l1` created: 2023-10-23 20:19:31 merged: 2023-10-24 14:14:33

34. [43090](http://github.com/cms-sw/cmssw/pull/43090){:target="_blank"}  from **@bsunanda**: Phase2-gem69 Correct GE21 eta partition sizes for the Phase2 scenarios `geometry` created: 2023-10-23 16:52:02 merged: 2023-10-24 14:16:18

35. [43089](http://github.com/cms-sw/cmssw/pull/43089){:target="_blank"}  from **@iarspider**: TestGeneratorInterfacePythia8ConcurrentGeneratorFilter: follow redirects `generators` created: 2023-10-23 13:45:43 merged: 2023-10-24 14:16:50

36. [43088](http://github.com/cms-sw/cmssw/pull/43088){:target="_blank"}  from **@iarspider**: Remove deprecated-copy warnings in DataFormats/Alignment `alca` created: 2023-10-23 13:35:47 merged: 2023-10-24 14:17:48

37. [43086](http://github.com/cms-sw/cmssw/pull/43086){:target="_blank"}  from **@iarspider**: Add missing namespace to isnan calls in in SiPixelGainCalibrationAnalysis.cc `alca` `trk` created: 2023-10-23 13:21:18 merged: 2023-10-24 14:20:38

38. [43085](http://github.com/cms-sw/cmssw/pull/43085){:target="_blank"}  from **@iarspider**: Fix deprecated-copy warnings in CondFormats/OptAlignObjects `alca` `db` created: 2023-10-23 12:28:47 merged: 2023-10-24 14:24:13

39. [43083](http://github.com/cms-sw/cmssw/pull/43083){:target="_blank"}  from **@iarspider**: Remove build warning in TrackerMap `dqm` `reconstruction` `trk` created: 2023-10-23 08:50:50 merged: 2023-11-01 13:41:17

40. [43080](http://github.com/cms-sw/cmssw/pull/43080){:target="_blank"}  from **@jeongeun**: Clean up and migrating edm::RefToBase to edm::Ptr (list 2 for RNTuple) `analysis` `reconstruction` created: 2023-10-23 03:34:06 merged: 2023-11-01 13:39:57

41. [43079](http://github.com/cms-sw/cmssw/pull/43079){:target="_blank"}  from **@michael-pitt**: Fix mismatch error in CTPPSRPAlignmentInfoAnalyzer `db` created: 2023-10-22 11:47:03 merged: 2023-10-29 23:23:03

42. [43076](http://github.com/cms-sw/cmssw/pull/43076){:target="_blank"}  from **@fwyzard**: Implement std::array-like wrapper `core` `heterogeneous` created: 2023-10-20 16:24:26 merged: 2023-10-25 02:05:36

43. [43075](http://github.com/cms-sw/cmssw/pull/43075){:target="_blank"}  from **@cerminar**: Phase-2 L1T: Fix GT packed format for Correlator e/gamma and tau objects `l1` `upgrade` created: 2023-10-20 14:55:10 merged: 2023-10-25 01:55:06

44. [43073](http://github.com/cms-sw/cmssw/pull/43073){:target="_blank"}  from **@bsunanda**: Run3-sim150 Change some of the defaults of FullSim for Test Beam simultion `simulation` created: 2023-10-20 13:57:54 merged: 2023-10-23 13:40:37

45. [43072](http://github.com/cms-sw/cmssw/pull/43072){:target="_blank"}  from **@abdoulline**: HCAL: fix applyQIEdelay() for MC timing studies    `simulation` created: 2023-10-20 12:56:17 merged: 2023-10-23 13:41:58

46. [43071](http://github.com/cms-sw/cmssw/pull/43071){:target="_blank"}  from **@bsunanda**: Phase2-TB76A Enable the TB script to produce meaningful results `simulation` `upgrade` created: 2023-10-20 11:42:30 merged: 2023-10-23 13:43:03

47. [43070](http://github.com/cms-sw/cmssw/pull/43070){:target="_blank"}  from **@iarspider**: Phase2L1CaloPFClusterEmulator: fix warnings in getEt `l1` `upgrade` created: 2023-10-20 10:43:36 merged: 2023-10-24 14:25:38

48. [43069](http://github.com/cms-sw/cmssw/pull/43069){:target="_blank"}  from **@bsunanda**: Phase2-hgx346B Next step toward calibration cell collection for HGCal in the next version of HGCal geometry replacing #43045 `geometry` `simulation` `upgrade` created: 2023-10-20 05:08:33 merged: 2023-10-23 13:47:55

49. [43068](http://github.com/cms-sw/cmssw/pull/43068){:target="_blank"}  from **@makortel**: Allow ESHandle be constructed from a whyFailedFactory of another ESHandle `core` created: 2023-10-19 19:56:54 merged: 2023-10-24 14:26:00

50. [43066](http://github.com/cms-sw/cmssw/pull/43066){:target="_blank"}  from **@bsunanda**: Run3-alca246 Update all the scripts for HCAL calibration using isolated charged particles `alca` created: 2023-10-19 14:00:24 merged: 2023-10-23 13:50:45

51. [43060](http://github.com/cms-sw/cmssw/pull/43060){:target="_blank"}  from **@nurfikri89**: [NanoAOD] Add pthatmax variable `xpog` created: 2023-10-19 08:38:15 merged: 2023-10-27 13:19:29

52. [43059](http://github.com/cms-sw/cmssw/pull/43059){:target="_blank"}  from **@mmusich**: Fix `StandaloneTrackerTopology` and providing unit tests  `alca` `db` `trk` created: 2023-10-19 08:24:10 merged: 2023-10-23 13:55:15

53. [43058](http://github.com/cms-sw/cmssw/pull/43058){:target="_blank"}  from **@alejands**: Skip EcalRawData collection in ECAL DQM in GPU WFs `dqm` `ecal` created: 2023-10-19 07:49:38 merged: 2023-10-27 13:17:56

54. [43055](http://github.com/cms-sw/cmssw/pull/43055){:target="_blank"}  from **@jeongeun**: Clean up deprecated edm::RefToBase list 1 for RNTuple `reconstruction` `simulation` created: 2023-10-19 04:47:44 merged: 2023-10-19 15:32:57

55. [43052](http://github.com/cms-sw/cmssw/pull/43052){:target="_blank"}  from **@CMSTrackerDPG**: Add storing of invalid ROC number error (errorType=36) in pixel GPU code `reconstruction` `trk` created: 2023-10-18 16:48:53 merged: 2023-10-23 13:56:17

56. [43049](http://github.com/cms-sw/cmssw/pull/43049){:target="_blank"}  from **@bsunanda**: Run3-sim149Z Update the cfg files in SimG4Core/PrintGeomInfo/test/python to avoid depreciated modules `simulation` created: 2023-10-18 12:28:43 merged: 2023-10-19 15:32:43

57. [43048](http://github.com/cms-sw/cmssw/pull/43048){:target="_blank"}  from **@civanch**: SIM: adopt cmssw for future Geant4 `simulation` created: 2023-10-18 09:03:05 merged: 2023-10-19 15:32:15

58. [43044](http://github.com/cms-sw/cmssw/pull/43044){:target="_blank"}  from **@jfernan2**: Remove deprecated std::iterator from MagneticField/Interpolation/src/bstream_iterator.h `reconstruction` created: 2023-10-17 18:00:36 merged: 2023-10-19 15:31:01

59. [43042](http://github.com/cms-sw/cmssw/pull/43042){:target="_blank"}  from **@kpedro88**: argparse migration for cmsDriver and FWCore `core` `operations` created: 2023-10-17 16:21:44 merged: 2023-10-25 01:47:25

60. [43041](http://github.com/cms-sw/cmssw/pull/43041){:target="_blank"}  from **@fwyzard**: Add the ASSERT_DEVICE_MATCHES_HOST_COLLECTION macro `heterogeneous` created: 2023-10-17 16:21:23 merged: 2023-10-19 15:09:05

61. [43039](http://github.com/cms-sw/cmssw/pull/43039){:target="_blank"}  from **@bsunanda**: Phase2-hgx346Z Modify the tester for parameter and a few scripts to test HGCal geometry `geometry` `upgrade` created: 2023-10-17 14:31:38 merged: 2023-10-19 15:30:34

62. [43038](http://github.com/cms-sw/cmssw/pull/43038){:target="_blank"}  from **@aandvalenzuela**: Fixing warning on `hgtopo[i]` uninitialized (`SimGeneral/Debugging`) in SKYLAKEAVX512 IBs `simulation` created: 2023-10-17 14:04:04 merged: 2023-10-19 15:29:58

63. [43037](http://github.com/cms-sw/cmssw/pull/43037){:target="_blank"}  from **@smuzaffar**: Use script_test_many_writeTotemDAQMapping.py from release if missing locally `alca` `db` created: 2023-10-17 13:26:47 merged: 2023-10-23 13:56:43

64. [43035](http://github.com/cms-sw/cmssw/pull/43035){:target="_blank"}  from **@makortel**: Add more tests for cmsRun argument parsing `core` created: 2023-10-17 08:48:41 merged: 2023-10-19 15:29:13

65. [43033](http://github.com/cms-sw/cmssw/pull/43033){:target="_blank"}  from **@makortel**: Updates to AlpakaCore README and tests `heterogeneous` created: 2023-10-17 08:32:26 merged: 2023-10-23 13:57:11

66. [43030](http://github.com/cms-sw/cmssw/pull/43030){:target="_blank"}  from **@smuzaffar**: Fix build errors when compiled with -O0 `alca` `dqm` `reconstruction` `db` `tracking` `trk` created: 2023-10-16 20:43:45 merged: 2023-10-19 15:28:04

67. [43029](http://github.com/cms-sw/cmssw/pull/43029){:target="_blank"}  from **@Dr15Jones**: Removed std::iterator use from DataFormats/Common `core` `reconstruction` created: 2023-10-16 16:35:08 merged: 2023-10-19 15:26:19

68. [43022](http://github.com/cms-sw/cmssw/pull/43022){:target="_blank"}  from **@missirol**: add explicit values to `l1t::GlobalObject` enum `l1` created: 2023-10-15 19:19:39 merged: 2023-10-23 13:58:40

69. [42987](http://github.com/cms-sw/cmssw/pull/42987){:target="_blank"}  from **@cms-tau-pog**: Store tau decay products in new nanoAOD table `reconstruction` `xpog` created: 2023-10-11 12:19:18 merged: 2023-10-19 15:24:28

70. [42970](http://github.com/cms-sw/cmssw/pull/42970){:target="_blank"}  from **@Dr15Jones**: Tracer can output a compact tracing log file `core` created: 2023-10-09 20:35:24 merged: 2023-10-29 18:03:58

71. [42964](http://github.com/cms-sw/cmssw/pull/42964){:target="_blank"}  from **@quinnanm**: AXOL1TL anomaly detection emulator for cms-sw `l1` created: 2023-10-06 19:00:44 merged: 2023-10-23 14:01:31

72. [42930](http://github.com/cms-sw/cmssw/pull/42930){:target="_blank"}  from **@thomreis**: Add ECAL portable data formats, collections and conditions for alpaka `alca` `reconstruction` `simulation` `db` `heterogeneous` `ecal` created: 2023-10-02 15:35:48 merged: 2023-11-01 13:35:31

73. [42807](http://github.com/cms-sw/cmssw/pull/42807){:target="_blank"}  from **@fllor**: Add Alpaka implementation of PFRecHitProducer `reconstruction` `heterogeneous` `pf` created: 2023-09-18 10:28:00 merged: 2023-10-27 13:11:57

74. [42756](http://github.com/cms-sw/cmssw/pull/42756){:target="_blank"}  from **@iarspider**: Fix heap-buffer-overflow in OnlineDQMDigiAD (#42445) `dqm` created: 2023-09-12 09:22:25 merged: 2023-11-01 14:37:54

75. [42518](http://github.com/cms-sw/cmssw/pull/42518){:target="_blank"}  from **@waredjeb**: Improve MC truth information in TICL, Sim-Reco Associators, TICLDumper `dqm` `reconstruction` `simulation` `upgrade` `tracking` `trk` created: 2023-08-09 09:07:27 merged: 2023-10-27 12:58:58

76. [42238](http://github.com/cms-sw/cmssw/pull/42238){:target="_blank"}  from **@simonepigazzini**: Introduce autoNANO `operations` `xpog` created: 2023-07-12 08:45:06 merged: 2023-11-01 17:25:47

77. [42039](http://github.com/cms-sw/cmssw/pull/42039){:target="_blank"}  from **@rbhattacharya04**: Custom_Muon_POG_NanoAOD `pdmv` `upgrade` `xpog` created: 2023-06-21 15:46:30 merged: 2023-10-30 17:23:40

78. [41564](http://github.com/cms-sw/cmssw/pull/41564){:target="_blank"}  from **@makortel**: Make every Alpaka EDProducer to store an unsigned short int for the backend `heterogeneous` created: 2023-05-05 20:52:43 merged: 2023-10-23 14:04:56

#### CMSDIST Changes between Tags REL/CMSSW_13_3_0_pre4/el8_amd64_gcc12 and REL/CMSSW_13_3_0_pre5/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_13_3_0_pre4/el8_amd64_gcc12...REL/CMSSW_13_3_0_pre5/el8_amd64_gcc12)



1. [8800](http://github.com/cms-sw/cmsdist/pull/8800){:target="_blank"}  from **@cms-sw**: Update tag for DQM-Integration to V00-05-00 created: 2023-11-01 20:34:20 merged: 2023-11-01 20:35:57

2. [8793](http://github.com/cms-sw/cmsdist/pull/8793){:target="_blank"}  from **@belforte**: Update crab-dev to v3.230130 created: 2023-10-30 11:48:33 merged: 2023-10-30 16:35:28

3. [8792](http://github.com/cms-sw/cmsdist/pull/8792){:target="_blank"}  from **@belforte**: bump CRABClient v3.231010 to prod. Previos prod to pre created: 2023-10-27 20:12:05 merged: 2023-10-28 12:51:34

4. [8791](http://github.com/cms-sw/cmsdist/pull/8791){:target="_blank"}  from **@cms-sw**: [LLVM] Update to version 17.0.3 created: 2023-10-27 15:16:12 merged: 2023-10-31 13:10:44

5. [8790](http://github.com/cms-sw/cmsdist/pull/8790){:target="_blank"}  from **@cms-sw**: [SCRAM] Monir update to fix the config tag mismatch error message created: 2023-10-27 10:15:21 merged: 2023-10-27 15:11:34

6. [8789](http://github.com/cms-sw/cmsdist/pull/8789){:target="_blank"}  from **@cms-sw**: [Geant4] G4TransportationWithMsc: Always update momentum direction created: 2023-10-27 07:52:33 merged: 2023-10-28 11:20:03

7. [8788](http://github.com/cms-sw/cmsdist/pull/8788){:target="_blank"}  from **@cms-sw**: [XRootD] Update to version 5.6.2 created: 2023-10-26 16:10:45 merged: 2023-10-27 07:23:50

8. [8786](http://github.com/cms-sw/cmsdist/pull/8786){:target="_blank"}  from **@thesps**: Update conifer version created: 2023-10-26 14:11:11 merged: 2023-10-27 07:26:42

9. [8782](http://github.com/cms-sw/cmsdist/pull/8782){:target="_blank"}  from **@fwyzard**: Mark the `TriangularSolverMatrix` "kernel" functions as `EIGEN_DEVICE_FUNC` created: 2023-10-24 06:19:28 merged: 2023-10-25 07:00:24

10. [8781](http://github.com/cms-sw/cmsdist/pull/8781){:target="_blank"}  from **@aloeliger**: Update CICADA version created: 2023-10-23 14:18:46 merged: 2023-10-24 14:15:04

11. [8780](http://github.com/cms-sw/cmsdist/pull/8780){:target="_blank"}  from **@thesps**: Add conifer external created: 2023-10-23 13:30:27 merged: 2023-10-25 09:04:35

12. [8775](http://github.com/cms-sw/cmsdist/pull/8775){:target="_blank"}  from **@cms-sw**: [G4] Reorder the vecgeom flag to avoid automatic forward port created: 2023-10-20 13:40:42 merged: 2023-10-20 13:41:06

13. [8772](http://github.com/cms-sw/cmsdist/pull/8772){:target="_blank"}  from **@cms-sw**: clhep: Build with c++17 i.e. default std used for building cmssw created: 2023-10-19 11:09:38 merged: 2023-10-20 14:17:09

14. [8771](http://github.com/cms-sw/cmsdist/pull/8771){:target="_blank"}  from **@cms-sw**: cms-git-tools: Introduce cms-squash-topic created: 2023-10-19 10:54:36 merged: 2023-10-20 12:13:51

15. [8767](http://github.com/cms-sw/cmsdist/pull/8767){:target="_blank"}  from **@fwyzard**: Update CUDA to support Pascal, Volta, Turing, Ampere and Lovelace GPUs created: 2023-10-18 09:24:56 merged: 2023-10-20 12:14:58
