---
layout: post
rel_link:  "12_0_0_pre1"
title:  "CMSSW_12_0_0_pre1"
date:   2021-05-06 06:59:33
categories: cmssw
relmajor: 12
relminor: 0
relsubminor: 0
relpre: _pre1
---

# CMSSW_12_0_0_pre1
#### Changes since CMSSW_11_3_0_pre6:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_11_3_0_pre6...CMSSW_12_0_0_pre1)



1. [33634](http://github.com/cms-sw/cmssw/pull/33634){:target="_blank"}  from **@missirol**: avoiding trailing whitespaces in config dump `core`  created: 2021-05-05 13:18:51 merged: 2021-05-06 00:10:12



2. [33631](http://github.com/cms-sw/cmssw/pull/33631){:target="_blank"}  from **@mrodozov**: Initialize id variable to silence warning `daq`  `reconstruction`  created: 2021-05-05 08:44:02 merged: 2021-05-05 12:03:03



3. [33628](http://github.com/cms-sw/cmssw/pull/33628){:target="_blank"}  from **@qliphy**: Set generateConcurrently to False to fix Herwig workflow issue `generators`  created: 2021-05-05 05:58:29 merged: 2021-05-05 09:12:54



4. [33627](http://github.com/cms-sw/cmssw/pull/33627){:target="_blank"}  from **@bsunanda**: Phase2-hgx285X Clean up a few classes for the use of ESGetToken and add a script for plots `dqm`  created: 2021-05-04 20:51:33 merged: 2021-05-05 10:24:56



5. [33625](http://github.com/cms-sw/cmssw/pull/33625){:target="_blank"}  from **@mmusich**: fix missing leftover Timing parameter in fed_dqm_sourceclient-live_cfg.py `dqm`  created: 2021-05-04 18:44:46 merged: 2021-05-05 07:06:25



6. [33624](http://github.com/cms-sw/cmssw/pull/33624){:target="_blank"}  from **@justinasr**: Allow to suppress ExternalLHEProducer exception if not all events were processed `generators`  created: 2021-05-04 18:14:20 merged: 2021-05-05 12:54:06



7. [33618](http://github.com/cms-sw/cmssw/pull/33618){:target="_blank"}  from **@perrotta**: Fix typo in the fillDescriptions method of RecoParticleFlow/PFClusterProducer/interface/HGCRecHitNavigator.h `reconstruction`  created: 2021-05-04 07:14:02 merged: 2021-05-05 00:33:04



8. [33614](http://github.com/cms-sw/cmssw/pull/33614){:target="_blank"}  from **@bsunanda**: Run4-hgx285 Update some of the remaining validation classes in Validation/HGCalValidation `dqm`  `simulation`  created: 2021-05-03 19:53:15 merged: 2021-05-04 10:39:35



9. [33611](http://github.com/cms-sw/cmssw/pull/33611){:target="_blank"}  from **@bsunanda**: Phase2-hgx285 Get rid of HCAL option from most of the code in Validation/HGCalValidation/plugins `dqm`  created: 2021-05-03 15:06:23 merged: 2021-05-03 23:55:11



10. [33601](http://github.com/cms-sw/cmssw/pull/33601){:target="_blank"}  from **@bsunanda**: Phase2-hgx282Z Remove the HCAL option in the validation codes in HGCalValidation/test `dqm`  created: 2021-05-02 23:48:52 merged: 2021-05-04 05:52:32



11. [33597](http://github.com/cms-sw/cmssw/pull/33597){:target="_blank"}  from **@davidlange6**: Validation/Geometry apply futurize stage1; use six.iteritems; use python3 for matplotlib `dqm`  `geometry`  created: 2021-05-01 14:56:35 merged: 2021-05-04 05:52:57



12. [33595](http://github.com/cms-sw/cmssw/pull/33595){:target="_blank"}  from **@bsunanda**: Run4-hgx282Z Remove overlaps in the V15 geometry of HGCal `geometry`  `upgrade`  created: 2021-05-01 01:47:00 merged: 2021-05-04 14:30:12



13. [33593](http://github.com/cms-sw/cmssw/pull/33593){:target="_blank"}  from **@namapane**: fix handling of air/iron in DD4hep MF construction `reconstruction`  created: 2021-04-30 15:24:56 merged: 2021-05-01 01:25:18



14. [33586](http://github.com/cms-sw/cmssw/pull/33586){:target="_blank"}  from **@cms-tau-pog**: Use genTauJet modules coherently across different nanoAOD cffs `xpog`  created: 2021-04-30 10:23:48 merged: 2021-05-01 11:29:15



15. [33584](http://github.com/cms-sw/cmssw/pull/33584){:target="_blank"}  from **@perrotta**: Remove dead assignments in ZtoMMEventSelector `dqm`  created: 2021-04-30 09:30:15 merged: 2021-04-30 12:43:23



16. [33582](http://github.com/cms-sw/cmssw/pull/33582){:target="_blank"}  from **@dildick**: Cleanup of data/simulation analyzer modules in CSCTriggerPrimitives `l1`  created: 2021-04-30 04:33:47 merged: 2021-05-05 11:59:13



17. [33581](http://github.com/cms-sw/cmssw/pull/33581){:target="_blank"}  from **@ats2008**: All daughter decay filter `generators`  created: 2021-04-30 03:08:17 merged: 2021-04-30 12:44:17



18. [33579](http://github.com/cms-sw/cmssw/pull/33579){:target="_blank"}  from **@jfernan2**: Update for cmsswSequenceInfo without extra sequences `dqm`  created: 2021-04-29 20:26:42 merged: 2021-05-01 01:21:02



19. [33576](http://github.com/cms-sw/cmssw/pull/33576){:target="_blank"}  from **@bsunanda**: Run3-gex72 Correct cfg's to test phase2 geometries `simulation`  created: 2021-04-29 13:22:23 merged: 2021-05-01 01:21:48



20. [33575](http://github.com/cms-sw/cmssw/pull/33575){:target="_blank"}  from **@archiron**: Validation/RecoEgamma remove recomp histos from miniAOD Validation `dqm`  created: 2021-04-29 12:18:12 merged: 2021-04-29 19:53:32



21. [33573](http://github.com/cms-sw/cmssw/pull/33573){:target="_blank"}  from **@b-fontana**: EcalCondObject container iteration fix `alca`  `db`  `l1`  `reconstruction`  created: 2021-04-29 09:01:50 merged: 2021-05-05 11:58:51



22. [33570](http://github.com/cms-sw/cmssw/pull/33570){:target="_blank"}  from **@dildick**: Prep work for the Run-3 GEM-CSC integrated local trigger `l1`  created: 2021-04-28 19:56:44 merged: 2021-04-30 12:47:12



23. [33569](http://github.com/cms-sw/cmssw/pull/33569){:target="_blank"}  from **@dildick**: EMTF and uGMT shower triggers (HadronicShowerTrigger-5) `l1`  `simulation`  created: 2021-04-28 19:54:05 merged: 2021-05-04 00:00:30



24. [33568](http://github.com/cms-sw/cmssw/pull/33568){:target="_blank"}  from **@cvuosalo**: [DD4he] Disable DD4hep workflow 11634.911 in PR tests while it produces unstable results `pdmv`  `upgrade`  created: 2021-04-28 18:57:28 merged: 2021-04-29 07:16:32



25. [33566](http://github.com/cms-sw/cmssw/pull/33566){:target="_blank"}  from **@gartung**: FWCore/Framework: Add cmsRunGP which links against Google perftools profiler library. `core`  created: 2021-04-28 13:07:46 merged: 2021-05-03 23:59:06



26. [33561](http://github.com/cms-sw/cmssw/pull/33561){:target="_blank"}  from **@fwyzard**: Autodetect if a GPU can be used with CMSSW `heterogeneous`  created: 2021-04-28 08:53:09 merged: 2021-04-29 00:00:15



27. [33560](http://github.com/cms-sw/cmssw/pull/33560){:target="_blank"}  from **@davidlange6**: remove Python2 unit tests ; migrate scripts using uproot to use python3 `analysis`  `dqm`  created: 2021-04-28 07:40:11 merged: 2021-04-30 08:19:13



28. [33559](http://github.com/cms-sw/cmssw/pull/33559){:target="_blank"}  from **@stahlleiton**: Provide access to HLTPathStatus in TriggerResultsFilter `hlt`  created: 2021-04-28 07:00:22 merged: 2021-05-01 01:13:45



29. [33557](http://github.com/cms-sw/cmssw/pull/33557){:target="_blank"}  from **@sroychow**: TkDQM phase2: Remove validation header from DQM package `dqm`  created: 2021-04-28 06:06:10 merged: 2021-04-28 12:59:48



30. [33556](http://github.com/cms-sw/cmssw/pull/33556){:target="_blank"}  from **@smuzaffar**: Update dict definiton package mapping for AssociationMap/TrackingParticle `core`  created: 2021-04-28 02:27:54 merged: 2021-04-28 23:59:29



31. [33550](http://github.com/cms-sw/cmssw/pull/33550){:target="_blank"}  from **@dan131riley**: Throw on missing file in ChainEvent, revive unit tests that would have caught this `core`  created: 2021-04-27 19:37:08 merged: 2021-04-29 19:47:05



32. [33549](http://github.com/cms-sw/cmssw/pull/33549){:target="_blank"}  from **@Dr15Jones**: Use only 1 thread when testing EventProcessor `core`  created: 2021-04-27 18:38:08 merged: 2021-04-28 01:37:59



33. [33543](http://github.com/cms-sw/cmssw/pull/33543){:target="_blank"}  from **@jeongeun**: Migrate module configurations in RecoLocalMuon to use automatically generated cfi default configurations `hlt`  `reconstruction`  created: 2021-04-27 14:58:16 merged: 2021-04-30 09:44:32



34. [33541](http://github.com/cms-sw/cmssw/pull/33541){:target="_blank"}  from **@gsorrentino18**: Implementing dedicated LHE filter for removing events with mttbar below a certain threshold `generators`  created: 2021-04-27 14:29:47 merged: 2021-04-30 15:51:06



35. [33540](http://github.com/cms-sw/cmssw/pull/33540){:target="_blank"}  from **@bsunanda**: Run4-hgx282X Introduce ESGetToken in all classes in Validation/HGCalValidation/test `dqm`  created: 2021-04-27 13:55:25 merged: 2021-04-28 13:03:42



36. [33539](http://github.com/cms-sw/cmssw/pull/33539){:target="_blank"}  from **@davidlange6**: Add support for zstd root output files `core`  created: 2021-04-27 12:22:39 merged: 2021-04-28 23:59:03



37. [33537](http://github.com/cms-sw/cmssw/pull/33537){:target="_blank"}  from **@bsunanda**: Phase2-hgx282X Change the use of ESHandle to ESGetToken `dqm`  created: 2021-04-26 23:47:05 merged: 2021-05-03 00:31:15



38. [33534](http://github.com/cms-sw/cmssw/pull/33534){:target="_blank"}  from **@makortel**: Remove confusing use of None from _TypedParameterizable constructor `core`  created: 2021-04-26 21:51:46 merged: 2021-05-03 23:52:36



39. [33530](http://github.com/cms-sw/cmssw/pull/33530){:target="_blank"}  from **@bsunanda**: Run4-hgx282 Remove overlap in for EB in 2 recent Phase2 scenarios D82 and D83 `geometry`  `upgrade`  created: 2021-04-26 19:13:49 merged: 2021-04-30 12:47:54



40. [33529](http://github.com/cms-sw/cmssw/pull/33529){:target="_blank"}  from **@bsunanda**: Phase2-hgx282 Prepare a simple example to test extruded polygon implementation in dd4hep `geometry`  `upgrade`  created: 2021-04-26 17:09:19 merged: 2021-04-30 12:45:14



41. [33527](http://github.com/cms-sw/cmssw/pull/33527){:target="_blank"}  from **@cms-tau-pog**: Fixes of anti-mu cff for tauReco at miniAOD `reconstruction`  created: 2021-04-26 15:00:38 merged: 2021-05-01 20:06:35



42. [33526](http://github.com/cms-sw/cmssw/pull/33526){:target="_blank"}  from **@czangela**: Pixel local reco: reduce code duplication between SiPixelDigiErrorsFromSoA and SiPixelRawToDigi `hlt`  `reconstruction`  created: 2021-04-26 12:17:56 merged: 2021-05-03 23:54:41



43. [33523](http://github.com/cms-sw/cmssw/pull/33523){:target="_blank"}  from **@pieterdavid**: Merge ShallowGainCalibration logic in SiStripGainsPCLWorker and a minor bugfix `alca`  created: 2021-04-26 09:33:53 merged: 2021-05-04 13:53:44



44. [33522](http://github.com/cms-sw/cmssw/pull/33522){:target="_blank"}  from **@cms-tau-pog**: Change input collection for genVisTaus `xpog`  created: 2021-04-26 08:04:01 merged: 2021-04-28 01:37:18



45. [33520](http://github.com/cms-sw/cmssw/pull/33520){:target="_blank"}  from **@hatakeyamak**: Adopt HFSignalAsymmetry flag in HF PFRecHit cleaning `operations`  `reconstruction`  created: 2021-04-25 03:06:18 merged: 2021-04-30 08:14:34



46. [33518](http://github.com/cms-sw/cmssw/pull/33518){:target="_blank"}  from **@jainshilpi**: Adding Phase II EB electron and photon IDs  `reconstruction`  created: 2021-04-23 23:27:33 merged: 2021-04-28 13:07:31



47. [33517](http://github.com/cms-sw/cmssw/pull/33517){:target="_blank"}  from **@jainshilpi**: Adding HtoZZ UL ID configs `reconstruction`  created: 2021-04-23 23:24:00 merged: 2021-05-05 09:04:19



48. [33516](http://github.com/cms-sw/cmssw/pull/33516){:target="_blank"}  from **@SiewYan**: implement concurrent ExternalLHEProducer technique `generators`  created: 2021-04-23 16:55:09 merged: 2021-04-27 03:52:40



49. [33515](http://github.com/cms-sw/cmssw/pull/33515){:target="_blank"}  from **@makortel**: Add copyAndAdd() to Task for easier interplay with Modifier `core`  created: 2021-04-23 14:21:17 merged: 2021-04-27 13:35:06



50. [33511](http://github.com/cms-sw/cmssw/pull/33511){:target="_blank"}  from **@Dres90**: Add new uploader script to CMSSW to master `db`  created: 2021-04-23 09:27:14 merged: 2021-04-27 07:09:13



51. [33510](http://github.com/cms-sw/cmssw/pull/33510){:target="_blank"}  from **@hftsoi**: Modify CaloLayer1 DQM for 5BX needed for Ecal `dqm`  `l1`  created: 2021-04-23 08:21:17 merged: 2021-04-24 14:20:46



52. [33508](http://github.com/cms-sw/cmssw/pull/33508){:target="_blank"}  from **@OzAmram**: Update template and gen errors for phase-2 geometries with 3D pixels `alca`  `pdmv`  `upgrade`  created: 2021-04-22 18:23:50 merged: 2021-04-28 13:06:03



53. [33507](http://github.com/cms-sw/cmssw/pull/33507){:target="_blank"}  from **@francescobrivio**: Add ECAL TPG double weight tags and remove GEMELMapRcd from GTs `alca`  `l1`  created: 2021-04-22 17:49:21 merged: 2021-04-23 08:50:54



54. [33506](http://github.com/cms-sw/cmssw/pull/33506){:target="_blank"}  from **@civanch**: Added forgotten const `simulation`  created: 2021-04-22 17:24:49 merged: 2021-04-23 00:34:58



55. [33505](http://github.com/cms-sw/cmssw/pull/33505){:target="_blank"}  from **@ggovi**: Support of private frontier Key for workflow-specific caching `alca`  `db`  created: 2021-04-22 15:23:12 merged: 2021-04-23 08:52:51



56. [33503](http://github.com/cms-sw/cmssw/pull/33503){:target="_blank"}  from **@fabferro**: PPS Pixel charge share bug fix - part 2 `alca`  `simulation`  created: 2021-04-22 13:11:12 merged: 2021-04-23 08:49:23



57. [33499](http://github.com/cms-sw/cmssw/pull/33499){:target="_blank"}  from **@rgoldouz**: Displaced muon with new parameters for the Phase2 L1 tracker studies `generators`  created: 2021-04-22 07:58:33 merged: 2021-05-01 01:15:10



58. [33495](http://github.com/cms-sw/cmssw/pull/33495){:target="_blank"}  from **@OzAmram**: Use Lorentz Angle from data base for pixel template CPE's in case of error  `hlt`  `reconstruction`  created: 2021-04-21 21:43:57 merged: 2021-04-28 08:12:23



59. [33491](http://github.com/cms-sw/cmssw/pull/33491){:target="_blank"}  from **@rmanzoni**: Consider charge conjugation in decay products in PythiaFilterMultiAncestor `generators`  created: 2021-04-21 15:09:54 merged: 2021-04-27 03:53:14



60. [33490](http://github.com/cms-sw/cmssw/pull/33490){:target="_blank"}  from **@CTPPS**: PPS: fix two validation plots `dqm`  created: 2021-04-21 12:32:15 merged: 2021-04-23 00:40:58



61. [33489](http://github.com/cms-sw/cmssw/pull/33489){:target="_blank"}  from **@davidlange6**: add missing dependencies to SimDataFormats/Association `simulation`  created: 2021-04-21 08:22:51 merged: 2021-04-21 15:02:27



62. [33488](http://github.com/cms-sw/cmssw/pull/33488){:target="_blank"}  from **@lecriste**: [HGCAL] Deprecate MultiCluster `dqm`  `reconstruction`  `upgrade`  created: 2021-04-21 08:20:47 merged: 2021-05-05 10:24:51



63. [33484](http://github.com/cms-sw/cmssw/pull/33484){:target="_blank"}  from **@dildick**: Remove CLCT-centric matching option in CSC trigger primitives  `l1`  created: 2021-04-21 02:07:58 merged: 2021-04-22 08:08:33



64. [33482](http://github.com/cms-sw/cmssw/pull/33482){:target="_blank"}  from **@sroychow**: TkDQM: Add standalone monitoring modules for OT Rechits and new resolution plots for ITRechits `dqm`  created: 2021-04-20 23:35:03 merged: 2021-04-24 07:21:01



65. [33481](http://github.com/cms-sw/cmssw/pull/33481){:target="_blank"}  from **@bsunanda**: Phase2-hgx281z Update validation scripts to do validation of V15 geometry of HGCal `dqm`  created: 2021-04-20 19:29:44 merged: 2021-04-21 11:36:53



66. [33477](http://github.com/cms-sw/cmssw/pull/33477){:target="_blank"}  from **@bsunanda**: run3-hcx296 Add a new testing code and rearrange some of the files `dqm`  created: 2021-04-20 12:52:20 merged: 2021-04-21 11:36:59



67. [33474](http://github.com/cms-sw/cmssw/pull/33474){:target="_blank"}  from **@gartung**: Changes required to compile with TBB 2021.2 `core`  `db`  `geometry`  `hlt`  `reconstruction`  created: 2021-04-19 18:59:25 merged: 2021-05-04 16:33:38



68. [33473](http://github.com/cms-sw/cmssw/pull/33473){:target="_blank"}  from **@mrodozov**: Update python tests - py3 only `analysis`  created: 2021-04-19 17:45:25 merged: 2021-04-20 07:45:12



69. [33472](http://github.com/cms-sw/cmssw/pull/33472){:target="_blank"}  from **@mmusich**: Deal with FastSim issue raised from #33430 `dqm`  created: 2021-04-19 17:32:43 merged: 2021-04-20 07:27:35



70. [33471](http://github.com/cms-sw/cmssw/pull/33471){:target="_blank"}  from **@bsunanda**: Run3-gex71 Modified version of EB numbering scheme code which will work with modified EB algorithm `geometry`  created: 2021-04-19 17:18:58 merged: 2021-04-20 00:05:06



71. [33467](http://github.com/cms-sw/cmssw/pull/33467){:target="_blank"}  from **@ebrondol**: Add python config to run only TICL `dqm`  created: 2021-04-19 14:16:49 merged: 2021-04-19 17:20:55



72. [33465](http://github.com/cms-sw/cmssw/pull/33465){:target="_blank"}  from **@perrotta**: Remove dead assignments from L1Trigger/CSCTrackFinder `l1`  created: 2021-04-19 11:17:09 merged: 2021-04-20 07:45:28



73. [33464](http://github.com/cms-sw/cmssw/pull/33464){:target="_blank"}  from **@silviodonato**: Fix unit test in PhysicsTools/UtilAlgos `analysis`  created: 2021-04-19 10:30:27 merged: 2021-04-20 07:13:24



74. [33462](http://github.com/cms-sw/cmssw/pull/33462){:target="_blank"}  from **@VinInn**: Speedup Track Validation `dqm`  `simulation`  created: 2021-04-19 06:55:01 merged: 2021-04-23 00:44:07



75. [33461](http://github.com/cms-sw/cmssw/pull/33461){:target="_blank"}  from **@chayanit**: Add new workflows to upgradeWorkflowComponents.py for HLT `pdmv`  `upgrade`  created: 2021-04-19 06:32:10 merged: 2021-05-04 05:51:54



76. [33458](http://github.com/cms-sw/cmssw/pull/33458){:target="_blank"}  from **@guitargeek**: Move PFClusterWidthAlgo into CommonTools/ParticleFlow `reconstruction`  created: 2021-04-18 09:31:36 merged: 2021-04-22 15:11:25



77. [33457](http://github.com/cms-sw/cmssw/pull/33457){:target="_blank"}  from **@civanch**: Cleanup Geant4 physics sub-libraries for version 10.7 and beyond `simulation`  created: 2021-04-17 17:41:23 merged: 2021-04-18 01:33:25



78. [33454](http://github.com/cms-sw/cmssw/pull/33454){:target="_blank"}  from **@bsunanda**: Phase2-gex70 Add a new scenario D84 same as D70 but with updated tracker T24 `geometry`  `operations`  `pdmv`  `upgrade`  created: 2021-04-17 02:27:40 merged: 2021-04-20 00:07:22



79. [33453](http://github.com/cms-sw/cmssw/pull/33453){:target="_blank"}  from **@fabiocos**: MTD geometry and digitization: move check for pixel active area into RectangularMTDTopology, make it usable for BTL as well `geometry`  `simulation`  `upgrade`  created: 2021-04-16 16:20:58 merged: 2021-04-20 09:55:09



80. [33451](http://github.com/cms-sw/cmssw/pull/33451){:target="_blank"}  from **@bsunanda**: Run3-gex69 Move the macros to a separate directory and adopt for dd4hep `dqm`  `geometry`  created: 2021-04-16 13:52:03 merged: 2021-04-20 00:07:50



81. [33450](http://github.com/cms-sw/cmssw/pull/33450){:target="_blank"}  from **@fwyzard**: Fix indentation in EDAlias python dump `core`  created: 2021-04-16 09:19:45 merged: 2021-04-18 01:35:05



82. [33449](http://github.com/cms-sw/cmssw/pull/33449){:target="_blank"}  from **@fwyzard**: Fix indentation in EDAlias python dump `core`  created: 2021-04-16 09:18:00 merged: 2021-04-18 01:34:43



83. [33446](http://github.com/cms-sw/cmssw/pull/33446){:target="_blank"}  from **@dildick**: Data formats for showers in the muon system in Run-3 (HadronicShowerTrigger-4) `l1`  created: 2021-04-15 19:35:52 merged: 2021-04-28 07:58:19



84. [33445](http://github.com/cms-sw/cmssw/pull/33445){:target="_blank"}  from **@guitargeek**: More BuildFiles cleaning `alca`  `dqm`  `heterogeneous`  `l1`  `reconstruction`  `simulation`  `upgrade`  created: 2021-04-15 18:31:25 merged: 2021-04-17 01:16:34



85. [33444](http://github.com/cms-sw/cmssw/pull/33444){:target="_blank"}  from **@dildick**: Load CLCT pre-trigger digis in CSC packer. Skeleton code to pack/unpack CSCShowerDigi (HadronicShowerTrigger-3) `l1`  `reconstruction`  created: 2021-04-15 17:46:54 merged: 2021-04-28 07:41:20



86. [33443](http://github.com/cms-sw/cmssw/pull/33443){:target="_blank"}  from **@bsunanda**: Run3-gex68 Check in more detail the contents of the geometry `simulation`  created: 2021-04-15 16:13:02 merged: 2021-04-17 06:52:48



87. [33441](http://github.com/cms-sw/cmssw/pull/33441){:target="_blank"}  from **@bsunanda**: Phase2-sim84 Utilize a phase2 scenario for testing dd4hep `simulation`  created: 2021-04-15 13:53:42 merged: 2021-04-16 01:29:33



88. [33440](http://github.com/cms-sw/cmssw/pull/33440){:target="_blank"}  from **@bsunanda**: Run3-hcx295 Correct validation code for MB of HCAL `dqm`  `geometry`  created: 2021-04-15 12:40:25 merged: 2021-04-16 11:59:45



89. [33439](http://github.com/cms-sw/cmssw/pull/33439){:target="_blank"}  from **@battibass**: DT DQM slice-test updates `dqm`  created: 2021-04-15 10:16:47 merged: 2021-04-16 11:59:19



90. [33437](http://github.com/cms-sw/cmssw/pull/33437){:target="_blank"}  from **@barvic**: re-introduce IORawData/CSCCommissioning module for CSC data files conversion `daq`  created: 2021-04-15 02:38:36 merged: 2021-04-28 11:01:30



91. [33434](http://github.com/cms-sw/cmssw/pull/33434){:target="_blank"}  from **@mmusich**: migrate DQM/TrackingMonitor to esConsumes `dqm`  created: 2021-04-14 19:30:10 merged: 2021-04-16 16:26:02



92. [33433](http://github.com/cms-sw/cmssw/pull/33433){:target="_blank"}  from **@Ror5ch**: Added ZpEE and ZpMM GEN fragments for release validation `generators`  created: 2021-04-14 16:22:50 merged: 2021-04-20 16:03:51



93. [33431](http://github.com/cms-sw/cmssw/pull/33431){:target="_blank"}  from **@thomreis**: Migrate EcalTPCondAnalyzer to use esConsumes `l1`  created: 2021-04-14 15:06:10 merged: 2021-04-16 16:27:29



94. [33430](http://github.com/cms-sw/cmssw/pull/33430){:target="_blank"}  from **@sroychow**: TkDQM: introduce new harvester module for creating 2D folded occupancy maps `dqm`  created: 2021-04-14 12:56:42 merged: 2021-04-19 07:47:30



95. [33429](http://github.com/cms-sw/cmssw/pull/33429){:target="_blank"}  from **@dildick**: Use CSCConstants in CSC trigger, packer, unpacker and track-finders `dqm`  `l1`  `reconstruction`  `simulation`  created: 2021-04-14 04:09:28 merged: 2021-04-20 15:31:32



96. [33424](http://github.com/cms-sw/cmssw/pull/33424){:target="_blank"}  from **@bsunanda**: Run3-gex67 Modify Run3 workflows with changed version of RP devices `geometry`  `upgrade`  created: 2021-04-13 15:23:14 merged: 2021-04-16 01:32:42



97. [33423](http://github.com/cms-sw/cmssw/pull/33423){:target="_blank"}  from **@bsunanda**: Phase2-gex67 Add a new workflow with V15 version of HGCal Geometry `geometry`  `operations`  `pdmv`  `upgrade`  created: 2021-04-13 15:19:25 merged: 2021-04-16 11:58:51



98. [33422](http://github.com/cms-sw/cmssw/pull/33422){:target="_blank"}  from **@adewit**: Remove trackingMaterialGroups_ForPhaseII.xml from T25/T26 dict `geometry`  `upgrade`  created: 2021-04-13 13:49:03 merged: 2021-04-16 00:38:21



99. [33421](http://github.com/cms-sw/cmssw/pull/33421){:target="_blank"}  from **@archiron**: /validation/RecoEgamma/ Phase2 miniAOD modification v2 `dqm`  created: 2021-04-13 12:14:32 merged: 2021-04-27 00:50:25



100. [33420](http://github.com/cms-sw/cmssw/pull/33420){:target="_blank"}  from **@perrotta**: Modernize code and simplify GeometricSearchTrackerBuilder `reconstruction`  created: 2021-04-13 11:11:18 merged: 2021-04-19 07:47:38



101. [33418](http://github.com/cms-sw/cmssw/pull/33418){:target="_blank"}  from **@perrotta**: Remove deprecated usages of isnan or isinf `alca`  `dqm`  `fastsim`  `reconstruction`  created: 2021-04-13 07:06:31 merged: 2021-04-21 09:12:11



102. [33416](http://github.com/cms-sw/cmssw/pull/33416){:target="_blank"}  from **@dildick**: Hit counters for Run-3 shower CSC trigger (HadronicShowerTrigger-2) `l1`  created: 2021-04-13 02:33:23 merged: 2021-04-16 15:41:56



103. [33414](http://github.com/cms-sw/cmssw/pull/33414){:target="_blank"}  from **@therwig**: Additional 14 TeV gen fragments for SUSY release validation `generators`  created: 2021-04-12 17:31:48 merged: 2021-04-20 19:21:07



104. [33413](http://github.com/cms-sw/cmssw/pull/33413){:target="_blank"}  from **@laurenhay**: Make BadHcalMitigation enabled by default `operations`  `pdmv`  `reconstruction`  `upgrade`  created: 2021-04-12 16:57:36 merged: 2021-04-19 16:55:51



105. [33412](http://github.com/cms-sw/cmssw/pull/33412){:target="_blank"}  from **@ebrondol**: [HGCAL] Fix deprecated method for ESHandle `dqm`  `reconstruction`  `upgrade`  created: 2021-04-12 15:54:45 merged: 2021-04-26 17:13:00



106. [33411](http://github.com/cms-sw/cmssw/pull/33411){:target="_blank"}  from **@akhukhun**: Fix conditions dumping for specific tags `db`  created: 2021-04-12 15:49:37 merged: 2021-04-27 13:36:11



107. [33409](http://github.com/cms-sw/cmssw/pull/33409){:target="_blank"}  from **@sharmaaash**:  New_samples (TTbarLepton_14 and QQH1252T_14) added without updating 'upgradeWorkflowComponents' file `generators`  created: 2021-04-12 14:34:53 merged: 2021-04-28 23:58:33



108. [33408](http://github.com/cms-sw/cmssw/pull/33408){:target="_blank"}  from **@ats2008**: All daughter decay filter `generators`  created: 2021-04-12 12:47:07 merged: 2021-04-16 12:05:59



109. [33407](http://github.com/cms-sw/cmssw/pull/33407){:target="_blank"}  from **@mtosi**: add WToLNu and WprimeToLNu genFragments at 14 TeV `generators`  `pdmv`  created: 2021-04-12 11:33:44 merged: 2021-05-04 05:47:30



110. [33405](http://github.com/cms-sw/cmssw/pull/33405){:target="_blank"}  from **@CTPPS**: Changing the proton propagator to the Optical Function method `simulation`  created: 2021-04-12 01:29:39 merged: 2021-04-21 08:12:12



111. [33399](http://github.com/cms-sw/cmssw/pull/33399){:target="_blank"}  from **@mmusich**: Split SiPixelCalSingleMuon into two separate ALCARECO producers `alca`  `operations`  `pdmv`  `upgrade`  created: 2021-04-11 16:48:13 merged: 2021-04-19 09:16:14



112. [33386](http://github.com/cms-sw/cmssw/pull/33386){:target="_blank"}  from **@vjmastra**: EtaBToJpsiJpsi gen fragment at 14 TeV for release validation `generators`  created: 2021-04-09 15:05:19 merged: 2021-04-30 01:16:43



113. [33384](http://github.com/cms-sw/cmssw/pull/33384){:target="_blank"}  from **@lecriste**: [HGCAL] MultiCluster to CaloParticle associator `reconstruction`  `simulation`  `upgrade`  created: 2021-04-09 11:46:59 merged: 2021-04-18 01:32:49



114. [33371](http://github.com/cms-sw/cmssw/pull/33371){:target="_blank"}  from **@VinInn**: Make the the size of the binner (HistoContainer) settable at run time. The total number of Pixel Clusters is not a limit anymore on GPU `heterogeneous`  `reconstruction`  created: 2021-04-08 09:07:19 merged: 2021-04-16 01:34:31



115. [33339](http://github.com/cms-sw/cmssw/pull/33339){:target="_blank"}  from **@ianna**: [DD4hep] Ecal Barrel algorithm - use assemblies. Fix all overlaps in EBAR. `geometry`  created: 2021-04-06 13:00:20 merged: 2021-04-21 15:24:42



116. [33318](http://github.com/cms-sw/cmssw/pull/33318){:target="_blank"}  from **@felicepantaleo**: [HGCAL] TICL SimTracksters `dqm`  `reconstruction`  `simulation`  `upgrade`  created: 2021-03-31 16:18:23 merged: 2021-04-16 01:30:13



117. [33300](http://github.com/cms-sw/cmssw/pull/33300){:target="_blank"}  from **@claralasa**: [Upgrade Phase-2 Pixel 3D Digitizer] Fix misevaluation of charge when migrating due to diffusion `simulation`  `upgrade`  created: 2021-03-30 15:50:53 merged: 2021-04-20 10:01:12



118. [33215](http://github.com/cms-sw/cmssw/pull/33215){:target="_blank"}  from **@forthommel**: [PPS] Prompt calibration loop component for timing detector `alca`  `hlt`  `operations`  `pdmv`  `upgrade`  created: 2021-03-18 18:17:41 merged: 2021-04-19 16:40:26



119. [33186](http://github.com/cms-sw/cmssw/pull/33186){:target="_blank"}  from **@davidlange6**: moving DataFormats/RecoCandidate/interface/TrackAssociation.h into SimDataFormats `alca`  `analysis`  `dqm`  `l1`  `reconstruction`  `simulation`  created: 2021-03-16 08:15:14 merged: 2021-04-26 09:23:59



120. [31697](http://github.com/cms-sw/cmssw/pull/31697){:target="_blank"}  from **@makortel**: Migrate most of MixingModule and PreMixingModule to EventSetup consumes `alca`  `db`  `reconstruction`  `simulation`  `upgrade`  created: 2020-10-07 15:25:30 merged: 2021-04-30 08:17:10



#### CMSDIST Changes between Tags REL/CMSSW_11_3_0_pre6/slc7_amd64_gcc900 and REL/CMSSW_12_0_0_pre1/slc7_amd64_gcc900:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_11_3_0_pre6/slc7_amd64_gcc900...REL/CMSSW_12_0_0_pre1/slc7_amd64_gcc900)



1. [6877](http://github.com/cms-sw/cmsdist/pull/6877){:target="_blank"}  from **@cms-sw**: [SCRAM] Protect against failure when run in container created: 2021-05-05 15:38:19 merged: 2021-05-05 16:07:06

2. [6874](http://github.com/cms-sw/cmsdist/pull/6874){:target="_blank"}  from **@cms-sw**: [SCRAM] Fix scram build -j without N option bug created: 2021-05-05 06:54:33 merged: 2021-05-05 08:26:05

3. [6873](http://github.com/cms-sw/cmsdist/pull/6873){:target="_blank"}  from **@gartung**: Add libunwind dependency on zlib. created: 2021-05-04 17:08:26 merged: 2021-05-05 11:25:53

4. [6871](http://github.com/cms-sw/cmsdist/pull/6871){:target="_blank"}  from **@cms-sw**: Update tag for GeneratorInterface-EvtGenInterface to V02-04-00 created: 2021-05-04 06:43:49 merged: 2021-05-04 08:50:51

5. [6870](http://github.com/cms-sw/cmsdist/pull/6870){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-ElectronIdentification to V01-05-00 created: 2021-05-04 06:28:42 merged: 2021-05-04 15:27:40

6. [6868](http://github.com/cms-sw/cmsdist/pull/6868){:target="_blank"}  from **@cms-sw**: [SCRAMV3] Fix for create dev area of AFS created: 2021-05-03 14:19:16 merged: 2021-05-03 18:29:19

7. [6867](http://github.com/cms-sw/cmsdist/pull/6867){:target="_blank"}  from **@gartung**: Igprof patch for TBB resumable tasks created: 2021-05-03 14:06:01 merged: 2021-05-04 13:08:18

8. [6866](http://github.com/cms-sw/cmsdist/pull/6866){:target="_blank"}  from **@cms-sw**: ROOT 6-22 - get one commit created: 2021-05-03 10:25:32 merged: 2021-05-05 08:38:17

9. [6864](http://github.com/cms-sw/cmsdist/pull/6864){:target="_blank"}  from **@cms-sw**: [SCRAM] Fixes for recursive scram build created: 2021-05-03 07:58:05 merged: 2021-05-03 12:57:54

10. [6861](http://github.com/cms-sw/cmsdist/pull/6861){:target="_blank"}  from **@cms-sw**: [BuildRules] LCGDict rules fixed for CXXMODULE IBs created: 2021-05-01 21:01:42 merged: 2021-05-02 02:35:39

11. [6860](http://github.com/cms-sw/cmsdist/pull/6860){:target="_blank"}  from **@cms-sw**: [SCRAMV3] Fix for scram tool info created: 2021-04-30 11:34:52 merged: 2021-04-30 16:03:33

12. [6855](http://github.com/cms-sw/cmsdist/pull/6855){:target="_blank"}  from **@hqucms**: Enable DYNAMIC_CPU_ARCH in ONNXRuntime to use up to AVX2 created: 2021-04-28 13:50:51 merged: 2021-04-29 13:14:59

13. [6854](http://github.com/cms-sw/cmsdist/pull/6854){:target="_blank"}  from **@gartung**: Profiling tools update.  created: 2021-04-28 13:02:25 merged: 2021-04-29 13:17:07

14. [6853](http://github.com/cms-sw/cmsdist/pull/6853){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-PhotonIdentification to V01-01-00 created: 2021-04-28 10:55:26 merged: 2021-04-29 05:35:46

15. [6851](http://github.com/cms-sw/cmsdist/pull/6851){:target="_blank"}  from **@fwyzard**: Keep the PTX in CUDA binaries, so it can be JIT'ted for newer devices created: 2021-04-28 08:08:36 merged: 2021-04-30 10:21:31

16. [6849](http://github.com/cms-sw/cmsdist/pull/6849){:target="_blank"}  from **@cms-sw**: Update SCRAM V3 created: 2021-04-27 17:11:08 merged: 2021-04-29 20:22:08

17. [6845](http://github.com/cms-sw/cmsdist/pull/6845){:target="_blank"}  from **@cms-sw**: build py2-Pygments which is needed by dxr; treat .icc as cpp files created: 2021-04-27 12:50:22 merged: 2021-04-27 20:44:14

18. [6844](http://github.com/cms-sw/cmsdist/pull/6844){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-11-00 created: 2021-04-27 12:48:17 merged: 2021-04-29 15:38:37

19. [6843](http://github.com/cms-sw/cmsdist/pull/6843){:target="_blank"}  from **@vbotta**: Update MillePede to version V04-09-01 created: 2021-04-27 11:13:23 merged: 2021-04-28 19:08:43

20. [6841](http://github.com/cms-sw/cmsdist/pull/6841){:target="_blank"}  from **@cms-sw**: ROOT 6-22 - get latest commits created: 2021-04-27 09:41:15 merged: 2021-04-30 16:57:41

21. [6838](http://github.com/cms-sw/cmsdist/pull/6838){:target="_blank"}  from **@cms-sw**: Update professor2 patch for PPC created: 2021-04-23 15:02:59 merged: 2021-04-24 13:33:23

22. [6832](http://github.com/cms-sw/cmsdist/pull/6832){:target="_blank"}  from **@ddaina**: move crab-dev to v3.210422 created: 2021-04-22 14:49:55 merged: 2021-04-23 11:17:30

23. [6830](http://github.com/cms-sw/cmsdist/pull/6830){:target="_blank"}  from **@cms-sw**: Coral - Fix for limiting idle connection pool size created: 2021-04-21 21:04:35 merged: 2021-04-22 12:06:15

24. [6826](http://github.com/cms-sw/cmsdist/pull/6826){:target="_blank"}  from **@cms-sw**: DD4Hep - get latest on master created: 2021-04-20 20:39:18 merged: 2021-04-21 08:58:02

25. [6825](http://github.com/cms-sw/cmsdist/pull/6825){:target="_blank"}  from **@cms-sw**: Openloops - remove a process created: 2021-04-20 17:24:58 merged: 2021-04-21 08:52:49

26. [6822](http://github.com/cms-sw/cmsdist/pull/6822){:target="_blank"}  from **@mseidel42**: Rivet 3.1.4, YODA 1.9.0, Professor 2.3.2 created: 2021-04-20 13:05:08 merged: 2021-04-22 14:35:11

27. [6821](http://github.com/cms-sw/cmsdist/pull/6821){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2021-04-20 12:25:10 merged: 2021-04-21 08:58:51

28. [6820](http://github.com/cms-sw/cmsdist/pull/6820){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-06-00 created: 2021-04-20 10:05:39 merged: 2021-04-20 10:06:24

29. [6818](http://github.com/cms-sw/cmsdist/pull/6818){:target="_blank"}  from **@cms-sw**: onnxruntime - get latest Arm fix created: 2021-04-19 08:04:30 merged: 2021-04-20 12:46:41

30. [6815](http://github.com/cms-sw/cmsdist/pull/6815){:target="_blank"}  from **@cms-sw**: onnxruntime - get updates for Arm created: 2021-04-16 09:26:09 merged: 2021-04-16 14:39:18

31. [6810](http://github.com/cms-sw/cmsdist/pull/6810){:target="_blank"}  from **@cms-sw**: ROOT - get latest commits from 6.22 created: 2021-04-14 16:10:00 merged: 2021-04-21 19:50:04

32. [6808](http://github.com/cms-sw/cmsdist/pull/6808){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-CSCTriggerPrimitives to V00-05-00 created: 2021-04-14 14:29:30 merged: 2021-04-14 14:31:01

33. [6807](http://github.com/cms-sw/cmsdist/pull/6807){:target="_blank"}  from **@cms-sw**: Update tag for GeneratorInterface-EvtGenInterface to V02-03-00 created: 2021-04-14 13:47:03 merged: 2021-04-14 14:34:00

34. [6804](http://github.com/cms-sw/cmsdist/pull/6804){:target="_blank"}  from **@vkuznet**: New dasgoclient version created: 2021-04-12 18:07:13 merged: 2021-04-13 19:40:05

35. [6792](http://github.com/cms-sw/cmsdist/pull/6792){:target="_blank"}  from **@mrodozov**: Update TBB to 2021.2.0 and use cmake to build created: 2021-04-07 12:12:59 merged: 2021-05-04 16:33:41

36. [6770](http://github.com/cms-sw/cmsdist/pull/6770){:target="_blank"}  from **@cms-sw**: Updated Pygments to 2.7.4 created: 2021-03-30 08:47:23 merged: 2021-04-20 07:45:21
