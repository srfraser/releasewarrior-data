# firefox 60.0b13

### Date of go-to-build: 2018-04-16

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/fvHtJbxNQ-iLoiT16aH00w) fvHtJbxNQ-iLoiT16aH00w
* [push](https://tools.taskcluster.net/push-inspector/#/eU0--JVTSZej9laTiZebeA) eU0--JVTSZej9laTiZebeA
* [ship](https://tools.taskcluster.net/push-inspector/#/OUvTM92vSwukvohCs_OQYg) OUvTM92vSwukvohCs_OQYg
```
export PROMOTE_TASK_ID=fvHtJbxNQ-iLoiT16aH00w
export PUSH_TASK_ID=eU0--JVTSZej9laTiZebeA
export SHIP_TASK_ID=OUvTM92vSwukvohCs_OQYg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug 1438246](https://bugzil.la/1438246)        | addonscript needs to retry harder | True | True |

