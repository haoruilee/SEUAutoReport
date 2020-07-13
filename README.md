# SEUAutoReport-Servers

用于解决东南大学恼人的信息化疫情填报

## 服务器版使用方法

1. 下载本Branch，在源码里填好你的一卡通和密码 或 在dist目录下创建一个名为C2P.txt的文件,以<一卡通> <密码> <个位数>为格式储存密码。比如:
> 213181234 123456 0  
> 213191234 123456 0  
> ...
2. 在命令行中运行 C:\Users\Lenovo-LI\source\repos\Gaussian_funs\SEUAutoReport\dist、AutoReport.exe

## 其他

1. 你**不需要**Python的基础环境来运行exe程序。
2. 但是该程序需要借助WebDriver使用。请在[WebDriver下载地址](http://chromedriver.storage.googleapis.com/index.html)下载与本地GoogleChrome适配的版本并参考[这篇博客](https://blog.csdn.net/weixin_41990913/article/details/90936149)进行环境变量添加
