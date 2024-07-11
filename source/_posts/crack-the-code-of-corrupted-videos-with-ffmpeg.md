---
title: Crack the Code of Corrupted Videos with FFmpeg
date: 2024-07-10T06:39:57.918Z
updated: 2024-07-11T06:39:57.918Z
categories:
  - repair-tools
description: This Article Describes Crack the Code of Corrupted Videos with FFmpeg
excerpt: This Article Describes Crack the Code of Corrupted Videos with FFmpeg
keywords: FFmpeg Video Corruption Fix,Corrupted Video Recovery Using FFmpeg,Optimize Video Quality with FFmpeg,FFmpeg Techniques for Damaged Media Files,How to Repair Broken Video Files with FFmpeg,crack the code of corrupted videos with ffmpeg,effortless repair of corrupt or busted mpeg videos with leading tools
thumbnail: https://thmb.techidaily.com/b1557e3d9700a9810b8b9bbec88362c53ba5a3f98f5f309c7652fc768db4746d.jpg
---

## Crack the Code of Corrupted Videos with FFmpeg

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
<li><a href="https://data-wizards.techidaily.com/revive-archives-embrace-the-stellar-recovery/"><u>Revive Archives: Embrace the Stellar Recovery</u></a></li>
<li><a href="https://data-wizards.techidaily.com/solving-display-card-glitches/"><u>Solving Display Card Glitches</u></a></li>
<li><a href="https://data-wizards.techidaily.com/1720671362461-issues-with-stellar-video-file-repairs/"><u>Issues with Stellar Video File Repairs.</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mitigating-unsupported-codec-constraints/"><u>Mitigating Unsupported Codec Constraints</u></a></li>
<li><a href="https://data-wizards.techidaily.com/quality-transformation/"><u>Quality Transformation</u></a></li>
<li><a href="https://data-wizards.techidaily.com/unveiling-steps-for-smooth-video-playback-win11-style/"><u>Unveiling Steps for Smooth Video Playback Win11 Style</u></a></li>
<li><a href="https://data-wizards.techidaily.com/corrupted-film-files-no-more-a-comprehensive-guide-to-fixing-with-vlc/"><u>Corrupted Film Files No More – A Comprehensive Guide to Fixing with VLC</u></a></li>
<li><a href="https://data-wizards.techidaily.com/1720673462771-unlock-the-mysteries-of-data-loss-with-totan-banerjee-at-stellar-inc/"><u>Unlock the Mysteries of Data Loss with Totan Banerjee at Stellar Inc</u></a></li>
<li><a href="https://data-wizards.techidaily.com/swiftly-fix-damaged-rmvb-and-ogms/"><u>Swiftly Fix Damaged RMVB and OGMs</u></a></li>
<li><a href="https://data-wizards.techidaily.com/recovered-media-not-functional/"><u>Recovered Media Not Functional</u></a></li>
<li><a href="https://data-wizards.techidaily.com/recovering-scrambled-avchd-files/"><u>Recovering Scrambled AVCHD Files</u></a></li>
<li><a href="https://data-wizards.techidaily.com/cost-effective-measures/"><u>Cost-Effective Measures</u></a></li>
<li><a href="https://data-wizards.techidaily.com/from-empty-to-full-memory-card-revival-success-story-by-customer/"><u>From Empty to Full: Memory Card Revival Success Story by Customer</u></a></li>
<li><a href="https://data-wizards.techidaily.com/totan-banerjee-author-at-stellar-data-recovery-article-en/"><u>Totan Banerjee, Author at Stellar Data Recovery Article - En</u></a></li>
<li><a href="https://data-wizards.techidaily.com/tech-product-assurance-clause/"><u>Tech Product Assurance Clause</u></a></li>
<li><a href="https://data-wizards.techidaily.com/enhancing-support-for-limited-codecs/"><u>Enhancing Support for Limited Codecs</u></a></li>
<li><a href="https://data-wizards.techidaily.com/revolutionizing-bookkeeping-stellar-fixes-corrupted-quickbooks-files/"><u>Revolutionizing Bookkeeping: Stellar Fixes Corrupted QuickBooks Files</u></a></li>
<li><a href="https://data-wizards.techidaily.com/recovered-media-not-opening-properly/"><u>Recovered Media Not Opening Properly</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellar-revival-software-a-free-lifeline-for-files/"><u>Stellar Revival Software – A Free Lifeline for Files</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fix-film-fractures-on-mac-unveil-the-power-of-stellar-phoenix/"><u>Fix Film Fractures on Mac - Unveil the Power of Stellar Phoenix</u></a></li>
<li><a href="https://data-wizards.techidaily.com/streamline-mov-repair-with-stellar-help/"><u>Streamline MOV Repair with Stellar Help</u></a></li>
<li><a href="https://data-wizards.techidaily.com/performance-enhancement/"><u>Performance Enhancement</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fixing-corrupted-m4v-files-mac-and-windows-guide/"><u>Fixing Corrupted M4V Files: Mac & Windows Guide</u></a></li>
<li><a href="https://data-wizards.techidaily.com/masterful-techniques-in-data-salvage-a-deep-dive-by-singh/"><u>Masterful Techniques in Data Salvage: A Deep Dive by Singh</u></a></li>
<li><a href="https://data-wizards.techidaily.com/solving-screen-sync-problems-post-win11-update/"><u>Solving Screen Sync Problems Post-Win11 Update</u></a></li>
<li><a href="https://data-wizards.techidaily.com/curing-lossy-compression-errors-in-mov-files/"><u>Curing Lossy Compression Errors in MOV Files</u></a></li>
<li><a href="https://data-wizards.techidaily.com/from-reviews-to-vlogs-with-mac-patrons/"><u>From Reviews to Vlogs with Mac Patrons</u></a></li>
<li><a href="https://data-wizards.techidaily.com/resolving-file-format-frustrations/"><u>Resolving File Format Frustrations</u></a></li>
<li><a href="https://android-unlock.techidaily.com/in-2024-how-to-enable-usb-debugging-on-a-locked-samsung-galaxy-s24plus-phone-by-drfone-android/"><u>In 2024, How To Enable USB Debugging on a Locked Samsung Galaxy S24+ Phone</u></a></li>
<li><a href="https://extra-resources.techidaily.com/boosting-photo-skills-speed-and-simplicity-with-windows-10-paint-app/"><u>Boosting Photo Skills  Speed & Simplicity with Windows 10 Paint App</u></a></li>
<li><a href="https://youtube-help.techidaily.com/2024-approved-starting-out-building-your-youtube-presence-and-earning/"><u>2024 Approved  Starting Out  Building Your YouTube Presence & Earning</u></a></li>
<li><a href="https://fox-info.techidaily.com/updated-in-2024-step-beyond-boundaries-with-innovative-wins11-titles/"><u>[Updated] In 2024, Step Beyond Boundaries with Innovative Wins11 Titles</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/new-2024-approved-creating-flawless-slow-motion-videos-is-every-content-creators-dream-learn-about-davinci-resolve-slow-motion-video-creation-amongst-other-/"><u>New 2024 Approved Creating Flawless Slow-Motion Videos Is Every Content Creators Dream. Learn About DaVinci Resolve Slow-Motion Video Creation, Amongst Other Tools</u></a></li>
<li><a href="https://extra-resources.techidaily.com/crafting-melodies-insights-into-magixs-newest-sound-suite-2024/"><u>Crafting Melodies  Insights Into Magix's Newest Sound Suite 2024</u></a></li>
<li><a href="https://howto.techidaily.com/android-safe-mode-how-to-turn-off-safe-mode-on-oneplus-nord-n30-se-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Android Safe Mode - How to Turn off Safe Mode on OnePlus Nord N30 SE? | Dr.fone</u></a></li>
<li><a href="https://some-knowledge.techidaily.com/new-in-depth-giroptic-360-angle-reviews/"><u>[New] In-Depth Giroptic 360-Angle Reviews</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/updated-2024-approved-intuitivestepsforyoucamuseandrecording/"><u>[Updated] 2024 Approved  IntuitiveStepsForYouCamUseAndRecording</u></a></li>
<li><a href="https://android-location-track.techidaily.com/in-2024-top-6-appsservices-to-trace-any-oneplus-ace-3-location-by-mobile-number-drfone-by-drfone-virtual-android/"><u>In 2024, Top 6 Apps/Services to Trace Any OnePlus Ace 3 Location By Mobile Number | Dr.fone</u></a></li>
<li><a href="https://screen-activity-recording.techidaily.com/2024-approved-key-screenshot-utilities-1-8/"><u>2024 Approved  Key Screenshot Utilities #1-8</u></a></li>
<li><a href="https://fox-glue.techidaily.com/2024-approved-synchronized-aesthetics-audio-meets-picture/"><u>2024 Approved  Synchronized Aesthetics  Audio Meets Picture</u></a></li>
<li><a href="https://bypass-frp.techidaily.com/how-to-bypass-vivo-y02t-frp-in-3-different-ways-by-drfone-android/"><u>How To Bypass Vivo Y02T FRP In 3 Different Ways</u></a></li>
</ul></div>
