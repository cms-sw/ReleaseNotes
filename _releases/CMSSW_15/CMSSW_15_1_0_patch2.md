---
layout: post
rel_link:  "15_1_0_patch2"
title:  "CMSSW_15_1_0_patch2"
date:   2025-10-29 12:17:45
categories: cmssw
relmajor: 15
relminor: 1
relsubminor: 0
relpatch: _patch2
---

# CMSSW_15_1_0_patch2
#### Changes since CMSSW_15_1_0_patch1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_15_1_0_patch1...CMSSW_15_1_0_patch2)



1. [49225](http://github.com/cms-sw/cmssw/pull/49225){:target="_blank"}  from **@stahlleiton**: [15_1_X] Reduce size of dEdx estimators in PbPb MiniAOD `reconstruction` `xpog` created: 2025-10-27 16:43:30 merged: 2025-10-28 20:41:16

2. [49223](http://github.com/cms-sw/cmssw/pull/49223){:target="_blank"}  from **@perrotta**: [CMSSW_15_1_X] Replace the GT for Run2 data re-reco in autoCond with a 150X clone of previous 141X_dataRun2_v3 `alca` created: 2025-10-27 14:22:57 merged: 2025-10-28 16:17:11

3. [49210](http://github.com/cms-sw/cmssw/pull/49210){:target="_blank"}  from **@srimanob**: [Backport 15_1] Remove miniAOD_customizeOutput, and define miniaod file parameter directly in EventContent `operations` created: 2025-10-24 14:29:23 merged: 2025-10-28 16:24:48

4. [49201](http://github.com/cms-sw/cmssw/pull/49201){:target="_blank"}  from **@AdrianoDee**: Fix Hit and Track SoA Writing to File [15_1_X] `reconstruction` `heterogeneous` `tracking` created: 2025-10-22 16:15:42 merged: 2025-10-25 14:36:15

5. [49184](http://github.com/cms-sw/cmssw/pull/49184){:target="_blank"}  from **@stahlleiton**: [15_1_X] Undo change in PF electron_ecalDrivenHademPreselCut in PbPb era `reconstruction` created: 2025-10-17 22:51:51 merged: 2025-10-23 08:49:05

6. [49171](http://github.com/cms-sw/cmssw/pull/49171){:target="_blank"}  from **@patinkaew**: [15_1_X] Update skipEventsWithoutScoutingByEra for ScoutingNano (backport of #49084) `operations` `pdmv` `xpog` created: 2025-10-15 19:29:58 merged: 2025-10-27 11:49:54

7. [49149](http://github.com/cms-sw/cmssw/pull/49149){:target="_blank"}  from **@AdrianoDee**: Fix for `startingPairs` for Pixel Tracks CA [15_1_X] `hlt` `reconstruction` `heterogeneous` `tracking` created: 2025-10-13 15:44:05 merged: 2025-10-16 11:20:33

8. [49143](http://github.com/cms-sw/cmssw/pull/49143){:target="_blank"}  from **@fwyzard**: Clamp `fakePixels` to `maxFakesInModule` [15.1.x] `reconstruction` `trk` created: 2025-10-13 07:43:23 merged: 2025-10-14 18:01:13

9. [49138](http://github.com/cms-sw/cmssw/pull/49138){:target="_blank"}  from **@nurfikri89**: [NanoAOD] Backport of #49137 (Fix puppi weight in PFCand table for reNanoV15) to 151X `xpog` created: 2025-10-11 18:46:51 merged: 2025-10-15 19:48:56

10. [49131](http://github.com/cms-sw/cmssw/pull/49131){:target="_blank"}  from **@cms-ngt-hlt**: Additions to scouting DQM with the ScoutingCollectionMonitor and a new ScoutingMuonPropertiesAnalyzer [15_1_X] `dqm` `hlt` created: 2025-10-10 15:34:28 merged: 2025-10-16 11:23:38

11. [49127](http://github.com/cms-sw/cmssw/pull/49127){:target="_blank"}  from **@CMSTrackerDPG**: [15_1_X]  Fix digi morphing (offline) out-of-bounds access `reconstruction` `trk` created: 2025-10-10 12:49:47 merged: 2025-10-14 09:02:41

12. [49117](http://github.com/cms-sw/cmssw/pull/49117){:target="_blank"}  from **@jprendi**: Changing https to http for CMS network in the uploadConditions script [15_1_X] `db` created: 2025-10-09 14:50:39 merged: 2025-10-14 18:02:03

13. [49100](http://github.com/cms-sw/cmssw/pull/49100){:target="_blank"}  from **@smorovic**: [DAQ] SFB mode detection of run end flag (15_1_X backport) `daq` created: 2025-10-08 11:12:58 merged: 2025-10-09 05:31:00

14. [49097](http://github.com/cms-sw/cmssw/pull/49097){:target="_blank"}  from **@cms-AlCaDB**: 15_1 Allow defining valid range of Energy values for LHCInfoPerFill O2O + Review  `db` created: 2025-10-08 10:13:27 merged: 2025-10-14 15:11:37

15. [49092](http://github.com/cms-sw/cmssw/pull/49092){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `15_1_X` (1/N) `hlt` created: 2025-10-08 07:56:47 merged: 2025-10-09 07:53:51

16. [49077](http://github.com/cms-sw/cmssw/pull/49077){:target="_blank"}  from **@jprendi**: Fixing EcalPedestal plots for CondDB [15_1_X] `db` created: 2025-10-07 07:50:49 merged: 2025-10-14 15:12:29

17. [49071](http://github.com/cms-sw/cmssw/pull/49071){:target="_blank"}  from **@makortel**: [15_1_X] Use the right TTreeCache in `RootTree::getEntryForAllBranches()` for prompt reading `core` created: 2025-10-06 13:31:06 merged: 2025-10-14 15:09:06

18. [49039](http://github.com/cms-sw/cmssw/pull/49039){:target="_blank"}  from **@KIT-CMS**: [15_1_X]  Backport tau embedding changes for 2025production `operations` `reconstruction` `simulation` `pdmv` `upgrade` `xpog` `tracking` `trk` created: 2025-10-01 13:43:37 merged: 2025-10-24 07:26:03

#### CMSDIST Changes between Tags REL/CMSSW_15_1_0_patch1/el8_amd64_gcc12 and REL/CMSSW_15_1_0_patch2/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_15_1_0_patch1/el8_amd64_gcc12...REL/CMSSW_15_1_0_patch2/el8_amd64_gcc12)


