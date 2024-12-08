# MyBatis Plus 代码生成器

#### 使用代码生成器

> 运行`MybatisPlusGenerator`类的main方法来生成代码，可直接生成controller、service、mapper、entity、mapper.xml的代码，无需手动创建。

#### 代码生成器支持三种模式
>第一种按照表名生成多表，比如生成`ums_user,ums_role`表代码可以先输入`ums`，后输入`ums_user,ums_role`；

>第二种直接生成模块下的表，比如生成`ums_user,ums_role`模块代码可以先输入`ums`，后输入`ums_*`；

>第三种生成该数据库下的所有表。

#### 配置文件
> 运行前需在`generator.properties`配置
- spring.datasource.url = 数据库连接地址
- spring.datasource.username = 数据库用户名
- spring.datasource.password = 数据库密码
- author = 作者名
- package.name = 生成的包路径
