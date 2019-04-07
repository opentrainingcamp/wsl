# Install Xserver on Windows 10

# Some scripts 

Many Linux GUI apps use the D-Bus for inter-process communication (IPC). Try running the following commands after launching X410:

```bash
export DISPLAY=127.0.0.1:0.0
dbus-launch --exit-with-x11
```

If you're getting a "command not found" error, install the 'dbus-x11' package:

`sudo apt install dbus-x11`