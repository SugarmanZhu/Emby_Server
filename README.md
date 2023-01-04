# Emby_Server

Emby is a media server designed to organize, play, and stream audio and video to a variety of devices.

I hosted my Emby server on a NAS. 


## Access the Server


### Using Emby Client

#### Step 1

Download Emby Client at: https://emby.media/download.html (Emby Apps & Devices section)

#### Step 2

Enter the following details:

Host: emby.zhuxiaotan.com

Port: 443 (or 80)

![image](https://user-images.githubusercontent.com/31754434/206093016-2f9459e9-eeb2-43aa-aba0-0ad2a29f7f05.png)

#### Step 3

Enter your account details:

![image](https://user-images.githubusercontent.com/31754434/206093557-d9d701ef-5d31-4d39-ab5e-4f5464bfb203.png)

#### Step 4

Enjoy

![image](https://user-images.githubusercontent.com/31754434/206093752-3d4b954c-4cd3-49a5-bd03-ee77b983b12f.png)


### Using Browser

#### Step 1

Navigate to https://emby.zhuxiaotan.com or http://emby.zhuxiaotan.com

#### Step 2

Enter your account details:

![image](https://user-images.githubusercontent.com/31754434/206094014-087cd737-bd62-47cb-a7e6-03ef52609b46.png)

#### Step 3

Enjoy

![image](https://user-images.githubusercontent.com/31754434/206094213-d5e02eaf-9b4c-4c6e-b5d3-19296cbd96c3.png)

Note: Your browser might not be able to play certain file formats, which could lead to problems with the video and audio. It is advised to access via Emby's App instead. You may also try linking your own player (VLC, PotPlayer, IINA, etc.) to your browser to solve the problem. [See 'There is video but no sound' section in FAQ](#there-is-video-but-no-sound).


## FAQ

### Got Emby Therater Visual C++ Runtime Library Error

In the Emby Theater app, navigate to App Settings -> Video -> Video output -> Select gpu-next.

![image](https://user-images.githubusercontent.com/31754434/206095819-7ba5b06a-8ade-442c-9775-54adbf894808.png)

See https://emby.media/community/index.php?/topic/114059-emby-theater-error/&do=findComment&comment=1206462


### There is video but no sound

This issue may occur when playing MKV videos in browsers. This is due to the fact that the majority of browsers do not natively support MKV files.

Playing the video in a video player will help you solve this problem. You could try the [Open in VLC™ plugin](https://chrome.google.com/webstore/detail/open-in-vlc-media-player/ihpiinojhnfhpdmmacgmpoonphhimkaj?hl=en) on Google Chrome.
