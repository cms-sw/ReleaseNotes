---
layout: post
rel_link:  "8_0_9"
title:  "CMSSW_8_0_9"
date:   2016-05-29 20:04:09
categories: cmssw
relmajor: 8
relminor: 0
relsubminor: 9
---

# CMSSW_8_0_9
#### Changes since CMSSW_8_0_8_patch2:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_0_8_patch2...CMSSW_8_0_9)



1. [14677](http://github.com/cms-sw/cmssw/pull/14677){:target="_blank"}  from **@slava77**: cleanup RawToDigi redefinition of already loaded from RawToDigi_cff (bp of #14675) `operations`  created: 2016-05-28 01:21:14 merged: 2016-05-29 20:01:57

2. [14662](http://github.com/cms-sw/cmssw/pull/14662){:target="_blank"}  from **@VinInn**: fix crash in case Limit on the number of clusters is really exceeded. `reconstruction`  created: 2016-05-27 14:10:11 merged: 2016-05-27 18:22:02

3. [14658](http://github.com/cms-sw/cmssw/pull/14658){:target="_blank"}  from **@ggovi**: Fix for handling copy of offline synchronized tags `db`  created: 2016-05-27 12:32:55 merged: 2016-05-29 19:58:41

4. [14650](http://github.com/cms-sw/cmssw/pull/14650){:target="_blank"}  from **@cms-l1t-offline**: Restore overflow check for et and ht sums `l1`  created: 2016-05-26 22:54:34 merged: 2016-05-27 08:39:07

5. [14647](http://github.com/cms-sw/cmssw/pull/14647){:target="_blank"}  from **@cms-l1t-offline**: Adding L1REPACK:FullMC workflow to run on RAW of MC (80x) `operations`  created: 2016-05-26 16:26:25 merged: 2016-05-27 07:46:17

6. [14646](http://github.com/cms-sw/cmssw/pull/14646){:target="_blank"}  from **@cms-l1t-offline**: MCprod l1t Tau Iso Option-21 80x `l1`  created: 2016-05-26 16:22:17 merged: 2016-05-27 08:41:16

7. [14617](http://github.com/cms-sw/cmssw/pull/14617){:target="_blank"}  from **@cms-l1t-offline**: Clean-up L1T unpacker warnings `l1`  created: 2016-05-24 10:38:32 merged: 2016-05-24 15:10:43

8. [14613](http://github.com/cms-sw/cmssw/pull/14613){:target="_blank"}  from **@cms-l1t-offline**: Update OMTF treatment of Muons at edge of OMTF acceptance `l1`  created: 2016-05-24 09:55:18 merged: 2016-05-24 15:10:53

9. [14602](http://github.com/cms-sw/cmssw/pull/14602){:target="_blank"}  from **@ndaci**:  Add a cut in the HLTPFJetIDProducer module. `hlt`  created: 2016-05-23 08:34:01 merged: 2016-05-24 15:11:16

10. [14600](http://github.com/cms-sw/cmssw/pull/14600){:target="_blank"}  from **@CTPPS**: CTPPS: new CondFormats related to TOTEM RP raw data and digi - backport of #13838 `alca`  `db`  created: 2016-05-23 08:02:55 merged: 2016-05-27 16:36:28

11. [14596](http://github.com/cms-sw/cmssw/pull/14596){:target="_blank"}  from **@smuzaffar**: Fix for runtestTqafTopEventSelection unit test: use againstElectronVLooseMVA6 instead of againstElectronVLooseMVA5 `analysis`  `reconstruction`  created: 2016-05-21 16:19:30 merged: 2016-05-24 18:53:09

12. [14588](http://github.com/cms-sw/cmssw/pull/14588){:target="_blank"}  from **@duanders**: Use PFMETCollection in scouting PF producer `hlt`  created: 2016-05-20 12:26:11 merged: 2016-05-23 12:12:16

13. [14587](http://github.com/cms-sw/cmssw/pull/14587){:target="_blank"}  from **@duanders**: Fix deltaR calculation in HLT widejet module `hlt`  created: 2016-05-20 11:49:24 merged: 2016-05-22 07:12:34

14. [14583](http://github.com/cms-sw/cmssw/pull/14583){:target="_blank"}  from **@ggovi**: Fix for GTEntry_t hash function `db`  created: 2016-05-20 08:41:20 merged: 2016-05-25 16:26:24

15. [14580](http://github.com/cms-sw/cmssw/pull/14580){:target="_blank"}  from **@CTPPS**: CTPPS: new DataFormats for local TOTEM RP reconstruction, backport of #14134 `reconstruction`  created: 2016-05-19 22:25:50 merged: 2016-05-24 08:14:47

16. [14579](http://github.com/cms-sw/cmssw/pull/14579){:target="_blank"}  from **@CTPPS**: CTPPS: new DataFormats related to TOTEM RP raw data and digi - backport of PR #13837 `reconstruction`  `simulation`  created: 2016-05-19 22:10:55 merged: 2016-05-24 18:54:32

17. [14578](http://github.com/cms-sw/cmssw/pull/14578){:target="_blank"}  from **@CTPPS**: Adding new detectors - integration of RomanPot detectors for CTPPS project - backport of PR #13766 `simulation`  created: 2016-05-19 21:54:25 merged: 2016-05-22 07:15:12

18. [14570](http://github.com/cms-sw/cmssw/pull/14570){:target="_blank"}  from **@cms-l1t-offline**: Update L1T to l1t-tsg-v7-cand performance (80x) `dqm`  `l1`  created: 2016-05-19 10:00:36 merged: 2016-05-23 13:07:07

19. [14568](http://github.com/cms-sw/cmssw/pull/14568){:target="_blank"}  from **@idebruyn**: TH1ClusterCharge and TH1ClusterStoNCorr plots per ring `dqm`  created: 2016-05-19 09:53:38 merged: 2016-05-29 19:58:28

20. [14567](http://github.com/cms-sw/cmssw/pull/14567){:target="_blank"}  from **@dmitrijus**: Disable broken Ewk*DQM modules `dqm`  created: 2016-05-19 09:08:21 merged: 2016-05-22 07:11:59

21. [14566](http://github.com/cms-sw/cmssw/pull/14566){:target="_blank"}  from **@OlivierBondu**: Update ResonanceDecayFilterHook.cc `generators`  created: 2016-05-19 08:07:11 merged: 2016-05-22 07:14:43

22. [14551](http://github.com/cms-sw/cmssw/pull/14551){:target="_blank"}  from **@cms-l1t-offline**: L1 repack 2016 2015 (Full, uGT, Full2015Data) cmssw808 `l1`  `operations`  created: 2016-05-18 12:30:44 merged: 2016-05-23 13:08:37

23. [14531](http://github.com/cms-sw/cmssw/pull/14531){:target="_blank"}  from **@fioriNTU**: retune max value for Chi2 `dqm`  created: 2016-05-17 14:08:24 merged: 2016-05-22 07:13:23

24. [14530](http://github.com/cms-sw/cmssw/pull/14530){:target="_blank"}  from **@rmanzoni**: [RecoTauTag] allow complete relax of tau isolation at high pt `reconstruction`  created: 2016-05-17 13:11:42 merged: 2016-05-22 07:13:02

25. [14528](http://github.com/cms-sw/cmssw/pull/14528){:target="_blank"}  from **@smorovic**: Adding merging type (DAQ) and changing defaults `daq`  `dqm`  `hlt`  `reconstruction`  created: 2016-05-17 09:53:57 merged: 2016-05-22 07:14:19

26. [14512](http://github.com/cms-sw/cmssw/pull/14512){:target="_blank"}  from **@usarica**: Muon analysis updates 8.0.x `alca`  `analysis`  created: 2016-05-16 13:36:35 merged: 2016-05-24 08:41:20

27. [14501](http://github.com/cms-sw/cmssw/pull/14501){:target="_blank"}  from **@bartosik-hep**: 80X: HLT path/module-name updates in the HLTObjectMonitor `dqm`  created: 2016-05-13 21:48:13 merged: 2016-05-23 12:14:04

28. [14477](http://github.com/cms-sw/cmssw/pull/14477){:target="_blank"}  from **@fwyzard**: L1TGlobalProducer: migrate to stream module (80x) `l1`  created: 2016-05-12 14:01:18 merged: 2016-05-23 13:09:20

29. [14467](http://github.com/cms-sw/cmssw/pull/14467){:target="_blank"}  from **@VinInn**: fix det search tollerances for Cosmics `reconstruction`  created: 2016-05-12 05:14:06 merged: 2016-05-24 08:16:32

30. [14462](http://github.com/cms-sw/cmssw/pull/14462){:target="_blank"}  from **@kpedro88**: Monitor CASTOR table data (80X) `alca`  `reconstruction`  `simulation`  created: 2016-05-11 19:55:18 merged: 2016-05-27 08:29:49

31. [14445](http://github.com/cms-sw/cmssw/pull/14445){:target="_blank"}  from **@cms-tsg-storm**: HLT development in May (80X) `alca`  `dqm`  `hlt`  created: 2016-05-11 08:02:14 merged: 2016-05-27 16:38:33

32. [14437](http://github.com/cms-sw/cmssw/pull/14437){:target="_blank"}  from **@ggovi**: Changes for O2O deployment and monitoring `db`  created: 2016-05-10 15:45:03 merged: 2016-05-27 07:41:47

33. [14421](http://github.com/cms-sw/cmssw/pull/14421){:target="_blank"}  from **@diguida**: Fixes for RunInfo O2O and cleanup of PopCon interface (80X) `alca`  `db`  created: 2016-05-09 16:51:24 merged: 2016-05-25 15:52:17

34. [14336](http://github.com/cms-sw/cmssw/pull/14336){:target="_blank"}  from **@Martin-Grunewald**: Prescale access for stage-2 environment (80X) `analysis`  `dqm`  `hlt`  `l1`  `reconstruction`  created: 2016-05-03 07:34:46 merged: 2016-05-29 19:59:22

35. [14265](http://github.com/cms-sw/cmssw/pull/14265){:target="_blank"}  from **@mmusich**: DropBox metadata - 2016 (80X) `alca`  `db`  created: 2016-04-27 07:53:31 merged: 2016-05-23 12:18:29

36. [13972](http://github.com/cms-sw/cmssw/pull/13972){:target="_blank"}  from **@fioriNTU**: improve TkMaps `dqm`  created: 2016-04-07 12:13:48 merged: 2016-05-27 07:42:24

37. [13813](http://github.com/cms-sw/cmssw/pull/13813){:target="_blank"}  from **@vkhristenko**: Online HCAL DQM adding a 3rd application `dqm`  created: 2016-03-23 10:56:21 merged: 2016-05-24 08:20:20

#### CMSDIST Changes between Tags REL/CMSSW_8_0_8_patch2/slc6_amd64_gcc530 and REL/CMSSW_8_0_9/slc6_amd64_gcc530:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_0_8_patch2/slc6_amd64_gcc530...REL/CMSSW_8_0_9/slc6_amd64_gcc530)



1. [2304](http://github.com/cms-sw/cmsdist/pull/2304){:target="_blank"}  from **@cms-sw**: Update data-L1Trigger-L1TMuon.spec created: 2016-05-20 12:41:23 merged: 2016-05-20 12:42:02

2. [2300](http://github.com/cms-sw/cmsdist/pull/2300){:target="_blank"}  from **@degano**: Update CUDA to version 7.5.18 created: 2016-05-18 10:27:54 merged: 2016-05-19 09:12:48
