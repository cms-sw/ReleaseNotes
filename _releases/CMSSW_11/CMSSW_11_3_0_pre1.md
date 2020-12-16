---
layout: post
rel_link:  "11_3_0_pre1"
title:  "CMSSW_11_3_0_pre1"
date:   2020-12-15 21:05:34
categories: cmssw
relmajor: 11
relminor: 3
relsubminor: 0
relpre: _pre1
---

# CMSSW_11_3_0_pre1
#### Changes since CMSSW_11_2_0_pre10:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_11_2_0_pre10...CMSSW_11_3_0_pre1)



1. [32491](http://github.com/cms-sw/cmssw/pull/32491){:target="_blank"}  from **@Sam-Harper**: Switching MCSmartSingleParticleFilter to use an input tag `generators`  created: 2020-12-15 08:48:48 merged: 2020-12-15 18:16:56



2. [32487](http://github.com/cms-sw/cmssw/pull/32487){:target="_blank"}  from **@Dr15Jones**: Use tbb:task_group in TestTBBTasksAnalyzer `core`  created: 2020-12-14 20:55:35 merged: 2020-12-15 18:13:15



3. [32484](http://github.com/cms-sw/cmssw/pull/32484){:target="_blank"}  from **@Dr15Jones**: Use esConsumes with SiPixelStatusProducer `alca`  created: 2020-12-14 19:09:17 merged: 2020-12-15 19:40:24



4. [32482](http://github.com/cms-sw/cmssw/pull/32482){:target="_blank"}  from **@Dr15Jones**: Removed direct use of tbb::task from SerialTaskQueue `core`  created: 2020-12-14 17:18:46 merged: 2020-12-15 18:19:44



5. [32478](http://github.com/cms-sw/cmssw/pull/32478){:target="_blank"}  from **@bsunanda**: Run3-hcx276 Make sure that change of units in dd4hep will not affect ECAL geom parameters `geometry`  created: 2020-12-14 15:47:37 merged: 2020-12-15 00:23:32



6. [32477](http://github.com/cms-sw/cmssw/pull/32477){:target="_blank"}  from **@bsunanda**: Run3-hcx275 Make sure that change of units in dd4hep will not affect Hcal sim parameters `geometry`  created: 2020-12-14 15:26:34 merged: 2020-12-15 00:23:26



7. [32473](http://github.com/cms-sw/cmssw/pull/32473){:target="_blank"}  from **@bsunanda**: Phase2-hgx272 Make sure that change of units in dd4hep will not affect HGCal geometry `geometry`  `upgrade`  created: 2020-12-14 13:58:48 merged: 2020-12-15 00:23:21



8. [32468](http://github.com/cms-sw/cmssw/pull/32468){:target="_blank"}  from **@Dominic-Stafford**: Rename external tool herwigpp to herwig7 `generators`  created: 2020-12-14 12:33:48 merged: 2020-12-15 11:03:50



9. [32461](http://github.com/cms-sw/cmssw/pull/32461){:target="_blank"}  from **@bsunanda**: Run3-hcx274 Make sure that change of units in dd4hep will not affect HCAL `geometry`  created: 2020-12-13 17:11:17 merged: 2020-12-14 06:53:15



10. [32456](http://github.com/cms-sw/cmssw/pull/32456){:target="_blank"}  from **@slomeo**: Added "/dd4hep::cm" to RPCGeometryBuilder `geometry`  created: 2020-12-12 07:17:20 merged: 2020-12-14 06:17:38



11. [32454](http://github.com/cms-sw/cmssw/pull/32454){:target="_blank"}  from **@trtomei**: Preliminary L1T-HLT Interface for Phase-2 -- redux `hlt`  created: 2020-12-11 19:52:33 merged: 2020-12-15 16:52:08



12. [32449](http://github.com/cms-sw/cmssw/pull/32449){:target="_blank"}  from **@rmanzoni**: [Bug fix] Avoid rejecting good events in PythiaFilterMultiAncestor.cc `generators`  created: 2020-12-11 15:14:49 merged: 2020-12-14 09:50:56



13. [32445](http://github.com/cms-sw/cmssw/pull/32445){:target="_blank"}  from **@bsunanda**: Run4-sim78 Add a few methods for HGCal scinitllator part `simulation`  `upgrade`  created: 2020-12-10 23:41:45 merged: 2020-12-11 16:04:40



14. [32442](http://github.com/cms-sw/cmssw/pull/32442){:target="_blank"}  from **@nvoytish**: Update CSCMake2DRecHit.cc `reconstruction`  created: 2020-12-10 19:21:53 merged: 2020-12-15 18:22:15



15. [32436](http://github.com/cms-sw/cmssw/pull/32436){:target="_blank"}  from **@cms-sw**: Revert "Adding infra. for L1T object scaling constants from DB" `alca`  `db`  `hlt`  created: 2020-12-10 08:36:51 merged: 2020-12-14 16:14:07



16. [32433](http://github.com/cms-sw/cmssw/pull/32433){:target="_blank"}  from **@bsunanda**: Run4-hgx270 Add tile attributes to scintillator DetId `geometry`  `simulation`  `upgrade`  created: 2020-12-09 18:42:42 merged: 2020-12-11 21:04:35



17. [32432](http://github.com/cms-sw/cmssw/pull/32432){:target="_blank"}  from **@mmusich**: Migrate Calibration/TkAlCaRecoProducers to esConsumes and other fixes `alca`  created: 2020-12-09 15:50:26 merged: 2020-12-15 18:26:42



18. [32431](http://github.com/cms-sw/cmssw/pull/32431){:target="_blank"}  from **@kdlong**: Fix the customization functions of genpart pruning in NanoGEN `analysis`  `xpog`  created: 2020-12-09 13:22:59 merged: 2020-12-12 09:53:59



19. [32427](http://github.com/cms-sw/cmssw/pull/32427){:target="_blank"}  from **@lecriste**: Store association maps `dqm`  `simulation`  created: 2020-12-09 00:37:55 merged: 2020-12-12 11:48:08



20. [32426](http://github.com/cms-sw/cmssw/pull/32426){:target="_blank"}  from **@slava77**: sync up with #32372: remove unnecessary include in PhysicsTools/PatAlgos slimmedLowPtElectrons_cff.py `analysis`  `reconstruction`  created: 2020-12-08 23:06:39 merged: 2020-12-10 00:17:24



21. [32424](http://github.com/cms-sw/cmssw/pull/32424){:target="_blank"}  from **@guitargeek**: Partially migrate EGEnergyCorrector to ESGetTokens and remove support for electrons `reconstruction`  created: 2020-12-08 22:18:38 merged: 2020-12-15 07:58:56



22. [32423](http://github.com/cms-sw/cmssw/pull/32423){:target="_blank"}  from **@bsunanda**: Phase2-hgx270 Bug correction for HGCal scintillator Geometry `geometry`  `upgrade`  created: 2020-12-08 16:56:08 merged: 2020-12-10 00:16:16



23. [32421](http://github.com/cms-sw/cmssw/pull/32421){:target="_blank"}  from **@christopheralanwest**: Add low pT electron payloads to Run 2 data/MC and Run 3 MC GTs `alca`  created: 2020-12-08 15:24:54 merged: 2020-12-09 20:48:26



24. [32419](http://github.com/cms-sw/cmssw/pull/32419){:target="_blank"}  from **@kpedro88**: fix syntax warnings in matrix code `pdmv`  `upgrade`  created: 2020-12-08 14:46:24 merged: 2020-12-09 08:38:38



25. [32412](http://github.com/cms-sw/cmssw/pull/32412){:target="_blank"}  from **@ebrondol**: Update of HGCal validation of CaloParticle `dqm`  created: 2020-12-08 10:09:12 merged: 2020-12-10 18:09:56



26. [32410](http://github.com/cms-sw/cmssw/pull/32410){:target="_blank"}  from **@makortel**: Demote module deletion printout to INFO `core`  created: 2020-12-08 02:11:37 merged: 2020-12-08 13:56:10



27. [32409](http://github.com/cms-sw/cmssw/pull/32409){:target="_blank"}  from **@makortel**: Improve method to get largest module ID in ProcessCallGraph `hlt`  created: 2020-12-07 22:41:42 merged: 2020-12-08 14:06:59



28. [32407](http://github.com/cms-sw/cmssw/pull/32407){:target="_blank"}  from **@bsunanda**: Run3-gex43 Remove double declaration of the same constant `geometry`  `simulation`  `upgrade`  created: 2020-12-07 20:15:49 merged: 2020-12-11 16:03:20



29. [32406](http://github.com/cms-sw/cmssw/pull/32406){:target="_blank"}  from **@makortel**: Enable concurrent lumis by default in cmsDriver.py `operations`  `pdmv`  `upgrade`  created: 2020-12-07 19:28:27 merged: 2020-12-11 22:44:28



30. [32405](http://github.com/cms-sw/cmssw/pull/32405){:target="_blank"}  from **@wddgit**: Fix debug compilation, GCC900 for FWCore/Utilities `core`  created: 2020-12-07 17:47:48 merged: 2020-12-08 10:03:12



31. [32404](http://github.com/cms-sw/cmssw/pull/32404){:target="_blank"}  from **@mmusich**: Strip payload inspector: add class to retrieve list of dead modules from JSON `db`  created: 2020-12-07 16:06:45 merged: 2020-12-09 19:48:19



32. [32401](http://github.com/cms-sw/cmssw/pull/32401){:target="_blank"}  from **@guitargeek**: Break circular dependency between CommonTools and JetMETCorrections subsystems `analysis`  `dqm`  `reconstruction`  created: 2020-12-07 15:02:56 merged: 2020-12-10 08:13:27



33. [32400](http://github.com/cms-sw/cmssw/pull/32400){:target="_blank"}  from **@silviodonato**: Fix in TauAnalysis/MCEmbeddingTools/python/customisers.py (lowPtGsfElectronTask) `analysis`  `simulation`  created: 2020-12-07 14:03:00 merged: 2020-12-08 18:28:44



34. [32396](http://github.com/cms-sw/cmssw/pull/32396){:target="_blank"}  from **@jeongeun**: drop type spec in TrackingTools RecoMuon `hlt`  `reconstruction`  created: 2020-12-07 09:12:07 merged: 2020-12-08 06:35:33



35. [32394](http://github.com/cms-sw/cmssw/pull/32394){:target="_blank"}  from **@mariadalfonso**: HBHE: Avoid double counting of correlated term `reconstruction`  created: 2020-12-06 11:08:59 merged: 2020-12-14 15:17:08



36. [32393](http://github.com/cms-sw/cmssw/pull/32393){:target="_blank"}  from **@bsunanda**: Phase2-hgx269 Make use of ESGetToken and remove usage of HCAL (in one app) `dqm`  `geometry`  `upgrade`  created: 2020-12-05 15:41:24 merged: 2020-12-10 18:11:31



37. [32389](http://github.com/cms-sw/cmssw/pull/32389){:target="_blank"}  from **@rmanzoni**: Add new Pythia filter to select particles based on ancestor (i.e. further back than mother) `generators`  created: 2020-12-04 14:56:36 merged: 2020-12-08 00:08:14



38. [32387](http://github.com/cms-sw/cmssw/pull/32387){:target="_blank"}  from **@missirol**: skip empty lines in JetCorrectorParameters ctor `analysis`  `db`  created: 2020-12-04 10:58:29 merged: 2020-12-07 18:03:00



39. [32385](http://github.com/cms-sw/cmssw/pull/32385){:target="_blank"}  from **@cms-sw**: Readd 1624.911, #2021 DD4hep from short matrix `pdmv`  `upgrade`  created: 2020-12-04 08:54:39 merged: 2020-12-04 15:35:16



40. [32384](http://github.com/cms-sw/cmssw/pull/32384){:target="_blank"}  from **@civanch**: Clean-up Geant4 interfaces `simulation`  created: 2020-12-04 01:38:09 merged: 2020-12-04 12:16:32



41. [32383](http://github.com/cms-sw/cmssw/pull/32383){:target="_blank"}  from **@Dr15Jones**: Removed debug globals used in Phase2L1ParticleFlow `l1`  `upgrade`  created: 2020-12-03 16:42:09 merged: 2020-12-09 00:47:49



42. [32382](http://github.com/cms-sw/cmssw/pull/32382){:target="_blank"}  from **@bsunanda**: Run3-hcx273 Utilize ESGetToken in HCAL RecHit validation code `dqm`  created: 2020-12-03 16:35:19 merged: 2020-12-04 08:56:57



43. [32381](http://github.com/cms-sw/cmssw/pull/32381){:target="_blank"}  from **@bsunanda**: Run3-hcx272 Update the testing code for objects from EventSetup `geometry`  created: 2020-12-03 16:17:45 merged: 2020-12-04 12:16:23



44. [32380](http://github.com/cms-sw/cmssw/pull/32380){:target="_blank"}  from **@Dr15Jones**: Make globals used by DTTrigPhase2Prod const `l1`  `upgrade`  created: 2020-12-03 15:24:22 merged: 2020-12-09 00:48:02



45. [32379](http://github.com/cms-sw/cmssw/pull/32379){:target="_blank"}  from **@makortel**: Fix some code checks warnings in FWCore `core`  created: 2020-12-03 14:29:28 merged: 2020-12-03 20:37:13



46. [32378](http://github.com/cms-sw/cmssw/pull/32378){:target="_blank"}  from **@bsunanda**: Run3-alca180 Remove usage of ESHandle in HcalAlCaRecoProducers `alca`  created: 2020-12-03 13:48:49 merged: 2020-12-08 00:11:30



47. [32375](http://github.com/cms-sw/cmssw/pull/32375){:target="_blank"}  from **@christopheralanwest**: New JEC for 2018 HI re-miniAOD `alca`  created: 2020-12-03 05:22:23 merged: 2020-12-08 06:36:07



48. [32374](http://github.com/cms-sw/cmssw/pull/32374){:target="_blank"}  from **@bsunanda**: Run3-alca179 Use ESGetToken in the analyzers of Calibration/HcalCalibAlgos `alca`  created: 2020-12-02 18:40:30 merged: 2020-12-03 11:53:26



49. [32373](http://github.com/cms-sw/cmssw/pull/32373){:target="_blank"}  from **@wddgit**: Make the skipBadFiles option work, add tests `comparison`  `core`  created: 2020-12-02 18:20:58 merged: 2020-12-04 15:36:14



50. [32371](http://github.com/cms-sw/cmssw/pull/32371){:target="_blank"}  from **@ianna**: [DD4hep] evaluate all numeric parameters in tracker detector description `geometry`  created: 2020-12-02 17:17:48 merged: 2020-12-02 21:18:26



51. [32368](http://github.com/cms-sw/cmssw/pull/32368){:target="_blank"}  from **@bsunanda**: Run2-gex42x Update GeometryConf.py with additional scenarios for 2017Plan1 and 2018 `geometry`  `operations`  created: 2020-12-02 14:46:03 merged: 2020-12-14 08:53:38



52. [32366](http://github.com/cms-sw/cmssw/pull/32366){:target="_blank"}  from **@bsunanda**: Run2-gex42 Extend the payload creators of 2017Plan1, 2018, 2021 for more scenarios `db`  created: 2020-12-02 14:06:22 merged: 2020-12-09 19:42:02



53. [32365](http://github.com/cms-sw/cmssw/pull/32365){:target="_blank"}  from **@panoskatsoulis**: Era support for the BMTF Packer `l1`  created: 2020-12-02 13:42:17 merged: 2020-12-15 11:37:08



54. [32363](http://github.com/cms-sw/cmssw/pull/32363){:target="_blank"}  from **@mmusich**: Adapt Tracker Alignment PV Validation to work with phase-2 geometries `alca`  created: 2020-12-02 09:30:22 merged: 2020-12-08 00:10:05



55. [32362](http://github.com/cms-sw/cmssw/pull/32362){:target="_blank"}  from **@guitargeek**: Merge remaining .h files with .cc plugin files in EgammaIsolationAlogs `reconstruction`  created: 2020-12-01 22:34:08 merged: 2020-12-07 13:05:08



56. [32361](http://github.com/cms-sw/cmssw/pull/32361){:target="_blank"}  from **@cvuosalo**: Fix small bugs in geometry DB payload scripts `db`  `dqm`  `geometry`  created: 2020-12-01 21:32:12 merged: 2020-12-09 19:39:58



57. [32360](http://github.com/cms-sw/cmssw/pull/32360){:target="_blank"}  from **@dildick**: Set Run-3 CCLUT algo results in LCT (CCLUT-10)  `l1`  created: 2020-12-01 18:59:36 merged: 2020-12-08 18:19:56



58. [32359](http://github.com/cms-sw/cmssw/pull/32359){:target="_blank"}  from **@Dr15Jones**: Fix race conditions in the PluginSystem `core`  created: 2020-12-01 18:47:06 merged: 2020-12-02 04:13:56



59. [32355](http://github.com/cms-sw/cmssw/pull/32355){:target="_blank"}  from **@bsunanda**: Run3-alca178 Use ESGetToken for the objects from EventSetup in the remaining examples after #32336 `alca`  created: 2020-12-01 15:29:57 merged: 2020-12-02 12:23:56



60. [32354](http://github.com/cms-sw/cmssw/pull/32354){:target="_blank"}  from **@cms-l1t-offline**: Pr112x L1T Customization for Unprefireable Bit - Follow up `l1`  created: 2020-12-01 13:27:35 merged: 2020-12-02 09:26:21



61. [32352](http://github.com/cms-sw/cmssw/pull/32352){:target="_blank"}  from **@silviodonato**: Remove temporarily ctppsProtons from recoCTPPSTask (Run-3 only) `reconstruction`  created: 2020-12-01 12:41:47 merged: 2020-12-01 17:28:06



62. [32351](http://github.com/cms-sw/cmssw/pull/32351){:target="_blank"}  from **@bsunanda**: Run3-gex41 Complementing the geometry scenarios of special cases with the Reco cff's `geometry`  `upgrade`  created: 2020-12-01 12:40:06 merged: 2020-12-02 17:29:57



63. [32345](http://github.com/cms-sw/cmssw/pull/32345){:target="_blank"}  from **@christopheralanwest**: Remove obsolete record SiPixelCPEGenericErrorParmRcd from frozen HLT GTs `alca`  created: 2020-12-01 00:29:10 merged: 2020-12-01 14:59:32



64. [32343](http://github.com/cms-sw/cmssw/pull/32343){:target="_blank"}  from **@missirol**: removal of TH1::StatOverflows calls in FastTimerService? `dqm`  `hlt`  created: 2020-11-30 20:12:10 merged: 2020-12-08 18:26:54



65. [32342](http://github.com/cms-sw/cmssw/pull/32342){:target="_blank"}  from **@guitargeek**: Implement fillDescriptions() for producers in RecoParticleFlow/PFSimProducer `reconstruction`  created: 2020-11-30 19:22:38 merged: 2020-12-04 17:34:27



66. [32341](http://github.com/cms-sw/cmssw/pull/32341){:target="_blank"}  from **@missirol**: [Puppi] option to use generic PU proxy `analysis`  `reconstruction`  created: 2020-11-30 18:58:31 merged: 2020-12-10 00:17:15



67. [32339](http://github.com/cms-sw/cmssw/pull/32339){:target="_blank"}  from **@ianna**: [DD4hep] remove an evaluator usage beyond geometry construction `geometry`  `simulation`  created: 2020-11-30 17:18:50 merged: 2020-12-02 00:24:38



68. [32337](http://github.com/cms-sw/cmssw/pull/32337){:target="_blank"}  from **@theofil**: adding configuration files for Matchbox and standalone H7 `generators`  created: 2020-11-30 16:16:12 merged: 2020-12-01 17:39:07



69. [32336](http://github.com/cms-sw/cmssw/pull/32336){:target="_blank"}  from **@bsunanda**: Run3-alca177 Use of ESGetToken and small change in StudyCaloResponse `alca`  created: 2020-11-30 16:07:53 merged: 2020-12-03 10:01:09



70. [32333](http://github.com/cms-sw/cmssw/pull/32333){:target="_blank"}  from **@thomreis**: Add RecoFakeHLT steps to 2018 Patatrack WFs to enable GPU modifiers `pdmv`  `upgrade`  created: 2020-11-30 11:43:29 merged: 2020-11-30 19:47:11



71. [32328](http://github.com/cms-sw/cmssw/pull/32328){:target="_blank"}  from **@lathomas**: PUPPI v15 bug/crash fix for NANOAOD `analysis`  `xpog`  created: 2020-11-30 01:47:21 merged: 2020-12-01 00:22:46



72. [32327](http://github.com/cms-sw/cmssw/pull/32327){:target="_blank"}  from **@guitargeek**: Remove GsfEleDEtaInSeedCut and GsfEleDPhiInCut `reconstruction`  created: 2020-11-29 18:12:13 merged: 2020-12-01 15:02:36



73. [32326](http://github.com/cms-sw/cmssw/pull/32326){:target="_blank"}  from **@mandrenguyen**: Set default value for jets w/o SV info in HI CSV tagger  `reconstruction`  created: 2020-11-29 16:55:36 merged: 2020-12-02 00:15:52



74. [32325](http://github.com/cms-sw/cmssw/pull/32325){:target="_blank"}  from **@mandrenguyen**: Use cleaned PF candidates in UE subtraction in HI miniAOD `reconstruction`  created: 2020-11-29 13:02:01 merged: 2020-12-02 00:21:07



75. [32324](http://github.com/cms-sw/cmssw/pull/32324){:target="_blank"}  from **@guitargeek**: Clean some more BuildFiles `alca`  `dqm`  `l1`  `reconstruction`  `upgrade`  created: 2020-11-29 12:24:11 merged: 2020-12-07 18:19:22



76. [32319](http://github.com/cms-sw/cmssw/pull/32319){:target="_blank"}  from **@agrohsje**: adjust cp5 cr fragments to compensate P8.240 changes `generators`  created: 2020-11-27 20:18:24 merged: 2020-11-30 13:29:14



77. [32313](http://github.com/cms-sw/cmssw/pull/32313){:target="_blank"}  from **@slava77**: remove 11624.911, #2021 DD4hep from short matrix (until it runs reliably) `pdmv`  `upgrade`  created: 2020-11-27 13:59:08 merged: 2020-11-28 09:23:36



78. [32311](http://github.com/cms-sw/cmssw/pull/32311){:target="_blank"}  from **@jsalfeld**: changing to esConsumes after fix in  #32217 `hlt`  created: 2020-11-27 11:22:10 merged: 2020-12-02 12:23:31



79. [32310](http://github.com/cms-sw/cmssw/pull/32310){:target="_blank"}  from **@intrepid42**: ParticleLevelProducer: check for leptonic decays of tag particles `generators`  created: 2020-11-27 10:49:48 merged: 2020-11-30 10:34:32



80. [32307](http://github.com/cms-sw/cmssw/pull/32307){:target="_blank"}  from **@smuzaffar**: [clang] Initialize data member to fix clang errors about explicit deleted def-constructor `analysis`  `reconstruction`  created: 2020-11-27 07:04:19 merged: 2020-11-28 09:08:27



81. [32305](http://github.com/cms-sw/cmssw/pull/32305){:target="_blank"}  from **@abhih1**: Fix reflection in tower mapping in Integrity error plots `dqm`  created: 2020-11-26 20:02:24 merged: 2020-11-30 10:32:36



82. [32302](http://github.com/cms-sw/cmssw/pull/32302){:target="_blank"}  from **@Dr15Jones**: Have PSet properly clone the allowAnyLabel_ option `core`  created: 2020-11-26 17:34:37 merged: 2020-12-01 09:45:41



83. [32301](http://github.com/cms-sw/cmssw/pull/32301){:target="_blank"}  from **@mmusich**: migrate Alignment/TrackerAlignment to use esConsumes `alca`  created: 2020-11-26 16:30:34 merged: 2020-12-01 15:19:55



84. [32300](http://github.com/cms-sw/cmssw/pull/32300){:target="_blank"}  from **@bsunanda**: Run3-gex40 Add scenarios with modified tracker material budgets for the Run3 scenario `geometry`  `operations`  `upgrade`  created: 2020-11-26 14:49:22 merged: 2020-12-01 13:27:44



85. [32299](http://github.com/cms-sw/cmssw/pull/32299){:target="_blank"}  from **@bsunanda**: Run3-gex39 Fix a bug in the zdcmaterials.xml file and also remove unnecessary materials `geometry`  created: 2020-11-26 13:57:48 merged: 2020-11-27 09:29:27



86. [32297](http://github.com/cms-sw/cmssw/pull/32297){:target="_blank"}  from **@andrzejnovak**: feat: allow for not sorting during PATJetUpdater call `analysis`  `reconstruction`  `xpog`  created: 2020-11-26 13:44:27 merged: 2020-12-15 18:29:24



87. [32295](http://github.com/cms-sw/cmssw/pull/32295){:target="_blank"}  from **@casarsa**: MTD simulation: explicit unit conversions `reconstruction`  `simulation`  `upgrade`  created: 2020-11-26 09:12:52 merged: 2020-12-04 15:37:32



88. [32287](http://github.com/cms-sw/cmssw/pull/32287){:target="_blank"}  from **@makortel**: Update EDProducer and EDAnalyzer skeletons and edmPythonConfigToCppValidation to show addWithDefaultLabel() in their examples `core`  created: 2020-11-25 16:07:09 merged: 2020-12-07 19:51:52



89. [32284](http://github.com/cms-sw/cmssw/pull/32284){:target="_blank"}  from **@fwyzard**: Implement the fillDescriptions method for RawStreamFileWriterForBU `daq`  `reconstruction`  created: 2020-11-25 14:17:43 merged: 2020-11-27 19:31:37



90. [32280](http://github.com/cms-sw/cmssw/pull/32280){:target="_blank"}  from **@mmusich**: optimize search algorithm for EventFilter/SiStripRawToDigi/plugins/WarningSummary.cc `reconstruction`  created: 2020-11-25 09:48:16 merged: 2020-11-27 19:35:54



91. [32279](http://github.com/cms-sw/cmssw/pull/32279){:target="_blank"}  from **@sroychow**: TrackerDQM: Migration of modules to use esConsumes `dqm`  created: 2020-11-25 08:26:48 merged: 2020-11-26 17:41:00



92. [32278](http://github.com/cms-sw/cmssw/pull/32278){:target="_blank"}  from **@saumyaphor4252**: Updated CosmicRateAnalyzer: MagField & Hits added, deleted latency `alca`  created: 2020-11-25 07:33:09 merged: 2020-12-01 00:15:52



93. [32271](http://github.com/cms-sw/cmssw/pull/32271){:target="_blank"}  from **@riga**: [TF] Accept const graphs in session creation `analysis`  `reconstruction`  created: 2020-11-24 22:53:06 merged: 2020-11-26 23:58:59



94. [32267](http://github.com/cms-sw/cmssw/pull/32267){:target="_blank"}  from **@dildick**: New GEM-CSC LUT generator `l1`  created: 2020-11-24 19:33:34 merged: 2020-12-01 14:55:55



95. [32266](http://github.com/cms-sw/cmssw/pull/32266){:target="_blank"}  from **@guitargeek**: Merge .h files with .cc plugin files in EgammaPhotonProducers `reconstruction`  created: 2020-11-24 18:56:46 merged: 2020-11-29 07:54:51



96. [32265](http://github.com/cms-sw/cmssw/pull/32265){:target="_blank"}  from **@hatakeyamak**: Remove unnecessary import of MessageLogger_cfi from RecoParticleFlow PFTracking configs `reconstruction`  created: 2020-11-24 18:18:11 merged: 2020-11-26 17:41:28



97. [32264](http://github.com/cms-sw/cmssw/pull/32264){:target="_blank"}  from **@bsunanda**: Run3-alca176 Introduce muon veto for isotrack analysis `alca`  created: 2020-11-24 17:28:20 merged: 2020-12-02 16:18:37



98. [32259](http://github.com/cms-sw/cmssw/pull/32259){:target="_blank"}  from **@guitargeek**: Merge .h files with .cc plugin files in EgammaIsolationAlogs `reconstruction`  created: 2020-11-24 13:32:52 merged: 2020-11-29 07:55:17



99. [32251](http://github.com/cms-sw/cmssw/pull/32251){:target="_blank"}  from **@mteroerd**: esConsume migration for APE and removing other static warnings `alca`  created: 2020-11-24 01:49:30 merged: 2020-12-03 10:00:25



100. [32248](http://github.com/cms-sw/cmssw/pull/32248){:target="_blank"}  from **@Dr15Jones**: Useful items for new MessageLogger syntax `core`  created: 2020-11-23 20:33:25 merged: 2020-12-01 00:16:36



101. [32244](http://github.com/cms-sw/cmssw/pull/32244){:target="_blank"}  from **@Dr15Jones**: Convert all remaining MessageLogger configurations to new syntax `alca`  `analysis`  `core`  `db`  `dqm`  `fastsim`  `generators`  `geometry`  `heterogeneous`  `hlt`  `l1`  `pdmv`  `reconstruction`  `simulation`  `upgrade`  created: 2020-11-23 14:09:18 merged: 2020-12-08 18:24:48



102. [32243](http://github.com/cms-sw/cmssw/pull/32243){:target="_blank"}  from **@cms-tau-pog**: Set fixes for tau reco at miniAOD `reconstruction`  created: 2020-11-23 13:42:43 merged: 2020-12-02 04:12:56



103. [32242](http://github.com/cms-sw/cmssw/pull/32242){:target="_blank"}  from **@cms-tau-pog**: Expand track information in lostTracks collection `analysis`  `reconstruction`  `xpog`  created: 2020-11-23 12:27:12 merged: 2020-11-27 00:00:08



104. [32235](http://github.com/cms-sw/cmssw/pull/32235){:target="_blank"}  from **@Dr15Jones**: Updated configurations in Reco* to new MessageLogger syntax `alca`  `reconstruction`  `upgrade`  created: 2020-11-21 16:59:34 merged: 2020-12-02 15:43:33



105. [32229](http://github.com/cms-sw/cmssw/pull/32229){:target="_blank"}  from **@Dr15Jones**: Updated configurations in IORawData to new MessageLogger syntax `alca`  created: 2020-11-21 16:55:12 merged: 2020-12-02 17:43:54



106. [32226](http://github.com/cms-sw/cmssw/pull/32226){:target="_blank"}  from **@Dr15Jones**: Updated configurations in FWCore to new MessageLogger syntax `core`  created: 2020-11-21 16:53:23 merged: 2020-11-30 18:08:15



107. [32220](http://github.com/cms-sw/cmssw/pull/32220){:target="_blank"}  from **@OzAmram**: Phase2 improved conditions and ntuple maker update `alca`  `db`  `geometry`  `reconstruction`  `upgrade`  created: 2020-11-20 19:36:58 merged: 2020-12-14 16:51:52



108. [32215](http://github.com/cms-sw/cmssw/pull/32215){:target="_blank"}  from **@Dr15Jones**: Updated configurations in CondTools/Si* to new MessageLogger syntax `alca`  `db`  `upgrade`  created: 2020-11-20 14:40:58 merged: 2020-12-03 00:38:14



109. [32211](http://github.com/cms-sw/cmssw/pull/32211){:target="_blank"}  from **@Dr15Jones**: Updated configurations in DPGAnalysis to new MessageLogger syntax `analysis`  `dqm`  `pdmv`  created: 2020-11-20 14:38:12 merged: 2020-11-26 17:42:07



110. [32207](http://github.com/cms-sw/cmssw/pull/32207){:target="_blank"}  from **@CTPPS**: dynamic conditions for PPS direct simulation `alca`  `db`  `dqm`  `geometry`  created: 2020-11-20 14:27:35 merged: 2020-12-08 09:51:42



111. [32203](http://github.com/cms-sw/cmssw/pull/32203){:target="_blank"}  from **@depasse**: Ecal DB PayloadInspector with two different tags `db`  created: 2020-11-20 09:20:23 merged: 2020-12-09 19:36:52



112. [32202](http://github.com/cms-sw/cmssw/pull/32202){:target="_blank"}  from **@hatakeyamak**: Adopt ChargedHadronPFTrackIsolationProducer for PFTICL candidates `reconstruction`  `upgrade`  created: 2020-11-20 07:32:03 merged: 2020-11-30 18:06:54



113. [32198](http://github.com/cms-sw/cmssw/pull/32198){:target="_blank"}  from **@Dr15Jones**: Updated configurations in CalibMuon to new MessageLogger syntax `alca`  created: 2020-11-19 21:49:28 merged: 2020-12-02 13:17:30



114. [32197](http://github.com/cms-sw/cmssw/pull/32197){:target="_blank"}  from **@Dr15Jones**: Updated configurations in CalibPPS to new MessageLogger syntax `alca`  created: 2020-11-19 21:48:57 merged: 2020-12-02 20:07:33



115. [32196](http://github.com/cms-sw/cmssw/pull/32196){:target="_blank"}  from **@Dr15Jones**: Updated configurations in CalibTracker to new MessageLogger syntax `alca`  `dqm`  created: 2020-11-19 21:48:13 merged: 2020-12-02 20:12:07



116. [32195](http://github.com/cms-sw/cmssw/pull/32195){:target="_blank"}  from **@Dr15Jones**: Updated configurations in Calibration to new MessageLogger syntax `alca`  created: 2020-11-19 21:47:36 merged: 2020-12-02 20:12:14



117. [32194](http://github.com/cms-sw/cmssw/pull/32194){:target="_blank"}  from **@Dr15Jones**: Updated configurations in CaloOnlineTools to new MessageLogger syntax `alca`  created: 2020-11-19 21:46:30 merged: 2020-12-02 20:12:24



118. [32193](http://github.com/cms-sw/cmssw/pull/32193){:target="_blank"}  from **@Dr15Jones**: Updated configurations in CondCore to new MessageLogger syntax `alca`  `db`  created: 2020-11-19 21:45:45 merged: 2020-11-27 09:27:07



119. [32192](http://github.com/cms-sw/cmssw/pull/32192){:target="_blank"}  from **@Dr15Jones**: Updated configurations in CondFormats to new MessageLogger syntax `alca`  `db`  created: 2020-11-19 21:45:07 merged: 2020-11-27 09:27:01



120. [32185](http://github.com/cms-sw/cmssw/pull/32185){:target="_blank"}  from **@Dr15Jones**: Updated configurations in Alignment to new MessageLogger syntax `alca`  created: 2020-11-19 21:23:07 merged: 2020-12-02 20:12:45



121. [32178](http://github.com/cms-sw/cmssw/pull/32178){:target="_blank"}  from **@mmusich**: add RecoLocalTracker_cff to TrackRefitters_cff `reconstruction`  created: 2020-11-18 17:02:47 merged: 2020-11-27 17:49:34



122. [32150](http://github.com/cms-sw/cmssw/pull/32150){:target="_blank"}  from **@trtomei**: DataFormats for Phase-2 L1T-HLT `hlt`  `l1`  `upgrade`  created: 2020-11-15 23:50:07 merged: 2020-12-08 18:23:13



123. [32102](http://github.com/cms-sw/cmssw/pull/32102){:target="_blank"}  from **@slomeo**: Migration to DD4Hep for RPC db Loader `db`  `geometry`  created: 2020-11-11 13:05:13 merged: 2020-12-09 19:36:27



124. [32093](http://github.com/cms-sw/cmssw/pull/32093){:target="_blank"}  from **@CMSTrackerDPG**: Migration of pixel code to esConsumes `alca`  `dqm`  `reconstruction`  `simulation`  created: 2020-11-10 22:56:39 merged: 2020-12-03 00:39:20



125. [32039](http://github.com/cms-sw/cmssw/pull/32039){:target="_blank"}  from **@mariadalfonso**: Patatrack integration - Hcal conditions (13/N) `alca`  `db`  created: 2020-11-05 16:00:50 merged: 2020-12-02 11:27:13



126. [31985](http://github.com/cms-sw/cmssw/pull/31985){:target="_blank"}  from **@cms-l1t-offline**: Pr112x  L1T Unprefireable Bit Functionality for miniAOD Reprocessing `analysis`  `l1`  `reconstruction`  created: 2020-10-29 13:23:08 merged: 2020-11-26 20:06:07



127. [31720](http://github.com/cms-sw/cmssw/pull/31720){:target="_blank"}  from **@cms-patatrack**: Patatrack integration - HCAL local reconstruction (8/N) `heterogeneous`  `reconstruction`  created: 2020-10-08 21:48:55 merged: 2020-12-08 10:40:02



128. [31601](http://github.com/cms-sw/cmssw/pull/31601){:target="_blank"}  from **@cms-l1t-offline**: L1T Phase2 NN Tau (11_3_X) `l1`  `upgrade`  created: 2020-09-27 22:39:10 merged: 2020-12-02 00:17:57



129. [31484](http://github.com/cms-sw/cmssw/pull/31484){:target="_blank"}  from **@forthommel**: [PPS] 2021 conditions for timing detectors geometry (resubmission after DD4hep) `alca`  `db`  `dqm`  `geometry`  `reconstruction`  `simulation`  created: 2020-09-16 12:43:03 merged: 2020-12-11 09:28:25



130. [31220](http://github.com/cms-sw/cmssw/pull/31220){:target="_blank"}  from **@bainbrid**: Add low-pT electrons to MINIAOD, update ID, improve end user experience `analysis`  `reconstruction`  `xpog`  created: 2020-08-24 20:39:41 merged: 2020-12-02 16:14:58



131. [29553](http://github.com/cms-sw/cmssw/pull/29553){:target="_blank"}  from **@makortel**: Delete unscheduled modules that are not consumed by any scheduled module `core`  `heterogeneous`  created: 2020-04-24 01:38:30 merged: 2020-12-02 11:54:04



#### CMSDIST Changes between Tags REL/CMSSW_11_2_0_pre10/slc7_amd64_gcc900 and REL/CMSSW_11_3_0_pre1/slc7_amd64_gcc900:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_11_2_0_pre10/slc7_amd64_gcc900...REL/CMSSW_11_3_0_pre1/slc7_amd64_gcc900)



1. [6508](http://github.com/cms-sw/cmsdist/pull/6508){:target="_blank"}  from **@belforte**: make crab-pre point to previous tag of crabserver created: 2020-12-15 09:44:41 merged: 2020-12-15 10:57:04

2. [6506](http://github.com/cms-sw/cmsdist/pull/6506){:target="_blank"}  from **@belforte**: update crab-pre to same version as prod and dev. Ol once does not wor created: 2020-12-13 15:49:42 merged: 2020-12-13 20:31:52

3. [6505](http://github.com/cms-sw/cmsdist/pull/6505){:target="_blank"}  from **@belforte**: align crab-prod with tatest, tested crab-dev created: 2020-12-13 15:47:20 merged: 2020-12-13 20:32:12

4. [6504](http://github.com/cms-sw/cmsdist/pull/6504){:target="_blank"}  from **@cms-sw**: fix libjpeg-turbo toolfile name created: 2020-12-13 15:09:41 merged: 2020-12-13 20:32:34

5. [6503](http://github.com/cms-sw/cmsdist/pull/6503){:target="_blank"}  from **@cms-sw**: use lower case tools created: 2020-12-13 00:05:59 merged: 2020-12-13 15:57:25

6. [6499](http://github.com/cms-sw/cmsdist/pull/6499){:target="_blank"}  from **@Dominic-Stafford**: Rename herwigpp tool to herwig7 created: 2020-12-11 15:49:06 merged: 2020-12-15 11:14:51

7. [6497](http://github.com/cms-sw/cmsdist/pull/6497){:target="_blank"}  from **@belforte**: use new ServerUtilities from CRABServer created: 2020-12-11 14:32:29 merged: 2020-12-11 21:28:37

8. [6493](http://github.com/cms-sw/cmsdist/pull/6493){:target="_blank"}  from **@cms-sw**: added missing fwlite packages created: 2020-12-10 13:24:27 merged: 2020-12-10 13:24:37

9. [6490](http://github.com/cms-sw/cmsdist/pull/6490){:target="_blank"}  from **@mrodozov**: Change source for awkward array created: 2020-12-08 14:34:51 merged: 2020-12-09 09:03:20

10. [6485](http://github.com/cms-sw/cmsdist/pull/6485){:target="_blank"}  from **@intrepid42**: Rivet 3.1.3 and YODA 1.8.5 created: 2020-12-06 07:49:16 merged: 2020-12-13 17:12:04

11. [6480](http://github.com/cms-sw/cmsdist/pull/6480){:target="_blank"}  from **@cms-sw**: Update py3-nootbook to version 6.1.5 created: 2020-12-03 15:00:31 merged: 2020-12-03 18:25:12

12. [6476](http://github.com/cms-sw/cmsdist/pull/6476){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-CSCTriggerPrimitives to V00-04-00 created: 2020-12-01 14:53:19 merged: 2020-12-01 14:54:47

13. [6471](http://github.com/cms-sw/cmsdist/pull/6471){:target="_blank"}  from **@cms-sw**: [11.3.X]Update CMS monitoring tools created: 2020-12-01 06:34:34 merged: 2020-12-01 06:35:11

14. [6462](http://github.com/cms-sw/cmsdist/pull/6462){:target="_blank"}  from **@Dominic-Stafford**: Upgrade Herwig to v7.2.1, and add patch to fix crash when reading lhe created: 2020-11-27 17:02:30 merged: 2020-12-01 11:01:12

15. [6461](http://github.com/cms-sw/cmsdist/pull/6461){:target="_blank"}  from **@cms-sw**: [BuildRuiel] Do not drop optimization flags for header checks created: 2020-11-27 09:31:59 merged: 2020-11-27 10:55:40

16. [6460](http://github.com/cms-sw/cmsdist/pull/6460){:target="_blank"}  from **@cms-sw**: BuiidRule: Allow to set flags for header checks via BuildFile created: 2020-11-27 07:36:07 merged: 2020-11-27 07:36:40

17. [6459](http://github.com/cms-sw/cmsdist/pull/6459){:target="_blank"}  from **@cms-sw**: [ROOT][11.3.X] Update root to 6.22.06 created: 2020-11-26 22:05:05 merged: 2020-11-28 21:38:18

18. [6456](http://github.com/cms-sw/cmsdist/pull/6456){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-ElectronIdentification to V01-03-00 created: 2020-11-26 13:24:20 merged: 2020-11-28 20:48:23

19. [6455](http://github.com/cms-sw/cmsdist/pull/6455){:target="_blank"}  from **@cms-sw**: [OpenLoops] do not build pplljj_ew for aarch64 as it again fails to build created: 2020-11-26 11:05:09 merged: 2020-11-26 11:09:47

20. [6451](http://github.com/cms-sw/cmsdist/pull/6451){:target="_blank"}  from **@cms-sw**: [cmsmon] cleanup hey-x509-csv-fixes once build is done created: 2020-11-25 22:14:08 merged: 2020-11-26 09:56:03
