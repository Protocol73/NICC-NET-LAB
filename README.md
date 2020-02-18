#Networking-Room111-NICC.MD

=-=-=-=-= BEGIN NETWORK DOCUMENTATION =-=-=-=-=

The lab network for room 111 is shared with room 107a.

The Network is 192.168.148.0/22 = (255.255.252.0)

The Gateway is 192.168.148.1 on the Edge Router.
The subnet mask on the router is set as /16
This is set to allow any 192.168.XX.XXX network.

DHCP & DNS are at 192.168.148.240 hosted via PFsense.

The Domains are .netlabs & .idrac more can/will be added.

All Dell Servers IDRAC's can be used via this format.

=-=-=-=-=-= [https://SERVERNAME.idrac] =-=-=-=-=-=

All Proxmox Server's can be used via this format.

=-=-=-= [https://SERVERNAME.netlabs:8006] =-=-=-=

 Note: The number in the hostname of a Proxmox
 server is used to show the order of said servers
 in the web interface and not part of the FQDN.

=-=-=-=-= END NETWORK DOCUMENTATION =-=-=-=-=

--Written by Protocol73