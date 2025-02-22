# PS Fundamentals
**Related:** [Regex](/Regex/Readme.md)

## Common Variables ‣
- $PSVersionTable ∙∙∙∙∙ $env:PATH ∙∙∙∙∙ $HOME ∙∙∙∙∙ $PROFILE
- `$_` = $PSItem (current obj. in pipeline)
- *Last command:*  `$?` (exec. status) ∙∙∙∙∙ `$^` (1st token) ∙∙∙∙∙ `$$` (last token)

## Common Commands
- systeminfo ∙∙∙∙∙ ipconfig ∙∙∙∙∙ help
- hostname ∙∙∙∙∙ whoami ∙∙∙∙∙ gdr

## Common Cmdlets
- Get-Help ∙∙∙∙∙ Get-Command ∙∙∙∙∙ Get-Alias (gal) ∙∙∙∙∙ Set-Alias (sal)
- Get-ChildItem (gci/ls) ∙∙∙∙∙ Get-Content (type)
- Where-Object (?) ∙∙∙∙∙ Select-Object (select)
- Format-List (fl) ∙∙∙∙∙ Format-Table (ft)
- Get-Process ∙∙∙∙∙ Get-Member 
- Get-ExecutionPolicy ∙∙∙∙∙ `Set-ExecutionPolicy RemoteSigned -Scope CurrentUser`