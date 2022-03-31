# WIZNet W7500: development platform for [PlatformIO](http://platformio.org)

![alt text](https://github.com/platformio/platform-wiznet7500/workflows/Examples/badge.svg "WIZNet W7500 development platform")

The IOP (Internet Offload Processor) W7500 is the one-chip solution which integrates an ARM Cortex-M0, 128KB Flash and hardwired TCP/IP core for various embedded application platform especially requiring Internet of things

* [Home](https://registry.platformio.org/platforms/platformio/wiznet7500) (home page in the PlatformIO Registry)
* [Documentation](https://docs.platformio.org/page/platforms/wiznet7500.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](https://docs.platformio.org/page/projectconf.html) file:

## Stable version

```ini
[env:stable]
platform = wiznet7500
board = ...
...
```

## Development version

```ini
[env:development]
platform = https://github.com/platformio/platform-wiznet7500.git
board = ...
...
```

# Configuration

Please navigate to [documentation](https://docs.platformio.org/page/platforms/wiznet7500.html).
