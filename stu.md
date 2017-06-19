# 学生信息管理系统
## 数据库设计
### 学生信息表Information设计

|中文名称 |列名 |字段属性 |默认值 | 备注 |
|-----|-----|------|-----|------|
|学号    |id   |int(4)|not null|信息表主键|
|姓名    |name |char(11)|null  |         |
|性别    |sex  |char(11)|null  |         |
|年龄    |age  |int(4)  |null  |         |
|系别    |dept |char(11)|null  |         |

### 学校信息表school设计
|中文名称 |列名 |字段属性 |默认值 | 备注 |
|-----|-----|------|-----|------|
|编号    |sno  |char(4) |not null|信息表主键|
|学校名称|sname |char(11)|not null|        |
|选修课  |spno |char(11) |null |          |

### 选课表score设计
|中文名称 |列名 |字段属性 |默认值 | 备注 |
|-----|-----|------|-----|------|
|学号    |id   |int(4) |not null|作sc表主键|
|编号    |sno  |char(4) |not null|作sc主键|
|成绩  |grade  |smallint(6) |null|       |
