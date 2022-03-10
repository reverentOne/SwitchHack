<h1 align="center"> SwitchHack </h1>
<h3 align="center"> All-in-One Guide to Hacking your Nintendo Switch </h3>  

</br> 

<p align="center"> 
  <img src="images/emulators.gif" alt="emulator gif" width="40%">
</p>

<!-- TABLE OF CONTENTS -->
<h2 id="table-of-contents"> :book: Table of Contents</h2>

<details open="open">
  <summary>Table of Contents</summary>
  <ol start="0">
    <li>
      <a href="#intro"> ➤ :checkered_flag: Before you Begin</a>
      <ul>
        <li><a href="#why-did-i-make-this-guide"> ➤ :thinking: Why did I make this guide?</a></li>
    	<li><a href="#what-you-will-need"> ➤ :hammer_and_wrench: What you will need</a></li>
    	<li><a href="#what-can-you-do"> ➤ :video_game: What you can do with a hacked switch?</a></li>
    	<li><a href="#is-hacking-illegal"> ➤ :detective: Is hacking your switch illegal?</a></li>
    	<li><a href="#how-much"> ➤ :moneybag: How much will it cost? How long will it take?</a></li>
      </ul>
    </li>
    <li><a href="#setup"> ➤ :floppy_disk: Step 1: Setup SD Card</a></li>
    <li><a href="#enter_rcm"> ➤ :syringe: Step 2: Enter RCM and Inject Payload</a></li>
    <li><a href="#safety"> ➤ :closed_lock_with_key: Step 3: Safety Precautions</a></li>
    <li><a href="#applications"> ➤ :computer: Step 4: Installing Useful Applications</a></li>
    <li><a href="#accessing"> ➤ :heavy_check_mark: Accessing your installed apps</a></li>  
    <li><a href="#overview"> ➤ :world_map: Overview of apps</a></li>
    <li><a href="#resources"> ➤ :toolbox: Useful Resources</a></li>
  </ol>
</details>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h1 id="intro" align="center"> Before You Begin! </h1>
<p>

<!-- Why did I make this guide -->
<h2 id="why-did-i-make-this-guide"> :thinking: Why Did I Make This Guide</h2>

<p align="justify"> 
There are many homebrew guides out there. Some are better than others, but all were either made in 2018-2019 and are not well maintained, or they are not easy to follow. None are all-in-one. This guide has its limitations, but if followed it will walk you through every step in the process of setting up a hacked switch. I wrote this guide for a buddy of mine who decided he wanted to buy and hack a switch. I got 2 new SD cards and went through this whole process step-by-step 3 times to make sure I'm explaining everything correctly. It is not finished, but I plan to continue updating and expanding it.
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- What You Will Need -->
<h2 id="what-you-will-need"> :hammer_and_wrench: What You Will Need</h2>

