## Download RSAT (Remote Server Administration Tools)

Download the latest version from Releases page:       
https://github.com/malthux/RSAT/releases/tag/1.412

RSAT provides IT professionals the ability to manage Windows Server roles and features remotely from a computer running either Windows 10 or Windows 7 Service Pack 1.

## Introduction

RSAT cannot be installed on devices running Home or Standard editions of Windows. It is only supported on Professional or Enterprise editions of the Windows client OS. Unless the download page specifically indicates support for a beta, preview, or other prerelease version of Windows, a full (RTM) release of the operating system is required for proper installation and operation. Some users have attempted to bypass the RSAT MSU limitations to install it on unsupported editions or builds of Windows, but such actions violate the Windows end-user license agreement.

Installing RSAT is similar to installing Adminpak.msi on client systems running Windows 2000 or Windows XP. However, there is an important distinction: in Windows 7, the tools are not immediately available after installation. You must manually enable the tools you want through the Control Panel. To do this, navigate to **Start** > **Control Panel** > **Programs and Features**.

In RSAT packages for Windows 10, all tools are activated by default once the installation is complete. To disable any tools you don’t intend to use on Windows 7, open **Turn Windows features on or off**.

For Windows 7 users, it is necessary to manually enable the tools corresponding to the roles and features you wish to manage after the RSAT package has been installed.

If you are managing roles or features on remote servers running Windows Server 2012 R2 or later, additional tools do not need to be installed. Open the Add Roles and Features Wizard in Windows Server 2012 R2 or newer, then on the **Select Features** screen, expand **Remote Server Administration Tools**, select the tools you require, and complete the wizard to finish the installation.

## RSAT for Windows 10, version 1809 or later versions

> **Note**
> The **Turn Windows features on and off** dialog in Control Panel is no longer available.

Installing RSAT on Windows 10 version 1809 and later is slightly different from previous methods. RSAT is now included as part of the operating system and can be installed via **Optional Features**.
