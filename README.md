
# XMRig - High Performance CPU/GPU Miner

![XMRig](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS%20%7C%20FreeBSD-blue?style=for-the-badge)
![XMRig](https://img.shields.io/badge/supports-CPU%20%7C%20GPU-orange?style=for-the-badge)
![XMRig](https://img.shields.io/badge/algorithms-RandomX%20%7C%20KawPow%20%7C%20CryptoNight%20%7C%20GhostRider-yellow?style=for-the-badge)
![XMRig](https://img.shields.io/github/release/tomobrynn3/XMRig?style=for-the-badge)
![XMRig](https://img.shields.io/github/license/tomobrynn3/XMRig?style=for-the-badge)
![XMRig](https://img.shields.io/badge/open_source-yes-brightgreen?style=for-the-badge)
![XMRig](https://img.shields.io/badge/build-passing-success?style=for-the-badge)

XMRig is an ultra-efficient, open-source miner designed for high-performance CPU and GPU mining. It supports a wide range of algorithms, including **RandomX**, **KawPow**, **CryptoNight**, and **GhostRider**. Built to be cross-platform, XMRig runs on **Windows**, **Linux**, **macOS**, and **FreeBSD**, making it the ideal choice for anyone looking to maximize their mining potential. Whether you're a beginner or a seasoned miner, XMRig provides the tools and flexibility you need to get started with ease.

## Features and Key Advantages

XMRig is designed for both novice users and experts. Here's a breakdown of its features:

| **Feature**                    | **Description**                                                                                           |
|---------------------------------|-----------------------------------------------------------------------------------------------------------|
| **Cross-Platform Support**      | Works seamlessly on Windows, Linux, macOS, and FreeBSD.                                                    |
| **Unified Miner**               | Mine using both CPU and GPU with a single application.                                                     |
| **High Efficiency**             | Optimized for maximum performance on both CPU and GPU, ensuring you get the most out of your hardware.      |
| **Multiple Algorithm Support**  | Supports RandomX, KawPow, CryptoNight, and GhostRider algorithms.                                          |
| **CPU Mining**                  | Full support for x86, x64, ARMv7, and ARMv8 architectures, providing efficient mining on various processors. |
| **GPU Mining**                  | OpenCL support for AMD GPUs and CUDA support for NVIDIA GPUs for an enhanced mining experience.             |
| **Real-Time Configuration**     | Adjust settings on the fly using a JSON config file or HTTP API without restarting the miner.               |
| **User-Friendly Setup**         | Configure your miner quickly with a web-based wizard for beginners or modify it for more advanced setups.   |
| **Remote Monitoring**           | Use the HTTP API to monitor and manage miners remotely in real time.                                        |
| **Open Source & Free**          | XMRig is released under the MIT License, making it free to use, modify, and distribute.                    |

## Supported Mining Backends

- **CPU Mining**: Fully compatible with x86, x64, ARMv7, and ARMv8 CPUs.
- **GPU Mining**: Supports OpenCL for AMD GPUs and CUDA for NVIDIA GPUs. You can also use the CUDA plugin for further performance optimization.
- **External Plugins**: Leverage additional plugins for enhanced performance or compatibility with specific hardware.

## Installation and Setup

1. **Download Binary Releases**: The easiest method to get started is by downloading the latest precompiled binaries for your platform. Binaries are available for Windows, Linux, macOS, and FreeBSD.
2. **Build from Source**: If you prefer to compile XMRig yourself or need custom configurations, follow the detailed instructions in the build documentation.

## Downloads

| Platform        | Download Link                                                                                      | Version    |
|-----------------|---------------------------------------------------------------------------------------------------|------------|
| Windows         | [XMRig Windows](https://github.com/tomobrynn3/XMRig/releases/download/vX.X.X/xmrig-vX.X.X-win64.zip) | Latest     |
| Linux           | [XMRig Linux](https://github.com/tomobrynn3/XMRig/releases/download/vX.X.X/xmrig-vX.X.X-linux-x64.tar.gz) | Latest     |
| macOS           | [XMRig macOS](https://github.com/tomobrynn3/XMRig/releases/download/vX.X.X/xmrig-vX.X.X-osx.tar.gz) | Latest     |
| FreeBSD         | [XMRig FreeBSD](https://github.com/tomobrynn3/XMRig/releases/download/vX.X.X/xmrig-vX.X.X-freebsd.tar.gz) | Latest     |

### Step-by-Step Setup

1. **Download the Latest Release**: Head to the [Releases section](https://github.com/tomobrynn3/XMRig/releases) to download the latest precompiled binary for your operating system.
2. **Use the Web Wizard**: If you're new to mining or need a quick configuration, the [XMRig Wizard](https://xmrig.com/wizard) is a simple web tool that generates the initial configuration file.
3. **Edit the Config File**: Modify the config.json file to fine-tune your mining settings, such as pool information, algorithm selection, and hardware optimizations.
4. **Launch the Miner**: Run the miner with your configured settings to start mining.

## API & Real-Time Monitoring

XMRig includes a powerful **HTTP API** that allows for real-time monitoring and remote management of your miners. Through this API, you can track performance metrics, change configurations, and even pause or stop mining operations as needed.

**Key Features of the API**:
- **Hashrate Monitoring**: Track the current hashrate of your miner and see performance metrics in real-time.
- **Config Adjustments**: Change mining settings without needing to restart the miner by sending API requests.
- **Worker Management**: Manage multiple mining workers and pools through the API interface.

## Why Choose XMRig?

XMRig is designed with one goal in mind: maximizing your mining efficiency. Whether you're using a powerful GPU or a multi-core CPU, XMRig ensures that you can get the most out of your hardware. Here’s why it stands out:

- **Optimized for Performance**: XMRig is tuned for both high hashrate and low system resource usage, giving you the best of both worlds.
- **Versatile Algorithm Support**: XMRig supports several popular mining algorithms, so you can mine the cryptocurrency of your choice.
- **User-Friendly**: With an intuitive configuration system, a web wizard, and a real-time monitoring API, XMRig is perfect for both beginners and advanced users.
- **Open Source**: As an open-source project, you have full control over the software and can contribute to its improvement.

## License

XMRig is open-source software released under the **MIT License**. You are free to use, modify, and distribute the software as per the terms of this license.

## Conclusion

XMRig provides a robust, flexible, and high-performance mining solution for both novice and expert users. With cross-platform support, high algorithm efficiency, and a wide range of configuration options, it is the go-to choice for anyone looking to maximize their mining operations.

Feel free to reach out to the community or consult the documentation if you need any assistance.
