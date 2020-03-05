# Apk2Source
##Download
For decompiling apk and dex android files first you should download :
1. [Dex2jar](https://github.com/pxb1988/dex2jar)
2. [Java decompiler](http://java-decompiler.github.io/)
3. [ApkTool](https://ibotpeaches.github.io/Apktool/install/)
4. [Framework-res.apk](https://androidfilehost.com/?fid=23212708291677144)

##steps:
1.Rename .apk file to .zip 
   now you can see drawables
2.Extract .zip file in same folder
3.Extract dex2jar ( you should download it first ) in that folder
4.Open command prompt and go to that directory and type ***d2j-dex2jar classes.dex*** 
   ( if you use mac or ubuntu use this command ***./d2j-dex2jar.sh classes.dex***)
5.Open java decompiler ( you should download it first ) and open your classes which changed by dex2jar
6.Put ApkTool which you download it to this folder
7.Run ***apktool if framework-res.apk***
8.Run ***apktool d YourApp.apk***
you can use [this](http://www.javadecompilers.com/apk) online tool too ; upload your apk file and get source code 
