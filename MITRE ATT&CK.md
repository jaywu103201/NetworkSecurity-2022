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
  * At 在系統上指定時間運行
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
* Account Manipulation 帳戶操縱
  * Additional Cloud Credentials 添加雲端憑證
  * Additional Email Delegate Permissions 添加電子信箱委託權限
  * Additional Cloud Roles 添加雲端角色
  * SSH Authorized Keys SSH授權密碼
  * Device Registration 裝置註冊
* BITS Jobs 後台智能傳輸服務
* Boot or Logon Autostart Execution 啟動或登入開始自動執行
  * Registry Run Keys / Startup Folder 註冊表運行鍵/啟動資料夾
  * Authentication Package 用戶認證包
  * Time Providers 時間提供者
  * Winlogon Helper DLL 安全相關用戶交互介面
  * Security Support Provider 安全支援供應商
  * Kernel Modules and Extensions 內核模組與擴展
  * Re-opened Applications 重新開放應用程式
  * LSASS Driver LSASS驅動
  * Shortcut Modification 快捷鍵修改
  * Port Monitors 端口監視器
  * Print Processors 影印處理器
  * XDG Autostart Entries XDG自動啟動項目
  * Active Setup 主動設置
  * Login Items 登入項目
* Boot or Logon Initialization Scripts 引導或登入初始化腳本 
  * Logon Script (Windows) 登入腳本
  * Login Hook 登陸掛勾
  * Network Logon Script 網路登入腳本 
  * RC Scripts 遙控腳本
  * Startup Items 啟動項目
* Browser Extensions 瀏覽器擴展
* Compromise Client Software Binary 竄改客戶端軟體二進制
* Create Account 創立帳號
  * Local Account 本地帳號
  * Domain Account 網域帳號
  * Cloud Account 雲端帳號
* Create or Modify System Process 創立或修改系統進程
  * Launch Agent 啟動代理
  * Systemd Service 系統化服務
  * Windows Service windosw服務
  * Launch Daemon 啟動守護進程
* Event Triggered Execution 事件觸發執行
  * Change Default File Association 更改默認關聯文件
  * Screensaver 螢幕保護
  * Windows Management Instrumentation Event Subscription 訂閱windows管理事件規範
  * Unix Shell Configuration Modification Unix Shlee配置修改
  * Trap 陷阱
  * LC_LOAD_DYLIB Addition 注入LC_LOAD_DYLIB
  * Netsh Helper DLL 網路配置命令工具
  * Accessibility Features 輔助功能
  * AppCert DLLs 注入AppCert DLLs 註冊表項
  * AppInit DLLs 注入AppInit DLLs 註冊表項
  * Application Shimming 應用程式填充
  * Image File Execution Options Injection 圖像檔執行選項注入
  * PowerShell Profile PowerShell設定檔
  * Emond 事件監視程式守護程式 （emond）
  * Component Object Model Hijacking 劫持組件對象模型
* External Remote Services 外部遠程服務
* Hijack Execution Flow 劫持執行流程
  * DLL Search Order Hijacking 劫持DLL檔搜尋目錄
  * DLL Side-Loading DLL旁側載入
  *	Dylib Hijacking 劫持 dylib(惡意程式庫)
  *	Executable Installer File Permissions Weakness 可執行安裝檔案權限弱點
  *	Dynamic Linker Hijacking 劫持動態連結
  *	Path Interception by PATH Environment Variable 環境變數的路徑攔截
  *	Path Interception by Search Order Hijacking 通過搜索命令劫持路徑攔截
  *	Path Interception by Unquoted Path 未引用的路徑攔截
  *	Services File Permissions Weakness 服務文件許可權弱點
  *	Services Registry Permissions Weakness 服務註冊表許可權弱點
  *	COR_PROFILER 利用COR_PROFILER環境變數來劫持載入
  *	KernelCallbackTable 內核回乎表 
