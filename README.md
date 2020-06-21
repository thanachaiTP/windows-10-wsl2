# Windows Subsystem for Linux (2) Installation Guide for Windows 10

## Windows Version (2004)
![Windows Version](pictures/1-Windows-version.png)

## Enable Windows Subsystem for Linux (WSL)
![Contral Panel](pictures/2-contral-panel-programs-turn-features.png)
![Enable WSL](pictures/3-enable-wsl_vm.png)

<h4>Restart Windows</h4>

![Restart Windows](pictures/4-restart.png)

### OR
## Enabling Virtual Machine Platform
<h4> Power Shell (Admin)</h4>

![Restart Windows](pictures/5.enable-virtualmachineplatform.png)

<h4>Restart Windows</h4>

---

# WSL2 
## Install WSL2 Kernel
(1) Download [WSL2 Kernel](https://wslstorestorage.blob.core.windows.net/wslblob/wsl_update_x64.msi)

(2) Power Shell (Admin) and Run
```
wsl --set-default-version 2
```
![Set Default WSL2](pictures/6.set-default-wsl2.png)

## Install your Linux distribution
(1) Open [Microsoft Store](https://aka.ms/wslstore)

(2) Search and install Ubuntu
![Install Ubuntu 20.04](pictures/7-install-ubuntu20-04.png)

## Set up a new distribution
<h4>Create user and password for your new linux </h4>

![Install Ubuntu 20.04](pictures/8-create-user.png)

## Show Version distro
![Show Version linux distro](pictures/9-wsl-list.png)

## Windows Terminal
![Windows Terminal](pictures/10-windows-terminal.png)

## Terminal
![Terminal](pictures/11-terminal.png)

## References
> https://pureinfotech.com/install-windows-subsystem-linux-2-windows-10/

> https://docs.microsoft.com/en-us/windows/wsl/install-win10

> https://docs.microsoft.com/en-us/windows/wsl/wsl2-kernel
