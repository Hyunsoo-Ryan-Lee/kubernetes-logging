# kubernetes-logging
- efk stack installation for kubernetes

## 0. 디렉토리 구조
```
.
├── 01_Namespace.yml
├── 02_ElasticSearch_Service.yaml
├── 03_ElasticSearch_StatefulSet.yaml
├── 07_Kibana_Deployment.yaml
├── 08_Kibana_Service.yaml
├── 09_Kibana_Ingress.yaml
├── fluent-bit
│   ├── 10_FluentBit_rbac.yaml
│   ├── 11_FluentBit_cm.yaml
│   ├── 12_FluentBit_ds.yaml
│   └── 90_FluentBit_test.yaml
├── fluent-bit-local
│   ├── 01_fluentbit-rbac.yaml
│   ├── 02_fluentbit-cm.yaml
│   ├── 03_fluentbit-ds.yaml
│   └── memo.txt
├── fluentd
│   ├── 04_Fluentd_ConfigMap.yaml
│   ├── 05_Fluend_rbac.yaml
│   └── 06_Fluend_DaemonSet.yaml
├── README.md
└── sample-app.yaml
```