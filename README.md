# Zero-Day Research 🔍

This repository contains my **zero-day findings**, Proof-of-Concepts (PoCs), and related security research. All content is meant for **educational use** and **responsible disclosure** only.

---

## Purpose

I created this repo to document and share vulnerabilities I discovered, their PoCs, and references so that other researchers, maintainers, and defenders can learn and fix issues faster.

---
## My CVE disclosures (registered)

Below are the CVEs I registered for vulnerabilities I found in *Campcodes Online Hospital Management System 1.0*.

1. **CVE-2025-9770** — Admin Dashboard Login: Authentication bypass via SQL Injection

   * Short: SQL injection in `/admin/` (Password parameter) allowing login bypass and potential data access.
   * PoC (this repo): `./HMS_Admin_Auth_Bypass.pdf`
   * Public references: NVD / other vulnerability trackers.

2. **CVE-2025-9754** — Edit Profile Page: Cross-Site Scripting (XSS)

   * Short: Stored/reflected XSS in `/edit-profile.php` via the `Username` parameter.
   * Public references: NVD / Tenable / VulDB.

3. **CVE-2025-9753** — Patient Search Module: Cross-Site Scripting (XSS)

   * Short: XSS in `/admin/patient-search.php` via `Search by Name / Mobile No` parameter.
   * Public references: NVD / CVEDetails / VulDB.

4. **CVE-2025-9746** — Edit Doctor Specialization Page: Cross-Site Scripting (XSS)

   * Short: XSS in `/admin/edit-doctor-specialization.php` allowing injection into the Doctor Specialization field.
   * Public references: NVD / Tenable / VulDB.

## Useful external references (official trackers)

* NVD (official CVE records):

  * CVE-2025-9770: [https://nvd.nist.gov/vuln/detail/CVE-2025-9770](https://nvd.nist.gov/vuln/detail/CVE-2025-9770)
  * CVE-2025-9754: [https://nvd.nist.gov/vuln/detail/CVE-2025-9754](https://nvd.nist.gov/vuln/detail/CVE-2025-9754)
  * CVE-2025-9753: [https://nvd.nist.gov/vuln/detail/CVE-2025-9753](https://nvd.nist.gov/vuln/detail/CVE-2025-9753)
  * CVE-2025-9746: [https://nvd.nist.gov/vuln/detail/CVE-2025-9746](https://nvd.nist.gov/vuln/detail/CVE-2025-9746)

