YTMusic: 6.22.51  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-4.0.3-all.jar  
Integrations: inotia00/revanced-integrations-0.119.15.apk  
Patches: inotia00/revanced-patches-2.193.15.jar  

YouTube
==
- feat(YouTube): add support version `v18.37.36`
- feat(YouTube): change patch name `Force VP9 codec` → `Force video codec` https://github.com/inotia00/revanced-patches/pull/25
- feat(YouTube/Force video codec): add `Enable HDR codec` settings https://github.com/inotia00/revanced-patches/pull/25
- feat(YouTube/Hide layout components): add `Hide channel profile links` settings
- feat(YouTube/Settings): remove warning dialog for Experimental Flags (wastes unnecessary strings resources)
- fix(YouTube/Custom playback speed): regulate maximum playback speed to 8.0x (playback rate that can be handled by the client)
- fix(YouTube/Enable minimized playback): Fix pip incorrectly showing if app is minimized immediately after opening a Short https://github.com/inotia00/ReVanced_Extended/issues/1539
- fix(YouTube/Hide general ads): block new type of web search panel
- fix(YouTube/Hide layout components): move `Hide join button` to the `Channel bar` subpreference in the `Bottom player` category
- fix(YouTube/Hide player flyout panel): Shorts player's flyout panel is hidden
- fix(YouTube/Overlay buttons): disable PiP when click external download button https://github.com/inotia00/revanced-integrations/pull/23
- fix(YouTube/Return YouTube Dislike): RYD patch for v18.34.38~ is not required for ~v18.33.40
- feat(YouTube/Translations): update translation
`Arabic`, `Brazilian`, `Bulgarian`, `French`, `Greek`, `Hungarian`, `Indonesian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(YouTube Music): add `Enable old player layout` patch https://github.com/inotia00/ReVanced_Extended/issues/1532
- feat(YouTube Music/Translations): update translation
`Brazilian`, `Bulgarian`, `Dutch`, `Greek`, `Indonesian`, `Japanese`, `Korean`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


Reddit
==
- fix(Reddit): some patches are broken in version `2023.41.0` https://github.com/inotia00/ReVanced_Extended/issues/1546


Etc
==
- When updating from YouTube v18.33.40 or lower to YouTube v18.34.xx or later, a clean install is recommended.
- The `Enable old player layout` patch for YouTube Music was added due to `patch-request`, but is excluded by default because it is quite unstable
- If you turn on the `Enable old player layout` setting and the `Enable new player background` setting at the same time, constant crashes will occur


※ Compatible ReVanced Manager: [RVX Manager v1.12.1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.12.1)
[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)


---  
