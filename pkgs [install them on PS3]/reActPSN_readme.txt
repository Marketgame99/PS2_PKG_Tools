   reActPSN V3.20+ Quick Start Guide 

Basic function: Create aa user and run reActPSN to generate PSN license from USB/exdata.
Button controls: [X] = pressing and holding X button for 6 seconds when launching reActPSN.
[L1] Reinstall RAPs&EDATs from USB0/exdata or USB1/exdata folder.
[L2] Backup RAPs&EDATs to USB/reActPSN/pubPSN/rapxxxedatxxx.zip.
[R1] Backup reg&rif&edat to USB/reActPSN/BKxxxx.zip.
[R2] Backup full fixed NPD files to /USB/reActPSN/FixedPSN.
[O] Fix PSone/PSPminis/THEME & generate C00 activation edat license.
[X] Batch installs PS2 ISO from USBorHDD/PS2ISO. Flawlessly same as PSN pkg install. 
[∆] Fix PSN retail to free.stage1:fix all eboot and start hook,play,stage2:fix sprx edat etc.
[□] Batch make BD games loader PKG from GAMES&GAMEZ, output PKG to HDD0/packages or USB/.
[∆+R2] Fix PSN and make all NPD FIX pkg to USB/. same as PSN crack patch.
[R2+L2] Make only 'Fixedby reActPSN' NPD FIX pkg to USB/ or HDD0/packages.
[R2+L1] Make all files FIX pkg to USB/ or HDD0/packages. make sure have enough freespace.
[R1+L2] Make retail NPDRM files pkg to USB/ or HDD0/packages.
[R1+L1] Make retail all files pkg to USB/ or HDD0/packages. make sure have enough freespace.
[RIGHT] 8 seconds CEX2DEX&DEX2CEX.
[DOWN] Patch VSH to run reActPSN2.0 and enable screen shoot.
[LEFT] Disable/Enable all users rif license(remove/restore act.dat).

BDloader functions: Install and run any BDloader,after one KEY 18 secondes, play BD games.
[∆] BD games unloader.
[□] Batch make BD games loader PKG from GAMES&GAMEZ,output PKG to HDD0/packages or USB/.
[L1] Forced downgrad this backup game and patch from 4.20+ to 4.20. Dont forget install bubble pkg.
[LEFT] Delete current user's all games Trophy.

BDselector functions: Run reActPSN or BDloader, use last BD icon to change Mount Games from XMB. 
[L1]or[X]or[O] downgrad this backup game and patch from 4.20+ to 4.20, install bubble pkg.
[R1] Forced copy external(USB) game to internal(HDD0).
[R2] Remove this game's internal(HDD0) copy.

* BDdirectboot(GMmount),BDselector,BDloader all need insert a boot disk!

How to use:
<1> PLAY BD backup games with BDdirectboot(GMmount), supported CFW4.30 to CFW4.65+.
    Run reActPSN, 9 BD icon(7 last play games, 1 HDD new game, 1 USB new game) will be added.
<2> PLAY BD backup games with BDselector, supported CFW4.21 to CFW4.65+.
    Run reActPSN or BDloader,use last BD icon to change mount Games from XMB, 
    Run PS3 Games from orignal BD icon.
<3> PLAY BD backup games with BDloader.
    Run reActPSN or any BDloader with holding SQUARE to make all BDloader PKGs. 
    Install you favorite rBL_xxxx.pkg from HDD/packages or USB/.
    run it, waiting 18 secondes then play BD game, or directboot this game.
<4> Flawlessly to play all PSN contents.
   (1) Download psnstuff v1.82,download psn contents and store RAP&edat files.
   (2) Put exdata folder with rap's on usb, create 'aa' user and run reActPSN.
   (3) Install PSN and playing...
   (4) Put exdata folder with new raps on usb, holding L1 button for 8s and run reActPSN.
       Install new PSN and play new PSN games.
