---
title: "Continuous Delivery isn't Continuous Deployment"
date: 2019-12-19T21:08:43Z
draft: false
author: "Ken Mugrage"
---

One of our organizers went to a DevOps book club the other day and was talking the the folks there about DeliveryConf. Something very interesting things, at least to me, came out of that conversation. Many of the people there thought that Continuous Delivery and Continuous Deployment are the same thing. Now, this isn't a new impression for sure, but I didn't expect it from a group of folks getting together to talk about DevOps books.

[Jez Humble](/speakers/jez-humble/) and [Dave Farley](/speakers/dave-farley/), both of whom are speaking at DeliveryConf 2020 in Seattle, wrote the book "Continuous Delivery". On Jez's website, https://www.continuousdelivery.com/ he defines Continuous Delivery as follows...

> Continuous Delivery is the ability to get changes of all types—including new features, configuration changes, bug fixes and experiments—into production, or into the hands of users, safely and quickly in a sustainable way.

Notice that his definition says *the ability* to get changes into production. It does not say that's an automatic thing. 

If you're creating a web application, it might be ok to automatically push to production when all the tests pass. As long as you're taking good care of user experience, it's a great way to get features into the hands of users as soon as possible so that you can start learning from them.

On the other hand, if you work on the Photoshop team at Adobe *please* don't ever go to a model where I need to download and install every good build.

In either case, you should be striving to ensure that you *can* deploy to production at any time. Not just on demand, *at any time*. This allows you to react when (not if) something like a security alert or critical bug or competitor action or any number of other things happen. 

The talks at DeliveryConf will be about Continuous Delivery. Many of the speakers and attendees will have chosen to automate the final release step, and many will not have. 

Don't let the term Continuous Delivery scare you. It doesn't mean every change is going out to your users whether you want it to or not. And come to DeliveryConf, where you'll learn lots of ways even that doesn't have to be scary.

