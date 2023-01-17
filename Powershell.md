
![List Powershell notes](scripts/List%20Powershell%20notes.md)

-   [Bulk rename picture and videos to their capture time](powershell/Bulk%20rename%20picture%20and%20videos%20to%20their%20capture%20time.md):
    
-   [Data file](powershell/Data%20file.md):
    
-   [Data types](powershell/Data%20types.md):
    -   Hashtable
-   [bash-equivalents](powershell/basics/bash-equivalents.md):
    -   While Loop
    -   `read name <-> $name = Read-Host -Prompt "Name"`
-   [Filter and select objects](powershell/basics/Filter%20and%20select%20objects.md):
    -   Add calculated property
    -   `$list[(0..1;-3..-1)]`
-   [Encrypt or decrypt sensitive text](powershell/Encrypt%20or%20decrypt%20sensitive%20text.md):
    -   Passwords
    -   `ConvertTo-SecureString`
-   [attributes](powershell/filesystem/attributes.md):
    
-   [Download or invoke files from the internet](powershell/filesystem/Download%20or%20invoke%20files%20from%20the%20internet.md):
    
-   [export](powershell/filesystem/export.md):
    
-   [Interact with the File System](powershell/filesystem/Interact%20with%20the%20File%20System.md):
    -   Run as administrator
-   [Test paths and retrieve filesystem information](powershell/filesystem/Test%20paths%20and%20retrieve%20filesystem%20information.md):
    
-   [Create shortcuts and symbolic links](powershell/filesystem/Create%20shortcuts%20and%20symbolic%20links.md):
    
-   [Input information](powershell/Input%20information.md):
    -   File Parsing
    -   `[RegEx]::Match($_, $pattern).Groups[1].value`
-   [List all apps in PATH locations](powershell/List%20all%20apps%20in%20PATH%20locations.md):
    
-   [List all bluetooth devices](powershell/List%20all%20bluetooth%20devices.md):
    -   List Devices
    -   `Get-PnpDevice -Class Bluetooth`
-   [Make scripts executable when renamed cmd](powershell/Make%20scripts%20executable%20when%20renamed%20cmd.md):
    -   script.ps1.bat
    -   `Invoke-Command -ScriptBlock ([ScriptBlock]::Create($cmd))`
-   [Naming convention](powershell/Naming%20convention.md):
    
-   [Offer different options in a command line menu](powershell/Offer%20different%20options%20in%20a%20command%20line%20menu.md):
    -   Select option 1, 2, 3
    -   `$Choice = Read-Host -Prompt "Select ..."`
-   [Sensitive input](powershell/Sensitive%20input.md):
    
-   [Specify parameters for functions and scripts](powershell/Specify%20parameters%20for%20functions%20and%20scripts.md):
    -   AutoComplete
    -   -   `Parameter(Mandatory = $true)`
-   [Upgrade applications](powershell/Upgrade%20applications.md):
    -   Update Store Apps
    -   `$wmiObj.UpdateScanMethod()`
-   [File system metadata](powershell/File%20system%20metadata.md):
    
-   [Powershell Examples](powershell/Powershell%20Examples.md):
    -   list connfiguration items
-   [Date and time](powershell/Date%20and%20time.md):
    
-   [Troubleshoot issues and help yourself](powershell/Troubleshoot%20issues%20and%20help%20yourself.md):