
[链接](https://repo1.maven.org/maven2/io/github/nmstarry/fluentui-system-icon/2026.11.15/)

基于 2026 年 11 月 15 日最新主分支的文件打包

依赖引入

```kotlin
implementation("io.github.nmstarry:fluentui-system-icon:2026.11.15")
```

使用需要在项目 src\main\res\color\fluent_default_icon_tintx.xml 下配置默认的图标颜色

```xml
<?xml version="1.0" encoding="utf-8"?>
<selector xmlns:android="http://schemas.android.com/apk/res/android">
    <item android:color="#FF000000" />
</selector>
```

如果使用这个则不需要

```kotlin
implementation("io.github.nmstarry:fluentui-system-icon:2026.11.15FX")
```

但默认颜色为黑色
