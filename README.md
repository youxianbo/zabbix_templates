# zabbix_templates
A set of templates and scripts for zabbix monitoring software

# Use

文件放置路径：
```
/etc/zabbix/zabbix_agentd.d/userparameters_redis.conf
/etc/zabbix/script/redis/zabbix_check_redis.py
#+执行权限
chmod a+x /etc/zabbix/script/redis/zabbix_check_redis.py
```

在zabbix5服务器web界面导入模板：配置-模板 ,导入项目中的template下的文件



PS:需要python3 并且安装 python的redis库支持

CentOs 可以使用yum直接安装
```
yum install python3
pip3 install redis
```
