# unlimited_hotspot_hack
<img width="800" height="600" alt="kitten" src="https://github.com/user-attachments/assets/a1860af9-1683-41d3-b1e3-213c97155040" />

Are you tired of not having a hotspot, despite having unlimited data on your phone? 
 
The Unlimited Hotspot Hack allows an unlimited mobile hotspot to work on a single-device data plan (presumably single-device unlimited data plan), but it requires a rooted Android as well as anti-DPI tools. This project is a work in progress. Inspired by Glytch from the Hak5 YouTube channel, who made a video about the fundamentals of this bypass trick back in the days of COVID, when he was camping out in the Rockies in his van. The Unlimited Hotspot Hack is primarily designed for wandering nomads such as Glytch and myself. After all, no matter where I may roam, I like having a hotspot, but I sure don't like paying those outrageous hotspot plan prices. And even if you're not a wanderer but a homebody, the unlimited hotspot hack allows you to save a significant amount of money by not having to pay an ISP bill. All you have to do is pay for unlimited data on one mobile device.


## how to use 
Once you have a rooted Android (rooting process not outlined here, go to XDA for more info about rooting), simply load the module with your favorite module manager. The module is the .zip file named unlimited-hotspot-repacked.zip. Your module manager can be anything, with some popular choices being Magisk Manager, KernelSU, SukiSU, and KSU-NXT. Ensure the module is enabled and has root privileges. Once the module is working, you will still need to obfuscate your hotspot from your ISP using a combination of anti-DPI software and firewall rules, so make sure you read the next section if you actually want the unlimited hotspot hack to work for you.

## limitations [IMPORTANT]
This software has quite a few important practical limitations, which can all be overcome in some way or another. 
- Since a rooted Android is required, you can't run this hack on most phones, especially not on iPhones.
- Your average Joe friends will NOT be able to use your hotspot, because any clients of the unlimited hotspot hack must be running anti-DPI software as well as firewall rules which modify outgoing packet TTL. If you try to run this hotspot without modifying TTL and running an anti-DPI program such as Zapret, your ISP (mobile carrier) will detect this hack, and then your speed will be throttled extremely low. You'll be able to tell this is happening because you'll still have internet, but it will be very, very slow.
- The only client device that I have tested and confirmed compatible with this hack is a Windows laptop and a Linux laptop, both of which must be running anti-DPI software and TTL modifiers via firewall rules. With that said, it is 100% possible to run an Android as a client, with the process currently being much simpler for a rooted Android. It is also 100% possible to run a MacBook or iMac or Mac Pro, but of course you'll need anti-DPi measures in effect and a TTL spoofer. It is also theoretically possible to run an iPhone as a client, although this functionality has not been implemented yet because it requires some precise VPN configuration. The process for an unrooted Android should be not too different from an iPhone, but no devices except Windows and Linux PC's have been tried by K0K0SH@. If you have any questions, create an issue and I'll be happy to work through it with you.
- Every ISP works a little differently, so unexpected results are possible   

## death and revival of this repo
As of Summer 2026, the unlimited_hotspot repository by felikcat (which is the basis for this repository) has been made private. Luckily, the legendary hacker K0K0$H@ (among others) was able to recover it with the WayBack machine, and ChatGPT was able to repack the repository into a working module. 

## work in progress notice
This repository is still a work-in-progress, and it's far from finished. Therefore, the functionality is not yet complete. Worse still, most resources on the web about how to do this trick have vanished as the internet gradually dies. I was only able to recovery this repo, which I'm not the original author of, from the WayBack machine. The original author, as noted previously, is github/felikcat

## other notes
- It is possible to run the unlimited hotspot bypass without requiring a module or a root manager. In theory, it's one line of code with a root shell such as ADB shell or Termux. This is not recommended whatsoever. The module offers significant advantages, such as being easily toggleable, simpler to install, and overall a better experience.
- For clients that cannot run local anti-DPI measures, such as unrooted Androids and iPhones, it is possible to perform all anti-DPI on the host side. One way to do this in theory is to route through a VPN. K0K0SH@ has not attempted this yet, but people on the web claim to be successful with this method. In short, it is possible to extend the module within this repo so that any client, even an iPhone, can connect to the hotspot. Unfortunately, this remains on K0K0$H@'s long to-do list.  
