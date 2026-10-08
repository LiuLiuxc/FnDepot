<div align="center">

![FnDepot](https://img.shields.io/badge/FnDepot-应用源-blue?style=for-the-badge)
![Moo](https://img.shields.io/badge/Moo-应用源-purple?style=for-the-badge)
![fnOS](https://img.shields.io/badge/fnOS-NAS-green?style=for-the-badge)

# 🚀 FnDepot / Moo 第三方应用源

**由 [Anixc](https://github.com/LiuLiuxc) 维护的 FnDepot / Moo 第三方应用源**

索引同时提供 **FnDepot**（`fnpack.json`）与 **Moo**（`moo.json`）两种格式，两个商店都能添加本源。

[![GitHub stars](https://img.shields.io/github/stars/LiuLiuxc/FnDepot?style=social)](https://github.com/LiuLiuxc/FnDepot)
[![GitHub forks](https://img.shields.io/github/forks/LiuLiuxc/FnDepot?style=social)](https://github.com/LiuLiuxc/FnDepot)
[![GitHub issues](https://img.shields.io/github/issues/LiuLiuxc/FnDepot)](https://github.com/LiuLiuxc/FnDepot/issues)

[🔗 添加本源](https://github.com/LiuLiuxc/FnDepot) · [📖 FnDepot 使用文档](https://github.com/EWEDLCM/FnDepot) · [📖 Moo 使用文档](https://github.com/Blue-Mink/moo) · [🐛 问题反馈](https://github.com/LiuLiuxc/FnDepot/issues)

</div>

---

## 📦 应用列表

### 📹 miNVR

适配米家摄像头的本地视频监控：实时预览、区域侦测、事件录像、历史回放、邮件提醒，画面全部留在自己的 NAS 上。

<br/>

<div align="center">

[![miNVR](https://img.shields.io/badge/miNVR-v1.4.74-orange?style=flat-square)](https://github.com/LiuLiuxc/FnDepot) [![Platform](https://img.shields.io/badge/Platform-x86__64-lightgrey?style=flat-square)](#)

</div>

<br/>

| 项目 | 信息 |
| :--- | :--- |
| 👨‍💻 **开发者** | [Anixc](https://github.com/LiuLiuxc) |
| 📥 **安装方式** | 在 FnDepot / Moo 中添加本源，客户端里搜索「miNVR」即可安装 |
| 🏷️ **版本** | v1.4.74 |
| 🖥️ **平台** | x86_64（飞牛 fnOS，安装位置：系统空间） |
| 📦 **安装包** | 本仓 [Releases](https://github.com/LiuLiuxc/FnDepot/releases)（141.6 MB） |
| 📖 **详细说明** | [miNVR/README.md](miNVR/README.md) |
| ❤️ **爱发电** | [afdian.com/a/miNVR](https://afdian.com/a/miNVR)（支持开发者持续维护） |

---

## 📂 仓库结构

```
README.md          本源首页（本文件）
fnpack.json        FnDepot 索引（V2：schema_version + source_info + apps）
moo.json           Moo 索引
miNVR/             每个应用一个目录
  ├── ICON.PNG     图标
  ├── README.md    应用介绍
  └── preview/     预览图
```

> **安装包不进仓库**：fpk 有 141.6 MB，超过 GitHub 单文件 100 MB 的硬上限，
> 因此挂在**本仓的 Release 附件**里，索引里的 `download_url` 直接指向它。

---

## 🙏 致谢

- [FnDepot 外部应用源编写说明](https://github.com/EWEDLCM/FnDepot)
- [FnDepot 社区源列表](https://github.com/710850609/FnDepot)
- [Moo 第三方应用中心（客户端与使用说明）](https://github.com/Blue-Mink/moo)
- [飞牛 fnOS](https://www.fnnas.com/)

---

<div align="center">

**⭐ 如果这个仓库对你有帮助，请给个 Star！** ⭐

Made with ❤️ by [Anixc](https://github.com/LiuLiuxc)

</div>
