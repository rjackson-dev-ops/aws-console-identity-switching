# Ideas and Stratgies for AWS Console Identity Switching
Ideas and strategies to handle AWS console access across multiple accounts.

## Definitions
- SSB : Site Specific Browsers
- AWS Idenity : IAM User, IAM Role, Federation Role, etc..
## The Session/Cookie Problem

AWS uses sessions and cookies to determine your current identity.

Usually each browser window can only work wth one account/identity at a time.

## Chrome/Firefox Extensions
## AWS Extend Switch Roles

## Tabs You May Need in Each Window

1) Google Advanced Search  
https://www.google.com/advanced_search?hl=en&num=100 

2) Project Management Tab
- JIRA
- Asana  
https://app.asana.com

3) Github Search Window  
https://github.com/search/advanced

4) Github  
https://github.com/

5) Client Github URL  
https://github.thebestclient.com

6) Other ??   

7) AWS Console URL for Stelligent/Client
- Landing zone : https://stelligent-sso.awsapps.com/start 
- Stelligent Labs : https://stelligentlabs.signin.aws.amazon.com/console

## Example SSB Strategies

### AWS Networking
1) Regional Networking Role
2) Workload Networking Role
3) Tools Account Role
4) CTower Role

### Organizational Roles
1) Admin
2) Billing
3) Engineers