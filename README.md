<h1 align="center"> SwitchHack </h1>
<h3 align="center"> All-in-One Guide to Hacking your Nintendo Switch </h3>  

</br>

<p align="center"> 
  <img src="images/emulators.gif" alt="Sample signal" width="40%">
</p>

<!-- TABLE OF CONTENTS -->
<h2 id="table-of-contents"> :book: Table of Contents</h2>

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#why-did-i-make-this-guide"> ➤ Why did I make this guide?</a></li>
    <li><a href="#what-can-you-do"> ➤ What you can do with a hacked switch?</a></li>
    <li><a href="#is-hacking-illegal"> ➤ Is hacking your switch illegal?</a></li>
    <li><a href="#what-you-will-need"> ➤ What you will need</a></li>
    <li><a href="#how-much"> ➤ How much will it cost? How long will it take?</a></li>
    <li><a href="#setup"> ➤ Step 1: Setup SD Card</a></li>
    <li><a href="#enter_rcm"> ➤ Step 2: Enter RCM and Inject Payload</a></li>
    <li><a href="#safety"> ➤ Step 3: Safety Precautions</a></li>
    <li><a href="#applications"> ➤ Step 4: Installing Useful Applications</a></li>
    <li>
      <a href="#"> ➤ </a>
      <ul>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
        <li><a href="#"></a></li>
      </ul>
    </li>
    <li><a href="#resources"> ➤ Useful Resources</a></li>
  </ol>
</details>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Why did I make this guide -->
<h2 id="why-did-i-make-this-guide"> :thinking: Why Did I Make This Guide</h2>

<p align="justify"> 
There are many homebrew guides out there. Some are better than others, but they are all different because often there are multiple ways of doing the same thing. None are all-in-one. This guide has its limitations, but if followed it will walk you through every step in the process of setting up a hacked switch. I wrote this guide for a buddy of mine who decided he wanted to buy and hack a switch. I got 2 new SD cards and went through this whole process step-by-step twice more to make sure I did everything correctly. It is not finished, but I plan to continue improving and expanding it.
</p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- What You Will Need -->
<h2 id="what-you-will-need"> :hammer_and_wrench: What You Will Need</h2>

* Unpatched v1 switch (Check your switch serial number <a href="https://ismyswitchpatched.com/" target="_blank">here</a>)
* Micro SD card (256GB or 512GB Recommended, 64GB Minimum)
  - Keep in mind that games are on average 5GB but the largest ones are over 15GB
  - Quality is important as this will help with boot and load times
* RCM jig (highly recommended)
* A device to send a payload
  - PC recommended, but android phones or jailbroken ios devises also work
* Some kind of cable to connect your Switch to your payload sender of choice


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- What you can do with a hacked switch? -->
<h2 id="what-can-you-do"> :video_game: What you can do with a hacked switch?</h2>

*	Easily edit, backup and manage save files
*	Customize your menu pages including home, lockscreen, settings, etc. 
*	Emulate older Console games
*	Download games from a cartridge to your switch
*	Use custom mods and cheats 
*	Connect ps4 and Xbox controllers through Bluetooth
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
*	I bought my switch from an online local marketplace for $230, 256GB SD card for $28 on Amazon, and RCM jig for $8 on Amazon.
*	Using this guide it should take about 1-2 hours depending on your download speed

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h1 align="center"> Lets Begin! </h1>
<p>
  
<!-- Step 1e: Setup SD Card -->
<h2 id="setup"> :floppy_disk: Step 1: Setup SD Card</h2>
<p> 
	
1. Format SD card to Fat32. I used <a href="http://ridgecrop.co.uk/index.htm?guiformat.htm">this tool</a> <a href=""></a>
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
   6.	Open the sd folder and transfer all the files inside to the root of your sd card
4. Download latest updates (Extract each and transfer to root of SD card. Click yes when asked to merge and override existing files)
   1. <a href="https://github.com/Atmosphere-NX/Atmosphere/releases">Atmosphere</a>
   2. <a href="https://github.com/CTCaer/hekate/releases">Hekate</a>, just the bootloader folder
   3. <a href="https://github.com/ITotalJustice/patches/releases">Sigpatches</a>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- Enter RCM and Inject Payload -->
<h2 id="enter_rcm"> :syringe: Step 2: Enter RCM and Inject Payload</h2>
<p>

1. Insert SD Card into switch
2. Turn off Switch
3. Take off right joycon and completely insert RCM jig (There are many other methods but this one is highly recommended. I used an LED light with bent wires before I got the jig which worked but was very annoying)
4. Hold down the volume up button and press the power button
5. If the screen stays black you are in YAH! If the switch logo appears something went wrong and you need to try again
6. Now you can take out the RCM jig and connect your switch to your PC
7. Time to open up TegraRcmGUI or whatever payload sending application you are using (from here on out I will assume you are using a PC)
8. Install drivers from settings tab (First time only)
9. If your Switch is in RCM and connected correctly the red image should turn green and say RCM OK
10. Select the hetake bin file from when you updated hetake and click inject payload
11. Your switch should turn on. You can now disconnect from your PC
12. Enter the date and time then click Done then OK (First time only)

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
	<ul>
		<li>Before you follow the steps for Getting your Console’s Unique keys you will need to download <a href="https://github.com/shchmue/Lockpick_RCM/releases">Lockpick_RCM</a> and transfer it to the payloads folder which is located in the bootloader folder on the root of your SD card</li>
	</ul>
		<li>Follow <a href="https://rentry.org/ExosphereDNSMITM">this</a> Exosphere and DNS Mitty guide</li>
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
	<li>Now follow step 4 to open Hetake</li>
</ol>
	
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
