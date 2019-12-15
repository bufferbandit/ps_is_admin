# ps_is_admin
Is admin?

([Security.Principal.WindowsPrincipal] [Security.Principal.WindowsIdentity]::GetCurrent()).IsInRole(` [Security.Principal.WindowsBuiltInRole] "Administrator")
