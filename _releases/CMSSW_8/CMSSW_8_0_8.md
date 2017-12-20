---
layout: post
rel_link:  "8_0_8"
title:  "CMSSW_8_0_8"
date:   2016-05-12 14:44:47
categories: cmssw
relmajor: 8
relminor: 0
relsubminor: 8
---

# CMSSW_8_0_8
#### Changes since CMSSW_8_0_7_patch3:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_8_0_7_patch3...CMSSW_8_0_8)



1. [14478](http://github.com/cms-sw/cmssw/pull/14478){:target="_blank"}  from **@davidlange6**: remove some printout in every event `comparison`  `l1`  created: 2016-05-12 14:41:38 merged: 2016-05-12 14:41:46

2. [14474](http://github.com/cms-sw/cmssw/pull/14474){:target="_blank"}  from **@fwyzard**: HLT DQM: add protection for empty L1 uGT collection `dqm`  created: 2016-05-12 12:43:38 merged: 2016-05-12 14:37:37

3. [14465](http://github.com/cms-sw/cmssw/pull/14465){:target="_blank"}  from **@cms-l1t-offline**: L1T Minimum Bias Trigger (80x) `l1`  created: 2016-05-11 21:12:49 merged: 2016-05-12 14:38:32

4. [14435](http://github.com/cms-sw/cmssw/pull/14435){:target="_blank"}  from **@davidlt**: Fix explicit GzInputStream::operator bool() const `comparison`  `l1`  created: 2016-05-10 13:09:52 merged: 2016-05-11 17:36:50

5. [14407](http://github.com/cms-sw/cmssw/pull/14407){:target="_blank"}  from **@dmitrijus**: Add DQMStore::getElement whichs throws an exception instead of a nullptr (80x)  `dqm`  created: 2016-05-09 08:16:57 merged: 2016-05-11 08:17:01

6. [14387](http://github.com/cms-sw/cmssw/pull/14387){:target="_blank"}  from **@cms-l1t-offline**: L1REPACK 2016 2015 `l1`  `operations`  created: 2016-05-05 18:33:08 merged: 2016-05-11 08:25:34

7. [14380](http://github.com/cms-sw/cmssw/pull/14380){:target="_blank"}  from **@barvic**: CSC Unpacker fixes for 2016 TMB/OTMB firmware updates (80X) `reconstruction`  created: 2016-05-04 15:53:43 merged: 2016-05-11 17:42:35

8. [14358](http://github.com/cms-sw/cmssw/pull/14358){:target="_blank"}  from **@cippy**: optimized CPU timing of ECAL Pi0 stream `hlt`  created: 2016-05-03 15:21:11 merged: 2016-05-11 08:16:50

9. [14325](http://github.com/cms-sw/cmssw/pull/14325){:target="_blank"}  from **@cms-tsg-storm**: Towards the first hlt menu for 2016 - 80X `hlt`  created: 2016-05-02 14:51:13 merged: 2016-05-12 14:40:48

10. [14323](http://github.com/cms-sw/cmssw/pull/14323){:target="_blank"}  from **@cms-l1t-offline**: Updates to L1T packer needed to simultaneously pack GT inputs and GMT/Calo ouputs `l1`  created: 2016-05-02 14:21:45 merged: 2016-05-11 08:15:57

11. [14320](http://github.com/cms-sw/cmssw/pull/14320){:target="_blank"}  from **@cms-l1t-offline**: Update L1Ntuples to l1t-tsg-v5, and address memory management problems. `l1`  created: 2016-05-02 11:50:08 merged: 2016-05-11 08:15:17

12. [14315](http://github.com/cms-sw/cmssw/pull/14315){:target="_blank"}  from **@sushilchauhan**: update dqm  client config for online beam spot running pixel tracking `dqm`  created: 2016-04-30 20:14:30 merged: 2016-05-11 08:14:57

13. [14285](http://github.com/cms-sw/cmssw/pull/14285){:target="_blank"}  from **@cms-l1t-offline**: Updates to L1TCaloLayer1 and unpacker (80X) `l1`  created: 2016-04-27 20:48:03 merged: 2016-05-11 08:14:31

14. [14281](http://github.com/cms-sw/cmssw/pull/14281){:target="_blank"}  from **@mmusich**: Update Global Tag for Collisions2016_v1 L1T menu and splitting Ecal Pedestal tags `alca`  created: 2016-04-27 19:54:21 merged: 2016-05-11 08:14:14

15. [14150](http://github.com/cms-sw/cmssw/pull/14150){:target="_blank"}  from **@rovere**: Enable OfflinePV and Beamspot in trackingLowPU era `dqm`  `reconstruction`  created: 2016-04-19 16:08:33 merged: 2016-05-11 08:28:16

16. [14147](http://github.com/cms-sw/cmssw/pull/14147){:target="_blank"}  from **@sarafiorendi**: update muon validation plots to Stage2L1 + update HLT DQM plots (backport of #14146) `dqm`  created: 2016-04-19 13:29:14 merged: 2016-05-11 08:14:02

17. [13421](http://github.com/cms-sw/cmssw/pull/13421){:target="_blank"}  from **@mtosi**: update trajectory filters (minNumberOfHits --> minNumberOfHitsForLoopers) `hlt`  `reconstruction`  created: 2016-02-22 09:56:45 merged: 2016-05-11 17:37:32

#### CMSDIST Changes between Tags REL/CMSSW_8_0_7_patch3/slc6_amd64_gcc530 and REL/CMSSW_8_0_8/slc6_amd64_gcc530:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_8_0_7_patch3/slc6_amd64_gcc530...REL/CMSSW_8_0_8/slc6_amd64_gcc530)



1. [2287](http://github.com/cms-sw/cmsdist/pull/2287){:target="_blank"}  from **@cms-sw**: Update data-L1Trigger-L1TCalorimeter.spec created: 2016-05-11 17:34:39 merged: 2016-05-11 17:35:00

2. [2283](http://github.com/cms-sw/cmsdist/pull/2283){:target="_blank"}  from **@smuzaffar**: Update utm.spec created: 2016-05-07 18:45:57 merged: 2016-05-07 18:46:03
