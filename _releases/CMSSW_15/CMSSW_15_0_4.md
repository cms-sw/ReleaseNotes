---
layout: post
rel_link:  "15_0_4"
title:  "CMSSW_15_0_4"
date:   2025-04-08 06:28:56
categories: cmssw
relmajor: 15
relminor: 0
relsubminor: 4
---

# CMSSW_15_0_4
#### Changes since CMSSW_15_0_3_patch1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_15_0_3_patch1...CMSSW_15_0_4)



1. [47797](http://github.com/cms-sw/cmssw/pull/47797){:target="_blank"}  from **@mmusich**: [15.0.X] Miscellaneous updates for modules targeting CDC reconstruction at HLT `reconstruction` `tracking` created: 2025-04-07 14:07:16 merged: 2025-04-08 05:35:58

2. [47783](http://github.com/cms-sw/cmssw/pull/47783){:target="_blank"}  from **@mmusich**: [15.0.X] fix `TrackToTrackComparisonHists` logic for cosmics `dqm` `tracking` created: 2025-04-03 16:11:33 merged: 2025-04-07 15:08:11

3. [47768](http://github.com/cms-sw/cmssw/pull/47768){:target="_blank"}  from **@smorovic**: [DAQ] fix DAQSource race condition (15_0_X) `daq` created: 2025-04-02 19:11:16 merged: 2025-04-07 08:39:58

4. [47754](http://github.com/cms-sw/cmssw/pull/47754){:target="_blank"}  from **@smorovic**: [HLTrigger/Egamma] fix swapped eta parameter for photons in Diphoton XGBoost MVA filter (15_0_X) `hlt` created: 2025-04-02 08:00:30 merged: 2025-04-07 08:40:04

5. [47746](http://github.com/cms-sw/cmssw/pull/47746){:target="_blank"}  from **@mmusich**: [15.0.X] add `dqmInfoHLTMon` to `offlineHLTSource` in `DQMOffline_Trigger_cosmics` and enable `showHLTGlobalTag` `dqm` created: 2025-04-01 08:27:55 merged: 2025-04-07 08:40:29

6. [47742](http://github.com/cms-sw/cmssw/pull/47742){:target="_blank"}  from **@Dongwoon77**: [15_0_X] Update on GEM offlineDQM Cluster plots to backport 15_0_X `dqm` created: 2025-03-31 15:58:46 merged: 2025-04-07 15:09:05

7. [47741](http://github.com/cms-sw/cmssw/pull/47741){:target="_blank"}  from **@asavincms**: Include L1Calo ZS modifications from 15_1_X to 15_0_x `l1` created: 2025-03-31 15:03:35 merged: 2025-04-02 05:27:51

8. [47737](http://github.com/cms-sw/cmssw/pull/47737){:target="_blank"}  from **@hqucms**: [15_0_X] Reduce memory usage in NANO merge jobs `xpog` created: 2025-03-31 10:49:47 merged: 2025-04-01 18:26:53

9. [47733](http://github.com/cms-sw/cmssw/pull/47733){:target="_blank"}  from **@fwyzard**: Remove legacy CUDA modules for HCAL unpacking and local reconstruction [15.0.x] `alca` `dqm` `reconstruction` `simulation` `db` `heterogeneous` created: 2025-03-29 14:15:56 merged: 2025-04-02 05:30:35

10. [47727](http://github.com/cms-sw/cmssw/pull/47727){:target="_blank"}  from **@kakwok**: [15_0_X] Update 2025 HMT shower thresholds for pp collision `l1` `operations` created: 2025-03-28 15:23:44 merged: 2025-04-02 05:20:40

11. [47722](http://github.com/cms-sw/cmssw/pull/47722){:target="_blank"}  from **@kandrosov**: [15_0_X] Adding L1TauTriggerFilterObjectProducer (backport) `hlt` created: 2025-03-28 08:58:46 merged: 2025-04-02 05:21:34

12. [47715](http://github.com/cms-sw/cmssw/pull/47715){:target="_blank"}  from **@y19y19**: fix a bug in miniAOD_tools.py backport to CMSSW_15_0_X `reconstruction` `xpog` created: 2025-03-27 17:14:31 merged: 2025-04-02 05:30:05

13. [47705](http://github.com/cms-sw/cmssw/pull/47705){:target="_blank"}  from **@cms-tsg-storm**: [15.0.X] remove hardcoded IP substitution for `dbproxy` option of `hltGetConfiguration` `hlt` created: 2025-03-26 19:28:16 merged: 2025-04-02 05:26:25

14. [47676](http://github.com/cms-sw/cmssw/pull/47676){:target="_blank"}  from **@mmusich**: [15.0.X] provide a `fillDescriptions` method for `CondDBESSource` `alca` `dqm` `hlt` `reconstruction` `db` `trk` created: 2025-03-24 11:38:08 merged: 2025-04-01 18:26:24

15. [47673](http://github.com/cms-sw/cmssw/pull/47673){:target="_blank"}  from **@fwyzard**: `AlpakaServiceSerialSync` should always be available [15.0.x] `heterogeneous` created: 2025-03-24 00:10:19 merged: 2025-04-02 05:30:47

16. [47671](http://github.com/cms-sw/cmssw/pull/47671){:target="_blank"}  from **@fwyzard**: Fix Service type name displayed in error message [15.0.x] `core` created: 2025-03-23 23:49:11 merged: 2025-04-02 05:31:42

17. [47619](http://github.com/cms-sw/cmssw/pull/47619){:target="_blank"}  from **@cms-AlCaDB**: [15_0] Print diagnostics on ProductResolver's loadTag setIntervalFor and IOVProxy's fetchSequence `alca` `db` created: 2025-03-18 17:34:24 merged: 2025-04-07 08:39:24

18. [47609](http://github.com/cms-sw/cmssw/pull/47609){:target="_blank"}  from **@nothingface0**: [DQM] Add print of GT on DQM online clients [`15_0_X`] `dqm` created: 2025-03-17 10:38:42 merged: 2025-04-07 15:07:32

#### CMSDIST Changes between Tags REL/CMSSW_15_0_3_patch1/el8_amd64_gcc12 and REL/CMSSW_15_0_4/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_15_0_3_patch1/el8_amd64_gcc12...REL/CMSSW_15_0_4/el8_amd64_gcc12)



1. [9760](http://github.com/cms-sw/cmsdist/pull/9760){:target="_blank"}  from **@cms-sw**: [15.0.X] Updated root to tip of branch v6-32 created: 2025-03-27 16:00:35 merged: 2025-03-28 08:49:28
