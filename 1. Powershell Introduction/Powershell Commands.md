```powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned -Force

Install-Module NtObjectManager -Scope CurrentUser -Force
Update-Module NtObjectManager

Import-Module NtObjectManager
```

## Types
|Type|.NET Type|Example|
|----------|-------------|------------
|array |System.Object[]|@(1, "abc",True) |
|hashtable|System.Collections.Hashtable|@{A=1; B="ABC"} |






