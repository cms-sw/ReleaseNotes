---
layout: post
rel_link:  "14_2_0"
title:  "CMSSW_14_2_0"
date:   2024-12-05 21:04:29
categories: cmssw
relmajor: 14
relminor: 2
relsubminor: 0
---

# CMSSW_14_2_0
#### Changes since CMSSW_14_2_0_pre4:
[compare to previous](https://github.com/cms-sw/cmssw/compare/CMSSW_14_2_0_pre4...CMSSW_14_2_0)



1. [46872](http://github.com/cms-sw/cmssw/pull/46872){:target="_blank"}  from **@smuzaffar**: [14.2.X]Class version update unit test fix `core` created: 2024-12-05 06:11:16 merged: 2024-12-05 09:43:06

2. [46849](http://github.com/cms-sw/cmssw/pull/46849){:target="_blank"}  from **@martinamalberti**: [14_2_X backport]: MTD reconstruction: save correct outermost hit position also for tracks w/o last hit in mtd `reconstruction` `upgrade` created: 2024-12-02 19:55:15 merged: 2024-12-04 18:39:21

3. [46847](http://github.com/cms-sw/cmssw/pull/46847){:target="_blank"}  from **@CMSTrackerDPG**: [14_2_X] Allow using fake pixels from the digi morphing algorithm as cluster seeds but drop them from final clusters `reconstruction` `trk` created: 2024-12-02 19:20:08 merged: 2024-12-04 18:38:46

4. [46842](http://github.com/cms-sw/cmssw/pull/46842){:target="_blank"}  from **@AdrianoDee**: [14_2_X]Use `Run4` for Phase2 PU inputs `pdmv` `upgrade` created: 2024-12-02 12:09:16 merged: 2024-12-03 10:18:56

5. [46822](http://github.com/cms-sw/cmssw/pull/46822){:target="_blank"}  from **@waredjeb**: [14_2_X] TICLv5a : Improve skeleton linking and parameters tuning `hlt` `reconstruction` `upgrade` created: 2024-11-28 10:46:50 merged: 2024-12-04 18:38:17

6. [46805](http://github.com/cms-sw/cmssw/pull/46805){:target="_blank"}  from **@cms-tsg-storm**: HLT menu development for `14_1_X` (4/N)  [`14_2_X`] `alca` `hlt` created: 2024-11-26 17:54:11 merged: 2024-11-28 07:43:54

7. [46796](http://github.com/cms-sw/cmssw/pull/46796){:target="_blank"}  from **@Dr15Jones**: Fix off by 1 error in Multi5x5ClusterAlgo [14_2] `reconstruction` created: 2024-11-25 16:23:50 merged: 2024-11-26 15:09:45

8. [46792](http://github.com/cms-sw/cmssw/pull/46792){:target="_blank"}  from **@fabiocos**:  [14_2_X backport] MTD geometry: Fix MTDGeometryBuilder text to avoid rounding issues with alternative architectures `geometry` `upgrade` created: 2024-11-25 08:58:27 merged: 2024-12-04 18:38:05

9. [46785](http://github.com/cms-sw/cmssw/pull/46785){:target="_blank"}  from **@bsunanda**: Run3-hcx380X Add the 2025 scenario after correcting for the DT Shield (backport of #46705 and #46784) `geometry` `operations` `upgrade` created: 2024-11-23 08:50:11 merged: 2024-11-27 05:47:50

10. [46758](http://github.com/cms-sw/cmssw/pull/46758){:target="_blank"}  from **@smuzaffar**: [UBSAN][LST]Fix runtime error by keep the region object alive `reconstruction` `tracking` created: 2024-11-21 22:27:23 merged: 2024-11-22 12:36:20

11. [46756](http://github.com/cms-sw/cmssw/pull/46756){:target="_blank"}  from **@Dr15Jones**: avoid holding memory between events in Multi5x5ClusterProducer  `reconstruction` created: 2024-11-21 18:49:23 merged: 2024-11-22 12:35:44

12. [46754](http://github.com/cms-sw/cmssw/pull/46754){:target="_blank"}  from **@smuzaffar**: Avoid using past module for python2/3 compatibility `core` created: 2024-11-21 15:58:08 merged: 2024-11-22 08:25:33

13. [46744](http://github.com/cms-sw/cmssw/pull/46744){:target="_blank"}  from **@bsunanda**: Run3-hcx379X Creating the possibility to add the additional MB4 shield in Phase2 scenarios `geometry` `upgrade` created: 2024-11-20 12:44:16 merged: 2024-11-21 08:37:46

14. [46743](http://github.com/cms-sw/cmssw/pull/46743){:target="_blank"}  from **@bsunanda**: Phase2-hgx360V Use the keyword Run4 instead of 2026 for naming a scenario in SimG4Core/PrintGeomInfo/test/python `simulation` created: 2024-11-20 12:26:24 merged: 2024-11-21 08:36:59

15. [46737](http://github.com/cms-sw/cmssw/pull/46737){:target="_blank"}  from **@francescobrivio**: Temporary Rollback for DIP BeamSpot client `dqm` created: 2024-11-19 15:52:16 merged: 2024-11-20 19:21:10

16. [46734](http://github.com/cms-sw/cmssw/pull/46734){:target="_blank"}  from **@bsunanda**: Phase2-hgx360U Update the code for guard ring and mouse bite usage in full and partial wafers in HGCal geometry definition `simulation` created: 2024-11-19 13:38:24 merged: 2024-11-21 08:37:35

17. [46733](http://github.com/cms-sw/cmssw/pull/46733){:target="_blank"}  from **@bsunanda**: Phase2-hgx360S Update a few constants in v19 hgcal.xml file `geometry` `upgrade` created: 2024-11-19 13:33:39 merged: 2024-11-20 19:21:23

18. [46728](http://github.com/cms-sw/cmssw/pull/46728){:target="_blank"}  from **@ctdax**: Fixed energy of R-Hadron cloud in energy deposit model `simulation` created: 2024-11-18 18:53:54 merged: 2024-11-21 08:38:38

19. [46720](http://github.com/cms-sw/cmssw/pull/46720){:target="_blank"}  from **@bsunanda**: Phase2-hgx360R Inhibit ZDC digitization in Phase2 scenario `simulation` created: 2024-11-18 08:10:32 merged: 2024-11-21 08:38:04

20. [46703](http://github.com/cms-sw/cmssw/pull/46703){:target="_blank"}  from **@cjh1**: fix retry logic for triton client `heterogeneous` created: 2024-11-14 19:49:43 merged: 2024-11-21 08:36:30

21. [46683](http://github.com/cms-sw/cmssw/pull/46683){:target="_blank"}  from **@fabiocos**: MTD geometry: update MTDGeometry test, use only DD4hep backend, add ETL pixel position test `geometry` `upgrade` created: 2024-11-12 17:17:32 merged: 2024-11-21 08:36:18

22. [46593](http://github.com/cms-sw/cmssw/pull/46593){:target="_blank"}  from **@rohitcms**: Add caloParams v0_0 for 2024 HI run `l1` created: 2024-11-03 18:45:19 merged: 2024-11-22 12:32:14

#### CMSDIST Changes between Tags REL/CMSSW_14_2_0_pre4/el8_amd64_gcc12 and REL/CMSSW_14_2_0/el8_amd64_gcc12:
[compare to previous](https://github.com/cms-sw/cmsdist/compare/REL/CMSSW_14_2_0_pre4/el8_amd64_gcc12...REL/CMSSW_14_2_0/el8_amd64_gcc12)



1. [9553](http://github.com/cms-sw/cmsdist/pull/9553){:target="_blank"}  from **@cms-sw**: [14.2.X]Update tag for Geometry-TestReference to V00-16-00 created: 2024-12-05 08:23:02 merged: 2024-12-05 09:43:17

2. [9545](http://github.com/cms-sw/cmsdist/pull/9545){:target="_blank"}  from **@cms-sw**: [14.2]Backport build rules for classversion created: 2024-12-03 11:46:19 merged: 2024-12-04 09:37:17

3. [9526](http://github.com/cms-sw/cmsdist/pull/9526){:target="_blank"}  from **@cms-sw**: [Buildrules] Avoid duplicate compilation messages for BUILD_LOG=yes created: 2024-11-21 17:05:34 merged: 2024-11-22 07:14:51

4. [9525](http://github.com/cms-sw/cmsdist/pull/9525){:target="_blank"}  from **@belforte**: crab-dev -> prod, bump crab-dev to 241121 (py3.12) created: 2024-11-21 16:25:49 merged: 2024-11-21 20:38:14

5. [9524](http://github.com/cms-sw/cmsdist/pull/9524){:target="_blank"}  from **@cms-sw**: Update tag for Geometry-TestReference to V00-15-00 created: 2024-11-21 08:35:57 merged: 2024-11-21 08:35:58
