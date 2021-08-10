# Spring Boot starter测试题

## 练习描述
在`WebSecurityConfig.java`文件中补充代码，使登录功能可以正常使用。  
  **具体步骤：**  
    1. 在下面完成代码，需要有"USER"权限的用户可以访问到 /user/** 的文件  
    2. 登录成功后，跳转到user.html页面  
    3. 登出成功后，跳转到login.html页面  

## 环境描述 
- java8
- Intellij-IDEA

## 如何开始
- 命令启动项目：

```
./gradlew bootRun
```

- 补全代码后登录  
用户名：`admin`  
密码：`admin`  
登录成功后会显示`欢迎USER权限用户登录`的字样。

- 成功后，截图即可。
