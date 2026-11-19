# Audio Visualizer for mpv player

- **Audio Visualizer** — Visualize audio in real time for mpv player.
- 一款为 mpv 播放器打造的音频可视化插件，支持多种可视化效果

![image](./images/visualizer.gif)

## 📦 安装方法 Installation

1. 将 `visualizer.lua` 复制到你的 mpv 配置目录下的 `scripts` 文件夹中：

- **Windows (Portable 便携版)**: `portable_config/scripts/visualizer.lua`
- **Windows (安装版)**: `%APPDATA%/mpv/scripts/visualizer.lua`
- **Linux / macOS**: `~/.config/mpv/scripts/visualizer.lua`

2. 设置快捷键

- 打开配置文件夹中的 `input.conf`，写入快捷键

```
c    script-message visualizer      #menu: 音频 > 开启/切换 可视化频谱
C    script-message visualizer off  #menu: 音频 > 关闭 可视化频谱
```

### ⚙️ 配置 Configuration

- 配置文件：`script-opts/visualizer.conf`

```bash
# mode=novideo, force
mode=novideo
# name=avectorscope, showfreqs, linefreqs, off
name=avectorscope
# quality=verylow, low, medium, high, veryhigh
quality=medium
# forcewindow=yes, no
forcewindow=yes
```
