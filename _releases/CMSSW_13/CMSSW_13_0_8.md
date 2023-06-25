---
layout: post
rel_link:  "13_0_8"
title:  "CMSSW_13_0_8"
date:   2023-06-24 19:45:24
categories: cmssw
relmajor: 13
relminor: 0
relsubminor: 8
---

# CMSSW_13_0_8
#### Changes since CMSSW_13_0_7_patch1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_13_0_7_patch1...CMSSW_13_0_8)



1. [42018](http://github.com/cms-sw/cmssw/pull/42018){:target="_blank"}  from **@rvenditti**: Backport of New definition of the DQM offline sequence to be run on Express strea `dqm` `operations` created: 2023-06-19 15:55:33 merged: 2023-06-23 11:52:18

2. [42014](http://github.com/cms-sw/cmssw/pull/42014){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_0_X` (10/N): GRun menu V1.2 of 2023 `hlt` created: 2023-06-19 14:20:59 merged: 2023-06-20 21:11:46

3. [42004](http://github.com/cms-sw/cmssw/pull/42004){:target="_blank"}  from **@eyigitba**: [13_0_X] EMTF muon shower unpacker update `l1` created: 2023-06-19 08:03:59 merged: 2023-06-20 14:12:19

4. [42002](http://github.com/cms-sw/cmssw/pull/42002){:target="_blank"}  from **@missirol**: fix how `HLTDeDxFilter` fills `TriggerFilterObjectWithRefs` output product [`13_0_X`] `reconstruction` `tracking` created: 2023-06-18 21:12:51 merged: 2023-06-22 18:37:05

5. [41999](http://github.com/cms-sw/cmssw/pull/41999){:target="_blank"}  from **@bsunanda**: Run3-gex164B Fix the bug in the RPC geometry - backport of the PRs #41907, #41921, #41990 from 13_2_X to 13_0_X `geometry` `upgrade` created: 2023-06-18 14:29:57 merged: 2023-06-20 14:34:40

6. [41992](http://github.com/cms-sw/cmssw/pull/41992){:target="_blank"}  from **@mmusich**: [13.0.X] zeroed mono/stereo cluster counts in `SiStripMonitorTrack` at each event loop `dqm` `trk` created: 2023-06-16 18:12:07 merged: 2023-06-20 14:35:07

7. [41968](http://github.com/cms-sw/cmssw/pull/41968){:target="_blank"}  from **@mmusich**: [13.0.X] add protection to `ParticleNetJetTagMonitor`, removed unused struct `dqm` created: 2023-06-15 07:19:34 merged: 2023-06-15 15:16:15

8. [41966](http://github.com/cms-sw/cmssw/pull/41966){:target="_blank"}  from **@mmusich**: remove tracking efficiency and fake rate w.r.t. offline plots from list of ME to be outputed by LS [13.0.X] `dqm` created: 2023-06-14 16:41:17 merged: 2023-06-14 21:18:59

9. [41960](http://github.com/cms-sw/cmssw/pull/41960){:target="_blank"}  from **@francescobrivio**: [13_0_X] Add preliminary GTs for 2023 MC and new L1T menu to relval/ideal/2024/run4 GTs and re-snapshot data GTS `alca` created: 2023-06-14 15:15:15 merged: 2023-06-15 15:14:27

10. [41956](http://github.com/cms-sw/cmssw/pull/41956){:target="_blank"}  from **@eyigitba**: [13_0_X] Change EMTF Primitive Conversion LUT Assignment for MC `l1` created: 2023-06-14 09:31:56 merged: 2023-06-15 04:40:56

11. [41953](http://github.com/cms-sw/cmssw/pull/41953){:target="_blank"}  from **@cms-tsg-storm**: Update of L1T pp menu in TSG GTs to `L1Menu_Collisions2023_v1_2_0_xml` [`13_0_X`] `hlt` created: 2023-06-14 09:11:32 merged: 2023-06-15 04:38:45

12. [41949](http://github.com/cms-sw/cmssw/pull/41949){:target="_blank"}  from **@barvic**: [13_0_X] backport. CSC Unpacker fix for handling of rare CSC data corruption `reconstruction` `muon` created: 2023-06-13 22:37:44 merged: 2023-06-15 04:36:46

13. [41939](http://github.com/cms-sw/cmssw/pull/41939){:target="_blank"}  from **@mmusich**: [13.0.X] Add `SiPixelRawDataError` monitoring for `gpuValidation` setup `dqm` `trk` created: 2023-06-13 08:45:57 merged: 2023-06-14 21:26:05

14. [41933](http://github.com/cms-sw/cmssw/pull/41933){:target="_blank"}  from **@makortel**: [13_0_X] Add isAvailable() function to RefToBaseProd `core` created: 2023-06-12 15:51:29 merged: 2023-06-13 04:55:08

15. [41912](http://github.com/cms-sw/cmssw/pull/41912){:target="_blank"}  from **@mmusich**: [13.0.X]  Tracker Alignment: all in one Zmumu fixes `alca` `trk` created: 2023-06-09 11:44:09 merged: 2023-06-09 14:39:12

16. [41910](http://github.com/cms-sw/cmssw/pull/41910){:target="_blank"}  from **@makortel**: [13_0_X] Fix a race condition in StMeasurementDetSet `reconstruction` `tracking` created: 2023-06-09 11:03:04 merged: 2023-06-12 13:20:31

#### CMSDIST Changes between Tags REL/CMSSW_13_0_7_patch1/el8_amd64_gcc11 and REL/CMSSW_13_0_8/el8_amd64_gcc11:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_13_0_7_patch1/el8_amd64_gcc11...REL/CMSSW_13_0_8/el8_amd64_gcc11)



1. [8528](http://github.com/cms-sw/cmsdist/pull/8528){:target="_blank"}  from **@cms-sw**: [13_0_X] Update tag for Configuration-Generator to V01-06-00 created: 2023-05-30 09:52:49 merged: 2023-05-31 17:15:27
