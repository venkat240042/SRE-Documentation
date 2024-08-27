- What is SRE? Site reliability Engineering is an approach for operations that ensures continusoly delivered applications run efficently and reliability by using software engineering and automation
- Site reliability Engineers operats services that sustain Service level objectives(SLO). They infuse automation, devopos principals, proactive monitoring and rigious trouble shooting for critical workloads <br>
- SRE's
  - Associate SRE's 
    - Focus on receiving alerts  and troubleshooting
    - Automate to ensure problems do not repeative 
  - Profession SRE's
    - Required a leadership skills to ensure the teams are set up for success
    - Operate well and are effective and productive
- How SRE manage Tradeoff between change, velocity and reliability
  - SRE Uses case error budge to manage the velocity and reliability of a system/application
  - Error budget is 100 - % availability, in generally  evalute the error budget over a period of month, however you can use for 29 days, sprint lenght (weekly, two week etc..)
  - SLI and SLO are also part of elements of error budget
  - Service level Indicator(SLI): Measurments of the service level provide by systems - such as availability, latency, throughput etc..
  - Service Level Object(SLO): Defined target level of service, mesasured using one or multiple SLI's
  - Attributes that determines Reliability
    - Latency
    - Error rate
    - Throughput
    - Availability
    - Durability
    - Correctness 
- **Problem Statement**: User wants to complete a secure on-line transaction to purchase an item from a retailer that needs to be delivered by Friday. To avoid the expedite fee, the transaction will need to be submitted before the 12 PM Eastern Standard Time (EST) deadline on Wednesday to successfully process with enough time to ensure the Friday delivery due date. <br>
<br>
It’s Wednesday, at 11:55 AM EST, and the transaction is in the cart. When you click the Submit button, a window opens with a message that reads “Transaction Failed.” 

Now what?
- Refresh the cart and click submit again, still no success

What Could be the possible reasons for the issues?
let's assume user access application through broweser, actual application is a standard 3 tier application(web server, app server and database)

- Failure could occur either send request to application or coming back response from the application, mean in/out flow 
- Possible componets part of the request journey
  - web browser
  - Internet
  - Load balancer
  - web server
  - app server
  - database server 
  - storage
- Apply Software Engineering Principles to drive Reliability 
  - Value of Test driven development
  - Value of Test Automation
  - Value of Chaos Engineering
  - Key Reliability Architecture Patterns  

 
