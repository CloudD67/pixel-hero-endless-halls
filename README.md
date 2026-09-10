# 像素勇者：无尽回廊 (Pixel Hero: Endless Halls)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Desktop%20%26%20Mobile-blue)]
[![Dependencies](https://img.shields.io/badge/Dependencies-Zero-green)]
[![Language](https://img.shields.io/badge/Language-JavaScript-blueviolet)]

> 🎮 **一个 .html 文件，双击就玩**的像素风 Roguelite 动作游戏。桌面键鼠、手机摇杆自动适配，同一个文件两头通吃。零依赖、零安装、零广告。

**🎯 在线试玩（推荐，直接点就能玩）：**
https://cloudd67.github.io/pixel-hero-endless-halls/

也可以直接访问游戏实体文件：
https://cloudd67.github.io/pixel-hero-endless-halls/pixel-hero.html

> 注意：仓库里的 `raw.githubusercontent.com` 链接打开是源码文本（GitHub 的 raw 设计如此），要玩请用上面的 Pages 地址。

## ✨ 特性

- **单文件零依赖**：无 CDN、无图片、无音频、无字体，全部内嵌
- **像素手绘风**：所有精灵用「字符串数组 + 调色板」程序化绘制
- **Web Audio 合成音效**：16+ 种音效纯振荡器/噪声合成，连击音随层数升调
- **完整 Roguelite 循环**：打怪掉经验/金币 → 升级三选一（12 强化卡 + 10 技能）→ 连击加伤 → 波次推进 → 每 5 波 Boss 战（三 Boss 轮换）→ 休整期商店
- **8 种敌人 + 精英变异**：史莱姆 / 蝙蝠 / 骷髅（死亡分裂）/ 法师 / 自爆怪 / 冲锋牛 / 暗影闪现
- **4 大场景主题**：地牢 → 雪原 → 熔岩 → 虚空，每 5 波轮换
- **性能友好**：对象池 + fixed timestep 60fps；手机端自动粒子减半、飘字限流、震屏减半

## 🎮 操作

| 平台 | 移动 | 攻击 | 冲刺 | 技能 | 其他 |
| --- | --- | --- | --- | --- | --- |
| 桌面 | WASD / 方向键 | J / 左键 | K / 右键 | 1~4 | P 暂停 · R 重开 · 空格确认 |
| 手机 | 左半屏虚拟摇杆 | 右下按钮 / 右半屏点按 | 冲刺钮 | 底部 4 钮 | 竖屏提示旋转 |

## 📦 仓库结构

```
pixel-hero.html      游戏本体（唯一的必要文件）
index.html           GitHub Pages 首页跳转（自动进入游戏）
404.html             兜底跳转（备用）
LICENSE              MIT 协议
CONTRIBUTING.md      贡献指南
CODE_OF_CONDUCT.md   行为准则
.github/             Issue 模板
```

## 🚀 本地运行

- 双击 `pixel-hero.html` 直接用浏览器打开
- 或起个本地服务（方便手机同 WiFi 试玩）：

```bash
python3 -m http.server 8000
# 手机访问 http://<电脑IP>:8000/pixel-hero.html
```

## 🧩 数值与玩法

所有数值集中在代码顶部 `CONFIG` 模块（与开发文档表格一一对应），想调节奏只改那里即可。

## 🤝 参与

见 [CONTRIBUTING.md](CONTRIBUTING.md)。有想法直接提 Issue / Discussion，欢迎 PR！

## 📄 许可

[MIT](LICENSE) © 2026 CloudD67
