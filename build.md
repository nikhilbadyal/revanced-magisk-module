CLI: revanced-cli-2.21.0-all.jar  
Integrations: revanced-integrations-0.99.30.apk  
Patches: revanced-patches-2.164.30.jar  

YouTube
==
- add `lift-vertical-video-restriction` patch (Experimental Flags) https://github.com/orgs/revanced/discussions/929
- add `disable-quic-protocol` patch (Experimental Flags)
- add `protobuf-spoof` patch (it fixes playback buffer issue https://github.com/inotia00/ReVanced_Extended/issues/141 https://github.com/microg/GmsCore/issues/1870)
- feat(youtube/general-ads): hide new type of ad
- fix: `Hide more information menu` setting is broken https://github.com/inotia00/ReVanced_Extended/issues/456
- fix: `default-video-speed` patch fails in YouTube v18.08.39 https://github.com/inotia00/ReVanced_Extended/issues/470
- fix: `enable-timestamps-speed` patch is not reflected in patch information
- fix: reboot dialog is missing in `Default downloader settings`
- fix(sponsorblock): context broken on [segment submission](https://www.reddit.com/r/revancedextended/comments/11pgnbh/12_im_too_stupid_to_submit_the_issue_on_github_so/)
- fix(hide-shorts-component): glitch when there are a lot of shorts component blocked in search results
- refactor(hide-shorts-component): check current PlayerType when blocking shorts player component
- refactor(litho): minor optimization
- rollback(default-video-speed): default video speed does not apply when playing live video
- crowdin translation update
`Arabic`, `Bengali`, `Chinese Traditional`, `French`, `Greek`, `Indonesian`, `Italian`, `Japanese`, `Korean`, `Polish`, `Portuguese (Brazilian)`, `Russian`, `Spanish`, `Turkish`, `Ukrainian`, `Vietnamese`


YouTube Music
==
- crowdin translation update
`Indonesian`, `Korean`, `Polish`, `Portuguese (Brazilian)`


ETC
==
- drop support YouTube v18.09.37

※ Compatible ReVanced Manager: v0.0.56
※ If you want to contribute to the translation, refer below

[Crowdin translation]
- [European Countries](https://crowdin.com/project/revancedextendedeu)
- [Other Countries](https://crowdin.com/project/revancedextended)
  
**App Versions:**  
YouTube-Red: 18.09.39  
YouTube: 18.09.39  
YouTube-Blue: 18.09.39  
YouTube-Revancify: 18.09.39  
YouTube-MMT: 18.09.39  
Music (arm64-v8a): 5.47.53  
Music (arm-v7a): 5.47.53  

[revanced-magisk-module](https://github.com/nikhilbadyal/revanced-magisk-module)  
