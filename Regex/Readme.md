# PS Regex
**Related:** [Fundamentals](/Fundamentals/Readme.md)

## Cmdlets
- Select-String (sls) ∙∙∙∙∙ Measure-Object (measure)
- ForEach-Object (%)
- Sort-Object (sort) ∙∙∙∙∙ Get-Unique
- Out-String -Stream

## Examples
```powershell
sls -Path <./file.txt> -Pattern "<regex>" | Measure-Object
    # : Count occurences of <regex> (up to one per line)
sls ... -AllMatches "<regex>" | % {$_.matches.value} | measure
    # : Count ALL <regex> in file using -AllMatches and foreach (%)
```