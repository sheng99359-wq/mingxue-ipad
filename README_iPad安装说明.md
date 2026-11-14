# 明学教育资料助手 — iPad 安装使用指南

本文件夹 (`ipad_ios_project`) 是可直接打包成 **iPad `.ipa` 安装包** 与 **iPad 桌面 PWA 应用** 的完整工程，内含网页主程序 (`www/`) 与自动云端编译脚本 (`.github/workflows/`)。

---

## 方式一：免费获取 `.ipa` 安装包并装到自己的 iPad（不需买 Mac）
1. 在 GitHub（`https://github.com`）新建一个仓库（可设为 Private 私有仓库），把本文件夹 `ipad_ios_project` 里的全部文件上传/推送上去。
2. 打开 GitHub 仓库顶部的 **Actions** 页面 → 点 **Build iPad IPA**，等待约 2～3 分钟云端 macOS 自动编译完成。
3. 在编译结果页面的 **Artifacts** 下方下载 **`MingXue-iPad-IPA`**（解压即得 `明学教育助手_iPad版.ipa`）。
4. 在 Windows 电脑下载免费工具 **Sideloadly**（`https://sideloadly.io`）或 **AltStore**，用数据线连接 iPad，输入您自己的普通 Apple ID，把 `.ipa` 拖进去点 Start，即可正式安装到 iPad 桌面！

---

## 方式二：同时自动生成一个免电脑永久网址（推荐，不用每 7 天续签）
上传到 GitHub 后，在仓库 **Settings → Pages → Source** 选择 **GitHub Actions**：
- **Deploy iPad Web App to GitHub Pages** 会自动为您生成一个专属 `https://您的用户名.github.io/仓库名/` 网址。
- 用 iPad **Safari** 打开该网址，点右上角 **分享（⬆️）→「添加到主屏幕」**，即可生成永久不过期的 iPad 桌面 App，支持离线缓存界面和词库，彻底脱离电脑和 OneDrive！
