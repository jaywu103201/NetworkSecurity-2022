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
4.Execution 執行
===
* Command and Scripting Interpreter 命令與腳本解譯器
  * PowerShell 
  * AppleScript	
  * Windows Command Shell
  * Unix Shell
  * Visual Basic
  * Python
  * JavaScript
  * Network Device CLI 
* Container Administration Command 容器管理命令
* Deploy Container 部屬容器
* Exploitation for Client Execution 利用客戶端執行
* Inter-Process Communication  行程間通訊
  * Component Object Model 組件對象模型
  * Dynamic Data Exchange 動態數據交換
  * XPC Services 管理安全的進程間通訊 服務
* Native API 原生API
* Scheduled Task/Job 工作排程器
  * At [海斯命令集](https://zh.m.wikipedia.org/zh-tw/%E6%B5%B7%E6%96%AF%E5%91%BD%E4%BB%A4%E9%9B%86)
  * Cron [任務管理系統](https://zh.wikipedia.org/zh-tw/Cron)
  * Scheduled Task 工作排程器
  * Systemd Timers 系統計時器
  * Container Orchestration Job 容器編排作業
* Shared Modules 共享模組
* Software Deployment Tools 軟體部署工具
* System Services 系統服務
  * Launchctl 管理系統的啟動腳本
  * Service Execution 執行服務
* User Execution 用戶執行
  * Malicious Link 惡意連結
  * Malicious File 惡意檔案
  * Malicious Image 惡意圖片
* Windows Management Instrumentation Windows管理規範
---
5.Persistence 持續潛伏
===
* Account Manipulation
  * Additional Cloud Credentials
  * Additional Email Delegate Permissions
  * Additional Cloud Roles
  * SSH Authorized Keys
  * Device Registration
* BITS Jobs
* Boot or Logon Autostart Execution
  * Registry Run Keys / Startup Folder
  * Authentication Package
  * Time Providers
  * Winlogon Helper DLL
  * Security Support Provider
  * Kernel Modules and Extensions
  * Re-opened Applications
  * LSASS Driver
  * Shortcut Modification
  * Port Monitors
  * Print Processors
  * XDG Autostart Entries
  * Active Setup
  * Login Items	
* Boot or Logon Initialization Scripts
  * Logon Script (Windows)
  * Login Hook
  * Network Logon Script
  * RC Scripts
  * Startup Items
* Browser Extensions
* Compromise Client Software Binary
* Create Account
  * Local Account
  * Domain Account
  * Cloud Account
* Create or Modify System Process
  * Launch Agent
  * Systemd Service
  * Windows Service
  * Launch Daemon
* Event Triggered Execution
  * Change Default File Association
  * Screensaver
  * Windows Management Instrumentation Event Subscription
  * Unix Shell Configuration Modification
  * Trap
  * LC_LOAD_DYLIB Addition
  * Netsh Helper DLL
  * Accessibility Features
  * AppCert DLLs
  * AppInit DLLs
  * Application Shimming
  * Image File Execution Options Injection
  * PowerShell Profile
  * Emond
  * Component Object Model Hijacking
* External Remote Services
* Hijack Execution Flow
  * DLL Search Order Hijacking
  * DLL Side-Loading
  *	Dylib Hijacking
  *	Executable Installer File Permissions Weakness
  *	Dynamic Linker Hijacking
  *	Path Interception by PATH Environment Variable
  *	Path Interception by Search Order Hijacking
  *	Path Interception by Unquoted Path
  *	Services File Permissions Weakness
  *	Services Registry Permissions Weakness
  *	COR_PROFILER
  *	KernelCallbackTable
* Implant Internal Image	
* Modify Authentication Process
  * Domain Controller Authentication
  * Password Filter DLL
  * Pluggable Authentication Modules
  * Network Device Authentication
  * Reversible Encryption
* Office Application Startup
  * Office Template Macros
  * Office Test
  * Outlook Forms
  * Outlook Home Page
  * Outlook Rules
  * Add-ins
* Pre-OS Boot
  * System Firmware
  * Component Firmware
  * Bootkit
  * ROMMONkit
  * TFTP Boot
* Scheduled Task/Job
  * At
  * Cron
  * Scheduled Task
  * Systemd Timers
  * Container Orchestration Job	
* Server Software Component
  * SQL Stored Procedures
  * Transport Agent
  * Web Shell
  * IIS Components
  * Terminal Services DLL
* Traffic Signaling
  * Port Knocking
* Valid Accounts
  * Default Accounts
  * Domain Accounts
  * Local Accounts
  * Cloud Accounts
