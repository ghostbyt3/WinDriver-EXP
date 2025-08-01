## PoC Repository for Vulnerable Windows Drivers

This repository includes PoC exploits for vulnerabilities in Windows drivers, showcasing flaws that can result in privilege escalation, arbitrary code execution, or other security risks. Intended for research and education only.


## POCs

| Vulnerability | CVE ID | Component(s) |
| ------------- | ------ | ------ | 
| Windows Kernel Elevation of Privilege Vulnerability | [CVE-2024-21338](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-21338) | appid.sys |
| Windows Kernel Streaming Elevation of Privilege Vulnerability| [CVE-2024-30084](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-30084) | ks.sys |
| Microsoft Streaming Service Elevation of Privilege Vulnerability| [CVE-2024-30090](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-30090) | ks.sys & ksthunk.sys |
| Windows Kernel Information Disclosure Vulnerability | [CVE-2024-38041](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-38041) | appid.sys |
| Windows Kernel Streaming Elevation of Privilege Vulnerability| [CVE-2024-35250](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-35250) | ks.sys |
| Windows Cloud Files Mini Filter Driver Elevation of Privilege Vulnerability| [CVE-2024-30085](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-30085) | cldflt.sys |
| Windows Common Log File System Driver Elevation of Privilege Vulnerability | [CVE-2024-49138](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2024-49138) | clfs.sys | 
| Windows Hyper-V NT Kernel Integration VSP Elevation of Privilege Vulnerability| [CVE-2025-21333](https://msrc.microsoft.com/update-guide/vulnerability/CVE-2025-21333) | vkrnlintvsp.sys |

## Disclaimer

This repository is intended for educational and research purposes only. The PoCs provided here should not be used for any illegal activities or malicious purposes. The maintainers of this repository are not responsible for any misuse of the information and code provided here.
