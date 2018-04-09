什么是BlockSql ?
==============

   1.BlockSql 是由Solidity语言编写的，是一个基于Etherenum网络的开源数据库系统。

   2.基本区块链的不可篡改以及可溯源特性，让BlockSql的数据安全成为一个明显的价值特征。

   3.Etherenum分布式系统本身的技术运行稳定特性可保障数据的永久保存，可溯源、可追索保障数据的安全，公钥、私钥保障数据信息的安全。所以，基于Etherenum区块链技术的BlockSql可以称作当下最稳定最安全的数据库。

   4.BlockSql 旨在为WEB应用提供可扩展的高性能数据存储解决方案。

   5.BlockSql 将数据存储在Etherenum网络的Strong中，数据结构由键值(key=>value)对组成。BlockSql 数据类似于 JSON 对象。字段值可以包含其他文档，数组及文档数组。


### BlockSql 主要特点

   *BlockSql 基本区块链存储，保证数据永久保存，数据库大小没有限制。

   *BlockSql使用区块链的Address 私钥签名访问，比普通数据库的用户名密码访问更加安全。
   
   *BlockSql 数据库是一个全局数据库，全网范围内的用户都可以访问，这意味着，企业上下游之间的数据可以共享。

   *BlockSql 专注于数据库操作，让主合约专注于业务逻辑。

   *BlockSql 设置任何属性的索引 (如：FirstName="Sameer",Address="8 Gandhi Road")来实现更快的排序。

   *BlockSql 支持丰富的查询表达式。查询指令使用JSON形式的标记，可轻易查询文档中内嵌的对象及数组。

   *BlockSql 使用update()命令可以实现替换完成的文档（数据）或者一些指定的数据字段 。

   *BlockSql中的Map/reduce主要是用来对数据进行批量处理和聚合操作。

   *BlockSql和Reduce。Map函数调用emit(key,value)遍历集合中所有的记录，将key与value传给Reduce函数进行处理。

   *BlockSql允许在服务端执行脚本，可以用Javascript编写某个函数，直接在服务端执行，也可以把函数的定义存储在服务端，下次直接调用即可。

   *BlockSql支持各种编程语言:RUBY，PYTHON，JAVA，C++，PHP，C#等多种语言。

   *BlockSql安装简单。

### BlockSql 框架

   *后端数据存储为solidity智能合约
   
   *服务器对外接口采用Node.js服务
   
   *服务器配置后台管理操作界面。
