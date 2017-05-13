# Open Source Bots for Cisco Spark 🤖

This reposistory represents a listing of Open Source Bots that have been contributed by the [Cisco Spark for Developers](https://developer.ciscospark.com) community.

We understand that there is no one size fits all solution when it comes to Bots and Integrations. Some customers will choose extend the functionality of Spark using the [Spark Depot](https://depot.ciscospark.com) directly, while others will use an Application Integration service such as Built.io or Kore.ai. While others will opt to build and host their own Bots.

This project is designed to address that need, this repository contains free and open source Bot projects for various enterprise applications.

- [x] Free, Open Source and completely customisable
- [x] Easy to Deploy in your preffered environment with a Dockerfile and add to Heroku button included in every repository
- [x] New functionality based on community contributions

### Best Practice

We recommend following the considerations.

- Use a UUID as the Bot address for anonymity 
- [Restrict the Bot to a specific room](https://developer.ciscospark.com/webhooks-explained.html)
- Make the Bot only respond to specific email domain or Cisco Spark organisation, you can see an [example](https://github.com/howdyai/botkit/blob/master/docs/readme-ciscospark.md#controller-options) of this here using the Botkit framework
- Use a long, randomly generated Secret to encrypt the Webhook payload (some frameworks will handle this for you)

### Contributing

How to contribute

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.

# Available Bots by Application

- ## JIRA
  - [JIRA by Cisco and Promptworks](https://ciscosparkopensource.github.io/ciscospark-jira/)
  
- ## Service Now
  - [ServiceNow by Cisco and WWT Asynchrony Labs](https://github.com/asynchrony-ringo/spark-botkit-servicenow)
  
- ## Salesforce
  - [Salesforce by Cisco and WWT Asynchrony Labs](https://github.com/asynchrony-ringo/spark-botkit-salesforce)
  
- ## Doorman
  - [Doorman by Cisco and Promptworks](https://github.com/promptworks/ciscospark-doorman)
  
- ## Polling

- ## OnBoarding
