
# [macOS]brew安装 #

MacOS上的包管理工具。

1.确认安装ruby

brew是ruby开发的，需要确认ruby是否已安装，默认是已经安装的。

    which ruby
    
    ruby --version

2.安装(较慢）

	ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

安装过程中需要输入一次用户密码

安装过程图（不要着急）

3.确认

	brew --version

测试是否已安装成功

	which brew

安装成功则显示路径

作者：萌萌花椰菜

链接：https://www.jianshu.com/p/73fd28be827f

来源：简书

著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。