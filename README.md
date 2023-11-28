# DetectLanguageAPI

Automation Tool: Ready API
Language Scripting: Groovy

Below are the high-level steps performed:
1.	Automation Project from Ready API tool pushed to GitHub repository which has converted to a composite project. 
2.	I have verified running the project using command prompt in local machine and got successful response.
3.	Verified the project on repository by comparing with local machine to make sure all the test scenarios and test cases are correct along with the test data.
4.	Now created an YAML file under Git Hub Actions for running the Project and test cases which are uploaded in the Repository. Below are challenges faced while creating executing YAML file.
    a.	It has some Prerequisites like Ready API tool must be established either by having server with Ready API license or it needs to have set up of self-hosted runner. 
    b.	Need to ensure to have a machine or server (physical or virtual) that meets the system requirements for hosting the runner. This machine should have internet access to communicate with GitHub.
  	
We need to follow steps mentioned in below link to set up of self-hosted runner.
https://github.com/ranam777/DetectLanguageAPI/settings/actions/runners/new
