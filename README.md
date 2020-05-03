# HACKTOOLS - Docker Project
hacktools contain some bug hunting tools which can help you to secure your networks,web-apps,server
etc. 

# NOTE
THIS IMAGE PURELY MEANT FOR BUGHUNTING N PENTESTING. DO NOT USE THIS IMAGE FOR ANY ILLEGAL ACTIVITIES

# Requirements/installation
These instructions will get you a copy of the project up and running on your local machine

# Make sure you have the latest versions of Docker installed on your machine.
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

#BONUS
#INSTALL DOCKER ON WINDOWS 7
*Verify your Windows OS is 64-bit (x64)
*INSTALL DOCKER TOOLBOX
 *LINK:::(https://github.com/docker/toolbox/releases)
 ![DEMO](https://github.com/xavier9909/hacktools/blob/master/2020-05-03.png)
 *AFTER THAT RUN .EXE FILE INSTALL IT
 
 ![DEMO](https://docs.docker.com/toolbox/images/installer_open.png)

 
 
 


# TOOLS
altdns,bucket_finder,CloudFlair,commix,dirb,dirsearch,dnsenum,dnsrecon,gobuster,joomscan,Knockpy
masscan,massdns,Nikto,Nmap,Recon-ng,s3recon,sqlmap,subfinder,Sublist3r,dotdotpwn,teh_s3_bucketeers
thc-hydra,theHarvester,virtual-host-discovery,wafw00f,wfuzz,wpscan,XSStrike,tmux,instainsane,proxychain

 # wordlists
    >SecLists
    >rockyou.txt
 
 
 # Why should bughunters use this toolkit
    >This toolkit have all the required tools any hunter need
    >can be customized to add or remove specific tools 
    >can run in very low-end pc without any problm
 
 # REQUIREMENTS
    >OS (win-linux-mac)
    >Docker:latest
    >Internet connection
 
 # DOWNLOAD
     >docker pull 
