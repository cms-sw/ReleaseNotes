---
layout: post
rel_link:  "8_1_0_pre6"
title:  "CMSSW_8_1_0_pre6"
date:   2016-05-30 06:25:20
categories: cmssw
relmajor: 8
relminor: 1
relsubminor: 0
relpre: _pre6
---

# CMSSW_8_1_0_pre6
#### Changes since CMSSW_8_1_0_pre5:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_1_0_pre5...CMSSW_8_1_0_pre6)



1. [14677](http://github.com/cms-sw/cmssw/pull/14677){:target="_blank"}  from **@slava77**: cleanup RawToDigi redefinition of already loaded from RawToDigi_cff (bp of #14675) `operations`  created: 2016-05-28 01:21:14 merged: 2016-05-29 20:01:57

2. [14667](http://github.com/cms-sw/cmssw/pull/14667){:target="_blank"}  from **@kpedro88**: remove unneeded hgchebackDigitizer `simulation`  created: 2016-05-27 15:36:39 merged: 2016-05-28 18:59:37

3. [14662](http://github.com/cms-sw/cmssw/pull/14662){:target="_blank"}  from **@VinInn**: fix crash in case Limit on the number of clusters is really exceeded. `reconstruction`  created: 2016-05-27 14:10:11 merged: 2016-05-27 18:22:02

4. [14661](http://github.com/cms-sw/cmssw/pull/14661){:target="_blank"}  from **@VinInn**: fix crash in case Limit on the number of clusters is really exceeded. `reconstruction`  created: 2016-05-27 14:02:01 merged: 2016-05-28 18:59:51

5. [14658](http://github.com/cms-sw/cmssw/pull/14658){:target="_blank"}  from **@ggovi**: Fix for handling copy of offline synchronized tags `db`  created: 2016-05-27 12:32:55 merged: 2016-05-29 19:58:41

6. [14657](http://github.com/cms-sw/cmssw/pull/14657){:target="_blank"}  from **@ggovi**: Fix for handling copy of offline synchronized tags `db`  created: 2016-05-27 12:32:17 merged: 2016-05-27 16:52:14

7. [14656](http://github.com/cms-sw/cmssw/pull/14656){:target="_blank"}  from **@jshlee**: fireworks Gem and me0 segments 81x `visualization`  created: 2016-05-27 11:38:54 merged: 2016-05-28 19:00:03

8. [14654](http://github.com/cms-sw/cmssw/pull/14654){:target="_blank"}  from **@cms-l1t-offline**: Change default caloParams to use Tau Iso Option 21 `comparison`  `l1`  created: 2016-05-27 08:45:59 merged: 2016-05-27 08:47:24

9. [14653](http://github.com/cms-sw/cmssw/pull/14653){:target="_blank"}  from **@davidlt**: Blacklist -xSSE3 (ICC) in condformats_serialization_generate.py `comparison`  `db`  created: 2016-05-27 08:29:30 merged: 2016-05-27 08:29:44

10. [14651](http://github.com/cms-sw/cmssw/pull/14651){:target="_blank"}  from **@cms-l1t-offline**: Restore overflow check for et and ht sums (81x) `l1`  created: 2016-05-27 01:26:48 merged: 2016-05-27 08:38:57

11. [14650](http://github.com/cms-sw/cmssw/pull/14650){:target="_blank"}  from **@cms-l1t-offline**: Restore overflow check for et and ht sums `l1`  created: 2016-05-26 22:54:34 merged: 2016-05-27 08:39:07

12. [14648](http://github.com/cms-sw/cmssw/pull/14648){:target="_blank"}  from **@kpedro88**: remove redundant HGCal unit test `simulation`  created: 2016-05-26 18:54:25 merged: 2016-05-27 08:22:27

13. [14647](http://github.com/cms-sw/cmssw/pull/14647){:target="_blank"}  from **@cms-l1t-offline**: Adding L1REPACK:FullMC workflow to run on RAW of MC (80x) `operations`  created: 2016-05-26 16:26:25 merged: 2016-05-27 07:46:17

14. [14646](http://github.com/cms-sw/cmssw/pull/14646){:target="_blank"}  from **@cms-l1t-offline**: MCprod l1t Tau Iso Option-21 80x `l1`  created: 2016-05-26 16:22:17 merged: 2016-05-27 08:41:16

15. [14640](http://github.com/cms-sw/cmssw/pull/14640){:target="_blank"}  from **@wmtan**: Use unique_ptr, not auto_ptr, in Full Simulation `l1`  `simulation`  created: 2016-05-26 05:17:32 merged: 2016-05-27 08:25:02

16. [14639](http://github.com/cms-sw/cmssw/pull/14639){:target="_blank"}  from **@cms-tau-pog**: restore functionality of removeMCMatching in PAT coreTools.py `analysis`  `reconstruction`  created: 2016-05-25 21:17:49 merged: 2016-05-28 19:00:08

17. [14635](http://github.com/cms-sw/cmssw/pull/14635){:target="_blank"}  from **@cms-l1t-offline**: Adding L1REPACK:FullMC workflow to run on RAW of MC. `operations`  created: 2016-05-25 14:40:35 merged: 2016-05-27 07:38:17

18. [14633](http://github.com/cms-sw/cmssw/pull/14633){:target="_blank"}  from **@ggovi**: Several improvements for the conddb tools `db`  created: 2016-05-25 13:04:34 merged: 2016-05-26 13:25:52

19. [14629](http://github.com/cms-sw/cmssw/pull/14629){:target="_blank"}  from **@gartung**: don't disable any default checkers as this causes the CMS one to not run `comparison`  `core`  created: 2016-05-24 20:39:09 merged: 2016-05-25 05:42:55

20. [14628](http://github.com/cms-sw/cmssw/pull/14628){:target="_blank"}  from **@boudoul**: cleaning obsolete names of phase2 geometry in tracker packages `analysis`  `simulation`  created: 2016-05-24 18:47:58 merged: 2016-05-25 16:15:53

21. [14621](http://github.com/cms-sw/cmssw/pull/14621){:target="_blank"}  from **@makortel**: Use pixel seed extension for phase1 in initialStep `reconstruction`  created: 2016-05-24 15:38:08 merged: 2016-05-26 17:35:28

22. [14618](http://github.com/cms-sw/cmssw/pull/14618){:target="_blank"}  from **@safarzad**: adding HLTPFMET170_BeamHaloCleaned to SUSY DQM `dqm`  created: 2016-05-24 10:52:44 merged: 2016-05-25 15:43:47

23. [14617](http://github.com/cms-sw/cmssw/pull/14617){:target="_blank"}  from **@cms-l1t-offline**: Clean-up L1T unpacker warnings `l1`  created: 2016-05-24 10:38:32 merged: 2016-05-24 15:10:43

24. [14614](http://github.com/cms-sw/cmssw/pull/14614){:target="_blank"}  from **@mtosi**: fix tracking DQM client config `dqm`  created: 2016-05-24 10:21:08 merged: 2016-05-24 15:11:05

25. [14613](http://github.com/cms-sw/cmssw/pull/14613){:target="_blank"}  from **@cms-l1t-offline**: Update OMTF treatment of Muons at edge of OMTF acceptance `l1`  created: 2016-05-24 09:55:18 merged: 2016-05-24 15:10:53

26. [14610](http://github.com/cms-sw/cmssw/pull/14610){:target="_blank"}  from **@boudoul**: Introducing PU WFs for phase2 `pdmv`  created: 2016-05-23 20:14:38 merged: 2016-05-25 15:51:57

27. [14608](http://github.com/cms-sw/cmssw/pull/14608){:target="_blank"}  from **@mmarionncern**: Fix posftix and scheduled mode issue in the runMETUncertainty tool `analysis`  `reconstruction`  created: 2016-05-23 17:52:20 merged: 2016-05-27 07:36:30

28. [14604](http://github.com/cms-sw/cmssw/pull/14604){:target="_blank"}  from **@cms-l1t-offline**: Update OMTF treatment of Muon at edge of OMTF acceptance `l1`  created: 2016-05-23 10:09:42 merged: 2016-05-23 12:35:32

29. [14602](http://github.com/cms-sw/cmssw/pull/14602){:target="_blank"}  from **@ndaci**:  Add a cut in the HLTPFJetIDProducer module. `hlt`  created: 2016-05-23 08:34:01 merged: 2016-05-24 15:11:16

30. [14601](http://github.com/cms-sw/cmssw/pull/14601){:target="_blank"}  from **@ndaci**: Add a cut in the HLTPFJetIDProducer module. `hlt`  created: 2016-05-23 08:32:19 merged: 2016-05-24 08:14:02

31. [14600](http://github.com/cms-sw/cmssw/pull/14600){:target="_blank"}  from **@CTPPS**: CTPPS: new CondFormats related to TOTEM RP raw data and digi - backport of #13838 `alca`  `db`  created: 2016-05-23 08:02:55 merged: 2016-05-27 16:36:28

32. [14599](http://github.com/cms-sw/cmssw/pull/14599){:target="_blank"}  from **@kpedro88**: Fix QIE11 unpacking bug `reconstruction`  created: 2016-05-22 21:44:29 merged: 2016-05-25 06:10:52

33. [14598](http://github.com/cms-sw/cmssw/pull/14598){:target="_blank"}  from **@ebrondol**: Phase2 tracking reconstruction in 81X `reconstruction`  `simulation`  created: 2016-05-22 15:15:13 merged: 2016-05-25 15:52:06

34. [14596](http://github.com/cms-sw/cmssw/pull/14596){:target="_blank"}  from **@smuzaffar**: Fix for runtestTqafTopEventSelection unit test: use againstElectronVLooseMVA6 instead of againstElectronVLooseMVA5 `analysis`  `reconstruction`  created: 2016-05-21 16:19:30 merged: 2016-05-24 18:53:09

35. [14594](http://github.com/cms-sw/cmssw/pull/14594){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx83 Update Geometry to handle minimum depth > 1 and max phi > 72 `geometry`  `reconstruction`  created: 2016-05-20 18:01:57 merged: 2016-05-25 06:10:30

36. [14592](http://github.com/cms-sw/cmssw/pull/14592){:target="_blank"}  from **@ghellwig**: Latest MillePede fixes 81X `alca`  created: 2016-05-20 16:24:56 merged: 2016-05-24 09:37:28

37. [14591](http://github.com/cms-sw/cmssw/pull/14591){:target="_blank"}  from **@cms-l1t-offline**: Clean-up L1T unpacker warnings `l1`  created: 2016-05-20 14:18:31 merged: 2016-05-22 07:10:06

38. [14590](http://github.com/cms-sw/cmssw/pull/14590){:target="_blank"}  from **@duanders**: Fix deltaR calculation in widejet module (81X) `comparison`  `hlt`  created: 2016-05-20 13:36:00 merged: 2016-05-22 07:12:21

39. [14589](http://github.com/cms-sw/cmssw/pull/14589){:target="_blank"}  from **@duanders**: Use PFMETCollection in scouting PF producer (81X) `comparison`  `hlt`  created: 2016-05-20 12:54:05 merged: 2016-05-22 07:11:49

40. [14588](http://github.com/cms-sw/cmssw/pull/14588){:target="_blank"}  from **@duanders**: Use PFMETCollection in scouting PF producer `hlt`  created: 2016-05-20 12:26:11 merged: 2016-05-23 12:12:16

41. [14587](http://github.com/cms-sw/cmssw/pull/14587){:target="_blank"}  from **@duanders**: Fix deltaR calculation in HLT widejet module `hlt`  created: 2016-05-20 11:49:24 merged: 2016-05-22 07:12:34

42. [14586](http://github.com/cms-sw/cmssw/pull/14586){:target="_blank"}  from **@schneiml**: Phase 1 Pixel DQM (number 4, the story continues) `dqm`  `reconstruction`  created: 2016-05-20 11:27:41 merged: 2016-05-24 08:40:47

43. [14584](http://github.com/cms-sw/cmssw/pull/14584){:target="_blank"}  from **@friccita**: use full geometry cffs for MB plotting scripts `comparison`  `dqm`  `geometry`  created: 2016-05-20 09:25:49 merged: 2016-05-25 06:11:30

44. [14583](http://github.com/cms-sw/cmssw/pull/14583){:target="_blank"}  from **@ggovi**: Fix for GTEntry_t hash function `db`  created: 2016-05-20 08:41:20 merged: 2016-05-25 16:26:24

45. [14582](http://github.com/cms-sw/cmssw/pull/14582){:target="_blank"}  from **@olivito**: SUSY HLT DQM updates for trimuon and dimu+MET paths, 81X `dqm`  created: 2016-05-19 23:10:06 merged: 2016-05-25 15:53:58

46. [14580](http://github.com/cms-sw/cmssw/pull/14580){:target="_blank"}  from **@CTPPS**: CTPPS: new DataFormats for local TOTEM RP reconstruction, backport of #14134 `reconstruction`  created: 2016-05-19 22:25:50 merged: 2016-05-24 08:14:47

47. [14579](http://github.com/cms-sw/cmssw/pull/14579){:target="_blank"}  from **@CTPPS**: CTPPS: new DataFormats related to TOTEM RP raw data and digi - backport of PR #13837 `reconstruction`  `simulation`  created: 2016-05-19 22:10:55 merged: 2016-05-24 18:54:32

48. [14578](http://github.com/cms-sw/cmssw/pull/14578){:target="_blank"}  from **@CTPPS**: Adding new detectors - integration of RomanPot detectors for CTPPS project - backport of PR #13766 `simulation`  created: 2016-05-19 21:54:25 merged: 2016-05-22 07:15:12

49. [14574](http://github.com/cms-sw/cmssw/pull/14574){:target="_blank"}  from **@smuzaffar**: use era Run2_2016 for testRecoMETMETProducers unit test `reconstruction`  created: 2016-05-19 18:13:40 merged: 2016-05-19 20:27:15

50. [14572](http://github.com/cms-sw/cmssw/pull/14572){:target="_blank"}  from **@kpedro88**: fix scope of hbheCells `simulation`  created: 2016-05-19 17:29:36 merged: 2016-05-20 07:17:21

51. [14571](http://github.com/cms-sw/cmssw/pull/14571){:target="_blank"}  from **@mmusich**: 81X  SiStrip Gains PCL cleanup `alca`  `db`  `operations`  `pdmv`  created: 2016-05-19 13:21:42 merged: 2016-05-25 15:45:15

52. [14570](http://github.com/cms-sw/cmssw/pull/14570){:target="_blank"}  from **@cms-l1t-offline**: Update L1T to l1t-tsg-v7-cand performance (80x) `dqm`  `l1`  created: 2016-05-19 10:00:36 merged: 2016-05-23 13:07:07

53. [14569](http://github.com/cms-sw/cmssw/pull/14569){:target="_blank"}  from **@idebruyn**: TH1ClusterCharge and TH1ClusterStoNCorr plots per ring `dqm`  created: 2016-05-19 09:53:43 merged: 2016-05-19 18:46:09

54. [14568](http://github.com/cms-sw/cmssw/pull/14568){:target="_blank"}  from **@idebruyn**: TH1ClusterCharge and TH1ClusterStoNCorr plots per ring `dqm`  created: 2016-05-19 09:53:38 merged: 2016-05-29 19:58:28

55. [14567](http://github.com/cms-sw/cmssw/pull/14567){:target="_blank"}  from **@dmitrijus**: Disable broken Ewk*DQM modules `dqm`  created: 2016-05-19 09:08:21 merged: 2016-05-22 07:11:59

56. [14566](http://github.com/cms-sw/cmssw/pull/14566){:target="_blank"}  from **@OlivierBondu**: Update ResonanceDecayFilterHook.cc `generators`  created: 2016-05-19 08:07:11 merged: 2016-05-22 07:14:43

57. [14563](http://github.com/cms-sw/cmssw/pull/14563){:target="_blank"}  from **@davidlt**: CondCore/PopCon: define static constexpr member `alca`  `db`  created: 2016-05-19 07:01:52 merged: 2016-05-19 10:18:25

58. [14561](http://github.com/cms-sw/cmssw/pull/14561){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-hgx53 Add 4 module setup of TB `geometry`  `simulation`  created: 2016-05-18 22:13:10 merged: 2016-05-19 18:45:29

59. [14560](http://github.com/cms-sw/cmssw/pull/14560){:target="_blank"}  from **@Dr15Jones**: RootDelayedReader now uses std::exception_ptr `core`  created: 2016-05-18 21:32:03 merged: 2016-05-19 07:02:12

60. [14558](http://github.com/cms-sw/cmssw/pull/14558){:target="_blank"}  from **@alja**: 80x Fireworks: Make shortcut to palette interface  `comparison`  `visualization`  created: 2016-05-18 18:24:09 merged: 2016-05-18 19:35:29

61. [14557](http://github.com/cms-sw/cmssw/pull/14557){:target="_blank"}  from **@davidlange6**: change das_client.py to das_client in cmsDriver `comparison`  `operations`  `pdmv`  created: 2016-05-18 15:37:54 merged: 2016-05-18 18:55:00

62. [14556](http://github.com/cms-sw/cmssw/pull/14556){:target="_blank"}  from **@OlivierBondu**: Update ResonanceDecayFilterHook.cc `comparison`  `generators`  created: 2016-05-18 14:42:16 merged: 2016-05-19 08:31:19

63. [14554](http://github.com/cms-sw/cmssw/pull/14554){:target="_blank"}  from **@ANSH0712**: Fastsim triplet seed selection branch `fastsim`  `reconstruction`  created: 2016-05-18 13:22:16 merged: 2016-05-22 17:08:24

64. [14553](http://github.com/cms-sw/cmssw/pull/14553){:target="_blank"}  from **@cms-l1t-offline**: Rekovic l1 repack 2016 2015 cmssw81x `l1`  `operations`  created: 2016-05-18 13:12:18 merged: 2016-05-19 08:33:48

65. [14551](http://github.com/cms-sw/cmssw/pull/14551){:target="_blank"}  from **@cms-l1t-offline**: L1 repack 2016 2015 (Full, uGT, Full2015Data) cmssw808 `l1`  `operations`  created: 2016-05-18 12:30:44 merged: 2016-05-23 13:08:37

66. [14550](http://github.com/cms-sw/cmssw/pull/14550){:target="_blank"}  from **@civanch**: Fixed Sim exceptions and printouts `simulation`  created: 2016-05-18 12:21:20 merged: 2016-05-23 07:10:34

67. [14548](http://github.com/cms-sw/cmssw/pull/14548){:target="_blank"}  from **@dmitrijus**: Disable broken Ewk*DQM modules `dqm`  created: 2016-05-18 11:56:07 merged: 2016-05-18 16:07:15

68. [14545](http://github.com/cms-sw/cmssw/pull/14545){:target="_blank"}  from **@mmusich**: Include full alignment and APE for Pixel Phase-I detector `alca`  `geometry`  created: 2016-05-18 08:52:35 merged: 2016-05-19 14:44:34

69. [14544](http://github.com/cms-sw/cmssw/pull/14544){:target="_blank"}  from **@makortel**: Unify tracking iteration configurations in RECO, DQM, and VALIDATION, and automatize cluster removal `dqm`  `reconstruction`  `simulation`  created: 2016-05-18 07:58:08 merged: 2016-05-25 15:53:27

70. [14543](http://github.com/cms-sw/cmssw/pull/14543){:target="_blank"}  from **@smorovic**: Adding merging type (DAQ) and changing defaults (81X) `daq`  `dqm`  `hlt`  `reconstruction`  created: 2016-05-18 07:46:14 merged: 2016-05-18 15:49:29

71. [14542](http://github.com/cms-sw/cmssw/pull/14542){:target="_blank"}  from **@Dr15Jones**: Made static TiXmlBase::entity const `comparison`  `core`  created: 2016-05-17 21:44:49 merged: 2016-05-19 07:03:46

72. [14541](http://github.com/cms-sw/cmssw/pull/14541){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca45 Add a filter which filters out isolated bunch with Jet triggers `alca`  `operations`  created: 2016-05-17 21:32:22 merged: 2016-05-28 19:01:05

73. [14538](http://github.com/cms-sw/cmssw/pull/14538){:target="_blank"}  from **@lathomas**: Typo correction in config file `reconstruction`  created: 2016-05-17 17:22:18 merged: 2016-05-20 07:17:50

74. [14537](http://github.com/cms-sw/cmssw/pull/14537){:target="_blank"}  from **@bsunanda**: bsunanda:Phase2-gem15 ME0 with eta partitions `geometry`  created: 2016-05-17 16:35:48 merged: 2016-05-19 10:21:04

75. [14536](http://github.com/cms-sw/cmssw/pull/14536){:target="_blank"}  from **@davidlt**: Utilities/StaticAnalyzers: adjust to LLVM/Clang 3.8.0 `comparison`  `core`  created: 2016-05-17 16:20:15 merged: 2016-05-17 16:20:24

76. [14535](http://github.com/cms-sw/cmssw/pull/14535){:target="_blank"}  from **@cms-l1t-offline**: Update L1T to l1t-tsg-v7-cand performance (81x) `comparison`  `dqm`  `l1`  created: 2016-05-17 14:39:36 merged: 2016-05-19 08:32:47

77. [14533](http://github.com/cms-sw/cmssw/pull/14533){:target="_blank"}  from **@fioriNTU**: retune max value for Chi2 `dqm`  created: 2016-05-17 14:19:28 merged: 2016-05-18 15:49:50

78. [14531](http://github.com/cms-sw/cmssw/pull/14531){:target="_blank"}  from **@fioriNTU**: retune max value for Chi2 `dqm`  created: 2016-05-17 14:08:24 merged: 2016-05-22 07:13:23

79. [14530](http://github.com/cms-sw/cmssw/pull/14530){:target="_blank"}  from **@rmanzoni**: [RecoTauTag] allow complete relax of tau isolation at high pt `reconstruction`  created: 2016-05-17 13:11:42 merged: 2016-05-22 07:13:02

80. [14529](http://github.com/cms-sw/cmssw/pull/14529){:target="_blank"}  from **@rmanzoni**: [RecoTauTag] allow complete relax of tau isolation at high pt `reconstruction`  created: 2016-05-17 12:24:20 merged: 2016-05-18 07:20:53

81. [14528](http://github.com/cms-sw/cmssw/pull/14528){:target="_blank"}  from **@smorovic**: Adding merging type (DAQ) and changing defaults `daq`  `dqm`  `hlt`  `reconstruction`  created: 2016-05-17 09:53:57 merged: 2016-05-22 07:14:19

82. [14524](http://github.com/cms-sw/cmssw/pull/14524){:target="_blank"}  from **@jruizvar**: Updates Calo Scouting triggers in EXO DQM  (81X) `dqm`  created: 2016-05-16 21:59:00 merged: 2016-05-18 07:28:03

83. [14523](http://github.com/cms-sw/cmssw/pull/14523){:target="_blank"}  from **@ebrondol**: 2023 workflows up to tracking reco `geometry`  `operations`  `pdmv`  `reconstruction`  `simulation`  created: 2016-05-16 19:42:10 merged: 2016-05-20 07:29:26

84. [14522](http://github.com/cms-sw/cmssw/pull/14522){:target="_blank"}  from **@Dr15Jones**: Added Erf and Landau functions to FormulaEvaluator `analysis`  `reconstruction`  created: 2016-05-16 18:46:14 merged: 2016-05-18 19:34:31

85. [14521](http://github.com/cms-sw/cmssw/pull/14521){:target="_blank"}  from **@alja**: 80x Fireworks: Implement palettes `comparison`  `visualization`  created: 2016-05-16 18:18:16 merged: 2016-05-17 12:39:02

86. [14520](http://github.com/cms-sw/cmssw/pull/14520){:target="_blank"}  from **@aspiezia**: Adding the cosmic during collision reconstruction in CMSSW81X `fastsim`  `operations`  `reconstruction`  created: 2016-05-16 17:54:49 merged: 2016-05-25 16:08:58

87. [14518](http://github.com/cms-sw/cmssw/pull/14518){:target="_blank"}  from **@mbandrews**: Fix statistics of Trend plots `dqm`  created: 2016-05-16 16:02:57 merged: 2016-05-25 06:12:30

88. [14513](http://github.com/cms-sw/cmssw/pull/14513){:target="_blank"}  from **@fioriNTU**: Ready to use cfg for shifters `analysis`  created: 2016-05-16 14:51:12 merged: 2016-05-18 08:22:35

89. [14512](http://github.com/cms-sw/cmssw/pull/14512){:target="_blank"}  from **@usarica**: Muon analysis updates 8.0.x `alca`  `analysis`  created: 2016-05-16 13:36:35 merged: 2016-05-24 08:41:20

90. [14511](http://github.com/cms-sw/cmssw/pull/14511){:target="_blank"}  from **@usarica**: Muon analysis updates 8.1.x `alca`  `analysis`  created: 2016-05-16 13:35:09 merged: 2016-05-18 08:26:52

91. [14507](http://github.com/cms-sw/cmssw/pull/14507){:target="_blank"}  from **@ggovi**: Fix for GTEntry_t hash function `db`  created: 2016-05-15 16:12:24 merged: 2016-05-18 08:09:29

92. [14506](http://github.com/cms-sw/cmssw/pull/14506){:target="_blank"}  from **@sarafiorendi**: add tentative propagation to ME2 if MB2 fails (backport of #14505) `reconstruction`  created: 2016-05-14 17:45:18 merged: 2016-05-18 19:35:41

93. [14505](http://github.com/cms-sw/cmssw/pull/14505){:target="_blank"}  from **@sarafiorendi**: Seeding of L2 muons: propagate L1 cands to ME2 if propagation to MB2 fails  `reconstruction`  created: 2016-05-14 17:38:34 merged: 2016-05-18 07:26:33

94. [14502](http://github.com/cms-sw/cmssw/pull/14502){:target="_blank"}  from **@fwyzard**: L1TGlobalPrescaler: implement arbitrary prescales on top of the existing L1 uGT results `core`  `l1`  created: 2016-05-13 23:24:33 merged: 2016-05-17 15:47:31

95. [14501](http://github.com/cms-sw/cmssw/pull/14501){:target="_blank"}  from **@bartosik-hep**: 80X: HLT path/module-name updates in the HLTObjectMonitor `dqm`  created: 2016-05-13 21:48:13 merged: 2016-05-23 12:14:04

96. [14500](http://github.com/cms-sw/cmssw/pull/14500){:target="_blank"}  from **@bartosik-hep**: HLT path/module-name updates in the HLTObjectMonitor `dqm`  created: 2016-05-13 21:30:45 merged: 2016-05-19 18:46:50

97. [14499](http://github.com/cms-sw/cmssw/pull/14499){:target="_blank"}  from **@alja**: 80x Fireworks:Fix problem in finding detail view for given class type `comparison`  `visualization`  created: 2016-05-13 20:31:09 merged: 2016-05-17 12:39:14

98. [14496](http://github.com/cms-sw/cmssw/pull/14496){:target="_blank"}  from **@mkirsano**: Prepare Pythia8Interface to pythia8 219 `comparison`  `generators`  created: 2016-05-13 16:45:08 merged: 2016-05-18 08:07:48

99. [14494](http://github.com/cms-sw/cmssw/pull/14494){:target="_blank"}  from **@Dr15Jones**: Added Erf and Landau functions to FormulaEvaluator `analysis`  `reconstruction`  created: 2016-05-13 14:34:26 merged: 2016-05-18 07:24:11

100. [14489](http://github.com/cms-sw/cmssw/pull/14489){:target="_blank"}  from **@cecchcms**: some APV plots removed `dqm`  created: 2016-05-13 07:27:01 merged: 2016-05-18 07:24:22

101. [14486](http://github.com/cms-sw/cmssw/pull/14486){:target="_blank"}  from **@alja**:  80x Fireworks:Update table view content (attempt No2) `comparison`  `visualization`  created: 2016-05-12 20:00:18 merged: 2016-05-17 12:39:25

102. [14483](http://github.com/cms-sw/cmssw/pull/14483){:target="_blank"}  from **@andresib**: Update SUSYBSM_HLT_VBF_Mu_cff.py `dqm`  created: 2016-05-12 18:40:32 merged: 2016-05-25 15:49:14

103. [14482](http://github.com/cms-sw/cmssw/pull/14482){:target="_blank"}  from **@kpedro88**: add QIE11 support in hcal digitization `alca`  `geometry`  `operations`  `simulation`  created: 2016-05-12 18:38:50 merged: 2016-05-17 15:50:50

104. [14478](http://github.com/cms-sw/cmssw/pull/14478){:target="_blank"}  from **@davidlange6**: remove some printout in every event `comparison`  `l1`  created: 2016-05-12 14:41:38 merged: 2016-05-12 14:41:46

105. [14477](http://github.com/cms-sw/cmssw/pull/14477){:target="_blank"}  from **@fwyzard**: L1TGlobalProducer: migrate to stream module (80x) `l1`  created: 2016-05-12 14:01:18 merged: 2016-05-23 13:09:20

106. [14474](http://github.com/cms-sw/cmssw/pull/14474){:target="_blank"}  from **@fwyzard**: HLT DQM: add protection for empty L1 uGT collection `dqm`  created: 2016-05-12 12:43:38 merged: 2016-05-12 14:37:37

107. [14469](http://github.com/cms-sw/cmssw/pull/14469){:target="_blank"}  from **@hengne**: relval matrix update `pdmv`  created: 2016-05-12 07:52:28 merged: 2016-05-18 09:44:49

108. [14467](http://github.com/cms-sw/cmssw/pull/14467){:target="_blank"}  from **@VinInn**: fix det search tollerances for Cosmics `reconstruction`  created: 2016-05-12 05:14:06 merged: 2016-05-24 08:16:32

109. [14465](http://github.com/cms-sw/cmssw/pull/14465){:target="_blank"}  from **@cms-l1t-offline**: L1T Minimum Bias Trigger (80x) `l1`  created: 2016-05-11 21:12:49 merged: 2016-05-12 14:38:32

110. [14462](http://github.com/cms-sw/cmssw/pull/14462){:target="_blank"}  from **@kpedro88**: Monitor CASTOR table data (80X) `alca`  `reconstruction`  `simulation`  created: 2016-05-11 19:55:18 merged: 2016-05-27 08:29:49

111. [14461](http://github.com/cms-sw/cmssw/pull/14461){:target="_blank"}  from **@kpedro88**: Monitor CASTOR table data (81X) `alca`  `reconstruction`  `simulation`  created: 2016-05-11 19:55:14 merged: 2016-05-20 10:41:27

112. [14456](http://github.com/cms-sw/cmssw/pull/14456){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx82 Add the possibility of a FrontEnd map for HCAL `alca`  `db`  created: 2016-05-11 15:35:18 merged: 2016-05-22 07:08:22

113. [14451](http://github.com/cms-sw/cmssw/pull/14451){:target="_blank"}  from **@lowette**: Geometric CPE and persistent rechits for Phase 2 tracker local reco `reconstruction`  created: 2016-05-11 12:01:07 merged: 2016-05-19 09:24:34

114. [14449](http://github.com/cms-sw/cmssw/pull/14449){:target="_blank"}  from **@kovitang**: Negative and positive  C-tagger in 81X `analysis`  `reconstruction`  created: 2016-05-11 10:14:29 merged: 2016-05-18 07:18:24

115. [14446](http://github.com/cms-sw/cmssw/pull/14446){:target="_blank"}  from **@cms-tsg-storm**: HLT development in May (81X) `alca`  `dqm`  `hlt`  created: 2016-05-11 08:02:55 merged: 2016-05-27 08:26:18

116. [14445](http://github.com/cms-sw/cmssw/pull/14445){:target="_blank"}  from **@cms-tsg-storm**: HLT development in May (80X) `alca`  `dqm`  `hlt`  created: 2016-05-11 08:02:14 merged: 2016-05-27 16:38:33

117. [14437](http://github.com/cms-sw/cmssw/pull/14437){:target="_blank"}  from **@ggovi**: Changes for O2O deployment and monitoring `db`  created: 2016-05-10 15:45:03 merged: 2016-05-27 07:41:47

118. [14421](http://github.com/cms-sw/cmssw/pull/14421){:target="_blank"}  from **@diguida**: Fixes for RunInfo O2O and cleanup of PopCon interface (80X) `alca`  `db`  created: 2016-05-09 16:51:24 merged: 2016-05-25 15:52:17

119. [14420](http://github.com/cms-sw/cmssw/pull/14420){:target="_blank"}  from **@diguida**: Fixes for RunInfo O2O and cleanup of PopCon interface `alca`  `db`  created: 2016-05-09 16:51:13 merged: 2016-05-18 07:28:16

120. [14403](http://github.com/cms-sw/cmssw/pull/14403){:target="_blank"}  from **@wmtan**: Use unique_ptr, not auto_ptr, in L1 `l1`  created: 2016-05-07 03:38:49 merged: 2016-05-24 08:07:30

121. [14400](http://github.com/cms-sw/cmssw/pull/14400){:target="_blank"}  from **@jshlee**: GEM and ME0 segments 81 x `reconstruction`  created: 2016-05-06 16:08:23 merged: 2016-05-26 23:48:34

122. [14395](http://github.com/cms-sw/cmssw/pull/14395){:target="_blank"}  from **@slehti**: HLT Tau DQM updated to stage2 L1 `dqm`  created: 2016-05-06 13:15:58 merged: 2016-05-25 15:55:04

123. [14393](http://github.com/cms-sw/cmssw/pull/14393){:target="_blank"}  from **@olivito**: updating SUSY HLT DQM config for lep+HT triggers `dqm`  created: 2016-05-06 11:13:02 merged: 2016-05-25 16:21:40

124. [14390](http://github.com/cms-sw/cmssw/pull/14390){:target="_blank"}  from **@pvmulder**: First version of the candidatebased GhostTrack tagger `analysis`  `dqm`  `reconstruction`  created: 2016-05-05 21:16:40 merged: 2016-05-22 17:08:44

125. [14382](http://github.com/cms-sw/cmssw/pull/14382){:target="_blank"}  from **@dildick**: L1CSC Trigger Primitive conditions DB vs Python config comparator `l1`  created: 2016-05-05 00:04:13 merged: 2016-05-26 06:31:22

126. [14368](http://github.com/cms-sw/cmssw/pull/14368){:target="_blank"}  from **@tanmaymudholkar**: Added names for hardcoded constants and added one TP plot `dqm`  created: 2016-05-04 09:37:46 merged: 2016-05-18 07:34:22

127. [14361](http://github.com/cms-sw/cmssw/pull/14361){:target="_blank"}  from **@wmtan**: Use unique_ptr, not auto_ptr, in Alignment/Calibration `alca`  created: 2016-05-03 22:34:11 merged: 2016-05-18 07:33:29

128. [14356](http://github.com/cms-sw/cmssw/pull/14356){:target="_blank"}  from **@makortel**: Add pixel-only seed extension `dqm`  `hlt`  `reconstruction`  created: 2016-05-03 14:21:24 merged: 2016-05-24 08:14:35

129. [14342](http://github.com/cms-sw/cmssw/pull/14342){:target="_blank"}  from **@hengne**: relval update data workflow reco step, and re-work the LHE-based fullSim workflows for HLT validation `generators`  `pdmv`  created: 2016-05-03 09:39:04 merged: 2016-05-17 15:50:34

130. [14336](http://github.com/cms-sw/cmssw/pull/14336){:target="_blank"}  from **@Martin-Grunewald**: Prescale access for stage-2 environment (80X) `analysis`  `dqm`  `hlt`  `l1`  `reconstruction`  created: 2016-05-03 07:34:46 merged: 2016-05-29 19:59:22

131. [14328](http://github.com/cms-sw/cmssw/pull/14328){:target="_blank"}  from **@minano**: Adding getBlade/getLadder functions `dqm`  created: 2016-05-02 15:17:22 merged: 2016-05-18 07:33:04

132. [14325](http://github.com/cms-sw/cmssw/pull/14325){:target="_blank"}  from **@cms-tsg-storm**: Towards the first hlt menu for 2016 - 80X `hlt`  created: 2016-05-02 14:51:13 merged: 2016-05-12 14:40:48

133. [14312](http://github.com/cms-sw/cmssw/pull/14312){:target="_blank"}  from **@Martin-Grunewald**: Prescale access for stage-2 environment (81X) `analysis`  `dqm`  `hlt`  `l1`  `reconstruction`  created: 2016-04-29 22:15:06 merged: 2016-05-20 07:58:34

134. [14265](http://github.com/cms-sw/cmssw/pull/14265){:target="_blank"}  from **@mmusich**: DropBox metadata - 2016 (80X) `alca`  `db`  created: 2016-04-27 07:53:31 merged: 2016-05-23 12:18:29

135. [14233](http://github.com/cms-sw/cmssw/pull/14233){:target="_blank"}  from **@vdutta**: Input files for offline TkCommissioner tool, 81X `comparison`  `dqm`  created: 2016-04-25 12:20:37 merged: 2016-05-19 10:40:16

136. [14029](http://github.com/cms-sw/cmssw/pull/14029){:target="_blank"}  from **@CTPPS**: CTPPS new reconstruction geometry related to TOTEM RP detectors `alca`  `db`  `geometry`  created: 2016-04-12 07:02:06 merged: 2016-05-22 17:09:29

137. [14010](http://github.com/cms-sw/cmssw/pull/14010){:target="_blank"}  from **@ianna**: 2015 Extended Scenario with Tracker Material Variations `db`  `geometry`  created: 2016-04-11 06:21:43 merged: 2016-05-18 10:09:36

138. [13972](http://github.com/cms-sw/cmssw/pull/13972){:target="_blank"}  from **@fioriNTU**: improve TkMaps `dqm`  created: 2016-04-07 12:13:48 merged: 2016-05-27 07:42:24

139. [13930](http://github.com/cms-sw/cmssw/pull/13930){:target="_blank"}  from **@clint-richardson**: added double lepton DQM `dqm`  created: 2016-04-05 12:52:50 merged: 2016-05-25 15:52:35

140. [13877](http://github.com/cms-sw/cmssw/pull/13877){:target="_blank"}  from **@mileva**: Adding new class GEMDigiSimLink in 81X `simulation`  created: 2016-03-31 14:16:35 merged: 2016-05-25 16:12:21

141. [13813](http://github.com/cms-sw/cmssw/pull/13813){:target="_blank"}  from **@vkhristenko**: Online HCAL DQM adding a 3rd application `dqm`  created: 2016-03-23 10:56:21 merged: 2016-05-24 08:20:20

#### CMSDIST Changes between Tags REL/CMSSW_8_1_0_pre5/slc6_amd64_gcc530 and REL/CMSSW_8_1_0_pre6/slc6_amd64_gcc530:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_1_0_pre5/slc6_amd64_gcc530...REL/CMSSW_8_1_0_pre6/slc6_amd64_gcc530)



1. [2302](http://github.com/cms-sw/cmsdist/pull/2302){:target="_blank"}  from **@degano**: Update data files for L1Trigger/L1TMuon. created: 2016-05-19 07:50:45 merged: 2016-05-19 07:50:51

2. [2298](http://github.com/cms-sw/cmsdist/pull/2298){:target="_blank"}  from **@degano**: Update GeneratorInterface/EvtGenInterface data. created: 2016-05-17 07:51:36 merged: 2016-05-17 07:52:08

3. [2294](http://github.com/cms-sw/cmsdist/pull/2294){:target="_blank"}  from **@mkirsano**: move to pythia8 219 from tarball created: 2016-05-13 20:01:46 merged: 2016-05-18 08:07:40

4. [2293](http://github.com/cms-sw/cmsdist/pull/2293){:target="_blank"}  from **@degano**: Update CUDA to version 7.5. created: 2016-05-13 14:01:33 merged: 2016-05-18 08:10:28
