# OpenModelica1.25VM
exemplar virtual machine with latest Open Modelica vagrant and bootstrap script

This repository provides a Vagrant script to set up a **preconfigured virtual machine based on XUbuntu** with the **OpenModelica nightly build (v1.25)** pre-installed. It simplifies the process of creating a consistent development environment for OpenModelica users.

## Features
- **Operating System**: Xubuntu
- **OpenModelica Version**: Nightly Build 1.25
- Automated installation via Vagrant.

## Requirements
Works on Windows, Linux and iOS. 
Before using this project, ensure you have the following software installed:

1. [**Vagrant**](https://www.vagrantup.com/downloads)  
   Vagrant is used to define and provision the virtual machine.

2. [**VirtualBox**](https://www.virtualbox.org/wiki/Downloads)  
   VirtualBox is the virtualization platform used to host the VM.

## Quick Start

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/creativeconnections/OpenModelica1.25VM.git
   cd OpenModelica1.25VM
   ```
2. Do start VM provisioning
   ```
   vagrant up
   ```
   this step may take several minutes when executed first time. Because VM image (4GB) is downloaded and deployed locally.
3. Open GUI of VirtualBox and login with username:openmodelica password:openmodelica

4. Start OMEdit

5. After you finish your work you can stop your VM by using guest feature to stop machine or
   ```
   vagrant halt
   ```

   

