[D3FEND™](https://d3fend.mitre.org/)
==
* 1.Harden
* 2.Detect
* 3.Isolate
* 4.Deceive
* 5.Evict
==
1.Harden
==
* Application Hardening
   * Application Configuration Hardening
   * Dead Code Elimination
   * Exception Handler Pointer Validation
   * Pointer Authentication
   * Process Segment Execution Prevention
   * Segment Address Offset Randomization
   * Stack Frame Canary Validation
* Credential Hardening
   * Biometric Authentication
   * Certificate-based Authentication
   * Certificate Pinning
   * Credential Transmission Scoping
   * Domain Trust Policy
   * Multi-factor Authentication
   * One-time Password
   * Strong Password Policy
   * User Account Permissions
* Message Hardening
   * Message Authentication
   * Message Encryption
   * Transfer Agent Authentication
* Platform Hardening
    * Bootloader Authentication
    * Disk Encryption
    * Driver Load Integrity Checking
    * File Encryption
    * Local File Permissions
    * RF Shielding
    * Software Update
    * System Configuration Permissions
    * TPM Boot Integrity
---
2.Detect
==
* File Analysis
    * Dynamic Analysis
    * Emulated File Analysis
    * File Content Rules
    * File Hashing
* Identifier Analysis
    * Homoglyph Detection
    * URL Analysis
* Message Analysis
    * Sender MTA Reputation Analysis
    * Sender Reputation Analysis
* Network Traffic Analysis
    * Administrative Network Activity Analysis
    * Byte Sequence Emulation
    * Certificate Analysis
    * Active Certificate Analysis
    * Passive Certificate Analysis
    * Client-server Payload Profiling
    * Connection Attempt Analysis
    * DNS Traffic Analysis
    * File Carving
    * Inbound Session Volume Analysis
    * IPC Traffic Analysis
    * Network Traffic Community Deviation
    * Per Host Download-Upload Ratio Analysis
    * Protocol Metadata Anomaly Detection
    * Relay Pattern Analysis
    * Remote Terminal Session Detection
    * RPC Traffic Analysis
* Platform Monitoring
    * Firmware Behavior Analysis
    * Firmware Embedded Monitoring Code
    * Firmware Verification
    * Peripheral Firmware Verification
    * System Firmware Verification
    * Operating System Monitoring
    * Endpoint Health Beacon
    * Input Device Analysis
    * Memory Boundary Tracking
    * Scheduled Job Analysis
    * System Daemon Monitoring
    * System File Analysis
    * Service Binary Verification
    * System Init Config Analysis
    * User Session Init Config Analysis
* Process Analysis
    * Database Query String Analysis
    * File Access Pattern Analysis
    * Indirect Branch Call Analysis
    * Process Code Segment Verification
    * Process Self-Modification Detection
    * Process Spawn Analysis
    * Process Lineage Analysis
    * Script Execution Analysis
    * Shadow Stack Comparisons
    * System Call Analysis
    * File Creation Analysis
* User Behavior Analysis
    * Authentication Event Thresholding
    * Authorization Event Thresholding
    * Credential Compromise Scope Analysis
    * Domain Account Monitoring
    * Job Function Access Pattern Analysis
    * Local Account Monitoring
    * Resource Access Pattern Analysis
    * Session Duration Analysis
    * User Data Transfer Analysis
    * User Geolocation Logon Pattern Analysis
    * Web Session Activity Analysis
---
3.Isolate
===
* Execution Isolation
    * Executable Allowlisting
    * Executable Denylisting
    * Hardware-based Process Isolation
    * IO Port Restriction
    * Kernel-based Process Isolation
    * Mandatory Access Control
    * System Call Filtering
* Network Isolation
    * Broadcast Domain Isolation
    * DNS Allowlisting
    * DNS Denylisting
    * Forward Resolution Domain Denylisting
    * Hierarchical Domain Denylisting
    * Homoglyph Denylisting
    * Forward Resolution IP Denylisting
    * Reverse Resolution IP Denylisting
    * Encrypted Tunnels
    * Network Traffic Filtering
    * Inbound Traffic Filtering
    * Outbound Traffic Filtering
---
4.Deceive
===
* Decoy Environment
    * Connected Honeynet
    * Integrated Honeynet
    * Standalone Honeynet
* Decoy Object
    * Decoy File
    * Decoy Network Resource
    * Decoy Persona
    * Decoy Public Release
    * Decoy Session Token
    * Decoy User Credential
---
5.Evict
===
* Credential Eviction
    * Account Locking
    * Authentication Cache Invalidation 
* Process Eviction
    * Process Termination  
---
