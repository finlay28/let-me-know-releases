# Global AI Ping
A native macOS menu-bar companion for local Codex and Claude Code sessions.

This repository contains public downloads and the cryptographically signed Sparkle update feed. Source code is maintained separately in a private repository.

## Download
See [Releases](https://github.com/finlay28/global-ai-ping-releases/releases).

Current releases are previews for Apple silicon, macOS 14+ (14.2+ for audio ducking). They are not yet Apple Developer ID signed or notarized, so macOS may block first launch on another Mac.

## Updates
Version 0.7.0 introduces in-app updates. Earlier versions need a one-time manual installation. The app checks the signed feed, offers installation now or later, verifies downloaded update signatures, and restarts after installation. You can disable automatic checks in Settings.

## Privacy
Session detection and audio processing happen locally. Systemaudio is processed live for optional ducking and is not recorded or uploaded. Update checks contact GitHub; no chat data is sent.
