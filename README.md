# Project 1: BCM Pte Ltd


## Assumption
* BCM Pte Ltd offers a food delivery service to end users on their mobile application
* Experience an increased in traffic during meal hours
* Current software development team is still using the waterfall model for application development
* Company's IT system is still on-premise


## Recommendations

### Implementing a DevOps culture
* Fostering a collaborative culture
	* ensuring that the QA team (Carol), Development team (Jayson) and the Operations team (Edmond) are not siloed from one another, but instead works together and committed to delivering value to their customers
* [Increased revenue](https://www.zdnet.com/article/the-urgency-of-devops/)
	* Organization adopting DevOps practices sees a 60% increased in revenue and profit growth
	* 2.4x more likely than their competitors to be growing at more than 20% rate
* Improved employees productivity 
	* Automation reduces the amount of redundant manual work 
	* DevOps practices have shown to [increase employee productivity by 51%](https://clutch.co/it-services/resources/why-businesses-need-devops-engineers)
* [IImproved agility](https://www.techrepublic.com/article/why-adopting-devops-can-increase-profitability-productivity-and-market-share/) 
	* Companies that have strong DevOps practices are shown to deploy their code 46x more frequently
	* Have a faster lead time of 2555x from commit to deploment of the code
	* They also have a 7x lower change failure rate
	* 2604x faster time in recovering from incidents
* [Improved in customer satisfaction](https://clutch.co/it-services/resources/why-businesses-need-devops-engineers)
	* Companies adopting DevOps experience a 45% improvement in customer satisfaction
	* There is also a [74% increase in customer experience](https://docs.broadcom.com/doc/accelerating-velocity-and-customer-value-with-agile-and-devops-research-paper)
		* Higher Customer experience will result in greater customer loyalty
		* better customer retention
		* Improved sales and ROI
	
	
### Technological components
* Using NoSQL (eg. MongoDB) as the caching/intermediate storage concurrently with their existing SQL as the primary storage
	* For better performance through sharding and reduces the risk of server crashing by having replications
	* And for better horizontal scalability when there is an increased in traffic
* Using GitHub
	* For collaborative works, fostering a culture of continuous experimentation and learning
* Using dockers containers
	* For building lightweight, secure and portable apps
	* Able to do an upgrade of dependencies or framework without worrying about altering what is working now
	* Able to work on any machine
* Using Kubernetes
	* For automation deployment, scaling and managment of containerized apps
	* Jayson no longer has to spend his time troubleshooting production outages and can spend more time mentoring junior staff




