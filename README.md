使用说明：
idea导入本maven项目
resources的applicationContext.xml的46行会报错，不用管，自动生成代码之后就不报错了
需要修改的地方：

 - src.main.java.main.GeneraterSqlMap的第18行，改为rescources中generatorConfig.xml的绝对路径
 - resources的db.properties按照本地的数据库进行配置
 - resources的generatorConfig.xml的第11-15行按照本地数据库进行配置
 - resources的generatorConfig.xml的第44行起选择需要自动生成的表