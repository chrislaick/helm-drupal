# solr

![Version: 0.1.10](https://img.shields.io/badge/Version-0.1.10-informational?style=flat-square) ![Type: application](https://img.shields.io/badge/Type-application-informational?style=flat-square) ![AppVersion: 8.11.3](https://img.shields.io/badge/AppVersion-8.11.3-informational?style=flat-square)

A Helm chart for a Solr instance using the official Solr Operator.

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| destinationRule.enabled | bool | `false` |  |
| destinationRule.mode | string | `"DISABLE"` |  |
| ingress.annotations | object | `{}` |  |
| ingress.enabled | bool | `false` |  |
| ingress.hosts[0] | string | `"chart-example.local"` |  |
| ingress.path | string | `"/.*"` |  |
| ingress.pathType | string | `"ImplementationSpecific"` |  |
| ingress.tls | list | `[]` |  |
| solr.basicAuthSecret | string | `nil` |  |
| solr.replicas | int | `1` |  |
| solr.solrJavaMem | string | `"-Xms1g -Xmx5g"` |  |
| solr.storage.size | string | `"5Gi"` |  |
| zookeeper.replicas | int | `1` |  |
| zookeeper.resources | object | `{}` |  |
| zookeeper.storage.size | string | `"5Gi"` |  |

----------------------------------------------
Autogenerated from chart metadata using [helm-docs v1.12.0](https://github.com/norwoodj/helm-docs/releases/v1.12.0)