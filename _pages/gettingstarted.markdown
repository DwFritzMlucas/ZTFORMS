---
layout: single
title: Getting Started
permalink: /pages/gettingstarted/
---

This page contains directions on how to download and install the latest version of Aether. As such, there are 
three sections: Downloading, Installing, and Running. Of course things have to be done in order, so grab a cup pf coffee and work our way through it. It shouldn't take approximately 10 minutes. 

<h3> DOWNLOADING THE SOFTWARE </h3>
1. Gain access to where the software is stored. It’s located on an internal network informally called ToolNet. To gain access (if I.T. allows it), map a drive to \\dwffs08.  If all this works you’ll be presented with 3 folders - shown below.

<p align="center">
  <img width="400" height="300" src="/assets/images/gettingstarted/pic_1_toolnet.png">
</p>

If not, get some help. There has to be someone around to help out. The software cant be downloaded from anywhere else, so gaining access to "ToolNet" is pretty critical.

2. Drill down to the download folders by selecting the Aether_EUP -> For Application Engineers -> Beta Release folder - but dont dowload anythng yet. We need to check what version of Windows 10 you're using.   

3. Find the version of Windows 10 you're using by selecting the “Start button” in the lower left corner of your screen, type “winver,” and then press Enter.  This should start up the Winver application which results in a dialog that looks like this:

<p align="center">
  <img width="400" height="400" src="/assets/images/gettingstarted/pic_2_windows_version.png">
</p>

The above dialog shows that this version of Windows 10 is Version 2004. 

4. Aether uses software called MSIX to install itself.  If your build number is earlier (lower in number), choose the “Non-packaged” folder. and move to the next step. If your version of Windows is later (greater) than 1809 select the “Packaged” folder and jump to step 6. 

5. If you have an older version of Windows – select the “Non-packaged” folder, and copy the entire ZeroTouch folder located within in into your local drive (usually the C drive).   Skip the rest of these instructions and jump to Starting the software. 

6. If your software version is above (greater than 1809) select the “Packaged folder”.

7. If this is your first installation, Install the Signing Certificate. If you’ve already done this, skip this step.  Double click on MsixDesktopApp.cer to open it.

<p align="center">
  <img width="400" height="400" src="/assets/images/gettingstarted/pic_3_cert_file.png">
</p>

This should open the following dialog:

<p align="center">
  <img width="300" height="500" src="/assets/images/gettingstarted/pic_4_dig_cert.png">
</p>


Under the General Tab, click on the “Install Certificate…” This will bring up a new dialog, select “Local Machine”. 

<p align="center">
  <img width="400" height="500" src="/assets/images/gettingstarted/pic_5_win_imp_cert_wiz.png">
</p>

Click Next . If a prompt window pops up, click OK.  

A new Certificate Import Wizard dialog will appear. Select the “Place all certificates in the following store” option
<p align="center">
  <img width="400" height="300" src="/assets/images/gettingstarted/pic_6_win_imp_cert_wiz_2.png">
</p>

Then click on the Browse button. This will take you back to the “Select Certificate Store dialog”.  select the “Trusted Root Certificate Authorities” folder then click OK

<p align="center">
  <img width="400" height="300" src="/assets/images/gettingstarted/pic_7_win_cert.png">
</p>

Finally, this will take you back to the “Certificate Import Wizard” window. Click Next

<p align="center">
  <img width="300" height="300" src="/assets/images/gettingstarted/pic_8_more_cert.png">
</p>

Click Finish

<p align="center">
  <img width="300" height="300" src="/assets/images/gettingstarted/pic_9_even_more_cert.png">
</p>

You Should see this prompt

<p align="center">
  <img width="200" height="200" src="/assets/images/gettingstarted/pic_10_cert_final.png">
</p>

Click Ok


<h3> INSTALLING AETHER </h3>

8. Install AEther MSIX Package by double clicking on MsixDesktopApp.msix file. This will open it and install the software. If the certificate was installed successfully, you should see a green check mark indicating AEther installer is a Trusted App

Click Install.

<h3> RUNNING/STARTING AETHER </h3>

9. If your Windows version was older (less than or equal to 1809) and you manually copied the ZeroTouch Folder, to your hard drive, simply select the ZeroTouch.exe file as shown below. 

10. If you Windows version was greater than 1809, there will be a new entry in the Start menu. Select the Windows "Start" menu (usually located in the bottom left of the screen) and either type "AE" or look for the Aether Icon. Depending on the the Aether version installed, the icon might read "Aether" or "Aether_Beta".

<p align="center">
  <img width="400" height="400" src="/assets/images/gettingstarted/aether_start_menu.png">
</p>

11. As Aether loads and starts a splash screen will be displayed, noting the current revision.

<p align="center">
  <img width="500" height="350" src="/assets/images/gettingstarted/aether_splash.png">
</p>

The revision shown above is B5.4.

12. Once Aether has loaded, the main view port with an empty workspace will be displayed. 

<p align="center">
  <img width="500" height="400" src="/assets/images/gettingstarted/aether_workspace.png">
</p>


This is the end of the getting started documentation and hope fully had ended with some operational software installed on you machine.  The next tutorial provides intial training on how to begin using Aether focusing on loading and orienting a solid model. If you want to go there, click on the following link