# JavaScript Fundamental Interview Knowledge Points (JavaScript 基础面试知识点)

## 1. JavaScript Data Types (JavaScript 数据类型)
**English**: JavaScript has 8 data types: String, Number, BigInt, Boolean, undefined, null, Symbol, and Object. The first 7 are primitive types, and Object is a reference type.

**中文**: JavaScript 有 8 种数据类型：String（字符串）、Number（数值）、BigInt（大整数）、Boolean（布尔值）、undefined（未定义）、null（空值）、Symbol（符号）和 Object（对象）。前 7 种是基本类型，Object 是引用类型。

## 2. Hoisting (变量提升)
**English**: Hoisting is JavaScript's default behavior of moving declarations to the top of the current scope. Variables defined with `var` are hoisted and initialized with `undefined`, while `let` and `const` are hoisted but not initialized.

**中文**: 变量提升是 JavaScript 的默认行为，它将声明移至当前作用域的顶部。用 `var` 定义的变量会被提升并初始化为 `undefined`，而 `let` 和 `const` 虽然被提升但不会被初始化。

## 3. Closures (闭包)
**English**: A closure is the combination of a function bundled together with references to its surrounding state. It gives you access to an outer function's scope from an inner function.

**中文**: 闭包是一个函数及其捆绑的周围环境状态的组合。它允许内部函数访问外部函数的作用域。

