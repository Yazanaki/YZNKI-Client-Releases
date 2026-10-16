# Yazanaki Client

The launcher for the Yazanaki Empire.

## Download

**[Download the latest version](https://github.com/Yazanaki/YZNKI-Client-Releases/releases/latest)** (Windows)

1. On that page, click **Yazanaki-Client-Setup-….exe** under *Assets*.
2. Double-click the file you downloaded.
3. If Windows says "Windows protected your PC", click **More info**, then **Run anyway**.
   This shows up because the installer isn't code-signed yet.

The client installs and opens by itself. From version 0.1.3 on it updates itself:
when a new version is out, a **Restart to update** button appears at the top.

## Publishing a new version

Replace the files in `installer/` with the new `Yazanaki-Client-Setup-<version>.exe`,
its `.blockmap` and `latest.yml` from the client's `dist/` folder, and push. The *Publish release* workflow creates release `v<version>` with it.
