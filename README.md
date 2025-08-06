Step1
Create an EC2 instaance 
Make a folder of Nodejs-demo-app
create file index.js, Package.js,Dockerfile,ci.yml
git init
git remote add origin https://github.com/skandakumar1992/node-demo-app.git
git add .
git commit -m "Initial commit"
git push -u origin main

Step2
Install a docker.io in the Instance
create a  image in the docker
create a cointainer in the docker

Step3
In your GitHub repo:
Go to Settings > Secrets and variables > Actions > New repository secret
Add:
DOCKER_USERNAME = your Docker Hub username
DOCKER_PASSWORD = your Docker Hub password or personal access token

Step4
A fully working CI/CD pipeline.
Image available at: docker.io/YOUR_USERNAME/your-nodejs-app:latest



