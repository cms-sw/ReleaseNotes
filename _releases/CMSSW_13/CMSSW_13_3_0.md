---
layout: post
rel_link:  "13_3_0"
title:  "CMSSW_13_3_0"
date:   2023-11-20 12:46:40
categories: cmssw
relmajor: 13
relminor: 3
relsubminor: 0
---

# CMSSW_13_3_0
#### Changes since CMSSW_13_3_0_pre5:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_13_3_0_pre5...CMSSW_13_3_0)



1. [43325](http://github.com/cms-sw/cmssw/pull/43325){:target="_blank"}  from **@missirol**: Do not use `size() - 1` in `HLTL1TMatchedJetsVBFFilter` [`13_3_X`] `hlt` created: 2023-11-18 11:43:33 merged: 2023-11-18 16:52:41

2. [43301](http://github.com/cms-sw/cmssw/pull/43301){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `13_2_X` (5/N) [`13_3_X`] `hlt` `operations` created: 2023-11-16 12:38:49 merged: 2023-11-17 15:51:13

3. [43292](http://github.com/cms-sw/cmssw/pull/43292){:target="_blank"}  from **@iasonkrom**: [CMSSW_13_3_X backport] Add CaloIdL_MW seeded filter and split the legs of CaloIdL_TrackIdL_IsoVL filter on nanoAOD filterBits `xpog` `egamma` created: 2023-11-15 15:00:17 merged: 2023-11-17 15:03:36

4. [43287](http://github.com/cms-sw/cmssw/pull/43287){:target="_blank"}  from **@francescobrivio**: [13_3_X] Vertex smearing for PbPb MC based on 2023 PbPb data `operations` `simulation` created: 2023-11-15 13:04:18 merged: 2023-11-17 13:58:06

5. [43286](http://github.com/cms-sw/cmssw/pull/43286){:target="_blank"}  from **@Prasant1993**: [CMSSW_13_3_X backport] Add Correct EGM Run3 electron NonIso MVA ID for EB `reconstruction` created: 2023-11-15 12:56:04 merged: 2023-11-17 15:35:32

6. [43280](http://github.com/cms-sw/cmssw/pull/43280){:target="_blank"}  from **@fwyzard**: Introduce new utilities for writing Alpaka kernels [13.3.x] `heterogeneous` created: 2023-11-14 22:28:47 merged: 2023-11-16 15:06:59

7. [43254](http://github.com/cms-sw/cmssw/pull/43254){:target="_blank"}  from **@maxgalli**: Revert decrease of precision introduced in ea3f693d `xpog` created: 2023-11-13 12:41:51 merged: 2023-11-17 13:55:57

8. [43241](http://github.com/cms-sw/cmssw/pull/43241){:target="_blank"}  from **@fwyzard**: Implement ROOT read rules for PortableHostCollection [13.3.x] `heterogeneous` created: 2023-11-09 17:38:42 merged: 2023-11-13 14:13:37

9. [43230](http://github.com/cms-sw/cmssw/pull/43230){:target="_blank"}  from **@mmusich**: [13.3.X] migrate `JetMETDQMDCSFilter` to use `DSCRecord`  `dqm` created: 2023-11-09 04:47:21 merged: 2023-11-13 14:13:57

10. [43221](http://github.com/cms-sw/cmssw/pull/43221){:target="_blank"}  from **@mmusich**: [13.3.X] customize HLT offline DQM for Run3 PbPb and introduce HI 2023A relval workflow (with reHLT) `dqm` `operations` `pdmv` `upgrade` created: 2023-11-08 10:37:00 merged: 2023-11-13 12:22:40

11. [43215](http://github.com/cms-sw/cmssw/pull/43215){:target="_blank"}  from **@francescobrivio**: [13_3_X] Add SimBeamSpotObject record to Run-1/2/3 MC GTs `alca` created: 2023-11-07 11:23:24 merged: 2023-11-13 14:14:19

12. [43209](http://github.com/cms-sw/cmssw/pull/43209){:target="_blank"}  from **@Prasant1993**:  [CMSSW_13_3_X Backport] Add superclusterEta of photon in NanoAOD `xpog` created: 2023-11-06 20:14:17 merged: 2023-11-13 14:16:57

13. [43207](http://github.com/cms-sw/cmssw/pull/43207){:target="_blank"}  from **@bsunanda**: Phase2-hgx348D Update HGCSiliconDetId in view of adding a fourth type of wafer: high density but thicker (backport of #43196) `geometry` `simulation` `upgrade` created: 2023-11-06 19:35:50 merged: 2023-11-13 14:17:51

14. [43206](http://github.com/cms-sw/cmssw/pull/43206){:target="_blank"}  from **@bsunanda**: Run3-hcx354X Modify the DetId fo ZDC to accommodate the changes that happened during Run3 and some provision for the future (backport of #43200) `geometry` `simulation` `db` created: 2023-11-06 19:17:03 merged: 2023-11-13 14:18:08

15. [43194](http://github.com/cms-sw/cmssw/pull/43194){:target="_blank"}  from **@bsunanda**: Phase2-hgx348B Take care of handling both HGCal and HFNose access to Geometry and Topology classes `geometry` `upgrade` created: 2023-11-05 14:33:59 merged: 2023-11-06 16:21:44

16. [43178](http://github.com/cms-sw/cmssw/pull/43178){:target="_blank"}  from **@bsunanda**: Phase2-sim150 Update the scripts in SimG4Core/PrintGeomInfo `simulation` created: 2023-11-03 13:35:03 merged: 2023-11-03 21:02:49

17. [43171](http://github.com/cms-sw/cmssw/pull/43171){:target="_blank"}  from **@abdoulline**: Adding lumi=0 defaults to hardcode HB PFCuts for Phase2 `alca` created: 2023-11-02 12:15:45 merged: 2023-11-03 21:02:13

18. [43170](http://github.com/cms-sw/cmssw/pull/43170){:target="_blank"}  from **@smuzaffar**: Use likelihood fit instead of chi-square fit for PFJetDQMPostProcessor plugin `dqm` created: 2023-11-02 11:59:42 merged: 2023-11-06 16:20:27

19. [43167](http://github.com/cms-sw/cmssw/pull/43167){:target="_blank"}  from **@bsunanda**: Phase2-hgx348A Make use of constexpr in the scintillator DeId for HGCal for better processing `simulation` `upgrade` created: 2023-11-02 08:32:10 merged: 2023-11-06 16:18:20

20. [43165](http://github.com/cms-sw/cmssw/pull/43165){:target="_blank"}  from **@tvami**: Fix upper bound of the scale in SUEP shower simulation `generators` created: 2023-11-01 22:49:24 merged: 2023-11-03 20:54:42

21. [43163](http://github.com/cms-sw/cmssw/pull/43163){:target="_blank"}  from **@fwyzard**: Improve the error message when trying to call a kernel from a .cc file `heterogeneous` created: 2023-11-01 17:02:20 merged: 2023-11-03 21:01:38

22. [43161](http://github.com/cms-sw/cmssw/pull/43161){:target="_blank"}  from **@bsunanda**: Run3-hcx353 Merging the changes of ZDC code from Anna which was used by the ZDC collaboration for the Run2 setup `geometry` `simulation` created: 2023-11-01 10:02:40 merged: 2023-11-03 21:01:09

23. [43160](http://github.com/cms-sw/cmssw/pull/43160){:target="_blank"}  from **@francescobrivio**: Update SimBeamSpotObjects to handle different EvtVtxGenerators `alca` `simulation` `db` `tracking` created: 2023-10-31 18:16:25 merged: 2023-11-03 20:59:37

24. [43145](http://github.com/cms-sw/cmssw/pull/43145){:target="_blank"}  from **@trackreco**: [mkFit] Tools supporting better layer-related computations -- technical changes to support further development `reconstruction` `tracking` created: 2023-10-29 10:44:13 merged: 2023-11-03 21:05:30

25. [43138](http://github.com/cms-sw/cmssw/pull/43138){:target="_blank"}  from **@wpmccormack**: Updating SONIC ParticleNet Producer and Config Files `reconstruction` created: 2023-10-27 19:44:29 merged: 2023-11-03 20:56:17

26. [43124](http://github.com/cms-sw/cmssw/pull/43124){:target="_blank"}  from **@fabiocos**: MTD geometry: speed up MTD reco geometry construction `geometry` `upgrade` created: 2023-10-26 15:49:36 merged: 2023-11-06 10:30:21

27. [43043](http://github.com/cms-sw/cmssw/pull/43043){:target="_blank"}  from **@dinyar**: Use ZDC digis in uGT DQM `dqm` created: 2023-10-17 17:15:08 merged: 2023-11-05 21:55:13

28. [43034](http://github.com/cms-sw/cmssw/pull/43034){:target="_blank"}  from **@aandvalenzuela**: Fix may be used uninitialized warning in `RecoTracker/MeasurementDet` (el8_aarch64_gcc12) `reconstruction` `tracking` created: 2023-10-17 08:34:19 merged: 2023-11-03 21:07:41

29. [43028](http://github.com/cms-sw/cmssw/pull/43028){:target="_blank"}  from **@Prasant1993**: Add EP combination variables to electron Table in NANOAOD  `xpog` `egamma` created: 2023-10-16 13:50:30 merged: 2023-11-03 20:53:12

#### CMSDIST Changes between Tags REL/CMSSW_13_3_0_pre5/el8_amd64_gcc12 and REL/CMSSW_13_3_0/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_13_3_0_pre5/el8_amd64_gcc12...REL/CMSSW_13_3_0/el8_amd64_gcc12)



1. [8825](http://github.com/cms-sw/cmsdist/pull/8825){:target="_blank"}  from **@Prasant1993**: [backport to IB/CMSSW_13_3_X/master] Update tag for RecoEgamma-ElectronIdentification to V01-13-00 created: 2023-11-17 12:34:43 merged: 2023-11-17 13:15:34

2. [8803](http://github.com/cms-sw/cmsdist/pull/8803){:target="_blank"}  from **@cms-sw**: Update tag for RecoBTag-Combined to V01-19-00 created: 2023-11-03 20:56:30 merged: 2023-11-04 10:14:06

3. [8794](http://github.com/cms-sw/cmsdist/pull/8794){:target="_blank"}  from **@Dominic-Stafford**: Add fix for segfault in Min Bias created: 2023-10-30 15:05:01 merged: 2023-11-04 10:24:42
