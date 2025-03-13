# JSON 转 Excel 和 Excel 转 JSON 工具

这是一个简单的网页应用程序，允许用户将 JSON 数据导出为 Excel 文件，并将 Excel 文件导入并转换为 JSON 数据。

## 功能

- **JSON 转 Excel**: 用户可以输入 JSON 数据，并将其导出为 Excel 文件。
- **Excel 转 JSON**: 用户可以选择一个 Excel 文件，并将其内容转换为 JSON 格式，显示在文本区域中。

## 使用说明

1. **JSON 转 Excel**
   - 在 "输入 JSON 数据" 文本框中输入有效的 JSON 数据。
   - 点击 "导出为 Excel" 按钮，生成并下载 Excel 文件。

2. **Excel 转 JSON**
   - 点击 "选择 Excel 文件" 按钮，选择一个 `.xlsx` 格式的 Excel 文件。
   - 点击 "转 JSON" 按钮，导入 Excel 文件并将其内容转换为 JSON 数据，显示在下方的文本区域中。

## 技术栈

- HTML
- CSS
- JavaScript
- [xlsx.js](https://github.com/SheetJS/sheetjs) - 用于处理 Excel 文件的库

## 安装与运行

1. 将项目克隆到本地

2. 在浏览器中打开 `jsonToExcel.html` 文件。

## 注意事项

- 确保输入的 JSON 数据格式正确，否则会提示无效的 JSON 数据。
- 仅支持 `.xlsx` 格式的 Excel 文件。

