# Student-Management-System
数据结构课程大作业
## 演示平台
* Visual Studio 2017编辑器
* C++语言/C语言
## 实现功能
* 年级管理：包括年级基本信息的添加、修改、删除、查询功能。学生必须归属于某个年级。
* 班级管理：包括班级基本信息的添加、修改、删除、查询功能。学生必须归属于某个班级。
* 课程管理：包括课程基本信息的添加、删除功能。
* 添加功能：分本科生和研究生两类人员，实现下列添加功能。
1. 本科生：能够添加学生信息，数据结构成绩、计组成绩、大英成绩都输入。
2. 研究生：能够添加学生信息，课程综合成绩、论文成绩都输入。
* 修改功能：分本科生和研究生两类人员，实现下列修改功能。
1. 本科生：根据学号来修改任意学生的除学号
2. 研究生：根据学号来修改任意学生的除学号外的信息。外的信息。
* 删除功能：分本科生和研究生两类人员，能够根据学号删除一个学生。
* 查询功能：分本科生和研究生两类人员，实现下列查询功能。
1. 统计某班级某课程不及格学生名单及人数。
2. 统计某班级某课程不同等级的学生人数。
3. 等级标准：优—大于等于90；良—大于等于80且小于90；中：大于等于70且小于80；及格：大于等于60且小于70；不及格：小于60。
## 函数框架
* Person类函数：
getID():获取学生的学号  
getName():获取学生的名字  
getSex()：获取学生的性别  
getMajorNumber()：获取学生的编码  
getClassNumber()：获取学生的班级编码  
getMajor()：获取学生的年级名称  
getClass()：获取学生的班级名称  
getScore(int n)：获取学生的成绩  
motify(int n)：提醒用户输入正确的姓名和性别  

* 本科生类函数：
Display()：输出学生的成绩  
motify(int n)：提醒用户输入正确的成绩  

* 研究生类函数：
Display()：输出学生的成绩  
motify(int n)：提醒用户输入正确的成绩  

* 班级类函数：
Display() const：输出学生的年级、学号、姓名  
getMajor_number()：获取学生的年级编号  
getMajor()：获取学生的年纪名称  
getName()：获取学生的姓名  
getID()：获取学生的学号  

* 年级类函数：
Display() const：输出学生的学号、姓名  
getName()：获取学生的姓名  
getID()：获取学生的学号  
