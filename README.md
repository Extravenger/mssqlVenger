# mssqlVenger

mssqlVenger is a tool designed for performing lateral movement within Active Directory (AD) environments. Focused on leveraging linked server across the network.

## Features

- <u><b>Impersonate a login</b></u>: Use EXECUTE AS LOGIN to impersonate logins in the current MSSQL instance.
- <b><u>Impersonate a user</u></b>: Use EXECUTE AS USER to impersonate users within the current MSSQL instance.
- <b><u>Execute commands on linked servers</u></b>: Utilize EXEC AT LinkedServer to run commands on linked servers.
- <b><u>Perform xp_dirtree</u></b>: Exploit the xp_dirtree extended procedure for reconnaissance or command execution.
- <b><u>Create new sysadmin users</u></b>: Add new sysadmin-level users on local or remote servers.
- <b><u>Pull login-mapping and execute commands on linked servers</u></b>: Gather login mappings and leverage them for command execution.
- <b><u>Enable RPCOUT on linked servers</u></b>: Activate the RPC OUT feature to extend exploitation capabilities.
