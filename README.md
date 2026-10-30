# HandPilot Downloads

HandPilot is a local-first webcam gesture controller by hollo-hub. Releases
are built from the existing [HandPilot source repository](https://github.com/hollo-hub/HandPilot).

## Latest: v0.1.3

- [Windows HandPilot.exe](https://github.com/hollo-hub/HandPilot-downloads/releases/download/v0.1.3/HandPilot.exe)
- [Linux x86_64 tarball](https://github.com/hollo-hub/HandPilot-downloads/releases/download/v0.1.3/HandPilot-linux-x86_64.tar.gz)

### Linux launch

Extract the archive, open a terminal in the extracted folder, and run:

```bash
chmod +x GestureControl
./GestureControl
```

Running from a terminal is recommended for the first launch because it shows
any platform or camera error. The Linux build targets x86_64 graphical Linux.
On X11, `pynput` needs `DISPLAY`; on Wayland, input injection may be limited by
the compositor. The app opens before loading input actions and reports startup
errors visibly.

### Windows launch

Download `HandPilot.exe`, allow camera access, and press **Start tracking**.
Windows SmartScreen may warn because this unsigned community build is new.

### Feedback

Report OS, desktop session, webcam, whether the window opened, whether the
preview appeared, the gesture attempted, the action observed, and exact error
text in the [source repository issues](https://github.com/hollo-hub/HandPilot/issues).
