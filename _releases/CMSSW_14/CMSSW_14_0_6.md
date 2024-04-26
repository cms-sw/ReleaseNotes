---
layout: post
rel_link:  "14_0_6"
title:  "CMSSW_14_0_6"
date:   2024-04-25 14:14:40
categories: cmssw
relmajor: 14
relminor: 0
relsubminor: 6
---

# CMSSW_14_0_6
#### Changes since CMSSW_14_0_5_patch2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_0_5_patch2...CMSSW_14_0_6)



1. [44842](http://github.com/cms-sw/cmssw/pull/44842){:target="_blank"}  from **@fwyzard**: Add script to merge the JSON files produced by the FastTimerService [14.0.x] `hlt` created: 2024-04-24 18:32:23 merged: 2024-04-24 19:21:26

2. [44812](http://github.com/cms-sw/cmssw/pull/44812){:target="_blank"}  from **@RSalvatico**: Add filterBit to EGMNano [14_0_X] `xpog` `egamma` created: 2024-04-23 09:12:03 merged: 2024-04-24 11:03:43

3. [44808](http://github.com/cms-sw/cmssw/pull/44808){:target="_blank"}  from **@mmusich**: [14.0.X] `BrokenLineFit` and `RiemannFit`: mask asserts behind `DEBUG` flags `reconstruction` `tracking` created: 2024-04-23 07:12:56 merged: 2024-04-24 11:03:30

4. [44807](http://github.com/cms-sw/cmssw/pull/44807){:target="_blank"}  from **@hqucms**: [14_0_X] Using explicit lazy parsing & concrete data types in SimpleFlatTableProducer `alca` `reconstruction` `xpog` `trk` created: 2024-04-23 06:48:45 merged: 2024-04-24 13:47:08

5. [44805](http://github.com/cms-sw/cmssw/pull/44805){:target="_blank"}  from **@fwyzard**: Migrate `assert` to to `ALPAKA_ASSERT_ACC` [14.0.x] `alca` `reconstruction` `db` `heterogeneous` `tracking` `trk` created: 2024-04-22 21:01:01 merged: 2024-04-24 11:00:39

6. [44793](http://github.com/cms-sw/cmssw/pull/44793){:target="_blank"}  from **@fwyzard**: Skip invalid HCAL PF rechits in PFRecHitTopologyESProducer [14.0.x] `reconstruction` `heterogeneous` `pf` created: 2024-04-21 10:51:50 merged: 2024-04-22 17:32:19

7. [44774](http://github.com/cms-sw/cmssw/pull/44774){:target="_blank"}  from **@AdrianoDee**: [14_0_X] Allow Runtime Number of Hits for Alpaka Pixel Reconstruction `geometry` `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-04-18 14:57:46 merged: 2024-04-18 20:55:56

8. [44768](http://github.com/cms-sw/cmssw/pull/44768){:target="_blank"}  from **@mmusich**: [14.0.X] fixup eta lookup in `absEtaLowEdges_` in miscellaneous `RecoEgamma/EgammaHLTProducers` plugins  `hlt` `egamma` created: 2024-04-18 06:47:26 merged: 2024-04-18 18:09:52

9. [44763](http://github.com/cms-sw/cmssw/pull/44763){:target="_blank"}  from **@makortel**: [14_0_X] Ignore errors from `alpaka::enqueue()` in `CachingAllocator::free()` `heterogeneous` created: 2024-04-17 13:55:32 merged: 2024-04-22 15:27:52

10. [44762](http://github.com/cms-sw/cmssw/pull/44762){:target="_blank"}  from **@smuzaffar**: [14.0] Added missing header to fix header consistency `heterogeneous` created: 2024-04-17 13:46:49 merged: 2024-04-18 15:26:36

11. [44756](http://github.com/cms-sw/cmssw/pull/44756){:target="_blank"}  from **@mmusich**: [14.0.X] modified for Phase2 `DeepJet` retraining model  `hlt` created: 2024-04-17 07:40:40 merged: 2024-04-18 15:28:46

12. [44752](http://github.com/cms-sw/cmssw/pull/44752){:target="_blank"}  from **@rseidita**: Adding PUPPI jets and METs to offline DQM - backport to 14_0_X `dqm` created: 2024-04-16 12:38:20 merged: 2024-04-24 11:49:30

13. [44750](http://github.com/cms-sw/cmssw/pull/44750){:target="_blank"}  from **@rseidita**: Adding CSC MEs to per-LS scope in Offline DQM - backport to 14_0_X `dqm` created: 2024-04-16 11:51:23 merged: 2024-04-22 17:49:36

14. [44747](http://github.com/cms-sw/cmssw/pull/44747){:target="_blank"}  from **@AdrianoDee**: [14_0_X] - Fix for `EndPath`s in `DependecyGraph` `core` created: 2024-04-16 00:59:43 merged: 2024-04-18 15:28:05

15. [44739](http://github.com/cms-sw/cmssw/pull/44739){:target="_blank"}  from **@Dr15Jones**: Fix memory use when writing ParameterSets to files [14_0] `core` created: 2024-04-15 14:32:37 merged: 2024-04-16 12:17:36

16. [44736](http://github.com/cms-sw/cmssw/pull/44736){:target="_blank"}  from **@missirol**: fix PSet of `EvFDaqDirector` in `convertToRaw.py` [`14_0_X`] `hlt` created: 2024-04-15 08:36:32 merged: 2024-04-16 12:11:58

17. [44734](http://github.com/cms-sw/cmssw/pull/44734){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_0_X` (6/N) `hlt` created: 2024-04-14 09:05:02 merged: 2024-04-15 16:42:05

18. [44731](http://github.com/cms-sw/cmssw/pull/44731){:target="_blank"}  from **@mmusich**: [14.0.X] Updates in Alignment/OfflineValidation used in Run3 re-reco validations `alca` `trk` created: 2024-04-12 20:51:09 merged: 2024-04-15 16:40:44

19. [44725](http://github.com/cms-sw/cmssw/pull/44725){:target="_blank"}  from **@TizianoBevilacqua**: Addition of Photon HoE variable needed for H(gg) analysis `xpog` created: 2024-04-12 14:47:49 merged: 2024-04-15 16:38:58

20. [44723](http://github.com/cms-sw/cmssw/pull/44723){:target="_blank"}  from **@lucasrussell01**: [14_0_X] Add Unified ParT to tau NanoAOD (Backport) `reconstruction` `xpog` created: 2024-04-12 12:52:58 merged: 2024-04-22 17:52:36

21. [44720](http://github.com/cms-sw/cmssw/pull/44720){:target="_blank"}  from **@smorovic**: updated parameters and model for photon XGboost MVA (HLT) [14_0_X (backport)] `hlt` `reconstruction` `egamma` created: 2024-04-12 07:35:50 merged: 2024-04-12 20:58:40

22. [44718](http://github.com/cms-sw/cmssw/pull/44718){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_0_X` (5/N) `hlt` created: 2024-04-11 21:47:27 merged: 2024-04-12 20:59:18

23. [44716](http://github.com/cms-sw/cmssw/pull/44716){:target="_blank"}  from **@hqucms**: [14_0_X] Backport of 44507+44726 (Add ParticleNet legacy discriminator scores and mass regression to MINIAOD) `reconstruction` `xpog` created: 2024-04-11 19:49:54 merged: 2024-04-18 15:29:56

24. [44715](http://github.com/cms-sw/cmssw/pull/44715){:target="_blank"}  from **@mbluj**: Modify tau sequences to not pull payloads from outside GT (14_0_X) `reconstruction` `xpog` `tau` created: 2024-04-11 15:34:40 merged: 2024-04-15 16:37:11

25. [44714](http://github.com/cms-sw/cmssw/pull/44714){:target="_blank"}  from **@fwyzard**: Reorganise alpaka kernel loop functions [14.0.x] `reconstruction` `heterogeneous` created: 2024-04-11 15:28:07 merged: 2024-04-22 17:57:12

26. [44707](http://github.com/cms-sw/cmssw/pull/44707){:target="_blank"}  from **@hqucms**: [14_0_X] backport of 44335 (slimmedMETsNoHF and possible cleanup) `dqm` `reconstruction` `xpog` created: 2024-04-11 12:06:28 merged: 2024-04-18 15:30:31

27. [44705](http://github.com/cms-sw/cmssw/pull/44705){:target="_blank"}  from **@mmusich**: [14.0.X] add a unit test for conversion of `millepede.res` files into DB payloads `alca` `trk` created: 2024-04-11 08:19:30 merged: 2024-04-12 21:00:10

28. [44703](http://github.com/cms-sw/cmssw/pull/44703){:target="_blank"}  from **@fwyzard**: Use explicit acelerator types in alpaka tests [14.0.x] `heterogeneous` created: 2024-04-10 22:21:39 merged: 2024-04-12 21:00:51

29. [44697](http://github.com/cms-sw/cmssw/pull/44697){:target="_blank"}  from **@fmanteca**: [14_0_X] Removed pixelLayers requirement in MuonSelectors.cc `reconstruction` `muon` created: 2024-04-10 19:21:51 merged: 2024-04-12 21:02:40

30. [44690](http://github.com/cms-sw/cmssw/pull/44690){:target="_blank"}  from **@brallmond**: Updated Tau Filterbits for 2024 Data Taking [Backport] `xpog` `tau` created: 2024-04-10 10:35:07 merged: 2024-04-12 21:03:05

31. [44689](http://github.com/cms-sw/cmssw/pull/44689){:target="_blank"}  from **@mbluj**: Add reduced lepton time-life info to NanoAOD (14_0_X) `pdmv` `upgrade` `xpog` `tau` created: 2024-04-10 10:31:39 merged: 2024-04-22 17:57:47

32. [44684](http://github.com/cms-sw/cmssw/pull/44684){:target="_blank"}  from **@rovere**: Add HGCAL Hit calibration to Phase2 HLT. `dqm` `hgcal` created: 2024-04-10 09:01:00 merged: 2024-04-18 15:31:21

33. [44683](http://github.com/cms-sw/cmssw/pull/44683){:target="_blank"}  from **@hqucms**: [14_0_X] Add orbitNumber to NanoAOD `xpog` created: 2024-04-10 08:10:06 merged: 2024-04-12 21:03:40

34. [44675](http://github.com/cms-sw/cmssw/pull/44675){:target="_blank"}  from **@kyungminparkdrums**: Update ECAL DQM GPU input tag module names for alpaka [14_0_X] `dqm` created: 2024-04-09 14:42:15 merged: 2024-04-18 15:31:57

35. [44663](http://github.com/cms-sw/cmssw/pull/44663){:target="_blank"}  from **@fwyzard**: Move EventSetup record dependency to non-device source file [14.0.x] `reconstruction` `pf` created: 2024-04-09 06:34:49 merged: 2024-04-12 21:04:05

36. [44660](http://github.com/cms-sw/cmssw/pull/44660){:target="_blank"}  from **@AlexDeMoor**: [14_0_X] Introduce Unified Particle Transformer AK4 jet tagger (Backport)  `reconstruction` `xpog` `btv` `tau` `jetmet` created: 2024-04-08 21:56:46 merged: 2024-04-22 17:52:23

37. [44657](http://github.com/cms-sw/cmssw/pull/44657){:target="_blank"}  from **@24LopezR**: Add reco::displacedMuons to offline validation (backport) `dqm` created: 2024-04-08 15:09:44 merged: 2024-04-15 15:11:28

38. [44654](http://github.com/cms-sw/cmssw/pull/44654){:target="_blank"}  from **@namapane**: [14_0_X] New plugin for gen-part isolation. `xpog` created: 2024-04-08 09:04:33 merged: 2024-04-12 21:04:41

39. [44627](http://github.com/cms-sw/cmssw/pull/44627){:target="_blank"}  from **@Ming-Yan**: [Backport 14.0.X] backport customize BTVNano changes  `reconstruction` `pdmv` `upgrade` `xpog` `pf` created: 2024-04-04 22:20:30 merged: 2024-04-12 20:55:25

40. [44512](http://github.com/cms-sw/cmssw/pull/44512){:target="_blank"}  from **@saumyaphor4252**: [14.0.X] Update 2024 geometry and GEM alignment conditions in 2024 MC GTs `alca` created: 2024-03-22 12:00:24 merged: 2024-04-24 15:38:30

#### CMSDIST Changes between Tags REL/CMSSW_14_0_5_patch2/el8_amd64_gcc12 and REL/CMSSW_14_0_6/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_0_5_patch2/el8_amd64_gcc12...REL/CMSSW_14_0_6/el8_amd64_gcc12)



1. [9158](http://github.com/cms-sw/cmsdist/pull/9158){:target="_blank"}  from **@cms-sw**: [14.0.X] backport of multi-arch and scram os mismatch hook created: 2024-04-24 11:44:04 merged: 2024-04-25 11:12:05

2. [9148](http://github.com/cms-sw/cmsdist/pull/9148){:target="_blank"}  from **@hqucms**: [14_0_X] Update tag for RecoBTag-Combined to V01-22-00 created: 2024-04-19 10:59:14 merged: 2024-04-22 18:53:39

3. [9145](http://github.com/cms-sw/cmsdist/pull/9145){:target="_blank"}  from **@fwyzard**: Add NVML python bindings [14.0.x] created: 2024-04-17 20:45:23 merged: 2024-04-24 15:35:05

4. [9142](http://github.com/cms-sw/cmsdist/pull/9142){:target="_blank"}  from **@cms-sw**: [14.0.X] Backported fix for multiarch unit tests created: 2024-04-17 13:23:59 merged: 2024-04-19 08:22:45

5. [9140](http://github.com/cms-sw/cmsdist/pull/9140){:target="_blank"}  from **@mmusich**: [14.0.X] Update tag for RecoBTag-Combined to V01-21-00 created: 2024-04-17 07:41:24 merged: 2024-04-18 15:28:34

6. [9136](http://github.com/cms-sw/cmsdist/pull/9136){:target="_blank"}  from **@mmusich**: Update tag for RecoEgamma-PhotonIdentification to V01-08-00 created: 2024-04-14 07:42:57 merged: 2024-04-14 12:49:29
