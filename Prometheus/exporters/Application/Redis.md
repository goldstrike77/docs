### Redis server metrics exposed

#### Related Exporters or Integrations
- [redis_exporter](https://github.com/oliver006/redis_exporter)
- [redis_sentinel](https://github.com/leominov/redis_sentinel_exporter)

#### Exporter collectors enabled by default
Name     | Description 
---------|-------------
default|Default metrics supplied

#### Alert rules
Name|Severity|Description
-|-|-
redis_Instance|critical|Redis has been stoped.
redis_Sentinel|critical|Redis Sentinel has been stoped.
redis_Rejected|warning|Some connections to Redis has been rejected.
redis_RAM_Usage|warning|Redis Memory usage has more than 90%.
redis_Rep|warning|Redis instance lost a slave.
redis_Master_LinkDown|critical|Redis master link has been down.

#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-linux-redis](https://github.com/goldstrike77/ansible-role-linux-redis)

#### Recommendation Grafana Dashboards
- Redis Overview| [json](https://raw.githubusercontent.com/goldstrike77/ansible-role-linux-grafana/master/files/dashboards/Universal/Redis_Overview.json) | [png](https://raw.githubusercontent.com/goldstrike77/Screenshots/master/Grafana/Universal/Redis_Overview.png)