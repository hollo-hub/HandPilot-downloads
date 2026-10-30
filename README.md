# HandPilot Downloads

HandPilot is a local-first webcam gesture controller by hollo-hub. Releases
are built from the existing [HandPilot source repository](https://github.com/hollo-hub/HandPilot)
by GitHub Actions; this repository contains distribution files only.

## Latest release

Download [HandPilot v0.1.1](https://github.com/hollo-hub/HandPilot-downloads/releases/tag/v0.1.1):

- **Windows:** `HandPilot.exe`
- **Linux x86_64:** `HandPilot-linux-x86_64.tar.gz`

### Windows

Download `HandPilot.exe`, allow camera access, and press **Start tracking**.
Windows SmartScreen may warn because this unsigned community build is new.

### Linux

Extract the tarball and run the `GestureControl` executable from a graphical
Linux desktop session. A webcam is required. On X11, set `DISPLAY` normally;
on Wayland, input injection can be limited by the compositor. The Linux build
is x86_64 and is not a Debian/RPM package.

## Testing feedback

Please report the OS, desktop session, webcam, whether the preview appeared,
the gesture attempted, the action observed, and any exact error text in the
source repository issues.
