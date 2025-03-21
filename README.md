# 域名展示系统

![](/1742609167462.png)

这是一个简单而强大的域名展示系统，用于管理和展示域名集合。系统提供了直观的用户界面！

## 功能特点

- **域名展示**：以卡片形式展示域名信息，包括域名名称、TLD、提供商和到期日期
- **响应式设计**：适配各种屏幕尺寸，提供良好的移动端体验
- **购买功能**：提供域名购买入口

## 如何安装

- vercel部署

- 构建命令 
```
bun run build
```

- 安装命令
```
bun install
```

## 域名内容信息

- 域名信息存储在 `data/domains.json` 中，你可以根据需要修改和添加域名信息。

- 出售域名信息存储在 `data/sold-domains.json` 中，你可以根据需要修改和添加域名信息。

- 友情链接信息存储在 `data/friendly-links.json` 中，你可以根据需要修改和添加域名信息。

## favicon图标
- 图标存储在 `layout.tsx` 中，你可以根据需要修改和添加修改。

## 域名商家的SVG代码图标
- 图标存储在 `registrar-icon.tsx` 中，你可以根据需要修改和添加修改。
