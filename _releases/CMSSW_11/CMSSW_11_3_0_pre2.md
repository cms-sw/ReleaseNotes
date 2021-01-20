---
layout: post
rel_link:  "11_3_0_pre2"
title:  "CMSSW_11_3_0_pre2"
date:   2021-01-19 20:41:13
categories: cmssw
relmajor: 11
relminor: 3
relsubminor: 0
relpre: _pre2
---

# CMSSW_11_3_0_pre2
#### Changes since CMSSW_11_3_0_pre1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_11_3_0_pre1...CMSSW_11_3_0_pre2)



1. [32682](http://github.com/cms-sw/cmssw/pull/32682){:target="_blank"}  from **@perrotta**: Fix a couple of sparse issues in reco pointed out by the static analyzer `reconstruction`  created: 2021-01-19 13:45:57 merged: 2021-01-19 20:29:53



2. [32675](http://github.com/cms-sw/cmssw/pull/32675){:target="_blank"}  from **@slava77**: fix in PixelTrackBuilder and MuonIdProducer to get debug build work for static ana `reconstruction`  created: 2021-01-16 21:01:35 merged: 2021-01-19 01:59:46



3. [32674](http://github.com/cms-sw/cmssw/pull/32674){:target="_blank"}  from **@Dr15Jones**: Avoid writing off beginning of arrays in RPCMonitorClient `dqm`  created: 2021-01-16 15:39:40 merged: 2021-01-19 17:19:55



4. [32673](http://github.com/cms-sw/cmssw/pull/32673){:target="_blank"}  from **@kpedro88**: finecalo patches v1 (rebased) `operations`  `simulation`  created: 2021-01-15 21:49:04 merged: 2021-01-19 09:02:49



5. [32671](http://github.com/cms-sw/cmssw/pull/32671){:target="_blank"}  from **@smuzaffar**: Revert #25298; memory leak fix for HepPDT::HeavyIonUnknownID `simulation`  created: 2021-01-15 12:09:59 merged: 2021-01-18 08:36:28



6. [32669](http://github.com/cms-sw/cmssw/pull/32669){:target="_blank"}  from **@bsunanda**: Run4-hgx284x Modify the conversion code to make titles for HGCal `geometry`  `upgrade`  created: 2021-01-14 15:00:56 merged: 2021-01-16 02:08:08



7. [32667](http://github.com/cms-sw/cmssw/pull/32667){:target="_blank"}  from **@cvuosalo**: [DD4hep] Fix PPS simulation so physical volume names are recognized `simulation`  created: 2021-01-13 23:39:58 merged: 2021-01-14 14:18:45



8. [32665](http://github.com/cms-sw/cmssw/pull/32665){:target="_blank"}  from **@Dr15Jones**: Set TrackMerger::debug_ in the constructor `reconstruction`  created: 2021-01-13 22:15:53 merged: 2021-01-14 09:08:46



9. [32664](http://github.com/cms-sw/cmssw/pull/32664){:target="_blank"}  from **@bsunanda**: RUn3-gex46 Make printouts more friendly in dumping geometry for firework `visualization`  created: 2021-01-13 21:58:59 merged: 2021-01-14 08:44:33



10. [32663](http://github.com/cms-sw/cmssw/pull/32663){:target="_blank"}  from **@emacdonald16**: L1 Tk DQM, plot range `dqm`  created: 2021-01-13 21:11:41 merged: 2021-01-14 15:03:22



11. [32661](http://github.com/cms-sw/cmssw/pull/32661){:target="_blank"}  from **@hatakeyamak**: PF validation update 11_3_0_pre1 `dqm`  created: 2021-01-13 19:48:59 merged: 2021-01-14 15:01:56



12. [32660](http://github.com/cms-sw/cmssw/pull/32660){:target="_blank"}  from **@bsunanda**: Run4-hgx284 Algorithm to make partial silicon modules `geometry`  `upgrade`  created: 2021-01-13 19:48:13 merged: 2021-01-17 06:00:22



13. [32658](http://github.com/cms-sw/cmssw/pull/32658){:target="_blank"}  from **@Dr15Jones**: Do not allow unscheduled execution after prefetching `core`  created: 2021-01-13 15:51:31 merged: 2021-01-14 00:17:42



14. [32651](http://github.com/cms-sw/cmssw/pull/32651){:target="_blank"}  from **@guitargeek**: Some modernization of plugins in EgammaIsolationAlgos `reconstruction`  created: 2021-01-13 11:40:08 merged: 2021-01-16 02:08:59



15. [32650](http://github.com/cms-sw/cmssw/pull/32650){:target="_blank"}  from **@cms-sw**: Remove gpu workflows from runTheMatrix defaults `pdmv`  `upgrade`  created: 2021-01-13 08:39:53 merged: 2021-01-13 09:59:12



16. [32649](http://github.com/cms-sw/cmssw/pull/32649){:target="_blank"}  from **@dan131riley**: Remove legacy memory barriers `core`  created: 2021-01-12 17:46:07 merged: 2021-01-13 00:10:36



17. [32648](http://github.com/cms-sw/cmssw/pull/32648){:target="_blank"}  from **@srimanob**: Update input of nanoULremini wf `pdmv`  `upgrade`  created: 2021-01-12 16:57:58 merged: 2021-01-13 05:20:45



18. [32645](http://github.com/cms-sw/cmssw/pull/32645){:target="_blank"}  from **@martatornago**: ETL v5 (D73) units of measurement moved to constant section `geometry`  `upgrade`  created: 2021-01-12 16:03:51 merged: 2021-01-13 05:20:32



19. [32640](http://github.com/cms-sw/cmssw/pull/32640){:target="_blank"}  from **@CTPPS**: PPS: fix/improvement of CompositeESSource `alca`  created: 2021-01-12 11:05:16 merged: 2021-01-14 14:16:53



20. [32636](http://github.com/cms-sw/cmssw/pull/32636){:target="_blank"}  from **@colizz**: Fix the ExternalGeneratorFilter argument passing to python config `generators`  created: 2021-01-12 10:42:47 merged: 2021-01-12 14:39:38



21. [32635](http://github.com/cms-sw/cmssw/pull/32635){:target="_blank"}  from **@silviodonato**: Update DeepCore wf from 11634.17 (TTbar) to 11723.17 (QCD_Pt_1800_2400_14) `pdmv`  `upgrade`  created: 2021-01-12 09:49:58 merged: 2021-01-13 00:10:50



22. [32633](http://github.com/cms-sw/cmssw/pull/32633){:target="_blank"}  from **@chayanit**: Update 2021 relval matrix for IB test `pdmv`  `upgrade`  created: 2021-01-12 04:55:06 merged: 2021-01-18 14:55:09



23. [32631](http://github.com/cms-sw/cmssw/pull/32631){:target="_blank"}  from **@Dr15Jones**: Added missing ROOT dependency for test in CondCore/SiStripPlugins `db`  created: 2021-01-11 16:31:53 merged: 2021-01-14 09:42:32



24. [32629](http://github.com/cms-sw/cmssw/pull/32629){:target="_blank"}  from **@Dr15Jones**: Removed unnecessary dependency from RecoParticleFlow/PFProducer `reconstruction`  created: 2021-01-11 15:49:06 merged: 2021-01-12 00:36:13



25. [32627](http://github.com/cms-sw/cmssw/pull/32627){:target="_blank"}  from **@bsunanda**: Run4-hgx283x Second step for V15 geometry of HGCal `geometry`  `upgrade`  created: 2021-01-10 21:46:49 merged: 2021-01-12 02:07:22



26. [32626](http://github.com/cms-sw/cmssw/pull/32626){:target="_blank"}  from **@guitargeek**: Use EDPutToken in ReducedEGProducer and modernize GEDPhotonCoreProducer `reconstruction`  created: 2021-01-10 17:45:24 merged: 2021-01-19 17:49:41



27. [32625](http://github.com/cms-sw/cmssw/pull/32625){:target="_blank"}  from **@jeongeun**: drop type spec in RecoLocalTracker `reconstruction`  `upgrade`  created: 2021-01-10 13:16:34 merged: 2021-01-15 03:56:02



28. [32624](http://github.com/cms-sw/cmssw/pull/32624){:target="_blank"}  from **@jeongeun**: drop type specifications in RecoLocalCalo `reconstruction`  created: 2021-01-09 13:33:48 merged: 2021-01-10 02:02:27



29. [32623](http://github.com/cms-sw/cmssw/pull/32623){:target="_blank"}  from **@jeongeun**: drop type specifications in RecoLocalMuon `reconstruction`  created: 2021-01-09 13:28:53 merged: 2021-01-10 02:02:13



30. [32622](http://github.com/cms-sw/cmssw/pull/32622){:target="_blank"}  from **@Dr15Jones**: Added include of cassert to Migration.h `core`  created: 2021-01-08 22:24:22 merged: 2021-01-11 20:52:09



31. [32621](http://github.com/cms-sw/cmssw/pull/32621){:target="_blank"}  from **@Dr15Jones**: Avoid seg fault in HTXSRivetProducer `generators`  created: 2021-01-08 20:45:01 merged: 2021-01-11 00:00:34



32. [32620](http://github.com/cms-sw/cmssw/pull/32620){:target="_blank"}  from **@fwyzard**: Implement support for Event::getByToken for a GenericHandle `core`  created: 2021-01-08 20:36:57 merged: 2021-01-12 14:15:50



33. [32617](http://github.com/cms-sw/cmssw/pull/32617){:target="_blank"}  from **@fabiocos**: MTD geometry: fix mtd.xml for scenario D49 for DD4hep compatibility `geometry`  `upgrade`  created: 2021-01-08 09:05:43 merged: 2021-01-11 15:22:07



34. [32615](http://github.com/cms-sw/cmssw/pull/32615){:target="_blank"}  from **@bsunanda**: Phase2-hgx283x Correct earlier versions for orientations of the depleted layers `geometry`  `upgrade`  created: 2021-01-07 21:15:44 merged: 2021-01-12 02:07:16



35. [32614](http://github.com/cms-sw/cmssw/pull/32614){:target="_blank"}  from **@Dr15Jones**: Principal::getProvenance can no longer trigger unscheduled execution `analysis`  `core`  `dqm`  `hlt`  `l1`  `reconstruction`  `simulation`  created: 2021-01-07 19:30:52 merged: 2021-01-13 10:50:11



36. [32613](http://github.com/cms-sw/cmssw/pull/32613){:target="_blank"}  from **@guitargeek**: Merge .h with .cc files of plugins in EgammaHFProducers `reconstruction`  created: 2021-01-07 18:27:32 merged: 2021-01-13 00:11:27



37. [32612](http://github.com/cms-sw/cmssw/pull/32612){:target="_blank"}  from **@ghugo83**: Fix ProdCuts and Sensitive detectors lists creation in DD4hep workflow `simulation`  created: 2021-01-07 15:06:28 merged: 2021-01-09 13:09:26



38. [32611](http://github.com/cms-sw/cmssw/pull/32611){:target="_blank"}  from **@bsunanda**: Run4-hgx283 Next step for V15 geometry of HGCal `geometry`  `upgrade`  created: 2021-01-07 15:02:13 merged: 2021-01-11 15:29:27



39. [32610](http://github.com/cms-sw/cmssw/pull/32610){:target="_blank"}  from **@ghugo83**: Also fix SpecPars names in ZDC `geometry`  `upgrade`  created: 2021-01-07 14:58:57 merged: 2021-01-12 02:06:32



40. [32609](http://github.com/cms-sw/cmssw/pull/32609){:target="_blank"}  from **@mmusich**: Tracker Alignment Payload Inspector: migration to new class templates `db`  created: 2021-01-07 10:24:51 merged: 2021-01-14 14:16:14



41. [32608](http://github.com/cms-sw/cmssw/pull/32608){:target="_blank"}  from **@smuzaffar**: add root histpainter deps to fix UBSAN issue `db`  created: 2021-01-06 15:13:14 merged: 2021-01-07 09:26:22



42. [32607](http://github.com/cms-sw/cmssw/pull/32607){:target="_blank"}  from **@Dr15Jones**: Reduce use of Worker::doWork `core`  created: 2021-01-06 14:05:53 merged: 2021-01-06 23:57:34



43. [32606](http://github.com/cms-sw/cmssw/pull/32606){:target="_blank"}  from **@forthommel**: [PPS] Thread-safe ES condition retrieval `dqm`  `reconstruction`  `simulation`  created: 2021-01-05 22:59:16 merged: 2021-01-07 17:12:16



44. [32605](http://github.com/cms-sw/cmssw/pull/32605){:target="_blank"}  from **@bsunanda**: Run3-hcx283 Use ESGetToken in CalibCalorimetry/HcalPlugins `alca`  created: 2021-01-05 18:58:01 merged: 2021-01-15 09:18:26



45. [32604](http://github.com/cms-sw/cmssw/pull/32604){:target="_blank"}  from **@bsunanda**: Run3-hcx282 Use ESGetToken in CalibCalorimetry/CastorCalib `alca`  created: 2021-01-05 18:40:34 merged: 2021-01-11 15:42:49



46. [32603](http://github.com/cms-sw/cmssw/pull/32603){:target="_blank"}  from **@CTPPS**: PPS: fix z sign in diamond geometry `dqm`  `geometry`  `reconstruction`  created: 2021-01-05 15:39:08 merged: 2021-01-07 04:10:52



47. [32602](http://github.com/cms-sw/cmssw/pull/32602){:target="_blank"}  from **@CTPPS**: PPS direct simulation: add 2021 profile `dqm`  `geometry`  created: 2021-01-05 12:02:09 merged: 2021-01-06 23:56:59



48. [32600](http://github.com/cms-sw/cmssw/pull/32600){:target="_blank"}  from **@Dr15Jones**: Set all member data in SiPixelGenError constructor `db`  `reconstruction`  created: 2021-01-04 20:47:34 merged: 2021-01-14 14:15:45



49. [32599](http://github.com/cms-sw/cmssw/pull/32599){:target="_blank"}  from **@bsunanda**: Phase2-hgx273 Zeroth Step for going to V15 geometry of HGCal `geometry`  `upgrade`  created: 2021-01-04 17:41:13 merged: 2021-01-07 04:11:06



50. [32598](http://github.com/cms-sw/cmssw/pull/32598){:target="_blank"}  from **@mmusich**: Migrate to esConsumes two Cond* packages `alca`  `db`  `upgrade`  created: 2021-01-04 16:23:38 merged: 2021-01-14 14:14:37



51. [32595](http://github.com/cms-sw/cmssw/pull/32595){:target="_blank"}  from **@bsunanda**: Run3-sim80 Make the Cherenkov example working for DDD `geometry`  `simulation`  created: 2021-01-01 18:12:28 merged: 2021-01-05 08:17:48



52. [32594](http://github.com/cms-sw/cmssw/pull/32594){:target="_blank"}  from **@Sam-Harper**: E/gamma HLT L1 Track Isolation Producer & TTTrack typedef: 11_3_X `hlt`  `l1`  `reconstruction`  `upgrade`  created: 2020-12-31 11:13:22 merged: 2021-01-14 00:11:43



53. [32593](http://github.com/cms-sw/cmssw/pull/32593){:target="_blank"}  from **@bsunanda**: Run3-hcx281 Make showerlibrary producer work `core`  `simulation`  created: 2020-12-31 00:09:17 merged: 2021-01-08 19:52:16



54. [32591](http://github.com/cms-sw/cmssw/pull/32591){:target="_blank"}  from **@fwyzard**: Rename local variables according to the coding rules `db`  `reconstruction`  created: 2020-12-30 16:18:59 merged: 2021-01-14 14:19:35



55. [32590](http://github.com/cms-sw/cmssw/pull/32590){:target="_blank"}  from **@bsunanda**: Run3-hcx280 Use ESGetToken in CalibCalorimetry/HcalAlgos `alca`  created: 2020-12-28 16:45:29 merged: 2021-01-06 00:04:56



56. [32589](http://github.com/cms-sw/cmssw/pull/32589){:target="_blank"}  from **@Dr15Jones**: Fix incorrect cast in CastorShowerLibrary `simulation`  created: 2020-12-28 16:35:12 merged: 2021-01-05 08:19:07



57. [32588](http://github.com/cms-sw/cmssw/pull/32588){:target="_blank"}  from **@guitargeek**: Migrate EcalBasicClusterLocalContCorrection to ESTokens `reconstruction`  created: 2020-12-28 11:35:10 merged: 2021-01-07 17:13:28



58. [32587](http://github.com/cms-sw/cmssw/pull/32587){:target="_blank"}  from **@lecriste**: SimCluster-LayerCluster associator implementation `simulation`  `upgrade`  created: 2020-12-26 23:40:42 merged: 2021-01-11 13:31:31



59. [32586](http://github.com/cms-sw/cmssw/pull/32586){:target="_blank"}  from **@cms-patatrack**: Simplify cudacompat layer to use a 1-dimensional grid `heterogeneous`  created: 2020-12-26 00:33:13 merged: 2020-12-26 10:25:09



60. [32584](http://github.com/cms-sw/cmssw/pull/32584){:target="_blank"}  from **@AndreaBellora**: CT-PPS DQM: Minor bug fix and improved readability `dqm`  created: 2020-12-24 20:52:00 merged: 2021-01-05 00:11:22



61. [32583](http://github.com/cms-sw/cmssw/pull/32583){:target="_blank"}  from **@bsunanda**: Run3-gex45 Use of ESGetToken in EcalAlgo examples `geometry`  created: 2020-12-24 16:40:31 merged: 2021-01-03 00:34:08



62. [32579](http://github.com/cms-sw/cmssw/pull/32579){:target="_blank"}  from **@slava77**: tobTecStepTrackCandidates.onlyPixelHitsForSeedCleaner False `reconstruction`  created: 2020-12-24 00:14:28 merged: 2021-01-14 14:17:57



63. [32578](http://github.com/cms-sw/cmssw/pull/32578){:target="_blank"}  from **@cvuosalo**: [DD4hep] Make special Sim script output stay same after DD4hep units change `simulation`  created: 2020-12-23 21:51:28 merged: 2020-12-25 12:13:27



64. [32577](http://github.com/cms-sw/cmssw/pull/32577){:target="_blank"}  from **@bsunanda**: Run3-hcx279 Use ESGetToken and utilize more advised computing styles `dqm`  created: 2020-12-23 16:52:42 merged: 2020-12-24 14:31:40



65. [32573](http://github.com/cms-sw/cmssw/pull/32573){:target="_blank"}  from **@bsunanda**: Run3-hcx278 Update HcalIsolatedTrackReco for accessing objects from EventSetup `alca`  created: 2020-12-22 17:09:51 merged: 2020-12-24 00:10:23



66. [32572](http://github.com/cms-sw/cmssw/pull/32572){:target="_blank"}  from **@forthommel**: [PPS] Systematic use of emplace_back `alca`  `dqm`  `reconstruction`  created: 2020-12-22 15:20:16 merged: 2020-12-27 01:47:37



67. [32570](http://github.com/cms-sw/cmssw/pull/32570){:target="_blank"}  from **@guitargeek**: Clean some more BuildFiles `analysis`  `dqm`  `reconstruction`  `simulation`  `upgrade`  `xpog`  created: 2020-12-22 12:17:37 merged: 2020-12-30 12:14:17



68. [32569](http://github.com/cms-sw/cmssw/pull/32569){:target="_blank"}  from **@chrispap95**: Add Fireworks proxies for Tracksters and fix a bug in FWCaloClusterProxyBuilder.cc `visualization`  created: 2020-12-21 17:39:34 merged: 2020-12-22 00:21:59



69. [32568](http://github.com/cms-sw/cmssw/pull/32568){:target="_blank"}  from **@bsunanda**: Run3-hcx277 Make the other shower library producer to work for HF `geometry`  `simulation`  created: 2020-12-21 16:37:58 merged: 2020-12-23 09:08:11



70. [32566](http://github.com/cms-sw/cmssw/pull/32566){:target="_blank"}  from **@Dr15Jones**: Fix bug where ED module tasks started in the es task_arena. `core`  created: 2020-12-19 17:46:54 merged: 2020-12-19 21:40:21



71. [32561](http://github.com/cms-sw/cmssw/pull/32561){:target="_blank"}  from **@bsunanda**: Run4-hgx272x Compress the property information of Wafers and tiles to reduce space requirement `geometry`  `upgrade`  created: 2020-12-18 23:01:04 merged: 2020-12-25 00:08:05



72. [32560](http://github.com/cms-sw/cmssw/pull/32560){:target="_blank"}  from **@cvuosalo**: [DD4hep] Keep mag. field geom. builder shape lengths same with DD4hep units change `reconstruction`  created: 2020-12-18 22:43:03 merged: 2020-12-29 07:40:30



73. [32559](http://github.com/cms-sw/cmssw/pull/32559){:target="_blank"}  from **@Dr15Jones**: Added missing package dependency needed for UBSAN in DQM/DataScouting `dqm`  created: 2020-12-18 21:55:44 merged: 2020-12-21 17:42:31



74. [32558](http://github.com/cms-sw/cmssw/pull/32558){:target="_blank"}  from **@Dr15Jones**: Switch from sprintf to std::to_string in DQM/L1TMonitor `dqm`  created: 2020-12-18 21:44:55 merged: 2020-12-29 00:03:55



75. [32556](http://github.com/cms-sw/cmssw/pull/32556){:target="_blank"}  from **@Dr15Jones**: Added missing package dependency needed for UBSAN in FastSimulation/ForwardDetectors `fastsim`  created: 2020-12-18 21:12:20 merged: 2020-12-30 12:13:51



76. [32555](http://github.com/cms-sw/cmssw/pull/32555){:target="_blank"}  from **@Dr15Jones**: Added missing package dependency needed for UBSAN in GeneratorInterface/ExhumeInterface `generators`  created: 2020-12-18 21:00:13 merged: 2020-12-29 00:04:04



77. [32554](http://github.com/cms-sw/cmssw/pull/32554){:target="_blank"}  from **@Dr15Jones**: Added missing package dependency needed for UBSAN in GeneratorInterface/TauolaInterface `generators`  created: 2020-12-18 20:45:58 merged: 2020-12-30 03:16:29



78. [32553](http://github.com/cms-sw/cmssw/pull/32553){:target="_blank"}  from **@Dr15Jones**: Added missing package dependency needed for UBSAN in IOMC/EventVertexGenerators `simulation`  created: 2020-12-18 20:42:44 merged: 2020-12-20 01:46:07



79. [32552](http://github.com/cms-sw/cmssw/pull/32552){:target="_blank"}  from **@Dr15Jones**: Added missing package dependency needed for UBSAN in JetMETCorrections/Type1MET `analysis`  `reconstruction`  created: 2020-12-18 20:00:29 merged: 2020-12-21 09:03:34



80. [32551](http://github.com/cms-sw/cmssw/pull/32551){:target="_blank"}  from **@vargasa**: [DD4hep] Tracker Use DD4hep Units Follow-up `simulation`  created: 2020-12-18 19:17:04 merged: 2020-12-21 00:06:44



81. [32549](http://github.com/cms-sw/cmssw/pull/32549){:target="_blank"}  from **@tomalin**: Clean-up of L1 Tracker cluster, stub & track truth-reco association code `l1`  `simulation`  `upgrade`  created: 2020-12-18 18:39:56 merged: 2021-01-12 14:40:59



82. [32548](http://github.com/cms-sw/cmssw/pull/32548){:target="_blank"}  from **@silviodonato**: Move DeepCore workflow to TTbar (existing GEN-SIM files) `pdmv`  `upgrade`  created: 2020-12-18 17:03:31 merged: 2020-12-19 08:58:58



83. [32547](http://github.com/cms-sw/cmssw/pull/32547){:target="_blank"}  from **@silviodonato**: Move GPU workflows to a specific GPU matrix `pdmv`  `upgrade`  created: 2020-12-18 15:54:01 merged: 2020-12-24 08:32:43



84. [32544](http://github.com/cms-sw/cmssw/pull/32544){:target="_blank"}  from **@ghugo83**: Improve DD4hep workflow perf, step 4: Improve performance of GeometricDet construction in old DD (DDD) and DD4hep `geometry`  created: 2020-12-18 14:35:51 merged: 2020-12-22 00:22:30



85. [32541](http://github.com/cms-sw/cmssw/pull/32541){:target="_blank"}  from **@slava77**: switch modifiers to pp_on_AA for hiEvtPlane `reconstruction`  created: 2020-12-18 12:56:18 merged: 2020-12-19 02:09:23



86. [32540](http://github.com/cms-sw/cmssw/pull/32540){:target="_blank"}  from **@ghugo83**: Improve DD4hep workflow perf, step 3: Also reduced the number of paths (with regex) looped over for HCAL `geometry`  `simulation`  `upgrade`  created: 2020-12-18 11:16:34 merged: 2021-01-12 02:28:08



87. [32539](http://github.com/cms-sw/cmssw/pull/32539){:target="_blank"}  from **@fabiocos**: MTD geometry: remove obsolete unused xml configuration files `geometry`  `upgrade`  created: 2020-12-18 10:02:48 merged: 2020-12-19 02:10:58



88. [32538](http://github.com/cms-sw/cmssw/pull/32538){:target="_blank"}  from **@ghugo83**: Make units dd4hep-dependent in PPS `geometry`  created: 2020-12-18 10:01:28 merged: 2021-01-06 00:05:27



89. [32537](http://github.com/cms-sw/cmssw/pull/32537){:target="_blank"}  from **@cms-tsg-storm**: HLT menu migration to CMSSW_11_3_0_pre1 `hlt`  created: 2020-12-18 09:41:34 merged: 2020-12-18 13:44:38



90. [32535](http://github.com/cms-sw/cmssw/pull/32535){:target="_blank"}  from **@bsunanda**: Run3-gex44 Correct use of unit coversion for CaloGeometryLoader `geometry`  created: 2020-12-17 22:40:10 merged: 2020-12-18 18:07:07



91. [32534](http://github.com/cms-sw/cmssw/pull/32534){:target="_blank"}  from **@bsunanda**: Run3-sim79 Enable the showerlibrary producer to work in the new CMSSW version `geometry`  `simulation`  `upgrade`  created: 2020-12-17 21:59:46 merged: 2020-12-20 01:46:22



92. [32530](http://github.com/cms-sw/cmssw/pull/32530){:target="_blank"}  from **@mmusich**: SiStrip Payload Inspector: alternative style Tracker Maps and code clean-up `db`  created: 2020-12-17 18:30:33 merged: 2020-12-23 00:06:09



93. [32528](http://github.com/cms-sw/cmssw/pull/32528){:target="_blank"}  from **@Dr15Jones**: Modernize TriggerNames `core`  created: 2020-12-17 17:17:06 merged: 2020-12-19 02:10:19



94. [32526](http://github.com/cms-sw/cmssw/pull/32526){:target="_blank"}  from **@slomeo**: Added "/dd4hep::cm" to the CSCGeometryParsFromDD Class `geometry`  created: 2020-12-17 17:12:53 merged: 2020-12-25 00:07:14



95. [32524](http://github.com/cms-sw/cmssw/pull/32524){:target="_blank"}  from **@felicepantaleo**: [HGCal] [bugfix] fix NaN values in LeafCandidate rapidity `reconstruction`  `upgrade`  created: 2020-12-17 16:58:12 merged: 2020-12-25 00:07:50



96. [32522](http://github.com/cms-sw/cmssw/pull/32522){:target="_blank"}  from **@bsunanda**: Run3-gem58 Remove reference to CLHEP `geometry`  `upgrade`  created: 2020-12-17 15:23:04 merged: 2020-12-19 02:08:42



97. [32521](http://github.com/cms-sw/cmssw/pull/32521){:target="_blank"}  from **@perrotta**: Range based loop in PPSFilteredProtonProducer `reconstruction`  created: 2020-12-17 13:49:59 merged: 2020-12-18 00:28:21



98. [32519](http://github.com/cms-sw/cmssw/pull/32519){:target="_blank"}  from **@SohamBhattacharya**: HGCal ID variables `hlt`  `reconstruction`  created: 2020-12-17 11:00:53 merged: 2021-01-08 14:49:24



99. [32514](http://github.com/cms-sw/cmssw/pull/32514){:target="_blank"}  from **@fwyzard**: Update HLT subtables after the migration to EOS `hlt`  created: 2020-12-17 10:13:14 merged: 2020-12-17 17:33:52



100. [32513](http://github.com/cms-sw/cmssw/pull/32513){:target="_blank"}  from **@christopheralanwest**: Use correct L1TMuonEndCapParams tag for 2017, 2018, Run 3 and Phase 2 MC `alca`  created: 2020-12-17 03:32:37 merged: 2020-12-17 18:35:50



101. [32511](http://github.com/cms-sw/cmssw/pull/32511){:target="_blank"}  from **@ghugo83**: Improve DD4hep workflow perf, step 2: Remove regex from Phase 1 trackerRecoMaterial.xml `geometry`  `simulation`  `upgrade`  created: 2020-12-16 18:05:54 merged: 2020-12-21 09:03:44



102. [32510](http://github.com/cms-sw/cmssw/pull/32510){:target="_blank"}  from **@Dr15Jones**: Use WaitingTaskHolder for function arguments `core`  created: 2020-12-16 17:25:25 merged: 2020-12-18 18:10:26



103. [32509](http://github.com/cms-sw/cmssw/pull/32509){:target="_blank"}  from **@cvuosalo**: [DD4hep] Ensure DDCMS test results stay same with DD4hep units change `geometry`  created: 2020-12-16 15:45:56 merged: 2020-12-17 09:22:35



104. [32508](http://github.com/cms-sw/cmssw/pull/32508){:target="_blank"}  from **@ebrondol**: Introduce extend flag in HGCal validation `dqm`  created: 2020-12-16 15:43:12 merged: 2020-12-17 11:56:35



105. [32506](http://github.com/cms-sw/cmssw/pull/32506){:target="_blank"}  from **@cms-l1t-offline**: Check bounds. `l1`  `upgrade`  created: 2020-12-16 12:56:44 merged: 2020-12-17 00:38:04



106. [32505](http://github.com/cms-sw/cmssw/pull/32505){:target="_blank"}  from **@ghugo83**: Improve DD4hep workflow perf, step 1: All paths from SpecPar blocks with same name are stacked together `simulation`  created: 2020-12-16 12:40:11 merged: 2020-12-17 13:00:47



107. [32504](http://github.com/cms-sw/cmssw/pull/32504){:target="_blank"}  from **@fabiocos**: MTD geometry: make dd4hep test independent on dd4hep length unit change `geometry`  `upgrade`  created: 2020-12-16 11:39:48 merged: 2020-12-19 02:09:08



108. [32503](http://github.com/cms-sw/cmssw/pull/32503){:target="_blank"}  from **@ggovi**: Bug fix for coral MessageService wrapper `alca`  `db`  created: 2020-12-16 09:13:08 merged: 2020-12-17 15:36:56



109. [32500](http://github.com/cms-sw/cmssw/pull/32500){:target="_blank"}  from **@bsunanda**: Run3-gem57 Make sure that change of units in dd4hep will not affect GEM/ME0 geometry `geometry`  `upgrade`  created: 2020-12-15 21:59:51 merged: 2020-12-17 00:36:56



110. [32499](http://github.com/cms-sw/cmssw/pull/32499){:target="_blank"}  from **@fwyzard**: Add and use preprocessors macros for loop unrolling `core`  `heterogeneous`  `reconstruction`  created: 2020-12-15 21:09:54 merged: 2020-12-16 16:39:34



111. [32498](http://github.com/cms-sw/cmssw/pull/32498){:target="_blank"}  from **@guitargeek**: EcalClusterEnergyUncertaintyElectronSpecific to free function `reconstruction`  created: 2020-12-15 19:36:57 merged: 2020-12-23 14:34:46



112. [32494](http://github.com/cms-sw/cmssw/pull/32494){:target="_blank"}  from **@Dr15Jones**: Better destructor behavior for SiPixelTemplateStore `db`  `fastsim`  `reconstruction`  created: 2020-12-15 16:42:28 merged: 2021-01-11 15:06:39



113. [32490](http://github.com/cms-sw/cmssw/pull/32490){:target="_blank"}  from **@seulgi324**: Build GE0 in the Muon Reco Geometry `reconstruction`  created: 2020-12-15 05:54:58 merged: 2020-12-25 00:09:00



114. [32489](http://github.com/cms-sw/cmssw/pull/32489){:target="_blank"}  from **@cvuosalo**: [DD4hep] Convert production cuts units using DD4hep-invariant method `simulation`  created: 2020-12-15 00:30:52 merged: 2020-12-16 09:02:19



115. [32488](http://github.com/cms-sw/cmssw/pull/32488){:target="_blank"}  from **@vargasa**: MTD & Tracker DD4hep Units `geometry`  `upgrade`  created: 2020-12-14 22:07:16 merged: 2020-12-17 00:36:23



116. [32485](http://github.com/cms-sw/cmssw/pull/32485){:target="_blank"}  from **@slomeo**: Added "/dd4hep::cm" to the DTGeometryBuilder Class  `geometry`  created: 2020-12-14 19:25:34 merged: 2020-12-16 00:25:50



117. [32479](http://github.com/cms-sw/cmssw/pull/32479){:target="_blank"}  from **@ghugo83**: Add evaluation of SpecPar numeric values in Phase II Tracker XMLs `geometry`  created: 2020-12-14 16:23:23 merged: 2020-12-16 09:06:05



118. [32476](http://github.com/cms-sw/cmssw/pull/32476){:target="_blank"}  from **@gsorrentino18**: ETL Validation code update and fixes `dqm`  `reconstruction`  `simulation`  `upgrade`  created: 2020-12-14 15:17:01 merged: 2020-12-17 00:35:44



119. [32472](http://github.com/cms-sw/cmssw/pull/32472){:target="_blank"}  from **@martatornago**: ETL v5 (D73)  x,y axes swapped and hardcoded offset removed `geometry`  `upgrade`  created: 2020-12-14 13:56:07 merged: 2020-12-17 17:04:39



120. [32469](http://github.com/cms-sw/cmssw/pull/32469){:target="_blank"}  from **@Sam-Harper**: EgHLT Phase-II showershape fix : 11_3_X `hlt`  created: 2020-12-14 13:07:50 merged: 2020-12-16 14:28:05



121. [32464](http://github.com/cms-sw/cmssw/pull/32464){:target="_blank"}  from **@jeongeun**: drop type spec in CommonTools `analysis`  `reconstruction`  created: 2020-12-14 05:42:58 merged: 2020-12-16 14:58:26



122. [32463](http://github.com/cms-sw/cmssw/pull/32463){:target="_blank"}  from **@mariadalfonso**: Update nano modifiers  `analysis`  `operations`  `pdmv`  `upgrade`  `xpog`  created: 2020-12-13 21:42:47 merged: 2020-12-23 00:40:34



123. [32462](http://github.com/cms-sw/cmssw/pull/32462){:target="_blank"}  from **@guitargeek**: Correctly add HIPhotonIsolation to pat::photon `reconstruction`  created: 2020-12-13 18:01:10 merged: 2020-12-19 02:08:28



124. [32459](http://github.com/cms-sw/cmssw/pull/32459){:target="_blank"}  from **@bsunanda**: Run4-hgx271 Remove some of the older unwanted xml files `geometry`  `upgrade`  created: 2020-12-12 20:29:23 merged: 2020-12-17 00:31:08



125. [32457](http://github.com/cms-sw/cmssw/pull/32457){:target="_blank"}  from **@bsunanda**: Phase2-hgx271 Make all plugins to take care of units `geometry`  `upgrade`  created: 2020-12-12 18:40:13 merged: 2020-12-17 00:32:17



126. [32452](http://github.com/cms-sw/cmssw/pull/32452){:target="_blank"}  from **@alberto-sanchez**: Update to evtgen 2.0 `generators`  created: 2020-12-11 19:16:28 merged: 2021-01-07 01:58:25



127. [32443](http://github.com/cms-sw/cmssw/pull/32443){:target="_blank"}  from **@alejands**: [DQM/EcalMonitorTasks] Add MEM FE Status and Integrity Error Plots `dqm`  created: 2020-12-10 19:32:43 merged: 2020-12-16 09:06:45



128. [32440](http://github.com/cms-sw/cmssw/pull/32440){:target="_blank"}  from **@mrodozov**: Change Minuit logger for CMS MessageLogger `reconstruction`  created: 2020-12-10 17:25:41 merged: 2020-12-18 00:29:43



129. [32438](http://github.com/cms-sw/cmssw/pull/32438){:target="_blank"}  from **@guitargeek**: Merge .h with .cc files in RecoEgamma/Examples `reconstruction`  created: 2020-12-10 13:25:19 merged: 2020-12-16 16:20:42



130. [32408](http://github.com/cms-sw/cmssw/pull/32408){:target="_blank"}  from **@MilanoBicocca-pix**: BeamSpotOnline updates `dqm`  created: 2020-12-07 21:11:51 merged: 2020-12-16 09:35:00



131. [32397](http://github.com/cms-sw/cmssw/pull/32397){:target="_blank"}  from **@rovere**: Clean HGCAL digitization. Fix Premixing for HGCAL `simulation`  `upgrade`  created: 2020-12-07 10:33:19 merged: 2020-12-16 16:03:46



132. [32392](http://github.com/cms-sw/cmssw/pull/32392){:target="_blank"}  from **@guitargeek**: New CondFormats/GBRForest package `alca`  `analysis`  `db`  `reconstruction`  created: 2020-12-04 20:47:33 merged: 2021-01-14 15:01:27



133. [32391](http://github.com/cms-sw/cmssw/pull/32391){:target="_blank"}  from **@bainbrid**: LowPtElectrons: final energy regression and ID `reconstruction`  created: 2020-12-04 19:10:34 merged: 2021-01-11 20:49:16



134. [32386](http://github.com/cms-sw/cmssw/pull/32386){:target="_blank"}  from **@jeongeun**: Drop type specs in RecoHI {Configuration, HiTracking} `reconstruction`  created: 2020-12-04 09:54:46 merged: 2020-12-16 16:32:37



135. [32222](http://github.com/cms-sw/cmssw/pull/32222){:target="_blank"}  from **@vberta**: DeepCore (NN jetCore seeding) implementation  `dqm`  `operations`  `pdmv`  `reconstruction`  `simulation`  `upgrade`  created: 2020-11-21 01:59:36 merged: 2020-12-17 15:16:36



136. [32048](http://github.com/cms-sw/cmssw/pull/32048){:target="_blank"}  from **@jpata**: MLPF: first integration of EDProducer and training code `dqm`  `operations`  `pdmv`  `reconstruction`  `upgrade`  created: 2020-11-06 14:57:03 merged: 2021-01-04 15:30:36



137. [31721](http://github.com/cms-sw/cmssw/pull/31721){:target="_blank"}  from **@cms-patatrack**: Patatrack integration - Pixel local reconstruction (9/N) `alca`  `db`  `dqm`  `geometry`  `heterogeneous`  `operations`  `reconstruction`  `simulation`  created: 2020-10-08 21:55:35 merged: 2021-01-11 13:16:57



138. [31719](http://github.com/cms-sw/cmssw/pull/31719){:target="_blank"}  from **@cms-patatrack**: Patatrack integration - ECAL local reconstruction (7/N) `heterogeneous`  `operations`  `reconstruction`  created: 2020-10-08 21:46:38 merged: 2021-01-18 19:48:48



139. [31531](http://github.com/cms-sw/cmssw/pull/31531){:target="_blank"}  from **@jwill24**: PPS nanoAOD `analysis`  `reconstruction`  `xpog`  created: 2020-09-22 00:48:37 merged: 2020-12-16 15:09:40



#### CMSDIST Changes between Tags REL/CMSSW_11_3_0_pre1/slc7_amd64_gcc900 and REL/CMSSW_11_3_0_pre2/slc7_amd64_gcc900:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_11_3_0_pre1/slc7_amd64_gcc900...REL/CMSSW_11_3_0_pre2/slc7_amd64_gcc900)



1. [6567](http://github.com/cms-sw/cmsdist/pull/6567){:target="_blank"}  from **@cms-sw**: heppdt: avoid using tbb_hasher created: 2021-01-19 19:26:17 merged: 2021-01-19 19:27:09

2. [6564](http://github.com/cms-sw/cmsdist/pull/6564){:target="_blank"}  from **@cms-sw**: Remove dqmgui, it breaks cc8 builds created: 2021-01-19 07:59:35 merged: 2021-01-19 07:59:47

3. [6562](http://github.com/cms-sw/cmsdist/pull/6562){:target="_blank"}  from **@cms-sw**: Retrained particle ID model and energy regression for HLT TDR created: 2021-01-19 07:02:31 merged: 2021-01-19 09:49:31

4. [6561](http://github.com/cms-sw/cmsdist/pull/6561){:target="_blank"}  from **@davidlange6**: update cmssw-wm-tools to remove the need for pythonpath created: 2021-01-18 18:13:03 merged: 2021-01-18 20:25:39

5. [6559](http://github.com/cms-sw/cmsdist/pull/6559){:target="_blank"}  from **@cms-sw**: use buildLogAnalyzer.py as RPM source created: 2021-01-18 10:34:17 merged: 2021-01-18 10:34:23

6. [6553](http://github.com/cms-sw/cmsdist/pull/6553){:target="_blank"}  from **@slava77**: update of mkFit for new TBB : new tag V2.1.0-0+pr291 created: 2021-01-14 19:58:30 merged: 2021-01-15 12:59:40

7. [6552](http://github.com/cms-sw/cmsdist/pull/6552){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2021-01-14 17:43:16 merged: 2021-01-15 07:21:12

8. [6548](http://github.com/cms-sw/cmsdist/pull/6548){:target="_blank"}  from **@cms-sw**: HepPDT version 3.04.01 created: 2021-01-13 10:46:59 merged: 2021-01-18 08:36:28

9. [6547](http://github.com/cms-sw/cmsdist/pull/6547){:target="_blank"}  from **@kpedro88**: remove ldscript from triton build to keep typeinfo created: 2021-01-12 21:41:57 merged: 2021-01-13 06:39:15

10. [6546](http://github.com/cms-sw/cmsdist/pull/6546){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-09-00 created: 2021-01-12 21:19:57 merged: 2021-01-12 21:25:38

11. [6543](http://github.com/cms-sw/cmsdist/pull/6543){:target="_blank"}  from **@cms-sw**: Update to cms-data/RecoEgamma-ElectronIdentification/pull/16 created: 2021-01-11 21:09:29 merged: 2021-01-11 21:10:34

12. [6542](http://github.com/cms-sw/cmsdist/pull/6542){:target="_blank"}  from **@davidlange6**: bug fix update to cmssw-wm-tools created: 2021-01-11 16:08:44 merged: 2021-01-12 07:50:35

13. [6538](http://github.com/cms-sw/cmsdist/pull/6538){:target="_blank"}  from **@cms-sw**: [BuildRules] Updated runtime hook to drop data externals from release created: 2021-01-11 08:24:10 merged: 2021-01-11 20:49:08

14. [6537](http://github.com/cms-sw/cmsdist/pull/6537){:target="_blank"}  from **@cms-sw**: [cms-common] Fix for SITECONFIG_PATH created: 2021-01-10 09:53:06 merged: 2021-01-10 18:41:14

15. [6534](http://github.com/cms-sw/cmsdist/pull/6534){:target="_blank"}  from **@cms-sw**: Update tag for RecoParticleFlow-PFProducer to V16-01-00 created: 2021-01-07 00:07:53 merged: 2021-01-07 08:56:20

16. [6533](http://github.com/cms-sw/cmsdist/pull/6533){:target="_blank"}  from **@cms-sw**: added new root tools for histpainter and imt created: 2021-01-06 15:03:33 merged: 2021-01-06 18:10:27

17. [6532](http://github.com/cms-sw/cmsdist/pull/6532){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-TrackTrigger to V00-01-00 created: 2021-01-06 11:07:24 merged: 2021-01-08 15:18:52

18. [6526](http://github.com/cms-sw/cmsdist/pull/6526){:target="_blank"}  from **@cms-sw**: [cms-common] default setting for the new SITECONFIG_PATH created: 2021-01-04 08:20:57 merged: 2021-01-04 11:42:20

19. [6524](http://github.com/cms-sw/cmsdist/pull/6524){:target="_blank"}  from **@fwyzard**: Update TBB to version 2020_U3 (v2020.3) created: 2020-12-30 11:24:39 merged: 2021-01-07 08:34:06

20. [6523](http://github.com/cms-sw/cmsdist/pull/6523){:target="_blank"}  from **@fwyzard**: Update OpenMPI to 4.1.0, and add extra support libraries created: 2020-12-23 22:44:45 merged: 2021-01-11 06:31:36

21. [6522](http://github.com/cms-sw/cmsdist/pull/6522){:target="_blank"}  from **@fwyzard**: Update to CUDA 11.2 created: 2020-12-23 09:20:39 merged: 2021-01-06 19:14:12

22. [6519](http://github.com/cms-sw/cmsdist/pull/6519){:target="_blank"}  from **@cms-sw**: Update tag for RecoJets-JetProducers to V05-13-00 created: 2020-12-21 11:08:22 merged: 2020-12-21 11:13:46

23. [6515](http://github.com/cms-sw/cmsdist/pull/6515){:target="_blank"}  from **@cms-sw**: Update tag for RecoTracker-TkSeedGenerator to V00-01-00 created: 2020-12-17 17:49:23 merged: 2020-12-17 18:30:30

24. [6511](http://github.com/cms-sw/cmsdist/pull/6511){:target="_blank"}  from **@davidlange6**: update cmssw-wm-tools with new tool for nEvents tweaking created: 2020-12-15 17:14:29 merged: 2021-01-11 07:32:57

25. [6494](http://github.com/cms-sw/cmsdist/pull/6494){:target="_blank"}  from **@alberto-sanchez**: update to evtgen 2.0.0 and requirements to  hepmc 2.06.10, photospp 3 created: 2020-12-11 05:38:25 merged: 2021-01-07 01:58:10

26. [6443](http://github.com/cms-sw/cmsdist/pull/6443){:target="_blank"}  from **@davidlange6**: Add several hep python tools (mostly histograming helpers) created: 2020-11-24 09:02:19 merged: 2020-12-17 15:47:28

27. [6371](http://github.com/cms-sw/cmsdist/pull/6371){:target="_blank"}  from **@cms-sw**: Added new dqmgui spec created: 2020-11-04 13:46:49 merged: 2021-01-18 20:30:42
