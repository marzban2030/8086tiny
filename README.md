8086 VM / MS-DOS 3.20 & Borland Turbo C
========

8086tiny is a completely free (MIT License) open source PC XT-compatible emulator/virtual machine written in C. It is, we believe, the smallest of its kind (the fully-commented source is under 25K). Despite its size, 8086tiny provides a highly accurate 8086 CPU emulation, together with support for PC peripherals including XT-style keyboard, floppy/hard disk, clock, audio, and Hercules/CGA graphics. 8086tiny is powerful enough to run software like AutoCAD, Windows 3.0, and legacy PC games: the 8086tiny distribution includes Alley Cat, the author's favorite PC game of all time.

8086tiny is highly portable and runs on practically any little endian machine, from simple 32-bit MCUs upwards. 8086tiny has successfully been deployed on 32-bit/64-bit Intel machines (Windows, Mac OS X and Linux), Nexus 4/ARM (Android), iPad 3 and iPhone 5S (iOS), and Raspberry Pi (Linux).

The philosophy of 8086tiny is to keep the code base as small as possible, and through the open source license encourage individual developers to tune and extend it as per their specific requirements, adding support, for example, for more complex instruction sets (e.g. Pentium) or peripherals (e.g. mouse).

Avoid to some leakages in the SDL, make with "no_graphics" mode argument is recommended.

Running instruction:

1- Unzip "UnzipMe.zip" file.

2- Run "make no_graphics" command in the repository directory.

3- Run "./runme" command.


Shortcut keys guide:

To send an Alt+xxx key combination, press Ctrl+A then the key, so for example to type Alt+F, press Ctrl+A then F.

To send an Fxx key, press Ctrl+F then a number key. For example, to get the F4 key, press Ctrl+F then 4. To get F10, press Ctrl+F then 0.

To send Ctrl+A, press Ctrl+F then Ctrl+A. To send Ctrl+F, press Ctrl+F then Ctrl+F.

To send a Page Down key, press Ctrl+F then O. To send a Page Up key, press Ctrl+F then Q.

Also you can read "doc.html" at "docs" folder to getting full guide.

Floppy changing during emulation guide:

Open another Linux console and run "cp [NewFloppy].img [InsertedFloppy].img" command in the repository directory.

Download whole of this repository as a zip file:

https://github.com/marzban2030/8086tiny/archive/refs/heads/patch-1.zip
