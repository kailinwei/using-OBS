---
layout: default
title: Streaming
nav_order: 3
---
 
# Streaming #

Now that you finished the basic setup of OBS studio, you can start to stream your screen using the streaming website using Twitch or YouTube. The OBS Studio has provided various plugins and more functions than a basic streaming site. We will show you how to connect OBS Studio with the streaming site in two versions with useful plugins.

### Task 2.1 Connect To Streaming Website ###

**1.** Click the **Settings** button which shows all setting options on the bottom of right.
![_INSERT IMAGE 2.1.1_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.1.1.png?raw=true "Click Settings")    

**2.** Click the **Stream** button on the left side. 

<em>**Note**: In this window, you can choose a streaming service that you want to use. We will use Twitch and YouTube in this instruction.</em>

![_INSERT IMAGE2.1.2_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.1.2.png?raw=true "Click Stream")

**3.** Select streaming service you want to broadcast. (Twitch or YouTube - RTMP)

![_INSERT IMAGE2.1.3_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.1.3.png?raw=true "Click Streaming Service")

* Twitch

    
    You should have an account to use the streaming service.


![_INSERT IMAGE2.1.4_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.1.4.png?raw=true "Twitch")


* Youtube

    You should have an account and verify your phone number, If you did not when you make your account.

![_INSERT IMAGE2.1.5_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.1.5.png?raw=true "YouTube") 

<em>**Note**: If you get a verification with your number at this step, You can use streaming service after 24 hours following the YouTube streaming rule.</em>


**4.** Click the **Get Stream Key** to get your stream key that connects to the streaming site and OBS studio. 
When you click the **Get Stream Key** button, you will be directed to the streaming website. 

![_INSERT IMAGE2.1.6_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.1.6.png?raw=true "Get Stream Key")

**5.** Copy the Primary stream key and paste it on the Stream Key section on OBS.

<em>**Note**: If you don’t go to this web page, you should log in first and click it again.</em>


![_INSERT IMAGE2.1.7_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.1.7.png?raw=true "Copy And Paste")

Now, we finished making connections between OBS studio and the streaming website. You can start streaming with **Start Streaming** button on the bottom right.


### Task 2.2 Set Up Your Display Screen ###

The following steps only appear for connection to streaming website. There is no streaming source on the screen yet, so if you clicked the Start Streaming button in the previous step, you will be broadcasting only a black screen.

Now, We will guide you through how to add a display source and web camera to your streaming screen. 


**1.** Go back to the main screen and click the **+** button on the Sources tap.

![_INSERT IMAGE2.2.1_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.2.1.png?raw=true "Click + button")

**2.** Click the **Display Capture** Button to add a screen you want to display first. 

![_INSERT IMAGE2.2.2_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.2.2.png?raw=true "Click Display Capture")

**3.** Choose a display option which you want to stream and click OK.

![_INSERT IMAGE2.2.3_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.2.3.png?raw=true "Choose Display")

<em>**Note**: If you use a single monitor, you don’t need to choose the display option. </em>

**4.** Click your right mouse button on the left screen. 

You can transform the display with several options. These options allow the user to rotate or edit the screen display.


![_INSERT IMAGE2.2.4_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.2.4.png?raw=true "Transform Screen")



**5.** Click **Video Capture Device** to add your webcam. 


![_INSERT IMAGE2.2.5_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.2.5.png?raw=true "Click Video Capture Device")

You can change the name if you want.

**6.** Select the camera device that you want to use on the Device tab and click OK.


![_INSERT IMAGE2.2.6_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.2.6.png?raw=true "Select Camera")

**7.** Resize the size of the second screen and move the location if you want.

![_INSERT IMAGE2.2.7_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.2.7png.png?raw=true "Resize")

<em>**Note**: We blurred our web-camera screen by using a photo edit program on purpose, you will get the clear screen.</em>

If you want to add more sources to your screen, you can do this later anytime with a source tap.
You can design your screen with any source you want to apply on the source tab.
A short explanation about each function is in the below table:

|      |**Explanation**  |
|:----:|:-----------------:|
|**Audio Input Capture**|Add audio sounds with a device that send audio signals to a computer such as a microphone |
|**Audio Output Capture**|Add audio sounds with a device that attaches to a computer such as a speaker|
|**Browser**|Show a webpage from your browser tab |
|**Color Source**|Add a color block as your background on the screen|
|**Display Capture**| Show everything that is on our computer screen |  
|**Image**| Show an image file stored in your computer|
|**Media Source**|Steam a Media file such as video|    
|**Scene**| Add another scene on your activated scene|  
|**Syphon Client**|Show a game screen you are playing |  
|**Text**| Write a text with font style, color and size on the screen|  
|**Video Capture Device**|Show a video camera screen with a device that attaches to a computer|  
|**Window Capture**|Show a certain application display on a computer such as PhotoShop|  


If you have trouble with **Audio Output Capture**, Please check out [Trouble Shooting](https://kailinwei.github.io/using-OBS/docs/troubleshooting/).

You can see the details about the **Scene** in [Studio mode](https://kailinwei.github.io/using-OBS/docs/studio/).


**8.** Click the **Transition** button after you set up your streaming screen.

<em>**Note**: The **left screen** is the screen you can edit and the **right screen** is the one that will show on streaming. </em>

![_INSERT IMAGE2.2.8_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.2.8.png?raw=true "Click Transition")

![_INSERT warning](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/caution.png?raw=true "Warning"){: style="float: left" }

**WARNING**: You should click the transition button after you change on the left screen.

<br />
<br />

**9.** Click the **Start Streaming** button to start your streaming.


![_INSERT IMAGE2.2.9_](https://github.com/kailinwei/using-OBS/blob/gh-pages/assets/images/task2.2.9.png?raw=true "Start Streaming")


Congratulations! You are finished setting up for streaming with OBS studio. As you've learned now, you can organize your screen with a source panel and choose any streaming service on the setting.

Next, you can record your live video with start [recording](https://kailinwei.github.io/using-OBS/docs/recording/) or use more functions for your streaming with [studio mode](https://kailinwei.github.io/using-OBS/docs/studio/). 

