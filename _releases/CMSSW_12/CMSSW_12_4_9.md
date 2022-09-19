---
layout: post
rel_link:  "12_4_9"
title:  "CMSSW_12_4_9"
date:   2022-09-18 21:09:29
categories: cmssw
relmajor: 12
relminor: 4
relsubminor: 9
---

# CMSSW_12_4_9
#### Changes since CMSSW_12_4_8:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_4_8...CMSSW_12_4_9)



1. [39421](http://github.com/cms-sw/cmssw/pull/39421){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `12_4_X` (8/N): HLT V1.4 of 2022 `hlt` created: 2022-09-16 13:20:53 merged: 2022-09-18 07:31:50

2. [39413](http://github.com/cms-sw/cmssw/pull/39413){:target="_blank"}  from **@eyigitba**: [12_4_X] Added protection against out-of-range BX values in EMTF unpacker blocks `l1` created: 2022-09-16 08:59:36 merged: 2022-09-18 19:56:58

3. [39399](http://github.com/cms-sw/cmssw/pull/39399){:target="_blank"}  from **@fwyzard**: Fix the `NVProfilerService` and `ProcessCallGraph` [12.4.x] `hlt` `heterogeneous` created: 2022-09-15 11:17:46 merged: 2022-09-17 08:09:41

4. [39395](http://github.com/cms-sw/cmssw/pull/39395){:target="_blank"}  from **@thomreis**: ECAL - Switch off online ECAL RecHit GPU vs. CPU monitoring - 12_4_X `dqm` created: 2022-09-14 17:31:40 merged: 2022-09-18 07:35:08

5. [39389](http://github.com/cms-sw/cmssw/pull/39389){:target="_blank"}  from **@eyigitba**: [12_4_X] Modify RPC and GEM unpacker blocks in EMTF unpacker to match the new Run 3 format `l1` created: 2022-09-14 13:04:07 merged: 2022-09-16 08:51:00

6. [39386](http://github.com/cms-sw/cmssw/pull/39386){:target="_blank"}  from **@mmusich**: [12.4.X] supply DQM for `SiPixelCalSingleMuonTight` `dqm` `operations` created: 2022-09-13 16:57:30 merged: 2022-09-17 08:13:28

7. [39383](http://github.com/cms-sw/cmssw/pull/39383){:target="_blank"}  from **@francescobrivio**: [12_4_X] Update PPS DMD tag, remove deprecated SiStrip DMD tag, add `SiStripBadStripFromHitEffRcd` `alca` `db` created: 2022-09-13 12:54:58 merged: 2022-09-14 21:42:55

8. [39379](http://github.com/cms-sw/cmssw/pull/39379){:target="_blank"}  from **@missirol**: support `XOR` operator in `triggerExpression::Parser` [`12_4_X`] `hlt` created: 2022-09-13 09:14:27 merged: 2022-09-14 21:46:44

9. [39373](http://github.com/cms-sw/cmssw/pull/39373){:target="_blank"}  from **@alejands**: [12_4_X] ECAL DQM GpuTask move enable flag checks to avoid unused collections from being consumed `dqm` created: 2022-09-12 19:37:18 merged: 2022-09-15 17:25:05

10. [39365](http://github.com/cms-sw/cmssw/pull/39365){:target="_blank"}  from **@mariadalfonso**: HBHE: arrival time [ backport 12_4 ] `reconstruction` created: 2022-09-10 11:24:33 merged: 2022-09-18 08:06:34

11. [39361](http://github.com/cms-sw/cmssw/pull/39361){:target="_blank"}  from **@CTPPS**: [124X] Fixed RP IDs in the PPS alignment harvester `alca` created: 2022-09-09 16:37:21 merged: 2022-09-11 20:47:35

12. [39357](http://github.com/cms-sw/cmssw/pull/39357){:target="_blank"}  from **@mmusich**: [12.4.X] `SiStripHitEfficiency` PCL workflow, take into account modules with `FEDErrors` `alca` created: 2022-09-09 13:48:46 merged: 2022-09-10 13:18:34

13. [39353](http://github.com/cms-sw/cmssw/pull/39353){:target="_blank"}  from **@francescobrivio**: [12_4_X] Add check of Tracker HV in BeamSpot DQM clients `alca` `dqm` `reconstruction` created: 2022-09-09 07:48:09 merged: 2022-09-09 13:27:30

14. [39349](http://github.com/cms-sw/cmssw/pull/39349){:target="_blank"}  from **@missirol**: introduce `MASKING` operator in `triggerExpression::Parser` [`12_4_X`] `hlt` created: 2022-09-08 13:55:10 merged: 2022-09-09 13:20:46

15. [39341](http://github.com/cms-sw/cmssw/pull/39341){:target="_blank"}  from **@francescobrivio**: [12_4_X] Fix try/catch in Vx3DHLTAnalyzer `dqm` `db` created: 2022-09-07 19:38:27 merged: 2022-09-09 13:22:23

16. [39334](http://github.com/cms-sw/cmssw/pull/39334){:target="_blank"}  from **@mmusich**: [12.4.X] `PrimaryVertexMonitor`: fix beamspot centering for Run3 and actually fill the beamspot type histograms `dqm` created: 2022-09-07 09:29:19 merged: 2022-09-08 07:31:47

17. [39332](http://github.com/cms-sw/cmssw/pull/39332){:target="_blank"}  from **@mmusich**: [12.4.X] Add Tracker Alignment di-muon monitoring to other resonances `dqm` created: 2022-09-07 09:12:53 merged: 2022-09-08 07:44:12

18. [39330](http://github.com/cms-sw/cmssw/pull/39330){:target="_blank"}  from **@AdrianoDee**: [12_4_X] Fix Pixel Clusters for Phase2 HLT Menu  `hlt` created: 2022-09-07 08:26:56 merged: 2022-09-15 07:19:00

19. [39326](http://github.com/cms-sw/cmssw/pull/39326){:target="_blank"}  from **@quark2**: Revive the green status on the lumi-based plots in GEM onlineDQM, a backport to 12_4_X `dqm` created: 2022-09-07 06:59:50 merged: 2022-09-09 13:25:28

20. [39306](http://github.com/cms-sw/cmssw/pull/39306){:target="_blank"}  from **@missirol**: specify compression settings in offline output modules used by HLT [`12_4_X`] `hlt` created: 2022-09-04 17:19:47 merged: 2022-09-06 21:49:21

21. [39290](http://github.com/cms-sw/cmssw/pull/39290){:target="_blank"}  from **@fabferro**: [12_4_X] Fix the mismatch in transition ID for idealGeo backport `geometry` created: 2022-09-02 12:17:16 merged: 2022-09-04 07:10:48

22. [39275](http://github.com/cms-sw/cmssw/pull/39275){:target="_blank"}  from **@swagata87**: [124X backport] [GSF tracking] Add TSOS only if it is meaningful `reconstruction` created: 2022-08-31 20:50:44 merged: 2022-09-04 07:07:17

23. [39271](http://github.com/cms-sw/cmssw/pull/39271){:target="_blank"}  from **@sam7k9621**: [backport] Update the EXODisappTrk skim source PD `pdmv` created: 2022-08-31 14:01:24 merged: 2022-09-05 20:03:07

24. [39258](http://github.com/cms-sw/cmssw/pull/39258){:target="_blank"}  from **@thomreis**: ECAL - Remove ExternalWork from EcalUncalibRecHitProducerGPU - 12_4_X `reconstruction` `heterogeneous` created: 2022-08-31 07:18:03 merged: 2022-09-04 07:21:37

25. [39253](http://github.com/cms-sw/cmssw/pull/39253){:target="_blank"}  from **@lathomas**: Compute/store unprefirable event information by default in MINIAOD `l1` `reconstruction` created: 2022-08-30 20:50:50 merged: 2022-08-31 13:24:25

26. [39248](http://github.com/cms-sw/cmssw/pull/39248){:target="_blank"}  from **@mmusich**: [12.4.X] Move `DiMuonMassBiasClient` to a regular harvesting path `dqm` `pdmv` `upgrade` created: 2022-08-30 07:30:38 merged: 2022-09-02 09:07:17

27. [39219](http://github.com/cms-sw/cmssw/pull/39219){:target="_blank"}  from **@tvami**: [124X] Add new tag for PPS PCL, move SiStrips tags to Prod `alca` `db` created: 2022-08-26 17:15:24 merged: 2022-08-29 08:02:56

28. [39211](http://github.com/cms-sw/cmssw/pull/39211){:target="_blank"}  from **@missirol**: [12_4_X] Declare production of Track collection after TrackExtra collection in modules run at HLT `hlt` `reconstruction` created: 2022-08-26 09:16:45 merged: 2022-08-29 08:04:30

29. [39210](http://github.com/cms-sw/cmssw/pull/39210){:target="_blank"}  from **@missirol**: improve replacement of `OutputModule`s in HLT `ConfDB` utilities [`12_4_X`] `hlt` created: 2022-08-26 09:06:35 merged: 2022-08-29 08:06:06

30. [39202](http://github.com/cms-sw/cmssw/pull/39202){:target="_blank"}  from **@swagata87**: [12_4_X backport] Do NaN-check before accepting a PF candidate for computing photon's isolation `reconstruction` created: 2022-08-25 20:22:25 merged: 2022-08-26 08:58:48

31. [39200](http://github.com/cms-sw/cmssw/pull/39200){:target="_blank"}  from **@kpedro88**: Fixes for DeepDoubleX [12_4_X] `reconstruction` created: 2022-08-25 18:10:11 merged: 2022-09-07 06:06:55

32. [39190](http://github.com/cms-sw/cmssw/pull/39190){:target="_blank"}  from **@dmeuser**: [12.4.X]  Enable veto logic for HG PCL Tracker alignment `alca` created: 2022-08-25 11:40:17 merged: 2022-08-29 08:08:34

33. [39175](http://github.com/cms-sw/cmssw/pull/39175){:target="_blank"}  from **@missirol**: allow `TriggerResultsFilter` to throw for invalid `HLTPathStatus` patterns [`12_4_X`] `hlt` created: 2022-08-24 12:49:59 merged: 2022-08-25 17:13:16

34. [39168](http://github.com/cms-sw/cmssw/pull/39168){:target="_blank"}  from **@davidwalter2**: Backport Updates on DQMOffline/ZCounting `dqm` created: 2022-08-24 08:41:13 merged: 2022-08-31 06:48:25

35. [39166](http://github.com/cms-sw/cmssw/pull/39166){:target="_blank"}  from **@mmusich**: [12.4.X] introduce `DiMuonMassBiasMonitor` and `DiMuonMassBiasClient`  `dqm` created: 2022-08-24 07:32:17 merged: 2022-08-25 17:35:00

36. [39162](http://github.com/cms-sw/cmssw/pull/39162){:target="_blank"}  from **@abhih1**: Timing, Laser and Hot cell quality plots adjustments  [12_4_X] `dqm` created: 2022-08-23 23:11:33 merged: 2022-09-08 07:49:42

37. [39146](http://github.com/cms-sw/cmssw/pull/39146){:target="_blank"}  from **@rgerosa**: Particle net monitoring dqm 124 x `dqm` `reconstruction` created: 2022-08-23 12:05:21 merged: 2022-09-08 07:36:46

38. [39145](http://github.com/cms-sw/cmssw/pull/39145){:target="_blank"}  from **@ChrisMisan**: [12_4_X] Fix OOT plot in PPS Diamond DQM `dqm` created: 2022-08-23 11:38:09 merged: 2022-08-25 17:36:33

#### CMSDIST Changes between Tags REL/CMSSW_12_4_8/el8_amd64_gcc10 and REL/CMSSW_12_4_9/el8_amd64_gcc10:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_4_8/el8_amd64_gcc10...REL/CMSSW_12_4_9/el8_amd64_gcc10)



1. [8083](http://github.com/cms-sw/cmsdist/pull/8083){:target="_blank"}  from **@cms-sw**: [12.4.X] backport multi-vec build rules and SCRAM created: 2022-09-12 13:49:52 merged: 2022-09-12 21:57:32

2. [8058](http://github.com/cms-sw/cmsdist/pull/8058){:target="_blank"}  from **@fwyzard**: Add `ROOT_INCLUDE_PATH` to `alpaka.xml` [12.4.x] created: 2022-08-31 18:57:27 merged: 2022-09-01 05:06:34

3. [8052](http://github.com/cms-sw/cmsdist/pull/8052){:target="_blank"}  from **@cms-sw**: [12.4][BuildRules] back port multi-vec fixes created: 2022-08-30 09:58:03 merged: 2022-08-31 05:26:44
