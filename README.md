# 简介
Open-cmdb是基于Python2.7、Django1.7、Puppet开发的一套快速将服务器软硬件等信息集中化展示的系统。

> 主要功能有：
> * 快速展示服务器信息
> * 支持服务器信息录入
> * 支持Ansible动态获取主机列表进行代码发布

如果环境中已有Puppet，此系统能快速接入，否则需要自行配置Puppet环境。目前暂时不支持Ansible的YAML格式。

# 环境依赖

* Python2.7
* Django1.7

# 启动
* yum install -y screen
* screen
* python manage.py runserver 0.0.0.0:80 &
