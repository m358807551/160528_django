# 160528_django

## 快速搭建 Blog

### 安装 Django

> 在 windows 下用 pip install django，在 ubantu 下用 sudo apt-get install django。

### 创建 Django 工程

> django-admin.py startproject mysite

### 创建 blog 应用

### 初始化 admin 数据库

> python manage.py syncdb
其中 sync 是同步的意思，而 db 是数据库的意思

### 设置 admin 应用

#### 添加 blog 应用

> 在settings.py 文件中添加 'blog'

#### 启动 Django 自带的服务器

> python manage.py runserver

#### 访问后台应用

> 在网页用打开 127.0.0.1/admin

### 设计 Model

#### 创建表

> class PostsModel(models.Model):pass
在应用下的 models.py 文件中添加继承自 models.Model 的类，该类名就是表名。

#### 为表添加属性
> 如 body = models.TextField()
有几种预先定义好的属性类型

* 字符串：models.CharField()
* 文本：models.TextField()
* 时间戳: models.DateTimeField()

#### 注册表
> 还是在 models.py 文件中，admin.site.register(BlogsPost)

### 设置 admin 的 BlogsPost 界面

### 创建模板

### 创建视图函数

### 创建 Blog 的 URl 模式

### 添加样式

# just think

> 将 vs 的字体和大小 换成 emacs 的样式。

> 开发一个项目，用来模拟写代码。

> 为了完成上述内容，有可能要学习编译原理的词法分析或者是语法分析。

> 学习 html，css，js