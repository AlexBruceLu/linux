### 1 查看当前mysql下的数据库。

 show databases;
 
 ![image](https://raw.githubusercontent.com/wiki/AlexBruceLu/Linux/showdatabases.png)

### 2 创建数据库mydb1

 create database mydb1;
 ![image](https://raw.githubusercontent.com/wiki/AlexBruceLu/Linux/createdatabase.png)

### 3 查看mydb1数据库信息

 show create database mydb1; 
 ![image](https://raw.githubusercontent.com/wiki/AlexBruceLu/Linux/showmydb1.png)

### 4 利用schema创建数据库mydb2

 create schema mydb1;
 
 ![image](https://raw.githubusercontent.com/wiki/AlexBruceLu/Linux/schema.png)

### 5 创建数据库mydb3 指定字符集为gb2312  校对规则为 gb2312_chinese_ci;

 create database mydb3 character set gb2312 collate gb2312_chinese_ci ;
 ![image](https://raw.githubusercontent.com/wiki/AlexBruceLu/Linux/char.png)

### 6 创建数据库mydb3前判断是否存在同名数据库

 create database if not exists mydb3;
 ![image](https://raw.githubusercontent.com/wiki/AlexBruceLu/Linux/6.png)

### 7 查看名称以mydb开头的数据库

 show databases like 'mydb%';
 
 ![image](https://raw.githubusercontent.com/wiki/AlexBruceLu/Linux/7.png)

### 8 选择数据库mydb1

 use mydb1;

### 9 修改mydb1数据库字符集为gb2312;

 alter database mydb1 character set gb2312;
 ![image](https://raw.githubusercontent.com/wiki/AlexBruceLu/Linux/89.png)

### 10 删除数据库mydb1

 drop database if exists mydb1;
 ![image](https://raw.githubusercontent.com/wiki/AlexBruceLu/Linux/10.png)


