# Damion 工具目录

| 目录 | 项目 | 用途 |
| --- | --- | --- |
| [skills/](./skills) | [mpd](https://github.com/DamionH0108/mpd#readme) | 在 Claude Code 或 Codex 中用一个总控会话协调多个项目。 |
| [tools/](./tools) | [Claude 出口守卫](https://github.com/DamionH0108/claude-network-guard#readme) | 在 macOS 上检查代理出口是否仍为指定 IP，并查看检测结果。 |

点击项目名查看最新安装说明。只用一个项目时，按它自己的 README 安装即可。

要把两项源码同时下载到对应目录，运行：

```sh
git clone --recurse-submodules https://github.com/DamionH0108/damion-toolkit.git
```

目录通过 Git 子模块引用两个项目的确定版本，原仓库和安装地址均保留。
