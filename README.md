<img src="assets/hopper-icon.png" width="72" alt="Hopper app icon" />

# Hopper for Android

**Nearby conversations. Places beyond them.** Find people around you and exchange supported messages over Bluetooth when compatible phones are reachable, even without internet. Go online to explore area conversations, a social feed, profiles, and media.

> **October 12 alpha prerelease available.** Download the signed universal APK and its checksum from the [official v0.3.5-alpha.1 release](https://github.com/hopper-social/hopper/releases/tag/v0.3.5-alpha.1-20261012). This is Hopper's download repository, not the Android source repository. The screens below are development captures and are not proof that they came from the signed public APK. Do not install APKs offered elsewhere.

## One app, more ways to connect

- **Around you:** Discover compatible phones and explore available groups. Supported Bluetooth mesh conversations can work without mobile data or Wi-Fi when peers are reachable; group discovery and delivery depend on the connection.
- **In a place:** Spin the globe to choose an area, then explore its conversations and notes through internet-backed relays. You can choose where to look without claiming to be there.
- **Beyond chat:** Browse the online feed, profiles, photos, Reels, and music. The people and places you find nearby sit alongside a wider social experience.

## A look inside

All 14 supplied phone captures are shown below. These are **edited v0.3.5-alpha.1 development captures**, not verified screenshots of the signed public APK or proof of message delivery. System bars were cropped; private conversations, posts, build details, and third-party media previews were covered before publication. Blank labeled regions are redactions, not empty app states. Places and discovery counts reflect one session, not current network availability.

| Nearby home | Find a group |
| :---: | :---: |
| <img src="assets/screens/nearby-home.png" width="280" alt="Nearby home with group, notes, and area actions plus a recent region card; its photo and post preview are hidden" /> | <img src="assets/screens/find-a-group.png" width="280" alt="Find a group with search, create group, scan code, and discovery controls" /> |
| Groups, notes, and area conversations. | Search, scan a code, or refresh discovery. |

| Nearby communities | Choose an area |
| :---: | :---: |
| <img src="assets/screens/nearby-communities.png" width="280" alt="Nearby community cards showing Chat, Call, and Photo actions with media previews hidden" /> | <img src="assets/screens/choose-an-area.png" width="280" alt="Globe area picker with spin, zoom, focus, detail settings, and Select button" /> |
| Community cards and available actions. | Spin and zoom to choose a broad area. |

| Place conversation | Place notes |
| :---: | :---: |
| <img src="assets/screens/place-conversation.png" width="280" alt="Region conversation header and message composer with message contents hidden" /> | <img src="assets/screens/place-notes.png" width="280" alt="Society, Block, Area, and City notes tabs and Add a note action; the pinned post is hidden" /> |
| Conversation view; participants and messages hidden. | Browse or add notes for a place. |

| For you, dark | For you, another moment |
| :---: | :---: |
| <img src="assets/screens/for-you-feed-dark.png" width="280" alt="Dark feed with For you selected and media post hidden" /> | <img src="assets/screens/for-you-feed-dark-alt.png" width="280" alt="Second dark For you feed capture with a different post frame hidden" /> |
| The feed in dark appearance. | A second frame of the same feed view. |

| For you, light | Global feed |
| :---: | :---: |
| <img src="assets/screens/for-you-feed-light.png" width="280" alt="Light feed with For you selected and media post hidden" /> | <img src="assets/screens/global-feed.png" width="280" alt="Dark feed with Global selected and third-party post hidden" /> |
| The same tab in light appearance. | Switch to the wider Global feed. |

| Profile and Reels | Music library |
| :---: | :---: |
| <img src="assets/screens/profile-and-reels.png" width="280" alt="Anonymous profile with post counts, Reels, Uploads, People, Music, and Saved tabs; reel thumbnail hidden" /> | <img src="assets/screens/music-library.png" width="280" alt="Music library with Play now and New playlist actions; third-party media preview and title hidden" /> |
| Your profile and media tabs. | Library and playlist controls. |

| Appearance and safety | Reels and storage settings |
| :---: | :---: |
| <img src="assets/screens/appearance-and-safety.png" width="280" alt="Settings with appearance swatches, language, haptics, SOS off, and location source" /> | <img src="assets/screens/reels-and-storage-settings.png" width="280" alt="Settings with nearby Reel and publishing toggles, backup, and data management; device build details hidden" /> |
| Choose appearance and safety options. | Control media, storage, and sharing options. |

## About Hopper and Bitchat

Hopper extends the nearby-first approach of [Bitchat](https://github.com/permissionlesstech/bitchat) with an Android social experience built around places, a feed, media, and profiles. Private mesh sessions use the [Noise Protocol](https://noiseprotocol.org). Hopper is a separate project, **not** the official Bitchat app; Bitchat releases are not Hopper downloads.

## Where it works

- **Nearby messaging** needs compatible phones in range, Bluetooth, and the required permissions. Obstacles and available peers affect delivery; a "Sent" label does not confirm receipt. Hopper is an **alpha**, not an emergency service.
- **Places, notes, and the feed** need internet access and external relays. Choosing an area can reveal what places interest you, and optional location lookups may disclose more precise location data to external services. Public posts and media can be copied or retained elsewhere.
- **Nearby reels** may use Wi-Fi Direct on supported devices. That is a separate transfer path from Bluetooth mesh messages; it is not a promise of offline media delivery.

Nearby access does not require a phone number. Read the [privacy information](https://hopper-social.github.io/hopper-legal-pages/privacy.html) and [account-data deletion limits](https://hopper-social.github.io/hopper-legal-pages/deletion.html) before sharing sensitive content.

## Get Hopper

1. Open the [October 12 alpha prerelease](https://github.com/hopper-social/hopper/releases/tag/v0.3.5-alpha.1-20261012). Under **Assets**, download the universal `.apk` and its matching `.sha256` file from that release. GitHub's automatic "Source code" archives here are neither the Android app source nor an installable APK.
2. Compare the APK's SHA-256 with the checksum file (`shasum -a 256 <file.apk>` on macOS or `sha256sum <file.apk>` on Linux). A match detects changed or incomplete downloads; it does **not** prove publisher identity. Check the repository address and release.
3. Open the APK on a compatible Android phone. Allow "Install unknown apps" for the browser or file manager only when prompted. To update later, install the new APK **over** the existing one. Android requires the same package and signing certificate to preserve app data; do not uninstall to bypass a mismatch. Back up anything important first.

Hopper is not currently on Google Play. Report problems through [Issues](https://github.com/hopper-social/hopper/issues) without posting private chats, device identifiers, or exact location history.
