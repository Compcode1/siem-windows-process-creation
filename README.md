**README.md Summary**

 Splunk Windows Security Log Analysis

Project Overview

This project investigates native Windows Security log data using Splunk to simulate real-world threat detection practices in a SOC (Security Operations Center) environment. The objective is to identify and understand system activity patterns, detect suspicious behaviors, and apply basic detection logic using SPL (Search Processing Language).

The analysis is structured into three progressive phases:

---

**Phase 1 – Baseline System Activity**

This phase establishes what "normal" looks like on the system by analyzing who logs in, when, from where, and using what type of logon. It provides a behavioral baseline to support later anomaly detection.

---

**Phase 2 – Suspicious Behavior Investigation**

Using targeted SPL filters, this phase investigates failed logons, account creation, privilege escalation, and off-hours logon activity. These checks are designed to uncover indicators of compromise (IOCs) or policy violations.

---

**Phase 3 – Detection Logic Prototypes**

This final phase converts suspicious patterns into detection rules. It includes simple logic to detect brute-force attempts and privilege changes outside business hours — both of which returned no alerts, consistent with the clean baseline.

---

**Outcome**

No signs of malicious activity were detected during this analysis. However, the methods used reflect standard practices in modern SOC environments and demonstrate how to move from raw data to operational detection logic using Splunk.
