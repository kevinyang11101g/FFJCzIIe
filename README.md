## 前言

随着社会的快速发展，人们生活水平的不断提高，对美的追求也越来越高。彩妆作为女性日常生活中不可或缺的一部分，市场需求日益旺盛。为了方便彩妆样品的销售与管理，我们开发了基于SSM（Spring、SpringMVC、MyBatis）的彩妆样品销售系统。以下是关于本项目的详细介绍。

## 内容介绍

本项目是一款基于SSM框架的彩妆样品销售系统，主要实现了以下功能：

1. 用户注册、登录、个人信息管理；
2. 彩妆样品分类展示、详情查看、搜索；
3. 购物车、订单管理；
4. 用户评论、点赞、收藏；
5. 后台管理，包括用户管理、样品管理、订单管理、评论管理等功能。

通过本项目，用户可以方便地购买到心仪的彩妆样品，同时商家也可以更好地进行销售管理。

## 技术介绍

- 语言：Java
- 使用框架：Spring、SpringMVC、MyBatis
- 前端技术：JS、Vue、CSS3
- 开发工具：IDEA/Eclipse
- 数据库：MySQL 5.7/8.0
- 数据库管理工具：phpstudy/Navicat
- JDK版本：jdk1.8
- Maven：apache-maven 3.8.1-bin
- 前端环境：Node.Js 12/14/16

## 核心代码

以下是一段关于用户登录的核心代码：

```java
@Service
public class UserServiceImpl implements UserService {

    @Autowired
    private UserMapper userMapper;

    @Override
    public User login(String username, String password) {
        // 查询用户
        User user = userMapper.selectByUsername(username);
        if (user != null && user.getPassword().equals(password)) {
            return user;
        }
        return null;
    }
}
```

## 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

## 项目截图

![封面图片](https://img12.360buyimg.com/ddimg/jfs/t1/328633/24/10920/96255/68acb30fF97a6ff11/e3f43c29975e8982.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/335943/34/1711/24257/68acb2eaF92f2f210/e289cc56539b2518.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/290868/23/25611/35982/68acb2ecF36ef3fa1/0a58a0b91bfaa416.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/295730/14/27283/64581/68acb2eeF1769f9d6/b312e00de675431c.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/333354/18/4184/56284/68acb2efF8e370c26/32b9e81b5482e79d.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/333208/36/4026/51621/68acb2f0F44be3865/f514be20236017c6.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/334539/38/4124/35015/68acb2f0F5ffbbb01/67f583311815b23b.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/327004/39/10725/45203/68acb2f1F3909e347/a16df3d6cabb5761.jpg)

![介绍图片](https://img12.360buyimg.com/ddimg/jfs/t1/330896/15/4256/63337/68acb2f2F8ecb6b62/c5ed4ddc9f3f39d7.jpg)

![介绍图片](https://img11.360buyimg.com/ddimg/jfs/t1/324807/27/11030/45169/68acb2f2F91f280cb/fa6843db5fffc0d7.jpg)

