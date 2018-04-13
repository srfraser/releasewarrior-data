# devedition 60.0b11

### Date of go-to-build: 2018-04-09

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/QNBKwf7_R9S1bf_58jtjCg) QNBKwf7_R9S1bf_58jtjCg
* [push](https://tools.taskcluster.net/push-inspector/#/ANh7A9r1TKSdItBOBEs2kQ) ANh7A9r1TKSdItBOBEs2kQ
* [ship](https://tools.taskcluster.net/push-inspector/#/UHk2QaGLTLCOTdbUS0XHhA) UHk2QaGLTLCOTdbUS0XHhA


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | reran the wrong task trying to fix a weird cot verify issue!! had to then cancel/rerun downstream tasks that had already run/were running. may have worked; otherwise we need a build2 | True | True |
| asasaki  | 2 | [bug none](https://bugzil.la/none)        | source task was unscheduled - unknown reason. cancelled & reran. had to rerun beetmover-cdns; we should probably block the notify-promote task and the beetmover-cdns on beetmover-source | True | True |

