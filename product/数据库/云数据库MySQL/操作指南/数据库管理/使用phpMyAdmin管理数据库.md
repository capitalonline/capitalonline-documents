#### 创建数据库

1. 登陆phpMyAdmin，点击【新建】或者【数据库】，进入创建数据库页面。

<img src="https://i.loli.net/2021/02/19/uspmEcqxYDNe7vW.png" alt="image-20210219150936122" style="zoom:67%;" />                               

2. 输入数据库名称，选择排序规则（默认为utf8_general_ci），单击【创建】即可完成数据库的创建。

 <img src="C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210219150901935.png" alt="image-20210219150901935" style="zoom:67%;" />

3. 选择需要操作的数据库，单击上方导航栏中的【操作】，即可进入数据库操作页面，在此页面可以对数据库进行【新建数据表】、【复制数据库】等操作。

 

#### 创建数据表

1. 选择需要建表的数据库，单击【新建】或者在【新建数据表】栏输入数据表名和选择字段数后单击【执行】。

![image-20210219151244311](https://i.loli.net/2021/02/19/L1mIxHvoBCDrf7Y.png) 

2. 进入数据表创建页面后，若需要添加字段，请在【添加】处输入所需添加的字段数，然后单击【执行】。【结构】栏为各字段信息的填写。【PARTITION definition】栏为分区信息（请参见 MySQL 分区章节）。填写完信息后单击【保存】，即可完成数据表的创建。

#### 删除数据库

1. 登陆phpMyAdmin，单击需要管理的数据库名称，进入数据库管理页面，点击【操作】。

![image-20210219151826031](https://i.loli.net/2021/02/19/3XLwNOuh6PZDqe2.png) 

2. 在此页面可以对数据库进行【新建数据表】、【删除数据库】等一系列操作。单击【删除数据库（DROP）】即可完成数据库的删除操作。

#### 删除数据表

选择需要删除的表所在的数据库，在此页面可以对数据表进行【浏览】、【结构】、【搜索】、【插入】、【清空】、【删除】一系列操作，单击【删除】。

![image-20210219151917247](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\image-20210219151917247.png) 

#### 使用SQL命令

登陆phpMyAdmin，点击【SQL】，即可执行SQL命令。

 ![image-20210219151954430](https://i.loli.net/2021/02/19/H1UkWiE8MNIdAg5.png)