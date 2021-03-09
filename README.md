# proxmoxbackupserver
Proxmox Backup Server - Docker Image

# Interactions
## Storage 

Docker volume is used and mounted at /mnt/pbs
Create a new datastore in PBS to store data at /mnt/pbs to store backups insid the docker volume

## networking
ensure you pass port 8007 in to the internal port of 8007 for proxmox backup server to function correctly
