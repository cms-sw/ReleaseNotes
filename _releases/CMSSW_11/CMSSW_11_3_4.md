---
layout: post
rel_link:  "11_3_4"
title:  "CMSSW_11_3_4"
date:   2021-08-05 11:53:09
categories: cmssw
relmajor: 11
relminor: 3
relsubminor: 4
---

# CMSSW_11_3_4
#### Changes since CMSSW_11_3_3:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_11_3_3...CMSSW_11_3_4)



1. [34782](http://github.com/cms-sw/cmssw/pull/34782){:target="_blank"}  from **@quark2**: Updates on GEM onlineDQM due to the updates of DAQ dataformat, backport to CMSSW_11_3_X `dqm` created: 2021-08-04 20:27:31 merged: 2021-08-05 09:58:46

2. [34768](http://github.com/cms-sw/cmssw/pull/34768){:target="_blank"}  from **@thomreis**: Fix crash of ECAL GPU reco when ECAL is out of the run - 11_3_X `reconstruction` created: 2021-08-04 13:39:36 merged: 2021-08-04 20:17:41

3. [34750](http://github.com/cms-sw/cmssw/pull/34750){:target="_blank"}  from **@fwyzard**: Protect HCAL GPU-related modules against empty events [11.3.x] `reconstruction` created: 2021-08-03 16:22:42 merged: 2021-08-05 06:17:42

4. [34736](http://github.com/cms-sw/cmssw/pull/34736){:target="_blank"}  from **@fwyzard**: enforce memory order to avoid crash on Ampere [11.3.x] `reconstruction` created: 2021-08-02 20:11:34 merged: 2021-08-04 20:09:07

5. [34731](http://github.com/cms-sw/cmssw/pull/34731){:target="_blank"}  from **@fwyzard**: Fix uploading EventSetup conditions from multiple CUDA streams [11.3.x] `heterogeneous` created: 2021-08-02 16:08:18 merged: 2021-08-04 07:58:32

6. [34721](http://github.com/cms-sw/cmssw/pull/34721){:target="_blank"}  from **@francescobrivio**: Update DQM onlinebeammonitor [11_3_X] `dqm` created: 2021-08-02 12:00:21 merged: 2021-08-04 08:13:56

7. [34684](http://github.com/cms-sw/cmssw/pull/34684){:target="_blank"}  from **@mmusich**: fix CAHitNtupletGeneratorOnGPU in case of no hits `reconstruction` created: 2021-07-29 08:41:19 merged: 2021-07-29 14:56:39

8. [34679](http://github.com/cms-sw/cmssw/pull/34679){:target="_blank"}  from **@alja**: Fireworks 11_3_X: Fix bug in scaling after projected view destruction `visualization` created: 2021-07-28 20:16:52 merged: 2021-07-29 15:27:56

9. [34585](http://github.com/cms-sw/cmssw/pull/34585){:target="_blank"}  from **@jshlee**: [Backport] - GEM unpacker - updated DAQ dataformat and new DAQ status collections `db` `reconstruction` `simulation` `upgrade` created: 2021-07-22 11:07:19 merged: 2021-08-04 20:21:55

#### CMSDIST Changes between Tags REL/CMSSW_11_3_3/slc7_amd64_gcc900 and REL/CMSSW_11_3_4/slc7_amd64_gcc900:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_11_3_3/slc7_amd64_gcc900...REL/CMSSW_11_3_4/slc7_amd64_gcc900)


