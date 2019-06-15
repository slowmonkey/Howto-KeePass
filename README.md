# Howto-KeePass
This document goes through how to set up kee pass on google drive.

## What is KeePass
Keepass is a light-weight and easy-to-use password manager.

## Setup
1. Create a Password folder on your Google Drive
2. Install Google Drive on the machine you wish to use KeePass on. (My advise is to sync only the required folders. For me I just sync the Password folder and leave everything else unsync'd)
3. Go to: http://keepass.info/ and download the latest 2.x version KeePass zip file.
4. Extract the KeePass zip file into your Google Drive Password folder.
5. Create a link to your taskbar to the KeePass.exe in your GoogleDrive
6. Create a new database, I just use myName.kbdx, on the Google Drive Password folder.

You now have KeePass setup! It's as easy as that.

## Plugins
Some useful plugins that I use.

Many more plugins can be found at: http://keepass.info/plugins.html

### Plugins - KeeAgent
The KeeAgent plugin adds SSH agent support to KeePass. It emulates Pageant.

1. Download KeeAgent.plgx from: http://lechnology.com/software/keeagent/
2. Place it in Google Drive/Passwords/KeePassx.x.x/plugins folder


## Synchronisation Workflow
To ensure that your database doesn't get corrupt I have a peculiar workflow.
It's what works for me so feel free to do something else if you find something better.

**NOTE:**
If you are using google drive as your cloud storage
- Only save your database (Ctrl+S) if the kbdx file is not synchronising. You can see this my the synchronisation icon on the google drive folder on your windows explorer.
- Similarly if you synchronise the database to another database make sure neither databases (kbxd files) are being synchronised.

What I like to do to ensure my database is backed up and corruption free is to do the following:

1. Create a database for each major computer I use the file on.

EG.
myName-Home.kbdx
myName-Work.kbdx
myName-Master.kbdx
myName-Phone.kbdx

Here I've created one for home, work and my phone. The master database is my main backup that I make sure to synchronise to always.

2. Synchronise regularly to at least another database. For me I'm a bit paranoid so I always synchronise to all the databases. KeePass is very good with synchronisations so you don't really have to worry about conflicts.

Enjoy and stay secure!

