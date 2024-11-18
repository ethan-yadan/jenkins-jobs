![Jenkins Pipeline Meme](pipelinememe.png)

# Jenkins Jobs Task 

Create Jenkins job that you can trigger via `curl` command, which will clone the project (details-app) from the github/gitlab and build container 
with it and push that container to docker hub registry.

- Create Token on your jenkins account
- Test to run the test job via `curl` command
- Create Job that will do the following:
    - Clone project(details-app) from gitlab/hub
    - Build docker images
    - Tag docker images with docker hub registry to push to.
    - Push to registry
      

## Table Of Contents

- [Prerequisites](#prerequisites)
- [Links](#links) 
- [Usage](#usage)
- [Script](#script)
- [Installation](#installation)
- [Contributing](#contributing)


## Prerequisites

- Hardware Requirments:
    - CPU: Modern processor with reasonable processing power
    - RAM: At least 2 GB of RAM
    - Disk: At least 10 GB of free space
      
- Software Requirments:
    - Linux Debian distribution
    - Python 3.5 or later (python ≥ 3.6 is recommended) and pip are installed
    - Docker environment installed (docker-compose)
    - Java Development Kit (JDK), compatible JDK installed
    - Account on docker hub
    - Firewall: Ensure FW allows traffic to 8080 port

      
## Links
- [Project: Details-App](https://github.com/zero-pytagoras/details-app.git)


## Installation 


### Updating, upgarding and installing in linux debian: 

1. ''' sudo apt update '''
2. ''' sudo apt-get upgrade '''
3. ''' sudo apt install python3-pip '''
4. ''' sudo apt install docker-compose '''
5. ''' sudo apt install default-jdk '''

### Adding Jenkins repository, installation and access: 

6. ''' sudo wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io-2023.key | sudo gpg --dearmor -o /usr/share/keyrings/jenkins-keyring.asc '''
7. ''' echo deb-src [signed-by=/usr/share/keyrings/jenkins-keyring.asc] https://pkg.jenkins.io/debian-stable binary/ '''
8. ''' sudo tee /etc/apt/sources.list.d/jenkins.list '''
9. ''' sudo apt update ''''
10. ''' sudo apt install jenkins '''
11. ''' sudo systemctl start jenkins '''

token 
install jenkins updates and packages 
web interface

- Jenkins master
- RestAPI access via account
- Jenkins Job With Required Steps

