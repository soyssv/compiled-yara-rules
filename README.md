# YARA Rules for Malware detection/Av training

**Note:** The `.yac` file is in a `.rar` archive due to GitHub's file size limitations.  

## Contents

- **rules_metadata.db** – Contains metadata for each rule:  
  - `rule_name` – YARA rule identifier  
  - `score` – Severity/confidence score  
  - `malware_type` – Malware type/family  
  - `description` – Description of the rule  

---

## Archive Summary

- **Total rules:** 135  
- **Malware families:** 16  

| Malware Family | Number of Rules | Severity |
|----------------|----------------|----------|
| APT            | 3              | Severe   |
| Ransomware     | 63             | Severe   |
| Botnet         | 4              | Severe   |
| Stealer        | 4              | Medium   |
| Trojan         | 12             | Medium   |
| Backdoor       | 38             | Medium   |
| Dropper        | 1              | Medium   |
| Worm           | 1              | Severe   |
| Downloader     | 2              | Medium   |
| Adware         | 1              | Low      |
| RAT            | 1              | Severe   |
| Hacktool       | 1              | Medium   |
| Rootkit        | 1              | Severe   |
| Miner          | 1              | Medium   |
| Keylogger      | 1              | Medium   |
