# x220_x230-Mod_Kits

There are a multiple Thinkpad X220 and X230 mod kits floating around. This repo attempts to provide some clarity regarding the differences of each.

Information here may be inaccurate as finding informatoin without direct access to the boards is rather 

## Known Mod Kits

There seems to be three different styles Nitrocaster, eDP only, and a.gain. All boards require a [firmware screen patch](firmware-Screen_Patch.md) to fully disable the original LVDS display.

### Nitrocaster: LVDS and EDP

Uses LVDS and EDP to control brightness. [VBT modifications](firmware-VBT_patch.md) should NOT be used. May require an aditional mod to deal with [VCC Power](firmware-VCC_Power.md).

- [Nitrocaster](images/nitrocaster-nitrocaster.png) : [nitrocaster store](https://nitrocaster.me/store/x220-x230-fhd-mod-kit.html) [(archive)](https://archive.is/TbwNl)

### eDP Only : EDP only

Only has the eDP and nothing else. Brightness controls implemented via power button and a USB HID devivice hooked into the X230's USB 2.0 bus.

- [eDP v4.0 for X230 X220](images/eDP-eDP%20v4.0%20for%20X230%20X220%20(2K).png) : [aliexpress](https://www.aliexpress.us/item/3256805565969412.html) [(archive)](https://archive.is/GfvCe)
- eDP v5.0 for X230 X220 :
- [eDP v5.1 for X230 X220](images/eDP-eDP%20v5.1%20for%20X230%20X220%20(2K).png) : [aliexpress](https://www.aliexpress.us/item/3256804036188775.html) [(archive)](https://archive.is/Bi991)
	
### a.gain : EDP and mSATA+USB3.0
Includes an mSATA+USB3.0 port. Brightness controls implemented via power button and a USB HID devivice hooked into the X230's USB 2.0 bus.

- [X220_X230 FHD RevA1.0](images/a.gain-X220_X230%20FHD%20RevA1.0.png) : [aliexpress](https://www.aliexpress.us/item/3256805565927750.html)
- [X230 QHD RevA1](images/a.gain-X230%20QHD%20RevA1.png) :
- [X220_X230 WQHD RevA1.0](images/a.gain-X220_X230%20WQHD%20RevA1.0.png) :
- [eDP V3.3 for X220 & X230 - msata3+USB3.0 port](images/a.gain-eDP%20V3.3%20for%20X220%20&%20X230.png) 
- [K.K-Thinkpad x230 FHD/ WQHD 2K屏改裝/加裝mSATA/USB3.0板](images/K.K-Thinkpad%20x230%20FHD-WQHD%202K.png) : [taobao](https://world.taobao.com/item/557203626813.htm) [(archive)](https://archive.ph/8UMyB)
