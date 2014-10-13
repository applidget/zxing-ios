#Zxing for iOs

This is a fork from [zxing/zxing](https://github.com/zxing/zxing/) in which we just reenable necessary code for iOs. This code has been retired a while ago in ZXing since it was no longer maintained. 

The status of the repo is based on [this commit](https://github.com/zxing/zxing/commit/00f6340) from zxing.

##Recommendation

We created this repo for 2 reasons :

1. Using Zxing ia cocoapods was really slow (until version 2.2). This was because using it implied cloning the whole Zxing repos that includes a lot of tests
2. ZXing 2.2 in cocoa pods does not work anymore in XCode 6 due to compiling errors. 

If you need to scan QR Codes in an iOs app, you need to use the built-in iOs features, unless your app needs to support iOs 6 or lower versions. 