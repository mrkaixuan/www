# 特色功能

::: warning 注意！
以下列举的是 魔趣ROM 在 [Android 开源项目 (AOSP)](https://source.android.com/) 基础上所做的改进，不同版本间可能存在差异。例如一个功能只支持基于 Android 8.0 的 MK80.1 或更高版本，将被标注为 <Badge text="MK80.1+"/>
:::

[[toc]]

## 短信界面

::: warning 注意！
当您刷入 [Open Gapps Mini](https://github.com/opengapps/opengapps/wiki/Mini-Package) 及更完整的版本，内置短信程序将会被替换为 Google 版本，下列功能将会丧失。
:::

### 归属地信息 <Badge text="MK44.4+"/>
短信列表中会显示发送方的归属地信息。

![归属地信息](/screenshots/zh/messaging_location.png)

### 智能归档短信 <Badge text="目前仅支持中国大陆、中国香港、马来西亚与印度号码的识别" type="warn"/> <Badge text="MK71.2+"/>

当下，我们的短信程序中充斥着各类通知与验证码短信。它们的存在使得我们检索与好友间的日常短信变得极为困难。因此，魔趣将帮助您自动归档此类短信，让重要短信变得清晰可见。

### 自动识别验证码短信 <Badge text="MK60.1+"/>

魔趣会自动识别验证码类短信，您只需点击通知即可一键复制验证码，提高效率。

![验证码短信](/screenshots/zh/messaging_captcha.png)

### 自动删除验证码短信 <Badge text="MK71.2+"/>

验证码短信具有时效性，长期保存是没有意义的。开启该选项，当您复制验证码后，短信会自动销毁。

![自动删除验证码短信](/screenshots/zh/messaging_captcha_autodelete.png)

### 归档短信未读角标 <Badge text="MK71.2+" />

我们为归档短信加入了未读角标，避免你错过需要及时阅读的短信。

![归档短信未读角标](/screenshots/zh/messaging_unread_badge.png)

### 可左右滑动的归档界面 <Badge text="MK60.1+" />

Google 并未在 [Android 开源项目 (AOSP)](https://source.android.com/) 中添加短信归档界面的滑动支持，魔趣完善了它。

![可左右滑动的归档界面](/screenshots/zh/messaging_swipe.png)

### 短信快捷处理选项 <Badge text="MK60.1+" />

收到新通知时，Android 原生版本 只有一个"回复"选项，魔趣增加了"拨打"和"已读"选项。

![短信快捷处理选项](/screenshots/zh/messaging_quick_message_option.png)

## 拨号界面


