[D3FEND™](https://d3fend.mitre.org/)
==
* 1.Harden 強化
* 2.Detect 檢測
* 3.Isolate 隔離
* 4.Deceive 欺騙
* 5.Evict 逐出


1.Harden
==
* Application Hardening 應用程式強化
   * Application Configuration Hardening 應用程式組態強化
   * Dead Code Elimination 死碼消除
   * Exception Handler Pointer Validation 異常處理程式指標驗證
   * Pointer Authentication 指標身份驗證
   * Process Segment Execution Prevention 進程分段執行預防
   * Segment Address Offset Randomization 分段位址偏移隨機化
   * Stack Frame Canary Validation 堆疊框架金絲雀驗證
* Credential Hardening 憑證強化
   * Biometric Authentication 生物認證
   * Certificate-based Authentication 基於憑證的身份驗證
   * Certificate Pinning 憑證固定
   * Credential Transmission Scoping 憑證傳輸範圍
   * Domain Trust Policy 網域信任策略
   * Multi-factor Authentication 多重身份驗證
   * One-time Password 一次性密碼
   * Strong Password Policy 強化密碼策略
   * User Account Permissions 用戶帳戶許可權
* Message Hardening 訊息強化
   * Message Authentication 訊息身份驗證
   * Message Encryption 郵件加密
   * Transfer Agent Authentication 傳輸代理身份驗證
* Platform Hardening 平台強化
    * Bootloader Authentication 引導載入程式身份驗證
    * Disk Encryption 磁碟加密
    * Driver Load Integrity Checking 驅動程式負載完整性檢查
    * File Encryption 檔案加密 
    * Local File Permissions 本地檔案許可權 
    * RF Shielding 射頻遮罩
    * Software Update 軟體升級
    * System Configuration Permissions 系統配置許可權
    * TPM Boot Integrity TPM引導完整性
---
2.Detect 檢測
==
* File Analysis 檔案分析
    * Dynamic Analysis 動態分析
    * Emulated File Analysis 模擬檔案分析
    * File Content Rules 檔案內容規則
    * File Hashing 檔案哈希
* Identifier Analysis 標識碼分析
    * Homoglyph Detection 同形字檢測
    * URL Analysis 網址分析
* Message Analysis 訊息分析
    * Sender MTA Reputation Analysis 寄件者 MTA 信譽分析
    * Sender Reputation Analysis 寄件人信譽分析
* Network Traffic Analysis 網路流量分析
    * Administrative Network Activity Analysis 管理網路活動分析
    * Byte Sequence Emulation 位元組序列模擬
    * Certificate Analysis 憑證分析
    * Active Certificate Analysis 活動憑證分析
    * Passive Certificate Analysis 被動憑證分析
    * Client-server Payload Profiling 用戶端-伺服器有效負載分析
    * Connection Attempt Analysis 嘗試連接分析
    * DNS Traffic Analysis 網域名稱系統流量分析
    * File Carving  檔案雕刻
    * Inbound Session Volume Analysis 入站會話量分析
    * IPC Traffic Analysis 行程間通訊流量分析
    * Network Traffic Community Deviation 社區網路流量偏差
    * Per Host Download-Upload Ratio Analysis 每主機下載-上傳比率分析
    * Protocol Metadata Anomaly Detection 協定元數據異常檢測
    * Relay Pattern Analysis 中繼模式分析
    * Remote Terminal Session Detection 遠端終端會話檢測
    * RPC Traffic Analysis 流量分析
* Platform Monitoring
    * Firmware Behavior Analysis 韌體行為分析
    * Firmware Embedded Monitoring Code 韌體嵌入式監控代碼
    * Firmware Verification 韌體驗證
    * Peripheral Firmware Verification 外設韌體驗證
    * System Firmware Verification 系統韌體驗證
    * Operating System Monitoring 操作系統監控
    * Endpoint Health Beacon 端點健康信標
    * Input Device Analysis 輸入設備分析
    * Memory Boundary Tracking 記憶體邊界追蹤
    * Scheduled Job Analysis 計劃作業分析
    * System Daemon Monitoring 系統守護程式監視
    * System File Analysis 系統檔分析
    * Service Binary Verification 服務二進位驗證
    * System Init Config Analysis 系統初始化配置分析
    * User Session Init Config Analysis 用戶會話初始化配置分析
* Process Analysis 進程分析
    * Database Query String Analysis 資料庫查詢字串分析
    * File Access Pattern Analysis 檔案訪問模式分析
    * Indirect Branch Call Analysis 間接分支調用分析
    * Process Code Segment Verification 進程代碼線段驗證
    * Process Self-Modification Detection 進程自修改檢測
    * Process Spawn Analysis 進程生成分析
    * Process Lineage Analysis 進程血緣分析
    * Script Execution Analysis 腳本執行分析
    * Shadow Stack Comparisons 影子堆疊比對
    * System Call Analysis 系統調用分析
    * File Creation Analysis 檔案創建分析
* User Behavior Analysis 使用者行為分析
    * Authentication Event Thresholding 身份驗證事件二質化
    * Authorization Event Thresholding 授權事件閾值
    * Credential Compromise Scope Analysis 憑證危害範圍分析
    * Domain Account Monitoring 網域帳戶監視
    * Job Function Access Pattern Analysis 工作函式訪問模式分析
    * Local Account Monitoring 本地帳戶監控
    * Resource Access Pattern Analysis 資源訪問模式分析
    * Session Duration Analysis 會話持續時間分析
    * User Data Transfer Analysis 用戶數據傳輸分析
    * User Geolocation Logon Pattern Analysis 使用者地理位置登錄模式分析
    * Web Session Activity Analysis 網路會話活動分析
---
3.Isolate 隔離
===
* Execution Isolation 執行隔離
    * Executable Allowlisting 可執行白名單
    * Executable Denylisting 可執行檔案拒絕清單
    * Hardware-based Process Isolation 基於硬體的進程隔離
    * IO Port Restriction IO 埠限制
    * Kernel-based Process Isolation 基於內核的進程隔離
    * Mandatory Access Control 強制訪問控制
    * System Call Filtering 系統呼叫過濾
* Network Isolation 網路隔離
    * Broadcast Domain Isolation 廣播網域隔離
    * DNS Allowlisting 網域名稱系統允許清單
    * DNS Denylisting 網域名稱系統拒絕清單
    * Forward Resolution Domain Denylisting 轉發解析網域拒絕清單
    * Hierarchical Domain Denylisting 分層網域拒絕清單
    * Homoglyph Denylisting 同形字詞否定清單
    * Forward Resolution IP Denylisting 轉發解析IP拒絕清單
    * Reverse Resolution IP Denylisting 反向解析IP拒絕清單
    * Encrypted Tunnels 加密通道 
    * Network Traffic Filtering 網路流量過濾
    * Inbound Traffic Filtering 入站流量篩選
    * Outbound Traffic Filtering 出站流量過濾
---
4.Deceive 欺騙
===
* Decoy Environment 誘餌環境
    * Connected Honeynet 互聯蜜網
    * Integrated Honeynet 集成蜜網
    * Standalone Honeynet 獨立蜜網
* Decoy Object 誘餌物件
    * Decoy File 誘餌檔案
    * Decoy Network Resource 誘餌網路資源
    * Decoy Persona 誘餌角色
    * Decoy Public Release 誘餌公開發布
    * Decoy Session Token 誘餌會話令牌
    * Decoy User Credential 誘餌使用者憑證
---
5.Evict 逐出
===
* Credential Eviction 憑證逐出
    * Account Locking 帳戶鎖定
    * Authentication Cache Invalidation  身份驗證緩存失效
* Process Eviction進程逐出
    * Process Termination 進程終止
---
