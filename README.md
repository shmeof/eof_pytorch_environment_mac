# eof_pytorch_environment_mac
Mac下，PyTorch环境配置

## 环境

1、Mac电脑
2、Python版本：2.7.10

## 配置步骤

1、安装Anaconda
	1、官网(https://www.anaconda.com/download/#macos)太慢，到镜像（https://mirrors.tuna.tsinghua.edu.cn/anaconda/archive/）下载“Anaconda2-5.0.0-MacOSX-x86_64.pkg”
 	2、双击安装
 	3、配置Path，检查是否安装成功
 	4、设置镜像路径
    # 添加Anaconda的TUNA镜像
    conda config --add channels https://mirrors.tuna.tsinghua.edu.cn/anaconda/pkgs/free/
    # TUNA的help中镜像地址加有引号，需要去掉

    # 设置搜索时显示通道地址
    conda config --set show_channel_urls yes
  参考[Anaconda使用总结 - 简书](https://www.jianshu.com/p/2f3be7781451)
2、如果在PyCharm下开发，若提示"ImportError: No module named torch"，需要配置anaconda的python路径。
	Mac下PyCharm设置：PyCharm -> Preferences... -> Project Interpreter -> 右侧选择路径（如"~/anaconda2/bin/python2.7"）
3、PyTorch
	 [10分钟快速入门PyTorch (0)](https://zhuanlan.zhihu.com/p/26854386)
