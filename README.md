# code-generation-tool
mybatis自动生成代码工具

使用:
* 修改jdbc.properties文件内的数据库地址和账号密码,还有mysql的jar包位置
* 修改generatorConfig.xml文件里的包名和要生成的表
* 新建一个Maven的Configuration
* 在Command line的输入框中添加: mybatis-generator:generate -e
* 应用完成
* 在Maven Projects里找到刚配置的Configuration
* 运行后代码自动创建到generate目录下

注: 包目录自动生成,不用手动创建.