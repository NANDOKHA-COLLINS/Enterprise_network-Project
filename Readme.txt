Base network 192.168.10.0
no. of departments= 3
departments=networks
number of subnets =3
number of networks/Subnets  = 2^n
where n = no. of bits borrowed from the host part

2^n = 3  N/B The number of networks must first satisfy the need 
and serve for future use.The number of subnets should be a 
little bit higher than what is needed 


Subnetting 192.168.10.0
default subnet mask= 255.255.255.0   11111111.11111111.11111111.00000000
New subnetmask =255.255.255.192      11111111.11111111.11111111.11000000

As per the requirement, we borrow 2 bits from the host to the network
2^2 =4 networks/Subnets
Block size = 256 - (Bits borrowed concerted to decimal)
Magic table
128 64 32 16 8  4 2 1 =255
1     1    0   0  0  0 0 0 =192

1st subnet I.D 192.168.10.0
Host range 192.168.10.1 - 192.168.10.62   Broadcast I.P 192.168.10.63

2nd subnet I.D 192.168.10.64
Host range 192.168.10.65 -192.168.10.126 Broadcast I.P 192.168.10.127

3rd Subnet I.D  192.168.10.128
Host range 192.168.10.129 - 192.168.10.190 Broadcast address 192.168.10.191

4rd Subnet I.D  192.168.10.192
Host range 192.168.10.193 - 192.168.10.254 Broadcast address 192.168.10.255


             Prepared by NANDOKHA COLLINS
             nandokhacollin0@gmail.com
