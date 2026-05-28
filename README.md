# Youssix

Security researcher focused on defensive tooling, Windows internals, virtualization security, and reverse engineering.

I publish research notes and source prototypes for low-level defensive analysis: hypervisor-based memory monitoring, DLL injection detection through CRT analysis, vtable integrity checking, PEB forensics, and binary structure recovery.

Portfolio: https://youssix.github.io

### Projects

| Project | What it does |
|---------|-------------|
| [HvShield](https://github.com/Youssix/HvShield) | Hypervisor/EPT memory integrity research prototype |
| [CRTScan](https://github.com/Youssix/CRTScan) | DLL injection detection via CRT fingerprinting and return-address analysis |
| [VTCheck](https://github.com/Youssix/VTCheck) | COM/C++ vtable integrity verifier with RTTI validation |
| [PEBWatch](https://github.com/Youssix/PEBWatch) | PEB tamper detection and module unlinking research |
| [IDAVtableRecovery](https://github.com/Youssix/IDAVtableRecovery) | IDA Pro plugin for vtable discovery and class hierarchy reconstruction |

### Writeups

Technical writeups at [youssix.github.io](https://youssix.github.io) covering EPT internals, VMCS debugging, PEB forensics, VMT hooking detection, and CRT-based DLL analysis.

### Responsible Use

The public repositories are defensive research prototypes for authorized labs,
malware-analysis environments, and security education. They do not include
exploitation, persistence, ransomware, credential theft, or mass-exfiltration
tooling.
