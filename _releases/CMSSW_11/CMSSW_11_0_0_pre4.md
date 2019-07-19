---
layout: post
rel_link:  "11_0_0_pre4"
title:  "CMSSW_11_0_0_pre4"
date:   2019-07-19 07:21:51
categories: cmssw
relmajor: 11
relminor: 0
relsubminor: 0
relpre: _pre4
---

# CMSSW_11_0_0_pre4
#### Changes since CMSSW_11_0_0_pre3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_11_0_0_pre3...CMSSW_11_0_0_pre4)



1. [27540](http://github.com/cms-sw/cmssw/pull/27540){:target="_blank"}  from **@mmusich**: fix segfault in DQMCertCommonFakeHLT `dqm`  created: 2019-07-17 08:39:41 merged: 2019-07-17 20:32:21



2. [27536](http://github.com/cms-sw/cmssw/pull/27536){:target="_blank"}  from **@fabiocos**: Add scenario Run3 to Configuration/DataProcessing `operations`  created: 2019-07-16 18:55:34 merged: 2019-07-17 05:22:13



3. [27535](http://github.com/cms-sw/cmssw/pull/27535){:target="_blank"}  from **@hbecerri**: Remove all the ocurrences of SetCanExtend from TrackAnalyzer `dqm`  created: 2019-07-16 16:08:00 merged: 2019-07-17 20:38:10



4. [27534](http://github.com/cms-sw/cmssw/pull/27534){:target="_blank"}  from **@Dr15Jones**: Avoid dereferencing nullptr in FEDRawData `daq`  created: 2019-07-16 15:45:53 merged: 2019-07-17 08:05:35



5. [27532](http://github.com/cms-sw/cmssw/pull/27532){:target="_blank"}  from **@Dr15Jones**: Avoid dereferencing nullptr in TStorageFactoryFile `core`  created: 2019-07-16 14:00:13 merged: 2019-07-17 08:08:31



6. [27529](http://github.com/cms-sw/cmssw/pull/27529){:target="_blank"}  from **@fabiocos**: Update globalreco_tracking sequence for Phase2 `operations`  `upgrade`  created: 2019-07-16 09:45:11 merged: 2019-07-18 09:50:33



7. [27527](http://github.com/cms-sw/cmssw/pull/27527){:target="_blank"}  from **@bsunanda**: Run3-hcx211 Clean up DDD references `simulation`  `upgrade`  created: 2019-07-15 20:54:07 merged: 2019-07-17 20:36:57



8. [27521](http://github.com/cms-sw/cmssw/pull/27521){:target="_blank"}  from **@bsunanda**: Phase2-hgx203 Fix a bug and add a test `geometry`  `upgrade`  created: 2019-07-15 16:52:31 merged: 2019-07-17 20:37:46



9. [27519](http://github.com/cms-sw/cmssw/pull/27519){:target="_blank"}  from **@civanch**: Reduce memory churn at Geant4 initialisation of geometry `simulation`  created: 2019-07-14 13:57:43 merged: 2019-07-15 17:31:14



10. [27518](http://github.com/cms-sw/cmssw/pull/27518){:target="_blank"}  from **@ianna**: DD4hep: Ecal Preshower Algorithm Migration `geometry`  created: 2019-07-14 13:17:38 merged: 2019-07-17 08:54:49



11. [27515](http://github.com/cms-sw/cmssw/pull/27515){:target="_blank"}  from **@Dr15Jones**: Initialize member variable in CSCDQM_Lock `dqm`  created: 2019-07-13 13:40:01 merged: 2019-07-14 19:58:10



12. [27513](http://github.com/cms-sw/cmssw/pull/27513){:target="_blank"}  from **@Dr15Jones**: Modernized ESProducers in RecoTracker/TkNavigation `reconstruction`  created: 2019-07-12 20:54:06 merged: 2019-07-17 20:36:12



13. [27510](http://github.com/cms-sw/cmssw/pull/27510){:target="_blank"}  from **@Dr15Jones**: Modernized TkTransientTrackingRecHitBuilderESProducer `reconstruction`  created: 2019-07-12 16:26:35 merged: 2019-07-17 20:35:48



14. [27509](http://github.com/cms-sw/cmssw/pull/27509){:target="_blank"}  from **@bsunanda**: Run3-TB37 Update HGCal TB simulation `geometry`  `simulation`  `upgrade`  created: 2019-07-12 16:22:53 merged: 2019-07-16 07:33:41



15. [27508](http://github.com/cms-sw/cmssw/pull/27508){:target="_blank"}  from **@rovere**: Add proper table columns for HGCAL objects in Fireworks `visualization`  created: 2019-07-12 13:46:43 merged: 2019-07-14 19:56:16



16. [27503](http://github.com/cms-sw/cmssw/pull/27503){:target="_blank"}  from **@clelange**: Account for layer offset when using waferZ in new geometry `reconstruction`  `upgrade`  created: 2019-07-11 18:13:29 merged: 2019-07-15 17:31:41



17. [27501](http://github.com/cms-sw/cmssw/pull/27501){:target="_blank"}  from **@ianna**: DD4hep: Ecal Endcap Algo `geometry`  created: 2019-07-11 16:25:17 merged: 2019-07-14 19:48:50



18. [27499](http://github.com/cms-sw/cmssw/pull/27499){:target="_blank"}  from **@fabiocos**: Fix SLHCUpgradeSimulations/Geometry unit test after geometry scenarios cleaning `geometry`  `upgrade`  created: 2019-07-11 13:24:46 merged: 2019-07-11 19:56:06



19. [27495](http://github.com/cms-sw/cmssw/pull/27495){:target="_blank"}  from **@ianna**: Geometry: Move DOMCount Regression Test to Geometry/CMSCommonData `geometry`  `upgrade`  created: 2019-07-11 10:10:46 merged: 2019-07-11 19:58:19



20. [27492](http://github.com/cms-sw/cmssw/pull/27492){:target="_blank"}  from **@adewit**: TkAl Millepede: improve file copying and copy error reporting `alca`  created: 2019-07-11 09:18:08 merged: 2019-07-12 12:26:36



21. [27488](http://github.com/cms-sw/cmssw/pull/27488){:target="_blank"}  from **@kpedro88**: rename 2023 -> 2026, fix bug in D44 `alca`  `db`  `geometry`  `l1`  `operations`  `pdmv`  `upgrade`  `visualization`  created: 2019-07-11 03:40:11 merged: 2019-07-17 20:39:21



22. [27484](http://github.com/cms-sw/cmssw/pull/27484){:target="_blank"}  from **@Dr15Jones**:  Modernized ESProducers in TrackingTools/KalmanUpdators `reconstruction`  created: 2019-07-10 22:07:35 merged: 2019-07-12 20:48:05



23. [27482](http://github.com/cms-sw/cmssw/pull/27482){:target="_blank"}  from **@Dr15Jones**: Modernized PropagatorWithMaterialESProducer `reconstruction`  created: 2019-07-10 21:15:16 merged: 2019-07-12 07:14:52



24. [27481](http://github.com/cms-sw/cmssw/pull/27481){:target="_blank"}  from **@cms-sw**: Revert "Primitive RPC trigger" `l1`  created: 2019-07-10 19:44:46 merged: 2019-07-10 19:55:36



25. [27480](http://github.com/cms-sw/cmssw/pull/27480){:target="_blank"}  from **@Dr15Jones**: Be consistent when replacing a module or Sequence in a Process `core`  created: 2019-07-10 18:15:15 merged: 2019-07-12 20:47:18



26. [27479](http://github.com/cms-sw/cmssw/pull/27479){:target="_blank"}  from **@civanch**: Fixed and clean-up initialisation of Geant4 `simulation`  created: 2019-07-10 16:55:27 merged: 2019-07-12 20:48:46



27. [27478](http://github.com/cms-sw/cmssw/pull/27478){:target="_blank"}  from **@apsallid**: [HGCal] Run HGCalValidator only on the hard scatterer event and correcting the mess from merging `dqm`  created: 2019-07-10 16:53:20 merged: 2019-07-14 19:52:22



28. [27474](http://github.com/cms-sw/cmssw/pull/27474){:target="_blank"}  from **@jeongeun**: Move Sequence to Task for RecoLocalCalo config files `dqm`  `reconstruction`  `simulation`  `upgrade`  created: 2019-07-10 06:02:12 merged: 2019-07-14 19:50:41



29. [27473](http://github.com/cms-sw/cmssw/pull/27473){:target="_blank"}  from **@Dr15Jones**: Added additional exception info to DQMRootSource `dqm`  created: 2019-07-09 22:10:18 merged: 2019-07-10 17:11:08



30. [27471](http://github.com/cms-sw/cmssw/pull/27471){:target="_blank"}  from **@wddgit**: Bug fix in new allowAnyLabel_ feature `core`  created: 2019-07-09 21:25:02 merged: 2019-07-10 17:06:41



31. [27468](http://github.com/cms-sw/cmssw/pull/27468){:target="_blank"}  from **@Dr15Jones**: Avoid switch statement fallthrough in edm::Path `core`  created: 2019-07-09 19:39:48 merged: 2019-07-10 17:03:24



32. [27467](http://github.com/cms-sw/cmssw/pull/27467){:target="_blank"}  from **@jfernan2**: First attempt to remove DQM HLT warnings from logs caused by HLT Fake menus `dqm`  `pdmv`  `upgrade`  created: 2019-07-09 17:56:33 merged: 2019-07-16 17:15:51



33. [27464](http://github.com/cms-sw/cmssw/pull/27464){:target="_blank"}  from **@bsunanda**: Phase2-hgx201 Provide Corner Centric Geometry for HGCal `geometry`  `upgrade`  created: 2019-07-09 15:13:20 merged: 2019-07-10 19:54:23



34. [27461](http://github.com/cms-sw/cmssw/pull/27461){:target="_blank"}  from **@jpriscia**: Si strip plugins two tags 110 x `db`  created: 2019-07-09 08:02:13 merged: 2019-07-11 08:36:58



35. [27460](http://github.com/cms-sw/cmssw/pull/27460){:target="_blank"}  from **@bsunanda**: Run3-sim35 Modify the IsolatedTrack GenFilter `generators`  created: 2019-07-08 19:47:56 merged: 2019-07-09 08:41:03



36. [27459](http://github.com/cms-sw/cmssw/pull/27459){:target="_blank"}  from **@bsunanda**: Run3-fwk02 Make use of name or fullname as option `visualization`  created: 2019-07-08 14:43:35 merged: 2019-07-09 19:00:01



37. [27454](http://github.com/cms-sw/cmssw/pull/27454){:target="_blank"}  from **@Dr15Jones**: cms.optional and obsolete now return None from call to value() `core`  created: 2019-07-07 15:06:44 merged: 2019-07-08 06:46:47



38. [27452](http://github.com/cms-sw/cmssw/pull/27452){:target="_blank"}  from **@civanch**: Fix circular dependences inside SIM packages `simulation`  created: 2019-07-06 15:44:16 merged: 2019-07-07 19:23:38



39. [27449](http://github.com/cms-sw/cmssw/pull/27449){:target="_blank"}  from **@kpedro88**: Clean up Phase2 workflows `geometry`  `operations`  `pdmv`  `upgrade`  created: 2019-07-05 17:05:23 merged: 2019-07-10 16:52:36



40. [27448](http://github.com/cms-sw/cmssw/pull/27448){:target="_blank"}  from **@mmusich**: Fix PixelCPEBase::fillDetParams() for Phase-2 IT, using new GeomDetEnumerators methods `geometry`  `reconstruction`  created: 2019-07-05 16:39:05 merged: 2019-07-10 17:00:11



41. [27444](http://github.com/cms-sw/cmssw/pull/27444){:target="_blank"}  from **@ianna**: DD4hep: Ecal Barrel New Algorithm v2 `geometry`  `reconstruction`  created: 2019-07-04 16:21:16 merged: 2019-07-09 17:45:11



42. [27442](http://github.com/cms-sw/cmssw/pull/27442){:target="_blank"}  from **@civanch**: Cleanup initialisation of Geant4 `simulation`  created: 2019-07-04 15:51:47 merged: 2019-07-05 15:35:28



43. [27441](http://github.com/cms-sw/cmssw/pull/27441){:target="_blank"}  from **@christopheralanwest**: Add 11_0_X global tags for 2021 and later MC scenarios `alca`  created: 2019-07-04 14:19:36 merged: 2019-07-11 19:54:11



44. [27440](http://github.com/cms-sw/cmssw/pull/27440){:target="_blank"}  from **@CTPPS**: PPS: update of association cuts `operations`  `reconstruction`  created: 2019-07-04 09:52:22 merged: 2019-07-11 08:27:11



45. [27438](http://github.com/cms-sw/cmssw/pull/27438){:target="_blank"}  from **@CTPPS**: g4SimHits changes in the source code needed to include PPS  `simulation`  created: 2019-07-04 08:32:44 merged: 2019-07-05 15:34:29



46. [27436](http://github.com/cms-sw/cmssw/pull/27436){:target="_blank"}  from **@ahmad3213**: Fix for relval_8.2 job splitting issue `pdmv`  `upgrade`  created: 2019-07-04 05:35:44 merged: 2019-07-09 19:23:32



47. [27430](http://github.com/cms-sw/cmssw/pull/27430){:target="_blank"}  from **@makortel**: Use ESGetToken in JetTagComputerESProducer<T> `reconstruction`  created: 2019-07-03 07:24:50 merged: 2019-07-07 19:23:13



48. [27428](http://github.com/cms-sw/cmssw/pull/27428){:target="_blank"}  from **@ahinzmann**: Fix jet energy fractions after jet resolution smearing `analysis`  `reconstruction`  created: 2019-07-02 15:33:10 merged: 2019-07-16 17:15:16



49. [27422](http://github.com/cms-sw/cmssw/pull/27422){:target="_blank"}  from **@slava77**: make some internal globals const in TkBfield.cc `reconstruction`  created: 2019-07-02 10:39:41 merged: 2019-07-05 15:36:26



50. [27419](http://github.com/cms-sw/cmssw/pull/27419){:target="_blank"}  from **@jshlee**: GEM vfat dataformat update v301 `dqm`  `reconstruction`  created: 2019-07-01 19:16:30 merged: 2019-07-17 20:31:22



51. [27418](http://github.com/cms-sw/cmssw/pull/27418){:target="_blank"}  from **@rovere**: Remove localDensity from the EventContent for HGCAL `reconstruction`  created: 2019-07-01 12:39:42 merged: 2019-07-09 19:11:16



52. [27415](http://github.com/cms-sw/cmssw/pull/27415){:target="_blank"}  from @mmusich: Move Data ReReco ZeroBias RelvVals to use **@rerecoZeroBias** DQM sequence `pdmv`  `upgrade`  created: 2019-06-30 16:46:41 merged: 2019-07-09 19:26:08



53. [27400](http://github.com/cms-sw/cmssw/pull/27400){:target="_blank"}  from **@cms-tau-pog**: Remove calo tau code and data formats `analysis`  `docs`  `dqm`  `hlt`  `reconstruction`  `visualization`  created: 2019-06-28 14:33:00 merged: 2019-07-09 17:48:02



54. [27377](http://github.com/cms-sw/cmssw/pull/27377){:target="_blank"}  from **@deguio**: Fix ADC range for HGC scintillators `simulation`  `upgrade`  created: 2019-06-27 13:14:57 merged: 2019-07-10 16:55:50



55. [27340](http://github.com/cms-sw/cmssw/pull/27340){:target="_blank"}  from **@PFCal-dev**: [HGCAL trigger] Updates (mainly) in Super/Coarse trigger cells and cluster seeding `l1`  `simulation`  `upgrade`  created: 2019-06-25 15:26:56 merged: 2019-07-10 16:51:14



56. [27179](http://github.com/cms-sw/cmssw/pull/27179){:target="_blank"}  from **@bi-ran**: deep copy to avoid modifying original values `core`  created: 2019-06-11 22:21:14 merged: 2019-07-17 20:34:46



57. [26967](http://github.com/cms-sw/cmssw/pull/26967){:target="_blank"}  from **@maseguracern**: Primitive RPC trigger `l1`  created: 2019-05-28 13:23:36 merged: 2019-07-09 19:01:16



#### CMSDIST Changes between Tags REL/CMSSW_11_0_0_pre3/slc7_amd64_gcc700 and REL/CMSSW_11_0_0_pre4/slc7_amd64_gcc700:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_11_0_0_pre3/slc7_amd64_gcc700...REL/CMSSW_11_0_0_pre4/slc7_amd64_gcc700)



1. [5096](http://github.com/cms-sw/cmsdist/pull/5096){:target="_blank"}  from **@davidlange6**: turn off modules for DataFormats/TrajectoryState created: 2019-07-18 13:32:30 merged: 2019-07-18 18:36:41

2. [5091](http://github.com/cms-sw/cmsdist/pull/5091){:target="_blank"}  from **@hqucms**: Update OpenBLAS build options created: 2019-07-12 22:05:02 merged: 2019-07-17 14:56:27

3. [5087](http://github.com/cms-sw/cmsdist/pull/5087){:target="_blank"}  from **@cms-sw**: Update cmake to 3.14.5 created: 2019-07-10 14:21:59 merged: 2019-07-17 13:04:02

4. [5086](http://github.com/cms-sw/cmsdist/pull/5086){:target="_blank"}  from **@cms-sw**: updated libunwind to 1.3.1 and drop libatomic_ops deps created: 2019-07-10 10:22:31 merged: 2019-07-10 19:43:19

5. [5085](http://github.com/cms-sw/cmsdist/pull/5085){:target="_blank"}  from **@cms-sw**: fix igprof:properly use cmake to find unwind and pcre instead of copying their headers in igprof created: 2019-07-10 05:00:41 merged: 2019-07-10 05:52:08

6. [5075](http://github.com/cms-sw/cmsdist/pull/5075){:target="_blank"}  from **@cms-sw**: [CMSDIST master] Get freetype from externals, move it to 2.10.0 created: 2019-07-05 10:05:45 merged: 2019-07-06 06:00:46

7. [5069](http://github.com/cms-sw/cmsdist/pull/5069){:target="_blank"}  from **@cms-sw**: [BuildRules] Back ports changes from cxxmodules branch created: 2019-07-03 12:59:04 merged: 2019-07-05 08:03:38

8. [5062](http://github.com/cms-sw/cmsdist/pull/5062){:target="_blank"}  from **@cms-sw**: Update the rest of the ROOT deps created: 2019-06-27 14:28:34 merged: 2019-07-12 06:07:49
