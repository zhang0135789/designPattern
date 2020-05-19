# designPattern
设计模式练习

欢迎交流 qq群:416311205

### 工厂模式
- factory
* 解决问题:主要解决接口选择的问题
* 优点:1.创建对象,只需要知道名字 2.扩展性高,如果想增加产品,只要增加一个工厂类就可以 3.屏蔽产品的具体实现,调用者只关心产品接口
* 缺点:每增加一个产品,就需要增加一个实体类和对象实现工厂,系统中类的个数增加,在一定程度上增加了系统的复杂度,同时也增加了系统类的依赖
* 场景:1.日志记录器 2.数据库访问 3.设计连接服务器的框架 4.MQ
1. 创建接口
2. 创建接口的实体类
3. 创建一个工厂,生成基于给定信息的实体类的对象

### 
