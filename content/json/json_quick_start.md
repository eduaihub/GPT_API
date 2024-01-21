JSON（JavaScript Object Notation）是一种轻量级的数据交换格式，易于人阅读和编写，同时也易于机器解析和生成。它基于JavaScript语言标准的一个子集，但是JSON是完全独立于语言的文本格式，代码为了清晰，我将使用JavaScript/Python风格的示例。

### 基础结构

JSON数据由两种结构组成：

1. **对象（Object）**：一组无序的“键/值”对（key/value pairs）。它在JavaScript中以大括号 `{}` 表示。
2. **数组（Array）**：有序的值集合。它在JavaScript中以方括号 `[]` 表示。

### 数据类型

JSON支持以下数据类型：

- 字符串（String）
- 数字（Number）
- 对象（Object）
- 数组（Array）
- 布尔值（Boolean，即 `true` 或 `false`）
- `null`

### 语法规则

1. 数据在名称/值对中：`"键": "值"`
2. 数据由逗号分隔。
3. 大括号保存对象 `{}`。
4. 方括号保存数组 `[]`。

### 示例

#### 简单对象

```json
{
  "name": "张三",
  "age": 30,
  "isStudent": false
}
```

#### 嵌套对象

```json
{
  "name": "李四",
  "address": {
    "street": "中山路",
    "city": "北京"
  },
  "hobbies": ["读书", "游泳"]
}
```

#### 数组

```json
[
  {
    "name": "王五",
    "age": 28
  },
  {
    "name": "赵六",
    "age": 35
  }
]
```

### 使用场景

JSON常用于以下场景：

- 网络数据传输：如Web API和Web服务之间的数据交换。
- 配置文件：由于其易读性，它常用于应用程序的配置。
- 数据存储：一些数据库（如MongoDB）使用JSON或类似的格式存储数据。

### 注意事项

- 所有的键必须用双引号包围。
- JSON文件和字符串中不能包含注释。
