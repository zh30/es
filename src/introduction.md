# ECMA 介绍

该 Ecma 标准定义了 ECMAScript 2021 语言。这是 ECMAScript 语言规范的第十二版。自 1997 年出版第一版以来，ECMAScript 已成长为世界上使用最广泛的通用编程语言之一。它是众所周知的嵌入在 Web 浏览器中的语言，但也已广泛用于服务器和嵌入式应用程序。

ECMAScript 基于多种原始技术，最著名的是 JavaScript（Netscape）和 JScript（Microsoft）。该语言是 Netscape 的 Brendan Eich 发明的，最早出现在该公司的 Navigator 2.0 浏览器中。从 Internet Explorer 3.0 开始，它出现在 Netscape 的所有后续浏览器以及 Microsoft 的所有浏览器中。

ECMAScript 语言规范的开发始于 1996 年 11 月。该 Ecma 标准的第一版于 1997 年 6 月由 Ecma 大会采用。

该 Ecma 标准已提交给 ISO / IEC JTC 1 以在快速程序下通过，并于 1998 年 4 月被批准为国际标准 ISO / IEC16262。1998 年 6 月的 Ecma 大会批准了 ECMA-262 的第二版使其完全与 ISO / IEC 16262 保持一致。第一版和第二版之间的更改本质上是社论。

该标准的第三版引入了强大的正则表达式，更好的字符串处理，新的控制语句，try / catch 异常处理，更严格的错误定义，数字输出格式以及对将来语言增长的预期的较小更改。ECMAScript 标准的第三版于 1999 年 12 月由 Ecma 大会采用，并于 2002 年 6 月作为 ISO / IEC 16262：2002 发布。

在发布第三版之后，ECMAScript 与万维网一起获得了广泛的采用，该万维网已经成为基本上所有 Web 浏览器都支持的编程语言。开发 ECMAScript 第四版的工作量很大。但是，该工作尚未完成，也没有作为 ECMAScript 的第四版发布，但是其中一些已合并到第六版的开发中。

ECMAScript 的第五版（发布为 ECMA-262 第 5 版）对语言规范的事实上的解释进行了编纂，这些解释在浏览器实现中已变得常见，并增加了对自第三版发布以来出现的新功能的支持。这些功能包括访问器属性，对象的反射式创建和检查，属性属性的程序控制，附加的数组操作功能，对 JSON 对象编码格式的支持以及提供增强的错误检查和程序安全性的严格模式。第五版于 2009 年 12 月由 Ecma 大会通过。

第五版已提交给 ISO / IEC JTC 1 以在快速程序下通过，并被批准为国际标准 ISO / IEC 16262：2011。ECMAScript 标准的 5.1 版包含一些小的更正，并且与 ISO / IEC 16262：2011 的文字相同。5.1 版由 2011 年 6 月的 Ecma 大会通过。

第六版的重点开发工作始于 2009 年，当时正准备出版第五版。但是，此之前要进行大量的实验和语言增强设计工作，直到 1999 年第三版出版为止。实际上，第六版的完成是十五年努力的结晶。该版本的目标包括为大型应用程序，库创建以及将 ECMAScript 用作其他语言的编译目标提供更好的支持。它的一些主要增强功能包括模块，类声明，词法块作用域，迭代器和生成器，对异步编程的承诺，解构模式以及适当的尾部调用。扩展了 ECMAScript 内置库，以支持其他数据抽象，包括地图，集合，以及二进制数值数组，以及对字符串和正则表达式中 Unicode 补充字符的附加支持。内建函数也可以通过子类进行扩展。第六版为常规，增量语言和库增强功能提供了基础。第六版于 2015 年 6 月由大会通过。

ECMAScript 2016 是在 Ecma TC39 的新年度发布节奏和开放式开发流程下发布的第一个 ECMAScript 版本。纯文本源文档是从 ECMAScript 2015 源文档构建的，可作为完全在 GitHub 上进行进一步开发的基础。在制定该标准的一年中，提交了数百个请求和问题，这些问题代表了成千上万的错误修复，编辑修复和其他改进。此外，还开发了许多软件工具来辅助此工作，包括 Ecmarkup，Ecmarkdown 和 Grammarkdown。ES2016 还包括了一个新的乘方运算的支持，并增加了一个新的方法 Array.prototype 叫 includes。

ECMAScript 2017 引入了异步功能，共享内存和原子，以及较小的语言和库增强功能，错误修复和编辑更新。异步函数通过为承诺返回函数提供语法来改善异步编程体验。共享内存和原子技术引入了新的记忆模型 允许多代理人使用原子操作进行通信的程序，即使在并行 CPU 上也能确保定义良好的执行顺序。它还包括对新对象的静态方法：Object.values，Object.entries，和 Object.getOwnPropertyDescriptors。

ECMAScript 2018 引入了对通过 AsyncIterator 协议和异步生成器进行异步迭代的支持。它还包括四个新的正则表达式功能：dotAll 标志，命名捕获组，Unicode 属性转义和后置断言。最后，它包括对象静止和传播属性。

ECMAScript 的 2019 引入了一些新的内置功能：flat 与 flatMap 上 Array.prototype 扁平化阵列，Object.fromEntries 直接打开的返回值 Object.entries 到一个新的对象，trimStart 并 trimEnd 在 String.prototype 更好的命名方案的广泛实施，但不规范 String.prototype.trimLeft 和 trimRight 内置插件。此外，它还对语法和语义进行了一些小的更新。更新的语法包括可选的 catch 绑定参数，并允许字符串文字中的 U + 2028（LINE SEPARATOR）和 U + 2029（PARAGRAPH SEPARATOR）与 JSON 对齐。其他更新包括要求 Array.prototype.sort 保持稳定的排序，要求 JSON.stringify 返回格式正确的 UTF-8（无论输入如何）以及澄清 Function.prototype.toString 要求它返回相应的原始源文本或标准占位符。

ECMAScript 的 2020 年，11 个版，介绍了 matchAll 对字符串的方法，以产生用于对象由全局正则表达式生成的所有匹配的迭代器; import()，一种使用动态说明符异步导入模块的语法；BigInt，一个用于处理任意精度整数的新数字基元；Promise.allSettled，新的 Promise 组合器不会短路；globalThis，一种获取全球 this 价值的普遍方式；export \* as ns from 'module'在模块内使用的专用语法；增加 for-in 枚举顺序的标准化；import.meta，是模块中可用的主机填充对象，其中可能包含有关模块的上下文信息；以及添加两个新的语法功能以改善对“空”值的使用（null 或 undefined）：无效合并，一个值选择运算符；以及可选链接，这是一个属性访问和函数调用运算符，如果访问/调用的值为空，则会短路。

在 Ecma TC39 中，数十个代表许多组织的个人为该版本和以前版本的开发做出了非常重要的贡献。此外，已经形成了一个充满活力的社区，以支持 TC39 的 ECMAScript。该社区审查了许多草案，提交了成千上万的 bug 报告，执行了实施实验，提供了测试套件，并对全球开发人员社区进行了 ECMAScript 教育。不幸的是，不可能确定和认可为这一努力做出贡献的每个人和组织。
