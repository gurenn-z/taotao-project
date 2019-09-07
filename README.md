# taotao-project
## 系统架构
![](https://i.loli.net/2019/09/08/uKd15FPsW6Vy4Qa.png)
## 项目结构
```
taotao-parent：父工程，打包方式pom，管理jar包的版本号。
    |           项目中所有工程都应该继承父工程。
|--taotao-common：  通用的工具类通用的pojo。打包方式jar
|--taotao-manager： 服务层工程。聚合工程。Pom工程
    |--taotao-manager-dao：  打包方式jar
    |--taotao-manager-pojo： 打包方式jar
    |--taotao-manager-interface： 打包方式jar
    |--taotao-manager-service：   打包方式：war
|--taotao-manager-web：  表现层工程。打包方式war
```

