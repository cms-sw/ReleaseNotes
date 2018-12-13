---
layout: post
rel_link:  "10_4_0_pre4"
title:  "CMSSW_10_4_0_pre4"
date:   2018-12-12 15:03:22
categories: cmssw
relmajor: 10
relminor: 4
relsubminor: 0
relpre: _pre4
---

# CMSSW_10_4_0_pre4
#### Changes since CMSSW_10_4_0_pre3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_10_4_0_pre3...CMSSW_10_4_0_pre4)



1. [25474](http://github.com/cms-sw/cmssw/pull/25474){:target="_blank"}  from **@fabiocos**: Fix the forgotten new default for 2018 HI vertex smearing (as in 10_3_X) `operations`  created: 2018-12-11 15:48:27 merged: 2018-12-12 10:39:06



2. [25471](http://github.com/cms-sw/cmssw/pull/25471){:target="_blank"}  from **@fabiocos**: MTD geometry: Update MTDGeometryBuilder test to make it really useful for MTD reco geometry `geometry`  `upgrade`  created: 2018-12-11 14:58:18 merged: 2018-12-12 10:40:04



3. [25470](http://github.com/cms-sw/cmssw/pull/25470){:target="_blank"}  from **@casarsa**: MTD simulation: double readout of BTL crystal bars (cleaned-up version) `geometry`  `operations`  `pdmv`  `reconstruction`  `simulation`  `upgrade`  created: 2018-12-11 12:20:00 merged: 2018-12-12 14:47:45



4. [25460](http://github.com/cms-sw/cmssw/pull/25460){:target="_blank"}  from **@ianna**: DD4hep:  Add Access to dd4hep::Detector from an EventSetup Source `geometry`  created: 2018-12-10 14:39:22 merged: 2018-12-11 12:57:30



5. [25452](http://github.com/cms-sw/cmssw/pull/25452){:target="_blank"}  from **@makortel**: Remove invalid tool from IORawData/DTCommissioning/plugins/BuildFile.xml `alca`  created: 2018-12-07 19:38:13 merged: 2018-12-11 12:14:35



6. [25451](http://github.com/cms-sw/cmssw/pull/25451){:target="_blank"}  from **@makortel**: Remove duplicate entry in Geometry/GlobalTrackingGeometryBuilder/test/BuildFile.xml `geometry`  created: 2018-12-07 19:17:48 merged: 2018-12-08 21:17:36



7. [25450](http://github.com/cms-sw/cmssw/pull/25450){:target="_blank"}  from **@Dr15Jones**: fix clang warnings in MuonAnalysis/MomentumScaleCalibration `analysis`  created: 2018-12-07 17:58:23 merged: 2018-12-10 08:00:58



8. [25438](http://github.com/cms-sw/cmssw/pull/25438){:target="_blank"}  from **@civanch**: Added extra Physics Lists for neutron background study `simulation`  created: 2018-12-06 18:12:02 merged: 2018-12-07 20:08:19



9. [25437](http://github.com/cms-sw/cmssw/pull/25437){:target="_blank"}  from **@adewit**: TkAl: making mille job submission via condor possible `alca`  created: 2018-12-06 14:36:14 merged: 2018-12-11 13:10:28



10. [25436](http://github.com/cms-sw/cmssw/pull/25436){:target="_blank"}  from **@lathomas**: Additional crystals added to the EcalBadCal MET filter `analysis`  `reconstruction`  created: 2018-12-06 13:09:14 merged: 2018-12-11 12:25:30



11. [25435](http://github.com/cms-sw/cmssw/pull/25435){:target="_blank"}  from **@clelange**: update PFCluster calibration for HGCal v9 geometry `reconstruction`  `upgrade`  created: 2018-12-06 11:37:23 merged: 2018-12-12 14:56:53



12. [25433](http://github.com/cms-sw/cmssw/pull/25433){:target="_blank"}  from **@fabiocos**: MTD: Add PMTDParameters to the GeometryObjects serialization test `alca`  `db`  created: 2018-12-06 09:14:58 merged: 2018-12-11 10:04:26



13. [25430](http://github.com/cms-sw/cmssw/pull/25430){:target="_blank"}  from **@Dr15Jones**: Fixed broken include guard in L1TMuonBarrelKalmanLUTs `l1`  created: 2018-12-05 16:43:59 merged: 2018-12-06 10:39:37



14. [25429](http://github.com/cms-sw/cmssw/pull/25429){:target="_blank"}  from **@Dr15Jones**: Fixed clang warnings in L1Trigger/L1THGCal `l1`  `upgrade`  created: 2018-12-05 16:34:57 merged: 2018-12-07 09:47:34



15. [25428](http://github.com/cms-sw/cmssw/pull/25428){:target="_blank"}  from **@Dr15Jones**: Fixed shifting a negative signed value in CondFormats/L1TObjects `alca`  `db`  `l1`  created: 2018-12-05 16:04:35 merged: 2018-12-11 12:37:39



16. [25427](http://github.com/cms-sw/cmssw/pull/25427){:target="_blank"}  from **@slomeo**: Bugfix for cavern `geometry`  `upgrade`  created: 2018-12-05 15:10:19 merged: 2018-12-07 06:00:50



17. [25426](http://github.com/cms-sw/cmssw/pull/25426){:target="_blank"}  from **@igv4321**: Switching the mode of charge asymmetry evaluation `reconstruction`  created: 2018-12-05 15:01:33 merged: 2018-12-06 17:53:08



18. [25423](http://github.com/cms-sw/cmssw/pull/25423){:target="_blank"}  from **@peruzzim**: Remove workflow 1325.9 testing NanoAOD on 92X `pdmv`  `upgrade`  created: 2018-12-05 10:54:53 merged: 2018-12-06 13:31:45



19. [25422](http://github.com/cms-sw/cmssw/pull/25422){:target="_blank"}  from **@tocheng**: [104X] Change GT. Offline GT Fix ECAL Queues `alca`  created: 2018-12-05 07:13:21 merged: 2018-12-07 05:57:37



20. [25421](http://github.com/cms-sw/cmssw/pull/25421){:target="_blank"}  from **@Dr15Jones**: Do not hold on to empty strings passed to getByLabel `core`  created: 2018-12-04 23:01:36 merged: 2018-12-05 11:45:40



21. [25418](http://github.com/cms-sw/cmssw/pull/25418){:target="_blank"}  from **@gartung**: FWCore: Update StallMonitor service to use microsecond timing `core`  created: 2018-12-04 20:38:49 merged: 2018-12-06 10:44:38



22. [25417](http://github.com/cms-sw/cmssw/pull/25417){:target="_blank"}  from **@fabiocos**: MTD geometry: move topology parameters from PSet to xml, adapt the code `geometry`  `upgrade`  created: 2018-12-04 15:22:52 merged: 2018-12-06 17:04:23



23. [25415](http://github.com/cms-sw/cmssw/pull/25415){:target="_blank"}  from **@ianna**: DD4hep: Add Trd2 Shape `geometry`  created: 2018-12-04 14:16:30 merged: 2018-12-05 08:58:20



24. [25413](http://github.com/cms-sw/cmssw/pull/25413){:target="_blank"}  from **@cms-tsg-storm**: Extended HLT menus (pp and PbPb) for MC production (104X) `core`  `hlt`  created: 2018-12-04 11:23:07 merged: 2018-12-06 09:39:05



25. [25412](http://github.com/cms-sw/cmssw/pull/25412){:target="_blank"}  from **@covarell**: Fix obvious bug in particle boosting (recursive statement) `generators`  created: 2018-12-04 10:54:46 merged: 2018-12-06 09:18:39



26. [25407](http://github.com/cms-sw/cmssw/pull/25407){:target="_blank"}  from **@bsunanda**: Phase2-TB41: Add first version of October 2018 HGCal TB setup `geometry`  `simulation`  `upgrade`  created: 2018-12-04 07:28:31 merged: 2018-12-12 14:59:01



27. [25406](http://github.com/cms-sw/cmssw/pull/25406){:target="_blank"}  from **@Dr15Jones**: Forward delcare as class not struct in PhysicsTools/Heppy `analysis`  created: 2018-12-03 21:22:36 merged: 2018-12-05 11:13:40



28. [25405](http://github.com/cms-sw/cmssw/pull/25405){:target="_blank"}  from **@Dr15Jones**: Fix clang warnings in RecoTracker/MeasurementDet `reconstruction`  created: 2018-12-03 21:00:00 merged: 2018-12-05 08:30:57



29. [25404](http://github.com/cms-sw/cmssw/pull/25404){:target="_blank"}  from **@Dr15Jones**: Removed unused variables and functions in RecoLocalCalo/HGCalRecAlgos `reconstruction`  `upgrade`  created: 2018-12-03 20:43:02 merged: 2018-12-05 08:56:35



30. [25403](http://github.com/cms-sw/cmssw/pull/25403){:target="_blank"}  from **@Dr15Jones**: Clang fixes in CondTools/SiPixel `alca`  `db`  created: 2018-12-03 20:09:30 merged: 2018-12-11 10:05:57



31. [25402](http://github.com/cms-sw/cmssw/pull/25402){:target="_blank"}  from **@Dr15Jones**: Remove std::move from return statements in CommonTools/CandUtils `analysis`  `reconstruction`  created: 2018-12-03 18:54:20 merged: 2018-12-05 08:28:24



32. [25401](http://github.com/cms-sw/cmssw/pull/25401){:target="_blank"}  from **@civanch**: Sim magnetic field `simulation`  created: 2018-12-03 18:39:32 merged: 2018-12-10 08:11:09



33. [25400](http://github.com/cms-sw/cmssw/pull/25400){:target="_blank"}  from **@Dr15Jones**: Remove std::move call from function return statement for L1TRawToDigi/Block `l1`  created: 2018-12-03 17:31:40 merged: 2018-12-05 08:18:29



34. [25399](http://github.com/cms-sw/cmssw/pull/25399){:target="_blank"}  from **@ianna**: DD4hep: Add Trd1 Division `geometry`  created: 2018-12-03 15:03:35 merged: 2018-12-04 09:47:50



35. [25397](http://github.com/cms-sw/cmssw/pull/25397){:target="_blank"}  from **@vargasa**: Validation/Geometry: Add reference plots to Material Budget test `dqm`  `geometry`  created: 2018-12-02 18:50:52 merged: 2018-12-07 20:10:36



36. [25396](http://github.com/cms-sw/cmssw/pull/25396){:target="_blank"}  from **@depasse**: ECAL : New method for MC production : outliers treatment.  Legacy Run2. `db`  created: 2018-12-02 17:58:07 merged: 2018-12-11 12:12:34



37. [25395](http://github.com/cms-sw/cmssw/pull/25395){:target="_blank"}  from **@bsunanda**: Phase2-hgx175 Update documentation of trigger DetId of HGCal and also the mask for trigger type `simulation`  `upgrade`  created: 2018-12-02 09:58:20 merged: 2018-12-04 09:42:38



38. [25394](http://github.com/cms-sw/cmssw/pull/25394){:target="_blank"}  from **@gartung**: edmStreamStallGrapher.py timings only count module Event times `core`  created: 2018-11-30 22:04:39 merged: 2018-12-03 17:15:07



39. [25393](http://github.com/cms-sw/cmssw/pull/25393){:target="_blank"}  from **@gartung**: FWCore/Framework: fix make_shared_noexcept_false template for macOS `core`  created: 2018-11-30 21:50:57 merged: 2018-12-04 09:43:13



40. [25390](http://github.com/cms-sw/cmssw/pull/25390){:target="_blank"}  from **@ColeLindsey**: Added 2018 PbPb collision vertex smearing parameters `operations`  `simulation`  created: 2018-11-30 21:05:04 merged: 2018-12-06 10:35:23



41. [25388](http://github.com/cms-sw/cmssw/pull/25388){:target="_blank"}  from **@suchandradutta**: Updating Phase2 Digitizer configuration for Inner Pixel `simulation`  `upgrade`  created: 2018-11-30 15:54:53 merged: 2018-12-03 17:14:17



42. [25383](http://github.com/cms-sw/cmssw/pull/25383){:target="_blank"}  from **@kpedro88**: fix TrackTimeValueProducer inputs for premixing `simulation`  created: 2018-11-30 00:04:13 merged: 2018-12-03 08:42:24



43. [25382](http://github.com/cms-sw/cmssw/pull/25382){:target="_blank"}  from **@vargasa**: Validation/Geometry: Integrate geometry comparison to MaterialBudget.py `dqm`  `geometry`  created: 2018-11-30 00:00:52 merged: 2018-12-06 10:26:19



44. [25381](http://github.com/cms-sw/cmssw/pull/25381){:target="_blank"}  from **@vargasa**: Validation/Geometry: CleanUp `dqm`  `geometry`  created: 2018-11-29 22:45:35 merged: 2018-12-04 08:58:07



45. [25378](http://github.com/cms-sw/cmssw/pull/25378){:target="_blank"}  from **@bsunanda**: Run2-TB40 Update TB geometry for June2018 setup `geometry`  `simulation`  `upgrade`  created: 2018-11-29 20:41:15 merged: 2018-12-04 09:59:55



46. [25376](http://github.com/cms-sw/cmssw/pull/25376){:target="_blank"}  from **@andrzejnovak**: Change default DDBvL model to 94X `reconstruction`  created: 2018-11-29 16:41:11 merged: 2018-12-05 08:15:21



47. [25374](http://github.com/cms-sw/cmssw/pull/25374){:target="_blank"}  from **@arossi83**: Tracker DQM HI Quality Test tuning and cleaning for Offline and Online `dqm`  created: 2018-11-29 15:10:46 merged: 2018-12-05 05:46:34



48. [25373](http://github.com/cms-sw/cmssw/pull/25373){:target="_blank"}  from **@cms-nanoAOD**: NanoAOD developments, 29Nov2018 version [104X] `analysis`  `operations`  created: 2018-11-29 14:19:25 merged: 2018-12-03 17:09:37



49. [25369](http://github.com/cms-sw/cmssw/pull/25369){:target="_blank"}  from **@Mourtz**: Bug Fix: "Calo Cluster" `visualization`  created: 2018-11-29 11:24:51 merged: 2018-11-30 16:34:46



50. [25366](http://github.com/cms-sw/cmssw/pull/25366){:target="_blank"}  from **@kpedro88**: Filter for semi-visible jet signal production `generators`  created: 2018-11-28 23:51:22 merged: 2018-11-29 17:40:58



51. [25364](http://github.com/cms-sw/cmssw/pull/25364){:target="_blank"}  from **@wddgit**: Return unique_ptr from fetchPayload `db`  created: 2018-11-28 21:08:24 merged: 2018-12-07 20:21:29



52. [25363](http://github.com/cms-sw/cmssw/pull/25363){:target="_blank"}  from **@Dr15Jones**: Make sure that Davix file is only closed once `core`  created: 2018-11-28 18:59:51 merged: 2018-11-30 16:37:08



53. [25360](http://github.com/cms-sw/cmssw/pull/25360){:target="_blank"}  from **@DryRun**: HCALDQM: Move channel quality lookup to dqmBeginLuminosityBlock (+increase pedestal RMS axis) `dqm`  created: 2018-11-28 16:18:42 merged: 2018-12-06 10:20:14



54. [25359](http://github.com/cms-sw/cmssw/pull/25359){:target="_blank"}  from **@ianna**: RECO Geometry: CTPPS DetGeomDesc Cleanup `geometry`  `reconstruction`  created: 2018-11-28 12:01:24 merged: 2018-12-06 18:06:21



55. [25358](http://github.com/cms-sw/cmssw/pull/25358){:target="_blank"}  from **@bsunanda**: Run2-alca146 Update the AlCaReco code for IsoTracksProducer `alca`  created: 2018-11-28 11:54:01 merged: 2018-12-02 18:57:54



56. [25357](http://github.com/cms-sw/cmssw/pull/25357){:target="_blank"}  from **@ghugo83**: Phase 2 Trackers T12 and T13: TBPX Lp GBTs placement study `geometry`  `operations`  `pdmv`  `upgrade`  created: 2018-11-28 10:47:56 merged: 2018-12-01 22:46:37



57. [25356](http://github.com/cms-sw/cmssw/pull/25356){:target="_blank"}  from **@ianna**: COCOA: Remove Dependency on DD `alca`  created: 2018-11-28 09:02:23 merged: 2018-12-11 14:18:30



58. [25352](http://github.com/cms-sw/cmssw/pull/25352){:target="_blank"}  from **@fabiocos**: MTD: store geometry scenario in topology record `alca`  `db`  `geometry`  `upgrade`  created: 2018-11-27 14:52:18 merged: 2018-11-30 21:36:05



59. [25351](http://github.com/cms-sw/cmssw/pull/25351){:target="_blank"}  from **@abdoulline**: LS-aware access to HcalChannelQuality `alca`  `analysis`  `reconstruction`  created: 2018-11-27 05:53:06 merged: 2018-12-04 09:50:34



60. [25348](http://github.com/cms-sw/cmssw/pull/25348){:target="_blank"}  from **@MRD2F**: Changes in SiPixelPhase1Summary and TrackEfficiencyMonitor_cfi `dqm`  created: 2018-11-26 20:45:30 merged: 2018-12-05 05:47:42



61. [25346](http://github.com/cms-sw/cmssw/pull/25346){:target="_blank"}  from **@makortel**: Fix MTV validation of initialStepPreSplitting tracks `core`  `dqm`  `simulation`  created: 2018-11-26 17:07:32 merged: 2018-12-01 17:15:32



62. [25344](http://github.com/cms-sw/cmssw/pull/25344){:target="_blank"}  from **@bsunanda**: Phase2-hgx174 Bug fixes `geometry`  `upgrade`  created: 2018-11-26 13:36:43 merged: 2018-12-06 09:36:05



63. [25338](http://github.com/cms-sw/cmssw/pull/25338){:target="_blank"}  from **@guitargeek**: PFEGammaAlgo removing unused function arguments `reconstruction`  created: 2018-11-26 02:07:21 merged: 2018-11-30 08:34:30



64. [25337](http://github.com/cms-sw/cmssw/pull/25337){:target="_blank"}  from **@guitargeek**: Make ElectronMVA usable in FWlite again `analysis`  `dqm`  `reconstruction`  `xpog`  created: 2018-11-26 02:04:32 merged: 2018-12-11 09:52:23



65. [25306](http://github.com/cms-sw/cmssw/pull/25306){:target="_blank"}  from **@knash**: Winter16 jetID update to include lepton veto  `analysis`  `reconstruction`  created: 2018-11-20 16:37:59 merged: 2018-11-30 16:37:56



66. [25304](http://github.com/cms-sw/cmssw/pull/25304){:target="_blank"}  from **@Dr15Jones**: Modernized BSCTrigger `l1`  created: 2018-11-20 15:46:23 merged: 2018-11-29 14:02:39



67. [25302](http://github.com/cms-sw/cmssw/pull/25302){:target="_blank"}  from **@bsunanda**: bsunanda:Run2 alca143  A new AlCaReco from Nan for muons at high |ieta|'s  `alca`  `operations`  created: 2018-11-20 14:52:18 merged: 2018-12-05 06:03:40



68. [25286](http://github.com/cms-sw/cmssw/pull/25286){:target="_blank"}  from **@bsunanda**: Run2-hcx188 First attempt to convert a few Hcal related algorithms to DD4HEP format `geometry`  created: 2018-11-19 16:28:17 merged: 2018-11-29 14:04:19



69. [25165](http://github.com/cms-sw/cmssw/pull/25165){:target="_blank"}  from **@dildick**: Various improvements to CSC local trigger emulator `l1`  created: 2018-11-08 22:01:38 merged: 2018-11-29 17:39:27



70. [25055](http://github.com/cms-sw/cmssw/pull/25055){:target="_blank"}  from **@alberto-sanchez**: Add k892 and bc 2s `analysis`  `reconstruction`  created: 2018-10-30 16:04:15 merged: 2018-11-30 12:36:25



#### CMSDIST Changes between Tags REL/CMSSW_10_4_0_pre3/slc6_amd64_gcc700 and REL/CMSSW_10_4_0_pre4/slc6_amd64_gcc700:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_10_4_0_pre3/slc6_amd64_gcc700...REL/CMSSW_10_4_0_pre4/slc6_amd64_gcc700)



1. [4558](http://github.com/cms-sw/cmsdist/pull/4558){:target="_blank"}  from **@cms-sw**: Update dd4hep to latest on master created: 2018-12-06 12:34:10 merged: 2018-12-07 07:30:31

2. [4554](http://github.com/cms-sw/cmsdist/pull/4554){:target="_blank"}  from **@cms-sw**: Added RecoTauTag-TrainingFiles V00-01-00 created: 2018-12-05 11:37:05 merged: 2018-12-06 10:07:26

3. [4551](http://github.com/cms-sw/cmsdist/pull/4551){:target="_blank"}  from **@cms-sw**: Update RecoBTag-Combined=V01-01-01 created: 2018-12-04 11:17:10 merged: 2018-12-04 18:03:02

4. [4544](http://github.com/cms-sw/cmsdist/pull/4544){:target="_blank"}  from **@cms-sw**: Update scram-project-build.file created: 2018-11-30 18:01:31 merged: 2018-11-30 21:48:46

5. [4539](http://github.com/cms-sw/cmsdist/pull/4539){:target="_blank"}  from **@cms-sw**: Update DD4hep to tip of master created: 2018-11-29 13:38:50 merged: 2018-11-30 20:09:56

6. [4515](http://github.com/cms-sw/cmsdist/pull/4515){:target="_blank"}  from **@cms-sw**: [10.4.X] data SimTransport PPSProtonTransport and TotemRPProtonTransportParametrization created: 2018-11-20 18:49:58 merged: 2018-12-01 16:36:05
