---
layout: post
rel_link:  "11_0_0_pre8"
title:  "CMSSW_11_0_0_pre8"
date:   2019-09-17 06:24:42
categories: cmssw
relmajor: 11
relminor: 0
relsubminor: 0
relpre: _pre8
---

# CMSSW_11_0_0_pre8
#### Changes since CMSSW_11_0_0_pre7:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_11_0_0_pre7...CMSSW_11_0_0_pre8)



1. [28006](http://github.com/cms-sw/cmssw/pull/28006){:target="_blank"}  from **@makortel**: Fix ExpandVisitor.result() to work also with an empty result `core`  created: 2019-09-16 15:58:14 merged: 2019-09-16 20:21:43



2. [27994](http://github.com/cms-sw/cmssw/pull/27994){:target="_blank"}  from **@dan131riley**: stronger edm::propagate_const const-correctness `core`  created: 2019-09-14 14:03:16 merged: 2019-09-15 20:31:02



3. [27993](http://github.com/cms-sw/cmssw/pull/27993){:target="_blank"}  from **@Dr15Jones**: Removed implicitly dropped move assignment from RectangularEtaPhiTrackingRegion `reconstruction`  created: 2019-09-13 16:21:48 merged: 2019-09-15 20:14:56



4. [27992](http://github.com/cms-sw/cmssw/pull/27992){:target="_blank"}  from **@Dr15Jones**: Explicitly declare copy assignment for bqueue `reconstruction`  created: 2019-09-13 15:47:41 merged: 2019-09-15 20:11:36



5. [27991](http://github.com/cms-sw/cmssw/pull/27991){:target="_blank"}  from **@Dr15Jones**: Removed unimplemented move constructor from StorageAccount `core`  created: 2019-09-13 15:01:11 merged: 2019-09-15 20:07:23



6. [27984](http://github.com/cms-sw/cmssw/pull/27984){:target="_blank"}  from **@mmusich**: Tracker Alignment: update PV Validation tool as used in Ultra-Legacy `alca`  created: 2019-09-12 18:32:26 merged: 2019-09-13 20:30:08



7. [27982](http://github.com/cms-sw/cmssw/pull/27982){:target="_blank"}  from **@fwyzard**: reintroduce missing lseek() for header-less files `daq`  `reconstruction`  created: 2019-09-12 15:26:46 merged: 2019-09-16 08:22:52



8. [27979](http://github.com/cms-sw/cmssw/pull/27979){:target="_blank"}  from **@bsunanda**: Run3-hgx220 Convert DDHGCalTBModule algorithm for DD4Hep `geometry`  `upgrade`  created: 2019-09-11 16:40:14 merged: 2019-09-13 07:04:14



9. [27975](http://github.com/cms-sw/cmssw/pull/27975){:target="_blank"}  from **@cms-tsg-storm**: Migration of HLT menus to CMSSW_11_0_0_pre7 template `hlt`  created: 2019-09-11 13:42:01 merged: 2019-09-12 08:55:59



10. [27971](http://github.com/cms-sw/cmssw/pull/27971){:target="_blank"}  from **@toropin**: Comments to parameters definition for HFStripFilter `reconstruction`  created: 2019-09-11 09:28:14 merged: 2019-09-12 20:01:02



11. [27969](http://github.com/cms-sw/cmssw/pull/27969){:target="_blank"}  from **@davidlange6**: remove histogrammar (obsolete package) `analysis`  created: 2019-09-11 08:03:29 merged: 2019-09-12 19:56:25



12. [27965](http://github.com/cms-sw/cmssw/pull/27965){:target="_blank"}  from **@cms-sw**: Run3-sim45 Remove reference to G4DataQuestionaire `alca`  created: 2019-09-10 20:28:52 merged: 2019-09-12 08:57:01



13. [27964](http://github.com/cms-sw/cmssw/pull/27964){:target="_blank"}  from **@bsunanda**: Run3-sim46 Add step length information for passive hits `simulation`  created: 2019-09-10 19:16:50 merged: 2019-09-12 19:58:20



14. [27963](http://github.com/cms-sw/cmssw/pull/27963){:target="_blank"}  from **@Dr15Jones**: Explicitly define move related ReferenceCounted methods `simulation`  created: 2019-09-10 18:56:00 merged: 2019-09-12 09:18:07



15. [27961](http://github.com/cms-sw/cmssw/pull/27961){:target="_blank"}  from **@Dr15Jones**: Support concurrent LuminosityBlocks in HLTrigReport `hlt`  created: 2019-09-10 15:27:50 merged: 2019-09-13 07:02:42



16. [27959](http://github.com/cms-sw/cmssw/pull/27959){:target="_blank"}  from **@kpedro88**: fix SimProducers for MT `simulation`  created: 2019-09-10 02:40:40 merged: 2019-09-12 19:57:42



17. [27954](http://github.com/cms-sw/cmssw/pull/27954){:target="_blank"}  from **@ianna**: DD4hep: Strip off Residual Namespace while Calculating the History `geometry`  created: 2019-09-09 12:25:14 merged: 2019-09-10 19:53:43



18. [27953](http://github.com/cms-sw/cmssw/pull/27953){:target="_blank"}  from **@fabiocos**: Move SimG4CMS/PPS dependency to geant4core only `simulation`  created: 2019-09-09 07:53:20 merged: 2019-09-09 20:23:28



19. [27952](http://github.com/cms-sw/cmssw/pull/27952){:target="_blank"}  from **@Dr15Jones**: Ignore sanitize options when generating CondFormat serialzations `db`  created: 2019-09-07 15:06:21 merged: 2019-09-09 20:23:40



20. [27951](http://github.com/cms-sw/cmssw/pull/27951){:target="_blank"}  from **@fabiocos**: Fix headers for check-headers errors reported in PR 27841 `analysis`  `generators`  created: 2019-09-07 14:44:16 merged: 2019-09-07 20:50:39



21. [27950](http://github.com/cms-sw/cmssw/pull/27950){:target="_blank"}  from **@hmiaozh**: HBHE: bugfix for MAHI on issue of missing SOI+4 subtraction `reconstruction`  created: 2019-09-07 01:20:06 merged: 2019-09-10 19:53:04



22. [27948](http://github.com/cms-sw/cmssw/pull/27948){:target="_blank"}  from **@wddgit**: Core support for concurrent IOVs in CondDBESSource `core`  created: 2019-09-06 19:07:40 merged: 2019-09-12 08:58:06



23. [27946](http://github.com/cms-sw/cmssw/pull/27946){:target="_blank"}  from **@ianna**: DD4hep: Legacy DD Shape ID Support and Mapping `geometry`  created: 2019-09-06 11:30:26 merged: 2019-09-10 19:55:50



24. [27944](http://github.com/cms-sw/cmssw/pull/27944){:target="_blank"}  from **@Sam-Harper**: Fixing VID return value for HEEP Trk Iso: 11_0_X `reconstruction`  created: 2019-09-06 07:43:00 merged: 2019-09-08 20:00:51



25. [27943](http://github.com/cms-sw/cmssw/pull/27943){:target="_blank"}  from **@bsunanda**: Run3-sim45 Remove reference to G4DataQuestionaire `simulation`  created: 2019-09-05 22:06:56 merged: 2019-09-08 19:58:41



26. [27941](http://github.com/cms-sw/cmssw/pull/27941){:target="_blank"}  from **@pieterdavid**: Add SiStripApvSimulationParameters database object and record `alca`  `db`  created: 2019-09-05 18:18:45 merged: 2019-09-16 08:20:25



27. [27940](http://github.com/cms-sw/cmssw/pull/27940){:target="_blank"}  from **@bsunanda**: Run3-hgx218 Conevrt one DDHGCalNoTaperEndcap algorithm to DD4Hep format `geometry`  `upgrade`  created: 2019-09-05 17:48:15 merged: 2019-09-10 19:58:12



28. [27939](http://github.com/cms-sw/cmssw/pull/27939){:target="_blank"}  from **@sbein**: Minor technical fix for FastSim de/dx LLP `fastsim`  created: 2019-09-05 17:24:52 merged: 2019-09-08 20:03:23



29. [27938](http://github.com/cms-sw/cmssw/pull/27938){:target="_blank"}  from **@bsunanda**: Run3-sim44 Make changes to conform G4/GV Comparison `geometry`  `simulation`  `upgrade`  created: 2019-09-05 16:42:23 merged: 2019-09-10 19:52:21



30. [27937](http://github.com/cms-sw/cmssw/pull/27937){:target="_blank"}  from **@fabiocos**: Add a data based relval test wf with lumi boundary crossing `pdmv`  `upgrade`  created: 2019-09-05 16:37:20 merged: 2019-09-11 08:36:31



31. [27935](http://github.com/cms-sw/cmssw/pull/27935){:target="_blank"}  from **@apsallid**: [HGCal] dEdx weights and plots `simulation`  created: 2019-09-05 10:53:59 merged: 2019-09-13 20:29:19



32. [27928](http://github.com/cms-sw/cmssw/pull/27928){:target="_blank"}  from **@fabiocos**: Add an LHE-based mc relval with multiple lumi sections and concurrent lumi settings `pdmv`  `upgrade`  created: 2019-09-04 14:50:01 merged: 2019-09-09 20:26:34



33. [27927](http://github.com/cms-sw/cmssw/pull/27927){:target="_blank"}  from **@Dr15Jones**: Explicitly removed methods implicitly ignored by compiler in FWCore/Framework `core`  created: 2019-09-04 14:30:18 merged: 2019-09-06 08:56:03



34. [27926](http://github.com/cms-sw/cmssw/pull/27926){:target="_blank"}  from **@ianna**: DD4hep: Tracker Builder, Numbering and GeometricDet pre-migration `geometry`  `upgrade`  created: 2019-09-04 12:42:04 merged: 2019-09-10 20:01:13



35. [27925](http://github.com/cms-sw/cmssw/pull/27925){:target="_blank"}  from **@aspiezia**: TAU miniaod validation/dqm `dqm`  `operations`  created: 2019-09-04 10:47:09 merged: 2019-09-08 20:12:31



36. [27922](http://github.com/cms-sw/cmssw/pull/27922){:target="_blank"}  from **@kpedro88**: fix handling of intermediate lumi values in HCAL aging `alca`  `db`  created: 2019-09-03 19:48:39 merged: 2019-09-09 20:24:17



37. [27921](http://github.com/cms-sw/cmssw/pull/27921){:target="_blank"}  from **@wddgit**: Define move assignment in SoATuple.h `core`  created: 2019-09-03 19:36:08 merged: 2019-09-06 07:53:00



38. [27909](http://github.com/cms-sw/cmssw/pull/27909){:target="_blank"}  from **@guitargeek**: Cleanup of EgammaHLTAlgos/Producers `core`  `dqm`  `hlt`  `reconstruction`  created: 2019-08-31 12:47:46 merged: 2019-09-09 20:40:09



39. [27908](http://github.com/cms-sw/cmssw/pull/27908){:target="_blank"}  from **@guitargeek**: More verbose error if plugin could not be loaded due to missing shared library `core`  `db`  created: 2019-08-31 09:06:51 merged: 2019-09-09 20:24:52



40. [27901](http://github.com/cms-sw/cmssw/pull/27901){:target="_blank"}  from **@jpata**: simplify elementLoop flow, add comments `reconstruction`  created: 2019-08-30 01:25:54 merged: 2019-09-06 08:39:11



41. [27888](http://github.com/cms-sw/cmssw/pull/27888){:target="_blank"}  from **@guitargeek**: Removing the PhysicsTools/MVATrainer package `analysis`  `core`  `reconstruction`  created: 2019-08-28 12:12:46 merged: 2019-09-12 20:07:52



42. [27886](http://github.com/cms-sw/cmssw/pull/27886){:target="_blank"}  from **@cvuosalo**: Magnetic field geometry builder DD4hep migration (part 1) `geometry`  `reconstruction`  created: 2019-08-27 20:22:31 merged: 2019-09-16 08:43:18



43. [27856](http://github.com/cms-sw/cmssw/pull/27856){:target="_blank"}  from **@mrodozov**: Fix gcc9 warnings in Reco `reconstruction`  created: 2019-08-23 16:59:13 merged: 2019-09-12 20:00:06



44. [27855](http://github.com/cms-sw/cmssw/pull/27855){:target="_blank"}  from **@mrodozov**: Fix gcc9 warning in PhysicsTools `analysis`  created: 2019-08-23 16:50:39 merged: 2019-09-08 20:14:48



45. [27854](http://github.com/cms-sw/cmssw/pull/27854){:target="_blank"}  from **@mrodozov**: Fix gcc9 warning in L1TriggerConfig `l1`  created: 2019-08-23 16:35:07 merged: 2019-09-06 08:12:19



46. [27852](http://github.com/cms-sw/cmssw/pull/27852){:target="_blank"}  from **@mrodozov**: Fix gcc9 warning in MuonAnalysis/MuonAssociators `analysis`  created: 2019-08-23 16:34:30 merged: 2019-09-08 20:10:27



47. [27850](http://github.com/cms-sw/cmssw/pull/27850){:target="_blank"}  from **@mrodozov**: Fix gcc9 warning in HeavyFlavorAnalysis/RecoDecay `analysis`  created: 2019-08-23 15:55:51 merged: 2019-09-08 20:06:30



48. [27847](http://github.com/cms-sw/cmssw/pull/27847){:target="_blank"}  from **@mrodozov**: Fix gcc9 warnings in FastSimDataFormats/L1GlobalMuonTrigger `fastsim`  created: 2019-08-23 15:18:52 merged: 2019-09-10 19:51:34



49. [27844](http://github.com/cms-sw/cmssw/pull/27844){:target="_blank"}  from **@mrodozov**: Fix gcc 9 warnings in DataFormats `alca`  `reconstruction`  created: 2019-08-23 14:32:33 merged: 2019-09-06 07:52:16



50. [27841](http://github.com/cms-sw/cmssw/pull/27841){:target="_blank"}  from **@davidlange6**: move away from boost shared_ptrs `alca`  `analysis`  `daq`  `db`  `dqm`  `generators`  `geometry`  `hlt`  `l1`  `reconstruction`  `simulation`  `xpog`  created: 2019-08-23 13:57:34 merged: 2019-09-06 19:44:27



51. [27827](http://github.com/cms-sw/cmssw/pull/27827){:target="_blank"}  from **@mrodozov**: Fix gcc9 warnings L1Trigger/GlobalCaloTrigger `l1`  created: 2019-08-22 15:53:06 merged: 2019-09-08 20:12:07



52. [27823](http://github.com/cms-sw/cmssw/pull/27823){:target="_blank"}  from **@EmyrClement**: Simulation of APV dynamic gain `simulation`  created: 2019-08-22 14:43:45 merged: 2019-09-16 08:20:15



53. [27819](http://github.com/cms-sw/cmssw/pull/27819){:target="_blank"}  from **@gouskos**: HGCAL: 1st version of hadronic reconstruction  `reconstruction`  `upgrade`  created: 2019-08-22 11:34:02 merged: 2019-09-12 20:02:21



54. [27792](http://github.com/cms-sw/cmssw/pull/27792){:target="_blank"}  from **@depasse**: ECAL : SRP and TPG tools `alca`  `db`  `l1`  created: 2019-08-19 09:06:04 merged: 2019-09-10 19:59:17



55. [27748](http://github.com/cms-sw/cmssw/pull/27748){:target="_blank"}  from **@abdoulline**: HCAL DQMOffline: adding rechits spectra with enabled cleaning    `dqm`  created: 2019-08-12 09:24:41 merged: 2019-09-13 20:29:53



56. [27673](http://github.com/cms-sw/cmssw/pull/27673){:target="_blank"}  from **@CTPPS**: SimG4CMS/PPS module for the PPS full simulation `simulation`  created: 2019-08-01 18:36:27 merged: 2019-09-08 20:13:25



57. [26592](http://github.com/cms-sw/cmssw/pull/26592){:target="_blank"}  from **@wddgit**: Implement core support for concurrent IOVs `alca`  `analysis`  `core`  `db`  created: 2019-05-01 22:07:27 merged: 2019-09-06 08:54:54



58. [25239](http://github.com/cms-sw/cmssw/pull/25239){:target="_blank"}  from **@gartung**: Convert auto_ptr to unique_ptr in SimDataFormats/GeneratorProducts. `generators`  created: 2018-11-14 20:40:24 merged: 2019-09-09 20:22:46



#### CMSDIST Changes between Tags REL/CMSSW_11_0_0_pre7/slc7_amd64_gcc820 and REL/CMSSW_11_0_0_pre8/slc7_amd64_gcc820:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_11_0_0_pre7/slc7_amd64_gcc820...REL/CMSSW_11_0_0_pre8/slc7_amd64_gcc820)



1. [5213](http://github.com/cms-sw/cmsdist/pull/5213){:target="_blank"}  from **@makortel**: Update mkFit to 2.0.1 created: 2019-09-06 18:43:11 merged: 2019-09-09 20:22:42

2. [5204](http://github.com/cms-sw/cmsdist/pull/5204){:target="_blank"}  from **@SiewYan**: Bump up openloops to 2.1.0 on 11_0_X created: 2019-09-05 10:51:58 merged: 2019-09-09 08:55:26

3. [5202](http://github.com/cms-sw/cmsdist/pull/5202){:target="_blank"}  from **@cms-sw**: [llvm] Include CXX11 vers in template args for llvm created: 2019-09-05 06:48:49 merged: 2019-09-05 09:06:31
