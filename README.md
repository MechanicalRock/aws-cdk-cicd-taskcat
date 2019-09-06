# aws-cdk-cicd-taskcat
A project to explore using AWS TaskCat to perform CI/CD for AWS CDK stacks 

#### Project structure #### 
* **templates** folder includes AWS CloudFormation templates
* **ci** folder, includes a TaskCat configuration file (**taskcat.yml**) and an input **parameters file**
    * **taskcat.yml** file should specifiy the template name that needs to be tested, the parameters file, and the tests that TaskCat should run.
    
[CI/CD Pipeline for AWS CloudFormation Templates on the AWS Cloud Using AWS TaskCat](https://aws.amazon.com/quickstart/architecture/cicd-taskcat/ "CI/CD Pipeline for AWS CloudFormation Templates on the AWS Cloud Using AWS TaskCat")

[AWS Quick Starts - Testing](https://aws-quickstart.github.io/testing.html)
