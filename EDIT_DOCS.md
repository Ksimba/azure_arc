# Edit DOCS

Please reference **azure_arc_sqlsrv_jumbstart/docs**

## Directory structure should be follow overview(READEM) structure

Order will be clarify with "weight" parameter.

```
azure_arc_sqlsrv_jumbstart/docs
  - azure
  - aws
  - gcp
  - vmware
```

##  Create Folder & Markdown File 

```
[name]/_index.md
```

## Frontmatter - Markdown Header Part

```
-------
title: <Page Title>
linkTitle: <Sidebar Menu Title>
weight: <Order for Same Level folder>
description: >-
---
```

## Screenshot images should be in same level with markdownfile folder.

```
/[name]/
  _index.md
  01.png
  02.png
  03.png
  ....

```