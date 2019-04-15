# Android 设置忽略文件

[版权所有，转载注明](https://github.com/DarkkingLucifer/Android-settings-ignore-files)
>每次新建项目都要去百度一下操作步骤，不如自己写一个以后都看自己的。如有问题还请大佬们在评论出指出，谢谢。

### 1.打开忽略文件设置路径
- 【File】→【Settings】→【Version Control】→【Ignored Files】
![图片.png](https://upload-images.jianshu.io/upload_images/3722198-e2b83219e6afe7b0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 2.添加忽略文件

点击右侧的【+】进行添加，【-】删除。

Android Studio默认给出了三种忽略方式：

1.忽略指定的文件【Ignore specified file】

2.忽略文件夹下所有文件【Ignore all files under】

3.忽略符合匹配规则的文件【Ignore all files matching】

![图片.png](https://upload-images.jianshu.io/upload_images/3722198-1ef5520176b62ea8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**Androis Studio一般忽略以下不需要增加到版本库的文件：**

###### 2.1 .gradle 文件夹，此文件夹是用来保存gradle的依赖信息。

![图片.png](https://upload-images.jianshu.io/upload_images/3722198-a53f0da507b95b69.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###### 2.2 .idea 文件夹，此文件夹是用来保存开发工具的设置信息。

![图片.png](https://upload-images.jianshu.io/upload_images/3722198-e78b769dc91ad632.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###### 2.3 所有的 build 文件夹，build文件夹是用来保存编译后的文件目录。

![图片.png](https://upload-images.jianshu.io/upload_images/3722198-2b215265ec39fa0d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###### 2.4 local.properties 文件，是用来保存项目依赖信息。

![图片.png](https://upload-images.jianshu.io/upload_images/3722198-b57972772fe383eb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

###### 2.5 所有的 .iml 文件，是用来保存开发工具信息。

![图片.png](https://upload-images.jianshu.io/upload_images/3722198-aa9f783a4882ebf9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

