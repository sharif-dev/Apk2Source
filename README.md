# Apk2Source
For decompiling apk and dex android files first you should download :
1. [Dex2jar](https://github.com/pxb1988/dex2jar)
2. [Java decompiler](http://java-decompiler.github.io/)
3. [ApkTool](https://ibotpeaches.github.io/Apktool/install/)
4. [Framework-res.apk](https://androidfilehost.com/?fid=23212708291677144)

steps:
Rename .apk file to .zip 
now you can see drawables
Extract .zip file in same folder
Extract dex2jar ( you should download it first ) in that folder
Open command prompt and go to that directory and type (d2j-dex2jar classes.dex) 
	( if you use mac or ubuntu use this command (./d2j-dex2jar.sh classes.dex))
Open java decompiler ( you should download it first ) and open your classes which changed by dex2jar
Put ApkTool which you download it to this folder
Run apktool if framework-res.apk
Run apktool d YourApp.apk
you can use this online tool too ; upload your apk file and get source code 
