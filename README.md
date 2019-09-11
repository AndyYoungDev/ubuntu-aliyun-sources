## ubuntu-aliyun-sources

ubuntu更换国源（阿里云源）

### 安装
- 方案1.shell命令一键更换
```shell script
sudo curl -L https://github.com/AndyYoungDev/ubuntu-aliyun-sources/releases/download/shell/change.sh | bash
```

- 方案2.shell命令安装
```shell script
sudo wget https://github.com/AndyYoungDev/ubuntu-aliyun-sources/releases/download/shell/change.sh

sudo chmod a+x change.sh

sudo ./change.sh
```

- 方案2.手工替换/etc/apt/sources.list
```shell script
ubuntu 14.04 请使用sources1404.list
ubuntu 16.04 请使用sources1604.list
ubuntu 18.04 请使用sources1804.list
#提示 VIM编辑器，命令模式输入ggVG可全选，按d进行删除，按i进入insert模式，SHIFT+INS进行粘贴
```


### 联系
* 微信：ylf283598349
* 希望和github的老哥们多多交流
