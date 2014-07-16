0. set new root password
1. change config values:
	lxc.network.hwaddr
	lxc.rootfs
	lxc.utsname

2. add to config
	lxc.network.ipv4 = 10.10.0.1/32
	lxc.network.ipv4.gateway = 10.1.1.1

3. set hostname in:
	/etc/hosts
	/etc/sysconfig/network

4. set cgroups tariff
