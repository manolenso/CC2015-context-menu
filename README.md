### REG file for create Adobe CC 2015 desktop context menu
*use for Windows 7!
####2 versions: Top and Bottom
#### Install: dbclick on Reg file

![context](https://github.com/manolenso/CC2015-context-menu/blob/master/screen/capture.png)

To add CC Adobe SOFTWARE, first edit "SubCommands" line

"SubCommands"="Photoshop;Illustrator;inDesign;lightroom;EdgeAnimate;Dreamweaver;Muse;Flash"


#### Quick addition code snippets:
copy and past, replace XXXXX


````reg
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CommandStore\shell\XXXXX]
@="Adobe XXXXX CC 2015"
"Icon"="C:\\Program Files\\Adobe\\Adobe XXXXX CC 2015\\XXXXX.exe"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CommandStore\shell\XXXXX\command]
@="C:\\Program Files\\Adobe\\Adobe XXXXX CC 2015\\XXXXX.exe"
````
