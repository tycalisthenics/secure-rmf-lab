# **System Description – Secure File Server (Lab Simulation)**

## **System Name:**

SecureFileServer01

## **System Purpose:**

This system is a simulated Windows Server 2019-based secure file server designed for storing and managing controlled unclassified information (CUI) within a classified network environment. It serves as the central repository for sensitive project documentation, personnel records, and mission-related reports.

## **System Owner:**

Lab Simulation \- Tyler Rowe (acting as System Owner/ISSO)

## **Users:**

* System Administrators (local Admin group)  
* Project Team Members (standard user accounts)  
* Security Monitoring System (Wazuh agent)

  ## **System Environment:**

* Standalone virtual machine hosted in VMware Workstation  
* Simulates a classified DoD enclave environment  
* Connected via NAT network to Kali Linux attacker VM and optional monitoring VM

  ## **Security Categorization (Simulated):**

* **Confidentiality:** High  
* **Integrity:** Moderate  
* **Availability:** Low (Categorization based on simulated FIPS 199 / NIST SP 800-60 guidance)

  ## **Interfaces:**

* SMB (for file sharing)  
* RDP (for remote administration)  
* Wazuh agent communication (for monitoring)

  ## **Data Stored:**

* Simulated personnel records  
* Mock project files (Word, PDF)  
* Lab-generated logs

  ## **Justification for Security Controls:**

Due to the nature of the simulated sensitive data and limited user access, this system requires implementation of moderate to high baseline security controls from NIST SP 800-53 and DISA STIGs. Risk Management Framework (RMF) procedures will be applied for assessment and authorization.

