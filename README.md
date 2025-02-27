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
- `document_code`: 文献标识码
- `article_number`: 文章编号
- `received_date`: 收稿日期
- `revised_date`: 修回日期
- `funds`: 基金项目详情
- `author_introduction`: 作者简介
- `corresponding_email`: 通讯作者邮箱

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd), see the [PDF output](template.pdf).
