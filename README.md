# Adrak for Windows and Mac

Adrak is a learning app for Windows 10 and 11 and for Macs with Apple silicon: interactive lessons with maps, code,
diagrams, math and quizzes, a library of ready-made lessons, and an AI Agent that writes new lessons, practice and exams
for what you are learning.

## Download

On Windows, get **AdrakApp-win-Setup.exe** from the
[latest release](https://github.com/snwaf929-cpu/adrak-releases/releases/latest) and run it. It installs Adrak for your
Windows account, with no administrator rights needed, and keeps it up to date: Adrak looks here for new versions and
offers to restart into them.

The first time, Windows may say "Windows protected your PC", because the installer is not code-signed yet. Choose
**More info**, then **Run anyway**.

On a Mac with Apple silicon (M1 or newer), get **AdrakApp-osx-Setup.pkg** from the same release and open it. Adrak keeps
itself up to date there too. The Mac version has the Agent, lessons and Settings; practice and exams come in a later
update.

The first time, macOS may say it can't check the installer, because Adrak isn't signed by Apple yet. Click **Done**,
open **System Settings → Privacy & Security**, and click **Open Anyway** next to the message about the installer.

## Your learning

What you learn stays on your computer: in `%LocalAppData%\Adrak` on Windows, and in
`~/Library/Application Support/Adrak` on a Mac. In Settings you can link a GitHub repository of your own to keep it in
sync between your computers. Uninstalling Adrak leaves it in place.

This repository holds only the installers and their updates.
