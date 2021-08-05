# Sol4sdkTemp

本工程为测试将讯飞语音识别SDK植入Unity，并打包成安卓试运行。在运行过程中出现部分问题，怀疑是安卓系统的读写权限导致SDK无法正常运行

根目录即为Unity工程

其中Android_aitalk_exp1141_23298663.zip 为讯飞提供的语音识别-离线命令词SDK，解压后可以导入为Android-Studio工程

Xunfei SDK + Unity.pptx 为本Unity工程的制作过程，由SDK输出为插件而来

Xunfei_Unity2019.apk 为本Unity工程试打包，在安卓手机上无法正常语音识别，报错信息显示无读写权限

Assets/Main.cs 为Unity中读取插件的脚本，非常简单

Assets/Plugin/Android/mscV5PlusDemo-debug.aar 为SDK试导出的Unity插件

本讯飞SDK所支持的APPID 为 23298663

