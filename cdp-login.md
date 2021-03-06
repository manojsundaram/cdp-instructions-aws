# Log In, Accept Terms, Add New Users

You would have received a welcome email from Cloudera with a link to CDP.  By
default CDP uses to my.cloudera.com for Single Sign On, which means:
* You can use your Cloudera support login to login to CDP
* If any user wants to connect to your CDP, all they need to do is self-register
on my.cloudera.com

On first login, you also may need to accept terms - which you can also find 
[here](https://www.cloudera.com/terms-conditions/). 


Of course, in a production deployment you can cut this link to my.cloudera.com and use your corporate SAML-based Identity Provider (instructions [here](https://docs.cloudera.com/management-console/cloud/user-management/topics/mc-configuring-your-enterprise-idp-to-work-with-cdp-as-a-service-provider.html)).


NOTE: If you don't see new users when you browse to User Management in the CDP Management Console, it probably is because they haven't logged in yet. The CDP user object is created only after first login to the Management Console. CDP does offer a [bulk pre-load option](https://docs.cloudera.com/management-console/cloud/user-management/topics/mc-importing-or-uploading-users.html) after you've connected your corporate ID Provider. 

