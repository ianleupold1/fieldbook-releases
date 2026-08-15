# Fieldbook — releases

Installers for [Fieldbook](https://github.com/ianleupold1/fieldbook), the
offline-first invoicing app built for Oasis Irrigation.

This repository is public for one reason: the app's auto-updater has to be able
to fetch `latest.json` and the signed installer without credentials. The source
code, and anything containing customer information, stays in the private
repository.

Nothing here is written by hand — every release is published by CI from a
tagged build.

## Installing

Download the latest `Fieldbook_x.y.z_x64-setup.exe` from
[Releases](../../releases/latest) and run it. Windows 10 or 11.

Once installed, the app updates itself: it checks on launch and offers the new
version in Settings → About.
