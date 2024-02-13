# VBT Modification

[XY-Tech VBT Information](https://github.com/xy-tech/x330-bios/tree/main/vbt)

VBT modification removes the LVDS port, moves DP-3 to port 1, and labels DP-3 as internal : https://review.coreboot.org/plugins/gitiles/coreboot/+/7a427122a0a01ee396079ded782072081f130e54

Depending on the mod, this may allow the brightness buttons to work as they are mapped to handling internal screen. The mod must have screen brightness controls that software can interact with to work.

This modifcation seems to be for getting brightness to work with eDP and a.gain mods but not confirmed. Nitrocaster should have no issues with this mod.
