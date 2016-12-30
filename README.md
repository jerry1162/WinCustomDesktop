WinCustomDesktop
=========

自绘桌面，用你的代码绘制桌面，支持插件开发，这里以*遮罩桌面*和*播放视频*为例


使用方法
---------

1. 使用VS2013生成
2. 把插件放在`CustomDesktop.dll`所在目录下的`Plugin`目录（如x64\Release\Plugin）（其实已经把生成目录设在这里了）
3. 复制`Data`文件夹到插件所在目录
4. 运行`Inject.exe`
5. 如果运行失败，提示“从服务器返回了一个参照”，在**文件属性-兼容性**里选择**以管理员身份运行此程序**
6. 目前MaskDesktop不支持XP系统


支持的平台
---------

以下是已通过测试的平台，其他平台未测试，不代表不支持

* 64位Windows 10
* 64位Windows 7
* 32位Windows 7
* Windows XP
