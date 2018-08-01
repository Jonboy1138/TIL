# Get AD Group Members

```powershell
Get-ADGroupMember -identity "AD Group" -Recursive | Get-ADUser -Property DisplayName | Select Name,ObjectClass,DisplayName | Export-Csv C:\Users\user\Documents\ADGroupMembers.csv
```