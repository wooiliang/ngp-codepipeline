# IaC for Creating CodePipeline

### Prerequisites
1. Create an s3bucket in US region to store the lamda function.
2. Create an ECR repository in the region containing the ECS CLUSTER.
3. The application repository must contain `ecs/service.yaml` and `buildspec.yaml`.

### Steps to install.
1. Run `bash bin/configure.sh`.
2. Open the link and at the end of the script to continue the installation.
3. Sample parameters can be seen in `parameter.json`

### Architecture
![Preview](CICDPipeline.png)
