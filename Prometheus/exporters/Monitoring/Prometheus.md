### Prometheus server metrics exposed

#### Related Exporters or Integrations
- Build-in

#### Exporter collectors enabled by default
Name     | Description 
---------|-------------
default|Default metrics supplied

#### Alert rules
Name|Severity|Description
-|-|-
prometheus_Configuration_Reload|critical|Prometheus configuration reload error.
prometheus_Disconnect_Alertmanager|warning|Prometheus cannot connect the alertmanager.


#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-linux-prometheus](https://github.com/goldstrike77/ansible-role-linux-prometheus)

#### Recommendation Grafana Dashboards
- Prometheus Overview | [json](https://raw.githubusercontent.com/goldstrike77/ansible-role-linux-grafana/master/files/dashboards/Universal/Prometheus_Overview.json) | [png](https://raw.githubusercontent.com/goldstrike77/Screenshots/master/Grafana/Universal/Prometheus_Overview.png)