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


## OUTPUT:
WHOIS
![img1](https://github.com/user-attachments/assets/bef338c7-4445-47e6-82e5-a0f24a67056f)

WEB ARCHIEVE
![img2](https://github.com/user-attachments/assets/162d54fb-a276-489d-bee1-5fed95ec508b)

IP2 LOCATION
![img3](https://github.com/user-attachments/assets/2d89ef70-bfda-4a56-aeff-c4f5b3cfa63c)

OUTPUT
![img4](https://github.com/user-attachments/assets/a7fc98b3-3fb0-409b-b325-71c1d8ca4aa5)

nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
OUTPUT
![img5](https://github.com/user-attachments/assets/6bb45ea6-58f7-4760-a222-33502c700d1a)

WhatWeb:
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
```
OUTPUT
![img6](https://github.com/user-attachments/assets/033a9032-7fd5-4c6d-8c66-99d4d83f9204)

httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
OUTPUT

![img7](https://github.com/user-attachments/assets/19d6ccc4-88c6-4913-b467-85af40c08306)

Tracing the Location:
```
sudo traceroute -T www.saveetha.ac.in
```
OUTPUT
![img8](https://github.com/user-attachments/assets/a3bc798c-bf97-4669-898f-5d0fd34209eb)

UDP Traceroute:
```
sudo traceroute -U www.saveetha.ac.in
```
OUTPUT
![img9](https://github.com/user-attachments/assets/d69d24db-5516-4af5-beb8-1e68b1296691)

ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
OUTPUT
![img10](https://github.com/user-attachments/assets/ee6e2e20-b4e4-44ad-a737-26b3898984f3)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
