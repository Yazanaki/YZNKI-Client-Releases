# Yazanaki Client

The launcher for the Yazanaki Empire.

## Download

**[Download the latest version](https://github.com/Yazanaki/YZNKI-Client-Releases/releases/latest)** (Windows)

1. On that page, click **Yazanaki-Client-Setup-….exe** under *Assets*.
2. Double-click the file you downloaded.
3. If Windows says "Windows protected your PC", click **More info**, then **Run anyway**.
   This shows up because the installer isn't code-signed yet.

The client installs and opens by itself. Updates are new releases on the same page.

## Publishing a new version

Put the new installer in `installer/` as `Yazanaki-Client-Setup-<version>.exe`
and push. The *Publish release* workflow creates release `v<version>` with it.
