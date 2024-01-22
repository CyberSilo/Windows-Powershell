<h1>SFC (System File Checker Tool)</h1>

<h2>Description</h2>
Project consist of running a simple command in Windows Powershell in order to check for corrupted files and restore them. You might use this command when Windows seems to crash constantly or functions aren't working properly. 


<h2>Utilities Used</h2>

- <b>Powershell<b>
- <b>SFC Tools<b>

<h2>Environments Used</h2>

- <b>Windows 10 (22H2)</b>

<h2>Program walk through</h2>

<p align="center">
Launch Windoes Powershell (Admin) in administrator mode. press Windows key + X to pop up menu <br/>
<img src="https://imgur.com/dVMy0Zg.png">
<br />
<br /> 
Run command (DISM.exe /Online / Cleanup-image / Restorehealth) in Windows Powershell as administrator in order to grab the necassary files to restore files on windows
<img src="https://imgur.com/5o2HfrN.png">
<br/>
<br/>
Once completed, run command (sfc /scannow) this will scan all files within Windows system, find corrupted ones and replace them with new restored files. dont worry, no files will be deleted.
<img src="https://imgur.com/YjLhnGl.png">
<br/>
<br/>
