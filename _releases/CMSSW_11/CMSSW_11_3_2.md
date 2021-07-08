---
layout: post
rel_link:  "11_3_2"
title:  "CMSSW_11_3_2"
date:   2021-07-07 14:09:09
categories: cmssw
relmajor: 11
relminor: 3
relsubminor: 2
---

# CMSSW_11_3_2
#### Changes since CMSSW_11_3_1_patch1:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_11_3_1_patch1...CMSSW_11_3_2)



1. [34354](http://github.com/cms-sw/cmssw/pull/34354){:target="_blank"}  from **@cecilecaillol**: L1T uGT: Three body invariant mass for muons backport `l1` created: 2021-07-06 15:25:19 merged: 2021-07-06 23:44:03

2. [34347](http://github.com/cms-sw/cmssw/pull/34347){:target="_blank"}  from **@mmusich**: fix definition override in RecoTrackerP5_cff.py [11_3_X] `reconstruction` created: 2021-07-06 07:53:50 merged: 2021-07-07 00:54:06

3. [34341](http://github.com/cms-sw/cmssw/pull/34341){:target="_blank"}  from **@abhih1**: Add new plots to ECAL Offline DQM with Pedestal and Laser transparency correction from the Database `dqm` created: 2021-07-06 00:17:23 merged: 2021-07-07 13:48:26

4. [34333](http://github.com/cms-sw/cmssw/pull/34333){:target="_blank"}  from **@francescobrivio**: Update BeamSpotOnline tags for CRUZET [11_3_X] `alca` `dqm` created: 2021-07-05 14:17:37 merged: 2021-07-07 13:09:30

5. [34316](http://github.com/cms-sw/cmssw/pull/34316){:target="_blank"}  from **@mmusich**: Pixel Barycenters histograms in Tracker DQM [11_3_X] `dqm` created: 2021-07-02 09:33:10 merged: 2021-07-03 09:15:28

6. [34313](http://github.com/cms-sw/cmssw/pull/34313){:target="_blank"}  from **@MilanoBicocca-pix**: Backporting of BSOnlineProducers for Run3 `alca` `reconstruction` created: 2021-07-02 09:14:03 merged: 2021-07-06 16:00:10

7. [34293](http://github.com/cms-sw/cmssw/pull/34293){:target="_blank"}  from **@thomreis**: Fix crash in ECAL local reco on GPU if ECAL is not in the run - 113X `reconstruction` created: 2021-06-30 15:48:11 merged: 2021-07-02 00:17:57

8. [34228](http://github.com/cms-sw/cmssw/pull/34228){:target="_blank"}  from **@wonpoint4**: BackPort(#33983) MuonHLTSeed MVA Classifier to 113X `reconstruction` created: 2021-06-23 16:52:06 merged: 2021-06-25 15:41:48

9. [34189](http://github.com/cms-sw/cmssw/pull/34189){:target="_blank"}  from **@smuzaffar**: [11.3] Split DQM configuration tests in smaller set to make then run  `dqm` created: 2021-06-20 09:22:05 merged: 2021-06-21 08:44:54

10. [34166](http://github.com/cms-sw/cmssw/pull/34166){:target="_blank"}  from **@francescobrivio**: Update GEMRECO geometry in online GTs [11_3_X] `alca` created: 2021-06-17 08:53:08 merged: 2021-06-18 12:56:35

11. [34078](http://github.com/cms-sw/cmssw/pull/34078){:target="_blank"}  from **@hftsoi**: [Backport] Modify CaloLayer1 DQM for 5BX needed for Ecal `dqm` `l1` created: 2021-06-10 09:40:13 merged: 2021-06-12 00:45:44

12. [33995](http://github.com/cms-sw/cmssw/pull/33995){:target="_blank"}  from **@Sam-Harper**: Update HLT Database Parameters: 11_3_X `hlt` created: 2021-06-07 08:42:42 merged: 2021-06-08 15:42:20

13. [33965](http://github.com/cms-sw/cmssw/pull/33965){:target="_blank"}  from **@barvic**: CSCRawToDigi the examiner related fixes. CMSSW_11_3_X_backport of PR#33955 `reconstruction` created: 2021-06-03 14:33:18 merged: 2021-06-04 01:00:08

14. [33948](http://github.com/cms-sw/cmssw/pull/33948){:target="_blank"}  from **@quinnanm**: do not print SiStrip O2O passwords in dbParams_ `db` created: 2021-06-02 15:05:31 merged: 2021-06-03 11:49:36

15. [33946](http://github.com/cms-sw/cmssw/pull/33946){:target="_blank"}  from **@rekovic**: L1T: KBMTF update to coarse eta (backport) `l1` created: 2021-06-02 12:45:43 merged: 2021-06-04 07:34:20

16. [33860](http://github.com/cms-sw/cmssw/pull/33860){:target="_blank"}  from **@perrotta**: Fix corrected eta in L1TkEmParticleProducer - 113X `l1` `upgrade` created: 2021-05-27 09:40:23 merged: 2021-06-12 00:45:16

#### CMSDIST Changes between Tags REL/CMSSW_11_3_1_patch1/slc7_amd64_gcc900 and REL/CMSSW_11_3_2/slc7_amd64_gcc900:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_11_3_1_patch1/slc7_amd64_gcc900...REL/CMSSW_11_3_2/slc7_amd64_gcc900)



1. [7072](http://github.com/cms-sw/cmsdist/pull/7072){:target="_blank"}  from **@cms-sw**: [11.3][OpenLoops] Generate process_src.tgz to be uploaded as source created: 2021-06-29 08:02:46 merged: 2021-06-29 16:11:28

2. [7064](http://github.com/cms-sw/cmsdist/pull/7064){:target="_blank"}  from **@cms-sw**: [11.3] patch openloops to use curl instead of urlopen to ignore SSL cert issues created: 2021-06-27 08:52:21 merged: 2021-06-27 08:53:55

3. [7058](http://github.com/cms-sw/cmsdist/pull/7058){:target="_blank"}  from **@cms-sw**: [11.3] Update tag for RecoMuon-TrackerSeedGenerator to V00-01-00 created: 2021-06-23 21:17:01 merged: 2021-06-24 01:11:13

4. [7023](http://github.com/cms-sw/cmsdist/pull/7023){:target="_blank"}  from **@SiewYan**: Update openloops-user.coll.file created: 2021-06-13 12:02:54 merged: 2021-06-13 12:04:14

5. [6983](http://github.com/cms-sw/cmsdist/pull/6983){:target="_blank"}  from **@qliphy**: Update tag for L1Trigger-L1TMuon to V01-05-00 created: 2021-06-04 07:28:07 merged: 2021-06-04 07:32:41
