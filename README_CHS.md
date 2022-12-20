clash 配置文件模板

## 特点

使用 **Proxy Provider** 和 **Rule Provider**, 定时自动更新。

将经常需要更新的节点和规则分离，脱离基础配置，摆脱机场的陈旧规则，避免因规则引起断流。

点击此处了解 [Proxy Provider](https://lancellc.gitbook.io/clash/clash-config-file/proxy-provider) 和 [Rule Provider](https://lancellc.gitbook.io/clash/clash-config-file/rule-provider)。

## 兼容性

本配置文件**仅支持** [Clash Premium 核心](https://github.com/Dreamacro/clash/releases/tag/premium) (闭源) 和第三方 clash 核心，如 [Clash.Meta 核心](https://github.com/MetaCubeX/Clash.Meta) (开源)。

使用 Clash Premium 核心的用户界面应用：[CFA Premium 版本](https://github.com/Kr328/ClashForAndroid/releases) (Android) 和 [CFW](https://github.com/Fndroid/clash_for_windows_pkg/releases) (Windows/MacOS)。

使用 Clash.Meta 核心的用户界面应用：[CMFA](https://github.com/MetaCubeX/ClashMetaForAndroid) (Android)。

## 使用方法

强烈推荐使用短链接服务（如 [short.io](https://short.io/) 或 [bitly](https://bitly.com)），方便更新订阅地址而无需修改配置文件。

本配置文件已经包含基础节点分组和规则集合，只需要把 rule-providers 字段中的 #必须填写 标记替换成你的机场订阅地址即可导入clash使用。

### ss订阅注意

如果你的订阅是 ShadowSocks (ss) 类型，可能需要在订阅地址结尾加上 `&flag=clash` 来获得 yaml 文件，若返回 based64 编码的字符串会导致 clash 更新失败。