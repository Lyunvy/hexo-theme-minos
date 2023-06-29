由于[原仓库](https://github.com/ppoffice/hexo-theme-minos)归档不再维护，开此仓库自用维护。

参考[原仓库文档](https://github.com/ppoffice/hexo-theme-minos)

使用主题前需安装必要模块：
```npm
npm install lodash cheerio hexo-generator-index-enhanced hexo-renderer-sass-next --save
```
由于采用 `hexo-generator-index-enhanced` 进行 index 页的生成，故需卸载原默认的生成模块 hexo-generator-index ：
```npm
npm uninstall hexo-generator-index --save
```
