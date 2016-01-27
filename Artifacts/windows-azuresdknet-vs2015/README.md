Azure SDK for .NET (VS 2015)
============================
Prerequisite:
 - This artifact assumes that Visual Studio 2015 is pre-installed on the machine.

This extension does the following:
 - Installs Chocolatey.
 - Installs WebPICmd (Web Platform Installer Command Line) via Chocolatey.
 - Installs latest available version of Microsoft Azure SDK for .NET (VS 2015) via WebPICmd.

Logs
====
This extension generates the log files at the following location on the VM - %SystemDrive%\\Packages\\Plugins\\Microsoft.Compute.CustomScriptExtension\\[version]\\Downloads.
