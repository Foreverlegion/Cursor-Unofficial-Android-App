# Privacy Policy

Unofficial Cursor for Android (`com.cursorandroid.app`)  
Last updated: November 2, 2026

**Not affiliated with Cursor or Anysphere.** This is an unofficial, personal project by Foreverlegion. It is not made by, endorsed by, sponsored by, or connected to Cursor or Anysphere.

## Summary

- The app is **free**. No ads, no in-app purchases, no paid unlocks from the developer.
- No third-party advertising SDKs, analytics SDKs, crash reporters, or trackers are embedded by the developer.
- Your Cursor API key and optional GitHub token are stored **on your device** (encrypted SharedPreferences; if the device cannot provide that, they are kept in memory only and never written to disk in plain text).
- Network traffic is for Cursor’s public Cloud Agents APIs, optional GitHub features you use with your token, MCP servers you configure, and anonymous in-app feedback when you choose to send it.
- The app installs and updates **only through Google Play**. There is no in-app update checker and no sideloaded APK distribution from the developer.

## Data stored on your device

- **Cursor user API key** — required to use Cloud Agents. Stored locally; not sent to the app developer.
- **Optional GitHub personal access token** — only if you add one in Settings (for creating a GitHub repo from New agent and related GitHub features). Stored locally.
- **App preferences** — notification toggles, theme, MCP server configs you enter, mute state, drafts, caches of conversation/inbox data needed to show the UI.

Uninstalling the app removes app-private storage, subject to Android backup/restore behavior.

## Network use

- **Cursor / Anysphere APIs** (for example `api.cursor.com`) — using *your* API key to list agents, start runs, stream status, fetch artifacts, and related Cloud Agents features. Prompts and agent content go to Cursor under your account; this client does not operate a separate agent backend.
- **Optional browser sign-in** — can open cursor.com flows to mint a user API key for this client.
- **GitHub** (`api.github.com`, `github.com`, and related GitHub hosts) when you use GitHub-related features that require your token, such as creating a repository from the app.
- **MCP servers you configure** — if you add HTTP/stdio MCP endpoints, the app contacts those hosts you chose (or Cursor’s cloud VMs as applicable). That is under your control.

## Feedback and bug reports

From **Settings → Report a bug** (or feedback), you can send a report to the developer. It is an **anonymous** report: the text you write, plus the app version and Android version. No name, email, API key, or device identifier is attached. This matches the in-app footer: *Anonymous report from the Android app. No name, email, API key, or device is attached.*

## Notifications

With permission, the app can show local notifications when a run finishes or needs approval (including per-chat mute). Notification content is generated on-device from agent status you already have access to; it is not sold or used for advertising.

## Install count

The app does not collect an install count and does not send an install identifier. Older test builds did. That ping was removed before this Play release.

## What the developer does not collect

- No developer-operated ad network, marketing pixel, or behavioral advertising profile.
- The developer does not receive your Cursor API key or chat contents through a separate telemetry pipeline.
- Data you send to Cursor or GitHub is processed by those services under *their* terms and privacy policies.

## Children

The app is a developer tool for managing cloud coding agents. It is not directed at children under 13.

## Changes

Updates to this policy will be posted on this page with a revised “Last updated” date.

## Contact

Contact: foreverlegion@gmail.com

You can also use in-app feedback (**Settings → Report a bug**) as described above.

Policy home: [github.com/Foreverlegion/Cursor-Unofficial-Android-App](https://github.com/Foreverlegion/Cursor-Unofficial-Android-App) (`PRIVACY.md` on the default branch).

This public repository has no issue tracker. Do not open GitHub Issues here for privacy questions.
