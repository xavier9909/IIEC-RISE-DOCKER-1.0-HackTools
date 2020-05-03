# IIEC-RISE-DOCKER-1.0-HackTools 
This project contains few bug hunting tools which can help you to secure your networks, web-apps, server
etc. 

# NOTE
THIS IMAGE PURELY MEANT FOR BUGHUNTING N PENTESTING. DO NOT USE THIS IMAGE FOR ANY ILLEGAL ACTIVITIES

# Requirements/Installation
These instructions will get you a copy of the project up and running on your local machine

* ## Make sure you have the latest versions of Docker installed on your machine.
For installing run the commands:

# For Docker Installation on RedHat/Centos:
 Prerequisite-yum configured-
* login as root, open terminal
* Run command- `cd /etc/yum.repos.d/`
![go to yum](https://github.com/xavier9909/hacktools/blob/master/go%20to%20yum%20repositories.png)

* Now, (To create a repository file, you can use any name.repo)   
`gedit docker.repo` 
![make docker repo](https://github.com/xavier9909/hacktools/blob/master/create%20docker%20repository.png)
* In the docker.repo paste this this url (https://download.docker.com/linux/centos/7/x86_64/stable/) and type
![content of docker repo](https://github.com/xavier9909/hacktools/blob/master/content%20of%20docker%20repository.png)
* Run
`yum install docker-ce --nobest` 
![install docker](https://github.com/xavier9909/hacktools/blob/master/cmd%20to%20install%20docker.png)
* ## To verify 
`docker version` 
![verify](https://github.com/xavier9909/hacktools/blob/master/verify%20docker%20version.png)
* ## Start Docker
```
systemctl start docker
`systemctl enable docker
```
![demo](https://github.com/xavier9909/hacktools/blob/master/start%20n%20enable%20docker.png)

# BONUS
# Install Docker on Windows 7
 * Verify your Windows OS is 64-bit (x64)
 * Install DOCKER TOOLBOX
 * Link:::(https://github.com/docker/toolbox/releases)
 ![DEMO](https://github.com/xavier9909/hacktools/blob/master/2020-05-03.png)
 
 * ## Now, Run .exe file to Install it
 
 ![DEMO](https://docs.docker.com/toolbox/images/installer_open.png)
 
 # For Installing Image
```
docker pull xavier9909/hacktoools:1
```
# Final Step:RUN
![DEMO](https://github.com/xavier9909/hacktools/blob/master/projectshowcase.png)

# Tools you get
- altdns 
- bucket_finder 
- CloudFlair 
- commix
- dirb
- dirsearch 
- dnsenum 
- dnsrecon
- gobuster
- joomscan 
- Knockpy
- masscan
- massdns
- Nikto
- Nmap
- Recon-ng
- s3recon
- sqlmap
- subfinder
- Sublist3r
- dotdotpwn
- teh_s3_bucketeers
- thc-hydra
- theHarvester
- virtual-host-discovery
- wafw00f
- wfuzz
- wpscan
- XSStrike
- tmux
- instainsane
- proxychain

 # Wordlists
 * SecLists
 * rockyou.txt
 
 
 # Why should bughunters use this Toolkit
 * This toolkit have all the required tools any hunter need
 * It can be customized to add or remove specific tools
 * It can run in very low-end pc without any problm
 
 # Reference
* IIEC RISE 1.0 DOCKER (https://www.youtube.com/watch?v=3Kn6_b-1mK4&list=PLAi9X1uG6jZ30QGz7FZ55A27jPeY8EwkE) 
* IIEC CONNECT 1.0 (https://www.youtube.com/channel/UCtY-JhEZ3iPLtozWGgd2efQ)
* Google (https://www.google.com/)
* RedHat 8 (https://developers.redhat.com/rhel8/)
* Docker (https://docs.docker.com/docker-hub/official_images/)

 # Author
  Kajal Kashyap
  Shubham Meena

