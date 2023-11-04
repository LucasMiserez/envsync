# Env Sync

## Overview
This repository provides two essential scripts for exporting and syncing Conda environments. These scripts are designed to streamline the process of managing Conda environments on the same operating system.

## Scripts
1. **export.sh**: Running this script in your Conda environment will generate an `env.yml` file, capturing the current environment's configuration.

2. **sync.sh**: Use this script to synchronize an environment with the configuration specified in the `env.yml` file. This is particularly useful for managing Pip packages.

## Compatibility
Please note that this tool is intended for use within the same operating system family. It supports synchronization between environments on the following platforms:
- Windows-to-Windows
- Linux-to-Linux
- Mac-to-Mac

However, it does not support cross-platform synchronization, such as Linux to Windows.

Enjoy the convenience of seamless Conda environment management with these simple and efficient scripts!
