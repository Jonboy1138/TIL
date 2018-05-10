# Get a remote users home directory location

``powershell
Get-ADUser -LDAPFilter "(sAMAccountName=username)" -Properties homeDirectory | Select-Object -ExpandProperty homeDirectory
``