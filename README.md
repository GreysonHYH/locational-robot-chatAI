# 可读取本地材料的聊天机器人
可以读取本地材料的聊天机器人核心思路展示，LangChain & OpenAI。

用最简单核心的代码来实现通过本地导入向量数据库来生成答案的基本流程。

## 实现背景：
* 1.由于ChatGPT的内容最新截止到2021年9月，而在这之后的互联网上最新的信息它是不知道的，而通过让它读取本地资料可获取到最新的数据。

* 2.当我们需要学习某一个特定的材料和文档时，可以让AI读取该材料，以实现聊天式学习。

* 3.提高我们查找本地资料的速度，以及让AI更懂用户，因为它还会对我们本地的数据信息进行总结。

* 4.未来开发者乃至各行各业工作者都离不开AI，有必要了解对于如何构建一个AI助手的基本实现思路。

## 使用指南

安装依赖
```js
npm i
```

修改api和向量数据库信息

* 进入 .env文件

* 将里面的值改为自己真实的信息

执行代码
```js
node chat.js
```
