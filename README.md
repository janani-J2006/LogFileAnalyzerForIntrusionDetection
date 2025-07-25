# LogFileAnalyzerForIntrusionDetection
## 📌 Objective:
A Python-based tool that parses Apache and SSH logs to detect brute-force attempts, suspicious activity, and visualize top IP request patterns.

## 🧰 Features:
- Parses `access.log` and `auth.log`
- Detects:
  - Suspicious HTTP requests (403, 404 errors)
  - SSH brute-force IPs
  - Top active IP addresses
- Visualizes access frequency with a bar chart
- Outputs:
  - `suspicious_requests.log`
  - `error_requests.log`
  - `suspicious_ips.txt`
  - `ssh_bruteforce_ips.csv`
  - `top_ips.csv`

## 📸 Sample Outputs:
| Screenshot | Description |
|------------|-------------|
| `chart_output.png` | IP vs Request Count |
| `folder_view.png` | Project File Structure |
| `suspicious_requests.png` | Detected 403/404 Requests |
| `brute_force_output.png` | SSH Brute-force IPs |
| `sample_log.png` | Sample of access.log file |

## 🚀 Run Instructions:
```bash
python3 log_analyzer.py

**Conclusion**

This project gave me hands-on experience in log analysis, an essential skill for cybersecurity roles.
I learned how attackers leave traces in logs and how scripting can help automate the detection of such threats.
This can be a building block for future SIEM or IDS tools.
