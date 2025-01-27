# mssqlVenger

mssqlVenger is a tool designed for performing lateral movement within Active Directory (AD) environments. Focused on leveraging linked servers across AD network.

## 🚀 Features
- <u><b>Impersonate a login</b></u>: Use EXECUTE AS LOGIN to impersonate logins in the current MSSQL instance.
- <b><u>Impersonate a user</u></b>: Use EXECUTE AS USER to impersonate users within the current MSSQL instance.
- <b><u>Execute commands on linked servers</u></b>: Utilize EXEC AT LinkedServer to run commands on linked servers.
- <b><u>Perform xp_dirtree</u></b>: Exploit the xp_dirtree extended procedure for command execution through NTLM-Relay attacks.
- <b><u>Create new sysadmin users</u></b>: Add new sysadmin-level users on local or remote servers.
- <b><u>Pull login-mapping and execute commands on linked servers</u></b>: Gather login mappings and leverage them for command execution.
- <b><u>Enable RPCOUT on linked servers</u></b>: Activate the RPC OUT feature to extend exploitation capabilities.

## 📋 Usage
The tool will ask for 4 parameters: <em>Server Name, Database Name, Username and Password. 

> [!Caution]
> Not providing username and password will result in Windows Authentication.

Upon running, you will see the following options:

```
[+] Choose an option:  

    1. Impersonate a login (EXECUTE AS LOGIN in current instance)  
    2. Impersonate a user (EXECUTE AS USER in current instance)  
    3. Execute command on a linked server (EXEC AT LinkedServer)  
    4. Perform xp_dirtree  
    5. Create new sysadmin user (local/remote)  
    6. Pull login-mapping and execute commands on linked server  
    7. Enable RPCOUT on linked server
```

## ⚠️ Disclaimer

This tool is designed to be used only for authorized purposes related to managing and interacting with MSSQL databases. Unauthorized use, including access without proper authorization, is strictly prohibited and may result in legal or administrative action. Always ensure compliance with applicable laws and regulations.
