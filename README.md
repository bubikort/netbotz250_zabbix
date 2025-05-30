# netbotz250_zabbix template

based on this one: https://github.com/zabbix/community-templates/tree/main/SCADA_IoT_Energy_Home_Automation_Industrial_monitoring/Monitoring_Equipment/template_apc_netbotz_monitor_2xx/6.0

Added two new LLD Discovery with Items, and Triggers
- Smoke Sensor
- Fluid Sensor

Automatically discovery all connected smoke and fluid sensor and add the two related item check(Is smoke/fluid detected), no matter in which port you are connected the devices. 
All trigger's thresholds comes from what you set up on the GUI of netbotz.
