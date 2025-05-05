# GattClientApp

A .NET MAUI application to connect to an ESP32-S3 GATT server via Bluetooth Low Energy (BLE).

## Features
- Scan for BLE devices with name `ESP_GATTS_DEMO`.
- Connect to the GATT server with service UUID `000000FF-0000-1000-8000-00805F9B34FB`.
- Read/write to characteristic UUID `0000FF01-0000-1000-8000-00805F9B34FB`.
- Receive notifications from the server.

## Requirements
- .NET 8
- Visual Studio 2022 with MAUI workload
- Plugin.BLE NuGet package
- ESP32-S3 with ESP-IDF v5.4.1 (gatt_server example)

## Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/shoderico/GattClientApp.git
1. Open in Visual Studio 2022.
1. Restore NuGet packages.
1. Build and run on Windows (or Android/iOS with appropriate permissions).

## License
MIT License
