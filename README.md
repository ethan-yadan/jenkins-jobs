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
- [Usage](#usage)
- [Script](#script)
- [Installation](#installation)
- [Contributing](#contributing)


## Prerequisites
1. Linux Debian distribution
2. python 3.5 or later (python ≥ 3.6 is recommended) and pip are installed
3. Docker environment installed (docker-compose)
4. Account on docker hub

## Installation 
### Updating, upgarding and installing in linux debian: 

1. ''' sudo apt update '''
2. ''' sudo apt-get upgrade '''
3. ''' sudo apt install python3-pip '''
4. ''' sudo apt install docker-compose '''
5. ''' ansible --version '''
   * check ansible installed and version 

- Jenkins master
- RestAPI access via account
- Jenkins Job With Required Steps

sudo apt install default-jdk
