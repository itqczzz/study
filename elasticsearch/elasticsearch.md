
#索引模块  
索引模块是控制所有关于索引功能的模块

##索引设置

每个索引都能设置索引等级，设置可能是：
***静态索引：***
索引只能在创建的时候设置或者是在关闭的索引上创建
***动态索引：***
  可以通过更新索引设置API实时改变索引
  
静态索引设置：
以下是一个静态索引设置列表 ：
index.number_of_shards：
一个索引应该有的基础分片默认是1.这个参数只能在索引创建的时候被设置。不能再一个已经关闭的索引上更改
Note：