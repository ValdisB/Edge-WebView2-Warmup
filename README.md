# Edge WebView2 Warmup
Version: 1.0.0  
Author: Valdis B.
License: Freeware / Portable  
Platform: Windows 10 / Windows 11 (PowerShell 5+)

## Overview
Edge WebView2 Launcher is a small, portable PowerShell utility that finds and launches the newest installed version of Microsoft Edge WebView2.
It works as a lightweight WebView2 warm‑up tool, initializing the runtime early during system startup.

When added to Windows Startup or Task Scheduler, it improves the initial responsiveness of Microsoft Edge and other WebView2‑based applications.

## Features
- Detects the newest WebView2 runtime version
- Automatically locates msedgewebview2.exe
- Launches WebView2 directly
- Clear status messages
- Safe to run from file or copy/paste
- No installation, no configuration files, no system changes

## Requirements
- Windows 10 or Windows 11  
- PowerShell 5.0 or newer  
- WebView2 Runtime installed (default on modern Windows)

## How to Use
1. Save the script as a `.ps1` file  
2. Run it with PowerShell  
3. The tool will:
   - Search for the newest WebView2 version
   - Locate msedgewebview2.exe
   - Launch it
4. Press ENTER to exit

## Notes
- No administrator rights required  
- No internet access required  
- No files are created or modified  
- Fully portable and transparent

## Changelog
### 1.0.0
- Initial release
