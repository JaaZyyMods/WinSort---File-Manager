# WinSort

**Your downloads, sorted into the right folders. Automatically.**

*Formerly Jaazorganizer.*

WinSort is a small Windows app that watches your Downloads folder and moves
each new download to the folder you choose, using simple rules.

## Features

- **Rules** by file type (`.mp3 .wav .pdf`...), words in the file name, and where
  the file came from: a website, or even **one specific Gmail or Google Drive account**.
- **Misc folder** (optional): anything that fits no rule goes there, so Downloads stays empty.
- **Timer for each rule**: move files right away, after 1 min, 30 min, 3 hours, or at the next restart.
  For example .mp3 and .wav right away, pictures after 30 minutes. Rules without their own timer use the default.
- **Activity + Undo**: see where every file went, open it, or put it back with one click.
- **Sort now**: tidy up the files that are already sitting in Downloads.
- Notifications, a tray icon, and it starts with Windows when it's on.
- A classic, no-nonsense Windows look: toolbar, lists with columns, status bar.
- A real Windows app (C#, .NET Framework 4.8, already part of Windows 10 and 11). Nothing else to install.

## Get started

1. Download `WinSort.exe` from the [Releases](../../releases) page.
2. Put it in a folder where it can stay (not in Downloads), for example `Documents\WinSort`.
3. Double-click it. Windows may say *"Windows protected your PC"* because the app
   isn't code-signed: click **More info** > **Run anyway**.
4. Set up your rules, then click **[ TURN ON ]**.

Nothing gets installed: WinSort runs from wherever you keep the exe, and while it's
on, Windows starts it from there when you sign in. No admin rights needed.
Requires Windows 10 or 11.

## Updating

Download the new `WinSort.exe` and replace the old one (close WinSort first: right-click its icon
near the clock > **Turn off**). Your rules, timers, settings and history are kept: they are saved
separately on your PC (in `%APPDATA%\WinSort`), so every new version picks them up automatically.
Coming from Jaazorganizer? Your rules come over by themselves the first time you open WinSort.

## Safety

- Nothing is ever deleted or overwritten: files are only moved, and name clashes become `name (1)`.
- Every move can be undone.
- It refuses to put files in Windows, Program Files or Startup folders.
- Windows' "downloaded from the internet" warning stays on moved files.
- Files that are still downloading or open in another app are left alone.
- No internet access, no admin rights, no tracking. Your rules stay on your PC.

## Remove

Open WinSort > **File** > **Remove WinSort from this PC**,
then delete `WinSort.exe`. Files it already moved stay where they are.

## License

Free to use. All rights reserved. See [LICENSE](LICENSE).

