# Marlin configuration files for the BIGTREETECH SKR Mini E3 v2.0 with BLTouch

This Marlin configuration is intended for use with the following hardware:

* Creality Ender 3
* BIGTREETECH SKR Mini E3 V2.0 control board
* BLTouch 2.0 attached to the Z-Probe header (NOT the Z-Stop header)

The probe offsets are configured for [this BLTouch mount](https://www.thingiverse.com/thing:3003725).
While the default offsets work fine for my unit, you may need to tweak
`NOZZLE_TO_PROBE_OFFSET` to get it to work with your printer.

This configuration should be similar to the `firmware-bltouch.bin` image
provided by BIGTREETECH in [their own repo](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/tree/master/firmware/V2.0).
