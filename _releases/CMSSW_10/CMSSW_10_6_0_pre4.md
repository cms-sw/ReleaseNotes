---
layout: post
rel_link:  "10_6_0_pre4"
title:  "CMSSW_10_6_0_pre4"
date:   2019-04-19 20:03:16
categories: cmssw
relmajor: 10
relminor: 6
relsubminor: 0
relpre: _pre4
---

# CMSSW_10_6_0_pre4
#### Changes since CMSSW_10_6_0_pre3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_10_6_0_pre3...CMSSW_10_6_0_pre4)



1. [26484](http://github.com/cms-sw/cmssw/pull/26484){:target="_blank"}  from **@mmusich**: fixing getPayloadData.py script to be able to compile `db`  created: 2019-04-17 16:51:57 merged: 2019-04-18 08:38:44



2. [26477](http://github.com/cms-sw/cmssw/pull/26477){:target="_blank"}  from **@fabiocos**: Add to short matrix upgrade scenario D41 (baseline for L1T TDR) `pdmv`  `upgrade`  created: 2019-04-17 08:47:55 merged: 2019-04-17 20:25:45



3. [26475](http://github.com/cms-sw/cmssw/pull/26475){:target="_blank"}  from **@davidlange6**: remove deepdish from list of things to test in imports unit test `analysis`  created: 2019-04-17 07:20:29 merged: 2019-04-17 20:22:10



4. [26470](http://github.com/cms-sw/cmssw/pull/26470){:target="_blank"}  from **@felicepantaleo**: [HGCal] Fix thread safety issue in layer clustering density map filling `reconstruction`  `upgrade`  created: 2019-04-16 17:06:13 merged: 2019-04-17 20:51:06



5. [26461](http://github.com/cms-sw/cmssw/pull/26461){:target="_blank"}  from **@apana**: Add trigger bit to emulated GlobalExtBlk to indicate event was not selected  `l1`  `operations`  created: 2019-04-15 17:26:56 merged: 2019-04-18 08:15:18



6. [26459](http://github.com/cms-sw/cmssw/pull/26459){:target="_blank"}  from **@drkovalskyi**: [muon] updated multiIso working points `analysis`  `reconstruction`  created: 2019-04-15 09:56:36 merged: 2019-04-17 07:55:20



7. [26456](http://github.com/cms-sw/cmssw/pull/26456){:target="_blank"}  from **@davidlange6**: python test updates for new sklearn version -  `analysis`  created: 2019-04-15 08:38:47 merged: 2019-04-16 08:19:19



8. [26455](http://github.com/cms-sw/cmssw/pull/26455){:target="_blank"}  from **@PFCal-dev**: [HGCAL trigger] Apply code-format `l1`  `upgrade`  created: 2019-04-15 08:06:09 merged: 2019-04-17 07:43:19



9. [26451](http://github.com/cms-sw/cmssw/pull/26451){:target="_blank"}  from **@bsunanda**: Run2-alca154 Source code reformatting with clang-format in Calibration/HcalCalibAlgos `alca`  created: 2019-04-13 02:11:56 merged: 2019-04-17 07:41:54



10. [26450](http://github.com/cms-sw/cmssw/pull/26450){:target="_blank"}  from **@bsunanda**: Run2-alca155 Source code reformatting with clang-format in Calibration/HcalAlCaRecoProducers `alca`  created: 2019-04-13 02:10:12 merged: 2019-04-17 07:39:23



11. [26447](http://github.com/cms-sw/cmssw/pull/26447){:target="_blank"}  from **@bsunanda**: Run3-sim32 Clean up the prints and make it conform clang `simulation`  created: 2019-04-12 14:11:40 merged: 2019-04-14 17:26:31



12. [26443](http://github.com/cms-sw/cmssw/pull/26443){:target="_blank"}  from **@davidlange6**: more iteritems and integer division cleanups (python3 unit tests) `dqm`  `reconstruction`  created: 2019-04-12 08:37:28 merged: 2019-04-15 20:43:58



13. [26442](http://github.com/cms-sw/cmssw/pull/26442){:target="_blank"}  from **@bsunanda**: Run2-TB35 Update the packages for code format an correct TB geometry for scenario 1 of Oct 18 HGCal TB `geometry`  `simulation`  `upgrade`  created: 2019-04-11 17:58:46 merged: 2019-04-18 08:31:34



14. [26436](http://github.com/cms-sw/cmssw/pull/26436){:target="_blank"}  from **@perrotta**: Fix include for HFStripFilter `reconstruction`  created: 2019-04-11 13:08:09 merged: 2019-04-12 08:09:35



15. [26435](http://github.com/cms-sw/cmssw/pull/26435){:target="_blank"}  from **@forthommel**: Correction of static check include path for edm::isNotFinite `core`  created: 2019-04-11 08:29:07 merged: 2019-04-11 20:24:45



16. [26434](http://github.com/cms-sw/cmssw/pull/26434){:target="_blank"}  from **@davidlange6**: Python3 syntax error cleanup `alca`  `core`  `reconstruction`  created: 2019-04-11 06:52:27 merged: 2019-04-11 20:23:31



17. [26432](http://github.com/cms-sw/cmssw/pull/26432){:target="_blank"}  from **@abdoulline**: HCAL: adding Phase 1 HBX/HEX channels to CalibDetId and ASCII conditions processing  `alca`  `simulation`  created: 2019-04-11 04:35:21 merged: 2019-04-17 20:18:46



18. [26430](http://github.com/cms-sw/cmssw/pull/26430){:target="_blank"}  from **@arossi83**: Added Residuals plots and fix monitoring plots for Pixel ClusterRepairs `alca`  `dqm`  created: 2019-04-10 23:38:01 merged: 2019-04-12 08:16:37



19. [26429](http://github.com/cms-sw/cmssw/pull/26429){:target="_blank"}  from **@fabiocos**: Fix clang warnings in FastSimulation/SimplifiedGeometryPropagator `fastsim`  created: 2019-04-10 16:35:54 merged: 2019-04-12 17:26:58



20. [26428](http://github.com/cms-sw/cmssw/pull/26428){:target="_blank"}  from **@fabiocos**: Remove unused variable in Geometry/MTDNumberingBuilder  `geometry`  `upgrade`  created: 2019-04-10 15:33:47 merged: 2019-04-11 14:25:05



21. [26427](http://github.com/cms-sw/cmssw/pull/26427){:target="_blank"}  from **@davidlange6**: add bool method to cms.Bool `core`  created: 2019-04-10 13:37:14 merged: 2019-04-10 20:18:09



22. [26426](http://github.com/cms-sw/cmssw/pull/26426){:target="_blank"}  from **@Dr15Jones**: Allow return value optimization in getAnyPtr `core`  created: 2019-04-10 13:36:50 merged: 2019-04-10 20:16:16



23. [26425](http://github.com/cms-sw/cmssw/pull/26425){:target="_blank"}  from **@smorovic**: DAQ multi-LS output module (10_6_X) `core`  `daq`  `reconstruction`  created: 2019-04-10 13:07:06 merged: 2019-04-17 07:33:34



24. [26424](http://github.com/cms-sw/cmssw/pull/26424){:target="_blank"}  from **@davidlange6**: xrange migration to L1 and egammaanalysis `analysis`  `l1`  `upgrade`  created: 2019-04-10 12:47:27 merged: 2019-04-12 08:19:10



25. [26421](http://github.com/cms-sw/cmssw/pull/26421){:target="_blank"}  from **@davidlange6**: replace map in python by list `dqm`  `simulation`  created: 2019-04-10 11:39:29 merged: 2019-04-11 20:22:47



26. [26420](http://github.com/cms-sw/cmssw/pull/26420){:target="_blank"}  from **@Sam-Harper**: adding fixedGridRhoFastjetAllTmp to MiniAOD event content `analysis`  `reconstruction`  `xpog`  created: 2019-04-10 11:14:08 merged: 2019-04-14 17:03:24



27. [26418](http://github.com/cms-sw/cmssw/pull/26418){:target="_blank"}  from **@davidlange6**: migrate away from commands in das utility `core`  created: 2019-04-10 06:46:44 merged: 2019-04-10 20:10:57



28. [26417](http://github.com/cms-sw/cmssw/pull/26417){:target="_blank"}  from **@ahmad3213**: Data relvals 2018 ABC,2016 and 2017 relvals using Offline GTs now by  `pdmv`  `upgrade`  created: 2019-04-10 03:36:24 merged: 2019-04-11 20:19:42



29. [26415](http://github.com/cms-sw/cmssw/pull/26415){:target="_blank"}  from **@tocheng**: Update Data/MC GTs in 106X `alca`  created: 2019-04-09 23:24:43 merged: 2019-04-18 16:32:17



30. [26414](http://github.com/cms-sw/cmssw/pull/26414){:target="_blank"}  from **@davidlange6**: xrange migration for python3 `alca`  created: 2019-04-09 19:31:34 merged: 2019-04-10 17:22:25



31. [26412](http://github.com/cms-sw/cmssw/pull/26412){:target="_blank"}  from **@davidlange6**: xrange migration for python3 `core`  `dqm`  created: 2019-04-09 18:32:34 merged: 2019-04-11 20:22:29



32. [26411](http://github.com/cms-sw/cmssw/pull/26411){:target="_blank"}  from **@davidlange6**: xrange migration for python3 `alca`  `analysis`  `db`  `reconstruction`  `xpog`  created: 2019-04-09 18:28:06 merged: 2019-04-12 18:16:18



33. [26410](http://github.com/cms-sw/cmssw/pull/26410){:target="_blank"}  from **@davidlange6**: xrange migration in fwk packages for python3 `analysis`  `core`  `reconstruction`  created: 2019-04-09 18:01:47 merged: 2019-04-11 20:21:39



34. [26409](http://github.com/cms-sw/cmssw/pull/26409){:target="_blank"}  from **@Sam-Harper**: swapping order of cuts to avoid expensive dxy/dz calc `reconstruction`  created: 2019-04-09 17:54:20 merged: 2019-04-10 20:09:46



35. [26408](http://github.com/cms-sw/cmssw/pull/26408){:target="_blank"}  from **@davidlange6**: make ECALHCAL.py python3 compatible `dqm`  `simulation`  created: 2019-04-09 15:40:49 merged: 2019-04-10 20:09:20



36. [26407](http://github.com/cms-sw/cmssw/pull/26407){:target="_blank"}  from **@Dr15Jones**: Avoid ambiguous statement in dqmfilesaver::fillJson `dqm`  created: 2019-04-09 14:59:56 merged: 2019-04-10 12:24:03



37. [26403](http://github.com/cms-sw/cmssw/pull/26403){:target="_blank"}  from **@DryRun**: HCAL updates for phase 1 HB digis `reconstruction`  `simulation`  created: 2019-04-09 12:09:46 merged: 2019-04-11 20:21:10



38. [26397](http://github.com/cms-sw/cmssw/pull/26397){:target="_blank"}  from **@davidlange6**: add clang-format file to CMSSW `core`  created: 2019-04-09 10:21:53 merged: 2019-04-10 11:00:44



39. [26394](http://github.com/cms-sw/cmssw/pull/26394){:target="_blank"}  from **@CTPPS**: PPS: proton reco finalisation before UL re-reco `alca`  `reconstruction`  created: 2019-04-09 06:54:56 merged: 2019-04-17 20:49:40



40. [26393](http://github.com/cms-sw/cmssw/pull/26393){:target="_blank"}  from **@depasse**: ECAL : automatic Ecal Preshower Gain Switching in DB, by O2O `db`  created: 2019-04-09 06:20:39 merged: 2019-04-17 07:47:16



41. [26392](http://github.com/cms-sw/cmssw/pull/26392){:target="_blank"}  from **@Dr15Jones**: Explicitly cast values in array used in FWHeatmapProxyBuilderTemplate `visualization`  created: 2019-04-08 18:28:02 merged: 2019-04-09 08:26:57



42. [26391](http://github.com/cms-sw/cmssw/pull/26391){:target="_blank"}  from **@fioriNTU**: defining DQM auto config for rereco `dqm`  created: 2019-04-08 18:23:36 merged: 2019-04-09 08:22:51



43. [26390](http://github.com/cms-sw/cmssw/pull/26390){:target="_blank"}  from **@bsunanda**: Run2-alca153 Correct the calibration algos `alca`  created: 2019-04-08 17:08:23 merged: 2019-04-11 15:09:57



44. [26387](http://github.com/cms-sw/cmssw/pull/26387){:target="_blank"}  from **@Dr15Jones**: Removed unnecesary include from EcalLaserDbService `alca`  created: 2019-04-08 16:11:50 merged: 2019-04-09 08:25:03



45. [26386](http://github.com/cms-sw/cmssw/pull/26386){:target="_blank"}  from **@ianna**: DD4hep: add an algorithm needed to build MTD geometry `geometry`  `upgrade`  created: 2019-04-08 14:35:08 merged: 2019-04-10 08:02:14



46. [26384](http://github.com/cms-sw/cmssw/pull/26384){:target="_blank"}  from **@apsallid**: [HGCal] Material budget for V10 geometry scenario `dqm`  `geometry`  created: 2019-04-08 13:51:34 merged: 2019-04-17 07:26:51



47. [26382](http://github.com/cms-sw/cmssw/pull/26382){:target="_blank"}  from **@toropin**: New slopes for S9S1filter `reconstruction`  created: 2019-04-08 08:23:26 merged: 2019-04-09 20:42:41



48. [26381](http://github.com/cms-sw/cmssw/pull/26381){:target="_blank"}  from **@Dr15Jones**: Avoid null reference in getTrackFromChargedHadron `reconstruction`  created: 2019-04-08 01:28:04 merged: 2019-04-08 20:06:14



49. [26377](http://github.com/cms-sw/cmssw/pull/26377){:target="_blank"}  from **@davidlange6**: Replace boost_python parameterset reader with a python3 version `core`  `visualization`  created: 2019-04-06 17:13:00 merged: 2019-04-08 07:52:01



50. [26376](http://github.com/cms-sw/cmssw/pull/26376){:target="_blank"}  from **@fabiocos**: DummyLHEAnalyzer: add option not to print event  `generators`  created: 2019-04-06 16:58:32 merged: 2019-04-07 20:24:02



51. [26375](http://github.com/cms-sw/cmssw/pull/26375){:target="_blank"}  from **@deguio**: Avoid conflict between HE and HGC in phase2 geometry when running an aged scenario `simulation`  `upgrade`  created: 2019-04-06 14:28:53 merged: 2019-04-06 21:29:17



52. [26372](http://github.com/cms-sw/cmssw/pull/26372){:target="_blank"}  from **@cms-tau-pog**: fix fillDescr config of PFRecoTauChargedHadronProducer `reconstruction`  created: 2019-04-05 15:07:40 merged: 2019-04-06 21:27:52



53. [26371](http://github.com/cms-sw/cmssw/pull/26371){:target="_blank"}  from **@ianna**: DD4hep: MTD Geometry Description `geometry`  `upgrade`  created: 2019-04-05 13:29:41 merged: 2019-04-09 07:36:10



54. [26369](http://github.com/cms-sw/cmssw/pull/26369){:target="_blank"}  from **@battibass**: Adding digi-based shower tagging to reco::Muon `analysis`  `reconstruction`  `simulation`  created: 2019-04-05 12:43:35 merged: 2019-04-18 16:34:07



55. [26368](http://github.com/cms-sw/cmssw/pull/26368){:target="_blank"}  from **@davidlange6**: python3 compatibility in PhysicsTools pieces of reco sequence `analysis`  `reconstruction`  created: 2019-04-05 12:15:16 merged: 2019-04-08 19:56:46



56. [26367](http://github.com/cms-sw/cmssw/pull/26367){:target="_blank"}  from **@davidlange6**:  python3 compatibility in FWCore/ParameterSet `core`  created: 2019-04-05 12:11:49 merged: 2019-04-07 20:14:55



57. [26366](http://github.com/cms-sw/cmssw/pull/26366){:target="_blank"}  from **@Dr15Jones**: Removed unused variable from SiPixelFedFillerWordEventNumber `alca`  created: 2019-04-05 08:32:47 merged: 2019-04-06 07:36:04



58. [26365](http://github.com/cms-sw/cmssw/pull/26365){:target="_blank"}  from **@srimanob**: add standard prod-like 2018 relvals w/ and w/o b-parking `pdmv`  `upgrade`  created: 2019-04-04 22:34:34 merged: 2019-04-09 20:40:26



59. [26364](http://github.com/cms-sw/cmssw/pull/26364){:target="_blank"}  from **@davidlange6**: use python3 compatible syntax in DQMOffline packages `dqm`  `l1`  created: 2019-04-04 19:22:33 merged: 2019-04-07 20:11:21



60. [26357](http://github.com/cms-sw/cmssw/pull/26357){:target="_blank"}  from **@davidlange6**: remove incorrect dependencies on boost_python and an obsolete build file `analysis`  `db`  `hlt`  `reconstruction`  created: 2019-04-04 13:31:46 merged: 2019-04-09 20:39:09



61. [26356](http://github.com/cms-sw/cmssw/pull/26356){:target="_blank"}  from **@davidlange6**: Remove FWCore/PythonParameterSet dependencies from unit tests in FWCore/Integration `core`  created: 2019-04-04 12:45:24 merged: 2019-04-05 07:35:04



62. [26355](http://github.com/cms-sw/cmssw/pull/26355){:target="_blank"}  from **@davidwalter2**: Updates on DQMOffline ZCounting for ultra legacy reco `dqm`  `operations`  created: 2019-04-04 11:40:31 merged: 2019-04-14 17:01:12



63. [26354](http://github.com/cms-sw/cmssw/pull/26354){:target="_blank"}  from **@apsallid**: [HGCal]  dEdx weights and thickness correction factors for V10 (D41) `reconstruction`  `upgrade`  created: 2019-04-04 10:52:53 merged: 2019-04-12 08:28:36



64. [26353](http://github.com/cms-sw/cmssw/pull/26353){:target="_blank"}  from **@davidlange6**: move PythonFramework to PyDevParameterSet `core`  created: 2019-04-04 10:16:45 merged: 2019-04-04 19:21:17



65. [26352](http://github.com/cms-sw/cmssw/pull/26352){:target="_blank"}  from **@ianna**: DD4hep: Merge Geometry Event Setup Records `geometry`  created: 2019-04-04 09:47:40 merged: 2019-04-09 07:29:36



66. [26351](http://github.com/cms-sw/cmssw/pull/26351){:target="_blank"}  from **@bsunanda**: Run2-hcx194 Changes to some of the algorithms used for TB application by removing explicit reference to CLHEP `geometry`  `simulation`  created: 2019-04-04 01:54:19 merged: 2019-04-17 07:19:15



67. [26350](http://github.com/cms-sw/cmssw/pull/26350){:target="_blank"}  from **@CTPPS**: Add small changes in CondCore for PPS proton reco, and serialization  `alca`  `db`  created: 2019-04-03 23:01:41 merged: 2019-04-09 20:38:21



68. [26349](http://github.com/cms-sw/cmssw/pull/26349){:target="_blank"}  from **@wddgit**: Bug fix for behavior after exceptions with concurrent lumis `core`  created: 2019-04-03 22:18:51 merged: 2019-04-07 20:23:13



69. [26347](http://github.com/cms-sw/cmssw/pull/26347){:target="_blank"}  from **@casarsa**: MTD validation package `dqm`  `simulation`  created: 2019-04-03 20:28:30 merged: 2019-04-18 16:31:17



70. [26346](http://github.com/cms-sw/cmssw/pull/26346){:target="_blank"}  from **@bsunanda**: Phase2-hgx191 Fix the scintillator cell size for V10 `geometry`  `upgrade`  created: 2019-04-03 19:00:05 merged: 2019-04-05 07:17:39



71. [26344](http://github.com/cms-sw/cmssw/pull/26344){:target="_blank"}  from **@fabiocos**: MTD Geometry: avoid dependence on namespace in volume name string  `geometry`  `upgrade`  created: 2019-04-03 16:03:27 merged: 2019-04-04 15:47:58



72. [26343](http://github.com/cms-sw/cmssw/pull/26343){:target="_blank"}  from **@clacaputo**: DyT algorithm new thresholds parameterization  `hlt`  `reconstruction`  created: 2019-04-03 15:36:17



73. [26342](http://github.com/cms-sw/cmssw/pull/26342){:target="_blank"}  from **@davidlange6**: Move fireworks exception handling to pybind11 `core`  `visualization`  created: 2019-04-03 14:36:35 merged: 2019-04-05 13:33:28



74. [26339](http://github.com/cms-sw/cmssw/pull/26339){:target="_blank"}  from **@kpedro88**: keep hidden valley and dark matter particles in miniAOD `analysis`  `reconstruction`  created: 2019-04-03 14:34:05 merged: 2019-04-04 14:32:43



75. [26338](http://github.com/cms-sw/cmssw/pull/26338){:target="_blank"}  from **@davidlange6**: remove incorrect build dependencies on FWCore/PythonParameterSet `analysis`  `core`  `geometry`  created: 2019-04-03 14:22:20 merged: 2019-04-04 15:24:15



76. [26337](http://github.com/cms-sw/cmssw/pull/26337){:target="_blank"}  from **@schneiml**: DQMIO-related tools `dqm`  created: 2019-04-03 13:56:52 merged: 2019-04-17 07:08:53



77. [26336](http://github.com/cms-sw/cmssw/pull/26336){:target="_blank"}  from **@andrius-k**: A small fix to dqmMemoryStats.py `dqm`  created: 2019-04-03 13:46:41 merged: 2019-04-05 08:06:00



78. [26335](http://github.com/cms-sw/cmssw/pull/26335){:target="_blank"}  from **@CTPPS**: PPS: proton reconstruction, algorithm update `alca`  `analysis`  `dqm`  `reconstruction`  created: 2019-04-03 13:36:28 merged: 2019-04-12 17:29:24



79. [26334](http://github.com/cms-sw/cmssw/pull/26334){:target="_blank"}  from **@Dr15Jones**: Added missing skipEvents to LHESource `generators`  created: 2019-04-03 12:52:02 merged: 2019-04-04 15:49:36



80. [26332](http://github.com/cms-sw/cmssw/pull/26332){:target="_blank"}  from **@makortel**: First attempt of premixing for MTD `reconstruction`  `simulation`  `upgrade`  created: 2019-04-03 08:42:41 merged: 2019-04-08 20:07:10



81. [26331](http://github.com/cms-sw/cmssw/pull/26331){:target="_blank"}  from **@bsunanda**: Run2-hgx185 Add 2 algorithms for HGCal to DD4Hep format `geometry`  created: 2019-04-02 16:09:20 merged: 2019-04-04 14:13:50



82. [26330](http://github.com/cms-sw/cmssw/pull/26330){:target="_blank"}  from **@fabiocos**: Let DummyLHEAnalyzer test run out of the box `generators`  created: 2019-04-02 15:28:15 merged: 2019-04-05 07:11:05



83. [26328](http://github.com/cms-sw/cmssw/pull/26328){:target="_blank"}  from **@slava77**: skip nonexistent branch checks in L1TGlobalUtilHelper `l1`  created: 2019-04-02 15:06:44 merged: 2019-04-09 08:49:04



84. [26327](http://github.com/cms-sw/cmssw/pull/26327){:target="_blank"}  from **@forthommel**: [PPS] Timing calibration for diamond rechits/tracks `alca`  `reconstruction`  created: 2019-04-02 13:55:07 merged: 2019-04-12 08:00:08



85. [26325](http://github.com/cms-sw/cmssw/pull/26325){:target="_blank"}  from **@mverzett**: split matching into GSF to track and GSF to Packed, store the first in AOD `analysis`  `reconstruction`  created: 2019-04-02 13:42:37 merged: 2019-04-09 08:08:50



86. [26324](http://github.com/cms-sw/cmssw/pull/26324){:target="_blank"}  from **@arossi83**: Added plots to monitor pixel clusterrepair algorithm `dqm`  created: 2019-04-02 13:41:04 merged: 2019-04-04 08:42:02



87. [26323](http://github.com/cms-sw/cmssw/pull/26323){:target="_blank"}  from **@Dr15Jones**: Fix const declaration of static used in OAQuality `alca`  `db`  created: 2019-04-02 13:01:40 merged: 2019-04-09 20:36:40



88. [26321](http://github.com/cms-sw/cmssw/pull/26321){:target="_blank"}  from **@Dr15Jones**: Fix thread safety issue in FEDNumbering `daq`  `reconstruction`  created: 2019-04-02 12:11:53 merged: 2019-04-05 08:10:12



89. [26319](http://github.com/cms-sw/cmssw/pull/26319){:target="_blank"}  from **@cms-tsg-storm**: Migration of HLT to 10_6 for Tau changes `hlt`  created: 2019-04-02 09:24:23 merged: 2019-04-03 08:16:50



90. [26318](http://github.com/cms-sw/cmssw/pull/26318){:target="_blank"}  from **@tocheng**: Fix GEM eMap and PF calibration in 2017 ideal simulation GT `alca`  created: 2019-04-02 09:03:15 merged: 2019-04-02 16:07:41



91. [26316](http://github.com/cms-sw/cmssw/pull/26316){:target="_blank"}  from **@CTPPS**: PPS geometry fix for Timing detectors `geometry`  created: 2019-04-02 07:16:42 merged: 2019-04-03 20:44:14



92. [26314](http://github.com/cms-sw/cmssw/pull/26314){:target="_blank"}  from **@bsunanda**: Phase2-hgx190 Modify the hit analyzer code to make tree or a set of histos `dqm`  created: 2019-04-01 21:03:03 merged: 2019-04-03 20:41:16



93. [26313](http://github.com/cms-sw/cmssw/pull/26313){:target="_blank"}  from **@smuzaffar**: cleanup dependency: DataFormats/Provenance does not depend on MessageLogger `core`  created: 2019-04-01 20:50:45 merged: 2019-04-02 09:51:47



94. [26312](http://github.com/cms-sw/cmssw/pull/26312){:target="_blank"}  from **@smuzaffar**: Added std namespace to avoid cxxmodule Ib errors `daq`  created: 2019-04-01 16:17:01 merged: 2019-04-03 20:30:31



95. [26311](http://github.com/cms-sw/cmssw/pull/26311){:target="_blank"}  from **@Dr15Jones**: Make sure isPixel is always initialized in TestAssociator `simulation`  created: 2019-04-01 15:26:43 merged: 2019-04-02 09:48:07



96. [26310](http://github.com/cms-sw/cmssw/pull/26310){:target="_blank"}  from **@makortel**: Make Modifier.isChosen() private `core`  `operations`  created: 2019-04-01 15:21:26 merged: 2019-04-02 10:40:44



97. [26309](http://github.com/cms-sw/cmssw/pull/26309){:target="_blank"}  from **@Dr15Jones**: Make sure all member variables are initialized in RPCEMapSourceHandler `db`  created: 2019-04-01 15:17:57 merged: 2019-04-02 16:06:19



98. [26308](http://github.com/cms-sw/cmssw/pull/26308){:target="_blank"}  from **@Dr15Jones**: Properly handle a polymorphic exception in DTCCablingMapProducer `alca`  `upgrade`  created: 2019-04-01 13:58:16 merged: 2019-04-04 15:14:54



99. [26307](http://github.com/cms-sw/cmssw/pull/26307){:target="_blank"}  from **@fabiocos**: Adapt ETL numbering scheme to new forward volume hierarchy (scenario D41, HGCal v10) `geometry`  `upgrade`  created: 2019-04-01 13:49:06 merged: 2019-04-02 15:51:57



100. [26306](http://github.com/cms-sw/cmssw/pull/26306){:target="_blank"}  from **@davidlange6**: speed up Mixins.py `core`  created: 2019-04-01 11:52:16 merged: 2019-04-02 08:18:00



101. [26305](http://github.com/cms-sw/cmssw/pull/26305){:target="_blank"}  from **@CTPPS**: PPS: alignment from auto GT `alca`  `dqm`  `reconstruction`  created: 2019-04-01 11:44:52 merged: 2019-04-03 20:23:01



102. [26304](http://github.com/cms-sw/cmssw/pull/26304){:target="_blank"}  from **@makortel**: Fix a corner case in ClusterTPAssociationProducer `simulation`  created: 2019-04-01 06:44:27 merged: 2019-04-02 20:37:43



103. [26303](http://github.com/cms-sw/cmssw/pull/26303){:target="_blank"}  from **@chayanit**: hadronizer for HToGG Minlo NNLOPS pLHE relval `generators`  created: 2019-03-31 07:03:03 merged: 2019-04-05 20:18:15



104. [26301](http://github.com/cms-sw/cmssw/pull/26301){:target="_blank"}  from **@bsunanda**: Phase2-hgx189 Add specifics for HGCal V10 geometry `geometry`  `operations`  `pdmv`  `upgrade`  created: 2019-03-29 23:21:54 merged: 2019-04-05 07:16:19



105. [26300](http://github.com/cms-sw/cmssw/pull/26300){:target="_blank"}  from **@gkaratha**: Pythia filter to focus on the probe side of B decays (backport) `generators`  created: 2019-03-29 16:07:20 merged: 2019-04-02 20:36:33



106. [26298](http://github.com/cms-sw/cmssw/pull/26298){:target="_blank"}  from **@hqucms**: Update DeepAK8 to 94X training `reconstruction`  created: 2019-03-29 12:58:52 merged: 2019-04-04 19:18:15



107. [26297](http://github.com/cms-sw/cmssw/pull/26297){:target="_blank"}  from **@Fedespring**: change of the argument definition of some reco::Muon functions  `reconstruction`  created: 2019-03-29 12:58:06 merged: 2019-04-04 08:29:22



108. [26294](http://github.com/cms-sw/cmssw/pull/26294){:target="_blank"}  from **@ggovi**: New feature for the Payload Inspector: support for two tags/ single IOV plot generation `db`  created: 2019-03-29 09:25:35 merged: 2019-04-15 07:19:18



109. [26290](http://github.com/cms-sw/cmssw/pull/26290){:target="_blank"}  from **@bsunanda**: Phase2-hgx188 Make changes to do geometry validation of V10 `dqm`  created: 2019-03-28 20:20:25 merged: 2019-04-01 08:26:21



110. [26289](http://github.com/cms-sw/cmssw/pull/26289){:target="_blank"}  from **@wddgit**: Fix race condition in EventProcessor `core`  created: 2019-03-28 20:00:26 merged: 2019-04-02 20:35:14



111. [26280](http://github.com/cms-sw/cmssw/pull/26280){:target="_blank"}  from **@zhenhu**: update job splitting for 2018 HI data workflows `pdmv`  `upgrade`  created: 2019-03-28 10:54:51 merged: 2019-04-01 16:01:06



112. [26277](http://github.com/cms-sw/cmssw/pull/26277){:target="_blank"}  from **@tonydp03**: Adding E, R and Z ranges to CloseByParticleGun generator `generators`  `simulation`  created: 2019-03-28 09:43:05 merged: 2019-04-02 08:34:43



113. [26276](http://github.com/cms-sw/cmssw/pull/26276){:target="_blank"}  from **@mmusich**: add necessary changes to handle dump import and fetch novel TrackerDetToDTCELinkCablingMap and DTCELinkId CondFormats `db`  created: 2019-03-28 09:04:58 merged: 2019-04-03 20:07:35



114. [26275](http://github.com/cms-sw/cmssw/pull/26275){:target="_blank"}  from **@mmusich**: Activate Simulation of the Pixel Bad Components on the FED channel basis `alca`  `simulation`  created: 2019-03-27 20:31:33 merged: 2019-04-01 08:16:51



115. [26273](http://github.com/cms-sw/cmssw/pull/26273){:target="_blank"}  from **@perrotta**: Adjust a few reco tau config `reconstruction`  created: 2019-03-27 20:01:06 merged: 2019-04-06 15:38:44



116. [26272](http://github.com/cms-sw/cmssw/pull/26272){:target="_blank"}  from **@bsunanda**: Run2-hcx193 Changes to DDHCalBarrelAlgo by removing explicit reference to CLHEP `geometry`  created: 2019-03-27 18:18:42 merged: 2019-04-15 20:49:15



117. [26271](http://github.com/cms-sw/cmssw/pull/26271){:target="_blank"}  from **@bsunanda**: Run2-hcx192 Changes to DDHCalAngular by removing explicit reference to CLHEP `geometry`  created: 2019-03-27 18:12:59 merged: 2019-04-12 20:09:34



118. [26270](http://github.com/cms-sw/cmssw/pull/26270){:target="_blank"}  from **@mariadalfonso**: HBHE: Mahi arrival time `reconstruction`  created: 2019-03-27 15:28:39 merged: 2019-04-02 08:22:28



119. [26267](http://github.com/cms-sw/cmssw/pull/26267){:target="_blank"}  from **@ianna**: DD4hep: Drop Namespace in Geometry Definition `geometry`  created: 2019-03-27 12:05:40 merged: 2019-04-03 20:27:41



120. [26266](http://github.com/cms-sw/cmssw/pull/26266){:target="_blank"}  from **@PFCal-dev**: [HGCAL trigger] Updates in SuperTCs and 3D clustering `l1`  `upgrade`  created: 2019-03-27 11:17:14 merged: 2019-04-11 20:30:12



121. [26264](http://github.com/cms-sw/cmssw/pull/26264){:target="_blank"}  from **@jingyucms**: HGCal Validation Plots `dqm`  created: 2019-03-26 22:27:23 merged: 2019-03-31 12:21:47



122. [26263](http://github.com/cms-sw/cmssw/pull/26263){:target="_blank"}  from **@cmantill**: Turning on ClusterRepair for edge hits only  `alca`  `reconstruction`  created: 2019-03-26 21:20:09 merged: 2019-04-11 20:20:19



123. [26258](http://github.com/cms-sw/cmssw/pull/26258){:target="_blank"}  from **@schneiml**: Ban DQMReferenceHistogramRootFileEventSetupAnalyzer from Production DQM sequences. `dqm`  created: 2019-03-26 16:05:10 merged: 2019-04-15 20:43:48



124. [26256](http://github.com/cms-sw/cmssw/pull/26256){:target="_blank"}  from **@bsunanda**: Run2-TB34 Update some of the code for material budget calculation and re-arrange `simulation`  `upgrade`  created: 2019-03-26 14:07:58 merged: 2019-04-01 16:03:49



125. [26251](http://github.com/cms-sw/cmssw/pull/26251){:target="_blank"}  from **@toropin**: HFStripFilter for Run 2 data `reconstruction`  created: 2019-03-26 09:06:23 merged: 2019-04-05 20:21:33



126. [26249](http://github.com/cms-sw/cmssw/pull/26249){:target="_blank"}  from **@dildick**: SimTrack to muon SimHit matching classes in Muon Validation code `dqm`  created: 2019-03-26 04:21:00 merged: 2019-04-18 16:28:41



127. [26248](http://github.com/cms-sw/cmssw/pull/26248){:target="_blank"}  from **@mondalspandan**: BTagCalibration: Added protection against -ve eta values for SFs calculated on abs(eta) `db`  created: 2019-03-25 22:08:25 merged: 2019-04-03 19:58:21



128. [26247](http://github.com/cms-sw/cmssw/pull/26247){:target="_blank"}  from **@forthommel**: [PPS] Track time selector for miniAOD lite format `reconstruction`  created: 2019-03-25 16:07:18 merged: 2019-04-03 19:55:15



129. [26241](http://github.com/cms-sw/cmssw/pull/26241){:target="_blank"}  from **@Dr15Jones**: Protect against bad inputs in EnergyUncertaintyElectronSpecific `reconstruction`  created: 2019-03-24 22:29:03 merged: 2019-03-31 12:21:58



130. [26234](http://github.com/cms-sw/cmssw/pull/26234){:target="_blank"}  from **@bsunanda**: Run2-TB33 Enable test beam setup to dump geometry for cmsShow `geometry`  `upgrade`  created: 2019-03-22 19:06:06 merged: 2019-04-01 15:49:45



131. [26233](http://github.com/cms-sw/cmssw/pull/26233){:target="_blank"}  from **@bmahakud**: Adding PUPPI combined isolation Working Points in miniAOD muon selector `analysis`  `reconstruction`  created: 2019-03-22 03:54:43 merged: 2019-04-01 08:11:51



132. [26232](http://github.com/cms-sw/cmssw/pull/26232){:target="_blank"}  from **@schneiml**: Save DQM output per lumisection for UL rereco `dqm`  `operations`  created: 2019-03-21 17:39:30 merged: 2019-04-18 16:30:06



133. [26231](http://github.com/cms-sw/cmssw/pull/26231){:target="_blank"}  from **@ianna**: DD4hep: Merge Development to a Usual Geometry Structure `geometry`  created: 2019-03-21 16:49:15 merged: 2019-04-08 19:58:09



134. [26230](http://github.com/cms-sw/cmssw/pull/26230){:target="_blank"}  from **@guitargeek**: RecoParticleFlow/PFProducers - Improve how the PFEGammaFilters and PFMuonAlgo are constructed `reconstruction`  created: 2019-03-21 13:00:30 merged: 2019-04-02 08:30:47



135. [26226](http://github.com/cms-sw/cmssw/pull/26226){:target="_blank"}  from **@wouf**: Interface for external Pyquen #4790 `generators`  created: 2019-03-20 19:24:39 merged: 2019-04-02 20:42:59



136. [26201](http://github.com/cms-sw/cmssw/pull/26201){:target="_blank"}  from **@saghosh**: DT calibration updates2019 `alca`  `dqm`  created: 2019-03-16 13:09:08 merged: 2019-04-02 20:34:05



137. [26194](http://github.com/cms-sw/cmssw/pull/26194){:target="_blank"}  from **@rovere**: HGCAL Clue algorithm 106 x `dqm`  `reconstruction`  `upgrade`  created: 2019-03-15 12:53:55 merged: 2019-04-02 08:25:43



138. [26074](http://github.com/cms-sw/cmssw/pull/26074){:target="_blank"}  from **@tocheng**: Backport : Update GT for ultra legacy - MC ECAL, GEM eMap `alca`  created: 2019-03-05 16:23:36 merged: 2019-03-08 13:24:08



139. [25997](http://github.com/cms-sw/cmssw/pull/25997){:target="_blank"}  from **@fabiocos**: [105X] removing three fragments from override (backport of #25955) `pdmv`  `upgrade`  created: 2019-02-22 08:42:29 merged: 2019-02-25 15:43:36



140. [25495](http://github.com/cms-sw/cmssw/pull/25495){:target="_blank"}  from **@CTPPS**: PPS proton reconstruction `alca`  `analysis`  `db`  `dqm`  `generators`  `operations`  `reconstruction`  `simulation`  created: 2018-12-13 15:42:11 merged: 2019-03-31 12:21:27



141. [25158](http://github.com/cms-sw/cmssw/pull/25158){:target="_blank"}  from **@jshlee**: GEM unpacker for  VFat V3 `dqm`  `reconstruction`  `simulation`  `upgrade`  created: 2018-11-08 13:52:33 merged: 2019-03-31 12:13:49



142. [22594](http://github.com/cms-sw/cmssw/pull/22594){:target="_blank"}  from **@cms-tau-pog**: Tau reconstruction based on miniAOD event content  `analysis`  `dqm`  `hlt`  `reconstruction`  `visualization`  created: 2018-03-13 13:35:26 merged: 2019-04-06 07:47:30



#### CMSDIST Changes between Tags REL/CMSSW_10_6_0_pre3/slc7_amd64_gcc700 and REL/CMSSW_10_6_0_pre4/slc7_amd64_gcc700:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_10_6_0_pre3/slc7_amd64_gcc700...REL/CMSSW_10_6_0_pre4/slc7_amd64_gcc700)



1. [4887](http://github.com/cms-sw/cmsdist/pull/4887){:target="_blank"}  from **@davidlange6**: update python packages and xtensor created: 2019-04-16 19:01:18 merged: 2019-04-17 20:23:53

2. [4886](http://github.com/cms-sw/cmsdist/pull/4886){:target="_blank"}  from **@fwyzard**: Update CUDA to version 10.1.105, on x86_64 created: 2019-04-16 15:55:19 merged: 2019-04-18 16:36:11

3. [4879](http://github.com/cms-sw/cmsdist/pull/4879){:target="_blank"}  from **@cms-sw**: Fix pip xgboost 0.82 for arm and ppc created: 2019-04-15 16:20:42 merged: 2019-04-15 19:49:54

4. [4872](http://github.com/cms-sw/cmsdist/pull/4872){:target="_blank"}  from **@cms-sw**: Add ppc64 flags for gcc and llvm created: 2019-04-11 14:42:15 merged: 2019-04-12 07:48:18

5. [4871](http://github.com/cms-sw/cmsdist/pull/4871){:target="_blank"}  from **@cms-sw**: Put condition for openloops in toolfiles - herwig and geneva created: 2019-04-11 09:55:41 merged: 2019-04-12 21:31:18

6. [4870](http://github.com/cms-sw/cmsdist/pull/4870){:target="_blank"}  from **@davidlange6**: update many python package versions created: 2019-04-11 09:09:46 merged: 2019-04-12 08:57:04

7. [4869](http://github.com/cms-sw/cmsdist/pull/4869){:target="_blank"}  from **@cms-sw**: Condition for ppc64 for tfcompile created: 2019-04-10 19:40:45 merged: 2019-04-10 21:28:45

8. [4865](http://github.com/cms-sw/cmsdist/pull/4865){:target="_blank"}  from **@fwyzard**: Ignore .pyc and .pyo temporary files created: 2019-04-09 16:44:34 merged: 2019-04-09 20:27:41

9. [4863](http://github.com/cms-sw/cmsdist/pull/4863){:target="_blank"}  from **@fwyzard**: Include missing NVIDIA drivers (gcc700 build) created: 2019-04-09 16:44:04 merged: 2019-04-10 06:55:28

10. [4860](http://github.com/cms-sw/cmsdist/pull/4860){:target="_blank"}  from **@cms-sw**: [BuildRule][10.6.X] Fix build rule code-format created: 2019-04-09 13:15:52 merged: 2019-04-09 20:30:11

11. [4859](http://github.com/cms-sw/cmsdist/pull/4859){:target="_blank"}  from **@cms-sw**: Update dd4hep with latest changes on master and remove ppc64 patch created: 2019-04-09 10:17:27 merged: 2019-04-09 20:30:55

12. [4857](http://github.com/cms-sw/cmsdist/pull/4857){:target="_blank"}  from **@cms-sw**: fwlite:drop FWCore/PyDevParameterSet and FWCore/Framework/bin created: 2019-04-08 21:29:48 merged: 2019-04-08 21:30:31

13. [4855](http://github.com/cms-sw/cmsdist/pull/4855){:target="_blank"}  from **@cms-sw**: Add DDG4 headers to dd4hep include created: 2019-04-08 14:26:07 merged: 2019-04-08 20:27:44

14. [4850](http://github.com/cms-sw/cmsdist/pull/4850){:target="_blank"}  from **@cms-sw**: Update Configuration-Generator tag to 01-00-03 created: 2019-04-08 07:57:41 merged: 2019-04-12 13:39:47

15. [4846](http://github.com/cms-sw/cmsdist/pull/4846){:target="_blank"}  from **@fabiocos**: Update gcc version to 7.4.1 created: 2019-04-05 14:12:43 merged: 2019-04-11 15:31:57

16. [4838](http://github.com/cms-sw/cmsdist/pull/4838){:target="_blank"}  from **@cms-sw**: Update externals for ppc64 build created: 2019-04-03 15:24:01 merged: 2019-04-09 07:15:43

17. [4836](http://github.com/cms-sw/cmsdist/pull/4836){:target="_blank"}  from **@cms-sw**: [CVE-2019-10255] Update py2-notebook to 5.7.8 created: 2019-04-02 17:39:29 merged: 2019-04-02 20:09:44

18. [4835](http://github.com/cms-sw/cmsdist/pull/4835){:target="_blank"}  from **@cms-sw**: [BuildRules][DD4Hep] look for listcomponent under DD4HEP_CORE_BASE created: 2019-04-02 10:45:12 merged: 2019-04-02 20:08:39

19. [4829](http://github.com/cms-sw/cmsdist/pull/4829){:target="_blank"}  from **@cms-sw**: [10.6.X] Update RecoBTag-Combined to V01-01-03 created: 2019-03-29 14:44:24 merged: 2019-04-04 08:37:41

20. [4820](http://github.com/cms-sw/cmsdist/pull/4820){:target="_blank"}  from **@cms-sw**: enable geant4 and example/ddcms for dd4hep created: 2019-03-28 12:46:25 merged: 2019-04-01 15:05:30

21. [4796](http://github.com/cms-sw/cmsdist/pull/4796){:target="_blank"}  from **@SiewYan**: Update openloops-2.0.b to openloops-2.0.0 created: 2019-03-21 22:02:32 merged: 2019-04-12 19:55:43

22. [4790](http://github.com/cms-sw/cmsdist/pull/4790){:target="_blank"}  from **@wouf**: Pyquen reintegration as external created: 2019-03-20 12:09:07 merged: 2019-04-02 20:40:45
