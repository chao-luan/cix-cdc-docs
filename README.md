# 此芯文档中心规划

本仓库用于放置此芯文档中心规划的 Markdown 文档，可直接上传 GitHub 后接入 Read the Docs。

当前文档结构已按仓库实际文件对齐：

```text
README.md
mkdocs.yml
.readthedocs.yaml
requirements.txt
docs/
├── index.md
├── assets/
├── 芯片简介/
├── 开发平台/
├── 固件开发/
├── 操作系统/
├── 软件应用设计/
├── 硬件参考设计/
└── 下载资料汇总/
```

## 本地预览

```bash
pip install -r requirements.txt
mkdocs serve
```

## 构建

```bash
mkdocs build
```
