# Bethany Architecture Machine Setup
Machine Setup for Architectual Tools for Bethany

# Install Chocolatey
Run the following command using Powershell:

```
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```

# Tools
```
choco install autocadlt -y
```
