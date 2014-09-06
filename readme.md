### Description

**xuserrun** is used to run a command as the X.org server user.  It discovers the DISPLAY and USER environmental variables via systemd and transfers them to the launch command to be able to run a program via the X.org server display.

### Usage

```bash
xuserrun xclock -digital
```
```bash
xuserrun bash -c "xterm & xclock"
```
