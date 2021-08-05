---
layout: post
rel_link:  "12_0_0_pre6"
title:  "CMSSW_12_0_0_pre6"
date:   2021-08-05 15:45:03
categories: cmssw
relmajor: 12
relminor: 0
relsubminor: 0
relpre: _pre6
---

# CMSSW_12_0_0_pre6
#### Changes since CMSSW_12_0_0_pre5:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_0_0_pre5...CMSSW_12_0_0_pre6)



1. [34766](http://github.com/cms-sw/cmssw/pull/34766){:target="_blank"}  from **@thomreis**: Fix crash of ECAL GPU reco when ECAL is out of the run - 12_0_X `reconstruction` created: 2021-08-04 13:20:55 merged: 2021-08-04 20:19:33

2. [34751](http://github.com/cms-sw/cmssw/pull/34751){:target="_blank"}  from **@mariadalfonso**: NANO: rework for Prompt (part2) backport `xpog` created: 2021-08-03 17:43:40 merged: 2021-08-04 10:15:06

3. [34749](http://github.com/cms-sw/cmssw/pull/34749){:target="_blank"}  from **@fwyzard**: Protect HCAL GPU-related modules against empty events [12.0.x] `reconstruction` created: 2021-08-03 16:21:16 merged: 2021-08-05 06:19:57

4. [34747](http://github.com/cms-sw/cmssw/pull/34747){:target="_blank"}  from **@bsunanda**: Run3-hcx306X Bug fix (backport #34738) to HCAL SD class `simulation` created: 2021-08-03 15:06:51 merged: 2021-08-04 12:30:43

5. [34743](http://github.com/cms-sw/cmssw/pull/34743){:target="_blank"}  from **@jshlee**: [Backport] GEM dataformat - fix classversion `reconstruction` `simulation` `upgrade` created: 2021-08-03 13:05:38 merged: 2021-08-04 20:26:34

6. [34741](http://github.com/cms-sw/cmssw/pull/34741){:target="_blank"}  from **@cms-tsg-storm**: HLT menu migration to CMSSW 12_0_0_pre5 template [12_0_X] `hlt` created: 2021-08-03 12:20:48 merged: 2021-08-04 16:06:50

7. [34730](http://github.com/cms-sw/cmssw/pull/34730){:target="_blank"}  from **@fwyzard**: Fix uploading EventSetup conditions from multiple CUDA streams [12.0.x] `heterogeneous` created: 2021-08-02 16:07:38 merged: 2021-08-04 07:57:12

8. [34726](http://github.com/cms-sw/cmssw/pull/34726){:target="_blank"}  from **@francescobrivio**:  Update DQM onlinebeammonitor [12_0_X] `dqm` created: 2021-08-02 14:44:10 merged: 2021-08-04 08:13:48

9. [34712](http://github.com/cms-sw/cmssw/pull/34712){:target="_blank"}  from **@fwyzard**: Fix integer division after migration to python 3 `dqm` created: 2021-07-31 07:37:12 merged: 2021-08-03 10:41:36

10. [34689](http://github.com/cms-sw/cmssw/pull/34689){:target="_blank"}  from **@smuzaffar**: [Misc1][clang-tidy] make deleted function public `analysis` `core` `dqm` `geometry` `reconstruction` created: 2021-07-29 10:05:03 merged: 2021-07-29 19:34:29

11. [34687](http://github.com/cms-sw/cmssw/pull/34687){:target="_blank"}  from **@smuzaffar**: [JetMETCorrections][clang-tidy] make deleted function public `analysis` `reconstruction` created: 2021-07-29 09:34:37 merged: 2021-07-29 16:22:13

12. [34685](http://github.com/cms-sw/cmssw/pull/34685){:target="_blank"}  from **@smuzaffar**: [Reco][clang-tidy] make deleted function public `reconstruction` created: 2021-07-29 08:43:48 merged: 2021-07-29 19:12:56

13. [34678](http://github.com/cms-sw/cmssw/pull/34678){:target="_blank"}  from **@smuzaffar**: [clang-tidy] Looks like NOLINTNEXTLINE is not working with misc-definitions-in-headers `reconstruction` created: 2021-07-28 18:27:33 merged: 2021-07-29 16:17:47

14. [34677](http://github.com/cms-sw/cmssw/pull/34677){:target="_blank"}  from **@smuzaffar**: [FWCore][clang-tidy] Fix suggested by modernize-use-nullptr check `core` created: 2021-07-28 17:59:30 merged: 2021-07-29 16:18:20

15. [34671](http://github.com/cms-sw/cmssw/pull/34671){:target="_blank"}  from **@smuzaffar**: [Alignment][clang-tidy] make deleted function public `alca` created: 2021-07-28 13:56:36 merged: 2021-07-29 16:13:47

16. [34669](http://github.com/cms-sw/cmssw/pull/34669){:target="_blank"}  from **@smuzaffar**: [CommonTools][clang-tidy] make deleted function public `reconstruction` created: 2021-07-28 13:00:55 merged: 2021-07-29 16:15:34

17. [34667](http://github.com/cms-sw/cmssw/pull/34667){:target="_blank"}  from **@smuzaffar**: [FWCore][clang-tidy] make deleted function public `core` created: 2021-07-28 10:40:16 merged: 2021-07-29 16:17:08

18. [34660](http://github.com/cms-sw/cmssw/pull/34660){:target="_blank"}  from **@guitargeek**: Merge .h and .cc files of remaining RecoParticleFlow plugins `dqm` `reconstruction` created: 2021-07-27 22:33:59 merged: 2021-07-29 16:11:26

19. [34658](http://github.com/cms-sw/cmssw/pull/34658){:target="_blank"}  from **@smuzaffar**: [PF][clang-tidy] fix readability-container-size-empty warnings `reconstruction` created: 2021-07-27 21:29:04 merged: 2021-07-29 16:10:58

20. [34653](http://github.com/cms-sw/cmssw/pull/34653){:target="_blank"}  from **@makortel**: Remove IgProfModule as obsolete `core` created: 2021-07-27 18:50:31 merged: 2021-07-29 16:10:10

21. [34637](http://github.com/cms-sw/cmssw/pull/34637){:target="_blank"}  from **@abhih1**: Migrate ECAL Validation codes to ESConsumes `dqm` created: 2021-07-26 21:35:22 merged: 2021-07-29 16:09:40

22. [34623](http://github.com/cms-sw/cmssw/pull/34623){:target="_blank"}  from **@grasph**: Ecal laser update: Changed a system("mv") by a rename() and removed second attempt to read matacq file to speed up the processing when the file is missing `alca` `reconstruction` created: 2021-07-26 15:54:07 merged: 2021-07-29 19:41:32

23. [34614](http://github.com/cms-sw/cmssw/pull/34614){:target="_blank"}  from **@quark2**: Updates on GEM onlineDQM due to the updates of DAQ dataformat `dqm` created: 2021-07-24 20:02:49 merged: 2021-07-29 19:54:46

24. [34604](http://github.com/cms-sw/cmssw/pull/34604){:target="_blank"}  from **@jfernan2**: [DQM] esConsumes migration for Validation package leftovers `dqm` `reconstruction` `simulation` created: 2021-07-23 11:07:02 merged: 2021-07-29 16:08:32

#### CMSDIST Changes between Tags REL/CMSSW_12_0_0_pre5/slc7_amd64_gcc900 and REL/CMSSW_12_0_0_pre6/slc7_amd64_gcc900:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_0_0_pre5/slc7_amd64_gcc900...REL/CMSSW_12_0_0_pre6/slc7_amd64_gcc900)



1. [7189](http://github.com/cms-sw/cmsdist/pull/7189){:target="_blank"}  from **@cms-sw**: Revert "Update py3-wheel, py3-numpy and py3-wrapt" created: 2021-07-30 23:02:57 merged: 2021-07-30 23:03:11

2. [7183](http://github.com/cms-sw/cmsdist/pull/7183){:target="_blank"}  from **@cms-sw**: Update py3-wheel, py3-numpy and py3-wrapt created: 2021-07-29 16:37:19 merged: 2021-07-30 22:57:19

3. [7182](http://github.com/cms-sw/cmsdist/pull/7182){:target="_blank"}  from **@cms-sw**: [FWLite] added HLS deps created: 2021-07-29 11:04:14 merged: 2021-07-29 11:04:24

4. [7178](http://github.com/cms-sw/cmsdist/pull/7178){:target="_blank"}  from **@cms-sw**: [BuildRules] Fix for project rename created: 2021-07-28 17:48:11 merged: 2021-07-29 11:11:20
