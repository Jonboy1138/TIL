# Get A List Of Subfolders One Level Deep

```powershell
Get-ChildItem .\*\* | Select-Object FullName | Export-Csv -Path C:\temp\Subfolders.csv
```