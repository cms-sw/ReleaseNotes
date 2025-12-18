---
layout: post
rel_link:  "16_0_0_pre4"
title:  "CMSSW_16_0_0_pre4"
date:   2025-12-18 05:16:30
categories: cmssw
relmajor: 16
relminor: 0
relsubminor: 0
relpre: _pre4
---

# CMSSW_16_0_0_pre4
#### Changes since CMSSW_16_0_0_pre3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_16_0_0_pre3...CMSSW_16_0_0_pre4)



1. [49658](http://github.com/cms-sw/cmssw/pull/49658){:target="_blank"}  from **@bfonta**: Enable persistency of maps and pairs of <DetId, const unsigned int>. `simulation` created: 2025-12-17 15:46:51 merged: 2025-12-17 21:44:59

2. [49657](http://github.com/cms-sw/cmssw/pull/49657){:target="_blank"}  from **@makortel**: Fix a typo in ParameterSetDescription exception message `core` created: 2025-12-17 14:58:14 merged: 2025-12-17 19:06:05

3. [49648](http://github.com/cms-sw/cmssw/pull/49648){:target="_blank"}  from **@makortel**: Extend an exception message to mention fillDescriptions() function `core` created: 2025-12-16 19:03:13 merged: 2025-12-17 08:18:26

4. [49646](http://github.com/cms-sw/cmssw/pull/49646){:target="_blank"}  from **@fwyzard**: Check that entries for missing FEDs have zero length `reconstruction` `trk` created: 2025-12-16 16:48:55 merged: 2025-12-17 08:21:00

5. [49645](http://github.com/cms-sw/cmssw/pull/49645){:target="_blank"}  from **@mmusich**: update the DQM legacy root file used in a bunch of SiStrip unit tests `alca` `dqm` `trk` created: 2025-12-16 16:44:13 merged: 2025-12-17 09:30:15

6. [49641](http://github.com/cms-sw/cmssw/pull/49641){:target="_blank"}  from **@ariostas**: Add rntupleWriteOptions param to NanoAODRNtupleOutputModule [port from RNTUPLE_X] `xpog` created: 2025-12-16 15:06:41 merged: 2025-12-17 19:07:12

7. [49638](http://github.com/cms-sw/cmssw/pull/49638){:target="_blank"}  from **@smuzaffar**: Fix for c++23 build errors `alca` `core` `reconstruction` `tracking` `trk` created: 2025-12-16 12:13:38 merged: 2025-12-17 08:21:17

8. [49636](http://github.com/cms-sw/cmssw/pull/49636){:target="_blank"}  from **@AdrianoDee**: Removing `JENKINS_PREFIX` Check from `das-up-to-nevents.py` `pdmv` created: 2025-12-16 06:30:52 merged: 2025-12-17 08:25:37

9. [49633](http://github.com/cms-sw/cmssw/pull/49633){:target="_blank"}  from **@missirol**: L1-uGT emulator: fix value of 3-muon mass with "duplicate" muons `l1` created: 2025-12-15 17:57:24 merged: 2025-12-17 21:44:38

10. [49631](http://github.com/cms-sw/cmssw/pull/49631){:target="_blank"}  from **@Dr15Jones**: Do not pass nullptr to memcpy in SiPixelRawToCusterKernel `reconstruction` `trk` created: 2025-12-15 15:49:23 merged: 2025-12-15 20:55:53

11. [49630](http://github.com/cms-sw/cmssw/pull/49630){:target="_blank"}  from **@Dr15Jones**: Initialize members of HGCalClusteringAlgoBase `reconstruction` created: 2025-12-15 15:04:29 merged: 2025-12-15 20:56:05

12. [49629](http://github.com/cms-sw/cmssw/pull/49629){:target="_blank"}  from **@Dr15Jones**: Initialize member data of SelectedBxTableOutputBranches `daq` created: 2025-12-15 14:48:18 merged: 2025-12-15 20:57:19

13. [49626](http://github.com/cms-sw/cmssw/pull/49626){:target="_blank"}  from **@smuzaffar**: [CPP23][FW] Fix for non-const lvalue reference of type E `core` created: 2025-12-13 11:33:17 merged: 2025-12-17 08:28:10

14. [49623](http://github.com/cms-sw/cmssw/pull/49623){:target="_blank"}  from **@SegmentLinking**: LST: T5-T5 Duplicate Merging `core` `reconstruction` `tracking` created: 2025-12-12 21:35:23 merged: 2025-12-16 09:37:33

15. [49622](http://github.com/cms-sw/cmssw/pull/49622){:target="_blank"}  from **@leonardogiannini**: [mkFit] fix charge flip bug in propagationToPlane `reconstruction` `tracking` created: 2025-12-12 17:16:07 merged: 2025-12-15 20:58:33

16. [49621](http://github.com/cms-sw/cmssw/pull/49621){:target="_blank"}  from **@makortel**: Fix memory leak in `auto_ptr` read rule test `core` created: 2025-12-12 16:25:45 merged: 2025-12-15 09:46:26

17. [49619](http://github.com/cms-sw/cmssw/pull/49619){:target="_blank"}  from **@sakura-ngt**: [NGT] Add `ScoutingRecHitAnalyzer` and integrate Calo RecHit monitoring into DQM for scouting 2025 era `dqm` `hlt` created: 2025-12-12 13:55:26 merged: 2025-12-17 08:20:27

18. [49614](http://github.com/cms-sw/cmssw/pull/49614){:target="_blank"}  from **@bsunanda**: Phase2-gex200 Update the V19 related scenarios using the drawings for the endcap calorimeter region `geometry` created: 2025-12-12 06:23:37 merged: 2025-12-15 06:52:29

19. [49613](http://github.com/cms-sw/cmssw/pull/49613){:target="_blank"}  from **@bsunanda**: Phase2-hgx364AA Update all the internal scenario definitions for the V19 setup `geometry` created: 2025-12-12 04:48:56 merged: 2025-12-12 09:30:05

20. [49612](http://github.com/cms-sw/cmssw/pull/49612){:target="_blank"}  from **@hjbossi**: Disable ZDC digitization for simulation. `operations` `simulation` created: 2025-12-12 04:02:19 merged: 2025-12-15 20:55:36

21. [49610](http://github.com/cms-sw/cmssw/pull/49610){:target="_blank"}  from **@mmusich**: Modernization of `FourVectorHLT` and related HLT DQM Configurations `dqm` `hlt` created: 2025-12-11 17:24:02 merged: 2025-12-17 08:28:32

22. [49609](http://github.com/cms-sw/cmssw/pull/49609){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Vertexing Validation Improvements: enhanced matching criteria, configurability, and new histograms `dqm` `simulation` `tracking` `trk` created: 2025-12-11 16:04:58 merged: 2025-12-15 09:48:46

23. [49608](http://github.com/cms-sw/cmssw/pull/49608){:target="_blank"}  from **@RSalvatico**: Fix HGCAL EM scale factor application `reconstruction` created: 2025-12-11 15:42:44 merged: 2025-12-17 08:42:13

24. [49599](http://github.com/cms-sw/cmssw/pull/49599){:target="_blank"}  from **@smorovic**: [DAQ] fix hang in single stream and thread mode `daq` created: 2025-12-11 11:19:15 merged: 2025-12-11 22:08:46

25. [49598](http://github.com/cms-sw/cmssw/pull/49598){:target="_blank"}  from **@RSalvatico**: Add MIPs sum and noise quadratic sum to HGCAL calibration cell handler `reconstruction` created: 2025-12-11 10:10:32 merged: 2025-12-15 09:49:30

26. [49597](http://github.com/cms-sw/cmssw/pull/49597){:target="_blank"}  from **@ywkao**: [HGCAL] Update SiPM typecode regex to support optional suffix `geometry` created: 2025-12-11 09:32:10 merged: 2025-12-15 09:47:08

27. [49594](http://github.com/cms-sw/cmssw/pull/49594){:target="_blank"}  from **@Dr15Jones**: Moved storage related code to FWStorage subsystem `alca` `core` `generators` `reconstruction` created: 2025-12-10 17:04:08 merged: 2025-12-15 20:57:12

28. [49593](http://github.com/cms-sw/cmssw/pull/49593){:target="_blank"}  from **@makortel**: Evolve `auto_ptr<gen::PdfInfo>`-to-`unique_ptr` read rules to avoid `std::auto_ptr` `generators` created: 2025-12-10 16:30:42 merged: 2025-12-17 08:17:47

29. [49592](http://github.com/cms-sw/cmssw/pull/49592){:target="_blank"}  from **@mkirsano**: Add pythia8 EGun producing HepMC3 event record `generators` created: 2025-12-10 14:28:58 merged: 2025-12-11 01:37:38

30. [49591](http://github.com/cms-sw/cmssw/pull/49591){:target="_blank"}  from **@martinamalberti**: MTD Validation: fix for additional plots in Primary4DVertexHarvester `dqm` created: 2025-12-10 13:43:46 merged: 2025-12-15 09:48:26

31. [49587](http://github.com/cms-sw/cmssw/pull/49587){:target="_blank"}  from **@fabiocos**: MTD validation: optional plots for entry angle in ETL `dqm` created: 2025-12-10 07:52:51 merged: 2025-12-11 20:21:05

32. [49586](http://github.com/cms-sw/cmssw/pull/49586){:target="_blank"}  from **@fwyzard**: Make host and device caching allocators independent `heterogeneous` created: 2025-12-10 07:14:00 merged: 2025-12-15 09:48:10

33. [49584](http://github.com/cms-sw/cmssw/pull/49584){:target="_blank"}  from **@bfonta**: Remove vertex smearing for CloseBy samples in the barrel. `operations` `simulation` `pdmv` created: 2025-12-09 17:33:29 merged: 2025-12-15 09:47:46

34. [49583](http://github.com/cms-sw/cmssw/pull/49583){:target="_blank"}  from **@kpedro88**: FastSim global producer `fastsim` `simulation` created: 2025-12-09 16:52:25 merged: 2025-12-10 03:17:42

35. [49581](http://github.com/cms-sw/cmssw/pull/49581){:target="_blank"}  from **@mmusich**: Define dictionaries for `X::Layout` type aliases in `DataFormats/EcalDigi` `simulation` created: 2025-12-09 15:49:33 merged: 2025-12-12 09:00:22

36. [49578](http://github.com/cms-sw/cmssw/pull/49578){:target="_blank"}  from **@Electricks94**: Propagate templates for SoABlocks `heterogeneous` created: 2025-12-09 11:34:52 merged: 2025-12-10 15:56:23

37. [49577](http://github.com/cms-sw/cmssw/pull/49577){:target="_blank"}  from **@ericcano**: Use of emit() instead of operator() for signals emission. `core` created: 2025-12-09 10:23:41 merged: 2025-12-16 09:39:58

38. [49575](http://github.com/cms-sw/cmssw/pull/49575){:target="_blank"}  from **@gabrielmscampos**: refactor: remove TH1::AddDirectory from DQMGenericClient `dqm` created: 2025-12-09 09:51:47 merged: 2025-12-15 09:47:28

39. [49573](http://github.com/cms-sw/cmssw/pull/49573){:target="_blank"}  from **@bfonta**: Fix CloseBy default configuration. `generators` created: 2025-12-09 09:27:38 merged: 2025-12-11 20:20:32

40. [49572](http://github.com/cms-sw/cmssw/pull/49572){:target="_blank"}  from **@iarspider**: Remove redefinition of EDM_ML_DEBUG from HGCalParameters.cc `geometry` created: 2025-12-09 09:09:36 merged: 2025-12-10 03:17:04

41. [49567](http://github.com/cms-sw/cmssw/pull/49567){:target="_blank"}  from **@cms-AlCaDB**: Remove TH1::AddDirectory(true) from Alignment `alca` created: 2025-12-08 11:21:50 merged: 2025-12-15 09:46:11

42. [49564](http://github.com/cms-sw/cmssw/pull/49564){:target="_blank"}  from **@kpedro88**: Triton server updates + client improvements and bug fixes `heterogeneous` created: 2025-12-06 00:09:10 merged: 2025-12-17 21:44:08

43. [49562](http://github.com/cms-sw/cmssw/pull/49562){:target="_blank"}  from **@kpedro88**: FastSim calorimetry bug fixes `fastsim` created: 2025-12-05 20:58:46 merged: 2025-12-09 08:49:29

44. [49561](http://github.com/cms-sw/cmssw/pull/49561){:target="_blank"}  from **@stahlleiton**: Extend MC list in prunedGenParticles for HIN analyses `reconstruction` `xpog` created: 2025-12-05 16:50:28 merged: 2025-12-10 13:05:04

45. [49560](http://github.com/cms-sw/cmssw/pull/49560){:target="_blank"}  from **@amecca**: TkAl add maxclusters for PV validation `alca` `trk` created: 2025-12-05 15:47:05 merged: 2025-12-15 06:53:27

46. [49559](http://github.com/cms-sw/cmssw/pull/49559){:target="_blank"}  from **@Dr15Jones**: Remove PoolSource name from generic messages `core` created: 2025-12-05 14:11:18 merged: 2025-12-06 08:17:31

47. [49558](http://github.com/cms-sw/cmssw/pull/49558){:target="_blank"}  from **@Dr15Jones**: Set rntupleStreamerMode for Wrapper of deque and list `core` created: 2025-12-05 13:51:13 merged: 2025-12-06 08:16:50

48. [49554](http://github.com/cms-sw/cmssw/pull/49554){:target="_blank"}  from **@fwyzard**: Improve heterogeneous HCAL code `alca` `reconstruction` `db` created: 2025-12-04 21:59:14 merged: 2025-12-17 15:25:28

49. [49553](http://github.com/cms-sw/cmssw/pull/49553){:target="_blank"}  from **@fwyzard**: Improve out-of-bounds error message `heterogeneous` created: 2025-12-04 21:52:29 merged: 2025-12-06 08:16:21

50. [49552](http://github.com/cms-sw/cmssw/pull/49552){:target="_blank"}  from **@smorovic**: [DAQ] Fix DTH input readout with multiple source IDs `daq` created: 2025-12-04 20:05:07 merged: 2025-12-09 08:50:20

51. [49551](http://github.com/cms-sw/cmssw/pull/49551){:target="_blank"}  from **@ariostas**: Fix NanoAODRNTupleOutputModule `xpog` created: 2025-12-04 19:07:14 merged: 2025-12-15 20:58:48

52. [49549](http://github.com/cms-sw/cmssw/pull/49549){:target="_blank"}  from **@bsunanda**: Phase2-hgx364Z Add a few utlities needed for neighbourhood findings `geometry` created: 2025-12-04 14:34:21 merged: 2025-12-06 08:17:16

53. [49548](http://github.com/cms-sw/cmssw/pull/49548){:target="_blank"}  from **@jfernan2**: [RECO] Reset AddDirectory from true to false `alca` `reconstruction` `tracking` created: 2025-12-04 12:04:55 merged: 2025-12-15 06:51:59

54. [49545](http://github.com/cms-sw/cmssw/pull/49545){:target="_blank"}  from **@fwyzard**: Reuse the device queue from produce in transform `heterogeneous` created: 2025-12-04 08:52:45 merged: 2025-12-17 08:20:01

55. [49544](http://github.com/cms-sw/cmssw/pull/49544){:target="_blank"}  from **@fwyzard**: Minor cleanup of  HeterogeneousCore/AlpakaCore `heterogeneous` created: 2025-12-04 07:13:41 merged: 2025-12-06 08:57:50

56. [49542](http://github.com/cms-sw/cmssw/pull/49542){:target="_blank"}  from **@Dr15Jones**: Safely write THF1 to file in BMixingModule `simulation` created: 2025-12-03 20:28:55 merged: 2025-12-06 16:10:47

57. [49541](http://github.com/cms-sw/cmssw/pull/49541){:target="_blank"}  from **@bsunanda**: Phase2-gex199 Modify HcalZDCDetId to add 2 functions to convert station # and phi index to channel ID and viceversa `simulation` created: 2025-12-03 18:34:42 merged: 2025-12-06 08:16:35

58. [49539](http://github.com/cms-sw/cmssw/pull/49539){:target="_blank"}  from **@Dr15Jones**: Added --use-rntuple option to runTheMatrix.py `pdmv` created: 2025-12-03 17:09:39 merged: 2025-12-09 08:48:04

59. [49537](http://github.com/cms-sw/cmssw/pull/49537){:target="_blank"}  from **@mkirsano**: Fix residualDecay code and 3 test configurations in /test `generators` created: 2025-12-03 15:58:38 merged: 2025-12-04 10:45:05

60. [49536](http://github.com/cms-sw/cmssw/pull/49536){:target="_blank"}  from **@bsunanda**: Phase2-hgx364X Correct the testing code for checking IDs of HGCal `geometry` created: 2025-12-03 12:39:51 merged: 2025-12-04 10:46:00

61. [49533](http://github.com/cms-sw/cmssw/pull/49533){:target="_blank"}  from **@jsamudio**: Fix LHEPtFilter default parameters `generators` created: 2025-12-02 22:04:58 merged: 2025-12-16 09:37:52

62. [49532](http://github.com/cms-sw/cmssw/pull/49532){:target="_blank"}  from **@Dr15Jones**: Add RNTupleTempSource and RNTupleTempOutputModule `core` created: 2025-12-02 20:44:57 merged: 2025-12-04 10:28:50

63. [49531](http://github.com/cms-sw/cmssw/pull/49531){:target="_blank"}  from **@Dr15Jones**: Use RNTuple streamer storage for deque and list `core` created: 2025-12-02 19:27:26 merged: 2025-12-04 10:28:21

64. [49530](http://github.com/cms-sw/cmssw/pull/49530){:target="_blank"}  from **@bsunanda**: Phase2-hgx364W Try to resolve the issue of wafer number mismatch in V19 geometry of HGCal `geometry` created: 2025-12-02 13:05:23 merged: 2025-12-03 09:45:53

65. [49529](http://github.com/cms-sw/cmssw/pull/49529){:target="_blank"}  from **@SegmentLinking**: LST: Creation and implementation of T4 (quadruplet) object `dqm` `hlt` `operations` `reconstruction` `tracking` created: 2025-12-02 12:27:54 merged: 2025-12-09 08:47:51

66. [49528](http://github.com/cms-sw/cmssw/pull/49528){:target="_blank"}  from **@Dr15Jones**: Add ESModule constructor info to ModuleAlloc file `core` created: 2025-12-01 22:59:25 merged: 2025-12-02 16:11:37

67. [49527](http://github.com/cms-sw/cmssw/pull/49527){:target="_blank"}  from **@lviliani**: Make the container-in-container feature optional `generators` created: 2025-12-01 17:43:14 merged: 2025-12-17 08:19:05

68. [49526](http://github.com/cms-sw/cmssw/pull/49526){:target="_blank"}  from **@Dr15Jones**: Renamed BranchAction* to TransitionAction* `core` `simulation` created: 2025-11-30 20:46:07 merged: 2025-12-02 16:10:28

69. [49522](http://github.com/cms-sw/cmssw/pull/49522){:target="_blank"}  from **@Dr15Jones**: Fix ownership of HepMC3::GenEvent `generators` `simulation` created: 2025-11-28 16:47:19 merged: 2025-12-03 06:19:56

70. [49521](http://github.com/cms-sw/cmssw/pull/49521){:target="_blank"}  from **@bsunanda**: Phase2-hgx364V Investigation of the DetId->Position->DetId issue for V19 HGCal Geometry `geometry` created: 2025-11-28 12:27:17 merged: 2025-11-29 07:00:28

71. [49517](http://github.com/cms-sw/cmssw/pull/49517){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] add "pixel-less" and "withPixels" track validation monitoring for HLT `dqm` `reconstruction` `tracking` created: 2025-11-27 15:32:54 merged: 2025-12-02 16:09:51

72. [49502](http://github.com/cms-sw/cmssw/pull/49502){:target="_blank"}  from **@smuzaffar**: [ALCA-DB] [LLVM21] Apply clang-tidy changes `alca` `db` `trk` created: 2025-11-26 14:16:38 merged: 2025-11-29 07:06:15

73. [49497](http://github.com/cms-sw/cmssw/pull/49497){:target="_blank"}  from **@smuzaffar**: [L1] [LLVM21] Apply clang-tidy changes `l1` created: 2025-11-26 14:15:36 merged: 2025-12-17 21:43:54

74. [49496](http://github.com/cms-sw/cmssw/pull/49496){:target="_blank"}  from **@smuzaffar**: [RECONSTRUCTION] [LLVM21] Apply clang-tidy changes `reconstruction` `tracking` created: 2025-11-26 14:15:27 merged: 2025-11-29 07:05:30

75. [49491](http://github.com/cms-sw/cmssw/pull/49491){:target="_blank"}  from **@smuzaffar**: [GENERATORS] [LLVM21] Apply clang-tidy changes `generators` created: 2025-11-26 14:14:19 merged: 2025-12-06 08:15:56

76. [49488](http://github.com/cms-sw/cmssw/pull/49488){:target="_blank"}  from **@smuzaffar**: [DQM-GENERATORS] [LLVM21] Apply clang-tidy changes `dqm` `generators` created: 2025-11-26 14:13:31 merged: 2025-12-06 08:58:30

77. [49487](http://github.com/cms-sw/cmssw/pull/49487){:target="_blank"}  from **@smuzaffar**: [ML] [LLVM21] Apply clang-tidy changes `ml` created: 2025-11-26 14:13:21 merged: 2025-11-29 07:01:13

78. [49479](http://github.com/cms-sw/cmssw/pull/49479){:target="_blank"}  from **@bsunanda**: Phase2-gex195 Modify several test scripts in the Simulation packages in view of changing Phase2 scenario default to D121 instead of D110 `l1` `simulation` created: 2025-11-26 10:43:14 merged: 2025-12-04 14:19:34

79. [49475](http://github.com/cms-sw/cmssw/pull/49475){:target="_blank"}  from **@fwyzard**: Trivial serialisation plugin mechanism `reconstruction` `simulation` `heterogeneous` `tracking` `trk` created: 2025-11-25 21:53:19 merged: 2025-12-17 19:06:35

80. [49474](http://github.com/cms-sw/cmssw/pull/49474){:target="_blank"}  from **@jroloff**: PF Offline DQM MiniAOD compatibility and jet calibration addition `dqm` created: 2025-11-25 21:18:41 merged: 2025-12-04 14:20:28

81. [49466](http://github.com/cms-sw/cmssw/pull/49466){:target="_blank"}  from **@abhih1**: Change threshold for ECAL DQM Laser quality plot `dqm` created: 2025-11-25 15:05:12 merged: 2025-12-02 16:08:44

82. [49429](http://github.com/cms-sw/cmssw/pull/49429){:target="_blank"}  from **@sbein**: Refined pT-based sorting of FastSim jets in NANO, Type-1 MET correction `xpog` created: 2025-11-20 22:40:47 merged: 2025-12-03 09:48:44

83. [49417](http://github.com/cms-sw/cmssw/pull/49417){:target="_blank"}  from **@thomreis**: ECAL - Get fill number and delivered lumi from LHCInfoPerFill `alca` `db` `ecal` created: 2025-11-19 11:23:00 merged: 2025-11-29 07:00:07

84. [49375](http://github.com/cms-sw/cmssw/pull/49375){:target="_blank"}  from **@bfonta**: Fix ControlledByREta in CloseByParticleGun `generators` created: 2025-11-12 14:11:16 merged: 2025-12-04 20:11:50

85. [49318](http://github.com/cms-sw/cmssw/pull/49318){:target="_blank"}  from **@mbluj**: Tau fixes to mini-to-mini `reconstruction` `xpog` created: 2025-11-05 10:07:50 merged: 2025-12-02 16:08:27

86. [49005](http://github.com/cms-sw/cmssw/pull/49005){:target="_blank"}  from **@makortel**: Add tests for `cmsTraceFunction` for various failures of the traced program `core` created: 2025-09-26 21:20:59 merged: 2025-12-03 09:47:44

87. [48817](http://github.com/cms-sw/cmssw/pull/48817){:target="_blank"}  from **@makortel**: Add test for schema evolution of auto_ptr -> unique_ptr `core` created: 2025-08-28 20:41:16 merged: 2025-12-04 09:50:05

#### CMSDIST Changes between Tags REL/CMSSW_16_0_0_pre3/el8_amd64_gcc13 and REL/CMSSW_16_0_0_pre4/el8_amd64_gcc13:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_16_0_0_pre3/el8_amd64_gcc13...REL/CMSSW_16_0_0_pre4/el8_amd64_gcc13)



1. [10255](http://github.com/cms-sw/cmsdist/pull/10255){:target="_blank"}  from **@cms-sw**: Geant4: Fix typo in member variable assignment created: 2025-12-15 21:10:06 merged: 2025-12-16 09:25:34

2. [10254](http://github.com/cms-sw/cmsdist/pull/10254){:target="_blank"}  from **@akritkbehera**: [ROOT636] Updated root to tip of branch v6-36-00-patches created: 2025-12-15 15:58:56 merged: 2025-12-15 21:10:59

3. [10248](http://github.com/cms-sw/cmsdist/pull/10248){:target="_blank"}  from **@cms-sw**: Celeritas: Remove G4VGConfig relocation from post-install created: 2025-12-10 14:35:15 merged: 2025-12-11 08:16:14

4. [10244](http://github.com/cms-sw/cmsdist/pull/10244){:target="_blank"}  from **@cms-sw**: Celeritas: 0.6.3: Use actual github release artifact created: 2025-12-08 12:47:49 merged: 2025-12-09 15:06:14

5. [10242](http://github.com/cms-sw/cmsdist/pull/10242){:target="_blank"}  from **@cms-sw**: Revert "Upgrade celeritas to v0.6.3" created: 2025-12-08 07:29:55 merged: 2025-12-08 07:30:42

6. [10241](http://github.com/cms-sw/cmsdist/pull/10241){:target="_blank"}  from **@whokion**: Upgrade celeritas to v0.6.3 created: 2025-12-04 22:17:15 merged: 2025-12-05 07:50:02

7. [10239](http://github.com/cms-sw/cmsdist/pull/10239){:target="_blank"}  from **@cms-sw**: Update tag for IOPool-Input to V00-05-00 created: 2025-12-04 10:34:47 merged: 2025-12-04 10:34:49

8. [10238](http://github.com/cms-sw/cmsdist/pull/10238){:target="_blank"}  from **@fwyzard**: Update ROCm configuration created: 2025-12-03 11:12:17 merged: 2025-12-15 11:48:18

9. [10236](http://github.com/cms-sw/cmsdist/pull/10236){:target="_blank"}  from **@raoatifshad**: cmssw-osenv: update cmssw-elX help message for extra-options created: 2025-12-02 13:38:14 merged: 2025-12-02 20:45:11

10. [10234](http://github.com/cms-sw/cmsdist/pull/10234){:target="_blank"}  from **@raoatifshad**: cms-git-tools: improved cherry picker created: 2025-12-02 12:55:49 merged: 2025-12-02 20:44:00

11. [10233](http://github.com/cms-sw/cmsdist/pull/10233){:target="_blank"}  from **@cms-sw**: Update tag for L1TriggerConfig-L1TConfigProducers to V00-02-00 created: 2025-12-02 11:35:29 merged: 2025-12-02 11:35:31

12. [10231](http://github.com/cms-sw/cmsdist/pull/10231){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-EgammaPhotonProducers to V00-06-00 created: 2025-12-02 09:54:54 merged: 2025-12-02 09:54:55

13. [10230](http://github.com/cms-sw/cmsdist/pull/10230){:target="_blank"}  from **@smuzaffar**: 16.0.X: Updated root to tip of branch v6-36-00-patches created: 2025-12-01 21:41:07 merged: 2025-12-02 20:43:05

14. [10229](http://github.com/cms-sw/cmsdist/pull/10229){:target="_blank"}  from **@cms-sw**: Update tag for PhysicsTools-PyTorch to V00-01-00 created: 2025-12-01 14:36:48 merged: 2025-12-01 14:36:50
