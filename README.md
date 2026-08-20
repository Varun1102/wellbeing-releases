# Wellbeing — releases

Download the latest installer from the [Releases page](https://github.com/Varun1102/wellbeing-releases/releases/latest).

Wellbeing is a Windows tray app that nudges you to drink water, take breaks, and rest
your eyes — and holds the nudge back when you are away from the machine rather than
piling reminders up.

## Installing

Run the `.msi`. Windows will warn you that the publisher is unrecognised, because the
installer is not code-signed yet: **More info → Run anyway**. It installs for your user
only, so it never asks for an admin password.

**Upgrading?** Quit Wellbeing from the tray first, then run the new installer over the
top. Your settings are kept. If you skip the quit, the installer still succeeds but the
old version keeps running until you restart it.

## latest.json

`latest.json` is the update manifest the app itself reads on startup. If it finds a
version newer than the one running, it offers a link to this page. It never downloads
or runs anything on its own.

Source code lives in a separate private repository.