* Unpatched Switch
 	- You can check your switch serial number <a href="https://ismyswitchpatched.com/">here</a>
	- <details><summary>Alternatively, for compatable devices see this chart ➤</summary>
		<table>
		<thead>
		<tr>
		<th align="left">Serial Numbers</th>
		<th align="left"><span>Unpatched</span></th>
		<th align="left"><span>Potentially patched</span></th>
		<th align="left"><span>Patched</span></th>
		</tr>
		</thead>
		<tbody>
		<tr>
		<td align="left">XAW1</td>
		<td align="left">XAW10000000000 to XAW10074000000</td>
		<td align="left">XAW10074000000 to XAW10120000000</td>
		<td align="left">XAW10120000000 and up</td>
		</tr>
		<tr>
		<td align="left">XAW4</td>
		<td align="left">XAW40000000000 to XAW40011000000</td>
		<td align="left">XAW40011000000 to XAW40012000000</td>
		<td align="left">XAW40012000000 and up</td>
		</tr>
		<tr>
		<td align="left">XAW7</td>
		<td align="left">XAW70000000000 to XAW70017800000</td>
		<td align="left">XAW70017800000 to XAW70030000000</td>
		<td align="left">XAW70030000000 and up</td>
		</tr>
		<tr>
		<td align="left">XAJ1</td>
		<td align="left">XAJ10000000000 to XAJ10020000000</td>
		<td align="left">XAJ10020000000 to XAJ10030000000</td>
		<td align="left">XAJ10030000000 and up</td>
		</tr>
		<tr>
		<td align="left">XAJ4</td>
		<td align="left">XAJ40000000000 to XAJ40046000000</td>
		<td align="left">XAJ40046000000 to XAJ40060000000</td>
		<td align="left">XAJ40060000000 and up</td>
		</tr>
		<tr>
		<td align="left">XAJ7</td>
		<td align="left">XAJ70000000000 to XAJ70040000000</td>
		<td align="left">XAJ70040000000 to XAJ70050000000</td>
		<td align="left">XAJ70050000000 and up</td>
		</tr>
		<tr>
		<td align="left">XKW1</td>
		<td align="left"><strong>N/A</strong></td>
		<td align="left"><strong>N/A</strong></td>
		<td align="left">XKW10000000000 and up</td>
		</tr>
		<tr>
		<td align="left">XKJ1</td>
		<td align="left"><strong>N/A</strong></td>
		<td align="left"><strong>N/A</strong></td>
		<td align="left">XKJ10000000000 and up</td>
		</tr>
		<tr>
		<td align="left">XJW1</td>
		<td align="left"><strong>N/A</strong></td>
		<td align="left"><strong>N/A</strong></td>
		<td align="left">XJW01000000000 and up</td>
		</tr>
		<tr>
		<td align="left">XWW1</td>
		<td align="left"><strong>N/A</strong></td>
		<td align="left"><strong>N/A</strong></td>
		<td align="left">XWW01000000000 and up</td>
		</tr>
		</tbody>
		</table>
		</details>
* Micro SD card (256GB or 512GB Recommended, 64GB Minimum)
  - Keep in mind that games are on average 5GB but the largest ones are over 15GB
  - Quality is important as this will help with boot and load times
* RCM jig (highly recommended) <a href="https://www.amazon.com/s?k=rcm+jig&crid=2WTYTM5F11KRR&sprefix=rcm+jig%2Caps%2C145&ref=nb_sb_noss_1">Find on Amazon</a>
* A device to send a payload
  - PC recommended, but android phones or jailbroken ios devises also work
* Some kind of USB cable to connect your Switch to your PC or other payload sender of choice


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- What you can do with a hacked switch? -->
<h2 id="what-can-you-do"> :video_game: What you can do with a hacked switch?</h2>

<img align="right" src="images/hacked_switch_home.jpg" alt="hacked switch home" width="55%">

<br>

*	Easily edit, backup and manage save files
*	Customize your menu pages including home, lockscreen, settings, etc. 
*	Emulate older Console games
*	Download games from a cartridge to your switch
*	Use custom mods and cheats 
*	Connect PS4, Xbox, or other controllers through Bluetooth
*	Play pirated games (Not recommended for legal reasons)
*	Much much more…

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Is hacking your switch illegal? -->
<h2 id="is-hacking-illegal"> :detective: Is hacking your switch illegal?</h2>

*	The short answer is No
*	Hacking your switch is against Nintendo terms of service and puts your device at risk of getting banned. That is all.
*	Pirating games is illegal but…
*	Nobody has EVER been arrested or charged for downloading pirated games. Distributing games is punishable, but again nobody as far as I know has EVER been arrested or charged for pirating games. The reason being that procecuting <a href="https://en.m.wikipedia.org/wiki/Criminal_copyright_law_in_the_United_States#Legal_definition">criminal copyright infringement</a> requires that the infringer acted "for the purpose of commercial advantage or private financial gain."


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- How much will it cost? How long will it take? -->
<h2 id="how-much"> :moneybag: How much will it cost? How long will it take?</h2>

*	~$250-350 USD
*	I bought my switch from an online local marketplace for $230, 256GB SD card for $28 on Amazon, and RCM jig for $7 on Amazon.
*	Using this guide it should take about 1-2 hours depending on your download speed

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h1 align="center"> Lets Begin! </h1>
<p>
  
<!-- Step 1e: Setup SD Card -->
<h2 id="setup"> :floppy_disk: Step 1: Setup SD Card</h2>
<p> 
	
1. <details><summary>:camera: Format SD card to Fat32. I used <a href="http://ridgecrop.co.uk/index.htm?guiformat.htm">this tool</a> <a href=""></a></summary>
	<img src="images/1.png" alt="1" width="40%">
	</details>
