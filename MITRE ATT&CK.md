[MITRE_Attack](https://attack.mitre.org/)
===
* 1.Reconnaissance 偵查
* 2.Resource Development 資源開發戰術
* 3.Initial Access 初期存取
* 4.Execution 執行
* 5.Persistence 持續潛伏
* 6.Privilege Escalation 權限提升
* 7.Defense Evasion 防禦逃脫
* 8.Credential Access	憑證存取
* 9.Discovery 發現
* 10.Lateral Movement	橫向移動
* 11.Collection 收集
* 12.Command and Control 命令與控制
* 13.Exfiltration 滲出
* 14.Impact 衝擊
---
1.Reconnaissance 偵查
===
* Active Scanning 主動掃描
  * Scanning IP Blocks 掃描IP
  * Vulnerability Scanning 漏洞掃描
  * Wordlist Scanning 字典掃描
* Gather Victim Host Information 收集受害者主機資訊
  * Hardware 硬體
  * Software 軟體
  * Firmware 韌體
  * Client Configurations 客戶端配置
* Gather Victim Identity Information 收集受害者身分資訊
  * Credentials 憑證
  * Email Addresses 電子郵件地址
  * Employee Names 員工姓名 
* Gather Victim Network Information 收集受害者網路資訊
  * Domain Properties 網域屬性 
  * DNS 網域名稱系統
  * Network Trust Dependencies 網路信任依賴關係
  * Network Topology 網路拓撲
  * IP Addresses IP位置 
  * Network Security Appliances 網路安全設備
* Gather Victim Org Information 收集受害者組織訊息
  * Determine Physical Locations 確定物理位置
  * Business Relationships 業務關係
  * Identify Business Tempo 確認業務節奏
  * Identify Roles 確認角色
* Phishing for Information 網路釣魚資訊
  * Spearphishing Service 魚叉式網路釣魚伺服器
  * Spearphishing Attachment 魚叉式網路釣魚附件
  * Spearphishing Link 魚叉式網路釣魚連結
* Search Closed Sources 搜尋專有軟體
  * Threat Intel Vendors 威脅情資供應商
  * Purchase Technical Data 採購技術資料
* Search Open Technical Databases 搜尋公開技術資料庫
  * DNS/Passive DNS 網域名稱系統/被動式網域名稱系統
  * WHOIS 查閱網域/IP位置工具
  * Digital Certificates 公開金鑰認證/數位憑證
  * CDNs 內容傳遞網路
  * Scan Databases 掃描資料庫
* Search Open Websites/Domains 搜尋公開網站/網域
  * Social Media 社交媒體
  * Search Engines 搜尋引擎
* Search Victim-Owned Websites 搜尋受害者擁有的網站
---
2.Resource Development 資源開發戰術
===
* Acquire Infrastructure 獲取基礎設施
  * Domains 網域
  * DNS Server 網域名稱系統伺服器
  * Virtual Private Server 虛擬私人伺服器
  * Server 伺服器
  * Botnet 殭屍網路
  * Web Services Web服務
* Compromise Accounts 竄改帳戶
  * Social Media Accounts 社交媒體帳戶
  * Email Accounts 電子信箱帳戶
* Compromise Infrastructure 竄改基礎架構
  * Domains 網域
  * DNS Server 網域名稱系統伺服器
  * Virtual Private Server 虛擬私人伺服器
  * Server 伺服器
  * Botnet 殭屍網路
  * Web Services Web服務
* Develop Capabilities 開發能力
  * Malware 惡意軟體 
  * Code Signing Certificates 程式碼數位憑証簽章
  * Digital Certificates 數位憑證
  * Exploits 漏洞利用
* Establish Accounts 建立帳戶
  * Social Media Accounts 社交媒體帳戶
  * Email Accounts 電子信箱帳戶
* Obtain Capabilities 獲取能力
  * Malware 惡意軟體
  * Tool 工具 
  * Code Signing Certificates 程式碼數位憑証簽章
  * Digital Certificates 數位憑證
  * Exploits 漏洞利用
  * Vulnerabilities 漏洞
* Stage Capabilities 強化能力
  * Upload Malware 上傳惡意軟體
  * Upload Tool 上傳工具
  * Install Digital Certificate 安裝數位憑証
  * Drive-by Target 中間目標
  * Link Target 連結目標
---
3.Initial Access 初期存取
===
* Drive-by Compromise 偷渡式劫持 [水坑攻擊](https://blog.trendmicro.com.tw/?p=4350)
* Exploit Public-Facing Application 利用公開應用程式
* External Remote Services 外部遠端服務
* Hardware Additions 利用硬體入侵
* Phishing 網路釣魚
  * Spearphishing Attachment 魚叉式釣魚附件
  * Spearphishing Link 魚叉式釣魚連結
  * Spearphishing via Service 透過服務魚叉式釣魚
* Replication Through Removable Media 使用移動裝置複製
* Supply Chain Compromise 供應鏈惡意竄改
  * Compromise Software Dependencies and Development Tools  竄改軟體相依性與開發工具
  * Compromise Software Supply Chain 軟體供應鏈惡意竄改
  * Compromise Hardware Supply Chain 硬體供應鏈惡意竄改
* Trusted Relationship 利用信任關係
* Valid Accounts 有效的帳戶
  * Default Accounts 默認帳號
  * Domain Accounts 網域帳號
  * Local Accounts 本地帳號
  * Cloud Accounts 雲端帳號
---
