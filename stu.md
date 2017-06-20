# 学生信息管理系统
## 数据库设计
### 学生信息表student设计

|中文名称 |列名 |字段属性 |默认值 | 备注 |
|-----|-----|------|-----|------|
|学号    |id   |varchar(10)|not null|信息表主键|
|姓名    |sname |varchar(12)|null  |         |
|性别    |sex  |char(1)|null  |         |
|年龄    |age  |int |null  |         |
|系别    |dept |varchar(11)|null  |         |

### 学校信息表university设计
|中文名称 |列名 |字段属性 |默认值 | 备注 |
|-----|-----|------|-----|------|
|编号    |uid  |varchar(12) |not null|信息表主键|
|学校名称|sname |varchar(11)|not null|        |
|系别 |dept|varchar(11) |null |          |
|教师|teacher|varchar(12) |null |          |

### 选课表score设计
|中文名称 |列名 |字段属性 |默认值 | 备注 |
|-----|-----|------|-----|------|
|学号    |sid   |varchar(10)|not null|作sc表主键|
|编号    |uid |vqarchar(10)|not null|作sc主键|
|成绩  |score  |varchar()|null|       |
