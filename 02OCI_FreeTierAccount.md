![](https://www.suse.com/c/wp-content/uploads/2021/05/oracle-cloud.png)
- Oracle provides Free Tier Account creation for anyone. 
- Some services are free for always. 
- Also provides 300 dollars for 30 days. 
- So if you cross 30 days or $300 then you can't use tha paid service.
- Create your free tier account [here](https://www.oracle.com/in/cloud/free/).
- After creation you can give login [here](https://www.oracle.com/in/cloud/sign-in.html).
- After logging in you can see a nice console, search & go through various services, also set your account, MFA and many more things.
<hr />

- When you create your account using mail id, the `Tenancy Admin` is created. It come under Root Compartment and `Administrators` group. They have highest level access to all resources within that particular tenancy.
- Service limits can be increased by raising the requests.
- The Root Compartment can hold all the resources within your tenancy but the best practice says to create separate compartment for different resources for logical division & granual access .
- A `Tenancy Admin` can create other Admin users such as Service Admins & they can be grouped as Storage admin or network admin. Best Practice says to not use `Tenancy Admin` for every thing in the account rather use other admins. Also to enable MFA for all users.
- Under Identity you can find users, groups, policies, compartments etc.
- The default policy for the `Tenancy Admin` is `Tenant Admin Policy` == manage all resource in that account.
- Root Compartment & some of these things are created by Orcale itself.
