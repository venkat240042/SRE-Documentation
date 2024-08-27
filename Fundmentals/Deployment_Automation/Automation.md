## Design Non-Disruptive Deployment
### What advantage SRE's gets with Continus Delivery
- Removes the need for manual intervention during the production deployment
- Automate the regression testing
- Expedite the time to market the product to client from Months to weeks and days
### What should deployment team to implement to manage the non-disruptive deployment?
- Implement the Continues delivery pipeline using the continus delivery tools such as Jenkins, Gitlab, Azure pipelines, AWS Code deployment and more
- Automate the monitoring and outage notification
- Create a fine tune the runbooks to troubleshoot the issues during outage
- Capture and maintain the applicaiton and infrastucture logs using the centralized logging solutions/tools, so that we can query the logs to identify the root cause for the issues, this would help to reduce the MTTD and MTTR issues/outages
- Surafce the SLA reports cleary breakdown by daily, weekly and monthly
### Benefits of Automated delivery pipeline
- Eliminate the need for expensive and error-prone manual tasks
- Quicker and more productivity of new team member
- Early detection of the code not fit for delivery
- Visability and confindence with code quality and efficency improve as testing progress through successive stages
### Different peaces part of Continues delivery pipeline
- Continues Integration, like test a small chuncks of code as developers work on small futures and bugs on future branches, this gives a quick feedback on changes 
- Continus building of code, after developer checkout the code in coderepo, pull those changes and build immediately, so that we get to know any build issues, such as missing a dependency or un-supported depedencies, code errros etc.. makes build failed, this helps to quickly check back issues and fix the same
- Continus testing (automate testing): Automate the testing of code changes after build by deploy the code in a dev/test environment and run a unit test cases, integration tests etc. So that we can get an immediate feedback on our changes rather than wait until someone from testing team run a test and get back to developer
### Continus deployment approaches/ pattern to minimize or avoid the system downtime, while upgrade or deploy a new changes of an application/system?
- Canry deployment - Rollout changes to small subset of users 
- Blue/green deployment - Create a two similar production environments, both environments infrastrucure exists, however sends a users traffic to new environment after successful deployment. In this approach endusers shouldn't experince any downtime during deployment, however it's costly because to manage more infrastructure 
- Standard deployment - Deploy the latest changes on an existing infrastructure, due to this end users experince an outage during deployment

## Infrastructure as a code (IaC): 
IaC is an DevOps Practice to automate the provision of infrastructure using high-level descriptive language
### Benfits of IaC:
- Faster time to Production and market: IaC automation speed up the process to provision infrastrcture for various environment(dev, test, stage, prod)
- Improved Consistency and less configuration drifts
- Faster more efficent development 
- Protection aganist churn
- Lower costs and improve ROI
### Tools or Technologies to Implement IaC
- Terraform 
- Ansible
- Helm
- OpenShift Operator

## SRE Responbilities to CI/CD Pipeline
- 
