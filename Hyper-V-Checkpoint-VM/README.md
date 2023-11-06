# Checkpoint-VM.ps1

## Role of script

- Prompts user to pick a virtual machine for checkpoint creation.
- Prompts user to assign a custom name for the checkpoint.
- Creates a checkpoint based on the answers to the arguments.

### Checkpoint-VM: What it is and how it works

> The Checkpoint-VM cmdlet creates a checkpoint of a virtual machine.
>
> Note: In Windows Server 2012 R2, virtual machine snapshots were renamed to virtual machine checkpoints. For clarity, this document will refer to virtual machine snapshots as checkpoints. - [Checkpoint-VM - Hyper-V - PowerShell](https://learn.microsoft.com/en-us/powershell/module/hyper-v/checkpoint-vm?view=windowsserver2022-ps)

Example:

`Checkpoint-VM -VMName deblab -SnapshotName base_2020-09-30` would create a checkpoint for the virtual machine deblab and name it base_2020-09-30. So, if something were to go wrong during the use of said VM, you could turn the VM off and restore from any checkpoint tied to it and go from there.
