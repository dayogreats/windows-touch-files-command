How to `touch` files in windows command (cmd) line like Linux; an equivalent of Linux `touch` to create an empty file with Windows PowerShell.

Windows does not natively include a touch command. 'Touch' is a Linux Command Terminal for creating files.

Follow these steps If you would like to do touch a file like `filename.[file_extension]` in Windows environment.


#STEP
* Git clone `https://github.com/dayogreats/windows-touch-files-command.git`
* Navigate to this path in your system `C:\Windows\System32`
* Copy `touch.bat`file only from the cloned folder and paste it in the system path above
* Or better still, you can also copy `touch.bat` to your system 'C:\'root like `C:\touch.bat` and then add it to your system environment path
* Then close your cmd and reopen it
* Done. To confirm it works, type `foo.txt` in your windows cmd
