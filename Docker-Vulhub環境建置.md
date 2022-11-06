# [kali安裝docker](https://blog.csdn.net/aodechudawei/article/details/122450720)

# - 1.安裝Docker
```
curl  -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-key add -
echo 'deb https://download.docker.com/linux/debian stretch stable'> /etc/apt/sources.list.d/docker.list
apt-get install apt-transport-https  ca-certificates  curl  gnupg2  software-properties-common
apt-get update 
sudo apt install docker.io
docker -v
```
# - 2.Docker 常用指令
```
service docker start   //啟動docker服務
 
docker version   //查看docker版本資訊
 
docker ps  查看容器
 
docker  images   查看已有的鏡像
```
# - 3.Docker安裝完成後要安裝 compose
```
apt install docker-compose

```
# [docker之vulhub靶場環境搭建（Linux)](https://blog.csdn.net/qq_50953689/article/details/124616151)
