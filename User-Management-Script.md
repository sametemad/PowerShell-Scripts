# User Management Script

PowerShell examples for user administration.

## Tasks

- Create users
- Disable users
- Reset passwords
- Export user lists

## Example Commands

```powershell
Get-ADUser -Filter *
```

```powershell
Disable-ADAccount -Identity username
```

```powershell
Set-ADAccountPassword
```
