# E: Unable to locate package error
[Fixing E: Unable to locate package error](https://www.youtube.com/watch?v=QQap6JVFbk0)
****
# 偵測不到端口 or Shell 反彈無反應
- 先確認監聽的IP是否為Kali
- 要搞清楚是該 放受害者主機IP or 攻擊主機(Kali)
****

#打靶機網路設置
- 把兩台虛擬機都設置 網路橋接介面卡
- 用NAT 兩台都可上網,但是在不同網段
- 用 僅限主機介面可,在同一個網段,但無法上網(內網)
****
#Burp Suite 使用
- Proxy -> Open Browser 
- 在打開的瀏覽器輸入要抓包的網址
- 成功抓包後 -> 右鍵 -> Send Repeater
![image](https://user-images.githubusercontent.com/71476447/198700178-b933cf1f-bc5a-4703-b985-b0d82aac0cd3.png)
![image](https://user-images.githubusercontent.com/71476447/198700200-91125fad-e575-480f-8fb1-bf29d4a709b7.png)
****