<5>  Play C00 type PSN games without rap&edat. [O] to activate it to full game.
<6>  Share your RAPs to others same as psnstuff, [L2] will help you.
<7>  Share your PSN crack patch to others.
   (1) Downloads PSN(1942 flower rain DLC) from PSN store(or install&play it with psnstuff).
   (2) Insert USB disk to usb0 or usb1.
   (3) Run reActPSN and holding ∆ triangle button for 6 seconds.
   (4) Play 1942,flower,rain,BD or PSN dlc.
   (5) Run reActPSN and holding triangle+R2 button for 6 seconds, then check your USB disk.
   (*) Do not insert any usb disk,[R2+R1] can gen >4G pkg on hdd0/packages.
<8> Flawlessly to install PS2 ISO. (Require CFW>4.20 and has been installed any RAP)
   (1) Copy few or many PS2 ISO files to USB/PS2ISO and run reActPSN with hold X.
   (2) Install bubble pkg on XMB. 
   (*) About >4G PS2 ISO. Must copy it to dev_hdd0/PS2ISO, do not insert USB, then [X]...
       PS2 ICON will be display if your have installed a full version MM.
<9> RISK FUNCTION!!! DO NOT TRY DOING IT IF YOU CAN NOT FIX A BRICKER.
   (1) SET QA, 3.55CFW, [RIGHT] [RIGHT].
   (2) 8s CEX2DEX DEX2CEX, REX4.21 to REX4.65.1 on slim, [RIGHT], its safe.
   (3) FIX VSH, works on every CFW. screen shot patch is added. 

===============================================================================
. reActPSN v3.20+
  Added support future CFW until new key added or code structure is changed. 
  It should works on all old CFW. tested on CFW3.55 4.21-4.65, working very well.

===============================================================================
. reActPSN v3.17
  Added support DEX4.65.
  Only this tool has fixed random black screen bug when play external directoy games.

===============================================================================
. reActPSN v3.16
  Added support CFW4.65.
  Only this tool has fixed random black screen bug when play external directoy games.

===============================================================================
. reActPSN v3.15
  Fixed CFW4.60 new crash bug when connected some USB storage.
  Added support backup games from internal folder GAMEZ.
  Fixed CFW4.60 DLC 0x80010038 error.

===============================================================================
. reActPSN v3.14 beta
  Added support DEX4.55 CFW4.60.
  CFW4.60 maybe added anti-USB storage cheching,RADOM crash bug does not fixed yet.
  
===============================================================================
. reActPSN v3.13
  Enhanced bddirectboot game list algorithm, 
  Fixed several bugs.

  Improved nine straight games to start the list of algorithms, fixes a few minor bug. 
  So far, all three run game disc backup method has been basically perfect. 
  
  Compared with the other two managers of the advantages and disadvantages: 
  Do not need to set up, to avoid crashes: mm need to set BD mirror (libfs), incorrect settings may crash. 
  Support built-in external libfs: iris only support built-in, when some external game may crash. 
  Does not destroy the file structure: iris when using BDEMU will move to the root directory of the game may cause the game to be lost. 
  Support multi-game straight start, support perfect downgrade. Choose the game is simple and quick. 
  bdselect graphical interface of the most beautiful, bddirectboot support icon animation and sound. 
  Does not support free disk free disk usefulness. 
  Does not support the ISO, ISO requires cobra, the cobra new system is not stable, it is not very convenient not support DEX.ISO downgrade. 
  reActPSN is the only supported PSN and disc games homebrew versatile tool 
  Author: Shenzhen, China zjq. 
  developer SHENZHENzjq. 
 
  Very simple to use, put the boot disk, external (or not take) a game removable hard disk, run reActPSN, 
  Started directly under the original disc icon to add multiple games., Or the final game of a CD-ROM icon and select Run from the original disc icon place.

===============================================================================
reActPSN v3.12
. Added auto copy external splited game to HDD0/GAMES for bdselector.
. Added forced copy external splited game to HDD0/GAMES for bdselector & bdloader.
. Added forced remove game's internal(HDD0/GAMES) copy  for bdselector & bdloader.
. Added supported CFW4.55.

===============================================================================
reActPSN v3.11
・ Added BDselector safe mode, support launch game from orignal BD icon.
・ Added professional(fix seg6001) downgrade backup games & patches to BDselector & BDloader.
・ Added forced repair incorrect downgraded by other game managers.
・ Added remove webmans lastgame.txt, so it works very well on cobra CFW.  

