# Hi, I'm Aravindhan L 👋

Software Engineer at Zoho Corporation, working on container infrastructure,
distributed systems, and backend platforms.

I build the systems that other engineers depend on — registries, runtimes,
network plugins, storage drivers. Most of my work lives at the level of
Linux bridges, veth pairs, iptables, cgroups, and OverlayFS rather than
frameworks.

## What I work on at Zoho

- **OCI/Docker Registry** — in-house registry in Java serving multiple
  engineering teams, replacing external registry services with air-gapped
  image distribution, zero-downtime deletion, and signed download URLs
- **Docker Volume Plugin** — XFS-backed storage with per-container quota
  enforcement and cgroup blkio throttling
- **Docker Network Plugin** — CNM remote driver with per-container bandwidth
  limits via Linux TC qdiscs and iptables
- **OCI Artifact Tooling** — Go CLI (Cobra + gRPC) for building and pushing
  OCI-compliant artifacts to distributed registry backends
- **Image Scanning Pipeline** — Syft + Grype images in
  under 2 minutes

## Personal Projects

| Project | What it is |
|---|---|
| [DockerIPAMPlugin](https://github.com/aravindhan-24/DockerIPAMPlugin) | Custom Docker IPAM driver in Go — full control over subnet and IP allocation, IPv4 + IPv6, atomic state persistence |
| [DockerNetworkPlugin](https://github.com/aravindhan-24/DockerNetworkPlugin) | Docker libnetwork remote driver — bridge networking, veth pairs, NAT, per-container bandwidth limits |
| [DockerVolumePlugin](https://github.com/aravindhan-24/DockerVolumePlugin) | Docker volume driver — XFS project quotas, blkio throttling, full plugin API |
| [Registry](https://github.com/aravindhan-24/Registry) | Private package manager in Go, currently NPM — designed to extend to Docker, Maven, PyPI |
| [Containers](https://github.com/aravindhan-24/Containers) | Building, securing, and packaging containers from scratch using Linux primitives |

## Writing

I write about container internals and Linux systems on Medium.
Recent articles:

- [Building Containers from Scratch with Linux](https://medium.com/@aravindhan24/building-containers-from-scratch-with-linux-712c4679c386)
- [From Registry to Running Container](https://medium.com/@aravindhan24/from-registry-to-running-container-f5a5d3ae45bb)
- [How Docker Networking Actually Works: CNM and Remote Drivers](https://medium.com/@aravindhan24/how-docker-networking-actually-works-a-deep-dive-into-cnm-and-remote-drivers-b6d07716173f)
- [A Deep Dive into Docker Custom Volume Driver Plugins](https://medium.com/@aravindhan24/a-deep-dive-into-docker-custom-volume-driver-plugins-9c0dedb09b00)
- [IPAM Driver: Delegating IP Address Management Away from Docker](https://medium.com/@aravindhan24/ipam-driver-delegating-ip-address-management-away-from-docker-919881fa485d)
- [Securing Linux Containers](https://medium.com/@aravindhan24/securing-linux-containers-052ccc69be2a)
- [Persisting and Packaging a Container for Distribution](https://medium.com/@aravindhan24/persisting-and-packaging-a-container-for-distribution-a66c660367de)

## Stack

**Languages:** Java · Go · SQL

**Container & Systems:** Docker · OCI · Linux Networking · iptables ·
Network Namespaces · Cgroups · XFS · OverlayFS · TC · systemd

**Backend:** gRPC · REST · OAuth 2.0 · Spring Boot · Redis · PostgreSQL · MySQL

**Infrastructure:** Nginx · AWS (EC2, S3) · Prometheus · Grafana

## Connect

- 💼 [LinkedIn](https://www.linkedin.com/in/laravindhan24/)
- ✍️ [Medium](https://medium.com/@aravindhan24)
- 📫 aravindhanlakshmanan24@gmail.com
