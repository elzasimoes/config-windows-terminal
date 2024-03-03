# config-windows-terminal

## Atualizar o Windows PowerShell

[https://learn.microsoft.com/pt-br/powershell/](https://learn.microsoft.com/pt-br/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.4)https://learn.microsoft.com/pt-br/powershell/scripting/install/installing-powershell-on-windows?view=powershell-7.4

``winget install --id Microsoft.Powershell --source winget``

https://ohmyposh.dev/docs/
https://github.com/dahlbyk/posh-git

Enable-PowerType
Set-PSReadLineOption -PredictionSource HistoryAndPlugin -PredictionViewStyle ListView
Import-Module posh-git
oh-my-posh init pwsh --config 'C:\Users\Acer\Posh\amro.omp.json' | Invoke-Expression
Enable-PoshTooltips
