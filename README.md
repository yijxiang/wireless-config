## wireless-config

#### How to use tcpdump on DNA center for netflow traffic src from edge2 switch
sudo tcpdump src 172.16.20.3 and dst port 6007 -w edge2.pcap


#### show run 文件
主要是9800 WLC 配置文件


#### factory-reset all

https://www.cisco.com/c/en/us/td/docs/switches/lan/catalyst9300/software/release/16-12/configuration_guide/sys_mgmt/b_1612_sys_mgmt_9300_cg/simplified_factory_reset.html



#### ROMMON tftp boot

Use set to set an address:

switch: set IP_ADDRESS 192.168.1.2
Use set to set a subnet mask:

switch: set IP_SUBNET_MASK 255.255.255.0
Use set to set a default gateway:

switch: set DEFAULT_GATEWAY 192.168.1.1

