# one-person-company
一人公司：只需要一个人就有可能运维一个公司，组合 Cloud Native 并完整设计技术架构（CNCF + Alibaba）。

- CNCF landscape(https://github.com/cncf/landscape https://landscape.cncf.io)
- Alibaba Open Source(https://github.com/Alibaba)

TODO 逐步补充，架构图.jpg、实践说明.md

## Infrastructure Components eg: 

### Cluster
- <img alt="KebeVela" src="https://kubevela.net/img/logo.svg" width="24" align="center" />KebeVela(OAM https://github.com/oam-dev/kubevela)
  - Terraform(https://www.terraform.io) IaC: Infrastructure as Code
  - <img alt="Configure Unify Execute" src="https://cuelang.org/images/cue.svg" width="20" align="center" /> CUE(https://cuelang.org)
- <img alt="Open Cluster Management" src="https://open-cluster-management.io/ocm.svg" width="24" align="center" />Open Cluster Management(https://github.com/open-cluster-management-io/OCM https://open-cluster-management.io)

### Cloud
- Alibaba Cloud
- Tecent Cloud
- Private Cloud

### Cloud Native Container
- Istio(https://github.com/istio/istio)
- Envoy(https://github.com/envoyproxy/envoy)
  - WebAssembly(https://github.com/WebAssembly/WASI)

- <img alt="Kubernetes" src="https://kubernetes.io/images/wheel.svg" width="22" align="center" /> Kubernetes(https://github.com/kubernetes/kubernetes)
  - <img alt="OpenKruise" src="https://cdn.jsdelivr.net/gh/openkruise/openkruise.io@gh-pages/img/openkruise.ico" width="22" align="center" /> OpenKruise(https://github.com/openkruise/kruise)
- Containerd(https://github.com/containerd/containerd)

### Observability(Metrixs Tracing Logging)
- <img alt="OpenTelemetry" src="https://opentelemetry.io/img/logos/opentelemetry-horizontal-color.svg" width="56" align="center" /> OpenTelemetry(https://opentelemetry.io)
- Prometheus(https://prometheus.io)
- Grafana(https://grafana.com)
- Kibana(https://www.elastic.co/cn/elastic-stack)
- ElasticSearch(https://www.elastic.co/cn/elasticsearch)
  - fluentd(https://github.com/fluent/fluentd)
- <img alt="SkyWalking" src="https://skywalking.apache.org/images/logo.svg" width="56" align="center" /> SkyWalking(https://github.com/apache/skywalking)

### High Avaliable
- ChaosBlade(https://github.com/chaosblade-io/chaosblade)
- AppActive(https://github.com/alibaba/Appactive)
- 全链路压测

### Application
- Nacos(https://github.com/alibaba/nacos)
- Dubbo(https://github.com/apache/dubbo)
- Sentinel(https://github.com/alibaba/Sentinel)
- Seata(https://github.com/seata/seata)
- RocketMQ(https://github.com/apache/rocketmq)
- ShardingSphere-JDBC(https://github.com/apache/shardingsphere)

## Operating System
- OpenAnolis(https://openanolis.cn)
