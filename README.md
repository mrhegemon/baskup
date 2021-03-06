## What is Baskup? 📲 + 💬 = 📦

Baskup is a bash script and macOS app that are aimed at converting iMessages, which Apple stores on your local machine in non-readable iChat files, into human-readable .txt files that you can read and keep as backups on your computer.
Whether it's a group message, picture, audio file, iMessage, or SMS, Baskup will back it up.

### *Update: 12/19/2018* -- 🚧 Baskup 3.0 for Mac is under construction 🚧 ###
The Mac version of Baskup is under some construction in an effort to distribute the app on Apple's macOS app store. 

In the meantime, you can still use the command-line script on Github and keep an eye out for updates as they will be posted to this page.

### *Update: 11/16/2018* -- macOS Mojave updates
Due to Apple security improvements, macOS Mojave users will need to add the program to the System Preferences → Security & Privacy → Privacy → Full Disk Access pane. This allows Baskup to access messages.

Baskup script users will need to add their terminal application to the Full Disk Access pane. Please note that granting your terminal application Full Disk Access allows all scripts run within your terminal to have Full Disk Access. After you have run your backup, you should revoke Full Disk Access from your terminal app and regrant it access only when you plan on running a backup.

![screen shot 2018-11-16 at 1 10 55 pm](https://user-images.githubusercontent.com/5935411/48647550-2c7a0200-e9a1-11e8-832a-4500ea67e571.jpg)

### *Update: 10/23/2017* -- 🎉 Baskup 2.0 🎉

Download the MacOS app for contact recognition & timestamps

*Most future improvements to Baskup will only be available on the desktop version.*

## Why baskup? 

Baskup furthers the work of https://github.com/kyro38 's iMessage backup script by reducing the need for user input and backing up all of the user's messages. 

## How do I use the Baskup script? 

To use baskup:

Download Baskup from this page by clicking download zip in the top right corner and then unzip the download

From terminal:

![alt tag](https://cloud.githubusercontent.com/assets/5935411/8760632/23ce21b8-2cee-11e5-80d7-37c97505cd17.JPEG)

1. Run: cd (path of the downloaded baskup folder, i.e *cd ~/Downloads/baskup-master*)

2a. Run: *bash baskup.sh* to only backup messages 💬

2b. Run: *bash baskup.sh -a* to backup messages AND attachments 💬 + 📎

Your bask-up master folder will now begin to be filled with your backups. This may take some time, so be patient.

## All done
![alt tag](https://cloud.githubusercontent.com/assets/5935411/8760633/272d34c0-2cee-11e5-87c7-084d3bc8f21f.png)


#### Each folder will be named after the contact's phone number. Group chat's will be identified as "chat XYZ"

![alt tag](https://cloud.githubusercontent.com/assets/5935411/8760635/29201a04-2cee-11e5-9cc7-668b6a6e5ee0.png)

#### Within each directory you will find a directory for the attachments from that message, and the actual message text file. 

## Opening an issue

When opening an issue, please note the issue as either related to the bash script or the macOS version of baskup. For macOS, please include the version number in your issue log.
