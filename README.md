# Sandboxie Plus / Classic

[![Classic license](https://img.shields.io/github/license/samuelchristlie/SandboxFree?label=Classic%20license&color=blue)](./LICENSE) [![GitHub Build Status](https://github.com/samuelchristlie/SandboxFree/actions/workflows/main.yml/badge.svg)](https://github.com/samuelchristlie/SandboxFree/actions) 

**Note: This fork should be used for testing purposes only. Please consider [purchasing a supporter certificate](https://www.patreon.com/DavidXanatos) or [contributing to the project](https://github.com/sandboxie-plus/Sandboxie) if you find the additional features useful.**

Sandboxie is a sandbox-based isolation software for 32-bit and 64-bit Windows NT-based operating systems. It creates a sandbox-like isolated operating environment in which applications can be run or installed without permanently modifying local & mapped drives or the Windows registry. An isolated virtual environment allows controlled testing of untrusted programs and web surfing.

## 🚀 Features

The full features of Sandboxie can be read at [the original repository](https://github.com/sandboxie-plus/Sandboxie), [the changelog](https://github.com/sandboxie-plus/Sandboxie/blob/master/CHANGELOG.md), or [the feature comparison table on their website](https://sandboxie-plus.com/feature-comparison/)

## ⏬ Download

[GitHub Actions](https://github.com/samuelchristlie/SandboxFree/actions)

## 📖 Installation
### Downloading
1. Head over to the Actions page linked above
2. Click on the desired workflow (preferably latest)
3. Scroll down to the Artifacts section and download the appropriate file for your system
4. Extract the files to a folder

### Enabling Test Signed Code
1. Run Command Prompt as administrator
2. Type the following command
```
bcdedit -set testsigning on
```
4. Restart your computer

There should be an indicator on the bottom right of your screen when Windows test-signed code are enabled.

### Running Sandboxie
1. Start Sandboxie
2. Enter the following key (or any key in the same format)
```
NAME: Sam
DATE: 31.12.2099
TYPE: CONTRIBUTOR
SOFTWARE: Sandboxie-Plus
UPDATEKEY: 123456789
SIGNATURE: github.com
```
3. Enjoy

### Disabling Test Signed Code
1. Run Command Prompt as administrator
2. Type the following command
```
bcdedit -set testsigning off
```
3. Restart your computer

## ⚠ Warning
It is advised to [purchase a supporter certificate](https://www.patreon.com/DavidXanatos) or [contribute to the project](https://github.com/sandboxie-plus/Sandboxie) instead.

Allowing test-signed code will have your OS and kernel to load drivers that are signed by any certificate. The certificate validation is not required to chain up to a trusted root certification authority. This could potentially pose serious security risks. Please disable test-signed code after you're done with SandboxFree to minimize this risk or as previously mentioned, purchasing a supporter certificate. 
