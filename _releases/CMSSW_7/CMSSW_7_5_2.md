---
layout: post
rel_link:  "7_5_2"
title:  "CMSSW_7_5_2"
date:   2015-08-20 19:38:19
categories: cmssw
relmajor: 7
relminor: 5
relsubminor: 2
---

# CMSSW_7_5_2
#### Changes since CMSSW_7_5_1:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_5_1...CMSSW_7_5_2)



1. [10872](http://github.com/cms-sw/cmssw/pull/10872){:target="_blank"}  from **@mmusich**: Adding e/gamma regression from Ecal Multifit in Run1/Run2 GTs `alca`  created: 2015-08-20 08:25:47 merged: 2015-08-20 15:56:47

2. [10597](http://github.com/cms-sw/cmssw/pull/10597){:target="_blank"}  from **@nhanvtran**: update PUPPI based on DP note `analysis`  `reconstruction`  created: 2015-08-05 21:19:30 merged: 2015-08-20 15:13:44

3. [10754](http://github.com/cms-sw/cmssw/pull/10754){:target="_blank"}  from **@ferencek**: Moving GBRForestWriter to CommonTools/Utils: 75X `analysis`  `reconstruction`  created: 2015-08-13 19:26:36 merged: 2015-08-20 15:12:07

4. [10777](http://github.com/cms-sw/cmssw/pull/10777){:target="_blank"}  from **@dgulhan**: Pixel cluster splitting and jet core iteration for HI Tracking `operations`  `reconstruction`  created: 2015-08-14 14:26:40 merged: 2015-08-20 15:11:21

5. [10885](http://github.com/cms-sw/cmssw/pull/10885){:target="_blank"}  from **@bbockelm**: Fix sigstack printer. `core`  created: 2015-08-20 14:12:43 merged: 2015-08-20 15:08:54

6. [10300](http://github.com/cms-sw/cmssw/pull/10300){:target="_blank"}  from **@kfjack**: Update MuTauSkim_cff with new Tau POG Isolation from Ram (7_5_X) `pdmv`  created: 2015-07-21 18:17:47 merged: 2015-08-20 05:56:49

7. [10749](http://github.com/cms-sw/cmssw/pull/10749){:target="_blank"}  from **@lgray**: Move slimmedAddPileupInfo to miniAOD_customizeMC (75X) `analysis`  created: 2015-08-13 16:28:21 merged: 2015-08-20 05:56:31

8. [10765](http://github.com/cms-sw/cmssw/pull/10765){:target="_blank"}  from **@mmarionncern**: Update the default relval for the recoMET tests `reconstruction`  created: 2015-08-14 08:17:34 merged: 2015-08-20 05:56:24

9. [10849](http://github.com/cms-sw/cmssw/pull/10849){:target="_blank"}  from **@dmitrijus**: Update Scal (Online DQM) configuration to work with our new setup (75x)  `dqm`  created: 2015-08-19 08:29:12 merged: 2015-08-20 05:56:18

10. [10857](http://github.com/cms-sw/cmssw/pull/10857){:target="_blank"}  from **@Dr15Jones**: Fix thread-safety issue with StreamerInputSource `core`  created: 2015-08-19 16:36:53 merged: 2015-08-20 05:56:12

11. [10789](http://github.com/cms-sw/cmssw/pull/10789){:target="_blank"}  from **@threus**: tiny update of occupancy script `dqm`  created: 2015-08-14 17:24:12 merged: 2015-08-20 05:54:44

12. [10865](http://github.com/cms-sw/cmssw/pull/10865){:target="_blank"}  from **@slava77**: forward port of dataProcessing changes for 25ns `l1`  `operations`  `reconstruction`  created: 2015-08-19 22:48:25 merged: 2015-08-20 05:52:22

13. [10868](http://github.com/cms-sw/cmssw/pull/10868){:target="_blank"}  from **@jhgoh**: Fix crash due to invalid track status 75X `reconstruction`  created: 2015-08-20 03:36:46 merged: 2015-08-20 05:51:05

14. [10541](http://github.com/cms-sw/cmssw/pull/10541){:target="_blank"}  from **@rappoccio**: Adjusting trigger paths for B2G DQM : 75x `dqm`  created: 2015-08-03 20:28:13 merged: 2015-08-19 05:47:12

15. [10632](http://github.com/cms-sw/cmssw/pull/10632){:target="_blank"}  from **@fioriNTU**: PixelBarrelEfficiency75 `dqm`  created: 2015-08-07 16:52:19 merged: 2015-08-19 05:47:06

16. [10685](http://github.com/cms-sw/cmssw/pull/10685){:target="_blank"}  from **@muell149**: adding HLT object monitoring to HLT online DQM `dqm`  created: 2015-08-11 14:02:17 merged: 2015-08-19 05:47:00

17. [10696](http://github.com/cms-sw/cmssw/pull/10696){:target="_blank"}  from **@cms-l1t-offline**:  Add HF Minimum Bias algorithm to Stage1 Emulator (backport #10695) `l1`  created: 2015-08-11 18:03:27 merged: 2015-08-19 05:46:53

18. [10702](http://github.com/cms-sw/cmssw/pull/10702){:target="_blank"}  from **@richard-cms**: Put GED photons into HI event content and DQM pathways (backport 75X #10700) `dqm`  `reconstruction`  created: 2015-08-11 19:54:42 merged: 2015-08-19 05:46:47

19. [10722](http://github.com/cms-sw/cmssw/pull/10722){:target="_blank"}  from **@prbbing**: Added ne displacedJets paths `dqm`  created: 2015-08-12 15:37:59 merged: 2015-08-19 05:46:36

20. [10823](http://github.com/cms-sw/cmssw/pull/10823){:target="_blank"}  from **@ginnocen**: new methods for D filters -- backports of  #10822 `hlt`  created: 2015-08-17 18:55:48 merged: 2015-08-19 05:46:16

21. [10807](http://github.com/cms-sw/cmssw/pull/10807){:target="_blank"}  from **@smorovic**: metadata JSON files produced for empty lumisections in DAQ (75X) `daq`  `dqm`  `hlt`  `reconstruction`  created: 2015-08-16 17:13:56 merged: 2015-08-19 05:42:23

22. [10377](http://github.com/cms-sw/cmssw/pull/10377){:target="_blank"}  from **@duanders**: Data scouting classes and producers (75X) `hlt`  created: 2015-07-26 22:03:33 merged: 2015-08-19 05:40:39

23. [10827](http://github.com/cms-sw/cmssw/pull/10827){:target="_blank"}  from **@fwyzard**: hltGetConfiguration: switch run:NNNNNN to use ConfDB v2 `hlt`  created: 2015-08-17 21:28:20 merged: 2015-08-18 13:31:49

24. [10830](http://github.com/cms-sw/cmssw/pull/10830){:target="_blank"}  from **@slava77**: add dqmSeq option to the recoinator (same as #10829) `operations`  created: 2015-08-17 23:52:00 merged: 2015-08-18 13:27:00

25. [10595](http://github.com/cms-sw/cmssw/pull/10595){:target="_blank"}  from **@alja**: 75x Fireworks:Update collection entry in configuration files `visualization`  created: 2015-08-05 19:10:06 merged: 2015-08-17 17:36:50

26. [10657](http://github.com/cms-sw/cmssw/pull/10657){:target="_blank"}  from **@echapon**: Run "high level muon reconstruction" for heavy ions `reconstruction`  created: 2015-08-10 17:23:11 merged: 2015-08-17 17:36:42

27. [10666](http://github.com/cms-sw/cmssw/pull/10666){:target="_blank"}  from **@cmkuo**: add low pt photons (10-14 GeV) to miniAOD for 75x `reconstruction`  created: 2015-08-10 21:40:00 merged: 2015-08-17 17:36:35

28. [10684](http://github.com/cms-sw/cmssw/pull/10684){:target="_blank"}  from **@prbbing**: Backport from 76X 10681, added new HT parking paths and changed the b `dqm`  created: 2015-08-11 13:57:13 merged: 2015-08-17 17:31:51

29. [10792](http://github.com/cms-sw/cmssw/pull/10792){:target="_blank"}  from **@dmitrijus**: Fix online DQM configuration for visualization (75x) `dqm`  created: 2015-08-14 17:29:02 merged: 2015-08-17 17:31:38

30. [10534](http://github.com/cms-sw/cmssw/pull/10534){:target="_blank"}  from **@cms-tsg-storm**: HLT update for 25ns (75X) `alca`  `hlt`  created: 2015-08-03 16:34:58 merged: 2015-08-17 08:36:44

31. [10781](http://github.com/cms-sw/cmssw/pull/10781){:target="_blank"}  from **@MilanoBicocca-pix**: [BeamSpot] fit 1D projections of PV distribution to get initial values for 3D fit parameters `alca`  `reconstruction`  created: 2015-08-14 16:11:52 merged: 2015-08-17 08:16:20

32. [10738](http://github.com/cms-sw/cmssw/pull/10738){:target="_blank"}  from **@dmitrijus**: Adding scal monitoring to online DQM (75x) `dqm`  created: 2015-08-13 09:51:17 merged: 2015-08-17 08:11:35

33. [10800](http://github.com/cms-sw/cmssw/pull/10800){:target="_blank"}  from **@gouskos**: enable beam spot validation - emails notifications suppressed 75x `dqm`  created: 2015-08-15 15:52:42 merged: 2015-08-17 08:11:19

34. [10770](http://github.com/cms-sw/cmssw/pull/10770){:target="_blank"}  from **@MilanoBicocca-pix**: [DQM/BeamMonitor] fix y-axis range to properly display d0-phi plot `dqm`  created: 2015-08-14 09:41:57 merged: 2015-08-16 19:31:36

35. [10774](http://github.com/cms-sw/cmssw/pull/10774){:target="_blank"}  from **@deguio**: add legacy module support for run and lumi based histograms `dqm`  created: 2015-08-14 11:43:42 merged: 2015-08-16 19:26:42

36. [10557](http://github.com/cms-sw/cmssw/pull/10557){:target="_blank"}  from **@lgray**: Migrate VID BDTs to GlobalCache + GBRForest (75X) `reconstruction`  created: 2015-08-04 11:30:32 merged: 2015-08-14 07:16:57

37. [10711](http://github.com/cms-sw/cmssw/pull/10711){:target="_blank"}  from **@fcavallo**: bug fix in OccupancyNoise `dqm`  created: 2015-08-12 09:10:45 merged: 2015-08-14 07:06:48

38. [10715](http://github.com/cms-sw/cmssw/pull/10715){:target="_blank"}  from **@dmitrijus**: Customisations and few fixes for online DQM (75x) `dqm`  `reconstruction`  created: 2015-08-12 10:07:58 merged: 2015-08-14 07:06:42

39. [10725](http://github.com/cms-sw/cmssw/pull/10725){:target="_blank"}  from **@dertexaner**: Fix r45Fraction_ calculation `reconstruction`  created: 2015-08-12 16:18:36 merged: 2015-08-14 07:06:25

40. [10741](http://github.com/cms-sw/cmssw/pull/10741){:target="_blank"}  from **@fwyzard**: fix location of ConfDB v2 .jar files `hlt`  created: 2015-08-13 12:46:23 merged: 2015-08-14 07:00:08

41. [10737](http://github.com/cms-sw/cmssw/pull/10737){:target="_blank"}  from **@geonmo**: Remove wrong "tracked". `simulation`  created: 2015-08-13 09:44:17 merged: 2015-08-14 06:59:25

42. [10651](http://github.com/cms-sw/cmssw/pull/10651){:target="_blank"}  from **@hengne**: update relval scripts `pdmv`  created: 2015-08-10 09:12:59 merged: 2015-08-13 07:21:42

43. [10728](http://github.com/cms-sw/cmssw/pull/10728){:target="_blank"}  from **@slava77**: SimGeneralAOD doesn't belong in AODEventContent (backport of #10727) `operations`  created: 2015-08-12 16:33:26 merged: 2015-08-13 07:15:33

44. [10466](http://github.com/cms-sw/cmssw/pull/10466){:target="_blank"}  from **@ndaci**: Updated paths.  `dqm`  created: 2015-07-30 07:19:14 merged: 2015-08-12 08:42:18

45. [10480](http://github.com/cms-sw/cmssw/pull/10480){:target="_blank"}  from **@emiglior**: Update for GEN infos in 75X  `analysis`  created: 2015-07-30 13:37:03 merged: 2015-08-12 08:42:12

46. [10640](http://github.com/cms-sw/cmssw/pull/10640){:target="_blank"}  from **@diguida**: Hotfix for Run2015A+B 0T luminous region centroid positions (75X) `simulation`  created: 2015-08-08 17:29:42 merged: 2015-08-12 08:41:41

47. [10656](http://github.com/cms-sw/cmssw/pull/10656){:target="_blank"}  from **@lathomas**: CSCHaloData kept in AOD `reconstruction`  created: 2015-08-10 16:27:38 merged: 2015-08-12 08:36:42

48. [10634](http://github.com/cms-sw/cmssw/pull/10634){:target="_blank"}  from **@lathomas**: Beam Halo filter bug fix `reconstruction`  created: 2015-08-07 20:09:57 merged: 2015-08-10 11:01:11

49. [10629](http://github.com/cms-sw/cmssw/pull/10629){:target="_blank"}  from **@dmitrijus**: Re-organize python configurations for the online DQM applications `dqm`  created: 2015-08-07 13:49:09 merged: 2015-08-10 05:52:23

50. [10125](http://github.com/cms-sw/cmssw/pull/10125){:target="_blank"}  from **@mtosi**: update track candidate DQM code `dqm`  `reconstruction`  created: 2015-07-10 11:57:29 merged: 2015-08-08 07:11:12

51. [10592](http://github.com/cms-sw/cmssw/pull/10592){:target="_blank"}  from **@lgray**: Pileup summary info slimmer for MiniAOD `analysis`  created: 2015-08-05 18:21:35 merged: 2015-08-08 07:01:35

52. [10622](http://github.com/cms-sw/cmssw/pull/10622){:target="_blank"}  from **@deguio**: remove HLT monitoring from standard offline trigger sequence `dqm`  created: 2015-08-07 10:45:37 merged: 2015-08-08 07:01:23

53. [10607](http://github.com/cms-sw/cmssw/pull/10607){:target="_blank"}  from **@davidlange6**: add a simple retry logic to das queries `operations`  `pdmv`  created: 2015-08-06 15:57:26 merged: 2015-08-07 08:06:56

54. [10505](http://github.com/cms-sw/cmssw/pull/10505){:target="_blank"}  from **@richard-cms**: Add 15GeV cut to electron seeds for HI workflow (75X backport of #10504) `reconstruction`  created: 2015-07-31 16:59:34 merged: 2015-08-06 13:21:42

55. [10521](http://github.com/cms-sw/cmssw/pull/10521){:target="_blank"}  from **@mrcarver**: CMSHLT-508 75X PR to update DQM modules `dqm`  created: 2015-08-02 22:10:54 merged: 2015-08-06 13:21:36

56. [10525](http://github.com/cms-sw/cmssw/pull/10525){:target="_blank"}  from **@lgray**: Alter VID tools to check for already existing ID Definitions when being switched on (75X) `analysis`  created: 2015-08-03 10:24:11 merged: 2015-08-06 13:21:30

57. [10565](http://github.com/cms-sw/cmssw/pull/10565){:target="_blank"}  from **@mbluj**: Cleaning of RecoTauTag/HLTProducers package (75X) `hlt`  created: 2015-08-04 13:52:57 merged: 2015-08-06 13:16:29

58. [10536](http://github.com/cms-sw/cmssw/pull/10536){:target="_blank"}  from **@alja**: 75 Fireworks: remove debug info from conical region 3D view  `visualization`  created: 2015-08-03 18:11:48 merged: 2015-08-06 13:16:17

59. [10558](http://github.com/cms-sw/cmssw/pull/10558){:target="_blank"}  from **@boudoul**: Cleaning matrix75 x `analysis`  `core`  `operations`  `pdmv`  created: 2015-08-04 11:34:37 merged: 2015-08-06 07:44:51

60. [10572](http://github.com/cms-sw/cmssw/pull/10572){:target="_blank"}  from **@kirschen**: Backport: make PFJetId-calculation configurable with maxEta parameter, set defa `hlt`  created: 2015-08-04 20:09:51 merged: 2015-08-06 07:36:26

61. [10600](http://github.com/cms-sw/cmssw/pull/10600){:target="_blank"}  from **@davidlange6**: 75x version of moving plugins in HLTrigger/JetMET to plugins (t2) `hlt`  created: 2015-08-06 07:29:29 merged: 2015-08-06 07:34:47

62. [10578](http://github.com/cms-sw/cmssw/pull/10578){:target="_blank"}  from **@cms-sw**: Revert "adding HLT object monitoring to HLT online DQM" `dqm`  created: 2015-08-05 08:32:18 merged: 2015-08-05 08:38:26

63. [10401](http://github.com/cms-sw/cmssw/pull/10401){:target="_blank"}  from **@argiro**: expanded typdefs in plugin definition `db`  created: 2015-07-27 16:06:57 merged: 2015-08-05 08:26:46

64. [10546](http://github.com/cms-sw/cmssw/pull/10546){:target="_blank"}  from **@Martin-Grunewald**: L1T fixes for ConfDB parsing (75X) `l1`  created: 2015-08-04 07:31:15 merged: 2015-08-04 18:31:30

65. [10539](http://github.com/cms-sw/cmssw/pull/10539){:target="_blank"}  from **@Sam-Harper**: fixing memory leak in EgammaHLTNxNClusterProducer :75X `hlt`  created: 2015-08-03 19:15:26 merged: 2015-08-04 13:32:18

#### CMSDIST Changes between Tags REL/CMSSW_7_5_1/slc6_amd64_gcc491 and REL/CMSSW_7_5_2/slc6_amd64_gcc491:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_5_1/slc6_amd64_gcc491...REL/CMSSW_7_5_2/slc6_amd64_gcc491)



1. [1747](http://github.com/cms-sw/cmsdist/pull/1747){:target="_blank"}  from **@degano**: Advance RecoEgamma/PhotonIdentification data to V01-00-03 created: 2015-08-19 09:30:49 merged: 2015-08-19 09:30:52

2. [1724](http://github.com/cms-sw/cmsdist/pull/1724){:target="_blank"}  from **@degano**: Advance RecoEgamma/ElectronIdentification and PhotonIdentification data created: 2015-08-06 20:25:54 merged: 2015-08-06 20:26:19
