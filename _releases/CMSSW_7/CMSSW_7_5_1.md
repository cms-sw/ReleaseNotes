---
layout: post
rel_link:  "7_5_1"
title:  "CMSSW_7_5_1"
date:   2015-08-03 05:18:14
categories: cmssw
relmajor: 7
relminor: 5
relsubminor: 1
---

# CMSSW_7_5_1
#### Changes since CMSSW_7_5_0:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_5_0...CMSSW_7_5_1)



1. [9864](http://github.com/cms-sw/cmssw/pull/9864){:target="_blank"}  from **@cms-btv-pog**: Btag DQM: move from binomial error to ClopperPearson error for Efficiency `dqm`  created: 2015-06-24 15:31:44 merged: 2015-08-02 19:36:42

2. [10272](http://github.com/cms-sw/cmssw/pull/10272){:target="_blank"}  from **@srimanob**: Add missing FS samples, fix index, remove obsolete FSPU `pdmv`  created: 2015-07-18 22:06:19 merged: 2015-08-02 19:36:32

3. [10277](http://github.com/cms-sw/cmssw/pull/10277){:target="_blank"}  from **@muell149**: adding HLT object monitoring to HLT online DQM `dqm`  created: 2015-07-20 10:42:12 merged: 2015-08-02 19:36:23

4. [10516](http://github.com/cms-sw/cmssw/pull/10516){:target="_blank"}  from **@davidlange6**: Forward port of AlCa output module configuration improvements `alca`  `operations`  created: 2015-08-02 09:48:19 merged: 2015-08-02 19:35:06

5. [10157](http://github.com/cms-sw/cmssw/pull/10157){:target="_blank"}  from **@cms-btv-pog**: Removing CSV+SL and adding SL taggers to the default PAT jet configuration `analysis`  created: 2015-07-12 03:11:31 merged: 2015-08-02 09:56:45

6. [10446](http://github.com/cms-sw/cmssw/pull/10446){:target="_blank"}  from **@lgray**: Test AdaBoost conversion to GBRForest (75X) `reconstruction`  created: 2015-07-29 08:04:37 merged: 2015-08-02 09:56:30

7. [10473](http://github.com/cms-sw/cmssw/pull/10473){:target="_blank"}  from **@lgray**: Convert PFEGAlgo to use a GlobalCache + GBRForest (75X) `reconstruction`  created: 2015-07-30 10:54:09 merged: 2015-08-02 09:56:20

8. [10420](http://github.com/cms-sw/cmssw/pull/10420){:target="_blank"}  from **@bbockelm**: Chirp-based HTCondor updates for 7_5_X `core`  created: 2015-07-28 13:31:35 merged: 2015-08-02 09:54:39

9. [10507](http://github.com/cms-sw/cmssw/pull/10507){:target="_blank"}  from **@diguida**: Complete fix for HcalCalPedestal AlCaReco (75X) `alca`  `operations`  created: 2015-07-31 22:43:09 merged: 2015-08-02 09:53:53

10. [10483](http://github.com/cms-sw/cmssw/pull/10483){:target="_blank"}  from **@davidlange6**: Properly handle long lists of Parameters `core`  created: 2015-07-30 15:35:15 merged: 2015-07-31 11:41:02

11. [10372](http://github.com/cms-sw/cmssw/pull/10372){:target="_blank"}  from **@dertexaner**: Set MaxADC0 threshold to 9999 `reconstruction`  created: 2015-07-25 11:45:12 merged: 2015-07-31 09:36:43

12. [10074](http://github.com/cms-sw/cmssw/pull/10074){:target="_blank"}  from **@mojoe137**: back port of pixel lumi dqm from 76X to 75X `dqm`  created: 2015-07-07 15:09:22 merged: 2015-07-31 09:33:19

13. [10405](http://github.com/cms-sw/cmssw/pull/10405){:target="_blank"}  from **@richard-cms**: Backport of #10194 :Add shower-shape cut capability to electron seed producer `reconstruction`  created: 2015-07-27 19:31:43 merged: 2015-07-31 09:31:48

14. [10174](http://github.com/cms-sw/cmssw/pull/10174){:target="_blank"}  from **@covarell**: added GenLumiInfoProduct for a posteriori cross-section calculation `analysis`  created: 2015-07-13 17:23:05 merged: 2015-07-31 08:50:19

15. [10293](http://github.com/cms-sw/cmssw/pull/10293){:target="_blank"}  from **@lgray**: Fix return type in vid::CutFlowResult accessor (75X) `analysis`  created: 2015-07-21 12:49:05 merged: 2015-07-31 08:01:36

16. [10357](http://github.com/cms-sw/cmssw/pull/10357){:target="_blank"}  from **@hroskes**: Backport of #10356: Allow selection of subdetector for track splitting `alca`  created: 2015-07-24 19:05:16 merged: 2015-07-31 07:57:06

17. [10394](http://github.com/cms-sw/cmssw/pull/10394){:target="_blank"}  from @deguio: adding entry to DQM matrix for HLT monitoring **@T0** `dqm`  created: 2015-07-27 14:45:12 merged: 2015-07-31 07:56:56

18. [10325](http://github.com/cms-sw/cmssw/pull/10325){:target="_blank"}  from **@deguio**: remove Edm2ME converter from final sequence for harvesting `operations`  created: 2015-07-23 14:03:43 merged: 2015-07-31 07:55:31

19. [10336](http://github.com/cms-sw/cmssw/pull/10336){:target="_blank"}  from **@lgray**: Migrate leftover modules (75X) `analysis`  `reconstruction`  created: 2015-07-23 21:25:08 merged: 2015-07-31 07:55:04

20. [10486](http://github.com/cms-sw/cmssw/pull/10486){:target="_blank"}  from **@alja**: 75x Fireworks: hide PF user code by the default  `visualization`  created: 2015-07-30 17:37:07 merged: 2015-07-31 07:51:23

21. [10488](http://github.com/cms-sw/cmssw/pull/10488){:target="_blank"}  from **@alja**: 75x Fireworks: open 3D region from context menu `visualization`  created: 2015-07-30 18:19:36 merged: 2015-07-31 07:51:08

22. [10489](http://github.com/cms-sw/cmssw/pull/10489){:target="_blank"}  from **@alja**: 75x Fireworks: port Fireworks configuration changes from 74 `visualization`  created: 2015-07-30 18:25:07 merged: 2015-07-31 07:50:53

23. [10367](http://github.com/cms-sw/cmssw/pull/10367){:target="_blank"}  from **@lgray**: Try converting RecoParticleFlow/PFTracking to GBRForest + GlobalCache (75X) `reconstruction`  created: 2015-07-25 07:50:16 merged: 2015-07-30 14:57:23

24. [10428](http://github.com/cms-sw/cmssw/pull/10428){:target="_blank"}  from **@sushilchauhan**: new vtx hist and updated dip file for LHC pub `dqm`  created: 2015-07-28 14:29:42 merged: 2015-07-30 14:56:52

25. [10469](http://github.com/cms-sw/cmssw/pull/10469){:target="_blank"}  from **@dmitrijus**:   Implement multi-processing in fastHadd to merge DQM histograms faster `dqm`  created: 2015-07-30 08:18:30 merged: 2015-07-30 14:54:24

26. [10374](http://github.com/cms-sw/cmssw/pull/10374){:target="_blank"}  from **@safarzad**: add path HLT_PFMET170_HBHECleaned, HLT_PFMET170_JetIdCleaned `dqm`  created: 2015-07-26 12:40:42 merged: 2015-07-30 07:37:00

27. [10456](http://github.com/cms-sw/cmssw/pull/10456){:target="_blank"}  from **@mdhildreth**: Change PreMixing input tags to read CSC information from unpacker  `simulation`  created: 2015-07-29 16:27:29 merged: 2015-07-29 16:44:22

28. [10369](http://github.com/cms-sw/cmssw/pull/10369){:target="_blank"}  from **@lgray**: Enhancements to GBRForest/Tree for converting TMVA classifiers (75X) `alca`  `db`  created: 2015-07-25 08:01:43 merged: 2015-07-29 07:47:10

29. [10396](http://github.com/cms-sw/cmssw/pull/10396){:target="_blank"}  from **@danduggan**: adding stage1 specific run keys for online dqm in 75x `dqm`  created: 2015-07-27 14:58:31 merged: 2015-07-29 07:46:52

30. [10422](http://github.com/cms-sw/cmssw/pull/10422){:target="_blank"}  from **@bbockelm**: Implement a well-behaved stack trace printer (75x backport) `core`  created: 2015-07-28 13:36:36 merged: 2015-07-29 07:41:59

31. [10423](http://github.com/cms-sw/cmssw/pull/10423){:target="_blank"}  from **@bbockelm**: Prevent too many chunks from being added per function call (forward port to 7_5_X). `core`  created: 2015-07-28 13:41:32 merged: 2015-07-29 07:41:50

32. [10433](http://github.com/cms-sw/cmssw/pull/10433){:target="_blank"}  from **@diguida**: Adding Global Tag for Upgrade2017 design simulation `alca`  created: 2015-07-28 17:06:57 merged: 2015-07-29 07:41:26

33. [10412](http://github.com/cms-sw/cmssw/pull/10412){:target="_blank"}  from **@cms-tsg-storm**: Legacy 50ns frozen HLT menu in the release 75X `alca`  `hlt`  `l1`  `simulation`  created: 2015-07-28 11:49:57 merged: 2015-07-29 07:41:00

34. [10436](http://github.com/cms-sw/cmssw/pull/10436){:target="_blank"}  from **@diguida**: Add vertex smearing parameters as measured during Run2015A (0T) and Run2015B (3.8T) (75X) `operations`  `simulation`  created: 2015-07-28 20:58:14 merged: 2015-07-29 07:38:15

35. [10261](http://github.com/cms-sw/cmssw/pull/10261){:target="_blank"}  from **@elimik31**: corrected electron response `simulation`  created: 2015-07-17 14:10:46 merged: 2015-07-28 12:53:14

36. [10266](http://github.com/cms-sw/cmssw/pull/10266){:target="_blank"}  from **@satan1028**: HI Centrality DQM bug fix `dqm`  created: 2015-07-17 14:57:43 merged: 2015-07-28 12:53:04

37. [10379](http://github.com/cms-sw/cmssw/pull/10379){:target="_blank"}  from **@istaslis**: Fixed invalid reference bug when # of tracks exceeds 32767 `reconstruction`  created: 2015-07-27 08:37:39 merged: 2015-07-28 12:52:21

38. [10317](http://github.com/cms-sw/cmssw/pull/10317){:target="_blank"}  from **@lgray**: Remove vestigial (and huge) GBRForest when running with PFEGAlgo (75X) `reconstruction`  created: 2015-07-23 12:30:30 merged: 2015-07-28 12:48:07

39. [10344](http://github.com/cms-sw/cmssw/pull/10344){:target="_blank"}  from **@arizzi**: Better fix to handle the error in the PVsorting `reconstruction`  created: 2015-07-24 11:44:31 merged: 2015-07-28 12:47:44

40. [10375](http://github.com/cms-sw/cmssw/pull/10375){:target="_blank"}  from **@duanders**: Trigger name change in hotline DQM (75X) `dqm`  created: 2015-07-26 20:46:59 merged: 2015-07-28 12:47:24

41. [10385](http://github.com/cms-sw/cmssw/pull/10385){:target="_blank"}  from **@MilanoBicocca-pix**: [IOMC]: update vertex smearing parameters for realistic 13 TeV 50ns collisions `simulation`  created: 2015-07-27 11:00:43 merged: 2015-07-28 12:47:04

42. [10295](http://github.com/cms-sw/cmssw/pull/10295){:target="_blank"}  from **@JetMETdqmval**: fix for running in unscheduled mode, rebased to 75X `dqm`  `operations`  created: 2015-07-21 14:28:38 merged: 2015-07-28 12:45:45

43. [10010](http://github.com/cms-sw/cmssw/pull/10010){:target="_blank"}  from **@rjwang**: correct gangedME11a flag, update LUT configuration with sectors `dqm`  created: 2015-07-02 07:16:43 merged: 2015-07-27 21:02:59

44. [8927](http://github.com/cms-sw/cmssw/pull/8927){:target="_blank"}  from **@aescalante**: Update WpM_13TeV_TuneCUETP8M1_cfi.py `generators`  created: 2015-04-30 09:45:12 merged: 2015-07-27 12:29:05

45. [10227](http://github.com/cms-sw/cmssw/pull/10227){:target="_blank"}  from **@franzoni**: SKIMS in Conf data processing 75 `operations`  created: 2015-07-15 16:47:48 merged: 2015-07-24 08:32:35

46. [10270](http://github.com/cms-sw/cmssw/pull/10270){:target="_blank"}  from **@ebouvier**: Temporarily fix of the offline DQM for the Top PAG (75X) `dqm`  created: 2015-07-18 17:22:01 merged: 2015-07-24 08:32:13

47. [10316](http://github.com/cms-sw/cmssw/pull/10316){:target="_blank"}  from **@slava77**: T0 processing fixes: csc untracked to tracked, add dqm_offline customization `operations`  created: 2015-07-23 12:30:24 merged: 2015-07-24 07:07:29

48. [10200](http://github.com/cms-sw/cmssw/pull/10200){:target="_blank"}  from **@wmtan**: kCanRebin is not supported in ROOT6 `alca`  `analysis`  `core`  `db`  `dqm`  `fastsim`  created: 2015-07-14 19:34:08 merged: 2015-07-23 10:57:07

49. [10303](http://github.com/cms-sw/cmssw/pull/10303){:target="_blank"}  from **@connorpa**: fix of pede job submission issue `alca`  created: 2015-07-22 12:19:06 merged: 2015-07-23 06:21:11

50. [10310](http://github.com/cms-sw/cmssw/pull/10310){:target="_blank"}  from **@alja**:   75x Fireworks: add check for PF PatJet constituents `visualization`  created: 2015-07-22 21:09:45 merged: 2015-07-23 06:01:14

51. [10239](http://github.com/cms-sw/cmssw/pull/10239){:target="_blank"}  from **@cms-l1t-offline**: backport stage1 unpacker to 75x `hlt`  `l1`  created: 2015-07-16 10:14:59 merged: 2015-07-23 05:33:27

52. [10235](http://github.com/cms-sw/cmssw/pull/10235){:target="_blank"}  from **@ndaci**: Added gen mu/electron from tau decay. `dqm`  created: 2015-07-16 09:29:05 merged: 2015-07-22 11:41:14

53. [10205](http://github.com/cms-sw/cmssw/pull/10205){:target="_blank"}  from **@ferencek**: Added full support for spectator variables in the TMVAEvaluator class: 75X `analysis`  `reconstruction`  created: 2015-07-15 01:29:30 merged: 2015-07-22 09:41:40

54. [10285](http://github.com/cms-sw/cmssw/pull/10285){:target="_blank"}  from **@mmusich**: Updating Global Tags with latest requests by L1, Pixel, Geometry `alca`  created: 2015-07-20 18:39:39 merged: 2015-07-22 09:31:26

55. [10237](http://github.com/cms-sw/cmssw/pull/10237){:target="_blank"}  from **@mtosi**: move PointSeededTrackingRegionsProducer to plugins (forward port of #10225) `reconstruction`  created: 2015-07-16 10:13:52 merged: 2015-07-21 18:32:12

56. [9675](http://github.com/cms-sw/cmssw/pull/9675){:target="_blank"}  from **@KiSooLee**: HLT name changed `dqm`  created: 2015-06-19 02:40:54 merged: 2015-07-21 18:22:04

57. [10057](http://github.com/cms-sw/cmssw/pull/10057){:target="_blank"}  from **@tlampen**: Print dmr rms error for75 x `alca`  created: 2015-07-06 20:10:11 merged: 2015-07-21 10:42:19

58. [10256](http://github.com/cms-sw/cmssw/pull/10256){:target="_blank"}  from **@fioriNTU**: fix to psu tracker map code `dqm`  `reconstruction`  created: 2015-07-17 12:14:43 merged: 2015-07-21 09:52:07

59. [10279](http://github.com/cms-sw/cmssw/pull/10279){:target="_blank"}  from **@cms-sw**: Revert "75X ExoLL and FSPremix dictionary" `pdmv`  created: 2015-07-20 12:28:47 merged: 2015-07-20 13:10:47

60. [9532](http://github.com/cms-sw/cmssw/pull/9532){:target="_blank"}  from **@hroskes**: More All-In-One tool improvements `alca`  created: 2015-06-09 22:18:56 merged: 2015-07-19 07:01:43

61. [10088](http://github.com/cms-sw/cmssw/pull/10088){:target="_blank"}  from **@arizzi**: MINIAOD: Whitelist IVF cands in packing + BugFix on SharedTracks helpers `analysis`  `reconstruction`  created: 2015-07-08 10:45:18 merged: 2015-07-19 07:01:33

62. [10154](http://github.com/cms-sw/cmssw/pull/10154){:target="_blank"}  from **@srimanob**: 75X ExoLL and FSPremix dictionary `pdmv`  created: 2015-07-11 23:24:53 merged: 2015-07-19 07:01:23

63. [10182](http://github.com/cms-sw/cmssw/pull/10182){:target="_blank"}  from **@fwyzard**: update hltGetConfiguration for ConfDB v2 (75x) `hlt`  created: 2015-07-14 06:50:56 merged: 2015-07-19 07:01:14

64. [10217](http://github.com/cms-sw/cmssw/pull/10217){:target="_blank"}  from **@kfjack**: enable EcalActivity skim in the skim matrix (7_5_X) `pdmv`  created: 2015-07-15 14:06:13 merged: 2015-07-19 06:51:23

65. [10223](http://github.com/cms-sw/cmssw/pull/10223){:target="_blank"}  from **@MilanoBicocca-pix**: Vtx smearing parameters for realistic 50ns collisions 13 TeV `simulation`  created: 2015-07-15 16:16:17 merged: 2015-07-19 06:51:14

66. [10251](http://github.com/cms-sw/cmssw/pull/10251){:target="_blank"}  from **@aescalante**: Update ExoticaDQM_cfi.py `dqm`  created: 2015-07-17 10:26:19 merged: 2015-07-19 06:49:53

67. [9160](http://github.com/cms-sw/cmssw/pull/9160){:target="_blank"}  from **@cms-tau-pog**: Added functionality to compute signed IP wrt tau direction  `reconstruction`  created: 2015-05-19 16:01:12 merged: 2015-07-15 16:43:09

68. [10004](http://github.com/cms-sw/cmssw/pull/10004){:target="_blank"}  from **@hroskes**: Backport of #10003 - Various All In One Tool bugfixes `alca`  created: 2015-07-01 21:56:34 merged: 2015-07-15 16:42:53

69. [10072](http://github.com/cms-sw/cmssw/pull/10072){:target="_blank"}  from **@emiglior**: Forward port 75X `analysis`  created: 2015-07-07 13:47:44 merged: 2015-07-15 16:42:37

70. [10159](http://github.com/cms-sw/cmssw/pull/10159){:target="_blank"}  from **@lgray**: Fix bug in DataFormats/FWLite/python/**init**.py (75X) `core`  created: 2015-07-12 18:17:29 merged: 2015-07-15 16:42:28

71. [10168](http://github.com/cms-sw/cmssw/pull/10168){:target="_blank"}  from **@cerminar**: RelVals for PCL (75X) `alca`  `pdmv`  created: 2015-07-13 14:31:51 merged: 2015-07-15 16:34:17

#### CMSDIST Changes between Tags REL/CMSSW_7_5_0/slc6_amd64_gcc491 and REL/CMSSW_7_5_1/slc6_amd64_gcc491:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_5_0/slc6_amd64_gcc491...REL/CMSSW_7_5_1/slc6_amd64_gcc491)



1. [1713](http://github.com/cms-sw/cmsdist/pull/1713){:target="_blank"}  from **@degano**: Advance L1Trigger/L1TCalorimeter to V01-00-05. created: 2015-07-31 12:48:44 merged: 2015-07-31 12:48:47

2. [1709](http://github.com/cms-sw/cmsdist/pull/1709){:target="_blank"}  from **@degano**: Advance RecoEgamma/ElectronIdentification data to V01-00-04. created: 2015-07-30 07:53:58 merged: 2015-07-30 07:54:02

3. [1703](http://github.com/cms-sw/cmsdist/pull/1703){:target="_blank"}  from **@deguio**: A new version of fastHadd executable: now able to merge in parallel.  created: 2015-07-29 09:57:18 merged: 2015-07-30 07:50:52

4. [1706](http://github.com/cms-sw/cmsdist/pull/1706){:target="_blank"}  from **@degano**: Revert "Remove patch for symlink and force them through makefile opti created: 2015-07-29 14:47:56 merged: 2015-07-29 14:48:00

5. [1696](http://github.com/cms-sw/cmsdist/pull/1696){:target="_blank"}  from **@degano**: Advance data for RecoJets/JetProducers. created: 2015-07-27 13:21:40 merged: 2015-07-27 13:21:44