reActPSN v3.10
・ Added new payload named GMmount, Direct boot any game from XMB is possible.
・ This version support max 9 directboot games,
・ include 7 last played games, 1 HDD0 new game, 1 USB new game.

reActPSN v3.02
・ Added supported CFW4.53.
・ Removed splited USB games from BD selector list.
・ Added truly downgrade BD games from 4.21+ to 4.20 in BDselector.

reActPSN v3.01
. Added BDselector from XMB, 2 seconds changes PS3 game.

reActPSN v3.00
. Added self-replicatable BDloader, supported CFW4.21 to DEX4.50.

reActPSN v2.28

Basic function: Create aa user and run reActPSN to generate PSN license from USB/exdata.
Button basic: Launch with [X] and hold the following buttons for 8 seconds when launching reActPSN:
[L1] Reinstall RAPs & EDATs from USB0/exdata or USB1/exdata fold.
[L2] Backup RAPs & EDATs to USB/reActPSN/pubPSN/rapxxxedatxxx.zip.
[R1] Backup reg & rif & edat to USB/reActPSN/BKxxxx.zip.
[R2] Backup full fixed NPD files to /USB/reActPSN/FixedPSN.
[O] Fix PSone/PSPminis/THEME & generate C00 activation edat license.
[X] Batch installs PS2 ISO from USBorHDD/PS2ISO. Flawlessly same as PSN pkg install. 
[/\] Fix PSN retail to free.stag1:fix all eboot and start hook,play,stag2:fix sprx edat etc.
[SQUARE] Same as [/\], it try to search all files and run slowly.
[/\+R2] Fix PSN and make all NPD FIX pkg to USB/. Same as PSN crack patch.
[R2+L2] Make only 'Fixedby reActPSN' NPD FIX pkg to USB/ or HDD0/packages.
[R2+L1] Make all files FIX pkg to USB/ or HDD0/packages. make sure have enough freespace.
[R1+L2] Make retail NPDRM files pkg to USB/ or HDD0/packages.
[R1+L1] Make retail all files pkg to USB/ or HDD0/packages. make sure have enough freespace.
[RIGHT] 8 seconds CEX2DEX & DEX2CEX.
[DOWN] Patch VSH to run reActPSN.
[LEFT] Disable/Enable all users rif license(remove/restore act.dat).

How to use:
<1> Flawlessly to play all PSN contents.
   (1) Download psnstuff v1.82,download psn contents and store RAP & edat files.
   (2) Put exdata folder with rap's on usb, create 'aa' user and run reActPSN.
   (3) Install PSN and playing...
   (4) Put exdata folder with new raps on usb, holding L1 button for 8s and run reActPSN.
       Install new PSN and play new PSN games.
<2>  Play C00 type PSN games without rap & edat. [O] to activate it to full game.
<3>  Share your RAPs to others same as psnstuff, [L1] will help you.
<4>  Share your PSN crack patch to others.
   (1) Downloads PSN(1942 flower rain DLC) from PSN store.(or install & play it with psnstuff)
   (2) Insert USB disk to usb0 or usb1.
   (3) Run reActPSN and holding /\ triangle button for 8 seconds.
   (4) Play 1942,flower,rain,BD or PSN dlc.
   (5) Run reActPSN and holding triangle+R2 button for 8 seconds, then check your USB disk.
   (*) Do not insert any usb disk,[R2+R1] can gen >4G pkg on hdd0/packages.
<5> Flawlessly to install PS2 ISO. (Require CFW>4.20 and has been installed any RAP)
   (1) Copy few or many PS2 ISO files to USB/PS2ISO and run reActPSN with hold X.
   (2) Install bubble pkg on XMB. 
   (*) About >4G PS2 ISO. Must copy it to dev_hdd0/PS2ISO, dont insert usb, then [X]...
       PS2 ICON will be display if your have installed a full version MM.
