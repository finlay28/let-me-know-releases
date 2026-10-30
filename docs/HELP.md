# Privacy and troubleshooting

## Local data

The official app keeps preferences, custom sounds, queued events and notification history in `~/Library/Application Support/Global AI Ping`. The legacy folder name preserves existing installations after the rename. Test V1 uses its own `Let Me Know Test V1` folder and app identifier.

Connecting a provider adds the app's hook command to supported local configuration files. Backups are made before configuration changes. Disconnect providers in the app before uninstalling it. Remove its login item if you enabled launch at login. Deleting the app alone does not erase its local history or sounds.

Audio ducking requires system-audio permission. Audio is processed locally, not stored or uploaded. Update checks contact GitHub and downloads are signature-verified. Do not post private session logs or audio in public issues.

## No notification

Check that the app is running and active, the provider is connected, and a sound or banner is enabled. Restart Claude Code sessions after connecting. Ordinary Claude and ChatGPT chats are outside the current scope. When testing Test V1, quit the normal app to avoid duplicate alerts and competing audio processing.

## No ducking

Ducking needs macOS 14.2+, a supported audio output and system-audio permission. Check System Settings → Privacy & Security → Screen & System Audio Recording. A capture failure can also reflect an unavailable audio device, rather than a denied permission. Banner and sound delivery can continue without ducking.

## Installation is blocked

The official v0.9.0 DMG is now signed and Apple-notarized, with its ticket attached. If you downloaded an earlier copy of v0.9.0 before notarization, download it again from this repository. The standard first-open internet-download confirmation may still appear. Do not disable Gatekeeper or run commands from strangers. If the new download is blocked, report the exact message and macOS version.

## Reporting a bug

Include app version, macOS version, Mac chip, AI-client version, audio output and reproduction steps. Redact private conversation contents and account identifiers. This is a preview, so compatibility with every client version and audio device is not guaranteed.
