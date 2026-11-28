# 已停用的历史工作流

这些文件只供追溯，已移出 `.github/workflows`，不会被 GitHub 执行。
2026-11-28 按用户要求取消 GitHub 托管机器上的构建、测试、诊断和镜像任务；旧工作流均已在仓库停用。

当前唯一发布入口为 `.github/workflows/publish-local.yml`，只支持手动启动，指定自有 Windows runner，上传本地已完成的包，不构建或测试产品。未准备齐三端产物时不启动。发布密钥仍在既有 Secrets 中，只传入这台自有电脑的发布进程，不写入交付文件。
