# Awesome ActivityWatch :star2: :fire: with stars

A collections of awesome links to resources relating to ActivityWatch, the free and open-source automated time-tracker.

**Please star :star: and share this repo! :loudspeaker:**

This list is just getting started. *Do you see anything missing? [Make a pull request!](https://github.com/ActivityWatch/awesome-activitywatch/edit/master/README.md) ⭐ 171 | 🐛 3 | 📅 2026-03-11 :pencil2:*

# Official links :link:

* [Website](https://activitywatch.net)
* [GitHub](https://github.com/ActivityWatch)
* [Forum](https://forum.activitywatch.net/)
* [Twitter](https://twitter.com/ActivityWatchIt)
* [Discord](https://discord.gg/vDskV9q)
* [LinkedIn](https://www.linkedin.com/company/activitywatch/)
* [r/ActivityWatch](https://www.reddit.com/r/ActivityWatch/) (mostly inactive), subreddit for ActivityWatch

# Applications

The main ActivityWatch application and alternative implementations:

* **ActivityWatch** ([releases](https://github.com/ActivityWatch/activitywatch/releases) ⭐ 18,580 | 🐛 191 | 🌐 Python | 📅 2026-08-06) - The official distribution, includes:
  * aw-qt (tray application)
  * aw-server & aw-server-rust (storage and API)
  * aw-watcher-window (window tracking)
  * aw-watcher-afk (idle detection)
  * aw-watcher-input (keyboard/mouse usage)
  * aw-sync (data syncing)
  * aw-notify (notifications)
* [aw-tauri](https://github.com/ActivityWatch/aw-tauri) ⭐ 62 | 🐛 16 | 🌐 Rust | 📅 2026-08-03 (WIP), experimental/alternative distribution of ActivityWatch using Tauri
* [yet-another-UI-for-AW](https://github.com/K-Kuyama/yet-another-UI-for-AW/) ⭐ 10 | 🐛 6 | 🌐 Python | 📅 2024-01-31, a native UI for ActivityWatch with Japanese localization ([announcement forum post](https://forum.activitywatch.net/t/another-gui-client-for-aw/2748))
* [Codewatch](https://github.com/jca41/codewatch) ⭐ 7 | 🐛 5 | 🌐 Svelte | 📅 2023-06-05, desktop client for ActivityWatch focused on software development and productivity.
* [Workflow](https://flathub.org/apps/com.gitlab.cunidev.Workflow), basic screentime application using GTK

# Documentation :books:

* [Official Documentation](https://docs.activitywatch.net)
* [Getting Started Guide](https://docs.activitywatch.net/en/latest/getting-started.html)
* [FAQ](https://docs.activitywatch.net/en/latest/faq.html)

# Server Implementations :computer:

ActivityWatch has a modular architecture that includes a server component for storing and analyzing the collected data.

* [aw-server-rust](https://github.com/ActivityWatch/aw-server-rust) ⭐ 312 | 🐛 61 | 🌐 Rust | 📅 2026-08-10, an official server implementation written in Rust for improved performance
* [aw-server](https://github.com/ActivityWatch/aw-server) ⭐ 124 | 🐛 31 | 🌐 Python | 📅 2026-07-28, an official server implementation written in Python

# Client Libraries

The ActivityWatch ecosystem provides client libraries to help developers interact with the ActivityWatch server API and create custom watchers, integrations, extensions, or applications. Here are the official client libraries:

* [aw-client-rust](https://github.com/ActivityWatch/aw-server-rust/tree/master/aw-client-rust) ⭐ 312 | 🐛 61 | 🌐 Rust | 📅 2026-08-10, a client library written in Rust
* [aw-client](https://github.com/ActivityWatch/aw-client) ⭐ 67 | 🐛 13 | 🌐 Python | 📅 2026-07-23, a client library written in Python
* [aw-client-js](https://github.com/ActivityWatch/aw-client-js) ⭐ 40 | 🐛 6 | 🌐 TypeScript | 📅 2026-07-28, a client library written in JavaScript/TypeScript

# Desktop Widgets :desktop\_computer:

* [activitywatch-plasmoid](https://github.com/NicoWeio/activitywatch-plasmoid) ⭐ 8 | 🐛 0 | 🌐 QML | 📅 2021-10-17, a KDE Plasma widget for ActivityWatch
* [activitywatch-status-gnome-shell](https://extensions.gnome.org/extension/7774/activitywatch-status/), GNOME Shell extension that shows the total time spent today ([source](https://codeberg.org/cweiske/activitywatch-status-gnome-shell))

# Watchers :watch:

ActivityWatch comes with two watchers enabled by default:

* [aw-watcher-window](https://github.com/ActivityWatch/aw-watcher-window) ⭐ 127 | 🐛 35 | 🌐 Python | 📅 2026-07-28 - Watches the active window and its metadata
* [aw-watcher-afk](https://github.com/ActivityWatch/aw-watcher-afk) ⭐ 74 | 🐛 12 | 🌐 Python | 📅 2026-07-22 - Watches for mouse & keyboard activity to detect if the user is active

## Window Watchers :desktop\_computer:

* [awatcher](https://github.com/2e3s/awatcher) ⭐ 300 | 🐛 33 | 🌐 Rust | 📅 2026-07-31 - A compiled watcher for X11 and Wayland by @2e3s
* [aw-watcher-window](https://github.com/ActivityWatch/aw-watcher-window) ⭐ 127 | 🐛 35 | 🌐 Python | 📅 2026-07-28 - The official window watcher for Windows, macOS, and Linux (X11)
* [aw-watcher-window-wayland](https://github.com/ActivityWatch/aw-watcher-window-wayland) ⭐ 100 | 🐛 17 | 🌐 Rust | 📅 2026-06-29 - Window watcher for Wayland by @johan-bjareholt
* [aw-watcher-enhanced](https://github.com/kepptic/aw-watcher-enhanced) ⭐ 7 | 🐛 2 | 🌐 Rust | 📅 2026-03-10 - Enhanced window watcher with OCR screen capture, LLM-powered context extraction (via Ollama), smart idle detection, and remote desktop support by @kepptic

## Browser Watchers :globe\_with\_meridians:

* [aw-watcher-web](https://github.com/ActivityWatch/aw-watcher-web) ⭐ 556 | 🐛 52 | 🌐 TypeScript | 📅 2026-08-04 - Official browser extension for Chrome, Edge, and Firefox

## Editor Watchers :pencil2:

* [aw-watcher-vscode](https://github.com/ActivityWatch/aw-watcher-vscode) ⭐ 278 | 🐛 22 | 🌐 TypeScript | 📅 2024-01-12 - Visual Studio Code extension by @Otto-AA
* [aw-watcher-vim](https://github.com/ActivityWatch/aw-watcher-vim) ⭐ 123 | 🐛 5 | 🌐 Vim Script | 📅 2023-10-09 - Vim extension by @johan-bjareholt and @ahnlabb
* [aw-watcher-obsidian](https://github.com/LordGrimmauld/aw-watcher-obsidian) ⭐ 112 | 🐛 9 | 🌐 TypeScript | 📅 2023-02-23 - Obsidian.md extension by @LordGrimmauld
* [activity-watch-mode](https://github.com/pauldub/activity-watch-mode) ⭐ 88 | 🐛 8 | 🌐 Emacs Lisp | 📅 2026-03-18 - Emacs mode by @pauldub
* [aw-watcher-jetbrains](https://github.com/OlivierMary/aw-watcher-jetbrains) ⭐ 88 | 🐛 8 | 🌐 Java | 📅 2024-07-08 - For all JetBrains IDEs by @OlivierMary ([JetBrains Marketplace](https://plugins.jetbrains.com/plugin/11361-activity-watcher))
* [ActivityWatchVS](https://github.com/LaggAt/ActivityWatchVS) ⭐ 35 | 🐛 6 | 🌐 C# | 📅 2025-01-07 - Visual Studio extension by @LaggAt
* [aw-watcher-sublime](https://github.com/kostasdizas/aw-watcher-sublime) ⭐ 17 | 🐛 1 | 🌐 Python | 📅 2025-05-27 - Sublime Text 3 by @kostasdizas
* [aw-idea](https://github.com/pascalwhoop/aw-idea) ⭐ 12 | 🐛 0 | 🌐 Java | 📅 2018-12-04 - JetBrains IDE extension by @pascalwhoop (WIP)
* [aw-watcher-atom](https://github.com/NicoWeio/aw-watcher-atom) ⭐ 11 | 🐛 1 | 🌐 JavaScript | 📅 2023-09-12 - Atom by @NicoWeio
* [AwWatcherNetBeans82](https://github.com/pytlus93/AwWatcherNetBeans82) ⭐ 0 | 🐛 0 | 🌐 Java | 📅 2022-04-11 - NetBeans 8.2 by @pytlus93

## Media Watchers :musical\_note:

* [aw-watcher-spotify](https://github.com/ActivityWatch/aw-watcher-spotify) ⭐ 87 | 🐛 13 | 🌐 Python | 📅 2026-05-24 - Tracks currently playing Spotify tracks (Beta)
* [aw-watcher-media-player](https://github.com/2e3s/aw-watcher-media-player) ⭐ 75 | 🐛 5 | 🌐 Rust | 📅 2026-04-25 - Tracks system-wide media playback
* [aw-watcher-lastfm](https://github.com/brayo-pip/aw-watcher-lastfm) ⭐ 15 | 🐛 0 | 🌐 Rust | 📅 2026-07-11 - Tracks Last.fm scrobbles (supports most streaming services)
* [aw-watcher-mpv-sender](https://github.com/RundownRhino/aw-watcher-mpv-sender) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2024-07-20 - Tracks currently playing mpv videos (WIP)
* [aw-watcher-openvr](https://github.com/ActivityWatch/aw-watcher-openvr) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2017-05-25 - For VR applications (WIP)
* [aw-watcher-chromecast](https://github.com/ActivityWatch/aw-watcher-chromecast) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2017-08-02 - For Chromecast devices (WIP)

## Other Watchers :gear:

* [aw-watcher-input](https://github.com/ActivityWatch/aw-watcher-input) ⭐ 167 | 🐛 21 | 🌐 Python | 📅 2024-10-17 - Tracks keyboard/mouse usage statistics
* [aw-watcher-utilization](https://github.com/Alwinator/aw-watcher-utilization) ⭐ 109 | 🐛 10 | 🌐 Python | 📅 2026-01-08 - System resource monitoring by @Alwinator
* [aw-watcher-tmux](https://github.com/akohlbecker/aw-watcher-tmux) ⭐ 94 | 🐛 3 | 🌐 Shell | 📅 2024-02-05 - Monitors tmux sessions by @akohlbecker
* [aw-watcher-ask](https://github.com/bcbernardo/aw-watcher-ask) ⭐ 89 | 🐛 3 | 🌐 Python | 📅 2023-03-16 - Periodically asks user questions (WIP)
* [aw-watcher-table](https://github.com/Alwinator/aw-watcher-table) ⭐ 59 | 🐛 0 | 🌐 Python | 📅 2023-11-20 - Monitors height-adjustable desk position by @Alwinator
* [aw-watcher-steam](https://github.com/Edwardsoen/aw-watcher-steam) ⭐ 38 | 🐛 6 | 🌐 Python | 📅 2025-06-16 - Tracks Steam gaming sessions
* [aw-watcher-anki](https://github.com/abdnh/aw-watcher-anki) ⭐ 33 | 🐛 1 | 🌐 Python | 📅 2023-11-02 - Tracks Anki flashcard review time
* [aw-watcher-netstatus](https://github.com/sameersismail/aw-watcher-netstatus) ⭐ 28 | 🐛 0 | 🌐 Python | 📅 2023-01-31 - Network connectivity monitoring by @sameersismail
* [aw-watcher-toggl](https://github.com/RTnhN/aw-watcher-toggl) ⭐ 20 | 🐛 0 | 🌐 Python | 📅 2025-10-04 - Imports time entries from Toggl
* [aw-watcher-screenshot](https://github.com/InertialG/aw-watcher-screenshot) ⭐ 8 | 🐛 0 | 🌐 Rust | 📅 2026-01-08 - Periodic screenshot capture with perceptual hash filtering and optional S3 upload
* [aw-watcher-buttons](https://github.com/RTnhN/aw-watcher-buttons) ⭐ 5 | 🐛 2 | 🌐 Python | 📅 2026-01-04 - Arduino-based hardware button tracking (WIP)

We also maintain a list of [watchers in the documentation](https://docs.activitywatch.net/en/latest/watchers.html).

Want to create your own watcher? Check out the [writing watchers guide](https://docs.activitywatch.net/en/latest/examples/writing-watchers.html) in the documentation.

Have you written a watcher? Submit a PR to have it included here!

# Importers :inbox\_tray:

Tools for migrating historical time tracking data from other tools into ActivityWatch:

* [aw-import-screentime](https://github.com/ActivityWatch/aw-import-screentime) ⭐ 82 | 🐛 6 | 🌐 Python | 📅 2026-07-27 - Import macOS Screen Time data into ActivityWatch (official)
* [aw-import-toggl](https://github.com/TimeToBuildBob/aw-import-toggl) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-11 - Import Toggl Track time entries from CSV export into ActivityWatch
* [aw-import-rescuetime](https://github.com/TimeToBuildBob/aw-import-rescuetime) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-11 - Import RescueTime activity data from CSV export into ActivityWatch
* [aw-import-manictime](https://github.com/TimeToBuildBob/aw-import-manictime) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-11 - Import ManicTime data directly from its SQLite database into ActivityWatch
* [aw-import-clockify](https://github.com/TimeToBuildBob/aw-import-clockify) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-11 - Import Clockify time entries via API into ActivityWatch
* [aw-import-harvest](https://github.com/TimeToBuildBob/aw-import-harvest) ⭐ 0 | 🐛 0 | 🌐 Python | 📅 2026-03-11 - Import Harvest time entries via API into ActivityWatch

# Sync

* [aw-sync](https://github.com/ActivityWatch/aw-server-rust/tree/master/aw-sync) ⭐ 312 | 🐛 61 | 🌐 Rust | 📅 2026-08-10, the official sync-with-folder/bring-your-own-sync solution for ActivityWatch
* [aw-sync-suite](https://github.com/phrp720/aw-sync-suite) ⭐ 39 | 🐛 1 | 🌐 Go | 📅 2026-08-03, a centralized sync solution backed by Prometheus and visualized with Grafana, by @phrp720
* [activitywatch-exporter](https://github.com/rare-magma/activitywatch-exporter) ⚠️ Archived, CLI tool that uploads the ActivityWatch data from the aw-server API to InfluxDB on a daily basis

# AI/LLM Integrations 🤖

* [activitywatch-mcp-server](https://github.com/8bitgentleman/activitywatch-mcp-server) ⭐ 72 | 🐛 1 | 🌐 TypeScript | 📅 2026-04-15 - A Model Context Protocol (MCP) server that connects to ActivityWatch, allowing LLMs like Claude to interact with your time tracking data

# Videos :tv:

* [ActivityWatch - Application time tracking done well](https://www.youtube.com/watch?v=FIP3Qvja7RM) (2023-2-3)
* [ActivityWatch: Save Time With Helpful Telemetry](https://www.youtube.com/watch?v=ZmYNc-dXm2s) by @BrodieRobertson (2021-6-13)
* [ActivityWatch Development Visualization 2014-2020 (with Gource)](https://www.youtube.com/watch?v=zjIn43lZq3U) by @ErikBjare (2020-12-20)

# Custom dashboards :bar\_chart:

* Metabase dashboard by @SqrtMinusTwo: <https://twitter.com/ActivityWatchIt/status/1522126015082151936>
* Grafana + PrometheusDB + InfluxDB dashboard by @KShivendu: <https://twitter.com/KShivendu_/status/1697483679495557228>

# Donations :moneybag:

Support the development of ActivityWatch by making a donation. Your contribution helps maintain and improve the software, ensuring its continued development.

* [GitHub Sponsors](https://github.com/sponsors/ActivityWatch), support the project through GitHub Sponsors
* [Open Collective](https://opencollective.com/activitywatch), donate and view transparent expenses and funding on Open Collective
* Support individual contributors
  * Erik Bjäreholt's [GitHub Sponsors](https://github.com/sponsors/ErikBjare) or [Patreon](https://www.patreon.com/activitywatch)
  * Johan Bjäreholt's [GitHub Sponsors](https://github.com/sponsors/johan-bjareholt)
* For more, see the [Donate page](https://activitywatch.net/donate/) on the website

Thank you for supporting ActivityWatch and helping it stay afloat financially as free and open-source software! :heart:

# Other links :link:

* [Awesome Quantified Self](https://github.com/woop/awesome-quantified-self) ⭐ 2,756 | 🐛 32 | 📅 2026-07-06, a list of awesome quantified self resources
* [Superuser Labs](https://superuserlabs.org/), company owned and run by founder Erik Bjäreholt for consulting and other ActivityWatch-related services (among other things).
  * [LinkedIn](https://www.linkedin.com/company/superuser-labs/)
  * [Twitter](https://twitter.com/SuperusrLabs)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-13._
