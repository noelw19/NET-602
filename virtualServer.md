# Windows Server 2019 ADDS 

I have installed a gui version of windows server 2019 on a virtual machine

root domain : corps.DC.local
net bios name: CORPS
pass: Thepasswordis42

#### step 1
>I installed the server and opened the server manager

#### step 2 
>I changed the name of the computer to something more fitting and configured 
>static ip and DNS gateways
>| name | value |
>|----|----|
>| IP | 192.168.1.10 |
>| subnet mask | 255.255.255.0 |
>| Gateway | 192.168.1.1 |
>| DNS | 8.8.8.8 |
>| DNS2 | 127.0.0.1 |

have currently finished promoting the server to DC and have completed the dhcp config.....

after i fully set up the server adding the above and then begin to setup the client computer with windows 10 pro so that the device is able to connect to a network and then by joining a domain on start up

firstly going to settings ipv4 settings and setting up a static ip address that is within the server subnet range 

| Name | Value |
|----|----|
| IP | 192.168.1.100 |
| Mask | 255.255.255.0 |
|gateway | ServerAddr - 192.168.1.10 |
| DNS |
|preffered | 192.168.1.10 |

Password for the user NWilliams is: P@ssword12

# To do:
setup sophos
setup wsus
setup hyperv 
setup rsat

#Sophos

Gui is accessed through the web browser using the dc gatewat ip and the port that is being used.
