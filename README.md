# SCP Foundation Logo Plymouth Theme

Boot splash plymouth theme that displays an animated SCP Foundation logo.

## Installing (works for most distros)
You should have Plymouth installed and hooked into your initrd.

1. Clone this repo somewhere.
2. Copy the `scp` folder to `/usr/share/plymouth/themes/`.
3. Run `plymouth-set-default-theme -R scp` as root.

## Testing
```bash
plymouthd --debug; plymouth --show-splash; sleep 10; plymouth quit
```
