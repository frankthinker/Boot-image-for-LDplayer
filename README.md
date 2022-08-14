# Boot-image-for-LDplayer

这个文件能实现在雷电模拟器9上配置Magisk app。众所周知，Magisk为手机的root提供了解决方案，但对于模拟器而言，情况有所不同，它的boot.img文件和通常的实体手机不一样，不容易获取。这里我提供了boot.img，可以直接配置Magisk。我忘掉了原作者的链接在哪里，所以重新自行上传了一份文件。

安装步骤：

首先，看这个教程： https://platinmods.com/threads/how-to-install-magisk-on-android-emulators-easy-android-7-and-above.146149/ ， 我在这个教程的指引下成功在雷电9上安装了Magisk。

此时，必须关掉模拟器自带的root，防止发生冲突，然后重启一遍模拟器。然后访问当前的github仓库，利用这里提供的boot.img文件(要导入到模拟器后用内置文件管理器浏览，并找到根目录下的Pictures共享文件夹，打开它)配置magisk。

若配置成功，这个时候需要权限的应用能正常弹出请求root权限的窗口〈是magisk的窗口，不是原先雷电的窗口)，说明magisk root能正常运行。
