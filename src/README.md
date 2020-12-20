# Scripts

Useful scripts.

## `update.sh` Script

This is used to update a Debian-based distribution by doing an update, upgrade, dist-upgrade, etc. To make it prettier, consider installing `neofetch` and `figlet`:

```bash
$ sudo apt install neofetch figlet -y
```

Neofetch will show an operation system summary first, and neofetch is used to show the current hostname in large letters. For example:

```text
Debian-based System Update Utility v1.0.0-alpha.1
..............                                     root@kalivm 
            ..,;:ccc,.                             ----------- 
          ......''';lxO.                           OS: Kali GNU/Linux Rolling x86_64 
.....''''..........,:ld;                           Host: VirtualBox 1.2 
           .';;;:::;,,.x,                          Kernel: 5.9.0-kali4-amd64 
      ..'''.            0Xxoc:,.  ...              Uptime: 19 hours, 34 mins 
  ....                ,ONkc;,;cokOdc',.            Packages: 2650 (dpkg) 
 .                   OMo           ':ddo.          Shell: zsh 5.8 
                    dMc               :OO;         Resolution: 1920x1080 
                    0M.                 .:o.       WM: Xfwm4 
                    ;Wd                            Theme: Kali-Dark [GTK2/3] 
                     ;XO,                          Icons: Flat-Remix-Blue-Dark [GTK2/3] 
                       ,d0Odlc;,..                 Terminal: qterminal 
                           ..',;:cdOOd::,.         CPU: Intel i7-8565U (4) @ 1.992GHz 
                                    .:d;.':;.      GPU: 00:02.0 VMware SVGA II Adapter 
                                       'd,  .'     Memory: 2862MiB / 3937MiB 
                                         ;l   ..
                                          .o                               
                                            c                              
                                            .'
                                             .

 _ __ ___  _   _ _ __   ___ / _ \/ |
| '_ ` _ \| | | | '_ \ / __| | | | |
| | | | | | |_| | |_) | (__| |_| | |
|_| |_| |_|\__, | .__/ \___|\___/|_|
           |___/|_|   

[+] Update starting...
[+] STEP 1 of 4: Refreshing repository cache...
Hit:1 https://repo.skype.com/deb stable InRelease
Hit:2 http://kali.download/kali kali-rolling InRelease
Fetched 2,521 B in 1s (2,371 B/s) 
Reading package lists... Done
[+] Repository cache refreshed.
[+] STEP 2 of 4: Upgrading all existing packages...
Reading package lists... Done
Building dependency tree       
Reading state information... Done
Calculating upgrade... Done
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
[+] Existing packages upgraded.
[+] STEP 3 of 4: Upgrading packages with conflict detection...
Reading package lists... Done
Building dependency tree       
Reading state information... Done
Calculating upgrade... Done
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
[+] Upgrade processed.
[+] STEP 4 of 4: Cleaning up unused and cached packages...
Reading package lists... Done
Building dependency tree       
Reading state information... Done
Reading package lists... Done
Building dependency tree       
Reading state information... Done
0 upgraded, 0 newly installed, 0 to remove and 0 not upgraded.
[+] Package cleanup complete.
[+] Update complete.
[*] No reboot is required.
[*] System update complete.
                               
```
