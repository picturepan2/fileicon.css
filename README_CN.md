语言: [English Document]

# 介绍

文件类型图标的纯 CSS 版本。可以不用图片来创建文件图标。（例如：doc, pdf, png, zip 等等）。

查看 [DEMO]

# 使用

```html
<div class="file-icon file-icon-xl" data-type="doc"></div>
```

显示为:

![doc](https://cloud.githubusercontent.com/assets/119550/5550524/583be08c-8be2-11e4-99a3-d7e9f24b1db3.jpg)

## 类型

使用 `data-type` 来定义文件类型，已经定义了一些:

- doc, docx
- xls, xlsx
- ppt, pptx
- pdf
- zip

## 尺寸

使用 `file-icon-xx` 来使用尺寸，支持：
 
- xs  (12x16)
- sm  (18x24)
- 默认 (24x32)
- lg  (48x64)
- xl  (120x160)

## 自定义

如果要定义自己的类型，只需要：

```css
.file-icon[data-type=custom] {
  background: #38A240;
}
```

# 谁在用

- PUBU.im - [https://pubu.im](https://pubu.im)

# License

Copyright (c) 2014-2015 Picturepan2. MIT Licensed, see [LICENSE] for details.

[DEMO]: https://picturepan2.github.io/fileicon.css
[LICENSE]: https://picturepan2.github.io/fileicon.css/LICENSE
[English Document]: https://github.com/picturepan2/fileicon.css

