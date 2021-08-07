[![Say Thanks!](https://img.shields.io/badge/Say%20Thanks-!-1EAEDB.svg)](https://saythanks.io/to/thescripttiger%40gmail.com)

# Windows 911!!!  
Curated list of FREE emergency resources when you find yourself in the inevitable pickle with Windows. **PRs welcome!**

If you find yourself routinely using recovery tools on a daily basis (e.g. you are an IT Technician or similar), then you may also want to reference the below link for a more expansive tooling list:  
https://github.com/LV-Crew/Multiboot-USB-Stick/

# The No More Ransom Project  
The No More Ransom Project is not specific to Windows operating systems, but still a great place to start if you discover your files are being taken hostage by ransomware or if you just want to read more on how to prevent ransomware attacks. Their website provides support in multiple languages, prevention advice, an expansive repository of ransomware decryption tools, as well as quick links to report criminal ransomware incidents to the appropriate authorities within multiple countries, all free of charge and maintained by an international cohort of government agencies, private institutions, and other passionate individuals striving to rid the world of ransomware.  
https://www.nomoreransom.org/

# Utility Libraries  
Take your time when going through the below utility libraries and use them to build your own. Most, if not all, are entirely portable and don't require installation.

**Sysinternals**  
A go-to for Windows diagnostics, along with some other simple yet powerful utilities for both local and domain environments.  
https://docs.microsoft.com/en-us/sysinternals/downloads/

**NirSoft**  
NirSoft is a massive collection of simple yet effective utilities for both getting things done and just curiosities. It has utilities for everything from network forensics to local PC diagnostics.  
https://www.nirsoft.net/

# Must-Have Disks  
If you have Windows, you should have a disk burned from every single one of the below links that is appropriate for your system!!!

**UBCD**  
UBCD is good for any OS and is a collection of all those floppies people thought they wouldn't need anymore but can still save your butt in a bind, plus a whole lot more. It also currently comes with a freeware version of Parted Magic for all your partitioning needs, but they are working to replace it with their own UBCD distro in the future. With everything from virus scanners to password crackers to data recovery and memory diagnostics, this is definitely a must-have!  
http://www.ultimatebootcd.com/

**TechBench**  
The TechBench website may seem unassuming and maybe even shady, but it's actually home to a download link generator which generates links to various flavors of Windows that are downloaded directly from software-download.microsoft.com (See for yourself when you are given a download link!), so you don't need to worry about them being hacked and cracked versions that you might find floating around in torrents. With modern versions of Windows, always keeping an up-to-date version of your OS's install disk allows you the option to be able to reinstall your current OS without losing any licensing or even any data!  
So the next time you decide trying your hand at gambling with Windows updates that land you sitting in front of a "Desktop Location is not available" error with no recovery options, no taskbar, no explorer, and no clue what to do, just CTRL+ALT+DELETE into the Task Manager, More details to make the File menu appear, File, Run new task, Browse. Keyboard shortcuts and right-click options apply here just like they do in the explorer and you can use it to back up what you need to before executing the disk's setup.exe to reinstall. It should also be noted when stuck in a situation like this, you may have to run everything with administrative privileges. Also, by default the Task Manager browser only views "program" file types, so don't forget to change that to "All files" in the bottom right drop-down. Backing your important data up should always be a precautionary step, but if your install disk is newer than your current OS build it will most likely be able to reinstall without losing anything similar to an upgrade. Slightly older install disks may also work, but the older they are the more likely they are to require data loss.  
(As an additional note to the above situation, if you have Windows Update enabled and third-party antivirus installed, such as AVG, Avast, Kaspersky, McAfee, etc., make sure you DO NOT allow Windows Update to automatically install. If your connection is good, allowing it automatically download and wait for you is fine. And then before you manually trigger the Windows Update to begin installing the downloaded updates, DISABLE YOUR ANTIVIRUS. Microsoft has been crashing significant quantities of systems in recent updates due to conflicts with antivirus and they DO NOT provide support in these cases.)  
https://tb.rg-adguard.net/public.php

**Debian**  
If Windows just isn't working and you're on a deadline, you can always save your Windows partition for later by resizing it and squeeze Debian and a swap into new partitions, or just wipe everything and just go with Debian and a swap. Debian will just about run on anything while also supporting modern applications you need to get your work done, such as the LibreOffice suite which allows you to create, modify, and save Microsoft Office files (with the exception of VBA macros, which are not fully supported) and continue on with your work as if nothing happened. It supports low-RAM machines as well as can support many common office peripherals, such as printers and scanners, out of the box. If you're new to Linux and prefer the Windows look and feel, I'd recommend installing the LXQt desktop environment when prompted during the installation.  
https://www.debian.org/

# Antivirus Rescue Disks  
The above UBCD comes with many antivirus tools, but everyone has their preferred and trusted antivirus and most come with a portable rescue disk. If you suspect you're down hard due to viruses, give your preferred AV rescue disk a shot. If your AV product isn't represented here and has a rescue disk available, just send us a PR to get it added. It should also be noted the below list is presented in alphanumeric order without any intentions of implied preference.

**Avast Rescue Disk**  
This is not a download, but just instructions on how to make an Avast rescue disk from your installed Avast software.  
https://help.avast.com/en/av_abs/10/page_rescue_disc.html

**AVG Rescue CD**  
https://www.avg.com/en-ww/download.prd-arl

**Avira Rescue System**  
https://www.avira.com/en/download/product/avira-rescue-system

**Kaspersky Rescue Disk**  
http://support.kaspersky.com/viruses/rescuedisk

# Other Useful Tools

**SUPERAntiSpyware**  
SUPERAntiSpyware offers a portable version not requiring installation that comes with its newest signatures and you can copy/burn it to any medium and run it on an infected system.  
https://www.superantispyware.com/portablescanner.html

**Spybot – Search & Destroy**  
Safer-Networking's Spybot - Search & Destroy is a spyware and adware removal program. S&D doesn't search in files like an antivirus program for signatures, instead it knows where spyware and adware place there files and removes them. As S&D isn't an AV solution, it's highly recommended that this be used to complement and supplement an AV scan and not replace one. S&D also repairs the registry and other system configurations that can be affected by spyware and adware, something AV programs normally don't do. The below link is not a download, but instructions on how to make an S&D disk from your installed S&D software.  
https://www.safer-networking.org/features/bootcd/

**Malwarebytes Anti-Rootkit-Tool**  
If you think your system is infected with a rootkit, you may want to run the Malwarebytes Anti-Rootkit-Tool. It does require unpacking and it's not entirely portable, but it definitely gets the job done for rootkits it knows about.  
https://www.malwarebytes.com/antirootkit/

**YUMI – Multiboot USB Creator**  
YUMI (Your Universal Multiboot Installer), is the successor of MultibootISOs. It can be used to create a Multiboot Bootable USB Flash Drive containing multiple operating systems, antivirus utilities, disc cloning, diagnostic tools, and more.  
https://www.pendrivelinux.com/yumi-multiboot-usb-creator/

# More About ScriptTiger

For more ScriptTiger scripts and goodies, check out ScriptTiger's GitHub Pages website:  
https://scripttiger.github.io/

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=MZ4FH4G5XHGZ4)

Donate Monero (XMR): 441LBeQpcSbC1kgangHYkW8Tzo8cunWvtVK4M6QYMcAjdkMmfwe8XzDJr1c4kbLLn3NuZKxzpLTVsgFd7Jh28qipR5rXAjx
