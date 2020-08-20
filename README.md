## 使用
```
<repositories>
    <repository>
        <id>sqber-util-repo</id>
        <url>https://raw.githubusercontent.com/xu-ben/MyJavaUtils/master/repository</url>
    </repository>
</repositories>

<dependency>
    <groupId>com.sqber</groupId>
    <artifactId>sqber-util</artifactId>
</dependency>
```

>项目发布到了 https://jitpack.io/ 

## 生成

项目修改之后，运行 mvn deploy 则会在 repository 目录下生成新的部署


gitignore 要忽略的文件
```
target/

### IntelliJ IDEA ###
.idea
*.iws
*.iml
*.ipr

/.project
/.settings
/.classpath
/.idea
/.DS_Store
/bin/
```