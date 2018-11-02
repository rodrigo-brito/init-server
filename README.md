# vm-init

This repository store my personal scripts do start virtual machines (VMs) on GCP / AWS.



## Scripts

 - Installing dependencies (docker, htop, build-essential, node/yarn): 
 
```sudo curl -s https://raw.githubusercontent.com/rodrigo-brito/init-server/master/scripts/dependencies.sh | sudo bash -s```

 - Configuring SWAP (configure 4GB of SWAP): 

```sudo curl -s https://raw.githubusercontent.com/rodrigo-brito/init-server/master/scripts/swap.sh | sudo bash -s 4G```
