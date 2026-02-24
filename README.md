# Flixarr for iOS

**Sonarr + Radarr + Plex — in one native iOS app.**

> This repository is for issue tracking, beta feedback, and documentation.
> Source code is private.

---

## Join the Beta

[![TestFlight](https://img.shields.io/badge/TestFlight-Join%20Beta-blue?logo=apple&logoColor=white)](https://testflight.apple.com/join/4AncqeX3)

App Store release coming soon. In the meantime, join the public beta on TestFlight.

---

## What is Flixarr?

Flixarr is a native iOS app for managing your self-hosted media server stack. It combines Sonarr, Radarr, and Plex into a single polished interface — so you can browse, add, and watch content without switching between apps.

### Features in v1.0.0

**Home Dashboard**
- Library statistics and system status at a glance
- Recently Added to Plex with direct playback
- Upcoming releases and quick action buttons
- Real-time connection status for Sonarr, Radarr, and Plex

**Sonarr & Radarr**
- Browse your library with posters, metadata, and status badges
- Search and add new content with quality profile and root folder selection
- Monitor and manage the download queue with real-time progress
- Queue actions: remove, blocklist, and retry downloads
- Manual import for failed or unmatched downloads
- Delete content with optional file removal

**Plex**
- Token-based authentication with multi-server support and automatic discovery
- In-app playback via native AVPlayer or fullscreen browser player
- Continue Watching synced across all your Plex clients (web, Roku, Apple TV, etc.)
- Visual watch progress indicators throughout the app
- Automatic connection failover between Plex.Direct and custom domains

**Player**
- Previous/next episode navigation for binge-watching
- Subtitle track selection during playback
- Automatic progress saving and resume
- Fullscreen landscape mode

**Discovery**
- Netflix-style composite genres — AI + rule-based combinations like "Korean Thriller" and "Japanese Anime"
- Personalized recommendations based on your watch history (all processing on-device)
- Calendar view for upcoming episode air dates and movie releases

**Multi-Profile**
- Multiple server configurations in one app (home, VPN, friend's server, etc.)
- Per-profile iCloud sync across your devices (opt-in)
- Each profile stores its own API keys, URLs, and preferences

**iOS Integration**
- Home Screen widget for upcoming releases
- Siri Shortcuts for adding content, checking queue, and searching
- Spotlight Search for your library
- Dark mode, accent color customization (9 options), and Dynamic Type support

### Requirements

- iOS 17.0+
- iPhone or iPad
- A running Sonarr and/or Radarr instance
- Optional: Plex Media Server with a valid Plex token

---

## Reporting Issues

Found a bug or have a feature request? [Open an issue](https://github.com/sinwe/flixarr-community/issues/new/choose).

Please search existing issues before opening a new one.

---

## FAQ

**Is the source code available?**
Not at this time. This repository is for community feedback only.

**Is it free?**
Yes, Flixarr is free.

**Does it support Radarr only / Sonarr only?**
Yes — you can configure either or both. Each is optional.

**Does it support multiple Sonarr/Radarr instances?**
Yes, via multi-profile support. Each profile stores its own server configuration.

**Where is my data stored?**
All server credentials are stored locally on your device. Optional iCloud sync (per-profile, opt-in) syncs your configuration across your own devices only.

**Does it require a Plex Pass?**
No. Basic Plex functionality works without Plex Pass.
