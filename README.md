# sysmon

Installing sysmon on Windows

1. Download sysmon (or entire Sysinternals suite)
2. Download configuration
3. Save as config.xml in C:\Windows
4. Install by opening a command prompt as administrator and typing:
    sysmon64.exe -accepteula -i c:\Windows\config.xml

Note: sysmon.exe is for 32-bit systems, sysmon64.exe is for 64-bit systems
