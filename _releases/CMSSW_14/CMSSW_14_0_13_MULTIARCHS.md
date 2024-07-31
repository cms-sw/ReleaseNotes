---
layout: post
rel_link:  "14_0_13_MULTIARCHS"
title:  "CMSSW_14_0_13_MULTIARCHS"
date:   2024-07-30 22:36:51
categories: cmssw
relmajor: 14
relminor: 0
relsubminor: 13
---

# CMSSW_14_0_13_MULTIARCHS
#### Changes since CMSSW_14_0_12_MULTIARCHS:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_0_12_MULTIARCHS...CMSSW_14_0_13_MULTIARCHS)



1. [45586](http://github.com/cms-sw/cmssw/pull/45586){:target="_blank"}  from **@mmusich**: [14.0.X] remove `SiPixelCompare*SoAAlpaka` templates and update `customizeHLTforAlpaka` to use the new modules `dqm` `hlt` `trk` created: 2024-07-30 07:15:00 merged: 2024-07-30 22:11:52

2. [45569](http://github.com/cms-sw/cmssw/pull/45569){:target="_blank"}  from **@swagata87**: [14_0_X] Reject badly measured tracks with very high values of `qoverpError` before trying to reconstruct displaced vertices `reconstruction` `pf` created: 2024-07-27 13:06:34 merged: 2024-07-30 22:04:18

3. [45562](http://github.com/cms-sw/cmssw/pull/45562){:target="_blank"}  from **@makortel**: [14_0_X] Mark `ScopedContextAcquire` destructor as `noexcept(false)` `heterogeneous` created: 2024-07-25 21:30:12 merged: 2024-07-29 21:55:36

4. [45559](http://github.com/cms-sw/cmssw/pull/45559){:target="_blank"}  from **@missirol**: update `hcalgpu` online-DQM client (post HCAL-Alpaka port at HLT) [`14_0_X`] `dqm` created: 2024-07-25 15:26:09 merged: 2024-07-29 21:53:51

5. [45549](http://github.com/cms-sw/cmssw/pull/45549){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_0_X` (9/N) `hlt` created: 2024-07-24 15:29:15 merged: 2024-07-29 10:40:41

6. [45541](http://github.com/cms-sw/cmssw/pull/45541){:target="_blank"}  from **@Dongwoon77**: [14_0_X] Adding GEM onlineDQM trigger primitive plots `dqm` created: 2024-07-24 09:53:37 merged: 2024-07-29 21:52:03

7. [45526](http://github.com/cms-sw/cmssw/pull/45526){:target="_blank"}  from **@Sam-Harper**: Use uncorrected H/E for electron energy regressions: 140X `reconstruction` `egamma` created: 2024-07-22 14:54:19 merged: 2024-07-23 15:16:32

8. [45494](http://github.com/cms-sw/cmssw/pull/45494){:target="_blank"}  from **@smuzaffar**: [14.0.X][DQM] Fix Warning: move the unused code in the comment where it is needed `dqm` created: 2024-07-18 12:23:39 merged: 2024-07-22 18:21:07

9. [45472](http://github.com/cms-sw/cmssw/pull/45472){:target="_blank"}  from **@fwyzard**: Fix pixel CPE position [14.0.x] `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-07-16 12:53:49 merged: 2024-07-17 13:04:05

10. [45461](http://github.com/cms-sw/cmssw/pull/45461){:target="_blank"}  from **@aloeliger**: [14_0] Add 2024 L1T modifier & modifiers for changing BMTF quality calculation `l1` `operations` created: 2024-07-15 13:56:45 merged: 2024-07-16 14:43:23

11. [45453](http://github.com/cms-sw/cmssw/pull/45453){:target="_blank"}  from **@missirol**: fix check on `shrEnergyM0TotalAccum` in HCAL-Alpaka kernel [`14_0_X`] `reconstruction` `heterogeneous` created: 2024-07-15 09:41:34 merged: 2024-07-17 13:04:11

12. [45451](http://github.com/cms-sw/cmssw/pull/45451){:target="_blank"}  from **@Mmiglio**: [14_0_X] L1 Scouting Online Selection modules `daq` `l1` created: 2024-07-15 08:36:16 merged: 2024-07-23 15:16:13

13. [45431](http://github.com/cms-sw/cmssw/pull/45431){:target="_blank"}  from **@makortel**: [14_0_X] Avoid releasing WaitingTask too early in case of exception in WaitingThreadPool `core` created: 2024-07-11 14:32:52 merged: 2024-07-23 15:16:43

14. [45430](http://github.com/cms-sw/cmssw/pull/45430){:target="_blank"}  from **@abhih1**: Change thresholds on LED and FEStatus Quality plots ECAL DQM [14_0_X] `dqm` created: 2024-07-11 14:21:18 merged: 2024-07-15 14:24:52

15. [45417](http://github.com/cms-sw/cmssw/pull/45417){:target="_blank"}  from **@stahlleiton**: [14_0_X] Update HLTPixelTrackFilter to store candidates `hlt` created: 2024-07-09 21:52:22 merged: 2024-07-11 14:26:48

16. [45396](http://github.com/cms-sw/cmssw/pull/45396){:target="_blank"}  from **@namapane**: [14.0.X] Add a protection for pathologic cases in MuonBeamspotConstraintValueMapProducer `reconstruction` created: 2024-07-08 08:03:11 merged: 2024-07-08 22:19:43

17. [45394](http://github.com/cms-sw/cmssw/pull/45394){:target="_blank"}  from **@kandrosov**: [14_0_X] Catch VertexException in PATLeptonTimeLifeInfoProducer when fitVertex fails `reconstruction` `xpog` created: 2024-07-06 20:22:38 merged: 2024-07-09 14:25:11

18. [45391](http://github.com/cms-sw/cmssw/pull/45391){:target="_blank"}  from **@perrotta**: Update GTs and modifiers for L1T 2024 menu L1Menu_Collisions2024_v1_3_0_xml [14_0_X] `alca` created: 2024-07-05 15:07:12 merged: 2024-07-11 14:26:05

19. [45388](http://github.com/cms-sw/cmssw/pull/45388){:target="_blank"}  from **@jking79**: Backport to 14_0_X of PR#45386 "Updated EcalUncalibRecHitTimingCCAlgo to correct for bias at high energies" `reconstruction` `ecal` created: 2024-07-05 14:05:53 merged: 2024-07-10 12:32:18

20. [45380](http://github.com/cms-sw/cmssw/pull/45380){:target="_blank"}  from **@fwyzard**: Update the GPU alpaka workflows [14.0.x] `pdmv` `upgrade` created: 2024-07-04 18:26:52 merged: 2024-07-11 14:25:52

21. [45374](http://github.com/cms-sw/cmssw/pull/45374){:target="_blank"}  from **@fwyzard**: Fix CachingAllocator debug for non-async operations [14.0.x] `pdmv` `upgrade` `heterogeneous` created: 2024-07-04 13:41:42 merged: 2024-07-11 14:25:27

22. [45128](http://github.com/cms-sw/cmssw/pull/45128){:target="_blank"}  from **@ThOliveira23**: [14_0_X] Monopole SKIM updates for Run 3 `pdmv` created: 2024-06-04 08:16:11 merged: 2024-07-09 14:22:11

#### CMSDIST Changes between Tags REL/CMSSW_14_0_12_MULTIARCHS/el8_amd64_gcc12 and REL/CMSSW_14_0_13_MULTIARCHS/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_0_12_MULTIARCHS/el8_amd64_gcc12...REL/CMSSW_14_0_13_MULTIARCHS/el8_amd64_gcc12)


