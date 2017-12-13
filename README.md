# 学生考试管理系统(sems)【Student Exam Manage System】
# JSP+Servlet
# MySQL 5.7
# tomcat 8.0
# MyEclipse 2014

学生考试管理系统使用说明


1.新建数据库sems，将sems.sql导入该数据库

2.用解压文件打开sems.war, 打开sems.war\WEB-INF\classes\c3p0-config.xml文件，修改服务器所在数据库用户名和密码

3.将sems.war文件放入tomcat/webapps目录下

4.启动tomcat服务器

5.打开浏览器，输入 localhost:8080/sems 进入登录界面

6.输入用户名和密码访问系统
 用户名：admin
 密码：111111
 
 教师账号：
	2012 
	2011
	2010
	2009
	2008
	
	
 学生账号：
	201301001
	201302002
	201401001
	201402002
	
 密码都为：111111

也可将sems.zip项目文件导入MyEclipse使用
注：将src下c3p0-config.xml中的用户名和密码改为自己数据库的用户名和密码












