# 布局和盒子模型
**弹性盒子模型（Flexbox）**：`display: flex;` 将元素设置为弹性容器。这对于创建灵活的布局非常有用。相关属性包括 `justify-content` 和 `align-items`，用于控制子元素的对齐方式。

**盒子尺寸**：如 `width` 和 `height` 属性，用于设置元素的宽度和高度。例如，`.history-content` 设置了 `height: 550px;`。

**内边距和外边距（Padding & Margin）**：`padding` 属性定义元素内部的空间，而 `margin` 定义元素外部的空间。例如，在 `body` 标签中，`padding: 20px;` 创建了20像素的内边距。

# 文本和字体样式
**字体样式**：`font-family` 属性定义文本的字体。例如，`body` 使用了 `'Arial', sans-serif;`。

**字体大小**：如 `font-size` 属性，用于设置文本的大小。在此示例中，`#userInput` 和 `#sendButton` 使用了 `font-size: 1em;`。

# 颜色和背景
**背景颜色**：`background-color` 用于设置元素的背景色。例如，`.assistant-container` 的背景色为 `#fff`（白色）。

**文本颜色**：`color` 属性用于设置文本颜色。例如，在 `h1` 中，设置为 `color: #333;`（深灰色）。

# 边框和圆角
**边框**：`border` 属性定义元素的边框样式、宽度和颜色。例如，`.question-history` 使用了 `border: 1px solid #ddd;`。

**圆角**：`border-radius` 用于创建圆角边框。例如，`.response` 的 `border-radius: 5px;` 则让边框角变圆。

# 阴影和视觉效果
**盒阴影**：`box-shadow` 添加元素的阴影，增加深度感。如 `.container` 中的 `box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);`。

# 滚动条和溢出控制
**溢出控制**：`overflow-x` 和 `overflow-y` 控制水平和垂直滚动条的显示。例如，`.history-content` 中的 `overflow-y: auto;` 允许垂直滚动。

**自定义滚动条**：`::-webkit-scrollbar` 及相关伪元素允许自定义滚动条的样式。

# 动画和转换
**关键帧动画**：使用 `@keyframes` 创建动画，如 `.circle` 的旋转动画。

**变换属性**：`transform` 用于应用旋转等效果。在动画 `rotate` 中使用了 `transform: rotate(0deg);` 到 `transform: rotate(360deg);`。