<6> RISK FUNCTION!!! DO NOT TRY DOING IT IF YOU COULD NOT FIX A BRICKER.
   (1) SET QA, 3.55CFW, [RIGHT] [RIGHT].
   (2) 8s CEX2DEX DEX2CEX, REX4.21 or REX4.46 on slim, [RIGHT], its safe.
   (3) FIX VSH, should works on every CFW (except ro4.40 v1.0?, I forgot).


reActPSN v2.27
First OFFLINE PSN license generator. 

reActPSN v2.x needs a vsh.self with an 8 byte patch. Some CFW like Rebug has the patch already applied.

Import new raps: press L1(6s) and run reActPSN, all usb exdata raps will be added to user reActPSN 2.0 xx xx
Backup raps: press L2(6s) and run reActPSN, all raps will be copied to usb/reActPSN/pubPSN/exdata folder.

***********************************

reActPSN v2.27 (Minor changes): 

1: Triangle fix mode now supports CFW 4.46 CEX, 4.46DEX is not supported.
2: Fixed L2 backup rap small bug.

***********************************

ReActPSN v2.26 

1: [Triangle] fix mode support up to CFW4.41.
2: [Triangle + L1], [Triangle + L2] downgrade will automatically generate a small SFO downgrade pkg that can be installed  from
Install Package Filesin the XMB-game, or from REBUG's Package Manager > PlayStation Network Content. 
3: Added [left] button mode, force to delete the current user's trophy file to solve the problem of games that can not be registered due the trophies.
4: Rewrite PS2 ISO import mode using [X], with PSN installation container is no longer needed, and install three times faster. 

***********************************
reActPSN v2.25 with support to fix edat 4.0

1:
[Triangle] fix mode support up to CFW4.40.

Hold [Triangle] button for ordinary fix mode: do not modify the version number.
Run the first time to crack all EBOOT.BIN, run the the second time to fix the sprx / edat in the games.

Hold [Triangle] + [L1] to fix EBOOT with 3.41 keys, and fix edat 4.0.

Hold [Triangle] + [L2] to downgrade EBOOT to 4.20.
Cracking the game this way, does re-sign the EBOOT and allows to boot games on 4.20 CFW and later.

2: 
Hold [Down] button on D-PAD for automatic patch of VSH import authorization . Supports 3.41, 3.55 CFW and OFW, 3.60 CFW 3.60 and 4.40 CFW.

3:
Hold [Right] button on D-PAD for eight seconds for CEXDEX conversion. Support for CFW4.30. The console must be QA flagged on 3.55CEX. 

The software does not support the 4.40 DEX converted and converting a Rogero 4.40 v1.03 will brick the console.

4:
PS2 conversion speed improvements to 12MB/s, now is the most accessible and user-friendly conversion method.

Also added a progress bar when importing the authorizations (rap/edats) [holding L1 or renaming the user account to 'aa']

--------------------------------------
reActPSN v2.24b1 with support for import PS2 ISO from XMB

1. Run the pkg.bat in the SOLTPKG directory to create the PS2 containers installation files ("slots").
   Then copy the PKG files to the root of the USB drive and install on them PS3.
   Depending on your needs, the suggested installation order is n to 1
2. PS3 insert USB device, run reActPSN v2.4 from the XMB, and press the x button for about 6 seconds
   it will automatically generate some directories, also generate the PS2 default authorizations.
3. Copy PS2 ISO file to a USB drive under the /reActPSN/ISOPS2 directory.
   PS3 insert USB device, run reActPSN v2.4 from the XMB, and press the x button for about 6 seconds
   wait until it finish the import andreturns to XMB.

   Files larger than 4GB can be copied to the/dev_hdd0/ISOPS2 directory
   Do not plug in a USB drive, run reActPSN v2.4 and press the x button to import.

Depending on the number of PKG that you have installed, you can import up to 99 ISOs.

ISO support Chinese file name.
The absence of () is required to import the file name.
To import into a specifed PS2 container include the the number enclosed in parenthesis as prefix.
For example, (1) Contra.ISO, (2) Chessmaster.ISO will be imported into slots 1 and 2 respectively.

