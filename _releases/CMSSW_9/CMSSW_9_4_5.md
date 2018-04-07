---
layout: post
rel_link:  "9_4_5"
title:  "CMSSW_9_4_5"
date:   2018-04-06 13:44:27
categories: cmssw
relmajor: 9
relminor: 4
relsubminor: 5
---

# CMSSW_9_4_5
#### Changes since CMSSW_9_4_4:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_9_4_4...CMSSW_9_4_5)



1. [22638](http://github.com/cms-sw/cmssw/pull/22638){:target="_blank"}  from **@arunhep**: JECs update for AK4PF, AK8PF, and AK8PFchs `alca`  created: 2018-03-15 21:36:33 merged: 2018-03-16 16:39:21



2. [22623](http://github.com/cms-sw/cmssw/pull/22623){:target="_blank"}  from **@Sam-Harper**: EGamma Scale & Smearing For Re-miniAOD : 94X `analysis`  `reconstruction`  created: 2018-03-14 22:31:02 merged: 2018-03-15 18:08:01



3. [22550](http://github.com/cms-sw/cmssw/pull/22550){:target="_blank"}  from **@Sam-Harper**: adding Egamma 2016/2017 IDs to MiniAOD : 94X MiniAOD `analysis`  `reconstruction`  created: 2018-03-09 15:02:47 merged: 2018-03-13 09:21:54



4. [22520](http://github.com/cms-sw/cmssw/pull/22520){:target="_blank"}  from **@apana**: Remove unnecessary updating of bx mask arrays `l1`  created: 2018-03-08 04:17:58 merged: 2018-03-15 17:36:59



5. [22508](http://github.com/cms-sw/cmssw/pull/22508){:target="_blank"}  from **@ahinzmann**: Add puppi multiplicities to MiniAOD - 94X backport `analysis`  `reconstruction`  created: 2018-03-07 13:20:25 merged: 2018-03-10 16:26:40



6. [22445](http://github.com/cms-sw/cmssw/pull/22445){:target="_blank"}  from **@bbockelm**: Optimize NanoAOD buffers at 1k events. `analysis`  created: 2018-03-03 18:20:46 merged: 2018-03-17 09:51:02



7. [22440](http://github.com/cms-sw/cmssw/pull/22440){:target="_blank"}  from **@jhgoh**: GenParticles2HepMCConverter null pointer protection `generators`  created: 2018-03-03 05:18:20 merged: 2018-03-17 09:52:48



8. [22410](http://github.com/cms-sw/cmssw/pull/22410){:target="_blank"}  from **@jainshilpi**: Ported 80X regression in 94X `reconstruction`  created: 2018-03-01 22:52:04 merged: 2018-03-17 10:25:48



9. [22381](http://github.com/cms-sw/cmssw/pull/22381){:target="_blank"}  from **@lpernie**: [Update GT] High Level conditions for 2017miniAOD rereco `alca`  created: 2018-02-27 21:52:22 merged: 2018-03-05 21:06:21



10. [22347](http://github.com/cms-sw/cmssw/pull/22347){:target="_blank"}  from **@danbarto**: Updating MET Significance Parameters with 80X Run2016 tune `reconstruction`  created: 2018-02-26 12:54:46 merged: 2018-03-10 18:45:16



11. [22345](http://github.com/cms-sw/cmssw/pull/22345){:target="_blank"}  from **@cms-met**: Fix in MET tool when reclustering jets and MET on the fly [backport] `analysis`  `reconstruction`  created: 2018-02-26 12:04:38 merged: 2018-03-10 19:28:01



12. [22343](http://github.com/cms-sw/cmssw/pull/22343){:target="_blank"}  from **@fabozzi**: re-miniAOD workflows on 94X input datasets (94MAOD) `pdmv`  `upgrade`  created: 2018-02-26 11:39:20 merged: 2018-03-08 09:06:40



13. [22332](http://github.com/cms-sw/cmssw/pull/22332){:target="_blank"}  from **@apana**: Add fix for different indexing convention in early uGT prescale columns `l1`  created: 2018-02-23 21:13:48 merged: 2018-02-27 10:14:16



14. [22303](http://github.com/cms-sw/cmssw/pull/22303){:target="_blank"}  from **@guitargeek**: Implementation of 2017 MVA Electron ID : 94X MiniAOD `reconstruction`  created: 2018-02-22 16:07:07 merged: 2018-03-02 09:10:37



15. [22302](http://github.com/cms-sw/cmssw/pull/22302){:target="_blank"}  from **@lsoffi**: 2017 Photon ID (cut based +MVA) Electron ID (cut based) implementation : 94X MiniAOD `analysis`  `reconstruction`  created: 2018-02-22 16:01:02 merged: 2018-03-01 18:42:03



16. [22294](http://github.com/cms-sw/cmssw/pull/22294){:target="_blank"}  from **@HEP-KBFI**: Fixed segmentation violation in PhysicsTools/SelectorUtils/interface/PFJetIDSelectionFunctor in case subjets are of type pat::Jet `analysis`  `reconstruction`  created: 2018-02-22 08:01:01 merged: 2018-03-02 17:49:44



17. [22132](http://github.com/cms-sw/cmssw/pull/22132){:target="_blank"}  from **@gpetruc**: Fix reading prescale values during miniAOD production (94X) `analysis`  `l1`  `reconstruction`  created: 2018-02-06 14:59:43 merged: 2018-03-16 09:45:09



18. [22128](http://github.com/cms-sw/cmssw/pull/22128){:target="_blank"}  from **@fabozzi**: Adding harvesting step to NANOAOD workflows (94X) `pdmv`  `upgrade`  created: 2018-02-06 11:44:48 merged: 2018-02-06 22:23:01



19. [22125](http://github.com/cms-sw/cmssw/pull/22125){:target="_blank"}  from **@gpetruc**: Fix dE/dx hit association index (94X) `analysis`  `reconstruction`  created: 2018-02-06 11:08:59 merged: 2018-02-15 16:35:46



20. [22093](http://github.com/cms-sw/cmssw/pull/22093){:target="_blank"}  from **@rappoccio**: Adding capability to write out Ptrs in JetConstituentSelector (Backport of #22092) `analysis`  `reconstruction`  created: 2018-02-02 14:10:19 merged: 2018-02-15 16:32:01



21. [22042](http://github.com/cms-sw/cmssw/pull/22042){:target="_blank"}  from **@pablodecm**: Backport to 9_4_X of DeepFlavour and TF API `analysis`  `reconstruction`  created: 2018-01-30 15:47:35 merged: 2018-02-15 16:33:40



22. [21989](http://github.com/cms-sw/cmssw/pull/21989){:target="_blank"}  from **@slava77**: treat non-pos-def covariance as if it contains a NaN `reconstruction`  created: 2018-01-26 21:16:41 merged: 2018-03-02 08:34:53



23. [21977](http://github.com/cms-sw/cmssw/pull/21977){:target="_blank"}  from **@cms-tau-pog**: New trainings for mvaTauID + one backport from CMSSW_10_0_X `analysis`  `operations`  `reconstruction`  created: 2018-01-26 16:55:06 merged: 2018-03-05 16:28:00



24. [21941](http://github.com/cms-sw/cmssw/pull/21941){:target="_blank"}  from **@ahinzmann**: Puppi weighted multiplicities, 94X backport `analysis`  `reconstruction`  created: 2018-01-24 13:02:59 merged: 2018-02-15 09:28:03



25. [21929](http://github.com/cms-sw/cmssw/pull/21929){:target="_blank"}  from **@mrodozov**: Backport updated python AI pkgs tests `analysis`  created: 2018-01-23 15:31:27 merged: 2018-02-15 09:33:29



26. [21882](http://github.com/cms-sw/cmssw/pull/21882){:target="_blank"}  from **@lpernie**: [94X GT update][2017 MC] Hcal MCParams update `alca`  created: 2018-01-18 04:16:08 merged: 2018-02-14 08:20:24



27. [21773](http://github.com/cms-sw/cmssw/pull/21773){:target="_blank"}  from **@Dr15Jones**: Revert making a copy of RefCore in RefVector calls `core`  created: 2017-12-22 02:02:50 merged: 2018-02-13 15:23:57



#### CMSDIST Changes between Tags REL/CMSSW_9_4_4/slc6_amd64_gcc630 and REL/CMSSW_9_4_5/slc6_amd64_gcc630:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_9_4_4/slc6_amd64_gcc630...REL/CMSSW_9_4_5/slc6_amd64_gcc630)



1. [3818](http://github.com/cms-sw/cmsdist/pull/3818){:target="_blank"}  from **@cms-sw**: Update data-Fireworks-Geometry.spec created: 2018-03-07 20:41:37 merged: 2018-03-08 21:11:58

2. [3813](http://github.com/cms-sw/cmsdist/pull/3813){:target="_blank"}  from **@cms-sw**: root [94X]: Fix ROOT-8359: the first compiler we look for is the one the path created: 2018-03-07 10:52:05 merged: 2018-03-07 20:23:15

3. [3774](http://github.com/cms-sw/cmsdist/pull/3774){:target="_blank"}  from **@cms-sw**: Update RecoEgamma-ElectronIdentification to new tag created: 2018-02-26 14:32:37 merged: 2018-03-01 14:35:31

4. [3773](http://github.com/cms-sw/cmsdist/pull/3773){:target="_blank"}  from **@cms-sw**: new EgammaAnalysis-ElectronTools data package for 94X created: 2018-02-26 10:47:37 merged: 2018-03-05 21:40:05

5. [3763](http://github.com/cms-sw/cmsdist/pull/3763){:target="_blank"}  from **@cms-sw**: Move the RecoEgamma-PhotonIdentification tag from 04 to 05 created: 2018-02-23 08:57:24 merged: 2018-03-01 14:28:50
