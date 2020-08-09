# REDIS

Redis is used for in-memory data storage, And allows users to access the data over API. 

## Manual Installation of Redis.

1. Install Redis.

```
# yum install epel-release yum-utils -y
# yum install http://rpms.remirepo.net/enterprise/remi-release-7.rpm -y
# yum-config-manager --enable remi
# yum install redis -y
```

2. Start Redis Database

```
# systemctl enable redis
# systemctl start redis
```

## Automated Installation of Redis.

```
# curl -s https://raw.githubusercontent.com/linuxautomations/labautomation/master/tools/redis/install.sh | bash 
```