---
title: "How to Hack any Windows PC using a bootable USB"
layout: post
---

Note: this Post is incomplete.

So, Are you pissed off that you Company/School has given you a shitty laptop and worse you can't even install/play games on it because you need Direct3D and you can't install Direct3D without Admin privileges and those imbeciles refuused to give you Admin Privilages! ( THANKS OBAMA )

This is a basic step by step Tutorial on how to Hack any Windows PC using a bootable USB.

The only requirement is that you need a USB, obviously.

## Make a bootable USB with Arch Linux Installed

First of all, install Rufus if you haven't already. Then download the Arch Linux OS from here. It isn't necessary to use Arch Linux, but that's what this tutorial is based on. You could use Ubuntu or Kali or some other OS but I tried it with Arch and I can confirm that it indeed works. Can't say the same for the Other OS's.

## Boot to the USB

Make sure that your USB is connected and then Restart your PC. Then once you get to the Lock Screen, Restart your PC again but this time, while holding the SHIFT key. Then once the Computer restarts, you will see a boot device selection Menu. Select your USB from the given Option ( Usually the Name of your USB ). Now your PC will Boot into the OS installed in your USB ( Arch Linux In our case ).

## Let the Hacking Begin

Once you boot into Arch, don't get scared by the CLI, you just haven't configured the GUI yet ( we won't do that in this tutorial ). Everything we need can be done in the CLI. 

Type in `cd ..` a couple times to make sure that you're on the root level.

Now you can see several folders named `mnt`, 