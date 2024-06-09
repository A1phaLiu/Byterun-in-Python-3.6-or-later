# Byterun in Python 3.6 or later

### 介绍

[Byterun](https://github.com/nedbat/byterun/tree/master) 是一个用 Python 编写的 Python 字节码执行虚拟机。它由 [Ned Batchelder](https://github.com/nedbat) 开始创建，目的是为了更好地理解字节码，以便修复 [coverage.py](https://github.com/nedbat/coveragepy) 中的分支预测错误。这个项目可以帮助开发者深入理解 Python 解释器的工作原理，尤其是 CPython 解释器。Byterun 的结构和主要的 Python 实现（CPython）相似，因此通过理解 Byterun 的工作方式，可以帮助理解大多数解释器的工作机制。

由于 Byterun 基于 Python 3.5 及其更早的版本，并且 Python 的字节码规范在 3.6 版本之后进行了一些更改，不再适用于之后的 Python 版本。本项目对字节码处理部分的代码进行了更正，使其能在 Python 3.6 及之后的版本运行，希望对大家有所帮助。

### 注意

- 字节码处理部分的代码来自于 [持墨](https://www.zhihu.com/people/ni-wo-yue-ding-92)
- 中文注释由 [waynerv](https://github.com/waynerv) 完成
- Byterun 收录于 [500 Lines or less](https://aosabook.org/en/index.html)
- 本人只是因为 Python 课程大作业而接触到这个项目，对于代码实现上的很多细节并未完全理解。
- 已在 Python 3.8.13 测试成功

### 参考

- [Byterun](https://github.com/nedbat/byterun/tree/master)
- [A Python Interpreter Written in Python](https://aosabook.org/en/500L/a-python-interpreter-written-in-python.html#fnref1)
- [A-Python-Interpreter-Written-in-Python-Interpreted-in-Chinese](https://github.com/waynerv/A-Python-Interpreter-Written-in-Python-Interpreted-in-Chinese)
- [用Python写一个Python解释器](https://zhuanlan.zhihu.com/p/481884570)

### 许可证

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/3.0/88x31.png" /></a><br />本作品采用<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/3.0/">知识共享署名-非商业性使用-相同方式共享 3.0 未本地化版本许可协议</a>进行许可。
