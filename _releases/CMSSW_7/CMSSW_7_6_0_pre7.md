---
layout: post
rel_link:  "7_6_0_pre7"
title:  "CMSSW_7_6_0_pre7"
date:   2015-10-09 14:43:16
categories: cmssw
relmajor: 7
relminor: 6
relsubminor: 0
relpre: _pre7
---

# CMSSW_7_6_0_pre7
#### Changes since CMSSW_7_6_0_pre6:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_6_0_pre6...CMSSW_7_6_0_pre7)



1. [11667](http://github.com/cms-sw/cmssw/pull/11667){:target="_blank"}  from **@abdoulline**: Replacing SpikeNoise flag by NegativeNoise one   `operations`  created: 2015-10-07 14:42:10 merged: 2015-10-09 12:50:33

2. [11707](http://github.com/cms-sw/cmssw/pull/11707){:target="_blank"}  from **@mark-grimes**: Add caloConfig and caloConfigSource to L1 step `l1`  created: 2015-10-09 05:46:26 merged: 2015-10-09 12:48:18

3. [11703](http://github.com/cms-sw/cmssw/pull/11703){:target="_blank"}  from **@wmtan**: Replace cryptic assert with informative exception for missing Wrapper dictionary `core`  created: 2015-10-08 22:14:25 merged: 2015-10-09 05:56:13

4. [11693](http://github.com/cms-sw/cmssw/pull/11693){:target="_blank"}  from **@cmkuo**: improve ES unpacker `reconstruction`  created: 2015-10-08 15:33:12 merged: 2015-10-09 05:54:03

5. [11699](http://github.com/cms-sw/cmssw/pull/11699){:target="_blank"}  from **@fojensen**: add 75x V0Producer to 76x `reconstruction`  created: 2015-10-08 16:03:18 merged: 2015-10-09 05:53:41

6. [11697](http://github.com/cms-sw/cmssw/pull/11697){:target="_blank"}  from **@diguida**: New GT with PF hadron calibration. `alca`  created: 2015-10-08 15:49:01 merged: 2015-10-08 19:22:41

7. [11466](http://github.com/cms-sw/cmssw/pull/11466){:target="_blank"}  from **@mark-grimes**: Switch runTheMatrix tests to use Run 2 eras `pdmv`  `simulation`  created: 2015-09-24 16:46:25 merged: 2015-10-08 18:49:58

8. [11686](http://github.com/cms-sw/cmssw/pull/11686){:target="_blank"}  from **@davidlange6**: put the new time slew in by default for HLT mc `hlt`  created: 2015-10-08 06:19:53 merged: 2015-10-08 08:00:04

9. [11641](http://github.com/cms-sw/cmssw/pull/11641){:target="_blank"}  from **@davidlt**: Fireworks cleanup for {private,protected} macro removal `visualization`  created: 2015-10-05 20:08:55 merged: 2015-10-08 06:08:06

10. [11601](http://github.com/cms-sw/cmssw/pull/11601){:target="_blank"}  from **@fioriNTU**: Make FED Occupancy plot a TProfile `dqm`  created: 2015-10-01 15:42:12 merged: 2015-10-08 06:07:00

11. [11614](http://github.com/cms-sw/cmssw/pull/11614){:target="_blank"}  from **@cmkuo**: fix ES unpacker when the 2nd OptoRX is diabled, but the 1t and 3rd Op `reconstruction`  created: 2015-10-02 03:27:12 merged: 2015-10-08 06:06:22

12. [11504](http://github.com/cms-sw/cmssw/pull/11504){:target="_blank"}  from **@cms-l1t-offline**: initial commit of 2016 L1T muon emulation `l1`  created: 2015-09-26 02:12:45 merged: 2015-10-08 06:05:03

13. [11572](http://github.com/cms-sw/cmssw/pull/11572){:target="_blank"}  from **@cms-btv-pog**: Switch on hadronFlavourHasPriority for b-tag Validation module. `dqm`  created: 2015-09-30 14:19:57 merged: 2015-10-08 06:04:46

14. [11647](http://github.com/cms-sw/cmssw/pull/11647){:target="_blank"}  from **@smuzaffar**: set reco::CandViewCandViewAssociation as transient `analysis`  `reconstruction`  created: 2015-10-06 07:00:05 merged: 2015-10-08 06:03:11

15. [11684](http://github.com/cms-sw/cmssw/pull/11684){:target="_blank"}  from **@Dr15Jones**: Fix precedence error and added additional functions `analysis`  `reconstruction`  created: 2015-10-08 03:15:10 merged: 2015-10-08 06:01:54

16. [11675](http://github.com/cms-sw/cmssw/pull/11675){:target="_blank"}  from **@davidlange6**: make hcal digitization changes the default `reconstruction`  `simulation`  created: 2015-10-07 18:50:44 merged: 2015-10-08 06:00:06

17. [11398](http://github.com/cms-sw/cmssw/pull/11398){:target="_blank"}  from **@dnash86**: Me0 muons in 76 x commitv2 `reconstruction`  `simulation`  created: 2015-09-21 15:29:01 merged: 2015-10-07 14:19:11

18. [11574](http://github.com/cms-sw/cmssw/pull/11574){:target="_blank"}  from **@lgray**: Use std::lower_bound to add/search for userFloats/Ints/Cands/KinResolutions (76X) `analysis`  created: 2015-09-30 14:51:52 merged: 2015-10-07 10:01:44

19. [11487](http://github.com/cms-sw/cmssw/pull/11487){:target="_blank"}  from **@fioriNTU**: fix bpix efficiency 76x `dqm`  created: 2015-09-25 08:49:09 merged: 2015-10-07 09:52:40

20. [11493](http://github.com/cms-sw/cmssw/pull/11493){:target="_blank"}  from **@BaylorCMS**: Adjusts SimHits histogram binning and adds Additional Noise plots `dqm`  created: 2015-09-25 14:27:26 merged: 2015-10-07 09:52:29

21. [11498](http://github.com/cms-sw/cmssw/pull/11498){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx31 Add simulation code for HGCal and single layer fast timing device `simulation`  created: 2015-09-25 21:41:08 merged: 2015-10-07 09:52:23

22. [11499](http://github.com/cms-sw/cmssw/pull/11499){:target="_blank"}  from **@wmtford**: New analysis module StripClusterMCanalysis `dqm`  created: 2015-09-25 22:04:31 merged: 2015-10-07 09:52:16

23. [11579](http://github.com/cms-sw/cmssw/pull/11579){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx34 Avoid the crashes in the DQM code `dqm`  created: 2015-09-30 21:11:16 merged: 2015-10-07 09:51:50

24. [11618](http://github.com/cms-sw/cmssw/pull/11618){:target="_blank"}  from **@geonmo**: Add L1 copad collection and ME0 validation on valid. `simulation`  created: 2015-10-02 10:24:08 merged: 2015-10-07 09:51:39

25. [11654](http://github.com/cms-sw/cmssw/pull/11654){:target="_blank"}  from **@mark-grimes**: Copy muonDetIdAssociator customisation changes to eras `reconstruction`  created: 2015-10-06 15:44:36 merged: 2015-10-07 07:49:22

26. [11658](http://github.com/cms-sw/cmssw/pull/11658){:target="_blank"}  from **@gsafronov**: 76X: fix pT selection in HLTrigger/special/src/HLTPixlMBFilt.cc `hlt`  created: 2015-10-06 16:16:57 merged: 2015-10-07 05:56:25

27. [11659](http://github.com/cms-sw/cmssw/pull/11659){:target="_blank"}  from **@civanch**: removed private_public in unit test `simulation`  created: 2015-10-06 18:00:53 merged: 2015-10-07 05:56:20

28. [11621](http://github.com/cms-sw/cmssw/pull/11621){:target="_blank"}  from **@makortel**: Fixes for phase1 workflow `reconstruction`  `simulation`  created: 2015-10-02 11:27:05 merged: 2015-10-07 05:51:40

29. [11642](http://github.com/cms-sw/cmssw/pull/11642){:target="_blank"}  from **@aehart**: TrackDetMatch DeltaR bug fix `reconstruction`  created: 2015-10-05 20:49:48 merged: 2015-10-07 05:51:34

30. [11662](http://github.com/cms-sw/cmssw/pull/11662){:target="_blank"}  from **@bbockelm**: Allow stacktrace handler to timeout. `core`  created: 2015-10-06 21:03:16 merged: 2015-10-07 05:51:14

31. [11626](http://github.com/cms-sw/cmssw/pull/11626){:target="_blank"}  from **@bsunanda**: Run2-hcx36 Add in the digitization code for HGCal `simulation`  created: 2015-10-04 13:23:31 merged: 2015-10-06 19:11:39

32. [11609](http://github.com/cms-sw/cmssw/pull/11609){:target="_blank"}  from **@mmusich**: New GTs for 76X: L1,HLT,Geometry and HCAL changes `alca`  `hlt`  created: 2015-10-01 17:30:45 merged: 2015-10-06 19:08:04

33. [11639](http://github.com/cms-sw/cmssw/pull/11639){:target="_blank"}  from **@wmtan**: Add HepMCProduct backward compatibility for premixing `operations`  created: 2015-10-05 16:48:46 merged: 2015-10-06 16:03:16

34. [11607](http://github.com/cms-sw/cmssw/pull/11607){:target="_blank"}  from **@lgray**: Change CandidateBoostedDoubleSecondaryVertexComputer to use GBRForest (76X) `reconstruction`  created: 2015-10-01 17:23:58 merged: 2015-10-06 06:21:21

35. [11603](http://github.com/cms-sw/cmssw/pull/11603){:target="_blank"}  from **@kkrajczar**: For HI HLT: migration of 5 HI tracking modules to stream modules `reconstruction`  created: 2015-10-01 16:03:52 merged: 2015-10-06 06:16:31

36. [11633](http://github.com/cms-sw/cmssw/pull/11633){:target="_blank"}  from **@duanders**: Scouting producers now ignore missing input collections (76X) `hlt`  created: 2015-10-05 09:08:01 merged: 2015-10-06 06:16:21

37. [11640](http://github.com/cms-sw/cmssw/pull/11640){:target="_blank"}  from **@fwyzard**: hltDiff: add protections against missing or empty input files `hlt`  created: 2015-10-05 17:11:41 merged: 2015-10-06 06:11:26

38. [11590](http://github.com/cms-sw/cmssw/pull/11590){:target="_blank"}  from **@davidlt**: DataFormats/TrackReco: remove intrusive macros breaking stdlibc++ `reconstruction`  created: 2015-10-01 13:04:57 merged: 2015-10-05 16:51:50

39. [11588](http://github.com/cms-sw/cmssw/pull/11588){:target="_blank"}  from **@diguida**: Add member function in FillInfo to check the injection scheme for 25 ns. `alca`  `db`  created: 2015-10-01 08:24:16 merged: 2015-10-05 16:47:05

40. [11591](http://github.com/cms-sw/cmssw/pull/11591){:target="_blank"}  from **@davidlt**: CondCore/DBCommon: remove intrusive macros breaking libstdc++ `alca`  `db`  created: 2015-10-01 13:08:39 merged: 2015-10-05 16:46:54

41. [11619](http://github.com/cms-sw/cmssw/pull/11619){:target="_blank"}  from **@ndaci**: Added new paths in PFHT category. `dqm`  created: 2015-10-02 10:44:53 merged: 2015-10-05 16:46:32

42. [11628](http://github.com/cms-sw/cmssw/pull/11628){:target="_blank"}  from **@smuzaffar**: remove ref to testCondDBDict which is not part of this package any more `db`  created: 2015-10-05 07:04:23 merged: 2015-10-05 16:46:23

43. [11584](http://github.com/cms-sw/cmssw/pull/11584){:target="_blank"}  from **@Dr15Jones**: Replace TFormula in SimpleJetCorrector `analysis`  `db`  `reconstruction`  created: 2015-10-01 01:12:59 merged: 2015-10-05 16:44:01

44. [11491](http://github.com/cms-sw/cmssw/pull/11491){:target="_blank"}  from **@cms-met**: Disabling the reclustering in the MET correction and uncertainty tool (76X) `analysis`  created: 2015-09-25 13:16:03 merged: 2015-10-05 14:03:19

45. [11576](http://github.com/cms-sw/cmssw/pull/11576){:target="_blank"}  from **@davidlange6**: Central bunch spacing producer for 76x `dqm`  `operations`  `reconstruction`  `simulation`  created: 2015-09-30 14:57:01 merged: 2015-10-05 10:25:29

46. [11583](http://github.com/cms-sw/cmssw/pull/11583){:target="_blank"}  from **@mark-grimes**: Update Run 2 eras to configure FastSim properly `fastsim`  created: 2015-09-30 22:00:13 merged: 2015-10-05 10:06:38

47. [11592](http://github.com/cms-sw/cmssw/pull/11592){:target="_blank"}  from **@davidlt**: CalibTracker/SiStripDCS: remove intrusive macros breaking libstdc++ `alca`  created: 2015-10-01 13:11:11 merged: 2015-10-05 10:06:28

48. [11526](http://github.com/cms-sw/cmssw/pull/11526){:target="_blank"}  from **@Soureek89**: Changing the name of the path HLT_Ele23_WPLoose_Gsf_CentralPFJet30_BTagCVS07_v1 to HLT_Ele23_WPLoose_Gsf_CentralPFJet30_BTagCSV07_v1 (cvs -> csv) `dqm`  created: 2015-09-28 13:44:21 merged: 2015-10-04 17:31:14

49. [11492](http://github.com/cms-sw/cmssw/pull/11492){:target="_blank"}  from **@VinInn**: add triplets using TOB and TIB4  for redundancy in TobTec and PIxelLess seeding steps respectively. reduce chi2-cut in MuonInOut `reconstruction`  created: 2015-09-25 14:21:02 merged: 2015-10-04 12:26:24

50. [11602](http://github.com/cms-sw/cmssw/pull/11602){:target="_blank"}  from **@geonmo**: Add GEM geometry v7 and v7_10deg version to gemGeometryCustoms.py `geometry`  created: 2015-10-01 15:54:30 merged: 2015-10-04 12:26:10

51. [11394](http://github.com/cms-sw/cmssw/pull/11394){:target="_blank"}  from **@blinkseb**: Fix crash in pat::MET when no Type-I uncertainties are added `analysis`  created: 2015-09-21 11:30:55 merged: 2015-10-04 12:23:47

52. [10564](http://github.com/cms-sw/cmssw/pull/10564){:target="_blank"}  from **@bartosik-desy**: Introduced plugin for generator-level tt+X event categorisation `analysis`  created: 2015-08-04 13:48:20 merged: 2015-10-04 12:21:38

53. [11596](http://github.com/cms-sw/cmssw/pull/11596){:target="_blank"}  from **@ndaci**: Added paths that are removde JetIdCleaned suffix (MonoJet, PhotonMET, `dqm`  created: 2015-10-01 13:54:02 merged: 2015-10-04 12:21:24

54. [11622](http://github.com/cms-sw/cmssw/pull/11622){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx35 Testing HGCal Geometry and Topology `geometry`  created: 2015-10-02 11:54:15 merged: 2015-10-04 12:21:13

55. [11610](http://github.com/cms-sw/cmssw/pull/11610){:target="_blank"}  from **@Dr15Jones**: Removed use of '#define private public' for testing `core`  created: 2015-10-01 18:47:09 merged: 2015-10-04 12:18:42

56. [11580](http://github.com/cms-sw/cmssw/pull/11580){:target="_blank"}  from **@mojoe137**: Add pcc info to WBM text file and update PCC x-section `dqm`  created: 2015-09-30 21:40:53 merged: 2015-10-02 17:10:23

57. [11606](http://github.com/cms-sw/cmssw/pull/11606){:target="_blank"}  from **@davidlt**: Do not use private 'XrdCl::FileSystem::FileSystem(const XrdCl::FileSystem&) `core`  created: 2015-10-01 16:47:36 merged: 2015-10-02 17:08:53

58. [11623](http://github.com/cms-sw/cmssw/pull/11623){:target="_blank"}  from **@smuzaffar**: update release deps check script `core`  created: 2015-10-02 12:29:41 merged: 2015-10-02 15:27:52

59. [11248](http://github.com/cms-sw/cmssw/pull/11248){:target="_blank"}  from **@jhgoh**: Do not use CSC Bad Chambers list during muon reconstruction `simulation`  created: 2015-09-14 22:03:46 merged: 2015-10-02 08:51:42

60. [11577](http://github.com/cms-sw/cmssw/pull/11577){:target="_blank"}  from **@lgray**: Convert NjettinessAdder to edm::stream `reconstruction`  created: 2015-09-30 15:50:27 merged: 2015-10-02 08:16:09

61. [11562](http://github.com/cms-sw/cmssw/pull/11562){:target="_blank"}  from **@Dr15Jones**: Removed inappropriate use of SerialTaskQueue from ClusterShapeLazyGetter `reconstruction`  created: 2015-09-29 17:57:22 merged: 2015-10-02 08:11:22

62. [11587](http://github.com/cms-sw/cmssw/pull/11587){:target="_blank"}  from **@Martin-Grunewald**: Addition of PFMET to Trigger Data Formats (76X) `hlt`  created: 2015-10-01 07:46:04 merged: 2015-10-02 08:11:12

63. [11611](http://github.com/cms-sw/cmssw/pull/11611){:target="_blank"}  from **@gartung**: add concurrent_unordered_map to list of safe class name `core`  created: 2015-10-01 19:58:02 merged: 2015-10-02 08:06:10

64. [11595](http://github.com/cms-sw/cmssw/pull/11595){:target="_blank"}  from **@davidlt**: [RFC] Removal of 'evtgenlhc' external (EvtGenLHC91, EvtGenLHCInterface) `generators`  created: 2015-10-01 13:43:03 merged: 2015-10-01 18:41:29

65. [11081](http://github.com/cms-sw/cmssw/pull/11081){:target="_blank"}  from **@cms-analysis-tools**: Improved handling of slimmedGenJets in JetFlavour and GenHFHadronMatcher `analysis`  created: 2015-09-02 11:24:31 merged: 2015-10-01 18:36:53

66. [11507](http://github.com/cms-sw/cmssw/pull/11507){:target="_blank"}  from **@igv4321**: Permanently enabling method 3 `reconstruction`  created: 2015-09-26 04:40:59 merged: 2015-10-01 10:41:38

67. [11120](http://github.com/cms-sw/cmssw/pull/11120){:target="_blank"}  from **@apfeiffer1**: fix conversion to XML for objects with template names `db`  created: 2015-09-04 09:33:58 merged: 2015-10-01 10:36:53

68. [11519](http://github.com/cms-sw/cmssw/pull/11519){:target="_blank"}  from **@davidlt**: Remove -Werror=unused-variable to downgrade errors from CLHEP `reconstruction`  created: 2015-09-28 10:06:30 merged: 2015-10-01 10:36:37

69. [11510](http://github.com/cms-sw/cmssw/pull/11510){:target="_blank"}  from **@fwyzard**: hltDiff: compare TriggerResults event by event (76x) `hlt`  created: 2015-09-26 10:39:10 merged: 2015-10-01 10:31:53

70. [11571](http://github.com/cms-sw/cmssw/pull/11571){:target="_blank"}  from **@makortel**: Update tracking MC validation scripts `dqm`  created: 2015-09-30 14:06:47 merged: 2015-10-01 10:31:42

#### CMSDIST Changes between Tags REL/CMSSW_7_6_0_pre6/slc6_amd64_gcc493 and REL/CMSSW_7_6_0_pre7/slc6_amd64_gcc493:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_6_0_pre6/slc6_amd64_gcc493...REL/CMSSW_7_6_0_pre7/slc6_amd64_gcc493)



1. [1878](http://github.com/cms-sw/cmsdist/pull/1878){:target="_blank"}  from **@degano**: Revert version of matplotlib pending investigations. created: 2015-10-09 11:51:15 merged: 2015-10-09 11:51:19

2. [1874](http://github.com/cms-sw/cmsdist/pull/1874){:target="_blank"}  from **@ijazahmad722**: add python package requests created: 2015-10-08 09:33:25 merged: 2015-10-08 09:50:40

3. [1871](http://github.com/cms-sw/cmsdist/pull/1871){:target="_blank"}  from **@degano**: Remove evtgenlhc from externals. created: 2015-10-06 08:20:30 merged: 2015-10-06 08:20:34

4. [1862](http://github.com/cms-sw/cmsdist/pull/1862){:target="_blank"}  from **@degano**: Update matplotlib to version 1.4.3. Add py2-six py2-pyparsing required. created: 2015-10-02 10:39:22 merged: 2015-10-02 12:28:58

5. [1861](http://github.com/cms-sw/cmsdist/pull/1861){:target="_blank"}  from **@degano**: Advance tip of xrootd to pick up patch. created: 2015-10-02 08:27:01 merged: 2015-10-02 08:27:05

6. [1859](http://github.com/cms-sw/cmsdist/pull/1859){:target="_blank"}  from **@degano**: Update root to pick up FBO getters fix. created: 2015-10-01 08:21:33 merged: 2015-10-01 08:21:36
