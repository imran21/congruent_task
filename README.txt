

Hello Sir,

I have done the Task what you have given.
As I am new to Ansible, I just spent one day in learning before starting the task.

I have used AWS machine for this task.

Totally 3 Virtual Machine(VM) with RedHat OS

VM-1 for Ansible server

VM-2 for webserver(Apache) PHP and Memcached

VM-3 for MySql Server


WorkFlow

web_memcache_server_install.yml -> installation of webserver and memcache and creation memcached
mysql_get_rpmpackage.yml -> Getting mysql RPM Pacakge
mysql_install_server.yml -> Installing Mysql package
mysql_user_add.yml 		 -> Adding user to mysql database.

mysqlServer not allowing to create a password "testuser". 
It allows only a password string with alpha-numeric with special characters (testuser@A1)



Sir, I am facing the problem with memcached. I have installed and configured memcached with php successfully, but I couldn't able to access ports what you have specified (11212, 11213, 11214) other than default port 11211. I tried a lot but I don't know sir.

The default port 11211 is working fine with PHP.

Apart from that everything is working fine sir.

Thanks 