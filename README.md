# hast_cluster

This is a FreeBSD script to control a redundant file server using HAST and CARP.

## Installing

This should be located on each host to be running as a file server master in /usr/local/etc/rc.d/ folder.

example:
```
cp hast_cluster /usr/local/etc/rc.d/hast_cluster
```

### Usage

```
hast_cluster start
hast_cluster stop	- switch to slave mode 
hast_cluster slav	- switch to slave mode
hast_cluster master	- switch to master mode
```

### Add the necessary variables to your /etc/rc.conf

example:
```
(pending)
```

### Add a sensor for carp failover to devd 

example:
```
(pending)
```
