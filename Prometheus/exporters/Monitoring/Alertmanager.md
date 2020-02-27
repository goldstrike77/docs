### Alertmanager server metrics exposed

#### Related Exporters or Integrations
- Build-in

#### Exporter collectors enabled by default
Name     | Description 
---------|-------------
default|Default metrics supplied

#### Alert rules
Name|Severity|Description
-|-|-
alertmanager_Notifications_Failed|warning|Alertmanager is seeing errors for integration.
alertmanager_Configuration_Reload|critical|Alertmanager configuration reload error.


#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-linux-prometheus](https://github.com/goldstrike77/ansible-role-linux-prometheus)

#### Recommendation Grafana Dashboards
- Alertmanager Overview | [json](https://raw.githubusercontent.com/goldstrike77/ansible-role-linux-grafana/master/files/dashboards/Universal/Alertmanager_Overview.json) | [png](https://raw.githubusercontent.com/goldstrike77/Screenshots/master/Grafana/Universal/Alertmanager_Overview.png)