# How to Unroot your Phone (Samsung)
IK this is github and not some kind of tutorial webside but here ill explain how u do the long way of unrooting ur phone

So if your Phone is rooted you would see this in the app: https://play.google.com/store/apps/details?id=com.joeykrim.rootcheck

<img width="198" alt="image" src="https://github.com/NotUrLocalScripter/How-to-unroot-your-Phone/assets/126284768/3ccb7707-f188-4400-842c-495bacc42785">

Disclaimer i needed to unrot my phone cuz being in a bootloop and it deleted all my files so secure your data in an cloud or remember to copy them to a harddrive every few days.

How i factory reset my phone and all...

You can do the lazy way of going in magisk and uninstalling it and thats it but if thats not working...

## For any of the folowing steps please remove your sd and sim card. It might delete the data from them.

...and your phone is in an bootloop or smth like that let the battery drain, then plug an usb cabel into the pc and your phone (turned off), then hold the on/off button and the volume up key.

You should see the recovery mode, you can controll it with the volume keys (up/down) and on/off (enter) button and head to cache clear and after that go to factory reset, hit "enter"

Now you should startup the phone like normaly. 
(for me it worked but i installed magisk again and flashed but got into non fixable bootloop)
... Going into the recovery mode and repeating the steps doesnt help anymore for me at that point.

The only thing you should do now is look the bootloader, how do you do that? 
Just press volume up and down at the same time and then put ur usb cabel into the phone (needs to be in pc)

then there should be 3 options, hold volume up key and then disable bootloader and reset ur phone.

### Now!
- Mobile is still connected to ur laptop or PC. 
- Install the latest Odin3 version: https://odinflashtool.com/download/odin3-v3-14-4/ 
- Install your latest firmware from ur phone i downloaded mine here: https://www.sammobile.com/
- and unzip it.
- Now open Odin3 as administrator.
- On phone, you are still in the downloading menu and you cant skip it.

# Important please read all steps carefully
In Odin3
You are gonna see this:
<img width="655" alt="image" src="https://github.com/NotUrLocalScripter/How-to-unroot-your-Phone/assets/126284768/28cce4fa-6c65-482e-a09e-6171c5c0bdb6">
First:
Click on BL and select the BL file (starts with BL)
Second:
Click on AP and select the AP file (starts with AP)
Third:
Click on CP and select the CP file (starts with CP)
Fourth: 
Click on CSC and select the CSC file (starts with CSC - NOT THE HOMECSC!!!)
Fifth:
Hit start

Troubleshooting:
If error just replug in ur device and reopen Odin3 and redo the steps above.

Now its installing your firmware, dont interrupt the download!

And simply setup your phone.


Contact:
Discord: discordapp.com/users/1111619403830796319 / .Hellofellas

If it helped please like or smth or reply, ty.
