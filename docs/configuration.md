---
layout: default
title: Download and Set up
nav_order: 2
---

# Downloading and Set up #

## Downloading ##

We will demonstrate how to download the OBS Studio website from the beginning and explain the settings you will want to do along the downloading process.

### Task 1.1 Downloading ###

**1.** Go to [OBS Studio website](https://obsproject.com/) 
![_INSERT IMAGE 1.1_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task1.1.png?raw=true "OBS Studio Website")

**2.** Select **macOS 10.13** , this will start downloading OBS software on your laptop. The downloading file will appears at the bottom part of your browser.  
_INSERT IMAGE1.2_

**3.** Click on the file when download is finished, to opening the downloaded software files. A small window will pop up to show the verification.  When the verification process is done, a small window will show up.
_INSERT IMAGE 1.3_

**4.** Select the **OBS.app** icon and drag it to the **Applications** icon. This step will help you move the downloaded files from **Download** folder to **Application** folder.  
![_INSET IMAGE 1.4_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task1.4.1.png?raw=true "Drag to application")
_INSERT IMAGE 1.5_

**5.** Go to your application folder and select the **OBS.app** to open the software. Since we just downloaded this app, we need some additional steps to set it up. These steps will not appears after the first time use.  

**6.** Select "**Open**" when  window pop up to confirm if we want to open this newly downloaded app.  
![_INSERT IMAGE 1.6_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task1.6.png?raw=true "Select Open")
Then,a new window appears to ask you granting OBS access in Security & Privacy.

**7.** Select "**Open System Preference**"
  ![_INSERT IMAGE 1.7_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task1.7.png?raw=true "Select Open system preference")

**8.** Select "**OK**"for giving OBS access to microphone.
   ![ _INSERT IMAGE 1.8_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task1.8.png?raw=true "Select Ok to obtain microphone permission")

Now, we finished giving OBS our access to necessary functions. We are ready to do some initial set up with the OBS software.

### Task 1.2 Initial OBS Set up ###

The following steps only appear for the first time downloading. We will guide you through about how to make the initial selections for the settings. If you want to change the settings later, you can always go to setting selection in the app and make changes.

When you open the OBS Studio software first time after finishing downloading, a window will appear to ask you to choose the program you would like to use. For the purpose of showing both of the streaming and recording functions, we will choose the first option. You can choose the second one if you only want to record. Choose the third option if you only use the virtual camera. You can always change the setting in **Tools** later if you would like to switch to a different program.  

**1.** Click the first option, then click **Next**
_image1.2.1_  

Then, a window appears to ask you choosing the Base(Canvas) Resolution and the FPS.

>* Base(Canvas) Resolution means the resolution of the space you use to layout your overlays in OBS. In general, the bigger the number, the better the video quality. However, when you are using streaming function, the high resolution may cause lagging problems. It is recommended to use a **16:9** aspect ratios. Hence, the resolutions of  **1920 x 1080** and **1280 x 720** are recommended.  </br>
>* FPS stands for frame per second, which means how fast a image is shown. 60FPS looks smooth when streaming, but it require extra work from your GPU or CPU to keep up. If you have a solid stream PC and the upload speed to match, 60FPS is recommended, because it look better. If not, 30 FPS is a reliable choices as it provide a clean video.

In this instruction, we set Base(Canvas) Resolution or 1920 x 1080, and FPS for "Either 60 or 30 but prefer 60 when possible" which is more flexible choice.

**2.** Click **Next** after you finishing choose the setting.  
_image1.2.2_

After that, a window pops up to set up your streaming information. You can choose your streaming services, server and the video bitrate.

Video bitrate means how many bits of data you are sending and the speed they are being sent. It should be determined by video resolution, video frame rate, upload bandwidth available and more. You can use this table to determine the bitrate to use:

|      |**Video Bitrate**  |**Audio Bitrate**  |**Resolution**  |
|:---:|:---:|:---:|:---:|
|**1080P**|6,000Kbps|128Kbps|1920×1080|
|**720P**|3,000Kbps	|128Kbps|1280×720|
|**480P**|1,000Kbps|128Kbps|854×480|
|**360P**|600Kbps|96Kbps|640×360|
|**240P**|300Kbps|96Kbps|426×240|


<br>
**3.** Click on **Service**, you will see many services options. Choose the one you would like to use. For this manuel, we will choose **Twitch** as an example.  

**4.** Enter your Stream Key of your selected service. Select the recommended default server.

**5.** Select your server. We will use Auto (Recommend) in this instruction.

**6.** Select your video bitrate and then choose **Next**.
 _image1.2.3_  

A window will pops up showing the configuration process. 

**7.** Choose **Apply Settings** when the configuration process finished
 _image1.2.4_

Then, the screen shows up and you are ready to use OBS Studio functions!
_image1,2,5_

Please refer to the next chapter for how to record and stream your video!
