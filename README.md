## 使用
```
<repositories>
    <repository>
        <id>jitpack.io</id>
        <url>https://jitpack.io</url>
    </repository>
</repositories>

<dependency>
	<groupId>com.github.shenqiangbin</groupId>
	<artifactId>sqber-util</artifactId>
	<version>v0.1.0</version>
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
