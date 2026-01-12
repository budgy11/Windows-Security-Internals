- Win32 core is in KERNEL32 and KERNELBASE
- NT Layer Dynamic Link Library (NTDLL) implements syscall dispatches aand runtime library API 
![[Win32 API.png]]
- User mode applications usually have the NTDLL loads new libraries on demand instead of directly containing implementations of the Windows system APIs
- 