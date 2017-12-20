---
layout: post
rel_link:  "9_2_5"
title:  "CMSSW_9_2_5"
date:   2017-07-06 21:00:33
categories: cmssw
relmajor: 9
relminor: 2
relsubminor: 5
---

# CMSSW_9_2_5
#### Changes since CMSSW_9_2_4:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_9_2_4...CMSSW_9_2_5)



1. [19581](http://github.com/cms-sw/cmssw/pull/19581){:target="_blank"}  from **@Martin-Grunewald**: HLTPrescaler work (92X) `hlt`  created: 2017-07-06 08:44:17 merged: 2017-07-06 20:58:39

2. [19545](http://github.com/cms-sw/cmssw/pull/19545){:target="_blank"}  from **@JanFSchulte**: Allow TrackClusterRemover to work on either pixel or strip clusters alone (92X backport) `reconstruction`  created: 2017-07-04 14:44:55 merged: 2017-07-06 16:03:37

3. [19540](http://github.com/cms-sw/cmssw/pull/19540){:target="_blank"}  from **@hroskes**: Tracker alignment validation das client `alca`  created: 2017-07-04 12:32:47 merged: 2017-07-06 20:58:50

4. [19516](http://github.com/cms-sw/cmssw/pull/19516){:target="_blank"}  from **@ggovi**: IOV range returned ordered by since `db`  created: 2017-07-03 09:57:57 merged: 2017-07-06 16:04:57

5. [19511](http://github.com/cms-sw/cmssw/pull/19511){:target="_blank"}  from **@Martin-Grunewald**: Do not throw on non-matching triggers in ecalTrgHLT (92X) `alca`  created: 2017-07-03 08:35:20 merged: 2017-07-06 16:04:04

6. [19497](http://github.com/cms-sw/cmssw/pull/19497){:target="_blank"}  from **@mschrode**: Add scripts to read and write APE from/to ASCII and db files `alca`  created: 2017-06-30 16:24:09 merged: 2017-07-06 16:02:22

7. [19494](http://github.com/cms-sw/cmssw/pull/19494){:target="_blank"}  from **@apana**: pr92x L1T fix L1T_ZeroBias not firing in RelVal MC. `l1`  created: 2017-06-30 12:47:25 merged: 2017-07-06 16:12:48

8. [19482](http://github.com/cms-sw/cmssw/pull/19482){:target="_blank"}  from **@makortel**: Add track selection MVA plots to tracking DQM (92X) `dqm`  `reconstruction`  created: 2017-06-29 14:46:09 merged: 2017-07-06 20:55:39

9. [19473](http://github.com/cms-sw/cmssw/pull/19473){:target="_blank"}  from **@cms-sw**: make sure that workflow commands are written with all the quotes `pdmv`  `upgrade`  created: 2017-06-29 11:24:04 merged: 2017-07-06 16:01:58

10. [19464](http://github.com/cms-sw/cmssw/pull/19464){:target="_blank"}  from **@apana**: pr92/93x L1T allow correlations from other than bx=0 (backport of #19453) `l1`  created: 2017-06-28 17:45:58 merged: 2017-07-06 16:09:28

11. [19448](http://github.com/cms-sw/cmssw/pull/19448){:target="_blank"}  from **@kmcdermo**: Combined backport of PR #19205 and #19404: ootPhotons in miniAOD from AOD from either 92X or 80X inputs `analysis`  `reconstruction`  created: 2017-06-27 14:42:22 merged: 2017-07-06 20:55:55

12. [19438](http://github.com/cms-sw/cmssw/pull/19438){:target="_blank"}  from **@makortel**: Update online beamspot to quadruplet-only and rescale track uncertainties (92X) `dqm`  `reconstruction`  created: 2017-06-27 07:49:36 merged: 2017-07-06 16:01:48

13. [19434](http://github.com/cms-sw/cmssw/pull/19434){:target="_blank"}  from **@forthommel**:  CTPPS: fixes for 2017 diamond data taking operations (backport to 9_2_X) `dqm`  `reconstruction`  created: 2017-06-27 07:05:23 merged: 2017-07-06 16:00:32

14. [19433](http://github.com/cms-sw/cmssw/pull/19433){:target="_blank"}  from **@mmusich**: [92X] add SiStripCalMinBias to the upgrade phase-I samples (backport of #19430) `pdmv`  `upgrade`  created: 2017-06-27 06:42:54 merged: 2017-07-06 16:00:45

15. [19416](http://github.com/cms-sw/cmssw/pull/19416){:target="_blank"}  from **@ianna**: Move Geometry Aligner Header `alca`  `geometry`  created: 2017-06-23 14:44:48 merged: 2017-06-26 08:26:51

16. [19375](http://github.com/cms-sw/cmssw/pull/19375){:target="_blank"}  from **@Sam-Harper**: Adding Cross Trigger Support to E/gamma TnP DQM `dqm`  created: 2017-06-19 20:58:58 merged: 2017-06-26 08:28:36

#### CMSDIST Changes between Tags REL/CMSSW_9_2_4/slc6_amd64_gcc530 and REL/CMSSW_9_2_5/slc6_amd64_gcc530:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_9_2_4/slc6_amd64_gcc530...REL/CMSSW_9_2_5/slc6_amd64_gcc530)



1. [3142](http://github.com/cms-sw/cmsdist/pull/3142){:target="_blank"}  from **@vkuznet**: New version fixed acess to RunRegistry data-service created: 2017-07-04 07:42:06 merged: 2017-07-04 10:52:38

2. [3137](http://github.com/cms-sw/cmsdist/pull/3137){:target="_blank"}  from **@vkuznet**: New version of dasgoclient to fix run splitting from DBS output created: 2017-06-30 09:13:03 merged: 2017-06-30 15:48:31

3. [3124](http://github.com/cms-sw/cmsdist/pull/3124){:target="_blank"}  from **@davidlange6**: adding hyperas and hyper opt python tools created: 2017-06-26 12:25:56 merged: 2017-06-26 14:46:13
