# 重装系统引导

> 我偶尔会因为各种各样的原因重装系统，故写下此篇引导，总结经验

## 基本工具

- [Chrome](https://www.google.com/chrome/)
- [uTools](https://www.u.tools/)
- [clashForWindows](https://github.com/ender-zhao/Clash-for-Windows_Chinese/releases)
  - 设置开机自动启动
- [weChat](https://weixin.qq.com/)
- [搜狗输入法](https://shurufa.sogou.com/)
  - 设置小鹤双拼

## 学习

### logseq

- 下载[logseq](https://logseq.com/)
- clone [knowledge graph](https://github.com/pidanmeng/knowlege-graph)
- 使用logseq选择knowledge graph
- 设置代理 `http://localhost:7890`
- 安装主题
  - dev theme
- 安装插件
  - Journals calendar
  - Tabs
  - Bullet Threading
  - Markmap
  - Heatmap
  - Agenda
  - Tags
  - Link Preview
  - TODO List
  - VIM shortcuts
  - Awesome Links
    - 修改设置中的icon
    - 取消超链接icon
  - Awesome ui // 目前有bug

## 娱乐

### 游戏

- [dodo](https://www.imdodo.com/)
- [奇游加速器](https://www.qiyou.cn/)
- [steam++](https://steampp.net/)
- [steam](https://store.steampowered.com/about/)
  - 解绑steam令牌
  - 设置steam令牌绑定到steam++
  - 下载Wallpaper Engine

### 多媒体

- [网易云音乐](https://music.163.com/#/download)
  - 设置中取消开机启动
- [potplayer](https://potplayer.daum.net/?lang=zh_CN)

## 开发环境

### 编辑器

- 微软商店下载Terminal
  - 打开powershell运行命令```set-executionpolicy remotesigned```
- 下载[VSCode](https://code.visualstudio.com/)
  - 登录 同步设置
- clone [dotfiles](https://github.com/pidanmeng/dotfiles)
  - 运行`keyboard.reg` 交换`ESC`和`CapsLock`键
    - 重启
  - 根据readme创建符号链接
- 下载并安装字体[VictorMono](https://rubjo.github.io/victor-mono/)

### git环境

- 下载[git](https://git-scm.com/)
  - [ 创建SSH私钥 ](https://www.jianshu.com/p/9317a927e844)
  - 在[github settings](https://github.com/settings/keys)设置SSH keys
  - 设置git代理(使用clash for windows作为默认代理)
    - ```git config --global http.proxy http://localhost:7890```
    - ```git config --global https.proxy https://localhost:7890```
  - 全局安装`gitcz`
    - ```pnpm i -g git-cz```

### node环境

- 下载[NVM windows](https://github.com/coreybutler/nvm-windows/releases)
  - 重启
- nvm下载最新LTS版本Node
- 全局安装pnpm ``` npm i -g pnpm ```
  - 注入环境变量
    - ```pnpm setup```
    - 重启
