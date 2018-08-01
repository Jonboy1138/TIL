# Get serial number from remote machine

```powershell
Get-CimInstance -classname win32_bios -computername Computername | format-list serialnumber
```