---
layout: post
rel_link:  "11_2_0_pre4"
title:  "CMSSW_11_2_0_pre4"
date:   2020-08-21 20:54:52
categories: cmssw
relmajor: 11
relminor: 2
relsubminor: 0
relpre: _pre4
---

# CMSSW_11_2_0_pre4
#### Changes since CMSSW_11_2_0_pre3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_11_2_0_pre3...CMSSW_11_2_0_pre4)



1. [31196](http://github.com/cms-sw/cmssw/pull/31196){:target="_blank"}  from **@davidlange6**: change return type of geomTracker to derived class (TrackerGeometry vs TrackingGeometry) `hlt`  `reconstruction`  created: 2020-08-20 17:40:39 merged: 2020-08-21 04:53:48



2. [31193](http://github.com/cms-sw/cmssw/pull/31193){:target="_blank"}  from **@jeongsumin**: [RPC] Removing the RPCDcsInfo module from RPC online client `dqm`  created: 2020-08-20 14:15:13 merged: 2020-08-21 13:17:37



3. [31188](http://github.com/cms-sw/cmssw/pull/31188){:target="_blank"}  from **@davidlange6**: change name of WSelector to avoid class name conflicts in same package `analysis`  created: 2020-08-20 06:34:24 merged: 2020-08-21 12:08:14



4. [31183](http://github.com/cms-sw/cmssw/pull/31183){:target="_blank"}  from **@vargasa**: Geometry: Remove Custom SpecPars from T23 Dict `geometry`  `upgrade`  created: 2020-08-19 21:26:41 merged: 2020-08-20 14:27:46



5. [31179](http://github.com/cms-sw/cmssw/pull/31179){:target="_blank"}  from **@perrotta**: Remove a duplicate line in FastjetJetProducer.cc `reconstruction`  created: 2020-08-19 16:20:41 merged: 2020-08-20 01:42:43



6. [31177](http://github.com/cms-sw/cmssw/pull/31177){:target="_blank"}  from **@ahinzmann**: Fix UL jet ID working point in DQM `dqm`  created: 2020-08-19 13:33:42 merged: 2020-08-20 01:42:04



7. [31175](http://github.com/cms-sw/cmssw/pull/31175){:target="_blank"}  from **@mommsen**: Add GEM plus/minus HV states `core`  `daq`  `reconstruction`  created: 2020-08-19 13:25:53 merged: 2020-08-21 08:42:56



8. [31170](http://github.com/cms-sw/cmssw/pull/31170){:target="_blank"}  from **@Dr15Jones**: Fix undefined behavior in EgammaTowerIsolation `reconstruction`  created: 2020-08-18 21:14:23 merged: 2020-08-20 01:41:36



9. [31169](http://github.com/cms-sw/cmssw/pull/31169){:target="_blank"}  from **@mmusich**: SimG4Core/Configuration: hardcoded GTs do not age well `simulation`  created: 2020-08-18 20:39:34 merged: 2020-08-20 01:40:55



10. [31168](http://github.com/cms-sw/cmssw/pull/31168){:target="_blank"}  from **@vargasa**: DD4hep: SimTracker/TrackerMaterialAnalysis Update migrated test ph1 `simulation`  created: 2020-08-18 20:03:33 merged: 2020-08-20 01:40:01



11. [31167](http://github.com/cms-sw/cmssw/pull/31167){:target="_blank"}  from **@camolezi**: Moved boost includes to the implementation file `analysis`  `reconstruction`  created: 2020-08-18 18:54:53 merged: 2020-08-20 01:38:51



12. [31166](http://github.com/cms-sw/cmssw/pull/31166){:target="_blank"}  from **@Dr15Jones**: Apply necessary changes to work with python3 `db`  created: 2020-08-18 18:45:51 merged: 2020-08-19 06:59:40



13. [31162](http://github.com/cms-sw/cmssw/pull/31162){:target="_blank"}  from **@jeongeun**: drop type specs in RecoJets `reconstruction`  created: 2020-08-18 10:12:01 merged: 2020-08-20 17:14:05



14. [31157](http://github.com/cms-sw/cmssw/pull/31157){:target="_blank"}  from **@civanch**: Added Z of the central detector for very forward simulation `simulation`  created: 2020-08-16 17:05:39 merged: 2020-08-17 01:39:28



15. [31155](http://github.com/cms-sw/cmssw/pull/31155){:target="_blank"}  from **@cms-patatrack**: Add a service to handle MPI initialisation `heterogeneous`  created: 2020-08-16 12:29:13 merged: 2020-08-19 01:47:33



16. [31153](http://github.com/cms-sw/cmssw/pull/31153){:target="_blank"}  from **@davidlange6**: add missing dep on FWCore/Utilities `core`  created: 2020-08-16 09:25:14 merged: 2020-08-17 01:38:35



17. [31152](http://github.com/cms-sw/cmssw/pull/31152){:target="_blank"}  from **@bsunanda**: Phase2-hgx259 Change the validation code for HGCal to make it work for DDD as well as for DD4hep `dqm`  created: 2020-08-15 16:40:22 merged: 2020-08-17 11:51:19



18. [31151](http://github.com/cms-sw/cmssw/pull/31151){:target="_blank"}  from **@hatakeyamak**: Cleanup of the PFTrack class `reconstruction`  created: 2020-08-15 14:33:01 merged: 2020-08-18 15:52:54



19. [31150](http://github.com/cms-sw/cmssw/pull/31150){:target="_blank"}  from **@camolezi**: Remove boost::phoenix dependency `core`  created: 2020-08-15 13:59:37 merged: 2020-08-17 01:38:19



20. [31149](http://github.com/cms-sw/cmssw/pull/31149){:target="_blank"}  from **@fwyzard**: Remove or make const few PFCluster obsolete data members `reconstruction`  created: 2020-08-15 12:10:25 merged: 2020-08-17 11:52:04



21. [31148](http://github.com/cms-sw/cmssw/pull/31148){:target="_blank"}  from **@perrotta**: Remove dead assignments in EventFilter/Utilities/DirManager and Validation/RecoTrack/SiStripTrackingRecHitsValid `daq`  `dqm`  `reconstruction`  created: 2020-08-15 08:26:26 merged: 2020-08-18 15:55:08



22. [31147](http://github.com/cms-sw/cmssw/pull/31147){:target="_blank"}  from **@Dr15Jones**: Initialize members in FastSimulation Crystal class `fastsim`  created: 2020-08-14 20:53:26 merged: 2020-08-21 01:07:39



23. [31146](http://github.com/cms-sw/cmssw/pull/31146){:target="_blank"}  from **@Dr15Jones**: Fix gcc10 warning in prepareMagneticFieldGrid `reconstruction`  created: 2020-08-14 20:27:05 merged: 2020-08-15 07:42:39



24. [31145](http://github.com/cms-sw/cmssw/pull/31145){:target="_blank"}  from **@Dr15Jones**: Fix gcc10 warning in KDTreeLinkerAlgo `reconstruction`  created: 2020-08-14 20:01:34 merged: 2020-08-15 07:41:55



25. [31144](http://github.com/cms-sw/cmssw/pull/31144){:target="_blank"}  from **@bsunanda**: Run3-gem51 Add a tool to compare DDD vs DD4HEP for CSC geometry `geometry`  created: 2020-08-14 19:27:38 merged: 2020-08-18 15:56:42



26. [31142](http://github.com/cms-sw/cmssw/pull/31142){:target="_blank"}  from **@vargasa**: DD4hep: SimTracker/TrackerMaterialAnalysis code update `simulation`  created: 2020-08-14 18:39:05 merged: 2020-08-17 01:37:16



27. [31141](http://github.com/cms-sw/cmssw/pull/31141){:target="_blank"}  from **@mmusich**: Update Alignment/OfflineValidation package `alca`  `db`  created: 2020-08-14 17:17:53 merged: 2020-08-18 15:51:55



28. [31140](http://github.com/cms-sw/cmssw/pull/31140){:target="_blank"}  from **@bsunanda**: Run3-TB60 Update and correct HCAL TB06 simulation `simulation`  created: 2020-08-14 14:54:30 merged: 2020-08-16 04:12:55



29. [31135](http://github.com/cms-sw/cmssw/pull/31135){:target="_blank"}  from **@Dr15Jones**: Fix undefined behavior in CaloPoint `fastsim`  created: 2020-08-13 20:16:06 merged: 2020-08-21 01:04:17



30. [31134](http://github.com/cms-sw/cmssw/pull/31134){:target="_blank"}  from **@Dr15Jones**: Fix undefined behavior in MTVHistoProducerAlgoForTracker `dqm`  created: 2020-08-13 17:58:46 merged: 2020-08-14 12:56:11



31. [31133](http://github.com/cms-sw/cmssw/pull/31133){:target="_blank"}  from **@bsunanda**: Run3-ft30 Cleanup a few buildfiles with duplicate use `reconstruction`  `simulation`  created: 2020-08-13 17:49:45 merged: 2020-08-14 07:04:42



32. [31131](http://github.com/cms-sw/cmssw/pull/31131){:target="_blank"}  from **@bsunanda**: Run3-gem50 Simplify access to fv and a dump utility `geometry`  `simulation`  `upgrade`  created: 2020-08-13 16:28:38 merged: 2020-08-19 01:48:56



33. [31128](http://github.com/cms-sw/cmssw/pull/31128){:target="_blank"}  from **@mmusich**: Refine RuInfo payload inspector `db`  created: 2020-08-12 15:57:04 merged: 2020-08-18 15:55:27



34. [31125](http://github.com/cms-sw/cmssw/pull/31125){:target="_blank"}  from **@ahinzmann**: Switch to UL jet ID in NanoAOD `analysis`  `xpog`  created: 2020-08-12 15:04:00 merged: 2020-08-20 01:38:08



35. [31122](http://github.com/cms-sw/cmssw/pull/31122){:target="_blank"}  from **@justinasr**: Move "wmsplit" dict build to a static method, remove circular import `pdmv`  `upgrade`  created: 2020-08-12 10:33:36 merged: 2020-08-12 17:10:52



36. [31121](http://github.com/cms-sw/cmssw/pull/31121){:target="_blank"}  from **@jpata**: optimize PFDisplacedVertexCandidateFinder::link `analysis`  `reconstruction`  created: 2020-08-12 07:12:35 merged: 2020-08-20 07:09:49



37. [31118](http://github.com/cms-sw/cmssw/pull/31118){:target="_blank"}  from **@perrotta**: Make CentralityProducer a global module `reconstruction`  created: 2020-08-11 14:10:14 merged: 2020-08-13 08:13:28



38. [31117](http://github.com/cms-sw/cmssw/pull/31117){:target="_blank"}  from **@slehti**: Hlt tau validation conditional plotting4 `dqm`  created: 2020-08-11 10:44:17 merged: 2020-08-13 15:07:27



39. [31116](http://github.com/cms-sw/cmssw/pull/31116){:target="_blank"}  from **@srimanob**: Define (GEN) only eventcontent `operations`  created: 2020-08-11 10:38:34 merged: 2020-08-12 01:18:07



40. [31115](http://github.com/cms-sw/cmssw/pull/31115){:target="_blank"}  from **@hatakeyamak**: Basic2D PFCluster for each rechit seed `hlt`  `reconstruction`  created: 2020-08-11 06:07:01 merged: 2020-08-17 08:05:24



41. [31112](http://github.com/cms-sw/cmssw/pull/31112){:target="_blank"}  from **@vargasa**: DD4hep: SimTracker/TrackerMaterialAnalysis SpecPars Groups `geometry`  `simulation`  `upgrade`  created: 2020-08-10 22:43:20 merged: 2020-08-16 09:34:17



42. [31111](http://github.com/cms-sw/cmssw/pull/31111){:target="_blank"}  from **@christopheralanwest**: Modify HCAL reco pulse shape for Run 3 `alca`  created: 2020-08-10 18:34:16 merged: 2020-08-11 14:32:25



43. [31110](http://github.com/cms-sw/cmssw/pull/31110){:target="_blank"}  from **@cms-patatrack**: Patatrack integration - common tools updates (3/N) `heterogeneous`  created: 2020-08-10 17:22:07 merged: 2020-08-11 05:49:09



44. [31109](http://github.com/cms-sw/cmssw/pull/31109){:target="_blank"}  from **@mariadalfonso**: Nano: add  workflows for run2_nanoAOD_106Xv1 `pdmv`  `upgrade`  created: 2020-08-10 17:07:38 merged: 2020-08-14 16:18:38



45. [31108](http://github.com/cms-sw/cmssw/pull/31108){:target="_blank"}  from **@mmusich**: Clean up CondTools/DQM configurations and add unit tests `db`  `dqm`  created: 2020-08-10 10:11:55 merged: 2020-08-12 15:44:20



46. [31104](http://github.com/cms-sw/cmssw/pull/31104){:target="_blank"}  from **@johnalison**: Add trigger to btv offline `dqm`  created: 2020-08-08 11:43:19 merged: 2020-08-21 12:20:51



47. [31103](http://github.com/cms-sw/cmssw/pull/31103){:target="_blank"}  from **@missirol**: fixed some special comments for clang-format in FastTimerService `hlt`  created: 2020-08-08 08:20:04 merged: 2020-08-08 19:17:54



48. [31098](http://github.com/cms-sw/cmssw/pull/31098){:target="_blank"}  from **@kpedro88**: convert L1TkMuon to stream producer `l1`  `upgrade`  created: 2020-08-07 23:21:12 merged: 2020-08-12 16:04:46



49. [31095](http://github.com/cms-sw/cmssw/pull/31095){:target="_blank"}  from **@mmusich**: Introduce SiPhase2OuterTrackerLorentzAngle  `alca`  `db`  `geometry`  `pdmv`  `reconstruction`  `simulation`  `upgrade`  created: 2020-08-07 17:12:05 merged: 2020-08-18 12:01:49



50. [31094](http://github.com/cms-sw/cmssw/pull/31094){:target="_blank"}  from **@bsunanda**: Phase2-gem49 Use constants defined in DataFormats `geometry`  `upgrade`  created: 2020-08-07 15:07:47 merged: 2020-08-10 07:09:07



51. [31093](http://github.com/cms-sw/cmssw/pull/31093){:target="_blank"}  from **@Dr15Jones**: Do not deref unset edm::Handle in OtherThingAlgorithm `core`  created: 2020-08-07 14:14:14 merged: 2020-08-08 07:48:04



52. [31092](http://github.com/cms-sw/cmssw/pull/31092){:target="_blank"}  from **@bsunanda**: Phase2-gex08 Rearrange the sequencing of the xml files for dd4hep `geometry`  `upgrade`  created: 2020-08-07 13:06:58 merged: 2020-08-10 07:12:19



53. [31091](http://github.com/cms-sw/cmssw/pull/31091){:target="_blank"}  from **@mmusich**: fix upgrade workflow steps for wf introduced in #30976 `comparison`  `pdmv`  `upgrade`  created: 2020-08-07 08:01:54 merged: 2020-08-07 08:47:42



54. [31083](http://github.com/cms-sw/cmssw/pull/31083){:target="_blank"}  from **@vargasa**: SimTracker/TrackerMaterialAnalysis Unit test `simulation`  created: 2020-08-06 21:07:43 merged: 2020-08-10 11:51:16



55. [31082](http://github.com/cms-sw/cmssw/pull/31082){:target="_blank"}  from **@bsunanda**: Run3-gex07 Create Run3 geometry with zero tracker material `geometry`  `operations`  `upgrade`  created: 2020-08-06 20:20:29 merged: 2020-08-11 15:50:35



56. [31080](http://github.com/cms-sw/cmssw/pull/31080){:target="_blank"}  from **@CMSBParking**: LowPtElectrons: updated BDT model and code base for ID `reconstruction`  created: 2020-08-06 19:07:25 merged: 2020-08-19 01:47:55



57. [31079](http://github.com/cms-sw/cmssw/pull/31079){:target="_blank"}  from **@gartung**: runTheMatrix.py: Change confusing message about number of threads. `pdmv`  `upgrade`  created: 2020-08-06 15:16:48 merged: 2020-08-08 07:46:43



58. [31078](http://github.com/cms-sw/cmssw/pull/31078){:target="_blank"}  from **@bsunanda**: Run4-hgx258 Try to address the issue reported in #31059 `geometry`  `upgrade`  created: 2020-08-06 13:57:19 merged: 2020-08-11 05:47:22



59. [31077](http://github.com/cms-sw/cmssw/pull/31077){:target="_blank"}  from **@cms-tau-pog**: Add the anti-electron-in-deadECal tauID to NanoAOD `analysis`  `xpog`  created: 2020-08-06 13:43:15 merged: 2020-08-18 01:24:03



60. [31075](http://github.com/cms-sw/cmssw/pull/31075){:target="_blank"}  from **@CTPPS**: PPS: adding missing IO rule for class TotemRPUVPattern `reconstruction`  created: 2020-08-06 11:41:25 merged: 2020-08-07 12:24:20



61. [31070](http://github.com/cms-sw/cmssw/pull/31070){:target="_blank"}  from **@bsunanda**: Run3-gem48 Use uniformly fromDD.. in all muon geometry builder `alca`  `geometry`  `hlt`  created: 2020-08-05 21:57:19 merged: 2020-08-10 16:01:05



62. [31067](http://github.com/cms-sw/cmssw/pull/31067){:target="_blank"}  from **@bsunanda**: Run3-gem47 Make ME0 geometry builder to work with dd4hep `geometry`  `upgrade`  created: 2020-08-05 19:11:11 merged: 2020-08-06 19:19:32



63. [31066](http://github.com/cms-sw/cmssw/pull/31066){:target="_blank"}  from **@wddgit**: update comment about concurrency `alca`  `db`  created: 2020-08-05 17:34:01 merged: 2020-08-12 15:46:10



64. [31064](http://github.com/cms-sw/cmssw/pull/31064){:target="_blank"}  from **@TaeunKwon**: code updates to add a noise correlation factor between adjacent time slices for HB and HE channels `reconstruction`  created: 2020-08-05 16:28:00 merged: 2020-08-13 05:22:02



65. [31060](http://github.com/cms-sw/cmssw/pull/31060){:target="_blank"}  from **@kpedro88**: fix premix nano step `pdmv`  `upgrade`  created: 2020-08-05 13:31:23 merged: 2020-08-06 19:17:14



66. [31058](http://github.com/cms-sw/cmssw/pull/31058){:target="_blank"}  from **@bsunanda**: Run3-gem46 Make 2 constants public (used in GeometryBuilder) `simulation`  created: 2020-08-05 13:05:24 merged: 2020-08-06 08:32:06



67. [31057](http://github.com/cms-sw/cmssw/pull/31057){:target="_blank"}  from **@silviodonato**: Remove L1Tk paths defined in L1TkObjectProducers_cff.py  `l1`  `upgrade`  created: 2020-08-05 12:13:58 merged: 2020-08-07 08:21:44



68. [31056](http://github.com/cms-sw/cmssw/pull/31056){:target="_blank"}  from **@jeongsumin**: [RPC] Changing the RPCDcsInfo* about an issue of the DQM legacy module `dqm`  created: 2020-08-05 09:11:20 merged: 2020-08-18 15:57:39



69. [31055](http://github.com/cms-sw/cmssw/pull/31055){:target="_blank"}  from **@ats2008**: Selector by region `reconstruction`  created: 2020-08-05 08:34:31 merged: 2020-08-13 07:55:04



70. [31053](http://github.com/cms-sw/cmssw/pull/31053){:target="_blank"}  from **@srimanob**: Add missing GEN fragment for relvals `generators`  created: 2020-08-05 07:53:41 merged: 2020-08-20 07:12:53



71. [31050](http://github.com/cms-sw/cmssw/pull/31050){:target="_blank"}  from **@christopheralanwest**: Fix HLT JEC conditions for 2018 MC `alca`  created: 2020-08-04 21:11:03 merged: 2020-08-06 08:30:57



72. [31049](http://github.com/cms-sw/cmssw/pull/31049){:target="_blank"}  from **@adewit**: MillePede alignment: add resubmission option `alca`  created: 2020-08-04 17:12:32 merged: 2020-08-07 12:18:15



73. [31048](http://github.com/cms-sw/cmssw/pull/31048){:target="_blank"}  from **@Dr15Jones**: Add missing pair dictionaries in DataFormats/GEMDigi `simulation`  `upgrade`  created: 2020-08-04 15:51:48 merged: 2020-08-05 13:58:28



74. [31047](http://github.com/cms-sw/cmssw/pull/31047){:target="_blank"}  from **@cms-tau-pog**: Fix to enable hpsPFTauDiscriminationByDeadECALElectronRejection in run2 reminiAODs `analysis`  `reconstruction`  created: 2020-08-04 15:36:44 merged: 2020-08-17 14:28:51



75. [31046](http://github.com/cms-sw/cmssw/pull/31046){:target="_blank"}  from **@bsunanda**: Run3-ft29 Add corresponding cfg's for DDD `simulation`  created: 2020-08-04 13:46:39 merged: 2020-08-05 07:58:59



76. [31045](http://github.com/cms-sw/cmssw/pull/31045){:target="_blank"}  from **@maaraujo94**: Adding an HLT filter for matching between PPS local tracks and central jet properties `hlt`  created: 2020-08-04 11:08:23 merged: 2020-08-14 07:13:37



77. [31042](http://github.com/cms-sw/cmssw/pull/31042){:target="_blank"}  from **@mmusich**: Add SiPixelGenErrorDBObject payload inspector `db`  created: 2020-08-04 08:41:36 merged: 2020-08-04 16:53:06



78. [31041](http://github.com/cms-sw/cmssw/pull/31041){:target="_blank"}  from **@dildick**: Add ghost LCTs in CSC stub matcher `dqm`  created: 2020-08-04 05:05:44 merged: 2020-08-05 08:05:11



79. [31040](http://github.com/cms-sw/cmssw/pull/31040){:target="_blank"}  from **@johnalison**: Add track-to-track validation tool plugin. Added instances for general HLT track monitoring and in BTV specific paths  `dqm`  created: 2020-08-04 01:08:11 merged: 2020-08-21 12:21:31



80. [31039](http://github.com/cms-sw/cmssw/pull/31039){:target="_blank"}  from **@kpedro88**: Fix improper static_cast in HcalAmplifier (part 2) `simulation`  created: 2020-08-04 00:06:20 merged: 2020-08-05 08:20:14



81. [31036](http://github.com/cms-sw/cmssw/pull/31036){:target="_blank"}  from **@hqucms**: New ParticleNet training for UL `reconstruction`  created: 2020-08-03 22:32:55 merged: 2020-08-06 19:27:51



82. [31035](http://github.com/cms-sw/cmssw/pull/31035){:target="_blank"}  from **@Dr15Jones**: Don't use uninitialized edm::Handle in AnalyticalTrackSelector `reconstruction`  created: 2020-08-03 22:17:18 merged: 2020-08-05 07:57:07



83. [31032](http://github.com/cms-sw/cmssw/pull/31032){:target="_blank"}  from **@bsunanda**: Run3-hcx262 Modify the material budget analysis code for HCAL `dqm`  `geometry`  created: 2020-08-03 20:39:05 merged: 2020-08-05 07:31:03



84. [31031](http://github.com/cms-sw/cmssw/pull/31031){:target="_blank"}  from **@Dr15Jones**: Don't use uninitialized edm::Handle in TrackstersProducer `reconstruction`  `upgrade`  created: 2020-08-03 18:50:00 merged: 2020-08-05 15:35:42



85. [31029](http://github.com/cms-sw/cmssw/pull/31029){:target="_blank"}  from **@Dr15Jones**: Don't use an uninitialized edm::Hande in GEDPhotonProducer `reconstruction`  created: 2020-08-03 17:19:30 merged: 2020-08-05 07:55:23



86. [31028](http://github.com/cms-sw/cmssw/pull/31028){:target="_blank"}  from **@dildick**: Revert #29562 and use low-quality ALCTs only in ME2/1 `l1`  created: 2020-08-03 16:35:12 merged: 2020-08-03 20:56:10



87. [31026](http://github.com/cms-sw/cmssw/pull/31026){:target="_blank"}  from **@Dr15Jones**: Modernize modules in HeavyFlavorAnalysis/Onia2MuMu `analysis`  created: 2020-08-03 15:30:41 merged: 2020-08-07 12:13:55



88. [31025](http://github.com/cms-sw/cmssw/pull/31025){:target="_blank"}  from **@makortel**: Remove unnecessary includes to FWCore/ParameterSet `core`  created: 2020-08-03 14:51:09 merged: 2020-08-03 20:41:17



89. [31024](http://github.com/cms-sw/cmssw/pull/31024){:target="_blank"}  from **@mrodozov**: Remove data folder of SimG4CMS/Forward `simulation`  created: 2020-08-03 14:31:45 merged: 2020-08-05 08:06:30



90. [31022](http://github.com/cms-sw/cmssw/pull/31022){:target="_blank"}  from **@civanch**: Update OscarMTProducer initialisation `simulation`  created: 2020-08-02 17:16:56 merged: 2020-08-03 08:13:54



91. [31020](http://github.com/cms-sw/cmssw/pull/31020){:target="_blank"}  from **@christopheralanwest**: Introduce Run 3 cosmics workflow using express GT `alca`  `pdmv`  `upgrade`  created: 2020-08-02 13:31:06 merged: 2020-08-06 08:29:07



92. [31018](http://github.com/cms-sw/cmssw/pull/31018){:target="_blank"}  from **@Dr15Jones**: Fix circular dependencies between Geometry packages `geometry`  `simulation`  created: 2020-08-01 18:23:27 merged: 2020-08-05 08:07:46



93. [31016](http://github.com/cms-sw/cmssw/pull/31016){:target="_blank"}  from **@kpedro88**: Minor updates to Sonic (Core and Triton) `heterogeneous`  created: 2020-08-01 01:48:20 merged: 2020-08-04 08:44:16



94. [31014](http://github.com/cms-sw/cmssw/pull/31014){:target="_blank"}  from **@yihui-lai**: HCAL MC: adding pulse shape 208 for signal reconstruction `alca`  `simulation`  created: 2020-07-31 22:24:31 merged: 2020-08-03 08:15:21



95. [31013](http://github.com/cms-sw/cmssw/pull/31013){:target="_blank"}  from **@JamminJones**: added esConsumes to modules in RecoHGCal/TICL and related packages `dqm`  `reconstruction`  `simulation`  `upgrade`  created: 2020-07-31 21:19:06 merged: 2020-08-08 07:42:53



96. [31011](http://github.com/cms-sw/cmssw/pull/31011){:target="_blank"}  from **@Dr15Jones**: Modernize modules in CalibTracker/SiStripCommon `alca`  created: 2020-07-31 21:00:09 merged: 2020-08-03 08:18:05



97. [31009](http://github.com/cms-sw/cmssw/pull/31009){:target="_blank"}  from **@tvami**: Make CPE packaging code compatible with Phase-2 as well `db`  created: 2020-07-31 19:55:36 merged: 2020-08-04 16:49:32



98. [31008](http://github.com/cms-sw/cmssw/pull/31008){:target="_blank"}  from **@makortel**: Replace snprintf() and string copies with fmt::format() in Validation/Mixing/src/GlobalTest.cc `dqm`  created: 2020-07-31 15:49:07 merged: 2020-08-03 08:12:05



99. [31007](http://github.com/cms-sw/cmssw/pull/31007){:target="_blank"}  from **@makortel**: Modernize MuonTrackProducer `simulation`  created: 2020-07-31 15:30:27 merged: 2020-08-03 08:06:29



100. [31006](http://github.com/cms-sw/cmssw/pull/31006){:target="_blank"}  from **@bsunanda**: Phase2-hgx258 Correct V14 geometry for dd4hep `geometry`  `upgrade`  created: 2020-07-31 14:55:35 merged: 2020-08-06 08:25:19



101. [31004](http://github.com/cms-sw/cmssw/pull/31004){:target="_blank"}  from **@ggovi**: Improvements for the DB credentials infrastructure `db`  created: 2020-07-31 12:19:29 merged: 2020-08-04 16:47:11



102. [31003](http://github.com/cms-sw/cmssw/pull/31003){:target="_blank"}  from **@ianna**: [DD4hep] Extra Check on a DOM Document Validity `geometry`  created: 2020-07-31 12:17:11 merged: 2020-08-20 17:12:08



103. [31001](http://github.com/cms-sw/cmssw/pull/31001){:target="_blank"}  from **@mmusich**: make LSNumberFilter a stream module `alca`  created: 2020-07-31 08:23:42 merged: 2020-08-03 08:10:14



104. [30999](http://github.com/cms-sw/cmssw/pull/30999){:target="_blank"}  from **@christopheralanwest**: Conditions needed to introduce pedestal correlation coefficient for HB and HE channels and update pedestal widths for 2023/2024 `alca`  created: 2020-07-31 03:39:35 merged: 2020-08-03 14:15:23



105. [30997](http://github.com/cms-sw/cmssw/pull/30997){:target="_blank"}  from **@bsunanda**: Run4-hgx257 Utilize mode access methods in validation code `dqm`  created: 2020-07-31 00:14:04 merged: 2020-07-31 10:15:37



106. [30996](http://github.com/cms-sw/cmssw/pull/30996){:target="_blank"}  from **@bsunanda**: Phase2-hgx257 Fix the error in workflow 29034.0 `geometry`  `upgrade`  created: 2020-07-30 23:09:42 merged: 2020-08-03 07:07:56



107. [30995](http://github.com/cms-sw/cmssw/pull/30995){:target="_blank"}  from **@Dr15Jones**: Modernize modules in SUSYBSMAnalysis/HSCP `analysis`  created: 2020-07-30 21:51:50 merged: 2020-08-07 12:08:09



108. [30994](http://github.com/cms-sw/cmssw/pull/30994){:target="_blank"}  from **@Dr15Jones**: Made AlignmentMuonSelectorModule a stream module `alca`  `reconstruction`  created: 2020-07-30 20:55:59 merged: 2020-08-03 08:09:07



109. [30992](http://github.com/cms-sw/cmssw/pull/30992){:target="_blank"}  from **@guitargeek**: phase-2 reco CPU hotspot: PFElecTkProducer `reconstruction`  created: 2020-07-30 20:02:32 merged: 2020-08-05 07:48:07



110. [30991](http://github.com/cms-sw/cmssw/pull/30991){:target="_blank"}  from **@Dr15Jones**: Made CandidateTriggerObjectProducer a stream module `analysis`  `reconstruction`  created: 2020-07-30 19:04:02 merged: 2020-08-04 17:25:40



111. [30989](http://github.com/cms-sw/cmssw/pull/30989){:target="_blank"}  from **@AdrianoDee**: Moving to Digi Geometry for L1 Hitless Seeding `reconstruction`  created: 2020-07-30 18:36:04 merged: 2020-08-03 16:37:43



112. [30988](http://github.com/cms-sw/cmssw/pull/30988){:target="_blank"}  from **@kpedro88**: Shorten upgrade workflow names, reorganize premixing workflow setup and add to PR tests for phase 2 `operations`  `pdmv`  `upgrade`  created: 2020-07-30 18:20:11 merged: 2020-08-04 19:33:05



113. [30987](http://github.com/cms-sw/cmssw/pull/30987){:target="_blank"}  from **@Dr15Jones**: Modernized HLTMuonPointingFilter `hlt`  created: 2020-07-30 18:01:40 merged: 2020-08-03 08:02:05



114. [30985](http://github.com/cms-sw/cmssw/pull/30985){:target="_blank"}  from **@Dr15Jones**: modernized modules in Calibration/EcalAlCaRecoProducers `alca`  created: 2020-07-30 16:44:46 merged: 2020-08-03 07:55:59



115. [30984](http://github.com/cms-sw/cmssw/pull/30984){:target="_blank"}  from **@christopheralanwest**: Update HLT jet energy corrections in offline data GTs `alca`  created: 2020-07-30 16:34:31 merged: 2020-07-31 13:42:59



116. [30983](http://github.com/cms-sw/cmssw/pull/30983){:target="_blank"}  from **@Dr15Jones**: Modernize modules in  Calibration/HcalAlCaRecoProducers `alca`  created: 2020-07-30 16:22:03 merged: 2020-08-04 08:04:00



117. [30978](http://github.com/cms-sw/cmssw/pull/30978){:target="_blank"}  from **@cerminar**: Fix L1T Phase2 EG scale `l1`  `upgrade`  created: 2020-07-30 13:24:17 merged: 2020-07-31 07:29:01



118. [30977](http://github.com/cms-sw/cmssw/pull/30977){:target="_blank"}  from **@civanch**: GFlash updated `simulation`  created: 2020-07-30 11:13:34 merged: 2020-07-30 20:08:45



119. [30976](http://github.com/cms-sw/cmssw/pull/30976){:target="_blank"}  from **@ghugo83**: Add Phase 2 Trackers T21 + T22 + T23 (Mechanical Update in Outer Tracker + Sensors studies in Inner Tracker) `alca`  `geometry`  `l1`  `operations`  `pdmv`  `upgrade`  created: 2020-07-30 09:11:49 merged: 2020-08-06 19:03:18



120. [30975](http://github.com/cms-sw/cmssw/pull/30975){:target="_blank"}  from **@gsorrentino18**: Validation of MTD BTL RecHit Longitudinal Position `dqm`  created: 2020-07-30 08:06:01 merged: 2020-07-30 20:11:01



121. [30974](http://github.com/cms-sw/cmssw/pull/30974){:target="_blank"}  from **@amkalsi**: MET filter fix for nanoAOD step in extraflags_cff file i.e. addition of slimmedOfflinePrimaryVertices input tag (follow up of PR 30015) `analysis`  `xpog`  created: 2020-07-30 02:58:47 merged: 2020-07-30 07:55:17



122. [30972](http://github.com/cms-sw/cmssw/pull/30972){:target="_blank"}  from **@Sam-Harper**: HLT TDR event content refinements: 11_2_X `hlt`  created: 2020-07-29 21:32:10 merged: 2020-07-30 08:38:43



123. [30971](http://github.com/cms-sw/cmssw/pull/30971){:target="_blank"}  from **@bsunanda**: Run3-gem45 Make GEM geometry tp be built from either DDD or DD4Hep `geometry`  `upgrade`  created: 2020-07-29 20:50:44 merged: 2020-08-03 07:48:10



124. [30970](http://github.com/cms-sw/cmssw/pull/30970){:target="_blank"}  from **@kpedro88**: Clean up L1TTrackMatch producers `l1`  `upgrade`  created: 2020-07-29 20:11:47 merged: 2020-08-03 07:05:21



125. [30967](http://github.com/cms-sw/cmssw/pull/30967){:target="_blank"}  from **@camolezi**: Moving boost dependency to c++ stl alternatives in CommonTools/Utils `analysis`  `reconstruction`  created: 2020-07-29 18:30:55 merged: 2020-08-04 17:12:05



126. [30966](http://github.com/cms-sw/cmssw/pull/30966){:target="_blank"}  from **@JamminJones**: added esConsumes to modules in RecoTracker/TrackProducer `reconstruction`  created: 2020-07-29 17:43:18 merged: 2020-07-30 15:36:45



127. [30965](http://github.com/cms-sw/cmssw/pull/30965){:target="_blank"}  from **@MilanoBicocca-pix**: Online BeamSpot ESProducer for Run3 workflow `alca`  `db`  `reconstruction`  created: 2020-07-29 17:18:02 merged: 2020-08-05 08:39:46



128. [30963](http://github.com/cms-sw/cmssw/pull/30963){:target="_blank"}  from **@ianna**: [DD4hep] Reorder XML Files in 2026 Scenarios `geometry`  `upgrade`  created: 2020-07-29 15:49:46 merged: 2020-07-30 15:28:39



129. [30962](http://github.com/cms-sw/cmssw/pull/30962){:target="_blank"}  from **@JamminJones**: added esConsumes to modules in RecoEgamma/ElectronIdentification `reconstruction`  created: 2020-07-29 15:45:17 merged: 2020-07-30 13:16:55



130. [30961](http://github.com/cms-sw/cmssw/pull/30961){:target="_blank"}  from **@smuzaffar**: plugin cache fix: initialize with file_time_type::min `core`  created: 2020-07-29 13:09:18 merged: 2020-07-30 08:29:55



131. [30960](http://github.com/cms-sw/cmssw/pull/30960){:target="_blank"}  from **@davidlange6**: add missing dependencies to DataFormats/TrackReco `reconstruction`  created: 2020-07-29 12:18:48 merged: 2020-07-30 15:30:39



132. [30951](http://github.com/cms-sw/cmssw/pull/30951){:target="_blank"}  from **@igv4321**: Add packed TDC information to HBHERecHit `reconstruction`  created: 2020-07-28 21:05:22 merged: 2020-08-03 16:54:42



133. [30950](http://github.com/cms-sw/cmssw/pull/30950){:target="_blank"}  from **@Dr15Jones**: Added allowedValues for ParameterSetDescription `core`  created: 2020-07-28 20:17:32 merged: 2020-07-30 08:29:11



134. [30948](http://github.com/cms-sw/cmssw/pull/30948){:target="_blank"}  from **@vgvassilev**: Remove redundant include. `reconstruction`  created: 2020-07-28 19:41:04 merged: 2020-07-29 07:31:51



135. [30947](http://github.com/cms-sw/cmssw/pull/30947){:target="_blank"}  from **@jeongeun**: drop type specs in RecoTracker `reconstruction`  created: 2020-07-28 19:33:21 merged: 2020-08-17 15:00:26



136. [30946](http://github.com/cms-sw/cmssw/pull/30946){:target="_blank"}  from **@mrodozov**: Remove redundant (?) files from SimG4CMS/Forward/data `simulation`  created: 2020-07-28 19:24:17 merged: 2020-07-30 08:23:40



137. [30944](http://github.com/cms-sw/cmssw/pull/30944){:target="_blank"}  from **@JamminJones**: added esConsumes to modules in RecoEgamma/EgammaIsolationAlgos `reconstruction`  created: 2020-07-28 17:04:15 merged: 2020-07-29 07:33:12



138. [30943](http://github.com/cms-sw/cmssw/pull/30943){:target="_blank"}  from **@MilanoBicocca-pix**: Fix lastLumiFile parameter in fake BeamSpot clients `dqm`  created: 2020-07-28 15:57:46 merged: 2020-07-28 22:21:50



139. [30942](http://github.com/cms-sw/cmssw/pull/30942){:target="_blank"}  from **@guitargeek**: Clean BuildFiles in ALCA `alca`  created: 2020-07-28 15:26:19 merged: 2020-08-03 07:26:59



140. [30941](http://github.com/cms-sw/cmssw/pull/30941){:target="_blank"}  from **@JamminJones**: added esConsumes to modules in EventFilter/EcalRawToDigi `reconstruction`  created: 2020-07-28 15:12:11 merged: 2020-07-29 07:35:09



141. [30938](http://github.com/cms-sw/cmssw/pull/30938){:target="_blank"}  from **@camolezi**: Migrate to c++17 filesystem in FWCore/Utilities `core`  created: 2020-07-28 14:05:47 merged: 2020-07-29 07:50:38



142. [30936](http://github.com/cms-sw/cmssw/pull/30936){:target="_blank"}  from **@hatakeyamak**: PFProducer fix for PFMuonAlgo's fillPSetDescription `hlt`  `reconstruction`  created: 2020-07-28 12:31:13 merged: 2020-08-04 14:20:25



143. [30934](http://github.com/cms-sw/cmssw/pull/30934){:target="_blank"}  from **@mandrenguyen**: add centrality bin to HI miniAOD `analysis`  `reconstruction`  created: 2020-07-28 08:52:36 merged: 2020-08-04 17:06:01



144. [30928](http://github.com/cms-sw/cmssw/pull/30928){:target="_blank"}  from **@Dr15Jones**: Throw if dereference an unset edm::Handle `core`  created: 2020-07-27 17:57:32 merged: 2020-08-06 19:16:59



145. [30924](http://github.com/cms-sw/cmssw/pull/30924){:target="_blank"}  from **@mmusich**: Add DB utilties for SiPixelVCal `alca`  `db`  created: 2020-07-27 14:28:59 merged: 2020-08-03 07:25:26



146. [30909](http://github.com/cms-sw/cmssw/pull/30909){:target="_blank"}  from **@dildick**: Fix broken LCTs reported in HLT_L1SingleMu25 [11_2_X] `l1`  `simulation`  created: 2020-07-24 22:50:02 merged: 2020-07-31 18:53:27



147. [30906](http://github.com/cms-sw/cmssw/pull/30906){:target="_blank"}  from **@makortel**: Refactor parts of the thinning code `core`  created: 2020-07-24 21:05:52 merged: 2020-08-07 08:07:06



148. [30891](http://github.com/cms-sw/cmssw/pull/30891){:target="_blank"}  from **@bsunanda**: Run4-hgx256 Make scenario/workflow for V14 HGCal `geometry`  `operations`  `pdmv`  `upgrade`  created: 2020-07-24 00:53:25 merged: 2020-07-29 10:42:43



149. [30889](http://github.com/cms-sw/cmssw/pull/30889){:target="_blank"}  from **@schneiml**: DQM: Optimize DQMIO memory use `dqm`  created: 2020-07-23 17:00:17 merged: 2020-07-30 08:22:13



150. [30883](http://github.com/cms-sw/cmssw/pull/30883){:target="_blank"}  from **@PFCal-dev**: [HGCAL trigger] Updated trigger towers (+minor updates) `l1`  `upgrade`  created: 2020-07-23 12:59:56 merged: 2020-08-07 08:44:42



151. [30867](http://github.com/cms-sw/cmssw/pull/30867){:target="_blank"}  from **@adas1994**: Memory efficient implementation of timing information for HGCDigitizer module for Premix Workflow. `simulation`  `upgrade`  created: 2020-07-21 21:25:31 merged: 2020-08-06 08:22:10



152. [30866](http://github.com/cms-sw/cmssw/pull/30866){:target="_blank"}  from **@guitargeek**: Clean BuildFiles in GeneratorInterface `generators`  created: 2020-07-21 20:57:58 merged: 2020-08-05 09:46:21



153. [30857](http://github.com/cms-sw/cmssw/pull/30857){:target="_blank"}  from **@fwyzard**: Migrate DQM from boost::format to {fmt} `dqm`  `hlt`  created: 2020-07-21 17:36:09 merged: 2020-08-05 07:43:01



154. [30855](http://github.com/cms-sw/cmssw/pull/30855){:target="_blank"}  from **@fwyzard**: Migrate EventFilter from boost::format to {fmt} `reconstruction`  created: 2020-07-21 17:34:33 merged: 2020-07-30 08:12:13



155. [30811](http://github.com/cms-sw/cmssw/pull/30811){:target="_blank"}  from **@camolezi**: Move DQMServices/StreamerIO to std::filesystem `dqm`  created: 2020-07-17 18:07:19 merged: 2020-07-30 08:08:29



156. [30748](http://github.com/cms-sw/cmssw/pull/30748){:target="_blank"}  from **@davidlange6**: remove ROOTCLING ifdefs that are no longer needed (were never?)  `analysis`  `core`  `reconstruction`  created: 2020-07-16 11:33:46 merged: 2020-07-30 08:05:54



157. [30698](http://github.com/cms-sw/cmssw/pull/30698){:target="_blank"}  from **@schneiml**: DQM: Use ProcessBlock in Harvesting `alca`  `dqm`  created: 2020-07-15 11:58:31 merged: 2020-08-06 08:08:11



158. [30674](http://github.com/cms-sw/cmssw/pull/30674){:target="_blank"}  from **@nurfikri89**: Major updates for Custom JME NanoAODs `analysis`  `reconstruction`  `xpog`  created: 2020-07-14 10:11:17 merged: 2020-08-06 19:10:16



159. [30667](http://github.com/cms-sw/cmssw/pull/30667){:target="_blank"}  from **@cms-sw**: cmsRun: By default use jemalloc for non-x86_64 archs too `core`  created: 2020-07-13 20:00:46 merged: 2020-08-03 07:14:46



160. [30665](http://github.com/cms-sw/cmssw/pull/30665){:target="_blank"}  from **@mrodozov**: Clang tidy checks - add new checks to .clang-tidy `core`  created: 2020-07-13 18:28:23 merged: 2020-08-04 15:53:03



161. [30457](http://github.com/cms-sw/cmssw/pull/30457){:target="_blank"}  from **@smorovic**: TCDS multi-fed support in DAQ and unpacker `daq`  `reconstruction`  created: 2020-06-29 16:39:16 merged: 2020-08-14 12:57:15



162. [30291](http://github.com/cms-sw/cmssw/pull/30291){:target="_blank"}  from **@yongbinfeng**: Add DeepMET into NanoAOD `analysis`  `reconstruction`  `xpog`  created: 2020-06-18 14:49:13 merged: 2020-08-04 14:32:54



#### CMSDIST Changes between Tags REL/CMSSW_11_2_0_pre3/slc7_amd64_gcc820 and REL/CMSSW_11_2_0_pre4/slc7_amd64_gcc820:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_11_2_0_pre3/slc7_amd64_gcc820...REL/CMSSW_11_2_0_pre4/slc7_amd64_gcc820)



1. [6181](http://github.com/cms-sw/cmsdist/pull/6181){:target="_blank"}  from **@cms-sw**: [DD4Hep] Add additional flag to bring missing functions created: 2020-08-19 09:56:37 merged: 2020-08-21 08:51:10

2. [6180](http://github.com/cms-sw/cmsdist/pull/6180){:target="_blank"}  from **@cms-sw**: Update tag for RecoEgamma-ElectronIdentification to V01-02-00 created: 2020-08-18 21:09:37 merged: 2020-08-18 21:11:44

3. [6179](http://github.com/cms-sw/cmsdist/pull/6179){:target="_blank"}  from **@belforte**: Test latest CRAB Client tag created: 2020-08-18 15:31:53 merged: 2020-08-19 20:54:20

4. [6177](http://github.com/cms-sw/cmsdist/pull/6177){:target="_blank"}  from **@cms-sw**: Update xrootd to 4.12.3 created: 2020-08-18 00:14:14 merged: 2020-08-18 20:15:36

5. [6176](http://github.com/cms-sw/cmsdist/pull/6176){:target="_blank"}  from **@davidlange6**: update some pip packages to most recent release available created: 2020-08-17 14:42:55 merged: 2020-08-21 10:47:32

6. [6173](http://github.com/cms-sw/cmsdist/pull/6173){:target="_blank"}  from **@mrodozov**: [ROOT] Update root 6-20  created: 2020-08-17 09:33:16 merged: 2020-08-18 20:04:44

7. [6170](http://github.com/cms-sw/cmsdist/pull/6170){:target="_blank"}  from **@belforte**: move forward to 0812 tag to fix httplib import created: 2020-08-15 13:05:38 merged: 2020-08-15 17:39:52

8. [6169](http://github.com/cms-sw/cmsdist/pull/6169){:target="_blank"}  from **@cms-sw**: Bump davix to 076 created: 2020-08-13 15:28:21 merged: 2020-08-13 23:07:57

9. [6168](http://github.com/cms-sw/cmsdist/pull/6168){:target="_blank"}  from **@belforte**: incorportate latest fixes,in particular the one for missing py2-future created: 2020-08-11 22:33:31 merged: 2020-08-12 10:28:11

10. [6167](http://github.com/cms-sw/cmsdist/pull/6167){:target="_blank"}  from **@belforte**: roll back to PREvious CRAB client version. created: 2020-08-11 22:05:14 merged: 2020-08-12 10:28:46

11. [6166](http://github.com/cms-sw/cmsdist/pull/6166){:target="_blank"}  from **@cms-sw**: Add py2-opt-einsum to python_tools created: 2020-08-11 19:12:13 merged: 2020-08-11 20:37:43

12. [6165](http://github.com/cms-sw/cmsdist/pull/6165){:target="_blank"}  from **@mrodozov**: [ROOT] Updated root to tip of branch v6-20-00-patches created: 2020-08-10 12:58:49 merged: 2020-08-11 20:14:19

13. [6162](http://github.com/cms-sw/cmsdist/pull/6162){:target="_blank"}  from **@belforte**: test latest crab client created: 2020-08-10 12:47:51 merged: 2020-08-12 18:27:04

14. [6161](http://github.com/cms-sw/cmsdist/pull/6161){:target="_blank"}  from **@fwyzard**: Update to CUDA 11.0 Update 1, and update the list of supported architectures created: 2020-08-08 16:54:05 merged: 2020-08-10 11:48:13

15. [6160](http://github.com/cms-sw/cmsdist/pull/6160){:target="_blank"}  from **@cms-sw**: HDF5 toolfile cleanup and added openmpi deps created: 2020-08-07 15:04:17 merged: 2020-08-08 07:15:00

16. [6158](http://github.com/cms-sw/cmsdist/pull/6158){:target="_blank"}  from **@gartung**: Update igprof.spec created: 2020-08-06 21:59:55 merged: 2020-08-07 15:05:53

17. [6157](http://github.com/cms-sw/cmsdist/pull/6157){:target="_blank"}  from **@cms-sw**: Update cmssw-osenv.spec created: 2020-08-06 21:41:12 merged: 2020-08-06 21:41:34

18. [6156](http://github.com/cms-sw/cmsdist/pull/6156){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-06-00 created: 2020-08-06 19:24:38 merged: 2020-08-06 19:26:42

19. [6155](http://github.com/cms-sw/cmsdist/pull/6155){:target="_blank"}  from **@cms-sw**: update scram: avoid recursively changes version between v2 and v3 created: 2020-08-06 17:34:08 merged: 2020-08-06 21:25:15

20. [6154](http://github.com/cms-sw/cmsdist/pull/6154){:target="_blank"}  from **@cms-sw**: Update cms-common.spec created: 2020-08-06 16:57:10 merged: 2020-08-06 17:06:32

21. [6150](http://github.com/cms-sw/cmsdist/pull/6150){:target="_blank"}  from **@cms-sw**: Update tag for L1Trigger-TrackFindingTMTT to V00-02-00 created: 2020-08-05 10:10:49 merged: 2020-08-05 10:13:00

22. [6149](http://github.com/cms-sw/cmsdist/pull/6149){:target="_blank"}  from **@cms-sw**: update cms common revision to 1210 created: 2020-08-05 09:32:12 merged: 2020-08-05 15:38:58

23. [6148](http://github.com/cms-sw/cmsdist/pull/6148){:target="_blank"}  from **@cms-sw**: Update DD4Hep to latest on master created: 2020-08-05 09:18:48 merged: 2020-08-11 19:23:33

24. [6147](http://github.com/cms-sw/cmsdist/pull/6147){:target="_blank"}  from **@mrodozov**: Update openmpi to 4.0.4 created: 2020-08-05 09:13:11 merged: 2020-08-06 15:33:56

25. [6146](http://github.com/cms-sw/cmsdist/pull/6146){:target="_blank"}  from **@belforte**: move latest CrabClient to production and test new build in dev created: 2020-08-04 16:25:35 merged: 2020-08-05 07:41:08

26. [6144](http://github.com/cms-sw/cmsdist/pull/6144){:target="_blank"}  from **@mrodozov**: [LLVM] Remove static libs created: 2020-08-04 14:34:51 merged: 2020-08-05 15:39:36

27. [6141](http://github.com/cms-sw/cmsdist/pull/6141){:target="_blank"}  from **@mrodozov**: [ROOT] v6-20-00-patches created: 2020-08-04 09:31:17 merged: 2020-08-04 18:04:05

28. [6138](http://github.com/cms-sw/cmsdist/pull/6138){:target="_blank"}  from **@cms-sw**:  vulnerabilities found in existing pillow version created: 2020-08-03 16:26:25 merged: 2020-08-04 12:33:25

29. [6136](http://github.com/cms-sw/cmsdist/pull/6136){:target="_blank"}  from **@cms-sw**: New buildrules which should work with SCRAM V2 and V3 created: 2020-08-03 15:38:01 merged: 2020-08-04 06:24:14

30. [6134](http://github.com/cms-sw/cmsdist/pull/6134){:target="_blank"}  from **@cms-sw**: SCRAM: use correct basedirectory to switch scram versions created: 2020-08-03 09:37:44 merged: 2020-08-03 13:36:23

31. [6129](http://github.com/cms-sw/cmsdist/pull/6129){:target="_blank"}  from **@gartung**: Add check to see that cms-handle code-formatter is linked into clang-tidy and run the unit tests on clang-tools-extra. created: 2020-07-30 19:19:13 merged: 2020-08-04 14:51:48

32. [6128](http://github.com/cms-sw/cmsdist/pull/6128){:target="_blank"}  from **@cms-sw**: Parallel support for HDF5 created: 2020-07-30 17:20:25 merged: 2020-08-04 14:49:04

33. [6125](http://github.com/cms-sw/cmsdist/pull/6125){:target="_blank"}  from **@cms-sw**: buildrules: another perl script converted to shell created: 2020-07-30 12:37:46 merged: 2020-08-03 13:36:00

34. [6124](http://github.com/cms-sw/cmsdist/pull/6124){:target="_blank"}  from **@cms-sw**: keep only CastorShowerLibrary_CMSSW500_Standard library created: 2020-07-30 10:11:18 merged: 2020-08-03 07:44:56

35. [6121](http://github.com/cms-sw/cmsdist/pull/6121){:target="_blank"}  from **@cms-sw**: use findDependencies.pl for SCRAM V2 based Ibs created: 2020-07-29 13:46:10 merged: 2020-07-29 18:39:16

36. [6120](http://github.com/cms-sw/cmsdist/pull/6120){:target="_blank"}  from **@fwyzard**: Update to CUDA 11.0.2 (11.0.207) created: 2020-07-28 15:58:35 merged: 2020-08-06 18:46:02

37. [6119](http://github.com/cms-sw/cmsdist/pull/6119){:target="_blank"}  from **@cms-sw**: Add awkward1 and uproot4 to python tools created: 2020-07-28 15:57:58 merged: 2020-08-12 12:10:14

38. [6118](http://github.com/cms-sw/cmsdist/pull/6118){:target="_blank"}  from **@mrodozov**: Remove codechecker external created: 2020-07-28 15:00:02 merged: 2020-07-30 08:30:14

39. [6108](http://github.com/cms-sw/cmsdist/pull/6108){:target="_blank"}  from **@davidlange6**: bumping versions of python(2) tools created: 2020-07-23 11:22:35 merged: 2020-07-30 10:56:00
