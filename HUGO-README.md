# HUGO GitHub Pages

本项目的GitHub Page主页基于[Hugo](https://gohugo.io/)构建。

- 主题: [hugo-whisper-theme](https://hugo-whisper.netlify.app/) (git module)
- 配置文件: [config.toml](config.toml)
- GitHub Page Workflow: [hugo.yaml](.github/workflows/hugo.yaml)
- 主要内容: 放置于 `content/docs/` 目录

## 本地部署

### 安装 Hugo

Windows

```powershell
winget install Hugo.Hugo.Extended
```

Linux

```sh
# Debian: elementary OS, KDE neon, Linux Lite, Linux Mint, MX Linux, Pop!_OS, Ubuntu, Zorin OS, and others
sudo apt install hugo   

# Fedora: CentOS, Red Hat Enterprise Linux, and others
sudo dnf install hugo   
```

macOS

```sh
brew install hugo
```

### 运行服务

启动热更新的本地hugo服务

```sh
cd awesome-research-tools
hugo server
```
