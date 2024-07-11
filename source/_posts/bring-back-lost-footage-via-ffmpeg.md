---
title: Bring Back Lost Footage via FFmpeg
date: 2024-07-10T06:47:07.951Z
updated: 2024-07-11T06:47:07.951Z
categories:
  - repair-tools
description: This Article Describes Bring Back Lost Footage via FFmpeg
excerpt: This Article Describes Bring Back Lost Footage via FFmpeg
keywords: FFmpeg Video Conversion,Lost Footage Recovery,FFmpeg Lossless Video Restoration,Advanced FFmpeg Techniques for Lost Footage,Efficient Video Conversion with FFmpeg,FFmpeg Footage Salvaging Techniques,bring back lost footage via ffmpeg
thumbnail: https://thmb.techidaily.com/dbece127b3474bfee03fecc83648c4194241691bdbde80d7fc24eae5256f2a38.jpg
---

## Bring Back Lost Footage via FFmpeg

[Video Repair](https://tools.techidaily.com/stellardata-recovery/buy-now/)

# How to Repair Corrupt Video Files using FFmpeg

* ![Written By](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/desktop/optimized/rev-636f8fd/secure.gravatar.com/avatar/51230a434c190250f4ff6504ca157fb6.1e1df7d66b301003bec30db63ac73954)  
 Written By [Sumona Chatterjee](https://tools.techidaily.com/stellardata-recovery/buy-now/) [linkdin](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-636f8fd/www.stellarinfo.com/public/frontEnd/images/author/linkdin.jpg) ](https://www.linkedin.com/in/sumona-chatterjee-38984450/)
* ![Date](https://cdn-cmlep.nitrocdn.com/DLSjJVyzoVcUgUSBlgyEUoGMDKLbWXQr/assets/images/optimized/rev-636f8fd/www.stellarinfo.com/public/frontEnd/images/author/clender.jpg)  
 Updated on22 May, 2024
* Min Reading 6  Min
* Share

---

Table of Content

> “Can I repair corrupt MOV video files using FFmpeg that became corrupted after I changed settings during recording?”
>
> _“How can I improve sound quality in my 2GB MP3 video file of Canon camcorder by FFmpeg? “_

 Videos need editing or repair to improve quality and enhance the viewing experience. Sometimes, however good in quality, you may just want to edit, cut, sharpen, rotate, add sound or text over them. To do such tasks, there are a plethora of video editing tools. But unlike paid editing platforms, which may not let you do all the activities, FFmpeg is a complete software project for multimedia files. It has a vast suite of libraries and programs that lets you convert, edit, repair, and improve your video formats.

 FFmpeg multimedia framework has its distinct fan following too, owing to its multi-facet utilities.

 Recently, NASA used FFmpeg to combine the high-resolution images taken from the GOES-R series of Earth observation satellites to create a video. While some miles away, the game developer- Looking Glass Studios included FFmpeg video support in its latest Dark Mod Thief game version 2.06.

 Everyone from end users to developers uses open-source FFmpeg to create, convert, record, cut, stream, encode, transcode, mux, demux, and so much more to their videos.

## **How does FFmpeg work?**

 FFmpeg is a command-line tool that uses commands to convert audio or video formats.

 For example: To extract sound from a video and save it as MP3, you can use the command line:

$ ffmpeg -i video1.avi -vn -ar 44100 -ac 2 -ab 192 -f mp3 audio3.mp3

 To increase video playback speed command line is:

$ ffmpeg -i video.mpg -vf "setpts=0.5*PTS" highspeed.mpg

 It can also capture and encode in real-time from various sources such as a TV capture card. FFmpeg comes with a wide range of audio and video codec support. You can use it to fix your video-related issues of any file format on Linux, Mac OS X, Microsoft Windows, the Unix BSDs, and Solaris systems.

## **What you can do with FFmpeg?**

* Decode, encode, transcode, mux, demux, stream, and filter multimedia files
* Convert video to images and images to video
* Scale, pad, crop, flip, rotate, blur, sharpen and de-noise video
* Speed up or slow down audio and video
* Let the computer read the text with the selected voice
* Display and record input from your webcam
* Record input from the microphone or send it to loudspeakers
* Add static or dynamic text to the video
* Add, edit, or delete file metadata
* Preview modified input in 2, 3, or 4 windows
* Include a logo or provide a Picture-in-Picture
* Create sound with mathematical expressions
* Resize video with a high-quality polyphase filter
* Display input from 2 webcams in one window
* Set the bitrate, frame rate, maximum file size, and related options
* Encode subtitles directly to the video stream
* Join various file formats, modify streams, and modify audio channels

## **Can FFmpeg repair corrupt videos?**

 Yes, it can. You can try to repair your video files using various command lines in FFmpeg. But this could be a little tricky for beginners. You should have knowledge of various command lines to perform different tasks in FFmpeg.

 Also, the success of repairing corrupt video files depends upon what issue you want to fix and how badly the file is damaged.

## **How to Repair Corrupt Video Files like MOV, MP4, etc. using FFmpeg?**

 To use FFmpeg you need to open a command prompt window and give specific command lines to fix corruption or inaccessible video problems.

**Step-by-step: How to use FFmpeg to fix corrupt video**

* Download and install FFmpeg on your computer.
* Copy the corrupt video file from a source location to the desktop
* Open Command Prompt using Win+R and type_cmd_ in the box
* In the command prompt window type in_cd Desktop_ and press Enter

* Enter the command line. For example, to convert an MP4 video called ‘Party’ into an AVI file called ‘Birthday’, type in _ffmpeg -i Party.mp4 Birthday.avi_

**Note:** Keep your file name exactly the same including the upper and lower case in the command line.

* Press Enter

 Once the process finishes, you can see the new video file on the Desktop with the file name that you entered (here as_Birthday.avi_)

### **Similarly, you can use different command lines for various actions like below:**

 **1\. To check for corruption in the input.ts stream video file and save the errors in log file:**

_ffmpeg –v error –i corruptedinput.ts -f null - &> corruptions.log_

**2\. To fix the corrupt video file use:**

ffmpeg –i corrupted_input.ts –map –ignore_unknown/-copy_unknown –c copy fixed.ts

**3\. If it’s a corrupt MP4 video:**

ffmpeg -i input.mp4 -c copy output.mp4

 **4\. To fix a WMV video not playing and showing a message video too long:**

 In FFmpeg, first convert the video to still images and then still images back to video.

 First, extract all the frames into JPEG images using the command line:

._\ffmpeg.exe -i ‘.\Video 36.wmv’ -an -f image2 filename%03d.jpg_

**Note:** Remember the number of images created (say for example 99987 images).

Then, extract the audio using:

_.\ffmpeg.exe -i ‘.\Video 36.wmv’ audio.mp3_

 Find the exact duration of the audio by using the command:

_.\ffprobe.exe -i .\audio.mp3 -showentries format=duration -v quiet -printformat json_

You would output something as:

_{    "format": { "duration": "4325.56210"  }}_

 Now calculate the frame rate of the output video to match the audio and video by diving the number of images formed by the audio duration:

 Here 99987 by 4325.56210 = 23.1153\. This is the frame rate for your output video. It is necessary to use the exact number.

Next, use the command line and press Enter:

_.\ffmpeg.exe -framerate_ 23.1153_-f image2 -i .\filename%3d.jpg -codec copy ouputnoaudio.mkv_

 Now, use the command line to mix the audio and video to get the final perfectly playing video:

_.\ffmpeg.exe –i .\outputnoaudio.mkv –i .\audio.mp3 –c copy –map 0:v:0 –map 1:a:0 output.mkv_

### **Other easier programs to repair corrupt videos**

 There are other programs such as video repair tools like **[Stellar Repair for Video](https://tools.techidaily.com/stellardata-recovery/buy-now/)**  ; noise reduction video plugins like **Neat Video or Red Giant Magic Bullet Denoiser** ; video editing software like **Adobe Premiere Pro, Final Cut Pro X, or Lightworks** that can be used to reduce noise and improve video quality.

 However, a dedicated video repair tool for video corruption is always a better choice. They can fix even severely corrupt MP4, MOV, AVI, MKV, and all other important video file formats that are not playable or show errors in loading.

 The free demo version of the software is good enough for evaluating whether a video corruption issue can be resolved.

[](https://cloud.stellarinfo.com/StellarRepairforVideo-B.exe) [](https://cloud.stellarinfo.com/StellarRepairforVideo-B.dmg.zip)

## **How to Repair Corrupt Videos Using Video Repair Software?**

 Are you searching for software to repair broken video files? **[Stellar Repair for Video](https://tools.techidaily.com/stellardata-recovery/buy-now/)**  fixes almost all types of video corruptions that occur during editing, shooting, converting to a different format, or the transfer of videos, etc. It repairs corruption in frames, sound sections, headers, etc. You can play your videos that turned grainy, choppy, jerky, broken, frozen, out of sync, etc.

 Even the severely corrupt video files that are not fixed by FFmpeg or other editing/repair tools can be made playable using Stellar Repair for Video.

 The software can also repair video files created through the FFmpeg program. Moreover, you do not need to fret over the repair process. The advanced algorithms of the software easily fix any damage in the video files.

 It supports the repair of AVI, ASF, WMV, MKV, FLV, DIVX, WEBM, MJPEG, MPEG, AVCHD, MTS, MOV, MP4, M4V, 3G2, 3GP, and F4V video files.

## **Wrapping up**

 Thus by the above-mentioned methods, you can repair corrupt video files using FFmpeg using its command lines. However, for severely corrupt video files, a secure**video repair tool** Stellar Repair for Video is recommended. Unlike FFmpeg, the software works in all kinds of video corruption without you putting in any effort to repair the distorted multimedia file.

### Was this article helpful?

YES 0

NO

About The Author

[Sumona Chatterjee](https://tools.techidaily.com/stellardata-recovery/buy-now/) [](https://www.linkedin.com/in/sumona-chatterjee-38984450/)

 Sumona is a tech blogger, avid photographer, & technogeek with vast experience in writing about media file recovery tips and tutorials. She has over 10 years of experience in media file recovery/media file repair technology. She is passionate about Photography, Creative Designing, Music, and Exploring lesser-known destinations.

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
<li><a href="https://data-wizards.techidaily.com/ensuring-playback-continuity-with-app-video/"><u>Ensuring Playback Continuity with App Video</u></a></li>
<li><a href="https://data-wizards.techidaily.com/diagnosing-video-load-failures/"><u>Diagnosing Video Load Failures</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-pioneering-innovative-webcam-functions/"><u>[Updated] Pioneering Innovative Webcam Functions</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-unveiling-the-top-15-tiktok-endorsed-literary-gems/"><u>[Updated] Unveiling the Top 15 TikTok-Endorsed Literary Gems</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-tips-for-creating-engaging-fb-video-content-for-2024/"><u>[Updated] Tips for Creating Engaging FB Video Content for 2024</u></a></li>
<li><a href="https://screen-sharing-recording.techidaily.com/new-innovative-strategies-for-captivate-demonstrations/"><u>[New] Innovative Strategies for Captivate Demonstrations</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-in-2024-the-ultimate-list-7-video-mergers-with-no-watermark/"><u>Updated In 2024, The Ultimate List 7 Video Mergers with No Watermark</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/how-to-add-custom-youtube-shorts-thumbnails-with-ease-for-2024/"><u>How to Add Custom YouTube Shorts Thumbnails with Ease for 2024</u></a></li>
<li><a href="https://youtube-help.techidaily.com/in-2024-master-your-vids-with-these-leading-youtube-editors/"><u>In 2024, Master Your Vids with These Leading YouTube Editors</u></a></li>
<li><a href="https://screen-mirroring-recording.techidaily.com/2024-approved-immediate-ios-screen-playback-guide/"><u>2024 Approved  Immediate iOS Screen Playback Guide</u></a></li>
<li><a href="https://windows11.techidaily.com/streamlining-audacity-paudio-operations-in-windows-os/"><u>Streamlining Audacity PAudio Operations in Windows OS</u></a></li>
<li><a href="https://vp-tips.techidaily.com/new-2024-approved-yi-cameras-edge-in-cinematic-quality-4k-capture/"><u>[New] 2024 Approved  Yi Camera's Edge in Cinematic Quality 4K Capture</u></a></li>
<li><a href="https://howto.techidaily.com/7-solutions-to-fix-chrome-crashes-or-wont-open-on-xiaomi-redmi-note-13-proplus-5g-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>7 Solutions to Fix Chrome Crashes or Wont Open on Xiaomi Redmi Note 13 Pro+ 5G | Dr.fone</u></a></li>
<li><a href="https://youtube-clips.techidaily.com/best-youtube-ad-creators/"><u>Best YouTube Ad Creators</u></a></li>
<li><a href="https://extra-skills.techidaily.com/2024-approved-mastering-adventure-the-best-6-gopro-mounts-revealed/"><u>2024 Approved  Mastering Adventure  The Best 6 GoPro Mounts Revealed</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/updated-2024-approved-instagram-de-following-immediate-awareness/"><u>[Updated] 2024 Approved  Instagram De-Following  Immediate Awareness</u></a></li>
<li><a href="https://digital-screen-recording.techidaily.com/in-2024-curated-top-picks-top-6-mac-video-capture-tools/"><u>In 2024, Curated Top Picks  Top 6 Mac Video Capture Tools</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/in-2024-rapid-retreival-of-trendiest-tiktok-vids/"><u>In 2024, Rapid Retreival of Trendiest TikTok Vids</u></a></li>
<li><a href="https://extra-support.techidaily.com/new-inside-the-innovations-of-vegaspro-19/"><u>[New] Inside the Innovations of VegasPro '19</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-in-2024-access-youtube-beats-freshly-split-with-this-compelling-list-of-17-crackers/"><u>[Updated] In 2024, Access YouTube Beats Freshly Split With This Compelling List of 17 Crackers</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/new-evaluating-zdsofts-prowess-in-screen-recorder-tech-for-2024/"><u>[New] Evaluating ZDSoft's Prowess in Screen Recorder Tech for 2024</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/2024-approved-navigating-through-the-premier-10-image-stock-websites/"><u>2024 Approved  Navigating Through the Premier 10 Image Stock Websites</u></a></li>
<li><a href="https://ai-vdieo-software.techidaily.com/updated-best-stop-motion-apps-for-ios-and-android/"><u>Updated Best Stop Motion Apps for iOS and Android</u></a></li>
</ul></div>
