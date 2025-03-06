# LuCI QFirehose Application

A LuCI web interface for QFirehose, providing a user-friendly way to flash Qualcomm firmware on OpenWrt devices.

## Features

- Easy-to-use web interface for firmware flashing
- Automatic USB device detection
- Real-time log monitoring
- Support for multiple USB ports and devices
- Progress tracking during firmware flashing
- Automatic completion detection

## Dependencies

This package requires the following packages to be installed:
- luci-base
- qfirehose
- unzip
- kmod-usbmon
- debugfs
- luci-compat

## Installation

1. Add this repository to your OpenWrt build system
2. Build the package:
```bash
make package/luci-app-qfirehose/compile V=s
```

3. Install the generated package on your OpenWrt device:
```bash
opkg install luci-app-qfirehose_1.0.0_all.ipk
```

## Usage

1. Access your OpenWrt LuCI web interface
2. Navigate to Modem -> QFirehose
3. Select your firmware file
4. Choose the appropriate USB port and device
5. Click "Flash" to start the firmware flashing process
6. Monitor the progress through the log window


https://github.com/user-attachments/assets/2a606b19-6bcb-4328-9aaa-3905fee269a2


## License

This project is licensed under the GPLv3 License - see the LICENSE file for details.

## Author

- Zag (ntbowen2001@gmail.com)
- Homepage: https://pcat.qsim.top

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
