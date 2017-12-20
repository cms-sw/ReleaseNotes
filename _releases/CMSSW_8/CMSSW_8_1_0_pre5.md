---
layout: post
rel_link:  "8_1_0_pre5"
title:  "CMSSW_8_1_0_pre5"
date:   2016-05-17 09:11:04
categories: cmssw
relmajor: 8
relminor: 1
relsubminor: 0
relpre: _pre5
---

# CMSSW_8_1_0_pre5
#### Changes since CMSSW_8_1_0_pre4:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_1_0_pre4...CMSSW_8_1_0_pre5)



1. [14526](http://github.com/cms-sw/cmssw/pull/14526){:target="_blank"}  from **@kpedro88**: Fix setting the # of presamples for HcalUpgradeDataFrame. `simulation`  created: 2016-05-16 22:56:27 merged: 2016-05-17 09:07:05

2. [14515](http://github.com/cms-sw/cmssw/pull/14515){:target="_blank"}  from **@Dr15Jones**: Changed global bool in TinyXML to be atomic `core`  created: 2016-05-16 15:36:26 merged: 2016-05-17 07:59:35

3. [14504](http://github.com/cms-sw/cmssw/pull/14504){:target="_blank"}  from **@slava77**: numeric header include  for std::accumulate to fix gcc600 error `reconstruction`  created: 2016-05-14 10:25:47 merged: 2016-05-15 20:07:35

4. [14503](http://github.com/cms-sw/cmssw/pull/14503){:target="_blank"}  from **@davidlt**: Ignore ICC specific flags (-ax_, -wd_) `comparison`  `db`  created: 2016-05-14 08:55:57 merged: 2016-05-14 08:57:09

5. [14497](http://github.com/cms-sw/cmssw/pull/14497){:target="_blank"}  from **@Dr15Jones**: Special case for only one ProductResolver matching a blank Process re `core`  created: 2016-05-13 19:58:32 merged: 2016-05-14 05:27:10

6. [14495](http://github.com/cms-sw/cmssw/pull/14495){:target="_blank"}  from **@cms-l1t-offline**: Update L1T Ntuples for l1t-tsg-v6-cand  `l1`  created: 2016-05-13 14:51:25 merged: 2016-05-17 07:59:56

7. [14491](http://github.com/cms-sw/cmssw/pull/14491){:target="_blank"}  from **@vkhristenko**: HCAL DQM Updates. On top of 13805 `dqm`  created: 2016-05-13 10:52:24 merged: 2016-05-13 15:20:36

8. [14490](http://github.com/cms-sw/cmssw/pull/14490){:target="_blank"}  from **@ahinzmann**: Cleanup unused pixel CPE code `reconstruction`  created: 2016-05-13 08:38:08 merged: 2016-05-13 14:24:10

9. [14488](http://github.com/cms-sw/cmssw/pull/14488){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx52 Enable single detector reconstruction (useful for TB) `geometry`  `reconstruction`  created: 2016-05-12 21:53:10 merged: 2016-05-14 05:28:21

10. [14487](http://github.com/cms-sw/cmssw/pull/14487){:target="_blank"}  from **@cms-sw**: Fix wrong merge from 80X to 81X `hlt`  created: 2016-05-12 20:31:41 merged: 2016-05-12 20:58:48

11. [14476](http://github.com/cms-sw/cmssw/pull/14476){:target="_blank"}  from **@fwyzard**: L1TGlobalProducer: migrate to stream module (81x) `l1`  created: 2016-05-12 13:59:52 merged: 2016-05-13 07:11:16

12. [14475](http://github.com/cms-sw/cmssw/pull/14475){:target="_blank"}  from **@fwyzard**: HLT DQM: add protection for empty L1 uGT collection `dqm`  created: 2016-05-12 12:48:33 merged: 2016-05-12 14:35:00

13. [14472](http://github.com/cms-sw/cmssw/pull/14472){:target="_blank"}  from **@makortel**: Fix SeedExtensionTrajectoryFilter when it is disabled `reconstruction`  created: 2016-05-12 10:49:51 merged: 2016-05-15 20:07:46

14. [14468](http://github.com/cms-sw/cmssw/pull/14468){:target="_blank"}  from **@emiglior**: revert PixelDigitizerAlgorithm.DigitalReadout to False and CellsToKil `simulation`  created: 2016-05-12 07:49:46 merged: 2016-05-12 17:22:35

15. [14466](http://github.com/cms-sw/cmssw/pull/14466){:target="_blank"}  from **@VinInn**: fix det search tolerances for Cosmics `reconstruction`  created: 2016-05-12 05:06:50 merged: 2016-05-13 09:40:34

16. [14460](http://github.com/cms-sw/cmssw/pull/14460){:target="_blank"}  from **@Dr15Jones**:  Only construct tbb::task_scheduler_init once `core`  created: 2016-05-11 19:00:03 merged: 2016-05-12 07:58:57

17. [14458](http://github.com/cms-sw/cmssw/pull/14458){:target="_blank"}  from **@cms-l1t-offline**: L1T Minimum Bias Trigger `l1`  created: 2016-05-11 18:25:02 merged: 2016-05-12 14:38:09

18. [14455](http://github.com/cms-sw/cmssw/pull/14455){:target="_blank"}  from **@ianna**: Migrate GeomDetLess and GluedGeomDet to Geometry/CommonDetUnit `alca`  `analysis`  `dqm`  `fastsim`  `geometry`  `reconstruction`  created: 2016-05-11 14:48:28 merged: 2016-05-14 18:10:04

19. [14452](http://github.com/cms-sw/cmssw/pull/14452){:target="_blank"}  from **@davidlt**: ReferenceCounted\* must always be the first in base class list `reconstruction`  `simulation`  created: 2016-05-11 12:27:49 merged: 2016-05-14 18:10:34

20. [14450](http://github.com/cms-sw/cmssw/pull/14450){:target="_blank"}  from **@davidlt**: Move CaloTowerDetId selection rules to DataFormats/CaloTowers `reconstruction`  created: 2016-05-11 11:08:44 merged: 2016-05-12 07:58:34

21. [14441](http://github.com/cms-sw/cmssw/pull/14441){:target="_blank"}  from **@lgray**: Fix ordering bug in reworked PFBlockAlgo `reconstruction`  created: 2016-05-10 19:16:29 merged: 2016-05-12 17:23:18

22. [14439](http://github.com/cms-sw/cmssw/pull/14439){:target="_blank"}  from **@ianna**: Detector Description Include What You Use  `geometry`  created: 2016-05-10 16:36:37 merged: 2016-05-13 14:24:34

23. [14438](http://github.com/cms-sw/cmssw/pull/14438){:target="_blank"}  from **@davidlt**: SIMDVec: enable USE_SSEVECT for __INTEL_COMPILER `reconstruction`  created: 2016-05-10 16:06:53 merged: 2016-05-12 08:18:16

24. [14436](http://github.com/cms-sw/cmssw/pull/14436){:target="_blank"}  from **@ggovi**: Changes for O2O deployment and monitoring `db`  created: 2016-05-10 15:39:44 merged: 2016-05-11 12:17:37

25. [14435](http://github.com/cms-sw/cmssw/pull/14435){:target="_blank"}  from **@davidlt**: Fix explicit GzInputStream::operator bool() const `comparison`  `l1`  created: 2016-05-10 13:09:52 merged: 2016-05-11 17:36:50

26. [14434](http://github.com/cms-sw/cmssw/pull/14434){:target="_blank"}  from **@davidlt**: Fix explicit GzInputStream::operator bool() const `comparison`  `l1`  created: 2016-05-10 13:06:34 merged: 2016-05-14 05:28:46

27. [14431](http://github.com/cms-sw/cmssw/pull/14431){:target="_blank"}  from **@cms-l1t-offline**: Bugfix of Giovanni Petrucciani for runaway combinatorics `l1`  created: 2016-05-10 10:04:26 merged: 2016-05-10 10:05:51

28. [14429](http://github.com/cms-sw/cmssw/pull/14429){:target="_blank"}  from **@cms-sw**: Revert "L1TGlobalProducer: migrate to stream module (80x)" `comparison`  `l1`  created: 2016-05-10 09:35:17 merged: 2016-05-10 09:36:06

29. [14428](http://github.com/cms-sw/cmssw/pull/14428){:target="_blank"}  from **@ianna**: Clean up clang warnings `geometry`  created: 2016-05-10 08:59:01 merged: 2016-05-10 16:12:33

30. [14426](http://github.com/cms-sw/cmssw/pull/14426){:target="_blank"}  from **@avetisya**: Fixing L1 seed module name `hlt`  created: 2016-05-10 04:06:25 merged: 2016-05-10 12:55:17

31. [14425](http://github.com/cms-sw/cmssw/pull/14425){:target="_blank"}  from **@avetisya**: Fixing L1 seed module name `hlt`  created: 2016-05-10 03:56:57 merged: 2016-05-11 07:55:51

32. [14424](http://github.com/cms-sw/cmssw/pull/14424){:target="_blank"}  from **@calabria**: small bug fix me0 background `simulation`  created: 2016-05-10 00:13:48 merged: 2016-05-10 16:11:28

33. [14423](http://github.com/cms-sw/cmssw/pull/14423){:target="_blank"}  from **@civanch**: fixed ZDC test `dqm`  `simulation`  created: 2016-05-09 17:37:29 merged: 2016-05-13 08:12:35

34. [14418](http://github.com/cms-sw/cmssw/pull/14418){:target="_blank"}  from **@kpedro88**: Premixing for QIE10 `simulation`  created: 2016-05-09 16:25:42 merged: 2016-05-10 16:11:15

35. [14416](http://github.com/cms-sw/cmssw/pull/14416){:target="_blank"}  from **@davidlt**: Add missing selection rules (GCC 6) `reconstruction`  created: 2016-05-09 13:42:37 merged: 2016-05-10 12:54:57

36. [14414](http://github.com/cms-sw/cmssw/pull/14414){:target="_blank"}  from **@cms-l1t-offline**: Fix HLT-L1T seed index to be from begin BxVector `hlt`  created: 2016-05-09 13:25:43 merged: 2016-05-09 14:03:11

37. [14413](http://github.com/cms-sw/cmssw/pull/14413){:target="_blank"}  from **@mtosi**: add track hit eff monitoring vs BX `dqm`  created: 2016-05-09 12:58:55 merged: 2016-05-10 16:20:39

38. [14412](http://github.com/cms-sw/cmssw/pull/14412){:target="_blank"}  from **@archiron**: Electron validation 81X preshower `dqm`  created: 2016-05-09 12:42:15 merged: 2016-05-10 12:54:44

39. [14408](http://github.com/cms-sw/cmssw/pull/14408){:target="_blank"}  from **@dmitrijus**: Add DQMStore::getElement whichs throws an exception instead of a nullptr (81x) `dqm`  created: 2016-05-09 08:18:10 merged: 2016-05-10 12:51:48

40. [14407](http://github.com/cms-sw/cmssw/pull/14407){:target="_blank"}  from **@dmitrijus**: Add DQMStore::getElement whichs throws an exception instead of a nullptr (80x)  `dqm`  created: 2016-05-09 08:16:57 merged: 2016-05-11 08:17:01

41. [14405](http://github.com/cms-sw/cmssw/pull/14405){:target="_blank"}  from **@civanch**: Clean-up Sim Exceptions `simulation`  created: 2016-05-07 19:38:34 merged: 2016-05-09 07:19:51

42. [14404](http://github.com/cms-sw/cmssw/pull/14404){:target="_blank"}  from **@cippy**: Optimization of ECAL Pi0 stream timing `hlt`  created: 2016-05-07 16:16:04 merged: 2016-05-09 07:14:56

43. [14401](http://github.com/cms-sw/cmssw/pull/14401){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx81 Correct the depth index for ieta=17 `geometry`  created: 2016-05-06 16:27:08 merged: 2016-05-10 16:10:52

44. [14396](http://github.com/cms-sw/cmssw/pull/14396){:target="_blank"}  from **@Dr15Jones**: Added noexcept(false) to module destructors for gcc 6 `alca`  `analysis`  `core`  `db`  `dqm`  `generators`  `reconstruction`  `simulation`  `visualization`  created: 2016-05-06 15:01:53 merged: 2016-05-12 07:56:24

45. [14392](http://github.com/cms-sw/cmssw/pull/14392){:target="_blank"}  from **@cms-l1t-offline**: L1REPAC 2016 2015 81x (clean history) `l1`  `operations`  created: 2016-05-06 10:23:17 merged: 2016-05-07 15:27:00

46. [14391](http://github.com/cms-sw/cmssw/pull/14391){:target="_blank"}  from **@dildick**: Correctly configure CSC trigger primitive emulator for Run2 (81X) `l1`  created: 2016-05-05 21:58:40 merged: 2016-05-14 18:12:09

47. [14387](http://github.com/cms-sw/cmssw/pull/14387){:target="_blank"}  from **@cms-l1t-offline**: L1REPACK 2016 2015 `l1`  `operations`  created: 2016-05-05 18:33:08 merged: 2016-05-11 08:25:34

48. [14386](http://github.com/cms-sw/cmssw/pull/14386){:target="_blank"}  from **@bapavlov**: fixing Phase2 RPC local reco `reconstruction`  created: 2016-05-05 16:21:55 merged: 2016-05-11 15:27:59

49. [14384](http://github.com/cms-sw/cmssw/pull/14384){:target="_blank"}  from **@kskovpen**: Keep muon parents in prunedGenParticles collection `analysis`  `reconstruction`  created: 2016-05-05 09:05:57 merged: 2016-05-12 07:55:39

50. [14383](http://github.com/cms-sw/cmssw/pull/14383){:target="_blank"}  from **@igv4321**: Initial implementation of the pre-reco stage for the Phase 1 HF reco `reconstruction`  created: 2016-05-05 08:44:50 merged: 2016-05-10 16:22:55

51. [14381](http://github.com/cms-sw/cmssw/pull/14381){:target="_blank"}  from **@barvic**: CSC Unpacker fixes for 2016 TMB/OTMB firmware updates (81X) `reconstruction`  created: 2016-05-04 17:54:43 merged: 2016-05-10 12:51:33

52. [14380](http://github.com/cms-sw/cmssw/pull/14380){:target="_blank"}  from **@barvic**: CSC Unpacker fixes for 2016 TMB/OTMB firmware updates (80X) `reconstruction`  created: 2016-05-04 15:53:43 merged: 2016-05-11 17:42:35

53. [14379](http://github.com/cms-sw/cmssw/pull/14379){:target="_blank"}  from **@fwyzard**: TriggerRatesMonitor: migrate to Stage 2 (81x) `dqm`  created: 2016-05-04 15:42:00 merged: 2016-05-09 11:28:07

54. [14378](http://github.com/cms-sw/cmssw/pull/14378){:target="_blank"}  from **@fwyzard**: TriggerRatesMonitor: migrate to Stage 2 (80x) `dqm`  created: 2016-05-04 15:41:55 merged: 2016-05-09 14:04:15

55. [14372](http://github.com/cms-sw/cmssw/pull/14372){:target="_blank"}  from **@makortel**: Update tracking MC validation scripts `dqm`  created: 2016-05-04 12:14:22 merged: 2016-05-13 08:12:50

56. [14366](http://github.com/cms-sw/cmssw/pull/14366){:target="_blank"}  from **@thomaslenzi**: Fixed clusterizer for Threaded version of CMSSW `reconstruction`  created: 2016-05-04 08:33:18 merged: 2016-05-06 08:44:21

57. [14364](http://github.com/cms-sw/cmssw/pull/14364){:target="_blank"}  from **@cms-l1t-offline**: Update L1T to l1t-tsg-v6-cand (81x) `l1`  created: 2016-05-04 02:07:25 merged: 2016-05-13 14:30:57

58. [14363](http://github.com/cms-sw/cmssw/pull/14363){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx80 Get rid of parameter set HcalRelabel `geometry`  `simulation`  created: 2016-05-04 01:30:32 merged: 2016-05-10 16:09:57

59. [14360](http://github.com/cms-sw/cmssw/pull/14360){:target="_blank"}  from **@wddgit**: Add new signal to ActivityRegistry around when a `core`  created: 2016-05-03 20:23:29 merged: 2016-05-06 08:44:45

60. [14359](http://github.com/cms-sw/cmssw/pull/14359){:target="_blank"}  from **@cippy**: optimized CPU timing of ECAL Pi0 stream `hlt`  created: 2016-05-03 15:50:29 merged: 2016-05-04 12:10:18

61. [14358](http://github.com/cms-sw/cmssw/pull/14358){:target="_blank"}  from **@cippy**: optimized CPU timing of ECAL Pi0 stream `hlt`  created: 2016-05-03 15:21:11 merged: 2016-05-11 08:16:50

62. [14354](http://github.com/cms-sw/cmssw/pull/14354){:target="_blank"}  from **@JanFSchulte**: Change of StoN cut in hit selection for SiPixAli in PCL + 0T configs for the same `alca`  created: 2016-05-03 13:18:45 merged: 2016-05-07 15:54:20

63. [14351](http://github.com/cms-sw/cmssw/pull/14351){:target="_blank"}  from **@fwyzard**: L1TGlobalProducer: migrate to stream module (80x) `l1`  created: 2016-05-03 13:04:50 merged: 2016-05-07 16:10:21

64. [14350](http://github.com/cms-sw/cmssw/pull/14350){:target="_blank"}  from **@slava77**: sync with 80X and cleanup of obsolete T0 processing scenarios `alca`  `dqm`  `operations`  `reconstruction`  created: 2016-05-03 12:13:02 merged: 2016-05-04 11:55:21

65. [14349](http://github.com/cms-sw/cmssw/pull/14349){:target="_blank"}  from **@fwyzard**: TriggerBxMonitor: migrate to Stage 2 (81x) `dqm`  created: 2016-05-03 12:11:18 merged: 2016-05-04 13:24:54

66. [14348](http://github.com/cms-sw/cmssw/pull/14348){:target="_blank"}  from **@deguio**: fix EDMtoMEConverter for multiRun harvesting `dqm`  created: 2016-05-03 11:37:07 merged: 2016-05-07 15:59:01

67. [14344](http://github.com/cms-sw/cmssw/pull/14344){:target="_blank"}  from **@VinInn**: avoid redundant computations in StripCPE `core`  `reconstruction`  created: 2016-05-03 10:13:49 merged: 2016-05-07 15:29:40

68. [14341](http://github.com/cms-sw/cmssw/pull/14341){:target="_blank"}  from **@gpetruc**: SCEnergyCorrectorSemiParm: don't cache ES objects the wrong way `reconstruction`  created: 2016-05-03 09:16:25 merged: 2016-05-04 12:15:05

69. [14340](http://github.com/cms-sw/cmssw/pull/14340){:target="_blank"}  from **@gpetruc**: SCEnergyCorrectorSemiParm: don't cache ES objects the wrong way `reconstruction`  created: 2016-05-03 09:15:02 merged: 2016-05-07 15:42:54

70. [14338](http://github.com/cms-sw/cmssw/pull/14338){:target="_blank"}  from **@fwyzard**: TriggerBxMonitor: migrate to Stage 2 (80x) `dqm`  created: 2016-05-03 09:06:27 merged: 2016-05-07 15:43:25

71. [14333](http://github.com/cms-sw/cmssw/pull/14333){:target="_blank"}  from **@kpedro88**: remove unneeded EE geometry from EcalRecHitWorkerRecover `reconstruction`  created: 2016-05-02 20:10:41 merged: 2016-05-04 12:18:56

72. [14331](http://github.com/cms-sw/cmssw/pull/14331){:target="_blank"}  from **@lathomas**: Filling the fillDescription method of CaloRecHitsBeamHaloCleaned and  `reconstruction`  created: 2016-05-02 19:44:23 merged: 2016-05-04 13:18:25

73. [14327](http://github.com/cms-sw/cmssw/pull/14327){:target="_blank"}  from **@makortel**: Improve low-pT performance of "quadruplets by propagation", and use it in phase1 tracking instead of "triplet merging" `reconstruction`  created: 2016-05-02 15:09:57 merged: 2016-05-07 15:30:03

74. [14324](http://github.com/cms-sw/cmssw/pull/14324){:target="_blank"}  from **@cms-tsg-storm**: Towards the first hlt menu for 2016 - 81X `hlt`  created: 2016-05-02 14:51:08 merged: 2016-05-09 07:16:43

75. [14323](http://github.com/cms-sw/cmssw/pull/14323){:target="_blank"}  from **@cms-l1t-offline**: Updates to L1T packer needed to simultaneously pack GT inputs and GMT/Calo ouputs `l1`  created: 2016-05-02 14:21:45 merged: 2016-05-11 08:15:57

76. [14322](http://github.com/cms-sw/cmssw/pull/14322){:target="_blank"}  from **@schneiml**: SiPixelMonitorTrack invalid TSOS crash fix `alca`  `dqm`  created: 2016-05-02 13:58:58 merged: 2016-05-07 15:43:56

77. [14320](http://github.com/cms-sw/cmssw/pull/14320){:target="_blank"}  from **@cms-l1t-offline**: Update L1Ntuples to l1t-tsg-v5, and address memory management problems. `l1`  created: 2016-05-02 11:50:08 merged: 2016-05-11 08:15:17

78. [14318](http://github.com/cms-sw/cmssw/pull/14318){:target="_blank"}  from **@schneiml**: TrackerMonitorTrack: Fix side for TID so that TID/MINUS histograms appear. `dqm`  created: 2016-05-02 08:58:35 merged: 2016-05-07 15:44:08

79. [14316](http://github.com/cms-sw/cmssw/pull/14316){:target="_blank"}  from **@sushilchauhan**: update of dqm  client config for online beam spot, running pixel trac `dqm`  created: 2016-04-30 20:18:52 merged: 2016-05-07 15:35:38

80. [14315](http://github.com/cms-sw/cmssw/pull/14315){:target="_blank"}  from **@sushilchauhan**: update dqm  client config for online beam spot running pixel tracking `dqm`  created: 2016-04-30 20:14:30 merged: 2016-05-11 08:14:57

81. [14313](http://github.com/cms-sw/cmssw/pull/14313){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx78 Correct access of HcalTopology `alca`  `db`  `geometry`  `l1`  created: 2016-04-30 13:58:26 merged: 2016-05-12 10:52:05

82. [14306](http://github.com/cms-sw/cmssw/pull/14306){:target="_blank"}  from **@jshlee**: bug fix for Me0 segments `reconstruction`  created: 2016-04-29 15:50:42 merged: 2016-05-10 12:42:04

83. [14305](http://github.com/cms-sw/cmssw/pull/14305){:target="_blank"}  from **@jshlee**: Gem Geometry fix for 81x `geometry`  `simulation`  created: 2016-04-29 15:20:57 merged: 2016-05-04 12:19:12

84. [14295](http://github.com/cms-sw/cmssw/pull/14295){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca41 Change the name of L1GTSeed (backport from 8_1_X) `alca`  created: 2016-04-28 22:27:37 merged: 2016-05-02 06:04:00

85. [14287](http://github.com/cms-sw/cmssw/pull/14287){:target="_blank"}  from **@jruizvar**: Implement HLT_TkMu50_v into EXO DQM (80X) `dqm`  created: 2016-04-27 22:03:21 merged: 2016-05-07 15:57:52

86. [14286](http://github.com/cms-sw/cmssw/pull/14286){:target="_blank"}  from **@jruizvar**: Implement HLT_TkMu50_v into EXO DQM (81X) `dqm`  created: 2016-04-27 22:03:11 merged: 2016-05-04 11:54:15

87. [14285](http://github.com/cms-sw/cmssw/pull/14285){:target="_blank"}  from **@cms-l1t-offline**: Updates to L1TCaloLayer1 and unpacker (80X) `l1`  created: 2016-04-27 20:48:03 merged: 2016-05-11 08:14:31

88. [14283](http://github.com/cms-sw/cmssw/pull/14283){:target="_blank"}  from **@davidsheffield**: Quietly return when producer fails to find input collection `hlt`  created: 2016-04-27 20:22:15 merged: 2016-05-04 13:17:31

89. [14281](http://github.com/cms-sw/cmssw/pull/14281){:target="_blank"}  from **@mmusich**: Update Global Tag for Collisions2016_v1 L1T menu and splitting Ecal Pedestal tags `alca`  created: 2016-04-27 19:54:21 merged: 2016-05-11 08:14:14

90. [14279](http://github.com/cms-sw/cmssw/pull/14279){:target="_blank"}  from **@duanders**: Jet ID and b-tag information for Scouting Calojets (80X) `core`  `hlt`  created: 2016-04-27 19:48:34 merged: 2016-05-02 06:05:16

91. [14272](http://github.com/cms-sw/cmssw/pull/14272){:target="_blank"}  from **@silviodonato**:  Pixel PU jet update (backport of #14269 in 80X) `hlt`  created: 2016-04-27 15:55:02 merged: 2016-05-02 07:12:43

92. [14267](http://github.com/cms-sw/cmssw/pull/14267){:target="_blank"}  from **@makortel**: Remove obsolete customiseForRunI `reconstruction`  `simulation`  created: 2016-04-27 09:10:36 merged: 2016-05-09 11:37:26

93. [14260](http://github.com/cms-sw/cmssw/pull/14260){:target="_blank"}  from **@deguio**: fix DQMExample `dqm`  created: 2016-04-26 16:58:10 merged: 2016-05-04 11:53:36

94. [14258](http://github.com/cms-sw/cmssw/pull/14258){:target="_blank"}  from **@acimmino**: RPC DQM ONLINE Patch for Active Channel Fraction `dqm`  created: 2016-04-26 16:53:14 merged: 2016-05-07 15:47:55

95. [14249](http://github.com/cms-sw/cmssw/pull/14249){:target="_blank"}  from **@makortel**: Migrate tracking DQM to phase1 and enable it `dqm`  created: 2016-04-26 12:59:21 merged: 2016-05-13 08:14:36

96. [14248](http://github.com/cms-sw/cmssw/pull/14248){:target="_blank"}  from **@makortel**: Add plots vs. seeding layer set to MultiTrackValidator `dqm`  `reconstruction`  created: 2016-04-26 11:58:48 merged: 2016-05-04 11:52:31

97. [14218](http://github.com/cms-sw/cmssw/pull/14218){:target="_blank"}  from **@fioriNTU**: Add protection to consider only Strip hits `dqm`  created: 2016-04-22 19:21:04 merged: 2016-05-07 15:47:39

98. [14217](http://github.com/cms-sw/cmssw/pull/14217){:target="_blank"}  from **@fioriNTU**: fix to fill properly the rec-hits Tracker maps 81X `dqm`  created: 2016-04-22 19:02:42 merged: 2016-05-10 12:40:38

99. [14214](http://github.com/cms-sw/cmssw/pull/14214){:target="_blank"}  from **@jpazzini**: Fixes involving DQM/Physics for Exo `dqm`  created: 2016-04-22 16:14:03 merged: 2016-05-09 11:37:45

100. [14210](http://github.com/cms-sw/cmssw/pull/14210){:target="_blank"}  from **@dimattia**: Calibration update 80 x `alca`  created: 2016-04-22 14:19:11 merged: 2016-05-02 05:57:33

101. [14208](http://github.com/cms-sw/cmssw/pull/14208){:target="_blank"}  from **@mbandrews**: Add pulse max check parameter `dqm`  created: 2016-04-22 14:14:28 merged: 2016-05-07 15:57:40

102. [14150](http://github.com/cms-sw/cmssw/pull/14150){:target="_blank"}  from **@rovere**: Enable OfflinePV and Beamspot in trackingLowPU era `dqm`  `reconstruction`  created: 2016-04-19 16:08:33 merged: 2016-05-11 08:28:16

103. [14147](http://github.com/cms-sw/cmssw/pull/14147){:target="_blank"}  from **@sarafiorendi**: update muon validation plots to Stage2L1 + update HLT DQM plots (backport of #14146) `dqm`  created: 2016-04-19 13:29:14 merged: 2016-05-11 08:14:02

104. [14145](http://github.com/cms-sw/cmssw/pull/14145){:target="_blank"}  from **@davidlt**: Misc. cleanup for CondFormats/HcalObjects (UNIX format & style) `alca`  `db`  created: 2016-04-19 12:12:51 merged: 2016-05-14 05:30:17

105. [14136](http://github.com/cms-sw/cmssw/pull/14136){:target="_blank"}  from **@sarafiorendi**: modify L2MuonSeedGeneratorFromL1T to deal with possible L1 zero charge (backport) `reconstruction`  created: 2016-04-19 10:11:24 merged: 2016-05-02 05:57:57

106. [14097](http://github.com/cms-sw/cmssw/pull/14097){:target="_blank"}  from **@jwwetzel**: HF Radiation Damage Simulation V2016 `alca`  `simulation`  created: 2016-04-15 17:23:16 merged: 2016-05-10 12:40:26

107. [14008](http://github.com/cms-sw/cmssw/pull/14008){:target="_blank"}  from **@silviodonato**: Change of VBF Hbb HLT path names in DQM code (online,offline,relval) (backport of #13966 in 80X) `dqm`  created: 2016-04-10 10:23:32 merged: 2016-05-02 05:59:53

108. [13993](http://github.com/cms-sw/cmssw/pull/13993){:target="_blank"}  from **@Dr15Jones**: Cleanup sim mergeable products `generators`  created: 2016-04-08 14:49:46 merged: 2016-05-10 16:56:14

109. [13973](http://github.com/cms-sw/cmssw/pull/13973){:target="_blank"}  from **@fioriNTU**: improve TkMaps 81X `dqm`  created: 2016-04-07 12:50:45 merged: 2016-05-11 14:06:05

110. [13951](http://github.com/cms-sw/cmssw/pull/13951){:target="_blank"}  from **@kirschen**: add L2L3Residual as know correction level to JetCorrector[Calculator] `analysis`  `db`  created: 2016-04-06 10:05:37 merged: 2016-05-07 15:56:46

111. [13805](http://github.com/cms-sw/cmssw/pull/13805){:target="_blank"}  from **@vkhristenko**: Online HCAL DQM adding a new application `dqm`  created: 2016-03-22 21:21:58 merged: 2016-05-11 13:23:46

112. [13759](http://github.com/cms-sw/cmssw/pull/13759){:target="_blank"}  from **@gouskos**: barrel vs ladder in roc level in 81x `dqm`  created: 2016-03-17 16:17:34 merged: 2016-05-11 08:03:27

113. [13421](http://github.com/cms-sw/cmssw/pull/13421){:target="_blank"}  from **@mtosi**: update trajectory filters (minNumberOfHits --> minNumberOfHitsForLoopers) `hlt`  `reconstruction`  created: 2016-02-22 09:56:45 merged: 2016-05-11 17:37:32

#### CMSDIST Changes between Tags REL/CMSSW_8_1_0_pre4/slc6_amd64_gcc530 and REL/CMSSW_8_1_0_pre5/slc6_amd64_gcc530:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_1_0_pre4/slc6_amd64_gcc530...REL/CMSSW_8_1_0_pre5/slc6_amd64_gcc530)



1. [2297](http://github.com/cms-sw/cmsdist/pull/2297){:target="_blank"}  from **@degano**: Update SLHCUpgradeSimulations/Geometry data. created: 2016-05-17 07:43:33 merged: 2016-05-17 07:43:42

2. [2288](http://github.com/cms-sw/cmsdist/pull/2288){:target="_blank"}  from **@smuzaffar**: Updated root to tip e4b3d70 of v6-06-00 patches branch created: 2016-05-11 21:51:19 merged: 2016-05-14 22:09:26

3. [2286](http://github.com/cms-sw/cmsdist/pull/2286){:target="_blank"}  from **@degano**: Fix data files for SLHCUpgradeSimulations/Geometry created: 2016-05-11 12:14:31 merged: 2016-05-11 12:14:37

4. [2282](http://github.com/cms-sw/cmsdist/pull/2282){:target="_blank"}  from **@cms-sw**: Update utm to r45210-xsd310-patch created: 2016-05-06 07:46:23 merged: 2016-05-06 16:30:59

5. [2281](http://github.com/cms-sw/cmsdist/pull/2281){:target="_blank"}  from **@cms-sw**: Update data-L1Trigger-L1TCalorimeter.spec created: 2016-05-04 07:27:49 merged: 2016-05-09 17:22:23

6. [2274](http://github.com/cms-sw/cmsdist/pull/2274){:target="_blank"}  from **@smuzaffar**: Updated root to tip of 86c0d59 created: 2016-04-27 08:52:26 merged: 2016-05-10 15:26:01
