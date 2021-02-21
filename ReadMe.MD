## Overview and Origin

* Name of company:  Ridgeline -- https://www.ridgelineapps.com 

* When was the company incorporated? 2018 headquartered in Tahoe, Nevada.

* Who are the founders of the company?  Dave Duffield (PeopleSoft and Workday founder) 

* How did the idea for the company (or project) come about? Dave is serial software entrepreneur and saw an opportunity in the Investment Management space to build a new platform from the ground up.

* How is the company funded? How much funding have they received? Privately funded  


## Business Activities:

* What specific financial problem is the company or project trying to solve?  Investment Management has been largely dominated by legacy software from companies like SS&C (Advent, Axys), BroadRidge, Sim Corp, BNY Mellon, and others.  Most of these companies have been in the industry for decades and their platforms have morphed through the years to keep pace with the change in the Investment  Management industry.  Some have done this better than others, but all have faced a challenge to modernize their code, while supporting existing customers.  Ridgeline is looking to build a fully cloud-native platform (AWS) with serverless infrastructure, from the ground up. Hence, providing a solution to the outdated software in the Investment Management space. They aim to eliminate the silos (ABOR, IBOR, PBOR) of information that exist and provide a fully integrated platform, acting as a single source of truth for Investment operations. 

* Who is the company's intended customer?  Is there any information about the market size of this set of customers?  Ridgeline is in their infancy and as of this writing has a limited customer base (>10).  As such they are opportunistically approaching Investment Management firms of all sizes to act as use cases for their product. Much of their development is still ongoing and will continue into 2022 for some features. 

What solution does this company offer that their competitors do not or cannot offer? (What is the unfair advantage they utilize?)  Ridgeline's competitive advantage over peers is their lack of existing technology stack and customer base.  Essentially they are "green fielding" their platform and can build on the latest platforms without having to drag legacy code along with them.  In addition, as privately funded company, they are not beholden to share-holder interests or other outside parties who may seek to alter their plans.  If done correctly, this should allow Ridgeline to offer a comprehensive Investment Management solution, that is scalable and "future proof".

* Which technologies are they currently using, and how are they implementing them? (This may take a little bit of sleuthing–– you may want to search the company’s engineering blog or use sites like Stackshare to find this information.)  Ridgeline's technology stack is based on entirely on the AWS cloud-native model.  In this sense, Ridgeline is relying completely on AWS to manage the underlying hardware infrastructure.  Their platform will consume AWS cloud resources (compute, dB's, networking, etc.) allowing them to scale infrastructure to only what is needed.  Ridgeline is constructing their platform from a number of microrservices that work together to provide the comprehensive functionality.  Examples of these microrservices include, search, audit, permissions, trade order management, accounting, and others.  Their code will be optimized for AWS Lambda (event based compute). APIs will be made available to clients and third parties to allow for further integration.  


## Landscape:

* What domain of the financial industry is the company in? Investment Management

* What have been the major trends and innovations of this domain over the last 5-10 years?  Rapid pace of technical change that includes the move to Cloud-Based applications (SaaS), deep learning / AI, process automation, amongst others.  

* What are the other major companies in this domain?  SS&C, Sim Corp, BroadRidge, BNY Mellon, FIS (InvestOne), Black Rock Solutions, State Street, and others. 


## Results

* What has been the business impact of this company so far? No major impact at the moment. Ridgeline is in the process of development for their platform and is recruiting "design partners" to work with them during this phase. 

* What are some of the core metrics that companies in this domain use to measure success? How is your company performing, based on these metrics?  Companies in this domain typical measure success based on client base (total number) and total AUM (assets under management).  As of 2020, Ridgeline has less than 10 customers who have $1 - 67 B in AUM.  

* How is your company performing relative to competitors in the same domain?  As a start-up, Ridgeline is not yet competitive from a revenue perspective. They have a long way to go before they take market share from existing providers.  However, based on their architecture and comprehensive offering, they could be poised to capture a large portion of the IMA market place.


## Recommendations

* If you were to advise the company, what products or services would you suggest they offer? (This could be something that a competitor offers, or use your imagination!)  Based on the projected mapping of Ridgeline's platform, they are offering functionality to support Investment Management from front to back office.  It would be difficult to look at their platform and envision functionality not on their roadmap.  That having been said, I am concerned about their sole reliance on AWS.  Should problems arise, would they be able to migrate their solution to a competing cloud environment (Azure, etc.)?

* Why do you think that offering this product or service would benefit the company? N/A

* What technologies would this additional product or service utilize? N/A

* Why are these technologies appropriate for your solution?  N/A

## Sources

As an employee for an Investment Management firm, I have been actively researching solutions to replace our existing systems.  This has included numerous phone calls and video meetings with various vendors and industry analysts. In addition, I have spent additional time reading vendor marketing material, technial whitepapers and other resources to gain a better understanding of the markets for IMS.

Some of my resources for this case study on Ridgeline include, but are not limited to the following:



Ridgeline Leverages AWS SaaS Factory to Launch Enterprise Platform for Investment Managers | AWS Partner Network (APN) Blog (amazon.com)  : https://aws.amazon.com/blogs/apn/ridgeline-leverages-aws-saas-factory-to-launch-enterprise-platform-for-investment-managers/


AWS Lambda – Serverless Compute - Amazon Web Services : https://aws.amazon.com/lambda/
 

A Single Book Of Record | Ridgeline (medium.com) : https://medium.com/ridgeline/single-book-of-record-blog-post-draft-12ba378f44f0
 

Building The Enterprise Cloud For Investment Managers | Ridgeline (ridgelineapps.com) 


"Investment Accounting Soluctions IMA " 2018 Cutter Associates - John Chandler and Bob Ruck

