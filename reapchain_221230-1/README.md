# Reapchain Network 

## Overview

Currently, the **Reapchain Network** is on [Version 3.1](https://github.com/reapchain/mainnet/tree/main/reapchain_221230-1/v3.1) with **Reapchain Binary** [Version 0.8.9](https://github.com/reapchain/reapchain/releases/tag/v0.8.9).

## Upgrades

| Version | Repository Link                                              | Upgrade Period                    |
|---------|--------------------------------------------------------------|-----------------------------------|
| **v3.1**    | [reapchain/mainnet/v3.1](https://github.com/reapchain/mainnet/tree/main/reapchain_221230-1/v3.1) | `23/01/2024` -> `Current`          |
| **v3.0**    | [reapchain/mainnet/v3.0](https://github.com/reapchain/mainnet/tree/main/reapchain_221230-1/v3.0) | `27/12/2023` -> `23/01/2024`       |
| **v2.0**    | [reapchain/mainnet/v2.0](https://github.com/reapchain/mainnet/tree/main/reapchain_221230-1/v2.0) | `25/09/2023` -> `27/12/2023`       |
| **v1.0**    | [reapchain/mainnet/v1.0](https://github.com/reapchain/mainnet/tree/main/reapchain_2022-1)         | `30/12/2022` -> `25/09/2023`       |

### Upgrade Notes

When an upgrade height is chosen, the current network's state is exported. This exported state becomes the initial genesis file for the new and upgraded network.

You can find all of the initial genesis files for each version in [reapchain_221230-1](https://github.com/reapchain/mainnet/tree/main/reapchain_221230-1) (`v2.0`, `v3.0`, `v3.1`) and [reapchain_2022-1](https://github.com/reapchain/mainnet/tree/main/reapchain_2022-1) (`v1.0`).

All of the exported genesis files can be found in [past-genesis](https://github.com/reapchain/mainnet/tree/main/past-genesis).
