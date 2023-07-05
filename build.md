CLI: revanced-cli-2.22.0-all.jar  
Integrations: revanced-integrations-0.111.2.apk  
Patches: revanced-patches-2.181.1.jar  

YouTube
==
- feat(youtube): add `add-splash-animation` patch
- feat(youtube): add `enable-compact-controls-overlay` patch
- feat(youtube): add `enable-debug-logging` patch
- feat(youtube): add `enable-new-splash-animation` patch https://github.com/inotia00/ReVanced_Extended/issues/869
- feat(youtube): add `enable-new-thumbnail-preview` patch
- feat(youtube): add `force-opus-codec` patch
- feat(youtube): add `hide-description-components` patch
- feat(youtube): add `hide-feed-flyout-panel` patch https://github.com/inotia00/ReVanced_Extended/issues/925 [Reddit](https://www.reddit.com/r/revancedextended/comments/14g0klm/any_way_to_remove_this/)
- feat(youtube): add `hide-speed-overlay` patch [Reddit](https://www.reddit.com/r/youtube/comments/14dcowf/the_2x_speed_when_im_holding_down_on_video/)
- feat(youtube): add `hide-suggestions-shelf` patch https://github.com/inotia00/ReVanced_Extended/issues/575 https://github.com/inotia00/ReVanced_Extended/issues/598 https://github.com/inotia00/ReVanced_Extended/issues/613
- feat(youtube): add `hide-trending-searches` patch
- feat(youtube): add `language-switch` patch https://github.com/inotia00/ReVanced_Extended/issues/661
- feat(youtube): improve patching speed
- feat(youtube): remove `custom-branding-icon-afn-blue` patch
- feat(youtube): remove `custom-branding-icon-afn-red` patch
- feat(youtube): remove `hide-breaking-news-shelf` patch
- feat(youtube): remove `hide-search-terms` patch
- feat(youtube): remove `hide-stories` patch [Google Help](https://yt.be/help/stories)
- feat(youtube/custom-video-speed): change custom video speeds inside app settings
- feat(youtube/custom-video-speed): change preference summary when a new player flyout is detected
- feat(youtube/default-video-quality): apply `video-cpn-hook` instead of `video-id-hook`
- feat(youtube/default-video-speed): apply method improvement
- feat(youtube/hide-button-container): add `Hide rewards button` settings
- feat(youtube/hide-button-container): rewrite codes
- feat(youtube/hide-general-ads): `Hide merchandise shelf` now hides merchandise shelf in video descriptions
- feat(youtube/hide-layout-components): add `Hide gray description` settings https://github.com/inotia00/ReVanced_Extended/issues/455
- feat(youtube/hide-layout-components): remove `Hide browse store button` settings
- feat(youtube/hide-layout-components): separate hiding expandable chips and chapters https://github.com/inotia00/ReVanced_Extended/issues/351 https://github.com/inotia00/ReVanced_Extended/issues/628
- feat(youtube/hide-layout-components): `Hide feed surveys` now hides the following banner - 'Recommendations not quite right?' [Image](https://imgur.com/a/lXVjO6U)
- feat(youtube/hide-shorts-component): hide likes, dislikes and share buttons in shorts player https://github.com/inotia00/ReVanced_Extended/issues/656
- feat(youtube/hide-shorts-component): hide toolbar in shorts player https://github.com/inotia00/ReVanced_Extended/issues/151
- feat(youtube/hide-video-ads): change to abstract patch
- feat(youtube/hook-player-button): rewrite codes
- feat(youtube/litho-filter): change to shared patch
- feat(youtube/litho-filter): return earlier when possible
- feat(youtube/overlay-buttons): change to an appropriate description
- feat(youtube/overlay-buttons): disable autoplay by tapping and holding the `always repeat button` https://github.com/inotia00/ReVanced_Extended/issues/707
- feat(youtube/overlay-buttons): launch `external-downloader` by clicking the offline download button in the video action bar https://github.com/inotia00/ReVanced_Extended/issues/7
- feat(youtube/overlay-buttons): remove `Always auto repeat` toggle from settings
- feat(youtube/overlay-buttons): remove PowerTube from default downloaders list and add ytdlnis to default downloaders list https://github.com/inotia00/ReVanced_Extended/issues/352
- feat(youtube/overlay-buttons): `Hook download button` preference is shown only in the available version
- feat(youtube/return-youtube-dislike): separate ryd for shorts and ryd for general video
- feat(youtube/settings): edit text dialog - add reset button
- feat(youtube/settings): edit text dialog - instead of comma-separated when entering custom filters, separate them with lines
- feat(youtube/settings): moved some settings to the appropriate category
- feat(youtube/settings): sort alphabetically https://github.com/inotia00/ReVanced_Extended/issues/242
- feat(youtube/spoof-app-version): add custom version input dialog
- feat(youtube/spoof-app-version): add 18.20.39 to version list
- feat(youtube/spoof-app-version): remove 17.06.35 from version list
- feat(youtube/spoof-app-version): set default value to 18.20.39
- feat(youtube/spoof-app-version): change to abstract patch
- feat(youtube/spoof-player-parameters): change patch name `protobuf-spoof` > `spoof-player-parameters`
- feat(youtube/spoof-player-parameters): remove from patch list and include in `microg-support` patch
- feat(youtube/spoof-player-parameters): split into `shorts parameter` and `incognito mode parameter`
- feat(youtube/default-video-quality): `Enable save video quality` not working in new layout
- feat(youtube/default-video-speed): `Enable save video speed` not working in new layout
- fix(youtube): separate `hide-general-ads` to `hide-layout-components` patch
- fix(youtube/custom-video-speed): not working in new player flyout panel
- fix(youtube/enable-old-quality-layout): not working in new player flyout panel https://github.com/inotia00/ReVanced_Extended/issues/377 https://github.com/inotia00/ReVanced_Extended/issues/627
- fix(youtube/integrations): playback in embedded video's context not set
- fix(youtube/litho-filter): don't include all Litho patches, when not included
- fix(youtube/litho-filter): Incorrect dex syntax
- fix(youtube/overlay-buttons): sometimes NullPointerException occurs when changing external downloader
- fix(youtube/settings): add a fallback action when the target preference is not found or the cast fails because the patch is excluded
- fix(youtube/sponsorblock): throw an exception when scrubbing thru a paused video
- fix(youtube/sponsorblock): `replaceMeWith` strings not replacing properly
- fix(youtube/sponsorblock): vote button and new segment button still showing when end screen overlay appears https://github.com/inotia00/ReVanced_Extended/issues/398
- refactor(youtube): move the patch to the correct path
- refactor(youtube): renamed some patches and description https://github.com/inotia00/ReVanced_Extended/issues/1026
- refactor(youtube/integrations): remove dummy class
- refactor(youtube/integrations): rewrite codes
- feat(youtube/translations): update translation
`Arabic`, `Bengali`, `Bulgarian`, `Chinese Simplified`, `Chinese Traditional`, `French`, `Greek`, `Hungarian`, `Indonesian`, `Italian`, `Japanese`, `Polish`, `Portuguese, Brazilian`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- feat(music): add `enable-custom-filter` patch
- feat(music): add `enable-debug-logging` patch
- feat(music): add `enable-dismiss-queue` patch
- feat(music): add `enable-new-layout` patch
- feat(music): add `enable-old-style-miniplayer` patch
- feat(music): add `enable-sleep-timer` patch
- feat(music): add `hide-navigation-label` patch
- feat(music): remove `custom-branding-music-afn-blue` patch
- feat(music): remove `custom-branding-music-afn-red` patch
- feat(music/enable-opus-codec): change to abstract patch
- feat(music/hide-music-ads): change to abstract patch
- feat(music/litho-filter): change to abstract patch
- feat(music/music-settings): edit text dialog - add reset button
- feat(music/share-button-hook): no longer hooking the sleep timer dialog
- feat(music/spoof-app-version): change to abstract patch
- fix(music/litho-filter): don't include all Litho patches, when not included
- fix(music/remember-video-quality): patches are broken in the latest versions
- fix(music/video-id-hook): patches are broken in the latest versions
- refactor(music): move the patch to the correct path
- refactor(music): renamed some patches name
- refactor(music): renamed some patches description https://github.com/inotia00/ReVanced_Extended/issues/1026
- feat(music/translations): update translation
`Chinese Traditional`, `French`, `Greek`, `Indonesian`, `Japanese`, `Korean`, `Polish`, `Spanish`, `Turkish`, `Vietnamese`


Reddit
==
- feat(reddit): add reddit patches
- feat(reddit): add `hide-navigation-buttons` patch
- feat(reddit): add `open-links-directly` patch
- feat(reddit): add `open-links-externally` patch
- feat(reddit): add `settings` patch
- fix(reddit/hide-comment-ads): patch is broken in old versions


Etc
==
- add support v18.20.39, v18.21.35, v18.22.37, v18.23.36, v18.24.37
- build: bump patcher to 11.0.4
- build: bump dependencies
- drop support for some YouTube versions
- for CLI users, manually delete `options.json` before proceeding with patching
- there are so many changes in the patch, so I recommend doing a clean install


Known Issues
==
- There is no way to apply a custom video speed in the new player flyout panel
- As a workaround for this issue, I applied the old style player flyout panel to the speed player flyout panel


※ Compatible ReVanced Manager: v1.3.6
[Crowdin translation]
- [European Countries](https://crowdin.com/project/revancedextendedeu)
- [Other Countries](https://crowdin.com/project/revancedextended)

  
**App Versions:**  
Music (arm-v7a): 6.08.50  
YouTube: 18.16.37  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) to be able to use non-root YouTube or Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  
