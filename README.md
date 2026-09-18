<div align="center">

<img src="logo.png" width="150" alt="FrostByte logo">

# FrostByte

**Weather Visualization Suite (Beta)**

A desktop app that renders live meteorological, oceanic, tropical-cyclone,
aviation, radar/satellite, and space-weather graphics from official public
data sources.

</div>

---

This repository holds FrostByte's **installers**. Get the newest one from the
[**Releases page**](../../releases/latest); the app's own update check reads the
same page.

Everything the app needs — the Python runtime, the scientific stack, and the
bundled helper tools — ships inside the installer. Nothing else to install. The
illustrated User Guide and the Theory & Math reference open from the app's
Jobs bar.

## Windows 10/11 (64-bit)

1. Download **`FrostByte-<version>-Setup.exe`** from the latest release.
2. Double-click. This beta is **not code-signed**, so Windows SmartScreen shows
   *"Windows protected your PC"* — click **More info → Run anyway**. Your
   antivirus may flag it for the same reason.
3. Follow the wizard (per-user install, no admin needed), then launch
   **FrostByte** from the Start Menu.

## Linux (64-bit, Debian/Ubuntu family)

```bash
sudo dpkg -i frostbyte_*_amd64.deb
```

Then launch **FrostByte** from your applications menu, or run `frostbyte`.
Uninstall with `sudo dpkg -r frostbyte`.

> Both installers set up the bundled runtime once at the end of installation
> (about a minute) — let that step finish.

## License and source

FrostByte is free software under the GNU General Public License, version 3 or
later (see `LICENSE.txt`). The complete Python source of each version ships
inside its installer, in the install directory.

Copyright (C) 2026 Evan James Lane.
