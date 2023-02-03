# CBZ-Zipper

CBZ Zipper is a simple command in the right click context menu.

## About the Program

This is a simple reg file and bat file.

The bat file is the main program that zips and renames the folders to the  `.cbz` format

# How to Install

Installation is very simple. **HOWEVER!** you will need to use `regedit` witch  *Can* mess up your windows installation.
I recommend backing up your registry (however its not necessary).
For safety, follow the tutorial on editing the registry carefully.

If you don't like reading, I've made a video tutorial on how to install this program. [Video not uploaded yet](https://www.youtube.com/c/dividedby0)

## 7zip

First things first are, you need 7zip to make this program work 

[7zip Download](https://www.7-zip.org/) <--- This link will take you to the 7zip download page and will download the most recent version of 7zip.

## Where to put the bat file

really you can put the `.bat` file anywhere on your pc. however i recommend a subfolder in `C:` drive.
The example folder in the defualt reg file is `C:\User Bat Files`

DONT put the bat file in a folder you use a lot, if you accidentally open the bat file it will start ziping all folders in that directory. it doesn't delete files but it is annoying deleting the new accidently crated CBZ files.

## Regedit
**BE CAREFUL EDITING THE REGISTRY**

    Temp Decription, subject to change
    Install the .reg file.
    open regedit
    go to Computer\HKEY_CLASSES_ROOT\Directory\shell\CBZ Zipper\command
    change the path to where your bat file is
    DONOT delete the "%1" and keep the path in ""
And you are done!

# How To Use

    Temp Decription, subject to change
    right click a folder in a directory of folders you want to make CBZ
    clcik "CBZ Zipper" in the context menu.
    All the folders in the current working directory will be ziped and then renamed to contane the .cbz format


# About me

I dont know how to use markdown or git or github but ill laern the ladder and bring to you my program!

My spelling to horible FYI.

Feedback is greatly appreciated! (Unless its about my spelling)