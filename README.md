# Mumla for Mac

Private, on-device dictation. These are signed and notarized Mac beta builds
for macOS 14 or later, on Apple silicon and Intel.

[Download the newest beta](https://github.com/simonbromander/Mumla-Releases/releases)

1. Quit existing copies of Mumla.
2. Download the ZIP, unzip it, and move Mumla to Applications, replacing the
   older copy. Do not run multiple copies at once.
3. Launch Mumla. Grant Microphone, Input Monitoring, and Accessibility in
   System Settings when needed.
4. From build 35 onward, choose **Check for Updates** in Mumla's menu or Settings
   to install future betas without replacing the app manually.

The first updater-enabled build requires one manual installation. The updater
does not migrate local history, dictionary, settings, or downloaded models.
Updates do not change macOS privacy permissions or bypass system security.

Updates are checked only when requested. There is no analytics or system
profiling. Only public release metadata and the app download are requested;
audio and transcripts are never included in update requests.

This repository contains release metadata and signed downloads only. The app's
source is [open under MIT](https://github.com/simonbromander/Mumla); models and
libraries have separate licenses. iOS and sandboxed Mac TestFlight builds use
TestFlight instead of this update feed.

Experimental meetings require Apple silicon and macOS 14.2 or later. From build
47, System audio + microphone is the default, including other apps' sounds.
Choose a specific app or Microphone only for narrower capture. Allow microphone
and system-audio recording permissions, obtain participants' consent, and start
and stop recording explicitly. Real-call audio and permission acceptance remain
outstanding; passing release checks does not establish meeting accuracy.

**Beta status:** actual hotkey and cross-app paste acceptance depends on the
target Mac and its permissions. Downloads and signatures have been verified;
live update installation/relaunch and populated-data preservation still need
acceptance. These checks are not proof that every editor supports paste.
