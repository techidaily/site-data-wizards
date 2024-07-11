---
title: Transforming Tarnished Tracks with FFmpeg
date: 2024-07-10T06:42:07.014Z
updated: 2024-07-11T06:42:07.014Z
categories:
  - repair-tools
description: This Article Describes Transforming Tarnished Tracks with FFmpeg
excerpt: This Article Describes Transforming Tarnished Tracks with FFmpeg
keywords: FFmpeg Audio Restoration,FFmpeg Track Conversion,Audio Repair with FFmpeg,Enhancing Audio Quality Using FFmpeg,FFmpeg Noise Reduction Techniques,Audio Editing with FFmpeg for Beginners,FFmpeg for Audio Transformation and Recording
thumbnail: https://thmb.techidaily.com/259362f05442761cee2c53bd4a987280fdd7ced53308719769d03bba8108cbbd.png
---

## Transforming Tarnished Tracks with FFmpeg

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
<li><a href="https://data-wizards.techidaily.com/keep-your-videos-in-shape-and-sound/"><u>Keep Your Videos In Shape and Sound</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fixing-damaged-mp4mov-videos-with-ease-a-step-by-step-guide-using-vlc/"><u>Fixing Damaged MP4/MOV Videos with Ease: A Step-by-Step Guide Using VLC</u></a></li>
<li><a href="https://data-wizards.techidaily.com/troubleshoot-and-repair-disrupted-movies-with-this-simple-guide-to-diy-methods-of-fixation-including-tips-on-cleanup-techniques-for-final-output-quality/"><u>Troubleshoot and Repair Disrupted Movies with This Simple Guide to DIY Methods of Fixation, Including Tips on Cleanup Techniques for Final Output Quality</u></a></li>
<li><a href="https://data-wizards.techidaily.com/memory-mercy-rescue-deleted-snapshots/"><u>Memory Mercy: Rescue Deleted Snapshots</u></a></li>
<li><a href="https://data-wizards.techidaily.com/how-do-i-fix-an-unsupported-video-codec/"><u>How Do I Fix an Unsupported Video Codec?</u></a></li>
<li><a href="https://data-wizards.techidaily.com/versatile-tools-flawless-repair-across-systems/"><u>Versatile Tools: Flawless Repair Across Systems</u></a></li>
<li><a href="https://data-wizards.techidaily.com/fixing-caught-on-video-code-0xc10100be/"><u>Fixing Caught on Video Code 0XC10100be</u></a></li>
<li><a href="https://data-wizards.techidaily.com/resolving-unsupported-video-playbacks/"><u>Resolving Unsupported Video Playbacks</u></a></li>
<li><a href="https://data-wizards.techidaily.com/cleaning-corrupt-vids-mac-solutions-to-look-forward-to/"><u>Cleaning Corrupt Vids: Mac Solutions to Look Forward To</u></a></li>
<li><a href="https://data-wizards.techidaily.com/perfect-your-videography-skills-with-the-leading-10-video-repair-programs-for-both-mac-and-pc/"><u>Perfect Your Videography Skills with the Leading 10 Video Repair Programs for Both Mac & PC</u></a></li>
<li><a href="https://data-wizards.techidaily.com/resolving-codec-compatibility-hurdles/"><u>Resolving Codec Compatibility Hurdles</u></a></li>
<li><a href="https://data-wizards.techidaily.com/optimize-video-playback-end-freezing-in-vlc/"><u>Optimize Video Playback - End Freezing in VLC</u></a></li>
<li><a href="https://data-wizards.techidaily.com/restore-pro-cleaning-up-corrupt-media/"><u>Restore Pro: Cleaning Up Corrupt Media</u></a></li>
<li><a href="https://data-wizards.techidaily.com/techniques-for-repairing-damaged-nikon-videos/"><u>Techniques for Repairing Damaged Nikon Videos</u></a></li>
<li><a href="https://data-wizards.techidaily.com/data-savior-for-mac-owners-the-best-8-software-ranks-revealed/"><u>Data Savior for Mac Owners: The Best 8 Software Ranks Revealed</u></a></li>
<li><a href="https://data-wizards.techidaily.com/video-repair-tool-mac-and-windows/"><u>Video Repair Tool Mac & Windows</u></a></li>
<li><a href="https://data-wizards.techidaily.com/restoring-lost-video-content-with-flawed-nikon-files/"><u>Restoring Lost Video Content with Flawed Nikon Files</u></a></li>
<li><a href="https://data-wizards.techidaily.com/unlocking-fix-for-video-glitch-0xc10100be/"><u>Unlocking Fix for Video Glitch 0XC10100be</u></a></li>
<li><a href="https://data-wizards.techidaily.com/efficient-email-service-restoration-an-analysis/"><u>Efficient Email Service Restoration: An Analysis</u></a></li>
<li><a href="https://data-wizards.techidaily.com/rebuild-lost-video-catalogs/"><u>Rebuild Lost Video Catalogs</u></a></li>
<li><a href="https://data-wizards.techidaily.com/cosmic-compilation-best-vids-and-positive-feedback/"><u>Cosmic Compilation: Best Vids & Positive Feedback</u></a></li>
<li><a href="https://data-wizards.techidaily.com/stellar-software-emerges-for-critical-quickbooks-recovery/"><u>Stellar Software Emerges for Critical QuickBooks Recovery</u></a></li>
<li><a href="https://data-wizards.techidaily.com/digitally-mending-fragmented-video-content/"><u>Digitally Mending Fragmented Video Content</u></a></li>
<li><a href="https://data-wizards.techidaily.com/unveiling-common-video-errors-and-simple-remedies/"><u>Unveiling Common Video Errors & Simple Remedies</u></a></li>
<li><a href="https://data-wizards.techidaily.com/solving-corrupted-media-issues-on-both-platforms/"><u>Solving Corrupted Media Issues on Both Platforms</u></a></li>
<li><a href="https://data-wizards.techidaily.com/new-era-in-accounting-repairing-quickbooks-with-stellars-solution/"><u>New Era in Accounting: Repairing QuickBooks with Stellar's Solution</u></a></li>
<li><a href="https://data-wizards.techidaily.com/unlock-the-power-of-coding-with-stellar-toolkit-essential-tricks-and-insider-knowledge-for-developers/"><u>Unlock the Power of Coding with Stellar Toolkit - Essential Tricks and Insider Knowledge for Developers</u></a></li>
<li><a href="https://unlock-android.techidaily.com/in-2024-bypassing-google-account-with-vnrom-bypass-for-infinix-hot-40-by-drfone-android/"><u>In 2024, Bypassing Google Account With vnROM Bypass For Infinix Hot 40</u></a></li>
<li><a href="https://tiktok-video-recordings.techidaily.com/new-embrace-the-thrill-how-to-engage-in-tiktok-livestreams-for-2024/"><u>[New] Embrace the Thrill  How to Engage in TikTok Livestreams for 2024</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-snickerscribble-program/"><u>[New] SnickerScribble Program</u></a></li>
<li><a href="https://some-techniques.techidaily.com/new-groundbreaking-gear-for-virtual-reality-players/"><u>[New] Groundbreaking Gear for Virtual Reality Players</u></a></li>
<li><a href="https://smart-video-editing.techidaily.com/updated-the-complete-guide-to-reversing-tiktok-videos-tips-and-tricks-for-2024/"><u>Updated The Complete Guide to Reversing TikTok Videos Tips and Tricks for 2024</u></a></li>
<li><a href="https://ai-voice-clone.techidaily.com/8-types-of-explainer-videos-with-best-examples/"><u>8 Types of Explainer Videos with Best Examples</u></a></li>
<li><a href="https://facebook-video-share.techidaily.com/new-the-ultimate-playbook-to-youtube-hub-mastery/"><u>[New] The Ultimate Playbook to YouTube Hub Mastery</u></a></li>
<li><a href="https://fake-location.techidaily.com/will-ispoofer-update-on-apple-iphone-se-drfone-by-drfone-virtual-ios/"><u>Will iSpoofer update On Apple iPhone SE | Dr.fone</u></a></li>
<li><a href="https://instagram-video-files.techidaily.com/in-2024-accelerate-the-performance-of-your-instagram-videos/"><u>In 2024, Accelerate the Performance of Your Instagram Videos</u></a></li>
<li><a href="https://youtube-help.techidaily.com/new-hidden-treasures-on-youtube-understanding-unlisted-footage/"><u>[New] Hidden Treasures on YouTube  Understanding 'Unlisted' Footage</u></a></li>
<li><a href="https://ai-video-translation.techidaily.com/updated-top-10-ai-subtitle-translators-for-content-creators/"><u>Updated Top 10 AI Subtitle Translators for Content Creators</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/updated-2024-approved-superior-10-audio-enhancement-solutions-your-guide-to-richer-mobile-sound/"><u>Updated 2024 Approved Superior 10 Audio Enhancement Solutions Your Guide to Richer Mobile Sound</u></a></li>
<li><a href="https://extra-approaches.techidaily.com/new-sharpening-your-minecraft-landscapes/"><u>[New] Sharpening Your Minecraft Landscapes</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/instagram-mastery-in-recreating-visual-stories-for-2024/"><u>Instagram  Mastery in Recreating Visual Stories for 2024</u></a></li>
<li><a href="https://change-location.techidaily.com/in-2024-what-is-the-best-pokemon-for-pokemon-pvp-ranking-on-vivo-t2-5g-drfone-by-drfone-virtual-android/"><u>In 2024, What is the best Pokemon for pokemon pvp ranking On Vivo T2 5G? | Dr.fone</u></a></li>
<li><a href="https://facebook-videos.techidaily.com/new-2024-approved-clearer-facebook-audio-addressing-half-volume-problems/"><u>[New] 2024 Approved  Clearer Facebook Audio  Addressing Half-Volume Problems</u></a></li>
<li><a href="https://fox-hovers.techidaily.com/new-ultimate-film-previews-collection/"><u>[New] Ultimate Film Previews Collection</u></a></li>
<li><a href="https://ios-unlock.techidaily.com/in-2024-locked-out-of-apple-iphone-12-pro-max-5-ways-to-get-into-a-locked-apple-iphone-12-pro-max-by-drfone-ios/"><u>In 2024, Locked Out of Apple iPhone 12 Pro Max? 5 Ways to get into a Locked Apple iPhone 12 Pro Max</u></a></li>
<li><a href="https://change-location.techidaily.com/pokemon-go-no-gps-signal-heres-every-possible-solution-on-vivo-s18-drfone-by-drfone-virtual-android/"><u>Pokemon Go No GPS Signal? Heres Every Possible Solution On Vivo S18 | Dr.fone</u></a></li>
<li><a href="https://sound-tweaking.techidaily.com/from-words-to-music-audio-conversion-of-textual-content-on-various-platforms/"><u>From Words to Music Audio Conversion of Textual Content on Various Platforms</u></a></li>
<li><a href="https://instagram-clips.techidaily.com/updated-2024-approved-the-compreeved-guide-to-saving-and-storing-reels/"><u>[Updated] 2024 Approved  The Compreeved Guide to Saving and Storing Reels</u></a></li>
<li><a href="https://smart-video-creator.techidaily.com/2024-approved-from-fast-to-furious-top-10-slow-motion-video-editing-solutions/"><u>2024 Approved From Fast to Furious Top 10 Slow Motion Video Editing Solutions</u></a></li>
<li><a href="https://tiktok-videos.techidaily.com/updated-eye-catching-tiktok-profiles-with-innovative-pfp-concepts/"><u>[Updated] Eye-Catching TikTok Profiles with Innovative PFP Concepts</u></a></li>
</ul></div>
