Lightcord-Stereo Discord Stereo Enabler
====================================

Lightcord-Stereo is a tool designed to enable stereo sound on Discord. It automatically modifies Discord's configuration to ensure stereo functionality is enabled, providing a better audio experience for users.

Features
========
- Enables stereo sound on Discord automatically.
- Closes Discord (if running) to ensure successful configuration.
- Logs the entire process for troubleshooting and confirmation.

Requirements
============
- Windows OS
- Discord installed
- Administrative privileges may be required to close Discord or modify files in system directories.

Usage
=====
1. Download the EXE
   ------------------
   Download the compiled `.exe` file (`Lightcord-Stereo.exe`) from the repository or source.

2. Run the EXE
   ------------
   - Double-click the `Lightcord-Stereo.exe` file to run it.
   - The tool will check if Discord is running. If it is, Discord will be closed automatically to allow for the configuration change.
   - The tool will modify the necessary Discord settings to enable stereo sound.
   - A log file will be created in the `logs` directory, containing detailed information about the process and any errors encountered.

3. Restart Discord
   ----------------
   Once the process is complete, you can restart Discord. Stereo sound should now be enabled and working.

Troubleshooting
===============
- **No Internet Connection**: If the tool cannot detect an active internet connection, it will terminate the process and prompt you to check your network settings.
- **Discord Not Running**: If Discord is not running, the tool will proceed with the modification process without closing Discord.
- **Error in Process**: If any issues arise during the process, detailed error messages will be logged in the `logs/update_log.txt` file for further diagnosis.

License
=======
This project is licensed under the MIT License.
