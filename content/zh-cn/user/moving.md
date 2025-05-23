---
title: 迁移或离开账户
description: 获取你的信息，并随意处置它们。
menu:
  docs:
    weight: 100
    parent: user
---

## 导出你的信息 {#export}

{{< figure src="assets/export.png" width="70%" caption="设置中的数据导出页面" >}}

你可以随时前往“设置”>“导出”，下载包含以下信息的 CSV 文件：你当前关注的账户、你当前创建的列表、你当前屏蔽的账户、你当前隐藏的账户，以及你当前屏蔽的站点。你的关注、隐藏、屏蔽和域名屏蔽列表可以在“设置”>“导入”中导入，并且可以选择合并或覆盖现有列表。

你可以每 7 天请求一次你的嘟文和媒体文件的存档，并以 Activity Streams 2.0 JSON 格式下载。由于技术限制，Mastodon 目前不支持导入嘟文或媒体文件，但你的存档可以通过任何能够解析 Activity Streams 2.0 文档的软件查看。

## 重定向或迁移你的账户 {#migration}

在“设置”>“账户”的底部，你可以找到与账户重定向或迁移相关的选项。

### 账户重定向 {#redirect}

重定向你的账户会禁用该账户的发布功能，并显示“账户已迁移”的通知，表明你的新账户。任何访问你账户的人都可以看到这个通知，并知晓需要转到你的新账户关注你。不支持关注重定向的账户。可以随时取消重定向。

### 账户迁移 {#move}

{{< figure src="assets/account-move.png" width="70%" caption="账户迁移表单" >}}

迁移你的账户与重定向你的账户相同，但它还会不可逆转地强制所有人取消关注你当前的账户，并关注你的新账户（如果他们的软件支持 Move 活动）。由于技术限制，你的嘟文不会被迁移。此外，还有一个 30 天的冷却期，在此期间你不能再次迁移，所以在使用此选项之前请务必小心！

虽然理论上迁移账户会自动将你的关注者转移到新账户，但它不会自动转移你的关注、屏蔽、隐藏和书签。这些可以通过[之前导出的 CSV 文件](./#export)导入。

### 账户别名 {#aliases}

只有当你的两个账户已经配置了别名关联时，才能发起账户迁移。账户别名目前仅用于账户迁移，你需要将你的旧账户设置为你的新账户的别名，然后才能发起迁移。设置别名本身是无害的，并且可以撤销。

## 删除你的账户 {#delete}

{{< figure src="assets/account-delete.png" width="70%" caption="账户删除表单" >}}

在“设置”>“账户”的底部，你可以找到删除你账户的表单。删除你的账户是不可逆转的，并且会令你的账户和用户名永远无法再次使用。

{{< translation-status-zh-cn raw_title="Moving or leaving accounts" raw_link="/user/moving/" last_translation_time="2025-04-21" raw_commit="6addd5cf525adec1859f48c52dafcfe1f96e558a">}}
