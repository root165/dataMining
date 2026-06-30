# 数据挖掘知识库

《数据挖掘原理与应用》（葛东旭）课程复习资料库，包含各章节重点总结、章节测试题、模拟真题及辅助脚本工具。

## 目录结构

```
数据挖掘知识库/
├── 第1-8章考察重点.md    # 各章节知识点总结
├── 第1-8章节测试.html     # 各章节选择题测试
├── 数据挖掘模拟真题1.html  # 模拟试卷一
├── 数据挖掘期末模拟真题2.html # 模拟试卷二
├── 数据挖掘期末复习大纲.pdf  # 官方复习大纲
├── 数据挖掘原理与应用 (葛东旭).pdf  # 教材 PDF
├── 复习大纲.docx           # 复习大纲 Word 版
├── 期末复习输出说明.md      # 复习输出说明文档
├── *.jpg                   # OCR 提取的教材截图
│
├── 辅助脚本
│   ├── expand_chapter_tests.py     # 扩展章节测试题
│   ├── generate_chapter_review.py  # 生成章节复习内容
│   ├── regenerate_markdown_only.py # 仅重新生成 Markdown
│   ├── extract_windows_ocr.ps1     # Windows OCR 提取脚本
│   ├── check_tests.js              # 测试检查工具
```

## 内容来源

- 教材：**《数据挖掘原理与应用》**（葛东旭 著）
- PDF 为教材电子版，复习大纲为课程官方发布

## 使用方式

直接用浏览器打开 `*测试*.html` 或 `*真题*.html` 文件即可自测。Markdown 文件可用任何文本编辑器或 Obsidian 查看。

## 脚本说明

| 脚本 | 用途 |
|------|------|
| `generate_chapter_review.py` | 读取教材 PDF 指定章节并生成重点总结 |
| `expand_chapter_tests.py` | 基于章节内容扩展生成更多测试题 |
| `regenerate_markdown_only.py` | 仅重新生成 Markdown 格式的输出 |
| `extract_windows_ocr.ps1` | 调用 Windows OCR API 从 PDF 截图提取文字 |
| `check_tests.js` | 校验测试题格式和答案正确性 |
