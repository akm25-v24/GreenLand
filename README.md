# GreenLand

Backup repository for my Voron 2.4 300mm build.

## About

This repository contains the configuration files for my [Voron 2.4](https://vorondesign.com/voron2.4) 300mm CoreXY 3D printer running [Klipper](https://www.klipper3d.org/) firmware.

## Directory Structure

```
├── printer_data/
│   └── config/          # Klipper configuration files
│       ├── printer.cfg  # Main printer configuration
│       ├── mainsail.cfg # Mainsail web interface config
│       └── macros/      # Custom macros
└── README.md
```

## Usage

To restore configuration, copy the contents of `printer_data/config/` to your printer's `~/printer_data/config/` directory.