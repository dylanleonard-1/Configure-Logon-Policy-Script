# Configure Logon Policy Script

This PowerShell script configures the "Interactive logon: Message title for users attempting to log on" and "Interactive logon: Message text for users attempting to log on" policies on Windows systems.

## Features
- Sets the logon banner title.
- Configures a detailed warning statement.
- Updates policies immediately.

## Prerequisites
- Administrator privileges on the target system.
- PowerShell execution policy set to allow script execution (`Set-ExecutionPolicy Bypass -Scope Process`).

## How to Use
1. Download the script: `ConfigureLogonPolicy.ps1`.
2. Open PowerShell as Administrator.
3. Run the script:
   ```powershell
   .\ConfigureLogonPolicy.ps1


 -ConfigureLogonPolicy.ps1m "https://github.com/dylanleonard-1/dylanleonard-1/blob/main/ConfigureLogonPolicy.ps1"


