# Mumla for Mac

Private, on-device dictation. These are signed and notarized Mac beta builds
for macOS 14 or later, on Apple silicon and Intel.

[Download the newest beta](https://github.com/simonbromander/Mumla-Releases/releases)

1. Quit existing copies of Mumla.
2. Download the ZIP, unzip it, and move Mumla to Applications, replacing the
   older copy. Do not run multiple copies at once.
3. Launch Mumla. Grant Microphone, Input Monitoring, and Accessibility in
   System Settings when needed.
4. From build 33 onward, choose **Check for Updates** in Mumla's menu or Settings
   to install future betas without replacing the app manually.

The first updater-enabled build requires one manual installation. Subsequent
updates preserve local history, dictionary, settings, and downloaded models.
Updates do not change macOS privacy permissions or bypass system security.

Updates are checked only when requested. There is no analytics or system
profiling. Only public release metadata and the app download are requested;
audio and transcripts are never included in update requests.

This repository contains release metadata and signed downloads only. The app's
source repository remains private. iOS and sandboxed Mac TestFlight builds use
TestFlight instead of this update feed.

**Beta status:** actual hotkey and cross-app paste acceptance depends on the
target Mac and its permissions. Signing and update installation checks are not
proof that every editor supports paste.
