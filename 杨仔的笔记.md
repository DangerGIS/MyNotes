# 杨仔的笔记

![我全要](杨仔的笔记.assets/1585468058713.png)

## Spring Boot

### 日志

#### 市面上的日志框架

 `JUL`、`JCL`、`Jboss-logging`、`logback`、`log4j`、`log4j2`、`slf4j` ……

|                   日志门面（日志的抽象层）                   |                           日志实现                           |
| :----------------------------------------------------------: | :----------------------------------------------------------: |
| JCL（Jakarta Commons Logging) <br/>**SLF4j（Simple Logging Facade for Java）**<br/>jboss-logging | JUL（java.util.logging）<br/>Log4j<br/>Log4j2<br/>**Logback** |

左边选择一个门面（抽象层），右边选择一个实现

Spring Boot选择SLF4j和Logback

