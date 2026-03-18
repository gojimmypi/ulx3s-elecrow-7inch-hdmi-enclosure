# New 3D Printable ULX3S Enclosure for the Elecrow 7 inch HDMI Display

The ULX3S community continues to build amazing projects ranging from retrocomputers to FPGA graphics demos. A new open source, 3D printable enclosure now makes it easy to combine the ULX3S with a 7 inch HDMI display to create a compact, portable FPGA workstation.

For a great overview of what people are building, see the extensive collection of examples at:

https://ulx3s.github.io/

One common request has been a clean way to combine the ULX3S with a display for portable demos and development. Community member gojimmypi has designed an open source, 3D printable enclosure that integrates the ULX3S with a popular 7 inch HDMI display.

An open source enclosure design is now available here:

https://github.com/gojimmypi/ulx3s-elecrow-7inch-hdmi-enclosure

## A Portable FPGA Workstation

The enclosure turns the ULX3S into a compact FPGA workstation by combining:

- ULX3S FPGA + ESP32 board
- Elecrow 7 inch HDMI display
- External buttons and controls
- Accessible development interfaces

The result is a portable system that is well suited for demonstrations, classroom environments, and FPGA development setups where a separate monitor is not convenient.

## Designed for Development

A key goal of the enclosure is to keep the ULX3S fully usable while mounted inside. Important interfaces remain accessible so developers can continue experimenting without removing the board.

Features include:

- External buttons for ULX3S controls
  (Power, F1, F2, Left, Right, Up, Down)

- Light pipe mounts for FPGA status LEDs
  (D0 through D7, TXLED, WiFi, and power)

- External access to important headers
  - J1 and J2 GPIO headers
  - J3 ESP32 control pins
  - J4 JTAG programming header
  - J5 power rails

- Access to display brightness and volume controls

- External audio jack routing

This allows you to program, debug, and interact with FPGA projects without opening the enclosure.

## Built Around the Elecrow 7 inch HDMI Display

The enclosure is designed around the widely available Elecrow 7 inch 1024x600 IPS HDMI display. Although originally designed for Raspberry Pi systems, it works well with the ULX3S when using the board GPDI HDMI interface and appropriate FPGA HDL.

This combination creates a convenient platform for projects such as:

- FPGA graphics demos
- retrocomputer cores
- FPGA user interfaces
- educational FPGA experiments

## Designed for Makers

The enclosure was designed in Autodesk Fusion and optimized for 3D printing on a Prusa MK3S using PETG filament.

The design includes several practical details:

- Internal routing for USB and HDMI cables
- Adjustable display mounting brackets
- Ventilation openings for airflow
- Optional internal 25 mm cooling fan mount

Optional features allow the enclosure to be customized for different setups:

- OLED status display mount
- Desktop stand configuration
- Horizontal development feet
- Wall mount keyhole
- Internal cable strain relief

## Open Source Hardware

The enclosure design is released under the Creative Commons BY-NC-SA 4.0 license, allowing the community to:

- print the enclosure
- modify the design
- share improvements

Commercial licensing is also available from the author.

## Continuing Progress

Development continues across the ULX ecosystem.

Work is progressing on the upcoming campaigns for:

- ULX4M
  https://www.crowdsupply.com/intergalaktik/ulx4m

- ULX5M, recently presented at CERN
  https://radiona.org/fpga-ulx5m-presented-cern/

ULX3S boards remain available from:

- Crowd Supply
  https://www.crowdsupply.com/radiona/ulx3s

- Mouser Electronics
  https://www.mouser.com/c/?q=ulx3s

We are excited to see how the community continues to build new projects and tools around the ULX platform.