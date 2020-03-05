### Thanos metrics exposed

#### Related Exporters or Integrations
- Build-in

#### Exporter collectors enabled by default
Name     | Description 
---------|-------------
default|Default metrics supplied

#### Alert rules
Name|Severity|Description
-|-|-
Thanos_Compact_Halted|critical|Thanos compaction has failed to run and now is halted.
Thanos_Compact_CompactionsFailed|warning|Thanos Compact is failing compaction.
Thanos_Compact_BucketOperationsFailed|warning|Thanos Compact bucket operations are failing.
Thanos_Compact_NotRunIn24Hours|warning|Thanos Compaction has not been run in 24 hours.
Thanos_Compact_IsNotRunning|warning|Thanos Compaction is not running.
Thanos_Compact_MultipleCompactionsAreRunning|warning|Multiple replicas of Thanos compaction shouldn't be running.
Thanos_Store_GrpcErrorRate|warning|Thanos Store is returning Internal/Unavailable errors.
Thanos_Store_BucketOperationsFailed|warning|Thanos Store is failing to do bucket operations.
Thanos_Sidecar_Prometheus|critical|Thanos Sidecar cannot connect to Prometheus.
Thanos_Sidecar_BucketOperationsFailed|warning|Thanos Sidecar bucket operations are failing.
Thanos_Sidecar_GrpcErrorRate|warning|Thanos Sidecar is returning Internal/Unavailable errors.
Thanos_Query_GrpcErrorRate|warning|Thanos Query is returning Internal/Unavailable errors.

#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-linux-prometheus](https://github.com/goldstrike77/ansible-role-linux-prometheus)

#### Recommendation Grafana Dashboards
- Coming soon