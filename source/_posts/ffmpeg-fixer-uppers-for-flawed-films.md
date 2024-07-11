---
title: FFmpeg Fixer-Uppers for Flawed Films
date: 2024-07-10T06:42:00.733Z
updated: 2024-07-11T06:42:00.733Z
categories:
  - repair-tools
description: This Article Describes FFmpeg Fixer-Uppers for Flawed Films
excerpt: This Article Describes FFmpeg Fixer-Uppers for Flawed Films
keywords: FFmpeg Film Correction,Advanced Video Editing Tools,Professional Film Enhancement Software,FFmpeg Video Restoration,Flawed Film Correction Methods,Digital Video Restoration Techniques,FFmpeg Usage for Film Repair
thumbnail: https://thmb.techidaily.com/7f4ae1b9b31cac38f7f5bddb79d648495e38c22783ddea3f0c620d5fbd42617b.jpg
---

## FFmpeg Fixer-Uppers for Flawed Films

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
<li><a href="https://data-wizards.techidaily.com/overcoming-file-playback-hurdle-224003/"><u>Overcoming File Playback Hurdle: 224003</u></a></li>
<li><a href="https://data-wizards.techidaily.com/resolving-unsupported-codecs-a-guide/"><u>Resolving Unsupported Codecs: A Guide</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fix-corrupted-and-damaged-mpeg-videos-with-advanced-mpeg-repair-solutions/"><u>Fix Corrupted & Damaged MPEG Videos with Advanced MPeg Repair Solutions</u></a></li>
<li><a href="https://data-wizards.techidaily.com/tackling-troublesome-errors-bsod-remedies-for-w1011/"><u>Tackling Troublesome Errors: BSOD Remedies for W10/11</u></a></li>
<li><a href="https://data-wizards.techidaily.com/hybrid-marketing-strategy-combining-facebook-linkedin-and-youtube-for-business-growth/"><u>Hybrid Marketing Strategy: Combining Facebook, LinkedIn, and YouTube for Business Growth</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mac-healing-seamless-video-repair-with-stellar-phoenix/"><u>'Mac Healing': Seamless Video Repair with Stellar Phoenix</u></a></li>
<li><a href="https://data-wizards.techidaily.com/why-cant-i-open-my-photos/"><u>Why Can't I Open My Photos?</u></a></li>
<li><a href="https://data-wizards.techidaily.com/conquering-kernel-panic-on-your-macbook-pro/"><u>Conquering Kernel Panic on Your MacBook Pro</u></a></li>
<li><a href="https://data-wizards.techidaily.com/streamline-android-video-playback/"><u>Streamline Android Video Playback</u></a></li>
<li><a href="https://data-wizards.techidaily.com/innovation-accessory-insurance/"><u>Innovation Accessory Insurance</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellar-launches-worlds-first-photo-recovery-and-repair-software-news-of-stellar/"><u>Stellar Launches World's First Photo Recovery & Repair Software - News of Stellar</u></a></li>
<li><a href="https://data-wizards.techidaily.com/navigating-the-labyrinth-of-lost-files-a-guide-to-recovery-by-singh/"><u>Navigating the Labyrinth of Lost Files: A Guide to Recovery, by Singh</u></a></li>
<li><a href="https://data-wizards.techidaily.com/exchange-data-rescue-with-stellardb-tools/"><u>Exchange Data Rescue with StellarDB Tools</u></a></li>
<li><a href="https://data-wizards.techidaily.com/the-magic-recovery-client-reports-a-miraculous-turnaround-for-lost-memories/"><u>The Magic Recovery: Client Reports a Miraculous Turnaround for Lost Memories</u></a></li>
<li><a href="https://data-wizards.techidaily.com/correctorpro-save-your-mp4s-and-movs/"><u>CorrectorPro: Save Your MP4s & MOVs</u></a></li>
<li><a href="https://data-wizards.techidaily.com/uncharted-territories-of-data-loss-navigating-with-totans-guidance/"><u>Uncharted Territories of Data Loss - Navigating with Totan's Guidance</u></a></li>
<li><a href="https://data-wizards.techidaily.com/totan-banerjee-on-stellar-pathways-to-digital-redemption/"><u>Totan Banerjee on Stellar Pathways to Digital Redemption</u></a></li>
<li><a href="https://data-wizards.techidaily.com/totans-odyssey-in-data-salvation-navigating-through-stellar-realms/"><u>Totan's Odyssey in Data Salvation - Navigating Through Stellar Realms</u></a></li>
<li><a href="https://data-wizards.techidaily.com/synergizing-your-brands-impact-on-facebook-linkedin-and-youtube/"><u>Synergizing Your Brand's Impact on Facebook, LinkedIn, and YouTube</u></a></li>
<li><a href="https://data-wizards.techidaily.com/proven-mysql-recovery-strategies-demonstrated-in-video-with-augusto/"><u>Proven MySql Recovery Strategies Demonstrated in Video with Augusto</u></a></li>
<li><a href="https://data-wizards.techidaily.com/unlocking-potential-top-tier-tutorials-and-tricks-for-home-improvement-by-steller-tech/"><u>Unlocking Potential: Top-Tier Tutorials and Tricks for Home Improvement by Steller Tech</u></a></li>
<li><a href="https://data-wizards.techidaily.com/techniques-to-minimize-compression-in-exported-media/"><u>Techniques to Minimize Compression in Exported Media</u></a></li>
<li><a href="https://data-wizards.techidaily.com/diy-video-stabilization-techniques/"><u>DIY Video Stabilization Techniques</u></a></li>
<li><a href="https://data-wizards.techidaily.com/groundbreayer-approaches-to-improve-vids-playback/"><u>Groundbreayer Approaches to Improve Vids Playback</u></a></li>
<li><a href="https://data-wizards.techidaily.com/critical-communication-restored-exchange-analysis/"><u>Critical Communication Restored: Exchange Analysis</u></a></li>
<li><a href="https://data-wizards.techidaily.com/expert-methods-to-eradicate-interlace-flaws-in-content/"><u>Expert Methods to Eradicate Interlace Flaws in Content</u></a></li>
<li><a href="https://data-wizards.techidaily.com/sql-rehab-by-microsofts-top-coder-damian/"><u>SQL Rehab by Microsoft's Top Coder, Damian</u></a></li>
<li><a href="https://data-wizards.techidaily.com/why-stellar-repair-for-video-doesnt-work-properly-on-some-of-my/"><u>Why Stellar Repair for Video Doesn't Work Properly on Some of My ...</u></a></li>
<li><a href="https://data-wizards.techidaily.com/cosmic-databases-reviving-your-sql/"><u>Cosmic Databases: Reviving Your SQL</u></a></li>
<li><a href="https://data-wizards.techidaily.com/conversion-of-voluminous-data-sets-directly-into-easily-accessible-and-analyzable-csv-formats-a-complete-guide-for-businesses-and-individuals-using-differen1/"><u>Conversion of Voluminous Data Sets Directly Into Easily Accessible and Analyzable CSV Formats – A Complete Guide for Businesses & Individuals Using Different Sources | Tech Blog Post</u></a></li>
<li><a href="https://data-wizards.techidaily.com/ultimate-guide-restoring-damaged-mp4mov-videos-with-vlc-media-player/"><u>Ultimate Guide: Restoring Damaged MP4/MOV Videos with VLC Media Player</u></a></li>
<li><a href="https://data-wizards.techidaily.com/windows-troubleshooting-combat-the-bsod-blues/"><u>Windows Troubleshooting: Combat the BSOD Blues</u></a></li>
<li><a href="https://data-wizards.techidaily.com/experience-shared-client-filmed-stories/"><u>Experience Shared: Client-Filmed Stories</u></a></li>
<li><a href="https://data-wizards.techidaily.com/reducing-playback-delay-in-vlc-player/"><u>Reducing Playback Delay in VLC Player</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/in-2024-premier-20-unrestricted-pubg-montage-samples/"><u>In 2024, Premier 20 Unrestricted PUBG Montage Samples</u></a></li>
<li><a href="https://android-location-track.techidaily.com/top-10-best-spy-watches-for-your-vivo-v30-pro-drfone-by-drfone-virtual-android/"><u>Top 10 Best Spy Watches For your Vivo V30 Pro | Dr.fone</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-2024-approved-unlock-old-facebook-memories-with-a-click/"><u>[Updated] 2024 Approved  Unlock Old Facebook Memories with a Click</u></a></li>
<li><a href="https://ai-editing-video.techidaily.com/new-turn-your-text-into-a-podcast-made-possible/"><u>New Turn Your Text Into a Podcast Made Possible</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/2024-approved-exploring-the-reasons-behind-blue-icons-in-facebooks-chat-communication/"><u>2024 Approved  Exploring the Reasons Behind Blue Icons in Facebook’s Chat Communication</u></a></li>
<li><a href="https://youtube-webster.techidaily.com/n-2024-earths-richest-digital-content-wizard/"><u>[New] In 2024, Earth's Richest Digital Content Wizard</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/new-in-2024-a-beginners-guide-to-video-editing-on-mac-create-stunning-movies/"><u>New In 2024, A Beginners Guide to Video Editing on Mac Create Stunning Movies</u></a></li>
<li><a href="https://youtube-blog.techidaily.com/ed-elevate-your-video-presence-with-stellar-intros-in-imovie/"><u>[Updated] Elevate Your Video Presence with Stellar Intros in iMovie</u></a></li>
<li><a href="https://desktop-recording.techidaily.com/advanced-terraria-modifications-guide-for-2024/"><u>Advanced Terraria Modifications Guide for 2024</u></a></li>
<li><a href="https://driver-install.techidaily.com/enhance-system-efficiency-update-lenovo-w11-drivers/"><u>Enhance System Efficiency - Update Lenovo W11 Drivers</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/updated-2024-approved-simplify-slide-sharing-at-work-webcam-assisted-tips/"><u>[Updated] 2024 Approved  Simplify Slide Sharing at Work  Webcam-Assisted Tips</u></a></li>
<li><a href="https://easy-unlock-android.techidaily.com/how-to-unlock-oppo-f23-5g-pattern-lock-if-forgotten-6-ways-by-drfone-android/"><u>How to Unlock Oppo F23 5G Pattern Lock if Forgotten? 6 Ways</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-does-the-sub4sub-strategy-improve-content-consumption-in-2024/"><u>[New] Does the Sub4Sub Strategy Improve Content Consumption, In 2024</u></a></li>
<li><a href="https://location-fake.techidaily.com/all-must-knows-to-use-fake-gps-go-location-spoofer-on-apple-iphone-6-plus-drfone-by-drfone-virtual-ios/"><u>All Must-Knows to Use Fake GPS GO Location Spoofer On Apple iPhone 6 Plus | Dr.fone</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/2024-approved-unleash-your-creativity-with-jaycut-a-free-online-video-editing-tutorial/"><u>2024 Approved Unleash Your Creativity with Jaycut A Free Online Video Editing Tutorial</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/in-2024-top-10-tiktok-ideas-to-make-your-videos-go-viral/"><u>In 2024, Top 10 TikTok Ideas to Make Your Videos Go Viral</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-in-2024-facebook-video-aspect-ratios-decoded-a-complete-guide/"><u>New In 2024, Facebook Video Aspect Ratios Decoded A Complete Guide</u></a></li>
<li><a href="https://pokemon-go-android.techidaily.com/in-2024-the-most-useful-tips-for-pokemon-go-ultra-league-on-honor-x9b-drfone-by-drfone-virtual-android/"><u>In 2024, The Most Useful Tips for Pokemon Go Ultra League On Honor X9b | Dr.fone</u></a></li>
<li><a href="https://on-screen-recording.techidaily.com/in-2024-internal-recording-feature-screen-capture-for-huaweis-mate-and-p-series-phones/"><u>In 2024, Internal Recording Feature  Screen Capture for Huawei's Mate & P Series Phones</u></a></li>
<li><a href="https://extra-hints.techidaily.com/expertise-in-action-mastering-iphone-silhouette-art/"><u>Expertise in Action  Mastering iPhone Silhouette Art</u></a></li>
<li><a href="https://howto.techidaily.com/full-solutions-to-fix-error-code-920-in-google-play-on-honor-x9b-drfone-by-drfone-fix-android-problems-fix-android-problems/"><u>Full Solutions to Fix Error Code 920 In Google Play on Honor X9b | Dr.fone</u></a></li>
<li><a href="https://blog-min.techidaily.com/5-ways-to-move-contacts-from-realme-v30-to-iphone-131415-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>5 Ways to Move Contacts From Realme V30 to iPhone (13/14/15) | Dr.fone</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-avoiding-tiktoks-ghost-mode-strategies-to-stay-visible-for-2024/"><u>[Updated] Avoiding TikTok's Ghost Mode  Strategies to Stay Visible for 2024</u></a></li>
<li><a href="https://android-location.techidaily.com/3-effective-methods-to-fake-gps-location-on-android-for-your-motorola-moto-g24-drfone-by-drfone-virtual/"><u>3 Effective Methods to Fake GPS location on Android For your Motorola Moto G24 | Dr.fone</u></a></li>
<li><a href="https://extra-tips.techidaily.com/2024-approved-a-chronicle-of-the-most-popular-reddit-threads-ever/"><u>2024 Approved  A Chronicle of the Most Popular Reddit Threads Ever</u></a></li>
</ul></div>
