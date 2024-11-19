# Fox Feeder MMU 🦊

The FoxFeeder MMU is a low-cost, easy-to-build multi-material unit (MMU) designed to bring advanced multi-material printing capabilities to any 3D printer running Klipper. Inspired by the functionality of the BambuLab AMS, the FoxFeeder MMU is a lightweight low-cost solution that pairs seamlessly with the FriendlyFox macro package and the innovative Slacker sensor for precise filament tracking.
![Fox Feeder v138](https://github.com/user-attachments/assets/1d6406db-5877-4e9a-9a66-8f6efe0a0a85)
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

## Assembly Instructions 🔧

- Print the Components
  Download the STL files and print them with your preferred settings.
- Prepare the Hardware
  Gather the required hardware components listed in the Bill of Materials.
- Assemble the FoxFeeder
  Follow the detailed step-by-step instructions in the Assembly Guide (still to come).

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
