---
layout: post
rel_link:  "7_5_4"
title:  "CMSSW_7_5_4"
date:   2015-10-21 10:08:33
categories: cmssw
relmajor: 7
relminor: 5
relsubminor: 4
---

# CMSSW_7_5_4
#### Changes since CMSSW_7_5_3_patch1:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_5_3_patch1...CMSSW_7_5_4)



1. [11373](http://github.com/cms-sw/cmssw/pull/11373){:target="_blank"}  from **@richard-cms**:  L1 Stage 1 MET fixes (75X backport of #11372 ) `l1`  created: 2015-09-18 18:48:35 merged: 2015-10-21 09:47:06

2. [11781](http://github.com/cms-sw/cmssw/pull/11781){:target="_blank"}  from **@Dr15Jones**: Removed inappropriate use of SerialTaskQueue from ClusterShapeLazyGetter `reconstruction`  created: 2015-10-14 07:47:14 merged: 2015-10-21 08:56:31

3. [11793](http://github.com/cms-sw/cmssw/pull/11793){:target="_blank"}  from **@fioriNTU**: fix of TrackSplit monitor `dqm`  created: 2015-10-14 14:59:17 merged: 2015-10-21 08:51:35

4. [11410](http://github.com/cms-sw/cmssw/pull/11410){:target="_blank"}  from **@cms-btv-pog**: Templated BVertex plugins (75X) `reconstruction`  created: 2015-09-22 01:30:05 merged: 2015-10-21 08:47:21

5. [11437](http://github.com/cms-sw/cmssw/pull/11437){:target="_blank"}  from **@cms-l1t-offline**: Backport of PR #11253 to 75X - Updates to Tau and Jet calibration LUT, Alg fixes `l1`  created: 2015-09-23 16:15:55 merged: 2015-10-21 08:47:15

6. [11488](http://github.com/cms-sw/cmssw/pull/11488){:target="_blank"}  from **@fioriNTU**: fix of Bpix Efficiency `dqm`  created: 2015-09-25 08:53:41 merged: 2015-10-21 08:47:10

7. [11542](http://github.com/cms-sw/cmssw/pull/11542){:target="_blank"}  from **@Soureek89**: Changing path name HLT_Ele23_WPLoose_Gsf_CentralPFJet30_BTagCVS07_v to HLT_Ele23_WPLoose_Gsf_CentralPFJet30_BTagCSV07_v `dqm`  created: 2015-09-29 10:38:09 merged: 2015-10-21 08:47:04

8. [11608](http://github.com/cms-sw/cmssw/pull/11608){:target="_blank"}  from **@lgray**: Change CandidateBoostedDoubleSecondaryVertexComputer to use GBRForest (75X) `reconstruction`  created: 2015-10-01 17:26:26 merged: 2015-10-21 08:46:58

9. [11137](http://github.com/cms-sw/cmssw/pull/11137){:target="_blank"}  from **@lathomas**: CSC Beam Halo filter update `analysis`  `reconstruction`  created: 2015-09-04 16:08:44 merged: 2015-10-21 08:46:34

10. [11186](http://github.com/cms-sw/cmssw/pull/11186){:target="_blank"}  from **@fioriNTU**: Avoid empty FED occupancy plot in PixDQM `dqm`  created: 2015-09-08 17:17:12 merged: 2015-10-20 17:22:47

11. [11306](http://github.com/cms-sw/cmssw/pull/11306){:target="_blank"}  from **@silviodonato**: HLT BTV DQM offline - 75X backport `dqm`  created: 2015-09-17 07:33:43 merged: 2015-10-20 17:22:36

12. [11339](http://github.com/cms-sw/cmssw/pull/11339){:target="_blank"}  from **@fioriNTU**: Multiplicity regions75 x `dqm`  created: 2015-09-18 10:54:00 merged: 2015-10-20 17:22:30

13. [11824](http://github.com/cms-sw/cmssw/pull/11824){:target="_blank"}  from **@barvic**: 75X - Fix for handling of rare case of CFEB data corruption `reconstruction`  created: 2015-10-15 15:24:36 merged: 2015-10-20 17:21:50

14. [11836](http://github.com/cms-sw/cmssw/pull/11836){:target="_blank"}  from **@BetterWang**: EP code bug fix `reconstruction`  created: 2015-10-15 20:34:17 merged: 2015-10-20 17:21:45

15. [10881](http://github.com/cms-sw/cmssw/pull/10881){:target="_blank"}  from **@cms-l1t-offline**: RCT unpacker plus DQM 75X `dqm`  `l1`  created: 2015-08-20 11:50:38 merged: 2015-10-20 17:18:04

16. [11061](http://github.com/cms-sw/cmssw/pull/11061){:target="_blank"}  from **@VinInn**:  Vertex and tracking DQM: fix histo scales, add ngood vertex, Add valid,lost,missing inner/outer hits 2d-histos `dqm`  created: 2015-09-01 13:31:17 merged: 2015-10-20 17:17:56

17. [11110](http://github.com/cms-sw/cmssw/pull/11110){:target="_blank"}  from **@mbandrews**: Tightened timing cut for 25ns runs. Relaxed Pedestal RMS qT threshold `dqm`  created: 2015-09-03 14:04:49 merged: 2015-10-20 17:17:50

18. [11433](http://github.com/cms-sw/cmssw/pull/11433){:target="_blank"}  from **@bachtis**: Improvements in track quality criteria in PF for muon seeded iterations `reconstruction`  created: 2015-09-23 14:26:18 merged: 2015-10-20 17:17:44

19. [11547](http://github.com/cms-sw/cmssw/pull/11547){:target="_blank"}  from **@cms-tsg-storm**: 75X hlt25ns round six `fastsim`  `hlt`  created: 2015-09-29 12:22:38 merged: 2015-10-20 17:17:38

20. [11582](http://github.com/cms-sw/cmssw/pull/11582){:target="_blank"}  from **@mojoe137**: Add pcc info to WBM text file and update PCC x-section for 75X `dqm`  created: 2015-09-30 21:43:45 merged: 2015-10-20 17:17:31

21. [11632](http://github.com/cms-sw/cmssw/pull/11632){:target="_blank"}  from **@duanders**: Scouting producers now ignore missing input collections (75X) `hlt`  created: 2015-10-05 08:58:02 merged: 2015-10-20 17:17:25

22. [11660](http://github.com/cms-sw/cmssw/pull/11660){:target="_blank"}  from **@fojensen**: added 3D and beamspot/vertex options `reconstruction`  created: 2015-10-06 18:34:04 merged: 2015-10-20 17:17:19

23. [11803](http://github.com/cms-sw/cmssw/pull/11803){:target="_blank"}  from **@mbandrews**: Fix TestPulse RMS binning and output `dqm`  created: 2015-10-14 22:13:57 merged: 2015-10-20 17:17:04

24. [11841](http://github.com/cms-sw/cmssw/pull/11841){:target="_blank"}  from **@jhgoh**:  75X backport assign muon PDG id using PFMuon charge  `reconstruction`  created: 2015-10-16 00:18:20 merged: 2015-10-20 17:16:44

25. [11391](http://github.com/cms-sw/cmssw/pull/11391){:target="_blank"}  from **@Martin-Grunewald**: 75X: New GT with L1T v5 and thus new HLT selection `alca`  `hlt`  created: 2015-09-21 10:44:06 merged: 2015-10-15 09:27:14

26. [11523](http://github.com/cms-sw/cmssw/pull/11523){:target="_blank"}  from **@arcidiac**: Fix for the Streams' names to be monitored `dqm`  created: 2015-09-28 11:04:20 merged: 2015-10-15 09:27:08

27. [11444](http://github.com/cms-sw/cmssw/pull/11444){:target="_blank"}  from **@dinardo**: Now the code is able to handle non consecutive LS `dqm`  created: 2015-09-23 22:43:36 merged: 2015-10-15 07:56:40

28. [11484](http://github.com/cms-sw/cmssw/pull/11484){:target="_blank"}  from **@cms-tsg-storm**: 75X hlt25ns round5 plus updated frozenv4 `hlt`  created: 2015-09-25 08:15:21 merged: 2015-10-15 07:51:39

29. [11688](http://github.com/cms-sw/cmssw/pull/11688){:target="_blank"}  from **@cms-btv-pog**: Switch on hadronFlavourHasPriority for b-tag Validation module. `dqm`  created: 2015-10-08 09:53:10 merged: 2015-10-15 07:36:50

30. [11760](http://github.com/cms-sw/cmssw/pull/11760){:target="_blank"}  from **@slava77**: pick ecal fraction of 0 for a candidate with trackMomentum 0 (same as #11302) `reconstruction`  created: 2015-10-13 14:12:59 merged: 2015-10-15 07:36:30

31. [11807](http://github.com/cms-sw/cmssw/pull/11807){:target="_blank"}  from **@alja**: 75x Fireworks: fix MuonDigi accessor type `visualization`  created: 2015-10-14 22:46:54 merged: 2015-10-15 07:36:12

32. [11657](http://github.com/cms-sw/cmssw/pull/11657){:target="_blank"}  from **@gsafronov**: 75X: fix pT selection in HLTrigger/special/src/HLTPixlMBFilt.cc `hlt`  created: 2015-10-06 16:07:37 merged: 2015-10-15 07:35:18

33. [10839](http://github.com/cms-sw/cmssw/pull/10839){:target="_blank"}  from **@yetkinyilmaz**: Option for DAS query in ConfigBuilder 75X `operations`  created: 2015-08-18 11:57:25 merged: 2015-10-13 07:37:30

34. [11541](http://github.com/cms-sw/cmssw/pull/11541){:target="_blank"}  from **@hengne**: relval scripts update, 2015c data workflows, a couple of fixes. `alca`  `hlt`  `pdmv`  `simulation`  created: 2015-09-29 10:27:35 merged: 2015-10-13 07:32:08

35. [11586](http://github.com/cms-sw/cmssw/pull/11586){:target="_blank"}  from **@Martin-Grunewald**: Addition of PFMET to Trigger Data Formats (75X) `hlt`  created: 2015-10-01 07:25:12 merged: 2015-10-13 07:31:56

36. [11741](http://github.com/cms-sw/cmssw/pull/11741){:target="_blank"}  from **@slava77**: heavyIonsRun2 scenario for data processing `dqm`  `operations`  created: 2015-10-12 23:38:58 merged: 2015-10-13 07:29:23

37. [11509](http://github.com/cms-sw/cmssw/pull/11509){:target="_blank"}  from **@fwyzard**: hltDiff: compare TriggerResults event by event (75x) `hlt`  created: 2015-09-26 10:38:39 merged: 2015-10-12 15:16:43

38. [11362](http://github.com/cms-sw/cmssw/pull/11362){:target="_blank"}  from **@cms-met**: Change the type1 jet pt threshold from 10 to 15 GeV `analysis`  created: 2015-09-18 15:59:36 merged: 2015-10-12 12:51:36

39. [11406](http://github.com/cms-sw/cmssw/pull/11406){:target="_blank"}  from **@lgray**: Fix sigmaIetaIphi for photon regression (75X) `reconstruction`  created: 2015-09-21 22:21:53 merged: 2015-10-12 12:51:31

40. [11531](http://github.com/cms-sw/cmssw/pull/11531){:target="_blank"}  from **@taroni**: fixing emulator fenix bug `l1`  created: 2015-09-28 14:18:10 merged: 2015-10-12 12:51:19

41. [11417](http://github.com/cms-sw/cmssw/pull/11417){:target="_blank"}  from **@argiro**: PositionCalc Fix `reconstruction`  created: 2015-09-22 09:55:43 merged: 2015-10-12 12:46:26

42. [11096](http://github.com/cms-sw/cmssw/pull/11096){:target="_blank"}  from **@VinInn**: fix inner outer for OutIn in 75X `reconstruction`  created: 2015-09-03 08:49:50 merged: 2015-10-12 12:42:21

43. [11457](http://github.com/cms-sw/cmssw/pull/11457){:target="_blank"}  from **@smorovic**: Freeing INI file buffer after writing the file is finished (75X) `core`  created: 2015-09-24 13:45:05 merged: 2015-10-12 12:42:14

44. [11521](http://github.com/cms-sw/cmssw/pull/11521){:target="_blank"}  from **@slehti**: Bugfix in HLTTauDQMPath affecting L2 plots `dqm`  created: 2015-09-28 10:18:05 merged: 2015-10-12 12:41:51

45. [11604](http://github.com/cms-sw/cmssw/pull/11604){:target="_blank"}  from **@kkrajczar**: For HI HLT: migration of 5 HI tracking modules to stream modules (75X backport) `reconstruction`  created: 2015-10-01 16:06:26 merged: 2015-10-12 12:41:45

46. [11615](http://github.com/cms-sw/cmssw/pull/11615){:target="_blank"}  from **@cmkuo**: fix ES unpacker when the 2nd OptoRX is diabled, but the 1t and 3rd Op `reconstruction`  created: 2015-10-02 03:33:05 merged: 2015-10-12 12:41:39

47. [11705](http://github.com/cms-sw/cmssw/pull/11705){:target="_blank"}  from **@lihux25**: Fix the duplicated HF channels `reconstruction`  created: 2015-10-08 22:30:07 merged: 2015-10-12 12:41:23

48. [11464](http://github.com/cms-sw/cmssw/pull/11464){:target="_blank"}  from **@threus**: updated x-axes for several SiStripDQM MEs (75x) `dqm`  created: 2015-09-24 16:04:58 merged: 2015-10-12 12:37:22

49. [11536](http://github.com/cms-sw/cmssw/pull/11536){:target="_blank"}  from **@smorovic**: Checksum parameter cfi export (75X) `daq`  `reconstruction`  created: 2015-09-28 16:53:47 merged: 2015-10-12 12:37:03

50. [11545](http://github.com/cms-sw/cmssw/pull/11545){:target="_blank"}  from **@sushilchauhan**: fix for LS range of fit if there are no event processed in a LS `dqm`  created: 2015-09-29 12:11:46 merged: 2015-10-12 12:36:57

51. [11551](http://github.com/cms-sw/cmssw/pull/11551){:target="_blank"}  from **@dmitrijus**: A fix for the DQMStreamerReader (75x) `dqm`  created: 2015-09-29 14:27:12 merged: 2015-10-12 12:36:50

52. [11594](http://github.com/cms-sw/cmssw/pull/11594){:target="_blank"}  from **@ggovi**: Back-port of several fixes and improvements for the conddb tools `db`  created: 2015-10-01 13:12:15 merged: 2015-10-12 12:36:43

53. [11638](http://github.com/cms-sw/cmssw/pull/11638){:target="_blank"}  from **@alja**: 75x Fireworks: fix problem with muon global track propagation `visualization`  created: 2015-10-05 16:30:42 merged: 2015-10-12 12:36:37

54. [11719](http://github.com/cms-sw/cmssw/pull/11719){:target="_blank"}  from **@fwyzard**: cmsCheckMultithreading replaced by edmCheckmultithreading `hlt`  created: 2015-10-10 11:37:16 merged: 2015-10-12 12:36:19

55. [11724](http://github.com/cms-sw/cmssw/pull/11724){:target="_blank"}  from **@Dr15Jones**: Fix python2.6 SyntaxError. `core`  created: 2015-10-11 13:10:14 merged: 2015-10-11 14:27:48

56. [11400](http://github.com/cms-sw/cmssw/pull/11400){:target="_blank"}  from **@Dr15Jones**: Change mayConsume to conditional consumes in PATJetProducer `analysis`  created: 2015-09-21 15:57:24 merged: 2015-09-28 13:32:30

#### CMSDIST Changes between Tags REL/CMSSW_7_5_3_patch1/slc6_amd64_gcc491 and REL/CMSSW_7_5_4/slc6_amd64_gcc491:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_5_3_patch1/slc6_amd64_gcc491...REL/CMSSW_7_5_4/slc6_amd64_gcc491)



1. [1889](http://github.com/\- cms-sw/cmsdist/pull/1889){:target="_blank"}  from **@degano**: Advance release for RecoEgamma/ElectronIdentification data.

2. [1828](http://github.com/\- cms-sw/cmsdist/pull/1828){:target="_blank"}  from **@degano**: Update with Weight files for MET3.0
