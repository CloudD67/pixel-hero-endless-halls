# 贡献指南 Contributing

欢迎来玩、来提意见、来写代码！这个仓库就一个 HTML 文件，门槛低，随便折腾。

## 🐞 报 Bug

直接用 [Issue 模板](https://github.com/CloudD67/pixel-hero-endless-halls/issues/new/choose) 提交，记得带上：

- 平台（桌面 / 手机）与浏览器机型
- 复现步骤（第几波、按了什么）
- 控制台报错（桌面按 F12 复制）或截图

## 💡 提建议

新技能、新 Boss、数值平衡、音效手感……直接提 Feature Issue，或到 Discussions 讨论。

## 🔧 改代码

1. Fork 仓库
2. 修改 `pixel-hero.html`（数值请只动 `CONFIG` 模块，别打散到别处）
3. 本地双击验证：确认桌面键鼠 / 手机摇杆都能正常玩、连续几波不卡
4. 提 Pull Request，说明改了什么、为什么改

### 小约定

- 注释用中文，模块头保持原有格式
- 不引入任何外部依赖（CDN/图片/音频/字体都要拒绝）
- 不破坏「单文件打开即玩」这条底线

## 📄 许可

参与即视为同意以 [MIT](LICENSE) 协议贡献你的改动。
