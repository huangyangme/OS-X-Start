#OS-X-Start


## Mac 上对第三方 SSD 开启 TRIM 支持

	sudo trimforce enable


## Install Homebrew

[http://brew.sh/](http://brew.sh/)

    ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

## Install Redis

    brew install redis

## Install MySQL

    brew install mysql

    // To have launchd start mysql at login:
    ln -sfv /usr/local/opt/mysql/*.plist ~/Library/LaunchAgents
    // Then to load mysql now:
    launchctl load ~/Library/LaunchAgents/homebrew.mxcl.mysql.plist
    
    // 执行安全选项（含设置密码）
    mysql.server start
    mysql_secure_installation


## installing Node & NPM

[https://nodejs.org/en/download/](https://nodejs.org/en/download/)

Or:

    brew install node.

## uninstall Node & NPM

    brew uninstall node

### [completely uninstall Node.js and reinstall from beginning (Mac OS X)](http://stackoverflow.com/questions/11177954/how-do-i-completely-uninstall-node-js-and-reinstall-from-beginning-mac-os-x)

## Sublime Text

[SublimeText-You-Need](https://github.com/huangyangme/SublimeText-You-Need)

## 配置git别名

    $ git config --global alias.st status
    $ git config --global alias.co checkout
    $ git config --global alias.ci commit
    $ git config --global alias.br branch

[详细](http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001375234012342f90be1fc4d81446c967bbdc19e7c03d3000)

## App

- [1Password 5](https://agilebits.com/onepassword)(密码管理)
- [网易云音乐](http://music.163.com/#/download)（音乐）
- [CodeKit](https://incident57.com/codekit/)（Web前端自动化神器，收费）
- [Mac Blu-ray Player](http://www.macblurayplayer.com/)（蓝光视频播放器）
- [AppCleaner](https://freemacsoft.net/appcleaner/)（卸载App）
- [Annotate](https://www.driftt.com/annotate-mac)（截屏神器，App Store下载，收费）
- Android 文件传输（在Mac上管理Android机）
- [Cyberduck](https://cyberduck.io/)（FTP工具）
- [Transmit](https://panic.com/transmit/)（FTP工具，App Store下载，收费）
- [DaisyDisk](https://daisydiskapp.com/)（磁盘数据分析）
- [Encrypto](http://macpaw.com/encrypto)（磁盘文件加密，App Store免费）
- [Gifrocket](http://www.gifrocket.com/)（视频转gif神器）
- iOSBetaBuilder（iOSBetaBuilder）
- HandBrake（视频格式转换）
- [HBuilder](http://dcloud.io/index.html)（HTML5开发IDE）
- [Parallels Desktop](http://www.parallelsdesktop.cn/)（虚拟机）
- [OnyX](http://www.onyxmac.com/)（OnyX）
- [sequel pro](http://www.sequelpro.com/)（MySQL可视化工具）
- [Sip](https://itunes.apple.com/cn/app/sip/id507257563?mt=12)（屏幕取色）
- [Sketch](http://www.sketchcn.com/)（Sketch）
- [Spectacle](https://www.spectacleapp.com/)（Mac窗口管理高效神器）
- [The Unarchiver](https://itunes.apple.com/cn/app/the-unarchiver/id425424353?mt=12)（解压缩工具）