2. Download payload sending application to desktop or other easily accessible location
   1. For Windows, you can use <a href="https://github.com/eliboa/TegraRcmGUI/releases">TegraRcmGUI</a> 
   2. For Mac and Linux, you can use <a href="https://github.com/nh-server/fusee-interfacee-tk/releases">fusee-interface-tk</a> 
   3.	For Android, you can use <a href="https://github.com/MenosGrante/Rekado/releases">Rekado</a> 
   4.	For ios, you can use <a href="https://github.com/mologie/nxboot/releases">NXBoot</a>
   5.	For all other payload options see <a href="https://wiki.gbatemp.net/wiki/List_of_Switch_payloads">here</a>
3. Download Software
   1.	Open <a href="https://www.sdsetup.com/console?switch">sdsetup</a>
   2.	Select Recommended Defaults
   3.	Under tesla overlays check EdiZon Overlay and Status Monitor Overlay
   4.	Under Utilities check Checkpoint and NxThemes Installer
   5.	Download your ZIP then Extract the files
   6.	Open the SD folder and transfer all the files inside to the root (a.k.a the main/home directory) of your SD card
   7.	Open the Payloads folder and copy Lockpick_RCM.bin to your SD card inside the payloads folder which is located inside the bootloader folder
4. <details><summary>:camera: Download latest updates (Extract each and transfer to root of SD card. Click yes when asked to merge and override existing files)</summary>
	<img src="images/2.png" alt="2" width="80%">
	</details> <p>
		
	1. <a href="https://github.com/Atmosphere-NX/Atmosphere/releases">Atmosphere</a>
   	2. <a href="https://github.com/CTCaer/hekate/releases">Hekate</a>, just the bootloader folder (save the bin file for the next step)
   	3. <a href="https://github.com/ITotalJustice/patches/releases">Sigpatches</a>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Enter RCM and Inject Payload -->
<h2 id="enter_rcm"> :syringe: Step 2: Enter RCM and Inject Payload</h2>
<p>

1. Insert SD Card into switch
2. Turn off your Switch
	- Hold down the power button on your Switch for 3 seconds and choose power options then Turn Off
3. Take off the right joycon and completely insert the RCM jig 
	- There are many other methods but this one is highly highly recommended. I used an LED light with bent wires before I got the jig which worked but was very annoying.
	- For a list of alternate methods see <a href="https://gbatemp.net/threads/the-ultimate-list-of-mods-to-enter-rcm.502145/">here</a>)
4. Hold down the <b>Volume Up</b> button and press the <b>Power</b> button
	- If the screen stays black that means you are in, YAH! If the switch logo appears, something went wrong and you need to try again
5. Now you can take out the RCM jig and connect your Switch to your PC
	- For other devices follow the instruction in the README.md file on their individual github pages)
6. Time to open up TegraRcmGUI on your PC
7. Open the settings tab and select Install drivers (First time only)
8. <details><summary>:camera: If your Switch is in RCM mode and connected correctly the red image should turn green and say RCM OK</summary>
	<img src="images/3.png" alt="3" width="50%">
	</details>
9. Select the hetake bin file from when you updated hetake and click Inject Payload
10. Your switch should turn on. You can now disconnect it from your PC
11. Enter the date and time then click Done then OK (First time only)

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Safety Precautions -->
<h2 id="safety"> :closed_lock_with_key: Step 3: Safety Precautions</h2>
<p>
	
These steps will prevent your switch from getting permanently bricked or banned
  <ol>
    <li><b>Emummc:</b> Follow steps 2-10 of <a href="https://switch.homebrew.guide/emummc/emummc.html">this</a> guide</li> 
	<ul>
		<li>For part 4 make sure to slide to 29GiB. Creating the emuMMC will take some time so be patient. You are cloning the switches internal memory to your SD card</li>
	</ul>
    <li>After installing press close, then change emuMMC, then SD Raw 1, ok</li>
    <li>Now follow <a href="https://nh-server.github.io/switch-guide/user_guide/emummc/making_emummc/">this</a> guide under Making a <b>NAND backup</b> and Getting your Console's <b>Unique Keys</b></li>
	  <li>Follow <a href="https://rentry.org/ExosphereDNSMITM">this</a> <b>Exosphere</b> and <b>DNS Mitty</b> guide</li>
	<ul>
		<li>I used notepad on my windows PC to create these .ini and .txt files</li>
		<li>For Exosphere just paste For EmuNAND</li>
		<li>For DNS MITY make sure to rename the file to emummc.txt</li>
  </ol>
