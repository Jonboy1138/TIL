# Get A List Of Subfolders One Level Deep

```powershell
Get-ChildItem -Path C:\Shared\Member\RETAIL\ACTIVE -Depth 1 -Directory | Select-Object Parent, Name | Export-Csv -Path C:\temp\Subfolders.csv
```