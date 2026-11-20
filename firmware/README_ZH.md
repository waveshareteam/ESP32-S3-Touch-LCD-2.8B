# ESP32-S3-LCD-2.8B 和 ESP32-S3-Touch-LCD-2.8B 出厂固件

请按实物型号选择固件。

| 文件 | 适用型号 | 版本日期 | 烧录偏移 |
| --- | --- | --- | --- |
| [ESP32-S3-LCD-2.8B_FactoryOnly_20250124.bin](ESP32-S3-LCD-2.8B_FactoryOnly_20250124.bin) | ESP32-S3-LCD-2.8B (无触摸) | 2025-01-24 | `0x0` |
| [ESP32-S3-Touch-LCD-2.8B_FactoryOnly_20241025.bin](ESP32-S3-Touch-LCD-2.8B_FactoryOnly_20241025.bin) | ESP32-S3-Touch-LCD-2.8B (带触摸) | 2024-10-25 | `0x0` |

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-LCD-2.8B_FactoryOnly_20250124.bin
```

```sh
esptool --chip esp32s3 write-flash 0x0 ESP32-S3-Touch-LCD-2.8B_FactoryOnly_20241025.bin
```
