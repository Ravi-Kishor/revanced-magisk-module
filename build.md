YouTube: 18.37.36  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.0.3-all.jar  
Integrations: inotia00/revanced-integrations-0.119.18.apk  
Patches: inotia00/revanced-patches-2.193.18.jar  

YouTube
==
- feat(YouTube): add support version `v18.38.44`, `v18.39.41`
- feat(YouTube): add `Hide toolbar button` patch
- feat(YouTube/Disable haptic feedback): `Disable seek haptic feedback` now also disables `seek undo haptic feedback`
- feat(YouTube/Hide seek message): now the seek undo message (`Release to cancel`) is also hidden
- feat(YouTube/Hide shorts components): remove the `Hide toolbar` setting and add settings to hide each toolbar button
- fix(YouTube/Enable minimized playback): play button not available after playing Shorts https://github.com/inotia00/ReVanced_Extended/issues/1539
- fix(YouTube/Hide account menu): improve patch method
- fix(YouTube/Hide comment component): `Hide emoji picker` hides timestamps for chapters https://github.com/inotia00/ReVanced_Extended/issues/1556
- fix(YouTube/Hide general ads): reflection of changes in new layout
- fix(YouTube/Hide handle): handle is not hidden in You tab https://github.com/inotia00/ReVanced_Extended/issues/630
- fix(YouTube/Hide mix playlists): when MixPlaylists are included in my playlist (library), all playlists are hidden
- fix(YouTube/Hide player flyout panel): components are not hidden in new layout https://github.com/inotia00/ReVanced_Extended/issues/1410
- fix(YouTube/Return YouTube Dislike): dislike count for previous video is displayed after clicking dislike button in Shorts https://github.com/inotia00/ReVanced_Extended/issues/1547
- fix(YouTube/Settings): header for `Experimental Flags` is added even though `Experimental Flags` is empty
- fix(YouTube/Settings): patch names in Patches Information section do not match https://github.com/inotia00/ReVanced_Extended/issues/1555
- refactor(Litho filter): reduce memory requirement for prefix tree searching https://github.com/ReVanced/revanced-integrations/pull/501
- feat(YouTube/Translations): update translation
`Brazilian`, `Bulgarian`, `Chinese Traditional`, `French`, `German`, `Hungarian`, `Indonesian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(YouTube Music/Translations): update translation
`Chinese Traditional`, `Japanese`, `Korean`, `Romanian`, `Russian`


Etc
==
- When updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.


※ Compatible ReVanced Manager: [RVX Manager v1.12.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.12.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---  
