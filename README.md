# IAM

Command to replace the Local Administrator

```
Remove-LocalGroupMember -Group "Administrators" -Member "G_IAM_WINDOWS_ROLES","G_IAM_REDES_ROLES"
Add-LocalGroupMember -Group "Administrators" -Member "G_IAM_REDES_ADMIN","G_IAM_WINDOWS_ADMIN"
```