---
layout: post
title:  "Azure SQL DB -Adding Azure AD Users"
date:   2020-06-05
categories: Azure SQL
---
1.  Create a new Azure SQL Database and Server
2.  Go to all resources and find the <b>SQL Server</b>
<img src="/images/SQLSewrver.JPG">
3. Under settings for the SQL Server, select Active Directory Admin
<img src="/images/AADAdmin.JPG">
4. Click Set admin and search for Active Directory Admin user and save.
5.  Connect to Azure SQL Database with Active Directory Admin account and click new query.
6. Click new query and run the following command
{% highlight SQL %}create user [sql@jomccoy.onmicrosoft.com] from external provider;{% endhighlight %}

