# KubeNexus

**Scheduling and control plane system focused on GPU placement, fragmentation, and topology-aware workload orchestration across heterogeneous fleets.**

- Multi-tenant, intent-driven GPU scheduling for Kubernetes
- Prevents GPU fragmentation and preserves topology for large jobs
- Integrates with Kueue for admission and quota management
- Supports NUMA, network fabric, and workload-aware placement

## Key Projects

- [kubenexus-scheduler](https://github.com/kube-nexus/kubenexus-scheduler): Topology- and fragmentation-aware scheduler for multi-tenant GPU fleets.
- [kubenexus-control-plane](https://github.com/kube-nexus/kubenexus-control-plane): Workload intent API, placement planning, and explainability for GPU-accelerated Kubernetes clusters.

See our repositories for schedulers, control plane, and deployment tools.

Apache 2.0 License.
