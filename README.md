Current working XML files

FOR DEVICE

Download latest device baseline XML from this repo (Device_Baseline_20204027.xml)
Download New-AOVPNDeviceConnection.ps1
Download the PSTools suite from https://docs.microsoft.com/en-us/sysinternals/downloads/pstools 
Open an elevated command prompt
Run the following command: psexec -s -i powershell.exe
Run Set-ExectutionPolicy Bypass
Change directory to where you downloaded the PS1 and XML
Run .\New-AOVPNDeviceConnection.ps1 .\Device_Baseline_XXXXXXXX.xml DEVICE (XXXXXXX is the date of the latest baseline and DEVICE is the name of the machine tunnel)
