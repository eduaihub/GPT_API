### HTM快速入门

#### 1. HTML文档结构
- `<!DOCTYPE html>`: 声明文档类型，告诉浏览器这是HTML5文档。
- `<html>`: HTML文档的根元素。
  - `lang="en"`: 设置文档的语言（这里是英语，对于中文可以改为`lang="zh"`）。

#### 2. 头部（Head）
- `<head>`: 包含了文档的元数据。
  - `<meta charset="UTF-8">`: 设置字符编码为UTF-8。
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: 为移动设备优化显示。
  - `<title>`: 定义文档的标题。
  - `<link rel="stylesheet" href="styles.css">`: 链接外部CSS文件。href="styles.css": 指定样式表文件的路径。这里假设文件名为“styles.css”，存放在与HTML文件相同的目录中。

#### 3. 主体（Body）
- `<body>`: 包含了可见的页面内容。
  - 容器元素：如`<div>`, `<section>`，用于组织和布局内容。
    - `<div class="container">`: 创建一个类为“container”的div容器。
    - `<section class="assistant-container">`: 创建一个类为“assistant-container”的section。
  - 文本元素：如`<h1>`, `<h2>`, `<p>`等，用于展示标题和段落。
    - `<h1>`, `<h2>`: 分别表示一级和二级标题。
  - 交互元素：
    - `<textarea>`: 文本输入区域。
    - `<button>`: 按钮，可用于提交表单或触发事件。
    - `onclick="fetchData()"`: 当按钮被点击时，执行`fetchData()`函数。

#### 4. 引入JavaScript
- `<script src="app.js"></script>`: 引入外部JavaScript文件。src="app.js":指定javascript文件的路径。这里假设文件名为“app.js”，存放在与HTML文件相同的目录中。

