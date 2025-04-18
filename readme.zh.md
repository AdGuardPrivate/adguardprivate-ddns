# AdGuard 私人 DDNS

[English](readme.md) | [Français](readme.fr.md) | [Português](readme.pt.md) | [Italiano](readme.it.md) | [Polski](readme.pl.md) | [Türkçe](readme.tr.md) | [Español](readme.es.md) | [Deutsch](readme.de.md) | [日本語](readme.ja.md) | [中文](readme.zh.md) | [Русский](readme.ru.md) | [العربية](readme.ar.md) | [한국어](readme.ko.md) | [Nederlands](readme.nl.md) | [Dansk](readme.da.md) | [Suomi](readme.fi.md) | [Norsk](readme.no.md) | [Svenska](readme.sv.md)

此项目由 [@jqknono](https://github.com/jqknono) 贡献。

## 概述

AdGuard 私人 DDNS 旨在提供一种简单的方法来快速设置私人动态 DNS (DDNS)，无需购买域名。此 DDNS 脚本专为 [adguardprivate.com](https://adguardprivate.com) 开发，通过利用 AdGuardPrivate 的基础功能，您可以无缝实现此功能。

## 功能

- 快速且易于设置。
- 利用 AdGuardPrivate 实现 DDNS 功能。
- 支持 Windows 和基于 Unix 的系统。
- 多种认证选项：cookies（更安全但可能过期）或用户名/密码（更持久但安全性较低）。
- **AdGuardHome 支持**：完全兼容 AdGuardHome，利用其功能实现无缝 DDNS 设置。

## 与传统 DDNS 的区别

与传统 DDNS 不同，此私人 DDNS 具有以下优势：

- **无缓存时间**：更改立即生效，无需等待 DNS 缓存过期。
- **无 DNS 传播**：更新立即可用，无需 DNS 传播延迟。
- **无需购买域名**：您可以使用伪域名进行访问，消除了购买域名的需要。
- **隐私保护**：只有连接到私人 DNS 服务的用户才能解析 DNS，确保隐私。

## 入门指南

1. 确保已安装并运行 AdGuardPrivate 或 AdGuardHome。
2. 按照 `win/ddns.ps1`（适用于 Windows）或 `unix/ddns.sh`（适用于基于 Unix 的系统）脚本中提供的说明配置您的私人 DDNS。

## 许可证

此项目根据存储库中包含的 [LICENSE](LICENSE) 的条款获得许可。