# elk-helm-chart
elk-helm-chart
```shell
tree elk-helm-chart/ 
elk-helm-chart/
├── Chart.yaml
├── filebeat.yaml
├── logstash.conf
├── templates
│   ├── elastisearch.yaml
│   ├── kibana.yaml
│   ├── logging-app-and-filebeat.yaml
│   └── logstash.yaml
└── values.yaml

run: 
helm install elk-auto/ --set global.hostIp=$(Node ip)
