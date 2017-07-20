# SpringMVC最小化配置

> 通过这个项目，可以之后在这个项目的基础上，测试其他功能。
 

1. 加入jar包依赖
	compile group: 'org.springframework', name: 'spring-context', version: '4.3.9.RELEASE'
	compile group: 'org.springframework', name: 'spring-webmvc', version: '4.3.9.RELEASE'

2. 加入配置文件
	web.xml
	applicationContext.xml
	Springmvc-servlet.xml
	
3. 加入Controller

***使用方式***

* 在项目根目录执行 gradlew appRun
  gradlew 代表 gradle wrapper意思是gradle的一层包装，大家可以理解为在这个项目本地就封装了gradle，即gradle wrapper
  gradle appRun是gradle的命令。