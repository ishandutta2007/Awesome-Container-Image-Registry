# Awesome-Container-Image-Registry 📦 🐳

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Container Image Registry Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Container-Image-Registry"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Container-Image-Registry?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Container-Image-Registry/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Container-Image-Registry?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Container-Image-Registry/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Container-Image-Registry?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Container Image Registry Ecosystem

**Curated Directory of Commercial Container Registries, Open-Source OCI Registry Platforms & Supply Chain Security Tools** ⚡  
*Focused on OCI-Compliant Storage, Vulnerability Scanning, Image Signing, Multi-Architecture Support, Replication & Self-Hosted Registries* 🛡️

**Last updated: October 2026** 📅

---

### 📌 Comprehensive Guide & SEO Summary

Welcome to the ultimate curated directory of **container image registries**, **open-source OCI artifact repositories**, and **container supply chain security tools**. Whether you are architecting enterprise-grade production Kubernetes clusters with cloud-native registries (such as *Amazon ECR*, *Docker Hub*, *Google Artifact Registry*, and *JFrog Artifactory*), or deploying self-hostable open-source alternatives (like *Harbor*, *Zot*, and *Distribution*), this comprehensive guide covers category leaders, security scanners, and artifact storage solutions.

**Key Container Ecosystem Insights:**
- ⚓ **Harbor** is the **most widely deployed open-source enterprise container registry**, a **CNCF Graduated project** with **25K+ GitHub stars**, featuring **built-in vulnerability scanning, Cosign image signing, RBAC, and replication**.
- 🚀 **Zot** is the **fastest-growing OCI-native container registry**, built directly on the **OCI Distribution Spec v1.1** with **vulnerability scanning, zero database dependencies**, and minimal memory overhead.
- 🏛️ **Distribution (Docker Registry v2)** serves as the **foundational reference implementation** of the OCI Distribution Specification, underpinning Docker Hub, GitHub Container Registry (GHCR), and major cloud platforms.
- 🔐 **Supply Chain Security Integrations**: Modern container registries seamlessly integrate with security tools like **Cosign (Sigstore)** for keyless image signing and **Trivy** for CVE vulnerability scanning.

---