* Implant Internal Image 注入圖片內部
* Modify Authentication Process 修改身分驗證過程
  * Domain Controller Authentication 網域控制身分驗證
  * Password Filter DLL 密碼過濾器DLL檔
  * Pluggable Authentication Modules 可插拔身分驗證模組
  * Network Device Authentication 網路裝置身分驗證
  * Reversible Encryption 可逆加密
* Office Application Startup Office 應用程式啟動
  * Office Template Macros Office模板巨集
  * Office Test office 測試
  * Outlook Forms Outlook 表格
  * Outlook Home Page outlook 首頁
  * Outlook Rules outlook規則
  * Add-ins 加載項
* Pre-OS Boot 作業系統啟動前
  * System Firmware 系統韌體 
  * Component Firmware 元件韌體
  * Bootkit 引導套件
  * ROMMONkit  ROM監視器
  * TFTP Boot 網路引導
* Scheduled Task/Job 工作排程器
  * At 用於在指定的時間和日期計劃任務
  * Cron Unix 作業系統的基於時間的作業調度程式
  * Scheduled Task 工作排程器
  * Systemd Timers 系統定時器
  * Container Orchestration Job 容器編排作業	
* Server Software Component 伺服器軟體元件
  * SQL Stored Procedures SQL儲存過程
  * Transport Agent 傳輸代理
  * Web Shell 在網頁上執行Shell
  * IIS Components IIS元件 
  * Terminal Services DLL 終端服務DLL檔
* Traffic Signaling 交通號誌
  * Port Knocking 端口敲門
* Valid Accounts 有效帳號
  * Default Accounts 默認帳號 
  * Domain Accounts 網域帳號
  * Local Accounts 本地帳號
  * Cloud Accounts 雲端帳號
---
6.Privilege Escalation 權限提升
===
* Abuse Elevation Control Mechanism 濫用提升控制機制
  * Setuid and Setgid 設置UID與設置GID
  * Bypass User Account Control 繞過使用者帳號控制
  * Sudo and Sudo Caching 超級使用者與超級使用者緩存
  * Elevated Execution with Prompt 通過提示提升執行力
* Access Token Manipulation 訪問令牌操作
  * Token Impersonation/Theft 令牌冒用/偷竊
  * Create Process with Token 使用令牌建立行程
  * Make and Impersonate Token 製作與模擬令牌
  * Parent PID Spoofing 父進程PID欺騙
  * SID-History Injection 注入SID歷史
* Boot or Logon Autostart Execution 引導或登錄自動啟動執行
  * Registry Run Keys / Startup Folder註冊表運行鍵/啟動資料夾
  * Authentication Package 用戶認證包
  * Time Providers 時間提供者
  * Winlogon Helper DLL 安全相關用戶交互介面
  * Security Support Provider 安全支援供應商 
  * Kernel Modules and Extensions 內核模組與擴展
  * Re-opened Applications 重新開放應用程式
  * LSASS Driver LSASS驅動
  * Shortcut Modification 快捷鍵修改 
  * Port Monitors 端口監視器
  * Print Processors 影印處理器 
  * XDG Autostart Entries XDG自動啟動項目
  * Active Setup  主動設置
  * Login Items 登入項目
* Boot or Logon Initialization Scripts 引導或登錄初始化腳本
  * Logon Script (Windows) 登入腳本
  * Login Hook 登陸掛勾
  * Network Logon Script	網路登入腳本
  * RC Scripts 遙控腳本 
  * Startup Items 啟動項目 
* Create or Modify System Process 創建或修改系統進程
  * Launch Agent 啟動代理 
  * Systemd Service 系統化服務
  * Windows Service windwos服務
  * Launch Daemon 啟動守護進程
* Domain Policy Modification 網域策略修改
  * Group Policy Modification 群組策略修改
  * Domain Trust Modification 網域信任修改
