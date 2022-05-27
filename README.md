# Minecraft Exporter for Prometheus

![Version: 11.1.5](https://img.shields.io/badge/Version-11.1.5-informational?style=for-the-badge)

![AppVersion: 1.21.6](https://img.shields.io/badge/AppVersion-1.21.6-informational?style=for-the-badge)

## Description

NGINX Open Source is a web server that can be also used as a reverse proxy, load balancer, and HTTP cache. Recommended for high-demanding sites due to its ability to provide faster content.

## Usage
<fill out>

## Source Code

* <https://github.com/bitnami/bitnami-docker-nginx>
* <https://www.nginx.org>

## Maintainers

| Name | Email | Url |
| ---- | ------ | --- |
| Bitnami | <containers@bitnami.com> |  |

## Values

| Key | Type | Default | Description |
|-----|------|---------|-------------|
| affinity | object | `{}` | Aca va la descripcion  |
| args | list | `[]` | Aca va una descripcion  |
| autoscaling.enabled | bool | `false` |  |
| autoscaling.maxReplicas | string | `""` |  |
| autoscaling.minReplicas | string | `""` |  |
| autoscaling.targetCPU | string | `""` |  |
| autoscaling.targetMemory | string | `""` |  |
| cloneStaticSiteFromGit.args | list | `[]` |  |
| cloneStaticSiteFromGit.branch | string | `""` |  |
| cloneStaticSiteFromGit.enabled | bool | `false` |  |
| cloneStaticSiteFromGit.extraEnvVars | list | `[]` |  |
| cloneStaticSiteFromGit.extraVolumeMounts | list | `[]` |  |
| cloneStaticSiteFromGit.gitClone.args | list | `[]` |  |
| cloneStaticSiteFromGit.gitClone.command | list | `[]` |  |
| cloneStaticSiteFromGit.gitSync.command | list | `[]` |  |
| cloneStaticSiteFromGit.image.pullPolicy | string | `"IfNotPresent"` |  |
| cloneStaticSiteFromGit.image.pullSecrets | list | `[]` |  |
| cloneStaticSiteFromGit.image.registry | string | `"docker.io"` |  |
| cloneStaticSiteFromGit.image.repository | string | `"bitnami/git"` |  |
| cloneStaticSiteFromGit.image.tag | string | `"2.36.1-debian-10-r13"` |  |
| cloneStaticSiteFromGit.interval | int | `60` |  |
| cloneStaticSiteFromGit.repository | string | `""` |  |
| clusterDomain | string | `"cluster.local"` |  |
| command | list | `[]` |  |
| commonAnnotations | object | `{}` |  |
| commonLabels | object | `{}` |  |
| containerPorts.http | int | `8080` |  |
| containerPorts.https | string | `""` |  |
| containerSecurityContext.enabled | bool | `false` |  |
| containerSecurityContext.runAsNonRoot | bool | `true` |  |
| containerSecurityContext.runAsUser | int | `1001` |  |
| customLivenessProbe | object | `{}` |  |
| customReadinessProbe | object | `{}` |  |
| customStartupProbe | object | `{}` |  |
| diagnosticMode.args[0] | string | `"infinity"` |  |
| diagnosticMode.command[0] | string | `"sleep"` |  |
| diagnosticMode.enabled | bool | `false` |  |
| existingServerBlockConfigmap | string | `""` |  |
| extraDeploy | list | `[]` |  |
| extraEnvVars | list | `[]` |  |
| extraEnvVarsCM | string | `""` |  |
| extraEnvVarsSecret | string | `""` |  |
| extraVolumeMounts | list | `[]` |  |
| extraVolumes | list | `[]` |  |
| fullnameOverride | string | `""` |  |
| global.imagePullSecrets | list | `[]` |  |
| global.imageRegistry | string | `""` |  |
| healthIngress.annotations | object | `{}` |  |
| healthIngress.enabled | bool | `false` |  |
| healthIngress.extraHosts | list | `[]` |  |
| healthIngress.extraPaths | list | `[]` |  |
| healthIngress.extraRules | list | `[]` |  |
| healthIngress.extraTls | list | `[]` |  |
| healthIngress.hostname | string | `"example.local"` |  |
| healthIngress.ingressClassName | string | `""` |  |
| healthIngress.path | string | `"/"` |  |
| healthIngress.pathType | string | `"ImplementationSpecific"` |  |
| healthIngress.secrets | list | `[]` |  |
| healthIngress.selfSigned | bool | `false` |  |
| healthIngress.tls | bool | `false` |  |
| hostAliases | list | `[]` |  |
| hostIPC | bool | `false` |  |
| hostNetwork | bool | `false` |  |
| image.debug | bool | `false` |  |
| image.pullPolicy | string | `"IfNotPresent"` |  |
| image.pullSecrets | list | `[]` |  |
| image.registry | string | `"docker.io"` |  |
| image.repository | string | `"bitnami/nginx"` |  |
| image.tag | string | `"1.21.6-debian-10-r114"` |  |
| ingress.annotations | object | `{}` |  |
| ingress.apiVersion | string | `""` |  |
| ingress.enabled | bool | `false` |  |
| ingress.extraHosts | list | `[]` |  |
| ingress.extraPaths | list | `[]` |  |
| ingress.extraRules | list | `[]` |  |
| ingress.extraTls | list | `[]` |  |
| ingress.hostname | string | `"nginx.local"` |  |
| ingress.ingressClassName | string | `""` |  |
| ingress.path | string | `"/"` |  |
| ingress.pathType | string | `"ImplementationSpecific"` |  |
| ingress.secrets | list | `[]` |  |
| ingress.selfSigned | bool | `false` |  |
| ingress.tls | bool | `false` |  |
| initContainers | list | `[]` |  |
| kubeVersion | string | `""` |  |
| lifecycleHooks | object | `{}` |  |
| livenessProbe.enabled | bool | `true` |  |
| livenessProbe.failureThreshold | int | `6` |  |
| livenessProbe.initialDelaySeconds | int | `30` |  |
| livenessProbe.periodSeconds | int | `10` |  |
| livenessProbe.successThreshold | int | `1` |  |
| livenessProbe.timeoutSeconds | int | `5` |  |
| metrics.enabled | bool | `false` |  |
| metrics.image.pullPolicy | string | `"IfNotPresent"` |  |
| metrics.image.pullSecrets | list | `[]` |  |
| metrics.image.registry | string | `"docker.io"` |  |
| metrics.image.repository | string | `"bitnami/nginx-exporter"` |  |
| metrics.image.tag | string | `"0.10.0-debian-10-r146"` |  |
| metrics.podAnnotations | object | `{}` |  |
| metrics.port | string | `""` |  |
| metrics.prometheusRule.additionalLabels | object | `{}` |  |
| metrics.prometheusRule.enabled | bool | `false` |  |
| metrics.prometheusRule.namespace | string | `""` |  |
| metrics.prometheusRule.rules | list | `[]` |  |
| metrics.resources.limits | object | `{}` |  |
| metrics.resources.requests | object | `{}` |  |
| metrics.securityContext.enabled | bool | `false` |  |
| metrics.securityContext.runAsUser | int | `1001` |  |
| metrics.service.annotations."prometheus.io/port" | string | `"{{ .Values.metrics.service.port }}"` |  |
| metrics.service.annotations."prometheus.io/scrape" | string | `"true"` |  |
| metrics.service.port | int | `9113` |  |
| metrics.serviceMonitor.enabled | bool | `false` |  |
| metrics.serviceMonitor.honorLabels | bool | `false` |  |
| metrics.serviceMonitor.interval | string | `""` |  |
| metrics.serviceMonitor.jobLabel | string | `""` |  |
| metrics.serviceMonitor.labels | object | `{}` |  |
| metrics.serviceMonitor.metricRelabelings | list | `[]` |  |
| metrics.serviceMonitor.namespace | string | `""` |  |
| metrics.serviceMonitor.relabelings | list | `[]` |  |
| metrics.serviceMonitor.scrapeTimeout | string | `""` |  |
| metrics.serviceMonitor.selector | object | `{}` |  |
| nameOverride | string | `""` |  |
| namespaceOverride | string | `""` |  |
| nodeAffinityPreset.key | string | `""` |  |
| nodeAffinityPreset.type | string | `""` |  |
| nodeAffinityPreset.values | list | `[]` |  |
| nodeSelector | object | `{}` |  |
| pdb.create | bool | `false` |  |
| pdb.maxUnavailable | int | `0` |  |
| pdb.minAvailable | int | `1` |  |
| podAffinityPreset | string | `""` |  |
| podAnnotations | object | `{}` |  |
| podAntiAffinityPreset | string | `"soft"` |  |
| podLabels | object | `{}` |  |
| podSecurityContext.enabled | bool | `false` |  |
| podSecurityContext.fsGroup | int | `1001` |  |
| podSecurityContext.sysctls | list | `[]` |  |
| priorityClassName | string | `""` |  |
| readinessProbe.enabled | bool | `true` |  |
| readinessProbe.failureThreshold | int | `3` |  |
| readinessProbe.initialDelaySeconds | int | `5` |  |
| readinessProbe.periodSeconds | int | `5` |  |
| readinessProbe.successThreshold | int | `1` |  |
| readinessProbe.timeoutSeconds | int | `3` |  |
| replicaCount | int | `1` |  |
| resources.limits | object | `{}` |  |
| resources.requests | object | `{}` |  |
| schedulerName | string | `""` |  |
| serverBlock | string | `""` |  |
| service.annotations | object | `{}` |  |
| service.clusterIP | string | `""` |  |
| service.externalTrafficPolicy | string | `"Cluster"` |  |
| service.extraPorts | list | `[]` |  |
| service.loadBalancerIP | string | `""` |  |
| service.loadBalancerSourceRanges | list | `[]` |  |
| service.nodePorts.http | string | `""` |  |
| service.nodePorts.https | string | `""` |  |
| service.ports.http | int | `80` |  |
| service.ports.https | int | `443` |  |
| service.sessionAffinity | string | `"None"` |  |
| service.sessionAffinityConfig | object | `{}` |  |
| service.targetPort.http | string | `"http"` |  |
| service.targetPort.https | string | `"https"` |  |
| service.type | string | `"LoadBalancer"` |  |
| serviceAccount.annotations | object | `{}` |  |
| serviceAccount.automountServiceAccountToken | bool | `false` |  |
| serviceAccount.create | bool | `false` |  |
| serviceAccount.name | string | `""` |  |
| sidecarSingleProcessNamespace | bool | `false` |  |
| sidecars | list | `[]` |  |
| startupProbe.enabled | bool | `false` |  |
| startupProbe.failureThreshold | int | `6` |  |
| startupProbe.initialDelaySeconds | int | `30` |  |
| startupProbe.periodSeconds | int | `10` |  |
| startupProbe.successThreshold | int | `1` |  |
| startupProbe.timeoutSeconds | int | `5` |  |
| staticSiteConfigmap | string | `""` |  |
| staticSitePVC | string | `""` |  |
| terminationGracePeriodSeconds | string | `""` |  |
| tolerations | object | `{}` |  |
| topologySpreadConstraints | list | `[]` |  |
| updateStrategy.rollingUpdate | object | `{}` |  |
| updateStrategy.type | string | `"RollingUpdate"` |  |

**Homepage:** <https://github.com/bitnami/charts/tree/master/bitnami/nginx>