## 📑 Table of Contents
- [🌐 Market Size & Industry Dynamics](#-market-size--industry-dynamics)
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🌐 Market Size & Industry Dynamics

> [!NOTE]
> The global container registry market is estimated at **$1.8 Billion - $2.5 Billion**, projecting strong CAGR driven by cloud-native Kubernetes adoption and DevSecOps expansion. The market structure is **moderately fragmented**: dominated at the infrastructure tier by hyperscalers (AWS ECR, Microsoft Azure ACR, Google Artifact Registry) and developer entry points (Docker Hub, GitHub Packages), while specialized enterprise artifact platforms (JFrog Artifactory, Red Hat Quay, Cloudsmith) compete on multi-format governance and advanced software supply chain security.

---

## 🏢 SaaS & Commercial Platforms

*Sorted by Parent Company Valuation / Market Cap (Descending)* 📊

| SaaS / Commercial Platform 🏢 | Company / Owner 🏢 | Company Size (Valuation / Market Cap) 💰 | Standard Edition Starting Price 🏷️ | Free Tier / Free Trial Limits 🎁 | Description 📝 |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Azure Container Registry (ACR)](https://azure.microsoft.com/en-us/products/container-registry/)** 🔷 | Microsoft | **$3.90 Trillion** | **$0.167/day ($5.00/month)** for Basic tier | **$200 free credit** (30-day Azure Free Trial) | **Azure-native container registry** — Geo-replication in Premium tier. Content trust for image signing, ACR Tasks for automated builds, and private endpoints. |
| **[GitHub Packages](https://github.com/features/packages)** 🐙 | Microsoft / GitHub | **$3.90 Trillion** | **$0.0025/GB/month** storage, **$0.01/GB** transfer beyond free limit | **500 MB storage & 1 GB data transfer/month** (Free forever) | **GitHub-native package registry** — Supports OCI container images, npm, Maven, NuGet, and RubyGems. Fully integrated with GitHub Actions CI/CD workflows. |
| **[Amazon Elastic Container Registry (ECR)](https://aws.amazon.com/ecr/)** ☁️ | Amazon | **$2.00 Trillion** | **$0.10/GB/month** storage, **$0.09/GB** data transfer out | **500 MB/month** storage (AWS Free Tier forever) | **AWS-native container registry** — Private & public repositories. Vulnerability scanning with Inspector, cross-region replication, and pull-through cache for Docker Hub. |
| **[Google Artifact Registry](https://cloud.google.com/artifact-registry)** 🌐 | Google (Alphabet) | **$2.00 Trillion** | **$0.10/GB/month** storage | **0.5 GB/month** storage (GCP Free Tier forever) | **GCP-native artifact registry** — Manages container images, OS packages, and language dependencies with built-in Container Analysis vulnerability scanning. |
| **[Harbor Cloud Enterprise](https://goharbor.io/)** ⚓ | VMware (Broadcom) | **$60 Billion** | **$150/node/month** (VMware Tanzu Platform) | **30-day free evaluation** (Commercial edition) | **Enterprise Harbor distribution** — Commercial support and management platform built on the CNCF Graduated open-source Harbor registry. |
| **[Quay.io / Red Hat Quay](https://quay.io/)** 🔴 | Red Hat (IBM) | **$50 Billion** | **$15/month** (Basic plan) | **Unlimited public repositories** (Free forever) | **Enterprise container registry** — Built-in Clair vulnerability scanning, image signing, geo-replication, and RBAC access control. Default registry for OpenShift. |
| **[GitLab Container Registry](https://docs.gitlab.com/ee/user/packages/container_registry/)** 🦊 | GitLab | **$8 Billion** | **$29/user/month** (GitLab Premium plan) | **5 GB storage & 10 GB transfer/month** (Free tier forever) | **GitLab-native container registry** — Tightly integrated with GitLab CI/CD pipelines, container scanning, and image cleanup retention policies. |
| **[JFrog Artifactory](https://jfrog.com/artifactory/)** 🐸 | JFrog | **$5 Billion** | **$98/month** (Cloud Pro plan) | **14-day free trial** (Includes 20 GB storage & 50 GB transfer) | **Universal artifact repository** — Enterprise-grade container & package registry with Xray security scanning, high availability, and multi-region replication. |
| **[Cloudsmith](https://cloudsmith.com/)** 📦 | Cloudsmith | **$200 Million** (Private) | **$49/month** (Team plan) | **14-day free trial** (Full Pro features) | **Cloud-native artifact management** — Supports container images, Helm charts, and language packages with entitlement tokens and automated SBOM generation. |
| **[Docker Hub](https://hub.docker.com/)** 🐳 | Docker Inc. | **$2.1 Billion** (Private) | **$9/month** (Personal Pro plan) | **1 private repository & unlimited public repos** (Free tier) | **The primary public container registry** — Hosts 15M+ container images. Default registry for Docker CLI and Kubernetes (rate limited to 200 pulls/6h for anonymous). |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub Stars Count (Descending)* 🌟

- **[Trivy](https://github.com/aquasecurity/trivy)** [![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social&color=white)](https://github.com/aquasecurity/trivy/stargazers)  
  **Comprehensive container security & vulnerability scanner**, Apache-2.0 licensed. **The standard scanner** powering Harbor, Zot, and CI/CD pipelines. Scans OS packages, language dependencies, IaC misconfigurations, and secrets. 🐟

- **[Harbor](https://github.com/goharbor/harbor)** [![Stars](https://img.shields.io/github/stars/goharbor/harbor?style=social&color=white)](https://github.com/goharbor/harbor/stargazers)  
  **Enterprise-grade open-source container registry**, Apache-2.0 licensed. **CNCF Graduated project**. Features vulnerability scanning (Trivy), image signing (Cosign/Notary), RBAC, replication across registries, web UI, and Helm deployment. ⚓

- **[Distribution (Docker Registry v2)](https://github.com/distribution/distribution)** [![Stars](https://img.shields.io/github/stars/distribution/distribution?style=social&color=white)](https://github.com/distribution/distribution/stargazers)  
  **Reference implementation of the OCI Distribution Spec**, Apache-2.0 licensed. **CNCF Graduated project**. The underlying core powering Docker Hub, GHCR, and cloud registries. Features pluggable storage drivers (S3, GCS, Azure Blob). 🏛️

- **[Dragonfly](https://github.com/dragonflyoss/dragonfly)** [![Stars](https://img.shields.io/github/stars/dragonflyoss/dragonfly?style=social&color=white)](https://github.com/dragonflyoss/dragonfly/stargazers)  
  **P2P-based image and file distribution system**, Apache-2.0 licensed. **CNCF Incubating project**. Reduces container image pull latency and registry bandwidth consumption by up to 90% in large Kubernetes clusters. 🐉

- **[Skopeo](https://github.com/containers/skopeo)** [![Stars](https://img.shields.io/github/stars/containers/skopeo?style=social&color=white)](https://github.com/containers/skopeo/stargazers)  
  **Command-line utility for remote container image operations**, Apache-2.0 licensed. Inspect, copy, and sync images between OCI registries without requiring a local Docker daemon. 🛠️

- **[Cosign (Sigstore)](https://github.com/sigstore/cosign)** [![Stars](https://img.shields.io/github/stars/sigstore/cosign?style=social&color=white)](https://github.com/sigstore/cosign/stargazers)  
  **Container image signing and supply chain verification**, Apache-2.0 licensed. Keyless signing using OIDC, artifact attestations, and Kubernetes admission controller policy enforcement. 🔐

- **[Crane (go-containerregistry)](https://github.com/google/go-containerregistry)** [![Stars](https://img.shields.io/github/stars/google/go-containerregistry?style=social&color=white)](https://github.com/google/go-containerregistry/stargazers)  
  **Go library and CLI tool for interacting with container registries**, Apache-2.0 licensed. Fast image layer manipulation, pulling, pushing, and manifest inspection. 🏗️

- **[Zot](https://github.com/project-zot/zot)** [![Stars](https://img.shields.io/github/stars/project-zot/zot?style=social&color=white)](https://github.com/project-zot/zot/stargazers)  
  **Production-grade OCI-native container image registry**, Apache-2.0 licensed. Built on OCI Distribution Spec v1.1. Zero database dependency, integrated CVE scanning, Cosign verification, and low memory consumption. 🚀

- **[Spegel](https://github.com/spegel-org/spegel)** [![Stars](https://img.shields.io/github/stars/spegel-org/spegel?style=social&color=white)](https://github.com/spegel-org/spegel/stargazers)  
  **Stateless P2P OCI image registry for Kubernetes**, Apache-2.0 licensed. Enables nodes in a cluster to share cached container images directly via peer-to-peer distribution. 🪞

- **[Kraken](https://github.com/uber/kraken)** [![Stars](https://img.shields.io/github/stars/uber/kraken?style=social&color=white)](https://github.com/uber/kraken/stargazers)  
  **P2P container registry for large-scale deployments**, Apache-2.0 licensed. Developed by Uber for distributing gigabytes of container images to thousands of hosts in seconds. 🐙

- **[Portus](https://github.com/SUSE/Portus)** [![Stars](https://img.shields.io/github/stars/SUSE/Portus?style=social&color=white)](https://github.com/SUSE/Portus/stargazers)  
  **Authorization service and frontend for Docker Registry (v2)**, Apache-2.0 licensed. Provides user management, fine-grained access control, team collaboration, and audit logs. 🚪

- **[Keel](https://github.com/keel-hq/keel)** [![Stars](https://img.shields.io/github/stars/keel-hq/keel?style=social&color=white)](https://github.com/keel-hq/keel/stargazers)  
  **Automated Kubernetes deployment updates on registry image pushes**, Apache-2.0 licensed. Monitors container registries for tag updates and triggers automated rolling updates. ⛵

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new container registries or open-source registry software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Container-Image-Registry&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Container-Image-Registry&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

Thank you so much for using and contributing to **Awesome Container Image Registry**! Your support keeps this project active, up-to-date, and growing.

If you find this repository useful, please consider supporting the project:
- ⭐ **Star** this repository on GitHub to increase visibility!
- 🔀 **Fork** and share it with fellow DevOps engineers, platform teams, and open-source advocates.
- ☕ **Buy Me a Coffee / Sponsor**: Support ongoing open-source curation and development via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Harbor is the most widely deployed open-source registry** — **25K+ GitHub stars**, **CNCF Graduated**, with **vulnerability scanning, signing, and replication** built in. **Zot is the fastest-growing OCI-native registry** with **no database dependency**.
- **Docker Hub rate limits**: **200 pulls/6 hours anonymous**, **5,000 pulls/6 hours authenticated**. **Paid plans from $9/month**.
- **Amazon ECR charges $0.10/GB/month** for storage and **$0.09/GB** for data transfer out. **Google Artifact Registry charges $0.10/GB/month**. **Azure ACR Basic is $5/month**.
- **Open-source registries (Harbor, Zot, Distribution) are not turnkey** — they require **deployment, storage configuration, and ongoing maintenance**. **Always validate registry performance and security with a proof-of-concept** before production deployment. 📦

---

<p align="center">
  <b>Made with ❤️ for DevOps engineers, platform teams, and open-source container registry advocates.</b>
</p>
