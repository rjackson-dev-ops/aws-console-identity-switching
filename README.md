# Ideas and Stratgies for AWS Console Identity Switching
Ideas and strategies to handle AWS console access across multiple accounts.

## The Session/Cookie Problem

AWS uses sessions and cookies to determine your current identity.

Usually each browser window can only work wth one account/identity at a time.

So if you have many AWS accounts to work with, it can be tedious logging in and out over and over all day.

Site Specific Browser apps like Epichrome and Firefox Multicontainer can help
manage your workload.
## Definitions
- SSB : Site Specific Browsers
- AWS Idenity : IAM User, IAM Role, Federation Role, etc..

## Helpful AWS Chrome Extensions
### AWS Extend Switch Roles
Allows you to easily switch AWS roles/profiles.

- Supports the Sync feature on all sorts of browsers
- Not support switching between AWS accounts you sign into with AWS SSO or SAML solution providers directly

### Tab Resize - split screen layouts
Great for resizing browsing windows.

### FreshStart - Cross Browser Session Manager
- Save multiple windows into a single session
- Save all open tabs to a new session, or hand select what to be saved

### Tab-Snap
Easy to copy tabs between windows.

### Password Manager of Choice
I use Roboform

## Helpful AWS Firefox Extensions
### AWS Extend Switch Roles
Allows you to easily switch AWS roles/profiles.

- Supports the Sync feature on all sorts of browsers
- Not support switching between AWS accounts you sign into with AWS SSO or SAML solution providers directly

### Window Layout Resizer
Great for resizing browsing windows.

### Tab Session Manager

### Tab Stash

### Password Manager of Choice
I use Roboform

## Tabs You May Need in Each Window
I also usually bookmark this sites too.

1) Google Advanced Search  
[Google Search](https://www.google.com/advanced_search?hl=en&num=100)

2) Project Management Tab
- JIRA
- Asana  
[Asana](https://app.asana.com)

3) Github Search Window  
[Github Search](https://github.com/search/advanced)

4) Github  
[github](https://github.com/)

5) Client Github URL  
https://github.thebestclient.com

6) Other ??   

7) AWS Console URL for Stelligent/Client
- Your AWS URL
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

## Other Tools

### Divvy
Window management on Mac/Windows.
[Divvy](https://mizage.com/windivvy/)
