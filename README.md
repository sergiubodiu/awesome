# Awesome

😎 A curated list of **awesome resources** for techies. The scope of this particular list is limited to things that infrastructure developers (Engineers, DevOps Practitioners, etc.) are likely to find useful. We love all the free services out there, this is my subjective list on topics that I'm interested.


# Table of Contents
  * [Best Practices for Onboarding](#onboarding)
  * [Engineering Career Development](#engineering-career-development)
  * [Major Cloud Providers' Always-Free Limits](#major-cloud-providers)
  * [Site Reliability Engineering](#site-reliability-engineering)
  * [Popular Observability Tools](#popular-observability-tools)
  * [Tools for Teams and Collaboration](#tools-for-teams-and-collaboration)

## Onboarding

* [Docs](https://github.com/greenelab/onboarding)
* [Engineer Onboarding Timeline & Expectations](https://docs.mattermost.com/process/engineer-expectations.html)
* [Training](https://docs.mattermost.com/process/training.html)
* [7 Proven Best Practices for Onboarding a New Engineer](https://blog.newrelic.com/culture/engineer-onboarding-best-practices/) 
* [**Experiences**](https://www.quora.com/What-is-the-onboarding-process-like-for-new-engineers-at-Quora)
* [How We Onboard New Engineers at Zapier](https://zapier.com/engineering/engineer-onboarding/)

### Principles
* [Engineering Values: A letter to the Medium Engineering team](https://medium.engineering/engineering-values-7143c0db0bd6)
* [Build strong values to build great products](https://blog.intercom.com/the-engineering-values-we-live-by/)
* [Guiding Principles for Imgur Engineers](https://blog.imgur.com/2018/02/13/guiding-principles-for-imgur-engineers/)
* [Khan Academy's Engineering Principles](http://engineering.khanacademy.org/posts/engineering-principles.htm)
    * [SLIDES Engineering Principles](https://docs.google.com/presentation/d/1ZQ-HTuH38L8sf4ZObfJNlESpzYIPAP6QFe30qOqE8DA/view)
* [Gusto's Engineering Principles and Values](https://engineering.gusto.com/our-engineering-values-and-principles/)
    * [PDF Engineering Principles and Values](https://app.gusto.com/static/engineering-principles-and-values.pdf)
* [Defining Culture: Engineering Principles](https://blog.navapbc.com/defining-engineering-culture-engineering-principles-558d2b4c5950)
* [AI at Google: our principles](https://blog.google/topics/ai/ai-principles/)
* [An update on our Engineering Principles](https://medium.com/@SkyscannerEng/an-update-on-our-engineering-principles-80405a96383a)
* [Why engineering principles matter](https://github.com/Skyscanner/engineering-principles)
* [How to build a platform team now! the secrets to successful engineering](https://hackernoon.com/how-to-build-a-platform-team-now-the-secrets-to-successful-engineering-8a9b6a4d2c8)

## Engineering Career Development
* [Kickstarter Engineering Ladder](https://gist.github.com/jamtur01/aef437a79fee5a9cefdc)
* [Dropbox Engineering Career Framework](https://dropbox.github.io/dbx-career-framework/overview.html)
* [Engineering Career Development](https://about.gitlab.com/handbook/engineering/career-development/)
* [Etsy Engineering Career Ladder](https://etsy.github.io/Etsy-Engineering-Career-Ladder/)

### Articles
* [So you want to Onboard a DevOps Practitioner](https://github.com/actionjack/so-you-want-to-onboard-a-devops-engineer) - Guidance on how to make your environment easier to onboard for Web Ops Engineers, SRE's and DevOps Practitioners.
* [The Ultimate Guide to Onboarding New Developers: Industry Best Practices and How to Plan the First 90 Days](https://codesubmit.io/blog/guide-to-onboarding-developers/) - Onboarding new hires requires taking their perspective into account and designing the best possible experience to get your new teammate assimilated and contributing as quickly as possible. 
* [Defining Principles for Software Engineering](https://medium.com/the-plain-programmer/defining-principles-for-software-engineering-e88c069a0446) - Address how to define the principles that drive software engineering efforts.
* [Principles of Successful Software Engineering Teams](https://blog.brunomiranda.com/principles-of-successful-software-engineering-teams-41a65bfd56b3) - Highlight important principles of a successful team's philosophy.
* [Key Principles That Lead to High-Performing Engineering Teams](https://www.hugeinc.com/articles/key-principles-that-lead-to-high-performing-engineering-teams) - How to build a culture that consistently delivers a quality product, shortens lead times, and improves continuously.
* [5 Principles on What Makes a Great Agile Development Team](http://blogs.starcio.com/2015/04/principles-great-agile-development-team.html) - Suggest a short list of what makes a well executing IT team great.

**[⬆️ Back to Top](#table-of-contents)**

## Major Cloud Providers

  * [Google Cloud Platform](https://cloud.google.com)
    * App Engine - 28 frontend instance hours per day, nine backend instance hours per day
    * Cloud Firestore - 1GB storage, 50,000 reads, 20,000 writes, 20,000 deletes per day
    * Compute Engine - 1 non-preemptible e2-micro, 30GB HDD, 5GB snapshot storage (restricted to certain regions), 1 GB network egress from North America to all region destinations (excluding China and Australia) per month
    * Cloud Storage - 5GB, 1GB network egress
    * Cloud Shell - Web-based Linux shell/primary IDE with 5GB of persistent storage. 60 hours limit per week
    * Cloud Pub/Sub - 10GB of messages per month
    * Cloud Functions - 2 million invocations per month (includes both background and HTTP invocations)
    * Cloud Run - 2 million requests per month, 360,000 GB-seconds memory, 180,000 vCPU-seconds of compute time, 1 GB network egress from North America per month
    * Google Kubernetes Engine - No cluster management fee for one zonal cluster. Each user node is charged at standard Compute Engine pricing
    * BigQuery - 1 TB of querying per month, 10 GB of storage each month
    * Cloud Build - 120 build-minutes per day
    * [Google Colab](https://colab.research.google.com/) - Free Jupyter Notebooks development environment.
    * Full, detailed list - https://cloud.google.com/free

  * [Amazon Web Services](https://aws.amazon.com)
    * [CloudFront](https://aws.amazon.com/cloudfront/) - 1TB egress per month and 2M Function invocations per month
    * [CloudWatch](https://aws.amazon.com/cloudwatch/) - 10 custom metrics and ten alarms
    * [CodeBuild](https://aws.amazon.com/codebuild/) - 100min of build time per month
    * [CodeCommit](https://aws.amazon.com/codecommit/) - 5 active users,50GB storage, and 10000 requests per month
    * [CodePipeline](https://aws.amazon.com/codepipeline/) - 1 active pipeline per month
    * [DynamoDB](https://aws.amazon.com/dynamodb/) - 25GB NoSQL DB
    * [EC2](https://aws.amazon.com/ec2/) - 750 hours per month of t2.micro or t3.micro(12mo). 100GB egress per month
    * [EBS](https://aws.amazon.com/ebs/) - 30GB per month of General Purpose (SSD) or Magnetic(12mo)
    * [Elastic Load Balancing](https://aws.amazon.com/elasticloadbalancing/) - 750 hours per month(12mo)
    * [RDS](https://aws.amazon.com/rds/) - 750 hours per month of db.t2.micro, db.t3.micro, or db.t4g.micro, 20GB of General Purpose (SSD) storage, 20GB of storage backups(12 mo)
    * [S3](https://aws.amazon.com/s3/) - 5GB Standard object storage, 20K Get requests and 2K Put requests(12 mo)
    * [Glacier](https://aws.amazon.com/glacier/) - 10GB long-term object storage
    * [Lambda](https://aws.amazon.com/lambda/) - 1 million requests per month
    * [SNS](https://aws.amazon.com/sns/) - 1 million publishes per month
    * [SES](https://aws.amazon.com/ses/) - 3.000 messages per month (12mo)
    * [SQS](https://aws.amazon.com/sqs/) - 1 million messaging queue requests
    * Full, detailed list - https://aws.amazon.com/free/

  * [Microsoft Azure](https://azure.microsoft.com)
    * [Virtual Machines](https://azure.microsoft.com/services/virtual-machines/) - 1 B1S Linux VM, 1 B1S Windows VM (12mo)
    * [App Service](https://azure.microsoft.com/services/app-service/) - 10 web, mobile, or API apps (60 CPU minutes/day)
    * [Functions](https://azure.microsoft.com/services/functions/) - 1 million requests per month
    * [DevTest Labs](https://azure.microsoft.com/services/devtest-lab/) - Enable fast, easy, and lean dev-test environments
    * [Active Directory](https://azure.microsoft.com/services/active-directory/) - 500,000 objects
    * [Active Directory B2C](https://azure.microsoft.com/services/active-directory/external-identities/b2c/) - 50,000 monthly stored users
    * [Azure DevOps](https://azure.microsoft.com/services/devops/) - 5 active users, unlimited private Git repos
    * [Azure Pipelines](https://azure.microsoft.com/services/devops/pipelines/) - 10 free parallel jobs with unlimited minutes for open source for Linux, macOS, and Windows
    * [Microsoft IoT Hub](https://azure.microsoft.com/services/iot-hub/) - 8,000 messages per day
    * [Load Balancer](https://azure.microsoft.com/services/load-balancer/) - 1 free public load-balanced IP (VIP)
    * [Notification Hubs](https://azure.microsoft.com/services/notification-hubs/) - 1 million push notifications
    * [Bandwidth](https://azure.microsoft.com/pricing/details/bandwidth/) - 15GB Inbound(12mo) & 5GB egress per month
    * [Cosmos DB](https://azure.microsoft.com/services/cosmos-db/) - 25GB storage and 1000 RUs of provisioned throughput
    * [Static Web Apps](https://azure.microsoft.com/pricing/details/app-service/static/) - Build, deploy, and host static apps and serverless functions with free SSL, Authentication/Authorization, and custom domains
    * [Storage](https://azure.microsoft.com/services/storage/) - 5GB LRS File or Blob storage (12mo)
    * [Cognitive Services](https://azure.microsoft.com/services/cognitive-services/) - AI/ML APIs (Computer Vision, Translator, Face detection, Bots, etc) with free tier including limited transactions
    * [Cognitive Search](https://azure.microsoft.com/services/search/#features) - AI-based search and indexation service, free for 10,000 documents
    * [Azure Kubernetes Service](https://azure.microsoft.com/services/kubernetes-service/) - Managed Kubernetes service, free cluster management
    * [Event Grid](https://azure.microsoft.com/services/event-grid/) - 100K ops/month
    * Full, detailed list - https://azure.microsoft.com/free/

  * [Oracle Cloud](https://www.oracle.com/cloud/)
    * Compute
       - 2 AMD-based Compute VMs with 1/8 OCPU and 1 GB memory each
       - 4 Arm-based Ampere A1 cores and 24 GB of memory usable as one VM or up to 4 VMs
       - Instances will be reclaimed when [deemed idle](https://docs.oracle.com/en-us/iaas/Content/FreeTier/freetier_topic-Always_Free_Resources.htm#compute__idleinstances)
    * Block Volume - 2 volumes, 200 GB total (used for compute)
    * Object Storage - 10 GB
    * Load balancer - 1 instance with 10 Mbps
    * Databases - 2 DBs, 20 GB each
    * Monitoring - 500 million ingestion data points, 1 billion retrieval datapoints
    * Bandwidth - 10 TB egress per month, speed limited to 50 Mbps on x64-based VM, 500 Mbps * core count on ARM-based VM
    * Public IP - 2 IPv4 for VMs, 1 IPv4 for load balancer
    * Notifications - 1 million delivery options per month, 1000 emails sent per month
    * Full, detailed list - https://www.oracle.com/cloud/free/

  * [IBM Cloud](https://www.ibm.com/cloud/free/)
    * Cloudant database - 1 GB of data storage
    * Db2 database - 100MB of data storage
    * API Connect - 50,000 API calls per month
    * Availability Monitoring - 3 million data points per month
    * Log Analysis - 500MB of daily log
    * Full, detailed list - https://www.ibm.com/cloud/free/

  * [Cloudflare](https://www.cloudflare.com/)
    * [Application Services](https://www.cloudflare.com/plans/) - Free DNS for an unlimited number of domains, DDoS Protection, CDN along with free SSL, Firewall rules and page rules,  WAF, Bot Mitigation, Free Unmetered Rate Limiting - 1 rule per domain, Analytics, Email forwarding
    * [Zero Trust & SASE](https://www.cloudflare.com/plans/zero-trust-services/) - Up to 50 Users, 24 hours of activity logging, three network locations
    * [Cloudflare Tunnel](https://www.cloudflare.com/products/tunnel/) -  You can expose locally running HTTP port over a tunnel to a random subdomain on trycloudflare.com use [Quick Tunnels](https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/do-more-with-tunnels/trycloudflare/), No account required. More features (TCP tunnel, Load balancing, VPN) in [Zero Trust](https://www.cloudflare.com/products/zero-trust/) Free Plan.
    * [Workers](https://developers.cloudflare.com/workers/) - Deploy serverless code for free on Cloudflare's global network-100k daily requests.
    * [Workers KV](https://developers.cloudflare.com/kv) - 100k read requests per day, 1000 write requests per day, 1000 delete requests per day, 1000 list requests per day, 1 GB stored data
    * [R2](https://developers.cloudflare.com/r2/) - 10 GB per month, 1 million Class A operations per month, 10 million Class B operations per month
    * [D1](https://developers.cloudflare.com/d1/) - 5 million rows read per day, 100k rows written per day, 1 GB storage
    * [Pages](https://developers.cloudflare.com/pages/) - Develop and deploy your web apps on Cloudflare's fast, secure global network. Five hundred monthly builds, 100 custom domains, Integrated SSL, unlimited accessible seats, unlimited preview deployments, and full-stack capability via Cloudflare Workers integration.
    * [Queues](https://developers.cloudflare.com/queues/) - 1 million operations per month
    * [TURN](https://developers.cloudflare.com/calls/turn/) - 1TB of free (outgoing) traffic per month.

  * [Zoho](https://www.zoho.com) - Started as an e-mail provider but now provides a suite of services, some of which have free plans. List of services having free plans :
    * [Catalyst by Zoho](https://catalyst.zoho.com) -  PaaS/full-stack cloud platform with a generous [free tier](https://catalyst.zoho.com/free-tier.html)
    * [Email](https://zoho.com/mail) Free for 5 users. 5GB/user & 25 MB attachment limit, one domain.
    * [Zoho Assist](https://www.zoho.com/assist) - Zoho Assist's forever free plan includes one concurrent remote support license and Access to 5 unattended computer licenses for unlimited duration available for both professional and personnel use.
    * [Sprints](https://zoho.com/sprints) Free for 5 users,5 Projects & 500MB storage.
    * [Docs](https://zoho.com/docs) - Free for 5 users with 1 GB upload limit & 5GB storage. Zoho Office Suite (Writer, Sheets & Show) comes bundled.
    * [Projects](https://zoho.com/projects) - Free for 3 users, 2 projects & 10 MB attachment limit. The same plan applies to [Bugtracker](https://zoho.com/bugtracker).
    * [Connect](https://zoho.com/connect) - Team Collaboration free for 25 users with three groups, three custom apps, 3 Boards, 3 Manuals, and 10 Integrations along with channels, events & forums.
    * [Meeting](https://zoho.com/meeting) - Meetings with upto 3 meeting participants & 10 Webinar attendees.
    * [Vault](https://zoho.com/vault) - Password Management is accessible for Individuals.
    * [Showtime](https://zoho.com/showtime) - Yet another Meeting software for training for a remote session of up to 5 attendees.
    * [Notebook](https://zoho.com/notebook) - A free alternative to Evernote.
    * [Wiki](https://zoho.com/wiki) - Free for three users with 50 MB storage, unlimited pages, zip backups, RSS & Atom feed, access controls & customizable CSS.
    * [Subscriptions](https://zoho.com/subscriptions) - Recurring Billing management free for 20 customers/subscriptions & 1 user with all the payment hosting done by Zoho. The last 40 subscription metrics are stored
    * [Checkout](https://zoho.com/checkout) - Product Billing management with 3 pages & up to 50 payments.
    * [Desk](https://zoho.com/desk) - Customer Support management with three agents, private knowledge base, and email tickets. Integrates with [Assist](https://zoho.com/assist) for one remote technician & 5 unattended computers.
    * [Cliq](https://zoho.com/cliq) - Team chat software with 100 GB storage, unlimited users, 100 users per channel & SSO.
    * [Campaigns](https://zoho.com/campaigns) - Email Marketing
    * [Forms](https://zoho.com/forms) - Form Creator
    * [Sign](https://zoho.com/sign) - Paperless Signatures
    * [Surveys](https://zoho.com/surveys) - Online Surveys
    * [Bookings](https://zoho.com/bookings) - Appointment Scheduling


### Cloud  Projects

Title | Description | Author 
------|-------------|--------|

[AWS Hands On Tutorials](https://aws.amazon.com/getting-started/hands-on/?getting-started-all.sort-by=item.additionalFields.sortOrder&getting-started-all.sort-order=asc&awsf.getting-started-category=*all&awsf.getting-started-level=*all&awsf.getting-started-content-type=*all) |  Get started with step-by-step tutorials to launch your first application | AWS |
[AWS Architecture Center](https://aws.amazon.com/architecture/) | The AWS Architecture Center provides reference architecture diagrams, vetted architecture solutions, Well-Architected best practices, patterns, icons, and more. | AWS
[DevOps the Hardway - AWS](https://github.com/AdminTurnedDevOps/DevOps-The-Hard-Way-AWS) | This tutorial contains a full, real-world solution for setting up an environment that is using DevOps technologies and practices for deploying apps and cloud services/cloud infrastructure to AWS. | [Mike Levan](https://michaellevan.net/)
[Azure Citadel](https://www.azurecitadel.com/) | Many hands-on labs with Azure | [Azure Citadel](https://www.azurecitadel.com/) 
[Azure Architecture Center](https://docs.microsoft.com/en-us/azure/architecture/browse/) |   Architecture diagrams and technology descriptions for reference architectures, real world examples of cloud architectures, and solution ideas for common workloads on Azure.   | Microsoft
[DevOps the Hardway - Azure](https://github.com/thomast1906/DevOps-The-Hard-Way-Azure) | This tutorial contains a full, real-world solution for setting up an environment that is using DevOps technologies and practices for deploying apps and cloud services/cloud infrastructure to Azure. | [Thomas Thorton](https://thomasthornton.cloud/)
[Deploy an App to Azure with ARM](https://github.com/SoniaConti/ContosoFinance-Demo) | ARM is an IaC tool used with Azure | [Sonia Conti](https://github.com/SoniaConti/ContosoFinance-Demo)

[GCP Architecture Center](https://cloud.google.com/architecture)|   Architectures, diagrams, design patterns, guidance, and best practices for building or migrating your workloads on Google Cloud.  | GCP
[GCP Codelabs](https://codelabs.developers.google.com/cloud) |  Learn about Google Cloud Platform by completing codelabs and coding challenges! | GCP
[Google Skills](https://www.skills.google) | Choose your path, build your skills, and validate your GCP knowledge. | GCP
[DevOps-Exercises](https://github.com/bregman-arie/devops-exercises) | This repo [devops-exercises](https://github.com/bregman-arie/devops-exercises) contains questions and exercises on various technical topics related to DevOps and SRE | [Arie Bregman](https://github.com/bregman-arie)

**[⬆️ Back to Top](#table-of-contents)**

## DevSecOps
Read Phoenix Project, Unicorn Project, DevOps Handbook, Google SRE books (there are a few). This should give you a good idea of what you should be doing.

Keep in mind the saying "There is no such thing as a junior DevOps". This basically resumes to the idea that you will be more effective in any DevOps role the more you will understand general concepts, tools and methodologies in a modern IT world. roadmap.sh/devops does a good job to make a comprehensive list of those various concepts but take it with a grain of salt. 

![DevSecOps diagram](https://www.plantuml.com/plantuml/png/PLFRRk8m47tdA_oqQiNo3sM1tI8j5v6gxrDx2ACwTZGUKsM_VYSED9I-cNCv9pCsJqc0fQ7W6cWdKxF4SuLsrwR9T6f-PVBEG70Ajpvs3GPH_4AKqo86eP1ZJcOT16i6eHWATUVPWzYJsK206WjOt4th2OB58Xb_6gkv77swno4xacyeQwAZiVg0TVOWaJjZRolC4WJKE6OF20RBNTlRHwpbA6Y_OjP3IdGaUwqoQuT1I3hpmyojnPHk9Yo-UPQJdaVB04McVoFocQAbPtB8gS0LMaOnhv2zf78FpzKcJMOpir0aCnPinpM4QzfCoIKcgeVZokMXk2Z_P79b4psrZvviD-3nZ1m-cHU4nhp4DlfO4oOTxO2fZI7H6taIXOhi5Nn6KmdtyWsqBOLQ2RD5-OZyFgwv5y_twzlDA5Hue81yTQY_F28-WaNpiDYk7ulm6TXXwDaA-KmMTScOJiCKODzHp3o0xn8DNLKyoWSmpfPur7ntc_zGBRTzgjcz9Gs3Cb4tV6B_jCe-DZ6GH5Pz8Nv7nf383kb_Otq_IOKsiyRernyZD-F2LsULtAYrVhtQ35CTnZTRjFCiKQteb4dHvvxuchvZUy8aN3m_1yFelzmHQiVky3Xvmk0kV-l_)

**[⬆️ Back to Top](#table-of-contents)**

## Site Reliability Engineering

In Site Reliability Engineering (SRE) practices, the major responsibilities of software engineering and operations are to build and improve service reliability and to do so in the most efficient, toil-free way. To improve service reliability, SRE teams generally proactively monitor their service(s) to identify areas that need closer inspection and potential engineering time to improve.  

Monitoring is a critical part of SRE practices. It’s often the starting point for managing the overall system and services reliability. With dashboards of reports and charts, the team can keep an ‘eye out’ for anything unusual.  With aggregated data updating dashboards in real-time, one can determine if the 4 golden signals are all green. Monitoring data can be tracked through code pushest to see how each release affects your service.

### SRE Golden Signals

SRE’s Golden Signals are four key metrics used to monitor the health of your service and underlying systems. We will explain what they are, and how they can help you improve service performance.

What are the Four Golden Signals?
* Latency: the time it takes to serve a request.
* Traffic: the total number of requests across the network.
* Errors: the number of requests that fail.
* Saturation: the load on your network and servers.

### What is Monitoring and Observability?

Monitoring and observability are critical practices in DevOps that help teams understand the health, performance, and behavior of their systems in production. While often used interchangeably, they serve complementary but distinct purposes.

**Monitoring** is the practice of collecting, aggregating, and analyzing predefined metrics and logs to detect known failure modes and performance issues. It answers the question: "Is the system working as expected?"

**Observability** goes beyond monitoring by providing deep insights into system behavior through comprehensive instrumentation. It enables teams to ask arbitrary questions about their system and debug unknown issues. Observability answers: "Why is the system behaving this way?"

### The Three Pillars of Observability

Modern observability is built on three fundamental pillars:

#### Metrics
Numerical measurements collected over time that represent the health and performance of your systems. Examples include CPU usage, memory consumption, request rates, and error rates. Metrics provide a high-level view of system behavior and are excellent for alerting.

#### Logs
Detailed, timestamped records of discrete events that happen in your system. Logs provide context about what happened at a specific point in time and are invaluable for debugging issues and understanding application behavior.

#### Traces
Distributed traces track requests as they flow through various services in a microservices architecture. They help identify bottlenecks and understand dependencies between services, showing the complete journey of a request through your system.

### Monitoring SRE’s Golden Signals 
The dilemma of complex distributed systems is that despite being complex, they should be easy to monitor. However, in a complex microservice architecture, it's difficult to identify the root cause of an issue as different technologies use different components that require expert oversight. 

The golden signals can help consolidate the data received from your many microservices into the most important factors. By reflecting on the most foundational aspects of your service, the four golden signals are the basic building blocks of an effective monitoring strategy. They improve the time to detect (TTD) and the time to resolve (TTR).  

#### Latency (Request Service Time)
Latency is the time it takes a system to respond to a request. Both successful and failed requests have latency and it’s vital to differentiate between the latency of successful and failed requests. For example, an HTTP 500 error, triggered because of a connection loss to the database might be served fast. Although, since HTTP 500 is an error indicating failed request, factoring it into the overall latency will lead to misleading calculations. Alternatively, a slow error can be even worse as it factors in even more latency. Therefore, instead of filtering out errors altogether, keep track of the error latency. Define a target for a good latency rate and monitor the latency of successful requests against failed ones to track the system’s health. 

#### Traffic (User Demand)
Traffic is the measure of how much your service is in demand among users. How this is determined varies depending on the type of business you have. For a web service, traffic measurement is generally HTTP requests per second, while. In a storage system, traffic might be transactions per second or retrievals per second. 

By monitoring user interaction and traffic in the service, SRE teams can usually figure out the user experience with the service and how it’s affected by shifts in the service's demand. 

#### Errors (Rate of Failed Requests)
Error is the rate of requests that fail in any of the following ways: 

Explicitly: for example, HTTP 500 internal server error.
Implicitly: for example, HTTP 200 success response coupled with inaccurate content.
By policy: for example, as your response time is set to one second, any request that takes over one second is considered an error.
SRE teams can monitor all errors across the system and at individual service levels to define which errors are critical and which are less severe. By identifying that, they determine the health of their system from the user’s perspective and can take rapid action to fix frequent errors.

#### Saturation (Overall Capacity of the System)
Saturation refers to the overall capacity of the service or how “full” the service is at a given time. It signifies how much memory or CPU resources your system is utilizing. Many systems start underperforming before they reach 100% utilization. Therefore, setting a utilization target is critical as it will help ensure the service performance and availability to the users.

An increase in latency is often a leading indicator of saturation. Measuring your 99th percentile response time over a small time period can provide an early indicator of saturation. For example, a 99th percentile latency of 60 ms indicates that there's a 60 ms delay for every one in 100 requests. 

### Troubleshooting various components of the system to find the root cause and fix the problem.
Alerting the response team about an incident when the signals drop too low, so they can identify the problem and work towards its remediation.

Capacity planning to consistently monitor and improve things over time.
The broad idea is to use your current alerting methods on the signals and track the progress. However, it’s harder to alert using the golden signals as they don’t exactly have a static alerting threshold. Ideally, you should use static thresholds (such as high CPU usage and low memory) but set them realistically to avoid false alerts. For example, the latency of more than 10 seconds, error rates over three per second, etc. 

*Basic alerts* normally compare the threshold against the average values, but we recommend using percentile or median values. Median values are less sensitive to outliers (big and small) and they reduce the probability of false alerts. In contrast, percentiles show how significant a given value is.

*Anomaly Detection*
Basic alerting is good enough in normal circumstances, but ideally, you want to use anomaly detection to catch unusual behavior, fast. For example, if your web traffic is 5 times higher at 3 am or drops down to zero in the middle of the day. Besides catching anomalies, it also sets tighter alerting bands to find issues faster than the static thresholds. 

In theory, anomaly detection sounds easy enough, but it can be challenging. Since it's a fairly new concept, few on-premise monitoring systems currently provide the option. Tools like Prometheus, InfluxDB, DataDog, and SignalFx are some of the tools that offer anomaly detection. 

### Service Level Concepts

#### Service Level Indicators (SLIs)
Quantitative measurements of service performance, such as request latency, error rate, or throughput.

#### Service Level Objectives (SLOs)
Target values or ranges for SLIs that define the expected level of service reliability. For example: "99.9% of requests should complete in under 200ms."

#### Service Level Agreements (SLAs)
Formal commitments made to customers about service availability and performance, often with consequences for not meeting them.

### Beyond The Golden Signals
Golden signals are a great first step towards understanding and improving incident response. However, many organizations are employing proactive measures to learn more about their system. That includes running simulations to test their system and prepare engineers for various scenarios. These techniques are a great way for SRE teams to learn more about the system and use the information to make it even more reliable. 

#### Chaos Engineering 
Chaos engineering is a discipline that involves running experiments on a system to identify its weak spots and potential points of failure. Netflix practices creating failures using the Chaos Monkey - a tool invented by Netflix in 2011 to test the resilience of its IT infrastructure. It works by terminating random VM (virtual machines) instances and containers running in the production environment. This allows teams to see what would happen if these failures really occurred and practice their responses.

#### Game Day 
Gameday is another technique that involves simulating a failure event to test the system, processes, and the team’s response. Unlike chaos engineering, game days are geared towards understanding the people and helping them prepare for big failure events. It’s used by many tech giants including Amazon to improve incident response. 

#### Synthetic User Monitoring 
Synthetic monitoring is the practice of monitoring your application by simulating users. It enables teams to create artificial users and simulate user behavior to determine their behavior flows. That way, teams can learn more about how the system responds under pressure.

### Best Practices

1. **Implement comprehensive instrumentation**: Instrument your applications from the start
2. **Use structured logging**: Make logs machine-readable with consistent formats (JSON)
3. **Set up meaningful alerts**: Alert on symptoms, not causes, and avoid alert fatigue
4. **Create actionable dashboards**: Design dashboards for specific audiences and use cases
5. **Practice observability-driven development**: Build observability into your applications
6. **Establish SLOs**: Define and track what reliability means for your services
7. **Monitor the full stack**: Include infrastructure, applications, and business metrics
8. **Implement distributed tracing**: Essential for microservices architectures

### Resources

| Resource | Notes |
| --- | ----------- |
| [Google SRE Book - Monitoring](https://sre.google/sre-book/monitoring-distributed-systems/) | Google's best practices for monitoring distributed systems |
| [Prometheus Tutorial](https://youtu.be/h4Sl21AKiDg) | TechWorld with Nana provides a complete introduction to Prometheus |
| [Grafana Tutorial for Beginners](https://youtu.be/9TJx7QTrTyo) | Learn how to create beautiful dashboards with Grafana |
| [OpenTelemetry Getting Started](https://opentelemetry.io/docs/getting-started/) | Official OpenTelemetry documentation to start instrumenting your applications |
| [ELK Stack Tutorial](https://youtu.be/gS_nHTWZEJ8) | Complete guide to the ELK Stack for log management |
| [Introduction to Tracing : OpenTelemetry & Opentracing](https://youtu.be/idDu_jXqf4E) | ThatDevOps Guy tells what Tracing is, and some of the terminology around distributed tracing as well as a demo of an opentracing implementation in a microservice architecture. |
| [Datadog Learning Center](https://learn.datadoghq.com/) | Official Datadog tutorials and courses |
| [The Art of Monitoring](https://artofmonitoring.com/) | Comprehensive book on modern monitoring practices |
| [The Three Pillars of Observability](https://www.oreilly.com/library/view/distributed-systems-observability/9781492033431/ch04.html) | O'Reilly's comprehensive guide to observability pillars |

**[⬆️ Back to Top](#table-of-contents)**

## Popular Observability Tools

### Prometheus
[Prometheus](https://prometheus.io/) is an open-source monitoring and alerting toolkit designed for reliability and scalability. It collects metrics from configured targets at given intervals, evaluates rule expressions, and can trigger alerts if conditions are met.

**Key Features:**
- Time-series database optimized for metrics
- Powerful query language (PromQL)
- Pull-based metric collection
- Service discovery integration
- Excellent for Kubernetes monitoring

### Grafana
[Grafana](https://grafana.com/) is an open-source analytics and visualization platform that integrates with various data sources including Prometheus, Elasticsearch, and many others. It's the de facto standard for creating beautiful, interactive dashboards.

**Key Features:**
- Rich visualization options
- Supports multiple data sources
- Customizable dashboards
- Alerting capabilities
- Large community and plugin ecosystem

### ELK Stack (Elasticsearch, Logstash, Kibana)
The ELK Stack is a powerful collection of open-source tools for log management and analysis.

- **Elasticsearch**: Search and analytics engine for storing and querying logs
- **Logstash**: Data processing pipeline for ingesting, transforming, and forwarding logs
- **Kibana**: Visualization layer for exploring and analyzing log data

### Datadog
[Datadog](https://www.datadoghq.com/) is a comprehensive cloud-based monitoring and analytics platform that provides full-stack observability.

**Key Features:**
- Infrastructure monitoring
- Application Performance Monitoring (APM)
- Log management
- Network monitoring
- Security monitoring
- Unified platform for metrics, traces, and logs

### New Relic
[New Relic](https://newrelic.com/) is an enterprise-grade observability platform that offers deep insights into application performance and user experience.

**Key Features:**
- Full-stack observability
- Real-time monitoring
- AI-assisted analysis
- Custom dashboards and alerting

### Jaeger
[Jaeger](https://www.jaegertracing.io/) is an open-source distributed tracing platform originally developed by Uber. It helps monitor and troubleshoot transactions in complex distributed systems.

### OpenTelemetry
[OpenTelemetry](https://opentelemetry.io/) is a collection of tools, APIs, and SDKs for generating, collecting, and exporting telemetry data (metrics, logs, and traces). It's vendor-neutral and has become the industry standard for instrumentation.

**[⬆️ Back to Top](#table-of-contents)**

## Tools for Teams and Collaboration
  * [Aha](https://www.aha.io) - Learn what customers want, create a **visual roadmap**, and build prototypes and applications
  * [Braid](https://www.braidchat.com/) - Chat app designed for teams. Free for public access group, unlimited users, history, and integrations. also, it provides a self-hostable open-source version.
  * [Calendly](https://calendly.com) - Calendly is the tool for connecting and scheduling meetings. The free plan provides 1 Calendar connection per user and Unlimited sessions. Desktop and Mobile apps are also offered.
  * [cally.com](https://cally.com/) - Find the perfect time and date for a meeting. Simple to use, works great for small and large groups.
  * [cDox](https://cdox.ca) - Private document editor hosted in Canada. Write, format, collaborate, and publish documents with clean public links. Data is never used for AI training. Free plan includes 50 MB storage, up to 3 public links, and export to PDF, Word, and Markdown.
  * [Chanty.com](https://chanty.com/) - Chanty is another alternative to Slack. It has a free forever plan for small teams (up to 10) with unlimited public and private conversations, searchable history, unlimited 1:1 audio calls, unlimited voice messages, ten integrations, and 20 GB storage per team.
  * [Discord](https://discord.com/) - Chat with public/private rooms. Markdown text, voice, video, and screen sharing capabilities. Free for unlimited users.
  * [Dubble](https://dubble.so/) - Free Step-by-Step Guide creator. Take screenshots, document processes and colloborate with your team. Also supports async screen recording.
  * [Duckly](https://duckly.com/) - Talk and collaborate in real time with your team. Pair programming with IDE, terminal sharing, voice, video, and screen sharing. Free for small teams.
  * [element.io](https://element.io/) - A decentralized and open-source communication tool built on Matrix. Group chats, direct messaging, encrypted file transfers, voice and video chats, and easy integration with other services.
  * [evernote.com](https://evernote.com/) - Tool for organizing information. Share your notes and work together with others
  * [Fibery](https://fibery.io/) - Connected workspace platform. Free for single users, up to 2 GB disk space.
  * [Fibo](https://fibo.dev) - A free online realtime scrum poker tool for agile teams that lets unlimited members estimate story points for faster planning.
  * [Fizzy](https://www.fizzy.do/) - Kanban-based platform for project management and issue tracking. Create public boards, set up webhooks, use card stamping, and track unlimited users - free for up to 1000 items.
  * [flat.social](https://flat.social) - Interactive customizable spaces for team meetings & happy hours socials. Unlimited meetings, free up to 8 concurrent users.
  * [flock.com](https://flock.com) - A faster way for your team to communicate. Free Unlimited Messages, Channels, Users, Apps & Integrations
  * [GitBook](https://www.gitbook.com/) - Platform for capturing and documenting technical knowledge - from product docs to internal knowledge bases and APIs. Free plan for individual developers.
  * [GitDailies](https://gitdailies.com) - Daily reports of your team's Commit and Pull Request activity on GitHub. Includes Push visualizer, peer recognition system, and custom alert builder. The free tier has unlimited users, three repos, and 3 alert configs.
  * [gitter.im](https://gitter.im/) - Chat, for GitHub. Unlimited public and private rooms, free for teams of up to 25
  * [gokanban.io](https://gokanban.io) - Syntax-based, no registration Kanban Board for fast use. Free with no limitations.
  * [Hackmd.io](https://hackmd.io/) - Real time collaboration & writing tool for markdown format docs/files. Like Google Docs but for markdown files. Free unlimited number of "notes", but the number of collaborators (invitee) for private notes & template [will be limited](https://hackmd.io/pricing).
  * [HeySpace](https://hey.space) - Task management tool with chat, calendar, timeline and video calls. Free for up to 5 users.
  * [Huly](https://huly.io/) - All-in-One Project Management Platform (alternative to Linear, Jira, Slack, Notion, Motion) - unlimited users, 10GB storage per workspace, 10GB video(audio) traffic.
  * [Keybase](https://keybase.io/) - Keybase is a FOSS alternative to Slack; it keeps everyone's chats and files safe, from families to communities to companies.
  * [meet.jit.si](https://meet.jit.si/) - One-click video conversations, and screen sharing, for free
  * [Miro](https://miro.com/) - Scalable, secure, cross-device, and enterprise-ready collaboration whiteboard for distributed teams. With a freemium plan.
  * [Notion](https://www.notion.so/) - Notion is a note-taking and collaboration application with markdown support that integrates tasks, wikis, and databases. The company describes the app as an all-in-one workspace for note-taking, project management and task management. In addition to cross-platform apps, it can be accessed via most web browsers.
  * [paste.sh](https://paste.sh/) - This is a JavaScript and the Crypto based simple paste site.
  * [Pastefy](https://pastefy.app/) - Beautiful and simple Pastebin with optional Client-Encryption, Multitab-Pastes, an API, a highlighted Editor and more.
  * [Pendulums](https://pendulums.io/) - Pendulums is a free time tracking tool that helps you manage your time in a better manner with an easy-to-use interface and valuable statistics.
  * [Proton Pass](https://proton.me/pass) - Password manager with built-in email aliases, 2FA authenticator, sharing and passkeys. Available on web, browser extension, and mobile app and desktop.
  * [Pullflow](https://pullflow.com) - Pullflow offers an AI-enhanced platform for code review collaboration across GitHub, Slack, and VS Code.
  * [Pumble](https://pumble.com) - Free team chat app. Unlimited users and message history, free forever.
  * [Quidlo Timesheets](https://www.quidlo.com/timesheets) - A simple timesheet and time tracking app for teams. The free plan has time tracking and generating reports features for up to 10 users.
  * [Revolt.chat](https://revolt.chat/) - An OpenSource alternative for[Discord](https://discord.com/), that respects your privacy. It also have most proprietary features from discord for free. Revolt is a all in one application that is secure and fast, while being 100% free. every features are free. They also have (official & unofficial) plugins support unlike most main-stream chatting applications.
  * [Rocket.Chat](https://rocket.chat/) - Open-source communication platform with Omnichannel features, Matrix Federation, Bridge with others apps, Unlimited messaging, and Full messaging history.
  * [Screen Sharing via Browser](https://screensharing.net) - Free screen sharing tool, share your screen with collabrators right from your browser, no download or registration needed. For free.
  * [seafile.com](https://www.seafile.com/) - Private or cloud storage, file sharing, sync, discussions. The cloud version has just 1 GB
  * [SiteDots](https://sitedots.com/) - Share feedback for website projects directly on your website, no emulation, canvas or workarounds. Completely functional free tier.
  * [Slab](https://slab.com/) - A modern knowledge management service for teams. Free for up to 10 users.
  * [slack.com](https://slack.com/) - Free for unlimited users with some feature limitations
  * [StatusPile](https://www.statuspile.com/) - A status page of status pages. Could you track the status pages of your upstream providers?
  * [Stickies](https://stickies.app/) - Visual collaboration app used for brainstorming, content curation, and notes. Free for up to 3 Walls, unlimited users, and 1 GB storage.
  * [talky.io](https://talky.io/) - Free group video chat. Anonymous. Peer‑to‑peer. No plugins, signup, or payment required
  * [Teamcamp](https://www.teamcamp.app) - All-in-one project management application for software development companies.
  * [Teamhood](https://teamhood.com/) - Free Project, Task, and Issue-tracking software. Supports Kanban with Swimlanes and full Scrum implementation. Has integrated time tracking. Free for five users and three project portfolios.
  * [Teamplify](https://teamplify.com) - improve team development processes with Team Analytics and Smart Daily Standup. Includes full-featured Time Off management for remote-first teams. Free for small groups of up to 5 users.
  * [Telegram](https://telegram.org/) - Telegram is for everyone who wants fast, reliable messaging and calls. Business users and small teams may like the large groups, usernames, desktop apps, and powerful file-sharing options.
  * [Tencent RTC](https://trtc.io/) - Tencent Real-Time Communication (TRTC) offers solutions for group audio/video calls.10,000 free minutes/month for the first year.
  * [TimeCamp](https://www.timecamp.com/) - Free time tracking software for unlimited users. Easily integrates with PM tools like Jira, Trello, Asana, etc.
  * [tldraw.com](https://tldraw.com) -  Free open-source white-boarding and diagramming tool with intelligent arrows, snapping, sticky notes, and SVG export features. Multiplayer mode for collaborative editing. Free official VS Code extension available as well.
  * [transfernow](https://www.transfernow.net/) - simplest, fastest and safest interface to transfer and share files. Send photos, videos and other large files without a manditory subscription.
  * [Tugboat](https://tugboat.qa) - Preview every pull request, automated and on-demand. Free for all, complimentary Nano tier for non-profits.
  * [userforge.com](https://userforge.com/) - Interconnected online personas, user stories and context mapping.  Helps keep design and dev in sync free for up to 3 personas and two collaborators.
  * [Visual Debug](https://visualdebug.com) - A Visual feedback tool for better client-dev communication
  * [Webex](https://www.webex.com/) - Video meetings with a free plan offering 40 minutes per meeting with 100 attendees.
  * [Webvizio](https://webvizio.com) - Website feedback tool, website review software, and bug reporting tool for streamlining web development collaboration on tasks directly on live websites and web apps, images, PDFs, and design files.
  * [whereby.com](https://whereby.com/) - One-click video conversations, for free (formerly known as appear.in)
  * [windmill.dev](https://windmill.dev/) - Windmill is an open-source developer platform to quickly build production-grade multi-step automation and internal apps from minimal Python and Typescript scripts. As a free user, you can create and be a member of at most three non-premium workspaces.
  * [wormhol.org](https://www.wormhol.org/) - Straightforward file sharing service. Share unlimited files up to 5GB with as many peers as you want.
  * [Wormhole](https://wormhole.app/) - Share files up to 5GB with end-to-end encryption for up to 24hours. For files larger than 5 GB, it uses peer-to-peer transfer to send your files directly.
  * [zoom.us](https://zoom.us/) - Secure Video and Web conferencing add-ons available. The free plan is limited to 40 minutes.
  * [Zulip](https://zulip.com/) - Real-time chat with a unique email-like threading model. The free plan includes 10,000 messages of search history and File storage up to 5 GB. also, it provides a self-hostable open-source version.

**[⬆️ Back to Top](#table-of-contents)**
