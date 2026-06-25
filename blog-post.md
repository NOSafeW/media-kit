# Blog Post Draft

# SafeW 安全吗？安装前先看这份公开证据整理

如果你是通过朋友、群聊或某个下载页看到 SafeW、SafeW Messenger、SafeW 小飞机、SafeX 聊天，请先别急着安装。

这篇文章不是让你相信某个站点的结论，而是把公开来源、包名、截图和自救步骤放在一起，方便你自己核对。

## 1. 公开报告点名了哪些标识

Kaspersky Securelist 的公开报告中，SafeW 相关包名 / Bundle ID 出现在受影响应用列表：

- `org.safew.messenger`
- `org.safew.messenger.store`
- `com.safew.messenger`

The Hacker News 2026 年报道中，也列出 Android 的 SafeX 与 iOS 的 SafeW - 云办公助理。

证据整理： https://nosafew.com/evidence/

## 2. 风险到底是什么

公开报告描述的 SparkCat 手法包括：应用申请图库权限后，使用 OCR 识别相册图片中的文字，寻找加密钱包恢复短语、助记词、私钥、密码等内容，并上传命中的图片。

所以问题不是“聊天软件能不能发图”，而是拿到相册权限后是否在后台扫描敏感截图。

## 3. SafeW 和 SafeX 是什么关系

站点整理的公开记录显示：SafeW 被公开点名 / 下架后，Android 分发链路出现 SafeX 名称，The Hacker News 2026 报道中也列出 SafeX。

普通用户不必纠结哪个名字更新。更简单的原则是：SafeW、SafeX 都不要装。

## 4. 已经安装怎么办

先做三件事：

1. 撤销相册、文件、通讯录等权限并卸载。
2. 检查相册里是否存过助记词、私钥、密码、2FA 备份码。
3. 如果存过助记词或私钥，尽快创建新钱包并转移资产。

完整自救指南： https://nosafew.com/remove/

## 5. 给普通用户的判断原则

不要只看“高强度加密”“安全通信”“管理员也看不到”这类宣传。聊天软件是否可信，要看：

- 客户端是否可信。
- 是否开源可审计。
- 是否有独立安全审计。
- 是否被安全厂商公开点名过。
- 出事后是否有透明复盘。

对于 SafeW / SafeX，这些公开记录已经足够让普通用户选择避开。
