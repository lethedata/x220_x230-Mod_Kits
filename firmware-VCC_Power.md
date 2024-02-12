# VCC Power Mod

Nitrocaster is powered by constant VCC power. This allows functionality of mod without any firmware hacks as the display remains on? To allow controllable power, remove the power cable and short J1 on the nitrocaster, then modify the firmware (gma.c) to control power from VCC3P rather than VCC : https://daduke.org/hardware/x220-fhd/