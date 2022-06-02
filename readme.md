# install winget

- [Winget](https://github.com/microsoft/winget-cli) is a command line package manager from Microsoft
- [Scoop](https://github.com/lukesampson/scoop) is a mature CLI package manager that has been around for years

set json ctrl+shift+p

# Examine the commands in the Pester module

Get-Command -Module Pester

# Invoke the Pester testing engine

Invoke-Pester -Path $PSScriptRoot

install-module PSScriptAnalyzer -Scope CurrentUser -Force

## Powershell Docker Env

for example , choose 7.2-ubuntu-focal

docker pull mcr.microsoft.com/powershell:7.2-ubuntu-focal

docker ps

run powershell container , and execute code in docker enviroment
