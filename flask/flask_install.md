### EPEL install for CentOS7
```
rpm -Uvh https://dl.fedoraproject.org/pub/epel/epel-release-latest-7.noarch.rpm
```

### yum으로 설치하기 위해서는 EPEL을 설치해야 합니다.

```
yum install python-pip
```

### 필요하면 pip를 업그레이드 합니다.
```
pip install --upgrade pip
```


### 수동으로 설치하기
참조 : https://pip.pypa.io/en/latest/installing.html

#### Download
```
curl -k -O https://bootstrap.pypa.io/get-pip.py
```

#### 설치 스크립트를 실행합니다.
```
python get-pip.py
```

### Flask를 설치합니다.
```
# pip install Flask
....
{directories}/app/venv/build/Flask/setup.py
....
```


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
