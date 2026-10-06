# miNVR

**适配米家摄像头的本地视频监控** —— 飞牛 fnOS 第三方应用，当前版本 **1.4.68**。

## 安装

| 客户端 | 操作 |
| :--- | :--- |
| **Moo** | 设置 → 应用源设置 → 添加应用源 → `https://github.com/LiuLiuxc/FnDepot` |
| **FnDepot** | 添加源 → 填同一个地址 |

> 也可以在 Moo 首页搜索框直接粘这个地址（贴链接直搜，不添加源也能列出，但不驻留、不检测更新）。

添加后搜 **miNVR** 即可安装。完整介绍见 [miNVR/README.md](miNVR/README.md)。

---

## 仓库结构

```
fnpack.json        FnDepot 索引（V1 扁平）
moo.json           Moo 索引
miNVR/             应用目录
  ├── ICON.PNG     图标
  ├── README.md    应用介绍
  └── preview/     预览图
```

> **安装包不进仓库**：fpk 有 141.6 MB，超过 GitHub 单文件 100 MB 的硬上限，
> 因此挂在**本仓的 Release 附件**里，索引里的 `download_url` 直接指向它。
