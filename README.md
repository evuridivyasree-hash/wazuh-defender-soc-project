# wazuh-defender-soc-project
# Real-Time Threat Detection using Wazuh & Windows Defender

## Overview
This project demonstrates real-time threat detection by integrating Wazuh SIEM with Windows Defender.

## Objectives
- Monitor endpoint security events
- Detect malware activity
- Identify failed login attempts (brute force simulation)
- Analyze alerts in Wazuh dashboard

## Tools Used
- Wazuh SIEM
- Windows Defender
- Oracle VirtualBox
- Windows 10

## Configuration
- Installed Wazuh server and agent
- Connected Windows agent to Wazuh
- Enabled Defender log monitoring
- Configured Security event logs

## Attack Simulation

### 1. Malware Detection
- Used EICAR test file
- Defender detected and quarantined malware
- Wazuh generated alerts

### 2. Brute Force Simulation
- Multiple failed login attempts
- Event ID 4625 detected
- Alerts generated in Wazuh

## Results
- Real-time malware detection
- Authentication failure monitoring
- Alert visualization in dashboard
- MITRE ATT&CK mapping

## Screenshots
<img width="1280" height="800" alt="Wazuh dashboard - Agent Active" src="https://github.com/user-attachments/assets/e2a4b198-7996-4c56-a101-2c71fceeb540" />
<img width="1918" height="1017" alt="powershell - wazuh service running" src="https://github.com/user-attachments/assets/03722cd2-5f47-407b-8a55-fdbb51f1000c" />
<img width="1918" height="1013" alt="ossec conf edited" src="https://github.com/user-attachments/assets/63388d06-ed04-4c55-82fb-15fd3404f1b7" />
<img width="1918" height="1017" alt="powershell - wazuh service running" src="https://github.com/user-attachments/assets/d931524a-d650-4c87-bcbb-22290d952697" />
<img width="1918" height="1002" alt="virus" src="https://github.com/user-attachments/assets/ced1f5a3-55fd-46f3-8234-82e06ae63781" />
<img width="1918" height="693" alt="threat qua" src="https://github.com/user-attachments/assets/d82f3026-e2b4-4117-b4a8-0db82d5f0b04" />
<img width="1917" height="983" alt="wazuhalert" src="https://github.com/user-attachments/assets/6464d29d-140e-4972-ab54-e2a600d38f5d" />
<img width="1918" height="1018" alt="wazuhdashboard" src="https://github.com/user-attachments/assets/8e7278c4-12c5-4cb9-9415-dbf23e7e0eb6" />
<img width="1918" height="1015" alt="wazuh scan" src="https://github.com/user-attachments/assets/405d38b7-c375-4f35-ab80-db5632162778" />
<img width="1918" height="1013" alt="wazuh scan1" src="https://github.com/user-attachments/assets/09ecc7d7-d426-45e4-b85d-9c4b71f1c33b" />
<img width="1918" height="1020" alt="failedlogin graph" src="https://github.com/user-attachments/assets/f214d67a-219b-486c-bc7b-0b6dd189b624" />
<img width="1918" height="1021" alt="alert evolution" src="https://github.com/user-attachments/assets/6a9ddd43-ed1f-4936-8e34-6e26d6add55d" />
<img width="1918" height="1020" alt="failed login password" src="https://github.com/user-attachments/assets/fb5e0455-549c-4594-a566-90f593a0dba9" />
<img width="1918" height="1022" alt="failedlogin details" src="https://github.com/user-attachments/assets/77a4e4fe-e34f-42e2-8c09-c2bdb4f8c6d4" />
<img width="1918" height="977" alt="failedlogin details1" src="https://github.com/user-attachments/assets/c6dd3b61-2998-44b6-afed-4677f9485300" />

## Skills Gained
- SIEM monitoring (Wazuh)
- Threat detection & analysis
- Log analysis (Windows Events)
- SOC Level 1 practical skills

## Conclusion
This project simulates real-world SOC operations by integrating endpoint protection with SIEM for effective threat detection.
