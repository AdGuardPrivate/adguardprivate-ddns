# AdGuard Private DDNS

![](https://img1.jqknono.com/blog/202504021622971.png)

[English](readme.md) | [Français](readme.fr.md) | [Português](readme.pt.md) | [Italiano](readme.it.md) | [Polski](readme.pl.md) | [Türkçe](readme.tr.md) | [Español](readme.es.md) | [Deutsch](readme.de.md) | [日本語](readme.ja.md) | [中文](readme.zh.md) | [Русский](readme.ru.md) | [العربية](readme.ar.md) | [한국어](readme.ko.md) | [Nederlands](readme.nl.md) | [Dansk](readme.da.md) | [Suomi](readme.fi.md) | [Norsk](readme.no.md) | [Svenska](readme.sv.md)

This project is contributed by [@jqknono](https://github.com/jqknono).

## Overview

AdGuard Private DDNS aims to provide an easy way to set up a quick private Dynamic DNS (DDNS) without the need to purchase a domain name. This DDNS script is specifically developed for [adguardprivate.com](https://adguardprivate.com) and by leveraging the base functionality of AdGuardPrivate, you can achieve this seamlessly.

## Features

- Quick and easy setup.
- Utilizes AdGuardPrivate for DDNS functionality.
- Supports both Windows and Unix-based systems.
- Multiple authentication options: cookies (safer but may expire) or username/password (more persistent but less secure).
- **AdGuardHome Support**: Fully compatible with AdGuardHome, leveraging its functionality for seamless DDNS setup.

## Difference from Traditional DDNS

Unlike traditional DDNS, this private DDNS has the following advantages:

- **No Cache Time**: Changes take effect immediately without waiting for DNS cache expiration.
- **No DNS Propagation**: Updates are instantly available without the need for DNS propagation delays.
- **No Domain Purchase Required**: You can use pseudo-domains for access, eliminating the need to buy a domain name.
- **Privacy Protection**: Only users connected to the private DNS service can resolve the DNS, ensuring privacy.

## Getting Started

1. Ensure you have AdGuardPrivate or AdGuardHome installed and running.
2. Follow the instructions provided in the `win/ddns.ps1` (for Windows) or `unix/ddns.sh` (for Unix-based systems) scripts to configure your private DDNS.

## License

This project is licensed under the terms of the [LICENSE](LICENSE) included in the repository.
