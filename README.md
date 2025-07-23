# Log Monitoring and Threat Detection using Wazuh + ELK Stack

This project sets up a **Security Information and Event Management (SIEM)** system using:

- **Wazuh** – Log collection, threat detection, and security event correlation  
- **Elasticsearch** – Scalable storage and fast indexing of security logs  
- **Logstash** – Parsing, filtering, and forwarding logs  
- **Kibana** – Visualization and real-time dashboards for analysis

---

## 📁 Folder Structure

wazuh-elk-siem-project/
├── configs/ # Config files for Wazuh, Elasticsearch, Logstash, and Kibana
├── setup/ # Shell scripts and installation steps
├── test-logs/ # Sample logs for testing the detection engine
├── reports/ # Output of detections and incident reports
└── screenshots/ # Visual evidence (alerts, dashboards, timelines)


---

## ⚙️ Setup Instructions

> 🚧 Coming soon... Full setup steps with tested scripts will be added here.

### Planned Instructions:
- System prerequisites and dependencies
- Step-by-step installation using `setup/*.sh`
- Enabling and verifying services (Wazuh, ELK)
- Feeding test logs
- Viewing alerts in Kibana
- Generating detection reports

---

## 📌 Project Goals

- ✅ Real-time log monitoring from agents and endpoints
- ✅ Threat detection via Wazuh rules
- ✅ Custom dashboards in Kibana
- ✅ Sample detection tests using logs
- ✅ Reports and screenshots as documentation

---

## 🧪 Sample Tests (Planned)

- SSH brute-force attack simulation
- Suspicious login attempts
- Port scan detection
- File integrity monitoring (FIM)

---

## 📸 Dashboards & Screenshots

Find sample screenshots under the `/screenshots` directory:
- SIEM dashboard
- Login anomalies
- Geo-location maps of attackers
- Rule matches and alert levels

---

## 👩‍💻 Author

**Safwana Nasrin**  
📁 GitHub: [SafwanaNasrin](https://github.com/SafwanaNasrin)  

---

## 📄 License

This project is licensed under the **MIT License**.  
Feel free to fork, customize, and improve for educational or professional use.

✅ Save It

To save and push this to your GitHub project:

cd ~/wazuh-elk-siem-project
nano README.md
# Paste the content
# Save with Ctrl+O, Enter, then Ctrl+X

git add README.md
git commit -m "Initial README added for Wazuh + ELK SIEM project"
git push
