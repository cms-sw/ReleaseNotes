---
layout: post
rel_link:  "7_1_0_pre9"
title:  "CMSSW_7_1_0_pre9"
date:   2014-06-07 20:56:01
categories: cmssw
relmajor: 7
relminor: 1
relsubminor: 0
relpre: _pre9
---

# CMSSW_7_1_0_pre9
#### Changes since CMSSW_7_1_0_pre8:

1. [4144](http://github.com/cms-sw/cmssw/pull/4144){:target="_blank"}  from **@davidlange6**: Fix uninited mem castor monitor module created: 2014-06-06 12:53:38 merged: 2014-06-06 12:53:51

2. [4143](http://github.com/cms-sw/cmssw/pull/4143){:target="_blank"}  from **@davidlange6**: Fix dqm memory leaks p2 created: 2014-06-06 11:42:51 merged: 2014-06-06 11:42:58

3. [4123](http://github.com/cms-sw/cmssw/pull/4123){:target="_blank"}  from **@rcastello**: GTs for pre9: migrating accounts to prod DB and updating muon layer alignment `alca`  created: 2014-06-05 14:44:46 merged: 2014-06-06 11:39:37

4. [4142](http://github.com/cms-sw/cmssw/pull/4142){:target="_blank"}  from **@davidlange6**: when new-ing you should delete created: 2014-06-06 11:16:02 merged: 2014-06-06 11:16:16

5. [4111](http://github.com/cms-sw/cmssw/pull/4111){:target="_blank"}  from **@deguio**: Update the DQMService to see the new fwk signals. `dqm`  created: 2014-06-04 17:37:44 merged: 2014-06-06 07:11:28

6. [4124](http://github.com/cms-sw/cmssw/pull/4124){:target="_blank"}  from **@deguio**: implement the label check for the PoolSource also to avoid crashes when ... `core`  `dqm`  created: 2014-06-05 16:14:44 merged: 2014-06-05 19:53:07

7. [3862](http://github.com/cms-sw/cmssw/pull/3862){:target="_blank"}  from **@threus**: Tkdetmap threadfix `alca`  `dqm`  created: 2014-05-14 13:50:14 merged: 2014-06-05 19:50:08

8. [4098](http://github.com/cms-sw/cmssw/pull/4098){:target="_blank"}  from **@olivito**: HLT single tracker muon trig code `hlt`  created: 2014-06-03 10:48:13 merged: 2014-06-04 15:35:05

9. [4051](http://github.com/cms-sw/cmssw/pull/4051){:target="_blank"}  from **@acimmino**: DQM/RPCMonitorClient fixes. `dqm`  created: 2014-05-29 16:13:15 merged: 2014-06-04 15:33:47

10. [3984](http://github.com/cms-sw/cmssw/pull/3984){:target="_blank"}  from **@JetMETdqmval**: remove direct calls of DQMStore, move SusyPostProcessor to DQMHarvester `dqm`  created: 2014-05-23 11:18:53 merged: 2014-06-04 15:33:06

11. [4107](http://github.com/cms-sw/cmssw/pull/4107){:target="_blank"}  from **@ktf**: Avoid forward port #4008 created: 2014-06-04 12:03:02 merged: 2014-06-04 12:04:18

12. [4105](http://github.com/cms-sw/cmssw/pull/4105){:target="_blank"}  from **@ktf**: Cleanup #4004. `analysis`  created: 2014-06-03 19:48:40 merged: 2014-06-03 19:49:56

13. [4087](http://github.com/cms-sw/cmssw/pull/4087){:target="_blank"}  from **@Dr15Jones**: Make GsfElectronBaseProducer a stream module. `reconstruction`  created: 2014-06-02 15:04:03 merged: 2014-06-03 19:04:21

14. [4088](http://github.com/cms-sw/cmssw/pull/4088){:target="_blank"}  from **@Dr15Jones**: Convert ElectronIDExternalProducer to stream Producer `reconstruction`  created: 2014-06-02 15:04:44 merged: 2014-06-03 19:04:09

15. [4083](http://github.com/cms-sw/cmssw/pull/4083){:target="_blank"}  from **@Dr15Jones**: Convert FwdPtrProducer to stream Producer. `analysis`  `reconstruction`  created: 2014-06-02 13:57:49 merged: 2014-06-03 19:03:27

16. [4078](http://github.com/cms-sw/cmssw/pull/4078){:target="_blank"}  from **@civanch**: use full model for fluorescence in XS and HP PHysicsLists `simulation`  created: 2014-06-02 13:10:06 merged: 2014-06-03 16:26:36

17. [4089](http://github.com/cms-sw/cmssw/pull/4089){:target="_blank"}  from **@Dr15Jones**: Convert PhotonConversionTrajectorySeedProducerFromSingleLeg to stream Producer `reconstruction`  created: 2014-06-02 15:05:26 merged: 2014-06-03 16:25:50

18. [4100](http://github.com/cms-sw/cmssw/pull/4100){:target="_blank"}  from **@apfeiffer1**: update serialisation generator script 71X version `db`  created: 2014-06-03 13:25:55 merged: 2014-06-03 16:25:04

19. [4052](http://github.com/cms-sw/cmssw/pull/4052){:target="_blank"}  from **@civanch**: Exotica and neutron background Physics Lists update `simulation`  created: 2014-05-30 09:46:45 merged: 2014-06-03 16:24:12

20. [4049](http://github.com/cms-sw/cmssw/pull/4049){:target="_blank"}  from **@Martin-Grunewald**: SUSYBSMfix in TriggerValidator `dqm`  created: 2014-05-29 15:43:11 merged: 2014-06-03 16:23:30

21. [4039](http://github.com/cms-sw/cmssw/pull/4039){:target="_blank"}  from **@perrotta**: FastSim customization, and ak4 GEN-SIM compatible input file in HLT tests `fastsim`  `hlt`  created: 2014-05-28 14:39:10 merged: 2014-06-03 16:23:19

22. [4004](http://github.com/cms-sw/cmssw/pull/4004){:target="_blank"}  from **@ktf**: Backport of clang fixes from CMSSW_7_1_CLANG_X branch `alca`  `analysis`  `db`  `dqm`  `generators`  `geometry`  `l1`  `reconstruction`  `simulation`  created: 2014-05-24 13:56:03 merged: 2014-06-03 16:21:59

23. [4086](http://github.com/cms-sw/cmssw/pull/4086){:target="_blank"}  from **@deguio**: support multithreading also for int, float and string `dqm`  created: 2014-06-02 14:24:28 merged: 2014-06-03 16:21:15

24. [4010](http://github.com/cms-sw/cmssw/pull/4010){:target="_blank"}  from **@ktf**: Allow a SingleObjectSelector to be a stream::EDFilter `analysis`  `dqm`  `reconstruction`  created: 2014-05-26 11:58:40 merged: 2014-06-03 16:20:27

25. [4021](http://github.com/cms-sw/cmssw/pull/4021){:target="_blank"}  from **@jstupak**: bug fixes for Jet toolbox `reconstruction`  created: 2014-05-27 18:23:09 merged: 2014-06-03 16:20:01

26. [4017](http://github.com/cms-sw/cmssw/pull/4017){:target="_blank"}  from **@mtosi**: fix maxVtx definition in fillDescription method (needed for confDB) `reconstruction`  created: 2014-05-27 12:35:52 merged: 2014-06-03 16:19:18

27. [4009](http://github.com/cms-sw/cmssw/pull/4009){:target="_blank"}  from **@civanch**: Minor updates for Geant4 10 `simulation`  created: 2014-05-26 11:34:08 merged: 2014-06-03 16:18:19

28. [3994](http://github.com/cms-sw/cmssw/pull/3994){:target="_blank"}  from **@cms-btv-pog**: Fix for  jet flavour clustering `analysis`  created: 2014-05-23 17:25:08 merged: 2014-06-03 16:17:39

29. [3919](http://github.com/cms-sw/cmssw/pull/3919){:target="_blank"}  from **@puigh**: Updates to GeneralHLTOffline `dqm`  created: 2014-05-19 02:07:46 merged: 2014-06-03 16:17:23

30. [3816](http://github.com/cms-sw/cmssw/pull/3816){:target="_blank"}  from **@dmitrijus**: DQM Online Source `dqm`  created: 2014-05-12 09:36:57 merged: 2014-06-03 16:17:09

31. [3875](http://github.com/cms-sw/cmssw/pull/3875){:target="_blank"}  from **@gpetruc**: Mini aod part3 (7.1.X) `analysis`  `core`  `operations`  `reconstruction`  created: 2014-05-14 20:26:52 merged: 2014-06-03 15:46:19

32. [4072](http://github.com/cms-sw/cmssw/pull/4072){:target="_blank"}  from **@nclopezo**: Removed duplicate line in DataFormats/TauReco/BuildFile.xml `reconstruction`  created: 2014-06-02 08:24:35 merged: 2014-06-02 08:39:02

33. [4028](http://github.com/cms-sw/cmssw/pull/4028){:target="_blank"}  from **@ktf**: Avoid certificate errors in tests. `core`  created: 2014-05-28 09:59:54 merged: 2014-05-28 10:01:23

34. [3987](http://github.com/cms-sw/cmssw/pull/3987){:target="_blank"}  from **@apfeiffer1**: DB -- Add QGLike objects to importer `db`  created: 2014-05-23 13:13:35 merged: 2014-05-26 20:36:05

35. [3968](http://github.com/cms-sw/cmssw/pull/3968){:target="_blank"}  from **@Dr15Jones**: Move edm::stream::imll::makeGlobal to own file. `core`  created: 2014-05-22 14:58:01 merged: 2014-05-26 17:19:27

36. [3979](http://github.com/cms-sw/cmssw/pull/3979){:target="_blank"}  from **@mbluj**: new instances of HLTDoublet to handle generic RecoEcalCandidate-(PF)Tau pairs `hlt`  created: 2014-05-23 09:24:24 merged: 2014-05-23 13:24:39

37. [3978](http://github.com/cms-sw/cmssw/pull/3978){:target="_blank"}  from **@davidlt**: CondFormats/Serialization -- Cond boost aarch64 71x `db`  created: 2014-05-23 07:45:24 merged: 2014-05-23 11:51:54

38. [3977](http://github.com/cms-sw/cmssw/pull/3977){:target="_blank"}  from **@davidlt**: ARM64 -- rdtscp.h disable on aarch64 `reconstruction`  created: 2014-05-23 07:39:24 merged: 2014-05-23 09:22:31

39. [3963](http://github.com/cms-sw/cmssw/pull/3963){:target="_blank"}  from **@pgunnell**: Generators -- New p6 p8 tunes `generators`  created: 2014-05-22 13:52:09 merged: 2014-05-23 09:14:23

40. [3939](http://github.com/cms-sw/cmssw/pull/3939){:target="_blank"}  from **@Dr15Jones**: Multithreading -- Make GsfElectronCoreBaseProducer a stream module `reconstruction`  created: 2014-05-20 13:18:58 merged: 2014-05-21 22:24:58

41. [3941](http://github.com/cms-sw/cmssw/pull/3941){:target="_blank"}  from **@Dr15Jones**: DQM -- Make DQMRootOutputModule a one module `dqm`  created: 2014-05-20 13:56:35 merged: 2014-05-20 19:20:15

42. [3936](http://github.com/cms-sw/cmssw/pull/3936){:target="_blank"}  from **@vadler**: AT -- Remove TCMET `analysis`  created: 2014-05-19 19:46:35 merged: 2014-05-20 18:49:17

43. [3937](http://github.com/cms-sw/cmssw/pull/3937){:target="_blank"}  from **@Martin-Grunewald**: HLT -- Move HLT to ConfDB template 710pre8 `hlt`  created: 2014-05-20 06:57:12 merged: 2014-05-20 10:48:25

44. [3929](http://github.com/cms-sw/cmssw/pull/3929){:target="_blank"}  from **@vadler**: AT -- Fix `metUncertaintyTools` for scheduled processing `analysis`  created: 2014-05-19 16:38:39 merged: 2014-05-20 09:00:39

45. [3927](http://github.com/cms-sw/cmssw/pull/3927){:target="_blank"}  from **@lveldere**: FastSim -- Fix unrunable schedule `fastsim`  created: 2014-05-19 15:33:22 merged: 2014-05-20 08:59:44

46. [3926](http://github.com/cms-sw/cmssw/pull/3926){:target="_blank"}  from **@gartung**: Clang -- update scripts used in ib-statics-checks Jenkins job. `core`  created: 2014-05-19 15:14:07 merged: 2014-05-20 08:53:13

47. [3909](http://github.com/cms-sw/cmssw/pull/3909){:target="_blank"}  from **@igv4321**: Reco -- Various fixes related to HCAL OOT pileup corrections code `db`  `reconstruction`  created: 2014-05-16 19:52:37 merged: 2014-05-20 07:41:30

48. [3935](http://github.com/cms-sw/cmssw/pull/3935){:target="_blank"}  from **@Dr15Jones**: Framework -- Improved format for edmSTreamStallGrapher.py output `core`  created: 2014-05-19 19:15:43 merged: 2014-05-19 19:19:56

49. [3896](http://github.com/cms-sw/cmssw/pull/3896){:target="_blank"}  from **@Dr15Jones**: Multithreading -- Revert MuonDetLayerGeometry using modules to stream modules `reconstruction`  created: 2014-05-15 22:10:10 merged: 2014-05-19 18:32:46

50. [3924](http://github.com/cms-sw/cmssw/pull/3924){:target="_blank"}  from **@Dr15Jones**: Added edmStreamStallGrapher.py `core`  created: 2014-05-19 14:53:10 merged: 2014-05-19 16:36:26

51. [3918](http://github.com/cms-sw/cmssw/pull/3918){:target="_blank"}  from **@Dr15Jones**: RecoParticleFlow/PFTracking -- Revert PFElecTkProducer to legacy module because of TMVA `reconstruction`  created: 2014-05-19 00:53:14 merged: 2014-05-19 14:08:27
