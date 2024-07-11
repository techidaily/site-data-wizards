---
title: Bring Back Blighted Broadcasts via FFmpeg
date: 2024-07-10T06:40:48.249Z
updated: 2024-07-11T06:40:48.249Z
categories:
  - repair-tools
description: This Article Describes Bring Back Blighted Broadcasts via FFmpeg
excerpt: This Article Describes Bring Back Blighted Broadcasts via FFmpeg
keywords: FFmpeg Broadcasting,Video Restoration Tools,Blight Removal Software,Advanced Video Processing,FFmpeg Features,Open Source Video Editing Software,Media Conversion and Enhancement
thumbnail: https://thmb.techidaily.com/d0111f28dd3d983ea5a260fddb9a6bea79bc1de4dd5cf7f39a57f89da5a5decf.jpg
---

## Bring Back Blighted Broadcasts via FFmpeg

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
<li><a href="https://data-wizards.techidaily.com/guidelines-on-fixing-broken-nikon-video-data/"><u>Guidelines on Fixing Broken Nikon Video Data</u></a></li>
<li><a href="https://data-wizards.techidaily.com/cosmic-data-safety-net-archive/"><u>Cosmic Data Safety Net Archive</u></a></li>
<li><a href="https://data-wizards.techidaily.com/rebuild-ruined-films-easily-on-mac-discover-stellar-phoenix/"><u>Rebuild Ruined Films Easily on Mac - Discover Stellar Phoenix</u></a></li>
<li><a href="https://data-wizards.techidaily.com/swift-fix-for-exchange-failures-real-life-tales/"><u>Swift Fix for Exchange Failures: Real-Life Tales</u></a></li>
<li><a href="https://data-wizards.techidaily.com/how-to-fix-audio-video-delay-in-vlc-media-player-stellar/"><u>How to Fix Audio Video Delay in VLC Media Player - Stellar</u></a></li>
<li><a href="https://data-wizards.techidaily.com/navigating-windowsmac-corruption-of-video-extensions/"><u>Navigating Windows/Mac Corruption of Video Extensions</u></a></li>
<li><a href="https://data-wizards.techidaily.com/1720672936317-totan-banerjees-secrets-to-unlocking-lost-data-at-stellar-inc/"><u>Totan Banerjee’s Secrets to Unlocking Lost Data at Stellar Inc</u></a></li>
<li><a href="https://data-wizards.techidaily.com/memory-miracle-unveiled-thousands-of-photos-restored-success-story/"><u>Memory Miracle Unveiled: Thousands of Photos Restored Success Story</u></a></li>
<li><a href="https://data-wizards.techidaily.com/rebuilding-corrupted-avchd-tapes/"><u>Rebuilding Corrupted AVCHD Tapes</u></a></li>
<li><a href="https://data-wizards.techidaily.com/decoding-mac-disk-management-visual-tutorial-explanation/"><u>Decoding Mac Disk Management - Visual Tutorial Explanation</u></a></li>
<li><a href="https://data-wizards.techidaily.com/smooth-playback-fix-vlc-enabled/"><u>Smooth Playback Fix - VLC Enabled</u></a></li>
<li><a href="https://data-wizards.techidaily.com/rejuvenate-damaged-jpegs-instantly/"><u>Rejuvenate Damaged JPEGs Instantly</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellar-launches-the-first-ever-software-to-repair-corrupted-quickbooks-file-news-of-stellar/"><u>Stellar Launches the First Ever Software to Repair Corrupted QuickBooks File - News of Stellar</u></a></li>
<li><a href="https://data-wizards.techidaily.com/from-deletion-to-joy-a-testimonial-on-extraordinary-photo-salvage/"><u>From Deletion to Joy: A Testimonial on Extraordinary Photo Salvage</u></a></li>
<li><a href="https://data-wizards.techidaily.com/hard-drive-rescue-stories/"><u>Hard Drive Rescue Stories</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fixed-instagram-reel-quirk/"><u>Fixed: Instagram Reel Quirk</u></a></li>
<li><a href="https://data-wizards.techidaily.com/getting-acquainted-with-stellar-12-mac-interface/"><u>Getting Acquainted with Stellar 12 Mac Interface</u></a></li>
<li><a href="https://data-wizards.techidaily.com/enhanced-functionality/"><u>Enhanced Functionality</u></a></li>
<li><a href="https://data-wizards.techidaily.com/solving-playback-disruptions-in-ios-youtube-videos/"><u>Solving Playback Disruptions in iOS YouTube Videos</u></a></li>
<li><a href="https://data-wizards.techidaily.com/peak-performance-in-client-contentment-achieving-245/"><u>Peak Performance in Client Contentment, Achieving 245%%</u></a></li>
<li><a href="https://data-wizards.techidaily.com/video-error-224003-decoded-resolved/"><u>Video Error 224003 Decoded, Resolved</u></a></li>
<li><a href="https://data-wizards.techidaily.com/seamless-social-experience-across-facebook-linkedin-and-youtube/"><u>Seamless Social Experience Across Facebook, LinkedIn and YouTube</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellars-phoenix-emerges-for-mac-users-seeking-image-perfection/"><u>Stellar’s Phoenix Emerges for Mac Users Seeking Image Perfection</u></a></li>
<li><a href="https://data-wizards.techidaily.com/mending-broken-media-ffmpeg-solutions/"><u>Mending Broken Media: FFmpeg Solutions</u></a></li>
<li><a href="https://article-tips.techidaily.com/2024-approved-quick-start-guide-making-your-gifs-count-as-emoji-stickers-in-telegram/"><u>2024 Approved  Quick-Start Guide  Making Your GIFS Count as Emoji Stickers in Telegram</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/new-mastering-adobe-premiere-top-6-essential-tips-for-pro-level-video-editing/"><u>New Mastering Adobe Premiere Top 6 Essential Tips for Pro-Level Video Editing</u></a></li>
<li><a href="https://sound-optimizing.techidaily.com/audiovisual-clarity-how-to-extract-silence-from-web-based-media-files-for-2024/"><u>Audiovisual Clarity How to Extract Silence From Web-Based Media Files for 2024</u></a></li>
<li><a href="https://some-approaches.techidaily.com/in-2024-tools-and-gear-for-crafting-vlogs/"><u>In 2024, Tools & Gear for Crafting Vlogs</u></a></li>
<li><a href="https://facebook-video-footage.techidaily.com/outstanding-films-not-on-mainstream-lists-for-2024/"><u>Outstanding Films Not on Mainstream Lists for 2024</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-in-2024-top-15-audio-collections-matching-melodies-with-every-type-of-visual-narrative/"><u>Updated In 2024, Top 15 Audio Collections Matching Melodies with Every Type of Visual Narrative</u></a></li>
<li><a href="https://extra-information.techidaily.com/meme-design-excellence-guide/"><u>Meme Design Excellence Guide</u></a></li>
<li><a href="https://facebook-record-videos.techidaily.com/updated-customizing-your-channel-icon-banner-and-thumbnail-ideas-for-2024/"><u>[Updated] Customizing Your Channel  Icon, Banner & Thumbnail Ideas for 2024</u></a></li>
<li><a href="https://extra-skills.techidaily.com/new-pro-webcams-8-your-go-to-for-flawless-livestreams/"><u>[New] Pro Webcams 8  Your Go-To for Flawless Livestreams</u></a></li>
<li><a href="https://instagram-video-recordings.techidaily.com/in-2024-incorporating-instagrams-cutting-edge-filters/"><u>In 2024, Incorporating Instagram's Cutting Edge Filters</u></a></li>
<li><a href="https://extra-guidance.techidaily.com/new-pro-audio-recording-the-ultimate-audacity-course/"><u>[New] Pro Audio Recording  The Ultimate Audacity Course</u></a></li>
<li><a href="https://fox-helps.techidaily.com/updated-2024-approved-crafting-visual-stories-in-minutes-using-windows-8-movie-maker/"><u>[Updated] 2024 Approved  Crafting Visual Stories in Minutes Using Window's 8 Movie Maker</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/new-becoming-an-active-participant-in-tiktok-lives/"><u>[New] Becoming an Active Participant in TikTok Lives</u></a></li>
<li><a href="https://android-location-track.techidaily.com/how-to-track-realme-note-50-location-by-number-drfone-by-drfone-virtual-android/"><u>How to Track Realme Note 50 Location by Number | Dr.fone</u></a></li>
<li><a href="https://voice-adjusting.techidaily.com/updated-in-2024-audio-absence-efficient-ways-to-extract-silent-videos-from-iphone-recordings/"><u>Updated In 2024, Audio Absence Efficient Ways to Extract Silent Videos From iPhone Recordings</u></a></li>
<li><a href="https://extra-skills.techidaily.com/master-the-mix-incorporating-and-refining-music-into-canva-projects-for-2024/"><u>Master the Mix  Incorporating & Refining Music Into Canva Projects for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/updated-recommendation-best-websites-for-downloading-snapchat-ringtone/"><u>[Updated] Recommendation  Best Websites For Downloading Snapchat Ringtone</u></a></li>
<li><a href="https://iphone-unlock.techidaily.com/how-to-unlock-disabled-iphone-11ipad-without-computer-drfone-by-drfone-ios/"><u>How to Unlock Disabled iPhone 11/iPad Without Computer | Dr.fone</u></a></li>
</ul></div>
