这个是2014年学习WTL时练手的代码，只花了2小时，所以功能很不完善，主要为了展示WTL的用法
只有100多KB，而且还可以精简到几十KB。现在的软件动不动100多M，时代变了，不用担心软件大小了
EyeSecretary.exe是已经编译好的，可以先体验效果


软件使用说明：
1、会在屏幕加上一层透明绿色，保护眼睛
2、右键点击托盘图标，可以设置透明度、或更换颜色
3、可以设置是否始终置顶
4、可以设置是否自动识别窗口：绿色不会覆盖指定的窗口，比如记事本、VS、WPS、Office等软件


编译说明：
1、EyeSecretary VS2022.sln 可以直接编译成功
2、EyeSecretary VS2008.sln 需要将WTL的include目录加到项目的include的目录和资源目录，才能编译成功
3、其他版本的VS，可以先打开EyeSecretary VS2022.sln，试试能不能编译成功，
		 不成功的话，就打开EyeSecretary VS2008.sln，按照步骤2来操作