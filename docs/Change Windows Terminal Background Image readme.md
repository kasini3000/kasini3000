# kasini3000, Change Windows Terminal Background Image, description file.

Its main function is: when a script or command error occurs, wrtie-error, at the same time, it calls related scripts and changes the Windows Terminal background image to achieve the purpose of eye-catching reminders.

The essence of the CWTBI function is to use the ps1 script to replace the image file in the Windows Terminal configuration file.

Since the minimum requirement of win term is win10-18362 version (win10-1903 version), the lower version win10 and win7 cannot be used.
Because win10-ltsb and win10-ltsc versions do not include the Microsoft application market, and Windows Terminal is a program in the Microsoft application market. Therefore, the above version 2 cannot be used.

------

# 1 paste text to file.

c:\Users\【your name】\AppData\Local\Packages\Microsoft.WindowsTerminal_8wekyb3d8bbwe\LocalState\settings.json

```
            "name" : "卡死你3000",
            "backgroundImage": "c:\\ProgramData\\kasini3000\\admin_gui\\pic\\ps壁纸.jpg",
            "startingDirectory" : "c:\\ProgramData\\kasini3000",
            "backgroundImageAlignment": "center",
            "backgroundImageStretchMode": "uniform",
            "backgroundImageOpacity" : 0.3
```

------

# 2 run ps1 script

```
c:\ProgramData\kasini3000\admin_gui\pic\bc随机报错背景图片.ps1
```

------

# 4 diy pic

Find all kinds of emoji pictures and put them in the following directories,

The file name is arbitrary, and the file name can contain Chinese. Support gif animation.

c:\ProgramData\kasini3000\admin_gui\pic\成功\
c:\ProgramData\kasini3000\admin_gui\pic\报错\
c:\ProgramData\kasini3000\admin_gui\pic\疑问\
c:\ProgramData\kasini3000\admin_gui\pic\警告\

then run ：
bc随机报错背景图片.ps1
cg随机成功背景图片.ps1
jg随机警告背景图片.ps1
m默认ps背景图片.ps1
yw随机疑问背景图片.ps1

------

# 5 Show your baby for free.

This project can help you show your baby for free.

Collect free loli pictures, be cute and beautiful. Just girls.

Need a guardian, give me authorization, and authorize me to edit. (Mainly adding text)

## I have allready get the authorization of beautiful girls pics like "惊2改.jpg" from her father (guardian) .

------

# 6 If there is any violation of your rights, please contact me to delete.

All pic file from the Internet, if there is any violation of your rights, please contact me to delete.

contact details: kasini3000 official technical support QQ group: 700816263

