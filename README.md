Java Web App Deployment with AWS CI/CD
Welcome to this project combining Java web app development and AWS CI/CD tools!


Table of Contents
[Introduction](https://github.com/itsnextwork/nextwork-web-project#introduction) 

[Technologies](https://github.com/itsnextwork/nextwork-web-project#technologies)

[Setup](https://github.com/itsnextwork/nextwork-web-project#setup)

[Contact](https://github.com/itsnextwork/nextwork-web-project#contact)

[Conclusion](https://github.com/itsnextwork/nextwork-web-project#introduction)

Introduction
This project is used for an introduction to creating and deploying a Java-based web app using AWS, especially their CI/CD tools.

The deployment pipeline I'm building around the Java web app in this repository is invisible to the end-user, but makes a big impact by automating the software release processes.

I'm doing this project to learn more about CI/CD and get hands on experience in automating the flow from developing code to deployed web app.
This fits into my career goals because I want to become a DevOps engineer this year!

Technologies
Here’s what I’m using for this project:

Amazon EC2: I'm developing my web app on Amazon EC2 virtual servers, so that software development and deployment happens entirely on the cloud.
Key pairs, SSH connections, Git, Maven and Java.
VSCode: For my IDE, I chose Visual Studio Code. It connects directly to my development EC2 instance, making it easy to edit code and manage files in the cloud.
GitHub: All my web app code is stored and versioned in this GitHub repository.
[COMING SOON] AWS CodeArtifact: Once it's rolled out, CodeArtifact will store my artifacts and dependencies, which is great for high availability and speeding up my project's build process.
[COMING SOON] AWS CodeBuild: Once it's rolled out, CodeBuild will take over my build process. It'll compile the source code, run tests, and produce ready-to-deploy software packages automatically.
[COMING SOON] AWS CodeDeploy: Once it's rolled out, CodeDeploy will automate my deployment process across EC2 instances.
[COMING SOON] AWS CodePipeline: Once it's rolled out, CodePipeline will automate the entire process from GitHub to CodeDeploy, integrating build, test, and deployment steps into one efficient workflow.

Setup
To get this project up and running on your local machine, follow these steps:

Clone the repository:
git clone https://github.com/yourusername/nextwork-web-project.git
Navigate to the project directory:
cd nextwork-web-project
Install dependencies:

mvn install

LinkedIn
www.linkedin.com/in/mahesh-alladi-582716290

