YouTube: 18.27.35  
Twitch: 15.4.1  
Tiktok: 30.6.2  
Reddit: 2023.29.0  
Twitter: 9.98.0-release.0  

Install [Vanced Microg](https://github.com/TeamVanced/VancedMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/j-hc/revanced-magisk-module)  

---
Changelog:  
CLI: j-hc/revanced-cli-2.23.0-all.jar  
Integrations: ReVanced/revanced-integrations-0.114.0.apk  
Patches: ReVanced/revanced-patches-2.186.0.jar  

### [2.186.0](https://github.com/ReVanced/revanced-patches/compare/v2.185.0...v2.186.0) (2023-07-21)


### Bug Fixes

* **Tiktok - Settings:** get instruction registers dynamically ([#2676](https://github.com/ReVanced/revanced-patches/issues/2676)) ([b34e45b](https://github.com/ReVanced/revanced-patches/commit/b34e45b6dafad8e9d567ad65f58a182b8cc04676))
* **YouTube - Spoof app version:** update target app version description ([#2666](https://github.com/ReVanced/revanced-patches/issues/2666)) ([307442e](https://github.com/ReVanced/revanced-patches/commit/307442e654ff5486656319d91e4a5f5fb2b92651))
* **YouTube - Theme:** allow setting no background color ([8a4e77a](https://github.com/ReVanced/revanced-patches/commit/8a4e77a290a61a1caf93eb8bccaf728c84a3ef53))
* **YouTube - Theme:** apply custom seekbar color to shorts ([#2670](https://github.com/ReVanced/revanced-patches/issues/2670)) ([1f6fe3d](https://github.com/ReVanced/revanced-patches/commit/1f6fe3da4284fd768057ef068c7ddf88d3a11049))


### Features

* **Twitter:** remove `Hide view stats` patch ([f0d3800](https://github.com/ReVanced/revanced-patches/commit/f0d38001b34db63f212209afb91eebf59dad2b24))
* **Youtube - Theme:** add a switch to enable/disable custom seekbar color ([#2663](https://github.com/ReVanced/revanced-patches/issues/2663)) ([5c39985](https://github.com/ReVanced/revanced-patches/commit/5c39985888cdfe3acfdd8811ff9b6f80e243704e))




---
CLI: inotia00/revanced-cli-2.22.2-all.jar  
Integrations: inotia00/revanced-integrations-0.114.7.apk  
Patches: inotia00/revanced-patches-2.186.7.jar  

YouTube
==
- fix(youtube/hide-player-flyout-panel): captions menu not hidden normally https://github.com/inotia00/ReVanced_Extended/issues/1074
- fix(youtube/overlay-buttons): fullscreen icon does not match https://github.com/inotia00/ReVanced_Extended/issues/1221
- fix(youtube/settings): wrong alphabetical alignment
- fix(youtube/spoof-app-version): change target version `17.30.34` > `17.08.35`
- feat(youtube/spoof-player-parameters): no longer automatically spoofed
- feat(youtube/spoof-player-parameters): set default value to `on` in non-root environments only
- feat(youtube/litho-filter): clean up some filters
- feat(youtube/navbar-index-hook): no longer depend on low-level filters
- feat(youtube/hide-player-flyout-panel): add `Hide lock screen menu` settings [ScreenShot](https://imgur.com/a/2CQXqhz)
- feat(youtube/hide-suggested-video-overlay): no longer dependent on `overlay-buttons` patches
- feat(youtube/translations): update translation
`Brazilian`, `Chinese Traditional`, `Greek`, `Japanese`, `Korean`, `Russian`, `Spanish`


Music
==
- feat(music/translations): update translation
`Brazilian`, `Chinese Traditional`


Reddit
==
- feat(reddit/hide-ads): implementing with settings


※ Compatible ReVanced Manager: [RVX Manager v1.4.3-1 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.4.3-1)

[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---  