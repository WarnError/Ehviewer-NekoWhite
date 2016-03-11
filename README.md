# EhViewer

![Icon](art/launcher_icon-web.png)

这是一个 E-Hentai Android 平台的浏览器。

An E-Hentai Application for Android.


# Screenshot

![screenshot-01](art/screenshot-01.png)


# Build

    $ git clone https://github.com/seven332/EhViewer
    $ cd EhViewer
    $ git submodule update --init
    $ gradlew app:copyNotice
    $ gradlew daogenerator:executeDaoGenerator
    $ gradlew app:assembleDebug

生成的 apk 文件在 app\build\outputs\apk 目录下

The apk is in app\build\outputs\apk

**注意**：如果你遇到了下面这样的错误，需要添加系统变量 NDK_HOME 为 android NDK 路径

**Note**: If you get the error below, set NDK_HOME environment variable

    * What went wrong:
    A problem occurred evaluating project ':app'.
    > assert ndkDir != null
           |      |
           null   false


# Thanks

本项目受到了诸多开源项目的帮助

Here is the libraries

- [AOSP](http://source.android.com/)
- [android-advancedrecyclerview](https://github.com/h6ah4i/android-advancedrecyclerview)
- [apng](http://apng.sourceforge.net/)
- [giflib](http://giflib.sourceforge.net)
- [greenDAO](https://github.com/greenrobot/greenDAO)
- [jsoup](https://github.com/jhy/jsoup)
- [libjpeg-turbo](http://libjpeg-turbo.virtualgl.org/)
- [libpng](http://www.libpng.org/pub/png/libpng.html)
- [okhttp](https://github.com/square/okhttp)
- [roaster](https://github.com/forge/roaster)
- [Slabo](https://github.com/TiroTypeworks/Slabo)
- [TagSoup](http://home.ccil.org/~cowan/tagsoup/)


# License

    Copyright (C) 2014-2016 Hippo Seven

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.