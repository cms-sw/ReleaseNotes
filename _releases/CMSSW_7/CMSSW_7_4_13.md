---
layout: post
rel_link:  "7_4_13"
title:  "CMSSW_7_4_13"
date:   2015-09-27 19:18:17
categories: cmssw
relmajor: 7
relminor: 4
relsubminor: 13
---

# CMSSW_7_4_13
#### Changes since CMSSW_7_4_12_patch4:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_4_12_patch4...CMSSW_7_4_13)



1. [11109](http://github.com/cms-sw/cmssw/pull/11109){:target="_blank"}  from **@mbandrews**: Tightened timing cut for 25ns runs. Relaxed Pedestal RMS qT threshold `dqm`  created: 2015-09-03 14:04:14 merged: 2015-09-27 13:31:22

2. [10697](http://github.com/cms-sw/cmssw/pull/10697){:target="_blank"}  from **@cms-l1t-offline**:  Add HF Minimum Bias algorithm to Stage1 Emulator (backport 74X #10695) `l1`  created: 2015-08-11 18:04:31 merged: 2015-09-27 09:31:31

3. [11332](http://github.com/cms-sw/cmssw/pull/11332){:target="_blank"}  from **@cms-tsg-storm**: 74X HLT 25ns Round 5 `hlt`  created: 2015-09-18 07:29:46 merged: 2015-09-27 09:31:25

4. [11395](http://github.com/cms-sw/cmssw/pull/11395){:target="_blank"}  from **@ndaci**: Fixed path names. Removed pt2 and pt3 in unnecessary cases. Added debug print (dump # of HLT passed events). Replace "cout" to DebugLog. Updated PhotonMET, PureMET, DiPhoton and HighPtPhoton paths. `dqm`  created: 2015-09-21 12:40:07 merged: 2015-09-27 09:31:19

5. [11026](http://github.com/cms-sw/cmssw/pull/11026){:target="_blank"}  from **@VinInn**: fix histo scales, add ngood vertex `dqm`  created: 2015-08-29 12:17:30 merged: 2015-09-27 07:51:33

6. [11027](http://github.com/cms-sw/cmssw/pull/11027){:target="_blank"}  from **@VinInn**: Add valid,lost,missing inner/outer hits 2d-histos `dqm`  created: 2015-08-29 15:19:47 merged: 2015-09-27 07:51:27

7. [11216](http://github.com/cms-sw/cmssw/pull/11216){:target="_blank"}  from **@aescalante**: Exotica dqm updated histograms `dqm`  created: 2015-09-09 20:31:27 merged: 2015-09-27 07:51:21

8. [11455](http://github.com/cms-sw/cmssw/pull/11455){:target="_blank"}  from **@smorovic**: Freeing INI file buffer after writing the file is finished (74X) `core`  created: 2015-09-24 12:43:17 merged: 2015-09-27 07:46:58

9. [11036](http://github.com/cms-sw/cmssw/pull/11036){:target="_blank"}  from **@ebouvier**: Top trigger names for 25 ns 74X `dqm`  created: 2015-08-31 08:50:41 merged: 2015-09-24 07:51:48

10. [10326](http://github.com/cms-sw/cmssw/pull/10326){:target="_blank"}  from **@deguio**: remove Edm2ME converter from final sequence for harvesting `operations`  created: 2015-07-23 14:05:26 merged: 2015-09-24 07:44:15

11. [11185](http://github.com/cms-sw/cmssw/pull/11185){:target="_blank"}  from **@fioriNTU**:  avoid empty FED occupancy plot in offline Pixel DQM `dqm`  created: 2015-09-08 15:28:26 merged: 2015-09-23 16:29:22

12. [11232](http://github.com/cms-sw/cmssw/pull/11232){:target="_blank"}  from **@lgray**: VID fix & core unit tests + Regression ValueMap Producer code cleanup. (74X) `reconstruction`  created: 2015-09-12 14:19:44 merged: 2015-09-23 16:29:11

13. [11282](http://github.com/cms-sw/cmssw/pull/11282){:target="_blank"}  from **@fcouderc**: add sigmaietaiphi for photon regression inputs (74X) `reconstruction`  created: 2015-09-16 14:12:08 merged: 2015-09-23 16:28:59

14. [11313](http://github.com/cms-sw/cmssw/pull/11313){:target="_blank"}  from **@fwyzard**: ThroughputServiceClient: add more throughput plots `hlt`  created: 2015-09-17 11:02:28 merged: 2015-09-23 16:28:49

15. [11314](http://github.com/cms-sw/cmssw/pull/11314){:target="_blank"}  from **@fwyzard**: DQMStore::removeElement: do not remove non-existing MEs `dqm`  created: 2015-09-17 11:03:37 merged: 2015-09-23 16:28:43

16. [11361](http://github.com/cms-sw/cmssw/pull/11361){:target="_blank"}  from **@drankincms**: Adding new trigger names to B2G DQM `dqm`  created: 2015-09-18 15:42:52 merged: 2015-09-23 16:28:06

17. [11415](http://github.com/cms-sw/cmssw/pull/11415){:target="_blank"}  from **@argiro**: Position calc fix `reconstruction`  created: 2015-09-22 09:22:22 merged: 2015-09-23 16:27:02

18. [11399](http://github.com/cms-sw/cmssw/pull/11399){:target="_blank"}  from **@Dr15Jones**: Change mayConsume to conditional consumes in PATJetProducer `analysis`  created: 2015-09-21 15:55:17 merged: 2015-09-23 16:23:29

19. [11103](http://github.com/cms-sw/cmssw/pull/11103){:target="_blank"}  from **@heppye**: add DQM Validation plots for MSSM Hbb Trigger Paths. `dqm`  created: 2015-09-03 10:33:35 merged: 2015-09-21 10:01:27

20. [11335](http://github.com/cms-sw/cmssw/pull/11335){:target="_blank"}  from **@deguio**: adapt to the new merger logic `dqm`  created: 2015-09-18 10:37:05 merged: 2015-09-20 12:21:26

21. [11369](http://github.com/cms-sw/cmssw/pull/11369){:target="_blank"}  from **@bendavid**: more robust protection against infinite loops in Ecal multifit (74x) `reconstruction`  created: 2015-09-18 18:09:09 merged: 2015-09-20 12:21:15

22. [11164](http://github.com/cms-sw/cmssw/pull/11164){:target="_blank"}  from **@hroskes**: Finally fix segfault! `alca`  created: 2015-09-06 15:46:57 merged: 2015-09-18 10:07:31

23. [11215](http://github.com/cms-sw/cmssw/pull/11215){:target="_blank"}  from **@alja**: 74x Fireworks: Adjust camera position when open 3D region `visualization`  created: 2015-09-09 19:58:37 merged: 2015-09-18 08:12:05

24. [11245](http://github.com/cms-sw/cmssw/pull/11245){:target="_blank"}  from **@smorovic**: Streamer output modules ported to one::OutputModule (74X) `core`  `daq`  `dqm`  `reconstruction`  created: 2015-09-14 13:34:50 merged: 2015-09-17 09:56:49

25. [10583](http://github.com/cms-sw/cmssw/pull/10583){:target="_blank"}  from **@rovere**: Factorise PreSplitting configuration from InitialStep `reconstruction`  created: 2015-08-05 11:37:08 merged: 2015-09-17 09:52:05

26. [10673](http://github.com/cms-sw/cmssw/pull/10673){:target="_blank"}  from **@lgray**: Convert all remaining RECO & MiniAOD modules that are executed to threaded FW (74X) `analysis`  `l1`  `reconstruction`  created: 2015-08-11 06:29:51 merged: 2015-09-17 09:51:59

27. [11265](http://github.com/cms-sw/cmssw/pull/11265){:target="_blank"}  from **@wmtan**: Use anonymous namespace to avoid duplicate symbols `reconstruction`  created: 2015-09-15 21:32:18 merged: 2015-09-17 09:51:49

28. [11288](http://github.com/cms-sw/cmssw/pull/11288){:target="_blank"}  from **@cms-l1t-offline**: remove rct parameters hardcode from 74X `l1`  created: 2015-09-16 15:52:13 merged: 2015-09-17 09:46:35

29. [11108](http://github.com/cms-sw/cmssw/pull/11108){:target="_blank"}  from **@KiSooLee**: HLT BPTX added `dqm`  created: 2015-09-03 13:44:56 merged: 2015-09-16 12:11:14

30. [11156](http://github.com/cms-sw/cmssw/pull/11156){:target="_blank"}  from **@smorovic**: Fix premature end of run in DAQ (74X) `daq`  `reconstruction`  created: 2015-09-05 21:34:55 merged: 2015-09-16 09:06:44

31. [11177](http://github.com/cms-sw/cmssw/pull/11177){:target="_blank"}  from **@slava77**: cleanup of uninitialized reads reported by valgrind (backport of #11173 ) `dqm`  `reconstruction`  created: 2015-09-07 20:07:13 merged: 2015-09-16 09:06:38

32. [11257](http://github.com/cms-sw/cmssw/pull/11257){:target="_blank"}  from **@deguio**: update GT for online processing `dqm`  created: 2015-09-15 16:52:41 merged: 2015-09-16 09:06:18

33. [11133](http://github.com/cms-sw/cmssw/pull/11133){:target="_blank"}  from **@davidsheffield**: Add scouting electron, photon, and muon classes and producers `hlt`  created: 2015-09-04 14:56:17 merged: 2015-09-16 09:02:31

34. [11241](http://github.com/cms-sw/cmssw/pull/11241){:target="_blank"}  from **@fwyzard**: edmCheckMultithreading: check for non multithreading-compliant modules `core`  created: 2015-09-14 08:46:26 merged: 2015-09-16 09:01:32

35. [11210](http://github.com/cms-sw/cmssw/pull/11210){:target="_blank"}  from **@wmtan**: Make ROOT5 checksums known to ROOT6 `analysis`  `reconstruction`  created: 2015-09-09 18:50:17 merged: 2015-09-16 09:01:14

36. [11222](http://github.com/cms-sw/cmssw/pull/11222){:target="_blank"}  from **@cms-met**: Cleaning of pat::MET data format `analysis`  created: 2015-09-10 13:22:36 merged: 2015-09-16 09:00:54

37. [11267](http://github.com/cms-sw/cmssw/pull/11267){:target="_blank"}  from **@slava77**: don't pass puppi NaNs to pseudojet methods `analysis`  `reconstruction`  created: 2015-09-16 05:11:02 merged: 2015-09-16 09:00:27

#### CMSDIST Changes between Tags REL/CMSSW_7_4_12_patch4/slc6_amd64_gcc491 and REL/CMSSW_7_4_13/slc6_amd64_gcc491:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_4_12_patch4/slc6_amd64_gcc491...REL/CMSSW_7_4_13/slc6_amd64_gcc491)


