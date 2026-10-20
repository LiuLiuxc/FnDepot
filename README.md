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

> ❤️ **支持开发者**：[爱发电 · afdian.com/a/Anixc](https://afdian.com/a/Anixc)
> —— 这里的应用都是一个人维护的，赞助只是让它们继续更新，不影响任何功能。
> （汇页 PDF 飞牛端完全免费；miNVR 基础功能免费，高级功能一次性解锁。）

---

## 📦 应用列表

### 📹 miNVR

本地视频监控：米家摄像头接入，实时预览最多九路同屏，事件录像与历史回放，画面全部留在自己的 NAS 上。

<br/>

<div align="center">

[![miNVR](https://img.shields.io/badge/miNVR-v1.7.1-orange?style=flat-square)](https://github.com/LiuLiuxc/FnDepot) [![Platform](https://img.shields.io/badge/Platform-x86__64-lightgrey?style=flat-square)](#)

</div>

<br/>

| 项目 | 信息 |
| :--- | :--- |
| 👨‍💻 **开发者** | [Anixc](https://github.com/LiuLiuxc) |
| 📥 **安装方式** | 在 FnDepot / Moo 中添加本源，客户端里搜索「miNVR」即可安装 |
| 🏷️ **版本** | v1.7.1 |
| 🖥️ **平台** | x86_64（飞牛 fnOS，安装位置：系统空间） |
| 📦 **安装包** | 本仓 [Releases](https://github.com/LiuLiuxc/FnDepot/releases)（158.3 MB） |
| 📖 **详细说明** | [miNVR/README.md](miNVR/README.md) |

<br/>

<div align="center">
  <img src="https://raw.githubusercontent.com/LiuLiuxc/FnDepot/main/assets/dash.svg" width="480" height="6" alt="">
</div>

<br/>

### 📄 汇页 PDF

PDF 与扫描件的合并、排序、删页旋转、按页拆分、压缩与隐私水印；全部在浏览器与 NAS 本机完成，文件不上传任何服务器。

<br/>

<div align="center">

[![汇页 PDF](https://img.shields.io/badge/%E6%B1%87%E9%A1%B5%20PDF-v1.0.29-orange?style=flat-square)](https://github.com/LiuLiuxc/FnDepot) [![Platform](https://img.shields.io/badge/Platform-x86__64%20%2F%20arm64-lightgrey?style=flat-square)](#)

</div>

<br/>

| 项目 | 信息 |
| :--- | :--- |
| 👨‍💻 **开发者** | [Anixc](https://github.com/LiuLiuxc) |
| 📥 **安装方式** | 在 FnDepot / Moo 中添加本源，客户端里搜索「汇页 PDF」即可安装 |
| 🏷️ **版本** | v1.0.29 |
| 🖥️ **平台** | x86_64 / arm64 通用（飞牛 fnOS，安装位置：系统空间） |
| 📦 **安装包** | 本仓 [Releases](https://github.com/LiuLiuxc/FnDepot/releases)（4.91 MB） |
| 📖 **详细说明** | [huiyepdf/README.md](huiyepdf/README.md) |

---

## 📂 仓库结构

```
README.md          本源首页（本文件）
fnpack.json        FnDepot 索引（V2：schema_version + source_info + apps）
moo.json           Moo 索引
miNVR/             应用目录：图标 / 介绍 / 预览图
huiyepdf/          同上（汇页 PDF）
  每个应用目录下：ICON.PNG、README.md、preview/
```

> **安装包不进仓库**：fpk 一律挂在**本仓的 Release 附件**里，索引里的 `download_url` 直接指向它。
> （miNVR 的包 158 MB，超过 GitHub 单文件 100 MB 的硬上限；汇页 PDF 只有 4.91 MB，但为保持一致也走 Release。）

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
