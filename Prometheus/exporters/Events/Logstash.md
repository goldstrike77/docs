### Logstash metrics exposed

#### Related Exporters or Integrations
- [logstash_exporter](https://github.com/BonnierNews/logstash_exporter)

#### Exporter collectors enabled by default
Name     | Description 
---------|-------------
default|Default metrics supplied

#### Alert rules
Name|Severity|Description
-|-|-
logstash_Instance|critical|Endpoint has been unreachable.

#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-linux-logstash](https://github.com/goldstrike77/ansible-role-linux-logstash)

#### Recommendation Grafana Dashboards
- Logstash Overview | [json](https://raw.githubusercontent.com/goldstrike77/ansible-role-linux-grafana/master/files/dashboards/Universal/Logstash_Overview.json) | [png](https://raw.githubusercontent.com/goldstrike77/Screenshots/master/Grafana/Universal/Logstash_Overview.png)