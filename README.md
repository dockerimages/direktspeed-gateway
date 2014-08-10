direktspeed-gateway
===================

Container that runs GATEWAY Services like NGINX, APACHE, HAPROXY, FTP-PROXY, MYSQL-PROXY
maybe code NODE.JS Application that takes values 

then only option is hostport for running this configuration server at


# using knockd to tigger updates
To know all hostnames for the ip we need to do run:
ddocker anet - that will list all running containers by host and ip
## seqqences
# ADD my_ip:80 - 
Recived it will add seqence starter to HAPROXY with its internal-hostname.docker optained via ddocker
# ADD my_ip:22 - creates ssh user restricts him (skel) and setups ssh config
# ADD my_ip:any
# ADD my_ip:bind
Recived will create bind config on skel base with optained ip host pair from ddocker anet


# localhost only

MultiHost
#### Options: dockerhosts, 