Usually you only need to perform step 3, when you want to import and run a different PS2 ISO.
If the same game has been imported, it does not repeat the import to save time.

Unfortunately, the new PS2 game does not displays in XMB icon once a game is modified.
Delete older PS2 saved data after importing, in Manage saved data (PS2) to shows the real PS2 TITLE ID and the file name of the ISO.

It’s just a beta1 version, feedback of problems are welcome.


ReActPSN v2.23 Features:

・Add set QA extra flag when do CEX2DEX.
    v2.23 Only support C2D2C2D.. Not support D2C2D2C.., 
    it will brick u console if you never set QA extra flag before!
    Beep3+reboot CEX2DEX ok, Beep2+reboot DEX2CEX ok.
・Add patch vsh.self to support reActPSN2.0 rap model for all 3.41 & 3.55MFW & CFW430.
    Run reActPSNv2.23 and keep pressed BUTTON_DOWN about 8s, 
      after 30s then auto reboot.


ReActPSN v2.22 Features:

- The triangle button to crack the mode new 0x4, 0x7, 0xA, 0xD 0x10 the NP KEY support previous versions only support 0x1 type of the NP KEY.
- reActPSN v2.22 one step conversion: CEX (retail) to DEX (development) 
  > Before using this feature, please backup your FLASH!
  > All work on 3.55CFW and 3.55DEX peek & poke firmwares.
  > To activate: Run reActPSN and continue to pressing the RIGHT ARROW key for about 8 seconds,
    the machine will automatically restart after a successful conversion.
- CEX-to-DEX / DEX-to-CEX: Retail machine can be converted to a development machine, development machine can also be converted into a retail machine.
  > Please upgrade to DEX3.55 or 3.55CFW.
  > 256M NAND FLASH models untested 16M models to test the more than 50 times occasionally crash, but no brick.
  > Please have the FLASHER tools first try, there are a lot of success without brick report the average user to use this feature.



             reActPSN v2.20  (TRIANGLE fixed mode update)

1. Compatible with reActPSN v2.00.
2. Changed v2.0 backup file format to one zip file, backup speed fast more than 20 times.
    Fixed some rap long name bug.
