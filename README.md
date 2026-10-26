# WorkKit Buddy

A free desktop pet for macOS, Windows and Linux. It sits on your screen, dances to whatever your computer is
playing, reacts to Claude Code and Codex while they work, and reminds you to take breaks.

Product page and install guide: **https://www.workkit.in/buddy/**

This repository hosts the release downloads. The app itself is free but not open source.

## Download (1.5)

Get the files from the [latest release](https://github.com/abhi-24395/workkit-buddy/releases/latest).

| Platform | File |
|---|---|
| macOS 14 or newer, Apple silicon and Intel | `WorkKitBuddy-1.5.pkg` |
| Windows 10 / 11, 64-bit | `WorkKitBuddy-Setup.exe`, or `WorkKitBuddy-windows.zip` to run without installing |
| Linux, any distribution | `WorkKitBuddy-linux-x86_64.AppImage` |
| Debian, Ubuntu, Mint, Pop!_OS | `workkitbuddy_1.5.0_amd64.deb`, `workkitbuddy_1.5.0_arm64.deb` |
| Anything else | `WorkKitBuddy-linux-x86_64.tar.gz`, `WorkKitBuddy-linux-aarch64.tar.gz` |

From 1.2 on, the buddy tells you itself when a new version is out.

## What it does

- **Reacts to your coding agent.** Connect Claude Code or Codex from the menu and the buddy shows what the
  agent is doing: thinking, editing, running tests, waiting for you, done, or stuck on an error.
- **Dances to your music.** Real beat and tempo detection on whatever is playing: Spotify, YouTube in any
  browser, games.
- **Delivers reminders in person.** An envelope drop, a paper plane or a knock, then a card you can dismiss.
- **Focus timer and breaks.** 25-minute focus sessions, and after 50 minutes in the chair it walks you
  through three short desk stretches. Stand-up and wrap-up nudges, meeting alerts, quiet hours.
- **23 characters.** Kit the fox, Duck, Bot, Pengu, Capy, Corgi, Octo, Bao the panda, Lotl the axolotl, Rex and more, or drag any
  picture onto it.
- Stays where you put it. Optional follow-the-cursor, a click-through ghost mode, and one hotkey to hide it.

## Privacy

No account, no analytics, no telemetry, no crash reports. From your coding agent it reads the event name,
the tool name and, only to tell whether tests are running, the shell command. Never your prompts or the
model's replies. What leaves your computer: a daily version check to GitHub, your calendar download if you
use meeting alerts on Windows or Linux, and your question if you use Ask (sent with your own API key).
The full list is at https://www.workkit.in/buddy/#privacy.

## Known limits

- The installers aren't signed with a paid certificate yet, so macOS and Windows each show one warning the
  first time. macOS: click **Done**, then System Settings › Privacy & Security › **Open Anyway**.
  Windows: **More info** › **Run anyway**.
- The Windows installer is large (about 155 MB) because it carries its own .NET runtime.
- Built and tested on a Mac. The Windows build is compiled and checked from macOS and the Linux build is
  tested in a container; neither has been run on physical hardware by us yet. Bug reports are welcome in
  [Issues](https://github.com/abhi-24395/workkit-buddy/issues).

## Follow along

- Instagram: https://www.instagram.com/workkit.in/
- LinkedIn: https://www.linkedin.com/company/workkit-in/

Made by [WorkKit](https://www.workkit.in).
