## 前言

随着新冠疫情的蔓延，图书馆作为公共场所，面临着更为严格的防控要求。在这样的背景下，一套功能齐全、便捷实用的图书馆管理系统显得尤为重要。本项目是基于Spring Boot开发的疫情下图书馆管理系统，旨在为读者和图书馆管理员提供安全、高效的图书管理服务。

## 内容介绍

本项目涵盖了图书馆管理的基本功能，包括用户管理、图书管理、借阅管理、公告管理等。系统采用前后端分离的设计模式，前端负责展示界面，后端负责数据处理。通过本项目的实战演练，您可以全面了解Spring Boot的开发流程，掌握Java Web项目的构建方法。

## 技术介绍

- 语言：Java
- 使用框架：Spring Boot
- 前端技术：JS、Vue、css3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12\14\16

## 核心代码

以下为项目中的部分核心代码，实现了图书查询功能：

```java
@RestController
@RequestMapping("/book")
public class BookController {

    @Autowired
    private BookService bookService;

    @GetMapping("/query")
    public ResponseEntity<List<Book>> queryBooks(@RequestParam String keyword) {
        List<Book> books = bookService.queryBooks(keyword);
        return ResponseEntity.ok(books);
    }
}
```

## 联系我们

🌟![在这里插入图片描述](https://github.com/user-attachments/assets/8f1ce2ba-72f1-441f-8d65-395ddab4650d)

如果您在使用本项目过程中遇到任何问题，或者有好的建议，欢迎联系我们。

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img13.360buyimg.com/ddimg/jfs/t1/328457/30/4351/94970/689da9beFa8a4cd43/e88ad327164bfa5a.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/303840/6/27161/19751/689da99bFd88639b5/9a7c8161a8f6afaf.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/288920/18/24683/33457/689da99bFbc759bb5/d3def8e04b34b912.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/319088/15/22945/38401/689da99cFfd4e4dab/48afc7d99b4ac03d.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/310867/28/26474/39907/689da99cF96ee4778/15972275ecb514a7.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/288348/10/20669/31414/689da99dF0474a69f/47787f742ee8b8f4.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/320567/40/24824/41281/689da99eFa5e5d241/9863a31d3fe376f3.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/313324/26/26156/76252/689da99fFfd47f639/39e7a1b3b40be02c.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/311688/39/25662/15818/689da9a0Ff0089dc1/94605ca17729b676.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/309722/18/25684/41201/689da99fF24ec0bc1/0cd9d3df89237792.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
