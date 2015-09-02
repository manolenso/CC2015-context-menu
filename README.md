### REG file for create Adobe CC 2015 desktop context menu

![context](https://github.com/manolenso/CC2015-context-menu/blob/master/screen/capture.png)


#### Quick addition code snippets
copy and past, replace XXXXX as you need!

````reg
[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CommandStore\shell\XXXXX]
@="Adobe XXXXX CC 2015"
"Icon"="C:\\Program Files\\Adobe\\Adobe XXXXX CC 2015\\XXXXX.exe"

[HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Explorer\CommandStore\shell\XXXXX\command]
@="C:\\Program Files\\Adobe\\Adobe XXXXX CC 2015\\XXXXX.exe"
````
