# 更新日志

[2016-11-09]

本插件可以配合 `react-native.d.ts` 以及 `react.d.ts` 使用
webstorm -> language & frameworks -> javascript -> Libraries 

点击【download】按钮，找到 react.d.ts 和 react-native.d.ts 下载，大功告成！

[2015-12-25]

新增组件属性，调用ReactNative组件时，首先按下 `command + J`，然后输入属性名的 `首字母` 如输入`onP` 自动提示 `onPress, onPressIn, onPressOut, .....`

# 说明
ReactNative的代码模板，包括：

1. 组件名称
2. Api 名称
3. 所有StyleSheets属性
4. 组件属性 [2015-12-25]新增

# 安装

### 方法一 由于ReactNative.jar更新不方便而且过于陈旧，强烈建议使用方法二进行安装，ReactNative.jar 也会删除
`file` -> `import settings` -> `ReactNative.jar`

### 方法二

Mac下安装

> 提示：如果没有`templets` 文件夹，你可以手动创建一个

#### webstorm11安装路径
将`ReactNative.xml`复制到 `~/Library/Preferences/WebStorm11/templates`

#### webstorm2016.2安装路径
将`ReactNative.xml`复制到 `~/Library/Preferences/WebStorm2016.2/templates`

#### webstorm2017.1安装路径
将`ReactNative.xml`复制到 `~/Library/Preferences/WebStorm2017.1/templates`

#### webstorm2017.2安装路径
将`ReactNative.xml`复制到 `~/Library/Preferences/WebStorm2017.2/templates`

重启 WebStorm

# 使用方法
### 通用方法
直接输入 `组件` 或 `Api` 名称的`首字母`，比如想要 `View`，只要输入 `V` 自动提示代码里就会看到 `View`

### StyleSheet属性提示

首先按下 `command + J`，然后输入属性名的 `首字母`

如：输入 `f`，会自动提示 fontSize, fontFamily, fontStyle...等等
