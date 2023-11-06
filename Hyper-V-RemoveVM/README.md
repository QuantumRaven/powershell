# Remove-VM.ps1

## Role of script

- Deletes virtual machine
- Deletes all VHD files
- Deletes all VM data files

### Remove-VM: What it is and how it works
>
> The `Remove-VM` cmdlet deletes a virtual machine. Running this cmdlet deletes the virtual machine's configuration file, but does not delete any virtual hard drives. If the virtual machine has any snapshots, these are deleted and merged into the virtual hard disk files after the virtual machine is deleted. [Remove-VM - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/remove-vm?view=windowsserver2022-ps)
