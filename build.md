CLI: revanced-cli-2.15.1-all.jar  
Integrations: app-release-unsigned-v0.68.0.apk  
Patches: revanced-patches-2.106.1.jar  

YouTube
==
- Ad filter update
- Add [`Seal` ](https://github.com/JunkFood02/Seal) to downloader settings
- Add `Cutout Glitch` settings
- Add `Player overlay background` settings
- Add `Shorts remix button` settings
- Add `Shorts thanks banner` settings
- Add `Shorts subscriptions banner` settings
- Move all settings related to Shorts to `Shorts component`
- `Mix playlist`, `Fullscreen button container` settings are now removed or disabled in the tablet UI (since these settings do not fully support the tablet UI)
- Improve `amoled` patch
- Improve `materialyou` patch
- Fix: `hide-mix-playlists` patch leaves traces of my mix layout
- Fix: `Crowdfunding box` settings work in reverse
- Fix: theme issues in comment fields on some devices (A/B test by Google) https://github.com/inotia00/revanced-patches/issues/13
- Fix: force close occurs when playing video due to return-youtube-dislike on some devices
- Change Sponsorblock Icon Resources
- Change some default settings values
- Remove some unused language resources
- Remove some unused settings
- Crowdin Translation Update
`Arabic`, `Bengali`, `Chinese Simplified`, `Chinese Traditional`, `Hindi`, `Indonesian`, `Korean`, `Polish`, `Russian`, `Spanish`, `Thai`, `Turkish`, `Ukrainian`, `Vietnamese`, 

ETC
==
- Added Support YouTube v17.43.37
- Deprecated support for YouTube v17.43.36
- Change the patch compatibility of YouTube Music to all versions
- bump revanced-patches-2.106.1
refactor: remove unused strings
refactor(youtube/general-ads-patch): remove unnecessary patches
fix(youtube/hide-info-cards): remove initial popup of info-cards
fix(youtube/hide-endscreen-cards): restore functionality
refactor(youtube/general-ads-patch): removed redundant code
refactor(youtube/general-ads-patch): remove unused code
refactor(youtube/general-ads-patch): squash extension classes

※ I don't know why, but the Crowdin translation site is dead again 🤷
※ If you want to contribute to the translation, refer this [documentations](https://telegra.ph/How-to-contribute-to-Crowdin-translations-via-upload-of-stringsxml-file-11-10)
  
**App Versions:**  
YouTube: 17.43.37  
Music (arm64-v8a): 5.32.50  
Music (arm-v7a): 5.32.50  

[revanced-extended-magisk-module](https://github.com/nikhilbadyal/revanced-magisk-module)  
