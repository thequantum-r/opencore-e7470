# Dell Latitude E7470 OpenCore Configuration

This repository contains the OpenCore configuration files for the Dell Latitude E7470 laptop. OpenCore is a clean, versatile bootloader that can be used to create a hackintosh or dual-boot system. This configuration is for MacOS Sequoia.

## What Works

- CPU Power Management
- GPU Acceleration
- Audio
- Ethernet
- Wi-Fi
- Trackpad (with gestures)
- Keyboard (including function keys)
- Battery status
- Sleep/Wake
- HDMI output

## What Doesn't Work

- SD Card Reader
- Power Plug/Unplug Freezing
- Brightness Control
- Bluetooth
- USB (Not patched properly

## Installation

1. Create a bootable USB drive with macOS
2. Clone this repository
3. Copy the EFI folder to your USB drive's EFI partition
4. Boot from the USB drive and install macOS
5. After installation, copy the EFI folder to your system drive's EFI partition

## Post-Installation

- Generate your own SMBIOS information using GenSMBIOS
- Update kexts and OpenCore as new versions become available

## Troubleshooting

If you encounter any issues, please check the following:

1. Ensure you're using the latest version of OpenCore
2. Verify that your BIOS settings match the recommended configuration
3. Check if your hardware matches the specifications listed above

If problems persist, please open an issue in this repository with detailed information about your setup and the problem you're experiencing.

## Contributing

Contributions are welcome! If you have any improvements or fixes, please submit a pull request.

## Disclaimer

This configuration is provided as-is, without any warranty. Use at your own risk. Always back up your important data before making system changes.

## Credits

- [Acidanthera](https://github.com/acidanthera) for OpenCore and many kexts
- [RehabMan](https://github.com/RehabMan) for guides and kexts
- The hackintosh community for their invaluable resources and support

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
