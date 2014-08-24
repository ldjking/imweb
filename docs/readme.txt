#设计的目的
---
admin 	监听一个固定的端口  
		能配置nginx 的配置文件，并能运行命令重启 nginx		 转发给具体的apps
		能执行git pull命令 更新代码
		能配置账号的访问权限
apps	应用目录
pub		公共目录
private 私有目录
logs	日志
docs	文档