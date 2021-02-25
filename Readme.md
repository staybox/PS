#### Как запускать скрипт RunSCCM-Manual.ps1

```
Как запускать:

.\RunSCCM.ps1 -ArrayComputers "ComputerName", "ComputerName"

или

.\RunSCCM.ps1 -ArrayComputers (Get-Content "\\SERVER\data.txt") где в файле написать имена компьютеров, по одному  на одной строке

или

.\RunSCCM.ps1 -ComputerName "ComputerName" - для одного компьютера
```