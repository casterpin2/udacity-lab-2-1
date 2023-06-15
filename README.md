# Overview

Building a CI/CD Pipeline in Udacity Cloud DevOps using Microsoft Azure course

[![Python application test with Github Actions]()

[![Build Status](https://dev.azure.com/tuyennn302090609/ProjectLabUdacity/_build/results?buildId=15&view=results)]

## Project Plan
<TODO: Project Plan

* A link to a Trello board for the project
 https://trello.com/invite/b/cortcw0h/ATTIf52e248fde5e011de1b19227aa8f3d70F8B71A86/udacityproject2
* A link to a spreadsheet that includes the original and final project plan>
https://docs.google.com/spreadsheets/d/1nvfKlratlH5HdoyHMtGiBE5B94lRrCl1xKcTu5zm7Bg/edit?usp=sharing

## Instructions


* Diagram>
<p>
<img src="./evidence/cd-diagram.png" width="100%" />
</p>

Instructions for running the Python project.  How could a user with no context run this project without asking you for any help.  Include screenshots with explicit steps to create that work. Be sure to at least include the following screenshots:

*Azure App Service
<p>
<img src="./evidence/webapp.png" width="100%" />
</p>

* Project cloned into Azure Cloud Shell
<p>
<img src="./evidence/clone code.png" width="100%" />
</p>

* Passing tests that are displayed after running the `make all` command from the `Makefile` and Output of a test run
<p>
<img src="./evidence/make all.png" width="100%" />
</p>
<p>
<img src="./evidence/makeall1.png" width="100%" />
</p>
<p>
<img src="./evidence/makeall2.png" width="100%" />
</p>

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

<p>
<img src="./evidence/CICD.png" width="100%" />
</p>

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
```

<p>
<img src="./evidence/make_predict_azure_app.png" width="100%" />
</p>

* Output of streamed log files from deployed application

<p>
<img src="./evidence/webapplog.png" width="100%" />
</p>

> 

* Locust load testing chart
<p>
<img src="./evidence/locust-chart.png" width="100%" />
</p>

* Locust load testing statics
<p>
<img src="./evidence/locust_report.png" width="100%" />
</p>

## Enhancements

<TODO: A short description of how to improve the project in the future>
- UI design 
- Pipeline improvement
- ML model upgrade
## Demo 

<TODO: Add link Screencast on YouTube>
https://youtu.be/9mTjxxCEV2M

