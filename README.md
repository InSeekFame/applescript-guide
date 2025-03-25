<!-- 在 README.md 中添加 -->
# AppleScript 完全开发指南

[![Documentation](https://img.shields.io/badge/PDF-Generate-blue)](https://github.com/YOURNAME/applescript-guide/actions)
[![License](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

> 实时更新版本：通过 Issues 提交内容请求

## 目录结构
```plaintext
.
├── chapters/          # 按章节组织的文档
│   ├── 01-Introduction.md
│   ├── 02-Syntax.md
│   └── ...
├── examples/          # 可运行的脚本案例
│   ├── file-management
│   │   ├── bulk-rename.applescript
│   │   └── image-convert.applescript
│   └── system-automation
├── TOC.md             # 自动生成的目录
└── build.sh           # 文档编译脚本