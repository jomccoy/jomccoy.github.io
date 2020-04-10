---
layout: post
title:  "Get-ADGroupMember"
date:   2020-04-10
categories: Learning
---
{% highlight Powershell %}Import-Moduel ActiveDirectory{% endhighlight %}
{% highlight Powershell %}Get-ADGropuMember -Identity "GroupName" | Select Name, SAMAccountName{% endhighlight %}

<a href="https://docs.microsoft.com/en-us/powershell/module/activedirectory/get-adgroupmember?view=winserver2012-ps">Docs</a href>
