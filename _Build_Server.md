#Initial Server
- [Getting Started with Linode](https://www.linode.com/docs/getting-started) 
- [Securing Your Server](https://www.linode.com/docs/security/securing-your-server)
- [Using Fail2ban to Secure Your Server](https://www.linode.com/docs/security/using-fail2ban-for-security)
- [Control Network Traffic with iptables](https://www.linode.com/docs/security/firewalls/control-network-traffic-with-iptables)
    + Config file: `iptables_v4.conf` and `iptables_v6.conf`
- [Introduction to FirewallD on CentOS](https://www.linode.com/docs/security/firewalls/introduction-to-firewalld-on-centos)

#Install LAMP
- [LAMP on CentOS 7](https://www.linode.com/docs/web-servers/lamp/lamp-on-centos-7)

##Apache Config
- http config in `apache_http.conf` to `/etc/httpd/conf/httpd.conf`
- vhost in `apache_vhost.conf` to `/etc/httpd/conf.d/vhost.conf`

##MySQL Database, User Create Command
```
mysql -u root -p
create database webdata;
grant all on webdata.* to 'webuser' identified by 'password';
quit;
```

##Install PHP 7.x
- [How to Install PHP 7.x on CentOS 7](https://www.vultr.com/docs/how-to-install-php-7-x-on-centos-7)
- [PHP 7.1 on CentOS/RHEL 6.9 and 7.4 via Yum](https://webtatic.com/packages/php71)

##Install Nginx As Reserve Proxy
- [How to configure Nginx as a reverse proxy for Apache on CentOS](https://www.hugeserver.com/kb/configure-nginx-reverse-proxy-apache-centos/)


#OSSEC - Open Source HIDS SECurity
- [How To Install OSSEC HIDS on a CentOS 7 Server](https://www.vultr.com/docs/how-to-install-ossec-hids-on-a-centos-7-server)
- [Installing OSSEC HIDS on CentOS 7](https://kmibei.com/04/03/2017/installing-ossec-hids-on-centos-7/)
- [Install and Configure OSSEC on Debian 7](https://linode.com/docs/security/ossec-ids-debian-7)
- [Documentation](https://ossec.github.io/docs)