# FontCDN - 本地字体CDN托管工具

FontCDN 是一个可以将本地字体文件转换为可托管的CDN链接的工具。这个工具可以帮助你轻松地将本地字体文件部署到GitHub Pages上，使其可以通过CDN方式访问。

## 功能特点

- 支持将本地字体文件转换为CDN链接
- 基于GitHub Pages托管，完全免费
- 简单易用的界面
- 支持多种字体格式

## 如何配置本地字体文件

1. 在项目根目录下创建 `fonts` 文件夹（如果还没有的话）
2. 将你的字体文件（支持 .ttf, .woff, .woff2 等格式）放入 `fonts` 文件夹中
3. 字体文件命名建议使用小写字母，避免使用空格，例如：`myfont.ttf`

## 使用方法

1. 克隆此仓库到本地
2. 将你的字体文件放入 `fonts` 文件夹
3. 提交更改并推送到GitHub
4. 访问 `https://[你的用户名].github.io/fontcdn-gh-pages/` 即可看到你的字体列表

## 字体文件引用方式

配置完成后，你可以通过以下方式引用字体：

```css
@font-face {
    font-family: '你的字体名称';
    src: url('https://[你的用户名].github.io/fontcdn-gh-pages/fonts/你的字体文件名.ttf') format('truetype');
}
```

## 注意事项

- 确保字体文件大小适中，过大的文件可能会影响加载速度
- 建议使用 .woff2 格式，它具有更好的压缩率
- 请确保你拥有字体的使用权限

## 原作者

Thomas Park

* [GitHub](http://github.com/thomaspark)
* [Twitter](http://twitter.com/thomashpark)
* [个人网站](http://thomaspark.co)

## 许可证

本项目采用 MIT 许可证
