刷機參考網址
https://firmwarefile.com/htc-desire-820s-dual-sim

cpu和gpu型號相同的開源資料
https://github.com/hankching/kernel-lenovo-mt6752
上面這個專案用的編譯工具包
git clone https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-4.9
1100505上面的連結使用時產生aarch64-linux-android-gcc: Command not found，而且真的找不到檔案，這可真是的


下載原廠OTA方式,未測試
http://www.rayzen-dev.com/get-ota/

自製andriod教學
https://forum.xda-developers.com/t/ultimate-guide-noob-friendly-compile-your-own-android-kernel-from-source.2871276/

官方Kernel Source Code, Binaries and Updates for HTC Android Phones
https://www.htcdev.com/devcenter/downloads


說明htc的kernel source怎麼make的網站，我比較在意的是他的toolchain
https://forum.xda-developers.com/t/howto-compile-the-kernel-source-code-for-the-htc-one-xl.1847344/







==============================================================================================================================
1100505
因為我的cs968玩掛了，htc 820s又閒著沒在用，所以改變目標來玩它
今天在找資料，基本上有官方的Kernel Source Code，所以驅動那些可以不必找了，而目前先測試如何把他依照andriod的方式make成功再說，暫時卡在toolchain上面，一來官方提供的來源沒有gcc了，二來自己找的來源make不成功，所以還要再想一下怎麼回事，在這邊先做個暫時的紀錄，以下說明一下各資料夾的內容
1.source kode
官方的Kernel Source Code及網路上下載回來的OTA檔放在這邊。
2.toolchains
目前測試的toolchains放在這，還沒找到合適的。
