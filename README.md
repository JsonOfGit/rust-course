# Rust语言圣经

- 书籍作者: [Sunface](https://im.dev)
- 官方网址： https://course.rs
- 修订时间： **尚未发行**
- Rust版本：Rust edition 2021
- QQ交流群： 1009730433

## 关于本书

#### 书本简介
`Rust语言圣经`是一本涵盖了从入门到精通各个阶段的Rust书籍，书本的章节和内容组织经过深思熟虑的设计，以符合中国用户的编程使用习惯，目的是尽量对新手更友好，同时也更方便老手的后期检索查询。

使用Rust的用户往往都对性能非常感兴趣，因此本书对于性能优化方面也是分散落入各个章节中，同时还有一个专门的**性能优化**专题，来帮助用户系统的认识如何优化Rust项目的性能。

针对不同的使用场景，我们也给出了多种模版代码，方便用户直接复制粘贴到代码中，例如读取文件、http请求等，无需再去网上搜索。

Rust的外部库层次不齐，针对这一点，我们根据功能分类推荐了相应的高质量开源库，同时提供了基础的使用帮助。

**在学完这本书后，你也会随之完成数个小型项目**，例如其中一些是：

- Mandelbrot集合渲染
- 类Grep命令
- CPU模拟器
- 小型数据库
- 小型Redis
- HTTP等网络请求客户端
- 小型操作系统内核

从上面的列表可以看出，学完本书，不仅会教会你Rust语言，还能学到系统编程和底层编程, 尽情享受奇妙的编程之旅吧。

#### 创作初心

还有很多，就不一一列举，等待大家自己去探索挖掘。 总之在写作过程中我们始终铭记初心：**为用户打造一本真正的Rust中文好书。 新手用来入门，老手用来提高，高手能用来提升生产力**。

#### 目标读者

目标读者大致能落在以下三个范畴内
1. 有其它语言编程基础，无Rust编程语言经验的爱好者
2. 已经熟悉Rust想要更进一步的中级Rust程序员
3. 想要随时检索一些Rust知识和代码，对生产力有要求的Rust开发者

#### 内容说明

书的目录组织结构和内容组织完全是原创，其中书籍内容部分，大部分是原创，另外一部分来源于外文资料及中文翻译书籍。

来源于中文翻译书籍的内容都会标明来源，在复制粘贴的同时，还进行了大量的修改，一个是增加中文翻译的准确性，还有就是提升阅读流畅度，让行文更符合中国人的阅读习惯，摆脱“机器翻译味", **所以本书的内容每句话都是经过精心构思，力求提供给大家最好的阅读体验**.

## 开源版权说明

Rust语言圣经是完全开源的电子书籍，但是也应该受到版权的保护，毕竟凝聚了大家多个数以百计小时的汗水、牺牲了大量陪伴家人的时间，才完成了该书。

因此我们选择了[No License](https://www.google.com.hk/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&ved=2ahUKEwigkv-KtMT0AhXFdXAKHdI4BCcQFnoECAQQAw&url=https%3A%2F%2Fchoosealicense.com%2Fno-permission%2F&usg=AOvVaw3M2Q4IbdhnpJ2K71TF7SPB)作为我们的版权，这意味着读者可以随意的fork、阅读，但是不能私下修改后再分发，如果想要修改，请提RP或者加入Rust编程学院，成为正式成员。


## Philosophy(设计哲学)

书本的内容组织上遵循以下原则：
1. 内聚性: 每个章节都应该系统的阐述一整块儿独立的内容,尽量减少章节之间的耦合性
2. 先易后难：按照初级 -> 中级 -> 高级排列内容
3. 知识链：知识B的学习如果需要先学习知识A，则A一定在B之前出现
4. 章节命名：当用户突然想了解某个知识点时，可以很快的定位到它所在的章节，例如想了解Arc，就应该`多线程 -> Arc`这种章节目录形式

## Rust社区

与国外的Rust发展如火如荼相比，国内的近况不是特别理想。

导致目前这种状况的原因，我个人认为有以下几点原因：
1. 上手难度大，学习曲线陡峭
2. 中文资料少，英文资料难学(基于原因1)
3. 没有体系化的学习路线，新人往往扫完一遍入门书籍，就不知道何去何从

因此我联合几个朋友一起创建了Rust编程学院(Rust College), 致力于给国内提供最新、最高质量Rust学习内容。

官网网址:
- https://college.rs
- https://rustcollege.cn
- QQ群：1009730433