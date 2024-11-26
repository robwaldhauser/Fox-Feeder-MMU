# Fox Feeder MMU 🦊

The FoxFeeder MMU is a low-cost, easy-to-build multi-material unit (MMU) designed to bring advanced multi-material printing capabilities to any 3D printer running Klipper. Inspired by the functionality of the BambuLab AMS, the FoxFeeder MMU is a lightweight low-cost solution that pairs seamlessly with the FriendlyFox macro package and the innovative Slacker sensor for precise filament tracking.
![Fox Feeder v138](https://github.com/user-attachments/assets/7b04603d-1f6c-49b7-b1f9-f125c56ca63e)
If you like this project, consider [tipping](https://www.Ko-fi.com/robxberty)!

## Features ✨

- Affordable: Designed with cost-effective components, making multi-material printing accessible.
- Customizable Lanes: Choose between 2-lane or 4-lane configurations to suit your needs (additional lanes may be supported in the future)
- Slacker Sensor Integration: Utilizes the Slacker Sensor for real-time monitoring of filament slack and tension through the Bowden tube, ensuring consistent filament flow.
- Seamless Integration: Built to work flawlessly with the FriendlyFox macro package. One .cfg to add and that's it, no plugins needed!
- Ease of Assembly: A straightforward assembly process suitable for hobbyists and newcomers alike.

## Table of Contents 📖

- Introduction
- [Features](https://github.com/robwaldhauser/Fox-Feeder-MMU#features-)
- [Requirements](https://github.com/robwaldhauser/Fox-Feeder-MMU#requirements-)
- [Assembly Instructions](https://github.com/robwaldhauser/Fox-Feeder-MMU#assembly-instructions-)
- [Configuration](https://github.com/robwaldhauser/Fox-Feeder-MMU#configuration-)
- [Usage](https://github.com/robwaldhauser/Fox-Feeder-MMU#usage-)
- [Roadmap](https://github.com/robwaldhauser/Fox-Feeder-MMU#roadmap-)
- [Contributing](https://github.com/robwaldhauser/Fox-Feeder-MMU#contributing-)
- [License](https://github.com/robwaldhauser/Fox-Feeder-MMU#license-)

## Requirements 🛠️

- A 3D printer with Bowden setup or compatible extruder system.
- A set of printed components for the FoxFeeder (STL files available in the STLs directory).
- Hardware kit (refer to the Bill of Materials).
- Slacker Sensor for filament slack detection (available from the Slacker repository).
- FriendlyFox Macro Package (available from the FriendlyFox repository).

## Printing Instructions

- Designed to follow Voron printing standards. General rule is 0.4mm line widths, 4 walls, 5 tops and bottoms, and 40% infill. Adjust at your own risk.
- All items with an [a] prefix are intended to be your accent color
- All items with a [s] prefix are best to be printed in a [s]oft but not too [s]quishy filament to keep things [s]ilent. This can be a medium to hard tpu.
- All items that need supports, have them built in.
- The Roller Clutch Inner parts are designed to have an overhang for the pinwheels. You will want to gently free them up after printing but before assembly.

## Assembly Instructions 🔧

- Assemble your frame using Corner Cubes. The center cross bar will need to have a 31mm gap between it and the front extrusion. The tapered corners of the Corner Cubes will face up and outward.
- Feet and Skirts assemble exactly like a Voron 0.
- **more instructions to come, this is currently being updated**

## Configuration ⚙️

To integrate the FoxFeeder MMU with your printer and firmware:

- Install the FriendlyFox Macro Package, simply copy the FriendlyFox.cfg file into your Klipper instance. Be sure to include it in your printer.cfg
- Configure your slicer to define the number of active lanes.
- Update your printer's Klipper configuration with the provided example configurations in configs/.

## Usage 🚀

Once set up, the FoxFeeder MMU will:

- Detect and manage filament slack using the Slacker Sensor.
- Switch lanes seamlessly during multi-material prints.
- Operate efficiently and reliably under the control of the FriendlyFox macros.

Refer to the Usage Guide for detailed instructions.

## Roadmap 🛣️

- Add support for more lanes (e.g., 6-lane or 8-lane configurations).
- Improve documentation and troubleshooting guides.
- Create community challenges and showcases.

## Contributing 🤝

Contributions are welcome! Feel free to submit issues, feature requests, and pull requests. Check the Contributing Guide for more details.
Please also consider [tipping](https://www.Ko-fi.com/robxberty) to help with further development!

## License 📄

This project is licensed under the MIT License.

## Join the FoxFeeder revolution and unleash the power of multi-material printing without breaking the bank! 🦊
