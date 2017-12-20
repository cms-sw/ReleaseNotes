---
layout: post
rel_link:  "7_0_0_pre12"
title:  "CMSSW_7_0_0_pre12"
date:   2014-01-20 15:25:15
categories: cmssw
relmajor: 7
relminor: 0
relsubminor: 0
relpre: _pre12
---

# CMSSW_7_0_0_pre12
#### Changes since CMSSW_7_0_0_pre11:

1. [2055](http://github.com/cms-sw/cmssw/pull/2055){:target="_blank"}  from **@ggovi**: DB fixes -- CondDB KeyList adapted to avoid dependency on the target CondFormat. `db`  created: 2014-01-17 09:59:33 merged: 2014-01-20 10:45:37

2. [2080](http://github.com/cms-sw/cmssw/pull/2080){:target="_blank"}  from **@davidlange6**: Misc fix -- reduce buffer size for FEVTHLTDEBUG output given the 2000++ branches tha... `operations`  created: 2014-01-20 10:39:02 merged: 2014-01-20 10:41:06

3. [1910](http://github.com/cms-sw/cmssw/pull/1910){:target="_blank"}  from **@jpavel**: Reco fixes -- 70x tau id trigger default config `reconstruction`  created: 2013-12-20 12:52:57 merged: 2014-01-20 10:37:44

4. [2044](http://github.com/cms-sw/cmssw/pull/2044){:target="_blank"}  from **@lgray**: Reco fixes -- Fixes to Cluster Shape Variables monitored in EXO DQM + #1986 Code Review  `reconstruction`  created: 2014-01-16 13:17:27 merged: 2014-01-17 13:26:20

5. [2047](http://github.com/cms-sw/cmssw/pull/2047){:target="_blank"}  from **@wddgit**: Sim fixes -- Bug fix. This bug will break the DataMixingModule completely. `simulation`  created: 2014-01-16 16:31:19 merged: 2014-01-17 11:22:39

6. [1935](http://github.com/cms-sw/cmssw/pull/1935){:target="_blank"}  from **@fwyzard**: Misc fixes -- FastTimerService, part 3 `hlt`  created: 2013-12-31 01:02:18 merged: 2014-01-17 10:18:20

7. [2048](http://github.com/cms-sw/cmssw/pull/2048){:target="_blank"}  from **@gartung**: Multicore fixes -- Add [[cms::thread_safe]] to non-const function static var Registry::instance()::s_reg `core`  created: 2014-01-16 19:09:15 merged: 2014-01-16 21:32:12

8. [2049](http://github.com/cms-sw/cmssw/pull/2049){:target="_blank"}  from **@Dr15Jones**: Framework fixes -- edm::refToPtr now handles null Refs `core`  created: 2014-01-16 20:09:31 merged: 2014-01-16 21:30:24

9. [2002](http://github.com/cms-sw/cmssw/pull/2002){:target="_blank"}  from **@fwyzard**: Db fixes -- LumiCorrectionSource: workaround CORAL not handling Timestamps `reconstruction`  created: 2014-01-12 14:45:23 merged: 2014-01-16 19:23:19

10. [1986](http://github.com/cms-sw/cmssw/pull/1986){:target="_blank"}  from **@bendavid**: Reco fix -- EGM GED bug fixes for pre12 (AOD size, cluster double counting, rechit fraction usage) `analysis`  `dqm`  `reconstruction`  `simulation`  created: 2014-01-10 16:41:51 merged: 2014-01-16 12:47:38

11. [2043](http://github.com/cms-sw/cmssw/pull/2043){:target="_blank"}  from **@ggovi**: Fix for support of reconnect in new Condition Database - required by HLT `db`  created: 2014-01-16 11:27:43 merged: 2014-01-16 11:33:02

12. [1864](http://github.com/cms-sw/cmssw/pull/1864){:target="_blank"}  from **@trocino**: HLT updates -- L2muon changes: L2MuonSeedGenerator, L2MuonProducer `reconstruction`  created: 2013-12-18 08:09:23 merged: 2014-01-15 15:49:38

13. [1913](http://github.com/cms-sw/cmssw/pull/1913){:target="_blank"}  from **@diguida**: Consumes migration -- Validation/TrackerHits `dqm`  created: 2013-12-20 16:47:34 merged: 2014-01-15 14:27:44

14. [1959](http://github.com/cms-sw/cmssw/pull/1959){:target="_blank"}  from **@lveldere**: Fastsim fixes -- New tuning of HF `fastsim`  created: 2014-01-07 18:48:17 merged: 2014-01-15 14:24:35

15. [1708](http://github.com/cms-sw/cmssw/pull/1708){:target="_blank"}  from **@mkirsano**: Generators fixes -- Redesign jet matching mg fast jet `generators`  created: 2013-12-06 17:59:50 merged: 2014-01-15 14:24:01

16. [2028](http://github.com/cms-sw/cmssw/pull/2028){:target="_blank"}  from **@inugent**: Validation updates -- Adding validation for Higgs->tautau CP and tau lifetime/decaylength in TauValidation `generators`  created: 2014-01-14 19:25:37 merged: 2014-01-15 14:22:17

17. [2008](http://github.com/cms-sw/cmssw/pull/2008){:target="_blank"}  from **@mkirsano**: Generators updates -- Lheint clean1 `generators`  created: 2014-01-13 11:38:36 merged: 2014-01-15 14:07:54

18. [2009](http://github.com/cms-sw/cmssw/pull/2009){:target="_blank"}  from **@mkirsano**: Generators fixes -- fix pydata loading problem, ported from 6_2_X `generators`  created: 2014-01-13 11:54:32 merged: 2014-01-15 14:07:07

19. [2027](http://github.com/cms-sw/cmssw/pull/2027){:target="_blank"}  from **@HuguesBrun**: Generators updates -- Add a fragment for H125 in bb produced by VBF `generators`  created: 2014-01-14 16:54:37 merged: 2014-01-15 14:06:03

20. [2023](http://github.com/cms-sw/cmssw/pull/2023){:target="_blank"}  from **@perrotta**: Consumes migration -- Fix a getByToken call in RecoTauTag/HLTProducers/src/CandidateSeededTrac... `hlt`  created: 2014-01-14 08:38:43 merged: 2014-01-15 14:00:09

21. [2024](http://github.com/cms-sw/cmssw/pull/2024){:target="_blank"}  from **@mommsen**: DAQ fixes -- Fix corruption of dat files `daq`  created: 2014-01-14 13:26:08 merged: 2014-01-15 09:33:12

22. [1970](http://github.com/cms-sw/cmssw/pull/1970){:target="_blank"}  from **@abdoulline**: ROOT6 fix -- fix of issues https://hypernews.cern.ch/HyperNews/CMS/get/swReleases/3982.html `alca`  created: 2014-01-09 08:17:12 merged: 2014-01-14 21:34:35

23. [1831](http://github.com/cms-sw/cmssw/pull/1831){:target="_blank"}  from **@ggovi**: DB improvements -- Fixes to allow the parallel use of ORA db and new CondDB `alca`  `db`  `dqm`  `l1`  created: 2013-12-16 15:27:00 merged: 2014-01-14 20:30:47

24. [1991](http://github.com/cms-sw/cmssw/pull/1991){:target="_blank"}  from **@Dr15Jones**: Reco fixes -- Declare several classes as non-storable `reconstruction`  created: 2014-01-10 21:21:31 merged: 2014-01-14 13:29:15

25. [1980](http://github.com/cms-sw/cmssw/pull/1980){:target="_blank"}  from **@gartung**: Multithreading fixes -- make static bool static std::atomic<bool> `db`  created: 2014-01-09 19:04:30 merged: 2014-01-14 13:05:29

26. [1914](http://github.com/cms-sw/cmssw/pull/1914){:target="_blank"}  from **@alja**: Fireworks fixes -- Fireworks table entries and tooltips for CSCDetId  `analysis`  `reconstruction`  `visualization`  created: 2013-12-20 17:25:50 merged: 2014-01-14 13:02:54

27. [1989](http://github.com/cms-sw/cmssw/pull/1989){:target="_blank"}  from **@Dr15Jones**: AT fixes -- Need to declare a member variable transient for AssociationMaps `analysis`  created: 2014-01-10 20:56:42 merged: 2014-01-14 13:02:26

28. [1976](http://github.com/cms-sw/cmssw/pull/1976){:target="_blank"}  from **@gartung**: Multithreading fixes -- Make file static variable const `alca`  `db`  created: 2014-01-09 17:12:53 merged: 2014-01-14 09:29:25

29. [2013](http://github.com/cms-sw/cmssw/pull/2013){:target="_blank"}  from **@fwyzard**: DQM fixes -- automatically support all DQMStore book\* calls in the IBooker (v2) `dqm`  created: 2014-01-13 15:03:20 merged: 2014-01-14 06:34:01

30. [1996](http://github.com/cms-sw/cmssw/pull/1996){:target="_blank"}  from **@Dr15Jones**: Multithreading fixes -- Add stack size control `core`  created: 2014-01-11 20:43:33 merged: 2014-01-13 14:05:54

31. [1936](http://github.com/cms-sw/cmssw/pull/1936){:target="_blank"}  from **@Martin-Grunewald**: Reco update -- Use new but equivalent CaloMETProducer instead of deprecated generic MET... `hlt`  `reconstruction`  created: 2013-12-31 09:26:04 merged: 2014-01-13 13:01:38

32. [1940](http://github.com/cms-sw/cmssw/pull/1940){:target="_blank"}  from **@TaiSakuma**: Reco cleanups -- Prepare to delete METProducer `analysis`  `dqm`  `hlt`  `reconstruction`  created: 2014-01-03 01:58:28 merged: 2014-01-13 13:00:37

33. [1974](http://github.com/cms-sw/cmssw/pull/1974){:target="_blank"}  from **@venturia**: Misc cleanups -- Removed dependencies which were not needed `dqm`  `reconstruction`  created: 2014-01-09 13:00:10 merged: 2014-01-13 12:36:40

34. [1973](http://github.com/cms-sw/cmssw/pull/1973){:target="_blank"}  from **@borrello**: DQM fixes -- Updated file for testing to include MET plot `dqm`  created: 2014-01-09 12:38:43 merged: 2014-01-13 11:25:15

35. [1938](http://github.com/cms-sw/cmssw/pull/1938){:target="_blank"}  from **@fwyzard**: DQM fixes -- DQMStore: avoid cloning MonitorElements that are not going to be merged `dqm`  created: 2014-01-01 13:57:20 merged: 2014-01-13 11:24:55

36. [1934](http://github.com/cms-sw/cmssw/pull/1934){:target="_blank"}  from **@fwyzard**: DQM cleanup -- Automatically support all DQMStore book\* calls in the IBooker `dqm`  created: 2013-12-31 00:43:19 merged: 2014-01-13 11:24:00

37. [1998](http://github.com/cms-sw/cmssw/pull/1998){:target="_blank"}  from **@davidlt**: DataFormats/Histograms: rename `debug' macro to`METOEDMFORMAT_DEBUG' `core`  `dqm`  created: 2014-01-12 07:48:37 merged: 2014-01-12 07:49:19

38. [1990](http://github.com/cms-sw/cmssw/pull/1990){:target="_blank"}  from **@Dr15Jones**: AT fix -- Fixed transient/persistent argument mixup `analysis`  created: 2014-01-10 21:17:43 merged: 2014-01-11 13:51:03

39. [1958](http://github.com/cms-sw/cmssw/pull/1958){:target="_blank"}  from **@rappoccio**: Bug fix : adding JEC producers for AK5CHS and AK7CHS `analysis`  created: 2014-01-07 18:26:54 merged: 2014-01-10 15:37:37

40. [1985](http://github.com/cms-sw/cmssw/pull/1985){:target="_blank"}  from **@mommsen**: DAQ updates -- Close file after writing the init message. `daq`  created: 2014-01-10 11:44:04 merged: 2014-01-10 12:55:04

41. [1952](http://github.com/cms-sw/cmssw/pull/1952){:target="_blank"}  from **@vkuznet**: Fix naming collision between locally defined function and variable phi. `reconstruction`  created: 2014-01-06 15:19:58 merged: 2014-01-09 15:09:13

42. [1966](http://github.com/cms-sw/cmssw/pull/1966){:target="_blank"}  from **@Dr15Jones**: Framework fixes -- Added option to set gDebug from InitRootHandler's parameters `core`  created: 2014-01-08 20:13:14 merged: 2014-01-09 10:32:03

43. [1962](http://github.com/cms-sw/cmssw/pull/1962){:target="_blank"}  from **@deguio**: DQM fixes -- Updating the memory references for whiteRabbit tests `dqm`  created: 2014-01-08 15:40:12 merged: 2014-01-09 09:49:11

44. [1963](http://github.com/cms-sw/cmssw/pull/1963){:target="_blank"}  from **@inugent**: Generator fix -- Patch for undertemined decay modes and adding Z+gamma mode in Generator Higgs Validation. `generators`  created: 2014-01-08 16:51:25 merged: 2014-01-09 09:48:23

45. [1961](http://github.com/cms-sw/cmssw/pull/1961){:target="_blank"}  from **@davidlt**: Misc fixes -- CommonTools/TrackerMap: add missing std:: in print_TrackerMap.cc `dqm`  `reconstruction`  created: 2014-01-08 11:53:18 merged: 2014-01-08 13:25:37

46. [1960](http://github.com/cms-sw/cmssw/pull/1960){:target="_blank"}  from **@davidlt**: Misc fixes -- DQM/TrackingMonitorClient: add missing std:: `dqm`  created: 2014-01-08 11:52:54 merged: 2014-01-08 12:55:35

47. [1957](http://github.com/cms-sw/cmssw/pull/1957){:target="_blank"}  from **@slava77**: Reco fix -- Moved dict for ValueMap of vector of PFCandidateRef from EgammaCandidate... `reconstruction`  created: 2014-01-07 16:00:43 merged: 2014-01-07 21:42:03

48. [1956](http://github.com/cms-sw/cmssw/pull/1956){:target="_blank"}  from **@slava77**: Reco fix -- rename typedef to avoid duplicate def with ElectronSeedRefVector::iterator `reconstruction`  created: 2014-01-07 14:42:42 merged: 2014-01-07 16:49:05

49. [1955](http://github.com/cms-sw/cmssw/pull/1955){:target="_blank"}  from **@thomreis**: DQM fixes -- Fix for manual offline egamma HLT validation script `dqm`  created: 2014-01-07 13:46:52 merged: 2014-01-07 16:29:27

50. [1944](http://github.com/cms-sw/cmssw/pull/1944){:target="_blank"}  from **@alja**: Fireworks fixes -- 70x improve unittest for fireworks configuration. `visualization`  created: 2014-01-03 18:58:24 merged: 2014-01-07 14:07:10

51. [1948](http://github.com/cms-sw/cmssw/pull/1948){:target="_blank"}  from **@Dr15Jones**: Multithreading fixes -- Removed DQM and PoolDBOutputServices from threaded jobs `core`  created: 2014-01-05 19:28:16 merged: 2014-01-05 19:33:29

52. [1943](http://github.com/cms-sw/cmssw/pull/1943){:target="_blank"}  from **@Dr15Jones**: Multithreading fixes -- Remove the HeavyIon module that depends on TkDetMap `core`  created: 2014-01-03 17:27:28 merged: 2014-01-05 16:16:11

53. [1945](http://github.com/cms-sw/cmssw/pull/1945){:target="_blank"}  from **@Dr15Jones**: Tools fixes -- Extended Helgrind Suppressions to more TBB and Framework internals `core`  created: 2014-01-04 02:14:45 merged: 2014-01-04 19:10:28

54. [1946](http://github.com/cms-sw/cmssw/pull/1946){:target="_blank"}  from **@Dr15Jones**: Misc fixes -- Properly handle built in customise additions `operations`  created: 2014-01-04 16:20:03 merged: 2014-01-04 19:06:30

55. [1942](http://github.com/cms-sw/cmssw/pull/1942){:target="_blank"}  from **@Dr15Jones**: Misc cleanup -- Allow cmsDriver.py to accept multiple --customise options `operations`  created: 2014-01-03 16:37:44 merged: 2014-01-03 22:51:46

56. [1931](http://github.com/cms-sw/cmssw/pull/1931){:target="_blank"}  from **@alja**: Fireworks fixes -- Fix crash in Fireworks DetailView, import missing changes from CVS head for scaling of RecHits `visualization`  created: 2013-12-30 18:10:45 merged: 2014-01-01 12:12:39

57. [1916](http://github.com/cms-sw/cmssw/pull/1916){:target="_blank"}  from **@demattia**: AlCa fixes -- Added MVAs to the prompt GT `alca`  created: 2013-12-20 20:35:39 merged: 2013-12-20 20:50:13
