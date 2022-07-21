# html2blog.js
爬取一个 HTML 页面，自动生成 Hexo 等静态博客软件可读的文件格式并转换图片为 webp

## 使用
```bash
node html2blog <爬取的链接> <生成的文件> <图片文件的前缀>
```
生成的文件可以在 output/ 看到。

## 关于 图片文件前缀
程序会自动改写 HTML 内 `<img>` 标签的 `src` 为 `/<前缀>/<前缀>-<序号>.webp` ,并遵循此路径储存。

## LICENSE
MIT。