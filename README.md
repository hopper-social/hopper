<img src="assets/hopper-icon.png" width="72" alt="Hopper app icon" />

# Hopper for Android

Nearby conversations, place-based discovery, and a social feed in one Android app. Hopper is an **alpha**, not an emergency communication service.

> **No public APK is available yet.** This is Hopper's official download repository, not the Android source repository. The [Releases page](https://github.com/hopper-social/hopper/releases) is empty until a signed build passes release checks and is approved. Do not install APKs offered by other accounts or links.

## Inside Hopper

These are captures of an installed **v0.3.5-alpha.1 Hacker development build**, not previews of an approved public APK. They show UI affordances, not verified end-to-end delivery. The named areas and discovery counts are what appeared on the capturing phone, not your location or a promise of nearby peers.

| Nearby | Find a group |
| :---: | :---: |
| <img src="assets/screens/nearby-home.png" width="280" alt="Nearby home with Start a group, Find a group, Notes near you, Explore area, and a recent region chat" /> | <img src="assets/screens/find-a-group.png" width="280" alt="Find a group with search or Hopper link, create group, QR scan, nearby access, refresh, and discovered nearby section" /> |
| Start or find a nearby group, read or leave local notes, or open the area explorer. A recent **region** chat appears below the actions. | Search for a group or paste a Hopper link, scan a group code, and refresh discovery. This capture shows **three discovered** and **zero joined**; it does not establish a connection or delivery. |

| Choose an area | Appearance and safety |
| :---: | :---: |
| <img src="assets/screens/choose-an-area.png" width="280" alt="Globe area picker with spin, zoom, focus, detail settings, and Select button" /> | <img src="assets/screens/appearance-and-safety.png" width="280" alt="Settings showing system light and dark appearance, color swatches, language, haptics, SOS off, background operation off, and real location source" /> |
| Spin and zoom the globe, choose a detail level, then select a geographic area. The highlighted region is approximately **5,000 km** wide in this capture, not a precise position. | Choose system, light, or dark appearance and an accent color; adjust language and haptics. The screen also shows the SOS gesture switched **off**, a background option, and the location source. The screenshot does not prove emergency delivery. |

Other captures from this alpha show a **For you / Global** feed with posts and reaction controls, a **profile** with Reels, Uploads, People, Music, and Saved tabs, a **music** library with playlists, and a **place chat** composer. We have not republished those captures: several include third-party media, identifiable people, or conversation content. Visible tabs and controls describe the interface; availability, media rights, connectivity, and message delivery depend on the actual build and environment.

## What to expect

- Nearby discovery and mesh messaging use Bluetooth and require another compatible Hopper phone, permissions, and enough radio reach. Obstacles, device support, and available peers affect delivery; offline does not mean unlimited range. A visible "Sent" state alone is not proof of receipt.
- Place conversations, profiles, and the social feed use internet connectivity and external relays. Picking an area or publishing a post can reveal location interests; posts, recipients, relays, and media services can retain copies, even after local deletion.
- The app does not require a phone number to start the nearby experience. Check the [privacy information](https://hopper-social.github.io/hopper-legal-pages/privacy.html) and [account-data deletion limits](https://hopper-social.github.io/hopper-legal-pages/deletion.html) before sharing sensitive content.

## Download and update (once a release exists)

1. Open the [official Releases page](https://github.com/hopper-social/hopper/releases) and download the universal `.apk` and its matching `.sha256` file from the **same release**. GitHub's automatic "Source code" archives here are this download repository, not the app source or an installable APK.
2. Compare the APK's SHA-256 with the checksum file (`shasum -a 256 <file.apk>` on macOS or `sha256sum <file.apk>` on Linux). A matching checksum detects changed or incomplete downloads; it does **not** independently prove publisher identity. Verify the repository address and release before installation.
3. Install the APK on a compatible Android phone, allowing "Install unknown apps" for your browser or file manager only when prompted. For later updates, install the newer APK **over** the existing app. Do not uninstall to bypass an update error: Android requires a matching package and signing certificate to preserve app data. Back up anything important first.

Hopper is not currently distributed through Google Play. To report a problem after a release, use this repository's [Issues](https://github.com/hopper-social/hopper/issues) without posting private chats, phone identifiers, or exact location history.
