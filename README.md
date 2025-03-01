# quarto-chinese-journal

A [Quarto](https://quarto.org/) template for Chinese journals. Modified from [Egbertm/Latex_ChinesePaper](https://github.com/Egbertm/Latex_ChinesePaper).

## Creating a New Article

To create a new article using this format:

```bash
quarto use template haiiliin/quarto-chinese-journal
```

This will create a new directory with an example document that uses this format.

## Using with an Existing Document

To add this format to an existing document:

```bash
quarto add haiiliin/quarto-chinese-journal
```

Then, add the format to your document options:

```yaml
format:
  chinese-journal-pdf: default
```

## Options

- `twocolumn`: 是否双栏排版，默认为 `true`
- `eauthor`: 英文作者名字和上标
- `eaffiliation`: 英文作者单位
- `eabstract`: 英文摘要
- `ekeywords`: 英文关键词
- `ejournal`: 英文期刊名
- `cjournal`: 中文期刊名
- `eyearmonth`: 英文年月
- `cyearmonth`: 中文年月
- `volume`: 卷号
- `number`: 期号
- `classification`: 中图分类号
- `document-code`: 文献标识码
- `article-number`: 文章编号
- `received-date`: 收稿日期
- `revised-date`: 修回日期
- `funds`: 基金项目详情
- `author-introduction`: 作者简介
- `corresponding-email`: 通讯作者邮箱
- `table-env`: 表格环境，默认为 `figure`
- `table-pos`: 表格位置，默认为 `!htb`

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd), see the [PDF output](template.pdf).
