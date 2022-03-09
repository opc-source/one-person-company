# One Person Company
一人公司：一个人就有可能运维一家公司，组合 Cloud Native 并完整设计技术架构（CNCF + Alibaba）；抓大放小、自顶而下、面向终态。

- CNCF landscape(https://github.com/cncf/landscape https://landscape.cncf.io)
- Alibaba Open Source(https://github.com/Alibaba)

或能提供一个踏上开源社区、持续学习的方向。TODO 逐步补充：架构图.jpg、实践说明.md

## Infrastructure Components eg: 

### Cluster Cloud Ops
- <img alt="KebeVela" src="https://kubevela.net/img/logo.svg" width="24" align="center" />KebeVela(OAM https://github.com/oam-dev/kubevela)
  - Terraform(https://www.terraform.io) IaC: Infrastructure as Code
- <img alt="Open Cluster Management" src="https://open-cluster-management.io/ocm.svg" width="24" align="center" />Open Cluster Management(https://github.com/open-cluster-management-io/OCM https://open-cluster-management.io)

### Cloud Deliver
- Sealer(https://github.com/alibaba/sealer)

### Cloud
- <img alt="Aliyun" src="https://img.alicdn.com/tfs/TB13DzOjXP7gK0jSZFjXXc5aXXa-212-48.png" width="52" /> Alibaba Cloud
- <img alt="Tecent Cloud" src="https://cloudcache.tencentcs.com/qcloud/portal/kit/images/slice/logo.23996906.svg" width="52" /> Tecent Cloud
- <img alt="Huawei Cloud" src="https://res.hc-cdn.com/cnpm-header-and-footer/2.0.6/base/header-china/components/images/logo.svg" width="52" align="center"/> Huawei Cloud
- Private Cloud

### Cloud Native Container
- <img alt="Istio" src="https://avatars.githubusercontent.com/u/23534644?s=30&v=4" width="22" align="center" /> Istio(https://github.com/istio/istio)
- <img alt="Envoy" src="https://avatars.githubusercontent.com/u/30125649?s=30&v=4" width="22" align="center" /> Envoy(https://github.com/envoyproxy/envoy)
  - <img alt="WebAssembly" src="https://avatars.githubusercontent.com/u/11578470?s=30&v=4" width="22" align="center" /> WebAssembly(https://github.com/WebAssembly/WASI)
- <img alt="Dapr" src="https://dapr.io/images/dapr.svg" width="22" align="center" /> Dapr(https://dapr.io)

- <img alt="Kubernetes" src="https://kubernetes.io/images/wheel.svg" width="22" align="center" /> Kubernetes(https://github.com/kubernetes/kubernetes)
  - <img alt="OpenKruise" src="https://cdn.jsdelivr.net/gh/openkruise/openkruise.io@gh-pages/img/openkruise.ico" width="22" align="center" /> OpenKruise(https://github.com/openkruise/kruise)
  - <img alt="etcd" src="https://etcd.io/etcd-horizontal-white.png" width="44" align="center" /> etcd(https://etcd.io)
- Containerd(https://github.com/containerd/containerd)

### Observability(Metrics Tracing Logging)
- <img alt="OpenTelemetry" src="https://grafana.com/static/img/menu/opentelemetry.svg" width="20" align="center" /> OpenTelemetry(https://opentelemetry.io)
- <img alt="Prometheus" src="https://grafana.com/static/img/menu/prometheus.svg" width="18" align="center" /> Prometheus(https://prometheus.io)
- <img alt="Grafana" src="https://grafana.com/static/img/menu/grafana2.svg" width="18" align="center" /> Grafana(https://grafana.com)
- <img alt="Kibana" src="https://images.contentstack.io/v3/assets/bltefdd0b53724fa2ce/blt4466841eed0bf232/5d082a5e97f2babb5af907ee/logo-kibana-32-color.svg" width="16" align="center" /> Kibana(https://www.elastic.co/cn/elastic-stack)
- <img alt="ElasticSearch" src="https://images.contentstack.io/v3/assets/bltefdd0b53724fa2ce/blt36f2da8d650732a0/5d0823c3d8ff351753cbc99f/logo-elasticsearch-32-color.svg" width="16" align="center" /> ElasticSearch(https://www.elastic.co/cn/elasticsearch)
  - fluentd(https://github.com/fluent/fluentd)
- <img alt="SkyWalking" src="https://skywalking.apache.org/images/logo.svg" width="56" align="center" /> SkyWalking(https://github.com/apache/skywalking)

### High Avaliable
- <img alt="ChaosBlade" src="https://chaosblade.io/zh/img/cb-head.png" width="28" align="center" /> ChaosBlade(https://github.com/chaosblade-io/chaosblade)
- Takin(https://github.com/shulieTech/Takin) Performance test for full-links.
- <img alt="AppActive" src="https://appactive.oss-cn-beijing.aliyuncs.com/images/appactive-logo.jpg?x-oss-process=style/h400" width="22" align="center" /> AppActive(https://github.com/alibaba/Appactive)

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


## Infrastructure Components Picture

部分组件并不能很好展现在架构图中，例如上述的 Observability 云原生可观测性至关重要而无处不在。

面向终态同时包含着当下的最佳实践，例如尚未成熟的产品 dapr，分布式应用运行时可以把应用之外的大多中间件都囊括（例 RocketMQ）；但当下的 Mesh 实践依旧不够成熟，所以还是描述出独立的依赖较为直观；故大致上数据代理逐步向 envoy 演进，MiddlewareMesh 向 dapr 演进。

自顶而下地描述：
- 多云(集群)的发布部署由 KubeVela 负责，仅 CD 不详述 CI；
- OCM 联通多云的 Kubernetes 集群，无论是阿里云、华为云、腾讯云、私有云等，被管理端的 Klusterlet 主动链接中控 OCM Hub，后可以双工通讯。
- 云(集群)交付由 Sealer 集群镜像技术支持，第一样例是[阿里云 ACK Distro 发行版](https://github.com/AliyunContainerService/ackdistro)；
- 每个 Kubernetes 集群都增强，OpenKruise, Istio 等 CRD+Operator。
- 集群/容器高可用： ChaosBlade 混沌工程持续的真实演练
- 应用高可用：AppActive 单元化容灾能力 + 全量路压测-生产性能测试/功能测试。
- Application 部分还能更详尽地细化，应用的代码结构仅以 COLA 为 Java 例子说明。
- gRPC 来实现所有跨语言的调用，语言中立、平台无关。

:v0.1.0
<img alt="Infrastructure Components Pic" src="arch/one-person-company-infrastructure-v0.1.0_x96.jpg"/>
