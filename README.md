System Update Manager

An advanced system update manager for Ubuntu/Debian featuring an interactive menu, multi-package management (APT, Flatpak, Snap), and comprehensive logging.


Features

    Easy-to-use interactive menu
    Supports updating APT, Flatpak, and Snap packages
    Complete system upgrade and cleanup workflow
    System information and package manager detection
    Detailed logging with automatic log rotation
    Colorful and informative output
    Error handling and user guidance

## Installation

    Clone this repository:
    ```bash
git clone https://github.com/Alex-code-sudo/System-Update-Script-Bash.git && cd System-Update-Script-Bash

Usage

    Make the script executable:
    

chmod +x System-Update-Script

Run the script:


    ./System-Update-Script

    Follow the on-screen menu:
        Update package lists
        Upgrade packages
        Clean up system
        Run a complete update workflow
        Update Flatpak or Snap apps
        Show system information
        Exit

    Note:

        The script does not need to be run as root. It will prompt for sudo when necessary.
        Internet connection is required.
        Logs are saved under ~/.update-logs/ and automatically cleaned up after 30 days.

Requirements

    Ubuntu or Debian-based system
    Bash shell
    APT package manager
    (Optional) Flatpak and Snap, if installed

