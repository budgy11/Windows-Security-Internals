- Kernel decides what user is allowed to do
- Kernel is split into subsystems
![[Kernel_subsystems.png]]

| Prefix | Subsystem                  | Example               |
| ------ | -------------------------- | --------------------- |
| Nt/Zw  | System call interface      | NtOpenFIle/ZwOpenFile |
| Se     | Security Reference Monitor | SeAccessCheck         |
|        |                            |                       |
