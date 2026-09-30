# 明媚下载器 · M6 Downloader

> 下载，本该明媚。 — Bright. Fast. Done.

这是 M6 Downloader 的**官方发布仓库**，只承载构建产物与产品官网。

- 🌐 **产品官网（介绍 + 下载）**：<https://moloStudio.github.io/m6-download/>
- 📦 **下载安装包**：见右侧 [Releases](../../releases) 或直接访问 [最新版](../../releases/latest)
- 🔒 **源码地址**：源码托管在私有仓库，**不在此公开**。如需参与或获取源码，请联系维护者。

---

## 关于 M6 Downloader

多线程分段下载器 + 内置浏览器嗅探 + HLS/BT + 可扩展插件体系。零广告、零捆绑、默认可离线。

| 平台 | 格式 |
|---|---|
| Windows | 安装包（NSIS）+ 便携版 |
| macOS | Apple Silicon / Intel（dmg + zip） |
| Linux | AppImage + deb + tar.gz |

## 下载

```text
Windows:  M6 Downloader-<version>-setup.exe / ...-portable.exe
macOS:    M6 Downloader-<version>-arm64.dmg  / ...-x64.dmg / .zip
Linux:    M6 Downloader-<version>-x64.AppImage / .deb / .tar.gz
```

所有安装包统一发布在 **[GitHub Releases](../../releases)**。

## 说明

- 安装包**未签名**：Windows 会触发 SmartScreen，点「更多信息 → 仍要运行」；macOS 会触发 Gatekeeper，在「系统设置 → 隐私与安全性」里点「仍要打开」，或执行 `xattr -dr com.apple.quarantine /Applications/明媚下载器.app`。
- 构建由 GitHub Actions 完成，源码从私有源临时拉取，构建编排见 `.github/workflows/release.yml`。

---

MIT License. Copyright © 2026 molo.