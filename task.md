# Jenkins jobs task

Create Jenkins job that you can trigger via `curl` command, which will clone the project (details-app) from the github/gitlab and build container with it and push that container to docker hub registry

### Pre Requisits

- Account on docker hub
- Linux vm (debian/rocky based)
- Docker and docker-compose installed
- Jenkins master
- RestAPI access via account
- Jenkins Job With Required Steps

### Tasks

- Create Token on your jenkins account
- Test to run the test job via `curl` command
- Create Job that will do the following:
    - Clone project(details-app) from gitlab/hub
    - Build docker images
    - Tag docker images with docker hub registry to push to.
    - Push to registry

### Notes
- Jenkins Job can be done with any scripting language while `shell` being the main default.
    - One may use any other language while it is installed on the Jenkins master container
    - If you wish to use python/Go/ruby/PowerShell, verify first that these are installed on the jenkins master container




