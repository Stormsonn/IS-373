# Step-by-Step WSL 2 Installation
## 1. Check System Requirements
Windows Version: Windows 10 (version 1903, build 18362 or higher) or Windows 11.
64-bit architecture required.
## 2. Enable WSL
Open PowerShell as Administrator.

Right-click Start Menu → Windows PowerShell (Admin).
Run this command to enable WSL:

dism.exe /online /enable-feature /featurename:Microsoft-Windows-Subsystem-Linux /all /norestart
Enable Virtual Machine Platform (required for WSL 2):

dism.exe /online /enable-feature /featurename:VirtualMachinePlatform /all /norestart
Restart your computer.

## 3. Set WSL 2 as Default
Open PowerShell as Administrator again.

Run this command to set WSL 2 as the default:

wsl --set-default-version 2

## 4. Install a Linux Distribution
Open Microsoft Store and search for a Linux distribution (e.g., Ubuntu, Debian).

Click "Get" to install it.

## 5. Initialize the Distribution
Launch the distribution from the Start Menu or Windows search.

Set up a new Linux user account when prompted.

## 6. Confirm WSL Version
Check WSL version for your Linux distribution:

wsl -l -v
If it's using WSL 1, upgrade it to WSL 2:

wsl --set-version <distribution_name> 2
Now you're ready to use WSL 2!
