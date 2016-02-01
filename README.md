# coreos-mesos-ceph-cluster
Launch a fully dockerized Mesos and Ceph cluster on CoreOS via Vagrant

## General setup

1) Install dependencies

* [VirtualBox][virtualbox] 4.3.10 or greater.
* [Vagrant][vagrant] 1.6 or greater.

2) Clone this project and get it running!

```
git clone https://github.com/tobilg/coreos-mesos-ceph-cluster.git
cd coreos-mesos-ceph-cluster
```

3) Startup, status and SSH

The VirtualBox provider is the default Vagrant provider. Use this if you are unsure.

**Startup**
```
vagrant up
```

**Status check**
```
vagrant status
```

will show something like

```
Current machine states:

core-01                   running (virtualbox)
core-02                   running (virtualbox)
core-03                   running (virtualbox)
```
