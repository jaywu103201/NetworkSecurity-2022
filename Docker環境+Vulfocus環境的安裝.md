# 1.解除安裝舊版本Docker
```
sudo apt-get remove docker docker-engine docker.io containerd runc
```
# 2.更新apt
```
sudo apt-get update
```
# 3.允許 apt 通過 HTTPS 使用存儲庫
```
sudo apt-get install \
     ca-certificates \
     curl \
     gnupg \
     lsb-release
```
# 4.添加Docker官方的GPG密鑰
```
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
```
# 5.使用以下命令設置穩定存儲庫
```
echo \
    "deb [arch=$(dpkg --print-architecture) signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu \
    $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null
————————————————
版权声明：本文为CSDN博主「温氏效应」的原创文章，遵循CC 4.0 BY-SA版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/x650007/article/details/121406363
```
# 6.更新apt
```
sudo apt-get update
```
# 7.安裝最新版本的 Docker Engine 和 containerd
```
sudo apt-get install docker-ce docker-ce-cli containerd.io
```
# 8.安裝您的存儲庫中可用的版本
```
apt-cache madison docker-ce
```
# 9.通過運行 hello-world 映像驗證 Docker Engine 是否已正確安裝
```
sudo docker run hello-world
```
![image](https://user-images.githubusercontent.com/71476447/201526906-1d27f1a3-60a9-4ccd-b949-d07fedcc4e08.png)

# 10.檢查是否啟動成功
```
sudo docker ps -a
```

****
# Vulfocus靶場安裝
# 1.拉取vulfocus鏡像
```
sudo docker pull vulfocus/vulfocus:latest
```
# 2.運行 Vulfocus
```
sudo docker run -d -p 80:80 -v /var/run/docker.sock:/var/run/docker.sock -e VUL_IP=your-ip vulfocus/vulfocus
```
# 3.查看一下Vulfocus環境ID
```
sudo docker ps -a
```
# 4.啟動Vulfocus環境
```
sudo docker start 環境ID
```
# 5.查看是否啟動成功
```
sudo docker ps -a
```
# 6.訪問靶場環境
```
http://youer-ip/#/dashboard
```
****
