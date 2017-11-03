# downdyn

The program downdyn was created by Sandia National Labs in 1996 to present the data gathered from a number of test wells.

Unfortunately, this program was written in VB3 and targeted at Windows 3.1. While it is possible to get this software running in a modern Windows installation, the support and instructions to do so are problematic.

As a simple alternative, downdyn can be installed in a virtual machine, making access to this old program quick and easy. Alternatively, the dosbox emulator has been ported to javascript making it possible to run old programs directly in a web browser.

## Update - downdyn in a web browser
For easy access to the original downdyn program, please follow this link with a modern web browser:

> http://downdyn.s3-website-us-west-2.amazonaws.com/

Chrome works best, but you might have luck with other browsers. Clicking on the emulator will steal the mouse - hit ESC to get it back. Older systems might bog down on this. If so, one of the options below might be a better solution.

For more old windows programs, checkout [Archive.org](https://archive.org/details/softwarelibrary_win3&tab=collection)


## Instructions - Virtual Machine Image
First, install Virtualbox on your machine (Please note the "dot-org")

https://www.virtualbox.org/wiki/Downloads

> You want the installer from the "VirtualBox platform packages" section. Dont worry about the "extension pack" links.

Next download the virtualbox machine image from this repository. 

https://github.com/wansco/downdyn/releases/download/2/DownDynImage.zip

Unzip and open the DownDyn.vbox file with Virtualbox (a doubleclick on the blue icon should accomplish this)


After the virtual machine boots, you should see a shortcut to DOWNDYN.EXE on the desktop.




### Notes on the virtual machine image
For distribution size consideration, the linux distribution [Slitaz](http://www.slitaz.org/en/) was used.

[Wine](https://www.winehq.org/) was installed to provide the necessary compatibility with downdyn.

Downdyn was then installed and tested. The data files were placed in the downdyn folder, which can be accessed via the "drive_c" shortcut on the desktop.




# Sandia Data Files
The original Sandia test data files are available in the machine images above.

Scott Malone provided the RODSTAR and SROD data files for the various tests and these are available in the **/WELL_#/DesignFiles/** folders. I have not recompiled the machine images above, so these design files are only available in the [git repository](https://github.com/wansco/downdyn)




### References
https://www.onepetro.org/journal-paper/SPE-60768-PA

http://www.osti.gov/estsc/details.jsp?rcdid=2957
