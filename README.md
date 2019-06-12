# docker-zabbix

- after docker installition, change ip adress(docker inspect agentcontainerID) on configuration->hosts->zabbix-server->agent-interfaces. 
- run this command on terminal -> docker exec -it (servercontainerID) zabbix_server -R config_cache_reload 
- refresh zabbix web interface.
