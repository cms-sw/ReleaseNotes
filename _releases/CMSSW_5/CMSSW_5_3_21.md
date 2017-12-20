---
layout: post
rel_link:  "5_3_21"
title:  "CMSSW_5_3_21"
date:   2016-09-05 16:00:40
categories: cmssw
relmajor: 5
relminor: 3
relsubminor: 21
---

# CMSSW_5_3_21
#### Changes since CMSSW_5_3_20:

[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_5_3_20...CMSSW_5_3_21)



1. [5672](http://github.com/cms-sw/cmssw/pull/5672){:target="_blank"}  from **@smuzaffar**: remove C++11 keywords for 53x `generators`  created: 2014-10-03 12:37:47 merged: 2014-10-03 12:39:51

2. [5498](http://github.com/cms-sw/cmssw/pull/5498){:target="_blank"}  from **@franzoni**: RequestType RequestPriority for relval submission `operations`  created: 2014-09-23 08:38:54 merged: 2014-10-03 06:38:27

3. [5632](http://github.com/cms-sw/cmssw/pull/5632){:target="_blank"}  from **@bendavid**: backport of single-step wmLHE+GEN-SIM and two output handling to 53x (ConfigBuilder) `operations`  created: 2014-09-30 23:31:57 merged: 2014-10-03 06:36:11

4. [5617](http://github.com/cms-sw/cmssw/pull/5617){:target="_blank"}  from **@bendavid**: Backport of GenLumiInfoProduct and associated cross section machinery to 53x `generators`  created: 2014-09-30 02:27:16 merged: 2014-10-03 06:35:30

5. [5639](http://github.com/cms-sw/cmssw/pull/5639){:target="_blank"}  from **@bendavid**: add (and enable) option to override SPINUP in lhe file for Pythia8 tau decays `generators`  created: 2014-10-01 17:46:44 merged: 2014-10-03 06:35:10

6. [5648](http://github.com/cms-sw/cmssw/pull/5648){:target="_blank"}  from **@bendavid**: remove C++11 keywords from 53x `generators`  created: 2014-10-02 08:47:03 merged: 2014-10-02 14:47:41

7. [5600](http://github.com/cms-sw/cmssw/pull/5600){:target="_blank"}  from **@bendavid**: Generator Interface backports for Pythia 8, LHE input, jet matching `generators`  created: 2014-09-28 19:10:40 merged: 2014-10-01 08:53:41

8. [5130](http://github.com/cms-sw/cmssw/pull/5130){:target="_blank"}  from **@inugent**: backport of TauolaInterface for Tauola 1.1.4 from 7_2_X to 5_3_X `generators`  created: 2014-09-01 16:13:23 merged: 2014-09-09 15:41:34

9. [5181](http://github.com/cms-sw/cmssw/pull/5181){:target="_blank"}  from **@apfeiffer1**: renamed script with a uniqe name to avoid clashes when installing/using `db`  created: 2014-09-05 07:39:54 merged: 2014-09-05 08:47:13

10. [5101](http://github.com/cms-sw/cmssw/pull/5101){:target="_blank"}  from **@smuzaffar**: disable running of testUtilitiesStorageFactory and testUtilitiesRFIOAdaptor via scram unittests/runtests created: 2014-08-29 07:31:47 merged: 2014-08-29 07:31:54

11. [5026](http://github.com/cms-sw/cmssw/pull/5026){:target="_blank"}  from **@sdevissc**: HQ filter 53 x `generators`  created: 2014-08-21 22:44:07 merged: 2014-08-26 18:38:03

12. [4736](http://github.com/cms-sw/cmssw/pull/4736){:target="_blank"}  from **@mkirsano**: to be compatible with the upgrade to thepeg 1.9.2 and herwigpp 2.7.1 `generators`  created: 2014-07-22 10:36:48 merged: 2014-08-25 08:42:35

13. [4609](http://github.com/cms-sw/cmssw/pull/4609){:target="_blank"}  from **@wmtan**: Allow option of reading of files with prior releases (for 5_3_X) `core`  created: 2014-07-10 22:36:31 merged: 2014-07-22 15:50:59

#### CMSDIST Changes between Tags REL/CMSSW_5_3_20/slc6_amd64_gcc472 and REL/CMSSW_5_3_21/slc6_amd64_gcc472:

[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_5_3_20/slc6_amd64_gcc472...REL/CMSSW_5_3_21/slc6_amd64_gcc472)



1. [1080](http://github.com/cms-sw/cmsdist/pull/1080){:target="_blank"}  from **@smuzaffar**: relocate bin/cython and bin/cygdb to use python from path created: 2014-10-02 11:18:12 merged: 2014-10-02 11:18:35

2. [1078](http://github.com/cms-sw/cmsdist/pull/1078){:target="_blank"}  from **@smuzaffar**: Add lhapdf6 tool with its dependency keeping it inactive created: 2014-10-02 06:45:40 merged: 2014-10-02 06:45:50

3. [1063](http://github.com/cms-sw/cmsdist/pull/1063){:target="_blank"}  from **@bendavid**: Update to Pythia 8.200pre2 (53x) created: 2014-09-28 19:07:08 merged: 2014-10-01 08:50:00

4. [1002](http://github.com/cms-sw/cmsdist/pull/1002){:target="_blank"}  from **@smuzaffar**: updated scram and config tags created: 2014-09-09 21:27:06 merged: 2014-09-09 21:27:10

5. [997](http://github.com/cms-sw/cmsdist/pull/997){:target="_blank"}  from **@smuzaffar**: updated to tauolapp 1.1.4 created: 2014-09-09 15:37:14 merged: 2014-09-09 15:39:54

6. [970](http://github.com/cms-sw/cmsdist/pull/970){:target="_blank"}  from **@smuzaffar**: updated scram version to V2_2_5 which contains bug fix for firstline comment in BuildFiles created: 2014-08-29 10:15:03 merged: 2014-08-29 10:15:07

7. [966](http://github.com/cms-sw/cmsdist/pull/966){:target="_blank"}  from **@smuzaffar**: scram-project-build: sync with 72x changes created: 2014-08-28 08:10:39 merged: 2014-08-28 08:10:43

8. [957](http://github.com/cms-sw/cmsdist/pull/957){:target="_blank"}  from **@smuzaffar**: use latest config and SCRAM created: 2014-08-27 09:04:03 merged: 2014-08-27 09:04:12

9. [947](http://github.com/cms-sw/cmsdist/pull/947){:target="_blank"}  from **@smuzaffar**: SLC6: upgrade to herwigpp 2.7.1 and thepeg 1.9.2 created: 2014-08-25 08:41:12 merged: 2014-08-25 08:42:20
