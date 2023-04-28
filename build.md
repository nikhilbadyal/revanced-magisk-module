CLI: revanced-cli-2.21.0-all.jar  
Integrations: revanced-integrations-0.105.1.apk  
Patches: revanced-patches-2.171.1.jar  

YouTube
==
- feat(sponsorblock): automatically hide skip button
- fix(microg-support): replace patch description correctly
- fix(protobuf-spoof): additional fixes for subtitle window positions
- refactor(hide-button-container): add support for a/b tests
- refactor(hide-shorts-navbar): no longer use dummy class - PivotBar in integrations
- refactor(layout-switch): community posts in channels are no longer hidden when `Enable tablet layout` is on
- refactor(return-youtube-dislike): matches official ReVanced's code
- remove `lift-vertical-video-restriction` patch (no longer valid)
- remove minimized playback toggle (enabled by default)
- crowdin translation update
`Arabic`, `Brazilian`, `Bulgarian`, `Chinese Traditional`, `Finnish`, `French`, `Greek`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- add `bitrate-default-value` patch
- add `hide-button-shelf` patch
- add `hide-carousel-shelf` patch
- add `remember-video-quality` patch https://github.com/inotia00/ReVanced_Extended/issues/457
- add `sleep-timer-hook` patch (included in `share-button-hook` patch)
- change default settings value
- feat(client-spoof-music): removed from patch list and dependent on `music-microg-support` patch
- feat(enable-landscape-mode): rename patch (`enable-tablet-mode` → `enable-landscape-mode`)
- feat(hide-category-bar): rename patch (`hide-compact-header` → `hide-category-bar`)
- feat(music-settings): update strings resources
- feat(spoof-app-version): rename patch (`spoof-version` → `spoof-app-version`)
- fix(music-microg-support): replace patch description correctly
- refactor(music-settings): rebase integrations
- refactor(hide-upgrade-button): optimize the patching process
- refactor(patch-options): remove `MusicDownloaderPackageName` options
(You should remove 'MusicDownloaderPackageName' from `options.toml` file, or just remove `options.toml` file. If both are difficult for you, simply reinstall the builder)
- refactor(share-button-hook): now downloader package name can be changed in settings
- crowdin translation update
`Brazilian`, `Bulgarian`, `Korean`, `Vietnamese`


ETC
==
- add support YouTube v18.16.37
- build: update dependencies


※ Compatible ReVanced Manager: v0.0.57
※ If you want to contribute to the translation, refer below

[Crowdin translation]
- [European Countries](https://crowdin.com/project/revancedextendedeu)
- [Other Countries](https://crowdin.com/project/revancedextended)
  
**App Versions:**  
YouTube: 18.16.37  
YouTube-Red: 18.16.37  
YouTube-Blue: 18.16.37  
YouTube-MMT: 18.16.37  
YouTube-Revancify: 18.16.37  
Music (arm64-v8a): 5.54.52  
Music (arm-v7a): 5.54.52  

[revanced-magisk-module](https://github.com/nikhilbadyal/revanced-magisk-module)  
