# AWS-CICD-DevOps-Immersion-Day
In this workshop you'll learn how to build a CI/CD pipeline (AWS CodePipeline) to develop a web-based application, containerize it, and deploy it on a Amazon EKS cluster. You'll use the blue/green method to deploy application and review the switchover using Application Load Balancer (ALB) Target-groups. You will spawn this infrastructure using AWS Cloud Development Kit (CDK), enabling you to reproduce the environment when needed, in relatively fewer lines of code.

Getting Started
For this workshop you’ll get access to a temporary AWS Account already pre-configured with Amazon SageMaker Studio. Follow the steps in this section to login to your AWS Account and download the workshop material.

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
