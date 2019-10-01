# InstallFusionInventoryAgentForDebian
Script to make the FusionInventory agent installation unattended on Debian and Ubuntu systems.
To install FusionInventory agent on Debian or Ubuntu, check the options (end of the line) and execute 
```
wget -O - https://raw.github.com/J-C-P/InstallFusionInventoryAgentForDebian/master/install.sh | bash -s -- --version 2.5.1-1 --taskcollect true --tasknetwork true --tasknetwork true --taskesx true --agentconfig "server = https://myserver.mydomain.local/glpi/plugins/fusioninventory|no-ssl-check = 1|httpd-trust = 192.168.0.25"
```
