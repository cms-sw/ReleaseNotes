---
layout: post
rel_link:  "13_0_0"
title:  "CMSSW_13_0_0"
date:   2023-03-05 22:38:50
categories: cmssw
relmajor: 13
relminor: 0
relsubminor: 0
---

# CMSSW_13_0_0
#### Changes since CMSSW_13_0_0_pre4:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_13_0_0_pre4...CMSSW_13_0_0)



1. [40948](http://github.com/cms-sw/cmssw/pull/40948){:target="_blank"}  from **@eyigitba**: [13_0_X] Modify EMTF unpacker to support new reduced DAQ window for 2023 data taking `l1` created: 2023-03-03 12:12:07 merged: 2023-03-04 07:54:23

2. [40935](http://github.com/cms-sw/cmssw/pull/40935){:target="_blank"}  from **@makortel**: [13_0_X] Allow access to const edm::{Event,EventSetup} from device::{Event,EventSetup} `heterogeneous` created: 2023-03-02 17:20:44 merged: 2023-03-03 10:53:22

3. [40929](http://github.com/cms-sw/cmssw/pull/40929){:target="_blank"}  from **@missirol**: use unique names for outputs of HLT-DQM unit tests [`13_0_X`] `dqm` `hlt` created: 2023-03-02 09:55:30 merged: 2023-03-03 20:15:36

4. [40919](http://github.com/cms-sw/cmssw/pull/40919){:target="_blank"}  from **@missirol**: avoid duplicates in `HLTPMMassFilter` plugin [`13_0_X`] `hlt` created: 2023-03-01 17:34:58 merged: 2023-03-03 10:58:06

5. [40908](http://github.com/cms-sw/cmssw/pull/40908){:target="_blank"}  from **@civanch**: [13_0_X] Fix generator interface to Geant4 `simulation` created: 2023-03-01 10:43:21 merged: 2023-03-02 10:33:56

6. [40896](http://github.com/cms-sw/cmssw/pull/40896){:target="_blank"}  from **@mmusich**: [13.0.X] Disentangle `TrackerTrackHitFilter` from phase-0 Strip conditions and activate common alignment track refitter sequence for phase-2 `alca` `reconstruction` `tracking` `trk` created: 2023-02-28 16:04:15 merged: 2023-03-01 08:46:30

7. [40894](http://github.com/cms-sw/cmssw/pull/40894){:target="_blank"}  from **@cmsbuild**: Initialise local variables to null pointers [13.0.x] `heterogeneous` created: 2023-02-28 14:18:39 merged: 2023-03-01 08:36:31

8. [40892](http://github.com/cms-sw/cmssw/pull/40892){:target="_blank"}  from **@cms-sw**: Drop unused lto flags in `BigProducts/Simulation` BuildFile `core` `simulation` created: 2023-02-28 08:23:07 merged: 2023-02-28 13:02:25

9. [40883](http://github.com/cms-sw/cmssw/pull/40883){:target="_blank"}  from **@srimanob**: [13_0 backport] Add 2023 DD4hep XML wf `pdmv` `upgrade` created: 2023-02-25 05:35:53 merged: 2023-02-28 09:04:00

10. [40875](http://github.com/cms-sw/cmssw/pull/40875){:target="_blank"}  from **@arossi83**: Fix Tracks related Pixel quantities at HLT DQM (backport) `dqm` `reconstruction` `tracking` `trk` created: 2023-02-24 10:51:52 merged: 2023-03-01 08:44:43

11. [40874](http://github.com/cms-sw/cmssw/pull/40874){:target="_blank"}  from **@davidwalter2**: DQMOffline/Lumi zcounting backport of PR #40815 [CMSSW_13_0_X] `dqm` created: 2023-02-24 10:50:00 merged: 2023-03-01 09:12:25

12. [40872](http://github.com/cms-sw/cmssw/pull/40872){:target="_blank"}  from @missirol: use `**@standardDQM**` for Run-3 re-HLT workflows [`13_0_X`] `pdmv` `upgrade` created: 2023-02-24 09:02:20 merged: 2023-02-27 09:01:57

13. [40871](http://github.com/cms-sw/cmssw/pull/40871){:target="_blank"}  from **@missirol**: improve `HLTMuonValidator` and `HLTMuonPlotter` (no UB, consider only `HLTFilter` modules) [`13_0_X`] `dqm` created: 2023-02-24 08:42:05 merged: 2023-02-27 09:13:24

14. [40870](http://github.com/cms-sw/cmssw/pull/40870){:target="_blank"}  from **@AdrianoDee**: [13_0_X] Fix `cudaMemcpyAsync` for `localCoordToHostAsync` `reconstruction` `heterogeneous` `tracking` created: 2023-02-24 08:21:46 merged: 2023-03-01 09:05:02

15. [40866](http://github.com/cms-sw/cmssw/pull/40866){:target="_blank"}  from **@bsunanda**: Run3-gex155X Backport #40865 to CMSSW_13_0_X for additional Run3 files needed as the step1 for making 2023 geometry payload `geometry` `operations` `upgrade` created: 2023-02-24 02:33:52 merged: 2023-02-27 09:42:39

16. [40864](http://github.com/cms-sw/cmssw/pull/40864){:target="_blank"}  from **@fwyzard**: Fix synchronization in ContextState test [13.0.x] `heterogeneous` created: 2023-02-23 22:55:49 merged: 2023-02-24 07:50:18

17. [40862](http://github.com/cms-sw/cmssw/pull/40862){:target="_blank"}  from **@bsunanda**: Phase2-gex154C Backport to 13_0_X to fix the issues of 2026D91 and 2026D94 `geometry` `operations` `upgrade` created: 2023-02-23 16:57:09 merged: 2023-02-24 07:55:09

18. [40861](http://github.com/cms-sw/cmssw/pull/40861){:target="_blank"}  from **@elfontan**: [Backport] uGT fix for muon showers full emulation and for HMT mismatches in the DQM workflow `dqm` `l1` `l1t` created: 2023-02-23 14:16:38 merged: 2023-02-27 06:30:08

19. [40860](http://github.com/cms-sw/cmssw/pull/40860){:target="_blank"}  from **@cms-tsg-storm**: Use frozen HLT menu `2022v15` in `13_0_X` Run-3 RelVals `hlt` created: 2023-02-23 13:57:47 merged: 2023-02-23 19:49:24

20. [40851](http://github.com/cms-sw/cmssw/pull/40851){:target="_blank"}  from **@fwyzard**: Remove the CUDAService from the HLT configuration [13.0.x] `hlt` created: 2023-02-22 19:55:32 merged: 2023-02-23 19:50:37

21. [40843](http://github.com/cms-sw/cmssw/pull/40843){:target="_blank"}  from **@CTPPS**: PPS diamond mapping XML for 2023 run (backport) `alca` `reconstruction` `ctpps` created: 2023-02-21 21:25:30 merged: 2023-02-22 15:41:31

22. [40842](http://github.com/cms-sw/cmssw/pull/40842){:target="_blank"}  from **@dinyar**: [13_0_X] Fix uGT shower unpacking `l1` created: 2023-02-21 19:43:13 merged: 2023-02-24 07:58:39

23. [40839](http://github.com/cms-sw/cmssw/pull/40839){:target="_blank"}  from **@kakwok**: [13_0_X]Update HMT shower thresholds for HMT emulation in CSC `l1` created: 2023-02-21 14:21:21 merged: 2023-02-22 07:44:23

24. [40836](http://github.com/cms-sw/cmssw/pull/40836){:target="_blank"}  from **@eyigitba**: [13_0_X] Fix RPC and GEM TP unpacking in EMTF unpacker `l1` created: 2023-02-21 13:14:44 merged: 2023-02-22 07:45:38

25. [40831](http://github.com/cms-sw/cmssw/pull/40831){:target="_blank"}  from **@laurenhay**: Run 3 jetid backport `operations` `reconstruction` `xpog` `jetmet` created: 2023-02-21 00:57:02 merged: 2023-02-22 13:56:37

26. [40826](http://github.com/cms-sw/cmssw/pull/40826){:target="_blank"}  from **@makortel**: [13_0_X] Move dictionary declarations of Alpaka serial backend data products to the host classes_def.xml `heterogeneous` created: 2023-02-20 16:57:57 merged: 2023-02-22 07:48:08

27. [40823](http://github.com/cms-sw/cmssw/pull/40823){:target="_blank"}  from **@covarell**: add double PFTau HLT filter [13_0_X] `hlt` created: 2023-02-20 14:27:46 merged: 2023-02-21 17:40:16

28. [40818](http://github.com/cms-sw/cmssw/pull/40818){:target="_blank"}  from **@makortel**: [13_0_X] Include product instance name for the data product copied implicitly to host in Alpaka EDProducers `heterogeneous` created: 2023-02-20 06:46:42 merged: 2023-02-20 16:34:42

29. [40816](http://github.com/cms-sw/cmssw/pull/40816){:target="_blank"}  from **@bsunanda**: Run3-gex153X Backport #40783 to CMSSW version 13_0_X the 2023 Geometry modified because of shifted positions of GE21 Chambers `geometry` `operations` `upgrade` created: 2023-02-18 09:46:48 merged: 2023-02-23 11:27:09

30. [40811](http://github.com/cms-sw/cmssw/pull/40811){:target="_blank"}  from **@francescobrivio**: [13_0_X] Fix BeamSpot Z value in Realistic25ns13p6TeVEOY2022Collision VtxSmearing scenario `simulation` created: 2023-02-17 15:35:14 merged: 2023-02-19 22:14:53

31. [40809](http://github.com/cms-sw/cmssw/pull/40809){:target="_blank"}  from **@fwyzard**: Minor improvements to Alpaka tests [13.0.x] `heterogeneous` created: 2023-02-17 14:53:29 merged: 2023-02-19 22:23:42

32. [40801](http://github.com/cms-sw/cmssw/pull/40801){:target="_blank"}  from **@jshin96**: [PileupJetId, Puppi] Backport of #40762 (Pileup ID input variable fix, puppi weight ValueMap access, optional photon protection for existing puppi weights) to CMSSW_13_0_X `reconstruction` `xpog` created: 2023-02-17 02:05:12 merged: 2023-02-21 17:45:23

33. [40796](http://github.com/cms-sw/cmssw/pull/40796){:target="_blank"}  from **@makortel**: [13_0_X] Remove call to alpaka::getDev() in test code when allocating TestDeviceCollection `heterogeneous` created: 2023-02-16 18:07:21 merged: 2023-02-17 17:51:13

34. [40791](http://github.com/cms-sw/cmssw/pull/40791){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_0_X` (2/N) `hlt` created: 2023-02-16 15:46:21 merged: 2023-02-17 12:45:57

35. [40784](http://github.com/cms-sw/cmssw/pull/40784){:target="_blank"}  from **@missirol**: stop using bare ROOT objects in `HLTDQMHist*` classes [`13_0_X`] `dqm` created: 2023-02-16 12:13:12 merged: 2023-02-20 11:47:34

36. [40781](http://github.com/cms-sw/cmssw/pull/40781){:target="_blank"}  from **@bsunanda**: Phase2-gex335R Backport #40644 to CMSSW_13_0_X to complete v17 definition of HGCal with different lateral sizes of the components inside a silicon module `geometry` `upgrade` created: 2023-02-16 01:52:32 merged: 2023-02-21 11:35:54

37. [40772](http://github.com/cms-sw/cmssw/pull/40772){:target="_blank"}  from **@fwyzard**: Alpaka-related updates [13.0.x] `core` `heterogeneous` created: 2023-02-15 00:11:26 merged: 2023-02-16 08:47:36

38. [40768](http://github.com/cms-sw/cmssw/pull/40768){:target="_blank"}  from **@hftsoi**: [backport] HCAL Fb DQM monitoring at layer1 `dqm` created: 2023-02-14 17:45:13 merged: 2023-02-15 07:27:46

39. [40766](http://github.com/cms-sw/cmssw/pull/40766){:target="_blank"}  from **@francescobrivio**: [13_0_X] Adding a check on the BS transverse widths in OnlineBeamSpotESProducer `alca` `reconstruction` `tracking` created: 2023-02-14 16:36:57 merged: 2023-02-20 11:54:57

40. [40759](http://github.com/cms-sw/cmssw/pull/40759){:target="_blank"}  from **@perrotta**: [13_0_X] Only compare geometry in Geometry/TrackerGoeometryBuilder test `geometry` `trk` created: 2023-02-14 07:15:57 merged: 2023-02-14 13:40:34

41. [40749](http://github.com/cms-sw/cmssw/pull/40749){:target="_blank"}  from **@Dr15Jones**: Extended SimpleMemoryCheck to print RSS info to the logger `core` created: 2023-02-10 20:31:43 merged: 2023-02-11 07:11:49

42. [40738](http://github.com/cms-sw/cmssw/pull/40738){:target="_blank"}  from **@makortel**: Clarify ProcessAccelerator documentation `core` created: 2023-02-09 21:41:40 merged: 2023-02-11 07:08:06

43. [40732](http://github.com/cms-sw/cmssw/pull/40732){:target="_blank"}  from **@zhokin2**: HCAL: bug fixed in DPGAnalysis/HcalTools for 2023 Run3 `dqm` `hcal` created: 2023-02-09 06:25:01 merged: 2023-02-11 07:04:49

44. [40727](http://github.com/cms-sw/cmssw/pull/40727){:target="_blank"}  from **@mmusich**: add a unit Test for `OnlineBeamMonitor` `dqm` `db` `tracking` created: 2023-02-08 13:47:40 merged: 2023-02-11 07:08:12

45. [40725](http://github.com/cms-sw/cmssw/pull/40725){:target="_blank"}  from **@fwyzard**: CUDA, ROCm and Alpaka-related updates [13.0.x] `alca` `operations` `reconstruction` `upgrade` `heterogeneous` `tracking` `trk` created: 2023-02-08 13:20:17 merged: 2023-03-02 16:03:16

#### CMSDIST Changes between Tags REL/CMSSW_13_0_0_pre4/el8_amd64_gcc11 and REL/CMSSW_13_0_0/el8_amd64_gcc11:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_13_0_0_pre4/el8_amd64_gcc11...REL/CMSSW_13_0_0/el8_amd64_gcc11)



1. [8347](http://github.com/cms-sw/cmsdist/pull/8347){:target="_blank"}  from **@fwyzard**: [BuildRules] Enable alpaka ROCm backend [13.0.x] created: 2023-03-02 11:13:25 merged: 2023-03-03 12:39:57

2. [8342](http://github.com/cms-sw/cmsdist/pull/8342){:target="_blank"}  from **@cms-sw**: [LTO] Enable lto for 13.0.X created: 2023-02-28 08:40:48 merged: 2023-02-28 13:43:02

3. [8334](http://github.com/cms-sw/cmsdist/pull/8334){:target="_blank"}  from **@fwyzard**: Update OpenMPI to version 4.1.5 [13.0.x] created: 2023-02-24 03:07:42 merged: 2023-03-02 16:30:46

4. [8317](http://github.com/cms-sw/cmsdist/pull/8317){:target="_blank"}  from **@cms-sw**: move sanitizer flags in to toolfile; drop sanitizer deps for rocm prod created: 2023-02-15 14:15:08 merged: 2023-02-15 21:11:08

5. [8316](http://github.com/cms-sw/cmsdist/pull/8316){:target="_blank"}  from **@fwyzard**: Update Alpaka to the development branch as of 2023.02.15 [13.0.x] created: 2023-02-15 08:01:07 merged: 2023-03-02 16:23:40
