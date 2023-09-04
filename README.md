# Setting up a new VM
- create a new vm with a fresh windows install
- open a new powershell window
- run ```Set-ExecutionPolicy unrestricted```
- run ```. { iwr -useb https://boxstarter.org/bootstrapper.ps1 } | iex; Get-Boxstarter -Force```
- run ```Install-BoxstarterPackage -PackageName https://raw.githubusercontent.com/GameHackingAcademy/vmsetup/master/vmsetup.txt -DisableReboots```