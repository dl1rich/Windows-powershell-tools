# Windows-powershell-tools
Windows powershell tools

## Scoop

Install

```
# open powershell terminal

Set-ExecutionPolicy RemoteSigned -scope CurrentUser
iwr -useb get.scoop.sh | iex

# Alt installer
iwr -useb https://raw.githubusercontent.com/ScoopInstaller/Install/master/install.ps1 | iex
```

Apps

```
scoop install curl git sudo 
```
