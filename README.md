# Proxmox Check Commands

This Repo does have several Nagios/icinga checks for Proxmox

# CMD Syntax check_proxmox_cluster_node_onlinestatus

`Usage: check_proxmox_cluster_node_onlinestatus -H <HostIP> -u <username> -t <tokenname> -s <secret> -n <nodeNumber>`

# CMD Syntax check_proxmox_cluster_onlinestatus

```
Usage: check_proxmox_cluster_node_uptime -H <HostIP> -u <username> -t <tokenname> -s <secret> -n <nodeName> -c <critical>
```


critical value: seconds (if uptime is less then critical value it's CRITICAL)
