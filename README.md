# Jc.SnowId

16位雪花ID生成模块
```c#
dotnet add package  Jc.SnowId
```
#### 实例化
```c#
Jc.SnowId.JcSnowId id= new Jc.SnowId.JcSnowId(1, 1);
```
> 请在一个公共的类里面声明一次，否则有可能会重复
#### 生成ID
```c#
id.NextId()
```