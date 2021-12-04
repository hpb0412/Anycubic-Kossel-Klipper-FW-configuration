# Anycubic Kossel Klipper FW configuration

This is my attempt to improve the power of my old Anycubic Kossel 3D printer.

Most of configuration is "copy & paste" from multiple reference sources.

## Model

- Anycubic Kossel Linear Plus
- Raspberry Pi 3B
- Octopi 0.18.0 / Octoprint 1.7.2
- Klipper 3D Firmware

## References

- [Official Configuration Sample](https://github.com/Klipper3d/klipper/blob/master/config/printer-anycubic-kossel-plus-2017.cfg)
- <https://www.lpomykal.cz/anycubic-kossel-klipper-configuration/>

## Usage

- Select the configuration file corresponding to the stepper driver
- Use a secure transfer command like `scp` (which is available for most of OS platform nowadays). Otherwise, use any tool you are familiar with to transfer the file to the octopi machine `/home/pi`

```shell
scp printer.cfg pi@octopi.local:/home/pi
```
