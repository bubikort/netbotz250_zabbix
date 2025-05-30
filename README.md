#NetBotz 250 Zabbix Template

Based on the following template:
https://github.com/zabbix/community-templates/tree/main/SCADA_IoT_Energy_Home_Automation_Industrial_monitoring/Monitoring_Equipment/template_apc_netbotz_monitor_2xx/6.0

Changes and Additions

Added two new LLD (Low-Level Discovery) rules with corresponding items and triggers:
	•	Smoke Sensor
	•	Fluid Sensor

Features
	•	Automatically discovers all connected smoke and fluid sensors, regardless of which port they are connected to.
	•	Adds two related item checks for each discovered sensor:
  	•	Is smoke detected
	  •	Is fluid detected
	•	Trigger thresholds are based on the configuration set in the NetBotz GUI.

⸻

Let me know if you’d like it adapted for a README file or documentation.
