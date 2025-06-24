Welcome to my homelab!<br>
<br>
Overview:<br>
I had an old pc lying around and decided to put it to good use.<br>
It is running Oracle Linux 9.6. On top, I installed K3s from Rancher and I manage all the deployments remotely via ArgoCD.<br>
<br>
Hardware:<br>
CPU: i7 4790S<br>
RAM: 8GB DDR3<br>
STORAGE: 256GB SSD + 512GB HDD<br>
<br>
Deployments:<br>
<br>
/Network<br>
MetalLB: LoadBalancer solution to expose kubernetes services via individual IPs in my LAN<br>
Pihole: Configured to run as a local DNS + Ad blocker with upstream DNS pointing to Google.<br>
<br>
/Storage<br>
NextCloud: Shared storage solution for my LAN, backed by postgreSQL
