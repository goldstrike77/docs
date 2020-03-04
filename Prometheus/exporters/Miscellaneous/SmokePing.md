### SmokePing metrics exposed

#### Related Exporters or Integrations
- [smokeping_prober](https://github.com/SuperQ/smokeping_prober)

#### Exporter collectors enabled by default

Name     | Description 
---------|-------------
default|Default metrics supplied

#### Alert rules
Name|Severity|Description
-|-|-
Ping_lost|warning|Ping package loss too much.

#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-linux-prometheus](https://github.com/goldstrike77/ansible-role-linux-prometheus)

#### Recommendation Grafana Dashboards
- Smoke Ping | [json](https://raw.githubusercontent.com/goldstrike77/ansible-role-linux-grafana/master/files/dashboards/Universal/Smoke_Ping.json) | [png](https://raw.githubusercontent.com/goldstrike77/Screenshots/master/Grafana/Universal/Smoke_Ping.png)