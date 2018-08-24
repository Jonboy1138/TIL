# Get A List Of Subfolders One Level Deep

```powershell
Get-ChildItem .\*\* | Select-Object Parent, Name | Export-Csv -Path C:\temp\Subfolders.csv
```