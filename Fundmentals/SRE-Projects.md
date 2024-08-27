# SRE Projects worked in my Journey
## Nike Experience
### Production Mobile application Management
- Manage Mobile applications reliability and availability using New Relic observability tool
- Collabrate with the application development teams (Frontend, backend services) on functional issues, cosmetic issues, capacity issues
- Bring the issues in application teams stand up, explain the impact, how the issue impacting the customer experience etc.. and priotize the issue with the help of product owner
- Engage with Technical lead on new features, discuss on arichecture, understand about the new change flow, value bring to the customer, also look into any failure points in the flow and finally create a monitoring dashboard, alerts to capture the new feature and monitoring during the development phase and bring issues to dev team attention to resolve the same before get into production
- Collabrate with Release management team on bi-weekly releases as well, new feature promotion to production through Apple and andriod app stores in a rolling deployment, also monitor the application during the rolling deployment period, check any new issues come or increase impact on existing increased etc.. then perform an impact analysis on issue, then discuss with Production owner, release managment team and take a next steps on release change to production
#### Tools used in Mobile application management 
- InteliJ - Integrated Development Environment  
- Github - Code repository 
- Jira - Issue and Project Tracking
- New Relic, Splunk Observability tool 
- AWS - Public cloud services EC2, SQS, RDS database
- Jenkins - CI/CD Pipeline to manage the SDLC of Service and promote code all the way to production
- Postman - Test the Endpoints, also check the response during the trouble shoot of issue
- Service Now - To Manage incidents and problems reported by Customers/End users
### Production web applications management 
- Instrumented the Services by including observability libaries part of code as a dependency, install the agent on a platform application runs
- Create a dashboards to capture and monitor the services by collecting the metrics (response time, traffic, errors, infrastrucutre related metrics cpu, memory etc..) using the golden signals Throughput, latency, error rate, saturation
- Create an alerts to proactively monitor the service, react and mitigate the issue before impact the customer experince 
- Define and Implement the SLO's and CUJ to Monitor the service reliability and high availability, use these a measurement to control the deployment velocity or negotiate with dev team on new feature vs Problem mitigation
- Collabrate with various teams (Dev, product, L1 Support teams) to identity various issues, work on ways to reduce the MTTR, MTTD, MTTF
- Automate the Monitoring using the Terrform 
- Perform a Chaos engineering game days to check the system failures, resiliency 
- Worked with devlopment teams to measure and monitor of the service performance and capacity to perform the Capacity planning of the resources to support the product lunches, sale days
- Deploy the micro services to dev and prod environments using the CI/CD Pipeline
- Created a Play books and integrated with Monitoring tool
- Set up and run the Synthetic tests of Endpoints using CatchPoint
### Tools used in Web application managment 
- Jira, bitbucket, github, Jenkins, SignalFx, New Relics, Catch Point, Splunk, IntelliJ, AWS (SQS, EC2, Postgresql,DynamoDB)
## BP Experience 
### Managed the Server less application perform the Pricing updates, devices used at gas station
- Had a design thinking session with customer to understand the application at high level, document the various tasks can be performed to incorporate an observability at platform level
- Perform the Operation readiness review of the service to get to know about the services maturity level 
- Identify the Observability gaps and mitigate the same
- Standarize the Access managment of the service by introduce the best practices through IAM (least priviliged access)
- Design and create the Curated dashboard to bring the E2E flow of the request journey start from the batch job and all the way to update the Price at fuel station
- Introduced the Tracing into services using the AWS X-ray, Open Telemetery libaries 
- Integrated the Services Slack and Teams to automatically notify the teams of failures in services, as well deployments 
- Analyze the service logs, identity the various failures, impact of each failure and work with dev team to resolve the issues
- Educate the dev teams and patern teams on use of observability tools as well incoporate the best practices of manage servic access through IAM, Standarize the dashboard, alert and playbook templates across the team
- Explore the various monitoring tools (Azure Monitoring, AWS X-ray, Cloud Watch, )
### Tools
- Azure Devops -- Code reposity, code deployment, project managment
- Cloud Watch, X -ray -- Monitoring tools
- Lambda, Step function, SQS, DynamoDB
## Discovery Finance Services Experince 
- Change/Release Management using Trident Pipelines 
- Manage the Infrastructure runs on OpenShift
- Implemented and managed the Services observability using the Instana and Kibana tools
- Dashboard, alert creation to measure the servcies as well user journey reliability, availability by measuring the Throughput, Error rate, response time of the service end points 
- Implemented a proactive monitoring using Instana tool on applicaiton, platform
- Managed the Operations, Configuration Managment activites, such as onboard a new service all the way from code repository, NexusIq, SonarQube, database provision, API onboarding etc..
- TLS Certify life cycle management for services, pipeline
- Produciton release managment using the Pipeline
- Collabarate with Product owners, dev team, dependency teams, QA team to take the change successful to produciton
- Created a Run books, play books to manage the Service life cycle 
#### Tools
- Postman, VS code, Instana, Kibana(ELK), Trident Pipeline, Code and Image scanning tools(NexusIq, SonarQube), Jira, ServiceNow 