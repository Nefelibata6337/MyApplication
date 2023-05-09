# Test01
Project Practice Development_test01

## 东西全部写在csdn了

[Anaconda下载安装教程](https://blog.csdn.net/wly_ok/article/details/130098793?spm=1001.2014.3001.5502)

[Android 的 SDK 安装和配置](https://blog.csdn.net/wly_ok/article/details/130158066?spm=1001.2014.3001.5502)

[关于Android Studio配置github和Git的问题](https://blog.csdn.net/wly_ok/article/details/130153828?spm=1001.2014.3001.5501)

[Anaconda中TensorFlow的安装（win+r形式）](https://blog.csdn.net/wly_ok/article/details/130468990?spm=1001.2014.3001.5501)
# 关于Android Studio配置github和Git的问题
## 1.下载Git和相应环境变量配置
首先，下载[Git](https://git-scm.com/book/zh/v2/%E8%B5%B7%E6%AD%A5-%E5%AE%89%E8%A3%85-Git)
不会的看这里[Git安装教程](https://blog.csdn.net/mukes/article/details/115693833)
然后配置环境变量，点击开始——>控制面板——>系统和安全——>系统（下拉）——>高级系统设置——>环境变量——>找到 path 环境变量,修改 path
![在这里插入图片描述](https://img-blog.csdnimg.cn/e28eed4ed5d44bc4866ac67755aabcb8.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/886ac1a92d674bcfbc2647742580780b.png#pic_center)

然后测试一下，打开cmd，输入sh
![在这里插入图片描述](https://img-blog.csdnimg.cn/f0b1dd5296a54b568d33a44d8483d04b.png#pic_center)
## 2.Android Studio配置Github和Git
Android Studio的[安装地址](https://developer.android.google.cn/studio)和[安装教程](https://blog.csdn.net/qq_38436214/article/details/105073213)
### 2.1Git配置
选择File——>setting——>Version Control——>Git
![在这里插入图片描述](https://img-blog.csdnimg.cn/69980f9ddcf64b56a4011681ba15d938.png#pic_center)
在Path to Git executable里面输入Git下面git.exe的安装地址,然后test
![在这里插入图片描述](https://img-blog.csdnimg.cn/af24df0639a040a0a9cf0a8f8b3a1b96.png#pic_center)
### 2.2Github配置
Github就在Git下面，点击“+”号，然后选择第一个
![在这里插入图片描述](https://img-blog.csdnimg.cn/0f1388385b7747e6b88d85ae7acb7547.png#pic_center)

这里会自动跳转到github里面获得token的页面
手动获得步骤：
进入github——>Settings——>Developer settings
![在这里插入图片描述](https://img-blog.csdnimg.cn/c3f580e90eda4cb8b6eee7b1775db78a.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/48f44df373c84980bbb9860e9f47f63d.png#pic_center)

点进去然后填写理由，全部勾，然后即可获得token，复制到Android Studio粘贴。
注意：每一个token只可以使用一次，如果没有使用，则不可以申请下一个
如果忘记token码
![在这里插入图片描述](https://img-blog.csdnimg.cn/b2847fe938d24d13883e3456ca39385b.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/c480b97c70c94cbfbdb24f0047a1ad63.png#pic_center)
这样即可重新获得token码，成功为这样![在这里插入图片描述](https://img-blog.csdnimg.cn/e4320c7353e545fda06e7750552dcf9a.png#pic_center)
如果出现错误server is unreachable
请参考：[https://blog.csdn.net/qq_44866828/article/details/118854948](https://blog.csdn.net/qq_44866828/article/details/118854948)
如果出现其他问题，请参考：
[Android Studio 关联并使用 GitHub（感觉把所有的错误都经历了一遍~~ ）](https://blog.csdn.net/zeroheitao/article/details/117198411)
[Android Studio关联Github出现的问题](https://blog.csdn.net/m0_56195064/article/details/122155378)
[AndroidStudio无法连接GitHub](https://blog.csdn.net/weixin_43101402/article/details/104634929)
成功了之后
![在这里插入图片描述](https://img-blog.csdnimg.cn/4ffed73b17954d4282f992c977960ee5.png#pic_center)
即可传项目到github。
## Project Practice Development_test01补充
## 命名行方式（推荐）
Open Anaconda Powershell Prompt (or Anaconda Command Prompt), create a Python environment for TensorFlow, install the TensorFlow library, and activate the environment using the following method.
(打开Anaconda Powershell Prompt（或者Anaconda Command Prompt），然后为TensorFlow创建一个Python环境并安装tensorflow库和激活环境，使用以下方式。)
Install TensorFlow:

1. Download and install Anaconda or the smaller Miniconda.

2. On Windows open the Start menu and open an Anaconda Command Prompt. On macOS or Linux open a terminal window. Use the default bash shell on macOS or Linux.

3. Choose a name for your TensorFlow environment, such as “tf”.

4. To install the current release of CPU-only TensorFlow, recommended for beginners:
```java
conda create -n tf tensorflow
conda activate tf
```
Or, to install the current release of GPU TensorFlow on Linux or Windows:

```java
conda create -n tf-gpu tensorflow-gpu
conda activate tf-gpu
```

![](https://img-blog.csdnimg.cn/a6b6989cbdfb46b6b0d2ce0704dfc713.png#pic_center)
![在这里插入图片描述](https://img-blog.csdnimg.cn/202aa72a37b14499b24966494b2ec34e.png#pic_center)

![在这里插入图片描述](https://img-blog.csdnimg.cn/3e7942d76d5341cf905f04c9b2d16a9e.png#pic_center)
TensorFlow is now installed and ready to use.
参考：[TensorFlow - Anaconda documentation](https://docs.anaconda.com/free/anaconda/applications/tensorflow/)
[其他方式](https://blog.csdn.net/llfjfz?type=blog)

