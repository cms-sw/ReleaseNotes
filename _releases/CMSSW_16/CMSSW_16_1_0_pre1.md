---
layout: post
rel_link:  "16_1_0_pre1"
title:  "CMSSW_16_1_0_pre1"
date:   2026-01-14 10:50:24
categories: cmssw
relmajor: 16
relminor: 1
relsubminor: 0
relpre: _pre1
---

# CMSSW_16_1_0_pre1
#### Changes since CMSSW_16_0_0_pre4:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_16_0_0_pre4...CMSSW_16_1_0_pre1)



1. [49801](http://github.com/cms-sw/cmssw/pull/49801){:target="_blank"}  from **@fabiocos**: Simulation: prevent exception if trackId larger than 200M `simulation` created: 2026-01-13 17:02:14 merged: 2026-01-13 21:31:40

2. [49789](http://github.com/cms-sw/cmssw/pull/49789){:target="_blank"}  from **@mmusich**: fix unit test `createTestDBObjects` after integration of #49725 `db` `trk` created: 2026-01-13 08:08:45 merged: 2026-01-13 16:36:46

3. [49778](http://github.com/cms-sw/cmssw/pull/49778){:target="_blank"}  from **@mmusich**: update unit test Miscellanea post integration of #49725 `alca` `trk` created: 2026-01-12 17:35:53 merged: 2026-01-12 21:33:38

4. [49777](http://github.com/cms-sw/cmssw/pull/49777){:target="_blank"}  from **@mmusich**: bug-fix: use `hltOnlineBeamSpot` in `hltWithPixelTracks` and `hltPixelLessTracks` `dqm` `tracking` created: 2026-01-12 17:29:13 merged: 2026-01-13 16:37:26

5. [49769](http://github.com/cms-sw/cmssw/pull/49769){:target="_blank"}  from **@mmusich**: Introduce DQM for `Run3ScoutingHBHERecHit` time `dqm` `hlt` created: 2026-01-12 11:03:46 merged: 2026-01-13 16:39:26

6. [49765](http://github.com/cms-sw/cmssw/pull/49765){:target="_blank"}  from **@Dr15Jones**: Added fillDescriptions to more classes in FWCore `core` created: 2026-01-11 17:01:53 merged: 2026-01-13 21:30:01

7. [49764](http://github.com/cms-sw/cmssw/pull/49764){:target="_blank"}  from **@bsunanda**: Run3-alca264 Modify some of the scripts to update calibration constants of HCAL `alca` created: 2026-01-11 14:04:23 merged: 2026-01-12 08:13:14

8. [49763](http://github.com/cms-sw/cmssw/pull/49763){:target="_blank"}  from **@bsunanda**: Phase2-hgx364X Add the tools with some more diagnostic help to debug the issue of wrong DetID->Position->DetID assignment `geometry` created: 2026-01-11 13:53:24 merged: 2026-01-12 21:32:57

9. [49757](http://github.com/cms-sw/cmssw/pull/49757){:target="_blank"}  from **@Dr15Jones**: Move AtomicPtrCache dictionary to proper packages `reconstruction` `xpog` `tracking` created: 2026-01-09 19:37:06 merged: 2026-01-12 21:33:58

10. [49753](http://github.com/cms-sw/cmssw/pull/49753){:target="_blank"}  from **@missirol**: L1-uGT emulator: fix to `AXOL1TL`'s "Pt" inputs `l1` created: 2026-01-09 17:49:55 merged: 2026-01-13 06:22:49

11. [49751](http://github.com/cms-sw/cmssw/pull/49751){:target="_blank"}  from **@SegmentLinking**: Remove unused flag from standalone LST `reconstruction` `tracking` created: 2026-01-09 17:04:52 merged: 2026-01-13 16:39:11

12. [49750](http://github.com/cms-sw/cmssw/pull/49750){:target="_blank"}  from **@Dr15Jones**: Add fillDescriptions to ToyModules.cc classes `core` created: 2026-01-09 16:20:19 merged: 2026-01-09 19:12:28

13. [49748](http://github.com/cms-sw/cmssw/pull/49748){:target="_blank"}  from **@fwyzard**: Use the alpaka Acc concept `reconstruction` `heterogeneous` `tracking` `trk` `ml` created: 2026-01-08 16:22:44 merged: 2026-01-09 16:39:41

14. [49747](http://github.com/cms-sw/cmssw/pull/49747){:target="_blank"}  from **@mmusich**: set `relval2025` autoHLT key to `Fake2` `hlt` `pdmv` created: 2026-01-08 14:23:29 merged: 2026-01-09 16:41:07

15. [49746](http://github.com/cms-sw/cmssw/pull/49746){:target="_blank"}  from **@mmusich**: update dqm online scouting unit test `dqm` created: 2026-01-08 14:00:52 merged: 2026-01-12 08:08:29

16. [49744](http://github.com/cms-sw/cmssw/pull/49744){:target="_blank"}  from **@Tizianop6**: Adding track path length resolution plots to MtdTracksValidation  `dqm` created: 2026-01-08 09:38:45 merged: 2026-01-12 18:46:28

17. [49737](http://github.com/cms-sw/cmssw/pull/49737){:target="_blank"}  from **@ljuckett**: Phase 2 Tracker: Summary histograms for release validation `dqm` `trk` created: 2026-01-07 15:24:41 merged: 2026-01-09 09:46:05

18. [49736](http://github.com/cms-sw/cmssw/pull/49736){:target="_blank"}  from **@martinamalberti**: ETL digitization: update comments on TDC window parameters `simulation` created: 2026-01-07 12:21:04 merged: 2026-01-09 09:45:30

19. [49735](http://github.com/cms-sw/cmssw/pull/49735){:target="_blank"}  from **@silviodonato**: Fix a variable name in HLTScoutingPFProducer: from dxy(z)Error to dxy(z)Sig `hlt` created: 2026-01-07 09:14:28 merged: 2026-01-07 21:35:27

20. [49733](http://github.com/cms-sw/cmssw/pull/49733){:target="_blank"}  from **@Dr15Jones**: Use more requires in EventSetup code `core` created: 2026-01-06 21:28:42 merged: 2026-01-12 18:49:47

21. [49730](http://github.com/cms-sw/cmssw/pull/49730){:target="_blank"}  from **@chrishanw**: Implement comments in #49436 and add HLT customisation function for `16_1_X` `hlt` `reconstruction` `tracking` created: 2026-01-06 15:22:40 merged: 2026-01-07 21:32:51

22. [49727](http://github.com/cms-sw/cmssw/pull/49727){:target="_blank"}  from **@akritkbehera**: suppress loop unroll warning in LSTCore `reconstruction` `tracking` created: 2026-01-06 13:08:04 merged: 2026-01-13 16:38:26

23. [49725](http://github.com/cms-sw/cmssw/pull/49725){:target="_blank"}  from **@kpedro88**: Phase 2 geometry deprecation `geometry` `operations` `pdmv` created: 2026-01-06 11:52:12 merged: 2026-01-09 16:42:28

24. [49722](http://github.com/cms-sw/cmssw/pull/49722){:target="_blank"}  from **@mmusich**: Miscellaneous fixes to SiStripApproximateCluster_v1 `reconstruction` `trk` created: 2026-01-06 09:12:47 merged: 2026-01-07 21:34:59

25. [49720](http://github.com/cms-sw/cmssw/pull/49720){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `16_0_X` (1/N) [`16_1_X`] `hlt` created: 2026-01-06 08:20:23 merged: 2026-01-06 11:54:59

26. [49719](http://github.com/cms-sw/cmssw/pull/49719){:target="_blank"}  from **@bsunanda**: Phase2-hgx364W Extend the tests for finding errors in iD->position and viceve  rsa for the V19 geometry `geometry` created: 2026-01-06 04:40:29 merged: 2026-01-09 09:43:49

27. [49715](http://github.com/cms-sw/cmssw/pull/49715){:target="_blank"}  from **@patinkaew**: Add time info to Run3ScoutingHBHERecHit `core` `hlt` created: 2026-01-03 14:56:02 merged: 2026-01-07 21:36:06

28. [49712](http://github.com/cms-sw/cmssw/pull/49712){:target="_blank"}  from **@Dr15Jones**: Removed use of deprecated std::aligned_storage `core` created: 2025-12-30 21:59:33 merged: 2026-01-07 21:33:42

29. [49711](http://github.com/cms-sw/cmssw/pull/49711){:target="_blank"}  from **@Dr15Jones**: Add include needed for c++23 compilation `core` created: 2025-12-30 21:13:11 merged: 2026-01-03 10:17:58

30. [49710](http://github.com/cms-sw/cmssw/pull/49710){:target="_blank"}  from **@Dr15Jones**: Additional info when tests fail in DQMOffline/Configuration `dqm` created: 2025-12-29 19:30:27 merged: 2026-01-07 21:32:22

31. [49708](http://github.com/cms-sw/cmssw/pull/49708){:target="_blank"}  from **@makortel**: Avoid adding TF2 and TF3 to global list of functions `alca` `analysis` `dqm` `hlt` `reconstruction` `simulation` `xpog` `tracking` created: 2025-12-29 15:42:06 merged: 2026-01-07 21:33:12

32. [49707](http://github.com/cms-sw/cmssw/pull/49707){:target="_blank"}  from **@Pruthvi-ch**: Corrections to Center of gravity for v19 HGCAL cells `geometry` created: 2025-12-28 08:10:09 merged: 2026-01-05 07:52:27

33. [49706](http://github.com/cms-sw/cmssw/pull/49706){:target="_blank"}  from **@mseidel42**: btvNano: add abort condition for genParticle mother search `xpog` created: 2025-12-27 16:19:32 merged: 2026-01-09 16:41:56

34. [49705](http://github.com/cms-sw/cmssw/pull/49705){:target="_blank"}  from **@dan131riley**: Fixes for uninitialized variable use detected by valgrind `daq` `generators` `l1` `reconstruction` `simulation` created: 2025-12-26 17:38:56 merged: 2026-01-12 18:46:17

35. [49704](http://github.com/cms-sw/cmssw/pull/49704){:target="_blank"}  from **@dan131riley**: Pointer safety protection in XrdAdaptor error reporting `core` created: 2025-12-26 17:32:45 merged: 2026-01-05 07:52:41

36. [49701](http://github.com/cms-sw/cmssw/pull/49701){:target="_blank"}  from **@makortel**: Copy IOPool/SecondaryInput tests for RNTupleTemp IO `core` created: 2025-12-22 21:23:33 merged: 2025-12-30 07:36:29

37. [49698](http://github.com/cms-sw/cmssw/pull/49698){:target="_blank"}  from **@makortel**: Fix InputTag of `particleFlowClusterHBHE` `reconstruction` created: 2025-12-22 17:14:23 merged: 2026-01-01 15:05:32

38. [49697](http://github.com/cms-sw/cmssw/pull/49697){:target="_blank"}  from **@makortel**: Remove obsolete CUDA-using modules from DQM/SiPixelHeterogeneous `dqm` `trk` created: 2025-12-22 17:06:08 merged: 2026-01-07 21:34:42

39. [49686](http://github.com/cms-sw/cmssw/pull/49686){:target="_blank"}  from **@Dr15Jones**: Added OutputModuleCore::finalSelection `core` created: 2025-12-19 20:53:35 merged: 2025-12-22 21:08:29

40. [49685](http://github.com/cms-sw/cmssw/pull/49685){:target="_blank"}  from **@makortel**: Add two RNTuple utilities `core` created: 2025-12-19 20:50:25 merged: 2025-12-22 21:08:15

41. [49684](http://github.com/cms-sw/cmssw/pull/49684){:target="_blank"}  from **@stahlleiton**: Add 2026 PbPb eras `hlt` `operations` `pdmv` created: 2025-12-19 20:18:56 merged: 2026-01-05 16:17:05

42. [49683](http://github.com/cms-sw/cmssw/pull/49683){:target="_blank"}  from **@makortel**: Remove obsolete `FWCore/Integration/test/run_TestProcessBlock.sh` `core` created: 2025-12-19 15:55:17 merged: 2025-12-19 21:45:26

43. [49680](http://github.com/cms-sw/cmssw/pull/49680){:target="_blank"}  from **@mmusich**: Remove `cutTk` condition from `interpretationDescPSet` `hlt` `reconstruction` created: 2025-12-19 09:37:51 merged: 2025-12-21 07:11:31

44. [49677](http://github.com/cms-sw/cmssw/pull/49677){:target="_blank"}  from **@stahlleiton**: Update HF FG thresholds for 2025 PbPb `l1` created: 2025-12-18 21:52:04 merged: 2026-01-09 09:43:35

45. [49675](http://github.com/cms-sw/cmssw/pull/49675){:target="_blank"}  from **@SegmentLinking**: LST: Ensure quadruplet 'dBeta' initialization `reconstruction` `tracking` created: 2025-12-18 21:30:40 merged: 2025-12-22 07:46:36

46. [49666](http://github.com/cms-sw/cmssw/pull/49666){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `15_1_X` (4/N) [`16_1_X`] `hlt` created: 2025-12-18 11:45:37 merged: 2025-12-19 13:02:27

47. [49656](http://github.com/cms-sw/cmssw/pull/49656){:target="_blank"}  from **@makortel**: Remove most dictionaries of CUDADataFormats `reconstruction` `heterogeneous` `tracking` `trk` created: 2025-12-17 14:25:53 merged: 2025-12-19 21:46:38

48. [49654](http://github.com/cms-sw/cmssw/pull/49654){:target="_blank"}  from **@Dr15Jones**: Rename AdaptorConfig to TFileAdaptor `core` `dqm` `operations` `simulation` `tracking` `trk` created: 2025-12-17 14:04:48 merged: 2025-12-19 21:51:07

49. [49652](http://github.com/cms-sw/cmssw/pull/49652){:target="_blank"}  from **@Moanwar**: GNN Track-Tracksters Linking in TICLv5 `hlt` `operations` `reconstruction` `pdmv` created: 2025-12-17 09:44:48 merged: 2026-01-12 06:28:31

50. [49647](http://github.com/cms-sw/cmssw/pull/49647){:target="_blank"}  from **@mmusich**: use automatic upgrade Detector number redirection introduced in #49437 in the GPU matrix `pdmv` created: 2025-12-16 18:00:03 merged: 2025-12-22 09:19:33

51. [49644](http://github.com/cms-sw/cmssw/pull/49644){:target="_blank"}  from **@yihui-lai**: auto detect first vertex with Higgs in children list `generators` created: 2025-12-16 16:43:51 merged: 2026-01-13 16:46:27

52. [49617](http://github.com/cms-sw/cmssw/pull/49617){:target="_blank"}  from **@cms-ngt-hlt**: [NGT] Add MC truth labels support to NanoAOD `reco::Track`s and introduce PixelTracks+RecHits ntuples `hlt` `xpog` created: 2025-12-12 10:33:37 merged: 2026-01-04 17:35:19

53. [49566](http://github.com/cms-sw/cmssw/pull/49566){:target="_blank"}  from **@ghyls**: A `cmsenv_mpirun` that works transparently with OpenMPI 5, OpenMPI 4 and MPICH `heterogeneous` created: 2025-12-07 15:53:24 merged: 2025-12-21 07:11:17

54. [49482](http://github.com/cms-sw/cmssw/pull/49482){:target="_blank"}  from **@ljuckett**: Phase 2 - Add new tracker DQM histograms showing OT cluster position in 2S modules & ladders `dqm` `trk` created: 2025-11-26 11:51:46 merged: 2026-01-07 21:34:12

55. [49436](http://github.com/cms-sw/cmssw/pull/49436){:target="_blank"}  from **@chrishanw**: Feature: Simplified and improved Pixel Seed Creation `reconstruction` `tracking` `egamma` created: 2025-11-21 16:20:41 merged: 2025-12-21 07:08:16

56. [49295](http://github.com/cms-sw/cmssw/pull/49295){:target="_blank"}  from **@jsamudio**: Fix location of alpaka modification for particleFlowClusterHCAL `dqm` `reconstruction` created: 2025-11-03 15:09:52 merged: 2025-12-19 21:45:52

57. [48824](http://github.com/cms-sw/cmssw/pull/48824){:target="_blank"}  from **@makortel**: Improve `PortableHost{Collection,Object}` dictionary declarations `reconstruction` `simulation` `upgrade` `heterogeneous` `tracking` `trk` created: 2025-08-29 20:41:20 merged: 2026-01-13 16:37:42

58. [48263](http://github.com/cms-sw/cmssw/pull/48263){:target="_blank"}  from **@CMSTrackerDPG**: Reduce LogError noise when using (E)EoR3 CPE conditions `reconstruction` `db` `trk` created: 2025-06-06 13:50:48 merged: 2026-01-09 06:24:34

59. [47629](http://github.com/cms-sw/cmssw/pull/47629){:target="_blank"}  from **@pietroGru**: SiStripClusterizer, an Alpaka port of the CUDA ClustersFromRawProducerGPU `reconstruction` `heterogeneous` `trk` created: 2025-03-19 18:09:15 merged: 2026-01-13 16:35:04

#### CMSDIST Changes between Tags REL/CMSSW_16_0_0_pre4/el8_amd64_gcc13 and REL/CMSSW_16_1_0_pre1/el8_amd64_gcc13:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_16_0_0_pre4/el8_amd64_gcc13...REL/CMSSW_16_1_0_pre1/el8_amd64_gcc13)



1. [10271](http://github.com/cms-sw/cmsdist/pull/10271){:target="_blank"}  from **@cms-sw**: Update tag for DQM-Integration to V00-14-00 created: 2026-01-12 08:09:04 merged: 2026-01-12 08:09:06

2. [10268](http://github.com/cms-sw/cmsdist/pull/10268){:target="_blank"}  from **@cms-sw**: Update tag for RecoHGCal-TICL to V00-09-00 created: 2026-01-12 06:28:22 merged: 2026-01-12 06:28:24

3. [10265](http://github.com/cms-sw/cmsdist/pull/10265){:target="_blank"}  from **@BenjaminRS**: Updating UTM to 0.14.0 with NETETMHF created: 2026-01-07 14:58:16 merged: 2026-01-07 22:53:20

4. [10263](http://github.com/cms-sw/cmsdist/pull/10263){:target="_blank"}  from **@akritkbehera**: [ROOT636] Updated root to tip of branch v6-36-00-patches created: 2026-01-05 11:02:40 merged: 2026-01-06 09:26:32

5. [10258](http://github.com/cms-sw/cmsdist/pull/10258){:target="_blank"}  from **@cms-sw**: added TrivialSerialisation and stop build Dataformats*/plugins created: 2025-12-18 16:48:48 merged: 2025-12-18 23:33:29

6. [10250](http://github.com/cms-sw/cmsdist/pull/10250){:target="_blank"}  from **@fwyzard**: Update alpaka to 2.1.1 "Fixed Transformation" created: 2025-12-13 05:24:48 merged: 2026-01-07 22:45:57
