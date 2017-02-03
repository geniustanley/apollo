## Features
* 文字排版參考 [medium.com](https://medium.com/)
* 引入 medium like zoom.js [demo](https://fat.github.io/zoom.js/)

## Installation guide

``` bash
hexo init Blog 
cd Blog 
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git clone https://github.com/geniustanley/hexo-theme-achilles themes/achilles
```

## Setting

修改 `_config.yml` 的 `theme` 配置项为 `achilles`:

```yaml
theme: achilles

# 在归档页面显示所有文章
# 需要上面安装的 hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

## Customize css

本專案採用 gulp

``` bash
cd themes/achilles
yarn
yarn run sass
```

## Update

``` bash
cd themes/achilles
git pull
```

## License

MIT
