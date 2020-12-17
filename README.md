# ThinkPad E490 Hackintosh

macOS Catalina with OpenCore on ThinkPad E490 (Hackintosh).

## Disclaimer

Your warranty is now void. Please do some research if you have any concerns before replacing your EFI with mine. I am not responsible for any loss, including but not limited to Kernel Panic, device fail to boot or can not function normally, storage damage or data loss, atomic bombing, World War III, The CK-Class Restructuring Scenario that SCP Foundation can not prevent, and so on.

## Devices

| Specifications | Details |
|:---|:---|
| Computer Model | ThinkPad E490 (2019) |
| CPU | Intel Core i7-8565U (Whiskey Lake) |
| Memory | DDR4 2400 Mhz. 1x16 GiB |
| NVMe SSD | Toshiba M.2 512 GiB |
| SATA SSD | Samsung SATA 480 GiB |
| Integrated Graphics | Intel UHD Graphics 630 |

## What is working

#### CPU

XCPM power management is native supported. HWP is fully enabled as well.

#### Memory

Intel Core i7-8565U supports only 32 GiB RAM (2400Mhz) at most.

#### Battery

The power display is functioning normally.

#### Wi-Fi & Bluetooth

Planing to change wireless card. Currently everything works but Airdrop.

#### Camera

Camera is functioning normally.

#### USB

USB Ports working, USB-c works and external docking station also.

#### Ethernet

Functioning normally.

#### Display

Functioning normally, laptop screen+ 2 external monitors.

#### Audio

Driven by AppleALC. Everything is working normally (including HDMI Audio output).

Built-in mic is functioning.

#### Keyboard

Functioning normally. Keyboard backlight (<kbd>Fn</kbd> + <kbd>Space</kbd>) is working properly as well.

#### SSD

Both NVMe & SATA are functioning normally and TRIM is enabled for both of them.

#### Touchpad & Trackpoint

Functioning normally. Trackpoint (which is my favorite) and UltraNavs are working properly as well, and Multigesture for touchpad is supported.

## What is not working

  Airdrop.
