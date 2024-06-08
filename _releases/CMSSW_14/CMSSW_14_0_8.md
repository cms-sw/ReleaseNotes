---
layout: post
rel_link:  "14_0_8"
title:  "CMSSW_14_0_8"
date:   2024-06-03 15:25:46
categories: cmssw
relmajor: 14
relminor: 0
relsubminor: 8
---

# CMSSW_14_0_8
#### Changes since CMSSW_14_0_7_patch2:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_0_7_patch2...CMSSW_14_0_8)



1. [45098](http://github.com/cms-sw/cmssw/pull/45098){:target="_blank"}  from **@smorovic**: fix lock contention in source (14_0_X backport) `daq` created: 2024-05-30 11:52:35 merged: 2024-06-03 15:17:53

2. [45061](http://github.com/cms-sw/cmssw/pull/45061){:target="_blank"}  from **@24LopezR**: [140X] Protection for invalid TSOS in MuonTrajectoryUpdator `reconstruction` `muon` created: 2024-05-27 18:27:34 merged: 2024-05-29 15:46:45

3. [45057](http://github.com/cms-sw/cmssw/pull/45057){:target="_blank"}  from **@mmusich**: [14.0.X] TkAlignment: Multi-IOV Zmumu mode, fixes to DMR averaged, PV trends `alca` `trk` created: 2024-05-27 14:34:48 merged: 2024-05-29 15:47:18

4. [45054](http://github.com/cms-sw/cmssw/pull/45054){:target="_blank"}  from **@perrotta**: Include per ROC histograms for Pixel Cluster Counting luminosity - CMSSW_14_0_X `alca` `reconstruction` created: 2024-05-27 12:28:16 merged: 2024-05-29 15:47:46

5. [45050](http://github.com/cms-sw/cmssw/pull/45050){:target="_blank"}  from **@mandrenguyen**: [14_0_X] Protect against invalid trajectory state on surface in STA muon reco `reconstruction` created: 2024-05-26 13:57:24 merged: 2024-05-27 22:22:04

6. [45048](http://github.com/cms-sw/cmssw/pull/45048){:target="_blank"}  from **@missirol**: guard against invalid output products from `HLTL1TSeed` [`14_0_X`] `hlt` created: 2024-05-26 10:18:48 merged: 2024-05-27 17:50:30

7. [45043](http://github.com/cms-sw/cmssw/pull/45043){:target="_blank"}  from **@mmusich**: [14.0.X] `PhotonXGBoostEstimator` : set `XGBoost` to use one thread to avoid spawning hundreds of OpenMP threads `reconstruction` `egamma` created: 2024-05-25 08:37:01 merged: 2024-05-27 17:51:08

8. [45027](http://github.com/cms-sw/cmssw/pull/45027){:target="_blank"}  from **@alaperto**: Disabled ROCs for Online DQM Pixel Summary (BP) `dqm` `trk` created: 2024-05-23 15:13:41 merged: 2024-05-27 22:20:53

9. [45022](http://github.com/cms-sw/cmssw/pull/45022){:target="_blank"}  from **@swagata87**: [14_0_X backport] Stop `dz` from being `NaN` in `PackedCandidates` `reconstruction` `xpog` `pf` created: 2024-05-23 12:24:23 merged: 2024-05-29 15:48:32

10. [45014](http://github.com/cms-sw/cmssw/pull/45014){:target="_blank"}  from **@CMSTrackerDPG**: [14.0.X] Computation of silicon strip hit efficiency : Consecutive missing hits recovery `alca` `trk` created: 2024-05-22 07:20:50 merged: 2024-05-28 12:52:13

11. [45007](http://github.com/cms-sw/cmssw/pull/45007){:target="_blank"}  from **@jfernan2**: [DT DQM] Fix some minor style bugs 14_0_X `dqm` created: 2024-05-21 11:38:02 merged: 2024-05-22 16:35:39

12. [45003](http://github.com/cms-sw/cmssw/pull/45003){:target="_blank"}  from **@aniketkhanal**: [14_0_X] Adding PNET scores to offline HLT DQM `dqm` created: 2024-05-20 21:32:44 merged: 2024-05-28 14:37:27

13. [45002](http://github.com/cms-sw/cmssw/pull/45002){:target="_blank"}  from **@mmusich**: [14.0.X] Improvements for Tracker Alignment `DiMuonValidation` `alca` `trk` created: 2024-05-20 17:09:55 merged: 2024-05-22 16:35:26

14. [44993](http://github.com/cms-sw/cmssw/pull/44993){:target="_blank"}  from **@phnattla**: [14.0.X] Adding PPS and ECALTiming Runs to HLT Menu veto of PCL alignment `alca` created: 2024-05-17 07:47:39 merged: 2024-05-22 15:40:37

15. [44990](http://github.com/cms-sw/cmssw/pull/44990){:target="_blank"}  from **@smorovic**: (DAQ) jsoncpp moved to a namespace (14_0_X backport) `daq` `hlt` created: 2024-05-16 17:29:44 merged: 2024-05-22 15:40:23

16. [44980](http://github.com/cms-sw/cmssw/pull/44980){:target="_blank"}  from **@smorovic**: (DAQ) fix input source cv notification [14_0_X] `daq` created: 2024-05-15 15:28:31 merged: 2024-05-22 15:40:08

17. [44920](http://github.com/cms-sw/cmssw/pull/44920){:target="_blank"}  from **@mbluj**: OMTF emulator corresponding to the 2024 OMTF firmware [14_0_X] `l1` created: 2024-05-07 13:51:49 merged: 2024-05-22 15:39:37

#### CMSDIST Changes between Tags REL/CMSSW_14_0_7_patch2/el8_amd64_gcc12 and REL/CMSSW_14_0_8/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_0_7_patch2/el8_amd64_gcc12...REL/CMSSW_14_0_8/el8_amd64_gcc12)



1. [9212](http://github.com/cms-sw/cmsdist/pull/9212){:target="_blank"}  from **@mmusich**: [14.0.X] Update tag for RecoMuon-TrackerSeedGenerator to V00-07-00 created: 2024-05-28 17:41:15 merged: 2024-05-30 12:50:27

2. [9177](http://github.com/cms-sw/cmsdist/pull/9177){:target="_blank"}  from **@mbluj**: Update L1Trigger-L1TMuon to V01-10-00 created: 2024-05-08 12:57:41 merged: 2024-05-22 15:39:21
