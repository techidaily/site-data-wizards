---
title: FFmpeg Insight for Reviving Media
date: 2024-07-10T06:43:20.726Z
updated: 2024-07-11T06:43:20.726Z
categories:
  - repair-tools
description: This Article Describes FFmpeg Insight for Reviving Media
excerpt: This Article Describes FFmpeg Insight for Reviving Media
keywords: FFmpeg Video Enhancement,Advanced Media Restoration,Reviving Old Videos with FFmpeg,HD Conversion Using FFmpeg,Audio and Video Editing Techniques with FFmpeg,FFmpeg for Media Quality Improvement,Data Recovery and Restoration with FFmpeg
thumbnail: https://thmb.techidaily.com/cd939fa7a6d55f7872fb793de3dd6a0a1cf42f10f319881184a8db53e138fd0a.jpg
---

## FFmpeg Insight for Reviving Media

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
<li><a href="https://data-wizards.techidaily.com/data-resurrection-expert-testimonial-by-damian/"><u>Data Resurrection: Expert Testimonial by Damian</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mac-hardware-help-regaining-external-hdd-visibility/"><u>Mac Hardware Help: Regaining External HDD Visibility</u></a></li>
<li><a href="https://data-wizards.techidaily.com/harmonizing-online-presence-across-facebook-linkedin-and-youtube-platforms/"><u>Harmonizing Online Presence Across Facebook, LinkedIn and YouTube Platforms</u></a></li>
<li><a href="https://data-wizards.techidaily.com/enterprise-victory-stellar-masterminds-data-revival-from-hdds/"><u>Enterprise Victory: Stellar Masterminds Data Revival From HDDs</u></a></li>
<li><a href="https://data-wizards.techidaily.com/how-to-repair-corrupt-mp4-video-files/"><u>How to Repair Corrupt MP4 Video Files</u></a></li>
<li><a href="https://data-wizards.techidaily.com/recovering-playback-from-error-224003/"><u>Recovering Playback From Error 224003</u></a></li>
<li><a href="https://data-wizards.techidaily.com/step-by-step-guide-for-overcoming-windows-blue-errors/"><u>Step-by-Step Guide for Overcoming Windows Blue Errors</u></a></li>
<li><a href="https://data-wizards.techidaily.com/exploring-the-depths-of-effective-data-extraction-with-vishakha/"><u>Exploring the Depths of Effective Data Extraction with Vishakha</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fabio-goncalves-explains-effective-exchanging-of-it-customer-feedback/"><u>Fabio Goncalves Explains Effective Exchanging of IT Customer Feedback</u></a></li>
<li><a href="https://data-wizards.techidaily.com/snapbackvid-instantly-mend-fractured-media/"><u>SnapBackVid: Instantly Mend Fractured Media</u></a></li>
<li><a href="https://data-wizards.techidaily.com/learn-the-process-exporting-restored-edb-mailbox-data-to-an-operational-exchange-server-video-guide/"><u>Learn the Process: Exporting Restored EDB Mailbox Data to an Operational Exchange Server - Video Guide</u></a></li>
<li><a href="https://data-wizards.techidaily.com/step-by-step-guide-fixing-nikon-written-movies/"><u>Step-by-Step Guide: Fixing Nikon' Written Movies</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mend-damaged-mp4s-with-these-proven-repair-software-options/"><u>Mend Damaged MP4s with These Proven Repair Software Options</u></a></li>
<li><a href="https://data-wizards.techidaily.com/expert-advice-on-repairing-faulty-m4v-media-files/"><u>Expert Advice on Repairing Faulty M4V Media Files</u></a></li>
<li><a href="https://data-wizards.techidaily.com/tackling-interlaced-video-glitches-solutions-explored/"><u>Tackling Interlaced Video Glitches: Solutions Explored</u></a></li>
<li><a href="https://data-wizards.techidaily.com/techniques-for-repairing-damaged-nikon-videos/"><u>Techniques for Repairing Damaged Nikon Videos</u></a></li>
<li><a href="https://data-wizards.techidaily.com/how-do-i-fix-a-video-card-problem/"><u>How Do I Fix a Video Card Problem?</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellar-upgrades-get-your-mac-flying-with-speedup/"><u>Stellar Upgrades: Get Your Mac Flying with Speedup</u></a></li>
<li><a href="https://data-wizards.techidaily.com/free-data-phoenix-stellar-recovery-software/"><u>Free Data Phoenix - Stellar Recovery Software</u></a></li>
<li><a href="https://data-wizards.techidaily.com/recovering-broken-mp4-and-mov-through-quicktime/"><u>Recovering Broken MP4 and MOV Through QuickTime</u></a></li>
<li><a href="https://data-wizards.techidaily.com/video-repair-tool-mac-and-windows/"><u>Video Repair Tool Mac & Windows</u></a></li>
<li><a href="https://data-wizards.techidaily.com/macs-comeback-heroes-unveiling-8-data-recovery-applications/"><u>Mac's Comeback Heroes: Unveiling 8 Data Recovery Applications</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fix-film-fractures-on-mac-unveil-the-power-of-stellar-phoenix/"><u>Fix Film Fractures on Mac - Unveil the Power of Stellar Phoenix</u></a></li>
<li><a href="https://some-skills.techidaily.com/top-10-most-shared-stock-photos-and-their-tales-for-2024/"><u>Top 10 Most Shared Stock Photos and Their Tales for 2024</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-elevate-your-whatsapp-status-game-with-these-top-apps-for-2024/"><u>Updated Elevate Your WhatsApp Status Game with These Top Apps for 2024</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/1716183955941-updated-how-to-reverse-image-search-instagram-for-2024/"><u>[Updated] How to Reverse Image Search Instagram for 2024</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-how-to-unlock-apple-iphone-14-by-drfone-ios/"><u>In 2024, How to Unlock Apple iPhone 14?</u></a></li>
<li><a href="https://extra-information.techidaily.com/calculated-viewing-time-for-a-standard-20mb-film-for-2024/"><u>Calculated Viewing Time for a Standard 20Mb Film for 2024</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/premium-editing-tools-unveiled-youtube-edition-for-2024/"><u>Premium Editing Tools Unveiled  YouTube Edition for 2024</u></a></li>
<li><a href="https://audio-editing.techidaily.com/2024-approved-optimize-m4a-playback-on-android-devices-with-these-strategies/"><u>2024 Approved Optimize M4A Playback on Android Devices with These Strategies</u></a></li>
<li><a href="https://extra-resources.techidaily.com/top-10-best-stabilized-camera-gimbals-for-iphone-android-and-dslr-for-2024/"><u>Top 10 Best Stabilized Camera Gimbals for iPhone, Android, and DSLR for 2024</u></a></li>
<li><a href="https://youtube-stream.techidaily.com/2024-approved-free-music-for-videos-finding-the-right-sources/"><u>2024 Approved  Free Music for Videos  Finding the Right Sources</u></a></li>
<li><a href="https://techidaily.com/how-to-recover-lost-data-of-apple-iphone-14-pro-drfone-by-drfone-ios-data-recovery-ios-data-recovery/"><u>How To Recover Lost Data of Apple iPhone 14 Pro? | Dr.fone</u></a></li>
<li><a href="https://audio-shaping.techidaily.com/updated-the-definitive-guide-to-choosing-best-pop-sounds-for-video-backdrops-2024s-catalogue/"><u>Updated The Definitive Guide to Choosing Best Pop Sounds for Video Backdrops (2024S Catalogue)</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/from-talk-to-text-proven-strategies-for-quality-recordings-for-2024/"><u>From Talk To Text  Proven Strategies for Quality Recordings for 2024</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/2024-approved-exploring-the-in-depth-world-of-magix-video-pro-x/"><u>2024 Approved  Exploring the In-Depth World of Magix Video Pro X</u></a></li>
<li><a href="https://some-techniques.techidaily.com/excellent-face-changing-software-iphone-and-android-for-2024/"><u>Excellent Face-Changing Software, iPhone & Android for 2024</u></a></li>
<li><a href="https://fox-access.techidaily.com/hone-your-meme-skills-quickly-using-9gag-strategies/"><u>Hone Your Meme Skills Quickly Using 9GAG Strategies</u></a></li>
<li><a href="https://blog-min.techidaily.com/4-ways-to-transfer-music-from-vivo-y27s-to-iphone-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>4 Ways to Transfer Music from Vivo Y27s to iPhone | Dr.fone</u></a></li>
<li><a href="https://facebook-video-content.techidaily.com/chatcam-save-extractor-for-facebook-for-2024/"><u>ChatCam Save Extractor for Facebook for 2024</u></a></li>
</ul></div>
