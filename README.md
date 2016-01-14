
# SpringMVC DEMO

## Description

- 本项目只是一个简单的例子，包含了一个只有两张表的数据库；
- 一直controller，里面仅有增删改查等操作而已；
- 学习过程中完全参照博客：http://my.oschina.net/gaussik/blog/385697 相关系列的文章，总共四篇。感谢作者Gaussic（一个为AI而奋斗却不得不兼顾项目的研究生） 的贡献帮助；
- 具体的请clone项目，使用idea直接打开查看即可；

### pom.xml

        <dependency>
            <groupId>junit</groupId>
            <artifactId>junit</artifactId>
            <version>3.8.1</version>
            <scope>test</scope>
        </dependency>
        <dependency>
            <groupId>org.springframework</groupId>
            <artifactId>spring-core</artifactId>
            <version>${spring.version}</version>
        </dependency>

        <dependency>
            <groupId>org.springframework</groupId>
            <artifactId>spring-web</artifactId>
            <version>${spring.version}</version>
        </dependency>

        <dependency>
            <groupId>javax.servlet</groupId>
            <artifactId>servlet-api</artifactId>
            <version>2.5</version>
        </dependency>

        <dependency>
            <groupId>javax.servlet.jsp</groupId>
            <artifactId>jsp-api</artifactId>
            <version>2.1</version>
            <scope>provided</scope>
        </dependency>

        <dependency>
            <groupId>org.springframework</groupId>
            <artifactId>spring-webmvc</artifactId>
            <version>${spring.version}</version>
        </dependency>

        <dependency>
            <groupId>org.springframework</groupId>
            <artifactId>spring-test</artifactId>
            <version>${spring.version}</version>
            <scope>test</scope>
        </dependency>

        <dependency>
            <groupId>jstl</groupId>
            <artifactId>jstl</artifactId>
            <version>1.2</version>
        </dependency>

        <dependency>
            <groupId>org.springframework.data</groupId>
            <artifactId>spring-data-jpa</artifactId>
            <version>${spring-data.version}</version>
        </dependency>

        <dependency>
            <groupId>org.hibernate.javax.persistence</groupId>
            <artifactId>hibernate-jpa-2.0-api</artifactId>
            <version>1.0.0.Final</version>
        </dependency>

        <dependency>
            <groupId>org.hibernate</groupId>
            <artifactId>hibernate-entitymanager</artifactId>
            <version>3.6.10.Final</version>
        </dependency>

        <dependency>
            <groupId>mysql</groupId>
            <artifactId>mysql-connector-java</artifactId>
            <version>5.1.34</version>
        </dependency>

        <dependency>
            <groupId>org.json</groupId>
            <artifactId>json</artifactId>
            <version>20080701</version>
        </dependency>
    </dependencies>


## 模块二名称
## 模块三名称

## ScreenShot
![](https://raw.githubusercontent.com/gao746700783/SpringMVC/tree/master/images/list.jpg)
![](https://raw.githubusercontent.com/gao746700783/SpringMVC/tree/master/images/add.jpg)
![](https://raw.githubusercontent.com/gao746700783/SpringMVC/tree/master/images/update.jpg)
![](https://raw.githubusercontent.com/gao746700783/SpringMVC/master/images/view.jpg)

## About Me

* Blog: [http://my.oschina.net/u/1408868][1]
* Mail: gao746700783@163.com
* Official Accounts: 全栈技术

## WiKi
* Gaussic: [http://my.oschina.net/u/1408868][2]

## License

    Copyright 2014 gao746700783

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
    


[1]: http://my.oschina.net/u/1408868
[2]: http://my.oschina.net/gaussik/blog/385697
