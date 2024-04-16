# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

# Pen Test Tools Categories:  

Following Categories of pen test tools are identified for information gathering:

Footprinting is a part of the reconnaissance process which is used for gathering possible information about a target computer system or network.
http://www.whois.com/whois website to get detailed information about a domain name information including its owner, its registrar, date of registration, expiry, name server, owner's contact information, etc.

## output
![1 whois](https://github.com/danush564/InformationGathering/assets/98585166/4848893e-ea34-45de-9421-922980210d32)

# Finding IP address:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of facebook.com.
## output

![2 ping](https://github.com/danush564/InformationGathering/assets/98585166/51581402-c19a-4fd2-bbed-005e18c30994)

# Finding Hosting Company
get further detail by using ip2location.com website.
## output

![3 ip2location](https://github.com/danush564/InformationGathering/assets/98585166/5ff8288c-0322-4db5-9176-a36b8fe7220e)

# History of the website:
```
https://web.archive.org/
```
## output

![4 web archive](https://github.com/danush564/InformationGathering/assets/98585166/5b560f51-892d-46b0-8a65-8b1b8e51a8bb)

# Webserver Fingerprinting:

## Netcat:
sudo nc example.com 80
GET / HTTP/1.1
Host: example.com
## output

![5 nc command](https://github.com/danush564/InformationGathering/assets/98585166/ddfdd978-02e0-4e79-b367-2a1a34da0905)

## nmap:
## #output

![6 nmap](https://github.com/danush564/InformationGathering/assets/98585166/7b8003cb-26a7-4bc2-9ac3-256b8a093c77)

# Whatweb
## output

![7 whatweb](https://github.com/danush564/InformationGathering/assets/98585166/4e95dd8a-61f9-448c-91d3-97ffbc58f3e1)

# httprint
## output

![8 httprint](https://github.com/danush564/InformationGathering/assets/98585166/85bef9bb-78d4-4abe-91cd-bc2a41cd4da8)

# Tracing the Location
TCP Traceroute:
sudo traceroute -T www.google.com
## output

![9 tcp traceroute](https://github.com/danush564/InformationGathering/assets/98585166/a9197d7e-2dff-4b70-b157-9e1e3dfaefa5)

# UDP Traceroute:
sudo traceroute -U www.google.com
## output

![9 udp traceroute](https://github.com/danush564/InformationGathering/assets/98585166/2a183f2a-4808-40aa-a942-aa568f1d6a6f)


# ICMP Traceroute:
sudo traceroute  www.google.com
## output

![9 ICMP traceroute](https://github.com/danush564/InformationGathering/assets/98585166/ab761f08-39f2-40c7-8ba9-330594861038)

# Netcraft
## output

![10 netcraft](https://github.com/danush564/InformationGathering/assets/98585166/8c7b05c5-e18b-4acc-80cb-95a8ee51df3d)

# Wapplyzer
## output

![11 wappalyzer](https://github.com/danush564/InformationGathering/assets/98585166/285bc538-1dc8-4f5f-b179-4ce9539da518)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
