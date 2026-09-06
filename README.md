# Awesome Talos

Collection of awesome talos resource from the community

## Table of Contents

- [Examples](#examples)
- [Community Extensions](#extensions)
- [Hardware](#Hardware)
- [Libraries](#libraries)
- [Management](#management)
- [Talos-Based Projects](#talos-based-projects)
- [Tools](#tools)
- [Omni Infrastructure Providers](#omni-infra-providers)

<details open><summary><h2>Examples</h2></summary>

- [Boot to Talos](https://github.com/cozystack/boot-to-talos) Convert any live Linux distro to Talos
- [`nextboot-talos`](https://salsa.debian.org/debian/nextboot-talos) Convert installed Linux systems, such as a _VPSes_, to Talos
- [Talos contrib](https://github.com/siderolabs/contrib) Talos examples in multiple clouds with multiple infrastructure tools
- [Talos azure](https://github.com/Orzelius/talos-azure) Example configuration of running Talos on Azure with Pulumi
- [Talos on Proxmox](https://github.com/alperencelik/kubemox/tree/main/examples/talos) Example configuration of running Talos on Proxmox with Kubemox
- [Terraform Talos](https://github.com/sergelogvinov/terraform-talos/) Multi-cloud terraform examples for Talos
- [Terraform Talos Hetzner](https://github.com/miran248/terraform-talos-modules) Terraform modules for Talos on Hetzner

</details>

<details open><summary><h2>Extensions</h2></summary>

- [chaosd](https://github.com/qjoly/talos.chaosd.extension/) Extension for [Chaos Mesh](https://chaos-mesh.org/)
- [FRR](https://github.com/vitaly-zverev/frr-talos-extension) Free Range Routing for Talos including BGP
- [talosctl-oidc](https://github.com/qjoly/talosctl-oidc) Extension that provides short-lived client certificates signed by the Talos CA based on OIDC provider.

</details>

<details open><summary><h2>Hardware</h2></summary>

- [Turing Pi v2](https://github.com/ro11net/tpi2-talos) Talos on Jetson Nano cluster
> Orange Pi5 and Turing RK1 Are Officaly Supported by Talos after 1.9
- [Orange Pi 5](https://github.com/schneid-l/talos-orangepi5) Support for Orange Pi SBC 
- [Turing RK1](https://github.com/nberlee/talos) Support Turing RK1 Compute module
- [x86_64 UFS](https://github.com/amoyrtil/talos-ufs) Custom Talos Linux builds with UFS (Universal Flash Storage) driver support for x86_64 devices

</details>

<details open><summary><h2>Talos-Based Projects</h2></summary>

- [cozystack](https://github.com/aenix-io/cozystack) An open-source PaaS platform for cloud providers based on Talos Linux
- [harbor-turnkey](https://github.com/max-pfeiffer/harbor-turnkey) Harbor as a turnkey solution: running on a Kubernetes single node cluster using Talos Linux and Proxmox VE.
  Provisioning with OpenTofu. [Works nicely as pull through image cache for a bigger Talos cluster.](https://www.talos.dev/v1.11/talos-guides/configuration/pull-through-cache/#using-harbor-as-a-caching-registry)
- [kargo](https://github.com/ContainerCraft/Kargo) ContainerCraft Kubevirt PaaS Undercloud

</details>

<details open><summary><h2>Libraries</h2></summary>

- [talos-linux-api](https://github.com/stereobutter/talos-linux-api) 🐍 Python bindings for the Talos Linux gRPC API
- [SideroLabs.Omni.Api](https://github.com/panoramicdata/SideroLabs.Omni.Api) .NET gRPC library for Omni

</details>

<details open><summary><h2>Management</h2></summary>

- [cluster-template](https://github.com/onedr0p/cluster-template) Opinionated template for deployment a talos cluster
- [Hcloud Kubernetes](https://github.com/hcloud-k8s/terraform-hcloud-kubernetes) Terraform Module to Deploy a Highly Available, Production-Ready Talos Kubernetes Cluster on Hetzner Cloud
- [Kangal-Patch](https://github.com/uozalp/kangal-patch) Automates rolling upgrades of Talos Linux nodes in Kubernetes clusters, handling draining, updates, and reboots safely.
- [Kubernetes as a Service](https://github.com/kubebn/talos-proxmox-kaas) Example Terraform deployment on Proxmox
- [omni-kubeconfig](https://github.com/Jubblin/omni-kubeconfig) Standalone tool to extract kubeconfig files from either a standalone or cloud based Sidero Omni instance.
- [proxmox-talos-opentofu](https://github.com/max-pfeiffer/proxmox-talos-opentofu) A turnkey Kubernetes cluster built with Talos Linux running on a Proxmox VE hypervisor. Cilium CNI. Provisioning with OpenTofu.
- [terraform proxmox cluster](https://github.com/roeldev/iac-talos-cluster) Deploy a Talos OS-based cluster in Proxmox using Terraform, with Cilium and ArgoCD
- [terraform vsphere cluster](https://github.com/ilpozzd/terraform-talos-vsphere-cluster) Deploy a Kubernetes cluster based on Talos OS in vSphere
- [terraform vsphere vm](https://github.com/ilpozzd/terraform-talos-vsphere-vm) Deploy a Talos OS-based vSphere virtual machine in vSphere
- [Talos Hetzner Dedicated Control](https://github.com/ErikLundJensen/thdctl) CLI to create Talos based Kubernetes clusters with Hetzner dedicated servers
- [Talos Operator](https://github.com/alperencelik/talos-operator) A Kubernetes operator to manage Talos Linux clusters on Kubernetes
- [TJ's Kubernetes Service](https://github.com/zimmertr/TJs-Kubernetes-Service) Terraform template for running HA Talos cluster on Proxmox
- [turnk8s](https://github.com/infraheads/turnk8s) Deploy Talos Linux based turnkey k8s clusters in a GitOps way on Proxmox with Netris and ArgoCD
- [talos-controlplane-on-k8s](https://github.com/blackliner/talos-controlplane-on-k8s) Run a Talos controlplane inside a Kubernetes cluster
- [Talos CSR Signer](https://github.com/clastix/talos-csr-signer) gRPC Server satisfying `securityapi` signature to let Talos-based worker nodes join a kubeadm-based Kubernetes Hosted Control Plane
- [tuppr](https://github.com/home-operations/tuppr) Kubernetes controller to upgrade Talos and Kubernetes

</details>

<details open><summary><h2>Tools</h2></summary>

- [ClusterTool](https://truecharts.org/guides/clustertool/) An opinionated tool for deployment and management of Talos-Based clusters
- [Pulumi provider](https://www.pulumi.com/registry/packages/talos/) Deploy Talos with Pulumi
- [talhelper](https://github.com/budimanjojo/talhelper) A tool to help creating Talos configuration files declaratively
- [Talm](https://github.com/aenix-io/talm) A Helm-like utility for declarative configuration management of Talos Linux
- [talos-ansible-playbooks](https://github.com/mgrzybek/talos-ansible-playbooks) Ansible playbooks to manage Talos Linux deployments
- [talos-bootstrap](https://github.com/aenix-io/talos-bootstrap) An interactive Talos Linux installer
- [talos-incus](https://github.com/windsorcli/talos-incus) A simplestream server that proxies Talos images for use with Incus
- [talos-pilot](https://github.com/handfish/talos-pilot) A TUI for real-time node monitoring, log streaming, etcd health, diagnostics, and node actions
- [talswitcher](https://github.com/mirceanton/talswitcher) A simple tool to help manage multiple talosconfig files
- [TOPF](https://github.com/postfinance/topf) Manages Talos cluster lifecycle with layered patches and SOPS support

</details>

<details open><summary><h2>Omni Infra Providers</h2></summary>

- [Bare metal](https://github.com/siderolabs/omni-infra-provider-bare-metal) (Official)
- [Kubevirt](https://github.com/siderolabs/omni-infra-provider-kubevirt) (Official)
- [Libvirt](https://github.com/siderolabs/omni-infra-provider-libvirt) (Official)
- [vSphere](https://github.com/siderolabs/omni-infra-provider-vsphere) (Official)
- [Proxmox](https://github.com/siderolabs/omni-infra-provider-proxmox) (Official)
- [Oxide](https://github.com/oxidecomputer/omni-infra-provider-oxide) (Supported)
- [AWS](https://github.com/rothgar/omni-infra-provider-aws) (Community)
- [OpenStack](https://github.com/rothgar/omni-infra-provider-openstack) (Community)
- [Openmetal](https://github.com/rothgar/omni-infra-provider-openmetal) (Community)
- [OVHcloud](https://github.com/ktijssen/omni-ovhcloud-infra-provider) (Community)
- [Nutanix](https://github.com/ktijssen/omni-nutanix-infra-provider) (Community)
- [Digital Ocean](https://github.com/ktijssen/omni-digitalocean-infra-provider) (Community)
- [TrueNAS](https://github.com/bearbinary/omni-infra-provider-truenas) (Community)
- [Scaleway](https://github.com/Coler-e/omni-infra-provider-scaleway) (Community)
- [Hetzner](https://github.com/theGunner295/omni-infra-provider-hetzner) Community)

</details>
