+ Add public key of mongodb
```bash
sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv EA312927
```

+ Create the source list file
```bash
sudo touch /etc/apt/sources.list.d/mongodb.list
deb http://mirrors.tuna.tsinghua.edu.cn/mongodb/apt/ubuntu trusty/mongodb-org/stable multiverse
```

+ Install the mongodb
```bash
sudo apt-get update
sudo apt-get install -y mongodb-org
```
