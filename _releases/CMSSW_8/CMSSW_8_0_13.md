---
layout: post
rel_link:  "8_0_13"
title:  "CMSSW_8_0_13"
date:   2016-06-28 20:59:17
categories: cmssw
relmajor: 8
relminor: 0
relsubminor: 13
---

# CMSSW_8_0_13
#### Changes since CMSSW_8_0_12:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_0_12...CMSSW_8_0_13)



1. [15012](http://github.com/cms-sw/cmssw/pull/15012){:target="_blank"}  from **@fwyzard**:  hltDiff: fix comparison of trigger candidates with different process name `hlt`  created: 2016-06-28 09:59:16 merged: 2016-06-28 17:15:44

2. [14991](http://github.com/cms-sw/cmssw/pull/14991){:target="_blank"}  from **@cms-l1t-offline**: Fix double loop causing sporadic ghost when seeding cross-object trig `hlt`  created: 2016-06-27 12:34:06 merged: 2016-06-28 17:15:19

3. [14987](http://github.com/cms-sw/cmssw/pull/14987){:target="_blank"}  from **@silviodonato**: Fixes in HLT BTV release validation DQM [backport of #14986] `dqm`  created: 2016-06-27 07:51:20 merged: 2016-06-28 17:15:11

4. [14978](http://github.com/cms-sw/cmssw/pull/14978){:target="_blank"}  from **@mbandrews**: Protect against negative occupancy thresholds `dqm`  created: 2016-06-25 10:09:54 merged: 2016-06-28 17:14:13

5. [14972](http://github.com/cms-sw/cmssw/pull/14972){:target="_blank"}  from **@Martin-Grunewald**: Fix HLTL1TSeed accounting for prescale handling (80X) `hlt`  created: 2016-06-24 09:28:56 merged: 2016-06-28 17:12:57

6. [14968](http://github.com/cms-sw/cmssw/pull/14968){:target="_blank"}  from **@slava77**:  check if updated TSOS is good in DYT to avoid a crash (backport of #14967 ) `reconstruction`  created: 2016-06-23 23:37:29 merged: 2016-06-24 08:13:49

7. [14956](http://github.com/cms-sw/cmssw/pull/14956){:target="_blank"}  from **@slava77**:  double the reserve for on-demand strip cluster from raw (backport of #14953 ) `reconstruction`  created: 2016-06-23 05:58:16 merged: 2016-06-24 08:14:14

8. [14955](http://github.com/cms-sw/cmssw/pull/14955){:target="_blank"}  from **@dan131riley**: Fix array bounds overrun in DetectPatterns(), 80x version `l1`  created: 2016-06-22 19:21:43 merged: 2016-06-24 08:14:09

9. [14949](http://github.com/cms-sw/cmssw/pull/14949){:target="_blank"}  from **@mmusich**: Fix the record-tag mapping for the AAG harvesting `alca`  created: 2016-06-22 11:56:37 merged: 2016-06-24 15:11:50

10. [14946](http://github.com/cms-sw/cmssw/pull/14946){:target="_blank"}  from **@diguida**: Update the fall-back Express GT for Event Display after the Era change in Tier0 `dqm`  created: 2016-06-22 10:55:30 merged: 2016-06-24 08:14:36

11. [14943](http://github.com/cms-sw/cmssw/pull/14943){:target="_blank"}  from **@VinInn**: protect tsos `reconstruction`  created: 2016-06-22 07:28:03 merged: 2016-06-24 08:14:47

12. [14936](http://github.com/cms-sw/cmssw/pull/14936){:target="_blank"}  from **@mbandrews**: Add noise correlation+difference plots `dqm`  created: 2016-06-21 16:16:55 merged: 2016-06-24 09:49:57

13. [14935](http://github.com/cms-sw/cmssw/pull/14935){:target="_blank"}  from **@dinardo**: Changed fit function for vtx and pixel hits distributions from exp to linear + changed LS window `dqm`  created: 2016-06-21 13:39:10 merged: 2016-06-28 20:58:37

14. [14912](http://github.com/cms-sw/cmssw/pull/14912){:target="_blank"}  from **@fabozzi**: relval matrix update in 80X `pdmv`  created: 2016-06-16 23:22:57 merged: 2016-06-24 09:36:35

15. [14903](http://github.com/cms-sw/cmssw/pull/14903){:target="_blank"}  from **@Sam-Harper**: Allowing HLT to be seeded by Taus `hlt`  created: 2016-06-16 11:55:19 merged: 2016-06-20 07:50:30

16. [14886](http://github.com/cms-sw/cmssw/pull/14886){:target="_blank"}  from **@Soureek89**: Updating Trigger Path and Fixing for Empty Histograms for single lept `dqm`  created: 2016-06-15 02:15:11 merged: 2016-06-24 08:18:34

17. [14876](http://github.com/cms-sw/cmssw/pull/14876){:target="_blank"}  from **@ghellwig**: Fix clang warnings alignment 80X (Backport of #14875) `alca`  created: 2016-06-14 13:55:29 merged: 2016-06-28 17:12:52

18. [14866](http://github.com/cms-sw/cmssw/pull/14866){:target="_blank"}  from **@alja**: 80x Fireworks:Fix drawing of 4th ME station in 3D view `comparison`  `visualization`  created: 2016-06-13 20:46:35 merged: 2016-06-24 15:15:38

19. [14846](http://github.com/cms-sw/cmssw/pull/14846){:target="_blank"}  from **@arizzi**: add a nan protection to avoid crash in fastjet call from pvsorter `reconstruction`  created: 2016-06-11 06:24:28 merged: 2016-06-24 15:10:15

20. [14765](http://github.com/cms-sw/cmssw/pull/14765){:target="_blank"}  from **@sarafiorendi**: add DQM monitoring for HLT_L1SingleMu18 `dqm`  created: 2016-06-03 16:51:56 merged: 2016-06-24 09:52:04

21. [14752](http://github.com/cms-sw/cmssw/pull/14752){:target="_blank"}  from **@olivito**: SUSY HLT DQM path and filter name fixes for various paths, 80X `dqm`  created: 2016-06-02 13:47:00 merged: 2016-06-24 08:18:46

22. [14745](http://github.com/cms-sw/cmssw/pull/14745){:target="_blank"}  from **@slava77**: remove unnecessary cloning of  particleFlowDisplacedVertex and pfCandidateToVertexAssociation in met corrections  (backport of #14744) `analysis`  `reconstruction`  created: 2016-06-02 01:16:09 merged: 2016-06-24 15:14:23

23. [14727](http://github.com/cms-sw/cmssw/pull/14727){:target="_blank"}  from **@mandrenguyen**: HiGenCommon consumes migration and GenHIEventProducer forward port from 75X `generators`  created: 2016-06-01 10:49:44 merged: 2016-06-28 17:13:11

24. [14696](http://github.com/cms-sw/cmssw/pull/14696){:target="_blank"}  from **@CTPPS**: CTPPS: DQM for TOTEM RP - backport of #14034 `dqm`  created: 2016-05-31 07:33:28 merged: 2016-06-20 07:53:08

25. [14637](http://github.com/cms-sw/cmssw/pull/14637){:target="_blank"}  from **@jasperlauwers**: 80X HLTriggerOffline/Higgs - MuMu SameSign paths without DZ `dqm`  created: 2016-05-25 15:25:49 merged: 2016-06-24 08:18:59

26. [13888](http://github.com/cms-sw/cmssw/pull/13888){:target="_blank"}  from **@suchandradutta**:  Bad channel from FED error `alca`  created: 2016-04-01 19:19:31 merged: 2016-06-28 17:13:36

#### CMSDIST Changes between Tags REL/CMSSW_8_0_12/slc6_amd64_gcc530 and REL/CMSSW_8_0_13/slc6_amd64_gcc530:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_0_12/slc6_amd64_gcc530...REL/CMSSW_8_0_13/slc6_amd64_gcc530)


