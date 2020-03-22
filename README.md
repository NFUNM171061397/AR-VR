# AR-VR-week01-Unity3d安装操作

### 安装Unity3d开发平台

![Unity3d开发平台](https://github.com/NFUNM171061397/VR-week01/blob/master/images/KF%7D7H2S%5BQ0W%7BN~%40POG0J__9.png)
![Unity3d开发平台](https://github.com/NFUNM171061397/VR-week01/blob/master/images/%24)OGE(Z8FM%60%7B95%24TD%60DS_1I.png)

### 安装JAVA开发平台
* 第一步：双击安装包

* 第二步：点击下一步，按照个人需要修改路径（如图：改为D盘下的jdk1.8）
![JAVA开发平台](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

* 第三步：继续下一步，点击确认，接着会出现安装jre的提示，按照个人需要修改路径（如图：改为D盘下的jre1.8），点击下一步
![JAVA开发平台](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

* 第四步：等待安装完成，之后点击关闭即可
![JAVA开发平台](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

### 配置电脑环境变量
* 在我的电脑处点击右键，选择最下面的属性，进入高级系统设置-高级-环境变量
![环境变量](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

* 新建：变量为"JAVA_HOME"，值为D:\jdk1.8（即JDK的安装路径）
* 编辑：变量"Path"，在值的最后面加上 %JAVA_HOME%\bin之后点击确定

![环境变量新建与编辑](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

* 验证JAVA是否安装成功：在window命令状态下键入cmd,能出现JAVA版本号就表现成功了
![验证](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

### 安装Android开发平台
* 安装sdk开发包 : android-sdk_r24.4.1-windows
![安装sdk开发包](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

* 进行更新：install 17 packages（需要大约半小时）
![更新sdk开发包](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

### 配置Unity3d的Android运行环境 
* 打开安装好的Unity3d开发平台，按照流程进行注册，依次完成登录-许可证-调查，进行使用
![流程1](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)
![流程2](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

*  启动Unity3d，进入-edit-Preferences，在-external tools模块中，External Script Editor选择MoneDevelop（bulit-in）,Android选择点击Browse，选择路径文件夹进行配置，jdk地址：D:\ jdk1.8，sdk选对应的D:/android-sdk-windows（安装路径）。

* 配置完成之后，新建场景，保存场景
![场景](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

* Build Settings-Add Open Scenes，选择场景，在Platform里面切换平台为安卓平台
![配置](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

* 接着点击Player Setting在右侧修改最上方的Company Name，以及Other Settings中的Packang Name
![修改company name](https://github.com/NFUNM171061397/VR-week01/blob/master/images/E5MI_67%5DPYW)AU%25%5B0R75LDT.png)

* 点击build，添加文件名，保存路径，用夜神模拟器打开即可预览。
