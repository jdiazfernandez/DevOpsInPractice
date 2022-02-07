## P01 TOO MUCH TIME FOR RELEASING
● P01a: need for being more agile, rapid — Too much time for releasing new features into production. Need to reduce time to market, need for being more agile/rapid to adapt to market needs (demands) either new features or updates. Business demands more velocity that the velocity teams can offer. Too much time deploying, delivering, releasing new features and/or hotfixes. (If releasing takes too long, you run the risk that the product is unsatisfactory). =Accelerate time to market = Accelerate value delivery = Faster time to market. = Rapid customer response.  

● P01b: need for rapid and continuous feedback loops from ops to dev — Feedback from customers/market (or other systems) are demanding to developers (e.g. feedback to the backlog). Until the delivery of the product in pre-production/production environments (operation) there is almost no feedback to dev. Thus, there is no rapid and continuous feedback loops with small deliveries.

● P01c: releases cannot stop production — Releases and specially hotfixes cannot stop production. Production should work 24/7 (i.e. deploy hotfixes at runtime).

● P01d: the team does not have skills for continuous integration and delivery (CI/CD) — The team does not have skills (training) for integrating software frequently, repeatedly (CI) and having deployable software into de master/trunk branch of the version control, ready to be released. 
*CI continuous integration*
*CD continuous delivery OR continuous deployment*

## P02 PROBLEMS WHEN RELEASING NEW VERSIONS
● P02a: need for higher quality (released) products/services — Need for releasing software with the least number of errors/bugs possible, improve user experience, or improve other quality metrics.

● P02b: need for higher quality deployments — Need for putting software into production with quality guarantees, control, etc.

● P02c: releasing problems — Problems for a release to arrive correctly. Releasing (delivery) failures; the deployment pipeline fails (is broken); or software is released/delivered but there are problems the generate claims of clients.

## P03 TOO MUCH TIME SPENT ON SETTING UP ENVIRONMENTS
● P03a: operations are not sized for assisting dev requirements (bottleneck) — Operations is not sized, scaled, for assisting dev requirements (requirements of infrastructure from developers, projects, etc.), which becomes a bottleneck.

● P03b: sharing environments by different teams generates conflicts — Sharing environments among different teams generates conflicts, e.g. disagreement in configuration changes on these environments.

● P03c: ticketing systems for configuring environments (bottleneck) — Developers request configuring new environments (or updating existing ones) but their request is enqueued and they don't know when it will be processed. The whole company requests environment configurations on this way and operations may become a bottleneck. This system of ticketing is inefficient because of the miscommunication between developers and operators.

● P03d: too much time on configuring environments — Too much time on configuring new environments or updating existing environments.

## P04 SYSTEM DOWNTIME
● P04a: system downtime.

## P05 BARRIERS TO INNOVATION/EXPERIMENTATION
● P05a: the team does not have autonomy (flexibility) to make decisions.

● P05b: the team has external dependencies to innovate or introduce changes — External dependencies on the (devops) team refer to managers or other teams (security, ddbb, qa, etc.) who make decisions, and this slows changes (innovation and experimentation).

## P06 ORGANIZATIONAL/CULTURAL SILOS
● P06a: biz & dev & ops have different goals (business or functional requirements) — Dev & Ops have different goals, expectatives, pursue different objectives, even these goals are different from business. Ops do not know the business requirements (functional requirements) until they have to operate the software. Dev do not know operational requirements before developing software. 

*goals /expectations: business or functional requirements.*

● P06b: dev & ops have different mindsets — Dev & Ops have different mindsets, ways of working (methodologies) and even tools.

● P06c: information/knowledge silos — A silo between the knowledge from Dev and the knowledge from Ops. For example: developers do not know about the tasks of operators and vice versa.

● P06d: organizational silos — Organizational silos due matrix or departmental structures (e.g. development versus operations or infrastructure). Organizational silos due to the large number of departments, the (large) size of the organization, etc.

## P07 PROBLEMS (LACK) OF COLLABORATION BETWEEN DEV & OPS
● P07a: problems/lack of collaboration/sync — Problems or lack of collaboration/sync between dev & ops

● P07b: problems/lack of communication — Problems or lack of communication and understanding between dev & ops

● P07c: problems/lack of transparency — Problems or lack of transparency between dev & ops. E.g. Ops does not know what Dev developed until they have to deploy it.

## P08 LACK OF END-TO-END VISION OF VALUE STREAM
● P08a: non-shared (end-to-end) responsibility — Teams do not share end-to-end responsibility (non-collective ownship), i.e. do not have end-to-end vision of value stream. Ops do not know about Dev, do not share responsibility with Dev and vice versa. 

● P08b: the deployment process is unknown — Developers do not know anything (o very little) about the deployment process. Need for deeper knowledge of the deployment process.

## P09 LACK OF STANDARIZATION AND/OR AUTOMATION
● P09a: complex processes — Complexity of building OR/AND testing OR/AND integration OR/AND deploying OR/AND releasing processes

