### sqlalchemy 설치
#### MySQL-python 설치
#####  설치 오류시 해결 방법
```
...
Command "python setup.py egg_info" failed with error code 1 in /tmp/pip-build-PTLtUn/MySQL-python/
```

###### For Ubuntu
```
sudo apt-get update
sudo apt-get install python-dev
sudo apt-get install python-MySQLdb
```

###### For CentOS
```
yum install python-devel mysql-devel
```
