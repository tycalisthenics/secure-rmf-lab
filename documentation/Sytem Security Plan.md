System Security Plan (SSP) \- SecureFileServer01

System Overview

- System Name: SecureFileServer01  
- OS: Windows Server 2019  
- Purpose: Stores and manages simulated CUI for training.  
- Environment: Standalone VM hosted in VMWare Workstation.  
- Owner: Tyler Rowe (Lab Owner/ISSO Role)

Implemented Security Controls:

| Control ID | Title | Summary |
| :---- | :---- | :---- |
| AC-3 | ACCESS ENFORCEMENT | Windows Server 2019 must be configured for named-based strong mappings for certificates. |
| AC-3 | ACCESS ENFORCEMENT | Windows Server 2019 must be configured for certificate-based authentication for domain controllers. |
| CM-6 b | CONFIGURATION SETTINGS | Windows Server 2019 default permissions of global system objects must be strengthened. |
| CM-6 b | CONFIGURATION SETTINGS | Windows Server 2019 Turning off File Explorer heap termination on corruption must be disabled. |
| SC-13 | CRYPTOGRAPHIC PROTECTION | Windows Server 2019 must be configured to use FIPS-compliant algorithms for encryption, hashing, and signing. |

STIG Hardening Summary

- Using STIG Viewer 3.5.1  
- Working from Windows Server 2019 Ver 3, Rel 3 checklist  
- First 5 STIGs completed  
- Checklist saved in ‘/scans/’ folder