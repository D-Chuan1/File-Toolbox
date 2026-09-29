# 文件工具箱 · File Toolbox

轻量级本地文件管理工具箱。基于 Python + pywebview 构建，界面简洁，操作简单，本地运行，不联网、不上传任何文件。

A lightweight local file management toolbox. Built with Python + pywebview. Clean UI, simple operation, runs entirely offline — no network access, no file uploads.

---

## 功能 · Features

| # | 功能 | Feature | 说明 |
|---|------|---------|------|
| 1 | 解除文件占用 | Unlock Files | 查找并结束占用文件的进程，解锁后可正常删除或移动 |
| 2 | 粉碎文件 | Shred Files | 按强度覆写后彻底销毁，不进回收站，无法恢复 |
| 3 | 扫描病毒 | Virus Scan | 自动适配本地杀软，支持命令行自动执行或唤起界面 |
| 4 | 批量重命名 | Batch Rename | 按规则批量修改文件名，执行前可预览 |
| 5 | 重复文件查找 | Find Duplicates | 按 MD5 识别内容完全相同的文件，分组展示 |
| 6 | 批量分类归档 | Auto Organize | 按扩展名 / 修改日期自动分类归档 |
| 7 | 文件搜索 | File Search | 文件名检索 + 文件内容检索，三分类展示结果 |
| 8 | 大文件清理 | Large File Cleaner | 扫描大文件，查用途 / 定位，勾选后二次确认删除 |
| 9 | 批量属性修改 | Batch Attributes | 批量设置只读、隐藏属性或统一修改时间戳 |
| 10 | 文件校验 | File Verify | 批量计算 MD5 / SHA-256，可对比官方校验值 |

## 技术栈 · Tech Stack

- Python 3.14
- pywebview（使用系统 WebView 渲染 HTML 界面，轻量无捆绑）

## 目录结构 · Structure

```
源码/
├── ui/          # 前端界面（HTML / CSS / JS）
├── core/        # 核心功能逻辑
├── main.py      # 程序入口
├── LICENSE      # 使用许可
└── README.md    # 本文件
```

## 构建 · Build

```
pip install pywebview psutil
pyinstaller -F -w main.py
```

## 许可 · License

自定义许可：**可免费使用（个人非商业用途）；未经作者书面许可，禁止复制、修改、合并、发布、分发、再许可、出售及商用。** 详见 [LICENSE](LICENSE)。

Custom License: **Free to use for personal, non-commercial purposes. Copying, modification, merging, publishing, distribution, sublicensing, selling, and commercial use are strictly prohibited without the author's written permission.** See [LICENSE](LICENSE).

## 联系 · Contact

- GitHub: https://github.com/D-Chuan1/File-Toolbox
- 网站 · Website: https://d-chuan-toolbox.pages.dev/
- 邮箱 · Email: 1710079261@qq.com
- QQ 群 · QQ Group: 1075049529

---

© 2026 D_Chuan · 保留所有权利 · All rights reserved
