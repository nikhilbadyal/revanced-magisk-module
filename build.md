YouTube: 18.27.35  
YouTube-Revancify-Red: 18.27.35  
YouTube-MMT: 18.27.35  
YouTube-Revancify-Blue: 18.27.35  
Music-arm64: 6.11.52  

Install [MMicrog](https://github.com/inotia00/mMicroG/releases) for non-root YouTube or YT Music  

[revanced-magisk-module](https://github.com/nikhilbadyal/revanced-magisk-module)  

---
Changelog:  
CLI: inotia00/revanced-cli-2.22.2-all.jar  
Integrations: inotia00/revanced-integrations-0.114.1.apk  
Patches: inotia00/revanced-patches-2.186.1.jar  

YouTube
==
- feat(youtube): add support version `v18.27.35`
- feat(youtube): add `hide-suggested-video-overlay` patch https://github.com/inotia00/ReVanced_Extended/issues/1197
- feat(youtube): change `video-speed` to `playback-speed` https://github.com/inotia00/revanced-patches/pull/13
- feat(youtube): generate an exception when an invalid options is entered
- feat(youtube/custom-seekbar-color): apply custom seekbar color to shorts https://github.com/inotia00/ReVanced_Extended/issues/1104
- feat(youtube/hide-general-ads): hide new type of ads
- feat(youtube/hide-layout-components): change the default value of `Hide expandable chip under video` https://github.com/inotia00/ReVanced_Extended/issues/1135
- feat(youtube/hide-shorts-components): shorts header is not blocked on some shorts shelves [ScreenShot](https://imgur.com/a/Z81TCYm)
- fix(youtube/custom-branding-youtube-name): takes too long to apply the patch in the RVX Manager
- fix(youtube/overlay-buttons): `Disable playlist autoplay` loops video in minimized and PiP mode https://github.com/inotia00/ReVanced_Extended/issues/1092
- fix(youtube/return-youtube-dislike): dislikes not showing in some situations https://github.com/inotia00/ReVanced_Extended/issues/1167
- fix(youtube/sponsorblock): some segments skipping slightly too late https://github.com/inotia00/ReVanced_Extended/issues/1144 https://github.com/inotia00/ReVanced_Extended/issues/1152
- feat(youtube/translations): update translation
`Arabic`, `Bengali`, `Bulgarian`, `Chinese Simplified`, `Chinese Traditional`, `French`, `German`, `Greek`, `Indonesian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


Music
==
- feat(music): remove `enable-dismiss-queue` patch (already applied to all users) [reference - 9to5Google](https://9to5google.com/2023/07/13/youtube-music-dismiss-queue/)
- feat(music): generate an exception when an invalid value is entered
- feat(music/microg-support): renamed patch name https://github.com/inotia00/ReVanced_Extended/issues/1141
- fix(music/custom-branding-music-name): no more error occurs when the patch is applied via RVX Manager
- feat(music/translations): update translation
`Bengali`, `Chinese Simplified`, `French`, `Indonesian`, `Korean`, `Turkish`, `Vietnamese`


MicroG
==
- feat(microg): add `custom-branding-icon-mmt` patch https://github.com/inotia00/revanced-patches/pull/12
- feat(microg): add `materialyou` patch https://github.com/inotia00/revanced-patches/pull/12


Reddit
==
- feat(reddit/hide-navigation-buttons): add `Hide chat button` settings
- feat(reddit/hide-navigation-buttons): change settings name `Hide discover button` > `Hide discover / community button`
- feat(reddit/hide-navigation-buttons): `hide-create-button`, `hide-discover-button` patches are integrated
- feat(reddit/hide-navigation-buttons): supports the latest version
- fix(reddit/open-links-externally): exceptions occur in some manufacturers ROM
- fix(reddit/reddit-settings): now when the patch is applied through the RVX Manager, the settings are added normally


Etc
==
- build: bump dependencies
- build: update gradle
- build(dependencies): move to official Google smali fork
- build(dependencies): move to maven central apktool fork
- build(dependencies): move to maven central revanced-patcher fork
- no longer compatible with the official ReVanced Manager


※ Compatible ReVanced Manager: [RVX Manager v1.4.3 (fork)](https://github.com/inotia00/revanced-manager/releases/tag/v1.4.3)

[Crowdin translation]
- [YouTube/European Countries](https://crowdin.com/project/revancedextendedeu)
- [YouTube/Other Countries](https://crowdin.com/project/revancedextended)
- [YT Music](https://crowdin.com/project/revanced-music-extended)

---  
