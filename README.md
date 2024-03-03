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

## Instalar power type auto complete

https://github.com/AnderssonPeter/PowerType

````
code $PROFILE
````

1. Habilitar o PowerType
2. Setar o histórico do auto complete
3. Importar o posh-git
4. Habilitar a PoshTooltips
5. Configurar um tema pro oh-my-posh
   
````
Enable-PowerType 
Set-PSReadLineOption -PredictionSource HistoryAndPlugin -PredictionViewStyle ListView 
Import-Module posh-git 
Enable-PoshTooltips 
oh-my-posh init pwsh --config 'C:\Users\Acer\Posh\amro.omp.json' | Invoke-Expression
````
