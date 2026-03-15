# Profile README 快速配置指南

## 🎉 已更新完成

你的 GitHub Profile README 已经更新并推送！新的首页突出展示了你的：

- ✅ **区块链/Web3 专业身份**
- ✅ **真实项目展示**（ZeroChain, 3D-GPS, 交易所 SDK 等）
- ✅ **核心技术栈**（Rust, Substrate, Solana 等）
- ✅ **GitHub 统计数据**（暗色主题）
- ✅ **组织贡献展示**

---

## 🔧 需要自定义的占位符

请立即修改以下内容：

### 1. 联系方式（第 8-12 行）

```markdown
[![Email](https://img.shields.io/badge/Email-Contact%20Me-24292f?style=flat-square&logo=gmail&logoColor=white)](mailto:你的邮箱)
[![Twitter](https://img.shields.io/badge/Twitter-Follow%20Me-24292f?style=flat-square&logo=twitter&logoColor=white)](https://twitter.com/你的 Twitter 账号)
[![Telegram](https://img.shields.io/badge/Telegram-Message%20Me-24292f?style=flat-square&logo=telegram&logoColor=white)](https://t.me/你的 Telegram 账号)
[![Blog](https://img.shields.io/badge/Blog-Visit-24292f?style=flat-square&logo=medium&logoColor=white)](https://你的博客地址)
```

### 2. 联系方式底部（约 第 200 行）

```markdown
- 📧 **Email**: 你的邮箱
- 💬 **Telegram**: [@你的账号](https://t.me/你的账号)
- 🐦 **Twitter**: [@你的账号](https://twitter.com/你的账号)
- 📝 **Blog**: [你的博客](https://你的博客地址)
- 🔗 **Website**: [个人网站](https://你的网站地址)
```

### 3. 关于我（可选，第 21-25 行）

修改为你当前的真实状态：

```markdown
- 🔭 **Working on**: 你正在做的项目
- 🌱 **Currently learning**: 你正在学习的技术
- 💬 **Ask me about**: 你擅长的领域
- ⚡ **Fun fact**: 你的趣事
```

---

## 📋 修改步骤

```bash
# 1. 克隆仓库（如果还没有）
cd /home/de/works/differs

# 2. 编辑 README.md
vim README.md
# 或使用你喜欢的编辑器：code README.md / nano README.md

# 3. 替换所有占位符：
#    - 你的邮箱
#    - 你的 Twitter 账号
#    - 你的 Telegram 账号
#    - 你的博客地址
#    - 你的网站地址

# 4. 保存并提交
git add README.md
git commit -m "docs: update contact info"
git push origin main

# 5. 刷新 https://github.com/differs 查看效果
```

---

## 🎨 自定义选项

### 修改主题配色

所有统计图表使用 `theme=dark`，你可以改为：

- `default` - 默认亮色
- `dark` - 暗色（当前）
- `github_dark` - GitHub 暗色
- `radical` - 激进
- `merko` - 薄荷绿
- `tokyonight` - 东京之夜

示例：
```markdown
<>&theme=tokyonight
```

### 调整展示项目

在 `Featured Projects` 部分（约 第 85 行），修改为你想展示的项目：

```markdown
| [**仓库名**](https://github.com/用户名/仓库) | [**仓库名**](https://github.com/用户名/仓库) |
```

### 修改技能徽章

在 `Tech Stack` 部分，添加或删除技术：

```markdown
![技术名](https://img.shields.io/badge/-技术名 -颜色？style=for-the-badge&logo=logo 名&logoColor=white&color=颜色)
```

更多徽章：https://shields.io/

---

## 📊 统计图表说明

当前展示：

1. **GitHub Stats** - 综合统计（评论、讨论、合并 PR 等）
2. **Top Languages** - 常用编程语言 TOP 10
3. **Commit Streak** - 提交连续天数
4. **Trophy** - GitHub 成就奖杯
5. **Activity Graph** - 贡献热力图

这些图表会自动更新（延迟约 24 小时）。

---

## 🔗 有用的链接

- [GitHub Profile README 规范](https://docs.github.com/en/account-and-profile/setting-up-and-managing-your-github-profile/customizing-your-profile/managing-your-profile-readme)
- [GitHub Readme Stats](https://github.com/anuraghazra/github-readme-stats)
- [GitHub Profile Trophy](https://github.com/ryo-ma/github-profile-trophy)
- [Activity Graph](https://github.com/Ashutosh00710/github-readme-activity-graph)
- [Shields.io 徽章](https://shields.io/)
- [Capsule Render 横幅](https://github.com/kyechan99/capsule-render)

---

## 📝 版本历史

| 版本 | 日期 | 说明 |
|------|------|------|
| v2.0 | 2026-03-15 | 基于真实项目优化，突出区块链专业身份 |
| v1.0 | 2026-03-15 | 初始版本 |

---

**祝你打造出一个出色的 GitHub 首页！** ✨
