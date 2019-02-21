---
layout: post
rel_link:  "10_5_0_pre2"
title:  "CMSSW_10_5_0_pre2"
date:   2019-02-20 19:27:02
categories: cmssw
relmajor: 10
relminor: 5
relsubminor: 0
relpre: _pre2
---

# CMSSW_10_5_0_pre2
#### Changes since CMSSW_10_5_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_10_5_0_pre1...CMSSW_10_5_0_pre2)



1. [25974](http://github.com/cms-sw/cmssw/pull/25974){:target="_blank"}  from **@bainbrid**: Low pT electrons: bug fix for SuperCluster class `reconstruction`  created: 2019-02-19 10:58:21 merged: 2019-02-20 08:46:53



2. [25963](http://github.com/cms-sw/cmssw/pull/25963){:target="_blank"}  from **@perrotta**: Avoid a possible memory leak in PixelTripletNoTipGenerator.cc `reconstruction`  created: 2019-02-17 21:10:42 merged: 2019-02-19 08:33:13



3. [25962](http://github.com/cms-sw/cmssw/pull/25962){:target="_blank"}  from **@perrotta**: Clean-up RecoParticleFlow/PFClusterProducer `reconstruction`  created: 2019-02-17 20:46:34 merged: 2019-02-20 08:44:47



4. [25961](http://github.com/cms-sw/cmssw/pull/25961){:target="_blank"}  from **@tocheng**: Fix ECAL pedestal tag to be prompt sync and remove PPS alignment tag in GT `alca`  created: 2019-02-16 17:04:16 merged: 2019-02-16 21:47:16



5. [25960](http://github.com/cms-sw/cmssw/pull/25960){:target="_blank"}  from **@Dr15Jones**: Several fixes/improvements to LowPtGsfElectronSCProducer `reconstruction`  created: 2019-02-16 15:27:27 merged: 2019-02-18 16:26:19



6. [25958](http://github.com/cms-sw/cmssw/pull/25958){:target="_blank"}  from **@makortel**: Manage PluginFactory plugins with unique_ptr in RecoEcal and RecoLocalCalo/EcalRecProducers `reconstruction`  created: 2019-02-15 23:00:08 merged: 2019-02-18 16:20:42



7. [25956](http://github.com/cms-sw/cmssw/pull/25956){:target="_blank"}  from **@makortel**: Use unique_ptr constructor for PluginFactory plugins in RecoPixelVertexing `reconstruction`  created: 2019-02-15 21:17:56 merged: 2019-02-18 08:14:30



8. [25954](http://github.com/cms-sw/cmssw/pull/25954){:target="_blank"}  from **@Dr15Jones**: Removed unused variable from src/EcalTrivialObjectAnalyzer `alca`  created: 2019-02-15 20:47:53 merged: 2019-02-17 17:14:58



9. [25953](http://github.com/cms-sw/cmssw/pull/25953){:target="_blank"}  from **@makortel**: Pass PluginFactory plugin directly to emplace_back() in TrajectoryFilterAnalyzer `reconstruction`  created: 2019-02-15 20:44:47 merged: 2019-02-16 15:19:18



10. [25952](http://github.com/cms-sw/cmssw/pull/25952){:target="_blank"}  from **@slava77**: fastsim to use firstStepPrimaryVerticesBeforeMixing in all iter tracking classifiers `reconstruction`  created: 2019-02-15 17:29:32 merged: 2019-02-16 15:16:04



11. [25947](http://github.com/cms-sw/cmssw/pull/25947){:target="_blank"}  from **@wddgit**: Bug fix to EventSetupImpl::find `core`  created: 2019-02-14 22:22:39 merged: 2019-02-15 17:37:11



12. [25946](http://github.com/cms-sw/cmssw/pull/25946){:target="_blank"}  from **@makortel**: Use unique_ptr constructor for PluginFactory plugins RecoTauTag `reconstruction`  created: 2019-02-14 22:00:30 merged: 2019-02-15 17:36:21



13. [25945](http://github.com/cms-sw/cmssw/pull/25945){:target="_blank"}  from **@Dr15Jones**: Avoid implicit conversion problem in DTDataIntegrityTest `dqm`  created: 2019-02-14 21:28:46 merged: 2019-02-15 17:34:11



14. [25944](http://github.com/cms-sw/cmssw/pull/25944){:target="_blank"}  from **@Dr15Jones**: Removed unused variable from lambda capture in EcalDQMMonitorTask `dqm`  created: 2019-02-14 21:19:14 merged: 2019-02-15 17:33:35



15. [25943](http://github.com/cms-sw/cmssw/pull/25943){:target="_blank"}  from **@Dr15Jones**: Added missing override to ESTrendTask `dqm`  created: 2019-02-14 21:14:57 merged: 2019-02-15 17:33:07



16. [25942](http://github.com/cms-sw/cmssw/pull/25942){:target="_blank"}  from **@makortel**: Use unique_ptr constructor for PluginFactory plugins in RecoParticleFlow `reconstruction`  created: 2019-02-14 21:05:29 merged: 2019-02-15 17:32:46



17. [25941](http://github.com/cms-sw/cmssw/pull/25941){:target="_blank"}  from **@Dr15Jones**: Added missing override in L1TEMTFEventInfoClient `dqm`  created: 2019-02-14 21:04:19 merged: 2019-02-15 17:31:18



18. [25940](http://github.com/cms-sw/cmssw/pull/25940){:target="_blank"}  from **@Dr15Jones**: Removed unused RPCBxTest `dqm`  created: 2019-02-14 20:08:22 merged: 2019-02-15 17:24:16



19. [25939](http://github.com/cms-sw/cmssw/pull/25939){:target="_blank"}  from **@Dr15Jones**: Removed unnecessary iterator declarations from RPCMonitorDigi `dqm`  created: 2019-02-14 19:41:53 merged: 2019-02-15 17:26:21



20. [25938](http://github.com/cms-sw/cmssw/pull/25938){:target="_blank"}  from **@Dr15Jones**: Fixed include guard in DaqScopeModeHistosUsingDb.h `dqm`  created: 2019-02-14 19:35:23 merged: 2019-02-15 17:23:07



21. [25937](http://github.com/cms-sw/cmssw/pull/25937){:target="_blank"}  from **@Dr15Jones**: Corrected forward declaration in SiStripSpyEventMatcher `dqm`  created: 2019-02-14 19:29:20 merged: 2019-02-15 17:29:34



22. [25935](http://github.com/cms-sw/cmssw/pull/25935){:target="_blank"}  from **@Dr15Jones**: Add missing overide in HTXSRivetProducer `generators`  created: 2019-02-13 16:49:29 merged: 2019-02-20 08:21:49



23. [25934](http://github.com/cms-sw/cmssw/pull/25934){:target="_blank"}  from **@Dr15Jones**: Fix clang warnings in LzmaFile `generators`  created: 2019-02-13 16:43:53 merged: 2019-02-20 08:22:21



24. [25933](http://github.com/cms-sw/cmssw/pull/25933){:target="_blank"}  from **@Dr15Jones**: Modernized MCPdgIndexFilter `generators`  created: 2019-02-13 16:38:31 merged: 2019-02-20 08:24:39



25. [25932](http://github.com/cms-sw/cmssw/pull/25932){:target="_blank"}  from **@Dr15Jones**: Fix clang warning in AMPTHadronizer `generators`  created: 2019-02-13 16:16:47 merged: 2019-02-20 08:23:09



26. [25931](http://github.com/cms-sw/cmssw/pull/25931){:target="_blank"}  from **@Dr15Jones**: Use auto for iterator declaration in PythiaHepMCFilterGammaGamma `generators`  created: 2019-02-13 16:07:26 merged: 2019-02-20 08:41:04



27. [25929](http://github.com/cms-sw/cmssw/pull/25929){:target="_blank"}  from **@tocheng**: Update GT in CMSSW to 105X for ultra legacy `alca`  created: 2019-02-13 15:19:00 merged: 2019-02-15 17:43:32



28. [25926](http://github.com/cms-sw/cmssw/pull/25926){:target="_blank"}  from **@civanch**: Minor fix of p/pbar NIEL sampling `simulation`  created: 2019-02-13 14:32:01 merged: 2019-02-14 15:05:40



29. [25921](http://github.com/cms-sw/cmssw/pull/25921){:target="_blank"}  from **@makortel**: Manage PluginFactory plugins with unique_ptr in RecoMuon `hlt`  `reconstruction`  created: 2019-02-12 17:49:02 merged: 2019-02-15 17:40:41



30. [25920](http://github.com/cms-sw/cmssw/pull/25920){:target="_blank"}  from **@davidlange6**: python3 migration get __builtin__ from six `analysis`  `core`  `hlt`  created: 2019-02-12 17:18:31 merged: 2019-02-14 15:36:44



31. [25918](http://github.com/cms-sw/cmssw/pull/25918){:target="_blank"}  from **@makortel**: Use emplace_back() directly for PluginFactory plugins in SimFastTiming and SimTracker `simulation`  `upgrade`  created: 2019-02-12 16:44:23 merged: 2019-02-13 19:42:40



32. [25915](http://github.com/cms-sw/cmssw/pull/25915){:target="_blank"}  from **@bainbrid**: Low pT electrons: modify value maps storing Seed BDT outputs `reconstruction`  created: 2019-02-12 16:22:19 merged: 2019-02-14 21:53:03



33. [25913](http://github.com/cms-sw/cmssw/pull/25913){:target="_blank"}  from **@watson-ij**:  Geometry/GEMGeometryBuilder/src/GEMGeometryBuilderFromDDD.cc const-cast fix `geometry`  `upgrade`  created: 2019-02-12 13:16:45 merged: 2019-02-19 08:37:14



34. [25911](http://github.com/cms-sw/cmssw/pull/25911){:target="_blank"}  from **@emiglior**: Small fixes to analyzers used for phase2 tracker studies `dqm`  `geometry`  `upgrade`  created: 2019-02-12 06:31:18 merged: 2019-02-13 19:41:13



35. [25907](http://github.com/cms-sw/cmssw/pull/25907){:target="_blank"}  from **@makortel**: Add support for EDAlias as a case in SwitchProducer `core`  `simulation`  created: 2019-02-11 16:31:57 merged: 2019-02-20 10:54:57



36. [25906](http://github.com/cms-sw/cmssw/pull/25906){:target="_blank"}  from **@Dr15Jones**: Exclude additional ROOT math libraries in DataFormats/Math `reconstruction`  created: 2019-02-11 15:23:35 merged: 2019-02-11 23:11:50



37. [25902](http://github.com/cms-sw/cmssw/pull/25902){:target="_blank"}  from **@bsunanda**: Run2-sim28 Correct a cfi file to make a successful run of the overlap code `simulation`  created: 2019-02-11 08:05:07 merged: 2019-02-14 21:56:24



38. [25900](http://github.com/cms-sw/cmssw/pull/25900){:target="_blank"}  from **@makortel**: Manage PluginFactory plugins with unique_ptr in SimMuon `simulation`  `upgrade`  created: 2019-02-08 23:16:15 merged: 2019-02-13 19:39:11



39. [25899](http://github.com/cms-sw/cmssw/pull/25899){:target="_blank"}  from **@makortel**: Manage PluginFactory plugins with unique_ptr in RecoLocalMuon `reconstruction`  `upgrade`  created: 2019-02-08 22:58:41 merged: 2019-02-11 23:07:16



40. [25897](http://github.com/cms-sw/cmssw/pull/25897){:target="_blank"}  from **@ianna**: DD4Hep: DT Geometry Builder with Correct Numbering `geometry`  created: 2019-02-08 21:03:11 merged: 2019-02-11 22:58:34



41. [25896](http://github.com/cms-sw/cmssw/pull/25896){:target="_blank"}  from **@wddgit**: Use fixed order vector instead of map in EventSetup `core`  created: 2019-02-08 19:14:49 merged: 2019-02-09 20:46:04



42. [25894](http://github.com/cms-sw/cmssw/pull/25894){:target="_blank"}  from **@civanch**: Added extra protection to Geant4 SteppingAction  `simulation`  created: 2019-02-08 16:47:15 merged: 2019-02-11 22:53:43



43. [25892](http://github.com/cms-sw/cmssw/pull/25892){:target="_blank"}  from **@kfjack**: Add BPHParking skim module and the relval steps `pdmv`  `upgrade`  created: 2019-02-08 13:06:06 merged: 2019-02-16 16:19:04



44. [25890](http://github.com/cms-sw/cmssw/pull/25890){:target="_blank"}  from **@davidlange6**: pybind11 based parameter set reading tools  `core`  created: 2019-02-08 12:15:26 merged: 2019-02-19 08:30:21



45. [25888](http://github.com/cms-sw/cmssw/pull/25888){:target="_blank"}  from **@makortel**: Manage PluginFactory plugins with unique_ptr in FastSim `fastsim`  created: 2019-02-07 22:35:25 merged: 2019-02-16 16:20:30



46. [25886](http://github.com/cms-sw/cmssw/pull/25886){:target="_blank"}  from **@makortel**: Use unique_ptr in HiEgammaSCCorrectionMaker `reconstruction`  created: 2019-02-07 16:41:38 merged: 2019-02-08 09:30:58



47. [25885](http://github.com/cms-sw/cmssw/pull/25885){:target="_blank"}  from **@CMSTrackerDPG**: Add label for pixel digitizer in SiPixelQualityESProducer `alca`  `operations`  `simulation`  created: 2019-02-07 14:22:32 merged: 2019-02-19 14:49:44



48. [25882](http://github.com/cms-sw/cmssw/pull/25882){:target="_blank"}  from **@Mourtz**: Moved "FWHeatmapProxyBuilderTemplate" to Fireworks/Calo package `visualization`  created: 2019-02-07 11:12:46 merged: 2019-02-08 09:31:58



49. [25880](http://github.com/cms-sw/cmssw/pull/25880){:target="_blank"}  from **@bsunanda**: Phase2-sim27 Try to remove dependency of CLHEP in a few places and streamline the SteppingAction code for transporting to GeantV application `dqm`  `fastsim`  `geometry`  `simulation`  created: 2019-02-07 10:08:17 merged: 2019-02-13 19:38:20



50. [25878](http://github.com/cms-sw/cmssw/pull/25878){:target="_blank"}  from **@civanch**: Added new and cleaned up existing Geant4 Physics Lists `simulation`  created: 2019-02-06 18:09:40 merged: 2019-02-07 17:50:18



51. [25877](http://github.com/cms-sw/cmssw/pull/25877){:target="_blank"}  from **@Dr15Jones**: Impoved edm::ESGetToken `core`  created: 2019-02-06 17:33:55 merged: 2019-02-07 17:51:17



52. [25874](http://github.com/cms-sw/cmssw/pull/25874){:target="_blank"}  from **@hroskes**: Utilities and fixes for HipPy alignment `alca`  created: 2019-02-06 14:24:27 merged: 2019-02-19 14:48:56



53. [25873](http://github.com/cms-sw/cmssw/pull/25873){:target="_blank"}  from **@depasse**: Ecal : to dump the tags based on EcalSimPulseShapeRcd `db`  created: 2019-02-06 12:10:52 merged: 2019-02-11 22:52:33



54. [25872](http://github.com/cms-sw/cmssw/pull/25872){:target="_blank"}  from **@nwickram**: updating relvals strings `pdmv`  `upgrade`  created: 2019-02-06 11:41:36 merged: 2019-02-08 09:29:52



55. [25867](http://github.com/cms-sw/cmssw/pull/25867){:target="_blank"}  from **@makortel**: Use unique_ptr constructor for PluginFactory plugins  in L1Trigger/L1THGCal `l1`  `upgrade`  created: 2019-02-05 20:40:34 merged: 2019-02-11 23:05:20



56. [25866](http://github.com/cms-sw/cmssw/pull/25866){:target="_blank"}  from **@makortel**: Use unique_ptr constructor for PluginFactory plugin in RecoLocalFastTime/FTLRecProducers `reconstruction`  `upgrade`  created: 2019-02-05 20:24:10 merged: 2019-02-11 23:04:06



57. [25857](http://github.com/cms-sw/cmssw/pull/25857){:target="_blank"}  from **@cvuosalo**: Continue migration of Geometry code to user-defined literals `geometry`  created: 2019-02-04 23:32:30 merged: 2019-02-09 20:15:40



58. [25856](http://github.com/cms-sw/cmssw/pull/25856){:target="_blank"}  from **@smuzaffar**: added rootgeom dependency to fix UBSAN IBs `geometry`  created: 2019-02-04 16:32:58 merged: 2019-02-06 16:13:57



59. [25855](http://github.com/cms-sw/cmssw/pull/25855){:target="_blank"}  from **@gudrutis**: analysis - removing '//' from header include. `analysis`  created: 2019-02-04 15:14:28 merged: 2019-02-06 16:14:31



60. [25854](http://github.com/cms-sw/cmssw/pull/25854){:target="_blank"}  from **@gudrutis**: alca - removing '//' from header include. `alca`  `db`  created: 2019-02-04 15:14:13 merged: 2019-02-05 20:59:08



61. [25853](http://github.com/cms-sw/cmssw/pull/25853){:target="_blank"}  from **@gudrutis**: simulation - removing '//' from header include. `simulation`  created: 2019-02-04 15:13:18 merged: 2019-02-05 20:59:43



62. [25852](http://github.com/cms-sw/cmssw/pull/25852){:target="_blank"}  from **@gudrutis**: reconstruction - removing '//' from header include. `reconstruction`  created: 2019-02-04 15:13:07 merged: 2019-02-05 09:35:08



63. [25851](http://github.com/cms-sw/cmssw/pull/25851){:target="_blank"}  from **@EmyrClement**: Generate events without MPI if LBCR or CRSS performed with MPI. `generators`  created: 2019-02-04 12:55:50 merged: 2019-02-05 09:36:09



64. [25850](http://github.com/cms-sw/cmssw/pull/25850){:target="_blank"}  from **@alberto-sanchez**: fixing missing pointer between lumi boundaries `generators`  created: 2019-02-04 11:31:04 merged: 2019-02-07 09:16:52



65. [25847](http://github.com/cms-sw/cmssw/pull/25847){:target="_blank"}  from **@Dr15Jones**: Removed unused function from writeInt.cc `alca`  `db`  created: 2019-02-03 16:30:51 merged: 2019-02-04 21:13:53



66. [25846](http://github.com/cms-sw/cmssw/pull/25846){:target="_blank"}  from **@Dr15Jones**: Modernized CastorDumpConditions `db`  created: 2019-02-03 14:59:25 merged: 2019-02-04 21:14:58



67. [25845](http://github.com/cms-sw/cmssw/pull/25845){:target="_blank"}  from **@Dr15Jones**: Pass intergral value to SetLineWidth in CondCore/EcalPlugins `db`  created: 2019-02-03 14:35:09 merged: 2019-02-06 09:30:04



68. [25844](http://github.com/cms-sw/cmssw/pull/25844){:target="_blank"}  from **@Dr15Jones**: Removed unused functions in HcalQIECoder `alca`  `db`  created: 2019-02-03 14:34:48 merged: 2019-02-04 21:15:17



69. [25843](http://github.com/cms-sw/cmssw/pull/25843){:target="_blank"}  from **@Dr15Jones**: Changed forward declaration to struct in DBSpecToDetUnit `alca`  `db`  created: 2019-02-03 14:21:23 merged: 2019-02-04 21:15:38



70. [25842](http://github.com/cms-sw/cmssw/pull/25842){:target="_blank"}  from **@ianna**: DD4Hep: DT Geometry Builder `geometry`  created: 2019-02-02 14:11:48 merged: 2019-02-06 09:55:27



71. [25841](http://github.com/cms-sw/cmssw/pull/25841){:target="_blank"}  from **@makortel**: Use unique_ptr constructor for PluginFactory plugins in RecoLocalCalo/HGCalRecProducers `reconstruction`  `upgrade`  created: 2019-02-01 23:02:20 merged: 2019-02-04 21:21:23



72. [25840](http://github.com/cms-sw/cmssw/pull/25840){:target="_blank"}  from **@makortel**: Manage PluginFactory plugin with unique_ptr in DTLocalTriggerSynchTask `dqm`  created: 2019-02-01 22:29:34 merged: 2019-02-05 09:38:38



73. [25839](http://github.com/cms-sw/cmssw/pull/25839){:target="_blank"}  from **@Dr15Jones**: Removed RPCRunIOV which conflicts with another class with same name `db`  created: 2019-02-01 22:15:07 merged: 2019-02-05 09:37:12



74. [25838](http://github.com/cms-sw/cmssw/pull/25838){:target="_blank"}  from **@makortel**: Remove EventSetup from PixelFitterBase-derived classes `fastsim`  `reconstruction`  created: 2019-02-01 22:08:26 merged: 2019-02-06 16:16:34



75. [25837](http://github.com/cms-sw/cmssw/pull/25837){:target="_blank"}  from **@makortel**: Manage PluginFactory plugins with unique_ptr in CalibMuon/DTCalibration `alca`  created: 2019-02-01 22:02:30 merged: 2019-02-04 09:00:15



76. [25836](http://github.com/cms-sw/cmssw/pull/25836){:target="_blank"}  from **@jshlee**: GEM - new gem emapping format for vfat v3 `alca`  `db`  created: 2019-02-01 19:46:21 merged: 2019-02-09 20:09:39



77. [25835](http://github.com/cms-sw/cmssw/pull/25835){:target="_blank"}  from **@Dr15Jones**: Removed unused EcalTPGScale which has same class name `alca`  created: 2019-02-01 17:09:47 merged: 2019-02-03 21:55:58



78. [25832](http://github.com/cms-sw/cmssw/pull/25832){:target="_blank"}  from **@makortel**: Use unique_ptr constructor for PluginFactory plugins in AttachSD `simulation`  created: 2019-02-01 03:14:40 merged: 2019-02-01 18:44:29



79. [25831](http://github.com/cms-sw/cmssw/pull/25831){:target="_blank"}  from **@Dr15Jones**: Removed struct dictionary from classes.h in TBDataFormats `analysis`  created: 2019-01-31 21:46:47 merged: 2019-02-01 08:37:35



80. [25830](http://github.com/cms-sw/cmssw/pull/25830){:target="_blank"}  from **@Dr15Jones**: Modernize dictionary generation in AnalysisDataFormats `analysis`  created: 2019-01-31 21:36:27 merged: 2019-02-01 08:40:03



81. [25829](http://github.com/cms-sw/cmssw/pull/25829){:target="_blank"}  from **@Dr15Jones**: Modernize dictionary generation in SimDataFormats `generators`  `simulation`  `upgrade`  created: 2019-01-31 21:09:27 merged: 2019-02-07 08:46:24



82. [25828](http://github.com/cms-sw/cmssw/pull/25828){:target="_blank"}  from **@Dr15Jones**: Modernize dictionary generation in FastSimDataFormats `fastsim`  created: 2019-01-31 20:53:03 merged: 2019-02-06 09:54:43



83. [25827](http://github.com/cms-sw/cmssw/pull/25827){:target="_blank"}  from **@makortel**: Manage PluginFactory plugin with unique_ptr in HLTMuonIsoFilter `hlt`  created: 2019-01-31 20:35:58 merged: 2019-02-04 09:05:02



84. [25826](http://github.com/cms-sw/cmssw/pull/25826){:target="_blank"}  from **@Dr15Jones**: Modernized dictionary generation in DataFormats `alca`  `analysis`  `core`  `daq`  `dqm`  `hlt`  `l1`  `reconstruction`  `simulation`  `upgrade`  `xpog`  created: 2019-01-31 19:52:45 merged: 2019-02-09 20:06:56



85. [25825](http://github.com/cms-sw/cmssw/pull/25825){:target="_blank"}  from **@makortel**: Manage PluginFactory plugin with unique_ptr in ExternalDecayDriver `generators`  created: 2019-01-31 18:56:59 merged: 2019-02-07 08:53:12



86. [25824](http://github.com/cms-sw/cmssw/pull/25824){:target="_blank"}  from **@angirar**: FastSim memory fix in TrajectorSeedProducer `fastsim`  created: 2019-01-31 17:11:48 merged: 2019-02-01 18:49:00



87. [25823](http://github.com/cms-sw/cmssw/pull/25823){:target="_blank"}  from **@guitargeek**: No more possibility to ignore exceptions in TagAndProbe `analysis`  created: 2019-01-31 16:31:07 merged: 2019-02-05 09:42:34



88. [25822](http://github.com/cms-sw/cmssw/pull/25822){:target="_blank"}  from **@bsunanda**: Run2-alca150 Make year dependent EE thresholds for IsoTrack analysis `alca`  created: 2019-01-31 16:02:55 merged: 2019-02-01 18:36:17



89. [25819](http://github.com/cms-sw/cmssw/pull/25819){:target="_blank"}  from **@civanch**: Extend field parameters modification to e+ and p `simulation`  created: 2019-01-31 12:23:42 merged: 2019-02-01 18:56:11



90. [25817](http://github.com/cms-sw/cmssw/pull/25817){:target="_blank"}  from **@intrepid42**: ParticleLevelProducer: fix warnings `generators`  created: 2019-01-31 09:28:09 merged: 2019-02-06 16:21:03



91. [25816](http://github.com/cms-sw/cmssw/pull/25816){:target="_blank"}  from **@makortel**: Manage PluginFactory plugin with a unique_ptr in CondDBESSource `alca`  `db`  created: 2019-01-31 04:32:18 merged: 2019-02-04 21:23:09



92. [25815](http://github.com/cms-sw/cmssw/pull/25815){:target="_blank"}  from **@makortel**: Remove redundant configuration settings for siPixelDigis `reconstruction`  created: 2019-01-31 04:05:34 merged: 2019-02-01 18:57:45



93. [25814](http://github.com/cms-sw/cmssw/pull/25814){:target="_blank"}  from **@makortel**: Remove unused variable from SiStripMonitorDigi `dqm`  created: 2019-01-31 03:09:06 merged: 2019-02-01 18:36:07



94. [25813](http://github.com/cms-sw/cmssw/pull/25813){:target="_blank"}  from **@makortel**: Manage PluginFactory plugin with a unique_ptr in algorithm_plugin_test in DetectorDescription `geometry`  created: 2019-01-31 02:47:35 merged: 2019-01-31 18:07:52



95. [25812](http://github.com/cms-sw/cmssw/pull/25812){:target="_blank"}  from **@makortel**: Use unique_ptr constructor for PluginFactory plugins in FWCore `core`  created: 2019-01-31 02:38:57 merged: 2019-01-31 18:07:19



96. [25811](http://github.com/cms-sw/cmssw/pull/25811){:target="_blank"}  from **@makortel**: Some modernization for SiPixelClusterProducer `alca`  `hlt`  `reconstruction`  created: 2019-01-31 02:37:09 merged: 2019-02-05 20:56:21



97. [25809](http://github.com/cms-sw/cmssw/pull/25809){:target="_blank"}  from **@Dr15Jones**: Fix clang warnings in L1TriggerConfig/L1GtConfigProducers `l1`  created: 2019-01-30 20:36:52 merged: 2019-02-08 09:24:14



98. [25808](http://github.com/cms-sw/cmssw/pull/25808){:target="_blank"}  from **@Dr15Jones**: Removed unused lambda capture in CSCGeometryESModule `geometry`  created: 2019-01-30 20:19:15 merged: 2019-01-31 09:15:12



99. [25807](http://github.com/cms-sw/cmssw/pull/25807){:target="_blank"}  from **@Dr15Jones**: Allow RVO to work in FedRawDataInputSource `daq`  `reconstruction`  created: 2019-01-30 20:10:16 merged: 2019-01-31 18:00:41



100. [25806](http://github.com/cms-sw/cmssw/pull/25806){:target="_blank"}  from **@Dr15Jones**: Removed unused variable from CSCDCCEventData `reconstruction`  created: 2019-01-30 20:00:29 merged: 2019-01-31 18:00:09



101. [25805](http://github.com/cms-sw/cmssw/pull/25805){:target="_blank"}  from **@Dr15Jones**: Fix clang warnings in EventFilter/SiPixelRawToDigi `reconstruction`  created: 2019-01-30 19:47:45 merged: 2019-02-07 09:38:27



102. [25803](http://github.com/cms-sw/cmssw/pull/25803){:target="_blank"}  from **@Dr15Jones**: Fix possible race in WaitingTaskHolder if reused `core`  created: 2019-01-30 19:33:35 merged: 2019-01-31 09:13:44



103. [25802](http://github.com/cms-sw/cmssw/pull/25802){:target="_blank"}  from **@bsunanda**: Phase2-hgx178 Get rid of Magic numbers `geometry`  `upgrade`  created: 2019-01-30 19:06:39 merged: 2019-02-03 21:55:14



104. [25801](http://github.com/cms-sw/cmssw/pull/25801){:target="_blank"}  from **@makortel**: Fix SwitchProducer sanity checks to allow more than one SwitchProducer in a job. `core`  created: 2019-01-30 17:06:11 merged: 2019-01-31 09:12:16



105. [25800](http://github.com/cms-sw/cmssw/pull/25800){:target="_blank"}  from **@Dr15Jones**: Fixed possible buffer overflow in CSCTriggerPrimitivesReader `l1`  created: 2019-01-30 16:51:46 merged: 2019-02-08 09:23:58



106. [25798](http://github.com/cms-sw/cmssw/pull/25798){:target="_blank"}  from **@ianna**: Fix Include Path Typo `simulation`  created: 2019-01-30 15:49:13 merged: 2019-01-31 18:03:06



107. [25794](http://github.com/cms-sw/cmssw/pull/25794){:target="_blank"}  from **@Dr15Jones**: Added fillDescriptions to EmptyIOVSource `db`  created: 2019-01-30 15:11:09 merged: 2019-01-31 09:09:29



108. [25793](http://github.com/cms-sw/cmssw/pull/25793){:target="_blank"}  from **@bsunanda**: Run2-alca149 Make year dependent thresholds for IsoTrackFilter `alca`  created: 2019-01-30 15:02:54 merged: 2019-02-03 21:57:34



109. [25791](http://github.com/cms-sw/cmssw/pull/25791){:target="_blank"}  from **@vkhristenko**: Add DataFrameContainer getters `core`  created: 2019-01-30 13:31:21 merged: 2019-01-30 20:47:50



110. [25790](http://github.com/cms-sw/cmssw/pull/25790){:target="_blank"}  from **@Mourtz**: Fix: transparency wasnt propagating after config changes `visualization`  created: 2019-01-30 10:50:02 merged: 2019-01-30 20:46:54



111. [25788](http://github.com/cms-sw/cmssw/pull/25788){:target="_blank"}  from **@ianna**: DD Cleanup: Remove Legacy Class `geometry`  created: 2019-01-30 09:50:31 merged: 2019-01-30 20:49:42



112. [25786](http://github.com/cms-sw/cmssw/pull/25786){:target="_blank"}  from **@slava77**: fix buffer overflow in TrackCleaner `reconstruction`  created: 2019-01-30 00:59:42 merged: 2019-01-30 20:46:04



113. [25784](http://github.com/cms-sw/cmssw/pull/25784){:target="_blank"}  from **@bsunanda**: Phase2-sim26 Add one simproducer class which can save hits of calorimeters `geometry`  `simulation`  `upgrade`  created: 2019-01-29 21:09:40 merged: 2019-02-05 20:57:52



114. [25783](http://github.com/cms-sw/cmssw/pull/25783){:target="_blank"}  from **@Dr15Jones**: Make edm::EventSetup a facade `alca`  `analysis`  `core`  `dqm`  `reconstruction`  `simulation`  created: 2019-01-29 20:47:35 merged: 2019-02-06 16:39:34



115. [25781](http://github.com/cms-sw/cmssw/pull/25781){:target="_blank"}  from **@Mourtz**: Draw 3D cross over the seed of each HGCal Layer Cluster `visualization`  created: 2019-01-29 15:43:09 merged: 2019-01-30 09:05:19



116. [25779](http://github.com/cms-sw/cmssw/pull/25779){:target="_blank"}  from **@makortel**: Remove empty endJob() functions from AlcaBeamMonitorClient and BeamMonitorBx `dqm`  created: 2019-01-28 21:08:32 merged: 2019-02-01 18:39:23



117. [25778](http://github.com/cms-sw/cmssw/pull/25778){:target="_blank"}  from **@makortel**: Fixes to TrackInfoProducer `analysis`  created: 2019-01-28 20:58:23 merged: 2019-01-30 09:08:18



118. [25777](http://github.com/cms-sw/cmssw/pull/25777){:target="_blank"}  from **@forthommel**: CondDB formats for PPS/Totem timing calibrations `alca`  `db`  created: 2019-01-28 18:27:29 merged: 2019-02-04 21:17:12



119. [25775](http://github.com/cms-sw/cmssw/pull/25775){:target="_blank"}  from **@Dr15Jones**: Fixed uninitialized values in HGCFEElectronics `simulation`  `upgrade`  created: 2019-01-27 04:05:33 merged: 2019-01-29 09:42:46



120. [25773](http://github.com/cms-sw/cmssw/pull/25773){:target="_blank"}  from **@bainbrid**: Move lowPtGsfElectronSequence back to highlevelreco (105X) `operations`  `reconstruction`  created: 2019-01-26 20:22:48 merged: 2019-01-28 21:24:30



121. [25770](http://github.com/cms-sw/cmssw/pull/25770){:target="_blank"}  from **@makortel**: Add a mechanism to adjust the pileup distribution in PreMixingModule `core`  `dqm`  `simulation`  created: 2019-01-25 23:18:22 merged: 2019-02-04 08:57:38



122. [25769](http://github.com/cms-sw/cmssw/pull/25769){:target="_blank"}  from **@makortel**: Actually run the SwitchProducer tests `core`  created: 2019-01-25 22:03:52 merged: 2019-01-28 09:41:02



123. [25768](http://github.com/cms-sw/cmssw/pull/25768){:target="_blank"}  from **@ianna**: DD4hep: Add Volume Processor `geometry`  created: 2019-01-25 16:02:36 merged: 2019-01-28 09:39:42



124. [25763](http://github.com/cms-sw/cmssw/pull/25763){:target="_blank"}  from **@Dr15Jones**: EventSetupRecordImpl now uses std::vectors instead of std::map `core`  created: 2019-01-24 23:00:26 merged: 2019-01-28 09:39:24



125. [25762](http://github.com/cms-sw/cmssw/pull/25762){:target="_blank"}  from **@schneiml**: CMSSW Config Tracing Tool `dqm`  created: 2019-01-24 18:06:16 merged: 2019-02-11 23:10:00



126. [25758](http://github.com/cms-sw/cmssw/pull/25758){:target="_blank"}  from **@angirar**: Fixing the seed check in CA iterations of FastSim `fastsim`  created: 2019-01-24 11:24:13 merged: 2019-01-29 17:53:06



127. [25756](http://github.com/cms-sw/cmssw/pull/25756){:target="_blank"}  from **@bsunanda**: Phase2-hgx179 Extend HGCScintillatorDetId to cover both detector and trigger cells `simulation`  `upgrade`  created: 2019-01-23 22:27:34 merged: 2019-01-28 09:38:49



128. [25755](http://github.com/cms-sw/cmssw/pull/25755){:target="_blank"}  from **@guitargeek**: Some GsfElectronAlgo modernization `reconstruction`  created: 2019-01-23 22:20:13 merged: 2019-02-17 16:21:59



129. [25753](http://github.com/cms-sw/cmssw/pull/25753){:target="_blank"}  from **@bainbrid**: Complete low pT electron chain (2) `analysis`  `reconstruction`  created: 2019-01-23 21:50:41 merged: 2019-02-10 00:58:44



130. [25752](http://github.com/cms-sw/cmssw/pull/25752){:target="_blank"}  from **@Dr15Jones**: Added firstLuminosityBlockForEachRun to ProducerSourceBase `core`  `generators`  created: 2019-01-23 21:36:46 merged: 2019-01-30 09:03:48



131. [25748](http://github.com/cms-sw/cmssw/pull/25748){:target="_blank"}  from **@veszpv**: Pixel simulated bad channel info packed into FED raw data `reconstruction`  created: 2019-01-23 15:14:08 merged: 2019-02-05 20:57:08



132. [25744](http://github.com/cms-sw/cmssw/pull/25744){:target="_blank"}  from **@slomeo**: Geometry 2018 (updated Cavern and new shields) `db`  `geometry`  `upgrade`  created: 2019-01-23 09:13:50 merged: 2019-01-29 17:50:17



133. [25743](http://github.com/cms-sw/cmssw/pull/25743){:target="_blank"}  from **@Dr15Jones**: Minor improvements to JetIdSelector `reconstruction`  created: 2019-01-22 22:43:20 merged: 2019-01-28 21:30:27



134. [25730](http://github.com/cms-sw/cmssw/pull/25730){:target="_blank"}  from **@vkhristenko**: make HBHERecHitAuxSetter::setAux constexpr `reconstruction`  created: 2019-01-22 11:31:01 merged: 2019-01-28 21:31:53



135. [25727](http://github.com/cms-sw/cmssw/pull/25727){:target="_blank"}  from **@OzAmram**: Working Version PixelCPECluster Repair (still turned off) `reconstruction`  created: 2019-01-22 00:20:28 merged: 2019-01-29 17:49:45



136. [25711](http://github.com/cms-sw/cmssw/pull/25711){:target="_blank"}  from **@tahuang1991**: fixed a memory issue caused by ME1a half strip value  `l1`  created: 2019-01-20 07:20:58 merged: 2019-01-29 17:49:17



137. [25705](http://github.com/cms-sw/cmssw/pull/25705){:target="_blank"}  from **@makortel**: Remove std::move from FastSim TrackingLayer to allow better compiler optimization `fastsim`  created: 2019-01-18 18:05:57 merged: 2019-01-29 17:48:44



138. [25685](http://github.com/cms-sw/cmssw/pull/25685){:target="_blank"}  from **@tahuang1991**: ME0  localTrigger `l1`  `simulation`  `upgrade`  created: 2019-01-16 21:19:50 merged: 2019-01-29 17:47:57



139. [25681](http://github.com/cms-sw/cmssw/pull/25681){:target="_blank"}  from **@guitargeek**: Using new Event::get and ::getHandle in PFProducers `reconstruction`  created: 2019-01-16 16:51:07 merged: 2019-01-29 17:47:14



140. [25616](http://github.com/cms-sw/cmssw/pull/25616){:target="_blank"}  from **@CTPPS**: PPS Alignment corrections object for condDB `alca`  `db`  `geometry`  `reconstruction`  created: 2019-01-09 17:12:35 merged: 2019-02-07 21:24:37



141. [25602](http://github.com/cms-sw/cmssw/pull/25602){:target="_blank"}  from **@mkirsano**: adapt Pythia8Interface to pythia8 240 `generators`  created: 2019-01-08 20:16:57 merged: 2019-02-14 21:54:05



142. [25595](http://github.com/cms-sw/cmssw/pull/25595){:target="_blank"}  from **@nancymarinelli**: Conversions from low pt ele tracks released in PR 25455 `operations`  `reconstruction`  created: 2019-01-07 16:43:16 merged: 2019-02-05 20:55:43



143. [25592](http://github.com/cms-sw/cmssw/pull/25592){:target="_blank"}  from **@PFCal-dev**: [HGCAL trigger] New validation package `dqm`  created: 2019-01-07 10:51:45 merged: 2019-02-01 19:12:37



144. [25577](http://github.com/cms-sw/cmssw/pull/25577){:target="_blank"}  from **@makortel**: Remove nearly all calls to Modifier.isChosen() from L1T configurations `hlt`  `l1`  `operations`  created: 2019-01-02 21:01:55 merged: 2019-02-04 21:18:41



145. [25575](http://github.com/cms-sw/cmssw/pull/25575){:target="_blank"}  from **@CTPPS**: Additional PPS tracks information `reconstruction`  created: 2018-12-31 08:58:06 merged: 2019-01-28 09:38:19



146. [25479](http://github.com/cms-sw/cmssw/pull/25479){:target="_blank"}  from **@mastrolorenzo**: Add filter for Charm quarks to produce C-enriched samples `generators`  created: 2018-12-12 08:06:21 merged: 2019-02-04 21:14:30



147. [21717](http://github.com/cms-sw/cmssw/pull/21717){:target="_blank"}  from **@hajohajo**: LWTNN Deep Neural Networks for track classification `reconstruction`  created: 2017-12-14 14:55:30 merged: 2019-02-15 09:48:36



#### CMSDIST Changes between Tags REL/CMSSW_10_5_0_pre1/slc7_amd64_gcc700 and REL/CMSSW_10_5_0_pre2/slc7_amd64_gcc700:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_10_5_0_pre1/slc7_amd64_gcc700...REL/CMSSW_10_5_0_pre2/slc7_amd64_gcc700)



1. [4717](http://github.com/cms-sw/cmsdist/pull/4717){:target="_blank"}  from **@cms-sw**: added py2-pybind11 dependency for fwlite created: 2019-02-20 11:01:04 merged: 2019-02-20 11:01:47

2. [4714](http://github.com/cms-sw/cmsdist/pull/4714){:target="_blank"}  from **@fabiocos**: Initialization fixes on top of pythia8 240 (from fixes on top of 230 not yet integrated) created: 2019-02-19 09:43:43 merged: 2019-02-20 09:46:23

3. [4707](http://github.com/cms-sw/cmsdist/pull/4707){:target="_blank"}  from **@cms-sw**: updated singularity env script created: 2019-02-18 10:42:15 merged: 2019-02-18 10:42:27

4. [4706](http://github.com/cms-sw/cmsdist/pull/4706){:target="_blank"}  from **@cms-sw**: [build rules] Inlcuded new cuda build rules created: 2019-02-18 09:03:33 merged: 2019-02-18 14:23:10

5. [4686](http://github.com/cms-sw/cmsdist/pull/4686){:target="_blank"}  from **@cms-sw**: Update scram-project-build.file created: 2019-02-09 07:48:24 merged: 2019-02-09 14:25:48

6. [4682](http://github.com/cms-sw/cmsdist/pull/4682){:target="_blank"}  from **@mrodozov**: Update DD4Hep to head of master created: 2019-02-07 11:36:18 merged: 2019-02-08 09:12:49

7. [4672](http://github.com/cms-sw/cmsdist/pull/4672){:target="_blank"}  from **@cms-sw**: Cxxmodule modulemap src created: 2019-02-04 08:51:46 merged: 2019-02-04 09:56:31

8. [4668](http://github.com/cms-sw/cmsdist/pull/4668){:target="_blank"}  from **@intrepid42**: Fix Professor2 and update to 2.2.2 created: 2019-01-30 17:52:15 merged: 2019-02-05 09:44:47

9. [4665](http://github.com/cms-sw/cmsdist/pull/4665){:target="_blank"}  from **@fwyzard**: Extend Eigen's support for decompositions on CUDA devices created: 2019-01-28 18:14:09 merged: 2019-01-29 07:11:27

10. [4663](http://github.com/cms-sw/cmsdist/pull/4663){:target="_blank"}  from **@cms-sw**: add cmssw-osenv dependency created: 2019-01-28 13:29:40 merged: 2019-01-28 20:18:58

11. [4650](http://github.com/cms-sw/cmsdist/pull/4650){:target="_blank"}  from **@cms-sw**: Update RecoEgamma-ElectronIdentification tag created: 2019-01-21 09:11:15 merged: 2019-02-10 00:54:53

12. [4643](http://github.com/cms-sw/cmsdist/pull/4643){:target="_blank"}  from **@fwyzard**: Update Eigen to the master branch created: 2019-01-16 22:18:32 merged: 2019-01-28 10:24:53

13. [4624](http://github.com/cms-sw/cmsdist/pull/4624){:target="_blank"}  from **@mkirsano**: upgrade pythia8 to 240, vincia to 2.2.04, dire to 2.003 created: 2019-01-08 19:51:09 merged: 2019-02-14 21:53:16

14. [4516](http://github.com/cms-sw/cmsdist/pull/4516){:target="_blank"}  from **@cms-sw**: [10.5.X] Updated data-RecoTracker-FinalTrackSelectors V01-00-06 created: 2018-11-20 22:00:43 merged: 2019-02-13 21:42:47

15. [4427](http://github.com/cms-sw/cmsdist/pull/4427){:target="_blank"}  from **@intrepid42**: Rivet 2.6.1 + Yoda 1.7.4 created: 2018-10-16 14:59:45 merged: 2019-02-05 09:53:09
