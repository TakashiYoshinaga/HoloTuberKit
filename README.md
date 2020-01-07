# HoloTuber Kit
This is a simple volumetric video capture &amp; AR visualization kit. Real-time 3D image is reconstructed from RGB-D images wihch are broadcasted via YouTube.<br>
[![](https://img.youtube.com/vi/IeaHt6bBw1o/0.jpg)](https://www.youtube.com/watch?v=IeaHt6bBw1o)
<br>
# Files Included
## Hologram Viewer
Following version of hologram viewer application are avairable on Android devices.<br>
・ARCore <br>
・Vuforia<br>
・Aryzon<br>

## Hologram Capture
This application captures RGB and Depth image from Azure Kinect and generates RGB-D merged image to send YouTube.<br>
You can use normal version or middle resolution version. (Please note the middle resolution version is not stable so far)<br>
To broadcast hologram, OBS Studio and your own YouTube account are also necessary.<br>
OBS Studio: https://obsproject.com/ja/download  <br>
YouTube: https://www.youtube.com/  <br>
<br>
# How to Live Streaming with Capture Application
## Sending Hologram (PC -> YouTube)
0) Set display scale to 100% in display setting of Windows.<br>
1) Download and unzip  <b>AzureKinectCapture.zip</b> <br>
2) Copy all files inclued in the directry of Azure Kinect SDK.<br>
  <i>C:\Program Files\Azure Kinect SDK v1.3.0\sdk\windows-desktop\amd64\release\bin</i><br>
  This application works with <b>AzureKinect 1.3!</b><br>
3) Connect a Azure Kinect with a PC.<br>
4) Launch <b>KinectCapture4PC.exe</b>.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/01.jpg" alt="" width="400"><br>

5) Open and login YouTube<br>
6) Click <b>Go live</b> button <br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/03.jpg" alt="" width="400"><br>
7) Click <b>CREATE STREAM</b> button after finishing to input a name of the streaming and set some propertis.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/04.jpg" alt="" width="400"><br>
8) Copy <b>Stream name</b><br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/05.jpg" alt="" width="400"><br>

9) Launch <b>OBS Studio</b>.<br>
10) Open Settings<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/02.jpg" alt="" width="400"><br>
11) Open <b>Stream</b> and select <b>YouTube</b>, <b>Primary TouTube ingest serever</b>.<br>
12) Paste Streaming Key which you copied earlier.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/06.jpg" alt="" width="400"><br>
13) Open <b>Video</b> to set resolution referring to following information.<br>
   <b>Base Resolution</b> : 960x432<br>
   <b>Output Resolution</b> : 960x432<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/07.jpg" alt="" width="400"><br>
14) Click Add button of Source area placed lower area.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/08.jpg" alt="" width="400"><br>
15) Click <b>Window Capture</b>.<br>
16) Click OK.<br>
17) Select <b>[KinectCapture4PC.exe]: Viwer</b> from Window.<br>
18) Clik OK.<br>
    <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/10.jpg" alt="" width="400"><br>
19) Click <b>Start Streaming</b><br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/11.jpg" alt="" width="400"><br>
20) Back to YouTube Live and click <b>Go Live</b> afater aroud 1min.<br><br>


## Receiving Hologram(YouTube -> Smartphone)
1) Check the URL of the Streaming.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/12.jpg" alt="" width="400"><br>
2) Launch application on your smartphone.<br>
3) Tap input text field and input URL of your YouTube live.<br>
   <img src="https://github.com/TakashiYoshinaga/HoloTuberApplication/blob/master/Images/13.jpg" alt="" width="400"><br>
4) Tap Connect button.

# Give Me Your Feedback
I'm glad if you'll give me feedback, or tag me when you share the video of your experience on SNS or other web-media.<br><br>
<b>Contact Me</b><br>
Twitter: @Tks_Yoshinaga (https://twitter.com/Tks_Yoshinaga)<br>
LinkedIn: Takashi Yoshinaga (https://www.linkedin.com/in/tks-yoshinaga/?locale=en_US)<br>
<br>
# If you want to develop application...
Please refer following material.
<script async class="speakerdeck-embed" data-id="9654031e9bfd4e4fbaeeef4f75a00b47" data-ratio="1.33333333333333" src="//speakerdeck.com/assets/embed.js"></script>
