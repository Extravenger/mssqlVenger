# mssqlVenger

mssqlVenger is a tool designed for performing lateral movement within Active Directory (AD) environments. Focused on leveraging linked server across the network.

## Features

- Impersonate a login: Use EXECUTE AS LOGIN to impersonate logins in the current MSSQL instance.
- Impersonate a user: Use EXECUTE AS USER to impersonate users within the current MSSQL instance.
- Execute commands on linked servers: Utilize EXEC AT LinkedServer to run commands on linked servers.
- Perform xp_dirtree: Exploit the xp_dirtree extended procedure for reconnaissance or command execution.
- Create new sysadmin users: Add new sysadmin-level users on local or remote servers.
- Pull login-mapping and execute commands on linked servers: Gather login mappings and leverage them for command execution.
- <b>Enable RPCOUT on linked servers</b>: Activate the RPC OUT feature to extend exploitation capabilities.
