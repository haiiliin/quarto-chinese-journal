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

- `cauthor`: 中文作者名字和上标
- `caffiliation`: 中文作者单位
- `cabstract`: 中文摘要
- `ckeywords`: 中文关键词
- `ejournal`: 英文期刊名
- `cjournal`: 中文期刊名
- `volume`: 卷号
- `number`: 期号
- `yearmonth`: 英文年月
- `cyearmonth`: 中文年月
- `classification`: 中图分类号
- `document_code`: 文献标识码
- `article_number`: 文章编号
- `received_date`: 收稿日期
- `revised_date`: 修回日期
- `funds`: 基金项目详情
- `author_introduction`: 作者简介

## Example

Here is the source code for a minimal sample document: [template.qmd](template.qmd), see the [PDF output](template.pdf).
