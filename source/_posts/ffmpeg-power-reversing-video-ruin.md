---
title: "FFmpeg Power: Reversing Video Ruin"
date: 2024-07-10T06:40:42.642Z
updated: 2024-07-11T06:40:42.642Z
categories:
  - repair-tools
description: "This Article Describes FFmpeg Power: Reversing Video Ruin"
excerpt: "This Article Describes FFmpeg Power: Reversing Video Ruin"
keywords: FFmpeg Tutorial,Video Reverse Technique,Rewind Video Effects,Prevent Video Damage,Advanced Video Editing,Restore Footage Quality,Video Reversal Software
thumbnail: https://thmb.techidaily.com/b59898c642420c0150db4c12439a573b325962138527651237e7ec403cd28916.jpg
---

## FFmpeg Power: Reversing Video Ruin

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
<li><a href="https://data-wizards.techidaily.com/the-essentials-stellars-12-mac-data-recovery-ux/"><u>The Essentials: Stellar's 12 Mac Data Recovery UX</u></a></li>
<li><a href="https://data-wizards.techidaily.com/data-resurrection-customer-story/"><u>Data Resurrection - Customer Story</u></a></li>
<li><a href="https://data-wizards.techidaily.com/unraveling-routine-video-corruption-causes/"><u>Unraveling Routine Video Corruption Causes</u></a></li>
<li><a href="https://data-wizards.techidaily.com/addressing-video-deformation-post-win10-update/"><u>Addressing VIDEO Deformation Post-Win10 Update</u></a></li>
<li><a href="https://data-wizards.techidaily.com/nebula-accountancy-support-guide/"><u>Nebula Accountancy Support Guide</u></a></li>
<li><a href="https://data-wizards.techidaily.com/the-magic-recovery-client-reports-a-miraculous-turnaround-for-lost-memories/"><u>The Magic Recovery: Client Reports a Miraculous Turnaround for Lost Memories</u></a></li>
<li><a href="https://data-wizards.techidaily.com/epic-retouch-success-trending-customer-stories/"><u>Epic Retouch Success, Trending Customer Stories</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fixing-quirky-question-mark-on-mac-writable-directories/"><u>Fixing Quirky Question Mark on Mac' Writable Directories</u></a></li>
<li><a href="https://data-wizards.techidaily.com/overcoming-damaged-mov-file-problems-in-macos/"><u>Overcoming Damaged MOV File Problems in macOS</u></a></li>
<li><a href="https://data-wizards.techidaily.com/recovermp4-salvage-damaged-videos/"><u>RecoverMP4: Salvage Damaged Videos</u></a></li>
<li><a href="https://data-wizards.techidaily.com/reviving-lost-treasures-with-stellar-free/"><u>Reviving Lost Treasures with Stellar FREE</u></a></li>
<li><a href="https://data-wizards.techidaily.com/streamline-your-macs-storage-with-our-in-depth-guide/"><u>Streamline Your Mac's Storage with Our In-Depth Guide</u></a></li>
<li><a href="https://data-wizards.techidaily.com/effortless-media-player-experience-with-vlc/"><u>Effortless Media Player Experience with VLC</u></a></li>
<li><a href="https://data-wizards.techidaily.com/cosmic-file-retrieval-quickbooks-fixes/"><u>Cosmic File Retrieval: QuickBooks Fixes</u></a></li>
<li><a href="https://data-wizards.techidaily.com/10-best-video-repair-software-windows-and-mac/"><u>10 Best Video Repair Software [Windows and Mac]</u></a></li>
<li><a href="https://data-wizards.techidaily.com/eradicate-code-0xc00d36c4-playback-issue/"><u>Eradicate Code 0XC00D36C4 Playback Issue</u></a></li>
<li><a href="https://data-wizards.techidaily.com/transforming-tarnished-tracks-with-ffmpeg/"><u>Transforming Tarnished Tracks with FFmpeg</u></a></li>
<li><a href="https://data-wizards.techidaily.com/how-vlc-can-resurrect-your-broken-mp4mov-videos-a-comprehensive-guide/"><u>How VLC Can Resurrect Your Broken MP4/MOV Videos: A Comprehensive Guide</u></a></li>
<li><a href="https://data-wizards.techidaily.com/1720669939084-video-customer-testimonial-recovered-thousands-of-photos-from-memory-card-with-stellar-photo-recovery/"><u>Video - Customer Testimonial: Recovered Thousands of Photos From Memory Card with Stellar Photo Recovery.</u></a></li>
<li><a href="https://data-wizards.techidaily.com/master-stellars-mac-recovery-ux/"><u>Master Stellar's Mac Recovery UX</u></a></li>
<li><a href="https://data-wizards.techidaily.com/best-of-breed-macs-data-recovery-solutions-top-8-rankings/"><u>Best of Breed - Mac's Data Recovery Solutions, Top 8 Rankings</u></a></li>
<li><a href="https://data-wizards.techidaily.com/blue-screen-downfall-turn-it-around-with-these-tips/"><u>Blue Screen Downfall? Turn It Around with These Tips</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mac-healing-seamless-video-repair-with-stellar-phoenix/"><u>'Mac Healing': Seamless Video Repair with Stellar Phoenix</u></a></li>
<li><a href="https://data-wizards.techidaily.com/swifter-video-playback-strategies/"><u>Swifter Video Playback Strategies</u></a></li>
<li><a href="https://data-wizards.techidaily.com/how-to-repair-corrupt-avchd-files/"><u>How to Repair Corrupt AVCHD Files</u></a></li>
<li><a href="https://data-wizards.techidaily.com/prime-fix-for-digital-broadcasting-glitches/"><u>Prime Fix for Digital Broadcasting Glitches</u></a></li>
<li><a href="https://data-wizards.techidaily.com/best-practices-in-transferring-extensive-database-data-from-edb-format-to-spreadsheets-effectively/"><u>Best Practices in Transferring Extensive Database Data From EDB Format to Spreadsheets Effectively</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellar-innovates-supercharge-your-mac-efficiency/"><u>Stellar Innovates: Supercharge Your Mac Efficiency</u></a></li>
<li><a href="https://data-wizards.techidaily.com/transform-your-photos-on-macos-with-stellars-phoenix-image-enhancer/"><u>Transform Your Photos on macOS with Stellar's Phoenix Image Enhancer</u></a></li>
<li><a href="https://data-wizards.techidaily.com/convert-huge-databases-to-csv-best-practices-and-tools-for-a-seamless-transfer-process-from-various-formats-including-edb-data-science-blog/"><u>Convert Huge Databases to CSV - Best Practices & Tools for a Seamless Transfer Process From Various Formats Including .EDB | Data Science Blog</u></a></li>
<li><a href="https://data-wizards.techidaily.com/elevating-playback-success-with-vfiles/"><u>Elevating Playback Success with VFiles</u></a></li>
<li><a href="https://data-wizards.techidaily.com/enhanced-mac-speeds-awaiting-stellar-launches-product/"><u>Enhanced Mac Speeds Awaiting – Stellar Launches Product</u></a></li>
<li><a href="https://fox-friendly.techidaily.com/2024-approved-sculpting-stories-with-specialty-fonts-in-after-effects/"><u>2024 Approved  Sculpting Stories with Specialty Fonts in After Effects</u></a></li>
<li><a href="https://tiktok-clips.techidaily.com/updated-2024-approved-elevate-your-digital-footprint-on-tiktok-with-these-names/"><u>[Updated] 2024 Approved  Elevate Your Digital Footprint on TikTok with These Names</u></a></li>
<li><a href="https://ai-video-editing.techidaily.com/1713948938104-color-finale-is-a-color-grading-plugin-for-final-cur-pro-it-allows-users-to-make-cinematic-looking-video-scenes-by-adjusting-the-color-here-well-share-you-s/"><u>Color Finale Is a Color Grading Plugin for Final Cur Pro. It Allows Users to Make Cinematic Looking Video Scenes by Adjusting the Color. Here Well Share You some Basic Information About This Plugin for 2024</u></a></li>
<li><a href="https://facebook-video-recording.techidaily.com/updated-fb-ad-videos-made-easy-utilize-free-video-making-kit-for-2024/"><u>[Updated] FB Ad Videos Made Easy  Utilize Free Video-Making Kit for 2024</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/updated-dominate-youtube-traffic-with-proficient-use-of-creator-studio-for-2024/"><u>[Updated] Dominate YouTube Traffic with Proficient Use of Creator Studio for 2024</u></a></li>
<li><a href="https://location-social.techidaily.com/how-to-change-apple-iphone-13-mini-location-on-skout-drfone-by-drfone-virtual-ios/"><u>How to Change Apple iPhone 13 mini Location on Skout | Dr.fone</u></a></li>
<li><a href="https://some-guidance.techidaily.com/2024-approved-unveiling-the-dji-spark-compact-drone-mastery-for-photographers/"><u>2024 Approved  Unveiling the DJI Spark  Compact Drone Mastery for Photographers</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/new-in-2024-unlock-vertical-video-potential-top-editing-apps-for-mobile/"><u>New In 2024, Unlock Vertical Video Potential Top Editing Apps for Mobile</u></a></li>
<li><a href="https://unlock-android.techidaily.com/how-to-unlock-itel-p55t-pin-codepattern-lockpassword-by-drfone-android/"><u>How to Unlock Itel P55T PIN Code/Pattern Lock/Password</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/updated-from-ordinary-to-extraordinary-your-pathway-with-tiktok-templates/"><u>[Updated] From Ordinary to Extraordinary  Your Pathway with TikTok Templates</u></a></li>
<li><a href="https://visual-screen-recording.techidaily.com/in-2024-mastering-the-art-of-cross-platform-skype-chats-with-this-comprehensive-guide/"><u>In 2024, Mastering the Art of Cross-Platform Skype Chats with This Comprehensive Guide</u></a></li>
<li><a href="https://blog-min.techidaily.com/how-to-retrieve-erased-videos-from-motorola-moto-g84-5g-by-fonelab-android-recover-video/"><u>How to retrieve erased videos from Motorola Moto G84 5G</u></a></li>
<li><a href="https://article-knowledge.techidaily.com/2024-approved-diving-into-hololens-technology-the-visionary-glimpse/"><u>2024 Approved  Diving Into HoloLens Technology – The Visionary Glimpse</u></a></li>
<li><a href="https://screen-capture.techidaily.com/new-voice-log-export-and-critique/"><u>[New] Voice Log Export & Critique</u></a></li>
<li><a href="https://ai-video-apps.techidaily.com/updated-beyond-gopro-quik-top-pc-video-editing-software-options-for-2024/"><u>Updated Beyond GoPro Quik Top PC Video Editing Software Options for 2024</u></a></li>
<li><a href="https://youtube-videos.techidaily.com/8-engaging-exercise-routines-for-active-viewership/"><u>8 Engaging Exercise Routines for Active Viewership</u></a></li>
<li><a href="https://android-transfer.techidaily.com/in-2024-5-ways-to-teach-you-to-transfer-files-from-nokia-c22-to-other-android-devices-easily-drfone-by-drfone-transfer-from-android-transfer-from-android/"><u>In 2024, 5 Ways To Teach You To Transfer Files from Nokia C22 to Other Android Devices Easily | Dr.fone</u></a></li>
<li><a href="https://video-screen-grab.techidaily.com/updated-2024-approved-optimal-techniques-for-capturing-ppt-sessions/"><u>[Updated] 2024 Approved  Optimal Techniques for Capturing PPT Sessions</u></a></li>
<li><a href="https://instagram-videos.techidaily.com/igtv-video-placement-to-facebook-networks-5-ways/"><u>IGTV Video Placement to Facebook Networks (5 Ways)</u></a></li>
<li><a href="https://video-capture.techidaily.com/updated-fraps-for-gamers-a-screen-record-review/"><u>[Updated] Fraps for Gamers  A Screen Record Review</u></a></li>
</ul></div>