<p>
Older guides recommend 90DNS. DO NOT DO THIS. It is not necessary and will slow down your internet connection. Incognito is also redundant as Exosphere does the same thing
	
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Installing Useful Applications -->
<h2 id="applications"> :computer: Step 4: Installing Useful Applications</h2>
<p>
Your Switch is now hacked and safe to use. In this step you will install many applications that I will explain in detail later. Follow each of the links below and install the files onto your SD card

<ol>
    <li>Transfer these nro files into your switch folder:</li> 
	    <ul>
				<li><a href="https://github.com/mtheall/ftpd/releases">ftpd pro</a> (download ftpd.nro)</li>
				<li><a href="https://github.com/tallbl0nde/NX-Activity-Log/releases">Activity Log</a> (Create a folder called NX-Activity-Log inside the Switch folder and place NX-Activity-Log.nro inside of it)</li>
		</ul>
    <li>Unzip and Transfer these to the root of your SD card:</li>
	    <ul>
		    <li><a href="https://www.retroarch.com/index.php?page=platforms">RetroArch for Switch</a> (RetroArch is a large file and will take longer than the rest so be patient)</li>
		    <li><a href="https://tinfoil.io/Download">Tinfoil nro Self Installer</a></li>
		    <li><a href="https://github.com/averne/Fizeau/releases">Fizeau</a></li>
		    <li><a href="https://github.com/HookedBehemoth/sys-tune/releases">SysTune</a></li>
		    <li><a href="https://github.com/ndeadly/MissionControl/releases">MissionControl</a></li>
		</ul>
</ol>
<details><summary>:camera: This is what your root and switch folders should look like</summary>
	<img src="images/4.png" alt="4" width="40%">
	&nbsp;&nbsp;&nbsp;
	<img src="images/5.png" alt="5" width="40%">
	</details>
	
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Accessing your Installed apps -->
<h2 id="accessing"> :heavy_check_mark: Accessing your Installed apps</h2>
<p>
	
1. Follow <a href="#enter_rcm">step 2<a/> completely. Now click launch, then Fusee. This should start your Homebrew Switch. *Each time you Turn off your switch or take out the SD card you will have to repeat this process.* If you keep your switch powered on (which is quite easy to do) then this process won’t have to be followed.
2. Accessing the homebrew menu: There are 2 ways to open the homebrew menu.
   1. First, you can launch it through the Album (Hold R when selecting if you actually want to access the Album not the hbmenu)
   2. Second, you can launch it by selecting any game while holding R
      - Some hb apps don’t work if you access the menu through the Album, but until you have a game you need to use the Album
3. Opening Tesla Menu
4. Mission Control
   - with MissionControl, you can use other consoles’ controllers on your Switch through Bluetooth. This is a background process 
   - For a list of compatible controllers look <a href="https://github.com/ndeadly/MissionControl">here</a>. I use the DualShock 4 PlayStation controller
   - To pair a controller go to the Switch Home screen, then Controllers, then Change Grip/Order. While on this screen, place your controller in pairing mode and wait for it to connect to the switch. That is all!

	
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Overview of apps -->
<h2 id="overview"> :world_map: Overview of apps</h2>
<p>

<img src="images/6.jpg" alt="6" width="70%" align="left">
<img src="images/7.png" alt="7" width="70%" align="center">
<p>
	
Note: Skip to Tinfoil to start downloading games

1.  <details><summary>Breeze and Edizon SE</summary
	</details>
2. <details><summary>Checkpoint</summary>
   - Checkpoint is a fast simple save manager. With this tool you can backup or edit save files. For a while this app wasn’t compatible with the latest firmware. If that happens again check out JKSB which does essentially the exact same thing
	</details>
3. <details><summary>Daybreak and Reboot to Payload</summary>
	</details>
4. <details><summary>Fizeau</summary>
   - Fizeau allows you to adjust the color of your screen with corrections including gamma, luminance, and color range. I usually use this to filter out some blue light when playing at night. You can also use this to try and make games look more vibrant. I usually access this through the Tesla Menu. 
	
	(<a href="https://github.com/averne/Fizeau/blob/master/README.md">Documentation</a>)
	</details>
