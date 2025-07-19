# 🌐 Whois 域名查询工具网站

一个现代化、响应式的 Whois 域名信息查询网站，通过 API 接口获取并展示域名注册信息。

## ✨ 功能特性

- ✅ 简洁美观的现代化 UI 设计
- ⚡ 实时 Whois 信息查询
- 📱 响应式布局，适配各种设备
- 🔍 支持查看原始 Whois 数据
- 🛡️ 内置查询频率限制 (2秒/次)

## 🛠️ 技术栈

### 前端技术
- **HTML5** & **CSS3** - 网页结构与样式
- **JavaScript** - 交互逻辑
- **Bootstrap 5.3** - UI 框架
- **Bootstrap Icons** - 图标库

### 第三方服务
- **WhoisCX API** - 域名查询服务https://api.whoiscx.com/
- **jsDelivr** - 此网页所需前端库已经本地化

## 🚀 快速使用

1. 直接访问部署好的网站https://whois.tiking.top 
2. 在输入框中输入要查询的域名 (如 `example.com`)
3. 点击"查询"按钮获取信息
4. 若要快速查询在URL后面加上/?domain=[要查询的域名]

### 或自行部署：

```bash
git clone https://github.com/Tiking-owo/whois.git
cd whois
# 将文件放入您的 Web 服务器
