# Perspecta Senior Design Project

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)

Senior Design project for Cyber Security Engineering

	- Current Phase: Spring 2019 Senior Design II CYSE 493
	- Chocolatey & Boxstarter

Current Branch Worker: Ammar Al-Kahfah

# Required Features!

	- Move software from one machine to another
	- Utilizing Chocolatey as the Package Manager to install software
	- Boxstarter for initialization of platform for installation of software

### Installation (Chocolatey)

##### Requirements
	- Windows 7+ / Windows Server 2003+
	- PowerShell v2+
	- .NET Framework 4+
##### Process

	* Open up Administrative CMD (Command Prompt) Shell
	```
	$ @"%SystemRoot%\System32\WindowsPowerShell\v1.0\powershell.exe" -NoProfile -InputFormat None -ExecutionPolicy Bypass -Command "iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))" && SET "PATH=%PATH%;%ALLUSERSPROFILE%\chocolatey\bin"
	```

	* Check if the program installed correctly
	```
	$ choco 
	$ choco install firefox -y 
	```
Last Updated by Ammar Al-Kahfah
	
