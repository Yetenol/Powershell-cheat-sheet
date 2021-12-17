# [⌂](../README.md) › [Powershell](../README.md#powershell) › **Applications**

## Update all Microsoft Store apps

```powershell
$namespaceName = "root\cimv2\mdm\dmmap"
$className = "MDM_EnterpriseModernAppManagement_AppManagement01"
$wmiObj = Get-WmiObject -Namespace $namespaceName -Class $className
$result = $wmiObj.UpdateScanMethod()
```