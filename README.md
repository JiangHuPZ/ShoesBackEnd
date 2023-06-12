# ShoesBackEnd
修改settings.py中的sql配置
在项目的根目录下，运行数据库迁移命令以创建用户表：
python manage.py makemigrations
python manage.py migrate
最后，在项目的根目录下，运行开发服务器：
python manage.py runserver

默认端口为localhost:8000
向127.0.0.1:8000/register 发送post请求，提交用户注册数据。
