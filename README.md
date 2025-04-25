# Plugin Folder Monitor for macOS 🎛️

![Bash](https://img.shields.io/badge/shell_script-%23121011.svg?style=for-the-badge&logo=gnu-bash&logoColor=white)
![macOS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=macos&logoColor=F0F0F0)

A powerful Bash script to monitor, manage, and clean audio plugin folders on macOS. Perfect for music producers, audio engineers, and DAW users!

## Features ✨

- 📊 **Quick overview** of plugin folder sizes and counts
- 🗂️ **Open plugin folders** directly in Finder
- 🧹 **Clean up plugins** by type (VST, VST3, AU, AAX)
- 🎨 **Color-coded output** for better readability
- 🔒 **Safe deletion** with confirmation prompts
- 🖥️ **Optimized for macOS** (handles bundle packages correctly)

## Supported Plugin Formats 🎧

| Format | Default Location | Extension |
|--------|------------------|-----------|
| AU     | `/Library/Audio/Plug-Ins/Components` | `.component` |
| VST    | `/Library/Audio/Plug-Ins/VST` | `.vst` |
| VST3   | `/Library/Audio/Plug-Ins/VST3` | `.vst3` |
| AAX    | `/Library/Application Support/Avid/Audio/Plug-Ins` | `.aaxplugin` |

## Installation ⚡

1. Download the script:
```bash
curl -O https://raw.githubusercontent.com/yourusername/plugin-folder-monitor/main/plugInsFolderMonitor