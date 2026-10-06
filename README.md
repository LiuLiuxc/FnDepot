# Anixc 的 FnDepot 应用源

飞牛 fnOS 第三方应用源，**一份仓同时服务 Moo 与 FnDepot 两个生态**。

## 添加本源

| 客户端 | 操作 |
|---|---|
| **Moo** | 设置 → 应用源设置 → 添加应用源 → `https://github.com/LiuLiuxc/FnDepot` |
| **FnDepot** | 添加源 → 填同一个地址 |

> 也可以是：Moo 首页搜索框直接粘这个地址（贴链接直搜，不添加源也能列出，但不驻留、不检测更新）。

本仓一份内容、两个索引：`moo.json`（Moo 客户端优先读它，字段最全）、`fnpack.json`（FnDepot 生态，V1 扁平格式）。

---

## 应用列表

### miNVR

适配米家摄像头的本地视频监控：实时预览、区域侦测、事件录像、历史回放、邮件提醒，**画面全部留在自己的 NAS 上**。

| 项目 | 信息 |
| :--- | :--- |
| 👨‍💻 **作者 / 发布者** | Anixc |
| 🏷️ **版本** | 1.4.68 |
| 🖥️ **平台** | x86_64 |
| 📁 **应用目录** | [`miNVR/`](miNVR/) |
| 📥 **获取方式** | 添加本源后，在客户端里搜「miNVR」安装 |

完整介绍见 **[miNVR/README.md](miNVR/README.md)**。

---

## 仓库结构

```
fnpack.json        FnDepot 索引（V1 扁平，社区源列表 CI 只认这一种）
moo.json           Moo 索引（字段最全：简介 / 预览 / README / 开发者）
miNVR/             每个应用一个目录，互不干扰
  ├── ICON.PNG     图标
  ├── README.md    应用介绍
  └── preview/     预览图
```

> **安装包不进仓库**：fpk 有 141.6 MB，超过 GitHub 单文件 100 MB 的硬上限，
> 因此挂在**本仓的 Release 附件**里，索引里的 `download_url` 直接指向它。