* Escape to Host 從主機逃離
* Event Triggered Execution 事件觸發執行
  * Change Default File Association 更改默認文件關聯
  * Screensaver 螢幕保護程式
  * Windows Management Instrumentation Event Subscription 訂閱windows 管理規範
  * Unix Shell Configuration Modification Unix Shell 配置修改
  * Trap 陷阱
  * LC_LOAD_DYLIB Addition 注入LC_LOAD_DYLIB
  * Netsh Helper DLL  Netsh 説明程式 DLL
  * Accessibility Features 輔助功能
  * AppCert DLLs 注入AppCert DLLs 註冊表項
  * AppInit DLLs AppInit DLLs 註冊表項
  * Application Shimming 應用程式填充
  * Image File Execution Options Injection 圖像檔執行選項注入
  * PowerShell Profile PowerShell配置檔
  * Emond 事件監視程式守護程式 （emond）
  * Component Object Model Hijacking 元件物件模型劫持
* Exploitation for Privilege Escalation 利用漏洞進行特權提升
* Hijack Execution Flow 劫持執行流程
  * DLL Search Order Hijacking DLL搜尋目錄劫持
  * DLL Side-Loading DLL旁側載入
  * Dylib Hijacking Dylib(惡意動態庫)劫持
  * Executable Installer File Permissions Weakness 可執行安裝程式檔許可權弱點
  * Dynamic Linker Hijacking 動態連結劫持
  * Path Interception by PATH Environment Variable 路徑環境變數的路徑攔截
  * Path Interception by Search Order Hijacking 通過搜索命令劫持進行路徑攔截
  * Path Interception by Unquoted Path 未加引號路徑的路徑攔截
  * Services File Permissions Weakness 服務文件許可權弱點
  * Services Registry Permissions Weakness 服務註冊表許可權弱點
  * COR_PROFILER 利用COR_PROFILER環境變數來劫持載入
  * KernelCallbackTable 內核回函表
* Process Injection 進程注入
  * Dynamic-link Library Injection 動態連結庫注入
  * Portable Executable Injection 可移植可執行注入
  * Thread Execution Hijacking 線程執行劫持
  * Asynchronous Procedure Call 異步過程調用
  * Thread Local Storage 線程本地存儲
  * Ptrace System Calls 跟蹤系統調用
  * Proc Memory 記憶歷程
  * Extra Window Memory Injection EWM式注入
  * Process Hollowing 創建傀儡進程
  *	Process Doppelgänging 創建分身進程
  *	VDSO Hijacking 虛擬動態共享物件劫持
  * ListPlanting 清單佈局
* Scheduled Task/Job 工作排程器
  * At 用於在指定的時間和日期計劃任務
  * Cron 作業系統的基於時間的作業調度程式
  * Scheduled Task 工作排程器
  * Systemd Timers 系統定時器 
  * Container Orchestration Job 容器編排作業
