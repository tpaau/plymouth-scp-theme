# SCP Foundation Logo Plymouth Theme

Plymouth theme that displays an animated SCP Foundation logo along with the Foundation's motto.

![showcase](https://github.com/tpaau/plymouth-scp-theme/blob/main/images/showcase.gif)

> [!NOTE]
> The animation here tears a bit because it's recorded in a VM with no GPU acceleration.

## Installing (works for most distros)
You should have Plymouth installed and hooked into your initrd.

1. Clone this repo somewhere.
2. Copy the `scp` folder to `/usr/share/plymouth/themes/`.
3. Run `plymouth-set-default-theme -R scp` as root.

## Testing
Run this in a TTY as root:
```bash
plymouthd --debug; plymouth --show-splash; sleep 10; plymouth quit
```
