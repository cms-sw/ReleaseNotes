---
layout: post
rel_link:  "14_0_1"
title:  "CMSSW_14_0_1"
date:   2024-03-02 11:13:22
categories: cmssw
relmajor: 14
relminor: 0
relsubminor: 1
---

# CMSSW_14_0_1
#### Changes since CMSSW_14_0_0:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_0_0...CMSSW_14_0_1)



1. [44278](http://github.com/cms-sw/cmssw/pull/44278){:target="_blank"}  from **@jsamudio**: [14_0_X] Fix logic in PFClusterSoAProducer kernels `reconstruction` `heterogeneous` `pf` created: 2024-02-29 20:40:42 merged: 2024-03-01 11:01:06

2. [44253](http://github.com/cms-sw/cmssw/pull/44253){:target="_blank"}  from **@mmusich**: [14.0.X] add failsafes for protecting the alpaka customization against `Fake` HLT menus `hlt` created: 2024-02-27 21:19:01 merged: 2024-02-29 15:05:44

3. [44094](http://github.com/cms-sw/cmssw/pull/44094){:target="_blank"}  from **@bsunanda**: Run3-gex176F Backport the correction to 2024 Geometry to CMSSW_14_0_X due to RPC detector (backport of #44065 and #44093) `geometry` created: 2024-02-27 04:44:45 merged: 2024-02-29 15:06:49

4. [44089](http://github.com/cms-sw/cmssw/pull/44089){:target="_blank"}  from **@yeckang**: [GEM][bug fix][backport] avoid the segmentation fault caused by the 2024 GEMGeometry `l1` created: 2024-02-26 15:51:36 merged: 2024-02-29 15:27:40

5. [44086](http://github.com/cms-sw/cmssw/pull/44086){:target="_blank"}  from **@theochatzis**: [14_0_X] Jet phi variable in L1 correction `analysis` created: 2024-02-26 13:00:44 merged: 2024-02-29 11:01:41

6. [44082](http://github.com/cms-sw/cmssw/pull/44082){:target="_blank"}  from **@fwyzard**: Correct the FindClus block size [14.0.x] `reconstruction` `trk` created: 2024-02-26 01:17:00 merged: 2024-02-28 16:55:00

7. [44080](http://github.com/cms-sw/cmssw/pull/44080){:target="_blank"}  from **@mmusich**: [14.0.X] Update 2024 MC GTs with the L1 menu `alca` created: 2024-02-25 13:11:38 merged: 2024-02-28 16:52:33

8. [44079](http://github.com/cms-sw/cmssw/pull/44079){:target="_blank"}  from **@fabiocos**: [Backport of 43846 to 14_0_X] Primary vertex reconstruction: update configuration handling `alca` `dqm` `reconstruction` `tracking` `trk` created: 2024-02-25 12:18:47 merged: 2024-02-29 15:28:06

9. [44076](http://github.com/cms-sw/cmssw/pull/44076){:target="_blank"}  from **@AdrianoDee**: [14_0_X] Updates for 2024 Wfs (PR Testing, IBs, Patatrack, inputs) `pdmv` `upgrade` created: 2024-02-25 00:32:44 merged: 2024-02-29 10:42:26

10. [44074](http://github.com/cms-sw/cmssw/pull/44074){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for 14_0_X (2/N) `hlt` created: 2024-02-24 17:13:30 merged: 2024-02-28 16:52:47

11. [44071](http://github.com/cms-sw/cmssw/pull/44071){:target="_blank"}  from **@jsamudio**: [14.0.X] Remove unnecessary ESProducer from LegacyPFClusterProducer `hlt` `reconstruction` `pf` created: 2024-02-24 06:30:29 merged: 2024-02-29 10:50:44

12. [44056](http://github.com/cms-sw/cmssw/pull/44056){:target="_blank"}  from **@missirol**: print total number of Paths in `hltIntegrationTests` [`14_0_X`] `hlt` created: 2024-02-22 08:40:58 merged: 2024-02-26 20:25:51

13. [44045](http://github.com/cms-sw/cmssw/pull/44045){:target="_blank"}  from **@saumyaphor4252**: [14.0.X] Update Run3 HLT GT with PPS conditions for 2024 data-taking `alca` created: 2024-02-21 17:04:31 merged: 2024-02-26 20:26:27

14. [44043](http://github.com/cms-sw/cmssw/pull/44043){:target="_blank"}  from **@rbhattacharya04**: Mu pog nano aod v2 backport `pdmv` `upgrade` `xpog` created: 2024-02-21 15:19:35 merged: 2024-02-26 20:27:04

15. [44042](http://github.com/cms-sw/cmssw/pull/44042){:target="_blank"}  from **@fwyzard**: Let tests fail gracefully if no devices are found [14.0.x] `reconstruction` `heterogeneous` `tracking` `trk` created: 2024-02-21 14:23:40 merged: 2024-02-26 20:27:49

16. [44040](http://github.com/cms-sw/cmssw/pull/44040){:target="_blank"}  from **@mbluj**: Lepton time-life info for NanoAOD and Nano branches from ValueMap of elaborated types (14_0_X) `reconstruction` `xpog` `tracking` created: 2024-02-21 12:14:17 merged: 2024-02-29 15:28:55

17. [44030](http://github.com/cms-sw/cmssw/pull/44030){:target="_blank"}  from **@mmusich**: [14.0.X] Update `SiStripLorentzAnglePCLHarvester` to avoid writing useless payloads and more control plots  `alca` `trk` created: 2024-02-20 15:24:51 merged: 2024-02-21 17:42:49

18. [44027](http://github.com/cms-sw/cmssw/pull/44027){:target="_blank"}  from **@cms-tsg-storm**: Move relval2023 to point to Fake2 for HLT [140X] `hlt` `pdmv` `upgrade` created: 2024-02-20 12:14:58 merged: 2024-02-29 10:53:53

19. [44024](http://github.com/cms-sw/cmssw/pull/44024){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for 14_0_X (1/N) [14_0_X] `hlt` created: 2024-02-20 09:10:33 merged: 2024-02-23 14:46:24

20. [44022](http://github.com/cms-sw/cmssw/pull/44022){:target="_blank"}  from **@fwyzard**: Move SoA collections ROOT read rules to classes.cc [14.0.x] `reconstruction` `simulation` `ecal` `pf` created: 2024-02-20 08:38:23 merged: 2024-02-26 20:28:12

21. [44016](http://github.com/cms-sw/cmssw/pull/44016){:target="_blank"}  from **@cms-tsg-storm**: Bugfix in fillDescriptions of EgammaHLTClusterShapeProducer [140X] `hlt` created: 2024-02-19 15:30:50 merged: 2024-02-21 18:11:31

22. [44014](http://github.com/cms-sw/cmssw/pull/44014){:target="_blank"}  from **@makortel**: [14_0_X] Simplify definition of `PortableMultiCollection<TDev, ...>`, and allow it to be used outside of `ALPAKA_ACCELERATOR_NAMESPACE` `heterogeneous` created: 2024-02-19 15:26:01 merged: 2024-02-21 18:20:33

23. [44007](http://github.com/cms-sw/cmssw/pull/44007){:target="_blank"}  from **@missirol**: add option to restrict single-Path jobs of hltIntegrationTests to a subset of triggers [`14_0_X`] `hlt` created: 2024-02-19 08:47:49 merged: 2024-02-21 18:09:37

24. [44000](http://github.com/cms-sw/cmssw/pull/44000){:target="_blank"}  from **@waredjeb**: [14.0.X] Fix HLT customization for alpaka PF `hlt` `pf` created: 2024-02-16 16:22:10 merged: 2024-02-23 14:47:16

25. [43995](http://github.com/cms-sw/cmssw/pull/43995){:target="_blank"}  from **@nurfikri89**: [MiniAOD] Backport of #43965 (Increase AK4 CHS pt cut and remove unsupported taggers for AK4 CHS and AK8 Puppi jets) to 14_0_X `reconstruction` `xpog` `btv` `jetmet` created: 2024-02-16 11:38:16 merged: 2024-02-21 18:19:47

26. [43993](http://github.com/cms-sw/cmssw/pull/43993){:target="_blank"}  from **@francescobrivio**: [14_0_X] Update LHCInfoProducer to use LHCInfoCombined `alca` `dqm` `xpog` `trk` created: 2024-02-16 09:05:38 merged: 2024-02-26 20:28:43

27. [43992](http://github.com/cms-sw/cmssw/pull/43992){:target="_blank"}  from **@nurfikri89**: [NanoAOD] Backport of #43966 (Add EM energy fraction for CorrT1METJet) to 14_0_X `xpog` created: 2024-02-16 07:57:50 merged: 2024-02-21 19:28:44

28. [43991](http://github.com/cms-sw/cmssw/pull/43991){:target="_blank"}  from **@yeckang**: [GEM][backport] GEMGeometryBuilder update for the 2024 geometry `geometry` `upgrade` created: 2024-02-16 06:40:36 merged: 2024-02-21 17:58:10

29. [43990](http://github.com/cms-sw/cmssw/pull/43990){:target="_blank"}  from **@bsunanda**: Run3-gex176X Backport #43978 of the modification of the sub-scenario of the RPC section for the 2024 scenario `geometry` created: 2024-02-16 00:45:55 merged: 2024-02-21 17:57:30

30. [43989](http://github.com/cms-sw/cmssw/pull/43989){:target="_blank"}  from **@pallabidas**: [Phase-2 L1T 14_0_X] small fixes for RCT cluster emulation `l1` `upgrade` created: 2024-02-15 22:22:59 merged: 2024-02-26 20:28:56

31. [43985](http://github.com/cms-sw/cmssw/pull/43985){:target="_blank"}  from **@eyigitba**: [14_0_X] Remove unpackLayer1 option from L1REPACK:Full `operations` created: 2024-02-15 17:44:44 merged: 2024-02-26 21:59:39

32. [43970](http://github.com/cms-sw/cmssw/pull/43970){:target="_blank"}  from **@bsunanda**: Run3-gex175X Backport #43876 to CMSSW version 14_0_X the changes for te 2024 version of GE21 geometry `geometry` created: 2024-02-15 02:38:44 merged: 2024-02-21 17:57:19

#### CMSDIST Changes between Tags REL/CMSSW_14_0_0/el8_amd64_gcc12 and REL/CMSSW_14_0_1/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_0_0/el8_amd64_gcc12...REL/CMSSW_14_0_1/el8_amd64_gcc12)



1. [9038](http://github.com/cms-sw/cmsdist/pull/9038){:target="_blank"}  from **@epalencia**: [14_0_X] Update UTM to 0.12.0 created: 2024-02-28 08:05:30 merged: 2024-02-29 09:46:45
