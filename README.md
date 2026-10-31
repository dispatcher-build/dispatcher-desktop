# Dispatcher desktop

Installers for the Dispatcher desktop app (macOS and Linux). Download the latest build from
[dispatcher.build/download](https://dispatcher.build/download) or from the
[Releases](https://github.com/dispatcher-build/dispatcher-desktop/releases) page.

The app runs the whole Dispatcher stack on your machine: it needs Docker Desktop (or the Docker
engine) and a Dispatcher account, which is the same sign-in as the website.

- macOS: open the `.dmg` and drag Dispatcher to Applications. Builds are not yet notarized, so
  right-click the app and choose Open the first time.
- Linux: `chmod +x` the `.AppImage` and run it, or install the `.deb` with `sudo apt install ./<file>.deb`.

Source lives in the main Dispatcher repository; this repository only hosts release assets.
