# win 下 配置 macaca 运行环境

## 目录

1.Java环境
2.Android环境
3.配置Gradle
4.配置Node环境
5.配置Macaca

### 一. 配置Java环境
##### 1.1 安装soft目录下的jdk-8u171-windows-x64.exe文件
    
    
步骤如图：

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/01-Java%E7%8E%AF%E5%A2%83/1.png)

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/01-Java%E7%8E%AF%E5%A2%83/2.png)

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/01-Java%E7%8E%AF%E5%A2%83/3.png)
    
##### 1.2 配置 JAVA_HOME 环境变量
JAVA_HOME
C:\Program Files\Java\jdk1.8.0_171

步骤如图：

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/01-Java%E7%8E%AF%E5%A2%83/4.png)

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/01-Java%E7%8E%AF%E5%A2%83/5.png)

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/01-Java%E7%8E%AF%E5%A2%83/6.png)

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/01-Java%E7%8E%AF%E5%A2%83/7.png)

在PATH中最前面加入 %JAVA_HOME%\bin 

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/01-Java%E7%8E%AF%E5%A2%83/8.png)

##### 1.3 测试 java 环境变量是否配置成功

打开 命令行 里，输入 java -version ,看是否如下输出：

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/01-Java%E7%8E%AF%E5%A2%83/9.png)
 
### 二，配置Android环境
##### 2.1 解压 soft 目录下的 sdk_win.zip 到 c:\User\***(本机用户名)\Documents\sdk 下
##### 2.2 安装 AndroidStudio，位于 soft 目录下的android-studio-ide-183.5692245-windows.exe文件

步骤如图：

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/02-Android%E7%8E%AF%E5%A2%83/1.png)

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/02-Android%E7%8E%AF%E5%A2%83/2.png)

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/02-Android%E7%8E%AF%E5%A2%83/3.png)

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/02-Android%E7%8E%AF%E5%A2%83/4.png)

这里选择sdk解压后的目录，比如：c:\User\***(本机用户名)\Documents\sdk

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/02-Android%E7%8E%AF%E5%A2%83/5.png)

##### 2.3 配置Android环境变量

ANDROID_HOME
c:\User\***(本机用户名)\Documents\sdk

在PATH中最前面加入 %ANDROID_HOME%\tools;%ANDROID_HOME%\platform-tools;

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/02-Android%E7%8E%AF%E5%A2%83/6.png)

##### 2.4 测试Android环境变量是否配置成功

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/02-Android%E7%8E%AF%E5%A2%83/7.png)

### 三，配置 Node 环境
##### 3.1 安装 Node ，位于 soft 目录下的node-v12.7.0-x64.msi文件

步骤如图：

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/03-node%E7%8E%AF%E5%A2%83/1.png)

这里选择 c:\nodejs\ 目录

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/03-node%E7%8E%AF%E5%A2%83/2.png)

这里要打勾

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/03-node%E7%8E%AF%E5%A2%83/3.png)

##### 3.2 

NODE_HOME
c:\nodejs\

在PATH中最前面加入 %NODE_HOME%;

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/03-node%E7%8E%AF%E5%A2%83/4.png)

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/03-node%E7%8E%AF%E5%A2%83/5.png)

##### 3.3 测试node环境变量是否配置成功

![](https://raw.githubusercontent.com/liupeipro/macacaDemo/master/img/03-node%E7%8E%AF%E5%A2%83/6.png) 
       
### 四，配置Gradle环境

##### 4.1 把soft目录下的gradle-5.2-bin.zip 解压后放到 c:\User\***(本机用户名)\Documents\gradle 目录下

##### 4.2 配置gradle环境变量

GRADLE_HOME
c:\User\***(本机用户名)\Documents\gradle

在PATH中最前面加入  %GRADLE_HOME%\bin;



### 五，配置macaca环境

参考 https://macacajs.github.io/zh/guide/environment-setup.html#%E5%AE%89%E8%A3%85-node-js 

### 六，demo测试

解压 demo目录下的uirecorder-te0727t.zip，


## 参考资料

https://macacajs.github.io/zh/guide/environment-setup.html#%E5%AE%89%E8%A3%85-node-js




