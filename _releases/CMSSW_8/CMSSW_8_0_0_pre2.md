---
layout: post
rel_link:  "8_0_0_pre2"
title:  "CMSSW_8_0_0_pre2"
date:   2015-11-16 17:43:18
categories: cmssw
relmajor: 8
relminor: 0
relsubminor: 0
relpre: _pre2
---

# CMSSW_8_0_0_pre2
#### Changes since CMSSW_8_0_0_pre1:

:arrow_right: Merge due to automatic forward port
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_0_0_pre1...CMSSW_8_0_0_pre2)



1. [12430](http://github.com/cms-sw/cmssw/pull/12430){:target="_blank"}  from **@davidlange6**: PackedCandidates.. comment out parts of unit test that are not expected to work given that data are packed upon creation with precision loss `analysis`  `comparison`  `reconstruction`  created: 2015-11-16 11:18:08 merged: 2015-11-16 12:25:44

2. [12429](http://github.com/cms-sw/cmssw/pull/12429){:target="_blank"}  from **@hdelanno**: Fix the way the folder is handled in SiPixelHLT in 8_0_X `dqm`  created: 2015-11-16 11:12:57 merged: 2015-11-16 17:11:25

3. [12420](http://github.com/cms-sw/cmssw/pull/12420){:target="_blank"}  from **@wmtan**: Remove obsolete conditional compilations in Framework only `comparison`  `core`  created: 2015-11-14 00:01:29 merged: 2015-11-16 17:08:07

4. [12418](http://github.com/cms-sw/cmssw/pull/12418){:target="_blank"}  from **@wmtan**: Make dependency messages consistent with other reports `core`  created: 2015-11-13 19:59:41 merged: 2015-11-14 06:23:06

5. [12416](http://github.com/cms-sw/cmssw/pull/12416){:target="_blank"}  from **@rrabadan**: missing-, inactive-, valid-hits and clusterChargePerCm trackerMaps `dqm`  created: 2015-11-13 17:56:16 merged: 2015-11-16 17:11:38

6. [12407](http://github.com/cms-sw/cmssw/pull/12407){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx49 First attempt of hexagonal geometry for HGCal `geometry`  created: 2015-11-12 21:34:51 merged: 2015-11-16 13:11:56

7. [12403](http://github.com/cms-sw/cmssw/pull/12403){:target="_blank"}  from **@lveldere**: fastsim: use fastsim era to define fastsim customs to mixing `fastsim`  `operations`  `simulation`  created: 2015-11-12 15:02:58 merged: 2015-11-15 10:09:23

8. [12402](http://github.com/cms-sw/cmssw/pull/12402){:target="_blank"}  from **@deguio**: fix harvesting T0 `operations`  created: 2015-11-12 13:27:26 merged: 2015-11-13 06:59:57

9. [12396](http://github.com/cms-sw/cmssw/pull/12396){:target="_blank"}  from **@lveldere**: FastSim/Configuration: remove outdated documentation and tests `fastsim`  created: 2015-11-12 10:37:56 merged: 2015-11-12 19:56:15

10. [12394](http://github.com/cms-sw/cmssw/pull/12394){:target="_blank"}  from **@diguida**: Fix for the reconnect-each-run policy in CondDBESSource 80X `db`  created: 2015-11-12 09:29:00 merged: 2015-11-16 17:11:49

11. [12391](http://github.com/cms-sw/cmssw/pull/12391){:target="_blank"}  from **@makortel**: Another fix to TrackingVertex->TrackingParticle links in premixing `simulation`  created: 2015-11-12 08:57:30 merged: 2015-11-14 06:24:21

12. [12390](http://github.com/cms-sw/cmssw/pull/12390){:target="_blank"}  from **@davidlt**: Use ExtVec on PPC64LE `reconstruction`  created: 2015-11-12 08:24:53 merged: 2015-11-12 21:25:23

13. [12389](http://github.com/cms-sw/cmssw/pull/12389){:target="_blank"}  from **@Dr15Jones**: Consolidated framework thread_local into one package `core`  created: 2015-11-11 22:50:22 merged: 2015-11-13 07:00:17

14. [12387](http://github.com/cms-sw/cmssw/pull/12387){:target="_blank"}  from **@forthommel**: Updated SiStrip unpacker (new FED readout modes) `reconstruction`  created: 2015-11-11 21:47:12 merged: 2015-11-16 07:46:16

15. [12380](http://github.com/cms-sw/cmssw/pull/12380){:target="_blank"}  from **@gouskos**: additional dqm plot for the pixel barrel occupancy vs module and ladd `dqm`  created: 2015-11-11 15:43:23 merged: 2015-11-16 17:11:58

16. [12376](http://github.com/cms-sw/cmssw/pull/12376){:target="_blank"}  from **@wmtan**: Fix FileInPath test in FWCore/PythonParameterSet `core`  created: 2015-11-11 15:08:02 merged: 2015-11-12 06:46:11
- :arrow_right: #12367 from **@davidlange6**: PackedCandidate restore old behavior `analysis`  `comparison` 

17. [12365](http://github.com/cms-sw/cmssw/pull/12365){:target="_blank"}  from **@gartung**: update symbols.py to produce reasonable dot graphs `core`  created: 2015-11-10 19:55:34 merged: 2015-11-12 06:51:10

18. [12362](http://github.com/cms-sw/cmssw/pull/12362){:target="_blank"}  from **@davidlt**: Remove -1 from ClassVersionID field in selection rules `reconstruction`  `simulation`  created: 2015-11-10 18:04:36 merged: 2015-11-12 06:56:10

19. [12361](http://github.com/cms-sw/cmssw/pull/12361){:target="_blank"}  from **@mark-grimes**: phase1Pixel era digi to/from raw additions `comparison`  `operations`  created: 2015-11-10 17:50:52 merged: 2015-11-12 06:53:04

20. [12360](http://github.com/cms-sw/cmssw/pull/12360){:target="_blank"}  from **@wmtan**: Fix hi relvals `analysis`  `comparison`  `generators`  `simulation`  created: 2015-11-10 17:38:04 merged: 2015-11-11 08:29:23

21. [12359](http://github.com/cms-sw/cmssw/pull/12359){:target="_blank"}  from **@mark-grimes**: phase1Pixel era validation additions `comparison`  `dqm`  created: 2015-11-10 17:03:09 merged: 2015-11-12 07:31:48

22. [12358](http://github.com/cms-sw/cmssw/pull/12358){:target="_blank"}  from **@mbandrews**: Fix Pedestal EB RMS threshold. Add chi2 cut on DQM timing. `comparison`  `dqm`  created: 2015-11-10 16:54:00 merged: 2015-11-16 17:10:13

23. [12353](http://github.com/cms-sw/cmssw/pull/12353){:target="_blank"}  from **@rkunnawa**: HIN Jet DQM/Validation in 80X, with removing commented out code `dqm`  created: 2015-11-10 16:10:30 merged: 2015-11-11 14:21:35

24. [12352](http://github.com/cms-sw/cmssw/pull/12352){:target="_blank"}  from **@mmusich**: Updating JEC in data/mc and fixes for HI `alca`  created: 2015-11-10 15:28:32 merged: 2015-11-11 08:31:14

25. [12350](http://github.com/cms-sw/cmssw/pull/12350){:target="_blank"}  from **@ianna**: Castor 2015 Scenarios `db`  `geometry`  created: 2015-11-10 14:46:53 merged: 2015-11-16 17:12:09

26. [12347](http://github.com/cms-sw/cmssw/pull/12347){:target="_blank"}  from **@vandreev11**: fix for testHGCalLocalReco script `reconstruction`  created: 2015-11-10 14:14:09 merged: 2015-11-11 08:31:24

27. [12342](http://github.com/cms-sw/cmssw/pull/12342){:target="_blank"}  from **@vanbesien**: Replaced the contents of the fed config by fedtest `dqm`  created: 2015-11-10 11:10:29 merged: 2015-11-10 19:41:34

28. [12337](http://github.com/cms-sw/cmssw/pull/12337){:target="_blank"}  from **@goni**: Cmssw 80x dqm histo range fix for HI `dqm`  created: 2015-11-10 10:54:21 merged: 2015-11-11 08:31:30

29. [12332](http://github.com/cms-sw/cmssw/pull/12332){:target="_blank"}  from **@gartung**: clangSA update symbols.py script and fix potential bug in fixAnonNS(). `core`  created: 2015-11-10 03:18:50 merged: 2015-11-10 08:56:15
- :arrow_right: #12331 from **@mdhildreth**: Add 25ns scenario for Fall 2015 MC to match data `operations`  `simulation` 

30. [12330](http://github.com/cms-sw/cmssw/pull/12330){:target="_blank"}  from **@Dr15Jones**: Fix problem in edmStreamStallGrapher `core`  created: 2015-11-10 00:54:46 merged: 2015-11-10 09:01:14
- :arrow_right: #12329 from **@fwyzard**: ignore empty paths when determining the first and last [End]Path `hlt` 
- :arrow_right: #12324 from **@kpedro88**: save particleFlowRecHitHBHE and particleFlowRecHitHF collections `reconstruction` 

31. [12322](http://github.com/cms-sw/cmssw/pull/12322){:target="_blank"}  from **@davidlt**: Fix temporaries in the header `dqm`  created: 2015-11-09 16:09:18 merged: 2015-11-10 17:02:31

32. [12319](http://github.com/cms-sw/cmssw/pull/12319){:target="_blank"}  from **@ianna**: HGCal DB Geometry Reader `db`  `geometry`  created: 2015-11-09 15:20:28 merged: 2015-11-12 07:31:11

33. [12313](http://github.com/cms-sw/cmssw/pull/12313){:target="_blank"}  from **@hroskes**: Fix systematic misalignment tool `alca`  created: 2015-11-08 18:42:05 merged: 2015-11-10 09:01:24
- :arrow_right: #12311 from **@srimanob**: fix FlatPU prob. `simulation` 

34. [12309](http://github.com/cms-sw/cmssw/pull/12309){:target="_blank"}  from **@mkirsano**: clean LHEInterface: remove files that are not compiled `generators`  created: 2015-11-07 17:09:31 merged: 2015-11-08 12:56:11

35. [12307](http://github.com/cms-sw/cmssw/pull/12307){:target="_blank"}  from **@VinInn**: Stateless clusterizer for SiStrip `reconstruction`  created: 2015-11-07 15:19:42 merged: 2015-11-12 06:51:24
- :arrow_right: #12305 from **@lathomas**: Reload calogeometry for every event:  `reconstruction` 
- :arrow_right: #12303 from **@wmtan**: Fix heavy ion relval tests `analysis`  `generators`  `simulation` 

36. [12301](http://github.com/cms-sw/cmssw/pull/12301){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-hcx47 Add trigger primitive version in geometry `geometry`  created: 2015-11-06 22:32:50 merged: 2015-11-11 08:36:24

37. [12300](http://github.com/cms-sw/cmssw/pull/12300){:target="_blank"}  from **@kpedro88**: save particleFlowRecHitHBHE and particleFlowRecHitHF collections `reconstruction`  created: 2015-11-06 20:42:53 merged: 2015-11-10 09:01:34
- :arrow_right: #12299 from **@gpetruc**: MuonAnalysis/MuonAssociators: getByToken in TriggerObjectFilterByCollection `analysis`  `comparison` 

38. [12297](http://github.com/cms-sw/cmssw/pull/12297){:target="_blank"}  from **@fratnikov**: data mixer tuning for HCAL and ECAL `operations`  `simulation`  created: 2015-11-06 19:20:18 merged: 2015-11-10 08:57:48
- :arrow_right: #12296 from **@mariadalfonso**: Met uncertainties from GT: remove txt file dependency `analysis` 

39. [12294](http://github.com/cms-sw/cmssw/pull/12294){:target="_blank"}  from **@fabozzi**: replacing 2012 relval with 2015 relval for reduced matrix tests `pdmv`  created: 2015-11-06 17:48:10 merged: 2015-11-08 13:01:09
- :arrow_right: #12293 from **@fabozzi**: replacing 2012 relval with 2015 relval for reduced matrix tests `pdmv` 
- :arrow_right: #12281 from **@ghellwig**: Fix bug in caching of surface deformations. `alca` 

40. [12277](http://github.com/cms-sw/cmssw/pull/12277){:target="_blank"}  from **@smorovic**: Fix race condition in DAQ modules for 80X (make new PR) `daq`  `reconstruction`  created: 2015-11-05 17:59:54 merged: 2015-11-12 06:51:29

41. [12275](http://github.com/cms-sw/cmssw/pull/12275){:target="_blank"}  from **@mark-grimes**: phase1Pixel era digitisation additions `comparison`  `simulation`  created: 2015-11-05 16:44:57 merged: 2015-11-12 07:31:27

42. [12269](http://github.com/cms-sw/cmssw/pull/12269){:target="_blank"}  from **@ggovi**: Clean up from conddb V1 code `alca`  `db`  `dqm`  created: 2015-11-05 14:12:07 merged: 2015-11-12 06:51:36

43. [12266](http://github.com/cms-sw/cmssw/pull/12266){:target="_blank"}  from **@ggovi**: Fix for conddb python tools `db`  created: 2015-11-05 10:49:00 merged: 2015-11-12 06:51:41
- :arrow_right: #12257 from **@bbockelm**: Provide a utility for efficiently copying multiple files to the local `core` 
- :arrow_right: #12236 from **@friccita**: corrected wrong cfi file called for PhaseIPixel tag in dumpSimGeometry_cfg.py `comparison`  `visualization` 
- :arrow_right: #12230 from **@istaslis**: Set mva tight value of initial step to be equal to highPurity mva (76X version of #12223) `reconstruction` 
- :arrow_right: #12060 from **@ferencek**: Updated logic in HadronAndPartonSelector `analysis` 

44. [11910](http://github.com/cms-sw/cmssw/pull/11910){:target="_blank"}  from **@sachikot**: SCAL online DQM monitoring `dqm`  created: 2015-10-19 08:09:54 merged: 2015-11-10 19:45:44

45. [11909](http://github.com/cms-sw/cmssw/pull/11909){:target="_blank"}  from **@fioriNTU**: Fix TrackSplit module `comparison`  `dqm`  created: 2015-10-19 08:09:37 merged: 2015-11-10 19:46:10

46. [11892](http://github.com/cms-sw/cmssw/pull/11892){:target="_blank"}  from **@JetMETdqmval**: update PFJetID for RunII, add ak8 MiniAOD monitoring, adopt ak4CHS JEC for type1 MET `analysis`  `dqm`  created: 2015-10-19 07:24:37 merged: 2015-11-16 07:49:10

47. [11879](http://github.com/cms-sw/cmssw/pull/11879){:target="_blank"}  from **@bsunanda**: bsunanda:Run2 hcx43 Modify the scripts (Salavat) for pion scans `comparison`  `dqm`  created: 2015-10-19 07:23:16 merged: 2015-11-10 19:48:15
- :arrow_right: #11612 from **@cms-btv-pog**: Updated flavor parton selection for Pythia8 `analysis`  `comparison` 

#### CMSDIST Changes between Tags REL/CMSSW_8_0_0_pre1/slc6_amd64_gcc493 and REL/CMSSW_8_0_0_pre2/slc6_amd64_gcc493:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_0_0_pre1/slc6_amd64_gcc493...REL/CMSSW_8_0_0_pre2/slc6_amd64_gcc493)



1. [1963](http://github.com/cms-sw/cmsdist/pull/1963){:target="_blank"}  from **@smuzaffar**: update branch and tag in  root.spec created: 2015-11-14 13:32:32 merged: 2015-11-14 13:32:40

2. [1962](http://github.com/cms-sw/cmsdist/pull/1962){:target="_blank"}  from **@degano**: Update sherpa to version 2.2.0 with CMS patches. created: 2015-11-13 14:07:55 merged: 2015-11-16 09:35:36

3. [1960](http://github.com/cms-sw/cmsdist/pull/1960){:target="_blank"}  from **@iahmad-khan**: added new davix tool created: 2015-11-13 10:47:37 merged: 2015-11-14 13:08:25

4. [1955](http://github.com/cms-sw/cmsdist/pull/1955){:target="_blank"}  from **@degano**: Update pythia8 to include Heavy other matching patch. created: 2015-11-12 09:49:22 merged: 2015-11-13 08:38:31

5. [1954](http://github.com/cms-sw/cmsdist/pull/1954){:target="_blank"}  from **@degano**: Update Openloops to CMS version 1.2.3. created: 2015-11-12 09:45:00 merged: 2015-11-13 08:41:10
