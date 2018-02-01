> 在线教育系统  
基于 Python 2.7.8 Django 1.9.8  
后台用的是xadmin  


#### 前台功能模块
##### 1.基本模块  
登录 注册 找回密码 / 全局搜索 / 个人中心  
##### 2.课程功能    
课程管理 / 讲师管理 / 授课机构管理 / 热门推荐 / 相关课程推荐  
##### 3.用户操作管理  
用户收藏 / 课程评论

#### 后台管理系统
##### 4.课程管理模块  
课程管理 / 课程资源管理 / 课程评论管理 / 轮播课程管理  
##### 5.认证和授权管理
用户管理 / 组管理 / 权限管理 / 用户日志管理  
##### 6.机构管理模块  
课程机构管理 / 讲轮播图管理


### Run:  
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
