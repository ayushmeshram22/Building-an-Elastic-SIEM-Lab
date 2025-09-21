
# SIEM Log Monitoring & Threat Detection

Building an Elastic SIEM Lab && splunk labs
Overview

This project is all about creating a hands-on Security Information and Event Management (SIEM) lab using Elastic SIEM and a Kali Linux VM. The idea is to collect and analyze logs from a system, visualize them on dashboards, and get alerts for specific security events. We’ll generate some sample security events using Nmap scans and forward them to Elastic for monitoring.

This lab is perfect if you want to learn how real-world security monitoring works and how SIEM tools help detect threats.

Tools Used

Oracle VirtualBox – to run our virtual machines

Kali Linux – for generating security events and testing

Elastic Stack – Elasticsearch, Kibana, and Elastic Agent for log collection and analysis

Nmap – to simulate network activity and security events


🔐 ELK Stack SIEM Lab — Log Monitoring & Threat Detection

This project is a hands-on Security Information and Event Management (SIEM) lab built with the Elastic Stack (Elasticsearch, Logstash, Kibana).
It demonstrates how to ingest, parse, and analyze logs from Windows and Linux systems, and detect simulated cyberattacks in real time.

Key highlights:

📥 Log Ingestion:

Windows Sysmon logs (via Winlogbeat).

Linux authentication logs (via Filebeat).

🛡 Threat Detection:

Detect SSH brute-force attempts from Linux auth logs.

Identify suspicious PowerShell activity (e.g., encoded commands) from Sysmon logs.

📊 Visualization & Alerts:

Custom Kibana dashboards for real-time log monitoring.

Detection rules and alerts for brute-force and malicious PowerShell usage.

⚔ Attack Simulation:

SSH brute-force attacks using Hydra from Kali Linux.

Obfuscated PowerShell commands to trigger Sysmon detections.

💡 Learning Outcomes:

Gain practical experience with the ELK stack as a SIEM.

Understand log ingestion pipelines, enrichment, and visualization.

Explore detection engineering by creating rules against real attack scenarios.

This project is perfect for students, SOC analysts, and cybersecurity enthusiasts who want a safe, lab-based environment to practice log monitoring, detection engineering, and SIEM operations.











