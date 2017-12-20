---
layout: post
rel_link:  "7_4_1"
title:  "CMSSW_7_4_1"
date:   2015-04-25 08:23:45
categories: cmssw
relmajor: 7
relminor: 4
relsubminor: 1
---

# CMSSW_7_4_1
#### Changes since CMSSW_7_4_0:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_4_0...CMSSW_7_4_1)



1. [8872](http://github.com/cms-sw/cmssw/pull/8872){:target="_blank"}  from **@diguida**: Update to simplified ecal pfcluster corrections on top of new Global Tags for PF corrections plus fixes for Run2 MC production `alca`  `reconstruction`  created: 2015-04-24 09:35:51 merged: 2015-04-25 08:16:49

2. [8862](http://github.com/cms-sw/cmssw/pull/8862){:target="_blank"}  from **@bbockelm**: Allow local file system detection to handle bind mounts. `core`  created: 2015-04-24 01:26:46 merged: 2015-04-24 08:35:07

3. [8861](http://github.com/cms-sw/cmssw/pull/8861){:target="_blank"}  from **@Dr15Jones**: Fixed use of hash filename `simulation`  created: 2015-04-23 23:15:19 merged: 2015-04-24 08:34:39

4. [8796](http://github.com/cms-sw/cmssw/pull/8796){:target="_blank"}  from **@ahinzmann**: Add CaloJet pT to MiniAOD `analysis`  created: 2015-04-20 15:28:10 merged: 2015-04-24 08:19:24

5. [8419](http://github.com/cms-sw/cmssw/pull/8419){:target="_blank"}  from **@cwohrman**: add castor lowPTjet trigger and reweight threshold via gain v2 `simulation`  created: 2015-03-19 17:38:03 merged: 2015-04-24 07:47:12

6. [8800](http://github.com/cms-sw/cmssw/pull/8800){:target="_blank"}  from **@lveldere**: FastSim: 74X: bug fix: use same tau DQM plot harvester as FullSim `dqm`  `reconstruction`  `simulation`  created: 2015-04-20 16:33:04 merged: 2015-04-23 17:45:13

7. [8843](http://github.com/cms-sw/cmssw/pull/8843){:target="_blank"}  from **@arizzi**: MINIAOD BUGFIX: pvREF not set for some electrons `analysis`  `reconstruction`  created: 2015-04-23 07:35:05 merged: 2015-04-23 17:25:04

8. [8840](http://github.com/cms-sw/cmssw/pull/8840){:target="_blank"}  from **@cms-l1t-offline**: update L1TRCTParameters for FGCut,HOECut, and EIC Isolation `l1`  created: 2015-04-22 23:49:49 merged: 2015-04-23 16:59:30

9. [8838](http://github.com/cms-sw/cmssw/pull/8838){:target="_blank"}  from **@rappoccio**: Backport from #8837 : Index bug in miniAOD substructure jets `analysis`  created: 2015-04-22 21:12:37 merged: 2015-04-23 16:21:38

10. [8805](http://github.com/cms-sw/cmssw/pull/8805){:target="_blank"}  from **@igv4321**: Hcal noise filters backport `reconstruction`  `simulation`  created: 2015-04-21 00:07:57 merged: 2015-04-23 13:01:15

11. [8847](http://github.com/cms-sw/cmssw/pull/8847){:target="_blank"}  from **@batinkov**: The script dqmdata_cleaner.py is deleted. `dqm`  created: 2015-04-23 08:36:25 merged: 2015-04-23 12:29:00

12. [8831](http://github.com/cms-sw/cmssw/pull/8831){:target="_blank"}  from **@deguio**: avoid having axis resized for LogMessageMonitor `dqm`  created: 2015-04-22 16:11:12 merged: 2015-04-23 12:12:12

13. [8781](http://github.com/cms-sw/cmssw/pull/8781){:target="_blank"}  from **@cms-tsg-storm**: HLT: Fixes and rationalisation/reuse of cfg files for tests `core`  `fastsim`  `hlt`  created: 2015-04-19 19:25:24 merged: 2015-04-22 14:44:19

14. [8820](http://github.com/cms-sw/cmssw/pull/8820){:target="_blank"}  from **@cms-l1t-offline**: update FW version to latest HW `l1`  created: 2015-04-22 05:03:34 merged: 2015-04-22 14:11:38

15. [8779](http://github.com/cms-sw/cmssw/pull/8779){:target="_blank"}  from **@sushilchauhan**: firststep and pixel tracking for 74X and minor fixes as for 73X `dqm`  created: 2015-04-18 17:44:56 merged: 2015-04-22 14:07:05

16. [8765](http://github.com/cms-sw/cmssw/pull/8765){:target="_blank"}  from **@fwyzard**: migrate more modules to be multi-thread safe `analysis`  `hlt`  `reconstruction`  created: 2015-04-17 03:15:08 merged: 2015-04-21 18:51:23

17. [8768](http://github.com/cms-sw/cmssw/pull/8768){:target="_blank"}  from **@fwyzard**: edmPluginHelp: differentiate thread-safe from legacy output modules `core`  created: 2015-04-17 07:40:12 merged: 2015-04-21 16:11:53

18. [8612](http://github.com/cms-sw/cmssw/pull/8612){:target="_blank"}  from **@abbiendi**: Backport to 74X of PR #8199 (cosmicMuonValidation) `dqm`  `reconstruction`  `simulation`  created: 2015-03-31 12:02:03 merged: 2015-04-21 16:09:49

19. [8720](http://github.com/cms-sw/cmssw/pull/8720){:target="_blank"}  from **@emanueledimarco**: Disable Not Working leading edge recovery for saturated ECAL RecHits (7_4_X back-port) `reconstruction`  created: 2015-04-14 08:14:20 merged: 2015-04-21 16:09:33

20. [8760](http://github.com/cms-sw/cmssw/pull/8760){:target="_blank"}  from **@emanueledimarco**: ECAL unpacker: consider the ADC hysteresis in the gain switches (back-port to 74X) `reconstruction`  created: 2015-04-16 10:48:30 merged: 2015-04-21 16:09:23

21. [8773](http://github.com/cms-sw/cmssw/pull/8773){:target="_blank"}  from **@mmarionncern**: Update PF hadron calibration code `reconstruction`  created: 2015-04-17 14:23:48 merged: 2015-04-21 16:09:03

22. [8776](http://github.com/cms-sw/cmssw/pull/8776){:target="_blank"}  from **@silviodonato**: Adding of HLT2PhotonMET `hlt`  created: 2015-04-17 15:32:34 merged: 2015-04-21 16:08:54

23. [8806](http://github.com/cms-sw/cmssw/pull/8806){:target="_blank"}  from **@mdhildreth**: 74X: Set noise off in ES for PreMixing step `simulation`  created: 2015-04-21 00:16:09 merged: 2015-04-21 16:08:21

24. [8755](http://github.com/cms-sw/cmssw/pull/8755){:target="_blank"}  from **@rappoccio**: Fixing reversed distance in accessing subjet collections `analysis`  created: 2015-04-15 19:18:31 merged: 2015-04-21 16:06:15

25. [8757](http://github.com/cms-sw/cmssw/pull/8757){:target="_blank"}  from **@deguio**: fix typo in the definition of the T0 sequences for tracking `dqm`  created: 2015-04-16 10:18:42 merged: 2015-04-21 16:06:06

26. [8750](http://github.com/cms-sw/cmssw/pull/8750){:target="_blank"}  from **@slava77**:  bug fixes in CSC (ME11) trigger primitives for re-emulation; fix ME11 selective readout (fw port of 73X #8664 ) `l1`  `reconstruction`  created: 2015-04-15 15:08:44 merged: 2015-04-21 16:03:57

27. [8689](http://github.com/cms-sw/cmssw/pull/8689){:target="_blank"}  from **@elaird**: add feds `reconstruction`  created: 2015-04-09 11:41:47 merged: 2015-04-16 00:16:51

28. [8722](http://github.com/cms-sw/cmssw/pull/8722){:target="_blank"}  from **@arizzi**: Fix bug in PVAssignment: missing abs for dxy `reconstruction`  created: 2015-04-14 09:10:42 merged: 2015-04-16 00:04:47

29. [8746](http://github.com/cms-sw/cmssw/pull/8746){:target="_blank"}  from **@franzoni**: PU scenarios for TSG RunIISpring15DR74x `operations`  `simulation`  created: 2015-04-15 05:54:04 merged: 2015-04-16 00:04:00

30. [8724](http://github.com/cms-sw/cmssw/pull/8724){:target="_blank"}  from **@bachtis**: Added protection for negative HCAL energy in presence of HO causing NAN in PF `reconstruction`  created: 2015-04-14 10:19:44 merged: 2015-04-14 22:21:07

31. [8568](http://github.com/cms-sw/cmssw/pull/8568){:target="_blank"}  from **@gpetruc**:   Fix logic of tev muon track embedding code (74X version of #8568) `analysis`  created: 2015-03-27 15:11:37 merged: 2015-04-14 06:34:52

32. [8697](http://github.com/cms-sw/cmssw/pull/8697){:target="_blank"}  from **@suchandradutta**: Bug fix in SiStripHotStripAlgorithmFromClusterOccupancy and update on README `alca`  created: 2015-04-10 14:14:07 merged: 2015-04-14 06:34:37

33. [8693](http://github.com/cms-sw/cmssw/pull/8693){:target="_blank"}  from **@cms-tsg-storm**: A few HLT integrations and bug fixes on top of CMSSW_7_4_0 `hlt`  created: 2015-04-10 11:07:22 merged: 2015-04-14 06:26:45

34. [8663](http://github.com/cms-sw/cmssw/pull/8663){:target="_blank"}  from **@wmtan**: fix memory leaks in FastTSGFromPropagation `fastsim`  created: 2015-04-03 22:03:19 merged: 2015-04-07 08:35:22

35. [8585](http://github.com/cms-sw/cmssw/pull/8585){:target="_blank"}  from **@lveldere**: FastSim bugfix for gtDigis (7_4_X) `dqm`  `fastsim`  created: 2015-03-30 09:02:42 merged: 2015-04-02 10:41:54

#### CMSDIST Changes between Tags REL/CMSSW_7_4_0/slc6_amd64_gcc491 and REL/CMSSW_7_4_1/slc6_amd64_gcc491:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_4_0/slc6_amd64_gcc491...REL/CMSSW_7_4_1/slc6_amd64_gcc491)



1. [1507](http://github.com/cms-sw/cmsdist/pull/1507){:target="_blank"}  from **@davidlt**: Fix broken auto-forward port created: 2015-04-22 10:18:03 merged: 2015-04-22 10:18:21

2. [1503](http://github.com/cms-sw/cmsdist/pull/1503){:target="_blank"}  from **@davidlt**: root: incl. ROOT-7245 bugfix created: 2015-04-22 07:40:38 merged: 2015-04-22 07:57:05
