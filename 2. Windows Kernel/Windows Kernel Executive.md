- Kernel decides what user is allowed to do
- Kernel is split into subsystems
![[Kernel_subsystems.png]]

| Prefix | Subsystem                  | Example                   |
| ------ | -------------------------- | ------------------------- |
| Nt/Zw  | System call interface      | NtOpenFIle/ZwOpenFile     |
| Se     | Security Reference Monitor | SeAccessCheck             |
| Ob     | Object manager             | ObReferenceObjectByHandle |
| Ps     | Process and Thread Manager | PsGetCurrentProcess       |
| Cm     | Configuration Manager      | CmRegisterCallback        |
| Mm     | Memory manager             | MmMapIoSpace              |
| Io     | Input/Output Manager       | IoCreateFile              |
| Ci     | Code integrity             | CiValidateFileObject      |

