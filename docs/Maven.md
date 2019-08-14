## Maven常用命令


### 下载
>http://maven.apache.org/


### 配置阿里云镜像加速

>apache-maven-3.5.0\conf\settings.xml
```xml
<mirror>
            <id>alimaven</id>
            <mirrorOf>central</mirrorOf>
            <name>aliyun maven</name>
            <url>http://maven.aliyun.com/nexus/content/repositories/central/</url>
</mirror>
```

### 修改本地缓存仓库位置
```xml
<localRepository>/maven/repository</localRepository>
```

### maven创建项目

>mvn archetype:generate -DgroupId=com.how2java -DartifactId=j2se -DarchetypeArtifactId=maven-archetype-quickstart -DinteractiveMode=false

>archetype:generate 表示创建个项目

>-DgroupId 项目包名: com.how2java

>-DartifactId 项目名称: j2se

>-DarchetypeArtifactId 项目类型: maven-archetype-quickstart

>-DinteractiveMode:false 表示前面参数都给了，就不用一个一个地输入了


### 项目打包

>进入项目文件夹
>mvn package


