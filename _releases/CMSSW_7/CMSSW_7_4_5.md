---
layout: post
rel_link:  "7_4_5"
title:  "CMSSW_7_4_5"
date:   2015-06-11 08:38:20
categories: cmssw
relmajor: 7
relminor: 4
relsubminor: 5
---

# CMSSW_7_4_5
#### Changes since CMSSW_7_4_4_patch4:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_4_4_patch4...CMSSW_7_4_5)



1. [9003](http://github.com/cms-sw/cmssw/pull/9003){:target="_blank"}  from **@lgray**: EGM VID IDs for 74X - PHYS14 tunings `analysis`  `reconstruction`  created: 2015-05-08 11:29:21 merged: 2015-06-10 19:35:16

2. [9400](http://github.com/cms-sw/cmssw/pull/9400){:target="_blank"}  from **@vdutta**: Fix to allow histogram rebinning to work again for Tracker DQM trend plots in ROOT6 `dqm`  created: 2015-06-02 09:00:03 merged: 2015-06-10 19:34:51

3. [9408](http://github.com/cms-sw/cmssw/pull/9408){:target="_blank"}  from **@fioriNTU**: SiStrip summary report back to old shape `dqm`  created: 2015-06-02 13:59:47 merged: 2015-06-10 14:42:10

4. [9416](http://github.com/cms-sw/cmssw/pull/9416){:target="_blank"}  from **@sushilchauhan**: kCanRebin is replaced with SetCanExtend in online beamspot code for dqm `dqm`  created: 2015-06-02 16:47:15 merged: 2015-06-10 14:38:06

5. [9447](http://github.com/cms-sw/cmssw/pull/9447){:target="_blank"}  from **@smuzaffar**: limit the proofsrv slaves to be only two for these unit tests `core`  created: 2015-06-04 12:25:33 merged: 2015-06-10 14:30:48

6. [9490](http://github.com/cms-sw/cmssw/pull/9490){:target="_blank"}  from **@bendavid**:  Protect against infinite loops in gen status flag code (74x) `analysis`  created: 2015-06-07 17:00:29 merged: 2015-06-10 14:30:25

7. [9085](http://github.com/cms-sw/cmssw/pull/9085){:target="_blank"}  from **@shervin86**: Fix alcareco 74x `alca`  `operations`  `pdmv`  created: 2015-05-14 13:24:27 merged: 2015-06-10 14:23:37

8. [9508](http://github.com/cms-sw/cmssw/pull/9508){:target="_blank"}  from **@mmusich**: Fixing AlCaRecoTriggerBits reading/writing for condDBv2 `db`  `hlt`  created: 2015-06-08 15:00:27 merged: 2015-06-10 13:51:42

9. [9513](http://github.com/cms-sw/cmssw/pull/9513){:target="_blank"}  from **@fwyzard**: add support for ConfDB v2 to hltConfigFromDB `hlt`  created: 2015-06-08 17:12:06 merged: 2015-06-10 13:46:50

10. [9504](http://github.com/cms-sw/cmssw/pull/9504){:target="_blank"}  from **@dmitrijus**: Properly zero terminate a string in DQMEventInfo. `dqm`  created: 2015-06-08 13:54:50 merged: 2015-06-10 10:47:09

11. [9072](http://github.com/cms-sw/cmssw/pull/9072){:target="_blank"}  from **@kkrajczar**: Multi-threading support added for Heavy Ions HLT modules `reconstruction`  created: 2015-05-13 09:05:46 merged: 2015-06-10 10:44:08

12. [9210](http://github.com/cms-sw/cmssw/pull/9210){:target="_blank"}  from **@mark-grimes**: Trim FastjetJetProducer memory (forward port #9203 to 74X) `reconstruction`  created: 2015-05-21 15:59:23 merged: 2015-06-10 10:43:56

13. [9233](http://github.com/cms-sw/cmssw/pull/9233){:target="_blank"}  from **@bmarzocc**: 7_4_X_AlCaPhiSym_ringCut `hlt`  created: 2015-05-22 12:37:40 merged: 2015-06-10 10:43:45

14. [9382](http://github.com/cms-sw/cmssw/pull/9382){:target="_blank"}  from **@BetterWang**: HeavyIon EP code backport `dqm`  `hlt`  `reconstruction`  created: 2015-06-01 12:22:45 merged: 2015-06-10 10:43:33

15. [9162](http://github.com/cms-sw/cmssw/pull/9162){:target="_blank"}  from **@bsunanda**: bsunanda:Run2-alca15 Backport the changes for AlCaReco and Trigger codes for Hcal calibrations in PRs 8943, 8950 and 9062 `alca`  `dqm`  created: 2015-05-19 19:56:27 merged: 2015-06-10 06:52:23

16. [9322](http://github.com/cms-sw/cmssw/pull/9322){:target="_blank"}  from **@VinInn**: back port of #9073 for 74x `reconstruction`  `simulation`  created: 2015-05-28 16:45:35 merged: 2015-06-10 06:52:11

17. [9277](http://github.com/cms-sw/cmssw/pull/9277){:target="_blank"}  from **@jingyucms**: fix rct HF FED vector and ungang csc ME1/a `dqm`  `l1`  created: 2015-05-26 16:15:37 merged: 2015-06-09 19:57:30

18. [9087](http://github.com/cms-sw/cmssw/pull/9087){:target="_blank"}  from **@cfmcginn**: Add low lumi HI jet and photon triggers HLT DQM entries (backport from 75X) `dqm`  created: 2015-05-14 15:49:40 merged: 2015-06-09 19:52:59

19. [9126](http://github.com/cms-sw/cmssw/pull/9126){:target="_blank"}  from **@mplaner**: update list of HLT paths monitored by the Higgs HLT DQM `dqm`  created: 2015-05-18 11:24:06 merged: 2015-06-09 19:52:49

20. [9332](http://github.com/cms-sw/cmssw/pull/9332){:target="_blank"}  from **@dmitrijus**: Added scripts for on-the-fly log file compression and reading. `dqm`  created: 2015-05-29 11:46:41 merged: 2015-06-09 19:52:38

21. [8674](http://github.com/cms-sw/cmssw/pull/8674){:target="_blank"}  from **@JetMETdqmval**: enable MiniAOD validation, in default validation switch GenJets to GenJetsNoNu as new default `dqm`  `operations`  `reconstruction`  `simulation`  created: 2015-04-07 19:27:52 merged: 2015-06-09 19:45:23

22. [9510](http://github.com/cms-sw/cmssw/pull/9510){:target="_blank"}  from **@deguio**: merge instead of adding in case the CanExtendAllAxis is set `dqm`  created: 2015-06-08 15:18:30 merged: 2015-06-09 19:36:44

23. [9398](http://github.com/cms-sw/cmssw/pull/9398){:target="_blank"}  from **@Martin-Grunewald**: L1T lowPU menu v3 `hlt`  `l1`  created: 2015-06-02 06:30:26 merged: 2015-06-09 08:13:21

24. [9325](http://github.com/cms-sw/cmssw/pull/9325){:target="_blank"}  from **@jmduarte**: backport of HLT Hbb filter for 74X `hlt`  created: 2015-05-29 02:31:40 merged: 2015-06-07 15:53:02

25. [9310](http://github.com/cms-sw/cmssw/pull/9310){:target="_blank"}  from **@davidlt**: Fix use-after-free bug in typeCode `analysis`  `reconstruction`  created: 2015-05-28 09:28:18 merged: 2015-06-06 16:18:30

#### CMSDIST Changes between Tags REL/CMSSW_7_4_4_patch4/slc6_amd64_gcc491 and REL/CMSSW_7_4_5/slc6_amd64_gcc491:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_4_4_patch4/slc6_amd64_gcc491...REL/CMSSW_7_4_5/slc6_amd64_gcc491)



1. [1550](http://github.com/cms-sw/cmsdist/pull/1550){:target="_blank"}  from **@pmillet**: openloops v1.1.1 and use proclibs from cms-externals repo created: 2015-05-13 13:19:06 merged: 2015-06-03 07:41:52
