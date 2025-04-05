I set up a standalone Windows Server 2019 VM and a Kali Linux VM to simulate a secure file server environment. To allow basic connectivity, I created an inbound firewall rule on the Windows server to enable ICMP (ping) requests from Kali Linux.

I applied **STIG hardening** using the Windows Server 2019 STIG (Ver 3, Rel 3\) through **STIG Viewer 3.5.1**. STIGs are DISA-developed security checklists that reduce system vulnerabilities. Each STIG maps to one or more **NIST SP 800-53** security controls such as `AC` (Access Control), `CM` (Configuration Management), and `SC` (System & Communications Protection).

As part of the Risk Management Framework (RMF), I created and documented:

* **System Security Plan (SSP)** – Describes the system, data sensitivity, users, and implemented controls

* **Control Mapping Spreadsheet** – Maps each STIG rule to its NIST control and implementation

* **POA\&M** – Lists non-applicable STIGs and tracks any gaps or findings

---

**STIGs Completed:**

* **V-205842** – FIPS mode enabled (SC-13)

* **V-205923** – Hardened global system object permissions (CM-6 b)

* **V-205871** – Heap termination verified (CM-6 b)

* **V-271428 / V-271429** – Marked Not Applicable (AC-3; applies only to domain controllers)

