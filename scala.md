#### How to add Jar files and classes to the REPL Classpath


##### 解决方法

启动REPL选项：

```
$ scala -cp DateUtils.jar
```

```
$ scala -cp "../Project1/bin:../Project2/classes"
```

在REPL中，可以：

```
scala> :cp DateUtils.jar
```


