[MITRE_Attack](https://attack.mitre.org/)
===
* 1.Reconnaissance 偵查
* 2.Resource Development 資源開發戰術
* 3.Initial Access 初期存取
* 4.Execution 執行
* 5.Persistence 持續潛伏
* 6.Privilege Escalation 權限提升
* 7.Defense Evasion 防禦規避
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
  * DLL Search Order Hijacking  劫持DLL檔搜索命令
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
  * TFTP Boot 檔案傳輸通訊協定引導
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
  * DLL Search Order Hijacking DLL搜索命令劫持
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
  * Portable Executable Injection 可移植的可執行文件注入
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
 7.Defense Evasion 防禦規避
 ===
 * Abuse Elevation Control Mechanism 濫用提升控制機制
   * Setuid and Setgid 設置UID 與 設置GID
   * Bypass User Account Control 繞過用戶帳號控制
   * Sudo and Sudo Caching 超級使用者 與 超級使用者緩存
   * Elevated Execution with Prompt 透過提示提升許可權
 * Access Token Manipulation 訪問令牌操作
   * Token Impersonation/Theft 令牌盜用/竊取
   * Create Process with Token 使用令牌創建進程
   * Make and Impersonate Token 製作與模擬令牌
   * Parent PID Spoofing 父進程PID欺騙
   * SID-History Injection 注入SID歷史
 * BITS Jobs 智慧傳輸服務工作 
 * Build Image on Host 在主機上建構映像檔
 * Debugger Evasion 調試器規避
 * Deobfuscate/Decode Files or Information 對檔案或資訊進行反混淆/解碼
 * Deploy Container 部屬容器
 * Direct Volume Access 直接訪問標籤
 * Domain Policy Modification 網域策略修改
   * Group Policy Modification 群組策略修改
   * Domain Trust Modification 網域信任修改
 * Execution Guardrails 執行護欄
   * Environmental Keying 環境鍵控
 * Exploitation for Defense Evasion 利用防禦規避
 * File and Directory Permissions Modification 文件和目錄許可權修改
   * Windows File and Directory Permissions Modification Windows文件和目錄許可權修改
   * Linux and Mac File and Directory Permissions Modification Linux and Mac文件和目錄許可權修改
 * Hide Artifacts 隱藏偽影
   * Hidden Files and Directories 隱藏的檔案和目錄
   * Hidden Users 隱藏使用者
   * Hidden Window 	隱藏視窗
   * NTFS File Attributes NTFS檔案屬性
   * Hidden File System 隱藏檔案系統
   * Run Virtual Instance 運行虛擬實例
   * VBA Stomping VBA踩踏
   * Email Hiding Rules 電子信箱隱藏規則
   * Resource Forking 資源分叉
   * Process Argument Spoofing 進程參數欺騙
 * Hijack Execution Flow 劫持執行流程
   * DLL Search Order Hijacking  DLL搜索命令劫持
   * DLL Side-Loading DLL旁側載入
   * Dylib Hijacking Dylib(惡意程式庫)劫持
   * Executable Installer File Permissions Weakness 可執行安裝程式檔許可權弱點
   * Dynamic Linker Hijacking 動態連結器劫持
   * Path Interception by PATH Environment Variable 路徑環境變數的路徑攔截
   * Path Interception by Search Order Hijacking 通過搜索命令劫持進行路徑攔截
   * Path Interception by Unquoted Path 未加引號路徑的路徑攔截
   * Services File Permissions Weakness 服務文件許可權弱點
   * Services Registry Permissions Weakness 服務註冊表許可權弱點
   * COR_PROFILER 利用COR_PROFILER環境變數來劫持載入
   * KernelCallbackTable 內核回乎表
 * Impair Defenses 損害防禦
   * Disable or Modify Tools 禁用或修改工具
   * Disable Windows Event Logging 禁用windows事件記錄
   * Impair Command History Logging 損害命令列歷史記錄
   * Disable or Modify System Firewall 	禁用或修改系統防火牆
   * Indicator Blocking 指示器阻塞
   * Disable or Modify Cloud Firewall 禁用或修改雲端防火牆
   * Disable Cloud Logs 禁用雲端日誌
   * Safe Mode Boot 安全模式啟動
   * Downgrade Attack 降級攻擊
 * Indicator Removal on Host 	主機上的指示器刪除
   * Clear Windows Event Logs 清除windows事件日誌
   * Clear Linux or Mac System Logs 清除Linux or Mac系統日誌
   * Clear Command History 清除命令列歷史紀錄
   * File Deletion 檔案刪除
   * Network Share Connection Removal 刪除網路共享連接
   * Timestomp 時間戳
 * Indirect Command Execution 間接命令執行
 * Masquerading 偽裝
   * Invalid Code Signature 無效的代碼簽名
   * Right-to-Left Override 從右向左覆蓋
   * Rename System Utilities 重新命名系統實用程式
   * Masquerade Task or Service 偽裝線程或服務
   * Match Legitimate Name or Location 匹配合法名稱或位置
   * Space after Filename 檔名後面的空格
   * Double File Extension 雙檔擴展名
 *	Modify Authentication Process 修改身份驗證過程
    *	Domain Controller Authentication 網域控制器身份驗證
    *	Password Filter DLL 密碼過濾器
    *	Pluggable Authentication Modules 可插拔身份驗證模組
    *	Network Device Authentication 網路設備身份驗證
    *	Reversible Encryption可逆加密
 *	Modify Cloud Compute Infrastructure 	修改雲端計算基礎架構
    *	Create Snapshot 創建快照
    *	Create Cloud Instance 創建雲端實例
    *	Delete Cloud Instance 刪除雲端實例
    *	Revert Cloud Instance 恢復雲端實例
 *	Modify Registry 修改註冊表
 *	Modify System Image 修改系統映像
    * Patch System Image 	修補程式系統映像
    * Downgrade System Image 降級系統映像
 * Network Boundary Bridging 網路邊界橋接
    *	Network Address Translation Traversal 網路位置轉換
 *	Obfuscated Files or Information 混淆檔或資訊
    *	Binary Padding 二進位填充
    *	Software Packing 打包軟體
    *	Steganography 隱寫術
    *	Compile After Delivery 派送後編譯
    *	Indicator Removal from Tools 從工具中刪除指標
    *	HTML Smuggling HTML 走私
 *	Plist File Modification 清單檔案修改
 *	Pre-OS Boot 	操作系統啟動前
    *	System Firmware 系統韌體
    *	Component Firmware 元件韌體
    *	Bootkit 引導套件
    * ROMMONkit  ROM監視器
    * TFTP Boot 檔案傳輸通訊協定引導
 *	Process Injection 進程注入
    *	Dynamic-link Library Injection 動態連結庫注入
    *	Portable Executable Injection 可移植的可執行文件注入
    *	Thread Execution Hijacking 線程執行劫持
    *	Asynchronous Procedure Call 異步過程調用
    *	Thread Local Storage 	線程本地存儲
    *	Ptrace System Calls 跟蹤系統調用
    *	Proc Memory 記憶體歷程
    *	Extra Window Memory Injection EWM式注入
    *	Process Hollowing 傀儡進程
    *	Process Doppelgänging 分身進程
    *	VDSO Hijacking 虛擬動態共享物件劫持
    *	ListPlanting 清單佈局
 *	Reflective Code Loading 反射式代碼載入
 *	Rogue Domain Controller 惡意網域控制器
 *	Rootkit 隱藏其他程式進程的軟體
 *	Subvert Trust Controls 	顛覆信任控制
    *	Gatekeeper Bypass 可繞過Gatekeeper(Mac安全軟體)
    *	Code Signing 代碼簽章
    *	SIP and Trust Provider Hijacking 會話發起協議與信任提供商劫持
    *	Install Root Certificate 安裝root憑證
    *	Mark-of-the-Web Bypass 繞過MoTW檔案類型
    *	Code Signing Policy Modification  代碼簽章策略修改
 *	System Binary Proxy Execution 系統二進位代理執行
    *	Compiled HTML File 已編譯的網頁檔
    *	Control Panel 控制面板
    *	CMSTP 安裝連接管理器服務配置文件的命令行程序
    *	InstallUtil 安裝與卸載命令列公用程式
    *	Mshta Windows操作系統相關程序
    *	Msiexec 系統進程，是Windows Installer的一部分
    *	Odbcconf 命令行工具，可用於配置ODBC 驅動程式與數據源名稱
    *	Regsvcs/Regasm 組件登入工具
    *	Regsvr32 命令行工具，用來註冊COM組件
    *	Rundll32 用來執行32位元的DLL檔
    *	Verclsid Microsoft XP 安全更新程序
    *	Mavinject windwos組件，可在進程運行中做代碼注入
    *	MMC  Microsoft管理主控台
 *	System Script Proxy Execution 系統腳本代理執行
    *	PubPrn PubPrn.vbs 是一個可視化基本腳本
 *	Template Injection 模板注入
 *	Traffic Signaling 交通信號
    *	Port Knocking 端口敲門
 *	Trusted Developer Utilities Proxy Execution 受信任的開發人員實用程式代理執行
    *	MSBuild MSBuild.exe（微軟生成引擎）
 *	Unused/Unsupported Cloud Regions 未使用/不支持的雲端區域
 *	Use Alternate Authentication Material 使用備用身份驗證資訊
    *	Application Access Token 應用程式訪問令牌
    *	Pass the Hash 傳遞哈希值
    *	Pass the Ticket  傳遞票證
    *	Web Session Cookie 網頁會話 Cookie 
 *	Valid Accounts 有效帳號
    *	Default Accounts 默認帳號
    *	Domain Accounts 網域帳號
    *	Local Accounts 本地帳號
    *	Cloud Accounts 雲端帳號
 *	Virtualization/Sandbox Evasion 虛擬化/沙盒規避
    *	System Checks 系統檢查
    *	User Activity Based Checks 	基於用戶活動的檢查
    * Time Based Evasion  	基於時間的規避
 *	Weaken Encryption 削弱加密
    *	Reduce Key Space 減少金鑰空間
    *	Disable Crypto Hardware	禁用加密硬體
 *	XSL Script Processing  XSL檔 腳本處理
 ---
 8.Credential Access	憑證存取
 ====
 * Adversary-in-the-Middle 中間人攻擊
    * LLMNR/NBT-NS Poisoning and SMB Relay  LLMNR/NBT-NS中毒與SMB中繼
    * ARP Cache Poisoning  ARP快取毒化
    * DHCP Spoofing DHCP欺騙
 *	Brute Force 暴力破解
    *	Password Guessing 密碼猜測
    *	Password Cracking 	密碼破解
    *	Password Spraying 密碼噴塗
    *	Credential Stuffing 撞庫
 *	Credentials from Password Stores 密碼庫中的憑證
    *	Keychain 鑰匙串
    *	Securityd Memory 安全記憶體
    *	Credentials from Web Browsers	來自 Web 瀏覽器的憑證
    *	Windows Credential Manager windows憑證管理員
    *	Password Managers 密碼管理員
 *	Exploitation for Credential Access 利用憑證訪問
 *	Forced Authentication	強制身份驗證
 *	Forge Web Credentials 偽造網路憑證
    *	Web Cookies 網頁cookies
    *	SAML Tokens  SAML 令牌簽名證書
 *	Input Capture 輸入捕捉
    *	Keylogging 鍵盤記錄
    *	GUI Input Capture 圖形使用者介面輸入捕捉
    *	Web Portal Capture 入口網站捕捉 
    *	Credential API Hooking 憑證介面掛鉤
 *	Modify Authentication Process 修改身份驗證過程
    *	Domain Controller Authentication 網域控制器身份驗證
    *	Password Filter DLL 密碼過濾器DLL檔 
    *	Pluggable Authentication Modules 可插拔身份驗證模組
    *	Network Device Authentication 驗證網路設備身份
    *	Reversible Encryption 可逆加密
 *	Multi-Factor Authentication Interception 攔截多重身份驗證
 *	Multi-Factor Authentication Request Generation 請求生成多重身份驗證
 *	Network Sniffing  網路嗅探
 *	OS Credential Dumping 作業系統轉儲憑證
    *	LSASS Memory (LSASS)本地安全機構子系統服務 記憶體
    *	Security Account Manager 帳號安全管理源
    *	NTDS 註冊表路徑
    *	LSA Secrets 鏈路狀態通告秘密
    *	Cached Domain Credentials 網域緩存憑證
    *	DCSync 透過DRS向網域發起數據同步請求
    *	Proc Filesystem 進程 文件系統
    *	/etc/passwd and /etc/shadow Linux帳號管理路徑
 *	Steal Application Access Token 竊取應用程式訪問令牌
 *	Steal or Forge Kerberos Tickets 竊取或鍛造Kerberos票證
    *	Golden Ticket 黃金票證
    *	Silver Ticket 銀票正
    *	Kerberoasting 是一種在請求訪問時利用Kerberos協議中弱點的技術
    *	AS-REP Roasting 對用戶帳號進行離線爆破的攻擊方式
 *	Steal Web Session Cookie 竊取網頁會話cookie
 *	Unsecured Credentials	不安全的憑據
    * Credentials In Files 檔中的憑證
    * Credentials in Registry 註冊表中的憑證
    * Bash History 命令處理器歷史紀錄
    * Private Keys 私人密鑰
    * Cloud Instance Metadata API 雲端實例元數據介面
    * Group Policy Preferences 組組策略首選
    * Container API 容器介面
   ---	
9.Discovery 發現
===
* Account Discovery 帳號發現
  * Local Account 本地帳號
  * Domain Account 網域帳號
  * Email Account 電子信箱帳號
  * Cloud Account 雲端帳號
* Application Window Discovery Windows應用程式發現
* Browser Bookmark Discovery 瀏覽器書籤發現 
* Cloud Infrastructure Discovery 雲端基礎設備發現
* Cloud Service Dashboard 雲端服務儀表板
* Cloud Service Discovery 雲端服務發現
* Cloud Storage Object Discovery 雲端儲存物件發現
* Container and Resource Discovery 容器和資源發現
* Debugger Evasion 調試器規避
* Domain Trust Discovery 網域信任發現
* File and Directory Discovery 檔案與目錄發現
* Group Policy Discovery 群組政策發現
* Network Service Discovery 網路服務發現
* Network Share Discovery 網路共享發現
* Network Sniffing 網路嗅探
* Password Policy Discovery 密碼策略發現
*	Peripheral Device Discovery 外圍設備發現
*	Permission Groups Discovery 許可權組發現
    *	Local Groups  本地群組
    *	Domain Groups 網域群組
    *	Cloud Groups 雲端群組
*	Process Discovery 進程發現	
*	Query Registry 	查詢註冊表
*	Remote System Discovery 遠端系統發現
*	Software Discovery 軟體發現
    *	Security Software Discovery 安全軟體發現
*	System Information Discovery 系統信息發現
*	System Location Discovery 系統位置發現
    *	System Language Discovery 系統語言發現
*	System Network Configuration Discovery 系統網路配置發現
    *	Internet Connection Discovery 互聯網連接發現
*	System Network Connections Discovery 系統網路連接發現
*	System Owner/User Discovery 系統擁有者/用戶發現
*	System Service Discovery 系統服務發現
*	System Time Discovery 系統時間發現
*	Virtualization/Sandbox Evasion 虛擬化/沙箱規避
    *	System Checks 	系統檢查
    *	User Activity Based Checks 基於用戶活動的檢查
    *	Time Based Evasion 	基於時間的規避
---
 10.Lateral Movement	橫向移動
===
* Exploitation of Remote Services 利用遠端服務
* Internal Spearphishing 內部魚叉式網路釣魚
* Lateral Tool Transfer 橫向工具轉移
* Remote Service Session Hijacking 遠端服務會話劫持
  * SSH Hijacking Secure Shell劫持
  * RDP Hijacking 遠端桌面協定(RDP)劫持
* Remote Services 遠端服務
  * Remote Desktop Protocol 遠端桌面協定
  * SMB/Windows Admin Shares 伺服器消息塊(SMB)/windows管理員共享
  * Distributed Component Object Model 分散式元件物件模型
  * SSH Secure Shell一種加密的網路傳輸協定
  * VNC  RFB協定的螢幕畫面分享及遠端操作軟體
  * Windows Remote Management windows遠端管理
* Replication Through Removable Media 通過可移動媒體複製
* Software Deployment Tools 軟體部署工具
* Taint Shared Content 污點共享內容
* Use Alternate Authentication Material 使用備用驗證身分資訊
  * Application Access Token 應用程式認證令牌
  * Pass the Hash 透過哈希值
  * Pass the Ticket 透過票根
  * Web Session Cookie 網頁會話cookie
 ---		
11.Collection 收集
===
* Adversary-in-the-Middle 中間人攻擊
   * LLMNR/NBT-NS Poisoning and SMB Relay  LLMNR/NBT-NS中毒與SMB中繼
   * ARP Cache Poisoning ARP快取毒化
   * DHCP Spoofing DHCP欺騙
* Archive Collected Data 收集檔案數據
   * Archive via Utility 通過實用程式存檔
   * Archive via Library 通過函式庫存檔
   * Archive via Custom Method 通過自定義方法存檔
* Audio Capture 音訊捕捉
*	Automated Collection 自動化收集
*	Browser Session Hijacking 瀏覽器會話劫持
*	Clipboard Data 剪貼簿數據
*	Data from Cloud Storage Object 來自雲端儲存的數據 
*	Data from Configuration Repository 來自組態儲存庫的數據
    *	SNMP (MIB Dump) 簡單網路管理協定/管理資訊庫 （MIB）
    *	Network Device Configuration Dump 網路設備組態轉儲
*	Data from Information Repositories 來自資訊儲存庫的數據
    *	Confluence 合流
    *	Sharepoint 共享點
    *	Code Repositories 程式碼儲存庫
*	Data from Local System 來自本地系統的數據
*	Data from Network Shared Drive 來自網路共享驅動的數據
*	Data from Removable Media 	來自可移動媒體的數據
*	Data Staged 暫存數據 
    *	Local Data Staging  本地數據暫存 
    *	Remote Data Staging 遠端數據暫存
*	Email Collection 	電子郵件收藏
    *	Local Email Collection 本地電子郵件收藏
    *	Remote Email Collection 遠端電子郵件收藏
    *	Email Forwarding Rule 電子信箱轉發規則
*	Input Capture 輸入捕捉
    *	Keylogging 鍵盤記錄
    *	GUI Input Capture 圖形使用者介面輸入捕捉
    *	Web Portal Capture 網頁入口捕捉
    *	Credential API Hooking 憑據介面掛鉤
*	Screen Capture 螢幕捕捉
*	Video Capture 影片捕捉
---
 12.Command and Control 命令與控制
 ===
 * Application Layer Protocol 應用層協定
   * Web Protocols 網路協定
   * File Transfer Protocols 	檔案傳輸協定
   * Mail Protocols 電子郵件協定
   * DNS 網域名稱系統
 * Communication Through Removable Media 通過可移動媒體進行通信
 * Data Encoding 數據編碼
     * Standard Encoding 標準編碼
     * Non-Standard Encoding 非標準編碼
 * Data Obfuscation 數據混淆
     * Junk Data 垃圾數據 
     * Steganography 隱寫術
     * Protocol Impersonation 類比協定
 * Dynamic Resolution 動態解析
     * Fast Flux DNS 快速通量網域名稱系統
     * Domain Generation Algorithms 網域生成演算法
     * DNS Calculation 網域名稱系統計算
 * Encrypted Channel 加密通道
     * Symmetric Cryptography  對稱加密
     * Asymmetric Cryptography 非對稱加密
 * Fallback Channels 倒退通道
 * Ingress Tool Transfer 入口傳輸工具
 *	Multi-Stage Channels 多級通道
 *	Non-Application Layer Protocol 非應用層協定
 *	Non-Standard Port 非標準埠
 *	Protocol Tunneling 協定隧道
 *	Proxy 代理
     * Internal Proxy 	內部代理
     * External Proxy 外部代理
     * Multi-hop Proxy 多跳代理
     * Domain Fronting 網域名稱前置
 *	Remote Access Software 遠端存取軟體
 *	Traffic Signaling 交通信號
     *	Port Knocking 敲端口
 *	Web Service 網路服務
     *	Dead Drop Resolver 死投解析器
     *	Bidirectional Communication 雙向通訊
     *	One-Way Communication 單向通訊
 ---
 13.Exfiltration 滲漏
 ===
* Automated Exfiltration 自動滲漏
     * Traffic Duplication  流量重複
* Data Transfer Size Limits 	傳輸數據大小限制
* Exfiltration Over Alternative Protocol 通過替代協議進行滲漏
     * Exfiltration Over Symmetric Encrypted Non-C2 Protocol 通過對稱加密非 C2 協議進行外洩
     * Exfiltration Over Asymmetric Encrypted Non-C2 Protocol 	通過非對稱加密非 C2 協議進行外洩
     * Exfiltration Over Unencrypted Non-C2 Protocol 通過未加密的非 C2 協議進行外洩
* Exfiltration Over C2 Channel  	通過 C2 通道滲出
* Exfiltration Over Other Network Medium 通過其他網路媒介滲漏
    * Exfiltration Over Bluetooth 通過藍牙滲漏
*	Exfiltration Over Physical Medium 	物理介質外滲
    *	Exfiltration over USB 透過USB進行滲漏
*	Exfiltration Over Web Service 通過 Web 服務進行外洩
    *	Exfiltration to Code Repository 滲漏到代碼存儲庫
    *	Exfiltration to Cloud Storage 滲透到雲端存儲
*	Scheduled Transfer 定期接送
*	Transfer Data to Cloud Account 將數據傳輸到雲端帳戶
 
 ---
 14.Impact 衝擊
 ===
* Account Access Removal 	帳戶訪問刪除
* Data Destruction 數據銷毀
* Data Encrypted for Impact 數據經過加密以產生衝擊
* Data Manipulation 數據操縱
   * Stored Data Manipulation 存儲的數據操縱
   * Transmitted Data Manipulation 傳輸數據操縱
   *	Runtime Data Manipulation  運行時數據操縱
* Defacement 竄改
   * Internal Defacement 內部竄改
   * External Defacement 外部竄改
* Disk Wipe 硬碟抹除
   *	Disk Content Wipe 磁碟內容抹除
   *	Disk Structure Wipe  磁碟結構抹除
* Endpoint Denial of Service 	端點拒絕服務
   * OS Exhaustion Flood 作業系統資源氾濫
   * Service Exhaustion Flood 服務資源氾濫
   * Application Exhaustion Flood 應用程式資源氾濫
   * Application or System Exploitation 應用程式或系統開發
* Firmware Corruption 韌體損壞
* Inhibit System Recovery 關閉系統恢復
* Network Denial of Service 網路拒絕服務
  * Direct Network Flood 	直接網路流量氾濫
  * Reflection Amplification 放大反射
* Resource Hijacking 資源劫持
* Service Stop 停止服務
* System Shutdown/Reboot 系統關閉/重啟
 ---
