---
layout: post
rel_link:  "7_2_2"
title:  "CMSSW_7_2_2"
date:   2014-11-19 21:13:17
categories: cmssw
relmajor: 7
relminor: 2
relsubminor: 2
---

# CMSSW_7_2_2
#### Changes since CMSSW_7_2_1_patch4:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_7_2_1_patch4...CMSSW_7_2_2)



1. [6480](http://github.com/cms-sw/cmssw/pull/6480){:target="_blank"}  from **@Sam-Harper**: removing spurious error message from GsfElectron::ecalDriven()  72X `reconstruction`  created: 2014-11-18 16:44:59 merged: 2014-11-19 08:51:27

2. [6485](http://github.com/cms-sw/cmssw/pull/6485){:target="_blank"}  from **@vadler**: 72X - fix `HadronAndPartonSelector` for unknown generators `analysis`  created: 2014-11-18 22:04:10 merged: 2014-11-19 08:46:20

3. [6465](http://github.com/cms-sw/cmssw/pull/6465){:target="_blank"}  from **@apfeiffer1**: remove use of oracle for plugins, 72x version `db`  created: 2014-11-18 09:26:19 merged: 2014-11-19 07:41:09

4. [6364](http://github.com/cms-sw/cmssw/pull/6364){:target="_blank"}  from **@wddgit**: Bug fix for NewEventStreamFileReader `core`  created: 2014-11-12 23:12:22 merged: 2014-11-18 17:23:04

5. [6389](http://github.com/cms-sw/cmssw/pull/6389){:target="_blank"}  from **@ggovi**: Changed payload proxy cache as required from Framework - for 72X `alca`  `db`  created: 2014-11-13 21:33:26 merged: 2014-11-18 17:22:53

6. [6418](http://github.com/cms-sw/cmssw/pull/6418){:target="_blank"}  from **@slava77**: fix crash in CtfSpecialSeedGenerator ocurring at run boundaries `reconstruction`  created: 2014-11-15 01:05:25 merged: 2014-11-18 17:22:34

7. [5949](http://github.com/cms-sw/cmssw/pull/5949){:target="_blank"}  from **@ggovi**: PopCon packages updated with new functionalities for executing the uploa... `alca`  `db`  created: 2014-10-22 19:27:49 merged: 2014-11-18 17:20:08

8. [6073](http://github.com/cms-sw/cmssw/pull/6073){:target="_blank"}  from **@tlampen**: Backport of #6030. Add features offline validation for72 x `alca`  created: 2014-10-29 10:33:36 merged: 2014-11-18 17:19:47

9. [6194](http://github.com/cms-sw/cmssw/pull/6194){:target="_blank"}  from **@mbluj**: Tau DQM fix: HLTEgammaGeneric and HLT2PhotonTau filters for (72X) `dqm`  created: 2014-11-04 12:09:25 merged: 2014-11-18 17:19:06

10. [6297](http://github.com/cms-sw/cmssw/pull/6297){:target="_blank"}  from **@cms-analysis-tools**: Merge pull request #6012 from cms-analysis-tools/CMSSW_7_3_X_AT_genHFHad... `analysis`  created: 2014-11-09 14:30:40 merged: 2014-11-18 17:18:37

11. [6320](http://github.com/cms-sw/cmssw/pull/6320){:target="_blank"}  from **@yiiyama**: Fix filter for ecal_ and collection names for ecal_, ecalcalib_ `dqm`  created: 2014-11-11 02:09:22 merged: 2014-11-18 17:18:18

12. [6391](http://github.com/cms-sw/cmssw/pull/6391){:target="_blank"}  from **@ggovi**: fix for IOVService test concurrency - 72X `alca`  `db`  created: 2014-11-13 21:37:18 merged: 2014-11-18 17:18:06

13. [6477](http://github.com/cms-sw/cmssw/pull/6477){:target="_blank"}  from **@Dr15Jones**: Avoid an infinite loop in InitRootHandlers destructor `core`  created: 2014-11-18 14:44:24 merged: 2014-11-18 17:16:43

14. [6478](http://github.com/cms-sw/cmssw/pull/6478){:target="_blank"}  from **@bbockelm**: Provide the ability to do a separate cache-hint for cloning. `core`  created: 2014-11-18 14:58:13 merged: 2014-11-18 17:16:32

15. [6437](http://github.com/cms-sw/cmssw/pull/6437){:target="_blank"}  from **@smuzaffar**: Added the missing Done Checking dependency message needed by the IBs scripts created: 2014-11-17 11:25:37 merged: 2014-11-17 11:25:56

16. [6339](http://github.com/cms-sw/cmssw/pull/6339){:target="_blank"}  from **@smorovic**: \* reading event type from FED header instead of L1 history `daq`  created: 2014-11-11 18:43:04 merged: 2014-11-11 20:19:37

17. [6338](http://github.com/cms-sw/cmssw/pull/6338){:target="_blank"}  from **@smorovic**: Bugfix in TCDS data block reading `daq`  created: 2014-11-11 16:08:22 merged: 2014-11-11 16:18:18

18. [6275](http://github.com/cms-sw/cmssw/pull/6275){:target="_blank"}  from **@dmitrijus**: Running an online DQM application will no longer require the monitoring ... `dqm`  created: 2014-11-07 16:59:56 merged: 2014-11-11 15:52:55

19. [6287](http://github.com/cms-sw/cmssw/pull/6287){:target="_blank"}  from **@Martin-Grunewald**: Fix of HLTDeDxFilter for 72X `reconstruction`  created: 2014-11-08 05:23:16 merged: 2014-11-11 15:52:44

20. [6309](http://github.com/cms-sw/cmssw/pull/6309){:target="_blank"}  from **@fwyzard**: TriggerRatesMonitor: fix booking of L1 Tech trigger rate plots `dqm`  created: 2014-11-10 14:26:40 merged: 2014-11-11 15:52:32

#### CMSDIST Changes between Tags REL/CMSSW_7_2_1_patch4/slc6_amd64_gcc481 and REL/CMSSW_7_2_2/slc6_amd64_gcc481:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_7_2_1_patch4/slc6_amd64_gcc481...REL/CMSSW_7_2_2/slc6_amd64_gcc481)