5. <details><summary>Ftpd pro</summary>
   - This is one of my very favorite apps. This allows you to download onto your switch wirelessly through wifi.
   - On your PC file browser, enter the ip address with the ftp:// prefix. e.g. ftp://xxx.xxx.x.x:5000
   - The Switch SD files should now appear on your PC. This is extremely useful for small files, but not recommended for files larger than 100MB as the transfer speed is much slower than direct to SD card
	
	(<a href="https://github.com/mtheall/ftpd/blob/master/README.md">Documentation</a>)
	</details>
6. <details><summary>Goldleaf</summary>
   - This is a multipurpose app that acts as a filesystem browser, NRO installer, web browser, and more
   - If for whatever reason all the Tinfoil app stores are down you can use this app to install NRO game files
	
	(<a href="https://github.com/XorTroll/Goldleaf/blob/master/README.md">Documentation</a>)
	</details>
7. <details><summary>HB App Store</summary>
   - This is a store for homebrew apps. Feel free to browse this and download any apps that seem interesting. Personally, I don’t like using this, but others may really appreciate it. There are many outdated or useless apps on the store so be careful. Most of the documentation for the apps are going to be on github so I recommend you check that out before installing
   - Start by checking out nxmp if you want a video player, ppsspp if you want to emulate psp games, amuiibo for virtual amiibos, sysDVR if you want to stream switch games to your PC
	
	(<a href="https://github.com/fortheusers/hb-appstore/blob/master/README.md">Documentation</a>)
	</details>
8. <details><summary>NX Activity Log</summary>
   - Because you can no longer connect to Nintendo servers you wouldn’t be able to see your activity and game play times without this app.
   - I recommend you replace your User Page with this app. To do that go to settings, scroll down to the bottom, and select Replace User Page to Enable it
	
	(<a href="https://github.com/tallbl0nde/NX-Activity-Log/blob/master/README.md">Documentation</a>)
	</details>
9. <details><summary>nxdumptool</summary>
	
	(<a href="https://github.com/DarkMatterCore/nxdumptool/blob/main/README.md">Documentation</a>)
	</details>
10. <details><summary>NXThemes Installer</summary>
	<a href="https://github.com/exelix11/SwitchThemeInjector/blob/master/readme.md">Documentation</a>
	</details>
11. <details><summary>Sys-clk manager</summary>
    - Sys-clk is a system-wide underclock and overclock sysmodule that allows you to overclock the Switch. It includes automatic underclocking and overclocking depending on if you are docked and what games you are playing
	
	(<a href="https://github.com/retronx-team/sys-clk/blob/develop/README.md">Documentation</a>)
	</details>
12. <details><summary>Retroarch</summary>

	Retroarch is one of the coolest features of the hacked Switch! You can easily play retro games from many consoles including but not limited to NES, SNES, N64, GB, GBC, and GBA. On these older consoles games will run perfectly. Many other consoles are supported, but even ones as recent as the DS may lag or crash so they are not recommended.
	Playing games is very simple. These are the steps:

	1. Find games you want to play and download the roms. I recommend this website: https://www.romsgames.net/
	2. Create a ROMS folder anywhere on your switch. I recommend either the root or in the Retroarch folder. Now create a fold inside this ROMS folder for each console you want to emulate. For example name one ‘NES’ and another ‘GBA’, etc.
	3. Transfer your downloaded games into there game folders you just created on the Switch
	4. On your switch open the hbmenu and select Retroarch
	5. Under Main Menu select Load Core then Download a Core. A list will appear and you can download the core for each console you plan to emulate
	6. Under Main Menu select Load Content then Start Directory then locate the ROMS folder 
	7. Select which game you wish to play and start playing!

	Now you will quickly come to realize that it takes some time to open your games. I just tested and it took me 17 clicks to open a game starting from the switches home. I will show you a way to have games on your Switch home so you can start playing in as little as one click.

	1. Follow this link and download the zip file: https://gbatemp.net/threads/gui-for-nsp-forwarder-tool-for-12.588018/ It is a GUI for an NSP Forwarder
	2. Unzip the file and transfer it to a safe place on your PC.
	3. Open it and run the menu executable and follow the next steps for each game
	4. Fill out each box in the GUI before clicking Create Forwarder
	   * Application Name: Name of the game you want displayed
	   * Author Name: You or whoever/whatever you want here
	   * Title ID: Hit the random key to generate an ID
	   * Icon Path: Where you have the icon you want used when you select the game
	   * Logo Path: Small logo you see when you boot the game. I keep this blank
	   * (Your images must be 256x256 for icons, 160x40 for logos)
	   * Custom prod.keys location: I like keeping the prod.keys in the root folder of the app. To get your keys boot into your switch using the lockpick_RCM payload found here: https://github.com/shchmue/Lockpick_RCM/releases and Dump 
	   * Forwarder Options: Check the Retroarch Rom Forwarder
	   * Core Path: This is the path on your SD card from the root to the core you want to use for the rom.
	   * Rom Path: This is the location of your rom you want to use with the core you selected in the previous step.
	5. The Forwarder should have created nsp files in the NSP folder on the root of the app
	6. Now create a folder on the root of your SD card called NSP Files or whatever
	7. Transfer the files in the NSP folder on the root of the app to the NSP Files folder on the root of your SD card
	8. On your switch open the hbmenu and select Goldleaf then Explore content then SD card then NSP Files
	9. Install each nsp file and they should now show up on your Switch’s Home!

	(<a href="https://www.retroarch.com/">Retroarch Documentation</a>)
	</details>

