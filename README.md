# CustomMTFAnnouncement
A simple exiled plugin that changes the Cassie announcement when NTF spawned.

# Configs
```yml
# Whether or not the plugin is enabled.
  is_enabled: true
  # What should cassie say when there's no scp left.
  noscp_announcement: mtfunit epsilon 11 designated {mtfunit} number {mtfnum} hasentered allremaining noscpsleft
  # What should cassie say when there's one scp left.
  onescp_announcement: mtfunit epsilon 11 designated {mtfunit} number {mtfnum} hasentered allremaining awaitingrecontainment {scpnum} scpsubject
  # What should cassie say when there are more than 2 scps left.
  twoscps_announcement: mtfunit epsilon 11 designated {mtfunit} number {mtfnum} hasentered allremaining awaitingrecontainment {scpnum} scpsubjects
  ```
