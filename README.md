# Security Log Analyzer 🔍

A lightweight Python-based **Security Log Analyzer** designed to parse Linux authentication logs and detect suspicious login attempts.

---

## 🚀 Features

- Parse Linux SSH / auth logs
- Detect failed login attempts
- Identify targeted users
- Identify attacking IP addresses
- Generate security alerts (LOW / MEDIUM / HIGH / CRITICAL)
- Export results as JSON report

---

## 🧠 How It Works

The tool analyzes log files and extracts:

- Username
- Source IP address
- Failed authentication attempts

Then it aggregates the data and generates:

- Threat levels based on behavior
- Top attacking IPs
- Most targeted users
- JSON report for further analysis

---

## 📦 Usage

### Run analysis on a log file:

```bash
python log_analyzer_v1.py real_auth.log
