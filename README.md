# Veilgram BUILD-0

This public repository contains **CI verification infrastructure only**. Veilgram product source and development history live in the private [Jigros/Veilgram-IOS](https://github.com/Jigros/Veilgram-IOS) repository. This repository is not a second source of truth for Veilgram.

BUILD-0 compiles the unchanged official [Telegram-iOS](https://github.com/TelegramMessenger/Telegram-iOS) source at `6ad963e5b62d354da79040f388ae2b9132fb17b8` for an iOS simulator. Runtime build configuration uses synthetic compile-only values and disables provisioning. There are **no production API credentials, signing certificates, sessions, or Veilgram product source** here.

A successful workflow proves that specific upstream target compiled in the recorded macOS/Xcode/Bazel environment. It does not produce an installable Veilgram release.
