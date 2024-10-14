---
title: Protecting Your Windows 11 System with DIY USB Security Keys - A Comprehensive Tutorial
date: 2024-10-13T02:21:45.992Z
updated: 2024-10-13T18:08:51.638Z
tags:
  - product
  - antivirus
  - utilities
categories:
  - malwarefox
thumbnail: https://thmb.techidaily.com/ab11097b735383eb1301c6c7953b6d3e90027241dcabace0ad8db43fe24b30d7.jpg
---

## Protecting Your Windows 11 System with DIY USB Security Keys - A Comprehensive Tutorial

Gone are the days when you could just rely on the passwords for your device security. With the advancement in cybercrimes and the [user’s reluctancy to create a secure password](https://tools.techidaily.com/malwarefox/products/), cracking the passwords and hacking any device is not a big deal for the web criminals.

![TotalAv Logo](https://www.malwarefox.com/wp-content/uploads/2024/02/totalav-svg.webp "totalav-svg")

**Stay malware-free with reliable antivirus**

Don't compromise your Data and Privacy. TotalAV is a top-notch antivirus program that handles various viruses, trojans, and other malware that may target your devices. It will safeguard your devices and enhance your system performance.

**4.9**/5

⭐ **Editor's Choice**

✔️ Excellent Malware Detection  
✔️ Multiple set of Features  
✔️ 30 Day Money-Back

[](https://tools.techidaily.com/malwarefox/products/) Get TotalAV > 

The **USB Security Key** can be the ultimate solution for the people who are very concerned about their devices’ security. Also, you do not have to rely just on passwords anymore. 

In this guide, we would discuss what a USB security key is and how to convert your regular USB drive into a device unlocker.

>  Disclaimer: This post includes affiliate links
>
>  If you click on a link and make a purchase, I may receive a commission at no extra cost to you.
>

## What is a USB Security Key?

The USB Security key or the physical security key is the advanced method of login authentication. This USB key can be used for locking and unlocking the PC and is a part of two-factor authentication. Obviously, it would be quite difficult for hackers to get their hands on the tangible key.

You can get such a physical security key from the manufacturer like Yubikey, Google, and Thetis. However, they are costly. 

The cheaper alternative is creating your own USB login key. However, for that, you have to compromise one of your USB drives or get an affordable Pendrive specifically for this purpose. 

## Pros and Cons of the Physical Security Key

Every coin has two sides. Likewise, security keys also have two sides, positive and negative. Let us list them out.

### **Pros:**

* A USB security would provide an extra layer of protection to your device by forming a two-factor authentication.
* Cybercriminals can hack your using several ways. Also, after exposure, a password is useless. On the other hand, USB keys are almost impossible to hack, and the hacker has to steal the key to get through your system, which is quite unlikely because usually, hackers work only online.
* You already have to memorize several passwords of your different accounts, getting a physical lock key would reduce some strain, and you can lock/unlock your computer hassle-free.

[How to Remove Virus Alert from Microsoft Edge?](https://tools.techidaily.com/malwarefox/products/)

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2112007/7443" target="_top" id="2112007">
  <img src="//a.impactradius-go.com/display-ad/7443-2112007" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2112007/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Cons:**

* If you damage or lose the physical key, the recovery is possible but by a long and lethargic process.
* If you want to allow access to your system to someone else, you have to provide them with your key physically. That becomes impossible if you are far away.
* The USB security key would permanently occupy a USB port, which means you would lose one of your USB ports forever.

So, these are the Pros and Cons of the Physical Security key. Weigh them keeping your preference in mind and then choose whether to go for it or not.

<!-- affiliate ads begin -->
<a href="https://aligracehair.sjv.io/c/5597632/2135359/19272" target="_top" id="2135359">
  <img src="//a.impactradius-go.com/display-ad/19272-2135359" border="0" alt="https://techidaily.com" width="392" height="72"/>
</a>
<img height="0" width="0" src="https://aligracehair.sjv.io/i/5597632/2135359/19272" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

## How to create a USB Security Key on Windows 10?

You can create a USB security key on Windows 10 using an in-built program – **Windows BitLocker.** However, this method would only work for Pro and Enterprise versions of Windows as the Home version does not come with BitLocker.

The first step is to enable the BitLocker on your system Drive, that is, the drive where the Windows 10 is installed.

<!-- affiliate ads begin -->
<a href="https://bluettius.sjv.io/c/5597632/2139112/17108" target="_top" id="2139112">
  <img src="//a.impactradius-go.com/display-ad/17108-2139112" border="0" alt="https://techidaily.com" width="250" height="90"/>
</a>
<img height="0" width="0" src="https://bluettius.sjv.io/i/5597632/2139112/17108" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Enable Bitlocker**

– Open File Explorer and go to “My PC.”

– Right-click on your system drive and choose “**Turn on BitLocker.**“

![Turn on BitLocker.](https://www.malwarefox.com/wp-content/uploads/2020/06/Turn-on-BitLocker.png)

– Follow the on-screen steps, and at the end, click on “**Start encrypting.**“

![Start encrypting](https://www.malwarefox.com/wp-content/uploads/2020/06/Bitlocker-encryption.png)

– Your system would restart, and then encryption would begin, which would take some time, depending on the size of the drive.

### **Enable Security Key using BitLocker**

Once the BitLocker is enabled, we can proceed to create the security key.

1. **Open Group Policy Editor**  
In Windows search bar, type “group policy editor” and click on the relatable icon to open **Group Policy Editor.**  
![Open Group Policy Editor](https://www.malwarefox.com/wp-content/uploads/2020/06/Group-Policy-Editor.png)
2. **Navigate to Operating System Drives**  
Follow this path **Computer Configuration -> Administrative Templates -> Windows Components -> BitLocker Drive Encryption -> Operating System Drives**
3. **Open Require Additional Authentication at startup**  
Look for “**Require Additional Authentication at startup**” and open it.  
![Require Additional Authentication at startup](https://www.malwarefox.com/wp-content/uploads/2020/06/Additional-Authentication.jpg)
4. **Enable it and Configure its settings**  
A new window would open, click on **Enable** bullet option. There’s a drop-down menu labeled “**Configure TPM startup key**.” Change this to “**Require Startup Key With TPM.**“  
![Enable additional authentication](https://www.malwarefox.com/wp-content/uploads/2020/06/Enable-additional-authentication.png)
5. **Run Command Prompt**  

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2043594/7443" target="_top" id="2043594">
  <img src="//a.impactradius-go.com/display-ad/7443-2043594" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2043594/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

In the final step, run Command Prompt as admin and type this command:  
**manage-bde -protectors -add c: -TPMAndStartupKey j:**  
Where ‘c:’ is the drive where Windows is installed and ‘j:’ is assigned to the USB drive.  
![Run Command](https://www.malwarefox.com/wp-content/uploads/2020/06/USB-key.png)

<!-- affiliate ads begin -->
<a href="https://25home.pxf.io/c/5597632/2148641/16836" target="_top" id="2148641">
  <img src="//a.impactradius-go.com/display-ad/16836-2148641" border="0" alt="https://techidaily.com" width="254" height="90"/>
</a>
<img height="0" width="0" src="https://25home.pxf.io/i/5597632/2148641/16836" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

[How to Reset Web Browser to Default Setting](https://tools.techidaily.com/malwarefox/products/)

That’s it. The security key is created, and you would be asked to insert it whenever you start the computer.

## How to create a USB Security Key Using Third-party App?

If you are a Windows 10 home user or you didn’t want to use the complicated method of Windows Bitlocker to create your USB security key, then some third-party applications could help you.

### **USB Raptor**

![USB Raptor security key](https://www.malwarefox.com/wp-content/uploads/2020/06/usb-raptor.jpg)

USB Raptor is one of the popular tools for turning a USB drive into a USB security key. The best part is that it is open-source software, and that is why it is entirely free to use for personal and non-commercial use. It is compatible with all the versions of Windows from Windows XP and above. 

With Raptor, you can link the key to the serial number of the drive. The only problem with Raptor is, it does not encrypt the system as the BitLocker does. Yet, it would lock and unlock the device with the USB drive. However, it is easy to install and is quite flexible, so you can use it for a medium-security.

[Get Raptor](https://sourceforge.net/projects/usbraptor/)

---

<!-- affiliate ads begin -->
<a href="https://unicoeye.pxf.io/c/5597632/2134495/18498" target="_top" id="2134495">
  <img src="//a.impactradius-go.com/display-ad/18498-2134495" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://unicoeye.pxf.io/i/5597632/2134495/18498" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Predator**

![Predator USB security key](https://www.malwarefox.com/wp-content/uploads/2020/06/predator.png)

Predator is another popular program to turn a USB into a physical security key. After the USB drive is converted into a security key, your system would only be accessible when the USB is plugged in. As soon as the drive would be plugged out, the computer will be locked automatically.

Anybody who tries to access the system without the USB drive would receive an error message, “Access Denied.” 

Installation of the Predator is easy. Download the installation file and open it. Later, you just have to follow the on-screen instructions.

[Get Predator](https://www.predator-usb.com/predator/en/index.php)

---

<!-- affiliate ads begin -->
<a href="https://appsumo.8odi.net/c/5597632/2151893/7443" target="_top" id="2151893">
  <img src="//a.impactradius-go.com/display-ad/7443-2151893" border="0" alt="https://techidaily.com" width="728" height="90"/>
</a>
<img height="0" width="0" src="https://appsumo.8odi.net/i/5597632/2151893/7443" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

### **Rohos Logon Key**

![Rohos Logon USB security Key](https://www.malwarefox.com/wp-content/uploads/2020/06/rohos-logon-key.jpg)

Rohos Logon Key is a multi-platform security key maker software that provides two-factor authentication to unlock both Windows and macOS devices. It comes with both a free and paid version. Though the free version offers a lot of features, it is only available for Windows users. 

[How to remove the WebDiscover Browser from the system?](https://tools.techidaily.com/malwarefox/products/)

Rohos store your login credential into the USB drive, and during startup, when you insert the drive, it automatically inputs the login details for unlocking the system.

[Get Rohos Logon Key](http://www.rohos.com/download/)

---

## Conclusion

These are the method using which you can convert a USB drive into a USB security key. As already mentioned, the physical keys can be of great use and provide extra security over passwords. Currently, you can use these keys for locking and unlocking the device; soon, you can also use them to log in to your different accounts.

**1\. How does a USB security key work?** 

A security key works by storing your login details in the drive, and when the drive is plugged in, it automatically inputs the stored credentials to unlock the device.

**2\. What happens if you lose your security key?** 

While creating a key, you would always be prompted to create a recovery method in case the key is lost or damaged. If you lose your key, immediately use the recovery method to log in and then remove the key as authentication.

**3\. How do I backup my YubiKey?** 

[According to YubiKey](https://support.yubico.com/support/solutions/articles/15000010242-can-i-duplicate-or-back-up-a-yubikey-), due to security reasons, the firmware of YubiKey does not allow the system to read the drive after it is written. Therefore, it is impossible to create a backup of YubiKey.

## 2 thoughts on “How to Make a USB Security Key to Protect Windows 10 PC”

1. ![](https://secure.gravatar.com/avatar/1f15aeebf604b14368e5d572c11913a9?s=50&d=mm&r=g)  
Robert  
[January 1, 2022 at 2:40 pm](https://tools.techidaily.com/malwarefox/products/)  
what about windows 11 this is now outdated information I been looking up information for windows 11 it pulls up this windows 10 in search on bing.com  
[Reply](https://tools.techidaily.com/malwarefox/products/)  
   * ![](https://secure.gravatar.com/avatar/b078f2f4ee5a7d70f03d2ed3d315f291?s=50&d=mm&r=g)  
   Lukas  

<!-- affiliate ads begin -->
<span id="1982456">
					<video width="576" height="240" style="cursor:pointer"
           poster="//a.impactradius-go.com/display-clicktoplayimage/1982456.png"
           onclick="if(!this.playClicked){this.play();this.setAttribute('controls',true);this.playClicked=true;}">
	   <source src="//a.impactradius-go.com/display-ad/22993-1982456">
	   <img src="//a.impactradius-go.com/display-clicktoplayimage/1982456.png" style="border: none; height: 100%; width: 100%; object-fit: contain">
	</video>
	<div style="width:360px;text-align:center"><a href="javascript:window.open(decodeURIComponent('https%3A%2F%2Fhomestyler.sjv.io%2Fc%2F5597632%2F1982456%2F22993'), '_blank');void(0);">Click here</a></div>
</span>
<img height="0" width="0" src="https://imp.pxf.io/i/5597632/1982456/22993" style="position:absolute;visibility:hidden;" border="0" />
<!-- affiliate ads end -->

   [February 25, 2022 at 2:41 am](https://tools.techidaily.com/malwarefox/products/)  
   Windows 11 is literally just a reskin of Windows 10 (with a few extra features). All of these should work perfectly fine.  
   [Reply](https://tools.techidaily.com/malwarefox/products/)

### Leave a Comment [Cancel reply](https://tools.techidaily.com/malwarefox/products/)

Comment

Name Email 

Save my name, email, and website in this browser for the next time I comment.

Δ

<ins class="adsbygoogle"
     style="display:block"
     data-ad-format="autorelaxed"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="1223367746"></ins>

<ins class="adsbygoogle"
     style="display:block"
     data-ad-client="ca-pub-7571918770474297"
     data-ad-slot="8358498916"
     data-ad-format="auto"
     data-full-width-responsive="true"></ins>

<span class="atpl-alsoreadstyle">Also read:</span>
<div><ul>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-economical-systems-optimized-by-ideal-obs-settings/"><u>[Updated] 2024 Approved Economical Systems Optimized by Ideal OBS Settings</u></a></li>
<li><a href="https://win-workspace.techidaily.com/desktop-users-manual-easily-access-and-enjoy-instagram-reels-without-a-mobile-device/"><u>Desktop Users' Manual: Easily Access and Enjoy Instagram Reels Without a Mobile Device</u></a></li>
<li><a href="https://win-workspace.techidaily.com/effortless-techniques-for-transforming-word-docs-into-portable-pdf-format/"><u>Effortless Techniques for Transforming Word Docs Into Portable PDF Format</u></a></li>
<li><a href="https://win-workspace.techidaily.com/effortlessly-shifting-itunes-audio-content-to-your-smartphone-a-comprehensive-tutorial/"><u>Effortlessly Shifting iTunes Audio Content to Your Smartphone - A Comprehensive Tutorial</u></a></li>
<li><a href="https://android-unlock.techidaily.com/full-guide-to-unlock-your-vivo-v29-pro-by-drfone-android/"><u>Full Guide to Unlock Your Vivo V29 Pro</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-catchemall-celebrate-national-pokemon-day-with-virtual-location-on-realme-v30t-drfone-by-drfone-virtual-android/"><u>In 2024, CatchEmAll Celebrate National Pokémon Day with Virtual Location On Realme V30T | Dr.fone</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/in-2024-economic-approaches-to-online-educational-broadcasting/"><u>In 2024, Economic Approaches to Online Educational Broadcasting</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/lights-camera-action-mastering-fundamental-shots-first-for-2024/"><u>Lights, Camera, Action! Mastering Fundamental Shots First for 2024</u></a></li>
<li><a href="https://tiktok-video-files.techidaily.com/mastering-maplestory-troubleshooting-fix-crashes-on-windows-11-for-gamers/"><u>Mastering MapleStory Troubleshooting – Fix Crashes on Windows 11 for Gamers</u></a></li>
<li><a href="https://win-workspace.techidaily.com/seamless-transition-guide-how-to-move-your-data-effortlessly-from-ios-to-android/"><u>Seamless Transition Guide: How to Move Your Data Effortlessly From iOS to Android</u></a></li>
<li><a href="https://win-workspace.techidaily.com/speedy-methods-for-extracting-background-from-images-on-an-iphone-a-step-by-step-guide/"><u>Speedy Methods for Extracting Background From Images on an iPhone: A Step-by-Step Guide</u></a></li>
<li><a href="https://techidaily.com/things-you-dont-know-about-honor-play-8t-reset-code-drfone-by-drfone-reset-android-reset-android/"><u>Things You Dont Know About Honor Play 8T Reset Code | Dr.fone</u></a></li>
<li><a href="https://some-skills.techidaily.com/unlocking-full-access-to-itunes-radio-features-for-2024/"><u>Unlocking Full Access to iTunes Radio Features for 2024</u></a></li>
<li><a href="https://howto.techidaily.com/want-to-uninstall-google-play-service-from-samsung-galaxy-s23-here-is-how-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Want to Uninstall Google Play Service from Samsung Galaxy S23? Here is How | Dr.fone</u></a></li>
</ul></div>

