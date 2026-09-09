# 像素勇者：无尽回廊 (Pixel Hero: Endless Halls)

单文件、零依赖的像素风 Roguelite 动作游戏。打开即玩，桌面（键鼠）与手机（虚拟摇杆+触摸按钮）自动适配。

A single-file, zero-dependency pixel-art Roguelite action game. Open and play — auto-adapts for desktop (keyboard & mouse) and mobile (virtual joystick + touch buttons).

## 玩法

打怪掉落经验/金币 → 升级三选一 → 12 种强化卡 + 10 个技能成长 → 连击攒伤害 → 每 5 波 Boss 战 → 休整期商店消费 → 每 5 波场景主题轮换（地牢/雪原/熔岩/虚空）。

## 运行

直接双击或在浏览器打开 `pixel-hero.html` 即可游玩。

- 桌面：WASD/方向键移动，J/左键普攻，K/右键冲刺，1-4 技能，P 暂停，R 重开，空格确认
- 手机：左半屏虚拟摇杆移动，右半屏点击/右下角按钮攻击，冲刺与技能为固定尺寸触摸按钮；竖屏提示旋转手机

## 特性

- 纯原生 JavaScript + Canvas，零外部依赖（无 CDN/图片/音频/字体）
- Web Audio 程序化合成 16+ 种音效
- 对象池 + fixed timestep 60fps 主循环
- 全部像素精灵由字符串数组 + 调色板程序化绘制
- 最高波次纪录存于 localStorage
