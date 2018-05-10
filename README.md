# **GsonFormatForDataBinding <br/>适用于生成 Android DataBinding Bean的GsonFormat 插件**
  [![](https://jitpack.io/v/zhangguoning/GsonFormat4DataBinding.svg)](https://jitpack.io/#zhangguoning/GsonFormat4DataBinding)
1. 可以使新生成的Bean自动继承自 BaseObservable
2. Setter方法 自动添加  notifyPropertyChanged(BR.'字段名');
3. Getter方法 自动添加 @Bindable 注解

安装：
1. 下载 [GsonFormat4DataBinding.jar](https://github.com/zhangguoning/GsonFormat4DataBinding/raw/master/pluginJar/GsonFormat4DataBinding.jar) 
2. Android studio  File->Settings..->Plugins --> install plugin from disk..导入下载的 GsonFormat4DataBinding.jar 
3. 重启 android studio 

其他：
1. 快捷键默认为 alt + d ，（原 GsonFormat 快捷键为 alt + s）
2. 插件名为GsonFormat4DataBinding 不和 GsonFormat 冲突，可以两者都安装，自己决定使用哪个生成Bean

效果图如下：

![](https://github.com/zhangguoning/GsonFormat4DataBinding/raw/master/Screenshot/GsonFormat4DataBinding.png)





更多内容请参见 [GsonFormat](https://github.com/zzz40500/GsonFormat) 原项目介绍


  
  
