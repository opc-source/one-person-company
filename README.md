# one-person-company
一人公司：只需要一个人就有可能运维一家公司，组合 Cloud Native 并完整设计技术架构（CNCF + Alibaba）。

- CNCF landscape(https://github.com/cncf/landscape https://landscape.cncf.io)
- Alibaba Open Source(https://github.com/Alibaba)

TODO 逐步补充，架构图.jpg、实践说明.md

## Infrastructure Components eg: 

### Cluster Cloud Ops
- <img alt="KebeVela" src="https://kubevela.net/img/logo.svg" width="24" align="center" />KebeVela(OAM https://github.com/oam-dev/kubevela)
  - Terraform(https://www.terraform.io) IaC: Infrastructure as Code
  - <img alt="Configure Unify Execute" src="https://cuelang.org/images/cue.svg" width="18" align="center" /> CUE(https://cuelang.org)
- <img alt="Open Cluster Management" src="https://open-cluster-management.io/ocm.svg" width="24" align="center" />Open Cluster Management(https://github.com/open-cluster-management-io/OCM https://open-cluster-management.io)

### Cloud
- Alibaba Cloud
- Tecent Cloud
- Private Cloud

### Cloud Native Container
- <img alt="Istio" src="https://avatars.githubusercontent.com/u/23534644?s=30" width="22" align="center" /> Istio(https://github.com/istio/istio)
- <img alt="Envoy" src="https://avatars.githubusercontent.com/u/30125649?s=30" width="22" align="center" /> Envoy(https://github.com/envoyproxy/envoy)
  - WebAssembly(https://github.com/WebAssembly/WASI)

- <img alt="Kubernetes" src="https://kubernetes.io/images/wheel.svg" width="22" align="center" /> Kubernetes(https://github.com/kubernetes/kubernetes)
  - <img alt="OpenKruise" src="https://cdn.jsdelivr.net/gh/openkruise/openkruise.io@gh-pages/img/openkruise.ico" width="22" align="center" /> OpenKruise(https://github.com/openkruise/kruise)
- Containerd(https://github.com/containerd/containerd)

### Observability(Metrixs Tracing Logging)
- <img alt="OpenTelemetry" src="https://grafana.com/static/img/menu/opentelemetry.svg" width="20" align="center" /> OpenTelemetry(https://opentelemetry.io)
- <img alt="Prometheus" src="https://grafana.com/static/img/menu/prometheus.svg" width="18" align="center" /> Prometheus(https://prometheus.io)
- <img alt="Grafana" src="https://grafana.com/static/img/menu/grafana2.svg" width="18" align="center" /> Grafana(https://grafana.com)
- <img alt="Kibana" src="https://images.contentstack.io/v3/assets/bltefdd0b53724fa2ce/blt4466841eed0bf232/5d082a5e97f2babb5af907ee/logo-kibana-32-color.svg" width="16" align="center" /> Kibana(https://www.elastic.co/cn/elastic-stack)
- <img alt="ElasticSearch" src="https://images.contentstack.io/v3/assets/bltefdd0b53724fa2ce/blt36f2da8d650732a0/5d0823c3d8ff351753cbc99f/logo-elasticsearch-32-color.svg" width="16" align="center" /> ElasticSearch(https://www.elastic.co/cn/elasticsearch)
  - fluentd(https://github.com/fluent/fluentd)
- <img alt="SkyWalking" src="https://skywalking.apache.org/images/logo.svg" width="56" align="center" /> SkyWalking(https://github.com/apache/skywalking)

### High Avaliable
- <img alt="ChaosBlade" src="https://avatars.githubusercontent.com/u/48477425?s=30" width="22" align="center" /> ChaosBlade(https://github.com/chaosblade-io/chaosblade)
- AppActive(https://github.com/alibaba/Appactive)
- 全链路压测

### Application
- 🥤 COLA(App Architecture https://github.com/alibaba/COLA)

- <img alt="Nacos" src="https://nacos.io/img/nacos_colorful.png" width="32" align="center" /> Nacos(https://github.com/alibaba/nacos)
- Dubbo(https://github.com/apache/dubbo)
- Sentinel(https://github.com/alibaba/Sentinel)
- <img alt="Seata" src="https://img.alicdn.com/tfs/TB1gqL1w4D1gK0jSZFyXXciOVXa-1497-401.png" width="28" align="center" /> Seata(https://github.com/seata/seata)
- <img alt="RocketMQ" src="https://rocketmq.apache.org/assets/images/rmq-logo.png" width="20" align="center" /> RocketMQ(https://github.com/apache/rocketmq)
- <img alt="ShardingSphere" src="https://shardingsphere.apache.org/images/background_logo.png" width="16" align="center" /> ShardingSphere-JDBC(https://github.com/apache/shardingsphere)

## Operating System
- OpenAnolis(https://openanolis.cn)
