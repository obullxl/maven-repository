# Maven仓库托管

## sequence-jdbc仓库

+ 个人博客：[https://ntopic.cn/p/2023062101/](https://ntopic.cn/p/2023062101/)
+ Gitee源代码仓库：[https://gitee.com/obullxl/sequence-jdbc](https://gitee.com/obullxl/sequence-jdbc)
+ GitHub源代码仓库：[https://github.com/obullxl/sequence-jdbc](https://github.com/obullxl/sequence-jdbc)

### 配置仓库
Gitee或者GitHub两个选择一个即可：
Gitee - 在项目`pom.xml`中增加仓库地址：
```xml
<repositories>
   <repository>
      <id>Gitee-obullxl</id>
      <url>https://gitee.com/obullxl/maven-repository/raw/master/repository</url>
   </repository>
</repositories>
```

或者GitHub - 在项目`pom.xml`中增加仓库地址：
```xml
<repositories>
   <repository>
      <id>GitHub-obullxl</id>
      <url>https://raw.githubusercontent.com/obullxl/maven-repository/raw/master/repository</url>
   </repository>
</repositories>
```

### JAR包依赖
```xml
<dependency>
    <groupId>cn.ntopic</groupId>
    <artifactId>sequence-jdbc</artifactId>
    <version>1.0.1</version>
</dependency>
```
