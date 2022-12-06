# 有处出错了 整个框架就崩了 我有空再修


# Hexo Theme Shoka Fix

## Fix

1. 修复 Iconfont CDN 链接格式变动导致的无法正常获取图标的BUG且更换图标库
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
 
6. 更换 cdn.jsdelivr.net 为我自己反代并用 Gcore Cdn 加速的节点 jsdone.ramsong.cn
 scripts/helpers/asset.js
 source/js/_app/utils.js

7. 把 Valine 换成更安全的评论系统 Waline

## Usage
