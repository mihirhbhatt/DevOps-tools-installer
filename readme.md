**This repository provides scripts to install/Uninstall a wide range of DevOps tools on both Linux and Windows operating systems. These scripts are designed to make the installation and uninstallation process seamless and straightforward, catering to the needs of DevOps engineers and enthusiasts.**

## Features

- **User-Friendly Interface**: Interactive terminal menus for selecting installation or uninstallation actions on Windows.
- **Multi-OS Detection**: Automatically detects your Linux distribution or Windows version and performs appropriate actions.
- **Multi-Platform Support**: Install and uninstall DevOps tools on multiple Linux distributions (Ubuntu/Debian, CentOS/RHEL, Fedora) and Windows.
  - Install and uninstall essential DevOps tools with a single script.
  - Support for multiple Linux distributions: Ubuntu/Debian, CentOS/RHEL, Fedora.
  - Support for Windows operating systems.
  - Choose which tools to install or uninstall from a list of available options.
  - New additional features:
    - Support for different Linux distributions and Windows versions.
    - Let users decide on which OS they are using and want to install or uninstall tools on.

## DevOps Tools Included

- **Comprehensive Toolset**: Support for a wide range of tools including:
  - Docker 🐳
  - Kubernetes (kubectl) ☸️
  - Ansible 📜
  - Terraform 🌍
  - Jenkins 🏗️
  - AWS CLI ☁️
  - Azure CLI ☁️
  - Google Cloud SDK ☁️
  - Helm ⛵
  - Prometheus 📈
  - Grafana 📊
  - GitLab Runner 🏃‍♂️
  - HashiCorp Vault 🔐
  - HashiCorp Consul 🌐

## Usage

After running the script, follow the on-screen prompts to select the tools you want to install or uninstall. The script will handle the rest based on your operating system and version.

### Linux Specific

- **Ubuntu/Debian**: Installs tools using `apt` package manager.
- **CentOS/RHEL**: Installs tools using `yum` package manager.
- **Fedora**: Installs tools using `dnf` package manager.




### Linux

[](https://github.com/mihirhbhatt/DevOps-tools-installer/blob/master/README.md#usage)

1.  Clone the repository:
    
    git clone https://github.com/mihirhbhatt/DevOps-tools-installer.git
    cd DevOps-Tool-Installer
    
2.  Make the script executable:
    
    chmod +x install_devops_tools.sh
    
3.  Run the script:
   
    ./install_devops_tools.sh
    

### Windows

[](https://github.com/mihirhbhatt/DevOps-tools-installer/blob/master/README.md#usage)

1.  Clone the repository:
    
    git clone https://github.com/mihirhbhatt/DevOps-tools-installer.git
    cd DevOps-Tool-Installer
    
2.  Run the script:
    
    .\install_devops_tools.ps1
