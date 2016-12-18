# zabbix-ssl-monitoring

Install dependencies for centos `yum install openssl bc`

Place `scripts/zabbix_ssl_expiration.sh` into /etc/zabbix/scripts/ and make executable `chmod 755 /etc/zabbix/scripts/scripts/zabbix_ssl_expiration.sh`

Place `config/userparameter_ssl_expiration.conf` into `/etc/zabbix/zabbix_agentd.d/` or directly into `/etc/zabbix/zabbix_agentd.conf`

Import template from `template/Template SSL Expiration.xml`

Edit items and triggers, in template is one example for www.google.ru


