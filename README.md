<h1># Xiaomi Mi 10i 5G (gauguininpro) Custom Firmware for Custom ROM Installation Guide</h1>
<h3>## Disclaimer</h3>
<p>**Note:** Flashing custom ROMs involves potential risks, and you may void your warranty. Follow these instructions at your own risk. Ensure that you understand the process and have backed up essential data before proceeding.<br>
* I am not responsible for bricked devices, dead SD cards, thermonuclear war, or you getting fired because the alarm app failed.<br> Please do some research if you have any concerns about features included in this ROM before flashing it!<br> YOU are choosing to make these modifications, and if you point the finger at me for messing up your device, I will laugh at you.
</p>
<h2></h2>
<h3>## Prerequisites</h3>
<h4>1. Unlock the bootloader of your Xiaomi Mi 10i 5G.<br><br>
2. Download the latest <a href="https://developer.android.com/tools/releases/platform-tools">platform-tools (ADB tools)</a> on your PC. <br><br>
3. Visit the official Xiaomi firmware updater website: <a href="https://xiaomifirmwareupdater.com/firmware/gauguin/">Xiaomi Firmware Updater</a> and Download the latest MIUI fastboot firmware for your region. <br><br>
4. Download the latest custom recovery for a particular latest custom ROM.
</h4>
<h2></h2>
<h3>## Installing/Boot Custom Recovery</h3>
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
<h3>## Firmware Not Working</h3>
<p>**If you encounter an issue with the official firmware being incompatible (e.g., "This package is for gauguin. This is gauguininpro"),<br> like shown in the image below, follow the steps below to make necessary tweaks.**<br>
<img src="https://i.postimg.cc/XqccmkjW/error.png" alt="Firmware Error" style="max-width: 100%; height: auto;">
</p>
<h3>## I already Tweaked the latest Indian firmware for Mi 10i 5G (gauguinpro)</h3>
<p>
Download the tweaked firmware for gauguinpro from the following links:

* [Google Drive](https://drive.google.com/file/d/1v_b1hnwgxA_X7NMkSdaHDLGC_eM1aFka/view?usp=sharing)
* [Dropbox](https://www.dropbox.com/scl/fi/cm2uvxlyqohlzwrin3kcj/firmware.zip?rlkey=l8vcgjdmb10ob113jxm3becaa&dl=0)
</p>
<h2></h2>
<h2>## How I Tweak the Firmware</h2>
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
<h2>About me:</h2>
<h1 align="center" href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=30&pause=1000&color=F7DC00&center=true&vCenter=true&random=false&width=550&height=32&lines=Hi+%F0%9F%91%8B%2C+I'm+Mohamed+Shahil" alt="Typing SVG" /></h1>

<h3 align="center">A passionate software enthusiast diving into the exciting world of development!<br>
  <h4 align="center">🚀 As a recent graduate with a Diploma in ECE (2018),</h4> <h3 align="center">I am eager to establish a robust foundation in Software Development, focusing on Python, Java, C, and C++.<br>
  💡 My journey is just beginning, and I've already taken my first steps by creating a project.<br>
  🛠️ As a beginner, I'm committed to continuously enhancing my skills and contributing to the ever-evolving tech landscape.<br>
  🌐 I'm thrilled about the endless possibilities in software development and am dedicated to mastering the intricacies of coding.</h3>
  <h3 align="center">My goal is to build a solid skill set that not only meets industry standards but also pushes the boundaries of innovation.<br>
  📚 Lifelong learning is my mantra, and I believe in the power of collaboration. Let's connect, learn, and grow together on this coding adventure! 🤝 </h3>
  
 <h2 align="center"> #CodeNewbie #Python #Java #Cplusplus #SoftwareDevelopment #TechEnthusiast</h2>

<p align="left"> <img src="https://komarev.com/ghpvc/?username=mohamedshahilshajahan&label=Profile%20views&color=0e75b6&style=flat" alt="mohamedshahilshajahan" /> </p>
<img align="right" alt="Coding" width="400" src="https://cdn.dribbble.com/users/1162077/screenshots/3848914/programmer.gif">
- 📫 You can contact me at **mohamedshahilshajahan@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left"> <a href="https://www.linkedin.com/in/mohamedshahilshajahan" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://i.postimg.cc/02ZQ9ft7/linkedin-dark.png" /> <source media="(prefers-color-scheme: light)" srcset="https://i.postimg.cc/XvKFcFjL/linkedin.png" /> <img src="https://i.postimg.cc/XvKFcFjL/linkedin.png" width="35" height=auto />&nbsp; </picture> </a><a href="https://www.github.com/mohamedshahilshajahan" target="_blank" rel="noreferrer"> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://i.postimg.cc/Bn6vbKyk/github-dark.png" /> <source media="(prefers-color-scheme: light)" srcset="https://i.postimg.cc/LsFL1vph/github.png" /> <img src="https://i.postimg.cc/LsFL1vph/github.png" width="32" height="32" /> </picture> </a> </p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <img src="https://i.postimg.cc/DZdk7s4J/c.png" alt="c" width="40" height=auto/>&nbsp;&nbsp;<img src="https://i.postimg.cc/br37thTq/cplus.png" alt="cplusplus" width="40" height=auto/>&nbsp;&nbsp;<img src="https://i.postimg.cc/0jkgjQ7t/java.png" alt="java" width="40" height=auto/>&nbsp;&nbsp;<img src="https://i.postimg.cc/T20MSVXB/python.png" alt="python" width="40" height=auto/> </p>
