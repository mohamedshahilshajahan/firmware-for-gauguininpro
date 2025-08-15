<h1># Xiaomi Mi 10i 5G (gauguininpro) Custom Firmware for Custom ROM Installation Guide #</h1>
<h3>## Disclaimer ##</h3>
<p>**Note:** Flashing custom ROMs involves potential risks, and you may void your warranty. Follow these instructions at your own risk. Ensure that you understand the process and have backed up essential data before proceeding.<br>
* I am not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.<br> Please do some research if you have any concerns about features included in this ROM before flashing it!<br> YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you.
</p>
<h2></h2>
<h3>## Prerequisites ##</h3>
<h4>1. Unlock the bootloader of your Xiaomi Mi 10i 5G.<br><br>
2. Download the latest <a href="https://developer.android.com/tools/releases/platform-tools">platform-tools (ADB tools)</a> on your PC. <br><br>
3. Visit the official Xiaomi firmware website: <a href="https://xiaomifirmwareupdater.com/firmware/gauguin/">Gauguin Official Firmware</a> and Download the latest MIUI fastboot firmware for your region. <br><br>
<a href="https://xiaomifirmwareupdater.com/firmware/gauguin/" target="_blank">
  <img src="https://i.postimg.cc/Y0nk6w6J/official.png" alt="Official firmware website" style="max-width: 100%; height: auto;" />
</a><br><br>
4. Download the latest custom recovery for a particular latest custom ROM.
</h4>
<h2></h2>
<h3>## Installing/Boot Custom Recovery ##</h3>
<p>1. Boot your Xiaomi Mi 10i 5G into fastboot mode (bootloader mode).<br><br>
2. Connect your device to your PC.<br><br>
3. Open a command prompt or terminal window on downloaded platform-tools {ADB tools} directory.<br><br>
4. Verify the proper connection of your device in fastboot mode with the command:
  
    fastboot devices  
<br>5. Use the following command to temporarily boot into the custom recovery: 
  
    fastboot boot <path-to-custom-recovery-image>
  
  Replace `path-to-custom-recovery-image` with the actual path to the custom recovery image.<br>
<br>
<h3>(or)</h3>
<br>
6. Use the following command to Install the custom recovery: 
 
    fastboot flash recovery <path-to-custom-recovery-image>
    
   Replace `<path-to-custom-recovery-image>` with the actual path to the custom recovery image.<br>
<br>
7. On Custom Recovery, go to Apply update > Apply from ADB.<br><br>
8. Ensure the correct connection of your device in adb mode by executing the command: 

    adb devices
<br>    
9. Flash the firmware through ADB sideload by running

    adb sideload <path/to/firmware.zip>

   Replace `<path/to/firmware.zip>` with the actual path to the official firmware image.
</p>
<h2></h2>
<h3>## Firmware Not Working ##</h3>
<p>**If you encounter an issue with the official firmware being incompatible<br> (e.g., "This package is for gauguin. This is gauguininpro"),<br> like shown in the image below, follow the steps below to make necessary tweaks.**<br><br>
<a href="https://xdaforums.com/t/rom-14-official-pixelos-aosp-stable-23-12-2023.4456563/post-89234133" target="_blank">
  <img src="https://i.postimg.cc/XqccmkjW/error.png" alt="Official firmware website" style="max-width: 100%; height: auto;" />
</a>
</p>
<h3>## I already Tweaked the latest Indian firmware for Mi 10i 5G (gauguininpro) ##</h3>
<p>
Download the tweaked firmware for gauguininpro from the following links:

