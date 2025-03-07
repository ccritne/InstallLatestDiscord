# Discord Installer Script for Linux

## Overview
This script downloads and installs the latest stable version of Discord on a Linux system. It extracts the downloaded archive, moves the necessary files to the appropriate locations, and creates symbolic links for easy access.

## Prerequisites
- A Linux distribution with `wget`, `tar`, and `sudo` installed.
- User privileges to execute commands with `sudo`.

## Installation Steps

1. Run the script:
   ```bash
   ./src/install.sh
   ```

## What the Script Does
1. Downloads the latest stable version of Discord for Linux as a tar.gz archive.
2. Extracts the archive to the `/usr/share` directory.
3. Removes the downloaded archive to free up space.
4. Creates a symbolic link to the Discord binary in `/usr/bin` for easy execution.
5. Copies the Discord `.desktop` file to `/usr/share/applications` to integrate Discord into the system’s application menu.

## Running Discord
Once installed, you can launch Discord using:
```bash
Discord
```
Alternatively, you can open it from the application menu.

## Uninstallation
To remove Discord from your system, run:
```bash
./src/uninstall.sh
```

## Notes
- Ensure you have an active internet connection while running the script.
- If you encounter any permission issues, run the script with `sudo`.

Enjoy using Discord on your Linux system!