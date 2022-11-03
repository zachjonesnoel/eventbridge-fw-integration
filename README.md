# AWS EventBridge with SaaS integrations
This is a sample repository for demonstrating how AWS EventBridge can integrate with SaaS products, here we are using [Freshworks](https://freshworks.com). 

This demo was presented at [AWS Dev Day Bengaluru 2022](https://pages.awscloud.com/aws-devday-bengaluru-reg.html)

### How to get started

This is built with [AWS SAM CLI](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/what-is-sam.html) and deploy the same with
```
sam deploy -g
```

Before you do this, keep your credentials for Freshdesk handy - 
+ Freshdesk domain
+ Freshdesk API key
+ Your Freshworks SaaS Event bus on AWS EventBridge

To understand API Destinations, a prior understanding of [Freshdesk APIs](https://developers.freshdesk.com/api/) is recommended.

