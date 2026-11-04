# Jo & Tom Content HQ updates

This public repository distributes software updates for Jo & Tom Content HQ. It does not contain footage, clip notes, review decisions, API keys, or a copy of the local app library.

## Install

Jo & Tom Content HQ 1.0.0 requires an Apple Silicon Mac running macOS 26 Tahoe or newer.

1. [Download Jo & Tom Content HQ for Mac](https://github.com/josiah-droid/jo-tom-content-hq-updates/releases/latest/download/Jo-Tom-Content-HQ-mac.zip).
2. Extract it and move `Jo & Tom Content HQ.app` to Applications.
3. Open the app. This build is ad-hoc signed and is not notarized. If macOS blocks the first launch, use the per-app approval in System Settings > Privacy & Security. Do not disable Gatekeeper.
4. Choose **Connect Footage Folder…** from the app menu, press Command-O, or use the in-app button. Select the folder containing the original footage.

The app analyzes files locally. Connecting a folder does not copy footage or duplicate clips already in the catalog. After an ad-hoc update, reconnect protected footage folders if macOS access is lost.

## Updates

Use **Check for Updates…** in the app menu. The app accepts updates only when the signed appcast and archive match its embedded Ed25519 public key. It refuses to relaunch while analysis or an approved AI run is active.

The update channel is public. The app's catalog and media remain on the Mac.