● P09b: lack of process automation — Lack of or need for an automated process for building OR/AND testing OR/AND integration OR/AND deploying OR/AND releasing software. Manual deployments generate some problems/failures and have a high cost associated.

● P09c: lack of standardized technology stacks, infrastructure, processes, methodologies — Lack of or need for standardized technology stacks, methodologies, etc.

● P09d: lack of version control

● P09e: need for automating infrastructure creation/configuration — Lack of infrastructure automation (on premise or datacenters, cloud, virtual machines, containers, etc.) and/or dynamic provisioning of this infrastructure. Automating infrastructure is necessary because it allows replication and ensures the consistency of environments because changes are replicated everywhere automatically.

● P09f: need for more efficient deployment/production process — The problem is an inefficient deployment process (also known as production process = put into production). 

● P09g: need for more efficient teams

## P10 DIGITAL TRANSFORMATION DRIVERS
● P10a: agile & lean drivers

● P10b: business/market demands or trends — Need to rapidly adapt to business velocity, new business opportunities, or market needs, especially for high variable markets or new service models. Respond to business needs and deal with the competition. Sometimes a trend or hype. This is also the case of IT consulting organizations, which have to satisfy client requirements/demands. 

● P10c: digital transformation or technological obsolescence — An organization has to guarantee its overall service (e.g. functionality, performance, availability, user experience, etc.) or has major problems with the technology stack (is obsolete) or infrastructure (limited physical resources) that lead the organization to a digital transformation (a new platform, a new stack, new infrastructure such as virtualization, containerization, cloud, etc.). The organization faces this digital transformation by adopting DevOps (mainly for increasing automation, dev & ops collaboration, rapid feedback, etc.).

● P10d: large organizational changes — An organization has major problems with the externalization of software constructions that lead the organization to a digital transformation (having an internal software development). The organization faces this digital transformation by adopting DevOps (good practices).

● P10e: large software architectural changes (modernizing legacy applications) — An organization has major problems with current software architecture that lead the organization to a digital transformation (mainly related to architecture, e.g. from monolithic architectures to microservices architectures, or migration of legacy applications). The organization faces this digital transformation by adopting DevOps (by changing methodologies, culture, practices, etc.).

## R01 FASTER TIME-TO-MARKET
● R01a: agile response to customers/market — The emphasis is rapid change adaptation to customers/market needs.

● R01b: fast and continuous integration — Small batch development and commit code to trunk/master frequently (at least, daily) to validate the systems is in a deployable state (green build).

● R01c: faster response of hotfixes 

*A hotfix is a single, cumulative package that is used to address a problem in a software product (i.e., a software bug). A vital fix or correction in software.*

● R01d: faster time-to-market — Accelerate time-to-market (by reducing dev, testing, qa, deployment or delivery time). 

## R02 BETTER SOFTWARE QUALITY
● R02a: better software quality —  Software quality in the more generic sense (e.g. better performance of systems/platforms)

● R02b: reliability, resilience (recoverability), availability  — Reduce bugs/incidents rate 

*Reliability: The target at which software designers have always aimed, i.e. perfect operation all the time. Reliability is the planned outcome.*

*Resiliency: The ability of an app to recover from certain types of failure and yet remain functional from the customer perspective. Resilience is how you achieve the outcome. Resiliency can also be called recoverability.*

## R03 IMPROVE PROCESS PRODUCTIVITY
● R0a3: process automation: efficiency, optimization, productivity — The more automatic the process, the more confidence in the process (more productivity and less errors than manual processes). Process optimization and/or agilization, process more efficient or more productive, mainly due to automatization.

● R03b: project management more effective 

● R03c: reduce IT cost 

## R04 IMPROVE TEAM EFFECTIVENESS & SATISFACTION
● R04a: build trust within the team and between silos  

● R04b: improve team autonomy/flexibility  

● R04c: improve team collaboration & communication  — Break barriers and silos. Improving team collaboration & communication improves the performance of teams. This means that there is no loss of effective work time on tasks that do provide value.
Collaboration (involvement) of dev, ops, qa, security, business (product owner), etc

● R04d: more motivated teams  — Motivation for continuous improvement and retrospective.

## R05 CUSTOMER FOCUS
● R05a: experimentation/innovation — More time for innovate. Less afraid to innovate.

● R05b: fast and continuous feedback  — Fast and better feedback from customer to business and development. As a result of this feedback, companies get fast learning of customer needs, better user experience, and/or better responsiveness to customer needs. 

● R05c: greater value to customers (excellence) — Greater value (explicitly value). Improve customer satisfaction, customer experience. Provide an excellent service to customers.

##  R06 ALIGN THE OBJECTIVES OF DEV & OPS WITH BIZ
● R06a: align objectives with business — Deliver value by aligning DevOps with business objectives. Being operations closer to dev and business.

● R06b: end-to-end vision of value stream — A single stream (end-to-end), from dev to ops, whose result is the product that business wants.
