# Initial Setup

This process will work on either a 32 or 64 bit installation of Windows 10 (other versions of Winodws have not been tested), with powershell instaled (Windows comes with Powershell, so this shouldn't be a problem unless you have knowingly deleted it in the past).
 
1) Open the "Control Panel" application;
2) In the "View by" option at the top right of the page, ensure that the "Large Icons" option is selected;
3) Select "Network and Sharing Center";
4) In the sidebar located at the left of the page, click "Change adapter settings";
5) Seeing the multiple network interfaces on your system, it may be nessesary to check which ones are your two ethernet interfaces if it is not immediatly clear (this page can be cluttered when multiple VPN applications or other network interfaces like WI-FI cards are installed). 
    Any interface that is manually enabled will have a blue icon, and any interface that is manually disabled will have a greyscale logo, and any port that is not currently conected to the internet will have a red "X" on the logo. Using this information, you can enable all of your network interfaces by right-clicking on them and selecting the first option in the list, which will show "Enable" if the interfact is disabled and vise-versa.
    Then, you can see which ports are your two ethernet ports, as when you plug and unplug each cable from your pc, the red "X" on it's logo will appear and disapear.
6) Once the two prots have been identifyed, right click on one of them, and select the "Rename" option, and rename it to "Network1" (With this exact capitalization and spacing, or lack thereof), and rename the second to "Network2".
7) Download the "Change Network" and "Shortcuts" folders;
8) Drag the "Change Network" folder to your "Documents" folder, which can be found in the "This PC" section in the File Explorer sidebar;
9) Now, with both of your network interfaced enabled in the control panel, you can right click on one of the the powershell scripts and select the "Run with Powershell" option, and ensure tha it works and you can swap between networks, doing any troubleshooting if nessesary;
10) Then, open the "Shortcuts" folder, and drap the shortcut files to wherever best suits your needs.
