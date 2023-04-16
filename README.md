# node-todo-cicd
# CI/CD Pipeline with Jenkins and Docker on AWS
This project provides a complete example of a CI/CD pipeline for a web application using Jenkins and Docker on Amazon Web Services (AWS).

Prerequisites
Before setting up the project, you must have the following prerequisites installed:

Docker
Jenkins
AWS CLI
AWS account with permissions to create and manage AWS resources
Jenkins plugins: AWS Pipeline, Docker Pipeline, Amazon ECR plugin, Amazon ECS plugin, and Pipeline Utility Steps.
Setup
Follow these steps to set up and configure the project:

Clone the repository to your local machine:
bash
Copy code
git clone https://github.com/shaktibaba123/node-todo-cicd
Create an Amazon ECR repository to store your Docker images.

Create an Amazon ECS cluster to run your Docker containers.

Create an AWS access key and secret access key for Jenkins to access your AWS resources.

**Configure Jenkins:**

Install the required plugins.
Configure Jenkins to use your AWS credentials.
Create a Jenkins pipeline for the project and configure it to use your Docker and AWS resources.
Build and deploy your Docker container to Amazon ECS using the Jenkins pipeline.
Usage
To use the project, trigger a build in Jenkins to initiate the pipeline. The pipeline will build and test the Docker image, and then deploy it to Amazon ECS.

Run these commands:


`sudo apt install nodejs`


`sudo apt install npm`


`npm install`

`node app.js`

You can monitor the pipeline's progress in the Jenkins console, and view the deployed application on the public IP address of your Amazon ECS cluster.

**Troubleshooting**
If you encounter any issues during setup or deployment, check the Jenkins console for error messages, and consult the official documentation for the tools and technologies used in the project.
![Screenshot (29)](https://user-images.githubusercontent.com/73735284/232285371-6a6c6d31-fdb9-4867-bf74-2f137c81beb3.png)

![![Screenshot (30)](https://user-images.githubusercontent.com/73735284/232286000-21c033d8-1bdf-4a16-ad34-9b7a3927d5f5.png)
Screenshot (31)](https://user-images.githubusercontent.com/73735284/232285417-5c39928b-fc8a-455d-81e2-4df9a2f1f534.png)
884e-bd046c4b2bf9.png)

**Future Improvements**
Potential areas for future improvement include:

Adding automated testing to the pipeline.
Integrating additional AWS services, such as Amazon S3 for storage or AWS Lambda for serverless computing.
Implementing more advanced deployment strategies, such as blue/green deployments or canary releases.

**Contributors**
Shakti Anand Jha 



