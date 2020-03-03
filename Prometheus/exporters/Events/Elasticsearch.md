### Elasticsearch Cluster metrics exposed

#### Related Exporters or Integrations
- [elasticsearch_exporter](https://github.com/justwatchcom/elasticsearch_exporter)

#### Exporter collectors enabled by default
Name     | Description 
---------|-------------
es.cluster_settings|Query stats for cluster settings.
es.indices|Query stats for all indices in the cluster.
es.indices_settings|Query settings stats for all indices in the cluster.
es.shards|Query stats for all indices in the cluster, including shard-level stats
es.snapshots|Query stats for the cluster snapshots.

#### Alert rules
Name|Severity|Description
-|-|-
Elastic_Instance|critical|ElasticSearch node has been stoped.
Elastic_Heap_Usage|warning|ElasticSearch node heap usage is over 90%.
Elastic_Cluster_Health|warning|Not all primary and replica shards are allocated in cluster.
Elastic_JVM_GC_Runs|warning|JVM GC per seconds more than 5.
Elastic_JVM_GC_Run_Time|warning|JVM GC run time in seconds more than 0.5.
Elastic_json_parse_failures|warning|JSON parse failures.
Elastic_breakers_tripped|warning|Breakers tripped.
Elastic_relocation_shards|warning|Number of relocation shards for 30 minutes.
Elastic_initializing_shards|warning|Number of initializing shards for 30 minutes.
Elastic_pending_tasks|warning|Number of pending tasks for 30 minutes.

#### Reference third-party Ansible role for RHEL/CentOS
- [ansible-role-linux-elasticsearch](https://github.com/goldstrike77/ansible-role-linux-elasticsearch)

#### Recommendation Grafana Dashboards
- Elasticsearch Overview | [json](https://raw.githubusercontent.com/goldstrike77/ansible-role-linux-grafana/master/files/dashboards/Universal/Elasticsearch_Overview.json) | [png](https://raw.githubusercontent.com/goldstrike77/Screenshots/master/Grafana/Universal/Elasticsearch_Overview.png)