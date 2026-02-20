# 更方便地创建 `ComicInfo.xml`

漫画文件档案 `cbz` 或 `cbr` 在内容根目录下使用 `ComicInfo.xml` 文件来描述档案信息。

这是一个用户友好的，更便捷的漫画信息文件编辑工具页面。


## 主要功能目标

以下是主要功能列表：
  + [ ] 支持主要信息标签：`<Title>`, `<Series>`, `<Number>`, `<Publisher>`, `<Editor>`, `<Penciller>`, `<CoverArtist>`, `<Summary>`, `<LanguageISO>`, `<Tags>`, `<AgeRating>` 及 `<Manga>`
  + [ ] 支持 `系列(Series)` 复用，在该系列下的档案将复用 `<Series>`, `<Publisher>`, `<Editor>` 标签  
  + [ ] 支持 `标签(Tag)` 自动分割并填充到 `<Tags>` 标签
  + [ ] 默认为日漫风格，标签 `<Manga>` 预设为 ___YesAndRightToLeft___
  + [ ] 默认为日语漫画，标签 `<LanguageISO>` 预设为 ___jpn___

## 开发

执行以下命令启动开发服务器:

```bash
ng serve
```

服务器启动后，使用浏览器访问 `http://localhost:4200/` 。项目会热重载任何变更的项目资源文件。


## 构建

执行以下命令以构建项目:

```bash
ng build
```

此操作将编译项目，并将构建产物存放在 `dist/` 目录中。默认情况下，生产环境构建会对应用程序进行性能与速度优化。