* Valid Accounts 有效帳號
  * Default Accounts 默認帳號
  * Domain Accounts 網域帳號
  * Local Accounts 本地帳號
  * Cloud Accounts 雲端帳號
  ---
 7.Defense Evasion 防禦逃脫
 ===
 * Abuse Elevation Control Mechanism
   * Setuid and Setgid
   * Bypass User Account Control
   * Sudo and Sudo Caching
   * Elevated Execution with Prompt
 * Access Token Manipulation
   * Token Impersonation/Theft
   * Create Process with Token
   * Make and Impersonate Token
   * Parent PID Spoofing
   * SID-History Injection
 * BITS Jobs
 * Build Image on Host
 * Debugger Evasion
 * Deobfuscate/Decode Files or Information
 * Deploy Container
 * Direct Volume Access
 * Domain Policy Modification	
   * Group Policy Modification
   * Domain Trust Modification
 * Execution Guardrails
   * Environmental Keying
 * Exploitation for Defense Evasion
 * File and Directory Permissions Modification
   * Windows File and Directory Permissions Modification
   * Linux and Mac File and Directory Permissions Modification
 * Hide Artifacts
   * Hidden Files and Directories
   * Hidden Users
   * Hidden Window
   * NTFS File Attributes
   * Hidden File System
   * Run Virtual Instance
   * VBA Stomping
   * Email Hiding Rules
   * Resource Forking
   * Process Argument Spoofing 
 * Hijack Execution Flow
   * DLL Search Order Hijacking
   * DLL Side-Loading
   * Dylib Hijacking
   * Executable Installer File Permissions Weakness
   * Dynamic Linker Hijacking
   * Path Interception by PATH Environment Variable
   * Path Interception by Search Order Hijacking
   * Path Interception by Unquoted Path
   * Services File Permissions Weakness
   * Services Registry Permissions Weakness
   * COR_PROFILER
   * KernelCallbackTable
 * Impair Defenses
   * Disable or Modify Tools
   * Disable Windows Event Logging
   * Impair Command History Logging
   * Disable or Modify System Firewall
   * Indicator Blocking
   * Disable or Modify Cloud Firewall
   * Disable Cloud Logs
   * Safe Mode Boot
   * Downgrade Attack
 * Indicator Removal on Host
   * Clear Windows Event Logs
   * Clear Linux or Mac System Logs
   * Clear Command History
   * File Deletion
   * Network Share Connection Removal
   * Timestomp 
 * Indirect Command Execution
 * Masquerading
   * Invalid Code Signature
   * Right-to-Left Override
   * Rename System Utilities
   * Masquerade Task or Service
   * Match Legitimate Name or Location
   * Space after Filename
   * Double File Extension
 *	Modify Authentication Process
    *	Domain Controller Authentication
    *	Password Filter DLL
    *	Pluggable Authentication Modules
    *	Network Device Authentication
    *	Reversible Encryption
 *	Modify Cloud Compute Infrastructure
    *	Create Snapshot
    *	Create Cloud Instance
    *	Delete Cloud Instance
    *	Revert Cloud Instance
 *	Modify Registry
 *	Modify System Image
    * Patch System Image
    * Downgrade System Image
    * Network Boundary Bridging
    *	Network Address Translation Traversal
 *	Obfuscated Files or Information
    *	Binary Padding
    *	Software Packing
    *	Steganography
    *	Compile After Delivery
    *	Indicator Removal from Tools
    *	HTML Smuggling
 *	Plist File Modification
 *	Pre-OS Boot
    *	System Firmware
    *	Component Firmware
    *	Bootkit
    * ROMMONkit
    * TFTP Boot
 *	Process Injection
    *	Dynamic-link Library Injection
    *	Portable Executable Injection	
    *	Thread Execution Hijacking
    *	Asynchronous Procedure Call
    *	Thread Local Storage
    *	Ptrace System Calls
    *	Proc Memory
    *	Extra Window Memory Injection
    *	Process Hollowing
    *	Process Doppelgänging
    *	VDSO Hijacking
    *	ListPlanting
 *	Reflective Code Loading
 *	Rogue Domain Controller
 *	Rootkit
 *	Subvert Trust Controls
    *	Gatekeeper Bypass
    *	Code Signing
    *	SIP and Trust Provider Hijacking
    *	Install Root Certificate
    *	Mark-of-the-Web Bypass
    *	Code Signing Policy Modification 
 *	System Binary Proxy Execution
    *	Compiled HTML File
    *	Control Panel
    *	CMSTP
    *	InstallUtil
    *	Mshta
    *	Msiexec
    *	Odbcconf
    *	Regsvcs/Regasm
    *	Regsvr32
    *	Rundll32
    *	Verclsid
    *	Mavinject
    *	MMC
 *	System Script Proxy Execution
    *	PubPrn
 *	Template Injection
 *	Traffic Signaling
    *	Port Knocking
 *	Trusted Developer Utilities Proxy Execution
    *	MSBuild
 *	Unused/Unsupported Cloud Regions
 *	Use Alternate Authentication Material
    *	Application Access Token
    *	Pass the Hash
    *	Pass the Ticket
    *	Web Session Cookie
 *	Valid Accounts
    *	Default Accounts
    *	Domain Accounts
    *	Local Accounts
    *	Cloud Accounts
 *	Virtualization/Sandbox Evasion
    *	System Checks
    *	User Activity Based Checks
    * Time Based Evasion 
 *	Weaken Encryption
    *	Reduce Key Space
    *	Disable Crypto Hardware	
 *	XSL Script Processing
