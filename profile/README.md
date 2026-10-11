<div align="center">

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="./assets/weaverai-logo-negative.svg">
  <source media="(prefers-color-scheme: light)" srcset="./assets/weaverai-logo-official.svg">
  <img src="./assets/weaverai-logo-official.svg" alt="WeaverAI" width="360">
</picture>

### Run your own token factory

Sovereign AI infrastructure software — from bare metal to working agents,
on hardware you own, under governance you set.

[Website](https://weaverai.org) · [Platform](https://weaverai.org/platform) · [Governance](https://weaverai.org/governance) · [Contact](https://weaverai.org/contact)

</div>

---

## The platform

WeaverAI is one stack in four layers. Each layer runs on its own; together they share one
identity, one policy model, one audit trail, one data plane and one observability plane.
Adopt one product or all four, and grow into the rest without re-platforming.

| Layer | Product | Manages | Turns |
| :---: | --- | --- | --- |
| 04 | **Agent Studio** | Agents | models into agents that do the work |
| 03 | **Studio** | Models | work into models you can trust |
| 02 | **Orbit** | Workloads | capacity into work |
| 01 | **Nucleus** | Machines | hardware into capacity |

**Fleet** complements the stack at the edge, releasing software across fleets of edge
Kubernetes clusters under the same governance model.

## Products

### Nucleus — Mission Control for modern infrastructure

The infrastructure control plane above physical hardware and Kubernetes. Nucleus discovers,
inventories and provisions bare metal, builds clusters from approved blueprints or adopts
existing ones in place, and operates them as a single estate. Teams receive **Capsules** —
isolated clusters on shared machines with multi-dimensional quota across CPU, memory, GPU
(whole, MIG or fractional), storage and network. Vendor-neutral through a provider framework
spanning Redfish, IPMI, Metal3, MAAS, Ironic, RKE2, K3s, Rancher, Cluster API, HAMi, the
NVIDIA GPU Operator and KubeVirt.

### Orbit — Where capacity becomes work

The workload platform on top of Nucleus-managed capacity. Orbit runs a single logical queue
across clusters with fair shares, priority classes, gang scheduling and topology-aware
placement, packing fractional and partitioned workloads into the gaps. Teams get isolated
workspaces, notebooks and cloud IDEs backed by fractions of an accelerator, with idle
detection, checkpoint-aware suspend and resume, and tiered data placement — keeping
expensive hardware producing instead of idle.

### Studio — Where models are made, proven and served

A Kubernetes-native LLMOps and ModelOps platform covering the full model lifecycle: model
discovery and import, data preparation, fine-tuning and training, experiment comparison,
evaluation, prompt engineering, approval, serving through a governed LLM gateway, and
production monitoring. Studio keeps an unbroken record from dataset to deployed version,
runs training and serving inside your own clusters, and supports on-premises and
air-gapped deployment. Runs standalone or integrated with Nucleus and Orbit.

### Agent Studio — Where agents go to work

The agent control plane. An agent is defined once as a specification; its runtime, sandbox
and target are chosen at deploy time. Agent Studio deploys to Kubernetes (GPU or CPU) and
container hosts — from accelerator clusters to a workstation under a desk — with pluggable
runtimes including NVIDIA NeMo Agent Toolkit, NemoClaw, LangGraph and custom images. It adds
durable multi-step workflows with human approval, chat with live tool-call traces,
per-agent token and cost accounting, hierarchical controls, quotas and a hash-chained
audit trail.

### Fleet — Release control for edge Kubernetes

A release control plane for fleets of edge clusters. Products are described once as
components (Helm or YAML) with layered configuration — project, component, release,
cluster — rendered to a signed artifact and delivered by an outbound-only, mTLS-enrolled
edge operator. Releases are immediate, scheduled or approval-gated, preserve local changes
on reconcile, and roll back exactly at cluster or release scope. Supports air-gapped sites
and any conformant Kubernetes distribution.

## Principles

- **Sovereign by design** — runs entirely inside your network and jurisdiction, including air-gapped environments.
- **Governed end to end** — multi-tenancy, MFA and SSO, scoped access control, quotas and tamper-evident audit across every layer.
- **Vendor-neutral** — silicon-agnostic and provider-pluggable; integrates the tools you already run rather than replacing them.
- **Composable** — every product stands alone and integrates through well-defined provider interfaces.

## Delivery

| Model | Description |
| --- | --- |
| **WeaverAI Cloud** | Fully managed, multi-tenant sovereign AI cloud, consumed as a metered service. |
| **Dedicated Token Factory** | A ring-fenced zone designed, built and operated for a single institution. |
| **Token Factory Suite** | The platform licensed and supported on your own hardware, with optional managed operations. |

---

<div align="center">
<sub>WeaverAI is built by NPCI Tech Solutions · <a href="https://weaverai.org">weaverai.org</a></sub>
</div>
