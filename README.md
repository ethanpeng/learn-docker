# learn-docker

在 ubuntu 16.04 下使用 vagrant 快速建立 docker 環境.  
在 [Vagrant Cloud](https://app.vagrantup.com/boxes/search?provider=docker) 找到有人建立好的docker, 直接下載來用  
```
mkdir ubuntu-16.04-docker
cd ubuntu-16.04-docker
vagrant init tknerr/baseimage-ubuntu-16.04 --box-version 1.0.0
vagrant up --provider docker
```

docker 剛建立為最小安裝, 很多指令都沒有, 安裝一些常用的工具吧！  
```
sudo apt-get update
sudo apt-get install iputils-ping # 安裝 ping 工具
sudo apt-get install net-tools # 安裝 ifconfig 工具
```

如何查詢某個指令在 apt-get 的那一個安裝包?  
```
dpkg -S ping # 查詢 ping
dpkg -S ifconfig # 查詢 ifconfig
```
