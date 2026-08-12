---
layout: post
rel_link:  "20_1_0_pre2"
title:  "CMSSW_20_1_0_pre2"
date:   2026-08-11 14:17:43
categories: cmssw
relmajor: 20
relminor: 1
relsubminor: 0
relpre: _pre2
---

# CMSSW_20_1_0_pre2
#### Changes since CMSSW_20_1_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_20_1_0_pre1...CMSSW_20_1_0_pre2)



1. [51668](http://github.com/cms-sw/cmssw/pull/51668){:target="_blank"}  from **@felicepantaleo**: RecoEgamma: drop the TICLGeom ES producers from the HGC egamma PAT task `reconstruction` created: 2026-08-11 09:36:50 merged: 2026-08-11 11:02:22

2. [51667](http://github.com/cms-sw/cmssw/pull/51667){:target="_blank"}  from **@mmusich**: comment failing wf 37834.0 until there is a suitable PU library `pdmv` created: 2026-08-11 07:03:51 merged: 2026-08-11 08:39:52

3. [51660](http://github.com/cms-sw/cmssw/pull/51660){:target="_blank"}  from **@felicepantaleo**: Keep the HGCal e/gamma and tau ID host helpers on RecHitTools `reconstruction` created: 2026-08-10 13:54:54 merged: 2026-08-10 20:00:39

4. [51657](http://github.com/cms-sw/cmssw/pull/51657){:target="_blank"}  from @felicepantaleo: TICLGeom: do not schedule the **@alpaka** geometry ES producers in FastSim `reconstruction` created: 2026-08-09 09:33:08 merged: 2026-08-09 20:18:38

5. [51647](http://github.com/cms-sw/cmssw/pull/51647){:target="_blank"}  from **@felicepantaleo**: Fix the detector-only validation and the heavy-ion hit index after #51562 `dqm` `generators` `simulation` created: 2026-08-07 13:17:50 merged: 2026-08-09 06:15:29

6. [51635](http://github.com/cms-sw/cmssw/pull/51635){:target="_blank"}  from **@sbein**: Fix FastSim NanoAOD jet row links `xpog` created: 2026-08-05 18:47:16 merged: 2026-08-09 16:08:13

7. [51634](http://github.com/cms-sw/cmssw/pull/51634){:target="_blank"}  from **@Dr15Jones**: Make Worker only if module uses the transition `core` created: 2026-08-05 18:05:07 merged: 2026-08-06 20:40:38

8. [51633](http://github.com/cms-sw/cmssw/pull/51633){:target="_blank"}  from **@kpedro88**: Move Run 4 default to D127 `db` `geometry` `operations` `pdmv` created: 2026-08-05 15:55:48 merged: 2026-08-10 08:47:43

9. [51632](http://github.com/cms-sw/cmssw/pull/51632){:target="_blank"}  from **@smuzaffar**: METAlgorithms: Cleanup dependency to avoid linking TF for GenMETProducer `reconstruction` created: 2026-08-05 14:23:34 merged: 2026-08-06 20:40:14

10. [51627](http://github.com/cms-sw/cmssw/pull/51627){:target="_blank"}  from **@EmanueleCoradin**: Patch: Remove hltPhase2PixelVertices from DST_HeterogeneousReco `hlt` created: 2026-08-05 10:38:45 merged: 2026-08-05 14:04:44

11. [51618](http://github.com/cms-sw/cmssw/pull/51618){:target="_blank"}  from **@bsunanda**: Phase2-gex218 Updted the documentation in Configuration/Geometry/README.md `geometry` created: 2026-08-04 03:30:18 merged: 2026-08-04 11:05:09

12. [51617](http://github.com/cms-sw/cmssw/pull/51617){:target="_blank"}  from **@alexstrel**: Hotfix for  MD PF Clusterizer shower shape and multi-block  epilogue unit tests `reconstruction` created: 2026-08-04 02:53:24 merged: 2026-08-04 15:53:19

13. [51616](http://github.com/cms-sw/cmssw/pull/51616){:target="_blank"}  from **@Dr15Jones**: fix problem with json output for module centric view `core` created: 2026-08-03 14:37:51 merged: 2026-08-04 11:06:10

14. [51611](http://github.com/cms-sw/cmssw/pull/51611){:target="_blank"}  from **@bsunanda**: Run3-alca268 Make small changes to scripts for HCAL calibration studies `alca` created: 2026-08-02 12:03:10 merged: 2026-08-03 13:04:36

15. [51602](http://github.com/cms-sw/cmssw/pull/51602){:target="_blank"}  from **@runtingt**: Add HTXSStage1p2Filter `generators` created: 2026-07-30 17:06:15 merged: 2026-08-04 19:24:55

16. [51601](http://github.com/cms-sw/cmssw/pull/51601){:target="_blank"}  from **@bsunanda**: Phase2-gex217 Make a new scenario Run4D127 which closely matches Run4D126 except using an earlier version T35 for Tracker `geometry` `operations` `pdmv` created: 2026-07-30 14:28:48 merged: 2026-08-03 13:07:07

17. [51595](http://github.com/cms-sw/cmssw/pull/51595){:target="_blank"}  from **@JanGerritSchulz**: [NGT] Add full Secondary Vertex information to NGT Scouting Nano `hlt` created: 2026-07-29 14:21:25 merged: 2026-07-29 17:05:49

18. [51588](http://github.com/cms-sw/cmssw/pull/51588){:target="_blank"}  from **@bsunanda**: Phase2-gex214 Modify the scenario Run4D126 to accommodate the latest shielding structure in the forward region `geometry` created: 2026-07-29 09:43:25 merged: 2026-07-29 17:47:01

19. [51584](http://github.com/cms-sw/cmssw/pull/51584){:target="_blank"}  from **@waredjeb**: Accurate MIP Scaling V19 `simulation` created: 2026-07-29 08:16:12 merged: 2026-08-04 11:04:26

20. [51583](http://github.com/cms-sw/cmssw/pull/51583){:target="_blank"}  from **@Parsifal-2045**: Add `hltDumpTaggedModules` configuration dumper for heterogeneous-only configs `hlt` created: 2026-07-29 07:35:18 merged: 2026-07-30 19:52:44

21. [51580](http://github.com/cms-sw/cmssw/pull/51580){:target="_blank"}  from **@fwyzard**: Update unit tests for `edmTypeInfo` `heterogeneous` created: 2026-07-28 22:59:11 merged: 2026-07-29 17:43:23

22. [51579](http://github.com/cms-sw/cmssw/pull/51579){:target="_blank"}  from **@cms-tsg-storm**: Add an `addOnTest` for the Phase 2 HLT menu `core` `hlt` created: 2026-07-28 21:57:26 merged: 2026-07-29 17:47:47

23. [51578](http://github.com/cms-sw/cmssw/pull/51578){:target="_blank"}  from **@Dr15Jones**: Reuse the REntry when doing prompt read in RNTupleTempSource `core` created: 2026-07-28 19:35:18 merged: 2026-07-30 18:27:24

24. [51575](http://github.com/cms-sw/cmssw/pull/51575){:target="_blank"}  from **@Parsifal-2045**: Reduce GPU kernel spill due to the PixelTracking CA `reconstruction` `tracking` created: 2026-07-28 13:27:52 merged: 2026-07-30 19:51:48

25. [51571](http://github.com/cms-sw/cmssw/pull/51571){:target="_blank"}  from **@slava77**: LST: speedup ExtendT5FromDupT5 kernel `reconstruction` `tracking` created: 2026-07-28 00:44:07 merged: 2026-07-29 17:42:51

26. [51563](http://github.com/cms-sw/cmssw/pull/51563){:target="_blank"}  from **@felicepantaleo**: TICLGeom: a portable SoA geometry `alca` `db` `dqm` `generators` `hlt` `reconstruction` `simulation` `xpog` created: 2026-07-25 17:10:29 merged: 2026-08-05 16:07:35

27. [51562](http://github.com/cms-sw/cmssw/pull/51562){:target="_blank"}  from **@felicepantaleo**: Enable the MC-truth graph with configurable event-content levels `dqm` `generators` `operations` `pdmv` `simulation` created: 2026-07-25 16:53:22 merged: 2026-08-05 14:18:01

28. [51561](http://github.com/cms-sw/cmssw/pull/51561){:target="_blank"}  from **@Dr15Jones**: Output mechanisms for IOV related classes `core` created: 2026-07-25 15:15:33 merged: 2026-07-28 22:06:07

29. [51559](http://github.com/cms-sw/cmssw/pull/51559){:target="_blank"}  from **@fwyzard**: Add flag to print GPU UUIDs `heterogeneous` created: 2026-07-25 06:34:05 merged: 2026-07-28 22:05:46

30. [51558](http://github.com/cms-sw/cmssw/pull/51558){:target="_blank"}  from **@JanGerritSchulz**: [NGT] Fix loop over track SoA in L2TauTagNNProducer `hlt` created: 2026-07-24 17:52:00 merged: 2026-07-25 10:06:26

31. [51557](http://github.com/cms-sw/cmssw/pull/51557){:target="_blank"}  from **@fwyzard**: Rename GPU check macros to uppercase `geometry` `heterogeneous` `reconstruction` `simulation` `trk` created: 2026-07-24 15:35:23 merged: 2026-07-28 14:38:11

32. [51556](http://github.com/cms-sw/cmssw/pull/51556){:target="_blank"}  from **@thomreis**: Change ECAL Phase 2 TP sample type to uint16_t `ecal` `simulation` created: 2026-07-24 15:00:12 merged: 2026-07-27 10:08:09

33. [51554](http://github.com/cms-sw/cmssw/pull/51554){:target="_blank"}  from **@Electricks94**: Nested SoABlocks `heterogeneous` created: 2026-07-24 13:01:09 merged: 2026-08-02 07:28:16

34. [51551](http://github.com/cms-sw/cmssw/pull/51551){:target="_blank"}  from **@makortel**: Extend ModuleAllocMonitor testing to modules that use ExternalWork and/or Transformer `core` created: 2026-07-23 19:49:34 merged: 2026-07-27 07:24:54

35. [51550](http://github.com/cms-sw/cmssw/pull/51550){:target="_blank"}  from **@xabiercidvidal**: RecoMTD/TrackExtender: extract MTDHitMatcher standalone class `hlt` `reconstruction` created: 2026-07-23 12:15:53 merged: 2026-08-04 19:24:42

36. [51546](http://github.com/cms-sw/cmssw/pull/51546){:target="_blank"}  from **@bsunanda**: Run3-alca266 Make changes to the HCAL IsoTrack calibration method using DNN-based PU Corrections `alca` created: 2026-07-23 05:52:50 merged: 2026-07-27 08:30:07

37. [51542](http://github.com/cms-sw/cmssw/pull/51542){:target="_blank"}  from **@brandiskip**: Phase2OT L1 track validation: add fake/duplicate/track-rate plots `dqm` `trk` created: 2026-07-22 19:26:23 merged: 2026-08-04 11:36:01

38. [51540](http://github.com/cms-sw/cmssw/pull/51540){:target="_blank"}  from **@felicepantaleo**: Fix v19 HGCal ToA jitter constant and per-type time offset generation `hlt` `simulation` created: 2026-07-22 00:45:54 merged: 2026-07-24 20:42:32

39. [51539](http://github.com/cms-sw/cmssw/pull/51539){:target="_blank"}  from **@makortel**: Fix a few typos in AllocMonitor README `core` created: 2026-07-21 21:18:48 merged: 2026-07-27 08:32:31

40. [51533](http://github.com/cms-sw/cmssw/pull/51533){:target="_blank"}  from **@bsunanda**: Phase2-hgx367N Correct the documentation of the versions in Configuration/Geometry `geometry` created: 2026-07-21 10:43:13 merged: 2026-07-22 10:37:09

41. [51532](http://github.com/cms-sw/cmssw/pull/51532){:target="_blank"}  from **@thomreis**: Fix ECAL DQM warnings about missing endcap collections in Phase 2 `dqm` `ecal` `simulation` created: 2026-07-21 10:04:33 merged: 2026-07-21 16:05:19

42. [51529](http://github.com/cms-sw/cmssw/pull/51529){:target="_blank"}  from **@felicepantaleo**: Build RecHitTools per event to fix cross-stream double-free `simulation` created: 2026-07-20 13:26:53 merged: 2026-07-21 16:05:13

43. [51527](http://github.com/cms-sw/cmssw/pull/51527){:target="_blank"}  from **@SegmentLinking**: Fix SerialSync sequence for Phase-2 offline LST-seeded mkFit `reconstruction` `tracking` created: 2026-07-20 09:06:19 merged: 2026-07-20 15:31:09

44. [51524](http://github.com/cms-sw/cmssw/pull/51524){:target="_blank"}  from **@felicepantaleo**: Fix HGCal HD 200um (type 3) handling in legacy digitizer ZS and v19 local reco constants `reconstruction` `simulation` created: 2026-07-18 13:03:19 merged: 2026-07-19 18:56:28

45. [51523](http://github.com/cms-sw/cmssw/pull/51523){:target="_blank"}  from **@alexstrel**: Updated unit tests for multilayer PF clusterizers `pf` `reconstruction` created: 2026-07-18 04:20:28 merged: 2026-07-28 18:23:07

46. [51519](http://github.com/cms-sw/cmssw/pull/51519){:target="_blank"}  from **@raoatifshad**: [WarningFix]Fix clang thread-safety warning in DQMEDAnalyzer.h `dqm` created: 2026-07-17 09:46:34 merged: 2026-07-20 15:29:48

47. [51518](http://github.com/cms-sw/cmssw/pull/51518){:target="_blank"}  from **@bsunanda**: Phase2-hgx368I One step toward solving the issues in HGCalNeighbourFinder `geometry` created: 2026-07-17 05:51:44 merged: 2026-07-20 03:41:48

48. [51517](http://github.com/cms-sw/cmssw/pull/51517){:target="_blank"}  from **@pietroGru**: Update `PrimaryVertexMonitor` axes labels accordingly to track pT cut `dqm` `tracking` created: 2026-07-16 23:16:41 merged: 2026-07-21 16:05:07

49. [51513](http://github.com/cms-sw/cmssw/pull/51513){:target="_blank"}  from **@Dr15Jones**: Added ThresholdAbortAllocMonitorPreload `core` created: 2026-07-16 18:48:22 merged: 2026-07-27 08:31:59

50. [51511](http://github.com/cms-sw/cmssw/pull/51511){:target="_blank"}  from **@Dr15Jones**: Added PeriodicAllocMonitorPreload `core` created: 2026-07-16 13:21:49 merged: 2026-07-21 16:04:57

51. [51510](http://github.com/cms-sw/cmssw/pull/51510){:target="_blank"}  from **@fdoljanin**: HGCal displaced gun validations `dqm` `tracking` created: 2026-07-16 12:20:13 merged: 2026-07-22 10:38:24

52. [51508](http://github.com/cms-sw/cmssw/pull/51508){:target="_blank"}  from **@bfonta**: Minor dqm-plot improvements. `dqm` created: 2026-07-16 10:33:12 merged: 2026-07-21 16:04:48

53. [51502](http://github.com/cms-sw/cmssw/pull/51502){:target="_blank"}  from **@jfernan2**: [RECO] Changes to EventContent to make it RISCV64 compliant `operations` `reconstruction` created: 2026-07-15 16:14:14 merged: 2026-07-16 20:11:55

54. [51489](http://github.com/cms-sw/cmssw/pull/51489){:target="_blank"}  from **@fdoljanin**: Improving DisplacedParticleGun `generators` `pdmv` created: 2026-07-14 21:51:09 merged: 2026-07-27 10:47:20

55. [51488](http://github.com/cms-sw/cmssw/pull/51488){:target="_blank"}  from **@pietroGru**: Update `GeneralPurposeVertexAnalyzer` axes labels accordingly to track pT cut `alca` `trk` created: 2026-07-14 20:56:23 merged: 2026-07-16 20:11:40

56. [51486](http://github.com/cms-sw/cmssw/pull/51486){:target="_blank"}  from **@SegmentLinking**: [LST standalone] Fix ROCm compilation `reconstruction` `tracking` created: 2026-07-14 20:01:13 merged: 2026-07-16 20:12:30

57. [51483](http://github.com/cms-sw/cmssw/pull/51483){:target="_blank"}  from **@fnenna**: Move Phase2Muon type assignment to the main muon loop `reconstruction` created: 2026-07-14 16:35:30 merged: 2026-07-16 20:12:11

58. [51481](http://github.com/cms-sw/cmssw/pull/51481){:target="_blank"}  from **@missirol**: remove `CaloTriggerPrimitives_cff` import from `L1TCaloLayer1Summary_cff` `dqm` created: 2026-07-14 15:15:43 merged: 2026-07-16 20:04:46

59. [51478](http://github.com/cms-sw/cmssw/pull/51478){:target="_blank"}  from **@mroguljic**: Correct compatible det propagation in `setSecondHitPattern` `reconstruction` `tracking` created: 2026-07-14 13:52:28 merged: 2026-07-15 08:56:02

60. [51476](http://github.com/cms-sw/cmssw/pull/51476){:target="_blank"}  from **@thomreis**: Update ECAL Phase 2 sample noise correlations `ecal` `simulation` created: 2026-07-13 15:29:30 merged: 2026-07-20 03:42:09

61. [51473](http://github.com/cms-sw/cmssw/pull/51473){:target="_blank"}  from **@raoatifshad**: [WarningFix]Alignment/LaserAlignment: remove unnecessary static local `alca` `trk` created: 2026-07-13 12:07:11 merged: 2026-07-14 03:56:04

62. [51470](http://github.com/cms-sw/cmssw/pull/51470){:target="_blank"}  from **@felicepantaleo**: TruthInfo: pileup-aware truth graph during mixing `generators` created: 2026-07-12 17:22:27 merged: 2026-07-14 15:20:38

63. [51468](http://github.com/cms-sw/cmssw/pull/51468){:target="_blank"}  from **@felicepantaleo**: Clamp the CLUE3D cluster radius variance at zero `reconstruction` created: 2026-07-12 05:37:40 merged: 2026-07-14 03:54:20

64. [51467](http://github.com/cms-sw/cmssw/pull/51467){:target="_blank"}  from **@felicepantaleo**: Guard unguarded hitMap lookups in HGVHistoProducerAlgo `dqm` created: 2026-07-12 05:26:56 merged: 2026-07-14 03:56:24

65. [51466](http://github.com/cms-sw/cmssw/pull/51466){:target="_blank"}  from **@bfonta**: Add pre-selections to the Tau Validation. `dqm` created: 2026-07-11 19:12:13 merged: 2026-07-14 03:54:58

66. [51465](http://github.com/cms-sw/cmssw/pull/51465){:target="_blank"}  from **@Dr15Jones**: EventSetup Refactoring `core` created: 2026-07-11 13:47:24 merged: 2026-07-27 08:30:59

67. [51463](http://github.com/cms-sw/cmssw/pull/51463){:target="_blank"}  from **@bsunanda**: Phase2-hgx368G Modify the testing scripts for neighbour finder and implement debug in the original code `geometry` created: 2026-07-11 05:59:05 merged: 2026-07-12 08:51:41

68. [51461](http://github.com/cms-sw/cmssw/pull/51461){:target="_blank"}  from **@slava77**: Fix customiseTrackingNtuple.extendedContent to correctly pick up OOT particles `dqm` `tracking` created: 2026-07-09 19:44:46 merged: 2026-07-10 14:37:25

69. [51457](http://github.com/cms-sw/cmssw/pull/51457){:target="_blank"}  from **@Martin-Grunewald**: Remove customizeHLTFor51053 function call in HLT `hlt` created: 2026-07-09 06:24:30 merged: 2026-07-09 10:32:30

70. [51456](http://github.com/cms-sw/cmssw/pull/51456){:target="_blank"}  from **@bsunanda**: Phase2-hgx368F Protect RecHitTools in RecoLocalCalo/HGCalRecAlgos for HFNose detIDs `reconstruction` created: 2026-07-09 06:23:08 merged: 2026-07-09 14:33:46

71. [51453](http://github.com/cms-sw/cmssw/pull/51453){:target="_blank"}  from **@kopperp**: Fix: remove unused Eigen variables in RecoTracker package `reconstruction` `tracking` created: 2026-07-08 16:08:12 merged: 2026-07-10 10:03:24

72. [51451](http://github.com/cms-sw/cmssw/pull/51451){:target="_blank"}  from **@chrishanw**: Fix: parameters in ElectronSeedFitter `hlt` `reconstruction` `tracking` created: 2026-07-08 15:34:23 merged: 2026-07-09 10:33:45

73. [51443](http://github.com/cms-sw/cmssw/pull/51443){:target="_blank"}  from **@smuzaffar**: [UBSAN]BasicTrajectoryState: Initialize surface side for default constructor `reconstruction` `tracking` created: 2026-07-08 09:33:19 merged: 2026-07-08 20:30:04

74. [51439](http://github.com/cms-sw/cmssw/pull/51439){:target="_blank"}  from **@bsunanda**: Phase2-hgx368C Bug fix in Geometry/HGCalGeometry, as pointed out by Daria Selivanova and Andreas Hinzman `geometry` created: 2026-07-08 07:27:58 merged: 2026-07-08 20:29:39

75. [51433](http://github.com/cms-sw/cmssw/pull/51433){:target="_blank"}  from **@felicepantaleo**: DPGAnalysis/HGCalNanoAOD: fix candidate extra table inputs `xpog` created: 2026-07-07 12:15:25 merged: 2026-07-09 10:34:14

76. [51425](http://github.com/cms-sw/cmssw/pull/51425){:target="_blank"}  from **@ghyls**: Prevent MPI deadlock after a configuration error `heterogeneous` created: 2026-07-06 12:01:30 merged: 2026-07-16 20:04:20

77. [51424](http://github.com/cms-sw/cmssw/pull/51424){:target="_blank"}  from **@silviodonato**: Add scouting to Phase-2 HLT menu `dqm` `hlt` created: 2026-07-06 09:09:34 merged: 2026-07-09 10:33:25

78. [51400](http://github.com/cms-sw/cmssw/pull/51400){:target="_blank"}  from **@thomreis**: Add ECAL Phase 2 digis and TP digis validation `dqm` `ecal` `l1` `simulation` created: 2026-07-03 12:06:58 merged: 2026-07-08 20:28:49

79. [51395](http://github.com/cms-sw/cmssw/pull/51395){:target="_blank"}  from **@Parsifal-2045**: Add `cudaKernelStackBudget` tool and richer CUDA device information `heterogeneous` created: 2026-07-02 12:36:52 merged: 2026-07-16 20:11:20

80. [51387](http://github.com/cms-sw/cmssw/pull/51387){:target="_blank"}  from **@ljuckett**: Phase-2 Tracker DQM folder restructure `dqm` `trk` created: 2026-07-01 16:00:09 merged: 2026-07-27 08:33:17

81. [51375](http://github.com/cms-sw/cmssw/pull/51375){:target="_blank"}  from **@smuzaffar**: MatrixUtil: For --ibeos wse ibeos-lfn-sort to sort LFNs for selected lumis `pdmv` created: 2026-06-30 09:53:46 merged: 2026-07-12 08:51:28

82. [51374](http://github.com/cms-sw/cmssw/pull/51374){:target="_blank"}  from **@xabiercidvidal**: RecoMTD: extract TrackSegments into shared TimingTools header `reconstruction` created: 2026-06-29 19:29:25 merged: 2026-07-21 15:50:31

83. [51358](http://github.com/cms-sw/cmssw/pull/51358){:target="_blank"}  from **@thomreis**: Add premixing to development ECAL Phase 2 simulation `ecal` `l1` `pdmv` `reconstruction` `simulation` created: 2026-06-29 10:10:10 merged: 2026-07-10 10:02:42

84. [51339](http://github.com/cms-sw/cmssw/pull/51339){:target="_blank"}  from **@SegmentLinking**: [LST standalone] Bump CUDA compute capability to 8.0 `reconstruction` `tracking` created: 2026-06-27 13:44:00 merged: 2026-07-09 10:33:05

85. [51277](http://github.com/cms-sw/cmssw/pull/51277){:target="_blank"}  from **@makortel**: Document ActivityRegistry signals `core` created: 2026-06-22 13:50:24 merged: 2026-07-27 08:30:36

86. [51269](http://github.com/cms-sw/cmssw/pull/51269){:target="_blank"}  from **@thomreis**: Add additional processes to ECAL development matrix workflows. `ecal` `pdmv` created: 2026-06-19 15:14:04 merged: 2026-07-12 08:50:37

87. [51263](http://github.com/cms-sw/cmssw/pull/51263){:target="_blank"}  from **@artlbv**: [Phase-2 L1T] Move TauNNIdHW to the externally-built NNPuppiTauModel package `l1` created: 2026-06-19 04:39:12 merged: 2026-07-09 10:34:41

88. [51213](http://github.com/cms-sw/cmssw/pull/51213){:target="_blank"}  from **@felicepantaleo**: MC-truth graph prototype `dqm` `generators` `operations` `pdmv` `simulation` created: 2026-06-13 21:28:50 merged: 2026-07-12 08:51:00

89. [51085](http://github.com/cms-sw/cmssw/pull/51085){:target="_blank"}  from **@JanGerritSchulz**: [NGT] Improvements to Patatrack Pixel Tracking for Phase-2 `geometry` `hlt` `reconstruction` `tracking` created: 2026-05-28 17:13:06 merged: 2026-07-20 15:21:44

90. [51084](http://github.com/cms-sw/cmssw/pull/51084){:target="_blank"}  from **@jchismar**: Track Purity DNN for Phase-2 HLT `hlt` `operations` `reconstruction` `tracking` created: 2026-05-28 16:44:07 merged: 2026-07-14 14:07:41

91. [51042](http://github.com/cms-sw/cmssw/pull/51042){:target="_blank"}  from **@EmanueleCoradin**: [NGT] DNN for HP Pixel track selection `dqm` `hlt` `operations` `reconstruction` `tracking` created: 2026-05-26 20:51:07 merged: 2026-08-04 11:04:42

92. [51006](http://github.com/cms-sw/cmssw/pull/51006){:target="_blank"}  from **@bfonta**: Displaced Particle Gun `generators` `pdmv` created: 2026-05-21 00:05:51 merged: 2026-07-12 08:51:15

93. [50888](http://github.com/cms-sw/cmssw/pull/50888){:target="_blank"}  from **@Electricks94**: Add source location to SoA out of range error messages `heterogeneous` `reconstruction` created: 2026-05-05 20:22:47 merged: 2026-07-14 03:54:39

94. [50842](http://github.com/cms-sw/cmssw/pull/50842){:target="_blank"}  from **@fwyzard**: Implement `edmTypeInfo` `core` `heterogeneous` created: 2026-04-30 17:35:22 merged: 2026-07-16 20:04:05

95. [50269](http://github.com/cms-sw/cmssw/pull/50269){:target="_blank"}  from **@bfonta**: dqm-plot improvements `dqm` created: 2026-02-26 16:43:04 merged: 2026-07-14 03:55:13

96. [49637](http://github.com/cms-sw/cmssw/pull/49637){:target="_blank"}  from **@Chihwan-An**: Phase2 Single_Tau_Trigger Path Added `dqm` `hlt` created: 2025-12-16 06:35:32 merged: 2026-07-14 03:55:31

97. [45216](http://github.com/cms-sw/cmssw/pull/45216){:target="_blank"}  from **@felicepantaleo**: Introduce vFloat and float types in ParameterSets `core` created: 2024-06-13 12:39:51 merged: 2026-08-02 07:28:01

#### CMSDIST Changes between Tags REL/CMSSW_20_1_0_pre1/el9_amd64_gcc13 and REL/CMSSW_20_1_0_pre2/el9_amd64_gcc13:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_20_1_0_pre1/el9_amd64_gcc13...REL/CMSSW_20_1_0_pre2/el9_amd64_gcc13)



1. [10776](http://github.com/cms-sw/cmsdist/pull/10776){:target="_blank"}  from **@cms-sw**: cms-common: Fix cuda-setup scram project hook for new tool format created: 2026-08-10 09:01:36 merged: 2026-08-10 10:07:42

2. [10775](http://github.com/cms-sw/cmsdist/pull/10775){:target="_blank"}  from **@cms-sw**: python 3.14: scram and build rules changes created: 2026-08-10 07:33:36 merged: 2026-08-10 12:22:25

3. [10772](http://github.com/cms-sw/cmsdist/pull/10772){:target="_blank"}  from **@cms-sw**: set HIPBLASLT_TENSILE_LIBPATH to point to hipsparselt/library/gfx942 created: 2026-08-08 20:41:48 merged: 2026-08-09 20:55:34

4. [10770](http://github.com/cms-sw/cmsdist/pull/10770){:target="_blank"}  from **@quinnanm**: Update hls4mlEmulatorExtras to v1.1.7 created: 2026-08-07 14:29:43 merged: 2026-08-08 09:00:24

5. [10768](http://github.com/cms-sw/cmsdist/pull/10768){:target="_blank"}  from **@cms-sw**: ROCM: separate aotriton-images and fix gcc15/16 build errors created: 2026-08-07 09:36:56 merged: 2026-08-08 20:15:17

6. [10763](http://github.com/cms-sw/cmsdist/pull/10763){:target="_blank"}  from **@cms-sw**: fix elfutils for el8 created: 2026-08-06 06:21:31 merged: 2026-08-06 10:05:15

7. [10758](http://github.com/cms-sw/cmsdist/pull/10758){:target="_blank"}  from **@smuzaffar**: Updated root to tip of branch v6-36-00-patches created: 2026-08-04 07:48:12 merged: 2026-08-04 20:36:29

8. [10752](http://github.com/cms-sw/cmsdist/pull/10752){:target="_blank"}  from **@cms-sw**: Update tag for Configuration-Generator to V01-14-01 created: 2026-08-03 16:26:56 merged: 2026-08-03 16:26:58

9. [10751](http://github.com/cms-sw/cmsdist/pull/10751){:target="_blank"}  from **@akritkbehera**: [ROCM] Update ROCM to use theRock7.14 with rocgdb created: 2026-08-03 14:08:38 merged: 2026-08-05 12:44:42

10. [10741](http://github.com/cms-sw/cmsdist/pull/10741){:target="_blank"}  from **@sbaldu**: Update to CLUEstering `2.11.0` created: 2026-07-24 11:59:10 merged: 2026-07-27 08:21:57

11. [10739](http://github.com/cms-sw/cmsdist/pull/10739){:target="_blank"}  from **@akritkbehera**: Update vecgeom version to 2.1.1 created: 2026-07-23 10:39:55 merged: 2026-07-23 21:13:15

12. [10738](http://github.com/cms-sw/cmsdist/pull/10738){:target="_blank"}  from **@akritkbehera**: Fix Issues py-torch-rocm CI Failures related to AOTRITON  created: 2026-07-22 09:59:00 merged: 2026-07-22 16:42:24

13. [10735](http://github.com/cms-sw/cmsdist/pull/10735){:target="_blank"}  from **@Parsifal-2045**: Implement CUDA 13 flags to parallelise device-code compilation created: 2026-07-20 14:55:46 merged: 2026-07-27 08:26:21

14. [10734](http://github.com/cms-sw/cmsdist/pull/10734){:target="_blank"}  from **@akritkbehera**: [ROOT636] Updated root to tip of branch v6-36-00-patches created: 2026-07-20 14:29:25 merged: 2026-07-22 18:21:03

15. [10731](http://github.com/cms-sw/cmsdist/pull/10731){:target="_blank"}  from **@cms-sw**: Revert "configtag V09-09-07: Modify Tool_DependencyCudaDLINK for conditional linking" created: 2026-07-17 08:57:48 merged: 2026-07-17 08:58:27

16. [10730](http://github.com/cms-sw/cmsdist/pull/10730){:target="_blank"}  from **@cms-sw**: configtag V09-09-07: Modify Tool_DependencyCudaDLINK for conditional linking created: 2026-07-15 20:38:04 merged: 2026-07-16 17:07:42

17. [10729](http://github.com/cms-sw/cmsdist/pull/10729){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-FinalTrackSelectors to V01-06-01 created: 2026-07-14 20:06:38 merged: 2026-07-14 20:06:41

18. [10728](http://github.com/cms-sw/cmsdist/pull/10728){:target="_blank"}  from **@cms-sw**: rocm-libraries: change directory to correct project created: 2026-07-14 09:15:45 merged: 2026-07-14 20:07:54

19. [10727](http://github.com/cms-sw/cmsdist/pull/10727){:target="_blank"}  from **@cms-sw**: improve license checking for newly build packages created: 2026-07-13 09:25:58 merged: 2026-07-14 07:50:57

20. [10721](http://github.com/cms-sw/cmsdist/pull/10721){:target="_blank"}  from **@cms-sw**: Geant4 version 11.4.2 created: 2026-07-10 10:33:11 merged: 2026-07-11 07:29:37

21. [10718](http://github.com/cms-sw/cmsdist/pull/10718){:target="_blank"}  from **@cms-sw**: Python 3.12.13, massive update of python modules created: 2026-07-09 13:30:40 merged: 2026-07-16 19:55:22

22. [10713](http://github.com/cms-sw/cmsdist/pull/10713){:target="_blank"}  from **@cms-sw**: [libzip] Added xz dependency and scram toolfile created: 2026-07-09 10:40:44 merged: 2026-07-09 22:09:45

23. [10711](http://github.com/cms-sw/cmsdist/pull/10711){:target="_blank"}  from **@cms-sw**: Vecgeom: Update to version v2.1.0 created: 2026-07-08 10:21:16 merged: 2026-07-13 12:30:08

24. [10707](http://github.com/cms-sw/cmsdist/pull/10707){:target="_blank"}  from **@cms-sw**: install package license file in the rpm distribution created: 2026-07-06 11:20:32 merged: 2026-07-10 15:26:18
