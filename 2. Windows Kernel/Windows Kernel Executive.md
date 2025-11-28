- Kernel decides what user is allowed to do
- Kernel is split into subsystems
![[Kernel_subsystems.png]]

| Prefix   | Subsystem                  | Example                   |
| -------- | -------------------------- | ------------------------- |
| Nt/Zw    | System call interface      | NtOpenFIle/ZwOpenFile     |
| Se       | Security Reference Monitor | SeAccessCheck             |
| Ob       | Object manager             | ObReferenceObjectByHandle |
| Ps       |                            |                           |
| Cm       |                            |                           |
| Mm<br>Io |                            | IoCreateFile              |
| Io       | Input/Output Manager       | CiValidateFileObject      |
| Ci       | Code integrity             | CiValidateFileObject      |

