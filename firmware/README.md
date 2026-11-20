# ESP32-S3-LCD-2.8B and ESP32-S3-Touch-LCD-2.8B factory firmware

Select the firmware for your board model.

| File | Board model | Version date | Flash offset |
| --- | --- | --- | --- |
| [ESP32-S3-LCD-2.8B_FactoryOnly_20250124.bin](ESP32-S3-LCD-2.8B_FactoryOnly_20250124.bin) | ESP32-S3-LCD-2.8B (non-touch) | 2025-01-24 | `0x0` |
| [ESP32-S3-Touch-LCD-2.8B_FactoryOnly_20241025.bin](ESP32-S3-Touch-LCD-2.8B_FactoryOnly_20241025.bin) | ESP32-S3-Touch-LCD-2.8B (touch) | 2024-10-25 | `0x0` |

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-LCD-2.8B_FactoryOnly_20250124.bin
```

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-Touch-LCD-2.8B_FactoryOnly_20241025.bin
```
