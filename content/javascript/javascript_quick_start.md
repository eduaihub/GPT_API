
#### 变量和常量
- **变量声明** (`const`): 使用`const`声明常量，如`const API_KEY = "sk-ou...OXo";`。常量一旦赋值后不可更改。
  
### 2. DOM 操作

#### 获取和设置元素
- **获取元素** (`document.getElementById`): 使用此方法获取页面元素，如`document.getElementById('sendButton')`。
- **设置元素内容** (`innerHTML`): 使用`innerHTML`来改变元素的HTML内容，如`loadingAnimation.innerHTML = '<div class="circle"></div>';`。

#### 修改元素属性
- **禁用和启用按钮** (`disabled`): 通过设置`disabled`属性来禁用或启用按钮，如`sendButton.disabled = true;`。
- **添加和移除类** (`classList.add`, `classList.remove`): 使用`classList.add`和`classList.remove`来添加或移除CSS类，如`loadingAnimation.classList.add('hidden');`。

### 3. 异步编程和网络请求

#### 异步函数 (`async` 和 `await`)
- **异步函数定义** (`async function`): 使用`async`关键字定义异步函数，如`async function fetchData() {...}`。
- **等待异步操作** (`await`): 在异步函数中使用`await`来等待Promise的解决，如`const data = await response.json();`。

#### 网络请求 (`fetch`)
- **发起网络请求**: 使用`fetch`发起网络请求，如`fetch("https://api.openai.com/v1/chat/completions", {...})`。
- **配置请求**: 设置请求的方法、头部和主体，如`method: "POST"`, `headers: {...}`, 和 `body: JSON.stringify({...})`。

### 4. 异常处理

#### `try...catch...finally`
- **错误处理**: 使用`try...catch`结构来捕获和处理异常，如在`try {...}`块中执行网络请求，在`catch (error) {...}`块中处理错误。
- **始终执行的代码**: 使用`finally`块来执行无论是否发生错误都需要执行的代码，如`finally {...}`。

### 5. JSON 处理

#### 解析JSON
- **解析响应数据**: 使用`await response.json();`将响应数据解析为JSON对象。

