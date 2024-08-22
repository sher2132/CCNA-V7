# CCNA-V7
# Configure Router Interfaces

<p>R1(config)# interface gigabitethernet 0/0/0</p>

R1(config-if)# ip address 192.168.10.1 255.255.255.0 

R1(config-if)# ipv6 address 2001:db8:acad:1::1/64 

R1(config-if)# description Link to LAN 1

R1(config-if)# no shutdown

R1(config-if)# exit

R1(config)# interface gigabitethernet 0/0/1

R1(config-if)# ip address 192.168.11.1 255.255.255.0 

R1(config-if)# ipv6 address 2001:db8:acad:2::1/64 

R1(config-if)# description Link to LAN 2

R1(config-if)# no shutdown

R1(config-if)# exit

R1(config)# interface serial 0/0/0

R1(config-if)# ip address 209.165.200.225 255.255.255.252 

R1(config-if)# ipv6 address 2001:db8:acad:3::225/64 

R1(config-if)# description Link to R2

R1(config-if)# no shutdown

R1(config-if)# exit

R1(config)#

