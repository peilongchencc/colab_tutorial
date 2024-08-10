# 实用技巧

- [实用技巧](#实用技巧)
  - [Colab保存Secret:](#colab保存secret)


## Colab保存Secret:

某些secret可能代码中会经常使用，总是粘贴很不方便，此时就可以将secret保存在colab中。操作方式如下:

1. 点击左侧🔑按钮。
2. 点击 "添加新密钥"。
3. 输入密钥名称、值、开启笔记本访问权限。

示例:

![](../docs/colab保存secret.png)

> [!CAUTION]
> 如果不 "开启笔记本访问权限" ，无法通过代码获取密钥内容。