# Ultimate Windows Toolbox
This script is the culmination of many scripts and gists from github with features of my own. I am building this script to be a swiss army knife of Windows tools to help setup and optimize machines.

## My Additions
- CCleaner Winget
- SFC and DISM options

## How to Run
Paste this command into Powershell (admin):
```
iex ((New-Object System.Net.WebClient).DownloadString('https://raw.githubusercontent.com/JacobWilliams22/win10script/master/win10debloat.ps1'))
```
Or, shorter:
```
iwr -useb https://raw.githubusercontent.com/JacobWilliams22/win10script/master/win10debloat.ps1 | iex
```
