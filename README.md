# Yo.js

`Yo.js`是笔者在学习`Promise`知识体系的过程中，依据`Promise/A+`规范，参考网上各路开发者前辈的知识分享和代码示例而编写的简单`Promise`实现，并且通过了`Promise/A+`的测试用例。

在学习基础知识之后，参考网上的开发者对`Promise`实现的探讨方案，再阅读`Promise/A+`规范，即可很容易理解大家的实现逻辑。

笔者在注释中根据规范的每一条都进行了标注，希望对你理解每一行代码有所帮助。

**如果笔者有逻辑错误，或者大家有其他建议，欢迎留言~**

再次感谢：

- [Basic Javascript promise implementation attempt - Stack Overflow](https://stackoverflow.com/questions/23772801/basic-javascript-promise-implementation-attempt/23785244) 翔实的讲解如何按照规范实现其代码逻辑
- [bluejava/zousan: A Lightning Fast, Yet Very Small Promise A+ Compliant Implementation](https://github.com/bluejava/zousan) 我最喜欢的`Promise`个人实现方案，快速创建微任务的`soon`函数被我直接引用。
- 其他开发者的分析

如何验证是否通过测试？

- yarn
- yarn run test

![](https://raw.githubusercontent.com/youyiqin/markdown_imgs/master/1.png)

