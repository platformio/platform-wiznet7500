# WIZNet W7500: development platform for [PlatformIO](http://platformio.org)
[![Build Status](https://travis-ci.org/platformio/platform-wiznet7500.svg?branch=develop)](https://travis-ci.org/platformio/platform-wiznet7500)
[![Build status](https://ci.appveyor.com/api/projects/status/mnouny09l75fc06u/branch/develop?svg=true)](https://ci.appveyor.com/project/ivankravets/platform-wiznet7500/branch/develop)

The IOP (Internet Offload Processor) W7500 is the one-chip solution which integrates an ARM Cortex-M0, 128KB Flash and hardwired TCP/IP core for various embedded application platform especially requiring Internet of things

* [Home](http://platformio.org/platforms/wiznet7500) (home page in PlatformIO Platform Registry)
* [Documentation](http://docs.platformio.org/page/platforms/wiznet7500.html) (advanced usage, packages, boards, frameworks, etc.)

# Usage

1. [Install PlatformIO](http://platformio.org)
2. Create PlatformIO project and configure a platform option in [platformio.ini](http://docs.platformio.org/page/projectconf.html) file:

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

Please navigate to [documentation](http://docs.platformio.org/page/platforms/wiznet7500.html).
