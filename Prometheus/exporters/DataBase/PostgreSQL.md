### PostgreSQL server metrics exposed

#### Related Exporters or Integrations
- [postgres_exporter](https://github.com/wrouesnel/postgres_exporter)

#### Exporter collectors enabled by default
Name     | Description 
---------|-------------
default|Default metrics supplied

#### Alert rules
Name|Severity|Description
-|-|-
PostgreSQL_Instance|critical|Instance has been stoped.
PostgreSQL_Rep_Lag|warning|The replication has fallen behind and is not recovering.
PostgreSQL_TableNotVaccumed|warning|Table has not been vaccum for 24 hours.
PostgreSQL_TableNotAnalyzed|warning|Table has not been analyzed for 24 hours.
PostgreSQL_Dead_locks|warning|PostgreSQL has dead-locks.

#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-linux-postgresql](https://github.com/goldstrike77/ansible-role-linux-postgresql)

#### Recommendation Grafana Dashboards
- PostgreSQL Overview | [json](https://raw.githubusercontent.com/goldstrike77/ansible-role-linux-grafana/master/files/dashboards/Databases/PostgreSQL_Overview.json) | [png](https://raw.githubusercontent.com/goldstrike77/Screenshots/master/Grafana/Databases/PostgreSQL_Overview.png)