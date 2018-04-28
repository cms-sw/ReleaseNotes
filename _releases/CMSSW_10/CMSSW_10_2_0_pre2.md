---
layout: post
rel_link:  "10_2_0_pre2"
title:  "CMSSW_10_2_0_pre2"
date:   2018-04-27 14:05:21
categories: cmssw
relmajor: 10
relminor: 2
relsubminor: 0
relpre: _pre2
---

# CMSSW_10_2_0_pre2
#### Changes since CMSSW_10_2_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_10_2_0_pre1...CMSSW_10_2_0_pre2)



1. [23071](http://github.com/cms-sw/cmssw/pull/23071){:target="_blank"}  from **@battibass**: Add flag to configure production of DDU-based trigger synch plots [10_2_X] `dqm`  created: 2018-04-26 16:08:17 merged: 2018-04-27 08:05:06



2. [23055](http://github.com/cms-sw/cmssw/pull/23055){:target="_blank"}  from **@ianna**: Detector Description Cleanup: Remove Unused Class PartSelectionExpander `geometry`  created: 2018-04-25 13:07:11 merged: 2018-04-26 08:52:24



3. [23052](http://github.com/cms-sw/cmssw/pull/23052){:target="_blank"}  from **@makortel**: Fix automated pixel pair mitigation to include "Fed25" information `reconstruction`  created: 2018-04-25 11:05:21 merged: 2018-04-27 07:35:00



4. [23048](http://github.com/cms-sw/cmssw/pull/23048){:target="_blank"}  from **@slehti**: Hlt tau dqm update `dqm`  created: 2018-04-24 12:26:18 merged: 2018-04-25 16:59:26



5. [23041](http://github.com/cms-sw/cmssw/pull/23041){:target="_blank"}  from **@thomreis**: L1T DQM Remove etsum collection empty check. `dqm`  created: 2018-04-23 15:23:02 merged: 2018-04-25 16:49:35



6. [23037](http://github.com/cms-sw/cmssw/pull/23037){:target="_blank"}  from **@ianna**: DD4Hep Algorithms and Shapes `geometry`  created: 2018-04-23 08:52:52 merged: 2018-04-25 16:35:26



7. [23034](http://github.com/cms-sw/cmssw/pull/23034){:target="_blank"}  from **@thomreis**: L1T DQM fix for ZS module `dqm`  created: 2018-04-23 00:13:15 merged: 2018-04-26 08:10:33



8. [23026](http://github.com/cms-sw/cmssw/pull/23026){:target="_blank"}  from **@slava77**: remove unnecessary import of particleFlowZeroSuppressionECAL in particleFlowRecHitECAL_cfi `reconstruction`  created: 2018-04-20 16:11:17 merged: 2018-04-21 10:49:27



9. [23022](http://github.com/cms-sw/cmssw/pull/23022){:target="_blank"}  from **@slava77**:  Remove BoundaryPlane and friends (follow up to #21637 ) `reconstruction`  created: 2018-04-20 12:45:46 merged: 2018-04-21 10:54:09



10. [23019](http://github.com/cms-sw/cmssw/pull/23019){:target="_blank"}  from **@skurz**: fixes for AddOn Test Failures `fastsim`  created: 2018-04-20 08:54:06 merged: 2018-04-23 17:07:52



11. [23015](http://github.com/cms-sw/cmssw/pull/23015){:target="_blank"}  from **@parbol**: The use of the innerTrack is now protected with an if, also a cout ha `dqm`  created: 2018-04-19 21:17:33 merged: 2018-04-25 16:26:59



12. [23014](http://github.com/cms-sw/cmssw/pull/23014){:target="_blank"}  from **@bsunanda**: Run2-alca128 Include rho dependent PU correction in calibration method `alca`  created: 2018-04-19 18:40:27 merged: 2018-04-25 16:32:07



13. [23013](http://github.com/cms-sw/cmssw/pull/23013){:target="_blank"}  from **@bsunanda**: Run2-alca127 Change calibration code for HB/HE using muons `alca`  created: 2018-04-19 16:50:27 merged: 2018-04-25 16:30:24



14. [23011](http://github.com/cms-sw/cmssw/pull/23011){:target="_blank"}  from **@Dr15Jones**: Initialize value for MonitorElement pointers `dqm`  created: 2018-04-19 16:06:09 merged: 2018-04-23 17:06:51



15. [23009](http://github.com/cms-sw/cmssw/pull/23009){:target="_blank"}  from **@hqucms**: Specify the DB schema explicitly in the SiStrip O2O code `db`  created: 2018-04-19 15:15:05 merged: 2018-04-23 17:02:36



16. [23008](http://github.com/cms-sw/cmssw/pull/23008){:target="_blank"}  from **@pieterdavid**: Use SiStripDetInfoFileReader as an edm::Service in fake ES producers `alca`  created: 2018-04-19 14:52:03 merged: 2018-04-26 08:47:40



17. [23004](http://github.com/cms-sw/cmssw/pull/23004){:target="_blank"}  from **@perrozzi**: try to solve mg5 /tmp problem from ExternalLHEProducer `generators`  created: 2018-04-19 12:35:42 merged: 2018-04-20 16:14:45



18. [23002](http://github.com/cms-sw/cmssw/pull/23002){:target="_blank"}  from **@dan131riley**: isolate TTree::Fill so IMT doesn't steal long running CMS tasks `core`  created: 2018-04-18 17:10:59 merged: 2018-04-19 08:42:10



19. [23001](http://github.com/cms-sw/cmssw/pull/23001){:target="_blank"}  from **@kpedro88**: Bug fix for static pulse shapes `alca`  created: 2018-04-18 15:18:21 merged: 2018-04-23 17:02:07



20. [22999](http://github.com/cms-sw/cmssw/pull/22999){:target="_blank"}  from **@ianna**: Magnetic Field: Remove Dependency on DDSolidShape `reconstruction`  created: 2018-04-18 13:37:47 merged: 2018-04-19 08:35:08



21. [22997](http://github.com/cms-sw/cmssw/pull/22997){:target="_blank"}  from **@makortel**: Switch the order of HARVESTING and ALCA steps for upgrade workflows `pdmv`  `upgrade`  created: 2018-04-18 12:47:56 merged: 2018-04-26 08:38:28



22. [22994](http://github.com/cms-sw/cmssw/pull/22994){:target="_blank"}  from **@argiro**: produce dqm plots also in case of low stat `alca`  created: 2018-04-18 10:25:53 merged: 2018-04-25 16:28:44



23. [22992](http://github.com/cms-sw/cmssw/pull/22992){:target="_blank"}  from **@fabiocos**: Temporary protection against missing jet corrector collection `dqm`  created: 2018-04-18 09:53:40 merged: 2018-04-18 14:17:08



24. [22990](http://github.com/cms-sw/cmssw/pull/22990){:target="_blank"}  from **@kpedro88**: Hcal phase1 fastsim updates `dqm`  `fastsim`  `simulation`  created: 2018-04-18 08:11:19 merged: 2018-04-24 14:13:14



25. [22989](http://github.com/cms-sw/cmssw/pull/22989){:target="_blank"}  from **@makortel**: Add move constructor and assignment operator to edm::HepMCProduct `generators`  created: 2018-04-18 07:13:54 merged: 2018-04-23 12:10:27



26. [22987](http://github.com/cms-sw/cmssw/pull/22987){:target="_blank"}  from **@Sam-Harper**: Fixing Default Values of EgammaHLTGsfTrackVarProducer to be only used if there is a track found : 102X `hlt`  created: 2018-04-17 16:17:04 merged: 2018-04-18 14:05:18



27. [22985](http://github.com/cms-sw/cmssw/pull/22985){:target="_blank"}  from **@Dr15Jones**: Remove Parameter existence check since done by fillDescriptions `analysis`  created: 2018-04-17 15:08:21 merged: 2018-04-18 15:04:40



28. [22984](http://github.com/cms-sw/cmssw/pull/22984){:target="_blank"}  from **@Dr15Jones**: Remove unused variable in SiPixelModuleStatus `alca`  created: 2018-04-17 13:41:04 merged: 2018-04-19 14:07:37



29. [22983](http://github.com/cms-sw/cmssw/pull/22983){:target="_blank"}  from **@makortel**: Clean up QuickTrackAssociatorByHits configuration `dqm`  `simulation`  created: 2018-04-17 13:38:23 merged: 2018-04-24 13:42:42



30. [22982](http://github.com/cms-sw/cmssw/pull/22982){:target="_blank"}  from **@pieterdavid**: SiStripEventSummary fixes for special runs in local-DAQ `reconstruction`  created: 2018-04-17 09:59:15 merged: 2018-04-18 15:54:32



31. [22980](http://github.com/cms-sw/cmssw/pull/22980){:target="_blank"}  from **@andreh7**: double EM enrichment filter support for HepMCfilter `generators`  created: 2018-04-16 17:47:05 merged: 2018-04-23 11:43:51



32. [22977](http://github.com/cms-sw/cmssw/pull/22977){:target="_blank"}  from **@makortel**: Fix CSC, DT, and RPC digi validation configuration for premixing `dqm`  `operations`  `simulation`  created: 2018-04-16 15:10:48 merged: 2018-04-23 09:43:50



33. [22973](http://github.com/cms-sw/cmssw/pull/22973){:target="_blank"}  from **@ianna**: DD Core Clean Up: Remove DDPartSelector `geometry`  created: 2018-04-16 12:51:02 merged: 2018-04-17 08:30:14



34. [22969](http://github.com/cms-sw/cmssw/pull/22969){:target="_blank"}  from **@mmusich**: Combined updates for SiStrip Payload Inspector `db`  created: 2018-04-15 17:32:53 merged: 2018-04-23 17:00:53



35. [22968](http://github.com/cms-sw/cmssw/pull/22968){:target="_blank"}  from **@bsunanda**: Phase2-hgx108 Fix a bug for numbering HGCal `geometry`  `simulation`  `upgrade`  created: 2018-04-15 16:14:44 merged: 2018-04-19 15:34:36



36. [22964](http://github.com/cms-sw/cmssw/pull/22964){:target="_blank"}  from **@kfjack**: Module name fix for SingleMuon and Charmonium skims for T0 `pdmv`  created: 2018-04-14 02:40:12 merged: 2018-04-15 17:07:53



37. [22963](http://github.com/cms-sw/cmssw/pull/22963){:target="_blank"}  from **@wddgit**: Use GBRForest in PATMuonProducer `analysis`  `reconstruction`  created: 2018-04-13 20:15:26 merged: 2018-04-18 15:35:26



38. [22961](http://github.com/cms-sw/cmssw/pull/22961){:target="_blank"}  from **@apana**: Make sure the GlobalAlgBlk is not empty before accessing member data `dqm`  `l1`  created: 2018-04-13 17:53:11 merged: 2018-04-17 15:14:38



39. [22959](http://github.com/cms-sw/cmssw/pull/22959){:target="_blank"}  from **@fioriNTU**: Activating Dead channel monitor Online `dqm`  created: 2018-04-13 16:37:26 merged: 2018-04-17 15:16:22



40. [22956](http://github.com/cms-sw/cmssw/pull/22956){:target="_blank"}  from **@makortel**: Add combined premixing stage1+stage2 workflows for 2016-18 `pdmv`  `upgrade`  created: 2018-04-13 15:12:29 merged: 2018-04-23 09:17:06



41. [22955](http://github.com/cms-sw/cmssw/pull/22955){:target="_blank"}  from **@cms-bph-trigger**: DQM for BPH paths `dqm`  created: 2018-04-13 14:24:48 merged: 2018-04-26 08:56:59



42. [22953](http://github.com/cms-sw/cmssw/pull/22953){:target="_blank"}  from **@makortel**: Move premixing worker plugins to packages with corresponding MixingModule plugins `simulation`  created: 2018-04-13 11:05:51 merged: 2018-04-19 14:28:40



43. [22951](http://github.com/cms-sw/cmssw/pull/22951){:target="_blank"}  from **@JanFSchulte**: Add layer counting capability to PixelActivityFilter `hlt`  created: 2018-04-13 08:46:49 merged: 2018-04-16 11:21:05



44. [22946](http://github.com/cms-sw/cmssw/pull/22946){:target="_blank"}  from **@fabozzi**: Updates to relvals `pdmv`  `upgrade`  created: 2018-04-12 15:20:46 merged: 2018-04-16 08:07:52



45. [22943](http://github.com/cms-sw/cmssw/pull/22943){:target="_blank"}  from **@cms-tsg-storm**: Small bug fix in hltGetConfiguration (102X) `hlt`  created: 2018-04-12 11:37:11 merged: 2018-04-13 17:18:45



46. [22938](http://github.com/cms-sw/cmssw/pull/22938){:target="_blank"}  from **@slava77**: decouple EventContent_cff load from general purpose use of Merge.py `operations`  created: 2018-04-11 20:29:30 merged: 2018-04-12 04:45:41



47. [22935](http://github.com/cms-sw/cmssw/pull/22935){:target="_blank"}  from **@fabiocos**: Add a flag to prevent storage of LHEXMLStringProduct `generators`  created: 2018-04-11 15:13:54 merged: 2018-04-12 14:58:15



48. [22934](http://github.com/cms-sw/cmssw/pull/22934){:target="_blank"}  from **@makortel**: Workaround for extra empty bins in MultiTrackValidator histograms with bin labels `dqm`  created: 2018-04-11 15:08:49 merged: 2018-04-13 17:11:37



49. [22932](http://github.com/cms-sw/cmssw/pull/22932){:target="_blank"}  from **@jlagram**: Strip hit eff update 10_2_x `alca`  created: 2018-04-11 14:34:49 merged: 2018-04-19 10:00:20



50. [22929](http://github.com/cms-sw/cmssw/pull/22929){:target="_blank"}  from **@makortel**: Remove unused simTrackHits parameter from some L1 track trigger code `l1`  `simulation`  `upgrade`  created: 2018-04-11 11:55:05 merged: 2018-04-24 12:28:51



51. [22925](http://github.com/cms-sw/cmssw/pull/22925){:target="_blank"}  from **@schneiml**: Fix noise in dqmMemoryStats `dqm`  created: 2018-04-11 07:47:07 merged: 2018-04-12 05:13:37



52. [22923](http://github.com/cms-sw/cmssw/pull/22923){:target="_blank"}  from **@threus**: updated online/express GT `dqm`  created: 2018-04-11 06:52:41 merged: 2018-04-12 07:21:26



53. [22921](http://github.com/cms-sw/cmssw/pull/22921){:target="_blank"}  from **@kpedro88**: avoid repeating computations when initializing HcalPulseShapes `alca`  created: 2018-04-10 16:49:34 merged: 2018-04-16 20:00:06



54. [22918](http://github.com/cms-sw/cmssw/pull/22918){:target="_blank"}  from **@lpernie**: [102X][change Metadata] Adding PCC + TrackAlign PCL not consumed by Prompt `alca`  `db`  created: 2018-04-10 13:38:54 merged: 2018-04-12 05:15:02



55. [22917](http://github.com/cms-sw/cmssw/pull/22917){:target="_blank"}  from **@bsunanda**: Phase2-hgx107 Change the basic geometry of HGCal from FlatTrd to FlatHexagon `db`  `geometry`  `upgrade`  created: 2018-04-10 13:25:19 merged: 2018-04-19 08:50:21



56. [22914](http://github.com/cms-sw/cmssw/pull/22914){:target="_blank"}  from **@ahinzmann**: Simplify jet constituent access in MiniAOD `analysis`  `reconstruction`  created: 2018-04-10 10:14:57 merged: 2018-04-21 11:08:07



57. [22907](http://github.com/cms-sw/cmssw/pull/22907){:target="_blank"}  from **@apana**: Add DQM module to make uGT data/emulator comparisons `dqm`  `l1`  created: 2018-04-09 03:51:24 merged: 2018-04-10 20:43:35



58. [22905](http://github.com/cms-sw/cmssw/pull/22905){:target="_blank"}  from **@cms-nanoAOD**: Add deep flavour of MiniAOD v2 to NANOAOD  (master version) `analysis`  created: 2018-04-08 18:43:32 merged: 2018-04-09 19:16:02



59. [22903](http://github.com/cms-sw/cmssw/pull/22903){:target="_blank"}  from **@threus**: remove eventAutoFlushCompressedSize in eventdisplay `dqm`  created: 2018-04-08 17:01:19 merged: 2018-04-10 19:58:48



60. [22901](http://github.com/cms-sw/cmssw/pull/22901){:target="_blank"}  from **@silviodonato**: HLT DQM online fix `dqm`  created: 2018-04-08 15:03:53 merged: 2018-04-10 19:58:15



61. [22891](http://github.com/cms-sw/cmssw/pull/22891){:target="_blank"}  from **@bsunanda**: Phase2-hgx106 Step toward HGCal interface of Geometry `geometry`  `upgrade`  created: 2018-04-07 06:32:43 merged: 2018-04-14 09:30:28



62. [22889](http://github.com/cms-sw/cmssw/pull/22889){:target="_blank"}  from **@popovvp**: CTPPS Pixel DQM: protection against RP ID corruption `dqm`  created: 2018-04-06 23:15:58 merged: 2018-04-11 07:12:47



63. [22888](http://github.com/cms-sw/cmssw/pull/22888){:target="_blank"}  from **@phylsix**: dedicated DQM on displacedStandAlone muons `dqm`  created: 2018-04-06 23:14:22 merged: 2018-04-26 08:27:28



64. [22886](http://github.com/cms-sw/cmssw/pull/22886){:target="_blank"}  from **@wddgit**: Add GlobalCache to DeepFlavourJetTagsProducer to improve startup perf `reconstruction`  created: 2018-04-06 20:23:39 merged: 2018-04-10 08:11:19



65. [22885](http://github.com/cms-sw/cmssw/pull/22885){:target="_blank"}  from **@Dr15Jones**: Sleeping modules `core`  created: 2018-04-06 19:38:37 merged: 2018-04-10 08:27:29



66. [22882](http://github.com/cms-sw/cmssw/pull/22882){:target="_blank"}  from **@Dr15Jones**: Minor cleanups to avoid clang warnings `core`  created: 2018-04-06 14:50:50 merged: 2018-04-09 19:29:49



67. [22881](http://github.com/cms-sw/cmssw/pull/22881){:target="_blank"}  from **@Dr15Jones**: Avoid self assignments in SiStrip Key classes `reconstruction`  created: 2018-04-06 14:24:25 merged: 2018-04-09 19:26:59



68. [22879](http://github.com/cms-sw/cmssw/pull/22879){:target="_blank"}  from **@HeinerTholen**: Make JetResolution class available from python `analysis`  `reconstruction`  created: 2018-04-06 14:08:08 merged: 2018-04-10 08:24:16



69. [22878](http://github.com/cms-sw/cmssw/pull/22878){:target="_blank"}  from **@ashtipliyski**: Remove check for empty sum collection in CALOL2-uGT comparison `dqm`  created: 2018-04-06 13:38:26 merged: 2018-04-12 07:20:03



70. [22875](http://github.com/cms-sw/cmssw/pull/22875){:target="_blank"}  from **@cedricpri**: Added ratios on the validation plots `dqm`  created: 2018-04-06 11:19:51 merged: 2018-04-10 19:48:59



71. [22874](http://github.com/cms-sw/cmssw/pull/22874){:target="_blank"}  from **@makortel**: Simplify caching of CLHEP::HepRandomEngine in digitizers `simulation`  `upgrade`  created: 2018-04-06 11:15:14 merged: 2018-04-13 17:16:27



72. [22873](http://github.com/cms-sw/cmssw/pull/22873){:target="_blank"}  from **@boudoul**: Phase2 Outer Tracker : Incorporating recent changes from TEDD Design + cleaning `geometry`  `upgrade`  created: 2018-04-06 11:10:59 merged: 2018-04-18 08:57:20



73. [22871](http://github.com/cms-sw/cmssw/pull/22871){:target="_blank"}  from **@wouf**: Update Hydjet_Quenched_MinBias_XeXe_5442GeV_cfi.py (Cymbal5F) `generators`  created: 2018-04-06 04:00:05 merged: 2018-04-12 05:16:11



74. [22868](http://github.com/cms-sw/cmssw/pull/22868){:target="_blank"}  from **@samhiggie**: Changed CorrPCCProducer from EDProducer to DQMEDAnalyzer for LumiPOG `alca`  `pdmv`  `upgrade`  created: 2018-04-05 18:49:13 merged: 2018-04-27 08:20:32



75. [22861](http://github.com/cms-sw/cmssw/pull/22861){:target="_blank"}  from **@drkovalskyi**: [Tag-N-Probe] Split read mode  `analysis`  created: 2018-04-05 15:44:47 merged: 2018-04-20 11:49:06



76. [22856](http://github.com/cms-sw/cmssw/pull/22856){:target="_blank"}  from **@ptrstn**: [SiStrip-DQM] Reduce the number of bins in the Eloss histograms `dqm`  created: 2018-04-05 10:03:33 merged: 2018-04-11 07:46:05



77. [22852](http://github.com/cms-sw/cmssw/pull/22852){:target="_blank"}  from **@makortel**: Minor simplifications to HGCDigiProducer `simulation`  `upgrade`  created: 2018-04-05 07:02:49 merged: 2018-04-10 09:49:16



78. [22848](http://github.com/cms-sw/cmssw/pull/22848){:target="_blank"}  from **@christopheralanwest**: Revert "Do not truncate QIE11 linearization LUTs at 10 bits" `alca`  `l1`  created: 2018-04-04 19:43:08 merged: 2018-04-13 17:16:04



79. [22845](http://github.com/cms-sw/cmssw/pull/22845){:target="_blank"}  from **@Dr15Jones**: Avoid reading memory after delete in CosMuoGenProducer `generators`  created: 2018-04-04 16:01:03 merged: 2018-04-09 19:21:24



80. [22839](http://github.com/cms-sw/cmssw/pull/22839){:target="_blank"}  from **@abrinke1**: EMTF April 2018 emulator update part 2 - GEM and Track Trigger data formats `l1`  created: 2018-04-04 13:09:21 merged: 2018-04-15 07:02:32



81. [22837](http://github.com/cms-sw/cmssw/pull/22837){:target="_blank"}  from **@makortel**: Move logintpack and libminifloat under DataFormats/Math, and add unit tests for logintpack::pack16 etc `analysis`  `dqm`  `reconstruction`  created: 2018-04-04 12:19:04 merged: 2018-04-11 07:50:16



82. [22836](http://github.com/cms-sw/cmssw/pull/22836){:target="_blank"}  from **@suchandradutta**: Ph2 TK Digitizer software updated for RandomNumberGenerator service `simulation`  `upgrade`  created: 2018-04-04 10:18:48 merged: 2018-04-13 17:14:08



83. [22807](http://github.com/cms-sw/cmssw/pull/22807){:target="_blank"}  from **@HeinerTholen**: BTag DQM with shallowTagInfos `dqm`  created: 2018-03-30 12:52:03 merged: 2018-04-15 07:00:06



84. [22796](http://github.com/cms-sw/cmssw/pull/22796){:target="_blank"}  from **@CTPPS**: CTPPS: TotemTimingDigi, totemTimingRawToDigi and mapping for the new Timing detector in Vertical RPs `alca`  `db`  `reconstruction`  `simulation`  created: 2018-03-29 09:31:24 merged: 2018-04-11 14:01:18



85. [22724](http://github.com/cms-sw/cmssw/pull/22724){:target="_blank"}  from **@DryRun**: HCALDQM: Update DigiTask for 2018 HE (10_1_X) `dqm`  created: 2018-03-23 14:27:09 merged: 2018-04-11 07:29:31



86. [22704](http://github.com/cms-sw/cmssw/pull/22704){:target="_blank"}  from **@slehti**: Hlt tau dqm update `dqm`  created: 2018-03-22 08:59:06 merged: 2018-04-13 09:30:27



87. [22682](http://github.com/cms-sw/cmssw/pull/22682){:target="_blank"}  from **@emacdonald16**: DQM OuterTrackerL1 plots for TTStubs, TTClusters, and TTTracks for release validation `dqm`  `simulation`  `upgrade`  created: 2018-03-20 16:40:47 merged: 2018-04-18 08:29:47



88. [22615](http://github.com/cms-sw/cmssw/pull/22615){:target="_blank"}  from **@civanch**: Cleanup definition of exotic particles `simulation`  created: 2018-03-14 17:09:24 merged: 2018-04-09 19:17:44



89. [22583](http://github.com/cms-sw/cmssw/pull/22583){:target="_blank"}  from **@makortel**: Perform premixing reco step customizations with premix_stage2 modifier `analysis`  `dqm`  `pdmv`  `reconstruction`  `simulation`  `upgrade`  created: 2018-03-12 11:59:30 merged: 2018-04-12 12:30:57



90. [22546](http://github.com/cms-sw/cmssw/pull/22546){:target="_blank"}  from **@pieterdavid**: Remove StripCPEfromTemplate `reconstruction`  created: 2018-03-09 13:03:52 merged: 2018-04-10 09:40:24



91. [22524](http://github.com/cms-sw/cmssw/pull/22524){:target="_blank"}  from **@dtsitson**: L1TObjects Ratio Timing Plots - L1T & Online DQM - CMSSW - 102X `dqm`  created: 2018-03-08 09:36:16 merged: 2018-04-24 12:57:06



92. [22465](http://github.com/cms-sw/cmssw/pull/22465){:target="_blank"}  from **@tsusa**: Implemented pixel inefficiency at ROC level `simulation`  created: 2018-03-05 18:25:01 merged: 2018-04-15 08:15:33



93. [22424](http://github.com/cms-sw/cmssw/pull/22424){:target="_blank"}  from **@hvanhaev**: CASTOR reconstruction and simulation updates `reconstruction`  `simulation`  created: 2018-03-02 15:46:13 merged: 2018-04-10 07:41:34



94. [22416](http://github.com/cms-sw/cmssw/pull/22416){:target="_blank"}  from **@makortel**: Replace DataMixingModule with specific PreMixingModule for premixing stage2 `operations`  `simulation`  created: 2018-03-02 10:38:24 merged: 2018-04-12 09:36:11



95. [22288](http://github.com/cms-sw/cmssw/pull/22288){:target="_blank"}  from **@dildick**: Shift the CSC LCT central BX from 6 to 8 in simulation `l1`  `simulation`  created: 2018-02-21 19:01:59 merged: 2018-04-17 08:27:34



96. [22145](http://github.com/cms-sw/cmssw/pull/22145){:target="_blank"}  from **@civanch**: Geant4 Sensitive Detectors update 4: revised selection of particle type for shower libraries `simulation`  created: 2018-02-07 14:47:32 merged: 2018-04-22 14:27:48



97. [22025](http://github.com/cms-sw/cmssw/pull/22025){:target="_blank"}  from **@perrozzi**: revert stream::producer to simple producer to avoid crashes in HTXSRivetProducer `generators`  created: 2018-01-29 20:57:39 merged: 2018-04-18 15:23:04



98. [21659](http://github.com/cms-sw/cmssw/pull/21659){:target="_blank"}  from **@lgray**: Require vertex to have time to use timing cuts in displaced track seeding `reconstruction`  `upgrade`  created: 2017-12-07 21:04:49 merged: 2018-04-14 09:15:22



#### CMSDIST Changes between Tags REL/CMSSW_10_2_0_pre1/slc6_amd64_gcc630 and REL/CMSSW_10_2_0_pre2/slc6_amd64_gcc630:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_10_2_0_pre1/slc6_amd64_gcc630...REL/CMSSW_10_2_0_pre2/slc6_amd64_gcc630)



1. [3962](http://github.com/cms-sw/cmsdist/pull/3962){:target="_blank"}  from **@fwyzard**: Hack CUDA to support GCC 7 created: 2018-04-26 17:53:03 merged: 2018-04-27 09:39:16

2. [3957](http://github.com/cms-sw/cmsdist/pull/3957){:target="_blank"}  from **@cms-sw**: Updated root to 6.12 for CMSSW 10.2.X created: 2018-04-26 09:36:41 merged: 2018-04-26 14:09:44

3. [3954](http://github.com/cms-sw/cmsdist/pull/3954){:target="_blank"}  from **@cms-sw**: backported git and xrootd from devel IBs in to production 10.2.X IB created: 2018-04-25 11:20:30 merged: 2018-04-25 20:41:13

4. [3953](http://github.com/cms-sw/cmsdist/pull/3953){:target="_blank"}  from **@cms-sw**: set TFCOMPILE pointing to tfcompile executable created: 2018-04-25 11:12:33 merged: 2018-04-25 11:12:42

5. [3952](http://github.com/cms-sw/cmsdist/pull/3952){:target="_blank"}  from **@cms-sw**: update config tag created: 2018-04-24 05:07:38 merged: 2018-04-24 05:55:52

6. [3938](http://github.com/cms-sw/cmsdist/pull/3938){:target="_blank"}  from **@davidlange6**: Backport python3 related changes from DEVEL to mainstream created: 2018-04-20 12:11:29 merged: 2018-04-21 11:23:20

7. [3935](http://github.com/cms-sw/cmsdist/pull/3935){:target="_blank"}  from **@cms-sw**: update SCRAM and build rules created: 2018-04-20 07:41:45 merged: 2018-04-20 20:16:20

8. [3931](http://github.com/cms-sw/cmsdist/pull/3931){:target="_blank"}  from **@cms-sw**: Update pythia8.spec created: 2018-04-18 22:40:20 merged: 2018-04-19 05:49:03

9. [3928](http://github.com/cms-sw/cmsdist/pull/3928){:target="_blank"}  from **@cms-sw**: renamed tensorflow specs; add tfcompile created: 2018-04-18 14:01:59 merged: 2018-04-18 19:25:35

10. [3926](http://github.com/cms-sw/cmsdist/pull/3926){:target="_blank"}  from **@cms-sw**: Geant4: Update the commit number after fix on that branch created: 2018-04-17 08:03:06 merged: 2018-04-21 10:46:00

11. [3918](http://github.com/cms-sw/cmsdist/pull/3918){:target="_blank"}  from **@cms-sw**: Update DD4HEP to tag 01-07 created: 2018-04-12 09:38:31 merged: 2018-04-12 15:22:35

12. [3913](http://github.com/cms-sw/cmsdist/pull/3913){:target="_blank"}  from **@cms-sw**: updated scram version to V2_2_7 created: 2018-04-11 16:54:41 merged: 2018-04-11 19:45:39

13. [3911](http://github.com/cms-sw/cmsdist/pull/3911){:target="_blank"}  from **@cms-sw**: [SCRAMV1]: only make one copy of scram under cms_path/share created: 2018-04-10 14:03:43 merged: 2018-04-10 16:51:15

14. [3901](http://github.com/cms-sw/cmsdist/pull/3901){:target="_blank"}  from **@cms-sw**: Update to new tag created: 2018-04-06 11:21:19 merged: 2018-04-18 08:56:22
