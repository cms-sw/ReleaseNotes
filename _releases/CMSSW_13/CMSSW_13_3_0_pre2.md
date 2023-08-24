---
layout: post
rel_link:  "13_3_0_pre2"
title:  "CMSSW_13_3_0_pre2"
date:   2023-08-23 09:25:44
categories: cmssw
relmajor: 13
relminor: 3
relsubminor: 0
relpre: _pre2
---

# CMSSW_13_3_0_pre2
#### Changes since CMSSW_13_3_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_13_3_0_pre1...CMSSW_13_3_0_pre2)



1. [42623](http://github.com/cms-sw/cmssw/pull/42623){:target="_blank"}  from **@mmusich**: Fix ROC mapping in `SiPixelFEDChannelContainer_PayloadInspector` `db` `trk` created: 2023-08-22 09:31:35 merged: 2023-08-22 17:08:42

2. [42618](http://github.com/cms-sw/cmssw/pull/42618){:target="_blank"}  from **@sroychow**: Fixed channel decoding for the timeout error in SiPixelRawToClusterGPUKernel `reconstruction` `trk` created: 2023-08-21 15:40:34 merged: 2023-08-22 17:03:56

3. [42617](http://github.com/cms-sw/cmssw/pull/42617){:target="_blank"}  from **@missirol**: remove plugin template `HLTJetTagWithMatching` `hlt` created: 2023-08-21 15:21:57 merged: 2023-08-22 06:23:45

4. [42616](http://github.com/cms-sw/cmssw/pull/42616){:target="_blank"}  from **@missirol**: remove duplicate plugin `SiPixelRawToClusterCUDA` `reconstruction` `trk` created: 2023-08-21 15:08:59 merged: 2023-08-22 20:15:50

5. [42614](http://github.com/cms-sw/cmssw/pull/42614){:target="_blank"}  from **@mmusich**: remove useless customization for `siStripClusters` in phase-2 (not used) `reconstruction` `trk` created: 2023-08-21 10:10:03 merged: 2023-08-22 20:12:23

6. [42610](http://github.com/cms-sw/cmssw/pull/42610){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_2_X` (1/N) [`13_3_X`] `hlt` created: 2023-08-19 21:05:42 merged: 2023-08-20 07:06:29

7. [42608](http://github.com/cms-sw/cmssw/pull/42608){:target="_blank"}  from **@TomasKello**: Fix on the findAndChange for a new All-in-one. `alca` `trk` created: 2023-08-18 22:56:06 merged: 2023-08-22 20:10:54

8. [42604](http://github.com/cms-sw/cmssw/pull/42604){:target="_blank"}  from **@PonIlya**: Fix conddb dump functionally when destfile is specified `db` created: 2023-08-18 14:00:20 merged: 2023-08-19 19:07:14

9. [42601](http://github.com/cms-sw/cmssw/pull/42601){:target="_blank"}  from **@perrotta**: Update 2023 MC GTs `alca` created: 2023-08-18 10:24:37 merged: 2023-08-18 17:03:38

10. [42600](http://github.com/cms-sw/cmssw/pull/42600){:target="_blank"}  from **@mmusich**: Put back wf 140.6 in the relval matrix  `operations` `pdmv` `upgrade` created: 2023-08-18 07:29:42 merged: 2023-08-21 12:54:02

11. [42597](http://github.com/cms-sw/cmssw/pull/42597){:target="_blank"}  from **@Dr15Jones**: Do not use a Task with SiPixelTemplateStoreESProducer `fastsim` `alca` `dqm` `reconstruction` `tracking` `trk` created: 2023-08-17 14:43:25 merged: 2023-08-19 18:56:04

12. [42592](http://github.com/cms-sw/cmssw/pull/42592){:target="_blank"}  from **@mmusich**: `Alignment/OfflineValidation`: follow-up to `SiPixelTemplateStore` from DB to an `ESProducer` `alca` `trk` created: 2023-08-17 09:56:15 merged: 2023-08-18 17:38:03

13. [42591](http://github.com/cms-sw/cmssw/pull/42591){:target="_blank"}  from **@mmusich**: Follow-up to `pixelgpu` online DQM client and augmented `DQM/Integration` unit tests `dqm` `trk` created: 2023-08-17 09:50:42 merged: 2023-08-18 06:25:57

14. [42590](http://github.com/cms-sw/cmssw/pull/42590){:target="_blank"}  from **@Dr15Jones**: Fix ODR violation in BaseKeyed serialization `db` created: 2023-08-16 19:56:41 merged: 2023-08-22 20:05:54

15. [42586](http://github.com/cms-sw/cmssw/pull/42586){:target="_blank"}  from **@makortel**: Include plugin factory name as part duplicate plugin check `core` created: 2023-08-16 15:20:14 merged: 2023-08-21 21:00:45

16. [42584](http://github.com/cms-sw/cmssw/pull/42584){:target="_blank"}  from **@mmusich**: add default for `config` and `ComponentName` in `MkFitIterationConfigESProducer` `reconstruction` `tracking` created: 2023-08-16 14:09:11 merged: 2023-08-16 17:15:50

17. [42580](http://github.com/cms-sw/cmssw/pull/42580){:target="_blank"}  from **@mmusich**: Tk Alignment Payload Inspector: add pixel alignment comparison maps per coordinate `db` created: 2023-08-16 08:33:14 merged: 2023-08-16 15:30:27

18. [42579](http://github.com/cms-sw/cmssw/pull/42579){:target="_blank"}  from **@perrotta**: Updated ParameterDescription in EcalUncalibRecHitWorkerMultiFit.cc, and clean up some other configs `reconstruction` created: 2023-08-16 08:19:08 merged: 2023-08-17 06:26:43

19. [42578](http://github.com/cms-sw/cmssw/pull/42578){:target="_blank"}  from **@bsunanda**: Run3-gex169 Modify the scenarios to have the right SimHit distributions for HF `geometry` `upgrade` created: 2023-08-16 04:11:44 merged: 2023-08-17 06:30:25

20. [42575](http://github.com/cms-sw/cmssw/pull/42575){:target="_blank"}  from **@Dr15Jones**: Send less MessageLogger calls when doing job summary `core` created: 2023-08-15 16:17:49 merged: 2023-08-15 20:55:12

21. [42574](http://github.com/cms-sw/cmssw/pull/42574){:target="_blank"}  from **@mmusich**: Introduce PCL-like workflows for SiStrip Lorentz Angle Monitoring (and potentially calibration) `alca` `operations` `pdmv` `upgrade` `trk` created: 2023-08-15 10:17:45 merged: 2023-08-22 09:59:39

22. [42570](http://github.com/cms-sw/cmssw/pull/42570){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_0_X` (13/N) [`13_3_X`] `hlt` created: 2023-08-15 10:15:52 merged: 2023-08-15 20:00:17

23. [42568](http://github.com/cms-sw/cmssw/pull/42568){:target="_blank"}  from **@Dr15Jones**: Added option to FastMonitoringService to quiet LogInfos `daq` created: 2023-08-14 22:17:14 merged: 2023-08-15 20:04:28

24. [42567](http://github.com/cms-sw/cmssw/pull/42567){:target="_blank"}  from **@wddgit**: Remove references to main ParameterSet in DQM subsystems `dqm` `trk` created: 2023-08-14 20:17:54 merged: 2023-08-15 15:16:40

25. [42562](http://github.com/cms-sw/cmssw/pull/42562){:target="_blank"}  from **@hsert**: FirstVersionsOFdiTauHLTPaths_forPhase2 `hlt` created: 2023-08-14 07:57:37 merged: 2023-08-17 08:49:54

26. [42558](http://github.com/cms-sw/cmssw/pull/42558){:target="_blank"}  from **@cms-patatrack**: Fix elements_with_stride_nd when the index is outside the extent `heterogeneous` created: 2023-08-13 22:49:22 merged: 2023-08-14 13:24:12

27. [42557](http://github.com/cms-sw/cmssw/pull/42557){:target="_blank"}  from **@bsunanda**: Run3-hcx352B Add files to evaluate the impact of the changes made to the geometry scenarios due to SD issue in HCAL `geometry` `simulation` created: 2023-08-13 14:10:45 merged: 2023-08-14 13:32:44

28. [42556](http://github.com/cms-sw/cmssw/pull/42556){:target="_blank"}  from **@fwyzard**: Remove duplicate entry `core` created: 2023-08-13 12:38:14 merged: 2023-08-14 13:26:05

29. [42551](http://github.com/cms-sw/cmssw/pull/42551){:target="_blank"}  from **@francescobrivio**: Add 132X data and MC GTs `alca` created: 2023-08-11 20:31:19 merged: 2023-08-15 06:28:24

30. [42550](http://github.com/cms-sw/cmssw/pull/42550){:target="_blank"}  from **@bsunanda**: Run3-hcx352A Modify the sensitive detector xmls of HCAL to allow old style HF simhits `geometry` created: 2023-08-11 15:03:21 merged: 2023-08-15 15:09:05

31. [42549](http://github.com/cms-sw/cmssw/pull/42549){:target="_blank"}  from **@bsunanda**: Run3-sim146Y Modify the code to accommodate trapezoid for HF volumes `geometry` `simulation` created: 2023-08-11 14:59:22 merged: 2023-08-15 13:50:05

32. [42547](http://github.com/cms-sw/cmssw/pull/42547){:target="_blank"}  from **@acmbulla**: Added efficiencies of matched and unmatched tracks (between HLT and offline) vs LS, vs online lumi and vs PU  `dqm` `tracking` created: 2023-08-11 13:40:24 merged: 2023-08-15 15:18:41

33. [42546](http://github.com/cms-sw/cmssw/pull/42546){:target="_blank"}  from **@mmusich**: add customization function to remove check on Tracker DCS bits in Strip and Tracker DQM `dqm` `trk` created: 2023-08-11 13:03:07 merged: 2023-08-16 16:47:12

34. [42543](http://github.com/cms-sw/cmssw/pull/42543){:target="_blank"}  from **@missirol**: add `HLTFilter` template `HLTL1TMatchedJetsVBFFilter` `hlt` created: 2023-08-11 10:08:54 merged: 2023-08-11 20:34:18

35. [42542](http://github.com/cms-sw/cmssw/pull/42542){:target="_blank"}  from **@mmusich**: Add `pixelgpu` online DQM client and augment DQM/Integration unit tests `dqm` `trk` created: 2023-08-11 10:05:08 merged: 2023-08-15 15:10:59

36. [42537](http://github.com/cms-sw/cmssw/pull/42537){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_0_X` (12/N) [`13_3_X`] `hlt` created: 2023-08-11 06:22:52 merged: 2023-08-11 15:49:31

37. [42536](http://github.com/cms-sw/cmssw/pull/42536){:target="_blank"}  from **@wddgit**: Remove references to main ParameterSet in Reco* subsystem `reconstruction` created: 2023-08-10 20:54:03 merged: 2023-08-15 15:06:49

38. [42533](http://github.com/cms-sw/cmssw/pull/42533){:target="_blank"}  from **@fwyzard**: Revert the time category for re-joining threads `hlt` created: 2023-08-10 15:00:26 merged: 2023-08-11 12:25:40

39. [42532](http://github.com/cms-sw/cmssw/pull/42532){:target="_blank"}  from **@CeliaFernandez**: Include an additional input to fill standalone muon tracks in MuonIdProducer `reconstruction` created: 2023-08-10 13:41:25 merged: 2023-08-22 20:22:40

40. [42531](http://github.com/cms-sw/cmssw/pull/42531){:target="_blank"}  from **@wddgit**: Remove references to PSet in SimMuon and SimPPS `simulation` created: 2023-08-09 21:37:33 merged: 2023-08-10 15:26:42

41. [42530](http://github.com/cms-sw/cmssw/pull/42530){:target="_blank"}  from **@nhduongvn**: Fix chaining in rules and unify prefix and rules of protocols `core` created: 2023-08-09 21:27:25 merged: 2023-08-18 17:37:18

42. [42528](http://github.com/cms-sw/cmssw/pull/42528){:target="_blank"}  from **@makortel**: Replace reference to ParameterSet with explicit parameter values in HBHEDarkening `alca` `db` created: 2023-08-09 19:44:31 merged: 2023-08-15 06:33:05

43. [42520](http://github.com/cms-sw/cmssw/pull/42520){:target="_blank"}  from **@mmusich**: restrict PCA z-component axis in the tracks matched to PV (dz<0.1) `dqm` `tracking` created: 2023-08-09 14:18:27 merged: 2023-08-11 11:03:59

44. [42519](http://github.com/cms-sw/cmssw/pull/42519){:target="_blank"}  from **@waredjeb**: Fix HGCAL Layer Clusters visualization in Fireworks `visualization` created: 2023-08-09 10:38:28 merged: 2023-08-14 13:17:51

45. [42517](http://github.com/cms-sw/cmssw/pull/42517){:target="_blank"}  from **@fabiocos**: MTD Validation: add histograms for detailed material budget vs eta study `dqm` `geometry` created: 2023-08-09 09:07:04 merged: 2023-08-11 07:24:16

46. [42514](http://github.com/cms-sw/cmssw/pull/42514){:target="_blank"}  from **@Dr15Jones**: Moved creating SiPixelTemplateStore from DB to an ESProducer `alca` `dqm` `fastsim` `hlt` `reconstruction` `db` `tracking` `trk` created: 2023-08-08 21:50:17 merged: 2023-08-17 08:48:19

47. [42513](http://github.com/cms-sw/cmssw/pull/42513){:target="_blank"}  from **@makortel**: Configure SectorProcessShower objects only once in L1TMuonEndCapShowerProducer `l1` created: 2023-08-08 21:30:56 merged: 2023-08-10 16:50:16

48. [42506](http://github.com/cms-sw/cmssw/pull/42506){:target="_blank"}  from **@fabiocos**: Simulation: define PSimHit track Id offset and propagate to MTD hit categories `simulation` created: 2023-08-08 09:32:20 merged: 2023-08-10 15:31:38

49. [42502](http://github.com/cms-sw/cmssw/pull/42502){:target="_blank"}  from **@makortel**: Replace reference to ParameterSet with explicit parameter values in HcalTimeSlewEP `alca` created: 2023-08-07 20:55:51 merged: 2023-08-08 10:32:47

50. [42496](http://github.com/cms-sw/cmssw/pull/42496){:target="_blank"}  from **@bsunanda**: Run3-sim146X Try to see the impact of additional SD's of HCAL in the Run3 scenario for dd4hep `geometry` `simulation` created: 2023-08-07 16:30:08 merged: 2023-08-10 05:44:40

51. [42495](http://github.com/cms-sw/cmssw/pull/42495){:target="_blank"}  from **@mmusich**: Add `SiStripApproximateClusterCollection` as a simple format for RAW (re-vamped) `dqm` `reconstruction` `pdmv` `upgrade` `trk` created: 2023-08-07 15:28:10 merged: 2023-08-15 15:05:32

52. [42493](http://github.com/cms-sw/cmssw/pull/42493){:target="_blank"}  from **@francescobrivio**: Add 2023 HI scenarios `operations` created: 2023-08-07 14:37:16 merged: 2023-08-07 19:38:17

53. [42491](http://github.com/cms-sw/cmssw/pull/42491){:target="_blank"}  from **@lguzzi**: Phase2 HLT pixel modules duplicate removal `hlt` `tracking` created: 2023-08-07 13:59:26 merged: 2023-08-08 12:30:06

54. [42488](http://github.com/cms-sw/cmssw/pull/42488){:target="_blank"}  from **@mmusich**: Add default for `FileName` in `TfGraphDefProducer::fillDescriptions()` `reconstruction` created: 2023-08-07 12:52:56 merged: 2023-08-08 09:10:21

55. [42486](http://github.com/cms-sw/cmssw/pull/42486){:target="_blank"}  from **@mmusich**: `SiStripClusters2ApproxClusters`: run `peakFilter` only if cluster is usable `reconstruction` `trk` created: 2023-08-07 12:36:58 merged: 2023-08-08 16:43:48

56. [42485](http://github.com/cms-sw/cmssw/pull/42485){:target="_blank"}  from **@fmanteca**: Update showerParams.py in L1Trigger/CSCTriggerPrimitives `l1` created: 2023-08-07 08:50:18 merged: 2023-08-10 21:53:26

57. [42480](http://github.com/cms-sw/cmssw/pull/42480){:target="_blank"}  from **@mmusich**: RAW' workflow: rename `siStripDigisHLT` to `hltSiStripRawToDigi` `operations` `reconstruction` `pdmv` `upgrade` `tracking` `trk` created: 2023-08-06 09:08:07 merged: 2023-08-10 15:21:14

58. [42478](http://github.com/cms-sw/cmssw/pull/42478){:target="_blank"}  from **@bsunanda**: Phase2-hgx344 Resolve the issue of non-matching DetIDs from DDD and DD4hep for HGCal versions in D98 and D99 `geometry` `upgrade` created: 2023-08-06 07:53:20 merged: 2023-08-06 14:44:57

59. [42477](http://github.com/cms-sw/cmssw/pull/42477){:target="_blank"}  from **@bsunanda**: Phase2-gex168 Modify all Phase2 scenarios after fixing the HCAL SD issue `geometry` `upgrade` created: 2023-08-05 15:42:18 merged: 2023-08-06 14:51:27

60. [42476](http://github.com/cms-sw/cmssw/pull/42476){:target="_blank"}  from **@bsunanda**: Run3-gex168 Modify all Run3 scenarios after fixing the HCAL SD issue `geometry` `upgrade` created: 2023-08-05 15:39:51 merged: 2023-08-06 14:50:32

61. [42475](http://github.com/cms-sw/cmssw/pull/42475){:target="_blank"}  from **@mmusich**: Fix approximated SiStrip clusters workflow by saving SiStrip FED error information  `operations` `reconstruction` `tracking` created: 2023-08-04 20:28:32 merged: 2023-08-05 16:42:32

62. [42474](http://github.com/cms-sw/cmssw/pull/42474){:target="_blank"}  from **@CMS-LUMI-POG**: Pileup 2023 august `operations` `simulation` created: 2023-08-04 17:02:03 merged: 2023-08-05 16:43:42

63. [42473](http://github.com/cms-sw/cmssw/pull/42473){:target="_blank"}  from **@mmusich**: SiPixel payload inspector: add `SiPixelQualityBadFractionMap` `db` `trk` created: 2023-08-04 14:53:14 merged: 2023-08-06 22:08:36

64. [42472](http://github.com/cms-sw/cmssw/pull/42472){:target="_blank"}  from **@bsunanda**: Run3-sim146 Modify the utility to dump sensitive detector for DDD and DD4hep option `simulation` created: 2023-08-04 14:50:53 merged: 2023-08-05 16:37:25

65. [42469](http://github.com/cms-sw/cmssw/pull/42469){:target="_blank"}  from **@aloeliger**: Port of 2022 and 2023 L1T CaloParams testing files `l1` created: 2023-08-04 08:52:48 merged: 2023-08-18 17:35:14

66. [42466](http://github.com/cms-sw/cmssw/pull/42466){:target="_blank"}  from **@bundocka**: L1T: add puppi jet requirement for filling zpt in L1Ntuples `l1` created: 2023-08-03 17:04:17 merged: 2023-08-04 16:04:22

67. [42464](http://github.com/cms-sw/cmssw/pull/42464){:target="_blank"}  from **@gmelachr**: Changes to store Daughters of Kshort and Lambda in the miniAOD prunedGenParticle Collection `reconstruction` `xpog` created: 2023-08-03 14:33:59 merged: 2023-08-07 13:39:05

68. [42463](http://github.com/cms-sw/cmssw/pull/42463){:target="_blank"}  from **@bsunanda**: Run3-hcx352 Try to avoid wrong list of SD names of HCAL while using DD4hep `geometry` created: 2023-08-03 13:57:44 merged: 2023-08-04 13:51:22

69. [42459](http://github.com/cms-sw/cmssw/pull/42459){:target="_blank"}  from **@mmusich**: Tracker Alignment monitoring: add unbalance histograms for pointing angle in Z events `dqm` created: 2023-08-03 10:06:18 merged: 2023-08-06 15:35:23

70. [42457](http://github.com/cms-sw/cmssw/pull/42457){:target="_blank"}  from **@fwyzard**: Extend `convertToRaw` to support different input collection names `hlt` created: 2023-08-03 09:38:32 merged: 2023-08-04 13:50:31

71. [42455](http://github.com/cms-sw/cmssw/pull/42455){:target="_blank"}  from **@fabiocos**: MTD simulation: update trackId for BTL PSimHits `simulation` created: 2023-08-03 09:21:09 merged: 2023-08-04 13:50:06

72. [42447](http://github.com/cms-sw/cmssw/pull/42447){:target="_blank"}  from **@mbluj**: Use make_unique in tau modules `reconstruction` created: 2023-08-02 14:07:33 merged: 2023-08-18 17:33:14

73. [42446](http://github.com/cms-sw/cmssw/pull/42446){:target="_blank"}  from **@iarspider**: AVXVec: replace 2*insertf128 with 1*_mm256_set_m128d `reconstruction` created: 2023-08-02 10:05:06 merged: 2023-08-04 13:48:36

74. [42442](http://github.com/cms-sw/cmssw/pull/42442){:target="_blank"}  from **@bsunanda**: Phase2-hgx343 Try to retrieve missing hits in the partial wafers of HGCal for DD4Hep description `simulation` created: 2023-08-02 02:59:17 merged: 2023-08-04 13:47:33

75. [42436](http://github.com/cms-sw/cmssw/pull/42436){:target="_blank"}  from **@hatakeyamak**: Updates to PFClusterMatchedToPhotonsSelector for PF ECAL cluster calibration `reconstruction` `egamma` created: 2023-08-01 11:45:49 merged: 2023-08-04 13:46:41

76. [42431](http://github.com/cms-sw/cmssw/pull/42431){:target="_blank"}  from **@Dr15Jones**: Retrieve conditions data from an Hdf5 file `alca` `analysis` `core` `dqm` `l1` `db` `tracking` `trk` created: 2023-07-31 17:58:34 merged: 2023-08-16 08:44:56

77. [42390](http://github.com/cms-sw/cmssw/pull/42390){:target="_blank"}  from **@aloeliger**: Add bit wise unity initialization for default LUT arrays `l1` created: 2023-07-27 11:58:09 merged: 2023-08-05 16:34:48

78. [42155](http://github.com/cms-sw/cmssw/pull/42155){:target="_blank"}  from **@lutuck**: EMTF add DQM plots for unconstrained pT and dxy `dqm` `l1t` created: 2023-06-29 17:51:48 merged: 2023-08-21 15:38:39

79. [42109](http://github.com/cms-sw/cmssw/pull/42109){:target="_blank"}  from **@ericcano**: Fixes bug when SoA has not columns, only scalars. `heterogeneous` created: 2023-06-27 13:10:51 merged: 2023-08-15 20:44:51

#### CMSDIST Changes between Tags REL/CMSSW_13_3_0_pre1/el8_amd64_gcc11 and REL/CMSSW_13_3_0_pre2/el8_amd64_gcc11:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_13_3_0_pre1/el8_amd64_gcc11...REL/CMSSW_13_3_0_pre2/el8_amd64_gcc11)



1. [8662](http://github.com/cms-sw/cmsdist/pull/8662){:target="_blank"}  from **@cms-sw**: [xrootd] avoid explicitly setting UUID lib and include flags created: 2023-08-22 11:21:47 merged: 2023-08-22 18:49:20

2. [8658](http://github.com/cms-sw/cmsdist/pull/8658){:target="_blank"}  from **@iarspider**: Updated root to tip of branch v6-26-00-patches created: 2023-08-21 09:38:29 merged: 2023-08-21 21:52:03

3. [8653](http://github.com/cms-sw/cmsdist/pull/8653){:target="_blank"}  from **@cms-sw**: Update tag for DQM-Integration to V00-03-00 created: 2023-08-15 15:10:23 merged: 2023-08-15 15:38:51

4. [8649](http://github.com/cms-sw/cmsdist/pull/8649){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-TrackTrigger to V00-03-00 created: 2023-08-14 14:30:44 merged: 2023-08-15 06:37:28

5. [8645](http://github.com/cms-sw/cmsdist/pull/8645){:target="_blank"}  from **@fwyzard**: Minimal backport of fixes and updates to alpaka::Vec created: 2023-08-13 22:41:47 merged: 2023-08-14 13:24:04

6. [8639](http://github.com/cms-sw/cmsdist/pull/8639){:target="_blank"}  from **@cms-sw**: TF: keep read cpp-standard first created: 2023-08-07 11:16:17 merged: 2023-08-07 11:18:03

7. [8638](http://github.com/cms-sw/cmsdist/pull/8638){:target="_blank"}  from **@cms-sw**: SCRAMV1: Do not update scram links.db via package installation created: 2023-08-07 09:11:03 merged: 2023-08-07 20:02:40

8. [8637](http://github.com/cms-sw/cmsdist/pull/8637){:target="_blank"}  from **@cms-sw**: drop py3-py package which is now part of pytest created: 2023-08-04 17:06:03 merged: 2023-08-05 13:02:13

9. [8633](http://github.com/cms-sw/cmsdist/pull/8633){:target="_blank"}  from **@cms-sw**: Python packages: Updates versions with security fixes created: 2023-08-03 13:05:12 merged: 2023-08-04 14:44:29

10. [8630](http://github.com/cms-sw/cmsdist/pull/8630){:target="_blank"}  from **@aandvalenzuela**: Update ROOT in master with v6.26 patches created: 2023-08-02 08:57:16 merged: 2023-08-04 15:36:46

11. [8628](http://github.com/cms-sw/cmsdist/pull/8628){:target="_blank"}  from **@cms-sw**: Fasthadd: move back to master repo after merging cms-sw/cmssw#42228 created: 2023-08-02 08:16:22 merged: 2023-08-04 14:46:40

12. [8617](http://github.com/cms-sw/cmsdist/pull/8617){:target="_blank"}  from **@cms-sw**: Define c++ standard in one place created: 2023-07-27 14:39:36 merged: 2023-08-05 20:30:52

13. [8583](http://github.com/cms-sw/cmsdist/pull/8583){:target="_blank"}  from **@amadio**: Update XRootD to version 5.6.1 created: 2023-07-07 13:40:49 merged: 2023-08-21 10:09:24
