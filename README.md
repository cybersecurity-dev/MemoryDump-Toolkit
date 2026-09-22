<div align="center">

```mermaid
mindmap
  root((Memory Forensics))

    Acquisition
      Live Response
        DumpIt
        WinPMEM
        LiME
        AVML

      Hypervisor Dumps
        VMware
        VirtualBox
        Hyper-V

      Cloud Memory
        AWS Snapshots
        Azure VM Memory
        GCP Forensics

    Analysis Platforms
      Volatility3
      Rekall
      Redline
      MemProcFS

    Windows Analysis
      pstree
      pslist
      dlllist
      netscan
      malfind
      cmdline
      handles

    Linux Analysis
      psaux
      lsof
      netstat
      kernel_modules
      bash_history
      rootkit_detection

    Android Analysis
      Applications
      Dalvik ART
      SQLite Databases
      SMS Artifacts
      Browser Credentials

    Malware Analysis
      Injected Code
      Reflective DLL
      Process Hollowing
      Fileless Malware
      Ransomware

    Credential Analysis
      LSASS
      Kerberos Tickets
      Hash Extraction
      Session Tokens

    Detection Engineering
      Sigma Rules
      YARA Rules
      ATT&CK Techniques
      IOC Correlation

    Reporting
      Evidence
      Timeline
      Indicators
      Attribution
```

# **`MemoryDumper`** | Memory Dump Toolkit
</div>

[![YouTube](https://img.shields.io/badge/YouTube-%23FF0000.svg?style=for-the-badge&logo=YouTube&logoColor=white)]()
[![Reddit](https://img.shields.io/badge/Reddit-FF4500?style=for-the-badge&logo=reddit&logoColor=white)](https://www.reddit.com/r/memoryforensics/new/)

<p align="center">
    <a href="https://github.com/cybersecurity-dev/"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/github.svg" alt="GitHub"></a>
    &nbsp;
    <a href="https://www.youtube.com/@CyberThreatDefence"><img height="25" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/youtube.svg" alt="YouTube"></a>
    &nbsp;
    <a href="https://cyberthreatdefence.com/my_awesome_lists"><img height="20" src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/blog.svg" alt="My Awesome Lists"></a>
    <img src="https://github.com/cybersecurity-dev/cybersecurity-dev/blob/main/assets/bar.gif">
</p>

```mermaid
flowchart LR

    A[Incident Alert]

    A --> B[Memory Acquisition]

    B --> C{Operating System}

    C --> D[Windows]
    C --> E[Linux]
    C --> F[Android]

    D --> D1[DumpIt]
    D --> D2[WinPMEM]

    E --> E1[LiME]
    E --> E2[AVML]

    F --> F1[ADB]
    F --> F2[TWRP]
    F --> F3[LiME]

    D1 --> G[Memory Image]
    D2 --> G
    E1 --> G
    E2 --> G
    F1 --> G
    F2 --> G
    F3 --> G

    G --> H[Volatility3]

    H --> I[Process Enumeration]
    H --> J[Malware Hunting]
    H --> K[Network Analysis]
    H --> L[Credential Analysis]
    H --> M[Rootkit Detection]

    I --> N[Timeline]
    J --> N
    K --> N
    L --> N
    M --> N

    N --> O[Forensic Report]
```

## 📖 Contents
- [My Awesome Lists](#my-awesome-lists)
- [Contributing](#contributing)
- [Contributors](#contributors)

---
---

##

### My Awesome Lists
You can access the my awesome lists [here](https://cyberthreatdefence.com/my_awesome_lists)

### Contributing

[Contributions of any kind welcome, just follow the guidelines](contributing.md)!

### Contributors

[Thanks goes to these contributors](https://github.com/cybersecurity-dev/memorydump-toolkit/graphs/contributors)!

[🔼 Back to top](#memorydumper--memory-dump-toolkit)

