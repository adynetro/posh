# POSH theme

## adynetro

![POSH](.adynetro.png)

## Installation

Install oh-my-posh from <https://ohmyposh.dev/> and Meslo LGM NF nerd font <https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Meslo.zip>

```posh
Install-Module oh-my-posh
Import-Module oh-my-posh
```

clone the repo inside home folder

```posh
oh-my-posh init pwsh --config "~\posh\.adynetro.omp.json" | Invoke-Expression

```

add poshprompt to ```$PROFILE``` and reload the terminal

## Add autocomplete

```posh
Install-Module PSReadLine -Force
```

add lines to ```$PROFILE``` and reload the terminal

```posh
Set-PSReadLineOption -PredictionSource History
Set-PSReadLineOption -PredictionViewStyle ListView
```
## Add terminal Icons

```posh
Install-Module -Name Terminal-Icons -Repository PSGallery
```
and add this to ```$PROFILE``` and reload the terminal

```posh
Import-Module -Name Terminal-Icons
```
