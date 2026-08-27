# Awesome Kubernetes Resources with stars

A curated list of awesome Kubernetes tools and resources.

Inspired by [awesome](https://github.com/sindresorhus/awesome) ⭐ 500,501 | 🐛 105 | 📅 2026-08-21 list and [donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws) ⭐ 14,126 | 🐛 101 | 🌐 Python | 📅 2024-03-12.

## The Fiery Meter of Awesomeness

* Repo with 0050+ Stars: :fire:
* Repo with 0200+ Stars: :fire::fire:
* Repo with 0500+ Stars: :fire::fire::fire:
* Repo with 1000+ Stars: :fire::fire::fire::fire:
* Repo with 2000+ Stars: :fire::fire::fire::fire::fire:

Idea taken from [donnemartin/awesome-aws](https://github.com/donnemartin/awesome-aws) ⭐ 14,126 | 🐛 101 | 🌐 Python | 📅 2024-03-12.

## Contents

* [Tools and Libraries](#tools-and-libraries)
  * [Command Line Tools](#command-line-tools)
  * [Cluster Provisioning](#cluster-provisioning)
  * [Automation and CI/CD](#automation-and-cicd)
  * [Cluster Resources Management](#cluster-resources-management)
  * [Secrets Management](#secrets-management)
  * [Networking](#networking)
  * [Storage](#storage)
  * [Testing and Troubleshooting](#testing-and-troubleshooting)
  * [Monitoring, Alerts, and Visualization](#monitoring-alerts-and-visualization)
  * [Backup and Restore](#backup-and-restore)
  * [Security and Compliance](#security-and-compliance)
  * [Service Mesh](#service-mesh)
  * [Development Tools](#development-tools)
  * [Data Processing and Machine Learning](#data-processing-and-machine-learning)
  * [Data Management](#data-management)
  * [Miscellaneous](#miscellaneous)
* [Guides, Documentations, Blogs, and Learnings](#guides-documentations-blogs-and-learnings)
  * [Guides](#guides)
  * [Blogs and Videos](#blogs-and-videos)
  * [Learnings and Documentations](#learnings-and-documentations)
  * [Certification Guides](#certification-guides)
* [Contribute](#contribute)
* [License](#license)

## Tools and Libraries

Items with :green\_heart: indicate open source projects.

### Command Line Tools

* :green\_heart:[K9s](https://github.com/derailed/k9s) ⭐ 34,453 | 🐛 98 | 🌐 Go | 📅 2026-08-25 :fire::fire::fire::fire::fire: - K9s provides a terminal UI to interact with your Kubernetes clusters.
* :green\_heart:[Helm](https://github.com/helm/helm) ⭐ 30,178 | 🐛 455 | 🌐 Go | 📅 2026-08-25 :fire::fire::fire::fire::fire: - Helm is a tool for managing Charts. Charts are packages of pre-configured Kubernetes resources.
* :green\_heart:[kubectx + kubens](https://github.com/ahmetb/kubectx) ⭐ 19,964 | 🐛 40 | 🌐 Go | 📅 2026-08-02 :fire::fire::fire::fire::fire: - `kubectx` helps you switch between clusters back and forth, and `kubens` helps you switch between Kubernetes namespaces smoothly.
* :green\_heart:[Kubevela](https://github.com/oam-dev/kubevela) ⭐ 7,888 | 🐛 276 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - KubeVela is an easy-to-use yet extensible platform that enables them to design and ship applications with minimal effort.
* :green\_heart:[Helmfile](https://github.com/helmfile/helmfile) ⭐ 5,181 | 🐛 25 | 🌐 Go | 📅 2026-08-24 :fire::fire::fire::fire::fire: - Helmfile is a declarative spec for deploying helm charts.
* :green\_heart:[stern](https://github.com/stern/stern) ⭐ 4,849 | 🐛 41 | 🌐 Go | 📅 2026-08-19 :fire::fire::fire::fire::fire: - Stern allows you to tail multiple pods on Kubernetes and multiple containers within the pod.
* :green\_heart:[kube-ps1](https://github.com/jonmosco/kube-ps1) ⭐ 3,807 | 🐛 5 | 🌐 Shell | 📅 2026-05-24 :fire::fire::fire::fire::fire: - kube-ps1: A script that lets you add the current Kubernetes context and namespace configured on kubectl to your Bash/Zsh prompt strings (i.e. the $PS1).
* :green\_heart:[kubectl-aliases](https://github.com/ahmetb/kubectl-aliases) ⭐ 3,704 | 🐛 3 | 🌐 Nu | 📅 2025-05-11 :fire::fire::fire::fire::fire: - This repository contains a script to generate hundreds of convenient shell aliases for kubectl.
* :green\_heart:[Kubetail](https://github.com/johanhaleby/kubetail) ⭐ 3,487 | 🐛 37 | 🌐 Shell | 📅 2026-06-12 :fire::fire::fire::fire::fire: - Bash script that enables you to aggregate (tail/follow) logs from multiple pods into one stream.
* :green\_heart:[kubectl tree](https://github.com/ahmetb/kubectl-tree) ⭐ 3,419 | 🐛 16 | 🌐 Go | 📅 2026-08-24 :fire::fire::fire::fire: - A kubectl plugin to explore ownership relationships between Kubernetes objects through owners.
* :green\_heart:[kube-shell](https://github.com/cloudnativelabs/kube-shell) ⭐ 2,390 | 🐛 67 | 🌐 Python | 📅 2022-11-02 :fire::fire::fire::fire: - Kube-shell: An integrated shell for working with the Kubernetes CLI.
* :green\_heart:[Kubebox](https://github.com/astefanutti/kubebox) ⭐ 2,231 | 🐛 42 | 🌐 JavaScript | 📅 2024-06-17 :fire::fire::fire::fire: - Terminal and Web console for Kubernetes
* :green\_heart:[Plural](https://github.com/pluralsh/plural) ⭐ 1,492 | 🐛 52 | 🌐 HTML | 📅 2026-08-23 :fire::fire: - Plural is a CLI tool and holistic DevOps management platform for rapidly deploying, managing, and monitoring open-source applications on Kubernetes.
* :green\_heart:[Infra](https://github.com/infrahq/infra) ⭐ 1,467 | 🐛 33 | 🌐 Go | 📅 2026-08-10 :fire::fire::fire: - Infra enables you to discover and access infrastructure (e.g. Kubernetes, databases). We help you connect an identity provider such as Okta or Azure active directory, and map users/groups with the permissions you set to your infrastructure.
* 💚[kubecolor](https://github.com/kubecolor/kubecolor) ⭐ 1,448 | 🐛 15 | 🌐 Go | 📅 2026-08-25 🔥🔥🔥 - colorizes kubectl output
* :green\_heart:[kubediff](https://github.com/weaveworks/kubediff) ⚠️ Archived :fire::fire::fire: - Kubediff is a tool for Kubernetes to show you the differences between your running configuration and your version controlled configuration.
* :green\_heart:[kapp](https://github.com/vmware-tanzu/carvel-kapp) ⭐ 1,077 | 🐛 128 | 🌐 Go | 📅 2026-08-25 :fire::fire::fire: - kapp is a simple deployment tool focused on the concept of "Kubernetes application" — a set of resources with the same label
* :green\_heart:[Ktunnel](https://github.com/omrikiei/ktunnel) ⭐ 1,057 | 🐛 29 | 🌐 Go | 📅 2026-02-20 :fire::fire: - Ktunnel is a CLI tool that establishes a reverse tunnel between a kubernetes cluster and your local machine.
* :green\_heart:[RBAC Lookup](https://github.com/FairwindsOps/rbac-lookup) ⭐ 978 | 🐛 7 | 🌐 Go | 📅 2026-08-10 :fire::fire::fire: - RBAC Lookup is a CLI that allows you to easily find Kubernetes roles and cluster roles bound to any user, service account, or group name.
* :green\_heart:[Helmwave](https://github.com/helmwave/helmwave) ⭐ 901 | 🐛 23 | 🌐 Go | 📅 2026-08-06 :fire::fire::fire: - Helmwave is helm3-native tool for deploy your Helm Charts. It is like Docker-Compose, but for Helm.
* :green\_heart:[nova](https://github.com/FairwindsOps/nova/) ⭐ 874 | 🐛 26 | 🌐 Go | 📅 2026-08-26 :fire::fire: - Nova scans your cluster for installed Helm charts, then cross-checks them against all known Helm repositories.
* :green\_heart:[kl](https://github.com/robinovitch61/kl) ⭐ 416 | 🐛 2 | 🌐 Go | 📅 2026-04-14 :fire: - kl is an interactive terminal application for interacting with logs across many containers and clusters.
* :green\_heart:[Move2Kube](https://github.com/konveyor/move2kube) ⭐ 412 | 🐛 55 | 🌐 Go | 📅 2025-03-06 :fire::fire: - A tool to help users migrate their apps from legacy platforms like Cloud Foundry to Kubernetes and Openshift. Analyses the application source code and generates Kubernetes YAMLs, Helm Charts, Tekton Pipelines, etc. The analysis and generation can be heavily customized to produce the exact output that you want.
* :green\_heart:[kconnect](https://github.com/fidelity/kconnect) ⭐ 245 | 🐛 34 | 🌐 Go | 📅 2026-08-05 :fire::fire: - kconnect is a CLI utility that can be used to discover and securely access Kubernetes clusters across multiple operating environments.
* :green\_heart:[kubeprompt](https://github.com/jlesquembre/kubeprompt) ⭐ 83 | 🐛 0 | 🌐 Go | 📅 2021-11-10 :fire: - Isolates KUBECONFIG in each shell and shows the current Kubernetes context/namespace in your prompt

### Cluster Provisioning

* :green\_heart:[k3s](https://github.com/rancher/k3s) ⭐ 33,836 | 🐛 72 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Lightweight Kubernetes. Easy to install,Kubernetes clusters from the command line.
* :green\_heart:[Minikube](https://github.com/kubernetes/minikube) ⭐ 32,071 | 🐛 543 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire::fire::fire: - minikube implements a local Kubernetes cluster on macOS,Linux,all in a binary less than 100 MB.
* :green\_heart:[kubespray](https://github.com/kubernetes-sigs/kubespray) ⭐ 18,704 | 🐛 202 | 🌐 Jinja | 📅 2026-08-21 :fire::fire::fire::fire::fire: - Deploy a production ready Kubernetes cluster
* :green\_heart:[kops](https://github.com/kubernetes/kops) ⭐ 16,669 | 🐛 137 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - `kops` helps you create,like kind,upgrade and maintain production-grade
* :green\_heart:[kind](https://github.com/kubernetes-sigs/kind) ⭐ 15,450 | 🐛 244 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire::fire::fire: - kind is a tool for running local Kubernetes clusters using Docker container "nodes".
* :green\_heart:[vCluster](https://github.com/loft-sh/vcluster/) ⭐ 11,277 | 🐛 162 | 🌐 Go | 📅 2026-08-27 : :fire::fire::fire::fire::fire: - vCluster allows you to create fully functional virtual Kubernetes clusters, drastically reducing costs and improving multi-tenancy and isolation compared to traditional Kubernetes.
* :green\_heart:[Talos Linux](https://github.com/siderolabs/talos) ⭐ 11,033 | 🐛 224 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Talos Linux is a minimal, immutable, secure OS that installs vanilla Kubernetes - for production datacenters, K8s\@home, and Edge.
* :green\_heart:[microK8s](https://github.com/ubuntu/microk8s) ⭐ 9,359 | 🐛 166 | 🌐 Python | 📅 2026-08-27 :fire::fire::fire::fire::fire: - The smallest, fastest Kubernetes
* :green\_heart:[k3d](https://github.com/rancher/k3d) ⭐ 6,538 | 🐛 288 | 🌐 Go | 📅 2026-08-25 :fire::fire::fire::fire::fire: - k3d,and Windows.,destroy,half the memory,highly available,is a tool for running local k3s clusters in docker. It's a single binary about 20 MB. You need to have docker installed.
* :green\_heart:[k0s](https://github.com/k0sproject/k0s) ⭐ 6,454 | 🐛 206 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - k0s - Zero Friction Kubernetes (The Simple, Solid & Certified Kubernetes Distribution)
* :green\_heart:[eksctl](https://github.com/weaveworks/eksctl) ⭐ 5,213 | 🐛 91 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - `eksctl` is a simple CLI tool for creating clusters on EKS - Amazon's new managed Kubernetes service for EC2.
* :green\_heart:[Cluster API](https://github.com/kubernetes-sigs/cluster-api) ⭐ 4,289 | 🐛 220 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Cluster API is a Kubernetes sub-project focused on providing declarative APIs and tooling to simplify provisioning, upgrading, and operating multiple Kubernetes clusters.
* :green\_heart:[Bootkube](https://github.com/kubernetes-sigs/bootkube) ⚠️ Archived :fire::fire::fire::fire: - Bootkube is a tool for launching self-hosted Kubernetes clusters.
* :green\_heart:[kube-aws](https://github.com/kubernetes-incubator/kube-aws) ⚠️ Archived :fire::fire::fire::fire: - `kube-aws` is a command-line tool to create/update/destroy Kubernetes clusters on AWS.
* :green\_heart:[Claudie](https://github.com/berops/claudie) ⭐ 790 | 🐛 65 | 🌐 Go | 📅 2026-08-26 :fire: - Multi-cloud clusters with each nodepool in a different cloud provider.
* :green\_heart:[karpenter](\[https://karpenter.sh]\(https://github.com/aws/karpenter-provider-aws\)) :fire::fire::fire::fire::fire: - Karpenter is a Kubernetes Node Autoscaler built for flexibility, performance, and simplicity.
* :green\_heart:[Kubeadm](https://kubernetes.io/docs/reference/setup-tools/kubeadm/kubeadm/) - kubeadm performs the actions necessary to get a minimum viable cluster up and running.

### Automation and CI/CD

* :green\_heart:[Argo CD](https://github.com/argoproj/argo-cd) ⭐ 24,012 | 🐛 4,407 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Argo CD is a declarative, GitOps continuous delivery tool for Kubernetes.
* :green\_heart:[KubeSphere](https://github.com/kubesphere/kubesphere) ⭐ 17,028 | 🐛 353 | 🌐 Go | 📅 2026-07-15 :fire::fire::fire::fire::fire: - KubeSphere is a distributed operating system providing cloud native stack with Kubernetes as its kernel, and aims to be plug-and-play architecture for third-party applications seamless integration to boost its ecosystem.
* :green\_heart:[Argo Workflows](https://github.com/argoproj/argo) ⭐ 16,940 | 🐛 1,254 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Argo Workflows is an open source container-native workflow engine for orchestrating parallel jobs on Kubernetes.
* :green\_heart:[Skaffold](https://github.com/GoogleContainerTools/skaffold) ⭐ 15,889 | 🐛 902 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Skaffold is a command line tool that facilitates continuous development for Kubernetes applications.
* :green\_heart:[Reloader](https://github.com/stakater/Reloader) ⭐ 10,371 | 🐛 164 | 🌐 Go | 📅 2026-08-23 :fire::fire::fire::fire::fire: - Reloader can watch changes in `ConfigMap` and `Secret` and do rolling upgrades on Pods with their associated `DeploymentConfigs`, `Deployments`, `Daemonsets` and `Statefulsets`.
* :green\_heart:[Spinnaker](https://github.com/spinnaker/spinnaker) ⭐ 9,778 | 🐛 108 | 🌐 Java | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Spinnaker is an open-source continuous delivery platform for releasing software changes with high velocity and confidence.
* :green\_heart:[Flux2](https://github.com/fluxcd/flux2) ⭐ 8,373 | 🐛 254 | 🌐 Go | 📅 2026-08-25 :fire::fire::fire::fire::fire: - Flux version 2 is built from the ground up to use Kubernetes' API extension system, and to integrate with Prometheus and other core components of the Kubernetes ecosystem.
* :green\_heart:[Flagger](https://github.com/weaveworks/flagger) ⭐ 5,395 | 🐛 387 | 🌐 Go | 📅 2026-08-24 :fire::fire::fire::fire::fire: - Flagger is a progressive delivery tool that automates the release process for applications running on Kubernetes.
* :green\_heart:[werf](https://github.com/werf/werf) ⭐ 4,717 | 🐛 29 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - werf is a CLI tool glueing Git, Docker, Helm & Kubernetes with any CI system to implement CI/CD and GitOps.
* :green\_heart:[Kubero](https://github.com/kubero-dev/kubero) ⭐ 4,398 | 🐛 117 | 🌐 TypeScript | 📅 2026-08-11 :fire::fire::fire::fire::fire: - A free and self-hosted Heroku PaaS alternative for Kubernetes that implements GitOps
* :green\_heart:[Argo Rollouts](https://github.com/argoproj/argo-rollouts) ⭐ 3,561 | 🐛 658 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire: - Argo Rollouts controller, uses the Rollout custom resource to provide additional deployment strategies such as Blue Green and Canary to Kubernetes.
* :green\_heart:[Argo Events](https://github.com/argoproj/argo-events) ⭐ 2,687 | 🐛 153 | 🌐 Go | 📅 2026-08-22 :fire::fire::fire::fire: - Argo Events is an event-driven workflow automation framework for Kubernetes which helps you trigger K8s objects, Argo Workflows, Serverless workloads, etc.
* :green\_heart:[Otomi - Self-hosted PaaS for K8s](https://github.com/redkubes/otomi-core) ⭐ 2,258 | 🐛 62 | 🌐 Go Template | 📅 2026-08-27 :fire::fire::fire::fire: - Otomi adds developer- and operations-centric tools, automation, and developer self-service on top of Kubernetes in any infrastructure or cloud, to code, build, release, deploy, secure, operate and monitor containerized applications.
  :green\_heart:[Cozystack - Self-hosted PaaS for K8s](https://github.com/cozystack/cozystack) ⭐ 2,205 | 🐛 630 | 🌐 Shell | 📅 2026-08-27 :fire::fire::fire::fire: - a turnkey, self-hosted PaaS built to run on hardened Talos Linux clusters, bringing security-first Kubernetes automation to your own metal. Perfect if you're building sovereign cloud or edge-native stacks.
* :green\_heart:[TF-controller](https://github.com/weaveworks/tf-controller) ⭐ 1,686 | 🐛 154 | 🌐 Go | 📅 2026-08-24 :fire: - TF-controller is an experimental controller for Flux to reconcile Terraform resources in the GitOps way.
* :green\_heart:[Weave GitOps](https://github.com/weaveworks/weave-gitops) ⭐ 1,128 | 🐛 162 | 🌐 MDX | 📅 2026-08-27 :fire::fire: - Weave GitOps is a simple open source developer platform for people who want cloud native applications, without needing Kubernetes expertise.
* :green\_heart:[Argocd autopilot](https://github.com/argoproj-labs/argocd-autopilot) ⭐ 1,125 | 🐛 96 | 🌐 Go | 📅 2025-12-16 :fire::fire::fire: - The Argo-CD Autopilot is a tool which offers an opinionated way of installing Argo-CD and managing GitOps repositories.
* :green\_heart:[k8s-image-swapper](https://github.com/estahn/k8s-image-swapper/) ⭐ 632 | 🐛 46 | 🌐 Go | 📅 2026-08-24 :fire::fire: - `k8s-image-swapper` is a mutating webhook for Kubernetes, downloading images into your own registry and pointing the images to that new location.
* :green\_heart:[terranetes-controller](https://github.com/appvia/terranetes-controller) ⭐ 248 | 🐛 36 | 🌐 Go | 📅 2026-07-16 :fire: - Terranetes controller enables the platform team to deliver self-service capabilities around cloud resources.

### Cluster Resources Management

* :green\_heart: [Meshery](https://github.com/meshery/meshery) ⭐ 11,591 | 🐛 1,836 | 🌐 TypeScript | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Meshery is an open-source cloud-native manager that enables the design and management of all Kubernetes-based infrastructure and applications.
* :green\_heart:[KEDA](https://github.com/kedacore/keda) ⭐ 10,472 | 🐛 245 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - KEDA allows for fine grained autoscaling (including to/from zero) for event driven Kubernetes workloads.
* :green\_heart:[Kruise](https://github.com/openkruise/kruise) ⭐ 5,325 | 🐛 81 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Kruise consists of several controllers which extend and complement the Kubernetes core controllers for workload management.
* :green\_heart:[Polaris](https://github.com/FairwindsOps/polaris) ⭐ 3,384 | 🐛 21 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Polaris is an open source policy engine for Kubernetes that validates and remediates resource configuration.
* :green\_heart:[Grafana Tanka](https://github.com/grafana/tanka) ⭐ 2,682 | 🐛 61 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire: - The clean, concise and super flexible alternative to YAML for your Kubernetes cluster.
* :green\_heart:[Pluto](https://github.com/FairwindsOps/pluto) ⭐ 2,570 | 🐛 12 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire::fire: - Pluto is a utility to help users find deprecated Kubernetes apiVersions in their code repositories and their helm releases.
* :green\_heart:[Kubenav](https://github.com/kubenav/kubenav) ⭐ 2,289 | 🐛 45 | 🌐 Dart | 📅 2026-08-01 :fire::fire::fire::fire: - kubenav is the navigator for your Kubernetes clusters right in your pocket.
* :green\_heart:[Liqo](https://github.com/liqotech/liqo) ⭐ 1,479 | 🐛 109 | 🌐 Go | 📅 2026-08-25 :fire::fire: - Liqo implements Dynamic resource sharing across different Kubernetes clusters (e.g.; offloading pods and services), supporting decentralized governance.
* :green\_heart:[The Hierarchical Namespace Controller](https://github.com/kubernetes-sigs/multi-tenancy/tree/master/incubator/hnc) ⚠️ Archived :fire::fire::fire: - Hierarchical namespaces make it easier to share your cluster by making namespaces more powerful.
* :green\_heart:[Clusterpedia](https://github.com/clusterpedia-io/clusterpedia) ⭐ 883 | 🐛 61 | 🌐 Go | 📅 2026-08-26 :fire: - Clusterpedia is used for complex resource searches across multiple clusters, support simultaneous search of a single kind of resource or multiple kinds of resources existing in multiple clusters.
* :green\_heart:[Projectsveltos](https://github.com/projectsveltos/addon-manager) ⭐ 565 | 🐛 11 | 🌐 Go | 📅 2026-08-22 :fire: Projectsveltos is a Kubernetes add-on controller that simplifies the deployment and management of add-ons and applications across multiple clusters.
* :green\_heart:[KubeDirector](https://github.com/bluek8s/kubedirector) ⭐ 409 | 🐛 85 | 🌐 Go | 📅 2026-03-26 :fire::fire: - KubeDirector uses standard Kubernetes (K8s) facilities of custom resources and API extensions to implement stateful scaleout application clusters.

### Secrets Management

* :green\_heart:[Sealed Secrets](https://github.com/bitnami-labs/sealed-secrets) ⭐ 9,260 | 🐛 67 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Encrypt your Secret into a SealedSecret, which is safe to store - even to a public repository.
* :green\_heart:[Kubernetes External Secrets](https://github.com/godaddy/kubernetes-external-secrets) ⚠️ Archived :fire::fire::fire::fire::fire: - Kubernetes External Secrets allows you to use external secret management systems, like AWS Secrets Manager or HashiCorp Vault, to securely add secrets in Kubernetes.
* :green\_heart:[akv2k8s](https://github.com/SparebankenVest/azure-key-vault-to-kubernetes) ⭐ 450 | 🐛 101 | 🌐 Go | 📅 2026-08-27 :fire::fire: - Azure Key Vault to Kubernetes (akv2k8s) will make Azure Key Vault objects available to Kubernetes in two ways: as native Kubernetes Secrets; as environment variables directly injected into your Container application

### Networking

* :green\_heart:[cilium](https://github.com/cilium/cilium) ⭐ 25,017 | 🐛 1,089 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Cilium is a networking, observability, and security solution with an eBPF-based dataplane.
* :green\_heart:[ingress-nginx](https://github.com/kubernetes/ingress-nginx) ⚠️ Archived :fire::fire::fire::fire::fire: - `ingress-nginx` is an Ingress controller for Kubernetes using NGINX as a reverse proxy and load balancer.
* :green\_heart:[CoreDNS](https://github.com/coredns/coredns) ⭐ 14,280 | 🐛 293 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - CoreDNS is a fast and flexible DNS server that works on Kubernetes.
* :green\_heart:[cert-manager](https://github.com/jetstack/cert-manager) ⭐ 14,052 | 🐛 245 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - cert-manager is a Kubernetes add-on to automate the management and issuance of TLS certificates from various issuing sources.
* :green\_heart:[Calico Networking](https://github.com/projectcalico/calico) ⭐ 7,338 | 🐛 246 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Calico is an open source networking and network security solution for containers, virtual machines, and bare-metal workloads
* :green\_heart:[kubernetes-ingress](https://github.com/nginxinc/kubernetes-ingress) ⭐ 5,070 | 🐛 241 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire:  - An implementation of an Ingress controller for NGINX and NGINX Plus (commercial).
* :green\_heart:[ksniff](https://github.com/eldadru/ksniff) ⭐ 3,473 | 🐛 67 | 🌐 Go | 📅 2024-08-02 :fire::fire::fire::fire: - A kubectl plugin that utilize tcpdump and Wireshark to start a remote capture on any pod in your Kubernetes cluster.
* :green\_heart:[Kong for Kubernetes](https://github.com/Kong/kubernetes-ingress-controller) ⭐ 2,408 | 🐛 277 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire: - Configure plugins, health checking, load balancing and more in Kong for Kubernetes Services.
* :green\_heart:[kube-ovn](https://github.com/alauda/kube-ovn) ⭐ 2,394 | 🐛 66 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire:  - A Kubernetes Network Fabric for Enterprises that is Rich in Functions and Easy in Operations.
* :green\_heart:[kubectl trace](https://github.com/iovisor/kubectl-trace) ⭐ 2,186 | 🐛 49 | 🌐 Go | 📅 2026-04-16 :fire::fire::fire::fire: - `kubectl trace` is a kubectl plugin that allows you to schedule the execution of bpftrace programs in your Kubernetes cluster.
* :green\_heart:[loxilb](https://github.com/loxilb-io/loxilb) ⭐ 1,871 | 🐛 30 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire:  - A Kubernetes service load-balancer based on eBPF.
* :green\_heart:[Kube Karp](https://github.com/immanuelfodor/kube-karp) ⭐ 135 | 🐛 2 | 🌐 Shell | 📅 2022-05-14 :fire: - Add a floating virtual IP to Kubernetes cluster nodes for load balancing easily based on the CARP protocol

### Storage

* :green\_heart:[Rook](https://github.com/rook/rook) ⭐ 13,617 | 🐛 128 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Rook is an open source cloud-native storage orchestrator for Kubernetes.
* :green\_heart:[OpenEBS](https://github.com/openebs/openebs) ⭐ 9,805 | 🐛 38 | 📅 2026-08-27 :fire::fire::fire::fire::fire: - OpenEBS is the most widely deployed and easy to use open-source storage solution for Kubernetes.
* :green\_heart:[Longhorn](https://github.com/longhorn/longhorn) ⭐ 7,941 | 🐛 1,879 | 🌐 Shell | 📅 2026-08-26 :fire::fire::fire::fire::fire: - Longhorn is a distributed block storage system for Kubernetes.

### Testing and Troubleshooting

* :green\_heart:[k6](https://github.com/loadimpact/k6) ⭐ 31,335 | 🐛 796 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - k6 is a modern load testing tool, building on Load Impact's years of experience in the load and performance testing industry.
* :green\_heart:[Chaos Mesh](https://github.com/pingcap/chaos-mesh) ⭐ 7,858 | 🐛 551 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Chaos Mesh® is a cloud-native Chaos Engineering platform that orchestrates chaos on Kubernetes environments.
* :green\_heart:[Litmus](https://github.com/litmuschaos/litmus) ⭐ 5,603 | 🐛 398 | 🌐 Go | 📅 2026-08-25 :fire::fire::fire::fire::fire: - Litmus provides tools to orchestrate chaos on Kubernetes to help SREs find weaknesses in their deployments.
* :green\_heart:[ksniff](https://github.com/eldadru/ksniff) ⭐ 3,473 | 🐛 67 | 🌐 Go | 📅 2024-08-02 :fire::fire::fire::fire: - A kubectl plugin that utilize tcpdump and Wireshark to start a remote capture on any pod in your Kubernetes cluster.
* :green\_heart:[Conftest](https://github.com/open-policy-agent/conftest) ⭐ 3,252 | 🐛 51 | 🌐 Go | 📅 2026-08-25 :fire::fire::fire::fire: - Conftest helps you write tests against structured configuration data.
* :green\_heart:[kube-score](https://github.com/zegl/kube-score) ⭐ 3,101 | 🐛 51 | 🌐 Go | 📅 2026-05-20 :fire::fire::fire::fire: - `kube-score` is a tool that performs static code analysis of your Kubernetes object definitions.
* :green\_heart:[kube-monkey](https://github.com/asobti/kube-monkey) ⭐ 3,072 | 🐛 25 | 🌐 Go | 📅 2026-08-12 :fire::fire::fire::fire::fire: - It randomly deletes Kubernetes (k8s) pods in the cluster encouraging and validating the development of failure-resilient services.
* :green\_heart:[Kube DOOM](https://github.com/storax/kubedoom) ⭐ 2,166 | 🐛 4 | 🌐 C++ | 📅 2024-08-20 :fire::fire::fire::fire: - The next level of chaos engineering is here! Kill pods inside your Kubernetes cluster by shooting them in Doom!
* :green\_heart:[PowerfulSeal](https://github.com/bloomberg/powerfulseal) ⭐ 1,981 | 🐛 55 | 🌐 Python | 📅 2023-11-10 :fire::fire::fire::fire: - PowerfulSeal injects failure into your Kubernetes clusters, so that you can detect problems as early as possible.
* :green\_heart:[chaoskube](https://github.com/linki/chaoskube) ⭐ 1,934 | 🐛 34 | 🌐 Go | 📅 2026-08-01 :fire::fire::fire::fire: - `chaoskube` periodically kills random pods in your Kubernetes cluster.
* :green\_heart:[Testkube](https://github.com/kubeshop/testkube) ⭐ 1,650 | 🐛 51 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire: - Testkube is a Kubernetes native Testing Framework for test orchestration and execution. It allows you to run any of your tests inside a Kubernetes cluster. Integrates with your CI/CD and allows you to follow a GitOps approach to Testing while having a centralized place for all of your Test Results accross all clusters.
* :green\_heart:[KubeInvaders](https://github.com/lucky-sideburn/KubeInvaders) ⭐ 1,120 | 🐛 0 | 🌐 JavaScript | 📅 2026-06-23 :fire::fire::fire: - Through KubeInvaders you can stress Kubernetes cluster in a fun way and check how it is resilient.
* :green\_heart:[Chainsaw](https://github.com/kyverno/chainsaw) ⭐ 612 | 🐛 70 | 🌐 Go | 📅 2026-07-28 :fire: - The ultimate end to end testing tool for Kubernetes operators.
* :green\_heart:[Kubectl-debug](https://github.com/JamesTGrant/kubectl-debug) ⭐ 376 | 🐛 1 | 🌐 Go | 📅 2024-05-06 :fire::fire::fire::fire::fire: - `kubectl-debug` is an out-of-tree solution for troubleshooting running pods, which allows you to run a new container in running pods for debugging purpose.
* :green\_heart:[Kubetest](https://github.com/vapor-ware/kubetest) ⭐ 207 | 🐛 37 | 🌐 Python | 📅 2022-09-22 :fire: - Kubetest is a pytest plugin that makes it easier to manage a Kubernetes cluster within your integration tests.
* :green\_heart:[DETIK](https://github.com/bats-core/bats-detik) ⭐ 166 | 🐛 5 | 🌐 Shell | 📅 2025-10-14 :fire: - A library that simplifies end-to-end testing of K8s applications by using [BATS](https://github.com/bats-core/bats-core) ⭐ 6,235 | 🐛 127 | 🌐 Shell | 📅 2026-07-26 assertions and natural language queries.
* :green\_heart:[popeye](https://popeyecli.io/) :fire::fire::fire::fire::fire: - Popeye is a utility that scans live Kubernetes cluster and reports potential issues with deployed resources and configurations.

### Monitoring, Alerts, and Visualization

* :green\_heart:[Grafana](https://github.com/grafana/grafana) ⭐ 76,455 | 🐛 3,315 | 🌐 TypeScript | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored.
* :green\_heart:[Prometheus](https://github.com/prometheus/prometheus) ⭐ 65,858 | 🐛 888 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Prometheus, a Cloud Native Computing Foundation project, is a systems and service monitoring system.
* :green\_heart:[Lens](https://github.com/lensapp/lens) ⭐ 23,230 | 🐛 1,170 | 📅 2025-02-11 :fire::fire::fire::fire::fire: - Lens it's an useful, attractive, open source user interface (UI) for working with Kubernetes clusters.
* :green\_heart:[Kubernetes Dashboard](https://github.com/kubernetes/dashboard) ⚠️ Archived :fire::fire::fire::fire::fire: - Kubernetes Dashboard is a general purpose, web-based UI for Kubernetes clusters.
* :green\_heart:[Thanos](https://github.com/thanos-io/thanos) ⭐ 14,188 | 🐛 881 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire::fire::fire: - Thanos is a set of components that can be composed into a highly available metric system with unlimited storage capacity.
* :green\_heart:[Mizu](https://github.com/up9inc/mizu) ⭐ 12,060 | 🐛 149 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire: - API traffic viewer for Kubernetes enabling you to view all API communication between microservices. Think TCPDump and Wireshark re-invented for Kubernetes
* :green\_heart:[Kubernetes Metrics Server](https://github.com/kubernetes-sigs/metrics-server) ⭐ 6,709 | 🐛 47 | 🌐 Go | 📅 2026-08-24 :fire::fire::fire::fire::fire: - Metrics Server is a scalable, efficient source of container resource metrics for Kubernetes built-in autoscaling pipelines.
* :green\_heart:[Popeye](https://github.com/derailed/popeye) ⭐ 6,353 | 🐛 68 | 🌐 Go | 📅 2025-12-08 :fire::fire::fire::fire::fire: - Popeye is a utility that scans live Kubernetes cluster and reports potential issues with deployed resources and configurations.
* :green\_heart:[kube-state-metrics](https://github.com/kubernetes/kube-state-metrics) ⭐ 6,187 | 🐛 107 | 🌐 Go | 📅 2026-08-23 :fire::fire::fire::fire::fire: - kube-state-metrics is a simple service that listens to the Kubernetes API server and generates metrics about the state of the objects.
* :green\_heart:[Cortex](https://github.com/cortexproject/cortex) ⭐ 5,856 | 🐛 356 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Cortex provides horizontally scalable, highly available, multi-tenant, long term storage for Prometheus.
* :green\_heart:[Helm Dashboard](https://github.com/komodorio/helm-dashboard) ⭐ 5,747 | 🐛 19 | 🌐 TypeScript | 📅 2026-08-10 :fire::fire::fire::fire: - The missing UI for Helm. The Helm Dashboard plugin offers a UI-driven way to view installed Helm charts, see their revision history and corresponding k8s resources.
* :green\_heart:[Kiali](https://github.com/kiali/kiali) ⭐ 3,633 | 🐛 76 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Kiali works with Istio to visualise the service mesh topology.
* :green\_heart:[Goldilocks](https://github.com/FairwindsOps/goldilocks) ⭐ 3,321 | 🐛 13 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire: - Goldilocks is a utility that can help you identify a starting point for resource requests and limits.
* :green\_heart:[Goldpinger](https://github.com/bloomberg/goldpinger) ⭐ 2,735 | 🐛 36 | 🌐 JavaScript | 📅 2026-04-23 :fire::fire::fire::fire::fire: - Debugging tool for Kubernetes which tests and displays connectivity between nodes in the cluster.
* :green\_heart:[KubeDiagrams](https://github.com/philippemerle/KubeDiagrams) ⭐ 2,683 | 🐛 11 | 🌐 JavaScript | 📅 2026-08-19 :fire: - Generate Kubernetes architecture diagrams from Kubernetes manifest files, kustomization files, Helm charts, and actual cluster state.
* :green\_heart:[kube-capacity](https://github.com/robscott/kube-capacity) ⭐ 2,664 | 🐛 51 | 🌐 Go | 📅 2025-11-21 :fire::fire::fire: - This is a simple CLI that provides an overview of the resource requests, limits, and utilization in a Kubernetes cluster.
* :green\_heart:[BotKube](https://github.com/infracloudio/botkube) ⭐ 2,303 | 🐛 64 | 🌐 Go | 📅 2024-12-11 :fire::fire::fire::fire: - BotKube integration with Slack or Mattermost helps you monitor your Kubernetes cluster, debug critical deployments and gives recommendations for standard practices by running checks on the Kubernetes resources.
* :green\_heart:[Kubernetes Operational View](https://github.com/hjacobs/kube-ops-view) ⚠️ Archived :fire::fire::fire::fire: - A tool that aims to provide a common operational picture for multiple Kubernetes clusters.
* :green\_heart:[Sloop](https://github.com/salesforce/sloop) ⭐ 1,583 | 🐛 61 | 🌐 Go | 📅 2026-02-17 :fire::fire::fire: - Sloop monitors Kubernetes, recording histories of events and resource state changes and providing visualizations to aid in debugging past events.
* :green\_heart:[K8Studio](https://github.com/guiqui/k8Studio) ⭐ 923 | 🐛 41 | 📅 2025-05-05 :fire::fire::fire: - K8Studio IDE to manage and visualise Kubernetes Clusters.
* :green\_heart:[kubewatch](https://github.com/robusta-dev/kubewatch) ⭐ 792 | 🐛 29 | 🌐 Go | 📅 2026-08-24 :fire::fire::fire::fire::fire: - `kubewatch` is a Kubernetes watcher that currently publishes notification to available collaboration hubs/notification channels.
* :green\_heart:[Network mapper](https://github.com/otterize/network-mapper) ⭐ 674 | 🐛 6 | 🌐 Go | 📅 2025-06-10 :fire::fire: - Map Kubernetes in-cluster traffic and export as text, intents, or an image.
* :green\_heart:[Canary Checker](https://github.com/flanksource/canary-checker) ⭐ 342 | 🐛 128 | 🌐 Go | 📅 2026-08-27 :fire: - Canary Checker is a kubernetes-native health check platform with 30+ built-in health check types.
* :green\_heart:[k8s-image-availability-exporter](https://github.com/flant/k8s-image-availability-exporter) ⭐ 255 | 🐛 29 | 🌐 Go | 📅 2026-07-29 :fire: - Prometheus exporter that warns you proactively about images that are defined in Kubernetes objects but are not available in the container registry.
* :green\_heart:[KubeHelper](https://github.com/KubeHelper/kubehelper) ⭐ 249 | 🐛 1 | 🌐 Java | 📅 2021-02-15 :fire: - KubeHelper - simplifies many daily Kubernetes cluster tasks through a web interface.
* :green\_heart:[Kubedev](https://github.com/relferreira/kubedev) ⭐ 100 | 🐛 14 | 🌐 JavaScript | 📅 2023-05-05 :fire: - Kubedev is a powerful and beautiful user interface for managing Kubernetes clusters.
* :green\_heart:[Searchlight](https://github.com/searchlight/searchlight) ⭐ 2 | 🐛 0 | 🌐 Go | 📅 2024-05-02 :fire::fire: - Searchlight/Icinga periodically runs various checks on a Kubernetes cluster and sends notifications if detects an issue.

### Backup and Restore

* :green\_heart:[Velero](https://github.com/vmware-tanzu/velero) ⭐ 10,256 | 🐛 830 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Velero (formerly Heptio Ark) gives you tools to back up and restore your Kubernetes cluster resources and persistent volumes.
* :green\_heart:[katafygio](https://github.com/bpineau/katafygio) ⭐ 207 | 🐛 9 | 🌐 Go | 📅 2023-12-15 :fire: - katafygio discovers Kubernetes objects (deployments, services, ...), and continuously save them as yaml files in a git repository.

### Security and Compliance

* :green\_heart:[Teleport](https://github.com/gravitational/teleport) ⭐ 20,856 | 🐛 3,343 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire::fire::fire: - Teleport Unified Access Plane enables engineers to quickly access any computing resource anywhere.
* :green\_heart:[Falco](https://github.com/falcosecurity/falco) ⭐ 9,310 | 🐛 64 | 🌐 C++ | 📅 2026-08-03 :fire::fire::fire::fire::fire: - Falco is a behavioral activity monitor designed to detect anomalous activity in your applications. You can use Falco to monitor run-time security of your Kubernetes applications and internal components.
* :green\_heart:[kube-bench](https://github.com/aquasecurity/kube-bench) ⭐ 8,157 | 🐛 95 | 🌐 Go | 📅 2026-08-24 :fire::fire::fire::fire::fire: - kube-bench is a Go application that checks whether Kubernetes is deployed securely by running the checks documented in the CIS Kubernetes Benchmark.
* :green\_heart:[Kyverno](https://github.com/kyverno/kyverno) ⭐ 8,077 | 🐛 643 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire: - Kyverno is a policy engine designed for Kubernetes. It can validate, mutate, and generate configurations using admission controls and background scans.
* :green\_heart:[Datree](https://github.com/datreeio/datree) ⚠️ Archived :fire::fire::fire::fire::fire: - Datree is a CLI tool that supports Kubernetes admins in their roles by preventing developers from making errors in Kubernetes configurations that can cause clusters to fail in production.
* :green\_heart:[Deepfence ThreatMapper](https://github.com/deepfence/ThreatMapper) ⭐ 5,318 | 🐛 144 | 🌐 TypeScript | 📅 2026-06-01 :fire::fire::fire: - Apache v2, powerful runtime vulnerability scanner for kubernetes, virtual machines and serverless.
* :green\_heart:[kube-hunter](https://github.com/aquasecurity/kube-hunter) ⭐ 5,080 | 🐛 82 | 🌐 Python | 📅 2024-03-19 :fire::fire::fire::fire::fire: - kube-hunter hunts for security weaknesses in Kubernetes clusters.
* :green\_heart:[Gatekeeper](https://github.com/open-policy-agent/gatekeeper) ⭐ 4,268 | 🐛 187 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Policy controller for Kubernetes
* :green\_heart:[KubeLinter](https://github.com/stackrox/kube-linter) ⭐ 3,500 | 🐛 92 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire::fire: - KubeLinter is a static analysis tool that checks Kubernetes YAML files and Helm charts to ensure the applications represented in them adhere to best practices.
* :green\_heart:[KubiScan](https://github.com/cyberark/KubiScan) ⭐ 1,432 | 🐛 6 | 🌐 Python | 📅 2025-05-25 :fire::fire::fire: - A tool for scanning Kubernetes cluster for risky permissions in Kubernetes's Role-based access control (RBAC) authorization model.
* :green\_heart:[rakkess](https://github.com/corneliusweig/rakkess) ⭐ 1,402 | 🐛 15 | 🌐 Go | 📅 2023-04-05 :fire::fire::fire: - kubectl plugin to show an access matrix for server resources
* :green\_heart:[Permission manager](https://github.com/sighupio/permission-manager) ⭐ 1,373 | 🐛 34 | 🌐 TypeScript | 📅 2024-05-12 :fire::fire::fire: - Permission Manager is an application developed by SIGHUP that enables a super-easy and user-friendly RBAC management for Kubernetes.
* :green\_heart:[Kubesploit](https://github.com/cyberark/kubesploit) ⭐ 1,225 | 🐛 0 | 🌐 Go | 📅 2025-02-03 :fire::fire::fire: - Kubesploit is a cross-platform post-exploitation HTTP/2 Command & Control server and agent dedicated for containerized environments written in Golang and built on top of Merlin project by Russel Van Tuyl (@Ne0nd0g).
* :green\_heart:[k-rail](https://github.com/cruise-automation/k-rail) ⚠️ Archived :fire::fire: - k-rail is a workload policy enforcement tool for Kubernetes. It can help you secure a multi tenant cluster with minimal disruption and maximum velocity.
* :green\_heart:[Konstraint](https://github.com/plexsystems/konstraint) ⭐ 393 | 🐛 21 | 🌐 Go | 📅 2025-11-20 :fire::fire: - Konstraint is a CLI tool to assist with the creation and management of constraints when using Gatekeeper.
* :green\_heart:[Intents operator](https://github.com/otterize/intents-operator) ⭐ 313 | 🐛 8 | 🌐 Go | 📅 2025-06-11 :fire::fire: - Manage network policies, Istio Authorization Policies, and Kafka ACLs in a Kubernetes cluster with ease.
* :green\_heart:[Netchecks](https://github.com/hardbyte/netchecks/) ⭐ 166 | 🐛 10 | 🌐 Python | 📅 2026-08-17 :fire: - Set of tools for testing network conditions and asserting that they are as expected.
* :green\_heart:[Rönd](https://github.com/rond-authz/rond) ⭐ 161 | 🐛 35 | 🌐 Go | 📅 2026-02-11 :fire: - Rönd is an open-source lightweight Kubernetes sidecar container that helps you protect your APIs with simple security policies. It also natively allows you to build your RBAC/ABAC solution.

### Service Mesh

* :green\_heart:[Istio](https://github.com/istio/istio) ⭐ 38,362 | 🐛 512 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - An open platform to connect, manage, and secure microservices.
* :green\_heart:[Linkerd](https://github.com/linkerd/linkerd) ⭐ 5,309 | 🐛 146 | 🌐 Scala | 📅 2023-03-04 :fire::fire::fire::fire::fire: - Linkerd is a transparent service mesh, designed to make modern applications safe and sane.
* :green\_heart:[Open Service Mesh](https://github.com/openservicemesh/osm/) ⚠️ Archived :fire::fire::fire::fire::fire: - Open Service Mesh (OSM) is a lightweight, extensible, Cloud Native service mesh that allows users to uniformly manage, secure, and get out-of-the-box observability features for highly dynamic microservice environments.

### Development Tools

* :green\_heart:[Tilt](https://github.com/tilt-dev/tilt) ⭐ 10,022 | 🐛 509 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Tilt powers multi-service development and makes sure they behave.
* :green\_heart:[ko](https://github.com/google/ko) ⭐ 8,512 | 🐛 56 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire::fire::fire: - `ko` is a tool for building and deploying Golang applications to Kubernetes.
* :green\_heart:[Telepresence](https://github.com/telepresenceio/telepresence) ⭐ 7,288 | 🐛 26 | 🌐 Go | 📅 2026-08-25 :fire::fire::fire::fire::fire: - Telepresence provides fast, realistic local development for Kubernetes microservices.
* :green\_heart:[mirrord](https://github.com/metalbear-co/mirrord) ⭐ 5,279 | 🐛 70 | 🌐 Rust | 📅 2026-08-27 :fire::fire::fire::fire::fire: - mirrord connects your local process and your cloud environment, and runs local code in cloud conditions.
* :green\_heart:[Tye](https://github.com/dotnet/tye) ⚠️ Archived :fire::fire::fire::fire::fire: - Tye is a developer tool that makes developing, testing, and deploying microservices and distributed applications easier.
* :green\_heart:[garden](https://github.com/garden-io/garden) ⭐ 3,609 | 🐛 247 | 🌐 TypeScript | 📅 2026-08-24 :fire::fire::fire::fire::fire: - Garden provides production-like Kubernetes testing environments for integration tests, QA, and development.
* :green\_heart:[Okteto](https://github.com/okteto/okteto) ⭐ 3,534 | 🐛 36 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire: - `okteto` accelerates the development workflow of Kubernetes applications.
* :green\_heart:[Cyclops](https://github.com/cyclops-ui/cyclops) ⭐ 3,321 | 🐛 84 | 🌐 Go | 📅 2026-01-22 :fire::fire: - Customizable UI for Kubernetes deployments
* :green\_heart:[Makisu](https://github.com/uber/makisu) ⚠️ Archived :fire::fire::fire::fire::fire: - Makisu is a fast and flexible Docker image build tool designed for unprivileged containerized environments such as Mesos or Kubernetes.
* :green\_heart:[Monokle](https://github.com/kubeshop/monokle) ⭐ 2,140 | 🐛 409 | 🌐 TypeScript | 📅 2026-02-26 :fire::fire::fire: - Monokle helps you create, edit and validate yaml manifests, visualize and validate resource links and dependencies, connect and compare resources to your clusters, debug the output of kustomize or helm, and more!
* :green\_heart:[kubevious](https://github.com/kubevious/Kubevious) ⭐ 1,706 | 🐛 17 | 📅 2026-06-13 :fire::fire::fire::fire: - Kubevious renders all configurations relevant to the application in one place. That saves a lot of time from operators, eliminating the need for looking up settings and digging within selectors and labels.
* :green\_heart:[Eclipse JKube](https://github.com/eclipse/jkube) ⭐ 852 | 🐛 159 | 🌐 Java | 📅 2026-08-27 :fire::fire: - Tools and plugins for Java developers that help you create container images along with the required manifests to deploy your applications to Kubernetes.
* :green\_heart:[kubernix](https://github.com/saschagrunert/kubernix) ⭐ 823 | 🐛 0 | 🌐 Rust | 📅 2026-08-27 :fire::fire::fire: - This project aims to provide single dependency Kubernetes clusters for local testing, experimenting and development purposes.
* :green\_heart:[gefyra](https://github.com/gefyrahq/gefyra) ⭐ 798 | 🐛 55 | 🌐 Python | 📅 2026-08-27 :fire::fire::fire: -Gefyra blazingly-fast, rock-solid, local application development ➡️ with Kubernetes.
* :green\_heart:[kubectl-warp](https://github.com/ernoaapa/kubectl-warp) ⭐ 313 | 🐛 10 | 🌐 Go | 📅 2023-04-04 :fire::fire: - Kubernetes CLI plugin for syncing and executing local files in Pod on Kubernetes
* :green\_heart:[Konfig](https://github.com/cloud66-oss/konfig) ⭐ 81 | 🐛 3 | 🌐 Ruby | 📅 2023-12-20 :fire: - Konfig is a Kubernetes friendly Rails gem. It can load configuration and secrets from both YAML or folders with individual files and present them to your application the same way.
* [Aptakube](https://aptakube.com) - A modern, lightweight and multi-cluster desktop client for Kubernetes. Connect to multiple clusters simultaneously to view, edit and manage all your resources.

### Data Processing and Machine Learning

* :green\_heart:[Kubeflow](https://github.com/kubeflow/kubeflow) ⭐ 15,835 | 🐛 0 | 📅 2026-08-21 :fire::fire::fire::fire::fire: - Kubeflow is a Cloud Native platform for machine learning based on Google’s internal machine learning pipelines.
* :green\_heart:[Strimzi](https://github.com/strimzi/strimzi-kafka-operator) ⭐ 5,917 | 🐛 154 | 🌐 Java | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Strimzi provides a way to run an Apache Kafka cluster on Kubernetes or OpenShift in various deployment configurations.
* :green\_heart:[Volcano](https://github.com/volcano-sh/volcano) ⭐ 5,902 | 🐛 803 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire: - Volcano is a batch system built on Kubernetes.
* :green\_heart:[yunikorn](https://github.com/apache/incubator-yunikorn-core) ⭐ 1,024 | 🐛 12 | 🌐 Go | 📅 2026-08-27 :fire::fire: - a light-weight, universal resource scheduler for container orchestrator systems.
* :green\_heart:[nos](https://github.com/nebuly-ai/nos) ⭐ 685 | 🐛 26 | 🌐 Go | 📅 2024-04-21 :fire::fire: - `nos` is an open-source platform to efficiently run AI workloads on Kubernetes, increasing GPU utilization and reducing infrastructure and operational costs.

### Data Management

* :green\_heart:[Postgres Operator](https://github.com/CrunchyData/postgres-operator) ⭐ 4,443 | 🐛 167 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire::fire::fire: - PGO, the Postgres Operator from Crunchy Data, gives you a declarative Postgres solution that automatically manages your PostgreSQL clusters.
* :green\_heart:[Redis Operator](https://github.com/spotahome/redis-operator) ⚠️ Archived :fire::fire::fire: - Redis Operator creates/configures/manages redis-failovers atop Kubernetes.
* :green\_heart:[MongoDB Community Kubernetes Operator](https://github.com/mongodb/mongodb-kubernetes-operator) ⚠️ Archived :fire::fire: - This is a Kubernetes Operator which deploys MongoDB Community into Kubernetes clusters.
* :green\_heart:[Kubegres](https://github.com/reactive-tech/kubegres) ⭐ 1,350 | 🐛 80 | 🌐 Go | 📅 2025-01-04 :fire::fire::fire: - Kubegres is a Kubernetes operator allowing to deploy one or many clusters of PostgreSql pods with data replication and failover enabled out-of-the box.
* :green\_heart:[MySQL Operator for Kubernetes](https://github.com/mysql/mysql-operator) ⭐ 947 | 🐛 8 | 🌐 Python | 📅 2026-07-31 :fire: - The MYSQL Operator for Kubernetes is an Operator for Kubernetes managing MySQL InnoDB Cluster setups inside a Kubernetes Cluster.

### Miscellaneous

* :green\_heart:[Crossplane](https://github.com/crossplane/crossplane) ⭐ 11,981 | 🐛 187 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Crossplane is an open source Kubernetes add-on that extends any cluster with the ability to provision and manage cloud infrastructure, services, and applications.
* :green\_heart:[KubeEdge](https://github.com/kubeedge/kubeedge) ⭐ 7,559 | 🐛 1,281 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire::fire::fire: - KubeEdge is built upon Kubernetes and extends native containerized application orchestration and device management to hosts at the Edge.
* :green\_heart:[Agones](https://github.com/googleforgames/agones) ⭐ 6,995 | 🐛 62 | 🌐 Go | 📅 2026-08-27 :fire::fire::fire::fire::fire: - Agones is a library for hosting, running and scaling dedicated game servers on Kubernetes.
* :green\_heart:[OpenCost](https://github.com/opencost/opencost) ⭐ 6,706 | 🐛 296 | 🌐 Go | 📅 2026-08-26 :fire::fire::fire::fire::fire: - OpenCost models give teams visibility into current and historical Kubernetes spend and resource allocation.
* :green\_heart:[Devtron](https://github.com/devtron-labs/devtron) ⭐ 5,590 | 🐛 766 | 🌐 Go | 📅 2026-08-24 :fire::fire::fire::fire: - It is designed as a self-serve platform for operationalizing and maintaining applications (AppOps) on kubernetes in a developer friendly way.
* :green\_heart:[Descheduler for Kubernetes](https://github.com/kubernetes-sigs/descheduler) ⭐ 5,498 | 🐛 61 | 🌐 Go | 📅 2026-08-25 :fire::fire::fire::fire::fire: - Descheduling pods from nodes based on policies
* :green\_heart:[Kube No Trouble](https://github.com/doitintl/kube-no-trouble) ⭐ 3,682 | 🐛 33 | 🌐 Go | 📅 2025-10-16 :fire::fire::fire::fire::fire: - Easily check your clusters for use of deprecated APIs
* :green\_heart:[AWS Controllers for Kubernetes](https://github.com/aws/aws-controllers-k8s) ⭐ 2,632 | 🐛 291 | 📅 2026-08-26 :fire::fire::fire::fire: - AWS Controllers for Kubernetes (ACK) lets you define and use AWS service resources directly from Kubernetes.
* :green\_heart:[Shell-operator](https://github.com/flant/shell-operator) ⭐ 2,605 | 🐛 70 | 🌐 Go | 📅 2026-08-21 :fire::fire::fire::fire: - Shell-operator is a tool for running event-driven scripts in a Kubernetes cluster.
* :green\_heart:[Brigade](https://github.com/brigadecore/brigade/) ⭐ 2,416 | 🐛 31 | 🌐 Go | 📅 2023-03-07 :fire::fire::fire::fire::fire: - Brigade is the tool for creating pipelines for Kubernetes.
* :green\_heart:[KubePug](https://github.com/rikatz/kubepug) ⭐ 1,840 | 🐛 39 | 🌐 Go | 📅 2026-06-22 :fire::fire: - A tool to check deprecations before upgrading Kubernetes version
* :green\_heart:[AWS Node Termination Handler](https://github.com/aws/aws-node-termination-handler) ⭐ 1,762 | 🐛 12 | 🌐 Go | 📅 2026-07-21 :fire::fire::fire: - A Kubernetes Daemonset to gracefully handle EC2 instance shutdown
* :green\_heart:[K8s-Cleaner](https://github.com/gianlucam76/k8s-cleaner) ⭐ 819 | 🐛 17 | 🌐 Go | 📅 2026-08-27 :fire: - `k8s-cleaner` identifies and removes unused resources.
* :green\_heart:[K8sPurger](https://github.com/yogeshkk/K8sPurger) ⭐ 257 | 🐛 0 | 🌐 Python | 📅 2024-02-18 :fire: - `K8sPurger` Hunt Unused Resources In Kubernetes.

## Guides, Documentations, Blogs, and Learnings

### Guides

* [Kubernetes The Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way) ⭐ 49,562 | 🐛 54 | 📅 2025-04-10 :fire::fire::fire::fire::fire: - Kubernetes The Hard Way guides you through bootstrapping a highly available Kubernetes cluster with end-to-end encryption between components and RBAC authentication.
* [Kubernetes Network Policy Recipes](https://github.com/ahmetb/kubernetes-network-policy-recipes) ⭐ 6,159 | 🐛 5 | 📅 2025-02-07 :fire::fire::fire::fire::fire: - This repository contains various use cases of Kubernetes Network Policies and sample YAML files to leverage in your setup.
* [Kubernetes Working Group for Multi-Tenancy](https://github.com/kubernetes-sigs/multi-tenancy) ⚠️ Archived :fire::fire::fire: - This is a working place for multi-tenancy related proposals and prototypes.
* [Amazon EKS Node Drainer](https://github.com/aws-samples/amazon-k8s-node-drainer) ⚠️ Archived :fire: - A guide and an example to cordon and evict all evictable pods from an EC2 node being terminated.
* [A Beginner’s Guide to Kubernetes](https://medium.com/containermind/a-beginners-guide-to-kubernetes-7e8ca56420b6) - A comprehensive introduction to Kubernetes architecture
* [A Deep Dive Into Kubernetes Schema Validation](https://www.datree.io/resources/kubernetes-schema-validation) - A guide about the Kubernetes schema and how to validate it using OSS and native tools
* [A Guide to the Kubernetes Networking Model](https://sookocheff.com/post/kubernetes/understanding-kubernetes-networking-model/) - A in-depth run-through of Kubernetes networking
* [Amazon EKS Best Practices Guide for Security](https://aws.github.io/aws-eks-best-practices/) - This guide provides advice about protecting information, systems, and assets that are reliant on EKS while delivering business value through risk assessments and mitigation strategies.
* [Comparison of Kubernetes Ingress controllers](https://docs.google.com/spreadsheets/d/191WWNpjJ2za6-nbG4ZoUMXMpUK8KlCIosvQB0f-oq3k/htmlview?pru=AAABdXUHlbs*g6XkyoZXhanlhRazst77Xw) - This research compares the capabilities of 14 different Kubernetes Ingress controllers.
* [Configuring HA Kubernetes cluster on bare metal servers with kubeadm](https://medium.com/faun/configuring-ha-kubernetes-cluster-on-bare-metal-servers-with-kubeadm-1-2-1e79f0f7857b) - A guide to standing up a HA Kubernetes cluster on bare metal servers with kubeadm.
* [Introduction to Using Google Kubernetes Engine; Explain Like I’m Five!](https://medium.com/faun/google-kubernetes-engine-explain-like-im-five-1890e550c099) - Creating your first managed Kubernetes cluster on Google Kubernetes Engine using Terraform.
* [Production grade Kubernetes Monitoring using Prometheus](https://medium.com/faun/production-grade-kubernetes-monitoring-using-prometheus-78144b835b60) - A in-depth guide to deploy Prometheus monitoring solution.
* [The Illustrated Children’s Guide to Kubernetes](https://www.cncf.io/phippy/the-childrens-illustrated-guide-to-kubernetes/) - Graphical explanations of Kubernetes
* [Troubleshooting Kubernetes deployments](https://learnk8s.io/a/troubleshooting-kubernetes.pdf) - A flow chart to troubleshoot a kubernetes deployment in case of issues
* [Vertical Pod Autoscaling: The Definitive Guide](https://povilasv.me/vertical-pod-autoscaling-the-definitive-guide/) - An in-depth explanation on Kubernetes VPA: what it is, how it works, how to use it and which limitations it has.
* [Writing Your First Kubernetes Operator](https://medium.com/faun/writing-your-first-kubernetes-operator-8f3df4453234) - In this article, we’ll see how to build and deploy your first Kubernetes Operator using the Operator SDK.

### Blogs and Videos

* [Kubernetes Failure Stories](https://github.com/hjacobs/kubernetes-failure-stories) ⚠️ Archived :fire::fire::fire::fire::fire: - A compiled list of links to public failure stories related to Kubernetes.
* [10 most common mistakes using kubernetes](https://blog.pipetail.io/posts/2020-05-04-most-common-mistakes-k8s/) - Common pitfalls and how to avoid them.
* [How the Department of Defense Moved to Kubernetes and Istio](https://www.youtube.com/watch?v=YjZ4AZ7hRM0) - Focus on the sidecar security stack leveraging Envoy and sidecar containers to ensure zero trust security and baked-in multi-layer security.
* [Kubernetes at Reddit: Tales from Production](https://youtu.be/WTbIBqNcjoQ) - Hear of successes, share in the heartbreak of production explosions, and gain insight into what has and hasn't worked well for one of the world's busiest web properties.
* [Life of a Packet](https://www.youtube.com/watch?v=0Omvgd7Hg1I) - Tracing the path of network traffic in the Kubernetes system.
* [OPA Deep Dive](https://www.youtube.com/watch?v=Uj2N9S58GLU) - Deep dive on some exciting new features in the OPA project presented by the co-creators.
* [Scaling Kubernetes to 2,500 Nodes](https://openai.com/blog/scaling-kubernetes-to-2500-nodes/) + [Scaling Kubernetes to 7,500 Nodes](https://openai.com/blog/scaling-kubernetes-to-7500-nodes/) - Issues you will encounter when running high-scale Kubernetes workloads.
* [Service Mesh Comparison](https://servicemesh.es/) - An easy compensation to help choose one of the service Mesh implementations.
* [ArgoCD Best Practices](https://datree.io/resources/argocd-best-practices-you-should-know)

### Learnings and Documentations

* [Kubectl Kubernetes CheatSheet](https://github.com/dennyzhang/cheatsheet-kubernetes-A4) ⭐ 2,161 | 🐛 0 | 🌐 Shell | 📅 2024-02-25 :fire::fire::fire::fire: - A cheatsheet containing many helpful kubectl commands
* [A Beginner’s Guide to Kubernetes](https://medium.com/containermind/a-beginners-guide-to-kubernetes-7e8ca56420b6) - A comprehensive introduction to Kubernetes architecture
* [ConfigMaps in Kubernetes: how they work and what you should remember](https://blog.flant.com/configmaps-in-kubernetes-how-they-work-and-what-you-should-remember/) - Understanding the evolution to ConfigMaps, how they work and what happens when they change.
* [Configuring Redis using a ConfigMap](https://kubernetes.io/docs/tutorials/configuration/configure-redis-using-configmap/) - A walkthrough that provides a real world example of how to configure Redis using a ConfigMap
* [Example: Deploying Cassandra with a StatefulSet](https://kubernetes.io/docs/tutorials/stateful-application/cassandra/) - This tutorial shows you how to run Apache Cassandra on Kubernetes. Cassandra, a database, needs persistent storage to provide data durability.
* [Example: Deploying PHP Guestbook application with Redis](https://kubernetes.io/docs/tutorials/stateless-application/guestbook/) - This tutorial shows you how to build and deploy a simple, multi-tier web application using Kubernetes and Docker.
* [Example: Deploying WordPress and MySQL with Persistent Volumes](https://kubernetes.io/docs/tutorials/stateful-application/mysql-wordpress-persistent-volume/) - This tutorial shows you how to deploy a WordPress site and a MySQL database using Minikube.
* [Exposing an External IP Address to Access an Application in a Cluster](https://kubernetes.io/docs/tutorials/stateless-application/expose-external-ip-address/) - This guide shows how to create a Kubernetes Service object that exposes an external IP address.
* [kubectl Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/) - An official list of commonly used kubectl commands and flags.
* [Kubernetes API Reference Docs](https://kubernetes.io/docs/reference/generated/kubernetes-api/v1.18/) - A high-level overview of the basic types of resources provided by the Kubernetes API and their primary functions.
* [Learn Kubernetes Basics](https://kubernetes.io/docs/tutorials/kubernetes-basics/) - This tutorial provides a walkthrough of the basics of the Kubernetes cluster orchestration system.
* [Play with Kubernetes](https://labs.play-with-k8s.com/) - Play with Kubernetes is a playground which allows users to run K8s clusters in a matter of seconds.
* [Ready-to-use commands and tips for kubectl](https://blog.flant.com/ready-to-use-commands-and-tips-for-kubectl/) - Various kubectl tips and tricks by Flant’s engineers.
* [Running ZooKeeper, A Distributed System Coordinator](https://kubernetes.io/docs/tutorials/stateful-application/zookeeper/) - This tutorial demonstrates running Apache Zookeeper on Kubernetes using StatefulSets, PodDisruptionBudgets, and PodAntiAffinity.
* [Set Up a CI/CD Pipeline with Kubernetes](https://www.linux.com/audience/enterprise/set-cicd-pipeline-kubernetes-part-1-overview/) - A end-to-end guide to set up a CI/CD Pipeline with Kubernetes.
* [StatefulSet Basics](https://kubernetes.io/docs/tutorials/stateful-application/basic-stateful-set/) - This tutorial provides an introduction to managing applications with StatefulSets.
* [Webinar: K8s with OPA Gatekeeper](https://www.youtube.com/watch?v=v4wJE3I8BYM) - How to use OPA to control what end-users can do on the cluster and ways to ensure that clusters are in compliance with company policies.

### Certification Guides

* [The ultimate CKA "Certfified Kuberenetes Administator" resource since exam inception](https://github.com/walidshaari/Kubernetes-Certified-Administrator) ⭐ 4,415 | 🐛 2 | 🌐 Shell | 📅 2025-01-05  - An updated repo of offical resources to help you master the CKA exam as well some extra resources to consolidate your kubernetes administration knowledge.
* [CKS "Certified Kubernetes security specialist certification](https://github.com/walidshaari/Certified-Kubernetes-Security-Specialist) ⭐ 2,121 | 🐛 0 | 🌐 AGS Script | 📅 2026-03-14 :fire::fire::fire::fire: - Kubernetes security resources primarly from material allowed during the exam, and extra optional items to help you advance your container and kubernetes security journey.
* [Certified Kubernetes Security Specialist - CKSS](https://github.com/ijelliti/CKSS-Certified-Kubernetes-Security-Specialist) ⭐ 2 | 🐛 0 | 🌐 HTML | 📅 2026-08-14 :fire::fire: - This repository is a collection of resources to prepare for the Certified Kubernetes Security Specialist (CKSS) exam.
* [How to pass the Certified Kubernetes Administrator (CKA) exam on the first attempt](https://medium.com/faun/how-to-pass-certified-kubernetes-administrator-cka-exam-on-first-attempt-36c0ceb4c9e) - A guide to pass CKA exam
* [Kubernetes Exam Simulator](https://killer.sh/) - CKS/CKA/CKAD exams scenarios and environment.

## Contribute

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Tom Huang has waived all copyright and
related or neighboring rights to this work.

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-27._
