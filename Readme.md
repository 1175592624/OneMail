# **OneMail**
### 什么是OneMail?
OneMail是一个通过控制手机批量发送短信的脚本
### 如何使用OneMail?
#### 前期准备
1. 在电脑上安装Python3的运行环境 ==(该脚本依靠python运行)==
2. \[可选\]在手机安卓端安装ADBKeyBoard,并设置成当前输入法 (以解决在发送短信期间输入法乱弹的问题)
3. 打开手机的开发者模式,并打开 开发者选项---USB调试,如果有USB调试(安全设置)也请一并打开
4. 打开在电脑设置中打开unicode-8,具体操作参考下图:
![unicode-8_Setting](https://github.com/1175592624/OneMail/blob/4dbdb06c872056e0120f3d4da12654f4cd4781cb/image/unicode-8_Setting.png)
5. 用数据线连接手机和电脑,大功告成!
#### 批量发送
![Mail_Button](https://github.com/1175592624/OneMail/blob/4dbdb06c872056e0120f3d4da12654f4cd4781cb/image/Mail_Button.png)
1. 打开手机自带的短信App,打开发送短信界面,截图(原图)并发送到电脑,用画板打开图片,找到按钮坐标(如上图),并将其输入到OneMail.py代码中的这一部分:
```
    ClickScreen(963,2001)   #按钮坐标请写到这儿
```
2. 保存代码并运行,根据提示导入表格 ==(表格内至少得拥有“姓名”和“电话”两列)==,再在对话框内输入文案 ==(姓名请用一个大写X代替)==,文案可参考下文:
```
社团联合会:亲爱的X,你好!恭喜你,经过我们对你面试表现的评定,恭喜你成功入选人力部,快加入我们的群一起交流吧!群号:1175592624,收到请务必回复呦~2019/10/20
```
