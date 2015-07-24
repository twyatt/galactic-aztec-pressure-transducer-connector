# About
[![OSHPark PCB Top Thumbnail](artwork/thumb_top.png?raw=true)](artwork/top.png?raw=true)
[![OSHPark PCB Bottom Thumbnail](artwork/thumb_bottom.png?raw=true)](artwork/bottom.png?raw=true)

Custom board used to convert 3 wire pressure transducer to ethernet plug for the [Galactic Aztec] rocket. The board was designed to interface with the [Galactic Aztec Raspberry Pi Add-on: Pressure Transducer Interface] board.

Custom EagleCAD parts on this board can be found in the [SDSU Rocket Eagle Libraries].

## Wiring
The ethernet port adheres to the following [T-568B] wiring configuration:

| Pin | Color        | Function       |
|:---:|:------------:|:--------------:|
| 1   | Orange/White | Signal         |
| 2   | Orange       | Signal         |
| 3   | Green/White  |                |
| 4   | Blue         | Supply Voltage |
| 5   | Blue/White   | Supply Voltage |
| 6   | Green        |                |
| 7   | Brown/White  | Ground         |
| 8   | Brown        | Ground         |

# Bill of Materials
| Qty | Description                               | Part Number       | Vendor   |
|:---:|-------------------------------------------|------------------:|----------|
| 1   | Jack RJ45 CAT5/CAT5e                      | [380-1046-ND]     | DigiKey  |


[Galactic Aztec]: http://rocket.sdsu.edu/rockets
[Galactic Aztec Raspberry Pi Add-on: Pressure Transducer Interface]: https://github.com/twyatt/galactic-aztec-rpi-addon-pressure
[SDSU Rocket Eagle Libraries]: https://github.com/twyatt/SDSURocket-Eagle-Libraries
[T-568B]: https://en.wikipedia.org/wiki/TIA/EIA-568#Wiring
[380-1046-ND]: http://www.digikey.com/product-detail/en/SS-7188-NF/380-1046-ND/388308