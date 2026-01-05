## Rocky Linux:

Rocky Linux is a free, open-source, community-driven Linux distribution built as a reliable, production-grade, and stable alternative to Red Hat Enterprise Linux (RHEL), aiming to be a direct successor to the original CentOS, offering 1:1 binary compatibility for servers, desktops, and cloud use with a long-term support lifecycle, backed by the Rocky Enterprise Software Foundation. 

It was created to fill the gap left when CentOS Linux was discontinued as a stable downstream RHEL clone.


### Key Facts: 
- Founder: Gregory Kurtzer (original CentOS founder)
- First Release: 2021
- License: Open Source (GPL & others)
- Target Users: Enterprises, servers, DevOps, cloud, hosting providers
- Release Model: Stable, long-term support


### Default Components:
- SELinux (Enforcing)
- Firewalld
- systemd
- NetworkManager
- XFS filesystem
- Cockpit (optional web UI)


### Security Features: 
- SELinux enforcing by default
- OpenSCAP compliance
- Firewalld
- FIPS support
- Regular CVE updates


Rocky Linux is one of the best choices for a free, enterprise-class Linux OS. 


## Most Common Packages on Rocky Linux: 

Below is a most-common, battle-tested package list that almost everyone installs on Rocky Linux 8/9 after a fresh install — suitable for servers, DevOps, and daily admin work.


#### System Update:

```
dnf update -y

dnf install -y epel-release 
```



#### Core Utilities:

```
dnf install -y vim nano wget curl git zip gzip unzip tar net-tools lsof htop rsync screen tree parted lvm2 bash-completion dnf-utils 
```


#### Networking & Troubleshooting:

```
dnf install -y net-tools bind-utils traceroute tcpdump nc nmap telnet
```


#### Development & Build Tools:

```
dnf groupinstall -y "Development Tools"
```


```
dnf install -y gcc gcc-c++ automake make autoconf libtool cmake readline-devel zlib-devel systemd-devel flex bison libicu-devel  
```


```
dnf install -y freetype fontconfig
```



#### Language Runtimes:

```
dnf install -y python3 python3-pip python3-devel
dnf install -y perl perl-core perl-devel
dnf install -y golang
dnf install -y ruby ruby-devel
```





