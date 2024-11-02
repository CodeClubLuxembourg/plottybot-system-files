# PlottyBot System Files

## Overview
The **plottybot-system-files** repository contains essential configuration files and scripts for setting up and running PlottyBot on a Raspberry Pi. These files help manage the boot process, system configurations, and interactions required for seamless operation.

## Included Files
- **/etc/rc.local**: Custom script to start necessary services and daemons on boot.
- **WiFi configuration scripts**: Files for setting up local WiFi networks for PlottyBot.
- **System setup scripts**: Scripts for initial configurations, such as enabling GPIO and SSH.

## Usage
1. Clone this repository to your Raspberry Pi.
2. Copy the files to their respective locations on your Raspberry Pi system.
3. Ensure proper permissions are set for each file, especially scripts that need execution privileges.

## Important Notes
- Always back up existing configuration files before replacing them.
- Some scripts may require adjustments based on your network and system environment.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements
This repository is maintained by Michael Stilmant and Code Club Luxembourg, building on the original work by [Ben Servoz](https://ben.akrin.com/plottybot/).
