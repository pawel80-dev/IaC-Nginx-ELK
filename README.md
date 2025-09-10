# IaC-Nginx-ELK
Infrastructure as Code: Nginx (reverse proxy), Elasticsearch, Logstash, Kibana

![alt text](drawings/elk_HLD_v04.png)  
*Syslog flow: high level design*

![alt text](drawings/elk_stack_v02.png)  
*Nginx, ELK stack: general design + IP address scheme*

> [!NOTE]
> For installing Ansible, I've used: sudo -S to elevate privileges.
> For passing sudo and user password to Nginx, I've used: sshpass. Installed on self-hosted runner.

<br/>