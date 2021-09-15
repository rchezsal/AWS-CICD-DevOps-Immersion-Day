# AWS-CICD-DevOps-Immersion-Day
This workshop illustrates how you can leverage the AWS developer tools to implement Continuous Integration (CI) and Continuous Deployment (CD) for your application.

You begin by deploying a web-based development environment using the AWS Cloud9 service. This allows you to focus on CI/CD practices without needing a local development environment.

You proceed to deploy a simple network in the AWS cloud using the Cloud Development Kit (CDK). The CDK application deploys EC2 instances to support two different deployment environments. The workshop provides the CDK application so that you can focus on the goal of implementing CI/CD.

With the prerequisites complete, you will start building a pipeline by creating a source code repository using CodeCommit to store the simple Java web application you will use for testing. You will next learn to use CodeBuild to build the Java application source code into a deployable web archive. You will use CodeDeploy to deploy the sample application and, finally, CodePipeline to automate the release process from source code all the way to deployment. You’ll configure these services yourself, as opposed to deploying a template, so that you can maximize your learning.

Your final architecture will look like the following:

   ![Screen Shot 2021-09-13 at 11 07 40 AM](https://user-images.githubusercontent.com/90632882/133303527-b127abf4-c03e-4919-a108-27508eb91a8f.png)

Getting Started

For this workshop you’ll get access to a temporary AWS Account. Follow the steps in this section to login to your AWS Account and start the workshop.

1. To get started navigate to - https://dashboard.eventengine.run/login and enter the Event Hash in the field
![image](https://user-images.githubusercontent.com/90632882/133285722-732ff8bc-0cc0-4c04-96d8-cb5900a656db.png)
Click on Accept Terms & Login

2. Click on Email One-Time OTP (Allow for up to 2 mins to receive the passcode)
![image](https://user-images.githubusercontent.com/90632882/133286863-bea37af2-650f-42d3-b67a-42ed03313b45.png)

3. Provide your email address

![image](https://user-images.githubusercontent.com/90632882/133287030-e9addf59-3216-4fc2-92f2-40cda61e9b43.png)

4. Enter your OTP code

![image](https://user-images.githubusercontent.com/90632882/133287082-c748b86a-4096-45e4-85cb-5d06dc3709a2.png)

5. Click on AWS Console

![image](https://user-images.githubusercontent.com/90632882/133287155-41263613-66fa-43e4-a56a-d3b089219815.png)

6. Click on Open AWS Console

![image](https://user-images.githubusercontent.com/90632882/133287214-6b98541c-ad36-458d-9af8-5ab9aabb7bac.png)

7. In the AWS Console search for CodeCommit in the top search bar and click on it.
![Screen Shot 2021-09-14 at 10 31 00 AM](https://user-images.githubusercontent.com/90632882/133287771-31195dea-0406-4b11-8667-769fc8897d0e.png)
