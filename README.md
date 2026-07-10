# OpenOCD 工具包 / OpenOCD Package

[中文](#中文说明) | [English](#english)

## 中文说明

本仓库提供用于极海 MCU 开发与调试流程的 OpenOCD 工具包。

### 仓库内容

| 文件 | 说明 |
| --- | --- |
| `openocd-v0.12.0-rc2-i686-w64-mingw32.tar_wkl.zip` | 适用于 32 位 Windows/MinGW 环境的 OpenOCD v0.12.0-rc2 工具包 |

### 使用方法

1. 下载并解压压缩包。
2. 检查其中的 OpenOCD 脚本与配置文件。
3. 根据调试器和目标 MCU 选择对应的接口及目标配置。
4. 在终端运行 OpenOCD，或在 IDE 中配置解压后的可执行文件。

命令结构示例：

```sh
openocd -f interface/<interface-config>.cfg -f target/<target-config>.cfg
```

请将占位符替换为适用于实际硬件的配置文件。

### 注意事项

- 本仓库存放的是已打包的二进制工具，并非完整的 OpenOCD 源码。
- 使用前请确认操作系统、调试器、MCU 及 IDE 的兼容性。
- 如需最新 OpenOCD 版本及上游文档，请参考 OpenOCD 官方项目。
- 极海器件资料及开发资源请访问[极海官网](https://www.geehy.com/)。

### 技术支持

产品信息与技术支持请访问：[www.geehy.com](https://www.geehy.com/)。

---

## English

This repository provides a packaged OpenOCD build used with Geehy MCU development and debugging workflows.

### Repository contents

| File | Description |
| --- | --- |
| `openocd-v0.12.0-rc2-i686-w64-mingw32.tar_wkl.zip` | Packaged OpenOCD v0.12.0-rc2 build for 32-bit Windows/MinGW |

### Usage

1. Download and extract the archive.
2. Review the included OpenOCD scripts and configuration files.
3. Select the interface and target configuration that match your debug adapter and MCU.
4. Run OpenOCD from a terminal or configure your IDE to use the extracted executable.

Example command structure:

```sh
openocd -f interface/<interface-config>.cfg -f target/<target-config>.cfg
```

Replace the placeholders with configuration files appropriate for your hardware.

### Notes

- This repository contains a packaged binary distribution rather than the full OpenOCD source tree.
- Verify compatibility with your host system, debug adapter, MCU, and IDE before use.
- For current OpenOCD releases and upstream documentation, refer to the official OpenOCD project.
- For current Geehy device documentation and development resources, visit the [Geehy website](https://www.geehy.com/).

### Support

For Geehy product information and technical support, visit [www.geehy.com](https://www.geehy.com/).
