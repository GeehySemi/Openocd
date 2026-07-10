# OpenOCD Package

This repository provides a packaged OpenOCD build used with Geehy MCU development and debugging workflows.

## Repository contents

| File | Description |
| --- | --- |
| `openocd-v0.12.0-rc2-i686-w64-mingw32.tar_wkl.zip` | Packaged OpenOCD v0.12.0-rc2 build for 32-bit Windows/MinGW |

## Usage

1. Download and extract the archive.
2. Review the included OpenOCD scripts and configuration files.
3. Select the interface and target configuration that match your debug adapter and MCU.
4. Run OpenOCD from a terminal or configure your IDE to use the extracted executable.

Example command structure:

```sh
openocd -f interface/<interface-config>.cfg -f target/<target-config>.cfg
```

Replace the placeholders with configuration files appropriate for your hardware.

## Notes

- This repository contains a packaged binary distribution rather than the full OpenOCD source tree.
- Verify compatibility with your host system, debug adapter, MCU, and IDE before use.
- For current OpenOCD releases and upstream documentation, refer to the official OpenOCD project.
- For current Geehy device documentation and development resources, visit the [Geehy website](https://www.geehy.com/).

## Support

For Geehy product information and technical support, visit [www.geehy.com](https://www.geehy.com/).
