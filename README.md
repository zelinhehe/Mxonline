> 在线教育系统  
基于 Python 2.7.8 Django 1.9.8  
后台用的是xadmin  

Feature:  
1.用户注册、登陆、找回密码。  
2.教育机构，讲师，课程的展示、操作（全局搜索、排序等）。  
3.后台管理。  
4.个人中心管理，头像更换，修改密码，更换邮箱。

Run:  
1.MariaDB> create database mxonline;    
  MariaDB> alter database mxonline character set utf8;    
  MariaDB> GRANT ALL PRIVILEGES ON mxonline.* TO 'root'@'%' IDENTIFIED BY '123456';    
2.导入sql文件  
3.安装依赖包:
    pip install -r requirements.txt 
4.python manage.py runserver 0.0.0.0 8006  
5.浏览器中输入 IP:8006 访问  


Q:  
源码安装 DjangoUeditor  
https://github.com/zhangfisher/DjangoUeditor 富文本编辑器   
python setup.py install  
