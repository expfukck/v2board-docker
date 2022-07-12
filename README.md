## v2board-docker
```
bash <(curl -Ls https://raw.githubusercontent.com/expfukck/v2board-docker/master/install.sh)
```
## 默认数据库
```
__     ______  ____                      _  
\ \   / /___ \| __ )  ___   __ _ _ __ __| | 
 \ \ / /  __) |  _ \ / _ \ / _` | '__/ _` | 
  \ V /  / __/| |_) | (_) | (_| | | | (_| | 
   \_/  |_____|____/ \___/ \__,_|_|  \__,_| 

 请输入数据库地址（默认:localhost） [localhost]:
 > mysql

 请输入数据库名:
 > v2board

 请输入数据库用户名:
 > root

 请输入数据库密码:
 > 开始自定义的密码默认(v2boardisbest)       

正在导入数据库请稍等...
数据库导入完成

 请输入管理员邮箱?:
 > v2board@qq.com

 请输入管理员密码?:
 > 自定义

一切就绪
访问 http(s)://你的站点/admin 进入管理面板
```
php artisan horizon:publish #更新最新horizon
