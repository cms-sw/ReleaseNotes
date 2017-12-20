---
layout: post
rel_link:  "9_2_14"
title:  "CMSSW_9_2_14"
date:   2017-10-28 07:27:54
categories: cmssw
relmajor: 9
relminor: 2
relsubminor: 14
---

# CMSSW_9_2_14
#### Changes since CMSSW_9_2_13:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_9_2_13...CMSSW_9_2_14)



1. [21056](http://github.com/cms-sw/cmssw/pull/21056){:target="_blank"}  from **@arunhep**: Prompt-like GT updated with revert of AlCaReco trigger bits to Fix wf 2016H `alca`  created: 2017-10-27 23:44:35 merged: 2017-10-28 07:18:42

2. [21019](http://github.com/cms-sw/cmssw/pull/21019){:target="_blank"}  from **@ahinzmann**: Protect against missing track info in MiniAOD `reconstruction`  created: 2017-10-25 16:49:05 merged: 2017-10-27 08:36:46

3. [21012](http://github.com/cms-sw/cmssw/pull/21012){:target="_blank"}  from **@bsunanda**: Run2-sim18 Do the bug fix for ECal shower profile correction to 9_2_X (back porting from 9_4_X) `simulation`  created: 2017-10-24 18:11:15 merged: 2017-10-27 11:23:14

4. [21008](http://github.com/cms-sw/cmssw/pull/21008){:target="_blank"}  from **@hroskes**: include firstRun and lastRun in the run range include firstRun and lastRun in the run range for TkAlAlllInOne tool `alca`  created: 2017-10-24 14:02:48 merged: 2017-10-27 08:36:35

5. [20984](http://github.com/cms-sw/cmssw/pull/20984){:target="_blank"}  from **@lpernie**: GT Updates: 92X offline, relval, promptLike, and HLT_frozen GT updated to make the release self-consistent with the data taken with it  `alca`  `pdmv`  `upgrade`  created: 2017-10-20 20:47:49 merged: 2017-10-27 08:41:49

6. [20978](http://github.com/cms-sw/cmssw/pull/20978){:target="_blank"}  from **@fioriNTU**: Adding the correct era mechanism to Strip client `dqm`  created: 2017-10-20 10:28:54 merged: 2017-10-25 08:39:33

7. [20974](http://github.com/cms-sw/cmssw/pull/20974){:target="_blank"}  from **@cippy**: saving the collections of ECAL selective readout flags (SrFlags) matc `hlt`  created: 2017-10-19 18:20:54 merged: 2017-10-27 08:37:14

8. [20971](http://github.com/cms-sw/cmssw/pull/20971){:target="_blank"}  from **@mtosi**: fix binning in muon->innerTrack DQM [backport #20970] `dqm`  created: 2017-10-19 10:58:10 merged: 2017-10-27 08:37:34

9. [20959](http://github.com/cms-sw/cmssw/pull/20959){:target="_blank"}  from **@hroskes**: Fix compiling PlotAlignmentValidation `alca`  created: 2017-10-18 13:21:40 merged: 2017-10-25 08:23:12

10. [20945](http://github.com/cms-sw/cmssw/pull/20945){:target="_blank"}  from **@thomreis**: L1T RegionalMuonCand constructor upgrade - 92x `l1`  created: 2017-10-17 14:42:55 merged: 2017-10-25 08:23:47

11. [20927](http://github.com/cms-sw/cmssw/pull/20927){:target="_blank"}  from **@thomreis**: L1T online DQM uGMT zero suppression plot axis range change - 92x `dqm`  created: 2017-10-16 11:11:54 merged: 2017-10-25 08:24:42

12. [20924](http://github.com/cms-sw/cmssw/pull/20924){:target="_blank"}  from **@thomreis**: L1TOffline DQM - add efficiency flag to efficiency ME - 92x `dqm`  `l1`  created: 2017-10-16 08:08:30 merged: 2017-10-25 08:24:56

13. [20873](http://github.com/cms-sw/cmssw/pull/20873){:target="_blank"}  from **@cms-tsg-storm**: HLT V4.0 Mercury (92X) `core`  `hlt`  created: 2017-10-10 09:23:15 merged: 2017-10-27 08:37:56

14. [20833](http://github.com/cms-sw/cmssw/pull/20833){:target="_blank"}  from **@stahlleiton**: [92X] OnlineDQM : Tune L1T Muon QTs v3 `dqm`  created: 2017-10-09 00:23:53 merged: 2017-10-27 11:23:54

15. [20770](http://github.com/cms-sw/cmssw/pull/20770){:target="_blank"}  from @mtosi: fix PV validation **@HLT** `dqm`  created: 2017-10-06 12:42:04 merged: 2017-10-27 08:45:24

16. [20695](http://github.com/cms-sw/cmssw/pull/20695){:target="_blank"}  from **@mtosi**: add PU vs LS `dqm`  `hlt`  created: 2017-09-28 16:36:02 merged: 2017-10-17 15:39:43

17. [20650](http://github.com/cms-sw/cmssw/pull/20650){:target="_blank"}  from **@astakia**: L1T Muon Offline DQM - Resolution plots & bug fixes - 92x `dqm`  `l1`  created: 2017-09-25 17:04:31 merged: 2017-10-27 08:38:39

18. [20620](http://github.com/cms-sw/cmssw/pull/20620){:target="_blank"}  from **@mtosi**: backport HLT DQM for menu v3.0 to CMSSW 9.2.x + HLTDQM : fix memory issue (part1) + add offlineHLTSourceOnAODextra sequence `dqm`  `operations`  `pdmv`  `upgrade`  created: 2017-09-21 21:32:52 merged: 2017-10-27 08:48:30

19. [20345](http://github.com/cms-sw/cmssw/pull/20345){:target="_blank"}  from **@npostiau**: Update smp validation paths (backport 9_2_X) `dqm`  created: 2017-09-01 13:36:04 merged: 2017-10-09 08:21:54

20. [20323](http://github.com/cms-sw/cmssw/pull/20323){:target="_blank"}  from **@mtosi**: add sequence for HLTDQM only step on AOD [backport of #20322] `dqm`  created: 2017-08-30 19:50:41 merged: 2017-10-17 15:39:02

21. [20314](http://github.com/cms-sw/cmssw/pull/20314){:target="_blank"}  from **@thomreis**: Add L1 offline DQM harvesting step - 92x `dqm`  created: 2017-08-30 09:30:43 merged: 2017-10-17 15:39:15

#### CMSDIST Changes between Tags REL/CMSSW_9_2_13/slc6_amd64_gcc530 and REL/CMSSW_9_2_14/slc6_amd64_gcc530:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_9_2_13/slc6_amd64_gcc530...REL/CMSSW_9_2_14/slc6_amd64_gcc530)



1. [3496](http://github.com/cms-sw/cmsdist/pull/3496){:target="_blank"}  from **@cms-sw**: Backport changes from 94 to 92 created: 2017-10-13 10:31:41 merged: 2017-10-13 14:21:24
