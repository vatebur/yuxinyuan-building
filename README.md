# 裕欣源建材 — 官方网站

裕欣源建材是福州本地的建材供应商家，经营电线电缆、管道管件、卫浴五金等建材产品。

**网站地址**: <https://yxyjc.cn/>

## 页面说明

- `index.html` — 首页（轮播、产品分类、供应能力、特色建材、客户评价、联系方式）
- `cable-details.html` — 电线电缆产品详情页
- `pipe-details.html` — 管道管件产品详情页
- `404.html` — 自定义 404 错误页

## 目录结构

```
assets/
  css/site.css        — 全站样式
  js/site.js          — 移动端菜单、滚动动画、图片画廊、返回顶部
  vendor/             — 第三方库（Font Awesome）
  images/             — 产品图片、品牌图片等
```

## 技术栈

- 纯静态 HTML / CSS / JS，无构建工具
- Font Awesome 图标
- Google Fonts（Manrope、Noto Sans SC、Noto Serif SC）
- Schema.org 结构化数据（LocalBusiness）

## 本地开发

```bash
python -m http.server 8000
```

浏览器打开 `http://localhost:8000` 即可预览。
