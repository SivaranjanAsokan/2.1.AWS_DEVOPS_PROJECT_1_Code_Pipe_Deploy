#DEPLOYMENT THROUGH CICD (GIT/JENKINS/AWS_SERVICES)
![image](https://github.com/SivaranjanAsokan/CICD-Static-web-deployment/assets/163242501/f361edaa-a986-4bd9-98fd-37a2e4904069)

Sivaranjan Asokan
♾️DevOps Engineer || ☁️ AWS Cloud || 🤵🏻 Jenkins || 🐳 Docker || 🚀Terraform || ☸️ K8s || 🐧Linux ||🔗Git@GitHub
1 article
May 14, 2024

#Open Immersive Reader:
CICD-Static-Page-Deployment: Full-PROJECT With Doc

#AWS Services:
1.S3 2.CODE-PIPELINE 3.CODE-DEPLYMENT 4.VPC 5.EC2
#TOOLS:
1.GIT BASH(LOCAL UPLOAD) 2.GITHUB(SCM) 3.JENKINS
MONITORING:
1.CLOUD_WATCH
#PLUGINS:
1.S3 PUBLISHER 2.AWS CODE-DEPLOY 3.AWS CODE-DEPLOY 4..ROLE-BASED 5.GIT SERVER 6.GIT AUTHENTICATION 7. ARTIFACR MANAGER OF S3 8.AWS S3 BUCKET CREDENTIALS
#PRE-REQUISISTIES:
1.JDK 2.RUBY 3.Apache HTTP Server 4.IAM USER 5.GIT TOKEN 6.CODE IN ZIP FORMAT (https://github.com/SivaranjanAsokan/Static-HTML-app.zip.git)
CI-CD:
1.Developer made the commit --> Webhook will trigger from jenkins --> Jenkins will Publish the artifact to S3 . 
2.code pipeline will trigger because of bucket Versioning --> Automatically it deploy the code using Code deployment to EC2.
