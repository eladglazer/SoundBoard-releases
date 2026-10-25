# SoundBoard releases

Installers for **SoundBoard**, a Windows soundboard that plays sounds into your microphone, so
everyone in Discord, a game or a meeting hears them.

This repository only holds the releases. Download the newest
`SoundBoard-Setup-<version>.exe` from [Releases](https://github.com/eladglazer/SoundBoard-releases/releases/latest).

## Install

1. Run `SoundBoard-Setup-<version>.exe`. It needs administrator permission and installs to
   Program Files. Windows 10 (2004) or 11, x64; no .NET install needed.
2. The installer isn't code-signed yet, so Windows SmartScreen may say it "protected your PC".
   Click **More info** → **Run anyway** if you trust this download. Each release lists the
   file's SHA-256 so you can check it: `Get-FileHash .\SoundBoard-Setup-<version>.exe`.
3. The first start opens Setup: pick your microphone, install the mic mixer (Windows asks for
   permission), check it in Discord, and add your first sounds.

## Update

SoundBoard checks this page when it starts and shows **Update** at the top when a newer version
is out. Download the new setup and run it over the old one; your sounds and settings stay.

## Uninstall

Windows Settings → Apps → SoundBoard → Uninstall. This also removes the mic mixer and puts your
microphones' original settings back. Your sounds stay in `%AppData%\SoundBoard`.
