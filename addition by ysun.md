### 解决【Failed to process string with tex because latex could not be found】的办法

<https://blog.csdn.net/qq_15546921/article/details/122896540>

* Mac的经过测试有效
* Windows不知

为防止网页失效，摘录如下

**1. windows系统下的安装步骤:**

第一步：安装MiKTeX；
第二步：安装dviping(a DVI-to-PNG convert):MiKTeX中的miktex包含安装程序dviping.exe，在路径"bin/x64/dvipng.exe"下；
第三步：安装Ghostscript；
安装完成后需要进行一些必要的软件安装和PATH环境变量的配置。

**2. mac系统下的安装步骤:**

第一步：安装python模块latex：pip3 install latex
第二步：安装latex环境MacTex：brew install mactex 或者直接在官网下载安装包(我是自己在官网下的安装包 *by ysun*)
 * 查看是否安装成功 latex --version或者which latex

第三步：MacTex安装成功后打开Tex Live Utility app然后将里面可更跟新的全部更新。