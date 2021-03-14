# Install Portainer into an Proxmox LXC container

The memory and cpu resources needed to run a LXC container are quite a bit less than running a VM and modifing the resouces assigned to the LXC container can be done without having to reboot the container.

## Usage

***Note:*** _Before using this repo, make sure your Proxmox host is up to date._

To setup Portainer within a new LXC container on your Proxmox host, download the following script:

```
wget -qL https://github.com/fiveangle/proxmox_portainer_lxc/raw/master/create_container.sh
```

Then edit create_container.sh to set your desired disk size, hostname, portainer version, etc...

Launch with:

```
bash create_container.sh
```

Then follow the prompts

Enjoy !

-=dave
