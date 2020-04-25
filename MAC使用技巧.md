# MAC使用技巧

# 快捷键篇

## 触控板

在全屏程序之间切换：三根手指 左/右滑动

现实当前所有运行程序及打开窗口缩略图：三根手指 从下向上/下滑动

## 键盘

copy：command + c

粘贴：command + v

转移黏贴：command + option + v

保存：command + s



# 命令行篇

查找命令安装位置：which，实例 which python

把文件copy到剪贴板：pbcopy， 实例pbcopy < /Users/wangguangli/.ssh/id_rsa.pub



# git 篇

一个工作流可以是这样：

1. 使用git clone命令把库从github上克隆到本地；
2. 在本地工作，使用git add，git commit等命令，操作本地库；
3. 使用git push origin master 命令把本地master 上传到github上



# brew

​        初步介绍几个brew命令



​    本地软件库列表：brew ls

​    查找软件：brew search google（其中google替换为要查找的软件关键字）

​    查看brew版本：brew -v 更新brew版本：brew update



​    Formulae（方案库 例如python）

​    安装方案库：brew install curl（其中curl替换为要安装的软件库名称）

​    卸载方案库：brew uninstall curl（其中curl替换为要卸载的软件库名称）



​    Casks  （界面软件 例如谷歌浏览器）

​    安装软件：brew cask install visual-studio-code（其中visual-studio-code替换为安装的软件名字，例如google-chrome）

​    卸载软件：brew cask uninstall visual-studio-code（其中visual-studio-code替换为要卸载的软件名字，例如google-chrome）



​    查找命令安装的位置：which brew（brew可以换成任何命令，包括brew安装的）



**现在可以输入命令open ~/.zshrc 或者 open ~/.bash_profile 整理一下重复的语句(运行 echo $SHELL 可以查看应该打开那一个文件修改)**



​    **https://zhuanlan.zhihu.com/p/111014448 欢迎来给点个赞**

# pip

通过豆瓣镜像下载实例：

pip install -i http://pypi.douban.com/simple/ --trusted-host=pypi.douban.com/simple pyqt5

