# java-jar-demo
java jar demo for rainbond
这是一个简单的 `java-jar` 示例，正常部署需要本地有java环境，执行命令为：
```bash
java -jar javajardemo.jar
```
当你在Rainbond部署的时候，需要注意的是：
```bash
该java项目监听了8080端口，而源码构建默认开启的是5000端口，需要部署过程中，在高级选项中设置
```