* [Mediafire](https://www.mediafire.com/file/qd6gohdh17skvfy/firmware.zip/file)
* [GDrive](https://drive.google.com/file/d/1mb8QdpCQxMlF8zmnSSe7wgePzBRxqUM9/view?usp=sharing)
* [Dropbox](https://www.dropbox.com/scl/fi/cm2uvxlyqohlzwrin3kcj/firmware.zip?rlkey=l8vcgjdmb10ob113jxm3becaa&dl=0)
</p>
<h2></h2>
<h3>## How I Tweak the Firmware ##</h3>
<h3>1. Extract the downloaded firmware ZIP file.<br>
<br>2. Navigate to the extracted firmware folder.<br>
  
<br>3. Open the `meta-inf/com/google/android/updater-script` file using a text editor (e.g., 'notepad++').<br><br>
<img src="https://i.postimg.cc/4ykTWMzL/updater-script.png" alt="updater-script image" style="max-width: 100%; height: auto;"><br>
<br>4. Change instances of 'gauguin' to 'gauguininpro' in the `updater-script` file.<br>
<br>5. Open the `meta-inf/com/android/metadata` file using a text editor (e.g., 'notepad++').<br><br>
<img src="https://i.postimg.cc/QtW3ksWK/metadata.png" alt="metadata image" style="max-width: 100%; height: auto;"><br>
<br>6. Change instances of 'gauguin' to 'gauguininpro' in the `metadata` file.<br>
<br>7. Save the changes.
</h3>
<h2></h2>
<h3>## Flashing the Tweaked Firmware ##</h3>
<p>1. Boot your Xiaomi Mi 10i 5G into fastboot mode (bootloader mode).<br>
<br>2. Connect your device to your PC.<br>
<br>3. Open a command prompt or terminal window on downloaded platform-tools {ADB tools} directory.<br>
<br>4. On Custom Recovery, go to Apply update > Apply from ADB.<br>
<br>5. Flash the firmware through ADB sideload by running: 
         
    adb sideload <path/to/firmware.zip>

  Replace `<path/to/firmware.zip>` with the actual path to the tweaked firmware image.<br><br>
<img src="https://i.postimg.cc/HjGWQyc7/firmwarecompleted.png" alt="Firmware Installed Successfully" style="max-width: 100%; height: auto;" /><br>
<br>6. Once the flashing is complete, now flash the downloaded custom ROM.
</p>
<h2></h2>
<h3>About me:</h3> <h1 align="center"><a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=30&pause=1000&color=1AF7E6&multiline=true&width=650&lines=Hi%F0%9F%98%8E%2C+I+am+Mohamed+Shahil+Shajahan" alt="Typing SVG" /></a></h1>

 <h3 align="center">🚀 Open-Source & Freelance Developer | Turning Ideas into Tools</h3>

<h4 align="center">💡 Passionate about building practical, smart, and user-friendly solutions.</h4>

<h3 align="center">
  With a foundation in tech and a love for problem-solving, Currently learning Windows app development, building automation with Google Apps Script, and experimenting with new ways to make technology more useful.<br><br>
  
  🛠️ From simple productivity tools to efficient desktop utilities, I enjoy crafting solutions that just work.<br>
  🌐 Open source is my playground — I believe in sharing knowledge and collaborating to create better tech for everyone.<br>
  📚 Always learning, always improving — because great software is built on curiosity and persistence.
</h3>

<h3 align="center">
  Let’s build something awesome together — one project at a time. 🤝
</h3>

<h2 align="center">#OpenSource #FreelanceDeveloper #GoogleAppsScript #Automation #TechEnthusiast</h2>

<p align="left">
  <img 
    src="https://komarev.com/ghpvc/?username=mohamedshahilshajahan&label=Profile%20views&color=blueviolet&style=flat" 
    alt="mohamedshahilshajahan" 
    width="200" 
    height="40" 
  />
</p>

<img align="right" alt="Coding" width="300" src="https://i.postimg.cc/CL981DpX/DEVELOPER.gif">

<table border="0" cellspacing="0" cellpadding="0">
  <tr>
    <td valign="top">
      <h3 align="left">Connect with me:</h3>
      <p align="left">
        <a href="https://www.linkedin.com/in/mohamedshahilshajahan" target="_blank" rel="noreferrer">
          <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://i.postimg.cc/02ZQ9ft7/linkedin-dark.png" />
            <source media="(prefers-color-scheme: light)" srcset="https://i.postimg.cc/XvKFcFjL/linkedin.png" />
            <img src="https://i.postimg.cc/XvKFcFjL/linkedin.png" width="35" height="auto" />
          </picture>
        </a>
        &nbsp;
        <a href="https://www.github.com/mohamedshahilshajahan" target="_blank" rel="noreferrer">
          <picture>
            <source media="(prefers-color-scheme: dark)" srcset="https://i.postimg.cc/Bn6vbKyk/github-dark.png" />
            <source media="(prefers-color-scheme: light)" srcset="https://i.postimg.cc/LsFL1vph/github.png" />
            <img src="https://i.postimg.cc/LsFL1vph/github.png" width="32" height="32" />
          </picture>
        </a>
      </p>
    </td>
    <td valign="top">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohamedshahilshajahan&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact" />
    </td>
  </tr>
</table>

<h3 align="left">Support:</h3>

<div align="left" style="display: flex; gap: 10px; justify-content: center; flex-wrap: wrap;">
  <a href="https://www.buymeacoffee.com/jazzboss@upi">
    <img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="50" width="210" alt="jazzboss@upi" />
  </a>
  <a href="https://paypal.me/MohamedShahil">
    <img src="https://img.shields.io/badge/PayPal-00457C?style=for-the-badge&logo=paypal&logoColor=white" height="50" width="210" />
  </a>
</div>


<p>
</p>

# 💻 Tech Stack:
![C](https://img.shields.io/badge/c-%2300599C.svg?style=flat&logo=c&logoColor=white) ![C++](https://img.shields.io/badge/c++-%2300599C.svg?style=flat&logo=c%2B%2B&logoColor=white) ![Windows Terminal](https://img.shields.io/badge/Windows%20Terminal-%234D4D4D.svg?style=flat&logo=windows-terminal&logoColor=white) ![Python](https://img.shields.io/badge/python-3670A0?style=flat&logo=python&logoColor=ffdd54) ![PowerShell](https://img.shields.io/badge/PowerShell-%235391FE.svg?style=flat&logo=powershell&logoColor=white) ![Markdown](https://img.shields.io/badge/markdown-%23000000.svg?style=flat&logo=markdown&logoColor=white) ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=flat&logo=openjdk&logoColor=white) ![Adobe Audition](https://img.shields.io/badge/Adobe%20Audition-9999FF.svg?style=flat&logo=Adobe%20Audition&logoColor=white) ![Adobe Photoshop](https://img.shields.io/badge/adobe%20photoshop-%2331A8FF.svg?style=flat&logo=adobe%20photoshop&logoColor=white) ![Canva](https://img.shields.io/badge/Canva-%2300C4CC.svg?style=flat&logo=Canva&logoColor=white) ![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=flat&logo=github&logoColor=white) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat&logo=git&logoColor=white) ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat&logo=Arduino&logoColor=white) ![OpenSea](https://img.shields.io/badge/OpenSea-%232081E2.svg?style=flat&logo=opensea&logoColor=white) ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=flat&logo=powerbi&logoColor=black) ![Tampermonkey](https://img.shields.io/badge/tampermonkey-%2300485B.svg?style=flat&logo=tampermonkey&logoColor=white) ![TOR](https://img.shields.io/badge/tor-%237E4798.svg?style=flat&logo=tor-project&logoColor=white)

