# Spring官方Guides

随着微服务的流行，Spring Boot/Cloud的崛起，Spring Source几乎再一次要成为Java的代名词。那么我们如何才能快速的学习和入门Spring呢？除了很多国内高手编写的一些教程之外，有没有更为官方的指导呢？实际上，在Spring官方网站中是有非常优秀的教程页面的：https://spring.io/guides。

但是由于该教程内容均是英文的，所以只有少部分人会关注这里。所以，我们[SpringForAll社区](http://spring4all.com)计划开始组织对这部分高质量内容的翻译工作，以促进Spring这样优秀的框架在国内的发展！由衷的希望Spring大生态变得越来越强大！

## 协作参与

- 交流社区：[SpringForAll社区](http://spring4all.com)
- Github：https://github.com/SpringForAll/spring-guides-translation
- 组织人：[程序猿DD](https://github.com/dyc87112/)

### 如何认领

下面列举了当前所有教程列表，还译者栏和校对栏空缺的表示还没有人参与翻译，有兴趣的读者可以联系我（微信：zhaiyongchao1987）参与翻译或校对工作。

**翻译登记方法**：

- 在本项目中提issue的方式提交认领登记

- 登记格式如下：

  > 原文：从下面表格中选择感兴趣的文章
  >
  > 角色：译者 or 校对

*注意：*

- 如果对文章翻译和Spring的使用没有太多经验的话，可以先从**校对**开始
- 请勿一次认领多篇，在完成一篇之后再认领下一篇，保证高效多人并行
- 为了保证翻译质量，所有文章都需要经过校对后才发布，校对人员可在交流群中找，校对通过PR的Review完成

### 翻译内容

待翻译内容有如下三个部分：

#### Getting Started Guides

Designed to be completed in 15-30 minutes, these guides provide quick, hands-on instructions for building the "Hello World" of any development task with Spring. In most cases, the only prerequisites are a JDK and a text editor.

| 标题                                       | 简介                                       | 译者                                       | 校对                                       |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- | ---------------------------------------- |
| [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/) | Learn how to create a RESTful web service with Spring. | [冀天宇](https://github.com/Jitianyu) 、 [aprimecoder](https://github.com/aprimecoder) | [ francischan714](https://github.com/francischan714) 、 [yh128](https://github.com/yh128)  、 [scuwuyu](https://github.com/scuwuyu) |
| [Scheduling Tasks](https://spring.io/guides/gs/scheduling-tasks/) | Learn how to schedule tasks with Spring. | [张伟文](https://github.com/carlzhangweiwen)、 [happyxiaofan](https://github.com/happyxiaofan) 、 [nl101531](https://github.com/nl101531) 、 [lovedboy2012](https://github.com/lovedboy2012) | [codedrinker](https://github.com/codedrinker) |
| [Consuming a RESTful Web Service](https://spring.io/guides/gs/consuming-rest/) | Learn how to retrieve web page data with Spring's RestTemplate. | [aprimecoder](https://github.com/aprimecoder) 、 [strongant](https://github.com/strongant) | [scuwuyu](https://github.com/scuwuyu)    |
| [Building Java Projects with Maven](https://spring.io/guides/gs/maven/) | Learn how to build a Java project with Gradle. | [ongoingdotme](https://github.com/ongoingdotme) 、   [shenpengyan](https://github.com/shenpengyan) | [william-hyx](https://github.com/william-hyx) |
| [Accessing Relational Data using JDBC with Spring](https://spring.io/guides/gs/relational-data-access/) | Learn how to access relational data with Spring. | [codedrinker](https://github.com/codedrinker) |                                          |
| [Uploading Files](https://spring.io/guides/gs/uploading-files/) | Learn how to build a Spring application that accepts multi-part file uploads. | [JustDoNow](https://github.com/JustDoNow) |                                          |
| [Authenticating a User with LDAP](https://spring.io/guides/gs/authenticating-ldap/) | Learn how to secure an application with LDAP. | [512013674](https://github.com/512013674) ， [Kandde](https://github.com/Kandde) |                                          |
| [Registering an Application with Facebook](https://spring.io/guides/gs/register-facebook-app/) | Learn how to register an application to integrate with Facebook. |                                          |                                          |
| [Messaging with Redis](https://spring.io/guides/gs/messaging-redis/) | Learn how to use Redis as a message broker. | [linzx2015](https://github.com/linzx2015) | [codedrinker](https://github.com/codedrinker) |
| [Registering an Application with Twitter](https://spring.io/guides/gs/register-twitter-app/) | Learn how to register apps with Twitter. |                                          |                                          |
| [Messaging with RabbitMQ](https://spring.io/guides/gs/messaging-rabbitmq/) | Learn how to create a simple publish-and-subscribe application with Spring and RabbitMQ. | [陈志军](https://github.com/chenzhijun)、 [hh23485](https://github.com/hh23485) 、 [shenpengyan](https://github.com/shenpengyan) 、 [linzx2015](https://github.com/linzx2015) |                                          |
| [Accessing Twitter Data](https://spring.io/guides/gs/accessing-twitter/) | Learn how to access user data from Twitter. |                                          |                                          |
| [Accessing Facebook Data](https://spring.io/guides/gs/accessing-facebook/) | Learn how to access Facebook information from an application. |                                          |                                          |
| [Accessing Data with Neo4j](https://spring.io/guides/gs/accessing-data-neo4j/) | Learn how to persist objects and relationships in Neo4j's NoSQL data store. |                                          |                                          |
| [Validating Form Input](https://spring.io/guides/gs/validating-form-input/) | Learn how to perform form validation with Spring. | [carl-zhao](https://github.com/carl-zhao) 、 [strongant](https://github.com/strongant) |                                          |
| [Building a RESTful Web Service with Spring Boot Actuator](https://spring.io/guides/gs/actuator-service/) | Learn how to create a RESTful Web service with Spring Boot Actuator. |                                          |                                          |
| [Messaging with JMS](https://spring.io/guides/gs/messaging-jms/) | Learn how to publish and subscribe to messages using a JMS broker. | [zivyu](https://github.com/zivyu)        | [JohnHello](https://github.com/JohnHello) |
| [Creating a Batch Service](https://spring.io/guides/gs/batch-processing/) | Learn how to create a basic batch-driven solution. |                                          |                                          |
| [Securing a Web Application](https://spring.io/guides/gs/securing-web/) | Learn how to protect your web application with Spring Security. | [徐靖峰](https://github.com/lexburner)      | [程序猿DD](https://github.com/dyc87112/)    |
| [Building a Hypermedia-Driven RESTful Web Service](https://spring.io/guides/gs/rest-hateoas/) | Learn how to create a hypermedia-driven RESTful Web service with Spring. |                                          |                                          |
| [Accessing Data with GemFire](https://spring.io/guides/gs/accessing-data-gemfire/) | Learn how to build an application using Gemfire's data fabric. |                                          |                                          |
| [Integrating Data](https://spring.io/guides/gs/integration/) | Learn how to build an application that uses Spring Integration to fetch data, process it, and write it to a file. | [xuxiaoxie](https://github.com/xuxiaoxie) |                                          |
| [Caching Data with GemFire](https://spring.io/guides/gs/caching-gemfire/) | Learn how to cache data in GemFire.      | [liweijian199011](https://github.com/liweijian199011) |                                          |
| [Managing Transactions](https://spring.io/guides/gs/managing-transactions/) | Learn how to wrap key parts of code with transactions. | [汪志峰](https://github.com/maskwang520)    | [francischan714](https://github.com/francischan714) |
| [Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/) | Learn how to work with JPA data persistence using Spring Data JPA. | [汪志峰](https://github.com/maskwang520) 、 [lovedboy2012](https://github.com/lovedboy2012) | [francischan714](https://github.com/francischan714) |
| [Accessing Data with MongoDB](https://spring.io/guides/gs/accessing-data-mongodb/) | Learn how to persist data in MongoDB.    |                                          |                                          |
| [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/) | Learn how to create a web page with Spring MVC. | [dejunyu](https://github.com/dejunyu)    | [xiudongxu](https://github.com/xiudongxu) |
| [Converting a Spring Boot JAR Application to a WAR](https://spring.io/guides/gs/convert-jar-to-war/) | Learn how to convert your Spring Boot JAR-based application to a WAR file. | [JohnHello](https://github.com/JohnHello) |                                          |
| [Creating Asynchronous Methods](https://spring.io/guides/gs/async-method/) | Learn how to create asynchronous service methods. | [nl101531](https://github.com/nl101531)  [shaoshao721](https://github.com/shaoshao721) |                                          |
| [Handling Form Submission](https://spring.io/guides/gs/handling-form-submission/) | Learn how to create and submit a web form with Spring. | [zzzvvvxxxd](https://github.com/zzzvvvxxxd) |                                          |
| [Building an Application with Spring Boot](https://spring.io/guides/gs/spring-boot/) | Learn how to build an application with minimal configuration. | [shenpengyan](https://github.com/shenpengyan) 、 [nycgym](https://github.com/Anycgym) | [xiudongxu](https://github.com/xiudongxu) |
| [Using WebSocket to build an interactive web application](https://spring.io/guides/gs/messaging-stomp-websocket/) | Learn how to the send and receive messages between a browser and the server over a WebSocket | [汪志峰](https://github.com/maskwang520)    | [francischan714](https://github.com/francischan714) |
| [Working a Getting Started guide with STS](https://spring.io/guides/gs/sts/) | Learn how to import a Getting Started guide with Spring Tool Suite (STS). |                                          |                                          |
| [Consuming a RESTful Web Service with AngularJS](https://spring.io/guides/gs/consuming-rest-angularjs/) | Learn how to retrieve web page data with AngularJS. | [yunlzheng](https://github.com/yunlzheng) |                                          |
| [Consuming a RESTful Web Service with rest.js](https://spring.io/guides/gs/consuming-rest-restjs/) | Learn how to retrieve web page data with rest.js. |                                          |                                          |
| [Consuming a RESTful Web Service with jQuery](https://spring.io/guides/gs/consuming-rest-jquery/) | Learn how to retrieve web page data with jQuery. | [william-hyx](https://github.com/william-hyx) |                                          |
| [Enabling Cross Origin Requests for a RESTful Web Service](https://spring.io/guides/gs/rest-service-cors/) | Learn how to create a RESTful web service with Spring that support Cross-Origin Resource Sharing (CORS). | [yunlzheng](https://github.com/yunlzheng) |                                          |
| [Building Spring YARN Projects with Gradle](https://spring.io/guides/gs/gradle-yarn/) | Learn how to build a Spring YARN Project with Gradle | [ucool2007](https://github.com/ucool2007) |                                          |
| [Building Spring YARN Projects with Maven](https://spring.io/guides/gs/maven-yarn/) | Learn how to build a Spring YARN Project with Maven | [ucool2007](https://github.com/ucool2007) | [zx-stefan](https://github.com/zx-stefan) |
| [Simple YARN Application](https://spring.io/guides/gs/yarn-basic/) | Learn how to build a simple Spring YARN application |                                          |                                          |
| [Testing YARN Application](https://spring.io/guides/gs/yarn-testing/) | Learn how to test a Spring YARN application |                                          |                                          |
| [Batch YARN Application](https://spring.io/guides/gs/yarn-batch-processing/) | Learn how to build a Spring Batch YARN application | [ucool2007](https://github.com/ucool2007) |                                          |
| [Restartable Batch YARN Application](https://spring.io/guides/gs/yarn-batch-restart/) | Learn how to build a restartable Spring Batch YARN application |                                          |                                          |
| [Consuming a SOAP web service](https://spring.io/guides/gs/consuming-web-service/) | Learn how to create a client that consumes a WSDL-based service |                                          |                                          |
| [Accessing JPA Data with REST](https://spring.io/guides/gs/accessing-data-rest/) | Learn how to work with RESTful, hypermedia-based data persistence using Spring Data REST. |                                          |                                          |
| [Accessing Neo4j Data with REST](https://spring.io/guides/gs/accessing-neo4j-data-rest/) | Learn how to work with RESTful, hypermedia-based data persistence using Spring Data REST. |                                          |                                          |
| [Accessing MongoDB Data with REST](https://spring.io/guides/gs/accessing-mongodb-data-rest/) | Learn how to work with RESTful, hypermedia-based data persistence using Spring Data REST. |                                          |                                          |
| [Accessing GemFire Data with REST](https://spring.io/guides/gs/accessing-gemfire-data-rest/) | Learn how to work with RESTful, hypermedia-based data persistence using Spring Data REST. |                                          |                                          |
| [Producing a SOAP web service](https://spring.io/guides/gs/producing-web-service/) | Learn how to create a SOAP-based web service with Spring. | [feilangrenM](https://github.com/feilangrenM) |                                          |
| [Simple Single Project YARN Application](https://spring.io/guides/gs/yarn-basic-single/) | Learn how to build a simple Spring YARN application |                                          |                                          |
| [Caching Data with Spring](https://spring.io/guides/gs/caching/) | Learn how to cache data in memory with Spring | [zzzvvvxxxd](https://github.com/zzzvvvxxxd) |                                          |
| [Deploying to Cloud Foundry from STS](https://spring.io/guides/gs/sts-cloud-foundry-deployment/) | Learn how to deploy a Spring application to Cloud Foundry from STS |                                          |                                          |
| [Spring Boot with Docker](https://spring.io/guides/gs/spring-boot-docker/) | Learn how to create a Docker container from a Spring Boot application with Maven or Gradle | [StormMaybin](https://github.com/StormMaybin)、 [suliangxd](https://github.com/suliangxd) | [jinliang123](https://github.com/jinliang123) |
| [Working a Getting Started guide with IntelliJ IDEA](https://spring.io/guides/gs/intellij-idea/) | Learn how to work a Getting Started guide with IntelliJ IDEA. | [xuxiaoxie](https://github.com/xuxiaoxie) 、 [xiudongxu](https://github.com/xiudongxu) |                                          |
| [Creating CRUD UI with Vaadin](https://spring.io/guides/gs/crud-with-vaadin/) | Use Vaadin and Spring Data JPA to build a dynamic UI |                                          |                                          |
| [Service Registration and Discovery](https://spring.io/guides/gs/service-registration-and-discovery/) | Learn how to register and find services with Eureka |                                          |                                          |
| [Centralized Configuration](https://spring.io/guides/gs/centralized-configuration/) | Learn how to manage application settings from an external, centralized source |                                          |                                          |
| [Routing and Filtering](https://spring.io/guides/gs/routing-and-filtering/) | Learn how to route and filter requests to a microservice using Netflix Zuul | [hh23485](https://github.com/hh23485)、 [oshare](https://github.com/oshare) 、 [RealDeanZhao](https://github.com/RealDeanZhao) |                                          |
| [Circuit Breaker](https://spring.io/guides/gs/circuit-breaker/) | Learn how to degrade gracefully services using Hystrix | [oshare](https://github.com/oshare)      |                                          |
| [Client Side Load Balancing with Ribbon and Spring Cloud](https://spring.io/guides/gs/client-side-load-balancing/) | Dynamically support services coming up and going down without interrupting the client |                                          |                                          |
| [Testing the Web Layer](https://spring.io/guides/gs/testing-web/) | Learn how to test Spring Boot applications and MVC controllers. | [lovedboy2012](https://github.com/lovedboy2012) |                                          |
| [Accessing data with MySQL](https://spring.io/guides/gs/accessing-data-mysql/) | Learn how to set up and manage user accounts on MySQL and how to configure Spring Boot to connect to it at runtime. | [suliangxd](https://github.com/suliangxd) ， [pzzls](https://github.com/pzzls) | [liangliang1259](https://github.com/liangliang1259) |
| [Creating a Multi Module Project](https://spring.io/guides/gs/multi-module/) | Learn how to build a library and package it for consumption in a Spring Boot application |                                          |                                          |
| [Creating API Documentation with Restdocs](https://spring.io/guides/gs/testing-restdocs/) | Learn how to generate documentation for HTTP endpoints using Spring Restdocs | [HoldDie](https://github.com/HoldDie)    |                                          |


#### Topical Guides

Designed to be read and comprehended in an hour or less, providing more wide-ranging or subjective content than a getting started guide.

| 标题                                       | 简介                                       | 译者                                  | 校对                                    |
| ---------------------------------------- | ---------------------------------------- | ----------------------------------- | ------------------------------------- |
| [Spring Security Architecture](https://spring.io/guides/topicals/spring-security-architecture/) | Topical guide to Spring Security, how the bits fit together and how they interact with Spring Boot | [徐靖峰](https://github.com/lexburner) | [程序猿DD](https://github.com/dyc87112/) |

#### Tutorials

Designed to be completed in 2-3 hours, these guides provide deeper, in-context explorations of enterprise application development topics, leaving you ready to implement real-world solutions.

| 标题                                       | 简介                                       | 译者                                       | 校对                                    |
| ---------------------------------------- | ---------------------------------------- | ---------------------------------------- | ------------------------------------- |
| [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/) | Learn how to easily build, test, and secure RESTful services with Spring | [silentbalanceyh](https://github.com/silentbalanceyh)、 [zzzvvvxxxd](https://github.com/zzzvvvxxxd) |                                       |
| [Spring Security and Angular JS](https://spring.io/guides/tutorials/spring-security-and-angular-js/) | A tutorial on how to use Spring Security with a single page application with various backend architectures, ranging from a simple single server to an API gateway with OAuth2 authentication. | [徐靖峰](https://github.com/lexburner)      | [程序猿DD](https://github.com/dyc87112/) |
| [React.js and Spring Data REST](https://spring.io/guides/tutorials/react-and-spring-data-rest/) | A tutorial based on the 5-part blog series by Greg Turnquist |                                          |                                       |
| [Spring Boot and OAuth2](https://spring.io/guides/tutorials/spring-boot-oauth2/) | A tutorial on "social" login and single sign on with Facebook and Github | [CoconutJuice](https://github.com/CoconutJuice) |                                       |

## 翻译规范

关于翻译的一些规范如下：

- 翻译文件格式：markdown

- 文件名格式：原文标题.md （文件已经预创建，直接编辑即可）

- 提交以Pull Request方式提交，每篇文章在他比较PR之后，必须找一位校对人员校对之后才能发布（翻译保证质量）

- 文章摘要部分采用如下的固定格式：（已经预创建，请勿删除该部分）

  > 原文：[Securing a Web Application](https://spring.io/guides/gs/securing-web/)
  >
  > 译者：[徐靖峰](https://github.com/lexburner)
  >
  > 校对：[程序猿DD](https://github.com/dyc87112/)

- 文章末尾使用统一的版权声明：（已经预创建，请勿删除该部分）

  > 本文由spring4all.com翻译小分队创作，采用[知识共享-署名-非商业性使用-相同方式共享 4.0 国际 许可](http://creativecommons.org/licenses/by-nc-sa/4.0/)协议进行许可。

## 致谢

将最诚挚的谢意给SpringForAll社区每一位翻译小队成员，他们都是Spring的忠实爱好者，这里的所有内容都是他们牺牲了业余时间所创造出来的。

下面是所有参与翻译与校对的小伙伴名单（排名不分先后）：

- 待补充

## License

本站作品由SpringForAll翻译小分队创作，采用[知识共享-署名-非商业性使用-相同方式共享 4.0 国际 许可](http://creativecommons.org/licenses/by-nc-sa/4.0/)协议进行许可。
