# Magie Android Releases

Magie Android 的官方发行包与更新清单。Android 8.0 及以上。

从 [最新版本](https://github.com/lantiansb/EEBadge-Android-Releases/releases/latest) 下载 APK。首次安装需要允许浏览器或文件管理器安装应用；后续可在 Magie 的「我的 → 应用更新」下载并安装新版。

每个正式版本提供签名 APK、`android-update.json`、`SHA256SUMS.txt`、`signing-certificate.txt` 和更新说明。此仓库启用了 GitHub release immutability，发布后的文件与标签保持不变；修复使用新版本号发布。APP 根据构建号判断升级，同签名覆盖更新保留本机数据。

正式版包名为 `cn.magie.app`。固定签名证书的 SHA-256：

```text
cd500650d6c4f3b3e8a41349360455f44c81df0c7a009db82221767f028a85c7
```

历史同包名调试版与正式签名不兼容，无法覆盖安装。卸载旧包会清除数据，请先另存本机作品。包名为 `cn.magie.app.debug` 的测试版可以与正式版共存。

源码另行私有管理。此仓库只存公开发行资料。
