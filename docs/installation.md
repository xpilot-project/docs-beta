# Installation

!> X-Plane (and xPilot) **must** be closed before installing or upgrading.

Download installation files respective for your computer's operating system from the [xPilot Release Page](https://github.com/xpilot-project/xpilot/releases/latest). The following screenshots are from Windows; however, the installation process will be the same for macOS and Linux.

!> If you're using Microsoft Edge, you may encounter a warning when trying to download the release file. Hover over the warning, click the three dots **(...)**, then click **Keep**.<br/><br/>
![Microsoft Edge Warning](media/EdgeWarning.png ':size=290 :class=img-border')<br/><br/>
A second window will pop up, click **Show more**<br/><br/>
![Microsoft Edge Warning](media/EdgeWarning2.png ':size=518 :class=img-border')<br/><br/>
Then click **Keep anyway**<br/><br/>
![Microsoft Edge Warning](media/EdgeWarning3.png ':size=644 :class=img-border')

?> If you're on Windows, you may encounter a Windows Defender SmartScreen speedbump when trying to launch the installer. Simply click the **More info** link then click the **Run anyway** button.

![Windows Defender Speedbump](media/WindowsDefender.png ':size=498 :class=img-border')

### xPilot Client Install Directory

Choose a folder to install the xPilot client. It is recommended that you leave it as the default folder.

![Install Directory](media/InstallDirectory.png ':size=377')

### X-Plane 11 Location

Next, specify the root folder path of where X-Plane 11 is installed to install the xPilot plugin.

![X-Plane Path](media/XplanePath.png ':size=377')

!> **Advanced Users:** If you have a multi-computer setup for X-Plane, you will need to run this installer on each computer to install the plugin on that X-Plane instance.

Now launch X-Plane and start a flight. If the xPilot plugin is installed correctly, you will see a new `xPilot` submenu under the X-Plane plugin menu.

![X-Plane Plugin Menu](media/PluginMenu.png ':size=253 :class=img-border')

## CSL Installation

xPilot has no special or complex model matching rules that need to be configured. Instead, you must have at least one CSL model package installed and xPilot will handle the rest. CSL models are essentially the aircraft models that X-Plane renders as other flying aircraft in your sim. Without these models, xPilot will not be able to render other VATSIM users in the sim.

When you first launch xPilot, you will be prompted to install a CSL model set. It is recommended that you click **Yes** to automatically install and configure the Bluebell CSL model set. If you choose No, you will need to manually install the model set yourself (only recommended for advanced users).

![Install CSL Models](media/DownloadModels.png ':size=250')

The download is approximately 560 MB. Depending on your internet download speed, it may take a few minutes to download. A progress bar will appear showing the progress of the download.

Before the download can start, you must authenticate yourself using your VATSIM network credentials. Click the "Get Token" button to generate a one-time download token. Your internet browser will open to a website with your download token.

![Get Download Token](media/ModelDownloadGetToken.png ':size=250')

![Download Token](media/DownloadToken.png ':size=207')

Type (or copy and paste) the download token in the xPilot client to begin the download.

![Confirm Download Token](media/ConfirmDownloadToken.png ':size=250')

A progress bar will appear showing the progress of the download.

![Install CSL Models](media/ModelsDownloading.png ':size=250')

Once the download is complete, you will be prompted to choose the root folder of where your X-Plane 11 instance is installed.

![Set X-Plane Path](media/ModelsXplaneFolder.png ':size=250')

After you select the path and click **OK**, the models will begin installing. This may take several minutes. Once the process is complete, the model installation window will close and a message will appear in the main window telling you the CSL aircraft model package was successfully installed. **You will need to restart xPilot (and X-Plane if it was already open).**

![Installing Models](media/ModelsInstalling.png ':size=250')

## Install Additional CSL Packages
Additional CSL model packages can be downloaded and installed to expand your CSL library. To enable additional packages, you will need to specify the paths to where the models are installed in the xPilot settings in X-Plane (`Plugins > xPilot > Settings`). After adding the new folder path, you must restart X-Plane.

![X-Plane CSL Configuration](media/XplaneCSLConfiguration.png ':size=385')
