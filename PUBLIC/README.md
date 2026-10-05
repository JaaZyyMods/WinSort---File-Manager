<p align="center">
  <img src="Jaazorganizer-logo.png" width="128" alt="Jaazorganizer logo">
</p>

# Jaazorganizer

**Your downloads, sorted into the right folders. Automatically.**

Jaazorganizer is a small Windows app that watches your Downloads folder and moves
each new download to the folder you choose, using simple rules.

## Features

- **Rules** by file type (`.mp3 .wav .pdf`...), words in the file name, and where
  the file came from: a website, or even **one specific Gmail or Google Drive account**.
- **Misc folder** (optional): anything that fits no rule goes there, so Downloads stays empty.
- **Timer**: move downloads right away, after 1 min, 30 min, 3 hours, or at the next restart.
- **Activity + Undo**: see where every file went, open it, or put it back with one click.
- **Sort now**: tidy up the files that are already sitting in Downloads.
- Notifications, a tray icon, and it starts with Windows when it's on.

## Install

1. Download `Jaazorganizer.exe` from the [Releases](../../releases) page.
2. Double-click it. Windows may say *"Windows protected your PC"* because the app
   isn't code-signed: click **More info** > **Run anyway**.
3. Set up your rules, then click **[ TURN ON ]**.

After the first start, Jaazorganizer is in your Start menu.
Requires Windows 10 or 11.

## Safety

- Nothing is ever deleted or overwritten: files are only moved, and name clashes become `name (1)`.
- Every move can be undone.
- It refuses to put files in Windows, Program Files or Startup folders.
- Windows' "downloaded from the internet" warning stays on moved files.
- Files that are still downloading or open in another app are left alone.
- No internet access, no admin rights, no tracking. Your rules stay on your PC.

## Remove

Open Jaazorganizer > **[3] settings + safety** > **[remove jaazorganizer]**.
Files it already moved stay where they are.

## License

Free to use. All rights reserved. See [LICENSE](LICENSE).
