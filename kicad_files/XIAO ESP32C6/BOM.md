## BOM

The same data is in [BOM.csv](BOM.csv), which can be uploaded to Digi-Key's BOM Manager. The symbols in the schematic also carry `Manufacturer`, `MPN` and `Digi-Key PN` fields.

### Board

|Ref|Qty|Value|Description|Package|Manufacturer|MPN|Digi-Key|
|-|-|-|-|-|-|-|-|
|U1|1|XIAO ESP32C6|ESP32-C6 module, standard (not pre-soldered) version|XIAO castellated SMD|Seeed Technology|113991254|[1597-113991254-ND](https://www.digikey.com/en/products/result?keywords=1597-113991254-ND)|
|J1|1|250-1402|PCB terminal block, push-button, 2-pole (RED, WHITE)|THT, 2.54 mm|WAGO|250-1402|[2946-250-1402-ND](https://www.digikey.com/en/products/result?keywords=2946-250-1402-ND)|
|D1|1|CDSOD323-T15S|TVS diode, unidirectional, 15 V standoff (cathode to RED)|SOD-323|Bourns|CDSOD323-T15S|[CDSOD323-T15SCT-ND](https://www.digikey.com/en/products/result?keywords=CDSOD323-T15SCT-ND)|
|Q1|1|2N7002|N-ch MOSFET 60 V, RX level shifter. Needs a ±20 V gate rating, so do not substitute AO3400A|SOT-23|onsemi|2N7002|[2N7002NCT-ND](https://www.digikey.com/en/products/result?keywords=2N7002NCT-ND)|
|Q2|1|AO3400A|N-ch MOSFET 30 V, open-drain TX driver|SOT-23|Alpha & Omega|AO3400A|[785-1000-1-ND](https://www.digikey.com/en/products/result?keywords=785-1000-1-ND)|
|R1|1|4.7k|TX gate pulldown|0805|Panasonic|ERA-6AEB472V|[P4.7KDACT-ND](https://www.digikey.com/en/products/result?keywords=P4.7KDACT-ND)|
|R2|1|1k|Q2 gate series resistor|0805|Panasonic|ERA-6AEB102V|[P1.0KDACT-ND](https://www.digikey.com/en/products/result?keywords=P1.0KDACT-ND)|
|R3, R5|2|10k|Q1 gate series resistor / RX pull-up|0805|Panasonic|ERA-6AED103V|[P123794CT-ND](https://www.digikey.com/en/products/result?keywords=P123794CT-ND)|
|R4|1|100k|RED line bias|0805|Panasonic|ERA-6AEB104V|[P100KDACT-ND](https://www.digikey.com/en/products/result?keywords=P100KDACT-ND)|

The resistors are thin-film 0.1% / 0.5% parts. That is more precision than the circuit needs, but in single quantities they cost about the same as basic 1% parts, so any 0805 resistor of the same value will do.

### Mounting hardware

|Ref|Qty|Part|Manufacturer|MPN|Source|
|-|-|-|-|-|-|
|H1|1|#6-32 × 1" nylon pan head Phillips machine screw (6.68 mm head), through the 4.0 mm hole|Essentra Components|010632PW100|Digi-Key [RPC7858-ND](https://www.digikey.com/en/products/result?keywords=RPC7858-ND)|
|-|1|SnapSkru SPM Mini self-drilling drywall anchor (3/8"–5/8" drywall, #6–#8 screws)|TOGGLER|SnapSkru SPM Mini|Hardware stores; not stocked by Digi-Key|

The anchor is designed for coarse #6–#8 screws. A fine-thread #6-32 screw still bites into it, but it will hold less than the anchor's rated load. That is plenty for a board this light.