## 4. Scope (作用域)
**English**: Scope determines the accessibility of variables. JavaScript has global scope, function scope, and block scope (introduced with ES6's `let` and `const`).

**中文**: 作用域决定了变量的可访问性。JavaScript 有全局作用域、函数作用域和块级作用域（通过 ES6 的 `let` 和 `const` 引入）。

## 5. `this` Keyword (this 关键字)
**English**: The value of `this` depends on how a function is called. In a method, `this` refers to the owner object. Alone, it refers to the global object. In a function, it refers to the global object. In strict mode, it's undefined. In an event, it refers to the element that received the event.

**中文**: `this` 的值取决于函数的调用方式。在方法中，`this` 指向拥有者对象。单独使用时，指向全局对象。在函数中，指向全局对象。在严格模式下，是 undefined。在事件中，指向接收事件的元素。

## 6. Prototypal Inheritance (原型继承)
**English**: JavaScript objects have a prototype property which is a reference to another object. When a property is accessed on an object and if it's not found, JavaScript looks for it in the prototype chain.

**中文**: JavaScript 对象有一个原型属性，它是对另一个对象的引用。当访问对象的属性而找不到时，JavaScript 会在原型链中查找。

## 7. Event Loop (事件循环)
**English**: The event loop is a mechanism that allows JavaScript to perform non-blocking operations despite being single-threaded. It handles asynchronous callbacks after the main thread has finished processing.

**中文**: 事件循环是一种机制，尽管 JavaScript 是单线程的，但它允许执行非阻塞操作。它在主线程完成处理后处理异步回调。

## 8. Promise (Promise 对象)
**English**: A Promise is an object representing the eventual completion or failure of an asynchronous operation. It has states: pending, fulfilled, and rejected.

**中文**: Promise 是一个表示异步操作最终完成或失败的对象。它有三种状态：等待（pending）、成功（fulfilled）和拒绝（rejected）。

## 9. Async/Await (异步/等待)
**English**: Async/await is syntactic sugar built on top of Promises, making asynchronous code look and behave more like synchronous code.

**中文**: Async/await 是建立在 Promise 之上的语法糖，使异步代码看起来和表现得更像同步代码。

## 10. Execution Context (执行上下文)
**English**: The execution context is an abstract concept that holds information about the environment where the current code is being executed.

**中文**: 执行上下文是一个抽象的概念，它包含了当前代码执行环境的信息。

## 11. Call Stack (调用栈)
**English**: The call stack is a mechanism for the JavaScript interpreter to keep track of function calls.

**中文**: 调用栈是 JavaScript 解释器用来跟踪函数调用的机制。

## 12. Memory Leaks (内存泄漏)
**English**: Memory leaks occur when a program incorrectly manages memory allocations, causing the application to consume increasing amounts of memory over time.

**中文**: 内存泄漏发生在程序错误地管理内存分配时，导致应用程序随着时间的推移消耗越来越多的内存。

## 13. `let`, `const`, and `var` Differences (let, const 和 var 的区别)
**English**: `var` has function scope, is hoisted, and can be redeclared. `let` and `const` have block scope, are hoisted without initialization, and cannot be redeclared. `const` cannot be reassigned.

**中文**: `var` 是函数作用域，会被提升，并且可以重新声明。`let` 和 `const` 是块级作用域，提升但不初始化，不能重新声明。`const` 不能重新赋值。

## 14. Arrow Functions (箭头函数)
**English**: Arrow functions have a shorter syntax and inherit `this` from the parent scope. They don't have their own `this` context, `arguments`, `super`, or `new.target`.

**中文**: 箭头函数有更简短的语法，并从父级作用域继承 `this`。它们没有自己的 `this` 上下文、`arguments`、`super` 或 `new.target`。

## 15. Temporal Dead Zone (TDZ) (暂时性死区)
**English**: The TDZ is the time between entering a scope where a variable is declared with `let` or `const` and the actual declaration being executed.

**中文**: 暂时性死区是指进入一个作用域，变量已经用 `let` 或 `const` 声明但还未执行到该声明语句这段时间。

## 16. JavaScript Modules (JavaScript 模块)
**English**: JavaScript modules are a way to organize code into separate files. They use `import` and `export` statements to share functionality.

**中文**: JavaScript 模块是一种将代码组织到单独文件中的方式。它们使用 `import` 和 `export` 语句来共享功能。

## 17. DOM Manipulation (DOM 操作)
**English**: DOM manipulation involves using JavaScript to add, remove, or modify elements on a webpage.

**中文**: DOM 操作涉及使用 JavaScript 添加、删除或修改网页上的元素。

## 18. Event Delegation (事件委托)
**English**: Event delegation is a technique of adding event listeners to a parent element instead of adding them to multiple child elements.

**中文**: 事件委托是一种将事件监听器添加到父元素而不是添加到多个子元素的技术。

## 19. Web Storage (Web 存储)
**English**: Web Storage (localStorage and sessionStorage) allows data to be stored in the browser. localStorage persists even after closing the browser, while sessionStorage is cleared after the session ends.

**中文**: Web 存储（localStorage 和 sessionStorage）允许在浏览器中存储数据。localStorage 在关闭浏览器后仍然存在，而 sessionStorage 在会话结束后被清除。

## 20. JSON (JSON)
**English**: JSON (JavaScript Object Notation) is a lightweight data interchange format used to exchange data between server and client.

**中文**: JSON（JavaScript 对象表示法）是一种轻量级数据交换格式，用于在服务器和客户端之间交换数据。

## 21. AJAX (AJAX)
**English**: AJAX (Asynchronous JavaScript and XML) allows web pages to be updated asynchronously by exchanging data with a web server behind the scenes.

**中文**: AJAX（异步 JavaScript 和 XML）允许网页通过在后台与 Web 服务器交换数据来异步更新。

## 22. Fetch API (Fetch API)
**English**: The Fetch API provides an interface for fetching resources. It returns a Promise that resolves to the Response to that request.

**中文**: Fetch API 提供了一个用于获取资源的接口。它返回一个解析为该请求的响应的 Promise。

## 23. Cross-Origin Resource Sharing (CORS) (跨源资源共享)
**English**: CORS is a mechanism that allows restricted resources on a web page to be requested from another domain outside the domain from which the resource originated.

**中文**: CORS 是一种机制，允许网页请求不同于资源所在域的其他域的受限资源。

## 24. ES6 Features (ES6 特性)
**English**: ES6 introduced features like arrow functions, let/const, template literals, destructuring, default parameters, rest/spread operators, classes, and modules.

**中文**: ES6 引入了箭头函数、let/const、模板字面量、解构、默认参数、rest/spread 运算符、类和模块等特性。

## 25. Map and Set (Map 和 Set)
**English**: Map is a collection of keyed data items, and Set is a collection of unique values.

**中文**: Map 是键值对的集合，Set 是唯一值的集合。

## 26. WeakMap and WeakSet (WeakMap 和 WeakSet)
**English**: WeakMap and WeakSet are collections that don't prevent garbage collection of their keys or values.

**中文**: WeakMap 和 WeakSet 是不阻止其键或值被垃圾回收的集合。

## 27. Generator Functions (生成器函数)
**English**: Generator functions return a Generator object. They can be paused and resumed, allowing other code to run during the pauses.

**中文**: 生成器函数返回一个 Generator 对象。它们可以暂停和恢复，允许在暂停期间运行其他代码。

## 28. Iterators and Iterables (迭代器和可迭代对象)
**English**: Iterators are objects that define a sequence and potentially a return value. Iterables are objects that implement the iterable protocol.

**中文**: 迭代器是定义序列和潜在返回值的对象。可迭代对象是实现可迭代协议的对象。

## 29. Regular Expressions (正则表达式)
**English**: Regular expressions are patterns used to match character combinations in strings.

**中文**: 正则表达式是用于匹配字符串中字符组合的模式。

## 30. Error Handling (错误处理)
**English**: JavaScript provides try, catch, and finally blocks to handle exceptions. Custom errors can be created with the Error constructor.

**中文**: JavaScript 提供 try、catch 和 finally 块来处理异常。可以使用 Error 构造函数创建自定义错误。

## 31. setTimeout and setInterval (setTimeout 和 setInterval)
**English**: setTimeout executes a function once after a specified delay. setInterval executes a function repeatedly at specified intervals.

**中文**: setTimeout 在指定延迟后执行一次函数。setInterval 以指定的间隔重复执行函数。

## 32. requestAnimationFrame (requestAnimationFrame)
**English**: requestAnimationFrame tells the browser to perform an animation before the next repaint, providing smoother animations than setTimeout.

**中文**: requestAnimationFrame 告诉浏览器在下一次重绘之前执行动画，比 setTimeout 提供更平滑的动画。

## 33. Callback Functions (回调函数)
**English**: A callback function is a function passed into another function as an argument to be executed later.

**中文**: 回调函数是一个作为参数传递给另一个函数并在稍后执行的函数。

## 34. Callback Hell and Solutions (回调地狱及解决方案)
**English**: Callback hell refers to nested callbacks that make code hard to read. Solutions include using Promises, async/await, and named functions.

**中文**: 回调地狱指的是嵌套回调使代码难以阅读。解决方案包括使用 Promise、async/await 和命名函数。

## 35. Immediately Invoked Function Expressions (IIFE) (立即调用函数表达式)
**English**: IIFE is a function that runs as soon as it is defined, often used to create private scope and avoid polluting the global namespace.

**中文**: IIFE 是定义后立即运行的函数，通常用于创建私有作用域和避免污染全局命名空间。

## 36. Debounce and Throttle (防抖和节流)
**English**: Debounce delays a function execution until after a period of inactivity. Throttle limits how often a function can be called in a period.

**中文**: 防抖延迟函数执行，直到一段不活动时间后。节流限制一段时间内函数可以被调用的频率。

## 37. Pure Functions (纯函数)
**English**: A pure function always returns the same result given the same arguments and has no side effects.

**中文**: 纯函数在给定相同参数时总是返回相同的结果，并且没有副作用。

## 38. Higher-Order Functions (高阶函数)
**English**: A higher-order function is a function that takes a function as an argument or returns a function.

**中文**: 高阶函数是接受函数作为参数或返回函数的函数。

## 39. Function Currying (函数柯里化)
**English**: Currying transforms a function with multiple arguments into a sequence of functions, each with a single argument.

**中文**: 柯里化将具有多个参数的函数转换为一系列函数，每个函数只有一个参数。

## 40. Memoization (记忆化)
**English**: Memoization is an optimization technique that stores the results of expensive function calls and returns the cached result when the same inputs occur again.

**中文**: 记忆化是一种优化技术，它存储昂贵函数调用的结果，并在再次发生相同输入时返回缓存的结果。

## 41. Object.create vs Constructor Functions (Object.create 与构造函数)
**English**: Object.create creates an object with a specified prototype object. Constructor functions create objects with the 'new' keyword and set the prototype through the constructor's prototype property.

**中文**: Object.create 创建具有指定原型对象的对象。构造函数使用 'new' 关键字创建对象，并通过构造函数的原型属性设置原型。

## 42. Function Binding (函数绑定)
**English**: Function binding creates a new function with a specified 'this' value, commonly done with the bind() method.

**中文**: 函数绑定创建一个具有指定 'this' 值的新函数，通常使用 bind() 方法完成。

## 43. Event Bubbling and Capturing (事件冒泡和捕获)
**English**: Event bubbling is the process where an event triggers on the innermost element and then bubbles up to ancestors. Event capturing is the opposite, from ancestors to target.

**中文**: 事件冒泡是事件从最内层元素触发然后冒泡到祖先的过程。事件捕获与之相反，从祖先到目标。

## 44. Object.defineProperty (Object.defineProperty)
**English**: Object.defineProperty defines a new property directly on an object, or modifies an existing property, and returns the object.

**中文**: Object.defineProperty 直接在对象上定义新属性，或修改现有属性，并返回该对象。

## 45. Proxy and Reflect (Proxy 和 Reflect)
**English**: Proxy objects define custom behavior for fundamental operations. Reflect is a built-in object that provides methods for interceptable JavaScript operations.

**中文**: 代理对象为基本操作定义自定义行为。Reflect 是一个内置对象，提供拦截 JavaScript 操作的方法。

## 46. Symbols (符号)
**English**: Symbol is a primitive data type whose instances are unique and immutable, often used as object property keys to avoid name collisions.

**中文**: Symbol 是一种原始数据类型，其实例是唯一且不可变的，通常用作对象属性键以避免名称冲突。

## 47. TypedArrays (类型化数组)
**English**: TypedArrays provide a mechanism for accessing raw binary data, offering better performance for operations involving binary data.

**中文**: 类型化数组提供了访问原始二进制数据的机制，为涉及二进制数据的操作提供更好的性能。

## 48. Blob and ArrayBuffer (Blob 和 ArrayBuffer)
**English**: Blob represents binary data with a type. ArrayBuffer is a generic fixed-length binary data buffer.

**中文**: Blob 表示具有类型的二进制数据。ArrayBuffer 是通用的固定长度二进制数据缓冲区。

## 49. Service Workers (服务工作者)
**English**: Service Workers are scripts that run in the background, separate from a web page, enabling features like offline functionality and push notifications.

**中文**: 服务工作者是在后台运行的脚本，与网页分开，支持离线功能和推送通知等特性。

## 50. Web Workers (Web 工作者)
**English**: Web Workers allow scripts to run in background threads, performing tasks without interfering with the user interface.

**中文**: Web 工作者允许脚本在后台线程中运行，执行任务而不干扰用户界面。

## 51. Garbage Collection (垃圾回收)
**English**: JavaScript automatically allocates memory when objects are created and frees it when they are not used anymore through a process called garbage collection.

**中文**: JavaScript 在创建对象时自动分配内存，并在不再使用对象时通过垃圾回收过程释放内存。

## 52. Deep and Shallow Copy (深拷贝和浅拷贝)
**English**: A shallow copy copies object references, while a deep copy duplicates all values and nested objects.

**中文**: 浅拷贝复制对象引用，而深拷贝复制所有值和嵌套对象。

## 53. Strict Mode (严格模式)
**English**: Strict mode makes several changes to normal JavaScript semantics, eliminating some silent errors and throwing exceptions for unsafe actions.

**中文**: 严格模式对普通 JavaScript 语义进行了一些更改，消除了一些静默错误，并对不安全的行为抛出异常。

## 54. Bitwise Operators (位运算符)
**English**: Bitwise operators perform operations on binary representations of numbers, including AND, OR, XOR, NOT, left shift, and right shift.

**中文**: 位运算符对数字的二进制表示执行操作，包括与、或、异或、非、左移和右移。

## 55. eval() Function (eval() 函数)
**English**: eval() executes JavaScript code represented as a string, but it's slow and poses security risks.

**中文**: eval() 执行表示为字符串的 JavaScript 代码，但它速度慢且存在安全风险。

## 56. ECMAScript Specifications (ECMAScript 规范)
**English**: ECMAScript is the scripting language specification standardized by ECMA International, which JavaScript implements.

**中文**: ECMAScript 是由 ECMA 国际标准化的脚本语言规范，JavaScript 实现了该规范。

## 57. Polyfills and Transpilation (Polyfills 和转译)
**English**: Polyfills add functionality not natively supported by older browsers. Transpilation converts modern JavaScript to older versions for compatibility.

**中文**: Polyfills 添加旧浏览器原生不支持的功能。转译将现代 JavaScript 转换为旧版本以实现兼容性。

## 58. Tree Shaking (摇树优化)
**English**: Tree shaking is a technique used in modern JavaScript build tools to eliminate unused code from the final bundle.

**中文**: 摇树优化是现代 JavaScript 构建工具中用来从最终包中剔除未使用代码的技术。

## 59. JavaScript Engine (JavaScript 引擎)
**English**: A JavaScript engine is a program that executes JavaScript code. Examples include V8 (Chrome), SpiderMonkey (Firefox), and JavaScriptCore (Safari).

**中文**: JavaScript 引擎是执行 JavaScript 代码的程序。例如 V8（Chrome）、SpiderMonkey（Firefox）和 JavaScriptCore（Safari）。

## 60. Same-Origin Policy (同源策略)
**English**: The same-origin policy restricts how a document or script loaded from one origin can interact with a resource from another origin for security reasons.

**中文**: 同源策略出于安全原因限制了从一个源加载的文档或脚本如何与另一个源的资源交互。
