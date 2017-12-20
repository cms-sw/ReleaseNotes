---
layout: post
rel_link:  "7_1_0_pre4"
title:  "CMSSW_7_1_0_pre4"
date:   2014-03-07 08:58:32
categories: cmssw
relmajor: 7
relminor: 1
relsubminor: 0
relpre: _pre4
---

# CMSSW_7_1_0_pre4
#### Changes since CMSSW_7_1_0_pre3:

1. [2741](http://github.com/cms-sw/cmssw/pull/2741){:target="_blank"}  from **@degano**: Gcc 4.9.0 -- Fix unused function warning. `alca`  `db`  created: 2014-03-06 10:29:17 merged: 2014-03-06 10:31:40

2. [2578](http://github.com/cms-sw/cmssw/pull/2578){:target="_blank"}  from **@itopsisg**: DQM -- From cmssw 7 1 x phase1 upgrade `dqm`  `simulation`  created: 2014-02-21 11:14:18 merged: 2014-03-05 19:46:33

3. [2731](http://github.com/cms-sw/cmssw/pull/2731){:target="_blank"}  from **@Dr15Jones**: Framework -- Use edm::convertException::wrap to handle conversion of exceptions `core`  created: 2014-03-05 15:25:25 merged: 2014-03-05 18:46:47

4. [2676](http://github.com/cms-sw/cmssw/pull/2676){:target="_blank"}  from **@acimmino**: DQM -- DQMEDAnalyzer migration for 71x `dqm`  created: 2014-02-28 16:07:24 merged: 2014-03-05 15:02:42

5. [2729](http://github.com/cms-sw/cmssw/pull/2729){:target="_blank"}  from **@nancymarinelli**: DQM -- Fix to have the DQMOffline/EGamma able to run on the HI sequence  `dqm`  created: 2014-03-05 14:17:29 merged: 2014-03-05 14:18:40

6. [2598](http://github.com/cms-sw/cmssw/pull/2598){:target="_blank"}  from **@VinInn**: Reco updates -- TrackingRecHit rework `analysis`  `fastsim`  `reconstruction`  created: 2014-02-23 09:14:14 merged: 2014-03-05 12:55:11

7. [2429](http://github.com/cms-sw/cmssw/pull/2429){:target="_blank"}  from **@jstupak**: RecoJets -- Addition of code for nSubjettiness and QJets `reconstruction`  created: 2014-02-12 18:06:44 merged: 2014-03-05 09:36:12

8. [2710](http://github.com/cms-sw/cmssw/pull/2710){:target="_blank"}  from **@cerati**: DQM -- Switch back to use associator for track validation `dqm`  created: 2014-03-04 01:54:44 merged: 2014-03-04 20:25:04

9. [2716](http://github.com/cms-sw/cmssw/pull/2716){:target="_blank"}  from **@wmtan**: Misc fixes -- Avoid segfault in playback mode if no files specified `core`  created: 2014-03-04 19:57:42 merged: 2014-03-04 20:04:25

10. [2672](http://github.com/cms-sw/cmssw/pull/2672){:target="_blank"}  from **@apsallid**: DQM -- Changes so that no package creates its own root file `dqm`  created: 2014-02-28 10:41:59 merged: 2014-03-04 15:01:10

11. [2687](http://github.com/cms-sw/cmssw/pull/2687){:target="_blank"}  from **@ebouvier**: Consumes migration -- DQMOffline/Trigger `dqm`  created: 2014-03-01 23:21:31 merged: 2014-03-04 14:51:31

12. [2645](http://github.com/cms-sw/cmssw/pull/2645){:target="_blank"}  from **@mkirsano**: Generators -- Fix residual decays for the guns `generators`  created: 2014-02-26 17:16:22 merged: 2014-03-04 14:04:28

13. [2714](http://github.com/cms-sw/cmssw/pull/2714){:target="_blank"}  from **@ktf**: Drop VerboseLevel, which is not supported anymore in root > 5.34.17. `reconstruction`  created: 2014-03-04 14:01:18 merged: 2014-03-04 14:02:25

14. [2704](http://github.com/cms-sw/cmssw/pull/2704){:target="_blank"}  from **@Dr15Jones**: FWCore/Framework -- Set Global cache at beginStream time for Stream modules `core`  created: 2014-03-03 17:21:46 merged: 2014-03-04 12:56:19

15. [2702](http://github.com/cms-sw/cmssw/pull/2702){:target="_blank"}  from **@ianna**: Geometry -- Fix overlaps with new beampipe. `geometry`  created: 2014-03-03 16:39:39 merged: 2014-03-04 12:55:06

16. [2712](http://github.com/cms-sw/cmssw/pull/2712){:target="_blank"}  from **@ktf**: Gcc 4.9.0 -- Warning fixes. `alca`  `db`  created: 2014-03-04 10:33:02 merged: 2014-03-04 10:34:51

17. [2697](http://github.com/cms-sw/cmssw/pull/2697){:target="_blank"}  from **@perrotta**: RecoEgamma/EgammaHLTProducers -- Rescue topic protect rho `hlt`  created: 2014-03-03 15:09:07 merged: 2014-03-04 08:34:39

18. [2636](http://github.com/cms-sw/cmssw/pull/2636){:target="_blank"}  from **@nancymarinelli**: Egm ged dqm offline updates for7 xx 1 `dqm`  created: 2014-02-25 18:11:01 merged: 2014-03-04 08:28:52

19. [2523](http://github.com/cms-sw/cmssw/pull/2523){:target="_blank"}  from **@wddgit**: New Random Number Generator -- Migrate Calibration Code to New Random Service Interface `alca`  created: 2014-02-18 22:50:49 merged: 2014-03-04 08:18:05

20. [2397](http://github.com/cms-sw/cmssw/pull/2397){:target="_blank"}  from **@dmitrijus**: HLT -- Make Ecal TimeBias correction to use a new GT. `hlt`  `operations`  `reconstruction`  created: 2014-02-11 12:47:35 merged: 2014-03-04 08:13:30

21. [2679](http://github.com/cms-sw/cmssw/pull/2679){:target="_blank"}  from **@cerati**: Fix compile errors debug flag `reconstruction`  `simulation`  created: 2014-02-28 19:08:42 merged: 2014-03-03 16:02:55

22. [2693](http://github.com/cms-sw/cmssw/pull/2693){:target="_blank"}  from **@aburgm**: TauAnalysis/MCEmbeddingTools -- Apply rotation around Z axis also for mumu->mumu transformations `simulation`  created: 2014-03-03 10:18:25 merged: 2014-03-03 13:43:28

23. [2681](http://github.com/cms-sw/cmssw/pull/2681){:target="_blank"}  from **@smrenna**: Pythia8 -- Check if Pythia8 recognizes the stable particles `generators`  created: 2014-02-28 20:04:51 merged: 2014-03-03 12:18:06

24. [2686](http://github.com/cms-sw/cmssw/pull/2686){:target="_blank"}  from **@mbluj**: HLT Consumes Migration -- HLTTau producers migrated to consume `hlt`  created: 2014-03-01 23:18:44 merged: 2014-03-03 12:17:06

25. [2690](http://github.com/cms-sw/cmssw/pull/2690){:target="_blank"}  from @bendavid: GeneratorInterface/LHEInterface -- Changes to allow aMC**@NLO** production with ExternalLHEProducer (71x) `generators`  created: 2014-03-03 00:04:27 merged: 2014-03-03 12:15:20

26. [2695](http://github.com/cms-sw/cmssw/pull/2695){:target="_blank"}  from **@ktf**: Fix issue introduced in #2619 `operations`  created: 2014-03-03 10:42:01 merged: 2014-03-03 10:43:42

27. [2628](http://github.com/cms-sw/cmssw/pull/2628){:target="_blank"}  from **@VinInn**: CalibTracker/SiPixelESProducers -- Si pixel gains `alca`  `db`  created: 2014-02-25 09:58:07 merged: 2014-03-03 10:02:02

28. [2691](http://github.com/cms-sw/cmssw/pull/2691){:target="_blank"}  from **@degano**: Gcc4.9.0 -- Fixup of unused function warnings for gcc490. `core`  `geometry`  created: 2014-03-03 08:52:05 merged: 2014-03-03 09:03:46

29. [2567](http://github.com/cms-sw/cmssw/pull/2567){:target="_blank"}  from **@cerati**: Reco update -- triplet-based seeding for iter5 and iter6 `fastsim`  `reconstruction`  created: 2014-02-20 21:22:22 merged: 2014-03-03 08:42:55

30. [2683](http://github.com/cms-sw/cmssw/pull/2683){:target="_blank"}  from **@matteosan1**: move delete of energy corrector in destructor `reconstruction`  created: 2014-02-28 23:00:12 merged: 2014-03-01 09:42:10

31. [2680](http://github.com/cms-sw/cmssw/pull/2680){:target="_blank"}  from **@wmtan**: ROOT6 -- Add missing iostream include `reconstruction`  created: 2014-02-28 19:50:29 merged: 2014-02-28 20:19:22

32. [2664](http://github.com/cms-sw/cmssw/pull/2664){:target="_blank"}  from **@gartung**: Thread Safety  DataFormats/ParticleFlowReco -- Change depthCor\* static members to static std::atomic `reconstruction`  created: 2014-02-27 17:15:39 merged: 2014-02-28 15:14:30

33. [2673](http://github.com/cms-sw/cmssw/pull/2673){:target="_blank"}  from **@degano**: GCC 4.9.0 -- Fix unused function warnings. `analysis`  `db`  `generators`  `reconstruction`  created: 2014-02-28 10:50:56 merged: 2014-02-28 14:05:27

34. [2646](http://github.com/cms-sw/cmssw/pull/2646){:target="_blank"}  from **@robervalwalsh**:  Geometry -- 710pre3 tracker-lumi geometry `geometry`  created: 2014-02-26 18:53:09 merged: 2014-02-28 10:02:29

35. [2665](http://github.com/cms-sw/cmssw/pull/2665){:target="_blank"}  from **@deguio**: DQM Fixes -- Fix dqm tests `dqm`  created: 2014-02-27 18:10:40 merged: 2014-02-28 09:24:25

36. [2582](http://github.com/cms-sw/cmssw/pull/2582){:target="_blank"}  from **@dmitrijus**: RecoLocalCalo/EcalRecAlgos -- Integrate a new, optimized EcalUncalibRecHitRatioMethodAlgo. `reconstruction`  created: 2014-02-21 14:16:39 merged: 2014-02-28 09:22:23

37. [2581](http://github.com/cms-sw/cmssw/pull/2581){:target="_blank"}  from **@VinInn**: RecoLocalTracker -- Fast match `reconstruction`  created: 2014-02-21 13:53:21 merged: 2014-02-28 09:17:44

38. [2449](http://github.com/cms-sw/cmssw/pull/2449){:target="_blank"}  from **@cms-tau-pog**: Reco update -- TauID patches `reconstruction`  created: 2014-02-13 14:32:39 merged: 2014-02-27 16:42:32

39. [2261](http://github.com/cms-sw/cmssw/pull/2261){:target="_blank"}  from **@bendavid**: Reco update -- Single leg conversion update `reconstruction`  created: 2014-01-31 23:44:56 merged: 2014-02-27 16:34:09

40. [2619](http://github.com/cms-sw/cmssw/pull/2619){:target="_blank"}  from **@franzoni**: Operations -- option in the matrix --revertDqmio  and HI min bias 2k `operations`  created: 2014-02-24 16:34:44 merged: 2014-02-27 15:39:23

41. [2662](http://github.com/cms-sw/cmssw/pull/2662){:target="_blank"}  from **@degano**: GCC490 Fixes -- Fix unused function warnings in 7_1_X gcc490. `alca`  `analysis`  `db`  `reconstruction`  `simulation`  created: 2014-02-27 14:12:45 merged: 2014-02-27 15:13:33

42. [2648](http://github.com/cms-sw/cmssw/pull/2648){:target="_blank"}  from **@Dr15Jones**: Framework -- Removed FileInPath::isLocal to avoid user confusion `core`  created: 2014-02-26 21:58:00 merged: 2014-02-27 13:08:27

43. [2384](http://github.com/cms-sw/cmssw/pull/2384){:target="_blank"}  from **@gartung**: Multithreading fixes -- Make CSCTriggerPrimitivesProducer inherit from edm::one::producer becaus... `l1`  created: 2014-02-10 17:58:41 merged: 2014-02-27 10:56:45

44. [2587](http://github.com/cms-sw/cmssw/pull/2587){:target="_blank"}  from **@ktf**: Misc updates -- Refactor InputInfo to easily get the list of DAS queries. `operations`  created: 2014-02-21 17:15:00 merged: 2014-02-27 10:56:00

45. [2240](http://github.com/cms-sw/cmssw/pull/2240){:target="_blank"}  from **@ktf**: Calo towers speed-up `analysis`  `core`  `geometry`  `reconstruction`  created: 2014-01-30 15:24:26 merged: 2014-02-27 09:19:44

46. [2640](http://github.com/cms-sw/cmssw/pull/2640){:target="_blank"}  from **@Martin-Grunewald**: HLT -- StripCulsterUnpacking and 8E33 removal `hlt`  created: 2014-02-26 13:27:55 merged: 2014-02-26 22:08:30

47. [2579](http://github.com/cms-sw/cmssw/pull/2579){:target="_blank"}  from **@perrotta**: Validation/MuonIsolation -- Remove double counting of ovflw bin in Validation/MuonIsolation `dqm`  created: 2014-02-21 12:48:49 merged: 2014-02-26 16:10:43

48. [2635](http://github.com/cms-sw/cmssw/pull/2635){:target="_blank"}  from **@Dr15Jones**: FWCore/Framework -- Check for unrunnable schedules `core`  created: 2014-02-25 17:06:02 merged: 2014-02-26 16:09:53

49. [2497](http://github.com/cms-sw/cmssw/pull/2497){:target="_blank"}  from **@matteosan1**: Consumes migration -- Finalize migration to consumes for RecoEgamma/EgammaHLT\* `analysis`  `dqm`  `hlt`  `reconstruction`  `simulation`  created: 2014-02-17 16:19:15 merged: 2014-02-25 22:10:12

50. [2629](http://github.com/cms-sw/cmssw/pull/2629){:target="_blank"}  from **@jpavel**: DQM -- Update of the RecoTau validation discriminators `dqm`  created: 2014-02-25 10:46:28 merged: 2014-02-25 19:13:10

51. [2425](http://github.com/cms-sw/cmssw/pull/2425){:target="_blank"}  from **@ebouvier**: DQM -- Fix harvesting `dqm`  `simulation`  created: 2014-02-12 15:13:33 merged: 2014-02-25 15:57:44

52. [2574](http://github.com/cms-sw/cmssw/pull/2574){:target="_blank"}  from **@makortel**: DQM -- Fix/Silence warnings in tau trigger DQM `dqm`  created: 2014-02-21 09:15:31 merged: 2014-02-25 13:41:06

53. [2620](http://github.com/cms-sw/cmssw/pull/2620){:target="_blank"}  from **@wddgit**: FastSimulation -- Migrate Code to New Random Service Interface `fastsim`  created: 2014-02-24 17:04:09 merged: 2014-02-25 12:43:31

54. [2526](http://github.com/cms-sw/cmssw/pull/2526){:target="_blank"}  from **@TaiSakuma**: Reco -- Adding test code for RecoMET `reconstruction`  created: 2014-02-19 03:56:42 merged: 2014-02-25 08:25:28

55. [2586](http://github.com/cms-sw/cmssw/pull/2586){:target="_blank"}  from **@rovere**: Reco updates -- Fix bug when reading ProjectedRecHits from disk with Coarse option  `reconstruction`  created: 2014-02-21 16:08:38 merged: 2014-02-24 18:01:33

56. [2605](http://github.com/cms-sw/cmssw/pull/2605){:target="_blank"}  from **@inugent**: Generator fixes -- Update TTbar_GenLepAnalyzer.cc `generators`  created: 2014-02-24 00:16:18 merged: 2014-02-24 10:19:20

57. [2595](http://github.com/cms-sw/cmssw/pull/2595){:target="_blank"}  from **@wmtan**: Simulation fixes -- Fix exception to action table lifetime `simulation`  created: 2014-02-22 19:56:28 merged: 2014-02-24 09:39:18

58. [2565](http://github.com/cms-sw/cmssw/pull/2565){:target="_blank"}  from **@mkirsano**: Generators updates -- Fix ResidualDecay port from 62X `generators`  created: 2014-02-20 19:55:37 merged: 2014-02-23 22:11:00

59. [2599](http://github.com/cms-sw/cmssw/pull/2599){:target="_blank"}  from **@VinInn**: Misc -- Fix check on number of arguments in test PixelTriplets_InvPrbl_prec `reconstruction`  created: 2014-02-23 09:33:50 merged: 2014-02-23 13:43:01
