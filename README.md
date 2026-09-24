# WorkKit Buddy

A free desktop companion for macOS and Windows from [WorkKit](https://www.workkit.in) — product page: https://www.workkit.in/buddy/

This repository hosts the release downloads. The latest installers are on the [Releases](https://github.com/abhi-24395/workkit-buddy/releases) page.

A free desktop companion for macOS and Windows from WorkKit — https://www.workkit.in/buddy/

## Downloads

| File | For | Notes |
|---|---|---|
| `WorkKitBuddy-1.1.pkg` | macOS 14 Sonoma or newer, Apple silicon and Intel | Installs the app and the lock-screen screen saver |
| `WorkKitBuddy-Setup.exe` | Windows 10 / 11, 64-bit | Per-user install, no administrator rights |
| `WorkKitBuddy-windows.zip` | Windows 10 / 11, 64-bit | Portable — unzip anywhere and run `WorkkitBuddy.exe` |

The installers are self-signed (no Apple Developer ID or Microsoft certificate yet), so each system shows a one-time notice:
macOS — click **Done**, then System Settings › Privacy & Security › **Open Anyway**; Windows — **More info** › **Run anyway**.

## What it does

- Dances to whatever your computer plays, with real beat and tempo detection (Spotify, YouTube in any browser, games).
- Delivers notifications in person — envelope drop, paper plane, knock, confetti — then a card with Open / Snooze / Dismiss.
- Reacts to Claude Code: thinking, editing, testing, waiting for you, done, error.
- Focus timer, break reminders, stand-up and wrap-up nudges, meeting alerts, battery warnings, quiet hours.
- Seventeen characters (the WorkKit logo, Kit the fox, Duck, Bot, Pengu, Blob, Spike, Hoot, Mocha, Corgi, Capy, Octo, Buzz, Boo, Slo, Cat, Briefcase) or any picture you drag onto it.
- Stays where you put it; optional follow-the-cursor; ghost (click-through) mode; one hotkey to hide or summon.

## Known limits in this release

- The Windows build is cross-compiled from macOS and has not yet been verified on real Windows hardware.
- Tested on one Apple-silicon Mac; Intel Macs and macOS 14 are untested.
- Everything runs on your machine; nothing is recorded or uploaded. Music detection needs the System Audio Recording permission on macOS (a single Allow dialog); Windows needs no permission.
