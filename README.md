# Splunk-DNS-Log-Analysis
Analyzing DNS log files using Splunk SIEM – field extraction, anomaly detection, and threat hunting with queries and sample logs.
# Splunk DNS Log Analysis

This project demonstrates how to analyze **DNS log files** using **Splunk SIEM**.  
It includes steps for uploading DNS logs, running queries, detecting anomalies, and identifying suspicious domains.

---

## 🔹 Project Overview
- Upload DNS logs into Splunk
- Extract fields (src_ip, fqdn, query type, response code, etc.)
- Detect anomalies in DNS activity
- Investigate suspicious domains using threat intelligence

---

## 📂 Project Files
- `Project1_Analyzing_DNS_Logs.md` → Detailed steps and queries
- `queries/dns_analysis_queries.spl` → SPL queries
- `sample_dns_logs/` → Example DNS log file
- `screenshots/` → Screenshots of Splunk dashboards

---

## 📊 Example Queries
Search DNS logs:
```spl
index=* sourcetype=dns_sample
