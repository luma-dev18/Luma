# Luma

Luma is an independent Android TV and Fire TV IPTV player with a cinematic home screen and remote-friendly navigation.

## Download

The latest APK and matching GPLv3 source archive are available from the [Releases](https://github.com/luma-dev18/Luma/releases) page. The app package is `app.luma.tv`.

## Features

- M3U playlists over HTTP or HTTPS.
- Standard Xtream-compatible live TV, movie, and series APIs over HTTP or HTTPS.
- Optional XMLTV guide address; standard Xtream XMLTV endpoint fallback.
- HLS and DASH playback through AndroidX Media3.
- Search, category rows, favourites, and TV guide.
- Playlist URL and account details encrypted locally with Android Keystore.

Provider compatibility varies. Modified Xtream APIs, unsupported DRM, or extra authentication headers may not work. Luma does not include channel lists, accounts, or stream URLs. Use only content and subscriptions you are authorized to access.

HTTP is unencrypted. Xtream credentials and viewing activity may be visible to others on the network. Prefer HTTPS when available and use HTTP only with a trusted provider and network.

## Source

The source archive attached to each release contains the corresponding GPLv3 source and build instructions.
