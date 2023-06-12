# Security Essentials
## In this course I acquired fundamental knowledge and skills required to assist with cybersecurity operations and practices. I learned about various potential threats and attacks. Implemented solutions to mitigate risks. Applied monitoring and assessment techniques to networks, applications, host devices, and cloud solutions. I learned the importance of data ownership and regulations. I respond to incidents and conducted analysis.
### In this activity, I used common network tools, such as local commands and the Nmap network mapper, to discover other hosts on the local network. Next, I conducted a banner grabbing exercise to identify specific services on the hosts. Finally, I used DNS tools to gather name resolution information.
I ran the ifconfig command to display the interface configuration.

![ifconfig](https://github.com/iamroot-GitHub/Security-Essentials/blob/27da5d9d0de8f8d261f360198534d32e3b2a9b5f/Images/SINN_01.png)

I ran the IP route show command to identify the default gateway.

![IP route show](https://github.com/iamroot-GitHub/Security-Essentials/blob/ba416ec5d9f9cda3317b07a8e0e18194c5a5c71d/Images/SINN_02.png)

I ran the arp -a command to check the ARP cache to display other hosts local to this subnet.

![arp -a](https://github.com/iamroot-GitHub/Security-Essentials/blob/4adc0384d2fa94fc7bf59cfe3906a65d72ed3c7b/Images/SINN_03.png)

I ran the netdiscover command to verify whether any other hosts were present.

![netdiscover](https://github.com/iamroot-GitHub/Security-Essentials/blob/75e30aeab96bef93e99ba648630e5d1609672b2c/Images/SINN_04.png)

I ran the ipconfig command to display the IP address configuration for the Windows Server.

![ipconfig](https://github.com/iamroot-GitHub/Security-Essentials/blob/c500c96afce50a346d73b33a185169ee6aa6e32f/Images/SINN_05.png)

I ran the pathping command to test the reliability (packet loss) and latency (delay) of the connection between the Windows Server VM and the Kali VM, discovering that the two machines are not very far apart on the network (on the same subnet in fact).

![pathping](https://github.com/iamroot-GitHub/Security-Essentials/blob/2d61d8f4b4dd0751db88245a97ece8886a063773/Images/SINN_06.png)

I ran the nmap localhost command to scan the Kali VM (discovering port 22/tcp open), the nmap command to do a basic network scan, and the nmap -sS command to check the output (dicovering that SSH and DNS services are running).

![nmap](https://github.com/iamroot-GitHub/Security-Essentials/blob/5f3732e3025b38ccdd7c764101a4ad80cda7c49a/Images/SINN_07.png)

I ran the nmap -A command to identify more about the host, discovering that the host was running the Linux OS.

![nmap -A](https://github.com/iamroot-GitHub/Security-Essentials/blob/d1b81d605c6b0720af72ec714ed9ba5df25ff296/Images/SINN_08.png)

I ran the nmap -p and nmap --top-ports for open ports 20-200 and the 20 most common ports.

I ran the nmap -sn command to quickly scan the network for hosts that were up or down to discover which server was configured as an email server.
