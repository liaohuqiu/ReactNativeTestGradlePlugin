Demo 主要演示了 build.gradle 的配置，用 Android Stuido 打开即可运行，不要修改 Dev Setting 中的 Debug Server，因为资源都已经打包，不再在从 Debug Server 下载。可以解开 debug.apk 看 assets 目录下的文件。

其中包含了一个编译安装 react-native-gradle 到本地 Maven 库的脚本，运行即可。

```bash
sh build-and-install-react-native-gradle-plugin.sh
```

> 关于 React Native 下 Android 应用程序的打包，详细的信息，在这里： http://www.liaohuqiu.net/cn/posts/react-native-android-package/

> 有问题欢迎留言或在微博上和我交流: http://weibo.com/liaohuqiu

