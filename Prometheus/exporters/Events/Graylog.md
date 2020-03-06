### Graylog metrics exposed

#### Related Exporters or Integrations
- [graylog_exporter](https://github.com/graylog-labs/graylog-plugin-metrics-reporter/tree/master/metrics-reporter-prometheus)

#### Exporter collectors enabled by default
Name     | Description 
---------|-------------
default|Default metrics supplied

#### Alert rules
Name|Severity|Description
-|-|-
graylog_Journal_Utilization|critical|The message journal store utilization ratio has more than 90%.

#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-linux-graylog](https://github.com/goldstrike77/ansible-role-linux-graylog)

#### Recommendation Grafana Dashboards
- Graylog Overview | [json](https://raw.githubusercontent.com/goldstrike77/ansible-role-linux-grafana/master/files/dashboards/Universal/Graylog_Overview.json) | [png](https://raw.githubusercontent.com/goldstrike77/Screenshots/master/Grafana/Universal/Graylog_Overview.png)