# Hexo Theme Shoka Fix

## Fix

1. 修复 Iconfont CDN 链接格式变动导致的无法正常获取图标的BUG
 source/css/_common/scaffolding/base.styl
 
2. 修正错误的用词
 languages/zh-TW.yml

3. 使用 Alicdn 加载 Polyfill
 layout/_partials/layout.njk

4. 添加对 Google analytics 4 的支持
 layout/_partials/layout.njk
 layout/_partials/third-party/google-analytics.njk
 layout/_partials/third-party/google-tag-body.njk
 layout/_partials/third-party/google-tag-head.njk
 
5. 默认 Iconfont图标库 替换为 1832207_15qncu9y48e
 _config.yml
 
6. 
## Usage
