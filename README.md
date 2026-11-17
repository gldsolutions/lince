# Lince

[![Version](https://img.shields.io/github/v/release/gldsolutions/lince?label=version)](https://github.com/gldsolutions/lince/releases/latest)
[![Android](https://img.shields.io/badge/Android-8.0%2B-3ddc84)](#requirements)
[![Downloads](https://img.shields.io/github/downloads/gldsolutions/lince/total?label=downloads)](https://github.com/gldsolutions/lince/releases)

A file manager for Android with an APK studio, a code editor, a Linux environment, a browser with an interception proxy and an AI agent. No root required, no ads, no tracking.

Made by [GLD Solutions](https://gldsolutions.com.br). Free to use; distributed as an APK only.

**[Download the latest version](https://gldsolutions.com.br/lince/download)** · [Product page](https://gldsolutions.com.br/lince) · [Release notes](https://github.com/gldsolutions/lince/releases) · [Privacy policy](https://gldsolutions.com.br/lince/privacidade.html)

## Installation

1. Download `Lince-x.y.z.apk` from the [site](https://gldsolutions.com.br/lince/download) or from the [latest release](https://github.com/gldsolutions/lince/releases/latest).
2. Open the file on the device and allow installing apps from that source when Android asks.
3. Confirm the installation.

### Verifying the download

Every release lists the SHA-256 of the APK, and every build is signed with the same key. Certificate SHA-256:

```
88f35bcf97054a9428a70216e17bf6461a670c685590c403b53b10cd0c01ee43
```

Updates installed from inside the app check the file's SHA-256 and the signature before installing, so a modified or third-party build never replaces the official one.

### Requirements

- Android 8.0 (API 26) or newer; arm64-v8a, armeabi-v7a, x86 and x86_64.
- Android may warn that the app was built for an older version of Android. That is expected: it lets the Linux environment run the programs you install.

## Features

| Area | What it does |
|---|---|
| Files | Two panes, trash, undo, favorites, search by name and content, folder compare and sync, fingerprint vault; ZIP, 7z, TAR and RAR, AES ZIP, browsing archives without extracting |
| APK studio | Install APK, APKS, XAPK and APKM; edit manifest, strings, resources, smali and Java; v1 to v3 signing; decompile to a project and build back; compare APKs |
| Code editor | More than 160 languages, autocomplete, formatting, lint, Git gutter and Git client; project tasks (npm scripts, Makefile and Cargo detected automatically); a debugger for Python, JavaScript/TypeScript, C, C++, Rust and Go |
| Linux | Debian, Ubuntu, Arch or Alpine without root; Linux Display for programs with windows |
| Viewers | PDF, spreadsheets, SQLite, DOCX, PPTX, EPUB, hex, images, audio and video |
| Network | FTP, SFTP, SMB and WebDAV clients with passwords in the Android Keystore; FTP server and access from a computer's browser, limited to the local network |
| Browser and proxy | Tabs, localhost access, downloads with page cookies; HTTP/HTTPS proxy with history, interception, repeater, decoder, comparer, replace rules and scope |
| AI agent | Codes, runs commands in Lince Linux, uses Git, tests in the browser and on the device, uses MCP servers. Your own key with Anthropic, OpenAI, Gemini, OpenRouter, Ollama and compatible APIs, or fully on the device with llama.cpp |
| Cloud agent | Optional. Hand a task to the Lince server; it keeps working with the phone offline, and you read the result and download its files later |
| Automation and system | Background tasks with notifications, scheduled backup/mirror/cleanup, app backup, logcat, root, Shizuku and wireless ADB |
| Customization | Themes, plugins, widgets and keyboard shortcuts |

Languages: English, Portuguese, Spanish, French, German, Italian, Russian and Simplified Chinese.

## Reporting problems

Open an [issue](https://github.com/gldsolutions/lince/issues/new/choose) with the Lince and Android versions, the device model, the steps, what you expected and what happened. If the app closed by itself, Lince shows the error report the next time it opens, with a button to copy it.

## License

Copyright © 2026 GLD Solutions. All rights reserved. Lince is proprietary software, free to use; see [LICENSE](LICENSE). Open source components keep their own licenses, listed in the app under About, Licenses.
