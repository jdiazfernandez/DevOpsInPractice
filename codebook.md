## P01 TOO MUCH TIME FOR RELASING
● P01a: need of being more agile, rapid: Too much time for releasing new features into production. Need to reduce time to market, need of being more agile/rapid to adapt to market needs (demands) either new features or updates. Business demands more velocity that the velocity teams can offer. Too much time deploying, delivering, releasing new features and/or hotfixes. (If releasing takes too long, so you run the risk that the product is unsatisfactory). =Accelerate time to market = Accelerate value delivery = Faster time to market. = Rapid customer response. 
● P01b: need of rapid and continuous feedback loops from ops to dev Feedback from customers/market (or other systems) are demanding to development (e.g. feedback to the backlog). Until the delivery of the product in pre-production/production environments (operation) there is almost no feedback to dev. Thus, there is no rapid and continuous feedback loops with small deliveries.
● P01c: releases cannot stop production Releases and specially hotfixes cannot stop production. Production should work 24/7 (i.e. deploy hotfixes at runtime).
● P01d: the team has not skills for continuous integration and delivery (CI/CD) The team does not have skills (training) for integrating software frequently, repeatedly (CI) and having deployable software into de master/trunk branch of the version control, ready to be released. *CI continuous integration, *CD continuous delivery OR continuous deployment

## P02 PROBLEMS WHEN RELEASING NEW VERSIONS
● P02a: need of higher quality (released) products/services Need of releasing software with the least number of errors/bugs possible, improve user experience, or improve other quality metrics.
● P02b: need of higher quality deployments Need of putting software into production with quality guarantees, control, etc.
● P02c: releasing problems Problems for a release to arrive correctly. Releasing (delivery) failures; the deployment pipeline fails (is broken); or software is released/delivered but there are problems the generate claims of clients.
● P03 TOO MUCH TIME SPENT ON SETTING UP ENVIRONMENTS
● P03a: need of automate the infrastructure creation/configuration Automating infrastructure is necessary because allows replication and ensures the consistency of environments because changes are replicated everywhere automatically.
● P03b: operations are not sized for assisting dev requirements (bottleneck) Operations is not sized, scaled, for assisting dev requirements (requirements of infrastructure from developers, projects, etc.) and it becomes a bottleneck
● P03c: sharing environments by different teams generates conflicts Sharing environments by different teams generates conflicts, e.g. disagreement in configuration changes on these environments
● P03d: ticketing systems for configuring environments (bottleneck) Developers request configuring new environments (or updating existing ones) but their request is enqueued and they don't know when it will be processed. The whole company requests environments on this way and operations may become a bottleneck. This system of ticketing is inefficient because of the miscommunication between developers and operators.
● P03e: too much time on configuring environments Too much time on configuring new environments on updating existing environments

## P04 SYSTEM DOWNTIME
● P04a: system downtime

## P05 BARRIERS TO INNOVATION/EXPERIMENTATION
● P05a: the team do not have autonomy (flexibility) to make decisions
● P05b: the team has external dependencies to innovate or introduce changes External dependencies to the (devops) team refer to managers or other teams (security, ddbb, qa, etc.) who take decisions, and this slows changes (innovation and experimentation)

## P06 ORGANIZATIONAL/CULTURAL SILOS
● P06a: biz & dev & ops have different goals (business or functional requirements) Dev & Ops have different goals, expectative, pursue different objectives, even different from business. Ops do not know business (functional requirements) until they have to operate the software. Dev do not know operational requirements before developing software. *goals /expectations: business or functional requirements.
● P06b: dev & ops have different mindset Dev & Ops have mindset, ways of working (methodologies) and even tools.
● P06c: information/knowledge silos A silo between the knowledge from Dev and the knowledge from Ops
● P06d: organizational silos Organizational silos due matrix or departmental structures (and the large number of departments), the (large) size of the organization, etc.

## P07 PROBLEMS (LACK) OF COLLABORATION BETWEEN DEV & OPS
● P07a: problems/lack of collaboration/sync Problems or lack of collaboration/sync between dev & ops
● P07b: problems/lack of communication Problems or lack of communication and understanding between dev & ops
● P07c: problems/lack of transparency Problems or lack of transparency between dev & ops. E.g. Ops does not know what Dev developed until they have to deploy it.

## P08 LACK OF END-TO-END VISION OF VALUE STREAM
● P08a: non-shared (end-to-end) responsibility Teams do not share end-to-end responsibility (non-collective ownship), i.e. do not have end-to-end vision of value stream. Ops do not know about dev / do not share responsibility with dev and vice versa. 
● P08b: the deployment process is unknown Developers do not know anything (o very little) about the deployment process. Need for deeper knowledge of the deployment process.

## P09 LACK OF STANDARIZATION AND/OR AUTOMATION
● P09a: complex processes Complexity of building OR/AND testing OR/AND integration OR/AND deploying OR/AND releasing processes
● P09b: lack of infrastructure automation Lack / need of infrastructure automation (on premise or datacenters, cloud, virtual machines, containers, etc.) and/or dynamic provisioning of this infrastructure.
● P09c: lack of processes automation Lack / need of an automated process for building OR/AND testing OR/AND integration OR/AND deploying OR/AND releasing software. Manual deployments generate some problems/failures and has associated a high cost.
● P09d: lack of standardized technology stacks, infrastructure, process, methodologies Lack / need of standardized technology stacks, methodologies, etc.
● P09e: lack of version control
● P09f: need of more efficient deployment Deployment process = production process = put into production
● P09g: need of more efficient teams

## P10 DIGITAL TRANSFORMATION DRIVERS
● P10a: agile & lean drivers
● P10b: clients/market demands This is the case of IT consulting organizations, which have to satisfy client requirements/demands or market trends
● P10c: digital transformation or technological obsolescence An organization has to guarantee its overall service or has major problems with the technology stack (is obsolete) that lead the organization to a digital transformation (a new platform, a new stack, etc.). The organization faces this digital transformation by adopting DevOps (mainly for automation).
● P10d: large architectural changes An organization has major problems with the current systems architecture that lead the organization to a digital transformation (mainly related to architecture, e.g. from monolithic architectures to microservices architectures, or migration of legacy systems). The organization faces this digital transformation by adopting DevOps (by changing methodologies, culture, practices, etc.).
● P10e: large infrastructure changes An organization has major problems with the current infrastructure that lead the organization to a digital transformation (mainly related to infrastructure, e.g. virtualization, containerization, cloud, etc.). The organization faces this digital transformation by adopting DevOps (because they think that DevOps will help them to increase dev & ops collaboration and understanding, rapid feedback, etc.).
● P10f: large organizational changes An organization has major problems with the externalization of software constructions that lead the organization to a digital transformation (having an own and internal software development). The organization faces this digital transformation by adopting DevOps (good practices).
