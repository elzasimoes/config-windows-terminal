# config-windows-terminal

## Atualizar o Windows PowerShell

[https://learn.microsoft.com/pt-br/powershell/](https://learn.microsoft.com/pt-br/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.4)https://learn.microsoft.com/pt-br/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.4

````
winget install --id Microsoft.Powershell --source winget
````

## Instalar o Oh My Posh

https://ohmyposh.dev/docs/

## Instalar o git posh

https://github.com/dahlbyk/posh-git

````
code $PROFILE
````

````
Enable-PowerType
Set-PSReadLineOption -PredictionSource HistoryAndPlugin -PredictionViewStyle ListView
Import-Module posh-git
oh-my-posh init pwsh --config 'C:\Users\Acer\Posh\amro.omp.json' | Invoke-Expression
Enable-PoshTooltips
````
