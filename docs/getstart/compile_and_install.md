# 程序部署
## 获取代码

新建一个目录，例如/mydata

```shell
sudo mkdir -p /mydata
sudo chmod 777 /mydata
cd /mydata
```
clone 源码

``` shell
git clone https://github.com/FISCO-BCOS/FISCO-BCOS.git
```

## 安装FISCO-BCOS

切换到FISCO-BCOS目录下，执行FISCO-BCOS安装脚本。脚本自动下载并安装程序。

```bash
cd FISCO-BCOS 
bash build.sh
#若需要源码编译安装 使用 bash build.sh -b
```

检查是否安装成功

```bash
fisco-bcos --version 
#成功: FISCO-BCOS version x.x.x
```

