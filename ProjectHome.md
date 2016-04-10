for latest version, please go to here: https://github.com/3pei/r5u870 . you can still download old versions from here (google code).


---


the previous download (0.3.2) should work with linux kernel 2.6.36 ~ 3.2. but it haven't been tested with kernel < 3.2. plz report if you meet any troubles.

if you use kernel <= 2.6.35, you could try old one (0.1a). and for kernel > 2.6.35 but < 3.0, plz use the latest one and report your result.

how to install:

1. download the package under "Downloads" category

2. extract it into a folder

3. cd into the folder, and type "make"

4. type "sudo make install"

5. type "sudo modprobe r5u870" (or any other methods to load driver)

6. try your webcam

for skype users: plz downgrade your skype to 2.1, you could download here:

http://download.skype.com/linux/skype-debian_2.1.0.81-1_i386.deb
http://download.skype.com/linux/skype-debian_2.1.0.47-1_i386.deb

or

http://download.skype.com/linux/skype_static-2.1.0.81.tar.bz2

tested with HP/Ricoh Webcam 1000, softwares: Cheese, Camorama Webcam Viewer, gstreamer-properties, QT V4L2 test Utility and skype 2.1.

plz tell me your results.

since the original maintainer have closed his project, I will continue to update the driver at every time Ubuntu upgrade its kernel until I would throw my notebook away.

you could find more detail here: http://www.arakhne.org/ricoh/ , thanks these guys for things they left to us :)