# docker-zabbix

- after docker installition, change ip adress(docker inspect agentcontainerID) on configuration->hosts->zabbix-server->agent-interfaces. 
- if you want to connect zabbix agent to remote zabbix server, you should write ip adress which is running zabbix-agent on host. 
- run this command on terminal -> docker exec -it (servercontainerID) zabbix_server -R config_cache_reload 
- refresh zabbix web interface.


zabbix user name: Admin
password: zabbix
