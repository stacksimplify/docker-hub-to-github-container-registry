# Docker Hub to GitHub Container Registry

## Step-01: Docker Hub Pull Limits
- Docker Hub limits the number of Docker image downloads (“pulls”) based on the account type of the user pulling the image. 
- Pull rates limits are based on individual IP address. For anonymous users, the rate limit is set to 100 pulls per 6 hours per IP address. 
- For authenticated users, it’s 200 pulls per 6 hour period. 
- Users with a paid Docker subscription get up to 5000 pulls per day.
- [Docker Pull Limits](https://docs.docker.com/docker-hub/download-rate-limit/)

## Step-02: GitHub Container Registry Packages
- Link to [GitHub Container Registry Packages](https://github.com/stacksimplify?tab=packages)

## Step-03: Docker Image List: Docker Hub vs GitHub Container Registry 
- To download the Docker Image from GitHub Container Registry we just need to prefix `ghcr.io/` for the Docker Image from Docker Hub. This is for our StackSimplify 13 Docker Images only.

|S.No| Docker Hub Image  | GitHub Container Image |
|----| ------------- | ------------- |
|01| stacksimplify/kubenginx:1.0.0  | ghcr.io/stacksimplify/kubenginx:1.0.0  |
|| stacksimplify/kubenginx:2.0.0  | ghcr.io/stacksimplify/kubenginx:2.0.0  |
|| stacksimplify/kubenginx:3.0.0  | ghcr.io/stacksimplify/kubenginx:3.0.0  |
|| stacksimplify/kubenginx:4.0.0  | ghcr.io/stacksimplify/kubenginx:4.0.0  |
||   |   |
|02| stacksimplify/kube-usermgmt-webapp:1.0.0-MySQLDB  | ghcr.io/stacksimplify/kube-usermgmt-webapp:1.0.0-MySQLDB  |
||   |   |
|03| stacksimplify/notifications-microservice:1.0.0  | ghcr.io/stacksimplify/notifications-microservice:1.0.0  |
|| stacksimplify/notifications-microservice:2.0.0  | ghcr.io/stacksimplify/notifications-microservice:2.0.0  |
||   |   |
|04| stacksimplify/kube-usermanagement-microservice:1.0.0  | ghcr.io/stacksimplify/kube-usermanagement-microservice:1.0.0  |
|| stacksimplify/kube-usermanagement-microservice:2.0.0-H2DB  | ghcr.io/stacksimplify/kube-usermanagement-microservice:2.0.0-H2DB  |
|| stacksimplify/kube-usermanagement-microservice:3.0.0-AWS-XRay-MySQLDB  | ghcr.io/stacksimplify/kube-usermanagement-microservice:3.0.0-AWS-XRay-MySQLDB  |
|| stacksimplify/kube-usermanagement-microservice:4.0.0-AWS-XRay-H2DB  | ghcr.io/stacksimplify/kube-usermanagement-microservice:4.0.0-AWS-XRay-H2DB  |
||   |   |
|05| stacksimplify/kube-notifications-microservice:1.0.0  | ghcr.io/stacksimplify/kube-notifications-microservice:1.0.0  |
|| stacksimplify/kube-notifications-microservice:2.0.0  | ghcr.io/stacksimplify/kube-notifications-microservice:2.0.0  |
|| stacksimplify/kube-notifications-microservice:3.0.0-AWS-XRay  | ghcr.io/stacksimplify/kube-notifications-microservice:3.0.0-AWS-XRay  |
|| stacksimplify/kube-notifications-microservice:4.0.0-AWS-XRay  | ghcr.io/stacksimplify/kube-notifications-microservice:4.0.0-AWS-XRay  |
||   |   |
|06| stacksimplify/kube-nginxapp1:1.0.0  | ghcr.io/stacksimplify/kube-nginxapp1:1.0.0  |
||   |   |
|07| stacksimplify/kube-nginxapp2:1.0.0  | ghcr.io/stacksimplify/kube-nginxapp2:1.0.0  |
||   |   |
|08| stacksimplify/kube-frontend-nginx:1.0.0  | ghcr.io/stacksimplify/kube-frontend-nginx:1.0.0  |
||   |   |
|09| stacksimplify/kube-helloworld:1.0.0  | ghcr.io/stacksimplify/kube-helloworld:1.0.0  |
||   |   |
|10| stacksimplify/usermanagement-microservice:1.0.0  | ghcr.io/stacksimplify/usermanagement-microservice:1.0.0  |
||   |   |
|11| stacksimplify/nginxapp2:latest  | ghcr.io/stacksimplify/nginxapp2:latest  |
||   |   |
|12| stacksimplify/nginxapp1:latest  | ghcr.io/stacksimplify/nginxapp1:latest  |
||   |   |
|13| stacksimplify/dockerintro-springboot-helloworld-rest-api:1.0.0-RELEASE  | ghcr.io/stacksimplify/dockerintro-springboot-helloworld-rest-api:1.0.0-RELEASE  |
||   |   |