---
layout: post
rel_link:  "9_2_10"
title:  "CMSSW_9_2_10"
date:   2017-08-24 16:05:13
categories: cmssw
relmajor: 9
relminor: 2
relsubminor: 10
---

# CMSSW_9_2_10
#### Changes since CMSSW_9_2_9_patch1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_9_2_9_patch1...CMSSW_9_2_10)



1. [20233](http://github.com/cms-sw/cmssw/pull/20233){:target="_blank"}  from **@arizzi**: Urgent bugfix for miniaod covariance `analysis`  `reconstruction`  created: 2017-08-22 15:00:06 merged: 2017-08-24 16:02:43

2. [20195](http://github.com/cms-sw/cmssw/pull/20195){:target="_blank"}  from **@stahlleiton**: [92X] OnlineDQM : Customize L1T Client for cosmic run `dqm`  created: 2017-08-17 10:27:13 merged: 2017-08-23 17:12:51

3. [20182](http://github.com/cms-sw/cmssw/pull/20182){:target="_blank"}  from **@bsunanda**: Run2-hcx146 Correct collection names used in IsoTrack HLTs (Backport PR #19776) `alca`  created: 2017-08-16 02:44:33 merged: 2017-08-22 19:23:38

4. [20174](http://github.com/cms-sw/cmssw/pull/20174){:target="_blank"}  from **@thomreis**: Fix MonitorElement exception in L1TTau offline DQM. - 92x v2 `dqm`  `l1`  created: 2017-08-15 13:52:42 merged: 2017-08-22 19:21:35

5. [20160](http://github.com/cms-sw/cmssw/pull/20160){:target="_blank"}  from @Martin-Grunewald: Move **@relval2017** default to HLT V2.2 (92X) `hlt`  created: 2017-08-14 14:23:18 merged: 2017-08-22 19:21:44

6. [20148](http://github.com/cms-sw/cmssw/pull/20148){:target="_blank"}  from **@fwyzard**: minor improvements to the L1T and HLT monitoring modules `hlt`  created: 2017-08-12 17:27:41 merged: 2017-08-22 19:20:56

7. [20145](http://github.com/cms-sw/cmssw/pull/20145){:target="_blank"}  from **@fwyzard**: add warnings to L1TGlobalPrescaler (92x) `l1`  created: 2017-08-12 13:16:44 merged: 2017-08-22 19:20:32

8. [20137](http://github.com/cms-sw/cmssw/pull/20137){:target="_blank"}  from **@cms-bph-trigger**: Make vertex filters rubust to L3Muon duplicates - 92X backport `hlt`  created: 2017-08-11 17:39:34 merged: 2017-08-22 19:20:21

9. [20134](http://github.com/cms-sw/cmssw/pull/20134){:target="_blank"}  from **@ggovi**: Fixes for conddb tool function to copy GT `db`  created: 2017-08-11 15:10:59 merged: 2017-08-22 19:23:27

10. [20117](http://github.com/cms-sw/cmssw/pull/20117){:target="_blank"}  from **@deguio**: disable ZS mark and pass for 2017 `reconstruction`  created: 2017-08-10 14:54:20 merged: 2017-08-22 19:19:41

11. [20114](http://github.com/cms-sw/cmssw/pull/20114){:target="_blank"}  from **@weishi10141993**: Update TrackAndVertexUnpacker.cc `analysis`  `reconstruction`  created: 2017-08-10 14:25:22 merged: 2017-08-22 19:19:22

12. [20102](http://github.com/cms-sw/cmssw/pull/20102){:target="_blank"}  from **@rmanzoni**: fix for Beam Spot txt file mess-up `alca`  `reconstruction`  created: 2017-08-09 15:55:31 merged: 2017-08-22 19:19:03

13. [20098](http://github.com/cms-sw/cmssw/pull/20098){:target="_blank"}  from **@mmusich**: [92X] Adding the DQMEventInfo module to the SiStrip Bad components harvesting `alca`  created: 2017-08-09 13:22:48 merged: 2017-08-22 19:18:43

14. [20089](http://github.com/cms-sw/cmssw/pull/20089){:target="_blank"}  from **@rmanzoni**: updates to tau3mu HLT producer `hlt`  created: 2017-08-09 09:12:46 merged: 2017-08-22 19:18:00

15. [20087](http://github.com/cms-sw/cmssw/pull/20087){:target="_blank"}  from **@mmusich**: [92X] Cleanup and Streamline Alignment PV Validation tool  `alca`  created: 2017-08-09 08:40:44 merged: 2017-08-22 19:22:07

16. [20065](http://github.com/cms-sw/cmssw/pull/20065){:target="_blank"}  from **@bsunanda**: Run2-hcx140 Backport PR's #19574 and #20049 which provides two HLT filters (1) for selecting multiple L1 objects; (2) Laser firing in HCAL `hlt`  created: 2017-08-04 17:27:02 merged: 2017-08-22 19:17:11

17. [20062](http://github.com/cms-sw/cmssw/pull/20062){:target="_blank"}  from **@hroskes**: Load deformations from HipPy alignments in alignment validation tool `alca`  created: 2017-08-04 17:11:38 merged: 2017-08-22 19:17:31

18. [20037](http://github.com/cms-sw/cmssw/pull/20037){:target="_blank"}  from **@arizzi**: Override split level in miniaod 92X version `analysis`  `operations`  `reconstruction`  created: 2017-08-03 12:52:43 merged: 2017-08-23 17:13:44

#### CMSDIST Changes between Tags REL/CMSSW_9_2_9_patch1/slc6_amd64_gcc530 and REL/CMSSW_9_2_10/slc6_amd64_gcc530:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_9_2_9_patch1/slc6_amd64_gcc530...REL/CMSSW_9_2_10/slc6_amd64_gcc530)



1. [3340](http://github.com/cms-sw/cmsdist/pull/3340){:target="_blank"}  from **@mkirsano**: fix pythia8 lhapdf interface and pdfsets.index created: 2017-08-08 14:19:35 merged: 2017-08-15 06:52:56
