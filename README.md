# SpringCkeck
**SpringBoot概况**

SpringBoot是由Pivotal团队提供的全新框架，其设计目的是用来简化新Spring应用的初始搭建以及开发过程。该框架使用了特定的方式来进行配置，从而使开发人员不再需要定义样板化的配置。通过这种方式，Spring Boot致力于在蓬勃发展的快速应用开发领域(rapid application development)成为领导者。

Actuator是SpringBoot提供的对应用系统的监控和管理的集成功能，可以查看应用配置的详细信息，例如自动化配置信息、创建的Spring beans信息、系统环境变量的配置信以及Web请求的详细信息等。在 Actuator 启用的情况下，如果没有做好相关权限控制，非法用户可通过访问默认的执行器端点（endpoints）来获取应用系统中的监控信息。常常使用不当或者一些不经意的疏忽，可能造成信息泄露等严重的安全隐患。

**SpringBoot框架识别**

springboot框架典型特征

![image-20231002114557694](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20231002114557694.png)

fofa语法：

```
body="Whitelabel Error Page"
```

**工具使用命令**

单个目标站点扫描:

```
SpringCheck.exe -u http:*//example.com*
```

多个目标站点扫描:

```
SpringCheck.exe -f url.txt
```

![image-20231002114731782](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20231002114731782.png)

![image-20231002114737575](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20231002114737575.png)

由于内容太多，插件使用方式请关注微信公众号：**琴音安全**查看使用方法

![qrcode_for_gh_930a1284eae3_430](C:\Users\Administrator\Downloads\qrcode_for_gh_930a1284eae3_430.jpg)
