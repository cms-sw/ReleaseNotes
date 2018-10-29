---
layout: post
rel_link:  "10_4_0_pre1"
title:  "CMSSW_10_4_0_pre1"
date:   2018-10-28 11:56:36
categories: cmssw
relmajor: 10
relminor: 4
relsubminor: 0
relpre: _pre1
---

# CMSSW_10_4_0_pre1
#### Changes since CMSSW_10_3_0_pre6:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_10_3_0_pre6...CMSSW_10_4_0_pre1)



1. [25011](http://github.com/cms-sw/cmssw/pull/25011){:target="_blank"}  from **@slava77**: streamline addition of centrality and pixel tracks for HI `operations`  created: 2018-10-26 06:01:07 merged: 2018-10-26 12:34:55



2. [25007](http://github.com/cms-sw/cmssw/pull/25007){:target="_blank"}  from **@tocheng**: Configure HcalMinBias AlCaReco for heavy Ion 2018 `alca`  `dqm`  created: 2018-10-25 21:57:41 merged: 2018-10-26 09:51:37



3. [25004](http://github.com/cms-sw/cmssw/pull/25004){:target="_blank"}  from **@tocheng**: Configure DtCalib AlCaReco for heavy Ion 2018 `alca`  created: 2018-10-25 19:49:47 merged: 2018-10-26 07:07:12



4. [25000](http://github.com/cms-sw/cmssw/pull/25000){:target="_blank"}  from **@mandrenguyen**: Add pixel tracks to XeXe era `operations`  created: 2018-10-25 16:45:50 merged: 2018-10-26 04:11:17



5. [24996](http://github.com/cms-sw/cmssw/pull/24996){:target="_blank"}  from **@mmusich**: [10.4.X] customize the DQM tracking only sequence when run in trackingOnlyEra_Run2_2018_pp_on_AA to remove hiConformalPixelTracks `dqm`  `operations`  created: 2018-10-25 13:01:32 merged: 2018-10-26 08:19:33



6. [24991](http://github.com/cms-sw/cmssw/pull/24991){:target="_blank"}  from **@casarsa**: MTD simulation: fix to the BTL digitization `simulation`  `upgrade`  created: 2018-10-25 09:05:34 merged: 2018-10-26 19:12:35



7. [24986](http://github.com/cms-sw/cmssw/pull/24986){:target="_blank"}  from **@apana**: Update uGT unpacker to pick up new HI centrality values `l1`  created: 2018-10-24 17:41:01 merged: 2018-10-25 19:40:57



8. [24985](http://github.com/cms-sw/cmssw/pull/24985){:target="_blank"}  from **@bsunanda**: Phase2-hgx164 Enable saving Digi results of HFNose and instead of PR #24913 `dqm`  `geometry`  `operations`  `reconstruction`  `simulation`  `upgrade`  created: 2018-10-24 16:14:55 merged: 2018-10-25 12:33:46



9. [24982](http://github.com/cms-sw/cmssw/pull/24982){:target="_blank"}  from **@cms-sw**: Added lxml and bs4 in python unit tests `analysis`  created: 2018-10-24 08:51:44 merged: 2018-10-28 08:03:22



10. [24980](http://github.com/cms-sw/cmssw/pull/24980){:target="_blank"}  from **@mdhildreth**: fix memory leak `l1`  `simulation`  created: 2018-10-23 16:05:03 merged: 2018-10-24 19:02:37



11. [24975](http://github.com/cms-sw/cmssw/pull/24975){:target="_blank"}  from **@mmusich**: [10.4.X] add missing eventSetupPathsKey swap for HI 2018 `alca`  created: 2018-10-23 11:47:29 merged: 2018-10-24 08:24:21



12. [24971](http://github.com/cms-sw/cmssw/pull/24971){:target="_blank"}  from **@cedricpri**: Moved to new muon validation web repository `dqm`  created: 2018-10-23 11:17:31 merged: 2018-10-24 15:34:47



13. [24964](http://github.com/cms-sw/cmssw/pull/24964){:target="_blank"}  from **@gartung**: Utilities/StaticAnalyzer: include dablooms library header as extern "C" `core`  created: 2018-10-22 17:15:13 merged: 2018-10-23 08:51:41



14. [24963](http://github.com/cms-sw/cmssw/pull/24963){:target="_blank"}  from **@argiro**: Trivial bug fixes to record  EcalSampleMask `alca`  `db`  created: 2018-10-22 16:18:28 merged: 2018-10-24 08:18:40



15. [24961](http://github.com/cms-sw/cmssw/pull/24961){:target="_blank"}  from **@pieterdavid**: Fix APV shot cleaner for 10bit `reconstruction`  created: 2018-10-22 15:59:24 merged: 2018-10-25 09:55:01



16. [24959](http://github.com/cms-sw/cmssw/pull/24959){:target="_blank"}  from **@schneiml**: HCAL DQClient: Reset _vhashCrates for each run. `dqm`  created: 2018-10-22 15:34:24 merged: 2018-10-24 15:36:27



17. [24958](http://github.com/cms-sw/cmssw/pull/24958){:target="_blank"}  from **@mandrenguyen**: Bug fixes to Run2_2018_pp_on_AA in EI and DQM `analysis`  `dqm`  `reconstruction`  created: 2018-10-22 15:20:11 merged: 2018-10-25 08:26:45



18. [24957](http://github.com/cms-sw/cmssw/pull/24957){:target="_blank"}  from **@bsunanda**: Phase2-hgx163 Update material property as discussed in DPG `geometry`  `upgrade`  created: 2018-10-22 15:16:39 merged: 2018-10-24 19:05:56



19. [24955](http://github.com/cms-sw/cmssw/pull/24955){:target="_blank"}  from **@schneiml**: SiStripMonitorClient: Fix caching logic in SiStripBadComponentInfo `dqm`  created: 2018-10-22 08:10:14 merged: 2018-10-24 08:02:10



20. [24954](http://github.com/cms-sw/cmssw/pull/24954){:target="_blank"}  from **@fabiocos**: MTD: fix TimingSD calculation of post-step local point and time slice unit definition, add SD geometry dump module `geometry`  `simulation`  `upgrade`  created: 2018-10-21 07:17:28 merged: 2018-10-25 09:58:37



21. [24953](http://github.com/cms-sw/cmssw/pull/24953){:target="_blank"}  from **@wddgit**: Prepare for concurrent IOVs, miscellaneous packages `analysis`  `reconstruction`  `upgrade`  created: 2018-10-19 21:29:57 merged: 2018-10-23 08:30:27



22. [24952](http://github.com/cms-sw/cmssw/pull/24952){:target="_blank"}  from **@muhammadansariqbal**: Tracker Alignment - Fix to conddb function in validation and migration to common EOS storage `alca`  created: 2018-10-19 20:09:40 merged: 2018-10-23 20:34:46



23. [24949](http://github.com/cms-sw/cmssw/pull/24949){:target="_blank"}  from **@cms-sw**: add test for import pydablooms `analysis`  created: 2018-10-19 16:37:20 merged: 2018-10-20 07:03:27



24. [24946](http://github.com/cms-sw/cmssw/pull/24946){:target="_blank"}  from **@gartung**: Update Utilities/StaticAnalyzers to use dablooms library added in CMSDIST PR 4436 `core`  created: 2018-10-19 14:29:42 merged: 2018-10-21 08:15:56



25. [24944](http://github.com/cms-sw/cmssw/pull/24944){:target="_blank"}  from **@threus**: online DQM GT update `dqm`  created: 2018-10-19 13:01:57 merged: 2018-10-23 08:41:19



26. [24943](http://github.com/cms-sw/cmssw/pull/24943){:target="_blank"}  from **@mondalspandan**: Fix numerical bug that causes NaNs in DeepCSV output `reconstruction`  created: 2018-10-19 12:46:13 merged: 2018-10-23 08:39:27



27. [24938](http://github.com/cms-sw/cmssw/pull/24938){:target="_blank"}  from **@fwyzard**: Skip tests if no CUDA devices are present `reconstruction`  created: 2018-10-19 11:50:34 merged: 2018-10-24 07:08:06



28. [24937](http://github.com/cms-sw/cmssw/pull/24937){:target="_blank"}  from **@guitargeek**: [10_4_X] Fixed copy-paste typo in Spring15 photon MVA weight file names `reconstruction`  created: 2018-10-19 09:17:27 merged: 2018-10-23 08:36:35



29. [24931](http://github.com/cms-sw/cmssw/pull/24931){:target="_blank"}  from **@bundocka**: Further CaloL2 O2O updates (supersedes #24922) `l1`  created: 2018-10-18 17:51:06 merged: 2018-10-24 07:26:11



30. [24930](http://github.com/cms-sw/cmssw/pull/24930){:target="_blank"}  from **@wddgit**: Prepare for concurrent IOVs in Geometry `geometry`  `upgrade`  created: 2018-10-18 16:48:57 merged: 2018-10-23 08:24:10



31. [24929](http://github.com/cms-sw/cmssw/pull/24929){:target="_blank"}  from **@makortel**: Move HGCal and MTD event content customizations to SimCalorimetry and SimFastTiming `operations`  `simulation`  `upgrade`  created: 2018-10-18 14:56:14 merged: 2018-10-24 07:59:36



32. [24925](http://github.com/cms-sw/cmssw/pull/24925){:target="_blank"}  from **@mmusich**: [10.4.X] Fix testProduceSystematicMisalignment and add unit tests `alca`  created: 2018-10-18 11:52:22 merged: 2018-10-24 19:04:32



33. [24917](http://github.com/cms-sw/cmssw/pull/24917){:target="_blank"}  from **@bsunanda**: Run2-hcx186 Treat the subdetid method correctly `alca`  `geometry`  `l1`  `simulation`  created: 2018-10-17 20:30:01 merged: 2018-10-26 19:09:10



34. [24916](http://github.com/cms-sw/cmssw/pull/24916){:target="_blank"}  from **@lpernie**: [10.4.X][Change GT] Update HI MC ECAL GT + 2019 GT Geom. fix `alca`  created: 2018-10-17 17:15:29 merged: 2018-10-20 02:09:16



35. [24914](http://github.com/cms-sw/cmssw/pull/24914){:target="_blank"}  from **@wddgit**: Remove const_cast from SiPixelESProducers `alca`  created: 2018-10-17 15:47:27 merged: 2018-10-23 13:25:00



36. [24911](http://github.com/cms-sw/cmssw/pull/24911){:target="_blank"}  from **@wddgit**: Prepare for concurrent IOVs, Fireworks & FastSimulation `fastsim`  `visualization`  created: 2018-10-17 15:13:27 merged: 2018-10-19 08:49:46



37. [24910](http://github.com/cms-sw/cmssw/pull/24910){:target="_blank"}  from **@icali**: Raw data remapper sequence `daq`  `operations`  `pdmv`  `upgrade`  created: 2018-10-17 15:05:22 merged: 2018-10-18 20:02:49



38. [24906](http://github.com/cms-sw/cmssw/pull/24906){:target="_blank"}  from **@cardinia**: Implemented option to run jobs in parallel for PV validation `alca`  created: 2018-10-17 13:51:49 merged: 2018-10-24 07:46:08



39. [24905](http://github.com/cms-sw/cmssw/pull/24905){:target="_blank"}  from **@dildick**: Remove cscTriggerPrimitiveDigis to prevent online client from crashing. `dqm`  created: 2018-10-17 13:10:17 merged: 2018-10-23 08:25:41



40. [24904](http://github.com/cms-sw/cmssw/pull/24904){:target="_blank"}  from **@smuzaffar**: make use of new iftool scram tag to conditionaly build/run tests `analysis`  created: 2018-10-17 12:21:59 merged: 2018-10-18 06:59:36



41. [24902](http://github.com/cms-sw/cmssw/pull/24902){:target="_blank"}  from **@slezki**: New folder in rpcdqm online to test new readouts `dqm`  created: 2018-10-17 09:50:05 merged: 2018-10-25 16:15:05



42. [24901](http://github.com/cms-sw/cmssw/pull/24901){:target="_blank"}  from **@bmahakud**: pat::Muon member function declaration bug  fix `analysis`  `reconstruction`  created: 2018-10-17 07:54:59 merged: 2018-10-23 08:45:12



43. [24897](http://github.com/cms-sw/cmssw/pull/24897){:target="_blank"}  from **@bsunanda**: Phase2-hgx162 Add the possibility of navigation in HGCalTopology `geometry`  `upgrade`  created: 2018-10-16 14:38:50 merged: 2018-10-25 10:33:22



44. [24896](http://github.com/cms-sw/cmssw/pull/24896){:target="_blank"}  from **@dildick**: Remove obsolete cout in CSCGEMMotherboard `l1`  created: 2018-10-16 14:22:25 merged: 2018-10-18 07:03:52



45. [24893](http://github.com/cms-sw/cmssw/pull/24893){:target="_blank"}  from **@schneiml**: DQM/Event Display: update scenario for HI `dqm`  created: 2018-10-16 14:01:43 merged: 2018-10-20 02:21:01



46. [24892](http://github.com/cms-sw/cmssw/pull/24892){:target="_blank"}  from **@YeonjuGo**: Centrality reco modification for 2018 heavy ion run `reconstruction`  created: 2018-10-16 13:59:15 merged: 2018-10-23 07:56:09



47. [24884](http://github.com/cms-sw/cmssw/pull/24884){:target="_blank"}  from **@vukasinmilosevic**: Changing default values of CaloLayer2 Agreement plots `dqm`  created: 2018-10-16 09:57:41 merged: 2018-10-19 09:10:43



48. [24883](http://github.com/cms-sw/cmssw/pull/24883){:target="_blank"}  from **@bundocka**: Calo Layer 2 saturation fixes `l1`  created: 2018-10-16 09:56:07 merged: 2018-10-18 20:07:38



49. [24882](http://github.com/cms-sw/cmssw/pull/24882){:target="_blank"}  from **@apsallid**: Update rechit calibration: dEdX weights, fCPerMIP, thickness corrections `reconstruction`  `upgrade`  created: 2018-10-16 09:42:28 merged: 2018-10-24 09:22:40



50. [24878](http://github.com/cms-sw/cmssw/pull/24878){:target="_blank"}  from **@cms-met**: Ecal Bad calib filter adding a new problematic crystal `analysis`  `reconstruction`  created: 2018-10-15 16:59:44 merged: 2018-10-20 02:19:20



51. [24877](http://github.com/cms-sw/cmssw/pull/24877){:target="_blank"}  from **@ssekmen**: disabling pixel histogram load messages - rebase to master `fastsim`  created: 2018-10-15 16:18:05 merged: 2018-10-16 07:10:04



52. [24876](http://github.com/cms-sw/cmssw/pull/24876){:target="_blank"}  from **@cms-met**: MET EE noise mitigation in 2017 data `analysis`  `reconstruction`  created: 2018-10-15 15:42:58 merged: 2018-10-24 07:50:08



53. [24870](http://github.com/cms-sw/cmssw/pull/24870){:target="_blank"}  from **@stahlleiton**: OfflineDQM: Offline L1T muon DQM bugfix for muon resolution plots CMSLITDPG-763 `dqm`  `l1`  created: 2018-10-15 11:38:35 merged: 2018-10-16 12:32:43



54. [24867](http://github.com/cms-sw/cmssw/pull/24867){:target="_blank"}  from **@bundocka**: HI O2O update: add new parameters and tidy up `l1`  created: 2018-10-15 10:31:12 merged: 2018-10-16 06:46:36



55. [24863](http://github.com/cms-sw/cmssw/pull/24863){:target="_blank"}  from **@guitargeek**: PFEGammaProducer with fillDescriptions `reconstruction`  created: 2018-10-14 17:52:53 merged: 2018-10-23 07:47:58



56. [24858](http://github.com/cms-sw/cmssw/pull/24858){:target="_blank"}  from **@wddgit**: Prepare for concurrent IOVs in FWCore `core`  created: 2018-10-12 20:03:24 merged: 2018-10-13 16:32:40



57. [24853](http://github.com/cms-sw/cmssw/pull/24853){:target="_blank"}  from **@panoskatsoulis**: BMTFTriggerAlgoSelector InputTag change for HeavyIons `dqm`  created: 2018-10-12 09:30:35 merged: 2018-10-15 16:29:02



58. [24851](http://github.com/cms-sw/cmssw/pull/24851){:target="_blank"}  from **@CMSTrackerDPG**: Regional strip unpacker: support for legacy modes and bugfix for virgin raw `hlt`  `reconstruction`  created: 2018-10-12 09:20:42 merged: 2018-10-18 08:41:12



59. [24849](http://github.com/cms-sw/cmssw/pull/24849){:target="_blank"}  from **@wddgit**: Prepare for concurrent IOVs `alca`  `db`  `l1`  created: 2018-10-11 20:45:56 merged: 2018-10-18 08:39:16



60. [24847](http://github.com/cms-sw/cmssw/pull/24847){:target="_blank"}  from **@christopheralanwest**: Implement second HF min-bias feature bit `alca`  `db`  `l1`  created: 2018-10-11 18:43:37 merged: 2018-10-16 16:24:16



61. [24846](http://github.com/cms-sw/cmssw/pull/24846){:target="_blank"}  from **@guitargeek**: Avoid unneccessary copies in RecoParticleFlow__PFProducer with emplace `reconstruction`  created: 2018-10-11 16:18:40 merged: 2018-10-15 08:54:38



62. [24844](http://github.com/cms-sw/cmssw/pull/24844){:target="_blank"}  from **@wddgit**: Extend EventSetup produce method return types `core`  created: 2018-10-10 20:53:38 merged: 2018-10-16 14:22:32



63. [24842](http://github.com/cms-sw/cmssw/pull/24842){:target="_blank"}  from **@cms-btv-pog**: [DQMOffline/Validation] BTV Updates `dqm`  created: 2018-10-10 08:02:16 merged: 2018-10-12 20:44:01



64. [24841](http://github.com/cms-sw/cmssw/pull/24841){:target="_blank"}  from **@wddgit**: Add more unit tests for PluginDescription `core`  created: 2018-10-09 18:39:53 merged: 2018-10-10 20:18:36



65. [24838](http://github.com/cms-sw/cmssw/pull/24838){:target="_blank"}  from **@amartelli**: Time for layerClusters in HGCAL `reconstruction`  `upgrade`  created: 2018-10-09 15:34:07 merged: 2018-10-16 07:09:19



66. [24837](http://github.com/cms-sw/cmssw/pull/24837){:target="_blank"}  from **@rekovic**: Pr103x L1T update centrality,  saturation fixes, EG eta restriction, jetphi ring subtraction (rebased) `l1`  created: 2018-10-09 15:06:59 merged: 2018-10-10 08:38:12



67. [24835](http://github.com/cms-sw/cmssw/pull/24835){:target="_blank"}  from **@vukasinmilosevic**: HI Plots for the CaloLayer2 DQM `dqm`  created: 2018-10-09 12:19:35 merged: 2018-10-15 11:15:59



68. [24833](http://github.com/cms-sw/cmssw/pull/24833){:target="_blank"}  from **@SanghyunKo**: Fix Relval steps for GEN workflow 535 `generators`  `pdmv`  `upgrade`  created: 2018-10-09 04:56:01 merged: 2018-10-11 13:37:17



69. [24832](http://github.com/cms-sw/cmssw/pull/24832){:target="_blank"}  from **@igv4321**: Added the capability to switch the mode of charge asymmetry evaluation `reconstruction`  created: 2018-10-09 02:07:02 merged: 2018-10-16 07:04:29



70. [24829](http://github.com/cms-sw/cmssw/pull/24829){:target="_blank"}  from **@nwickram**: fastsim 2017 PU and pmx wfs `fastsim`  `pdmv`  `upgrade`  created: 2018-10-08 16:21:19 merged: 2018-10-10 20:21:27



71. [24827](http://github.com/cms-sw/cmssw/pull/24827){:target="_blank"}  from **@makortel**: Use SimHits instead of digis for muon detectors in premixing `dqm`  `fastsim`  `operations`  `reconstruction`  `simulation`  `upgrade`  created: 2018-10-08 15:45:02 merged: 2018-10-26 19:09:32



72. [24823](http://github.com/cms-sw/cmssw/pull/24823){:target="_blank"}  from **@EmyrClement**: Settings for Herwig7 CH2 tune `generators`  created: 2018-10-08 09:36:39 merged: 2018-10-09 16:29:18



73. [24821](http://github.com/cms-sw/cmssw/pull/24821){:target="_blank"}  from **@siddhesh86**: Added Mixing scenario for PU250 and PU300 `operations`  created: 2018-10-07 14:31:38 merged: 2018-10-09 16:13:00



74. [24820](http://github.com/cms-sw/cmssw/pull/24820){:target="_blank"}  from **@Dr15Jones**: Switched to snprintf and increased buffer size `dqm`  created: 2018-10-07 13:37:25 merged: 2018-10-09 16:24:37



75. [24819](http://github.com/cms-sw/cmssw/pull/24819){:target="_blank"}  from **@icali**: Raw data remapper `daq`  created: 2018-10-07 10:17:52 merged: 2018-10-16 16:10:20



76. [24818](http://github.com/cms-sw/cmssw/pull/24818){:target="_blank"}  from **@slava77**: (re)introduce hit pair limit in iterative tracking seeding `reconstruction`  created: 2018-10-07 09:13:13 merged: 2018-10-19 08:22:40



77. [24816](http://github.com/cms-sw/cmssw/pull/24816){:target="_blank"}  from **@zhenhu**: update relval recycle strings of 10_3_0_pre5 `pdmv`  `upgrade`  created: 2018-10-05 22:31:10 merged: 2018-10-09 16:18:53



78. [24815](http://github.com/cms-sw/cmssw/pull/24815){:target="_blank"}  from **@bsunanda**: Phase2-159 Update the xml files for HFNose to make it working again `dqm`  `geometry`  `simulation`  `upgrade`  created: 2018-10-05 21:09:50 merged: 2018-10-11 08:36:04



79. [24814](http://github.com/cms-sw/cmssw/pull/24814){:target="_blank"}  from **@nancymarinelli**: bug fix in the linearizer ... `l1`  `upgrade`  created: 2018-10-05 14:35:56 merged: 2018-10-22 20:04:58



80. [24813](http://github.com/cms-sw/cmssw/pull/24813){:target="_blank"}  from **@Andrej-CMS**: Workflow 511.1: herwig7+ MG5+Openloops pptoee at NLO QCD `generators`  `pdmv`  `upgrade`  created: 2018-10-05 13:38:08 merged: 2018-10-09 16:16:57



81. [24812](http://github.com/cms-sw/cmssw/pull/24812){:target="_blank"}  from **@pieterdavid**: SiStrip unpacker: update packet code check in cmMedian (for nonstandard ZS modes) `reconstruction`  created: 2018-10-05 12:11:29 merged: 2018-10-13 16:31:24



82. [24810](http://github.com/cms-sw/cmssw/pull/24810){:target="_blank"}  from **@efeyazgan**: deleting RivetHarvesting `generators`  created: 2018-10-05 08:35:48 merged: 2018-10-18 06:36:27



83. [24807](http://github.com/cms-sw/cmssw/pull/24807){:target="_blank"}  from **@bsunanda**: Phase2-hgx158 Correct density of PCB for v9 geometry `geometry`  `upgrade`  created: 2018-10-04 18:23:34 merged: 2018-10-11 08:29:43



84. [24805](http://github.com/cms-sw/cmssw/pull/24805){:target="_blank"}  from **@civanch**: Fixed interface to Geant4 for custom dark matter photon `simulation`  created: 2018-10-04 15:18:19 merged: 2018-10-11 08:27:46



85. [24803](http://github.com/cms-sw/cmssw/pull/24803){:target="_blank"}  from **@dinardo**: Revert back from oversight about rawDataRepacker and rawDataCollector for the BeamPixel DQM application `dqm`  created: 2018-10-04 13:49:07 merged: 2018-10-15 16:31:42



86. [24800](http://github.com/cms-sw/cmssw/pull/24800){:target="_blank"}  from **@cms-tau-pog**: Update anti-e tau discriminant `reconstruction`  created: 2018-10-04 10:02:10 merged: 2018-10-12 20:19:51



87. [24796](http://github.com/cms-sw/cmssw/pull/24796){:target="_blank"}  from **@bsunanda**: Phase2-hgx157 Update the standalone digi study of HGCal (upgrade) to give reasonable o/p `dqm`  created: 2018-10-03 16:23:22 merged: 2018-10-11 08:33:59



88. [24791](http://github.com/cms-sw/cmssw/pull/24791){:target="_blank"}  from **@knoepfel**: EventSetup consumes interface `analysis`  `core`  created: 2018-10-02 17:07:53 merged: 2018-10-12 20:26:24



89. [24789](http://github.com/cms-sw/cmssw/pull/24789){:target="_blank"}  from **@guitargeek**: Replaced BOOST_FOREACH in RecoTauTag_RecoTau `reconstruction`  created: 2018-10-02 16:00:22 merged: 2018-10-12 08:13:26



90. [24787](http://github.com/cms-sw/cmssw/pull/24787){:target="_blank"}  from **@dan131riley**: skip getting event auxiliary if duplicate checker is disabled `core`  created: 2018-10-02 15:09:14 merged: 2018-10-11 08:24:21



91. [24784](http://github.com/cms-sw/cmssw/pull/24784){:target="_blank"}  from **@bsunanda**: Run2 alca141 IsoTrack calibration updates `alca`  created: 2018-10-02 14:47:56 merged: 2018-10-11 08:23:27



92. [24779](http://github.com/cms-sw/cmssw/pull/24779){:target="_blank"}  from **@abdoulline**: Small bugfix in HCAL peds+ped.widths DB objects names (HcalTextCalibrations input)  `alca`  created: 2018-10-02 12:29:28 merged: 2018-10-11 08:21:42



93. [24774](http://github.com/cms-sw/cmssw/pull/24774){:target="_blank"}  from **@guitargeek**: Replaced BOOST_STATIC_ASSERT with static_assert keyword `analysis`  `db`  `reconstruction`  created: 2018-10-01 19:14:05 merged: 2018-10-12 16:35:18



94. [24773](http://github.com/cms-sw/cmssw/pull/24773){:target="_blank"}  from **@mandrenguyen**: Update several heavy ion wfs to 2018 pp_on_AA era `pdmv`  `upgrade`  created: 2018-10-01 18:53:31 merged: 2018-10-09 16:55:25



95. [24766](http://github.com/cms-sw/cmssw/pull/24766){:target="_blank"}  from **@abrinke1**: EMTF new LCT coordinate conversion LUTs `l1`  created: 2018-10-01 09:42:01 merged: 2018-10-11 07:56:54



96. [24763](http://github.com/cms-sw/cmssw/pull/24763){:target="_blank"}  from **@AndrewLevin**: update POWHEG EmissionVeto1 for WGamma special case `generators`  created: 2018-09-29 14:53:09 merged: 2018-10-10 20:23:16



97. [24761](http://github.com/cms-sw/cmssw/pull/24761){:target="_blank"}  from **@henriettepetersen**: Implementation of the option preexistingprimaryvertex `alca`  created: 2018-09-28 18:01:57 merged: 2018-10-11 07:57:50



98. [24759](http://github.com/cms-sw/cmssw/pull/24759){:target="_blank"}  from **@mmusich**: [10.3.X] CalibrationTrackSelectorFromDetIdList: clone hits only when building track `alca`  created: 2018-09-28 17:04:03 merged: 2018-10-11 07:54:38



99. [24757](http://github.com/cms-sw/cmssw/pull/24757){:target="_blank"}  from **@DryRun**: HCALDQM: bad capid/LED misfire sound alarms only for last 60 LSes (10_3_X) `dqm`  created: 2018-09-28 16:43:29 merged: 2018-10-16 14:20:40



100. [24754](http://github.com/cms-sw/cmssw/pull/24754){:target="_blank"}  from **@andreh7**: made double em enrichment filter parameters tracked `generators`  created: 2018-09-28 13:45:24 merged: 2018-10-11 07:40:21



101. [24746](http://github.com/cms-sw/cmssw/pull/24746){:target="_blank"}  from **@wddgit**: Prepare for concurrent IOVs, MisalignedMuonESProducer `alca`  `geometry`  created: 2018-09-27 18:58:14 merged: 2018-10-11 07:37:56



102. [24711](http://github.com/cms-sw/cmssw/pull/24711){:target="_blank"}  from **@gartung**: FastSimulation/ParticleDecay: replace auto_ptr removed in strict std=c++17 `fastsim`  created: 2018-09-27 16:04:22 merged: 2018-10-11 20:45:37



103. [24694](http://github.com/cms-sw/cmssw/pull/24694){:target="_blank"}  from **@gartung**: CondFormats/HcalObjects: replace auto_ptr deprecated and removed in std=c++17 `alca`  `db`  created: 2018-09-27 14:51:08 merged: 2018-10-16 16:09:53



104. [24690](http://github.com/cms-sw/cmssw/pull/24690){:target="_blank"}  from **@civanch**: Clean-up Geant4 interface `simulation`  created: 2018-09-27 14:42:52 merged: 2018-10-10 20:16:05



105. [24683](http://github.com/cms-sw/cmssw/pull/24683){:target="_blank"}  from **@CTPPS**: Totem Timing detectors: updated mapping for future rereco of dedicated run data `alca`  `db`  `reconstruction`  created: 2018-09-27 14:28:52 merged: 2018-10-16 12:29:33



106. [24678](http://github.com/cms-sw/cmssw/pull/24678){:target="_blank"}  from **@mtosi**: add gen fragment for DarkSUSY MC relval production `generators`  created: 2018-09-26 19:56:23 merged: 2018-10-09 16:22:22



107. [24658](http://github.com/cms-sw/cmssw/pull/24658){:target="_blank"}  from **@wddgit**: Prepare RPCConeBuilder for concurrent IOVs `l1`  created: 2018-09-25 19:43:13 merged: 2018-10-10 20:12:36



108. [24625](http://github.com/cms-sw/cmssw/pull/24625){:target="_blank"}  from **@vargasa**: Validation/Geometry: No histos ROOT file being created by configuration scripts  && CleanUp `dqm`  `geometry`  created: 2018-09-22 11:14:51 merged: 2018-10-11 07:32:10



109. [24620](http://github.com/cms-sw/cmssw/pull/24620){:target="_blank"}  from **@davidlange6**: Factorize PythonParameterSet code from other fwk to reduce dependencies `alca`  `analysis`  `core`  `db`  `l1`  `reconstruction`  `visualization`  created: 2018-09-21 15:07:11 merged: 2018-10-12 20:12:14



110. [24613](http://github.com/cms-sw/cmssw/pull/24613){:target="_blank"}  from **@ftorresd**: RPC Digi Collection Merger `l1`  `operations`  `reconstruction`  created: 2018-09-20 21:25:06 merged: 2018-10-16 13:17:44



111. [24603](http://github.com/cms-sw/cmssw/pull/24603){:target="_blank"}  from **@depasse**: Ecal Transparency corrections : use either a tag or a file for TPG `alca`  `l1`  created: 2018-09-20 08:13:49 merged: 2018-10-11 08:11:08



112. [24556](http://github.com/cms-sw/cmssw/pull/24556){:target="_blank"}  from **@christopheralanwest**: Complete HE depth feature bit implementation `alca`  `db`  `l1`  created: 2018-09-16 15:02:12 merged: 2018-10-24 08:14:16



113. [24549](http://github.com/cms-sw/cmssw/pull/24549){:target="_blank"}  from **@guitargeek**: Removed many unary_/binary_functions `alca`  `analysis`  `core`  `db`  `dqm`  `fastsim`  `geometry`  `l1`  `reconstruction`  `upgrade`  created: 2018-09-14 20:14:54 merged: 2018-10-11 08:19:08



114. [24547](http://github.com/cms-sw/cmssw/pull/24547){:target="_blank"}  from **@cms-tau-pog**: Tau offline DQM update `dqm`  created: 2018-09-14 15:58:21 merged: 2018-10-10 20:08:12



115. [24509](http://github.com/cms-sw/cmssw/pull/24509){:target="_blank"}  from **@cvuosalo**: Start conversion to using user-defined literals for Geometry `geometry`  created: 2018-09-11 18:52:38 merged: 2018-10-11 08:44:47



116. [24503](http://github.com/cms-sw/cmssw/pull/24503){:target="_blank"}  from **@mrodozov**: Move from tinyxml to tinyxml2 in FWCore-MessageLogger `core`  `generators`  created: 2018-09-11 13:13:27 merged: 2018-10-15 20:11:45



117. [24496](http://github.com/cms-sw/cmssw/pull/24496){:target="_blank"}  from **@wddgit**: Prepare HcalTPGCoderULUT for concurrent IOVs `alca`  `l1`  `reconstruction`  created: 2018-09-10 18:09:19 merged: 2018-10-10 20:04:31



118. [24465](http://github.com/cms-sw/cmssw/pull/24465){:target="_blank"}  from **@lgray**: Extend TrackBase and Track to include time and velocity `reconstruction`  created: 2018-09-04 17:01:37 merged: 2018-10-10 20:02:12



119. [24422](http://github.com/cms-sw/cmssw/pull/24422){:target="_blank"}  from **@dildick**:  Remove smartME1aME1b in ME1/1. Make ME1/1 upgrade TMB inherit from CSCUpgradeMotherboard `l1`  created: 2018-08-30 23:16:25 merged: 2018-10-10 20:01:06



120. [24419](http://github.com/cms-sw/cmssw/pull/24419){:target="_blank"}  from **@lgray**: Extend the hit pattern class to include MTD hits `hlt`  `reconstruction`  created: 2018-08-30 16:16:23 merged: 2018-10-10 19:57:25



#### CMSDIST Changes between Tags REL/CMSSW_10_3_0_pre6/slc6_amd64_gcc700 and REL/CMSSW_10_4_0_pre1/slc6_amd64_gcc700:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_10_3_0_pre6/slc6_amd64_gcc700...REL/CMSSW_10_4_0_pre1/slc6_amd64_gcc700)



1. [4449](http://github.com/cms-sw/cmsdist/pull/4449){:target="_blank"}  from **@cms-sw**: generate cuda-gcc-support toolfile if cuda supports the existing gcc version created: 2018-10-24 12:22:25 merged: 2018-10-25 09:18:20

2. [4448](http://github.com/cms-sw/cmsdist/pull/4448){:target="_blank"}  from **@davidlange6**: use default to openloops docs optimization, pick up factorial calc improvement created: 2018-10-24 10:58:47 merged: 2018-10-25 14:23:38

3. [4447](http://github.com/cms-sw/cmsdist/pull/4447){:target="_blank"}  from **@cms-sw**: Added py2-lxml and py2-beautifulsoup4 tools created: 2018-10-24 08:49:30 merged: 2018-10-24 19:17:30

4. [4442](http://github.com/cms-sw/cmsdist/pull/4442){:target="_blank"}  from **@cms-sw**: Update SCRAMV1.spec created: 2018-10-22 15:52:34 merged: 2018-10-22 16:13:09

5. [4439](http://github.com/cms-sw/cmsdist/pull/4439){:target="_blank"}  from **@cms-sw**: Update scram tag V2_2_9_pre00 created: 2018-10-22 09:22:03 merged: 2018-10-22 11:11:41

6. [4438](http://github.com/cms-sw/cmsdist/pull/4438){:target="_blank"}  from **@cms-sw**: add ofast-flag tool and updated SCRAM created: 2018-10-20 16:25:38 merged: 2018-10-20 20:32:13

7. [4436](http://github.com/cms-sw/cmsdist/pull/4436){:target="_blank"}  from **@gartung**: Add dablooms spec and dablooms-toolfile spec so dablooms library can be linked by StaticAnalyzers library created: 2018-10-19 12:27:21 merged: 2018-10-20 07:03:47

8. [4435](http://github.com/cms-sw/cmsdist/pull/4435){:target="_blank"}  from **@cms-sw**: [10.4.X] BuildRules: Do not check the CUDA library version created: 2018-10-19 09:05:32 merged: 2018-10-19 20:01:08

9. [4433](http://github.com/cms-sw/cmsdist/pull/4433){:target="_blank"}  from **@mrodozov**: Remove tinyxml external, tinyxml2 used instead in cmssw created: 2018-10-18 13:37:10 merged: 2018-10-19 14:17:34

10. [4430](http://github.com/cms-sw/cmsdist/pull/4430){:target="_blank"}  from **@cms-sw**: Revert "Updated root to tip of branch v6-12-00-patches" created: 2018-10-17 14:37:14 merged: 2018-10-18 05:19:23

11. [4429](http://github.com/cms-sw/cmsdist/pull/4429){:target="_blank"}  from **@cms-sw**: generate python_tools toolfile created: 2018-10-17 12:16:27 merged: 2018-10-17 15:40:25

12. [4428](http://github.com/cms-sw/cmsdist/pull/4428){:target="_blank"}  from **@cms-sw**: update scram tag created: 2018-10-16 15:22:27 merged: 2018-10-16 20:30:50

13. [4422](http://github.com/cms-sw/cmsdist/pull/4422){:target="_blank"}  from **@cms-sw**: [10.4.X] patch llvm to avoid AARCH64 build errors created: 2018-10-12 13:10:21 merged: 2018-10-13 08:05:31

14. [4417](http://github.com/cms-sw/cmsdist/pull/4417){:target="_blank"}  from **@mrodozov**: Updated root to tip of branch v6-12-00-patches created: 2018-10-10 11:40:19 merged: 2018-10-12 14:05:50

15. [4415](http://github.com/cms-sw/cmsdist/pull/4415){:target="_blank"}  from **@cms-sw**: update TBB to 2019_U1 created: 2018-10-10 11:08:15 merged: 2018-10-12 20:08:03

16. [4359](http://github.com/cms-sw/cmsdist/pull/4359){:target="_blank"}  from **@cms-sw**: Update llvm/clang to version 7.0.0 (release)  created: 2018-09-24 08:13:58 merged: 2018-10-11 15:32:52
