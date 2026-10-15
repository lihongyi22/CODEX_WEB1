# CODEX_WEB1

一个尝试让 codex 云端运行的仓库。

## Copilot/Codex 云端连接与运行

本仓库已添加 `/.github/workflows/copilot-setup-steps.yml`，用于在 GitHub Actions 中为 Copilot cloud agent 预热环境。

使用方式：

1. 保持该 workflow 在默认分支上。
2. 在仓库中启用 Copilot cloud agent 后，Agent 会先执行 `copilot-setup-steps` 任务，再开始代码工作。
3. 你也可以在 Actions 页手动运行 **Copilot Setup Steps**，确认云端环境可用。
