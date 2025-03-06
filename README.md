# luci-app-qfirehose
![GitHub release (latest by date)](https://img.shields.io/github/v/release/4IceG/luci-app-qfirehose?style=flat-square)
![GitHub stars](https://img.shields.io/github/stars/4IceG/luci-app-qfirehose?style=flat-square)
![GitHub forks](https://img.shields.io/github/forks/4IceG/luci-app-qfirehose?style=flat-square)
![GitHub All Releases](https://img.shields.io/github/downloads/4IceG/luci-app-qfirehose/total)

My package is fork from https://github.com/ntbowen/luci-app-qfirehose (I made minor corrections, visual changes and added a Polish translation).

#### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="24"> A LuCI web interface for QFirehose, providing a user-friendly way to flash Quectel firmware on OpenWrt devices.

#### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="24"> Interfejs LuCI dla QFirehose, zapewnia przyjazny użytkownikowi sposób wgrywania firmware Quectel-a na urządzeniach z OpenWrt.

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


## Usage

1. Access your OpenWrt LuCI web interface
2. Navigate to Modem -> QFirehose
3. Select your firmware file
4. Choose the appropriate USB port and device
5. Click "Flash" to start the firmware flashing process
6. Monitor the progress through the log window

### <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="32"> Preview / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="32"> Podgląd

![](https://github.com/4IceG/Personal_data/blob/master/zrzuty/luci-app-qfirehose.png?raw=true)


## <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_United_Kingdom.png" height="32"> Thanks to / <img src="https://raw.githubusercontent.com/4IceG/Personal_data/master/dooffy_design_icons_EU_flags_Poland.png" height="32"> Podziękowania dla
- [Zag](https://github.com/ntbowen)


