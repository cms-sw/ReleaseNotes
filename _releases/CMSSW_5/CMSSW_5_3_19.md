---
layout: post
rel_link:  "5_3_19"
title:  "CMSSW_5_3_19"
date:   2014-06-11 07:25:03
categories: cmssw
relmajor: 5
relminor: 3
relsubminor: 19
---

# CMSSW_5_3_19
#### Changes since CMSSW_5_3_18:

1. [4189](http://github.com/cms-sw/cmssw/pull/4189){:target="_blank"}  from **@vciulli**: Newtunes 53x `generators`  created: 2014-06-10 15:36:50 merged: 2014-06-10 15:47:32

2. [3556](http://github.com/cms-sw/cmssw/pull/3556){:target="_blank"}  from **@cms-btv-pog**: Updates for PAT python configuration files: Backport from 7_1_X to 5_3_X `analysis`  created: 2014-04-28 18:56:01 merged: 2014-06-03 16:15:58

3. [3795](http://github.com/cms-sw/cmssw/pull/3795){:target="_blank"}  from **@cms-btv-pog**: New mva taggers backport from 71X to 53X `analysis`  `reconstruction`  created: 2014-05-09 20:23:16 merged: 2014-06-03 16:15:39

4. [4038](http://github.com/cms-sw/cmssw/pull/4038){:target="_blank"}  from **@smuzaffar**: If no .edmplugincache file found under LD_LIBRARY_PATH then force to use one under CMSSW_BASE to avoid cat hanging `core`  created: 2014-05-28 14:13:11 merged: 2014-05-28 14:18:28

5. [4031](http://github.com/cms-sw/cmssw/pull/4031){:target="_blank"}  from **@smuzaffar**: fixed duplicateReflexLibrarySearch for patch releases `core`  created: 2014-05-28 12:52:19 merged: 2014-05-28 12:53:36

6. [3895](http://github.com/cms-sw/cmssw/pull/3895){:target="_blank"}  from **@vciulli**: Allow Powheg to run using precalculated grid  `generators`  created: 2014-05-15 21:07:18 merged: 2014-05-21 08:08:54

7. [3908](http://github.com/cms-sw/cmssw/pull/3908){:target="_blank"}  from **@bbockelm**: Fix Xrootd ReadV implementation `core`  created: 2014-05-16 17:07:20 merged: 2014-05-21 08:07:49

#### External tools chages since CMSSW_5_3_18:
- lhapdf version updated to 5.9.1
- xrootd version updated to 3.2.4
- boost 1.47.0 rebuild to avoid a lot of non virtual destructor warnings in CMSSW (slc6 only)
- root rebuilt to pick up our openssl
