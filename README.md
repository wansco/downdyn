# downdyn

The program downdyn was created by Sandia National Labs in 1996 to present the data gathered from a number of test wells.

Unfortunately, this program was written in VB3 and target at Windows 3.1. While it is possible to get this software running in a modern Windows installation, the support and instructions to do so are problematic.

As a simple alternative, downdyn is installed in a virtual machine, making access to this old program quick and easy.


##Instructions
First, install Virtualbox on your machine (Please note the "dot-org")

https://www.virtualbox.org/wiki/Downloads
(You want the installer from the "VirtualBox platform packages" section. Dont worry about the "extension pack" links)



Next download the virtualbox machine image from this repository. 

https://github.com/wansco/downdyn/releases/download/Initial/DownDynImage.zip

Unzip and open the DownDyn.vbox file with Virtualbox (a doubleclick on the blue icon should accomplish this)


After the virtual machine boots, you should see a shortcut to DOWNDYN.EXE on the desktop.




###Notes on the virtual machine image
For distribution size consideration, the linux distribution [Slitaz](http://www.slitaz.org/en/) was used.

[Wine](https://www.winehq.org/) was installed to provide the necessary compatibility with downdyn.

Downdyn was then installed and tested. The data files were placed in the downdyn folder, which can be accessed via the "drive_c" shortcut on the desktop.




###References
https://www.onepetro.org/journal-paper/SPE-60768-PA

http://www.osti.gov/estsc/details.jsp?rcdid=2957
