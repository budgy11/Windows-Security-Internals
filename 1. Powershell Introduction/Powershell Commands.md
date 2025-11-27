```powershell
Set-ExecutionPolicy -Scope CurrentUser -ExecutionPolicy RemoteSigned -Force

Install-Module NtObjectManager -Scope CurrentUser -Force
Update-Module NtObjectManager

Import-Module NtObjectManager
```
- use a `` ` `` to escape characters i.e. `` `r `` or `` `"  ``
## Types
|Type|.NET Type|Example|
|----------|-------------|------------
|array |System.Object[]|@(1, "abc",True) |
|hashtable|System.Collections.Hashtable|@{A=1; B="ABC"} |

## Operators
- `-f` is used as a string formatter
```powershell
"0x{0:X} {1}" -f 42, 123 #0x2A 123
```

## Finding Commands
```powershell
Get-Command -Module NtObjectManager -Name Start-*
```
## Help
```powershell
Get-Help Start-NtWait
Get-Help Start-NtWait -Parameter Object
Get-Help Start-NtWait -Examples
Get-Help Start-NtWait -ShowWindow
```
## Defining Functions


