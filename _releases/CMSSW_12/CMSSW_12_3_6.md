---
layout: post
rel_link:  "12_3_6"
title:  "CMSSW_12_3_6"
date:   2022-06-27 22:05:52
categories: cmssw
relmajor: 12
relminor: 3
relsubminor: 6
---

# CMSSW_12_3_6
#### Changes since CMSSW_12_3_5_patch1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_12_3_5_patch1...CMSSW_12_3_6)



1. [38505](http://github.com/cms-sw/cmssw/pull/38505){:target="_blank"}  from **@alejands**: [12_3_X Backport] Add checks for ECAL DQM setup objects to prevent crashes on runs with no calibration data `dqm` created: 2022-06-25 00:25:07 merged: 2022-06-27 19:27:13

2. [38478](http://github.com/cms-sw/cmssw/pull/38478){:target="_blank"}  from **@fwyzard**: Initialise the errors_ data member of SiPixelDigiErrorsSoAFromCUDA [12.3.x] `reconstruction` created: 2022-06-22 21:04:01 merged: 2022-06-25 07:42:51

3. [38459](http://github.com/cms-sw/cmssw/pull/38459){:target="_blank"}  from **@malbouis**: [12_3_X] Update HLT GT with ECAL DQM tower and channel status tags `alca` created: 2022-06-21 22:30:48 merged: 2022-06-24 01:42:53

4. [38446](http://github.com/cms-sw/cmssw/pull/38446){:target="_blank"}  from **@missirol**: update of `HLTriggerJSONMonitoring` for `DatasetPath`s [`12_3_X`] `hlt` created: 2022-06-20 20:16:01 merged: 2022-06-22 07:29:49

5. [38441](http://github.com/cms-sw/cmssw/pull/38441){:target="_blank"}  from **@smuzaffar**: [12.3.X] use cms_omds_adg instead of temp tunnel cms_omds_tunnel `db` created: 2022-06-20 11:54:15 merged: 2022-06-21 00:31:37

6. [38436](http://github.com/cms-sw/cmssw/pull/38436){:target="_blank"}  from **@AndreaBellora**: Added plots for 2/3 aligned ROCs per BX, backport of PR #38435 `dqm` created: 2022-06-20 10:46:47 merged: 2022-06-22 17:09:42

7. [38433](http://github.com/cms-sw/cmssw/pull/38433){:target="_blank"}  from **@francescobrivio**: [12_3_X] Fix for printouts with special (for python) chars `db` created: 2022-06-20 08:31:47 merged: 2022-06-20 13:09:46

8. [38430](http://github.com/cms-sw/cmssw/pull/38430){:target="_blank"}  from **@mmusich**: [12.3.X] Update SiStrip and TkAlignment ALCARECO event content for Run3  `alca` created: 2022-06-20 08:10:05 merged: 2022-06-20 13:12:08

9. [38424](http://github.com/cms-sw/cmssw/pull/38424){:target="_blank"}  from **@lwang046**: HcalDQM: Add FED integrity module, backport of #38387 `dqm` created: 2022-06-20 06:57:16 merged: 2022-06-24 06:42:21

10. [38420](http://github.com/cms-sw/cmssw/pull/38420){:target="_blank"}  from **@fabiocos**: [123X backport] Simulation: Add Flat0To200_OOTPoisson PU scenario `operations` `simulation` created: 2022-06-19 16:45:23 merged: 2022-06-23 01:02:02

11. [38412](http://github.com/cms-sw/cmssw/pull/38412){:target="_blank"}  from **@pmandrik**: [12_3_X] Fix output file name of hcalgpu DQM client `dqm` created: 2022-06-17 18:27:55 merged: 2022-06-18 14:23:53

12. [38403](http://github.com/cms-sw/cmssw/pull/38403){:target="_blank"}  from **@tvami**: [12_3_X] Introduce AlCaPPS_Run3 scenario `alca` `operations` created: 2022-06-17 07:03:08 merged: 2022-06-17 12:32:39

13. [38399](http://github.com/cms-sw/cmssw/pull/38399){:target="_blank"}  from **@hftsoi**: [backport] Change at CaloLayer1 DQM the filling threshold for ECAL 5BX plots `dqm` created: 2022-06-16 20:47:58 merged: 2022-06-20 00:53:08

14. [38385](http://github.com/cms-sw/cmssw/pull/38385){:target="_blank"}  from **@mmusich**: [12.3.X] `CalibTracker`: fallback to the `OnlineLuminosityRecord` when SCAL is not available `alca` created: 2022-06-16 08:16:48 merged: 2022-06-17 07:07:43

15. [38376](http://github.com/cms-sw/cmssw/pull/38376){:target="_blank"}  from **@ChrisMisan**: [12_3_X]Restore sampicSubDetId backward compatibility `alca` `reconstruction` created: 2022-06-15 12:17:20 merged: 2022-06-20 14:13:23

16. [38360](http://github.com/cms-sw/cmssw/pull/38360){:target="_blank"}  from **@abhih1**: Code Fix to read tower geometry correctly in Ecal DQM StatusManager  [12_3_X] `alca` `dqm` created: 2022-06-13 14:05:49 merged: 2022-06-25 07:46:06

17. [38354](http://github.com/cms-sw/cmssw/pull/38354){:target="_blank"}  from **@CMS-ECAL-Trigger-Group**: [backport] Fix ECAL TPG emulator discrepancy for saturated strips `l1` created: 2022-06-13 08:37:28 merged: 2022-06-20 00:48:26

18. [38333](http://github.com/cms-sw/cmssw/pull/38333){:target="_blank"}  from **@missirol**: Fix range in recHitsEndcapsPosXY [`12_3_X`] `dqm` created: 2022-06-11 12:23:27 merged: 2022-06-14 00:40:15

19. [38330](http://github.com/cms-sw/cmssw/pull/38330){:target="_blank"}  from **@seungjin-yang**: GEM Online & Offline Efficiency Update (backport of #37954, 12_3_X) `dqm` created: 2022-06-11 10:34:29 merged: 2022-06-23 05:13:57

20. [38322](http://github.com/cms-sw/cmssw/pull/38322){:target="_blank"}  from **@thomreis**: ECAL - Sort digis collections coming from GPU unpacking - 123x `hlt` `reconstruction` created: 2022-06-10 16:56:29 merged: 2022-06-14 07:58:29

21. [38301](http://github.com/cms-sw/cmssw/pull/38301){:target="_blank"}  from **@minerva1993**: RPC DQM minor fix [12_3_X] `dqm` created: 2022-06-09 09:54:13 merged: 2022-06-14 00:37:59

22. [38297](http://github.com/cms-sw/cmssw/pull/38297){:target="_blank"}  from **@cms-trackeralign**: [12.3.X] Introduce `TkAlJetHT` `alca` `dqm` `operations` created: 2022-06-09 08:56:16 merged: 2022-06-10 11:12:16

23. [38287](http://github.com/cms-sw/cmssw/pull/38287){:target="_blank"}  from **@pmandrik**: [12_3_X] Fix ThroughputServiceClient.cc unsigned variables overflow `hlt` created: 2022-06-08 13:35:49 merged: 2022-06-11 00:51:07

24. [38264](http://github.com/cms-sw/cmssw/pull/38264){:target="_blank"}  from **@pmandrik**: [12_3_X] Update DQM beam clients playback machine type check `dqm` created: 2022-06-06 18:23:24 merged: 2022-06-09 23:59:54

25. [38258](http://github.com/cms-sw/cmssw/pull/38258){:target="_blank"}  from **@pmandrik**: [12_3_X] Fix streamLabel name in hcalgpu_dqm_sourceclient-live_cfg.p `dqm` created: 2022-06-06 14:23:42 merged: 2022-06-09 23:59:04

26. [38100](http://github.com/cms-sw/cmssw/pull/38100){:target="_blank"}  from **@quark2**: Revive of reverted #37852 with a fix on the issue #38044 `dqm` `simulation` created: 2022-05-27 13:42:14 merged: 2022-06-13 06:04:16

27. [38067](http://github.com/cms-sw/cmssw/pull/38067){:target="_blank"}  from **@silviodonato**: Sort pixel tracks in the SoA converter (12_3_X) `reconstruction` created: 2022-05-24 16:33:39 merged: 2022-06-11 00:52:20

#### CMSDIST Changes between Tags REL/CMSSW_12_3_5_patch1/slc7_amd64_gcc10 and REL/CMSSW_12_3_6/slc7_amd64_gcc10:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_12_3_5_patch1/slc7_amd64_gcc10...REL/CMSSW_12_3_6/slc7_amd64_gcc10)


