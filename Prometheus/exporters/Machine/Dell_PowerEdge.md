### Dell PowerEdge Server metrics exposed

#### Related Exporters or Integrations
- [ansible-role-OS-bootstrap](https://github.com/goldstrike77/ansible-role-OS-bootstrap)

#### Exporter collectors enabled by default

Name     | Description 
---------|-------------
chassis|Overall status of chassis components.
chassis_batteries|Overall status of chassis CMOS batteries.
fans|Overall status of system fans.
memory|System RAM DIMM status.
nics|NICs connection status.
processors|Overall status of CPUs.
ps|Overall status of power supplies.
ps_amps_sysboard_pwr|System board power usage.
storage_battery|Status of storage controller backup batteries.
storage_controller|Overall status of storage controllers.
storage_enclosure|Overall status of storage enclosures.
storage_pdisk|Overall status of physical disks.
storage_vdisk|Overall status of virtual disks.
system|Overall status of system components.
temps|Overall temperatures (in Celsius) and status of system temperature readings.
volts|Overall volts and status of power supply volt readings.

#### Alert rules
Name|Severity|Description
-|-|-
Batteries|critical|System Board CMOS Battery has been failured.
Cooling|critical|System Cooling component has been failured.
Intrusion|critical|System Board Intrusion has been failured.
Memory|critical|System Board Memory has been failured.
Power_Supplies|critical|Power Supplies has been failured.
Processors|critical|CPU/GPU has been failured.
Temperatures|critical|Temperature Probes has been failured.
Voltages|critical|System Board Voltages has been failured.
Storage_battery|critical|Storage Controller Battery has been failured.
Storage_Controller|critical|Storage Controller has been failured.
Storage_Enclosure|critical|Storage Enclosure has been failured.
Storage_Pdisk|critical|Physical disks has been failured.
Storage_Vdisk|critical|Virtual disks has been failured.
Inlet_Temperature|critical|Temperatures has exceeded the threshold.

#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-OS-bootstrap](https://github.com/goldstrike77/ansible-role-OS-bootstrap)
- [ansible-role-OS-consul](https://github.com/goldstrike77/ansible-role-OS-consul)
- [ansible-role-linux-prometheus](https://github.com/goldstrike77/ansible-role-linux-prometheus)
- [ansible-role-linux-grafana](https://github.com/goldstrike77/ansible-role-linux-grafana)

#### Recommendation Grafana Dashboards
- Dell PowerEdge | [json](https://raw.githubusercontent.com/goldstrike77/ansible-role-linux-grafana/master/files/dashboards/Cloud/Dell_PowerEdge.json) | [png](https://raw.githubusercontent.com/goldstrike77/Screenshots/master/Grafana/Cloud/Dell_PowerEdge.png)