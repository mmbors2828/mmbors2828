- 👋 
- 👀 Development with NodeJs using express framework
- 🌱 I’m currently learning 
- 💞️ I’m looking to collaborate on Uni Frankurt research
- 📫 How to reach me at Uni Frankfurt
- 😄 Pronouns: her / she
- ⚡ Fun fact: developments will be uploaded and run in AWS

<!---
mmbors2828/mmbors2828 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->


how to create the docker
https://dockerize.io/guides/node-express-guide

push commands for ecr 
__________________________
##retrieve auth token for ECR
look at push commands

## build docker image
docker build -t meimay_repo .

##tag image to push to ecr 
docker tag meimay_repo:latest 429736510743.dkr.ecr.eu-central-1.amazonaws.com/meimay_repo:latest


## push to aws 
docker tag meimay_repo:latest 429736510743.dkr.ecr.eu-central-1.amazonaws.com/meimay_repo:latest