3. Added edat fix mode, this mode works on any CFW, no need aa user or patched vsh.self.
    (1) Auto generate XMB purchase full activation edat, no need any raps or official edat files.
          Install official LIMBO.pkg TERIS.pkg HCU.pkg, 
          Run reActPSNv2.10 and keep pressed BUTTON_CIRCLE about 6s, all will be full working.
          Higher PS3_SYSTEM_VER also be fixed in SFO files (old save data could not be accessed).
    (2) Fix PSone PSP THEME with raps. raps from USB0(1)/exdata/*.rap .
          Install official PSone PSP THEME, copy raps to USB0(1)/exdata/ folder(not in subDirs!).
          Run reActPSNv2.10 and keep pressed BUTTON_CIRCLE about 6s, all working.
          And also fix PARAM.SFO to enable PSP remote, higher PS3_SYSTEM_VER also be fixed.
    (3) DLC, in game purchase PSN games now working on this fix mode(not sure for all PSN contents).
         Install official 1942.pkg Flower.pkg ,  copy raps to USB0(1)/exdata/ folder(not in subDirs!),
         Run reActPSNv2.20 and keep pressed BUTTON_TRIANGLE about 6s, all will be working,
         1942 is full working, Flower still has a error,  (press PS KEY)exit to XMB, 
         Run reActPSNv2.20 again and keep pressed BUTTON_TRIANGLE about 6s, Flower is full working.

         DLC also could be fixed with this TRIANGLE mode.  
         As I know, EBOOT.BIN with self.flag=4 does not works, and don't run MM with BDEMU2 mode.
         All fixed contens maybe still woking on cfw4.0 with data transfer(All signed with .......).
         TRIANGLE mode only fix dev_hdd0/game/TITLE_ID/ BIN-sprx-edat-EDAT-self files. 
         There is a BUTTON_SQUARE mode searching for all type files, but slowly.
    (4) Backup v2.10 & v2.20 full fixed PSN contents.
         Run reActPSNv2.20 and keep pressed BUTTON_R2 about 6s, 
         All fixed games(only full working)  backup to /dev_usb000(1)/reActPSN/FixedNPD
    
Please use reActPSN v2.00 Raps mode. Only Raps mode works flawlessly for all PSN contents!     

XMB purchase-- purchase menu is in XMB. CFW3.55, target PSN LOGO, press BUTTON_TRIANGLE. 
                            Activated with edat and rif, trial and full with one installed package.
in game purchase PSN games -- purchase menu is in game.  Activated with one rif only.

*******************************************************************************************
 
               reActPSN v2.00
   First OFFLINE PSN license generator. 

Backup license without any private information.
Power on PS3, Running of all PSN contents same as official activation.
reActPSNv 2.0 must needs an 8byte patch for vsh.self.
Compatible with reActPSN v1.11.

**************************
Name: reActPSN v2.00.pkg
Size: 173KB 
Releaser: Hotz8611
**************************

Working on CFW3.41 & CFW3.55, 256M NAND ROM model no tested!
Maybe not work on:
 256M NAND FlashRom consoles(no tested),
 OtherOS++(this cfw seems does not support PSN game activation),
 Virgin PSN console with cfw3.55K
  (Never login PSN before, error 80010601. please upgrade it to rebug3.55)


This tool only reactivates reActPSN1.10 or later version backup's exdata.
Backup location: dev_usb000/reActPSN/BK00xx, act.dat act.key xx.rif, private data backup. Don't share it.
Backup location: dev_usb000(1)/reActPSN/pubPSN/exdata, only xx.edat and xx.rap(16B), without any private information.


This tool has 8 functions.

1. Create new user aa, copy exdata folder (xx.edat xx.rap or any subfolders with v1.10 v2.0 backup) to dev_usb000 or dev_usb001 root.
  Run it, it will regenerate license from usb exdata to /dev_hdd0/home/0000000x(aa user)/, 
  And rename aa user name to "reActPSN 2.0 xx.rif xx.edat",when finished then auto reboot.

2. Run it and keep pressed BUTTON_CIRCLE about 6s, it does make a forced full backup to dev_usb000/reActPSN/BKxxxx.
   xx.edat xx.rap also backup to dev_usb000(1)/reActPSN/pubPSN/exdata folder.
   (changed this to edat fix mode after ver2.10)    
3. Run it and keep pressed BUTTON_L1 about 6s, it does make a forced license generation from dev_usb000(1)/exdata to user "reActPSN 2.0 xx"

4. Run it and keep pressed BUTTON_L2 about 6s, xx.edat xx.rap also backup to dev_usb000(1)/reActPSN/pubPSN/exdata folder.

5. Run it and keep pressed BUTTON_R1 about 6s, it does make a forced full backup to dev_usb000/reActPSN/BKxxxx.
   xx.edat xx.rap also backup to dev_usb000(1)/reActPSN/pubPSN/exdata folder.

6. Run it and keep pressed BUTTON_R2 about 6s, it does make a lv2 dump to /dev_usb000/dump.bin 
   
7. Run it once time when you log in yourself or replayGamesN_Cyyyy user account, 
  it will reactivate yourself or all same yyyy users license. don't use this function again.
  But it also restores act.dat from act1.dat.

8. Run it, you can't login PSN again. All important information send to PSN is random! (Faked ID)


***********************************
TUT for how to run full PSN games:
***********************************

1. Install reActPSN v2.00
2. Run it and keep pressed BUTTON_R1 about 6s, make a forced full backup to dev_usb000/reActPSN/BKxxxx.
   Backup xx.edat xx.rap to dev_usb000/reActPSN/pubPSN/exdata folder.
3. Download vsh.self.patcher.for.reActPSN2.pkg, auto patch your CFW.
3. Import license from exdata folder
   Copy exdata folder to USB media root, inserted it to dev_usb000 or dev_usb001 port.
   Create a new ps3 account aa
   Run reActPSN, auto reboot.
4. Delete all replayGamesN_Cyyyy(v1.1x generation) user account.  
5. Enjoy official PSN games now, 
   Run PSN games.
