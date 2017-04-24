## Sublime Env

通过 [Package Control](https://packagecontrol.io/installation) 的 Sync 特性，同步不同设备下 [Sublime Text 3](http://www.sublimetext.com/3) 的配置及安装的插件。

## 使用
1. 安装 `Sublime Text 3` 插件管理器 `Package Control`
1. 通过 `Sublime Text 3` 菜单 `Preferences > Browse Packages...` 进入 `Packages` 目录，删除此目录下 `User` 文件夹，并执行命令：
    ```bash
    git clone https://github.com/lym125/sublime-syncing.git User
    ```
1. 关闭 `Sublime Text 3` 后，重新打开 `Sublime Text 3`，等待 `Package Control` 同步配置及插件
