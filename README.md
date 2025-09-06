# Zero-Day Research 🔍

This repository contains my **zero-day findings**, Proof-of-Concepts (PoCs), and related security research. All content is meant for **educational use** and **responsible disclosure** only.

---
## Purpose

I created this repo to document and share vulnerabilities I discovered, their PoCs, and references so that other researchers, maintainers, and defenders can learn and fix issues faster.

---
## My CVE disclosures (registered)

Below are the CVEs I registered for vulnerabilities I found in *Campcodes Online Hospital Management System 1.0*.

### **CVE-2025-9770**
#### Campcodes Hospital Management System Admin Dashboard Login admin sql injection
**Description:**
A weakness has been identified in Campcodes Hospital Management System 1.0. Affected by this vulnerability is an unknown functionality of the file /admin/ of the component Admin Dashboard Login. This manipulation of the argument Password causes sql injection. It is possible to initiate the attack remotely. The exploit has been made available to the public and could be exploited.
### Proof of Concept (PoC)
The detailed Proof of Concept can be found here:  
[HMS Admin Auth Bypass via SQL Injection (PDF)](https://github.com/Yashh-G/zero-day-research/blob/main/HMS_Admin_Auth_Bypass.pdf)


##### References:
- **NVD Link: [https://nvd.nist.gov/vuln/detail/CVE-2025-9770](https://nvd.nist.gov/vuln/detail/CVE-2025-9770)**
- **VulnDB: [https://vuldb.com/?submit.640807](https://vuldb.com/?submit.640807)**
- **CVE Details: [https://www.cvedetails.com/cve/CVE-2025-9770/](https://www.cvedetails.com/cve/CVE-2025-9770/)**
- **CVE Record MITRE: [https://www.cve.org/CVERecord?id=CVE-2025-9770](https://www.cve.org/CVERecord?id=CVE-2025-9770)**
- **Vulners: [https://vulners.com/cve/CVE-2025-9770](https://vulners.com/cve/CVE-2025-9770)**
- **Tenable: [https://www.tenable.com/cve/CVE-2025-9770](https://www.tenable.com/cve/CVE-2025-9770)**

---

### **CVE-2025-9754**
#### Campcodes Online Hospital Management System Edit Profile edit-profile.php cross site scripting (XSS)
**Description:**
A flaw has been found in Campcodes Online Hospital Management System 1.0. The impacted element is an unknown function of the file /edit-profile.php of the component Edit Profile Page. Executing manipulation of the argument Username can lead to cross site scripting. The attack may be launched remotely. The exploit has been published and may be used.
### Proof of Concept (PoC)
The detailed Proof of Concept can be found here:  
[Edit Profile Page XSS (PDF)](https://github.com/Yashh-G/zero-day-research/blob/main/HMS_Stored_XSS_In_UserName_Field.pdf)

##### References:
- **NVD Link: [https://nvd.nist.gov/vuln/detail/CVE-2025-9754](https://nvd.nist.gov/vuln/detail/CVE-2025-9754)**
- **CVE Details: [https://www.cvedetails.com/cve/CVE-2025-9754/](https://www.cvedetails.com/cve/CVE-2025-9754/)**
- **VulnDB: [https://vuldb.com/?id.322055](https://vuldb.com/?id.322055)**
- **CVE Feed: [https://cvefeed.io/vuln/detail/CVE-2025-9754](https://cvefeed.io/vuln/detail/CVE-2025-9754)**
- **Tenable: [https://www.tenable.com/cve/CVE-2025-9754](https://www.tenable.com/cve/CVE-2025-9754)**

---

### **CVE-2025-9753**
#### Campcodes Online Hospital Management System Patient Search patient-search.php cross site scripting (XSS)
**Description:**
A vulnerability was detected in Campcodes Online Hospital Management System 1.0. The affected element is an unknown function of the file /admin/patient-search.php of the component Patient Search Module. Performing manipulation of the argument Search by Name Mobile No results in cross site scripting. The attack may be initiated remotely. The exploit is now public and may be used.
##### References:
- **NVD Link: [https://nvd.nist.gov/vuln/detail/CVE-2025-9753](https://nvd.nist.gov/vuln/detail/CVE-2025-9753)**
- **CVE Details: [https://www.cvedetails.com/cve/CVE-2025-9753/](https://www.cvedetails.com/cve/CVE-2025-9753/)**
- **VulnDB: [https://vuldb.com/?id.322054](https://vuldb.com/?id.322054)**
- **CVE Feed: [https://cvefeed.io/vuln/detail/CVE-2025-9753](https://cvefeed.io/vuln/detail/CVE-2025-9753)**
- **Tenable: [https://www.tenable.com/cve/CVE-2025-9753/cpes](https://www.tenable.com/cve/CVE-2025-9753/cpes)**

---

### **CVE-2025-9746**
#### Campcodes Hospital Management System Edit Doctor Specialization edit-doctor-specialization.php cross site scripting (XSS)
**Description:**
A vulnerability was detected in Campcodes Hospital Management System 1.0. This affects an unknown function of the file /admin/edit-doctor-specialization.php of the component Edit Doctor Specialization Page. The manipulation results in cross site scripting. The attack may be launched remotely. The exploit is now public and may be used.
##### References:
- **NVD Link: [https://nvd.nist.gov/vuln/detail/CVE-2025-9746](https://nvd.nist.gov/vuln/detail/CVE-2025-9746)**
- **CVE Details: [https://www.cvedetails.com/cve/CVE-2025-9746/](https://www.cvedetails.com/cve/CVE-2025-9746/)**
- **CVE Record MITRE: [https://www.cve.org/CVERecord?id=CVE-2025-9746](https://www.cve.org/CVERecord?id=CVE-2025-9746)**
- **Tenable: [https://www.tenable.com/cve/CVE-2025-9746](https://www.tenable.com/cve/CVE-2025-9746)**
- **VulnDB: [https://vuldb.com/?id.322045](https://vuldb.com/?id.322045)**
