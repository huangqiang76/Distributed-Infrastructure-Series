# 并发模型

- 线程与锁：线程与锁模型有很多众所周知的不足，但仍是其他模型的技术基础，也是很多并发软件开发的首选。

- 函数式编程：函数式编程日渐重要的原因之一，是其对并发编程和并行编程提供了良好的支持。函数式编程消除了可变状态，所以从根本上是线程安全的，而且易于并行执行。

- Clojure 中的分离标识与状态：编程语言 Clojure 是一种指令式编程和函数式编程的混搭方案，在两种编程方式上取得了微妙的平衡来发挥两者的优势。

- Actor：actor 模型是一种适用性很广的并发编程模型，适用于共享内存模型和分布式内存模型，也适合解决地理分布型问题，能提供强大的容错性。

- 通信顺序进程(Communicating Sequential Processes，CSP)：表面上看，CSP 模型与 actor 模型很相似，两者都基于消息传递。不过 CSP 模型侧重于传递信息的通道，而 actor 模型侧重于通道两端的实体，使用 CSP 模型的代码会带有明显不同的风格。

- 数据级并行：每个笔记本电脑里都藏着一台超级计算机——GPU。GPU 利用了数据级并行，不仅可以快速进行图像处理，也可以用于更广阔的领域。如果要进行有限元分析、流体力学计算或其他的大量数字计算，GPU 的性能将是不二选择。

- Lambda 架构：大数据时代的到来离不开并行——现在我们只需要增加计算资源，就能具有处理 TB 级数据的能力。Lambda 架构综合了 MapReduce 和流式处理的特点，是一种可以处理多种大数据问题的架构。

# 链接

- https://medium.com/one-datum-at-a-time/an-exploration-into-concurrent-programming-and-concurrency-models-b22144950a88

- [concurrency-models](http://tutorials.jenkov.com/java-concurrency/concurrency-models.html)

- [七周七并发模型](https://drive.wps.cn/view/l/3db758274cf94555a456332436ec5f19)

- [并发之痛 Thread，Goroutine，Actor](http://www.tuicool.com/articles/MNVbAbQ)
