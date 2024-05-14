# Get-Internet-Explorer
# Force Internet Explorer on Windows 10/11

This repository contains a simple VBS script to launch Internet Explorer on Windows 10 and 11 machines.

## Description

When the `InternetExploter.vbs` script is run, it will open Internet Explorer, allowing you to access sites and applications that require it. This script works even on Windows 10 and 11, where Internet Explorer might be hidden or disabled by default.

If you want to recreate the Internet Explorer experience more permanently, you can create a shortcut to the VBS file and change the shortcut's icon to the Internet Explorer icon.

## Usage

1. Download the `InternetExploter.vbs` file.
2. Double-click the `InternetExploter.vbs` file to run it.
3. Internet Explorer will open.

### Optional: Create a Shortcut with IE Icon

1. Right-click the `InternetExploter.vbs` file and select `Create shortcut`.
2. Right-click the newly created shortcut and select `Properties`.
3. Under the `Shortcut` tab, click `Change Icon`.
4. Select the Internet Explorer icon from the list or browse to find it.
5. Click `OK` to save the changes.

## Compatibility

This script is compatible with:
- Windows 10
- Windows 11

## Script Content

```vbs
CreateObject("WScript.Shell").Run "iexplore.exe"
 
