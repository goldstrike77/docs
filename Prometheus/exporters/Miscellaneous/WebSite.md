### Blackbox metrics exposed

#### Related Exporters or Integrations
- [blackbox_exporter](https://github.com/prometheus/blackbox_exporter)

#### Exporter collectors enabled by default

Name     | Description 
---------|-------------
default|Default metrics supplied

#### Alert rules
Name|Severity|Description
-|-|-
WebSite|critical|Endpoint has been unreachable.
SSLCertExpiringSoon|warning|SSL certificate expires.
StatusCode|warning|HTTP status code is not 1xx-3xx.

#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-linux-prometheus](https://github.com/goldstrike77/ansible-role-linux-prometheus)

#### Recommendation Grafana Dashboards
- WebSite Overview | [json](https://raw.githubusercontent.com/goldstrike77/ansible-role-linux-grafana/master/files/dashboards/Universal/WebSite_Overview.json) | [png](https://raw.githubusercontent.com/goldstrike77/Screenshots/master/Grafana/Universal/WebSite_Overview.png)