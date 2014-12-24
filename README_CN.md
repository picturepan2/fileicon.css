语言: [English Document]

# 介绍

文件类型图标的纯 CSS 版本。可以不用图片来文件图标。（例如：doc, pdf, png, zip 等等）。

查看 [DEMO]

# 使用

```html
<div class="file-icon size-36" data-type="doc"></div>
```

显示为:



## 类型

使用 `data-type` 来定义文件类型，已经定义了一些:

- doc, docx
- xls, xlsx
- ppt, pptx
- pdf
- zip

## 尺寸

使用 `file-icon-xx` 来使用尺寸，支持：
 
- xs  (48x48)
- sm  (96x96)
- md  (128x128)
- lg  (256x256)

## 自定义

如果要定义自己的类型，只需要：

```css
.file-icon[data-type^=custom] {
  background: #38A240;
}
```

# License

Copyright (c) 2014-2015 Picturepan2. MIT Licensed, see [LICENSE] for details.

[DEMO]: https://picturepan2.github.io/fileicon.css
[LICENSE]: https://picturepan2.github.io/fileicon.css/LICENSE
[English Document]: https://github.com/picturepan2/fileicon.css

