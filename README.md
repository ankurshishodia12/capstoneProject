# capstoneProject

This is the final Project of Cloud devops Engineer Course.

I have build this project using Rolling Deployment.

To run this project :

1. Launch EC2 instance in the AWS console.
2. Install Jenkins in your EC2 Instance with necessary commands.
3. Install all the necessary plugins in your Jenkins such as Blue Ocean, AWS-pipeline(steps).
4. Set all the credentials for AWS and docker.
5. Create a new pipeline in Blue Ocean and setup github using access token.
6. Install docker,aws-cli,eksctl,kubectl in your EC2 instance.
7. Link for creating cluster and nodes : https://docs.aws.amazon.com/eks/latest/userguide/getting-started-eksctl.html
8. cluster will create EC2 instances.
9. deployment script Link: https://kubernetes.io/docs/concepts/workloads/controllers/deployment/
10. Jenkinsfile test your applications and deploy it using rolling deployment.