# ONiOFF smart switch ESPHome Project template

The ONiOFF smart switch is an ESP8285-based device with Tuya firmware. With a
small bit of soldering, ot can be flashed to ESPHome (or Tasmota or any other
custom firmware).

## Versions

There is a generic switch, a fan, and a light version on the firmware available
for download or web flashing.

[You can use the firmware web flashing tool by clicking here](https://curtistinkers.github.com/esphome-onioff-smart-switch)

## Serial interface pins

With the button closest to you, the pins are as follows, going left to right:

| Pin | Function |
| --- | -------- |
| 1   | 3.3V VCC |
| 2   | RXD      |
| 3   | TXD      |
| 4   | GPIO0    |
| 5   | Reset    |
| 6   | Ground   |

## GPIO

The relay, button, and LED pins are as follows:

| Pin | Function |
| --- | -------- |
| 1   | Blue LED |
| 5   | Button   |
| 12  | Relay    |

## Notes

Additionally, there is a Red LED which turns on when the relay is engaged. It
is hardwired and cannot be controlled in software.
