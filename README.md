# 广州敏哥聊财税｜微信视频号

本仓库对应本地项目根目录，包含：

- `财税视频号内容库/`：视频号内容、选题、复盘与素材库
- `.codex/`：本项目使用的 Codex 工作流配置

## 同步到 GitHub

在项目根目录执行：

```powershell
git status
git add -A
git commit -m "更新视频号内容与项目配置"
git pull --rebase origin main
git push origin main
```

以后不要进入 `财税视频号内容库/` 目录单独执行 Git 命令；所有项目文件都从本目录统一同步。
