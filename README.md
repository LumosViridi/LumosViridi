# Welcome to my GitHub Profile

- 🔭 I’m currently working on implementing Hashicorp Vault on my Raspberry Pi cluster!
- 🌱 I’m currently learning Go and will be adding some fun projects in here soon!
- 🆕 Most of what I work on is in a private GitHub org and will be moving things here as I have time. If you are curious about something that you see here just ask!

## Current Home Lab

- 4 Rasperry Pis running k3s
- Synology NAS
- Ubiquiti Unifi Dream Machine Router
  - VLANs running for IoT Devices, Gaming, and Servers

## Terraform

I love Terraform and use it in a lot of different places

- **My Website**
  - I use terraform to manage all configuration and website files. This allows me to keep my website up to date easily.
- **Kubernetes**
  - After years of typing "kubectl create" and "kubectl delete" I decided to manage all my K3s deployments with Terraform. I love how much easier it is to read and it removes a lot of room for human error.
- **Minecraft on AWS Fargate**
  - When I came up with the idea to create a Minecraft world and host it on AWS Fargate I found a great project by [doctorray117](https://github.com/doctorray117/minecraft-ondemand). Once I had played around in the console and learned more about Fargate, I decided to manage it with Terraform. Since then I have turned it into a module so I can easily create new worlds and I now have a repeatable template I can use if I decide to spin this up again in the future.

## Current Projects

### Infrastructure and Monitoring

- PiHole
- [Uptime Kuma](https://github.com/LumosViridi/k3s-playground/tree/main/apps/uptime-kuma)
- [mySQL](https://github.com/LumosViridi/k3s-playground/tree/main/apps/mysql-server)
- [Kubernetes Dashboard](https://github.com/LumosViridi/k3s-playground/tree/main/apps/kubernetes-dashboard)
- [MetalLB](https://github.com/LumosViridi/k3s-playground/tree/main/cluster/metallb)
- [CSI Driver for NFS](https://github.com/LumosViridi/k3s-playground/tree/main/cluster/nfs-csi-driver)
- [CSI Driver for SMB](https://github.com/LumosViridi/k3s-playground/tree/main/cluster/smb-csi-driver)

### Fun Stuff

- [Jellyfin Media Server](https://github.com/LumosViridi/k3s-playground/tree/main/apps/jellyfin)
- Minecraft Server - AWS Fargate Version - I ended up tearing this down to save on cost and now run on my pi cluster
- [Minecraft Server](https://github.com/LumosViridi/k3s-playground/tree/main/apps/minecraft) - Raspberry Pi Version
- [My Website](http://ciarahatcher.com) - This is currently a basic HTML/CSS site hosted on AWS but will be upgraded soon to a more modern version using React
  - AWS S3
  - AWS CloudFront
  - AWS Route53

## Future Projects

- Update Website to React
- Create an app to track progress for Stardew Valley
- URL Shortener
- Hashicorp Vault Cluster

<!--
**LumosViridi/LumosViridi** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
