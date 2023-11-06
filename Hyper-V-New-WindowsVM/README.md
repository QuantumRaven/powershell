# New-WindowsVM.ps1

## Role of script

- Creates and sets up virtual hardware for Windows based virtual machines

### New-VM: What it is and what it does
>
> The New-VM cmdlet creates a new virtual machine. [New-VM - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/new-vm?view=windowsserver2022-ps)

### Set-VM: What it is and what it does

> The Set-VM cmdlet configures a virtual machine. [Set-VM - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/set-vm?view=windowsserver2022-ps)

### Write-Host: What it is and what it does
>
> The `Write-Host` cmdlet's primary purpose is to produce for-(host)-display-only output, such as printing colored text like when prompting the user for input in conjunction with [Read-Host](https://docs.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/read-host?view=powershell-7). `Write-Host` uses the [ToString()](https://learn.microsoft.com/en-us/dotnet/api/system.object.tostring?view=net-7.0) method to write the output. By contrast, to output data to the pipeline, use [Write-Output](https://learn.microsoft.com/en-us/powershell/module/Microsoft.PowerShell.Utility/write-output?view=powershell-7.3) or implicit output.
>
> You can specify the color of text by using the `ForegroundColor` parameter, and you can specify the background color by using the `BackgroundColor` parameter. The Separator parameter lets you specify a string to use to separate displayed objects. The particular result depends on the program that is hosting PowerShell.

### Add-VMDvdDrive: What it is and what it does
>
> The Add-VMDvdDrive cmdlet adds a DVD drive to a virtual machine. - [Add-VMDvdDrive - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/add-vmdvddrive?view=windowsserver2022-ps)

### Set-VMFirmware: What it is and what it does
>
> The Set-VMFirmware cmdlet sets the firmware configuration of a Generation 2 virtual machine. [Set-VMFirmware - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/Set-VMFirmware?view=windowsserver2022-ps)

### Get-VMDvdDrive: What it is and what it does
>
> The Get-VMDvdDrive cmdlet gets the DVD drives attached to a virtual machine or snapshot. This cmdlet has no ControllerType parameter, as the Get-VMHardDiskDrive cmdlet does, because virtual DVD drives can be attached only to the IDE controller. [Get-VMDvdDrive - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/Get-VMDvdDrive?view=windowsserver2022-ps)

### Get-VMHardDiskDrive: What it is and what it does
>
> The Get-VMHardDiskDrive cmdlet gets the virtual hard disk drives attached to one or more virtual machines. [Get-VMHardDiskDrive - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/Get-VMHardDiskDrive?view=windowsserver2022-ps)

### Get-VMNetworkAdapter: What it is and what it does
>
> The Get-VMNetworkAdapter cmdlet gets the virtual network adapters of the specified virtual machine, snapshot, or management operating system. [Get-VMNetworkAdapter - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/Get-VMNetworkAdapter?view=windowsserver2022-ps)

### Enable-VMIntegrationService: What it is and what it does
>
> The Enable-VMIntegrationService cmdlet enables an integration service on a virtual machine. [Enable-VMIntegrationService - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/Enable-VMIntegrationService?view=windowsserver2022-ps)
