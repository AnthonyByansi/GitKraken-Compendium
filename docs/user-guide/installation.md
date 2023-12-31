# Installation Guide

📚 This guide will walk you through the installation process for GitKraken on various operating systems. 🖥️

## Prerequisites

Before installing GitKraken, ensure that you have the following prerequisites:

- **Operating System**: GitKraken is compatible with Windows, macOS, and Linux. 💻
- **System Requirements**: Ensure that your system meets the minimum requirements specified by GitKraken. ⚙️
- **Internet Connection**: A stable internet connection is required to download and install GitKraken. 🌐

## Windows

To install GitKraken on Windows:

1. Visit the [GitKraken website](https://www.gitkraken.com/) and click on the "Download" button. 💻💾

2. Run the installer file once it is downloaded. 📥💻

3. Follow the on-screen instructions to complete the installation process. 📝✅

4. Once installed, launch GitKraken by locating the GitKraken shortcut in the Start Menu or by double-clicking the GitKraken desktop icon. 🚀🖱️

## macOS

To install GitKraken on macOS:

1. Visit the [GitKraken website](https://www.gitkraken.com/) and click on the "Download" button. 💻💾

2. Open the downloaded .dmg file. 📂🖱️

3. Drag and drop the GitKraken.app file into the Applications folder. 📂🔽🖱️

4. Launch GitKraken by opening the Applications folder and double-clicking on the GitKraken icon. 🚀🖱️

## Linux

To install GitKraken on Linux:

1. Visit the [GitKraken website](https://www.gitkraken.com/) and click on the "Download" button. 💻💾

2. Choose the appropriate package format for your Linux distribution (e.g., .deb for Debian-based distributions, .rpm for Red Hat-based distributions). 📦🐧

3. Open a terminal and navigate to the directory where the downloaded package is located. 🖥️📂

4. Run the package installation command specific to your Linux distribution (e.g., `sudo dpkg -i <package-name>.deb` for Debian-based distributions). 💻📝

5. Launch GitKraken by searching for it in the applications menu or by running the `gitkraken` command in the terminal. 🚀🔍🖥️

## Verify Installation

To verify the successful installation of GitKraken, open GitKraken and ensure that it launches without any errors. You can also check for any available updates within the application. ✅🔍

```mermaid

graph TD

subgraph Prerequisites
  A[Operating System]
  B[System Requirements]
  C[Internet Connection]
end

subgraph Windows
  clickDownloadButton[Visit GitKraken website and click "Download" button]
  runInstaller[Run installer file]
  completeInstallation[Follow on-screen instructions to complete installation]
  launchGitKraken[Launch GitKraken]
end

subgraph macOS
  clickDownloadButton2[Visit GitKraken website and click "Download" button]
  openDmg[Open downloaded .dmg file]
  dragDrop[Drag and drop GitKraken.app file into Applications folder]
  launchGitKraken2[Launch GitKraken]
end

subgraph Linux
  clickDownloadButton3[Visit GitKraken website and click "Download" button]
  choosePackage[Choose appropriate package format for Linux distribution]
  navigateTerminal[Open terminal and navigate to downloaded package directory]
  runInstallationCommand[Run package installation command specific to Linux distribution]
  launchGitKraken3[Launch GitKraken]
end

subgraph VerifyInstallation
  openGitKraken[Open GitKraken]
  checkErrors[Check for any launch errors]
  checkUpdates[Check for available updates]
end

subgraph Congratulations
  readyStart[Ready to start using GitKraken]
  support[Refer to troubleshooting guide or contact support for assistance]
end

Prerequisites --> Windows
Prerequisites --> macOS
Prerequisites --> Linux

Windows --> clickDownloadButton
clickDownloadButton --> runInstaller
runInstaller --> completeInstallation
completeInstallation --> launchGitKraken

macOS --> clickDownloadButton2
clickDownloadButton2 --> openDmg
openDmg --> dragDrop
dragDrop --> launchGitKraken2

Linux --> clickDownloadButton3
clickDownloadButton3 --> choosePackage
choosePackage --> navigateTerminal
navigateTerminal --> runInstallationCommand
runInstallationCommand --> launchGitKraken3

VerifyInstallation --> openGitKraken
openGitKraken --> checkErrors
checkErrors --> checkUpdates

checkUpdates --> readyStart
checkErrors --> support

```
--- 

Congratulations! You have successfully installed GitKraken on your operating system. You are now ready to start using GitKraken for your version control needs. 👏🎉

If you encounter any issues during the installation process, refer to the [troubleshooting](../troubleshooting.md) guide or reach out to the GitKraken support team for further assistance. 🛠️🆘
