# QUIP-TESTNET-NODE

# Requirements
- pc
- good network

# STEP 1: install quick node manager
1. windows (powershell)
   run
   <pre>
     irm https://gitlab.com/quip.network/quip-node-manager/-/raw/main/scripts/install.ps1 | iex
   </pre>

2. Mac (terminal)
   run
   <pre>
     curl -fsSL https://gitlab.com/quip.network/quip-node-manager/-/raw/main/scripts/install.sh | sh
   </pre>

<img width="1089" height="598" alt="quick node install" src="https://github.com/user-attachments/assets/6184e2af-ef00-4e76-95d3-b73b6c293ab1" />

after installation, run
<pre>
  quip-node-manager
</pre>

# STEP 2: install docker and enable wsl integration
- install [here](https://docs.docker.com/desktop/)
- enable wsl integration
  a. go to settings
  b. click on resources
  c. click on wsl integration
  d. enable it and save changes

<img width="1044" height="557" alt="enable wsl integration in docker" src="https://github.com/user-attachments/assets/4bcb97c4-e5b9-44b6-8473-1433b2f8c1de" />

# STEP 3: Pull images on docker
- go to docker global search and search for (carback1/quip-network-node-cpu)
- then pull the image manually
<img width="1920" height="886" alt="image" src="https://github.com/user-attachments/assets/e6ae1b2e-1016-4170-8953-21a6c5ecc09a" />

# STEP 4: confirm node image version
- in the quick node manager, confirm node version by recheckingf
- if not up to date, pull latest image from the manager
<img width="1908" height="346" alt="image" src="https://github.com/user-attachments/assets/26e65051-f432-4011-8191-15c4b63ceb61" />

# STEP 5: generate node secret
- scroll down to configurations
- add node name
- generate node secrets and save
- also enable automine
<img width="1894" height="492" alt="generate secret" src="https://github.com/user-attachments/assets/b126c676-7763-4f2e-8fd5-f722cfbc8a66" />

# STEP 6: start node
- after completing all configurations, kickstart the node
- you can check logs at the bottom of the node manager app

<img width="1532" height="603" alt="check logs" src="https://github.com/user-attachments/assets/b07691d2-ac96-4c82-bf09-1c6e7fa6b7b7" />

# others
- to start the node manager app
  open your terminal and run
  <pre>
    quip-node-manager
  </pre>

## according to quip, node will be rewarded on mainnet, but still keep expectations low

# made by Chuks
