Welcome to my homelab.

Overview:
I had an old pc lying around and decided to put it to good use.
It is running Oracle Linux 9.6. On top, I installed K3s from Rancher and I manage all the deployments remotely via ArgoCD.

Hardware:
CPU: i7 4790S
RAM: 8GB DDR3
STORAGE: 256GB SSD + 512GB HDD

Deployments:

/Network
MetalLB: LoadBalancer solution to expose kubernetes services via individual IPs in my LAN
Pihole: Configured to run as a local DNS + Ad blocker with upstream DNS pointing to Google.

/Storage
NextCloud: Shared storage solution for my LAN, backed by postgreSQL
