# MenuDrawer

A native macOS 27 menu bar drawer for Apple Silicon. This repository contains signed downloads and the update feed; source is private.

[Download the latest release](https://github.com/ngzhenghui94/menuDrawer-releases/releases/latest)

Unzip the download and move MenuDrawer.app to Applications. Open the tray button and choose **Check for Updates…** for future releases. Updates are Developer ID signed and notarized, with a signed Sparkle feed and archive.

This is an early preview. Menu bar hiding uses a private macOS API and needs app-control permission. Full hide/reveal and native menu interaction remain unverified. The app starts with all icons visible; **Show All** or quitting restores them.

Credits: the native visibility bridge comes from [Hidden Bar](https://github.com/dwarvesf/hidden) under the MIT license. Updates use [Sparkle](https://sparkle-project.org/). Both licenses are included in the app.
