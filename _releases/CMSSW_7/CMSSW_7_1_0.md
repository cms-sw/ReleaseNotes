---
layout: post
rel_link:  "7_1_0"
title:  "CMSSW_7_1_0"
date:   2014-06-21 20:02:05
categories: cmssw
relmajor: 7
relminor: 1
relsubminor: 0
---

# CMSSW_7_1_0
#### Changes since CMSSW_7_1_0_pre9:

1. [4335](http://github.com/cms-sw/cmssw/pull/4335){:target="_blank"}  from **@ktf**: Revert classversion. `analysis`  created: 2014-06-21 13:17:43 merged: 2014-06-21 13:18:47

2. [4334](http://github.com/cms-sw/cmssw/pull/4334){:target="_blank"}  from **@ktf**: Fix cout. created: 2014-06-21 09:38:32 merged: 2014-06-21 09:39:10

3. [4316](http://github.com/cms-sw/cmssw/pull/4316){:target="_blank"}  from **@ktf**: Fix forward port 71x `analysis`  `core`  `operations`  `reconstruction`  `simulation`  created: 2014-06-19 15:53:25 merged: 2014-06-20 21:13:21

4. [4333](http://github.com/cms-sw/cmssw/pull/4333){:target="_blank"}  from **@civanch**: Fix hf sl sampling factor `simulation`  created: 2014-06-20 15:32:51 merged: 2014-06-20 15:48:01

5. [4305](http://github.com/cms-sw/cmssw/pull/4305){:target="_blank"}  from **@diguida**: GTs in autoCond for 710 `alca`  created: 2014-06-18 13:55:01 merged: 2014-06-20 12:07:33

6. [4327](http://github.com/cms-sw/cmssw/pull/4327){:target="_blank"}  from **@ktf**: Backport TLS fixes from #4293 to CMSSW_7_1_X `alca`  `db`  `reconstruction`  created: 2014-06-20 07:52:04 merged: 2014-06-20 09:52:16

7. [4302](http://github.com/cms-sw/cmssw/pull/4302){:target="_blank"}  from **@civanch**: Alternative EM physics for heavy exotics  `simulation`  created: 2014-06-18 10:42:44 merged: 2014-06-19 07:32:01

8. [4304](http://github.com/cms-sw/cmssw/pull/4304){:target="_blank"}  from **@deguio**: handle correctly the ME which are not TH1 [int,string,float] `dqm`  created: 2014-06-18 12:52:32 merged: 2014-06-19 07:27:11

9. [4160](http://github.com/cms-sw/cmssw/pull/4160){:target="_blank"}  from **@Dr15Jones**: removed unnecessary mutables from CondFormats/L1TObjects `alca`  `db`  `l1`  created: 2014-06-07 22:24:17 merged: 2014-06-18 16:27:38

10. [4264](http://github.com/cms-sw/cmssw/pull/4264){:target="_blank"}  from **@cms-l1t-offline**: L1t global bugfixes for 7 1 x `alca`  `db`  `l1`  created: 2014-06-16 09:04:15 merged: 2014-06-18 12:45:46

11. [4221](http://github.com/cms-sw/cmssw/pull/4221){:target="_blank"}  from **@jpavel**: removed duplicated definitions of EDProducers (for 71x) `reconstruction`  created: 2014-06-12 13:57:32 merged: 2014-06-18 06:36:44

12. [4245](http://github.com/cms-sw/cmssw/pull/4245){:target="_blank"}  from **@srimanob**: Fast sim for mixing71 x fix1 `fastsim`  `operations`  created: 2014-06-14 14:41:04 merged: 2014-06-17 16:50:15

13. [4266](http://github.com/cms-sw/cmssw/pull/4266){:target="_blank"}  from **@cms-l1t-offline**: L1t calorimeter bugfixes for 7 1 x created: 2014-06-16 10:18:02 merged: 2014-06-17 16:49:41

14. [4288](http://github.com/cms-sw/cmssw/pull/4288){:target="_blank"}  from **@civanch**: Fix for inf loop neutron bgr sim `simulation`  created: 2014-06-17 10:27:43 merged: 2014-06-17 16:48:41

15. [4280](http://github.com/cms-sw/cmssw/pull/4280){:target="_blank"}  from **@mileva**: Unused maps and lines removed from RPCDidisValid `dqm`  created: 2014-06-16 20:14:31 merged: 2014-06-17 16:48:29

16. [4272](http://github.com/cms-sw/cmssw/pull/4272){:target="_blank"}  from **@mgalanti**: Bugfix: assign correct FED IDs if some FEDs are not in the DAQ `dqm`  created: 2014-06-16 15:28:46 merged: 2014-06-17 16:48:16

17. [4270](http://github.com/cms-sw/cmssw/pull/4270){:target="_blank"}  from **@civanch**: New hf sl 2011 2012 `simulation`  created: 2014-06-16 13:13:29 merged: 2014-06-17 16:47:59

18. [4268](http://github.com/cms-sw/cmssw/pull/4268){:target="_blank"}  from **@mommsen**: Add new FED IDs for future uTCA FEDs `daq`  created: 2014-06-16 11:25:11 merged: 2014-06-17 16:47:20

19. [4224](http://github.com/cms-sw/cmssw/pull/4224){:target="_blank"}  from **@sarafiorendi**: Split old mmtkfilter in a vertex producer and a filter `hlt`  created: 2014-06-12 17:09:27 merged: 2014-06-17 16:47:04

20. [4254](http://github.com/cms-sw/cmssw/pull/4254){:target="_blank"}  from **@davidlange6**: Remove hoarding of sim tracks `dqm`  `generators`  `reconstruction`  created: 2014-06-15 18:53:22 merged: 2014-06-16 17:11:09

21. [4263](http://github.com/cms-sw/cmssw/pull/4263){:target="_blank"}  from **@battibass**: Trivial Fix for VertexFromTrackProducer `hlt`  created: 2014-06-16 08:43:05 merged: 2014-06-16 11:42:25

22. [4257](http://github.com/cms-sw/cmssw/pull/4257){:target="_blank"}  from **@fwyzard**: FastTimerService: avoid race condition across different threads when updating summary information `hlt`  created: 2014-06-15 21:11:48 merged: 2014-06-16 11:41:55

23. [4223](http://github.com/cms-sw/cmssw/pull/4223){:target="_blank"}  from **@Dr15Jones**: Removed depricated KfComponentsHolder::setup function `alca`  `reconstruction`  created: 2014-06-12 15:13:23 merged: 2014-06-16 11:41:15

24. [4261](http://github.com/cms-sw/cmssw/pull/4261){:target="_blank"}  from **@ktf**: Make sure files are at CERN also when specifying multiple runs. `operations`  created: 2014-06-16 07:57:19 merged: 2014-06-16 08:16:10

25. [4244](http://github.com/cms-sw/cmssw/pull/4244){:target="_blank"}  from **@alja**: cmsShow script: fix warning about missing version.txt `visualization`  created: 2014-06-14 14:27:49 merged: 2014-06-16 06:12:48

26. [4209](http://github.com/cms-sw/cmssw/pull/4209){:target="_blank"}  from **@lgray**: demote message status of gap-region linking bug `reconstruction`  created: 2014-06-11 12:58:25 merged: 2014-06-15 14:30:14

27. [4233](http://github.com/cms-sw/cmssw/pull/4233){:target="_blank"}  from **@mbluj**: Bug fix to an "OR" logic in tau discrimination `reconstruction`  created: 2014-06-13 11:49:40 merged: 2014-06-15 14:29:22

28. [4226](http://github.com/cms-sw/cmssw/pull/4226){:target="_blank"}  from **@ericvaandering**: 71x improve lumilist `core`  created: 2014-06-12 21:05:33 merged: 2014-06-15 14:28:45

29. [4216](http://github.com/cms-sw/cmssw/pull/4216){:target="_blank"}  from **@ahinzmann**: Make the magnetic field record for the PixelCPEGeneric configurable `reconstruction`  created: 2014-06-12 08:31:05 merged: 2014-06-15 14:27:56

30. [4210](http://github.com/cms-sw/cmssw/pull/4210){:target="_blank"}  from **@smorovic**: EvF updates `daq`  `dqm`  created: 2014-06-11 15:28:20 merged: 2014-06-15 14:27:05

31. [4207](http://github.com/cms-sw/cmssw/pull/4207){:target="_blank"}  from **@nclopezo**: Forward port CMSSW_7_0_X into CMSSW_7_1_X (Fixed Conflicts) `operations`  created: 2014-06-11 11:55:37 merged: 2014-06-15 14:25:46

32. [4197](http://github.com/cms-sw/cmssw/pull/4197){:target="_blank"}  from **@giamman**: New fastsim event content for pileup `fastsim`  created: 2014-06-10 19:43:15 merged: 2014-06-15 14:24:53

33. [4179](http://github.com/cms-sw/cmssw/pull/4179){:target="_blank"}  from **@VinInn**: Global muon refitter and TrackTransformer `reconstruction`  created: 2014-06-10 10:10:47 merged: 2014-06-15 14:23:34

34. [4140](http://github.com/cms-sw/cmssw/pull/4140){:target="_blank"}  from **@cms-btv-pog**: remove unused variable `reconstruction`  created: 2014-06-06 10:07:39 merged: 2014-06-15 14:23:14

35. [3991](http://github.com/cms-sw/cmssw/pull/3991){:target="_blank"}  from **@Dr15Jones**: Make GctRawToDigi thread safe `l1`  created: 2014-05-23 16:11:11 merged: 2014-06-15 14:22:18

36. [4198](http://github.com/cms-sw/cmssw/pull/4198){:target="_blank"}  from **@wmtan**: Avoid thread locals. `core`  created: 2014-06-10 19:55:36 merged: 2014-06-11 09:19:19

37. [4177](http://github.com/cms-sw/cmssw/pull/4177){:target="_blank"}  from **@Martin-Grunewald**: 710pre9 hlt `hlt`  created: 2014-06-10 07:48:10 merged: 2014-06-10 15:46:15

38. [4167](http://github.com/cms-sw/cmssw/pull/4167){:target="_blank"}  from **@Dr15Jones**: Make HcalDDDGeometry thread-safe `geometry`  created: 2014-06-09 20:56:27 merged: 2014-06-10 15:45:04

39. [4163](http://github.com/cms-sw/cmssw/pull/4163){:target="_blank"}  from **@civanch**: T rugg ribbon `geometry`  created: 2014-06-09 16:12:03 merged: 2014-06-10 15:44:45

40. [4138](http://github.com/cms-sw/cmssw/pull/4138){:target="_blank"}  from **@perrotta**: allow using the developing HLT menu for run2 in CMSSW_7_1_X `fastsim`  `hlt`  created: 2014-06-06 09:03:15 merged: 2014-06-10 15:43:59

41. [4109](http://github.com/cms-sw/cmssw/pull/4109){:target="_blank"}  from **@fwyzard**: hltGetConfiguration cleanup `hlt`  created: 2014-06-04 15:12:13 merged: 2014-06-10 15:42:50

42. [4116](http://github.com/cms-sw/cmssw/pull/4116){:target="_blank"}  from **@ktf**: Add missing header. `analysis`  created: 2014-06-05 06:18:44 merged: 2014-06-09 17:59:04
