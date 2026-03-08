# 2026 美伊战争信息汇总网站

一个提供美伊战争相关信息的静态网站，包含权威新闻来源链接和背景资料。

## 🌐 在线预览

使用 GitHub Pages 访问：https://guchezw.github.io/us-iran-war-info/

## 📁 文件结构

```
us-iran-war-info/
├── index.html          # 主页面
├── style.css           # 样式表
└── README.md           # 说明文档
```

## 🚀 部署到 GitHub Pages

### 方法 1: 使用 GitHub Actions（推荐）

1. 进入仓库 Settings → Pages
2. Source 选择 "GitHub Actions"
3. 等待自动部署

### 方法 2: 使用 gh-pages 分支

```bash
# 克隆仓库
git clone https://github.com/guchezw/us-iran-war-info.git
cd us-iran-war-info

# 创建 gh-pages 分支
git checkout --orphan gh-pages
git reset --hard

# 复制文件
cp /path/to/index.html .
cp /path/to/style.css .

# 提交
git add .
git commit -m "Deploy to GitHub Pages"
git push -f origin gh-pages
```

## 📋 网站内容

### 核心内容
- **战争概况** - 事件简介、关键事实
- **历史背景** - 1953 年至今的美伊关系历史
- **战争起因** - 核问题、地区影响力、经济制裁、国内抗议
- **详细时间线** - 2026 年 1 月至 3 月的事件发展
- **各方立场** - 美国、以色列、伊朗、国际社会的立场
- **影响分析** - 经济、地缘政治、人道主义影响
- **权威来源** - 新闻媒体、官方渠道、分析机构
- **信息甄别** - 如何识别可靠信息

## 🔗 收录的信息来源

### 国际新闻
- 纽约时报
- 路透社
- CNN
- 今日美国

### 背景资料
- 维基百科
- 大英百科全书

### 官方渠道
- 美国政府信息
- 美国国务院
- 联合国

### 分析机构
- 外交关系委员会
- 布鲁金斯学会

## ⚠️ 免责声明

本网站仅提供信息汇总，不代表任何政治立场。请从多个权威来源获取信息，形成独立判断。

## 📝 更新日志

- **2026-03-08** - 初始版本发布

## 👨‍💻 作者

- GitHub: [@guchezw](https://github.com/guchezw)

## 📄 许可证

MIT License
