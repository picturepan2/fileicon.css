Languages: [中文文档]

# Intro

Pure CSS file icons. Help you show files icon without Image. (eg. doc, pdf, png, zip and so on).

See the [DEMO]

# Usage

```html
<div class="file-icon size-36" data-type="doc"></div>
```

Will display:

![doc](https://cloud.githubusercontent.com/assets/119550/5550524/583be08c-8be2-11e4-99a3-d7e9f24b1db3.jpg)

## Type

Use attribute `data-type` to define the file type, We had already defined some file type styles, includes:

- doc, docx.
- xls, xlsx
- ppt, pptx
- pdf
- zip

## Size

Use class `file-icon-xx` for size define, We support some size below:
 
- xs  (48x48)
- sm  (96x96)
- md  (128x128)
- lg  (256x256)

## Custom

Want define your file types, just set below:

```css
.file-icon[data-type^=custom] {
  background: #38A240;
}
```

# License

Copyright (c) 2014-2015 Picturepan2. MIT Licensed, see [LICENSE] for details.

[DEMO]: https://picturepan2.github.io/fileicon.css
[LICENSE]: https://picturepan2.github.io/fileicon.css/LICENSE
[中文文档]: https://github.com/picturepan2/fileicon.css/blob/master/README_CN.md