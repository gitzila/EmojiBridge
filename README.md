# EmojiBridge
A quick and dirty Android App to bring emojis to HK8 pro max (and maybe other smartwatches).

It fakes itself as "com.tencent.mm"-package (this is the package of the WeeChat app), so you can activate it in WearFit pro App to get notifications from.

After installing the APK there will be a new app called "EmojiBridge". Put both properties-files in this folder:

/storage/emulated/0/Android/data/com.tencent.mm/files

Create folder if does not exist.

Grant "read notifications" and "read memory"-permissions to this app.

Allow autostart and execution in background. And except from any battery saving options.

Now open WearFit pro app and switch on notifications from "EmojiBridge". See https://github.com/gitzila/EmojiBridge/blob/main/Screenshot_2023-03-06-15-34-52-66_7f4e6599bb8a59f95e52727fad58b156%7E2.jpg

After that you can edit the properties-files. I guess it is rather self explaining...

After editing open the app and press the floating button bottom right. It will then load the properties-files. 

After reboot these files are loaded automatically. 

Have fun.

Some time I will improve this app. I know for now it is a piece of shit 🙈.

Sourcecode follows in some days. Do what you want with it.

No license, no permissions needed. Free to use.
No warranty.
