Real-Time Healthcare IoT Network Monitoring
This project helps hospitals monitor their IoT devices (like patient monitors, ventilators, lab machines, etc.) in real time so there is no downtime.
If any device goes offline or shows high CPU/Memory usage, you get alerts instantly.
This makes the hospital safer and more reliable.

Why This Project?

Hospitals use many connected devices.
Even a small failure can affect patient care.

This system helps you:
	•	Watch all devices in real time
	•	Know when a device is slow or failing
	•	Get alerts instantly
	•	See everything on a dashboard

  Tool used and What it does
  •	Zabbix Collects all monitoring data
  •	Grafana Shows dashboards and graphs
  •	SNMP Talks to IoT devices
  •	MariaDB / MySQL Stores Zabbix data
  •	Docker Runs everything easily
  •	Ubuntu Operating System

How the System Works
IoT Devices → Zabbix → Grafana → You (Dashboard)
Devices send data using SNMP
	•	Zabbix collects it
	•	Grafana displays beautiful graphs

  Start everything with Docker
  docker-compose up -d

  Open the websites
  Tool                Link
Zabbix Web UI         http://192.168.64.3:8080
Username: Admin
Password: zabbix

Grafana               http://192.168.64.3:3000
Username: admin
Password: admin

What You Can Improve Later
	•	Add NETCONF device monitoring
	•	Add AI predictions
	•	Add alert notifications (SMS/Email)
	•	Add more IoT device templates

Author -YASH MR



