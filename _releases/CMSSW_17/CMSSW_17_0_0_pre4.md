---
layout: post
rel_link:  "17_0_0_pre4"
title:  "CMSSW_17_0_0_pre4"
date:   2026-07-25 09:26:10
categories: cmssw
relmajor: 17
relminor: 0
relsubminor: 0
relpre: _pre4
---

# CMSSW_17_0_0_pre4
#### Changes since CMSSW_17_0_0_pre3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_17_0_0_pre3...CMSSW_17_0_0_pre4)



1. [51496](http://github.com/cms-sw/cmssw/pull/51496){:target="_blank"}  from **@mroguljic**: [17.0.X] Correct compatible det propagation in `setSecondHitPattern` `reconstruction` `tracking` created: 2026-07-15 12:18:27 merged: 2026-07-21 15:57:51

2. [51493](http://github.com/cms-sw/cmssw/pull/51493){:target="_blank"}  from **@Parsifal-2045**: [17_0_X] Add `cudaKernelStackBudget` tool and richer CUDA device information `heterogeneous` created: 2026-07-15 09:21:27 merged: 2026-07-21 15:57:33

3. [51492](http://github.com/cms-sw/cmssw/pull/51492){:target="_blank"}  from **@fwyzard**: [17.0] Prevent MPI deadlock after a configuration error `heterogeneous` created: 2026-07-15 05:13:08 merged: 2026-07-20 03:42:47

4. [51491](http://github.com/cms-sw/cmssw/pull/51491){:target="_blank"}  from **@fwyzard**: [17.0] Fix `edmMpiConfigSplitter` logic for duplicated modules `heterogeneous` created: 2026-07-15 05:07:41 merged: 2026-07-21 15:57:16

5. [51490](http://github.com/cms-sw/cmssw/pull/51490){:target="_blank"}  from **@fwyzard**: [17.0] Implement `edmTypeInfo` `core` `heterogeneous` created: 2026-07-14 22:22:52 merged: 2026-07-20 03:42:32

6. [51475](http://github.com/cms-sw/cmssw/pull/51475){:target="_blank"}  from **@bfonta**: [170X] Add pre-selections to the Tau Validation. `dqm` created: 2026-07-13 14:06:04 merged: 2026-07-14 15:49:40

7. [51459](http://github.com/cms-sw/cmssw/pull/51459){:target="_blank"}  from **@silviodonato**: Stop running CPUOnly-duplicate HLT reconstruction sequences in MC production `hlt` created: 2026-07-09 11:49:07 merged: 2026-07-14 15:48:20

8. [51447](http://github.com/cms-sw/cmssw/pull/51447){:target="_blank"}  from **@michael-pitt**: Update GenProton NanoAOD acceptance for Run 3 [17_0_X] `xpog` created: 2026-07-08 10:49:59 merged: 2026-07-09 17:41:19

9. [51441](http://github.com/cms-sw/cmssw/pull/51441){:target="_blank"}  from **@bsunanda**: Phase2-hgx368E Bug fix in Geometry/HGCalGeometry, as pointed out by Daria Selivanova and Andreas Hinzman -- backport of #51439 `geometry` created: 2026-07-08 08:32:52 merged: 2026-07-09 10:35:50

10. [51430](http://github.com/cms-sw/cmssw/pull/51430){:target="_blank"}  from **@mkirsano**: fix2 HepMC3 Pythia8 EGun `generators` created: 2026-07-06 20:52:27 merged: 2026-07-07 07:36:21

11. [51417](http://github.com/cms-sw/cmssw/pull/51417){:target="_blank"}  from **@stahlleiton**: [17_0_X] Fix use of unsubtracted jets in tag info producers `reconstruction` created: 2026-07-06 00:00:16 merged: 2026-07-06 07:49:25

12. [51404](http://github.com/cms-sw/cmssw/pull/51404){:target="_blank"}  from **@mroguljic**: [17.0.X] Store SiPixelDigi collections in AlCaRecos that store pixel clusters `alca` `trk` created: 2026-07-03 13:25:58 merged: 2026-07-08 05:29:50

13. [51377](http://github.com/cms-sw/cmssw/pull/51377){:target="_blank"}  from **@stahlleiton**: Add HIN Run3 Mini2Mini relvals `operations` `pdmv` `reconstruction` `xpog` created: 2026-06-30 13:17:21 merged: 2026-07-12 08:52:00

14. [51336](http://github.com/cms-sw/cmssw/pull/51336){:target="_blank"}  from **@slava77**: LST: set T5 occupancy threshold at 100K (backport of #51333) `reconstruction` `tracking` created: 2026-06-26 19:43:45 merged: 2026-07-09 10:32:45

15. [51294](http://github.com/cms-sw/cmssw/pull/51294){:target="_blank"}  from **@artlbv**: [Backport of #51263] [Phase-2 L1T] Move TauNNIdHW to the externally-built NNPuppiTauModel package  `l1` created: 2026-06-23 14:37:19 merged: 2026-07-14 15:46:36

16. [51240](http://github.com/cms-sw/cmssw/pull/51240){:target="_blank"}  from **@bsunanda**: Phase2-hgx367F Make a new scenario for Phase2 with latest versions of Tracker, HGCal, GE0 and MTD `geometry` `operations` `pdmv` created: 2026-06-17 09:37:12 merged: 2026-07-24 14:07:42

17. [51233](http://github.com/cms-sw/cmssw/pull/51233){:target="_blank"}  from **@li-chenyan**: [17_0_X][L1T] Changed the CENT Threshold and LUT for PbPb 2026 run `l1` created: 2026-06-16 21:19:54 merged: 2026-07-03 08:04:12

18. [51192](http://github.com/cms-sw/cmssw/pull/51192){:target="_blank"}  from **@alexstrel**: backport of #50887 Hotfix for Alpaka MD PF clusterizer (CPU backend) `heterogeneous` `pf` `reconstruction` created: 2026-06-10 20:03:31 merged: 2026-07-14 15:47:35

#### CMSDIST Changes between Tags REL/CMSSW_17_0_0_pre3/el8_amd64_gcc13 and REL/CMSSW_17_0_0_pre4/el8_amd64_gcc13:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_17_0_0_pre3/el8_amd64_gcc13...REL/CMSSW_17_0_0_pre4/el8_amd64_gcc13)



1. [10702](http://github.com/cms-sw/cmsdist/pull/10702){:target="_blank"}  from **@cms-sw**: [17.0.X] Update DQM-Integration version to V00-18-02 created: 2026-07-03 11:10:28 merged: 2026-07-03 12:49:32

2. [10679](http://github.com/cms-sw/cmsdist/pull/10679){:target="_blank"}  from **@artlbv**: [Backport] Add NNPuppiTauModel external spec and toolfile created: 2026-06-23 14:36:09 merged: 2026-07-14 15:46:06
