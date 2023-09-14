## 沙特身体

~~~sh
$ pip install flask-sqlalchemy
# 必须安装下面这个
$ sudo apt-get install libmysqlclient-dev
# flask-mysqldb才能安装
$ pip install flask-mysqldb
~~~

配置：

~~~python
# app.config['SQLALCHEMY_DATABASE_URI']=mysql://用户名:密码@ip:端口/数据库名
app.config['SQLALCHEMY_DATABASE_URI']='mysql://root:mysql@127.0.0.1:3306/FLASK_04'
~~~

## redis

~~~sh
$ pip install redis
~~~



## Flask-WTF表单

~~~sh
$ pip install Flask-WTF
~~~



## WTForms

一个支持多个web框架的form组件，主要用于对用户请求数据进行验证。

~~~sh
$ pip3 install wtforms
~~~



## flask-wtf   --- 解决csrf问题

~~~sh
$ pip install flask-wtf
~~~



## Flask-session 

因为小写的session数据保存在cookie当中，不能满足我们需求，因此的使用Flask-session

~~~sh
$ pip install Flask-session
~~~

## flask-migrate数据迁移

~~~sh
$ pip install flask-migrate
~~~

## flask-script 

~~~sh
$ pip install flask-script
~~~

## pillow / pil

~~~sh
$  pip install pillow
~~~

