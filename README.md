## Youssix

Security researcher. Hypervisors, Windows internals, reverse engineering.

I build defensive tools that operate below the OS: hypervisor-based memory integrity, DLL injection detection, binary structure recovery. Most of my work sits at the intersection of low-level systems programming and detection engineering.

### Projects

| Project | What it does |
|---------|-------------|
| [HvShield](https://github.com/Youssix/HvShield) | Hypervisor-based kernel memory integrity monitor (VT-x/EPT) |
| [CRTScan](https://github.com/Youssix/CRTScan) | DLL injection detection via CRT fingerprinting and return address analysis |
| [VTCheck](https://github.com/Youssix/VTCheck) | COM/C++ vtable integrity verifier with RTTI validation |
| [PEBWatch](https://github.com/Youssix/PEBWatch) | PEB tamper detection and module unlinking discovery |
| [IDAVtableRecovery](https://github.com/Youssix/IDAVtableRecovery) | IDA Pro plugin for vtable discovery and class hierarchy reconstruction |

### Writeups

Technical writeups at [youssix.github.io](https://youssix.github.io) covering EPT internals, VMCS debugging, PEB forensics, VMT hooking detection, and CRT-based DLL analysis.
