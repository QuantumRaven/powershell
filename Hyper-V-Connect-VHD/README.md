# Connect-VHD.ps1

## Role of script

- Utilizes custom variables along with the `New-VHD` and `Add-VMHardDiskDrive` cmdlets to create and attach VHDs or Virtual Hard Drives.

### New-VHD: What it is and how it works

> The New-VHD cmdlet creates one or more new virtual hard disks in either VHD format or the newer VHDX format. The file name extension you specify determines the format. - [New-VHD - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/new-vhd?view=windowsserver2022-ps)

Example:

`New-VHD -Path D:\VM_Storage\disk0.vhdx -SizeBytes 10GB`

- Creates a virtual hard disk in the VHDX format. The file name extension you specify determines the format.

### Add-VMHardDiskDrive: What it is and how it works

> The Add-VMHardDiskDrive cmdlet adds a hard disk drive to a virtual machine. - [Add-VMHardDiskDrive - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/add-vmharddiskdrive?view=windowsserver2022-ps)

Example:

`Add-VMHardDiskDrive -VMName Test -Path D:\VM_Storage\disk0.vhdx`

- Creates a virtual hard disk using file D:\VM_Storage\disk0.vhdx on virtual machine Test.