13. <details><summary>Tinfoil</summary>

	There are basically 3 unconventional ways to get games onto your switch. Firstly, you can download from a cartridge that you own. If your goal is to avoid pirating than this is the best method for you. Secondly, you can go to any number of sketchy websites filled with adds and links to malware to download the game file onto your switch. Using an app like Goldleaf you can install and play them. Thirdly, you can use a game store through Tinfoil. This is far easier, quicker, and safer than the second method. I will now walk you through how to get games from Tinfoil.

	1. Boot into your switch using fusee and make sure you are connected to the internet
	2. On your switch open the hbmenu and select Tinfoil installer
	3. After installation Tinfoil should show up as an app on the Switch home
	4. Open Tinfoil if not already open, select File Browser, and press (-)
	5. Fill out:
	   * Protocol: https
	   * Host: raw.githubusercontent.com
	   * Path: carcaschoi/tinfoil-json/master/tinfoilshop.json
	   * Titles: Luffshop
	6. The details, if needed, to install Luffshop can be found here: https://github.com/carcaschoi/tinfoil-json
	7. Save and wait a minute or so for the shop to load
	8. A new tab in Tinfoil should appear called New Games
	9. Great! Now you can search for any games or DLCs that your heart desires
	*To install via USB on Windows read: https://discord.com/channels/679180031854903316/703531443267043409/745781154757476373 
	**If you want to explore more ways to access games check out: https://games.jits.cc/ 

	Titz Pro shop

	Luffshop is not actually a shop but a redirect to many other shops. Sometimes shops go down, but with Luffshop you will have your best bet of having access to games. One of these shops that you are redirected to is titz (turtle in the shop). There is also a premium shop called Titz Pro. The only way to access this shop is through the turtle in the shop discord channel here: https://discord.com/channels/829394042025672704/874130275343401000 
	Follow the instructions under #info-check-here-first. You will need to buy an eshop code and donate it. There are links to where to buy codes under #support-nintendo. $5 cards work as well as 500 Yen cards

	Why should I get Titz Pro?

	First, you are supporting the community as all donations go to expanding the shop. Second you will have early access to many titles often before they are officially released. Third, You will have access to Retroarch games.

	(<a href="https://tinfoil.io/">Tinfoil Documentation</a>)
</details>

	
![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Useful Resources -->
<h2 id="resources"> :toolbox: Useful Resources</h2>
<p>
	
Switch acking communities:
* GBATEMP: https://gbatemp.net/forums/nintendo-switch.283/
* Reddit: https://www.reddit.com/r/SwitchPirates/
* Discord: https://discord.gg/C29hYvh
<p>
	
Useful but incomplete guides:
* https://rentry.org/SwitchHackingIsEasy
* https://nh-server.github.io/switch-guide/
* https://switch.homebrew.guide/index.html
* https://www.cfwaifu.com/switch/
