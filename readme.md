# dotnet

这个仓库用于 hebau 2022 春季 dotnet 课程.

核心指导原则是: 看文档 -> [https://docs.microsoft.com/zh-cn/dotnet](https://docs.microsoft.com/zh-cn/dotnet)

所有知识点都包含在文档中，这里有一切你需要的东西。

## 课程参考文章

1. .Net 发展史与开发环境配置
   1. [NET简介](./samples/lessons1.0/lessons1.1.md)
   2. [IDE安装及Dotnet环境配置](./samples/lessons1.0/lessons1.2.md)
2. C#语言基础与进阶
3. 面向对象
4. WinForm
5. ADO.net
6. 多线程
7. ASP.NET Core

## 什么是 .NET

.NET 是一个开源的跨平台的开发平台，它是一个涵盖性的概念，它包含 .NET 相关的一系列类库、标准、文档、工具等。

在 5.0 版本之前，它被称为 .NET Core 和 .NET Framework。

.NET 的核心是 .NET Standard，它是一个 API 规范。

.NET 提供的一系列工具和框架、库等，允许开发者使用 C#、VB、F# 等语言创建应用程序。

这些框架可以让开发者方便地开发 Web 服务端程序（ASP.NET Core）、游戏（Unity3D）以及桌面应用程序（UWP）等。

在很多时候 .NET 也可指已经安装在操作系统中的虚拟机和类库的集合，其中最主要的是 .NET CLR（Common Language Runtime），它就像 JVM 可以运行 Java 字节码一样，.NET CLR 是 C#、VB、F# 等语言生成的中间代码 IL（Intermediate Language） 的运行时环境。

所以，我们也可以说 C# 运行在 .NET CLR 上。

## 知识点清单

- .NET 与 Visual Studio
  - Visual Stuido 的安装，以及 .NET 环境配置
  - dotnet 命令行工具（创建示例程序模板，构建和运行程序）
  - .NET 这个概念的含义
  - .NET 是如何跨平台的
  - .NET 程序，中间代码和虚拟机
  - .NET 有哪些框架，这些框架可以做什么
  - .NET 的历史
    - .NET Framework
    - .NET Core
    - .NET
- C#
  - 流程控制
  - 顶级语句(Top-level statements)
  - 类型系统
    - 命名空间
    - 类和结构体
    - 元祖
    - 枚举
    - 记录
    - 接口
    - 泛型
    - 委托和 lambda 表达式
    - 允许为 null 的值类型和允许为 null 的引用类型
    - 类型转换
  - 错误处理
- WinForm
  - TODO
- C# 面向对象
  - 封装
    - 可访问性修饰符
  - 继承
  - 多态
    - 简单设计模式
      - 工厂模式
  - C# 特性
    - 事件
    - 终结器（析构）
    - 索引器
    - 迭代器
    - 运算符重载
    - 嵌套类型
    - 匿名类型
  - 与 Java 对比
- ADO.NET(数据库)
  - 使用 ADO.NET 连接 SQL Server 数据库
  - 使用 ADO.NET 的接口通过 SQL 语句增删改查数据库
  - 语言集成查询 LINQ
    - 使用 LINQ 增删改查内存中的数据（LINQ to Object）
  - Entity Framework Core（EF Core）
    - 使用 LINQ 增删改查 MySQL数据库
    - 在 EF Core 中使用不同的数据库 Provider
- 多线程
  - TODO
- ASP.NET Core
  - RESTful 是什么
  - 如何使用 ASP.NET Core 开发 RESTful HTTP 服务端
  - 什么是依赖注入，它解决了什么问题，该如何在 ASP.NET Core 中使用它
  - 什么是 MVC
  - 如何使用 Razor Pages 开发 Web 服务端程序
