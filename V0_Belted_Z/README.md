# V0 Universal Belted Z
This is a new belted Z mod for the Voron Zero. It drops the Z drive below the bottom frame extrusion. This allows full range of motion for both stock (V0.0/V0.1/V0.2) and Kirigami setups. It has been tested with 5:1 gearing up to 300mm/s at 1000mm/s/s z accels and 200mm/s at 3000mm/s/s with an OMC-17HS08-1004S motor set to run_current: 0.5.

If you are installing fresh you will need to install the motor plate after installing the rear panel (the rest of the Z drive can be installed before).  You will also need to install the bedmount prior to mounting the back panel for the stock bed setups as they bolt from the back.  For the Kirigami the whole thing can be installed without removing the panel.

For the Z Drive itself, you will need three F695 bearings, a 200mm GT2 belt loop, and a 5mm OD by 75mm long shaft with flats for pulleys.  Longer shafts will also work (I am using a 100mm currently because I was too lazy to cut it shorted) as long as you set the end flush with the pulley in the 80 tooth, but you'll need to restrain cables to ensure they don't get near the shaft.

For the upper idler there are two models, one that can use F695 bearings and one for F623 bearings. I highly recommend using F623 bearings as the belt alignment will be a little bit better and if you're building a V0 you probably have two extras.

For bolt/nut/heatset counts they should all be in place in the CAD, each configuration has slight differences.

## Updates

### 2023-04-24

It was brought to my attention by mapaba#0044 on the Discord that there were some clearance issues with the rear skirt and power inlet on the V0.2 which could be fixed by mirroring the assembly to shift the z drive further from the power inlet.  All components have been switched to a mirrored assembly for better compatibility with V0.2 parts while maintaining compatibility with the other configurations as well.  

The old parts are still fine for V0.0 or V0.1 builds, but for new build V0.2 or upgrading to V0.2 from a prior revision it is recommended to use the new mirrored assembly.  Drilling a hole in the rear panel may be required to use the mirrored z-min endstop. It is recommended to use the newer z-max endstop configuration.

This mod is compatible with V0.0, V0.1, and V0.2 in either Kirigami or Stock Bed configurations as of 2023-04-24.

## Pictures

### Kirigami Bed

![ZBelt-Pic001](Images/v0zbelt_kirigami1.png)
![ZBelt-Pic002](Images/v0zbelt_kirigami2.png)

### Stock Bed

![ZBelt-Pic003](Images/v0zbelt_stock1.png)

### V0.2 Compatibility

![ZBelt-Pic004](Images/v0zbelt_kirigami1_v0.2.png)
![ZBelt-Pic005](Images/v0zbelt_kirigami2_v0.2.png)
