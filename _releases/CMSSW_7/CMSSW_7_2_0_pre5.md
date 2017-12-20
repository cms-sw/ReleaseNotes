---
layout: post
rel_link:  "7_2_0_pre5"
title:  "CMSSW_7_2_0_pre5"
date:   2014-08-27 12:08:44
categories: cmssw
relmajor: 7
relminor: 2
relsubminor: 0
relpre: _pre5
---

# CMSSW_7_2_0_pre5
#### Changes since CMSSW_7_2_0_pre4:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_2_0_pre4...CMSSW_7_2_0_pre5)



1. [5067](http://github.com/cms-sw/cmssw/pull/5067){:target="_blank"}  from **@Dr15Jones**: Fix clang compiler error by explicitly calling default constructor `geometry`  created: 2014-08-26 19:15:42 merged: 2014-08-27 09:42:37

2. [5069](http://github.com/cms-sw/cmssw/pull/5069){:target="_blank"}  from **@Dr15Jones**: simple clang fix for electronMVAEstimator `reconstruction`  created: 2014-08-26 19:31:08 merged: 2014-08-27 09:42:06

3. [5070](http://github.com/cms-sw/cmssw/pull/5070){:target="_blank"}  from **@alja**: 72x Fix clang error in Fireworks/ParticleFlow `visualization`  created: 2014-08-27 00:21:48 merged: 2014-08-27 09:19:15

4. [5068](http://github.com/cms-sw/cmssw/pull/5068){:target="_blank"}  from **@davidlange6**: Remove taudau assert `generators`  created: 2014-08-26 19:27:02 merged: 2014-08-26 19:31:27

5. [4946](http://github.com/cms-sw/cmssw/pull/4946){:target="_blank"}  from **@xshi**: Xshi hlt photon jet dqm `dqm`  created: 2014-08-14 14:31:55 merged: 2014-08-26 18:41:52

6. [5030](http://github.com/cms-sw/cmssw/pull/5030){:target="_blank"}  from **@avartak**: Tk Validation dedx plot bugfix and adding eff/fake vs dR plots `dqm`  created: 2014-08-22 14:10:20 merged: 2014-08-26 18:40:12

7. [5042](http://github.com/cms-sw/cmssw/pull/5042){:target="_blank"}  from **@HuguesBrun**: add Hww and Hgg paths to be monitored in the Higgs HLT validation `dqm`  created: 2014-08-25 14:53:46 merged: 2014-08-26 18:39:39

8. [5059](http://github.com/cms-sw/cmssw/pull/5059){:target="_blank"}  from **@dmitrijus**: Migrate DQMFileSaver to use LogAbsolute instead of std::cout. `dqm`  created: 2014-08-26 11:41:22 merged: 2014-08-26 18:39:09

9. [5034](http://github.com/cms-sw/cmssw/pull/5034){:target="_blank"}  from **@slava77**: introduce repacking step in post-LS1 CSC simulation `reconstruction`  `simulation`  created: 2014-08-23 22:28:54 merged: 2014-08-26 14:01:03

10. [5056](http://github.com/cms-sw/cmssw/pull/5056){:target="_blank"}  from **@fwyzard**: fix the summing of TriggerResults across multiple streams `core`  created: 2014-08-26 10:11:33 merged: 2014-08-26 12:18:53

11. [5053](http://github.com/cms-sw/cmssw/pull/5053){:target="_blank"}  from **@Martin-Grunewald**: PAT fix to deal with GTs with added payloads `analysis`  created: 2014-08-26 09:03:33 merged: 2014-08-26 11:27:40

12. [5047](http://github.com/cms-sw/cmssw/pull/5047){:target="_blank"}  from **@dabelknap**: Applying patch for 25ns Dec 2012 runs `l1`  created: 2014-08-25 20:36:01 merged: 2014-08-26 09:39:08

13. [5043](http://github.com/cms-sw/cmssw/pull/5043){:target="_blank"}  from **@ggovi**: Switched off IOV caching in pages `db`  created: 2014-08-25 15:46:03 merged: 2014-08-26 07:06:54

14. [4973](http://github.com/cms-sw/cmssw/pull/4973){:target="_blank"}  from **@quertenmont**: Update RecoTracker/dEdx package `alca`  `analysis`  `dqm`  `operations`  `reconstruction`  created: 2014-08-18 08:11:58 merged: 2014-08-26 06:14:47

15. [5040](http://github.com/cms-sw/cmssw/pull/5040){:target="_blank"}  from **@ianna**: Pick up executable from PATH `geometry`  created: 2014-08-25 13:33:12 merged: 2014-08-25 14:40:00

16. [5041](http://github.com/cms-sw/cmssw/pull/5041){:target="_blank"}  from **@Dr15Jones**: Wait longer for job timeout when testing multi-threaded `core`  created: 2014-08-25 14:01:38 merged: 2014-08-25 14:05:36

17. [4958](http://github.com/cms-sw/cmssw/pull/4958){:target="_blank"}  from **@wmtan**: Don't check dictionaries unnecessarily `alca`  `analysis`  `core`  `daq`  `generators`  `geometry`  `reconstruction`  `simulation`  `visualization`  created: 2014-08-15 14:43:46 merged: 2014-08-25 12:23:18

18. [4988](http://github.com/cms-sw/cmssw/pull/4988){:target="_blank"}  from **@Martin-Grunewald**: HLT menu with new HLT JECs and autoCond update `alca`  `hlt`  created: 2014-08-19 06:58:44 merged: 2014-08-25 11:28:48

19. [5038](http://github.com/cms-sw/cmssw/pull/5038){:target="_blank"}  from **@ktf**: Set boolean so that test does not fail. `alca`  `db`  `l1`  created: 2014-08-25 10:40:04 merged: 2014-08-25 10:41:18

20. [4943](http://github.com/cms-sw/cmssw/pull/4943){:target="_blank"}  from **@ktf**: Drop tests which break after obsoletion of castor pool. `core`  created: 2014-08-14 08:12:48 merged: 2014-08-25 09:51:26

21. [5036](http://github.com/cms-sw/cmssw/pull/5036){:target="_blank"}  from **@ianna**: Remove unused code `geometry`  created: 2014-08-25 08:45:12 merged: 2014-08-25 09:19:58

22. [4934](http://github.com/cms-sw/cmssw/pull/4934){:target="_blank"}  from **@cms-analysis-tools**: Generator level heavy flavour jet origin/flavour identification `analysis`  created: 2014-08-12 23:06:08 merged: 2014-08-25 09:06:44

23. [5029](http://github.com/cms-sw/cmssw/pull/5029){:target="_blank"}  from **@ianna**: Clean up DDRoot `geometry`  created: 2014-08-22 13:45:12 merged: 2014-08-25 08:39:38

24. [4971](http://github.com/cms-sw/cmssw/pull/4971){:target="_blank"}  from **@syuvivida**: Codes require to save generator cross section in each luminosity block `generators`  created: 2014-08-15 21:19:22 merged: 2014-08-25 07:46:16

25. [4948](http://github.com/cms-sw/cmssw/pull/4948){:target="_blank"}  from **@rappoccio**: Adding Hadronic-path HLT DQM for B2G PAG created: 2014-08-14 19:04:53 merged: 2014-08-25 07:43:26

26. [4985](http://github.com/cms-sw/cmssw/pull/4985){:target="_blank"}  from **@franzoni**: Mixing execute base cmssw 7 2 `operations`  `simulation`  created: 2014-08-18 21:28:38 merged: 2014-08-25 07:41:33

27. [5025](http://github.com/cms-sw/cmssw/pull/5025){:target="_blank"}  from **@sdevissc**: Hq filter72 x `generators`  created: 2014-08-21 22:07:44 merged: 2014-08-25 07:41:11

28. [5035](http://github.com/cms-sw/cmssw/pull/5035){:target="_blank"}  from **@fwyzard**: add -fdebug-prefix-map to the unsupported options `db`  created: 2014-08-24 17:16:40 merged: 2014-08-25 07:00:21

29. [4858](http://github.com/cms-sw/cmssw/pull/4858){:target="_blank"}  from **@wddgit**: Add check that the event number is valid `core`  created: 2014-07-31 21:51:40 merged: 2014-08-22 15:53:23

30. [5031](http://github.com/cms-sw/cmssw/pull/5031){:target="_blank"}  from **@ktf**: Add csa_assert macro. `core`  created: 2014-08-22 15:06:30 merged: 2014-08-22 15:07:25

31. [5018](http://github.com/cms-sw/cmssw/pull/5018){:target="_blank"}  from **@ianna**: Thread safe singleton `geometry`  created: 2014-08-21 14:21:35 merged: 2014-08-22 13:14:10

32. [5007](http://github.com/cms-sw/cmssw/pull/5007){:target="_blank"}  from **@vlimant**: Cfa renewal 72 x `analysis`  `reconstruction`  created: 2014-08-20 09:40:58 merged: 2014-08-22 13:01:14

33. [5023](http://github.com/cms-sw/cmssw/pull/5023){:target="_blank"}  from **@ggovi**: fixed iov caching for edge conditions on non-ordered queries `db`  created: 2014-08-21 16:17:15 merged: 2014-08-22 08:26:51

34. [5022](http://github.com/cms-sw/cmssw/pull/5022){:target="_blank"}  from **@slava77**: fix crash in pre4 Assertion `seedCollection==nullptr' failed.`reconstruction`  created: 2014-08-21 15:49:26 merged: 2014-08-21 20:01:49

35. [4937](http://github.com/cms-sw/cmssw/pull/4937){:target="_blank"}  from @mtosi: tracking and PV validation**@HLT** `dqm`  `simulation`  created: 2014-08-13 10:11:20 merged: 2014-08-21 14:37:09

36. [4872](http://github.com/cms-sw/cmssw/pull/4872){:target="_blank"}  from **@rovere**: Move Vertex Validation histograms in a more appropriate folder. `dqm`  created: 2014-08-04 10:03:42 merged: 2014-08-21 13:21:43

37. [4902](http://github.com/cms-sw/cmssw/pull/4902){:target="_blank"}  from **@jhgoh**: RPCMuon bugfix in MuonIdProducer `dqm`  `reconstruction`  created: 2014-08-07 16:27:56 merged: 2014-08-21 13:07:10

38. [4947](http://github.com/cms-sw/cmssw/pull/4947){:target="_blank"}  from **@VinInn**: Tracker geom det `alca`  `fastsim`  `geometry`  `reconstruction`  `visualization`  created: 2014-08-14 18:33:52 merged: 2014-08-21 13:02:53

39. [5010](http://github.com/cms-sw/cmssw/pull/5010){:target="_blank"}  from **@battibass**: Fixed L1 emulation sequence for FastSim to be compliant with postLS customisations for CSC `fastsim`  `hlt`  created: 2014-08-20 17:06:35 merged: 2014-08-21 11:43:06

40. [4980](http://github.com/cms-sw/cmssw/pull/4980){:target="_blank"}  from **@franzoni**: Add files need for RunDependent MC `operations`  `simulation`  created: 2014-08-18 20:11:49 merged: 2014-08-21 06:54:22

41. [5005](http://github.com/cms-sw/cmssw/pull/5005){:target="_blank"}  from **@lveldere**: Allow postLS1 customisation for reduced geometries  `simulation`  created: 2014-08-20 08:32:00 merged: 2014-08-21 05:49:51

42. [5006](http://github.com/cms-sw/cmssw/pull/5006){:target="_blank"}  from **@ianna**: Remove const_cast `geometry`  created: 2014-08-20 09:26:53 merged: 2014-08-20 13:19:46

43. [4997](http://github.com/cms-sw/cmssw/pull/4997){:target="_blank"}  from **@ianna**: Return const member from const function `geometry`  created: 2014-08-19 14:33:44 merged: 2014-08-19 19:55:20

44. [4975](http://github.com/cms-sw/cmssw/pull/4975){:target="_blank"}  from **@Dr15Jones**: Fix crash in DTDCSByLumiSummary when MonitorElements are missing `dqm`  created: 2014-08-18 12:47:44 merged: 2014-08-19 13:01:07

45. [4989](http://github.com/cms-sw/cmssw/pull/4989){:target="_blank"}  from **@ianna**: Update xml validation script `geometry`  created: 2014-08-19 07:45:26 merged: 2014-08-19 10:28:20

46. [4986](http://github.com/cms-sw/cmssw/pull/4986){:target="_blank"}  from **@bendavid**: Revert broken tau fixes (72x) `generators`  created: 2014-08-19 00:47:11 merged: 2014-08-19 07:31:21

47. [4982](http://github.com/cms-sw/cmssw/pull/4982){:target="_blank"}  from **@franzoni**: Fw port tsg pu scenario cmssw 7 2 x  `operations`  `simulation`  created: 2014-08-18 20:29:22 merged: 2014-08-19 07:18:25

48. [4976](http://github.com/cms-sw/cmssw/pull/4976){:target="_blank"}  from **@VinInn**: fix bug affecting pre4 relvals `reconstruction`  created: 2014-08-18 16:08:35 merged: 2014-08-18 16:18:47

49. [4974](http://github.com/cms-sw/cmssw/pull/4974){:target="_blank"}  from **@ianna**: Migrate geometry tests helper to bin directory `geometry`  created: 2014-08-18 08:46:41 merged: 2014-08-18 09:25:04

50. [4972](http://github.com/cms-sw/cmssw/pull/4972){:target="_blank"}  from **@franzoni**: Update input GEN-SIM for relvals to 7_2_0_pre4 `operations`  created: 2014-08-17 20:42:47 merged: 2014-08-18 09:14:05

51. [4959](http://github.com/cms-sw/cmssw/pull/4959){:target="_blank"}  from **@franzoni**: Update input samples cmssw 7 2 0 pre4 `operations`  created: 2014-08-15 15:04:13 merged: 2014-08-16 07:58:29

52. [4969](http://github.com/cms-sw/cmssw/pull/4969){:target="_blank"}  from **@Dr15Jones**: Protect Electron DQM code from missing MonitorElements `dqm`  created: 2014-08-15 18:57:45 merged: 2014-08-16 07:50:53

53. [4966](http://github.com/cms-sw/cmssw/pull/4966){:target="_blank"}  from **@Dr15Jones**: Fix clang problems in JetMETCorrections/Type1MET `analysis`  created: 2014-08-15 16:42:06 merged: 2014-08-16 07:49:59

54. [4967](http://github.com/cms-sw/cmssw/pull/4967){:target="_blank"}  from **@Dr15Jones**: Fixed bug in BoostedJetMerger and made it a edm::stream::Producer `analysis`  created: 2014-08-15 16:45:20 merged: 2014-08-16 07:48:41

55. [4961](http://github.com/cms-sw/cmssw/pull/4961){:target="_blank"}  from **@pgunnell**: Pythia8CUEP8M1Settings_cfi.py (72x) `generators`  created: 2014-08-15 15:22:41 merged: 2014-08-16 07:47:07

56. [4965](http://github.com/cms-sw/cmssw/pull/4965){:target="_blank"}  from **@Dr15Jones**: Fix clang problems in DataFormats/PatCandidates `analysis`  created: 2014-08-15 16:28:30 merged: 2014-08-15 21:38:01

57. [4963](http://github.com/cms-sw/cmssw/pull/4963){:target="_blank"}  from **@Dr15Jones**: Change forward declartion from struct to class for clang `core`  created: 2014-08-15 16:19:50 merged: 2014-08-15 17:57:18

58. [4952](http://github.com/cms-sw/cmssw/pull/4952){:target="_blank"}  from **@ianna**: Validation script update `geometry`  created: 2014-08-15 07:32:24 merged: 2014-08-15 12:35:57

59. [4953](http://github.com/cms-sw/cmssw/pull/4953){:target="_blank"}  from **@inugent**: Switching to genparticles for TauValidation `generators`  created: 2014-08-15 10:25:40 merged: 2014-08-15 12:34:41

60. [4696](http://github.com/cms-sw/cmssw/pull/4696){:target="_blank"}  from **@inugent**: Rel val 13 te v 7 2 x `generators`  `operations`  created: 2014-07-18 10:35:43 merged: 2014-08-15 11:07:53

61. [4951](http://github.com/cms-sw/cmssw/pull/4951){:target="_blank"}  from **@Dr15Jones**: Fix bugs in Validation/RecoEgamma `dqm`  created: 2014-08-14 22:22:37 merged: 2014-08-15 10:13:46

62. [4949](http://github.com/cms-sw/cmssw/pull/4949){:target="_blank"}  from **@alja**: 72x New PF Candidate Detail View `visualization`  created: 2014-08-14 19:35:28 merged: 2014-08-15 07:56:46

63. [4950](http://github.com/cms-sw/cmssw/pull/4950){:target="_blank"}  from **@Dr15Jones**: Need to pass run number ot bookHistogram to store to DQMRootOutputModule `dqm`  created: 2014-08-14 22:04:48 merged: 2014-08-14 22:19:19

64. [4944](http://github.com/cms-sw/cmssw/pull/4944){:target="_blank"}  from **@ianna**: World cavern size `geometry`  created: 2014-08-14 09:34:22 merged: 2014-08-14 12:52:01

65. [4868](http://github.com/cms-sw/cmssw/pull/4868){:target="_blank"}  from **@aehart**: Int monitor element fix `dqm`  created: 2014-08-02 08:09:49 merged: 2014-08-14 09:21:18

#### CMSDIST Changes between Tags REL/CMSSW_7_2_0_pre4/slc6_amd64_gcc481 and REL/CMSSW_7_2_0_pre5/slc6_amd64_gcc481:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_2_0_pre4/slc6_amd64_gcc481...REL/CMSSW_7_2_0_pre5/slc6_amd64_gcc481)



1. [959](http://github.com/cms-sw/cmsdist/pull/959){:target="_blank"}  from **@smuzaffar**: updated config tag to V05-03-18 created: 2014-08-27 09:07:29 merged: 2014-08-27 09:19:29

2. [956](http://github.com/cms-sw/cmsdist/pull/956){:target="_blank"}  from @ktf: Move to cms-sw/root**@6685636b54f8** created: 2014-08-26 14:46:28 merged: 2014-08-26 14:46:56

3. [952](http://github.com/cms-sw/cmsdist/pull/952){:target="_blank"}  from **@smuzaffar**: updated config tag to V05-03-16 created: 2014-08-26 10:55:35 merged: 2014-08-26 10:55:40

4. [945](http://github.com/cms-sw/cmsdist/pull/945){:target="_blank"}  from **@mkirsano**: move to lhapdf6 6.1.4 and make a few fixes created: 2014-08-23 07:34:11 merged: 2014-08-26 10:27:28

5. [938](http://github.com/cms-sw/cmsdist/pull/938){:target="_blank"}  from **@degano**: Add BaBar files for EvtGen. created: 2014-08-14 09:34:27 merged: 2014-08-25 13:50:14

6. [941](http://github.com/cms-sw/cmsdist/pull/941){:target="_blank"}  from **@nclopezo**: New Data external: added data external for RecoHI/HiJetAlgos created: 2014-08-15 13:04:33 merged: 2014-08-15 13:14:54

7. [940](http://github.com/cms-sw/cmsdist/pull/940){:target="_blank"}  from **@cms-sw**: Revert "Re-enable xrootd 4.0.2." created: 2014-08-14 18:48:09 merged: 2014-08-14 18:48:23
