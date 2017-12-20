---
layout: post
rel_link:  "7_6_0_pre2"
title:  "CMSSW_7_6_0_pre2"
date:   2015-07-27 20:38:17
categories: cmssw
relmajor: 7
relminor: 6
relsubminor: 0
relpre: _pre2
---

# CMSSW_7_6_0_pre2
#### Changes since CMSSW_7_6_0_pre1:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_6_0_pre1...CMSSW_7_6_0_pre2)



1. [10315](http://github.com/cms-sw/cmssw/pull/10315){:target="_blank"}  from **@lgray**: Remove vestigial (and huge) GBRForest when running with PFEGAlgo `reconstruction`  created: 2015-07-23 12:29:55 merged: 2015-07-27 19:02:50

2. [10275](http://github.com/cms-sw/cmssw/pull/10275){:target="_blank"}  from **@bendavid**: Enhancements to GBRForest/Tree for converting TMVA classifiers `alca`  `db`  created: 2015-07-19 23:10:27 merged: 2015-07-27 14:26:19

3. [10259](http://github.com/cms-sw/cmssw/pull/10259){:target="_blank"}  from **@elimik31**: Corrected electron response for CASTOR `simulation`  created: 2015-07-17 13:51:05 merged: 2015-07-27 12:52:43

4. [10347](http://github.com/cms-sw/cmssw/pull/10347){:target="_blank"}  from **@arizzi**: Better fix to handle the error in the PVsorting (76X PR) `reconstruction`  created: 2015-07-24 14:40:43 merged: 2015-07-27 12:45:40

5. [10011](http://github.com/cms-sw/cmssw/pull/10011){:target="_blank"}  from **@rjwang**: correct gangedME11a flag, update LUT configuration with sectors `dqm`  created: 2015-07-02 07:50:14 merged: 2015-07-27 12:23:41

6. [10314](http://github.com/cms-sw/cmssw/pull/10314){:target="_blank"}  from **@abdoulline**: HF MC changes "a la" data:  ZS removed from config  and Digi size set to 4  `simulation`  created: 2015-07-23 11:20:46 merged: 2015-07-27 12:22:32

7. [10341](http://github.com/cms-sw/cmssw/pull/10341){:target="_blank"}  from **@satan1028**: HI Centrality DQM bug fix `dqm`  created: 2015-07-24 10:50:28 merged: 2015-07-27 12:22:10

8. [10352](http://github.com/cms-sw/cmssw/pull/10352){:target="_blank"}  from **@deguio**: port EDM2ME to consumes `dqm`  created: 2015-07-24 16:59:11 merged: 2015-07-27 12:21:55

9. [9945](http://github.com/cms-sw/cmssw/pull/9945){:target="_blank"}  from **@cms-tau-pog**: Payload generator 7 6 x `alca`  `db`  `reconstruction`  created: 2015-06-28 18:32:38 merged: 2015-07-27 12:17:24

10. [10359](http://github.com/cms-sw/cmssw/pull/10359){:target="_blank"}  from **@duanders**: Trigger name change in hotline DQM `dqm`  created: 2015-07-24 19:06:13 merged: 2015-07-27 12:11:49

11. [10290](http://github.com/cms-sw/cmssw/pull/10290){:target="_blank"}  from **@lgray**: Fix return type in vid::CutFlowResult accessor `analysis`  created: 2015-07-21 12:46:14 merged: 2015-07-26 07:04:43

12. [10333](http://github.com/cms-sw/cmssw/pull/10333){:target="_blank"}  from **@Dr15Jones**: Properly handle long lists of Parameters `core`  created: 2015-07-23 20:44:42 merged: 2015-07-25 20:31:48

13. [10351](http://github.com/cms-sw/cmssw/pull/10351){:target="_blank"}  from **@cms-tsg-storm**: HLT updates for the 25ns menu - 76X `hlt`  created: 2015-07-24 16:04:40 merged: 2015-07-25 20:31:33

14. [10289](http://github.com/cms-sw/cmssw/pull/10289){:target="_blank"}  from **@JetMETdqmval**: fixes for running in unscheduled mode, rebase to 76X `dqm`  `operations`  created: 2015-07-21 11:10:09 merged: 2015-07-25 20:29:58

15. [10143](http://github.com/cms-sw/cmssw/pull/10143){:target="_blank"}  from **@lgray**: Try converting RecoParticleFlow/PFTracking to GBRForest + GlobalCache `reconstruction`  created: 2015-07-11 07:44:47 merged: 2015-07-25 08:13:04

16. [10216](http://github.com/cms-sw/cmssw/pull/10216){:target="_blank"}  from **@ralfulrich**: Castor fs noncompensation 7 6 0 pre1 `simulation`  created: 2015-07-15 13:06:15 merged: 2015-07-24 16:02:49

17. [10166](http://github.com/cms-sw/cmssw/pull/10166){:target="_blank"}  from **@lveldere**: New FastSim Tracker RecHit Masking `fastsim`  `reconstruction`  created: 2015-07-13 13:50:33 merged: 2015-07-24 14:02:10

18. [9765](http://github.com/cms-sw/cmssw/pull/9765){:target="_blank"}  from **@inugent**: adding David Lange's comments built on rebase of ValidationDoubleCountin... `dqm`  `generators`  created: 2015-06-23 07:46:52 merged: 2015-07-24 12:22:32

19. [10232](http://github.com/cms-sw/cmssw/pull/10232){:target="_blank"}  from **@ngrenz**: ngrenz Strip Validation Package Optimization `dqm`  created: 2015-07-16 07:35:01 merged: 2015-07-24 12:22:04

20. [10271](http://github.com/cms-sw/cmssw/pull/10271){:target="_blank"}  from **@ebouvier**: Temporarily fix of the offline DQM for the Top PAG (76X) `dqm`  created: 2015-07-18 17:26:28 merged: 2015-07-24 12:14:06

21. [10343](http://github.com/cms-sw/cmssw/pull/10343){:target="_blank"}  from **@davidlange6**: adding chunk missed in forward port in HLTrigger/Configuration `hlt`  created: 2015-07-24 11:44:19 merged: 2015-07-24 12:08:24

22. [10318](http://github.com/cms-sw/cmssw/pull/10318){:target="_blank"}  from **@slava77**:  T0 processing fixes: csc untracked to tracked, add dqm_offline customization (same as #10316 ) `operations`  created: 2015-07-23 12:30:53 merged: 2015-07-24 07:07:02

23. [10219](http://github.com/cms-sw/cmssw/pull/10219){:target="_blank"}  from **@makortel**: Add additional MultiTrackValidator instances to validation `dqm`  `reconstruction`  created: 2015-07-15 14:41:16 merged: 2015-07-24 07:02:15

24. [10305](http://github.com/cms-sw/cmssw/pull/10305){:target="_blank"}  from **@makortel**: Replace bunch of debug-ifdefs in MultiHitGeneratorFromChi2 with a macro `reconstruction`  created: 2015-07-22 12:49:26 merged: 2015-07-24 07:01:44

25. [10322](http://github.com/cms-sw/cmssw/pull/10322){:target="_blank"}  from **@deguio**: remove Edm2ME converter from the harvesting sequence `operations`  created: 2015-07-23 13:51:16 merged: 2015-07-24 07:01:12

26. [10209](http://github.com/cms-sw/cmssw/pull/10209){:target="_blank"}  from **@cms-tsg-storm**: Hlt updates on top of745plus epsilon 76X `alca`  `hlt`  `l1`  `simulation`  created: 2015-07-15 07:01:55 merged: 2015-07-24 06:56:48

27. [10220](http://github.com/cms-sw/cmssw/pull/10220){:target="_blank"}  from **@cms-l1t-offline**: L1t rcttodigi `l1`  created: 2015-07-15 15:41:07 merged: 2015-07-24 06:55:42

28. [10299](http://github.com/cms-sw/cmssw/pull/10299){:target="_blank"}  from **@ianna**: Clean up Unnecessary Direct Dependencies `alca`  `geometry`  created: 2015-07-21 16:35:26 merged: 2015-07-24 06:53:19

29. [10302](http://github.com/cms-sw/cmssw/pull/10302){:target="_blank"}  from **@connorpa**: fix of pede job submission issue `alca`  created: 2015-07-22 12:17:59 merged: 2015-07-24 06:52:49

30. [10226](http://github.com/cms-sw/cmssw/pull/10226){:target="_blank"}  from **@franzoni**: SKIMS in Conf data processing 76 `operations`  created: 2015-07-15 16:39:50 merged: 2015-07-23 16:43:09

31. [10267](http://github.com/cms-sw/cmssw/pull/10267){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcs23 Modify to add the adequate ESProducers in the configuration scenarios `geometry`  created: 2015-07-17 17:55:24 merged: 2015-07-23 16:42:29

32. [10268](http://github.com/cms-sw/cmssw/pull/10268){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hgx29 HGCal geometry (all xml files and numbering scheme) `geometry`  created: 2015-07-17 22:16:40 merged: 2015-07-23 05:31:43

33. [10311](http://github.com/cms-sw/cmssw/pull/10311){:target="_blank"}  from **@jhgoh**: GenParticles2HepMCConverter Consumes migration `generators`  created: 2015-07-22 22:06:19 merged: 2015-07-23 05:31:24

34. [10105](http://github.com/cms-sw/cmssw/pull/10105){:target="_blank"}  from **@emanueledimarco**: ECAL MultiFit: symmetric Pulse Shape Covariance Matrix DB object `alca`  `db`  created: 2015-07-08 21:52:23 merged: 2015-07-22 11:31:25

35. [10066](http://github.com/cms-sw/cmssw/pull/10066){:target="_blank"}  from **@makortel**: Fixes to some issues reported by static analyzer in tracking related code `alca`  `dqm`  `reconstruction`  `simulation`  created: 2015-07-07 08:47:03 merged: 2015-07-22 11:28:15

36. [10202](http://github.com/cms-sw/cmssw/pull/10202){:target="_blank"}  from **@Dr15Jones**: Apply event filter before data prefetching for OutputModules `core`  created: 2015-07-14 20:56:54 merged: 2015-07-22 09:31:44

37. [10056](http://github.com/cms-sw/cmssw/pull/10056){:target="_blank"}  from **@bbockelm**: Integrate CMSSW with HTCondor's update service. `core`  created: 2015-07-06 20:05:44 merged: 2015-07-21 18:17:32

38. [10204](http://github.com/cms-sw/cmssw/pull/10204){:target="_blank"}  from **@ferencek**: Added full support for spectator variables in the TMVAEvaluator class `analysis`  `reconstruction`  created: 2015-07-15 01:28:31 merged: 2015-07-21 18:16:22

39. [10201](http://github.com/cms-sw/cmssw/pull/10201){:target="_blank"}  from **@wmtan**: kCanRebin is not supported in ROOT6 (76X) `alca`  `analysis`  `core`  `db`  `dqm`  `fastsim`  created: 2015-07-14 19:43:54 merged: 2015-07-21 18:14:52

40. [10288](http://github.com/cms-sw/cmssw/pull/10288){:target="_blank"}  from **@diguida**: Updating Global Tags with latest requests by L1, Pixel, Geometry and BTV (as in #10285) `alca`  created: 2015-07-20 19:50:58 merged: 2015-07-21 09:51:14

41. [9770](http://github.com/cms-sw/cmssw/pull/9770){:target="_blank"}  from **@wddgit**: Replace call to getProcessParameterSet `daq`  `reconstruction`  created: 2015-06-23 07:48:40 merged: 2015-07-21 09:33:14

42. [10257](http://github.com/cms-sw/cmssw/pull/10257){:target="_blank"}  from **@fioriNTU**: fix needed for psu TkMap `dqm`  `reconstruction`  created: 2015-07-17 12:41:41 merged: 2015-07-21 09:32:08

43. [10281](http://github.com/cms-sw/cmssw/pull/10281){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-gem08 Add the GE21 geometry with pointing strips `geometry`  created: 2015-07-20 15:58:29 merged: 2015-07-21 09:31:25

44. [10194](http://github.com/cms-sw/cmssw/pull/10194){:target="_blank"}  from **@doanhien**: add variable of sigma_ieta_ieta at electron seed level `reconstruction`  created: 2015-07-14 12:59:37 merged: 2015-07-21 05:51:34

45. [10231](http://github.com/cms-sw/cmssw/pull/10231){:target="_blank"}  from **@makortel**: Transform couts to LogDebug/LogTrace in MultiHitGeneratorFromChi2 `reconstruction`  created: 2015-07-16 06:55:25 merged: 2015-07-21 05:51:24

46. [10238](http://github.com/cms-sw/cmssw/pull/10238){:target="_blank"}  from **@mtosi**: move PointSeededTrackingRegionsProducer to plugins (forward port of #10237) `reconstruction`  created: 2015-07-16 10:14:43 merged: 2015-07-21 05:51:14

47. [10024](http://github.com/cms-sw/cmssw/pull/10024){:target="_blank"}  from **@diguida**: Add HcalCalIsoTrk AlCaReco in the correct RelVal steps `pdmv`  created: 2015-07-02 17:04:58 merged: 2015-07-19 06:49:14

48. [10252](http://github.com/cms-sw/cmssw/pull/10252){:target="_blank"}  from **@aescalante**: Update ExoticaDQM_cfi.py `dqm`  created: 2015-07-17 10:26:30 merged: 2015-07-18 09:41:23

49. [10003](http://github.com/cms-sw/cmssw/pull/10003){:target="_blank"}  from **@hroskes**: Various All In One Tool bugfixes `alca`  created: 2015-07-01 21:56:15 merged: 2015-07-18 09:02:21

50. [10253](http://github.com/cms-sw/cmssw/pull/10253){:target="_blank"}  from **@ndaci**: Added gen mu/electron from tau decay. `dqm`  created: 2015-07-17 10:52:03 merged: 2015-07-18 09:01:51

51. [10222](http://github.com/cms-sw/cmssw/pull/10222){:target="_blank"}  from **@MilanoBicocca-pix**: Vtx smearing parameters for realistic 50ns collisions 13 TeV `simulation`  created: 2015-07-15 16:15:16 merged: 2015-07-18 08:49:20

52. [10246](http://github.com/cms-sw/cmssw/pull/10246){:target="_blank"}  from **@wmtan**: Remove files that use non-existent config fragment MixingNoPileUp_cff `alca`  `dqm`  `fastsim`  `generators`  `geometry`  `l1`  `reconstruction`  `simulation`  created: 2015-07-16 20:57:55 merged: 2015-07-18 08:48:40

53. [10229](http://github.com/cms-sw/cmssw/pull/10229){:target="_blank"}  from **@cms-sw**: Revert "Updated HLTTau validation to include legs X in tau+X triggers" `dqm`  created: 2015-07-16 05:57:46 merged: 2015-07-16 06:02:10

54. [10212](http://github.com/cms-sw/cmssw/pull/10212){:target="_blank"}  from **@kfjack**: enable EcalActivity skim in the skim matrix `pdmv`  created: 2015-07-15 11:01:50 merged: 2015-07-16 06:01:42

55. [10214](http://github.com/cms-sw/cmssw/pull/10214){:target="_blank"}  from **@ianna**: Hcal DD Rec and Sim Constants Cleanup `geometry`  created: 2015-07-15 11:05:31 merged: 2015-07-16 06:01:32

56. [9812](http://github.com/cms-sw/cmssw/pull/9812){:target="_blank"}  from **@hroskes**: More All-In-One tool improvements `alca`  created: 2015-06-23 09:02:49 merged: 2015-07-15 16:32:47

57. [10000](http://github.com/cms-sw/cmssw/pull/10000){:target="_blank"}  from **@wmtan**: Use C++ regex, not boost regex, in the framework where feasible. `core`  created: 2015-07-01 21:00:38 merged: 2015-07-15 14:32:33

58. [10055](http://github.com/cms-sw/cmssw/pull/10055){:target="_blank"}  from **@tlampen**: Print dmr rms error for76 x `alca`  created: 2015-07-06 20:04:47 merged: 2015-07-15 14:32:18

59. [10185](http://github.com/cms-sw/cmssw/pull/10185){:target="_blank"}  from **@srimanob**: 76X relvals update `pdmv`  created: 2015-07-14 08:49:08 merged: 2015-07-15 14:32:01

60. [10116](http://github.com/cms-sw/cmssw/pull/10116){:target="_blank"}  from **@wmtan**: Remove some configuration files using nonexistent standard sequences `alca`  `dqm`  `fastsim`  `generators`  `geometry`  `reconstruction`  `simulation`  created: 2015-07-09 21:28:02 merged: 2015-07-15 14:25:54

61. [10181](http://github.com/cms-sw/cmssw/pull/10181){:target="_blank"}  from **@fwyzard**: update hltGetConfiguration for ConfDB v2 (76x) `hlt`  created: 2015-07-14 06:48:33 merged: 2015-07-15 14:25:27

62. [10123](http://github.com/cms-sw/cmssw/pull/10123){:target="_blank"}  from **@ianna**: Hcal Parameters Schema Update v2 `alca`  `db`  `geometry`  created: 2015-07-10 09:46:54 merged: 2015-07-14 07:11:37

#### CMSDIST Changes between Tags REL/CMSSW_7_6_0_pre1/slc6_amd64_gcc491 and REL/CMSSW_7_6_0_pre2/slc6_amd64_gcc491:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_6_0_pre1/slc6_amd64_gcc491...REL/CMSSW_7_6_0_pre2/slc6_amd64_gcc491)



1. [1695](http://github.com/cms-sw/cmsdist/pull/1695){:target="_blank"}  from **@degano**: Take root files from cms-sw/cmssw#9803 from cms-data repo. created: 2015-07-27 13:16:05 merged: 2015-07-27 13:16:25

2. [1690](http://github.com/cms-sw/cmsdist/pull/1690){:target="_blank"}  from **@mkirsano**: upgrade lhapdfsets to 6.1.5b with CT14 created: 2015-07-23 13:15:09 merged: 2015-07-27 09:15:08

3. [1694](http://github.com/cms-sw/cmsdist/pull/1694){:target="_blank"}  from **@degano**: Additional fixes for CUDA. created: 2015-07-25 07:37:44 merged: 2015-07-25 07:37:50

4. [1693](http://github.com/cms-sw/cmsdist/pull/1693){:target="_blank"}  from **@degano**: Fix CUDA to allow installation on slc7 arch. created: 2015-07-24 12:57:02 merged: 2015-07-24 12:57:05

5. [1692](http://github.com/cms-sw/cmsdist/pull/1692){:target="_blank"}  from **@degano**: Advance data for RecoJets/JetProducers. created: 2015-07-24 08:01:52 merged: 2015-07-24 08:03:33

6. [1691](http://github.com/cms-sw/cmsdist/pull/1691){:target="_blank"}  from **@degano**: Update RecoEgamma/ElectronIdentification data to V01-00-04 created: 2015-07-23 16:03:32 merged: 2015-07-23 16:04:27

7. [1686](http://github.com/cms-sw/cmsdist/pull/1686){:target="_blank"}  from **@mkirsano**: Upgrade to pythia8 210 created: 2015-07-22 13:31:32 merged: 2015-07-23 09:24:15

8. [1689](http://github.com/cms-sw/cmsdist/pull/1689){:target="_blank"}  from **@degano**: Download and install CUDA with relative toolfile. created: 2015-07-23 08:00:48 merged: 2015-07-23 08:00:52

9. [1688](http://github.com/cms-sw/cmsdist/pull/1688){:target="_blank"}  from **@degano**: Include fix for runtime memory leak. created: 2015-07-23 07:52:29 merged: 2015-07-23 07:53:11

10. [1685](http://github.com/cms-sw/cmsdist/pull/1685){:target="_blank"}  from **@degano**: Revert "Remove patch for symlink and force them through makefile opti created: 2015-07-22 10:19:09 merged: 2015-07-22 10:19:15

11. [1684](http://github.com/cms-sw/cmsdist/pull/1684){:target="_blank"}  from **@degano**: Point again to root patches + missing commit. created: 2015-07-20 20:26:46 merged: 2015-07-20 20:27:06

12. [1683](http://github.com/cms-sw/cmsdist/pull/1683){:target="_blank"}  from **@cms-sw**: Revert "Include recent fixes from 6.02.patches root branch." created: 2015-07-17 07:43:14 merged: 2015-07-17 07:43:51

13. [1682](http://github.com/cms-sw/cmsdist/pull/1682){:target="_blank"}  from **@degano**: Include recent fixes from 6.02.patches root branch. created: 2015-07-15 18:37:02 merged: 2015-07-15 18:37:10

14. [1680](http://github.com/cms-sw/cmsdist/pull/1680){:target="_blank"}  from **@degano**: Create separate spec for mcfm. created: 2015-07-15 13:46:01 merged: 2015-07-15 13:46:15

15. [1677](http://github.com/cms-sw/cmsdist/pull/1677){:target="_blank"}  from **@degano**: Advance clhep to 2.2.0.4 from cms-externals. created: 2015-07-14 05:34:31 merged: 2015-07-15 12:55:05

16. [1678](http://github.com/cms-sw/cmsdist/pull/1678){:target="_blank"}  from **@degano**: Update frontier client to 2.8.12. created: 2015-07-14 08:05:08 merged: 2015-07-15 12:54:51
