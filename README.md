## 简介
SmartWiki是一款针对IT团队开发的简单好用的文档管理系统。
可以用来储存日常接口文档，数据库字典，手册说明等文档。内置项目管理，用户管理，权限管理等功能，能够满足大部分中小团队的文档管理需求。

## 使用

1.下载源码
```
git clone https://github.com/lifei6671/SmartWiki.git
```
2.安装composer

```
sudo curl -sS https://getcomposer.org/installer | sudo php
sudo mv composer.phar /usr/local/bin/composer
```
3.设置目录权限

```
sudo chmod -R 0777 storage

```

4.恢复laravel的依赖

```
composer install

```

如果不是root权限，可能会出现没有写权限的错误。解决方法是手动创建目录，或者是切换到root权限执行。


5.然后打开首页会自动跳转到安装页面。


## 部分截图

**个人资料**

![个人资料](https://raw.githubusercontent.com/lifei6671/SmartWiki/master/storage/app/images/20161124082553.png)

**我的项目**

![我的项目](https://raw.githubusercontent.com/lifei6671/SmartWiki/master/storage/app/images/20161124082647.png)

**项目参与用户**

![项目参与用户](https://raw.githubusercontent.com/lifei6671/SmartWiki/master/storage/app/images/20161124082703.png)

**文档编辑**

![文档编辑](https://raw.githubusercontent.com/lifei6671/SmartWiki/master/storage/app/images/20161124082810.png)

**文档模板**

![文档模板](https://raw.githubusercontent.com/lifei6671/SmartWiki/master/storage/app/images/20161124082844.png)


## 使用的技术
- laravel 5.2
- mysql 5.6
- editor.md
- bootstrap 3.2
- jquery 库
- layer 弹出层框架
- webuploader 文件上传框架
- Nprogress 库
- jstree 
- font awesome 字体库
- cropper 图片剪裁库

## 功能
1. 项目管理，可以对项目进行编辑更改，成员添加等。
2. 文档管理，添加和删除文档，文档历史恢复等。
3. 用户管理，添加和禁用用户，个人资料更改等。
4. 用户权限管理 ， 实现用户角色的变更。
5. 项目加密，可以设置项目公开状态为私密、半公开、全公开。
6. 站点配置，二次开发时可以添加自定义配置项。

## 待实现

1. 项目转让
2. 项目导出
3. 角色细分
4. 项目文档树生成
5. 忘记密码

## 作者

一个纯粹的PHPer。[SmartWiki 演示文档](http://www.iminho.me/docs/show/1)









