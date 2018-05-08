# osx

在 ubuntu 下使用 vagrant 快速建立 docker 環境.  
以下為我的操作環境  
- ubuntu 16.04  
- vagrant 2.0.2 (用 `vagrant --version` 查看)  
- virtualbox 5.2.6 r120293  

在 [Vagrant Cloud ](https://app.vagrantup.com/boxes/search?utf8=%E2%9C%93&sort=downloads&provider=virtualbox&q=osx) 找到有人建立好的 box, 直接下載來用！  


osx 10.11 elcapitan (測試成功)
```
mkdir osx-10.11-elcapitan
cd osx-10.11-elcapitan
vagrant init carbon/osx-elcapitan-10.11 --box-version 1.0.1
vagrant up # 第一次需要下載很久..., 若失敗只須再次下這個指令
```

osx 10.13 


### 版本列表  
OSX 10.5 Leopard  
OSX 10.6 Snow Leopard  
OSX 10.7 Lion  
OSX 10.8 Mountain Lion  
OSX 10.9 Mavericks  
OSX 10.10 Yosemite  
OSX 10.11 El Capitan  
macOS 10.12 Sierra  
macOS 10.13 High Sierra  
參考 https://zh.wikipedia.org/wiki/MacOS  
